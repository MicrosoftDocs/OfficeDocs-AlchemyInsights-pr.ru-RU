---
title: Получение списка корпоративных приложений
ms.author: v-jmathew
author: v-jmathew
manager: scotv
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004342"
- "9837"
ms.openlocfilehash: f5c1a77e415d4bbaa5718a6668af95934db7e5ae
ms.sourcegitcommit: e5f261f95ffc6074cce89e62ef8c4e9fd519d3ee
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/26/2021
ms.locfileid: "51379915"
---
# <a name="get-a-list-of-enterprise-applications"></a><span data-ttu-id="9c9fc-102">Получение списка корпоративных приложений</span><span class="sxs-lookup"><span data-stu-id="9c9fc-102">Get a list of Enterprise Applications</span></span>

1. <span data-ttu-id="9c9fc-103">Чтобы **получить** список корпоративных приложений (все приложения или фильтруются по имени Display, идентификатору, ИДЕНТИФИКАТОРу идентификатора и т.д.) с помощью команды Powershell, см. в приложении [Get-AzureADApplication (AzureAD).](https://docs.microsoft.com/powershell/module/azuread/get-azureadapplication)</span><span class="sxs-lookup"><span data-stu-id="9c9fc-103">To **get a list of enterprise applications** (all applications or filtered by Display name, ID, Identifier URIs, etc.) through Powershell command, see [Get-AzureADApplication (AzureAD)](https://docs.microsoft.com/powershell/module/azuread/get-azureadapplication).</span></span>
2. <span data-ttu-id="9c9fc-104">Чтобы получить список основных объектов службы (все объекты или фильтруются по ID) с помощью команды Powershell, см. в обзоре [Get-AzureADServicePrincipal (AzureAD).](https://docs.microsoft.com/powershell/module/azuread/get-azureadserviceprincipal)</span><span class="sxs-lookup"><span data-stu-id="9c9fc-104">To get a list of service principal objects (all objects or filtered by ID) through Powershell command, see [Get-AzureADServicePrincipal (AzureAD)](https://docs.microsoft.com/powershell/module/azuread/get-azureadserviceprincipal).</span></span>
3. <span data-ttu-id="9c9fc-105">Если вы хотите получить список приложений, настроенных samL, вам помогут следующие скрипты **PowerShell:**</span><span class="sxs-lookup"><span data-stu-id="9c9fc-105">If you want to **get a list of SAML configured apps, following PowerShell scripts** may help you:</span></span>

    <span data-ttu-id="9c9fc-106">Каждое приложение, в том числе приложение OAuth или SAML (как галереи, так и приложения, не в галерее), будет иметь два объекта, созданных в AAD при их регистрации.</span><span class="sxs-lookup"><span data-stu-id="9c9fc-106">Every Application be it an OAuth app or SAML app (both gallery and non-gallery apps) would have two objects created in AAD when their registration happens.</span></span> <span data-ttu-id="9c9fc-107">Один из них называется объектом приложения, а другой — объектом Service Principal.</span><span class="sxs-lookup"><span data-stu-id="9c9fc-107">One is called the Application Object and the other is the Service Principal object.</span></span> <span data-ttu-id="9c9fc-108">При сбросе свойств основного объекта службы с помощью PowerShell вы найдете, что каждое приложение имеет определенное количество тегов, связанных с ним, как:</span><span class="sxs-lookup"><span data-stu-id="9c9fc-108">When you dump the properties of a Service Principal Object using PowerShell, you would find that every application has a certain number of Tags associated with it like:</span></span>

    - <span data-ttu-id="9c9fc-109">OAuth apps would have a tag called **"WindowsAzureActiveDirectoryIntegratedApp"**</span><span class="sxs-lookup"><span data-stu-id="9c9fc-109">OAuth apps would have a tag called "**WindowsAzureActiveDirectoryIntegratedApp**"</span></span>
    - <span data-ttu-id="9c9fc-110">Приложение SAML Gallery будет иметь тег **"WindowsAzureActiveDirectoryGalleryApplicationPrimaryV1"**</span><span class="sxs-lookup"><span data-stu-id="9c9fc-110">Gallery SAML Apps would have a tag called "**WindowsAzureActiveDirectoryGalleryApplicationPrimaryV1**"</span></span>
    - <span data-ttu-id="9c9fc-111">Non-Gallery SAML Apps would have a tag called **"WindowsAzureActiveDirectoryCustomSingleSignOnApplication"**</span><span class="sxs-lookup"><span data-stu-id="9c9fc-111">Non-Gallery SAML Apps would have a tag called "**WindowsAzureActiveDirectoryCustomSingleSignOnApplication**"</span></span>

    <span data-ttu-id="9c9fc-112">Таким образом, вы можете использовать эти теги и узнать, что это такое приложение.</span><span class="sxs-lookup"><span data-stu-id="9c9fc-112">Hence, you can use these tags and find out what kind of app it is.</span></span> <span data-ttu-id="9c9fc-113">Тег **"WindowsAzureActiveDirectoryIntegratedApp"** является общим для всех типов приложений.</span><span class="sxs-lookup"><span data-stu-id="9c9fc-113">The tag "**WindowsAzureActiveDirectoryIntegratedApp**" is common to all types of apps.</span></span> <span data-ttu-id="9c9fc-114">Вы можете использовать следующий фрагмент, чтобы перечислить все приложения SAML (как в галерее, так и в негалерее):</span><span class="sxs-lookup"><span data-stu-id="9c9fc-114">You can use following snippet to list all the SAML apps (both gallery and non-gallery):</span></span>

    `$type = "SAML APP"`

    `Get-AzureADServicePrincipal -All true | Where-Object {(.Tags -contains "WindowsAzureActiveDirectoryGalleryApplicationNonPrimaryV1") -or (_.Tags -contains "WindowsAzureActiveDirectoryCustomSingleSignOnApplication")} | Select DisplayName, @{Name="AppType"; Expression={type}}_.`

    <span data-ttu-id="9c9fc-115">Дополнительные сведения см. в [видеоролике Определение приложений с поддержкой SAML в Azure AD.](https://docs.microsoft.com/answers/questions/24259/identify-saml-enabled-apps-in-azure-ad.html)</span><span class="sxs-lookup"><span data-stu-id="9c9fc-115">For more information, see [Identify SAML-enabled apps in Azure AD](https://docs.microsoft.com/answers/questions/24259/identify-saml-enabled-apps-in-azure-ad.html).</span></span>

4. <span data-ttu-id="9c9fc-116">**Поиск и список только** веб-приложений: Используйте приведенную ниже команду, чтобы получить все приложения Azure AD с типом приложения "Веб-приложение/API"</span><span class="sxs-lookup"><span data-stu-id="9c9fc-116">**Find and list only Web applications**: Use the below command to get all Azure AD applications with the application type "Web app/API"</span></span>

    <span data-ttu-id="9c9fc-117">Get-AzureADApplication -All:$true | Where-Object { $_. PublicClient -ne $true } | FT</span><span class="sxs-lookup"><span data-stu-id="9c9fc-117">Get-AzureADApplication -All:$true | Where-Object { $_.PublicClient -ne $true } | FT</span></span>
5. <span data-ttu-id="9c9fc-118">**Найдите и перечислить** только приложения Native: запустите следующую команду, чтобы получить все приложения для родных клиентов (настольных компьютеров и мобильных устройств).</span><span class="sxs-lookup"><span data-stu-id="9c9fc-118">**Find and list Native applications alone**: Run the following command to get all the native client (desktop/mobile device) applications.</span></span>

    <span data-ttu-id="9c9fc-119">Get-AzureADApplication -All:$true | Where-Object { $_. PublicClient -eq $true } | FT</span><span class="sxs-lookup"><span data-stu-id="9c9fc-119">Get-AzureADApplication -All:$true | Where-Object { $_.PublicClient -eq $true } | FT</span></span>
6. <span data-ttu-id="9c9fc-120">Экспорт всех зарегистрированных сведений **о приложениях Azure AD в CSV:** ниже команда экспортирует все приложения Azure AD с требуемой подробными сведениями в csv-файл:</span><span class="sxs-lookup"><span data-stu-id="9c9fc-120">**Export All Registered Azure AD Application Details to CSV**: The below command exports all the Azure AD apps with required details to csv file:</span></span>

    - <span data-ttu-id="9c9fc-121">Get-AzureADApplication -All:$true | Select-Object DisplayName, AppID, PublicClient, AvailableToOtherTenants, HomePage, LogoutUrl |</span><span class="sxs-lookup"><span data-stu-id="9c9fc-121">Get-AzureADApplication -All:$true | Select-Object DisplayName, AppID, PublicClient, AvailableToOtherTenants, HomePage, LogoutUrl |</span></span>
    - <span data-ttu-id="9c9fc-122">Export-Csv "C:\AzureADApps.csv" -NoTypeInformation-Encoding UTF8</span><span class="sxs-lookup"><span data-stu-id="9c9fc-122">Export-Csv "C:\AzureADApps.csv" -NoTypeInformation -Encoding UTF8</span></span>

7. <span data-ttu-id="9c9fc-123">**Необходимо экспортировать список неиспользованых приложений Azure** — отчет аудита</span><span class="sxs-lookup"><span data-stu-id="9c9fc-123">**Need to export a list of unused Azure apps** – Audit report</span></span>

    <span data-ttu-id="9c9fc-124">Azure AD может показывать журналы приложений только в течение 30 дней при условии, что у вас есть лицензия Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="9c9fc-124">Azure AD can show application logs for only up to 30 days provided you have Azure AD Premium license.</span></span>
    <span data-ttu-id="9c9fc-125">У вас есть два варианта хранения данных дольше 30 дней.</span><span class="sxs-lookup"><span data-stu-id="9c9fc-125">You have two options to retain the data for longer than 30 days.</span></span> <span data-ttu-id="9c9fc-126">API отчетов [Azure AD](https://docs.microsoft.com/azure/active-directory/reports-monitoring/concept-reporting-api) можно использовать для получения данных программным образом и хранения их в базе данных.</span><span class="sxs-lookup"><span data-stu-id="9c9fc-126">You can use the [Azure AD Reporting APIs](https://docs.microsoft.com/azure/active-directory/reports-monitoring/concept-reporting-api) to retrieve the data programmatically and store it in a database.</span></span> <span data-ttu-id="9c9fc-127">Кроме того, можно интегрировать журналы аудита в сторонние системы SIEM.</span><span class="sxs-lookup"><span data-stu-id="9c9fc-127">Alternatively, you can integrate audit logs into a third party SIEM system.</span></span>

    <span data-ttu-id="9c9fc-128">Вы также можете скачать список приложений для всех приложений и приложений в Azure Active directory>Регистрация приложений>Загрузка>Все приложения и собственные приложения.</span><span class="sxs-lookup"><span data-stu-id="9c9fc-128">You can also download the app list for all applications and owned applications under Azure Active directory>App Registrations>Download>All applications/Owned applications.</span></span>

    <span data-ttu-id="9c9fc-129">Чтобы получить список приложений через MS Graph, см. в приложении [List - Microsoft Graph v1.0](https://docs.microsoft.com/graph/api/application-list) и типе ресурсов приложений - Microsoft Graph [v1.0.](https://docs.microsoft.com/graph/api/resources/application)</span><span class="sxs-lookup"><span data-stu-id="9c9fc-129">To get a list of applications through MS Graph, see [List applications - Microsoft Graph v1.0](https://docs.microsoft.com/graph/api/application-list) and [application resource type - Microsoft Graph v1.0](https://docs.microsoft.com/graph/api/resources/application).</span></span>

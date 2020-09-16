---
title: PowerShell в SharePoint Online
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000266"
- "1867"
ms.openlocfilehash: d90b60de72cf87a56e3b7f6a792708693f31af00
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/15/2020
ms.locfileid: "47770852"
---
# <a name="sharepoint-online-powershell"></a><span data-ttu-id="0d1f7-102">PowerShell в SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="0d1f7-102">Sharepoint Online PowerShell</span></span>

<span data-ttu-id="0d1f7-103">Работаете с PowerShell или сценариями в SharePoint Online?</span><span class="sxs-lookup"><span data-stu-id="0d1f7-103">Working with PowerShell or Scripts within Sharepoint Online?</span></span> <span data-ttu-id="0d1f7-104">Для получения дополнительных сведений посетите приведенные ниже ссылки.</span><span class="sxs-lookup"><span data-stu-id="0d1f7-104">Visit the links below for more information.</span></span>
- [<span data-ttu-id="0d1f7-105">Начало работы с командной консолью SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="0d1f7-105">Getting started with SharePoint Online Management Shell</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps)
- [<span data-ttu-id="0d1f7-106">Подключение к SPO PowerShell с многофакторной проверкой подлинности (MFA)</span><span class="sxs-lookup"><span data-stu-id="0d1f7-106">Connect to SPO PowerShell with multifactor authentication (MFA)</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps#to-connect-with-multifactor-authentication-mfa)
- <span data-ttu-id="0d1f7-107">[Шаблоны и методики SharePoint (PnP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) содержат библиотеку команд PowerShell, которая позволяет выполнять сложные действия по управлению для SPO.</span><span class="sxs-lookup"><span data-stu-id="0d1f7-107">[SharePoint Patterns and Practices (PnP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) contains a library of PowerShell commands that allows you to perform complex management actions towards SPO.</span></span>

> [!NOTE]
> - <span data-ttu-id="0d1f7-108">Если у вас возникли проблемы с подключением к командной консоли SPO, убедитесь, что вы обновили последнюю версию и пытаетесь [повторно импортировать модуль](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) с помощью командлета *"Import-Module Microsoft. Online. SharePoint. PowerShell".*</span><span class="sxs-lookup"><span data-stu-id="0d1f7-108">If you are having issues connecting with the SPO management shell, make sure that you have updated to the latest version and try to [re-import the module](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) using *“Import-Module Microsoft.Online.SharePoint.PowerShell”.*</span></span>
> - <span data-ttu-id="0d1f7-109">При попытке запустить скрипты объектной модели на стороне клиента на локальном компьютере должен быть установлен [пакет SDK для клиентских компонентов SharePoint Online](https://www.microsoft.com/download/details.aspx?id=42038) .</span><span class="sxs-lookup"><span data-stu-id="0d1f7-109">If you are attempting to run client-side object model scripts, you will need to have the [Sharepoint Online Client Components SDK](https://www.microsoft.com/download/details.aspx?id=42038) installed on your local machine.</span></span>
> - <span data-ttu-id="0d1f7-110">Если у вас возникли проблемы с запуском сценариев из PowerShell, вы можете использовать PowerShell от имени администратора и изменить [политику выполнения](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span><span class="sxs-lookup"><span data-stu-id="0d1f7-110">If you are having issues running scripts from PowerShell, you may want to consider running PowerShell as an Administrator and changing the [Execution Policy](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span></span>
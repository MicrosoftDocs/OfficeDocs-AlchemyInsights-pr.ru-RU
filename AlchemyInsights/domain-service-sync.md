---
title: Синхронизация службы доменов
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 01/15/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003245"
- "7922"
- "7921"
ms.openlocfilehash: b35d3a402bc08a27a818209385c5666b901fa524
ms.sourcegitcommit: 83fe2a8d060794fdf58445b469b30a3294b7a9b6
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/15/2021
ms.locfileid: "49876519"
---
# <a name="domain-service-synchronization"></a><span data-ttu-id="6e1aa-102">Синхронизация службы доменов</span><span class="sxs-lookup"><span data-stu-id="6e1aa-102">Domain service synchronization</span></span>

<span data-ttu-id="6e1aa-103">Объекты и учетные данные в управляемом домене доменных служб Azure Active Directory (Azure AD DS) можно создавать локально в домене или синхронизировать с клиентом Azure Active Directory (Azure AD).</span><span class="sxs-lookup"><span data-stu-id="6e1aa-103">Objects and credentials in an Azure Active Directory Domain Services (Azure AD DS) managed domain can either be created locally within the domain, or synchronized from an Azure Active Directory (Azure AD) tenant.</span></span> <span data-ttu-id="6e1aa-104">При первом развертывании Azure AD DS настраивается и инициируется автоматическая синхронизация в одну сторону для репликации объектов из Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6e1aa-104">When you first deploy Azure AD DS, an automatic one-way synchronization is configured and initiated to replicate the objects from Azure AD.</span></span> <span data-ttu-id="6e1aa-105">Эта однонаправная синхронизация продолжает работать в фоновом режиме, чтобы поддерживать управляемый домен Azure AD DS в курсе всех изменений, внесенных в Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6e1aa-105">This one-way synchronization continues to run in the background to keep the Azure AD DS managed domain up-to-date with any changes from Azure AD.</span></span> <span data-ttu-id="6e1aa-106">Синхронизация из Azure AD DS обратно в Azure AD не происходит.</span><span class="sxs-lookup"><span data-stu-id="6e1aa-106">No synchronization occurs from Azure AD DS back to Azure AD.</span></span>

<span data-ttu-id="6e1aa-107">Дополнительные сведения о синхронизации службы домена Azure Active Directory см. в этой [теме.](https://docs.microsoft.com/azure/active-directory-domain-services/synchronization)</span><span class="sxs-lookup"><span data-stu-id="6e1aa-107">For more details on Azure Active Directory domain service synchronization, see [Domain Service Synchronization](https://docs.microsoft.com/azure/active-directory-domain-services/synchronization).</span></span> 

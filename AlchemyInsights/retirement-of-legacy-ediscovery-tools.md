---
title: Выход на пенсию устаревших средств для электронных обнаружений
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001487"
- "3523"
ms.openlocfilehash: 986c78f20e7b8c303c302913d63d817a56ce2896
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/15/2021
ms.locfileid: "51798562"
---
# <a name="retirement-of-legacy-ediscovery-tools"></a><span data-ttu-id="39fc2-102">Выход на пенсию устаревших средств для электронных обнаружений</span><span class="sxs-lookup"><span data-stu-id="39fc2-102">Retirement of Legacy eDiscovery Tools</span></span>

<span data-ttu-id="39fc2-103">В результате новых и улучшенных функций по обнаружению электронных данных в центре соответствия требованиям Microsoft 365 следующие устаревшие средства и командные команды электронной почты будут отправлены в отставку в ближайшие месяцы:</span><span class="sxs-lookup"><span data-stu-id="39fc2-103">As a result of the new and improved eDiscovery functionality in Microsoft 365 Compliance center, the following legacy eDiscovery tools and commandlets will be retired in the coming months:</span></span>

- <span data-ttu-id="39fc2-104">[Открытие электронных данных на месте](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery) и удерживает на месте [в](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds) центре администрирования Exchange.</span><span class="sxs-lookup"><span data-stu-id="39fc2-104">[In-Place eDiscovery](https://docs.microsoft.com/exchange/security-and-compliance/in-place-ediscovery/in-place-ediscovery) and [In-Place Holds](https://docs.microsoft.com/exchange/security-and-compliance/create-or-remove-in-place-holds) in the Exchange admin center.</span></span>

- <span data-ttu-id="39fc2-105">Комлеты Exchange Online PowerShell, которые поддерживают In-Place и In-Place удерживает.</span><span class="sxs-lookup"><span data-stu-id="39fc2-105">The Exchange Online PowerShell cmdlets that support In-Place eDiscovery and In-Place Holds.</span></span> <span data-ttu-id="39fc2-106">(Эти cmdlets совместно определены как \*-MailboxSearch cmdlets.) Это включает в себя следующие cmdlets:</span><span class="sxs-lookup"><span data-stu-id="39fc2-106">(These cmdlets are collectively identified as \*-MailboxSearch cmdlets.) This includes the following cmdlets:</span></span>

    - [<span data-ttu-id="39fc2-107">New-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="39fc2-107">New-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/new-mailboxsearch)
    - [<span data-ttu-id="39fc2-108">Start-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="39fc2-108">Start-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/start-mailboxsearch)
    - [<span data-ttu-id="39fc2-109">Stop-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="39fc2-109">Stop-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/stop-mailboxsearch)
    - [<span data-ttu-id="39fc2-110">Set-MailboxSearch</span><span class="sxs-lookup"><span data-stu-id="39fc2-110">Set-MailboxSearch</span></span>](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance-content-search/set-mailboxsearch)

- <span data-ttu-id="39fc2-111">Комлет [Search-Mailbox](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) в Exchange Online PowerShell.</span><span class="sxs-lookup"><span data-stu-id="39fc2-111">The [Search-Mailbox](https://docs.microsoft.com/powershell/module/exchange/mailboxes/search-mailbox?view=exchange-ps) cmdlet in Exchange Online PowerShell.</span></span>
- <span data-ttu-id="39fc2-112">Следующие операции в API веб-служб Exchange:</span><span class="sxs-lookup"><span data-stu-id="39fc2-112">The following operations in the Exchange Web Services API:</span></span>
    - [<span data-ttu-id="39fc2-113">GetSearchableMailboxes</span><span class="sxs-lookup"><span data-stu-id="39fc2-113">GetSearchableMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getsearchablemailboxes-operation)
    - [<span data-ttu-id="39fc2-114">SetHoldOnMailboxes</span><span class="sxs-lookup"><span data-stu-id="39fc2-114">SetHoldOnMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/setholdonmailboxes-operation)
    - [<span data-ttu-id="39fc2-115">GetHoldOnMailboxes</span><span class="sxs-lookup"><span data-stu-id="39fc2-115">GetHoldOnMailboxes</span></span>](https://docs.microsoft.com/exchange/client-developer/web-service-reference/getholdonmailboxes-operation)

- [<span data-ttu-id="39fc2-116">Advanced eDiscovery v1.0</span><span class="sxs-lookup"><span data-stu-id="39fc2-116">Advanced eDiscovery v1.0</span></span>](https://docs.microsoft.com/microsoft-365/compliance/office-365-advanced-ediscovery)

<span data-ttu-id="39fc2-117">**Сроки выхода на пенсию:**</span><span class="sxs-lookup"><span data-stu-id="39fc2-117">**Timeline for retirement**:</span></span>
- <span data-ttu-id="39fc2-118">**1 июля 2020 г.** Вы больше не можете создавать новые поиски и удерживает, но вы можете запускать, редактировать и удалять существующие поиски на свой собственный риск.</span><span class="sxs-lookup"><span data-stu-id="39fc2-118">**July 1, 2020** You can no longer create new searches and holds, but you can run, edit, and delete existing searches at your own risk.</span></span> <span data-ttu-id="39fc2-119">Поддержка Майкрософт больше не поддерживает In-Place электронных & в EAC.</span><span class="sxs-lookup"><span data-stu-id="39fc2-119">Microsoft Support no longer supports In-Place eDiscovery & Holds in the EAC.</span></span>
    
- <span data-ttu-id="39fc2-120">**1 октября 2020** In-Place функции & eDiscovery в EAC будут размещены в режиме только для чтения, поэтому можно удалить только существующие поиски и удерживает.</span><span class="sxs-lookup"><span data-stu-id="39fc2-120">**October 1, 2020** In-Place eDiscovery & Holds functionality in the EAC will be placed in read-only mode, so you can only remove existing searches and holds.</span></span>

<span data-ttu-id="39fc2-121">**Дополнительные сведения см. в .**</span><span class="sxs-lookup"><span data-stu-id="39fc2-121">**For more information, see**:</span></span>

 - [<span data-ttu-id="39fc2-122">Перенос устаревших поисков электронных данных и их перенос в центр соответствия требованиям Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="39fc2-122">Migrate legacy eDiscovery searches and holds to the Microsoft 365 compliance center</span></span>](https://docs.microsoft.com/microsoft-365/compliance/migrate-legacy-ediscovery-searches-and-holds)
 - [<span data-ttu-id="39fc2-123">Прекращение поддержки устаревших средств обнаружения электронных данных</span><span class="sxs-lookup"><span data-stu-id="39fc2-123">Retirement of legacy eDiscovery tools</span></span>](https://docs.microsoft.com/microsoft-365/compliance/legacy-ediscovery-retirement)
 - [<span data-ttu-id="39fc2-124">FAQs about In-Place eDiscovery and In-Place Holds</span><span class="sxs-lookup"><span data-stu-id="39fc2-124">FAQs about In-Place eDiscovery and In-Place Holds</span></span>](https://docs.microsoft.com/microsoft-365/compliance/legacy-ediscovery-retirement#faqs-about-in-place-ediscovery-and-in-place-holds)




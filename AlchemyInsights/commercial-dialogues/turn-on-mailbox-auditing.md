---
title: Включить аудит почтовых ящиков
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 02/26/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3100005"
- "7327"
ms.openlocfilehash: aa0ff925ae891d28e31394ec66eb17c2d9710008
ms.sourcegitcommit: 251e2e82571fb3bb1fbe3dbf7bfca30e004b3373
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/05/2021
ms.locfileid: "50464935"
---
# <a name="turn-on-mailbox-auditing"></a><span data-ttu-id="3e562-102">Включить аудит почтовых ящиков</span><span class="sxs-lookup"><span data-stu-id="3e562-102">Turn on mailbox auditing</span></span>

<span data-ttu-id="3e562-103">Чтобы включить аудит почтовых ящиков для одного пользователя или всей организации, запустите следующие cmdlets from Remote PowerShell:</span><span class="sxs-lookup"><span data-stu-id="3e562-103">To turn on mailbox auditing for a single user or an entire organization, run the following cmdlets from Remote PowerShell:</span></span>

- <span data-ttu-id="3e562-104">**Один пользователь:** Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="3e562-104">**Single user**: Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
- <span data-ttu-id="3e562-105">**Организация**: Get-Mailbox -ResultSize Unlimited-Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox-AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="3e562-105">**Organization**: Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>

<span data-ttu-id="3e562-106">Дополнительные дополнительные сообщения см. в [сообщении Управление аудитом почтовых ящиков.](https://go.microsoft.com/fwlink/?linkid=2103668)</span><span class="sxs-lookup"><span data-stu-id="3e562-106">To learn more, see [Manage mailbox auditing](https://go.microsoft.com/fwlink/?linkid=2103668).</span></span>
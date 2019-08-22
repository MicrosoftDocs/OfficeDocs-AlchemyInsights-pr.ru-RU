---
title: Включение аудита почтовых ящиков
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 1ef60017f1ea656296bc7b2aa3bc5365646f11f3
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 08/22/2019
ms.locfileid: "36527628"
---
# <a name="enable-mailbox-auditing"></a><span data-ttu-id="e11e3-102">Включение аудита почтовых ящиков</span><span class="sxs-lookup"><span data-stu-id="e11e3-102">Enable mailbox auditing</span></span>

<span data-ttu-id="e11e3-103">Чтобы включить аудит почтовых ящиков для отдельного пользователя или всей Организации, необходимо запустить следующие командлеты из удаленной консоли управления Exchange:</span><span class="sxs-lookup"><span data-stu-id="e11e3-103">To enable Mailbox Auditing for either a single user or an entire organization the following cmdlets must be run from Remote Power Shell:</span></span>
  
 <span data-ttu-id="e11e3-104">**Один пользователь**</span><span class="sxs-lookup"><span data-stu-id="e11e3-104">**Single User**</span></span>
  
<span data-ttu-id="e11e3-105">Set $ Mailbox: Identity "Джейн Dow" — Auditenabled указывает $true</span><span class="sxs-lookup"><span data-stu-id="e11e3-105">Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
  
 <span data-ttu-id="e11e3-106">**organization**</span><span class="sxs-lookup"><span data-stu-id="e11e3-106">**Organization**</span></span>
  
<span data-ttu-id="e11e3-107">Get/Mailbox – ResultSize Unlimited — фильтр {RecipientTypeDetails – EQ "UserMailbox"} | Set/Mailbox — Auditenabled указывает $true</span><span class="sxs-lookup"><span data-stu-id="e11e3-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>
  
[<span data-ttu-id="e11e3-108">Подробнее</span><span class="sxs-lookup"><span data-stu-id="e11e3-108">Learn more</span></span>](https://support.office.com/article/aaca8987-5b62-458b-9882-c28476a66918)
  


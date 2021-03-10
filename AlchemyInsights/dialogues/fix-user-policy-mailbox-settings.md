---
title: Исправление параметров политики пользователя и почтовых ящиков
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: ca998c453fcb0905b122436f0eea384a9b8a9992
ms.sourcegitcommit: bd6a9cb5d357baee5134c0dea430afc2a035c810
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/09/2021
ms.locfileid: "50568687"
---
# <a name="fix-user-policymailbox-settings"></a><span data-ttu-id="3ef06-102">Исправление параметров политики пользователя и почтовых ящиков</span><span class="sxs-lookup"><span data-stu-id="3ef06-102">Fix user policy/mailbox settings</span></span>

<span data-ttu-id="3ef06-103">Параметры нежелательной почты в почтовом ящике повлияли на это сообщение.</span><span class="sxs-lookup"><span data-stu-id="3ef06-103">The junk mail settings on the mailbox affected this message.</span></span> <span data-ttu-id="3ef06-104">Чтобы просмотреть параметры, сделайте следующее:</span><span class="sxs-lookup"><span data-stu-id="3ef06-104">To review the settings, do the following:</span></span>

1. <span data-ttu-id="3ef06-105">Запуск оболочки управления Exchange.</span><span class="sxs-lookup"><span data-stu-id="3ef06-105">Launch Exchange Management Shell.</span></span> <span data-ttu-id="3ef06-106">Дополнительные сведения см. в [рублях Open the Exchange Management Shell.](https://go.microsoft.com/fwlink/?linkid=2101432)</span><span class="sxs-lookup"><span data-stu-id="3ef06-106">For more information, see [Open the Exchange Management Shell](https://go.microsoft.com/fwlink/?linkid=2101432).</span></span>
2. <span data-ttu-id="3ef06-107">Запустите эту команду (используя адрес электронной почты  **пользователя): get-mailboxjunkmailconfiguration -identity "user@domain.com"**</span><span class="sxs-lookup"><span data-stu-id="3ef06-107">Run this command (using the user's email address):  **get-mailboxjunkmailconfiguration -identity "user@domain.com"**</span></span>
3. <span data-ttu-id="3ef06-108">Проверьте, является ли адрес электронной почты отправителей частью **TrustedSendersAndDomains** или **BlockedSendersAndDomains.**</span><span class="sxs-lookup"><span data-stu-id="3ef06-108">Check if the sender's email address is part of **TrustedSendersAndDomains** or **BlockedSendersAndDomains**.</span></span> <span data-ttu-id="3ef06-109">Если адрес электронной почты находится в одном из списков, его может потребоваться удалить.</span><span class="sxs-lookup"><span data-stu-id="3ef06-109">If the email address is in one of the lists, you may have to remove it.</span></span> <span data-ttu-id="3ef06-110">Дополнительные дополнительные сообщения см. [в сообщении Set-MailboxJunkEmailConfiguration.](https://go.microsoft.com/fwlink/?linkid=2101047)</span><span class="sxs-lookup"><span data-stu-id="3ef06-110">To learn more, see [Set-MailboxJunkEmailConfiguration](https://go.microsoft.com/fwlink/?linkid=2101047).</span></span>
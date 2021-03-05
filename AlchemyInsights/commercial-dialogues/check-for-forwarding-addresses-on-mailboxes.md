---
title: Проверка на пересылку адресов в почтовых ящиках
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 17/02/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9002486"
- "7524"
ms.openlocfilehash: 1b0a6c8fe368196f2d1f9811aea895c2c024b2e6
ms.sourcegitcommit: 251e2e82571fb3bb1fbe3dbf7bfca30e004b3373
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/05/2021
ms.locfileid: "50465087"
---
# <a name="check-for-forwarding-addresses-on-mailboxes"></a><span data-ttu-id="3912c-102">Проверка на пересылку адресов в почтовых ящиках</span><span class="sxs-lookup"><span data-stu-id="3912c-102">Check for forwarding addresses on mailboxes</span></span>

<span data-ttu-id="3912c-103">Иногда хакеры пересылают сообщения электронной почты пользователей самим себе, поэтому сначала мы проверяем, как пересылать адреса и правила в почтовом ящике.</span><span class="sxs-lookup"><span data-stu-id="3912c-103">Sometimes hackers forward users' email messages to themselves, so first we'll check for forwarding addresses and rules on the mailbox.</span></span> <span data-ttu-id="3912c-104">Затем мы проверим журналы аудита.</span><span class="sxs-lookup"><span data-stu-id="3912c-104">Then we'll check the audit logs.</span></span> <span data-ttu-id="3912c-105">Вот как проверить, как переададовать адреса:</span><span class="sxs-lookup"><span data-stu-id="3912c-105">Here's how to check for forwarding addresses:</span></span>

1. <span data-ttu-id="3912c-106">Выбор **пользователей**  >  **Активные пользователи**.</span><span class="sxs-lookup"><span data-stu-id="3912c-106">Select **Users** > **Active users**.</span></span>
1. <span data-ttu-id="3912c-107">Выберите пользователя, чья учетная запись скомпрометирована.</span><span class="sxs-lookup"><span data-stu-id="3912c-107">Select the user whose account has been compromised.</span></span>
1. <span data-ttu-id="3912c-108">В вылете, который появляется, раздвигать **параметры почты,** а затем нажмите **кнопку Изменить** для **пересылания электронной почты**.</span><span class="sxs-lookup"><span data-stu-id="3912c-108">In the flyout that appears, expand **Mail Settings**, and then click **Edit** for **Email forwarding**.</span></span>
1. <span data-ttu-id="3912c-109">Удалите не распознающие адреса переададки.</span><span class="sxs-lookup"><span data-stu-id="3912c-109">Remove any forwarding addresses you don't recognize.</span></span>
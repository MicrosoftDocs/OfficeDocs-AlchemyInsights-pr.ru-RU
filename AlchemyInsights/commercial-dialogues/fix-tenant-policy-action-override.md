---
title: Исправлена политика клиента (переопределения действий)
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
ms.openlocfilehash: bc7ad8acd86c9d5b2f99ffdc6fe8a8b53e1fcb8b
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/11/2021
ms.locfileid: "50737541"
---
# <a name="fix-tenant-policy-action-override"></a><span data-ttu-id="e072e-102">Исправлена политика клиента (переопределения действий)</span><span class="sxs-lookup"><span data-stu-id="e072e-102">Fix Tenant policy (action override)</span></span>

<span data-ttu-id="e072e-103">Политика борьбы со спамом в клиенте повлияла на это сообщение.</span><span class="sxs-lookup"><span data-stu-id="e072e-103">An anti-spam policy in your tenant affected this message.</span></span> <span data-ttu-id="e072e-104">Чтобы просмотреть политику, сделайте следующее:</span><span class="sxs-lookup"><span data-stu-id="e072e-104">To review the policy, do the following:</span></span>

1. <span data-ttu-id="e072e-105">Перейдите в Центр обеспечения безопасности [Office 365 &,](https://go.microsoft.com/fwlink/p/?linkid=2077143)а затем перейдите в центр по борьбе со спамом политики управления   >    >  [угрозами.](https://go.microsoft.com/fwlink/?linkid=2101518)</span><span class="sxs-lookup"><span data-stu-id="e072e-105">Go to the [Office 365 Security & Compliance Center](https://go.microsoft.com/fwlink/p/?linkid=2077143), and then go to **Threat management** > **Policy** > [Anti-spam](https://go.microsoft.com/fwlink/?linkid=2101518).</span></span>
2. <span data-ttu-id="e072e-106">Проверьте, **указывает** ли источник политики следующее:  **Add-Xheader/ModifySubject/Redirect/Delete/No action/ BCC message**</span><span class="sxs-lookup"><span data-stu-id="e072e-106">Check to see if **Policy source** indicates the following:  **Add-Xheader/ModifySubject/Redirect/Delete/No action/ BCC message**</span></span>

    <span data-ttu-id="e072e-107">Если это так, на **вкладке Custom** проверьте параметры политики, которая повлияла на сообщение.</span><span class="sxs-lookup"><span data-stu-id="e072e-107">If so, on the **Custom** tab, check the settings of the policy that affected the message.</span></span> <span data-ttu-id="e072e-108">Не исключено, что стандартные **параметры,** применяемые для всех клиентов Exchange Online Protection, повлияли на сообщение.</span><span class="sxs-lookup"><span data-stu-id="e072e-108">It's possible that the **Standard settings** applied to all Exchange Online Protection customers affected the message.</span></span>

<span data-ttu-id="e072e-109">Дополнительные сведения о настройке политик фильтрации нежелательной почты см. в дополнительных сведениях о настройке политик фильтра [нежелательной почты.](https://go.microsoft.com/fwlink/?linkid=2101431)</span><span class="sxs-lookup"><span data-stu-id="e072e-109">For more information on configuring spam filter policies, see [Configure your spam filter policies](https://go.microsoft.com/fwlink/?linkid=2101431).</span></span>
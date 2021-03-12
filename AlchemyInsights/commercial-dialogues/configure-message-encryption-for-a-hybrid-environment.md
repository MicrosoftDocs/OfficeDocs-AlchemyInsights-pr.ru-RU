---
title: Настройка шифрования сообщений для гибридной среды
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/24/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000078"
- "7342"
ms.openlocfilehash: 22c2468b7639680b447b6464431a79b69f7198c3
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/11/2021
ms.locfileid: "50737381"
---
# <a name="configure-message-encryption-for-a-hybrid-environment"></a><span data-ttu-id="e2d84-102">Настройка шифрования сообщений для гибридной среды</span><span class="sxs-lookup"><span data-stu-id="e2d84-102">Configure message encryption for a hybrid environment</span></span>

<span data-ttu-id="e2d84-103">В гибридных средах Exchange локально пользователи могут отправлять зашифрованную электронную почту с помощью шифрования сообщений Office (OME) только в том случае, если электронная почта направляется через Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="e2d84-103">For hybrid Exchange environments, on-premises users can send encrypted email using Office Message Encryption (OME) only if email is routed through Exchange Online.</span></span>

<span data-ttu-id="e2d84-104">Чтобы шифровать сообщения электронной почты с помощью OME, выполните следующие действия:</span><span class="sxs-lookup"><span data-stu-id="e2d84-104">To encrypt emails using OME, perform the following steps:</span></span>

1. <span data-ttu-id="e2d84-105">Используйте мастер [гибридной конфигурации](https://docs.microsoft.com/Exchange/hybrid-configuration-wizard) для настройки гибридной среды.</span><span class="sxs-lookup"><span data-stu-id="e2d84-105">Use the [Hybrid Configuration wizard](https://docs.microsoft.com/Exchange/hybrid-configuration-wizard) to set up your hybrid environment.</span></span> <span data-ttu-id="e2d84-106">Для настройки шифрования не требуется никаких специальных действий.</span><span class="sxs-lookup"><span data-stu-id="e2d84-106">No special steps are required for setting up encryption.</span></span>
2. <span data-ttu-id="e2d84-107">[Настройка правил потока почты для шифрования,](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email) как обычно.</span><span class="sxs-lookup"><span data-stu-id="e2d84-107">[Set up your mail flow rules for encryption](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email) like you normally would.</span></span>



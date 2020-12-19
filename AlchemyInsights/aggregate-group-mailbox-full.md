---
title: Полный NDR AggregateGroupMailbox, полученный для электронной почты, отправленной в группу Microsoft 365
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/18/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004286"
- "7656"
ms.openlocfilehash: 9de09ab4cbd2f09648305b11da6273ed990907cf
ms.sourcegitcommit: 2ffdf6096de5608b117c6677d3cd7dd4c23ea024
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 12/18/2020
ms.locfileid: "49715727"
---
# <a name="aggregategroupmailbox-full-ndr-received-for-email-sent-to-microsoft-365-group"></a>Полный NDR AggregateGroupMailbox, полученный для электронной почты, отправленной в группу Microsoft 365

Используйте следующую команду EXO Shell, чтобы создать правило транспорта Exchange для отправки сообщений электронной почты в почтовый ящик группы в тихом режиме:

`New-TransportRule -SentTo @("AggregateGroupMailbox.A.201708181918@contoso.onmicrosoft.com") -DeleteMessage:$true -Name 'Agg1' -StopRuleProcessing:$false -Mode 'Enforce' -Comments '' -RuleErrorAction 'Ignore' -SenderAddressLocation 'Header'`

> [!NOTE]
> Замените SMTP-адрес в **-SentTo** SMTP-адресом сводного почтового ящика группы в клиенте. SmTP-адрес сводного почтового ящика группы можно получить из полученного сообщения о NDR.




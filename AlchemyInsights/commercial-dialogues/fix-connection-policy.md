---
title: Исправлена политика подключения
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
ms.openlocfilehash: 0b6286350e706e493f6d30b7978aacedc02daff5
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/11/2021
ms.locfileid: "50737831"
---
# <a name="fix-connection-policy"></a>Исправлена политика подключения

Электронная почта была помечена безопасной и доставлена в почтовый ящик пользователя, так как ip-адрес отправки был помечен безопасно в политике фильтра подключения. Чтобы просмотреть политику, сделайте следующее:

1. Перейдите в Центр обеспечения безопасности [Office 365 &,](https://go.microsoft.com/fwlink/p/?linkid=2077143)а затем перейдите в центр по борьбе со спамом политики управления   >    >  [угрозами.](https://go.microsoft.com/fwlink/?linkid=2101518)
2. На **вкладке Custom** выберите политику **фильтра подключения** и выберите политику **редактирования.**
3. Просмотрите **список IP-адресов.** Узнайте, **включен ли безопасный** список.

    > [!NOTE]
    > Корпорация Майкрософт использует сторонние источники надежных отправителей. Если **включен безопасный** список, эти доверенные отправители не по ошибке помечены как спам. Я рекомендую выбрать этот параметр, так как это уменьшит количество ложных срабатывающих сообщений (хорошая почта, классифицируется как спам), которые вы получаете.

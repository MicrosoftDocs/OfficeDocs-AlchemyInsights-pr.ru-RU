---
title: Создание улова электронной почты
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
- "9001524"
- "3732"
ms.openlocfilehash: 2b9131a620139a93ddb844fd49d8fa2ed68e52c2
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/15/2021
ms.locfileid: "51816213"
---
# <a name="create-an-email-catch-all"></a>Создание улова электронной почты

Использование улова все настоятельно рекомендуется. Лучше предоставить отскок отправителю, позволяя отправителям знать, что их сообщение не может быть доставлено по мере решения, чтобы они могли принять меры. Вы также можете ограничить отслеживаемую почту только для того, чтобы ловить ранее допустимые адреса электронной почты. 

Любой улов всех почтовых ящиков будет получать много нежелательной почты и может в конечном итоге заполнить, если не внимательно следить. (Существуют ограничения на получение.) 

Если вы решите продолжить, выполните следующие действия:

1. Создание группы динамического распространения & "Все типы получателей".

2. Создайте специальный почтовый ящик для ловли электронных писем, например, catchall@domain.com.

3. Для определенного домена установите DomainType на "InternalRelay". Если вы позже удалите все уловы, не забудьте установить домен обратно в Авторитетный.

4. Создайте правило транспорта почтового потока следующим образом:

    - Если отправитель "Вне организации"
    - Перенаправление сообщения на Catchall@domain.com
    - Кроме того, что получатель является членом allusers@domain.com (Группа рассылки содержит всех участников)
    - Убедитесь, что новые почтовые ящики добавлены в группу динамического распространения

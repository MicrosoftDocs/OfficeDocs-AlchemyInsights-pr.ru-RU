---
title: Не отправляется сообщение электронной почты для рабочих процессов
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "5200020"
- "1586"
ms.openlocfilehash: 7efb8895ac7e2816a2c6055ec3c08d6f7029d39d
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/14/2020
ms.locfileid: "47749002"
---
# <a name="workflow-email-is-not-being-sent-for-a-sharepoint-list-or-library"></a>Не отправляется сообщение электронной почты для списка или библиотеки SharePoint

1. Сообщения электронной почты от рабочих процессов не отправляются всем пользователям или только определенным пользователям или отображается сообщение об ошибке **"не удается отправить сообщение электронной почты. Убедитесь, что у электронной почты есть действительный получатель**.

    Проверьте, существует ли пользователь в группе разрешений " **все пользователи** " (список сведений о пользователях) для этого семейства веб-сайтов.  URL-адрес прямого примера: https:// <tenant> . SharePoint.com/sites/ <sitename> /_layouts/15/People.aspx? Мембершипграупид = 0

    - Если пользователь не существует, убедитесь, что пользователь вошел на страницу. 
    - Если это внешний пользователь, убедитесь, что его приглашение принято.
    - Если пользователь существует в группе разрешений, убедитесь, что адрес электронной почты задан правильно.
    - Если адрес электронной почты пользователя не задан, создайте пример оповещения для этого пользователя, который принудительно выполняет синхронизацию учетной записи этого пользователя с профилями пользователей SharePoint с этим семейством веб-сайтов.
 
2. Сообщения электронной почты от рабочих процессов отправляются администраторам семейства веб-сайтов, но не отправляются другим пользователям и отображаются ошибки **http, запрещенные для <span>https:</span>//УРЛ/_vti_bin/клиент.КСВК.СП.утилитиес.утилити.сендемаил**.
 

    [В статье отказ в доступе при отправке сообщения электронной почты в группу SharePoint](https://docs.microsoft.com/sharepoint/support/sharing-and-permissions/access-denied-when-send-an-email-to-groups).

    Кроме того, убедитесь, что компонент "семейство веб-сайтов **с ограниченным доступом" не активен в режиме ограниченного доступа** .


## <a name="related-topics"></a>Статьи по теме
Хотите попробовать Microsoft Flow в SharePoint Online?
- [Создание последовательности](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [SharePoint и Flow](https://flow.microsoft.com/blog/sharepoint-and-flow/) 



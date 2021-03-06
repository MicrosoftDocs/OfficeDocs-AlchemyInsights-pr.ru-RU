---
title: Сообщение "только для чтения" для обслуживания при попытке использовать SharePoint или OneDrive
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "127"
- "128"
ms.assetid: de7b6877-f3f9-4402-8072-c73783aaccaa
ms.openlocfilehash: a3d313816beefcefa4d93528d3ad9a684e60390e
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/14/2020
ms.locfileid: "47670845"
---
# <a name="read-only-for-maintenance-message-when-attempting-to-use-sharepoint-or-onedrive"></a>Сообщение "только для чтения" для обслуживания при попытке использовать SharePoint или OneDrive

При попытке использовать SharePoint или OneDrive для выполнения одного из следующих сценариев пользователи могут получить сообщение об **обслуживании, доступное только для чтения** . 

-   Запланированные или активные действия по обслуживанию.  Проверьте их, перейдя в [Центр сообщений](https://portal.office.com/adminportal/home#/messagecenter).
-   Высокоприоритетный инцидент Active Service, который может возникать. Проверьте наличие помощников и инцидентов, перейдя к [работоспособности службы](https://portal.office.com/adminportal/home#/servicehealth).
-   Дополнительный сценарий восстановления с автовосстановлением, который может происходить из-за непредвиденных событий на серверах, которые могут быть последними менее чем на 30 минут. 
    
    Не существует центра сообщений или сообщений о работоспособности службы для этих незначительных восстановлений, но вам следует вернуться к нормальному началу работы.

В очень редких случаях мы наблюдали, что существует один из трех указанных выше сценариев, а служба восстановлена, но кэш браузера пользователей не был очищен.

Перед переходом на сайт попробуйте очистить кэш браузера.

1. В браузере Microsoft Edge выберите **Параметры**, а затем выберите **Конфиденциальность и безопасность**.
2. В разделе **очистить обзор**выберите **команду выбрать, что нужно очистить**.
3. Выберите **файлы cookie и сохраненные данные веб-сайта**, а затем нажмите кнопку **очистить**.

>[!Note] 
> Эти действия могут отличаться при использовании других браузеров, таких как Mozilla Firefox или Google Chrome.

>[!Note] 
> Кроме того, можно открыть сайт SharePoint или OneDrive в новом окне InPrivate.
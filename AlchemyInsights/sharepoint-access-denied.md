---
title: Устранение неполадок при доступе к сообщениям
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: f49cfc50142b3d98a5f431a38e9a943eb5624523
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/14/2020
ms.locfileid: "47691696"
---
# <a name="troubleshoot-access-denied-messages"></a>Устранение неполадок при доступе к сообщениям

Если вы получаете сообщение об отказе в доступе при попытке просмотреть сайт SharePoint Online, ознакомьтесь со статьями ниже.

**Добавление и лицензия пользователя**

Убедитесь, что вы [назначаете пользователям лицензии в Microsoft 365 для бизнеса](https://docs.microsoft.com/microsoft-365/admin/add-users/add-users).

**Назначение разрешений**

Если пользователю назначена лицензия SharePoint и по-прежнему получается сообщение об отказе в доступе, убедитесь, что для него [назначен соответствующий уровень разрешений](https://docs.microsoft.com/sharepoint/understanding-permission-levels).

**Рассмотрите возможность использования функции запросов на доступ**

Функция [запросов на доступ](https://support.office.com/article/Set-up-and-manage-access-requests-94B26E0B-2822-49D4-929A-8455698654B3) позволяет пользователям запрашивать доступ к контенту, на просмотр которого у них нет разрешения. 

**Разрешить настраиваемый скрипт может вызывать проблемы, связанные с доступом**

Существует несколько сценариев, в которых функция "разрешить пользовательский сценарий" может привести к отказу в доступе. Список затронутых компонентов, рекомендации по безопасности и возможность отключения этой функции. Посетите, [разрешите или запретите использование настраиваемого скрипта](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script) .

Примечание. Если сайт OneDrive или SharePoint недоступен для нескольких пользователей, у которых ранее был доступ, может возникнуть временная ошибка службы. [Проверьте панель мониторинга работоспособности службы](https://portal.office.com/adminportal/home#/servicehealth).


  


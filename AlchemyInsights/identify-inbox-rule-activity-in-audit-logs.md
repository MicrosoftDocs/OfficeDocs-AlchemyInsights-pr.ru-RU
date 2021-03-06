---
title: Определение активности правила для папки "Входящие" в журналах аудита
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1368"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 3de6fcde6dc649cb77077d469cc66d4003e0c890
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/15/2020
ms.locfileid: "47779064"
---
# <a name="identify-inbox-rule-activity-in-audit-logs"></a>Определение активности правила для папки "Входящие" в журналах аудита

Вы можете использовать поиск в журнале аудита в центре безопасности & соответствия требованиям Microsoft 365 для просмотра событий правил папки "Входящие" (создание, изменение и удаление правил для папки "Входящие").

1. Войдите в [центр соответствия требованиям & безопасности Microsoft 365](https://protection.office.com/).

2. Перейдите на страницу **Search**  >  **поиска журнала аудита** поиска.

3. Выберите диапазон дат в полях **Дата начала** и **Дата окончания** .

4. В разделе **действия почтового ящика Exchange**убедитесь, что для поля **действия** задано значение создать, **InboxRule создать/изменить/включить или отключить правило для папки "Входящие"**.

5. Нажмите кнопку **Поиск**.

В списке результатов выберите запись аудита. В всплывающем меню сведения щелкните **Дополнительные сведения**. Сведения о параметрах правила папки "Входящие" отображаются в поле **Параметры** .

Дополнительные сведения см. в статье [Определение, создал ли пользователь правило для папки "Входящие"](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)

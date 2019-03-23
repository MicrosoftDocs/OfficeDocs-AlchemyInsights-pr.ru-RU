---
title: НаСтольный отзыв или замена сообщения электронной почты на рабочем столе Outlook
ms.author: daeite
author: daeite
manager: joallard
ms.date: 3/13/2019
ms.audience: Admin
ms.topic: article
ms.custom: 9000260
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: aced684777ef82860b969aea8825699b78b04c5a
ms.sourcegitcommit: aad9f863bc9fd7d5522c480bd1a7d15f3a80ff4f
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/15/2019
ms.locfileid: "30657056"
---
# <a name="recall-or-replace-an-email-message"></a>Отзыв или замена сообщения электронной почты

- Администратор может **отозвать сообщения от имени пользователей с помощью PowerShell**. Вы не можете отозвать сообщения из центра администрирования.
- Вы можете **отозвать только те сообщения, которые отправляются пользователям в вашей организации**. Например, если сообщение было отправлено на адрес Gmail, его невозможно отозвать.
- Вы можете **отозвать сообщения, отправленные из Outlook 2016 на компьютер**. Если пользователь отправляет сообщение с помощью Outlook для Mac или Outlook в Интернете, вы не можете отозвать его.

Чтобы отозвать или заменить сообщение электронной почты, выполните указанные ниже действия.

1. В области папок слева от окна Outlook выберите папку Отправленные.
1. Дважды щелкните сообщение, которое нужно отозвать, чтобы открыть его.
1. Перейдите на вкладку **сообщение** , а затем выберите **действия** > **отозвать это сообщение**.
1. Выберите **Удалить непрочтенные копии этого сообщения** или **Удалить непрочтенные копии и замените на новое сообщение**, а затем нажмите кнопку **ОК**.
1. Если вы отправляете заменяющее сообщение, создайте сообщение, а затем нажмите кнопку **Отправить**.
1. Успех или неудача при отзыве сообщения зависит от параметров получателя в Outlook. Действия, которые необходимо выполнить для проверки отзыва, приведены в [этой статье](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

Поиск и удаление сообщений электронной почты в Организации

- Если вы не являетесь глобальным администратором, необходимо добавить свою учетную запись в роль диспетчера обнаружения электронных данных или роль управления поиском соответствия требованиям для поиска сообщений. Чтобы удалить сообщения, необходимо присоединиться к группе ролей Управление организацией или ролью управления поиска и очистки. Разрешения для этих ролей назначаются в [центре безопасности и соответствия требованиям](https://go.microsoft.com/fwlink/?linkid=2083731).
- [Создайте поиск контента](https://docs.microsoft.com/office365/securitycompliance/content-search) , чтобы найти сообщение, которое требуется удалить.
- [Подключение к PowerShell центра безопасности и соответствия требованиям](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).

Если вы используете многофакторную проверку подлинности, ознакомьтесь со статьей [Подключение к Office 365 Security and Security Center PowerShell с использованием многофакторной проверки](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps)подлинности.
---
title: Автоматически шифруются сообщения электронной почты Office 365, отправленные в определенные домены
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
ms.openlocfilehash: 7fb96a30cd1922bd39a4b99a7ecd869622f3a466
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/11/2021
ms.locfileid: "50737589"
---
# <a name="automatically-encrypt-office-365-email-messages-sent-to-certain-domains"></a>Автоматически шифруются сообщения электронной почты Office 365, отправленные в определенные домены

1. В центре [администрирования Exchange](https://outlook.office365.com/ecp/)выберите поток **почты > правила.** 
2. Щелкните **значок New (+)** и нажмите кнопку **Применить шифрование сообщений Office 365** и защиту прав на сообщения.
3. В **Name** введите имя правила, например шифруем сообщений, отправленных *в contoso.com.*
4. В **Применение этого правила,** если выберите получателя > **домена**. 
5. Введите имя домена, например **contoso.com.**
6. Щелкните **значок Добавить (+)** и нажмите **кнопку ОК**.
7. Рядом со следующим **полем Do** щелкните **Выберите одно.** 
8. В **выпадаемом меню** шаблона RMS выберите **Шифруй** и нажмите **кнопку ОК.** (Если вы не видите этот параметр, это означает, что ваш план не включает автоматическое шифрование. Но вы можете добавить его!)
9. Выберите любой необязательный выбор (из списка необязательных выборов, которые можно сделать на данном этапе, многие из которых можно оставить с параметром по умолчанию для простоты).
10. Щелкните **Сохранить**.

> [!IMPORTANT]
> Вы всегда можете вернуться и изменить это правило позже.

Дополнительные сведения о создании правил шифрования см. в тексте Определение правил потока почты для шифрования сообщений электронной почты [в Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email)
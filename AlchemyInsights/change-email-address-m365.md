---
title: Изменение адреса электронной почты группы Microsoft 365 или Microsoft Teams
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1200024"
- "4704"
ms.openlocfilehash: 7800a447c5dfcc8397121e1149921916ff7944ac
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/15/2021
ms.locfileid: "51819093"
---
# <a name="change-email-address-of-a-microsoft-365-group-or-microsoft-teams"></a>Изменение адреса электронной почты группы Microsoft 365 или Microsoft Teams

Вы можете изменить адрес электронной почты группы Microsoft 365 или Microsoft Teams с помощью [Центра администрирования Microsoft 365](https://admin.microsoft.com/). Достаточно выбрать группу, а затем выбрать @Изменить адрес электронной почты.

Также можно использовать следующую команду EXO PowerShell, чтобы изменить основной SMTP-адрес группы Microsoft 365 или Teams:

`Set-UnifiedGroup <Group Name> -PrimarySmtpAddress <new SMTP Address>`

Пример:

`Set-UnifiedGroup Marketing -PrimarySmtpAddress marketing@contoso.com`

---
title: Включение вебинаров Teams
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 06/02/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "11513"
- "9006672"
ms.openlocfilehash: 5a732e6746e9fd23e54a0b2ffeabb59623012a0e
ms.sourcegitcommit: 9de78b30602f917d58705057cdcce31fec349969
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/04/2021
ms.locfileid: "52760857"
---
# <a name="enable-teams-webinars"></a>Включение вебинаров Teams

Вебинары включены по умолчанию. С помощью команд PowerShell Teams вы можете управлять тем, кто может планировать вебинары Teams и регистрироваться в них.

- Все пользователи, которые могут создавать собрания, также могут создавать вебинары. Если вы хотите управлять тем, кто может планировать вебинары Teams, используйте параметр *allowMeetingRegistration*. 
- По умолчанию параметр *whoCanRegister* включен и ему присвоено значение **Все**. Если вы хотите отключить регистрацию в собраниях, присвойте параметру *allowMeetingRegistration* значение **False**.

Чтобы изменить эти параметры, установите [PowerShell Teams](/microsoftteams/teams-powershell-install). Кроме того, к вебинарам Teams применяются политики собраний. Например, если анонимное присоединение отключено в параметрах собрания, анонимные пользователи не смогут присоединяться к вебинарам.

Дополнительные сведения о настройке того, кто может регистрироваться в вебинарах, см. в разделе [Настройка пользователей, которые могут регистрироваться в вебинарах](/microsoftteams/set-up-webinars?source=docs#configure-who-can-register-for-webinars). Дополнительные сведения о параметрах Microsoft Списки см. в статье [Управление параметрами для Microsoft Списки](/sharepoint/control-lists).
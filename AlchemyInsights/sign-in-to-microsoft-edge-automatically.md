---
title: Вход в Microsoft Edge автоматически
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/03/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003848"
- "6898"
- "8333"
- "9004625"
ms.openlocfilehash: 6021991c125f5cb2a33ce8db8fe7717b528bf49b
ms.sourcegitcommit: 6bfe9cd9d0b18481e0cac6f1f5bc86ed7df31037
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/27/2021
ms.locfileid: "51398742"
---
# <a name="sign-in-to-microsoft-edge-automatically"></a>Вход в Microsoft Edge автоматически

Microsoft Edge использует учетную запись по умолчанию ОС, чтобы автоматически войти в пользователя в соответствии с настройкой устройства пользователя. 

Ниже описаны сценарии каждого типа конфигурации устройства и его зависимого процесса регистрации пользователя:

- **Устройство гибридное/AAD-J.** Этот параметр доступен в Windows 10, Windows на уровне и в соответствующих версиях сервера. Пользователи автоматически включались в свои учетные записи Azure Active Directory (AD).
- **Устройство соединено с доменом:** этот параметр доступен в Windows 10, Windows на уровне и в соответствующих версиях сервера. По умолчанию пользователи с учетными записями домена не включались автоматически; Чтобы включить автоматический вход для них, используйте политику **ConfigureOnPremisesAccountAutoSignIn.** Чтобы включить автоматическую регистрацию для пользователей с учетными записями Azure AD, рассмотрите возможность гибридного присоединения к своим устройствам.
- **Учетная** запись оси по умолчанию — учетная запись Майкрософт. Этот параметр доступен в Windows 10 RS3 (версия 1709, сборка 10.0.16299) и более поздних версиях. Сценарий вряд ли будет происходить на корпоративных устройствах. Однако если учетная запись по умолчанию ОС является учетной записью Майкрософт, microsoft Edge автоматически включит пользователя с учетной записью Майкрософт.
 
 

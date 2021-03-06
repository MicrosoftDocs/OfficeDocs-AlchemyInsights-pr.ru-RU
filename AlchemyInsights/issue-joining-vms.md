---
title: Проблема с подключением к виртуальным машинам
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 01/15/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "7924"
- "9004395"
ms.openlocfilehash: 77a889f05d6c4e7b19a1e0a66a99ffc0565c69d8
ms.sourcegitcommit: a61a29dbd0382370fea0be5fa4a61c9a1a9354c7
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/18/2021
ms.locfileid: "49884615"
---
# <a name="issue-joining-vms"></a>Проблема с подключением к виртуальным машинам

Чтобы устранить проблему, связанную с подключением к виртуальным машинам, выполните следующие действия.

1. Попробуйте войти в систему, используя формат **UPN** (например, 'joeuser@contoso.com') вместо формата **SAMAccountName** ('CONTOSO\joeuser').
2. Убедитесь, что синхронизация паролей включена в соответствии с инструкциями, описанными в *Руководстве по началу работы*.
3. Убедитесь, что затронутая учетная запись пользователя не является внешней учетной записью в клиенте Azure AD. Внешние пользователи не могут войти в управляемый домен, так как доменные службы Azure AD не имеют учетных данных для таких учетных записей.
4. Если затронутая учетная запись пользователя является облачной учетной записью, убедитесь, что пользователи изменили свои пароли после включения доменных служб Azure AD. Это действие приводит к созданию хэшей учетных данных, необходимых для доменных служб Azure AD.
5. Если затронутые учетные записи пользователей синхронизируются из локального каталога, убедитесь, что для выполнения полной синхронизации настроен рекомендуемый выпуск Azure AD Connect.
6. Если проблема сохраняется после выполнения Действия 4, выполните следующие команды с вашего устройства синхронизации.
 
     `"net stop 'Microsoft Azure AD Sync'"`  
     `"net start 'Microsoft Azure AD Sync'"`.
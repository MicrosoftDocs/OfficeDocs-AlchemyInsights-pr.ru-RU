---
title: Создание связи организации, чтобы разрешить пользователям взаимодействовать с другой организацией
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3800014"
- "898"
ms.openlocfilehash: 2c6cd6a178c6e012bfe1c8d769b037168ffa3254
ms.sourcegitcommit: 722e9a0ed058cb1eab2dd053be2418b60f7d4aac
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/23/2020
ms.locfileid: "44854044"
---
# <a name="create-an-organization-relationship-to-allow-your-users-to-collaborate-with-another-organization"></a>Создание связи организации, чтобы разрешить пользователям взаимодействовать с другой организацией

1. На панели мониторинга Центра администрирования Microsoft 365 выберите **Администрирование** > **Exchange**.
2. Перейдите в раздел **Организация** > **Общий доступ**.
3. В разделе **Общий доступ к организации** нажмите кнопку **Создать**.
4. В окне **Новая связь организации** в поле **Имя связи** введите понятное имя связи.
5. В поле **Домены, которым предоставлен общий доступ** введите домен для внешней организации Office 365 или локальной организации Exchange, которым нужно предоставить возможность просмотра ваших календарей. Если требуется ввести более одного домена, разделяйте их имена запятыми. Например, contoso.com, service.contoso.com.
6. Select the **Enable calendar free/busy information sharing** check box to turn on calendar sharing with the domains you listed. Set the sharing level for calendar free/busy information and set which users can share calendar free/busy information.  

Для настройки уровня доступа к сведениям о занятости выберите одно из следующих действий:

- **Календарных данных о занятости только по времени**
- **Календарные данные о занятости со временем, темой и местом**  

 Чтобы указать, какие пользователи могут предоставлять общий доступ к сведениям о доступности в календаре, выберите один из указанных ниже вариантов.

- **Все в организации**
- **Заданная группа безопасности**  

Щелкните **Обзор**, чтобы выбрать из списка группу безопасности, затем нажмите кнопку **ОК**.

Нажмите кнопку **Сохранить**, чтобы создать связь организации.  

**Примечание**. Межклиентские конфигурации не поддерживают просмотр сведений о доступности личных контактов. Чтобы просматривать сведения о доступности, контакты должны быть включены в глобальный список адресов.

**Полные сведения по этой теме см. в статье:**

- [Создание связи организации в Exchange Online](https://docs.microsoft.com/exchange/sharing/organization-relationships/create-an-organization-relationship)
- [Изменение связи организации в Exchange Online](https://docs.microsoft.com/exchange/sharing/organization-relationships/modify-an-organization-relationship)
- [Удаление связи организации в Exchange Online](https://docs.microsoft.com/exchange/sharing/organization-relationships/remove-an-organization-relationship)
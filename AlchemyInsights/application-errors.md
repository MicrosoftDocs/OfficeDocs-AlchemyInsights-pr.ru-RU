---
title: Ошибки приложения
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 01/25/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004342"
- "7841"
ms.openlocfilehash: 2ef90b54ce222a06740e05891fabe87b6565cb14
ms.sourcegitcommit: ba3118b7ad5e02756d0e5c2113245090f54370af
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/25/2021
ms.locfileid: "49976914"
---
# <a name="application-errors"></a>Ошибки приложения

Ищете сведения о кодах ошибок **AADSTS,** которые возвращаются из службы маркеров безопасности Azure Active Directory (Azure AD)? Прочитайте коды ошибок проверки подлинности и авторизации [Azure AD,](https://docs.microsoft.com/azure/active-directory/develop/reference-aadsts-error-codes) чтобы найти описания ошибок AADSTS, исправления и некоторые рекомендуемые обходные пути.

Ошибки авторизации могут быть результатом нескольких различных проблем, большинство из которых создают ошибку 401 или 403. Например, ошибки авторизации могут возникнуть в результате следующих неполадок:

- Некорректные [потоки получения маркеров доступа](https://docs.microsoft.com/azure/active-directory/develop/reference-aadsts-error-codes) 
- Неправильно настроенные [области разрешений](https://docs.microsoft.com/azure/active-directory/develop/active-directory-v2-scopes) 
- Отсутствие [согласия](https://docs.microsoft.com/azure/active-directory/develop/active-directory-devhowto-multi-tenant-overview#understanding-user-and-admin-consent)

Чтобы устранить распространенные ошибки авторизации, попробуйте следующие действия, которые наиболее точно совпадают с ошибкой, которую вы получаете. Может применяться несколько.

**Ошибка "401 — недостаточно прав": является ли маркер допустимым?**

Убедитесь, что приложение представляет допустимый маркер доступа в Microsoft Graph в рамках запроса. Эта ошибка часто означает, что маркер доступа отсутствует в заголовке HTTP-запроса на проверку подлинности, что он недопустим или срок его действия истек. Мы настоятельно рекомендуем использовать [Библиотеку проверки подлинности Майкрософт (MSAL)](https://docs.microsoft.com/azure/active-directory/develop/msal-overview) для получения маркеров доступа. Кроме того, эта ошибка может возникнуть при попытке использовать маркер делегирования доступа, предоставленный личной учетной записи Майкрософт, для доступа к API, который поддерживает только работу или учебные учетные записи (учетные записи организации).

**Ошибка "403 — запрещено": выбран ли соответствующий набор разрешений?**

Убедитесь, что вы запросили правильный набор разрешений на основе API Microsoft Graph, которые вызывает ваше приложение. Рекомендуемые разрешения с наименьшими привилегиями предоставляются во всех справочных методах API Microsoft Graph. Кроме того, эти разрешения должны быть предоставлены приложению пользователем или администратором. Для предоставления разрешений обычно используется страница подтверждения или колонка "Регистрация приложений" на портале Azure. В колонке для приложения **Параметры** выберите **Необходимые разрешения** > **Предоставить разрешения**.

- [Разрешения Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) 
- [Общие сведения о разрешениях Azure AD и согласии](https://docs.microsoft.com/azure/active-directory/develop/v2-permissions-and-consent) 

**Ошибка "403 — запрещено": получило ли приложение маркер для соответствия выбранным разрешениям?**

Убедитесь, что тип запрошенных или предоставленных разрешений совпадает с типом маркера доступа, который получает приложение. Возможно, вы запрашиваете и предоставляете разрешения для приложения, но используете маркеры потоков делегированного интерактивного кода вместо маркеров потоков учетных данных клиента, или запрашиваете и предоставляете делегированные разрешения, но используете маркеры потоков учетных данных клиента вместо маркеров потоков делегированного кода.

- [Получение доступа от имени пользователей и делегированные разрешения](https://docs.microsoft.com/graph/auth_v2_user) 
- [Azure AD версии 2.0 — поток кода авторизации OAuth 2.0](https://docs.microsoft.com/azure/active-directory/develop/v2-oauth2-auth-code-flow) 
- [Получение доступа без пользователя (служба управляющей программы) и разрешения приложения](https://docs.microsoft.com/graph/auth_v2_service) 
- [Azure AD версии 2.0 — поток учетных данных клиента OAuth 2.0](https://docs.microsoft.com/azure/active-directory/develop/v2-oauth2-client-creds-grant-flow) 

**Ошибка "403 — запрещено": сброс пароля**

В настоящее время нет разрешений для служб программы, управляющей разрешениями приложения, которые позволяют сбросить пароли пользователей. Эти API поддерживаются только с помощью потоков интерактивного делегированного кода для администратора, выполнившего вход.

- [Разрешения Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference)

**Ошибка "403 — запрещено": есть ли доступ у пользователя, и имеет ли он лицензию?**

Для потоков делегирования кода Microsoft Graph оценивает, разрешен ли запрос, на основе разрешений, предоставленных приложению, и разрешений, которые есть у вочастного пользователя. Как правило, эта ошибка указывает на то, что пользователь не обладает достаточными правами для выполнения запроса или что у пользователя нет лицензии на доступ к данным. Только пользователи с необходимыми разрешениями или лицензиями могут успешно выполнить запрос.

**Ошибка "403 — запрещено": выбран ли правильный API ресурсов?**

Службы API, такие как Microsoft Graph, проверяют, что утверждение aud (аудитория) в полученном маркере доступа соответствует значению, которое оно ожидает для себя, и если нет, это приводит к ошибке 403 Forbidden. Распространенная ошибка, вызываемая этой ошибкой, — попытка использовать маркер, полученный для API Azure AD Graph, API Outlook или API SharePoint/OneDrive, для вызова Microsoft Graph (или наоборот). Убедитесь, что ресурс (или область), для которого приложение получает маркер, соответствует API, который вызывает приложение.

**Ошибка "400 — ошибочный запрос" или "403 — запрещено": выполняет ли пользователь требования политики условного доступа своей организации?**

На основе политик ЦС организации пользователю, который получает доступ к ресурсам Microsoft Graph через ваше приложение, может потребоваться получить дополнительные сведения, которые не присутствуют в маркере доступа, который изначально было приобретено приложением. В этом случае приложение получает сообщение об ошибке 400 с *interaction_required* при получении маркера доступа или сообщение об ошибке 403 с *insufficient_claims* при вызове Microsoft Graph. В обоих случаях сообщение об ошибке содержит дополнительные сведения, которые могут быть представлены в конечную точку авторизации, чтобы запросить у пользователя дополнительную информацию (например, многофакторная проверка подлинности или регистрация устройства).

- [Обработка проблем условного доступа с помощью MSAL ](https://docs.microsoft.com/azure/active-directory/develop/msal-handling-exceptions#conditional-access-and-claims-challenges)
- [Руководство для разработчиков по условному доступу в Azure Active Directory](https://docs.microsoft.com/azure/active-directory/develop/conditional-access-dev-guide)
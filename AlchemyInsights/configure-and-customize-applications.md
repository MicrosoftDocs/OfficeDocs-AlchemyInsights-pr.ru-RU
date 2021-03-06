---
title: Настройка и настройка приложений
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004334"
- "7733"
ms.openlocfilehash: 30127beda85dd9824f7e3a7a4744d109e7ea874b
ms.sourcegitcommit: aeb15e206865f61ff61a1e55c407e34eaa89b6d1
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/29/2021
ms.locfileid: "50043989"
---
# <a name="configure-and-customize-applications"></a>Настройка и настройка приложений

**Настройка приложений**

1. Краткое руководителем: настройка свойств приложения в клиенте [Azure Active Directory (Azure AD)](https://docs.microsoft.com/azure/active-directory/manage-apps/add-application-portal-configure) показывает, как настроить некоторые свойства приложения.
2. Для интеграции приложений с Azure Active Directory [](https://docs.microsoft.com/azure/active-directory/saas-apps/tutorial-list) мы разработали коллекцию учебников, которые помогут вам в настройке.
3. [Настройка прокси-приложения](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-config-how-to) приложения помогает понять, как настроить приложение-прокси приложения в Azure AD для того, чтобы ваши приложения были в облаке.
4. Скачайте [PingAccess](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-ping-access-publishing-guide#download-pingaccess-and-configure-your-application)и настройте свое приложение: следуйте инструкциям в настройке *PingAccess для Azure AD,* чтобы защитить приложения, опубликованные с помощью прокси приложения Microsoft Azure AD на веб-сайте удостоверения Ping, и скачайте последнюю версию PingAccess.

**Ошибки неправильного приложения (AADSTS650056)**

1. Убедитесь, что вы обращались к приложению с адреса для регистрации, предоставленного владельцем приложения. В противном случае во sign in to the application through its normal process. В большинстве случаев это будет автоматически разрешаться естественно. Если этого не сделать, эта публикация поможет устранить неполадки и устранить ее.
2. **Если вашей организации принадлежит приложение** (то есть регистрация приложения находится в вашей организации):
    - Рекомендуется как минимум добавить или делегировать `User.Read` `openid` разрешение из Microsoft **Graph.**
    - Убедитесь, что приложение и все его разрешения согласились. Это можно проверить, проверив столбец **"Состояние"** регистрации приложения в **разрешениях API.**
    - В некоторых случаях приложение может быть сторонним, но оно может быть зарегистрировано в вашей организации. Подтвердите, указано ли это приложение в ваших регистрациях приложений (не корпоративных).
    - Если вы продолжаете видеть это сообщение об ошибке. Затем может потребоваться создать URL-адрес согласия, описанный **в шаге 4.**
3. **Если ваша организация не является владельцем приложения и использует его в качестве сторонного приложения:**
    - Если вы глобальный администратор или администратор компании, вы должны увидеть экран согласия. Убедитесь, что вы нажмите "Согласие от имени **вашей организации".**
    - Если вы не видите экран согласия, удалите корпоративное приложение и попробуйте еще раз.
    - Если вы продолжаете видеть это сообщение об ошибке. Затем может потребоваться создать URL-адрес согласия, описанный **в шаге 4.**
4. Вручную создайте **URL-адрес** согласия для использования: если приложение предназначено для доступа к определенному ресурсу, вы не сможете использовать кнопки согласия с портала Azure, вам потребуется вручную создать собственный URL-адрес согласия и использовать его.
    - Вам потребуется получить и от владельца `{App-Id}` `{App-Uri-Id}` приложения. `{Tenant-Id}` будет идентификатором клиента. Это будет либо `yourdomain.onmicrosoft.com` ваш ИД каталога.
    - Если приложение имеет доступ к самому ресурсу, он будет таким `{App-Id}` `{App-Uri-Id}` же.
5. Дополнительные сведения см. в сведениях о проблемах при входе в приложения с единым входом на основе [SAML.](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-problem-federated-sso-gallery#misconfigured-application)

**Настройка приложений**

- Добавьте фирменную символику на страницу входов [в Azure Active Directory](https://docs.microsoft.com/azure/active-directory/fundamentals/customize-branding) вашей организации. Используйте логотип организации и пользовательские цветовые схемы, чтобы обеспечить согласованный внешний вид страниц для входов в Azure Active Directory (Azure AD).
- [Добавьте собственное доменное имя с помощью портала Azure Active Directory](https://docs.microsoft.com/azure/active-directory/fundamentals/add-custom-domain) . Каждый новый клиент Azure AD поставляется с начальным доменным именем. Исходное доменное имя изменить или удалить нельзя, но вы можете добавить имена организации. Добавление пользовательских доменных имен помогает создавать знакомые пользователям имена пользователей.

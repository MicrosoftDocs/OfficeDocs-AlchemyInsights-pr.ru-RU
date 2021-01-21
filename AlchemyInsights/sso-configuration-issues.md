---
title: Ошибки конфигурации единого входа
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 01/17/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "7760"
- "9004346"
ms.openlocfilehash: 5ab56ec1eda10ea059e600e8933ce85bb143b76e
ms.sourcegitcommit: 6d02eb533fd74199af6b20f714b3720991da2c4a
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/18/2021
ms.locfileid: "49886911"
---
# <a name="sso-configuration-issues"></a>Ошибки конфигурации единого входа

1. Следуйте инструкциям, приведенным в статье [Краткое руководство: Настройка свойств приложения](https://docs.microsoft.com/azure/active-directory/manage-apps/add-application-portal-configure), чтобы настроить приложение.
2. В зависимости от приложения и выбранного [варианта единого входа](https://docs.microsoft.com/azure/active-directory/manage-apps/sso-options), выполните следующие действия: а. Чтобы настроить **локальное приложение** для **единого входа на основе SAML**, см. статью [Единый вход SAML для локальных приложений с использованием прокси-сервера приложений](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-single-sign-on-on-premises-apps).
    б. Чтобы настроить **облачное приложение** для **единого входа на основе паролей**, см. статью [Настройка единого входа с помощью пароля](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-password-single-sign-on-non-gallery-applications).
    в. Чтобы настроить **локальное приложение** для **единого входа через прокси-сервер приложения**, см. статью [Настройка хранилища паролей для единого входа с помощью прокси-сервера приложения](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-single-sign-on-password-vaulting).
3. **Устранение неполадок, связанных с прокси-сервером приложения**. Рекомендуется начать с изучения процесса устранения неполадок в статье [Отладка проблем с соединителем прокси-сервера ](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-debug-connectors), чтобы определить, правильно ли настроены соединители прокси-сервера приложения.. Если у вас по-прежнему возникают проблемы с подключением к приложению, выполните действия по устранению неполадок в статье [Отладка проблем с прокси приложения](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-debug-apps). Вы можете [определить ошибки CORS](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-understand-cors-issues#understand-and-identify-cors-issues), выполнив следующие действия по отладке браузера: Запустите браузер и перейдите в веб-приложение.
    б. Нажмите клавишу **F12**, чтобы вывести консоль отладки.
    в. Попробуйте воспроизвести транзакцию и посмотреть сообщение консоли. Нарушение CORS вызывает консольную ошибку о происхождении.
    г. Некоторые проблемы CORS невозможно решить, например истечение срока действия маркера доступа, когда приложение перенаправляется на login.microsoftonline.com для проверки подлинности. В результате истечения срока действия маркера доступа, вызов CORS завершается ошибкой. Временное решение для этого сценария — продлить жизненный цикл маркера доступа, чтобы предотвратить истечение его срока действия в течении сеанса пользователя. Дополнительные сведения о том, как это сделать, см. в статье [Настраиваемые жизненные циклы маркеров на платформе удостоверений Майкрософт](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes).
4. **Устранение неполадок единого входа на основе SAML**. Рекомендуется ознакомиться со статьей [Проблемы со входом в настраиваемые приложения с поддержкой единого входа на основе SAML](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-problem-federated-sso-gallery), чтобы найти решения наиболее распространенных проблем.
5. **Устранение неполадок единого входа на основе паролей**. Рекомендуется ознакомиться со статьей [Устранение неполадок с единым входом на основе паролей в Azure AD](https://docs.microsoft.com/azure/active-directory/manage-apps/troubleshoot-password-based-sso), чтобы найти решения наиболее распространенных проблем.
6. **Произошла ошибка конфигурации**. Чтобы устранить ошибки конфигурации, рекомендуем ознакомиться со статьями ниже. [Проблемы со входом в приложения на основе SAML, настроенные на единый вход.](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-problem-federated-sso-gallery) б. [Учетные данные заполнены, но расширение не отправляет их](https://docs.microsoft.com/azure/active-directory/manage-apps/troubleshoot-password-based-sso#credentials-are-filled-in-but-the-extension-does-not-submit-them) в. [Учетные данные заполнены и отправлены, но на странице указано, что учетные данные неверны](https://docs.microsoft.com/azure/active-directory/manage-apps/troubleshoot-password-based-sso) г. [На странице приложения выводится сообщение об ошибке после входа пользователя](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-problem-application-error)
7. **Проблемы с интеграцией простого единого входа в локальных приложениях**. Чтобы устранить проблемы, связанные с интеграцией простого единого входа в локальных приложениях, рекомендуем ознакомиться со статьями ниже: а. [Настройка единого входа в прокси приложение](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-config-sso-how-to) б. [Единый вход SAML для локальных приложений с прокси-сервером](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-single-sign-on-on-premises-apps) в. [Сведенья об устранении проблем с CORS прокси-сервера приложения Azure Active Directory.](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-understand-cors-issues#solutions-for-application-proxy-cors-issues) г. [Устранение неполадок с настойками ограниченного делегирования Kerberos для прокси-сервера приложения](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-back-end-kerberos-constrained-delegation-how-to)
8. **Мне нужно исправить утверждения или продлить срок действия маркера. Мне нужно изменить продолжительность сеанса**. Для этого рекомендуется ознакомиться со статьями ниже: а. [Настройка утверждений SAML, отправленных приложению](https://docs.microsoft.com/azure/active-directory/develop/active-directory-claims-mapping) б. [Работа с приложениями, поддерживающими утверждения](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-for-claims-aware-applications) в. [Настраиваемый жизненный цикл маркеров на платформе удостоверений Майкрософт](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes) г. [Настройка управления сеансом проверки подлинности с помощью условного доступа](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-conditional-access-session-lifetime) д. [Параметры файлов cookie для доступа к локальным приложениям](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-cookie-settings)
9. **Мне нужна помощь в управлении доступом пользователей и гостей (B2B)**. Подробные сведения об управлении доступом для пользователей и гостей, рекомендуется см. в следующих статьях: а.  [Управление доступом к приложениям](https://docs.microsoft.com/azure/active-directory/manage-apps/what-is-access-management) б. [Управление назначением пользователей для приложений в Azure Active Directory](https://docs.microsoft.com/azure/active-directory/manage-apps/assign-user-or-group-access-portal) в. [Настройка приложений SaaS для совместной работы B2B](https://docs.microsoft.com/azure/active-directory/external-identities/configure-saas-apps) г. [Предоставление доступа пользователям B2B в Azure AD к локальным приложениям](https://docs.microsoft.com/azure/active-directory/external-identities/configure-saas-apps) д. [Предоставление доступа локально управляемым партнерским учетным записям к облачным ресурсам с использованием совместной работы B2B службы Azure AD](https://docs.microsoft.com/azure/active-directory/external-identities/hybrid-on-premises-to-cloud)
10. **Я хочу настроить приложения**. Подробные сведения о настройке приложений см. в следующих статьях: а. [Настройка пользовательских доменов с помощью прокси-сервера приложения Azure AD](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-custom-domain) б. [Установка пользовательской домашней страницы для опубликованных приложений](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-custom-home-page) в. [Приложения с подстановочными знаками](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-wildcard)
11. **У меня возникают проблемы с переносом приложения из AD FS в Azure**. Чтобы устранить неполадки, возникающие во время миграции приложения из AD FS в Azure, рекомендуется ознакомиться со статьями: а. [Перенос проверки подлинности приложения из служб федерации Active Directory в Azure Active Directory](https://docs.microsoft.com/azure/active-directory/manage-apps/migrate-adfs-apps-to-azure) б. [Ресурсы для переноса приложений в Azure Active Directory](https://docs.microsoft.com/azure/active-directory/manage-apps/migration-resources)

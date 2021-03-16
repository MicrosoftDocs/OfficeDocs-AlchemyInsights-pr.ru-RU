---
title: Проблемы с API Microsoft Graph
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
- "9004345"
- "7759"
ms.openlocfilehash: a856094d9152568c3c067da5856153230d6590a6
ms.sourcegitcommit: 9d03083ea6e18070296b87a1b02339ca4d8e6064
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/29/2021
ms.locfileid: "50716205"
---
# <a name="microsoft-graph-api-issues"></a><span data-ttu-id="cfcae-102">Проблемы с API Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="cfcae-102">Microsoft Graph API issues</span></span>

<span data-ttu-id="cfcae-103">Этот раздел также может применяться к разработчикам, использующим API Azure AD Graph.</span><span class="sxs-lookup"><span data-stu-id="cfcae-103">This topic may also apply to developers still using Azure AD Graph API.</span></span> <span data-ttu-id="cfcae-104">Однако настоятельно рекомендуется **использовать** Microsoft Graph для всех сценариев управления каталогом, удостоверениями и доступом.</span><span class="sxs-lookup"><span data-stu-id="cfcae-104">However, it is **strongly** recommended that you use Microsoft Graph for all your directory, identity, and access management scenarios.</span></span>

<span data-ttu-id="cfcae-105">**Проблемы с проверкой подлинности или авторизацией**</span><span class="sxs-lookup"><span data-stu-id="cfcae-105">**Authentication or authorization issues**</span></span>

- <span data-ttu-id="cfcae-106">Если ваше  приложение не может приобрести маркеры для вызова Microsoft Graph, выберите проблему с получением категории Маркер доступа **(Проверка подлинности)** Microsoft Graph, чтобы получить более конкретную помощь и поддержку по этому вопросу.</span><span class="sxs-lookup"><span data-stu-id="cfcae-106">If your app is **unable to acquire tokens** to call Microsoft Graph, pick **Problem with getting an access token (Authentication)** Microsoft Graph category to get more specific help and support on this topic.</span></span>
- <span data-ttu-id="cfcae-107">Если ваше приложение получает **401 или 403** ошибки авторизации  при вызове Microsoft Graph, выберите категорию API API Microsoft Graph, чтобы получить более конкретную помощь и поддержку по этому вопросу.</span><span class="sxs-lookup"><span data-stu-id="cfcae-107">If your app is **receiving 401 or 403 authorization errors** when calling Microsoft Graph, pick the **Getting an access denied error (Authorization)** Microsoft Graph API category to get more specific help and support on this topic.</span></span>

<span data-ttu-id="cfcae-108">**Я хочу использовать Microsoft Graph, но не знаю, с чего начать**</span><span class="sxs-lookup"><span data-stu-id="cfcae-108">**I want to use Microsoft Graph, but not sure where to start**</span></span>

- [<span data-ttu-id="cfcae-109">Обзор Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="cfcae-109">Overview of Microsoft Graph</span></span>](https://docs.microsoft.com/graph/overview)
- [<span data-ttu-id="cfcae-110">Обзор управления удостоверением и доступом в Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="cfcae-110">Overview of Identity and Access Management in Microsoft Graph</span></span>](https://docs.microsoft.com/graph/azuread-identity-access-management-concept-overview)
- [<span data-ttu-id="cfcae-111">Начало создания приложений Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="cfcae-111">Getting started building Microsoft Graph apps</span></span>](https://docs.microsoft.com/graph/)
- <span data-ttu-id="cfcae-112">**Обозреватель Microsoft Graph** — тестирование API Microsoft Graph в клиенте или клиенте демонстрации</span><span class="sxs-lookup"><span data-stu-id="cfcae-112">**Microsoft Graph Explorer** - Test Microsoft Graph APIs in your tenant or a demo tenant</span></span>

<span data-ttu-id="cfcae-113">**Я хочу использовать Microsoft Graph, но поддерживает ли он API каталогов v1.0, которые мне нужны?**</span><span class="sxs-lookup"><span data-stu-id="cfcae-113">**I want to use Microsoft Graph, but does it support the v1.0 directory APIs I need?**</span></span>

<span data-ttu-id="cfcae-114">Microsoft Graph — это рекомендуемый API для управления каталогами, удостоверением и доступом.</span><span class="sxs-lookup"><span data-stu-id="cfcae-114">Microsoft Graph is the recommended API for directory, identity, and access management.</span></span> <span data-ttu-id="cfcae-115">Однако между возможными в Azure AD Graph и Microsoft Graph остаются некоторые пробелы.</span><span class="sxs-lookup"><span data-stu-id="cfcae-115">However, there are still a few gaps between what is possible in Azure AD Graph and Microsoft Graph.</span></span> <span data-ttu-id="cfcae-116">Просмотрите следующие статьи, в которых освещаются самые последние различия, которые помогут вам выбрать:</span><span class="sxs-lookup"><span data-stu-id="cfcae-116">Review the following articles, which highlight the most up-to-date differences to assist in your choice:</span></span>

- [<span data-ttu-id="cfcae-117">Различия типа ресурсов между Azure AD Graph и Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="cfcae-117">Resource type differences between Azure AD Graph and Microsoft Graph</span></span>](https://docs.microsoft.com/graph/migrate-azure-ad-graph-resource-differences)
- [<span data-ttu-id="cfcae-118">Различия свойств между Azure AD Graph и Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="cfcae-118">Property differences between Azure AD Graph and Microsoft Graph</span></span>](https://docs.microsoft.com/graph/migrate-azure-ad-graph-property-differences)
- [<span data-ttu-id="cfcae-119">Различия метода между Azure AD и Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="cfcae-119">Method differences between Azure AD and Microsoft Graph</span></span>](https://docs.microsoft.com/graph/migrate-azure-ad-graph-method-differences)

<span data-ttu-id="cfcae-120">**API, который я вызываю, не работает, где можно сделать больше тестирования?**</span><span class="sxs-lookup"><span data-stu-id="cfcae-120">**The API I am calling doesn't work - where can I do more testing?**</span></span>

<span data-ttu-id="cfcae-121">**Обозреватель Microsoft Graph** — проверьте API Microsoft Graph в клиенте или клиенте демонстрации, а также ознакомьтесь с примерами запросов **в** Microsoft Graph Explorer.</span><span class="sxs-lookup"><span data-stu-id="cfcae-121">**Microsoft Graph Explorer** - Test Microsoft Graph APIs in your tenant or a demo tenant and also check out the **sample queries** in Microsoft Graph Explorer.</span></span>

<span data-ttu-id="cfcae-122">**Мое приложение слишком медленно и также получает регулирование. Какие улучшения можно сделать?**</span><span class="sxs-lookup"><span data-stu-id="cfcae-122">**My app is too slow and is also getting throttled. What improvements can I make?**</span></span>

<span data-ttu-id="cfcae-123">В зависимости от сценария в вашем распоряжении имеется множество вариантов, которые сделают приложение более исполняемым, а в некоторых случаях менее подвержено регулированием со стороны службы (когда вы выполняете слишком много вызовов).</span><span class="sxs-lookup"><span data-stu-id="cfcae-123">Depending on your scenario, there are a variety of options at your disposal to make your application more performant, and in some cases, less prone to being throttled by the service (when you are making too many calls).</span></span>

- [<span data-ttu-id="cfcae-124">Лучшие практики Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="cfcae-124">Microsoft Graph best practices</span></span>](https://docs.microsoft.com/graph/best-practices-concept)
- [<span data-ttu-id="cfcae-125">Пакетные запросы</span><span class="sxs-lookup"><span data-stu-id="cfcae-125">Batching requests</span></span>](https://docs.microsoft.com/graph/json-batching)
- [<span data-ttu-id="cfcae-126">Отслеживание изменений с помощью запроса delta</span><span class="sxs-lookup"><span data-stu-id="cfcae-126">Track changes through delta query</span></span>](https://docs.microsoft.com/graph/delta-query-overview)
- [<span data-ttu-id="cfcae-127">Получать уведомления об изменениях через веб-сайты</span><span class="sxs-lookup"><span data-stu-id="cfcae-127">Get notified of changes through webhooks</span></span>](https://docs.microsoft.com/graph/webhooks)
- [<span data-ttu-id="cfcae-128">Руководство по регулированием</span><span class="sxs-lookup"><span data-stu-id="cfcae-128">Throttling guidance</span></span>](https://docs.microsoft.com/graph/throttling)

<span data-ttu-id="cfcae-129">**Где можно найти дополнительные сведения об ошибках и известных проблемах?**</span><span class="sxs-lookup"><span data-stu-id="cfcae-129">**Where can I find more information on errors and known issues?**</span></span>

- [<span data-ttu-id="cfcae-130">Сведения об ошибке Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="cfcae-130">Microsoft Graph error response information</span></span>](https://docs.microsoft.com/graph/errors)
- [<span data-ttu-id="cfcae-131">Известные проблемы с Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="cfcae-131">Known issues with Microsoft Graph</span></span>](https://docs.microsoft.com/graph/known-issues)

<span data-ttu-id="cfcae-132">**Где можно проверить состояние доступности и подключения к службе?**</span><span class="sxs-lookup"><span data-stu-id="cfcae-132">**Where can I check status of service availability and connectivity?**</span></span>

<span data-ttu-id="cfcae-133">Доступность и подключение к службам, к которые можно получить доступ через Microsoft Graph, может повлиять на общую доступность и производительность Microsoft Graph.</span><span class="sxs-lookup"><span data-stu-id="cfcae-133">The service availability and connectivity of the underlying services that can be accessed through Microsoft Graph can impact the overall availability and performance of Microsoft Graph.</span></span>

- <span data-ttu-id="cfcae-134">Чтобы проверить состояние службы Azure Active Directory, проверьте состояние служб **безопасности и** удостоверений, перечисленных на странице [состояние Azure.](https://azure.microsoft.com/status/)</span><span class="sxs-lookup"><span data-stu-id="cfcae-134">For Azure Active Directory service health, check the status of **Security + Identity** services listed in the [Azure status page](https://azure.microsoft.com/status/).</span></span>
- <span data-ttu-id="cfcae-135">Для служб Office, которые вносят вклад в Microsoft Graph, проверьте состояние служб, перечисленных в панели мониторинга здоровья служб [Office.](https://portal.office.com/adminportal/home#/servicehealth)</span><span class="sxs-lookup"><span data-stu-id="cfcae-135">For Office services that contribute to Microsoft Graph, check the status of services listed in the [Office Service Health Dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>

<span data-ttu-id="cfcae-136">Ошибки авторизации Microsoft Graph могут быть результатом нескольких различных проблем, большинство из которых создают ошибку 401 или 403.</span><span class="sxs-lookup"><span data-stu-id="cfcae-136">Microsoft Graph authorization errors can be a result of several different issues, most of which generate a 401 or 403 error.</span></span> <span data-ttu-id="cfcae-137">Например, ошибки авторизации могут возникнуть в результате следующих неполадок:</span><span class="sxs-lookup"><span data-stu-id="cfcae-137">For example, the following can all lead to authorization errors:</span></span>

- <span data-ttu-id="cfcae-138">Некорректные [потоки получения маркеров доступа](https://docs.microsoft.com/azure/active-directory/develop/active-directory-authentication-scenarios)</span><span class="sxs-lookup"><span data-stu-id="cfcae-138">Incorrect [access token acquisition flows](https://docs.microsoft.com/azure/active-directory/develop/active-directory-authentication-scenarios)</span></span>
- <span data-ttu-id="cfcae-139">Неправильно настроенные [области разрешений](https://docs.microsoft.com/azure/active-directory/develop/active-directory-v2-scopes)</span><span class="sxs-lookup"><span data-stu-id="cfcae-139">Poorly configured [permission scopes](https://docs.microsoft.com/azure/active-directory/develop/active-directory-v2-scopes)</span></span>
- <span data-ttu-id="cfcae-140">Отсутствие [согласия](https://docs.microsoft.com/azure/active-directory/develop/active-directory-devhowto-multi-tenant-overview#understanding-user-and-admin-consent)</span><span class="sxs-lookup"><span data-stu-id="cfcae-140">Lack of [consent](https://docs.microsoft.com/azure/active-directory/develop/active-directory-devhowto-multi-tenant-overview#understanding-user-and-admin-consent)</span></span>

<span data-ttu-id="cfcae-141">\**_Окончание поддержки Библиотеки проверки подлинности Azure Active Directory (ADAL) и API Azure AD Graph (AAD Graph_*)_</span><span class="sxs-lookup"><span data-stu-id="cfcae-141">\**_End of support for Azure Active Directory Authentication Library (ADAL) and Azure AD Graph API (AAD Graph)_* _</span></span>

<span data-ttu-id="cfcae-142">_\*Начиная с 30 июня 2020 г.\*\*, мы больше не будем добавлять новые функции в ADAL и Azure AD Graph.</span><span class="sxs-lookup"><span data-stu-id="cfcae-142">_\*Starting June 30th, 2020\*\*, we will no longer add any new features to ADAL and Azure AD Graph.</span></span> <span data-ttu-id="cfcae-143">Мы продолжим предоставлять техническую поддержку и обновления для системы безопасности, но больше не будем предоставлять обновления компонентов.</span><span class="sxs-lookup"><span data-stu-id="cfcae-143">We will continue to provide technical support and security updates but will no longer provide feature updates.</span></span>

<span data-ttu-id="cfcae-144">**Начиная с 30 июня 2022** г. мы переимеем поддержку ADAL и Azure AD Graph и больше не будем предоставлять техническую поддержку или обновления безопасности.</span><span class="sxs-lookup"><span data-stu-id="cfcae-144">**Starting June 30th, 2022**, we will end support for ADAL and Azure AD Graph and will no longer provide technical support or security updates.</span></span>

<span data-ttu-id="cfcae-145">Приложения, использующие ADAL в существующих версиях ОС, продолжат работать после этого времени, но не получат никакой технической поддержки *или обновлений безопасности.*</span><span class="sxs-lookup"><span data-stu-id="cfcae-145">Apps using ADAL on existing OS versions will continue to work after this time but will not *get any technical support or security updates*.</span></span>

<span data-ttu-id="cfcae-146">Приложения, использующие Azure AD Graph после этого времени, могут больше не получать ответы из конечной точки Azure AD Graph.</span><span class="sxs-lookup"><span data-stu-id="cfcae-146">Apps using Azure AD Graph after this time may no longer receive responses from the Azure AD Graph endpoint.</span></span>

<span data-ttu-id="cfcae-147">**Миграция ADAL**</span><span class="sxs-lookup"><span data-stu-id="cfcae-147">**ADAL Migration**</span></span>

<span data-ttu-id="cfcae-148">Мы рекомендуем выполнить обновление до [Библиотеки проверки подлинности Microsoft (MSAL)](https://docs.microsoft.com/azure/active-directory/develop/v2-overview), включающей новые возможности и обновления для системы безопасности.</span><span class="sxs-lookup"><span data-stu-id="cfcae-148">We recommend updating to the [Microsoft Authentication Library (MSAL)](https://docs.microsoft.com/azure/active-directory/develop/v2-overview), which has the latest features and security updates.</span></span>

<span data-ttu-id="cfcae-149">Если вы используете приложения Майкрософт, знайте, что Корпорация Майкрософт в процессе переноса своих приложений в MSAL к концу срока поддержки, гарантируя, что они будут извлекать выгоду из текущих улучшений безопасности и функций MSAL.</span><span class="sxs-lookup"><span data-stu-id="cfcae-149">If you are using Microsoft apps, know that Microsoft is in the process of migrating its applications to MSAL by the end-of-support deadline, ensuring they'll benefit from MSAL's ongoing security and feature improvements.</span></span>

1. [<span data-ttu-id="cfcae-150">Ознакомьтесь с вопросами и ответами по ADAL</span><span class="sxs-lookup"><span data-stu-id="cfcae-150">Read the ADAL FAQ</span></span>](https://docs.microsoft.com/azure/active-directory/develop/msal-migration#frequently-asked-questions-faq)
2. [<span data-ttu-id="cfcae-151">Сведения о миграции приложений для каждой платформы</span><span class="sxs-lookup"><span data-stu-id="cfcae-151">Learn about how to migrate apps on a per-platform basis</span></span>](https://docs.microsoft.com/azure/active-directory/develop/msal-migration#frequently-asked-questions-faq)
3. <span data-ttu-id="cfcae-152">Если вам нужна помощь в понимании того, какие из ваших приложений используют ADAL, рекомендуется просмотреть все исходные коды своих приложений, а если это применимо, связаться с любыми поставщиками isV или app.</span><span class="sxs-lookup"><span data-stu-id="cfcae-152">If you need help understanding which of your apps use ADAL, we recommend you review all of your apps' source code, and if applicable, reach out to any ISVs or app providers.</span></span> <span data-ttu-id="cfcae-153">Кроме того, служба поддержки корпорации Майкрософт может предоставить вам список всех приложений сторонних разработчиков, использующих ADAL, в вашем клиенте.</span><span class="sxs-lookup"><span data-stu-id="cfcae-153">Microsoft support can also provide you with a list of all non-Microsoft ADAL apps in your tenant.</span></span>

<span data-ttu-id="cfcae-154">**Миграция приложений, использующих AAD Graph**</span><span class="sxs-lookup"><span data-stu-id="cfcae-154">**AAD Graph Migration**</span></span>

<span data-ttu-id="cfcae-155">Для приложений, использующих Azure AD Graph, следуйте нашим указаниям по переносу [приложений Azure AD Graph в Microsoft Graph.](https://docs.microsoft.com/graph/migrate-azure-ad-graph-overview)</span><span class="sxs-lookup"><span data-stu-id="cfcae-155">For applications that are using Azure AD Graph, follow our guidance to [migrate Azure AD Graph apps to Microsoft Graph](https://docs.microsoft.com/graph/migrate-azure-ad-graph-overview).</span></span>

1. <span data-ttu-id="cfcae-156">[Контрольный список миграции содержит стартовую точку](https://docs.microsoft.com/graph/migrate-azure-ad-graph-planning-checklist).</span><span class="sxs-lookup"><span data-stu-id="cfcae-156">[Our migration checklist provides a getting started point](https://docs.microsoft.com/graph/migrate-azure-ad-graph-planning-checklist).</span></span>
2. <span data-ttu-id="cfcae-157">На портале регистрации приложений Azure показано, какие приложения используют AAD Graph.</span><span class="sxs-lookup"><span data-stu-id="cfcae-157">Your Azure app registration portal shows which applications are using AAD Graph.</span></span> <span data-ttu-id="cfcae-158">Рекомендуем просмотреть исходный код всех приложений и, если возможно, связаться с независимыми поставщиками программного обеспечения (ISV) или поставщиками приложений.</span><span class="sxs-lookup"><span data-stu-id="cfcae-158">We recommend you review all of your apps' source code, and if applicable, reach out to any ISVs or app providers.</span></span> <span data-ttu-id="cfcae-159">Служба поддержки Майкрософт также может предоставить вам список всех данных об использовании AAD Graph в клиенте.</span><span class="sxs-lookup"><span data-stu-id="cfcae-159">Microsoft support can also provide you with a list of all AAD Graph usage in your tenant.</span></span>
3. <span data-ttu-id="cfcae-160">Чтобы приложение имело доступ к данным в Microsoft Graph, пользователь или администратор должен предоставить ему соответствующие разрешения с помощью процедуры получения согласия.</span><span class="sxs-lookup"><span data-stu-id="cfcae-160">For your app to access data in Microsoft Graph, the user or administrator must grant it the correct permissions via a consent process.</span></span> <span data-ttu-id="cfcae-161">В [справке разрешений](https://docs.microsoft.com/graph/permissions-reference) Microsoft Graph перечислены разрешения, связанные с каждым основным набором API Microsoft Graph.</span><span class="sxs-lookup"><span data-stu-id="cfcae-161">The [Microsoft Graph permissions reference](https://docs.microsoft.com/graph/permissions-reference) lists the permissions associated with each major set of Microsoft Graph APIs.</span></span> <span data-ttu-id="cfcae-162">В ней также приведены руководства по использованию разрешений.</span><span class="sxs-lookup"><span data-stu-id="cfcae-162">It also provides guidance about how to use the permissions.</span></span>
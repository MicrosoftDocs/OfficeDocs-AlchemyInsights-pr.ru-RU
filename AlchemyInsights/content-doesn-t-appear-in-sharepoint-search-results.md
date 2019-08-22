---
title: Контент не отображается в результатах поиска SharePoint
ms.author: tlarsen
author: tklarsen
ms.date: 1/8/2019
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "750"
- "5300017"
ms.assetid: 693db84f-2737-4c21-b027-4ab3d121b4a8
ms.openlocfilehash: ffb6bf349f9e8c2323186a8fc3183325d1d7e1bf
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 08/22/2019
ms.locfileid: "36517044"
---
# <a name="content-doesnt-appear-in-sharepoint-search-results"></a><span data-ttu-id="ef1fe-102">Контент не отображается в результатах поиска SharePoint</span><span class="sxs-lookup"><span data-stu-id="ef1fe-102">Content doesn't appear in SharePoint search results</span></span>

<span data-ttu-id="ef1fe-103">Выполните следующие действия по устранению неполадок, когда ожидаемое содержимое не отображается в результатах поиска:</span><span class="sxs-lookup"><span data-stu-id="ef1fe-103">Follow these troubleshooting steps when expected content doesn't appear in search results:</span></span>
  
1. <span data-ttu-id="ef1fe-104">Убедитесь, что **сайт** , который содержит ожидаемый контент, настроен на разрешение отображения контента в результатах поиска.</span><span class="sxs-lookup"><span data-stu-id="ef1fe-104">Check that the **site** that contains the expected content is set to allow content to appear in search results.</span></span> <span data-ttu-id="ef1fe-105">Выполните действия, описанные в разделе [Просмотр контента сайта в результатах поиска](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-on-a-site-in-search-results).</span><span class="sxs-lookup"><span data-stu-id="ef1fe-105">Follow the steps in [Show content on a site in search results](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-on-a-site-in-search-results).</span></span>

2. <span data-ttu-id="ef1fe-106">Убедитесь, что **список** или **Библиотека** , содержащие ожидаемый контент, настроены на разрешение отображения контента в результатах поиска.</span><span class="sxs-lookup"><span data-stu-id="ef1fe-106">Check that the **list** or **library** that contains the expected content is set to allow content to appear in search results.</span></span> <span data-ttu-id="ef1fe-107">Выполните действия, описанные в статье [Показать содержимое из списков или библиотек в результатах поиска](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-from-lists-or-libraries-in-search-results).</span><span class="sxs-lookup"><span data-stu-id="ef1fe-107">Follow the steps in [Show content from lists or libraries in search results](https://docs.microsoft.com/sharepoint/make-site-content-searchable#show-content-from-lists-or-libraries-in-search-results).</span></span>

3. <span data-ttu-id="ef1fe-108">Убедитесь, что страница, документ или пользовательский макет страницы опубликованы в качестве **основной версии.**</span><span class="sxs-lookup"><span data-stu-id="ef1fe-108">Verify that the page, document, or custom page layout is published as a **Major version.**</span></span> <span data-ttu-id="ef1fe-109">Выполните шаг 3 в разделе [Поиск не возвращает все результаты в SharePoint Online](https://go.microsoft.com/fwlink/?linkid=874525).</span><span class="sxs-lookup"><span data-stu-id="ef1fe-109">Follow step 3 in [Search doesn't return all results in SharePoint Online](https://go.microsoft.com/fwlink/?linkid=874525).</span></span>

4. <span data-ttu-id="ef1fe-110">Убедитесь, что у пользователя есть **разрешения** на просмотр контента.</span><span class="sxs-lookup"><span data-stu-id="ef1fe-110">Verify that the user has **permissions** to view the content.</span></span> <span data-ttu-id="ef1fe-111">Выполните действия, описанные в статье [Общие сведения о уровнях разрешений в SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span><span class="sxs-lookup"><span data-stu-id="ef1fe-111">Follow the steps in [Understanding permission levels in SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span></span>
    
5. <span data-ttu-id="ef1fe-112">Если схема поиска была изменена путем добавления нового управляемого свойства, редактирования управляемого свойства или удаления управляемого свойства, потребуется выполнить обход контента и повторное индексирование.</span><span class="sxs-lookup"><span data-stu-id="ef1fe-112">If the search schema has been changed by adding a new managed property, by editing a managed property, or by removing a managed property then requesting a crawl and re-index will be required.</span></span> <span data-ttu-id="ef1fe-113">**Выполните повторную индексацию** контента, выполнив действия, описанные в статье [Ручное сканирование и повторная индексация сайта, библиотеки или списка](https://docs.microsoft.com/sharepoint/crawl-site-content).</span><span class="sxs-lookup"><span data-stu-id="ef1fe-113">**Re-index** the content by following the steps in [Manually request crawling and re-indexing of a site, a library or a list](https://docs.microsoft.com/sharepoint/crawl-site-content).</span></span> <span data-ttu-id="ef1fe-114">Это может занять некоторое время, подождите 24 часа, прежде чем снова будет проверять результаты.</span><span class="sxs-lookup"><span data-stu-id="ef1fe-114">This might take a while, wait 24 hours before checking the results again.</span></span>

<span data-ttu-id="ef1fe-115">Дополнительные сведения можно найти в статье [Включение поддержки поиска контента на сайте](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span><span class="sxs-lookup"><span data-stu-id="ef1fe-115">For more information, see [Enable content on a site to be searchable](https://docs.microsoft.com/sharepoint/make-site-content-searchable).</span></span> 
  

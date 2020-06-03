---
title: Код ошибки 550 5.7.501 отказано в доступе, обнаружена Нежелательная почта
ms.author: chrisda
author: chrisda
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "351"
- "3100015"
ms.assetid: 3105905c-e7a0-42a7-9c5a-61dc56a1d6fc
ms.openlocfilehash: 9fd4f14798f27e7bf93daceb3620aff9b7f9e8ed
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506823"
---
# <a name="550-57501-access-denied-spam-abuse-detected"></a><span data-ttu-id="1ff15-102">550 5.7.501 отказано в доступе, обнаружена Нежелательная почта</span><span class="sxs-lookup"><span data-stu-id="1ff15-102">550 5.7.501 Access denied, spam abuse detected</span></span>

<span data-ttu-id="1ff15-103">Как правило, это сообщение появляется, когда пользователи отправляют сообщения электронной почты с IP-адресов с помощью начального домена *onmicrosoft.com* , назначенного новым клиентам в Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="1ff15-103">Typically, this message occurs when users send email messages from IP addresses using the initial *.onmicrosoft.com* domain that's assigned to new tenants in Microsoft 365.</span></span> <span data-ttu-id="1ff15-104">Самый простой способ устранить эту проблему:</span><span class="sxs-lookup"><span data-stu-id="1ff15-104">The easiest way to resolve this problem is to:</span></span>

1. <span data-ttu-id="1ff15-105">[Добавление домена в клиент](https://docs.microsoft.com/microsoft-365/admin/setup/add-domain).</span><span class="sxs-lookup"><span data-stu-id="1ff15-105">[Add a domain to your tenant](https://docs.microsoft.com/microsoft-365/admin/setup/add-domain).</span></span>

2. <span data-ttu-id="1ff15-106">[Измените основной адрес электронной почты пользователя](https://docs.microsoft.com/microsoft-365/admin/add-users/change-a-user-name-and-email-address) на новый личный домен, который вы только что добавили.</span><span class="sxs-lookup"><span data-stu-id="1ff15-106">[Change your users' primary email address](https://docs.microsoft.com/microsoft-365/admin/add-users/change-a-user-name-and-email-address) to the new custom domain you just added.</span></span>

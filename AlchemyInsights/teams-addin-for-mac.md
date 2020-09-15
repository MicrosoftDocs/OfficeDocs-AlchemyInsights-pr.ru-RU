---
title: Надстройка Teams для Mac
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 08/10/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "6173"
- "9003233"
ms.openlocfilehash: 1e5f6d66386398ad8600f9383f9f7a1dcf0ce69f
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/14/2020
ms.locfileid: "47670341"
---
# <a name="teams-add-in-for-mac"></a><span data-ttu-id="5ed69-102">Надстройка Teams для Mac</span><span class="sxs-lookup"><span data-stu-id="5ed69-102">Teams add-in for Mac</span></span>

<span data-ttu-id="5ed69-103">Чтобы устранить проблему с отсутствующей надстройкой Teams для пользователей операционной системы компьютеров Mac, выполните следующие действия:</span><span class="sxs-lookup"><span data-stu-id="5ed69-103">To troubleshoot a missing Teams add-in for Mac operating system users, follow these steps:</span></span>

<span data-ttu-id="5ed69-104">**Шаг 1.** При локальном применении гибридной среды Exchange (версия 2016 с накопительным пакетом обновления 3 или более поздняя версия) используйте средство Test-HMA.ps1, чтобы подтвердить правильность настройки гибридной современной проверки подлинности.</span><span class="sxs-lookup"><span data-stu-id="5ed69-104">**Step 1:** If you have Hybrid Exchange On-Premises (2016 CU3 or later required), use the Test-HMA.ps1 tool to confirm that Hybrid Modern Authentication is correctly configured.</span></span> <span data-ttu-id="5ed69-105">Дополнительные сведения см. в разделе [Проверка настройки гибридной современной проверки подлинности в Outlook для iOS и Android](https://aka.ms/AA980zq).</span><span class="sxs-lookup"><span data-stu-id="5ed69-105">For more info, see [Validating Hybrid Modern Authentication setup for Outlook for iOS and Android](https://aka.ms/AA980zq).</span></span>  

<span data-ttu-id="5ed69-106">**Примечание**. Используйте формат адреса UPN (например, [имя_пользователя@contoso.com](mailto:username@contoso.com)), а не домен\имя_пользователя.</span><span class="sxs-lookup"><span data-stu-id="5ed69-106">**Note** Use the UPN address format (for example, [username@contoso.com](mailto:username@contoso.com)), not domain\username.</span></span> <span data-ttu-id="5ed69-107">Выполняйте это даже для пользователей с почтовыми ящиками Exchange Online.</span><span class="sxs-lookup"><span data-stu-id="5ed69-107">Do this even for users with Exchange Online mailboxes.</span></span>

<span data-ttu-id="5ed69-108">**Шаг 2.** Попросите пользователя перейти в раздел **Средства** > **Учетные записи**... в Outlook для Mac, а затем найти и выбрать учетную запись.</span><span class="sxs-lookup"><span data-stu-id="5ed69-108">**Step 2:** Have the user go to **Tools** > **Accounts**... in Outlook for Mac, and find and select the account.</span></span> <span data-ttu-id="5ed69-109">Убедитесь, что имя пользователя указано в формате UPN (например, [имя_пользователя@contoso.com](mailto:username@contoso.com)).</span><span class="sxs-lookup"><span data-stu-id="5ed69-109">Confirm the username listed is in UPN format (for example, [username@contoso.com](mailto:username@contoso.com)).</span></span>

<span data-ttu-id="5ed69-110">**Шаг 3.** Подтвердите, что пользователь является лицензированным пользователем Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="5ed69-110">**Step 3:** Confirm the user is a licensed Microsoft Teams user.</span></span> <span data-ttu-id="5ed69-111">Пользователь должен использовать подписку на Office 365 для Mac версии 16.24 или более поздней.</span><span class="sxs-lookup"><span data-stu-id="5ed69-111">The user must be using the Office 365 for Mac subscription, product version 16.24 or later.</span></span>
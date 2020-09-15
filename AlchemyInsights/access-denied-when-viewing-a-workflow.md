---
title: Отказано в доступе при просмотре рабочего процесса
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: 710775e8b2dee98969df7a4c8410a3e61181aaf6
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/14/2020
ms.locfileid: "47688815"
---
# <a name="access-denied-when-viewing-a-workflow"></a><span data-ttu-id="9584e-102">Отказано в доступе при просмотре рабочего процесса</span><span class="sxs-lookup"><span data-stu-id="9584e-102">Access denied when viewing a Workflow</span></span>

<span data-ttu-id="9584e-103">Рабочие процессы SharePoint 2013, которые пытаются отправить сообщение в группу SharePoint, могут привести к сбою с сообщением об ошибке "отказано в доступе", если для группы SharePoint не задано значение "все".</span><span class="sxs-lookup"><span data-stu-id="9584e-103">SharePoint 2013 Workflows that attempt to send an email to a SharePoint group can fail with an "Access Denied" error message if the membership of the SharePoint group is not set to Everyone.</span></span>
  
 <span data-ttu-id="9584e-104">**Чтобы устранить эту проблему, выполните указанные ниже действия.**</span><span class="sxs-lookup"><span data-stu-id="9584e-104">**To resolve this issue, do these steps:**</span></span>
  
 1. <span data-ttu-id="9584e-105">Разрешить всем пользователям просматривать участников группы SharePoint.</span><span class="sxs-lookup"><span data-stu-id="9584e-105">Allow everybody to see the members of the SharePoint group.</span></span>
  
 2. <span data-ttu-id="9584e-106">Удаление группы SharePoint из строки "Кому" или "копия" сообщения электронной почты.</span><span class="sxs-lookup"><span data-stu-id="9584e-106">Remove the SharePoint group from the To or CC line of the email.</span></span>
  
 3. <span data-ttu-id="9584e-107">Явно добавьте пользователей в строку "Кому" или "копия", если невозможно изменить видимость членства для группы SharePoint.</span><span class="sxs-lookup"><span data-stu-id="9584e-107">Explicitly add the users to the To or CC line if the membership visibility cannot be changed for SharePoint group.</span></span>
  
<span data-ttu-id="9584e-108">Чтобы просмотреть дополнительные сведения, обратитесь к разделу [http несанкционированный доступ к/_vti_bin/клиент.СВК/СП.утилитиес.утилити.сендемаил](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="9584e-108">To view more details please refer to [HTTP Unauthorized to /_vti_bin/client.svc/sp.utilities.utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span></span>
  
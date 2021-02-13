---
title: Блокировка пользовательских подписей электронной почты
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/18/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1200009"
- "7310"
ms.openlocfilehash: dab7eacb617c8f3a8bd63634e974166b6e448d75
ms.sourcegitcommit: 2f39850ac0fba9fbeba9b8b7939ae79b505d3b67
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 02/12/2021
ms.locfileid: "50232814"
---
# <a name="block-user-made-email-signatures"></a><span data-ttu-id="71a21-102">Блокировка пользовательских подписей электронной почты</span><span class="sxs-lookup"><span data-stu-id="71a21-102">Block user-made email signatures</span></span>

<span data-ttu-id="71a21-103">Следующее решение применимо только к подписям электронной почты, созданным в Outlook в Интернете.</span><span class="sxs-lookup"><span data-stu-id="71a21-103">The following solution only applies to email signatures created in Outlook on the web.</span></span> <span data-ttu-id="71a21-104">Подписи в приложении Outlook можно заблокировать только при локальной Exchange Server.</span><span class="sxs-lookup"><span data-stu-id="71a21-104">You can only block signatures in the Outlook app if you have an on-premises Exchange Server.</span></span>

1. <span data-ttu-id="71a21-105">В Центре администрирования выберите **"Центры администрирования**  >  **Exchange".**</span><span class="sxs-lookup"><span data-stu-id="71a21-105">In the admin center, choose **Admin centers** > **Exchange**.</span></span>
2. <span data-ttu-id="71a21-106">Щелкните **разрешения**  >  **Outlook Web App политик.**</span><span class="sxs-lookup"><span data-stu-id="71a21-106">Click **permissions** > **Outlook Web App policies**.</span></span>
3. <span data-ttu-id="71a21-107">Выберите политику и щелкните значок карандаша, чтобы изменить ее.</span><span class="sxs-lookup"><span data-stu-id="71a21-107">Select the policy, and then click the pencil icon to edit it.</span></span>
4. <span data-ttu-id="71a21-108">Щелкните   >  **"Функции" Дополнительные параметры.**</span><span class="sxs-lookup"><span data-stu-id="71a21-108">Click **features** > **More options**.</span></span>
5. <span data-ttu-id="71a21-109">В **окне "Пользовательский интерфейс"** пойдите на **проверку подписи** электронной почты и нажмите кнопку **"Сохранить".**</span><span class="sxs-lookup"><span data-stu-id="71a21-109">Under **User experience**, clear the **Email signature** check box, and then click **Save**.</span></span>

<span data-ttu-id="71a21-110">**Важно!** Если подпись была добавлена перед очисткой этого контрольного окна, пользователь по-прежнему сможет ее использовать.</span><span class="sxs-lookup"><span data-stu-id="71a21-110">**Important:** If a signature was added before clearing this check box, the user will still be able to use it.</span></span> <span data-ttu-id="71a21-111">Попросите их удалить его.</span><span class="sxs-lookup"><span data-stu-id="71a21-111">Ask them to remove it.</span></span>

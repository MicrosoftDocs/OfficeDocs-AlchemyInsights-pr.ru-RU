---
title: Автоматически шифруются сообщения электронной почты Office 365, отправленные в определенные домены
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/24/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000078"
- "7342"
ms.openlocfilehash: 7fb96a30cd1922bd39a4b99a7ecd869622f3a466
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/11/2021
ms.locfileid: "50737589"
---
# <a name="automatically-encrypt-office-365-email-messages-sent-to-certain-domains"></a><span data-ttu-id="70402-102">Автоматически шифруются сообщения электронной почты Office 365, отправленные в определенные домены</span><span class="sxs-lookup"><span data-stu-id="70402-102">Automatically encrypt Office 365 email messages sent to certain domains</span></span>

1. <span data-ttu-id="70402-103">В центре [администрирования Exchange](https://outlook.office365.com/ecp/)выберите поток **почты > правила.**</span><span class="sxs-lookup"><span data-stu-id="70402-103">From the [Exchange admin center](https://outlook.office365.com/ecp/), choose **mail flow > rules**.</span></span> 
2. <span data-ttu-id="70402-104">Щелкните **значок New (+)** и нажмите кнопку **Применить шифрование сообщений Office 365** и защиту прав на сообщения.</span><span class="sxs-lookup"><span data-stu-id="70402-104">Click the **New (+)** icon, and then click **Apply Office 365 Message Encryption and rights protection to messages**.</span></span>
3. <span data-ttu-id="70402-105">В **Name** введите имя правила, например шифруем сообщений, отправленных *в contoso.com.*</span><span class="sxs-lookup"><span data-stu-id="70402-105">In **Name**, enter a name for the rule, such as *Encrypt messages sent to contoso.com*.</span></span>
4. <span data-ttu-id="70402-106">В **Применение этого правила,** если выберите получателя > **домена**.</span><span class="sxs-lookup"><span data-stu-id="70402-106">In **Apply this rule if**, choose **The recipient > domain is**.</span></span> 
5. <span data-ttu-id="70402-107">Введите имя домена, например **contoso.com.**</span><span class="sxs-lookup"><span data-stu-id="70402-107">Enter the name of the domain, such as **contoso.com**.</span></span>
6. <span data-ttu-id="70402-108">Щелкните **значок Добавить (+)** и нажмите **кнопку ОК**.</span><span class="sxs-lookup"><span data-stu-id="70402-108">Click the **Add (+)** icon, and then click **OK**.</span></span>
7. <span data-ttu-id="70402-109">Рядом со следующим **полем Do** щелкните **Выберите одно.**</span><span class="sxs-lookup"><span data-stu-id="70402-109">Next to the **Do the following** field, click **Select one**.</span></span> 
8. <span data-ttu-id="70402-110">В **выпадаемом меню** шаблона RMS выберите **Шифруй** и нажмите **кнопку ОК.**</span><span class="sxs-lookup"><span data-stu-id="70402-110">In the **RMS template** drop-down menu, select **Encrypt**, and then click **OK**.</span></span> <span data-ttu-id="70402-111">(Если вы не видите этот параметр, это означает, что ваш план не включает автоматическое шифрование.</span><span class="sxs-lookup"><span data-stu-id="70402-111">(If you don't see this option, it means your plan doesn't include automatic encryption.</span></span> <span data-ttu-id="70402-112">Но вы можете добавить его!)</span><span class="sxs-lookup"><span data-stu-id="70402-112">But you can add it!)</span></span>
9. <span data-ttu-id="70402-113">Выберите любой необязательный выбор (из списка необязательных выборов, которые можно сделать на данном этапе, многие из которых можно оставить с параметром по умолчанию для простоты).</span><span class="sxs-lookup"><span data-stu-id="70402-113">Choose any optional selection (from a list of optional selections that you can make at this point, many of which can be left with the default setting for simplicity).</span></span>
10. <span data-ttu-id="70402-114">Щелкните **Сохранить**.</span><span class="sxs-lookup"><span data-stu-id="70402-114">Click **Save**.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="70402-115">Вы всегда можете вернуться и изменить это правило позже.</span><span class="sxs-lookup"><span data-stu-id="70402-115">You can always come back and edit this rule later.</span></span>

<span data-ttu-id="70402-116">Дополнительные сведения о создании правил шифрования см. в тексте Определение правил потока почты для шифрования сообщений электронной почты [в Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email)</span><span class="sxs-lookup"><span data-stu-id="70402-116">For more information about creating rules for encryption, see [Define mail flow rules to encrypt email messages in Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email)</span></span>
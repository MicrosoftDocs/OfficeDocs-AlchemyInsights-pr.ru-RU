---
title: Автоматическое шифрование определенных сообщений электронной почты из Office 365
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
ms.openlocfilehash: 5ddaaed361f6ec934cfffb00cc62a9df2d1a04e8
ms.sourcegitcommit: c202c0df2d141e63f4f7eb13a56efbfc2f57348f
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/05/2021
ms.locfileid: "50510222"
---
# <a name="automatically-encrypt-certain-email-messages-from-office-365"></a><span data-ttu-id="3bba9-102">Автоматическое шифрование определенных сообщений электронной почты из Office 365</span><span class="sxs-lookup"><span data-stu-id="3bba9-102">Automatically encrypt certain email messages from office 365</span></span>

1. <span data-ttu-id="3bba9-103">В центре [администрирования Exchange](https://outlook.office365.com/ecp/)выберите поток **почты > правила.**</span><span class="sxs-lookup"><span data-stu-id="3bba9-103">From the [Exchange admin center](https://outlook.office365.com/ecp/), choose **mail flow > rules**.</span></span> 
2. <span data-ttu-id="3bba9-104">Щелкните **значок New (+)** и нажмите кнопку **Применить шифрование сообщений Office 365** и защиту прав на сообщения.</span><span class="sxs-lookup"><span data-stu-id="3bba9-104">Click the **New (+)** icon, and then click **Apply Office 365 Message Encryption and rights protection to messages**.</span></span>
3. <span data-ttu-id="3bba9-105">В **Name** введите имя правила, например *Шифруй все сообщения.*</span><span class="sxs-lookup"><span data-stu-id="3bba9-105">In **Name**, enter a name for the rule, such as *Encrypt all messages*.</span></span>
4. <span data-ttu-id="3bba9-106">В **Применить это правило, если**, выберите **[Применить для всех сообщений]**.</span><span class="sxs-lookup"><span data-stu-id="3bba9-106">In **Apply this rule if**, choose **[Apply to all messages]**.</span></span> 
5. <span data-ttu-id="3bba9-107">Рядом со следующим **полем Do** щелкните **Выберите одно.**</span><span class="sxs-lookup"><span data-stu-id="3bba9-107">Next to the **Do the following** field, click **Select one**.</span></span> 
6. <span data-ttu-id="3bba9-108">В **выпадаемом меню** шаблона RMS выберите **Шифруй** и нажмите **кнопку ОК.**</span><span class="sxs-lookup"><span data-stu-id="3bba9-108">In the **RMS template** drop-down menu, select **Encrypt**, and then click **OK**.</span></span> <span data-ttu-id="3bba9-109">(Если вы не видите этот параметр, это означает, что ваш план не включает автоматическое шифрование.</span><span class="sxs-lookup"><span data-stu-id="3bba9-109">(If you don't see this option, it means your plan doesn't include automatic encryption.</span></span> <span data-ttu-id="3bba9-110">Но вы можете добавить его!)</span><span class="sxs-lookup"><span data-stu-id="3bba9-110">But you can add it!)</span></span>
7. <span data-ttu-id="3bba9-111">Проверьте это **правило с помощью контрольного окна** уровня серьезности, а затем выберите нужный уровень.</span><span class="sxs-lookup"><span data-stu-id="3bba9-111">Check the **Audit this rule with severity level** check box, and then select the desired level.</span></span> <span data-ttu-id="3bba9-112">Если у вашей компании есть контрактные обязательства по отправке всех зашифрованных сообщений электронной почты, я рекомендую установить уровень **high**.</span><span class="sxs-lookup"><span data-stu-id="3bba9-112">If your company has contractual obligations to send all emails encrypted, I recommend setting the level to **High**.</span></span>
8. <span data-ttu-id="3bba9-113">В **статье Выбор модели для этого правила** нажмите кнопку **Принудить**.</span><span class="sxs-lookup"><span data-stu-id="3bba9-113">Under **Choose a model for this rule**, click **Enforce**.</span></span> 
9. <span data-ttu-id="3bba9-114">Выберите любой необязательный выбор (из списка необязательных выборов, которые можно сделать на данном этапе, многие из которых можно оставить с параметром по умолчанию для простоты).</span><span class="sxs-lookup"><span data-stu-id="3bba9-114">Choose any optional selection (from a list of optional selections that you can make at this point, many of which can be left with the default setting for simplicity).</span></span>
10. <span data-ttu-id="3bba9-115">Щелкните **Сохранить**.</span><span class="sxs-lookup"><span data-stu-id="3bba9-115">Click **Save**.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="3bba9-116">Вы всегда можете вернуться и изменить это правило позже.</span><span class="sxs-lookup"><span data-stu-id="3bba9-116">You can always come back and edit this rule later.</span></span>

<span data-ttu-id="3bba9-117">Дополнительные сведения о создании правил шифрования см. в тексте Определение правил потока почты для шифрования сообщений электронной почты [в Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email)</span><span class="sxs-lookup"><span data-stu-id="3bba9-117">For more information about creating rules for encryption, see [Define mail flow rules to encrypt email messages in Office 365](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email)</span></span>

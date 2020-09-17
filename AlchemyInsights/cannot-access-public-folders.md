---
title: Не удается получить доступ к общедоступным папкам
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3462"
ms.openlocfilehash: 272918b38f6019cb2bdcaa4013baebaa5f04fe85
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/15/2020
ms.locfileid: "47812560"
---
# <a name="outlook-cannot-connect-to-public-folders"></a><span data-ttu-id="ac0cf-102">Outlook не удается подключиться к общедоступным папкам</span><span class="sxs-lookup"><span data-stu-id="ac0cf-102">Outlook cannot connect to public folders</span></span>

<span data-ttu-id="ac0cf-103">Если доступ к общедоступным папкам не работает для некоторых пользователей, попробуйте выполнить следующие действия:</span><span class="sxs-lookup"><span data-stu-id="ac0cf-103">If public folder access isn't working for some users, try the following:</span></span>

<span data-ttu-id="ac0cf-104">Подключитесь к EXO PowerShell и настройте параметр DefaultPublicFolderMailbox учетной записи пользователя, чтобы он был сопоставлен с параметром рабочей учетной записи пользователя.</span><span class="sxs-lookup"><span data-stu-id="ac0cf-104">Connect to EXO PowerShell and configure the DefaultPublicFolderMailbox parameter on the problem user account to match the parameter on a working user account.</span></span>

<span data-ttu-id="ac0cf-105">Пример:</span><span class="sxs-lookup"><span data-stu-id="ac0cf-105">Example:</span></span>

<span data-ttu-id="ac0cf-106">Get/Mailbox Воркингусер | ft DefaultPublicFolderMailbox, Еффективепубликфолдермаилбокс</span><span class="sxs-lookup"><span data-stu-id="ac0cf-106">Get-Mailbox WorkingUser | ft DefaultPublicFolderMailbox,EffectivePublicFolderMailbox</span></span>

<span data-ttu-id="ac0cf-107">Set — Mailbox Проблемусер — DefaultPublicFolderMailbox \<value from previous command></span><span class="sxs-lookup"><span data-stu-id="ac0cf-107">Set-Mailbox ProblemUser -DefaultPublicFolderMailbox \<value from previous command></span></span>

<span data-ttu-id="ac0cf-108">Чтобы изменения вступили в силу, подождите хотя бы один час.</span><span class="sxs-lookup"><span data-stu-id="ac0cf-108">Wait at least one hour for the change to take effect.</span></span>

<span data-ttu-id="ac0cf-109">Если проблема не устранена, выполните указанные ниже [действия](https://aka.ms/pfcte) , чтобы устранить проблемы с доступом к общим папкам с помощью Outlook.</span><span class="sxs-lookup"><span data-stu-id="ac0cf-109">If the issue remains, please follow [this procedure](https://aka.ms/pfcte) to troubleshoot public folder access issues using Outlook.</span></span>
 
<span data-ttu-id="ac0cf-110">**Чтобы определить, какие пользователи могут получать доступ к общедоступным папкам с помощью Outlook**:</span><span class="sxs-lookup"><span data-stu-id="ac0cf-110">**To control which users can access public folders using Outlook**:</span></span>

1.  <span data-ttu-id="ac0cf-111">Используйте Set – CASMailbox <mailboxname> публикфолдерклиентакцесс $true или $false</span><span class="sxs-lookup"><span data-stu-id="ac0cf-111">Use Set-CASMailbox <mailboxname> -PublicFolderClientAccess $true or $false</span></span>  
      
    <span data-ttu-id="ac0cf-112">$true: Разрешить пользователям получать доступ к общедоступным папкам в Outlook</span><span class="sxs-lookup"><span data-stu-id="ac0cf-112">$true: Allow users access public folders in Outlook</span></span>  
      
    <span data-ttu-id="ac0cf-113">$false. Запретить пользователям получать доступ к общедоступным папкам в Outlook.</span><span class="sxs-lookup"><span data-stu-id="ac0cf-113">$false: Prevent user access to public folders in Outlook.</span></span> <span data-ttu-id="ac0cf-114">Это значение используется по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="ac0cf-114">This is the default value.</span></span>  
        
2.  <span data-ttu-id="ac0cf-115">Set — OrganizationConfig — Публикфолдершовклиентконтрол $true</span><span class="sxs-lookup"><span data-stu-id="ac0cf-115">Set-OrganizationConfig -PublicFolderShowClientControl $true</span></span>   
      
<span data-ttu-id="ac0cf-116">**Note (Примечание** ) Эта процедура позволяет управлять подключениями только с клиентами Outlook Desktop для Windows.</span><span class="sxs-lookup"><span data-stu-id="ac0cf-116">**Note** This procedure can control connections only with Outlook desktop for Windows clients.</span></span> <span data-ttu-id="ac0cf-117">Пользователь может продолжить доступ к общедоступным папкам с помощью OWA или Outlook для Mac.</span><span class="sxs-lookup"><span data-stu-id="ac0cf-117">A user can continue accessing public folders using OWA or Outlook for Mac.</span></span>
 
<span data-ttu-id="ac0cf-118">Дополнительные сведения приведены в статье [объявления о поддержке управляемых подключений для общедоступных папок в Outlook](https://aka.ms/controlpf).</span><span class="sxs-lookup"><span data-stu-id="ac0cf-118">For more info, see [Announcing Support for Controlled Connections to Public Folders in Outlook](https://aka.ms/controlpf).</span></span>
---
title: Перемещение сообщений электронной почты в архивный почтовый ящик
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: 37f256ef31402f5139fdd7c2af8f3a6ca9dc3525
ms.sourcegitcommit: 228c986911ecf73217116a5d1fdcd2e89362774e
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/09/2019
ms.locfileid: "31747216"
---
# <a name="move-email-to-the-archive-mailbox"></a><span data-ttu-id="81606-102">Перемещение электронной почты в архивный почтовый ящик</span><span class="sxs-lookup"><span data-stu-id="81606-102">Move email to the archive mailbox</span></span>
 
1. <span data-ttu-id="81606-103">Убедитесь, что **архивный почтовый ящик** включен.</span><span class="sxs-lookup"><span data-stu-id="81606-103">Confirm that an **Archive mailbox** has been enabled.</span></span> <span data-ttu-id="81606-104">В противном случае выполните действия, описанные в [этой статье](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) , чтобы включить архивный почтовый ящик.</span><span class="sxs-lookup"><span data-stu-id="81606-104">If not, use the steps in [this article](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) to enable the archive mailbox.</span></span>

2. <span data-ttu-id="81606-105">Чтобы автоматически архивировать сообщения в архивный почтовый ящик, тег хранения с действием **переместить в архив** должен **автоматически применять ко всему тегу почтового ящика (по умолчанию)**.</span><span class="sxs-lookup"><span data-stu-id="81606-105">To archive messages automatically to the archive mailbox, a retention tag with the **Move to archive** action must be set to **applied automatically to entire mailbox (default) tag**.</span></span> <span data-ttu-id="81606-106">Выполните действия, описанные в этой статье, чтобы создать тег: [Archive Default Tag](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Foffice365%2Fsecuritycompliance%2Fset-up-an-archive-and-deletion-policy-for-mailboxes%23create-a-custom-archive-default-policy-tag&data=04%7C01%7Cstephow%40microsoft.com%7C89934e16dbd84ebdef6708d6b319b348%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636893320296576506%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C-1&sdata=UibWi%2BtrO3ITZ6iF%2FtKQj5JyxzEb9Mu9frBJPT6FNFI%3D&reserved=0).</span><span class="sxs-lookup"><span data-stu-id="81606-106">Use the steps here to create the tag: [Archive Default tag](https://nam06.safelinks.protection.outlook.com/?url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Foffice365%2Fsecuritycompliance%2Fset-up-an-archive-and-deletion-policy-for-mailboxes%23create-a-custom-archive-default-policy-tag&data=04%7C01%7Cstephow%40microsoft.com%7C89934e16dbd84ebdef6708d6b319b348%7C72f988bf86f141af91ab2d7cd011db47%7C1%7C0%7C636893320296576506%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C-1&sdata=UibWi%2BtrO3ITZ6iF%2FtKQj5JyxzEb9Mu9frBJPT6FNFI%3D&reserved=0).</span></span>
    
3. <span data-ttu-id="81606-107">Затем добавьте тег **Archive** в политику хранения.</span><span class="sxs-lookup"><span data-stu-id="81606-107">Next, add the **Archive** tag to your retention policy.</span></span> <span data-ttu-id="81606-108">В центре администрирования Exchange выберите **политики хранения** _гт_ добавьте **тег "переместить в архив** " в политику _гт_ **сохранить**.</span><span class="sxs-lookup"><span data-stu-id="81606-108">In the Exchange admin center, choose **Retention Policies** > add the **Move to Archive tag** to the policy > **Save**.</span></span> 
    
4. <span data-ttu-id="81606-109">Теперь [назначьте политику хранения](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) для почтового ящика определенного пользователя.</span><span class="sxs-lookup"><span data-stu-id="81606-109">Now [Assign the Retention Policy](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) to the specific user's mailbox.</span></span> <span data-ttu-id="81606-110">Та же политика будет применяться и к основному \*\*\*\* , и к **архивному** почтовому ящику.</span><span class="sxs-lookup"><span data-stu-id="81606-110">The same policy will be applied to both the **Primary** and the **Archive** mailbox.</span></span> 
    
<span data-ttu-id="81606-111">Может потребоваться принудительно запустить помощник по обслуживанию управляемых папок (MFA) и применить новые параметры к почтовому ящику пользователя.</span><span class="sxs-lookup"><span data-stu-id="81606-111">It may be necessary to force the Managed Folder Assistant (MFA) to run and apply the new settings to the user's mailbox.</span></span> <span data-ttu-id="81606-112">Выполните следующую команду при [подключении к EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) для запуска помощника по работе с управляемыми папками для определенного почтового ящика:</span><span class="sxs-lookup"><span data-stu-id="81606-112">Run the following command while [connected to EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) to start the Managed Folder Assistant for a specific mailbox:</span></span> 
  
```
Start-ManagedFolderAssistant -Identity <name of the mailbox>
```

<span data-ttu-id="81606-113">Дополнительные сведения о настройке политики архивации можно найти в разделе [Настройка политики архивации и удаления для](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users)почтовых ящиков.</span><span class="sxs-lookup"><span data-stu-id="81606-113">For more information on setting up an archive policy, see [Set up an archive and deletion policy for mailboxes](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span></span>
  


---
title: 902 (ошибки синхронизации из-за повторяющихся объектов)
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 5/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: f8db233167a5e2b2ef7290438b8e6d92d0dccb1e
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/24/2019
ms.locfileid: "29486895"
---
# <a name="sync-errors-due-to-duplicate-objects"></a><span data-ttu-id="33daf-102">Ошибки синхронизации из-за повторяющихся объектов</span><span class="sxs-lookup"><span data-stu-id="33daf-102">Sync errors due to duplicate objects</span></span>

<span data-ttu-id="33daf-103">Вы можете получить одно из следующих сообщений об ошибке после завершения синхронизации службы каталогов:</span><span class="sxs-lookup"><span data-stu-id="33daf-103">You might receive one of the following error messages when directory synchronization finishes:</span></span>
  
- <span data-ttu-id="33daf-104">Не удается обновить этот объект в Microsoft Online Services, так как следующие атрибуты, связанное с объектом значения, которые могут быть уже связаны с другой объект в локальный каталог.</span><span class="sxs-lookup"><span data-stu-id="33daf-104">Unable to update this object in Microsoft Online Services because the following attributes associated with this object have values that may already be associated with another object in your local directory.</span></span>
    
- <span data-ttu-id="33daf-105">Синхронизированных объектов с тем же адресом прокси-сервер уже существует в каталоге Microsoft Online Services.</span><span class="sxs-lookup"><span data-stu-id="33daf-105">A synchronized object with the same proxy address already exists in your Microsoft Online Services directory.</span></span>
    
- <span data-ttu-id="33daf-106">Не удается обновить этот объект, так как следующие атрибуты, связанное с объектом значения, которые могут быть уже связаны с другой объект в локальный каталог служб: UserPrincipalName.</span><span class="sxs-lookup"><span data-stu-id="33daf-106">Unable to update this object because the following attributes associated with this object have values that may already be associated with another object in your local directory services: UserPrincipalName.</span></span>
    
<span data-ttu-id="33daf-107">Чтобы определить и устранить проблему, загрузите и запустите [Средство исправления ошибок IdFix DirSync](https://www.microsoft.com/download/details.aspx?id=36832).</span><span class="sxs-lookup"><span data-stu-id="33daf-107">To identify and fix the issue, download and run the [IdFix DirSync Error Remediation Tool](https://www.microsoft.com/download/details.aspx?id=36832).</span></span>
  
<span data-ttu-id="33daf-108">Для получения дополнительных сведений см [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span><span class="sxs-lookup"><span data-stu-id="33daf-108">For more information, see [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span></span>
  


---
title: Этот параметр отключен синхронизации имени участника-пользователя
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 2a3489fe-c2a8-4e43-96c2-be4b3c5e978c
ms.openlocfilehash: 983796ce8fb7e8b52c0ce31aa13597b53cc9e038
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 02/12/2019
ms.locfileid: "29921721"
---
# <a name="upn-sync-disabled"></a><span data-ttu-id="b183d-102">Этот параметр отключен синхронизации имени участника-пользователя</span><span class="sxs-lookup"><span data-stu-id="b183d-102">UPN sync disabled</span></span>

<span data-ttu-id="b183d-103">Если запустить синхронизацию с Azure AD до 30 марта 2016, выполните следующий командлет Windows Azure AD PowerShell, чтобы включить соответствие программных имени участника-пользователя для вашей организации только:</span><span class="sxs-lookup"><span data-stu-id="b183d-103">If you started syncing to Azure AD before March 30, 2016, run the following Azure AD PowerShell cmdlet to enable UPN soft match for your organization only:</span></span>
  
 <span data-ttu-id="b183d-104">**SET-MsolDirSyncFeature-EnableSoftMatchOnUpn в функциях-включить $True**</span><span class="sxs-lookup"><span data-stu-id="b183d-104">**Set-MsolDirSyncFeature -Feature EnableSoftMatchOnUpn -Enable $True**</span></span>
  
<span data-ttu-id="b183d-105">Для организаций, которые удалось запустить синхронизацию с Azure AD не ранее 30 марта 2016 включается автоматически программных совпадение имени участника-пользователя.</span><span class="sxs-lookup"><span data-stu-id="b183d-105">UPN soft match is automatically turned on for organizations that started syncing to Azure AD on or after March 30, 2016.</span></span>
  
<span data-ttu-id="b183d-106">Для получения дополнительных сведений о включении программных совпадение на имя участника-пользователя и другие функции синхронизации, можно найти [компонентов службы синхронизации Azure AD подключение](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span><span class="sxs-lookup"><span data-stu-id="b183d-106">To learn more about enabling soft match on UPN and other sync features, please see [Azure AD Connect sync service features](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnectsyncservice-features).</span></span>
  


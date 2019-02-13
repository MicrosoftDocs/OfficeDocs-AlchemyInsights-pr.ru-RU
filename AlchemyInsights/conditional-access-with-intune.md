---
title: Условное доступа с Intune
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: 2e778bf4fbdb766700fb24b3405b4ddce89253f7
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 02/12/2019
ms.locfileid: "29935962"
---
# <a name="conditional-access-with-intune"></a><span data-ttu-id="82a2a-102">Условное доступа с Intune</span><span class="sxs-lookup"><span data-stu-id="82a2a-102">Conditional Access with Intune</span></span>

<span data-ttu-id="82a2a-103">Использование **Условного доступа** с Intune требуется три этапа:</span><span class="sxs-lookup"><span data-stu-id="82a2a-103">Using **Conditional Access** with Intune requires 3 steps:</span></span> 
  
- <span data-ttu-id="82a2a-p101">Создайте **Условную политику доступа** , который определяет, какие ресурсы защищены и условия, необходимые для быть выполнены для доступа к ресурсам. Например устройства должны быть совместимыми перед доступом к корпоративной электронной почты.</span><span class="sxs-lookup"><span data-stu-id="82a2a-p101">Create a **Conditional Access Policy** that defines what resources are being protected, and what conditions need to be met to access those resources. For example, a device must be compliant before accessing corporate email.</span></span> 
    
- <span data-ttu-id="82a2a-p102">Создание **Политики соответствия** для определения параметров, которые должны быть выполнены перед считается совместимые устройства. Например устройство ПИН-кодов по крайней мере 6 цифр перед необходимо считается спецификации.</span><span class="sxs-lookup"><span data-stu-id="82a2a-p102">Create a **Compliance Policy** to define settings that must be met before the device is considered compliant. For example, a device must have a pin of at least 6 digits before it is considered compliant.</span></span> 
    
- <span data-ttu-id="82a2a-p103">Настройка **Политики соответствия** и **Условной политики доступа** предназначены для нужного групп пользователей. Может потребоваться создание определенных групп пользователей в Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="82a2a-p103">Ensuring both **Compliance Policies** and **Conditional Access Policies** are targeted to the desired groups of users. This may require creating specific groups of users in Azure Active Directory.</span></span> 
    
<span data-ttu-id="82a2a-110">Дополнительные сведения:</span><span class="sxs-lookup"><span data-stu-id="82a2a-110">Read more:</span></span>
  
- [<span data-ttu-id="82a2a-111">Рекомендации по условного доступа</span><span class="sxs-lookup"><span data-stu-id="82a2a-111">Conditional Access best practices</span></span>](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [<span data-ttu-id="82a2a-112">Приступая к работе с условным доступом</span><span class="sxs-lookup"><span data-stu-id="82a2a-112">Getting started with Conditional Access </span></span>](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    


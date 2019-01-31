---
title: Условное доступа с Intune
ms.author: pebaum
author: pebaum
ms.date: 10/11/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: aecba7c5-e86d-4ec8-9d44-679f5a3d659d
ms.openlocfilehash: 3b50bc96a879017b62e42e1849f72e68408a0d9d
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/30/2019
ms.locfileid: "29662340"
---
# <a name="conditional-access-with-intune"></a><span data-ttu-id="e1f07-102">Условное доступа с Intune</span><span class="sxs-lookup"><span data-stu-id="e1f07-102">Conditional Access with Intune</span></span>

<span data-ttu-id="e1f07-103">Использование **Условного доступа** с Intune требуется три этапа:</span><span class="sxs-lookup"><span data-stu-id="e1f07-103">Using **Conditional Access** with Intune requires 3 steps:</span></span> 
  
- <span data-ttu-id="e1f07-p101">Создайте **Условную политику доступа** , который определяет, какие ресурсы защищены и условия, необходимые для быть выполнены для доступа к ресурсам. Например устройства должны быть совместимыми перед доступом к корпоративной электронной почты.</span><span class="sxs-lookup"><span data-stu-id="e1f07-p101">Create a **Conditional Access Policy** that defines what resources are being protected, and what conditions need to be met to access those resources. For example, a device must be compliant before accessing corporate email.</span></span> 
    
- <span data-ttu-id="e1f07-p102">Создание **Политики соответствия** для определения параметров, которые должны быть выполнены перед считается совместимые устройства. Например устройство ПИН-кодов по крайней мере 6 цифр перед необходимо считается спецификации.</span><span class="sxs-lookup"><span data-stu-id="e1f07-p102">Create a **Compliance Policy** to define settings that must be met before the device is considered compliant. For example, a device must have a pin of at least 6 digits before it is considered compliant.</span></span> 
    
- <span data-ttu-id="e1f07-p103">Настройка **Политики соответствия** и **Условной политики доступа** предназначены для нужного групп пользователей. Может потребоваться создание определенных групп пользователей в Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="e1f07-p103">Ensuring both **Compliance Policies** and **Conditional Access Policies** are targeted to the desired groups of users. This may require creating specific groups of users in Azure Active Directory.</span></span> 
    
<span data-ttu-id="e1f07-110">Дополнительные сведения:</span><span class="sxs-lookup"><span data-stu-id="e1f07-110">Read more:</span></span>
  
- [<span data-ttu-id="e1f07-111">Рекомендации по условного доступа</span><span class="sxs-lookup"><span data-stu-id="e1f07-111">Conditional Access best practices</span></span>](https://docs.microsoft.com/azure/active-directory/conditional-access/best-practices)
    
- [<span data-ttu-id="e1f07-112">Приступая к работе с условным доступом</span><span class="sxs-lookup"><span data-stu-id="e1f07-112">Getting started with Conditional Access </span></span>](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access-azure-portal-get-started)
    


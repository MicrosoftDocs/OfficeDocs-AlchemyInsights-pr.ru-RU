---
title: ConsistencyGuid / sourceAnchor behaviour
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: eafe1ec9636cddc9d73a88beb7ae3ad9f6fad660
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/15/2021
ms.locfileid: "51817005"
---
# <a name="consistencyguid--sourceanchor-behavior"></a><span data-ttu-id="18f6d-102">ConsistencyGuid / sourceAnchor behaviour</span><span class="sxs-lookup"><span data-stu-id="18f6d-102">ConsistencyGuid / sourceAnchor behavior</span></span>

<span data-ttu-id="18f6d-103">Azure AD Connect (версия 1.1.524.0 и после) теперь упрощает использование msDS-ConsistencyGuid в качестве атрибута sourceAnchor.</span><span class="sxs-lookup"><span data-stu-id="18f6d-103">Azure AD Connect (version 1.1.524.0 and after) now facilitates the use of msDS-ConsistencyGuid as sourceAnchor attribute.</span></span> <span data-ttu-id="18f6d-104">При использовании этой функции Azure AD Connect автоматически настраивает правила синхронизации на:</span><span class="sxs-lookup"><span data-stu-id="18f6d-104">When using this feature, Azure AD Connect automatically configures the synchronization rules to:</span></span>
  
- <span data-ttu-id="18f6d-105">Используйте msDS-ConsistencyGuid в качестве атрибута sourceAnchor для объектов пользователя.</span><span class="sxs-lookup"><span data-stu-id="18f6d-105">Use msDS-ConsistencyGuid as the sourceAnchor attribute for User objects.</span></span> <span data-ttu-id="18f6d-106">ObjectGUID используется для других типов объектов.</span><span class="sxs-lookup"><span data-stu-id="18f6d-106">ObjectGUID is used for other object types.</span></span>
    
- <span data-ttu-id="18f6d-107">Для любого локального объекта AD User, атрибут msDS-ConsistencyGuid которого не заполнен, Azure AD Connect записывает свое значение objectGUID обратно в атрибут msDS-ConsistencyGuid в локальном Active Directory.</span><span class="sxs-lookup"><span data-stu-id="18f6d-107">For any given on-premises AD User object whose msDS-ConsistencyGuid attribute isn't populated, Azure AD Connect writes its objectGUID value back to the msDS-ConsistencyGuid attribute in on-premises Active Directory.</span></span> <span data-ttu-id="18f6d-108">После заполнения атрибута msDS-ConsistencyGuid Azure AD Connect экспортирует объект в Azure AD.</span><span class="sxs-lookup"><span data-stu-id="18f6d-108">After the msDS-ConsistencyGuid attribute is populated, Azure AD Connect then exports the object to Azure AD.</span></span>
    
 <span data-ttu-id="18f6d-109">**Примечание:** После импорта локального объекта AD в Azure AD Connect (то есть импортируемого в пространство соединителя AD и проецируемого в Metaverse), невозможно изменить его значение sourceAnchor.</span><span class="sxs-lookup"><span data-stu-id="18f6d-109">**Note:** Once an on-premises AD object is imported into Azure AD Connect (that is, imported into the AD Connector Space and projected into the Metaverse), you cannot change its sourceAnchor value anymore.</span></span> <span data-ttu-id="18f6d-110">Чтобы указать значение sourceAnchor для данного локального объекта AD, настройте атрибут msDS-ConsistencyGuid перед его импортом в Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="18f6d-110">To specify the sourceAnchor value for a given on-premises AD object, configure its msDS-ConsistencyGuid attribute before it is imported into Azure AD Connect.</span></span> 
  
<span data-ttu-id="18f6d-111">Дополнительные сведения о SourceAnchor и ConsistencyGuid можно найти в следующих сведениях: [Azure AD Connect: Design concepts](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span><span class="sxs-lookup"><span data-stu-id="18f6d-111">For more information on SourceAnchor and ConsistencyGuid, refer to the following: [Azure AD Connect: Design concepts](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span></span>
  


---
title: Код ошибки 0x15
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Если вы получаете сообщение об ошибке при активации Office 2013 для развертываний служб удаленных рабочих столов, рассмотрите возможность включения ADAL, изменив реестр.
ms.openlocfilehash: 468d13e59602cf173ed2e17af44c66babfc28703
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506859"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a><span data-ttu-id="5d312-103">Ошибка при активации Office 2013 в службах удаленных рабочих столов</span><span class="sxs-lookup"><span data-stu-id="5d312-103">Error while activation Office 2013 on Remote Desktop Services</span></span>

<span data-ttu-id="5d312-104">Если вы получаете сообщение об ошибке при активации Office 2013 для развертываний служб удаленных рабочих столов, рассмотрите возможность включения ADAL, изменив реестр.</span><span class="sxs-lookup"><span data-stu-id="5d312-104">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span>
  
|<span data-ttu-id="5d312-105">**Раздел реестра**</span><span class="sxs-lookup"><span data-stu-id="5d312-105">**Registry key**</span></span>|<span data-ttu-id="5d312-106">**Тип**</span><span class="sxs-lookup"><span data-stu-id="5d312-106">**Type**</span></span>|<span data-ttu-id="5d312-107">**Значение**</span><span class="sxs-lookup"><span data-stu-id="5d312-107">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="5d312-108">HKEY_CURRENT_USER \Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="5d312-108">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="5d312-109">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="5d312-109">REG_DWORD</span></span>  <br/> |<span data-ttu-id="5d312-110">1 </span><span class="sxs-lookup"><span data-stu-id="5d312-110">1</span></span>  <br/> |

<span data-ttu-id="5d312-111">Дополнительную информацию можно узнать [в статье Включение современной проверки подлинности для Office 2013 на устройствах с Windows](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="5d312-111">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="5d312-112">ADAL включается по умолчанию в приложениях Microsoft 365 для предприятий и Office 2016.</span><span class="sxs-lookup"><span data-stu-id="5d312-112">ADAL is enabled by default in Microsoft 365 Apps for enterprise and Office 2016.</span></span> <span data-ttu-id="5d312-113">Службы удаленных рабочих столов (RDS) ранее назывались службами терминалов.</span><span class="sxs-lookup"><span data-stu-id="5d312-113">Remote Desktop Services (RDS) was previously named Terminal Services.</span></span>
  
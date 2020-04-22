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
ms.openlocfilehash: 566d63cbe37d295b3546b9d7d5b14dfc8e8fe0ec
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703151"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a><span data-ttu-id="81e8d-103">Ошибка при активации Office 2013 в службах удаленных рабочих столов</span><span class="sxs-lookup"><span data-stu-id="81e8d-103">Error while activation Office 2013 on Remote Desktop Services</span></span>

<span data-ttu-id="81e8d-104">Если вы получаете сообщение об ошибке при активации Office 2013 для развертываний служб удаленных рабочих столов, рассмотрите возможность включения ADAL, изменив реестр.</span><span class="sxs-lookup"><span data-stu-id="81e8d-104">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span>
  
|<span data-ttu-id="81e8d-105">**Раздел реестра**</span><span class="sxs-lookup"><span data-stu-id="81e8d-105">**Registry key**</span></span>|<span data-ttu-id="81e8d-106">**Тип**</span><span class="sxs-lookup"><span data-stu-id="81e8d-106">**Type**</span></span>|<span data-ttu-id="81e8d-107">**Значение**</span><span class="sxs-lookup"><span data-stu-id="81e8d-107">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="81e8d-108">HKEY_CURRENT_USER \Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="81e8d-108">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="81e8d-109">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="81e8d-109">REG_DWORD</span></span>  <br/> |<span data-ttu-id="81e8d-110">1,1</span><span class="sxs-lookup"><span data-stu-id="81e8d-110">1</span></span>  <br/> |

<span data-ttu-id="81e8d-111">Дополнительную информацию можно узнать [в статье Включение современной проверки подлинности для Office 2013 на устройствах с Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="81e8d-111">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="81e8d-112">ADAL включается по умолчанию в приложениях Microsoft 365 для предприятий и Office 2016.</span><span class="sxs-lookup"><span data-stu-id="81e8d-112">ADAL is enabled by default in Microsoft 365 Apps for enterprise and Office 2016.</span></span> <span data-ttu-id="81e8d-113">Службы удаленных рабочих столов (RDS) ранее назывались службами терминалов.</span><span class="sxs-lookup"><span data-stu-id="81e8d-113">Remote Desktop Services (RDS) was previously named Terminal Services.</span></span>
  
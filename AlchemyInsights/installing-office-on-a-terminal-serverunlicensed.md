---
title: Установка office на сервере терминалов - нелицензированный
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 73d5128b55cae7712c48be9e2d05e558c3ba2e5c
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/15/2019
ms.locfileid: "28308661"
---
# <a name="installing-office-on-a-terminal-server"></a><span data-ttu-id="6534d-102">Установка Office на сервере терминалов</span><span class="sxs-lookup"><span data-stu-id="6534d-102">Installing Office on a Terminal Server</span></span>

<span data-ttu-id="6534d-103">Для развертывания Office 365 профессиональный плюс в Windows Server с помощью служб удаленных рабочих столов (RDS), прежнее название служб терминалов:</span><span class="sxs-lookup"><span data-stu-id="6534d-103">For deploying Office 365 ProPlus on a Windows Server using Remote Desktop Services (RDS), formerly named Terminal Services:</span></span>
  
- <span data-ttu-id="6534d-p101">Необходимо иметь план Office 365, которая включает в себя Office 365 профессиональный плюс, таких как Office 365 для предприятий E3 или Enterprise E5. Планы Office 365 для бизнеса и Office 365 бизнеса расширенный не включать Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="6534d-p101">You must have an Office 365 plan that includes Office 365 ProPlus, such as Office 365 Enterprise E3 or Enterprise E5. The Office 365 Business and Office 365 Business Premium plans do not include Office 365 ProPlus.</span></span>
    
- <span data-ttu-id="6534d-106">Необходимо включить [активацию совместно используемый компьютер](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="6534d-106">You need to enable [shared computer activation](https://docs.microsoft.com/DeployOffice/overview-of-shared-computer-activation-for-office-365-proplus).</span></span>
    
<span data-ttu-id="6534d-107">Если вы хотите установить Office 365 ProPlus на служб удаленных рабочих СТОЛОВ с портала Office 365 \*\* *с использованием параметров установки по умолчанию* \*\*, выполните следующие действия:</span><span class="sxs-lookup"><span data-stu-id="6534d-107">If you want to install Office 365 ProPlus on RDS from the Office 365 portal, \*\* *which uses default installation settings* \*\*, follow these steps:</span></span> 
  
1. <span data-ttu-id="6534d-p102">Проверьте план Office 365, у вас есть. [Узнайте, как](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)</span><span class="sxs-lookup"><span data-stu-id="6534d-p102">Check what Office 365 plan you have. [Learn how](https://docs.microsoft.com/office365/admin/admin-overview/what-subscription-do-i-have)</span></span>
    
2. <span data-ttu-id="6534d-p103">При необходимости переключитесь различных Office 365. [Узнайте, как](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)</span><span class="sxs-lookup"><span data-stu-id="6534d-p103">If necessary, switch to a different Office 365 plan. [Learn how](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/switch-to-a-different-plan)</span></span>
    
3. <span data-ttu-id="6534d-p104">Если Office уже установлен на сервере служб удаленных рабочих СТОЛОВ, с использованием других планов Office 365, ее необходимо удалите. Например, выбрав пункты панель управления \> удаление программы. Удалите с помощью [службы поддержки Майкрософт и помощник по восстановлению](https://aka.ms/SARA-OfficeUninstall-Alchemy) , если вы используете за ошибок.</span><span class="sxs-lookup"><span data-stu-id="6534d-p104">If Office is already installed on the RDS server using any other Office 365 plans, uninstall it. For example, by going to Control Panel \> Uninstall a program. Uninstall using [Microsoft Support and Recovery Assistant](https://aka.ms/SARA-OfficeUninstall-Alchemy) if you're running into issues.</span></span> 
    
4. <span data-ttu-id="6534d-115">На сервере служб удаленных рабочих СТОЛОВ войдите в портал Office 365 с помощью учетной записи администратора и [установить Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span><span class="sxs-lookup"><span data-stu-id="6534d-115">On the RDS server, sign in to the Office 365 portal with your administrator account and [install Office 365 ProPlus](https://portal.office.com/OLS/MySoftware.aspx).</span></span>
    
5. <span data-ttu-id="6534d-116">После установки Office \*\* *не открывать или входа в* \*\* в любое приложение Office.</span><span class="sxs-lookup"><span data-stu-id="6534d-116">After Office is installed, \*\* *don't open or sign in* \*\* to any Office applications.</span></span> 
    
6. <span data-ttu-id="6534d-117">На сервере служб удаленных рабочих СТОЛОВ активации совместно используемый компьютер с помощью реестра, выполнив следующие действия:</span><span class="sxs-lookup"><span data-stu-id="6534d-117">On the RDS server, enable shared computer activation by editing the registry by following these steps:</span></span>
    
1. <span data-ttu-id="6534d-p105">Щелкните правой кнопкой мыши кнопку Windows в левом нижнем углу экрана и выберите команду выполнить. В поле Открыть введите **команду regedit**и нажмите кнопку «ОК».</span><span class="sxs-lookup"><span data-stu-id="6534d-p105">Right-click the Windows button in the lower left-hand corner of your screen and select Run. In the Open box, type **regedit**, and then select OK.</span></span> 
    
2. <span data-ttu-id="6534d-120">Нажмите кнопку Да при отображении запроса на разрешение редактор реестра для внесения изменений в устройстве.</span><span class="sxs-lookup"><span data-stu-id="6534d-120">Select Yes when prompted to allow Registry Editor to make changes to your device.</span></span>
    
3. <span data-ttu-id="6534d-121">В редакторе реестра добавьте строковое значение **SharedComputerLicensing** с параметром 1 в реестр \Office\ClickToRun\Configuration.</span><span class="sxs-lookup"><span data-stu-id="6534d-121">In the Registry Editor, add a string value of **SharedComputerLicensing** with a setting of 1 under HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft \Office\ClickToRun\Configuration.</span></span> 
    
7. <span data-ttu-id="6534d-122">На сервере служб удаленных рабочих СТОЛОВ \*\* *Вход как пользователь* \*\* и [Убедитесь, что активации совместно используемый компьютер включен для Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span><span class="sxs-lookup"><span data-stu-id="6534d-122">On the RDS server, \*\* *sign in as an end user* \*\* and [verify that shared computer activation is enabled for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus#verify-that-activation-for-office-365-proplus-succeeded).</span></span>
    
<span data-ttu-id="6534d-123">Для получения дополнительных сведений о необходимых компонентов, инструкции по установке и рекомендации по настраиваемой установки с помощью средства развертывания Office можно найти [Развертывание Office 365 профессиональный плюс с помощью служб удаленных рабочих столов](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span><span class="sxs-lookup"><span data-stu-id="6534d-123">For more details on prerequisites, setup instructions and guidance on customized installations by using the Office Deployment Tool, please see [Deploy Office 365 ProPlus by using Remote Desktop Services](https://docs.microsoft.com/DeployOffice/deploy-office-365-proplus-by-using-remote-desktop-services).</span></span>
  
<span data-ttu-id="6534d-124">Для устранения ошибок, связанных с активацией совместно используемый компьютер, ознакомьтесь с разделом [Устранение проблем, связанных с активацией совместно используемый компьютер для Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span><span class="sxs-lookup"><span data-stu-id="6534d-124">To fix errors related to shared computer activation, please see [Troubleshoot issues with shared computer activation for Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/troubleshoot-issues-with-shared-computer-activation-for-office-365-proplus).</span></span>
  


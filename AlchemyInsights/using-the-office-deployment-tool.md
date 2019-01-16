---
title: С помощью средства развертывания Office
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 7ff7cc06-76d0-468f-bd66-3f2760750d04
ms.openlocfilehash: b4ade0f21794a8986aa7a37d783da5fa289488fc
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/15/2019
ms.locfileid: "28308747"
---
# <a name="using-the-office-deployment-tool-odt"></a><span data-ttu-id="848b1-102">С помощью средства развертывания Office (ODT)</span><span class="sxs-lookup"><span data-stu-id="848b1-102">Using the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="848b1-p101">Использовать средство развертывания Office (ODT) для развертывания Office 365 версии Office. Средства развертывания Office (setup.exe), запустите из командной строки и используется XML-файл конфигурации, чтобы определить, какие параметры, применяемые при развертывании Office.</span><span class="sxs-lookup"><span data-stu-id="848b1-p101">You use the Office Deployment Tool (ODT) to deploy Office 365 versions of Office. The Office Deployment Tool (setup.exe) is run from the command line and uses a configuration XML file to determine what settings to apply when deploying Office.</span></span>
  
1. <span data-ttu-id="848b1-105">Загрузите последнюю версию средства развертывания Office из [Центра загрузки Майкрософт](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="848b1-105">Download the latest version of the Office Deployment Tool from the [Microsoft Download Center](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>
    
2. <span data-ttu-id="848b1-p102">Использование [Центра развертывания Office (OCT)](https://config.office.com) Выбор параметров развертывания и создать XML-файл конфигурации. Экспорт файла конфигурации и поместите его в ту же папку, где находится программу setup.exe.</span><span class="sxs-lookup"><span data-stu-id="848b1-p102">Use the [Office Customization Tool (OCT)](https://config.office.com) to select your deployment preferences and create the configuration XML file. Export the configuration file and place it locally on the same folder where the setup.exe resides.</span></span> 
    
    <span data-ttu-id="848b1-p103">**Примечание:** Адреса файлов конфигурации или проблемы обычно возникают из-за для неправильно настроенный установки Office. Чтобы избежать таких проблем, рекомендуется использовать центр развертывания Office для создания файла конфигурации. Также можно импортировать существующие файлы конфигурации в центр развертывания Office.</span><span class="sxs-lookup"><span data-stu-id="848b1-p103">**Note:** Office installation issues commonly occur due to misconfigured or malformatted configuration files. To avoid such issues, we recommend that you use the Office Customization Tool to create the configuration file. You can also import existing configuration files into the Office Customization Tool.</span></span> 
    
3. <span data-ttu-id="848b1-p104">Из командной строки с повышенными привилегиями перейдите в расположение, где находится setup.exe и запустите средство развертывания Office в режиме загрузки и укажите только что сохраненный файл конфигурации. В следующем примере файла конфигурации с именем Configuration.xml:</span><span class="sxs-lookup"><span data-stu-id="848b1-p104">From an elevated command prompt, switch to the location where setup.exe resides and run the Office Deployment Tool in download mode and specify the configuration file you just saved. In this example, the configuration file is named Configuration.xml:</span></span>
    
  ```
  setup.exe /download Configuration.xml  
  ```

4. <span data-ttu-id="848b1-113">Запуск средства развертывания Office в режиме configure и указать файл конфигурации.</span><span class="sxs-lookup"><span data-stu-id="848b1-113">Run the Office Deployment Tool in configure mode and specify the configuration file.</span></span>
    
  ```
  setup.exe /configure Configuration.xml
  ```

    <span data-ttu-id="848b1-114">**Примечание:** Это действие необходимо выполнить на клиентском компьютере, на котором необходимо установить Office и необходимо иметь разрешения локального администратора на этом компьютере.</span><span class="sxs-lookup"><span data-stu-id="848b1-114">**Note:** You must run this step from the client computer on which you want to install Office and you must have local administrator permissions on that computer.</span></span> 
    
<span data-ttu-id="848b1-p105">Для получения дополнительных сведений об использовании средства развертывания Office для Office 365 ProPlus сценариев развертывания, просмотрите [Общие сведения о средства развертывания Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool). Для получения дополнительных сведений о том, как с помощью центра развертывания Office, в разделе [Обзор центра развертывания Office](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).</span><span class="sxs-lookup"><span data-stu-id="848b1-p105">To learn more about using Office Deployment Tool for your Office 365 ProPlus deployment scenarios, see [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool). For more details on how to use the Office Customization Tool, see [Overview of the Office Customization Tool](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).</span></span>
  


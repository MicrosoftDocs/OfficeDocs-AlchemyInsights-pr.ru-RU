---
title: Проблемы при установке Microsoft Defender на Mac и Linux
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/16/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "6028"
- "9001222"
ms.openlocfilehash: a8d5ad2246b9b83e1e0a4d5be4dd8bb41c16e734
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/14/2020
ms.locfileid: "49768464"
---
# <a name="issues-installing-microsoft-defender-on-mac-or-linux"></a><span data-ttu-id="451d7-102">Проблемы при установке Microsoft Defender на Mac и Linux</span><span class="sxs-lookup"><span data-stu-id="451d7-102">Issues installing Microsoft Defender on Mac or Linux</span></span>

<span data-ttu-id="451d7-103">**Mac**</span><span class="sxs-lookup"><span data-stu-id="451d7-103">**Mac**</span></span>

- <span data-ttu-id="451d7-104">Перед установкой пакета Microsoft Defender для Mac убедитесь, что система удовлетворяет требованиям.</span><span class="sxs-lookup"><span data-stu-id="451d7-104">Ensure that system requirements are met before installing Microsoft Defender ATP for Mac.</span></span> <span data-ttu-id="451d7-105">Дополнительные сведения см. в статье [Установка Microsoft Defender для Mac](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-mac#how-to-install-microsoft-defender-atp-for-mac).</span><span class="sxs-lookup"><span data-stu-id="451d7-105">For more info, see [How to install Microsoft Defender ATP for Mac](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-mac#how-to-install-microsoft-defender-atp-for-mac).</span></span>  
- <span data-ttu-id="451d7-106">Ознакомьтесь со сведениями в файле "/Library/Logs/Microsoft/mdatp/install.log".</span><span class="sxs-lookup"><span data-stu-id="451d7-106">Review the information in the file: "/Library/Logs/Microsoft/mdatp/install.log".</span></span>

<span data-ttu-id="451d7-107">**Linux**</span><span class="sxs-lookup"><span data-stu-id="451d7-107">**Linux**</span></span>

- <span data-ttu-id="451d7-108">Перед установкой пакета Microsoft Defender ATP для Linux убедитесь, что система удовлетворяет требованиям.</span><span class="sxs-lookup"><span data-stu-id="451d7-108">Ensure that system requirements are met before installing Microsoft Defender ATP for Linux.</span></span> <span data-ttu-id="451d7-109">Дополнительные сведения см. в статье [Установка Microsoft Defender ATP для Linux](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-linux#system-requirements).</span><span class="sxs-lookup"><span data-stu-id="451d7-109">For more info, see [How to install Microsoft Defender ATP for Linux](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-linux#system-requirements).</span></span> 
- <span data-ttu-id="451d7-110">Чтобы узнать, как проверить, запущена ли служба MDATP, ознакомьтесь с разделом [Сбой установки](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/linux-support-install#installation-failed).</span><span class="sxs-lookup"><span data-stu-id="451d7-110">To verify that MDATP service is running, see [Installation failed](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/linux-support-install#installation-failed).</span></span>  
    <span data-ttu-id="451d7-111">Если службу запустить не удалось, то, чтобы найти и устранить проблемы, следуйте инструкциям в разделе [Действия по устранению неполадок, если служба MDATP не запущена](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/linux-support-install#steps-to-troubleshoot-if-mdatp-service-isnt-running).</span><span class="sxs-lookup"><span data-stu-id="451d7-111">To troubleshoot and resolve issues if the service is not running, see [Steps to troubleshoot if mdatp service isn't running](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/linux-support-install#steps-to-troubleshoot-if-mdatp-service-isnt-running).</span></span>
- <span data-ttu-id="451d7-112">Пошаговые инструкции по проверке конфигурации клиента, которые помогут проверить состояние продукта и прогнать тест для обнаружения неполадок с помощью текстового файла EICAR, см. в разделе [Конфигурация клиента](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/linux-install-manually#client-configuration).</span><span class="sxs-lookup"><span data-stu-id="451d7-112">For steps to check the client configuration, which verifies the health of the product, and to run a detection test on the EICAR text file, see [Client configuration](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/linux-install-manually#client-configuration).</span></span>  

    <span data-ttu-id="451d7-113">**Примечание.** Список файловых систем, для которых поддерживается управление доступом, см. в статье [ATP в Microsoft Defender для Linux](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-linux#system-requirements).</span><span class="sxs-lookup"><span data-stu-id="451d7-113">**Note** For a list of supported file systems for on-access activity, see [Microsoft Defender ATP for Linux](https://docs.microsoft.com/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-linux#system-requirements).</span></span>
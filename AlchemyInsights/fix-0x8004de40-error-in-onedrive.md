---
title: Исправление 0x8004de40 ошибки в OneDrive
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: ''
ms.openlocfilehash: 0edb3e19b5dea240c9f2846dc503e65d92113cb7
ms.sourcegitcommit: 477cce131dc4a3c212ab18a8763a50b2f3bb20b1
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/09/2021
ms.locfileid: "51649761"
---
# <a name="fix-0x8004de40-error-in-onedrive"></a><span data-ttu-id="92486-102">Исправление 0x8004de40 ошибки в OneDrive</span><span class="sxs-lookup"><span data-stu-id="92486-102">Fix 0x8004de40 error in OneDrive</span></span>

<span data-ttu-id="92486-103">Если вы работаете с Windows 7 и получаете эту ошибку, обновление, чтобы включить [TLS 1.1 и TLS 1.2](https://support.microsoft.com/topic/update-to-enable-tls-1-1-and-tls-1-2-as-default-secure-protocols-in-winhttp-in-windows-c4bd73d2-31d7-761e-0178-11268bb10392)в качестве безопасных протоколов по умолчанию в WinHTTP в Windows .</span><span class="sxs-lookup"><span data-stu-id="92486-103">If you're running Windows 7 and receive this error, [Update to enable TLS 1.1 and TLS 1.2 as default secure protocols in WinHTTP in Windows](https://support.microsoft.com/topic/update-to-enable-tls-1-1-and-tls-1-2-as-default-secure-protocols-in-winhttp-in-windows-c4bd73d2-31d7-761e-0178-11268bb10392).</span></span>

<span data-ttu-id="92486-104">Если вы работаете с Windows 10 и получаете ошибку 0x8004de40 OneDrive:</span><span class="sxs-lookup"><span data-stu-id="92486-104">If you're running Windows 10, and you receive an 0x8004de40 error with OneDrive:</span></span>

- <span data-ttu-id="92486-105">Перезагружайте затронутый компьютер, подключив его к домену Acitve Directory.</span><span class="sxs-lookup"><span data-stu-id="92486-105">Reboot the affected computer while connected to your Acitve Directory domain.</span></span>
- <span data-ttu-id="92486-106">Если перезагрузка не устраняет проблему, отсоединяйтесь и всоедините устройство с Azure AD.</span><span class="sxs-lookup"><span data-stu-id="92486-106">If a reboot doesn't fix the issue, unjoin and rejoin your device from Azure AD.</span></span> 

<span data-ttu-id="92486-107">**Примечание.** Вы должны быть в корпоративной сети при выполнении этих действий.</span><span class="sxs-lookup"><span data-stu-id="92486-107">**Note**: You should be on your corporate network while performing these steps.</span></span> <span data-ttu-id="92486-108">Не выполнять эти действия, если вы не подключены к корпоративной инфраструктуре (например, во время путешествия).</span><span class="sxs-lookup"><span data-stu-id="92486-108">Don't perform these steps when you aren't connected to your corporate infrastructure (for example, while traveling).</span></span> 

1. <span data-ttu-id="92486-109">Откройте командную команду с повышенным нажатием, выбрав **команду Начните,** щелкните правой кнопкой **мыши** Командная подсказка, а затем выберите Выполнить в качестве **администратора.**</span><span class="sxs-lookup"><span data-stu-id="92486-109">Open an elevated command prompt by selecting **Start**, right-click **Command Prompt**, and then select **Run as administrator**.</span></span>

1. <span data-ttu-id="92486-110">Введите *dsregcmd /leave* and press **Enter**.</span><span class="sxs-lookup"><span data-stu-id="92486-110">Type *dsregcmd /leave* and press **Enter**.</span></span>

1. <span data-ttu-id="92486-111">По завершению введите *dsregcmd/join* и нажмите **кнопку Ввод**.</span><span class="sxs-lookup"><span data-stu-id="92486-111">When complete, type *dsregcmd /join* and press **Enter**.</span></span>

1. <span data-ttu-id="92486-112">После завершения закроем командную подсказку.</span><span class="sxs-lookup"><span data-stu-id="92486-112">When complete, close the command prompt.</span></span>

1. <span data-ttu-id="92486-113">Перезагружай компьютер и войдите в OneDrive.</span><span class="sxs-lookup"><span data-stu-id="92486-113">Reboot the computer, and log into OneDrive.</span></span>
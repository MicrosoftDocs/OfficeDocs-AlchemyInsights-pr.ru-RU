---
title: Microsoft Defender для Office 365 для SharePoint, OneDrive и Microsoft Teams
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1037
ms.assetid: ''
ms.openlocfilehash: 7d2ed7bc4c7d99cd01dadc12e38762903d6d8ab3
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52543590"
---
# <a name="microsoft-defender-for-office-365-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="a26c3-102">Microsoft Defender для Office 365 для SharePoint, OneDrive и Microsoft Teams</span><span class="sxs-lookup"><span data-stu-id="a26c3-102">Microsoft Defender for Office 365 for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="a26c3-103">Выполните следующие действия, чтобы включить Microsoft Defender для Office 365:</span><span class="sxs-lookup"><span data-stu-id="a26c3-103">Follow these steps to enable Microsoft Defender for Office 365:</span></span>

1. <span data-ttu-id="a26c3-104">Войдите [https://protection.office.com](https://protection.office.com) и войдите с учетной записью глобального администратора или администратора безопасности.</span><span class="sxs-lookup"><span data-stu-id="a26c3-104">Go to [https://protection.office.com](https://protection.office.com) and sign in with a global administrator or security administrator account.</span></span>

2. <span data-ttu-id="a26c3-105">В левой области навигации под **управлением Угрозы** выберите **политики** \> **Сейф вложения**.</span><span class="sxs-lookup"><span data-stu-id="a26c3-105">In the left navigation pane under **Threat management**, choose **Policy** \> **Safe Attachments**.</span></span>

3. <span data-ttu-id="a26c3-106">Выберите **Включить защитник для Office 365 для SharePoint, OneDrive и Microsoft Teams**.</span><span class="sxs-lookup"><span data-stu-id="a26c3-106">Select **Turn on Defender for Office 365 for SharePoint, OneDrive, and Microsoft Teams**.</span></span>

4. <span data-ttu-id="a26c3-107">[Создайте политику оповещения о действиях для](/microsoft-365/compliance/create-activity-alerts) получения уведомлений при обнаружении вредоносных файлов.</span><span class="sxs-lookup"><span data-stu-id="a26c3-107">[Create an activity alert policy](/microsoft-365/compliance/create-activity-alerts) to receive notifications when we detect malicious files.</span></span>

<span data-ttu-id="a26c3-108">Полные инструкции см. в этой Сейф вложения для [SharePoint, OneDrive и Microsoft Teams.](/microsoft-365/security/office-365-security/turn-on-atp-for-spo-odb-and-teams)</span><span class="sxs-lookup"><span data-stu-id="a26c3-108">For complete instructions, see this [Turn on Safe Attachments for SharePoint, OneDrive, and Microsoft Teams](/microsoft-365/security/office-365-security/turn-on-atp-for-spo-odb-and-teams).</span></span>

<span data-ttu-id="a26c3-109">**Примечание.** По проекту Microsoft Defender для Office 365 не сканирует каждый файл SharePoint Online, OneDrive для бизнеса или Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="a26c3-109">**Note**: By design, Microsoft Defender for Office 365 doesn't scan every single file in SharePoint Online, OneDrive for Business, or Microsoft Teams.</span></span> <span data-ttu-id="a26c3-110">Файлы сканируют асинхронно с помощью процесса, который использует действия общего доступа, действия гостей и сигналы угроз для выявления вредоносных файлов.</span><span class="sxs-lookup"><span data-stu-id="a26c3-110">Files are scanned asynchronously by a process that uses sharing activity, guest activity, and threat signals to identify malicious files.</span></span> <span data-ttu-id="a26c3-111">Дополнительные сведения см. [в Сейф вложениях SharePoint, OneDrive и Microsoft Teams.](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)</span><span class="sxs-lookup"><span data-stu-id="a26c3-111">For more information, see [Safe Attachments for SharePoint, OneDrive, and Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams).</span></span>

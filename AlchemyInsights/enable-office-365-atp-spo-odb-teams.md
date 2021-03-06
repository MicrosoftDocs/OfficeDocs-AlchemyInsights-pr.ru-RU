---
title: Включить Office 365 atP для SharePoint, OneDrive и Microsoft Teams
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: dd367176f8d6f38f1f94ae6627229234f15c81ff
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52543941"
---
# <a name="enable-microsoft-defender-for-office-365-for-sharepoint-online-onedrive-and-microsoft-teams"></a>Включить Microsoft Defender для Office 365 для SharePoint Online, OneDrive и Microsoft Teams

1. Перейдите на https://protection.office.com и войдите.
2. Выберите **политику управления**  >    >  **угрозами Сейф вложения.**
3. Выберите **Включить Защитник для Office 365 для SharePoint, OneDrive и Microsoft Teams,** а затем нажмите **кнопку Сохранить**.
4. (Рекомендуется) В качестве глобального администратора или администратора SharePoint Online запустите комлет [Set-SPOTenant](/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) с параметром **DisallowInfectedFileDownload,** заданным для *true*.
5. (Рекомендуется) [Настройка оповещений](/microsoft-365/security/office-365-security/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) для обнаруженных файлов.

> [!NOTE]
> Microsoft Defender для Office 365 не будет сканировать каждый файл SharePoint Online, OneDrive или Microsoft Teams. Файлы сканируют асинхронно, с помощью процесса, который использует события совместной и гостевой активности, а также интеллектуальные heuristics и сигналы угрозы для выявления вредоносных файлов. См. в Office 365 [Microsoft Defender для SharePoint, OneDrive и Microsoft Teams](/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams).
---
title: Изменение требований к надежному паролю
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: a054735a0c139c90d76098297bb9984d37464d3b
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/22/2020
ms.locfileid: "43706574"
---
# <a name="change-strong-password-requirement"></a>Изменение требований к надежному паролю

По умолчанию Майкрософт требует использования надежных паролей. 

С помощью PowerShell можно отключить надежные пароли для определенных пользователей с помощью этой команды:<br>
*Set-MsolUser – UserPrincipalName <UserPrincipalName> – стронгпассвордрекуиред $false*

- [Дополнительные сведения о политике паролей](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [Подключение к Microsoft 365 с помощью PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [Дополнительные сведения о командах MsolUser PowerShell](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)

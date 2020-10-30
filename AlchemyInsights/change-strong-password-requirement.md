---
title: Изменение требований к надежному паролю
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: 8ce331275e066b5a4f177ae27178ec726f90762f
ms.sourcegitcommit: aa35d2e1829f7d07f64fb891bf73b1fd80f0864c
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/30/2020
ms.locfileid: "48804436"
---
# <a name="change-strong-password-requirement"></a>Изменение требований к надежному паролю

По умолчанию Майкрософт требует использования надежных паролей.

С помощью PowerShell можно отключить надежные пароли для определенных пользователей с помощью следующих команд:

`Set-MsolUser –UserPrincipalName <UserPrincipalName> –StrongPasswordRequired  $false`

Чтобы отключить надежные пароли для всех пользователей, используйте:

`Get-MsolUser | Set-MsolUser -StrongPasswordRequired $false`

- [Дополнительные сведения о политике паролей](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [Подключение к Microsoft 365 с помощью PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [Дополнительные сведения о командах MsolUser PowerShell](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)

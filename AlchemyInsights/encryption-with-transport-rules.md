---
title: Шифрование с помощью правил транспорта
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002635"
- "5154"
ms.openlocfilehash: 3f16c7e7be99a50cd57f47ea2801b3022c4aec95
ms.sourcegitcommit: 07725fcaf073f0ac145f98653b989afdb34c5ad0
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/28/2020
ms.locfileid: "43915167"
---
# <a name="encryption-with-transport-rules"></a>Шифрование с помощью правил транспорта

В [Центре администрирования Exchange](https://go.microsoft.com/fwlink/p/?linkid=834822) (EAC) вы можете использовать функции шифрования сообщений Office (OME) в правилах потока обработки почты, чтобы активировать шифрование сообщений. Выберите параметр **Применить шифрование сообщений Office 365 и защиту прав** в условии правила транспорта.

- Дополнительные сведения см. в статье [Определение правила потока обработки почты для шифрования](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email).

- В PowerShell используйте командлет [New-TransportRule](https://docs.microsoft.com/microsoft-365/compliance/define-mail-flow-rules-to-encrypt-email?view=o365-worldwide#use-exchange-online-powershell-to-create-a-mail-flow-rule-for-encrypting-email-messages-without-the-new-ome-capabilities) и присвойте параметру *ApplyOME* значение $true.

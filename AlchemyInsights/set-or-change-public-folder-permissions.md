---
title: Настройка или изменение разрешений общедоступных папок
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cffdf9bf-34ce-40f6-a69e-d02f17d9caef
ms.openlocfilehash: e419c72a890e68fc7b6d40d2b64406e42f9b0769
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/15/2021
ms.locfileid: "51789220"
---
# <a name="permissions-and-public-folders"></a>Разрешения и общедоступные папки

Разрешения в общедоступных папках можно изменить с помощью Outlook, центра администрирования Exchange (EAC) или PowerShell:
  
- Инструкции Outlook нажмите [здесь](https://support.office.com/article/Set-or-change-permissions-for-a-public-folder-b2e0440c-7873-48ec-9ff2-b1a20b723005.aspx).
    
- Для EAC обратитесь к [этой статье для](https://technet.microsoft.com/library/jj651147%28v=exchg.150%29.aspx.aspx#Anchor_1) инструкций. 
    
- Для Powershell обратитесь к [этой статье](https://technet.microsoft.com/library/bb124743%28v=exchg.160%29.aspx.aspx) для инструкций по использованию командного Add-PublicFolderClientPermission. Если вам нужны инструкции для подключения к Exchange Powershell, нажмите [здесь](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx.aspx).
    
Если **внешние** пользователи не могут отправлять электронные письма в общедоступные папки с включенной почтой, причина может быть в том, что в публичной папке отсутствуют разрешения, необходимые для внешней доставки электронной почты. Это можно исправить с помощью инструкций Outlook [здесь](https://technet.microsoft.com/library/aa997560%28v=exchg.150%29.aspx.aspx#Anchor_1)или инструкций PowerShell [здесь](https://support.microsoft.com/help/2984402/-5.7.1-smtp-550-5.7.1-resolver.rst.authrequired-nondelivery-report-when-external-users-try-to-send-mail-to-mail-enabled-public-folders-in-office-365.aspx).
  


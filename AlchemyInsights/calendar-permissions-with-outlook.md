---
title: Разрешения для календаря
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3800009"
- "611"
ms.openlocfilehash: 78f27014c60badc801212177dd455ef2a0de5a9e
ms.sourcegitcommit: 722e9a0ed058cb1eab2dd053be2418b60f7d4aac
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/23/2020
ms.locfileid: "44854038"
---
# <a name="calendar-permissions"></a>Разрешения для календаря

Пользователи могут изменять собственные разрешения календаря с помощью Outlook в Интернете или на других клиентах, но в качестве администратора также может потребоваться изучить.  
С помощью командлета Exchange PowerShell вы увидите разрешение на доступ к календарю пользователя:

`Get-MailboxFolderPermission <SMTPAddress>:\Calendar | FT -a`

Более подробную информацию можно узнать в следующих статьях:

- [Get — MailboxFolderPermission](https://docs.microsoft.com/powershell/module/exchange/get-mailboxfolderpermission?view=exchange-ps)

- [Set — MailboxFolderPermission](https://docs.microsoft.com/powershell/module/exchange/set-mailboxfolderpermission?view=exchange-ps)

- [Add — MailboxFolderPermission](https://office.visualstudio.com/DefaultCollection/MAX/_queries/query/Add-MailboxFolderPermission)

Разрешения календаря используются в общем доступе к календарю для просмотра дополнительных сведений об общем доступе к календарю Outlook в следующих статьях:

- [Предоставление общего доступа к календарю Outlook другим пользователям](https://support.office.com/article/353ed2c1-3ec5-449d-8c73-6931a0adab88)
- [Предоставление общего доступа к календарю в Outlook в Интернете для бизнеса](https://support.office.com/article/7ecef8ae-139c-40d9-bae2-a23977ee58d5)

Для устранения неполадок, связанных с календарем, можно воспользоваться [помощником по поддержке и восстановлению](https://support.microsoft.com/office/e90bb691-c2a7-4697-a94f-88836856c72f) .
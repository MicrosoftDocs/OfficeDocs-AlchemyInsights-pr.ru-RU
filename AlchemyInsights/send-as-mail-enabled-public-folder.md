---
title: Отправка общедоступной папки с включенной поддержкой почты в EXO
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1956"
- "3500007"
ms.openlocfilehash: 0765262c04571e7df139de993611fd6e67068c54
ms.sourcegitcommit: 45635cc7a6c36d6c7b5f78215ad32f2aa7e3aed0
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/08/2020
ms.locfileid: "48394691"
---
# <a name="sendas-mail-enabled-public-folder"></a>Общедоступная папка с включенной поддержкой почты SendAs

В следующем примере назначается разрешение "Отправить как" для общедоступной папки с включенной поддержкой почты NewPF1 пользователю Жасон.

Add-RecipientPermission — Identity "NewPF1" — доверенное лицо "Жасон" — AccessRights "SendAs"

Для получения подробных сведений о синтаксисе и параметрах см. [разрешения "Отправить как" или "Отправить от имени" для общедоступных папок, поддерживающих почту](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/assign-permissions-mail-enabled-pfs).

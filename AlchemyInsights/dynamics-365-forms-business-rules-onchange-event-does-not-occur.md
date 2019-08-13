---
title: 'Бизнес-правила Dynamics 365: бизнес-правило не срабатывает для формы'
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1926"
- "6200018"
ms.openlocfilehash: 4ade8d2f68b465298e2d6efff3eef4f04f25c3bf
ms.sourcegitcommit: a413a0e27ef4ab8c484fa9fccff8bbef381c8b96
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/16/2019
ms.locfileid: "35748553"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a>Событие OnChange не происходит, если поле изменяется программным способом

Событие *onChange* не происходит, если поле изменяется программным способом с помощью *атрибута.* метод [SetValue](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) . Если вы хотите, чтобы обработчики ** событий для события onchange выполнялись после установки значения, необходимо использовать *атрибут формконтекст. Data. Entity.* метод [фиреончанже](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) в коде.

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
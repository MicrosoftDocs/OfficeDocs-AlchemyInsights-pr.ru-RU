---
title: Внеплановая многофакторная проверка подлинности
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: ''
ms.custom:
- "1300007"
- "4372"
ms.openlocfilehash: a664bd709062ec1335ebcf1f9adddc8aef917ac1
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766614"
---
# <a name="unexpected-multi-factor-authentication"></a>Внеплановая многофакторная проверка подлинности

Если ваш клиент был создан позднее 21 октября 2019 г. и вам неожиданно предлагают пройти MFA, скорее всего, в вашем клиенте включены [параметры безопасности по умолчанию](https://aka.ms/securitydefaults). 

Для управления параметрами безопасности по умолчанию:

1. Войдите в [Центр администрирования](https://go.microsoft.com/fwlink/p/?linkid=834822) с учетными данными глобального администратора.

2. Перейдите в раздел [Свойства Azure Active Directory](https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Properties).

3. В нижней части страницы щелкните **Управление параметрами безопасности по умолчанию**.

4. Нажмите кнопку **Да**, чтобы включить параметры безопасности по умолчанию, или **Нет**, чтобы их отключить.

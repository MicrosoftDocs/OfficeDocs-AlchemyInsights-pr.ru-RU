---
title: Monitor Intune Conditional Access
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 02/25/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004636"
- "8386"
ms.openlocfilehash: e2803a49aaf087ac55b1fd62056e2b0af3fcd919
ms.sourcegitcommit: 229bd519ec1c14c65a243226a94eee23e117a7fc
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/03/2021
ms.locfileid: "50417319"
---
# <a name="monitor-intune-conditional-access"></a>Monitor Intune Conditional Access

Пользователи с условным доступом получат уведомление по электронной почте, если они не соответствуют требованиям к доступу вашей организации. Для решения рекомендуется одно или несколько следующих решений:

1. Если предполагается, что устройство зарегистрируется, советуйте пользователю перейти в приложение Портал компании и убедиться, что оно отображается на портале компании. Если этого не сделать, пользователь должен записать устройство.
1. На портале Azure перейдите к **соблюдению требований к устройству Intune.**  >   
1. Чтобы просмотреть отчет о соответствии устройств, чтобы убедиться, что устройство пользователя помечено как совместимый, в **статье Monitor** нажмите **кнопку Соответствие устройству.**
1. На портале Azure перейдите к **соблюдению требований к устройству Intune.**  >   В **статье Управление щелкните** **Политики**. В списке политик соответствия требованиям убедитесь, что профиль назначен устройству пользователя. Если профиль не назначен, intune не сможет подтвердить состояние соответствия требованиям устройства.
1. Изменение назначения условного доступа пользователя.
1. На портале Azure перейдите к политикам условного доступа **Intune,** выберите политику из списка и нажмите  >    >  кнопку **Пользователи и группы.**
1. Чтобы на кого-то нацелить определенную политику, добавьте их в список **Include.** Чтобы исключить человека из политики, добавьте его в список **Исключений.**

**Полезные ссылки:**

- [Обзор соответствия требованиям устройств](https://docs.microsoft.com/intune/device-compliance-get-started)
- [Устранение неполадок в ЦС](https://docs.microsoft.com/intune/troubleshoot-conditional-access)
- [Политика устранения неполадок](https://docs.microsoft.com/intune/troubleshoot-policies-in-microsoft-intune)
- [Мониторинг соответствия устройствам Intune](https://docs.microsoft.com/intune/compliance-policy-monitor)

> [!NOTE]
> Эти действия полезны только для устранения неполадок с функцией Условного доступа Azure Active Directory. Кроме того, можно карантить устройство, блокирующее доступ к электронной почте с помощью политики Exchange. Дополнительные сведения об управлении устройствами Exchange можно найти [**здесь.**](https://docs.microsoft.com/previous-versions/office/exchange-server-2010/ff959225(v=exchg.141))

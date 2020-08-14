---
title: Удаление данных и очистка устройств в Intune
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/27/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1279"
- "6700008"
ms.openlocfilehash: efaf111f694ab57d0435b141a6d4baad58658ed2
ms.sourcegitcommit: e34bb95fb93250f1dc7aec6a13578bb3bb355935
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 07/28/2020
ms.locfileid: "45434634"
---
# <a name="removing-data-and-wiping-devices-from-intune"></a>Удаление данных и очистка устройств в Intune

С помощью удаленных действий снятия с учета и очистки устройств можно удалить данные компании, находящиеся под управлением Intune, или выполнить сброс параметров устройства и восстановить параметры по умолчанию.

1. Войдите на панель мониторинга "Управление устройствами Microsoft 365", перейдите в раздел **Устройства** > **Все устройства**.
2. Выберите устройство, которое нужно очистить.
3. Выберите тип удаленной очистки. При снятии с учета удаляются только данные организации. При полной очистке восстанавливаются заводские параметры устройства.
4. Нажмите кнопку **Да** для подтверждения. До завершения очистки для устройства отображается состояние действия "Снятие с учета ожидается".</br>
    После завершения этого действия это мобильное устройство перестанет отображаться в списке управляемых устройств.

**Примечание.** Данные компании невозможно удалить с устройств, присоединенных к Azure AD.

Подробные сведения о действиях снятия с учета и очистки, включая сведения о том, какие данные сохраняются, а какие — удаляются, см. в статье [Удаление устройств с помощью очистки, снятия с учета или отмены регистрации вручную](https://docs.microsoft.com/intune/devices-wipe).

Сведения об удалении всех данных с устройств macOS см. в статье [Удаление всех данных с устройства macOS](https://docs.microsoft.com/intune/device-erase).
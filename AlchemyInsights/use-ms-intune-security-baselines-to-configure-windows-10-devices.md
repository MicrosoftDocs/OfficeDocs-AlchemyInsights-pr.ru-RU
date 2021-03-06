---
title: Настройка устройств с Windows 10 с помощью базовых планов безопасности Microsoft Intune
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 12/03/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004135"
- "7211"
ms.openlocfilehash: 24257f1ac5752df1598d08fcfdb95ee2642adfea
ms.sourcegitcommit: c069f1b53567ad14711c423740f120439a312a60
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 12/04/2020
ms.locfileid: "49571895"
---
# <a name="use-microsoft-intune-security-baselines-to-configure-windows-10-devices"></a>Настройка устройств с Windows 10 с помощью базовых планов безопасности Microsoft Intune

Базовые показатели безопасности Intune помогают защитить пользователей и устройства. Базовые планы безопасности — это предварительно настроенные группы параметров Windows, которые использовались для применения известной группы параметров и значений по умолчанию, рекомендуемых соответствующими группами обеспечения безопасности. Создавая базовый профиль безопасности в Intune, вы создаете шаблон, который состоит из нескольких профилей конфигурации устройств.

При развертывании базовых показателей безопасности до групп пользователей или устройств эти параметры применяются к устройствам, которые работают в Windows 10 или более поздней версии. Например, базовый план безопасности MDM автоматически (1) включает BitLocker для съемных дисков, (2) требует пароль для разблокировки устройства, а (3) отключает обычную проверку подлинности. Если значение по умолчанию не работает в вашей среде, настройте базовую линию для применения нужных параметров.

Шаблоны безопасности также помогают установить сквозной безопасный рабочий процесс в Microsoft 365. Ниже приведены некоторые преимущества.

- Базовый план безопасности содержит рекомендации и рекомендации для параметров, влияющих на безопасность. Так как партнеры Intune с группой безопасности Windows, которая создает базовые планы для групповых политик, эти рекомендации основываются на надежном руководстве и расширенном интерфейсе.
- Если вы не знакомы с Intune и не знаете, с чего начать, базовые планы безопасности помогут быстро создать и развернуть защищенный профиль.
- Если в настоящее время используется групповая политика, то миграция в Intune в целях управления значительно упрощается с учетом базовых показателей безопасности, так как они встроены в Intune и включают в себя новейшие возможности управления.

Чтобы узнать больше, ознакомьтесь с [планами безопасности Windows](https://go.microsoft.com/fwlink/?linkid=2141503) и [управлением мобильными устройствами](https://go.microsoft.com/fwlink/?linkid=2141701).
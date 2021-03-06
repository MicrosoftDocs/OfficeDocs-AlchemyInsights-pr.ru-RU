---
title: Используйте Microsoft Intune безопасности для настройки Windows 10 устройств
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 06/04/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9006500"
- "11142"
ms.openlocfilehash: 88525fccd6dcde0cb3949e348d1f2a7df3ee7ce7
ms.sourcegitcommit: f7a9e97d04b7b6cbb633b32094d40f1874bf0fce
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/06/2021
ms.locfileid: "52783228"
---
# <a name="use-microsoft-intune-security-baselines-to-configure-windows-10-devices"></a>Используйте Microsoft Intune безопасности для настройки Windows 10 устройств

Базовые конфигурации безопасности Intune помогают защитить пользователей и устройства. Базовые показатели безопасности Windows предварительно настроенных групп, используемых для применения известной группы параметров и значений по умолчанию, рекомендуемых соответствующими группами безопасности. Создавая профиль базовой конфигурации безопасности в Intune, вы создаете шаблон, состоящий из нескольких профилей конфигурации устройств.

При развертывании базовых показателей безопасности для групп пользователей или устройств эти параметры применяются к устройствам, которые работают на Windows 10 или позже. Например, базовый уровень безопасности управления мобильными устройствами (MDM) Майкрософт автоматически включает BitLocker для съемных дисков, требует пароль для разблокировки устройства и отключает базовую проверку подлинности. Если в вашей среде не поддерживается значение по умолчанию, вы можете настроить базовую конфигурацию, чтобы применить нужные параметры.

Базовые конфигурации безопасности также помогают создать комплексный безопасный рабочий процесс в Microsoft 365. Базовая конфигурация безопасности включает рекомендации для параметров, влияющих на безопасность. Intune партнеров с группой Windows, которая создает базовые основы для групповой политики, поэтому эти рекомендации основаны на твердом руководстве и обширный опыт.

Если вы не знаете, с чего начать, базовые параметры безопасности помогут быстро создать и развернуть безопасный профиль. Если вы в настоящее время используете групповую политику, миграция в Intune для целей управления намного проще с базовыми показателями безопасности, так как они встроены в Intune и включают передовые возможности управления.

Дополнительные данные см. [в Windows базовых показателей](/windows/security/threat-protection/windows-security-baselines) безопасности и [управления мобильными устройствами.](/windows/client-management/mdm/)


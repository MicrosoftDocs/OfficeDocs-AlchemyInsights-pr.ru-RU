---
title: Проблемы при установке Microsoft Defender на Mac и Linux
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/16/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "6028"
- "9001222"
ms.openlocfilehash: 39f180852fd0438597fa1ce665b2703fbc7b1aa4
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52539693"
---
# <a name="issues-installing-microsoft-defender-on-mac-or-linux"></a>Проблемы при установке Microsoft Defender на Mac и Linux

**Mac**

- Перед установкой пакета Microsoft Defender для Mac убедитесь, что система удовлетворяет требованиям. Дополнительные сведения см. в статье [Установка Microsoft Defender для Mac](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-mac#how-to-install-microsoft-defender-atp-for-mac).  
- Ознакомьтесь со сведениями в файле "/Library/Logs/Microsoft/mdatp/install.log".

**Linux**

- Перед установкой пакета Microsoft Defender ATP для Linux убедитесь, что система удовлетворяет требованиям. Дополнительные сведения см. в статье [Установка MDATP для Linux](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-linux#system-requirements). 
- Чтобы узнать, как проверить, запущена ли служба MDATP, ознакомьтесь с разделом [Сбой установки](/windows/security/threat-protection/microsoft-defender-atp/linux-support-install#installation-failed).  
    Если службу запустить не удалось, то, чтобы найти и устранить проблемы, следуйте инструкциям в разделе [Действия по устранению неполадок, если служба MDATP не запущена](/windows/security/threat-protection/microsoft-defender-atp/linux-support-install#steps-to-troubleshoot-if-mdatp-service-isnt-running).
- Пошаговые инструкции по проверке конфигурации клиента, которые помогут проверить состояние продукта и прогнать тест для обнаружения неполадок с помощью текстового файла EICAR, см. в разделе [Конфигурация клиента](/windows/security/threat-protection/microsoft-defender-atp/linux-install-manually#client-configuration).  

    **Примечание.** Список файловых систем, для которых поддерживается управление доступом, см. в статье [ATP в Microsoft Defender для Linux](/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-atp-linux#system-requirements).
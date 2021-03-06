---
title: Развертывание команд в автономном режиме или с помощью новых или существующих установок Office
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000660"
- "2509"
ms.openlocfilehash: c3ca4365abc41509ccf602c5b9046655706840fc
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/15/2020
ms.locfileid: "47806772"
---
# <a name="deploying-teams-as-standalone-or-with-new-or-existing-office-installations"></a>Развертывание команд в автономном режиме или с помощью новых или существующих установок Office

Microsoft Teams теперь входит в состав ***новых установок*** приложений Microsoft 365 для предприятий, Майкрософт 365 для бизнеса и Office для Mac. Дополнительные сведения о том, [когда будет запущено приложение Microsoft Teams, будет включено в новые установки Office?](https://docs.microsoft.com/deployoffice/teams-install#when-will-microsoft-teams-start-being-included-with-new-installations-of-microsoft-365-apps)

Кроме того, начиная с версии 1906 в текущем канале, Teams будет ***добавляться к существующим установкам*** приложений Microsoft 365 для предприятий (и приложений Microsoft 365 для бизнеса) на устройствах под управлением Windows, когда вы обновите текущую установку до последней версии. Дополнительные сведения [о существующих установках Office](https://docs.microsoft.com/deployoffice/teams-install#what-about-existing-installations-of-microsoft-365-apps)

> [!NOTE]
> Если вы не хотите ждать этого расписания развертывания, вы можете развернуть Teams как самостоятельный для пользователей, [выполнив указанные ниже инструкции](https://docs.microsoft.com/MicrosoftTeams/msi-deployment),   или пользователи смогут установить Teams самостоятельно  [https://teams.microsoft.com/downloads](https://teams.microsoft.com/downloads) .

Если ваша организация не готова к развертыванию Teams, мы поможем предпринять действия для ***исключения Teams*** из [новых](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-microsoft-365-apps) или [существующих](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams) экземпляров Office. Если вы хотите установить Teams, но не хотите, чтобы команда автоматически запускалась для пользователя после установки, ознакомьтесь со статьей [запретить автоматический запуск Microsoft Teams после установки](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation).

Чтобы ***Удалить Teams*** с устройства под управлением Windows, ознакомьтесь с разделом [uninstall Microsoft Teams](https://support.office.com/article/3b159754-3c26-4952-abe7-57d27f5f4c81). Чтобы очистить Microsoft Teams с нескольких целевых компьютеров или пользователей, ознакомьтесь с разделом [развертывание Microsoft Teams](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up).

Если вы используете общие компьютеры, службы удаленных рабочих столов (RDS) или инфраструктуру виртуальных рабочих столов (VDI), ознакомьтесь [со статьей общие среды компьютера и VDI с Microsoft Teams](https://docs.microsoft.com/deployoffice/teams-install#shared-computer-and-vdi-environments-with-microsoft-teams).

Если вы используете Office для Mac, ознакомьтесь с разделом [Установка Microsoft Teams на компьютере Mac](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac).

> [!NOTE]
> После установки Teams он [автоматически обновляется](https://docs.microsoft.com/deployoffice/teams-install#feature-and-quality-updates-for-microsoft-teams) приблизительно каждые две недели с новыми функциями и обновлениями качества. 
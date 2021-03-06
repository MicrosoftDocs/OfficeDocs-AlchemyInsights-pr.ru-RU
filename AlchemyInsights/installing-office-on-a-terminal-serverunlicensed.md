---
title: Установка Office на сервере терминалов — Нелицензировано
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "917"
- "2000020"
ms.assetid: b1074430-489e-4d49-bfe4-3d8783d8073c
ms.openlocfilehash: 1d862f60e7a8a4c90c83f4538e57972b0c0547da
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/14/2020
ms.locfileid: "47663130"
---
# <a name="installing-office-on-a-terminal-server"></a>Установка Office на сервере терминалов

Для развертывания приложений Microsoft 365 для предприятий в Windows Server с помощью служб удаленных рабочих столов (RDS), ранее именуемых службами терминалов:
  
- Вы должны иметь подписку на Microsoft 365, включающую приложения Майкрософт 365 для предприятий, например Office 365 Enterprise E3 или Enterprise "\". Приложения Microsoft 365 для бизнеса и Microsoft 365 для планов бизнеса Premium не включают приложения Microsoft 365 для предприятия.

- Необходимо включить [активацию на общем компьютере](https://docs.microsoft.com/DeployOffice/overview-shared-computer-activation).

Если вы хотите установить приложения Microsoft 365 для Enterprise в RDS из центра администрирования Майкрософт 365, ***использующего параметры установки по умолчанию***, выполните указанные ниже действия.

> [!TIP]
> Вы также можете скачать и запустить [Помощник по поддержке и восстановлению Майкрософт](https://aka.ms/SaRA_OfficeSCA_M365Portal) для установки приложений Microsoft 365 для предприятий в режиме активации на общем компьютере.
  
1. Проверьте, что у вас есть подписка на Microsoft 365. [Узнайте, как](https://docs.microsoft.com/microsoft-365/admin/admin-overview/what-subscription-do-i-have)

2. При необходимости переключитесь на другую подписку Microsoft 365. [Узнайте, как](https://docs.microsoft.com/microsoft-365/commerce/subscriptions/switch-to-a-different-plan)

3. Если Office уже установлен на сервере RDS с использованием других подписок Microsoft 365, удалите его. Например, с помощью панели управления \> удалите программу. Удаление с помощью [помощника по поддержке и восстановлению Майкрософт](https://aka.ms/SARA-OfficeUninstall-Alchemy) , если у вас возникли проблемы.

4. На сервере RDS Войдите в центр администрирования Microsoft 365 с учетной записью администратора и [установите приложения Microsoft 365 для предприятия](https://portal.office.com/OLS/MySoftware.aspx).

5. После установки Office ***не открывайте и не входите*** в приложения Office.

6. На сервере RDS Включите активацию на общем компьютере, отредактировав реестр, выполнив указанные ниже действия.

1. Щелкните правой кнопкой мыши кнопку Windows в левом нижнем углу экрана и выберите команду выполнить. В поле Открыть введите **regedit**и нажмите кнопку ОК.

2. Выберите Да, если будет предложено разрешить редактору реестра вносить изменения на устройстве.

3. В редакторе реестра добавьте строковое значение **SharedComputerLicensing** с параметром 1 в разделе HKEY_LOCAL_MACHINE \софтваре\микрософт \оффице\кликкторун\конфигуратион.

7. ***Выполните вход в качестве конечного пользователя*** на сервере RDS и [Убедитесь, что активация на общем компьютере включена для приложений Microsoft 365 для предприятий](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation#verify-that-activation-for-microsoft-365-apps-succeeded).

Для получения дополнительных сведений о предварительных требованиях и инструкциях по настройке для настраиваемых установок с помощью средства развертывания Office, ознакомьтесь со статьей [развертывание приложений Microsoft 365 для предприятий с помощью служб удаленных рабочих столов](https://docs.microsoft.com/DeployOffice/deploy-microsoft-365-apps-remote-desktop-services).
  
Устранение ошибок, связанных с активацией на общедоступном компьютере, можно найти в [статье Устранение неполадок, связанных с активацией на общем компьютере для приложений Microsoft 365 для предприятий](https://docs.microsoft.com/DeployOffice/troubleshoot-shared-computer-activation).
  
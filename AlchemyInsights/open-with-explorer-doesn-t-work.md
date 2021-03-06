---
title: Открытие с помощью проводника не работает
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: b8f07022-69fe-4112-a2f6-d3a6cedb966c
ms.openlocfilehash: 5bf28982533d8ca9998605cf3592f317c0ef99b0
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/14/2020
ms.locfileid: "47694469"
---
# <a name="open-with-explorer-isnt-working"></a>Открытие с помощью проводника не работает

Если **окно Открыть в проводнике** или **Просмотреть в проводнике** не работает, убедитесь, что служба WebClient настроена на **Запуск** , выполнив указанные ниже действия. Например, для открытия библиотеки SharePoint или OneDrive может потребоваться много времени, если служба не запущена. 
  
1. В поле поиска Windows введите выполнить, выберите классическое приложение Run. msc, введите Services. msc и нажмите клавишу **Ввод**.
    
2. Прокрутите список вниз до службы WebClient и проверьте столбец **состояние** . Если служба WebClient не **запущена**, дважды щелкните службу, нажмите кнопку **Пуск**, а затем нажмите кнопку **ОК**. Включите службу (при необходимости), выбрав в поле **Тип запуска** значение **вручную** или **автоматически** . 
    
> [!NOTE]
> Устранение неполадок, возникающих при открытии в проводнике, представлено в разделе [Открыть в проводнике](https://go.microsoft.com/fwlink/?linkid=871665). Узнайте, как лучше всего синхронизировать [файлы SharePoint с помощью нового клиента синхронизации OneDrive](https://go.microsoft.com/fwlink/?linkid=871666). 
  


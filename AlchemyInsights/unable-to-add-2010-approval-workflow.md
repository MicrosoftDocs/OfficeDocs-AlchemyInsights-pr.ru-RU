---
title: Не удалось добавить рабочий процесс утверждения 2010
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 0df65cf9-7eae-4de7-88e9-1914635c8d11
ms.openlocfilehash: aa61f1615b60d27cffad15f02f6ce5dbac1b607f
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/14/2020
ms.locfileid: "47699748"
---
# <a name="unable-to-add-2010-approval-workflow"></a>Не удалось добавить рабочий процесс утверждения 2010

В семействе веб-сайтов Microsoft SharePoint невозможно добавить глобальный рабочий процесс для повторного использования (например, "утверждение-SharePoint 2010") в список или библиотеку.
  
Чтобы устранить эту проблему, выполните указанные ниже действия. 
  
1. Откройте корневой веб-сайт семейства веб-сайтов в SharePoint Designer 2013.
  
2. В разделе **объекты сайта**выберите **рабочие процессы**. 
  
3. В разделе **создать** на ленте **рабочие процессы** выберите **Рабочий процесс для повторного использования**. 
  
4. В форме **Создание рабочего процесса для повторного использования** введите имя * * *Repair2010* * *. В качестве **типа платформы**выберите элемент **рабочий процесс SharePoint 2010**и нажмите кнопку **ОК**. 
  
1. В разделе **Сохранение** ленты **рабочего процесса** нажмите кнопку **опубликовать**. 
  
2. В разделе **Управление** ленты **рабочего процесса** выберите параметр **опубликовать глобально**. В появившемся диалоговом окне подтверждения нажмите кнопку **ОК**. 
  
3. В веб-браузере найдите корневой веб-сайт семейства веб-сайтов, а затем **Site Settings** доступ к \> **функциям семейства веб**-сайтов с помощью параметров сайта. Переключать функции **рабочих процессов** : 
  
· Если компонент  *активирован*  , щелкните **Отключить,** а затем нажмите кнопку **активировать**. 
  
· Если компонент  *отключен, нажмите*  кнопку **активировать**. 
  
Для получения дополнительных сведений обратитесь к следующей [статье](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).
  


---
title: Работа с идентификатором правила приложений для iOS VPP 1018
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1018"
- "6700004"
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: 67800b261e7d670181b17783bc81e276d75026e0
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/14/2020
ms.locfileid: "47688959"
---
# <a name="working-with-ios-vpp-applications"></a>Работа с приложениями для iOS VPP

Узнайте, [как управлять приложениями для iOS, приобретенными через программу Volume-Purchase, с помощью Microsoft Intune](https://docs.microsoft.com/intune/vpp-apps-ios) , чтобы узнать о возможностях, ограничениях и действиях по использованию программы Apple Volume Purchase Program, а также ее поддержке в Microsoft Intune.
  
 **Распространенные проблемы:** "Мне назначено приложение для iOS VPP для пользователей, но не удалось выполнить установку".
  
- Это может произойти, если один токен VPP используется для нескольких поставщиков услуг управления мобильными устройствами. Токены VPP от Apple можно использовать только с одним поставщиком. Если вы использовали токен VPP с несколькими поставщиками, необходимо повторно отправить маркер в Intune.

- Установка также может быть неисправной, если общее число установок превышает количество лицензий. Чтобы просмотреть отчет об использовании лицензий, перейдите на страницу "лицензии приложения для **мобильных приложений Intune** " \> **App licenses** . Сведения о том, как повторно использовать лицензии, можно найти в [этой статье.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)

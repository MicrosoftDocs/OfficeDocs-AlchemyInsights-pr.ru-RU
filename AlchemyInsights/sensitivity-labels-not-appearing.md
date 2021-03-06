---
title: Метки конфиденциальности не отображаются
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: 04/21/2020
ms.audience: admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1778"
- "9000181"
ms.openlocfilehash: 6a64e001be115c8e5553a0d8c97b8cb815922c69
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/15/2020
ms.locfileid: "47801197"
---
# <a name="sensitivity-labels-not-appearing"></a>Метки конфиденциальности не отображаются

Метки конфиденциальности позволяют классифицировать и защищать конфиденциальное содержимое. Они могут быть созданы в центре соответствия требованиям Microsoft 365, центре безопасности 365 Майкрософт или Microsoft 365 центр соответствия требованиям & безопасности в разделе классификация > меток конфиденциальности. Чтобы узнать больше об этой функции, просмотрите раздел [Обзор меток конфиденциальности](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels).

Если вы настроили метки конфиденциальности, но они не отображаются в приложениях Microsoft 365, проверьте следующее:

- Убедитесь, что метка конфиденциальности была [опубликована](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels#what-label-policies-can-do) для нужных пользователей и групп.

- Убедитесь, что пользователь использует приложение, которое поддерживает метки чувствительности — просмотрите [метки конфиденциальности в документе](https://support.office.com/article/apply-sensitivity-labels-to-your-documents-and-email-within-office-2f96e7cd-d5a4-403b-8bd7-4cc636bae0f9?#bkmk_whereavailable).

- Если вы переносите [метки Azure Information Protection](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels), учитывайте вопросы, приведенные в [этой статье](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels#considerations-for-unified-labels).

- Поддержка защиты от потери данных (DLP): в настоящее время в качестве условия в политиках защиты от потери данных можно использовать только метки хранения.  Поддержка меток конфиденциальности в политике DLP пока недоступна, но мы работаем над этим.

- Если для метки конфиденциальности включено шифрование, вы можете выбрать один из следующих вариантов:
    - Назначение разрешений
    - Предоставление пользователям возможности назначать разрешения


Дополнительные сведения о возможных проблемах приведены в статье [Известные проблемы с метками чувствительности](https://support.office.com/article/known-issues-with-sensitivity-labels-in-office-b169d687-2bbd-4e21-a440-7da1b2743edc).
---
title: Включение аудита почтовых ящиков
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 81041685cf383a231a9a9739d6daffd6039b4602
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/22/2019
ms.locfileid: "30757831"
---
# <a name="enable-mailbox-auditing"></a>Включение аудита почтовых ящиков

Чтобы включить аудит поЧтовых ящиков для отдельного пользователя или всей Организации, необходимо запустить следующие командлеты из удаленной консоли управления Exchange:
  
 **Один пользователь**
  
Set $ Mailbox: Identity "Джейн Dow" — Auditenabled указывает $true
  
 **Организация**
  
Get/Mailbox – ResultSize Unlimited — фильтр {RecipientTypeDetails – EQ "UserMailbox"} | Set/Mailbox — Auditenabled указывает $true
  
[Подробнее](https://support.office.com/article/aaca8987-5b62-458b-9882-c28476a66918)
  


---
title: На портале отсутствуют устройства Configuration Manager
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4384"
ms.openlocfilehash: b6538cb6a348e194856024680a25af948152910a
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/15/2020
ms.locfileid: "47812164"
---
# <a name="configuration-manager-devices-missing-in-the-portal"></a>На портале отсутствуют устройства Configuration Manager

Для синхронизации устройств [обязательные конечные точки в Интернете](https://docs.microsoft.com/configmgr/tenant-attach/device-sync-actions#internet-endpoints) должны быть доступны на локальном сервере, на котором размещена роль точки подключения службы. Чтобы устранить неполадки с синхронизацией устройств, просмотрите файл **CMGatewaySyncUploadWorker.log**, находящийся в точке подключения службы.

Узнайте больше о том, как [подключить клиент в Microsoft Endpoint Manager](https://docs.microsoft.com/configmgr/tenant-attach/).

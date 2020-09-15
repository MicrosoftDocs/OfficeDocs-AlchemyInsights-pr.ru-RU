---
title: 1554 Winsock Error 10061
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1554"
- "9000079"
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: 4f8007bd8ccb4666260c75fdca15dd0b14eb4e96
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/14/2020
ms.locfileid: "47698875"
---
# <a name="winsock-error-10061"></a><span data-ttu-id="46d6d-102">Ошибка Winsock 10061</span><span class="sxs-lookup"><span data-stu-id="46d6d-102">Winsock error 10061</span></span>

<span data-ttu-id="46d6d-103">Этот код ошибки означает, что корпорации Майкрософт не удалось установить TCP-сокет (подключение) с конечным узлом.</span><span class="sxs-lookup"><span data-stu-id="46d6d-103">This error code means that Microsoft couldn't establish a TCP socket (connection) with the target host.</span></span> <span data-ttu-id="46d6d-104">Наиболее вероятная причина этой ошибки — проблема с настройкой брандмауэра.</span><span class="sxs-lookup"><span data-stu-id="46d6d-104">The most likely cause of this error is a problem with your firewall configuration.</span></span> <span data-ttu-id="46d6d-105">Чтобы устранить эту проблему, проверьте указанные ниже параметры.</span><span class="sxs-lookup"><span data-stu-id="46d6d-105">To fix the problem, check these settings:</span></span>

- <span data-ttu-id="46d6d-106">Проверьте конфигурацию брандмауэра, указав сведения в [диапазонах адресов и IP-адресов Microsoft 365](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges) .</span><span class="sxs-lookup"><span data-stu-id="46d6d-106">Verify your firewall configuration with the information in [Microsoft 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span></span>

- <span data-ttu-id="46d6d-107">Если сообщение об ошибке относится только к Exchange Online Protection (EOP), вы уже получали уведомление об изменении [IP-адресов Exchange Online Protection](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span><span class="sxs-lookup"><span data-stu-id="46d6d-107">If the error is specific to Exchange Online Protection (EOP), you should have been previously notified to a change to the [Exchange Online Protection IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>

- <span data-ttu-id="46d6d-108">Убедитесь, что ваш поставщик услуг Интернета (ISP) не блокирует порт.</span><span class="sxs-lookup"><span data-stu-id="46d6d-108">Verify that your Internet Service Provider (ISP) isn't blocking the port.</span></span>

- <span data-ttu-id="46d6d-109">Проверьте параметры промежуточного узла и целевого сервера в соединителях.</span><span class="sxs-lookup"><span data-stu-id="46d6d-109">Verify the smart host and target server settings in your connectors.</span></span>

<span data-ttu-id="46d6d-110">Обратите внимание, что Microsoft 365 не блокирует *Входящие* подключения таким образом.</span><span class="sxs-lookup"><span data-stu-id="46d6d-110">Note that Microsoft 365 doesn't block *incoming* connections in this manner.</span></span>

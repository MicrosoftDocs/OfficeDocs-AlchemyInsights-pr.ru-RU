---
title: Вопросы об использовании средства развертывания Office (ODT)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: c5b055989014b464d3136895702c8ea40e8eb701
ms.sourcegitcommit: 35e2c122d8a838d98d1f0851c29b16282261580f
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 11/17/2020
ms.locfileid: "49086169"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a>Вопросы об использовании средства развертывания Office (ODT)

Скачайте средство развертывания Office в [ Центре загрузки Майкрософт](https://go.microsoft.com/fwlink/p/?LinkID=626065).
  
После загрузки файла запустите самораспаковывающийся исполняемый файл, который содержит исполняемый файл средства развертывания Office (setupodt.exe) и пример файла конфигурации (configuration.xml).
  
 **Чтобы исключить или удалить приложения Microsoft 365 для корпоративных продуктов с клиентских компьютеров, выполните указанные ниже действия.**
  
При установке приложений Microsoft 365 для Enterprise можно исключить определенные продукты. Для этого выполните действия по установке Office с помощью средства развертывания Office, но при этом включите элемент ExcludeApp в файл конфигурации. Например, в этом файле конфигурации устанавливаются все приложения Microsoft 365 для корпоративных продуктов за исключением издателя:
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[Общие сведения о средстве развертывания Office](https://docs.microsoft.com/deployoffice/overview-office-deployment-tool)
  


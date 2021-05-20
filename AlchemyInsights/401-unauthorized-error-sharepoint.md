---
title: Ошибка "401 Не авторизовано" в SharePoint
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/14/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "10935"
- "9001435"
ms.openlocfilehash: ac2fe27a8e7b277bfaf18303bf5b792410a1ea6a
ms.sourcegitcommit: f4866e94918c7b591ad0cd3b58169d340bcc7f00
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 05/19/2021
ms.locfileid: "52539945"
---
# <a name="401-unauthorized-error-in-sharepoint"></a><span data-ttu-id="5fd29-102">Ошибка "401 Не авторизовано" в SharePoint</span><span class="sxs-lookup"><span data-stu-id="5fd29-102">401 Unauthorized error in SharePoint</span></span>

<span data-ttu-id="5fd29-p101">Если вы получаете сообщение об ошибке "(401) Не авторизовано" в SharePoint, эта ошибка может быть связана с упразднением TLS 1.0/1.1. Дополнительные сведения см. в:</span><span class="sxs-lookup"><span data-stu-id="5fd29-p101">If you receive the error "(401) Unauthorized" in SharePoint it might be related to the deprecation of TLS 1.0/1.1. For more info, see:</span></span>

- [<span data-ttu-id="5fd29-105">Подготовка к TLS 1.2 в Office 365 и Office 365 GCC</span><span class="sxs-lookup"><span data-stu-id="5fd29-105">Preparing for TLS 1.2 in Office 365 and Office 365 GCC</span></span>](/microsoft-365/compliance/prepare-tls-1.2-in-office-365)

- [<span data-ttu-id="5fd29-106">Возникновение ошибок проверки подлинности, если у клиента нет поддержки TLS 1.2</span><span class="sxs-lookup"><span data-stu-id="5fd29-106">Authentication errors occur if client doesn't have TLS 1.2 support</span></span>](/sharepoint/troubleshoot/administration/authentication-errors-tls12-support)

- [<span data-ttu-id="5fd29-107">Обновление для включения TLS 1.1 и TLS 1.2 в качестве стандартных протоколов защиты в WinHTTP в Windows</span><span class="sxs-lookup"><span data-stu-id="5fd29-107">Update to enable TLS 1.1 and TLS 1.2 as default secure protocols in WinHTTP in Windows</span></span>](https://support.microsoft.com/topic/update-to-enable-tls-1-1-and-tls-1-2-as-default-secure-protocols-in-winhttp-in-windows-c4bd73d2-31d7-761e-0178-11268bb10392)

<span data-ttu-id="5fd29-108">Если пользователи используют Windows 7, убедитесь, что они проверяют [комплекты шифров TLS в Windows 7](/windows/win32/secauthn/tls-cipher-suites-in-windows-7).</span><span class="sxs-lookup"><span data-stu-id="5fd29-108">If users are on Windows 7, make sure they check [TLS Cipher Suites in Windows 7](/windows/win32/secauthn/tls-cipher-suites-in-windows-7).</span></span>
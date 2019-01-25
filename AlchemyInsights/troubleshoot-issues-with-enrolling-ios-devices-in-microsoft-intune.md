---
title: Устранение неполадок с Регистрация устройств операций ввода-вывода в Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: d717bcc9-1cc1-44f6-b5e6-c1bc059c1973
ms.openlocfilehash: 663ff9b101494be781095ca550a4ed3deedca175
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/24/2019
ms.locfileid: "29486787"
---
# <a name="troubleshoot-issues-with-enrolling-ios-devices-in-microsoft-intune"></a><span data-ttu-id="e61bf-102">Устранение неполадок с Регистрация устройств операций ввода-вывода в Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="e61bf-102">Troubleshoot issues with enrolling iOS devices in Microsoft Intune</span></span>

<span data-ttu-id="e61bf-103">Просмотрите ресурсы, перечисленные ниже, чтобы устранить проблему сейчас.</span><span class="sxs-lookup"><span data-stu-id="e61bf-103">Review the resources listed below to resolve your issue now.</span></span> 
  
<span data-ttu-id="e61bf-104">Некоторые распространенные сообщения об ошибках и инструкции по устранению неполадок:</span><span class="sxs-lookup"><span data-stu-id="e61bf-104">Some common error messages and resolution steps:</span></span>
  
- <span data-ttu-id="e61bf-p101">**Ограничение устройства связаться с вами** У пользователя есть несколько устройств, участвуют превышает ограничение устройства. Просмотрите эти документы, чтобы [Удалить устройство](https://docs.microsoft.com/en-us/intune/devices-wipe) или [Изменение ограничения устройства](https://docs.microsoft.com/en-us/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span><span class="sxs-lookup"><span data-stu-id="e61bf-p101">**Device Cap Reached** The user has more devices enrolled than the device limit. Review these documents to [remove a device](https://docs.microsoft.com/en-us/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/en-us/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>
    
- <span data-ttu-id="e61bf-p102">Эта служба **не поддерживается. Политика не регистрации:** службы Push-уведомления Apple (APNS) необходимо настроить или обновленной панели мониторинга. Просмотрите [Этот документ](https://docs.microsoft.com/en-us/intune/apple-mdm-push-certificate-get) для получения инструкций по как это сделать.</span><span class="sxs-lookup"><span data-stu-id="e61bf-p102">**This Service is not supported. No Enrollment Policy:** Apple Push Notification Service (APNS) needs to be configured or renewed. Review [this document](https://docs.microsoft.com/en-us/intune/apple-mdm-push-certificate-get) for instructions on how to do that.</span></span> 
    
- <span data-ttu-id="e61bf-p103">**Недопустимый тип лицензии пользователя или имя пользователя не распознается:** Пользователю необходимо назначить Intune или Командной лицензии. Просмотрите эти документы назначение лицензии через: [Центр администрирования Office](https://docs.microsoft.com/en-us/intune/licenses-assign) или [Azure портала](https://docs.microsoft.com/en-us/azure/active-directory/license-users-groups).</span><span class="sxs-lookup"><span data-stu-id="e61bf-p103">**User License Type Invalid or User Name Not Recognized:** The user needs to be assigned an Intune or EMS license. Review these documents to assign a license through: [Office Admin Center](https://docs.microsoft.com/en-us/intune/licenses-assign) or [Azure portal](https://docs.microsoft.com/en-us/azure/active-directory/license-users-groups).</span></span>
    
<span data-ttu-id="e61bf-111">Дополнительные ресурсы, которые помогут устранить проблему:</span><span class="sxs-lookup"><span data-stu-id="e61bf-111">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="e61bf-p104">[Устранение неполадок в портал Intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) используйте для диагностики и устранения распространенных ошибок регистрации. Просмотрите [Этот документ](https://docs.microsoft.com/en-us/intune/help-desk-operators) для получения дополнительных сведений.</span><span class="sxs-lookup"><span data-stu-id="e61bf-p104">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures. Review [this document](https://docs.microsoft.com/en-us/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="e61bf-114">Просмотрите эти документы, список распространенные ошибки, которые препятствуют регистрации и решения в каждое: [руководство по Устранение неполадок](https://support.microsoft.com/en-us/help/4039809/troubleshooting-ios-device-enrollment-in-intune) и [Устранение неполадок doc](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="e61bf-114">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/en-us/help/4039809/troubleshooting-ios-device-enrollment-in-intune) and [Troubleshooting doc](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>
    
3. <span data-ttu-id="e61bf-115">[Узнайте, как возможность зачисления устройств операций ввода-вывода в Microsoft Intune](https://docs.microsoft.com/en-us/intune/ios-enroll).</span><span class="sxs-lookup"><span data-stu-id="e61bf-115">[Learn how to enroll iOS devices in Microsoft Intune](https://docs.microsoft.com/en-us/intune/ios-enroll).</span></span>
    


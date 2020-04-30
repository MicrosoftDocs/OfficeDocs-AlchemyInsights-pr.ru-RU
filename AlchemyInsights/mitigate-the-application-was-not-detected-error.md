---
title: Устранение ошибки "Приложение не обнаружено"
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000171"
- "1712"
ms.openlocfilehash: e07c6b128a39f1fb1c998d051aafe72205d8cbee
ms.sourcegitcommit: 82155846ce771c18050e6113d6c199b34a1504ff
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/24/2020
ms.locfileid: "43810496"
---
# <a name="mitigate-the-application-was-not-detected-error"></a><span data-ttu-id="62951-102">Устранение ошибки "Приложение не обнаружено"</span><span class="sxs-lookup"><span data-stu-id="62951-102">Mitigate "The application was not detected" error</span></span>

<span data-ttu-id="62951-103">Ошибка установки приложения "Приложение не обнаружено после успешной установки", получаемая от Intune, может возникать на всех основных платформах ОС (Windows, iOS и Android).</span><span class="sxs-lookup"><span data-stu-id="62951-103">The app installation error, “The application was not detected after installation completed successfully,” reported by Intune, may occur on all major OS platforms (Windows, iOS and Android).</span></span>

<span data-ttu-id="62951-104">Наиболее распространенные сценарии возникновения этой ошибки:</span><span class="sxs-lookup"><span data-stu-id="62951-104">The most common scenarios that generate this error include:</span></span>

- <span data-ttu-id="62951-105">Приложение обновлено за пределами Intune (из стороннего магазина приложений) после первоначального развертывания.</span><span class="sxs-lookup"><span data-stu-id="62951-105">The app has been updated outside of Intune (from a third-party app store) after the initial deployment.</span></span> <span data-ttu-id="62951-106">Например, некоторые приложения, такие как Google Chrome, могут выполнять автоматическое обновление.</span><span class="sxs-lookup"><span data-stu-id="62951-106">For example some applications such as Google Chrome may perform auto updates.</span></span>
- <span data-ttu-id="62951-107">Пользователь удалил приложение после первоначальной установки.</span><span class="sxs-lookup"><span data-stu-id="62951-107">A user has uninstalled the app after the initial install.</span></span>

<span data-ttu-id="62951-108">Чтобы устранить эту проблему, сначала проверьте затронутые устройства, чтобы определить сценарий возникновения ошибки.</span><span class="sxs-lookup"><span data-stu-id="62951-108">To mitigate this issue, first perform a review of the affected devices to determine the scenario in which the error occurs.</span></span>

- <span data-ttu-id="62951-109">Если приложение обновлено за пределами Intune, развертывание приложения можно настроить на игнорирование версии приложения.</span><span class="sxs-lookup"><span data-stu-id="62951-109">If the app has been updated outside of Intune, the app deployment can be set to ignore the application version.</span></span> <span data-ttu-id="62951-110">Для этого в разделе **Конфигурация приложений > Сведения о приложении** присвойте параметру **Игнорировать версию приложения** значение **Да**.</span><span class="sxs-lookup"><span data-stu-id="62951-110">To do so, under **App Configuration > App Information**, set **Ignore App** version to **Yes**.</span></span>
- <span data-ttu-id="62951-111">Если целью является клиент, может быть уместно развертывание приложения в качестве "обязательного" с обеспечением развертывания последней версии.</span><span class="sxs-lookup"><span data-stu-id="62951-111">When targeting the client, it may be appropriate to deploy the application as “required,” and to ensure that the latest version is deployed.</span></span>
- <span data-ttu-id="62951-112">Кроме того, на платформе iOS можно использовать функцию **автоматического обновления** с помощью программы корпоративных закупок Apple, которую можно настроить на автоматическое обновление до новых версий приложений по мере их появления.</span><span class="sxs-lookup"><span data-stu-id="62951-112">Alternatively, on the iOS platform, it is possible to use the **autoupdate** functionality associated with the Apple Volume Purchase Program, which can be configured to automatically update to new application versions as they become available.</span></span>

<span data-ttu-id="62951-113">Дополнительные сведения об устранении проблем с установкой приложений см. в статье [Устранение проблем с установкой приложений](https://docs.microsoft.com/intune/troubleshoot-app-install).</span><span class="sxs-lookup"><span data-stu-id="62951-113">For more information about troubleshooting app installation issues, please see [Troubleshoot app installation issues](https://docs.microsoft.com/intune/troubleshoot-app-install).</span></span>
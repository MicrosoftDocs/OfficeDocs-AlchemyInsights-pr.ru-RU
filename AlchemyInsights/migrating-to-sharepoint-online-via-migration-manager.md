---
title: Переход на SharePoint Online с помощью диспетчера переноса данных
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 686e8f18-b871-4dd2-864f-8562947ab583
ms.collection: Adm_O365
ms.custom:
- "5300030"
- "3192"
ms.openlocfilehash: 5aebf7903670e74f616c8f151749d760caf1d642
ms.sourcegitcommit: b0d5b68366028abcf08610672d5bc9d3b25ac433
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 03/24/2020
ms.locfileid: "42932191"
---
# <a name="migrating-to-sharepoint-online-via-migration-manager"></a><span data-ttu-id="e067c-102">Переход на SharePoint Online с помощью диспетчера переноса данных</span><span class="sxs-lookup"><span data-stu-id="e067c-102">Migrating to SharePoint Online via Migration Manager</span></span>

<span data-ttu-id="e067c-103">**Важно!** Многие клиенты SharePoint Online и OneDrive с помощью службы запускают критически важные для бизнеса приложения, которые выполняются в фоновом режиме.</span><span class="sxs-lookup"><span data-stu-id="e067c-103">**Important**: Many SharePoint Online and OneDrive customers run business-critical applications against the service that run in the background.</span></span> <span data-ttu-id="e067c-104">В их число входят перенос контента, защита от потери данных и решения для резервного копирования.</span><span class="sxs-lookup"><span data-stu-id="e067c-104">These include content migration, Data Loss Prevention (DLP), and backup solutions.</span></span> <span data-ttu-id="e067c-105">В это беспрецедентное время мы работаем над тем, чтобы службы SharePoint Online и OneDrive оставались высокодоступными и надежными для пользователей, которые зависят от них более, чем когда-либо, в связи с удаленной работой.</span><span class="sxs-lookup"><span data-stu-id="e067c-105">During these unprecedented times, we are taking steps to ensure that SharePoint Online and OneDrive services remain highly available and reliable for your users who depend on the service more than ever in remote work scenarios.</span></span>

<span data-ttu-id="e067c-106">Для этого мы установили более жесткие ограничения регулирования для фоновых приложений (миграция, защита от потери данных и решения для резервного копирования) в рабочие дни в дневное время.</span><span class="sxs-lookup"><span data-stu-id="e067c-106">In support of this objective, we have implemented tighter throttling limits on background apps (migration, DLP and backup solutions) during weekday daytime hours.</span></span> <span data-ttu-id="e067c-107">Ожидается, что теперь пропускная способность этих приложений будет очень ограничена.</span><span class="sxs-lookup"><span data-stu-id="e067c-107">You should expect that these apps will achieve very limited throughput during these times.</span></span> <span data-ttu-id="e067c-108">Однако в вечернее время и на выходных (для данного региона) служба будет готова обработать значительно больший объем запросов от фоновых приложений.</span><span class="sxs-lookup"><span data-stu-id="e067c-108">However, during evening and weekend hours for the region, the service will be ready to process a significantly higher volume of requests from background apps.</span></span>

<span data-ttu-id="e067c-109">**Диспетчер переноса данных**</span><span class="sxs-lookup"><span data-stu-id="e067c-109">**Migration Manager**</span></span>

<span data-ttu-id="e067c-110">Диспетчер переноса данных, расположенный в современном Центре администрирования SharePoint, помогает настраивать клиенты и создавать задачи.</span><span class="sxs-lookup"><span data-stu-id="e067c-110">Located in the modern SharePoint Admin Center, the Migration Manager guides you through the setup of your clients and the creation of your tasks.</span></span> <span data-ttu-id="e067c-111">Можно настраивать параметры как на глобальном уровне, так и на уровне задач, просматривать ход выполнения всех задач, скачивать сводные отчеты и отчеты на уровне задач.</span><span class="sxs-lookup"><span data-stu-id="e067c-111">You can specify global or task-level settings, view all-up task progress, and download aggregated summary and task-level reports.</span></span>

- [<span data-ttu-id="e067c-112">Начало работы с диспетчером переноса данных</span><span class="sxs-lookup"><span data-stu-id="e067c-112">Get started with the Migration Manager</span></span>](https://docs.microsoft.com/sharepointmigration/mm-get-started)

- [<span data-ttu-id="e067c-113">Настройка клиентов диспетчера переноса данных</span><span class="sxs-lookup"><span data-stu-id="e067c-113">Setup Migration Manager clients</span></span>](https://docs.microsoft.com/sharepointmigration/mm-setup-clients)

- [<span data-ttu-id="e067c-114">Параметры диспетчера переноса данных</span><span class="sxs-lookup"><span data-stu-id="e067c-114">Migration Manager Settings</span></span>](https://docs.microsoft.com/sharepointmigration/mm-settings)

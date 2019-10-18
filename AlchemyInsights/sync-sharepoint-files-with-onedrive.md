---
title: Устранение проблем команды "Открыть в проводнике" в SharePoint Online
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 8/7/19
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 5ad2f1f2-9650-4eb0-b4fa-2f52a09f535a
ms.openlocfilehash: 73583b3b27143c708a4cc993cdff94a33131ab52
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/04/2019
ms.locfileid: "36743106"
---
# <a name="troubleshoot-open-with-explorer-issues-in-sharepoint-online"></a><span data-ttu-id="641b3-102">Устранение проблем команды "Открыть в проводнике" в SharePoint Online</span><span class="sxs-lookup"><span data-stu-id="641b3-102">Troubleshoot “Open with Explorer” issues in SharePoint Online</span></span>

<span data-ttu-id="641b3-103">Команда "Открыть в проводнике" открывает локальный экземпляр проводника Windows, отображающий структуру папок на сервере, содержащем сайт SharePoint.</span><span class="sxs-lookup"><span data-stu-id="641b3-103">The Open with Explorer command opens a local instance of Windows Explorer that displays the folder structure on the server that hosts the SharePoint site.</span></span> <span data-ttu-id="641b3-104">С учетом этого рекомендуется [синхронизировать файлы SharePoint с помощью нового клиента синхронизации OneDrive](https://support.office.com/article/sync-sharepoint-files-with-the-new-onedrive-sync-client-6de9ede8-5b6e-4503-80b2-6190f3354a88)</a>, поддерживающего функцию [Файлы по запросу](https://support.office.com/article/learn-about-onedrive-files-on-demand-0e6860d3-d9f3-4971-b321-7092438fb38e), так как он обеспечивает локальный доступ к файлам и наилучшую производительность.</span><span class="sxs-lookup"><span data-stu-id="641b3-104">This being said, we recommend [syncing SharePoint files with the new OneDrive sync client](https://support.office.com/article/sync-sharepoint-files-with-the-new-onedrive-sync-client-6de9ede8-5b6e-4503-80b2-6190f3354a88)</a> which provides [Files On-Demand](https://support.office.com/article/learn-about-onedrive-files-on-demand-0e6860d3-d9f3-4971-b321-7092438fb38e) because it provides local access to your files and offers the best performance.</span></span>


<span data-ttu-id="641b3-105">Если вместо нового клиента синхронизации OneDrive вы решите использовать представление проводника, следуйте инструкциям и рекомендациям, изложенным в приведенных ниже статьях:</span><span class="sxs-lookup"><span data-stu-id="641b3-105">If you chose to use Explorer view instead of using the new OneDrive sync client, make sure you follow the steps and best practices in the following articles:</span></span>

- [<span data-ttu-id="641b3-106">Как устранять неполадки в SharePoint Online с помощью команды "Открыть в проводнике"</span><span class="sxs-lookup"><span data-stu-id="641b3-106">How to use the "Open with Explorer" command to troubleshoot issues in SharePoint Online</span></span>](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/troubleshoot-issues-using-open-with-explorer)

- [<span data-ttu-id="641b3-107">Копирование и перемещение файлов библиотеки с помощью команды "Открыть в проводнике"</span><span class="sxs-lookup"><span data-stu-id="641b3-107">Copy or move library files by using Open with Explorer</span></span>](https://support.office.com/article/copy-or-move-library-files-by-using-open-with-explorer-aaee7bfb-e2a1-42ee-8fc0-bcc0754f04d2)

> [!Note]  
> <span data-ttu-id="641b3-108">Кнопка **Открыть в проводнике** не отображается в новом интерфейсе библиотеки.</span><span class="sxs-lookup"><span data-stu-id="641b3-108">The **Open with Explorer** button doesn't appear in the new library experience.</span></span> <span data-ttu-id="641b3-109">Выберите раскрывающийся список **Вид** справа вверху (имя списка может меняться в зависимости от текущего представления), а затем выберите команду **Просмотреть в проводнике**.</span><span class="sxs-lookup"><span data-stu-id="641b3-109">Select the **View** drop-down in the upper right (the name of the drop-down changes depending on your current view), and then select **View in File Explorer**.</span></span>
>
 ><span data-ttu-id="641b3-110">Команда "Открыть в проводнике" для SharePoint использует элементы ActiveX, поэтому поддерживается только в Internet Explorer 10 или 11.</span><span class="sxs-lookup"><span data-stu-id="641b3-110">SharePoint Open with Explorer uses ActiveX controls, so it's only supported in Internet Explorer 10 or 11.</span></span> <span data-ttu-id="641b3-111">Она не работает в Windows с браузером Microsoft Edge, Google Chrome, Mozilla Firefox или на платформе Mac.</span><span class="sxs-lookup"><span data-stu-id="641b3-111">Open with Explorer doesn't work in Windows with Microsoft Edge, Google Chrome, Mozilla Firefox, or on the Mac platform.</span></span> <span data-ttu-id="641b3-112">По этой причине возможность просмотра в проводнике может быть недоступна.</span><span class="sxs-lookup"><span data-stu-id="641b3-112">Due to this reason, the Explorer View option may be grayed out.</span></span>
>
> - <span data-ttu-id="641b3-113">[Почему кнопки на ленте SharePoint недоступны или неактивны?](https://support.office.com/article/Why-SharePoint-ribbon-buttons-are-unavailable-48b0939a-2efb-4e79-b5e8-b2c4cb5d04ca)</span><span class="sxs-lookup"><span data-stu-id="641b3-113">[Why SharePoint ribbon buttons are unavailable or grayed out](https://support.office.com/article/Why-SharePoint-ribbon-buttons-are-unavailable-48b0939a-2efb-4e79-b5e8-b2c4cb5d04ca).</span></span>
  


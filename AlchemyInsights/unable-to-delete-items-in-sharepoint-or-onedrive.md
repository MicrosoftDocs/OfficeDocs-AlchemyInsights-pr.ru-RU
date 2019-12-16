---
title: Не удается удалить элементы в SharePoint или OneDrive
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: cc19fcb6603160032dac52b1ec9e194a90b7891f
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 12/15/2019
ms.locfileid: "40049530"
---
# <a name="unable-to-delete-items"></a><span data-ttu-id="344b8-102">Не удается удалить элементы</span><span class="sxs-lookup"><span data-stu-id="344b8-102">Unable to delete items</span></span>

<span data-ttu-id="344b8-103">Возникли проблемы с удалением элементов SharePoint?</span><span class="sxs-lookup"><span data-stu-id="344b8-103">Having issues deleting SharePoint items?</span></span>

- <span data-ttu-id="344b8-104">Всегда убедитесь, что у вас есть [соответствующие разрешения](https://docs.microsoft.com/sharepoint/default-sharepoint-groups) на удаление элемента или если [администратор семейства веб-сайтов](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) попытался удалить элемент.</span><span class="sxs-lookup"><span data-stu-id="344b8-104">Always make sure you have the [appropriate permissions](https://docs.microsoft.com/sharepoint/default-sharepoint-groups) to delete the item or have a [site collection administrator](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) attempt remove the item.</span></span>

- <span data-ttu-id="344b8-105">Убедитесь, что для элемента отсутствует настройка [политики хранения](https://docs.microsoft.com/office365/securitycompliance/retention-policies) .</span><span class="sxs-lookup"><span data-stu-id="344b8-105">Ensure that there is not a [retention policy](https://docs.microsoft.com/office365/securitycompliance/retention-policies) setup on the item.</span></span>

- <span data-ttu-id="344b8-106">Убедитесь, что элемент не [извлечен](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) другим пользователем.</span><span class="sxs-lookup"><span data-stu-id="344b8-106">Ensure the item is not [checked out](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) to another user.</span></span>

- <span data-ttu-id="344b8-107">Наконец, администраторы могут использовать [шаблоны и методики SharePoint](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) , которые содержат библиотеку команд PowerShell, которые позволяют выполнять сложные действия управления, такие как принудительное удаление элементов стубборн.</span><span class="sxs-lookup"><span data-stu-id="344b8-107">Finally, administrators can use [SharePoint Patterns and Practices](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) which contains a library of PowerShell commands that allow you to perform complex management actions such as force deleting stubborn items.</span></span>
- [<span data-ttu-id="344b8-108">Удаление PNP файла</span><span class="sxs-lookup"><span data-stu-id="344b8-108">Remove PNP File</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [<span data-ttu-id="344b8-109">Удаление папки PNP</span><span class="sxs-lookup"><span data-stu-id="344b8-109">Remove PNP Folder</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [<span data-ttu-id="344b8-110">Удаление элемента списка PNP</span><span class="sxs-lookup"><span data-stu-id="344b8-110">Remove PNP List Item</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [<span data-ttu-id="344b8-111">Удаление списка PNP</span><span class="sxs-lookup"><span data-stu-id="344b8-111">Remove PNP List</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [<span data-ttu-id="344b8-112">Удаление поля PNP (столбец)</span><span class="sxs-lookup"><span data-stu-id="344b8-112">Remove PNP Field (Column)</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)
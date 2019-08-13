---
title: Рабочий процесс не запускается
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 8/2/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000144"
- "1670"
ms.openlocfilehash: a3bac74c19a77b7703f948c1d8b6bcd182e9b075
ms.sourcegitcommit: 631e527967f4d641bc9227642ffe38967ae87a00
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 08/09/2019
ms.locfileid: "36270793"
---
# <a name="workflow-is-not-starting"></a>Рабочий процесс не запускается

- Рабочие процессы SharePoint 2010 и SharePoint 2013 не запускаются.

    - Если рабочий процесс не запускается, возможна временная ошибка службы, из-за которой пользователи могут столкнуться с периодическими задержками, связанными с ходом выполнения рабочего процесса. Просмотрите [панель мониторинга работоспособности службы](https:/admin.microsoft.com/AdminPortal/Home#/servicehealth) , чтобы проверить, влияет ли ваша организация на работу.

    - Если вы пропустили эту ошибку более 24 часов, запишите запрос в службу поддержки. Во многих случаях мы уже работаем над решением. Отправьте нам по крайней мере 24 часа для завершения решения.

- Рабочие процессы SharePoint 2010, задержанные при запуске.

    - Это происходит, если рабочий процесс запускается в больших пакетах. (например, при одновременном добавлении нескольких элементов).

    - Рабочие процессы не предназначены для работы в режиме реального времени, поэтому задержка связана с поведением по проектированию.

   -  Если рабочий процесс является сложным языковым языком разметки объектов (КСМОЛ), компиляция может выполняться медленно. Обратитесь к [этой](https://support.microsoft.com/en-us/kb/3043697) статье.

    - Необходимо упростить рабочий процесс или изменить его с помощью типа платформы рабочих процессов Microsoft SharePoint 2013.

    - Если размер журнала рабочего процесса увеличился, можно удалить элементы или создать новый список журналов.

        Дополнительные сведения: [Очистка журнала рабочих процессов](https://blogs.technet.microsoft.com/marj/2015/08/07/sharepoint-2010-workflows-best-practice-purge-workflow-history-list-items/)


## <a name="related-topics"></a>Статьи по теме
Хотите попробовать Microsoft Flow в SharePoint Online?
- [Создание последовательности](https://support.office.com/article/Create-a-flow-for-a-list-or-library-in-SharePoint-Online-or-OneDrive-for-Business-a9c3e03b-0654-46af-a254-20252e580d01) 
- [SharePoint и Flow](https://flow.microsoft.com/blog/sharepoint-and-flow/) 


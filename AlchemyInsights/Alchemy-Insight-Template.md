---
title: то же самое, что и filename
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: 113d01e0fc92cc9845e585919ab05f386d6892bb
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/14/2020
ms.locfileid: "47664147"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a>"Обязательный заголовок Алчеми H1, H2's не работает".
Рекомендации и рекомендации по разработке Алчеми:

1. **Не публикуйте алчеми Insights в папках**, так как это приведет к нарушению структуры URL-адресов. Мы хотим устранить эту ошибку.
1. Файлы в папке **алчеминсигхтс** должны содержать имена файлов с символами нижнего регистра с дефисами для пробелов ex. ***Практическое руководство — удержание***.
    1. Включите идентификатор правила или идентификатор контейнера из [портала партнеров алчеми](https://alchemyportal.azurewebsites.net) в поле MS. Custom. Пример. ***MS. Custom: 100021***
1. Используйте остальные метаданные вверху этого файла в качестве шаблона.
1. На [портале партнера алчеми](https://alchemyportal.azurewebsites.net)перейдите к разделу **Application Insight Title (заголовок клиента** ) и используйте его в качестве отправной точки для получения информации о должности H1. 
    > [!NOTE]
    > В верхней части алчеми Insights должен быть только один элемент H1, или они будут прерываться в рабочей среде. H2S не отображаются, поэтому для обозначения отдельных разделов используйте **полужирное начертание** или другие условные обозначения.
1. Затем заполните основной текст, используя черновик материала в разделе "сведения о клиентах" страницы правила Алчеми
    1. Маркированные списки прекрасно отличаются
    1. Слишком нумерованные списки
    1. **Полужирный** и *курсив* — это хорошо
    1. Ссылки всегда должны быть ссылками **на веб-/Екстернал** или **глубокими ссылками на элементы пользовательского интерфейса**, а не внутренними ссылками.
    1. На данный момент фотографии не поддерживаются официально, но они включены в схему.

И это уже слишком большая длина. Рекомендация: около 400 символов---------------------------------

Когда контент будет готов, изтяните его в ветвь Live. Затем перейдите на [портал партнера алчеми](https://alchemyportal.azurewebsites.net) и введите имя файла в поле URL-адрес. 
---
title: инструкции по импорту – NK2 — файлы
ms.author: daeite
author: daeite
manager: joallard
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1800027"
- "1267"
ms.assetid: ''
ms.openlocfilehash: 6a823f6e0c4c46de64dd7b70fb40c76255d78ec1
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/15/2020
ms.locfileid: "47780072"
---
# <a name="how-to-import-nk2-files"></a>Импорт NK2 файлов 

При первом запуске Microsoft Outlook 2013, Outlook 2016, Outlook 2019 или Outlook для Microsoft 365 ваш кэш псевдонимов (хранящийся в файле *имя_профиля*. nk2) импортируется в скрытое сообщение в хранилище сообщений по умолчанию.

Чтобы импортировать файлы с расширением NK2 в Outlook 2013, Outlook 2016, Outlook 2019 или Outlook для Microsoft 365, убедитесь, что NK2-файл находится в следующей папке:%Аппдата%\микрософт\аутлук

**Note**: NK2 файл должен иметь то же имя, что и текущий профиль Outlook 2013 или Outlook 2016. По умолчанию используется имя профиля "Outlook". Чтобы проверить имя профиля, выполните указанные ниже действия. 
1. Нажмите кнопку **Пуск** и выберите **Панель управления**.
2. Дважды щелкните элемент **почта**.
3. В диалоговом окне Настройка почты выберите пункт **Показать профили**.
4. Нажмите кнопку **начать**  >  **выполнение**.
5. В поле **Открыть** введите *outlook.exe/importnk2*, а затем нажмите кнопку **ОК**. 

После импорта NK2 файла содержимое файла объединяется с существующим кэшем псевдонимов, хранящимся в вашем почтовом ящике.

**Note**: NK2-файл переименовывается с использованием старого расширения имени файла при следующем запуске Outlook 2013, Outlook 2016, Outlook 2019 или Outlook для Microsoft 365. Если требуется повторно импортировать файл с расширением. nk2, сначала удалите старое расширение имени файла.

Дополнительные сведения можно найти [в статье импорт или копирование списка автозавершения на другой компьютер](https://support.microsoft.com/help/2806550/how-to-import-nk2-files-into-outlook%).
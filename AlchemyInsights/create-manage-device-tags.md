---
title: Создание тегов или групп устройств и управление ими
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 06/01/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "11446"
- "9003537"
ms.openlocfilehash: 3a7d53beaaf830055904f0634f09a3e9e447006e
ms.sourcegitcommit: 1226e9a9601dc8fc8ec427235f3c2dd88ff84ced
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 06/02/2021
ms.locfileid: "52721731"
---
# <a name="create-and-manage-device-tags-or-groups"></a>Создание тегов или групп устройств и управление ими

Добавьте теги на устройства, чтобы создать логическую группу. Теги устройств поддерживают правильное сопоставление сети, позволяя вам присоединять различные теги для захвата контекста и включения динамического создания списков в рамках инцидента. Теги можно использовать в качестве фильтра в представлении списка устройств или для группировки устройств. Дополнительные сведения о группировке устройств см. в статье [Создание тегов устройств и управление ими](/microsoft-365/security/defender-endpoint/machine-tags).

Добавлять теги на устройства, можно с помощью следующего:

- Использование портала

- Настройка значения раздела реестра
 
**Примечание.** Между добавлением тега на устройство, и его доступностью в списке устройств, а также на странице устройства может быть задержка.

Чтобы добавить теги устройств с помощью API, см. [API добавления и удаления тегов устройств](/microsoft-365/security/defender-endpoint/add-or-remove-machine-tags).

## <a name="add-and-manage-device-tags-using-the-portal"></a>Добавление тегов устройств и управление ими с помощью портала

1. Выберите устройство, для которого вы хотите настроить теги. Можно выбрать устройство или найти его в любом из следующих представлений:

    - **Панель мониторинга операций обеспечения безопасности** Выберите имя устройства из раздела "Устройства с активными оповещениями".
    - **Очередь оповещений** – Выберите имя устройства рядом со значком устройства из очереди оповещений.
    - **Список устройств** – Выберите имя устройства из списка устройств.
    - **Поле поиска** – Выберите устройство из раскрывающегося меню и введите имя устройства.

    Вы также можете попасть на страницу оповещений с помощью представления файлов и IP-адресов.

1. Выберите **Управление тегами** в строке действий ответа.

1. Начните ввод для поиска или создания тегов.

Теги добавляются в представление устройства и отражаются в представлении списка устройств. Затем можно использовать фильтр тегов, чтобы увидеть соответствующий список устройств.

Дополнительные сведения см. в статье [Создание тегов устройств и управление ими](/microsoft-365/security/defender-endpoint/machine-tags).
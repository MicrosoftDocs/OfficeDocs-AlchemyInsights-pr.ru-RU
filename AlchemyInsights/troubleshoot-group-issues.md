---
title: Устранение проблем с группой
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 01/15/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "7814"
- "9004358"
ms.openlocfilehash: 7e2957a27305e8fb0bfd10e21189cef9870c5aaa
ms.sourcegitcommit: 6d02eb533fd74199af6b20f714b3720991da2c4a
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 01/18/2021
ms.locfileid: "50716115"
---
# <a name="troubleshoot-group-issues"></a><span data-ttu-id="ebe3d-102">Устранение проблем с группой</span><span class="sxs-lookup"><span data-stu-id="ebe3d-102">Troubleshoot group issues</span></span>

<span data-ttu-id="ebe3d-103">**Назначение группы роли Azure AD**</span><span class="sxs-lookup"><span data-stu-id="ebe3d-103">**I need to assign a group to an Azure AD role**</span></span>

<span data-ttu-id="ebe3d-104">Чтобы назначить группу Azure Active Directory (AD) роли Azure AD, выполните следующие действия:</span><span class="sxs-lookup"><span data-stu-id="ebe3d-104">To assign an Azure Active Directory (AD) group to an Azure AD role, perform the following steps:</span></span>

1. <span data-ttu-id="ebe3d-105">Создание группы. Чтобы создать группу:</span><span class="sxs-lookup"><span data-stu-id="ebe3d-105">Create a new group - To create a new group:</span></span>

    <span data-ttu-id="ebe3d-106">а.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-106">a.</span></span> <span data-ttu-id="ebe3d-107">Войдите в Центр администрирования Azure AD с разрешениями администратора привилегированных ролей или глобального администратора.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-107">Sign in to the Azure AD admin center with privileged role administrator or global administrator permissions.</span></span> 
    <span data-ttu-id="ebe3d-108">б.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-108">b.</span></span> <span data-ttu-id="ebe3d-109">Выберите Azure Active Directory > Группы > Все группы > Создать группу.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-109">Select Azure Active Directory > Groups > All groups > New group.</span></span> 
    <span data-ttu-id="ebe3d-110">в.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-110">c.</span></span> <span data-ttu-id="ebe3d-111">Создайте группу.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-111">Create the group.</span></span>

2. <span data-ttu-id="ebe3d-112">Назначьте группе роль во время создания группы или после ее создания.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-112">Assign the role to the group either during group creation or after the group is created.</span></span>

    <span data-ttu-id="ebe3d-113">а.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-113">a.</span></span> <span data-ttu-id="ebe3d-114">Чтобы назначить роль во время создания группы, включите переключатель Возможность назначения группе ролей Azure AD и создайте группу.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-114">To assign a role to the group at the time of group creation, switch on the toggle Azure AD roles can be assigned to the group and create the group.</span></span>
    <span data-ttu-id="ebe3d-115">б.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-115">b.</span></span> <span data-ttu-id="ebe3d-116">Чтобы назначить роль после создания группы, перейдите на вкладку Назначенные роли созданной группы и назначьте ей роль.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-116">To assign a role to the group after it has been created, navigate to the Assigned roles tab for the newly created group, and assign the role to the group.</span></span>

<span data-ttu-id="ebe3d-117">**Управление участием в группе, которой назначена роль Azure AD**</span><span class="sxs-lookup"><span data-stu-id="ebe3d-117">**I need to manage membership of a group that is assigned to Azure AD role**</span></span>

1. <span data-ttu-id="ebe3d-118">Чтобы не допустить повышения привилегий, по умолчанию только администраторы привилегированных ролей и глобальные администраторы могут изменять участников группы, которой назначена роль.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-118">To prevent elevation of privileges, by default, only privileged role administrator and global administrator can modify the membership of a group that is assigned to a role.</span></span> <span data-ttu-id="ebe3d-119">Тем не менее, они могут назначить владельца для такой группы и делегировать эту задачу.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-119">They can, however, choose to assign an owner for such a group and delegate this task.</span></span> <span data-ttu-id="ebe3d-120">Дополнительные сведения см. в статье [Использование облачных групп для управления назначением ролей в службе Azure Active Directory](https://docs.microsoft.com/azure/active-directory/roles/groups-concept).</span><span class="sxs-lookup"><span data-stu-id="ebe3d-120">For more information see, [Use cloud groups to manage role assignments in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/roles/groups-concept).</span></span>
2. <span data-ttu-id="ebe3d-121">Часто задаваемые вопросы и советы по устранению неполадок при назначении ролей группам в Azure AD см. в статье [Устранение неполадок ролей, назначенных облачным группам.](https://docs.microsoft.com/azure/active-directory/roles/groups-faq-troubleshooting).</span><span class="sxs-lookup"><span data-stu-id="ebe3d-121">For common questions and troubleshooting tips for assigning roles to groups in Azure AD, see [Troubleshooting roles assigned to cloud groups](https://docs.microsoft.com/azure/active-directory/roles/groups-faq-troubleshooting).</span></span>

<span data-ttu-id="ebe3d-122">**Динамические группы**</span><span class="sxs-lookup"><span data-stu-id="ebe3d-122">**Dynamic groups**</span></span>

1. <span data-ttu-id="ebe3d-123">Если встроенные атрибуты пользователя не удается найти, убедитесь, что атрибут находится в списке поддерживаемых свойств.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-123">If you cannot find the built-in user attributes, ensure that the attribute is in the list of supported properties.</span></span>
2. <span data-ttu-id="ebe3d-124">Если вы ищете встроенные атрибуты устройства, убедитесь, что атрибут находится в списке атрибутов устройства</span><span class="sxs-lookup"><span data-stu-id="ebe3d-124">If you are looking for built-in device attributes, ensure that the attribute is in the list of device attributes</span></span> 
3. <span data-ttu-id="ebe3d-125">В дополнение к встроенным атрибутам пользователя и устройства можно также использовать [атрибуты расширения](https://docs.microsoft.com/azure/active-directory/enterprise-users/groups-dynamic-membership#extension-properties-and-custom-extension-properties).</span><span class="sxs-lookup"><span data-stu-id="ebe3d-125">In addition to the built-in user and device attributes, you could also use [Extension Attributes](https://docs.microsoft.com/azure/active-directory/enterprise-users/groups-dynamic-membership#extension-properties-and-custom-extension-properties).</span></span> <span data-ttu-id="ebe3d-126">После синхронизации атрибутов расширения из локальной версии Windows Server AD или из подключенного приложения SaaS атрибуты должны быть видны в раскрывающемся списке построителя правил.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-126">After syncing extension attributes from on-premises Windows Server AD or from a connected SaaS application, the attributes should be visible in the drop-down list of the rule builder.</span></span> <span data-ttu-id="ebe3d-127">Имя настраиваемого атрибута можно найти в каталоге, запросив атрибут пользователя с помощью PowerShell и выполнив поиск имени атрибута.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-127">The custom attribute name can be found in the directory by querying a user's attribute using PowerShell and searching for the attribute name.</span></span> <span data-ttu-id="ebe3d-128">Их также можно использовать при построении правил в синтаксисе правил.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-128">These could also be used when constructing rules in the rule syntax.</span></span>
4. <span data-ttu-id="ebe3d-129">Убедитесь, что у вашего клиента есть соответствующая лицензия.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-129">Ensure that your tenant has the appropriate license.</span></span> <span data-ttu-id="ebe3d-130">Для динамических групп требуется наличие у клиента лицензии Azure AD P1 Premium.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-130">Dynamic groups require the tenant to have an Azure AD P1 Premium license.</span></span> <span data-ttu-id="ebe3d-131">Список планов лицензирования Azure AD можно найти [здесь](https://azure.microsoft.com/pricing/details/active-directory/).</span><span class="sxs-lookup"><span data-stu-id="ebe3d-131">The list of Azure AD license plans can be accessed [here](https://azure.microsoft.com/pricing/details/active-directory/).</span></span> <span data-ttu-id="ebe3d-132">Планы лицензирования Enterprise Mobility + Security доступны [здесь](https://www.microsoft.com/microsoft-365/enterprise-mobility-security/compare-plans-and-pricing).</span><span class="sxs-lookup"><span data-stu-id="ebe3d-132">Enterprise Mobility + Security licensing plans can be accessed [here](https://www.microsoft.com/microsoft-365/enterprise-mobility-security/compare-plans-and-pricing).</span></span>
5. <span data-ttu-id="ebe3d-133">Убедитесь, что ролью пользователя, который создает динамическую группу, является глобальный администратор, администратор Intune, администратор группы или администратор пользователя.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-133">Ensure that the role of the user creating the dynamic group is a global administrator, intune administrator, group administrator, or a user administrator.</span></span>
6. <span data-ttu-id="ebe3d-134">Подождите, пока группа будет заполнена.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-134">Please allow time for the group to populate.</span></span> <span data-ttu-id="ebe3d-135">В зависимости от размера клиента, для заполнения группы в первый раз или после изменения правила может потребоваться до 24 часов.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-135">Depending on the size of your tenant, the group may take up to 24 hours for populating for the first time or after a rule change.</span></span>
7. <span data-ttu-id="ebe3d-136">Дополнительные сведения см. в статье [Создание правил на основе атрибутов для членства в динамической группе](https://docs.microsoft.com/azure/active-directory/enterprise-users/groups-dynamic-membership).</span><span class="sxs-lookup"><span data-stu-id="ebe3d-136">For more information, see [Create attribute-based rules for dynamic group membership](https://docs.microsoft.com/azure/active-directory/enterprise-users/groups-dynamic-membership).</span></span>

<span data-ttu-id="ebe3d-137">**Удаление группы**</span><span class="sxs-lookup"><span data-stu-id="ebe3d-137">**I need to delete a group**</span></span>

1. <span data-ttu-id="ebe3d-138">Группы можно удалить из каталога с помощью командлета Remove-AzureADGroup в модуле Azure AD Powershell.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-138">Groups can be deleted from the directory using the Remove-AzureADGroup cmdlet in the Azure AD Powershell module.</span></span>
2. <span data-ttu-id="ebe3d-139">Перед удалением синхронизированной группы в Azure AD удалите все назначенные лицензии, чтобы избежать ошибок.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-139">Before attempting to delete a synced group in Azure AD, ensure you have deleted all assigned licenses  to avoid errors.</span></span>
3. <span data-ttu-id="ebe3d-140">Дополнительные сведения об удалении групп см. в статье [Удаление группы с назначенной лицензией](https://docs.microsoft.com/azure/active-directory/enterprise-users/licensing-group-advanced#deleting-a-group-with-an-assigned-license).</span><span class="sxs-lookup"><span data-stu-id="ebe3d-140">For more information on deleting groups, see [Deleting a group with an assigned license](https://docs.microsoft.com/azure/active-directory/enterprise-users/licensing-group-advanced#deleting-a-group-with-an-assigned-license).</span></span>

<span data-ttu-id="ebe3d-141">**Восстановление удаленной группы**</span><span class="sxs-lookup"><span data-stu-id="ebe3d-141">**I need to restore a deleted group**</span></span>

1. <span data-ttu-id="ebe3d-142">При удалении группы Office 365 ее можно восстановить только за 30 дней до того, как произойдет окончательное удаление.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-142">If an Office 365 group is deleted, it can only be restored up to 30 days before permanent deletion occurs.</span></span> <span data-ttu-id="ebe3d-143">После окончательного удаления группу нельзя будет восстановить.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-143">Once permanently deleted, the group can no longer be restored.</span></span> <span data-ttu-id="ebe3d-144">Дополнительные сведения о восстановлении групп см. [здесь](https://docs.microsoft.com/azure/active-directory/enterprise-users/groups-restore-deleted).</span><span class="sxs-lookup"><span data-stu-id="ebe3d-144">Learn more about restoring groups [here](https://docs.microsoft.com/azure/active-directory/enterprise-users/groups-restore-deleted).</span></span>
2. <span data-ttu-id="ebe3d-145">Эта функция не поддерживается для групп безопасности и групп рассылки.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-145">This functionality is not supported for security groups and distribution groups.</span></span>
3. <span data-ttu-id="ebe3d-146">Убедитесь, что у вас есть права на восстановление группы Office 365.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-146">Ensure you are authorized to restore an Office 365 group.</span></span> <span data-ttu-id="ebe3d-147">Глобальные администраторы, администраторы групп, администраторы учетных записей пользователей, администраторы службы Intune, поддержка партнеров уровня 1 или 2 и владелец группы могут восстановить группу.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-147">Global administrators, group administrators, user account administrators, intune service administrators, partner tier1 or tier2 support, and the owner of the group can be able to restore a group.</span></span>
4. <span data-ttu-id="ebe3d-148">При удалении и восстановлении динамической группы она рассматривается как новая группа и повторно заполняется в соответствии с правилом.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-148">When a dynamic group is deleted and restored, it is seen as a new group and re-populated according to the rule.</span></span> <span data-ttu-id="ebe3d-149">Этот процесс может занять до 24 часов.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-149">This process might take up to 24 hours.</span></span>
5. <span data-ttu-id="ebe3d-150">Дополнительные сведения о восстановлении удаленной группы см. в статье [Восстановление удаленной группы Office 365 в Azure Active Directory](https://docs.microsoft.com/azure/active-directory/enterprise-users/groups-restore-deleted).</span><span class="sxs-lookup"><span data-stu-id="ebe3d-150">For more information on restoring a deleted group, see [Restore a deleted Office 365 group in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/enterprise-users/groups-restore-deleted).</span></span>

<span data-ttu-id="ebe3d-151">**Настройка политики срока действия группы**</span><span class="sxs-lookup"><span data-stu-id="ebe3d-151">**Group expiration policy configuration**</span></span>

1. <span data-ttu-id="ebe3d-152">Эта функция поддерживается только для групп Office 365, но не для групп безопасности и групп рассылки.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-152">This functionality is only supported for Office 365 groups, and not for security groups and distribution groups are not supported.</span></span>
2. <span data-ttu-id="ebe3d-153">Для настройки и использования политики срока действия групп Office 365 требуется лицензия Azure AD Premium.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-153">Configuring and using the expiration policy for Office 365 groups requires an Azure AD Premium license.</span></span>
3. <span data-ttu-id="ebe3d-154">В настоящее время для групп Office 365 в клиенте можно настроить только одну политику срока действия.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-154">Currently, only one expiration policy can be configured for Office 365 groups on a tenant.</span></span>
4. <span data-ttu-id="ebe3d-155">Только глобальные администраторы, администраторы групп, администраторы пользователей и владелец группы могут обновлять группу.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-155">Only Global administrators, group administrators, user administrators, and the owner of the group can be able to renew a group.</span></span>
5. <span data-ttu-id="ebe3d-156">Если срок действия группы Office 365 истек, она удаляется и может быть восстановлена только за 30 дней до того, как произойдет окончательное удаление.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-156">If an Office 365 group is expired, it is deleted and can only be restored up to 30 days before permanent deletion occurs.</span></span> <span data-ttu-id="ebe3d-157">После окончательного удаления группу нельзя будет восстановить.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-157">Once permanently deleted, the group can no longer be restored.</span></span> <span data-ttu-id="ebe3d-158">Дополнительные сведения о восстановлении групп см. [здесь](https://docs.microsoft.com/azure/active-directory/enterprise-users/groups-restore-deleted).</span><span class="sxs-lookup"><span data-stu-id="ebe3d-158">Learn more about restoring groups [here](https://docs.microsoft.com/azure/active-directory/enterprise-users/groups-restore-deleted).</span></span>

<span data-ttu-id="ebe3d-159">**Автоматическое продление на основе действий**</span><span class="sxs-lookup"><span data-stu-id="ebe3d-159">**Activity-based automatic renewal**</span></span>

<span data-ttu-id="ebe3d-160">Действия пользователей в SharePoint, Outlook и Teams могут запускать автоматическое обновление группы.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-160">User activities from SharePoint, Outlook and Teams can trigger group automatic renewal.</span></span> <span data-ttu-id="ebe3d-161">Действия проверяются за 35 дней до истечения срока действия группы.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-161">Activities are checked at 35 days before a group expires.</span></span> <span data-ttu-id="ebe3d-162">Если в течение срока действия группы есть действия, группа будет автоматически обновлена, а уведомление по электронной почте не будет отправлено владельцам группы.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-162">If there is activity during the current group lifecycle, the group will be automatically renewed and email notification won't be sent out to group owners.</span></span>

<span data-ttu-id="ebe3d-163">**Время уведомления для групп с истекшим сроком действия**</span><span class="sxs-lookup"><span data-stu-id="ebe3d-163">**Notification timing for expired groups**</span></span>

1. <span data-ttu-id="ebe3d-164">Уведомления по электронной почте отправляются владельцам группы Office 365 за 30, 15 и 1 день до истечения срока действия группы.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-164">Email notifications are sent to the Office 365 group owners 30 days, 15 days, and 1 day prior to expiration of the group.</span></span>
2. <span data-ttu-id="ebe3d-165">При первой настройке срока действия для всех групп, которые старше этого интервала, устанавливаются 35 дней до окончания срока действия.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-165">When you first set up expiration, any groups that are older than the expiration interval are set to 35 days until expiration.</span></span>
3. <span data-ttu-id="ebe3d-166">Дата истечения срока действия группы рассчитывается на основе даты обновления группы, а не на основе даты обновления политики.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-166">Group expiration date is calculated based on the group’s renewal date, not based on the policy updated date.</span></span> <span data-ttu-id="ebe3d-167">Если политика срока действия обновлена, дата окончания срока действия не изменится.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-167">If the expiration policy is updated, the expiration date will not change.</span></span>
4. <span data-ttu-id="ebe3d-168">Дополнительные сведения см. в статье [Политика срока действия группы и сообщения электронной почты о продление](https://docs.microsoft.com/azure/active-directory/enterprise-users/groups-lifecycle) и [Восстановление удаленной группы Office 365 в Azure Active Directory](https://docs.microsoft.com/azure/active-directory/enterprise-users/groups-restore-deleted).</span><span class="sxs-lookup"><span data-stu-id="ebe3d-168">For more information see, [Group Expiration policy and renewal emails](https://docs.microsoft.com/azure/active-directory/enterprise-users/groups-lifecycle) and [Restore a deleted Office 365 group in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/enterprise-users/groups-restore-deleted).</span></span>

<span data-ttu-id="ebe3d-169">**Разрешение на создание группы**</span><span class="sxs-lookup"><span data-stu-id="ebe3d-169">**Permission to create a group**</span></span>

<span data-ttu-id="ebe3d-170">Убедитесь, что у вас есть разрешение на создание новой группы.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-170">Ensure that you are authorized to create a new group.</span></span> <span data-ttu-id="ebe3d-171">Глобальные администраторы могут отключить создание групп на портале Azure или панели доступа.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-171">Global administrators can disable group creation in the Azure portal or Access Panel.</span></span> <span data-ttu-id="ebe3d-172">Может потребоваться администратор для создания новой группы или для получения соответствующих разрешений.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-172">You may need an administrator to create the new group for you, or to give you appropriate permissions.</span></span>

1. [<span data-ttu-id="ebe3d-173">Создание группы и добавление участников на портале Azure</span><span class="sxs-lookup"><span data-stu-id="ebe3d-173">Create a new group and add members in Azure portal</span></span>](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-groups-create-azure-portal)
2. [<span data-ttu-id="ebe3d-174">Создание групп в Powershell MSOnline</span><span class="sxs-lookup"><span data-stu-id="ebe3d-174">Create groups in Powershell MSOnline</span></span>](https://docs.microsoft.com/azure/active-directory/enterprise-users/groups-settings-v2-cmdlets#create-groups)
3. [<span data-ttu-id="ebe3d-175">Отключение создания групп в Powershell</span><span class="sxs-lookup"><span data-stu-id="ebe3d-175">Disable groups creation in Powershell</span></span>](https://docs.microsoft.com/azure/active-directory/enterprise-users/groups-settings-v2-cmdlets#disable-group-creation-by-your-users) 
4. [<span data-ttu-id="ebe3d-176">Управление разрешениями пользователей на создание групп Office 365</span><span class="sxs-lookup"><span data-stu-id="ebe3d-176">Manage who can create groups in Office 365</span></span>](https://docs.microsoft.com/microsoft-365/solutions/manage-creation-of-groups) 
5. [<span data-ttu-id="ebe3d-177">Отключение уведомления о приветствии Office 365 с помощью Powershell</span><span class="sxs-lookup"><span data-stu-id="ebe3d-177">Disable Office 365 welcome notification via Powershell</span></span>](https://docs.microsoft.com/powershell/module/exchange/set-unifiedgroup)
6. [<span data-ttu-id="ebe3d-178">Административные роли Azure AD</span><span class="sxs-lookup"><span data-stu-id="ebe3d-178">Azure AD administrative roles</span></span>](https://docs.microsoft.com/azure/active-directory/roles/permissions-reference)

<span data-ttu-id="ebe3d-179">**Управление разрешениями на создание групп**</span><span class="sxs-lookup"><span data-stu-id="ebe3d-179">**Manage Group creation permissions**</span></span>

1. <span data-ttu-id="ebe3d-180">Глобальные администраторы могут управлять разрешениями на создание групп для безопасности или группами Office 365, созданными на портале Azure или панели доступа, путем настройки параметров **Пользователи могут создавать группы безопасности на порталах Azure** или **Пользователи могут создавать группы Office 365 на порталах Azure** в разделе **Все группы > Общие (параметры)**.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-180">Global administrators can manage group creation permissions for security or Office 365 groups created in the Azure portal or Access Panel, by setting **Users can create security groups in Azure portals** or **Users can create Office 365 groups in Azure portals** settings in **All groups > General (Settings)**.</span></span>
2. <span data-ttu-id="ebe3d-181">Вы также можете ограничить создание групп, чтобы выбрать группу пользователей, если у вас есть лицензия Azure AD P1 Premium.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-181">You can also restrict group creation to select a group of users if you have an Azure AD P1 Premium license.</span></span>

<span data-ttu-id="ebe3d-182">**Отключение уведомления о приветствий для новых участников группы Office 365**</span><span class="sxs-lookup"><span data-stu-id="ebe3d-182">**Disabling welcome notification for new members of an Office 365 group**</span></span>

<span data-ttu-id="ebe3d-183">Приветствие, отправленное пользователям, добавленным в группы Office 365, можно отключить, установив для параметра `UnifiedGroupWelcomeMessageEnabled` значение **False** в Powershell.</span><span class="sxs-lookup"><span data-stu-id="ebe3d-183">The welcome notification sent to users who are added to Office 365 groups can be disabled by setting `UnifiedGroupWelcomeMessageEnabled` to **False** in Powershell.</span></span> <span data-ttu-id="ebe3d-184">Подробные сведения об этом параметре см. [здесь](https://docs.microsoft.com/powershell/module/exchange/set-unifiedgroup).</span><span class="sxs-lookup"><span data-stu-id="ebe3d-184">Learn about this setting [here](https://docs.microsoft.com/powershell/module/exchange/set-unifiedgroup).</span></span>













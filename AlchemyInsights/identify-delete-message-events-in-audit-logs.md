---
title: Identifier les événements de suppression de messages dans les journaux d'audit
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1370
ms.assetid: ''
ms.openlocfilehash: 93f8a192af6e689e2b2d04013f35b8da2b69e607
ms.sourcegitcommit: ffe2f489b1ac3aae62aa784c959da6a41c3261eb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/17/2019
ms.locfileid: "31909221"
---
# <a name="audit-logs-for-deleted-email-messages"></a><span data-ttu-id="76b7e-102">Journaux d'audit pour les messages électroniques supprimés</span><span class="sxs-lookup"><span data-stu-id="76b7e-102">Audit logs for deleted email messages</span></span>

<span data-ttu-id="76b7e-103">À compter du 1er janvier 2019, Microsoft Active la journalisation d'audit des boîtes aux lettres par défaut.</span><span class="sxs-lookup"><span data-stu-id="76b7e-103">Starting in January 2019, Microsoft is turning on mailbox audit logging by default.</span></span> <span data-ttu-id="76b7e-104">Dans le cas contraire, pour examiner les événements de suppression de message pour un utilisateur spécifique, vous devez activer manuellement les actions de suppression pour l'audit.</span><span class="sxs-lookup"><span data-stu-id="76b7e-104">Otherwise, to review delete message events for a specific user, you need to manually enable the delete actions for auditing.</span></span> <span data-ttu-id="76b7e-105">Si la journalisation d'audit des boîtes aux lettres est déjà activée pour votre organisation ou pour un utilisateur spécifique, suivez les étapes ci-dessous.</span><span class="sxs-lookup"><span data-stu-id="76b7e-105">If mailbox audit logging is already enabled for your organization or for the specific user, follow the steps below.</span></span>

1. <span data-ttu-id="76b7e-106">Connectez-vous au [Centre de sécurité & de sécurité Office 365](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="76b7e-106">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="76b7e-107">Cliquez sur **recherche et enquête** , puis sélectionnez **recherche du journal d'audit**.</span><span class="sxs-lookup"><span data-stu-id="76b7e-107">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

3. <span data-ttu-id="76b7e-108">Sélectionnez la plage de dates dans les champs **Date de début** et **Date de fin** .</span><span class="sxs-lookup"><span data-stu-id="76b7e-108">Select the date range in the **Start date** and **End date** fields.</span></span> <span data-ttu-id="76b7e-109">Spécifiez le nom d'utilisateur de l'utilisateur que vous souhaitez examiner (l'utilisateur qui a supprimé les éléments).</span><span class="sxs-lookup"><span data-stu-id="76b7e-109">Specify username for the user that you want to investigate (the user who deleted the items).</span></span> <span data-ttu-id="76b7e-110">Dans le champ **activités** , sélectionnez **messages supprimés du dossier éléments supprimés** et **messages déplacés dans le dossier éléments supprimés**.</span><span class="sxs-lookup"><span data-stu-id="76b7e-110">In the **Activities** field, select **Deleted messages from Deleted Items folder** and **Moved messages to Deleted Items folder**.</span></span>

4. <span data-ttu-id="76b7e-111">Cliquez sur **Rechercher**.</span><span class="sxs-lookup"><span data-stu-id="76b7e-111">Click **Search**.</span></span>

<span data-ttu-id="76b7e-112">Dans les résultats, sélectionnez un enregistrement d'audit.</span><span class="sxs-lookup"><span data-stu-id="76b7e-112">In the results, select an audit record.</span></span> <span data-ttu-id="76b7e-113">Dans la fenêtre mobile des détails, cliquez sur **informations supplémentaires**.</span><span class="sxs-lookup"><span data-stu-id="76b7e-113">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="76b7e-114">Des informations supplémentaires sur l'élément supprimé (par exemple, la ligne d'objet et l'emplacement de l'élément lors de sa suppression) s'affichent dans le champ **AffectedItems** .</span><span class="sxs-lookup"><span data-stu-id="76b7e-114">Additional information about the deleted item (for example, the subject line and the location of the item when it was deleted) is displayed in the **AffectedItems** field.</span></span> <span data-ttu-id="76b7e-115">La propriété **ClientInfoString** indique si la suppression s'est produite dans Outlook, Outlook sur le Web (anciennement appelé Outlook Web App) ou un autre appareil.</span><span class="sxs-lookup"><span data-stu-id="76b7e-115">The **ClientInfoString** property will show if the deletion occurred in Outlook, Outlook on the web (formerly known as Outlook Web App), or any other device.</span></span>

<span data-ttu-id="76b7e-116">Pour plus d'informations, consultez [la rubrique Détermination de la personne qui a configuré le transfert du courrier pour une boîte aux lettres](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).</span><span class="sxs-lookup"><span data-stu-id="76b7e-116">For more information, see [Determining who set up email forwarding for a mailbox](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).</span></span>

<span data-ttu-id="76b7e-117">**Remarque**: vous ne pouvez pas récupérer les éléments supprimés à l'aide de la fonctionnalité de journal d'audit.</span><span class="sxs-lookup"><span data-stu-id="76b7e-117">**Note**: You can't retrieve deleted items using the audit log feature.</span></span> <span data-ttu-id="76b7e-118">Pour récupérer des messages supprimés dans Outlook sur le Web, consultez la rubrique [récupérer des éléments supprimés dans Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).</span><span class="sxs-lookup"><span data-stu-id="76b7e-118">To retrieve deleted messages in Outlook on the web, see [Recover deleted items in Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).</span></span>
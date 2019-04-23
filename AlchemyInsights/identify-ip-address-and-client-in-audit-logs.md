---
title: Identification de l'adresse IP et du client dans les journaux d'audit
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1367
ms.assetid: ''
ms.openlocfilehash: 7e30a638de5926aa11b8ae637613a48076d7bdc9
ms.sourcegitcommit: ffe2f489b1ac3aae62aa784c959da6a41c3261eb
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/17/2019
ms.locfileid: "31909223"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a><span data-ttu-id="359c5-102">Identification de l'adresse IP et du client dans les journaux d'audit</span><span class="sxs-lookup"><span data-stu-id="359c5-102">Identify IP address and client in audit logs</span></span>

<span data-ttu-id="359c5-103">L'adresse IP correspondant à une activité par un utilisateur ou un administrateur est affichée dans les journaux d'audit.</span><span class="sxs-lookup"><span data-stu-id="359c5-103">The IP address that corresponds to an activity by a user or administrator is shown in the Audit Logs.</span></span> <span data-ttu-id="359c5-104">Les informations sur le client sont également consignées.</span><span class="sxs-lookup"><span data-stu-id="359c5-104">The client information is also logged.</span></span> <span data-ttu-id="359c5-105">Voici les étapes à suivre pour identifier ces informations</span><span class="sxs-lookup"><span data-stu-id="359c5-105">Here are the steps to identifying such information</span></span>

1. <span data-ttu-id="359c5-106">Connectez-vous au [Centre de sécurité & de sécurité Office 365](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="359c5-106">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="359c5-107">Cliquez sur **recherche et enquête** , puis sélectionnez **recherche du journal d'audit**.</span><span class="sxs-lookup"><span data-stu-id="359c5-107">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

   <span data-ttu-id="359c5-108">Si vous êtes intéressé par une activité spécifique, sélectionnez-la dans la liste **activités** .</span><span class="sxs-lookup"><span data-stu-id="359c5-108">If you're interested in a specific activity, select it from **Activities** list.</span></span> <span data-ttu-id="359c5-109">Si ce n'est pas le cas, toutes les activités seront retournées pour l'utilisateur sélectionné (paramètre par défaut).</span><span class="sxs-lookup"><span data-stu-id="359c5-109">If not, all activities will be returned for the selected user (default setting).</span></span>

   <span data-ttu-id="359c5-110">**Remarque**: certaines activités ne sont pas disponibles dans le menu **activités** ; Toutefois, ces éléments d'audit seront renvoyés si l'option **afficher les résultats de toutes les activités** est sélectionnée (paramètre par défaut).</span><span class="sxs-lookup"><span data-stu-id="359c5-110">**Note**: Certain activities may not be available in the **Activities** menu; however, those audit items will be returned if **Show Results for all activities** is selected (default setting).</span></span>

3. <span data-ttu-id="359c5-111">Spécifiez le nom d'utilisateur dans le champ **utilisateurs** , sélectionnez la plage de dates appropriée pour l'activité, puis cliquez sur **Rechercher**.</span><span class="sxs-lookup"><span data-stu-id="359c5-111">Specify the username in the **Users** field, select the appropriate date range for the activity, and then click **Search**.</span></span>

<span data-ttu-id="359c5-112">Dans les résultats, vous pouvez voir l'adresse IP de cette activité dans le volet de résultats.</span><span class="sxs-lookup"><span data-stu-id="359c5-112">In the results, you can see the IP address for that activity in the results pane.</span></span> <span data-ttu-id="359c5-113">Sélectionnez l'enregistrement d'audit pour afficher des informations détaillées dans la fenêtre mobile des **Détails** (par exemple, le client, l'utilisateur qui a effectué l'action, etc.).</span><span class="sxs-lookup"><span data-stu-id="359c5-113">Select the audit record to see detailed information in the **Details** flyout (for example, Client, User that performed action, etc.).</span></span>

<span data-ttu-id="359c5-114">Pour plus d'informations, consultez [la rubrique recherche de l'adresse IP de l'ordinateur utilisé pour accéder à un compte compromis](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span><span class="sxs-lookup"><span data-stu-id="359c5-114">For more information, see [Finding the IP address of the computer used to access a compromised account](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span></span>
---
title: Onedrive entreprise Web OneDrive redirige vers Delve
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1870"
- "900072"
ms.openlocfilehash: 8ba296c6986c767939ef51076551f95719d11aa2
ms.sourcegitcommit: a65d196d00adb70045af5caca9828fe44b951f61
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/04/2019
ms.locfileid: "36752246"
---
# <a name="redirected-to-delve-after-you-click-onedrive"></a><span data-ttu-id="dc287-102">Redirigé vers Delve après avoir cliqué sur OneDrive</span><span class="sxs-lookup"><span data-stu-id="dc287-102">Redirected to Delve after you click OneDrive</span></span>

<span data-ttu-id="dc287-103">Pour résoudre ce problème, l’administrateur Office 365 doit accorder aux utilisateurs le droit de créer leur site mes sites.</span><span class="sxs-lookup"><span data-stu-id="dc287-103">To resolve this problem, the Office 365 administrator must grant users the right to create their My Sites site.</span></span> <span data-ttu-id="dc287-104">Cela est dû au fait que la page OneDrive entreprise est créée sur les sites mon site.</span><span class="sxs-lookup"><span data-stu-id="dc287-104">This is because the OneDrive for Business page is created on My Sites.</span></span>

<span data-ttu-id="dc287-105">Pour accorder ce droit, procédez comme suit :</span><span class="sxs-lookup"><span data-stu-id="dc287-105">To grant this right, follow these steps:</span></span>

1. <span data-ttu-id="dc287-106">Dans le centre d’administration SharePoint, cliquez sur **profils utilisateur**.</span><span class="sxs-lookup"><span data-stu-id="dc287-106">In the SharePoint admin center,click **user profiles**.</span></span>

2. <span data-ttu-id="dc287-107">Dans la section **personnes** , cliquez sur **gérer les autorisations des utilisateurs**.</span><span class="sxs-lookup"><span data-stu-id="dc287-107">In the **People** section, click **Manage User Permissions**.</span></span>

3. <span data-ttu-id="dc287-108">Ajoutez des utilisateurs qui requièrent des autorisations pour créer leur site mes sites.</span><span class="sxs-lookup"><span data-stu-id="dc287-108">Add users who require permissions to create their My Sites site.</span></span> <span data-ttu-id="dc287-109">Par défaut, ce paramètre est défini sur **tout le monde sauf les utilisateurs externes**.</span><span class="sxs-lookup"><span data-stu-id="dc287-109">By default, this setting is set to **Everyone except external users**.</span></span>

4. <span data-ttu-id="dc287-110">Une fois que vous avez ajouté l’utilisateur, les utilisateurs ou le groupe, vérifiez que l’utilisateur, les utilisateurs ou le groupe ajouté est sélectionné, faites défiler jusqu’à la section **autorisations** , puis activez la case à cocher en regard de **créer un site personnel (requis pour le stockage personnel, les flux d’actualités et suivi du contenu)**.</span><span class="sxs-lookup"><span data-stu-id="dc287-110">After you have added the user, users, or group, make sure that the added user, users, or group is selected, scroll to the **permissions** section, and then select the check box next to **Create Personal Site (required for personal storage, newsfeed, and followed content)**.</span></span>

5. <span data-ttu-id="dc287-111">Cliquez sur **OK**, puis demandez à l’utilisateur d’accéder à la page OneDrive pour créer le site.</span><span class="sxs-lookup"><span data-stu-id="dc287-111">Click **OK**, and then have the user browse to the OneDrive page to create the site.</span></span>
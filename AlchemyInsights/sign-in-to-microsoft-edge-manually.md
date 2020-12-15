---
title: Se connecter à Microsoft Edge manuellement
ms.author: v-smandalika
author: v-smandalika
ms.date: 12/03/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 686e8f18-b871-4dd2-864f-8562947ab583
ms.collection: Adm_O365
ms.custom:
- "9003844"
- "6893"
ms.openlocfilehash: c5d71c26ba3584f8ce496a28587fe75cae2d344f
ms.sourcegitcommit: 94036315916fbc79dca2a692c2e9bc1139dd28f6
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 12/08/2020
ms.locfileid: "49599476"
---
# <a name="sign-in-to-microsoft-edge-manually"></a><span data-ttu-id="e03ee-102">Se connecter à Microsoft Edge manuellement</span><span class="sxs-lookup"><span data-stu-id="e03ee-102">Sign in to Microsoft Edge manually</span></span>

<span data-ttu-id="e03ee-103">Si un utilisateur n’est pas connecté automatiquement pendant une première exécution, il peut se connecter manuellement par le biais des paramètres du navigateur ou de la fenêtre mobile d’identité.</span><span class="sxs-lookup"><span data-stu-id="e03ee-103">If a user isn't automatically signed in during a first-run experience, the user can manually sign in through the browser's settings or the identity flyout.</span></span> <span data-ttu-id="e03ee-104">Pour gérer la connexion, utilisez les stratégies suivantes :</span><span class="sxs-lookup"><span data-stu-id="e03ee-104">To manage sign-in, use the following policies:</span></span>

1. <span data-ttu-id="e03ee-105">[NonRemovableProfileEnabled](https://docs.microsoft.com/deployedge/microsoft-edge-policies#nonremovableprofileenabled) : permet de s’assurer qu’un utilisateur dispose toujours d’un profil de travail dans Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="e03ee-105">[NonRemovableProfileEnabled](https://docs.microsoft.com/deployedge/microsoft-edge-policies#nonremovableprofileenabled) - To ensure that a user always has a work profile in Microsoft Edge.</span></span>
2. <span data-ttu-id="e03ee-106">[RestrictSigninToPattern](https://docs.microsoft.com/deployedge/microsoft-edge-policies#restrictsignintopattern) -permet de limiter la connexion à un ensemble de comptes approuvés.</span><span class="sxs-lookup"><span data-stu-id="e03ee-106">[RestrictSigninToPattern](https://docs.microsoft.com/deployedge/microsoft-edge-policies#restrictsignintopattern) - To restrict sign-in to a set of trusted accounts.</span></span>
3. <span data-ttu-id="e03ee-107">[BrowserSignin](https://docs.microsoft.com/deployedge/microsoft-edge-policies#browsersignin) : pour désactiver la connexion ou pour obliger les utilisateurs à se connecter.</span><span class="sxs-lookup"><span data-stu-id="e03ee-107">[BrowserSignin](https://docs.microsoft.com/deployedge/microsoft-edge-policies#browsersignin) - To disable sign-in or to force users to sign in.</span></span>

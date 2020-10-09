---
title: Envoyer en tant que dossier public à extension messagerie dans EXO
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1956"
- "3500007"
ms.openlocfilehash: 0765262c04571e7df139de993611fd6e67068c54
ms.sourcegitcommit: 45635cc7a6c36d6c7b5f78215ad32f2aa7e3aed0
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 10/08/2020
ms.locfileid: "48394687"
---
# <a name="sendas-mail-enabled-public-folder"></a><span data-ttu-id="93a84-102">Dossier public envoyer en tant que courrier électronique</span><span class="sxs-lookup"><span data-stu-id="93a84-102">SendAs Mail Enabled Public Folder</span></span>

<span data-ttu-id="93a84-103">L’exemple suivant affecte des autorisations « Envoyer en tant que » pour le dossier public à extension messagerie NewPF1 à l’utilisateur Jason.</span><span class="sxs-lookup"><span data-stu-id="93a84-103">The following example assigns "Send As" permissions for the mail-enabled public folder NewPF1 to the user Jason.</span></span>

<span data-ttu-id="93a84-104">Add-RecipientPermission-Identity’NewPF1 '-Trustee "Jason"-AccessRights’SendAs'</span><span class="sxs-lookup"><span data-stu-id="93a84-104">Add-RecipientPermission -Identity 'NewPF1' -Trustee "Jason" -AccessRights 'SendAs'</span></span>

<span data-ttu-id="93a84-105">Pour obtenir des informations détaillées sur la syntaxe et les paramètres, consultez la rubrique [attribuer des autorisations « Envoyer en tant que » ou « envoyer de la part de » pour les dossiers publics à extension messagerie](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/assign-permissions-mail-enabled-pfs).</span><span class="sxs-lookup"><span data-stu-id="93a84-105">For detailed syntax and parameter information see [Assign "Send As" or "Send on Behalf" permissions for mail-enabled public folders](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/assign-permissions-mail-enabled-pfs).</span></span>
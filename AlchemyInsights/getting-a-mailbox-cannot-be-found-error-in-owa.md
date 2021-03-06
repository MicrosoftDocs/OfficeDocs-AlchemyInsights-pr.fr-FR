---
title: 126 Erreur d’obtention d’une boîte aux lettres dans OWA ?
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "126"
- "1600020"
ms.assetid: e85bffec-e5ad-418a-8561-dab6257e1864
ms.openlocfilehash: 6bab821aaa3b50c365ef5d25a61bca195c76d7ce
ms.sourcegitcommit: e552d65aac79433a911723412bf1252d20d3f0da
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/30/2021
ms.locfileid: "51426660"
---
# <a name="getting-a-mailbox-not-found-error-in-outlook-on-the-web"></a>Erreur d’obtention d’une boîte aux lettres in trouvée dans Outlook sur le web ?

Si vous utilisez Outlook sur le web  et que vous obtenez une boîte aux lettres indessable pour erreur, le compte que vous avez utilisé pour vous connecter à Outlook sur le web n’a pas de licence Exchange Online et, par conséquent, aucune boîte aux lettres n’est associée au compte. Votre administrateur peut attribuer une licence à votre compte en suivant les étapes suivantes :

1. Ouvrez le Centre d’administration Microsoft  [365](https://portal.office.com/adminportal/home#/homepage) et sélectionnez Utilisateurs actifs sous la **section** Utilisateurs, puis sélectionnez l’utilisateur qui voit l’erreur.

2. Dans la page utilisateur qui s’ouvre, allez à la  section **Licences** et applications, sélectionnez la valeur d’emplacement appropriée et attribuez une licence qui contient Exchange Online (développez la licence pour en voir les détails). Lorsque vous avez terminé, cliquez sur **Enregistrer les modifications**.

Dans certains cas, si la licence est déjà attribuée à un compte d’utilisateur, la suppression et la réaffectation de la licence permettent de résoudre le problème et de l’obtenir correctement mis en service dans le système : 

- Vérifiez si vos abonnements Exchange Online M365 (et d’autres, si vous en avez) sont à jour et n’ont pas expiré récemment.

Une fois que vous vous êtes assuré que votre abonnement n’a pas expiré et qu’une licence valide a été attribuée au compte d’utilisateur, la mise en service de la licence peut prendre jusqu’à 24 heures, ce qui vous permet d’attendre la résolution de votre problème. Pour plus d’informations, voir [Attribuer et gérer des licences.](https://docs.microsoft.com/deployoffice/overview-licensing-activation-microsoft-365-apps#assign-and-manage-licenses)
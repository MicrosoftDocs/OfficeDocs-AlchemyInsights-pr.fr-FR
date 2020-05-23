---
title: Résoudre l’erreur de connexion Teams AADSTS9000411
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9000744"
- "5689"
ms.openlocfilehash: b70f1320ea1dfa29e6fa489bd02acfcd1d92971b
ms.sourcegitcommit: 88d2918aa51f4ba10771527380c3e0db0f5a9147
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 05/20/2020
ms.locfileid: "44328785"
---
# <a name="addressing-teams-sign-in-error-aadsts9000411"></a>Résoudre l’erreur de connexion Teams AADSTS9000411

Lorsque vous vous connectez à Microsoft Teams, le message d’erreur suivant peut s’afficher : **Désolé... Nous rencontrons des difficultés pour vous connecter à AADSTS9000411 : la demande n’est pas correctement mise en forme. Le paramètre « login_hint » est dupliqué.**

Pour résoudre ce problème, assurez-vous que vos clients Microsoft Teams sont mis à jour. Pour plus d’informations sur la mise à jour de votre client, voir [Mettre à jour Microsoft Teams](https://support.office.com/article/Update-Microsoft-Teams-535a8e4b-45f0-4f6c-8b3d-91bca7a51db1).

Si vous ne pouvez pas mettre à jour votre client pour une raison quelconque, la déconnexion du client efface la plupart des données mises en cache. Toutefois, si vous rencontrez encore des problèmes après la fermeture et l’ouverture de session, quittez Teams et effacez le cache de votre client en procédant comme suit :
1. Fermez Microsoft Teams.
2. Accédez à :%appdata%\microsoft\teams et supprimez tous les fichiers.
3. Ouvrir Microsoft Teams de nouveau.
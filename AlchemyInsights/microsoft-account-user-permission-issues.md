---
title: Résoudre le problème-utilisateur introuvable dans l’annuaire
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 63f7d676-7cd9-4549-ba84-c3a8a7867f63
ms.openlocfilehash: 512494a69ab274af00962cb9777a3479b4200fd7
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47725405"
---
# <a name="troubleshoot-issue---user-not-found-in-directory"></a>Résoudre le problème-utilisateur introuvable dans l’annuaire

Si les utilisateurs reçoivent un message d’erreur indiquant que l’utilisateur est introuvable dans le répertoire, réessayez en indiquant que le type de problème est User not in Directory.

Vous pouvez effectuer les étapes suivantes pour résoudre le problème.

- Assurez-vous que le compte qui a accepté l’invitation électronique est le même compte que celui utilisé pour la connexion ultérieure. Assurez-vous que l’utilisateur utilise le même compte pour accepter l’invitation et se connecter au site. 

Pour plus d’informations, reportez-vous à la rubrique [How to Manage aliases for Your Microsoft Account </a> pour gérer la connexion Microsoft 365](https://support.microsoft.com/help/12407/microsoft-account-how-to-manage-aliases). 

- Accédez à chaque site (s) dans lequel l’utilisateur reçoit l’erreur. 

Ajoutez « /_layouts/15/People.aspx/MembershipGroupId = 0 » (dans les guillemets doubles) à la fin de l’URL du site. 

Exemple : https://< « contoso » >. sharepoint.com/_layouts/15/people.aspx/membershipGroupId=0.

- Sélectionnez l’utilisateur dans la liste.

- Cliquez sur **Supprimer les autorisations des utilisateurs** du ruban. 
-  Rajoutez l’utilisateur et renvoyez-le à l’utilisateur.


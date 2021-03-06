---
title: identique au nom de fichier recommandé
ms.author: pebaum
author: pebaum
manager: jackiesm
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: (guid of old soc version if any)
ms.openlocfilehash: 113d01e0fc92cc9845e585919ab05f386d6892bb
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47664132"
---
# <a name="required-alchemy-header-h1-h2s-dont-work"></a>« En-tête Alchemy obligatoire H1, H2's ne fonctionne pas. »
Meilleures pratiques et instructions pour la création de Alchemy :

1. **Ne pas imbriquer les informations Alchemy dans les dossiers**: cette opération va rompre la structure de l’URL. Nous nous penchons sur cette correction.
1. Les fichiers dans le dossier **AlchemyInsights** doivent avoir des caractères en minuscules avec des traits d’Union pour les espaces ex. ***procédure d’activation-conservation pour litige***.
    1. Incluez l’ID de la règle ou l’ID du compartiment à partir du [portail du partenaire Alchemy](https://alchemyportal.azurewebsites.net) dans le champ ms. Custom. ex. ***ms. Custom : 100021***
1. Utilisez le reste des métadonnées en haut de ce fichier comme modèle.
1. Dans le [portail du partenaire Alchemy](https://alchemyportal.azurewebsites.net), accédez à la section **titre du service client :** et utilisez-la comme point de départ pour votre titre H1 pour la vue d’analyse. 
    > [!NOTE]
    > Alchemy Insights ne doit avoir qu’un seul H1 en haut ou ils seront interrompus en production. H2s ne pas afficher de manière à utiliser le **gras** ou d’autres conventions pour signifier des sections distinctes.
1. Ensuite, renseignez le corps de texte à l’aide de l’élément brouillon dans la section informations client de la page de la règle Alchemy.
    1. Les listes à puces conviennent parfaitement
    1. Listes numérotées
    1. **Gras** et *italique* sont un-OK
    1. Les liens doivent toujours être **« liens vers le Web »/External** ou **des liens détaillés vers les éléments de l’interface utilisateur**, pas les liens internes.
    1. Les images ne sont pas officiellement prises en charge pour le moment, mais elles figurent dans la feuille de route.

Et cela est déjà un peu trop long. La meilleure pratique est de 400 caractères---------------------------------

Une fois que votre contenu est prêt, tirez-le vers la branche Live. Ensuite, accédez au [portail du partenaire Alchemy](https://alchemyportal.azurewebsites.net) et entrez le nom du fichier dans le champ URL. 
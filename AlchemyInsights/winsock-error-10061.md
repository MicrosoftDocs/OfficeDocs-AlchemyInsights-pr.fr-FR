---
title: 1554 erreur Winsock 10061
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1554
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: f44ed42906b85e63f1f694813f54710906969904
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/22/2019
ms.locfileid: "30772440"
---
# <a name="winsock-error-10061"></a>Erreur Winsock 10061

Ce code d'erreur signifie qu'Office 365 n'a pas pu établir de socket TCP (connexion) avec l'hôte cible. La cause la plus probable de cette erreur est un problème avec la configuration de votre pare-feu. Pour résoudre le problème, vérifiez les paramètres suivants:
  
- Vérifier la configuration de votre pare-feu avec les informations contenues dans les [URL et plages d'adresses IP Office 365](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)
    
- Si l'erreur est spécifique à Exchange Online Protection (EOP), vous devriez avoir été préalablement notifié à une modification apportée aux [adresses IP d'Exchange Online Protection](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).
    
- Vérifiez que votre fournisseur de services Internet (ISP) ne bloque pas le port.
    
- Vérifiez les paramètres de l'hôte actif et du serveur cible dans vos connecteurs.
    
Notez qu'Office 365 ne bloque pas les connexions *entrantes* de cette manière. 
  

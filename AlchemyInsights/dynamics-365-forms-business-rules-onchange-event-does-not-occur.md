---
title: Règles métier des formulaires Dynamics 365-la règle d’entreprise ne se déclenche pas pour un formulaire
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1926"
- "6200018"
ms.openlocfilehash: 4ade8d2f68b465298e2d6efff3eef4f04f25c3bf
ms.sourcegitcommit: a413a0e27ef4ab8c484fa9fccff8bbef381c8b96
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 07/16/2019
ms.locfileid: "35747573"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a>OnChange, événement ne se produit pas si le champ est modifié par programme

L’événement *OnChange* ne se produit pas si le champ est modifié par programmation à l’aide de l' *attribut.* [](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) méthode SetValue. Si vous souhaitez que les gestionnaires d’événements de l’événement *OnChange* s’exécutent une fois que vous avez défini la valeur, vous devez utiliser l' *attribut formContext. Data. Entity.* méthode [fireOnchange](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) dans votre code.

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
---
title: 1332 la ou les règles de boîte de réception OWA ne s’exécutent pas pour une boîte aux lettres
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
- "1332"
- "3700002"
ms.assetid: 383d1c77-5e4b-4a69-92d6-c404d890b6b7
ms.openlocfilehash: f4d8db9c590abc490f193ef54a8a1dc5afba82b9
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47721589"
---
# <a name="an-inbox-rule-doesnt-work-as-expected"></a>Une règle de boîte de réception ne fonctionne pas comme prévu

Vérifiez les paramètres suivants dans Outlook sur le Web :

- Un message peut être redirigé, transféré ou une réponse est automatiquement basée sur les règles de boîte de réception une seule fois. Une règle de redirection (une règle de boîte de réception ou une règle de flux de messagerie, également appelée règle de transport) peut ajouter un maximum de dix destinataires de transfert à un message. Pour plus d’informations, consultez les [limitations de journal, de transport et de règles de boîte de réception](https://docs.microsoft.com/office365/servicedescriptions/exchange-online-service-description/exchange-online-limits).

- Les règles de boîte de réception ne fonctionnent pas sur l’autre boîte aux lettres de journalisation. Pour plus d’informations sur l’autre boîte aux lettres de journalisation, voir [autre boîte aux lettres de journalisation](https://docs.microsoft.com/Exchange/security-and-compliance/journaling/journaling#alternate-journaling-mailbox).

Pour résoudre ces problèmes, reportez-vous à la rubrique [KB 2829319](https://support.microsoft.com/kb/2829319).

Si les problèmes précédents ne s’appliquent pas, exécutez le rapport de diagnostic des règles de boîte de réception avant de remonter le problème vers le support Microsoft :

1. Ouvrez la boîte aux lettres dans Outlook sur le Web, puis cliquez sur <img src='data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAMAAABhEH5lAAAA51BMVEX6+fj6+fDr+fjK+fj69LRxsuj6+cjY+fi/+fin3ev6+ddMk81HdK5AaatHLn/ntXTrsW5cRmLOk0pAND5KNCl1NCOi3fiGwvjJ3fDBz+F6teFgpdt6stX68c314syTucirtchum8bjz8BQh7/6+b47fbrKtapiian63aFDaaHJuZJiQo36woVabH7ZtHiOQnTHm2wlKmqriWF/cFzVnVTFjlSyeUkrNEmBLkWfaUGsaT67fTrj9Pi19PjO8fiv5vj69OFWm9Pt3aZ1Qo0lNHQ1P2iYTWGOQmHcpV5kRlqvc0mrbERpPzMoEeekAAAAxElEQVQY03WQ5w6CUAyFy3Jv3HsrICoKqLj3fP/nsTcNakjsn9t+bW/OKfyL6iTCc49e/ktuRs2WEhE1U/qgQQfEzGkNyxzVXLdw0ASW+a7BZp3HpJ+cpovUjcv6PYtvSmKj4/SswTMaBgg9FQF5axWysKoson4cGMYCvlEAQDwK7XkZwEVbRBpDPC46ygbAbPl31p4Wvd8nwiRCLnIArJb1ZBD7KFWMkdQLSUVIhowsGaIwzzVHikfVV8lzHPv3OGTfTd4gnRNqGdZ49AAAAABJRU5ErkJggg==' />
 **Paramètres**  >  **Afficher tous les paramètres Outlook**  >  **Courrier électronique**  >  **Règles**.

2. Au bas de la page, cliquez sur **si vos règles ne fonctionnent pas cliquez ici pour générer un rapport de diagnostic**.

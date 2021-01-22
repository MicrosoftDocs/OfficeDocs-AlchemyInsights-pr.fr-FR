---
title: Activer la technologie NDI
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004403"
- "7947"
ms.openlocfilehash: ea694898baffa50fca71957175eba3664dece44e
ms.sourcegitcommit: 112f18dce8257b98fab32d44910ee879efb44cb8
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 01/21/2021
ms.locfileid: "49917312"
---
# <a name="turn-on-ndi-technology"></a>Activer la technologie NDI

La technologie NDI nécessite deux étapes pour être allumée pour un utilisateur :

1. L’administrateur client doit activer la propriété « AllowNDIStreaming » dans CsTeamsMeetingPolicy.

    `Set-CsTeamsMeetingPolicy -Identity MEETING_POLICY -AllowNDIStreaming $true`

2. Une fois cette modification remplie, l’utilisateur final doit activer la technologie NDI® pour son client spécifique à partir des **paramètres > autorisations**.

Pour plus d’informations, voir [Utiliser la technologie NDI dans Microsoft Teams.](https://docs.microsoft.com/microsoftteams/use-ndi-in-meetings)

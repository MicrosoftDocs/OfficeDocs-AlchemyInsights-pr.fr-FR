---
title: ATP pour SharePoint, OneDrive et Microsoft Teams.
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1037
ms.assetid: ''
ms.openlocfilehash: b304f6c7d9959e49a8152c03f11c6c864a154ea5
ms.sourcegitcommit: 4b7e478ce700c0b781efec3857ac4dce5bdf00c6
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 06/07/2019
ms.locfileid: "34765036"
---
# <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a>ATP pour SharePoint, OneDrive et Microsoft Teams.

Procédez comme suit pour activer la protection avancée contre les menaces:

1. Accédez à [https://protection.office.com](https://protection.office.com) et connectez-vous à l’aide d’un compte d’administrateur général ou d’administrateur de sécurité.

2. Dans le volet de navigation de gauche, sous **gestion des menaces**, sélectionnez **stratégie** \> de **pièces jointes fiables**.

3. Sélectionnez Activer la protection avancée contre **les menaces pour SharePoint, OneDrive et Microsoft teams**.

4. [Créer une stratégie d’alerte d’activité](https://docs.microsoft.com/office365/securitycompliance/create-activity-alerts) pour recevoir des notifications lors de la détection de fichiers malveillants.

Pour obtenir des instructions complètes, consultez cette [rubrique](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams).

**Remarque**: par conception, la protection avancée contre les menaces n’analyse pas tous les fichiers dans SharePoint Online, OneDrive entreprise ou Microsoft Teams. Les fichiers sont analysés de manière asynchrone par un processus qui utilise l’activité de partage, l’activité des invités et des signaux de menace pour identifier les fichiers malveillants. Pour plus d’informations, consultez cette [rubrique](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).
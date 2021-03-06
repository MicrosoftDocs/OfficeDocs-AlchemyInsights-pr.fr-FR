---
title: Utilisation de l’outil déploiement d’Office
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "918"
- "2000022"
ms.assetid: 7ff7cc06-76d0-468f-bd66-3f2760750d04
ms.openlocfilehash: f3a5dbfc6b64ccd4f0b19a5f86236336e78838d4
ms.sourcegitcommit: 35e2c122d8a838d98d1f0851c29b16282261580f
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 11/17/2020
ms.locfileid: "49085830"
---
# <a name="using-the-office-deployment-tool-odt"></a>Utilisation de l’outil déploiement d’Office (ODT)

L’outil déploiement d’Office (ODT) vous permet de déployer des versions Office 365 d’Office. L’outil déploiement d’Office (setupodt.exe) est exécuté à partir de la ligne de commande et utilise un fichier XML de configuration pour déterminer les paramètres à appliquer lors du déploiement d’Office.
  
1. Téléchargez la dernière version de l’outil déploiement d’Office à partir du [Centre de téléchargement Microsoft](https://go.microsoft.com/fwlink/p/?LinkID=626065).

2. Utilisez l' [outil de personnalisation Office (OPO)](https://config.office.com) pour sélectionner vos préférences de déploiement et créer le fichier XML de configuration. Exportez le fichier de configuration et placez-le localement dans le dossier où se trouve le setupodt.exe.

    **Remarque :** Les problèmes d’installation d’Office se produisent généralement en raison de fichiers de configuration mal configurés ou malformatted. Pour éviter ces problèmes, nous vous recommandons d’utiliser l’outil de personnalisation Office pour créer le fichier de configuration. Vous pouvez également importer des fichiers de configuration existants dans l’outil de personnalisation Office.

3. À partir d’une invite de commandes avec élévation de privilèges, basculez vers l’emplacement où setupodt.exe réside et exécutez l’outil déploiement d’Office en mode de téléchargement et spécifiez le fichier de configuration que vous venez d’enregistrer. Dans cet exemple, le fichier de configuration est nommé Configuration.xml :

```setupodt.exe /download Configuration.xml```

4. Exécutez l’outil déploiement d’Office en mode de configuration et spécifiez le fichier de configuration.

```setupodt.exe /configure Configuration.xml```

**Remarque :** Vous devez exécuter cette étape à partir de l’ordinateur client sur lequel vous voulez installer Office et vous devez disposer des autorisations d’administrateur local sur cet ordinateur.

Pour en savoir plus sur l’utilisation de l’outil déploiement d’Office pour vos applications Microsoft 365 pour les scénarios de déploiement d’entreprise, reportez-vous à [vue d’ensemble de l’outil déploiement d’Office](https://docs.microsoft.com/deployoffice/overview-office-deployment-tool). Pour plus d’informations sur l’utilisation de l’outil de personnalisation Office, voir [vue d’ensemble de l’outil de personnalisation Office](https://docs.microsoft.com/DeployOffice/overview-of-the-office-customization-tool-for-click-to-run).

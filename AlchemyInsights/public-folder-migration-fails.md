---
title: Échec de la migration de dossiers publics à 95%
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 08/25/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "639"
- "3500007"
ms.openlocfilehash: b22dce778b4507e0a3337a59a55531ce248b59c4
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47662421"
---
# <a name="public-folder-migration-fails-at-95"></a>Échec de la migration de dossiers publics à 95%

Vous avez peut-être initié un lot de migration, et son état continue d’afficher **Synchronisé** pendant une période très longue. Il s'agit d'un comportement normal.

Il est fréquent que l’état d’un lot de migration reste sur **Synchronisé** pendant quelques heures avant qu’il ne passe à **Finalisation**. Pour les migrations impliquant un grand nombre de boîtes aux lettres cibles, il est normal de voir l’état Synchronisé pendant plus de 24 heures, pour autant qu’aucune des demandes de migration de dossiers publics sous-jacentes n’ait échoué ou n’ait été mise en quarantaine. Merci de laisser 24 à 48 heures au lot de migration pour effectuer les tâches.

Pour les migrations de dossier public qui échouent à 95%, avec l’erreur FailedToMailEnablePublicFoldersException :

1. Téléchargez et exécutez le script [ValidateMailEnabledPublicFolders](https://aka.ms/ValidateMEPF) sur votre serveur Exchange local.

2. Effectuez les actions correctives suggérées par le script.

3. Exécutez le Sync-MailPublicFolders (pour Exchange 2010) ou Sync-ModernMailPublicFolders (pour Exchange 2013 et versions ultérieures).

4. Reprendre la migration de dossiers publics.

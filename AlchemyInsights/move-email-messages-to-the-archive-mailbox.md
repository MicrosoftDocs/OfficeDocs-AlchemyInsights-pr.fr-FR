---
title: Déplacer des messages électroniques vers la boîte aux lettres d’archivage
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
- "1083"
- "3100008"
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: 61d0b1a58fff6655b745bb9d39e8384f0a543336
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/15/2020
ms.locfileid: "47799778"
---
# <a name="move-email-to-the-archive-mailbox"></a>Déplacer le courrier électronique vers la boîte aux lettres d’archivage

Si vous souhaitez que nous puissions exécuter des vérifications automatiques pour les paramètres mentionnés ci-dessous, sélectionnez le bouton précédent <--en haut de cette page, puis entrez l’adresse de messagerie de l’utilisateur qui rencontre des problèmes lors du transfert du courrier électronique vers sa boîte aux lettres d’archivage.

1. Vérifiez qu’une **boîte aux lettres d’archivage** a été activée. Si ce n’est pas le cas, suivez les étapes décrites dans [cet article](https://docs.microsoft.com/microsoft-365/compliance/enable-archive-mailboxes) pour activer la boîte aux lettres d’archivage.

2. Pour archiver automatiquement les messages dans la boîte aux lettres d’archivage, une balise de rétention avec l’action **déplacer vers l’archive** doit être définie sur **appliqué automatiquement à la balise de boîte aux lettres (par défaut) entière**. Suivez les étapes ci-dessous pour créer la balise : [archive default](https://docs.microsoft.com/microsoft-365/compliance/set-up-an-archive-and-deletion-policy-for-mailboxes#create-a-custom-archive-default-policy-tag).

3. Ensuite, ajoutez la balise **Archive** à votre stratégie de rétention. Dans le centre d’administration Exchange, choisissez **stratégies de Rétention** > ajouter la **balise déplacer vers l’archive** à la stratégie > **Enregistrer**.

4. À présent, [affectez la stratégie de rétention](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) à la boîte aux lettres de l’utilisateur spécifique. La même stratégie sera appliquée à la boîte aux lettres **principale** et à la boîte aux lettres d' **archivage** .

Il peut s’avérer nécessaire de forcer l’Assistant dossier géré à exécuter et d’appliquer les nouveaux paramètres à la boîte aux lettres de l’utilisateur. Exécutez la commande suivante lorsque [vous êtes connecté à exo PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) pour démarrer l’Assistant dossier géré pour une boîte aux lettres spécifique :
  
Start-ManagedFolderAssistant-Identity <name of the mailbox>

Pour plus d’informations sur la configuration d’une stratégie d’archivage, consultez la rubrique [configurer une stratégie d’archivage et de suppression pour les boîtes aux lettres](https://docs.microsoft.com/microsoft-365/compliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).
  
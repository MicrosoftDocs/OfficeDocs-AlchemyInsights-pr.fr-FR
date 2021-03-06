---
title: Rappel du Bureau Outlook ou remplacement d’un message électronique
ms.author: daeite
author: daeite
manager: joallard
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ms.custom: 9000260
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: 578e2690061286bde74ee0b4b74a197630716f59
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47663988"
---
# <a name="recall-or-replace-an-outlook-email-message"></a>Rappeler ou remplacer un message électronique Outlook

- En tant qu’administrateur, vous pouvez **rappeler des messages au nom des utilisateurs à l’aide de PowerShell**. Vous ne pouvez pas rappeler les messages à partir du centre d’administration.
- Vous pouvez **uniquement rappeler les messages qui sont envoyés à des personnes de votre organisation**. Si le message a été envoyé à une adresse Gmail, par exemple, vous ne pouvez pas le rappeler.
- Vous pouvez **uniquement rappeler les messages envoyés à partir d’Outlook 2016 sur le PC**. Si un utilisateur envoie un message à l’aide d’Outlook pour Mac ou d’Outlook sur le Web, vous ne pouvez pas le rappeler.

Pour rappeler ou remplacer un message électronique :

1. Dans le volet des dossiers situé à gauche de la fenêtre Outlook, sélectionnez le dossier éléments envoyés.
1. Double-cliquez sur le message que vous souhaitez rappeler pour l’ouvrir.
1. Sélectionnez l’onglet **message** , puis sélectionnez **actions**  >  **rappeler ce message**.
1. Sélectionnez **Supprimer les copies non lues de ce message** ou **Supprimer les copies non lues et les remplacer par un nouveau message**, puis cliquez sur **OK**.
1. Si vous envoyez un message de remplacement, composez le message, puis sélectionnez **Envoyer**.
1. La réussite ou l’échec d’un rappel de message dépend des paramètres du destinataire dans Outlook. Pour connaître les étapes à suivre pour vérifier le rappel, consultez [cet article](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

Recherche et suppression de messages électroniques dans votre organisation

- Si vous n’êtes pas un administrateur général, votre compte doit être ajouté au rôle gestionnaire eDiscovery ou au rôle de gestion de la recherche de conformité pour rechercher des messages. Pour supprimer des messages, vous devez rejoindre le groupe de rôles gestion de l’organisation ou le rôle de gestion de la recherche et de la purge. Les autorisations de ces rôles sont attribuées dans le [Centre de sécurité et de conformité](https://go.microsoft.com/fwlink/?linkid=2083731).
- [Créer une recherche de contenu](https://docs.microsoft.com/microsoft-365/compliance/content-search) pour rechercher le message à supprimer.
- [Connectez-vous au centre de sécurité et de conformité PowerShell](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).

Si vous utilisez l’authentification multifacteur, reportez-vous [à se connecter au centre de sécurité et de conformité Microsoft 365 PowerShell à l’aide de l’authentification multifacteur](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).
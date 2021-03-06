---
title: Enregistrement d’appareil dupliqué dans le portail
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4386"
ms.openlocfilehash: e6f477807823e68965ce966faf0a6f50f9472f3d
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51814514"
---
# <a name="duplicate-device-record-in-the-portal"></a>Enregistrement d’appareil dupliqué dans le portail

Vous pouvez voir 2 enregistrements pour un appareil dans le portail si l’appareil ne signale pas correctement l’état de la co-gestion sur le site de Configuration Manager. Pour vérifier l’état de co-gestion d’un appareil, consultez la colonne **co-géré** de l’appareil dans la console de Configuration Manager. Si la colonne n’est pas visible, vous pouvez l’ajouter en cliquant avec le bouton droit sur l’un des en-têtes de colonne, puis en sélectionnant celle-ci dans la liste.

La valeur Co-géré doit être définie sur **Oui**. Si la valeur est définie sur **Non**, ouvrez l’applet client Configuration Manager sur l’appareil client et vérifiez la propriété **Co-gestion** dans l’onglet général.

- Si la valeur est définie sur **Activé**, cela indique la présence de problèmes liés aux communications client avec le point de gestion. Consultez le **CcmMessaging.log** sur l’appareil pour identifier les problèmes de connectivité potentiels.

- Si la valeur est définit sur **désactivée** et si l’appareil est inscrit dans Intune, vérifiez que l’appareil a reçu la stratégie de co-gestion en examinant le **CoManagementHandler.log** sur l’appareil.

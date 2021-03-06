---
title: Icône d’alimentation ou de batterie manquante dans Windows 10
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
- "9002953"
- "5655"
ms.openlocfilehash: 95b68cee58f88d04f02e29477b139f7f583dc0b1
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51790546"
---
# <a name="power-or-battery-icon-missing-in-windows-10"></a>Icône d’alimentation ou de batterie manquante dans Windows 10

Si votre appareil Windows 10 possède une batterie (par exemple, un ordinateur portable ou une tablette, ou un PC connecté via USB à un onduleur), une icône d’alimentation/de batterie apparaît habituellement dans la barre des tâches près de l’horloge, par exemple :

![Icône de la batterie](media/battery-icon.png)

Si vous ne voyez pas cette icône, il est possible qu’elle soit masquée :

1. Accédez à **Paramètres [> Personnalisation > Barre des tâches](ms-settings:taskbar?activationSource=GetHelp)**.

2. Dans le volet de Notifications, cliquez sur **Sélectionner les icônes à afficher dans la barre des tâches**.

3. Recherchez ensuite l’élément d’**alimentation** dans la liste et définissez-le sur **Activé**.

    ![Afficher l’icône d’alimentation dans la barre des tâches](media/power-icon-on.png)

**Résolution des problèmes**

Si vous avez suivi les instructions ci-dessus et que le bouton bascule d’**Alimentation** est grisé ou n’apparaît pas, dans la zone de recherche de la barre des tâches, tapez **gestionnaire d’appareils**, puis sélectionnez **Gestionnaire d’appareils** dans la liste des résultats. Sous **Batteries**, cliquez avec le bouton droit sur la batterie sur votre appareil, puis sur **Désactiver**, et enfin sur **Oui**. Patientez quelques secondes, puis cliquez avec le bouton droit sur la batterie, enfin cliquez sur **Activer**. Redémarrez ensuite votre appareil.

Si vous avez suivi les instructions ci-dessus, mais que l’icône de la batterie ne s’affiche pas dans la barre des tâches, dans la zone de recherche de la barre des tâches, tapez **gestionnaire des tâches**, puis cliquez sur **Gestionnaire des tâches** dans la liste des résultats. Sous l’onglet **Processus**, sous **Nom**, cliquez avec le bouton droit sur **Explorateur**, puis cliquez sur **Redémarrer**.

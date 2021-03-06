---
title: Résoudre les problèmes d'inscription d'appareils Android dans Microsoft Intune
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d0269461-20a8-4c9e-83b2-8fcf608dc0a5
ms.custom:
- "787"
- "6200002"
ms.openlocfilehash: 08620a44dcf693482c65ff05e19f11870f67afbe
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51830940"
---
# <a name="troubleshoot-issues-with-enrolling-android-devices-in-microsoft-intune"></a>Résoudre les problèmes d'inscription d'appareils Android dans Microsoft Intune

Examinez les ressources répertoriées ci-dessous pour résoudre votre problème maintenant.
  
Quelques problèmes courants et étapes de résolution :
  
 **Erreur d'appareil non chiffré dans le portail d'entreprise :** Les versions plus récentes d'Android, en particulier à partir de la version v7.0, nécessitent un code secret de démarrage pour s'assurer que votre appareil est entièrement chiffré. Les solutions courantes sont d'activer un code confidentiel de démarrage ou de chiffrer entièrement l'appareil. Pour plus [d'informations,](https://docs.microsoft.com/intune-user-help/your-device-appears-encrypted-but-cp-says-otherwise-android) examinez ce document.
  
 Les appareils ne parviennent pas à s'enregistrer avec le service Intune ou s'affichent comme « Défectueux » dans la **console d'administration Intune :** Certains appareils Samsung 4.4 et 5.5 peuvent ne pas être connectés au service. Il existe 3 solutions possibles à ce problème :
  
1. Ouvrez manuellement l'application Portail d'entreprise Intune, qui lancera automatiquement une synchronisation d'appareil.

2. Mettez à jour l'appareil vers Android 6.0 ou version supérieure.

3. Désactivez Samsung Smart Manager de la gestion du portail d'entreprise Intune. Pour [plus d'informations](https://docs.microsoft.com/troubleshoot/mem/intune/troubleshoot-device-enrollment-in-intune#devices-fail-to-check-in-with-the-intune-service-and-display-as-unhealthy-in-the-intune-admin-console) sur ces problèmes et résolutions, examinez ce document.

 **Type de licence utilisateur non** valide ou erreur de nom d'utilisateur non reconnu **:** une licence Intune ou EMS doit être attribuée à l'utilisateur. Examinez ces documents pour attribuer une licence par le biais du Centre d'administration Office ou du portail Azure.
  
Ressources supplémentaires pour vous aider à résoudre votre problème :
  
1. Utilisez [le portail de dépannage Intune pour](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) diagnostiquer et résoudre les échecs d'inscription courants. Pour [plus d'informations,](https://docs.microsoft.com/intune/help-desk-operators) examinez ce document.

2. Examinez [ce document pour](https://docs.microsoft.com/troubleshoot/mem/intune/troubleshoot-device-enrollment-in-intune) obtenir la liste des erreurs courantes qui empêchent l'inscription et les résolutions à chacune d'elles.

3. [Découvrez comment inscrire des appareils Android dans Microsoft Intune.](https://docs.microsoft.com/intune/android-enroll)

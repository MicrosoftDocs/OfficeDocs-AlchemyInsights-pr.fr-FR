---
title: Restreindre l’accès dans SharePoint ou OneDrive
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: af1b936b-0475-497b-a6d3-e671aef7b717
ms.openlocfilehash: e9eb1822a7770bc206992cc5fb7e54a5c972b7e2
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47700453"
---
# <a name="restrict-access-in-sharepoint-or-onedrive"></a>Restreindre l’accès dans SharePoint ou OneDrive

Il existe plusieurs façons de restreindre l’accès aux services SharePoint Online/OneDrive. Ces différentes méthodes de restriction d’accès sont décrites ci-dessous. 

**Restriction des autorisations**

Dans SharePoint Online et OneDrive entreprise, nous restreignons l’accès à des éléments tels que des sites, des fichiers et des dossiers en accordant uniquement l’accès à ces groupes/individus qui doivent avoir accès.

- [Personnaliser les autorisations pour une liste ou une bibliothèque SharePoint](https://support.office.com/article/Customize-permissions-for-a-SharePoint-list-or-library-02d770f3-59eb-4910-a608-5f84cc297782)

- [Personnaliser les autorisations de site SharePoint](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions)

- [Modifier les autorisations sur un sous-dossier](https://support.office.com/article/Change-the-permissions-on-a-subfolder-5427BD7C-F20A-4F75-8CF2-5359DD45A1A6)

- [Contrôler l’accès à partir d’appareils non gérés](https://docs.microsoft.com/sharepoint/control-access-from-unmanaged-devices)

En tant qu’administrateur SharePoint ou global, vous pouvez bloquer ou limiter l’accès au contenu SharePoint et OneDrive à partir d’appareils non gérés (ceux qui ne sont pas des services AD hybrides ou conformes dans Intune).

**Restriction d’emplacement réseau**

En tant qu’administrateur informatique, vous pouvez contrôler l’accès aux ressources SharePoint et OneDrive en fonction des emplacements réseau définis auxquels vous faites confiance. C’est ce qu’on appelle aussi une stratégie basée sur l’emplacement. Pour plus d’informations, reportez-vous à la rubrique [contrôler l’accès à SharePoint Online et aux données OneDrive en fonction de l’emplacement réseau](https://docs.microsoft.com/sharepoint/control-access-based-on-network-location)

**Restriction de verrouillage de site** 

Dans SharePoint Online, vous avez la possibilité de verrouiller une collection de sites, de sorte que personne ne puisse y accéder. Cette valeur est définie via PowerShell et [SharePoint Online Management Shell](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps) à l’aide de la propriété [Set-SPOSite](https://docs.microsoft.com/powershell/module/sharepoint-online/set-sposite?view=sharepoint-ps) -LockState.

**Empêcher les utilisateurs de créer des sites ou des sous-sites**

En tant qu’administrateur SharePoint ou administrateur général, vous pouvez permettre à vos utilisateurs de créer et d’administrer leurs propres sites SharePoint, de déterminer le type de sites qu’ils peuvent créer et de spécifier l’emplacement des sites. Pour plus d’informations, consultez la rubrique [gérer la création de sites dans SharePoint Online](https://docs.microsoft.com/sharepoint/manage-site-creation) .


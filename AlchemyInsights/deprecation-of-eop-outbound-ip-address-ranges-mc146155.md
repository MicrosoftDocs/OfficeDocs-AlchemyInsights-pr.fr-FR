---
title: 1065 dépréciation de l’adresse IP sortante rangesMC146155
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1065
ms.assetid: bd41784e-8002-428d-bc19-25671cfd34e8
ms.openlocfilehash: afd725668f906339f4b7d769bb67a4d2ee5a6ac6
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/15/2020
ms.locfileid: "47806793"
---
# <a name="deprecation-of-eop-outbound-ip-address-ranges"></a>Dépréciation des plages d’adresses IP sortantes EOP

Nous avons détecté un problème potentiel avec votre organisation, qui (si elle n’a pas été corrigé par le 26 octobre 2018) peut rompre le flux de messagerie vers vos destinations locales ou externes. Comme précédemment communiqué, pour simplifier la gestion des plages d’adresses IP, nous consolidons les plages d’adresses IP d’Exchange Online Protection (EOP) qui sont utilisées pour envoyer et recevoir des courriers électroniques en dehors de Microsoft 365. Notre analyse indique qu’une ou plusieurs des sources de messagerie ou des destinations externes que vous avez configurées dans les connecteurs de flux de messagerie n’acceptent pas les connexions à partir des plages d’adresses IP indiquées [ici](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).

Act avant le 26 octobre pour s’assurer que ces sources et destinations acceptent les connexions vers et à partir de toutes les [adresses IP EOP publiées](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).

Pour plus d’informations sur cette modification, consultez la rubrique messages Center Posts [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620)ou [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).

**Remarque**: Si vous utilisiez précédemment la publication IP ou URL via html, XML et RSS pour les mises à jour de point de terminaison, vous devez également effectuer une migration vers les nouveaux services Web pour l’automatisation de ces types de mises à jour. Pour plus d’informations, consultez les [catégories de points de terminaison de microsoft 365 et l’adresse IP de microsoft 365 et le service Web d’URL](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).

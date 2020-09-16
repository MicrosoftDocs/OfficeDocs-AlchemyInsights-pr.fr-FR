---
title: Activer l’audit de boîte aux lettres
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 404ef9ecd824541f98471bb8797f5f6e025012b7
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/15/2020
ms.locfileid: "47806289"
---
# <a name="enable-mailbox-auditing"></a>Activer l’audit de boîte aux lettres

Pour activer l’audit de boîte aux lettres pour un seul utilisateur ou une organisation entière, les cmdlets suivantes doivent être exécutées à distance :
  
 **Utilisateur unique**
  
Set-Mailbox-Identity "Jeanne Dow"-AuditEnabled $true
  
 **Organisation**
  
Get-Mailbox-result-Unlimited-Filter {RecipientTypeDetails-EQ "UserMailbox"} | Set-Mailbox-AuditEnabled $true
  
[En savoir plus](https://docs.microsoft.com/microsoft-365/compliance/enable-mailbox-auditing)
  


---
title: Modifier les serveurs de noms
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5"
- "14"
ms.openlocfilehash: 51532f42e7cbd39ebad3f0160465218c6e1454a2
ms.sourcegitcommit: a256e8680379c006287ae30996763051c4d9ff85
ms.translationtype: HT
ms.contentlocale: fr-FR
ms.lasthandoff: 09/04/2019
ms.locfileid: "36736647"
---
# <a name="update-your-domain-nameservers-to-office-365"></a><span data-ttu-id="5b1cf-102">Mettre à jour les serveurs de noms de votre domaine vers Office 365</span><span class="sxs-lookup"><span data-stu-id="5b1cf-102">Update your domain nameservers to Office 365</span></span>

<span data-ttu-id="5b1cf-103">Remarque : le Serveur de noms modifications peut prendre jusqu'à 48 heures.</span><span class="sxs-lookup"><span data-stu-id="5b1cf-103">Note: Nameserver changes can sometimes take up to 48 hours to propagate.</span></span>
  
<span data-ttu-id="5b1cf-p101">Pour configurer votre domaine dans Office 365, les serveurs de noms de votre bureau d’enregistrement doivent être mis à jour. Créez ou modifiez vos enregistrements de serveur de noms auprès de votre bureau d’enregistrement de domaine.</span><span class="sxs-lookup"><span data-stu-id="5b1cf-p101">To set up your domain in Office 365, the nameservers at your registrar need to be updated. Create or edit your nameserver records at your domain registrar.</span></span>
  
1. <span data-ttu-id="5b1cf-106">Accédez au site web de votre bureau d’enregistrement de domaines et recherchez la zone dans laquelle vous pouvez modifier les serveurs de noms.</span><span class="sxs-lookup"><span data-stu-id="5b1cf-106">Go to your domain registrar's website and find the area where you can edit the nameservers.</span></span>
  
2. <span data-ttu-id="5b1cf-107">Créez ou modifiez deux enregistrements de serveur de noms avec ces valeurs :</span><span class="sxs-lookup"><span data-stu-id="5b1cf-107">Create or edit two nameserver records to match these values:</span></span>

  - <span data-ttu-id="5b1cf-108">ns1.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="5b1cf-108">ns1.bdm.microsoftonline.com</span></span>

  - <span data-ttu-id="5b1cf-109">ns2.bdm.microsoftonline.com</span><span class="sxs-lookup"><span data-stu-id="5b1cf-109">ns2.bdm.microsoftonline.com</span></span>

3. <span data-ttu-id="5b1cf-110">Enregistrez les modifications.</span><span class="sxs-lookup"><span data-stu-id="5b1cf-110">Save changes.</span></span>

<span data-ttu-id="5b1cf-111">Vous trouverez également des instructions détaillées dans cet article : [Modifier les serveurs de noms de manière à configurer Office 365 avec n’importe quel bureau d’enregistrement de domaines](https://docs.microsoft.com//office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span><span class="sxs-lookup"><span data-stu-id="5b1cf-111">You can also find detailed instructions in this article: [Change nameservers to set up Office 365 with any domain registrar](https://docs.microsoft.com//office365/admin/get-help-with-domains/change-nameservers-at-any-domain-registrar)</span></span>
  
---
title: Joindre Azure Active Directory
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 03/24/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003257"
- "9890"
ms.openlocfilehash: 59e3798131956847a61af2416c2e4210199cffa5
ms.sourcegitcommit: db908b3da2c7a6508a77bf4f2c80afb294fadbd1
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 03/29/2021
ms.locfileid: "51403799"
---
# <a name="azure-active-directory-join"></a><span data-ttu-id="6f212-102">Joindre Azure Active Directory</span><span class="sxs-lookup"><span data-stu-id="6f212-102">Azure Active Directory join</span></span>

1. <span data-ttu-id="6f212-103">Si vous êtes en train de définir des inscriptions d’appareils pour la première fois, assurez-vous d’avoir examiné l’introduction à la gestion des appareils dans [Azure Active Directory](/azure/active-directory/devices/overview) qui vous guidera sur la façon d’obtenir des appareils sous le contrôle d’Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6f212-103">If you are setting up device registrations for the first time, ensure that you have reviewed [Introduction to device management in Azure Active Directory](/azure/active-directory/devices/overview) that will guide you on how to get Devices under the control to Azure AD.</span></span> 
1. <span data-ttu-id="6f212-104">Si vous inscrivez des appareils directement dans Azure AD et que vous les inscrivez dans Intune, vous [](/mem/intune/fundamentals/licenses-assign) devez vous assurer que vous avez configuré [Intune](/mem/intune/enrollment/device-enrollment) et que la licence est en place en premier.</span><span class="sxs-lookup"><span data-stu-id="6f212-104">If you are registering devices into Azure AD directly and enrolling them into Intune, you will need to ensure that you have [configured Intune](/mem/intune/enrollment/device-enrollment) and have the [licensing](/mem/intune/fundamentals/licenses-assign) in place first.</span></span>
1. <span data-ttu-id="6f212-105">Assurez-vous que vous êtes autorisé à effectuer des opérations dans Azure AD.</span><span class="sxs-lookup"><span data-stu-id="6f212-105">Ensure you are authorized to perform operations in Azure AD.</span></span> <span data-ttu-id="6f212-106">Seul un administrateur général dans Azure AD peut gérer les paramètres d’inscription des appareils.</span><span class="sxs-lookup"><span data-stu-id="6f212-106">Only a global administrator in Azure AD can manage settings for device registrations.</span></span>
1. <span data-ttu-id="6f212-107">Pour l’implémentation de la jointisation Azure AD, voir [Planifier Azure AD Join](/azure/active-directory/devices/azureadjoin-plan).</span><span class="sxs-lookup"><span data-stu-id="6f212-107">To do Azure AD join implementation, see [Plan Azure AD Join](/azure/active-directory/devices/azureadjoin-plan).</span></span>

<span data-ttu-id="6f212-108">Pour plus d’informations sur la résolution des problèmes courants avec la jointation Azure AD, consultez le FAQ sur azure [Ad Join](/azure/active-directory/devices/faq) et pour l’appareil Windows 10 professionnel, voir Impossible de joindre l’ordinateur [Windows 10 Professionnel](https://answers.microsoft.com/en-us/msoffice/forum/msoffice_install-mso_win10-mso_365hp/unable-to-join-windows-10-pro-machine-to-azure-ad/abb1ca7d-b317-45ec-a628-e1c10eae2900)à Azure AD - Besoin de mettre à niveau vers - Microsoft Community .</span><span class="sxs-lookup"><span data-stu-id="6f212-108">For more details on resolving common issues with Azure AD join, see [Azure Ad Join FAQ](/azure/active-directory/devices/faq) and for Windows 10 pro device, see [Unable to join Windows 10 Pro machine to Azure AD - Need to upgrade to - Microsoft Community](https://answers.microsoft.com/en-us/msoffice/forum/msoffice_install-mso_win10-mso_365hp/unable-to-join-windows-10-pro-machine-to-azure-ad/abb1ca7d-b317-45ec-a628-e1c10eae2900).</span></span>
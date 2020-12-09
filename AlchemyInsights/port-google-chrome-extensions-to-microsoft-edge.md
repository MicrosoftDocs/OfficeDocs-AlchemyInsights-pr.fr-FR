---
title: Porter les extensions Google Chrome vers Microsoft Edge (chrome)
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/03/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004032"
- "7102"
ms.openlocfilehash: 2a20f258cbcbca7c8db4e38c52464fefb1b6f39d
ms.sourcegitcommit: 38c87ed786dda7181562492d5d2e7ef0e18e0cab
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 12/08/2020
ms.locfileid: "49600114"
---
# <a name="port-google-chrome-extensions-to-microsoft-edge-chromium"></a><span data-ttu-id="fcf6e-102">Porter les extensions Google Chrome vers Microsoft Edge (chrome)</span><span class="sxs-lookup"><span data-stu-id="fcf6e-102">Port Google Chrome extensions to Microsoft Edge (Chromium)</span></span>

<span data-ttu-id="fcf6e-103">Il est facile de [porter les extensions Google Chrome vers Microsoft Edge (chrome)](https://docs.microsoft.com/microsoft-edge/extensions-chromium/developer-guide/port-chrome-extension).</span><span class="sxs-lookup"><span data-stu-id="fcf6e-103">It's easy to [port Google Chrome extensions to Microsoft Edge (Chromium)](https://docs.microsoft.com/microsoft-edge/extensions-chromium/developer-guide/port-chrome-extension).</span></span> <span data-ttu-id="fcf6e-104">Dans la plupart des cas, des modifications minimes sont nécessaires pour exécuter ces extensions sur Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="fcf6e-104">In most cases, only minimal changes are needed to run these extensions on Microsoft Edge.</span></span>

<span data-ttu-id="fcf6e-105">Les API d’extension et les clés de manifeste prises en charge par Google Chrome sont compatibles avec le code Microsoft Edge.</span><span class="sxs-lookup"><span data-stu-id="fcf6e-105">The extension APIs and manifest keys supported by Google Chrome are code-compatible with Microsoft Edge.</span></span> <span data-ttu-id="fcf6e-106">Toutefois, Microsoft Edge ne prend pas en charge les API d’extension chrome. GCM, chrome. Identity. getAccounts, chrome. Identity. getAuthToken et chrome. instanceID.</span><span class="sxs-lookup"><span data-stu-id="fcf6e-106">However, Microsoft Edge does not support the extension APIs chrome.gcm, chrome.identity.getAccounts, chrome.identity.getAuthToken, and chrome.instanceID.</span></span>
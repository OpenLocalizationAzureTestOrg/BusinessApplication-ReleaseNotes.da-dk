---
title: "Hurtigere indlæsning med parallel dataindlæsning i lærred-apps"
description: "Appudviklere kan indlæse flere data på samme tid, hvilket reducerer den samlede ventetid for appbrugere."
author: gregli
manager: AnnBe
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 41ca7431301c5af53be78b728ab95ce7101aa7e0
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---
# <a name="faster-load-times-with-parallel-data-loading-in-canvas-apps"></a><span data-ttu-id="75541-103">Hurtigere indlæsning med parallel dataindlæsning i lærred-apps</span><span class="sxs-lookup"><span data-stu-id="75541-103">Faster load times with parallel data loading in canvas apps</span></span>

[!include[powerapps banner](../includes/powerapps.md)]




<span data-ttu-id="75541-104">For at få en bedre ydeevne vil mange udviklere af lærred-apps forudindlæse flere tabeller og objekter, når deres app starter.</span><span class="sxs-lookup"><span data-stu-id="75541-104">For better performance, many canvas-app makers will preload multiple tables and entities when their app starts.</span></span> <span data-ttu-id="75541-105">I dag gøres dette serielt, én indlæsning ad gangen, og ofte i appens **OnStart**-formular.</span><span class="sxs-lookup"><span data-stu-id="75541-105">Today, this is done serially, one load after another, often in the **OnStart** formula of the app.</span></span> 

<span data-ttu-id="75541-106">Med denne funktion kan appudviklere indlæse flere datasæt parallelt, hvilket reducerer slutbrugernes ventetid betydeligt.</span><span class="sxs-lookup"><span data-stu-id="75541-106">With this feature, app makers can load multiple data sets in parallel, dramatically reducing the end users' wait.</span></span>  <span data-ttu-id="75541-107">Og funktionen er ikke kun begrænset til opstartssituationer. Udviklere kan bruge den alle steder, hvor paralleloperationer vil forbedre ydeevnen.</span><span class="sxs-lookup"><span data-stu-id="75541-107">And this facility isn't just limited to startup; makers can use it anywhere that parallel operations would improve performance.</span></span>


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
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 587d76f50fead1766f5dc810e2f9b0bf34bd760a
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
# <a name="faster-load-times-with-parallel-data-loading-in-canvas-apps"></a>Hurtigere indlæsning med parallel dataindlæsning i lærred-apps


[!include[banner](../../includes/banner.md)]

For at få en bedre ydeevne vil mange udviklere af lærred-apps forudindlæse flere tabeller og objekter, når deres app starter. I dag gøres dette serielt, én indlæsning ad gangen, og ofte i appens **OnStart**-formular. 

Med denne funktion kan appudviklere indlæse flere datasæt parallelt, hvilket reducerer slutbrugernes ventetid betydeligt.  Og funktionen er ikke kun begrænset til opstartssituationer. Udviklere kan bruge den alle steder, hvor paralleloperationer vil forbedre ydeevnen.


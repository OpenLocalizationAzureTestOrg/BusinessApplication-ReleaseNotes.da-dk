---
title: Sammensatte modeller
description: "Understøttelse af miks af DirectQuery- og importdatakilder i Power BI Desktop"
author: MI77
manager: kimani
ms.date: 7/22/18
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: willthom
audience: developer, citizen developer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 3256b373787e8c32a7ef80faad85e2ebd5f3634e
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---

# <a name="composite-models-public-preview"></a>Sammensatte modeller (offentlig prøveversion)

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

Med sammensatte modeller kan du blande importkilder og DirectQuery-kilder i tabelformat og have flere DirectQuery-kilder i tabelformat. På denne måde kan du udvide din virksomheds datamodeller med importerede tabeller. 

Modeludviklere kan oprette en Power BI Desktop-fil ud fra en DirectQuery-datakilde og derefter tilføje tabeller, der er importeret fra en anden datakilde. For at understøtte denne nye modelstruktur indfører vi også mange til mange-relationer og tabeller, der er i dobbelttilstand, hvilket betyder, at de kan fungere som import eller DirectQuery, afhængigt af hvilke andre tabeller du føjer til de visuelle elementer. Power BI giver derefter intelligente svar på dine analyser, enten fra de importerede data eller ved at overføre en forespørgsel til den underliggende datakilde.

<!--
### Who uses this feature
This feature is intended for model developers. 
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->


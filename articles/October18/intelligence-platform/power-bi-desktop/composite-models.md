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
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: f32678967b820a258a7ad9a37325f99bf11a6cc7
ms.contentlocale: da-dk
ms.lasthandoff: 08/16/2018

---

# <a name="composite-models-public-preview"></a><span data-ttu-id="19ca4-103">Sammensatte modeller (offentlig prøveversion)</span><span class="sxs-lookup"><span data-stu-id="19ca4-103">Composite models (Public Preview)</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

<span data-ttu-id="19ca4-104">Med sammensatte modeller kan du blande importkilder og DirectQuery-kilder i tabelformat og have flere DirectQuery-kilder i tabelformat.</span><span class="sxs-lookup"><span data-stu-id="19ca4-104">Composite models allow you to mix import and tabular direct query sources as well as have multiple tabular DirectQuery sources.</span></span> <span data-ttu-id="19ca4-105">På denne måde kan du udvide din virksomheds datamodeller med importerede tabeller.</span><span class="sxs-lookup"><span data-stu-id="19ca4-105">This lets you augment your enterprise data models with imported tables.</span></span> 

<span data-ttu-id="19ca4-106">Modeludviklere kan oprette en Power BI Desktop-fil ud fra en DirectQuery-datakilde og derefter tilføje tabeller, der er importeret fra en anden datakilde.</span><span class="sxs-lookup"><span data-stu-id="19ca4-106">Modelers can create a Power BI Desktop file over a DirectQuery datasource, and then also add tables that are imported from another data source.</span></span> <span data-ttu-id="19ca4-107">For at understøtte denne nye modelstruktur indfører vi også mange til mange-relationer og tabeller, der er i dobbelttilstand, hvilket betyder, at de kan fungere som import eller DirectQuery, afhængigt af hvilke andre tabeller du føjer til de visuelle elementer.</span><span class="sxs-lookup"><span data-stu-id="19ca4-107">To support this new model structure, we also are introducing many-to-many relationships and tables that are in dual mode, which means they can act as import or DirectQuery, depending on what other tables you add to the visuals.</span></span> <span data-ttu-id="19ca4-108">Power BI giver derefter intelligente svar på dine analyser, enten fra de importerede data eller ved at overføre en forespørgsel til den underliggende datakilde.</span><span class="sxs-lookup"><span data-stu-id="19ca4-108">Power BI will then intelligently serve answers to your analyses from either the imported data or by pushing a query to the underlying datasource.</span></span>

<!--
### Who uses this feature
This feature is intended for model developers. 
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->


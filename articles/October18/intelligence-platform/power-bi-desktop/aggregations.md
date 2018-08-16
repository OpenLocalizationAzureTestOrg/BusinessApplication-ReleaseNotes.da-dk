---
title: Aggregeringer
description: "Understøttelse af cachelagring af aggregerede forespørgsler, samtidig med at brugerne kan analysere ned til detaljeringsniveau via DirectQuery"
author: MI77
manager: kimani
ms.date: 7/22/18
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: willthom
audience: developer, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: ec6fc313ef498181725c0e131d0e2ec1a91a90ce
ms.contentlocale: da-dk
ms.lasthandoff: 08/16/2018

---

# <a name="aggregations-public-preview"></a><span data-ttu-id="121f6-103">Aggregeringer (offentlig prøveversion)</span><span class="sxs-lookup"><span data-stu-id="121f6-103">Aggregations (Public Preview)</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

<span data-ttu-id="121f6-104">Store datamængder kræver nye måder at lagre oplysninger på for at afveje behovet for en detaljeret interaktiv analyse med rapportering på detaljeringsniveau.</span><span class="sxs-lookup"><span data-stu-id="121f6-104">Massive volumes of data require new ways of storing information to balance the needs of slice-and-dice interactive analysis with deep, detail-level reporting.</span></span> <span data-ttu-id="121f6-105">Med aggregeringer kan modeludviklere vise cachelagrede værdier på et højt niveau til interaktiv analyse, men brugerne kan stadig analysere ned til de detaljerede data, der forespørges på fra de underliggende data.</span><span class="sxs-lookup"><span data-stu-id="121f6-105">Aggregations allow model developers to surface cached values at a high level for interactive analysis, but still let users drill down to detailed data that is queried from the underlying data.</span></span>

<span data-ttu-id="121f6-106">Du kan oprette DirectQuery-modeller over datakilder i stor målestok som f.eks. Spark-klynger eller lagre til massive datamængder.</span><span class="sxs-lookup"><span data-stu-id="121f6-106">You can create DirectQuery models over massive-scale data sources such as Spark clusters, or massive data warehouses.</span></span> <span data-ttu-id="121f6-107">Ved interaktiv analyse kan der ikke køres forespørgsler direkte på disse datasæt.</span><span class="sxs-lookup"><span data-stu-id="121f6-107">For interactive analysis, running queries directly against these datasets is impractical.</span></span> <span data-ttu-id="121f6-108">Men for datasæt, der kan være på op til flere hundrede terabyte, kan ikke alle data cachelagres i hukommelsen.</span><span class="sxs-lookup"><span data-stu-id="121f6-108">But for datasets that could be as large as hundreds of terabytes, the data cannot all be cached in memory.</span></span> <span data-ttu-id="121f6-109">Med aggregeringer kan du nøjes med at cachelagre aggregerede data i hukommelsen, hvor der er hurtig adgang til dem.</span><span class="sxs-lookup"><span data-stu-id="121f6-109">Aggregations lets you cache just aggregate data into memory for fast access.</span></span> <span data-ttu-id="121f6-110">Du kan definere tabeller i din datamodel som aggregerede tabeller, der er knyttet til tabeller på detaljeringsniveauet.</span><span class="sxs-lookup"><span data-stu-id="121f6-110">You define tables in your data model as an aggregate table, linked to tables at the detail level.</span></span> 

<span data-ttu-id="121f6-111">Tabellerne med detaljerne forbliver i DirectQuery-tilstand, men aggregeringerne defineres som værende i dobbelt tilstand, så dataene cachelagres også i hukommelsen på det samlede niveau.</span><span class="sxs-lookup"><span data-stu-id="121f6-111">The detail tables stay in DirectQuery mode but the aggregates are defined as being in dual mode so the data is also cached in memory at the aggregate level.</span></span> <span data-ttu-id="121f6-112">Hvis brugerne kører forespørgsler eller opretter visuals, der kan besvares fra cachen i hukommelsen, hentes resultaterne derfra.</span><span class="sxs-lookup"><span data-stu-id="121f6-112">If users run queries or create visuals that can be answered from the in-memory cache, the results are retrieved from there.</span></span> <span data-ttu-id="121f6-113">Men hvis forespørgslen kræver de detaljerede data, overføres den dynamisk til den underliggende DirectQuery-kilde.</span><span class="sxs-lookup"><span data-stu-id="121f6-113">But if the query requires the detail data, it’s pushed down to the underlying DirectQuery source dynamically.</span></span> <span data-ttu-id="121f6-114">Slutbrugerne oplever ikke nogen forskel i deres Power BI-rapport.</span><span class="sxs-lookup"><span data-stu-id="121f6-114">The end user doesn’t see any difference in experience in their Power BI report.</span></span>

<!--
### Who uses this feature
This feature is intended for advanced modelers. It enables them to create data models with aggregate tables linked together to make sure that their end-user reports are designed to encourage filtering of data before queries are served from the DirectQuery source. 
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->


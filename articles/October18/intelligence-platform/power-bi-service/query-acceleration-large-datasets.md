---
title: "Acceleration af forespørgsler til store datasæt"
description: "Acceleration af forespørgsler til store datasæt"
author: MargoC
manager: AnnBe
ms.date: 07/22/2018
ms.assetid: 04524b66-4727-4ce6-9cca-2b1439428497
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: ca50273c7e4a3f49e634536c88398806a2bdb2f4
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---

#  <a name="query-acceleration-for-large-datasets-public-preview"></a><span data-ttu-id="afe3a-103">Acceleration af forespørgsler til store datasæt (offentlig prøveversion)</span><span class="sxs-lookup"><span data-stu-id="afe3a-103">Query acceleration for large datasets (Public Preview)</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



<span data-ttu-id="afe3a-104">Brugerne kan oprette [DirectQuery](https://docs.microsoft.com/power-bi/desktop-directquery-about)-modeller over datakilder af enhver størrelse, f.eks. Spark og Azure SQL Data Warehouse, og derefter fremskynde almindelige forespørgsler ved at oprette aggregeringer over nogle af dataene i hukommelsen.</span><span class="sxs-lookup"><span data-stu-id="afe3a-104">Users can create [DirectQuery](https://docs.microsoft.com/power-bi/desktop-directquery-about) models over any size data in sources, such as Spark and Azure SQL Data Warehouse, and then accelerate common queries by building in-memory aggregations over some of the data.</span></span> <span data-ttu-id="afe3a-105">Almindelige forespørgsler bruger den aggregerede cache til at returnere resultater i et brøkdel af et sekund i stedet for direkte forespørgsler til kilden.</span><span class="sxs-lookup"><span data-stu-id="afe3a-105">Common queries use the aggregated cache to return results in a fraction of a second instead of directly querying the source.</span></span> <span data-ttu-id="afe3a-106">Brugerne kan oprette datasæt af omfattende størrelse og stadig benytte interaktive forespørgsler.</span><span class="sxs-lookup"><span data-stu-id="afe3a-106">Users can create datasets of massive size and still provide interactive querying.</span></span>


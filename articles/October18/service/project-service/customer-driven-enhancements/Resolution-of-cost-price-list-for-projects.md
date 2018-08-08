---
title: "Fortolkning af kostprisliste med flere valutaer på projekter"
description: "Fortolkning af kostprisliste med flere valutaer på projekter"
author: rumant
manager: shellyhaverkamp
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: rumant
audience: developer, admin, end user, citizen developer, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: dc40b9862dcb8c4e8eeb12168ab8497bc131c000
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
#  <a name="resolution-of-multi-currency-cost-price-list-on-projects"></a><span data-ttu-id="5946e-103">Fortolkning af kostprisliste med flere valutaer på projekter</span><span class="sxs-lookup"><span data-stu-id="5946e-103">Resolution of multi-currency cost price list on projects</span></span> 


[!include[banner](../../../../includes/banner.md)]

<span data-ttu-id="5946e-104">Project Service fortolker prislisten for omkostningssatser på projekter ved at sammenligne valutaen i den afdeling, der ejer projektet, med prislistens valuta.</span><span class="sxs-lookup"><span data-stu-id="5946e-104">Project Service resolves the price list for cost rates on projects by matching the currency of the organizational unit that owns the project to the price list currency.</span></span> <span data-ttu-id="5946e-105">I det tilfælde, hvor en prisliste kan have priser i flere valutaer, forventes det, at der er én masterprisliste med omkostningssatslinjer i flere valutaer, og at denne prisliste vil blive brugt af alle projekter globalt.</span><span class="sxs-lookup"><span data-stu-id="5946e-105">In the case where a price list may have prices in multiple currencies, it's expected that there would be one master price list with cost rate lines in multiple currencies, and that this price list would be used by all projects globally.</span></span> 

<span data-ttu-id="5946e-106">I denne situation vil det ikke fungere at fortolke en kostprisliste for et projekt ved hjælp af valutaen i prislistens hoved.</span><span class="sxs-lookup"><span data-stu-id="5946e-106">In that situation, resolving a cost price list for a project using the currency on the header of the price list would not work.</span></span> <span data-ttu-id="5946e-107">Med denne funktion er det muligt at konfigurere standardfortolkningen af projektets kostprisliste.</span><span class="sxs-lookup"><span data-stu-id="5946e-107">With this feature, it will be configurable to set up the default resolution of the project cost price list.</span></span> <span data-ttu-id="5946e-108">De tilgængelige indstillinger vil være at sammenligne projektets omkostningsvaluta med prislistens hoved, sådan som det virker i dag, eller bruge den globalt administrerede prisliste uanset dens valuta i hovedet.</span><span class="sxs-lookup"><span data-stu-id="5946e-108">The options available would be to match the project’s cost currency with the header of the price list as it works today or to use the globally managed price list regardless of its header currency.</span></span>  




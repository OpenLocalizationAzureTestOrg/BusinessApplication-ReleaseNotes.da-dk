---
title: "Valuta for ressourceenhed på rolleprislinjer for omkostninger"
description: Omkostningssatser for ressourcetid kan nu angives i ressourceenhedens valuta
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
ms.openlocfilehash: a40e2adff4c8ca26094dddb8bcc9bd6f8fadaacb
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
#  <a name="resourcing-unit-currency-on-role-price-lines-for-cost"></a><span data-ttu-id="ecec7-103">Valuta for ressourceenhed på rolleprislinjer for omkostninger</span><span class="sxs-lookup"><span data-stu-id="ecec7-103">Resourcing unit currency on role price lines for cost</span></span> 


[!include[banner](../../../../includes/banner.md)]

<span data-ttu-id="ecec7-104">Project Service tillader kun én valuta pr. prisliste, som angives i prislistens hoved.</span><span class="sxs-lookup"><span data-stu-id="ecec7-104">Project Service allows only one currency per price list, which is specified on the price list header.</span></span> <span data-ttu-id="ecec7-105">Prislistelinjen for prissætning af ressourcen er den samme valuta, der er angivet i prislistens hoved.</span><span class="sxs-lookup"><span data-stu-id="ecec7-105">The price list line for resource pricing has the same currency specified on the price list header.</span></span> <span data-ttu-id="ecec7-106">Men for driften af globale projektstyringsfirmaer med centraliserede priser på tværs af deres divisioner og lande kan det kræve en dataintensiv opsætning, hvor de skal oprette en prisliste for hver separat valuta, som de sælger produkter eller beregner omkostninger i.</span><span class="sxs-lookup"><span data-stu-id="ecec7-106">However, for globally operating project service companies that have centralized pricing across all of their divisions across countries, this can necessitate a data-intensive setup where they'll need to set up a price list for each distinct currency that they sell or incur costs in.</span></span> 

<span data-ttu-id="ecec7-107">Med denne funktion giver Project Service mulighed for en valuta på linjeniveau for ressourcepriser, der adskiller sig fra valutaen i prislistens hoved.</span><span class="sxs-lookup"><span data-stu-id="ecec7-107">With this feature, Project Service will allow for a line-level currency for resource prices that differs from the price list header currency.</span></span> <span data-ttu-id="ecec7-108">Valutaen i prislistens hoved bruges som standard på ressourceprislinjer.</span><span class="sxs-lookup"><span data-stu-id="ecec7-108">Currency on the price list header will be used as a default on the resource price lines.</span></span> <span data-ttu-id="ecec7-109">På denne måde kan store globale virksomheder, som ønsker en mere centraliseret prissætning, arbejde med én global prisliste, der angiver ressourcepriser i mange valutaer.</span><span class="sxs-lookup"><span data-stu-id="ecec7-109">This way, large global firms that would like more centralized pricing setup may work with one global price list that specifies resource prices in many currencies.</span></span> <span data-ttu-id="ecec7-110">Det kan også muliggøre scenarier, hvor priser, der administreres af hver enkelt ressourceenhed, bliver samlet på én masterprisliste.</span><span class="sxs-lookup"><span data-stu-id="ecec7-110">This could also enable scenarios where prices managed by each resourcing unit come together as one master price list.</span></span>

<span data-ttu-id="ecec7-111">Brug af en enkelt valuta pr. prisliste vil stadig fungere, hvilket er en fordel for firmaer, der tillader mere decentral prissætning og sporer kurspriser for ressourcer.</span><span class="sxs-lookup"><span data-stu-id="ecec7-111">Using a single currency per price list will still function, which benefits companies that allow for more decentralized pricing and that track exchange prices for resources.</span></span> <span data-ttu-id="ecec7-112">Det kan tilpasses, så ressourcepriserne på en prisliste følger valutaen i prislistens hoved.</span><span class="sxs-lookup"><span data-stu-id="ecec7-112">This can be customized so that the resource prices on a price list follow the currency of the price list header.</span></span>

<span data-ttu-id="ecec7-113">![Prisliste for omkostninger med prislistelinjer i flere valutaer](media/Resourcing-unit-currency-on-pricelist.png "Prisliste for omkostninger med prislistelinjer i flere valutaer")
<!-- Picture 2 --></span><span class="sxs-lookup"><span data-stu-id="ecec7-113">![Price list for cost with price list lines in multiple currencies](media/Resourcing-unit-currency-on-pricelist.png "Price list for cost with price list lines in multiple currencies")
<!-- Picture 2 --></span></span>


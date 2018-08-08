---
title: "Validering af ikrafttrædelsesdato på prislister"
description: "Validering sikrer, at Project Service-brugere undgår fejlagtige priser som følge af, at de har mere end én gældende prisliste for en bestemt dato."
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
ms.openlocfilehash: ebe319f383c161cea41fe8d483206b72f9244de7
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
#   <a name="date-effectivity-validation-on-price-lists"></a><span data-ttu-id="eed58-103">Validering af ikrafttrædelsesdato på prislister</span><span class="sxs-lookup"><span data-stu-id="eed58-103">Date effectivity validation on price lists</span></span>


[!include[banner](../../../../includes/banner.md)]


<span data-ttu-id="eed58-104">Denne funktion sikrer, at Project Service-brugere undgår fejlagtige priser som følge af, at de har mere end én gældende prisliste for en bestemt dato.</span><span class="sxs-lookup"><span data-stu-id="eed58-104">This feature ensures that Project Service users avoid errors in price defaulting arising from having more than one price list effective for a certain date.</span></span> <span data-ttu-id="eed58-105">Som Project Service-kunder er opmærksomme på, kan de arbejde med flere projektprislister, der kan knyttes til tilbud, projektkontrakter og afdelinger.</span><span class="sxs-lookup"><span data-stu-id="eed58-105">As Project Service customers are aware, the product allows for multiple project price lists to be associated to quotes, project contracts, and organizational units.</span></span> <span data-ttu-id="eed58-106">Formålet er at tage højde for inflatoriske prisændringer, som kan forekomme på prislister med forskellige ikrafttrædelsesdatoer.</span><span class="sxs-lookup"><span data-stu-id="eed58-106">This is to allow for inflationary pricing changes represented by price lists with different date effectivities.</span></span> 

<span data-ttu-id="eed58-107">Med denne funktion kan systemet validere opsætningen af prislisten for at sikre, at der ikke er nogen overlappende ikrafttrædelsesdatoer i en enkelt kontekst, f.eks. et projekt eller en kontrakt.</span><span class="sxs-lookup"><span data-stu-id="eed58-107">With this feature, the system will validate the price list setup to ensure no overlapping date effectivities given a single context such as a project or a contract.</span></span> <span data-ttu-id="eed58-108">Systemet kontrollerer også, at den korrekte prissætning bliver anvendt, når et estimat på et tilbud eller en kontrakt dækker flere prisperioder.</span><span class="sxs-lookup"><span data-stu-id="eed58-108">Also, the system will ensure that when an estimate on a quote or contract spans multiple price periods, the system is able to correctly price the work.</span></span> 


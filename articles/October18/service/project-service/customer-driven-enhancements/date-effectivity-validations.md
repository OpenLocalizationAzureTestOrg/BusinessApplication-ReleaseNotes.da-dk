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
#   <a name="date-effectivity-validation-on-price-lists"></a>Validering af ikrafttrædelsesdato på prislister


[!include[banner](../../../../includes/banner.md)]


Denne funktion sikrer, at Project Service-brugere undgår fejlagtige priser som følge af, at de har mere end én gældende prisliste for en bestemt dato. Som Project Service-kunder er opmærksomme på, kan de arbejde med flere projektprislister, der kan knyttes til tilbud, projektkontrakter og afdelinger. Formålet er at tage højde for inflatoriske prisændringer, som kan forekomme på prislister med forskellige ikrafttrædelsesdatoer. 

Med denne funktion kan systemet validere opsætningen af prislisten for at sikre, at der ikke er nogen overlappende ikrafttrædelsesdatoer i en enkelt kontekst, f.eks. et projekt eller en kontrakt. Systemet kontrollerer også, at den korrekte prissætning bliver anvendt, når et estimat på et tilbud eller en kontrakt dækker flere prisperioder. 


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
#  <a name="resourcing-unit-currency-on-role-price-lines-for-cost"></a>Valuta for ressourceenhed på rolleprislinjer for omkostninger 

[!include[project-service banner](../../../includes/project-service.md)]




Project Service tillader kun én valuta pr. prisliste, som angives i prislistens hoved. Prislistelinjen for prissætning af ressourcen er den samme valuta, der er angivet i prislistens hoved. Men for driften af globale projektstyringsfirmaer med centraliserede priser på tværs af deres divisioner og lande kan det kræve en dataintensiv opsætning, hvor de skal oprette en prisliste for hver separat valuta, som de sælger produkter eller beregner omkostninger i. 

Med denne funktion giver Project Service mulighed for en valuta på linjeniveau for ressourcepriser, der adskiller sig fra valutaen i prislistens hoved. Valutaen i prislistens hoved bruges som standard på ressourceprislinjer. På denne måde kan store globale virksomheder, som ønsker en mere centraliseret prissætning, arbejde med én global prisliste, der angiver ressourcepriser i mange valutaer. Det kan også muliggøre scenarier, hvor priser, der administreres af hver enkelt ressourceenhed, bliver samlet på én masterprisliste.

Brug af en enkelt valuta pr. prisliste vil stadig fungere, hvilket er en fordel for firmaer, der tillader mere decentral prissætning og sporer kurspriser for ressourcer. Det kan tilpasses, så ressourcepriserne på en prisliste følger valutaen i prislistens hoved.

![Prisliste for omkostninger med prislistelinjer i flere valutaer](media/Resourcing-unit-currency-on-pricelist.png "Prisliste for omkostninger med prislistelinjer i flere valutaer")
<!-- Picture 2 -->


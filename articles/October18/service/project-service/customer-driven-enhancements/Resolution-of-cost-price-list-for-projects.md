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
#  <a name="resolution-of-multi-currency-cost-price-list-on-projects"></a>Fortolkning af kostprisliste med flere valutaer på projekter 

[!include[project-service banner](../../../includes/project-service.md)]




Project Service fortolker prislisten for omkostningssatser på projekter ved at sammenligne valutaen i den afdeling, der ejer projektet, med prislistens valuta. I det tilfælde, hvor en prisliste kan have priser i flere valutaer, forventes det, at der er én masterprisliste med omkostningssatslinjer i flere valutaer, og at denne prisliste vil blive brugt af alle projekter globalt. 

I denne situation vil det ikke fungere at fortolke en kostprisliste for et projekt ved hjælp af valutaen i prislistens hoved. Med denne funktion er det muligt at konfigurere standardfortolkningen af projektets kostprisliste. De tilgængelige indstillinger vil være at sammenligne projektets omkostningsvaluta med prislistens hoved, sådan som det virker i dag, eller bruge den globalt administrerede prisliste uanset dens valuta i hovedet.  




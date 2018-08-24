---
title: "Konfiguration af en tidsenhed til forkalkulation af arbejdet på projektopgaver"
description: "Forkalkulation af arbejdsindsatsen på projektopgaver ved hjælp af en konfigurerbar tidsenhed"
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
ms.openlocfilehash: 25e88afe31f492f72f29e3fde9ce38530ecc1291
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
#  <a name="configure-a-unit-of-time-for-estimating-work-on-project-tasks"></a>Konfiguration af en tidsenhed til forkalkulation af arbejdet på projektopgaver

[!include[project-service banner](../../../includes/project-service.md)]




Project Service bruger *time* som den eneste tidsenhed til forkalkulation af arbejdsindsatsen for en projektopgave. I mange områder af verden foretages forkalkulation i "arbejdsdage", hvor hvert land eller område har sin særskilte definition af, hvor mange timer en typisk arbejdsdag består af. Afhængigt af hvilken afdeling der ejer leveringen af projektet, skal den enhed, der anvendes til forkalkulation i projektet, derfor som standard være denne afdelings definition af en arbejdsdag. 

Med denne funktion kan hver afdeling angive en arbejdskalender og en foretrukken enhed til forkalkulation af indsatsen. Alle projekter, der ejes af denne afdeling, skal derefter bruge denne arbejdskalender og denne enhed til forkalkulation. 

Se et eksempel: Hvis Contoso Scotland har arbejdsdage på 7,5 time, og virksomhedens foretrukne forkalkulationsenhed for arbejdsindsatsen er en "Skotsk arbejdsdag", skal alle projekter, der ejes af Contoso Scotland, herefter bruge Skotsk arbejdsdag som forkalkulationsenhed, og multiplikatoren 7,5 skal bruges til at oversætte forkalkulationen til timer. 

## <a name="setting-up-time-unit-and-calendar-on-the-organizational-unit"></a>Konfiguration af tidsenhed og kalender for afdelingen

![Konfiguration af tidsenhed og kalender for afdelingen](media/Setting-time-unit-on-the-orgunit.png "Konfiguration af tidsenhed og kalender for afdelingen")

## <a name="defaulting-time-unit-and-calendar-on-the-project-from-the-settings-on-the-organizational-unit"></a>Den tidsenhed og kalender, der bruges som standard i projektet, fra indstillingerne for afdelingen

![Den tidsenhed og kalender, der bruges som standard i projektet](media/Defaulting-time-unit-calendar-on-the-project.png "Den tidsenhed og kalender, der bruges som standard i projektet")
<!-- Picture 2 -->


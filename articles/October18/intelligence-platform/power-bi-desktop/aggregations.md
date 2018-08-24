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
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 40cbd22fb19eb8a5799b6ccb8a9ea5eec6a1576f
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---

# <a name="aggregations-public-preview"></a>Aggregeringer (offentlig prøveversion)

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

Store datamængder kræver nye måder at lagre oplysninger på for at afveje behovet for en detaljeret interaktiv analyse med rapportering på detaljeringsniveau. Med aggregeringer kan modeludviklere vise cachelagrede værdier på et højt niveau til interaktiv analyse, men brugerne kan stadig analysere ned til de detaljerede data, der forespørges på fra de underliggende data.

Du kan oprette DirectQuery-modeller over datakilder i stor målestok som f.eks. Spark-klynger eller lagre til massive datamængder. Ved interaktiv analyse kan der ikke køres forespørgsler direkte på disse datasæt. Men for datasæt, der kan være på op til flere hundrede terabyte, kan ikke alle data cachelagres i hukommelsen. Med aggregeringer kan du nøjes med at cachelagre aggregerede data i hukommelsen, hvor der er hurtig adgang til dem. Du kan definere tabeller i din datamodel som aggregerede tabeller, der er knyttet til tabeller på detaljeringsniveauet. 

Tabellerne med detaljerne forbliver i DirectQuery-tilstand, men aggregeringerne defineres som værende i dobbelt tilstand, så dataene cachelagres også i hukommelsen på det samlede niveau. Hvis brugerne kører forespørgsler eller opretter visuals, der kan besvares fra cachen i hukommelsen, hentes resultaterne derfra. Men hvis forespørgslen kræver de detaljerede data, overføres den dynamisk til den underliggende DirectQuery-kilde. Slutbrugerne oplever ikke nogen forskel i deres Power BI-rapport.

<!--
### Who uses this feature
This feature is intended for advanced modelers. It enables them to create data models with aggregate tables linked together to make sure that their end-user reports are designed to encourage filtering of data before queries are served from the DirectQuery source. 
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->


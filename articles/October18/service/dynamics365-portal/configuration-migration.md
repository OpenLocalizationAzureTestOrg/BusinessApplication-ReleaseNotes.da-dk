---
title: "Konfigurationsoverførsel"
description: "Overføre din Dynamics 365 Portal-konfiguration fra ét miljø til et andet"
author: sandhangitmsft
manager: ramalingamkrishnan
ms.date: 7/22/2018
ms.assetid: f454a2d3-c047-4a57-8a9f-7ddf38781971
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: sandhan
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 2f1b97389e79909e67c1f60ab00862dbb805ccf3
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
# <a name="configuration-migration"></a>Konfigurationsoverførsel

[!include[banner](../../../includes/banner.md)]


Udvikling af portaler kræver flere konfigurationer og tilpasninger, før du kan give portalens slutbrugere den ønskede oplevelse. Hvis du vil reducere den tid og arbejdsindsats, der kræves for at administrere portalkonfigurationen på tværs af miljøer, kan du bruge det skema til konfiguration af overførslen, vi udgiver, som fungerer med [SDK-værktøjet Configuration Migration](https://technet.microsoft.com/library/dn647421.aspx).

Portaler kan tilpasses på mange måder, herunder gennem oprettelse af skemafiler fra bunden, så SDK-værktøjet Configuration Migration kan flytte konfigurationer til forskellige miljøer, typisk udviklings-, test- og produktionsmiljøer. Oprettelse af skemaer fra bunden kan være tidskrævende og kan undertiden forårsage delvise dataoverførsler. Desuden kan de være fejlbehæftede.

Alle funktioner i SDK-værktøjet Configuration Migration kan bruges sammen med dette skema til at administrere portalkonfiguration:

 - **Opret skema**: Skemaet kan tilpasses til implementeringen med de standardmetoder, der leveres af værktøjet. Skemafiler kan indlæses i værktøjet og ændres for at tilføje, fjerne og redigere objekter, attributter og så videre, så de passer til overførselsbehovet.
 - **Eksportér data**: Brug skemafilen til at eksportere data fra et miljø til en .zip-fil, og brug den til sikkerhedskopiering, versionsstyring eller import til et målmiljø.
 - **Importér data**: Brug de eksporterede data til import til et målmiljø.

<!--
### Who uses this feature
This feature is intended for administrators and customizers who need to migrate their portal configuration between environments.
## Status
### Development status
Generally available
#### Target timeframe
October 2018
### Availability
Cloud
### Regional availability
Global
-->

## <a name="wed-like-to-thank"></a>Tak!

Tak for din indsendelse af [denne ide](https://experience.dynamics.com/ideas/idea/?ideaid=b75ece29-1481-e611-80c1-00155d460f3c) med stemmer og kommentarer, som har hjulpet os med at prioritere den.



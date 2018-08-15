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
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 337b55b8f25273b3934a03e9821648590d55098c
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---
# <a name="configuration-migration"></a><span data-ttu-id="12435-103">Konfigurationsoverførsel</span><span class="sxs-lookup"><span data-stu-id="12435-103">Configuration migration</span></span>

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]




<span data-ttu-id="12435-104">Udvikling af portaler kræver flere konfigurationer og tilpasninger, før du kan give portalens slutbrugere den ønskede oplevelse.</span><span class="sxs-lookup"><span data-stu-id="12435-104">Portal development involves several configurations and customizations to achieve a desired experience for portal end users.</span></span> <span data-ttu-id="12435-105">Hvis du vil reducere den tid og arbejdsindsats, der kræves for at administrere portalkonfigurationen på tværs af miljøer, kan du bruge det skema til konfiguration af overførslen, vi udgiver, som fungerer med [SDK-værktøjet Configuration Migration](https://technet.microsoft.com/library/dn647421.aspx).</span><span class="sxs-lookup"><span data-stu-id="12435-105">To reduce the time and effort required to manage portal configuration across environments, we are publishing schema for configuration migration that works with the [Configuration Migration SDK tool](https://technet.microsoft.com/library/dn647421.aspx).</span></span>

<span data-ttu-id="12435-106">Portaler kan tilpasses på mange måder, herunder gennem oprettelse af skemafiler fra bunden, så SDK-værktøjet Configuration Migration kan flytte konfigurationer til forskellige miljøer, typisk udviklings-, test- og produktionsmiljøer.</span><span class="sxs-lookup"><span data-stu-id="12435-106">Portal customizers use various ways, including creation of schema files from scratch, for the Configuration Migration SDK tool to move configurations to different environments, typically development, test, and production.</span></span> <span data-ttu-id="12435-107">Oprettelse af skemaer fra bunden kan være tidskrævende og kan undertiden forårsage delvise dataoverførsler. Desuden kan de være fejlbehæftede.</span><span class="sxs-lookup"><span data-stu-id="12435-107">Creating schema from scratch can be time-consuming, sometimes causing partial data migration, and can be error-prone.</span></span>

<span data-ttu-id="12435-108">Alle funktioner i SDK-værktøjet Configuration Migration kan bruges sammen med dette skema til at administrere portalkonfiguration:</span><span class="sxs-lookup"><span data-stu-id="12435-108">All Configuration Migration SDK tool capabilities can be used with this schema to manage portal configuration:</span></span>

 - <span data-ttu-id="12435-109">**Opret skema**: Skemaet kan tilpasses til implementeringen med de standardmetoder, der leveres af værktøjet.</span><span class="sxs-lookup"><span data-stu-id="12435-109">**Create schema**: The schema can be tailored for the implementation using standard ways provided by the tool.</span></span> <span data-ttu-id="12435-110">Skemafiler kan indlæses i værktøjet og ændres for at tilføje, fjerne og redigere objekter, attributter og så videre, så de passer til overførselsbehovet.</span><span class="sxs-lookup"><span data-stu-id="12435-110">Schema files can be loaded in the tool and altered to add, remove, and modify entities, attributes, and so on to suit configuration migration needs.</span></span>
 - <span data-ttu-id="12435-111">**Eksportér data**: Brug skemafilen til at eksportere data fra et miljø til en .zip-fil, og brug den til sikkerhedskopiering, versionsstyring eller import til et målmiljø.</span><span class="sxs-lookup"><span data-stu-id="12435-111">**Export data**: Use the schema file to export data from an environment into a .zip file, and use it for backup, source control, or importing into a target environment.</span></span>
 - <span data-ttu-id="12435-112">**Importér data**: Brug de eksporterede data til import til et målmiljø.</span><span class="sxs-lookup"><span data-stu-id="12435-112">**Import data**: Use the exported data to import into a target environment.</span></span>

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

## <a name="wed-like-to-thank"></a><span data-ttu-id="12435-113">Tak!</span><span class="sxs-lookup"><span data-stu-id="12435-113">We'd like to thank</span></span>

<span data-ttu-id="12435-114">Tak for din indsendelse af [denne ide](https://experience.dynamics.com/ideas/idea/?ideaid=b75ece29-1481-e611-80c1-00155d460f3c) med stemmer og kommentarer, som har hjulpet os med at prioritere den.</span><span class="sxs-lookup"><span data-stu-id="12435-114">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=b75ece29-1481-e611-80c1-00155d460f3c) with votes and comments that helped us prioritize it.</span></span>



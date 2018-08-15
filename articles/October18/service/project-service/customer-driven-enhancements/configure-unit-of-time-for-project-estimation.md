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
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 3d9c093dc2928be990b3737ca3d94d61a485c9a9
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---
#  <a name="configure-a-unit-of-time-for-estimating-work-on-project-tasks"></a><span data-ttu-id="9baa3-103">Konfiguration af en tidsenhed til forkalkulation af arbejdet på projektopgaver</span><span class="sxs-lookup"><span data-stu-id="9baa3-103">Configure a unit of time for estimating work on project tasks</span></span>

[!include[project-service banner](../../../includes/project-service.md)]




<span data-ttu-id="9baa3-104">Project Service bruger *time* som den eneste tidsenhed til forkalkulation af arbejdsindsatsen for en projektopgave.</span><span class="sxs-lookup"><span data-stu-id="9baa3-104">Project Service uses *hour* as the only time unit for estimating work effort on a project task.</span></span> <span data-ttu-id="9baa3-105">I mange områder af verden foretages forkalkulation i "arbejdsdage", hvor hvert land eller område har sin særskilte definition af, hvor mange timer en typisk arbejdsdag består af.</span><span class="sxs-lookup"><span data-stu-id="9baa3-105">In many regions across the world, estimation is done in “work days,” with each country or region having its own definition of how many hours are in a typical work day.</span></span> <span data-ttu-id="9baa3-106">Afhængigt af hvilken afdeling der ejer leveringen af projektet, skal den enhed, der anvendes til forkalkulation i projektet, derfor som standard være denne afdelings definition af en arbejdsdag.</span><span class="sxs-lookup"><span data-stu-id="9baa3-106">Therefore, depending on which division owns the delivery of the project, the unit of estimation on the project must default to that division's definition of work day.</span></span> 

<span data-ttu-id="9baa3-107">Med denne funktion kan hver afdeling angive en arbejdskalender og en foretrukken enhed til forkalkulation af indsatsen.</span><span class="sxs-lookup"><span data-stu-id="9baa3-107">With this feature, each organizational unit will be able to identify a working calendar and specify a preferred unit for estimating effort.</span></span> <span data-ttu-id="9baa3-108">Alle projekter, der ejes af denne afdeling, skal derefter bruge denne arbejdskalender og denne enhed til forkalkulation.</span><span class="sxs-lookup"><span data-stu-id="9baa3-108">All projects owned by that that organizational unit will then use that working calendar and that unit for estimating effort.</span></span> 

<span data-ttu-id="9baa3-109">Se et eksempel: Hvis Contoso Scotland har arbejdsdage på 7,5 time, og virksomhedens foretrukne forkalkulationsenhed for arbejdsindsatsen er en "Skotsk arbejdsdag", skal alle projekter, der ejes af Contoso Scotland, herefter bruge Skotsk arbejdsdag som forkalkulationsenhed, og multiplikatoren 7,5 skal bruges til at oversætte forkalkulationen til timer.</span><span class="sxs-lookup"><span data-stu-id="9baa3-109">Consider an example: If Contoso Scotland works 7.5-hour days and its preferred unit for estimating effort is a “Scottish working day,” then all projects owned by Contoso Scotland will use Scottish working day as the unit of estimation, and the multiplier of 7.5 will be used to translate that estimate into hours.</span></span> 

## <a name="setting-up-time-unit-and-calendar-on-the-organizational-unit"></a><span data-ttu-id="9baa3-110">Konfiguration af tidsenhed og kalender for afdelingen</span><span class="sxs-lookup"><span data-stu-id="9baa3-110">Setting up time unit and calendar on the organizational unit</span></span>

<span data-ttu-id="9baa3-111">![Konfiguration af tidsenhed og kalender for afdelingen](media/Setting-time-unit-on-the-orgunit.png "Konfiguration af tidsenhed og kalender for afdelingen")</span><span class="sxs-lookup"><span data-stu-id="9baa3-111">![Setting up time unit and calendar on the Org. Unit](media/Setting-time-unit-on-the-orgunit.png "Setting up time unit and calendar on the organizational unit")</span></span>

## <a name="defaulting-time-unit-and-calendar-on-the-project-from-the-settings-on-the-organizational-unit"></a><span data-ttu-id="9baa3-112">Den tidsenhed og kalender, der bruges som standard i projektet, fra indstillingerne for afdelingen</span><span class="sxs-lookup"><span data-stu-id="9baa3-112">Defaulting time unit and calendar on the project from the settings on the organizational unit</span></span>

<span data-ttu-id="9baa3-113">![Den tidsenhed og kalender, der bruges som standard i projektet](media/Defaulting-time-unit-calendar-on-the-project.png "Den tidsenhed og kalender, der bruges som standard i projektet")
<!-- Picture 2 --></span><span class="sxs-lookup"><span data-stu-id="9baa3-113">![Defaulting time unit and calendar on the project](media/Defaulting-time-unit-calendar-on-the-project.png "Defaulting time unit and calendar on the project")
<!-- Picture 2 --></span></span>


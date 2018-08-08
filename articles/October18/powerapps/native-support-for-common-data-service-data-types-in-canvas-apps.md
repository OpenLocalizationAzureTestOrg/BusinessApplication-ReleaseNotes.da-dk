---
title: "Indbygget understøttelse af Common Data Service-datatyper i lærred-apps"
description: Appudviklere kan nemt arbejde med optionsets, GUID'er og datatyper som kun dato og kun dato uden tidszone
author: gregli
manager: AnnBe
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 94039419a4491ff73e7b9b09418e964242036b59
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
# <a name="native-support-for-common-data-service-data-types-in-canvas-apps"></a><span data-ttu-id="1c797-103">Indbygget understøttelse af Common Data Service-datatyper i lærred-apps</span><span class="sxs-lookup"><span data-stu-id="1c797-103">Native support for Common Data Service data types in canvas apps</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="1c797-104">I dag er understøttelse af nogle Common Data Service-datatyper begrænset eller svær at bruge.</span><span class="sxs-lookup"><span data-stu-id="1c797-104">Today, support for some Common Data Service data types is limited or hard to use.</span></span> <span data-ttu-id="1c797-105">Optionset-værdier skal slås op manuelt på udviklerportalen, GUID'er håndteres gennem strenge, der kan skabe problemer i sammenligninger, og der opstår problemer med tidszoner med kun dato- og dato/tid-felter.</span><span class="sxs-lookup"><span data-stu-id="1c797-105">Optionset values must be looked up manually on the maker portal, GUIDs are handled through strings that can cause problems in comparisons, and there are time zone issues with date only and date/time fields.</span></span>

<span data-ttu-id="1c797-106">Denne funktion løser alle disse problemer ved at tilføje indbygget understøttelse af optionsets og GUID'er samt forbedre håndteringen af tidszoner for dato/tid-værdier.</span><span class="sxs-lookup"><span data-stu-id="1c797-106">This feature cleans all that up, adding native support for optionsets and GUIDs and improving the time zone handling for date/time values.</span></span>


---
title: "Microsoft Dynamics 365 for Finance and Operations – Lovpligtige tjenester, Konfigurationstjeneste"
description: I dette emne beskrives den konfigurationstjeneste, der frigives som en del af Microsoft Dynamics 365 for Finance and Operations - Lovpligtige tjenester.
author: JaneA07
manager: sshvedov
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: janeaug
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: e56816ca696ce846b0a629daf670c9b04b14ca70
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
#  <a name="microsoft-dynamics-365-for-finance-and-operations---regulatory-services-configuration-service"></a><span data-ttu-id="ba3b9-103">Microsoft Dynamics 365 for Finance and Operations – Lovpligtige tjenester, Konfigurationstjeneste</span><span class="sxs-lookup"><span data-stu-id="ba3b9-103">Microsoft Dynamics 365 for Finance and Operations - Regulatory Services, Configuration service</span></span> 


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="ba3b9-104">Konfigurationstjenesten Microsoft Dynamics 365 for Finance and Operations - Lovpligtige tjenester er udviklingen af det lovpligtige konfigurationsværktøj (også kaldet Elektronisk rapportering).</span><span class="sxs-lookup"><span data-stu-id="ba3b9-104">The Microsoft Dynamics 365 for Finance and Operations - Regulatory Services, Configuration service is the evolution of the regulatory configuration tool (also known as Electronic Reporting).</span></span> <span data-ttu-id="ba3b9-105">Med konfigurationstjenesten kan partnere og kunder, der bruger flere versioner af Microsoft Dynamics 365 for Finance and Operations og tidligere versioner af Microsoft Dynamics AX (f.eks. AX 2012 og AX 2009 for Indien), konfigurere lovpligtige funktioner én gang og bruge én fælles tjeneste.</span><span class="sxs-lookup"><span data-stu-id="ba3b9-105">The Configuration service allows partners and customers using multiple versions of Microsoft Dynamics 365 for Finance and Operations and earlier Microsoft Dynamics AX versions (such as AX 2012 and AX 2009 for India only) to configure regulatory features only once using a common service.</span></span> <span data-ttu-id="ba3b9-106">Konfigurationstjenesten er baseret på programmering uden kode, hvilket giver superbrugere mulighed for at konfigurere krav, der ændres ofte, til lovpligtige rapporter, e-fakturaer, betalingsformater og momsregler i stedet for at skrive kode i flere programmer.</span><span class="sxs-lookup"><span data-stu-id="ba3b9-106">The Configuration service targets a no-code programming approach, allowing power users to configure frequently changed legal requirements for regulatory reports, e-invoices, payment formats and tax rules, rather than writing code in multiple applications.</span></span> 

<span data-ttu-id="ba3b9-107">Konfigurationstjenesten er den første komponent i Lovpligtige tjenester, der frigives.</span><span class="sxs-lookup"><span data-stu-id="ba3b9-107">The Configuration service is the first component of Regulatory Services to be released.</span></span> <span data-ttu-id="ba3b9-108">Lovpligtige tjenester vil tilbyde funktionalitet, der kan integreres med et virksomhedsprogram.</span><span class="sxs-lookup"><span data-stu-id="ba3b9-108">Regulatory Services will provide functionality that can be integrated with any business application.</span></span> <span data-ttu-id="ba3b9-109">Med denne tjeneste kan udviklere bygge programmer med fokus på deres kernefunktioner i stedet for at prøve at overholde det stigende antal juridiske krav, de bliver mødt med overalt i verden.</span><span class="sxs-lookup"><span data-stu-id="ba3b9-109">This service allows developers building applications to focus on their core functionality rather than worrying about meeting the increasing number of legal requirements around the globe.</span></span> 

<span data-ttu-id="ba3b9-110">Konfigurationstjenesten leverer følgende funktioner:</span><span class="sxs-lookup"><span data-stu-id="ba3b9-110">The Configuration service provides the following capabilities:</span></span>

-   <span data-ttu-id="ba3b9-111">Adgang for visual-designere til at konfigurere lovpligtige rapporter, e-fakturaer, betalingsformater, momsregler og andre lovpligtige funktioner.</span><span class="sxs-lookup"><span data-stu-id="ba3b9-111">Access to visual designers to configure regulatory reports, e-invoices, payment formats, tax rules, and other regulatory features.</span></span> 
-   <span data-ttu-id="ba3b9-112">Metadata, der giver mulighed for enten at importere en beskrivelse af destinationsprogrammets artefakter, f.eks. datatabeller, fasttekst og klasser, eller bruge forbundne programmer til at få adgang til metadata.</span><span class="sxs-lookup"><span data-stu-id="ba3b9-112">Metadata that provides the ability to either import a description of the target application’s artifacts, such as data tables, enumeration, and classes, or use connected applications for accessing metadata.</span></span> <span data-ttu-id="ba3b9-113">Metadata bruges på designtidspunktet til at definere datakilder for en tilknytningsversion af datamodellen.</span><span class="sxs-lookup"><span data-stu-id="ba3b9-113">Metadata is used at design time to define data sources of a data model mapping version.</span></span> 
-   <span data-ttu-id="ba3b9-114">Understøttelse af internationale installationer, så brugerne kan vælge, hvilket område deres data opbevares i.</span><span class="sxs-lookup"><span data-stu-id="ba3b9-114">Support for regional deployments to enable users to select what region their data is held in.</span></span> <span data-ttu-id="ba3b9-115">Der vil være et begrænset sæt af tilgængelige lande i den første GT-produktfrigivelse, men de øvrige kommer til i senere produktfrigivelser.</span><span class="sxs-lookup"><span data-stu-id="ba3b9-115">There will be a limited set of countries available with the initial GA release, but these will be added to over later releases.</span></span>    

## <a name="regional-availability"></a><span data-ttu-id="ba3b9-116">Tilgængelighed i geografiske områder</span><span class="sxs-lookup"><span data-stu-id="ba3b9-116">Regional availability</span></span>
<span data-ttu-id="ba3b9-117">Når konfigurationstjenesten bliver alment tilgængelig, vil den være det i alle de områder, hvor Finance and Operations er tilgængelig.</span><span class="sxs-lookup"><span data-stu-id="ba3b9-117">When the Configuration service is generally available, it will be available in all regions in which Finance and Operations is available.</span></span> <span data-ttu-id="ba3b9-118">Men data vil dog indledningsvist kun have et datacenter i USA som vært.</span><span class="sxs-lookup"><span data-stu-id="ba3b9-118">However, data will be initially hosted only in a US datacenter.</span></span>

<span data-ttu-id="ba3b9-119">Du kan se den fulde liste over områder i [Vejledning om international tilgængelighed i Dynamics 365](https://aka.ms/dynamics_365_international_availability_deck).</span><span class="sxs-lookup"><span data-stu-id="ba3b9-119">For a complete list of regions, see the [Dynamics 365 International Availability Guide](https://aka.ms/dynamics_365_international_availability_deck).</span></span>


---
title: "Mere avanceret og ensartet økosystem af connectorer og udviklere"
description: "Mere avanceret og ensartet økosystem af connectorer og udviklere"
author: shellyhaverkamp
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 64dd4753-dced-47af-8087-0a75f48a4a2d
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: tpalmer
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 1a28b60ca0960084042d198483f7b2789415593d
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---
#  <a name="richer-and-more-unified-connector-and-developer-ecosystem"></a><span data-ttu-id="946f4-103">Mere avanceret og ensartet økosystem af connectorer og udviklere</span><span class="sxs-lookup"><span data-stu-id="946f4-103">Richer and more unified connector and developer ecosystem</span></span>

[!include[data-integration-platform banner](../includes/data-integration-platform.md)]




<span data-ttu-id="946f4-104">En vigtig del af dataintegration og den produktpakke, den understøtter, er forbindelse til eksterne datakilder.</span><span class="sxs-lookup"><span data-stu-id="946f4-104">A critical part of Data Integration and the suite of products it supports is connectivity to external data sources.</span></span> <span data-ttu-id="946f4-105">Mens vi fortsat vil investere i et sæt datakilder for virksomheder, er der et stigende antal databaser og tjenester ved siden af dette sæt, som mange brugere ofte benytter.</span><span class="sxs-lookup"><span data-stu-id="946f4-105">While we continue to invest in a set of enterprise grade data sources, there are a growing number of databases and services many users come to depend on outside of that set.</span></span> <span data-ttu-id="946f4-106">For at sikre at vores brugere kan få adgang til de data, som de har brug for, investerer vi fortsat i vores udvidelsesmuligheder over hele platformen.</span><span class="sxs-lookup"><span data-stu-id="946f4-106">To ensure our users can connect to the data they need, we continue to invest in our extensibility points throughout the platform.</span></span>

## <a name="improved-development-for-connectors-across-the-platform"></a><span data-ttu-id="946f4-107">Forbedret udvikling for connectorer på tværs af platformen</span><span class="sxs-lookup"><span data-stu-id="946f4-107">Improved development for connectors across the platform</span></span>

<span data-ttu-id="946f4-108">Udviklere og uafhængige softwareleverandører, der ønsker at oprette connectorer til vores platform, kan vælge at oprette connectorer med handlinger og udløsere til PowerApps, Microsoft Flow og Logic Apps eller oprette funktionelle dataconnectorer til Power BI.</span><span class="sxs-lookup"><span data-stu-id="946f4-108">Developers and ISVs looking to build connectors for our platform can choose to build connectors with actions and triggers for PowerApps, Microsoft Flow, and Logic Apps, or build rich data connectors for Power BI.</span></span> <span data-ttu-id="946f4-109">Udviklere og uafhængige softwareleverandører kan desuden oprette connectorer til Common Data Service til programmer og Power BI-dataflows ved hjælp af dataintegration.</span><span class="sxs-lookup"><span data-stu-id="946f4-109">Developers and ISVs can additionally build connectors for the Common Data Service for Applications and Power BI dataflows through Data Integration.</span></span> <span data-ttu-id="946f4-110">Uafhængige softwareleverandører, der er interesserede i at understøtte vores komplette platform, kan gøre det nu.</span><span class="sxs-lookup"><span data-stu-id="946f4-110">ISVs interested in supporting our full platform can do so now.</span></span>

<span data-ttu-id="946f4-111">Denne produktfrigivelse indeholder en række forbedringer, som uafhængige softwareleverandører og udviklere kan bruge til at udvikle, teste og frigive deres connectorer på tværs af hele vores platform.</span><span class="sxs-lookup"><span data-stu-id="946f4-111">This release includes a number of improvements for ISVs and developers to build, test, and release their connectors across our entire platform.</span></span>  <span data-ttu-id="946f4-112">Med den generelle tilgængelighed i Power-forespørgsel SDK har udviklere nu adgang til en moderne platform til oprettelse af operationelle connectorer til Power BI, Common Data Service til programmer og Power BI-dataflows.</span><span class="sxs-lookup"><span data-stu-id="946f4-112">With the general availability of the Power Query SDK, developers now have access to a mature platform for building rich connectors for Power BI, Common Data Service for Applications, and Power BI dataflows.</span></span>  <span data-ttu-id="946f4-113">Med et omfattende dokumentations- og eksempelsæt til vejledning af udviklere giver nye funktioner i SDK mulighed for signering, versionsstyring og validering af brugerdefinerede connectorer.</span><span class="sxs-lookup"><span data-stu-id="946f4-113">With a rich set of documentation and samples to guide developers, new features in the SDK allow for signing, versioning, and validation of custom connectors.</span></span>  <span data-ttu-id="946f4-114">Få adgang til [Power-forespørgsel SDK her](https://aka.ms/dataconnectors).</span><span class="sxs-lookup"><span data-stu-id="946f4-114">Access the [Power Query SDK here](https://aka.ms/dataconnectors).</span></span>

<span data-ttu-id="946f4-115">En af funktionerne i prøveversionen er en single-connector, der fungerer på tværs af hele platformen og kan udvikles fra bunden eller oprettes ud fra en eksisterende OpenAPI-definition.</span><span class="sxs-lookup"><span data-stu-id="946f4-115">One of the features in preview is a single connector that works across the full platform, and can be developed from scratch or created from an existing OpenAPI definition.</span></span>  <span data-ttu-id="946f4-116">Udviklere, der er interesserede i at oprette en sådan connector, kan komme i gang ved hjælp af den brugerdefinerede connectorportal i Microsoft PowerApps, Microsoft Flow eller Logic Apps eller med Data Connector SDK'et til Power-forespørgsel, der nu er tilgængeligt.</span><span class="sxs-lookup"><span data-stu-id="946f4-116">Developers interested in building such a connector can get started with the custom connector portal in Microsoft PowerApps, Microsoft Flow or Logic Apps, or with the Power Query Data Connector SDK that is now available.</span></span> <span data-ttu-id="946f4-117">På denne måde kan udviklerne generere de korrekte artefakter til hele platformen.</span><span class="sxs-lookup"><span data-stu-id="946f4-117">It allows developers to generate the correct artifacts for the full platform.</span></span>
<span data-ttu-id="946f4-118">Ud over de aktuelle integrerede testoplevelser i Microsoft Flow og PowerApps kan connectoren downloades til brug med Power BI Desktop eller datagatewayen i det lokale miljø for en komplet afprøvning i disse produkter.</span><span class="sxs-lookup"><span data-stu-id="946f4-118">In addition to the current inline testing experiences in Microsoft Flow and PowerApps, the connector can be downloaded to use with the Power BI Desktop or On-premises Data Gateway for a full end-to-end testing in those products.</span></span>

<span data-ttu-id="946f4-119">![](media/3-richer-more-unified-connector-developer-ecosystem-2.png "Liste over kontakter i Navigator")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="946f4-119">![](media/3-richer-more-unified-connector-developer-ecosystem-2.png "ListContacts in Navigator")
<!-- picture --></span></span>

## <a name="improved-consumption-for-connectors"></a><span data-ttu-id="946f4-120">Forbedret forbrug for connectorer</span><span class="sxs-lookup"><span data-stu-id="946f4-120">Improved consumption for connectors</span></span>
<span data-ttu-id="946f4-121">Med denne produktfrigivelse kan vi nu levere en integreret oplevelse med forbedrede forbrugsoplevelser for connectorer i Power BI Desktop og ved hjælp af datagatewayen i det lokale miljø.</span><span class="sxs-lookup"><span data-stu-id="946f4-121">With this release, we now provide an integrated experience to offer improved consumption experiences for connectors in Power BI Desktop and via the On-premises Data Gateway.</span></span>  <span data-ttu-id="946f4-122">Certificerede connectorer oprettet af partnere og uafhængige softwareleverandører kan nu nemt registreres og bruges i Power BI Desktop.</span><span class="sxs-lookup"><span data-stu-id="946f4-122">Certified connectors built by partners and ISVs can now be easily discovered and used in Power BI Desktop.</span></span>
<span data-ttu-id="946f4-123">Denne integration føjer connectorer til det store antal integrationer og forbedrer oplevelsen for vores udviklere og forbrugere i økosystemet.</span><span class="sxs-lookup"><span data-stu-id="946f4-123">This  integration will add connectors to the large number of integrations and improve experiences for our developers and consumers in the ecosystem.</span></span>  <span data-ttu-id="946f4-124">Både personlige versioner og versioner for virksomheder af datagatewayen i det lokale miljø understøtter nu registrering og dataopdateringer for certificerede og brugerdefinerede connectorer.</span><span class="sxs-lookup"><span data-stu-id="946f4-124">Both the personal and enterprise versions of the On-premises Data Gateway now support discovery and data refreshes for certified and custom connectors.</span></span>

-  [<span data-ttu-id="946f4-125">Understøttelse af certificerede connectorer i Power BI Desktop</span><span class="sxs-lookup"><span data-stu-id="946f4-125">Support for certified connectors in Power BI Desktop</span></span>](1-power-query.md#certified-custom-connectors-in-power-bi-desktop)
-  [<span data-ttu-id="946f4-126">Understøttelse af brugerdefinerede connectorer i den personlige gateway og gatewayen for virksomheder</span><span class="sxs-lookup"><span data-stu-id="946f4-126">Support for custom connectors in the personal and enterprise gateway</span></span>](5-data-gateway.md#certified-custom-connectors-in-power-bi-desktop)


## <a name="unified-connector-certification-program"></a><span data-ttu-id="946f4-127">Samlet connectorcertificeringsprogram</span><span class="sxs-lookup"><span data-stu-id="946f4-127">Unified connector certification program</span></span>
<span data-ttu-id="946f4-128">Udviklere og uafhængige softwareleverandører, der opretter connectorer, kan indsende deres connectorer til Microsoft med henblik på certificering.</span><span class="sxs-lookup"><span data-stu-id="946f4-128">Developers and ISVs building connectors may submit their connectors for certification to Microsoft.</span></span>
<span data-ttu-id="946f4-129">Certificerede connectorer udgives offentligt og giver slutbrugere en integreret oplevelse.</span><span class="sxs-lookup"><span data-stu-id="946f4-129">Certified connectors are released publicly and provide an integrated experience for end users.</span></span>
<span data-ttu-id="946f4-130">Dette øger tjenestens rækkevidde, identificerbarhed og anvendelse.</span><span class="sxs-lookup"><span data-stu-id="946f4-130">It increases the reach, discoverability, and usage of the service.</span></span>

<span data-ttu-id="946f4-131">Alle connectorer, der er oprettet af partnere og opfylder følgende grundlæggende krav, kan indsendes til connectorcertificeringsprogrammet:</span><span class="sxs-lookup"><span data-stu-id="946f4-131">The connector certification program is open to submissions for any partner-built connectors that meet the basic requirements:</span></span>

- <span data-ttu-id="946f4-132">Afsenderen er tilknyttet den tjeneste, connectoren er oprettet ud fra.</span><span class="sxs-lookup"><span data-stu-id="946f4-132">The submitter is affiliated with the service the connector is built against.</span></span>
- <span data-ttu-id="946f4-133">Connectoren understøtter virksomhedsbrugeres scenarier for målplatformen.</span><span class="sxs-lookup"><span data-stu-id="946f4-133">The connector supports business user scenarios for the targeted platform.</span></span>

<span data-ttu-id="946f4-134">Læs mere om [connectorcertificeringsprogrammet](https://aka.ms/connector-certification).</span><span class="sxs-lookup"><span data-stu-id="946f4-134">Read more about the [connector certification program](https://aka.ms/connector-certification).</span></span>



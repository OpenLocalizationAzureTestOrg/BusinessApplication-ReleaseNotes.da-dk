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
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 3b01ce72e354533570465a5953bf12d1412327f5
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
#  <a name="richer-and-more-unified-connector-and-developer-ecosystem"></a>Mere avanceret og ensartet økosystem af connectorer og udviklere


[!include[banner](../../includes/banner.md)]

En vigtig del af dataintegration og den produktpakke, den understøtter, er forbindelse til eksterne datakilder. Mens vi fortsat vil investere i et sæt datakilder for virksomheder, er der et stigende antal databaser og tjenester ved siden af dette sæt, som mange brugere ofte benytter. For at sikre at vores brugere kan få adgang til de data, som de har brug for, investerer vi fortsat i vores udvidelsesmuligheder over hele platformen.

## <a name="improved-development-for-connectors-across-the-platform"></a>Forbedret udvikling for connectorer på tværs af platformen

Udviklere og uafhængige softwareleverandører, der ønsker at oprette connectorer til vores platform, kan vælge at oprette connectorer med handlinger og udløsere til PowerApps, Microsoft Flow og Logic Apps eller oprette funktionelle dataconnectorer til Power BI. Udviklere og uafhængige softwareleverandører kan desuden oprette connectorer til Common Data Service til programmer og Power BI-dataflows ved hjælp af dataintegration. Uafhængige softwareleverandører, der er interesserede i at understøtte vores komplette platform, kan gøre det nu.

Denne produktfrigivelse indeholder en række forbedringer, som uafhængige softwareleverandører og udviklere kan bruge til at udvikle, teste og frigive deres connectorer på tværs af hele vores platform.  Med den generelle tilgængelighed i Power-forespørgsel SDK har udviklere nu adgang til en moderne platform til oprettelse af operationelle connectorer til Power BI, Common Data Service til programmer og Power BI-dataflows.  Med et omfattende dokumentations- og eksempelsæt til vejledning af udviklere giver nye funktioner i SDK mulighed for signering, versionsstyring og validering af brugerdefinerede connectorer.  Få adgang til [Power-forespørgsel SDK her](https://aka.ms/dataconnectors).

En af funktionerne i prøveversionen er en single-connector, der fungerer på tværs af hele platformen og kan udvikles fra bunden eller oprettes ud fra en eksisterende OpenAPI-definition.  Udviklere, der er interesserede i at oprette en sådan connector, kan komme i gang ved hjælp af den brugerdefinerede connectorportal i Microsoft PowerApps, Microsoft Flow eller Logic Apps eller med Data Connector SDK'et til Power-forespørgsel, der nu er tilgængeligt. På denne måde kan udviklerne generere de korrekte artefakter til hele platformen.
Ud over de aktuelle integrerede testoplevelser i Microsoft Flow og PowerApps kan connectoren downloades til brug med Power BI Desktop eller datagatewayen i det lokale miljø for en komplet afprøvning i disse produkter.

![](media/3-richer-more-unified-connector-developer-ecosystem-2.png "Liste over kontakter i Navigator")
<!-- picture -->

## <a name="improved-consumption-for-connectors"></a>Forbedret forbrug for connectorer
Med denne produktfrigivelse kan vi nu levere en integreret oplevelse med forbedrede forbrugsoplevelser for connectorer i Power BI Desktop og ved hjælp af datagatewayen i det lokale miljø.  Certificerede connectorer oprettet af partnere og uafhængige softwareleverandører kan nu nemt registreres og bruges i Power BI Desktop.
Denne integration føjer connectorer til det store antal integrationer og forbedrer oplevelsen for vores udviklere og forbrugere i økosystemet.  Både personlige versioner og versioner for virksomheder af datagatewayen i det lokale miljø understøtter nu registrering og dataopdateringer for certificerede og brugerdefinerede connectorer.

-  [Understøttelse af certificerede connectorer i Power BI Desktop](1-power-query.md#certified-custom-connectors-in-power-bi-desktop)
-  [Understøttelse af brugerdefinerede connectorer i den personlige gateway og gatewayen for virksomheder](5-data-gateway.md#certified-custom-connectors-in-power-bi-desktop)


## <a name="unified-connector-certification-program"></a>Samlet connectorcertificeringsprogram
Udviklere og uafhængige softwareleverandører, der opretter connectorer, kan indsende deres connectorer til Microsoft med henblik på certificering.
Certificerede connectorer udgives offentligt og giver slutbrugere en integreret oplevelse.
Dette øger tjenestens rækkevidde, identificerbarhed og anvendelse.

Alle connectorer, der er oprettet af partnere og opfylder følgende grundlæggende krav, kan indsendes til connectorcertificeringsprogrammet:

- Afsenderen er tilknyttet den tjeneste, connectoren er oprettet ud fra.
- Connectoren understøtter virksomhedsbrugeres scenarier for målplatformen.

Læs mere om [connectorcertificeringsprogrammet](https://aka.ms/connector-certification).



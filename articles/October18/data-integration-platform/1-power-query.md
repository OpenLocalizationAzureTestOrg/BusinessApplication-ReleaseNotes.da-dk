---
title: "Forenklet, smartere transformering og integration af virksomhedsdata med Power-forespørgsel og dataintegrationsplatformen"
description: "Forenklet, smartere transformering og integration af virksomhedsdata med Power-forespørgsel og dataintegrationsplatformen"
author: shellyhaverkamp
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 4870e3a2-ac78-4f21-be77-0ddf0ce91282
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: tpalmer
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 94765585de94995c31436ad1b6b801aefa0389ce
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
#  <a name="simpler-smarter-transformation-and-integration-of-enterprise-data-with-power-query-and-data-integration-platform"></a>Forenklet, smartere transformering og integration af virksomhedsdata med Power-forespørgsel og dataintegrationsplatformen

[!include[data-integration-platform banner](../includes/data-integration-platform.md)]




Vi har gjort det nemmere at håndtere typiske dataintegrationsproblemer i virksomheder ved at udvikle:

- Nye funktioner til dataforberedelse i forbindelse med Power-forespørgsler.
- Connectorer for virksomheder.
- Forbedringer af Common Data Service-dataintegration.

## <a name="new-power-query-data-preparation-capabilities"></a>Nye funktioner til dataforberedelse i forbindelse med Power-forespørgsel

Power-forespørgsel er væsentligt forbedret med markedets førende oplevelser inden for *Smart dataforberedelse*, herunder:

-   Udtræk af data fra semistrukturerede kilder, f.eks. PDF-filer.
-   HTML-sider.
-   Fuzzy matching-algoritmer til at rationalisere og normalisere data baseret på lighedsmønstre.
-   Funktioner til dataprofilering.

Disse funktioner gør det nemmere at identificere fejl og afvigelser som en del af arbejdet med dataforberedelse i Power-forespørgselseditoren.

![](media/power-query-becomes-more-powerful-smarter-1.jpg "Power-forespørgsel bliver smartere og mere effektiv")
<!-- picture -->


Microsoft udnytter sin førende position inden for kunstig intelligens, der er baseret på flere års investering i forskellige projekter under Microsoft Research, og tilføjer disse funktioner til Smart dataforberedelse i Power-forespørgsel. Dette gør dem lettilgængelige for millioner af forretningsbrugere på tværs af forskellige Microsoft-produkter og -tjenester (Excel, Power BI, Common Data Service til apps og Microsoft Flow).

### <a name="intelligent-transforms-and-ai-support-in-power-query"></a>Intelligente transformeringer og understøttelse af kunstig intelligens i Power-forespørgsel 

Forretningsanalytikerne kan let integrere indsigt baseret på kunstig intelligens med adgang til transformeringer baseret på kunstig intelligens med et enkelt klik. De indledende funktioner inden for dette område omfatter synspunktsanalyse og udtræk af en tekst på et naturligt sprog. Yderligere funktioner som f.eks. OCR og billedanalyse kan tilføjes over tid.

Analytikere og BI-medarbejdere får adgang til nye standardfunktioner og API'er til transformationer, der er baseret på kunstig intelligens. Dette muliggør transformeringer af kolonner til synspunktanalyse og udtræk af nøgleord med et enkelt klik på en knap eller med en enkelt scriptlinje, f.eks. "ApplySentimentIndex([textResponse])".

API'er i forbindelse med Power-forespørgsel understøttes også til brug under installation og konfiguration af Power BI-programmer, der gør brug af dataflows. I dette tilfælde vil batchbehandling af transformeringer for kolonnen føres problemfrit til en Cognitive Services-container, der kører som en del af en kundes Power BI Premium-kapacitet.

### <a name="analytic-and-ml-extensibility-with-scripting"></a>Analyse og ML-udvidelsesmulighed med scripting

Vi understøtter i øjeblikket brugen af R-scripts til brugerdefineret modellering og visualisering i Power BI. Disse R-scripts kan også køres som en del af dataopdateringen i forbindelse med Power BI-tjenestens udnyttelse af datagateway i det lokale miljø (personlig tilstand) med muligheden for at indlæse brugerdefinerede R-biblioteker.

Python er blevet meget udbredt blandt udviklere og it-professionelle.
Det er de facto-standarden for dataanalyse og arbejde, der er relateret til kunstig intelligens, på grund af den omfattende understøttelse af nyttige biblioteker. Som det næste trin tilføjer Power BI Desktop understøttelse af Python-scripting.

### <a name="intellisense-support-for-the-m-formula-language"></a>IntelliSense-understøttelse af M-formelsproget

IntelliSense-understøttelse af M-sprogredigeringsfunktionerne (Avanceret forespørgselseditor, Tilføj brugerdefinerede kolonner og Formellinje) føjes til Power-forespørgselseditoren, så brugere nemmere kan redigere deres M-kode direkte, let finde fejl, udforske M-biblioteksfunktionerne og forstå, hvilke parametre der skal bruges. M IntelliSense-understøttelse har i de seneste par år været en af de mest efterspurgte funktioner af mellemliggende-til-avancerede brugere af Power-forespørgsel og er fortsat øverst på listen over indlæg vedrørende Power-forespørgsel i forummer om funktioner i Power BI og Excel.

![](media/power-query-becomes-more-powerful-smarter-4.png "")
<!-- picture -->


Ud over de nye kernefunktioner i Power-forespørgsel udvider Microsoft også udvalget af produkter og tjenester, der udnytter Power-forespørgsel. I løbet af de sidste seks måneder er Power-forespørgsel online blevet integreret med Microsoft Flow.

<a name="flow-support-for-data-filtering--mashup"></a>  
### <a name="flow-support-for-data-filtering-and-mashup"></a>Flow-support til filtrering og miks af data

Microsoft Flow er nu integreret med Power-forespørgsel online, så brugerne kan "Få rækker ved hjælp af Power-forespørgsel", hvilket muliggør filtrering og miksning af data som en del af handlingen "Få rækker" på bestemte connectorer som f.eks. SQL Server.

### <a name="power-query-community-website"></a>Onlinecommunity for Power-forespørgsel

Der er blevet oprettet et nyt onlinecommunity for Power-forespørgsel. Det indeholder en teknologioversigt og dybdegående artikler samt fora, UserVoice og indhold produceret af communitiet (blogindlæg, webinarer) vedrørende Power-forespørgsel. Dette nye community har fokus på de vigtigste aspekter af teknologien bag Power-forespørgsel, der gør det muligt for partnere at opbygge nye connectorer og datatransformeringer oven på platformen, og som supplerer de tidligere produktbaserede ressourcer (Excel, Power BI, PowerApps med flere), der dækker specifikke Power-forespørgsel-integrationer fra et slutbrugerperspektiv.

##  <a name="enterprise-grade-connectors"></a>Connectorer for virksomheder

Dataintegrationsteamet bidrager fortsat til connectorer for virksomheder på tværs af Power BI, Common Data Service til apps, PowerApps, Microsoft Flow og Logic Apps.

Til Power BI udgiver Microsoft væsentlige forbedringer af deres SAP Business Warehouse-connectorer (programserver og meddelelsesserver), der placerer Microsoft Power BI på samme niveau og i nogle tilfælde foran andre tredjeparts BI-leverandører, hvad angår forbindelse til SAP Business Warehouse (BW).

SAP har **certificeret Microsofts connectorer til SAP HANA og SAP BW.** Derudover er SAP HANA-connectoren blevet forbedret for at muliggøre store virksomhedsfunktioner, f.eks. SAML-baseret (Security Assertion Markup Language) enkeltlogon og validering af SSL-certifikater. SAP BW-connectoren forbedres betydeligt med en ny implementering, der giver markant bedre ydeevne og indeholder yderligere funktioner.

Andre forbedringer af connectorer omfatter understøttelse af enkeltlogon via Kerberos for Spark i det lokale miljø og udgivelse af eksisterende connectorer som generelt tilgængelige, herunder **HDInsight Spark, Google BigQuery, Spark (non-HDInsight)** med flere.

Der er også sket forbedringer af connectorerne i PowerApps, Microsoft Flow og Logic Apps, f.eks. udgivelse af skrivefunktioner til Azure SQL Data Warehouse, flere opdateringer af Visual Studio Team Services med bedre udløsere og understøttelse af brugerdefinerede felter samt flere funktioner i Oracle-connectoren og meget mere.

Platformen udvikles fortsat og har tilføjet nye connectorer, der fungerer ens på tværs af Common Data Service til apps, Power BI, PowerApps, Microsoft Flow og Logic Apps. Dette sker i et forsøg på at forbedre kundeoplevelsen på tværs af alle produkterne.

##  <a name="improved-connectors-and-import-experiences-for-cds-data-integration"></a>Forbedrede connectorer og importoplevelser i forbindelse med CDS-dataintegration 

I april 2018 lancerede Microsoft en offentlig prøveversion af Common Data Service til apps. Som en del af denne prøveversion var der indbyggede funktioner, der gjorde det muligt for virksomhedsbrugere at importere data fra en lang række datakilder fra Microsoft og tredjeparter i skyen og i det lokale miljø ved at anvende en webbaseret Power-forespørgsel med lidt eller ingen kode, som brugerne allerede kender det fra Excel og Power BI Desktop.

Microsoft vil i løbet af de næste seks måneder fortsat udvide understøttelsen af dataconnectorer og datatransformeringer i denne webbaserede oplevelse af Power-forespørgsel, herunder understøttelse af virksomhedskritiske datakilder (i det lokale miljø og skyen), f.eks. Oracle, Amazon Redshift, Google BigQuery, Impala og andre.

Microsoft tilføjer også understøttelse af brugerdefinerede connectorer (baseret på Data Connector SDK) i Power-forespørgsel online, så eksisterende brugerdefinerede connectorer bygget af partnere kan anvendes til dataintegration med Common Data Service til apps og Power BI-dataflows.

Brugeroplevelsen i forbindelse med import af data fra filer i Power-forespørgsel online forbedres også ved at gøre det muligt for brugerne at uploade lokale filer, hvilket der ofte anmodes om.

![](media/4-1.png "")
<!-- Get Data 5.png -->

På samme måde vil Microsoft gøre det muligt at søge i Power-forespørgsel efter filer i populære skybaserede tjenester til fillagring, f.eks. OneDrive Business eller Personal og SharePoint-teamwebsteder. 

##  <a name="certified-custom-connectors-in-power-bi-desktop"></a>Godkendte brugerdefinerede connectorer i Power BI Desktop

I april 2018 frigav Microsoft de første brugerdefinerede connectorer i Power BI ved at udnytte M-sprogets effektive funktioner, der gør det muligt for partnere at skrive deres egne connectorer og distribuere dem til enhver Power BI-bruger. Nu kan enhver bruger nemt få adgang til connectorer fra alle sine datakilder, og leverandører kan nemt skrive nye connectorer, som deres egne kunder efterspørger, hvilket forbedrer Power BIs rolle som den bedste BI-platform til både leverandører og slutbrugere.

I maj 2018 blev dette bragt i overensstemmelse med den eksisterende Get Data-oplevelse, hvilket giver en problemfri oplevelse med eksisterende standardconnectorer og mulighed for at øge antallet af tilgængelige connectorer dramatisk med et enkelt klik på en knap.




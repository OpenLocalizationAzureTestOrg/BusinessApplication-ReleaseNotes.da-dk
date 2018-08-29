---
title: Nyheder i forbindelse med dataintegration
description: "Få en oversigt over nyheder i forbindelse med dataintegration i produktfrigivelsen fra oktober 2018 af Microsoft Virksomhedsprogrammer."
author: shellyhaverkamp
manager: AnnBe
ms.date: 8/16/2018
ms.assetid: 7326561e-192f-4897-ad72-af64d29849da
ms.topic: summary
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: tpalmer
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 31ec4b8d7fd211e5fe46f7c2362c123c9186bd5d
ms.openlocfilehash: 2e448f707d107ae422ce543330458036bf3bc756
ms.contentlocale: da-dk
ms.lasthandoff: 08/17/2018

---
#  <a name="summary-of-whats-new-in-data-integration"></a>Oversigt over nyheder i forbindelse med dataintegration



Forbedringer af denne platformsfunktionalitet muliggør mere omfattende forbindelser til forskellige programmer og tjenester fra Microsoft og tredjeparter.

Disse produktbemærkninger beskriver funktionalitet, der muligvis ikke er udgivet endnu. Leveringstidsplaner og forventet funktionalitet kan ændres eller kan ikke afsendes (se [Microsoft-gruppepolitik](https://go.microsoft.com/fwlink/p/?linkid=2007332)).
    
For at få en liste over områder, hvor Dynamics 365-virksomhedsprogrammer er tilgængelige, skal du se [Vejledning om international tilgængelighed](https://aka.ms/dynamics_365_international_availability_deck). 

|**Produkt** | **Funktioner**| **Frigivelsestype** | **Målmåned for frigivelse**|
|---------|-----------------------------------|---------|---------|
| Power BI | [Nye og forbedrede connectorer](1-power-query.md#enterprise-grade-connectors)<ul><li>Fuld understøttelse af OData v4-protokollen</li><li>Generel tilgængelighed af HDInsight Spark-connector</li><li>Generel tilgængelighed af Google BigQuery-connector</li><li>SAP HANA</li><ul><li>Understøttelse af validering af SSL-certifikater i Power BI-tjeneste (via gateway)</li><li>[SAML-baseret enkeltlogon](5-data-gateway.md#saml-based-single-sign-on-for-supported-data-sources) (herunder Power BI Desktop og gateway)</li></ul><li>SAP BW</li><ul><li>Forbedringer af ydeevne</li><li>Yderligere DirectQuery-metadata (egenskaber, valuta, måleenheder)</li><li>Certificering</li><li> Enkeltlogon for Power BI Desktop + service (via gateway)***</li></ul><li>Enkeltlogon til Spark-connector (ikke-HDInsight) i Power BI Desktop + tjeneste (via gateway)</li><li>Forbedringer af HTML-connector (udtræk af data efter eksempel)</li></ul>| Generel tilgængelighed | Oktober 2018 |
| Power BI | [Understøttelse af certificerede brugerdefinerede connectorer i Get Data-oplevelse](1-power-query.md#certified-custom-connectors-in-power-bi-desktop) | Generel tilgængelighed | Oktober 2018 |
| Power BI | Forbedret udviklingsdokumentation for brugerdefinerede connectorer, herunder indhold til ODBC-udviklere | Generel tilgængelighed | Oktober 2018 |
| Power BI | [Ny PDF-connector*](1-power-query.md#enterprise-grade-connectors)| Generel tilgængelighed* | December 2018* |
| Power BI | ["Fuzzy flet"-transformation**](1-power-query.md#new-power-query-data-preparation-capabilities) | Offentlig prøveversion** | Oktober 2018** |
| Power BI | [Nye og forbedrede connectorer](1-power-query.md#enterprise-grade-connectors)<ul><li>AtScale-connector</li><li>Essbase-connector</li><li>IBM DB2 DirectQuery\***</li><li>Vertica i PBI Service (via gateway)\*\*\*</li><li>HDInsight-interaktiv forespørgsel i PBI Service (via gateway)\*\*\*</li></ul> | Offentlig prøveversion | Oktober 2018 |
| Datagateway i det lokale miljø | [Understøttelse af brugerdefinerede connectorer i den personlige gateway og gatewayen for virksomheder](5-data-gateway.md#certified-custom-connectors-in-power-bi-desktop) | Generel tilgængelighed | Oktober 2018 |
| Datagateway i det lokale miljø | [Sikrer en høj tilgængelighed af gateways via klyngedannelse](5-data-gateway.md#guarantee-high-availability-of-gateways-via-clustering) | Generel tilgængelighed | Oktober 2018 |
| Datagateway i det lokale miljø | [Forbedret understøttelse af Kerberos-enkeltlogon](5-data-gateway.md#improved-kerberos-single-sign-on-support) | Generel tilgængelighed | Oktober 2018 |
| Datagateway i det lokale miljø | [Yderligere datakildefunktioner, der findes i Power BI Desktop](5-data-gateway.md#additional-cloud-data-refresh-capabilities-for-parity-with-pbi-desktop) | Generel tilgængelighed | Oktober 2018 |
| Datagateway i det lokale miljø | [Forbedret oplevelse af datakildeindstillinger](5-data-gateway.md#improved-data-sources-settings-experience) | Generel tilgængelighed | Oktober 2018 |
| Datagateway i det lokale miljø | [Mulighed for at administrere alle lejerens gateways i D365-administrationsportalen](5-data-gateway.md#tenant-level-administration-of-on-premises-data-gateway) | Generel tilgængelighed | Oktober 2018 |
| Datagateway i det lokale miljø | [Justering af trafikbelastning i datagatewayen i det lokale miljø](5-data-gateway.md#basic-traffic-load-balancing-in-the-on-premises-data-gateway) | Offentlig prøveversion | Oktober 2018 |
| CDS til apps og Power BI-dataflows | Planlagt opdateringsunderstøttelse af dataintegrationsprojekter i PowerApps-udviklerportal*** | Generel tilgængelighed*** | Oktober 2018*** |
| CDS til apps og Power BI-dataflows | GDPR (mulighed for at eksportere brugerdata, mulighed for at overvåge alle CRUD-handlinger foretaget af en bruger, DPIA-dokument)** | Generel tilgængelighed** | Oktober 2018** |
| CDS til apps og Power BI-dataflows | Forbedringer for administratorer af dataintegration**<ul><li>Ny oplevelse i Administration af virksomhedsplatform</li><li>Mulighed for at oprette supportanmodninger fra administrationsportalen</li><li>Forbedret gennemgang af historiske data (sideinddeling i udførelseshistorik)</li></ul> | Generel tilgængelighed** | Oktober 2018** |
| CDS til apps og Power BI-dataflows | Understøttelse af filoverførsel som en del af Filconnector-oplevelser | Offentlig prøveversion | Oktober 2018 |
| CDS til apps og Power BI-dataflows | Mulighed for at søge i skybaserede fillagre (OneDrive Business, OneDrive Personal og SharePoint-teamwebsteder) | Offentlig prøveversion | Oktober 2018 |
| CDS til apps og Power BI-dataflows | Understøttelse af de bedste relationsconnectorer for virksomheder (herunder Oracle Database, IBM DB2-database og PostgreSQL)| Offentlig prøveversion | Oktober 2018 |
| CDS til apps og Power BI-dataflows | Understøttelse af datatransformeringer i en data lake | Offentlig prøveversion | Oktober 2018 |
| CDS til apps og Power BI-dataflows | Nye og forbedrede skabelonfunktioner<ul><li>Ny Salesforce-skabelon til at importere data til CDS til apps og Power BI-dataflows</li><li>Yderligere nye skabeloner til dataintegration</li><li>Forbedret mulighed for at tilpasse skabeloner (oprette tomme projekter uden at vælge en eksisterende skabelon)</li><li>Understøttelse af versionsstyring</li><li>Validering af destinationer og kildeløsning(er)</li><li>Mulighed for at oprette et DI-projekt fra de offentliggjorte skabeloner på markedspladsen (med udgangspunkt i DI eller fra markedspladsen)</li><li>Deling af skabeloner på tværs af og blandt lejere</li></ul> | Offentlig prøveversion | Oktober 2018 |
| CDS til apps og Power BI-dataflows | Centraliseret installationsoplevelse for DI (undgå skift mellem udvikler-/administrationsportaler) | Offentlig prøveversion | Oktober 2018 |
| CDS til apps og Power BI-dataflows | Forbedringer af ydeevnen, herunder parallelitet mellem data og batch | Offentlig prøveversion | Oktober 2018 |
| CDS til apps og Power BI-dataflows | Mulighed for at annullere en igangværende udførelse | Offentlig prøveversion | Oktober 2018 |
| CDS til apps og Power BI-dataflows | Forbedret dokumentation, herunder vejledning om almindelige mønstre (løsninger på almindelige udfordringer) og retningslinjer for skalerbarhed | Offentlig prøveversion | Oktober 2018 |
| CDS til apps og Power BI-dataflows | Mulighed for at dele projekter med lejer | Offentlig prøveversion | Oktober 2018 |
| CDS til apps og Power BI-dataflows | Mere omfattende dashboard med meningsfuld indsigt fra integrationsdata og yderligere integrationsrelaterede statistikker | Offentlig prøveversion | Oktober 2018 |
| CDS til apps og Power BI-dataflows | Oprettelse af automatisk relation mellem objekter via dataintegration, når kildeobjekter er relaterede*** | Offentlig prøveversion*** | Oktober 2018*** |
| Microsoft Flow og PowerApps | Brug af eksempeldata i udløsere for de mest populære connectorer | Generel tilgængelighed | Oktober 2018 |
| Microsoft Flow og PowerApps | Forbedrede connectorer<ul><li>Oracle-database (generel tilgængelighed)</li><li>MQ (generel tilgængelighed)</li></li><li>Understøttelse af indbyggede nøgler til Cognitive Services API'er, Microsoft Translator, Bing Search og Bing Kort</li></ul> | Generel tilgængelighed | Oktober 2018 |
| Microsoft Flow og PowerApps | Understøttelse af nye områder:<ul><li>Amerikanske myndigheder</li><li>Brasilien</li></ul> | Generel tilgængelighed | Oktober 2018 |
| Microsoft Flow og PowerApps | Nye og forbedrede connectorer<ul><li>Oracle-database<ul><li>Understøttelse af gemte procedurer</li><li>Understøttelse af materialiserede visninger</li></ul></li><li>Azure SQL Data Warehouse<ul><li>Understøttelse af skrivehandlinger</li></ul></li><li>Excel Online**<ul><li>Understøttelse af opdatering**</li></ul></ul> | Offentlig prøveversion | Oktober 2018 |
| Microsoft Flow og PowerApps | Understøttelse af politikskabeloner i brugerdefinerede connectorer | Offentlig prøveversion | Oktober 2018 |
| Microsoft Flow og PowerApps | [Understøttelse af Power-forespørgsel til omformning af data i Microsoft Flow (med SQL Server-connectoren)](1-power-query.md#flow-support-for-data-filtering--mashup) | Offentlig prøveversion | Oktober 2018 |
| Power-forespørgsel | [Lancering af onlinecommunity](1-power-query.md#power-query-community-website) | Generel tilgængelighed | Oktober 2018 |
| Power-forespørgsel | [Funktioner til dataprofilering gør det nemmere at identificere fejl og afvigelser som en del af arbejdet med dataforberedelse**](1-power-query.md#new-power-query-data-preparation-capabilities) | Offentlig prøveversion** | Oktober 2018** |
| Power-forespørgsel | [Intellisense-understøttelse af M-sprog**](1-power-query.md#intellisense-support-for-the-m-formula-language) | Offentlig prøveversion** | Oktober 2018** |
| Udvidelsesmulighed for connectorplatform | [Konsolideret program til connectorcertificering for partnere til certificering og udgivelse af connectorer for alle produkter på platformen (Power BI, Microsoft Flow, PowerApps og CDS)](3-connector-ecosystem.md#unified-connector-certification-program)| Generel tilgængelighed | Oktober 2018 |
| Udvidelsesmulighed for connectorplatform | [Understøttelse af brugerdefinerede connectorer ved hjælp af Power-forespørgsel SDK](3-connector-ecosystem.md#improved-development-for-connectors-across-the-platform) | Generel tilgængelighed | Oktober 2018 |
| Udvidelsesmulighed for connectorplatform | [Forbedrede værktøjer til udvikling og validering til M-, OpenAPI- og OData-baserede connectorer](3-connector-ecosystem.md#improved-development-for-connectors-across-the-platform) | Offentlig prøveversion | Oktober 2018 |
| Common Data Model | [CDM GitHub-lager, hvor objektdefinitioner er åbenkilde med yderligere dokumentation og værktøjer***](2-cdm.md)  | Generel tilgængelighed*** | Oktober 2018*** |
| Common Data Model | [Forbedret CDM-dokumentationen, der beskriver værdiforslag og giver forebyggende vejledning til udvikling af udvidelser](2-cdm.md#docs)  | Generel tilgængelighed | Oktober 2018 |
| Common Data Model | [Forbedringer af interaktiv, grafisk Common Data Model-objektsporing med CDM GitHub](2-cdm.md#explorer) | Generel tilgængelighed | Oktober 2018 |
| Common Data Model | [Indledende CDM-objektpakker til brancheløsninger i f.eks. sundhedspleje, finanssektor og detail](2-cdm.md#industry) | Offentlig prøveversion | Oktober 2018 |
| Common Data Model | [Yderligere CDM-objektdefinitioner, der dækker vigtige scenarier fra populære Dynamics-tilbud, herunder Finance, Operations og Marketing med flere](2-cdm.md#dynamics) | Offentlig prøveversion | Oktober 2018 |

Forklaring:  
\* Disse datoer er blevet opdateret siden den oprindelige udgivelse af produktbemærkninger.  
** Frigivelsestypen (offentlig prøveversion versus generel tilgængelighed) af disse elementer har været forkert markeret og er blevet opdateret.  
*** Disse elementer er nye funktioner, der kommer i oktober.  



Elementer, der er fjernet fra denne liste:  

|Funktion | Årsag |
|-----|--------------------------|
| Understøttelse af brugerdefinerede connectorer (via gateway) i CDS til apps og Power BI-dataflows <br> (var offentlig prøveversion i oktober 2018) | Undersøgelsen af understøttelse af denne funktion er stadig undervejs; vi har ikke en fast tidsramme for den. Stem på forslaget på [PowerApps-ideer](https://powerusers.microsoft.com/t5/PowerApps-Ideas/idb-p/PowerAppsIdeas) og/eller [Power BI-ideer](https://ideas.powerbi.com) for at hjælpe med prioriteringen. |
| Understøttelse af gateway med Power BI premium i forskellige kapacitetsområder <br> (var generel tilgængelighed i oktober 2018)| På grund af ændrede prioriteter er tidsrammen for denne funktion ikke fastlagt. Mens undersøgelsen fortsætter, skal du stemme på forslaget på https://ideas.powerbi.com for at hjælpe med at prioritere.| 


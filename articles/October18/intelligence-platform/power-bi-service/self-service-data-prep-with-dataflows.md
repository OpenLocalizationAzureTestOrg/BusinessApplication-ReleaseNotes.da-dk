---
title: Selvbetjening af dataforberedelse med dataflows
description: "Dataflows reducerer tidsforbruget, kompleksiteten og omkostningerne ved udvikling af virksomhedsanalyse ud fra data, der strækker sig over flere virksomhedsprogrammer og datakilder."
author: adiregev
manager: PaBenja
ms.date: 7/22/2018
ms.assetid: 
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: adiregev
audience: 
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 2ceb2263e9fb343cb8feb050198f8a16050c2e5f
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---

# <a name="self-service-data-prep-with-dataflows"></a><span data-ttu-id="778f9-103">Selvbetjening af dataforberedelse med dataflows</span><span class="sxs-lookup"><span data-stu-id="778f9-103">Self-service data prep with dataflows</span></span> 

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



<span data-ttu-id="778f9-104">Power BI introducerer dataflows, så organisationer kan samle data fra forskellige kilder og forberede dem til modellering.</span><span class="sxs-lookup"><span data-stu-id="778f9-104">Power BI introduces dataflows to help organizations unify data from disparate sources and prepare it for modeling.</span></span> <span data-ttu-id="778f9-105">Analytikere kan nemt oprette dataflows ved hjælp af velkendte selvbetjeningsværktøjer.</span><span class="sxs-lookup"><span data-stu-id="778f9-105">Analysts can easily create dataflows, using familiar, self-service tools.</span></span> <span data-ttu-id="778f9-106">Dataflows bruges til at indtage, transformere, integrere og forbedre big data ved at definere datakildeforbindelser, ETL-logik, opdateringsplaner og meget mere.</span><span class="sxs-lookup"><span data-stu-id="778f9-106">Dataflows are used to ingest, transform, integrate, and enrich big data by defining data source connections, ETL logic, refresh schedules, and more.</span></span> <span data-ttu-id="778f9-107">Data gemmes som enheder i Common Data Model-kompatible mapper i Azure Data Lake Storage Gen2.</span><span class="sxs-lookup"><span data-stu-id="778f9-107">Data is stored as entities in Common Data Model compliant folders in Azure Data Lake Storage Gen2.</span></span> <span data-ttu-id="778f9-108">Dataflows oprettes og administreres i apparbejdsområder ved hjælp af Power BI-tjenesten.</span><span class="sxs-lookup"><span data-stu-id="778f9-108">Dataflows are created and managed in app workspaces by using the Power BI service.</span></span>   

<span data-ttu-id="778f9-109">Du kan bruge dataflows til at indtage data fra et stort og voksende sæt af understøttede lokale og skybaserede datakilder, herunder Dynamics 365, Salesforce, Azure SQL Database, Excel, SharePoint og meget mere.</span><span class="sxs-lookup"><span data-stu-id="778f9-109">You can use dataflows to ingest data from a large and growing set of supported on-premises and cloud- based data sources including Dynamics 365, Salesforce, Azure SQL Database, Excel, SharePoint, and more.</span></span>

<span data-ttu-id="778f9-110">Du kan derefter knytte data til kendte Common Data Model-objekter, redigere og udvide eksisterende objekter og oprette brugerdefinerede objekter.</span><span class="sxs-lookup"><span data-stu-id="778f9-110">You can then map data to known Common Data Model entities, modify and extend existing entities, and create custom entities.</span></span> <span data-ttu-id="778f9-111">Erfarne brugere kan oprette fuldt tilpassede dataflows ved hjælp af en indbygget selvbetjent oprettelse af en Power-forespørgsel med lidt eller ingen kode, som ligner den Power-forespørgselsoplevelse, som millioner af Power BI Desktop- og Excel-brugere allerede kender.</span><span class="sxs-lookup"><span data-stu-id="778f9-111">Advanced users can create fully-customized dataflows, using a self-service, low- code/no-code, built-in Power Query authoring experience, similar to the Power Query experience that millions of Power BI Desktop and Excel users already know.</span></span>  

<span data-ttu-id="778f9-112">Når du har oprettet et dataflow, kan du bruge tjenesten Power BI Desktop og Power BI til at oprette datasæt, rapporter, dashboards og apps, der udnytter styrken ved Common Data Model til at skabe omfattende indsigt i dine forretningsaktiviteter.</span><span class="sxs-lookup"><span data-stu-id="778f9-112">Once you’ve created a dataflow, you can use Power BI Desktop and the Power BI service to create datasets, reports, dashboards, and apps that leverage the power of the Common Data Model to drive deep insights into your business activities.</span></span> 

<span data-ttu-id="778f9-113">Planlægning af dataflow-opdatering administreres direkte fra det arbejdsområde, hvor dit dataflow er oprettet, ligesom dine datasæt.</span><span class="sxs-lookup"><span data-stu-id="778f9-113">Dataflow refresh scheduling is managed directly from the workspace in which your dataflow was created, just like your datasets.</span></span> 

<span data-ttu-id="778f9-114">Eksempelvisningen omfatter mere end 20 forbindelser til almindelige datakilder som Excel, SQL Server, Oracle, Azure SQL Datawarehouse, Dynamics 365 og Salesforce.</span><span class="sxs-lookup"><span data-stu-id="778f9-114">The preview includes more than 20 connectors to common data sources such as Excel, SQL Server, Oracle, Azure SQL Datawarehouse, Dynamics 365, and Salesforce.</span></span> 


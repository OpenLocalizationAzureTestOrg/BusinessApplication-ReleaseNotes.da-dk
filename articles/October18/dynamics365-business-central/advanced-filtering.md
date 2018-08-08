---
title: Avanceret filtrering
description: "Få større produktivitet på din stationære computer med effektive funktioner til filtrering."
author: mikebcMSFT
manager: edupont04
ms.date: 07/22/2018
ms.assetid: 011c924e-f156-4cd7-a034-99a13b5a7869
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: mikebc
audience: end user
ms.translationtype: HT
ms.sourcegitcommit: e4d721713b70d0a9cfeb06d0f795f23d3f0223a5
ms.openlocfilehash: f1d1fccfc70da49d1ca0bb2fe1beeee32095f4dc
ms.contentlocale: da-dk
ms.lasthandoff: 07/27/2018

---
# <a name="advanced-filtering"></a><span data-ttu-id="d8447-103">Avanceret filtrering</span><span class="sxs-lookup"><span data-stu-id="d8447-103">Advanced filtering</span></span>

[!include[banner](../../includes/banner.md)]

[!include[banner](Includes/disclaimer.md)]


<span data-ttu-id="d8447-104">Arbejd effektivt med lister i Dynamics 365 Business Central ved at påvirke beregninger og anvende filtre på flere felter.</span><span class="sxs-lookup"><span data-stu-id="d8447-104">Work efficiently in lists in Dynamics 365 Business Central by influencing calculations and applying filters to multiple fields.</span></span>

<span data-ttu-id="d8447-105">Administrationsmedarbejdere bruger meget tid på at arbejde med lister: De indtaster eller redigerer data, analyserer tendenser og afvigelser eller søger ganske enkelt efter bestemte poster.</span><span class="sxs-lookup"><span data-stu-id="d8447-105">Back-office information workers spend significant time working with lists: entering or modifying data, analyzing trends and anomalies, or simply looking for specific records.</span></span> <span data-ttu-id="d8447-106">Mens en hurtig søgning, der finder det bedste match på tværs af alle kolonner, kan reducere listen, har brugerne ofte behov for mere styring, efterhånden som forretningsdatabasen bliver større.</span><span class="sxs-lookup"><span data-stu-id="d8447-106">While a quick search can reduce the list by finding the closest matches across all columns, users often need a higher degree of control as the size of the business database grows.</span></span> <span data-ttu-id="d8447-107">De effektive filtreringsfunktioner i Business Central effektiviserer opgaver i forbindelse med lister – brugeren får fuld styring med filtreringen i en moderne og intuitiv oplevelse.</span><span class="sxs-lookup"><span data-stu-id="d8447-107">The powerful filtering capabilities in Business Central accelerate list-related tasks by providing absolute control over filtering in a modern and intuitive experience.</span></span>

## <a name="filtering-lists"></a><span data-ttu-id="d8447-108">Filtrering af lister</span><span class="sxs-lookup"><span data-stu-id="d8447-108">Filtering lists</span></span>
<span data-ttu-id="d8447-109">Den nye filterrude, som er forankret ved siden af listerne, har et velkendt design, der er nemt og effektivt at arbejde med.</span><span class="sxs-lookup"><span data-stu-id="d8447-109">Anchored to the side of your lists, the new filter pane has a familiar design that is easy to learn and efficient to work with.</span></span> <span data-ttu-id="d8447-110">Skift mellem foruddefinerede filtrerede visninger af listen, juster en visning ved at tilføje dine egne filtre, eller start helt fra bunden.</span><span class="sxs-lookup"><span data-stu-id="d8447-110">Switch between predefined filtered views of your list, adjust a view by adding your own filters, or simply start from scratch.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="d8447-111">![alt text](media/list-page-with-advanced-filter.png "Tidligt design for en filterrude, der er forankret ved siden af en liste.")</span><span class="sxs-lookup"><span data-stu-id="d8447-111">![alt text](media/list-page-with-advanced-filter.png "Early design concept for a filter pane anchored alongside a list.")</span></span>

<span data-ttu-id="d8447-112">I filterruden kan du:</span><span class="sxs-lookup"><span data-stu-id="d8447-112">The filter pane allows you to:</span></span>

-   <span data-ttu-id="d8447-113">Få et overblik over de aktuelt anvendte filtre og se, om de er indstillet af dig, af en filtreret visning eller af selve programmet.</span><span class="sxs-lookup"><span data-stu-id="d8447-113">Get an overview of the currently applied filters, and see if they were set by you, by a filtered view, or by the application itself.</span></span>
-   <span data-ttu-id="d8447-114">Tilføj så mange filtrerede kolonner, du vil – når du skriver, kan du hurtigt søge efter flere felter i kildetabellen.</span><span class="sxs-lookup"><span data-stu-id="d8447-114">Add as many filtered columns as you like by typing to quickly search for more fields on the source table.</span></span>
-   <span data-ttu-id="d8447-115">Få hjælp til at angive filterværdier ved hjælp af opslag eller feltets datatype.</span><span class="sxs-lookup"><span data-stu-id="d8447-115">Get assistance with specifying filter values using lookups or the field's data type.</span></span>
-   <span data-ttu-id="d8447-116">Opret avancerede filtre ved hjælp af operatorer, områder, variabler og oversigter.</span><span class="sxs-lookup"><span data-stu-id="d8447-116">Create complex filters using operators, ranges, variables, and shorthand.</span></span>
-   <span data-ttu-id="d8447-117">Filtrer den aktuelle celleværdi på listen.</span><span class="sxs-lookup"><span data-stu-id="d8447-117">Filter to the current cell value in the list.</span></span>

<span data-ttu-id="d8447-118">Business Central husker de filtre, du har anvendt under hele sessionen, mens du har navigeret frem og tilbage på tværs af sider.</span><span class="sxs-lookup"><span data-stu-id="d8447-118">Business Central remembers the filters you applied throughout the session as you navigate back and forth across pages.</span></span> <span data-ttu-id="d8447-119">Der bliver mulighed for at gemme ændringerne permanent som en filtreret visning på et senere tidspunkt.</span><span class="sxs-lookup"><span data-stu-id="d8447-119">The ability to permanently save your changes as a filtered view will be available at a later date.</span></span>

<span data-ttu-id="d8447-120">Filterruden er tilgængelig på alle sider, der indeholder lister, herunder regneark, dokumentlinjer og oversigtsdele.</span><span class="sxs-lookup"><span data-stu-id="d8447-120">The filter pane is available on all pages that display lists, including worksheets, document lines, and list parts.</span></span>
<span data-ttu-id="d8447-121">Denne funktion erstatter det tidligere filtervindue, der er tilgængeligt fra de enkelte kolonneoverskrifter, og den supplerer andre funktioner, f.eks. søgning og sortering, der kan hjælpe dig med at finde bestemte rækker eller analysere data.</span><span class="sxs-lookup"><span data-stu-id="d8447-121">This feature replaces the previous filter window reachable from each column header, and it complements other features that help you find specific rows or analyze your data, such as searching and sorting.</span></span>

## <a name="limit-totals"></a><span data-ttu-id="d8447-122">Begræns totaler</span><span class="sxs-lookup"><span data-stu-id="d8447-122">Limit totals</span></span>
<span data-ttu-id="d8447-123">En af de mest populære funktioner i Dynamics NAV finder nu vej til Business Central.</span><span class="sxs-lookup"><span data-stu-id="d8447-123">One of the most popular features of Dynamics NAV now makes its way to Business Central.</span></span> <span data-ttu-id="d8447-124">Lister viser ofte aggregerede eller beregnede værdier, f.eks. beløbstotaler i bestemte valutaer.</span><span class="sxs-lookup"><span data-stu-id="d8447-124">Lists often display aggregated or computed values, such as currency amount totals.</span></span> <span data-ttu-id="d8447-125">Med denne produktfrigivelse giver Business Central dig styring på et helt nyt niveau, hvor du kan anvende filtre på en eller flere dimensioner, der påvirker beregnede værdier.</span><span class="sxs-lookup"><span data-stu-id="d8447-125">With this release, Business Central gives you a whole new level of control through which you can apply filters to one or more dimensions that influence computed values.</span></span> <span data-ttu-id="d8447-126">Brug dette sammen med filtre, sortering og søgning for at undersøge og analysere dine data.</span><span class="sxs-lookup"><span data-stu-id="d8447-126">Use this in combination with filters, sort, and search to explore and analyze your data.</span></span>

## <a name="keyboard-shortcuts"></a><span data-ttu-id="d8447-127">Tastaturgenveje</span><span class="sxs-lookup"><span data-stu-id="d8447-127">Keyboard shortcuts</span></span>
<span data-ttu-id="d8447-128">Selvom filterruden er tilgængelig med blot et klik, kan du også få en oplevelse uden brug af musen, men i stedet med en lang række kombinationer af tastaturgenveje, herunder genvejen Alt + F3, som filtrerer den aktuelle værdi.</span><span class="sxs-lookup"><span data-stu-id="d8447-128">Although the filter pane is just a click away, you can also have a mouse-free experience with a variety of keyboard shortcut combinations, including the Alt+F3 shortcut to filter to the current value.</span></span> <span data-ttu-id="d8447-129">Du kan nu oprette sammensatte filtre løbende uden at skulle forlade listen ved at bruge tastaturgenveje til at navigere på tværs af celler og derefter filtrere til den pågældende værdi eller rydde filteret i den aktuelle kolonne.</span><span class="sxs-lookup"><span data-stu-id="d8447-129">You can now create compound filters on the fly without ever leaving the list, using shortcuts to navigate across cells and then filter to the currently focused value or clear the filter on the current column.</span></span>

<!--
### Who uses these features
These features are available to all desktop users without additional setup, in the browser or Windows 10 companion app.
## Status
### Availability
Cloud, on-premises, hybrid
### Regional availability
No regional restrictions. Available in all Dynamics 365 Business Central supported markets.
-->

## <a name="tell-us-what-you-think"></a><span data-ttu-id="d8447-130">Fortæl os, hvad du synes</span><span class="sxs-lookup"><span data-stu-id="d8447-130">Tell us what you think</span></span>
<span data-ttu-id="d8447-131">Hjælp os med at forbedre Dynamics 365 Business Central ved at diskutere ideer, stille forslag og give feedback.</span><span class="sxs-lookup"><span data-stu-id="d8447-131">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="d8447-132">Brug Business Central-forummet på https://aka.ms/businesscentralfeedback.</span><span class="sxs-lookup"><span data-stu-id="d8447-132">Use the Business Central forum at https://aka.ms/businesscentralfeedback.</span></span>


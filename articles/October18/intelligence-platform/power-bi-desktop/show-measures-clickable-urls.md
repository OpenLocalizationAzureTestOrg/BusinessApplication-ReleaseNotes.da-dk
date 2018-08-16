---
title: "Vise målinger som klikbare URL-adresser"
description: "Brug målinger til at definere et link for at navigere fra en rapport til en anden webadresse."
author: MI77
manager: kimani
ms.date: 6/22/18
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: willthom
audience: end user, developer, citizen developer, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: 3b3db487a5e105bae80656d20640059c915a8bf2
ms.contentlocale: da-dk
ms.lasthandoff: 08/16/2018

---

# <a name="show-measures-as-clickable-urls"></a><span data-ttu-id="eb34d-103">Vise målinger som klikbare URL-adresser</span><span class="sxs-lookup"><span data-stu-id="eb34d-103">Show measures as clickable URLS</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

<span data-ttu-id="eb34d-104">Slutbrugerne skal nemt kunne navigere mellem rapporter eller fra rapporter til andre programmer, mens de stadig bevarer konteksten af de data, de ser på.</span><span class="sxs-lookup"><span data-stu-id="eb34d-104">End users need an easy way to navigate between reports, or from reports to other applications, while still retaining the context of the data they were looking at.</span></span> <span data-ttu-id="eb34d-105">Målinger kan generere URL-adresser for at tillade navigation og kan vises som links, der gør det nemt at flytte mellem rapporter eller programmer.</span><span class="sxs-lookup"><span data-stu-id="eb34d-105">Measures can generate URLs to allow navigation, and can be shown as hyperlinks that make it easy to move between reports or applications.</span></span>

<span data-ttu-id="eb34d-106">En DAX-måling kan returnere en URL-adresse med tilføjede filtre, der svarer til de datavalg, som er foretaget i rapporten.</span><span class="sxs-lookup"><span data-stu-id="eb34d-106">A DAX measure can return a URL, appended with filters corresponding to the data selections made in the report.</span></span> <span data-ttu-id="eb34d-107">Dette kan vises i tabel- og matrixvisuals som et link, der justeres dynamisk på basis af de valg, der foretages.</span><span class="sxs-lookup"><span data-stu-id="eb34d-107">This can be shown in table and matrix visuals as a hyperlink, dynamically adjusted based on the selections that are made.</span></span> <span data-ttu-id="eb34d-108">Slutbrugerne kan klikke på dette link for at åbne en ny fane, hvor målrapporten vises.</span><span class="sxs-lookup"><span data-stu-id="eb34d-108">End users can click this link to open a new tab with the target report shown.</span></span>

<span data-ttu-id="eb34d-109">DAX-målingen kan se således ud:</span><span class="sxs-lookup"><span data-stu-id="eb34d-109">The DAX measure might look something like this:</span></span>

`Link = “http://app.powerbi.com/Report/GUID/&filter=Table1/Category eq “ & SELECTEDVALUE(Products[Category])`

<!--
### Who uses this feature
This feature is intended for end users, developers, citizen developers, customizers, business analysts, and IT pros. No additional setup is required.
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->


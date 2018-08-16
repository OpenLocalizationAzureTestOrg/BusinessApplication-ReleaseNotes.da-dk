---
title: Udtryksbaseret formatering
description: Rapportforfattere kan udnytte DAX til at levere mere komplekse formateringsregler, som dynamisk anvender typografiske formateringsindstillinger og tekstfelter.
author: MI77
manager: kimani
ms.date: 7/22/18
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: willthom
audience: developer, citizen developer, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: bf1e3add265363a1d4424e361993e3f10efdbacf
ms.contentlocale: da-dk
ms.lasthandoff: 08/16/2018

---

# <a name="expression-based-formatting"></a><span data-ttu-id="84ace-103">Udtryksbaseret formatering</span><span class="sxs-lookup"><span data-stu-id="84ace-103">Expression-based formatting</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]

<span data-ttu-id="84ace-104">Rapportforfattere kræver fleksible løsninger på, hvordan deres visualiseringer kan formateres.</span><span class="sxs-lookup"><span data-stu-id="84ace-104">Report authors need flexibility over how their visuals are formatted.</span></span> <span data-ttu-id="84ace-105">Ud over at definere formatering via formateringsruden kan et [DAX](https://docs.microsoft.com/power-bi/desktop-quickstart-learn-dax-basics)-udtryk bruges til at angive formateringen og give fuld kontrol over den forretningslogik, der bruges til at formatere visualiseringen.</span><span class="sxs-lookup"><span data-stu-id="84ace-105">As well as defining formatting through the formatting pane, a [DAX](https://docs.microsoft.com/power-bi/desktop-quickstart-learn-dax-basics) expression can be used to set the formatting, giving full control over the business logic used to format the visual.</span></span>


<span data-ttu-id="84ace-106">Forfatterne kan oprette regler, der angiver farven på en KPI baseret på statussen mod et mål, angive typen af en linje i et diagram baseret på, hvilken kategori der klarer sig bedst, eller en kombination af disse.</span><span class="sxs-lookup"><span data-stu-id="84ace-106">Authors can create rules that set the color of a KPI based on the progress towards a goal, set the style of a line on a chart based on which category is performing best, or any combination of these.</span></span> <span data-ttu-id="84ace-107">Forfatterne kan endda dynamisk opdatere titlen på en visualisering baseret på valg, der er foretaget et andet sted i rapporten.</span><span class="sxs-lookup"><span data-stu-id="84ace-107">Authors can even dynamically update the title of a visual based on selections made elsewhere in the report.</span></span>

<!--
### Who uses this feature
This feature is intended for report developers. It works without any additional setup. 
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->


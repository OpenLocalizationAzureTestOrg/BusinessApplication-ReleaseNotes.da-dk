---
title: "Oprette lærred-apps med dynamisk layout"
description: "Avancerede udviklere kan oprette apps, der er dynamiske og tilpasser sig til forskellige miljøer."
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
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: a8908855955edfae9b14c67feaf2d2fdfd7482a6
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---
# <a name="create-canvas-apps-with-responsive-layout"></a><span data-ttu-id="d8b50-103">Oprette lærred-apps med dynamisk layout</span><span class="sxs-lookup"><span data-stu-id="d8b50-103">Create canvas apps with responsive layout</span></span>

[!include[powerapps banner](../includes/powerapps.md)]




<span data-ttu-id="d8b50-104">Normalt skaleres skærmene i en lærred-app, så de passer til den plads, der leveres af appværten.</span><span class="sxs-lookup"><span data-stu-id="d8b50-104">Normally the screens of a canvas app are scaled to fit the space provided by the app host.</span></span>  <span data-ttu-id="d8b50-105">På denne måde kan du nemt oprette en app og være sikker på, at den vil se korrekt ud på enhver skærm, hvor den bliver anvendt.</span><span class="sxs-lookup"><span data-stu-id="d8b50-105">This makes it easy to create an app and know that it will look proportionally correct on any screen in which it's used.</span></span>  <span data-ttu-id="d8b50-106">Men det har en pris – efterhånden som skærme bliver større og større, kan apps ikke udnytte den ekstra plads.</span><span class="sxs-lookup"><span data-stu-id="d8b50-106">But it comes at a price - as screens get bigger, the app can't adapt to take advantage of the additional real estate.</span></span>  <span data-ttu-id="d8b50-107">Mange websteder er i dag "dynamiske" – de tilpasser sig til den størrelse skærm, de bliver vist på – fra små skærme på telefoner til store skærme på stationære computere.</span><span class="sxs-lookup"><span data-stu-id="d8b50-107">Many websites today are "responsive" - they adjust depending on the size of the screen they are shown on, adapting from small screens on phones to large screens on desktops.</span></span>  

<span data-ttu-id="d8b50-108">Med denne funktion kan erfarne appudviklere skabe dynamiske lærred-apps.</span><span class="sxs-lookup"><span data-stu-id="d8b50-108">With this feature, experienced app makers can create responsive canvas apps.</span></span>  <span data-ttu-id="d8b50-109">Du skal skrive formler, der under kørsel tilpasser kontrolelementers størrelse og placering ud fra skærmens størrelse.</span><span class="sxs-lookup"><span data-stu-id="d8b50-109">You must write formulas that adapt the size and position of controls based on the size of the screen at runtime.</span></span>  <span data-ttu-id="d8b50-110">Du kan slå standardskaleringen fra.</span><span class="sxs-lookup"><span data-stu-id="d8b50-110">You can turn off the default scaling behavior.</span></span>  <span data-ttu-id="d8b50-111">Som følge heraf viser skærme flere oplysninger i en mere passende skriftstørrelse, hvilket giver en bedre oplevelse af appen.</span><span class="sxs-lookup"><span data-stu-id="d8b50-111">As a result, screens show more information with more appropriate font sizes, all making for a better app experience.</span></span>


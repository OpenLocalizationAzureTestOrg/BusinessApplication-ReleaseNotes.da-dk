---
title: "Kapacitetsplanlægning"
description: "Kapacitetsplanlægning"
author: Dgittler
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 96e82715-35fd-4587-a004-bbf57a14c1b2
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 832f1714f8cce2602dd724f95337a0c7d4ad6a17
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---




#  <a name="capacity-scheduling"></a><span data-ttu-id="70a45-103">Kapacitetsplanlægning</span><span class="sxs-lookup"><span data-stu-id="70a45-103">Capacity scheduling</span></span>

[!include[field-service banner](../../../includes/field-service.md)]



<span data-ttu-id="70a45-104">Ressourcekrav kan nu angive, hvor stor en arbejdsindsats, et krav stiller til en ressource.</span><span class="sxs-lookup"><span data-stu-id="70a45-104">Resource requirements can now specify how much effort a requirement needs from a resource.</span></span> <span data-ttu-id="70a45-105">Når du planlægger, ser planlægningsassistenten på en ressources definerede kapacitet i ressourcens arbejdstimer for at se, om vedkommende er tilgængelig for den nødvendige indsats.</span><span class="sxs-lookup"><span data-stu-id="70a45-105">When scheduling, the Schedule Assistant will look at a resource’s defined capacity on its work hours to check if the necessary effort is available.</span></span> <span data-ttu-id="70a45-106">En ressources kapacitet kan variere, selv inden for en dag.</span><span class="sxs-lookup"><span data-stu-id="70a45-106">A resource's capacity can vary even within a day.</span></span>

<span data-ttu-id="70a45-107">Det er særlig nyttigt at bruge kapacitetsplanlægning, når du reserverer en facilitet (f.eks. et lokale).</span><span class="sxs-lookup"><span data-stu-id="70a45-107">Capacity scheduling is exceptionally useful when booking a facility.</span></span> <span data-ttu-id="70a45-108">Et eksempel: En lastvogn kan kræve dobbelt så meget plads som en standardbil.</span><span class="sxs-lookup"><span data-stu-id="70a45-108">By way of example, a van may require twice the space as a standard car.</span></span> <span data-ttu-id="70a45-109">Du kan nu oprette en facilitet med en bestemt kapacitet, men når du reserverer tid til at arbejde på en lastvogn, fylder den det samme (har samme kapacitetsforbrug), som hvis du reserverede plads til to biler eller seks motorcykler.</span><span class="sxs-lookup"><span data-stu-id="70a45-109">You can now create a facility with a certain capacity, but when booking time to work on a van, it consumes the capacity of the facility as if you were booking two cars or six motorcycles.</span></span>

<span data-ttu-id="70a45-110">Planlægningsområdet viser også et visual-indikator, når en ressource har yderligere kapacitet, selvom der er en reservation på et bestemt tidspunkt.</span><span class="sxs-lookup"><span data-stu-id="70a45-110">The Schedule Board will also offer a visual indicator when a resource has additional capacity even though there is a booking at a given time.</span></span>

* <span data-ttu-id="70a45-111">Sager med eksempler på brug</span><span class="sxs-lookup"><span data-stu-id="70a45-111">Sample use cases</span></span>
    * <span data-ttu-id="70a45-112">Udvidelse af medarbejderstab, hvor ressourcerne ikke er navngivet.</span><span class="sxs-lookup"><span data-stu-id="70a45-112">Staff augmentation where resources are unnamed.</span></span>
    * <span data-ttu-id="70a45-113">Effektive ressourcer.</span><span class="sxs-lookup"><span data-stu-id="70a45-113">Efficient resources.</span></span>
        * <span data-ttu-id="70a45-114">Person, der kan reparere to cykler på samme tid, som det normalt tager en person at reparere én cykel.</span><span class="sxs-lookup"><span data-stu-id="70a45-114">Person can fix two bikes in the time a typical person can fix one.</span></span>
    * <span data-ttu-id="70a45-115">Fysisk område.</span><span class="sxs-lookup"><span data-stu-id="70a45-115">Physical space.</span></span>
        * <span data-ttu-id="70a45-116">Ét arbejdsområde kan være nok til to biler eller én lastvogn.</span><span class="sxs-lookup"><span data-stu-id="70a45-116">One workspace can fit two cars or one van.</span></span>
        * <span data-ttu-id="70a45-117">Opret en "klasse" som en ressource, og tillad, at op til 10 kunder kan være reserveret til klassen.</span><span class="sxs-lookup"><span data-stu-id="70a45-117">Create a “class” as a resource, and allow up to 10 customers to be booked to the class.</span></span>
> <span data-ttu-id="70a45-118">Ressourcer, som udfører arbejde hos virksomheden, kan højst have en kapacitet på én.</span><span class="sxs-lookup"><span data-stu-id="70a45-118">Resources that perform onsite work cannot have a capacity of more than one.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="70a45-119">![](media/Additional-Capacity.png "Yderligere kapacitet")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="70a45-119">![](media/Additional-Capacity.png "Additional Capacity")
<!-- picture --></span></span>

<span data-ttu-id="70a45-120">*Planlægningsområde, der viser en ressource, hvor rækken med yderligere kapacitet er udvidet*</span><span class="sxs-lookup"><span data-stu-id="70a45-120">*Schedule Board showing a resource with additional capacity row expanded*</span></span>


---
title: Ressourcepuljer
description: "Med ressourcepuljer kan planlæggere reservere arbejde til en generisk pulje uden behov for at bestemme, hvilken ressource der rent faktisk skal udføre arbejdet."
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
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 8450e5278a3b84e410ad73c3635ff94a20d32812
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---

#  <a name="resource-pools"></a><span data-ttu-id="4a9ca-103">Ressourcepuljer</span><span class="sxs-lookup"><span data-stu-id="4a9ca-103">Resource pools</span></span>

[!include[banner](../../../../includes/banner.md)]

<span data-ttu-id="4a9ca-104">Knyt ressourcer til ressourcepuljer, så planlæggere kan reservere krav til en generisk pulje uden behov for at bestemme, hvilken ressource der rent faktisk skal udføre arbejdet.</span><span class="sxs-lookup"><span data-stu-id="4a9ca-104">Associate resources to resource pools to enable schedulers to book requirements to a generic pool without needing to decide which resource will actually perform the work.</span></span>

# <a name="why"></a><span data-ttu-id="4a9ca-105">Hvorfor?</span><span class="sxs-lookup"><span data-stu-id="4a9ca-105">Why?</span></span>

- <span data-ttu-id="4a9ca-106">Undgå at skulle reservere specifikke ressourcer i forvejen, og reservér i stedet "ressourcepuljen" samtidig med, at du ikke overforpligter dig.</span><span class="sxs-lookup"><span data-stu-id="4a9ca-106">Avoid being forced to book specific resources up front and instead book the “resource pool” while ensuring you are not overcommitting.</span></span>
- <span data-ttu-id="4a9ca-107">Giv centrale planlæggere mulighed for at være fritaget fra detaljer, og overlad detaljerne til den lokale ressourcestyring.</span><span class="sxs-lookup"><span data-stu-id="4a9ca-107">Enable central schedulers to be shielded from details and leave the details to the local resource manager.</span></span>
- <span data-ttu-id="4a9ca-108">Specifikke ressourcer er måske endnu ikke navngivet, men kapaciteten i puljen er fastlagt, og ressourcer navngives senere.</span><span class="sxs-lookup"><span data-stu-id="4a9ca-108">Specific resources may not be named yet but capacity of the pool is established and resources will be named later.</span></span> <span data-ttu-id="4a9ca-109">Planlæggere kan stadig planlægge, da kapaciteten i puljen kan angives, som om alle ressourcerne var navngivet (kapacitetsstyring).</span><span class="sxs-lookup"><span data-stu-id="4a9ca-109">Schedulers can still schedule since capacity of the pool can be set as if all the resources were named (capacity management).</span></span>
- <span data-ttu-id="4a9ca-110">Muliggør bevidst overreservation med forventning om annulleringer.</span><span class="sxs-lookup"><span data-stu-id="4a9ca-110">Deliberately enable overbooking for expected cancellations.</span></span>

# <a name="what"></a><span data-ttu-id="4a9ca-111">Hvad er formålet?</span><span class="sxs-lookup"><span data-stu-id="4a9ca-111">What?</span></span>

- <span data-ttu-id="4a9ca-112">Ressourcepuljer kan enten bestå af faciliteter eller puljer af firmaer/kontakter/brugere eller udstyrspuljer.</span><span class="sxs-lookup"><span data-stu-id="4a9ca-112">Resource pools can be either pools of facilities, or pools of accounts/contacts/users, or pools of equipment.</span></span> <span data-ttu-id="4a9ca-113">Puljer skal være et sæt ensartede ressourcer.</span><span class="sxs-lookup"><span data-stu-id="4a9ca-113">Pools are intended to be a set of homogenous resources.</span></span>
- <span data-ttu-id="4a9ca-114">Puljemedlemmer kan være permanent eller midlertidigt tildelt puljer med gældende datoer.</span><span class="sxs-lookup"><span data-stu-id="4a9ca-114">Pool members can be permanently or temporarily assigned to pools, date effective.</span></span>
- <span data-ttu-id="4a9ca-115">Du kan også udlede den overordnede puljekapacitet fra puljemedlemmer.</span><span class="sxs-lookup"><span data-stu-id="4a9ca-115">Optionally derive overall pool capacity from pool members.</span></span>

> <span data-ttu-id="4a9ca-116">*Krav på stedet er ikke planlagt til at være understøttet af ressourcepuljer*</span><span class="sxs-lookup"><span data-stu-id="4a9ca-116">*Onsite requirements not planned to be supported with resource pools*</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="4a9ca-117">![](media/ResourcePools.png "Ressourcepuljescenarier")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="4a9ca-117">![](media/ResourcePools.png "Resource pool scenarios")
<!-- picture --></span></span>

<span data-ttu-id="4a9ca-118">*Ressourcepuljescenarier*</span><span class="sxs-lookup"><span data-stu-id="4a9ca-118">*Resource pool scenarios*</span></span>


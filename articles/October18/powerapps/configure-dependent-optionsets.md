---
title: "Konfigurere afhængige grupperede indstillinger"
description: "Konfigurer afhængige grupperede indstillinger for at levere overlappende rullemenuer i dine apps og sikre simpel datavalidering mellem rullemenuer."
author: clwesene
manager: AnnBe
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: clwesene
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: d00774edef47cf743fec7f13e6c9f7c12128b7e4
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---
# <a name="configure-dependent-option-sets"></a><span data-ttu-id="622d0-103">Konfigurere afhængige grupperede indstillinger</span><span class="sxs-lookup"><span data-stu-id="622d0-103">Configure dependent option sets</span></span>

[!include[powerapps banner](../includes/powerapps.md)]




<span data-ttu-id="622d0-104">Ved at oprette afhængige grupperede indstillinger kan du nemt fastsætte regler mellem grupperede indstillinger for at sikre, at de valgte værdier giver mening.</span><span class="sxs-lookup"><span data-stu-id="622d0-104">By creating dependent option sets, you can easily set rules between option sets to make sure that selected values make sense.</span></span> <span data-ttu-id="622d0-105">Du kan for eksempel oprette grupperede indstillinger som **Land/område** og **Stater**.</span><span class="sxs-lookup"><span data-stu-id="622d0-105">As an example, you can create a **Country/region** option set and a **States** option set.</span></span> <span data-ttu-id="622d0-106">Hvis en bruger vælger **USA** i rullemenuen for den første grupperede indstilling, bør rullemenuen for den anden grupperede indstilling kun vise de stater, der ligger i det land/område.</span><span class="sxs-lookup"><span data-stu-id="622d0-106">If a user selects **United States** in the drop-down list for the first option set, the drop-down list for the second option set should show only those states that are in that country/region.</span></span> <span data-ttu-id="622d0-107">Du kan sørge for, at dataene stemmer overens og er korrekte ved at definere denne struktur på objektniveau til anvendelse i alle apps.</span><span class="sxs-lookup"><span data-stu-id="622d0-107">You can ensure that data is consistent and accurate by defining this structure at the entity level for consumption in all apps.</span></span>


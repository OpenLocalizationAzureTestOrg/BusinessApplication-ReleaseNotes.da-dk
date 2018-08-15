---
title: Forseglet budafgivelse
description: Forseglet budafgivelse
author: ShylaThompson
manager: AnnBe
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: shylaw
audience: end-user
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 072d54c3326f02d285fd80cf964384f718997fe1
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---

# <a name="sealed-bidding"></a><span data-ttu-id="c78f8-103">Forseglet budafgivelse</span><span class="sxs-lookup"><span data-stu-id="c78f8-103">Sealed bidding</span></span> 

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



<span data-ttu-id="c78f8-104">Funktionerne for tilbudsanmodningen udvides til at understøtte forseglet budafgivelse.</span><span class="sxs-lookup"><span data-stu-id="c78f8-104">The request for quotation capabilities will be enhanced to support sealed bidding.</span></span> <span data-ttu-id="c78f8-105">En leverandør kan angive og indsende et tilbud, herunder vedhæftede .pdf-filer, via en særlig formular i brugergrænsefladen for leverandørsamarbejde.</span><span class="sxs-lookup"><span data-stu-id="c78f8-105">A vendor can enter and submit a bid including .pdf attachments via a dedicated form in vendor collaborating interface.</span></span> <span data-ttu-id="c78f8-106">Buddet kan ikke ses i forbindelse med den tilbudsanmodning, som indkøberne har adgang til.</span><span class="sxs-lookup"><span data-stu-id="c78f8-106">The bid will not be visible in the context of the RFQ that the procurement personnel have access to.</span></span> <span data-ttu-id="c78f8-107">Buddet gemmes i krypteret format.</span><span class="sxs-lookup"><span data-stu-id="c78f8-107">The bid is stored encrypted.</span></span> <span data-ttu-id="c78f8-108">Det er kun den kontaktperson, der er registreret som leverandørkontakt og har fået rolletilladelserne, som har adgang til buddet, før dets forsegling brydes.</span><span class="sxs-lookup"><span data-stu-id="c78f8-108">Only the contact person registered as a vendor contact and having the required role permissions can access the bid before it is unsealed.</span></span> <span data-ttu-id="c78f8-109">Indkøberne kan bryde forseglingen af buddene efter udløbsdatoen, og de kan herefter se leverandørens bud i forbindelse med tilbudsanmodningen.</span><span class="sxs-lookup"><span data-stu-id="c78f8-109">The procurement personnel can unseal the bids after the expiration date, and from that point can see the vendor's bid in context of the RFQ.</span></span> <span data-ttu-id="c78f8-110">Enhver brugerhandling, der læser eller skriver i buddet før udløbsdatoen, logføres til overvågning, og disse oplysninger vil være tilgængelige for leverandøren og indkøberne, når forseglingen af buddet brydes.</span><span class="sxs-lookup"><span data-stu-id="c78f8-110">Any user action that reads or writes in the bid before the expiration date will be logged for audit purposes and that information will be available to the vendor and also to the procurement personnel when the bid is unsealed.</span></span>  


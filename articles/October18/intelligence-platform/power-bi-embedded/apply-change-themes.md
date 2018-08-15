---
title: "Anvende og ændre temaer"
description: "Med rapporttemaerne kan du anvende et farvetema, f.eks. virksomhedens eller årstidens farver, på hele din rapport."
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: c44d4deb-6158-4658-9171-7fa813e438cf
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: bbcd52e8beedcc5309ddcb2ee2093eb59e44f81a
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---
# <a name="api-to-apply-and-change-report-themes-in-power-bi-embedded"></a><span data-ttu-id="66b69-103">API til anvendelse og ændring af rapporttemaer i Power BI Embedded</span><span class="sxs-lookup"><span data-stu-id="66b69-103">API to apply and change report themes in Power BI Embedded</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]




<span data-ttu-id="66b69-104">Denne nye funktion gør det muligt for programmer at kalde en API for at anvende og ændre rapporttemaer for integrerede objekter på sessionsniveau.</span><span class="sxs-lookup"><span data-stu-id="66b69-104">This new capability allows applications to call an API to apply and change report themes for embedded objects on a session level.</span></span> <span data-ttu-id="66b69-105">Med rapporttemaerne kan du anvende et farvetema, f.eks. virksomhedens eller årstidens farver, på en hel rapport.</span><span class="sxs-lookup"><span data-stu-id="66b69-105">With report themes, you can apply a color theme to an entire report, such as corporate colors, or seasonal coloring.</span></span> <span data-ttu-id="66b69-106">Når du anvender et rapporttema, bruger alle visuals i rapporten farverne fra det valgte tema.</span><span class="sxs-lookup"><span data-stu-id="66b69-106">When you apply a report theme, all visuals in your report use the colors from your selected theme.</span></span>

<span data-ttu-id="66b69-107">![](media/apply-change-themes-1.png "Anvende rapporttemaer")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="66b69-107">![](media/apply-change-themes-1.png "Apply report themes")
<!-- picture --></span></span>


<span data-ttu-id="66b69-108">Når du anvender et rapporttema, kræver det en JSON-fil, som du kan importere til Power BI Desktop og anvende på din rapport.</span><span class="sxs-lookup"><span data-stu-id="66b69-108">Applying a report theme requires a JSON file, which you can import into the Power BI Desktop and apply to your report.</span></span> 


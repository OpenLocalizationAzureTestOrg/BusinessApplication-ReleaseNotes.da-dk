---
title: Opdatere en eksisterende Power BI-app i AppSource
description: Opdatere en eksisterende Power BI-app i AppSource
author: ezaviv
manager: HaydnR
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: avive
audience: Admin, end user
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 3ad9af8d11d2ebf408a73a25ccee959befa61142
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---
# <a name="update-an-existing-power-bi-app-in-appsource"></a><span data-ttu-id="3ce07-103">Opdatere en eksisterende Power BI-app i AppSource</span><span class="sxs-lookup"><span data-stu-id="3ce07-103">Update an existing Power BI app in AppSource</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



<span data-ttu-id="3ce07-104">Administrationen af programlivscyklus (ALM) indeholder følgende funktioner:</span><span class="sxs-lookup"><span data-stu-id="3ce07-104">The application lifecycle management (ALM) story includes the following capabilities:</span></span>

- <span data-ttu-id="3ce07-105">En app, der er baseret på et Power BI-arbejdsområde med flere indstillinger (parametre).</span><span class="sxs-lookup"><span data-stu-id="3ce07-105">An app is based on a Power BI workspace with additional settings (parameters).</span></span>
- <span data-ttu-id="3ce07-106">Der er tre frigivelsesniveauer for en app: arbejdsområde (IGVF)--> pakke (frigivelseskandidat)--> publiceret app (indhold, der er offentligt tilgængeligt for installation via AppSource).</span><span class="sxs-lookup"><span data-stu-id="3ce07-106">There are three release levels for an app: workspace (WIP) --> package (release candidate) --> published app (content that is publicly available to install through AppSource).</span></span>
- <span data-ttu-id="3ce07-107">På hvert frigivelsesniveau har vi en enkelt version: ét arbejdsområde i IGVF, én pakke, én publiceret app.</span><span class="sxs-lookup"><span data-stu-id="3ce07-107">On each release level we keep a single version: one workspace in WIP, one package, one published app.</span></span> <span data-ttu-id="3ce07-108">Hvis du vil foretage en opdatering af en publiceret app, skal du installere en pakke.</span><span class="sxs-lookup"><span data-stu-id="3ce07-108">To make an update to a published app, you deploy a package.</span></span> <span data-ttu-id="3ce07-109">Installation af en pakke vil overskrive den publicerede app i AppSource.</span><span class="sxs-lookup"><span data-stu-id="3ce07-109">Deploying a package will overwrite the published app in AppSource.</span></span>
- <span data-ttu-id="3ce07-110">Udvikling af appen kan fortsætte hele tiden i IGVF-arbejdsområdet.</span><span class="sxs-lookup"><span data-stu-id="3ce07-110">Building the app can continue at all times on the WIP workspace.</span></span>
- <span data-ttu-id="3ce07-111">Når du er klar til at oprette en frigivelseskandidat, skal du gemme pakken.</span><span class="sxs-lookup"><span data-stu-id="3ce07-111">Whenever you are ready to create a release candidate, save the package.</span></span>


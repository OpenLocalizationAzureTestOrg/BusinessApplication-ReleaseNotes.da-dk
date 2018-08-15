---
title: "CFS – Integration med IoT Central"
description: "I den første fase af integrationen foregår integrationsløsningen primært via Flow."
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: ce0f2e97-8ded-4530-9c50-fc82ce4a6171
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: a93e3c09095e6033a960b8fccfcb04f2f3e1f470
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---
#  <a name="cfs---integration-with-iot-central"></a><span data-ttu-id="071f9-103">CFS – Integration med IoT Central</span><span class="sxs-lookup"><span data-stu-id="071f9-103">CFS - Integration with IoT Central</span></span>

[!include[field-service banner](../../../includes/field-service.md)]




<span data-ttu-id="071f9-104">I den første fase af integrationen foregår integrationsløsningen primært via Microsoft Flow.</span><span class="sxs-lookup"><span data-stu-id="071f9-104">For the first phase of integration, the focus of the integration solution will be through Microsoft Flow.</span></span> <span data-ttu-id="071f9-105">Dette er en envejskommunikation fra IoT Central til Connected Field Service.</span><span class="sxs-lookup"><span data-stu-id="071f9-105">This is a one-way communication from IoT Central to Connected Field Service.</span></span> <span data-ttu-id="071f9-106">IoT Central overvåger eksterne enheder, og alle mål, der overskrider de tærskelværdier, der er defineret i IoT Central, udløser en handling, der starter en advarsel i CFS.</span><span class="sxs-lookup"><span data-stu-id="071f9-106">With IoT Central monitoring remote devices, any measurements that exceed thresholds defined in IoT Central will trigger an action to fire an alert in CFS.</span></span> <span data-ttu-id="071f9-107">Field Service-chefer kan gruppere disse advarselsbeskeder efter kriterier, f.eks. kundeaktiv og hændelsestype.</span><span class="sxs-lookup"><span data-stu-id="071f9-107">Field service managers can group these alerts by criteria such as customer asset and incident type.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="071f9-108">![](media/enhanced-iot-central-integration-1.png "Udvidet IoT Central-integration")
<!-- picture --></span><span class="sxs-lookup"><span data-stu-id="071f9-108">![](media/enhanced-iot-central-integration-1.png "Enhanced IoT Central integration")
<!-- picture --></span></span>


<span data-ttu-id="071f9-109">Med produktfrigivelsen fra oktober 2018 kan teknikere få indsigt i og reagere på indsigt fra loT-enheder, når de befinder sig på et lokalt sted, og de kan have nogle muligheder, afhængigt af tilstanden af loT Central:</span><span class="sxs-lookup"><span data-stu-id="071f9-109">For the October '18 release, technicians can be equipped with and act on insight from IoT devices when on site, with a few options depending on the state of IoT Central.</span></span>

-   <span data-ttu-id="071f9-110">Integrere loT Central-enhedens tilstand og målvisualiseringer direkte i Field Service-mobilprogrammet.</span><span class="sxs-lookup"><span data-stu-id="071f9-110">Embed IoT Central device state and measurement visuals directly within the Field Service mobile application.</span></span>
-   <span data-ttu-id="071f9-111">Gemme telemetridata fra loT Central i en Azure Blob og aktivere en integreret Power BI-visualisering af dataene.</span><span class="sxs-lookup"><span data-stu-id="071f9-111">Store telemetry data from IoT Central in an Azure blob and enable an embedded Power BI visualizing the data.</span></span>
-   <span data-ttu-id="071f9-112">Tillade, at teknikere sender kommandoer fra Field Service-mobilprogrammet tilbage til loT Central.</span><span class="sxs-lookup"><span data-stu-id="071f9-112">Allow technicians to send commands from the Field Service mobile application back to IoT Central.</span></span>


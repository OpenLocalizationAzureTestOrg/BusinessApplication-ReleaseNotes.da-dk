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
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 822172ac452b6513ec700dc421fa61b7faffa195
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
#  <a name="cfs---integration-with-iot-central"></a>CFS – Integration med IoT Central


[!include[banner](../../../../includes/banner.md)]

I den første fase af integrationen foregår integrationsløsningen primært via Microsoft Flow. Dette er en envejskommunikation fra IoT Central til Connected Field Service. IoT Central overvåger eksterne enheder, og alle mål, der overskrider de tærskelværdier, der er defineret i IoT Central, udløser en handling, der starter en advarsel i CFS. Field Service-chefer kan gruppere disse advarselsbeskeder efter kriterier, f.eks. kundeaktiv og hændelsestype.

> [!div class="mx-imgBorder"]
> ![](media/enhanced-iot-central-integration-1.png "Udvidet IoT Central-integration")
<!-- picture -->


Med produktfrigivelsen fra oktober 2018 kan teknikere få indsigt i og reagere på indsigt fra loT-enheder, når de befinder sig på et lokalt sted, og de kan have nogle muligheder, afhængigt af tilstanden af loT Central:

-   Integrere loT Central-enhedens tilstand og målvisualiseringer direkte i Field Service-mobilprogrammet.
-   Gemme telemetridata fra loT Central i en Azure Blob og aktivere en integreret Power BI-visualisering af dataene.
-   Tillade, at teknikere sender kommandoer fra Field Service-mobilprogrammet tilbage til loT Central.


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
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: a870e8f0d03f19cfd9ba3d93a7bcfce85524d332
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
# <a name="update-an-existing-power-bi-app-in-appsource"></a>Opdatere en eksisterende Power BI-app i AppSource

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



Administrationen af programlivscyklus (ALM) indeholder følgende funktioner:

- En app, der er baseret på et Power BI-arbejdsområde med flere indstillinger (parametre).
- Der er tre frigivelsesniveauer for en app: arbejdsområde (IGVF)--> pakke (frigivelseskandidat)--> publiceret app (indhold, der er offentligt tilgængeligt for installation via AppSource).
- På hvert frigivelsesniveau har vi en enkelt version: ét arbejdsområde i IGVF, én pakke, én publiceret app. Hvis du vil foretage en opdatering af en publiceret app, skal du installere en pakke. Installation af en pakke vil overskrive den publicerede app i AppSource.
- Udvikling af appen kan fortsætte hele tiden i IGVF-arbejdsområdet.
- Når du er klar til at oprette en frigivelseskandidat, skal du gemme pakken.


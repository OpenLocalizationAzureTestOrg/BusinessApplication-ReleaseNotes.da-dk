---
title: "Identificere, håndtere og rapportere fejl og skrive Null-værdier til databaser med lærred-apps"
description: "Appudviklere kan tage kontrollen over fejl, når de opstår, og som en sidegevinst skrive Null-værdier."
author: gregli-msft
manager: AnnBe
ms.date: 8/10/2018
ms.assetid: 461c1f60-ce73-e811-a96b-000d3a18c83b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: b6df0f68e3460358864533346e69a712684da551
ms.openlocfilehash: c198c53f04636c4cbef3f6723cfa5246afc06cfa
ms.contentlocale: da-dk
ms.lasthandoff: 08/16/2018

---
# <a name="catch-handle-and-report-errors-and-write-null-values-to-databases-with-canvas-apps-public-preview"></a>Identificere, håndtere og rapportere fejl og skrive Null-værdier til databaser med lærred-apps (Offentlig prøveversion)


[!include[banner](../../includes/banner.md)]

Der vil opstå fejl.  Lærred-apps har standardindstillinger, der anvendes, når fejl opstår, men det er ikke nødvendigvis de indstillinger, du vil bruge.  Med denne funktion kan du identificere, søge efter oplysninger om, udløse, undertrykke, logge og give besked om fejl til dine brugere.

Tidligere kunne man ikke skelne mellem fejl og Null-værdier, så det var et problem at skubbe Null-værdier til databaser.  Null er en legitim værdi i mange databasesystemer.  I og med at fejl er korrekt adskilt i lærred-apps, kan du skrive Null-værdier til alle databaser.


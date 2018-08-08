---
title: "Identificere, håndtere og rapportere fejl og skrive Null-værdier til databaser med lærred-apps"
description: "Appudviklere kan tage kontrollen over fejl, når de opstår, og som en sidegevinst skrive Null-værdier."
author: gregli
manager: AnnBe
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: gregli
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: e79ea4939906626d448c7a389f7507061bed596b
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
# <a name="catch-handle-and-report-errors-and-write-null-values-to-databases-with-canvas-apps"></a>Identificere, håndtere og rapportere fejl og skrive Null-værdier til databaser med lærred-apps


[!include[banner](../../includes/banner.md)]

Der vil opstå fejl.  Lærred-apps har standardindstillinger, der anvendes, når fejl opstår, men det er ikke nødvendigvis de indstillinger, du vil bruge.  Med denne funktion kan du identificere, søge efter oplysninger om, udløse, undertrykke, logge og give besked om fejl til dine brugere.

Tidligere kunne man ikke skelne mellem fejl og Null-værdier, så det var et problem at skubbe Null-værdier til databaser.  Null er en legitim værdi i mange databasesystemer.  I og med at fejl er korrekt adskilt i lærred-apps, kan du skrive Null-værdier til alle databaser.


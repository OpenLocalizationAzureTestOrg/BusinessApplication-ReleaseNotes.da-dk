---
title: Forbedringer af udvidelsesmulighed for platform
description: Forbedringer af udvidelsesmulighed for platform
author: ChrisGarty
manager: AnnBe
ms.date: 08/10/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: cgarty
audience: developer, customizer
ms.translationtype: HT
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: 374dad1c0120667f742ef9bd216b79c591c04742
ms.contentlocale: da-dk
ms.lasthandoff: 08/16/2018

---

# <a name="platform-extensibility-enhancements"></a>Forbedringer af udvidelsesmulighed for platform

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

Funktioner til forbedret udvidelsesmulighed:
- Gør det muligt at ændre en formular for at bruge et brugerdefineret mønster ved hjælp af en formularudvidelse. Dette gør det muligt for uafhængige softwareleverandører at tilføje faner og andre formulardele, der ikke passer til det oprindelige mønster. Udviklere kan nu **indstille mønster til brugerdefineret** og **gendanne oprindeligt mønster**.
- En udvidelse kan ændre **TableField.AssetClassification** så GDPR-dataklassifikationsoplysninger (generel forordning om databeskyttelse) kan leveres.
- Der er mulighed for formularudvidelsesmetoder til kald af metoder og kontrolelementer, der er tilføjet via andre udvidelser. Når en formular har en knap og nogle metoder tilføjet via udvidelser, vil fremtidige udvidelser til den pågældende formular f.eks. kunne foretage kald af den nye knap og metoder.
- Understøttelse af forespørgselsobjekt kan tilføjes for sætbaserede opdateringssætninger via en **update_recordset**-metode.
- En forespørgselsudvidelse kan føje en roddatakilde til en foreningsforespørgsel.
- Områder kan tilføjes i en visning ved hjælp af en udvidelse.
- Indstillingen **SupportsSetBasedSqlOperations** er mulig i dataenhedens udvidelser. Ja kan kun indstilles, hvis alle udvidelser er blevet indstillet til Ja, herunder basiselementet. Hvis en udvidelse eller basiselementet har værdien indstillet til Nej, vil kørselsresultatet være Nej.
- En formularudvidelse kan føje en arbejdsproces til en formular ved at redigere **WorkflowEnabled**, **WorkflowDataSource** og **WorkflowType**.
- Kommandokæden kan aktiveres for formularmetoder. Dette giver især mulighed for, at en udvidelse kan føje en arbejdsproces til en formular ved at tilsidesætte **canSubmitToWorkflow**-metoden. Bemærk, at hvis målformularmetoden er en kernemetode uden en X ++-tilsidesættelse, er det nødvendigt at genkompilere målformularen. 
- Kommandokæden kan aktiveres for dataenheder.
- Kommandokæden kan aktiveres på indlejrede typer inden for formularer, der indeholder datakilder og kontrolelementer.

For at få flere oplysninger om alle udvidelsesmulighederne skal du se [Startside for udvidelsesmuligheder](/dynamics365/unified-operations/dev-itpro/extensibility/extensibility-home-page).


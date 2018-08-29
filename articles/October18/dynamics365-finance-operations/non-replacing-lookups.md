---
title: Forbedret funktion i ikke-erstattende opslag
description: "Der er foretaget en række funktionelle forbedringer i ikke-erstattende opslag i Finance and Operations."
author: jasongre
manager: AnnBe
ms.date: 08/10/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: jasongre
audience: developer, admin, end user, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: bc5017cc0df74ed2071e2b77c65d62dc3cc5a198
ms.contentlocale: da-dk
ms.lasthandoff: 08/16/2018

---

# <a name="improved-behavior-of-non-replacing-lookups"></a>Forbedret funktion i ikke-erstattende opslag

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

Nogle opslag i Finance and Operations er *ikke-erstattende*, hvilket betyder, at når der vælges en værdi fra opslaget, erstatter det ikke det, der allerede var i feltet, men det sætter den valgte værdi ind i feltet. Opslag i dialogboksen **Avanceret filtrering/sortering** er f.eks. ikke-erstattende som standard.  

Funktionen i ikke-erstattende opslag er blevet forbedret på følgende måder: 
- Funktionen til autoudfyldning er slået fra for ikke-erstattende opslag. 
- Kun tegn, der er indtastet efter, at opslaget er blevet åbnet, bruges til at positionere i opslagsgitteret.
- Den valgte værdi fra opslaget føjes til det, der var i feltet, før opslaget blev åbnet (dvs. ethvert tegn, der indtastes, mens opslaget er åbent, erstattes, når den valgte værdi fra opslaget tilføjes).  
- Der vises et nyt ikon på ikke-erstattende opslag for at adskille dem visuelt fra almindelige opslag.

Disse justeringer gør det lettere for brugerne at filtrere data ved hjælp af dialogboksen **Avanceret filtrering/sortering**.


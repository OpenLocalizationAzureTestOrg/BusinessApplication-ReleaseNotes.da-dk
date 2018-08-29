---
title: Skjule hyperlinks
description: Udviklere kan skjule hyperlinks til kontrolelementer
author: jasongre
manager: AnnBe
ms.date: 08/10/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: jasongre
audience: developer
ms.translationtype: HT
ms.sourcegitcommit: 7d6f339c1e92c937c47306db6da360eb8fdd5d77
ms.openlocfilehash: 76aaf7ff6926e396df13155a5df8bd2013d407c2
ms.contentlocale: da-dk
ms.lasthandoff: 08/16/2018

---

# <a name="suppressing-hyperlinks"></a>Skjule hyperlinks

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]

Udviklere er i stand til at skjule hyperlinks på formularkontrolelementer ved at indstille **EnableFormRef**-egenskaben til **Nej**. Denne egenskab kan indstilles i både formularer og formularudvidelser. Når et hyperlink er skjult, er den tilsvarende **Vis detaljer**-indstilling i højrekliksgenvejsmenuen også skjult. 
 
Når brugere for øjeblikket klikker på nogle hyperlinks, medfører det et forsøg på navigation og derefter en fejlmeddelelse, da der ikke er nogen formular at åbne. At skjule hyperlinks i disse scenarier vil forbedre brugeroplevelsen ved at fjerne disse forvirrende links.  


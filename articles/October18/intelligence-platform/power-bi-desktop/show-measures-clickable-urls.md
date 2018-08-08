---
title: "Vise målinger som klikbare URL-adresser"
description: "Brug målinger til at definere et link for at navigere fra en rapport til en anden webadresse."
author: MI77
manager: kimani
ms.date: 6/22/18
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: willthom
audience: end user, developer, citizen developer, customizer, business analyst, IT pro
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 0ae8e309078c1aea0a4b24abe8eb4b253db34b29
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---

# <a name="show-measures-as-clickable-urls"></a>Vise målinger som klikbare URL-adresser

[!include[banner](../../../includes/banner.md)]

Slutbrugerne skal nemt kunne navigere mellem rapporter eller fra rapporter til andre programmer, mens de stadig bevarer konteksten af de data, de ser på. Målinger kan generere URL-adresser for at tillade navigation og kan vises som links, der gør det nemt at flytte mellem rapporter eller programmer.

En DAX-måling kan returnere en URL-adresse med tilføjede filtre, der svarer til de datavalg, som er foretaget i rapporten. Dette kan vises i tabel- og matrixvisuals som et link, der justeres dynamisk på basis af de valg, der foretages. Slutbrugerne kan klikke på dette link for at åbne en ny fane, hvor målrapporten vises.

DAX-målingen kan se således ud:

`Link = “http://app.powerbi.com/Report/GUID/&filter=Table1/Category eq “ & SELECTEDVALUE(Products[Category])`

<!--
### Who uses this feature
This feature is intended for end users, developers, citizen developers, customizers, business analysts, and IT pros. No additional setup is required.
## Status
### Development status
In development
#### Target timeframe
October ‘18
-->


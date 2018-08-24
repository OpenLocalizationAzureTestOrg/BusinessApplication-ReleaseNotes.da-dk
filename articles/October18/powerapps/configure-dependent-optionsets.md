---
title: "Konfigurere afhængige grupperede indstillinger"
description: "Konfigurer afhængige grupperede indstillinger for at levere overlappende rullemenuer i dine apps og sikre simpel datavalidering mellem rullemenuer."
author: clwesene
manager: AnnBe
ms.date: 7/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: clwesene
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 22c0a725d5f46f6ec89fafeb05ea1b00fb183fc1
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
# <a name="configure-dependent-option-sets"></a>Konfigurere afhængige grupperede indstillinger

[!include[powerapps banner](../includes/powerapps.md)]




Ved at oprette afhængige grupperede indstillinger kan du nemt fastsætte regler mellem grupperede indstillinger for at sikre, at de valgte værdier giver mening. Du kan for eksempel oprette grupperede indstillinger som **Land/område** og **Stater**. Hvis en bruger vælger **USA** i rullemenuen for den første grupperede indstilling, bør rullemenuen for den anden grupperede indstilling kun vise de stater, der ligger i det land/område. Du kan sørge for, at dataene stemmer overens og er korrekte ved at definere denne struktur på objektniveau til anvendelse i alle apps.


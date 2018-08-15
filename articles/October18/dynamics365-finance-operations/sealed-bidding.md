---
title: Forseglet budafgivelse
description: Forseglet budafgivelse
author: ShylaThompson
manager: AnnBe
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: shylaw
audience: end-user
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 2405e676929ee3a49bce634b83c744f138fe401a
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---

# <a name="sealed-bidding"></a>Forseglet budafgivelse 

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



Funktionerne for tilbudsanmodningen udvides til at understøtte forseglet budafgivelse. En leverandør kan angive og indsende et tilbud, herunder vedhæftede .pdf-filer, via en særlig formular i brugergrænsefladen for leverandørsamarbejde. Buddet kan ikke ses i forbindelse med den tilbudsanmodning, som indkøberne har adgang til. Buddet gemmes i krypteret format. Det er kun den kontaktperson, der er registreret som leverandørkontakt og har fået rolletilladelserne, som har adgang til buddet, før dets forsegling brydes. Indkøberne kan bryde forseglingen af buddene efter udløbsdatoen, og de kan herefter se leverandørens bud i forbindelse med tilbudsanmodningen. Enhver brugerhandling, der læser eller skriver i buddet før udløbsdatoen, logføres til overvågning, og disse oplysninger vil være tilgængelige for leverandøren og indkøberne, når forseglingen af buddet brydes.  


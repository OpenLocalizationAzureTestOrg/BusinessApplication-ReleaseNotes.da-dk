---
title: "Understøttelse af Azure Active Directory-programgodkendelse"
description: "Understøttelse af Azure Active Directory-programgodkendelse"
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: cba1b690-0d07-4400-8bf6-80de880157ba
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 3c644df8af2bbc07c910cc7dd6581d55fc95686e
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
# <a name="azure-active-directory-application-authentication-public-preview"></a>Azure Active Directory-programgodkendelse (offentlig prøveversion)

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]




Vi tilføjer programgodkendelse i Power BI Embedded. Dette forbedrer installationen, sikkerheden og administrationen af programlivscyklus for Power BI Embedded-programmer. På nuværende tidspunkt kræver opbygning af et Power BI Embedded-program oprettelse af en overordnet brugerkonto, lagring af legitimationsoplysninger for den pågældende konto og derefter brug af dem i programkoden for at kunne udføre ikke-interaktiv logon på Power BI. Azure Active Directory har særlig understøttelse af programmer, der godkendes ved hjælp af deres egen identitet uden en brugerkontekst. Denne understøttelse, der alene er udviklet til app-godkendelse, giver større kontrol og sikkerhed, har færre begrænsninger og er den anbefalede fremgangsmåde. 


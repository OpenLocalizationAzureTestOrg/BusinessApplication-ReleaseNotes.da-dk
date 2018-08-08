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
# <a name="azure-active-directory-application-authentication-public-preview"></a><span data-ttu-id="820dc-103">Azure Active Directory-programgodkendelse (offentlig prøveversion)</span><span class="sxs-lookup"><span data-stu-id="820dc-103">Azure Active Directory application authentication (Public Preview)</span></span>


[!include[banner](../../../includes/banner.md)]

<span data-ttu-id="820dc-104">Vi tilføjer programgodkendelse i Power BI Embedded.</span><span class="sxs-lookup"><span data-stu-id="820dc-104">We are adding application authentication to Power BI Embedded.</span></span> <span data-ttu-id="820dc-105">Dette forbedrer installationen, sikkerheden og administrationen af programlivscyklus for Power BI Embedded-programmer.</span><span class="sxs-lookup"><span data-stu-id="820dc-105">This will enhance the deployment, security, and application lifecycle management Power BI Embedded applications.</span></span> <span data-ttu-id="820dc-106">På nuværende tidspunkt kræver opbygning af et Power BI Embedded-program oprettelse af en overordnet brugerkonto, lagring af legitimationsoplysninger for den pågældende konto og derefter brug af dem i programkoden for at kunne udføre ikke-interaktiv logon på Power BI.</span><span class="sxs-lookup"><span data-stu-id="820dc-106">Currently, building a Power BI Embedded application requires the creation of a master user account, storing the credentials for that account, and then using them in the application code for performing non-interactive sign-in to Power BI.</span></span> <span data-ttu-id="820dc-107">Azure Active Directory har særlig understøttelse af programmer, der godkendes ved hjælp af deres egen identitet uden en brugerkontekst.</span><span class="sxs-lookup"><span data-stu-id="820dc-107">Azure Active Directory has special support for applications authenticating using their own identity without a user context.</span></span> <span data-ttu-id="820dc-108">Denne understøttelse, der alene er udviklet til app-godkendelse, giver større kontrol og sikkerhed, har færre begrænsninger og er den anbefalede fremgangsmåde.</span><span class="sxs-lookup"><span data-stu-id="820dc-108">This support, designed for app-only authentication, allows higher control and security, has fewer limitations, and is the recommended approach.</span></span> 


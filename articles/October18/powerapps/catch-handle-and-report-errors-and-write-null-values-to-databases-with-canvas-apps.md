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
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 6b7018a8f71dfbdc937430575e6c561b0d1a4e05
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---
# <a name="catch-handle-and-report-errors-and-write-null-values-to-databases-with-canvas-apps"></a><span data-ttu-id="93cd6-103">Identificere, håndtere og rapportere fejl og skrive Null-værdier til databaser med lærred-apps</span><span class="sxs-lookup"><span data-stu-id="93cd6-103">Catch, handle, and report errors, and write Null values to databases with canvas apps</span></span>

[!include[powerapps banner](../includes/powerapps.md)]




<span data-ttu-id="93cd6-104">Der vil opstå fejl.</span><span class="sxs-lookup"><span data-stu-id="93cd6-104">Errors happen.</span></span>  <span data-ttu-id="93cd6-105">Lærred-apps har standardindstillinger, der anvendes, når fejl opstår, men det er ikke nødvendigvis de indstillinger, du vil bruge.</span><span class="sxs-lookup"><span data-stu-id="93cd6-105">Canvas apps provide a default behavior when they do, but this may not always match what you want.</span></span>  <span data-ttu-id="93cd6-106">Med denne funktion kan du identificere, søge efter oplysninger om, udløse, undertrykke, logge og give besked om fejl til dine brugere.</span><span class="sxs-lookup"><span data-stu-id="93cd6-106">With this feature, you can catch, interrogate, throw, suppress, log, and message errors to your users.</span></span>

<span data-ttu-id="93cd6-107">Tidligere kunne man ikke skelne mellem fejl og Null-værdier, så det var et problem at skubbe Null-værdier til databaser.</span><span class="sxs-lookup"><span data-stu-id="93cd6-107">Errors and Null values were previously indistinguishable, so pushing Null values to databases was a problem.</span></span>  <span data-ttu-id="93cd6-108">Null er en legitim værdi i mange databasesystemer.</span><span class="sxs-lookup"><span data-stu-id="93cd6-108">Null is a legitimate value in many database systems.</span></span>  <span data-ttu-id="93cd6-109">I og med at fejl er korrekt adskilt i lærred-apps, kan du skrive Null-værdier til alle databaser.</span><span class="sxs-lookup"><span data-stu-id="93cd6-109">With errors properly separated out in canvas apps, you can write Null values to all databases.</span></span>


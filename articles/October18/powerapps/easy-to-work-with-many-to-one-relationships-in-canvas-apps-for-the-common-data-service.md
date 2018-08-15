---
title: "Nemt arbejde med mange til én-relationer i lærred-apps for Common Data Service til apps"
description: "Det er ikke længere nødvendigt at sammenføje eller slå op manuelt. PowerApps udvider automatisk mange til én-relationer, så de nødvendige oplysninger kun er et klik væk."
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
ms.openlocfilehash: bdd0b30bfa06bf223e9a64f838ed4b16a62dcc44
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---
# <a name="easy-to-work-with-many-to-one-relationships-in-canvas-apps-for-common-data-service-for-apps"></a><span data-ttu-id="d35a8-104">Nemt arbejde med mange til én-relationer i lærred-apps for Common Data Service til apps</span><span class="sxs-lookup"><span data-stu-id="d35a8-104">Easy to work with many-to-one relationships in canvas apps for Common Data Service for Apps</span></span>

[!include[powerapps banner](../includes/powerapps.md)]




<span data-ttu-id="d35a8-105">Det er afgørende for de fleste virksomhedsprogrammer at kunne arbejde med relationsdata.</span><span class="sxs-lookup"><span data-stu-id="d35a8-105">Working with relational data is key to most business applications.</span></span> <span data-ttu-id="d35a8-106">Men det kan være kedeligt at skrive forespørgsler om de nødvendige oplysninger, sammenkæde med fremmede nøgler og kontrollere projektionen.</span><span class="sxs-lookup"><span data-stu-id="d35a8-106">Yet it can be tedious to write queries that pull in the necessary information, join on foreign keys, and control the projection.</span></span>

<span data-ttu-id="d35a8-107">Med denne funktion bliver det hele meget nemmere for udviklere af lærred-apps, når de anvender Common Data Service til apps.</span><span class="sxs-lookup"><span data-stu-id="d35a8-107">With this feature, it all becomes a lot easier for canvas app makers when they use Common Data Service for Apps.</span></span> <span data-ttu-id="d35a8-108">I CDS til apps-standardmodellen er der for eksempel et firmaobjekt med et opslag for PrimaryContact, der fører til kontaktobjektet.</span><span class="sxs-lookup"><span data-stu-id="d35a8-108">For example, in the CDS for Apps standard model, there is an Account entity with a lookup for PrimaryContact that points to the Contacts entity.</span></span> <span data-ttu-id="d35a8-109">Forestil dig, at du vil have vist efternavnet på den primære kontaktperson i kontrolelementet for et galleri.</span><span class="sxs-lookup"><span data-stu-id="d35a8-109">Let's say you need to display the last name of the primary contact in a gallery control.</span></span> <span data-ttu-id="d35a8-110">Så skal du blot skrive **ThisItem.PrimaryContact.LastName**.</span><span class="sxs-lookup"><span data-stu-id="d35a8-110">All you need to write is **ThisItem.PrimaryContact.LastName**.</span></span> <span data-ttu-id="d35a8-111">Datakilden for kontakter behøver ikke engang at blive indlæst.</span><span class="sxs-lookup"><span data-stu-id="d35a8-111">The Contacts data source doesn't even need to be loaded.</span></span> <span data-ttu-id="d35a8-112">PowerApps analyserer appen for at afgøre, hvilke opslag der er acceptable, og for kun at hente de felter, der er nødvendige for projektionen.</span><span class="sxs-lookup"><span data-stu-id="d35a8-112">PowerApps analyzes the app to determine which lookups are desired and to bring in only the fields that are required for the projection.</span></span>


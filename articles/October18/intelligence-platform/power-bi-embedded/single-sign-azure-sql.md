---
title: Enkeltlogon for Azure SQL Database
description: Enkeltlogon for Azure SQL Database
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: defe56c9-38a5-48c6-ba86-e1c6371bfb75
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: c8d95cb4e81d995c1d99a28ea0516194cfa184c2
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---
#  <a name="power-bi-embedded-single-sign-on-for-azure-sql-database"></a><span data-ttu-id="3c065-103">Power BI Embedded-enkeltlogon for Azure SQL Database</span><span class="sxs-lookup"><span data-stu-id="3c065-103">Power BI Embedded single sign-on for Azure SQL Database</span></span>

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]




<span data-ttu-id="3c065-104">På denne måde kan Power BI Embedded overholde sikkerhedsindstillinger, der er konfigureret på datakildeniveau.</span><span class="sxs-lookup"><span data-stu-id="3c065-104">This enables Power BI Embedded to respect security settings that are configured at the data source level.</span></span> <span data-ttu-id="3c065-105">Power BI Embedded har ingen indsigt i programmets bruger.</span><span class="sxs-lookup"><span data-stu-id="3c065-105">Power BI Embedded has no awareness of the application’s user.</span></span> <span data-ttu-id="3c065-106">For programmer, der skal have konfigureret sikkerhed på rækkeniveau i Azure SQL Database, er der behov for at overføre programmets brugeroplysninger til SQL Database.</span><span class="sxs-lookup"><span data-stu-id="3c065-106">For applications that want to set row-level security in Azure SQL Database, there is a need to pass the application’s user information to SQL Database.</span></span> <span data-ttu-id="3c065-107">Hvis du aktiverer indstillingen for enkeltlogon, sender Power BI Embedded godkendte Azure Active Directory-legitimationsoplysninger for brugere, der skaffer adgang til rapporter i forespørgslerne til Azure SQL Database.</span><span class="sxs-lookup"><span data-stu-id="3c065-107">By enabling the single sign-on option, Power BI Embedded sends authenticated Azure Active Directory credentials for users accessing reports in the queries to the Azure SQL Database.</span></span> 


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
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 4e774f63cd021959f0fe95f44598a2d937ada967
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
#  <a name="power-bi-embedded-single-sign-on-for-azure-sql-database"></a>Power BI Embedded-enkeltlogon for Azure SQL Database

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]




På denne måde kan Power BI Embedded overholde sikkerhedsindstillinger, der er konfigureret på datakildeniveau. Power BI Embedded har ingen indsigt i programmets bruger. For programmer, der skal have konfigureret sikkerhed på rækkeniveau i Azure SQL Database, er der behov for at overføre programmets brugeroplysninger til SQL Database. Hvis du aktiverer indstillingen for enkeltlogon, sender Power BI Embedded godkendte Azure Active Directory-legitimationsoplysninger for brugere, der skaffer adgang til rapporter i forespørgslerne til Azure SQL Database. 


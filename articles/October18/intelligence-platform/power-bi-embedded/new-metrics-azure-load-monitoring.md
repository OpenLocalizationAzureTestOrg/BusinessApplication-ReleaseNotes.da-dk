---
title: "Nye målepunkter for Azure-overvågning af arbejdsbelastning"
description: "Fire nye målepunkter er blevet tilknyttet for at overvåge Power BI Embedded-ressourceforbruget og udløse handlinger, når konfigurerbare tærskelværdier overskrides."
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 082d21ac-805e-4007-8810-f1838369569c
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 38c5ad6fa4ff1160d482cb5d62a7701990bff15a
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---
#  <a name="new-metrics-for-azure-workload-monitoring"></a>Nye målepunkter for Azure-overvågning af arbejdsbelastning

[!include[intelligence-platform banner](../../includes/intelligence-platform.md)]



Da nye opgaver nu er tilgængelige i Power BI-sideinddelte rapporter og dataflow, vil tre nye målepunkter blive tilknyttet for at overvåge Power BI Embedded-ressourceforbruget og udløse handlinger, når de konfigurerbare tærskelværdier overskrides. De nye målepunkter vil afspejle hver af arbejdsbelastningerne i ressourcen. De nye målepunkter er:

•   CPU-forbrug •   Hukommelsesforbrug •   Forbrug af hukommelseallokering (inkl. sideopdeling af hukommelse)

Udviklere kan bruge Azure til at definere tærskelværdier, der udløser bestemte handlinger ved hjælp af påmindelser, f.eks. automatisk opskalering af ressourcen, hver gang en bestemt skærm overskrider en fastlagt grænse.


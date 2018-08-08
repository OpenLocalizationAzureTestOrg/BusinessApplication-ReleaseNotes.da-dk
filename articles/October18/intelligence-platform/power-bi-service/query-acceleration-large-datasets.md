---
title: "Acceleration af forespørgsler til store datasæt"
description: "Acceleration af forespørgsler til store datasæt"
author: MargoC
manager: AnnBe
ms.date: 07/22/2018
ms.assetid: 04524b66-4727-4ce6-9cca-2b1439428497
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 285bf3e5cbfb965d27f0b717b5cdc8fa332e28d6
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---

#  <a name="query-acceleration-for-large-datasets-public-preview"></a>Acceleration af forespørgsler til store datasæt (offentlig prøveversion)

[!include[banner](../../../includes/banner.md)]

Brugerne kan oprette [DirectQuery](https://docs.microsoft.com/power-bi/desktop-directquery-about)-modeller over datakilder af enhver størrelse, f.eks. Spark og Azure SQL Data Warehouse, og derefter fremskynde almindelige forespørgsler ved at oprette aggregeringer over nogle af dataene i hukommelsen. Almindelige forespørgsler bruger den aggregerede cache til at returnere resultater i et brøkdel af et sekund i stedet for direkte forespørgsler til kilden. Brugerne kan oprette datasæt af omfattende størrelse og stadig benytte interaktive forespørgsler.


---
title: Dobbelt valuta
description: Dobbelt valuta
author: MargoC
manager: AnnBe
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: end-user
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 7256af54b5d02188d150b37520142196b0b38b4a
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
#  <a name="dual-currency"></a>Dobbelt valuta

[!include[dynamics365-finance-operations banner](../includes/dynamics365-finance-operations.md)]



Rapporteringsvalutaen får nyt formål som en anden faktisk regnskabsvaluta. Rapporteringsvalutaen skal fortsat beregnes for alle transaktioner, der bogføres i finans.  Nogle finansprocesser udvides, og der tilføjes en ny kladde, der kan bruges til at bogføre posteringer i rapporteringsvalutaen. For forskellige reskontrokladder, f.eks. anlægsaktiver, sker der større ændringer. For anlægsaktiver begynder vi at vedligeholde alle posteringer i reskontrokladden til rapporteringsvalutaen. Når du kører afskrivning, afskrives beløb i rapporteringsvalutaen ved hjælp af afskrivningsmetoderne, ligesom med regnskabsvalutaen. Andre berørte reskontrokladdemoduler er Kreditorer, Debitorer og Likviditetsstyring.


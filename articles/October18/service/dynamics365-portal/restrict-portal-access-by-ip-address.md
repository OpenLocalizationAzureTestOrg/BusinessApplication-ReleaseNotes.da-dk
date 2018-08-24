---
title: "Begrænse portaladgang efter IP-adresse"
description: "Begrænsning af portaladgang til kun et undersæt af brugere ved at definere tilladte IP-intervaller"
author: dileeps
manager: prvenka
ms.date: 07/22/2018
ms.assetid: 143d1e32-f70e-478c-b8c1-d25b37782653
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: dileeps
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 8259579ac1b19d93a71a9bc7db8ae07fb3c6a5cb
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
# <a name="restrict-portal-access-by-ip-address"></a>Begrænse portaladgang efter IP-adresse

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]




Sikkerhed er yderst vigtigt for programmer, og det er endnu mere afgørende for et eksternt orienteret program som f.eks. Dynamics 365 Portal. Som en del af denne frigivelse tilføjer vi muligheder, så kunderne kan begrænse adgangen til deres portaler fra visse IP-adresser. Det gør det nemmere for organisationer, der har brug for at begrænse deres portaler fra faste lokationer på samme måde som interne firmanetværk. Desuden hjælper det kunder, der er i udviklingsfasen og ønsker at sikre, at deres data ikke bliver lækket på grund af en forkert konfiguration.

Denne funktion giver administratorer mulighed for at definere en liste over IP-adresser, der har adgangstilladelse til din portal. Listen over tilladte kan omfatte individuelle IP-adresser eller et interval af IP-adresser, der er defineret af en undernetmaske. Når en anmodning til portalen oprettes af en bruger, evalueres dennes IP-adresse i forhold til listen over tilladte. Hvis IP-adressen ikke står listen, svarer portalen med en HTTP 403-statuskode.

<!--
### Who uses this feature
This feature is intended for administrators who are managing portals.
## Status
### Development status
Generally available
#### Target timeframe
October 2018
### Availability 
Cloud
### Regional availability
Global
-->


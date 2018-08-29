---
title: "Hybridforbindelser for virksomheder via datagateway i det lokale miljø"
description: "Hybridforbindelser for virksomheder via datagateway i det lokale miljø"
author: shellyhaverkamp
manager: AnnBe
ms.date: 8/16/2018
ms.assetid: 5b0c45ea-97e4-4e6f-8555-f2bc05ccb336
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: tpalmer
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: a1561a448e7906d9509fc41293ac499a4722f458
ms.openlocfilehash: 29480860b839d38f18ef16541c9f2c3a45c0dff3
ms.contentlocale: da-dk
ms.lasthandoff: 08/16/2018

---
#  <a name="enterprise-grade-hybrid-connectivity-using-the-on-premises-data-gateway"></a>Hybridforbindelser for virksomheder via datagateway i det lokale miljø


[!include[banner](../../includes/banner.md)]

Denne produktfrigivelse indeholder flere opdateringer, der er relateret til forbedring af datagatewayen i det lokale miljø.

## <a name="certified-custom-connectors-in-power-bi-desktop"></a>Godkendte brugerdefinerede connectorer i Power BI Desktop

Tidligere i år annoncerede vi understøttelse af brugerdefinerede connectorer i Power BI Desktop ved hjælp af M-sprogets effektive funktioner, der gør det muligt for partnere at skrive deres egne connectorer og distribuere dem til enhver Power BI-bruger.

Understøttelse af brugerdefinerede connectorer i gatewayen giver brugerne mulighed for at holde de rapporter, de har oprettet med brugerdefinerede connectorer, opdateret i Power BI-tjenesten ved at opdatere dataene ved hjælp af datagatewayen i det lokale miljø.

![Understøttelse af brugerdefinerede connectorer i datagatewayen i det lokale miljø](media/custom-connectors-support-premises-data-gateway-1.jpg "Understøttelse af brugerdefinerede connectorer i datagatewayen i det lokale miljø")

## <a name="gateway-multi-geo-support-for-power-bi-premium"></a>Understøttelse af gateway med flere geokoder for Power BI Premium
På grund af ændrede prioriteter er tidsrammen for denne funktion ikke fastlagt. Mens undersøgelsen fortsætter, skal du stemme på forslaget på https://ideas.powerbi.com for at hjælpe med at prioritere.

## <a name="guarantee-high-availability-of-gateways-via-clustering"></a>Sikrer en høj tilgængelighed af gateways via klyngedannelse
De funktioner vedrørende høj tilgængelighed i datagatewayen i det lokale miljø, som vi frigav i november 2017, er ved at blive overført fra offentlig prøveversion til generel tilgængelighed. En del af denne indsats omfatter flere forbedringer af oplevelser, især hvad angår bedre fejlrapportering og forbedret brugeroplevelse.

## <a name="improved-kerberos-single-sign-on-support"></a>Forbedret understøttelse af Kerberos-enkeltlogon
Vi har planer om at understøtte flere domæner i vores SSO-implementering samt gøre det nemmere at teste SSO-forbindelsen og diagnosticere problemer.

![Forbedret understøttelse af Kerberos-enkeltlogon](media/improved-kerberos-single-sign-support-premises-data-gateway-1.png "Forbedret understøttelse af Kerberos-enkeltlogon")

## <a name="saml-based-single-sign-on-for-supported-data-sources"></a>SAML-baseret enkeltlogon til understøttede datakilder

Sidste år føjede vi understøttelse af Kerberos-enkeltlogon til gatewayen for flere kilder, herunder SQL Server, SAP HANA og Teradata.

I denne periode har vi planer om fortsat at investere i understøttelse af enkeltlogon ved at tilføje understøttelse af SAML-baserede enkeltlogon-scenarier for understøttede datakilder.

<a name="additional-cloud-data-refresh-capabilities-for-parity-with-pbi-desktop"></a>  
## <a name="additional-cloud-data-refresh-capabilities-for-parity-with-power-bi-desktop"></a>Yderligere funktioner til opdatering af data i skyen for paritet med Power BI Desktop

Der er nogle tilfælde, hvor et Power BI-datasæt uden problemer kan opdateres i Power BI Desktop, men ikke kan opdateres i Power BI-tjenesten. Dette sker typisk på grund af indstillingerne for beskyttelse af personlige oplysninger tilhørende de datakilder, der anvendes i dette datasæt.

I Power BI Desktop kan brugere ændre indstillingerne for beskyttelse af personlige oplysninger for hver datakilde, så datasættet uden videre kan opdateres. Vi arbejder på at give brugerne mulighed for at opdatere disse datasæt i Power BI-tjenesten uden problemer.

<a name="improved-data-sources-settings-experience"></a>  
## <a name="improved-data-source-settings-experience"></a>Forbedret oplevelse af datakildeindstillinger

Vi har planer om at forbedre oplevelsen med at oprette datakilder på "Administrer gateways"-siden i Power BI-tjenesten ved at tilføje nogle af de mest efterspurgte funktioner, f.eks. muligheden for at springe testforbindelsestrinnet over, omdøbe datakilder og oprette flere datakilder med forskellige legitimationsoplysninger.

## <a name="tenant-level-administration-of-on-premises-data-gateway"></a>Administration på lejerniveau i datagatewayen i det lokale miljø
Vi vil give lejeradministratorer mulighed for at administrere alle datagateways i det lokale miljø i deres lejer gennem både en API og brugergrænsefladen.

## <a name="basic-traffic-load-balancing-in-the-on-premises-data-gateway"></a>Grundlæggende justering af trafikbelastning i datagatewayen i det lokale miljø
Vi har planer om at introducere en mulighed for at opdele trafik i forbindelse med anmodninger for en given gatewayklynge på tværs af alle gateways i den klynge.
Gatewayadministratoren vil kunne slå denne funktion til og fra i overensstemmelse med organisationens behov.


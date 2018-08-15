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
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 6e8406073dd7c7d202d8152877222da082d27bd6
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---
# <a name="restrict-portal-access-by-ip-address"></a><span data-ttu-id="6e8f2-103">Begrænse portaladgang efter IP-adresse</span><span class="sxs-lookup"><span data-stu-id="6e8f2-103">Restrict portal access by IP address</span></span>

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]




<span data-ttu-id="6e8f2-104">Sikkerhed er yderst vigtigt for programmer, og det er endnu mere afgørende for et eksternt orienteret program som f.eks. Dynamics 365 Portal.</span><span class="sxs-lookup"><span data-stu-id="6e8f2-104">Security is a key concern for applications and it becomes more paramount for an external-facing application like Dynamics 365 Portal.</span></span> <span data-ttu-id="6e8f2-105">Som en del af denne frigivelse tilføjer vi muligheder, så kunderne kan begrænse adgangen til deres portaler fra visse IP-adresser.</span><span class="sxs-lookup"><span data-stu-id="6e8f2-105">As part of this release, we will add capabilities for customers to be able to restrict access to their portals from certain IP addresses.</span></span> <span data-ttu-id="6e8f2-106">Det gør det nemmere for organisationer, der har brug for at begrænse deres portaler fra faste lokationer på samme måde som interne firmanetværk.</span><span class="sxs-lookup"><span data-stu-id="6e8f2-106">This will help organizations that are looking to restrict their portals from fixed locations like internal company networks.</span></span> <span data-ttu-id="6e8f2-107">Desuden hjælper det kunder, der er i udviklingsfasen og ønsker at sikre, at deres data ikke bliver lækket på grund af en forkert konfiguration.</span><span class="sxs-lookup"><span data-stu-id="6e8f2-107">Also, this will help customers who are in a development phase and want to make sure their data doesn't get leaked because of a bad configuration.</span></span>

<span data-ttu-id="6e8f2-108">Denne funktion giver administratorer mulighed for at definere en liste over IP-adresser, der har adgangstilladelse til din portal.</span><span class="sxs-lookup"><span data-stu-id="6e8f2-108">This feature would allow administrators to define a list of IP addresses that are allowed to access your portal.</span></span> <span data-ttu-id="6e8f2-109">Listen over tilladte kan omfatte individuelle IP-adresser eller et interval af IP-adresser, der er defineret af en undernetmaske.</span><span class="sxs-lookup"><span data-stu-id="6e8f2-109">The allow list can include individual IP addresses or a range of IP addresses defined by a subnet mask.</span></span> <span data-ttu-id="6e8f2-110">Når en anmodning til portalen oprettes af en bruger, evalueres dennes IP-adresse i forhold til listen over tilladte.</span><span class="sxs-lookup"><span data-stu-id="6e8f2-110">When a request to the portal is generated from any user, their IP address is evaluated against the allow list.</span></span> <span data-ttu-id="6e8f2-111">Hvis IP-adressen ikke står listen, svarer portalen med en HTTP 403-statuskode.</span><span class="sxs-lookup"><span data-stu-id="6e8f2-111">If the IP address is not in the list, the portal replies with an HTTP 403 status code.</span></span>

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


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
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 12b5d7ce158263a16f558e96e9cbe3c7dc4f43a6
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---
# <a name="easy-to-work-with-many-to-one-relationships-in-canvas-apps-for-common-data-service-for-apps"></a>Nemt arbejde med mange til én-relationer i lærred-apps for Common Data Service til apps


[!include[banner](../../includes/banner.md)]

Det er afgørende for de fleste virksomhedsprogrammer at kunne arbejde med relationsdata. Men det kan være kedeligt at skrive forespørgsler om de nødvendige oplysninger, sammenkæde med fremmede nøgler og kontrollere projektionen.

Med denne funktion bliver det hele meget nemmere for udviklere af lærred-apps, når de anvender Common Data Service til apps. I CDS til apps-standardmodellen er der for eksempel et firmaobjekt med et opslag for PrimaryContact, der fører til kontaktobjektet. Forestil dig, at du vil have vist efternavnet på den primære kontaktperson i kontrolelementet for et galleri. Så skal du blot skrive **ThisItem.PrimaryContact.LastName**. Datakilden for kontakter behøver ikke engang at blive indlæst. PowerApps analyserer appen for at afgøre, hvilke opslag der er acceptable, og for kun at hente de felter, der er nødvendige for projektionen.


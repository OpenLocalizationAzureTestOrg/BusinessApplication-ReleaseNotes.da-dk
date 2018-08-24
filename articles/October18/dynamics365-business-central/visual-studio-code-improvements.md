---
title: Forbedret AL-oplevelse af Visual Studio-kode
description: Forbedringer af AL-oplevelsen af Visual Studio-kode
author: pborring
manager: edupont04
ms.date: 07/22/2018
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: pborring
audience: developer, customizer
ms.translationtype: HT
ms.sourcegitcommit: 0b40bb3c98145f5a260f412701a884a5936174ce
ms.openlocfilehash: 161da5108c31c88f8e0f254abcf0f4b0fa6e950c
ms.contentlocale: da-dk
ms.lasthandoff: 07/18/2018

---

# <a name="improved-visual-studio-code-al-experience"></a>Forbedret AL-oplevelse af Visual Studio-kode

[!include[banner](../../includes/banner.md)]

Oprettelse af udvidelser er tilpasningsmåden for Business Central. I produktfrigivelsen fra oktober 2018 tilføjes forbedringer af produktiviteten i udviklingsarbejdet samt understøttelse af flere udvidelsesscenarier.

Med forbedringerne af værktøjs- og udvidelsesfunktionerne kan udviklere være mere produktive, når de udvikler og foretager fejlfinding i forbindelse med løsninger, og de får flere muligheder for at imødekomme kundernes tilpasningskrav ved hjælp af udvidelser.

## <a name="sandbox-with-production-data"></a>Sandkasse med produktionsdata
Et almindeligt scenarie, når du arbejder med sandkasser, især i forbindelse med test eller fejlfinding, er ønsket om at have tilgængelige produktionsdata. Med denne frigivelse tilføjer vi muligheden for at oprette en sandkasse, der er baseret på en kopi af den seneste skysikkerhedskopi af produktionsdataene. For at minimere tværkommunikation med integrationer, der er angivet i produktionsdataene, vil disse integrationer være deaktiveret under oprettelsen af sandkassen. Administratorer kan med forsigtighed aktivere eller omkonfigurere disse integrationer efter behov for at understøtte den tilsigtede sandkassebrug.

## <a name="new-object-extensions"></a>Nye objektudvidelser
Du kan nu udvide følgende:

- Fasttekster (indstillinger) fra basisprogrammet samt oprettelse af nye, udvidelige fasttekster i dine udvidelser.
- Rapportdatasæt i udvidelser. Rapportdatalayout er stadig et spørgsmål om erstatning.
- Feltgrupper.

## <a name="event-discoverability"></a>Registrering af hændelser
Et kerneaspekt under oprettelse af udvidelser er at abonnere på hændelser. En almindelig udfordring er dog kendskab til, hvilke hændelser der er tilgængelige i en given brugerproces. Fejlfinding kan hjælpe, men vil kun vise hændelser, der allerede abonneres på. For at støtte registreringen af hændelser og udvidelsespunkter er der en ny hændelsessporing i klienten. Med denne kan en brugerproces registreres til at vise hændelser, og udvikleren kan have abonnentkode for den genererede hændelse, som nemt kan kopieres til AL-kode.

> [!div class="mx-imgBorder"]
> ![Hændelsessporing](media/Event-tracer.png "Hændelsessporing")

Desuden er der tilføjet et stort antal nye hændelser, hvilket gør det muligt at udvide flere forskellige steder.

## <a name="visual-studio-code-al-extension-enhancements"></a>Forbedringer af Visual Studio-kode AL-udvidelse
Med versionsstyring og bagudkompatibilitet kan du nu installere AL-sprogudvidelsen fra Visual Studio-kodemarkedspladsen og bruge den til at udvikle løsninger til mange forskellige platforme, herunder skysandkasser, Business Central fra april 2018, Business Central fra oktober 2018 og fremtidige versioner. Kompileren kontrollerer, om den forbundne lejer er kompatibel, og kompilerer mod målplatformen, som er angivet i den nye app.json-egenskab.

Desuden er AL-udvidelsen hurtigere og mere dynamisk, når du arbejder med større projekter, der indeholder mange objektudvidelser/filer.

## <a name="debugger-enhancements"></a>Forbedringer af fejlfinding
På samme måde som i den ældre Dynamics NAV-fejlfinding kan du nu bruge den almindelige Afbryd ved fejl samt Afbryd ved skrivning. Du kan også gå til definitionen i basisprogramkoden og angive pausepunkter der.

> [!div class="mx-imgBorder"]
> ![F12 Gå til definition af basisprogramkode](media/Go-to-definition-F12.gif "F12 Gå til definition af basisprogramkode")

## <a name="intellisense-enhancements"></a>Forbedringer af IntelliSense
Alle egenskaber i AL, både ved pegning med musen og i IntelliSense, har nu hjælpelinks, der omdirigerer til relateret onlinedokumentation. Desuden bliver dokumentationen til AL-sprogstrukturer genereret automatisk og bruges til både onlinereferencedokumentation og IntelliSense for at sikre opdateret og justeret dokumentation.

> [!div class="mx-imgBorder"]
> ![Hjælpelink fra IntelliSense](media/Help-link-from-IntelliSense.gif "Hjælpelink fra IntelliSense")

Forslag til egenskaber for billede i en udvidelse foreslår nu kun dem, der kan bruges i den aktuelle kontekst, og viser en advarsel for billeder, der ikke kan bruges i den aktuelle kontekst, og du kan få vist eksempelbilleder, når du bruger IntelliSense og peger med musen.

> [!div class="mx-imgBorder"]
> ![Vælge og se eksempelbilleder med IntelliSense](media/IntelliSense-Preview-Images.gif "Vælge og se eksempelbilleder med IntelliSense")

## <a name="working-with-permissions"></a>Arbejde med tilladelser
Hvis du vil gøre det nemmere at arbejde med tilladelser, er det nu muligt at eksportere tilladelsessæt fra programmet ved hjælp af klienten og importere disse i Visual Studio kode AL-udvidelsen. Ny tilladelsesfiler til objekterne i en udvidelse kan også oprettes inde i Visual Studio-kode AL-projektet.

> [!div class="mx-imgBorder"]
> ![Visual Studio-kode AL-kommando for oprettelse af tilladelsesfil til udvidelsesobjekter](media/Permissions-AL-command.png "Visual Studio-kode AL-kommando for oprettelse af tilladelsesfil til udvidelsesobjekter")

## <a name="net-interop"></a>.NET-kompatibilitet
Når du arbejder med Business Central-løsninger, der er rettet mod lokale installationer, kan du nu tilføje .NET-kompatibilitet i AL-kode. Bemærk, at dette indebærer, at løsningen ikke kan flyttes til skyen senere uden at erstatte .NET-kompatibiliteten.

> [!div class="mx-imgBorder"]
> ![.NET-kompatibilitet i lokal AL](media/DotNet-interop.png ".NET-kompatibilitet i lokal AL")

## <a name="translation-enhancements"></a>Forbedringer af oversættelse
Nye kontekstafhængige oplysninger, der beskriver, hvilket objekt og element der vedrører en bestemt streng, er føjet til de genererede XLIFF-oversættelsesfiler. Derved får oversættere et bedre overblik over, hvor en streng vises i brugergrænsefladen, og dermed højere kvalitet af oversættelsen.

> [!div class="mx-imgBorder"]
> ![XLIFF-oversættelsesfil med notemærke](media/xliff-note.png "XLIFF-oversættelsesfil med notemærke")

## <a name="odata-bound-actions-in-al"></a>OData-bundne handlinger i AL
Det er nu muligt at erklære OData-bundne handlinger i AL. En ny attribut og en ny AL-type er introduceret for at opnå denne funktionalitet.

```
[ServiceEnabled]
procedure CreateCustomerCopy(var actionContext : WebServiceActionContext)
var
createdCustomerGuid : Guid;
customer : Record Customer;
begin
actionContext.SetObjectType(ObjectType::Page);
actionContext.SetObjectId(Pages::Customer);
actionContext.AddEntityKey(customer.fieldNo(Id), createdCustomerGuid);
actionContext.SetResultCode(WebServiceActionResultCode::Created);
end;
```
<!--
### Who uses this feature
These features are intended for ISV and VAR developers.
## Status
### Availability
Cloud, On-premises
### Regional availability
Globally
-->

## <a name="tell-us-what-you-think"></a>Fortæl os, hvad du synes
Hjælp os med at forbedre Dynamics 365 Business Central ved at diskutere ideer, stille forslag og give feedback. Brug Business Central-forummet på [https://aka.ms/businesscentralfeedback](https://aka.ms/businesscentralfeedback).


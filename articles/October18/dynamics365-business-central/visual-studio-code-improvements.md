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

# <a name="improved-visual-studio-code-al-experience"></a><span data-ttu-id="e80c6-103">Forbedret AL-oplevelse af Visual Studio-kode</span><span class="sxs-lookup"><span data-stu-id="e80c6-103">Improved Visual Studio Code AL experience</span></span>

[!include[banner](../../includes/banner.md)]

<span data-ttu-id="e80c6-104">Oprettelse af udvidelser er tilpasningsmåden for Business Central.</span><span class="sxs-lookup"><span data-stu-id="e80c6-104">Creating extensions is the way to customize Business Central.</span></span> <span data-ttu-id="e80c6-105">I produktfrigivelsen fra oktober 2018 tilføjes forbedringer af produktiviteten i udviklingsarbejdet samt understøttelse af flere udvidelsesscenarier.</span><span class="sxs-lookup"><span data-stu-id="e80c6-105">The October '18 release adds productivity enhancements to the development experience as well as support for additional extension scenarios.</span></span>

<span data-ttu-id="e80c6-106">Med forbedringerne af værktøjs- og udvidelsesfunktionerne kan udviklere være mere produktive, når de udvikler og foretager fejlfinding i forbindelse med løsninger, og de får flere muligheder for at imødekomme kundernes tilpasningskrav ved hjælp af udvidelser.</span><span class="sxs-lookup"><span data-stu-id="e80c6-106">With the enhancements to the tooling and extension capabilities, developers can be more productive when developing and troubleshooting solutions, and will have more options to meet customers' customization requirements using extensions.</span></span>

## <a name="sandbox-with-production-data"></a><span data-ttu-id="e80c6-107">Sandkasse med produktionsdata</span><span class="sxs-lookup"><span data-stu-id="e80c6-107">Sandbox with production data</span></span>
<span data-ttu-id="e80c6-108">Et almindeligt scenarie, når du arbejder med sandkasser, især i forbindelse med test eller fejlfinding, er ønsket om at have tilgængelige produktionsdata.</span><span class="sxs-lookup"><span data-stu-id="e80c6-108">A common scenario when working with sandboxes, especially when testing or troubleshooting, is the wish to have production data available.</span></span> <span data-ttu-id="e80c6-109">Med denne frigivelse tilføjer vi muligheden for at oprette en sandkasse, der er baseret på en kopi af den seneste skysikkerhedskopi af produktionsdataene.</span><span class="sxs-lookup"><span data-stu-id="e80c6-109">With this release, we add the ability to create a sandbox based on a copy of the latest cloud backup of the production data.</span></span> <span data-ttu-id="e80c6-110">For at minimere tværkommunikation med integrationer, der er angivet i produktionsdataene, vil disse integrationer være deaktiveret under oprettelsen af sandkassen.</span><span class="sxs-lookup"><span data-stu-id="e80c6-110">To minimize cross-talk with integrations set up in the production data, these integrations will be disabled when the sandbox is created.</span></span> <span data-ttu-id="e80c6-111">Administratorer kan med forsigtighed aktivere eller omkonfigurere disse integrationer efter behov for at understøtte den tilsigtede sandkassebrug.</span><span class="sxs-lookup"><span data-stu-id="e80c6-111">Using caution, admin users can enable or reconfigure these integrations as required to support the intended sandbox use.</span></span>

## <a name="new-object-extensions"></a><span data-ttu-id="e80c6-112">Nye objektudvidelser</span><span class="sxs-lookup"><span data-stu-id="e80c6-112">New object extensions</span></span>
<span data-ttu-id="e80c6-113">Du kan nu udvide følgende:</span><span class="sxs-lookup"><span data-stu-id="e80c6-113">You can now extend the following:</span></span>

- <span data-ttu-id="e80c6-114">Fasttekster (indstillinger) fra basisprogrammet samt oprettelse af nye, udvidelige fasttekster i dine udvidelser.</span><span class="sxs-lookup"><span data-stu-id="e80c6-114">Enums (options) from the base application as well as create new, extensible enums in your extensions.</span></span>
- <span data-ttu-id="e80c6-115">Rapportdatasæt i udvidelser.</span><span class="sxs-lookup"><span data-stu-id="e80c6-115">Report data sets in extensions.</span></span> <span data-ttu-id="e80c6-116">Rapportdatalayout er stadig et spørgsmål om erstatning.</span><span class="sxs-lookup"><span data-stu-id="e80c6-116">Report data layouts are still a replacement story.</span></span>
- <span data-ttu-id="e80c6-117">Feltgrupper.</span><span class="sxs-lookup"><span data-stu-id="e80c6-117">Field groups.</span></span>

## <a name="event-discoverability"></a><span data-ttu-id="e80c6-118">Registrering af hændelser</span><span class="sxs-lookup"><span data-stu-id="e80c6-118">Event discoverability</span></span>
<span data-ttu-id="e80c6-119">Et kerneaspekt under oprettelse af udvidelser er at abonnere på hændelser.</span><span class="sxs-lookup"><span data-stu-id="e80c6-119">A core aspect of creating extensions is to subscribe to events.</span></span> <span data-ttu-id="e80c6-120">En almindelig udfordring er dog kendskab til, hvilke hændelser der er tilgængelige i en given brugerproces.</span><span class="sxs-lookup"><span data-stu-id="e80c6-120">However, a common challenge is understanding which events are available in a given user flow.</span></span> <span data-ttu-id="e80c6-121">Fejlfinding kan hjælpe, men vil kun vise hændelser, der allerede abonneres på.</span><span class="sxs-lookup"><span data-stu-id="e80c6-121">Debugging can help, but will only show events already being subscribed to.</span></span> <span data-ttu-id="e80c6-122">For at støtte registreringen af hændelser og udvidelsespunkter er der en ny hændelsessporing i klienten.</span><span class="sxs-lookup"><span data-stu-id="e80c6-122">To aid in the discoverability of events and extension points, there is a new event tracer in the client.</span></span> <span data-ttu-id="e80c6-123">Med denne kan en brugerproces registreres til at vise hændelser, og udvikleren kan have abonnentkode for den genererede hændelse, som nemt kan kopieres til AL-kode.</span><span class="sxs-lookup"><span data-stu-id="e80c6-123">With this, a user flow can be recorded to list events that are raised, and the developer can have subscriber code for the event generated for easy copy into AL code.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="e80c6-124">![Hændelsessporing](media/Event-tracer.png "Hændelsessporing")</span><span class="sxs-lookup"><span data-stu-id="e80c6-124">![Event tracer](media/Event-tracer.png "Event tracer")</span></span>

<span data-ttu-id="e80c6-125">Desuden er der tilføjet et stort antal nye hændelser, hvilket gør det muligt at udvide flere forskellige steder.</span><span class="sxs-lookup"><span data-stu-id="e80c6-125">Furthermore, a large number of new events has been added, making it possible to extend in more places.</span></span>

## <a name="visual-studio-code-al-extension-enhancements"></a><span data-ttu-id="e80c6-126">Forbedringer af Visual Studio-kode AL-udvidelse</span><span class="sxs-lookup"><span data-stu-id="e80c6-126">Visual Studio Code AL Extension enhancements</span></span>
<span data-ttu-id="e80c6-127">Med versionsstyring og bagudkompatibilitet kan du nu installere AL-sprogudvidelsen fra Visual Studio-kodemarkedspladsen og bruge den til at udvikle løsninger til mange forskellige platforme, herunder skysandkasser, Business Central fra april 2018, Business Central fra oktober 2018 og fremtidige versioner.</span><span class="sxs-lookup"><span data-stu-id="e80c6-127">With versioning check and backward compatibility, you can now install the AL Language extension from the Visual Studio Code marketplace and use it to develop solutions for many different platforms, including cloud sandboxes, Business Central April 2018 release, Business Central October 2018 release, and future versions.</span></span> <span data-ttu-id="e80c6-128">Kompileren kontrollerer, om den forbundne lejer er kompatibel, og kompilerer mod målplatformen, som er angivet i den nye app.json-egenskab.</span><span class="sxs-lookup"><span data-stu-id="e80c6-128">The compiler will check that the connected tenant is compatible, and compile against the target platform as set in the new app.json property.</span></span>

<span data-ttu-id="e80c6-129">Desuden er AL-udvidelsen hurtigere og mere dynamisk, når du arbejder med større projekter, der indeholder mange objektudvidelser/filer.</span><span class="sxs-lookup"><span data-stu-id="e80c6-129">Also, the AL extension is now faster and more responsive when working with larger projects containing many object extensions/files.</span></span>

## <a name="debugger-enhancements"></a><span data-ttu-id="e80c6-130">Forbedringer af fejlfinding</span><span class="sxs-lookup"><span data-stu-id="e80c6-130">Debugger enhancements</span></span>
<span data-ttu-id="e80c6-131">På samme måde som i den ældre Dynamics NAV-fejlfinding kan du nu bruge den almindelige Afbryd ved fejl samt Afbryd ved skrivning.</span><span class="sxs-lookup"><span data-stu-id="e80c6-131">Just like in the legacy Dynamics NAV debugger, you can now use the common Break on Error, as well as Break on Write.</span></span> <span data-ttu-id="e80c6-132">Du kan også gå til definitionen i basisprogramkoden og angive pausepunkter der.</span><span class="sxs-lookup"><span data-stu-id="e80c6-132">You can also go to definition in the base application code and set breakpoints there.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="e80c6-133">![F12 Gå til definition af basisprogramkode](media/Go-to-definition-F12.gif "F12 Gå til definition af basisprogramkode")</span><span class="sxs-lookup"><span data-stu-id="e80c6-133">![F12 Go to Definition for base application code](media/Go-to-definition-F12.gif "F12 Go to Definition for base application code")</span></span>

## <a name="intellisense-enhancements"></a><span data-ttu-id="e80c6-134">Forbedringer af IntelliSense</span><span class="sxs-lookup"><span data-stu-id="e80c6-134">IntelliSense enhancements</span></span>
<span data-ttu-id="e80c6-135">Alle egenskaber i AL, både ved pegning med musen og i IntelliSense, har nu hjælpelinks, der omdirigerer til relateret onlinedokumentation.</span><span class="sxs-lookup"><span data-stu-id="e80c6-135">All properties in AL, both on hover and in IntelliSense, now have Help links that redirect you to the related online documentation.</span></span> <span data-ttu-id="e80c6-136">Desuden bliver dokumentationen til AL-sprogstrukturer genereret automatisk og bruges til både onlinereferencedokumentation og IntelliSense for at sikre opdateret og justeret dokumentation.</span><span class="sxs-lookup"><span data-stu-id="e80c6-136">Furthermore, the documentation for AL language constructs is autogenerated and used for both online reference documentation and IntelliSense, ensuring up-to-date and aligned documentation.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="e80c6-137">![Hjælpelink fra IntelliSense](media/Help-link-from-IntelliSense.gif "Hjælpelink fra IntelliSense")</span><span class="sxs-lookup"><span data-stu-id="e80c6-137">![Help link from IntelliSense](media/Help-link-from-IntelliSense.gif "Help link from IntelliSense")</span></span>

<span data-ttu-id="e80c6-138">Forslag til egenskaber for billede i en udvidelse foreslår nu kun dem, der kan bruges i den aktuelle kontekst, og viser en advarsel for billeder, der ikke kan bruges i den aktuelle kontekst, og du kan få vist eksempelbilleder, når du bruger IntelliSense og peger med musen.</span><span class="sxs-lookup"><span data-stu-id="e80c6-138">Suggestions for Image properties in an extension now only propose the ones that can be used in the current context, displaying a warning for images that cannot be used in the current context, and you can preview images when using IntelliSense and on-hover.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="e80c6-139">![Vælge og se eksempelbilleder med IntelliSense](media/IntelliSense-Preview-Images.gif "Vælge og se eksempelbilleder med IntelliSense")</span><span class="sxs-lookup"><span data-stu-id="e80c6-139">![Select and preview images with IntelliSense](media/IntelliSense-Preview-Images.gif "Select and preview images with IntelliSense")</span></span>

## <a name="working-with-permissions"></a><span data-ttu-id="e80c6-140">Arbejde med tilladelser</span><span class="sxs-lookup"><span data-stu-id="e80c6-140">Working with permissions</span></span>
<span data-ttu-id="e80c6-141">Hvis du vil gøre det nemmere at arbejde med tilladelser, er det nu muligt at eksportere tilladelsessæt fra programmet ved hjælp af klienten og importere disse i Visual Studio kode AL-udvidelsen.</span><span class="sxs-lookup"><span data-stu-id="e80c6-141">To make working with permissions easier, it is now possible to export permission sets from the application, using the client, and import these into the Visual Studio Code AL Extension.</span></span> <span data-ttu-id="e80c6-142">Ny tilladelsesfiler til objekterne i en udvidelse kan også oprettes inde i Visual Studio-kode AL-projektet.</span><span class="sxs-lookup"><span data-stu-id="e80c6-142">New permission files for the objects in an extension can also be generated from within the Visual Studio Code AL project.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="e80c6-143">![Visual Studio-kode AL-kommando for oprettelse af tilladelsesfil til udvidelsesobjekter](media/Permissions-AL-command.png "Visual Studio-kode AL-kommando for oprettelse af tilladelsesfil til udvidelsesobjekter")</span><span class="sxs-lookup"><span data-stu-id="e80c6-143">![Visual Studio Code AL command for generating permissions file for extension objects](media/Permissions-AL-command.png "Visual Studio Code AL command for generating permissions file for extension objects")</span></span>

## <a name="net-interop"></a><span data-ttu-id="e80c6-144">.NET-kompatibilitet</span><span class="sxs-lookup"><span data-stu-id="e80c6-144">.NET Interop</span></span>
<span data-ttu-id="e80c6-145">Når du arbejder med Business Central-løsninger, der er rettet mod lokale installationer, kan du nu tilføje .NET-kompatibilitet i AL-kode.</span><span class="sxs-lookup"><span data-stu-id="e80c6-145">When working with Business Central solutions that target on-premises deployments, you can now add .NET Interop in AL code.</span></span> <span data-ttu-id="e80c6-146">Bemærk, at dette indebærer, at løsningen ikke kan flyttes til skyen senere uden at erstatte .NET-kompatibiliteten.</span><span class="sxs-lookup"><span data-stu-id="e80c6-146">Note that this implies that the solution cannot be moved to the cloud later without replacing the .NET Interop.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="e80c6-147">![.NET-kompatibilitet i lokal AL](media/DotNet-interop.png ".NET-kompatibilitet i lokal AL")</span><span class="sxs-lookup"><span data-stu-id="e80c6-147">![.NET Interop in on-premises AL](media/DotNet-interop.png ".NET Interop in on-premises AL")</span></span>

## <a name="translation-enhancements"></a><span data-ttu-id="e80c6-148">Forbedringer af oversættelse</span><span class="sxs-lookup"><span data-stu-id="e80c6-148">Translation enhancements</span></span>
<span data-ttu-id="e80c6-149">Nye kontekstafhængige oplysninger, der beskriver, hvilket objekt og element der vedrører en bestemt streng, er føjet til de genererede XLIFF-oversættelsesfiler.</span><span class="sxs-lookup"><span data-stu-id="e80c6-149">New contextual information that describes which object and element a given string applies to has been added to the generated XLIFF translation files.</span></span> <span data-ttu-id="e80c6-150">Derved får oversættere et bedre overblik over, hvor en streng vises i brugergrænsefladen, og dermed højere kvalitet af oversættelsen.</span><span class="sxs-lookup"><span data-stu-id="e80c6-150">This helps translators get a better overview of where a string is displayed in the UI, thereby increasing the quality of the translation.</span></span>

> [!div class="mx-imgBorder"]
> <span data-ttu-id="e80c6-151">![XLIFF-oversættelsesfil med notemærke](media/xliff-note.png "XLIFF-oversættelsesfil med notemærke")</span><span class="sxs-lookup"><span data-stu-id="e80c6-151">![XLIFF translation file note tag](media/xliff-note.png "XLIFF translation file note tag")</span></span>

## <a name="odata-bound-actions-in-al"></a><span data-ttu-id="e80c6-152">OData-bundne handlinger i AL</span><span class="sxs-lookup"><span data-stu-id="e80c6-152">OData-bound actions in AL</span></span>
<span data-ttu-id="e80c6-153">Det er nu muligt at erklære OData-bundne handlinger i AL.</span><span class="sxs-lookup"><span data-stu-id="e80c6-153">It is now possible to declare OData bound actions in AL.</span></span> <span data-ttu-id="e80c6-154">En ny attribut og en ny AL-type er introduceret for at opnå denne funktionalitet.</span><span class="sxs-lookup"><span data-stu-id="e80c6-154">A new attribute and a new AL type have been introduced to achieve this.</span></span>

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

## <a name="tell-us-what-you-think"></a><span data-ttu-id="e80c6-155">Fortæl os, hvad du synes</span><span class="sxs-lookup"><span data-stu-id="e80c6-155">Tell us what you think</span></span>
<span data-ttu-id="e80c6-156">Hjælp os med at forbedre Dynamics 365 Business Central ved at diskutere ideer, stille forslag og give feedback.</span><span class="sxs-lookup"><span data-stu-id="e80c6-156">Help us improve Dynamics 365 Business Central by discussing ideas, providing suggestions, and giving feedback.</span></span> <span data-ttu-id="e80c6-157">Brug Business Central-forummet på [https://aka.ms/businesscentralfeedback](https://aka.ms/businesscentralfeedback).</span><span class="sxs-lookup"><span data-stu-id="e80c6-157">Use the Business Central forum at [https://aka.ms/businesscentralfeedback](https://aka.ms/businesscentralfeedback).</span></span>


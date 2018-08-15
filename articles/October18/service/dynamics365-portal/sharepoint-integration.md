---
title: SharePoint-dokumentstyring for portaler
description: SharePoint-dokumentstyring for portaler
author: sandhangitmsft
manager: ramalingamkrishnan
ms.date: 07/22/2018
ms.assetid: aa14cee1-b121-4c02-8937-13e0717e8fb8
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: sandhan
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: 62ff356275ffd55047573b9224fb7c94df8dd602
ms.openlocfilehash: 318636631f44de9d4991ee0733b502fbed2403fa
ms.contentlocale: da-dk
ms.lasthandoff: 08/15/2018

---
#  <a name="manage-sharepoint-documents"></a><span data-ttu-id="7ab4b-103">Styre SharePoint-dokumenter</span><span class="sxs-lookup"><span data-stu-id="7ab4b-103">Manage SharePoint documents</span></span>

[!include[dynamics365-portal banner](../../includes/dynamics365-portal.md)]




<span data-ttu-id="7ab4b-104">Denne funktion udvider dokumentstyringsfunktionerne i Dynamics 365-programmer til portaler for at give en ensartet oplevelse, hvor kunderne kan udnytte deres eksisterende investering i SharePoint sammen med Dynamics 365 til dokumentstyring.</span><span class="sxs-lookup"><span data-stu-id="7ab4b-104">This feature extends document management capabilities of Dynamics 365 applications to portals, providing a consistent experience and allowing customers to leverage their existing investments in SharePoint with Dynamics 365 for document management.</span></span>

<span data-ttu-id="7ab4b-105">Dokumenter, der er knyttet til objektposter, kan styres af portalbrugere, da de er gemt i et SharePoint-dokumentbibliotek, så det også er muligt for virksomheder at udnytte de problemfri samarbejdsmuligheder, der er indbygget i SharePoint.</span><span class="sxs-lookup"><span data-stu-id="7ab4b-105">Documents associated with entity records can be managed by portal users as they are stored in a SharePoint document library, thus also enabling businesses to leverage the seamless collaboration capabilities offered natively by SharePoint.</span></span>

<span data-ttu-id="7ab4b-106">SharePoint Online-dokumentbiblioteker, der er konfigureret med objekter i Dynamics 365, kan indlæses via portalobjektet og webformularer.</span><span class="sxs-lookup"><span data-stu-id="7ab4b-106">SharePoint Online document libraries configured with entities in Dynamics 365 can be surfaced via portal entity and web forms.</span></span> <span data-ttu-id="7ab4b-107">Det giver portalbrugere mulighed for at udføre følgende handlinger:</span><span class="sxs-lookup"><span data-stu-id="7ab4b-107">This allows portal users to perform the following actions:</span></span>

## <a name="add-documents"></a><span data-ttu-id="7ab4b-108">Tilføje dokumenter</span><span class="sxs-lookup"><span data-stu-id="7ab4b-108">Add documents</span></span>

<span data-ttu-id="7ab4b-109">![Føje filer til en sagspost](media/SP_Portal_Add_Files.png "Føje filer til en sagspost")</span><span class="sxs-lookup"><span data-stu-id="7ab4b-109">![Add files to a case record](media/SP_Portal_Add_Files.png "Add files to a case record")</span></span>

## <a name="view-and-download-documents"></a><span data-ttu-id="7ab4b-110">Se og downloade dokumenter</span><span class="sxs-lookup"><span data-stu-id="7ab4b-110">View and download documents</span></span>

<span data-ttu-id="7ab4b-111">![Se dokumenter, der er relateret til en sagspost](media/SP_Portal_View_Files.png "Se dokumenter, der er relateret til en sagspost")</span><span class="sxs-lookup"><span data-stu-id="7ab4b-111">![View documents related to case record](media/SP_Portal_View_Files.png "View documents related to case record")</span></span> 

## <a name="create-folder"></a><span data-ttu-id="7ab4b-112">Oprette mappe</span><span class="sxs-lookup"><span data-stu-id="7ab4b-112">Create folder</span></span>

<span data-ttu-id="7ab4b-113">![Oprette undermappe på dokumentliste for at organisere filer](media/SP_Portal_Create_Folder.png "Oprette undermappe på dokumentliste for at organisere filer")</span><span class="sxs-lookup"><span data-stu-id="7ab4b-113">![Create subfolder within document list to organize files](media/SP_Portal_Create_Folder.png "Create subfolder within document list to organize files")</span></span>

## <a name="delete-document"></a><span data-ttu-id="7ab4b-114">Slette dokument</span><span class="sxs-lookup"><span data-stu-id="7ab4b-114">Delete document</span></span>

<span data-ttu-id="7ab4b-115">![Slette filer fra en sagspost](media/SP_Portal_Delete_File.png "Slette filer fra en sagspost")</span><span class="sxs-lookup"><span data-stu-id="7ab4b-115">![Delete files from a case record](media/SP_Portal_Delete_File.png "Delete files from a case record")</span></span>

<!--
### Who uses this feature
This feature is intended for portal end users, allowing them access to SharePoint documents from portal web pages.
Portal administrators customize the form to display document lists on a portal. Entity permission configuration is used to control actions available to portal end users on files and folders.
### Setup required
This feature requires that document management is set up for [Dynamics 365 with SharePoint Online](https://go.microsoft.com/fwlink/p/?linkid=859386).
-->

## <a name="quick-steps"></a><span data-ttu-id="7ab4b-116">Hurtige trin</span><span class="sxs-lookup"><span data-stu-id="7ab4b-116">Quick steps</span></span>

### <a name="configuring-document-list-on-entity-forms"></a><span data-ttu-id="7ab4b-117">Konfiguration af dokumentliste på objektformularer</span><span class="sxs-lookup"><span data-stu-id="7ab4b-117">Configuring document list on entity forms</span></span>

<span data-ttu-id="7ab4b-118">![Konfigurere undergitter til dokumentliste i sagsobjektformular](media/SP_Portal_configure_entity_form_doc_location.png "Konfigurere undergitter til dokumentliste i sagsobjektformular")</span><span class="sxs-lookup"><span data-stu-id="7ab4b-118">![Configure document list subgrid on case entity form](media/SP_Portal_configure_entity_form_doc_location.png "Document location subgrid configuration")</span></span>

### <a name="configuring-permissions-on-document-list"></a><span data-ttu-id="7ab4b-119">Konfiguration af tilladelser på dokumentliste</span><span class="sxs-lookup"><span data-stu-id="7ab4b-119">Configuring permissions on document list</span></span>

<span data-ttu-id="7ab4b-120">![Konfigurere tilladelser på dokumentliste](media/SP_Portal_configure_doc_permissions.png "Konfigurere tilladelser på dokumentliste")</span><span class="sxs-lookup"><span data-stu-id="7ab4b-120">![Configure document list permissions](media/SP_Portal_configure_doc_permissions.png "Configure permissions")</span></span>

<span data-ttu-id="7ab4b-121">Med en tilladelsesbaseret model er det muligt at styre disse handlinger på filer og mapper i bestemte kundescenarier.</span><span class="sxs-lookup"><span data-stu-id="7ab4b-121">A permissions-based model allows controlling these actions on files and folders for specific customer scenarios.</span></span>

<!--
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

## <a name="wed-like-to-thank"></a><span data-ttu-id="7ab4b-122">Tak!</span><span class="sxs-lookup"><span data-stu-id="7ab4b-122">We'd like to thank</span></span>

<span data-ttu-id="7ab4b-123">Tak for din indsendelse af [denne ide](https://experience.dynamics.com/ideas/idea/?ideaid=d3398770-f9ac-e611-80c2-00155d4616d6) med stemmer og kommentarer, som har hjulpet os med at prioritere den.</span><span class="sxs-lookup"><span data-stu-id="7ab4b-123">Thank you for submitting [this idea](https://experience.dynamics.com/ideas/idea/?ideaid=d3398770-f9ac-e611-80c2-00155d4616d6) with votes and comments that helped us prioritize it.</span></span>


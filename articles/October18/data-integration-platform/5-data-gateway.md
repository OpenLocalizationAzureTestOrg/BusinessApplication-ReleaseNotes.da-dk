---
title: "Hybridforbindelser for virksomheder via datagateway i det lokale miljø"
description: "Hybridforbindelser for virksomheder via datagateway i det lokale miljø"
author: MargoC
manager: AnnBe
ms.date: 7/22/2018
ms.assetid: 5b0c45ea-97e4-4e6f-8555-f2bc05ccb336
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin
ms.translationtype: HT
ms.sourcegitcommit: e4d721713b70d0a9cfeb06d0f795f23d3f0223a5
ms.openlocfilehash: bfe4ab5339acfa70c55d7cf0d2357fc95c47c4de
ms.contentlocale: da-dk
ms.lasthandoff: 07/27/2018

---
#  <a name="enterprise-grade-hybrid-connectivity-using-the-on-premises-data-gateway"></a><span data-ttu-id="ad542-103">Hybridforbindelser for virksomheder via datagateway i det lokale miljø</span><span class="sxs-lookup"><span data-stu-id="ad542-103">Enterprise-grade hybrid connectivity using the on-premises data gateway</span></span>


[!include[banner](../../includes/banner.md)]

<span data-ttu-id="ad542-104">Denne produktfrigivelse indeholder flere opdateringer, der er relateret til forbedring af datagatewayen i det lokale miljø.</span><span class="sxs-lookup"><span data-stu-id="ad542-104">This release includes multiple updates around improving the on-premises data gateway.</span></span>

## <a name="certified-custom-connectors-in-power-bi-desktop"></a><span data-ttu-id="ad542-105">Godkendte brugerdefinerede connectorer i Power BI Desktop</span><span class="sxs-lookup"><span data-stu-id="ad542-105">Certified custom connectors in Power BI Desktop</span></span>

<span data-ttu-id="ad542-106">Tidligere i år annoncerede vi understøttelse af brugerdefinerede connectorer i Power BI Desktop ved hjælp af M-sprogets effektive funktioner, der gør det muligt for partnere at skrive deres egne connectorer og distribuere dem til enhver Power BI-bruger.</span><span class="sxs-lookup"><span data-stu-id="ad542-106">Earlier this year, we announced support for custom connectors in Power BI Desktop, leveraging the powerful capabilities of the M language allowing partners to write their own connectors and distribute them to every Power BI user.</span></span>

<span data-ttu-id="ad542-107">Understøttelse af brugerdefinerede connectorer i gatewayen giver brugerne mulighed for at holde de rapporter, de har oprettet med brugerdefinerede connectorer, opdateret i Power BI-tjenesten ved at opdatere dataene ved hjælp af datagatewayen i det lokale miljø.</span><span class="sxs-lookup"><span data-stu-id="ad542-107">Custom connectors support in the gateway allows users to have their reports that they built with custom connectors stay up to date on the Power BI service by refreshing the data through the on-premises data gateway.</span></span>

<span data-ttu-id="ad542-108">![Understøttelse af brugerdefinerede connectorer i datagatewayen i det lokale miljø](media/custom-connectors-support-premises-data-gateway-1.jpg "Understøttelse af brugerdefinerede connectorer i datagatewayen i det lokale miljø")</span><span class="sxs-lookup"><span data-stu-id="ad542-108">![Custom connectors support in the on-premises data gateway](media/custom-connectors-support-premises-data-gateway-1.jpg "Custom connectors support in the on-premises data gateway")</span></span>

## <a name="gateway-multi-geo-support-for-power-bi-premium"></a><span data-ttu-id="ad542-109">Understøttelse af gateway med flere geokoder for Power BI Premium</span><span class="sxs-lookup"><span data-stu-id="ad542-109">Gateway multi-geo support for Power BI Premium</span></span>

<span data-ttu-id="ad542-110">Som en del af arbejdet med at understøtte flere geokoder i Power BI-tjenesten vil datagatewayen i det lokale miljø give brugerne mulighed for under konfigurationen at vælge et andet område end deres lejers eget område.</span><span class="sxs-lookup"><span data-stu-id="ad542-110">As part of the work to support multi-geo in the Power BI service, the on-premises data gateway will allow users during the configuration step to choose a different region from their tenant's home region.</span></span> <span data-ttu-id="ad542-111">Dette sikrer, at datakildens data og legitimationsoplysninger forbliver i det valgte område i overensstemmelse med organisationens entydige lovgivningsmæssige krav.</span><span class="sxs-lookup"><span data-stu-id="ad542-111">This will ensure that the data source's information and credentials remain in the chosen region to comply with the organization’s unique regulatory requirements.</span></span>

<span data-ttu-id="ad542-112">Oplevelser skal opdateres, så brugerne kan udnytte datagatewayen i det lokale miljø i de pågældende områder.</span><span class="sxs-lookup"><span data-stu-id="ad542-112">Experiences need to be updated so that users can leverage the on-premises data gateway in those regions.</span></span> <span data-ttu-id="ad542-113">En del af denne indsats drejer sig om at sikre, at datakildens oplysninger (for eksempel legitimationsoplysninger) ikke forlader det område, som arbejdsområdet ligger i (for at overholde datasuverænitet).</span><span class="sxs-lookup"><span data-stu-id="ad542-113">Part of that effort includes ensuring the data source information (credentials, for example) does not leave the region the workspace is in (to comply with data sovereignty).</span></span>

<span data-ttu-id="ad542-114">![Understøttelse med flere geokoder i datagatewayen i det lokale miljø](media/gateway-multi-geo-support-pbi-premium-1.png "Understøttelse med flere geokoder i datagatewayen i det lokale miljø")</span><span class="sxs-lookup"><span data-stu-id="ad542-114">![Multi-geo support in the on-premises data gateway](media/gateway-multi-geo-support-pbi-premium-1.png "Multi-geo support in the on-premises data gateway")</span></span>

## <a name="guarantee-high-availability-of-gateways-via-clustering"></a><span data-ttu-id="ad542-115">Sikrer en høj tilgængelighed af gateways via klyngedannelse</span><span class="sxs-lookup"><span data-stu-id="ad542-115">Guarantee high availability of gateways via clustering</span></span>
<span data-ttu-id="ad542-116">De funktioner vedrørende høj tilgængelighed i datagatewayen i det lokale miljø, som vi frigav i november 2017, er ved at blive overført fra offentlig prøveversion til generel tilgængelighed.</span><span class="sxs-lookup"><span data-stu-id="ad542-116">The high availability capabilities in the on-premises data gateway that we released in November 2017 are transitioning from public preview to general availability.</span></span> <span data-ttu-id="ad542-117">En del af denne indsats omfatter flere forbedringer af oplevelser, især hvad angår bedre fejlrapportering og forbedret brugeroplevelse.</span><span class="sxs-lookup"><span data-stu-id="ad542-117">Part of this effort includes multiple experience improvements, especially around better error reporting and improved user experience.</span></span>

## <a name="improved-kerberos-single-sign-on-support"></a><span data-ttu-id="ad542-118">Forbedret understøttelse af Kerberos-enkeltlogon</span><span class="sxs-lookup"><span data-stu-id="ad542-118">Improved Kerberos single sign-on support</span></span>
<span data-ttu-id="ad542-119">Vi har planer om at understøtte flere domæner i vores SSO-implementering samt gøre det nemmere at teste SSO-forbindelsen og diagnosticere problemer.</span><span class="sxs-lookup"><span data-stu-id="ad542-119">We plan to support multiple domains in our SSO implementation as well as make it easier to test the SSO connection and diagnose issues.</span></span>

<span data-ttu-id="ad542-120">![Forbedret understøttelse af Kerberos-enkeltlogon](media/improved-kerberos-single-sign-support-premises-data-gateway-1.png "Forbedret understøttelse af Kerberos-enkeltlogon")</span><span class="sxs-lookup"><span data-stu-id="ad542-120">![Improved Kerberos single sign-on support](media/improved-kerberos-single-sign-support-premises-data-gateway-1.png "Improved Kerberos single sign-on support")</span></span>

## <a name="saml-based-single-sign-on-for-supported-data-sources"></a><span data-ttu-id="ad542-121">SAML-baseret enkeltlogon til understøttede datakilder</span><span class="sxs-lookup"><span data-stu-id="ad542-121">SAML-based single sign-on for supported data sources</span></span>

<span data-ttu-id="ad542-122">Sidste år føjede vi understøttelse af Kerberos-enkeltlogon til gatewayen for flere kilder, herunder SQL Server, SAP HANA og Teradata.</span><span class="sxs-lookup"><span data-stu-id="ad542-122">Last year we added Kerberos single sign-on support to the gateway for multiple sources, including SQL Server, SAP HANA, and Teradata.</span></span>

<span data-ttu-id="ad542-123">I denne periode har vi planer om fortsat at investere i understøttelse af enkeltlogon ved at tilføje understøttelse af SAML-baserede enkeltlogon-scenarier for understøttede datakilder.</span><span class="sxs-lookup"><span data-stu-id="ad542-123">This period we plan to continue investments in single sign-on support by adding support to SAML-based single sign-on scenarios for supported data sources.</span></span>

<a name="additional-cloud-data-refresh-capabilities-for-parity-with-pbi-desktop"></a>  
## <a name="additional-cloud-data-refresh-capabilities-for-parity-with-power-bi-desktop"></a><span data-ttu-id="ad542-124">Yderligere funktioner til opdatering af data i skyen for paritet med Power BI Desktop</span><span class="sxs-lookup"><span data-stu-id="ad542-124">Additional cloud data refresh capabilities for parity with Power BI Desktop</span></span>

<span data-ttu-id="ad542-125">Der er nogle tilfælde, hvor et Power BI-datasæt uden problemer kan opdateres i Power BI Desktop, men ikke kan opdateres i Power BI-tjenesten.</span><span class="sxs-lookup"><span data-stu-id="ad542-125">There are some cases where a Power BI dataset can refresh without issues in Power BI Desktop but fails to refresh in the Power BI service.</span></span> <span data-ttu-id="ad542-126">Dette sker typisk på grund af indstillingerne for beskyttelse af personlige oplysninger tilhørende de datakilder, der anvendes i dette datasæt.</span><span class="sxs-lookup"><span data-stu-id="ad542-126">This commonly happens because of the privacy settings of the individual data sources used in this dataset.</span></span>

<span data-ttu-id="ad542-127">I Power BI Desktop kan brugere ændre indstillingerne for beskyttelse af personlige oplysninger for hver datakilde, så datasættet uden videre kan opdateres.</span><span class="sxs-lookup"><span data-stu-id="ad542-127">In Power BI Desktop, users can change the privacy settings for each data source, allowing the dataset to refresh successfully.</span></span> <span data-ttu-id="ad542-128">Vi arbejder på at give brugerne mulighed for at opdatere disse datasæt i Power BI-tjenesten uden problemer.</span><span class="sxs-lookup"><span data-stu-id="ad542-128">We intend to give users the ability to successfully refresh those datasets in the Power BI service.</span></span>

<a name="improved-data-sources-settings-experience"></a>  
## <a name="improved-data-source-settings-experience"></a><span data-ttu-id="ad542-129">Forbedret oplevelse af datakildeindstillinger</span><span class="sxs-lookup"><span data-stu-id="ad542-129">Improved data source settings experience</span></span>

<span data-ttu-id="ad542-130">Vi har planer om at forbedre oplevelsen med at oprette datakilder på "Administrer gateways"-siden i Power BI-tjenesten ved at tilføje nogle af de mest efterspurgte funktioner, f.eks. muligheden for at springe testforbindelsestrinnet over, omdøbe datakilder og oprette flere datakilder med forskellige legitimationsoplysninger.</span><span class="sxs-lookup"><span data-stu-id="ad542-130">We plan to improve the data sources creation experience on the "Manage Gateways" page in the Power BI service by adding some of the highly requested capabilities, such as the ability to skip the test connection step, to rename data sources, and to create multiple data sources with different credentials.</span></span>

## <a name="tenant-level-administration-of-on-premises-data-gateway"></a><span data-ttu-id="ad542-131">Administration på lejerniveau i datagatewayen i det lokale miljø</span><span class="sxs-lookup"><span data-stu-id="ad542-131">Tenant level administration of on-premises data gateway</span></span>
<span data-ttu-id="ad542-132">Vi vil give lejeradministratorer mulighed for at administrere alle datagateways i det lokale miljø i deres lejer gennem både en API og brugergrænsefladen.</span><span class="sxs-lookup"><span data-stu-id="ad542-132">We intend to add the ability for tenant administrators to manage all the on-premises data gateways in their tenant through both an API and the user interface.</span></span>

## <a name="basic-traffic-load-balancing-in-the-on-premises-data-gateway"></a><span data-ttu-id="ad542-133">Grundlæggende justering af trafikbelastning i datagatewayen i det lokale miljø</span><span class="sxs-lookup"><span data-stu-id="ad542-133">Basic traffic load balancing in the on-premises data gateway</span></span>
<span data-ttu-id="ad542-134">Vi har planer om at introducere en mulighed for at opdele trafik i forbindelse med anmodninger for en given gatewayklynge på tværs af alle gateways i den klynge.</span><span class="sxs-lookup"><span data-stu-id="ad542-134">We plan to introduce the ability to split the requests traffic for a given gateway cluster across all gateways in that cluster.</span></span>
<span data-ttu-id="ad542-135">Gatewayadministratoren vil kunne slå denne funktion til og fra i overensstemmelse med organisationens behov.</span><span class="sxs-lookup"><span data-stu-id="ad542-135">The gateway administrator will be able to turn this capability on and off according to their organization's needs.</span></span>


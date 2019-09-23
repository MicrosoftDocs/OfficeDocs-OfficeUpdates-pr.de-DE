---
title: Bekannte Probleme bei Office 365 ProPlus
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Enthält Informationen zu bekannten Problemen bei Office 365 ProPlus
ms.openlocfilehash: a8b385e197a6f61c10797bf160101cdd70285aaf
ms.sourcegitcommit: a6d8dba3ee51727c2d3a2dad89cb986595c1a7b8
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/20/2019
ms.locfileid: "37068054"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="c4d07-103">Bekannte Probleme bei Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="c4d07-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="c4d07-104">Diese Informationen zu bekannten Problemen umfassen Informationen zu nicht sicherheitsrelevanten Updates, die in den monatlichen Channel-, SACT- und SAC-Updates für Office 365 ProPlus im Jahre 2019, Visio Pro für Office 365, Project Online Desktop Client und Office 365 Business enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="c4d07-104">These release notes provide information about new features and non-security updates that are included in Monthly Channel updates to Office 365 ProPlus in 2019, including Visio Pro for Office 365 and Project Online Desktop Client.</span></span>

<span data-ttu-id="c4d07-105">Diese Tabelle enthält eine Zusammenfassung aktueller aktiver Probleme sowie der behobenen Probleme.</span><span class="sxs-lookup"><span data-stu-id="c4d07-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="c4d07-106">Wir werden die Tabelle unten mit wichtigen Problemen, die wir untersuchen, aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="c4d07-106">We will update the table below with significant issues we are investigating.</span></span>

 > [!NOTE]
 >- <span data-ttu-id="c4d07-107">Diese Liste ist nicht vollständig.</span><span class="sxs-lookup"><span data-stu-id="c4d07-107">This list is not comprehensive.</span></span>

<br>

## <a name="september-2019"></a><span data-ttu-id="c4d07-108">September 2019</span><span class="sxs-lookup"><span data-stu-id="c4d07-108">September 10, 2019</span></span>

|<span data-ttu-id="c4d07-109">Zusammenfassung</span><span class="sxs-lookup"><span data-stu-id="c4d07-109">Summary</span></span>|<span data-ttu-id="c4d07-110">Wird untersucht</span><span class="sxs-lookup"><span data-stu-id="c4d07-110">Investigating</span></span>|<span data-ttu-id="c4d07-111">Gelöst</span><span class="sxs-lookup"><span data-stu-id="c4d07-111">Resolved</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="c4d07-112">**Outlook**</span><span class="sxs-lookup"><span data-stu-id="c4d07-112">**Outlook**</span></span>
<span data-ttu-id="c4d07-113">Es wurde ein Problem gefunden, durch das Dateien u. U. nicht an einem WebDAV-Speicherort gespeichert werden konnten.</span><span class="sxs-lookup"><span data-stu-id="c4d07-113">We found an issue which could have prevented files from being saved to a WebDAV location.</span></span>|<span data-ttu-id="c4d07-114">Monatliche Version 1909</span><span class="sxs-lookup"><span data-stu-id="c4d07-114">Monthly Version 1909</span></span>||
|<span data-ttu-id="c4d07-115">**Project**</span><span class="sxs-lookup"><span data-stu-id="c4d07-115">**Project**</span></span>
<span data-ttu-id="c4d07-116">Nehmen Sie folgendes Szenario an.</span><span class="sxs-lookup"><span data-stu-id="c4d07-116">Consider the following scenario.</span></span> <span data-ttu-id="c4d07-117">Sie öffnen ein Projekt.</span><span class="sxs-lookup"><span data-stu-id="c4d07-117">You open a project.</span></span> <span data-ttu-id="c4d07-118">Sie klicken auf das Menü "Datei", dann auf "Exportieren" und schließlich auf die Schaltfläche "PDF/XPS erstellen".</span><span class="sxs-lookup"><span data-stu-id="c4d07-118">You click the File menu, click Export and click the Create PDF/XPS button.</span></span> <span data-ttu-id="c4d07-119">Im Dialogfeld "Durchsuchen" geben Sie einen Dateinamen ein, und klicken dann auf "OK".</span><span class="sxs-lookup"><span data-stu-id="c4d07-119">Within the Browse dialog box, you enter a file name and click OK.</span></span> <span data-ttu-id="c4d07-120">In diesem Fall stellen Sie fest, dass die PDF- oder XPS-Datei nicht erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="c4d07-120">In this situation, you find that the PDF of XPS file is not created.</span></span> |<span data-ttu-id="c4d07-121">SAC Version 1902</span><span class="sxs-lookup"><span data-stu-id="c4d07-121">SAC Version 1902</span></span>||
|<span data-ttu-id="c4d07-122">**Word**</span><span class="sxs-lookup"><span data-stu-id="c4d07-122">**Word**</span></span>
<span data-ttu-id="c4d07-123">Wir haben ein Problem gefunden, auf das Benutzer beim Öffnen einer Datei stoßen können.</span><span class="sxs-lookup"><span data-stu-id="c4d07-123">We found an issue users could hit on opening a file.</span></span>|<span data-ttu-id="c4d07-124">Monatliche Version 1908</span><span class="sxs-lookup"><span data-stu-id="c4d07-124">Monthly Version 1908</span></span>||
<span data-ttu-id="c4d07-125">Bei Office-Dateien, die vom OneDrive-Synchronisierungsmodul synchronisiert werden, werden Dokumentmetadaten (z. B. "Voraussetzungen" und "Inhaltstyp") nach dem Klicken auf "Speichern" und "Speichern unter" nicht mehr überprüft.</span><span class="sxs-lookup"><span data-stu-id="c4d07-125">For Office files synced by the OneDrive Sync Engine, document metadata such as Require Properties and Content Type requirements are no longer validated upon Save and Save As.</span></span>|<span data-ttu-id="c4d07-126">SAC Version 1902</span><span class="sxs-lookup"><span data-stu-id="c4d07-126">SAC Version 1902</span></span>||

## <a name="may-2019---sample"></a><span data-ttu-id="c4d07-127">Mai 2019 – BEISPIEL</span><span class="sxs-lookup"><span data-stu-id="c4d07-127">May 2019 - SAMPLE</span></span>

|<span data-ttu-id="c4d07-128">Zusammenfassung</span><span class="sxs-lookup"><span data-stu-id="c4d07-128">Summary</span></span>|<span data-ttu-id="c4d07-129">Wird untersucht</span><span class="sxs-lookup"><span data-stu-id="c4d07-129">Investigating</span></span>|<span data-ttu-id="c4d07-130">Gelöst</span><span class="sxs-lookup"><span data-stu-id="c4d07-130">Resolved</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="c4d07-131">**Excel**</span><span class="sxs-lookup"><span data-stu-id="c4d07-131">**Excel**</span></span>
<span data-ttu-id="c4d07-132">Beispiel in mehreren Builds behoben – Es wurde ein Problem behoben, durch das Wasserfall- und Trichterdiagramme beim Einfügen oder Löschen von Zellen nicht mehr mit Tabellen synchronisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="c4d07-132">Sample resoved in multiple builds -- We found an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>||<span data-ttu-id="c4d07-133">SAC Version 1902</span><span class="sxs-lookup"><span data-stu-id="c4d07-133">SAC Version 1902</span></span> <br> <span data-ttu-id="c4d07-134">(16.0.11328.20306)</span><span class="sxs-lookup"><span data-stu-id="c4d07-134">(16.0.11328.20306)</span></span> <br> <span data-ttu-id="c4d07-135">Monatliche Version 1905</span><span class="sxs-lookup"><span data-stu-id="c4d07-135">Monthly Version 1905</span></span> <br> <span data-ttu-id="c4d07-136">(16.0.11629.20210)</span><span class="sxs-lookup"><span data-stu-id="c4d07-136">(16.0.11629.20210)</span></span>|
|<span data-ttu-id="c4d07-137">**Word**</span><span class="sxs-lookup"><span data-stu-id="c4d07-137">**Word**</span></span>
<span data-ttu-id="c4d07-138">Beispiel in einigen, jedoch nicht allen Builds behoben – Es wurde ein Problem mit der Leistung beim Aktivieren von Schnellbausteinen für Dokumenteigenschaften gefunden.</span><span class="sxs-lookup"><span data-stu-id="c4d07-138">Sample resoved in some builds, not all -- We found an issue with performance when enabling Quick Parts for Document propertiesk.</span></span>|<span data-ttu-id="c4d07-139">SAC Version 1808</span><span class="sxs-lookup"><span data-stu-id="c4d07-139">SAC Version 1808</span></span>|<span data-ttu-id="c4d07-140">SAC Version 1902</span><span class="sxs-lookup"><span data-stu-id="c4d07-140">SAC Version 1902</span></span> <br> <span data-ttu-id="c4d07-141">(16.0.11328.20340)</span><span class="sxs-lookup"><span data-stu-id="c4d07-141">(16.0.11328.20340)</span></span>|

<br>
<br>

> [!NOTE]
> <span data-ttu-id="c4d07-142">Wenn Sie Hilfe bei einem Problem mit der Nutzung von Office benötigen, empfehlen wir, dass Sie Ihre Frage im [Microsoft Answers-Forum](https://answers.microsoft.com/) oder in der [Tech-Community](https://techcommunity.microsoft.com/) veröffentlichen, oder Sie können sich an den [Support](https://support.microsoft.com/contactus) wenden.</span><span class="sxs-lookup"><span data-stu-id="c4d07-142">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>

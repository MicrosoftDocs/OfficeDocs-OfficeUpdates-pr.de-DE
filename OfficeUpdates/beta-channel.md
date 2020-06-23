---
title: Anmerkungen zur Version für den Beta-Kanal
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt der Zielgruppe von Insiders Fast die aktuelle Liste neuer Features, Fehlerkorrekturen oder bekannter Probleme bereit.
ms.openlocfilehash: ab1953f105cbab856ac183335fb54edb538b5d43
ms.sourcegitcommit: 6bd9e41014037650170125aaed9847880d438645
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/19/2020
ms.locfileid: "44814304"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="a9c28-103">Anmerkungen zu dieser Version für Office-Insider</span><span class="sxs-lookup"><span data-stu-id="a9c28-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="a9c28-104">Dieser Artikel enthält Versionshinweise für Beta-Kanal-Builds von Word, Excel, PowerPoint, Outlook, Access und Project für Windows-Desktop.</span><span class="sxs-lookup"><span data-stu-id="a9c28-104">This article contains release notes for Beta Channel builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="a9c28-105">Jede Woche werden interessante neue Features, wichtige Fehlerbehebungen und alle wichtigen Probleme, über die Sie informiert werden sollen, hervorgehoben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="a9c28-106">Beachten Sie, dass wir in einem bestimmten Zeitraum häufig Features (und manchmal sogar Fixes) auf den Beta-Kanal aufrollen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-106">Note that we often roll out features (and sometimes even fixes) to Beta Channel over a period of time.</span></span> <span data-ttu-id="a9c28-107">Auf diese Weise können wir sicherstellen, dass alles reibungslos funktioniert, bevor das Feature für ein breiteres Publikum bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="a9c28-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="a9c28-108">Wenn Sie also unten nichts beschrieben sehen, machen Sie sich keine Sorgen, Sie werden es eventuell irgendwann erhalten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="a9c28-109">Wir nehmen einige Änderungen an den Updatekanälen für Microsoft 365-Apps vor, unter anderem fügen wir einen neuen Updatekanal hinzu (monatlicher Enterprise-Kanal) und ändern die Namen der vorhandenen Updatekanäle.</span><span class="sxs-lookup"><span data-stu-id="a9c28-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="a9c28-110">Um mehr zu erfahren, [lesen Sie diesen Artikel](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="a9c28-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="a9c28-111">Versionshinweise werden wöchentlich veröffentlicht und können eine Kompilierung mehrerer Builds sein.</span><span class="sxs-lookup"><span data-stu-id="a9c28-111">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="a9c28-112">Das Veröffentlichungsdatum der Versionshinweise stimmt möglicherweise nicht mit dem tatsächlichen Veröffentlichungsdatum des Builds überein.</span><span class="sxs-lookup"><span data-stu-id="a9c28-112">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (NICHT ENTFERNEN)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

## <a name="version-2007-june-19"></a><span data-ttu-id="a9c28-115">Version 2007:19. Juni</span><span class="sxs-lookup"><span data-stu-id="a9c28-115">Version 2007: June 19</span></span>
<span data-ttu-id="a9c28-116">*Version 2007 (Build 13012,20000)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-116">*Version 2007 (Build 13012.20000)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-118">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-118">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a9c28-119">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-119">Excel</span></span>

- <span data-ttu-id="a9c28-120">Es wurde ein Problem behoben, bei dem customUI XML für eine benutzerdefinierte menübandregisterkarte beim Speichern einer Arbeitsmappe in SharePoint/OneDrive entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-120">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>
- <span data-ttu-id="a9c28-121">Es wurde ein Problem behoben, bei dem Arbeitsmappen schreibgeschützt waren, als die Datei nur mit Schreibschutz empfohlen wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-121">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

### <a name="outlook"></a><span data-ttu-id="a9c28-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-122">Outlook</span></span>

- <span data-ttu-id="a9c28-123">Es wurde ein Problem behoben, bei dem das IME-Fenster (Input Method Editor) den zugrunde liegenden Text über den IME überlappen würde, wenn mehrere Monitore mit unterschiedlichen Auflösungen verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-123">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="a9c28-124">Es wurde ein Problem behoben, aufgrund dessen Benutzer den folgenden Fehler beim Schließen eines Termins sehen konnten, der zuvor gespeichert wurde: "das Element kann nicht gespeichert werden, da es von einem anderen Benutzer oder in einem anderen Fenster geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-124">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved: "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="a9c28-125">Möchten Sie eine Kopie im Standardordner für das Element erstellen? "</span><span class="sxs-lookup"><span data-stu-id="a9c28-125">Do you want to make a copy in the default folder for the item?"</span></span>
- <span data-ttu-id="a9c28-126">Es wurde ein Problem behoben, bei dem Datumsangaben im Minikalender für Benutzer in Japan nicht fett dargestellt wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-126">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>
- <span data-ttu-id="a9c28-127">Es wurde ein Problem behoben, aufgrund dessen Kalendererinnerungen keine genauen Zeiten für Besprechungen in weniger als einer Woche anzeigen konnten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-127">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-128">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-128">PowerPoint</span></span>

- <span data-ttu-id="a9c28-129">Es wurde ein Problem behoben, bei dem der Anwesenheits Farbindikator eines Benutzers während einer Live-gemeinsamen Erstellungs Sitzung nicht im gemeinsamen Dokument Erstellungs Katalog aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-129">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>

### <a name="project"></a><span data-ttu-id="a9c28-130">Project</span><span class="sxs-lookup"><span data-stu-id="a9c28-130">Project</span></span>

- <span data-ttu-id="a9c28-131">Es wurde ein Problem behoben, bei dem, wenn feste Daueraufgaben bei 100% abgeschlossen sind, das tatsächliche Ende jedoch nicht angegeben ist, der Vorgang "% abgeschlossen" als weniger als 100% angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="a9c28-131">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-132">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-132">Word</span></span>

- <span data-ttu-id="a9c28-133">Es wurde ein Problem behoben, bei dem die Farbe des HTML-Hyperlinks nicht korrekt gerendert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-133">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a9c28-134">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a9c28-134">Office Suite</span></span>

- <span data-ttu-id="a9c28-135">Es wurde ein Problem behoben, bei dem URLs, die nicht http oder HTTPS-basiert waren, nicht in der Liste der zuletzt verwendeten Listen angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-135">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2007-june-12"></a><span data-ttu-id="a9c28-137">Version 2007:12. Juni</span><span class="sxs-lookup"><span data-stu-id="a9c28-137">Version 2007: June 12</span></span>
<span data-ttu-id="a9c28-138">*Version 2007 (Build 13006,20002)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-138">*Version 2007 (Build 13006.20002)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a9c28-140">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a9c28-140">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a9c28-141">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-141">Excel</span></span>

- <span data-ttu-id="a9c28-142">**Abrufen von Organisationsdaten aus Power BI mithilfe von Datentypen:** Excel-Datentypen von Power BI werden nun für Insider in Organisationen mit Office 365 E5/A5 oder Microsoft 365 E5/A5 bereit gerollt.</span><span class="sxs-lookup"><span data-stu-id="a9c28-142">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="a9c28-143">Das erhalten der benötigten Informationen und das einfache aktualisieren ist für viele tägliche Workflows entscheidend.</span><span class="sxs-lookup"><span data-stu-id="a9c28-143">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="a9c28-144">Wir geben Ihnen Zugriff auf Ihre Unternehmens-oder Organisationsinformationen von Power BI als einen Datentyp in Excel, wodurch die Möglichkeit erweitert wird, verknüpfte Informationen in Ihren Tabellen zu integrieren.</span><span class="sxs-lookup"><span data-stu-id="a9c28-144">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="a9c28-145">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a9c28-145">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="a9c28-146">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/).</span><span class="sxs-lookup"><span data-stu-id="a9c28-146">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-149">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-149">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a9c28-150">Access</span><span class="sxs-lookup"><span data-stu-id="a9c28-150">Access</span></span>

- <span data-ttu-id="a9c28-151">Es wurde ein Problem behoben, aufgrund dessen Microsoft Access Fehler beim Identifizieren einer Identitätsspalte in einer verknüpften SQL Server-Tabelle verursachte, was dazu führen könnte, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-151">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="a9c28-152">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-152">Excel</span></span>

- <span data-ttu-id="a9c28-153">Es wurde ein Problem behoben, bei dem die wichtigsten Rasterlinien von Radar Diagrammen nicht ordnungsgemäß formatiert werden konnten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-153">We fixed an issue where the major grid lines of radar charts could not be formatted correctly.</span></span>

### <a name="project"></a><span data-ttu-id="a9c28-154">Project</span><span class="sxs-lookup"><span data-stu-id="a9c28-154">Project</span></span>

- <span data-ttu-id="a9c28-155">Es wurde ein Problem behoben, bei dem das ProjectBeforeTaskChange-Ereignis nicht ausgelöst wurde, als es eine Änderung am Projektsammelvorgang gab, entweder im Feld Projektstart/-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a9c28-155">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>
- <span data-ttu-id="a9c28-156">Es wurde ein Problem behoben, bei dem ein Baseline-Reset oder-Update Zeitphasen bezogene Kosten/Arbeitsressourcen ändern könnte und der Basisplan falsche Budgetwerte widerspiegeln könnte.</span><span class="sxs-lookup"><span data-stu-id="a9c28-156">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-157">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-157">Word</span></span>

- <span data-ttu-id="a9c28-158">Es wurde ein Problem behoben, bei dem die Möglichkeit, die Formatierung im Kommentarbereich über die Schaltfläche "Formatierung löschen" im Office-Menüband zu löschen, nicht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="a9c28-158">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>
- <span data-ttu-id="a9c28-159">Es wurde ein Problem behoben, bei dem das Ändern der Größe einer Tabelle, wenn das Lineal nicht angezeigt wird, dazu führte, dass andere Anwendungen, die im Hintergrund ausgeführt werden, mit dem blinken beginnen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-159">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>
- <span data-ttu-id="a9c28-160">Es wurde ein Problem behoben, bei dem im Modus "gemeinsame Dokumenterstellung" Kommentar Antworten manchmal nicht im Kommentarbereich angezeigt, aber im Bereich "Überarbeitung" angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-160">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>
- <span data-ttu-id="a9c28-161">Es wurde ein Problem behoben, bei dem bei einer Liste von mehr als 50 häufig geöffneten Dokumenten in Word ein Überarbeitungsverlauf angezeigt wird, nachdem ein Dokument gespeichert und geöffnet wurde, obwohl keine Änderungen an diesem Dokument vorgenommen wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-161">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-june-05"></a><span data-ttu-id="a9c28-163">Version 2006: Juni 05</span><span class="sxs-lookup"><span data-stu-id="a9c28-163">Version 2006: June 05</span></span>
<span data-ttu-id="a9c28-164">*Version 2006 (Build 13001,20002)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-164">*Version 2006 (Build 13001.20002)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a9c28-166">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a9c28-166">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a9c28-167">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-167">Excel</span></span>

- <span data-ttu-id="a9c28-168">**Sortieren/Filtern bei der Zusammenarbeit in Excel:** Sie können Ihre Excel-Datei jetzt sortieren und Filtern, während Sie mit anderen Personen zusammenarbeiten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-168">**Sort/filter while collaborating in Excel:** You can now sort and filter your Excel file while collaborating with others.</span></span> <span data-ttu-id="a9c28-169">Dieses neue Feature verhindert, dass Sie von den Sortierungen und Filtern anderer Benutzer betroffen sind, während Sie das Dokument gemeinsam erstellen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-169">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span>

- <span data-ttu-id="a9c28-170">**Erstellen von PivotTables aus Datasets in Power BI in Excel:** Sie können PivotTables in Excel erstellen, die mit wenigen Klicks mit in Power BI gespeicherten Datasets verbunden sind.</span><span class="sxs-lookup"><span data-stu-id="a9c28-170">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="a9c28-171">Auf diese Weise können Sie das Beste aus PivotTables und Power BI erhalten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-171"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="a9c28-172">Berechnen, zusammenfassen und Analysieren Ihrer Daten mit PivotTables aus ihren Secure Power BI-Datasets.</span><span class="sxs-lookup"><span data-stu-id="a9c28-172">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="a9c28-173">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a9c28-173">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a><span data-ttu-id="a9c28-174">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-174">Outlook</span></span>

- <span data-ttu-id="a9c28-175">**Schnelles Öffnen von Elementen aus der vorherigen Sitzung:** Wir haben eine Option zum schnellen Öffnen von Elementen aus einer vorherigen Outlook-Sitzung hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="a9c28-175">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="a9c28-176">Unabhängig davon, ob Outlook abstürzt oder geschlossen wird, können Sie die Elemente jetzt schnell neu starten, wenn Sie die APP erneut öffnen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-176">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="a9c28-177">Dieses Feature ist standardmäßig aktiviert.</span><span class="sxs-lookup"><span data-stu-id="a9c28-177">This feature is on by default.</span></span> <span data-ttu-id="a9c28-178">Wechseln Sie zum Deaktivieren der Option Optionen > allgemeine > Start Optionen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-178">To turn it off, go to Options > General > Start up Options.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-181">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-181">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a9c28-182">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-182">Excel</span></span>

- <span data-ttu-id="a9c28-183">Es wurde ein Problem behoben, bei dem benutzerdefinierte Werte auf der Diagrammachse nicht ordnungsgemäß angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-183">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>
- <span data-ttu-id="a9c28-184">Es wurde ein Problem behoben, bei dem Arbeitsblätter mit mehreren Formeln mit definierten Namen zu längeren Zeiten beim Speichern von Dateien führten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-184">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

### <a name="outlook"></a><span data-ttu-id="a9c28-185">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-185">Outlook</span></span>

- <span data-ttu-id="a9c28-186">Es wurde ein Problem behoben, bei dem das Fenster IME (Input Method Editor) den zugrunde liegenden Text über den IME überlappen würde, wenn mehrere Monitore mit unterschiedlichen Auflösungen verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-186">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>
- <span data-ttu-id="a9c28-187">Es wurde ein Problem behoben, bei dem das Anzeigen einer Vorlage beim Erstellen einer neuen e-Mail-Nachricht zu einem Absturz führen würde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-187">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>
- <span data-ttu-id="a9c28-188">Es wurde ein Problem behoben, bei dem Benutzer nach Outlook, Version 1911, keine öffentlichen Ordner Exchange 2010 konnten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-188">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>
- <span data-ttu-id="a9c28-189">Es wurde ein Problem behoben, bei dem die Schaltfläche kategorisieren für Gruppenkalender im Office-Menüband deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-189">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="a9c28-190">Es wurde ein Problem behoben, aufgrund dessen Benutzer mit Konflikt verursachenden Kontakten in Outlook Abstürze abstürzen konnten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-190">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>
- <span data-ttu-id="a9c28-191">Es wurde ein Problem behoben, aufgrund dessen die Dropdownliste der Online Archive in Ordner Eigenschaften für Benutzer mit hohen dpi-Monitoren fehlte.</span><span class="sxs-lookup"><span data-stu-id="a9c28-191">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>
- <span data-ttu-id="a9c28-192">Es wurde ein Problem behoben, aufgrund dessen Benutzer bei der Arbeit mit Hyperlinks in reinen Text-e-Mails einen Absturz in Outlook verursachten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-192">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>
- <span data-ttu-id="a9c28-193">Es wurde ein Problem behoben, aufgrund dessen Outlook keine langen Dateinamen analysieren konnte, die mit RFC2231 codiert wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-193">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>
- <span data-ttu-id="a9c28-194">Es wurde ein Problem behoben, aufgrund dessen Outlook-Benutzer bei der Verwendung von Bildschirmsprachausgaben nicht mehr reagierten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-194">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-195">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-195">PowerPoint</span></span>

- <span data-ttu-id="a9c28-196">Es wurde ein Problem beim Öffnen von Server konfigurierten Dateien mit formularbasierter Authentifizierung behoben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-196">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>
- <span data-ttu-id="a9c28-197">Es wurde ein Problem behoben, bei dem PowerPoint-Dateien mit eingebetteten Diagrammen/Arbeitsmappen zu Fehlern beim Speichern der Datei führen könnten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-197">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>
- <span data-ttu-id="a9c28-198">Es wurde ein Problem behoben, bei dem ein Kommentarbereich, der vom Benutzer geschlossen wurde, automatisch erneut geöffnet wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-198">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>
- <span data-ttu-id="a9c28-199">Es wurde ein Problem behoben, bei dem sich der Folien Editor von einer Folie zur nächsten Folie hin überschneidet.</span><span class="sxs-lookup"><span data-stu-id="a9c28-199">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="a9c28-200">Project</span><span class="sxs-lookup"><span data-stu-id="a9c28-200">Project</span></span>

- <span data-ttu-id="a9c28-201">Es wurde ein Problem behoben, aufgrund dessen verhindert wurde, dass verwaiste Aufgaben gelöscht oder erneut zugewiesen wurden, nachdem der übergeordnete Plan gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-201">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-202">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-202">Word</span></span>

- <span data-ttu-id="a9c28-203">Es wurde ein Problem behoben, bei dem Timestamps in Kommentar Bereichen nicht auf der Systemgebietsschema zeitbasierten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-203">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>
- <span data-ttu-id="a9c28-204">Es wurde ein Problem behoben, bei dem Kommentare zwischen der-Webanwendung und der Desktopanwendung nicht synchronisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-204">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)


## <a name="version2006may29"></a><span data-ttu-id="a9c28-206">Version 2006:29. Mai</span><span class="sxs-lookup"><span data-stu-id="a9c28-206">Version 2006: May 29</span></span>
<span data-ttu-id="a9c28-207">*Version 2006 (Build 12920,20000)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-207">*Version 2006 (Build 12920.20000)*</span></span>

### <a name="featureupdates"></a><span data-ttu-id="a9c28-208">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a9c28-208">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a9c28-209">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-209">Outlook</span></span>

- <span data-ttu-id="a9c28-210">**Zusätzliche Schaltflächen zu Outlook-Popupbenachrichtigungen hinzugefügt:** Schaltflächen für die schnell Aktion werden jetzt in Outlook-Popupbenachrichtigungen angezeigt, wenn Outlook unter Windows 10 ausführt wird.</span><span class="sxs-lookup"><span data-stu-id="a9c28-210">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-211">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-211">PowerPoint</span></span>

- <span data-ttu-id="a9c28-212">**Verbesserte Stream Videoleistung in PowerPoint:** Wir haben Verbesserungen an der Wiedergabeleistung von Microsoft Stream-Videos vorgenommen, um die Ladezeit von Videos zu minimieren und eine glatte Anzeige zu erzielen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-212">**Improved Stream video performance in PowerPoint:** We've made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span>  <span data-ttu-id="a9c28-213">Verwenden Sie Ihre Unternehmensvideos aus Microsoft Stream, um bessere Präsentationen zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-213">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolvedissues"></a><span data-ttu-id="a9c28-216">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-216">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="a9c28-217">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-217">Excel</span></span>

- <span data-ttu-id="a9c28-218">Es wurde ein Problem behoben, bei dem Excel gelegentlich beim Eingriff in OneDrive heruntergefahren wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-218">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>
- <span data-ttu-id="a9c28-219">Es wurde ein Problem behoben, bei dem durch Klicken auf einen mit einem Lesezeichen versehenen Hyperlink in derselben Arbeitsmappe das Ausblenden der Arbeitsmappe verursacht würde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-219">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>
- <span data-ttu-id="a9c28-220">Es wurde ein Problem behoben, bei dem einige kopierte und eingefügte Diagramm links anstelle universeller Adressen zugeordnete Laufwerks Adressen verwendeten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-220">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>
- <span data-ttu-id="a9c28-221">Es wurde ein Problem behoben, aufgrund dessen Excel möglicherweise nicht mehr reagiert, nachdem Sie STRG + UMSCHALT + Pfeiltasten verwendet haben, um zu scrollen, wenn das Excel-Fenster über Teams freigegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-221">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-222">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-222">PowerPoint</span></span>

- <span data-ttu-id="a9c28-223">Es wurde ein Problem behoben, bei dem Folien nach dem Zoomen mit dem Mausrad nicht zentriert wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-223">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-224">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-224">Word</span></span>

- <span data-ttu-id="a9c28-225">Es wurde ein Problem behoben, bei dem das Kopieren und Einfügen von Text in einen Kommentarbereich nicht angezeigt würde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-225">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>
- <span data-ttu-id="a9c28-226">Es wurde ein Problem behoben, bei dem Kommentar-Hint Bubbles verschwommen bei 100% Zoom erschienen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-226">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>
- <span data-ttu-id="a9c28-227">Es wurde ein Problem behoben, bei dem das Aktivieren von Richtlinien Word 2007 und späteren binären Dokumenten und Vorlagen dazu führen würde, dass einige gemeinsame Dokument Erstellungs Fälle fehlschlagen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-227">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>
- <span data-ttu-id="a9c28-228">Es wurde ein Problem behoben, bei dem Dateien mit langen Pfadnamen (mehr als 32 KB) nicht geöffnet würden und eine entsprechende Fehlermeldung nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-228">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2006-may-22"></a><span data-ttu-id="a9c28-229">Version 2006:22. Mai</span><span class="sxs-lookup"><span data-stu-id="a9c28-229">Version 2006: May 22</span></span>
<span data-ttu-id="a9c28-230">*Version 2006 (Build 12914,20000)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-230">*Version 2006 (Build 12914.20000)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a9c28-232">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a9c28-232">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a9c28-233">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-233">Excel</span></span>

- <span data-ttu-id="a9c28-234">**In fixierten Ordnern speichern:** Durch anheften Ihrer Ordner wird das Speichern von Office-Dateien vereinfacht.</span><span class="sxs-lookup"><span data-stu-id="a9c28-234">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="a9c28-235">Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die verfügbaren Ordner erhalten möchten, wenn eine neue Datei gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="a9c28-235">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="a9c28-236">Wir freuen uns darauf, Ihnen eine neue Funktion zu bieten: Heften Sie Ihre Ordner im Dialogfeld Speichern an.</span><span class="sxs-lookup"><span data-stu-id="a9c28-236">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="a9c28-237">Mit dieser neuen Funktion können Sie Ihre Word-, Excel-und PowerPoint-Dateien einfacher speichern.</span><span class="sxs-lookup"><span data-stu-id="a9c28-237">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="a9c28-238">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/).</span><span class="sxs-lookup"><span data-stu-id="a9c28-238">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-239">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-239">PowerPoint</span></span>

- <span data-ttu-id="a9c28-240">**In fixierten Ordnern speichern:** Durch anheften Ihrer Ordner wird das Speichern von Office-Dateien vereinfacht.</span><span class="sxs-lookup"><span data-stu-id="a9c28-240">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="a9c28-241">Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die verfügbaren Ordner erhalten möchten, wenn eine neue Datei gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="a9c28-241">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="a9c28-242">Wir freuen uns darauf, Ihnen eine neue Funktion zu bieten: Heften Sie Ihre Ordner im Dialogfeld Speichern an.</span><span class="sxs-lookup"><span data-stu-id="a9c28-242">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="a9c28-243">Mit dieser neuen Funktion können Sie Ihre Word-, Excel-und PowerPoint-Dateien einfacher speichern.</span><span class="sxs-lookup"><span data-stu-id="a9c28-243">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="a9c28-244">Einzelheiten finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/).</span><span class="sxs-lookup"><span data-stu-id="a9c28-244">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-245">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-245">Word</span></span>

- <span data-ttu-id="a9c28-246">**In fixierten Ordnern speichern:** Durch anheften Ihrer Ordner wird das Speichern von Office-Dateien vereinfacht.</span><span class="sxs-lookup"><span data-stu-id="a9c28-246">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="a9c28-247">Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die verfügbaren Ordner erhalten möchten, wenn eine neue Datei gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="a9c28-247">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="a9c28-248">Wir freuen uns darauf, Ihnen eine neue Funktion zu bieten: Heften Sie Ihre Ordner im Dialogfeld Speichern an.</span><span class="sxs-lookup"><span data-stu-id="a9c28-248">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="a9c28-249">Mit dieser neuen Funktion können Sie Ihre Word-, Excel-und PowerPoint-Dateien einfacher speichern.</span><span class="sxs-lookup"><span data-stu-id="a9c28-249">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="a9c28-250">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/).</span><span class="sxs-lookup"><span data-stu-id="a9c28-250">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-253">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-253">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a9c28-254">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-254">Excel</span></span>

- <span data-ttu-id="a9c28-255">Es wurde ein Problem behoben, aufgrund dessen die Fehlermeldung: "diese Arbeitsmappe wird derzeit von einem anderen referenziert und nicht geschlossen werden kann" angezeigt wird, da Add-Ins in alphabetischer Reihenfolge geladen wurden, statt in einer benutzerdefinierten Reihenfolge.</span><span class="sxs-lookup"><span data-stu-id="a9c28-255">We fixed an issue where the error message: “This workbook is currently referenced by another and cannot be closed” would appear because Add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>
- <span data-ttu-id="a9c28-256">Es wurde ein Problem behoben, bei dem der Arbeitsspeicher beim Verwalten von Schriftarten zwischen Excel und einigen Anwendungen für Hilfstechnologien von Drittanbietern beschädigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-256">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>
- <span data-ttu-id="a9c28-257">Es wurde ein Problem behoben, bei dem Excel abstürzte, wenn Add-Ins nach Host Elementen in Arbeitsblättern Fragen, die Shapes mit noselect-Sperren enthalten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-257">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

### <a name="outlook"></a><span data-ttu-id="a9c28-258">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-258">Outlook</span></span>

- <span data-ttu-id="a9c28-259">Es wurde ein Problem behoben, bei dem das Folder. BeforeItemMove-Ereignis nicht ordnungsgemäß ausgelöst wurde, wenn ein Benutzer Elemente zwischen Ordnern verschoben hat.</span><span class="sxs-lookup"><span data-stu-id="a9c28-259">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>
- <span data-ttu-id="a9c28-260">Es wurde ein Problem behoben, bei dem Benutzer Kalenderelemente sahen, die den Mitternachts Schwellenwert als ganztägige Ereignisse überspannt haben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-260">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>
- <span data-ttu-id="a9c28-261">Es wurde ein Problem behoben, bei dem Outlook abstürzte, als zwei Add-Ins eine Schaltfläche zu derselben Gruppe im Menüband hinzugefügt haben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-261">We fixed an issue where Outlook crashed when two Add-ins added a button to the same group in the ribbon.</span></span>
- <span data-ttu-id="a9c28-262">Es wurde ein Problem behoben, bei dem Benutzer keinen Kalender für einen Gastbenutzer freigeben konnten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-262">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-263">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-263">PowerPoint</span></span>

- <span data-ttu-id="a9c28-264">Es wurde ein Problem behoben, bei dem ein-und Auszoomen aus dem Präsentationsbereich zu einer Lücke zwischen dem vergrößerten Auswahlrechteck und dem Mauszeiger führte.</span><span class="sxs-lookup"><span data-stu-id="a9c28-264">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

### <a name="project"></a><span data-ttu-id="a9c28-265">Project</span><span class="sxs-lookup"><span data-stu-id="a9c28-265">Project</span></span>

- <span data-ttu-id="a9c28-266">Es wurde ein Problem behoben, bei dem Project nach dem Klicken auf Optionen abstürzte.</span><span class="sxs-lookup"><span data-stu-id="a9c28-266">We fixed an issue where Project would crash after clicking on Options.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-267">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-267">Word</span></span>

- <span data-ttu-id="a9c28-268">Es wurde ein Problem behoben, bei dem Hyperlinks in Kommentaren nicht funktionierten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-268">We fixed an issue where hyperlinks in comments weren’t working.</span></span>
- <span data-ttu-id="a9c28-269">Es wurde ein Problem behoben, bei dem ein-und Auszoomen aus dem Präsentationsbereich zu einer Lücke zwischen dem vergrößerten Auswahlrechteck und dem Mauszeiger führte.</span><span class="sxs-lookup"><span data-stu-id="a9c28-269">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>
- <span data-ttu-id="a9c28-270">Es wurde ein Problem behoben, bei dem das Einfügen von HTML in WordMail for Calendar nicht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="a9c28-270">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>
- <span data-ttu-id="a9c28-271">Es wurde ein Problem behoben, bei dem das Antworten auf einen Kommentar in einer gemeinsamen Sitzung manchmal dazu führen könnte, dass Word einfriert.</span><span class="sxs-lookup"><span data-stu-id="a9c28-271">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-may-15"></a><span data-ttu-id="a9c28-273">Version 2006:15. Mai</span><span class="sxs-lookup"><span data-stu-id="a9c28-273">Version 2006: May 15</span></span>
<span data-ttu-id="a9c28-274">*Version 2006 (Build 12905.20000)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-274">*Version 2006 (Build 12905.20000)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a9c28-276">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a9c28-276">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a9c28-277">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-277">Excel</span></span>

- <span data-ttu-id="a9c28-278">**Stellen Sie eine PDF-Verbindung her:** Verbinden mit, importieren, Aktualisieren von Daten aus einer PDF-Datei.</span><span class="sxs-lookup"><span data-stu-id="a9c28-278">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="a9c28-279">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a9c28-279">Learn more</span></span>](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

### <a name="outlook"></a><span data-ttu-id="a9c28-280">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-280">Outlook</span></span>

- <span data-ttu-id="a9c28-281">**Finden Sie genau das, was Sie benötigen:** Schränken Sie die Suche mit Optionen wie Ordner, Absender, Datum, anlageninfo und mehr ein.</span><span class="sxs-lookup"><span data-stu-id="a9c28-281">**Find just what you need:** Narrow your search with options like folder, sender, date, attachment info, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-282">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-282">PowerPoint</span></span>

- <span data-ttu-id="a9c28-283">**Kein Klicker erforderlich: Ihre Ohrhörer haben Sie abgedeckt:** Verwenden Sie Ihre Surface-Ohrhörer, um Ihre PowerPoint-Präsentationen zu steuern.</span><span class="sxs-lookup"><span data-stu-id="a9c28-283">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="a9c28-284">Wichtig: Sie müssen ihre Oberflächen Ohrhörer in der Surface Audio-App für Windows 10 koppeln, um Gesten zum Steuern von Präsentationen zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-284">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="a9c28-285">Anweisungen zum Einstieg in die Surface-Audioanwendung unter Windows 10 finden Sie hier.</span><span class="sxs-lookup"><span data-stu-id="a9c28-285">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="a9c28-286">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a9c28-286">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="word"></a><span data-ttu-id="a9c28-287">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-287">Word</span></span>

- <span data-ttu-id="a9c28-288">**Automatisches Anwenden oder empfehlen von Sensitivitäts Bezeichnungen:** Office kann eine Vertraulichkeits Bezeichnung basierend auf dem erkannten vertraulichen Inhalt empfehlen oder automatisch anwenden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-288">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-291">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-291">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="a9c28-292">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-292">Excel</span></span>
- <span data-ttu-id="a9c28-293">Es wurde ein Problem behoben, das zu einer verbesserten Leistungszeit für Benutzer führte, wenn Sie die zusammengeführten Spalten gelöscht haben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-293">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>
- <div><span data-ttu-id="a9c28-294">Es wurde ein Problem behoben, aufgrund dessen Druckernamen in der Liste der verfügbaren Drucker dupliziert wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-294">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-295">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-295">PowerPoint</span></span>
- <span data-ttu-id="a9c28-296">Es wurde ein Problem behoben, bei dem Tastenkombinationen und Rechtschreibprüfung nicht wie erwartet funktionieren, wenn Sie eine Englisch Schweiz (QWERTZ)-Tastatur verwenden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-296">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-297">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-297">Word</span></span>
- <span data-ttu-id="a9c28-298">Es wurde ein Problem behoben, bei dem das Hinzufügen eines neuen Kommentars in einem leeren Dokument nichts tun würde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-298">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>
- <span data-ttu-id="a9c28-299">Es wurde ein Problem behoben, bei dem das Einfügen oder Aktualisieren eines Index in einem Dokument mit mehr als hundert Einträgen zum Absturz der Anwendung führen würde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-299">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>
- <span data-ttu-id="a9c28-300">Es wurde ein Problem behoben, bei dem Dateien mit benutzerdefinierten XML-Werten äußerst langsam geöffnet wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-300">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a9c28-301">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a9c28-301">Office Suite</span></span>
- <span data-ttu-id="a9c28-302">Es wurde ein Problem in Visual Basic für Anwendungen in Microsoft Office behoben, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung als beschädigt beim Laden angezeigt würden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-302">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-may-08"></a><span data-ttu-id="a9c28-305">Version 2006: 08. Mai</span><span class="sxs-lookup"><span data-stu-id="a9c28-305">Version 2006: May 08</span></span>
<span data-ttu-id="a9c28-306">*Version 2006 (Build 12829.20000)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-306">*Version 2006 (Build 12829.20000)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a9c28-308">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a9c28-308">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a9c28-309">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-309">Excel</span></span>

- <span data-ttu-id="a9c28-310">**Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-310">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="a9c28-311">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-311">Outlook</span></span>

- <span data-ttu-id="a9c28-312">**Bessere Ergebnisse – im Handumdrehen:** wir haben die Suche aktualisiert, damit Sie intelligenter, schneller und zuverlässiger als je zuvor ist.</span><span class="sxs-lookup"><span data-stu-id="a9c28-312">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="a9c28-313">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a9c28-313">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="a9c28-314">**Erzählen Sie mit animierten GIFs über sich:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden künftig noch pfiffiger aussehen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-314">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-315">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-315">PowerPoint</span></span>

- <span data-ttu-id="a9c28-316">**Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-316">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span> [<span data-ttu-id="a9c28-317">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a9c28-317">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="a9c28-318">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-318">Word</span></span>

- <span data-ttu-id="a9c28-319">**Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-319">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-322">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-322">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="a9c28-323">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a9c28-323">Office Suite</span></span>

- <span data-ttu-id="a9c28-324">Wir haben das Problem untersucht und behoben, bei dem die Bereitstellung von Office 365 ProPlus über InTune nach einem Herunterfahren des Betriebssystems pausiert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-324">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-may-01"></a><span data-ttu-id="a9c28-326">Version 2005: 1. Mai</span><span class="sxs-lookup"><span data-stu-id="a9c28-326">Version 2005: May 01</span></span>
<span data-ttu-id="a9c28-327">*Version 2005 (Build 12827.20030)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-327">*Version 2005 (Build 12827.20030)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a9c28-329">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a9c28-329">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a9c28-330">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-330">Outlook</span></span>

- <span data-ttu-id="a9c28-331">**Verbesserte Links in E-Mails:** Wenn Sie einen Link zu einer Datei einfügen, ersetzt der Dateiname die URL.</span><span class="sxs-lookup"><span data-stu-id="a9c28-331">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="a9c28-332">Sie können die Berechtigungen so ändern, dass alle Empfänger Zugriff haben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-332">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="a9c28-333">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a9c28-333">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-336">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-336">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a9c28-337">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-337">Excel</span></span>

- <span data-ttu-id="a9c28-338">Ein Problem wurde behoben, bei dem die Diagrammdatentabelle Werte in einer Datumsachse nicht korrekt rendern konnte.</span><span class="sxs-lookup"><span data-stu-id="a9c28-338">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>
- <span data-ttu-id="a9c28-339">Es wurde ein Problem behoben, bei dem Seitenumbrüche nicht deaktiviert werden konnten, nachdem die Seitenlayout- oder Seitenumbruchsvorschau angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-339">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>
- <span data-ttu-id="a9c28-340">Es wurde ein Problem behoben, bei dem Diagrammlinienarten nach dem Ein- und Ausblenden von Spalten mit Seriendaten verloren gehen konnten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-340">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>
- <span data-ttu-id="a9c28-341">Das Einfügen einer Spalte in eine gefilterte Liste würde länger dauern als erwartet.</span><span class="sxs-lookup"><span data-stu-id="a9c28-341">Inserting a column in a filtered list would take longer than expected.</span></span>
- <span data-ttu-id="a9c28-342">Ein Absturz konnte auftreten, wenn versucht wurde, Änderungen mithilfe des Legacymodus "Freigegebene Arbeitsmappe" auf einem neuen Blatt für eine Arbeitsmappe aufzulisten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-342">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>
- <span data-ttu-id="a9c28-343">Das Problem, bei dem es sein konnte, dass benutzerdefinierte Formatierungen in Pivot-Diagrammen nicht gespeichert wurden, wenn die Option "Invertieren, wenn negativ" aktiviert war, wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-343">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>
- <span data-ttu-id="a9c28-344">Es wurde ein Problem behoben, bei dem die benutzerdefinierte Formatierung für einen einzelnen Datenpunkt in einem Pivot-Diagramm nicht gespeichert wurde, wenn die Option "Invertieren, wenn negativ" ausgewählt wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-344">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>
- <span data-ttu-id="a9c28-345">Diese Änderung behebt ein Problem, bei dem das in eine CSV-Datei hochgeladene @-Zeichen dazu führte, dass die Zeichenfolge nach dem @-Zeichen in eine Formel konvertiert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-345">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>
- <span data-ttu-id="a9c28-346">Es wurde ein Problem behoben, bei dem Dezimalwerte in der SEQUENCE-Funktion nicht korrekt gerundet wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-346">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="outlook"></a><span data-ttu-id="a9c28-347">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-347">Outlook</span></span>

- <span data-ttu-id="a9c28-348">Behebt ein Problem, das dazu führte, dass sehr lange Safelinks, auf die Benutzer im Outlook-Desktopclient klickten, aufgrund von Trunkierung nicht geladen wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-348">Addresses an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>
- <span data-ttu-id="a9c28-349">Es wurde ein Problem behoben, bei dem Outlook-Ordner mit Namen, die DBCS-Zeichen (Doublebyte-Zeichensatz) enthalten, bei der Synchronisierung mit dem Server zeitweise verschwanden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-349">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="a9c28-350">Dazu musste Outlook mit einem IMAP-Konto konfiguriert und auf einem System mit dem Gebietsschema „Japanisch“ ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-350">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-351">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-351">PowerPoint</span></span>

- <span data-ttu-id="a9c28-352">Es wurde ein Problem behoben, bei dem Entwürfe von Kommentaren nicht verfügbar waren, wenn ein Benutzer einen Kommentar erstellte, ohne ihn zu posten, und den Kommentarbereich schloss, dann ein neues Fenster öffnete, über mehrere Folien navigierte, das Fenster schloss und schließlich den Kommentarbereich in der ursprünglichen Präsentation wieder öffnete.</span><span class="sxs-lookup"><span data-stu-id="a9c28-352">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

### <a name="project"></a><span data-ttu-id="a9c28-353">Project</span><span class="sxs-lookup"><span data-stu-id="a9c28-353">Project</span></span>

- <span data-ttu-id="a9c28-354">Folgendes Problem wurde behoben: Wenn Sie Project in Verbindung mit der Project Web App verwenden, das Kommas als Dezimaltrennzeichen festgelegt ist, und Sie versuchten, eine Verzögerung hinzuzufügen, schlägt die Methode "TaskDependencies Add" fehl.</span><span class="sxs-lookup"><span data-stu-id="a9c28-354">Fixed an issue where if Project is connected to the Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-355">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-355">Word</span></span>

- <span data-ttu-id="a9c28-356">Es wurde ein Problem behoben, das dazu führte, dass das Einfügen von Kommentaren in ein Dokument im Kollaborationsmodus nicht immer funktionierte.</span><span class="sxs-lookup"><span data-stu-id="a9c28-356">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>
- <span data-ttu-id="a9c28-357">Diese Änderung behebt ein Problem, bei dem die Personenkarte kurzzeitig eingeblendet wurde, wenn auf die Erwähnung geklickt wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-357">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>
- <span data-ttu-id="a9c28-358">Es wurde das Problem behoben, dass beim Schließen eines Dokuments mit Kommentarentwürfen der Benutzer aufgefordert wurde, ob er das Dokument schließen möchte, ohne die Kommentarentwürfe zu speichern.</span><span class="sxs-lookup"><span data-stu-id="a9c28-358">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="a9c28-359">Das Abbrechen der Eingabeaufforderung schloss das Dokument, anstatt es geöffnet zu lassen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-359">Cancelling the prompt would close the document rather than leaving it open.</span></span>
- <span data-ttu-id="a9c28-360">Es wurde ein Problem behoben, bei dem die Übersetzung eines geposteten Kommentars den Fehler "Fehler beim Einfügen des übersetzten Textes" zur Folge hatte.</span><span class="sxs-lookup"><span data-stu-id="a9c28-360">Fixed an issue where translating a posted comment would result in the error "Inserting translated text failed".</span></span>
- <span data-ttu-id="a9c28-361">In der Webansicht und im Plastischen Reader wurde durch das Anklicken eines Hinweises nach oben gescrollt, obwohl er bereits angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-361">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="a9c28-362">Dieser Fehler wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-362">This has been fixed.</span></span>
- <span data-ttu-id="a9c28-363">Wir haben ein Problem behoben, dass infolge des Speicherns einer Datei, die ein Makro enthält, unter einem neuen Namen sie mit der Erweiterung DOCX und dem Dateinamen WRO0004.docx gespeichert wurde, und zwar unabhängig davon, was der Benutzer eingab, wodurch das Dokument unbrauchbar wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-363">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)


## <a name="version-2005-april-24"></a><span data-ttu-id="a9c28-365">Version 2005: 24. April</span><span class="sxs-lookup"><span data-stu-id="a9c28-365">Version 2005: April 24</span></span>
<span data-ttu-id="a9c28-366">*Version 2005 (Build 12816.20006)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-366">*Version 2005 (Build 12816.20006)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-368">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-368">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a9c28-369">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-369">Excel</span></span>
- <span data-ttu-id="a9c28-370">Diese Änderung behebt ein Problem, bei dem das Bestimmtheitsmaß der Diagrammtrendlinie (im Fall des erzwungenen y-Achsenabschnitts) falsch war, obwohl die Funktion LINEST den richtigen Wert zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="a9c28-370">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>
- <span data-ttu-id="a9c28-371">Diese Änderung behebt ein Problem, bei dem benutzerdefinierte Diagramm-Trendlinienformatierungen nicht immer gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-371">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

### <a name="outlook"></a><span data-ttu-id="a9c28-372">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-372">Outlook</span></span>
- <span data-ttu-id="a9c28-373">Es wurde ein Problem behoben, bei dem die Schaltfläche "Kategorisieren" für Gruppenkalender im Office-Menüband deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-373">Fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>
- <span data-ttu-id="a9c28-374">Es wurde ein Problem behoben, bei dem Gruppenordner von Unternehmenskunden, die nicht implementiert sind oder nicht funktionieren, in Outlook zu der Meldung "reagiert nicht" führte.</span><span class="sxs-lookup"><span data-stu-id="a9c28-374">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-375">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-375">PowerPoint</span></span>
- <span data-ttu-id="a9c28-376">Es wurde ein Problem behoben, bei dem beim Bewegen des Mauszeigers über das Sternchen-Symbol (\*) der Benutzername und das Datum der letzten Person, die das Dokument aktualisiert hat, nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-376">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-377">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-377">Word</span></span>
- <span data-ttu-id="a9c28-378">Beim Aktivieren der Option "Lesezeichen anzeigen" wurden keine Lesezeichen angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a9c28-378">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="a9c28-379">Dieser Fehler wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-379">This has been fixed.</span></span>
- <span data-ttu-id="a9c28-380">Diese Änderung behebt ein Problem, bei dem Text mit Hyperlinks möglicherweise nicht angezeigt wurde, wenn die Option "Feldcodes statt ihrer Werte anzeigen" aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="a9c28-380">This change fixes an issue where text with hyperlinks may not display if the option "Show field codes instead of their values" was enabled.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)


## <a name="version-2005-april-17"></a><span data-ttu-id="a9c28-382">Version 2005: 17. April</span><span class="sxs-lookup"><span data-stu-id="a9c28-382">Version 2005: April 17</span></span>
<span data-ttu-id="a9c28-383">*Version 2005 (Build 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-383">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-385">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-385">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a9c28-386">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-386">Excel</span></span>
- <span data-ttu-id="a9c28-387">Die Größe der Steuerelemente zur Bearbeitung von Zellreferenzen im Dialogfeld "Benutzerdefinierte Fehlerindikatoren", das bei Diagrammen verwendet wird, wurde erhöht.</span><span class="sxs-lookup"><span data-stu-id="a9c28-387">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="a9c28-388">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-388">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="a9c28-389">Ein Problem mit der Skalierung von Kontrollkästchen in Formularsteuerelementen beim Drucken wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-389">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="a9c28-390">Application.Evaluate (VBA) funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.</span><span class="sxs-lookup"><span data-stu-id="a9c28-390">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="a9c28-391">Diese Änderung behebt ein Problem, bei dem Informationen zur bedingten Formatierung (CF) nicht korrekt in XLSB-Dateien gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-391">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="a9c28-392">OneNote</span><span class="sxs-lookup"><span data-stu-id="a9c28-392">OneNote</span></span>
- <span data-ttu-id="a9c28-393">Ein Problem beim Speichern von Zeilenumbrüchen als vertikale Registerkarten wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-393">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="a9c28-394">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-394">Outlook</span></span>
- <span data-ttu-id="a9c28-395">Behebt ein Problem, das dazu führte, dass Benutzer keine "Persönliche Kontaktgruppe" als "Besprechungsteilnehmer" hinzufügen konnten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-395">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="a9c28-396">Behebt ein Problem, das dazu geführt hat, dass bei Besprechungen, die mehr als 2 Monate entfernt sind, ein Besprechungsthema im "Terminplanungs-Assistenten" nicht angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="a9c28-396">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="a9c28-397">Behebt ein Problem, das dazu führte, dass Benutzer beim Weiterleiten großer HTML-Nachrichten den Nachrichtentext abgeschnitten sahen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-397">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="a9c28-398">Es wurde die Möglichkeit des Erzwingens der S/MIME-Standardsignatur-Konfiguration über eine Gruppenrichtlinie hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="a9c28-398">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="a9c28-399">Behebt ein Problem, das dazu führte, dass Löschregeln, die für andere Postfächer als das primäre Postfach des Benutzers erstellt wurden, ungültig wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-399">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="a9c28-400">Behebt ein Problem, das dazu führte, dass Anlagen beim Weiterleiten einer verschlüsselten Nachricht verworfen wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-400">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="a9c28-401">Project</span><span class="sxs-lookup"><span data-stu-id="a9c28-401">Project</span></span>
- <span data-ttu-id="a9c28-402">Wenn Vorgänger/Nachfolger-Daten in einer Formular-Maske bearbeitet werden, wird ein zusätzliches ProjectBeforeTaskChange-Ereignis ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="a9c28-402">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="a9c28-403">Es wurde ein Problem behoben, bei dem Project abstürzen konnte, wenn das Feld „Boardstatus“ in einem Projekt geändert wurde, das mit einer SharePoint-Aufgabenliste verbunden ist.</span><span class="sxs-lookup"><span data-stu-id="a9c28-403">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="a9c28-404">Ein Problem wurde behoben, bei dem Project beim Speichern von Projekten, die mit älteren Project-Versionen erstellt wurden, möglicherweise abstürzt.</span><span class="sxs-lookup"><span data-stu-id="a9c28-404">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)


## <a name="version-2004-april-10"></a><span data-ttu-id="a9c28-406">Version 2004: 10. April</span><span class="sxs-lookup"><span data-stu-id="a9c28-406">Version 2004: April 10</span></span>
<span data-ttu-id="a9c28-407">*Version 2004 (Build 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-407">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (FEATUREDETAILS CONTENT START NICHT ENTFERNEN)

### <a name="feature-updates"></a><span data-ttu-id="a9c28-409">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a9c28-409">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a9c28-410">Access</span><span class="sxs-lookup"><span data-stu-id="a9c28-410">Access</span></span>

- <span data-ttu-id="a9c28-411">\*\* Das Dialogfeld „Tabelle anzeigen“ umgehen, direkt zu einem Aufgabenbereich wechseln und das Hinzufügen von Tabellen zu Beziehungen und Abfragen rationalisieren:\*\* Fügen Sie Tabellen und Abfragen hinzu, indem Sie auf vier Registerkarten klicken, Namen mehrfach auswählen, nach Text suchen und aus einem Aufgabenbereich ziehen, der während der Arbeit geöffnet bleibt.</span><span class="sxs-lookup"><span data-stu-id="a9c28-411">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="a9c28-412">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-412">Excel</span></span>

- <span data-ttu-id="a9c28-413">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="a9c28-413">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a9c28-414">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a9c28-414">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="a9c28-415">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-415">Outlook</span></span>

- <span data-ttu-id="a9c28-416">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="a9c28-416">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a9c28-417">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a9c28-417">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="a9c28-418">**Bewahren Sie die Klangtreue Ihrer Bilder, wenn Sie diese als Teil einer E-Mail versenden:** Eine neue Outlook-Einstellung ist verfügbar, um die Bildkomprimierung zu begrenzen, wenn Sie Bilder als Teil des E-Mail-Inhalts versenden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-418">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-419">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-419">PowerPoint</span></span>

- <span data-ttu-id="a9c28-420">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="a9c28-420">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a9c28-421">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a9c28-421">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="a9c28-422">**Synchronisieren von Änderungen während der Präsentation:** Änderungen können jetzt synchronisiert werden, wenn sie vorgenommen werden, selbst wenn sich die Präsentation im Bildschirmpräsentationsmodus befindet.</span><span class="sxs-lookup"><span data-stu-id="a9c28-422">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-423">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-423">Word</span></span>

- <span data-ttu-id="a9c28-424">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="a9c28-424">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a9c28-425">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a9c28-425">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="a9c28-426">**Fügen Sie einen privaten Kopie Anmerkungen hinzu:** Erstellen Sie handschriftliche Notizen nur für Sie, indem Sie eine private Kopie eines freigegebenen Dokuments erstellen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-426">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="a9c28-427">Wechseln Sie dazu einfach zu "Anzeige" > "Private Kopie erstellen".</span><span class="sxs-lookup"><span data-stu-id="a9c28-427">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-430">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-430">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a9c28-431">Access</span><span class="sxs-lookup"><span data-stu-id="a9c28-431">Access</span></span>

- <span data-ttu-id="a9c28-432">Probleme bei der Anpassung der Größe und der Aktualisierung von Tabellen im Aufgabenbereich wurden behoben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-432">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="a9c28-433">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-433">Excel</span></span>

- <span data-ttu-id="a9c28-434">Es wurde ein Problem behoben, bei dem das Auswählen eines Zellbereichs auf einem Arbeitsblatt zur Auswahl nur einer einzelnen Zelle geführt hat.</span><span class="sxs-lookup"><span data-stu-id="a9c28-434">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="a9c28-435">Es wurde ein Problem behoben, das dazu führen konnte, dass Excel nicht mehr reagierte, wenn die Größe eines Diagramms mit einigen x-Achsen-Bereichen reduziert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-435">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="a9c28-436">Es wurde ein Problem behoben, bei dem das Einfügen einer benutzerdefinierten Diagrammvorlage als Standard dazu führte, dass sie als Säulendiagramm gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-436">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="a9c28-437">Ein Problem wurde behoben, bei dem Datenbeschriftungen in Diagrammen leer angezeigt wurden, wenn die zugrundeliegenden Datenzellen keine Beschriftung aufwiesen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-437">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="a9c28-438">Es wurde ein Problem behoben, bei dem eine Excel-Tabelle mit aktiviertem Z1S1-Zellbezug die freigegeben bzw. gemeinsam erstellt wurde, der aktive Zellbezug im Z1S1-Modus nicht angezeigt wurde, wenn man auf das Symbol für die Anwesenheitsanzeige zeigte.</span><span class="sxs-lookup"><span data-stu-id="a9c28-438">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="a9c28-439">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-439">Outlook</span></span>

- <span data-ttu-id="a9c28-440">Behebt ein Problem, durch das gelegentlich Kategorien in E-Mail-Nachrichten nicht mehr aufschienen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-440">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="a9c28-441">Behebt ein Problem, durch das Stellvertretungen auf unterschiedlichen Computern unterschiedliche Ordnerhierarchien für freigegebene Postfächer angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-441">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="a9c28-442">Behebt ein Problem, das einen Absturz verursachte, wenn Benutzer versuchten, die Eigenschaften eines Organisationsformulars anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-442">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="a9c28-443">Behebt ein Problem, durch das einige Erinnerungen nicht ausgelöst wurden, wenn die Zeitzone auf einem Computer geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-443">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-444">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-444">PowerPoint</span></span>

- <span data-ttu-id="a9c28-445">Diese Änderung behebt ein Problem, bei dem beim Rendern eines Diagramms einer älteren Excel-Version, das als OLE-Objekt in PowerPoint oder Word eingebettet ist, u. U. nicht immer der Diagrammtitel angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-445">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="a9c28-446">Es wurde ein Problem behoben, bei dem beim Kopieren von Text aus Excel in PowerPoint u. U. dessen Formatierung geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-446">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="a9c28-447">Diese Änderung behebt ein Problem, bei dem das Suchen von Sonderzeichen mithilfe der Option "Nur ganze Wörter suchen" nicht immer erwartungsgemäß funktioniert hat.</span><span class="sxs-lookup"><span data-stu-id="a9c28-447">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="a9c28-448">Project</span><span class="sxs-lookup"><span data-stu-id="a9c28-448">Project</span></span>

- <span data-ttu-id="a9c28-449">Es wurde ein Problem behoben, bei dem der Benutzer keine zeitgesteuerte Baseline-Arbeit eingeben konnte, wenn die Einstellung zum Schutz der aktuellen Arbeit aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="a9c28-449">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-450">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-450">Word</span></span>

- <span data-ttu-id="a9c28-451">Diese Änderung behebt ein Problem, bei dem wenn der Mauszeiger über einen Hinweis gehalten wurde, dessen Karte nicht hervorgehoben wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-451">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="a9c28-452">Diese Änderung behebt ein Problem, das dazu führte, dass der Text in gruppierten Formen beim Verwenden des Lasso-Auswahltools vorübergehend ausgeblendet wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-452">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="a9c28-453">Diese Änderung behebt ein Problem, bei dem beim Rendern eines Diagramms einer älteren Excel-Version, das als OLE-Objekt in PowerPoint oder Word eingebettet ist, u. U. nicht immer der Diagrammtitel angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-453">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="a9c28-454">Diese Änderung behebt ein Problem in der Zwei-Seiten-Ansicht. Beim Erstellen eines Kommentars wurde der Kommentaranker nicht immer in der Anzeige angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a9c28-454">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="a9c28-455">Ein Problem wurde behoben, bei dem ein Absatz, dessen Formatvorlage ein Vorgänger einer mit einer Liste verknüpften Formatvorlage war, möglicherweise verloren ging.</span><span class="sxs-lookup"><span data-stu-id="a9c28-455">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-march-27"></a><span data-ttu-id="a9c28-457">Version 2004: 27. März</span><span class="sxs-lookup"><span data-stu-id="a9c28-457">Version 2004: March 27</span></span>
<span data-ttu-id="a9c28-458">*Version 2004 (Build 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-458">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a9c28-460">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a9c28-460">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a9c28-461">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-461">Outlook</span></span>

- <span data-ttu-id="a9c28-462">**Neue Option zum Deaktivieren von @Erwähnung-Vorschlägen beim Verfassen von E-Mails:** Findest Sie die @Erwähnung eher lästig als sinnvoll?</span><span class="sxs-lookup"><span data-stu-id="a9c28-462">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="a9c28-463">Wenn Sie das möchten, können Sie diese nun deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="a9c28-463">Now you can turn it off if you prefer.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-466">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-466">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a9c28-467">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-467">Outlook</span></span>
- <span data-ttu-id="a9c28-468">Behebt ein Problem, das bewirkt hat, dass die Schaltfläche "In der Cloud speichern" in den Anlagentools fehlt.</span><span class="sxs-lookup"><span data-stu-id="a9c28-468">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="a9c28-469">Behebt ein Problem, das bewirkt hat, dass Benutzer beim Antworten auf eine verwaltete Nachricht mit digitaler Berechtigung aus einem Inspektor-Fenster keine Signatur hinzufügen können, wenn der Benutzer nicht über die Berechtigung "Besitzer" für die Nachricht verfügt, auf die geantwortet wird.</span><span class="sxs-lookup"><span data-stu-id="a9c28-469">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="a9c28-470">Behebt ein Problem, durch das Benutzer keine weiteren Anlagen von einem Webspeicherort zu einer zuvor erstellten Besprechung hinzufügen können.</span><span class="sxs-lookup"><span data-stu-id="a9c28-470">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-471">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-471">PowerPoint</span></span>
- <span data-ttu-id="a9c28-472">Diese Änderung behebt einen Fehler, der dazu führen kann, dass PowerPoint-Dateien mit Emojis beim Speichern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-472">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="a9c28-473">Project</span><span class="sxs-lookup"><span data-stu-id="a9c28-473">Project</span></span>
- <span data-ttu-id="a9c28-474">Ein Problem wurde behoben, durch das, wenn "CustomFieldValueListGetItem" ausgeführt wird und eine Nachschlagetabelle für das benutzerdefinierte Feld nicht vorhanden ist, eine leere Nachschlagetabelle erstellt wird, auch wenn dies nicht der Fall sein sollte.</span><span class="sxs-lookup"><span data-stu-id="a9c28-474">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-475">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-475">Word</span></span>
- <span data-ttu-id="a9c28-476">Diese Änderung behebt ein Problem, bei dem mehrere Seiten aus dem Menü "Ansicht" ausgewählt werden, in dem der Kommentarbereich als leer angezeigt werden kann.</span><span class="sxs-lookup"><span data-stu-id="a9c28-476">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-march-20"></a><span data-ttu-id="a9c28-478">Version 2004: 20. März</span><span class="sxs-lookup"><span data-stu-id="a9c28-478">Version 2004: March 20</span></span>
<span data-ttu-id="a9c28-479">*Version 2004 (Build 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-479">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a9c28-481">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a9c28-481">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a9c28-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-482">Outlook</span></span>

- <span data-ttu-id="a9c28-483">**Visuelle Aktualisierung des Kalenders:** Letztes Jahr haben wir die E-Mail-Erfahrung visuell aufgefrischt, und dieses Jahr ist der Kalender mit einem Facelifting an der Reihe!</span><span class="sxs-lookup"><span data-stu-id="a9c28-483">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="a9c28-484">Die Aktualisierungen sind frisch, aber vertraut, so dass Sie als erfahrener Outlook-Benutzer sofort einsteigen und produktiver sein können.</span><span class="sxs-lookup"><span data-stu-id="a9c28-484">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="a9c28-485">**Schützen von Daten in einer Gruppe:** Die beim Erstellen einer Gruppe ausgewählte Vertraulichkeitsbezeichnung wird auf Gruppen-E-Mails, Dokumente und Teamwebsites angewendet</span><span class="sxs-lookup"><span data-stu-id="a9c28-485">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-486">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-486">PowerPoint</span></span>

- <span data-ttu-id="a9c28-487">**Aktualisieren von Folien während der Bildschirmpräsentation:** Aktualisieren Sie Folien, die von anderen Autoren während Ihrer Präsentation geändert wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-487">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-490">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-490">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a9c28-491">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-491">Excel</span></span>

- <span data-ttu-id="a9c28-492">Diese Änderung betrifft Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-492">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="a9c28-493">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-493">Outlook</span></span>

- <span data-ttu-id="a9c28-494">Diese Änderung ist gegen Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen gerichtet.</span><span class="sxs-lookup"><span data-stu-id="a9c28-494">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="a9c28-495">Diese Änderung behebt ein Problem, bei dem die neuesten Änderungen an E-Mail-Entwürfen nicht aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-495">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="a9c28-496">Ein Problem wurde behoben, bei dem Sie mit der rechten Maustaste auf eine Datei klicken und "Senden an" nicht funktionieren würde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-496">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="a9c28-497">Es wurde ein Problem behoben, bei dem, wenn ein Benutzer einen angepassten Suchpfad für das Adressbuch hatte, der Namensauflösungsbereich von Outlook auf den angepassten Pfad beschränkt wurde, anstatt die Globale Adressliste (GAL) einzubeziehen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-497">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="a9c28-498">Es wurde ein Problem behoben, bei dem innerhalb eines Satzes von zurückgegebenen Suchergebnissen beim Sortieren der Ergebnisse nach Kategorien die Farben der Kategorien nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-498">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="a9c28-499">Project</span><span class="sxs-lookup"><span data-stu-id="a9c28-499">Project</span></span>

- <span data-ttu-id="a9c28-500">Ein Problem wurde behoben, bei dem das VBA-Ereignis (Visual Basic Applications) "ProjectBeforeTaskChange" nicht ausgelöst wurde, als ein Benutzer auf die Schaltfläche "inaktivieren" geklickt hat, die sich auf dem Menüband "Vorgänge" innerhalb der Planungsgruppierung befindet.</span><span class="sxs-lookup"><span data-stu-id="a9c28-500">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="a9c28-501">Wenn Sie Vorgänger- oder Nachfolgerdetails in einer Ansicht vom Typ „Formular“ festlegen, wurden die Änderungen nicht immer durch das Ereignis „ProjectBeforeTaskChange Visual Basic Applications“ (VBA) erfasst.</span><span class="sxs-lookup"><span data-stu-id="a9c28-501">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="a9c28-502">Wenn Sie beispielsweise eine Abhängigkeit gelöscht und im Formular auf „OK“ geklickt haben, wurde das Ereignis nicht ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="a9c28-502">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="a9c28-503">Dieses Verhalten wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-503">This behavior has been fixed.</span></span>

- <span data-ttu-id="a9c28-504">Es wurde ein Problem behoben, bei dem die neuesten Werte für die tatsächlichen Kosten der geleisteten Arbeit (ACWP) nicht angezeigt wurden, nachdem eine Änderung, z. B. eine Datumsänderung, vorgenommen wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-504">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="a9c28-505">Es wurde ein Problem behoben, bei dem das Öffnen eines Projekts über das Menü "Zuletzt verwendet" (MRU) die Projektdatei mit Lese- bzw. Schreibzugriff öffnete.</span><span class="sxs-lookup"><span data-stu-id="a9c28-505">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="a9c28-506">Diese Änderung behebt das Problem, dass Sie eine manuelle Aufgabe mit einem Startdatum und einer Uhrzeit (aber ohne Dauer) erstellt haben, diese aber mit einer falschen Uhrzeit auf der Zeitachse angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-506">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="a9c28-507">Es wurde ein Problem behoben, bei dem das Drucken einer Zeitleiste mit dem Hijri-Kalender dazu führte, dass ein Monat in der Druckansicht übersprungen oder dupliziert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-507">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="a9c28-508">Diese Änderung richtet sich gegen ein Problem, bei dem die Arbeit im Team Planner mit GDI-Objekten zu einer Überzuweisung von GDI-Objekten und zu geringem Speicherplatz führen konnte.</span><span class="sxs-lookup"><span data-stu-id="a9c28-508">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-509">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-509">Word</span></span>

- <span data-ttu-id="a9c28-510">Es wurde ein Problem behoben, bei dem die Funktion zum Posten von Kommentaren deaktiviert war.</span><span class="sxs-lookup"><span data-stu-id="a9c28-510">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="a9c28-511">Diese Änderung ist gegen Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen gerichtet.</span><span class="sxs-lookup"><span data-stu-id="a9c28-511">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="a9c28-512">Diese Änderung ist gegen ein Problem gerichtet, bei dem der Account Manager keine Nachrichten versendete, was zu einer Unterbrechung bei Anwendungen von Drittanbietern führte.</span><span class="sxs-lookup"><span data-stu-id="a9c28-512">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="a9c28-513">Diese Änderung behebt ein Problem, bei dem das Inhaltsverzeichnis mit Überschriftenformaten aktualisiert wurde, die im Dokument nicht vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="a9c28-513">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="a9c28-514">Es wurde ein Problem behoben, bei dem in Word-Dokumenten gespeicherte digitale Signaturen beim Versand der Dokumente entfernt wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-514">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (BUGDETAILS AM INHALTSENDE NICHT ENTFERNEN)

## <a name="version-2004-march-13"></a><span data-ttu-id="a9c28-516">Version 2004: 13. März</span><span class="sxs-lookup"><span data-stu-id="a9c28-516">Version 2004: March 13</span></span>
<span data-ttu-id="a9c28-517">*Version 2004 (Build 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-517">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a9c28-519">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a9c28-519">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="a9c28-520">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-520">Excel</span></span>
- <span data-ttu-id="a9c28-521">**Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern.</span><span class="sxs-lookup"><span data-stu-id="a9c28-521">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a9c28-522">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a9c28-522">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="a9c28-523">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-523">PowerPoint</span></span>
- <span data-ttu-id="a9c28-524">**Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern.</span><span class="sxs-lookup"><span data-stu-id="a9c28-524">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a9c28-525">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a9c28-525">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="a9c28-526">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-526">Word</span></span>
- <span data-ttu-id="a9c28-527">**Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern.</span><span class="sxs-lookup"><span data-stu-id="a9c28-527">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a9c28-528">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a9c28-528">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-531">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-531">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="a9c28-532">Access</span><span class="sxs-lookup"><span data-stu-id="a9c28-532">Access</span></span>
- <span data-ttu-id="a9c28-533">Ein Problem wurde behoben, bei dem internationale Versionen von Access in der Benutzeroberfläche englische Zeichenfolgen anzeigten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-533">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="a9c28-534">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-534">Excel</span></span>
- <span data-ttu-id="a9c28-535">Es wurde ein Leistungsproblem behoben, das Benutzer beim programmgesteuerten Bearbeiten eines großen Zellbereichs festgestellt haben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-535">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="a9c28-536">Ein Leistungsproblem beim Öffnen von CSV-Dateien in japanischen Umgebungen wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-536">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="a9c28-537">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-537">Outlook</span></span>
- <span data-ttu-id="a9c28-538">Behebt ein Problem, das dazu geführt hat, dass das Datum der letzten Änderung in einer Datei beim Hinzufügen einer Anlage zu einer E-Mail oder beim Speichern einer Anlage aus einer E-Mail durch Ziehen und Ablegen (im Gegensatz zum Hinzufügen oder Speichern über ein Menü) aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-538">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="a9c28-539">Behebt ein Problem, bei dem durch das Drücken der EINGABETASTE im erweiterten Suchbereich keine Suche gestartet wird. Stattdessen müssen Benutzer auf die Schaltfläche "Suchen" klicken.</span><span class="sxs-lookup"><span data-stu-id="a9c28-539">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="a9c28-540">Ein Problem wurde behoben, bei dem die Suche keine Informationen zu Benutzern anzeigt, wenn die Option "Benutzerfotos anzeigen, wenn verfügbar" deaktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="a9c28-540">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="a9c28-541">Project</span><span class="sxs-lookup"><span data-stu-id="a9c28-541">Project</span></span>
- <span data-ttu-id="a9c28-542">Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-542">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="a9c28-543">Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-543">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-544">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-544">Word</span></span>
- <span data-ttu-id="a9c28-545">Ein Problem wurde behoben, bei dem das Eingeben oder Bearbeiten eines Kommentars und Verwenden von STRG+A dazu führte, dass statt nur innerhalb der Kommentarkarte Text im Zeichenbereich markiert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-545">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="a9c28-546">Es wurde ein Problem behoben, bei dem die Ausrichtung von Wörtern in einem Dokument durcheinandergebracht wird, wenn Sie nach dem Drucken mit Schnelldruck versuchen, den Text zu bearbeiten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-546">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="a9c28-547">Es wurde ein Problem beim Zusammenführen von zwei Dokumenten in ein Dokument behoben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-547">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="a9c28-548">Es wurde ein Problem behoben, bei dem das Markieren von Überarbeitungen, die Formeln enthalten, beim Speichern der Datei zu einem Fehler führen konnte.</span><span class="sxs-lookup"><span data-stu-id="a9c28-548">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-06"></a><span data-ttu-id="a9c28-550">Version 2003: 6. März</span><span class="sxs-lookup"><span data-stu-id="a9c28-550">Version 2003: March 06</span></span>
<span data-ttu-id="a9c28-551">*Version 2003 (Build 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-551">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-553">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-553">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a9c28-554">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-554">Outlook</span></span>

- <span data-ttu-id="a9c28-555">Ein Problem wurde behoben, bei dem das Erstellen einer Regel mit Outlook Web App auf dem Exchange-Server nicht beibehalten werden konnte und zu einem Konflikt geführt hat.</span><span class="sxs-lookup"><span data-stu-id="a9c28-555">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="a9c28-556">Wurde ein Problem mit Outlook im dunklen Modus behoben, wird möglicherweise die Dropdownliste im Feld "Von:" nicht angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a9c28-556">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="a9c28-557">Behebt ein Problem, das bewirkt hat, dass Benutzer Dateien nicht über den Datei-Explorer ihrer E-Mail-Nachricht als Anlage hinzufügen konnten, wenn diese Datei in einer anderen Anwendung geöffnet war.</span><span class="sxs-lookup"><span data-stu-id="a9c28-557">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-558">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-558">PowerPoint</span></span>

- <span data-ttu-id="a9c28-559">Ein Problem wurde behoben, bei dem die empfohlenen Miniaturansichten blinkten, wenn Sie mit der Maus auf die Miniaturansichten gingen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-559">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="a9c28-560">In einigen Fällen kann dies dazu führen, dass PowerPoint abstürzt.</span><span class="sxs-lookup"><span data-stu-id="a9c28-560">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-561">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-561">Word</span></span>

- <span data-ttu-id="a9c28-562">Es wurde ein Problem mit der compare-Funktion für Dokumente behoben, die für die Bearbeitung geschützt waren.</span><span class="sxs-lookup"><span data-stu-id="a9c28-562">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a9c28-563">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a9c28-563">Office Suite</span></span>

- <span data-ttu-id="a9c28-564">Behebt ein Problem mit Word/Excel/PowerPoint, bei dem der User-Principal-Name (UPN) nicht mehr die Groß-/Kleinschreibung beachtet, was zu weniger Fehlern beim Arbeiten mit Dateien in SharePoint führt.</span><span class="sxs-lookup"><span data-stu-id="a9c28-564">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="a9c28-565">Behebt ein kosmetisches Problem, bei dem die Schaltfläche "OK" im Dialogfeld „Datei \ Optionen“ abgeblendet angezeigt, die Funktionalität aber nicht beeinträchtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-565">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (BUGDETAILS NICHT AM INHALTSENDE ENTFERNEN)

[//]: # (FEATUREDETAILS CONTENT START NICHT ENTFERNEN)

## <a name="version-2003-february-28"></a><span data-ttu-id="a9c28-568">Version 2003: 28. Februar</span><span class="sxs-lookup"><span data-stu-id="a9c28-568">Version 2003: February 28</span></span>
<span data-ttu-id="a9c28-569">*Version 2003 (Build 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-569">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a9c28-571">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a9c28-571">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a9c28-572">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-572">Outlook</span></span>

- <span data-ttu-id="a9c28-573">**Benachrichtigung Über Vorfall für IT-Administratoren:** Globale Administratoren von Microsoft 365-Mandanten und Administratoren von Office-Apps werden über Outlook und O365 Exchange-Vorfällen benachrichtigt, die sich auf Ihre Benutzer auswirken – mit einer neuen Benachrichtigung im rechten Seitenbereich in Outlook für Windows.</span><span class="sxs-lookup"><span data-stu-id="a9c28-573">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="a9c28-574">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a9c28-574">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a><span data-ttu-id="a9c28-575">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-575">PowerPoint</span></span>

- <span data-ttu-id="a9c28-576">**Verbesserte Freihand-Shape-Diagrammdarstellung:** Zeichnen Sie bessere Diagramme und lassen Sie diese in ein Office-Objekt umwandeln, das Sie bearbeiten können. [Weitere Informationen unter ](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="a9c28-576">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-579">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-579">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a9c28-580">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-580">Excel</span></span>

- <span data-ttu-id="a9c28-581">Ein Problem wurde behoben, bei dem der Text in einem Datenschnitt in der Druckvorschau nicht ordnungsgemäß skaliert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-581">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="a9c28-582">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-582">Outlook</span></span>

- <span data-ttu-id="a9c28-583">Behebt ein Problem, das dazu geführt hat, dass das „Datum der letzten Änderung“ in einer Datei beim Hinzufügen einer Anlage zu einer E-Mail oder beim Speichern einer Anlage aus einer E-Mail durch Ziehen und Ablegen (im Gegensatz zum Hinzufügen oder Speichern über ein Menü) aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-583">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-584">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-584">Word</span></span>

- <span data-ttu-id="a9c28-585">Behebt ein Problem, das dazu geführt hat, dass beim Navigieren über eine Kommentarkarte mit der Tabulatortaste der Fokus auf dem Bearbeitungsfeld für den Kommentar nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-585">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="a9c28-586">Das Einfügen eines Steuerelements (beispielsweise eines Textinhaltssteuerelements) in eine Gleichung und das anschließende Speichern und Öffnen der Datei führte zu einem Fehler aufgrund nicht lesbaren Inhalts.</span><span class="sxs-lookup"><span data-stu-id="a9c28-586">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="a9c28-587">Ein Problem wurde behoben, aufgrund dessen das Speichern einer zuvor kennwortgeschützten Datei in einem Cloudspeicher nicht funktioniert hat.</span><span class="sxs-lookup"><span data-stu-id="a9c28-587">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a9c28-588">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a9c28-588">Office Suite</span></span>

- <span data-ttu-id="a9c28-589">Behebt ein Problem, das dazu geführt hat, dass beim Öffnen mehrerer Dokumente in Word/Excel/PowerPoint aus derselben SharePoint-Bibliothek lediglich das erste geöffnete Dokument auf Richtlinienkonformität gescannt wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-589">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSWENDE)

## <a name="version-2003-february-21"></a><span data-ttu-id="a9c28-591">Version 2003: 21. Februar</span><span class="sxs-lookup"><span data-stu-id="a9c28-591">Version 2003: February 21</span></span>
<span data-ttu-id="a9c28-592">*Version 2003 (Build 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-592">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a9c28-594">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a9c28-594">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="a9c28-595">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a9c28-595">Office Suite</span></span>

- <span data-ttu-id="a9c28-596">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-596">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-599">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-599">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="a9c28-600">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-600">Excel</span></span>
- <span data-ttu-id="a9c28-601">Es wurde ein Problem behoben, das möglicherweise beim Umbenennen von Pivot-Tabellenmaßen aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="a9c28-601">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="a9c28-602">Es wurde ein Leistungsproblem behoben, das möglicherweise bei der Verwendung eines VBA-Makros zum Löschen des Inhalts eines Bereichs aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="a9c28-602">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="a9c28-603">Es wurde ein Problem behoben, das zum Blinken der Benutzeroberfläche führte, wenn Benutzer ein Makro ausführten, das mit dem Menüband interagierte.</span><span class="sxs-lookup"><span data-stu-id="a9c28-603">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="a9c28-604">Es wurde ein Problem behoben, bei dem CSV-Dateien falsch geladen wurden, wenn das erste Wort in der Datei TABLE lautete.</span><span class="sxs-lookup"><span data-stu-id="a9c28-604">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="a9c28-605">Es wurde ein Problem behoben, bei dem es zu Abstürzen kommen konnte, wenn Benutzer zwischen zwei Arbeitsmappen mit unterschiedlichen Zoomstufen wechselten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-605">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="a9c28-606">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-606">Outlook</span></span>
- <span data-ttu-id="a9c28-607">Es wurde ein Problem behoben, das dazu führte, dass Benutzer keine Nachrichten in öffentlichen Ordnern öffnen konnten, wenn Outlook über Nacht laufen gelassen wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-607">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="a9c28-608">Es wurde eine Racebedingung behoben, bei der die Schaltflächen "Zulassen" und "Verweigern" auf der Seite "Berechtigungen" während des Authentifizierungsworkflows beim Hinzufügen eines Google Mail-Kontos deaktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="a9c28-608">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="a9c28-609">Es wurde ein Problem behoben, das dazu führte, dass Outlook in einigen Szenarien unerwartet Protokollausgaben erzeugte, selbst wenn die Protokollierung ausgeschaltet war.</span><span class="sxs-lookup"><span data-stu-id="a9c28-609">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-610">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-610">Word</span></span>
- <span data-ttu-id="a9c28-611">Es wurde ein Problem behoben, bei dem Kommentarkarten nicht immer hervorgehoben werden, wenn der Mauszeiger über die Kommentarkarte bewegt wird.</span><span class="sxs-lookup"><span data-stu-id="a9c28-611">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="a9c28-612">Während einer aktiven Sitzung zur gemeinsamen Dokumenterstellung kann das direkte Hinzufügen eines Bildes in eine Kommentarkarte dazu führen, dass ein Tag hinzugefügt wird.</span><span class="sxs-lookup"><span data-stu-id="a9c28-612">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="a9c28-613">Das Problem wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-613">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a9c28-614">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a9c28-614">Office Suite</span></span>
- <span data-ttu-id="a9c28-615">Beim Verwenden der Metadateneigenschaften MultiChoice/Verweis/Verwaltet mit Word/Excel/PowerPoint-Dokumenten und dem Speichern in einer SharePoint-Dokumentbibliothek waren diese Eigenschaften bisher auf 255 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="a9c28-615">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="a9c28-616">Wenn diese Eigenschaften 255 Zeichen überschritten, konnten solche Dokumente nicht gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-616">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="a9c28-617">Mit dieser Änderung wurde dieser Grenzwert auf 2048 Zeichen erhöht.</span><span class="sxs-lookup"><span data-stu-id="a9c28-617">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-february-14"></a><span data-ttu-id="a9c28-619">Version 2003: 14. Februar</span><span class="sxs-lookup"><span data-stu-id="a9c28-619">Version 2003: February 14</span></span>
<span data-ttu-id="a9c28-620">*Version 2003 (Build 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-620">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a9c28-622">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a9c28-622">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a9c28-623">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-623">Outlook</span></span>

- <span data-ttu-id="a9c28-624">**Neue Benutzeroberfläche für WLAN-Netzwerke mit Anmeldung:** Sind Sie schon einmal einem WLAN-Netzwerk beigetreten, mit dem Sie sich anmelden mussten?</span><span class="sxs-lookup"><span data-stu-id="a9c28-624">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="a9c28-625">Outlook erkennt dies jetzt und hilft Ihnen, eine Verbindung zu herstellen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-625">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-626">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-626">Word</span></span>

- <span data-ttu-id="a9c28-627">**Freihand-Editor in der Toolbox der Zeichentools finden:** Wählen Sie "Zeichnen" und dann den Freihand-Editor-Stift aus, um Ihr Dokument mit dem Finger oder einem digitalen Stift zu bearbeiten.</span><span class="sxs-lookup"><span data-stu-id="a9c28-627">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="a9c28-628">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a9c28-628">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="a9c28-629">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a9c28-629">Office Suite</span></span>

- <span data-ttu-id="a9c28-630">**Übersichtlichere Statusleistensymbole:** Statusleistensymbole sind jetzt einfacher zu sehen.</span><span class="sxs-lookup"><span data-stu-id="a9c28-630">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-633">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-633">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a9c28-634">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-634">Outlook</span></span>

- <span data-ttu-id="a9c28-635">Ein Problem wurde behoben, durch das Benutzer den Zugriff auf das Dialogfeld "Frei/Gebucht-Optionen" der Kalenderberechtigungen verloren.</span><span class="sxs-lookup"><span data-stu-id="a9c28-635">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="a9c28-636">Es wurde ein Problem behoben, das zur Warnung "Leider besteht ein Problem beim Öffnen dieses Elements" führen kann, wenn Sie bestimmte Besprechungsserien-Instanzen öffnen, die aus einer anderen Zeitzone gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-636">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="a9c28-637">Es wurde ein Problem behoben, durch das Benutzer eine MSG-Datei möglicherweise nicht mehr öffnen können, nachdem die eine Anlage aus dieser Nachricht durch Ziehen und Ablegen verschoben haben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-637">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="a9c28-638">Ein Problem wurde behoben, bei dem der Dateiname nach dem Hochladen einer Dateianlage aus Outlook nach OneDrive möglicherweise geändert wird, wenn der Name der Anlage eine Klammer enthält.</span><span class="sxs-lookup"><span data-stu-id="a9c28-638">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-639">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-639">PowerPoint</span></span>

- <span data-ttu-id="a9c28-640">Es wurde ein Problem behoben, das dazu führen kann, dass ein Dokument, das ein Excel-Diagramm enthält, nicht in PowerPoint oder Word gespeichert werden kann.</span><span class="sxs-lookup"><span data-stu-id="a9c28-640">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-641">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-641">Word</span></span>

- <span data-ttu-id="a9c28-642">Ein Problem wurde behoben, bei dem Bilder in Dokumenten beim Export in eine PDF-Datei transparent sind.</span><span class="sxs-lookup"><span data-stu-id="a9c28-642">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-february-07"></a><span data-ttu-id="a9c28-644">Version 2002: 07. Februar</span><span class="sxs-lookup"><span data-stu-id="a9c28-644">Version 2002: February 07</span></span>
<span data-ttu-id="a9c28-645">*Version 2002 (Build 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="a9c28-645">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a9c28-647">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a9c28-647">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a9c28-648">Zugriff</span><span class="sxs-lookup"><span data-stu-id="a9c28-648">Access</span></span>

- <span data-ttu-id="a9c28-649">**Seien Sie beim Arbeiten im Abfrage-Designer, in der SQL-Ansicht und im Fenster „Beziehungen“ produktiver:** Klicken Sie zum Öffnen, Gestalten, Vergrößern oder Verkleinern und Ausblenden mit der rechten Maustaste auf die betreffende Tabelle.</span><span class="sxs-lookup"><span data-stu-id="a9c28-649">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="a9c28-650">Suchen und Ersetzen von Text in der SQL-Ansicht.</span><span class="sxs-lookup"><span data-stu-id="a9c28-650">Search and replace text in SQL View.</span></span> <span data-ttu-id="a9c28-651">Auswählen mehrerer Tabellen im Fenster „Beziehungen“.</span><span class="sxs-lookup"><span data-stu-id="a9c28-651">Select multiple tables in the Relationships window.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a9c28-654">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a9c28-654">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a9c28-655">Access</span><span class="sxs-lookup"><span data-stu-id="a9c28-655">Access</span></span>

- <span data-ttu-id="a9c28-656">Dieses Update behebt ein Problem bei der Verwendung von ADODB.</span><span class="sxs-lookup"><span data-stu-id="a9c28-656">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="a9c28-657">Das Recorder-Objekt im VB-Code meldet möglicherweise einen Fehler falsch.</span><span class="sxs-lookup"><span data-stu-id="a9c28-657">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="a9c28-658">Dieses Update behebt ein Problem, das dazu führen kann, dass Microsoft Access eine Identitätsspalte in einer verknüpften SQL-Server-Tabelle nicht identifiziert, was dazu führen kann, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-658">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="a9c28-659">Excel</span><span class="sxs-lookup"><span data-stu-id="a9c28-659">Excel</span></span>

- <span data-ttu-id="a9c28-660">Ein Problem wurde behoben, das dazu geführt hatte, dass Excel bei Verschieben von Text in Spalten mit dynamischen Pfeilern abgestürzt ist.</span><span class="sxs-lookup"><span data-stu-id="a9c28-660">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="a9c28-661">Outlook</span><span class="sxs-lookup"><span data-stu-id="a9c28-661">Outlook</span></span>

- <span data-ttu-id="a9c28-662">Ein Problem wurde behoben, das dazu geführt hatte, dass beim Durchblättern des Kalanders in der Monatsansicht die vorangegangenen Kalenderereignisse nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-662">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="a9c28-663">Behebt ein Problem, das dazu geführt hat, dass Benutzer beim Anzeigen von mehr als 30 Kalendern in einer Citrix-Umgebung einen Absturz erlebt haben.</span><span class="sxs-lookup"><span data-stu-id="a9c28-663">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a9c28-664">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a9c28-664">PowerPoint</span></span>

- <span data-ttu-id="a9c28-665">Ein Problem wurde behoben, das dazu geführt hatte, dass PowerPoint nach dem Schließen einer Datei diese nicht sofort aus der Sammlung von Präsentationen entfernt hat, sofern Ereignisverarbeiter (event handlers) ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-665">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="a9c28-666">Dadurch war die Zahl der vom Objektmodell gemeldeten, geöffneten Präsentationen falsch und das Herunterfahren von PowerPoint wurde verhindert.</span><span class="sxs-lookup"><span data-stu-id="a9c28-666">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="a9c28-667">Ein Problem mit dem Textmarker wurde behoben: Weißer Text mit dunkleren Textmarkerfarben wurde Schwarz mit Graustufen gedruckt.</span><span class="sxs-lookup"><span data-stu-id="a9c28-667">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="a9c28-668">Word</span><span class="sxs-lookup"><span data-stu-id="a9c28-668">Word</span></span>

- <span data-ttu-id="a9c28-669">Beim Aktualisieren eines Inhaltsverzeichnisses bzw. dem Blättern durch dieses wird manchmal möglicherweise ein grauer Bereich auf dem Dokument angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a9c28-669">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="a9c28-670">Ein Problem wurde behoben, bei dem die Entwurfsversion eines Stammkommentars bei der gemeinsamen Dokumenterstellung zeitweise nicht beibehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-670">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="a9c28-671">Ein Problem wurde behoben, das dazu geführt hatte, dass beim Hin- und Herwechseln zwischen Kommentar-Karten manchmal der anfänglich ausgewählte Kommentar mit einer Auswahlhervorhebung angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-671">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="a9c28-672">Es wurde ein Problem mit der Verwendung von „Durchsuchen“ zum Speichern einer Datei behoben, das nicht funktioniert hat, wenn ein Kommentar geschrieben, jedoch nicht gepostet worden war und der Benutzer versucht hatte, die Datei zu speichern.</span><span class="sxs-lookup"><span data-stu-id="a9c28-672">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="a9c28-673">Wenn „SlideTrack“ aktiviert und der Bereich „Kommentare“ geschlossen ist, kann der Bereich „Kommentare“ mit STRG+ALT+M möglicherweise nicht geöffnet werden.</span><span class="sxs-lookup"><span data-stu-id="a9c28-673">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="a9c28-674">Es wurde ein Problem behoben, das dazu geführt hatte, dass beim Hinzufügen von @mention in einer Tabelle die Fehlermeldung „Eine Tabelle in diesem Dokument ist beschädigt“ generiert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-674">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a9c28-675">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a9c28-675">Office Suite</span></span>

- <span data-ttu-id="a9c28-676">Behebt ein Problem, das dazu geführt hat, dass Korrekturhilfe-Paket Norwegen Nynorsk (nn-no) nicht ordnungsgemäß installiert wurde.</span><span class="sxs-lookup"><span data-stu-id="a9c28-676">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

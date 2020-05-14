---
title: Versionshinweise für Releases im halbjährlichen Kanal (gezielt) im Jahr 2020
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt IT-Experten Anmerkungen zur Version für Releases im halbjährlichen Kanal (gezielt) für Microsoft 365 Apps im Jahr 2020 zur Verfügung.
ms.openlocfilehash: 8cf9ae0e43417941ec588ff3c45835d7d613488a
ms.sourcegitcommit: 1c78e7def81461cd758dded4b443b5dcffa17461
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 05/12/2020
ms.locfileid: "44211230"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2020"></a><span data-ttu-id="55309-103">Versionshinweise für Releases im halbjährlichen Kanal (gezielt) im Jahr 2020</span><span class="sxs-lookup"><span data-stu-id="55309-103">Release notes for Semi-Annual Channel (Targeted) releases in 2020</span></span>

<span data-ttu-id="55309-104">Diese Versionshinweise enthalten Informationen zu neuen Features und nicht sicherheitsrelevanten Updates, die in halbjährlichen Kanal-Updates (gezielt) im Jahr 2020 für Microsoft 365 Apps for Enterprise, Microsoft 365 Apps for Business sowie in den Abonnementversionen der Desktop-Apps für Project und Visio enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="55309-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Channel (Targeted) updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="55309-105">Wir nehmen einige Änderungen an den Updatekanälen für Microsoft 365-Apps vor. Unter anderem fügen wir einen neuen Updatekanal hinzu (Monatlicher Enterprise-Kanal) und ändern die Namen der vorhandenen Updatekanäle.</span><span class="sxs-lookup"><span data-stu-id="55309-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="55309-106">Um mehr zu erfahren, [lesen Sie diesen Artikel](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="55309-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>


## <a name="version-2002-may-12"></a><span data-ttu-id="55309-107">Version 2002: 12. Mai</span><span class="sxs-lookup"><span data-stu-id="55309-107">Version 2002: May 12</span></span>
<span data-ttu-id="55309-108">*Version 2002 (Build 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="55309-108">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="55309-109">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="55309-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="55309-111">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="55309-111">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="55309-112">Excel</span><span class="sxs-lookup"><span data-stu-id="55309-112">Excel</span></span>

- <span data-ttu-id="55309-113">Das Öffnen einer Arbeitsmappe mit Verweisen auf zahlreiche andere Arbeitsmappen, insbesondere mit versteckten Fenstern, würde langsamer als erwartet ablaufen.</span><span class="sxs-lookup"><span data-stu-id="55309-113">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="55309-114">Das Öffnen von CSV-Dateien dauerte unter bestimmten Umständen länger als erwartet.</span><span class="sxs-lookup"><span data-stu-id="55309-114">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="55309-115">Excel stürzt möglicherweise unter bestimmten Umständen ab, wenn zwischen den Arbeitsmappen mit anderen Zoomstufen gewechselt wird.</span><span class="sxs-lookup"><span data-stu-id="55309-115">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="55309-116">Es wurde ein Problem mit VBA behoben, bei dem das Schreiben von Werten in einem Wertebereich langsamer als erwartet war.</span><span class="sxs-lookup"><span data-stu-id="55309-116">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="55309-117">Daten, die aus einer nach Farbe gefilterten Spalte kopiert wurden, werden manchmal nicht ordnungsgemäß eingefügt.</span><span class="sxs-lookup"><span data-stu-id="55309-117">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="55309-118">Ein Problem wurde behoben, bei dem Excel in manchen Fällen abstürzte, nachdem ein Blatt mit einer PivotTable kopiert wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-118">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="55309-119">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-119">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="55309-120">Es wurde ein Problem behoben, bei dem die Eigenschaft "Wert wird überschneidet bei" auf der Diagrammachse unerwartet geändert wird, wenn Sie eine Datei speichern und erneut öffnen.</span><span class="sxs-lookup"><span data-stu-id="55309-120">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="55309-121">Die Verwendung von Range.Value und Range.Value2 (VBA) würde dazu führen, dass Formeln als dynamische Arrays eingegeben werden.</span><span class="sxs-lookup"><span data-stu-id="55309-121">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="55309-122">OneNote</span><span class="sxs-lookup"><span data-stu-id="55309-122">OneNote</span></span>

- <span data-ttu-id="55309-123">Lokalisiert die Benachrichtigung, durch die der Benutzer mehr über temporäre Maßnahmen erfahren kann, die in der OneNote-Benutzeroberfläche implementiert sind, um die Synchronisierungs- und Dienststabilität zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="55309-123">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="55309-124">Zeigt eine Benachrichtigung an, durch die der Benutzer mehr über temporäre Maßnahmen erfahren kann, die in der OneNote-Benutzeroberfläche implementiert sind, um die Synchronisierungs- und Dienststabilität zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="55309-124">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="55309-125">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehendes verringern der Anzahl und Häufigkeit der Synchronisierungen von Seiten des Versionsverlaufs in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="55309-125">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="55309-126">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehende Deaktivierung des Papierkorbs in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="55309-126">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="55309-127">Wenn ein Benutzer versucht, die Daten zu löschen, die normalerweise in den Papierkorb verschoben werden, wird der Benutzer gefragt, ob er die Daten beibehalten oder dauerhaft löschen möchte.</span><span class="sxs-lookup"><span data-stu-id="55309-127">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="55309-128">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehende Anpassung der Synchronisierungshäufigkeit in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="55309-128">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="55309-129">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehendes zurückschieben des Downloads eingebetteter Dateien und Bilder in Online-Notizbücher, bis der Benutzer zu der Seite in OneNote 2016 navigiert.</span><span class="sxs-lookup"><span data-stu-id="55309-129">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="55309-130">Verbesserte Synchronisierungs- und Servicestabilität durch vorübergehende Deaktivierung der Videoaufzeichnung in der Anwendung in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="55309-130">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="55309-131">Lokale Notizbücher sind von dieser Maßnahme nicht betroffen.</span><span class="sxs-lookup"><span data-stu-id="55309-131">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="55309-132">Verbesserte Synchronisierungs- und Servicestabilität durch vorübergehende Reduzierung der maximal zulässigen Größe neuer eingebetteter Anhänge auf 50 MB in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="55309-132">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="55309-133">Bei Dateien, die dieses Limit überschreiten, haben Benutzer die Möglichkeit, die Datei auf OneDrive hochzuladen und einen Link in OneNote einzufügen.</span><span class="sxs-lookup"><span data-stu-id="55309-133">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="55309-134">Outlook</span><span class="sxs-lookup"><span data-stu-id="55309-134">Outlook</span></span>

- <span data-ttu-id="55309-135">Ein Problem wurde behoben, bei dem die Breite des Ordnerbereichs unerwartet geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-135">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="55309-136">Es wurde ein Problem behoben, das bewirkt, dass Benutzer beim Öffnen von .msg- und .oft-Dateien nach einem Windows-Update einen Absturz erfahren.</span><span class="sxs-lookup"><span data-stu-id="55309-136">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="55309-137">Behebt ein Problem, das dazu führte, dass Benutzer beim Weiterleiten großer HTML-Nachrichten den Nachrichtentext abgeschnitten sahen.</span><span class="sxs-lookup"><span data-stu-id="55309-137">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="55309-138">Dieses Update behebt ein Problem, bei dem Microsoft Outlook beim Anzeigen oder Verfassen von Nachrichten nicht die aktuelle Vertraulichkeitskennzeichnung anzeigt.</span><span class="sxs-lookup"><span data-stu-id="55309-138">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="55309-139">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="55309-139">PowerPoint</span></span>

- <span data-ttu-id="55309-140">Es wurde ein Problem mit der Weiterleitung von korrekten Nachrichten für Benutzer behoben, die eine Kopie einer Datei mit verbesserten Kommentaren öffnen.</span><span class="sxs-lookup"><span data-stu-id="55309-140">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="55309-141">Word</span><span class="sxs-lookup"><span data-stu-id="55309-141">Word</span></span>

- <span data-ttu-id="55309-142">Es wurde ein Problem behoben, bei dem Access und Publisher nicht ordnungsgemäß gestartet werden, je nachdem, welche Sprachen installiert wurden.</span><span class="sxs-lookup"><span data-stu-id="55309-142">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="55309-143">Es wurde ein Problem mit der compare-Funktion für Dokumente behoben, die für die Bearbeitung geschützt waren.</span><span class="sxs-lookup"><span data-stu-id="55309-143">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="55309-144">Es wurde ein Problem beim Zusammenführen von 2 Dokumenten in ein Dokument behoben.</span><span class="sxs-lookup"><span data-stu-id="55309-144">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="55309-145">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="55309-145">Office Suite</span></span>

- <span data-ttu-id="55309-146">Diese Behebung soll sicherstellen, dass die Projektanwendung das Netzwerk nicht blockiert, wenn die Datei im Cache des Clients gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="55309-146">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="55309-147">Das Problem wurde behoben, bei dem ein interner Vorgang bei einem Fehler eine Ausnahme ausgelöst hat, anstatt diesen zu protokollieren und fortzufahren.</span><span class="sxs-lookup"><span data-stu-id="55309-147">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="55309-148">Die betroffenen Benutzer werden nicht mehr daran gehindert, Updates zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="55309-148">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="55309-149">Dadurch wird sichergestellt, dass skizzierte Konturen im Menüband ordnungsgemäß funktionieren.</span><span class="sxs-lookup"><span data-stu-id="55309-149">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="55309-150">Es wurde ein Problem beim Öffnen von Dateien von lokalen Standorten aus mit einigen bestimmten Proxykonfigurationen behoben.</span><span class="sxs-lookup"><span data-stu-id="55309-150">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="55309-151">Dieses Update behebt ein Problem in Visual Basic for Applications in Microsoft Office, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung beim Laden als fehlerhaft angesehen werden.</span><span class="sxs-lookup"><span data-stu-id="55309-151">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="55309-152">Das Update behebt ein Problem in Microsoft Office, bei dem Visual Basic for Applications-Projekte mit Referenzen, die bei der Suche nach in der PATH-Umgebungsvariable angegebenen Speicherorten gefunden werden sollen, zur Laufzeit möglicherweise nicht richtig gefunden werden, was zu VBA-Laufzeitfehlern führt.</span><span class="sxs-lookup"><span data-stu-id="55309-152">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="55309-153">Dieses Update behebt ein Problem in Microsoft Word, bei dem Text, der länger als 255 Zeichen ist, während die Anwendung einer Vertraulichkeitskennzeichnung eingefügt wird, später nicht identifiziert und entfernt werden konnte, wenn die Kennzeichnungsrichtlinie eine Kopf- oder Fußzeile oder ein Wasserzeichen angewendet hat.</span><span class="sxs-lookup"><span data-stu-id="55309-153">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="55309-154">Es wurde ein Problem behoben, durch das Abstürze während der Office-Übergabesitzungen eliminiert, und es wurde die Zuverlässigkeit der Benutzeroberfläche erhöht.</span><span class="sxs-lookup"><span data-stu-id="55309-154">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="55309-155">Dieser Fehler aktualisiert den Enhanced Configuration Service (ECS).</span><span class="sxs-lookup"><span data-stu-id="55309-155">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="55309-156">Das Aufrufen von diesem neueren Endpunkt aus hat eine höhere Erfolgsrate für den Abruf aus ECS.</span><span class="sxs-lookup"><span data-stu-id="55309-156">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-april-14"></a><span data-ttu-id="55309-158">Version 2002: 14. April</span><span class="sxs-lookup"><span data-stu-id="55309-158">Version 2002: April 14</span></span>
<span data-ttu-id="55309-159">*Version 2002 (Build 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="55309-159">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="55309-160">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="55309-160">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="55309-161">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="55309-161">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="55309-162">Excel</span><span class="sxs-lookup"><span data-stu-id="55309-162">Excel</span></span>

- <span data-ttu-id="55309-163">**Geben Sie eine Formel ein, die mehrere Werte zurückgibt:** Geben Sie schnell eine Formel ein, die mehrere Werte zurückgibt, und diese werden automatisch in die benachbarten Zellen übertragen.</span><span class="sxs-lookup"><span data-stu-id="55309-163">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="55309-164">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-164">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="55309-165">**Sechs leistungsfähige Funktionen:** Wir haben sechs neue Funktionen hinzugefügt, um Ihre Tabellenkalkulationen hochgradig zu optimieren: FILTERN, SORTIEREN, SORTIERENNACH, EINDEUTIG, SEQUENZ und ZUFALLSMATRIX.</span><span class="sxs-lookup"><span data-stu-id="55309-165">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="55309-166">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-166">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="55309-167">**Schau nach links, schau nach rechts... XVERWEIS ist da!:** Finden Sie mit XVERWEIS Zeile für Zeile alles, was Sie in einer Tabelle oder einem Bereich benötigen.</span><span class="sxs-lookup"><span data-stu-id="55309-167">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  [<span data-ttu-id="55309-168">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-168">Learn more</span></span>](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="55309-170">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="55309-170">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="55309-171">Excel</span><span class="sxs-lookup"><span data-stu-id="55309-171">Excel</span></span>

- <span data-ttu-id="55309-172">Excel stürzt in bestimmten Fällen ab, wenn eine in Word oder PowerPoint eingebettete Arbeitsmappe erneut geöffnet wird.</span><span class="sxs-lookup"><span data-stu-id="55309-172">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="55309-173">Beim Speichern als CSV-Datei hat Excel in einigen Fällen alle Spalten in einer einzigen Spalte zusammengeführt.</span><span class="sxs-lookup"><span data-stu-id="55309-173">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="55309-174">Die Verwendung von Range.ClearContents für einen Bereich auf einem geschützten Blatt hat möglicherweise länger gedauert als erwartet.</span><span class="sxs-lookup"><span data-stu-id="55309-174">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="55309-175">Es wurde ein Problem beim Skalieren von Text in Steuerelementen von Formularen beim Anzeigen in der Druckansicht behoben.</span><span class="sxs-lookup"><span data-stu-id="55309-175">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="55309-176">VBA-Makros, die mit dem Menüband interagieren, können möglicherweise mit ScreenUpdating unerwartet auf „Wahr“ festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="55309-176">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="55309-177">Es wurde ein Problem behoben, bei dem externe Links beim Füllen(abwärts füllen, übergreifend füllen usw.) nicht aktualisiert wurden, wenn das Quellbuch geschlossen war.</span><span class="sxs-lookup"><span data-stu-id="55309-177">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="55309-178">Die Verwendung des VBA-Befehls Application.Evaluate funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.</span><span class="sxs-lookup"><span data-stu-id="55309-178">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="55309-179">Es wurde ein Leistungsproblem beim Erstellen von Diagrammen aus Vorlagen behoben.</span><span class="sxs-lookup"><span data-stu-id="55309-179">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="55309-180">Outlook</span><span class="sxs-lookup"><span data-stu-id="55309-180">Outlook</span></span>

- <span data-ttu-id="55309-181">Es wurde ein Problem behoben, das dazu führte, dass die Kopfzeile einer Gruppe in einigen Szenarios unerwartet erweitert wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-181">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="55309-182">Es wurde ein Problem behoben, bei dem es zu einem Absturz kam, wenn Benutzer bestimmte Ergebnisse ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="55309-182">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="55309-183">Es wurde ein Problem behoben, das gelegentlich zu einem Absturz führte, wenn Benutzer den X-Knopf ihrer Maus verwendeten.</span><span class="sxs-lookup"><span data-stu-id="55309-183">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="55309-184">Es wurde ein Problem behoben, das bewirkt hat, dass die Schaltfläche „In der Cloud speichern“ in den Tools für Anlagen fehlte.</span><span class="sxs-lookup"><span data-stu-id="55309-184">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="55309-185">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="55309-185">PowerPoint</span></span>

- <span data-ttu-id="55309-186">Verbessertes Szenario zum Kopieren und Einfügen: Das Kopieren der Form in eine PowerPoint-Folie und das Einfügen in eine andere Folie in einer Schleife schlägt möglicherweise mit Ausnahme fehl.</span><span class="sxs-lookup"><span data-stu-id="55309-186">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="55309-187">Project</span><span class="sxs-lookup"><span data-stu-id="55309-187">Project</span></span>

- <span data-ttu-id="55309-188">Ein Problem wurde behoben, bei dem Project beim Speichern von Projekten, die mit älteren Project-Versionen erstellt wurden, möglicherweise abstürzt.</span><span class="sxs-lookup"><span data-stu-id="55309-188">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="55309-189">Ein Problem wurde behoben, bei dem das Ereignis „ProjectBeforeTaskChange“ nichts erkennt, wenn ein Vorgang über die Schaltfläche „Deaktivieren“ deaktiviert/aktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-189">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="55309-190">Word</span><span class="sxs-lookup"><span data-stu-id="55309-190">Word</span></span>

- <span data-ttu-id="55309-191">Es wurde ein Problem behoben, das gelegentlich zu einem Absturz führte, wenn Benutzer den X-Knopf ihrer Maus verwendeten.</span><span class="sxs-lookup"><span data-stu-id="55309-191">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="55309-192">Es wurde ein Problem mit der Anpassung von Text in einer Tabelle behoben.</span><span class="sxs-lookup"><span data-stu-id="55309-192">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="55309-193">Ein Problem wurde behoben, damit eingefügte horizontale Linien nicht kürzer und zentriert sind.</span><span class="sxs-lookup"><span data-stu-id="55309-193">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-march-10"></a><span data-ttu-id="55309-195">Version 2002: 10. März</span><span class="sxs-lookup"><span data-stu-id="55309-195">Version 2002: March 10</span></span>
<span data-ttu-id="55309-196">*Version 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="55309-196">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="55309-197">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="55309-197">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="55309-199">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="55309-199">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="55309-200">Access</span><span class="sxs-lookup"><span data-stu-id="55309-200">Access</span></span>

- <span data-ttu-id="55309-201">**Schnelle Suche nach verknüpften Tabellen:** Unser neues Suchfeld macht die Suche nach verknüpften Tabellen zu einem Kinderspiel.</span><span class="sxs-lookup"><span data-stu-id="55309-201">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="55309-202">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-202">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="55309-203">Excel</span><span class="sxs-lookup"><span data-stu-id="55309-203">Excel</span></span>

- <span data-ttu-id="55309-204">**Mit \@Erwähnen andere auf sich aufmerksam machen:** Mithilfe von Erwähnungen in Kommentaren können Sie Kollegen informieren, wenn Sie deren Input benötigen.</span><span class="sxs-lookup"><span data-stu-id="55309-204">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="55309-205">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-205">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="55309-206">**Finden Sie, wonach Sie suchen:** Suchen Sie Befehle, Personen, Dateien, Fotos, Webartikel und mehr.</span><span class="sxs-lookup"><span data-stu-id="55309-206">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="55309-207">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-207">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="55309-208">**Zeichnen Sie es auf:** Verleihen Sie Office-Shapes in Ihrer Arbeitsmappe ein ungezwungenes, von Hand gezeichnetes Aussehen.</span><span class="sxs-lookup"><span data-stu-id="55309-208">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="55309-209">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-209">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="55309-210">**Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="55309-210">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="55309-211">**Keine Umleitung zum Browser mehr:** Sie legen fest, wie Links zu Office-Dokumenten geöffnet werden: im Browser oder in der App.</span><span class="sxs-lookup"><span data-stu-id="55309-211">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="55309-212">**Konzentrieren Sie sich darauf, was noch erledigt werden muss:** Wählen Sie "Auflösen" aus, um Kommentare zu reduzieren und offene Punkte hervorzuheben.</span><span class="sxs-lookup"><span data-stu-id="55309-212">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="55309-213">**Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten.</span><span class="sxs-lookup"><span data-stu-id="55309-213">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="55309-214">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-214">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="55309-215">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="55309-215">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="55309-216">\*\*Add-In „Datenschnellansicht“: \*\* erstellen Sie schnell Visio-Flussdiagramme aus Excel.</span><span class="sxs-lookup"><span data-stu-id="55309-216">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="55309-217">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-217">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="55309-218">**Schnell lesen und antworten:** Antworten Sie auf Kommentare und Erwähnungen direkt aus dem E-Mail-Bereich, ohne die Arbeitsmappe zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="55309-218">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="55309-219">**Statistiken für Ihre Arbeitsmappe abrufen:** Arbeitsmappenstatistiken bieten einen Überblick über den Inhalt einer Arbeitsmappe, um Ihnen das Erkunden des Inhalts zu erleichtern.</span><span class="sxs-lookup"><span data-stu-id="55309-219">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="55309-220">**Speichern von Shapes als Bildern:** mit nur wenigen Mausklicks können Sie eine Form, ein Symbol oder ein anderes Objekt als Bilddatei speichern, um Sie an anderer Stelle wiederzuverwenden.</span><span class="sxs-lookup"><span data-stu-id="55309-220">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="55309-221">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-221">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)



### <a name="outlook"></a><span data-ttu-id="55309-222">Outlook</span><span class="sxs-lookup"><span data-stu-id="55309-222">Outlook</span></span>



- <span data-ttu-id="55309-223">**Verbinden Ihres LinkedIn-Netzwerks mit Outlook:** Stellen Sie eine sichere Verbindung zwischen Ihrem LinkedIn-Konto und Ihrem Microsoft-Konto her, um Informationen aus LinkedIn-Profilen direkt auf der Karte mit Ihren Kontakten anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="55309-223">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="55309-224">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-224">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="55309-p118">**Alle Verschlüsselungsoptionen an einem zentralen Ort:** Gehen Sie einfach zu Optionen > Verschlüsseln, um auszuwählen, wie Ihre E-Mail-Nachricht gesichert wird. [Weitere Informationen](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="55309-p118">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="55309-227">**Das Menü „Link einfügen“ in Outlook fügt einen Link mit der vom Mandantenadministrator festgelegten Berechtigung ein:** Ein Link aus dem Link-Einfügen-MRU in Outlook fügte einen Link ein, der nur für diejenigen Benutzer funktionierte, die bereits eine Berechtigung besaßen.</span><span class="sxs-lookup"><span data-stu-id="55309-227">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="55309-228">Dies führte häufig zu E-Mail-Nachrichten zwischen Benutzern, die den Zugriff auf ein Dokument anforderten.</span><span class="sxs-lookup"><span data-stu-id="55309-228">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="55309-229">Wir haben diese Erfahrung aktualisiert, sodass der Link jetzt mit der vom Mandantenadministrator festgelegten Standardberechtigung eingefügt wird. Für MSIT ist dies "Organisation kann bearbeiten", sodass alle internen Benutzer, die einen auf diese Weise freigegebenen Link erhalten, darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="55309-229">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="55309-230">**Suchen bei Rechtschreibschwierigkeiten oder mit Tippfehlern:** Outlook wird auch dann finden, was Sie suchen, wenn Sie sich verschreiben.</span><span class="sxs-lookup"><span data-stu-id="55309-230">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="55309-231">**Phishing-E-Mails sind jetzt leicht zu erkennen:** Spam- und Phishing-E-Mails haben ein anderes Aussehen und Verhalten, sodass Sie sie leichter identifizieren und aus Ihrem Posteingang entfernen können.</span><span class="sxs-lookup"><span data-stu-id="55309-231">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="55309-232">**Erweiterter Schutz gegen Angriffe:** Mit Office 365 Advanced Threat Protection sind Sie vor Angriffen durch Links in E-Mail-Betreffzeilen, angefügten Nachrichten, signierten Nachrichten, Netzwerkpfaden usw. geschützt.</span><span class="sxs-lookup"><span data-stu-id="55309-232">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="55309-233">**Müheloses Zeichnen und Signieren:** Kritzeln Sie über die Bilder, oder fügen Sie einen Zeichenbereich hinzu, um Ihren Gedanken als Freihandnotizen Ausdruck zu verleihen.</span><span class="sxs-lookup"><span data-stu-id="55309-233">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="55309-234">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-234">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="55309-235">**Finden Sie relevante Nachrichten in Ihren Suchergebnissen:** Outlook analysiert Suchbegriffe und zeigt die wichtigsten E-Mail-Nachrichten am Anfang der Suchergebnisse an.</span><span class="sxs-lookup"><span data-stu-id="55309-235">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="55309-236">Außerdem sehen Sie alle Ergebnisse sortiert nach Datum im Abschnitt „Top-Ergebnisse“.</span><span class="sxs-lookup"><span data-stu-id="55309-236">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="55309-237">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-237">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="55309-238">**Erhalten Sie Ortsvorschläge:** Beginnen Sie beim Planen von Terminen und Besprechungen mit der Eingabe im Feld „Ort“, so schlägt Outlook Räume, Adressen und andere zuletzt verwendete Orte vor.</span><span class="sxs-lookup"><span data-stu-id="55309-238">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="55309-239">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-239">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="55309-240">**Mehr Nachrichten am Bildschirm anzeigen:** Wählen Sie "Anzeigen" > Engere Abstände verwenden, um die Abstände zwischen den Nachrichten anzupassen.</span><span class="sxs-lookup"><span data-stu-id="55309-240">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="55309-241">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-241">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="55309-242">**Sehen Sie Ihre Nachrichten in einem neuen Licht:** Verwenden Sie die Sonne/Mond-Schaltfläche, um im Lesebereich zwischen hellem und dunklem Hintergrund zu wechseln.</span><span class="sxs-lookup"><span data-stu-id="55309-242">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="55309-243">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-243">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)



### <a name="powerpoint"></a><span data-ttu-id="55309-244">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="55309-244">PowerPoint</span></span>

- <span data-ttu-id="55309-245">**Schnelle Zusammenarbeit in Echtzeit in PowerPoint:** Schnelle Zusammenarbeit in Echtzeit in PowerPoint</span><span class="sxs-lookup"><span data-stu-id="55309-245">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="55309-246">**Neue Tools zum Korrekturlesen:** Machen Sie sich keine Sorgen mehr über Ihre Texte.</span><span class="sxs-lookup"><span data-stu-id="55309-246">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="55309-247">PowerPoint bietet jetzt Grammatik- und Textvorschläge.</span><span class="sxs-lookup"><span data-stu-id="55309-247">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="55309-248">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-248">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)


- <span data-ttu-id="55309-249">**Live-Beschriftungen und -Untertitel:** die Worte des Referenten werden automatisch als Beschriftungen oder Untertitel in der von Ihnen gewünschten Sprache auf dem Bildschirm angezeigt.</span><span class="sxs-lookup"><span data-stu-id="55309-249">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="55309-250">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-250">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="55309-p127">**Sie berechnen, wir formatieren:** Von Hand gezeichnete mathematische Ausdrücke werden in Standardzeichen umgewandelt. Wählen Sie einfach "Freihand in Gleichung" und Ihre handschriftlichen Notizen aus, um loszulegen. [Weitere Informationen](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="55309-p127">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="55309-254">**Finden Sie, wonach Sie suchen:** Verwenden Sie das Suchfeld, um Text, Befehle, Hilfe und mehr zu finden.</span><span class="sxs-lookup"><span data-stu-id="55309-254">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="55309-255">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-255">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="55309-256">**Suchen und Beheben von fehlenden Folientiteln:** Folientitel verleihen Ihrem Pitch mehr Nachdruck und machen Ihre Folien für Benutzer mit unterschiedlichen Fähigkeiten zugänglich.</span><span class="sxs-lookup"><span data-stu-id="55309-256">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="55309-257">Die Barrierefreiheitsprüfung zeigt Ihnen, wo Titel fehlen, damit Sie diese schnell hinzufügen können.</span><span class="sxs-lookup"><span data-stu-id="55309-257">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="55309-258">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-258">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="55309-259">**Zeichnen Sie es auf:** Verleihen Sie Office-Shapes in Ihrer Präsentation ein ungezwungenes, von Hand gezeichnetes Aussehen.</span><span class="sxs-lookup"><span data-stu-id="55309-259">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="55309-260">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-260">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="55309-261">**Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="55309-261">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="55309-262">**Keine Umleitung zum Browser mehr:** Sie legen fest, wie Links zu Office-Dokumenten geöffnet werden: im Browser oder in der App.</span><span class="sxs-lookup"><span data-stu-id="55309-262">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="55309-263">**Speichern einer Illustration als SVG:** Speichern Sie ein Diagramm, eine Form oder eine andere Abbildung als skalierbare Vektorgrafik, deren Größe ohne Verlust der Bildqualität geändert werden kann.</span><span class="sxs-lookup"><span data-stu-id="55309-263">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="55309-264">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-264">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="55309-265">**Drucken von Foliennummern auf Handzetteln:** Foliennummern werden automatisch in Ihre Handzettel integriert.</span><span class="sxs-lookup"><span data-stu-id="55309-265">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="55309-266">Sie können diese Funktion an- oder abschalten, wie es Ihnen beliebt.</span><span class="sxs-lookup"><span data-stu-id="55309-266">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="55309-267">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-267">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="55309-268">**Wiedergabe von animierten Freihandzeichnungen:** Wenn Sie Freihandeingaben auf Ihren Folien vornehmen, können Sie auf diese Freihandeingaben Replay-Animationen anwenden, um den eigentlichen Zeichenvorgang während der Bildschirmpräsentation wiederzugeben.</span><span class="sxs-lookup"><span data-stu-id="55309-268">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="55309-269">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-269">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="55309-270">**Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten.</span><span class="sxs-lookup"><span data-stu-id="55309-270">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="55309-271">**Optimieren Sie Ihre Präsentation für alle:** Die Barrierefreiheitsprüfung hilft Ihnen beim Anordnen von Objekten auf Ihren Folien, indem sie die Sprachausgabe berücksichtigt.</span><span class="sxs-lookup"><span data-stu-id="55309-271">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="55309-272">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="55309-272">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="55309-273">**Eine sicherere Video-Umgebung:** Security-Verbesserungen bedeuten für Sie eine sicherere Online-Video-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="55309-273">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="55309-274">**Warum neu erstellen, wenn Sie etwas wiederverwenden können?** Sparen Sie Zeit, indem Sie Folien, die Sie erstellt haben oder die andere für Sie freigegeben haben, erneut verwenden.</span><span class="sxs-lookup"><span data-stu-id="55309-274">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="55309-275">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-275">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="55309-276">**Ändern der handschriftlichen Freihandeingabe in Formen, Text oder Mathematik in PowerPoint für Office 365:** Wechseln Sie mit wenigen Strichen von der Freihandeingabe zu Office-Formen, Text oder einem mathematischen Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="55309-276">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="55309-277">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-277">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="55309-278">**Erstellen Sie eine hervorragende Folie:** Konvertieren Sie Ihre Freihandeingaben in Standardformen und -text, und lassen Sie sich dann von PowerPoint-Designer intelligente Folienentwurfsideen anzeigen.</span><span class="sxs-lookup"><span data-stu-id="55309-278">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="55309-279">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-279">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

### <a name="visio"></a><span data-ttu-id="55309-280">Visio</span><span class="sxs-lookup"><span data-stu-id="55309-280">Visio</span></span>

- <span data-ttu-id="55309-281">**Zurück zum Tatort:** Verwenden Sie die neuen Schablonen "Beweismittel", "Drinnen" und "Draußen" der Vorlage "Tatortermittlung", um Tatorte im Detail nachzustellen.</span><span class="sxs-lookup"><span data-stu-id="55309-281">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="55309-282">\*\* Erstellen Sie ansprechende Visio-Diagramme in Excel:\*\* Erstellen Sie ein Flussdiagramm oder ein Organigramm durch Einfügen von Daten in ein Arbeitsblatt.</span><span class="sxs-lookup"><span data-stu-id="55309-282">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="55309-283">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-283">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="55309-284">Word</span><span class="sxs-lookup"><span data-stu-id="55309-284">Word</span></span>

- <span data-ttu-id="55309-285">**Lebenslauf-Editor-Verknüpfung mit dem LinkedIn-Lebenslauf-Assistent:** Der Lebenslauf-Editor bietet eine Auswahl an Grammatik- und Stilprüfungen, die speziell auf Lebensläufe zugeschnitten sind, um Ihr Schreiben präziser und professioneller zu gestalten.</span><span class="sxs-lookup"><span data-stu-id="55309-285">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="55309-286">**Es wurde ein Problem mit beschädigten Dokumenten behoben, das durch das Zusammenführen von 3D-Objekten verursacht wurde:** Es wurde ein Problem mit beschädigten Dokumenten behoben, das durch das Zusammenführen von 3D-Objekten verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-286">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="55309-287">**Finden Sie, wonach Sie suchen:** Verwenden Sie das Suchfeld, um Text, Befehle, Hilfe und mehr zu finden.</span><span class="sxs-lookup"><span data-stu-id="55309-287">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="55309-288">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-288">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="55309-289">**Zusammenarbeit in lebendigen Farben:** Kommentare und Änderungen sind nach Verfasser farblich gekennzeichnet, sodass Sie die einzelnen Mitwirkenden leichter unterscheiden können.</span><span class="sxs-lookup"><span data-stu-id="55309-289">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="55309-290">**Makrofähige Dokumente gemeinsam bearbeiten:** Speichern Sie Ihre Dokumentdateien auf OneDrive for Business, und bearbeiten Sie sie mit anderen in Echtzeit.</span><span class="sxs-lookup"><span data-stu-id="55309-290">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="55309-291">**Verbesserungen bei der gemeinsamen Dokumenterstellung**: verbesserte Leistung von Word bei der gemeinsamen Dokumenterstellung mit nachverfolgbaren Änderungen.</span><span class="sxs-lookup"><span data-stu-id="55309-291">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="55309-292">**Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="55309-292">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="55309-293">Sie finden diese unter "Einfügen" > "Symbole".</span><span class="sxs-lookup"><span data-stu-id="55309-293">Find them at Insert > Icons.</span></span> [<span data-ttu-id="55309-294">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-294">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="55309-295">**Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.</span><span class="sxs-lookup"><span data-stu-id="55309-295">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="55309-296">**Zeichnen Sie es auf:** Verleihen Sie Office-Shapes in Ihrem Dokument ein ungezwungenes, von Hand gezeichnetes Aussehen.</span><span class="sxs-lookup"><span data-stu-id="55309-296">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="55309-297">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-297">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="55309-298">**Präzises Löschen:** Wählen Sie aus zwei Radierergrößen aus, um kleine Unvollkommenheiten zu beheben.</span><span class="sxs-lookup"><span data-stu-id="55309-298">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="55309-299">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-299">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="55309-300">**Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="55309-300">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="55309-301">**Keine Umleitung zum Browser mehr:** Sie legen fest, wie Links zu Office-Dokumenten geöffnet werden: im Browser oder in der App.</span><span class="sxs-lookup"><span data-stu-id="55309-301">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="55309-302">**Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.</span><span class="sxs-lookup"><span data-stu-id="55309-302">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="55309-303">**Verbesserungen bei der gemeinsamen Dokumenterstellung:** Verbesserte Zuverlässigkeit bei der gemeinsamen Dokumenterstellung.</span><span class="sxs-lookup"><span data-stu-id="55309-303">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="55309-304">**Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten.</span><span class="sxs-lookup"><span data-stu-id="55309-304">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="55309-305">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-305">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="55309-306">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="55309-306">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="55309-307">**Eine sicherere Video-Umgebung:** Security-Verbesserungen bedeuten für Sie eine sicherere Online-Video-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="55309-307">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="55309-308">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-308">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="55309-309">**Speichern von Shapes als Bildern:** mit nur wenigen Mausklicks können Sie eine Form, ein Symbol oder ein anderes Objekt als Bilddatei speichern, um Sie an anderer Stelle wiederzuverwenden.</span><span class="sxs-lookup"><span data-stu-id="55309-309">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="55309-310">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="55309-310">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)



[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="55309-313">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="55309-313">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="55309-314">Access</span><span class="sxs-lookup"><span data-stu-id="55309-314">Access</span></span>

- <span data-ttu-id="55309-315">Mit diesem Update wird ein Problem in Microsoft Access behoben, das den Fehler &quot;Abfrage ist beschädigt&quot; verursachen kann, wenn eine Aktualisierungsabfrage ausgeführt oder eine UPDATE-Anweisung in SQL verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="55309-315">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="55309-316">Dieses Update behebt ein Problem, das dazu führen kann, dass Microsoft Access eine Identitätsspalte in einer verknüpften SQL-Server-Tabelle nicht identifiziert, was dazu führen kann, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.</span><span class="sxs-lookup"><span data-stu-id="55309-316">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="55309-317">Dieses Update behebt ein Problem bei der Verwendung von ADODB.</span><span class="sxs-lookup"><span data-stu-id="55309-317">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="55309-318">Das Recorder-Objekt im VB-Code meldet möglicherweise einen Fehler falsch.</span><span class="sxs-lookup"><span data-stu-id="55309-318">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="55309-319">Access-Vorlagen sollten nicht länger dazu führen, dass Anhangsspalten in einer Datenbank fehlschlagen.</span><span class="sxs-lookup"><span data-stu-id="55309-319">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="55309-320">Nachdem Sie eine Vorlage instanziiert haben, sollten Sie nun in der Lage sein, Ihrer Datenbank ein Anhangsfeld hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="55309-320">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="55309-321">Excel</span><span class="sxs-lookup"><span data-stu-id="55309-321">Excel</span></span>

- <span data-ttu-id="55309-322">Es wurde ein Problem behoben, aufgrund dessen bei Benutzern Abstürze beim Umbenennen einer Signatur auftraten.</span><span class="sxs-lookup"><span data-stu-id="55309-322">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="55309-323">Diese Änderung umgeht ein Problem mit bestimmten Intel-Grafiktreibern durch Verwendung des Softwarerenderings.</span><span class="sxs-lookup"><span data-stu-id="55309-323">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="55309-324">Es wurde ein Problem behoben, durch das bei einigen Benutzern Abstürze auftraten, wenn Text in Spalten mit Zellen mit einem übergelaufenem Array konvertiert wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-324">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="55309-325">Dieses Update behebt ein Problem, das dazu führte, dass die Bearbeitungsleiste Text in einer anderen Schriftart als erwartet anzeigte.</span><span class="sxs-lookup"><span data-stu-id="55309-325">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="55309-326">Die Funktion "Text in Spalte" funktioniert bei einigen Gebietsschemas möglicherweise nicht.</span><span class="sxs-lookup"><span data-stu-id="55309-326">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="55309-327">Beim Zugriff auf einen verborgenen benannten Bereich kann ein Fehler auftreten.</span><span class="sxs-lookup"><span data-stu-id="55309-327">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="55309-328">Beim Speichern von Änderungen bei der Verwendung einiger nicht englischer Zeichengruppen tritt möglicherweise ein Fehler auf.</span><span class="sxs-lookup"><span data-stu-id="55309-328">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="55309-329">Wir haben ein Problem gelöst, durch das das Auswählen einer Zelle nach dem Scrollen dazu führen konnte, dass die falsche Zelle ausgewählt wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-329">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="55309-330">In Excel kann ein Problem auftreten, durch das das Bearbeiten einer geschützten Datei von einer nicht vertrauenswürdigen Netzwerkfreigabe zu einem Fehler in Excel führt.</span><span class="sxs-lookup"><span data-stu-id="55309-330">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="55309-331">Die Funktion "Text in Spalte" funktioniert bei einigen Lokalisierungen möglicherweise nicht.</span><span class="sxs-lookup"><span data-stu-id="55309-331">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="55309-332">Beim Zugriff auf einen verborgenen benannten Bereich kann ein Fehler auftreten.</span><span class="sxs-lookup"><span data-stu-id="55309-332">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="55309-333">Beim Speichern von Änderungen bei der Verwendung einiger nicht englischer Zeichengruppen tritt möglicherweise ein Fehler auf.</span><span class="sxs-lookup"><span data-stu-id="55309-333">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="55309-334">Es wurde ein Problem behoben, das bei einigen Benutzern mit verknüpften und eingebetteten Objekten (OLE) auftrat.</span><span class="sxs-lookup"><span data-stu-id="55309-334">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="55309-335">Das Kontextmenü für PivotCharts wurde korrigiert, um die Option "Details anzeigen" zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="55309-335">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="55309-336">Es wurde ein Problem behoben, das bei der Suche nach zuletzt verwendeten Dateien zu einem Absturz geführt hat, wenn keine Arbeitsmappe geöffnet ist.</span><span class="sxs-lookup"><span data-stu-id="55309-336">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="55309-337">Es wurde ein Problem behoben, durch das einigen Benutzern mehrere Popupfenster angezeigt wurden, wenn externe Links in der Arbeitsmappe vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="55309-337">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="55309-338">Es wurde ein Problem behoben, bei dem Kommentarbefehle im Kontextmenü nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="55309-338">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="55309-339">Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-339">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="55309-340">Ein Problem wurde behoben, bei dem CUBEWERT-Funktionen manchmal ein falsches Ergebnis zurückgaben.</span><span class="sxs-lookup"><span data-stu-id="55309-340">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="55309-341">Outlook</span><span class="sxs-lookup"><span data-stu-id="55309-341">Outlook</span></span>

- <span data-ttu-id="55309-342">Es wurde ein Problem behoben, durch das die Such-Feedback-Umgebung zum Hängen gebracht wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-342">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="55309-343">Es wurde ein Problem behoben, das dazu führte, dass Benutzer in Outlook beim Abrufen von Cloudeinstellungen hängen bleiben.</span><span class="sxs-lookup"><span data-stu-id="55309-343">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="55309-344">Es wurde ein Problem behoben, das dazu führte, dass das Suchfeld im Modus mit hohem DPI-Wert nicht korrekt ausgerichtet war.</span><span class="sxs-lookup"><span data-stu-id="55309-344">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="55309-345">Ein Problem wurde behoben, durch das Benutzer einen Speicherverlust im Outlook-Prozess beobachten konnten.</span><span class="sxs-lookup"><span data-stu-id="55309-345">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="55309-346">Es wurde ein Problem behoben, durch das Benutzern unter bestimmten Umständen E-Mails angezeigt werden, die an eine Adresse gesendet wurden, die nicht mit der angezeigten SMTP-Adresse übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="55309-346">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="55309-347">Diese Änderung stellt die Fähigkeit wieder her, mehrzeilige Betreffzeilen im Nachrichtenkopf anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="55309-347">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="55309-348">Es wurde ein Problem behoben, durch das verhindert werden konnte, dass Dateien an einem WebDAV-Speicherort gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="55309-348">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="55309-349">Es wurde ein Problem mit der Auswahl des SMIME-Algorithmus behoben.</span><span class="sxs-lookup"><span data-stu-id="55309-349">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="55309-350">Ein Problem wurde behoben, durch das Anwendungen von Drittanbietern keine E-Mail-Nachrichten mehr senden konnten.</span><span class="sxs-lookup"><span data-stu-id="55309-350">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="55309-351">Es wurde ein Problem behoben, das bewirkt hat, dass Benutzer ein leeres Meldungsfeld mit einer &quot;OK&quot;-Schaltfläche angezeigt bekamen, wenn Sie versuchten, den Support über den Kontext der Kontoerstellung zu kontaktieren.</span><span class="sxs-lookup"><span data-stu-id="55309-351">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="55309-352">Ein Problem wurde behoben, das während der Profilerstellung ein Absturz verursachte.</span><span class="sxs-lookup"><span data-stu-id="55309-352">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="55309-353">Ein Problem wurde behoben, das dazu führte, dass Outlook unerwartet alle E-Mails synchronisierte, selbst wenn der Synchronisierungsschieberegler auf eine kleinere Einstellung eingestellt ist.</span><span class="sxs-lookup"><span data-stu-id="55309-353">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="55309-354">Ein Problem wurde behoben, das dazu führte, dass für Benutzer mit dem schwarzen Design die Dropdownliste &quot;Von&quot; als weißer Text auf weißem Hintergrund angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-354">Addressed an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>

- <span data-ttu-id="55309-355">Es wurde ein Problem behoben, bei dem es durch das Abbrechen der Kontoeinrichtung einen Absturz gab.</span><span class="sxs-lookup"><span data-stu-id="55309-355">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="55309-356">Es wurde ein Problem behoben, aufgrund dessen bei Benutzern Abstürze beim Umbenennen einer Signatur auftraten.</span><span class="sxs-lookup"><span data-stu-id="55309-356">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="55309-357">Es wurde ein Problem behoben, durch das die Option zum Deaktivieren der Hervorhebung markierter Elemente in einigen Szenarien nicht berücksichtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-357">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="55309-358">Es wurde ein Problem behoben, durch das Benutzer die Aufforderung &quot;die Regeln auf diesem Computer entsprechen nicht den Regeln von Microsoft Exchange&quot; beim Öffnen des Dialogfelds „Regeln“ angezeigt bekommen.</span><span class="sxs-lookup"><span data-stu-id="55309-358">Addressed an issue that caused users to see a &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="55309-359">Es wurde ein Problem behoben, bei dem beim Angeben einer ungültigen Absenderadresse ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-359">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="55309-360">Es wurde ein Problem behoben, das einen Speicherverlust bei sehr langen Outlook-Sitzungen verursachte.</span><span class="sxs-lookup"><span data-stu-id="55309-360">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="55309-361">Ein Problem wurde behoben, das zu einem Absturz führen könnte, wenn dasselbe Element in mehreren Fenstern angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="55309-361">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="55309-362">Es wurde ein Problem behoben, durch das Benutzer mit einer spürbaren Verzögerung beim Interagieren mit ihren Postfachordnern über Tastenkombinationen konfrontiert waren.</span><span class="sxs-lookup"><span data-stu-id="55309-362">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="55309-363">Ein Problem wurde behoben, durch das Benutzer einige Instanzen von wiederkehrenden Kalenderelementen nicht öffnen konnten.</span><span class="sxs-lookup"><span data-stu-id="55309-363">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="55309-364">Es wurde ein Problem behoben, das bei Benutzern mit Postfächern auf Exchange 2010-Servern zu Problemen beim Hinzufügen von Anlagen zu Kalendereinträgen führte.</span><span class="sxs-lookup"><span data-stu-id="55309-364">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="55309-365">Es wurde ein Problem behoben, durch das Benutzer Probleme beim Beantworten digital signierter Nachrichten hatten.</span><span class="sxs-lookup"><span data-stu-id="55309-365">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="55309-366">Es wurde ein Problem behoben, durch das das Feld "Ort" in Besprechungen unerwartet aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-366">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="55309-367">Es wurde ein Problem behoben, das dazu führte, dass Kommas im Ortsfeld einer Besprechung in Semikolons umgewandelt wurden.</span><span class="sxs-lookup"><span data-stu-id="55309-367">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="55309-368">Es wurde ein Problem behoben, bei dem der Standort einer Besprechung unerwartet nach dem Löschen wieder der Besprechung hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-368">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="55309-369">Es wurden Probleme im Zusammenhang mit in der brasilianischen Zeitzone festgelegten Sitzungen und Terminen behoben.</span><span class="sxs-lookup"><span data-stu-id="55309-369">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="55309-370">Es wurde ein Problem behoben, durch beim Drücken der Taste &quot;S&quot; nach dem Schließen der Barrierefreiheitsprüfung unerwartet E-Mails gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="55309-370">Addressed an issue that caused users to see mails unexpectedly send when pressing the &quot;S&quot; key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="55309-371">Hiermit wird die Blockierungslogik für Anlagen in Outlook aktualisiert, um auch Python-Anlagen zu blockieren.</span><span class="sxs-lookup"><span data-stu-id="55309-371">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="55309-372">Ein Problem wurde behoben, durch das Web-Add-Ins auf von Digital Rights Management verwaltete Nachrichten zugreifen konnten.</span><span class="sxs-lookup"><span data-stu-id="55309-372">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="55309-373">Ein Problem wurde behoben, das während der Profilerstellung ein Absturz verursachte.</span><span class="sxs-lookup"><span data-stu-id="55309-373">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="55309-374">Es wurde ein Problem behoben, aufgrund dessen bei Benutzern Abstürze beim Umbenennen einer Signatur auftraten.</span><span class="sxs-lookup"><span data-stu-id="55309-374">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="55309-375">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="55309-375">PowerPoint</span></span>

- <span data-ttu-id="55309-376">Ein Problem mit der Shape.Paste-Methode wurde behoben: Wenn der Benutzer die Form mit der Shape.Paste-Methode kopiert und einfügt, wird die Auswahl in die eingefügte Form geändert.</span><span class="sxs-lookup"><span data-stu-id="55309-376">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="55309-377">Es wurde ein Problem behoben, das bei der Verwendung des Kontextmenüs in älteren PPT-Kommentaren zu einem Absturz führen könnte.</span><span class="sxs-lookup"><span data-stu-id="55309-377">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="55309-378">Project</span><span class="sxs-lookup"><span data-stu-id="55309-378">Project</span></span>

- <span data-ttu-id="55309-379">Ein Problem wurde identifiziert, bei dem Benutzer beim Öffnen eines schreibgeschützten Projekts möglicherweise mehrere Meldungen erhielten.</span><span class="sxs-lookup"><span data-stu-id="55309-379">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="55309-380">Es wurde ein Problem behoben, bei dem 100% Aufgaben vom Typ "feste Dauer" fälschlicherweise zu weniger als 100% erledigt wurden.</span><span class="sxs-lookup"><span data-stu-id="55309-380">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="55309-381">Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="55309-381">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="55309-382">Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.</span><span class="sxs-lookup"><span data-stu-id="55309-382">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="55309-383">Word</span><span class="sxs-lookup"><span data-stu-id="55309-383">Word</span></span>

- <span data-ttu-id="55309-384">Ein Problem wurde behoben, bei dem das Speichern einer vorhandenen Datei in einigen Fällen das Dialogfeld "Speichern unter" aufruft und die Datei nie wirklich gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="55309-384">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="55309-385">Im Organizer für Bausteine könnte eine ungültige Warnung angezeigt werden: &quot;Sie haben modifizierte Formen, Bausteine&quot;.</span><span class="sxs-lookup"><span data-stu-id="55309-385">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>

### <a name="office-suite"></a><span data-ttu-id="55309-386">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="55309-386">Office Suite</span></span>

- <span data-ttu-id="55309-387">Diese Änderung betrifft die langsame Darstellung einiger Streudiagramme mit Markierungen.</span><span class="sxs-lookup"><span data-stu-id="55309-387">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="55309-388">Diese Änderung behebt gemeldete Probleme mit Grafikadaptern, die die integrierte Intel-GPU nutzen.</span><span class="sxs-lookup"><span data-stu-id="55309-388">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="55309-389">Ein Fehler in der Einstellung des Stichtags für ODT- und GPO-Updates wurde behoben, bei dem der relative Stichtag nur beim ersten Festlegen funktionierte. Der Fix aktiviert den relativen Stichtag für spätere Updates.</span><span class="sxs-lookup"><span data-stu-id="55309-389">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="55309-390">Es wurde ein Problem behoben, bei dem Office-Aktualisierungen möglicherweise unerwartet Dateien aus dem Office CDN anstelle der beabsichtigten Quelle heruntergeladen haben, beispielsweise eine lokale oder Netzwerkfreigabe oder einen vom Configuration Manager bereitgestellten Speicherort.</span><span class="sxs-lookup"><span data-stu-id="55309-390">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="55309-391">Ein Problem wurde behoben, das dazu führte, dass beim Öffnen mehrerer Dokumente in Word/Excel/PowerPoint aus derselben SharePoint-Bibliothek lediglich das erste geöffnete Dokument auf Richtlinienkonformität gescannt wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-391">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (BUGDETAILS NICHT AM INHALTSENDE ENTFERNEN)

## <a name="version-1908-february-11"></a><span data-ttu-id="55309-393">Version 1908: 11. Februar</span><span class="sxs-lookup"><span data-stu-id="55309-393">Version 1908: February 11</span></span>
<span data-ttu-id="55309-394">*Version 1908 (Build 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="55309-394">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="55309-395">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="55309-395">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="55309-397">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="55309-397">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="55309-398">Excel</span><span class="sxs-lookup"><span data-stu-id="55309-398">Excel</span></span>

- <span data-ttu-id="55309-399">Dieses Update behebt ein Problem, das dazu führte, dass ein Fehler auftrat, wenn VBA zum Hinzufügen eines Bildes zur Kopf-/Fußzeile eines Diagramms verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-399">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="55309-400">Es wurde ein Problem behoben, bei dem der Rand eines Gruppenfeld-Steuerelements in der Druckvorschau oder beim Drucken nicht sichtbar war.</span><span class="sxs-lookup"><span data-stu-id="55309-400">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="55309-401">Nutzer können beim Speichern von Änderungen auf einen Fehler stoßen, wenn sie manche nicht englische Zeichensätze verwenden.</span><span class="sxs-lookup"><span data-stu-id="55309-401">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="55309-402">Es wurde ein Problem behoben, durch das die Dateigröße von Bildern in Diagrammkopfzeilen beim Speichern der Arbeitsmappe mit dem Diagramm zunahm.</span><span class="sxs-lookup"><span data-stu-id="55309-402">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="55309-403">Es wurde ein Problem behoben, das zur Beschädigung von DBCS-Zeichen in Büchern mit Querverweisen führte, indem die Auswahlbereiche mit dem Buch mit Querverweisen synchronisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="55309-403">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="55309-404">Es wurde ein Problem behoben, das dazu führen konnte, dass Kontrollkästchen bei Verwendung der automatischen Anpassung zum Anpassen der Zeilenhöhe verkleinert wurden.</span><span class="sxs-lookup"><span data-stu-id="55309-404">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="55309-405">Outlook</span><span class="sxs-lookup"><span data-stu-id="55309-405">Outlook</span></span>

- <span data-ttu-id="55309-406">Es wurde ein Problem behoben, bei dem beim Angeben einer ungültigen Absenderadresse ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-406">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="55309-407">Es wurde ein Problem behoben, bei dem Nutzer bei der Verarbeitung von Konfliktnachrichten Synchronisierungsfehler hatten.</span><span class="sxs-lookup"><span data-stu-id="55309-407">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="55309-408">Es wurde ein Problem behoben, bei dem Nutzer beim Starten von Outlook beim Laden des Profils auf dem Bildschirm "Laden von Profilen" hängen blieben.</span><span class="sxs-lookup"><span data-stu-id="55309-408">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="55309-409">Es wurde ein Problem behoben, durch das Nutzer beim Ändern von Ansichten zeitweise Abstürze sehen konnten.</span><span class="sxs-lookup"><span data-stu-id="55309-409">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="55309-410">Es wurde ein Problem behoben, bei dem beim Anzeigen von mehr als 30 Kalendern in einer Citrix-Umgebung ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-410">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="55309-411">[Hier](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) ist die einzelne KB, in der dies für frühere Versionen dokumentiert wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-411">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="55309-412">Behebt ein Problem, bei dem Nutzer Probleme mit der Synchronisierung freigegebener Kalenderordner mit dem OST hatten, was zu Berechtigungsfehlern führte, wenn sie versuchten, mit diesen Ordnern zu interagieren.</span><span class="sxs-lookup"><span data-stu-id="55309-412">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="55309-413">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="55309-413">PowerPoint</span></span>

- <span data-ttu-id="55309-414">Verbessertes Szenario zum Kopieren und Einfügen Das Kopieren der Form in eine PowerPoint-Folie und das Einfügen in eine andere Folie in einer Schleife schlägt möglicherweise mit Ausnahme fehl.</span><span class="sxs-lookup"><span data-stu-id="55309-414">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="55309-415">Es wurde ein Problem behoben, das zu einer langsameren Leistung zwischen Nutzern, die zusammenarbeiten, führte.</span><span class="sxs-lookup"><span data-stu-id="55309-415">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="55309-416">Es wurde ein Problem behoben, das auftreten konnte, wenn eine Datei, die inkrementell geöffnet wurde, eine Folie mit mehr als einem eingebetteten Mediendatenstrom enthielt.</span><span class="sxs-lookup"><span data-stu-id="55309-416">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="55309-417">Wir haben ein Problem behoben, bei dem beim ersten Start von PowerPoint möglicherweise keine Sicherheitswarnmeldung für nicht vertrauenswürdige Add-Ins angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="55309-417">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="55309-418">Project</span><span class="sxs-lookup"><span data-stu-id="55309-418">Project</span></span>

- <span data-ttu-id="55309-419">Es wurde ein Problem behoben, bei dem die tatsächliche Arbeit zwischen Arbeitszeittabelle und Projektplan unterschiedlich sein kann, da Ressourcenkalender nicht aktualisiert werden, wenn sich der Basiskalender ändert.</span><span class="sxs-lookup"><span data-stu-id="55309-419">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="55309-420">Word</span><span class="sxs-lookup"><span data-stu-id="55309-420">Word</span></span>

- <span data-ttu-id="55309-421">Ein Absturz in Word wurde behoben, indem es von einer veralteten API entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-421">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="55309-422">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="55309-422">Office Suite</span></span>

- <span data-ttu-id="55309-423">Diese Änderung behebt das korrekte Rendern von Bildern nach dem Öffnen einer beschädigten Datei.</span><span class="sxs-lookup"><span data-stu-id="55309-423">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1908-january-14"></a><span data-ttu-id="55309-425">Version 1908: 14. Januar</span><span class="sxs-lookup"><span data-stu-id="55309-425">Version 1908: January 14</span></span>
<span data-ttu-id="55309-426">*Version 1908 (Build 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="55309-426">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="55309-427">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="55309-427">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="55309-429">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="55309-429">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="55309-430">Excel</span><span class="sxs-lookup"><span data-stu-id="55309-430">Excel</span></span>

- <span data-ttu-id="55309-431">Die Niederländische Tastenkombination für Dokumenttitel wurde in Alt-G geändert.</span><span class="sxs-lookup"><span data-stu-id="55309-431">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="55309-432">Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-432">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="55309-433">Es gab ein Problem, bei dem Sie keine Elemente aus dem Kombinationsfeld eines WPF-Formulars (Windows Presentation Foundation) auswählen konnten, das von einem Add-n geöffnet wurde.</span><span class="sxs-lookup"><span data-stu-id="55309-433">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="55309-434">Outlook</span><span class="sxs-lookup"><span data-stu-id="55309-434">Outlook</span></span>

- <span data-ttu-id="55309-435">Es wurde ein Problem behoben, durch das Benutzer mit einer spürbaren Verzögerung beim Interagieren mit ihren Postfachordnern über Tastenkombinationen konfrontiert waren.</span><span class="sxs-lookup"><span data-stu-id="55309-435">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="55309-436">Es wurde ein Problem behoben, bei dem Richtlinientipps bei Verwendung eines alternativen Absenders nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="55309-436">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="55309-437">Es wurde ein Problem behoben, das bei der Aktualisierung von Anwesenheitsinformationen zu zeitweiligen Abstürzen führte.</span><span class="sxs-lookup"><span data-stu-id="55309-437">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="55309-438">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="55309-438">PowerPoint</span></span>

- <span data-ttu-id="55309-439">Wir haben ein Problem behoben, bei dem beim Kopieren einer Folie von einer Präsentation in eine andere möglicherweise doppelte Master erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="55309-439">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="55309-440">Bei Dateien mit neuen modernen Kommentaren wird eine gelbe Warnung angezeigt, wenn sie in einer nicht unterstützten Version geöffnet werden.</span><span class="sxs-lookup"><span data-stu-id="55309-440">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="55309-441">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="55309-441">Office Suite</span></span>

- <span data-ttu-id="55309-442">Es wurde ein Problem behoben, bei dem Office-Update-Nachrichten in einer anderen Sprache als erwartet angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="55309-442">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="55309-443">In Zukunft entsprechen Office-Update-Nachrichten ordnungsgemäß der Windows-Anzeigesprache.</span><span class="sxs-lookup"><span data-stu-id="55309-443">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="55309-444">Es wurde ein Problem behoben, bei dem ein Update in bestimmten Fällen nicht installiert wurde, wenn der Benutzer kein Administrator ist und das Systemkonto keine Netzwerkverbindung hatte.</span><span class="sxs-lookup"><span data-stu-id="55309-444">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

> [!NOTE]
> <span data-ttu-id="55309-446">Wenn Sie Hilfe bei einem Problem mit der Nutzung von Office benötigen, empfehlen wir, dass Sie Ihre Frage im [Microsoft Answers-Forum](https://answers.microsoft.com/) oder in der [Tech-Community](https://techcommunity.microsoft.com/) veröffentlichen, oder Sie können sich an den [Support](https://support.microsoft.com/contactus) wenden.</span><span class="sxs-lookup"><span data-stu-id="55309-446">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>

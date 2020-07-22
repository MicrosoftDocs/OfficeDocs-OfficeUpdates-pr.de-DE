---
title: Versionshinweise für Versionen des halbjährlichen Unternehmenskanals (Vorschau) im Jahr 2020
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt IT-Experten Anmerkungen zur Version für Releases im halbjährlichen Kanal (gezielt) für Microsoft 365 Apps im Jahr 2020 zur Verfügung.
ms.openlocfilehash: 28b78e3952867cb55b2b91e9e6d9d8d5f2e35063
ms.sourcegitcommit: 6f79e3c3948db4d7ae1c6dfc855970551d3b1678
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/20/2020
ms.locfileid: "45187585"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview-releases-in-2020"></a><span data-ttu-id="19df9-103">Versionshinweise für Versionen des halbjährlichen Unternehmenskanals (Vorschau) im Jahr 2020</span><span class="sxs-lookup"><span data-stu-id="19df9-103">Release notes for Semi-Annual Enterprise Channel (Preview) releases in 2020</span></span>

<span data-ttu-id="19df9-104">Diese Versionshinweise enthalten Informationen zu neuen Features und nicht sicherheitsrelevanten Updates, die in halbjährlichen Kanal-Updates (Vorschau) im Jahr 2020 für Microsoft 365 Apps for Enterprise, Microsoft 365 Apps for Business sowie in den Abonnementversionen der Desktop-Apps für Project und Visio enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="19df9-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="19df9-105">Wir nehmen einige Änderungen an den Updatekanälen für Microsoft 365-Apps vor, unter anderem fügen wir einen neuen Updatekanal hinzu (Monatlicher Enterprise-Kanal) und ändern die Namen der vorhandenen Updatekanäle.</span><span class="sxs-lookup"><span data-stu-id="19df9-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="19df9-106">Um mehr zu erfahren, [lesen Sie diesen Artikel](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="19df9-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>


## <a name="version-2002-july-14"></a><span data-ttu-id="19df9-107">Version 2002: 14. Juli</span><span class="sxs-lookup"><span data-stu-id="19df9-107">Version 2002: July 14</span></span>
<span data-ttu-id="19df9-108">*Version 2002 (Build 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="19df9-108">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="19df9-109">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="19df9-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="19df9-111">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="19df9-111">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="19df9-112">Excel</span><span class="sxs-lookup"><span data-stu-id="19df9-112">Excel</span></span>

- <span data-ttu-id="19df9-113">Beschleunigen des Ladens von Dateien, die im lokalen OneDrive-Ordner zur Verfügung stehen.</span><span class="sxs-lookup"><span data-stu-id="19df9-113">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="19df9-114">Es wurde ein Problem behoben, das dazu führte, dass CustomUI XML für eine benutzerdefinierte Multifunktionsleisten-Registerkarte beim Speichern in SharePoint/OneDrive entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-114">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="19df9-115">Es wurde ein Problem behoben, bei dem die Fehlermeldung „Diese Arbeitsmappe wird derzeit von einer anderen Arbeitsmappe referenziert und kann nicht geschlossen werden“ eingeblendet wurde, weil Add-Ins in alphabetischer Reihenfolge und nicht in einer vom Benutzer festgelegten Reihenfolge geladen wurden.</span><span class="sxs-lookup"><span data-stu-id="19df9-115">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="19df9-116">Es wurde ein Problem behoben, bei dem beim Klicken auf einen Hyperlink zu einer Stelle in einer bereits geöffneten Arbeitsmappe eine Arbeitsmappe ausgeblendet werden konnte.</span><span class="sxs-lookup"><span data-stu-id="19df9-116">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="19df9-117">Es wurde ein Problem behoben, bei dem einige kopierte und eingefügte Diagrammverknüpfungen zugeordnete Laufwerksadressen anstelle von Universaladressen verwendeten.</span><span class="sxs-lookup"><span data-stu-id="19df9-117">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="19df9-118">Die Leistung beim Löschen von Spalten mit verbundenen Zellen wurde verbessert.</span><span class="sxs-lookup"><span data-stu-id="19df9-118">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="19df9-119">Ein Problem wurde behoben, bei dem Druckernamen in der Liste der Drucker im Dialogfeld „Drucken“ wiederholt werden konnten.</span><span class="sxs-lookup"><span data-stu-id="19df9-119">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="19df9-120">Es wurde ein Problem behoben, bei dem Arbeitsblätter, die mehrere Formeln mit definierten Namen enthielten, zu längeren Zeiten beim Speichern von Dateien geführt haben.</span><span class="sxs-lookup"><span data-stu-id="19df9-120">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="19df9-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="19df9-121">Outlook</span></span>

- <span data-ttu-id="19df9-122">Es wurde ein Problem behoben, bei dem das IME-Fenster (Eingabemethoden-Editor) den zugrunde liegenden Text, der über den IME eingegeben wird, überlappte, wenn mehrere Monitore mit unterschiedlichen Auflösungen verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="19df9-122">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="19df9-123">Es wurde ein Problem behoben, das bewirkte, dass bei einer bevorstehenden Änderung der Zeitzonendefinition Terminserien oder Besprechungen zur falschen Uhrzeit angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="19df9-123">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="19df9-124">Es wurde ein Problem behoben, durch das Benutzern die Nachricht "Die Regeln auf diesem Computer entsprechen nicht den Regeln in Microsoft Exchange" angezeigt wird, wenn sie ihre Regeln in Outlook aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="19df9-124">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="19df9-125">Es wurde ein Problem behoben, bei dem die Option "Weiterleitung zulassen" in den "Antwortoptionen" für Kalenderbesprechungen nicht angezeigt wurde, wenn die Option für das Herunterladen freigegebener Ordner NICHT aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="19df9-125">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="19df9-126">Ein Problem wurde behoben, durch das gelegentlich Kategorien in E-Mail-Nachrichten nicht mehr aufschienen.</span><span class="sxs-lookup"><span data-stu-id="19df9-126">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="19df9-127">Ein Problem wurde behoben, durch das Stellvertretungen auf unterschiedlichen Computern unterschiedliche Ordnerhierarchien für freigegebene Postfächer angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="19df9-127">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="19df9-128">Ein Problem wurde behoben, durch das Stellvertretungen beim Bearbeiten eines vorhandenen Kalendertermins im Kalender eines Managers eine Fehlermeldung erhalten haben.</span><span class="sxs-lookup"><span data-stu-id="19df9-128">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="19df9-129">Ein Problem wurde behoben, das bewirkt hatte, dass der Text einer NDR-Nachricht nach der Bearbeitung des Betreffs von Unicode in ASCII geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-129">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="19df9-130">Es wurde ein Problem behoben, durch das Benutzer einen Absturz erfahren, wenn zwei Add-Ins der gleichen Menübandgruppe eine Schaltfläche hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="19df9-130">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="19df9-131">Es wurde ein Problem behoben, aufgrund dessen Benutzer nicht in der Lage waren, E-Mails an eine persönliche Verteilerliste zu senden.</span><span class="sxs-lookup"><span data-stu-id="19df9-131">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="19df9-132">Es wurde ein Problem behoben, das bewirkt, dass Links nicht zu E-Mails mit der richtigen standardmäßigen Mandantenberechtigung hinzugefügt werden können, wenn die standardmäßige Mandantenberechtigung als "jeder" konfiguriert ist.</span><span class="sxs-lookup"><span data-stu-id="19df9-132">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="19df9-133">Ein Problem wurde behoben, das dazu führte, dass Benutzer OneDrive-Anlagen von außerhalb ihres Mandanten nicht auf ihrem lokalen Computer speichern konnten, wenn sie im Dialogfeld "Sicherheit" die Option "Speichern" wählten.</span><span class="sxs-lookup"><span data-stu-id="19df9-133">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="19df9-134">Word</span><span class="sxs-lookup"><span data-stu-id="19df9-134">Word</span></span>

- <span data-ttu-id="19df9-135">Es wurde ein Problem im Coautthoring behoben, wenn die Richtlinie "FileBlick\Word2007Files" aktiviert wird.</span><span class="sxs-lookup"><span data-stu-id="19df9-135">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="19df9-136">Es wurde das Problem behoben, dass Word QuickPart beim Hinzufügen eines Suchfelds, das umbenannt wurde, nicht funktioniert.</span><span class="sxs-lookup"><span data-stu-id="19df9-136">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="19df9-137">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="19df9-137">Office Suite</span></span>

- <span data-ttu-id="19df9-138">Ein Problem wurde behoben, bei dem Benutzer bei der gemeinsamen Erstellung von großen PowerPoint-Dateien übermäßige Netzwerk- und CPU-Auslastung erfahren können.</span><span class="sxs-lookup"><span data-stu-id="19df9-138">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="19df9-139">Ein neuer Sturz von AppV51 wurde zurückportiert, um eine Regression im vorherigen AppV51 zu beheben.</span><span class="sxs-lookup"><span data-stu-id="19df9-139">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="19df9-140">Es wurde ein Absturzproblem mit dem Office-Host in Windows behoben, wenn ein Add-In aktiviert wird, während die Registrierung TabProcGrowth den Wert REG_SZ Typ hat.</span><span class="sxs-lookup"><span data-stu-id="19df9-140">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-june-09"></a><span data-ttu-id="19df9-142">Version 2002: 9. Juni</span><span class="sxs-lookup"><span data-stu-id="19df9-142">Version 2002: June 09</span></span>
<span data-ttu-id="19df9-143">*Version 2002 (Build 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="19df9-143">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="19df9-144">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="19df9-144">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="19df9-146">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="19df9-146">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="19df9-147">Excel</span><span class="sxs-lookup"><span data-stu-id="19df9-147">Excel</span></span>

- <span data-ttu-id="19df9-148">Es wurde ein Problem behoben, bei dem die externe Verknüpfung nicht mehr funktioniert, nachdem die Datei erneut geöffnet wurde, wenn der Dateipfad zu lang ist.</span><span class="sxs-lookup"><span data-stu-id="19df9-148">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="19df9-149">Es wurde ein Problem behoben, bei dem Excel u. U. nicht mehr reagierte, nachdem STRG+UMSCHALT+Pfeiltasten zum Scrollen verwendet wurden, wenn das Excel-Fenster über Microsoft Teams gemeinsam genutzt wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-149">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="19df9-150">Ein Problem mit der Skalierung von Kontrollkästchen in Formularsteuerelementen beim Drucken wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="19df9-150">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="19df9-151">Ein Absturz konnte auftreten, wenn versucht wurde, Änderungen mithilfe des Legacymodus "Freigegebene Arbeitsmappe" auf einem neuen Blatt für eine Arbeitsmappe aufzulisten.</span><span class="sxs-lookup"><span data-stu-id="19df9-151">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="19df9-152">Das Einfügen einer Spalte in eine gefilterte Liste würde länger dauern als erwartet.</span><span class="sxs-lookup"><span data-stu-id="19df9-152">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="19df9-153">Es wurde ein Problem behoben, bei dem ein @-Symbol, mit dem eine Formel beginnt, als impliziter Schnittmengenoperator betrachtet wird.</span><span class="sxs-lookup"><span data-stu-id="19df9-153">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="19df9-154">Outlook</span><span class="sxs-lookup"><span data-stu-id="19df9-154">Outlook</span></span>

- <span data-ttu-id="19df9-155">Ermöglicht die Teilnahme an einer Teambesprechung direkt über den systemeigenen Teams-Client.</span><span class="sxs-lookup"><span data-stu-id="19df9-155">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="19df9-156">Es wurde ein Problem behoben, bei dem Outlook die Datenschutzrichtlinie nicht aktiviert hat, um Tipps für Benutzer zu geben, die für den Dienst bezahlt haben und M365 Business Plus-Pläne nutzen.</span><span class="sxs-lookup"><span data-stu-id="19df9-156">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="19df9-157">Es wurde ein Problem behoben, aufgrund dessen Benutzer mit der falschen Browseremulationseinstellung nicht die Authentifizierungsaufforderung für Gmail ausführen konnten.</span><span class="sxs-lookup"><span data-stu-id="19df9-157">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="19df9-158">Es wurde ein Problem behoben, aufgrund dessen Outlook-Benutzern auf Serverbetriebssystemen die Fehlermeldung "Antivirenstatus: Ungültig" angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-158">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="19df9-159">Diese Version von Windows unterstützt die Erkennung von Antivirus, aber es wurde kein Antivirus gefunden, obwohl Antivirus korrekt konfiguriert war.</span><span class="sxs-lookup"><span data-stu-id="19df9-159">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="19df9-160">Word</span><span class="sxs-lookup"><span data-stu-id="19df9-160">Word</span></span>

- <span data-ttu-id="19df9-161">Es wurde ein Problem behoben, bei dem die Ausrichtung von Wörtern in einem Dokument durcheinandergebracht wurde, wenn Benutzer nach dem Drucken mit Schnelldruck versuchten, den Text zu bearbeiten.</span><span class="sxs-lookup"><span data-stu-id="19df9-161">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="19df9-162">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="19df9-162">Office Suite</span></span>

- <span data-ttu-id="19df9-163">Dieses Problem wurde behoben, indem die Kanalnamen in der Januar 2020-Verzweigung in der Backstage-Version auf die neuen Kanalnamen aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="19df9-163">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="19df9-164">Dieses Problem wurde behoben. Wenn ein Gerät nun mit Richtlinien verwaltet wird, wird nicht die DMS Audience-API aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="19df9-164">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="19df9-165">Es wurde das Problem behoben, aufgrund dessen es beim Hinzufügen oder Entfernen von Apps in einer einzigen Transaktion zu einer unvollständigen Entfernung kam.</span><span class="sxs-lookup"><span data-stu-id="19df9-165">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="19df9-166">Der Office-Host stürzte in Fenstern ab, wenn ein Add-In aktiviert wird, während der Registrierungsschlüssel HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth auf Null gesetzt ist.</span><span class="sxs-lookup"><span data-stu-id="19df9-166">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="19df9-167">Mit dieser Änderung wird dieses Problem behoben.</span><span class="sxs-lookup"><span data-stu-id="19df9-167">This change would fix this issue.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-may-12"></a><span data-ttu-id="19df9-169">Version 2002: 12. Mai</span><span class="sxs-lookup"><span data-stu-id="19df9-169">Version 2002: May 12</span></span>
<span data-ttu-id="19df9-170">*Version 2002 (Build 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="19df9-170">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="19df9-171">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="19df9-171">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="19df9-173">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="19df9-173">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="19df9-174">Excel</span><span class="sxs-lookup"><span data-stu-id="19df9-174">Excel</span></span>

- <span data-ttu-id="19df9-175">Das Öffnen einer Arbeitsmappe mit Verweisen auf zahlreiche andere Arbeitsmappen, insbesondere mit versteckten Fenstern, würde langsamer als erwartet ablaufen.</span><span class="sxs-lookup"><span data-stu-id="19df9-175">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="19df9-176">Das Öffnen von CSV-Dateien dauerte unter bestimmten Umständen länger als erwartet.</span><span class="sxs-lookup"><span data-stu-id="19df9-176">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="19df9-177">Excel stürzt möglicherweise unter bestimmten Umständen ab, wenn zwischen den Arbeitsmappen mit anderen Zoomstufen gewechselt wird.</span><span class="sxs-lookup"><span data-stu-id="19df9-177">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="19df9-178">Es wurde ein Problem mit VBA behoben, bei dem das Schreiben von Werten in einem Wertebereich langsamer als erwartet war.</span><span class="sxs-lookup"><span data-stu-id="19df9-178">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="19df9-179">Daten, die aus einer nach Farbe gefilterten Spalte kopiert wurden, werden manchmal nicht ordnungsgemäß eingefügt.</span><span class="sxs-lookup"><span data-stu-id="19df9-179">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="19df9-180">Ein Problem wurde behoben, bei dem Excel in manchen Fällen abstürzte, nachdem ein Blatt mit einer PivotTable kopiert wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-180">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="19df9-181">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-181">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="19df9-182">Es wurde ein Problem behoben, bei dem die Eigenschaft "Wert wird überschneidet bei" auf der Diagrammachse unerwartet geändert wird, wenn Sie eine Datei speichern und erneut öffnen.</span><span class="sxs-lookup"><span data-stu-id="19df9-182">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="19df9-183">Die Verwendung von Range.Value und Range.Value2 (VBA) würde dazu führen, dass Formeln als dynamische Arrays eingegeben werden.</span><span class="sxs-lookup"><span data-stu-id="19df9-183">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="19df9-184">OneNote</span><span class="sxs-lookup"><span data-stu-id="19df9-184">OneNote</span></span>

- <span data-ttu-id="19df9-185">Lokalisiert die Benachrichtigung, durch die der Benutzer mehr über temporäre Maßnahmen erfahren kann, die in der OneNote-Benutzeroberfläche implementiert sind, um die Synchronisierungs- und Dienststabilität zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="19df9-185">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="19df9-186">Zeigt eine Benachrichtigung an, durch die der Benutzer mehr über temporäre Maßnahmen erfahren kann, die in der OneNote-Benutzeroberfläche implementiert sind, um die Synchronisierungs- und Dienststabilität zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="19df9-186">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="19df9-187">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehendes verringern der Anzahl und Häufigkeit der Synchronisierungen von Seiten des Versionsverlaufs in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="19df9-187">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="19df9-188">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehende Deaktivierung des Papierkorbs in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="19df9-188">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="19df9-189">Wenn ein Benutzer versucht, die Daten zu löschen, die normalerweise in den Papierkorb verschoben werden, wird der Benutzer gefragt, ob er die Daten beibehalten oder dauerhaft löschen möchte.</span><span class="sxs-lookup"><span data-stu-id="19df9-189">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="19df9-190">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehende Anpassung der Synchronisierungshäufigkeit in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="19df9-190">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="19df9-191">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehendes zurückschieben des Downloads eingebetteter Dateien und Bilder in Online-Notizbücher, bis der Benutzer zu der Seite in OneNote 2016 navigiert.</span><span class="sxs-lookup"><span data-stu-id="19df9-191">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="19df9-192">Verbesserte Synchronisierungs- und Servicestabilität durch vorübergehende Deaktivierung der Videoaufzeichnung in der Anwendung in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="19df9-192">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="19df9-193">Lokale Notizbücher sind von dieser Maßnahme nicht betroffen.</span><span class="sxs-lookup"><span data-stu-id="19df9-193">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="19df9-194">Verbesserte Synchronisierungs- und Servicestabilität durch vorübergehende Reduzierung der maximal zulässigen Größe neuer eingebetteter Anhänge auf 50 MB in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="19df9-194">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="19df9-195">Bei Dateien, die dieses Limit überschreiten, haben Benutzer die Möglichkeit, die Datei auf OneDrive hochzuladen und einen Link in OneNote einzufügen.</span><span class="sxs-lookup"><span data-stu-id="19df9-195">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="19df9-196">Outlook</span><span class="sxs-lookup"><span data-stu-id="19df9-196">Outlook</span></span>

- <span data-ttu-id="19df9-197">Ein Problem wurde behoben, bei dem die Breite des Ordnerbereichs unerwartet geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-197">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="19df9-198">Es wurde ein Problem behoben, das bewirkt, dass Benutzer beim Öffnen von .msg- und .oft-Dateien nach einem Windows-Update einen Absturz erfahren.</span><span class="sxs-lookup"><span data-stu-id="19df9-198">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="19df9-199">Behebt ein Problem, das dazu führte, dass Benutzer beim Weiterleiten großer HTML-Nachrichten den Nachrichtentext abgeschnitten sahen.</span><span class="sxs-lookup"><span data-stu-id="19df9-199">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="19df9-200">Dieses Update behebt ein Problem, bei dem Microsoft Outlook beim Anzeigen oder Verfassen von Nachrichten nicht die aktuelle Vertraulichkeitskennzeichnung anzeigt.</span><span class="sxs-lookup"><span data-stu-id="19df9-200">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="19df9-201">Es wurde ein Problem behoben, aufgrund dessen Benutzer nicht in der Lage waren, E-Mails an eine persönliche Verteilerliste zu senden.</span><span class="sxs-lookup"><span data-stu-id="19df9-201">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19df9-202">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19df9-202">PowerPoint</span></span>

- <span data-ttu-id="19df9-203">Es wurde ein Problem mit der Weiterleitung von korrekten Nachrichten für Benutzer behoben, die eine Kopie einer Datei mit verbesserten Kommentaren öffnen.</span><span class="sxs-lookup"><span data-stu-id="19df9-203">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="19df9-204">Word</span><span class="sxs-lookup"><span data-stu-id="19df9-204">Word</span></span>

- <span data-ttu-id="19df9-205">Es wurde ein Problem behoben, bei dem Access und Publisher nicht ordnungsgemäß gestartet werden, je nachdem, welche Sprachen installiert wurden.</span><span class="sxs-lookup"><span data-stu-id="19df9-205">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="19df9-206">Es wurde ein Problem mit der compare-Funktion für Dokumente behoben, die für die Bearbeitung geschützt waren.</span><span class="sxs-lookup"><span data-stu-id="19df9-206">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="19df9-207">Es wurde ein Problem beim Zusammenführen von 2 Dokumenten in ein Dokument behoben.</span><span class="sxs-lookup"><span data-stu-id="19df9-207">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="19df9-208">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="19df9-208">Office Suite</span></span>

- <span data-ttu-id="19df9-209">Diese Behebung soll sicherstellen, dass die Projektanwendung das Netzwerk nicht blockiert, wenn die Datei im Cache des Clients gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="19df9-209">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="19df9-210">Das Problem wurde behoben, bei dem ein interner Vorgang bei einem Fehler eine Ausnahme ausgelöst hat, anstatt diesen zu protokollieren und fortzufahren.</span><span class="sxs-lookup"><span data-stu-id="19df9-210">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="19df9-211">Die betroffenen Benutzer werden nicht mehr daran gehindert, Updates zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="19df9-211">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="19df9-212">Dadurch wird sichergestellt, dass skizzierte Konturen im Menüband ordnungsgemäß funktionieren.</span><span class="sxs-lookup"><span data-stu-id="19df9-212">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="19df9-213">Es wurde ein Problem beim Öffnen von Dateien von lokalen Standorten aus mit einigen bestimmten Proxykonfigurationen behoben.</span><span class="sxs-lookup"><span data-stu-id="19df9-213">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="19df9-214">Dieses Update behebt ein Problem in Visual Basic for Applications in Microsoft Office, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung beim Laden als fehlerhaft angesehen werden.</span><span class="sxs-lookup"><span data-stu-id="19df9-214">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="19df9-215">Das Update behebt ein Problem in Microsoft Office, bei dem Visual Basic for Applications-Projekte mit Referenzen, die bei der Suche nach in der PATH-Umgebungsvariable angegebenen Speicherorten gefunden werden sollen, zur Laufzeit möglicherweise nicht richtig gefunden werden, was zu VBA-Laufzeitfehlern führt.</span><span class="sxs-lookup"><span data-stu-id="19df9-215">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="19df9-216">Dieses Update behebt ein Problem in Microsoft Word, bei dem Text, der länger als 255 Zeichen ist, während die Anwendung einer Vertraulichkeitskennzeichnung eingefügt wird, später nicht identifiziert und entfernt werden konnte, wenn die Kennzeichnungsrichtlinie eine Kopf- oder Fußzeile oder ein Wasserzeichen angewendet hat.</span><span class="sxs-lookup"><span data-stu-id="19df9-216">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="19df9-217">Es wurde ein Problem behoben, durch das Abstürze während der Office-Übergabesitzungen eliminiert, und es wurde die Zuverlässigkeit der Benutzeroberfläche erhöht.</span><span class="sxs-lookup"><span data-stu-id="19df9-217">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="19df9-218">Dieser Fehler aktualisiert den Enhanced Configuration Service (ECS).</span><span class="sxs-lookup"><span data-stu-id="19df9-218">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="19df9-219">Das Aufrufen von diesem neueren Endpunkt aus hat eine höhere Erfolgsrate für den Abruf aus ECS.</span><span class="sxs-lookup"><span data-stu-id="19df9-219">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-april-14"></a><span data-ttu-id="19df9-221">Version 2002: 14. April</span><span class="sxs-lookup"><span data-stu-id="19df9-221">Version 2002: April 14</span></span>
<span data-ttu-id="19df9-222">*Version 2002 (Build 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="19df9-222">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="19df9-223">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="19df9-223">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="19df9-224">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="19df9-224">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="19df9-225">Excel</span><span class="sxs-lookup"><span data-stu-id="19df9-225">Excel</span></span>

- <span data-ttu-id="19df9-226">**Geben Sie eine Formel ein, die mehrere Werte zurückgibt:** Geben Sie schnell eine Formel ein, die mehrere Werte zurückgibt, und diese werden automatisch in die benachbarten Zellen übertragen.</span><span class="sxs-lookup"><span data-stu-id="19df9-226">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="19df9-227">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-227">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="19df9-228">**Sechs leistungsfähige Funktionen:** Wir haben sechs neue Funktionen hinzugefügt, um Ihre Tabellenkalkulationen hochgradig zu optimieren: FILTERN, SORTIEREN, SORTIERENNACH, EINDEUTIG, SEQUENZ und ZUFALLSMATRIX.</span><span class="sxs-lookup"><span data-stu-id="19df9-228">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="19df9-229">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-229">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="19df9-230">**Schau nach links, schau nach rechts... XVERWEIS ist da!:** Finden Sie mit XVERWEIS Zeile für Zeile alles, was Sie in einer Tabelle oder einem Bereich benötigen.</span><span class="sxs-lookup"><span data-stu-id="19df9-230">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  [<span data-ttu-id="19df9-231">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-231">Learn more</span></span>](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="19df9-233">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="19df9-233">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="19df9-234">Excel</span><span class="sxs-lookup"><span data-stu-id="19df9-234">Excel</span></span>

- <span data-ttu-id="19df9-235">Excel stürzt in bestimmten Fällen ab, wenn eine in Word oder PowerPoint eingebettete Arbeitsmappe erneut geöffnet wird.</span><span class="sxs-lookup"><span data-stu-id="19df9-235">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="19df9-236">Beim Speichern als CSV-Datei hat Excel in einigen Fällen alle Spalten in einer einzigen Spalte zusammengeführt.</span><span class="sxs-lookup"><span data-stu-id="19df9-236">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="19df9-237">Die Verwendung von Range.ClearContents für einen Bereich auf einem geschützten Blatt hat möglicherweise länger gedauert als erwartet.</span><span class="sxs-lookup"><span data-stu-id="19df9-237">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="19df9-238">Es wurde ein Problem beim Skalieren von Text in Steuerelementen von Formularen beim Anzeigen in der Druckansicht behoben.</span><span class="sxs-lookup"><span data-stu-id="19df9-238">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="19df9-239">VBA-Makros, die mit dem Menüband interagieren, können möglicherweise mit ScreenUpdating unerwartet auf „Wahr“ festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="19df9-239">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="19df9-240">Es wurde ein Problem behoben, bei dem externe Links beim Füllen(abwärts füllen, übergreifend füllen usw.) nicht aktualisiert wurden, wenn das Quellbuch geschlossen war.</span><span class="sxs-lookup"><span data-stu-id="19df9-240">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="19df9-241">Die Verwendung des VBA-Befehls Application.Evaluate funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.</span><span class="sxs-lookup"><span data-stu-id="19df9-241">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="19df9-242">Es wurde ein Leistungsproblem beim Erstellen von Diagrammen aus Vorlagen behoben.</span><span class="sxs-lookup"><span data-stu-id="19df9-242">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="19df9-243">Outlook</span><span class="sxs-lookup"><span data-stu-id="19df9-243">Outlook</span></span>

- <span data-ttu-id="19df9-244">Es wurde ein Problem behoben, das dazu führte, dass die Kopfzeile einer Gruppe in einigen Szenarios unerwartet erweitert wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-244">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="19df9-245">Es wurde ein Problem behoben, bei dem es zu einem Absturz kam, wenn Benutzer bestimmte Ergebnisse ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="19df9-245">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="19df9-246">Es wurde ein Problem behoben, das gelegentlich zu einem Absturz führte, wenn Benutzer den X-Knopf ihrer Maus verwendeten.</span><span class="sxs-lookup"><span data-stu-id="19df9-246">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="19df9-247">Es wurde ein Problem behoben, das bewirkt hat, dass die Schaltfläche „In der Cloud speichern“ in den Tools für Anlagen fehlte.</span><span class="sxs-lookup"><span data-stu-id="19df9-247">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19df9-248">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19df9-248">PowerPoint</span></span>

- <span data-ttu-id="19df9-249">Verbessertes Szenario zum Kopieren und Einfügen: Das Kopieren der Form in eine PowerPoint-Folie und das Einfügen in eine andere Folie in einer Schleife schlägt möglicherweise mit Ausnahme fehl.</span><span class="sxs-lookup"><span data-stu-id="19df9-249">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="19df9-250">Project</span><span class="sxs-lookup"><span data-stu-id="19df9-250">Project</span></span>

- <span data-ttu-id="19df9-251">Ein Problem wurde behoben, bei dem Project beim Speichern von Projekten, die mit älteren Project-Versionen erstellt wurden, möglicherweise abstürzt.</span><span class="sxs-lookup"><span data-stu-id="19df9-251">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="19df9-252">Ein Problem wurde behoben, bei dem das Ereignis „ProjectBeforeTaskChange“ nichts erkennt, wenn ein Vorgang über die Schaltfläche „Deaktivieren“ deaktiviert/aktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-252">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="19df9-253">Word</span><span class="sxs-lookup"><span data-stu-id="19df9-253">Word</span></span>

- <span data-ttu-id="19df9-254">Es wurde ein Problem behoben, das gelegentlich zu einem Absturz führte, wenn Benutzer den X-Knopf ihrer Maus verwendeten.</span><span class="sxs-lookup"><span data-stu-id="19df9-254">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="19df9-255">Es wurde ein Problem mit der Anpassung von Text in einer Tabelle behoben.</span><span class="sxs-lookup"><span data-stu-id="19df9-255">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="19df9-256">Ein Problem wurde behoben, damit eingefügte horizontale Linien nicht kürzer und zentriert sind.</span><span class="sxs-lookup"><span data-stu-id="19df9-256">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-march-10"></a><span data-ttu-id="19df9-258">Version 2002: 10. März</span><span class="sxs-lookup"><span data-stu-id="19df9-258">Version 2002: March 10</span></span>
<span data-ttu-id="19df9-259">*Version 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="19df9-259">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="19df9-260">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="19df9-260">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="19df9-262">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="19df9-262">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="19df9-263">Access</span><span class="sxs-lookup"><span data-stu-id="19df9-263">Access</span></span>

- <span data-ttu-id="19df9-264">**Schnelle Suche nach verknüpften Tabellen:** Unser neues Suchfeld macht die Suche nach verknüpften Tabellen zu einem Kinderspiel.</span><span class="sxs-lookup"><span data-stu-id="19df9-264">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="19df9-265">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-265">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="19df9-266">Excel</span><span class="sxs-lookup"><span data-stu-id="19df9-266">Excel</span></span>

- <span data-ttu-id="19df9-267">**Mit \@Erwähnen andere auf sich aufmerksam machen:** Mithilfe von Erwähnungen in Kommentaren können Sie Kollegen informieren, wenn Sie deren Input benötigen.</span><span class="sxs-lookup"><span data-stu-id="19df9-267">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="19df9-268">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-268">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="19df9-269">**Finden Sie, wonach Sie suchen:** Suchen Sie Befehle, Personen, Dateien, Fotos, Webartikel und mehr.</span><span class="sxs-lookup"><span data-stu-id="19df9-269">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="19df9-270">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-270">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="19df9-271">**Zeichnen Sie es auf:** Verleihen Sie Office-Shapes in Ihrer Arbeitsmappe ein ungezwungenes, von Hand gezeichnetes Aussehen.</span><span class="sxs-lookup"><span data-stu-id="19df9-271">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="19df9-272">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-272">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="19df9-273">**Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="19df9-273">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="19df9-274">**Keine Umleitung zum Browser mehr:** Sie legen fest, wie Links zu Office-Dokumenten geöffnet werden: im Browser oder in der App.</span><span class="sxs-lookup"><span data-stu-id="19df9-274">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="19df9-275">**Konzentrieren Sie sich darauf, was noch erledigt werden muss:** Wählen Sie "Auflösen" aus, um Kommentare zu reduzieren und offene Punkte hervorzuheben.</span><span class="sxs-lookup"><span data-stu-id="19df9-275">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="19df9-276">**Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten.</span><span class="sxs-lookup"><span data-stu-id="19df9-276">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="19df9-277">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-277">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="19df9-278">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="19df9-278">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="19df9-279">\*\*Add-In „Datenschnellansicht“: \*\* erstellen Sie schnell Visio-Flussdiagramme aus Excel.</span><span class="sxs-lookup"><span data-stu-id="19df9-279">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="19df9-280">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-280">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="19df9-281">**Schnell lesen und antworten:** Antworten Sie auf Kommentare und Erwähnungen direkt aus dem E-Mail-Bereich, ohne die Arbeitsmappe zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="19df9-281">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="19df9-282">**Statistiken für Ihre Arbeitsmappe abrufen:** Arbeitsmappenstatistiken bieten einen Überblick über den Inhalt einer Arbeitsmappe, um Ihnen das Erkunden des Inhalts zu erleichtern.</span><span class="sxs-lookup"><span data-stu-id="19df9-282">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="19df9-283">**Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="19df9-283">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="19df9-284">Sie finden diese unter "Einfügen" > "Symbole".</span><span class="sxs-lookup"><span data-stu-id="19df9-284">Find them at Insert > Icons.</span></span> [<span data-ttu-id="19df9-285">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-285">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="19df9-286">Outlook</span><span class="sxs-lookup"><span data-stu-id="19df9-286">Outlook</span></span>

- <span data-ttu-id="19df9-287">**Verbinden Ihres LinkedIn-Netzwerks mit Outlook:** Stellen Sie eine sichere Verbindung zwischen Ihrem LinkedIn-Konto und Ihrem Microsoft-Konto her, um Informationen aus LinkedIn-Profilen direkt auf der Karte mit Ihren Kontakten anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="19df9-287">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="19df9-288">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-288">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="19df9-p120">**Alle Verschlüsselungsoptionen an einem zentralen Ort:** Gehen Sie einfach zu Optionen > Verschlüsseln, um auszuwählen, wie Ihre E-Mail-Nachricht gesichert wird. [Weitere Informationen](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="19df9-p120">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="19df9-291">**Das Menü „Link einfügen“ in Outlook fügt einen Link mit der vom Mandantenadministrator festgelegten Berechtigung ein:** Ein Link aus dem Link-Einfügen-MRU in Outlook fügte einen Link ein, der nur für diejenigen Benutzer funktionierte, die bereits eine Berechtigung besaßen.</span><span class="sxs-lookup"><span data-stu-id="19df9-291">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="19df9-292">Dies führte häufig zu E-Mail-Nachrichten zwischen Benutzern, die den Zugriff auf ein Dokument anforderten.</span><span class="sxs-lookup"><span data-stu-id="19df9-292">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="19df9-293">Wir haben diese Erfahrung aktualisiert, sodass der Link jetzt mit der vom Mandantenadministrator festgelegten Standardberechtigung eingefügt wird. Für MSIT ist dies "Organisation kann bearbeiten", sodass alle internen Benutzer, die einen auf diese Weise freigegebenen Link erhalten, darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="19df9-293">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="19df9-294">**Suchen bei Rechtschreibschwierigkeiten oder mit Tippfehlern:** Outlook wird auch dann finden, was Sie suchen, wenn Sie sich verschreiben.</span><span class="sxs-lookup"><span data-stu-id="19df9-294">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="19df9-295">**Phishing-E-Mails sind jetzt leicht zu erkennen:** Spam- und Phishing-E-Mails haben ein anderes Aussehen und Verhalten, sodass Sie sie leichter identifizieren und aus Ihrem Posteingang entfernen können.</span><span class="sxs-lookup"><span data-stu-id="19df9-295">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="19df9-296">**Erweiterter Schutz gegen Angriffe:** Mit Office 365 Advanced Threat Protection sind Sie vor Angriffen durch Links in E-Mail-Betreffzeilen, angefügten Nachrichten, signierten Nachrichten, Netzwerkpfaden usw. geschützt.</span><span class="sxs-lookup"><span data-stu-id="19df9-296">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="19df9-297">**Müheloses Zeichnen und Signieren:** Kritzeln Sie über die Bilder, oder fügen Sie einen Zeichenbereich hinzu, um Ihren Gedanken als Freihandnotizen Ausdruck zu verleihen.</span><span class="sxs-lookup"><span data-stu-id="19df9-297">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="19df9-298">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-298">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="19df9-299">**Finden Sie relevante Nachrichten in Ihren Suchergebnissen:** Outlook analysiert Suchbegriffe und zeigt die wichtigsten E-Mail-Nachrichten am Anfang der Suchergebnisse an.</span><span class="sxs-lookup"><span data-stu-id="19df9-299">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="19df9-300">Außerdem sehen Sie alle Ergebnisse sortiert nach Datum im Abschnitt „Top-Ergebnisse“.</span><span class="sxs-lookup"><span data-stu-id="19df9-300">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="19df9-301">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-301">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="19df9-302">**Erhalten Sie Ortsvorschläge:** Beginnen Sie beim Planen von Terminen und Besprechungen mit der Eingabe im Feld „Ort“, so schlägt Outlook Räume, Adressen und andere zuletzt verwendete Orte vor.</span><span class="sxs-lookup"><span data-stu-id="19df9-302">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="19df9-303">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-303">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="19df9-304">**Mehr Nachrichten am Bildschirm anzeigen:** Wählen Sie "Anzeigen" > Engere Abstände verwenden, um die Abstände zwischen den Nachrichten anzupassen.</span><span class="sxs-lookup"><span data-stu-id="19df9-304">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="19df9-305">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-305">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="19df9-306">**Sehen Sie Ihre Nachrichten in einem neuen Licht:** Verwenden Sie die Sonne/Mond-Schaltfläche, um im Lesebereich zwischen hellem und dunklem Hintergrund zu wechseln.</span><span class="sxs-lookup"><span data-stu-id="19df9-306">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="19df9-307">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-307">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="19df9-308">**Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="19df9-308">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="19df9-309">Sie finden diese unter "Einfügen" > "Symbole".</span><span class="sxs-lookup"><span data-stu-id="19df9-309">Find them at Insert > Icons.</span></span> [<span data-ttu-id="19df9-310">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-310">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="19df9-311">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19df9-311">PowerPoint</span></span>

- <span data-ttu-id="19df9-312">**Schnelle Zusammenarbeit in Echtzeit in PowerPoint:** Schnelle Zusammenarbeit in Echtzeit in PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19df9-312">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="19df9-313">**Neue Tools zum Korrekturlesen:** Machen Sie sich keine Sorgen mehr über Ihre Texte.</span><span class="sxs-lookup"><span data-stu-id="19df9-313">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="19df9-314">PowerPoint bietet jetzt Grammatik- und Textvorschläge.</span><span class="sxs-lookup"><span data-stu-id="19df9-314">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="19df9-315">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-315">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="19df9-316">**Live-Beschriftungen und -Untertitel:** die Worte des Referenten werden automatisch als Beschriftungen oder Untertitel in der von Ihnen gewünschten Sprache auf dem Bildschirm angezeigt.</span><span class="sxs-lookup"><span data-stu-id="19df9-316">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="19df9-317">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-317">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="19df9-p130">**Sie berechnen, wir formatieren:** Von Hand gezeichnete mathematische Ausdrücke werden in Standardzeichen umgewandelt. Wählen Sie einfach "Freihand in Gleichung" und Ihre handschriftlichen Notizen aus, um loszulegen. [Weitere Informationen](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="19df9-p130">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="19df9-321">**Finden Sie, wonach Sie suchen:** Verwenden Sie das Suchfeld, um Text, Befehle, Hilfe und mehr zu finden.</span><span class="sxs-lookup"><span data-stu-id="19df9-321">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="19df9-322">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-322">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="19df9-323">**Suchen und Beheben von fehlenden Folientiteln:** Folientitel verleihen Ihrem Pitch mehr Nachdruck und machen Ihre Folien für Benutzer mit unterschiedlichen Fähigkeiten zugänglich.</span><span class="sxs-lookup"><span data-stu-id="19df9-323">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="19df9-324">Die Barrierefreiheitsprüfung zeigt Ihnen, wo Titel fehlen, damit Sie diese schnell hinzufügen können.</span><span class="sxs-lookup"><span data-stu-id="19df9-324">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="19df9-325">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-325">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="19df9-326">**Zeichnen Sie es auf:** Verleihen Sie Office-Shapes in Ihrer Präsentation ein ungezwungenes, von Hand gezeichnetes Aussehen.</span><span class="sxs-lookup"><span data-stu-id="19df9-326">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="19df9-327">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-327">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="19df9-328">**Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="19df9-328">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="19df9-329">**Keine Umleitung zum Browser mehr:** Sie legen fest, wie Links zu Office-Dokumenten geöffnet werden: im Browser oder in der App.</span><span class="sxs-lookup"><span data-stu-id="19df9-329">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="19df9-330">**Speichern einer Illustration als SVG:** Speichern Sie ein Diagramm, eine Form oder eine andere Abbildung als skalierbare Vektorgrafik, deren Größe ohne Verlust der Bildqualität geändert werden kann.</span><span class="sxs-lookup"><span data-stu-id="19df9-330">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="19df9-331">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-331">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="19df9-332">**Drucken von Foliennummern auf Handzetteln:** Foliennummern werden automatisch in Ihre Handzettel integriert.</span><span class="sxs-lookup"><span data-stu-id="19df9-332">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="19df9-333">Sie können diese Funktion an- oder abschalten, wie es Ihnen beliebt.</span><span class="sxs-lookup"><span data-stu-id="19df9-333">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="19df9-334">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-334">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="19df9-335">**Wiedergabe von animierten Freihandzeichnungen:** Wenn Sie Freihandeingaben auf Ihren Folien vornehmen, können Sie auf diese Freihandeingaben Replay-Animationen anwenden, um den eigentlichen Zeichenvorgang während der Bildschirmpräsentation wiederzugeben.</span><span class="sxs-lookup"><span data-stu-id="19df9-335">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="19df9-336">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-336">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="19df9-337">**Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten.</span><span class="sxs-lookup"><span data-stu-id="19df9-337">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="19df9-338">**Optimieren Sie Ihre Präsentation für alle:** Die Barrierefreiheitsprüfung hilft Ihnen beim Anordnen von Objekten auf Ihren Folien, indem sie die Sprachausgabe berücksichtigt.</span><span class="sxs-lookup"><span data-stu-id="19df9-338">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="19df9-339">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="19df9-339">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="19df9-340">**Eine sicherere Video-Umgebung:** Security-Verbesserungen bedeuten für Sie eine sicherere Online-Video-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="19df9-340">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="19df9-341">**Warum neu erstellen, wenn Sie etwas wiederverwenden können?** Sparen Sie Zeit, indem Sie Folien, die Sie erstellt haben oder die andere für Sie freigegeben haben, erneut verwenden.</span><span class="sxs-lookup"><span data-stu-id="19df9-341">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="19df9-342">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-342">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="19df9-343">**Ändern der handschriftlichen Freihandeingabe in Formen, Text oder Mathematik in PowerPoint für Office 365:** Wechseln Sie mit wenigen Strichen von der Freihandeingabe zu Office-Formen, Text oder einem mathematischen Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="19df9-343">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="19df9-344">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-344">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="19df9-345">**Erstellen Sie eine hervorragende Folie:** Konvertieren Sie Ihre Freihandeingaben in Standardformen und -text, und lassen Sie sich dann von PowerPoint-Designer intelligente Folienentwurfsideen anzeigen.</span><span class="sxs-lookup"><span data-stu-id="19df9-345">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="19df9-346">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-346">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="19df9-347">**Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="19df9-347">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="19df9-348">Sie finden diese unter "Einfügen" > "Symbole".</span><span class="sxs-lookup"><span data-stu-id="19df9-348">Find them at Insert > Icons.</span></span> [<span data-ttu-id="19df9-349">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-349">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="19df9-350">Visio</span><span class="sxs-lookup"><span data-stu-id="19df9-350">Visio</span></span>

- <span data-ttu-id="19df9-351">**Zurück zum Tatort:** Verwenden Sie die neuen Schablonen "Beweismittel", "Drinnen" und "Draußen" der Vorlage "Tatortermittlung", um Tatorte im Detail nachzustellen.</span><span class="sxs-lookup"><span data-stu-id="19df9-351">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="19df9-352">\*\* Erstellen Sie ansprechende Visio-Diagramme in Excel:\*\* Erstellen Sie ein Flussdiagramm oder ein Organigramm durch Einfügen von Daten in ein Arbeitsblatt.</span><span class="sxs-lookup"><span data-stu-id="19df9-352">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="19df9-353">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-353">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="19df9-354">Word</span><span class="sxs-lookup"><span data-stu-id="19df9-354">Word</span></span>

- <span data-ttu-id="19df9-355">**Lebenslauf-Editor-Verknüpfung mit dem LinkedIn-Lebenslauf-Assistent:** Der Lebenslauf-Editor bietet eine Auswahl an Grammatik- und Stilprüfungen, die speziell auf Lebensläufe zugeschnitten sind, um Ihr Schreiben präziser und professioneller zu gestalten.</span><span class="sxs-lookup"><span data-stu-id="19df9-355">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="19df9-356">**Es wurde ein Problem mit beschädigten Dokumenten behoben, das durch das Zusammenführen von 3D-Objekten verursacht wurde:** Es wurde ein Problem mit beschädigten Dokumenten behoben, das durch das Zusammenführen von 3D-Objekten verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-356">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="19df9-357">**Finden Sie, wonach Sie suchen:** Verwenden Sie das Suchfeld, um Text, Befehle, Hilfe und mehr zu finden.</span><span class="sxs-lookup"><span data-stu-id="19df9-357">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="19df9-358">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-358">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="19df9-359">**Zusammenarbeit in lebendigen Farben:** Kommentare und Änderungen sind nach Verfasser farblich gekennzeichnet, sodass Sie die einzelnen Mitwirkenden leichter unterscheiden können.</span><span class="sxs-lookup"><span data-stu-id="19df9-359">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="19df9-360">**Makrofähige Dokumente gemeinsam bearbeiten:** Speichern Sie Ihre Dokumentdateien auf OneDrive for Business, und bearbeiten Sie sie mit anderen in Echtzeit.</span><span class="sxs-lookup"><span data-stu-id="19df9-360">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="19df9-361">**Verbesserungen bei der gemeinsamen Dokumenterstellung**: verbesserte Leistung von Word bei der gemeinsamen Dokumenterstellung mit nachverfolgbaren Änderungen.</span><span class="sxs-lookup"><span data-stu-id="19df9-361">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="19df9-362">**Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="19df9-362">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="19df9-363">Sie finden diese unter "Einfügen" > "Symbole".</span><span class="sxs-lookup"><span data-stu-id="19df9-363">Find them at Insert > Icons.</span></span> [<span data-ttu-id="19df9-364">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-364">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="19df9-365">**Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.</span><span class="sxs-lookup"><span data-stu-id="19df9-365">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="19df9-366">**Zeichnen Sie es auf:** Verleihen Sie Office-Shapes in Ihrem Dokument ein ungezwungenes, von Hand gezeichnetes Aussehen.</span><span class="sxs-lookup"><span data-stu-id="19df9-366">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="19df9-367">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-367">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="19df9-368">**Präzises Löschen:** Wählen Sie aus zwei Radierergrößen aus, um kleine Unvollkommenheiten zu beheben.</span><span class="sxs-lookup"><span data-stu-id="19df9-368">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="19df9-369">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-369">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="19df9-370">**Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="19df9-370">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="19df9-371">**Keine Umleitung zum Browser mehr:** Sie legen fest, wie Links zu Office-Dokumenten geöffnet werden: im Browser oder in der App.</span><span class="sxs-lookup"><span data-stu-id="19df9-371">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="19df9-372">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-372">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="19df9-373">**Verbesserungen bei der gemeinsamen Dokumenterstellung:** Verbesserte Zuverlässigkeit bei der gemeinsamen Dokumenterstellung.</span><span class="sxs-lookup"><span data-stu-id="19df9-373">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="19df9-374">**Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten.</span><span class="sxs-lookup"><span data-stu-id="19df9-374">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="19df9-375">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-375">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="19df9-376">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="19df9-376">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="19df9-377">**Eine sicherere Video-Umgebung:** Security-Verbesserungen bedeuten für Sie eine sicherere Online-Video-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="19df9-377">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="19df9-378">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="19df9-378">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="19df9-381">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="19df9-381">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="19df9-382">Access</span><span class="sxs-lookup"><span data-stu-id="19df9-382">Access</span></span>

- <span data-ttu-id="19df9-383">Mit diesem Update wird ein Problem in Microsoft Access behoben, das den Fehler &quot;Abfrage ist beschädigt&quot; verursachen kann, wenn eine Aktualisierungsabfrage ausgeführt oder eine UPDATE-Anweisung in SQL verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="19df9-383">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="19df9-384">Dieses Update behebt ein Problem, das dazu führen kann, dass Microsoft Access eine Identitätsspalte in einer verknüpften SQL-Server-Tabelle nicht identifiziert, was dazu führen kann, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.</span><span class="sxs-lookup"><span data-stu-id="19df9-384">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="19df9-385">Dieses Update behebt ein Problem bei der Verwendung von ADODB.</span><span class="sxs-lookup"><span data-stu-id="19df9-385">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="19df9-386">Das Recorder-Objekt im VB-Code meldet möglicherweise einen Fehler falsch.</span><span class="sxs-lookup"><span data-stu-id="19df9-386">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="19df9-387">Access-Vorlagen sollten nicht länger dazu führen, dass Anhangsspalten in einer Datenbank fehlschlagen.</span><span class="sxs-lookup"><span data-stu-id="19df9-387">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="19df9-388">Nachdem Sie eine Vorlage instanziiert haben, sollten Sie nun in der Lage sein, Ihrer Datenbank ein Anhangsfeld hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="19df9-388">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="19df9-389">Excel</span><span class="sxs-lookup"><span data-stu-id="19df9-389">Excel</span></span>

- <span data-ttu-id="19df9-390">Es wurde ein Problem behoben, aufgrund dessen bei Benutzern Abstürze beim Umbenennen einer Signatur auftraten.</span><span class="sxs-lookup"><span data-stu-id="19df9-390">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="19df9-391">Diese Änderung umgeht ein Problem mit bestimmten Intel-Grafiktreibern durch Verwendung des Softwarerenderings.</span><span class="sxs-lookup"><span data-stu-id="19df9-391">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="19df9-392">Es wurde ein Problem behoben, durch das bei einigen Benutzern Abstürze auftraten, wenn Text in Spalten mit Zellen mit einem übergelaufenem Array konvertiert wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-392">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="19df9-393">Dieses Update behebt ein Problem, das dazu führte, dass die Bearbeitungsleiste Text in einer anderen Schriftart als erwartet anzeigte.</span><span class="sxs-lookup"><span data-stu-id="19df9-393">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="19df9-394">Die Funktion "Text in Spalte" funktioniert bei einigen Gebietsschemas möglicherweise nicht.</span><span class="sxs-lookup"><span data-stu-id="19df9-394">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="19df9-395">Beim Zugriff auf einen verborgenen benannten Bereich kann ein Fehler auftreten.</span><span class="sxs-lookup"><span data-stu-id="19df9-395">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="19df9-396">Beim Speichern von Änderungen bei der Verwendung einiger nicht englischer Zeichengruppen tritt möglicherweise ein Fehler auf.</span><span class="sxs-lookup"><span data-stu-id="19df9-396">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="19df9-397">Wir haben ein Problem gelöst, durch das das Auswählen einer Zelle nach dem Scrollen dazu führen konnte, dass die falsche Zelle ausgewählt wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-397">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="19df9-398">In Excel kann ein Problem auftreten, durch das das Bearbeiten einer geschützten Datei von einer nicht vertrauenswürdigen Netzwerkfreigabe zu einem Fehler in Excel führt.</span><span class="sxs-lookup"><span data-stu-id="19df9-398">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="19df9-399">Die Funktion "Text in Spalte" funktioniert bei einigen Lokalisierungen möglicherweise nicht.</span><span class="sxs-lookup"><span data-stu-id="19df9-399">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="19df9-400">Beim Zugriff auf einen verborgenen benannten Bereich kann ein Fehler auftreten.</span><span class="sxs-lookup"><span data-stu-id="19df9-400">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="19df9-401">Beim Speichern von Änderungen bei der Verwendung einiger nicht englischer Zeichengruppen tritt möglicherweise ein Fehler auf.</span><span class="sxs-lookup"><span data-stu-id="19df9-401">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="19df9-402">Es wurde ein Problem behoben, das bei einigen Benutzern mit verknüpften und eingebetteten Objekten (OLE) auftrat.</span><span class="sxs-lookup"><span data-stu-id="19df9-402">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="19df9-403">Das Kontextmenü für PivotCharts wurde korrigiert, um die Option "Details anzeigen" zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="19df9-403">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="19df9-404">Es wurde ein Problem behoben, das bei der Suche nach zuletzt verwendeten Dateien zu einem Absturz geführt hat, wenn keine Arbeitsmappe geöffnet ist.</span><span class="sxs-lookup"><span data-stu-id="19df9-404">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="19df9-405">Es wurde ein Problem behoben, durch das einigen Benutzern mehrere Popupfenster angezeigt wurden, wenn externe Links in der Arbeitsmappe vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="19df9-405">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="19df9-406">Es wurde ein Problem behoben, bei dem Kommentarbefehle im Kontextmenü nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="19df9-406">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="19df9-407">Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-407">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="19df9-408">Ein Problem wurde behoben, bei dem CUBEWERT-Funktionen manchmal ein falsches Ergebnis zurückgaben.</span><span class="sxs-lookup"><span data-stu-id="19df9-408">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="19df9-409">Outlook</span><span class="sxs-lookup"><span data-stu-id="19df9-409">Outlook</span></span>

- <span data-ttu-id="19df9-410">Es wurde ein Problem behoben, durch das die Such-Feedback-Umgebung zum Hängen gebracht wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-410">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="19df9-411">Es wurde ein Problem behoben, das dazu führte, dass Benutzer in Outlook beim Abrufen von Cloudeinstellungen hängen bleiben.</span><span class="sxs-lookup"><span data-stu-id="19df9-411">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="19df9-412">Es wurde ein Problem behoben, das dazu führte, dass das Suchfeld im Modus mit hohem DPI-Wert nicht korrekt ausgerichtet war.</span><span class="sxs-lookup"><span data-stu-id="19df9-412">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="19df9-413">Ein Problem wurde behoben, durch das Benutzer einen Speicherverlust im Outlook-Prozess beobachten konnten.</span><span class="sxs-lookup"><span data-stu-id="19df9-413">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="19df9-414">Es wurde ein Problem behoben, durch das Benutzern unter bestimmten Umständen E-Mails angezeigt werden, die an eine Adresse gesendet wurden, die nicht mit der angezeigten SMTP-Adresse übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="19df9-414">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="19df9-415">Diese Änderung stellt die Fähigkeit wieder her, mehrzeilige Betreffzeilen im Nachrichtenkopf anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="19df9-415">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="19df9-416">Es wurde ein Problem behoben, durch das verhindert werden konnte, dass Dateien an einem WebDAV-Speicherort gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="19df9-416">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="19df9-417">Es wurde ein Problem mit der Auswahl des SMIME-Algorithmus behoben.</span><span class="sxs-lookup"><span data-stu-id="19df9-417">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="19df9-418">Ein Problem wurde behoben, durch das Anwendungen von Drittanbietern keine E-Mail-Nachrichten mehr senden konnten.</span><span class="sxs-lookup"><span data-stu-id="19df9-418">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="19df9-419">Es wurde ein Problem behoben, das bewirkt hat, dass Benutzer ein leeres Meldungsfeld mit einer &quot;OK&quot;-Schaltfläche angezeigt bekamen, wenn Sie versuchten, den Support über den Kontext der Kontoerstellung zu kontaktieren.</span><span class="sxs-lookup"><span data-stu-id="19df9-419">Addressed an issue that caused users to see an empty message box with an &quot;OK&quot; button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="19df9-420">Ein Problem wurde behoben, das während der Profilerstellung ein Absturz verursachte.</span><span class="sxs-lookup"><span data-stu-id="19df9-420">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="19df9-421">Ein Problem wurde behoben, das dazu führte, dass Outlook unerwartet alle E-Mails synchronisierte, selbst wenn der Synchronisierungsschieberegler auf eine kleinere Einstellung eingestellt ist.</span><span class="sxs-lookup"><span data-stu-id="19df9-421">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="19df9-422">Ein Problem wurde behoben, das dazu führte, dass für Benutzer mit dem schwarzen Design die Dropdownliste &quot;Von&quot; als weißer Text auf weißem Hintergrund angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-422">Addressed an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>

- <span data-ttu-id="19df9-423">Es wurde ein Problem behoben, bei dem es durch das Abbrechen der Kontoeinrichtung einen Absturz gab.</span><span class="sxs-lookup"><span data-stu-id="19df9-423">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="19df9-424">Es wurde ein Problem behoben, aufgrund dessen bei Benutzern Abstürze beim Umbenennen einer Signatur auftraten.</span><span class="sxs-lookup"><span data-stu-id="19df9-424">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="19df9-425">Es wurde ein Problem behoben, durch das die Option zum Deaktivieren der Hervorhebung markierter Elemente in einigen Szenarien nicht berücksichtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-425">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="19df9-426">Es wurde ein Problem behoben, durch das Benutzer die Aufforderung &quot;die Regeln auf diesem Computer entsprechen nicht den Regeln von Microsoft Exchange&quot; beim Öffnen des Dialogfelds „Regeln“ angezeigt bekommen.</span><span class="sxs-lookup"><span data-stu-id="19df9-426">Addressed an issue that caused users to see a &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="19df9-427">Es wurde ein Problem behoben, bei dem beim Angeben einer ungültigen Absenderadresse ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-427">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="19df9-428">Es wurde ein Problem behoben, das einen Speicherverlust bei sehr langen Outlook-Sitzungen verursachte.</span><span class="sxs-lookup"><span data-stu-id="19df9-428">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="19df9-429">Ein Problem wurde behoben, das zu einem Absturz führen könnte, wenn dasselbe Element in mehreren Fenstern angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="19df9-429">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="19df9-430">Es wurde ein Problem behoben, durch das Benutzer mit einer spürbaren Verzögerung beim Interagieren mit ihren Postfachordnern über Tastenkombinationen konfrontiert waren.</span><span class="sxs-lookup"><span data-stu-id="19df9-430">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="19df9-431">Ein Problem wurde behoben, durch das Benutzer einige Instanzen von wiederkehrenden Kalenderelementen nicht öffnen konnten.</span><span class="sxs-lookup"><span data-stu-id="19df9-431">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="19df9-432">Es wurde ein Problem behoben, das bei Benutzern mit Postfächern auf Exchange 2010-Servern zu Problemen beim Hinzufügen von Anlagen zu Kalendereinträgen führte.</span><span class="sxs-lookup"><span data-stu-id="19df9-432">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="19df9-433">Es wurde ein Problem behoben, durch das Benutzer Probleme beim Beantworten digital signierter Nachrichten hatten.</span><span class="sxs-lookup"><span data-stu-id="19df9-433">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="19df9-434">Es wurde ein Problem behoben, durch das das Feld "Ort" in Besprechungen unerwartet aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-434">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="19df9-435">Es wurde ein Problem behoben, das dazu führte, dass Kommas im Ortsfeld einer Besprechung in Semikolons umgewandelt wurden.</span><span class="sxs-lookup"><span data-stu-id="19df9-435">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="19df9-436">Es wurde ein Problem behoben, bei dem der Standort einer Besprechung unerwartet nach dem Löschen wieder der Besprechung hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-436">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="19df9-437">Es wurden Probleme im Zusammenhang mit in der brasilianischen Zeitzone festgelegten Sitzungen und Terminen behoben.</span><span class="sxs-lookup"><span data-stu-id="19df9-437">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="19df9-438">Es wurde ein Problem behoben, durch beim Drücken der Taste &quot;S&quot; nach dem Schließen der Barrierefreiheitsprüfung unerwartet E-Mails gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="19df9-438">Addressed an issue that caused users to see mails unexpectedly send when pressing the &quot;S&quot; key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="19df9-439">Hiermit wird die Blockierungslogik für Anlagen in Outlook aktualisiert, um auch Python-Anlagen zu blockieren.</span><span class="sxs-lookup"><span data-stu-id="19df9-439">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="19df9-440">Ein Problem wurde behoben, durch das Web-Add-Ins auf von Digital Rights Management verwaltete Nachrichten zugreifen konnten.</span><span class="sxs-lookup"><span data-stu-id="19df9-440">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="19df9-441">Ein Problem wurde behoben, das während der Profilerstellung ein Absturz verursachte.</span><span class="sxs-lookup"><span data-stu-id="19df9-441">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="19df9-442">Es wurde ein Problem behoben, aufgrund dessen bei Benutzern Abstürze beim Umbenennen einer Signatur auftraten.</span><span class="sxs-lookup"><span data-stu-id="19df9-442">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19df9-443">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19df9-443">PowerPoint</span></span>

- <span data-ttu-id="19df9-444">Ein Problem mit der Shape.Paste-Methode wurde behoben: Wenn der Benutzer die Form mit der Shape.Paste-Methode kopiert und einfügt, wird die Auswahl in die eingefügte Form geändert.</span><span class="sxs-lookup"><span data-stu-id="19df9-444">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="19df9-445">Es wurde ein Problem behoben, das bei der Verwendung des Kontextmenüs in älteren PPT-Kommentaren zu einem Absturz führen könnte.</span><span class="sxs-lookup"><span data-stu-id="19df9-445">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="19df9-446">Project</span><span class="sxs-lookup"><span data-stu-id="19df9-446">Project</span></span>

- <span data-ttu-id="19df9-447">Ein Problem wurde identifiziert, bei dem Benutzer beim Öffnen eines schreibgeschützten Projekts möglicherweise mehrere Meldungen erhielten.</span><span class="sxs-lookup"><span data-stu-id="19df9-447">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="19df9-448">Es wurde ein Problem behoben, bei dem 100% Aufgaben vom Typ "feste Dauer" fälschlicherweise zu weniger als 100% erledigt wurden.</span><span class="sxs-lookup"><span data-stu-id="19df9-448">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="19df9-449">Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="19df9-449">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="19df9-450">Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.</span><span class="sxs-lookup"><span data-stu-id="19df9-450">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="19df9-451">Word</span><span class="sxs-lookup"><span data-stu-id="19df9-451">Word</span></span>

- <span data-ttu-id="19df9-452">Ein Problem wurde behoben, bei dem das Speichern einer vorhandenen Datei in einigen Fällen das Dialogfeld "Speichern unter" aufruft und die Datei nie wirklich gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="19df9-452">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="19df9-453">Im Organizer für Bausteine könnte eine ungültige Warnung angezeigt werden: &quot;Sie haben modifizierte Formen, Bausteine&quot;.</span><span class="sxs-lookup"><span data-stu-id="19df9-453">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>

### <a name="office-suite"></a><span data-ttu-id="19df9-454">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="19df9-454">Office Suite</span></span>

- <span data-ttu-id="19df9-455">Diese Änderung betrifft die langsame Darstellung einiger Streudiagramme mit Markierungen.</span><span class="sxs-lookup"><span data-stu-id="19df9-455">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="19df9-456">Diese Änderung behebt gemeldete Probleme mit Grafikadaptern, die die integrierte Intel-GPU nutzen.</span><span class="sxs-lookup"><span data-stu-id="19df9-456">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="19df9-457">Ein Fehler in der Einstellung des Stichtags für ODT- und GPO-Updates wurde behoben, bei dem der relative Stichtag nur beim ersten Festlegen funktionierte. Der Fix aktiviert den relativen Stichtag für spätere Updates.</span><span class="sxs-lookup"><span data-stu-id="19df9-457">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="19df9-458">Es wurde ein Problem behoben, bei dem Office-Aktualisierungen möglicherweise unerwartet Dateien aus dem Office CDN anstelle der beabsichtigten Quelle heruntergeladen haben, beispielsweise eine lokale oder Netzwerkfreigabe oder einen vom Configuration Manager bereitgestellten Speicherort.</span><span class="sxs-lookup"><span data-stu-id="19df9-458">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="19df9-459">Ein Problem wurde behoben, das dazu führte, dass beim Öffnen mehrerer Dokumente in Word/Excel/PowerPoint aus derselben SharePoint-Bibliothek lediglich das erste geöffnete Dokument auf Richtlinienkonformität gescannt wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-459">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (BUGDETAILS NICHT AM INHALTSENDE ENTFERNEN)

## <a name="version-1908-february-11"></a><span data-ttu-id="19df9-461">Version 1908: 11. Februar</span><span class="sxs-lookup"><span data-stu-id="19df9-461">Version 1908: February 11</span></span>
<span data-ttu-id="19df9-462">*Version 1908 (Build 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="19df9-462">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="19df9-463">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="19df9-463">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="19df9-465">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="19df9-465">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="19df9-466">Excel</span><span class="sxs-lookup"><span data-stu-id="19df9-466">Excel</span></span>

- <span data-ttu-id="19df9-467">Dieses Update behebt ein Problem, das dazu führte, dass ein Fehler auftrat, wenn VBA zum Hinzufügen eines Bildes zur Kopf-/Fußzeile eines Diagramms verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-467">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="19df9-468">Es wurde ein Problem behoben, bei dem der Rand eines Gruppenfeld-Steuerelements in der Druckvorschau oder beim Drucken nicht sichtbar war.</span><span class="sxs-lookup"><span data-stu-id="19df9-468">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="19df9-469">Nutzer können beim Speichern von Änderungen auf einen Fehler stoßen, wenn sie manche nicht englische Zeichensätze verwenden.</span><span class="sxs-lookup"><span data-stu-id="19df9-469">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="19df9-470">Es wurde ein Problem behoben, durch das die Dateigröße von Bildern in Diagrammkopfzeilen beim Speichern der Arbeitsmappe mit dem Diagramm zunahm.</span><span class="sxs-lookup"><span data-stu-id="19df9-470">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="19df9-471">Es wurde ein Problem behoben, das zur Beschädigung von DBCS-Zeichen in Büchern mit Querverweisen führte, indem die Auswahlbereiche mit dem Buch mit Querverweisen synchronisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="19df9-471">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="19df9-472">Es wurde ein Problem behoben, das dazu führen konnte, dass Kontrollkästchen bei Verwendung der automatischen Anpassung zum Anpassen der Zeilenhöhe verkleinert wurden.</span><span class="sxs-lookup"><span data-stu-id="19df9-472">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="19df9-473">Outlook</span><span class="sxs-lookup"><span data-stu-id="19df9-473">Outlook</span></span>

- <span data-ttu-id="19df9-474">Es wurde ein Problem behoben, bei dem beim Angeben einer ungültigen Absenderadresse ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-474">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="19df9-475">Es wurde ein Problem behoben, bei dem Nutzer bei der Verarbeitung von Konfliktnachrichten Synchronisierungsfehler hatten.</span><span class="sxs-lookup"><span data-stu-id="19df9-475">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="19df9-476">Es wurde ein Problem behoben, bei dem Nutzer beim Starten von Outlook beim Laden des Profils auf dem Bildschirm "Laden von Profilen" hängen blieben.</span><span class="sxs-lookup"><span data-stu-id="19df9-476">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="19df9-477">Es wurde ein Problem behoben, durch das Nutzer beim Ändern von Ansichten zeitweise Abstürze sehen konnten.</span><span class="sxs-lookup"><span data-stu-id="19df9-477">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="19df9-478">Es wurde ein Problem behoben, bei dem beim Anzeigen von mehr als 30 Kalendern in einer Citrix-Umgebung ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-478">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="19df9-479">[Hier](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) ist die einzelne KB, in der dies für frühere Versionen dokumentiert wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-479">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="19df9-480">Behebt ein Problem, bei dem Nutzer Probleme mit der Synchronisierung freigegebener Kalenderordner mit dem OST hatten, was zu Berechtigungsfehlern führte, wenn sie versuchten, mit diesen Ordnern zu interagieren.</span><span class="sxs-lookup"><span data-stu-id="19df9-480">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="19df9-481">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19df9-481">PowerPoint</span></span>

- <span data-ttu-id="19df9-482">Verbessertes Szenario zum Kopieren und Einfügen Das Kopieren der Form in eine PowerPoint-Folie und das Einfügen in eine andere Folie in einer Schleife schlägt möglicherweise mit Ausnahme fehl.</span><span class="sxs-lookup"><span data-stu-id="19df9-482">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="19df9-483">Es wurde ein Problem behoben, das zu einer langsameren Leistung zwischen Nutzern, die zusammenarbeiten, führte.</span><span class="sxs-lookup"><span data-stu-id="19df9-483">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="19df9-484">Es wurde ein Problem behoben, das auftreten konnte, wenn eine Datei, die inkrementell geöffnet wurde, eine Folie mit mehr als einem eingebetteten Mediendatenstrom enthielt.</span><span class="sxs-lookup"><span data-stu-id="19df9-484">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="19df9-485">Wir haben ein Problem behoben, bei dem beim ersten Start von PowerPoint möglicherweise keine Sicherheitswarnmeldung für nicht vertrauenswürdige Add-Ins angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="19df9-485">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="19df9-486">Project</span><span class="sxs-lookup"><span data-stu-id="19df9-486">Project</span></span>

- <span data-ttu-id="19df9-487">Es wurde ein Problem behoben, bei dem die tatsächliche Arbeit zwischen Arbeitszeittabelle und Projektplan unterschiedlich sein kann, da Ressourcenkalender nicht aktualisiert werden, wenn sich der Basiskalender ändert.</span><span class="sxs-lookup"><span data-stu-id="19df9-487">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="19df9-488">Word</span><span class="sxs-lookup"><span data-stu-id="19df9-488">Word</span></span>

- <span data-ttu-id="19df9-489">Ein Absturz in Word wurde behoben, indem es von einer veralteten API entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-489">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="19df9-490">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="19df9-490">Office Suite</span></span>

- <span data-ttu-id="19df9-491">Diese Änderung behebt das korrekte Rendern von Bildern nach dem Öffnen einer beschädigten Datei.</span><span class="sxs-lookup"><span data-stu-id="19df9-491">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1908-january-14"></a><span data-ttu-id="19df9-493">Version 1908: 14. Januar</span><span class="sxs-lookup"><span data-stu-id="19df9-493">Version 1908: January 14</span></span>
<span data-ttu-id="19df9-494">*Version 1908 (Build 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="19df9-494">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="19df9-495">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="19df9-495">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="19df9-497">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="19df9-497">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="19df9-498">Excel</span><span class="sxs-lookup"><span data-stu-id="19df9-498">Excel</span></span>

- <span data-ttu-id="19df9-499">Die Niederländische Tastenkombination für Dokumenttitel wurde in Alt-G geändert.</span><span class="sxs-lookup"><span data-stu-id="19df9-499">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="19df9-500">Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-500">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="19df9-501">Es gab ein Problem, bei dem Sie keine Elemente aus dem Kombinationsfeld eines WPF-Formulars (Windows Presentation Foundation) auswählen konnten, das von einem Add-n geöffnet wurde.</span><span class="sxs-lookup"><span data-stu-id="19df9-501">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="19df9-502">Outlook</span><span class="sxs-lookup"><span data-stu-id="19df9-502">Outlook</span></span>

- <span data-ttu-id="19df9-503">Es wurde ein Problem behoben, durch das Benutzer mit einer spürbaren Verzögerung beim Interagieren mit ihren Postfachordnern über Tastenkombinationen konfrontiert waren.</span><span class="sxs-lookup"><span data-stu-id="19df9-503">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="19df9-504">Es wurde ein Problem behoben, bei dem Richtlinientipps bei Verwendung eines alternativen Absenders nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="19df9-504">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="19df9-505">Es wurde ein Problem behoben, das bei der Aktualisierung von Anwesenheitsinformationen zu zeitweiligen Abstürzen führte.</span><span class="sxs-lookup"><span data-stu-id="19df9-505">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="19df9-506">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="19df9-506">PowerPoint</span></span>

- <span data-ttu-id="19df9-507">Wir haben ein Problem behoben, bei dem beim Kopieren einer Folie von einer Präsentation in eine andere möglicherweise doppelte Master erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="19df9-507">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="19df9-508">Bei Dateien mit neuen modernen Kommentaren wird eine gelbe Warnung angezeigt, wenn sie in einer nicht unterstützten Version geöffnet werden.</span><span class="sxs-lookup"><span data-stu-id="19df9-508">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="19df9-509">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="19df9-509">Office Suite</span></span>

- <span data-ttu-id="19df9-510">Es wurde ein Problem behoben, bei dem Office-Update-Nachrichten in einer anderen Sprache als erwartet angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="19df9-510">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="19df9-511">In Zukunft entsprechen Office-Update-Nachrichten ordnungsgemäß der Windows-Anzeigesprache.</span><span class="sxs-lookup"><span data-stu-id="19df9-511">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="19df9-512">Es wurde ein Problem behoben, bei dem ein Update in bestimmten Fällen nicht installiert wurde, wenn der Benutzer kein Administrator ist und das Systemkonto keine Netzwerkverbindung hatte.</span><span class="sxs-lookup"><span data-stu-id="19df9-512">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

> [!NOTE]
> <span data-ttu-id="19df9-514">Wenn Sie Hilfe bei einem Problem mit der Nutzung von Office benötigen, empfehlen wir, dass Sie Ihre Frage im [Microsoft Answers-Forum](https://answers.microsoft.com/) oder in der [Tech-Community](https://techcommunity.microsoft.com/) veröffentlichen, oder Sie können sich an den [Support](https://support.microsoft.com/contactus) wenden.</span><span class="sxs-lookup"><span data-stu-id="19df9-514">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (ADMIN CENTER-METADATENINHALT NICHT ÄNDERN BEGINN)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (ADMIN CENTER-METADATENINHALT NICHT ÄNDERN ENDE)

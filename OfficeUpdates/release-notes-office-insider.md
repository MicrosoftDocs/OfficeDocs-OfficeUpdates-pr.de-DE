---
title: Anmerkungen zu dieser Version für Office-Insider
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt der Zielgruppe von Insiders Fast die aktuelle Liste neuer Features, Fehlerkorrekturen oder bekannter Probleme bereit.
ms.openlocfilehash: e89f899f5a890b5db7b2ebaa0cc495f9b623f699
ms.sourcegitcommit: beff319f87f2fbecd15468f3ffa9bb99416ed165
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/22/2020
ms.locfileid: "43714715"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="a0b79-103">Anmerkungen zu dieser Version für Office-Insider</span><span class="sxs-lookup"><span data-stu-id="a0b79-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="a0b79-104">Dieser Artikel enthält Versionshinweise zu Insider-Builds von Word, Excel, PowerPoint, Outlook, Access und Project für Windows Desktop.</span><span class="sxs-lookup"><span data-stu-id="a0b79-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="a0b79-105">Jede Woche werden interessante neue Features, wichtige Fehlerbehebungen und alle wichtigen Probleme, über die Sie informiert werden sollen, hervorgehoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-105">Every week, we'll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="a0b79-106">Beachten Sie, dass das Rollout von Funktionen (und manchmal auch Fixes) für Insider häufig über einen längeren Zeitraum erfolgt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="a0b79-107">Auf diese Weise können wir sicherstellen, dass alles reibungslos funktioniert, bevor das Feature für ein breiteres Publikum bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="a0b79-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="a0b79-108">Wenn Sie also unten nichts beschrieben sehen, machen Sie sich keine Sorgen, Sie werden es eventuell irgendwann erhalten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-108">So, if you don't see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="a0b79-109">Versionshinweise werden wöchentlich veröffentlicht und können eine Kompilierung mehrerer Builds sein.</span><span class="sxs-lookup"><span data-stu-id="a0b79-109">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="a0b79-110">Das Veröffentlichungsdatum der Versionshinweise stimmt möglicherweise nicht mit dem tatsächlichen Veröffentlichungsdatum des Builds überein.</span><span class="sxs-lookup"><span data-stu-id="a0b79-110">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (NICHT ENTFERNEN)

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-april-17"></a><span data-ttu-id="a0b79-113">Version 2005: 17. April</span><span class="sxs-lookup"><span data-stu-id="a0b79-113">Version 2005: April 17</span></span>
<span data-ttu-id="a0b79-114">*Version 2005 (Build 12810.20002)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-114">*Version 2005 (Build 12810.20002)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-116">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-116">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-117">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-117">Excel</span></span>
- <span data-ttu-id="a0b79-118">Die Größe der Steuerelemente zur Bearbeitung von Zellreferenzen im Dialogfeld "Benutzerdefinierte Fehlerindikatoren", das bei Diagrammen verwendet wird, wurde erhöht.</span><span class="sxs-lookup"><span data-stu-id="a0b79-118">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>
- <span data-ttu-id="a0b79-119">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-119">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>
- <span data-ttu-id="a0b79-120">Ein Problem mit der Skalierung von Kontrollkästchen in Formularsteuerelementen beim Drucken wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-120">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>
- <span data-ttu-id="a0b79-121">Application.Evaluate (VBA) funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.</span><span class="sxs-lookup"><span data-stu-id="a0b79-121">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>
- <span data-ttu-id="a0b79-122">Diese Änderung behebt ein Problem, bei dem Informationen zur bedingten Formatierung (CF) nicht korrekt in XLSB-Dateien gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-122">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="a0b79-123">OneNote</span><span class="sxs-lookup"><span data-stu-id="a0b79-123">OneNote</span></span>
- <span data-ttu-id="a0b79-124">Ein Problem beim Speichern von Zeilenumbrüchen als vertikale Registerkarten wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-124">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-125">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-125">Outlook</span></span>
- <span data-ttu-id="a0b79-126">Behebt ein Problem, das dazu führte, dass Benutzer keine "Persönliche Kontaktgruppe" als "Besprechungsteilnehmer" hinzufügen konnten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-126">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>
- <span data-ttu-id="a0b79-127">Behebt ein Problem, das dazu geführt hat, dass bei Besprechungen, die mehr als 2 Monate entfernt sind, ein Besprechungsthema im "Terminplanungs-Assistenten" nicht angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="a0b79-127">Addresses an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>
- <span data-ttu-id="a0b79-128">Behebt ein Problem, das dazu führte, dass Benutzer beim Weiterleiten großer HTML-Nachrichten den Nachrichtentext abgeschnitten sahen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-128">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>
- <span data-ttu-id="a0b79-129">Es wurde die Möglichkeit des Erzwingens der S/MIME-Standardsignatur-Konfiguration über eine Gruppenrichtlinie hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-129">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>
- <span data-ttu-id="a0b79-130">Behebt ein Problem, das dazu führte, dass Löschregeln, die für andere Postfächer als das primäre Postfach des Benutzers erstellt wurden, ungültig wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-130">Addresses an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>
- <span data-ttu-id="a0b79-131">Behebt ein Problem, das dazu führte, dass Anlagen beim Weiterleiten einer verschlüsselten Nachricht verworfen wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-131">Addresses an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-132">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-132">Project</span></span>
- <span data-ttu-id="a0b79-133">Wenn Vorgänger/Nachfolger-Daten in einer Formular-Maske bearbeitet werden, wird ein zusätzliches ProjectBeforeTaskChange-Ereignis ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="a0b79-133">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>
- <span data-ttu-id="a0b79-134">Es wurde ein Problem behoben, bei dem Project abstürzen konnte, wenn das Feld „Boardstatus“ in einem Projekt geändert wurde, das mit einer SharePoint-Aufgabenliste verbunden ist.</span><span class="sxs-lookup"><span data-stu-id="a0b79-134">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>
- <span data-ttu-id="a0b79-135">Ein Problem wurde behoben, bei dem Project beim Speichern von Projekten, die mit älteren Project-Versionen erstellt wurden, möglicherweise abstürzt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-135">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-april-10"></a><span data-ttu-id="a0b79-137">Version 2004: 10. April</span><span class="sxs-lookup"><span data-stu-id="a0b79-137">Version 2004: April 10</span></span>
<span data-ttu-id="a0b79-138">*Version 2004 (Build 12730.20024)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-138">*Version 2004 (Build 12730.20024)*</span></span>

[//]: # (FEATUREDETAILS CONTENT START NICHT ENTFERNEN)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-140">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-140">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a0b79-141">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-141">Access</span></span>

- <span data-ttu-id="a0b79-142">\*\* Das Dialogfeld „Tabelle anzeigen“ umgehen, direkt zu einem Aufgabenbereich wechseln und das Hinzufügen von Tabellen zu Beziehungen und Abfragen rationalisieren:\*\* Fügen Sie Tabellen und Abfragen hinzu, indem Sie auf vier Registerkarten klicken, Namen mehrfach auswählen, nach Text suchen und aus einem Aufgabenbereich ziehen, der während der Arbeit geöffnet bleibt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-142">**Bypass the Show Table dialog box, go directly to a task pane, and streamline adding tables to relationships and queries.:** Add tables and queries by clicking four tabs, multi-selecting names, searching by text, and dragging from a task pane that stays open while you work.</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-143">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-143">Excel</span></span>

- <span data-ttu-id="a0b79-144">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="a0b79-144">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a0b79-145">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a0b79-145">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-146">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-146">Outlook</span></span>

- <span data-ttu-id="a0b79-147">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="a0b79-147">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a0b79-148">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a0b79-148">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="a0b79-149">**Bewahren Sie die Klangtreue Ihrer Bilder, wenn Sie diese als Teil einer E-Mail versenden:** Eine neue Outlook-Einstellung ist verfügbar, um die Bildkomprimierung zu begrenzen, wenn Sie Bilder als Teil des E-Mail-Inhalts versenden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-149">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-150">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-150">PowerPoint</span></span>

- <span data-ttu-id="a0b79-151">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="a0b79-151">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a0b79-152">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a0b79-152">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="a0b79-153">**Synchronisieren von Änderungen während der Präsentation:** Änderungen können jetzt synchronisiert werden, wenn sie vorgenommen werden, selbst wenn sich die Präsentation im Bildschirmpräsentationsmodus befindet.</span><span class="sxs-lookup"><span data-stu-id="a0b79-153">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-154">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-154">Word</span></span>

- <span data-ttu-id="a0b79-155">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="a0b79-155">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="a0b79-156">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="a0b79-156">Explore 1000's of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

- <span data-ttu-id="a0b79-157">**Fügen Sie einen privaten Kopie Anmerkungen hinzu:** Erstellen Sie handschriftliche Notizen nur für Sie, indem Sie eine private Kopie eines freigegebenen Dokuments erstellen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-157">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="a0b79-158">Wechseln Sie dazu einfach zu "Anzeige" > "Private Kopie erstellen".</span><span class="sxs-lookup"><span data-stu-id="a0b79-158">Go to View > Create a Private Copy to get started.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-161">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-161">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a0b79-162">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-162">Access</span></span>

- <span data-ttu-id="a0b79-163">Probleme bei der Anpassung der Größe und der Aktualisierung von Tabellen im Aufgabenbereich wurden behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-163">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-164">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-164">Excel</span></span>

- <span data-ttu-id="a0b79-165">Es wurde ein Problem behoben, bei dem das Auswählen eines Zellbereichs auf einem Arbeitsblatt zur Auswahl nur einer einzelnen Zelle geführt hat.</span><span class="sxs-lookup"><span data-stu-id="a0b79-165">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="a0b79-166">Es wurde ein Problem behoben, das dazu führen konnte, dass Excel nicht mehr reagierte, wenn die Größe eines Diagramms mit einigen x-Achsen-Bereichen reduziert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-166">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="a0b79-167">Es wurde ein Problem behoben, bei dem das Einfügen einer benutzerdefinierten Diagrammvorlage als Standard dazu führte, dass sie als Säulendiagramm gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-167">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="a0b79-168">Ein Problem wurde behoben, bei dem Datenbeschriftungen in Diagrammen leer angezeigt wurden, wenn die zugrundeliegenden Datenzellen keine Beschriftung aufwiesen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-168">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="a0b79-169">Es wurde ein Problem behoben, bei dem eine Excel-Tabelle mit aktiviertem Z1S1-Zellbezug die freigegeben bzw. gemeinsam erstellt wurde, der aktive Zellbezug im Z1S1-Modus nicht angezeigt wurde, wenn man auf das Symbol für die Anwesenheitsanzeige zeigte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-169">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-170">Outlook</span></span>

- <span data-ttu-id="a0b79-171">Behebt ein Problem, durch das gelegentlich Kategorien in E-Mail-Nachrichten nicht mehr aufschienen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-171">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="a0b79-172">Behebt ein Problem, durch das Stellvertretungen auf unterschiedlichen Computern unterschiedliche Ordnerhierarchien für freigegebene Postfächer angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-172">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="a0b79-173">Behebt ein Problem, das einen Absturz verursachte, wenn Benutzer versuchten, die Eigenschaften eines Organisationsformulars anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-173">Addresses an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="a0b79-174">Behebt ein Problem, durch das einige Erinnerungen nicht ausgelöst wurden, wenn die Zeitzone auf einem Computer geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-174">Addresses an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-175">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-175">PowerPoint</span></span>

- <span data-ttu-id="a0b79-176">Diese Änderung behebt ein Problem, bei dem beim Rendern eines Diagramms einer älteren Excel-Version, das als OLE-Objekt in PowerPoint oder Word eingebettet ist, u. U. nicht immer der Diagrammtitel angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-176">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="a0b79-177">Es wurde ein Problem behoben, bei dem beim Kopieren von Text aus Excel in PowerPoint u. U. dessen Formatierung geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-177">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="a0b79-178">Diese Änderung behebt ein Problem, bei dem das Suchen von Sonderzeichen mithilfe der Option "Nur ganze Wörter suchen" nicht immer erwartungsgemäß funktioniert hat.</span><span class="sxs-lookup"><span data-stu-id="a0b79-178">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-179">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-179">Project</span></span>

- <span data-ttu-id="a0b79-180">Es wurde ein Problem behoben, bei dem der Benutzer keine zeitgesteuerte Baseline-Arbeit eingeben konnte, wenn die Einstellung zum Schutz der aktuellen Arbeit aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="a0b79-180">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-181">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-181">Word</span></span>

- <span data-ttu-id="a0b79-182">Diese Änderung behebt ein Problem, bei dem wenn der Mauszeiger über einen Hinweis gehalten wurde, dessen Karte nicht hervorgehoben wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-182">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="a0b79-183">Diese Änderung behebt ein Problem, das dazu führte, dass der Text in gruppierten Formen beim Verwenden des Lasso-Auswahltools vorübergehend ausgeblendet wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-183">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="a0b79-184">Diese Änderung behebt ein Problem, bei dem beim Rendern eines Diagramms einer älteren Excel-Version, das als OLE-Objekt in PowerPoint oder Word eingebettet ist, u. U. nicht immer der Diagrammtitel angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-184">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="a0b79-185">Diese Änderung behebt ein Problem in der Zwei-Seiten-Ansicht. Beim Erstellen eines Kommentars wurde der Kommentaranker nicht immer in der Anzeige angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-185">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="a0b79-186">Ein Problem wurde behoben, bei dem ein Absatz, dessen Formatvorlage ein Vorgänger einer mit einer Liste verknüpften Formatvorlage war, möglicherweise verloren ging.</span><span class="sxs-lookup"><span data-stu-id="a0b79-186">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-march-27"></a><span data-ttu-id="a0b79-188">Version 2004: 27. März</span><span class="sxs-lookup"><span data-stu-id="a0b79-188">Version 2004: March 27</span></span>
<span data-ttu-id="a0b79-189">*Version 2004 (Build 12718.20010)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-189">*Version 2004 (Build 12718.20010)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-191">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-191">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a0b79-192">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-192">Outlook</span></span>

- <span data-ttu-id="a0b79-193">**Neue Option zum Deaktivieren von @Erwähnung-Vorschlägen beim Verfassen von E-Mails:** Findest Sie die @Erwähnung eher lästig als sinnvoll?</span><span class="sxs-lookup"><span data-stu-id="a0b79-193">**New option to disable @ mention suggestions when composing mail:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="a0b79-194">Wenn Sie das möchten, können Sie diese nun deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-194">Now you can turn it off if you prefer.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-197">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-197">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a0b79-198">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-198">Outlook</span></span>
- <span data-ttu-id="a0b79-199">Behebt ein Problem, das bewirkt hat, dass die Schaltfläche "In der Cloud speichern" in den Anlagentools fehlt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-199">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>
- <span data-ttu-id="a0b79-200">Behebt ein Problem, das bewirkt hat, dass Benutzer beim Antworten auf eine verwaltete Nachricht mit digitaler Berechtigung aus einem Inspektor-Fenster keine Signatur hinzufügen können, wenn der Benutzer nicht über die Berechtigung "Besitzer" für die Nachricht verfügt, auf die geantwortet wird.</span><span class="sxs-lookup"><span data-stu-id="a0b79-200">Addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>
- <span data-ttu-id="a0b79-201">Behebt ein Problem, durch das Benutzer keine weiteren Anlagen von einem Webspeicherort zu einer zuvor erstellten Besprechung hinzufügen können.</span><span class="sxs-lookup"><span data-stu-id="a0b79-201">Addresses an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-202">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-202">PowerPoint</span></span>
- <span data-ttu-id="a0b79-203">Diese Änderung behebt einen Fehler, der dazu führen kann, dass PowerPoint-Dateien mit Emojis beim Speichern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-203">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-204">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-204">Project</span></span>
- <span data-ttu-id="a0b79-205">Ein Problem wurde behoben, durch das, wenn "CustomFieldValueListGetItem" ausgeführt wird und eine Nachschlagetabelle für das benutzerdefinierte Feld nicht vorhanden ist, eine leere Nachschlagetabelle erstellt wird, auch wenn dies nicht der Fall sein sollte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-205">Fixed an issue where if 'CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-206">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-206">Word</span></span>
- <span data-ttu-id="a0b79-207">Diese Änderung behebt ein Problem, bei dem mehrere Seiten aus dem Menü "Ansicht" ausgewählt werden, in dem der Kommentarbereich als leer angezeigt werden kann.</span><span class="sxs-lookup"><span data-stu-id="a0b79-207">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-march-20"></a><span data-ttu-id="a0b79-209">Version 2004: 20. März</span><span class="sxs-lookup"><span data-stu-id="a0b79-209">Version 2004: March 20</span></span>
<span data-ttu-id="a0b79-210">*Version 2004 (Build 12711.20000)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-210">*Version 2004 (Build 12711.20000)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-212">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-212">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a0b79-213">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-213">Outlook</span></span>

- <span data-ttu-id="a0b79-214">**Visuelle Aktualisierung des Kalenders:** Letztes Jahr haben wir die E-Mail-Erfahrung visuell aufgefrischt, und dieses Jahr ist der Kalender mit einem Facelifting an der Reihe!</span><span class="sxs-lookup"><span data-stu-id="a0b79-214">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar's turn to get a facelift!</span></span> <span data-ttu-id="a0b79-215">Die Aktualisierungen sind frisch, aber vertraut, so dass Sie als erfahrener Outlook-Benutzer sofort einsteigen und produktiver sein können.</span><span class="sxs-lookup"><span data-stu-id="a0b79-215">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

- <span data-ttu-id="a0b79-216">**Schützen von Daten in einer Gruppe:** Die beim Erstellen einer Gruppe ausgewählte Vertraulichkeitsbezeichnung wird auf Gruppen-E-Mails, Dokumente und Teamwebsites angewendet</span><span class="sxs-lookup"><span data-stu-id="a0b79-216">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-217">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-217">PowerPoint</span></span>

- <span data-ttu-id="a0b79-218">**Aktualisieren von Folien während der Bildschirmpräsentation:** Aktualisieren Sie Folien, die von anderen Autoren während Ihrer Präsentation geändert wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-218">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-221">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-221">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-222">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-222">Excel</span></span>

- <span data-ttu-id="a0b79-223">Diese Änderung ist gegen Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen gerichtet.</span><span class="sxs-lookup"><span data-stu-id="a0b79-223">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-224">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-224">Outlook</span></span>

- <span data-ttu-id="a0b79-225">Diese Änderung ist gegen Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen gerichtet.</span><span class="sxs-lookup"><span data-stu-id="a0b79-225">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="a0b79-226">Diese Änderung behebt ein Problem, bei dem die neuesten Änderungen an E-Mail-Entwürfen nicht aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-226">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="a0b79-227">Ein Problem wurde behoben, bei dem Sie mit der rechten Maustaste auf eine Datei klicken und "Senden an" nicht funktionieren würde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-227">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="a0b79-228">Es wurde ein Problem behoben, bei dem, wenn ein Benutzer einen angepassten Suchpfad für das Adressbuch hatte, der Namensauflösungsbereich von Outlook auf den angepassten Pfad beschränkt wurde, anstatt die Globale Adressliste (GAL) einzubeziehen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-228">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="a0b79-229">Es wurde ein Problem behoben, bei dem innerhalb eines Satzes von zurückgegebenen Suchergebnissen beim Sortieren der Ergebnisse nach Kategorien die Farben der Kategorien nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-229">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-230">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-230">Project</span></span>

- <span data-ttu-id="a0b79-231">Ein Problem wurde behoben, bei dem das VBA-Ereignis (Visual Basic Applications) "ProjectBeforeTaskChange" nicht ausgelöst wurde, als ein Benutzer auf die Schaltfläche "inaktivieren" geklickt hat, die sich auf dem Menüband "Vorgänge" innerhalb der Planungsgruppierung befindet.</span><span class="sxs-lookup"><span data-stu-id="a0b79-231">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the "Inactivate" button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="a0b79-232">Wenn Sie Vorgänger- oder Nachfolgerdetails in einer Ansicht vom Typ „Formular“ festlegen, wurden die Änderungen nicht immer durch das Ereignis „ProjectBeforeTaskChange Visual Basic Applications“ (VBA) erfasst.</span><span class="sxs-lookup"><span data-stu-id="a0b79-232">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="a0b79-233">Wenn Sie beispielsweise eine Abhängigkeit gelöscht und im Formular auf „OK“ geklickt haben, wurde das Ereignis nicht ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="a0b79-233">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="a0b79-234">Dieses Verhalten wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-234">This behavior has been fixed.</span></span>

- <span data-ttu-id="a0b79-235">Es wurde ein Problem behoben, bei dem die neuesten Werte für die tatsächlichen Kosten der geleisteten Arbeit (ACWP) nicht angezeigt wurden, nachdem eine Änderung, z. B. eine Datumsänderung, vorgenommen wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-235">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="a0b79-236">Es wurde ein Problem behoben, bei dem das Öffnen eines Projekts über das Menü "Zuletzt verwendet" (MRU) die Projektdatei mit Lese- bzw. Schreibzugriff öffnete.</span><span class="sxs-lookup"><span data-stu-id="a0b79-236">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="a0b79-237">Diese Änderung behebt das Problem, dass Sie eine manuelle Aufgabe mit einem Startdatum und einer Uhrzeit (aber ohne Dauer) erstellt haben, diese aber mit einer falschen Uhrzeit auf der Zeitachse angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-237">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="a0b79-238">Es wurde ein Problem behoben, bei dem das Drucken einer Zeitleiste mit dem Hijri-Kalender dazu führte, dass ein Monat in der Druckansicht übersprungen oder dupliziert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-238">Fixed an issue where printing a timeline using Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="a0b79-239">Diese Änderung richtet sich gegen ein Problem, bei dem die Arbeit im Team Planner mit GDI-Objekten zu einer Überzuweisung von GDI-Objekten und zu geringem Speicherplatz führen konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-239">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-240">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-240">Word</span></span>

- <span data-ttu-id="a0b79-241">Es wurde ein Problem behoben, bei dem die Funktion zum Posten von Kommentaren deaktiviert war.</span><span class="sxs-lookup"><span data-stu-id="a0b79-241">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="a0b79-242">Diese Änderung ist gegen Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen gerichtet.</span><span class="sxs-lookup"><span data-stu-id="a0b79-242">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="a0b79-243">Diese Änderung ist gegen ein Problem gerichtet, bei dem der Account Manager keine Nachrichten versendete, was zu einer Unterbrechung bei Anwendungen von Drittanbietern führte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-243">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="a0b79-244">Diese Änderung behebt ein Problem, bei dem das Inhaltsverzeichnis mit Überschriftenformaten aktualisiert wurde, die im Dokument nicht vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-244">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="a0b79-245">Es wurde ein Problem behoben, bei dem in Word-Dokumenten gespeicherte digitale Signaturen beim Versand der Dokumente entfernt wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-245">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

[//]: # (BUGDETAILS AM INHALTSENDE NICHT ENTFERNEN)

## <a name="version-2004-march-13"></a><span data-ttu-id="a0b79-247">Version 2004: 13. März</span><span class="sxs-lookup"><span data-stu-id="a0b79-247">Version 2004: March 13</span></span>
<span data-ttu-id="a0b79-248">*Version 2004 (Build 12703.20010)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-248">*Version 2004 (Build 12703.20010)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-250">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-250">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-251">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-251">Excel</span></span>
- <span data-ttu-id="a0b79-252">**Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern.</span><span class="sxs-lookup"><span data-stu-id="a0b79-252">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a0b79-253">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a0b79-253">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="a0b79-254">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-254">PowerPoint</span></span>
- <span data-ttu-id="a0b79-255">**Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern.</span><span class="sxs-lookup"><span data-stu-id="a0b79-255">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a0b79-256">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a0b79-256">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="a0b79-257">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-257">Word</span></span>
- <span data-ttu-id="a0b79-258">**Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern.</span><span class="sxs-lookup"><span data-stu-id="a0b79-258">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="a0b79-259">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a0b79-259">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-262">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-262">Resolved issues</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-263">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-263">Access</span></span>
- <span data-ttu-id="a0b79-264">Ein Problem wurde behoben, bei dem internationale Versionen von Access in der Benutzeroberfläche englische Zeichenfolgen anzeigten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-264">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-265">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-265">Excel</span></span>
- <span data-ttu-id="a0b79-266">Es wurde ein Leistungsproblem behoben, das Benutzer beim programmgesteuerten Bearbeiten eines großen Zellbereichs festgestellt haben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-266">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>
- <span data-ttu-id="a0b79-267">Ein Leistungsproblem beim Öffnen von CSV-Dateien in japanischen Umgebungen wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-267">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-268">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-268">Outlook</span></span>
- <span data-ttu-id="a0b79-269">Behebt ein Problem, das dazu geführt hat, dass das Datum der letzten Änderung in einer Datei beim Hinzufügen einer Anlage zu einer E-Mail oder beim Speichern einer Anlage aus einer E-Mail durch Ziehen und Ablegen (im Gegensatz zum Hinzufügen oder Speichern über ein Menü) aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-269">Addresses an issue that caused the "Last Modified"; date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>
- <span data-ttu-id="a0b79-270">Behebt ein Problem, bei dem durch das Drücken der EINGABETASTE im erweiterten Suchbereich keine Suche gestartet wird. Stattdessen müssen Benutzer auf die Schaltfläche "Suchen" klicken.</span><span class="sxs-lookup"><span data-stu-id="a0b79-270">Addresses an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>
- <span data-ttu-id="a0b79-271">Ein Problem wurde behoben, bei dem die Suche keine Informationen zu Benutzern anzeigt, wenn die Option "Benutzerfotos anzeigen, wenn verfügbar" deaktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="a0b79-271">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-272">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-272">Project</span></span>
- <span data-ttu-id="a0b79-273">Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-273">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>
- <span data-ttu-id="a0b79-274">Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-274">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-275">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-275">Word</span></span>
- <span data-ttu-id="a0b79-276">Ein Problem wurde behoben, bei dem das Eingeben oder Bearbeiten eines Kommentars und Verwenden von STRG+A dazu führte, dass statt nur innerhalb der Kommentarkarte Text im Zeichenbereich markiert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-276">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>
- <span data-ttu-id="a0b79-277">Es wurde ein Problem behoben, bei dem die Ausrichtung von Wörtern in einem Dokument durcheinandergebracht wird, wenn Sie nach dem Drucken mit Schnelldruck versuchen, den Text zu bearbeiten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-277">We fixed an issue in which the alignment of words in a document gets scrambled when tried to edit after printing using Quick Print.</span></span>
- <span data-ttu-id="a0b79-278">Es wurde ein Problem beim Zusammenführen von zwei Dokumenten in ein Dokument behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-278">We fixed an issue when merging two documents into one document.</span></span>
- <span data-ttu-id="a0b79-279">Es wurde ein Problem behoben, bei dem das Markieren von Überarbeitungen, die Formeln enthalten, beim Speichern der Datei zu einem Fehler führen konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-279">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-06"></a><span data-ttu-id="a0b79-281">Version 2003: 6. März</span><span class="sxs-lookup"><span data-stu-id="a0b79-281">Version 2003: March 06</span></span>
<span data-ttu-id="a0b79-282">*Version 2003 (Build 12624.20086)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-282">*Version 2003 (Build 12624.20086)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-284">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-284">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a0b79-285">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-285">Outlook</span></span>

- <span data-ttu-id="a0b79-286">Ein Problem wurde behoben, bei dem das Erstellen einer Regel mit Outlook Web App auf dem Exchange-Server nicht beibehalten werden konnte und zu einem Konflikt geführt hat.</span><span class="sxs-lookup"><span data-stu-id="a0b79-286">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>
- <span data-ttu-id="a0b79-287">Wurde ein Problem mit Outlook im dunklen Modus behoben, wird möglicherweise die Dropdownliste im Feld "Von:" nicht angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-287">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>
- <span data-ttu-id="a0b79-288">Behebt ein Problem, das bewirkt hat, dass Benutzer Dateien nicht über den Datei-Explorer ihrer E-Mail-Nachricht als Anlage hinzufügen konnten, wenn diese Datei in einer anderen Anwendung geöffnet war.</span><span class="sxs-lookup"><span data-stu-id="a0b79-288">Addresses an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-289">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-289">PowerPoint</span></span>

- <span data-ttu-id="a0b79-290">Ein Problem wurde behoben, bei dem die empfohlenen Miniaturansichten blinkten, wenn Sie mit der Maus auf die Miniaturansichten gingen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-290">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="a0b79-291">In einigen Fällen kann dies dazu führen, dass PowerPoint abstürzt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-291">In some cases this could cause PowerPoint to crash.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-292">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-292">Word</span></span>

- <span data-ttu-id="a0b79-293">Es wurde ein Problem mit der compare-Funktion für Dokumente behoben, die für die Bearbeitung geschützt waren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-293">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a0b79-294">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-294">Office Suite</span></span>

- <span data-ttu-id="a0b79-295">Behebt ein Problem mit Word/Excel/PowerPoint, bei dem der User-Principal-Name (UPN) nicht mehr die Groß-/Kleinschreibung beachtet, was zu weniger Fehlern beim Arbeiten mit Dateien in SharePoint führt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-295">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="a0b79-296">Behebt ein kosmetisches Problem, bei dem die Schaltfläche "OK" im Dialogfeld „Datei \ Optionen“ abgeblendet angezeigt, die Funktionalität aber nicht beeinträchtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-296">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog was being displayed as grayed out but functionality was not impacted.</span></span>

[//]: # (BUGDETAILS NICHT AM INHALTSENDE ENTFERNEN)

[//]: # (FEATUREDETAILS CONTENT START NICHT ENTFERNEN)

## <a name="version-2003-february-28"></a><span data-ttu-id="a0b79-299">Version 2003: 28. Februar</span><span class="sxs-lookup"><span data-stu-id="a0b79-299">Version 2003: February 28</span></span>
<span data-ttu-id="a0b79-300">*Version 2003 (Build 12619.20002)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-300">*Version 2003 (Build 12619.20002)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-302">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-302">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a0b79-303">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-303">Outlook</span></span>

- <span data-ttu-id="a0b79-304">**Benachrichtigung Über Vorfall für IT-Administratoren:** Globale Administratoren von Microsoft 365-Mandanten und Administratoren von Office-Apps werden über Outlook und O365 Exchange-Vorfällen benachrichtigt, die sich auf Ihre Benutzer auswirken – mit einer neuen Benachrichtigung im rechten Seitenbereich in Outlook für Windows.</span><span class="sxs-lookup"><span data-stu-id="a0b79-304">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-305">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-305">PowerPoint</span></span>

- <span data-ttu-id="a0b79-306">**Verbesserte Freihand-Shape-Diagrammdarstellung:** Zeichnen Sie bessere Diagramme und lassen Sie diese in ein Office-Objekt umwandeln, das Sie bearbeiten können. [Weitere Informationen unter ](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span><span class="sxs-lookup"><span data-stu-id="a0b79-306">**Improved ink to shape diagramming experience:** Draw better diagrams and have it convert so office object you can manipulate [Learn more](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-309">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-309">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-310">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-310">Excel</span></span>

- <span data-ttu-id="a0b79-311">Ein Problem wurde behoben, bei dem der Text in einem Datenschnitt in der Druckvorschau nicht ordnungsgemäß skaliert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-311">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-312">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-312">Outlook</span></span>

- <span data-ttu-id="a0b79-313">Behebt ein Problem, das dazu geführt hat, dass das „Datum der letzten Änderung“ in einer Datei beim Hinzufügen einer Anlage zu einer E-Mail oder beim Speichern einer Anlage aus einer E-Mail durch Ziehen und Ablegen (im Gegensatz zum Hinzufügen oder Speichern über ein Menü) aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-313">Addresses an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-314">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-314">Word</span></span>

- <span data-ttu-id="a0b79-315">Behebt ein Problem, das dazu geführt hat, dass beim Navigieren über eine Kommentarkarte mit der Tabulatortaste der Fokus auf dem Bearbeitungsfeld für den Kommentar nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-315">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="a0b79-316">Das Einfügen eines Steuerelements (beispielsweise eines Textinhaltssteuerelements) in eine Gleichung und das anschließende Speichern und Öffnen der Datei führte zu einem Fehler aufgrund nicht lesbaren Inhalts.</span><span class="sxs-lookup"><span data-stu-id="a0b79-316">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="a0b79-317">Ein Problem wurde behoben, aufgrund dessen das Speichern einer zuvor kennwortgeschützten Datei in einem Cloudspeicher nicht funktioniert hat.</span><span class="sxs-lookup"><span data-stu-id="a0b79-317">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a0b79-318">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-318">Office Suite</span></span>

- <span data-ttu-id="a0b79-319">Behebt ein Problem, das dazu geführt hat, dass beim Öffnen mehrerer Dokumente in Word/Excel/PowerPoint aus derselben SharePoint-Bibliothek lediglich das erste geöffnete Dokument auf Richtlinienkonformität gescannt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-319">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSWENDE)

## <a name="version-2003-february-21"></a><span data-ttu-id="a0b79-321">Version 2003: 21. Februar</span><span class="sxs-lookup"><span data-stu-id="a0b79-321">Version 2003: February 21</span></span>
<span data-ttu-id="a0b79-322">*Version 2003 (Build 12615.20000)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-322">*Version 2003 (Build 12615.20000)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-324">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-324">Feature updates</span></span>
### <a name="office-suite"></a><span data-ttu-id="a0b79-325">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-325">Office Suite</span></span>

- <span data-ttu-id="a0b79-326">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-326">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-329">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-329">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-330">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-330">Excel</span></span>
- <span data-ttu-id="a0b79-331">Es wurde ein Problem behoben, das möglicherweise beim Umbenennen von Pivot-Tabellenmaßen aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="a0b79-331">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>
- <span data-ttu-id="a0b79-332">Es wurde ein Leistungsproblem behoben, das möglicherweise bei der Verwendung eines VBA-Makros zum Löschen des Inhalts eines Bereichs aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="a0b79-332">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>
- <span data-ttu-id="a0b79-333">Es wurde ein Problem behoben, das zum Blinken der Benutzeroberfläche führte, wenn Benutzer ein Makro ausführten, das mit dem Menüband interagierte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-333">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>
- <span data-ttu-id="a0b79-334">Es wurde ein Problem behoben, bei dem CSV-Dateien falsch geladen wurden, wenn das erste Wort in der Datei TABLE lautete.</span><span class="sxs-lookup"><span data-stu-id="a0b79-334">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>
- <span data-ttu-id="a0b79-335">Es wurde ein Problem behoben, bei dem es zu Abstürzen kommen konnte, wenn Benutzer zwischen zwei Arbeitsmappen mit unterschiedlichen Zoomstufen wechselten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-335">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-336">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-336">Outlook</span></span>
- <span data-ttu-id="a0b79-337">Es wurde ein Problem behoben, das dazu führte, dass Benutzer keine Nachrichten in öffentlichen Ordnern öffnen konnten, wenn Outlook über Nacht laufen gelassen wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-337">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>
- <span data-ttu-id="a0b79-338">Es wurde eine Racebedingung behoben, bei der die Schaltflächen "Zulassen" und "Verweigern" auf der Seite "Berechtigungen" während des Authentifizierungsworkflows beim Hinzufügen eines Google Mail-Kontos deaktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="a0b79-338">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>
- <span data-ttu-id="a0b79-339">Es wurde ein Problem behoben, das dazu führte, dass Outlook in einigen Szenarien unerwartet Protokollausgaben erzeugte, selbst wenn die Protokollierung ausgeschaltet war.</span><span class="sxs-lookup"><span data-stu-id="a0b79-339">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-340">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-340">Word</span></span>
- <span data-ttu-id="a0b79-341">Es wurde ein Problem behoben, bei dem Kommentarkarten nicht immer hervorgehoben werden, wenn der Mauszeiger über die Kommentarkarte bewegt wird.</span><span class="sxs-lookup"><span data-stu-id="a0b79-341">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>
- <span data-ttu-id="a0b79-342">Während einer aktiven Sitzung zur gemeinsamen Dokumenterstellung kann das direkte Hinzufügen eines Bildes in eine Kommentarkarte dazu führen, dass ein Tag hinzugefügt wird.</span><span class="sxs-lookup"><span data-stu-id="a0b79-342">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="a0b79-343">Das Problem wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-343">This issue has been fixed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a0b79-344">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-344">Office Suite</span></span>
- <span data-ttu-id="a0b79-345">Beim Verwenden der Metadateneigenschaften MultiChoice/Verweis/Verwaltet mit Word/Excel/PowerPoint-Dokumenten und dem Speichern in einer SharePoint-Dokumentbibliothek waren diese Eigenschaften bisher auf 255 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-345">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="a0b79-346">Wenn diese Eigenschaften 255 Zeichen überschritten, konnten solche Dokumente nicht gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-346">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="a0b79-347">Mit dieser Änderung wurde dieser Grenzwert auf 2048 Zeichen erhöht.</span><span class="sxs-lookup"><span data-stu-id="a0b79-347">With this change, this limit has been increased to 2048 characters.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-february-14"></a><span data-ttu-id="a0b79-349">Version 2003: 14. Februar</span><span class="sxs-lookup"><span data-stu-id="a0b79-349">Version 2003: February 14</span></span>
<span data-ttu-id="a0b79-350">*Version 2003 (Build 12607.20000)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-350">*Version 2003 (Build 12607.20000)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-352">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-352">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a0b79-353">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-353">Outlook</span></span>

- <span data-ttu-id="a0b79-354">**Neue Benutzeroberfläche für WLAN-Netzwerke mit Anmeldung:** Sind Sie schon einmal einem WLAN-Netzwerk beigetreten, mit dem Sie sich anmelden mussten?</span><span class="sxs-lookup"><span data-stu-id="a0b79-354">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="a0b79-355">Outlook erkennt dies jetzt und hilft Ihnen, eine Verbindung zu herstellen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-355">Outlook now detects this and helps you get connected.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-356">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-356">Word</span></span>

- <span data-ttu-id="a0b79-357">**Freihand-Editor in der Toolbox der Zeichentools finden:** Wählen Sie "Zeichnen" und dann den Freihand-Editor-Stift aus, um Ihr Dokument mit dem Finger oder einem digitalen Stift zu bearbeiten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-357">**Find Ink Editor in your drawing toolbox:** Select Draw and then choose the Ink Editor pen to edit your document with your finger or a digital pen.</span></span> [<span data-ttu-id="a0b79-358">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a0b79-358">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a><span data-ttu-id="a0b79-359">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-359">Office Suite</span></span>

- <span data-ttu-id="a0b79-360">**Übersichtlichere Statusleistensymbole:** Statusleistensymbole sind jetzt einfacher zu sehen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-360">**Clearer status bar icons:** Status bar icons are now easier to see</span></span>

[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-363">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-363">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a0b79-364">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-364">Outlook</span></span>

- <span data-ttu-id="a0b79-365">Ein Problem wurde behoben, durch das Benutzer den Zugriff auf das Dialogfeld "Frei/Gebucht-Optionen" der Kalenderberechtigungen verloren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-365">Addressed an issue that caused users to lose access to the "Free Busy Options" calendar permissions dialog.</span></span>

- <span data-ttu-id="a0b79-366">Es wurde ein Problem behoben, das zur Warnung "Leider besteht ein Problem beim Öffnen dieses Elements" führen kann, wenn Sie bestimmte Besprechungsserien-Instanzen öffnen, die aus einer anderen Zeitzone gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-366">Fixed an issue that may result in the alert: "Sorry we're having trouble opening this item" when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="a0b79-367">Es wurde ein Problem behoben, durch das Benutzer eine MSG-Datei möglicherweise nicht mehr öffnen können, nachdem die eine Anlage aus dieser Nachricht durch Ziehen und Ablegen verschoben haben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-367">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="a0b79-368">Ein Problem wurde behoben, bei dem der Dateiname nach dem Hochladen einer Dateianlage aus Outlook nach OneDrive möglicherweise geändert wird, wenn der Name der Anlage eine Klammer enthält.</span><span class="sxs-lookup"><span data-stu-id="a0b79-368">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-369">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-369">PowerPoint</span></span>

- <span data-ttu-id="a0b79-370">Es wurde ein Problem behoben, das dazu führen kann, dass ein Dokument, das ein Excel-Diagramm enthält, nicht in PowerPoint oder Word gespeichert werden kann.</span><span class="sxs-lookup"><span data-stu-id="a0b79-370">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-371">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-371">Word</span></span>

- <span data-ttu-id="a0b79-372">Ein Problem wurde behoben, bei dem Bilder in Dokumenten beim Export in eine PDF-Datei transparent sind.</span><span class="sxs-lookup"><span data-stu-id="a0b79-372">Fixed an issue where pictures in documents lose transparency when exported to PDF.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-february-07"></a><span data-ttu-id="a0b79-374">Version 2002: 07. Februar</span><span class="sxs-lookup"><span data-stu-id="a0b79-374">Version 2002: February 07</span></span>
<span data-ttu-id="a0b79-375">*Version 2002 (Build 12527.20040)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-375">*Version 2002 (Build 12527.20040)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-377">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-377">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a0b79-378">Zugriff</span><span class="sxs-lookup"><span data-stu-id="a0b79-378">Access</span></span>

- <span data-ttu-id="a0b79-379">**Seien Sie beim Arbeiten im Abfrage-Designer, in der SQL-Ansicht und im Fenster „Beziehungen“ produktiver:** Klicken Sie zum Öffnen, Gestalten, Vergrößern oder Verkleinern und Ausblenden mit der rechten Maustaste auf die betreffende Tabelle.</span><span class="sxs-lookup"><span data-stu-id="a0b79-379">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="a0b79-380">Suchen und Ersetzen von Text in der SQL-Ansicht.</span><span class="sxs-lookup"><span data-stu-id="a0b79-380">Search and replace text in SQL View.</span></span> <span data-ttu-id="a0b79-381">Auswählen mehrerer Tabellen im Fenster „Beziehungen“.</span><span class="sxs-lookup"><span data-stu-id="a0b79-381">Select multiple tables in the Relationships window.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-384">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-384">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a0b79-385">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-385">Access</span></span>

- <span data-ttu-id="a0b79-386">Dieses Update behebt ein Problem bei der Verwendung von ADODB.</span><span class="sxs-lookup"><span data-stu-id="a0b79-386">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="a0b79-387">Das Recorder-Objekt im VB-Code meldet möglicherweise einen Fehler falsch.</span><span class="sxs-lookup"><span data-stu-id="a0b79-387">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="a0b79-388">Dieses Update behebt ein Problem, das dazu führen kann, dass Microsoft Access eine Identitätsspalte in einer verknüpften SQL-Server-Tabelle nicht identifiziert, was dazu führen kann, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-388">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-389">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-389">Excel</span></span>

- <span data-ttu-id="a0b79-390">Ein Problem wurde behoben, das dazu geführt hatte, dass Excel bei Verschieben von Text in Spalten mit dynamischen Pfeilern abgestürzt ist.</span><span class="sxs-lookup"><span data-stu-id="a0b79-390">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-391">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-391">Outlook</span></span>

- <span data-ttu-id="a0b79-392">Ein Problem wurde behoben, das dazu geführt hatte, dass beim Durchblättern des Kalanders in der Monatsansicht die vorangegangenen Kalenderereignisse nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-392">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="a0b79-393">Behebt ein Problem, das dazu geführt hat, dass Benutzer beim Anzeigen von mehr als 30 Kalendern in einer Citrix-Umgebung einen Absturz erlebt haben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-393">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-394">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-394">PowerPoint</span></span>

- <span data-ttu-id="a0b79-395">Ein Problem wurde behoben, das dazu geführt hatte, dass PowerPoint nach dem Schließen einer Datei diese nicht sofort aus der Sammlung von Präsentationen entfernt hat, sofern Ereignisverarbeiter (event handlers) ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-395">Fixed an issue where after closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="a0b79-396">Dadurch war die Zahl der vom Objektmodell gemeldeten, geöffneten Präsentationen falsch und das Herunterfahren von PowerPoint wurde verhindert.</span><span class="sxs-lookup"><span data-stu-id="a0b79-396">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>

- <span data-ttu-id="a0b79-397">Ein Problem mit dem Textmarker wurde behoben: Weißer Text mit dunkleren Textmarkerfarben wurde Schwarz mit Graustufen gedruckt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-397">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-398">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-398">Word</span></span>

- <span data-ttu-id="a0b79-399">Beim Aktualisieren eines Inhaltsverzeichnisses bzw. dem Blättern durch dieses wird manchmal möglicherweise ein grauer Bereich auf dem Dokument angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-399">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>

- <span data-ttu-id="a0b79-400">Ein Problem wurde behoben, bei dem die Entwurfsversion eines Stammkommentars bei der gemeinsamen Dokumenterstellung zeitweise nicht beibehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-400">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>

- <span data-ttu-id="a0b79-401">Ein Problem wurde behoben, das dazu geführt hatte, dass beim Hin- und Herwechseln zwischen Kommentar-Karten manchmal der anfänglich ausgewählte Kommentar mit einer Auswahlhervorhebung angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-401">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>

- <span data-ttu-id="a0b79-402">Es wurde ein Problem mit der Verwendung von „Durchsuchen“ zum Speichern einer Datei behoben, das nicht funktioniert hat, wenn ein Kommentar geschrieben, jedoch nicht gepostet worden war und der Benutzer versucht hatte, die Datei zu speichern.</span><span class="sxs-lookup"><span data-stu-id="a0b79-402">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>

- <span data-ttu-id="a0b79-403">Wenn „SlideTrack“ aktiviert und der Bereich „Kommentare“ geschlossen ist, kann der Bereich „Kommentare“ mit STRG+ALT+M möglicherweise nicht geöffnet werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-403">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>

- <span data-ttu-id="a0b79-404">Es wurde ein Problem behoben, das dazu geführt hatte, dass beim Hinzufügen von @mention in einer Tabelle die Fehlermeldung „Eine Tabelle in diesem Dokument ist beschädigt“ generiert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-404">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a0b79-405">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-405">Office Suite</span></span>

- <span data-ttu-id="a0b79-406">Behebt ein Problem, das dazu geführt hat, dass Korrekturhilfe-Paket Norwegen Nynorsk (nn-no) nicht ordnungsgemäß installiert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-406">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-january-31"></a><span data-ttu-id="a0b79-408">Version 2002: 31. Januar</span><span class="sxs-lookup"><span data-stu-id="a0b79-408">Version 2002: January 31</span></span>
<span data-ttu-id="a0b79-409">*Version 2002 (Build 12513.20010)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-409">*Version 2002 (Build 12513.20010)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-411">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-411">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-412">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-412">Excel</span></span>

- <span data-ttu-id="a0b79-413">**Schnell lesen und antworten:** Antworten Sie auf Kommentare und Erwähnungen direkt aus dem E-Mail-Bereich, ohne die Arbeitsmappe zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-413">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="a0b79-414">**Datenprofilerstellung im Abfrage-Editor:** Sie können die Daten in Ihren Spalten auf einen Blick analysieren, Fehler- und Leerwerte identifizieren, Verteilungshistogramme anzeigen und vieles mehr.</span><span class="sxs-lookup"><span data-stu-id="a0b79-414">**Data Profiling in Query Editor:** Get-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-417">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-417">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a0b79-418">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-418">Outlook</span></span>

- <span data-ttu-id="a0b79-419">Problem behoben, bei dem für auf Grundlage einer Aufbewahrungsrichtlinie ablaufende E-Mails zwei Beschriftungen angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-419">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="a0b79-420">Eine mit der Aussage, dass die E-Mail in einem Tag, die andere, dass die E-Mail in zwei Tagen abläuft.</span><span class="sxs-lookup"><span data-stu-id="a0b79-420">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-421">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-421">Word</span></span>

- <span data-ttu-id="a0b79-422">Problem behoben, bei dem ein Kommentarhinweis bei &quot;inverser&quot; Seitenfarbe nicht sichtbar war.</span><span class="sxs-lookup"><span data-stu-id="a0b79-422">Fixed an issue where comment hint was not visible in read mode with &quot;Inverse&quot; page color.</span></span>

- <span data-ttu-id="a0b79-423">Problem behoben, bei dem kursive Formatierung nach dem Bearbeiten eines Kommentars, kursiver Formatierung des Texts und anschließendem Posten verloren wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-423">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>

- <span data-ttu-id="a0b79-424">Problem behoben, bei dem Kommentarbefehle (Kommentar bearbeiten, auf Kommentar antworten, Kommentar löschen, Kommentar auflösen) nicht im Kontextmenü von Kommentaren angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-424">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-january-17"></a><span data-ttu-id="a0b79-426">Version 2002: 17. Januar</span><span class="sxs-lookup"><span data-stu-id="a0b79-426">Version 2002: January 17</span></span>
<span data-ttu-id="a0b79-427">*Version 2002 (Build 12508.20000)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-427">*Version 2002 (Build 12508.20000)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-429">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-429">Feature updates</span></span>
### <a name="word"></a><span data-ttu-id="a0b79-430">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-430">Word</span></span>

- <span data-ttu-id="a0b79-431">**Benachrichtigungs-E-Mails für Erwähnungen und Kommentare enthalten jetzt eine Vorschau:** E-Mail-Benachrichtigungen für Erwähnungen und Kommentare enthalten jetzt eine Vorschau des Kommentartexts und des Kontexts, auf den verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="a0b79-431">**Mention & comment notification emails now contain previews:** Email notifications for mentions & comments will now include previews of the comment text and context for what it is referring to.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-434">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-434">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-435">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-435">Excel</span></span>

- <span data-ttu-id="a0b79-436">In einigen Fällen wurden von der Barrierefreiheitsprüfung keine Empfehlungen für Formen angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-436">In some cases, the Accessibility checker would not show the recommendations for shapes.</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-437">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-437">Outlook</span></span>

- <span data-ttu-id="a0b79-438">Ordner, die unter "Favoriten" im linken Navigationsbereich gespeichert sind, können zeitweise verschwinden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-438">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-439">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-439">PowerPoint</span></span>

- <span data-ttu-id="a0b79-440">Ein Problem wurde behoben, bei dem Freihandelemente in einer PowerPoint-Freihandanimation nicht vollständig gerendert wurde oder übersprungen wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-440">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2001-january-10"></a><span data-ttu-id="a0b79-442">Version 2001: 10. Januar</span><span class="sxs-lookup"><span data-stu-id="a0b79-442">Version 2001: January 10</span></span>
<span data-ttu-id="a0b79-443">*Version 2001 (Build 12430.20000)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-443">*Version 2001 (Build 12430.20000)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-445">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-445">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-446">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-446">Excel</span></span>
- <span data-ttu-id="a0b79-447">**Speichern von Shapes als Bildern:** mit nur wenigen Mausklicks können Sie eine Form, ein Symbol oder ein anderes Objekt als Bilddatei speichern, um Sie an anderer Stelle wiederzuverwenden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-447">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="a0b79-448">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a0b79-448">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

### <a name="outlook"></a><span data-ttu-id="a0b79-449">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-449">Outlook</span></span>
- <span data-ttu-id="a0b79-450">**Der Benutzer kann nun Objekte in Word/Excel/Outlook als Bild für Windows speichern.:** Diese Möglichkeit ist bereits aus PowerPoint bekannt, sodass Benutzer nun Objekte in Word, Excel und Outlook als Bild speichern können.</span><span class="sxs-lookup"><span data-stu-id="a0b79-450">**User can now save objects in Word/Excel/Outlook as a picture for Windows.:** With the ability already seen in PowerPoint, users can now save objects in Word, Excel and Outlook as a picture.</span></span> <span data-ttu-id="a0b79-451">Zu den Objekten gehören Formen, Symbole, Bilder und vieles mehr!</span><span class="sxs-lookup"><span data-stu-id="a0b79-451">Objects include shapes, icons, pictures, and more!</span></span> <span data-ttu-id="a0b79-452">Sie können über das Kontextmenü darauf zugreifen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-452">This can be accessed through the right-click menu.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-453">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-453">Word</span></span>
- <span data-ttu-id="a0b79-454">**Wählen Sie auf einfache Weise Freihand in Word aus, indem Sie eine Form um das Freihandobjekt zeichnen.:** das Lassotool auf der Registerkarte „Zeichnen“ hilft Ihnen beim Auswählen von frei handgezeichneten Objekten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-454">**Easily select ink in Word by drawing a shape around it.:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="a0b79-455">Wählen Sie einzelne Striche oder ganze Wörter aus.</span><span class="sxs-lookup"><span data-stu-id="a0b79-455">Select individual strokes, or whole words.</span></span> <span data-ttu-id="a0b79-456">Das ist praktisch, wenn Sie eine viele Freihandobjekte haben und nur mit einigen davon arbeiten möchten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-456">It's handy when you have lots of ink and you only want to work with some of it.</span></span> [<span data-ttu-id="a0b79-457">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a0b79-457">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="a0b79-458">**Speichern von Shapes als Bildern:** mit nur wenigen Mausklicks können Sie eine Form, ein Symbol oder ein anderes Objekt als Bilddatei speichern, um Sie an anderer Stelle wiederzuverwenden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-458">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="a0b79-459">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a0b79-459">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-462">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-462">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="a0b79-463">OneNote</span><span class="sxs-lookup"><span data-stu-id="a0b79-463">OneNote</span></span>
- <span data-ttu-id="a0b79-464">Seitenregisterkarten werden bei einer Auflösung von 100% möglicherweise zu klein und zu nah aneinander angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-464">Page tabs may appear too small and close together at 100% resolution.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-465">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-465">Word</span></span>
- <span data-ttu-id="a0b79-466">Bei einer großen Gruppe von Kommentaren kann das Löschen eines Kommentars am Ende der Kommentarliste dazu führen, dass der Bereich ganz nach oben gescrollt wird.</span><span class="sxs-lookup"><span data-stu-id="a0b79-466">In a large set of comments, deleting a comment near the end of the list of comments may result in the pane scrolling all the way to the top.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2001-january-03"></a><span data-ttu-id="a0b79-468">Version 2001: 03. Januar</span><span class="sxs-lookup"><span data-stu-id="a0b79-468">Version 2001: January 03</span></span>
<span data-ttu-id="a0b79-469">*Version 2001 (Build 12425.20000)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-469">*Version 2001 (Build 12425.20000)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-471">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-471">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-472">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-472">Excel</span></span>
- <span data-ttu-id="a0b79-473">Einige Rahmenlinien werden auf Papier im Format A4 möglicherweise nicht wie erwartet gedruckt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-473">Some border lines may not print as expected on A4 size paper.</span></span>
- <span data-ttu-id="a0b79-474">Das Einfügen eines Bildes in die Kopf-/Fußzeile eines Diagrammobjekts auf einem Blatt mit VBA kann zu einem Fehler führen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-474">Adding an image to the header/footer of a chart object on a sheet using VBA may result in an error.</span></span>
- <span data-ttu-id="a0b79-475">Beim Formatieren einer Diagrammachse ist der Abstand zwischen den Beschriftungen auf 255 Zeichen begrenzt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-475">When formatting a chart axis, the interval between labels was limited to 255.</span></span>
- <span data-ttu-id="a0b79-476">Ein Problem wurde behoben, bei dem beim Versuch, eine XML-Abfrage zu aktualisieren, deren URL zur Datenquelle abgeschnitten wurde, ein Fehler auftrat.</span><span class="sxs-lookup"><span data-stu-id="a0b79-476">Fixed an issue where an error would occur trying to refresh an XML query in which the URL to the datasource was being truncated.</span></span>
- <span data-ttu-id="a0b79-477">In der Arbeitsmappenstatistik wird eine Makroanzahl aus allen geöffneten Arbeitsmappen angezeigt, einschließlich der persönlichen Makroarbeitsmappe.</span><span class="sxs-lookup"><span data-stu-id="a0b79-477">Workbook Statistics would report a macro count from all open workbooks, including the personal macro workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-478">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-478">Outlook</span></span>
- <span data-ttu-id="a0b79-479">Das Wechseln von Ordnern kann zu einem kurzen weißen "Blitz" in der E-Mail-Liste/E-Mail-Vorschau führen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-479">Switching folders may result in a brief white 'flash' in the mail list / mail preview.</span></span> <span data-ttu-id="a0b79-480">Dieses Verhalten war im dunklen Modus ausgeprägter.</span><span class="sxs-lookup"><span data-stu-id="a0b79-480">This behavior was more pronounced in dark mode.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-481">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-481">PowerPoint</span></span>
- <span data-ttu-id="a0b79-482">Ein Problem mit dem Objektmodell wurde behoben, bei dem das Aufrufen der Methode "Shape.Paste" dazu führte, dass die eingefügte Form den Fokus erhielt.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="a0b79-482">Fixed an Object Model issue where calling Shape.Paste method would result in the pasted shape receiving focus.&nbsp;</span></span>
- <span data-ttu-id="a0b79-483">Verbessertes Kopieren-Einfügen-Szenario:&nbsp; Das programmgesteuerte Kopieren einer Form aus einer PowerPoint-Folie und das Einfügen dieser Form in eine andere Folie in einer Schleife konnte mit einem Ausnahmefehler fehlschlagen.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="a0b79-483">Improved a copy-paste scenario:&nbsp;Progamatically copying a shape from a PowerPoint slide and pasting it to another slide in a loop could fail with an exception error.&nbsp;</span></span>
- <span data-ttu-id="a0b79-484">Animationen in den Abschnittsüberschriften von Folien wurden nach dem Reduzieren und Erweitern von Abschnittsüberschriften nicht korrekt gerendert.</span><span class="sxs-lookup"><span data-stu-id="a0b79-484">Animation in the section headers of slides would not render properly after collapsing and expanding section headers.</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-485">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-485">Project</span></span>
- <span data-ttu-id="a0b79-486">Ein Problem wurde behoben, bei dem der Textumbruch in der Task- und Ressourcennutzungsansicht nicht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-486">Fixed an issue where text wrapping wasn't working in the task and resource usage views.</span></span>
- <span data-ttu-id="a0b79-487">Ein Problem wurde behoben, bei dem der Kostenwert bei Aufgaben möglicherweise nicht korrekt ist, wenn eine Ressource mehrere Kostensätze aufweist.</span><span class="sxs-lookup"><span data-stu-id="a0b79-487">Fixed an issue where if a resource has more than one cost rate, cost value on assignments may not be correct.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-488">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-488">Word</span></span>
- <span data-ttu-id="a0b79-489">Das Einfügen eines Steuerelements (z. B. eines Textinhaltssteuerelements) in eine Gleichung und das anschließende Speichern und Öffnen der Datei führte zu einem Fehler aufgrund nicht lesbaren Inhalts.</span><span class="sxs-lookup"><span data-stu-id="a0b79-489">Inserting a control (such as a Text Content Control) in an equation, then saving and opening the file would result in an un-readable content error.</span></span>
- <span data-ttu-id="a0b79-490">Bei der gemeinsamen Dokumenterstellung wird ein Kommentar, der mit Word Online hinzugefügt wurde, auf dem Word-Desktop möglicherweise nicht angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-490">When co-authoring, adding a comment using Word online may not appear in Word desktop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a0b79-491">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-491">Office Suite</span></span>
- <span data-ttu-id="a0b79-492">Die Anzeige eines falschen Ablaufdatums der gültigen Lizenz beim Versuch, eine Einzellizenz zu ändern, wurde entfernt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-492">Removed showing an erroneous expiry date of the valid license when trying to change license with only one license.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2001-december-13"></a><span data-ttu-id="a0b79-494">Version 2001: 13. Dezember</span><span class="sxs-lookup"><span data-stu-id="a0b79-494">Version 2001: December 13</span></span>
<span data-ttu-id="a0b79-495">*Version 2001 (Build 12410.20000)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-495">*Version 2001 (Build 12410.20000)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-497">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-497">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a0b79-498">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-498">Outlook</span></span>

- <span data-ttu-id="a0b79-499">**Ziehen Sie E-Mails in eine Gruppe, die Sie besitzen:** Verschieben und Kopieren von Nachrichten und Unterhaltungen, indem Sie diese aus Ihrem Posteingang ziehen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-499">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="a0b79-500">Die von ihnen gezogenen Nachrichten werden für alle Gruppenmitglieder freigegeben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-500">Messages you drag will be shared with all group members.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-503">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-503">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a0b79-504">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-504">Access</span></span>
- <span data-ttu-id="a0b79-505">Das Ausführen einer Verbundabfrage, die auf verknüpfte ODBC-Tabellen verweist und eine ORDER BY-Klausel enthält, stürzt den 64-Bit-Zugriff ab.</span><span class="sxs-lookup"><span data-stu-id="a0b79-505">Executing a union query that references linked ODBC table(s) and contains an Order By clause crashes 64 bit Access.</span></span>
- <span data-ttu-id="a0b79-506">Das Summieren von Daten aus Verbundsabfragen in Access (O365) kann zu einer Verkürzung der dezimalen Daten führen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-506">Summing of data from union queries in Access (O365) may result in truncation of decimal data.</span></span>
- <span data-ttu-id="a0b79-507">COM-Schnittstellen für ACE werden nicht für den Einsatz außerhalb von Office-Anwendungen freigegeben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-507">COM Interfaces for ACE are not exposed for use outside of Office applications.</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-508">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-508">Excel</span></span>
- <span data-ttu-id="a0b79-509">Das Einfügen eines 3D-Modells (animiert oder statisch) und der Versuch, als Bild zu speichern, funktioniert nicht.</span><span class="sxs-lookup"><span data-stu-id="a0b79-509">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>
- <span data-ttu-id="a0b79-510">Die Kurztaste (Alt + Strg + 7/8), um Feedback aus dem Backstage-Bereich zu starten, steht im Konflikt mit QWERTZ-Tastaturen (AltGr + 7/8).</span><span class="sxs-lookup"><span data-stu-id="a0b79-510">The shortkey (Alt+Ctrl + 7/8)  to launch feedback from backstage is in conflict with AZERTY keyboards (Alt-Gr + 7/8).</span></span> <span data-ttu-id="a0b79-511">Auswirkung: Benutzer sind möglicherweise nicht in der Lage, einige Zeichen wie: '\' zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-511">Impact: users may not be able to use some characters such as: '\'.</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-512">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-512">Outlook</span></span>
- <span data-ttu-id="a0b79-513">Behebt ein Problem, bei dem E-Mails an die für den Empfänger falsche Adresse gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-513">Addresses an issue that caused email to be sent to the wrong address for the recipient.</span></span>
- <span data-ttu-id="a0b79-514">Behebt ein Problem, das dazu führte, dass Outlook-Benutzern mit &quot;Lesezugriff&quot; auf ein Postfach fälschlicherweise erlaubte, den gelesenen/ungelesenen Status einer Nachricht zu ändern.</span><span class="sxs-lookup"><span data-stu-id="a0b79-514">Addresses an issue that caused Outlook to incorrectly allow users with &quot;read&quot; access to a mailbox to change the read/unread state of a message.</span></span>
- <span data-ttu-id="a0b79-515">Der Widerruf des Sicherheitszertifikats auf der Website ist für den Produkt Support nicht reproduzierbar.</span><span class="sxs-lookup"><span data-stu-id="a0b79-515">The revocation of the security certificate on the web site is not re-producible by Product Support.</span></span> <span data-ttu-id="a0b79-516">Die Protokollierung muss hinzugefügt werden, um die Ursache für das Problem zu beheben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-516">Logging needs to be added to help root cause the issue.</span></span>
- <span data-ttu-id="a0b79-517">Behebt ein Problem, bei dem Benutzer Synchronisationsfehler festgestellt haben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-517">Addresses an issue that caused users to see synchronization failures.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-518">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-518">PowerPoint</span></span>
- <span data-ttu-id="a0b79-519">Das Einfügen eines 3D-Modells (animiert oder statisch) und der Versuch, als Bild zu speichern, funktioniert nicht.</span><span class="sxs-lookup"><span data-stu-id="a0b79-519">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-520">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-520">Project</span></span>
- <span data-ttu-id="a0b79-521">Die Aufgabenarbeit wird im Summenrollup für manuell geplante Unteraufgaben nicht berechnet.</span><span class="sxs-lookup"><span data-stu-id="a0b79-521">Task work is not calculated in Summary roll-up for manually scheduled child tasks.</span></span>
- <span data-ttu-id="a0b79-522">Projekt-VBA-Code, der von einer Multifunktionsleiste aufgerufen wird, funktioniert möglicherweise nicht, wenn versucht wird, serverbasierte Projekte zu speichern.</span><span class="sxs-lookup"><span data-stu-id="a0b79-522">Project VBA Code invoked from a Ribbon button may not work when trying to save server-based Projects.</span></span>
- <span data-ttu-id="a0b79-523">Wenn Project nicht bereits ausgeführt wird, zeigt das Öffnen von Projektdateien aus einer SharePoint-Dokumentbibliothek einen Fehler an und die Datei wird nicht geöffnet.</span><span class="sxs-lookup"><span data-stu-id="a0b79-523">Unless Project is already running, opening Project files from a SharePoint document library displays an error and the file will not open.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-524">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-524">Word</span></span>
- <span data-ttu-id="a0b79-525">Das Speichern vorhandener Dateien funktioniert möglicherweise nicht.</span><span class="sxs-lookup"><span data-stu-id="a0b79-525">Saving existing files may not work.</span></span>
- <span data-ttu-id="a0b79-526">Die Verwendung der Pfeiltasten im Fenster des Editors für Rechtschreibung und Grammatik kann zu intermittierendem Flackern führen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-526">Using arrow keys in the Spelling and Grammar editor window may result in intermittent flickering.</span></span>
- <span data-ttu-id="a0b79-527">Bei der Behebung einer Nachverfolgung können zugehörige Kommentare nicht in Punktkommentare umgewandelt werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-527">When resolving a follow-up, associated comments may not convert to point comments.</span></span>
- <span data-ttu-id="a0b79-528">Das Einfügen eines 3D-Modells (animiert oder statisch) und der Versuch, als Bild zu speichern, funktioniert nicht.</span><span class="sxs-lookup"><span data-stu-id="a0b79-528">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a0b79-529">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-529">Office Suite</span></span>
- <span data-ttu-id="a0b79-530">Es wurde ein Problem behoben, bei dem Office-Update-Nachrichten in einer anderen Sprache als erwartet angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-530">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="a0b79-531">In Zukunft entsprechen Office-Update-Nachrichten ordnungsgemäß der Windows-Anzeigesprache.</span><span class="sxs-lookup"><span data-stu-id="a0b79-531">Going forward, Office update messages will correctly match the Windows display language.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1912-december-06"></a><span data-ttu-id="a0b79-533">Version 1912: 6. Dezember</span><span class="sxs-lookup"><span data-stu-id="a0b79-533">Version 1912: December 06</span></span>
<span data-ttu-id="a0b79-534">*Version 1912 (Build 12325.20012)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-534">*Version 1912 (Build 12325.20012)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-536">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-536">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a0b79-537">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-537">Outlook</span></span>

- <span data-ttu-id="a0b79-538">**Erweiterte Gruppen-E-Mail-Einstellungen:** Diese Funktion hilft Gruppenbenutzern dabei, die E-Mails oder Ereignisse anzupassen, die sie in ihrem Posteingang empfangen/verfolgen möchten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-538">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="a0b79-539">**Benennungsrichtlinie für Gruppen:** Mit einer Benennungsrichtlinie für Gruppen kann der IT-Administrator die Namen von Gruppen, die von Benutzern in der Organisation erstellt wurden, standardisieren und verwalten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-539">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="a0b79-540">Der Administrator kann festlegen, dass dem Namen einer Gruppe beim Erstellen ein bestimmtes Präfixes und ein Suffix hinzugefügt werden, und er kann bestimmte Wörter blockieren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-540">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="a0b79-541">Auf diese Weise kann die Verwendung von unpassenden Wörtern in Gruppennamen minimiert und die Darstellung von Gruppen in Ihrem Verzeichnis verwaltet werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-541">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="a0b79-542">Die Benennungsrichtlinie hilft außerdem Organisationen, die Teamwebsites bereitstellen, um diese je nach Abteilung zu kategorisieren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-542">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a0b79-543">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-543">Office Suite</span></span>

- <span data-ttu-id="a0b79-544">**Bereiche im Registerkartenformat:** Jetzt können Sie über die Registerkarten-Benutzeroberfläche auf der rechten Seite der App zwischen mehreren Bereichen wechseln.</span><span class="sxs-lookup"><span data-stu-id="a0b79-544">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="a0b79-545">Die Benutzeroberfläche wird nur angezeigt, wenn Sie mehr als 2 Fenster geöffnet haben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-545">The UI will only be visible when you have 2+ panes open.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-548">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-548">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-549">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-549">Excel</span></span>
- <span data-ttu-id="a0b79-550">Beim Speichern von Änderungen bei der Verwendung einiger nicht englischer Zeichengruppen tritt möglicherweise ein Fehler auf.</span><span class="sxs-lookup"><span data-stu-id="a0b79-550">Users may encounter an error when saving changes while using some non-English character sets.</span></span>
- <span data-ttu-id="a0b79-551">Beim Zugriff auf einen verborgenen benannten Bereich kann ein Fehler auftreten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-551">Users may encounter an error when accessing a hidden named range.</span></span>
- <span data-ttu-id="a0b79-552">Das Deaktivieren der Beschleunigung von Hardware-Grafiken mit 4K könnte die Wiedergabe von Zellen verzögern.</span><span class="sxs-lookup"><span data-stu-id="a0b79-552">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>
- <span data-ttu-id="a0b79-553">Das Löschen einer langen Formel, die eine Zellbegrenzung überlappt, wird möglicherweise weiterhin über die Zellbegrenzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-553">Clearing a long formula that overlaps a cell boundary may still display across the cell boundary.</span></span>
- <span data-ttu-id="a0b79-554">Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-554">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>
- <span data-ttu-id="a0b79-555">Dropdownmenü „Rand“ wird möglicherweise nicht ordnungsgemäß gerendert.</span><span class="sxs-lookup"><span data-stu-id="a0b79-555">Margin dropdown menu may not render correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="a0b79-556">OneNote</span><span class="sxs-lookup"><span data-stu-id="a0b79-556">OneNote</span></span>
- <span data-ttu-id="a0b79-557">Möglicherweise wird OneNote nicht über das Outlook-Add-in „Besprechungsnotizen“ geöffnet.</span><span class="sxs-lookup"><span data-stu-id="a0b79-557">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-558">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-558">Outlook</span></span>
- <span data-ttu-id="a0b79-559">Bei Aufbewahrungsrichtlinien für Bezeichnungen kann der Aufbewahrungszeitraum in Klammern anzeigt sein.</span><span class="sxs-lookup"><span data-stu-id="a0b79-559">Retention policy labels may display the retention time period in parenthesis.</span></span>
- <span data-ttu-id="a0b79-560">Auf Visitenkarten mit dem japanischem Sprachpaket können Leerzeichen angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-560">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>
- <span data-ttu-id="a0b79-561">Bilder, die in Outlook-E-Mail-Nachrichten Inline eingefügt wurden, können manchmal geändert werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-561">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-562">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-562">PowerPoint</span></span>
- <span data-ttu-id="a0b79-563">Wenn ein Benutzer zwei (oder mehr) verschiedene Videos auf einer Folie in einer Cloud-Datei hat, werden die Videobilder korrekt wiedergegeben, aber wenn der Benutzer zum Abspielen auf jedes einzelne klickt, ist der Videoinhalt derselbe.</span><span class="sxs-lookup"><span data-stu-id="a0b79-563">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>
- <span data-ttu-id="a0b79-564">In einigen Fällen geht Scrollen bei Touchscreen-Geräten nicht.</span><span class="sxs-lookup"><span data-stu-id="a0b79-564">In some cases, scrolling with touch devices will not work.</span></span>
- <span data-ttu-id="a0b79-565">Dropdownmenü „Rand“ wird möglicherweise nicht ordnungsgemäß gerendert.</span><span class="sxs-lookup"><span data-stu-id="a0b79-565">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="a0b79-566">Safelinks aus einer Office-Anwendung zu einer anderen können die verknüpfte Anwendung nicht starten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-566">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-567">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-567">Project</span></span>
- <span data-ttu-id="a0b79-568">Project stürzt ab, wenn Sie die Funktion „Projekte vergleichen“ verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="a0b79-568">Project may crash when you use the Compare Projects feature.</span></span>
- <span data-ttu-id="a0b79-569">Wenn Sie sich im dunklen Modus befinden, können Sie die Tabelle nicht lesen, wenn Sie zu einem Vorgang mit einer überlasteten Ressource im Vorgangsinspektor wechseln.</span><span class="sxs-lookup"><span data-stu-id="a0b79-569">If you are in Dark mode, when you go to the task inspector panel on a task with an over allocated resource, you are unable to read the table.</span></span>
- <span data-ttu-id="a0b79-570">Das Festlegen von Aufwand für Vorgänge, die keine Aufgaben haben, wird auf 1 Tag abgerundet.</span><span class="sxs-lookup"><span data-stu-id="a0b79-570">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-571">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-571">Word</span></span>
- <span data-ttu-id="a0b79-572">Das Speichern einer Datei nach einem Seriendruck funktioniert unter bestimmten Bedingungen möglicherweise nicht.</span><span class="sxs-lookup"><span data-stu-id="a0b79-572">Saving a file after doing a mail merge may not work under certain conditions.</span></span>
- <span data-ttu-id="a0b79-573">Im Organizer für Bausteine könnte eine ungültige Warnung angezeigt werden: &quot;Sie haben modifizierte Formen, Bausteine&quot;.</span><span class="sxs-lookup"><span data-stu-id="a0b79-573">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>
- <span data-ttu-id="a0b79-574">Der Kommentarbereich wird manchmal beim Kopieren/Einfügen neu geladen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-574">Comment pane sometimes gets reloaded when using copy/paste.</span></span>
- <span data-ttu-id="a0b79-575">Kommentare werden manchmal nicht in der richtigen Reihenfolge eingefügt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-575">Comments are sometimes not pasted in the correct order.</span></span>
- <span data-ttu-id="a0b79-576">Das Anwenden einer Vorlage, die aus einer mehrstufigen Liste mit benutzerdefinierten Formatvorlagen besteht, auf bestehende Dokumente kann unter bestimmten Bedingungen die Formatvorlage nicht beibehalten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-576">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>
- <span data-ttu-id="a0b79-577">Wenn Sie die Größe eines geteilten Bildschirms ändern, wird ggf. ein weiterer geteilter Bildschirm öffnen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-577">Resizing a split screen border may introduce an additional split screen.</span></span>
- <span data-ttu-id="a0b79-578">Dropdownmenü „Rand“ wird möglicherweise nicht ordnungsgemäß gerendert.</span><span class="sxs-lookup"><span data-stu-id="a0b79-578">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="a0b79-579">Wenn ein Benutzer auf einer Kommentarkarte erwähnt wird, wird möglicherweise JSON angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-579">At-mentioning a user in a comment card may show JSON.</span></span>
- <span data-ttu-id="a0b79-580">Safelinks aus einer Office-Anwendung zu einer anderen können die verknüpfte Anwendung nicht starten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-580">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a0b79-581">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-581">Office Suite</span></span>
- <span data-ttu-id="a0b79-582">Bei Produkten mit einer Formatierung für Japan wird der Nachname des Benutzerkontos in der falschen Reihenfolge angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-582">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>
- <span data-ttu-id="a0b79-583">Beim Bewegen des Mauszeigers über Kommentare wird möglicherweise eine TextBox-Kontur um den Kommentar angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-583">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1912-november-15"></a><span data-ttu-id="a0b79-585">Version 1912: 15. November</span><span class="sxs-lookup"><span data-stu-id="a0b79-585">Version 1912: November 15</span></span>
<span data-ttu-id="a0b79-586">*Version 1912 (Build 12307.20000)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-586">*Version 1912 (Build 12307.20000)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-588">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-588">Feature updates</span></span>
### <a name="insights-services"></a><span data-ttu-id="a0b79-589">Insights-Services</span><span class="sxs-lookup"><span data-stu-id="a0b79-589">Insights Services</span></span>
- <span data-ttu-id="a0b79-590">**Abfragen in natürlicher Sprache in "Excel-Ideen":** Die neue Funktion von "Excel-Ideen", mit der Sie eine Frage zu Ihren Daten in natürlicher Sprache stellen können.</span><span class="sxs-lookup"><span data-stu-id="a0b79-590">**Natural Language Queries in Ideas in Excel:** Excel Ideas's new capability to ask a natural language question about your data.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-593">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-593">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-594">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-594">Excel</span></span>
- <span data-ttu-id="a0b79-595">Die Funktion "Text in Spalte" könnte bei einigen Lokalisierungen nicht funktionieren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-595">Text to Column functionality may fail for some localizations.</span></span>
- <span data-ttu-id="a0b79-596">Beim Bearbeiten von dynamischen Arrayformeln innerhalb einer Zelle könnte Text außerhalb der Begrenzung der Zelle ausgerichtet werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-596">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell.</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-597">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-597">Outlook</span></span>
- <span data-ttu-id="a0b79-598">Es wurde die Möglichkeit des Erzwingens der S/MIME-Konfiguration über eine Gruppenrichtlinie hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-598">Added the ability to enforce S/MIME configuration via group policy.</span></span>
- <span data-ttu-id="a0b79-599">Eingebettete Bilder könnten kleiner als erwartet erscheinen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-599">Embedded images may appear smaller than expected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-600">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-600">PowerPoint</span></span>
- <span data-ttu-id="a0b79-601">Der Cursor verschwindet möglicherweise nach dem Verschieben des Fokus von einem Textinhalt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-601">Cursor may disappear after moving focus from text.</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-602">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-602">Project</span></span>
- <span data-ttu-id="a0b79-603">Es könnte ein Fehler hinsichtlich der Lizenzierung auftreten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-603">Users may experience an error regarding licensing.</span></span>
- <span data-ttu-id="a0b79-604">Die Schaltfläche "Heute" in der Datumsauswahl könnte ein falsches Datum festlegen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-604">The Today button in the date picker may sometimes set the incorrect date.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-605">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-605">Word</span></span>
- <span data-ttu-id="a0b79-606">Bei einem Rechtsklick könnte manchmal nicht das ganze Wort markiert werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-606">Right-clicking can sometimes not result in selecting the whole word.</span></span>
- <span data-ttu-id="a0b79-607">Nach der Konvertierung in ein vorgeschlagenes Format bleibt der Cursor u. U. in einem Objekt aktiv.</span><span class="sxs-lookup"><span data-stu-id="a0b79-607">The cursor may remain active within an object after converting to a suggested format.</span></span>
- <span data-ttu-id="a0b79-608">In einigen Szenarien werden Bilder in Nachrichten u. U. nicht ordnungsgemäß skaliert.</span><span class="sxs-lookup"><span data-stu-id="a0b79-608">Images in messages may be incorrectly scaled in some scenarios.</span></span>
- <span data-ttu-id="a0b79-609">Einige Designs erschweren es möglicherweise, den ausgewählten Kommentar zu erkennen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-609">Some themes may make it difficult to determine which comment is selected.</span></span>
- <span data-ttu-id="a0b79-610">Beim Auswählen eines Kommentarhinweises im Bereich "Ansicht wechseln" sollte jetzt der moderne Kommentarbereich angezeigt werden, wenn dieser verborgen war.</span><span class="sxs-lookup"><span data-stu-id="a0b79-610">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a0b79-611">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-611">Office Suite</span></span>
- <span data-ttu-id="a0b79-612">Das Antworten auf einen Kommentar könnte dazu führen, dass das Textfeld vertikal über den Rand des Bereichs hinaus erweitert wird.</span><span class="sxs-lookup"><span data-stu-id="a0b79-612">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1912-november-08"></a><span data-ttu-id="a0b79-614">Version 1912: 8. November</span><span class="sxs-lookup"><span data-stu-id="a0b79-614">Version 1912: November 08</span></span>
<span data-ttu-id="a0b79-615">*Version 1912 (Build 12231.20000)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-615">*Version 1912 (Build 12231.20000)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-617">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-617">Feature updates</span></span>
### <a name="user-lifecycle"></a><span data-ttu-id="a0b79-618">Lebenszyklus des Benutzers:</span><span class="sxs-lookup"><span data-stu-id="a0b79-618">User Lifecycle</span></span>
- <span data-ttu-id="a0b79-619">**Verbesserungen bei der AFO-Aktivierung:** Aktualisierungen der Bildschirme, die den Kunden beim Aktivieren der im Lieferumfang Ihres neuen PCs enthaltenen Office-Version angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-619">**Experience improvements for AFO activation:** Updates to the screens customers see when activating Office that comes bundled with their new PC.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-620">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-620">Word</span></span>
- <span data-ttu-id="a0b79-621">**Neue und verbesserte Online-Videofunktionen in Word:** Neue und sicherere Onlinevideoerfahrung, die Ihnen beim Einfügen neuer Videos und beim Abspielen vorhandener Videos in Word hilft.</span><span class="sxs-lookup"><span data-stu-id="a0b79-621">**New and improved online video experience in Word:** New and more secure online video experience to help you insert new videos and play existing videos in Word.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-624">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-624">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="a0b79-625">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-625">Outlook</span></span>
- <span data-ttu-id="a0b79-626">Zeitweiliger Absturz bei ordnerübergreifenden Inhalten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-626">Intermittent crash involving cross folder content.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a0b79-627">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-627">Office Suite</span></span>
- <span data-ttu-id="a0b79-628">Wenn Sie ein Diagramm aus Excel in PowerPoint einfügen, kann sich die Größe des Diagramms verringern.</span><span class="sxs-lookup"><span data-stu-id="a0b79-628">Pasting a chart from Excel to PowerPoint can reduce the size of the chart.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1911-november-01"></a><span data-ttu-id="a0b79-630">Version 1911: 1. November</span><span class="sxs-lookup"><span data-stu-id="a0b79-630">Version 1911: November 01</span></span>
<span data-ttu-id="a0b79-631">*Version 1911 (Build 12228.20020)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-631">*Version 1911 (Build 12228.20020)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-633">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-633">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-634">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-634">Excel</span></span>
- <span data-ttu-id="a0b79-635">**Nehmen Sie den Kontext mit ihren SVG-Objekten mit!:** Sie können jetzt den Text in Karten, Diagrammen und anderen SVG-Vektoren beibehalten, wenn Sie diese Objekte in Office konvertieren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-635">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="a0b79-636">**Sehen Sie sich die Stiftoptionen an, wenn Sie Ihren Surface Pen aufnehmen:** Wenn Sie Ihren Surface Pen in Word, Excel oder PowerPoint in die Hand nehmen, wird die Registerkarte „Zeichnen“ aktiviert, damit Sie ganz einfach die Stiftfarben auswählen können.</span><span class="sxs-lookup"><span data-stu-id="a0b79-636">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-637">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-637">PowerPoint</span></span>
- <span data-ttu-id="a0b79-638">**Nehmen Sie den Kontext mit ihren SVG-Objekten mit!:** Sie können jetzt den Text in Karten, Diagrammen und anderen SVG-Vektoren beibehalten, wenn Sie diese Objekte in Office konvertieren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-638">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="a0b79-639">**Sehen Sie sich die Stiftoptionen an, wenn Sie Ihren Surface Pen aufnehmen:** Wenn Sie Ihren Surface Pen in Word, Excel oder PowerPoint in die Hand nehmen, wird die Registerkarte „Zeichnen“ aktiviert, damit Sie ganz einfach die Stiftfarben auswählen können.</span><span class="sxs-lookup"><span data-stu-id="a0b79-639">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="visio"></a><span data-ttu-id="a0b79-640">Visio</span><span class="sxs-lookup"><span data-stu-id="a0b79-640">Visio</span></span>
- <span data-ttu-id="a0b79-641">**Erstellen von ansprechenden Visio-Diagrammen in Excel:** Visualisieren Sie Ihre Daten schnell und einfach in ansprechenden Visio-Diagrammen in Excel.</span><span class="sxs-lookup"><span data-stu-id="a0b79-641">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> <span data-ttu-id="a0b79-642">[Weitere Informationen](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span><span class="sxs-lookup"><span data-stu-id="a0b79-642">[Learn more](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-643">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-643">Word</span></span>
- <span data-ttu-id="a0b79-644">**Sehen Sie sich die Stiftoptionen an, wenn Sie Ihren Surface Pen aufnehmen:** Wenn Sie Ihren Surface Pen in Word, Excel oder PowerPoint in die Hand nehmen, wird die Registerkarte „Zeichnen“ aktiviert, damit Sie ganz einfach die Stiftfarben auswählen können.</span><span class="sxs-lookup"><span data-stu-id="a0b79-644">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

- <span data-ttu-id="a0b79-645">**Verbesserungen bei der gemeinsamen Dokumenterstellung:** Die gemeinsame Dokumenterstellung wurde verbessert, indem Inhaltsänderungen den anderen Benutzern nun nahezu immer in Echtzeit angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-645">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="a0b79-646">**Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.</span><span class="sxs-lookup"><span data-stu-id="a0b79-646">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-649">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-649">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-650">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-650">Excel</span></span>
- <span data-ttu-id="a0b79-651">Es wurde ein Problem behoben, durch das die Bearbeitung einer geschützten Datei von einer nicht vertrauenswürdigen Netzwerkfreigabe zum Absturz von Excel geführt haben könnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-651">Resolved an issue where Excel may crash when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="a0b79-652">Es wurde ein Problem behoben, bei dem das Löschen von Blättern mit Sparklines, die auf Daten auf einem anderen Arbeitsblatt verweisen, dazu führen könnte, dass die Datei beim erneuten Öffnen als fehlerhaft identifiziert wird.</span><span class="sxs-lookup"><span data-stu-id="a0b79-652">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="a0b79-653">Es wurde ein Problem behoben, bei dem Sie beim Konvertieren von Berichtsfiltern zusammen mit der restlichen PivotTable für Abfragen an tabellarische SQL-Server möglicherweise falsche Ergebnisse erhalten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-653">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="a0b79-654">Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Absturz führen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-654">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="a0b79-655">Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Absturz führen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-655">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-656">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-656">Outlook</span></span>
- <span data-ttu-id="a0b79-657">Bei einer weitergeleiteten e-Mail fehlen möglicherweise eingebettete Bilder.</span><span class="sxs-lookup"><span data-stu-id="a0b79-657">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="a0b79-658">Das Tool „Raumsuche“ zeigt bei verfügbaren Räumen möglicherweise &quot;Keine&quot; an.</span><span class="sxs-lookup"><span data-stu-id="a0b79-658">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="a0b79-659">Benutzer sind möglicherweise nicht in der Lage, Outlook-Profile mit strikter Mandantenbeschränkung zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-659">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-660">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-660">PowerPoint</span></span>
- <span data-ttu-id="a0b79-661">Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Absturz führen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-661">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-662">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-662">Project</span></span>
- <span data-ttu-id="a0b79-663">Der Benutzer kann eine Aufgabe nicht als erledigt markieren, und sie wird auf 99 % festgelegt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-663">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="a0b79-664">Überlastungen werden durch einen Abgleich nicht behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-664">Overallocations are not resolved by leveling.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-665">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-665">Word</span></span>
- <span data-ttu-id="a0b79-666">Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Absturz führen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-666">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="a0b79-667">Das Öffnen alter Dokumente und das anschließende Wechseln zur Registerkarte „Info“ kann zu einem Absturz führen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-667">Opening legacy documents and then going to the Info tab can cause a crash.</span></span>
- <span data-ttu-id="a0b79-668">Vorschläge der Dokumentprüfung werden nicht in Kontextmenüs angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-668">Proofing suggestins are not displaying in contextual menus.</span></span>
- <span data-ttu-id="a0b79-669">Inhaltsrichtlinien werden nicht ordnungsgemäß auf Kommentare angewendet.</span><span class="sxs-lookup"><span data-stu-id="a0b79-669">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="a0b79-670">Alte Kommentare, die mit dunklem Text geschrieben wurden, sind im dunklen Modus nicht sichtbar.</span><span class="sxs-lookup"><span data-stu-id="a0b79-670">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="a0b79-671">Bei Verwendung der AutoKorrektur für Koreanisch/Englisch werden möglicherweise falsche Zeichen angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-671">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="a0b79-672">Niedrigere Richtlinienbezeichnungen werden möglicherweise angewendet, wenn eine höhere Richtlinienbezeichnung Vorrang haben sollte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-672">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="a0b79-673">Die Links von cid:-Bildern aus Outlook-Nachrichten&nbsp;können nun auf Anforderung erfolgreich unterbrochen werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-673">The links of cid: images from Outlook messages&nbsp;can now be successfully broken when requested.</span></span>
- <span data-ttu-id="a0b79-674">Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Absturz führen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-674">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="a0b79-675">Die Suche im Navigationsbereich schlägt möglicherweise fehl.</span><span class="sxs-lookup"><span data-stu-id="a0b79-675">Searching from the Navigation pane may fail.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a0b79-676">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-676">Office Suite</span></span>
- <span data-ttu-id="a0b79-677">Einige Zeichnungen werden in der Vorschau oder in Bildschirmpräsentationen möglicherweise nicht angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-677">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="a0b79-678">Einige Katakana-Zeichen werden in einem vertikalen Textfeld möglicherweise nicht korrekt angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-678">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="a0b79-679">Der Versuch, eine Datei auf einer nicht verbundenen Netzwerkfreigabe zu speichern, kann zu einem Absturz führen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-679">Attempting to save a file to a disconnected network share may result in a crash.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1911-october-25"></a><span data-ttu-id="a0b79-681">Version 1911: 25. Oktober</span><span class="sxs-lookup"><span data-stu-id="a0b79-681">Version 1911: October 25</span></span>
<span data-ttu-id="a0b79-682">*Version 1911 (Build 12215.20006)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-682">*Version 1911 (Build 12215.20006)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-684">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-684">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="a0b79-685">Visio</span><span class="sxs-lookup"><span data-stu-id="a0b79-685">Visio</span></span>

- <span data-ttu-id="a0b79-686">**Erstellen von ansprechenden Visio-Diagrammen in Excel:** Visualisieren Sie Ihre Daten schnell und einfach in ansprechenden Visio-Diagrammen in Excel.</span><span class="sxs-lookup"><span data-stu-id="a0b79-686">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="a0b79-687">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a0b79-687">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="a0b79-688">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-688">Word</span></span>

- <span data-ttu-id="a0b79-689">**Verbesserungen bei der gemeinsamen Dokumenterstellung:** Die gemeinsame Dokumenterstellung wurde verbessert, indem Inhaltsänderungen den anderen Benutzern nun nahezu immer in Echtzeit angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-689">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="a0b79-690">**Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.</span><span class="sxs-lookup"><span data-stu-id="a0b79-690">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a0b79-693">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a0b79-693">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a0b79-694">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-694">Access</span></span>

- <div><span data-ttu-id="a0b79-695"><span>Möglicherweise ist die Datensatzanzahl falsch</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-695"><span>The record count could be incorrect</span></span></span></div>


### <a name="excel"></a><span data-ttu-id="a0b79-696">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-696">Excel</span></span>

- <div><span data-ttu-id="a0b79-697"><span>Wir haben die Leistung beim Löschen von Spalten mit verbundenen Zellen erheblich verbessert.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-697"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


- <div><span data-ttu-id="a0b79-698"><span>Es könnte Benutzern ggfs. nicht möglich sein, im Office 365-Format für Excel-Arbeitsmappen zu speichern</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-698"><span>Users could be prevented from saving in Office 365 Excel Workbook format</span></span></span></div>


- <div><span data-ttu-id="a0b79-699"><span>Kontrollkästchen wurden nicht ordnungsgemäß gerendert</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-699"><span>Checkboxes could not render correctly</span></span></span></div>


- <div><span data-ttu-id="a0b79-700"><span>Änderungen an der Größe eines Diagramms konnten nicht gespeichert werden.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-700"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="a0b79-701"><span>Einige VBA-Funktionen haben bei neuen Diagrammtypen einen Fehler zurückgegeben</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-701"><span>Some VBA functions would return an error on new chart types</span></span></span></div>


- <div><span data-ttu-id="a0b79-702"><span>Bei einigen Dialogfeldern zur Auswahl von Datenquellen wurde die Groß-/Kleinschreibung nicht beachtet</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-702"><span>Select Data Source dialogs were not case sensitive for some fields</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a0b79-703">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-703">PowerPoint</span></span>

- <div><span data-ttu-id="a0b79-704"><span>Änderungen an der Größe eines Diagramms konnten nicht gespeichert werden.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-704"><span>Changes to a chart size could not be saved</span></span></span></div>


### <a name="publisher"></a><span data-ttu-id="a0b79-705">Publisher</span><span class="sxs-lookup"><span data-stu-id="a0b79-705">Publisher</span></span>

- <div><span data-ttu-id="a0b79-706"><span>Shapes konnten außerhalb des Grafikrahmens angezeigt werden</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-706"><span>Shapes could appear outside of the graphics border</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a0b79-707">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-707">Word</span></span>

- <div><span data-ttu-id="a0b79-708"><span>Shapes konnten außerhalb des Grafikrahmens angezeigt werden</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-708"><span>Shapes could appear outside of the graphics border</span></span></span></div>


- <div><span data-ttu-id="a0b79-709"><span>Das Hervorheben von Text kann sich schwierig gestalten</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-709"><span>Highlighting text could be challenging</span></span></span></div>


- <div><span data-ttu-id="a0b79-710"><span>Ein Benutzer konnte daran gehindert werden, zu einem einzelnen Element im Editor zu navigieren.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-710"><span>A user could be prevented from navigating to an individual item in the editor</span></span></span></div>


- <div><span data-ttu-id="a0b79-711"><span>Möglicherweise wurden Grammatik- oder Rechtschreibfehler nicht hervorgehoben</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-711"><span>Grammar or spelling errors might not be highlighted</span></span></span></div>


- <div><span data-ttu-id="a0b79-712"><span>Änderungen an der Größe eines Diagramms konnten nicht gespeichert werden.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-712"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="a0b79-713"><span>Eine Visitenkarte konnte ggfs. nicht mehr geöffnet werden, nachdem eine Formatierung auf @mention angewendet wurde</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-713"><span>A contact card could be prevented from opening after apply formatting to an @ mention</span></span></span></div>


- <div><span data-ttu-id="a0b79-714"><span>Ein Problem wurde behoben, bei dem Nutzer ggfs. Word, Excel- und PowerPoint-Dokumente nicht mehr speichern konnten.&nbsp; Dieses Problem betraf Benutzer, die eine neue Datei erstellten und das Dialogfeld &quot;Modell speichern&quot; öffneten, nachdem Sie auf das Symbol "Speichern" geklickt oder STRG + S gedrückt hatten.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-714"><span>Resolvedan issue where users may be unable to save Word, Excel, and PowerPoint documents.&nbsp; This issue affects users that create a new file and bring up the &quot;Save as Model Dialog&quot; option after clicking on the Save icon or pressing Ctrl + S.</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a0b79-715">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-715">Office Suite</span></span>

- <div><span data-ttu-id="a0b79-716"><span>Leistungsproblem bei der Verwendung von Shapes unter Windows 7</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-716"><span>Performance issue when using Shapes on Windows 7</span></span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1911-october-18"></a><span data-ttu-id="a0b79-718">Version 1911: 18. Oktober</span><span class="sxs-lookup"><span data-stu-id="a0b79-718">Version 1911: October 18</span></span>
<span data-ttu-id="a0b79-719">*Version 1911 (Build 12209.20010)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-719">*Version 1911 (Build 12209.20010)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-721">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-721">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a0b79-722">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-722">Outlook</span></span>

- <span data-ttu-id="a0b79-723">**Senden Sie barrierefreie E-Mails an die Benutzer, die sie am dringendsten benötigen:** Outlook zeigt einen E-Mail-Tipp an, um sicherzustellen, dass Ihr Inhalt barrierefrei ist, wenn Sie ihn an einen Benutzer senden, der barrierefreien Inhalt bevorzugt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-723">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-724">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-724">PowerPoint</span></span>

- <span data-ttu-id="a0b79-725">**Optimieren Sie Ihre Präsentation für alle:** Die Barrierefreiheitsprüfung hilft Ihnen beim Anordnen von Objekten auf Ihren Folien, indem sie die Sprachausgabe berücksichtigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-725">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="office-suite"></a><span data-ttu-id="a0b79-726">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-726">Office Suite</span></span>

- <span data-ttu-id="a0b79-727">**Das Upload Center wird durch die Funktion „Dateien, die Ihre Aufmerksamkeit benötigen“ ersetzt:** Das Upload Center wird durch die in den Office-Anwendungen unter „Datei“ > „Öffnen“ angezeigte Funktion „Dateien, die Ihre Aufmerksamkeit benötigen“ ersetzt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-727">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="a0b79-728">Die neue Oberfläche ist moderner, besser integriert und im Vergleich zum Upload Center weniger aufdringlich.</span><span class="sxs-lookup"><span data-stu-id="a0b79-728">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a><span data-ttu-id="a0b79-731">Nicht sicherheitsrelevante Sicherheitsupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-731">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-732">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-732">Excel</span></span>

- <div><span data-ttu-id="a0b79-733"><span>Wir haben ein Problem behoben, bei dem Kontrollkästchen-Steuerelemente unter Verwendung der automatischen Anpassung der Zeilenhöhe verkleinert werden konnten</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-733"><span>Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span></span></div>


- <div><span data-ttu-id="a0b79-734"><span>Wir haben ein Problem gelöst, durch das das Auswählen einer Zelle nach dem Scrollen dazu führen konnte, dass die falsche Zelle ausgewählt wurde</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-734"><span>Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a0b79-735">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-735">Outlook</span></span>

- <div><span data-ttu-id="a0b79-736"><span>Wir haben ein Problem erkannt, durch das digitale Signaturen beim Signieren einer E-Mail-Nachricht mit einem digital signierten Anhang beschädigt werden könnten</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-736"><span>Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment</span></span></span></div>


- <div><span data-ttu-id="a0b79-737"><span>Wir haben ein Problem erkannt, bei dem lange Dateinamen nach dem Drag & Drop im Textkörper der Nachricht abgeschnitten wurden</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-737"><span>Identified an issue where long filenames were truncated after draging and droping to the message body</span></span></span></div>


- <div><span data-ttu-id="a0b79-738">Wir haben ein Problem erkannt, bei dem es sein konnte, dass das Suchfeld nicht mehr angezeigt werden könnte, wenn das Menüband auf automatisches Ausblenden eingestellt ist</span><span class="sxs-lookup"><span data-stu-id="a0b79-738">Identified an issue where the search box could disappear when the ribbon is set to hide automatically</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a0b79-739">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-739">PowerPoint</span></span>

- <div><span data-ttu-id="a0b79-740"><span>Es wurde ein Problem erkannt, bei dem das Seitenverhältnis für die Folienvorschau nicht ordnungsgemäß gesperrt bzw. entriegelt wurde</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-740"><span>Identified an issuewhere aspect ratio for the slide preview was not being properly locked/unlocked</span></span></span></div>

### <a name="project"></a><span data-ttu-id="a0b79-741">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-741">Project</span></span>

- <div><span data-ttu-id="a0b79-742">Wir haben ein Problem erkannt, bei dem Notizen, die während Aktualisierungsvorgängen eingegeben werden, möglicherweise nicht gespeichert werden</span><span class="sxs-lookup"><span data-stu-id="a0b79-742">Identified an issue where notes might not persist if entered while doing update tasks</span></span><br></div>


- <div><span data-ttu-id="a0b79-743">Wir haben ein Problem erkannt, bei dem eine Datei durch einen Benutzer gesperrt werden konnte, aber kein Benutzername in der Fehlermeldung angezeigt wird</span><span class="sxs-lookup"><span data-stu-id="a0b79-743">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message</span></span></div>


- <div><span data-ttu-id="a0b79-744"><span>Wir haben ein Problem erkannt, bei dem Benutzer beim Öffnen eines schreibgeschützten Projekts mehrere Nachrichten erhalten könnten</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-744"><span>Identified an issue where users could get several messages when opening a read-only project</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a0b79-745">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-745">Word</span></span>

- <div><span data-ttu-id="a0b79-746"><span>Bei der Anzeige von Kommentaren während der Verwendung einer Sprachausgabe wurde ein Problem erkannt</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-746"><span>Identified an issue when viewing comments while using a screen reader</span></span></span></div>


- <div><span data-ttu-id="a0b79-747"><span>Wir haben ein Problem festgestellt, bei dem einige Kritiken fälschlicherweise als Rechtschreib- oder Grammatikkritiken erkannt wurden</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-747"><span>Identified an issue where some critiques were misidentified as being spelling or grammar critiques</span></span></span></div>


- <div><span data-ttu-id="a0b79-748"><span>Wir haben ein Problem erkannt, bei dem ein neues Kommentardialogfeld manchmal nicht in den Fokus gesetzt werden konnte</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-748"><span>Identified an issue where a new comment dialog could sometimes not obtain focus</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a0b79-749">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-749">Office Suite</span></span>

- <div><span data-ttu-id="a0b79-750"><span>Wir haben ein Problem behoben, bei dem ein Upgrade durch die falsche Fehlermeldung &quot;Es wird bereits eine andere Installation ausgeführt&quot;</span> verhindert werden konnte</span><span class="sxs-lookup"><span data-stu-id="a0b79-750"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="a0b79-751"><span>Wir haben ein Problem erkannt, das sich auf die Synchronisierung einer lokalen Ressource mit einer Cloud-Ressource auswirken könnte</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-751"><span>Identified an issue which could affect syncing from a local resource to a cloud resource</span></span></span></div>

- <div><span data-ttu-id="a0b79-752"><span>Es wurde ein Problem erkannt, bei dem eine Willkommensnachricht einen ungültigen Link enthielt</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-752"><span>Identified an issue where a welcome message contained an invalid link</span></span></span></div>


[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-1910-october-11"></a><span data-ttu-id="a0b79-754">Version 1910: 11. Oktober</span><span class="sxs-lookup"><span data-stu-id="a0b79-754">Version 1910: October 11</span></span>
<span data-ttu-id="a0b79-755">*Version 1910 (Build 12130.20112)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-755">*Version 1910 (Build 12130.20112)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)
[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)
[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a><span data-ttu-id="a0b79-759">Nicht sicherheitsrelevante Sicherheitsupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-759">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-760">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-760">Excel</span></span>

- <div><span data-ttu-id="a0b79-761">Ein Problem beim Einfügen von Dateien als Objekt aus OneDrive wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-761">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="a0b79-762">Ein Problem wurde behoben, bei dem das Hyperlink-Format auf einige Inhalte nicht ordnungsgemäß angewendet werden konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-762">Resolved an issue where the hyperlink format could not be properly applied to some content</span></span></div>


- <div><span data-ttu-id="a0b79-763">Ein Problem wurde behoben, bei dem Formeln mit strukturierten absoluten Bezügen nicht ordnungsgemäß angepasst wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-763">Resolved an issue where formulas containing structured absolute references may be adjusted incorrectly</span></span></div>


- <div><span data-ttu-id="a0b79-764">Ein Problem wurde behoben, das beim Öffnen von in früheren Versionen von Office erstellten Arbeitsmappen in aktuellen Versionen von Office zu Programmabstürzen führen konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-764">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office</span></span></div>


- <div><span data-ttu-id="a0b79-765">Ein Problem wurde behoben, bei dem Inhalte, die aus Excel kopiert wurden, beim Einfügen in andere Office-Anwendungen falsch dargestellt werden konnten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-765">Resolved an issue where content copied from Excel could appear incorrect when pasted into other Office applications</span></span></div>


- <div><span data-ttu-id="a0b79-766">Es wurde ein Problem mit Farben behoben, die in der Vorschau beim Einfügen von Diagrammen mithilfe von Diagrammvorlagen verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-766">Fix to correct colors used in previews when inserting charts using chart templates</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a0b79-767">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-767">PowerPoint</span></span>

- <div><span data-ttu-id="a0b79-768">Es wurde ein Problem identifiziert, durch das ARC-Geräte die Verbindung verlieren können, wenn sie unter AirSpace WinComp ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-768">Identified an issue where ARC Devices could lose connection when running under AirSpace WinComp</span></span></div>


### <a name="word"></a><span data-ttu-id="a0b79-769">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-769">Word</span></span>

- <div><span data-ttu-id="a0b79-770">Ein Problem beim Einfügen von Dateien als Objekt aus OneDrive wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-770">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="a0b79-771">Die Wiederherstellungsschritte wurden verbessert, <span>um ein Problem zu beheben, das dazu führte, dass grafische Inhalte aus E-Mail-Threads gelöscht werden konnten.&nbsp;</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-771">Improved our recovery steps to f<span>ix an issue that caused graphical content to get deleted from email threads.&nbsp;</span></span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1910-october-04"></a><span data-ttu-id="a0b79-773">Version 1910: 04. Oktober</span><span class="sxs-lookup"><span data-stu-id="a0b79-773">Version 1910: October 04</span></span>
<span data-ttu-id="a0b79-774">*Version 1910 (Build 12126.20000)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-774">*Version 1910 (Build 12126.20000)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-776">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-776">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-777">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-777">Excel</span></span>

- <span data-ttu-id="a0b79-778">\*\*Add-In „Datenschnellansicht“: \*\* erstellen Sie schnell Visio-Flussdiagramme aus Excel.</span><span class="sxs-lookup"><span data-stu-id="a0b79-778">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="a0b79-779">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a0b79-779">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a><span data-ttu-id="a0b79-782">Nicht sicherheitsrelevante Sicherheitsupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-782">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-783">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-783">Excel</span></span>

- <div><span data-ttu-id="a0b79-784"><span>Ein Problem wurde behoben, bei dem der Druckbereich in der Seitenansicht nicht korrekt war.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-784"><span>We fixed an issue where the print area in print preview was not correct</span></span></span></div>


- <div><span data-ttu-id="a0b79-785"><span>Wir haben ein Problem behoben, durch das es gelegentlich nicht möglicher war, PivotTables während der gemeinsamen Dokumenterstellung zu aktualisieren</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-785"><span>We fixed an issue which could have prevented pivot tables from being refreshed during a co-authoring session</span></span></span></div>


### <a name="access"></a><span data-ttu-id="a0b79-786">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-786">Access</span></span>

- <div><span data-ttu-id="a0b79-787">Wir haben ein Problem behoben, bei dem Benutzer bei der Verwendung einer freigegebenen Datenbank die Fehlermeldung &quot;„inkonsistenter Zustand“&quot; erhalten konnten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-787">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="a0b79-788">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-788">Outlook</span></span>

- <div><span data-ttu-id="a0b79-789"><span>Es wurde ein Problem behoben, durch das die Duplikation von E-Mail-Ordnern verursacht werden konnte</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-789"><span>We fixed an issue which could have caused duplication of mail folders</span></span></span></div>


- <div><span data-ttu-id="a0b79-790"><span>Wir haben ein Problem behoben, das beim Senden einer s/MIME-verschlüsselten E-Mail-Nachricht eine falsche Fehlermeldung verursacht hat.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-790"><span>We fixed an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail</span></span></span></div>


- <div><span data-ttu-id="a0b79-791"><span>Wir haben ein Problem behoben, das manchmal zu einem Absturz führen konnte, wenn ein Benutzer eine Nachricht vom Typ „verpasste Unterhaltung“ von Skype empfängt</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-791"><span>We fixed an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype</span></span></span></div>


- <div><span data-ttu-id="a0b79-792"><span>Wir haben ein Problem behoben, durch das ein Speicherleck entstehen konnte</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-792"><span>We fixed an issue which could have resulted in a memory leak</span></span></span></div>


- <div><span data-ttu-id="a0b79-793"><span>Es wurde ein Problem behoben, durch das beim Speichern als Entwurf ein falscher Absender angezeigt werden konnte</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-793"><span>We fixed an issue which could have caused the senders name to change when saved as a draft</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a0b79-794">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-794">PowerPoint</span></span>

- <div><span></span></div><span data-ttu-id="a0b79-795">Es wurde ein Problem behoben, durch das TextRanges nach dem Einfügen von Text in den Platzhalter für Kopf-/Fußzeile/Foliennummer im Folienmaster und Folienlayout nicht mehr funktionieren konnten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-795">We fixed an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout</span></span>


- <div><span></span></div><span data-ttu-id="a0b79-796">Wir haben ein Problem behoben, durch das das Erstellen von Links beim Einfügen von Text mit Link verhindert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-796">We fixed an issue which prevented hyperlink from being created when pasting text with hyperlink</span></span>


- <div><span data-ttu-id="a0b79-797">Wir haben ein Problem behoben, durch das die ordnungsgemäße Funktion von Statistiken verhindert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-797">We fixed an issue which would prevent statistics from working correctly</span></span></div>


### <a name="word"></a><span data-ttu-id="a0b79-798">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-798">Word</span></span>

- <div><span data-ttu-id="a0b79-799"><span>Wir haben ein Problem behoben, durch das Schriftfarben nicht angewendet wurden</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-799"><span>We fixed an issue where font colors were not being committed</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a0b79-800">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-800">Office Suite</span></span>

- <div><span data-ttu-id="a0b79-801">Wir haben ein Problem behoben, durch welches der Versionsverlauf angeboten werden konnte, obwohl diese Funktion deaktiviert worden war</span><span class="sxs-lookup"><span data-stu-id="a0b79-801">We fixed an issue which could offer version history when that feature was disabled</span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1910-september-27"></a><span data-ttu-id="a0b79-803">Version 1910: 27. September</span><span class="sxs-lookup"><span data-stu-id="a0b79-803">Version 1910: September 27</span></span>
<span data-ttu-id="a0b79-804">*Version 1910 (Build 12119.20000)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-804">*Version 1910 (Build 12119.20000)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)
[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)
[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a><span data-ttu-id="a0b79-808">Nicht sicherheitsrelevante Sicherheitsupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-808">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-809">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-809">Excel</span></span>

- <div><span data-ttu-id="a0b79-810"><span>Es wurde ein Problem behoben, durch das Punkt-Linien-Diagramme beim Ändern der Reihensammlung nicht ordnungsgemäß dargestellt werden konnten.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-810"><span>We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a0b79-811">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-811">Outlook</span></span>

- <div><span data-ttu-id="a0b79-812"><span>Es wurde ein Problem behoben, durch das bei der Interaktion mit freigegebenen Kalenderordnern Berechtigungsfehler gemeldet wurden.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-812"><span>We fixed an issue which could have reported permission errors when interacting with shared calendar folders</span></span></span></div>


- <div><span data-ttu-id="a0b79-813"><span>Es wurde ein Problem behoben, das Benutzer eventuell daran gehindert hätte, Anlagen an Kalender hinzuzufügen</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-813"><span>We fixed an issue which could have prevented users from adding attachments to calendars</span></span></span></div>


- <div><span data-ttu-id="a0b79-814"><span>Es wurde ein Problem behoben, durch das beim Antworten auf eine digital signierte Nachricht Fehlermeldungen angezeigt wurden</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-814"><span>We fixed an issue which caused error messages to display when replying to a digitally signed message</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a0b79-815">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-815">Word</span></span>

- <div><span data-ttu-id="a0b79-816"><span> Es wurde ein Problem behoben, das zu Skalierungsproblemen führte, wenn auf Deskjet-Druckern gedruckt wurde</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-816"><span>We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a0b79-817">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-817">Office Suite</span></span>

- <div><span data-ttu-id="a0b79-818"><span>Es wurde ein Problem behoben, bei dem mittel-fett formatierter Text nicht ordnungsgemäß formatiert werden konnte</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-818"><span>We fixed an issue where medium bold text could be incorrectly styled</span></span></span></div>


- <div><span data-ttu-id="a0b79-819"><span>Es wurde ein Problem behoben, bei dem einem Benutzer beim Schließen einer Datei mit ausstehendem Upload eine falsche Fehlermeldung angezeigt wird</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-819"><span>We fixed an issue where a user could be given an incorrect error message when closing a file with a pending upload</span></span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1910-september-20"></a><span data-ttu-id="a0b79-821">Version 1910: 20. September</span><span class="sxs-lookup"><span data-stu-id="a0b79-821">Version 1910: September 20</span></span>
<span data-ttu-id="a0b79-822">*Version 1910 (Build 12112.20000)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-822">*Version 1910 (Build 12112.20000)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a><span data-ttu-id="a0b79-826">Nicht sicherheitsrelevante Sicherheitsupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-826">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-827">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-827">Excel</span></span>

- <div><span data-ttu-id="a0b79-828"><span>Es wurde ein Problem behoben, durch das Excel manchmal beim Start hängen geblieben ist.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-828"><span>We fixed an issue where Excel could sometimes hang at launch</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="a0b79-829">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-829">Outlook</span></span>

- <div><span data-ttu-id="a0b79-830"><span>Die Leistung der Raumauswahl bei einer großen Anzahl von verfügbaren Räumen wurde erheblich verbessert.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-830"><span>We significantly improved the performance of room selection when there are a large number of rooms available</span></span></span></div>


- <div><span data-ttu-id="a0b79-831"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Es wurde ein Problem behoben, durch das die Postfachsynchronisierung für Kunden mit mehreren Postfächern in Outlook nach der Migration zur modernen Authentifizierung in Office 365 verhindert wurde.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-831"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can prevent mailbox sync for customers with multiple mailboxes in Outlook when migrating to modern authentication in Office 365.</span></span></span><br></div>


- <div><span data-ttu-id="a0b79-832"><span>Es wurde ein Problem behoben, bei dem einige Zeichen in Signaturbeschriftungen im Dropdownmenü nicht angezeigt wurden</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-832"><span>We fixed an issue where some characters in signature labels would not display in the dropdown menu</span></span></span></div>


### <a name="project"></a><span data-ttu-id="a0b79-833">Projekt</span><span class="sxs-lookup"><span data-stu-id="a0b79-833">Project</span></span>

- <div><span data-ttu-id="a0b79-834"><span>Es wurde ein Problem behoben, das beim Ersetzen einer Unternehmensressource durch eine lokale Ressource zu einem Absturz führte</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-834"><span>We fixed an issue which could cause a crash when replacing an enterprise resource with a local resource</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a0b79-835">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-835">Word</span></span>

- <div><span data-ttu-id="a0b79-836"><span>Es wurde ein Problem behoben, durch das ein synchrones Scrollen in der Entwurfsdarstellung nicht ordnungsgemäß funktionierte</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-836"><span>We fixed an issue which could prevent synchronous scrolling from working properly in draft view</span></span></span></div>


- <div><span data-ttu-id="a0b79-837">Es wurde ein Problem behoben, durch das QuickInfos nach dem erstmaligen Speichern eines Dokuments zeitweise nicht ordnungsgemäß angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-837">We fixed an issue which could prevent Tool Tips from displaying properly after saving a document for the first time</span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1910-september-13"></a><span data-ttu-id="a0b79-839">Version 1910: 13. September</span><span class="sxs-lookup"><span data-stu-id="a0b79-839">Version 1910: September 13</span></span>
<span data-ttu-id="a0b79-840">*Version 1910 (Build 12105.20000)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-840">*Version 1910 (Build 12105.20000)*</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a><span data-ttu-id="a0b79-842">Nicht sicherheitsrelevante Sicherheitsupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-842">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-843">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-843">Excel</span></span>

- <div><span data-ttu-id="a0b79-844"><span>Ein Problem wurde behoben, das verhindern konnte, dass ein Benutzer Links in bestimmte geschützte Blättern einfügt</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-844"><span>We fixed an issue which could prevent a user from pasting hyperlinks in some protected sheets</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a0b79-845">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-845">Outlook</span></span>

- <div><span data-ttu-id="a0b79-846"><span>Ein Problem wurde behoben, bei dem die Benutzeroberfläche möglicherweise in einer kompakten Darstellung stecken blieb</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-846"><span>We fixed an issue where the UI could get stuck in a compact view</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a0b79-847">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-847">PowerPoint</span></span>

- <div><span data-ttu-id="a0b79-848"><span>Ein Problem wurde behoben, bei dem ein Benutzer beim Drucken in eine PDF-Datei möglicherweise eine Fehlermeldung erhielt</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-848"><span>We fixed an issue where a user could experience an error upon printing to PDF</span></span></span></div>


### <a name="project"></a><span data-ttu-id="a0b79-849">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-849">Project</span></span>

- <div><span data-ttu-id="a0b79-850"><span>Ein Problem wurde behoben, bei dem <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">Änderungen an einem Arbeitswert in einem Sammelvorgang zu einem Absturz führen konnten, wenn geschützte Arbeit aktiviert ist</span></span></span><span class="sxs-lookup"><span data-stu-id="a0b79-850"><span>We fixed an issue where <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">changes to a work value on a summary task could cause a crash if protected work is enabled</span></span></span></span></div>


- <span data-ttu-id="a0b79-851"><font size=2 style="background-color:rgb(255, 255, 255);">Ein Problem wurde behoben, durch das die Möglichkeit zum Synchronisieren von Ereignissen mit Enterprise-Kalendern verhindert werden konnte</font></span><span class="sxs-lookup"><span data-stu-id="a0b79-851"><font size=2 style="background-color:rgb(255, 255, 255);">We fixed an issue which could inhibit the ability to sync events with enterprise calendars</font></span></span>


### <a name="office-suite"></a><span data-ttu-id="a0b79-852">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-852">Office Suite</span></span>

- <div><span data-ttu-id="a0b79-853"><span>Ein Problem wurde behoben, durch das eine wiederholte Warnung zum Verwerfen lokaler Versionen einer Datei angezeigt werden konnte</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-853"><span>We fixed an issue which could cause a repeated warning to discard local versions of a file</span></span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1910-september-06"></a><span data-ttu-id="a0b79-855">Version 1910: 6. September</span><span class="sxs-lookup"><span data-stu-id="a0b79-855">Version 1910: September 06</span></span>
<span data-ttu-id="a0b79-856">*Version 1910 (Build 12030.20004)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-856">*Version 1910 (Build 12030.20004)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-858">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-858">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-859">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-859">Excel</span></span>

- <span data-ttu-id="a0b79-860">**Auf die Plätze, fertig, zeichnen!** Sobald Sie Ihren Surface Pen in der Hand halten, können Sie mit dem Zeichnen beginnen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-860">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="a0b79-861">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a0b79-861">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a><span data-ttu-id="a0b79-862">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-862">PowerPoint</span></span>

- <span data-ttu-id="a0b79-863">**Auf die Plätze, fertig, zeichnen!** Sobald Sie Ihren Surface Pen in der Hand halten, können Sie mit dem Zeichnen beginnen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-863">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="a0b79-864">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a0b79-864">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="a0b79-865">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-865">Word</span></span>

- <span data-ttu-id="a0b79-866">**Auf die Plätze, fertig, zeichnen!** Sobald Sie Ihren Surface Pen in der Hand halten, können Sie mit dem Zeichnen beginnen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-866">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="a0b79-867">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a0b79-867">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a><span data-ttu-id="a0b79-870">Nicht sicherheitsrelevante Sicherheitsupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-870">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-871">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-871">Excel</span></span>

- <div><span data-ttu-id="a0b79-872"><span>Es wurde ein Problem behoben, das dazu führen konnte, dass der Name der Schriftart im Menü von der verwendeten Schriftart abweicht</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-872"><span>We fixed an issue which could cause the font name in the ribbon to be different from the font being used</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a0b79-873">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-873">Outlook</span></span>

- <div><span data-ttu-id="a0b79-874"><span>Es wurde ein Problem behoben, das zu einer unangemessenen Ressourcennutzung von Outlook führen kann, wenn der geschützte Modus für eingeschränkte Websites im Internet Explorer deaktiviert ist</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-874"><span>We fixed an issue that could result in inappropriate resource consumption by Outlook when Protected Mode is disabled for Restricted Sites in Internet Explorer</span></span></span></div>


- <div><span data-ttu-id="a0b79-875"><span>Es wurde ein Problem behoben, das beim Einfügen eines Textes aus einer ANSI-Quelle manchmal dazu führen kann, dass Unicode-Zeichen angezeigt werden</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-875"><span>We fixed an issue which could sometimes cause Unicode characters to appear when pasting text from an ANSI source</span></span></span></div>


- <div><span data-ttu-id="a0b79-876"><span>Ein Problem wurde behoben, bei dem einige Benutzer in einer Gruppen-Planungsanzeige fälschlicherweise als offline angezeigt wurden</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-876"><span>We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a0b79-877">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-877">Word</span></span>

- <div><span data-ttu-id="a0b79-878"><span>Ein Problem wurde behoben, welches dazu führen konnte, dass Tabellenformatierung verloren ging</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-878"><span>We fixed an issue where table formatting could be lost</span></span></span></div>


- <div><span data-ttu-id="a0b79-879"><span>Wir haben ein Problem behoben, welches dazu führen konnte, dass die Tastenkombination STRG + V nicht ordnungsgemäß funktionierte</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-879"><span>We fixed an issue which could break the ctrl+v keyboard shortcut</span></span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1909-august-30"></a><span data-ttu-id="a0b79-881">Version 1909: 30. August</span><span class="sxs-lookup"><span data-stu-id="a0b79-881">Version 1909: August 30</span></span>
<span data-ttu-id="a0b79-882">*Version 1909 (Build 12026.20000)*</span><span class="sxs-lookup"><span data-stu-id="a0b79-882">*Version 1909 (Build 12026.20000)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a0b79-884">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-884">Feature updates</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-885">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-885">Access</span></span>

- <span data-ttu-id="a0b79-886">**Schnelle Suche nach verknüpften Tabellen:** Unser neues Suchfeld macht die Suche nach verknüpften Tabellen zu einem Kinderspiel.</span><span class="sxs-lookup"><span data-stu-id="a0b79-886">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-887">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-887">PowerPoint</span></span>

- <span data-ttu-id="a0b79-888">**Speichern einer Illustration als SVG:** Speichern Sie ein Diagramm, eine Form oder eine andere Abbildung als skalierbare Vektorgrafik, deren Größe ohne Verlust der Bildqualität geändert werden kann.</span><span class="sxs-lookup"><span data-stu-id="a0b79-888">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="a0b79-889">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a0b79-889">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a><span data-ttu-id="a0b79-892">Nicht sicherheitsrelevante Sicherheitsupdates</span><span class="sxs-lookup"><span data-stu-id="a0b79-892">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="a0b79-893">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-893">Excel</span></span>

- <div><span data-ttu-id="a0b79-894"><span>Wir haben ein Problem behoben, bei dem die Tastenkombination für&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Vertraulichkeit</span> mit&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">einer anderen Tastenkombination in Konflikt stand.</span></span></span><span class="sxs-lookup"><span data-stu-id="a0b79-894"><span>We fixed an issue where the keytip for&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensitivity </span>was&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">conflicting with another keytip.</span></span></span></span></div>

- <div><span data-ttu-id="a0b79-895"><span>Beim Speichern wurde ein Problem behoben, das beim Bearbeiten einer freigegebenen Arbeitsmappe auftrat, wenn versucht wurde zu speichern.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-895"><span>We fixed an issue that occurred while working on a shared workbook when trying to save.</span></span></span></div>

- <div><span data-ttu-id="a0b79-896"><span>Wir haben ein Problem behoben, bei dem Excel nur die ersten 16 Add-Ins auflistet, die sich in den „\Excel\Add-in Manager“ Registrierungswerten befinden.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span><span class="sxs-lookup"><span data-stu-id="a0b79-896"><span>We fixed an issue where Excel only lists the first 16 addins located in the '\Excel\Add-in Manager' registry values.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span></span></div>


- <div><span data-ttu-id="a0b79-897"><span>Wir haben ein Problem behoben, bei dem die Funktion „Häufigkeit()“ falsche Ergebnisse liefert.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-897"><span>We fixed an issue where the function Frequency() returns incorrect results.</span></span></span></div>


- <div><span data-ttu-id="a0b79-898"><span>Die Leistung der Filterung nach Farbe wurde deutlich verbessert.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-898"><span>We have significantly improved the performance of filtering by color.</span></span></span></div>


- <div><span data-ttu-id="a0b79-899"><span>Wir haben ein Problem für Surface-Benutzer behoben, bei dem das Bewegen der Maus als ein Mausklick interpretiert werden konnte.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-899"><span>We fixed an issue for Surface users where moving the mouse could be interpreted as a mouse click event.</span></span></span></div>


- <div><span data-ttu-id="a0b79-900"><span>Wir haben ein Problem behoben, das die Tastaturnavigation im Dialog „Suchen/Ersetzen“ verhinderte.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-900"><span>We fixed an issue which prevented keyboard navigation in the Find/Replace dialog</span></span></span></div>


- <div><span data-ttu-id="a0b79-901"><span>Wir haben ein Problem behoben, bei dem der Name einiger Schriftarten nicht korrekt angezeigt wurde.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-901"><span>We fixed an issue where the name of some fonts were not displayed correctly</span></span></span></div>


- <div><span data-ttu-id="a0b79-902"><span>Wir haben ein Problem behoben, durch das CSV nicht als unterstützter Dateityp angezeigt wurde.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-902"><span>We fixed an issue which prevented CSV from appearing as a supported file type</span></span></span></div>


### <a name="access"></a><span data-ttu-id="a0b79-903">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-903">Access</span></span>

- <div><span data-ttu-id="a0b79-904">Wir haben ein Problem behoben, bei dem Benutzer bei der Verwendung einer freigegebenen Datenbank die Fehlermeldung &quot;„inkonsistenter Zustand“&quot; erhalten konnten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-904">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


- <div><span data-ttu-id="a0b79-905"><span>Wir haben ein Problem behoben, bei dem die Datumsauswahl angezeigt wurde, wenn es nicht nötig war.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-905"><span>We fixed an issue which could cause the date picker to appear when it shouldn't</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a0b79-906">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-906">Outlook</span></span>

- <div><span data-ttu-id="a0b79-907"><span>Es wurde ein Problem behoben, das die Darstellung von HTML-Inhalten für einige POP3-Benutzer verhinderte.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-907"><span>We fixed an issue which prevented HTML content from appearing for some POP3 users</span></span></span></div>


- <div><span data-ttu-id="a0b79-908"><span>Es wurde ein Problem behoben, bei dem der nicht funktionierende Link "Planer" aus dem Überlaufmenü der Visitenkarte entfernt wurde, wenn Sie in Umgebungen arbeiten, in denen er nicht verfügbar ist.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-908"><span>We fixed an issue to remove non-functional 'Planner' link from the overflow menu in the contact card when working in environments where it is not available.</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="a0b79-909">OneNote</span><span class="sxs-lookup"><span data-stu-id="a0b79-909">OneNote</span></span>

- <div><span data-ttu-id="a0b79-910"><span>Es wurde ein Problem behoben&nbsp;, bei dem die Hintergrundsynchronisierung von OneNote manchmal den Fokus auf sich zog.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-910"><span>We fixed an issue where&nbsp;OneNote background sync was sometimes stealing focus.</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a0b79-911">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-911">PowerPoint</span></span>

- <div><span data-ttu-id="a0b79-912"><span>Wir haben ein Problem behoben, das sich auf die Drehrichtung eines 3D-Drehtisches auswirken würde.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-912"><span>We fixed an issue which would affect the rotation orientation of a 3D Turntable.</span></span></span></div>

- <div><span data-ttu-id="a0b79-913"><span>Wir haben ein Problem behoben, durch das einige Hyperlinks nicht mehr funktionierten, wenn sie Sonderzeichen enthielten.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-913"><span>We fixed an issue which prevented some hyperlinks from working if they contained special characters.</span></span></span></div>

- <div><span data-ttu-id="a0b79-914"><span>Es wurde ein Problem behoben, bei dem mehrere Kommentarfenster gleichzeitig geöffnet wurden.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-914"><span>We fixed an issue which caused multiple comment panes to open at the same time.</span></span></span></div>

### <a name="project"></a><span data-ttu-id="a0b79-915">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-915">Project</span></span>

- <div><span data-ttu-id="a0b79-916"><span>Wir haben ein Problem behoben, das nach dem Drucken einer Teamplaneransicht manchmal zu einem Absturz führen konnte.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-916"><span>We fixed an issue which could sometimes cause a crash after printing a Team Planner view.</span></span></span></div>

### <a name="word"></a><span data-ttu-id="a0b79-917">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-917">Word</span></span>

- <div><span data-ttu-id="a0b79-918">Wir <span>haben ein Problem behoben, bei dem Multibyte-Zeichen in vertikalem Textfeld in der Leseansicht überlappt dargestellt werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-918">We f<span>ixed an issue where multi-byte characters in vertical text box are shown overlapped in reading view.</span></span><br></span></div>

- <div><span data-ttu-id="a0b79-919"><span>Wir&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">haben ein Problem behoben, bei dem die japanischen Postkarten-und Grußkarten bezogenen Add-in-Ressourcen nicht gefunden werden, wenn der Benutzer im Add-in-Assistenten eine Aktion durchführt.</span></span></span><span class="sxs-lookup"><span data-stu-id="a0b79-919"><span>We&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">fixed an issue where Japanese post card and greeting card related addin resources are not found when the user takes action in the addin wizard.</span></span></span></span></div>

- <div><span data-ttu-id="a0b79-920"><span>Wir haben ein Problem behoben, das Schwierigkeiten mit der Benutzeroberfläche der Titelleiste verursachen konnte, wenn Sie sich in der geschützten Anzeige befinden.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-920"><span>We fixed an issue which could cause issues with the Title Bar User Interface when in Protected View</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="a0b79-921">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-921">Office Suite</span></span>

- <div><span data-ttu-id="a0b79-922"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> Wir haben ein Problem, das eine fehlerhafte Datei erzeugte, wenn Sie die Form in einer Auswahl ändern, die sowohl eine normale Form als auch eine Verbinder-Form enthält.</span></span></span><span class="sxs-lookup"><span data-stu-id="a0b79-922"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> We fixed a corrupt file issue when you Change Shape on a selection that contains both a normal shape and a connector shape.</span></span></span></span></div>

- <div><span data-ttu-id="a0b79-923"><span>Wir haben ein Problem behoben, das <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">zu einem Problem in Anwendungen führte, wenn man das An- und Abdocken von mehreren externen Displays verwendet.</span></span></span><span class="sxs-lookup"><span data-stu-id="a0b79-923"><span>We fixed an issue that <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">caused a problem in applications when using dock/undock from multiple external displays. </span></span></span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="august-23-2019br"></a><span data-ttu-id="a0b79-925">**23. August 2019**</span><span class="sxs-lookup"><span data-stu-id="a0b79-925">**August 23, 2019**</span></span><br/>
<span data-ttu-id="a0b79-926">Version 1909 (Build 12015.20004)</span><span class="sxs-lookup"><span data-stu-id="a0b79-926">Version 1909 (Build 12015.20004)</span></span><br/>



## <a name="non-security-updates"></a><span data-ttu-id="a0b79-927">Nicht sicherheitsrelevante Updates:</span><span class="sxs-lookup"><span data-stu-id="a0b79-927">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-928">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-928">Excel</span></span>

- <div><span data-ttu-id="a0b79-929"><span>Wir haben die Leistung beim Löschen von Spalten mit verbundenen Zellen erheblich verbessert.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-929"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a0b79-930">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-930">Office Suite</span></span>

- <div><span data-ttu-id="a0b79-931"><span>Es wurde ein Problem behoben, durch das einige Unicode-Zeichen nicht angezeigt werden konnten, wenn sie in einem Browser dargestellt werden sollten.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-931"><span>We fixed an issue which could prevent some Unicode characters from being displayed when viewed in a browser</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="a0b79-932">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-932">Outlook</span></span>

- <div><span data-ttu-id="a0b79-933"><span>Es wurde ein Problem behoben, durch das Dateien am WebDAV-Speicherort nicht gespeichert werden konnten.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-933"><span>We fixed an issue which could have prevented files from being saved to a WebDAV location</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a0b79-934">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-934">PowerPoint</span></span>

- <div><span data-ttu-id="a0b79-935"><span>Ein Problem wurde behoben, bei dem ein Benutzer auf einen Kommentar klickte, aber ein anderer Kommentar ausgewählt wurde.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-935"><span>We fixed an issue where a user would click on one comment, but another comment would be selected</span></span></span></div>





## <a name="august-16-2019br"></a><span data-ttu-id="a0b79-936">**16. August 2019**</span><span class="sxs-lookup"><span data-stu-id="a0b79-936">**August 16, 2019**</span></span><br/>
<span data-ttu-id="a0b79-937">Version 1909 (Build 12013.20000)</span><span class="sxs-lookup"><span data-stu-id="a0b79-937">Version 1909 (Build 12013.20000)</span></span><br/>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="a0b79-938">PowerPoint-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="a0b79-938">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="a0b79-939">**Drucken von Foliennummern auf Handzetteln:** Foliennummern werden automatisch in Ihre Handzettel integriert.</span><span class="sxs-lookup"><span data-stu-id="a0b79-939">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="a0b79-940">Sie können diese Funktion an- oder abschalten, wie es Ihnen beliebt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-940">Leave them on, turn them off, it's all up to you.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="a0b79-941">Nicht sicherheitsrelevante Updates:</span><span class="sxs-lookup"><span data-stu-id="a0b79-941">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-942">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-942">Excel</span></span>

- <div><span data-ttu-id="a0b79-943"><span>Wir haben ein Problem behoben, durch das sich die Funktion „Automatisches Speichern“ aktivieren konnte.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-943"><span>We fixed an issue which could cause AutoSave to become enabled</span></span></span></div>


- <div><span data-ttu-id="a0b79-944">Wir haben ein Problem behoben, das zur ungenauen Bemessung der Zellenhöhe führen konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-944">We fixed an issue which could result in cell heights being measured inaccurately</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="a0b79-945">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-945">Office Suite</span></span>

- <div><span data-ttu-id="a0b79-946"><span>Wir haben ein Problem behoben, das die Leistung der Kommentarfunktion erheblich verbessert.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-946"><span>We fixed an issue which significantly improves the performance of the Comments feature</span></span></span></div>


- <div><span data-ttu-id="a0b79-947"><span>Ein Problem wurde behoben, das bei der Verwendung von Pfeiltasten während der Suche zum Absturz führen konnte.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-947"><span>We fixed an issue which could cause a crash when using arrow keys while in search</span></span></span></div>


- <div><span data-ttu-id="a0b79-948"><span>Wir haben ein Problem behoben, durch das eine @Erwähnung verhindert werden konnte, wenn das @-Symbol nach bestimmten Zeichen gesetzt wurde.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-948"><span>We fixed an issue which could prevent an @ mention if the @ symbol was placed after certain characters</span></span></span></div>


- <div><span data-ttu-id="a0b79-949"><span>Wir haben ein Problem behoben, das beim Löschen von @Erwähnungen zum Absturz führen konnte.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-949"><span>We fixed an issue which could sometimes cause a crash when deleting @ mentions</span></span></span></div>


- <div><span data-ttu-id="a0b79-950"><span>Es wurde ein Problem behoben, durch das die korrekte Anzeige von Emojis in Kommentarkarten verhindert wurde.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-950"><span>We fixed an issue which prevented emojis from displaying correctly in comment cards</span></span></span></div>


- <div><span data-ttu-id="a0b79-951"><span>Es wurde ein Problem mit Active Clipboard behoben, das manchmal zum Absturz führen konnte.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-951"><span>We fixed an issue with Active Clipboard which could sometimes result in a crash</span></span></span></div>


- <div><span data-ttu-id="a0b79-952"><span>Wir haben ein Problem behoben, durch das die Schaltflächen für die Symbolleiste für den Schnellzugriff nicht mehr funktionierte.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-952"><span>We fixed an issue which could cause the Quick Access Toolbar buttons to stop working</span></span></span></div>


- <div><span data-ttu-id="a0b79-953"><span>Wir haben ein Problem behoben, durch das das Wechseln der Dokumentformatierungsvorschau in den Hintergrund verhindert werden konnte.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-953"><span>We fixed an issue which could prevent the Document Formatting Preview from switching to the background</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="a0b79-954">OneNote</span><span class="sxs-lookup"><span data-stu-id="a0b79-954">OneNote</span></span>

- <span data-ttu-id="a0b79-955">Ein Problem wurde behoben, bei dem die Namen von Abschnitten in der Dropdownliste „Abschnitt“ nicht dargestellt wurden, wenn das Office-Design auf „schwarz“ festgelegt war.</span><span class="sxs-lookup"><span data-stu-id="a0b79-955">We fixed an issue where the names of sections appear blank in the section dropdown list when Office Theme is set to Black.</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-956">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-956">Outlook</span></span>

- <div><span data-ttu-id="a0b79-957"><span>Wir haben ein Problem beim Senden von Ereignissen behoben, das dazu führen konnte, dass Outlook wiederholt fokussiert und den Fokus verliert.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-957"><span>We fixed an issue with Send Events which could cause Outlook to repeatedly gain and lose focus</span></span></span></div>


- <div><span data-ttu-id="a0b79-958"><span>Es wurde ein Problem behoben, durch das die Verknüpfung „Antwort im Ordner bereitstellen“ nicht funktionierte.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-958"><span>We fixed an issue which prevented the Post Reply to Folder shortcut from working</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-959">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-959">PowerPoint</span></span>

- <div><span data-ttu-id="a0b79-960"><span>Es wurde ein Problem mit der geschützten Ansicht behoben, das manchmal bei der Zusammenarbeit zu Problemen führen konnte.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-960"><span>We fixed an issue with Protected View which could sometimes cause problems when collaborating</span></span></span></div>


- <div><span data-ttu-id="a0b79-961"><span>Es wurde ein Problem behoben, das verhindern konnte, dass Aufgaben in Kommentarbereichen korrekt angezeigt werden.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-961"><span>We fixed an issue which could prevent tasks in comment panes from displaying properly</span></span></span></div>


- <div><span data-ttu-id="a0b79-962"><span>Ein Problem wurde behoben, das beim Einfügen neuer Folien zum Absturz führen konnte.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-962"><span>We fixed an issue which could cause a crash when inserting new slides</span></span></span></div>


### <a name="user-lifecycle"></a><span data-ttu-id="a0b79-963">Lebenszyklus des Benutzers:</span><span class="sxs-lookup"><span data-stu-id="a0b79-963">User Lifecycle</span></span>

- <div><span data-ttu-id="a0b79-964"><span>Es wurde ein Problem behoben, das manchmal dazu führte, dass Abonnementfeatures nicht mehr angezeigt wurden.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-964"><span>We fixed an issue which could sometimes result in subscription features disappearing</span></span></span></div>


### <a name="word"></a><span data-ttu-id="a0b79-965">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-965">Word</span></span>

- <div><span data-ttu-id="a0b79-966"><span>Es wurde ein Problem behoben, durch das Hyperlinks fehlerhaft sein konnten, wenn sie bestimmte Zeichen enthielten.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-966"><span>We fixed an issue where hyperlinks could be broken if the hyperlink contained certain characters</span></span></span></div>


- <div><span data-ttu-id="a0b79-967"><span>Ein Problem wurde behoben, bei dem beim Anzeigen eines Kommentars für ein Bild dieses manchmal nicht in der korrekten Größe dargestellt wurde.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-967"><span>We fixed an issue where images could be improperly sized when viewing a comment for that image</span></span></span></div>


- <div><span data-ttu-id="a0b79-968"><span>Es wurde ein Problem mit dem Dropdownmenü „Aufzählung“ behoben, das manchmal zu einem Absturz führten konnte.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-968"><span>We fixed an issue with the Bullet List drop down menu which could sometimes result in a crash</span></span></span></div>





## <a name="august-09-2019br"></a><span data-ttu-id="a0b79-969">**09. August 2019**</span><span class="sxs-lookup"><span data-stu-id="a0b79-969">**August 09, 2019**</span></span><br/>
<span data-ttu-id="a0b79-970">Version 1909 (Build 12001.20000)</span><span class="sxs-lookup"><span data-stu-id="a0b79-970">Version 1909 (Build 12001.20000)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="a0b79-971">Excel-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="a0b79-971">Excel Feature updates:</span></span>

- <span data-ttu-id="a0b79-972">**Zusammenarbeiten ist jetzt noch einfacher:** Verbesserungen bei der gemeinsamen Dokumenterstellung führen dazu, dass Ihre Änderungen beim Arbeiten mit bedingter Formatierung, Zellformatvorlagen und mehr nahtlos mit denen Ihrer Mitarbeiter zusammengeführt werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-972">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>


- <span data-ttu-id="a0b79-973">**Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können.</span><span class="sxs-lookup"><span data-stu-id="a0b79-973">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="a0b79-974">Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-974">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="office-suite-feature-updates"></a><span data-ttu-id="a0b79-975">Office-Suite-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="a0b79-975">Office Suite Feature updates:</span></span>

- <span data-ttu-id="a0b79-976">**Neue Office-App-Symbole:** Neu gestaltete App-Symbole, die die einfache, leistungsstarke und intelligente Oberfläche von Office widerzuspiegeln.</span><span class="sxs-lookup"><span data-stu-id="a0b79-976">**New Office app icons:** Redesigned app icons to reflect the simple, powerful, and intelligent experiences of Office</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="a0b79-977">Outlook-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="a0b79-977">Outlook Feature updates:</span></span>

- <span data-ttu-id="a0b79-978">**Erweiterter Schutz gegen Angriffe:** Mit Office 365 Advanced Threat Protection sind Sie vor Angriffen durch Links in E-Mail-Betreffzeilen, angefügten Nachrichten, signierten Nachrichten, Netzwerkpfaden usw. geschützt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-978">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>


- <span data-ttu-id="a0b79-979">**Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können.</span><span class="sxs-lookup"><span data-stu-id="a0b79-979">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="a0b79-980">Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-980">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="a0b79-981">PowerPoint-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="a0b79-981">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="a0b79-982">**Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können.</span><span class="sxs-lookup"><span data-stu-id="a0b79-982">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="a0b79-983">Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-983">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="a0b79-984">Word-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="a0b79-984">Word Feature updates:</span></span>

- <span data-ttu-id="a0b79-985">**Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.</span><span class="sxs-lookup"><span data-stu-id="a0b79-985">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


- <span data-ttu-id="a0b79-986">**Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können.</span><span class="sxs-lookup"><span data-stu-id="a0b79-986">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="a0b79-987">Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-987">And when you're selecting, the Insert button tells you how many you've picked.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="a0b79-988">Nicht sicherheitsrelevante Updates:</span><span class="sxs-lookup"><span data-stu-id="a0b79-988">Non-security updates:</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-989">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-989">Outlook</span></span>

- <div><span data-ttu-id="a0b79-990"><span>Ein Problem wurde behoben, das dazu führte, dass Besprechungsempfänger zwei Benachrichtigungen erhielten, nachdem eine Besprechung abgebrochen wurde</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-990"><span>We fixed an issue which caused meeting recipients to receive two notifications after a meeting was cancelled</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="a0b79-991">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-991">PowerPoint</span></span>

- <div><span data-ttu-id="a0b79-992"><span>Ein Problem wurde behoben, durch das ein Absturz verursacht werden konnte, wenn der Benutzer für Formen und Symbole "Keine Kontur" oder "Keine Füllung" auswählte</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-992"><span>We fixed an issue which could cause a crash when the user selected No Outline or No Fill for Shapes and Icons</span></span></span></div>





## <a name="august-02-2019br"></a><span data-ttu-id="a0b79-993">**02. August 2019**</span><span class="sxs-lookup"><span data-stu-id="a0b79-993">**August 02, 2019**</span></span><br/>
<span data-ttu-id="a0b79-994">Version 1908 (Build 11929.20002)</span><span class="sxs-lookup"><span data-stu-id="a0b79-994">Version 1908 (Build 11929.20002)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="a0b79-995">Excel-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="a0b79-995">Excel Feature updates:</span></span>

- <span data-ttu-id="a0b79-996">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="a0b79-996">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="a0b79-997">**Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente:** Sie können eine Vertraulichkeitsbezeichnung auf Ihre Dateien und E-Mails anwenden, damit sie den Richtlinien zum Datenschutz Ihrer Organisation entsprechen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-997">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="a0b79-998">Outlook-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="a0b79-998">Outlook Feature updates:</span></span>

- <span data-ttu-id="a0b79-999">**Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente:** Sie können eine Vertraulichkeitsbezeichnung auf Ihre Dateien und E-Mails anwenden, damit sie den Richtlinien zum Datenschutz Ihrer Organisation entsprechen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-999">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="a0b79-1000">PowerPoint-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1000">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="a0b79-1001">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1001">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="a0b79-1002">**Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente:** Sie können eine Vertraulichkeitsbezeichnung auf Ihre Dateien und E-Mails anwenden, damit sie den Richtlinien zum Datenschutz Ihrer Organisation entsprechen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1002">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="a0b79-1003">Word-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1003">Word Feature updates:</span></span>

- <span data-ttu-id="a0b79-1004">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1004">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="a0b79-1005">**Anders ausgedrückt:** Wenn Sie etwas anders formulieren möchten, hilft Ihnen „Neu schreiben“ dabei.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1005">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="a0b79-1006">„Neu schreiben“ bietet Alternativen zum Verbessern Ihrer Formulierungen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1006">Rewrite offers alternatives for finessing your phrases.</span></span>


- <span data-ttu-id="a0b79-1007">**Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente:** Sie können eine Vertraulichkeitsbezeichnung auf Ihre Dateien und E-Mails anwenden, damit sie den Richtlinien für den Datenschutz Ihrer Organisation entsprechen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1007">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="a0b79-1008">Nicht sicherheitsrelevante Updates:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1008">Non-security updates:</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1009">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1009">Access</span></span>
- <span data-ttu-id="a0b79-1010">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1010">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1011">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1011">Excel</span></span>

- <div><span data-ttu-id="a0b79-1012"><span>Es wurde ein Problem behoben, bei dem es so aussah, als ob die Option &quot;Alle Beschriftungen wiederholen&quot; beim Drucken in eine PDF-Datei angewendet wurde.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-1012"><span>We fixed an issue which made it appear as though &quot;repeat all labels&quot; was applied when printing to a PDF</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="a0b79-1013">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a0b79-1013">Office Suite</span></span>

- <div><span data-ttu-id="a0b79-1014"><span>Es wurde ein Problem behoben, durch das verhindert wurde, dass Benutzer ein Dokument auf dem Desktop öffnen.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-1014"><span>We fixed an issue which could have prevented users from opening a document from the desktop</span></span></span></div>

- <div><span data-ttu-id="a0b79-1015"><span>Es wurde ein Problem behoben, bei dem ein Upgrade durch eine falsche Fehlermeldung bei &quot;Es wird bereits eine andere Installation ausgeführt&quot;</span> verhindert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1015"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="a0b79-1016"><span>Es wurde ein Problem behoben, bei dem einem Benutzer beim Installieren von Sicherheitsupdates Fehlermeldungen angezeigt wurden.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-1016"><span>We fixed an issue where a user could see error messages when security updates are installed</span></span></span></div>

- <div><span data-ttu-id="a0b79-1017"><span>Es wurde ein Problem behoben, aufgrund dessen der Cursor verschwand.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-1017"><span>We fixed an issue which could cause the cursor to disappear</span></span></span></div>

- <div><span data-ttu-id="a0b79-1018"><span>Wir haben ein Problem behoben, bei dem für einen Benutzer standardmäßig die Registerkarte „Zeichnen“ der Registerkarte „Start“ angezeigt wurde.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-1018"><span>We fixed an issue where a user could be defaulted to the draw tab instead of the home tab</span></span></span></div>

- <div><span data-ttu-id="a0b79-1019"><span>Es wurde ein Problem behoben, bei dem große Strukturansichten zu einem Absturz führten.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-1019"><span>We fixed an issue where large tree views could result in a crash</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="a0b79-1020">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1020">Outlook</span></span>

- <div></div><span data-ttu-id="a0b79-1021"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Es wurde ein Problem behoben, durch das wiederholte Kennworteingabeaufforderungen verursacht werden können.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-1021"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can cause repeated password prompts</span></span></span>

- <div><span data-ttu-id="a0b79-1022"><span>Es wurde ein Problem behoben, durch das verhindert wurde, dass eine E-Mail-Adresse korrekt abgefragt wird.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-1022"><span>We fixed an issue which could prevent an email address from being queried correctly</span></span></span></div>

- <div><span data-ttu-id="a0b79-1023"><span>Es wurde ein Problem behoben, durch das verhindert wurde, dass Benutzer Kalenderelemente öffnen, die von älteren Versionen von Outlook erstellt wurden.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-1023"><span>We fixed an issue which could prevent users from opening calendar items created by legacy versions of Outlook</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1024">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1024">PowerPoint</span></span>

- <div><span data-ttu-id="a0b79-1025"><span>Es wurde ein Problem behoben, durch das verhindert wurde, dass einige Animationen gestartet werden.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-1025"><span>We fixed an issue which could prevent some animations from starting</span></span></span></div>

### <a name="project"></a><span data-ttu-id="a0b79-1026">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1026">Project</span></span>
- <span data-ttu-id="a0b79-1027">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1027">Various performance and stability fixes</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1028">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1028">Word</span></span>

- <div><span data-ttu-id="a0b79-1029"><span>Es wurde ein Problem behoben, bei dem Antworten auf Kommentare in falscher Reihenfolge angezeigt wurden.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-1029"><span>We fixed an issue where replies to comments could appear out of order</span></span></span></div>

- <div><span data-ttu-id="a0b79-1030"><span>Es wurde ein Problem behoben, bei dem in manchen Fällen Hinweise anstelle von Kommentaren angezeigt wurden.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-1030"><span>We fixed an issue where in some situations, hints would be displayed instead of comments</span></span></span></div>

- <div><span data-ttu-id="a0b79-1031"><span>Es wurde ein Problem behoben, bei dem der Bereich „Überprüfungen“ angezeigt wurde, wenn der Benutzer versuchte, einen neuen Kommentar hinzuzufügen.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-1031"><span>We fixed an issue where the Revisions Pane could display when the user tried to add a new comment</span></span></span></div>

- <div><span data-ttu-id="a0b79-1032"><span>Es wurde ein Problem behoben, durch das verhindert wurde, dass die Dropdownliste „Rückgängig machen“ angezeigt wird.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-1032"><span>We fixed an issue which could prevent the undo dropdown list from appearing</span></span></span></div>

- <div><span data-ttu-id="a0b79-1033"><span>Es wurde ein Problem behoben, durch das verhindert wurde, das Kommentare hinzugefügt werden.</span></span><span class="sxs-lookup"><span data-stu-id="a0b79-1033"><span>We fixed an issue which could prevent comments from being added</span></span></span></div>


## <a name="july-26-2019"></a><span data-ttu-id="a0b79-1034">26. Juli 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1034">July 26, 2019</span></span>
<span data-ttu-id="a0b79-1035">Version 1908 (Build 11916.20000)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1035">Version 1908 (build 11916.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1036">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1036">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="a0b79-1037">Word, Excel, PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1037">Word, Excel, PowerPoint</span></span>

#### <a name="create-more-accessible-pdfs"></a><span data-ttu-id="a0b79-1038">Erstellen von barrierefreien PDF-Dateien</span><span class="sxs-lookup"><span data-stu-id="a0b79-1038">Create more accessible PDFs</span></span>

<span data-ttu-id="a0b79-1039">Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1039">Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1040">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1040">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a0b79-1041">Alle</span><span class="sxs-lookup"><span data-stu-id="a0b79-1041">All</span></span>

- <span data-ttu-id="a0b79-1042">Ein Problem wurde behoben, bei dem die Zuordnung von Dateitypen und Symbolen für Office nach einem Office-Update manchmal entfernt wurden</span><span class="sxs-lookup"><span data-stu-id="a0b79-1042">We fixed an issue where file type association and icons for Office could sometimes break after an Office Update</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1043">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1043">Word</span></span> 
- <span data-ttu-id="a0b79-1044">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1044">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1045">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1045">Excel</span></span>
- <span data-ttu-id="a0b79-1046">Ein Problem wurde behoben, bei dem das Verschieben eines Diagramms manchmal zu einem Absturz führte</span><span class="sxs-lookup"><span data-stu-id="a0b79-1046">We fixed an issue where moving a chart could sometimes result in a crash</span></span>
- <span data-ttu-id="a0b79-1047">Ein Problem wurde behoben, bei dem das Abrufen eines Arbeitsmappenobjekts aus einem Diagrammobjekt nach dem Ändern von Diagrammtypen manchmal zu einem Fehler führte</span><span class="sxs-lookup"><span data-stu-id="a0b79-1047">We fixed an issue where to get Workbook object from Chart object after changing chart types could sometimes result in an error</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1048">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1048">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1049">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1049">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1050">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1050">Outlook</span></span>
- <span data-ttu-id="a0b79-1051">Ein Problem wurde behoben, bei dem im vereinfachten Menüband ein deaktiviertes Steuerelement manchmal nicht grau dargestellt wurde</span><span class="sxs-lookup"><span data-stu-id="a0b79-1051">We fixed an issue where in simplified ribbon, a disabled control could sometimes not be greyed out in the ribbon</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1052">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1052">Access</span></span>
- <span data-ttu-id="a0b79-1053">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1053">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1054">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1054">Project</span></span>
- <span data-ttu-id="a0b79-1055">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1055">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-19-2019"></a><span data-ttu-id="a0b79-1056">19. Juli 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1056">July 19, 2019</span></span>
<span data-ttu-id="a0b79-1057">Version 1908 (build 11911.20000)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1057">Version 1908 (build 11911.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1058">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1058">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1059">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1059">Word</span></span>

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a><span data-ttu-id="a0b79-1060">Informationen zur Bedeutung von Abkürzungen beim Lesen in Word Online</span><span class="sxs-lookup"><span data-stu-id="a0b79-1060">Learn what Acronyms mean when you read in Word Online</span></span>

<span data-ttu-id="a0b79-1061">Wenn Sie auf eine Abkürzung treffen, versuchen wir, diese mithilfe von Daten innerhalb Ihrer Organisation zu definieren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1061">When you encounter an Acronym, we'll try to define it using data from within your organization.</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1062">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1062">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1063">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1063">Word</span></span> 
- <span data-ttu-id="a0b79-1064">Das Problem des fehlenden BookMarkEnd-Tags wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1064">We fixed an issue which BookMarkEnd tag was missing.</span></span>
- <span data-ttu-id="a0b79-1065">Ein Problem wurde behoben, bei dem sich die Schriftartauswahl bei der Eingabe von Sonderzeichen ändern konnte</span><span class="sxs-lookup"><span data-stu-id="a0b79-1065">We fixed an issue where the font selection could change while the user was typing special characters</span></span>
- <span data-ttu-id="a0b79-1066">Ein Problem wurde behoben, das manchmal dazu führen könnte, dass Antworten auf eine neue Kommentarkarte leer waren</span><span class="sxs-lookup"><span data-stu-id="a0b79-1066">We fixed an issue which could sometimes cause blank replies to a new comment card</span></span>
- <span data-ttu-id="a0b79-1067">Ein Problem wurde behoben, das dazu führen könnte, dass Formatierungen beim Teilen einer E-Mail-Nachricht verloren gingen</span><span class="sxs-lookup"><span data-stu-id="a0b79-1067">We fixed an issue which could cause formatting to be lost when sharing an email</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1068">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1068">Excel</span></span>
- <span data-ttu-id="a0b79-1069">Ein Problem wurde behoben, durch das ein Array mit einem großen Bereich manchmal einen Absturz verursachte</span><span class="sxs-lookup"><span data-stu-id="a0b79-1069">We fixed an issue where an array with a large range could sometimes cause a crash</span></span>
- <span data-ttu-id="a0b79-1070">Die Leistung beim Kopieren von Daten aus gefilterten Bereichen wurde erheblich verbessert</span><span class="sxs-lookup"><span data-stu-id="a0b79-1070">We significantly improved the performance of copying data from filtered ranges</span></span>
- <span data-ttu-id="a0b79-1071">Ein Problem wurde behoben, durch das einige Dateien, deren Dateinamen Sonderzeichen enthielten, nicht geöffnet wurden</span><span class="sxs-lookup"><span data-stu-id="a0b79-1071">We fixed an issue which prevented some files from opening if the filenames contained special characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1072">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1072">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1073">Ein Problem wurde behoben, bei dem der Abschnittname für den neu erstellten Abschnitt in PowerPoint nicht standardmäßig aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1073">We fixed an issue where section name was not selected by default for newly created section in PowerPoint.</span></span>
- <span data-ttu-id="a0b79-1074">Ein Problem wurde behoben, durch das die Verwendung der Benutzeroberfläche in einer 4:3-Anzeige schwierig war</span><span class="sxs-lookup"><span data-stu-id="a0b79-1074">We fixed an issue which could cause the UI to become difficult to use when using a 4:3 display</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1075">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1075">Outlook</span></span>
- <span data-ttu-id="a0b79-1076">Ein Problem wurde behoben, durch das verfügbare Räume möglicherweise nicht aufgeführt wurden</span><span class="sxs-lookup"><span data-stu-id="a0b79-1076">We fixed an issue which could prevent available rooms from being listed</span></span>
- <span data-ttu-id="a0b79-1077">Ein Problem wurde behoben, durch das einige POP3-Benutzer keine HTML-Formatierungen verwenden konnten</span><span class="sxs-lookup"><span data-stu-id="a0b79-1077">We fixed an issue which prevented HTML formatting for some POP3 users</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1078">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1078">Access</span></span>
- <span data-ttu-id="a0b79-1079">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1079">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1080">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1080">Project</span></span>
- <span data-ttu-id="a0b79-1081">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1081">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-12-2019"></a><span data-ttu-id="a0b79-1082">12. Juli 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1082">July 12, 2019</span></span>
<span data-ttu-id="a0b79-1083">Version 1907 (Build 11901.20038)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1083">Version 1907 (build 11901.20038)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1084">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1084">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1085">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1085">PowerPoint</span></span>
 
#### <a name="use-ink-replay-in-your-presentations"></a><span data-ttu-id="a0b79-1086">Verwenden von Freihand-Wiedergabe in Präsentationen</span><span class="sxs-lookup"><span data-stu-id="a0b79-1086">Use ink replay in your presentations</span></span>
 
<span data-ttu-id="a0b79-1087">Verwenden Sie Wiedergabe-Animationen für Freihand in PowerPoint, um in Präsentationen mehr auszudrücken und zu kommunizieren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1087">Apply a replay animation for ink in PowerPoint to express and communicate more in presentations.</span></span> 

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1088">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1088">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1089">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1089">Word</span></span> 
- <span data-ttu-id="a0b79-1090">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1090">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1091">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1091">Excel</span></span>
- <span data-ttu-id="a0b79-1092">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1092">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1093">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1093">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1094">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1094">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1095">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1095">Outlook</span></span>
- <span data-ttu-id="a0b79-1096">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1096">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1097">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1097">Access</span></span>
- <span data-ttu-id="a0b79-1098">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1098">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1099">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1099">Project</span></span>
- <span data-ttu-id="a0b79-1100">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1100">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-5-2019"></a><span data-ttu-id="a0b79-1101">5. Juli 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1101">July 5, 2019</span></span>
<span data-ttu-id="a0b79-1102">Version 1907 (Build 11901.20018)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1102">Version 1907 (build 11901.20018)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1103">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1103">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="a0b79-1104">Word, Excel, PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1104">Word, Excel, PowerPoint</span></span>

#### <a name="sketchy-shapes"></a><span data-ttu-id="a0b79-1105">Skizzenhafte Formen!</span><span class="sxs-lookup"><span data-stu-id="a0b79-1105">Sketchy Shapes!</span></span>

<span data-ttu-id="a0b79-1106">Mitten im Entwurfs einer Präsentation?</span><span class="sxs-lookup"><span data-stu-id="a0b79-1106">In the middle of drafting a presentation?</span></span> <span data-ttu-id="a0b79-1107">Wenden Sie die Formatvorlage "Skizzenhaft" an, um anzuzeigen, dass Sie zurzeit noch am Entwurf arbeiten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1107">Apply the sketchy style to show that you're still working on it.</span></span> <span data-ttu-id="a0b79-1108">Dies verleiht Ihren Objekten eine persönliche Note, ohne sie in von Hand gezeichnete Freiformobjekte umzuwandeln.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1108">It gives a personal touch to your objects without turning it into a free form, hand-drawn shapes.</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1109">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1109">Excel</span></span>

- <span data-ttu-id="a0b79-1110">**Schnellere Dateifreigabe**: Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1110">**Faster file sharing**: Share your documents right from the recently used list without having to open the file.</span></span>
### <a name="powerpoint"></a><span data-ttu-id="a0b79-1111">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1111">PowerPoint</span></span>

- <span data-ttu-id="a0b79-1112">**Um den Zugriff zu erleichtern, wurde die Einstellung zum Drucken von Foliennummern in Handzetteln wurde in das Menü „Drucken“ verschoben:** Sie finden sie in der Dropdownliste Druck > Drucklayout, wenn ein Handzettellayout ausgewählt ist.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1112">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="a0b79-1113">Auf diese Weise können Sie die Einstellung auch für einzelne Präsentationen ganz einfach umschalten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1113">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="a0b79-1114">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a0b79-1114">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="a0b79-1115">**Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1115">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1116">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1116">Word</span></span>

- <span data-ttu-id="a0b79-1117">**Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1117">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1118">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1118">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a0b79-1119">Alle</span><span class="sxs-lookup"><span data-stu-id="a0b79-1119">All</span></span>
- <span data-ttu-id="a0b79-1120">Die Leistung der Menüband-Zugriffstasteninfos wurde erheblich verbessert</span><span class="sxs-lookup"><span data-stu-id="a0b79-1120">We significantly improved the performance of Ribbon KeyTips</span></span>
- <span data-ttu-id="a0b79-1121">Ein Problem wurde behoben, das verhinderte, dass das Dialogfeld "Erfahren Sie, was in Kürze verfügbar ist" ordnungsgemäß angezeigt wurde</span><span class="sxs-lookup"><span data-stu-id="a0b79-1121">We fixed an issue which prevented the "See what's coming soon" dialog from being displayed properly</span></span>
- <span data-ttu-id="a0b79-1122">Ein Problem wurde behoben, durch das Fotos im Katalogflyout für die gemeinsame Dokumenterstellung falsch ausgerichtet sein konnten</span><span class="sxs-lookup"><span data-stu-id="a0b79-1122">We fixed an issue which could cause Photos to be misaligned in the Co-auth Gallery flyout</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1123">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1123">Word</span></span> 
- <span data-ttu-id="a0b79-1124">Ein Problem wurde behoben, durch das manchmal das Hinzufügen neuer Kommentare verhindert wurde</span><span class="sxs-lookup"><span data-stu-id="a0b79-1124">We fixed an issue which could sometimes prevent new comments from being added</span></span>
- <span data-ttu-id="a0b79-1125">Ein Problem wurde behoben, durch das Tabellen manchmal einen Absturz verursachten</span><span class="sxs-lookup"><span data-stu-id="a0b79-1125">We fixed an issue where tables could sometimes cause a crash</span></span>
- <span data-ttu-id="a0b79-1126">Ein Problem wurde behoben, bei dem manchmal ungültige Daten ans Ende eines Seriendrucks angehängt wurden</span><span class="sxs-lookup"><span data-stu-id="a0b79-1126">We fixed an issue where invalid data could sometimes be added to the end of a mail merge</span></span>
- <span data-ttu-id="a0b79-1127">Ein Problem wurde behoben, durch das einige LaTeX-Gleichungen nicht ordnungsgemäß gerendert wurden</span><span class="sxs-lookup"><span data-stu-id="a0b79-1127">We fixed an issue which could cause some LaTeX equations to render incorrectly</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1128">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1128">Excel</span></span>
- <span data-ttu-id="a0b79-1129">Ein Problem wurde behoben, bei dem das Ändern von Diagrammtypen zu einer Laufzeitausnahme führen konnte</span><span class="sxs-lookup"><span data-stu-id="a0b79-1129">We fixed an issue where changing chart types could sometimes result in a runtime exception</span></span>
- <span data-ttu-id="a0b79-1130">Ein Problem wurde behoben, bei dem manchmal das falsche Menüband angezeigt wurde, wenn mehrere Fenster geöffnet waren</span><span class="sxs-lookup"><span data-stu-id="a0b79-1130">We fixed an issue where the incorrect ribbon could be displayed when multiple windows were open</span></span>
- <span data-ttu-id="a0b79-1131">Ein Problem wurde behoben, das einen Fehler verursachen konnte, wenn ein Makro eine zweite Instanz einer Arbeitsmappe öffnete</span><span class="sxs-lookup"><span data-stu-id="a0b79-1131">We fixed an issue which could cause an error when a macro opened a second instance of a workbook</span></span>
- <span data-ttu-id="a0b79-1132">Ein Problem wurde behoben, das beim Öffnen oder Erstellen einer Arbeitsmappe oder beim Wechseln zwischen Arbeitsmappen zu einem Absturz führen könnte</span><span class="sxs-lookup"><span data-stu-id="a0b79-1132">We fixed an issue which could cause a crash when opening or creating a workbook, or switching between workbooks</span></span>
- <span data-ttu-id="a0b79-1133">Ein Problem wurde behoben, das verhinderte, dass Benutzer eine aus Word erstellte PDF-Datei in Teams öffnen konnten</span><span class="sxs-lookup"><span data-stu-id="a0b79-1133">We fixed an issue preventing users from opening a PDF created from Word in Teams</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1134">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1134">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1135">Ein Problem wurde behoben, durch das die Qualität eines Diagramms beim Export in eine PDF-Datei beeinträchtigt wurde</span><span class="sxs-lookup"><span data-stu-id="a0b79-1135">We fixed an issue which would degrade the quality of a chart when exported to a pdf</span></span>
- <span data-ttu-id="a0b79-1136">Ein Problem wurde behoben, durch das eine QuickInfo, die die Entfernung zur Mitte angibt, nicht angezeigt wurde</span><span class="sxs-lookup"><span data-stu-id="a0b79-1136">We fixed an issue which prevented a tooltip indicating the distance to center from displaying</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1137">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1137">Outlook</span></span>
- <span data-ttu-id="a0b79-1138">Ein Problem wurde behoben, das manchmal die Anzeige des Fehlers "Datenträger voll" verhinderte</span><span class="sxs-lookup"><span data-stu-id="a0b79-1138">We fixed an issue which could sometimes prevent a Disk Full error to be displayed</span></span>
- <span data-ttu-id="a0b79-1139">Ein Problem wurde behoben, das dazu führen könnte, dass Anlagen beim Aktualisieren einer Besprechungsanfrage dupliziert wurden</span><span class="sxs-lookup"><span data-stu-id="a0b79-1139">We fixed an issue which could cause attachments to become duplicated when updating a meeting request</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1140">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1140">Access</span></span>
- <span data-ttu-id="a0b79-1141">Ein Problem wurde behoben, durch das einige Abfragen keine großen ganzzahligen Werte mehr zurückgeben konnten</span><span class="sxs-lookup"><span data-stu-id="a0b79-1141">We fixed an issue which prevented some queries from returning large integer values</span></span>
- <span data-ttu-id="a0b79-1142">Ein Problem wurde behoben, durch das SQL-Textfeld nicht mehr bearbeitet werden konnte</span><span class="sxs-lookup"><span data-stu-id="a0b79-1142">We fixed an issue which could make the sql textbox uneditable</span></span>
- <span data-ttu-id="a0b79-1143">Ein Problem wurde behoben, bei dem QuickInfos auf einigen High DPI-Displays schwer zu erkennen waren</span><span class="sxs-lookup"><span data-stu-id="a0b79-1143">We fixed an issue where tooltips could be difficult to see on some High DPI displays</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1144">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1144">Project</span></span>
- <span data-ttu-id="a0b79-1145">Ein Problem wurde behoben, durch das Flagwerte in neuen Vorgängen nicht mehr bearbeitet werden konnten</span><span class="sxs-lookup"><span data-stu-id="a0b79-1145">We fixed an issue which could cause flag values to become uneditable in new tasks</span></span>
- <span data-ttu-id="a0b79-1146">Ein Problem wurde behoben, durch das eine Statusaktualisierung dazu führen konnte, dass das tatsächliche Anfangsdatum bei Aufgaben und Vorgängen nicht ordnungsgemäß festgelegt wurde</span><span class="sxs-lookup"><span data-stu-id="a0b79-1146">We fixed an issue which could cause a status update to improperly set Actual Start Date on Assignments and Tasks</span></span>
- <span data-ttu-id="a0b79-1147">Ein Problem wurde behoben, das dazu führen könnte, dass einige Ressourcen fälschlicherweise als überlastet angezeigt wurden</span><span class="sxs-lookup"><span data-stu-id="a0b79-1147">We fixed an issue which could cause some resources to incorreclty appear overallocated</span></span>
- <span data-ttu-id="a0b79-1148">Ein Problem wurde behoben, bei dem die Methode "TaskDependencies Add" beim Hinzufügen von "Lag", wenn das Dezimaltrennzeichen ein Komma war und bei einer Verbindung mit einem Server manchmal fehlschlug</span><span class="sxs-lookup"><span data-stu-id="a0b79-1148">We fixed an issue where the TaskDependencies Add method could fail when Lag is added, the decimal separator is a comma, and when connected to a server</span></span>
- <span data-ttu-id="a0b79-1149">Es wurde ein Problem behoben, durch das das Aktualisieren von lokalen Werten der Nachschlagetabelle für das benutzerdefinierte Feld über CSOM zum Absturz des PCs führen konnte</span><span class="sxs-lookup"><span data-stu-id="a0b79-1149">We fixed an issue where updating local custom field lookup table values via CSOM could crash PCS</span></span>
- <span data-ttu-id="a0b79-1150">Ein Problem wurde behoben, bei dem die Werte für die gesamte Arbeit falsch erscheinen können, wenn sie eine Dezimalzahl enthalten</span><span class="sxs-lookup"><span data-stu-id="a0b79-1150">We fixed an issue where the total work values may appear incorrect if they contain a decimal</span></span>

</BR></BR>

## <a name="june-28-2019"></a><span data-ttu-id="a0b79-1151">28. Juni 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1151">June 28, 2019</span></span>
<span data-ttu-id="a0b79-1152">Version 1907 (Build 11819.20002)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1152">Version 1907 (build 11819.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1153">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1153">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1154">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1154">Excel</span></span>

- <span data-ttu-id="a0b79-1155">**Schnelles Programmieren mit Power Query-Verbesserungen:** Mit AutoVervollständigen und farbiger Syntax können Sie Code schnell fertigstellen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1155">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="a0b79-1156">Außerdem können Sie auf einfache Weise Funktionen, Spalten und Parameter ermitteln.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1156">Easily discover functions, columns, and parameters, too</span></span>

- <span data-ttu-id="a0b79-1157">**Verknüpfen von Tabellen in ähnlichen Spalten:** Abrufen & Transformieren (Power Query) bietet jetzt eine ungefähre Textübereinstimmungslogik (auch Fuzzy-Übereinstimmung genannt) beim Vergleichen von Spalten zum Zusammenführen von Tabellen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1157">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1158">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1158">Word</span></span>

- <span data-ttu-id="a0b79-1159">**Verbesserungen bei der gemeinsamen Dokumenterstellung:** Verbesserte Zuverlässigkeit bei der gemeinsamen Dokumenterstellung.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1159">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>
 
### <a name="word-excel-powerpoint-and-visio"></a><span data-ttu-id="a0b79-1160">Word, Excel, PowerPoint und Visio</span><span class="sxs-lookup"><span data-stu-id="a0b79-1160">Word, Excel, PowerPoint, and Visio</span></span>

#### <a name="recommended-documents"></a><span data-ttu-id="a0b79-1161">Empfohlene Dokumente</span><span class="sxs-lookup"><span data-stu-id="a0b79-1161">Recommended Documents</span></span>

<span data-ttu-id="a0b79-1162">Lassen Sie sich Dokumente mit für Sie relevanter Aktivität empfehlen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1162">Find documents with relevant activity recommended to you.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1163">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1163">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1164">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1164">Word</span></span> 
- <span data-ttu-id="a0b79-1165">Wir haben ein Problem behoben, welches einige Nutzer daran hindern konnte, einige .doc-Dateien zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1165">We fixed an issue which could prevent some .DOC files from opening</span></span>
- <span data-ttu-id="a0b79-1166">Wir haben ein Problem behoben, das gelegentlich verhindert hat, dass Kommentare richtig geladen wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1166">We fixed an issue which could have prevented comments from loading properly</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1167">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1167">Excel</span></span>
- <span data-ttu-id="a0b79-1168">Wir haben die Leistung von Power Queries verbessert.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1168">We improved the performance of Power Queries</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1169">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1169">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1170">Es wurde ein Problem mit der Verwendung eines Stifts auf einem Surface-Gerät behoben, der dazu führen konnte, dass der Bildschirm flackerte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1170">We fixed an issue related to using a pen on a Surface device which could cause the screen to flicker</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1171">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1171">Outlook</span></span>
- <span data-ttu-id="a0b79-1172">Wir haben ein Problem behoben, durch das der Frei/Gebucht-Status eines Termins bei der Konvertierung in eine Besprechung geändert werden konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1172">We fixed an issue which could change the free/busy status of an appointment when converted to a meeting</span></span>
- <span data-ttu-id="a0b79-1173">Ein Problem wurde behoben, bei dem die falsche Vorlage und Beschreibung angezeigt wurden, wenn eine E-Mail mit einer Ad-hoc-Vorlage geschützt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1173">We fixed an issue where the wrong template and description would be displayed when an e-mail was protected with an ad-hoc template</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1174">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1174">Access</span></span>
- <span data-ttu-id="a0b79-1175">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1175">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1176">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1176">Project</span></span>
- <span data-ttu-id="a0b79-1177">Verschiedene Korrekturen der Leistung und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1177">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-21-2019"></a><span data-ttu-id="a0b79-1178">21. Juni 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1178">June 21, 2019</span></span>
<span data-ttu-id="a0b79-1179">Version 1907 (build 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1179">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1180">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1180">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1181">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1181">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="a0b79-1182">Dunkler Modus für "schwarzes Design" in Outlook-Desktop</span><span class="sxs-lookup"><span data-stu-id="a0b79-1182">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="a0b79-1183">Im dunklen Modus wird nun Benutzern, die das Design "Schwarz" verwenden, auch der Lesebereich beim Lesen von E-Mails sowie die Verfassen-Oberfläche beim Schreiben von E-Mails mit einem dunklen Hintergrund angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1183">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="a0b79-1184">Mit Hilfe eines Sonne/Mond-Schalters im Lesebereich und im Menüband können Benutzer in einer Vorschau ansehen, wie eine Nachricht hingegen mit einem hellen Hintergrund aussieht.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1184">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a0b79-1185">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1185">Getting Started:</span></span>

1. <span data-ttu-id="a0b79-1186">Wählen Sie das schwarze Design aus. Der dunkle Modus ist in diesem Fall standardmäßig aktiviert.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1186">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="a0b79-1187">Verwenden Sie den Sonne/Mond-Schalter (im Lesebereich und im Menüband), um in einer Vorschau anzuzeigen, wie die Nachricht für Benutzer aussieht, die den dunklen Modus nicht aktiviert haben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1187">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1188">Szenarien zum Ausprobieren:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1188">Scenarios to Try</span></span>

1. <span data-ttu-id="a0b79-1189">Lesen von E-Mails im dunklen Modus.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1189">Read emails in dark mode.</span></span> <span data-ttu-id="a0b79-1190">Wenn Sie etwas nicht lesen können, verwenden Sie den Umschalter "Sonne" im Lesebereich, um zu einem hellen Hintergrund zu wechseln.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1190">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="a0b79-1191">Verfassen von E-Mails im dunklen Modus.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1191">Compose emails in dark mode.</span></span> <span data-ttu-id="a0b79-1192">Zeigen Sie mit Hilfe des Sonne-Schalters im Menüband in einer Vorschau an, wie Ihre Nachricht mit einem hellen Hintergrund aussehen wird.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1192">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="a0b79-1193">Sollten einzelne E-Mails nicht korrekt dargestellt werden, senden Sie diese bitte (als Anlage) an OutlookDarkModeFail@service.microsoft.com</span><span class="sxs-lookup"><span data-stu-id="a0b79-1193">If you encounter any emails that don't render properly, please send them (as an attachment) to OutlookDarkModeFail@service.microsoft.com</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="a0b79-1194">Abrufen von Standortvorschlägen</span><span class="sxs-lookup"><span data-stu-id="a0b79-1194">Get location suggestions</span></span>

<span data-ttu-id="a0b79-1195">Beginnen Sie mit der Eingabe, Outlook wird automatisch nach passenden Orten suchen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1195">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="a0b79-1196">Dies gilt für das Feld "Ort" beim Erstellen von Terminen und Besprechungen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1196">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a0b79-1197">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1197">Getting Started:</span></span>

- <span data-ttu-id="a0b79-1198">Erstellen Sie einen Termin oder eine Besprechung in einem O365- oder Outlook.com-Kalender in Outlook.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1198">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="a0b79-1199">Klicken Sie in das Feld "Ort", und beginnen Sie mit der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1199">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1200">Szenarien zum Ausprobieren:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1200">Scenarios to Try</span></span>

<span data-ttu-id="a0b79-1201">Wenn Sie einer Besprechung einen Konferenzraum hinzufügen möchten, klicken Sie auf das Feld "Ort", anstatt das "Raumsuche"-Add-in oder das Adressbuch zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1201">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="a0b79-1202">Versuchen Sie für Termine an einem öffentlichen Ort – beispielsweise ein Restaurant, ein Coffeeshop oder eine Zahnartpraxis – den exakten Standort mithilfe der neuen Auswahl zu finden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1202">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="a0b79-1203">Auf diese Weise können Sie über Outlook Mobile benachrichtigt werden, wenn es Zeit ist, aufzubrechen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1203">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1204">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1204">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a0b79-1205">Alle</span><span class="sxs-lookup"><span data-stu-id="a0b79-1205">All</span></span>
- <span data-ttu-id="a0b79-1206">Wir haben ein Problem behoben, durch das das Suchfeld im Offlinemodus aktiviert blieb.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1206">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1207">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1207">Word</span></span> 
- <span data-ttu-id="a0b79-1208">Ein Problem wurde behoben, bei dem der Tastaturfokus manchmal schwierig zu erkennen war.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1208">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="a0b79-1209">Ein Problem wurde behoben, bei dem der in ein neues Dokument eingefügte Text manchmal eine falsche Textausrichtung aufwies.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1209">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="a0b79-1210">Ein Problem wurde behoben, bei dem einige Benutzer nach dem Sperren des Computers keine Änderungen mehr speichern konnten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1210">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="a0b79-1211">Es wurde ein Problem behoben, bei dem in bestimmten Fällen statt des ausgewählten Bereichs das komplette Dokument gedruckt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1211">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="a0b79-1212">Ein Problem wurde behoben, durch das Kommentare auf kleineren Displays schwer zu lesen waren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1212">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="a0b79-1213">Ein Problem wurde behoben, durch das beim Erfassen von Daten auf einem Gerät ein Absturz verursacht werden konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1213">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1214">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1214">Excel</span></span>
- <span data-ttu-id="a0b79-1215">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1215">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1216">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1216">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1217">Ein Problem wurde behoben, bei dem der Tastaturfokus manchmal schwierig zu erkennen war.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1217">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1218">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1218">Outlook</span></span>
- <span data-ttu-id="a0b79-1219">Ein Problem wurde behoben, bei dem ein Add-In möglicherweise als aktiviert angezeigt wurde, auch wenn es nicht aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1219">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="a0b79-1220">Ein Problem wurde behoben, das dazu führte, dass einem Kunden möglicherweise nicht alle Aufbewahrungsrichtlinien angezeigt wurden, wenn sehr viele Aufbewahrungsrichtlinien vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1220">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1221">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1221">Access</span></span>
- <span data-ttu-id="a0b79-1222">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1222">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1223">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1223">Project</span></span>
- <span data-ttu-id="a0b79-1224">Verschiedene Korrekturen der Leistung und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1224">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="a0b79-1225">14. Juni 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1225">June 14, 2019</span></span>
<span data-ttu-id="a0b79-1226">Version 1907 (build 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1226">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1227">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1227">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1228">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1228">Word</span></span> 
- <span data-ttu-id="a0b79-1229">Es wurde ein Problem behoben, durch das Benutzer sich beim Speichern auf OneDrive nicht anmelden konnten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1229">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="a0b79-1230">Ein Problem wurde behoben, bei dem Benutzer daran gehindert werden konnten, SharePoint-Eigenschaften im eingeschränkten Zugriffsmodus zu ändern.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1230">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="a0b79-1231">Es wurde ein Problem behoben, bei dem sich die Kopf- und Fußzeileninhalte beim Anpassen von Seitenrändern ändern konnten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1231">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="a0b79-1232">Es wurde ein Problem behoben, bei dem die Formatierung beim Umschalten in die Webansicht unterbrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1232">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="a0b79-1233">Es wurde ein Problem behoben, durch das Benutzer daran gehindert werden konnten, benutzerdefinierte Felder beim Öffnen von SharePoint zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1233">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1234">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1234">Excel</span></span>
- <span data-ttu-id="a0b79-1235">Ein Leistungsproblem wurde behoben, das beim Löschen von Zeilen einer gefilterten Gruppe auftrat.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1235">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="a0b79-1236">Es wurde ein Problem behoben, das manchmal dazu führte, dass die Maus in der geschützten Anzeige flackert.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1236">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="a0b79-1237">Wir haben ein Problem behoben, das beim Löschen einer Reihe zu einem Absturz führen konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1237">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="a0b79-1238">Ein Problem wurde behoben, bei dem einige Benutzer die Möglichkeit hatten, Versionsverlauf hinzuzufügen, wenn diese Option nicht verfügbar war.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1238">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="a0b79-1239">Wir haben ein Problem behoben, das bei Verwendung des Tools „Arbeitsblattabgleich“ eine Ausnahme verursacht hat.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1239">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1240">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1240">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1241">Wir haben ein Problem behoben, durch das ein Absturz beim Klicken auf einen Link zu SharePoint verursacht werden konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1241">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="a0b79-1242">Wir haben ein Problem behoben, durch das der Benutzer zur nächsten Seite wechseln konnte, während er mit einem Surface-Stift tippte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1242">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1243">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1243">Outlook</span></span>
- <span data-ttu-id="a0b79-1244">Ein Problem wurde behoben, bei dem in manchen Fällen das Feld „An“ größer als normal war.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1244">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1245">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1245">Access</span></span>
- <span data-ttu-id="a0b79-1246">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1246">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1247">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1247">Project</span></span>
- <span data-ttu-id="a0b79-1248">Verschiedene Korrekturen der Leistung und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1248">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="a0b79-1249">7. Juni 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1249">June 7, 2019</span></span>
<span data-ttu-id="a0b79-1250">Version 1907 (Build 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1250">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1251">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1251">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1252">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1252">Word</span></span> 
- <span data-ttu-id="a0b79-1253">Ein Problem wurde behoben, bei dem Word manchmal abstürzt, wenn die AutoKorrektur so eingerichtet wurde, dass der erste Buchstabe eines Satzes groß geschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1253">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="a0b79-1254">Die Leistung beim Bearbeiten eines Dokuments in SharePoint wurde verbessert</span><span class="sxs-lookup"><span data-stu-id="a0b79-1254">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="a0b79-1255">Ein Problem wurde behoben, bei dem vektorbasierte Bilder, die in Adobe Illustrator erstellt wurden, nicht ordnungsgemäß angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1255">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1256">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1256">Excel</span></span>
- <span data-ttu-id="a0b79-1257">Ein Problem wurde behoben, bei dem die Sortierfelder beim Aufzeichnen eines Makros manchmal nicht ordnungsgemäß festgelegt wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1257">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="a0b79-1258">Ein Problem wurde behoben, das beim Neuberechnen einer Arrayformel ein Hängen oder einen Absturz verursacht.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1258">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1259">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1259">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1260">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1260">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1261">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1261">Outlook</span></span>
- <span data-ttu-id="a0b79-1262">Ein Problem wurde behoben, bei dem Inline-Anlagen manchmal nicht ordnungsgemäß skaliert wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1262">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1263">Zugriff</span><span class="sxs-lookup"><span data-stu-id="a0b79-1263">Access</span></span>
- <span data-ttu-id="a0b79-1264">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1264">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1265">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1265">Project</span></span>
- <span data-ttu-id="a0b79-1266">Ein Problem wurde behoben, bei dem Zeittabellen mit festgelegter Dauer manchmal den Endtermin der Aufgabe ändern konnten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1266">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="a0b79-1267">Ein Problem wurde behoben, bei dem die Werte für den Prozentsatz der Komplettierung beim Öffnen eines Projekts aus einer früheren Version falsch sein konnten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1267">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="a0b79-1268">31. Mai 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1268">May 31, 2019</span></span>
<span data-ttu-id="a0b79-1269">Version 1906 (build 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1269">Version 1906 (build 11722.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1270">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1270">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1271">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1271">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="a0b79-1272">Das Dialogfeld zum Kontaktieren des Supports ist jetzt andockbar und wird auf der rechten Seite angezeigt</span><span class="sxs-lookup"><span data-stu-id="a0b79-1272">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="a0b79-1273">Das zum Kontaktieren des Supports verwendete Dialogfeld wird jetzt in einem Bereich auf der rechten Seite angezeigt und beginnt als angedocktes Fenster.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1273">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="a0b79-1274">Freihand in Ihrer E-Mail!</span><span class="sxs-lookup"><span data-stu-id="a0b79-1274">Ink in Your Email!</span></span>

<span data-ttu-id="a0b79-1275">Sie können Bilder jetzt in Ihren Outlook-E-Mails zeichnen und kommentieren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1275">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1276">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1276">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="a0b79-1277">Öffnen von Dokument-Links in Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1277">Open document links in Word</span></span>

<span data-ttu-id="a0b79-1278">Wenn Sie in Office auf einen Dokument Link klicken, können Sie Ihre Einstellungen dahingehend aktualisieren, dass er standardmäßig in der Word-App geöffnet wird.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1278">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="a0b79-1279">Um Ihre Einstellungen zu aktualisieren, wechseln Sie zu Datei > Optionen – > Erweitert-> Verhalten von Links.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1279">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="a0b79-1280">Weitere Informationen: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="a0b79-1280">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a0b79-1281">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1281">Getting Started:</span></span>

<span data-ttu-id="a0b79-1282">Das Feature wird standardmäßig auf aus eingestellt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1282">Feature will default to off.</span></span> <span data-ttu-id="a0b79-1283">Benutzer können es entweder über Optionen > Erweitert > Verhalten von Links aktivieren, oder sie können ihm zustimmen, wenn Sie von Win32-WXP-Apps durch eine Opt-In-Umgebung geleitet werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1283">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="a0b79-1284">Links werden standardmäßig in der entsprechenden Office-Anwendung anstelle des Browsers geöffnet, wenn Benutzer in Outlook, Word, PowerPoint oder Excel auf Links zu Word/PowerPoint/Excel-Dateien klicken, die auf OneDrive, OneDrive für Business oder in SharePoint gespeichert sind.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1284">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="a0b79-1285">Um diese Standardeinstellung zu ändern, können Benutzer die folgende Einstellung in Outlook/Word/Excel/PowerPoint aktualisieren:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1285">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="a0b79-1286">Datei –> Optionen –> Erweitert –> Verhalten von Links.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1286">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="a0b79-1287">Diese Einstellung ist für Outlook/Word/PowerPoint/Excel freigegeben und kann in jeder dieser Apps festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1287">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1288">Szenarien zum Ausprobieren:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1288">Scenarios to Try:</span></span>

<span data-ttu-id="a0b79-1289">Lösen Sie die Opt-in-Benutzererfahrung aus – öffnen eines Links zu einem Word-Dokument, das in OneDrive/SharePoint aus Outlook/Word/PowerPoint/Excel aus gespeichert ist – klicken Sie aus Office Online auf in Client öffnen – tun Sie dies zwei Mal in einem Zeitraum von 30 Tagen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1289">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="a0b79-1290">Nachdem Sie die Einstellung gesetzt haben, werden Links standardmäßig in den Win32-Apps gestartet.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1290">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1291">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1291">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="a0b79-1292">Öffnen Sie Präsentationslinks in PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1292">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="a0b79-1293">Wenn Sie in Office auf einen Präsentationslink klicken, können Sie Ihre Einstellungen dahingehend aktualisieren, dass er standardmäßig in der PowerPoint-App geöffnet wird.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1293">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="a0b79-1294">Um Ihre Einstellungen zu aktualisieren, wechseln Sie zu Datei > Optionen – > Erweitert-> Verhalten von Links.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1294">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="a0b79-1295">Weitere Informationen: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="a0b79-1295">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a0b79-1296">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1296">Getting Started:</span></span>

<span data-ttu-id="a0b79-1297">Das Feature wird standardmäßig auf aus eingestellt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1297">Feature will default to off.</span></span> <span data-ttu-id="a0b79-1298">Benutzer können es entweder über Optionen > Erweitert > Verhalten von Links aktivieren, oder sie können ihm zustimmen, wenn Sie von Win32-WXP-Apps durch eine Opt-In-Umgebung geleitet werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1298">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="a0b79-1299">Links werden standardmäßig in der entsprechenden Office-Anwendung anstelle des Browsers geöffnet, wenn Benutzer in Outlook, Word, PowerPoint oder Excel auf Links zu Word/PowerPoint/Excel-Dateien klicken, die auf OneDrive, OneDrive für Business oder in SharePoint gespeichert sind.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1299">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="a0b79-1300">Um diese Standardeinstellung zu ändern, können Benutzer die folgende Einstellung in Outlook/Word/Excel/PowerPoint aktualisieren:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1300">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="a0b79-1301">Datei –> Optionen –> Erweitert –> Verhalten von Links.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1301">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="a0b79-1302">Diese Einstellung ist für Outlook/Word/PowerPoint/Excel freigegeben und kann in jeder dieser Apps festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1302">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1303">Szenarien zum Ausprobieren:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1303">Scenarios to Try:</span></span>

<span data-ttu-id="a0b79-1304">Lösen Sie die Opt-in-Benutzererfahrung aus – öffnen eines Links zu einer PowerPoint-Präsentation, die in OneDrive/SharePoint aus Outlook/Word/PowerPoint/Excel aus gespeichert ist – klicken Sie aus Office Online auf in Client öffnen – tun Sie dies zwei Mal in einem Zeitraum von 30 Tagen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1304">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="a0b79-1305">Nachdem Sie die Einstellung gesetzt haben, werden Links standardmäßig in den Win32-Apps gestartet.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1305">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1306">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1306">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="a0b79-1307">Öffnen von Arbeitsmappen-Links in Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1307">Open workbook links in Excel</span></span>

<span data-ttu-id="a0b79-1308">Wenn Sie in Office auf einen Link zu einer Arbeitsmappe klicken, können Sie Ihre Einstellungen dahingehend aktualisieren, dass diese standardmäßig in der Excel-App geöffnet wird.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1308">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="a0b79-1309">Um Ihre Einstellungen zu aktualisieren, wechseln Sie zu Datei > Optionen – > Erweitert-> Verhalten von Links.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1309">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="a0b79-1310">Weitere Informationen: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="a0b79-1310">Learn More: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a0b79-1311">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1311">Getting Started:</span></span>

<span data-ttu-id="a0b79-1312">Das Feature wird standardmäßig auf aus eingestellt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1312">Feature will default to off.</span></span> <span data-ttu-id="a0b79-1313">Benutzer können es entweder über Optionen > Erweitert > Verhalten von Links aktivieren, oder sie können ihm zustimmen, wenn Sie von Win32-WXP-Apps durch eine Opt-In-Umgebung geleitet werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1313">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="a0b79-1314">Links werden standardmäßig in der entsprechenden Office-Anwendung anstelle des Browsers geöffnet, wenn Benutzer in Outlook, Word, PowerPoint oder Excel auf Links zu Word/PowerPoint/Excel-Dateien klicken, die auf OneDrive, OneDrive für Business oder in SharePoint gespeichert sind.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1314">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="a0b79-1315">Um diese Standardeinstellung zu ändern, können Benutzer die folgende Einstellung in Outlook/Word/Excel/PowerPoint aktualisieren:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1315">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="a0b79-1316">Datei –> Optionen –> Erweitert –> Verhalten von Links.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1316">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="a0b79-1317">Diese Einstellung ist für Outlook/Word/PowerPoint/Excel freigegeben und kann in jeder dieser Apps festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1317">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1318">Szenarien zum Ausprobieren:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1318">Scenarios to Try:</span></span>

<span data-ttu-id="a0b79-1319">Lösen Sie die Opt-in-Benutzererfahrung aus – öffnen eines Links zu einer Excel-Arbeitsmappe, die in OneDrive/SharePoint aus Outlook/Word/PowerPoint/Excel aus gespeichert ist – klicken Sie aus Office Online auf in Client öffnen – tun Sie dies zwei Mal in einem Zeitraum von 30 Tagen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1319">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="a0b79-1320">Nachdem Sie die Einstellung gesetzt haben, werden Links standardmäßig in den Win32-Apps gestartet.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1320">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1321">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1321">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a0b79-1322">Alle</span><span class="sxs-lookup"><span data-stu-id="a0b79-1322">All</span></span>
- <span data-ttu-id="a0b79-1323">Wir haben ein Problem behoben, durch das Dateien manchmal automatisch gespeichert wurden, auch wenn die automatische Speicherung deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1323">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1324">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1324">Word</span></span> 
- <span data-ttu-id="a0b79-1325">Wir haben ein Problem behoben, das einige Benutzer daran gehindert hat, auf SharePoint zu speichern.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1325">We fixed an issue which may have prevented some users from saving to SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1326">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1326">Excel</span></span>
- <span data-ttu-id="a0b79-1327">Ein Problem wurde behoben, bei dem ein falsches Symbol für inaktive Filter angezeigt werden konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1327">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1328">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1328">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1329">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1329">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1330">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1330">Outlook</span></span>
- <span data-ttu-id="a0b79-1331">Ein Problem wurde behoben, bei dem einige Benutzer in einer Gruppen-Planungsanzeige fälschlicherweise als offline angezeigt wurden</span><span class="sxs-lookup"><span data-stu-id="a0b79-1331">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="a0b79-1332">Wir haben ein Problem behoben, das verhindert, dass SafeLink eine URL mit einem nachgestellten Leerzeichen analysiert</span><span class="sxs-lookup"><span data-stu-id="a0b79-1332">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="a0b79-1333">Ein Problem wurde behoben, bei dem Räume außerhalb der arbeitsfreien Zeiten als verfügbar angezeigt wurden</span><span class="sxs-lookup"><span data-stu-id="a0b79-1333">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1334">Zugriff</span><span class="sxs-lookup"><span data-stu-id="a0b79-1334">Access</span></span>
- <span data-ttu-id="a0b79-1335">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1335">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1336">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1336">Project</span></span>
- <span data-ttu-id="a0b79-1337">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1337">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="a0b79-1338">24. Mai 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1338">May 24, 2019</span></span>
<span data-ttu-id="a0b79-1339">Version 1906 (build 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1339">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1340">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1340">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="a0b79-1341">Updates für die Benutzeroberfläche</span><span class="sxs-lookup"><span data-stu-id="a0b79-1341">User Experience Updates</span></span>

<span data-ttu-id="a0b79-1342">Updates, die als „Bald verfügbar“ angezeigt wurden, sind jetzt verfügbar. Dazu gehört das vereinfachte Menüband sowie ein überarbeitetes Design für den Ordnerbereich, die Nachrichtenliste und den Lesebereich.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1342">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1343">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1343">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a0b79-1344">Alle</span><span class="sxs-lookup"><span data-stu-id="a0b79-1344">All</span></span>

- <span data-ttu-id="a0b79-1345">Ein Problem wurde behoben, bei dem der Chat-Bereich nicht angezeigt wurde</span><span class="sxs-lookup"><span data-stu-id="a0b79-1345">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1346">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1346">Word</span></span> 
- <span data-ttu-id="a0b79-1347">Ein Problem wurde behoben, bei dem in manchen Fällen Text fälschlicherweise als Grammatikfehler hervorgehoben werden konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1347">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1348">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1348">Excel</span></span>
- <span data-ttu-id="a0b79-1349">Ein Problem wurde behoben, bei dem ein falsches Symbol für Diagrammelemente verwendet wurde</span><span class="sxs-lookup"><span data-stu-id="a0b79-1349">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="a0b79-1350">Ein Problem wurde behoben, bei dem die falsche Arbeitsmappe in einem VBA-Skript aktiviert werden konnte, wenn die gleiche Mappe bereits geöffnet war.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1350">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1351">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1351">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1352">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1352">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1353">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1353">Outlook</span></span>
- <span data-ttu-id="a0b79-1354">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1354">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1355">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1355">Access</span></span>
- <span data-ttu-id="a0b79-1356">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1356">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1357">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1357">Project</span></span>
- <span data-ttu-id="a0b79-1358">Ein Problem wurde behoben, bei dem das Projekt nach dem Wechsel zur Taskleiste abstürzen konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1358">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="a0b79-1359">17. Mai 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1359">May 17, 2019</span></span>
<span data-ttu-id="a0b79-1360">Version 1906 (Build 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1360">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1361">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1361">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1362">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1362">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="a0b79-1363">Updates für die Benutzeroberfläche</span><span class="sxs-lookup"><span data-stu-id="a0b79-1363">User Experience Updates</span></span>

<span data-ttu-id="a0b79-1364">Updates, die als „Bald verfügbar“ angezeigt wurden, sind jetzt verfügbar. Dazu gehört das vereinfachte Menüband sowie ein überarbeitetes Design für den Ordnerbereich, die Nachrichtenliste und den Lesebereich.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1364">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a0b79-1365">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1365">Getting Started:</span></span>

<span data-ttu-id="a0b79-1366">Diese Änderungen sind Bestandteil der neuen Standardbenutzeroberfläche. Sie waren bereits seit Mitte Dezember zu 100% verfügbar, jedoch nur bei Aktivierung des Schalters „in Kürze verfügbar“.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1366">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="a0b79-1367">Anpassbares vereinfachtes Menüband</span><span class="sxs-lookup"><span data-stu-id="a0b79-1367">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="a0b79-1368">Sie können einfach zwischen klassischer und vereinfachter Ansicht sowie den Befehlen "Anheften" und "Lösen" wechseln.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1368">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a0b79-1369">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1369">Getting Started:</span></span>

<span data-ttu-id="a0b79-1370">Benutzer können zum vereinfachten Menüband wechseln, indem Sie zuerst „in Kürze verfügbar“ einschalten und dann auf das Chevron im Menüband klicken, um zwischen dem klassischen, mehrzeiligen Menüband und dem neuen, vereinfachten, einreihigen Menüband zu wechseln.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1370">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1371">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1371">Scenarios to Try:</span></span>

<span data-ttu-id="a0b79-1372">Wechseln zwischen dem klassischen Menüband und dem vereinfachten Menüband</span><span class="sxs-lookup"><span data-stu-id="a0b79-1372">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="a0b79-1373">Wählen Sie Ihre bevorzugte Aktion aus</span><span class="sxs-lookup"><span data-stu-id="a0b79-1373">Pick your favorite action</span></span>

<span data-ttu-id="a0b79-1374">Sie möchten „Kennzeichnen“ und „Löschen“ nicht verwenden?</span><span class="sxs-lookup"><span data-stu-id="a0b79-1374">Don't use Flag and Delete?</span></span> <span data-ttu-id="a0b79-1375">Wie sieht es mit „Archivieren“ oder „Als gelesen markieren2 aus?</span><span class="sxs-lookup"><span data-stu-id="a0b79-1375">How about Archive or Mark as Read?</span></span> <span data-ttu-id="a0b79-1376">Passen Sie das Menü mit schnellen Aktionen mit den am häufigsten verwendeten Befehlen an.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1376">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a0b79-1377">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1377">Getting Started:</span></span>

<span data-ttu-id="a0b79-1378">Wenn Sie Ihre schnellen Aktionen auswählen möchten, klicken Sie mit der rechten Maustaste auf eine e-Mail in der Nachrichtenliste, um das Kontextmenü aufzurufen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1378">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="a0b79-1379">Klicken sie dann auf „Schnelle Aktionen festlegen...“.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1379">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1380">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1380">Scenarios to Try:</span></span>

<span data-ttu-id="a0b79-1381">Ändern der Standardeinstellungen von „Kennzeichnen“ und „Löschen“ in „Archivieren“, „Bewegen“, „als gelesen markieren" oder "keine" für eine übersichtlichere Nachrichtenliste</span><span class="sxs-lookup"><span data-stu-id="a0b79-1381">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="a0b79-1382">Aufgelockertes oder engeres Layout?</span><span class="sxs-lookup"><span data-stu-id="a0b79-1382">Relaxed or tighter layout?</span></span> <span data-ttu-id="a0b79-1383">Sie haben die Wahl!</span><span class="sxs-lookup"><span data-stu-id="a0b79-1383">You choose</span></span>

<span data-ttu-id="a0b79-1384">Sie können entscheiden, ob Sie zwischen Elementen mehr Abstand wünschen oder ob Sie mehr Elemente in einem engeren Layout bevorzugen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1384">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a0b79-1385">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1385">Getting Started:</span></span>

<span data-ttu-id="a0b79-1386">In der Registerkarte „Ansicht“ das Kontrollkästchen „engere Abstände" aktivieren. Zu finden in „Nachrichten“ im klassischen Menüband; in „Aktuelle Ansichtseinstellungen“ im vereinfachten Menüband.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1386">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1387">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1387">Scenarios to Try:</span></span>

<span data-ttu-id="a0b79-1388">Verwenden Sie Outlook, um e-Mail-Nachrichten zu selektieren und zu schreiben, ohne die Einstellung zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1388">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="a0b79-1389">Bei Verwendung von „engere Abstände“ werden mehr Nachrichten pro Seite angezeigt, und die Steuerelemente in den Ansichten „Verfassen“ sind übersichtlicher.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1389">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="a0b79-1390">Deduplizieren von MRU-Einträgen bei Verwendung des Onedrive-Synchronisierungs Clients</span><span class="sxs-lookup"><span data-stu-id="a0b79-1390">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="a0b79-1391">Bessere Integration des OneDrive-Synchronisierungsclients mit Cloud-Anlagen durch Deduplizierung der MRU-Einträge und Aktivieren des schnelleren Anfügens als Kopierverhalten für synchronisierte Daten</span><span class="sxs-lookup"><span data-stu-id="a0b79-1391">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a0b79-1392">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1392">Getting Started:</span></span>

<span data-ttu-id="a0b79-1393">Wenn Sie den OneDrive-Synchronisierungsclient verwenden, werden in den „Datei anfügen“-MRU-Einträgen keine Dateiduplikate mehr angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1393">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1394">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1394">Scenarios to Try:</span></span>

<span data-ttu-id="a0b79-1395">Aktivieren des OneDrive-Synchronisierungsclients und Verwenden des Menüs „Datei anfügen“ in der Outlook-Desktopanwendung</span><span class="sxs-lookup"><span data-stu-id="a0b79-1395">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="a0b79-1396">Verbesserte Synchronisierung von freigegebenen Ordnern für Postfächer mit vielen Ordnern</span><span class="sxs-lookup"><span data-stu-id="a0b79-1396">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="a0b79-1397">Seit Jahren ist Outlook beim Synchronisieren von freigegebenen Postfächern auf maximal 500 Ordner beschränkt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1397">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="a0b79-1398">Mit dieser Änderung wurde Outlook so verbessert, dass es auf eine Weise synchronisiert wird, die dieser Beschränkung auf 500 Ordner nicht mehr unterliegt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1398">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a0b79-1399">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1399">Getting Started:</span></span>

<span data-ttu-id="a0b79-1400">Erstellen Sie in einem Postfach 1000 Ordner, geben Sie einer anderen Person Zugriff auf das Postfach, erstellen Sie ein Outlook-Profil für diese andere Person, und vergewissern Sie sich, dass die Synchronisierung funktioniert.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1400">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1401">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1401">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="a0b79-1402">Nur ein wenig löschen</span><span class="sxs-lookup"><span data-stu-id="a0b79-1402">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a0b79-1403">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1403">Getting Started:</span></span>

<span data-ttu-id="a0b79-1404">Wechseln Sie zur Registerkarte „Zeichnen“, und wählen Sie die Dropdownliste „Radierer“ aus.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1404">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="a0b79-1405">Wählen Sie den kleinen Radierer oder den mittleren Radierer aus.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1405">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1406">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1406">Scenarios to Try:</span></span>

<span data-ttu-id="a0b79-1407">Wechseln Sie zur Registerkarte „Zeichnen“, und wählen Sie einen Stift aus.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1407">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="a0b79-1408">Zeichnen Sie einen Strich.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1408">Draw an ink stroke.</span></span> <span data-ttu-id="a0b79-1409">Wählen Sie die Dropdownliste „Radierer“ aus.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1409">Select the Eraser dropdown.</span></span> <span data-ttu-id="a0b79-1410">Wählen Sie den kleinen Radierer oder den mittleren Radierer aus.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1410">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="a0b79-1411">Radieren Sie nur Teile des Striches aus.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1411">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1412">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1412">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a0b79-1413">Alle</span><span class="sxs-lookup"><span data-stu-id="a0b79-1413">All</span></span> 
- <span data-ttu-id="a0b79-1414">Wir haben ein Problem behoben, welches einige Nutzer daran hindern konnte eine PDF-Datei zu speichern.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1414">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="a0b79-1415">Wir haben ein Problem behoben, welches sich auf Nutzer ausgewirkt hat, die große Dateien auf einem 32-Bit System speicherten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1415">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1416">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1416">Word</span></span> 
- <span data-ttu-id="a0b79-1417">Die Reaktionsfähigkeit des Diktat-Features wurde erheblich verbessert.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1417">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1418">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1418">Excel</span></span>
- <span data-ttu-id="a0b79-1419">Wir haben ein Problem behoben, bei dem Doppelklick-Ereignisse auf Touchscreen-Geräten fehlschlagen konnten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1419">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="a0b79-1420">Wir haben ein Problem behoben, welches einige Nutzer daran hindern konnte VBA Makros zu bearbeiten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1420">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="a0b79-1421">Wir haben ein Problem behoben, welches sich auf die Performance bei der Nutzung von Slicers auswirken konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1421">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1422">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1422">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1423">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1423">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1424">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1424">Outlook</span></span>
- <span data-ttu-id="a0b79-1425">Es wurde ein Problem behoben, bei dem statt der ausgewählten Vorlage eine falsche angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1425">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1426">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1426">Access</span></span>
- <span data-ttu-id="a0b79-1427">Wir haben ein Problem behoben, bei dem bei der Verwendung von Zoom Builder zum Anzeigen langer Rich Text schwer lesbar sein konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1427">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1428">Projekt</span><span class="sxs-lookup"><span data-stu-id="a0b79-1428">Project</span></span>
- <span data-ttu-id="a0b79-1429">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1429">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="a0b79-1430">10. Mai 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1430">May 10, 2019</span></span>
<span data-ttu-id="a0b79-1431">Version 1906 (Build 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1431">Version 1906 (build 11702.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1432">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1432">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1433">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1433">Outlook</span></span>

<span data-ttu-id="a0b79-1434">**Mehr Nachrichten am Bildschirm anzeigen:** Wählen Sie „Anzeigen“ > Engere Abstände verwenden, um die Abstände zwischen den Nachrichten anzupassen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1434">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1435">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1435">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a0b79-1436">Alle</span><span class="sxs-lookup"><span data-stu-id="a0b79-1436">All</span></span>
- <span data-ttu-id="a0b79-1437">Ein Problem wurde behoben, bei dem im Dialogfeld "Speichern unter" manchmal ein falscher Pfad angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1437">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1438">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1438">Word</span></span> 
- <span data-ttu-id="a0b79-1439">Ein Problem wurde behoben, bei dem einige Auswahloptionen aus der Funktion "Was möchten Sie tun?" nicht eingefügt wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1439">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1440">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1440">Excel</span></span>
- <span data-ttu-id="a0b79-1441">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1441">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1442">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1442">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1443">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1443">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1444">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1444">Outlook</span></span>
- <span data-ttu-id="a0b79-1445">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1445">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1446">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1446">Access</span></span>
- <span data-ttu-id="a0b79-1447">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1447">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1448">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1448">Project</span></span>
- <span data-ttu-id="a0b79-1449">Ein Problem wurde behoben, bei dem Aufgaben-IDs manchmal nur angezeigt wurden, wenn sie markiert wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1449">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="a0b79-1450">3. Mai 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1450">May 3, 2019</span></span>
<span data-ttu-id="a0b79-1451">Version 1906 (Build 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1451">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1452">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1452">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1453">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1453">Outlook</span></span>

<span data-ttu-id="a0b79-1454">**Alle Verschlüsselungsoptionen an einem zentralen Ort:** Gehen Sie einfach zu „Optionen“ > „Verschlüsseln“, um auszuwählen, wie Ihre E-Mail-Nachricht gesichert werden soll.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1454">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1455">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1455">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="a0b79-1456">Alle</span><span class="sxs-lookup"><span data-stu-id="a0b79-1456">All</span></span>
- <span data-ttu-id="a0b79-1457">Ein Problem wurde behoben, bei dem bei einigen Benutzern Probleme beim Synchronisieren mit OneDrive for Business auftraten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1457">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1458">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1458">Word</span></span> 
- <span data-ttu-id="a0b79-1459">Ein Problem wurde behoben, bei dem Word in einigen Fällen sehr lange zum Starten brauchte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1459">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1460">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1460">Excel</span></span>
- <span data-ttu-id="a0b79-1461">Ein Problem wurde behoben, bei dem externe Links nach dem Upgrade auf eine neuere Version von Excel manchmal aus Arbeitsmappen entfernt wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1461">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="a0b79-1462">Ein Problem wurde behoben, bei dem einige Benutzern Schwierigkeiten beim Auswählen von Zellen in einer neuen Arbeitsmappen hatten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1462">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1463">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1463">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1464">Ein Problem wurde behoben, bei dem Schriftgrade beim Konvertieren von Freihandzeichnungen in Text nicht konsistent waren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1464">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1465">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1465">Outlook</span></span>
- <span data-ttu-id="a0b79-1466">Ein Problem wurde behoben, bei dem das Speichern eines Kontakts aus einer VCF-Datei zu leeren Feldern führen konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1466">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="a0b79-1467">Ein Problem wurde behoben, bei dem eine Nachricht im Ordner "Postausgang" stecken blieb, obwohl sie gesendet wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1467">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="a0b79-1468">Ein Problem wurde behoben, bei dem Outlook beim Anzeigen einer DRM-Meldung abstürzte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1468">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1469">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1469">Access</span></span>
- <span data-ttu-id="a0b79-1470">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1470">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1471">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1471">Project</span></span>
- <span data-ttu-id="a0b79-1472">Ein Problem wurde behoben, bei dem der Editor von Chinesisch auf Englisch wechselte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1472">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="a0b79-1473">Ein Problem wurde behoben, bei dem unveröffentlichte Aufgaben manchmal in der veröffentlichten Kopie eines Hauptprojekts angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1473">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="a0b79-1474">26. April 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1474">April 26, 2019</span></span>
<span data-ttu-id="a0b79-1475">Version 1905 (Build 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1475">Version 1905 (build 11617.20002)</span></span>

## <a name="new-features"></a><span data-ttu-id="a0b79-1476">Neue Features</span><span class="sxs-lookup"><span data-stu-id="a0b79-1476">New Features</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1477">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1477">Outlook</span></span>

<span data-ttu-id="a0b79-1478">**Aktualisierungen freigebender Kalender funktionieren jetzt noch schneller:** Outlook ist in der Lage, freigegebene Kalender in Office 365 mithilfe der REST API zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1478">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="a0b79-1479">Aktivieren Sie die Vorschau, um schnellere und zuverlässigere Aktualisierungen für freigegebene Kalender zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1479">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1480">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1480">Excel</span></span>

#### <a name="coauthoring-improvements"></a><span data-ttu-id="a0b79-1481">Verbesserungen bei der gemeinsamen Dokumenterstellung</span><span class="sxs-lookup"><span data-stu-id="a0b79-1481">Coauthoring improvements</span></span>

<span data-ttu-id="a0b79-1482">Die gemeinsame Dokumenterstellung wurde verbessert, indem Inhaltsänderungen den anderen Benutzern nun nahezu immer in Echtzeit angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1482">Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="visio"></a><span data-ttu-id="a0b79-1483">Visio</span><span class="sxs-lookup"><span data-stu-id="a0b79-1483">Visio</span></span>

- <span data-ttu-id="a0b79-1484">**Exportieren von Visio-Visualisierungen aus Power BI:** Die Visio-Visualisierung für Power BI wird nun ordnungsgemäß angezeigt, wenn Sie Power BI-Berichte beispielsweise als PDF-Dateien, PowerPoint-Dateien und mehr exportieren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1484">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1485">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1485">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1486">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1486">Word</span></span> 
- <span data-ttu-id="a0b79-1487">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1487">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1488">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1488">Excel</span></span>
- <span data-ttu-id="a0b79-1489">Wir haben ein Problem behoben, bei dem Solver-Makros nicht ausgeführt werden konnten</span><span class="sxs-lookup"><span data-stu-id="a0b79-1489">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="a0b79-1490">Wir haben ein Problem behoben, das den Import von Excel-Dateien in SharePoint verhindern konnte</span><span class="sxs-lookup"><span data-stu-id="a0b79-1490">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1491">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1491">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1492">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1492">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1493">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1493">Outlook</span></span>
- <span data-ttu-id="a0b79-1494">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1494">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1495">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1495">Access</span></span>
- <span data-ttu-id="a0b79-1496">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1496">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1497">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1497">Project</span></span>
- <span data-ttu-id="a0b79-1498">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1498">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="a0b79-1499">19. April 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1499">April 19, 2019</span></span>
<span data-ttu-id="a0b79-1500">Version 1905 (Build 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1500">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1501">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1501">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1502">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1502">Outlook</span></span>

<span data-ttu-id="a0b79-1503">**Erhalten Sie E-Mail-Vorschläge, wenn Sie nach einer Person suchen:** Wenn Sie den Namen einer Person im Suchfeld eingeben, werden die relevantesten E-Mail-Nachrichten in die Ihnen gezeigten Suchvorschläge einbezogen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1503">**Get email suggestions when you search for a person:** When you type a person's name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1504">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1504">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="a0b79-1505">Verbesserte Benutzererfahrung für ausgefüllte Karten durch die Verwendung von Datentypen</span><span class="sxs-lookup"><span data-stu-id="a0b79-1505">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="a0b79-1506">Dieses Feature ist eine Verbesserung für Benutzer, die ausgefüllte Kartendiagramme mithilfe der geografischen Datentypen von Excel darstellen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1506">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="a0b79-1507">Der Vorteil für den Endbenutzer besteht in einer umfangreicheren Integration zwischen den Features und einer höheren Genauigkeit des Bereichs, den der Endbenutzer zuordnen möchte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1507">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="a0b79-1508">Weitere Vorteile: Zuordnen von Stadt-Polygonen</span><span class="sxs-lookup"><span data-stu-id="a0b79-1508">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="a0b79-1509">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1509">Getting Started:</span></span>

- <span data-ttu-id="a0b79-1510">Dieses Feature ist eine Verbesserung der vorhandenen Funktionen in Excel.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1510">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="a0b79-1511">Verwenden der Verbesserung: Konvertieren Sie Orte in Rich-Entitäten und stellen Sie sie durch ausgefüllte Karten dar.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1511">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1512">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1512">Scenarios to Try:</span></span>

- <span data-ttu-id="a0b79-1513">Benutzer können Städte, Staaten, Landkreise, Länder und Postleitzahlen zuordnen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1513">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1514">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1514">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="a0b79-1515">Alle Anwendungen</span><span class="sxs-lookup"><span data-stu-id="a0b79-1515">All Applications</span></span>
- <span data-ttu-id="a0b79-1516">Es wurde ein Fehler behoben, bei dem der Dialog der ersten Ausführung beim Start einer Anwendung immer angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1516">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="a0b79-1517">Es wurde ein Problem behoben, bei dem ein SharePoint-Link im Dialogfeld "Speichern unter" in manchen Fällen nicht vorhanden war.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1517">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="a0b79-1518">Es wurde ein Fehler behoben, bei dem Benutzern fälschlicherweise der Dialog "Jetzt reparieren" angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1518">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1519">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1519">Word</span></span> 
- <span data-ttu-id="a0b79-1520">Es wurde ein Fehler behoben, bei dem einige Benutzer beim Anfordern einer Schriftart die Fehlermeldung erhielten, dass nicht genügend Arbeitsspeicher oder Speicherplatz vorhanden sei.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1520">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="a0b79-1521">Es wurde ein Fehler behoben, bei dem ein Fenster beim Umschalten vom Bereich "Kommentare" unscharf wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1521">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1522">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1522">Excel</span></span>
- <span data-ttu-id="a0b79-1523">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1523">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1524">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1524">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1525">Es wurde ein Fehler behoben, der bewirkte, dass die Größe von Formen mit Branding nicht angepasst werden konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1525">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="a0b79-1526">Es wurde ein Fehler behoben, bei dem PowerPoint abstürzen konnte, wenn eine Datei im geschützten Ansichtsmodus geöffnet wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1526">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1527">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1527">Outlook</span></span>
- <span data-ttu-id="a0b79-1528">Wir haben ein Problem behoben, aufgrund dessen einige Benutzer keine chinesischen Wörter auswählen konnten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1528">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="a0b79-1529">Wir haben ein Problem behoben, bei dem Ablaufdaten nicht korrekt berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1529">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1530">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1530">Access</span></span>
- <span data-ttu-id="a0b79-1531">Wir haben ein Problem behoben, aufgrund dessen einige Benutzer nicht den Makro-Generator benutzen konnten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1531">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="a0b79-1532">Wir haben ein Problem behoben, aufgrund dessen beim Drucken eines Berichts nur die erste Seite ausgedruckt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1532">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="a0b79-1533">Es wurde ein Problem behoben, bei dem die Anwendung beim Fahren über einen Hyperlink abstürzen konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1533">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="a0b79-1534">Wir haben ein Problem behoben, das bewirkte, dass in der Ansicht "Beziehungen" einige Elemente außerhalb des Fensters angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1534">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1535">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1535">Project</span></span>
- <span data-ttu-id="a0b79-1536">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1536">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="a0b79-1537">12. April 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1537">April 12, 2019</span></span>
<span data-ttu-id="a0b79-1538">Version 1905 (Build 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1538">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1539">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1539">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1540">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1540">Access</span></span>

#### <a name="get-smart-with-microsoft-graph"></a><span data-ttu-id="a0b79-1541">Intelligenter mit Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="a0b79-1541">Get smart with Microsoft Graph</span></span>

<span data-ttu-id="a0b79-1542">Importieren oder verlinken Sie intelligente Daten, und erfinden Sie Ihre Desktopdatenbank mit intelligenter Technologie neu.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1542">Import or link to intelligent data and reinvent your desktop database with Intelligent Technology.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1543">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1543">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="a0b79-1544">Alle Anwendungen</span><span class="sxs-lookup"><span data-stu-id="a0b79-1544">All Applications</span></span>
 - <span data-ttu-id="a0b79-1545">Wir haben ein Problem behoben, aufgrund dessen einige Benutzer Dateien nicht an Cloudspeicherorten speichern konnten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1545">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="a0b79-1546">Wir haben ein Problem behoben, bei dem der falsche Bereich auf dem Menüband geöffnet wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1546">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1547">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1547">Word</span></span> 
- <span data-ttu-id="a0b79-1548">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1548">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1549">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1549">Excel</span></span>
- <span data-ttu-id="a0b79-1550">Wir haben ein Problem behoben, bei dem eine Fehlermeldung aufgrund verknüpfter Datentypen für Benutzer angezeigt wird, wenn die Arbeitsmappe keine verknüpften Datentypen enthält.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1550">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="a0b79-1551">Wir haben ein Problem behoben, bei dem sich URL-Links innerhalb eines Word-Dokuments ändern, wenn diese lokal und nicht online angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1551">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1552">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1552">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1553">Wir haben ein Problem behoben, bei dem die Anwendung nach dem Rückgängigmachen von Änderungen auf der Registerkarte „Animationen“ abstürzte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1553">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1554">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1554">Outlook</span></span>
- <span data-ttu-id="a0b79-1555">Wir haben ein Problem behoben, aufgrund dessen einige Benutzer das Feld „Notizen“ für Kontakt in einem öffentlichen Ordner nicht bearbeiten konnten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1555">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="a0b79-1556">Wir haben ein Problem behoben, bei dem ein Konflikt zwischen den Ablaufdatumsangaben und den Löschdatumsangaben auftrat.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1556">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1557">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1557">Access</span></span>
- <span data-ttu-id="a0b79-1558">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1558">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1559">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1559">Project</span></span>
- <span data-ttu-id="a0b79-1560">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1560">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="a0b79-1561">5. April 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1561">April 5, 2019</span></span>
<span data-ttu-id="a0b79-1562">Version 1904 (Build 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1562">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1563">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1563">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1564">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1564">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="a0b79-1565">Outlook für Windows: Festlegen und Teilen Ihrer Einstellungen für „Posteingang mit Relevanz"</span><span class="sxs-lookup"><span data-stu-id="a0b79-1565">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="a0b79-1566">Ihre Einstellungen für "Posteingang mit Relevanz" werden in der Cloud gespeichert, sodass Sie auf jedem verwendeten Computer die gleiche konsistente Umgebung für Outlook für Windows und Outlook im Web erhalten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1566">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a0b79-1567">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1567">Getting Started:</span></span>

<span data-ttu-id="a0b79-1568">Unter „Datei" > „Optionen" > Registerkarte „Allgemein" gibt es eine neue Einstellung für „Meine Outlook-Einstellungen in der Cloud speichern".</span><span class="sxs-lookup"><span data-stu-id="a0b79-1568">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="a0b79-1569">Benutzer müssen das Kontrollkästchen aktivieren, damit ihre Einstellungen für "Posteingang mit Relevanz" für andere Desktopinstallationen von Outlook und OWA übernommen werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1569">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1570">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1570">Scenarios to Try:</span></span>

<span data-ttu-id="a0b79-1571">Ändern Sie auf dem Computer, auf dem die Einstellung für die Cloudeinstellungen aktiviert ist, den Posteingang mit Priorität.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1571">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="a0b79-1572">Navigieren Sie zu OWA, und sehen Sie sich die dort angewendete Einstellung an.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1572">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="a0b79-1573">Ändern Sie den „Posteingangs mit Relevanz“ in OWA und starten Sie Outlook für Desktop, um die Einstellungen anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1573">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1574">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1574">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="a0b79-1575">Der Modus „Lerntools" unterstützt weitere Seitenfarben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1575">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="a0b79-1576">Lerntools in Word unterstützt weitere Farben für Seitendesigns, wodurch die Hintergrundfarbe der Seite geändert werden kann.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1576">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="a0b79-1577">Für viele Personen ist es schwierig bei einem vollen weißen oder schwarzen Hintergrund zu lesen, deshalb haben wir die Auswahl von Farben in Word auf PC und Mac erweitert.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1577">Many people have challenges reading with an all-white or all-black background, so we've expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a0b79-1578">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1578">Getting Started:</span></span>

<span data-ttu-id="a0b79-1579">Um dies auszuprobieren, wechseln Sie zur Registerkarte „Anzeige", und wählen Sie „Lerntools", dann „Seitenfarbe" aus.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1579">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1580">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1580">Scenarios to Try:</span></span>

<span data-ttu-id="a0b79-1581">Um dies auszuprobieren, wechseln Sie zur Registerkarte „Anzeige", und wählen Sie „Lerntools", dann „Seitenfarbe" aus.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1581">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1582">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1582">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="a0b79-1583">Kreativität durch animierte 3D-Modelle steigern</span><span class="sxs-lookup"><span data-stu-id="a0b79-1583">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="a0b79-1584">Office unterstützt jetzt animierte Modelle, die im Editor wiedergegeben werden, damit Sie Ihre Arbeitsblätter zum Leben erwecken können!</span><span class="sxs-lookup"><span data-stu-id="a0b79-1584">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a0b79-1585">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1585">Getting Started:</span></span>

1. <span data-ttu-id="a0b79-1586">Öffnen Sie Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1586">Open Excel</span></span>
2. <span data-ttu-id="a0b79-1587">Fügen Sie ein animiertes 3D-Modell ein (demnächst in Remix verfügbar, bereits jetzt können Sie hier auf animierte Modelle zugreifen: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1587">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="a0b79-1588">Das animierte Modell wird im Editor wiedergegeben!</span><span class="sxs-lookup"><span data-stu-id="a0b79-1588">The animated model will play in the editor!</span></span> <span data-ttu-id="a0b79-1589">Wechseln Sie in den Bildschirmpräsentationsmodus – es wird auch dort wiedergegeben werden!</span><span class="sxs-lookup"><span data-stu-id="a0b79-1589">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="a0b79-1590">Im Menüband 3D-Format finden Sie noch weitere animierte Szenen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1590">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1591">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1591">Scenarios to Try:</span></span>

1. <span data-ttu-id="a0b79-1592">Fügen Sie ein 3D-Modell ein und betrachten Sie dessen Animation im Editor.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1592">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="a0b79-1593">Entdecken Sie die im animierten Modell verfügbaren Animationsszenen in der Szenengalerie, zu finden im Menüband 3D-Format</span><span class="sxs-lookup"><span data-stu-id="a0b79-1593">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="a0b79-1594">Die Animation kann ganz einfach über das Menüband, den Floatie oder die Leertaste wiedergegeben oder pausiert werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1594">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1595">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1595">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="a0b79-1596">Alle Anwendungen</span><span class="sxs-lookup"><span data-stu-id="a0b79-1596">All Applications</span></span>
- <span data-ttu-id="a0b79-1597">Wir haben ein Problem behoben, bei dem das Symbol für eine falsche App für Excel in Kontextmenüs nicht ordnungsgemäß angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1597">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="a0b79-1598">Wir haben ein Problem behoben, bei dem die Menüschaltfläche „Datei“ nach der Installation eines Updates nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1598">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="a0b79-1599">Wir haben ein Problem behoben, bei dem Ihre Benutzerlizenz geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1599">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1600">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1600">Word</span></span> 
- <span data-ttu-id="a0b79-1601">Wir haben ein Problem behoben, bei dem Text auf bestimmten Zoomebenen nicht richtig gerendert wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1601">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1602">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1602">Excel</span></span>
- <span data-ttu-id="a0b79-1603">Wir haben ein Problem behoben, bei dem Benutzer nicht aufgefordert wurden, eine Arbeitsmappe nach Änderungen zu speichern.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1603">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="a0b79-1604">Wir haben ein Problem behoben, bei dem ein BeforeSave-Ereignis nicht ausgelöst wurde, wenn der Benutzer die Arbeitsmappe teilte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1604">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="a0b79-1605">Wir haben ein Problem behoben, bei dem das Ändern der Größe einer Spalte auf weniger als 6 Pixel eine falsche Fehlermeldung ausgab.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1605">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="a0b79-1606">Wir haben ein Problem behoben, bei dem Excel das Application.Visible-Kennzeichen ignorierte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1606">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="a0b79-1607">Wir haben ein Problem behoben, bei dem Ablaufverfolgungspfeile auf nicht aktiven fixierten Fenstern bestehen blieben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1607">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="a0b79-1608">Wir haben ein Problem behoben, bei dem sich die Zellenformatierung von Datumsangaben und Währung beim Öffnen einer Arbeitsmappe änderte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1608">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="a0b79-1609">Wir haben ein Problem behoben, bei dem Tooltips sich unerwartet verschoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1609">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="a0b79-1610">Wir haben Lokalisierungsprobleme für den Power Query-Editor behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1610">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="a0b79-1611">Wir haben ein Problem behoben, bei dem eine Arbeitsmappe als Anlage beim Senden per E-Mail entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1611">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1612">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1612">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1613">Wir haben ein Problem behoben, bei dem das Kopieren von Shapes länger als erwartet dauerte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1613">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1614">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1614">Outlook</span></span>
- <span data-ttu-id="a0b79-1615">Wir haben ein Problem behoben, bei dem Outlook bei der Verwendung des Zeichnungstools abstürzte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1615">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="a0b79-1616">Wir haben ein Lokalisierungsproblem beim Verfassen von HTML-E-Mails behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1616">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="a0b79-1617">Wir haben ein Problem behoben, bei dem Benutzer Schwierigkeiten bei der Auswahl des unteren Fensterbereichs hatten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1617">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1618">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1618">Access</span></span>
- <span data-ttu-id="a0b79-1619">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1619">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1620">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1620">Project</span></span>
- <span data-ttu-id="a0b79-1621">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1621">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="a0b79-1622">22. März 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1622">March 22, 2019</span></span>
<span data-ttu-id="a0b79-1623">Version 1904 (Build 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1623">Version 1904 (build 11514.20004)</span></span>

## <a name="new-features"></a><span data-ttu-id="a0b79-1624">Neue Features</span><span class="sxs-lookup"><span data-stu-id="a0b79-1624">New Features</span></span>

- <span data-ttu-id="a0b79-1625">**Kontrollmechanismen für den Datenschutz:** Neue aktualisierte und verbesserte Kontrollmechanismen für Diagnosedaten und verbundene Oberflächen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1625">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> <span data-ttu-id="a0b79-1626">Weitere Informationen <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span><span class="sxs-lookup"><span data-stu-id="a0b79-1626">Learn more <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span></span>

- <span data-ttu-id="a0b79-1627">**Office-Symbole mit neuem Look:** Die Office-Symbole wurden neu gestaltet, um die einfache, leistungsstarke und intelligente Office-Benutzeroberfläche widerzuspiegeln.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1627">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1628">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1628">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1629">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1629">Word</span></span> 
- <span data-ttu-id="a0b79-1630">Ein Problem wurde behoben, bei dem die Benutzeroberfläche ständig "Überprüfung auf Änderungen" anzeigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1630">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1631">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1631">Excel</span></span>
- <span data-ttu-id="a0b79-1632">Ein Problem wurde behoben, bei dem die Anwendung nach dem Verschieben eines Arbeitsblattes abstürzte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1632">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="a0b79-1633">Ein Problem wurde behoben, bei dem die Anwendung nach dem Speichern im PDF-Format abstürzte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1633">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="a0b79-1634">Ein Problem wurde behoben, bei dem das Dialogfeld "Speichern" einige koreanische Zeichen nicht akzeptierte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1634">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1635">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1635">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1636">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1636">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1637">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1637">Outlook</span></span>
- <span data-ttu-id="a0b79-1638">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1638">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1639">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1639">Access</span></span>
- <span data-ttu-id="a0b79-1640">Die Fehlermeldung in Access wurde korrigiert, bei der eine zusätzliche Verknüpfung zu Access erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1640">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="a0b79-1641">Ein Problem wurde behoben, bei dem Daten aus einem verlinkten SharePoint falsch angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1641">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1642">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1642">Project</span></span>
- <span data-ttu-id="a0b79-1643">Ein Problem wurde behoben, bei dem die Spracheinstellungen von Chinesisch auf Englisch wechselten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1643">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="a0b79-1644">Ein Problem wurde behoben, bei dem die Anwendung beim Synchronisieren mit SharePoint abstürzen konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1644">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="a0b79-1645">15. März 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1645">March 15, 2019</span></span>
<span data-ttu-id="a0b79-1646">Version 1904 (Build 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1646">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1647">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1647">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1648">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1648">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="a0b79-1649">Fokusmodus</span><span class="sxs-lookup"><span data-stu-id="a0b79-1649">Focus Mode</span></span>

<span data-ttu-id="a0b79-1650">Wechseln Sie im Menü Ansicht in den Fokusmodus, damit Sie nicht abgelenkt werden und sich auf Ihre Arbeit konzentrieren können.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1650">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="a0b79-1651">Nur für Abonnenten von Office 365.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1651">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a0b79-1652">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1652">Getting Started:</span></span>

<span data-ttu-id="a0b79-1653">Zugriff durch Schaltfläche „Fokus" auf der Registerkarte „Anzeige".</span><span class="sxs-lookup"><span data-stu-id="a0b79-1653">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1654">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1654">Scenarios to Try:</span></span>

<span data-ttu-id="a0b79-1655">Schalten Sie den Fokusmodus ein und erleben Sie die fokussierte Benutzererfahrung</span><span class="sxs-lookup"><span data-stu-id="a0b79-1655">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1656">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1656">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1657">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1657">Word</span></span> 
- <span data-ttu-id="a0b79-1658">Ein Problem wurde behoben, bei dem Bilder in einem als PDF-Datei gespeicherten Dokument den falschen DPI-Wert aufweisen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1658">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1659">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1659">Excel</span></span>
- <span data-ttu-id="a0b79-1660">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1660">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1661">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1661">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1662">Ein Problem wurde behoben, bei dem der Bereich "Kommentare" sich nicht ordnungsgemäß öffnet oder schließt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1662">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="a0b79-1663">Ein Problem wurde behoben, bei dem die Anwendung beim Löschen eines Videos abstürzte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1663">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="a0b79-1664">Ein Problem wurde behoben, bei dem die Anwendung in einigen Fällen nicht gestartet werden konnte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1664">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1665">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1665">Outlook</span></span>
- <span data-ttu-id="a0b79-1666">Ein Problem wurde behoben, bei dem im Japanischen falsche Lesebestätigungen angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1666">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1667">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1667">Access</span></span>
- <span data-ttu-id="a0b79-1668">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1668">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1669">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1669">Project</span></span>
- <span data-ttu-id="a0b79-1670">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1670">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="a0b79-1671">8. März 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1671">March 8, 2019</span></span> 
<span data-ttu-id="a0b79-1672">Version 1903 (Build 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1672">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1673">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1673">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1674">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1674">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="a0b79-1675">Finden gesuchter Elemente mit Microsoft Search</span><span class="sxs-lookup"><span data-stu-id="a0b79-1675">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="a0b79-1676">Mit Microsoft Search können Sie alle Dateien, Aktionen, Personen und Hilfethemen finden, die Sie benötigen, um Ihre Arbeit zu erledigen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1676">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a0b79-1677">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1677">Getting Started:</span></span>

- <span data-ttu-id="a0b79-1678">Das Feature wird leicht erkennbar in der Kopfzeile über der Benutzeroberfläche angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1678">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1679">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1679">Scenarios to Try:</span></span>

- <span data-ttu-id="a0b79-1680">Suchen nach einer Hochschule, einem aktuellen Dokument oder den Menübandbefehlen, die Sie am häufigsten verwenden</span><span class="sxs-lookup"><span data-stu-id="a0b79-1680">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="a0b79-1681">Nachschlagen eines Themas, um mehr Informationen darüber zu erhalten</span><span class="sxs-lookup"><span data-stu-id="a0b79-1681">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="a0b79-1682">CoAuthoring</span><span class="sxs-lookup"><span data-stu-id="a0b79-1682">CoAuthoring</span></span>

<span data-ttu-id="a0b79-1683">Sind Sie es leid, von Ihren Dokumenten mit Makros ausgesperrt zu werden?</span><span class="sxs-lookup"><span data-stu-id="a0b79-1683">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="a0b79-1684">Jetzt ist die gleichzeitige Bearbeitung durch mehrere Autoren für Ihre docm-Dateien in OneDrive for Business möglich.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1684">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a0b79-1685">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1685">Getting Started:</span></span>

<span data-ttu-id="a0b79-1686">Der Benutzer muss keine Schaltflächen auf der Benutzeroberfläche drücken, um auf diese Funktion zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1686">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="a0b79-1687">Sie ist in OneDrive for Business docm-Dateien standardmäßig aktiviert.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1687">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="a0b79-1688">Deshalb sollte der Benutzer eine docm-Datei in OneDrive for Business speichern, um dies auszuprobieren.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1688">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1689">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1689">Scenarios to Try:</span></span>

<span data-ttu-id="a0b79-1690">Erstellen Sie eine docm-Datei auf OneDrive for Business, teilen Sie sie mit Ihren Kollegen, und arbeiten Sie gemeinsam daran!</span><span class="sxs-lookup"><span data-stu-id="a0b79-1690">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1691">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1691">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1692">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1692">Word</span></span> 
- <span data-ttu-id="a0b79-1693">Wir haben ein Absturzproblem behoben, der beim Drücken von ESC in "Optionen" auftrat</span><span class="sxs-lookup"><span data-stu-id="a0b79-1693">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="a0b79-1694">Die Ursache für einen Absturz wurde behoben, der beim Antworten auf Kommentare auftrat.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1694">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="a0b79-1695">Ein Problem mit dem Kopieren und Einfügen von Word nach PowerPoint Online wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1695">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1696">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1696">Excel</span></span>
- <span data-ttu-id="a0b79-1697">Ein Problem wurde behoben, bei dem das Kopieren einer Zelle in Excel zu einer hohen CPU-Auslastung führte, wenn geschützte Dokumente und editierbare Dokumente geöffnet wurden</span><span class="sxs-lookup"><span data-stu-id="a0b79-1697">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1698">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1698">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1699">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1699">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1700">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1700">Outlook</span></span>
- <span data-ttu-id="a0b79-1701">Ein Problem wurde behoben, bei dem die Outlook-Suche die ausgewählte chronologische Sortierung nicht einhielt</span><span class="sxs-lookup"><span data-stu-id="a0b79-1701">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="a0b79-1702">Ein Problem wurde behoben, bei dem die Schaltfläche "Diese Aufgabe öffnen" im Menüband "Workflow" auf bestimmte E-Mails nicht reagierte</span><span class="sxs-lookup"><span data-stu-id="a0b79-1702">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="a0b79-1703">Ein Problem wurde behoben, bei dem Outlook lokale Räume nicht löschte, nachdem Benutzer einen verfügbaren Raum in der Raumsuche ausgewählt hatten</span><span class="sxs-lookup"><span data-stu-id="a0b79-1703">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1704">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1704">Access</span></span>
- <span data-ttu-id="a0b79-1705">Das Dialogfeld "Gespeicherter Import/Export", das im dunklen Design weißen Text auf weißem Hintergrund enthielt, wurde korrigiert</span><span class="sxs-lookup"><span data-stu-id="a0b79-1705">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="a0b79-1706">Ein Problem wurde behoben, bei dem Benutzer die Eigenschaft "DisplayControl" für ein Ja/Nein-Feld im Tabellenentwurf nicht auf Textfeld festlegen konnten</span><span class="sxs-lookup"><span data-stu-id="a0b79-1706">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1707">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1707">Project</span></span>
- <span data-ttu-id="a0b79-1708">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1708">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="a0b79-1709">1. März 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1709">March 1, 2019</span></span> 
<span data-ttu-id="a0b79-1710">Version 1903 (Build 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1710">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1711">Neuerungen</span><span class="sxs-lookup"><span data-stu-id="a0b79-1711">What's New</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1712">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1712">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="a0b79-1713">Farben für „Änderungen nachverfolgen", Kommentare und Echtzeitzusammenarbeit jetzt synchronisiert:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1713">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="a0b79-1714">Korrekturen in unserem Produkt stellen nun sicher, dass Kommentare, Änderungsnachverfolgung und der Cursor für einen Projektmitarbeiter in der gleichen Farbe angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1714">Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a0b79-1715">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1715">Getting Started:</span></span>

<span data-ttu-id="a0b79-1716">Öffnen Sie ein SharePoint- oder OneDrive-Dokument, das andere Personen geöffnet haben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1716">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="a0b79-1717">Vergewissern Sie sich, dass das Nachverfolgen von Änderungen und die Farbe der Kommentare für einen Benutzer mit der Farbe des Cursors eines Benutzers übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1717">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1718">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1718">Scenarios to Try:</span></span>

<span data-ttu-id="a0b79-1719">Öffnen Sie ein SharePoint- oder OneDrive-Dokument, das andere Personen geöffnet haben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1719">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="a0b79-1720">Vergewissern Sie sich, dass das Nachverfolgen von Änderungen und die Farbe der Kommentare für einen Benutzer mit der Farbe des Cursors eines Benutzers übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1720">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1721">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1721">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1722">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1722">Word</span></span> 
- <span data-ttu-id="a0b79-1723">Wir haben ein Absturzproblem behoben, der beim Drücken von ESC in "Optionen" auftrat</span><span class="sxs-lookup"><span data-stu-id="a0b79-1723">We fixed a crashing issue that occurred when pressing 'ESC' while in Options</span></span>
- <span data-ttu-id="a0b79-1724">Ein Problem mit dem Kopieren und Einfügen von Word nach PowerPoint Online wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1724">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1725">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1725">Excel</span></span>
- <span data-ttu-id="a0b79-1726">Ein Problem wurde behoben, bei dem das Kopieren einer Zelle in Excel zu einer hohen CPU-Auslastung führte, wenn geschützte Dokumente und editierbare Dokumente geöffnet wurden</span><span class="sxs-lookup"><span data-stu-id="a0b79-1726">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1727">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1727">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1728">Ein Problem mit der Folienbildgröße bei Verwendung von @Erwähnungen in PowerPoint wurde behoben</span><span class="sxs-lookup"><span data-stu-id="a0b79-1728">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1729">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1729">Outlook</span></span>
- <span data-ttu-id="a0b79-1730">Ein Problem wurde behoben, bei dem die Outlook-Suche die ausgewählte chronologische Sortierung nicht einhielt</span><span class="sxs-lookup"><span data-stu-id="a0b79-1730">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="a0b79-1731">Ein Problem wurde behoben, bei dem die Schaltfläche "Diese Aufgabe öffnen" im Menüband "Workflow" auf bestimmte E-Mails nicht reagierte</span><span class="sxs-lookup"><span data-stu-id="a0b79-1731">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="a0b79-1732">Ein Problem wurde behoben, bei dem Outlook lokale Räume nicht löschte, nachdem Benutzer einen verfügbaren Raum in der Raumsuche ausgewählt hatten</span><span class="sxs-lookup"><span data-stu-id="a0b79-1732">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1733">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1733">Access</span></span>
- <span data-ttu-id="a0b79-1734">Der Eingabeaufforderungstext wurde aktualisiert, der beim Bestätigen der erneuten Verknüpfung von Tabellen mit einer Datenquelle angezeigt wurde</span><span class="sxs-lookup"><span data-stu-id="a0b79-1734">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="a0b79-1735">Das Dialogfeld "Gespeicherter Import/Export", das im dunklen Design weißen Text auf weißem Hintergrund enthielt, wurde korrigiert</span><span class="sxs-lookup"><span data-stu-id="a0b79-1735">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="a0b79-1736">Ein Problem wurde behoben, bei dem Benutzer die Eigenschaft "Steuerelement anzeigen" für ein Ja/Nein-Feld im Tabellenentwurf nicht auf Textfeld festlegen konnten</span><span class="sxs-lookup"><span data-stu-id="a0b79-1736">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1737">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1737">Project</span></span>
- <span data-ttu-id="a0b79-1738">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1738">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="a0b79-1739">15. Februar 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1739">February 15, 2019</span></span> 
<span data-ttu-id="a0b79-1740">Version 1903 (Build 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1740">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="a0b79-1741">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1741">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1742">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1742">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="a0b79-1743">Verbesserungen beim Übergang "Morphen" – Morphen nach Name</span><span class="sxs-lookup"><span data-stu-id="a0b79-1743">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="a0b79-1744">Geben Sie die Formen an, die Sie morphen möchten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1744">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a0b79-1745">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1745">Getting Started:</span></span>

- <span data-ttu-id="a0b79-1746">Damit beim Morphen zwei Objekte als das gleiche Objekt behandelt werden, kann der Benutzer die Formen über das Auswahlfenster umbenennen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1746">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="a0b79-1747">Dem Namen muss "!!" vorangestellt werden.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1747">The name must be prefaced with "!!"</span></span> <span data-ttu-id="a0b79-1748">(zwei Ausrufezeichen) für Morph, um es zum Außerkraftsetzen des standardmäßigen Übereinstimmungsverhaltens zu verwenden, z. B. "!!Name"</span><span class="sxs-lookup"><span data-stu-id="a0b79-1748">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. "!!Name"</span></span>
- <span data-ttu-id="a0b79-1749">Benutzer können Formen weiterhin in beliebige Namen umbenennen, die nicht mit "!!" beginnen</span><span class="sxs-lookup"><span data-stu-id="a0b79-1749">Users can continue to rename shapes with any name that doesn't start with "!!"</span></span> <span data-ttu-id="a0b79-1750">ohne dass dadurch die Funktionsweise von Morph geändert wird.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1750">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1751">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1751">Scenarios to Try:</span></span>

- <span data-ttu-id="a0b79-1752">Fügen Sie eine Form auf einer Folie ein, z.B. ein Rechteck.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1752">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="a0b79-1753">Erstellen Sie eine neue Folie.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1753">Create a new slide</span></span>
- <span data-ttu-id="a0b79-1754">Fügen Sie eine andere Form auf der zweiten Folie ein, z.B. ein Dreieck.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1754">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="a0b79-1755">Öffnen Sie das Auswahlfenster, benennen Sie das Rechteck in Folie 1 in "!!Form" und das Dreieck in Folie 2 in "!!Form" um.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1755">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="a0b79-1756">Wenden Sie Morphen auf die zweite Folie an.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1756">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="a0b79-1757">Verbesserungen beim Übergang "Morphen" – SmartArt</span><span class="sxs-lookup"><span data-stu-id="a0b79-1757">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="a0b79-1758">SmartArt-Morphen mit weicheren Übergängen</span><span class="sxs-lookup"><span data-stu-id="a0b79-1758">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a0b79-1759">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1759">Getting Started:</span></span>

<span data-ttu-id="a0b79-1760">Verwenden Sie Morphen wie bei SmartArt.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1760">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1761">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1761">Scenarios to Try:</span></span>

- <span data-ttu-id="a0b79-1762">Fügen Sie eine SmartArt auf einer Folie ein.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1762">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="a0b79-1763">Duplizieren Sie die Folie.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1763">Duplicate the Slide</span></span>
- <span data-ttu-id="a0b79-1764">Ändern oder verschieben Sie die SmartArt auf der duplizierten Folie, oder ändern Sie deren Größe.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1764">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="a0b79-1765">Wenden Sie Morph auf die duplizierte Folie an.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1765">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="a0b79-1766">Verbesserungen beim Übergang "Morphen" – Tabellen</span><span class="sxs-lookup"><span data-stu-id="a0b79-1766">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="a0b79-1767">Tabellen-Morphen mit weicheren Übergängen</span><span class="sxs-lookup"><span data-stu-id="a0b79-1767">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="a0b79-1768">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1768">Getting Started:</span></span>
<span data-ttu-id="a0b79-1769">Verwenden Sie Morphen wie bei Tabellen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1769">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1770">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1770">Scenarios to Try:</span></span>

- <span data-ttu-id="a0b79-1771">Fügen Sie eine Tabelle auf einer Folie ein.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1771">Insert a Table in a slide</span></span>
- <span data-ttu-id="a0b79-1772">Duplizieren Sie die Folie.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1772">Duplicate the slide</span></span>
- <span data-ttu-id="a0b79-1773">Ändern oder verschieben Sie die Tabelle auf der duplizierten Folie, oder ändern Sie deren Größe.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1773">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="a0b79-1774">Wenden Sie Morph auf die duplizierte Folie an.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1774">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="a0b79-1775">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher und Visio</span><span class="sxs-lookup"><span data-stu-id="a0b79-1775">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="a0b79-1776">Nahtloses Wechseln zwischen Konten</span><span class="sxs-lookup"><span data-stu-id="a0b79-1776">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="a0b79-1777">Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Konten an einem Ort an, und erleichtert Ihnen das Wechseln zwischen diesen Konten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1777">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="a0b79-1778">Diese aktualisierte Oberfläche verdeutlicht, wie Sie gerade angemeldet sind. Jetzt können Sie zwischen geschäftlichen und privaten Konten wechseln, ohne sich vorher abmelden zu müssen oder sich mit komplexen Dialogfeldern zu beschäftigen.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1778">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="a0b79-1780">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1780">Scenarios to Try:</span></span>
- <span data-ttu-id="a0b79-1781">Wechseln zwischen Konten</span><span class="sxs-lookup"><span data-stu-id="a0b79-1781">Switch between accounts</span></span>
- <span data-ttu-id="a0b79-1782">Hinzufügen eines neuen Kontos [Hinweis: Sie sollten möglicherweise zuerst zu "Datei" | "Konto" | "Verbundene Dienste" navigieren und alle persönlichen Dienste entfernen, die mit Geschäftskonten verbunden sind oder umgekehrt].</span><span class="sxs-lookup"><span data-stu-id="a0b79-1782">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="a0b79-1783">Abmelden von einem Konto</span><span class="sxs-lookup"><span data-stu-id="a0b79-1783">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1784">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1784">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1785">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1785">Word</span></span> 
- <span data-ttu-id="a0b79-1786">Ein Problem mit der Kontextvorschau für Tabellen und Bilder wurde behoben</span><span class="sxs-lookup"><span data-stu-id="a0b79-1786">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1787">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1787">Excel</span></span>
- <span data-ttu-id="a0b79-1788">Ein Problem wurde behoben, bei dem Text im "AutoFilter"-Suchfeld im Design "Schwarz" weiß angezeigt wird</span><span class="sxs-lookup"><span data-stu-id="a0b79-1788">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="a0b79-1789">Ein Problem mit der Zustimmungsbenutzeroberfläche beim neuen Office-Add-In wurde behoben</span><span class="sxs-lookup"><span data-stu-id="a0b79-1789">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1790">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1790">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1791">Ein Problem mit der sich automatisch erweiternden Anzeige beim Präsentieren von Bildschirmpräsentationen auf Laptops oder Tablets wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1791">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1792">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1792">Outlook</span></span>
- <span data-ttu-id="a0b79-1793">Ein Problem mit dem Anzeigen der Schaltfläche "An OneNote senden" wurde behoben</span><span class="sxs-lookup"><span data-stu-id="a0b79-1793">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1794">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1794">Access</span></span>
- <span data-ttu-id="a0b79-1795">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1795">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1796">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1796">Project</span></span>
- <span data-ttu-id="a0b79-1797">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1797">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="a0b79-1798">11. Februar 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1798">February 11, 2019</span></span>
<span data-ttu-id="a0b79-1799">Version 1903 (Build 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1799">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1800">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="a0b79-1800">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1801">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1801">Word</span></span> 
- <span data-ttu-id="a0b79-1802">Es wurde ein Problem behoben, bei dem einige angepasste Formatvorlagen nicht auf Word Online angewendet werden konnten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1802">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="a0b79-1803">Es wurden Probleme in der Kontextvorschau mit umfangreichen Objekten in Word behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1803">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="a0b79-1804">Es wurde ein Problem behoben, bei dem Word beim Einfügen von Listen abstürzte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1804">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1805">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1805">Excel</span></span>
- <span data-ttu-id="a0b79-1806">Es wurde ein Problem behoben, bei dem angefügte Leerzeichen nach Zahlenformaten nicht mehr angezeigt werden, wenn kein Währungssymbol vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1806">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="a0b79-1807">Es wurde ein Problem mit der automatischen Erkennung von Aktien behoben.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1807">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1808">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1808">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1809">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1809">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1810">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1810">Outlook</span></span>
- <span data-ttu-id="a0b79-1811">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1811">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1812">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1812">Access</span></span>
- <span data-ttu-id="a0b79-1813">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1813">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1814">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1814">Project</span></span>
- <span data-ttu-id="a0b79-1815">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1815">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="a0b79-1816">1. Februar 2019</span><span class="sxs-lookup"><span data-stu-id="a0b79-1816">February 1, 2019</span></span> 
<span data-ttu-id="a0b79-1817">Version 1902 (Build 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="a0b79-1817">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="a0b79-1818">Wichtige Fixes</span><span class="sxs-lookup"><span data-stu-id="a0b79-1818">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="a0b79-1819">Word</span><span class="sxs-lookup"><span data-stu-id="a0b79-1819">Word</span></span> 
- <span data-ttu-id="a0b79-1820">Ein Problem mit der Größenänderung von Zellen in einer eingebetteten Excel-Tabelle wurde behoben</span><span class="sxs-lookup"><span data-stu-id="a0b79-1820">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="a0b79-1821">Ein Problem mit dem Kopieren/Einfügen von Formen in einem Zeichenbereich wurde behoben</span><span class="sxs-lookup"><span data-stu-id="a0b79-1821">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="a0b79-1822">Excel</span><span class="sxs-lookup"><span data-stu-id="a0b79-1822">Excel</span></span>
- <span data-ttu-id="a0b79-1823">Ein Problem mit dem Öffnen von Dateien aus Excel Web App wurde behoben</span><span class="sxs-lookup"><span data-stu-id="a0b79-1823">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="a0b79-1824">Ein Problem wurde behoben, durch das das Speichern einer CSV-Datei als XLSX-Datei aufgrund der Dateinamengröße fehlschlug.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1824">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="a0b79-1825">Ein Problem mit dem Kontextmenü, dessen Kontextmenüoptionen nicht angezeigt wurden, wurde behoben</span><span class="sxs-lookup"><span data-stu-id="a0b79-1825">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a0b79-1826">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a0b79-1826">PowerPoint</span></span>
- <span data-ttu-id="a0b79-1827">Ein Problem wurde behoben, durch das Benutzer eckige Klammern nicht mithilfe der Tastenkombinationen STRG+ALT+7/STRG+ALT+8 eingeben konnten.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1827">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="a0b79-1828">Wir haben ein Problem behoben, bei dem das Einfügen eines lokalen Videos in die PPT-Datei den Festplattenspeicher des Laufwerks C reduzierte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1828">We fixed an issue where inserting a local video into the PPT would reduce the 'C' drive disk space</span></span>
- <span data-ttu-id="a0b79-1829">Die Schaltfläche "In Microsoft Stream veröffentlichen", die einigen Benutzern nicht angezeigt wurde, wurde korrigiert.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1829">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="a0b79-1830">Outlook</span><span class="sxs-lookup"><span data-stu-id="a0b79-1830">Outlook</span></span>
- <span data-ttu-id="a0b79-1831">Ein Problem wurde behoben, bei dem die Aufgabenansicht im Kalender das Thema der Aufgabe nicht richtig anzeigte.</span><span class="sxs-lookup"><span data-stu-id="a0b79-1831">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="a0b79-1832">Access</span><span class="sxs-lookup"><span data-stu-id="a0b79-1832">Access</span></span>
- <span data-ttu-id="a0b79-1833">Ein Skalierungsproblem mit Diagrammen wurde behoben</span><span class="sxs-lookup"><span data-stu-id="a0b79-1833">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="a0b79-1834">Project</span><span class="sxs-lookup"><span data-stu-id="a0b79-1834">Project</span></span>
- <span data-ttu-id="a0b79-1835">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="a0b79-1835">Various performance and stability fixes</span></span>

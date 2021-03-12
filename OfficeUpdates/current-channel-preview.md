---
title: Versionshinweise Aktueller Kanal (Vorschau)
ms.author: anankani
author: v-lislo
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Für die Zielgruppe von Insider Slow die aktuelle Liste neuer Features, Fehlerkorrekturen oder bekannter Probleme bereitstellen
ms.openlocfilehash: 64fa879f8279057f7e768c6743568516cb8046dc
ms.sourcegitcommit: d7b61837c922993e563c83df547d865c6715517b
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/12/2021
ms.locfileid: "50741638"
---
# <a name="release-notes-for-office-current-channel-preview"></a><span data-ttu-id="b48ee-103">Versionshinweise für Office Aktueller Kanal (Vorschau)</span><span class="sxs-lookup"><span data-stu-id="b48ee-103">Release Notes for Office Current Channel (Preview)</span></span>

<span data-ttu-id="b48ee-104">Dieser Artikel enthält Versionshinweise zu Builds von Word, Excel, PowerPoint, Outlook, Access, Project und Teams für Windows-Desktop für den aktuellen Kanal (Vorschau).</span><span class="sxs-lookup"><span data-stu-id="b48ee-104">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, Project, and Teams for Windows desktop.</span></span> <span data-ttu-id="b48ee-105">Jede Woche heben wir interessante neuer Features, wichtige Fixes und wesentliche Probleme hervor, über die wir Sie gerne informieren möchten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="b48ee-106">Bitte beachten Sie, dass wir Features (und häufig auch Fixes) häufig über einen Zeitraum in den aktuellen Kanal (Vorschau) einführen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-106">Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time.</span></span> <span data-ttu-id="b48ee-107">Auf diese Weise können wir sicherstellen, dass alles reibungslos funktioniert, bevor das Feature für ein breiteres Publikum bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="b48ee-108">Wenn also im Folgenden etwas nicht beschrieben wird, machen Sie sich keine Sorgen, es wird bald behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="b48ee-109">Wir nehmen einige Änderungen an den Updatekanälen für Microsoft 365-Apps vor, unter anderem fügen wir einen neuen Updatekanal hinzu (Monatlicher Enterprise-Kanal) und ändern die Namen der vorhandenen Updatekanäle.</span><span class="sxs-lookup"><span data-stu-id="b48ee-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="b48ee-110">Um mehr zu erfahren, [lesen Sie diesen Artikel](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="b48ee-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="b48ee-111">Das Veröffentlichungsdatum der Versionshinweise stimmt möglicherweise nicht mit dem tatsächlichen Veröffentlichungsdatum des Builds überein.</span><span class="sxs-lookup"><span data-stu-id="b48ee-111">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="b48ee-112">Microsoft Teams-Features unterscheiden sich möglicherweise von den neuesten veröffentlichten Features der aktuellen Kanalvorschau, da sie einen häufigeren Versionswechsel aufweisen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-112">Microsoft Teams features may differ from the latest Current Channel Preview released as they have a more frequent release cadence.</span></span>

[//]: # (NICHT ENTFERNEN)

## <a name="version-2103-march-11"></a><span data-ttu-id="b48ee-114">Version 2103: 11. März</span><span class="sxs-lookup"><span data-stu-id="b48ee-114">Version 2103: March 11</span></span>
<span data-ttu-id="b48ee-115">*Version 2103 (Build 13901.20148)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-115">*Version 2103 (Build 13901.20148)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-117">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-117">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-118">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-118">Excel</span></span>

- <span data-ttu-id="b48ee-119">**AutoSpeichern und gemeinsame Dokumentenerstellung für vertrauliche, verschlüsselte Dokumente:** Tauschen Sie nicht die Produktivität gegen die Sicherheit ein.</span><span class="sxs-lookup"><span data-stu-id="b48ee-119">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="b48ee-120">Mit Microsoft Information Protection können Dokumente, die mit Vertraulichkeitsbezeichnungen verschlüsselt sind, jetzt genauso wie unverschlüsselte Dokumente automatisch gespeichert und mit anderen in Echtzeit gemeinsam bearbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-120">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="b48ee-121">Erfordert Einverständnis des Mandanten (weitere Informationen: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="b48ee-121">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-122">Outlook</span></span>

- <span data-ttu-id="b48ee-123">**Neue Buchungserfahrung für Konferenzräume und Arbeitsbereiche:** Die Buchungserfahrung für Konferenzräume wurde aktualisiert und zudem neue Funktionen hinzugefügt, mit denen Sie auch einzelne Arbeitsbereiche planen können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-123">**New conference room and workspace booking experience:** The conference room booking experience has been refreshed, and with it we've added capabilities to allow you to schedule individual workspaces as well</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b48ee-124">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-124">PowerPoint</span></span>

- <span data-ttu-id="b48ee-125">**AutoSpeichern und gemeinsame Dokumentenerstellung für vertrauliche, verschlüsselte Dokumente:** Tauschen Sie nicht die Produktivität gegen die Sicherheit ein.</span><span class="sxs-lookup"><span data-stu-id="b48ee-125">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="b48ee-126">Mit Microsoft Information Protection können Dokumente, die mit Vertraulichkeitsbezeichnungen verschlüsselt sind, jetzt genauso wie unverschlüsselte Dokumente automatisch gespeichert und mit anderen in Echtzeit gemeinsam bearbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-126">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="b48ee-127">Erfordert Einverständnis des Mandanten (weitere Informationen: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="b48ee-127">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="visio"></a><span data-ttu-id="b48ee-128">Visio</span><span class="sxs-lookup"><span data-stu-id="b48ee-128">Visio</span></span>

- <span data-ttu-id="b48ee-129">**Office-Symbole mit neuem Look:** Die Produktsymbole wurden neu gestaltet, um die einfache, leistungsstarke und intelligente Office-Benutzeroberfläche widerzuspiegeln.</span><span class="sxs-lookup"><span data-stu-id="b48ee-129">**Office icons have a new look:** The product icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span> [<span data-ttu-id="b48ee-130">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-130">Learn more</span></span>](https://support.office.com/article/a6cdf19a-b2bd-4be1-9515-d74a37aa59bf)

### <a name="word"></a><span data-ttu-id="b48ee-131">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-131">Word</span></span>

- <span data-ttu-id="b48ee-132">**Dunkler Modus für Word-Dokumente:** Der dunkle Modus kann dabei helfen, die Augen zu entlasten und die Lichtempfindlichkeit zu berücksichtigen, während Sie an Ihren Dokumenten arbeiten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-132">**Dark Mode for Word documents:** Dark Mode may help reduce eye strain and accommodate light sensitivity while working on your documents.</span></span>

- <span data-ttu-id="b48ee-133">**AutoSpeichern und gemeinsame Dokumentenerstellung für vertrauliche, verschlüsselte Dokumente:** Tauschen Sie nicht die Produktivität gegen die Sicherheit ein.</span><span class="sxs-lookup"><span data-stu-id="b48ee-133">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="b48ee-134">Mit Microsoft Information Protection können Dokumente, die mit Vertraulichkeitsbezeichnungen verschlüsselt sind, jetzt genauso wie unverschlüsselte Dokumente automatisch gespeichert und mit anderen in Echtzeit gemeinsam bearbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-134">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="b48ee-135">Erfordert Einverständnis des Mandanten (weitere Informationen: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="b48ee-135">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>



[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-138">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-138">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b48ee-139">Zugriff</span><span class="sxs-lookup"><span data-stu-id="b48ee-139">Access</span></span>

- <span data-ttu-id="b48ee-140">Ein Problem wurde behoben, das beim Entfernen eines externen Laufwerks zu einem unerwarteten Schließen der App führen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-140">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="b48ee-141">Ein Problem wurde behoben, das, wenn eine externe Anwendung eine Benutzeroberfläche zur Barrierefreiheit anfordert, uns daran hindert, herunterzufahren, bis sie ihre Referenz freigibt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-141">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="excel"></a><span data-ttu-id="b48ee-142">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-142">Excel</span></span>

- <span data-ttu-id="b48ee-143">Ein Problem wurde behoben, das beim Entfernen eines externen Laufwerks zu einem unerwarteten Schließen der App führen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-143">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="b48ee-144">Es wurde ein Problem behoben, das dazu geführt hatte, das Excel beim Versuch, die Registerkarte „Dateitypen“ anzuzeigen, manchmal unerwartet geschlossen wurde, weil es nicht in der Lage war, ein Bild abzurufen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-144">Fixed an issue where Excel would sometimes close unexpectedly when trying to show the Data Types card due to a not being able to retrieve an image.</span></span>


- <span data-ttu-id="b48ee-145">Es wurde ein Fehler korrigiert, bei dem sich die Schriftart unerwartet veränderte, wenn ein Multiplikations- oder Divisionszeichen mit einer japanischen Schriftart verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-145">Corrected an issue where the font would change unexpectedly when using a multiplication or divide sign with a Japanese font.</span></span> <span data-ttu-id="b48ee-146">Wir verwenden jetzt weiterhin dieselbe Schriftart, wenn sie das Zeichen unterstützt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-146">We now continue to use the same font if it supports the character.</span></span>


- <span data-ttu-id="b48ee-147">Es wurde ein Problem behoben, das Benutzer am Exportieren von Excel-Arbeitsmappen nach PDF hinderte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-147">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="b48ee-148">Ein Problem wurde behoben, das dazu führte, dass Bilder bei Verwendung der Option „Verknüpftes Bild einfügen“ kleiner als erwartet waren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-148">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="b48ee-149">Ein Problem wurde behoben, bei dem einige Formatierungen verloren gehen konnten, wenn während der gemeinsamen Dokumentenerstellung ein Blatt kopiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-149">We fixed an issue where some formatting could be lost when copying a sheet while coauthoring.</span></span>


- <span data-ttu-id="b48ee-150">Ein Problem wurde behoben, bei dem beim Öffnen einer Arbeitsmappe einige Notizen unerwartet angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-150">We fixed an issue where some notes were unexpectedly shown when opening a workbook.</span></span>


- <span data-ttu-id="b48ee-151">Ein Problem wurde behoben, bei dem einige PivotTable-Formatierungen die Arbeitsmappe beschädigten, wenn diese im XLS- oder XLT-Format gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-151">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


### <a name="outlook"></a><span data-ttu-id="b48ee-152">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-152">Outlook</span></span>

- <span data-ttu-id="b48ee-153">Ein Problem wurde behoben, das beim Entfernen eines externen Laufwerks zu einem unerwarteten Schließen der App führen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-153">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="b48ee-154">Ein Problem wurde behoben, das dazu führte, dass Benutzern nach dem Erstellen einer neuen Gruppe doppelte Kalendergruppen angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-154">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="b48ee-155">Ein Problem wurde behoben, das dazu führte, dass Benutzer der Verbesserungen des geteilten Kalenders die Farbe eines Kalenders nicht auf gelb oder braun setzen konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-155">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="b48ee-156">Wir haben ein Problem behoben, das dazu führte, dass neu hinzugefügte Kalender den Benutzern erst nach einem Neustart von Outlook im Navigationsbereich angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-156">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="b48ee-157">Es wurde ein Problem behoben, das dazu führte, dass Nicht-ASCII-Zeichen beim Export in CSV falsch exportiert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-157">We fixed an issue that caused non-ASCII characters to export incorrectly when exporting to CSV.</span></span>


- <span data-ttu-id="b48ee-158">Wir haben ein Problem behoben, das dazu führte, dass einige Personen nicht auf Signaturen zugreifen konnten, die mit zweiten E-Mail-Konten verbunden waren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-158">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="b48ee-159">Wir haben ein Problem behoben, das dazu führte, dass bei der Funktion "Cloud-Einstellungen" die benutzerdefinierten Einstellungen durch die Standardeinstellung überschrieben wurden, nachdem die Benutzer Outlook auf einem neuen Gerät konfiguriert hatten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-159">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="b48ee-160">Ein Problem wurde behoben, das dazu führte, dass Benutzersignaturen mit Unicode-Inhalten beschädigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-160">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="b48ee-161">Ein Problem wurde behoben, das dazu führte, dass Benutzer der Inlineübersetzung kein Feedback abgeben konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-161">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="b48ee-162">Ein Problem wurde behoben, das dazu führte, dass Anlagen beim Entfernen des DRM-Schutzes dupliziert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-162">We fixed an issue that caused users to see attachments getting duplicated when removing DRM protection.</span></span>


- <span data-ttu-id="b48ee-163">Es wurde ein Problem behoben, das dazu führte, dass Benutzer beim Erstellen von E-Mails eine Kontaktgruppe mit „Namen überprüfen“ nicht suchen konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-163">We fixed an issue that caused users to be unable to look up a contact group with Check Names  when composing mail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b48ee-164">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-164">PowerPoint</span></span>

- <span data-ttu-id="b48ee-165">Ein Problem wurde behoben, das beim Entfernen eines externen Laufwerks zu einem unerwarteten Schließen der App führen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-165">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="b48ee-166">Es wurde ein Problem behoben, bei dem im PowerPoint-Diashowmodus Pfeile in Liniendiagrammen nicht wie erwartet angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-166">We fixed an issue where arrows in line charts were not appearing as expected in PowerPoint slideshow mode.</span></span>


- <span data-ttu-id="b48ee-167">Behebt ein Problem mit Animationsschleifen und Audiolesezeichen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-167">Fixes an issue with looping animations and audio bookmarks.</span></span>


### <a name="project"></a><span data-ttu-id="b48ee-168">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-168">Project</span></span>

- <span data-ttu-id="b48ee-169">Ein Problem wurde behoben, bei dem Visio während des Schließens manchmal nicht mehr funktionierte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-169">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="b48ee-170">Ein Problem wurde behoben, das beim Entfernen eines externen Laufwerks zu einem unerwarteten Schließen der App führen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-170">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="b48ee-171">Es wurde ein Problem behoben, das dazu geführt hatte, dass eine zu 100 % abgeschlossene Aufgabe auf den Status „99 % abgeschlossen“ zurückgesetzt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-171">Fixed an issue where a task that are 100% complete may revert back to 99% complete.</span></span>


- <span data-ttu-id="b48ee-172">Es wurde ein Problem behoben, das zum unerwarteten Schließen von Project geführt hatte, wenn Benutzer JAWS ausgeführt haben oder in den Vorgangsinformationsdialog gewechselt sind.</span><span class="sxs-lookup"><span data-stu-id="b48ee-172">Fixed an issue where Project may close unexpectedly if you are running JAWS and go to the task information dialog.</span></span>


- <span data-ttu-id="b48ee-173">Folgendes Problem wurde behoben: Wenn die Indikatorspalte nicht an der ersten Spaltenstelle stand, wurden Sie beim Ausschneiden eines Sammelvorgangs nicht gewarnt, dass auch die Unteraufgaben entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-173">Fixed an issue where if the indicator column is not in the first column spot, when you cut a summary task you aren't warned that the subtasks will also be removed.</span></span>


- <span data-ttu-id="b48ee-174">Folgendes Problem wurde behoben: Wenn ein Benutzer auf seiner Arbeitszeittabelle die Funktion „Sich selbst zu einem Vorgang hinzufügen“ auswählte, wurden möglicherweise nicht die richtigen Ressourcenverfügbarkeitseinheiten für die erstellte Aufgabe verwendet.</span><span class="sxs-lookup"><span data-stu-id="b48ee-174">Fixed an issue where if a user selected the Add Yourself to a Task function on their Timesheet, the correctly resource availability units may not be used on the created assignment.</span></span>


- <span data-ttu-id="b48ee-175">Es wurde ein Problem behoben, bei dem möglicherweise falsche Vorgangsaufteilungen erstellt wurden, wenn ein Projekt aus der Project Web App in einer lokalen Datei gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-175">Fixed an issue where task splits may be wrongly created when saving a project from Project web app to a local file.</span></span> <span data-ttu-id="b48ee-176">Dies würde beispielsweise bei Verwendung eines Vorgangskalenders mit nicht standardmäßigen Arbeitszeiten auftreten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-176">This would happen if a task calendar with non-standard working times was being used.</span></span>


### <a name="publisher"></a><span data-ttu-id="b48ee-177">Publisher</span><span class="sxs-lookup"><span data-stu-id="b48ee-177">Publisher</span></span>

- <span data-ttu-id="b48ee-178">Ein Problem wurde behoben, das beim Entfernen eines externen Laufwerks zu einem unerwarteten Schließen der App führen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-178">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="visio"></a><span data-ttu-id="b48ee-179">Visio</span><span class="sxs-lookup"><span data-stu-id="b48ee-179">Visio</span></span>

- <span data-ttu-id="b48ee-180">Ein Problem wurde behoben, bei dem Visio während des Schließens manchmal nicht mehr funktionierte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-180">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="b48ee-181">Ein Problem wurde behoben, das beim Entfernen eines externen Laufwerks zu einem unerwarteten Schließen der App führen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-181">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="word"></a><span data-ttu-id="b48ee-182">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-182">Word</span></span>

- <span data-ttu-id="b48ee-183">Es wurde ein Problem behoben, bei dem das Öffnen einer mit einer Microsoft Information Protection (MIP)-Bezeichnung geschützten Datei unbegrenzt hängen bleiben kann, wenn der Benutzer nicht mit einer Identität angemeldet ist, die Zugriff auf die MIP-geschützte Bezeichnung hat.</span><span class="sxs-lookup"><span data-stu-id="b48ee-183">We fixed an issue where opening a file protected with a Microsoft Information Protection (MIP) label can hang indefinitely if the user is not signed in to an identity that has access to the MIP protected label.</span></span> <span data-ttu-id="b48ee-184">Der Benutzer ist gezwungen, das Öffnen abbrechen, um die Anmeldeaufforderung anzuzeigen, und das Öffnen ist erst nach diesem Zeitpunkt erfolgreich.</span><span class="sxs-lookup"><span data-stu-id="b48ee-184">The user is forced to cancel the open to show the sign-in prompt, and the open only succeeds after that point.</span></span> <span data-ttu-id="b48ee-185">Das Problem wurde behoben, indem die Anmeldeaufforderung während dem Öffnen/Herunterladen angezeigt werden kann.</span><span class="sxs-lookup"><span data-stu-id="b48ee-185">Fixing this issue by allowing the sign-in prompt to be shown during open/download.</span></span>


- <span data-ttu-id="b48ee-186">Ein Problem wurde behoben, das beim Entfernen eines externen Laufwerks zu einem unerwarteten Schließen der App führen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-186">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="b48ee-187">Es wurde ein Problem bei der Verwendung von Diktat in der neuen Word-Kommentierung behoben. Die Diktat-Schaltfläche in der Kommentar-Karte schaltet nun korrekt ein und aus.</span><span class="sxs-lookup"><span data-stu-id="b48ee-187">We fixed an issue when using Dictation in the new Word Commenting, the Dictation button in the Comment card now correctly toggles on and off.</span></span>


- <span data-ttu-id="b48ee-188">Bei der gemeinsamen Dokumentenerstellung wird der aktive Entwurf nicht gelöscht, wenn sich die Kommentarreihenfolge ändert.</span><span class="sxs-lookup"><span data-stu-id="b48ee-188">When coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="b48ee-189">Es wurde ein Problem behoben, bei dem kein Leerzeichen zwischen Wörtern eingefügt wurde, wenn Benutzer in ihr Dokument diktierten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-189">Fixed an issue where there was no space being inserted between words when users dictated into their document.</span></span>


- <span data-ttu-id="b48ee-190">Behebt ein Problem in der Rendering-Pipeline im Zusammenhang mit Scrollebenen, die Scroll- oder Zoomanimationen enthalten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-190">Fixes an issue in the rendering pipeline related to scrolling layers that contain scroll or zoom animations.</span></span>


- <span data-ttu-id="b48ee-191">Behebt ein Problem mit Farben, die auf Symbole und SVG-Grafiken mit 3D-Effekten angewendet wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-191">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="b48ee-192">Es wurde ein Problem mit dem Automatischen Speichern behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-192">We fixed an issue in AutoSave.</span></span>


- <span data-ttu-id="b48ee-193">Es wurde ein Problem mit der Fußnote behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-193">We fixed an issue in footnote.</span></span>


- <span data-ttu-id="b48ee-194">Es wurde ein Problem behoben, bei dem das Veröffentlichen von mehrzeiligen, in RTL getippten Kommentaren dazu führte, dass die zweite und weitere Zeilen links statt rechts ausgerichtet wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-194">We fixed an issue when posting multi-line comments typed in RTL caused the 2nd and onward lines to be aligned to the left instead of the right.</span></span>


- <span data-ttu-id="b48ee-195">Ein Problem mit der Ausrichtung von mehreren Kommentaren wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-195">We fixed an issue with alignment of multiple comments.</span></span>


- <span data-ttu-id="b48ee-196">Ein Problem mit den Tastenkombinationen im Aufgabenbereich „Vorlesen“ wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-196">We fixed an issue in Read Aloud task pane keyboard shortcuts.</span></span>


- <span data-ttu-id="b48ee-197">Wir haben ein Problem mit der Sprachausgabe behoben, bei dem ein Absatz u. U. übersprungen wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-197">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="b48ee-198">Es wurde ein Problem behoben, bei dem die Rechtschreibprüfung zwischen zwei verschiedenen Kontextmenüs für die Rechtschreibkorrektur wechselte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-198">We fixed an issue where spell check switched between two different spelling correction context menus.</span></span>


- <span data-ttu-id="b48ee-199">Wir haben ein Problem mit Rich-Text-Inhaltssteuerelementen behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-199">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="b48ee-200">Wir haben ein Problem behoben, bei dem die Eingabe am Ende eines ausgeblendeten Absatzes dazu führen konnte, dass die Anwendung nicht mehr reagierte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-200">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


- <span data-ttu-id="b48ee-201">Es wurde ein Problem behoben, bei dem Spalten möglicherweise überlappenden Text enthalten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-201">We fixed an issue where columns might have overlapping text.</span></span>


- <span data-ttu-id="b48ee-202">Ein Problem mit dem Lesezeichen wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-202">We fixed an issue relating to bookmark.</span></span>


- <span data-ttu-id="b48ee-203">Es wurde ein Problem mit dem Auflösen von Konflikten bei der gemeinsamen Dokumenterstellung gelöst.</span><span class="sxs-lookup"><span data-stu-id="b48ee-203">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b48ee-204">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-204">Office Suite</span></span>

- <span data-ttu-id="b48ee-205">OneDrive-Orte werden nun entsprechend der Gruppenrichtlinieneinstellung herausgefiltert.</span><span class="sxs-lookup"><span data-stu-id="b48ee-205">OneDrive places are now filtered out as appropriate per the group policy setting.</span></span>


- <span data-ttu-id="b48ee-206">Ein Problem, das bei Verwendung der Sprachausgabe in Text mit mathematischen Formeln auftrat, wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-206">Fixed an issue that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="b48ee-207">Behebt ein Problem mit der Zuverlässigkeit im Zusammenhang mit der Unterstützung von Office-Apps, die in Sitzung 0 ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-207">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="b48ee-208">Behebt ein Problem mit der Zuverlässigkeit im Zusammenhang mit der Unterstützung von Office-Apps, die in Sitzung 0 ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-208">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="b48ee-209">Ein Problem wurde behoben, das beim Laden von EMF-Images dazu führte, dass das System nicht mehr reagierte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-209">Fixes an issue related to unresponsiveness that may occur when loading EMF images.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2102-march-03"></a><span data-ttu-id="b48ee-211">Version 2102: 03. März</span><span class="sxs-lookup"><span data-stu-id="b48ee-211">Version 2102: March 03</span></span>
<span data-ttu-id="b48ee-212">*Version 2102 (Build 13801.20274)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-212">*Version 2102 (Build 13801.20274)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-214">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-214">Resolved issues</span></span>
### <a name="word"></a><span data-ttu-id="b48ee-215">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-215">Word</span></span>

- <span data-ttu-id="b48ee-216">Es wurde ein Problem mit auf Symbole und SVG-Grafiken angewendeten Designinformationen behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-216">Fixes an issue with theme information applied to icons and SVG graphics.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2102-march-01"></a><span data-ttu-id="b48ee-218">Version 2102: 01. März</span><span class="sxs-lookup"><span data-stu-id="b48ee-218">Version 2102: March 01</span></span>
<span data-ttu-id="b48ee-219">*Version 2102 (Build 13801.20266)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-219">*Version 2102 (Build 13801.20266)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-221">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-221">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-222">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-222">Outlook</span></span>

- <span data-ttu-id="b48ee-223">**Freigabe an Teams:** Teilen Sie Nachrichten aus Outlook mit einer Person oder einen Kanal in Teams.</span><span class="sxs-lookup"><span data-stu-id="b48ee-223">**Share to Teams:** Share messages from Outlook with a person or channel in Teams.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-226">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-226">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-227">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-227">Outlook</span></span>

- <span data-ttu-id="b48ee-228">Ein Problem wurde behoben, das dazu führte, dass Benutzern nach dem Erstellen einer neuen Gruppe doppelte Kalendergruppen angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-228">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="b48ee-229">Ein Problem wurde behoben, das dazu führte, dass Benutzer der Verbesserungen des geteilten Kalenders die Farbe eines Kalenders nicht auf gelb oder braun setzen konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-229">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="b48ee-230">Ein Problem wurde behoben, das bei einigen Benutzern dazu führte, dass die App beim Schließen von Nachrichtenfenstern heruntergefahren wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-230">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="b48ee-231">Ein Problem wurde behoben, das dazu führte, dass Benutzersignaturen mit Unicode-Inhalten beschädigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-231">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="b48ee-232">Ein Problem wurde behoben, das dazu führte, dass Benutzer der Inlineübersetzung kein Feedback abgeben konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-232">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2102-february-21"></a><span data-ttu-id="b48ee-234">Version 2102: 21. Februar</span><span class="sxs-lookup"><span data-stu-id="b48ee-234">Version 2102: February 21</span></span>
<span data-ttu-id="b48ee-235">*Version 2102 (Build 13801.20182)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-235">*Version 2102 (Build 13801.20182)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-237">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-237">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-238">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-238">Outlook</span></span>

- <span data-ttu-id="b48ee-239">**Verfassen Sie Nachrichten mit Ihrer Stimme:** Verwenden Sie die neue Diktatsymbolleiste, neue Sprachbefehle, automatische Zeichensetzung und mehr, um Nachrichten zu verfassen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-239">**Draft messages with your voice:** Use the new dictation toolbar, voice commands, auto-punctuation, and more to compose messages.</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-240">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-240">Word</span></span>

- <span data-ttu-id="b48ee-241">**Verfassen Sie Dokumente mit Ihrer Stimme:** Verwenden Sie die neue Diktatsymbolleiste, neue Sprachbefehle und automatische Zeichensetzung, um Dokumente zu verfassen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-241">**Draft documents with your voice:** Use the new dictation toolbar, voice commands and auto-punctuation to draft documents.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-244">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-244">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-245">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-245">Excel</span></span>

- <span data-ttu-id="b48ee-246">Ein Problem wurde behoben, das dazu führte, dass Bilder bei Verwendung der Option „Verknüpftes Bild einfügen“ kleiner als erwartet waren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-246">We fixed an issue which caused images to bee smaller than expected when using the Paste Linked Picture option.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2102-february-16"></a><span data-ttu-id="b48ee-248">Version 2102: 16. Februar</span><span class="sxs-lookup"><span data-stu-id="b48ee-248">Version 2102: February 16</span></span>
<span data-ttu-id="b48ee-249">*Version 2102 (Build 13801.20160)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-249">*Version 2102 (Build 13801.20160)*</span></span>
* <span data-ttu-id="b48ee-250">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b48ee-250">Various bugs and performance fixes.</span></span>

## <a name="version-2102-february-15"></a><span data-ttu-id="b48ee-251">Version 2102: 15. Februar</span><span class="sxs-lookup"><span data-stu-id="b48ee-251">Version 2102: February 15</span></span>
<span data-ttu-id="b48ee-252">*Version 2102 (Build 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-252">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-254">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-254">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-255">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-255">Outlook</span></span>

- <span data-ttu-id="b48ee-256">**Die Diktatfunktion ist in weiteren Sprachen verfügbar:** Die Diktatfunktion unterstützt jetzt 7 neue Sprachen: Hindi, Russisch, Polnisch, Portugiesisch (Portugal), Koreanisch, Thailändisch, Chinesisch (Taiwan)</span><span class="sxs-lookup"><span data-stu-id="b48ee-256">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-257">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-257">Word</span></span>

- <span data-ttu-id="b48ee-258">**Die Diktatfunktion ist in weiteren Sprachen verfügbar:** Die Diktatfunktion unterstützt jetzt 7 neue Sprachen: Hindi, Russisch, Polnisch, Portugiesisch (Portugal), Koreanisch, Thailändisch, Chinesisch (Taiwan)</span><span class="sxs-lookup"><span data-stu-id="b48ee-258">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-261">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-261">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-262">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-262">Excel</span></span>

- <span data-ttu-id="b48ee-263">Es wurde ein Problem behoben, das Benutzer am Exportieren von Excel-Arbeitsmappen nach PDF hinderte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-263">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


### <a name="word"></a><span data-ttu-id="b48ee-264">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-264">Word</span></span>

- <span data-ttu-id="b48ee-265">Es wurde ein Problem mit dem Auflösen von Konflikten bei der gemeinsamen Dokumenterstellung gelöst.</span><span class="sxs-lookup"><span data-stu-id="b48ee-265">We fixed an issue in resolving conflicts while in coauthoring.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)


## <a name="version-2102-february-11"></a><span data-ttu-id="b48ee-267">Version 2102: 11. Februar</span><span class="sxs-lookup"><span data-stu-id="b48ee-267">Version 2102: February 11</span></span>
<span data-ttu-id="b48ee-268">*Version 2102 (Build 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-268">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-270">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-270">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="b48ee-271">Teams</span><span class="sxs-lookup"><span data-stu-id="b48ee-271">Teams</span></span>

- <span data-ttu-id="b48ee-272">**2x2-Video in Microsoft Edge- und Chrome-Browsern auf Windows und Mac:** Benutzer können in Teams-Besprechungen in Microsoft Edge- und Chrome-Browsern unter Windows und Mac die Videos von bis zu 4 Teilnehmern anzeigen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-272">**2x2 video on Edge and Chrome browsers on Windows and Mac** Users can see up to 4 participants' video in Teams meetings in Edge and Chrome browsers on Windows and Mac.</span></span> [<span data-ttu-id="b48ee-273">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-273">Learn more</span></span>](https://support.microsoft.com/office/using-video-in-microsoft-teams-3647fc29-7b92-4c26-8c2d-8a596904cdae#bkmk_videolayout)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

## <a name="version-2102-february-08"></a><span data-ttu-id="b48ee-275">Version 2102: 08. Februar</span><span class="sxs-lookup"><span data-stu-id="b48ee-275">Version 2102: February 08</span></span>
<span data-ttu-id="b48ee-276">*Version 2102 (Build 13801.20084)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-276">*Version 2102 (Build 13801.20084)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-278">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-278">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-279">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-279">Outlook</span></span>

- <span data-ttu-id="b48ee-280">**Microsoft Search-unterstütztes Verfassen (An\CC\BCC), Vorschläge:** Das Hinzufügen von Personen zur An\CC-Zeile wird jetzt von Microsoft Search unterstützt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-280">**Microsoft Search powered compose (To\CC\BCC) suggestions:** Adding people to the To\CC line is now powered by Microsoft Search.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-283">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-283">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b48ee-284">Zugriff</span><span class="sxs-lookup"><span data-stu-id="b48ee-284">Access</span></span>

- <span data-ttu-id="b48ee-285">Sie werden jetzt ausgewählte Registerkarten in Access klarer sehen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-285">You will now see selected tabs clearer in Access.</span></span>


### <a name="excel"></a><span data-ttu-id="b48ee-286">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-286">Excel</span></span>

- <span data-ttu-id="b48ee-287">Ein Problem wurde behoben, bei dem bestimmte Diagramme, die diskontinuierliche Zellbereiche verwenden, beim erneuten Öffnen von Dateien nicht geladen wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-287">Fixes issue where certain charts using discontinuous ranges of cells would not load when files are re-opened.</span></span>


- <span data-ttu-id="b48ee-288">Ein Problem wurde behoben, bei dem Excel nicht gestartet werden konnte bzw. unerwartet geschlossen wurde, wenn bestimmte Einstellungen für den Schutz vor Windows-Sicherheit-Exploits (SimExec, CallerCheck) verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-288">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="b48ee-289">Ein Problem wurde behoben, bei dem Excel nach der Auswahl einer Datenreihen in einem Diagramm nicht mehr antwortete.</span><span class="sxs-lookup"><span data-stu-id="b48ee-289">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="b48ee-290">Ein Problem wurde behoben, bei dem Excel beim Hinzufügen eines Namens im Dialogfeld "Name definieren" unerwartet beendet wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-290">We fixed an issue where Excel would unexpectedly quit when you added a Name in the Define Name dialog.</span></span>


- <span data-ttu-id="b48ee-291">Wir haben ein Problem mit Bildern behoben, damit diese während eines Zuschneidevorgangs ihr Seitenverhältnis beibehalten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-291">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="outlook"></a><span data-ttu-id="b48ee-292">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-292">Outlook</span></span>

- <span data-ttu-id="b48ee-293">Wir haben ein Problem behoben, bei dem E-Mails als digital signiert versendet wurde, obwohl der Benutzer die Option deaktiviert hatte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-293">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


- <span data-ttu-id="b48ee-294">Ein Problem wurde behoben, das dazu führte, dass das Verschlüsselungssymbol bei E-Mails, die mit der Option "Nur verschlüsseln" gesendet wurden, nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-294">We fixed an issue that caused the encryption icon to fail to display for emails sent using the Encrypt Only option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b48ee-295">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-295">PowerPoint</span></span>

- <span data-ttu-id="b48ee-296">Es wurde ein Problem beim der Anzeigen von Emojis mit Farben behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-296">Fixed an issue related to displaying emojis with color.</span></span>


- <span data-ttu-id="b48ee-297">Ein Problem mit Bildern wurde behoben, damit diese während eines Zuschneidevorgangs ihr Seitenverhältnis beibehalten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-297">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="visio"></a><span data-ttu-id="b48ee-298">Visio</span><span class="sxs-lookup"><span data-stu-id="b48ee-298">Visio</span></span>

- <span data-ttu-id="b48ee-299">Dieses Problem beim Rendern von Formen aus CAD-Schablonen wurde jetzt behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-299">This issue on shape rendering from CAD stencils has now been fixed.</span></span> <span data-ttu-id="b48ee-300">Das Problem wird mit dem neuesten Build behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-300">Users will see the issue resolved in the latest build.</span></span>


### <a name="word"></a><span data-ttu-id="b48ee-301">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-301">Word</span></span>

- <span data-ttu-id="b48ee-302">Es wurde ein Problem behoben, bei dem die Eingabe in Echtzeit und die Anwesenheit nicht wiederhergestellt werden konnten, nachdem die Internetverbindung für eine gewisse Zeit unterbrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-302">This fixes an issue that prevented real-time typing and presence from being restored after losing internet connectivity for a period of time.</span></span>


- <span data-ttu-id="b48ee-303">Wenn ein Benutzer Text in einem Kommentar auswählt, hebt Word jetzt die Auswahl von ausgewähltem Text in anderen Kommentaren auf.</span><span class="sxs-lookup"><span data-stu-id="b48ee-303">When a user selects text in a comment, Word now unselects selected text in other comments.</span></span>


- <span data-ttu-id="b48ee-304">Word erlaubt jetzt das Kopieren von Kommentartext nach Excel.</span><span class="sxs-lookup"><span data-stu-id="b48ee-304">Word now allows copying comment text into Excel.</span></span>


- <span data-ttu-id="b48ee-305">Wir haben ein Problem behoben, bei dem das Ausführen des VBA-Makros ExportAsFixedFormat2 mit dem Fehler „Präsentation (unbekanntes Mitglied) unzulässiger Wert“ fehlschlug.</span><span class="sxs-lookup"><span data-stu-id="b48ee-305">We fixed an issue when running the VBA macro ExportAsFixedFormat2 fails with an error stating "Presentation (unknown member) illegal value".</span></span>


- <span data-ttu-id="b48ee-306">Wir haben ein Problem mit Bildern behoben, damit diese während eines Zuschneidevorgangs ihr Seitenverhältnis beibehalten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-306">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


- <span data-ttu-id="b48ee-307">Wir haben ein Problem behoben, bei dem der Kommentar mit Links möglicherweise abgeschnitten wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-307">We fixed an issue which the comment may be truncated with links.</span></span>


- <span data-ttu-id="b48ee-308">Wir haben ein Problem beim Speichern nach SharePoint Online behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-308">We fixed an issue in saving to SharePoint Online</span></span>


- <span data-ttu-id="b48ee-309">Wir haben ein Problem beim Exportieren von Word-Dokumenten nach PDF behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-309">We fixed an issue in exporting Word document to PDF.</span></span>


- <span data-ttu-id="b48ee-310">Es wurde ein Problem mit AutoWiederherstellen behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-310">We fixed an issue with AutoRecover.</span></span>

- <span data-ttu-id="b48ee-311">Es wurde ein Problem bei der gemeinsamen Dokumentenerstellung mit DRM-geschützten Dateien behoben</span><span class="sxs-lookup"><span data-stu-id="b48ee-311">We fixed an issue when coauthoring with DRM protected files</span></span>


### <a name="office-suite"></a><span data-ttu-id="b48ee-312">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-312">Office Suite</span></span>

- <span data-ttu-id="b48ee-313">Ein Fehler in PowerPoint wurde behoben, bei dem das Einfügen von Aufzählungszeichen als Bilder dazu führte, dass die Aufzählungszeichen verschwanden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-313">Fixing a bug in PowerPoint where inserting bullets as images would result in bullets disappearing.</span></span> <span data-ttu-id="b48ee-314">Durch diese Korrektur werden sie zuverlässiger dargestellt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-314">This fix makes it so they render more reliably.</span></span>

- <span data-ttu-id="b48ee-315">Es wurde ein Problem behoben, bei dem Office unter bestimmten Umständen Vertraulichkeitsbezeichnungen für ein angemeldetes Konto anzeigte, wenn stattdessen Vertraulichkeitsbezeichnungen für ein anderes angemeldetes Konto angezeigt werden sollten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-315">Fixed an issue where Office would in some circumstances present sensitivity labels for one signed-in account when it should present sensitivity labels for a different signed-in account.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2101-february-03"></a><span data-ttu-id="b48ee-317">Version 2101: 03. Februar</span><span class="sxs-lookup"><span data-stu-id="b48ee-317">Version 2101: February 03</span></span>
<span data-ttu-id="b48ee-318">*Version 2101 (Build 13628.20330)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-318">*Version 2101 (Build 13628.20330)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-320">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-320">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-321">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-321">Outlook</span></span>

- <span data-ttu-id="b48ee-322">Ein Problem wurde behoben, das die Anzeige der richtigen Standardsignatur im OWA beeinträchtigt hat.</span><span class="sxs-lookup"><span data-stu-id="b48ee-322">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="b48ee-323">Ein Problem wurde behoben, das dazu geführt har, dass das Verschlüsselungssymbol bei E-Mails, die mit der Option „Nur mit Verschlüsselung“ gesendet wurden, nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-323">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2101-february-02"></a><span data-ttu-id="b48ee-325">Version 2101: 02. Februar</span><span class="sxs-lookup"><span data-stu-id="b48ee-325">Version 2101: February 02</span></span>
<span data-ttu-id="b48ee-326">*Version 2101 (Build 13628.20320)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-326">*Version 2101 (Build 13628.20320)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-328">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-328">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-329">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-329">Outlook</span></span>

- <span data-ttu-id="b48ee-330">Es wurde ein Problem behoben, das dazu führte, dass das System hängen blieb, wenn Benutzer die Einstellungen unter "Cloudeinstellungen" aktualisierten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-330">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2101-january-25"></a><span data-ttu-id="b48ee-332">Version 2101: 25. Januar</span><span class="sxs-lookup"><span data-stu-id="b48ee-332">Version 2101: January 25</span></span>
<span data-ttu-id="b48ee-333">*Version 2101 (Build 13628.20274)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-333">*Version 2101 (Build 13628.20274)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-335">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-335">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-336">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-336">Excel</span></span>

- <span data-ttu-id="b48ee-337">**Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar.</span><span class="sxs-lookup"><span data-stu-id="b48ee-337">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="b48ee-338">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-338">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="b48ee-339">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-339">Outlook</span></span>

- <span data-ttu-id="b48ee-340">**Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar.</span><span class="sxs-lookup"><span data-stu-id="b48ee-340">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="b48ee-341">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-341">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a><span data-ttu-id="b48ee-342">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-342">PowerPoint</span></span>

- <span data-ttu-id="b48ee-343">**Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar.</span><span class="sxs-lookup"><span data-stu-id="b48ee-343">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> <span data-ttu-id="b48ee-344">[Weitere Informationen](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels).</span><span class="sxs-lookup"><span data-stu-id="b48ee-344">[Learn more](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels).</span></span>


### <a name="word"></a><span data-ttu-id="b48ee-345">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-345">Word</span></span>

- <span data-ttu-id="b48ee-346">**Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar.</span><span class="sxs-lookup"><span data-stu-id="b48ee-346">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="b48ee-347">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-347">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)


### <a name="resolved-issues"></a><span data-ttu-id="b48ee-348">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-348">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-349">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-349">Outlook</span></span>

- <span data-ttu-id="b48ee-350">Ein Problem wurde behoben, das bei Benutzern mit freigegebenen oder delegierten Postfächern mit großen Hierarchien in ihrem Profil zu Blockaden führte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-350">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)



## <a name="version-2101-january-18"></a><span data-ttu-id="b48ee-352">Version 2101: 18. Januar</span><span class="sxs-lookup"><span data-stu-id="b48ee-352">Version 2101: January 18</span></span>
<span data-ttu-id="b48ee-353">*Version 2101 (Build 13628.20158)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-353">*Version 2101 (Build 13628.20158)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)



[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-357">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-357">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="b48ee-358">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-358">Project</span></span>

- <span data-ttu-id="b48ee-359">Ein Problem wurde behoben, bei dem keine Rahmen für Vorgänge in der Teamplaneransicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-359">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="b48ee-360">Ein Problem wurde behoben, bei dem Drag & Drop für Aufgaben in der Teamplaneransicht nicht funktioniert hat.</span><span class="sxs-lookup"><span data-stu-id="b48ee-360">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2101-january-13"></a><span data-ttu-id="b48ee-362">Version 2101: 13. Januar</span><span class="sxs-lookup"><span data-stu-id="b48ee-362">Version 2101: January 13</span></span>
<span data-ttu-id="b48ee-363">*Version 2101 (Build 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-363">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)
### <a name="feature-updates"></a><span data-ttu-id="b48ee-365">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-365">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="b48ee-366">Teams</span><span class="sxs-lookup"><span data-stu-id="b48ee-366">Teams</span></span>
- <span data-ttu-id="b48ee-367">**Weitere Designs:** Für Desktop- und Webclients sind jetzt neue Designs verfügbar.</span><span class="sxs-lookup"><span data-stu-id="b48ee-367">**More themes:** New themes are now available for desktop and web clients.</span></span>

- <span data-ttu-id="b48ee-368">**PPT-Freigabe:** Referentenansicht in Teams. Sobald Sie eine PowerPoint-Datei in der Teilen-Leiste von Teams auswählen, wird automatisch die Referentenansicht geöffnet.</span><span class="sxs-lookup"><span data-stu-id="b48ee-368">**PPT Sharing:** Presenter View in Teams Once you select a PowerPoint file from the Teams Share Tray, Presenter View is opened automatically.</span></span> <span data-ttu-id="b48ee-369">Die aktuelle Folie, die Foliennotizen und ein Miniaturansichtenstreifen aller Folien im Deck für eine einfache Ad-hoc-Foliennavigation wird angezeigt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-369">You can see the current slide, the slide notes, and a thumbnail strip of all the slides in the deck for easy ad-hoc slide navigation.</span></span> <span data-ttu-id="b48ee-370">Diese Ansicht befindet sich vollständig im Hintergrund, ist privat und nur für den Referenten bestimmt, der die Präsentation leitet.</span><span class="sxs-lookup"><span data-stu-id="b48ee-370">This view is completely behind the scenes, and it’s private to the presenter in control.</span></span> <span data-ttu-id="b48ee-371">Ihr Publikum kann nur die aktuelle Folie (hervorgehoben im großen roten Kasten) oder die Folie sehen, zu der es navigieren möchte (sofern die Zuschauernavigation nicht von Ihnen gesperrt wurde).</span><span class="sxs-lookup"><span data-stu-id="b48ee-371">Your audience can only see your current slide (highlighted in the big red box), or the slide that they choose to navigate to (if audience navigation is not locked by you).</span></span> 

- <span data-ttu-id="b48ee-372">**Computerton bei Desktop- oder Fensterfreigabe auf Mac einbeziehen:** Wenn Sie einen Desktop oder ein Fenster aus Teams auf dem Mac freigeben, können Sie jetzt auch den Ton Ihres Computers freigeben, damit die Personen, die an der Besprechung teilnehmen, den Ton aus Ihrem Computer hören können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-372">**Include computer sound when desktop or window sharing on Mac** When you share a desktop or window from Teams on Mac, you can now include your computer's sound so people that have joined the meeting can hear the audio playing out of your computer.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)
<br/>

## <a name="version-2101-january-09"></a><span data-ttu-id="b48ee-374">Version 2101: 9. Januar</span><span class="sxs-lookup"><span data-stu-id="b48ee-374">Version 2101: January 09</span></span>
<span data-ttu-id="b48ee-375">*Version 2101 (Build 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-375">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-377">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-377">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-378">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-378">Outlook</span></span>

- <span data-ttu-id="b48ee-379">**Schreibvorschläge mit einem Klick:** Übernehmen Sie Schreibvorschläge mit nur einem Klick.</span><span class="sxs-lookup"><span data-stu-id="b48ee-379">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="b48ee-380">Der Editor korrigiert die Rechtschreibung und Grammatik und gibt Ihnen Anregungen, um Ihren Text zu optimieren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-380">Editor corrects spelling and grammar and gives you ideas for refining your writing.</span></span> [<span data-ttu-id="b48ee-381">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-381">Learn more</span></span>](https://support.office.com/article/1e72a440-89a6-457c-bd76-cd5cea901dc0)<br /><span data-ttu-id="b48ee-382">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://insider.office.com/de-DE/blog/microsoft-editor-gets-an-upgrade)</span><span class="sxs-lookup"><span data-stu-id="b48ee-382">See details in [blog post](https://insider.office.com/de-DE/blog/microsoft-editor-gets-an-upgrade)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-385">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-385">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-386">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-386">Outlook</span></span>

- <span data-ttu-id="b48ee-387">Wir haben ein Problem behoben, das bei einigen Benutzern dazu führte, dass Outlook in bestimmten Suchszenarien unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-387">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2101-january-07"></a><span data-ttu-id="b48ee-389">Version 2101: 7. Januar</span><span class="sxs-lookup"><span data-stu-id="b48ee-389">Version 2101: January 07</span></span>
<span data-ttu-id="b48ee-390">*Version 2101 (Build 13628.20030)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-390">*Version 2101 (Build 13628.20030)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-392">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-392">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-393">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-393">Excel</span></span>

- <span data-ttu-id="b48ee-394">**Blenden Sie viele Blätter gleichzeitig ein:** Sie müssen nicht mehr ein Blatt nach dem anderen einblenden – Sie können mehrere ausgeblendete Blätter gleichzeitig einblenden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-394">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="b48ee-395">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-395">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

- <span data-ttu-id="b48ee-396">**Verbesserte Dialogfelder für bedingte Formatierung:** Die Größe von Dialogfeldern für bedingte Formatierung kann jetzt geändert und die Regel mit einem einzigen Klick dupliziert werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-396">**Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click.</span></span> [<span data-ttu-id="b48ee-397">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-397">Learn more</span></span>](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-400">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-400">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-401">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-401">Excel</span></span>

- <span data-ttu-id="b48ee-402">Ein Problem wurde behoben, bei dem Excel fälschlicherweise eine Meldungsleiste anzeigt, dass eine neue Version der Datei verfügbar ist, und den Benutzer auffordert, seine Änderungen in einer Kopie der Arbeitsmappe zu speichern oder die Änderungen zu verwerfen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-402">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="b48ee-403">Es wurde ein Problem mit dem Wechsel von Trennzeichen nach einem Aufruf von Selection.Parent.Copy behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-403">Fixed an issue with switching separators after a Selection.Parent.Copy call.</span></span>


- <span data-ttu-id="b48ee-404">Leistungsverbesserungen wurden erzielt, wenn Formatvorlagen auf Pivot-Tabellen angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-404">Made a performance improvement when applying formatting styles to pivot tables.</span></span>


- <span data-ttu-id="b48ee-405">Es wurde ein Problem behoben, bei dem Excel möglicherweise Makros ohne Anfrage deaktiviert lässt, wenn eine Excel-Add-In-Datei geöffnet wird, die Excel 4.0 Makros beinhaltet.</span><span class="sxs-lookup"><span data-stu-id="b48ee-405">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="b48ee-406">Aktualisierung, damit die Einstellungen für Dezimal- und Tausendertrennzeichen übernommen werden, wenn ein Diagramm aus Excel kopiert und in Word eingefügt wird</span><span class="sxs-lookup"><span data-stu-id="b48ee-406">Update so that decimal and thousands separators settings carryover when copying a chart from Excel and pasting into Word</span></span>


- <span data-ttu-id="b48ee-407">Ein Problem wurde behoben, durch das Excel beim Öffnen von UNC-Dateien mit ungültigen Dateiattributen (Erstellungszeit, Änderungszeit usw.) unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-407">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="b48ee-408">Es wurde ein Problem behoben, das bei Verwendung der STOCKHISTORY-Funktion die Warnung „keine Ressourcen mehr“ verursachen könnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-408">Fixed an issue which could cause an "out of resources" alert when using the STOCKHISTORY function.</span></span>


- <span data-ttu-id="b48ee-409">Es wurde eine FuzzyClustering dll zur Liste der PQ dlls hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-409">Added a FuzzyClustering dll to PQ dlls list.</span></span>


- <span data-ttu-id="b48ee-410">Diese Änderung behebt ein Problem im Zusammenhang mit dem Ändern der Umrissfarben von SVG-Bildern.</span><span class="sxs-lookup"><span data-stu-id="b48ee-410">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="b48ee-411">Ein Problem wurde behoben, bei dem die Vorschau des eingebetteten Excel-Bereich in PowerPoint eine falsche Größe anzeigt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-411">We have fixed an issue where Preview of embedded Excel range in PowerPoint shows incorrect size.</span></span>


### <a name="onenote"></a><span data-ttu-id="b48ee-412">OneNote</span><span class="sxs-lookup"><span data-stu-id="b48ee-412">OneNote</span></span>

- <span data-ttu-id="b48ee-413">Diese Änderung adressiert ein Rendering-Problem, das OneNote betrifft.</span><span class="sxs-lookup"><span data-stu-id="b48ee-413">This change addresses a rendering issue affecting OneNote.</span></span>


### <a name="outlook"></a><span data-ttu-id="b48ee-414">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-414">Outlook</span></span>

- <span data-ttu-id="b48ee-415">Ein Problem wurde behoben, das dazu führte, dass Benutzer beim Starten eines Seriendrucks von Word aus nicht angeben konnten, wie lange sie den Zugriff zulassen wollten, was dazu führte, dass sie übermäßig viele Eingabeaufforderungen erhielten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-415">We fixed an issue that caused users to be unable to specify how long they wanted to allow access for when starting a mail merge from Word, resulting in them getting excess prompts.</span></span>


- <span data-ttu-id="b48ee-416">Durch diese Änderung kann Outlook eine Exchange-Servereinstellung nutzen, welche die Anzeige des Exchange Online-Archivpostfachs für Endbenutzer unterdrückt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-416">This change enables Outlook to take advantage of an Exchange server setting that suppresses the display of the Exchange Online Archive Mailbox to end users.</span></span>


- <span data-ttu-id="b48ee-417">Es wurde ein Problem behoben, das dazu führte, dass Outlook für Benutzer von auf Einlösung basierenden Add-Ins unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-417">We fixed an issue that caused a Outlook to close unexpectedly for users of Redemption based Add-ins.</span></span>


- <span data-ttu-id="b48ee-418">Es wurde ein Problem behoben, bei dem Benutzer nicht mehr als eine Kategorie für die Suche auswählen konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-418">We fixed and issue that caused users to be unable to select more than one category to search.</span></span>


- <span data-ttu-id="b48ee-419">Es wurde ein Problem behoben, bei dem die Startzeit einiger Kalenderelemente unerwartet verändert wurden, wenn ein Ereignis aus einem anderen Termin kopiert wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-419">We fixed an issue that caused the start time of some calendar items to change unexpectedly when the event is copied from another appointment.</span></span>


- <span data-ttu-id="b48ee-420">Behebung eines Problems, das dazu führte, dass Klartext-S/MIME-Nachrichten beim Senden verstümmelt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-420">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b48ee-421">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-421">PowerPoint</span></span>

- <span data-ttu-id="b48ee-422">Diese Änderung adressiert ein Problem beim Formen zusammenführen, wenn mit Text gearbeitet wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-422">This change addresses an issue with Merge Shapes working with text.</span></span>


- <span data-ttu-id="b48ee-423">Diese Änderung behebt ein Problem im Zusammenhang mit dem Ändern der Umrissfarben von SVG-Bildern.</span><span class="sxs-lookup"><span data-stu-id="b48ee-423">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="b48ee-424">Diese Änderung behebt ein Problem mit der wiederholten Wiedergabe von Hintergrundvideos in einer Bildschirmpräsentation.</span><span class="sxs-lookup"><span data-stu-id="b48ee-424">This change addresses an issue with looping background videos playback in Slide Show.</span></span>


- <span data-ttu-id="b48ee-425">Es wurde ein Problem behoben, bei dem der Befehl "Schriftgrad", der in QAT hinzugefügt wurde, beim Aktualisieren automatisch zum nächsten definierten Schriftgrad vervollständigt wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-425">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


### <a name="project"></a><span data-ttu-id="b48ee-426">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-426">Project</span></span>

- <span data-ttu-id="b48ee-427">Ein Problem wurde behoben, bei dem die maximalen Einheiten einer Ressource nicht immer die letzte Aktualisierung der maximalen Einheiten widerspiegelten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-427">Fixed an issue where a resource's max units would not always reflect the latest update to max units.</span></span>


### <a name="visio"></a><span data-ttu-id="b48ee-428">Visio</span><span class="sxs-lookup"><span data-stu-id="b48ee-428">Visio</span></span>

- <span data-ttu-id="b48ee-429">Das Problem trat aufgrund einer aktuellen Regression auf.</span><span class="sxs-lookup"><span data-stu-id="b48ee-429">The issue occurred due to a recent regression.</span></span> <span data-ttu-id="b48ee-430">Dieses Problem wurde gelöst.</span><span class="sxs-lookup"><span data-stu-id="b48ee-430">We have resolved the issue.</span></span> <span data-ttu-id="b48ee-431">Im Dialogfeld „als Webseite speichern“ werden die Felder nun nach den Benutzereingaben ordnungsgemäß ausgefüllt, und die Benutzer können Ihre Dateien nahtlos als Webseiten speichern.</span><span class="sxs-lookup"><span data-stu-id="b48ee-431">"Save as Web Page" dialog will now have the fields correctly populated as per the user inputs and users can seamlessly save their files as web pages.</span></span>


- <span data-ttu-id="b48ee-432">Das Problem wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-432">This issue has been fixed.</span></span> <span data-ttu-id="b48ee-433">Sie können jetzt Visio-Dateien als Objekte in anderen Office-Anwendungen wie PowerPoint und Word einbetten und aus diesen Anwendungen nahtlos darauf zugreifen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-433">You can now embed Visio files as objects in other Office applications like PowerPoint and Word and seamlessly access them from within these applications.</span></span>


### <a name="word"></a><span data-ttu-id="b48ee-434">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-434">Word</span></span>

- <span data-ttu-id="b48ee-435">Es wurde ein Problem behoben, bei dem Computer mit benutzerdefinierten Hash-Einstellungen Probleme bekamen, wenn sie in eine Gemeinschaftssitzung mit einer anderen Hash-Einstellung als sha512 eintraten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-435">Fixed an issue where machines with custom hash settings were running in to issues when they got into a collab session with a hash setting other than sha512.</span></span>


- <span data-ttu-id="b48ee-436">Diese Änderung behebt ein Problem im Zusammenhang mit dem Ändern der Umrissfarben von SVG-Bildern.</span><span class="sxs-lookup"><span data-stu-id="b48ee-436">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="b48ee-437">Ein Problem beim Bearbeiten von Kommentaren mit @erwähnen wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-437">Fixed an issue when editing commenting post with @mention.</span></span>


- <span data-ttu-id="b48ee-438">Ein Problem wurde behoben, um moderne Kommentare robuster zu machen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-438">Fixed an issue to make Modern comments more robust.</span></span>


- <span data-ttu-id="b48ee-439">Es wurde ein Problem mit dem Löschen von modernen Kommentaren in einem Inhaltssteuerelement behoben, das als nicht bearbeitbar gekennzeichnet ist.</span><span class="sxs-lookup"><span data-stu-id="b48ee-439">We fixed an issue around deleting modern comments in a content control that is marked as not editable.</span></span>


- <span data-ttu-id="b48ee-440">Es wurde ein Problem mit der Animation behoben, wenn am Ende der Kommentarkarte eine Eingabe gemacht wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-440">Fix animation when typing on the bottom of a comment card.</span></span>


- <span data-ttu-id="b48ee-441">Behebung des Problems, bei dem das Antwortfeld auf einer Kommentarkarte nicht auf dem Bildschirm angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-441">Fixes an issue where the reply box on a comment card is off the screen.</span></span>


- <span data-ttu-id="b48ee-442">Behebung des Problems mit einer Kommentarkarte, die oben auf der Seite angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-442">Fixes an issue with a comment card displaying at top of page.</span></span>


- <span data-ttu-id="b48ee-443">Behebung eines Problems in Kommentaren, bei denen Text über den Bildschirm hinausgehen kann.</span><span class="sxs-lookup"><span data-stu-id="b48ee-443">Fixes bug in comments where text can scroll off screen.</span></span>


- <span data-ttu-id="b48ee-444">Behebung eines Problems mit verschachtelten Bildlaufleisten im Kommentarbereich.</span><span class="sxs-lookup"><span data-stu-id="b48ee-444">Fix and issue with nested scrollbars in the comments pane.</span></span>


- <span data-ttu-id="b48ee-445">Kommentarentwürfe verschwinden beim Anlegen einer neuen Word-Instanz.</span><span class="sxs-lookup"><span data-stu-id="b48ee-445">Comment drafts disappears when creating a new Word instance.</span></span>


- <span data-ttu-id="b48ee-446">Es wurde ein Problem behoben, bei dem Word beim Speichern von Dokumenten mit verborgenem Text ins PDF-Format hängen bleibt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-446">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2012-january-04"></a><span data-ttu-id="b48ee-448">Version 2012: 4. Januar</span><span class="sxs-lookup"><span data-stu-id="b48ee-448">Version 2012: January 04</span></span>
<span data-ttu-id="b48ee-449">*Version 2012 (Build 13530.20316)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-449">*Version 2012 (Build 13530.20316)*</span></span>
* <span data-ttu-id="b48ee-450">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b48ee-450">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-452">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-452">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-453">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-453">Excel</span></span>

- <span data-ttu-id="b48ee-454">**Erforderliche Kennzeichnung:** Benutzer mit einer von ihren Administratoren festgelegten Richtlinie „Erforderliche Kennzeichnung“ müssen ihre Dokumente und E-Mails kennzeichnen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-454">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b48ee-455">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-455">PowerPoint</span></span>

- <span data-ttu-id="b48ee-456">**Erforderliche Kennzeichnung:** Benutzer mit einer von ihren Administratoren festgelegten Richtlinie „Erforderliche Kennzeichnung“ müssen ihre Dokumente und E-Mails kennzeichnen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-456">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-457">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-457">Word</span></span>

- <span data-ttu-id="b48ee-458">**Erforderliche Kennzeichnung:** Benutzer mit einer von ihren Administratoren festgelegten Richtlinie „Erforderliche Kennzeichnung“ müssen ihre Dokumente und E-Mails kennzeichnen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-458">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2012-december-28"></a><span data-ttu-id="b48ee-460">Version 2012: 28. Dezember</span><span class="sxs-lookup"><span data-stu-id="b48ee-460">Version 2012: December 28</span></span>
<span data-ttu-id="b48ee-461">*Version 2012 (Build 13530.20264)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-461">*Version 2012 (Build 13530.20264)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-463">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-463">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-464">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-464">Outlook</span></span>

- <span data-ttu-id="b48ee-465">Es wurde ein Problem behoben, das bei einigen Kunden dazu führte, dass sich das System beim Laden ihrer Kalender aufhängte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-465">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2012-december-21"></a><span data-ttu-id="b48ee-467">Version 2012: 21. Dezember</span><span class="sxs-lookup"><span data-stu-id="b48ee-467">Version 2012: December 21</span></span>
<span data-ttu-id="b48ee-468">*Version 2012 (Build 13530.20218)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-468">*Version 2012 (Build 13530.20218)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-470">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-470">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-471">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-471">Excel</span></span>

- <span data-ttu-id="b48ee-472">**Überwachungsdaten über vertrauliche Bezeichnungen an M365-Administratoren senden:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, sendet Office Überwachungsdaten an das Back-End der M365-Überwachung, damit Administratoren sie sehen können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-472">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="b48ee-473">Dies ist eine Hintergrundfunktionalität (keine Benutzeroberfläche) für Administrator-Zwecke.</span><span class="sxs-lookup"><span data-stu-id="b48ee-473">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-474">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-474">Outlook</span></span>

- <span data-ttu-id="b48ee-475">**Einbauen einer Zeitspanne zwischen unmittelbar aufeinander folgenden Besprechungen**: Geben Sie den Teilnehmern Zeit für eine Atempause und oder den Weg zwischen verschiedenen Besprechungsorten, indem Sie festlegen, dass Besprechungen standardmäßig 5–10 Minuten verspätet beginnen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-475">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="b48ee-476">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-476">Learn more</span></span>](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

- <span data-ttu-id="b48ee-477">**Überwachungsdaten über vertrauliche Bezeichnungen an M365-Administratoren senden:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, sendet Office Überwachungsdaten an das Back-End der M365-Überwachung, damit Administratoren sie sehen können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-477">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="b48ee-478">Dies ist eine Hintergrundfunktionalität (keine Benutzeroberfläche) für Administrator-Zwecke.</span><span class="sxs-lookup"><span data-stu-id="b48ee-478">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b48ee-479">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-479">PowerPoint</span></span>

- <span data-ttu-id="b48ee-480">**Überwachungsdaten über vertrauliche Bezeichnungen an M365-Administratoren senden:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, sendet Office Überwachungsdaten an das Back-End der M365-Überwachung, damit Administratoren sie sehen können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-480">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="b48ee-481">Dies ist eine Hintergrundfunktionalität (keine Benutzeroberfläche) für Administrator-Zwecke.</span><span class="sxs-lookup"><span data-stu-id="b48ee-481">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-482">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-482">Word</span></span>

- <span data-ttu-id="b48ee-483">**Überwachungsdaten über vertrauliche Bezeichnungen an M365-Administratoren senden:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, sendet Office Überwachungsdaten an das Back-End der M365-Überwachung, damit Administratoren sie sehen können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-483">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="b48ee-484">Dies ist eine Hintergrundfunktionalität (keine Benutzeroberfläche) für Administrator-Zwecke.</span><span class="sxs-lookup"><span data-stu-id="b48ee-484">This is a silent functionality (no UI) for administrator benefit.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-487">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-487">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="b48ee-488">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-488">PowerPoint</span></span>

- <span data-ttu-id="b48ee-489">Es wurde ein Problem behoben, bei dem der Befehl "Schriftgrad", der in QAT hinzugefügt wurde, beim Aktualisieren automatisch zum nächsten definierten Schriftgrad vervollständigt wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-489">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2012-december-14"></a><span data-ttu-id="b48ee-491">Version 2012: 14. Dezember</span><span class="sxs-lookup"><span data-stu-id="b48ee-491">Version 2012: December 14</span></span>
<span data-ttu-id="b48ee-492">*Version 2012 (Build 13530.20144)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-492">*Version 2012 (Build 13530.20144)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-494">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-494">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-495">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-495">Outlook</span></span>

- <span data-ttu-id="b48ee-496">**Ihre Outlook-Einstellungen in der Cloud:** Wählen Sie Ihre Outlook für Windows-Einstellungen aus, z. B. Automatische Antworten, Posteingang mit Relevanz und Datenschutz, und greifen Sie auf jedem beliebigen PC darauf zu.</span><span class="sxs-lookup"><span data-stu-id="b48ee-496">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-499">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-499">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="b48ee-500">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-500">Office Suite</span></span>

- <span data-ttu-id="b48ee-501">Binäre Größe optimiert.</span><span class="sxs-lookup"><span data-stu-id="b48ee-501">Optimized binary size.</span></span>


- <span data-ttu-id="b48ee-502">Anaheim WebView unterstützt noch keinen Windows Information Protection (WIP).</span><span class="sxs-lookup"><span data-stu-id="b48ee-502">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="b48ee-503">Mit diesem Fix wird die Add-In-Plattform in Office wieder abwärtskompatibel mit WebView in einer Umgebung mit aktiviertem WIP.</span><span class="sxs-lookup"><span data-stu-id="b48ee-503">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="b48ee-504">Dabei kann es sich entweder um Microsoft Edge Spartan WebView oder Trident WebView handeln, abhängig von der Computerumgebung des Kunden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-504">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="b48ee-505">Beide abwärtskompatiblem WebViews unterstützen WIP.</span><span class="sxs-lookup"><span data-stu-id="b48ee-505">Both down level WebViews support WIP.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2012-december-07"></a><span data-ttu-id="b48ee-507">Version 2012: 7. Dezember</span><span class="sxs-lookup"><span data-stu-id="b48ee-507">Version 2012: December 07</span></span>
<span data-ttu-id="b48ee-508">*Version 2012 (Build 13530.20064)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-508">*Version 2012 (Build 13530.20064)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-510">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-510">Feature updates</span></span>

### <a name="teams"></a><span data-ttu-id="b48ee-511">Teams</span><span class="sxs-lookup"><span data-stu-id="b48ee-511">Teams</span></span>

- <span data-ttu-id="b48ee-512">**Windows native Benachrichtigung wird jetzt in Teams unterstützt:** Benutzer können nun die von ihnen bevorzugte Art der Benachrichtigungszustellung auswählen, entweder über in Teams integrierte Banner oder über die nativen Windows-Banner.</span><span class="sxs-lookup"><span data-stu-id="b48ee-512">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through Teams built-in banners or the Windows native banners.</span></span>


- <span data-ttu-id="b48ee-513">**Teams-Besprechungen 2x2-Katalogansicht in Citrix und VMware VDI:** Die Teams-Funktion in VDI 2x2-Katalogansicht ermöglicht das Anzeigen von bis zu vier Teilnehmervideos in der 2x2-Katalogansicht auf VDI-Clients von Citrix und VMware, wenn der Microsoft Teams-Client im VDI-optimierten Modus ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-513">**Teams Meetings 2x2 Gallery View in Citrix and VMWare VDI:** Teams on VDI 2x2 Gallery View feature will enable to view up to four attendees videos in 2x2 Gallery View on VDI clients from Citrix, VMWare when Teams client in VDI optimized mode.</span></span>


- <span data-ttu-id="b48ee-514">**Besprechungsreaktionen:**  Besprechungsreaktionen stellen eine neue Möglichkeit zur Interaktion in Besprechungen dar.</span><span class="sxs-lookup"><span data-stu-id="b48ee-514">**Meeting Reactions:**  Meeting reactions are a new way to interact in meetings.</span></span> <span data-ttu-id="b48ee-515">Teilnehmer können Reaktionen senden, die als Stream auf freigegebene Inhalte angezeigt werden, und auf der Person, welche die Reaktion gesendet hat, wenn sie in der Besprechungsphase angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-515">Participants can send reactions which are shown as a stream on content that is being shared, and on the individual who sent the reaction if they're displayed on the meeting stage.</span></span> 


- <span data-ttu-id="b48ee-516">**Zusammen-Modus und umfangreicher Katalog für Webbesprechungen** Mit dem großen Katalog können Sie Videos von bis zu 49 anderen Benutzern gleichzeitig sehen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-516">**Together Mode and Large Gallery for Web Meetings** Large Gallery enables you to see the videos of up to 49 other people at once.</span></span> <span data-ttu-id="b48ee-517">Diese Option ist verfügbar, wenn mindestens zehn Personen Ihre Kameras aktiviert haben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-517">This option is available when at least ten people have their cameras turned on.</span></span> <span data-ttu-id="b48ee-518">Im Zusammen-Modus fühlen Sie sich, wie wenn Sie mit allen Teilnehmern des Meetings im selben gemeinsamen Raum wären.</span><span class="sxs-lookup"><span data-stu-id="b48ee-518">Together mode lets you feel like you're in the same shared space with everyone in the meeting.</span></span> <span data-ttu-id="b48ee-519">Der Zusammen-Modus ist verfügbar, wenn sich mindestens fünf Personen in der Besprechung befinden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-519">Together mode is available when there are at least five people in the meeting.</span></span> 


- <span data-ttu-id="b48ee-520">**Anruf-Zusammenführung** Mit dem Zusammenführen von Anrufen können Benutzer einen neuen zu startenden Anruf oder einen neuen eingehenden Anruf in ihren 1:1- oder Gruppen-Anruf zusammenführen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-520">**Call Merge** Call Merge allows users to merge a new call they place, or a new incoming call, into their 1-1 or group call.</span></span> <span data-ttu-id="b48ee-521">Das gilt für Teams VoIP- und PSTN-Anrufe.</span><span class="sxs-lookup"><span data-stu-id="b48ee-521">This applies to Teams VOIP calls and PSTN calls.</span></span> 


### <a name="visio"></a><span data-ttu-id="b48ee-522">Visio</span><span class="sxs-lookup"><span data-stu-id="b48ee-522">Visio</span></span>

- <span data-ttu-id="b48ee-523">**Neue Azure-Schablonen und -Formen:** Wir haben viele weitere Schablonen hinzugefügt, die Ihnen beim Erstellen von aktuellen Azure-Diagrammen helfen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-523">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="b48ee-524">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-524">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-527">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-527">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-528">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-528">Excel</span></span>

- <span data-ttu-id="b48ee-529">Ein Problem wurde behoben, bei dem einige Menübandelemente nicht in Chinesisch (vereinfacht) lokalisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-529">We fixed an issue where some Ribbon elements were not localized in Simplified Chinese.</span></span>


- <span data-ttu-id="b48ee-530">Ein Problem wurde behoben, bei dem Excel beim Aktualisieren unerwartet beendet wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-530">We fixed an issue where Excel terminated unexpectedly when updating.</span></span>


- <span data-ttu-id="b48ee-531">Ein Problem wurde behoben, bei dem der Befehl "Objekt einfügen" beim Einfügen einer Datei aus dem lokalen OneDrive-Synchronisationsordner nicht das richtige Symbol anzeigte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-531">We fixed an issue where the Insert Object command does not show the correct icon when inserting a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="b48ee-532">Es wurde ein Problem behoben, bei dem die Bearbeitung in Sprachen, die die Verwendung von IME erfordern, bei der Bearbeitung im Überschreiben-Modus schlecht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-532">Fixed an issue where editing in languages that require use of IME would behave poorly when editing in overwrite mode.</span></span>


- <span data-ttu-id="b48ee-533">Es wurde ein Problem behoben, bei dem einigen Benutzern während der gemeinsamen Erstellung fälschlicherweise eine Statusleiste angezeigt wurde, die sie über eine neue Version einer Datei informierte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-533">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="b48ee-534">Es wurde ein Problem behoben, aufgrund dessen Excel beim Kopieren und Einfügen von Daten in der Formelansicht unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-534">Fixed an issue where Excel would close unexpectedly when copying and pasting data in formula view.</span></span>


- <span data-ttu-id="b48ee-535">Es wurde ein fehlerhafter Hyperlink zu einem Hilfeartikel in einer Warnung behoben, die angezeigt wird, wenn das automatische Speichern deaktiviert wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-535">Fixed a broken hyperlink to a help article in an alert in case Autosave becomes disabled.</span></span>


- <span data-ttu-id="b48ee-536">Es wurde ein Problem behoben, das bei der Eingabe von Daten, während Excel in bestimmten Sprachen ausgeführt wurde, dazu führen konnte, dass Excel nicht mehr funktionierte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-536">We fixed an issue where when entering data while Excel is running in certain languages could cause Excel to stop working.</span></span>


- <span data-ttu-id="b48ee-537">Durch diese Änderung wird ein Problem behoben, bei dem Schriftarten in Formeln nicht ordnungsgemäß angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-537">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="b48ee-538">Hierdurch wird ein Problem behoben, bei dem Power Pivot eine durch Tabstopps getrennte Textdatei nicht ordnungsgemäß importieren konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-538">This fixes an issue where Power Pivot wasn't able to correctly import a tab-delimited text file.</span></span>


### <a name="outlook"></a><span data-ttu-id="b48ee-539">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-539">Outlook</span></span>

- <span data-ttu-id="b48ee-540">Ein Problem wurde behoben, durch das das Feld "An:" in Aufgabenstatusberichten leer war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-540">We fixed an issue that caused the To: field to be blank in task status reports.</span></span>


- <span data-ttu-id="b48ee-541">Es wurde ein Problem behoben, das dazu führte, dass das Ereignis "MailItem.BeforeAttachmentAdd" abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-541">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="b48ee-542">Es wurde ein Problem behoben, aufgrund dessen Benutzer einige Probleme beim Senden von Outlook-E-Mails von anderen Anwendungen als Outlook haben konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-542">We fixed an issue that was causing users to experience some issues when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="b48ee-543">Es wurde ein Problem behoben, aufgrund dessen die Formatierung von SmartLinks beim Speichern in Entwürfen verloren ging.</span><span class="sxs-lookup"><span data-stu-id="b48ee-543">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="b48ee-544">Ein Problem wurde behoben, bei dem das Hinzufügen einer Anlage zu einer aus einer Zip-Datei geöffneten Nachricht fehlschlug.</span><span class="sxs-lookup"><span data-stu-id="b48ee-544">We fixed and issue where adding an attachment to a message opened from a zip file would fail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b48ee-545">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-545">PowerPoint</span></span>

- <span data-ttu-id="b48ee-546">Ein Problem mit dem Kopieren/Einfügen einer Formel aus Word in PowerPoint wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-546">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="b48ee-547">Diese Änderung behebt ein Problem im Zusammenhang mit Timeouts, die während der Freihandanalyse aufgetreten sind.</span><span class="sxs-lookup"><span data-stu-id="b48ee-547">This change addresses an issue related to timeouts experienced during ink analysis.</span></span>


- <span data-ttu-id="b48ee-548">Diese Änderung behebt einen Grammatikfehler in der Benutzeroberfläche für die Erstellung animierter GIFs.</span><span class="sxs-lookup"><span data-stu-id="b48ee-548">This change addresses a grammatical error in the Create an Animated GIF user interface.</span></span>


- <span data-ttu-id="b48ee-549">Diese Änderung behebt ein Problem mit Pfadfüllungen beim Anwenden von "Formen zusammenführen"-Vorgängen mit bestimmten Geometrien.</span><span class="sxs-lookup"><span data-stu-id="b48ee-549">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="b48ee-550">Durch diese Änderung wird ein Problem behoben, bei dem Schriftarten in Formeln nicht ordnungsgemäß angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-550">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="b48ee-551">Durch diese Änderung wird ein Problem beim Behandeln von Fehlern behoben, das während des Ladens von Videos auftreten konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-551">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="b48ee-552">Ein VBA-Problem wurde behoben, bei dem "Slide.Shapes.AddMediaObject2" bei veralteten Videoformaten abstürzte (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="b48ee-552">We fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="b48ee-553">Es wurde ein Problem behoben, bei dem der Anwesenheitsindikator eines unbekannten Mitautors nicht vollständig aktualisiert wurde, wenn weitere Informationen über den Mitverfasser verfügbar waren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-553">We fixed an issue where an unknown coauthor's presence indicator does not get completely refreshed when more information about the coauthor is available.</span></span>


- <span data-ttu-id="b48ee-554">Es wurde ein Problem mit einem NULL-Zeiger behoben, der dereferenziert wurde, wenn die Größe der Folienansicht bei aktiviertem Lineal geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-554">Fixed a null pointer being dereferenced when slide view is resized with ruler turned on.</span></span>


- <span data-ttu-id="b48ee-555">Ein Problem wurde behoben, bei dem einige beschädigte PowerPoint-Dateien auch nach einem Dokumentreparaturvorgang nicht ordnungsgemäß geöffnet wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-555">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="b48ee-556">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-556">Project</span></span>

- <span data-ttu-id="b48ee-557">Es wurde ein Problem behoben, bei dem Benutzer beim Öffnen von Projekten, die angeblich mit aktualisierten Informationen gespeichert wurden, feststellten, dass keine Aktualisierungen vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-557">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


- <span data-ttu-id="b48ee-558">Ein Problem wurde behoben, bei dem keine Abhängigkeiten von Projektleistungen gelöscht werden konnten, wenn die SharePoint-Website, der die Projektleistung zugeordnet war, nicht mehr vorhanden war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-558">We fixed an issue where you couldn't delete dependencies on the deliverables if the SharePoint site the deliverable was associated with no longer existed.</span></span>


- <span data-ttu-id="b48ee-559">Es wurde ein Problem behoben, bei dem das Öffnen eines Projekts mit vielen Ressourcen sehr lange dauerte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-559">Fixed an issue where opening a project with a lot of resources was taking a long time.</span></span>


- <span data-ttu-id="b48ee-560">Es wurde ein Problem behoben, bei dem Benutzern u. U. mehrere nicht zugewiesene Zuordnungen angezeigt wurden, die einer Aufgabe zugeordnet waren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-560">Fixed an issue where users may see multiple unassigned assignments associated with a task.</span></span>


- <span data-ttu-id="b48ee-561">Es wurde ein Problem behoben, bei dem bei großen Projekten die Eingabe von Aufgabennamen sehr langsam sein konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-561">Fixed an issue where in large projects it can be very slow to enter a task name.</span></span>


- <span data-ttu-id="b48ee-562">Es wurde ein Problem behoben, bei dem bestimmte Projekte geöffnet werden konnten, wenn ein Problem mit der Projektdatei in einem bestimmten Teil der Last vorlag.</span><span class="sxs-lookup"><span data-stu-id="b48ee-562">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="b48ee-563">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-563">Word</span></span>

- <span data-ttu-id="b48ee-564">Das Einfügen als nur-Text wird häufig gegenüber Rich-Text-Formatierung bevorzugt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-564">Paste as plain text is often preferred to pasting as rich text.</span></span> <span data-ttu-id="b48ee-565">Mit diesem Kontextmenü-Fix kann der Benutzer Inhalte als nur-Text einfügen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-565">This context menu fix allows the user to paste as plain text.</span></span> <span data-ttu-id="b48ee-566">Andernfalls müsste er ihn zunächst in einen nur-Text-Editor wie Notepad kopieren und dann aus dem Editor in die gewünschte Ziel-Anwendung kopieren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-566">Else the user would have to copy into a plain-text editor like Notepad and then copy from Notepad into the desired target app</span></span>


- <span data-ttu-id="b48ee-567">Ein Problem mit dem Kopieren/Einfügen einer Formel aus Word in PowerPoint wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-567">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="b48ee-568">Durch diese Änderung wird ein Problem mit dem Cursor beim Bearbeiten eines Dokuments behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-568">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="b48ee-569">Es wurde ein Problem mit verschwommenen Bildern beim Zoomen behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-569">We fixed an issue related to pictures becoming blurry while zooming.</span></span>


- <span data-ttu-id="b48ee-570">Ein Problem wurde behoben, bei dem lange Links abgeschnitten wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-570">We fixed an issue where long hyperlinks were getting truncated.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b48ee-571">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-571">Office Suite</span></span>

- <span data-ttu-id="b48ee-572">Office-Suite: Es wurde ein Problem behoben, bei dem aufgrund fehlender Registrierungseinträge die Installation einer neueren Version von Office über bestimmte ältere Versionen zu einer eingeschränkten Funktionalität führen konnte (beispielsweise war die Verwendung der Power-Abfrage nicht möglich).</span><span class="sxs-lookup"><span data-stu-id="b48ee-572">Office Suite Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2011-december-01"></a><span data-ttu-id="b48ee-574">Version 2011: 1. Dezember</span><span class="sxs-lookup"><span data-stu-id="b48ee-574">Version 2011: December 01</span></span>
<span data-ttu-id="b48ee-575">*Version 2011 (Build 13426.20306)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-575">*Version 2011 (Build 13426.20306)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-577">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-577">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-578">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-578">Outlook</span></span>

- <span data-ttu-id="b48ee-579">**Alle Besprechungen online:** Vereinfacht die Planung von Online-Besprechungen durch eine neue Einstellung, bei der alle Ihre Besprechungen standardmäßig online sind.</span><span class="sxs-lookup"><span data-stu-id="b48ee-579">**Every meeting online:** Make it easier to schedule online meetings with a new setting to make all your meetings online by default.</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-582">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-582">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-583">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-583">Outlook</span></span>

- <span data-ttu-id="b48ee-584">Es wurde ein Problem behoben, aufgrund dessen die ursprünglichen Teilnehmer einiger Besprechungen eine Veranstaltungsabsage erhielten, wenn ein anderer Teilnehmer die Besprechung weiterleitete.</span><span class="sxs-lookup"><span data-stu-id="b48ee-584">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="b48ee-585">Es wurde ein Problem behoben, aufgrund dessen einige Benutzer keine Signaturen im Signaturen-Dropdownfeld sehen konnten, obwohl mindestens eine Signatur konfiguriert war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-585">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


### <a name="project"></a><span data-ttu-id="b48ee-586">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-586">Project</span></span>

- <span data-ttu-id="b48ee-587">Es wurde ein Problem behoben, bei dem bestimmte Projekte geöffnet werden konnten, wenn ein Problem mit der Projektdatei in einem bestimmten Teil der Last vorlag.</span><span class="sxs-lookup"><span data-stu-id="b48ee-587">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2011-november-24"></a><span data-ttu-id="b48ee-589">Version 2011: 24. November</span><span class="sxs-lookup"><span data-stu-id="b48ee-589">Version 2011: November 24</span></span>
<span data-ttu-id="b48ee-590">*Version 2011 (Build 13426.20294)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-590">*Version 2011 (Build 13426.20294)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-592">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-592">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="b48ee-593">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-593">Office Suite</span></span>

- <span data-ttu-id="b48ee-594">Ein Problem mit dem Kopieren/Einfügen einer Formel aus Word in PowerPoint wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-594">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2011-november-21"></a><span data-ttu-id="b48ee-596">Version 2011: 21. November</span><span class="sxs-lookup"><span data-stu-id="b48ee-596">Version 2011: November 21</span></span>
<span data-ttu-id="b48ee-597">*Version 2011 (Build 13426.20274)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-597">*Version 2011 (Build 13426.20274)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-599">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-599">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="b48ee-600">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-600">PowerPoint</span></span>

- <span data-ttu-id="b48ee-601">**Videobibliothek:** Erweitern Sie Ihre Dokumente mit einer Sammlung von kuratierten, lizenzfreien, in der App verfügbaren Videoaufnahmen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-601">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-604">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-604">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-605">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-605">Outlook</span></span>

- <span data-ttu-id="b48ee-606">Es wurde ein Problem behoben, durch das das MailItem.BeforeAttachmentAdd-Ereignis unterbrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-606">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="b48ee-607">Es wurde ein Registrierungsschlüssel hinzugefügt, mit dem Kunden die Einbeziehung der Dateizeit für Anhänge in IDataObject-Operationen (d. h. Drag & Drop, Zwischenablage) deaktivieren können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-607">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="b48ee-608">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="b48ee-608">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="b48ee-609">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="b48ee-609">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="b48ee-610">0 = Dateizeiten sind ausgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-610">0 = filetimes are excluded.</span></span> <span data-ttu-id="b48ee-611">1 = (Standard) Dateizeiten sind enthalten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-611">1 = (default) filetimes are included</span></span>


- <span data-ttu-id="b48ee-612">Es wurde ein Problem behoben, das dazu führte, dass Inline-Bilder verschwanden, wenn auf eine Nachricht mit einer Schutzbezeichnung von Azure Information Protection geantwortet wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-612">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2011-november-18"></a><span data-ttu-id="b48ee-614">Version 2011: 18. November</span><span class="sxs-lookup"><span data-stu-id="b48ee-614">Version 2011: November 18</span></span>
<span data-ttu-id="b48ee-615">*Version 2011 (Build 13426.20250)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-615">*Version 2011 (Build 13426.20250)*</span></span>
* <span data-ttu-id="b48ee-616">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b48ee-616">Various bugs and performance fixes.</span></span>

## <a name="version-2011-november-16"></a><span data-ttu-id="b48ee-617">Version 2011: 16. November</span><span class="sxs-lookup"><span data-stu-id="b48ee-617">Version 2011: November 16</span></span>
<span data-ttu-id="b48ee-618">*Version 2011 (Build 13426.20234)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-618">*Version 2011 (Build 13426.20234)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-620">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-620">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-621">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-621">Outlook</span></span>

- <span data-ttu-id="b48ee-622">**Die gleiche Signatur auf allen Geräten:** Ihre Signatur wird in der Cloud gespeichert.</span><span class="sxs-lookup"><span data-stu-id="b48ee-622">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="b48ee-623">Erstellen Sie die Signatur einmal, und verwenden Sie diese überall, wo Sie Outlook verwenden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-623">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-626">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-626">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-627">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-627">Outlook</span></span>

- <span data-ttu-id="b48ee-628">Es wurde ein Problem behoben, das dazu führte, dass das Feld „An“ beim Senden eines Statusberichts zu einer Aufgabe leer war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-628">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b48ee-629">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-629">PowerPoint</span></span>

- <span data-ttu-id="b48ee-630">Ein VBA-Problem wurde behoben, bei dem "Slide.Shapes.AddMediaObject2" bei veralteten Videoformaten abstürzte (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="b48ee-630">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2011-november-09"></a><span data-ttu-id="b48ee-632">Version 2011: 9. November</span><span class="sxs-lookup"><span data-stu-id="b48ee-632">Version 2011: November 09</span></span>
<span data-ttu-id="b48ee-633">*Version 2011 (Build 13426.20184)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-633">*Version 2011 (Build 13426.20184)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-635">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-635">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-636">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-636">Excel</span></span>

- <span data-ttu-id="b48ee-637">**Erstellen von Power Platform-Datenflüssen aus Abfragen:** Jetzt können Sie Ihre Abfragen in Power Query-Vorlagen exportieren, die zum Erstellen von neuen Power Platform-Datenflüssen verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-637">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-640">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-640">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b48ee-641">Zugriff</span><span class="sxs-lookup"><span data-stu-id="b48ee-641">Access</span></span>

- <span data-ttu-id="b48ee-642">Es wurde ein Problem behoben, bei dem einige Benutzer die Fehlermeldung "Systemressource überschritten" angezeigt erhielten, wenn sie eine Abfrage aus dem synchronisierten OneDrive-Ordner exportieren wollten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-642">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>


- <span data-ttu-id="b48ee-643">Es wurde ein Problem behoben, bei dem das automatische Umschalten zwischen Formularfenstern zu einem anderen Formular führte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-643">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>


- <span data-ttu-id="b48ee-644">Es wurde ein Problem behoben, das bei Verwendung von DAO aus nicht-Office-Anwendungen dazu führte, dass die Anwendung unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-644">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="b48ee-645">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-645">Excel</span></span>

- <span data-ttu-id="b48ee-646">Es wurde ein Problem behoben, bei dem „Dateiname“ nach einem „SaveAs“-Vorgang mit aktiviertem COM-Add-In nicht geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-646">We fixed an issue where Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="b48ee-647">Ein Problem mit Power Pivot bei Verwendung einer Verbindung zu einer Oracle-Datenbank wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-647">Fixed an issue with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="b48ee-648">Es wurde ein Problem behoben, bei dem das automatische Speichern mit einer falschen/irreführenden Fehlermeldung fehlschlug, wenn im Excel-Datenmodell eine schlechte Kennzahldefinition vorhanden war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-648">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="b48ee-649">Ein Problem wurde behoben, durch das Excel unerwartet beendet wurde, wenn der Prozess der MTR-Berechnung und der Aktualisierung von Gruppenrichtlinienobjekten (z. B. über Remoteaktualisierung von Gruppenrichtlinien) ausgelöst wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-649">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="b48ee-650">Es wurde ein Problem behoben, bei dem ein Benutzer eine atomsvc-Datei (UTF8 + BOM) nicht direkt aus SharePoint öffnen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-650">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="b48ee-651">Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-651">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="b48ee-652">Es wurde ein Problem behoben, bei dem Word zu hängen scheint, wenn eine Excel-Arbeitsmappe in ein Word-Dokument eingefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-652">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="b48ee-653">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-653">Outlook</span></span>

- <span data-ttu-id="b48ee-654">Es wurde ein Problem behoben, das dazu führte, dass Outlook beim Hinzufügen oder Speichern von Anlagen sporadisch nicht mehr funktionierte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-654">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


- <span data-ttu-id="b48ee-655">Es wurde ein Problem behoben, bei dem der Schnelldruck für Bildanlagen zu einem Fehler geführt hat: "Windows kann dieses Bild nicht finden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-655">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture.</span></span> <span data-ttu-id="b48ee-656">Überprüfen Sie den Speicherort, und versuchen Sie es dann erneut."</span><span class="sxs-lookup"><span data-stu-id="b48ee-656">Check the location, and then try again".</span></span>


- <span data-ttu-id="b48ee-657">Es wurde ein Problem behoben, das dazu führte, dass Outlook im Offline-Status startete, bis die Benutzer manuell wählten, online zu arbeiten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-657">We fixed an issue that caused some users to see Outlook start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="b48ee-658">Es wurde ein Problem behoben, bei dem beim Einfügen einer aus dem Besprechungsort kopierten URL an eine andere Stelle (z. B. in einen Browser) der URL ein Strickpunkt am Ende hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-658">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>


- <span data-ttu-id="b48ee-659">Es wurde ein Problem behoben, bei dem Benutzer Termine im Kalender von Microsoft 365-Gruppen in der Standardauthentifizierung nicht löschen konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-659">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="b48ee-660">Es wurde ein Problem behoben, bei dem das Starten von Outlook beim Laden des Spitznamen-Caches fehlschlug.</span><span class="sxs-lookup"><span data-stu-id="b48ee-660">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


- <span data-ttu-id="b48ee-661">Ein Problem wurde behoben, bei dem ein Postfachbesitzer die Freigabeberechtigung für den eigenen Kalender nicht verwalten konnte, da die Option abgeblendet war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-661">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="b48ee-662">Ein Problem wurde behoben, bei dem in Outlook keine Nachricht mit eingeschränkten Berechtigungen erstellt werden konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-662">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="b48ee-663">Es wurde ein Problem behoben, bei dem beim Speichern von E-Mail-Vorlagen als .OFT chinesische Zeichen in Fragezeichen geändert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-663">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b48ee-664">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-664">PowerPoint</span></span>

- <span data-ttu-id="b48ee-665">Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-665">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="b48ee-666">Es wurde ein Problem behoben, bei dem das Symbol „Inhaltsplatzhalter“ neben „Bilder“ keine QuickInfo aufwies.</span><span class="sxs-lookup"><span data-stu-id="b48ee-666">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="b48ee-667">Es wurde ein Problem behoben, bei dem die geschützte Ansicht einer Bildschirmpräsentation, die durch eine pptsx-Datei dargestellt wurde, die Bildschirmaufnahme von IRM-geschützten Dokumenten ermöglichte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-667">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>


- <span data-ttu-id="b48ee-668">Es wurde ein Problem behoben, bei dem Gitternetzlinien beim Schließen des Entwurfsfensters von den Folien verschoben wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-668">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="b48ee-669">Es wurde ein Problem behoben, bei dem beim Duplizieren einer Bildschirmpräsentation auf einen sekundären Monitor diese manchmal von einem anderen Fenster verdeckt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-669">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>


- <span data-ttu-id="b48ee-670">Es wurde ein Problem behoben, bei dem sich die Bildlaufleiste in einer Folie von selbst einstellte, nachdem die Bildschirmaufnahme bei geöffnetem Auswahlfenster gestoppt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-670">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="b48ee-671">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-671">Project</span></span>

- <span data-ttu-id="b48ee-672">Es wurde ein Problem behoben, bei dem „NewVal“ im Ereignis „ProjectBeforeTaskChange“ nicht den richtigen Wert hatte, wenn eine Verzögerung innerhalb einer Ansicht vom Typ "Aufgabenformular" geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-672">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="b48ee-673">Es wurde ein Problem behoben, bei dem Project beim Öffnen von Dateien manchmal abstürzte, wenn Ressourcenprofile auf eine bestimmte Weise angegeben waren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-673">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="b48ee-674">Es wurde ein Problem behoben, bei dem beim Speichern eines Projekts aus PWA in eine lokale MPP-Datei das ProjectBeforeTaskChangeEvent für Daten ausgelöst wurde, die vom Benutzer nicht tatsächlich geändert worden waren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-674">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="b48ee-675">Es wurde ein Problem behoben, bei dem die Suche nach einer Ressource durch Ressourcenverhandlungen anhand des Namens anstelle der GUID erfolgte, was zu Problemen führen konnte, wenn mehrere Ressourcen denselben Namen aufwiesen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-675">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


- <span data-ttu-id="b48ee-676">Es wurde ein Problem behoben, bei dem wenn es in einer Projektsite eine Aufgabenliste gab und diese gruppiert wurde, sie nicht schnell bearbeitet werden konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-676">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="b48ee-677">Es wurde ein Problem behoben, bei dem, wenn Sie eine Unternehmensressource über CSOM aktualisieren, die maximale Anzahl von Ressourcen möglicherweise verloren geht.</span><span class="sxs-lookup"><span data-stu-id="b48ee-677">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="b48ee-678">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-678">Word</span></span>

- <span data-ttu-id="b48ee-679">Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-679">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="b48ee-680">Ein Problem wurde behoben, bei dem das Klicken auf einen Kommentarhinweis nicht dazu führte, dass die Kommentarkarte in der Ansicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-680">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="b48ee-681">Ein Layout-Problem wurde behoben, bei dem sich die Linie zwischen den Spalten verschieben konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-681">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="b48ee-682">Es wurde ein Problem mit dem Nachverfolgen von Änderungen behoben, bei dem beim Öffnen von Word-Dokumenten manchmal eine Fehlermeldung angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-682">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="b48ee-683">Es wurde ein Problem behoben, bei dem Word zu hängen scheint, wenn eine Excel-Arbeitsmappe in ein Word-Dokument eingefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-683">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


- <span data-ttu-id="b48ee-684">Es wurde ein Problem mit dem Drucken behoben, das beim Anwenden von Vertraulichkeitsbezeichnungen mit Wasserzeichen auftrat.</span><span class="sxs-lookup"><span data-stu-id="b48ee-684">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b48ee-685">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-685">Office Suite</span></span>

- <span data-ttu-id="b48ee-686">Es wurde ein Problem mit dem Office-Bereitstellungstool behoben, bei dem die Konfiguration fehlschlug, wenn das Feature "RemoveMSI" in Anwesenheit des Produkts „Microsoft-Anwendungsfehler-Berichterstattung“ in Office 2007 verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-686">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="b48ee-687">Es wurde ein Problem behoben, bei dem bei der interaktiven SSO-API-Anmeldung ein Fehlercode zurückgegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-687">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-november-06"></a><span data-ttu-id="b48ee-689">Version 2010: 6. November</span><span class="sxs-lookup"><span data-stu-id="b48ee-689">Version 2010: November 06</span></span>
<span data-ttu-id="b48ee-690">*Version 2010 (Build 13328.20356)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-690">*Version 2010 (Build 13328.20356)*</span></span>
* <span data-ttu-id="b48ee-691">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b48ee-691">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)



[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-november-04"></a><span data-ttu-id="b48ee-694">Version 2010: 4. November</span><span class="sxs-lookup"><span data-stu-id="b48ee-694">Version 2010: November 04</span></span>
<span data-ttu-id="b48ee-695">*Version 2010 (Build 13328.20340)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-695">*Version 2010 (Build 13328.20340)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-697">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-697">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-698">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-698">Excel</span></span>

- <span data-ttu-id="b48ee-699">**Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-699">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="b48ee-700">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-700">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="b48ee-701">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-701">Outlook</span></span>

- <span data-ttu-id="b48ee-702">**Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-702">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="b48ee-703">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-703">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="b48ee-704">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-704">PowerPoint</span></span>

- <span data-ttu-id="b48ee-705">**Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-705">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="b48ee-706">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-706">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="b48ee-707">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://insider.office.com/de-DE/blog/svg-content-office-third-party-apps)</span><span class="sxs-lookup"><span data-stu-id="b48ee-707">See details in [blog post](https://insider.office.com/de-DE/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="b48ee-708">**Erstellen von GIFs mit transparenten Hintergründen:** Wenn Sie in ein animiertes GIF exportieren, ermöglicht Ihnen eine neue Option den transparenten Hintergrund.</span><span class="sxs-lookup"><span data-stu-id="b48ee-708">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span><br /><span data-ttu-id="b48ee-709">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/export-animated-gifs-transparent-backgrounds)</span><span class="sxs-lookup"><span data-stu-id="b48ee-709">See details in [blog post](https://insider.office.com/de-DE/blog/export-animated-gifs-transparent-backgrounds)</span></span>

- <span data-ttu-id="b48ee-710">**Exportieren eines animierten GIF in einem Bereich:** Folienbereich auswählen, wenn Sie nach animiertem GIF exportieren</span><span class="sxs-lookup"><span data-stu-id="b48ee-710">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-711">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-711">Word</span></span>

- <span data-ttu-id="b48ee-712">**Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-712">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="b48ee-713">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-713">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-716">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-716">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-717">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-717">Outlook</span></span>

- <span data-ttu-id="b48ee-718">Es wurde ein Problem behoben, durch das Benutzer ihren Delegierten keine Editor-Berechtigung erteilen konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-718">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b48ee-719">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-719">Office Suite</span></span>

- <span data-ttu-id="b48ee-720">Wir haben ein Problem behoben, das zu einem Fehlschlag beim Versuch führte, Dateien zu speichern, die von SyncBacked auf „Nur Server“ übergegangen sind.</span><span class="sxs-lookup"><span data-stu-id="b48ee-720">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-october-27"></a><span data-ttu-id="b48ee-722">Version 2010: 27. Oktober</span><span class="sxs-lookup"><span data-stu-id="b48ee-722">Version 2010: October 27</span></span>
<span data-ttu-id="b48ee-723">*Version 2010 (Build 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-723">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-727">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-727">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-728">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-728">Outlook</span></span>

- <span data-ttu-id="b48ee-729">Wir haben ein Problem behoben, durch das die Cloudeinstellungen standardmäßig nicht für Benutzer aktiviert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-729">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="b48ee-730">Es wurde ein Problem behoben, durch das die Änderungen an einer Benutzersignatur nicht gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-730">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-october-24"></a><span data-ttu-id="b48ee-732">Version 2010: 24. Oktober</span><span class="sxs-lookup"><span data-stu-id="b48ee-732">Version 2010: October 24</span></span>
<span data-ttu-id="b48ee-733">*Version 2010 (Build 13328.20278)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-733">*Version 2010 (Build 13328.20278)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)



[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-737">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-737">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-738">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-738">Outlook</span></span>

- <span data-ttu-id="b48ee-739">Es wurde ein Problem behoben, durch das die Kopfzeilen chinesischer Nachrichten bei der Beantwortung oder Weiterleitung nicht lesbar waren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-739">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="b48ee-740">Es wurde ein Problem behoben, durch das chinesische Zeichen beim Speichern als OFT-Datei in Fragezeichen geändert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-740">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="project"></a><span data-ttu-id="b48ee-741">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-741">Project</span></span>

- <span data-ttu-id="b48ee-742">Es wurde ein Problem behoben, bei dem beim Speichern eines Projekts aus PWA in eine lokale MPP-Datei das ProjectBeforeTaskChangeEvent für Daten ausgelöst wurde, die vom Benutzer nicht tatsächlich geändert worden waren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-742">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="b48ee-743">Es wurde ein Problem behoben, bei dem das Ereignis NewVal im ProjectBeforeTaskChange nicht den richtigen Wert hat, wenn eine Verzögerung innerhalb einer Ansicht vom Typ "Aufgabenformular" geändert wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-743">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-october-19"></a><span data-ttu-id="b48ee-745">Version 2010: 19. Oktober</span><span class="sxs-lookup"><span data-stu-id="b48ee-745">Version 2010: October 19</span></span>
<span data-ttu-id="b48ee-746">*Version 2010 (Build 13328.20210)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-746">*Version 2010 (Build 13328.20210)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-748">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-748">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-749">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-749">Outlook</span></span>

- <span data-ttu-id="b48ee-750">**Sparen Sie Zeit beim Verfassen von Nachrichten:** Outlook macht Ihnen Formulierungsvorschläge, sodass Sie Nachrichten schnell verfassen können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-750">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="b48ee-751">Wenn Sie den Vorschlag akzeptieren möchten, verwenden Sie einfach die TAB-Taste.</span><span class="sxs-lookup"><span data-stu-id="b48ee-751">To accept the suggestion, just use the Tab key.</span></span><br /><span data-ttu-id="b48ee-752">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/text-predictions-in-word-outlook)</span><span class="sxs-lookup"><span data-stu-id="b48ee-752">See details in [blog post](https://insider.office.com/de-DE/blog/text-predictions-in-word-outlook)</span></span>

- <span data-ttu-id="b48ee-753">**Aufheben der Sprachbarriere durch einen integrierten Übersetzer:** Ab jetzt sind keine Add-Ins für die Übersetzung mehr erforderlich!</span><span class="sxs-lookup"><span data-stu-id="b48ee-753">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="b48ee-754">Klicken Sie in einer Nachricht mit der rechten Maustaste, um bestimmte Wörter, Ausdrücke oder die gesamte Nachricht zu übersetzen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-754">In a message, right-click to translate specific words, phrases, or the whole message.</span></span> [<span data-ttu-id="b48ee-755">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-755">Learn more</span></span>](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

- <span data-ttu-id="b48ee-756">**Updates zur Verbesserung der Benutzerfreundlichkeit für Aufgaben:** visuelle Auffrischung von Aufgabenelementen</span><span class="sxs-lookup"><span data-stu-id="b48ee-756">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b48ee-757">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-757">PowerPoint</span></span>

- <span data-ttu-id="b48ee-758">**Üben Sie Ihre Präsentation mit der PowerPoint-Vorschau:** Lassen Sie sich bei den Dingen coachen, die die Aufmerksamkeit Ihrer Benutzergruppe erhöhen – wie Tempo, zu oft verwendete Wörter, Körpersprache und mehr.</span><span class="sxs-lookup"><span data-stu-id="b48ee-758">**Practice your presentation with Presenter Coach:** Get coaching on the things that help keep an audience engaged — like pacing, overused words, body language, and more.</span></span> [<span data-ttu-id="b48ee-759">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-759">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

### <a name="word"></a><span data-ttu-id="b48ee-760">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-760">Word</span></span>

- <span data-ttu-id="b48ee-761">**Der Microsoft-Editor-Bereich erhält in der Desktopversion von Word ein Update:** Die aktuelle Benutzeroberfläche im Editorbereich in Word für Desktopclients wurde aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="b48ee-761">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>

- <span data-ttu-id="b48ee-762">**Schreibvorschläge mit einem Klick:** Übernehmen Sie Schreibvorschläge mit nur einem Klick.</span><span class="sxs-lookup"><span data-stu-id="b48ee-762">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="b48ee-763">Der aktualisierte Editor-Bereich erleichtert die Navigation zwischen den Vorschlägen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-763">The updated Editor pane makes it easy to navigate between suggestions.</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-766">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-766">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="b48ee-767">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-767">PowerPoint</span></span>

- <span data-ttu-id="b48ee-768">Hierbei handelt es sich um einen Fix für ein Problem, bei dem beim Schließen des Dokuments die Aufforderung „Speichern“ in einer Schleife angezeigt wird, wenn es ein Add-In gibt, das auf das Ereignis PresentationBeforeClose hört und die Eigenschaft Presentation.Saved als Teil des Ereignishandlers prüft.</span><span class="sxs-lookup"><span data-stu-id="b48ee-768">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-october-11"></a><span data-ttu-id="b48ee-770">Version 2010: 11. Oktober</span><span class="sxs-lookup"><span data-stu-id="b48ee-770">Version 2010: October 11</span></span>
<span data-ttu-id="b48ee-771">*Version 2010 (Build 13328.20154)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-771">*Version 2010 (Build 13328.20154)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-773">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-773">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-774">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-774">Excel</span></span>

- <span data-ttu-id="b48ee-775">**Schützen Sie Ihre Daten vor schädlichen Dateien:** Application Guard schützt Sie vor Schadsoftware, indem Sie Office-Dateien in einem isolierten Container lesen, drucken und speichern können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-775">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="b48ee-776">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-776">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="powerpoint"></a><span data-ttu-id="b48ee-777">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-777">PowerPoint</span></span>

- <span data-ttu-id="b48ee-778">**Schützen Sie Ihre Daten vor schädlichen Dateien:** Application Guard schützt Sie vor Schadsoftware, indem Sie Office-Dateien in einem isolierten Container lesen, drucken und speichern können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-778">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="b48ee-779">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-779">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="word"></a><span data-ttu-id="b48ee-780">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-780">Word</span></span>

- <span data-ttu-id="b48ee-781">**Schützen Sie Ihre Daten vor schädlichen Dateien:** Application Guard schützt Sie vor Schadsoftware, indem Sie Office-Dateien in einem isolierten Container lesen, drucken und speichern können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-781">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="b48ee-782">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-782">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-785">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-785">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b48ee-786">Zugriff</span><span class="sxs-lookup"><span data-stu-id="b48ee-786">Access</span></span>

- <span data-ttu-id="b48ee-787">Ein Problem wurde behoben, bei dem die Position der Bildlaufleiste nicht ordnungsgemäß festgelegt wurde, wenn das Abfrage/Beziehungsfenster beim Scrollen geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-787">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="b48ee-788">Ein Problem wurde behoben, bei dem der Aufgabenbereich "Tabelle hinzufügen" Namen mit "&" nicht korrekt anzeigte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-788">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="b48ee-789">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-789">Excel</span></span>

- <span data-ttu-id="b48ee-790">Es wurde ein Problem behoben, bei dem die mehrstufige Kategorie "manuelles Intervall" in Diagrammen nicht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-790">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="b48ee-791">Es wurde ein Problem mit 2D-Kartendiagrammen behoben, bei dem das Festlegen der Farben für die Werte "Max.", "Mittel" und "Min." für eine Reihe bei Verwendung von VBA nicht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-791">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="b48ee-792">Es wurde ein Problem behoben, das die Fehlermeldung „Excel hat nicht ausreichend Ressourcen zur Verfügung für die Berechnung einer oder mehrerer Formeln“ verursachen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-792">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="b48ee-793">Es wurde ein Problem, bei dem in Datenüberprüfungslisten u. U. nicht alle Elemente in der Liste angezeigt wurden, wenn die Office-Sprache auf Spanisch festgelegt war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-793">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="b48ee-794">Ein Problem wurde behoben, bei dem beim Wechseln zwischen Arbeitsblättern mit großen Datenmengen eine deutliche Verzögerung auftrat, wenn ‚Seitenumbruchvorschau‘ aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-794">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>


- <span data-ttu-id="b48ee-795">Es wurde ein Problem behoben, bei dem das Hinzufügen zu einer für die Datenüberprüfung verwendeten Tabelle die Optionen nicht für alle Blätter in der Arbeitsmappe aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-795">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


- <span data-ttu-id="b48ee-796">Ein Problem wurde behoben, das beim Aktualisieren von OLAP-PivotTables zu einem Absturz führen könnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-796">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="b48ee-797">Ein Problem wurde behoben, bei dem ChartSheet in einigen Fällen abgestürzt ist, wenn eine Formel über die Bearbeitungsleiste eingegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-797">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


- <span data-ttu-id="b48ee-798">Es wurde ein Problem behoben, bei dem die Excel-Formularleiste nicht vollständig gerendert werden konnte, wenn die Verbindung zu einem Gerät verloren ging, wie z. B. beim Verbinden/Trennen einer Remote-Sitzung oder bei einem Monitorwechsel.</span><span class="sxs-lookup"><span data-stu-id="b48ee-798">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>


### <a name="onenote"></a><span data-ttu-id="b48ee-799">OneNote</span><span class="sxs-lookup"><span data-stu-id="b48ee-799">OneNote</span></span>

- <span data-ttu-id="b48ee-800">Es wurde ein Problem behoben, bei dem ein Benutzer nicht in der Lage war, eine Notizbuch-URL aus einem Textfeld in OutSpace File > Info auszuwählen und zu kopieren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-800">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


- <span data-ttu-id="b48ee-801">Es wurde ein Problem behoben, dass beim Fahren mit der Maus über die grüne Farbe in der Farbauswahl des Notizbuchs das Popup "Rote Kreide" angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-801">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


- <span data-ttu-id="b48ee-802">Es wurde ein Problem behoben, bei dem OneNote im Zeichenbereich hohe Kontrastfarben für benutzerdefinierte Designs nicht beachtete.</span><span class="sxs-lookup"><span data-stu-id="b48ee-802">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


### <a name="outlook"></a><span data-ttu-id="b48ee-803">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-803">Outlook</span></span>

- <span data-ttu-id="b48ee-804">Behebt ein Problem, das dazu führte, dass automatisch generierte E-Mails mit einem leeren Textkörper gesendet wurden, wenn die Betreffzeile leer war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-804">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="b48ee-805">Es wurde ein Problem behoben, bei dem die falsche Ordner-GUID für Ordner zwischengespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-805">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="b48ee-806">Wenn ein Benutzer eine E-Mail-Adresse in das Feld "Empfänger" mit dem Anzeigenamen kopierte und einfügte, wurde die E-Mail-Adresse nicht immer ordnungsgemäß analysiert, woraufhin eine Warnung zu einer ungültigen E-Mail-Adresse angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-806">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="b48ee-807">Das Problem wurde so behoben, dass Name und E-Mail-Adresse nun ordnungsgemäß analysiert werden und die Warnung nicht mehr angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-807">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="b48ee-808">Es wurde ein Problem behoben, bei dem freigegebene Ordner nicht den übergeordneten Ordnernamen zurückgegeben haben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-808">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="b48ee-809">Anstatt wurde ein leerer Pfad zurückgegeben, der nicht ordnungsgemäß an das primäre Konto ging.</span><span class="sxs-lookup"><span data-stu-id="b48ee-809">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="b48ee-810">Es wurde ein Problem behoben, bei dem die Option "Speichern unter" für klassische Anlagen nicht verfügbar war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-810">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="b48ee-811">Es wurde ein Problem behoben, durch das ein Benutzer eine Möglichkeit zum Anpassen des Rechtfertigungstexts bietet, wenn eine Richtlinie überschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-811">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="b48ee-812">Es wurde ein Problem behoben, bei dem „Änderungen nachverfolgen“ nach dem erneuten Öffnen des Entwurfs im schreibgeschützten Vorschaufenster aktiviert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-812">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="b48ee-813">Es wurde ein Problem behoben, bei dem E-Mails ausgeblendet wurden, wenn „Posteingang mit Relevanz“ deaktiviert und eine Sortierung durchgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-813">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>


- <span data-ttu-id="b48ee-814">Es wurde ein Problem behoben, bei dem Outlook eine zweite leere Signatur für Personen mit aktivierter Cloud-Einstellung erstellt hat.</span><span class="sxs-lookup"><span data-stu-id="b48ee-814">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b48ee-815">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-815">PowerPoint</span></span>

- <span data-ttu-id="b48ee-816">Es wurde ein Problem behoben, bei dem PowerPoint beim Exportieren in das PDF-Format keine rechteckige Aufzählungspunkte exportierte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-816">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="b48ee-817">Ein Problem wurde behoben, bei dem GIF-Dateien im Editor und in Bildschirmpräsentationen nur einmal animiert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-817">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>


- <span data-ttu-id="b48ee-818">Ein Problem wurde behoben, bei dem ein verknüpftes Excel-Diagramm fälschlicherweise in eine Excel-Tabelle geändert wurde, wenn der Benutzer den Quellpfad in den lokalen OneDrive-Ordner änderte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-818">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="b48ee-819">Es wurde ein Problem behoben bei dem, wenn Sie sich auf der letzten Folie befinden und zur nächsten Folie wechseln, nachdem Sie "Sitzung beenden" gedrückt haben und bevor die Zusammenfassung angezeigt wird, der Dialog "Sitzung beenden" auch auf der Zusammenfassungsseite sichtbar ist.</span><span class="sxs-lookup"><span data-stu-id="b48ee-819">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="b48ee-820">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-820">Project</span></span>

- <span data-ttu-id="b48ee-821">Es wurde ein Problem mit der ConsolidateProjects-VBA-Methode behoben, wenn Sie versuchen, dasselbe Projekt mehrmals hinzuzufügen und AttachToSources auf "false" festzulegen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-821">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="b48ee-822">Ein Problem wurde behoben, bei dem Sie, wenn Sie einen Ereigniscode ausführen, die Änderungen über eine Aufgaben-Maske durchführen und dann durch Klicken auf die Schaltfläche OK keine Änderungen vornehmen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-822">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="b48ee-823">Es wurde ein Problem mit der ConsolidateProjects-VBA-Methode behoben, wenn Sie versuchen, dasselbe Projekt mehrmals hinzuzufügen und AttachToSources auf "false" festzulegen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-823">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="b48ee-824">Es wurde ein Problem behoben, bei dem Sie, wenn Sie benutzerdefinierte Felder mit Formeln haben und den Ertragswert verwenden, Leistungsverzögerungen beim Wechsel der Ansichten und beim Öffnen von Projekt-/Aufgabendetails feststellen konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-824">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="b48ee-825">Es wurde ein Problem behoben, bei dem Project abstürzt, wenn Sie eine Gruppe auf die Ressourcennutzung oder die Arbeitsblattanzeige anwenden und dann eine Spalte einfügen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-825">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


### <a name="word"></a><span data-ttu-id="b48ee-826">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-826">Word</span></span>

- <span data-ttu-id="b48ee-827">Ein Problem wurde behoben, bei dem Links zu workflowaktivierten Dateien nicht erwartungsgemäß geöffnet wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-827">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>


- <span data-ttu-id="b48ee-828">Es wurde ein Problem behoben, bei dem es vorkam, dass wenn ein Benutzer auf eine nachverfolgte Änderung tippte (Einfügung/Löschung), ein Kommentar-Popup angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-828">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="b48ee-829">Es wurde ein Problem mit dem Löschen von Kommentarbeschriftungen in Word behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-829">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="b48ee-830">Es wurde ein Problem in Outlook mit auf "Nicht weiterleiten" festgelegten Nachrichten behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-830">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="b48ee-831">Es wurde ein Problem mit dem Speichern eines Word-Dokuments mit Zitaten und Formeln behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-831">We fixed an issue with saving Word document that contains citation and equation.</span></span>


- <span data-ttu-id="b48ee-832">Es wurde ein Problem mit dem Dialogfeld "Formatvorlagenkatalog" behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-832">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b48ee-833">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-833">Office Suite</span></span>

- <span data-ttu-id="b48ee-834">Wenn ein Benutzer ein Dokument/ eine Datei auf Tintenstrahldrucker aus Office druckt und die Druckertinte niedrig ist, wird die Meldung "Wenig Toner" oder "Kein Toner" angezeigt, auch wenn Tintenstrahldrucker keine Toner haben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-834">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="b48ee-835">Nachricht wird geändert, um "Wenig Toner/ Tinte" & "Kein Toner/ keine Tinte" anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-835">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-october-07"></a><span data-ttu-id="b48ee-837">Version 2009: 07. Oktober</span><span class="sxs-lookup"><span data-stu-id="b48ee-837">Version 2009: October 07</span></span>
<span data-ttu-id="b48ee-838">*Version 2009 (Build 13231.20360)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-838">*Version 2009 (Build 13231.20360)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-840">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-840">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-841">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-841">Excel</span></span>

- <span data-ttu-id="b48ee-842">**Datentypen mit Microsoft Power Query für Excel erstellen:** Erstellen Sie umfangreiche Datentypen mit Microsoft Power Query für Excel von jeder Datenquelle</span><span class="sxs-lookup"><span data-stu-id="b48ee-842">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-843">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-843">Outlook</span></span>

- <span data-ttu-id="b48ee-844">**Die Grammatikprüfung hält Ihnen den Rücken frei:** Outlook markiert Grammatikfehler während der Eingabe, so dass Sie Vorschläge mit einem einzigen Klick anwenden können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-844">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> <br /><span data-ttu-id="b48ee-845">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/grammar-and-style-suggestions-available-in-outlook)</span><span class="sxs-lookup"><span data-stu-id="b48ee-845">See details in [blog post](https://insider.office.com/de-DE/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-848">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-848">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-849">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-849">Outlook</span></span>

- <span data-ttu-id="b48ee-850">Behebt ein Problem, das bewirkt, dass die Suche keine Ergebnisse zurückgibt, wenn nicht zwischengespeicherte freigegebene Kalender durchsucht werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-850">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="b48ee-851">Behebt ein Problem, das bewirkt hat, dass einige Benutzer Outlook unerwartet starten, wenn Sie offline sind.</span><span class="sxs-lookup"><span data-stu-id="b48ee-851">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="b48ee-852">Behebt ein Problem, durch das Delegaten beim Öffnen freigegebener Ordner in einem anderen Postfach zeitweilige Fehler erhalten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-852">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b48ee-853">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-853">PowerPoint</span></span>

- <span data-ttu-id="b48ee-854">Sicherheitsproblembehebung für ein Problems, bei dem IRM-Schutz beim Öffnen einer PowerPoint-Datei in der geschützten Anzeige deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-854">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b48ee-855">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-855">Office Suite</span></span>

- <span data-ttu-id="b48ee-856">Wenn ein Benutzer ein Dokument/ eine Datei auf Tintenstrahldrucker aus Office druckt und die Druckertinte niedrig ist, wird die Meldung "Wenig Toner" oder "Kein Toner" angezeigt, auch wenn Tintenstrahldrucker keine Toner haben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-856">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="b48ee-857">Nachricht wird geändert, um "Wenig Toner/ Tinte" & "Kein Toner/ keine Tinte" anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-857">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-september-26"></a><span data-ttu-id="b48ee-859">Version 2009: 26. September</span><span class="sxs-lookup"><span data-stu-id="b48ee-859">Version 2009: September 26</span></span>
<span data-ttu-id="b48ee-860">*Version 2009 (Build 13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-860">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-862">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-862">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-863">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-863">Outlook</span></span>

- <span data-ttu-id="b48ee-864">Behebt ein Problem, das dazu führte, dass einige automatisch generierte E-Mails mit einem leeren Textkörper gesendet wurden, wenn die Betreffzeile leer war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-864">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="project"></a><span data-ttu-id="b48ee-865">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-865">Project</span></span>

- <span data-ttu-id="b48ee-866">Ein Problem wurde behoben, bei dem Sie, wenn Sie einen Ereigniscode ausführen, die Änderungen über eine Aufgaben-Formularansicht durchführen und dann durch Klicken auf die Schaltfläche OK keine Änderungen vornehmen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-866">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-september-21"></a><span data-ttu-id="b48ee-868">Version 2009: 21. September</span><span class="sxs-lookup"><span data-stu-id="b48ee-868">Version 2009: September 21</span></span>
<span data-ttu-id="b48ee-869">*Version 2009 (Build 13231.20200)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-869">*Version 2009 (Build 13231.20200)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-871">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-871">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="b48ee-872">Zugriff</span><span class="sxs-lookup"><span data-stu-id="b48ee-872">Access</span></span>

- <span data-ttu-id="b48ee-873">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-873">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="b48ee-874">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="b48ee-874">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="b48ee-875">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-875">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="b48ee-876">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-876">Excel</span></span>

- <span data-ttu-id="b48ee-877">**iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-877">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="b48ee-878">Keine Konvertierung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b48ee-878">No conversion required.</span></span><br /><span data-ttu-id="b48ee-879">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="b48ee-879">See details in [blog post](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="b48ee-880">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-880">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="b48ee-881">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="b48ee-881">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="b48ee-882">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-882">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="b48ee-883">OneNote</span><span class="sxs-lookup"><span data-stu-id="b48ee-883">OneNote</span></span>

- <span data-ttu-id="b48ee-884">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-884">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="b48ee-885">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="b48ee-885">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="b48ee-886">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-886">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="b48ee-887">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-887">Outlook</span></span>

- <span data-ttu-id="b48ee-888">**Unterhaltung löschen nach Nachrichtenbesitzer:** Dieses Feature ermöglicht es Ihnen, eine Unterhaltung nach dem Nachrichtenbesitzer zu löschen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-888">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

- <span data-ttu-id="b48ee-889">**iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-889">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="b48ee-890">Keine Konvertierung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b48ee-890">No conversion required.</span></span><br /><span data-ttu-id="b48ee-891">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="b48ee-891">See details in [blog post](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="b48ee-892">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-892">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="b48ee-893">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="b48ee-893">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="b48ee-894">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-894">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="powerpoint"></a><span data-ttu-id="b48ee-895">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-895">PowerPoint</span></span>

- <span data-ttu-id="b48ee-896">**iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-896">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="b48ee-897">Keine Konvertierung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b48ee-897">No conversion required.</span></span><br /><span data-ttu-id="b48ee-898">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="b48ee-898">See details in [blog post](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="b48ee-899">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-899">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="b48ee-900">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="b48ee-900">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="b48ee-901">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-901">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="b48ee-902">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-902">Project</span></span>

- <span data-ttu-id="b48ee-903">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-903">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="b48ee-904">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="b48ee-904">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="b48ee-905">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-905">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="b48ee-906">Publisher</span><span class="sxs-lookup"><span data-stu-id="b48ee-906">Publisher</span></span>

- <span data-ttu-id="b48ee-907">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-907">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="b48ee-908">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="b48ee-908">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="b48ee-909">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-909">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="b48ee-910">Visio</span><span class="sxs-lookup"><span data-stu-id="b48ee-910">Visio</span></span>

- <span data-ttu-id="b48ee-911">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-911">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="b48ee-912">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="b48ee-912">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="b48ee-913">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-913">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="b48ee-914">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-914">Word</span></span>

- <span data-ttu-id="b48ee-915">**iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-915">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="b48ee-916">Keine Konvertierung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b48ee-916">No conversion required.</span></span><br /><span data-ttu-id="b48ee-917">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="b48ee-917">See details in [blog post](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="b48ee-918">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-918">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="b48ee-919">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="b48ee-919">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="b48ee-920">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-920">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-923">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-923">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="b48ee-924">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-924">PowerPoint</span></span>

- <span data-ttu-id="b48ee-925">Es wurde ein Problem behoben, das die gemeinsame Dokumenterstellung für Dateien mit großen Mengen eines bestimmten Datenobjekttyps (E2o) verlangsamt hat.</span><span class="sxs-lookup"><span data-stu-id="b48ee-925">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-september-14"></a><span data-ttu-id="b48ee-927">Version 2009: 14. September</span><span class="sxs-lookup"><span data-stu-id="b48ee-927">Version 2009: September 14</span></span>
<span data-ttu-id="b48ee-928">*Version 2009 (Build 13231.20152)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-928">*Version 2009 (Build 13231.20152)*</span></span>
* <span data-ttu-id="b48ee-929">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b48ee-929">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-september-10"></a><span data-ttu-id="b48ee-932">Version 2009: 10. September</span><span class="sxs-lookup"><span data-stu-id="b48ee-932">Version 2009: September 10</span></span>
<span data-ttu-id="b48ee-933">*Version 2009 (Build 13231.20126)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-933">*Version 2009 (Build 13231.20126)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-935">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-935">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b48ee-936">Access</span><span class="sxs-lookup"><span data-stu-id="b48ee-936">Access</span></span>

- <span data-ttu-id="b48ee-937">Dieses Problem wurde nun behoben, und es sollte jetzt kein Absturz mehr auftreten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-937">This issue has now been resolved and you should no longer experience a crash.</span></span>


- <span data-ttu-id="b48ee-938">Ein Problem wurde behoben, bei dem Verbindungen zu einer ODBC-Datenbank mit Anwendungen von Drittanbietern nicht funktionierten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-938">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>


### <a name="excel"></a><span data-ttu-id="b48ee-939">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-939">Excel</span></span>

- <span data-ttu-id="b48ee-940">Es wurde ein Problem behoben, bei dem beim Öffnen einer Datei, die die LET-Funktion enthält, die Warnmeldung angezeigt wurde: "Wir haben ein Problem mit dem Inhalt in "Ihrer Datei.xlsx" gefunden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-940">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="b48ee-941">Möchten Sie, dass wir so viel wie möglich wiederherstellen?</span><span class="sxs-lookup"><span data-stu-id="b48ee-941">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="b48ee-942">Wenn die Quelle für diese Arbeitsmappe vertrauenswürdig ist, klicken Sie auf „Ja“.</span><span class="sxs-lookup"><span data-stu-id="b48ee-942">If you trust the source of this workbook, click Yes".</span></span>


- <span data-ttu-id="b48ee-943">Es wurde ein Problem behoben, bei dem, wenn ein Benutzer einen Formelnamen einschließlich der Klammer eingab und die Hilfe über F1 aufrief, das für diese Formel spezifische Hilfethema nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-943">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>


- <span data-ttu-id="b48ee-944">Es wurde ein Problem behoben: Beim Festlegen der FormulaR1C1-Eigenschaft für einen Bereich mithilfe eines Makros waren die Zellbezüge falsch, wenn ein Diagrammblatt das aktive Blatt war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-944">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="b48ee-945">Es wurde ein Problem behoben, bei dem Benutzer einen PivotTable-Filter nicht ändern konnten, weil er auf einen Wert eingestellt war, der in einer Analysis Services-Datenbank nicht mehr vorhanden war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-945">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="b48ee-946">Es wurde ein Absturz im Zusammenhang mit XLAM-Add-In-Referenzen und benannten Bereichen behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-946">Fixed a crash related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="b48ee-947">Es wurde ein Problem behoben, bei dem Benutzer, die einen benutzerdefinierten Stil auf ein dynamisches Array anwandten, die Fehlermeldung erhielten: "Sie können einen Teil eines Arrays nicht ändern".</span><span class="sxs-lookup"><span data-stu-id="b48ee-947">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array".</span></span> <span data-ttu-id="b48ee-948">Hierbei handelt es sich um eine Legacy-Einschränkung, die entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-948">This was a legacy restriction that has been removed.</span></span>


- <span data-ttu-id="b48ee-949">Es wurde ein Problem behoben, bei dem den Schaltflächen zugewiesene Makros nach der Wiederherstellung einer älteren Version der Datei beschädigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-949">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>


- <span data-ttu-id="b48ee-950">Ein Problem wurde behoben, bei dem Freihandeingaben dazu führen konnten, dass Excel nicht mehr reagierte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-950">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="b48ee-951">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-951">Outlook</span></span>

- <span data-ttu-id="b48ee-952">Es wurde ein Problem behoben, das mehr Flexibilität bei der Aktivierung/Deaktivierung der Standardprotokollierungsoptionen über die Gruppenrichtlinie bietet.</span><span class="sxs-lookup"><span data-stu-id="b48ee-952">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>


- <span data-ttu-id="b48ee-953">Es wurde ein Problem behoben, bei dem der Legacy-Domänenname für einen E-Mail-Absender beibehalten und angezeigt wurde, nachdem ein Entwurf der E-Mail zwischen Postfächern mit Assistenten- und Manager-Berechtigungen verschoben wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-953">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>


- <span data-ttu-id="b48ee-954">Es wurde ein Problem behoben, das dazu führte, dass einige Benutzer Outlook im Offline-Status starteten, bis sie manuell wählten, online zu arbeiten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-954">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="b48ee-955">Es wurde ein Problem behoben, bei dem das Ausführen des VBA-Codes ActiveInspector.CommandBars.ExecuteMso ("ShowSchedulingPage") nach dem Aktivieren des Einzeiligen Menübands (SLR) zu einem Laufzeitfehler führen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-955">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>


- <span data-ttu-id="b48ee-956">Es wurde ein Problem behoben, bei dem die Schaltflächen "OK" und "Abbrechen" im Dialogfeld "Automatische Antworten" auf einem System mit einer hohen Auflösung (z. B. 1750 x 1920) in Verbindung mit einer großen Textgröße (z. B. 175 %) nicht sichtbar waren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-956">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>


- <span data-ttu-id="b48ee-957">Es wurde eine Bedingung behoben, nach der das Senden einer Besprechungsanfrage von einer leeren Kontaktgruppe an eine andere Kontaktgruppe zu einem Absturz führen würde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-957">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>


- <span data-ttu-id="b48ee-958">Es wurde ein Problem behoben, bei dem es zu einem Absturz kam, wenn Benutzer bestimmte sehr große E-Mails öffneten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-958">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="b48ee-959">Es wurde ein Problem behoben, bei dem, wenn die Gruppenrichtlinie erfordert, dass ein Add-In immer aktiviert sein muss, die Überwachungs-Add-Ins nicht mehr verfügbar sind, um Benutzer daran zu hindern, das Add-In zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-959">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>


- <span data-ttu-id="b48ee-960">Behebt ein Problem, das dazu führte, dass Benutzer durch das Auswählen mehrerer Nachrichten E-Mail-Inhalte senden konnten, für die eine "Nicht weiterleiten"-Richtlinie in OneNote festgelegt war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-960">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>


- <span data-ttu-id="b48ee-961">Ein Problem wurde behoben: Benutzer können IRM (Information Rights Management) jetzt für Outlook deaktivieren, ohne es für die übrigen Office-Anwendungen deaktivieren zu müssen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-961">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="b48ee-962">Ein Problem wurde behoben, bei dem die Benutzerkontoattribute in Active Directory für "otherTelephone" und "otherHomePhone" nicht den entsprechenden Outlook-LDAP-Attributen zugeordnet wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-962">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>


- <span data-ttu-id="b48ee-963">Diese Änderung behebt ein Problem, bei dem die Seite "Besprechung" weiterhin angezeigt wurde, nachdem der Benutzer die Registerkarten von der Seite "Besprechung" auf die Seite "Terminplanungs-Assistent" gewechselt hatte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-963">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b48ee-964">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-964">PowerPoint</span></span>

- <span data-ttu-id="b48ee-965">Ein Problem wurde behoben, bei dem das Menüband bzw. die Titelleiste unter bestimmten Bedingungen nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-965">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>


- <span data-ttu-id="b48ee-966">Es wurde ein Problem behoben, bei dem nach dem Starten von PowerPoint, dem Einfügen einer Folie und dem Öffnen und Schließen des Kommentarbereichs die Folien im Miniaturansichtenbereich als überlappend angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-966">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>


- <span data-ttu-id="b48ee-967">Es wurde ein Problem behoben, durch das die Funktion zum Einfügen eines Videos deaktiviert war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-967">We fixed an issue where the functionality to insert a video was disabled.</span></span>


- <span data-ttu-id="b48ee-968">Es wurde ein Problem behoben, bei dem Videos in Bildschirmpräsentationen nicht automatisch wiedergegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-968">We fixed an issue where videos were not playing automatically in slideshows.</span></span>


### <a name="project"></a><span data-ttu-id="b48ee-969">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-969">Project</span></span>

- <span data-ttu-id="b48ee-970">Es wurde ein Problem behoben, bei dem, wenn eine Ressource mehrere Kostensatztabellen hat, die verbleibenden Kosten möglicherweise nicht korrekt berechnet werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-970">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>


- <span data-ttu-id="b48ee-971">Es wurde ein Problem behoben, bei dem das Projektabschlussdatum für Projekte, die mit der Microsoft Office SharePoint Online-Aufgabenliste verbunden sind, nicht aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-971">We fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


### <a name="visio"></a><span data-ttu-id="b48ee-972">Visio</span><span class="sxs-lookup"><span data-stu-id="b48ee-972">Visio</span></span>

- <span data-ttu-id="b48ee-973">Die Live-Vorschau stürzt ab, wenn die Textausrichtung von Kunden gemeldet wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-973">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="b48ee-974">Häufigster Absturz im Juli, Kopie.</span><span class="sxs-lookup"><span data-stu-id="b48ee-974">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="b48ee-975">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-975">Word</span></span>

- <span data-ttu-id="b48ee-976">Es wurde ein Problem behoben, bei dem die Kommentarkarte einen Rahmen um den Kommentartext anzeigte, wenn der Benutzer auf den Kommentar klickte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-976">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>


- <span data-ttu-id="b48ee-977">Es wurde ein Problem behoben, bei dem das Aufzählungsbildsymbol nicht korrekt angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-977">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>


- <span data-ttu-id="b48ee-978">Ein Problem wurde behoben, bei dem der Benutzer die Kopf-oder Fußzeile beim Auswählen eines Kommentars nicht verlassen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-978">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>


- <span data-ttu-id="b48ee-979">Ein Problem wurde behoben, bei dem Word nach dem Löschen von Kommentaren abstürzen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-979">We fixed an issue where Word could crash after comments were deleted.</span></span>


- <span data-ttu-id="b48ee-980">Es wurde ein Problem behoben, bei dem, wenn ein Benutzer einen Kommentar-Entwurf erstellte, der in einer Zeile verankert war, die bereits bestätigte Kommentare enthielt, der Entwurf in der falschen Reihenfolge in Bezug auf den bestätigten Kommentar im SideTrack angeordnet wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-980">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>


- <span data-ttu-id="b48ee-981">Es wurde ein Problem behoben, bei dem der Fokus nicht auf den Kommentarbereich gelegt wurde, wenn das Dokument auf 160 % oder mehr gezoomt wurde und der Kommentarbereich nicht sichtbar war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-981">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>


- <span data-ttu-id="b48ee-982">Es wurde ein Problem behoben, das Benutzer daran hinderte, Benutzerkommentar-Threads zu sehen, die die Sidetrack-Grenze überschritten, weil das Scrollen durch den Sidetrack nicht funktioniert hat.</span><span class="sxs-lookup"><span data-stu-id="b48ee-982">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>


- <span data-ttu-id="b48ee-983">Ein Problem wurde behoben, bei dem die Suche nach aufgelösten Kommentaren im Sidetrack-Bereich nicht funktioniert hat.</span><span class="sxs-lookup"><span data-stu-id="b48ee-983">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>


- <span data-ttu-id="b48ee-984">Es wurde ein Problem behoben, bei dem die Kommentare zu einem Dokument auf anderen geöffneten Dokumenten angezeigt wurden, nachdem zwischen den mehreren geöffneten Dokumenten gewechselt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-984">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>


- <span data-ttu-id="b48ee-985">Es wurde ein Problem behoben, bei dem lange Links beim Speichern eines Dokuments im HTML-Format nicht umgebrochen wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-985">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="b48ee-986">Ein Problem wurde behoben, bei dem in einigen Fällen Aufzählungszeichen in E-Mails nicht korrekt angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-986">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>


- <span data-ttu-id="b48ee-987">Es wurde ein Problem mit Makros behoben, in denen „AutoOpen“ vor „AutoExec“ ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-987">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b48ee-988">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-988">Office Suite</span></span>

- <span data-ttu-id="b48ee-989">Es wurde ein Problem mit dem Office-Bereitstellungstool behoben, bei dem die Konfiguration fehlschlug, wenn das Feature "RemoveMSI" in Anwesenheit des Produkts „Microsoft-Anwendungsfehler-Berichterstattung“ in Office 2007 verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-989">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="b48ee-990">Im Dialogfeld "Bild komprimieren" wurde ein Problem behoben, bei dem einige vom Benutzer ausgewählte DPI-Einstellungen nicht beibehalten wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-990">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>


- <span data-ttu-id="b48ee-991">Diese Änderung behebt ein Problem, bei dem im Dialogfeld „Bild komprimieren“ bestimmte Benutzereinstellungen nicht beibehalten werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-991">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-september-04"></a><span data-ttu-id="b48ee-993">Version 2008: 4. September</span><span class="sxs-lookup"><span data-stu-id="b48ee-993">Version 2008: September 04</span></span>
<span data-ttu-id="b48ee-994">*Version 2008 (Build 13127.20378)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-994">*Version 2008 (Build 13127.20378)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-996">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-996">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="b48ee-997">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-997">Office Suite</span></span>

- <span data-ttu-id="b48ee-998">Diese Änderung behebt ein Problem, bei dem im Dialogfeld „Bild komprimieren“ bestimmte Benutzereinstellungen nicht beibehalten werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-998">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-september-02"></a><span data-ttu-id="b48ee-1000">Version 2008: 2. September</span><span class="sxs-lookup"><span data-stu-id="b48ee-1000">Version 2008: September 02</span></span>
<span data-ttu-id="b48ee-1001">*Version 2008 (Build 13127.20360)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1001">*Version 2008 (Build 13127.20360)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1003">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1003">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1004">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1004">Excel</span></span>

- <span data-ttu-id="b48ee-1005">**Speichern von Shapes als Bildern:** mit nur wenigen Mausklicks können Sie eine Form, ein Symbol oder ein anderes Objekt als Bilddatei speichern, um Sie an anderer Stelle wiederzuverwenden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1005">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="b48ee-1006">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-1006">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="b48ee-1007">**Schnelle Bearbeitungen mit dem Excel-Stift:** Ein Stifttool, mit dem Sie handschriftliche Eingaben machen und Ihre Daten schnell bearbeiten können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1007">**Make quick edits using the Excel pen:** Pen Tool to help you handwrite and make quick edits to your data</span></span>



[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1010">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1010">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1011">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1011">Excel</span></span>

- <span data-ttu-id="b48ee-1012">Es wurde ein Problem behoben, bei dem Excel unter bestimmten Umständen abstürzte, wenn "Format übertragen" verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1012">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="b48ee-1013">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1013">Word</span></span>

- <span data-ttu-id="b48ee-1014">Ein Problem wurde behoben, bei dem die Basisformatvorlagen nicht mit der Standardformatvorlage aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1014">We fixed an issue which the base styles are not updated with Normal style.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-august-27"></a><span data-ttu-id="b48ee-1016">Version 2008: 27. August</span><span class="sxs-lookup"><span data-stu-id="b48ee-1016">Version 2008: August 27</span></span>
<span data-ttu-id="b48ee-1017">*Version 2008 (Build 13127.20296)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1017">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1021">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1021">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-1022">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1022">Outlook</span></span>

- <span data-ttu-id="b48ee-1023">Behebt ein Problem, das dazu führte, dass Benutzer, die versuchten, eine Besprechungsanfrage von einem zu ihrem Profil hinzugefügten sekundären Konto aus zu erstellen, kein leeres Von: Feld anstelle ihrer E-Mail-Adresse sahen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1023">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="b48ee-1024">Behebt ein Problem, das dazu führte, dass Benutzer nach dem Hinzufügen eines freigegebenen Postfachs keine Verbindung mit öffentlichen Ordnern herstellen konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1024">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="b48ee-1025">Behebt ein Problem, das bei der Interaktion mit Cloud-Anlagen gelegentlich zu Abstürzen führte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1025">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="b48ee-1026">Dies behebt ein Problem, das beim Bearbeiten von Empfängern gelegentlich zu Abstürzen führte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1026">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="b48ee-1027">Behebt ein Problem, das dazu führte, dass Benutzern bei Verwendung der kompakten Ansicht gelegentlich Anomalien angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1027">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-1028">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1028">Word</span></span>

- <span data-ttu-id="b48ee-1029">Diese Änderung behebt ein Problem, bei dem Office-Anwendungen nach einer vorherigen gemeinsamen Dokumenterstellung in einem Silent-Save-Fehlerstatus hängenbleiben konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1029">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="b48ee-1030">Es wurde ein Problem behoben, bei dem das Makro „AutoOpen“ vor „Autoexec“ ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1030">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-august-25"></a><span data-ttu-id="b48ee-1032">Version 2008: 25. August</span><span class="sxs-lookup"><span data-stu-id="b48ee-1032">Version 2008: August 25</span></span>
<span data-ttu-id="b48ee-1033">*Version 2008 (Build 13127.20268)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1033">*Version 2008 (Build 13127.20268)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1035">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1035">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-1036">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1036">Outlook</span></span>

- <span data-ttu-id="b48ee-1037">**Empfangen von E-Mail-Vorschlägen bei der Suche nach Personen:** Während Sie Ihre Suchbegriffe in Outlook eingeben, werden Ihnen in den Vorschlägen die relevantesten E-Mails angezeigt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1037">**Receive email suggestions when searching by person.:** As you type your search terms in Outlook you'll receive the most relevant emails surfaced in the suggestions.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1040">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1040">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-1041">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1041">Outlook</span></span>

- <span data-ttu-id="b48ee-1042">Behebt ein Problem, durch das Benutzern beim Beantworten von oder Verfassen neuer E-Mails den folgenden Fehler angezeigt wurde: „Einige der Dateien auf dieser Webseite befinden sich nicht am erwarteten Speicherort.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1042">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="b48ee-1043">Möchten Sie sie dennoch herunterladen?</span><span class="sxs-lookup"><span data-stu-id="b48ee-1043">Do you want to download them anyway?</span></span> <span data-ttu-id="b48ee-1044">Wenn Sie sicher sind, dass die Webseite aus einer vertrauenswürdigen Quelle stammt, klicken Sie auf 'Ja'.“</span><span class="sxs-lookup"><span data-stu-id="b48ee-1044">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="b48ee-1045">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-1045">Project</span></span>

- <span data-ttu-id="b48ee-1046">Ein Problem wurde behoben, bei dem die Restkosten nicht immer richtig berechnet wurden, wenn für eine Ressource mehrere Kostensatztabellen definiert waren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1046">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


### <a name="word"></a><span data-ttu-id="b48ee-1047">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1047">Word</span></span>

- <span data-ttu-id="b48ee-1048">Es wurde ein Problem behoben, durch das es bei Benutzern beim Antworten auf oder Verfassen einer neuen E-Mail zu einem Absturz kam.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1048">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-august-17"></a><span data-ttu-id="b48ee-1050">Version 2008: 17. August</span><span class="sxs-lookup"><span data-stu-id="b48ee-1050">Version 2008: August 17</span></span>
<span data-ttu-id="b48ee-1051">*Version 2008 (Build 13127.20208)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1051">*Version 2008 (Build 13127.20208)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1053">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1053">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-1054">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1054">Outlook</span></span>

- <span data-ttu-id="b48ee-1055">Es wurde ein Problem behoben, das bewirkt hat, dass Besprechungen aus dem Kalender eines Managers nicht entfernt werden konnten, wenn sie von einem Delegierten unter bestimmten Umständen abgelehnt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1055">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="b48ee-1056">Es wurde ein Problem behoben, das bewirkt hat, dass Benutzende einiger Zeichensätze beim Hinzufügen eines Smart Link zu einer Microsoft Office SharePoint Online-Datei Dateinamen falsch angezeigt bekamen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1056">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="b48ee-1057">Es wurde ein Problem behoben, das zu einem Absturz führte, wenn Benutzende beim Löschen von 4 oder mehr E-Mails von einem POP-Konto mit der Option "Nur Kopfzeilen herunterladen" einen Absturz erlebten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1057">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="b48ee-1058">Es wurde ein Problem behoben, das bewirkt hat, dass das Rechtsklick-Kontextmenü nicht in den Suchsteuerelementen angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1058">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-august-11"></a><span data-ttu-id="b48ee-1060">Version 2008: 11. August</span><span class="sxs-lookup"><span data-stu-id="b48ee-1060">Version 2008: August 11</span></span>
<span data-ttu-id="b48ee-1061">*Version 2008 (Build 13127.20164)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1061">*Version 2008 (Build 13127.20164)*</span></span>

<span data-ttu-id="b48ee-1062">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="b48ee-1062">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1064">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1064">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b48ee-1065">Zugriff</span><span class="sxs-lookup"><span data-stu-id="b48ee-1065">Access</span></span>

- <span data-ttu-id="b48ee-1066">Diese Korrektur behebt das Problem, bei dem der Versuch, bestimmte Abfragen auszuführen, zuvor die Fehlermeldung „Abfrage ist zu komplex“ erzeugt hat.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1066">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="b48ee-1067">Wenn Sie Office 365 installiert haben, müssen Sie nicht mehr unsere ACE Redistributable Engine installieren, um ACE außerhalb des Office-Ökosystems bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1067">If you have Office 365 installed, you no longer need to install our ACE Redistributable Engine to expose ACE outside of the Office ecosystem.</span></span> <span data-ttu-id="b48ee-1068">Daher benötigen Sie für Benutzende mit Office 365 die ACE Redist Engine nicht mehr, und folglich sollte dieses Problem nicht auftreten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1068">Therefore, for those with Office 365, you will no longer need the ACE Redist Engine, and consequently you should not experience this issue.</span></span>

- <span data-ttu-id="b48ee-1069">Das Problem wurde gelöst – Sie können nun unseren ODBC-Treiber außerhalb der Office-Click-to-Run-App verwenden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1069">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="b48ee-1070">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1070">Excel</span></span>

- <span data-ttu-id="b48ee-1071">Das Problem wurde behoben, bei dem, wenn die Reihenfolge einer Diagrammserie geändert wurde, das entsprechende, an der Serie ausgerichtete Kontrollkästchen nicht zusammen mit der Serie neu geordnet wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1071">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>

- <span data-ttu-id="b48ee-1072">Beim Versuch eine Datei zu speichern, die eine Formel mit der Funktion LET() enthält, konnte ein Fehler auftreten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1072">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="b48ee-1073">Ein Problem wurde behoben, bei dem Diagramme nicht immer wie erwartet aktualisiert wurden, wenn "ForceFullCalculation" über VBA für die Arbeitsmappe aktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1073">We fixed an issue where charts were not always updated as expected when "ForceFullCalculation" was enabled via VBA for the workbook.</span></span>

- <span data-ttu-id="b48ee-1074">Ein Problem wurde behoben, bei dem die Kopie eines Bildes mit einer radialen Verlaufsfüllung nicht mit dem Original übereinstimmte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1074">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="onenote"></a><span data-ttu-id="b48ee-1075">OneNote</span><span class="sxs-lookup"><span data-stu-id="b48ee-1075">OneNote</span></span>

- <span data-ttu-id="b48ee-1076">Wir haben ein Problem behoben, bei dem der Platzhaltertext im Bearbeitungsfeld „Suchen“ überlaufen würde, wenn die Größe des Anwendungsfensters auf eine kleine Dimension geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1076">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1077">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1077">Outlook</span></span>

- <span data-ttu-id="b48ee-1078">Wir haben ein Problem beim Erstellen mehrerer Profile in Outlook von derselben E-Mail-Domäne behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1078">We fixed an issue around creating multiple profiles in Outlookfrom the same email domain.</span></span>

- <span data-ttu-id="b48ee-1079">Es wurde ein Problem behoben, durch das einige Benutzende des Features "Verbesserungen bei gemeinsam genutzten Kalendern" nicht in der Lage waren, einen neu hinzugefügten freigegebenen Kalender anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1079">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="b48ee-1080">Es wurde ein Problem behoben, das dazu führte, dass das Schloss-Symbol im Header von S/MIME-verschlüsselten Nachrichten nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1080">Addressed an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>

- <span data-ttu-id="b48ee-1081">Wir haben ein Problem behoben, bei dem die Option "Weiterleitung zulassen" in den "Antwortoptionen" der freigegebenen Kalenderbesprechung fehlte, wenn "Gemeinsamer Ordner herunterladen" NICHT aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1081">We fixed an issue where the "Allow Forwarding" option was missing from the shared calendar meeting "Response Options" if Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="b48ee-1082">Ein Problem wurde behoben, das dazu führte, dass Benutzer OneDrive-Anlagen von außerhalb ihres Mandanten nicht auf ihrem lokalen Computer speichern konnten, wenn sie im Dialogfeld "Sicherheit" die Option "Speichern" wählten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1082">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="b48ee-1083">Es wurde ein Problem behoben, bei dem die Schaltfläche "Drucken" als deaktiviert angezeigt wurde, auch wenn Benutzende über die entsprechenden Druckberechtigungen verfügten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1083">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

- <span data-ttu-id="b48ee-1084">Behebung eines Problems, das dazu führte, dass Anhänge aus S/MIME-Nachrichten entfernt wurden, wenn diese unverschlüsselt gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1084">Addressed an issue that caused attachments to get stripped from S/MIME messages when sending as unencrypted.</span></span>

- <span data-ttu-id="b48ee-1085">Behebung eines Problems, das dazu führte, dass Klartext-S/MIME-Nachrichten beim Senden verstümmelt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1085">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>

- <span data-ttu-id="b48ee-1086">Behebt ein Problem, durch das Anhänge beschädigt wurden, wenn eine S/MIME-E-Mail unverschlüsselt gesendet wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1086">Addressed an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>

- <span data-ttu-id="b48ee-1087">Es wurde ein Problem behoben, das dazu führt, dass Empfänger geschützte Nachrichten nicht speichern können, selbst wenn der/die Absender/in die Erlaubnis zum Speichern als Datei erteilt hat.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1087">Addressed an issue that cause recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>

- <span data-ttu-id="b48ee-1088">Diese Korrektur behebt ein Problem, bei dem Benutzende beim Beantworten einer mit digitalen Rechten verwalteten Nachricht in einem Inspektorfenster keine Signatur hinzufügen konnten, wenn sie keine Eigentümerrechte für die Nachricht hatten, auf die sie antworteten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1088">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>

- <span data-ttu-id="b48ee-1089">Diese Korrektur behebt ein Problem, das dazu führte, dass Outlook Zeilenumbrüche in Abschrifteninhalten nicht richtig anzeigte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1089">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

- <span data-ttu-id="b48ee-1090">Behebt ein Problem, bei dem die Bezeichnungen für einige Optionen für die erweiterte Suche in einigen Sprachen abgeschnitten wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1090">Addressed an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b48ee-1091">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1091">PowerPoint</span></span>

- <span data-ttu-id="b48ee-1092">Ein Problem wurde behoben, bei dem die Kopie eines Bildes mit einer radialen Verlaufsfüllung nicht mit dem Original übereinstimmte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1092">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="b48ee-1093">Ein Problem wurde behoben, bei dem die Schaltfläche „Formulare“ in PowerPoint das Erstellen von Formularen nicht zulässt, wenn der Zugriff auf den Microsoft Store nicht zulässig war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1093">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="b48ee-1094">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-1094">Project</span></span>

- <span data-ttu-id="b48ee-1095">Wir haben ein Problem behoben, bei dem die in der Task Board-Ansicht aufgelisteten Aufgaben nicht mit denen im Dialogfeld "Ressourcen zuordnen" synchronisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1095">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>

- <span data-ttu-id="b48ee-1096">Wir haben ein Problem behoben, bei dem beim Versuch, ein PDF/XPS aus dem Projekt in eine SharePoint-Dokumentenbibliothek zu speichern, nichts passiert.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1096">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

- <span data-ttu-id="b48ee-1097">Wir haben ein Problem behoben, bei dem beim Kopieren und Einfügen einer Aufgabe mit mehreren Abhängigkeiten nicht alle Abhängigkeiten korrekt kopiert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1097">We fixed an issue where if you copied & pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

- <span data-ttu-id="b48ee-1098">Ein Problem wurde behoben, bei dem für eine SharePoint-Aufgabenliste die Schaltflächen auf dem Menüband auf der zweiten Registerkarte deaktiviert sein können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1098">Fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="skype"></a><span data-ttu-id="b48ee-1099">Skype</span><span class="sxs-lookup"><span data-stu-id="b48ee-1099">Skype</span></span>

- <span data-ttu-id="b48ee-1100">Der Hautton des Tanzemoticons wurde auf neutrale Farbe geändert</span><span class="sxs-lookup"><span data-stu-id="b48ee-1100">Changed dancing emoticon skin tone to neutral color</span></span>

### <a name="visio"></a><span data-ttu-id="b48ee-1101">Visio</span><span class="sxs-lookup"><span data-stu-id="b48ee-1101">Visio</span></span>

- <span data-ttu-id="b48ee-1102">Wenn Benutzende nach dieser Korrektur die Ausführung des Löschbefehls durch einen dazwischen liegenden Mechanismus angehalten haben (in diesem Fall durch ein Add-in), wird der Speicher nicht lecken und die gesamte Maschine wird nicht beeinträchtigt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1102">After this fix, if the user halted the execution of delete command by any mechanism in between (in this case it was through add-in) the memory won't leak and the whole machine won't be impacted.</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-1103">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1103">Word</span></span>

- <span data-ttu-id="b48ee-1104">Ein Problem wurde behoben, bei dem Word nicht mehr reagierte, nachdem Text und ein Bild in ein Kommentarfeld eingefügt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1104">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>

- <span data-ttu-id="b48ee-1105">Ein Problem wurde behoben, bei dem die Kopie eines Bildes mit einer radialen Verlaufsfüllung nicht mit dem Original übereinstimmte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1105">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="b48ee-1106">Wir haben ein Problem behoben, bei dem der Platzhaltertext im Bearbeitungsfeld „Suchen“ überlaufen würde, wenn die Größe des Anwendungsfensters auf eine kleine Dimension geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1106">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

- <span data-ttu-id="b48ee-1107">Ein Problem wurde behoben, bei dem sich das Überarbeitungsfeld unerwartet öffnet, wenn ein Kommentar hinzugefügt wurde, um eine Änderung zu verfolgen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1107">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>

- <span data-ttu-id="b48ee-1108">Wir haben ein Problem behoben, bei dem der Befehl „Editor“ deaktiviert wurde, als sich der Fokus in einem Kommentartextfeld befand.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1108">We fixed an issue where the Editor command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="b48ee-1109">Wir haben ein Problem behoben, bei dem der Befehl „Markup anzeigen“ deaktiviert wurde, als sich der Fokus in einem Kommentartextfeld befand.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1109">We fixed an issue where the Show Markup command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="b48ee-1110">Ein Problem wurde behoben, bei dem die Schaltfläche „Neuer Kommentar“ nach dem Löschen des letzten Kommentars deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1110">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

- <span data-ttu-id="b48ee-1111">Wir haben ein Problem behoben, bei dem die Option „Bestimmte Personen“ zum Nachverfolgen von Änderungen deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1111">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>

- <span data-ttu-id="b48ee-1112">Ein Problem wurde behoben, bei dem Links zu Dokumenten nicht über die Dropdown-Liste Einfügen -> Link in das Kommentarfeld eingefügt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1112">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>

- <span data-ttu-id="b48ee-1113">Wir haben ein gelegentliches Aufhängen beim Öffnen von HTML-Dateien behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1113">We fixed an occasional hang while opening HTML files.</span></span>

- <span data-ttu-id="b48ee-1114">Wir haben ein Problem in benutzerdefiniertem XML behoben, bei dem der Status der Kommentare beim Öffnen des Dokuments verloren geht.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1114">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

- <span data-ttu-id="b48ee-1115">Ein Problem wurde behoben, bei dem die Anzahl der Hyperlinks in der VBA-Hyperlinks-Sammlung nach dem Hinzufügen eines Bildes, das einen Hyperlink enthält, nicht korrekt iteriert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1115">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

- <span data-ttu-id="b48ee-1116">Bei dem alten, nicht webdienstbasierten Bereich Freigeben könnte das Schließen des Dokuments bei geöffnetem Bereich Freigeben zu einem Absturz führen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1116">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="b48ee-1117">Dieses Problem wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1117">This is now fixed.</span></span>

- <span data-ttu-id="b48ee-1118">Wir haben ein Problem behoben, durch das, nach dem der User ein neues App-Fenster über die Taskleiste geöffnet und ein neues leeres Dokuments erstellt hatte, zusätzliche Dateien erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1118">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>

- <span data-ttu-id="b48ee-1119">Wir haben ein Problem behoben, bei dem ein Benutzer, der ein Dokument bearbeitete, aber zwischenzeitlich die Berechtigungen verloren hatte, wir den Benutzer nicht darüber informierten, dass er sich erneut authentifizieren musste.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1119">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2007-august-05"></a><span data-ttu-id="b48ee-1121">Version 2007: 5. August</span><span class="sxs-lookup"><span data-stu-id="b48ee-1121">Version 2007: August 05</span></span>
<span data-ttu-id="b48ee-1122">*Version 2007 (Build 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1122">*Version 2007 (Build 13029.20344)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)



[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1126">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1126">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-1127">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1127">Outlook</span></span>

- <span data-ttu-id="b48ee-1128">Ein Problem wurde behoben, das dazu führte, dass Outlook keine Suchvorschläge abrufen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1128">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="b48ee-1129">Ein Problem wurde behoben, das gelegentlich zu einem Absturz führte, wenn Benutzer Persona-Informationen abriefen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1129">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="b48ee-1130">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-1130">Project</span></span>

- <span data-ttu-id="b48ee-1131">Ein Problem wurde behoben, bei dem ein Projekt, das in einen ungültigen Zustand geraten war, nicht geöffnet werden konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1131">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2007-july-29"></a><span data-ttu-id="b48ee-1133">Version 2007: 29. Juli</span><span class="sxs-lookup"><span data-stu-id="b48ee-1133">Version 2007: July 29</span></span>
<span data-ttu-id="b48ee-1134">*Version 2007 (Build 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1134">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1136">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1136">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1137">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1137">Excel</span></span>

- <span data-ttu-id="b48ee-1138">**Abrufen von Organisationsdaten aus Power BI mithilfe von Datentypen:** Excel-Datentypen aus Power BI werden nun für Insider in Organisationen mit Office 365 E5/A5 oder Microsoft 365 E5/A5 bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1138">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="b48ee-1139">Benötigte Informationen abrufen und deren einfache Aktualisierung ist für viele tägliche Abläufe von entscheidender Bedeutung.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1139">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="b48ee-1140">Sie erhalten Zugriff auf Ihre Unternehmens-oder Organisationsinformationen aus Power BI als Datentyp in Excel. Dadurch wird die Möglichkeit, verknüpfte Informationen in Tabellen einzugben, erweitert. </span><span class="sxs-lookup"><span data-stu-id="b48ee-1140">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="b48ee-1141">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-1141">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="b48ee-1142">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="b48ee-1142">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1143">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1143">Outlook</span></span>

- <span data-ttu-id="b48ee-1144">**Auswählen, wo gesucht werden soll:** Das neue Dropdownmenü für den Suchbereich ermöglicht es Ihnen, Ihre Suche einfacher zu ändern und zwischen dem aktuellen Ordner und dem aktuellen Postfach zu wechseln.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1144">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="b48ee-1145">Vielen Dank an alle in "Demnächst verfügbar", die uns ihr Feedback zu der neuen Search-at-Top-Erfahrung gesendet haben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1145">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="b48ee-1146">Das vorliegende Design und Update sind aus diesem Feedback entstanden!</span><span class="sxs-lookup"><span data-stu-id="b48ee-1146">This design and update came out of that feedback!</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-1147">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1147">Word</span></span>

- <span data-ttu-id="b48ee-1148">**Bessere Zusammenarbeit mit modernen Kommentaren:** Für eine bessere Zusammenarbeit fügen Sie Kommentare zu Objekten hinzu, @erwähnen Sie Kollegen, und lösen Sie Kommentarthreads auf.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1148">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="b48ee-1149">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-1149">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1152">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1152">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-1153">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1153">Outlook</span></span>

- <span data-ttu-id="b48ee-1154">Ein Problem wurde behoben, das zu einem Absturz führte, wenn Benutzer von CLP die Absenderadresse in einer Antwort von geschütztem in ungeschützten Kontext wechselten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1154">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="b48ee-1155">Ein Problem wurde behoben, das dazu führte, dass die Seite des Terminplanungs-Assistenten nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1155">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="b48ee-1156">Ein Problem wurde behoben, das zu Formatierungsproblemen in Benachrichtigungen über einen Sicherheitsvorfälle führte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1156">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2007-july-27"></a><span data-ttu-id="b48ee-1158">Version 2007: 27. Juli</span><span class="sxs-lookup"><span data-stu-id="b48ee-1158">Version 2007: July 27</span></span>
<span data-ttu-id="b48ee-1159">*Version 2007 (Build 13029.20292)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1159">*Version 2007 (Build 13029.20292)*</span></span>
* <span data-ttu-id="b48ee-1160">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1160">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-20"></a><span data-ttu-id="b48ee-1161">Version 2007: 20. Juli</span><span class="sxs-lookup"><span data-stu-id="b48ee-1161">Version 2007: July 20</span></span>
<span data-ttu-id="b48ee-1162">*Version 2007 (Build 13029.20236)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1162">*Version 2007 (Build 13029.20236)*</span></span>
* <span data-ttu-id="b48ee-1163">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1163">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-15"></a><span data-ttu-id="b48ee-1164">Version 2007: 15. Juli</span><span class="sxs-lookup"><span data-stu-id="b48ee-1164">Version 2007: July 15</span></span>
<span data-ttu-id="b48ee-1165">*Version 2007 (Build 13029.20200)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1165">*Version 2007 (Build 13029.20200)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1167">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1167">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1168">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1168">Excel</span></span>

- <span data-ttu-id="b48ee-1169">**Erstellen Sie ansprechende Visio-Diagramme in Excel:** Erstellen Sie ein Flussdiagramm oder ein Organigramm durch Einfügen von Daten in ein Arbeitsblatt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1169">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="b48ee-1170">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-1170">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1173">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1173">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b48ee-1174">Zugriff</span><span class="sxs-lookup"><span data-stu-id="b48ee-1174">Access</span></span>

- <span data-ttu-id="b48ee-1175">Ein Problem wurde behoben, bei dem der Tabellenverknüpfungs-Manager einen Primärschlüssel anforderte, wenn eine verknüpfte SQL-Tabelle aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1175">We fixed an issue where the linked table manager would prompt a primary key if a linked SQL table was refreshed.</span></span>

- <span data-ttu-id="b48ee-1176">Es wurde ein Problem behoben, das dazu führte, dass Abfragen im Abfrage-Editor aus dem sichtbaren Bereich verschwanden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1176">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>

- <span data-ttu-id="b48ee-1177">Ein Problem wurde behoben, bei dem die Abfrageausführung ungefähr doppelt so lange dauerte als erwartet.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1177">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="b48ee-1178">Es wurde ein Problem behoben, das dazu führte, dass Microsoft Access eine Identitätsspalte in einer verknüpften SQL Server-Tabelle nicht identifizierte, was dazu führen konnte, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1178">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="b48ee-1179">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1179">Excel</span></span>

- <span data-ttu-id="b48ee-1180">Ein Problem wurde behoben, bei dem URLs, die nicht auf HTTP oder HTTPS basierten, nicht in der Liste "Zuletzt verwendet" angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1180">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

- <span data-ttu-id="b48ee-1181">Ein Problem wurde behoben, bei dem beim Laden einer Arbeitsmappe mit mehreren Blättern in der Seitenumbruchvorschau ein Fehler oder eine Unterbrechung auftreten kann.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1181">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="b48ee-1182">Es wurde ein Problem behoben, bei dem Datenmodelltabellen, die in bestimmten Excel-Versionen erstellt wurden, in der "Tabellenvorschau" nicht angezeigt wurden, selbst wenn die mit der Tabelle verknüpfte Abfrage nicht bearbeitet wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1182">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>

- <span data-ttu-id="b48ee-1183">Relativ/Absolut ignorieren"-Bezügen im Dialogfeld "Namen definieren \ Namen anwenden" führte dazu, dass Formeln nicht funktionierten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1183">Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>

- <span data-ttu-id="b48ee-1184">Es wurde ein Problem behoben, bei dem CustomUI XML für eine benutzerdefinierte Menüband-Registerkarte beim Speichern einer Arbeitsmappe in SharePoint/OneDrive entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1184">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="b48ee-1185">Ein Problem wurde behoben, bei dem Arbeitsmappen schreibgeschützt waren, wenn für die Datei nur die Empfehlung des Schreibschutzes vorlag.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1185">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

- <span data-ttu-id="b48ee-1186">Ein Problem wurde behoben, bei dem beim Laden einer Arbeitsmappe mit mehreren Blättern in der Seitenumbruchvorschau ein Fehler oder eine Unterbrechung auftreten kann.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1186">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="b48ee-1187">Ein Problem wurde behoben, bei dem die wichtigsten Netzlinien von Netzdiagrammen nicht ordnungsgemäß formatiert werden konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1187">We fixed an issue where the major gridlines of radar charts could not be formatted correctly.</span></span>


- <span data-ttu-id="b48ee-1188">Es wurde ein Problem behoben, bei dem durch das Löschen eines erweiterten Datenfilters die Tabellenformatierung verloren gehen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1188">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>


- <span data-ttu-id="b48ee-1189">Ein Problem wurde behoben, bei dem in der Dokumentbeschriftung der vollständige Pfad eines eingebetteten PDF-Dokuments und nicht nur der Dateiname angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1189">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>


- <span data-ttu-id="b48ee-1190">Ein Problem wurde behoben, bei dem es nach dem Deaktivieren des Wolfram Cloud-Connectors und dem anschließenden Speichern und erneuten Öffnen einer Excel-Arbeitsmappe zu einem Absturz kommen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1190">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>


- <span data-ttu-id="b48ee-1191">Es wurde ein Problem behoben, durch das das Starten von Excel mit aktiviertem Solver-Add-in zu einem Absturz führte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1191">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>


### <a name="outlook"></a><span data-ttu-id="b48ee-1192">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1192">Outlook</span></span>

- <span data-ttu-id="b48ee-1193">Es wurde ein Problem behoben, bei dem Outlook nicht mehr reagierte, wenn mehr als 130 Empfänger in der Zeile "An" vorhanden waren; darüber hinaus wurde auch die Leistung beim Renderns des Texts verbessert.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1193">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>


- <span data-ttu-id="b48ee-1194">Es wurde ein Problem behoben, bei dem das IME-Fenster (Eingabemethoden-Editor) den zugrunde liegenden Text, der über den IME eingegeben wird, überlappte, wenn mehrere Monitore mit unterschiedlichen Auflösungen verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1194">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>


- <span data-ttu-id="b48ee-1195">Es wurde ein Problem in der "Aufgabenleiste" behoben, bei dem für Ereignisse, die mehr als zwei Tage dauerten, für alle nachfolgenden Tage dieselbe Endzeit angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1195">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>


- <span data-ttu-id="b48ee-1196">Behebt ein Problem, durch das Benutzer das Erstellungsdatum der Anlagen sehen konnten, die Sie per Drag & Drop in Ihr Dateisystem kopiert haben, wobei es auf den 1. Januar 4501 festgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1196">Addresses an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="b48ee-1197">Ein Problem wurde behoben, bei dem Benutzer nicht in der Lage waren, "Senden als" oder "Senden im Auftrag von" einer Verteilerliste zu senden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1197">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>


- <span data-ttu-id="b48ee-1198">Behebt ein Problem, durch das Stellvertretungen beim Bearbeiten eines vorhandenen Kalendertermins im Kalender eines Managers eine Fehlermeldung erhalten haben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1198">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="b48ee-1199">Es wurde ein Problem behoben, durch das Benutzern beim Schließen eines vorher gespeicherten Termins der folgende Fehler angezeigt wurde: "Das Element kann nicht gespeichert werden, da es von einem anderen Benutzer oder in einem anderen Fenster geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1199">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="b48ee-1200">Möchten Sie eine Kopie im Standardordner für das Element erstellen?"</span><span class="sxs-lookup"><span data-stu-id="b48ee-1200">Do you want to make a copy in the default folder for the item?"</span></span>


- <span data-ttu-id="b48ee-1201">Behebt ein Problem, bei dem die Option "Weiterleitung zulassen" in den "Antwortoptionen" für Kalenderbesprechungen nicht angezeigt wurde, wenn die Option für das Herunterladen freigegebener Ordner NICHT aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1201">Addresses an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="b48ee-1202">Behebt ein Problem, das dazu führte, dass Benutzer OneDrive-Anlagen von außerhalb ihres Mandanten nicht auf ihrem lokalen Computer speichern konnten, wenn sie im Dialogfeld "Sicherheit" die Option "Speichern" wählten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1202">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="b48ee-1203">Es wurde ein Problem behoben, das bewirkt hat, dass die Nachrichtenliste von Outlook-Benutzern, nachdem diese freigegebene Kalender verwendet hatten, einige Minuten lang nicht mehr aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1203">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>


- <span data-ttu-id="b48ee-1204">Wir haben ein Problem behoben, das verhinderte, dass in Kalendererinnerungen genaue Uhrzeiten für Besprechungen in weniger als einer Woche angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1204">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span> 


- <span data-ttu-id="b48ee-1205">Es wurde ein Problem behoben, das dazu führte, dass wenn ein Bild inline in eine Nachricht eingefügt wurde und die Nachricht dann als Entwurf gespeichert wurde, dies zu einer Größenänderung bei dem Bild führte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1205">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>


- <span data-ttu-id="b48ee-1206">Es wurde ein Problem behoben, das bewirkt hatte, dass der Text einer NDR-Nachricht nach der Bearbeitung des Betreffs von Unicode in ASCII geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1206">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>


- <span data-ttu-id="b48ee-1207">Ein Problem wurde behoben, durch das die Datumsangaben im Minikalender für Benutzer in Japan nicht fett formatiert angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1207">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b48ee-1208">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1208">PowerPoint</span></span>

- <span data-ttu-id="b48ee-1209">Es wurde ein Problem behoben, bei dem der Farbindikator für Abwesenheiten eines Benutzers während einer aktiven Sitzung zur gemeinsamen Dokumenterstellung nicht im Katalog für die gemeinsame Dokumenterstellung aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1209">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>


- <span data-ttu-id="b48ee-1210">Es wurde ein Problem behoben, durch das beim Einfügen von HTML in einen Textbereich auf einer Folie dieser stattdessen in ein Textfeld eingefügt wurde, das am oberen Rand der Folie erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1210">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>


- <span data-ttu-id="b48ee-1211">Ein Problem wurde behoben, bei dem die Auswahl aller Folien in der Referentenansicht, das anschließende Verlassen der Referentenansicht mittels Alt+Tab und die Rückkehr zur Bildschirmpräsentation und das Klicken auf "Präsentation beenden" zu einem Ausnahmefehler führte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1211">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>


### <a name="project"></a><span data-ttu-id="b48ee-1212">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-1212">Project</span></span>

- <span data-ttu-id="b48ee-1213">Es wurde ein Problem behoben, bei dem man kein PDF/XPS aus Project in einer SharePoint-Dokumentbibliothek speichern konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1213">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="b48ee-1214">Ein Problem wurde behoben, bei dem Projekte aus Project Web App nicht im Project-Desktop Client geöffnet werden konnten, wenn die URL in .com endete.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1214">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="b48ee-1215">Ein Problem wurde behoben, bei dem Project beim Öffnen bestimmter XML-Dateien abstürzte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1215">We fixed an issue where Project may crash when opening certain XML files.</span></span>


- <span data-ttu-id="b48ee-1216">Es wurde ein Problem behoben, bei dem Projekte aus Project Web App im Project-Desktopclient nicht geöffnet werden konnten, wenn die URL in ".com" endete.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1216">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>


- <span data-ttu-id="b48ee-1217">Es wurde ein Problem behoben, das bewirkt, dass nicht alle Abhängigkeiten korrekt kopiert werden, wenn ein Vorgang mit mehreren Abhängigkeiten eingefügt wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1217">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="b48ee-1218">Ein Problem wurde behoben, bei dem die im Dialogfeld "Ressourcen zuordnen" ausgewählte Aufgabe nicht mit der in der Ansicht "Task Board" ausgewählten Aufgabe identisch ist.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1218">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="b48ee-1219">Es wurde ein Problem behoben, bei dem das Ereignis "ProjectBeforeTaskChange" nicht ausgelöst wurde, wenn eine Änderung am Projektzusammenfassungsvorgang – entweder am Projektstart/Aufgabenfeld – vorgenommen wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1219">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>


- <span data-ttu-id="b48ee-1220">Es wurde ein Problem behoben, dass dazu führte, dass wenn Vorgänge mit fester Dauer zu 100 % abgeschlossen waren, das Ist-Ende aber nicht angegeben war, bei "Vorgang zu % abgeschlossen" weniger als 100 % angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1220">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

- <span data-ttu-id="b48ee-1221">Es wurde ein Problem behoben, bei dem bei einem Basisplan-Reset oder -Update u. U. Zeitphasen-Kosten-/Arbeitsbudgetressourcen geändert wurden und die Baseline falsche Budgetwerte wiedergab.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1221">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>


- <span data-ttu-id="b48ee-1222">Es wurde ein Problem behoben, bei dem Project Planner-Links in Government Community Cloud-Umgebungen deaktiviert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1222">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>


- <span data-ttu-id="b48ee-1223">Ein Problem wurde behoben, bei dem keine Projektdatei aus einer SharePoint-Dokumentbibliothek geöffnet werden konnte, wenn sich die Bibliothek im modernen Modus befand.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1223">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>


### <a name="word"></a><span data-ttu-id="b48ee-1224">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1224">Word</span></span>

- <span data-ttu-id="b48ee-1225">Ein Problem wurde behoben, bei dem die Möglichkeit, die Formatierung im Kommentarbereich über die Schaltfläche "Formatierung löschen" im Office-Menüband zu deaktivieren, nicht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1225">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>


- <span data-ttu-id="b48ee-1226">Es wurde ein Problem behoben, durch das in eine skalierbare Vektorgrafik (Scalable Vector Graphic, SVG) eingefügter Text nach deren Einfügen in eine Word-, Excel- oder PowerPoint-Datei, dem Speichern und Schließen der Datei und erneutem Öffnen der Datei unlesbar war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1226">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>


- <span data-ttu-id="b48ee-1227">Ein Problem wurde behoben, bei dem das Ändern der Größe einer Tabelle bei nicht angezeigtem Lineal dazu führte, dass andere Anwendungen, die im Hintergrund ausgeführt wurden, zu blinken begannen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1227">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>


- <span data-ttu-id="b48ee-1228">Es wurde ein Problem behoben, bei dem im Modus "Gemeinsame Dokumenterstellung" Antworten auf Kommentare manchmal nicht im Kommentarbereich angezeigt wurden, sondern im Bereich "Überprüfungen".</span><span class="sxs-lookup"><span data-stu-id="b48ee-1228">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>


- <span data-ttu-id="b48ee-1229">Es wurde ein Problem in der gemeinsamen Dokumenterstellung behoben, bei dem wenn beim Zusammenführen ein Konflikt vorlag und der Benutzer bereits Änderungen verworfen hatte, die Option zum Speichern oder Verwerfen von Änderungen nicht mehr angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1229">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>


- <span data-ttu-id="b48ee-1230">Ein Problem wurde behoben, bei dem die Farbe von HTML-Links nicht ordnungsgemäß gerendert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1230">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>


- <span data-ttu-id="b48ee-1231">Es wurde ein Problem behoben, bei dem wenn in Word eine Liste mit mehr als 50 häufig geöffneten Dokumenten vorlag, nach dem Speichern und Öffnen eines Dokuments ein Versionsverlauf angezeigt wurde, selbst wenn keine Änderungen an diesem Dokument vorgenommen wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1231">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>


- <span data-ttu-id="b48ee-1232">Es wurde ein Problem mit der automatischen Speicherung bei der gemeinsamen Dokumenterstellung behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1232">We fixed in issue with autosave during coauthoring.</span></span>


- <span data-ttu-id="b48ee-1233">Es wurde ein Problem behoben, das beim Speichern einer Datei, die ein Makro enthielt, unter einem neuen Namen dazu führte, dass sie mit einer .docx-Erweiterung und dem Dateinamen "WRO0004.docx" gespeichert wurde, und zwar unabhängig davon, was der Benutzer eingegeben hatte, wodurch das Dokument unbrauchbar wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1233">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b48ee-1234">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-1234">Office Suite</span></span>

- <span data-ttu-id="b48ee-1235">Ein Timing-Problem konnte beim Schließen von Office-Dateien zu einem Absturz führen</span><span class="sxs-lookup"><span data-stu-id="b48ee-1235">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="b48ee-1236">Der Fix für dieses Problem bestand darin, sicherzustellen, dass der Dienst hinzugefügte Produkte ordnungsgemäß berechnet.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1236">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="b48ee-1237">Wir haben die neu hinzugefügten Produkte herausgefiltert (dabei wurde sichergestellt, dass sie auch in der neuen Konfiguration vorhanden sind) und sie am Ende der vorhandenen Produkt-Release-IDs hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1237">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-july-09"></a><span data-ttu-id="b48ee-1239">Version 2006: 09. Juli</span><span class="sxs-lookup"><span data-stu-id="b48ee-1239">Version 2006: July 09</span></span>
<span data-ttu-id="b48ee-1240">*Version 2006 (Build 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1240">*Version 2006 (Build 13001.20384)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1242">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1242">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1243">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1243">Excel</span></span>

- <span data-ttu-id="b48ee-1244">**Eine PDF-Verbindung herstellen:** Herstellen einer Verbindung zu, Importieren und Aktualisieren von Daten aus einer PDF-Datei.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1244">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="b48ee-1245">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-1245">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="b48ee-1246">**Erstellen von Variablen zur Verwendung in Formeln:** Verbessern Sie Leistung, Lesbarkeit und Zusammensetzbarkeit mit der LET-Funktion.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1246">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="b48ee-1247">Mit dieser Funktion können Sie benannte Variablen in neuen oder bereits vorhandenen Formeln erstellen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1247">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="b48ee-1248">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-1248">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="b48ee-1249">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/).</span><span class="sxs-lookup"><span data-stu-id="b48ee-1249">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="b48ee-1250">**Tastenkombinationen in Excel:** Aktualisierte Tastenkombinationen für Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1250">**Keyboard shortcuts in Excel:** Updated keyboard shortcuts for Excel</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1251">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1251">Outlook</span></span>

- <span data-ttu-id="b48ee-1252">**Erstellen von Umfragen in Outlook mit Quick Poll**: Einfaches Erstellen einer Umfrage, Sammeln von Stimmen und Anzeigen der Ergebnisse in einer E-Mail [Weitere Informationen](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="b48ee-1252">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="b48ee-1253">**Bewahren Sie die Klangtreue Ihrer Bilder, wenn Sie diese als Teil einer E-Mail versenden:** Eine neue Outlook-Einstellung ist verfügbar, um die Bildkomprimierung zu begrenzen, wenn Sie Bilder als Teil des E-Mail-Inhalts versenden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1253">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1256">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1256">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b48ee-1257">Access</span><span class="sxs-lookup"><span data-stu-id="b48ee-1257">Access</span></span>

- <span data-ttu-id="b48ee-1258">Dieses Problem wurde behoben, und Sie sollten erwarten, dass Sie verknüpfte SQL-Tabellen, die ein Identitätsfeld (z. B. Autonummer) enthalten, erfolgreich in Access einfügen können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1258">This issue is resolved, and you should expect to be able to successfully insert linked SQL tables that include an identity (e.g. autonumber) field into Access.</span></span>

### <a name="excel"></a><span data-ttu-id="b48ee-1259">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1259">Excel</span></span>

- <span data-ttu-id="b48ee-1260">Ein Absturz wurde behoben, der beim Versuch, eine Datenverbindung herzustellen, auftreten konnte, wenn Sie sich von Ihrem Konto abgemeldet haben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1260">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1261">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1261">Outlook</span></span>

- <span data-ttu-id="b48ee-1262">Ein Problem wurde behoben, das dazu führte, dass Benutzer OneDrive-Anlagen von außerhalb ihres Mandanten nicht auf ihrem lokalen Computer speichern konnten, wenn sie im Dialogfeld "Sicherheit" die Option "Speichern" wählten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1262">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b48ee-1263">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-1263">Office Suite</span></span>

- <span data-ttu-id="b48ee-1264">Ein neuer Sturz von AppV51 wurde zurückportiert, um eine Regression im vorherigen AppV51 zu beheben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1264">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="b48ee-1265">Der Office-Host stürzte in Fenstern ab, wenn ein Add-In aktiviert wird, während der Registrierungswert TabProcGrowth vom Typ REG_SZ und mit dem Wert "0" ist.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1265">he office host was crashing in windows, when an add-in is being activated while the registry TabProcGrowth value is REG_SZ type and with value "0".</span></span>  <span data-ttu-id="b48ee-1266">Der Registrierungswert TabProcGrowth kann unter einem von 4 Pfaden stehen: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1266">That registry TabProcGrowth value can be under any one of 4 paths: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-june-25"></a><span data-ttu-id="b48ee-1268">Version 2006: 25. Juni</span><span class="sxs-lookup"><span data-stu-id="b48ee-1268">Version 2006: June 25</span></span>
<span data-ttu-id="b48ee-1269">*Version 2006 (Build 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1269">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1271">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1271">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="b48ee-1272">Visio</span><span class="sxs-lookup"><span data-stu-id="b48ee-1272">Visio</span></span>

- <span data-ttu-id="b48ee-1273">**Erstellen Sie ansprechende Visio-Diagramme in Excel:** Erstellen Sie ein Flussdiagramm oder ein Organigramm auf der Grundlage von Daten in einem Arbeitsblatt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1273">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart based on data in a worksheet.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1276">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1276">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b48ee-1277">Access</span><span class="sxs-lookup"><span data-stu-id="b48ee-1277">Access</span></span>

- <span data-ttu-id="b48ee-1278">Dieses Problem ist jetzt behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1278">This problem is now resolved.</span></span> <span data-ttu-id="b48ee-1279">Bitte teilen Sie dem Team mit, wenn Sie weitere Probleme mit diesem Prozess haben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1279">Please let the team know if you experience more issues with this process.</span></span>


### <a name="outlook"></a><span data-ttu-id="b48ee-1280">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1280">Outlook</span></span>

- <span data-ttu-id="b48ee-1281"><span style="display:inline !important;">Behebt ein Problem, das dazu führte, dass Benutzer<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">das Erstellungsdatum von&nbsp; Anlagen sahen, die sie per Drag & Drop in ihr Dateisystem kopierten, wobei&nbsp; auf den 1. Januar 4501 gesetzt wurde.</span></span><span class="sxs-lookup"><span data-stu-id="b48ee-1281"><span style="display:inline !important;">Addresses an issue that caused users to see<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">the creation date of&nbsp; attachments that they copied to their file system via drag and drop getting&nbsp; set to January 1, 4501.</span></span></span><br>


- <span data-ttu-id="b48ee-1282"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Behebt ein Problem, das dazu führte, dass Benutzer von Verbesserungen am "Freigegebenen Kalender" Kalenderfehler sahen.</span></span><span class="sxs-lookup"><span data-stu-id="b48ee-1282"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span></span><br>


- <span data-ttu-id="b48ee-1283"><span style="display:inline !important;">Behebt ein Problem, das dazu führte, dass Benutzer ständig von Outlook aufgefordert wurden, das Reparaturtool für den Posteingang auszuführen.</span></span><span class="sxs-lookup"><span data-stu-id="b48ee-1283"><span style="display:inline !important;">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span></span><br>


- <span data-ttu-id="b48ee-1284"><span style="display:inline !important;">Behebt ein Problem, das dazu führte, dass bei der Suche nach einem Feature in "Features vorschlagen" keine Ergebnisse zurückgegeben wurden und der Benutzer keine Möglichkeit hatte, eine neue Idee für Features einzureichen.</span></span><span class="sxs-lookup"><span data-stu-id="b48ee-1284"><span style="display:inline !important;">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span></span><br>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-june-18"></a><span data-ttu-id="b48ee-1286">Version 2006: 18. Juni</span><span class="sxs-lookup"><span data-stu-id="b48ee-1286">Version 2006: June 18</span></span>
<span data-ttu-id="b48ee-1287">*Version 2006 (Build 13001.20198)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1287">*Version 2006 (Build 13001.20198)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1289">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1289">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1290">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1290">Excel</span></span>



- <span data-ttu-id="b48ee-1291">**In angeheftete Ordner speichern:** Durch das Anheften Ihrer Ordner wird das Speichern von Office-Dateien einfacher. Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die verfügbaren Ordner wünschen, wenn eine neue Datei gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1291">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="b48ee-1292">Wir freuen uns, Ihnen eine neue Funktion zur Verfügung stellen zu können: anheften Ihrer Ordner im Dialogfeld "Speichern".</span><span class="sxs-lookup"><span data-stu-id="b48ee-1292">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="b48ee-1293">Mit dieser neuen Funktion können Sie Ihre Word-, Excel- und PowerPoint-Dateien einfacher speichern.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1293">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="b48ee-1294">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="b48ee-1294">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b48ee-1295">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1295">PowerPoint</span></span>

- <span data-ttu-id="b48ee-1296">**In angeheftete Ordner speichern:** Durch das Anheften Ihrer Ordner wird das Speichern von Office-Dateien einfacher. Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die verfügbaren Ordner wünschen, wenn eine neue Datei gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1296">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="b48ee-1297">Wir freuen uns, Ihnen eine neue Funktion zur Verfügung stellen zu können: anheften Ihrer Ordner im Dialogfeld "Speichern".</span><span class="sxs-lookup"><span data-stu-id="b48ee-1297">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="b48ee-1298">Mit dieser neuen Funktion können Sie Ihre Word-, Excel- und PowerPoint-Dateien einfacher speichern.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1298">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="b48ee-1299">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="b48ee-1299">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-1300">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1300">Word</span></span>

- <span data-ttu-id="b48ee-1301">**In angeheftete Ordner speichern:** Durch das Anheften Ihrer Ordner wird das Speichern von Office-Dateien einfacher. Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die verfügbaren Ordner wünschen, wenn eine neue Datei gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1301">**Save to Pinned Folders:** Pin your folders makes saving Office files easierWe received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="b48ee-1302">Wir freuen uns, Ihnen eine neue Funktion zur Verfügung stellen zu können: anheften Ihrer Ordner im Dialogfeld "Speichern".</span><span class="sxs-lookup"><span data-stu-id="b48ee-1302">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="b48ee-1303">Mit dieser neuen Funktion können Sie Ihre Word-, Excel- und PowerPoint-Dateien einfacher speichern.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1303">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="b48ee-1304">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="b48ee-1304">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1307">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1307">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1308">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1308">Excel</span></span>

- <span data-ttu-id="b48ee-1309">Es wurde ein Problem behoben, das dazu führte, dass CustomUI XML für eine benutzerdefinierte Multifunktionsleisten-Registerkarte beim Speichern in SharePoint/OneDrive entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1309">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1310">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1310">Outlook</span></span>

- <span data-ttu-id="b48ee-1311">Es wurde ein Problem behoben, das dazu führte, dass STRG+Klicken nicht mehr funktionierte, wenn die Cloud-Einstellungen aktiviert waren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1311">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

### <a name="project"></a><span data-ttu-id="b48ee-1312">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-1312">Project</span></span>

- <span data-ttu-id="b48ee-1313">Es wurde ein Problem behoben, bei dem eine Aufgabe, die als 100 % abgeschlossen gekennzeichnet ist, fälschlicherweise weniger als 100 % abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1313">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-june-11"></a><span data-ttu-id="b48ee-1315">Version 2006: 11. Juni</span><span class="sxs-lookup"><span data-stu-id="b48ee-1315">Version 2006: June 11</span></span>
<span data-ttu-id="b48ee-1316">*Version 2006 (Build 13001.20144)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1316">*Version 2006 (Build 13001.20144)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1318">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1318">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="b48ee-1319">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1319">PowerPoint</span></span>

- <span data-ttu-id="b48ee-1320">**Verbesserte Stream-Video-Leistung in PowerPoint:** Wir haben die Wiedergabeleistung von Microsoft Stream-Videos verbessert, um die Ladezeit von Videos zu minimieren und eine reibungslose Wiedergabe zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1320">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="b48ee-1321">Verwenden Sie Ihre Unternehmensvideos aus Microsoft Stream, um bessere Präsentationen zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1321">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-1322">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1322">Word</span></span>

- <span data-ttu-id="b48ee-1323">**Beibehalten von Text in Vektoren:** Sie können jetzt den Text in Karten, Diagrammen und anderen SVG-Vektoren beibehalten, wenn Sie diese Objekte in Excel, Word und PowerPoint konvertieren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1323">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1326">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1326">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1327">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1327">Excel</span></span>

- <span data-ttu-id="b48ee-1328">Es wurde ein Problem behoben, bei dem Excel gelegentlich beim Einschalten von OneDrive heruntergefahren wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1328">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>

- <span data-ttu-id="b48ee-1329">Es wurde ein Problem behoben, bei dem benutzerdefinierte Werte auf der Diagrammachse nicht korrekt angewendet wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1329">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>

- <span data-ttu-id="b48ee-1330">Es wurde ein Problem behoben, bei dem Arbeitsblätter, die mehrere Formeln mit definierten Namen enthielten, zu längeren Zeiten beim Speichern von Dateien geführt haben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1330">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="b48ee-1331">Es wurde ein Problem behoben, das dazu führte, dass Druckernamen in der Liste der verfügbaren Drucker dupliziert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1331">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span>

- <span data-ttu-id="b48ee-1332">Es wurde ein Problem behoben, das zur Verbesserung der Leistung führte, wenn zusammengeführte Spalten gelöscht wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1332">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>

- <span data-ttu-id="b48ee-1333">Es wurde ein Problem behoben, bei dem die Fehlermeldung "Diese Arbeitsmappe wird derzeit von einer anderen Arbeitsmappe referenziert und kann nicht geschlossen werden" erschien, weil Add-Ins in alphabetischer Reihenfolge und nicht in einer vom Benutzer festgelegten Reihenfolge geladen wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1333">We fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="b48ee-1334">Es wurde ein Problem behoben, bei dem der Speicher bei der Verwaltung von Schriftarten zwischen Excel und einigen Hilfstechnologie-Anwendungen von Drittanbietern beschädigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1334">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>

- <span data-ttu-id="b48ee-1335">Es wurde ein Problem behoben, bei dem das Klicken auf einer mit einem Lesezeichen versehenen Verknüpfung innerhalb derselben Arbeitsmappe dazu führte, dass die Arbeitsmappe ausgeblendet wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1335">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="b48ee-1336">Es wurde ein Problem behoben, bei dem einige kopierte und eingefügte Diagrammverknüpfungen zugeordnete Laufwerksadressen anstelle von Universaladressen verwendeten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1336">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="b48ee-1337">Es wurde ein Problem behoben, bei dem Excel nicht mehr reagierte, nachdem STRG+UMSCHALT+Pfeiltasten zum Scrollen verwendet wurden, wenn das Excel-Fenster von Teams gemeinsam genutzt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1337">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

- <span data-ttu-id="b48ee-1338">Es wurde ein Problem behoben, bei dem Excel abstürzte, wenn Add-Ins auf Arbeitsblättern, die Shapes mit „noSelect“-Sperren enthalten, nach „Hostelemente“ fragen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1338">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="b48ee-1339">Es wurde ein Problem behoben, bei dem Excel abstürzen kann, wenn versucht wird, PivotTables in ein Diagrammblatt einzufügen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1339">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1340">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1340">Outlook</span></span>

- <span data-ttu-id="b48ee-1341">Es wurde ein Problem behoben, bei dem das IME-Fenster (Eingabemethoden-Editor) den zugrunde liegenden Text, der über den IME eingegeben wird, überlappte, wenn mehrere Monitore mit unterschiedlichen Auflösungen verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1341">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="b48ee-1342">Es wurde ein Problem behoben, bei dem die Anzeige einer Vorlage beim Verfassen einer neuen E-Mail-Nachricht zu einem Absturz führen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1342">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>

- <span data-ttu-id="b48ee-1343">Es wurde ein Problem behoben, bei dem Benutzer nach der Outlook-Version 1911 nicht in der Lage waren, öffentliche Ordner von Exchange 2010 zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1343">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>

- <span data-ttu-id="b48ee-1344">Es wurde ein Problem behoben, bei dem die Schaltfläche "Kategorisieren" für Gruppenkalender im Office-Menüband deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1344">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="b48ee-1345">Es wurde ein Problem behoben, bei dem Outlook die Datenschutzrichtlinie nicht aktiviert hat, um Tipps für Benutzer zu geben, die für den Dienst bezahlt haben und M365 Business Plus-Pläne nutzen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1345">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="b48ee-1346">Ein Problem wurde behoben, das dazu geführt hat, dass Outlook bei einigen Windows-Versionen abstürzt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1346">Addressed an issue that caused Outlook to crash on some Windows builds.</span></span>

- <span data-ttu-id="b48ee-1347">Es wurde ein Problem behoben, bei dem Benutzer nicht in der Lage waren, einen Kalender für einen Gastbenutzer freizugeben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1347">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

- <span data-ttu-id="b48ee-1348">Es wurde ein Problem behoben, bei dem Benutzer Kalendereinträge, welche die Mitternachtsschwelle überstiegen, als Ganztagesereignisse sahen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1348">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>

- <span data-ttu-id="b48ee-1349">Es wurde ein Problem behoben, das dazu führte, dass die Dropdown-Liste "Online-Archiv" in den Ordnereigenschaften für Benutzer mit hohem DPI-Wert nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1349">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>

- <span data-ttu-id="b48ee-1350">Es wurde ein Problem behoben, bei dem das Ereignis "Folder.BeforeItemMove" nicht korrekt ausgelöst wurde, wenn ein Benutzer Elemente zwischen Ordnern verschoben hat.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1350">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>

- <span data-ttu-id="b48ee-1351">Es wurde ein Problem behoben, bei dem Outlook abstürzte, wenn zwei Add-Ins eine Schaltfläche zur gleichen Gruppe im Menüband hinzufügten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1351">We fixed an issue where Outlook crashed when two add-ins added a button to the same group in the ribbon.</span></span>

- <span data-ttu-id="b48ee-1352">Es wurde ein Problem behoben, das zu einem Absturz in Outlook führte, wenn Benutzer mit Verknüpfungen in E-Mails im Format "Nur Text" arbeiteten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1352">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>

- <span data-ttu-id="b48ee-1353">Es wurde ein Problem behoben, das dazu führte, dass Outlook lange Dateinamen, die mit RFC2231 kodiert sind, nicht analysieren konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1353">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>

- <span data-ttu-id="b48ee-1354">Es wurde ein Problem behoben, das bei Outlook-Benutzern bei der Verwendung von Sprachausgaben zu zeitweiligen Aussetzern führte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1354">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

- <span data-ttu-id="b48ee-1355">Es wurde ein Problem behoben, das bei Benutzern mit widersprüchlichen Kontakten zu Abstürzen in Outlook führen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1355">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b48ee-1356">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1356">PowerPoint</span></span>

- <span data-ttu-id="b48ee-1357">Es wurde ein Problem beim Öffnen von Server-konfigurierten Dateien mit formularbasierter Authentifizierung behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1357">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>

- <span data-ttu-id="b48ee-1358">Es wurde ein Problem behoben, bei dem PowerPoint-Dateien mit eingebetteten Diagrammen/Arbeitsmappen zu Fehlern beim Speichern der Datei führen konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1358">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>

- <span data-ttu-id="b48ee-1359">Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1359">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="b48ee-1360">Es wurde ein Problem behoben, bei dem die Folien nach dem Zoomen mit dem Mausrad nicht zentriert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1360">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

- <span data-ttu-id="b48ee-1361">Ein Problem wurde behoben, bei dem Tastenkombinationen und die Rechtschreibprüfung bei Verwendung einer Schweizer Englisch-Tastatur (QWERTZ) nicht erwartungsgemäß funktionierten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1361">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

- <span data-ttu-id="b48ee-1362">Es wurde ein Problem behoben, bei dem ein Bereich "Kommentar", der vom Benutzer geschlossen wurde, automatisch wieder geöffnet wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1362">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>

- <span data-ttu-id="b48ee-1363">Es wurde ein Problem behoben, bei dem der Folieneditor von einer Folie die nächste überlappte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1363">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="b48ee-1364">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-1364">Project</span></span>

- <span data-ttu-id="b48ee-1365">Es wurde ein Problem behoben, bei dem das Ereignis "ProjectBeforeTaskChange" nicht ausgelöst wurde, wenn eine Änderung am Projektzusammenfassungsvorgang – entweder am Projektstart/Aufgabenfeld – vorgenommen wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1365">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="b48ee-1366">Es wurde ein Problem behoben, bei dem eine Aufgabe, die als 100 % abgeschlossen gekennzeichnet ist, fälschlicherweise weniger als 100 % abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1366">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="b48ee-1367">Es wurde ein Problem behoben, bei dem "Project" nach dem Klicken auf "Optionen" abstürzte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1367">We fixed an issue where Project would crash after clicking on Options.</span></span>

- <span data-ttu-id="b48ee-1368">Es wurde ein Problem behoben, das verhinderte, dass verwaiste Aufgaben gelöscht oder neu zugewiesen werden konnten, nachdem ihr übergeordneter Plan gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1368">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="visio"></a><span data-ttu-id="b48ee-1369">Visio</span><span class="sxs-lookup"><span data-stu-id="b48ee-1369">Visio</span></span>

- <span data-ttu-id="b48ee-1370">Es gab eine Regression im abhängigen Code, die behoben wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1370">There was regression in dependent code which has been fixed.</span></span> <span data-ttu-id="b48ee-1371">Jetzt werden die Bilder in Visio-Diensten, die auf SharePoint Onprem ausgeführt werden, gerendert.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1371">Now, the images are getting rendered in Visio services running on SharePoint Onprem.</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-1372">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1372">Word</span></span>

- <span data-ttu-id="b48ee-1373">Es wurde ein Problem behoben, bei dem die Zeitstempel in den Bereichen "Kommentar" nicht auf der Systemgebietszeit basierten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1373">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>

- <span data-ttu-id="b48ee-1374">Es wurde ein Problem beim Öffnen von Word-Dokumenten aus der benutzerdefinierten Dokumentbereitstellung (aspx) behoben, wenn die URL eine Abfragekomponente enthält.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1374">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="b48ee-1375">Es wurde ein Problem behoben, bei dem das Kopieren und Einfügen von Text in einem Kommentarbereich nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1375">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>

- <span data-ttu-id="b48ee-1376">Es wurde ein Problem behoben, bei dem Verknüpfungen in Kommentaren nicht funktionierten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1376">We fixed an issue where hyperlinks in comments weren’t working.</span></span>

- <span data-ttu-id="b48ee-1377">Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1377">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="b48ee-1378">Wir haben ein Problem behoben, bei dem die Kommentare zwischen der Webanwendung und der Desktopanwendung nicht synchronisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1378">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

- <span data-ttu-id="b48ee-1379">Es wurde ein Problem behoben, bei dem Kommentar-Hinweisblasen bei einer Vergrößerung von 100 % verschwommen erschienen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1379">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>

- <span data-ttu-id="b48ee-1380">Es wurde ein Problem behoben, bei dem beim Hinzufügen eines neuen Kommentars zu einem leeren Dokument nichts geschah.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1380">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>

- <span data-ttu-id="b48ee-1381">Es wurde ein Problem behoben, bei dem das Einfügen von HTML in WordMail für Kalender nicht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1381">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>

- <span data-ttu-id="b48ee-1382">Es wurde ein Problem behoben, bei dem die Beantwortung eines Kommentars in einer gemeinsam verfassten Sitzung manchmal zum Einfrieren von Word führen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1382">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

- <span data-ttu-id="b48ee-1383">Es wurde ein Problem behoben, bei dem das Einfügen oder Aktualisieren eines Indexes in einem Dokument mit mehr als hundert Einträgen zum Absturz der Anwendung führte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1383">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>

- <span data-ttu-id="b48ee-1384">Es wurde ein Problem behoben, bei dem die Aktivierung der Richtlinie Word 2007 und höher Binärdokumente und -vorlagen dazu führen würde, dass einige Fälle bei der gemeinsamen Dokumentenerstellung fehlschlugen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1384">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>

- <span data-ttu-id="b48ee-1385">Es wurde ein Problem behoben, durch das Dateien mit benutzerdefinierten XML-Werten extrem langsam geöffnet wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1385">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

- <span data-ttu-id="b48ee-1386">Es wurde ein Problem behoben, bei dem Dateien mit langen Pfadnamen (größer als 32 KB) nicht geöffnet werden konnten und eine entsprechende Fehlermeldung nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1386">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b48ee-1387">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-1387">Office Suite</span></span>

- <span data-ttu-id="b48ee-1388">Wir haben das Problem untersucht und behoben, bei dem die Bereitstellung von Office 365 ProPlus über InTune nach einem Herunterfahren des Betriebssystems pausiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1388">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

- <span data-ttu-id="b48ee-1389">Es wurde ein Problem in Visual Basic for Applications in Microsoft Office behoben, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthielten, von der Office-Anwendung beim Laden als fehlerhaft angesehen wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1389">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="b48ee-1390">Das Update behebt ein Problem in Microsoft Office, bei dem Visual Basic for Applications-Projekte mit Referenzen, die bei der Suche nach in der PATH-Umgebungsvariable angegebenen Speicherorten gefunden werden sollen, zur Laufzeit möglicherweise nicht richtig gefunden werden, was zu VBA-Laufzeitfehlern führt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1390">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-june-08"></a><span data-ttu-id="b48ee-1392">Version 2005: 08. Juni</span><span class="sxs-lookup"><span data-stu-id="b48ee-1392">Version 2005: June 08</span></span>
<span data-ttu-id="b48ee-1393">*Version 2005 (Build 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1393">*Version 2005 (Build 12827.20336)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1395">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1395">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="b48ee-1396">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1396">PowerPoint</span></span>

- <span data-ttu-id="b48ee-1397">Es wurde ein Problem mit dem Dialog zum Ersetzen von Schriftarten behoben, bei dem die Dropdown-Liste zum Ersetzen von Schriftarten nur Schriftarten innerhalb der Präsentation anzeigt, statt der auf dem System installierten Schriftarten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1397">We have fixed an issue with replace fonts dialog where replace font dropdown only shows fonts within the presentation instead of fonts installed on the system.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-june-04"></a><span data-ttu-id="b48ee-1399">Version 2005: 04. Juni</span><span class="sxs-lookup"><span data-stu-id="b48ee-1399">Version 2005: June 04</span></span>
<span data-ttu-id="b48ee-1400">*Version 2005 (Build 12827.20320)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1400">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1402">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1402">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="b48ee-1403">Access</span><span class="sxs-lookup"><span data-stu-id="b48ee-1403">Access</span></span>

- <span data-ttu-id="b48ee-1404">**Bleiben Sie am Puls der Zeit! Der Datentyp "Datum/Uhrzeit Erweitert" hat eine bessere Genauigkeit:** Einführung eines neuen und verbesserten Datentyps.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1404">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="b48ee-1405">Zur Verbesserung der Syntaxkompatibilität mit SQL und zur Erhöhung der Genauigkeit und des Detaillierungsgrads von Datensätzen, die Datum und Uhrzeit enthalten, implementieren wir den Datentyp "DateTime2" in Access.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1405">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="b48ee-1406">Dieser zusätzliche Datentyp für Datum und Uhrzeit umfasst einen größeren Datumsbereich (0001-01-01 bis 9999-12-31) mit einer höher spezifizierten Zeitgenauigkeit (Nanosekunden statt Sekunden), die Sie bereitstellen und Berechnungen durchführen können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1406">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="b48ee-1407">Zum Aktivieren wählen Sie Neues Feld > Datum und Uhrzeit Erweitert.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1407">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="b48ee-1408">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-1408">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="b48ee-1409">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1409">Excel</span></span>

- <span data-ttu-id="b48ee-1410">**Erstellen von PivotTables aus Datasets in Power BI in Excel:** Sie können mit wenigen Klicks PivotTables in Excel erstellen, die mit in Power BI gespeicherten Datensätzen verbunden sind.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1410">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="b48ee-1411"> Auf diese Weise können Sie sowohl PivotTables als auch Power BI optimal nutzen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1411">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="b48ee-1412">Berechnen, zusammenfassen und analysieren Sie Ihre Daten mit PivotTables aus Ihren sicheren Power BI-Datensätzen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1412">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1413">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1413">Outlook</span></span>

- <span data-ttu-id="b48ee-1414">**Option zum schnellen Wiederöffnen von Elementen aus der vorherigen Outlook-Sitzung:** Wir haben eine Option zum schnellen Wiederöffnen von Elementen aus einer vorherigen Outlook-Sitzung hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1414">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1417">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1417">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="b48ee-1418">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1418">PowerPoint</span></span>

- <span data-ttu-id="b48ee-1419">Dies behebt einen Absturz, wenn Benutzer sowohl moderne als auch ältere Kommentare in einer Datei haben, wodurch ein Upgrade der Kommentare ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1419">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b48ee-1420">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-1420">Office Suite</span></span>

- <span data-ttu-id="b48ee-1421">Es wurde das Problem der Fehlerrate von „ValidateInstall“ behoben, indem die Bing-Add-On-Installationsvalidierung standardmäßig auf „wahr“ gesetzt und die erfolgreiche Ausführung von MSI als erfolgreiche Installation betrachtet wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1421">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-may-29"></a><span data-ttu-id="b48ee-1423">Version 2005: 29. Mai</span><span class="sxs-lookup"><span data-stu-id="b48ee-1423">Version 2005: May 29</span></span>
<span data-ttu-id="b48ee-1424">*Version 2005 (Build 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1424">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1426">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1426">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="b48ee-1427">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1427">Excel</span></span>

- <span data-ttu-id="b48ee-1428">**Tabellendarstellung:** Sortieren/Filtern während der Zusammenarbeit mit anderen in der Excel-Desktopumgebung.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1428">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1429">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1429">Outlook</span></span>

- <span data-ttu-id="b48ee-1430">**Zusätzliche Schaltflächen zu Outlook-Toastbenachrichtigungen hinzugefügt:** In Outlook-Toastbenachrichtigungen werden nun Schaltflächen für schnelle Aktionen angezeigt, wenn Outlook unter Windows 10 ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1430">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1433">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1433">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="b48ee-1434">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1434">Outlook</span></span>

- <span data-ttu-id="b48ee-1435">Es wurde ein Problem behoben, das dazu führte, dass Benutzer von Windows 10-Serverversionen die Warnung "Antivirenstatus: Ungültig" gesehen haben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1435">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="b48ee-1436">Diese Version von Windows unterstützt die Erkennung von Antivirus, aber es wurde kein Antivirus gefunden, obwohl Antivirus korrekt installiert war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1436">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b48ee-1437">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-1437">Office Suite</span></span>

- <span data-ttu-id="b48ee-1438">Der Office-Host stürzte in Fenstern ab, wenn ein Add-In aktiviert wird, während der Registrierungsschlüssel HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth auf Null gesetzt ist.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1438">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="b48ee-1439">Mit dieser Änderung wird dieses Problem behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1439">This change would fix this issue.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-may-21"></a><span data-ttu-id="b48ee-1441">Version 2005: 21. Mai</span><span class="sxs-lookup"><span data-stu-id="b48ee-1441">Version 2005: May 21</span></span>
<span data-ttu-id="b48ee-1442">*Version 2005 (Build 12827.20210)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1442">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)




[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1446">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1446">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1447">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1447">Excel</span></span>

- <span data-ttu-id="b48ee-1448">Es wurde ein Problem behoben, bei dem Excel u. U. nicht mehr reagierte, nachdem STRG+UMSCHALT+Pfeiltasten zum Scrollen verwendet wurden, wenn das Excel-Fenster über Microsoft Teams gemeinsam genutzt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1448">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="b48ee-1449">In einigen Fällen führt das Anklicken einer Verknüpfung zu einem Ort innerhalb derselben Arbeitsmappe dazu, dass die Arbeitsmappe ausgeblendet wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1449">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="b48ee-1450">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1450">Outlook</span></span>

- <span data-ttu-id="b48ee-1451">Es wurde ein Problem mit dem Ereignis "CLP-Überwachung" für die Bezeichnung "Antworten/Weiterleiten" behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1451">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="b48ee-1452">Es wurde ein Problem behoben, bei dem beim Einreichen von Feedback aus einer Administratorbenachrichtigung ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1452">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-may-14"></a><span data-ttu-id="b48ee-1454">Version 2005: 14. Mai</span><span class="sxs-lookup"><span data-stu-id="b48ee-1454">Version 2005: May 14</span></span>
<span data-ttu-id="b48ee-1455">*Version 2005 (Build 12827.20160)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1455">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1457">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1457">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1458">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1458">Excel</span></span>

- <span data-ttu-id="b48ee-1459">**Automatisches Anwenden oder Empfehlen von Vertraulichkeitsbezeichnungen:** Office kann eine Vertraulichkeitsbezeichnung basierend auf den erkannten vertraulichen Inhalten empfehlen oder automatisch anwenden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1459">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b48ee-1460">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1460">PowerPoint</span></span>

- <span data-ttu-id="b48ee-1461">**Kein Clicker benötigt: das erledigen Ihre Ohrhörer**: Verwenden Sie Ihre Surface Earbuds, um Ihre PowerPoint-Präsentationen zu steuern.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1461">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="b48ee-1462">Wichtig: Sie müssen Ihre Surface Earbuds in der Surface Audio-App für Windows 10 koppeln, um Gesten für die Steuerung von Präsentationen verwenden zu können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1462">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="b48ee-1463">Anweisungen für die ersten Schritte mit der Surface Audio-App unter Windows 10 finden Sie hier.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1463">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="b48ee-1464">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-1464">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="b48ee-1465">**Automatisches Anwenden oder Empfehlen von Vertraulichkeitsbezeichnungen:** Office kann eine Vertraulichkeitsbezeichnung basierend auf den erkannten vertraulichen Inhalten empfehlen oder automatisch anwenden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1465">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-1466">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1466">Word</span></span>

- <span data-ttu-id="b48ee-1467">**Automatisches Anwenden oder Empfehlen von Vertraulichkeitsbezeichnungen:** Office kann eine Vertraulichkeitsbezeichnung basierend auf den erkannten vertraulichen Inhalten empfehlen oder automatisch anwenden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1467">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1470">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1470">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="b48ee-1471">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1471">Excel</span></span>

- <span data-ttu-id="b48ee-1472">Die Größe der Steuerelemente zur Bearbeitung von Zellreferenzen im Dialogfeld "Benutzerdefinierte Fehlerindikatoren", das bei Diagrammen verwendet wird, wurde erhöht.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1472">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="b48ee-1473">Ein Problem wurde behoben, bei dem die Diagrammdatentabelle Werte in einer Datumsachse nicht korrekt rendern konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1473">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="b48ee-1474">Es wurde ein Problem behoben, bei dem Seitenumbrüche nicht deaktiviert werden konnten, nachdem die Seitenlayout- oder Seitenumbruchsvorschau angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1474">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="b48ee-1475">Es wurde ein Problem behoben, bei dem Diagrammlinienarten nach dem Ein- und Ausblenden von Spalten mit Seriendaten verloren gehen konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1475">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="b48ee-1476">Es wurde ein Problem behoben, bei dem das Einfügen einer Spalte in eine gefilterte Liste länger als erwartet dauern würde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1476">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="b48ee-1477">Ein Problem mit der Skalierung von Kontrollkästchen in Formularsteuerelementen beim Drucken wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1477">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="b48ee-1478">Es wurde ein Problem behoben, bei dem die externe Verknüpfung nicht mehr funktioniert, nachdem die Datei erneut geöffnet wurde, wenn der Dateipfad zu lang ist.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1478">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="b48ee-1479">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1479">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="b48ee-1480">Application.Evaluate (VBA) funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1480">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="b48ee-1481">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1481">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="b48ee-1482">Diese Änderung behebt ein Problem, bei dem Informationen zur bedingten Formatierung (CF) nicht korrekt in XLSB-Dateien gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1482">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="b48ee-1483">Diese Änderung behebt ein Problem, bei dem das Bestimmtheitsmaß der Diagrammtrendlinie (im Fall des erzwungenen y-Achsenabschnitts) falsch war, obwohl die Funktion LINEST den richtigen Wert zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1483">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="b48ee-1484">Diese Änderung behebt ein Problem, bei dem benutzerdefinierte Diagramm-Trendlinienformatierungen nicht immer gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1484">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="b48ee-1485">Ein Absturz konnte auftreten, wenn versucht wurde, Änderungen mithilfe des Legacymodus "Freigegebene Arbeitsmappe" auf einem neuen Blatt für eine Arbeitsmappe aufzulisten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1485">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="b48ee-1486">Das Problem, bei dem es sein konnte, dass benutzerdefinierte Formatierungen in Pivot-Diagrammen nicht gespeichert wurden, wenn die Option "Invertieren, wenn negativ" aktiviert war, wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1486">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="b48ee-1487">Es wurde ein Problem behoben, bei dem die benutzerdefinierte Formatierung für einen einzelnen Datenpunkt in einem Pivot-Diagramm nicht gespeichert wurde, wenn die Option "Invertieren, wenn negativ" ausgewählt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1487">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="b48ee-1488">Diese Änderung behebt ein Problem, bei dem das in eine CSV-Datei hochgeladene @-Zeichen dazu führte, dass die Zeichenfolge nach dem @-Zeichen in eine Formel konvertiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1488">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="b48ee-1489">Es wurde ein Problem behoben, bei dem Dezimalwerte in der SEQUENCE-Funktion nicht korrekt gerundet wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1489">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="b48ee-1490">OneNote</span><span class="sxs-lookup"><span data-stu-id="b48ee-1490">OneNote</span></span>

- <span data-ttu-id="b48ee-1491">Ein Problem beim Speichern von Zeilenumbrüchen als vertikale Registerkarten wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1491">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1492">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1492">Outlook</span></span>

- <span data-ttu-id="b48ee-1493">Behebt ein Problem, das dazu führte, dass Benutzer keine "Persönliche Kontaktgruppe" als "Besprechungsteilnehmer" hinzufügen konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1493">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="b48ee-1494">Es wurde ein Problem behoben, bei dem die Schaltfläche "Kategorisieren" für Gruppenkalender im Office-Menüband deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1494">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="b48ee-1495">Es wurde ein Problem behoben, durch das Outlook nach einem Windows-Update beim Öffnen von lokal gespeicherten MSG- oder OFT-Dateien abstürzte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1495">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="b48ee-1496">Es wurde ein Problem behoben, bei dem Gruppenordner von Unternehmenskunden, die nicht implementiert sind oder nicht funktionieren, in Outlook zu der Meldung "reagiert nicht" führte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1496">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="b48ee-1497">Es wurde ein Problem behoben, das dazu führte, dass sehr lange Safelinks, auf die Benutzer im Outlook-Desktopclient klickten, aufgrund von Trunkierung nicht geladen wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1497">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="b48ee-1498">Es wurde ein Problem behoben, bei dem Outlook-Ordner mit Namen, die DBCS-Zeichen (Doublebyte-Zeichensatz) enthalten, bei der Synchronisierung mit dem Server zeitweise verschwanden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1498">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="b48ee-1499">Dazu musste Outlook mit einem IMAP-Konto konfiguriert und auf einem System mit dem Gebietsschema „Japanisch“ ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1499">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="b48ee-1500">Es wurde ein Problem behoben, das dazu führte, dass Löschregeln, die für andere Postfächer als das primäre Postfach des Benutzers erstellt wurden, ungültig wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1500">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="b48ee-1501">Es wurde ein Problem behoben, das dazu führte, dass Anlagen beim Weiterleiten einer verschlüsselten Nachricht verworfen wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1501">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="b48ee-1502">Es wurde ein Problem behoben, das dazu geführt hat, dass bei Besprechungen, die mehr als 2 Monate entfernt sind, ein Besprechungsthema im "Terminplanungs-Assistenten" nicht angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1502">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="b48ee-1503">Behebt ein Problem, das dazu führte, dass Benutzer beim Weiterleiten großer HTML-Nachrichten den Nachrichtentext abgeschnitten sahen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1503">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="b48ee-1504">Es wurde die Möglichkeit des Erzwingens der S/MIME-Standardsignatur-Konfiguration über eine Gruppenrichtlinie hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1504">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b48ee-1505">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1505">PowerPoint</span></span>

- <span data-ttu-id="b48ee-1506">Es wurde ein Problem behoben, bei dem Entwürfe von Kommentaren nicht verfügbar waren, wenn ein Benutzer einen Kommentar erstellte, ohne ihn zu posten, und den Kommentarbereich schloss, dann ein neues Fenster öffnete, über mehrere Folien navigierte, das Fenster schloss und schließlich den Kommentarbereich in der ursprünglichen Präsentation wieder öffnete.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1506">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="b48ee-1507">Es wurde ein Problem behoben, bei dem beim Bewegen des Mauszeigers über das Sternchen-Symbol (\*) der Benutzername und das Datum der letzten Person, die das Dokument aktualisiert hat, nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1507">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="b48ee-1508">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-1508">Project</span></span>

- <span data-ttu-id="b48ee-1509">Wenn Vorgänger/Nachfolger-Daten in einer Formular-Maske bearbeitet werden, wird ein zusätzliches ProjectBeforeTaskChange-Ereignis ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1509">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="b48ee-1510">Es wurde ein Problem behoben, bei dem Project abstürzen konnte, wenn das Feld „Boardstatus“ in einem Projekt geändert wurde, das mit einer SharePoint-Aufgabenliste verbunden ist.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1510">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="b48ee-1511">Ein Problem wurde behoben, bei dem Project beim Speichern von Projekten möglicherweise abstürzt, die mit älteren Project-Versionen erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1511">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="b48ee-1512">Folgendes Problem wurde behoben: Wenn Sie Project in Verbindung mit der Project Web App verwenden, das Kommas als Dezimaltrennzeichen festgelegt ist, und Sie versuchten, eine Verzögerung hinzuzufügen, schlägt die Methode "TaskDependencies Add" fehl.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1512">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="b48ee-1513">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1513">Word</span></span>

- <span data-ttu-id="b48ee-1514">Es wurde ein Problem behoben, das dazu führte, dass das Einfügen von Kommentaren in ein Dokument im Kollaborationsmodus nicht immer funktionierte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1514">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="b48ee-1515">Diese Änderung behebt ein Problem, bei dem die Personenkarte kurzzeitig eingeblendet wurde, wenn auf die Erwähnung geklickt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1515">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="b48ee-1516">Beim Aktivieren der Option "Lesezeichen anzeigen" wurden keine Lesezeichen angezeigt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1516">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="b48ee-1517">Dieser Fehler wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1517">This has been fixed.</span></span>

- <span data-ttu-id="b48ee-1518">Es wurde das Problem behoben, dass beim Schließen eines Dokuments mit Kommentarentwürfen der Benutzer aufgefordert wurde, ob er das Dokument schließen möchte, ohne die Kommentarentwürfe zu speichern.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1518">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="b48ee-1519">Das Abbrechen der Eingabeaufforderung schloss das Dokument, anstatt es geöffnet zu lassen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1519">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="b48ee-1520">Ein Problem beim Kopieren und Einfügen von Überschriften wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1520">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="b48ee-1521">Es wurde ein Problem behoben, bei dem die Übersetzung eines geposteten Kommentars den Fehler "Fehler beim Einfügen des übersetzten Textes" zur Folge hatte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1521">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="b48ee-1522">Diese Änderung behebt ein Problem, bei dem Text mit Hyperlinks möglicherweise nicht angezeigt wurde, wenn die Option "Feldcodes statt ihrer Werte anzeigen" aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1522">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="b48ee-1523">In der Webansicht und im Plastischen Reader wurde durch das Anklicken eines Hinweises nach oben gescrollt, obwohl er bereits angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1523">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="b48ee-1524">Dieser Fehler wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1524">This has been fixed.</span></span>

- <span data-ttu-id="b48ee-1525">Wir haben ein Problem behoben, dass infolge des Speicherns einer Datei, die ein Makro enthält, unter einem neuen Namen sie mit der Erweiterung DOCX und dem Dateinamen WRO0004.docx gespeichert wurde, und zwar unabhängig davon, was der Benutzer eingab, wodurch das Dokument unbrauchbar wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1525">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b48ee-1526">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-1526">Office Suite</span></span>

- <span data-ttu-id="b48ee-1527">Wenn ein Benutzer eine Richtlinie erhält, die ihn in die Kategorie "Nur für Teams" verschiebt, konnte er dennoch das Outlook-Add-In "Skype for Business" zur Planung von Besprechungen verwenden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1527">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="b48ee-1528">Nach diesem Update können Sie keine Besprechungen mit Skype for Business mehr planen, nachdem der Client die Richtlinie gelesen hat, in der angegeben ist, dass der Benutzer "Nur für Teams" ist, und in den Modus "Nur an Besprechung teilnehmen" wechselt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1528">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="b48ee-1529">Darüber hinaus aktiviert sich das Outlook-Add-In "Skype for Business" beim Start nicht selbst, wenn es sieht, dass sich der Skype for Business-Client im Modus "Nur an Besprechung teilnehmen" befindet.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1529">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="b48ee-1530">Das Update behebt ein Problem in Microsoft Office, bei dem Visual Basic for Applications-Projekte mit Referenzen, die bei der Suche nach in der PATH-Umgebungsvariable angegebenen Speicherorten gefunden werden sollen, zur Laufzeit möglicherweise nicht richtig gefunden werden, was zu VBA-Laufzeitfehlern führt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1530">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="b48ee-1531">Dieses Update behebt ein Problem in Visual Basic for Applications in Microsoft Office, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung beim Laden als fehlerhaft angesehen werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1531">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-may-11"></a><span data-ttu-id="b48ee-1533">Version 2004: 11. Mai</span><span class="sxs-lookup"><span data-stu-id="b48ee-1533">Version 2004: May 11</span></span>
<span data-ttu-id="b48ee-1534">*Version 2004 (Build 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1534">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1536">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1536">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1537">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1537">Excel</span></span>

- <span data-ttu-id="b48ee-1538">**Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1538">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1539">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1539">Outlook</span></span>

- <span data-ttu-id="b48ee-1540">**Verbesserte Links in E-Mails:** Wenn Sie einen Link zu einer Datei einfügen, ersetzt der Dateiname die URL.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1540">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="b48ee-1541">Sie können die Berechtigungen so ändern, dass alle Empfänger Zugriff haben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1541">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="b48ee-1542">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-1542">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="b48ee-1543">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span><span class="sxs-lookup"><span data-stu-id="b48ee-1543">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="b48ee-1544">**Erzählen Sie mit animierten GIFs über sich:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden künftig noch pfiffiger aussehen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1544">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b48ee-1545">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1545">PowerPoint</span></span>

- <span data-ttu-id="b48ee-1546">**Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1546">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="b48ee-1547">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-1547">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="b48ee-1548">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1548">Word</span></span>

- <span data-ttu-id="b48ee-1549">**Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1549">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1552">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1552">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-1553">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1553">Outlook</span></span>

- <span data-ttu-id="b48ee-1554">Es wurde ein Problem behoben, das bei Benutzern zu Abstürzen geführt hat, wenn diese Toast-Nachrichten angesehen haben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1554">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-may-04"></a><span data-ttu-id="b48ee-1556">Version 2004: 04. Mai</span><span class="sxs-lookup"><span data-stu-id="b48ee-1556">Version 2004: May 04</span></span>
<span data-ttu-id="b48ee-1557">*Version 2004 (Build 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1557">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1559">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1559">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-1560">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1560">Outlook</span></span>

- <span data-ttu-id="b48ee-1561">**Bessere Ergebnisse – im Handumdrehen:** wir haben die Suche aktualisiert, damit Sie intelligenter, schneller und zuverlässiger als je zuvor ist.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1561">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="b48ee-1562">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-1562">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="b48ee-1563">**Benachrichtigung Über Vorfall für IT-Administratoren:** Globale Administratoren von Microsoft 365-Mandanten und Administratoren von Office-Apps werden über Outlook und O365 Exchange-Vorfällen benachrichtigt, die sich auf Ihre Benutzer auswirken – mit einer neuen Benachrichtigung im rechten Seitenbereich in Outlook für Windows.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1563">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="b48ee-1564">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-1564">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1567">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1567">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="b48ee-1568">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-1568">Office Suite</span></span>

- <span data-ttu-id="b48ee-1569">Dieses Update behebt ein Problem in Visual Basic for Applications in Microsoft Office, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung beim Laden als fehlerhaft angesehen werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1569">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-april-29"></a><span data-ttu-id="b48ee-1571">Version 2004: 29. April</span><span class="sxs-lookup"><span data-stu-id="b48ee-1571">Version 2004: April 29</span></span>
<span data-ttu-id="b48ee-1572">*Version 2004 (Build 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1572">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1574">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1574">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-1575">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1575">Outlook</span></span>

- <span data-ttu-id="b48ee-1576">**Schützen von Daten in einer Gruppe:** Die beim Erstellen einer Gruppe ausgewählte Vertraulichkeitsbezeichnung wird auf Gruppen-E-Mails, Dokumente und Teamwebsites angewendet.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1576">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1579">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1579">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-1580">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1580">Outlook</span></span>

- <span data-ttu-id="b48ee-1581">Behebt ein Problem, das dazu geführt hat, dass Outlook bei einigen Windows-Versionen abstürzt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1581">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-april-25"></a><span data-ttu-id="b48ee-1583">Version 2004: 25. April</span><span class="sxs-lookup"><span data-stu-id="b48ee-1583">Version 2004: April 25</span></span>
<span data-ttu-id="b48ee-1584">*Version 2004 (Build 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1584">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1586">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1586">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-1587">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1587">Outlook</span></span>

- <span data-ttu-id="b48ee-1588">Es wurde ein Problem behoben, durch das Outlook nach einem Windows-Update beim Öffnen von lokal gespeicherten MSG- oder OFT-Dateien abstürzte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1588">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="b48ee-1589">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-1589">Project</span></span>

- <span data-ttu-id="b48ee-1590">Folgendes Problem wurde behoben: Wenn Sie Project in Verbindung mit Project Web App verwenden, das Kommas als Dezimaltrennzeichen festgelegt ist, und Sie versuchten, einer Abhängigkeit eine Verzögerung hinzuzufügen, schlägt die Methode "TaskDependencies Add" fehl.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1590">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b48ee-1591">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-1591">Office Suite</span></span>

- <span data-ttu-id="b48ee-1592">Mit diesem Fix wird ein Fehler behoben, der verhindert, dass Sie gleichzeitig den Zugriff einschränken und Dateien mit einem Kennwort schützen können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1592">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-april-21"></a><span data-ttu-id="b48ee-1594">Version 2004: 21. April</span><span class="sxs-lookup"><span data-stu-id="b48ee-1594">Version 2004: April 21</span></span>
<span data-ttu-id="b48ee-1595">*Version 2004 (Build 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1595">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1597">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1597">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-1598">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1598">Outlook</span></span>

- <span data-ttu-id="b48ee-1599">Behebt ein Problem, bei dem die Breite des Ordnerbereichs unerwartet geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1599">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="b48ee-1600">Behebt ein Problem, bei dem sich das Programm beim Verlassen von Outlook aufhängte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1600">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-april-15"></a><span data-ttu-id="b48ee-1602">Version 2004: 15. April</span><span class="sxs-lookup"><span data-stu-id="b48ee-1602">Version 2004: April 15</span></span>
<span data-ttu-id="b48ee-1603">*Version 2004 (Build 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1603">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1605">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1605">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1606">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1606">Excel</span></span>

- <span data-ttu-id="b48ee-1607">**Die Unterstützung für Facebook Connector endet:** Ab April 2020 werden von Excel keine externen Datenverbindungen mehr unterstützt, für die der Facebook-Connector eingesetzt wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1607">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1608">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1608">Outlook</span></span>

- <span data-ttu-id="b48ee-1609">**Neue Option zum Deaktivieren von Vorschlägen für @Erwähnungen beim Verfassen von E-Mails in Outlook:** Finden Sie die @Erwähnung-Auswahl eher lästig als sinnvoll?</span><span class="sxs-lookup"><span data-stu-id="b48ee-1609">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="b48ee-1610">Wenn Sie das möchten, können Sie diese nun deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1610">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b48ee-1611">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1611">PowerPoint</span></span>

- <span data-ttu-id="b48ee-1612">**Synchronisieren von Änderungen während der Präsentation:** Änderungen können jetzt synchronisiert werden, wenn sie vorgenommen werden, selbst wenn sich die Präsentation im Bildschirmpräsentationsmodus befindet.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1612">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-1613">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1613">Word</span></span>

- <span data-ttu-id="b48ee-1614">**Fügen Sie einen privaten Kopie Anmerkungen hinzu:** Erstellen Sie handschriftliche Notizen nur für Sie, indem Sie eine private Kopie eines freigegebenen Dokuments erstellen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1614">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="b48ee-1615">Wechseln Sie dazu einfach zu "Anzeige" > "Private Kopie erstellen".</span><span class="sxs-lookup"><span data-stu-id="b48ee-1615">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1618">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1618">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b48ee-1619">Access</span><span class="sxs-lookup"><span data-stu-id="b48ee-1619">Access</span></span>

- <span data-ttu-id="b48ee-1620">Probleme bei der Anpassung der Größe und der Aktualisierung von Tabellen im Aufgabenbereich wurden behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1620">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="b48ee-1621">Ein Problem wurde behoben, bei dem internationale Versionen von Access in der Benutzeroberfläche englische Zeichenfolgen anzeigten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1621">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="b48ee-1622">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1622">Excel</span></span>

- <span data-ttu-id="b48ee-1623">Es wurde ein Problem behoben, bei dem das Auswählen eines Zellbereichs auf einem Arbeitsblatt zur Auswahl nur einer einzelnen Zelle geführt hat.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1623">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="b48ee-1624">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1624">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="b48ee-1625">Ein Problem wurde behoben, bei dem Excel in manchen Fällen abstürzte, nachdem ein Blatt mit einer PivotTable kopiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1625">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="b48ee-1626">Application.Evaluate (VBA) funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1626">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="b48ee-1627">Es wurde ein Leistungsproblem behoben, das Benutzer beim programmgesteuerten Bearbeiten eines großen Zellbereichs festgestellt haben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1627">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="b48ee-1628">Ein Leistungsproblem beim Öffnen von CSV-Dateien in japanischen Umgebungen wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1628">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="b48ee-1629">Es wurde ein Problem behoben, bei dem das Einfügen einer benutzerdefinierten Diagrammvorlage als Standard dazu führte, dass sie als Säulendiagramm gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1629">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="b48ee-1630">Ein Problem wurde behoben, bei dem Datenbeschriftungen in Diagrammen leer angezeigt wurden, wenn die zugrundeliegenden Datenzellen keine Beschriftung aufwiesen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1630">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="b48ee-1631">Es wurde ein Problem behoben, das dazu führen konnte, dass Excel nicht mehr reagierte, wenn die Größe eines Diagramms mit einigen x-Achsen-Bereichen reduziert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1631">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="b48ee-1632">Es wurde ein Problem behoben, bei dem eine Excel-Tabelle mit aktiviertem Z1S1-Zellbezug die freigegeben bzw. gemeinsam erstellt wurde, der aktive Zellbezug im Z1S1-Modus nicht angezeigt wurde, wenn man auf das Symbol für die Anwesenheitsanzeige zeigte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1632">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="b48ee-1633">Diese Änderung betrifft Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1633">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1634">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1634">Outlook</span></span>

- <span data-ttu-id="b48ee-1635">Diese Änderung ist gegen Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen gerichtet.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1635">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="b48ee-1636">Diese Änderung behebt ein Problem, bei dem die neuesten Änderungen an E-Mail-Entwürfen nicht aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1636">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="b48ee-1637">Ein Problem wurde behoben, bei dem Sie mit der rechten Maustaste auf eine Datei klicken und "Senden an" nicht funktionieren würde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1637">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="b48ee-1638">Ein Problem wurde behoben, durch das Stellvertretungen auf unterschiedlichen Computern unterschiedliche Ordnerhierarchien für freigegebene Postfächer angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1638">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="b48ee-1639">Ein Problem wurde behoben, durch das gelegentlich Kategorien in E-Mail-Nachrichten nicht mehr aufschienen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1639">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="b48ee-1640">Es wurde ein Problem behoben, durch das einige Erinnerungen nicht ausgelöst wurden, wenn die Zeitzone auf einem Computer geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1640">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="b48ee-1641">Es wurde ein Problem behoben, das einen Absturz verursachte, wenn Benutzer versuchten, die Eigenschaften eines Organisationsformulars anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1641">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="b48ee-1642">Es wurde ein Problem behoben, bei dem, wenn ein Benutzer einen angepassten Suchpfad für das Adressbuch hatte, der Namensauflösungsbereich von Outlook auf den angepassten Pfad beschränkt wurde, anstatt die Globale Adressliste (GAL) einzubeziehen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1642">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="b48ee-1643">Es wurde ein Problem behoben, das bewirkt hat, dass die Schaltfläche "In der Cloud speichern" in den Anlagentools fehlte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1643">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="b48ee-1644">Es wurde ein Problem behoben, das bewirkt hat, dass Benutzer beim Antworten auf eine verwaltete Nachricht mit digitaler Berechtigung aus einem Inspektor-Fenster keine Signatur hinzufügen konnten, wenn er nicht über die Berechtigung "Besitzer" für die Nachricht verfügte, auf die geantwortet wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1644">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="b48ee-1645">Es wurde ein Problem behoben, durch das Benutzer keine weiteren Anlagen von einem Webspeicherort zu einer zuvor erstellten Besprechung hinzufügen konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1645">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="b48ee-1646">Es wurde ein Problem behoben, das dazu geführt hat, dass das „Datum der letzten Änderung“ in einer Datei beim Hinzufügen einer Anlage zu einer E-Mail oder beim Speichern einer Anlage aus einer E-Mail durch Ziehen und Ablegen (im Gegensatz zum Hinzufügen oder Speichern über ein Menü) aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1646">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="b48ee-1647">Es wurde ein Problem behoben, bei dem durch das Drücken der EINGABETASTE im erweiterten Suchbereich keine Suche gestartet wurde. Stattdessen mussten Benutzer auf die Schaltfläche "Suchen" klicken.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1647">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="b48ee-1648">Es wurde ein Problem behoben, bei dem innerhalb eines Satzes von zurückgegebenen Suchergebnissen beim Sortieren der Ergebnisse nach Kategorien die Kategoriefarben nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1648">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="b48ee-1649">Ein Problem wurde behoben, bei dem die Suche keine Informationen zu Benutzern anzeigte, wenn die Option "Benutzerfotos anzeigen, wenn verfügbar" deaktiviert war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1649">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b48ee-1650">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1650">PowerPoint</span></span>

- <span data-ttu-id="b48ee-1651">Diese Änderung behebt einen Fehler, der dazu führen kann, dass PowerPoint-Dateien mit Emojis beim Speichern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1651">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="b48ee-1652">Diese Änderung behebt ein Problem, bei dem beim Rendern eines Diagramms einer älteren Excel-Version, das als OLE-Objekt in PowerPoint oder Word eingebettet ist, u. U. nicht immer der Diagrammtitel angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1652">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="b48ee-1653">Es wurde ein Problem behoben, bei dem beim Kopieren von Text aus Excel in PowerPoint u. U. dessen Formatierung geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1653">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="b48ee-1654">Diese Änderung behebt ein Problem, bei dem das Suchen von Sonderzeichen mithilfe der Option "Nur ganze Wörter suchen" nicht immer erwartungsgemäß funktioniert hat.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1654">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="b48ee-1655">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-1655">Project</span></span>

- <span data-ttu-id="b48ee-1656">Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1656">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="b48ee-1657">Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1657">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="b48ee-1658">Ein Problem wurde behoben, bei dem das VBA-Ereignis (Visual Basic Applications) "ProjectBeforeTaskChange" nicht ausgelöst wurde, wenn ein Benutzer auf die Schaltfläche "Deaktivieren" geklickt hat, die sich auf dem Menüband "Vorgänge" innerhalb der Planungsgruppierung befindet.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1658">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="b48ee-1659">Wenn Sie Vorgänger- oder Nachfolgerdetails in einer Ansicht vom Typ „Formular“ festlegen, wurden die Änderungen nicht immer durch das Ereignis „ProjectBeforeTaskChange Visual Basic Applications“ (VBA) erfasst.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1659">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="b48ee-1660">Wenn Sie beispielsweise eine Abhängigkeit gelöscht und im Formular auf „OK“ geklickt haben, wurde das Ereignis nicht ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1660">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="b48ee-1661">Dieses Verhalten wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1661">This behavior has been fixed.</span></span>

- <span data-ttu-id="b48ee-1662">Es wurde ein Problem behoben, bei dem die neuesten Werte für die tatsächlichen Kosten der geleisteten Arbeit (ACWP) nicht angezeigt wurden, nachdem eine Änderung, z. B. eine Datumsänderung, vorgenommen wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1662">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="b48ee-1663">Es wurde ein Problem behoben, bei dem das Öffnen eines Projekts über das Menü "Zuletzt verwendet" (MRU) die Projektdatei mit Lese- bzw. Schreibzugriff öffnete.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1663">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="b48ee-1664">Diese Änderung behebt das Problem, dass Sie eine manuelle Aufgabe mit einem Startdatum und einer Uhrzeit (aber ohne Dauer) erstellt haben, diese aber mit einer falschen Uhrzeit auf der Zeitachse angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1664">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="b48ee-1665">Es wurde ein Problem behoben, bei dem das Drucken einer Zeitleiste mithilfe eines Hijri-Kalenders dazu führte, dass ein Monat in der Druckansicht übersprungen oder dupliziert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1665">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="b48ee-1666">Diese Änderung richtet sich gegen ein Problem, bei dem die Arbeit im Team Planner mit GDI-Objekten zu einer Überzuweisung von GDI-Objekten und zu geringem Speicherplatz führen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1666">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="b48ee-1667">Ein Problem wurde behoben, durch das, wenn "CustomFieldValueListGetItem" ausgeführt wurde und keine Nachschlagetabelle für das benutzerdefinierte Feld vorhanden war, eine leere Nachschlagetabelle erstellt wurde, auch wenn dies nicht so sein sollte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1667">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="b48ee-1668">Wenn Vorgänger/Nachfolger-Daten in einer Maske bearbeitet werden, wird ein zusätzliches ProjectBeforeTaskChangeevent ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1668">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="b48ee-1669">Es wurde ein Problem behoben, bei dem der Benutzer keine zeitgesteuerte Baseline-Arbeit eingeben konnte, wenn die Einstellung zum Schutz der aktuellen Arbeit aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1669">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-1670">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1670">Word</span></span>

- <span data-ttu-id="b48ee-1671">Diese Änderung behebt ein Problem, bei dem wenn der Mauszeiger über einen Hinweis gehalten wurde, dessen Karte nicht hervorgehoben wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1671">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="b48ee-1672">Diese Änderung behebt ein Problem, bei dem wenn mehrere Seiten aus dem Menü "Ansicht" ausgewählt wurden, der Kommentarbereich u. U. als leer angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1672">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="b48ee-1673">Es wurde ein Problem behoben, durch das die Funktion zum Posten von Kommentaren deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1673">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="b48ee-1674">Diese Änderung behebt ein Problem, das dazu führte, dass der Text in gruppierten Formen beim Verwenden des Lasso-Auswahltools vorübergehend ausgeblendet wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1674">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="b48ee-1675">Diese Änderung betrifft Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1675">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="b48ee-1676">Diese Änderung behebt ein Problem, bei dem beim Rendern eines Diagramms einer älteren Excel-Version, das als OLE-Objekt in PowerPoint oder Word eingebettet ist, u. U. nicht immer der Diagrammtitel angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1676">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="b48ee-1677">Diese Änderung betrifft ein Problem, bei dem der Account Manager keine Nachrichten versendete, was zu einer Unterbrechung bei Anwendungen von Drittanbietern führte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1677">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="b48ee-1678">Diese Änderung behebt ein Problem in der Zwei-Seiten-Ansicht. Beim Erstellen eines Kommentars wurde der Kommentaranker nicht immer in der Anzeige angezeigt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1678">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="b48ee-1679">Ein Problem wurde behoben, bei dem das Eingeben oder Bearbeiten eines Kommentars und Verwenden von STRG+A dazu führte, dass statt nur innerhalb der Kommentarkarte Text im Zeichenbereich markiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1679">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="b48ee-1680">Ein Problem wurde behoben, bei dem ein Absatz, dessen Formatvorlage ein Vorgänger einer mit einer Liste verknüpften Formatvorlage war, möglicherweise verloren ging.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1680">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="b48ee-1681">Diese Änderung behebt ein Problem, bei dem das Inhaltsverzeichnis mit Überschriftenformaten aktualisiert wurde, die im Dokument nicht vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1681">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="b48ee-1682">Es wurde ein Problem behoben, bei dem die Ausrichtung von Wörtern in einem Dokument durcheinandergebracht wurde, wenn Benutzer nach dem Drucken mit Schnelldruck versuchten, den Text zu bearbeiten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1682">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="b48ee-1683">Es wurde ein Problem beim Zusammenführen von zwei Dokumenten in ein Dokument behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1683">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="b48ee-1684">Es wurde ein Problem behoben, bei dem in Word-Dokumenten gespeicherte digitale Signaturen beim Versand der Dokumente per E-Mail entfernt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1684">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="b48ee-1685">Es wurde ein Problem behoben, bei dem das Markieren von Überarbeitungen, die Formeln enthalten, beim Speichern der Datei zu einem Fehler führen konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1685">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-april-14"></a><span data-ttu-id="b48ee-1687">Version 2003: 14. April</span><span class="sxs-lookup"><span data-stu-id="b48ee-1687">Version 2003: April 14</span></span>
<span data-ttu-id="b48ee-1688">*Version 2003 (Build 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1688">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="b48ee-1689">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="b48ee-1689">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS CONTENT START NICHT ENTFERNEN)

- <span data-ttu-id="b48ee-1691">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1691">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-april-09"></a><span data-ttu-id="b48ee-1693">Version 2003: 09. April</span><span class="sxs-lookup"><span data-stu-id="b48ee-1693">Version 2003: April 09</span></span>
<span data-ttu-id="b48ee-1694">*Version 2003 (Build 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1694">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1696">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1696">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1697">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1697">Excel</span></span>

- <span data-ttu-id="b48ee-1698">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="b48ee-1698">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="b48ee-1699">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="b48ee-1699">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1700">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1700">Outlook</span></span>

- <span data-ttu-id="b48ee-1701">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="b48ee-1701">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="b48ee-1702">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="b48ee-1702">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b48ee-1703">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1703">PowerPoint</span></span>

- <span data-ttu-id="b48ee-1704">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="b48ee-1704">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="b48ee-1705">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="b48ee-1705">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-1706">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1706">Word</span></span>

- <span data-ttu-id="b48ee-1707">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="b48ee-1707">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="b48ee-1708">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="b48ee-1708">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)




[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-april-03"></a><span data-ttu-id="b48ee-1712">Version 2003: 3. April</span><span class="sxs-lookup"><span data-stu-id="b48ee-1712">Version 2003: April 03</span></span>
<span data-ttu-id="b48ee-1713">*Version 2003 (Build 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1713">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1715">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1715">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1716">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1716">Excel</span></span>

- <span data-ttu-id="b48ee-1717">Verwendung der VBA-Anwendung. „Evaluate“ funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1717">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1718">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1718">Outlook</span></span>

- <span data-ttu-id="b48ee-1719">Es wurde ein Problem behoben, das dazu führte, dass Benutzer gelegentlich einen Absturz feststellten, wenn Sie den X-Knopf auf ihrer Maus verwendeten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1719">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="b48ee-1720">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-1720">Project</span></span>

- <span data-ttu-id="b48ee-1721">Wenn Vorgänger/Nachfolger-Daten in einer Maske bearbeitet werden, wird ein zusätzliches ProjectBeforeTaskChangeevent ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1721">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-1722">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1722">Word</span></span>

- <span data-ttu-id="b48ee-1723">Es wurde ein Problem behoben, das dazu führte, dass Benutzer gelegentlich einen Absturz feststellten, wenn Sie den X-Knopf auf ihrer Maus verwendeten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1723">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-31"></a><span data-ttu-id="b48ee-1725">Version 2003: 31. März</span><span class="sxs-lookup"><span data-stu-id="b48ee-1725">Version 2003: March 31</span></span>
<span data-ttu-id="b48ee-1726">*Version 2003 (Build 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1726">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1728">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1728">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="b48ee-1729">Access</span><span class="sxs-lookup"><span data-stu-id="b48ee-1729">Access</span></span>

- <span data-ttu-id="b48ee-1730">**Aufgabenbereich "Tabellen hinzufügen":** Der neue Aufgabenbereich "Tabellen hinzufügen" von Access ist endlich da!</span><span class="sxs-lookup"><span data-stu-id="b48ee-1730">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="b48ee-1731">Mit dieser Funktion können Sie einfach auswählen/mehrfach auswählen, welche Tabellen sie in einem Abfragefenster hinzufügen/entfernen möchten, ohne zum Dialogfeld "Tabellen anzeigen" für Abfragen und für die Beziehungsansicht zu navigieren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1731">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="b48ee-1732">Dazu gehört auch eine neue Registerkarte "Verknüpfungen", um verknüpfte Tabellen anzuzeigen, ein Suchfeld, um die aktuelle Liste zu filtern, "Drag & Drop"-Verhalten und mehr!</span><span class="sxs-lookup"><span data-stu-id="b48ee-1732">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1735">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1735">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="b48ee-1736">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-1736">Project</span></span>

- <span data-ttu-id="b48ee-1737"><span style="display:inline !important;">Es wurde ein Problem behoben, bei dem der Benutzer keine zeitgesteuerte Baseline-Arbeit eingeben konnte, wenn die Einstellung zum Schutz der tatsächlichen Arbeit aktiviert ist.</span></span><span class="sxs-lookup"><span data-stu-id="b48ee-1737"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-25"></a><span data-ttu-id="b48ee-1739">Version 2003: 25. März</span><span class="sxs-lookup"><span data-stu-id="b48ee-1739">Version 2003: March 25</span></span>
<span data-ttu-id="b48ee-1740">*Version 2003 (Build 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1740">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="b48ee-1741">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1741">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="b48ee-1742">Version 2003: 23. März</span><span class="sxs-lookup"><span data-stu-id="b48ee-1742">Version 2003: March 23</span></span>
<span data-ttu-id="b48ee-1743">*Version 2003 (Build 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1743">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="b48ee-1744">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1744">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="b48ee-1745">Version 2003: 21. März</span><span class="sxs-lookup"><span data-stu-id="b48ee-1745">Version 2003: March 21</span></span>
<span data-ttu-id="b48ee-1746">*Version 2003 (Build 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1746">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1748">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1748">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-1749">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1749">Outlook</span></span>

- <span data-ttu-id="b48ee-1750">**An Besprechungen teilnehmen, ohne den Posteingang zu verlassen:** Sie brauchen nicht zu Ihrem Kalender zu wechseln, um an Onlinebesprechungen teilzunehmen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1750">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="b48ee-1751">Wenn der Kalender im Aufgabenbereich angeheftet ist, können Sie mit nur einem Klick an einer Besprechung teilnehmen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1751">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="b48ee-1752">**Visuelle Aktualisierung des Kalenders:** Letztes Jahr haben wir die E-Mail-Erfahrung visuell aufgefrischt, und dieses Jahr ist der Kalender mit einem Facelifting an der Reihe!</span><span class="sxs-lookup"><span data-stu-id="b48ee-1752">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="b48ee-1753">Die Aktualisierungen sind frisch, aber vertraut, so dass Sie als erfahrener Outlook-Benutzer sofort einsteigen und produktiver sein können.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1753">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b48ee-1754">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1754">PowerPoint</span></span>

- <span data-ttu-id="b48ee-1755">**Aktualisieren von Folien während der Bildschirmpräsentation:** Aktualisieren Sie Folien, die von anderen Autoren während Ihrer Präsentation geändert wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1755">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-16"></a><span data-ttu-id="b48ee-1757">Version 2003: 16. März</span><span class="sxs-lookup"><span data-stu-id="b48ee-1757">Version 2003: March 16</span></span>
<span data-ttu-id="b48ee-1758">*Version 2003 (Build 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1758">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1760">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1760">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1761">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1761">Excel</span></span>

- <span data-ttu-id="b48ee-1762">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1762">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1763">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1763">Outlook</span></span>

- <span data-ttu-id="b48ee-1764">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1764">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b48ee-1765">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1765">PowerPoint</span></span>

- <span data-ttu-id="b48ee-1766">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1766">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-1767">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1767">Word</span></span>

- <span data-ttu-id="b48ee-1768">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1768">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b48ee-1769">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-1769">Office Suite</span></span>

- <span data-ttu-id="b48ee-1770">**Bereiche im Registerkartenformat:** Jetzt können Sie über die Registerkarten-Benutzeroberfläche auf der rechten Seite der App zwischen mehreren Bereichen wechseln.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1770">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="b48ee-1771">Die Benutzeroberfläche wird nur angezeigt, wenn Sie mehr als 2 Fenster geöffnet haben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1771">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1774">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1774">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1775">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1775">Excel</span></span>

- <span data-ttu-id="b48ee-1776">Es wurde ein Problem behoben, bei dem externe Links beim Füllen nicht aktualisiert werden, wenn das Quellbuch geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1776">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1777">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1777">Outlook</span></span>

- <span data-ttu-id="b48ee-1778">Es wurde ein Problem behoben, das dazu führte, dass der Outlook-Prozess nach dem Beenden im Task-Manager fortbestand.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1778">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-10"></a><span data-ttu-id="b48ee-1780">Version 2003: 10. März</span><span class="sxs-lookup"><span data-stu-id="b48ee-1780">Version 2003: March 10</span></span>
<span data-ttu-id="b48ee-1781">*Version 2003 (Build 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1781">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="b48ee-1782">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="b48ee-1782">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)
### <a name="feature-updates"></a><span data-ttu-id="b48ee-1784">Funktionsupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1784">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1785">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1785">Excel</span></span>
- <span data-ttu-id="b48ee-1786">**Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1786">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="b48ee-1787">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-1787">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="powerpoint"></a><span data-ttu-id="b48ee-1788">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1788">PowerPoint</span></span>
- <span data-ttu-id="b48ee-1789">**Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1789">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="b48ee-1790">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-1790">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="word"></a><span data-ttu-id="b48ee-1791">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1791">Word</span></span>
- <span data-ttu-id="b48ee-1792">**Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1792">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="b48ee-1793">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b48ee-1793">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1794">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1794">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1795">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1795">Excel</span></span>

- <span data-ttu-id="b48ee-1796">Ein kosmetisches Problem wurde behoben, bei dem die Schaltfläche "OK" im Dialogfeld "Datei\Optionen" abgeblendet angezeigt, die Funktionalität aber nicht beeinträchtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1796">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="b48ee-1797">Es wurde ein Problem behoben, das möglicherweise beim Umbenennen von Pivot-Tabellenmaßen aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1797">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="b48ee-1798">Ein Problem wurde behoben, bei dem der Text in einem Datenschnitt in der Druckvorschau nicht ordnungsgemäß skaliert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1798">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="b48ee-1799">Es wurde ein Leistungsproblem behoben, das möglicherweise bei der Verwendung eines VBA-Makros zum Löschen des Inhalts eines Bereichs aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1799">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="b48ee-1800">Es wurde ein Problem behoben, das zum Blinken der Benutzeroberfläche führte, wenn Benutzer ein Makro ausführten, das mit dem Menüband interagierte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1800">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="b48ee-1801">Es wurde ein Problem behoben, bei dem CSV-Dateien falsch geladen wurden, wenn das erste Wort in der Datei TABLE lautete.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1801">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="b48ee-1802">Es wurde ein Problem behoben, bei dem es zu Abstürzen kommen konnte, wenn Benutzer zwischen zwei Arbeitsmappen mit unterschiedlichen Zoomstufen wechselten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1802">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="b48ee-1803">Ein Problem wurde behoben, bei dem CUBEWERT-Funktionen manchmal ein falsches Ergebnis zurückgaben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1803">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="b48ee-1804">Diese Änderung behebt einen Laufzeitfehler im Objektmodell und verhindert einen möglichen Absturz der App (Excel, Word), wenn Add-Ins nach Hostelementen in Dokumenten/Arbeitsblättern fragen, die Formen mit noSelect-Sperren enthalten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1804">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="b48ee-1805">Behebt ein Problem, durch das Outlook beim Synchronisieren der Einstellungen abstürzte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1805">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="b48ee-1806">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1806">Outlook</span></span>

- <span data-ttu-id="b48ee-1807">Ein Problem wurde behoben, bei dem das Erstellen einer Regel mit Outlook Web App auf dem Exchange-Server nicht beibehalten werden konnte und zu einem Konflikt geführt hat.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1807">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="b48ee-1808">Es wurde ein Problem behoben, durch das Outlook beim Synchronisieren der Einstellungen abstürzte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1808">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="b48ee-1809">Es wurde ein Problem mit Outlook im dunklen Modus behoben, wird möglicherweise die Dropdownliste im Feld "Von:" nicht angezeigt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1809">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="b48ee-1810">Es wurde ein Problem behoben, das dazu führte, dass Outlook in einigen Szenarien unerwartet Protokollausgaben erzeugte, selbst wenn die Protokollierung ausgeschaltet war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1810">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="b48ee-1811">Es wurde ein Problem behoben, das dazu führte, dass Benutzer keine Nachrichten in öffentlichen Ordnern öffnen konnten, wenn Outlook über Nacht laufen gelassen wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1811">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="b48ee-1812">Es wurde eine Racebedingung behoben, bei der die Schaltflächen "Zulassen" und "Verweigern" auf der Seite "Berechtigungen" während des Authentifizierungsworkflows beim Hinzufügen eines Google Mail-Kontos deaktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1812">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="b48ee-1813">Ein Problem wurde behoben, durch das Benutzer den Zugriff auf das Dialogfeld &quot;Frei/Gebucht-Optionen&quot; der Kalenderberechtigungen verloren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1813">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="b48ee-1814">Es wurde ein Problem behoben, das zur Warnung &quot;Leider besteht ein Problem beim Öffnen dieses Elements&quot; führen kann, wenn Sie bestimmte Besprechungsserien-Instanzen öffnen, die aus einer anderen Zeitzone gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1814">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="b48ee-1815">Es wurde ein Problem behoben, durch das Benutzer eine MSG-Datei möglicherweise nicht mehr öffnen können, nachdem die eine Anlage aus dieser Nachricht durch Ziehen und Ablegen verschoben haben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1815">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="b48ee-1816">Ein Problem wurde behoben, bei dem der Dateiname nach dem Hochladen einer Dateianlage aus Outlook nach OneDrive möglicherweise geändert wird, wenn der Name der Anlage eine Klammer enthält.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1816">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="b48ee-1817">Es wurde ein Problem behoben, durch das Benutzer über den Datei-Explorer eine Datei nicht als Anlage zu einer E-Mail-Nachricht hinzufügen konnten, wenn diese Datei in einer anderen Anwendung geöffnet war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1817">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="b48ee-1818">Es wurde ein Problem behoben, durch das Outlook beim Synchronisieren der Einstellungen abstürzte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1818">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b48ee-1819">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1819">PowerPoint</span></span>

- <span data-ttu-id="b48ee-1820">Ein Problem wurde behoben, bei dem die empfohlenen Miniaturansichten blinkten, wenn Sie mit der Maus auf die Miniaturansichten gingen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1820">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="b48ee-1821">In einigen Fällen kann dies dazu führen, dass PowerPoint abstürzt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1821">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="b48ee-1822">Ein kosmetisches Problem wurde behoben, bei dem die Schaltfläche "OK" im Dialogfeld "Datei\Optionen" abgeblendet angezeigt, die Funktionalität aber nicht beeinträchtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1822">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="b48ee-1823">Es wurde ein Problem behoben, das dazu führen konnte, dass ein Dokument, das ein Excel-Diagramm enthält, nicht in PowerPoint oder Word gespeichert werden konnte.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1823">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="b48ee-1824">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-1824">Project</span></span>

- <span data-ttu-id="b48ee-1825">Ein Problem wurde behoben, bei dem "Vorgang Prozent abgeschlossen" fälschlicherweise in einen Wert kleiner als 100 % geändert wurde, nachdem der Vorgang als abgeschlossen gekennzeichnet wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1825">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="b48ee-1826">Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1826">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="b48ee-1827">Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1827">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="b48ee-1828">Visio</span><span class="sxs-lookup"><span data-stu-id="b48ee-1828">Visio</span></span>

- <span data-ttu-id="b48ee-1829">Im Shape-Infobereich wurden im Abschnitt "Shapedaten" inkonsistente Details zur Datei angezeigt, wenn diese in Visio Desktop angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1829">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="b48ee-1830">Dieses Problem wurde jetzt behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1830">It has now been fixed.</span></span>

- <span data-ttu-id="b48ee-1831">In Versionen vor 2016 importierte Bitmaps wurden aufgrund einiger Sicherheitsüberprüfungen nicht wiedergegeben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1831">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="b48ee-1832">Dieses Problem wurde im Visio-Abonnement behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1832">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-1833">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1833">Word</span></span>

- <span data-ttu-id="b48ee-1834">Es wurde ein Problem behoben, bei dem Kommentarkarten nicht immer hervorgehoben werden, wenn der Mauszeiger über die Kommentarkarte bewegt wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1834">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="b48ee-1835">Behebt ein Problem, das dazu geführt hat, dass beim Navigieren über eine Kommentarkarte mit der Tabulatortaste der Fokus auf dem Bearbeitungsfeld für den Kommentar nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1835">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="b48ee-1836">Ein kosmetisches Problem wurde behoben, bei dem die Schaltfläche "OK" im Dialogfeld "Datei\Optionen" abgeblendet angezeigt, die Funktionalität aber nicht beeinträchtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1836">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="b48ee-1837">Während einer aktiven Sitzung zur gemeinsamen Dokumenterstellung kann das direkte Hinzufügen eines Bildes in eine Kommentarkarte dazu führen, dass ein Tag hinzugefügt wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1837">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="b48ee-1838">Das Problem wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1838">This issue has been fixed.</span></span>

- <span data-ttu-id="b48ee-1839">Das Einfügen eines Steuerelements (beispielsweise eines Textinhaltssteuerelements) in eine Gleichung und das anschließende Speichern und Öffnen der Datei führte zu einem Fehler aufgrund nicht lesbaren Inhalts.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1839">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="b48ee-1840">Ein Problem wurde behoben, aufgrund dessen das Speichern einer zuvor kennwortgeschützten Datei in einem Cloudspeicher nicht funktioniert hat.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1840">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="b48ee-1841">Es wurde ein Problem mit der compare-Funktion für Dokumente behoben, die für die Bearbeitung geschützt waren.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1841">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="b48ee-1842">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-1842">Office Suite</span></span>

- <span data-ttu-id="b48ee-1843">Beim Verwenden der Metadateneigenschaften MultiChoice/Verweis/Verwaltet mit Word/Excel/PowerPoint-Dokumenten und dem Speichern in einer SharePoint-Dokumentbibliothek waren diese Eigenschaften bisher auf 255 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1843">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="b48ee-1844">Wenn diese Eigenschaften 255 Zeichen überschritten, konnten solche Dokumente nicht gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1844">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="b48ee-1845">Mit dieser Änderung wurde dieser Grenzwert auf 2048 Zeichen erhöht.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1845">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="b48ee-1846">Behebt ein Problem mit Word/Excel/PowerPoint, bei dem der User-Principal-Name (UPN) nicht mehr die Groß-/Kleinschreibung beachtet, was zu weniger Fehlern beim Arbeiten mit Dateien in SharePoint führt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1846">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="b48ee-1847">Ein Problem wurde behoben, das dazu führte, dass beim Öffnen mehrerer Dokumente in Word/Excel/PowerPoint aus derselben SharePoint-Bibliothek lediglich das erste geöffnete Dokument auf Richtlinienkonformität gescannt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1847">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (BUGDETAILS NICHT AM INHALTSENDE ENTFERNEN)

## <a name="version-2002-march-05"></a><span data-ttu-id="b48ee-1849">Version 2002: 05. März</span><span class="sxs-lookup"><span data-stu-id="b48ee-1849">Version 2002: March 05</span></span>
<span data-ttu-id="b48ee-1850">*Version 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1850">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="b48ee-1851">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1851">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="b48ee-1852">Version 2002: 04. März</span><span class="sxs-lookup"><span data-stu-id="b48ee-1852">Version 2002: March 04</span></span>
<span data-ttu-id="b48ee-1853">*Version 2002 (Build 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1853">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1855">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1855">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="b48ee-1856">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-1856">Project</span></span>
- <span data-ttu-id="b48ee-1857">Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1857">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b48ee-1858">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-1858">Office Suite</span></span>
- <span data-ttu-id="b48ee-1859">Behebt ein Problem, das dazu geführt hat, dass beim Öffnen mehrerer Dokumente in Word/Excel/PowerPoint aus derselben SharePoint-Bibliothek lediglich das erste geöffnete Dokument auf Richtlinienkonformität gescannt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1859">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSWENDE)

## <a name="version-2002-march-01"></a><span data-ttu-id="b48ee-1861">Version 2002: 01. März</span><span class="sxs-lookup"><span data-stu-id="b48ee-1861">Version 2002: March 01</span></span>
<span data-ttu-id="b48ee-1862">*Version 2002 (Build 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1862">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1863">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1863">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-1864">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1864">Outlook</span></span>

- <span data-ttu-id="b48ee-1865">Behebt ein Problem, das bewirkt hatte, dass Anwendungen von Drittanbietern keine E-Mail-Nachrichten mehr senden konnten.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1865">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2002-february-24"></a><span data-ttu-id="b48ee-1867">Version 2002: 24. Februar</span><span class="sxs-lookup"><span data-stu-id="b48ee-1867">Version 2002: February 24</span></span>
<span data-ttu-id="b48ee-1868">*Version 2002 (Build 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1868">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="b48ee-1869">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1869">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="b48ee-1870">Version 2002: 22. Februar</span><span class="sxs-lookup"><span data-stu-id="b48ee-1870">Version 2002: February 22</span></span>
<span data-ttu-id="b48ee-1871">*Version 2002 (Build 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1871">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="b48ee-1872">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1872">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="b48ee-1873">Version 2002: 21. Februar</span><span class="sxs-lookup"><span data-stu-id="b48ee-1873">Version 2002: February 21</span></span>
<span data-ttu-id="b48ee-1874">*Version 2002 (Build 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1874">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1876">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1876">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="b48ee-1877">Zugriff</span><span class="sxs-lookup"><span data-stu-id="b48ee-1877">Access</span></span>

- <span data-ttu-id="b48ee-1878">**Seien Sie beim Arbeiten im Abfrage-Designer, in der SQL-Ansicht und im Fenster „Beziehungen“ produktiver:** Klicken Sie zum Öffnen, Gestalten, Vergrößern oder Verkleinern und Ausblenden mit der rechten Maustaste auf die betreffende Tabelle.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1878">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="b48ee-1879">Suchen und Ersetzen von Text in der SQL-Ansicht.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1879">Search and replace text in SQL View.</span></span> <span data-ttu-id="b48ee-1880">Auswählen mehrerer Tabellen im Fenster „Beziehungen“.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1880">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1881">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1881">Outlook</span></span>

- <span data-ttu-id="b48ee-1882">**Neue Benutzeroberfläche für WLAN-Netzwerke mit Anmeldung:** Sind Sie schon einmal einem WLAN-Netzwerk beigetreten, mit dem Sie sich anmelden mussten?</span><span class="sxs-lookup"><span data-stu-id="b48ee-1882">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="b48ee-1883">Outlook erkennt dies jetzt und hilft Ihnen, eine Verbindung zu herstellen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1883">Outlook now detects this and helps you get connected.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1886">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1886">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b48ee-1887">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1887">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="b48ee-1888">Ein Problem wurde behoben, bei dem CUBEWERT-Funktionen manchmal ein falsches Ergebnis zurückgaben.&nbsp;<span style="display:inline !important;"></span></span><span class="sxs-lookup"><span data-stu-id="b48ee-1888">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;<span style="display:inline !important;"></span></span></span><br>


### <a name="outlook"></a><span data-ttu-id="b48ee-1889">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1889">Outlook</span></span>

- <span data-ttu-id="b48ee-1890">Behebt ein Problem, das dazu führte, dass Kommas im Ortsfeld einer Besprechung in Semikolons umgewandelt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1890">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>


- <span data-ttu-id="b48ee-1891">Behebt ein Problem, das zu einem Absturz führen könnte, wenn dasselbe Element in mehreren Fenstern angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1891">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>


- <span data-ttu-id="b48ee-1892">Behebt ein Problem, das dazu führte, dass Outlook unerwartet alle E-Mails synchronisierte, selbst wenn der Synchronisierungsschieberegler auf eine kleinere Einstellung eingestellt ist.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="b48ee-1892">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span>


- <span data-ttu-id="b48ee-1893">Behebt ein Problem, das dazu führte, dass für Benutzer mit dem schwarzen Design die Dropdownliste &quot;Von&quot; als weißer Text auf weißem Hintergrund angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1893">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>


- <span data-ttu-id="b48ee-1894"><span style="display:inline !important;">Diese Änderung stellt die Fähigkeit wieder her, mehrzeilige Betreffzeilen im Nachrichtenkopf anzuzeigen.</span></span><span class="sxs-lookup"><span data-stu-id="b48ee-1894"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-february-18"></a><span data-ttu-id="b48ee-1896">Version 2002: 18. Februar</span><span class="sxs-lookup"><span data-stu-id="b48ee-1896">Version 2002: February 18</span></span>
<span data-ttu-id="b48ee-1897">*Version 2002 (Build 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1897">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="b48ee-1898">Version 2002: 11. Februar</span><span class="sxs-lookup"><span data-stu-id="b48ee-1898">Version 2002: February 11</span></span>
<span data-ttu-id="b48ee-1899">*Version 2002 (Build 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="b48ee-1899">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="b48ee-1900">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="b48ee-1900">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b48ee-1902">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b48ee-1902">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b48ee-1903">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1903">Outlook</span></span>

- <span data-ttu-id="b48ee-1904">**Ziehen Sie E-Mails in eine Gruppe, die Sie besitzen:** Verschieben und Kopieren von Nachrichten und Unterhaltungen, indem Sie diese aus Ihrem Posteingang ziehen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1904">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="b48ee-1905">Die von ihnen gezogenen Nachrichten werden für alle Gruppenmitglieder freigegeben.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1905">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="b48ee-1906">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1906">Word</span></span>

- <span data-ttu-id="b48ee-1907">**Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1907">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b48ee-1908">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-1908">Office Suite</span></span>

- <span data-ttu-id="b48ee-1909">**Übersichtlichere Statusleistensymbole:** Statusleistensymbole sind jetzt einfacher zu sehen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1909">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b48ee-1912">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b48ee-1912">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b48ee-1913">Zugriff</span><span class="sxs-lookup"><span data-stu-id="b48ee-1913">Access</span></span>

- <span data-ttu-id="b48ee-1914">Access-Vorlagen sollten nicht länger dazu führen, dass Anhangsspalten in einer Datenbank fehlschlagen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1914">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="b48ee-1915">Nachdem Sie eine Vorlage instanziiert haben, sollten Sie nun in der Lage sein, Ihrer Datenbank ein Anhangsfeld hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1915">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="b48ee-1916">Dieses Update behebt ein Problem bei der Verwendung von ADODB.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1916">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="b48ee-1917">Das Recorder-Objekt im VB-Code meldet möglicherweise einen Fehler falsch.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1917">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="b48ee-1918">Dieses Update behebt ein Problem, das dazu führen kann, dass Microsoft Access eine Identitätsspalte in einer verknüpften SQL-Server-Tabelle nicht identifiziert, was dazu führen kann, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1918">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="b48ee-1919">Excel</span><span class="sxs-lookup"><span data-stu-id="b48ee-1919">Excel</span></span>

- <span data-ttu-id="b48ee-1920">Es wurde ein Problem behoben, bei dem Kommentarbefehle im Kontextmenü nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1920">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="b48ee-1921">Es wurde ein Problem behoben, durch das bei einigen Nutzern Abstürze auftraten, wenn Text in Spalten mit Zellen mit einem übergelaufenem Array konvertiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1921">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="b48ee-1922">Ein Problem wurde behoben, das dazu geführt hatte, dass Excel bei Verschieben von Text in Spalten mit dynamischen Pfeilern abgestürzt ist.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1922">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="b48ee-1923">Outlook</span><span class="sxs-lookup"><span data-stu-id="b48ee-1923">Outlook</span></span>

- <span data-ttu-id="b48ee-1924">Ein Problem wurde behoben, das dazu geführt hatte, dass beim Durchblättern des Kalanders in der Monatsansicht die vorangegangenen Kalenderereignisse nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1924">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="b48ee-1925">Ordner, die unter "Favoriten" im linken Navigationsbereich gespeichert sind, können zeitweise verschwinden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1925">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="b48ee-1926">Es wurde ein Problem behoben, bei dem beim Angeben einer ungültigen Absenderadresse ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1926">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="b48ee-1927">Es wurde ein Problem behoben, durch das die Option zum Deaktivieren der Hervorhebung markierter Elemente in einigen Szenarien nicht berücksichtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1927">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="b48ee-1928">Es wurde ein Problem behoben, bei dem es durch das Abbrechen der Kontoeinrichtung einen Absturz gab.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1928">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="b48ee-1929">Problem behoben, bei dem für auf Grundlage einer Aufbewahrungsrichtlinie ablaufende E-Mails zwei Beschriftungen angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1929">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="b48ee-1930">Eine mit der Aussage, dass die E-Mail in einem Tag, die andere, dass die E-Mail in zwei Tagen abläuft.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1930">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="b48ee-1931">Es wurde ein Problem behoben, bei dem beim Anzeigen von mehr als 30 Kalendern in einer Citrix-Umgebung ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1931">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b48ee-1932">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b48ee-1932">PowerPoint</span></span>

- <span data-ttu-id="b48ee-1933">Ein Problem wurde behoben, bei dem Freihandelemente in einer PowerPoint-Freihandanimation nicht vollständig gerendert wurde oder übersprungen wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1933">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="b48ee-1934">Ein Problem wurde behoben, das dazu geführt hatte, dass PowerPoint Nach dem Schließen einer Datei diese nicht sofort aus der Sammlung von Präsentationen entfernt hat, wenn Ereignisverarbeiter ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1934">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="b48ee-1935">Dadurch war die Zahl der vom Objektmodell gemeldeten, geöffneten Präsentationen falsch und das Herunterfahren von PowerPoint wurde verhindert.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1935">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="b48ee-1936">Ein Problem mit dem Textmarker wurde behoben: Weißer Text mit dunkleren Textmarkerfarben wurde Schwarz mit Graustufen gedruckt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1936">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="b48ee-1937">Project</span><span class="sxs-lookup"><span data-stu-id="b48ee-1937">Project</span></span>

- <span data-ttu-id="b48ee-1938">Es wurde ein Problem behoben, bei dem 100% Aufgaben vom Typ „feste Dauer“ fälschlicherweise zu weniger als 100% erledigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1938">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="b48ee-1939">Word</span><span class="sxs-lookup"><span data-stu-id="b48ee-1939">Word</span></span>

- <span data-ttu-id="b48ee-1940">Beim Aktualisieren eines Inhaltsverzeichnisses bzw. dem Blättern durch dieses wird manchmal möglicherweise ein grauer Bereich auf dem Dokument angezeigt.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1940">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="b48ee-1941">Es wurde ein Problem mit der Verwendung von „Durchsuchen“ zum Speichern einer Datei behoben, das nicht funktioniert hat, wenn ein Kommentar geschrieben, jedoch nicht gepostet worden war und der Benutzer versucht hatte, die Datei zu speichern.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1941">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="b48ee-1942">Ein Problem wurde behoben, das dazu geführt hatte, dass beim Hin- und Herwechseln zwischen Kommentar-Karten manchmal der anfänglich ausgewählte Kommentar mit einer Auswahlhervorhebung angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1942">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="b48ee-1943">Es wurde ein Problem behoben, bei dem die kursive Formatierung verloren ging, nachdem ein Kommentar bearbeitet, der Text kursiv geschrieben und anschließend veröffentlicht wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1943">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="b48ee-1944">Problem behoben, bei dem ein Kommentarhinweis im Lesemodus mit Inverser Seitenfarbe nicht sichtbar war.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1944">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="b48ee-1945">Ein Problem wurde behoben, bei dem die Entwurfsversion eines Stammkommentars bei der gemeinsamen Dokumenterstellung zeitweise nicht beibehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1945">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="b48ee-1946">Wenn „SlideTrack“ aktiviert und der Bereich „Kommentare“ geschlossen ist, kann der Bereich „Kommentare“ mit STRG+ALT+M möglicherweise nicht geöffnet werden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1946">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="b48ee-1947">Es wurde ein Problem behoben, das dazu geführt hatte, dass beim Hinzufügen von @mention in einer Tabelle die Fehlermeldung „Eine Tabelle in diesem Dokument ist beschädigt“ generiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1947">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="b48ee-1948">Problem behoben, bei dem Kommentarbefehle (Kommentar bearbeiten, auf Kommentar antworten, Kommentar löschen, Kommentar auflösen) nicht im Kontextmenü von Kommentaren angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1948">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b48ee-1949">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b48ee-1949">Office Suite</span></span>

- <span data-ttu-id="b48ee-1950">Behebt ein Problem, das dazu geführt hat, dass Korrekturhilfe-Paket Norwegen Nynorsk (nn-no) nicht ordnungsgemäß installiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1950">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="b48ee-1951">Diese Änderung behebt gemeldete Probleme mit Grafikadaptern, die die integrierte Intel-GPU nutzen.</span><span class="sxs-lookup"><span data-stu-id="b48ee-1951">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)


---
title: Versionshinweise Aktueller Kanal (Vorschau)
ms.author: anankani
author: anankani
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Für die Zielgruppe von Insider Slow die aktuelle Liste neuer Features, Fehlerkorrekturen oder bekannter Probleme bereitstellen
ms.openlocfilehash: 712501114acb6e1a14ae8f0c55727ac3e504afe1
ms.sourcegitcommit: ad3ff8ea83a9930956cbb6f30300b0b57d3ef151
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/09/2021
ms.locfileid: "52851845"
---
# <a name="release-notes-for-office-current-channel-preview"></a><span data-ttu-id="03067-103">Versionshinweise für Office Aktueller Kanal (Vorschau)</span><span class="sxs-lookup"><span data-stu-id="03067-103">Release Notes for Office Current Channel (Preview)</span></span>

<span data-ttu-id="03067-104">Dieser Artikel enthält Versionshinweise zu Builds von Word, Excel, PowerPoint, Outlook, Access, Project und Teams für Windows-Desktop für den aktuellen Kanal (Vorschau).</span><span class="sxs-lookup"><span data-stu-id="03067-104">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, Project, and Teams for Windows desktop.</span></span> <span data-ttu-id="03067-105">Jede Woche heben wir interessante neuer Features, wichtige Fixes und wesentliche Probleme hervor, über die wir Sie gerne informieren möchten.</span><span class="sxs-lookup"><span data-stu-id="03067-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="03067-106">Bitte beachten Sie, dass wir Features (und häufig auch Fixes) häufig über einen Zeitraum in den aktuellen Kanal (Vorschau) einführen.</span><span class="sxs-lookup"><span data-stu-id="03067-106">Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time.</span></span> <span data-ttu-id="03067-107">Auf diese Weise können wir sicherstellen, dass alles reibungslos funktioniert, bevor das Feature für ein breiteres Publikum bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="03067-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="03067-108">Wenn also im Folgenden etwas nicht beschrieben wird, machen Sie sich keine Sorgen, es wird bald behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="03067-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  


> [!NOTE]
> - <span data-ttu-id="03067-109">Das Veröffentlichungsdatum der Versionshinweise stimmt möglicherweise nicht mit dem tatsächlichen Veröffentlichungsdatum des Builds überein.</span><span class="sxs-lookup"><span data-stu-id="03067-109">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="03067-110">Microsoft Teams-Features unterscheiden sich möglicherweise von den neuesten veröffentlichten Features der aktuellen Kanalvorschau, da sie einen häufigeren Versionswechsel aufweisen.</span><span class="sxs-lookup"><span data-stu-id="03067-110">Microsoft Teams features may differ from the latest Current Channel Preview released as they have a more frequent release cadence.</span></span>

[//]: # (NICHT ENTFERNEN)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

## <a name="version-2106-june-07"></a><span data-ttu-id="03067-113">Version 2106: 07. Juni</span><span class="sxs-lookup"><span data-stu-id="03067-113">Version 2106: June 07</span></span>
<span data-ttu-id="03067-114">*Version 2106 (Build 14131.20012)*</span><span class="sxs-lookup"><span data-stu-id="03067-114">*Version 2106 (Build 14131.20012)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-116">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-116">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-117">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-117">Excel</span></span>

- <span data-ttu-id="03067-118">Ein Problem wurde behoben, das verhinderte, dass der Namens-Manager Bücher mit einer großen Anzahl von ausgeblendeten Namen öffnete.</span><span class="sxs-lookup"><span data-stu-id="03067-118">We fixed an issue that prevented the Name Manager from opening books with a large number of hidden names.</span></span>


- <span data-ttu-id="03067-119">Es wurde ein Problem behoben, das Auswirkungen auf die Leistung von VLOOKUP und INDEX/MATCH beim Ausfüllen einer großen Datenmenge hatte.</span><span class="sxs-lookup"><span data-stu-id="03067-119">We fixed an issue that impacted the performance of VLOOKUP and INDEX/MATCH when filling a large amount of data.</span></span>


- <span data-ttu-id="03067-120">Es wurde ein Problem behoben, das dazu führte, dass Dynamische Arrays Zellwerte nicht aktualisierten, wenn von RealTimeData-Funktionen darauf verwiesen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-120">We fixed an issue that caused Dynamic Arrays to not update cell values when referenced by RealTimeData functions.</span></span>


- <span data-ttu-id="03067-121">Es wurde ein Problem behoben, bei dem im IME-Überschreibmodus Zeichen nicht überschrieben wurden, sondern am Ende der Zeichenfolge eingefügt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-121">Fixed an issue where IME's OverType mode was not typing over characters, it left them at the end of the string.</span></span>


- <span data-ttu-id="03067-122">Wir haben ein Problem im Zusammenhang mit dem Scrollen mit zwei Fingern beim Fixieren von Fensterbereichen behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-122">We fixed an issue related to two-finger scrolling when using freeze panes.</span></span>


- <span data-ttu-id="03067-123">Wir haben ein Problem im Zusammenhang mit Problemen mit nicht ausreichendem Arbeitsspeicher beim Drucken auf Großformatdruckern behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-123">We fixed an issue related to out of memory issues when printing on large-format printers.</span></span>


### <a name="outlook"></a><span data-ttu-id="03067-124">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-124">Outlook</span></span>

- <span data-ttu-id="03067-125">Wir haben ein Problem behoben, durch das beim Ausführen des Modus "Nur Kopfzeilen herunterladen" Aktionen erfordernde Nachrichten entweder ständig aktualisiert oder wieder zu Kopfzeilen zurückkonvertiert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-125">We fixed an issue that caused users to see actionable messages either constantly refreshing or reverting back to headers after download when running in Download Headers Only mode.</span></span>


- <span data-ttu-id="03067-126">Es wurde ein Problem behoben, bei dem Benutzer in "nicht geschäftlich" lizenzierten Outlook-Versionen keine Elemente zwischen Ordnern verschieben konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-126">We fixed an issue where users were unable to move items across folders in "non-business" licensed Outlook versions.</span></span>


- <span data-ttu-id="03067-127">Ein Problem wurde behoben, das dazu führte, dass Outlook unerwartet geschlossen wurde, wenn Benutzer Ordner aus einem Archivspeicher entfernten.</span><span class="sxs-lookup"><span data-stu-id="03067-127">We fixed an issue that caused users to experience a unexpected close when removing folders from an archive store.</span></span>


- <span data-ttu-id="03067-128">Es wurde ein Problem behoben, das dazu führte, dass Outlook bei einigen Benutzern beim Laden von Personenkarten unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-128">We fixed an issue that caused some users to experience a unexpected close when loading person cards.</span></span>


- <span data-ttu-id="03067-129">Wir haben ein Problem behoben, durch das die Personenauswahl in Outlook für Benutzer mit einer unbefristeten Lizenz eher nach oben als nach unten erweitert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-129">We fixed an issue that caused the people picker in Outlook to expand upwards rather than downwards for users with a perpetual license.</span></span>


- <span data-ttu-id="03067-130">Wir haben ein Problem behoben, durch das die Feedback-Option für Benutzer der Office Dauerlizenz 2021-Vorschau nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-130">We fixed an issue that caused the feedback option to fail to appear for users of the Office Perpetual 2021 preview.</span></span>


- <span data-ttu-id="03067-131">Ein Problem wurde behoben, das dazu führte, dass Benutzern Kopien all ihrer gesendeten Elemente in ihrem Postausgangsordner angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-131">We fixed an issue that caused users to see copies of all of their sent items appearing in their Outbox folder.</span></span>


- <span data-ttu-id="03067-132">Wir haben ein Problem behoben, durch das Benutzern benutzerdefinierter Domänen beim Einfügen eines Links in eine E-Mail-Nachricht eine Warnmeldung zu Berechtigungen angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-132">We fixed an issue that caused users of custom domains to see a warning message about permissions when pasting a link into an email message.</span></span>


- <span data-ttu-id="03067-133">Es wurde ein Registrierungsschlüssel hinzugefügt, mit dem die neue Benutzeroberfläche der Raumsuche (dieselbe Benutzeroberfläche wie in Outlook für Web) deaktiviert und die Vorgängerversion der Raumsuche mit "Vorgeschlagene Zeiten" aktiviert wird.</span><span class="sxs-lookup"><span data-stu-id="03067-133">We added a registry key that disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with Suggested Times.</span></span>

    <span data-ttu-id="03067-134">Registrierungsschlüssel:</span><span class="sxs-lookup"><span data-stu-id="03067-134">Registry Key:</span></span>

    ><span data-ttu-id="03067-135">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span><span class="sxs-lookup"><span data-stu-id="03067-135">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span></span> </br>
    > <span data-ttu-id="03067-136">REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="03067-136">REG_DWORD “ShowLegacyRoomFinder”</span></span></br></br>
    > <span data-ttu-id="03067-137">0 (Standard) – Outlook verwendet die neue von OWA unterstützte Benutzeroberfläche für die Raumsuche, wenn der Benutzer auf die Schaltfläche „Raumsuche“ klickt, um nach verfügbaren Räumen zu suchen</span><span class="sxs-lookup"><span data-stu-id="03067-137">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span>  </br>
    > <span data-ttu-id="03067-138">1 – Outlook verwendet die ältere Benutzeroberfläche der Raumsuche, um nach verfügbaren Räumen zu suchen</span><span class="sxs-lookup"><span data-stu-id="03067-138">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span> </br>


- <span data-ttu-id="03067-139">Ein Problem wurde behoben, das dazu führte, dass Outlook unerwartet geschlossen wurde, wenn lautes Vorlesen mit anderen Versionen von Windows verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-139">We fixed an issue that caused an expected close when using read aloud with other versions of Windows.</span></span>


- <span data-ttu-id="03067-140">Ein Problem wurde behoben, das dazu führte, dass Outlook nicht mehr reagierte, wenn Benutzer Ordner aus einem Archivspeicher entfernten.</span><span class="sxs-lookup"><span data-stu-id="03067-140">We fixed an issue that caused users to experience a hang when removing folders from an archive store.</span></span>


- <span data-ttu-id="03067-141">Es wurde ein Problem behoben, das bei einigen Benutzern beim Laden von Personenkarten zu einem unerwarteten Absturz führte.</span><span class="sxs-lookup"><span data-stu-id="03067-141">We fixed an issue that caused some users to experience a crash when loading person cards.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="03067-142">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-142">PowerPoint</span></span>

- <span data-ttu-id="03067-143">Wir haben ein Problem behoben, durch das das Kopieren aus dem Sprechernotizenbereich im Schreibgeschützten Modus verhindert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-143">We fixed an issue that prevented copying from the speaker notes pane while in Read Only mode.</span></span>


- <span data-ttu-id="03067-144">Ein Problem wurde behoben, um sicherzustellen, dass eine Datei, die über die Schaltfläche „Speichern wiederholen“ in der Busleiste gespeichert wurde, zur Liste „Zuletzt verwendet“ hinzugefügt wird.</span><span class="sxs-lookup"><span data-stu-id="03067-144">We fixed an issue to ensure that a file saved using the Retry Save button on the bus bar is added to the Recent List.</span></span>


- <span data-ttu-id="03067-145">Es wurde ein Problem behoben, bei dem die Option „Folien wiederverwenden“ für wenige Benutzer nicht verfügbar war.</span><span class="sxs-lookup"><span data-stu-id="03067-145">Fixed an issue where Reuse Slides option was not available for few users.</span></span>


### <a name="project"></a><span data-ttu-id="03067-146">Project</span><span class="sxs-lookup"><span data-stu-id="03067-146">Project</span></span>

- <span data-ttu-id="03067-147">Es wurde ein Problem behoben, bei dem Zuordnungen zu manuell geplanten Vorgängen auf ein falsches Datum verschoben werden konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-147">We fixed an issue where assignments on manually scheduled tasks could be moved to an incorrect date.</span></span>


- <span data-ttu-id="03067-148">Es wurde ein Problem behoben, bei dem der Ressourcenpool nicht antwortete und nicht geöffnet werden konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-148">We fixed an issue where the resource pool was unresponsive and couldn't be opened.</span></span>


- <span data-ttu-id="03067-149">Es wurde ein Problem behoben, bei dem ein Fehler erzeugt wurde, wenn Sie eine benutzerdefinierte Feldformel erstellt haben, welche die Funktionen ProjectDate */ProjectDur* mit bestimmten Datums- oder Zeitparametern verwendet hat.</span><span class="sxs-lookup"><span data-stu-id="03067-149">We fixed an issue where an error was generated if you created a custom field formula that used the ProjectDate */ProjectDur* functions with specific date or time parameters.</span></span>


### <a name="word"></a><span data-ttu-id="03067-150">Word</span><span class="sxs-lookup"><span data-stu-id="03067-150">Word</span></span>

- <span data-ttu-id="03067-151">Behebung eines Problems, bei dem ein Kommentar nach dem Posten vorübergehend leer war.</span><span class="sxs-lookup"><span data-stu-id="03067-151">Fixes an issue where a  comment is temporarily blank after posting.</span></span>


- <span data-ttu-id="03067-152">Wir haben ein Problem behoben, bei dem eine „Speichern unter“-Fehlermeldung selbst dann angezeigt wurde, wenn ein Benutzer Änderungen verworfen hat.</span><span class="sxs-lookup"><span data-stu-id="03067-152">We fixed an issue where a Save As error message was displayed even after a user chose to discard changes.</span></span>


- <span data-ttu-id="03067-153">Wir haben ein Problem behoben, das das Posten von Bildern in modernen Kommentaren verhindert hatte.</span><span class="sxs-lookup"><span data-stu-id="03067-153">We fixed an issue that prevented images from being posted in modern comments.</span></span>


- <span data-ttu-id="03067-154">Wir haben ein Problem behoben, bei dem durch Drücken von Tastenkombinationen wie STRG+UMSCHALT+@ nicht der erwartete Akzentbuchstabe (in diesem Fall "å") erzeugt würde.</span><span class="sxs-lookup"><span data-stu-id="03067-154">We fixed an issue where pressing key combinations such as ctrl + shift + @ would not produce the expected accented character( in this case, 'å').</span></span>


- <span data-ttu-id="03067-155">Es wurde ein Problem mit der Bildkomprimierung behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-155">We fixed an issue related to image compression.</span></span>


- <span data-ttu-id="03067-156">Es wurde ein Problem behoben, bei dem der Überarbeitungsbereich scrollte oder zu scrollen schien, aber nicht an dem ausgewählten Kommentar ausgerichtet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-156">We fixed an issue where the Reviewing pane could scroll or appear to scroll but didn't align with selected comment.</span></span>


- <span data-ttu-id="03067-157">Es wurde ein Problem behoben, bei dem einige Kommentare beim Exportieren eines Dokuments nach PDF nicht gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-157">We fixed an issue where some comments were not saved when exporting a document to PDF.</span></span>


- <span data-ttu-id="03067-158">Es wurde ein Problem behoben, das die Bearbeitung eines neuen Kommentars in einem ungeschützten Bereich eines Dokuments verhinderte, wenn „Eingeschränktes Bearbeiten“ angewendet ist.</span><span class="sxs-lookup"><span data-stu-id="03067-158">We fixed an issue that prevented the editing of a new comment in an unprotected area of a document when Restricted Editing is applied.</span></span>


- <span data-ttu-id="03067-159">Es wurde ein Problem im Zusammenhang mit einer nicht benötigten Bildlaufanimation wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-159">We fixed an issue related to unneeded scrolling animation.</span></span>


- <span data-ttu-id="03067-160">Es wurde ein Problem behoben, bei dem der Kommentarbereich unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-160">Fixed an issue where the comments pane closed unexpectedly.</span></span>


- <span data-ttu-id="03067-161">Es wurde ein Problem behoben, bei dem Kommentare nicht hervorgehoben wurden, wenn sie ausgewählt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-161">We fixed an issue where comments aren't highlighted when selected.</span></span>


- <span data-ttu-id="03067-162">Wir haben ein Problem behoben, durch das die Auswahl in einem Dokument beim Klicken außerhalb eines neu erstellten Kommentars nicht aufgehoben wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-162">We fixed an issue that caused the selection in the document to not be cleared when clicking outside a newly created comment.</span></span>


- <span data-ttu-id="03067-163">Wir haben ein Problem behoben, bei dem das Kopieren einer E-Mail-Anlage in eine andere Anwendung als Word fehlschlug, wenn der Dateiname DBCS-Zeichen enthielt.</span><span class="sxs-lookup"><span data-stu-id="03067-163">We fixed an issue where copying a mail attachment to an application other than Word would fail if the filename included DBCS characters.</span></span>


- <span data-ttu-id="03067-164">Ein Problem wurde behoben, das dazu führte, dass Outlook unerwartet geschlossen wurde, wenn lautes Vorlesen mit anderen Versionen von Windows verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-164">We fixed an issue that caused an expected close when using read aloud with other versions of Windows.</span></span>


- <span data-ttu-id="03067-165">Es wurde eine Problem behoben, bei dem in kontextbezogenen Karten für Rechtschreibung und Grammatik im Zusammenarbeitsbereich Schaltflächen-Symbole angezeigt wurden, diese Schaltflächen aber keine QuickInfo aufwiesen.</span><span class="sxs-lookup"><span data-stu-id="03067-165">Fixed an issue where canvas contextual cards for spelling and grammar show icon buttons, but those buttons have no tooltips.</span></span>


- <span data-ttu-id="03067-166">Es wurde ein Problem behoben, das zu einer Nichtübereinstimmung zwischen dem Design des Bearbeitungsbereichs und dem Systemdesign führte.</span><span class="sxs-lookup"><span data-stu-id="03067-166">We fixed an issue that was causing a mismatch between the Editor pane theme and the system theme.</span></span>


- <span data-ttu-id="03067-167">Es wurde ein Problem behoben, bei dem der Editorbereich nicht geöffnet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-167">Fixed an issue where the Editor Pane doesn't open.</span></span>


- <span data-ttu-id="03067-168">Es wurde ein Problem behoben, bei dem beim Wechsel zur Kategorie "Rechtschreibung" im Editor weiterhin Ähnlichkeitsmarkierungen angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-168">Fixed an issue where similarity squiggles do not dissapear when switching to Spelling category in the Editor.</span></span>


- <span data-ttu-id="03067-169">Wir haben ein Problem behoben, bei dem Word manchmal einen Rahmen um Text angezeigt hat, der nicht hätte dort sein sollen.</span><span class="sxs-lookup"><span data-stu-id="03067-169">We fixed an issue where Word sometimes displayed a border around text that should not have been there.</span></span>


- <span data-ttu-id="03067-170">Ein Problem wurde behoben, bei dem sich der Zeichenabstand für bestimmte Schriftarten vergrößerte, wenn der Text um 90 Grad gedreht wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-170">We fixed an issue where character spacing increases for specific fonts when rotating them 90 degrees.</span></span>


- <span data-ttu-id="03067-171">Wir haben ein Problem behoben, bei dem beim Ausführen eines Makros das falsche Feld aktualisiert wurde, wenn Bearbeitungseinschränkungen angewendet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-171">We fixed an issue where the wrong field is getting updated when running a macro if editing restrictions are applied.</span></span>


- <span data-ttu-id="03067-172">Ein Problem wurde behoben, bei dem bei der Zusammenarbeit mit mehreren Benutzern an Dokumenten manchmal Kommentarantworten verloren gingen.</span><span class="sxs-lookup"><span data-stu-id="03067-172">We fixed an issue where comment replies were sometimes lost when coauthoring with multiple users.</span></span>


- <span data-ttu-id="03067-173">Es wurde ein Problem im Zusammenhang mit dem Arbeiten an großen Dokumenten behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-173">We fixed a performance issue related to working with large documents.</span></span>


- <span data-ttu-id="03067-174">Wir haben ein Problem behoben, bei dem einige Word-Dateien aufgrund beschädigter Lesezeichen nicht geöffnet werden.</span><span class="sxs-lookup"><span data-stu-id="03067-174">We fixed an issue where some Word files don't open because of corrupt bookmarks.</span></span>


### <a name="office-suite"></a><span data-ttu-id="03067-175">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-175">Office Suite</span></span>

- <span data-ttu-id="03067-176">Ein Problem wurde behoben, bei dem das CLP-Feature bisher ein unaufgefordertes Speichern in der SyncBacked-Datei (von OneDrive synchronisierte Datei) verursachte.</span><span class="sxs-lookup"><span data-stu-id="03067-176">We fixed an issue where the CLP feature previously caused unprompted saves to the SyncBacked file (File synced by OneDrive).</span></span>


- <span data-ttu-id="03067-177">Ein Problem wurde behoben, bei dem Benutzer auf lokalen Servern gespeicherte Dateien nicht bearbeiten konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-177">We fixed an issue where the user was unable to edit files stored in OnPrem servers.</span></span>


- <span data-ttu-id="03067-178">Eine Leistungsregression beim Öffnen von SyncBacked-Dateien wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-178">Fixed a performance regression on opening SyncBacked files.</span></span>


- <span data-ttu-id="03067-179">Wir haben ein Problem behoben, bei dem in OneDrive eine Fehlermeldung für den Seriendruck angezeigt wurde, wenn gar kein Seriendruckkonflikt vorlag.</span><span class="sxs-lookup"><span data-stu-id="03067-179">We fixed an issue where OneDrive would display a merge error message when there was indeed no merge conflict.</span></span>


- <span data-ttu-id="03067-180">Wir haben ein Problem behoben, bei dem die Anmeldung mit einem anderen Konto zu einem Herunterfahren führen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-180">We fixed an issue where signing in with a different account could result in a shutdown.</span></span>


- <span data-ttu-id="03067-181">Wir haben ein Problem in Bezug auf die Z-Reihenfolge von SVG-Objekten bei der Umwandlung in Formen behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-181">We fixed an issue related to z-order of SVG objects when converted to shapes.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2105-june-04"></a><span data-ttu-id="03067-183">Version 2105: 04. Juni</span><span class="sxs-lookup"><span data-stu-id="03067-183">Version 2105: June 04</span></span>
<span data-ttu-id="03067-184">*Version 2105 (Build 14026.20264)*</span><span class="sxs-lookup"><span data-stu-id="03067-184">*Version 2105 (Build 14026.20264)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-186">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-186">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-187">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-187">Excel</span></span>

- <span data-ttu-id="03067-188">**Einstellungen für die Datentyperkennung:** Konfigurieren des Verhaltens der Datentyperkennung beim Importieren von Daten aus unstrukturierten Quellen mit Power Query in Excel</span><span class="sxs-lookup"><span data-stu-id="03067-188">**Data type detection settings:** Configure the data type detection behavior when importing data from unstructured sources with Power Query in Excel</span></span>

### <a name="word"></a><span data-ttu-id="03067-189">Word</span><span class="sxs-lookup"><span data-stu-id="03067-189">Word</span></span>

- <span data-ttu-id="03067-190">**Schreibstile:** Schreibstile stellt Kritiken basierend auf dem vom Benutzer gewählten Formalitätsgrad zusammen</span><span class="sxs-lookup"><span data-stu-id="03067-190">**Writing Styles:** Writing Styles curates critiques based on users' selected formality level</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-193">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-193">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-194">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-194">Excel</span></span>

- <span data-ttu-id="03067-195">Es wurde ein Problem behoben, bei dem bei einigen Benutzern zusätzliche Einträge in der Excel-Add-In-Liste angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-195">We fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2105-june-01"></a><span data-ttu-id="03067-197">Version 2105: 01. Juni</span><span class="sxs-lookup"><span data-stu-id="03067-197">Version 2105: June 01</span></span>
<span data-ttu-id="03067-198">*Version 2105 (Build 14026.20254)*</span><span class="sxs-lookup"><span data-stu-id="03067-198">*Version 2105 (Build 14026.20254)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-200">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-200">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-201">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-201">Outlook</span></span>

- <span data-ttu-id="03067-202">**Letzte Anmeldung / Verdächtige Anmeldung:** Outlook informiert Sie jetzt, wann und wo Sie sich zuletzt bei Ihrem Konto angemeldet haben, und benachrichtigt Sie, wenn verdächtige Anmeldeaktivitäten erkannt werden</span><span class="sxs-lookup"><span data-stu-id="03067-202">**Last Sign In / Suspicious Sign In:** Outlook now tells you when and where you last signed into your account, and alerts you if any suspicious sign-in activity is detected</span></span>

- <span data-ttu-id="03067-203">**Aktivieren Sie Verbesserungen für freigegebene Kalender:** Outlook ist in der Lage, freigegebene Kalender in Office 365 mithilfe der REST API zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="03067-203">**Turn on shared calendar improvements:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="03067-204">Aktivieren Sie die Vorschau, um schnellere und zuverlässigere Aktualisierungen für freigegebene Kalender zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="03067-204">Turn on the preview for faster and more reliable updates to shared calendars.</span></span><br /><span data-ttu-id="03067-205">Weitere Detailinformationen finden Sie in [diesem Blogbeitrag](https://insider.office.com/de-DE/blog/shared-calendars-improvements-in-outlook-for-windows).</span><span class="sxs-lookup"><span data-stu-id="03067-205">See details in [blog post](https://insider.office.com/de-DE/blog/shared-calendars-improvements-in-outlook-for-windows)</span></span>

- <span data-ttu-id="03067-206">**Barrierefreiheit-Überprüfungsanstupser beim Senden von E-Mails an große Verteilerlisten, externe Benutzer:** Wir haben die Funktion hinzugefügt, beim Verfassen einer E-Mail an große Zielgruppen, externe Benutzer usw. automatisch über einen Mailtipp auf eine Verletzung der Barrierefreiheit hingewiesen zu werden. Diese Einstellungen befinden sich in „Erleichterte Bedienung“</span><span class="sxs-lookup"><span data-stu-id="03067-206">**Accessibility Checker nudge when sending emails to large DL, external users:** We added the functionally to get prompted automatically, through a mailtip, of an accessibility violation while composing an email to large audiences, external users, etc. These settings live in the Ease of Access</span></span><br /><span data-ttu-id="03067-207">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/sending-accessible-emails-in-outlook-for-windows)</span><span class="sxs-lookup"><span data-stu-id="03067-207">See details in [blog post](https://insider.office.com/de-DE/blog/sending-accessible-emails-in-outlook-for-windows)</span></span>

### <a name="visio"></a><span data-ttu-id="03067-208">Visio</span><span class="sxs-lookup"><span data-stu-id="03067-208">Visio</span></span>

- <span data-ttu-id="03067-209">**AWS-Schablonen und -Formen:** Wir haben jetzt Schablonen mit den neuesten AWS-Formen, die Sie bei der Erstellung von Diagrammen unterstützen.</span><span class="sxs-lookup"><span data-stu-id="03067-209">**AWS stencils and shapes:** We now have stencils with the latest AWS shapes to help you create diagrams.</span></span> [<span data-ttu-id="03067-210">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-210">Learn more</span></span>](https://support.office.com/article/138206bf-d10f-4583-9f31-885ce706af49)




[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-213">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-213">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-214">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-214">Outlook</span></span>

- <span data-ttu-id="03067-215">Ein Problem wurde behoben, das zu einem unerwarteten Schließen bei der Interaktion mit der Outlook Mail- oder Kalenderansichten führen kann.</span><span class="sxs-lookup"><span data-stu-id="03067-215">We fixed an issue that may cause a unexpected close when interacting with Outlook Mail or Calendar Views.</span></span>




[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2105-may-23"></a><span data-ttu-id="03067-217">Version 2105: 23. Mai</span><span class="sxs-lookup"><span data-stu-id="03067-217">Version 2105: May 23</span></span>
<span data-ttu-id="03067-218">*Version 2105 (Build 14026.20246)*</span><span class="sxs-lookup"><span data-stu-id="03067-218">*Version 2105 (Build 14026.20246)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-220">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-220">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="03067-221">Teams</span><span class="sxs-lookup"><span data-stu-id="03067-221">Teams</span></span>

- <span data-ttu-id="03067-222">**Ankündigung der Dashboardansichten für Anwesenheitsdaten:** Sie müssen von nun an keine Berichte mehr manuell herunterladen. Teams ermöglicht Ihnen jetzt die Anzeige aller aggregierten Daten in einer Dashboardansicht mit nur einem Klick</span><span class="sxs-lookup"><span data-stu-id="03067-222">**Announcing attendance data dashboard views:** No longer do you need to manually download reports, Teams now allows you to view all aggregated data in a one click dashboard view</span></span>

- <span data-ttu-id="03067-223">**Sicherheits-, Compliance- und Datenschutzfunktionen für Apps:** Für von Microsoft 365 zertifizierte Teams-Apps können Administratoren die Sicherheits-, Compliance- und Datenschutzfunktionen auf einer neuen Registerkarte auf der Detailseite der App im Teams Admin Center anzeigen.</span><span class="sxs-lookup"><span data-stu-id="03067-223">**Security, compliance, and data protection capabilities for apps:** For Microsoft 365 Certified Teams apps, admins can view security, compliance, and data protection capabilities in a new tab on the app's detail page in the Teams Admin Center.</span></span> <span data-ttu-id="03067-224">Diese Transparenz gibt Microsoft-Kunden Vertrauen in die Anwendungen, die ihre Organisationen ausführen.</span><span class="sxs-lookup"><span data-stu-id="03067-224">This transparency gives Microsoft customers trust in the applications that run their organizations.</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-227">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-227">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-228">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-228">Outlook</span></span>

- <span data-ttu-id="03067-229">Es wurde ein Problem behoben, durch das einige Anweisungen für das Feature "Besprechungen kürzen" aufgrund von Sprachausgabetechnologien nicht verfügbar waren.</span><span class="sxs-lookup"><span data-stu-id="03067-229">We fixed an issue that caused some instructions for the "Shorten Meetings" feature to be unavailable through screen reader technologies.</span></span>


- <span data-ttu-id="03067-230">Es wurde ein Problem behoben, das dazu führte, dass einige Benutzer beim Laden von Personenkarten unerwartet geschlossen wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-230">We fixed an issue that caused some users to experience unexpectedly closed when loading person cards.</span></span>


- <span data-ttu-id="03067-231">Es wurde ein Registrierungsschlüssel hinzugefügt, mit dem die neue Benutzeroberfläche der Raumsuche (dieselbe Benutzeroberfläche wie in Outlook für Web) deaktiviert und die Vorgängerversion der Raumsuche mit "Vorgeschlagene Zeiten" aktiviert wird.</span><span class="sxs-lookup"><span data-stu-id="03067-231">We added a registry key that disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with Suggested Times.</span></span>
    - <span data-ttu-id="03067-232">Registrierungsschlüssel:</span><span class="sxs-lookup"><span data-stu-id="03067-232">Registry Key:</span></span>

        > <span data-ttu-id="03067-233">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span><span class="sxs-lookup"><span data-stu-id="03067-233">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span></span> </br>
        > <span data-ttu-id="03067-234">REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="03067-234">REG_DWORD “ShowLegacyRoomFinder”</span></span></br></br>
        > <span data-ttu-id="03067-235">0 (Standard) – Outlook verwendet die neue von OWA unterstützte Benutzeroberfläche für die Raumsuche, wenn der Benutzer auf die Schaltfläche „Raumsuche“ klickt, um nach verfügbaren Räumen zu suchen</span><span class="sxs-lookup"><span data-stu-id="03067-235">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span>  </br>
        > <span data-ttu-id="03067-236">1 – Outlook verwendet die ältere Benutzeroberfläche der Raumsuche, um nach verfügbaren Räumen zu suchen</span><span class="sxs-lookup"><span data-stu-id="03067-236">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span> </br>


### <a name="project"></a><span data-ttu-id="03067-237">Project</span><span class="sxs-lookup"><span data-stu-id="03067-237">Project</span></span>

- <span data-ttu-id="03067-238">Ein Problem wurde behoben, bei dem Zuordnungen zu manuell geplanten Vorgängen möglicherweise auf ein falsches Datum verschoben wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-238">Fixed an issue where assignments on manually scheduled tasks may be moved to an incorrect date.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2105-may-19"></a><span data-ttu-id="03067-240">Version 2105: 19. Mai</span><span class="sxs-lookup"><span data-stu-id="03067-240">Version 2105: May 19</span></span>
<span data-ttu-id="03067-241">*Version 2105 (Build 14026.20202)*</span><span class="sxs-lookup"><span data-stu-id="03067-241">*Version 2105 (Build 14026.20202)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-243">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-243">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="03067-244">Teams</span><span class="sxs-lookup"><span data-stu-id="03067-244">Teams</span></span>

- <span data-ttu-id="03067-245">**Teams-Webinare werden in Dynamics 365 Marketing integriert, um die Lead-Pflege zu ermöglichen:** Mit diesem Feature können Webinar-Organisatoren die Nutzung von Registranten nach der Veranstaltung durch die Nutzung von D365 Marketing fördern.</span><span class="sxs-lookup"><span data-stu-id="03067-245">**Teams Webinars integrate with Dynamics 365 Marketing to enable lead nurturing:** With this feature, webinar organizers can drive post event engagement with registrants by leveraging D365 Marketing.</span></span> <span data-ttu-id="03067-246">Die Teilnehmer-Engagement-Daten werden mit der D365 Marketing-Organisation synchronisiert und ermöglichen automatisierte Benutzerreisen</span><span class="sxs-lookup"><span data-stu-id="03067-246">The attendee engagement data syncs with D365 Marketing org and enabled automated user journeys</span></span>

- <span data-ttu-id="03067-247">**Intelligente Lautsprecher:** Intelligente Lautsprecher sind intelligente Peripheriegeräte für Microsoft Teams Rooms unter Windows.</span><span class="sxs-lookup"><span data-stu-id="03067-247">**Intelligent speakers:** Intelligent speakers are intelligent peripherals for Microsoft Teams Rooms on Windows.</span></span> <span data-ttu-id="03067-248">Sie bringen den Teilnehmern im Besprechungsraum eine vom Lautsprecher zugeordnete Transkription, sodass die Teilnehmer weniger Zeit mit Notizen verbringen und problemlos mitverfolgen können, wer was im Raum gesagt hat.</span><span class="sxs-lookup"><span data-stu-id="03067-248">They will bring speaker attributed transcription for participants in the meeting room, enabling attendees to spend less time note-taking and easily follow along who said what in the room.</span></span>

- <span data-ttu-id="03067-249">**Ermöglichen Sie Teams-Benutzern den Kauf von Team-Apps über den Teams-Client:** Teams-Benutzer können jetzt Teams-App-Abonnements im Teams-Store erwerben.</span><span class="sxs-lookup"><span data-stu-id="03067-249">**Enable Teams users to purchase Teams apps through Teams client:** Teams users have now the ability to purchase Teams app subscriptions from the Teams store.</span></span>

- <span data-ttu-id="03067-250">**Erstellen von Teams mit Teams-Vorlagen:** Mit Vorlagen in Teams können Benutzer beim Erstellen eines neuen Teams aus einer Vielzahl von anpassbaren Vorlagen auswählen, damit sie schnell loslegen können.</span><span class="sxs-lookup"><span data-stu-id="03067-250">**Create Teams with Team Templates:** With Templates in Teams, users can choose from a variety of customizable templates when creating a new team, helping them get started quickly.</span></span> <span data-ttu-id="03067-251">IT-Administratoren können auch benutzerdefinierte Vorlagen für ihre Organisation erstellen, mit denen sie Teamstrukturen standardisieren, relevante Apps vorinstallieren und Best Practices skalieren können.</span><span class="sxs-lookup"><span data-stu-id="03067-251">IT Admins can also create custom templates for their organization, allowing them to standardize team structures, preinstall relevant apps, and scale best practices.</span></span> <span data-ttu-id="03067-252">IT-Administratoren können auswählen, welche Teamvorlagen Endbenutzern im Teams Admin Center angezeigt werden sollen, und Website-Registerkarten vorkonfigurieren, indem sie URLs zu einer Website-Registerkarte in einer Teamvorlage hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="03067-252">IT Admins can choose which team templates to show to end users in Teams Admin Center, and also preconfigure website tabs by adding URLs to a website tab in a team template.</span></span>

- <span data-ttu-id="03067-253">**Verwenden von Laserpointer- und Freihandanmerkungen in PowerPoint Live in Teams:** Wir führen virtuelle Laserpointer- und Annotationsanmerkungen ein, damit Präsentatoren Inhalte effektiv teilen und ihre Zielgruppe ansprechen können, indem sie auf bestimmte Abschnitte des PowerPoint-Foliensatzes aufmerksam machen.</span><span class="sxs-lookup"><span data-stu-id="03067-253">**Use laser pointer and ink annotations in PowerPoint Live in Teams:** We are introducing virtual laser pointer and annotations so presenters can effectively share content and engage their audience by drawing attention to certain sections of the PowerPoint deck.</span></span> <span data-ttu-id="03067-254">So wie Sie einen physischen Laserpointer in einem Raum verwenden würden, können Sie mit PowerPoint Live effektiv auf verschiedene Stellen zeigen, sodass das Publikum problemlos nachverfolgen kann, was sich auf der Folie befindet.</span><span class="sxs-lookup"><span data-stu-id="03067-254">Just as you would use a physical laser point in a room, PowerPoint Live allows you to effectively point at different places so the audience can easily follow along what’s on the slide.</span></span>

- <span data-ttu-id="03067-255">**Power Automate-Flussempfehlungen mit 1P-Teamvorlagen:** Surface Power Automate-Flussvorlagen für Teams, die aus 1P-Teamvorlagen erstellt wurden</span><span class="sxs-lookup"><span data-stu-id="03067-255">**Power Automate flow recommendations with 1P Team Templates:** Surface Power Automate flow templates for teams created from 1P team templates</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-258">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-258">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-259">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-259">Outlook</span></span>

- <span data-ttu-id="03067-260">Wir haben ein Problem behoben, durch das die Feedback-Option für Benutzer der Office Dauerlizenz 2021-Vorschau nicht angezeigt werden konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-260">We fixed an issue that caused the feedback option unable to appear for users of the Office Perpetual 2021 preview.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2105-may-12"></a><span data-ttu-id="03067-262">Version 2105: 12. Mai</span><span class="sxs-lookup"><span data-stu-id="03067-262">Version 2105: May 12</span></span>
<span data-ttu-id="03067-263">*Version 2105 (Build 14026.20164)*</span><span class="sxs-lookup"><span data-stu-id="03067-263">*Version 2105 (Build 14026.20164)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-265">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-265">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="03067-266">Teams</span><span class="sxs-lookup"><span data-stu-id="03067-266">Teams</span></span>

- <span data-ttu-id="03067-267">**Benutzerpräferenz-Einstellung, um Dateien standardmäßig in Desktop (oder) Browser (oder) Teams zu öffnen:** Benutzer können ihre Standardpräferenz als Browser, Desktop oder Teams festlegen, wenn sie Office-Dateien (Word, Excel und Power Point) öffnen, die in Teams freigegeben sind. Desktop-Einstellung kann ausgewählt werden, wenn die neuesten Office-Clients installiert und aktiviert sind</span><span class="sxs-lookup"><span data-stu-id="03067-267">**User preference setting to open files by default in Desktop (or) Browser (or) Teams:** Users can set their default preference as Browser, Desktop or Teams when opening Office (Word, Excel, and Power Point) files that are shared in Teams.Desktop setting can be selected if latest Office clients are installed and activated</span></span>

- <span data-ttu-id="03067-268">**Reporter- und Nebeneinander-Modus in Teams-Besprechungen:** Sie können jetzt neben Ihren Inhalten angezeigt werden, um eine ansprechendere Präsentations- und Konsumerfahrung zu erzielen</span><span class="sxs-lookup"><span data-stu-id="03067-268">**Reporter and Side-by-Side Mode in Teams meetings:** You can now appear next to your content for a more engaging presentation and consumption experience</span></span>

- <span data-ttu-id="03067-269">**Teams-Webinar-Funktionen sind generell verfügbar:** Planen und liefern Sie Webinare für 1000 Personen mit der gleichen Teams-App, die Sie auch für Meetings verwenden!</span><span class="sxs-lookup"><span data-stu-id="03067-269">**Teams webinar capabilities general availability:** Schedule and deliver 1,000 person webinars with the same Teams app you use for meetings!</span></span> <span data-ttu-id="03067-270">Webinar-Funktionen unterstützen das Erstellen einer Registrierungsseite, die E-Mail-Bestätigung für Registrierende, die Host-Verwaltung für Video und Audio von Teilnehmenden, die Teilnehmer-Berichterstellung sowie interaktiver Features wie Umfragen, Chats und Reaktionen.</span><span class="sxs-lookup"><span data-stu-id="03067-270">Webinar capabilities support registration page creation, email confirmation for registrants, host management for attendee video and audio, attendee reporting, plus interactive features like polls, chat and reactions.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-273">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-273">Resolved issues</span></span>
### <a name="word"></a><span data-ttu-id="03067-274">Word</span><span class="sxs-lookup"><span data-stu-id="03067-274">Word</span></span>

- <span data-ttu-id="03067-275">Es wurde eine Problem behoben, bei dem kontextbezogene Karten für Rechtschreibung und Grammatik im Zusammenarbeitsbereich Schaltflächen-Symbole anzeigen, diese Schaltflächen aber keine QuickInfo haben.</span><span class="sxs-lookup"><span data-stu-id="03067-275">Fixed an issue where canvas contextual cards for spelling and grammar show icon buttons, but those buttons have no tooltips.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2105-may-07"></a><span data-ttu-id="03067-277">Version 2105: 7. Mai</span><span class="sxs-lookup"><span data-stu-id="03067-277">Version 2105: May 07</span></span>
<span data-ttu-id="03067-278">*Version 2105 (Build 14026.20138)*</span><span class="sxs-lookup"><span data-stu-id="03067-278">*Version 2105 (Build 14026.20138)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-280">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-280">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="03067-281">Teams</span><span class="sxs-lookup"><span data-stu-id="03067-281">Teams</span></span>

- <span data-ttu-id="03067-282">**Einführung von Layouts in Teams-Besprechungen:** Jetzt können Sie überlagerte Inhalte anzeigen, um ihre Präsentation und das Erlebnis für Zuhörer noch ansprechender zu gestalten</span><span class="sxs-lookup"><span data-stu-id="03067-282">**Introducing layouts to Teams meetings:** Now you can appear overlaid ontop of content for a more immersive presentation and consumption experience</span></span>

- <span data-ttu-id="03067-283">**Kamera für bestimmte Teilnehmer deaktivieren:** Besprechungsorganisatoren und Referenten können die Kamera bestimmter Teilnehmer in einer Teams-Besprechung deaktivieren, um sicherzustellen, dass sie kein Video in der Besprechung teilen.</span><span class="sxs-lookup"><span data-stu-id="03067-283">**Disable Camera for Specific Attendees:** Meeting Organizers and Presenters can disable the cameras of specific Attendees in a Teams Meeting to make sure they don't share video in the meeting.</span></span>

- <span data-ttu-id="03067-284">**Kamera für alle Teilnehmer deaktivieren:** Besprechungsorganisatoren und Referenten können die Kamera aller Teilnehmer in einer Teams-Besprechung deaktivieren, um sicherzustellen, dass sie kein Video in der Besprechung teilen.</span><span class="sxs-lookup"><span data-stu-id="03067-284">**Disable Camera for All Attendees:** Meeting Organizers and Presenters can disable the cameras of all Attendees in a Teams Meeting to make sure they don't share video in the meeting.</span></span>

- <span data-ttu-id="03067-285">**Anonyme Benutzer können präsentieren:** Beim Hosten einer Teams-Liveereignis haben wir für anonyme Benutzer die Möglichkeit hinzugefügt, an einem Liveereignis teilzunehmen und während der Veranstaltung ebenfalls präsentieren zu können.</span><span class="sxs-lookup"><span data-stu-id="03067-285">**Anonymous users can present:** When hosting a Teams live event, we added the ability for an anonymous users to join a Live Event and so that they can also present during the event.</span></span>

- <span data-ttu-id="03067-286">**Programmgesteuertes Verwalten von Kategorien in Teams – Microsoft Teams-Kategorien-APIs sind jetzt in der öffentlichen Vorschau verfügbar:** Diese Gruppe von APIs kann verwendet werden, um Benutzerkategorien programmgesteuert in einem Team zuzuweisen, wodurch die Erstellung und Wartung von Kategorien schneller und einfacher wird.</span><span class="sxs-lookup"><span data-stu-id="03067-286">**Manage tags in Teams programmatically - Microsoft Teams Tags APIs are now in public preview:** This set of APIs can be used to programmatically assign users tags in a team, making tag creation and maintenance faster and easier.</span></span>  <span data-ttu-id="03067-287">Mit Kategorien in Teams können Benutzer schnell eine Gruppe von Personen erreichen, ohne jeden @erwähnen oder eingeben zu müssen.</span><span class="sxs-lookup"><span data-stu-id="03067-287">Tags in Teams let users quickly reach a group of people without having to @mention or type out everyone.</span></span> <span data-ttu-id="03067-288">Weitere Informationen zu Kategorien in Teams finden Sie unter „Verwenden von Kategorien in Teams“.</span><span class="sxs-lookup"><span data-stu-id="03067-288">For more information on tag in teams, see Using tags in Teams.</span></span> <span data-ttu-id="03067-289">Mithilfe dieser neuen APIs können Entwickler jetzt Kategorien in einem Team erstellen und Benutzern zuweisen, eine Liste von Kategorien in einem Team abrufen, Kategorien aktualisieren und löschen</span><span class="sxs-lookup"><span data-stu-id="03067-289">Using these new APIs, developers can nowCreate tags in a team and assign usersGet a list of tags in a team Update tagsDelete tags</span></span>

- <span data-ttu-id="03067-290">**Von PowerPoint in Teams präsentieren:** Präsentieren Sie Ihre Folien direkt aus der PowerPoint-App in einer Teams-Besprechung über PowerPoint Live.</span><span class="sxs-lookup"><span data-stu-id="03067-290">**Present from PowerPoint to Teams:** Present your slides directly from the PowerPoint app to a Teams meeting via PowerPoint Live.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-293">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-293">Resolved issues</span></span>
### <a name="word"></a><span data-ttu-id="03067-294">Word</span><span class="sxs-lookup"><span data-stu-id="03067-294">Word</span></span>

- <span data-ttu-id="03067-295">Behebt ein Problem, bei dem der Editorbereich nicht geöffnet wird.</span><span class="sxs-lookup"><span data-stu-id="03067-295">Fixes an issue where the Editor Pane doesn't open.</span></span>


### <a name="office-suite"></a><span data-ttu-id="03067-296">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-296">Office Suite</span></span>

- <span data-ttu-id="03067-297">RelNotesNotNeeded</span><span class="sxs-lookup"><span data-stu-id="03067-297">RelNotesNotNeeded</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2105-may-03"></a><span data-ttu-id="03067-299">Version 2105: 3. Mai</span><span class="sxs-lookup"><span data-stu-id="03067-299">Version 2105: May 03</span></span>
<span data-ttu-id="03067-300">*Version 2105 (Build 14026.20052)*</span><span class="sxs-lookup"><span data-stu-id="03067-300">*Version 2105 (Build 14026.20052)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-302">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-302">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="03067-303">Teams</span><span class="sxs-lookup"><span data-stu-id="03067-303">Teams</span></span>

- <span data-ttu-id="03067-304">**Mehrere Benutzer gleichzeitig in einer Besprechung ins Spotlight setzen:** Organisatoren und Präsentatoren können jetzt während Besprechungen gleichzeitig mehrere Teilnehmer ins Spotlight setzen.</span><span class="sxs-lookup"><span data-stu-id="03067-304">**Spotlight multiple users at the same time in a meeting:** Organizers and presenters can now spotlight multiple participants simultaneously during meetings.</span></span> <span data-ttu-id="03067-305">Auf der Besprechungsbühne werden diese hervorgehobenen Teilnehmer für jeden in der Besprechung mit ihren Videos oder Avataren angezeigt.</span><span class="sxs-lookup"><span data-stu-id="03067-305">The meeting stage will show these spotlighted participants, with their videos or avatars, to everyone in the meeting.</span></span>

- <span data-ttu-id="03067-306">**Aus PowerPoint nach Teams präsentieren:** Präsentieren Sie Ihre Folien direkt aus der PowerPoint-App ein eine Teams-Besprechung über PowerPoint Live.</span><span class="sxs-lookup"><span data-stu-id="03067-306">**Present from PowerPoint to Teams:** Present your slides directly from the PowerPoint app to a Teams meeting via PowerPoint Live.</span></span>

- <span data-ttu-id="03067-307">**Neue Erfahrung „Kategorie verwalten“ und andere Erweiterungen:** Mit Kategorien in Teams können Benutzer schnell eine Gruppe von Personen erreichen, ohne alle Personen zu @erwähnen oder einzugeben. Die Erfahrung „Kategorien verwalten“ ist jetzt eine Registerkarte. Kategorien haben jetzt auch ein Beschreibungsfeld, so dass Sie mehr Details zu einer Kategorie hinzufügen können.</span><span class="sxs-lookup"><span data-stu-id="03067-307">**New manage tag experience and other enhancements:** Tags in Teams let users quickly reach a group of people without having to @mention or type out everyone.The manage tags experience is now a Tab. Tags also now have a description field so that you can add more details to a tag.</span></span> <span data-ttu-id="03067-308">Die neue Registerkarte „Kategorien“ wird die Landeseite für Kategorie-Benachrichtigungen und die Suche nach Kategorien sein, welche ebenfalls bald verfügbar sein wird.</span><span class="sxs-lookup"><span data-stu-id="03067-308">The new Tags Tab will be the landing page for tag notifications and search for tags, which is also coming soon.</span></span>

- <span data-ttu-id="03067-309">**Intelligente Lautsprecher:** Intelligente Lautsprecher sind intelligente Peripheriegeräte für Microsoft Teams-Räume unter Windows.</span><span class="sxs-lookup"><span data-stu-id="03067-309">**Intelligent Speakers:** Intelligent speakers are intelligent peripherals for Microsoft Teams Rooms on Windows.</span></span> <span data-ttu-id="03067-310">Sie bringen den Teilnehmern im Besprechungsraum eine vom Lautsprecher zugeordnete Transkription, sodass die Teilnehmer weniger Zeit mit Notizen verbringen und problemlos mitverfolgen können, wer was im Raum gesagt hat.</span><span class="sxs-lookup"><span data-stu-id="03067-310">They will bring speaker attributed transcription for participants in the meeting room, enabling attendees to spend less time note-taking and easily follow along who said what in the room.</span></span>

- <span data-ttu-id="03067-311">**Ändern des Standards für neue Benutzer von „Teams Lila“ zur nativen Benachrichtigung:** Native Benachrichtigungen bieten eine Reihe von Vorteilen wie Unterstützung für das Aktions-Center, Barrierefreiheit, Unterstützung für den Modus „Fokusunterstützung“ usw. Derzeit ist „Teams Lila“ der Standard-Benachrichtigungsstil für einen neuen Benutzer in Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="03067-311">**Changing default to native notification from teams purple for new users:** Native Notifications provide a host of benefits like support for action center, accessibility, support for focus assist mode e.t.c.Currently the default notification style for a new user in Microsoft teams is Teams Purple.</span></span> <span data-ttu-id="03067-312">Mit dieser Änderung wird der Standard für neue Benutzer auf „Native Benachrichtigung“ geändert.</span><span class="sxs-lookup"><span data-stu-id="03067-312">With this change the default for new user will change to Native Notification.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-315">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-315">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-316">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-316">Excel</span></span>

- <span data-ttu-id="03067-317">Es wurde ein Problem behoben, bei dem Excel unerwartet geschlossen wurde, wenn ein 32-Bit-Office auf einem 64-Bit-Windows verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-317">We fixed an issue that caused Excel to close unexpectedly when using 32 bit Office on 64 bit Windows.</span></span>


- <span data-ttu-id="03067-318">Es wurde ein Problem behoben, bei dem Excel unerwartet geschlossen wurde, wenn man sich durch Kommentare im Kommentarbereich bewegte.</span><span class="sxs-lookup"><span data-stu-id="03067-318">We fixed an issue that caused Excel to close unexpectedly when moving through comments in the Comments pane.</span></span>


- <span data-ttu-id="03067-319">Es wurde ein Problem behoben, bei dem einige Add-ins für die Automatisierung für Excel nicht geladen werden konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-319">Fixed an issue where some automation add-ins for Excel unable to load.</span></span>


- <span data-ttu-id="03067-320">Es wurde ein Problem behoben, bei dem die Sprachausgabe die Eigenschaften zweier Schaltflächen auf der Registerkarte Kopfzeile/Fußzeile im Dialogfeld „Seiteneinrichtung“ falsch vorgelesen hat.</span><span class="sxs-lookup"><span data-stu-id="03067-320">We fixed an issue that caused Narrator to incorrectly read the properties of two buttons on the Header/Footer tab in the Page Setup dialog box.</span></span>


- <span data-ttu-id="03067-321">Es wurde ein Problem behoben, bei dem einige Arbeitsmappen, die in anderen Office-Anwendungen verknüpft waren, ohne Speicherung der Änderungen geschlossen wurden, wenn „Link aktualisieren“ ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-321">We fixed an issue that caused some workbooks linked in other Office applications to close without saving changes when running Update Link.</span></span>


- <span data-ttu-id="03067-322">Es wurde ein Problem behoben, bei dem das Add-In „Analyse-Funktionen“ für einige Benutzer nicht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="03067-322">Fixed an issue where the Analysis ToolPak add-in did not work for some users.</span></span>


- <span data-ttu-id="03067-323">Es wurde ein Problem behoben, bei dem einige Dateien gelegentlich nicht in der geschützten Ansicht geöffnet werden konnten</span><span class="sxs-lookup"><span data-stu-id="03067-323">We fixed an issue where some files would occasionally fail to open in Protected View</span></span>


- <span data-ttu-id="03067-324">Es wurde in Problem behoben, das dazu führte, dass die Datumsformatierung bei der Verwendung von Add-Ins in einigen Sprachen nicht korrekt angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-324">We fixed an issue that caused date formatting to be displayed incorrectly in some languages when using add-ins.</span></span>


- <span data-ttu-id="03067-325">Es wurde ein Problem behoben, das bei einigen Benutzern dazu führte, dass die Statusleiste keinen Bereitschaftsstatus anzeigte.</span><span class="sxs-lookup"><span data-stu-id="03067-325">We fixed an issue that caused the status bar to not indicate a Ready state for some users.</span></span>


- <span data-ttu-id="03067-326">Es wurde eine Änderung gemacht, damit der Namensmanager bei Büchern mit einer großen Anzahl von ausgeblendeten Namen geöffnet werden kann.</span><span class="sxs-lookup"><span data-stu-id="03067-326">We made a change to enable the Name Manager to open on books with a large number of hidden names.</span></span>


- <span data-ttu-id="03067-p115">Es wurde ein Problem behoben, um die Rückwärtskompatibilität mit älteren Versionen von Excel zu unterstützen. Das Problem kann dazu führen, dass eine Datei, die in einer neueren Version von Excel gespeichert wurde, in älteren Versionen von Excel aufgrund von Funktionen wie WENNFEHLER und XVERWEIS, die seit Office 2007 zu Excel hinzugefügt wurden, nicht richtig geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-p115">We fixed an issue to support backward compatibility with older versions of Excel. The issue may cause a file that is saved in a more recent version of Excel failed to load properly in older versions of Excel due to  functions such as IFERROR and XLOOKUP added to Excel since Office 2007.</span></span>


- <span data-ttu-id="03067-329">Es wurde ein Problem behoben, bei dem Excel unerwartet geschlossen werden könnte, wenn „Einfügen von Inhalten mit Formaten“ in gewissen Situationen verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-329">We fixed an issue which could cause Excel to close unexpectedly when using Paste Special with formats in certain situations.</span></span>


### <a name="outlook"></a><span data-ttu-id="03067-330">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-330">Outlook</span></span>

- <span data-ttu-id="03067-331">Es wurde ein Problem behoben, durch das Outlook die in OWA konfigurierten Einstellungen für den Posteingang mit Relevanz außer Kraft gesetzt hat.</span><span class="sxs-lookup"><span data-stu-id="03067-331">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="03067-332">Es wurde ein Problem behoben, das bei Benutzern von Roaming-Einstellungen zu Hängern führte.</span><span class="sxs-lookup"><span data-stu-id="03067-332">We fixed an issue that caused users of roaming settings to experience hangs .</span></span>


- <span data-ttu-id="03067-333">Es wurde ein Problem behoben, durch das die Namensauflösung deaktiviert wurde, wenn etwas im Namen eines anderen Benutzers gesendet und mit einem Adressbuch verglichen wurde, das nicht der globalen Adressliste entsprach.</span><span class="sxs-lookup"><span data-stu-id="03067-333">We fixed an issue that caused name resolution disabled when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="03067-334">Es wurde ein Problem behoben, bei dem für einige Benutzer der Funktion zur Verbesserung der Kalenderfreigaben Probleme auftraten, wenn Sie im Navigationsbereich mit Ihrem Kalender interagierten.</span><span class="sxs-lookup"><span data-stu-id="03067-334">We fixed an issue that caused some users of the calendar sharing improvements feature to experience issues with interacting with their calendar in the navigation pane.</span></span>


- <span data-ttu-id="03067-335">Es wurde ein Problem behoben, bei dem die Verwendung des Modus „Hoher Kontrast“ über einen längeren Zeitraum hinweg dazu führte, dass Outlook unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-335">We fixed an issue where using High Contrast mode for extended periods of time would caused Outlook to close unexpectedly.</span></span>


- <span data-ttu-id="03067-336">Es wurde ein Problem behoben, bei dem Links, die Ziffern enthalten, deaktiviert wurden, wenn eine Nachricht in Outlook in einer Rechts-nach-Links-Sprache verfasst wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-336">We fixed an issue where hyperlinks including digits would be disable when composing a message in Outlook in a right-to-left language.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="03067-337">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-337">PowerPoint</span></span>

- <span data-ttu-id="03067-338">Es wurde ein Problem im Zusammenhang mit verknüpften Bildern behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-338">Fixes an issue related to linked pictures.</span></span>


### <a name="project"></a><span data-ttu-id="03067-339">Project</span><span class="sxs-lookup"><span data-stu-id="03067-339">Project</span></span>

- <span data-ttu-id="03067-340">Es wurde ein Problem behoben, bei dem Änderungen, die durch Planungsassistenten durchgeführt wurden, nicht immer von Änderungsereignissen erfasst wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-340">We fixed an issue where changes done through Planning Wizards weren't always captured by change events.</span></span>


- <span data-ttu-id="03067-341">Es wurde ein Problem behoben, bei dem Benutzer Projekte nicht aus dem Ressourcenpool entfernen konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-341">We fixed an issue where users were unable to remove projects from the resource pool.</span></span>


### <a name="visio"></a><span data-ttu-id="03067-342">Visio</span><span class="sxs-lookup"><span data-stu-id="03067-342">Visio</span></span>

- <span data-ttu-id="03067-343">Es wurde ein Problem behoben, bei dem Visio mit dem aktuellen Build unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-343">We fixed an issue which caused Visio closed unexpectedly with recent build.</span></span>


### <a name="word"></a><span data-ttu-id="03067-344">Word</span><span class="sxs-lookup"><span data-stu-id="03067-344">Word</span></span>

- <span data-ttu-id="03067-345">Es wurde ein Problem behoben, bei dem die Textformatierung nach dem Entfernen von Hyperlinks bestehen bleibt.</span><span class="sxs-lookup"><span data-stu-id="03067-345">We fixed an issue where text formatting remains after removing hyperlinks.</span></span>


- <span data-ttu-id="03067-346">Es wurde ein Problem behoben, bei dem Platzhaltertext in Kommentaren abgeschnitten wurde, wenn Rechts-nach-Links-Sprachen verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-346">We fixed a issue where placeholder text was clipped in comments when using right-to-left languages.</span></span>


- <span data-ttu-id="03067-347">Es wurde ein Problem behoben, bei dem Kommentare nicht angezeigt werden, nachdem nach Personen gefiltert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-347">We fixed an issue where comments are not displayed after filtering by people.</span></span>


- <span data-ttu-id="03067-348">Es wurde ein Problem behoben, bei dem Word keinen Seriendruck mit einer Access-Datenbank durchführen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-348">We fixed an issue where Word was unable to perform a Mail Merge with an Access database.</span></span>


- <span data-ttu-id="03067-349">Es wurde ein Problem behoben, durch das die Fähigkeit, Ränder in einem Dokument mit mehreren Spalten zu reduzieren, verfügbar wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-349">We fixed an issue that caused the ability to collapse margins in a document containing multiple columns to be available.</span></span>


- <span data-ttu-id="03067-350">Es wurde in Problem behoben, bei dem einige Buchstaben in Tabellenzellen nicht korrekt angezeigt wurden, wenn sich Kommentare im Dokument befinden.</span><span class="sxs-lookup"><span data-stu-id="03067-350">We fixed an issue where some characters are not displayed correctly in table cells when there are comments in the document.</span></span>


- <span data-ttu-id="03067-351">Es wurde ein Problem behoben, beim dem Dateiformatänderungen auftraten, wenn Dokumente mit aktiviertem AIP-Add-In gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-351">We fixed an issue where the file format changes occurred when saving documents with the AIP add-in enabled.</span></span>


- <span data-ttu-id="03067-352">Es wurde in Problem behoben, bei dem Word beim Bearbeiten von Feldern nicht mehr antwortete.</span><span class="sxs-lookup"><span data-stu-id="03067-352">We fixed an issue where Word would become unresponsive when editing fields.</span></span>


- <span data-ttu-id="03067-353">Es wurde ein Problem behoben, bei dem die Vertraulichkeitsbezeichnung von einer Datei in Word verschwindet, nachdem die Datei in SharePoint Online hochgeladen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-353">We fixed an issue where the sensitivity label disappears from a file in Word after uploading the file to SharePoint Online.</span></span>


- <span data-ttu-id="03067-354">Es wurde ein Problem behoben, bei dem Benutzer nicht zum Speichern eines Dokumentes aufgefordert wurden, wenn sie einen Befehl benutzten (statt dem Tastaturkurzbefehl STRG+S).</span><span class="sxs-lookup"><span data-stu-id="03067-354">We fixed an issue where users would not be prompted to save documents when using a command (rather than the CTRL+S keyboard shortcut).</span></span>


- <span data-ttu-id="03067-355">Es wurde ein Problem behoben, das dazu führen konnte, dass Word beim Herunterfahren unerwartet geschlossen wurde, weil der Benutzer sich abgemeldet oder seinen Computer neu gestartet hat.</span><span class="sxs-lookup"><span data-stu-id="03067-355">Fixes an issue that may caused Word unexpectedly closed when shutting down due to the user logging off or restarting their computer.</span></span>


- <span data-ttu-id="03067-356">Es wurde ein Problem behoben, bei dem die Textformatierung nach dem Entfernen von Hyperlinks bestehen bleibt.</span><span class="sxs-lookup"><span data-stu-id="03067-356">We fixed an issue where text formatting remains after removing hyperlinks.</span></span>


### <a name="office-suite"></a><span data-ttu-id="03067-357">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-357">Office Suite</span></span>

- <span data-ttu-id="03067-358">Es wurde ein Problem behoben, das dazu führte, dass die Diktat-Schaltfläche beim Hinzufügen von Kommentaren zu einem Dokument falsch ausgerichtet war.</span><span class="sxs-lookup"><span data-stu-id="03067-358">We fixed an issue that caused the Dictation button to be misaligned when adding comments to a document.</span></span>


- <span data-ttu-id="03067-359">Es wurde ein Problem beim Analysieren einer Zeichenfolge für die Emoji-Verarbeitung behoben, bei dem Anwendungen unerwartet geschlossen wurden, wenn außerhalb der Grenzen einer Matrix gelesen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-359">Fixed an issue when parsing a string for emoji processing that casued application closed unexpectedly when reading outside of the bounds of an array</span></span>


- <span data-ttu-id="03067-360">Wir haben ein Problem behoben, bei dem einige skalierbare Vektorgrafiken (SVG) nicht korrekt gerendert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-360">We fixed an issue where some Scalable Vector Graphics (SVG) did not render correctly.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2104-april-28"></a><span data-ttu-id="03067-362">Version 2104: 28. April</span><span class="sxs-lookup"><span data-stu-id="03067-362">Version 2104: April 28</span></span>
<span data-ttu-id="03067-363">*Version 2104 (Build 13929.20296)*</span><span class="sxs-lookup"><span data-stu-id="03067-363">*Version 2104 (Build 13929.20296)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-365">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-365">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="03067-366">Teams</span><span class="sxs-lookup"><span data-stu-id="03067-366">Teams</span></span>

- <span data-ttu-id="03067-367">**Erweiterte Emoji-Auswahl:** Das Update für erweiterte Emojis bietet Personen mehr Spaß und Ausdrucksmöglichkeit in Teams.</span><span class="sxs-lookup"><span data-stu-id="03067-367">**Expanded Emoji Picker:** The expanded emoji update offers people more fun and expressiveness in Teams.</span></span> <span data-ttu-id="03067-368">Es wird auch ein breiteres Spektrum an Vielfalt und Repräsentation eingeführt.</span><span class="sxs-lookup"><span data-stu-id="03067-368">It also introduces a wider range of diversity and representation.</span></span> <span data-ttu-id="03067-369">Die Emoji-Anzahl wurde von 85 auf über 800 Emojis erweitert, mit Auswahl der Kategorie, Auswahl der Hautfarbe und Abkürzungsauswahl.</span><span class="sxs-lookup"><span data-stu-id="03067-369">The emoji set has expanded from 85 to over 800 emojis, with a category selector, skin tone selector and shortcode picker.</span></span>

- <span data-ttu-id="03067-370">**Microsoft Teams: Überarbeitete Freigabeerfahrung in Besprechungen:** Die Benutzeroberfläche für die Freigabefunktion in Besprechungen in Microsoft Teams wurde neu gestaltet, damit Präsentatoren ihre gewünschten Inhalte schneller und einfacher finden können.</span><span class="sxs-lookup"><span data-stu-id="03067-370">**Microsoft Teams: Revised in-meeting Share experience:** The user interface for the in-meeting Share feature in Microsoft Teams has been redesigned to help presenters find their desired content more quickly and easily.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-373">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-373">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-374">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-374">Excel</span></span>

- <span data-ttu-id="03067-375">Es wurde ein Problem behoben, bei dem einige Add-ins für die Automatisierung für Excel nicht geladen werden konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-375">Fixed a problem where some automation add-ins for Excel failed to load.</span></span>


### <a name="outlook"></a><span data-ttu-id="03067-376">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-376">Outlook</span></span>

- <span data-ttu-id="03067-377">Es wurde ein Problem behoben, das bei Benutzern von Roaming-Einstellungen zu Hängern führte.</span><span class="sxs-lookup"><span data-stu-id="03067-377">We fixed an issue that caused users of roaming settings to experience hangs .</span></span>


### <a name="powerpoint"></a><span data-ttu-id="03067-378">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-378">PowerPoint</span></span>

- <span data-ttu-id="03067-379">Es wurde ein Problem mit verknüpften Bildern behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-379">We fixed an issue related to linked pictures.</span></span>


### <a name="project"></a><span data-ttu-id="03067-380">Project</span><span class="sxs-lookup"><span data-stu-id="03067-380">Project</span></span>

- <span data-ttu-id="03067-381">Es wurde ein Problem behoben, bei dem Benutzer Projekte nicht aus dem Ressourcenpool entfernen konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-381">Fixed an issue where users were unable to remove projects from the resource pool.</span></span>


### <a name="word"></a><span data-ttu-id="03067-382">Word</span><span class="sxs-lookup"><span data-stu-id="03067-382">Word</span></span>

- <span data-ttu-id="03067-383">Es wurde eine Änderung bei der Bearbeitung des OLE-Objekts vorgenommen.</span><span class="sxs-lookup"><span data-stu-id="03067-383">We made a change on editing OLE object.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2104-april-26"></a><span data-ttu-id="03067-385">Version 2104: 26. April</span><span class="sxs-lookup"><span data-stu-id="03067-385">Version 2104: April 26</span></span>
<span data-ttu-id="03067-386">*Version 2104 (Build 13929.20254)*</span><span class="sxs-lookup"><span data-stu-id="03067-386">*Version 2104 (Build 13929.20254)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-388">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-388">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-389">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-389">Outlook</span></span>

- <span data-ttu-id="03067-390">**Aktivieren Sie Verbesserungen für freigegebene Kalender:** Outlook ist in der Lage, freigegebene Kalender in Office 365 mithilfe der REST API zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="03067-390">**Turn on shared calendar improvements:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="03067-391">Aktivieren Sie die Vorschau, um schnellere und zuverlässigere Aktualisierungen für freigegebene Kalender zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="03067-391">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-394">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-394">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-395">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-395">Excel</span></span>

- <span data-ttu-id="03067-396">Es wurde ein Problem behoben, bei dem einige Dateien gelegentlich nicht in der geschützten Ansicht geöffnet werden konnten</span><span class="sxs-lookup"><span data-stu-id="03067-396">We fixed an issue where some files would occasionally fail to open in Protected View</span></span>


### <a name="outlook"></a><span data-ttu-id="03067-397">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-397">Outlook</span></span>

- <span data-ttu-id="03067-398">Es wurde ein Problem behoben, durch das Outlook die in OWA konfigurierten Einstellungen für den Posteingang mit Relevanz außer Kraft gesetzt hat.</span><span class="sxs-lookup"><span data-stu-id="03067-398">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2104-april-19"></a><span data-ttu-id="03067-400">Version 2104: 19. April</span><span class="sxs-lookup"><span data-stu-id="03067-400">Version 2104: April 19</span></span>
<span data-ttu-id="03067-401">*Version 2104 (Build 13929.20216)*</span><span class="sxs-lookup"><span data-stu-id="03067-401">*Version 2104 (Build 13929.20216)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-403">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-403">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-404">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-404">Excel</span></span>

- <span data-ttu-id="03067-405">**Importieren von Daten aus dynamischen Arrays:** Sie können nun Daten aus dynamischen Arrays in die aktuelle Arbeitsmappe importieren und sie dort gestalten und aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="03067-405">**Import data from dynamic arrays:** You can now import, shape and refresh data from dynamic arrays in the current workbook.</span></span> [<span data-ttu-id="03067-406">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-406">Learn more</span></span>](https://support.office.com/article/205c6b06-03ba-4151-89a1-87a7eb36e531)

### <a name="outlook"></a><span data-ttu-id="03067-407">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-407">Outlook</span></span>

- <span data-ttu-id="03067-408">**Verbesserte Kalendersuche:** An der Kalendersuche wurden Verbesserungen vorgenommen. Die größte davon ist die Möglichkeit, das nächste Vorkommen einer Serie in den Suchergebnissen einfacher zu finden.</span><span class="sxs-lookup"><span data-stu-id="03067-408">**Improved Calendar Search:** Improvements have been made to Calendar search, largest of which is the ability to more easily find the next occurence of a series in search results.</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-411">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-411">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="03067-412">Zugriff</span><span class="sxs-lookup"><span data-stu-id="03067-412">Access</span></span>

- <span data-ttu-id="03067-413">Diese Änderung behebt ein Problem, bei dem in einigen Fällen das Ausführen einer SQL Server-Pass-Through-Abfrage zu einer Fehlermeldung führen kann, die darauf hinweist, dass ein "ungültiger Cursorstatus" vorliegt.</span><span class="sxs-lookup"><span data-stu-id="03067-413">This change fixes an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


- <span data-ttu-id="03067-414">Ein Problem wurde behoben, das, wenn eine externe Anwendung eine Benutzeroberfläche zur Barrierefreiheit anfordert, uns daran hindert, herunterzufahren, bis sie ihre Referenz freigibt.</span><span class="sxs-lookup"><span data-stu-id="03067-414">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="excel"></a><span data-ttu-id="03067-415">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-415">Excel</span></span>

- <span data-ttu-id="03067-416">Manuelles Zurücksetzen von Windows Update-Komponenten</span><span class="sxs-lookup"><span data-stu-id="03067-416">We fixed a problem that was preventing the ability to paste as formulas on a protected sheet.</span></span>


- <span data-ttu-id="03067-417">Es wurde ein Problem behoben, bei dem mittels der HYPERLINK-Funktion erstellte Links nicht funktionierten, wenn die Datei als PDF-Dokument gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-417">We fixed an issue in which hyperlinks created using the HYPERLINK function would not work if the file was saved as a PDF document.</span></span>


- <span data-ttu-id="03067-418">Wir haben ein Problem behoben, bei dem der Formel ein implizites Operatorsymbol (@) mit einem Bezug auf einen leeren Bereich hinzugefügt und möglicherweise das falsche Ergebnis angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-418">We fixed an issue where an implicit operator (@) symbol would be added to the formula with a reference to an empty range and potentially give the incorrect result.</span></span>


### <a name="outlook"></a><span data-ttu-id="03067-419">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-419">Outlook</span></span>

- <span data-ttu-id="03067-420">Wir haben ein Problem behoben, durch das Outlook bei einigen Benutzern beim Synchronisieren von Änderungen der Ordnerhierarchie unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-420">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


- <span data-ttu-id="03067-421">Ein Problem wurde behoben, das dazu führte, dass Benutzern beim Hinzufügen eines Kalenders fälschlicherweise die Meldung „Dies kann eine Weile dauern“ angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-421">We fixed an issue that cause users to erroneously see a "This may take a while" message when adding a calendar.</span></span>


- <span data-ttu-id="03067-422">Ein Problem wurde behoben, das dazu führte, dass Stellvertretungen als Organisator von Besprechungen angezeigt wurden, die in neu hinzugefügten Kalendern erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-422">We fixed an issue that caused delegates to appear as the organizer of meetings created on newly added calendars.</span></span>  <span data-ttu-id="03067-423">Besprechungen in diesem Zustand wurden im Kalender des Prinzipals nicht angezeigt.</span><span class="sxs-lookup"><span data-stu-id="03067-423">Meetings in this state did not appear on the principal's calendar.</span></span>


- <span data-ttu-id="03067-424">Wir haben ein Problem behoben, das bei der Suche von Benutzern zum Absturz führte.</span><span class="sxs-lookup"><span data-stu-id="03067-424">We fixed an issue that caused users to experience a crash when searching.</span></span>


- <span data-ttu-id="03067-425">Wir haben einen Absturz bei der Suche behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-425">We fixed a search related crash.</span></span>


- <span data-ttu-id="03067-426">Wir haben ein Problem behoben, das dazu führte, dass die Signaturen von Benutzern unerwartet verschwunden sind.</span><span class="sxs-lookup"><span data-stu-id="03067-426">We fixed an issue that caused users to see signatures disappear unexpectedly.</span></span>


- <span data-ttu-id="03067-427">Wir haben ein Problem behoben, durch das Benutzern möglicherweise die Meldung angezeigt wurde, dass der Fokus auf der Benutzeroberfläche verloren geht.</span><span class="sxs-lookup"><span data-stu-id="03067-427">We fixed an issue that could cause users to see the message that they are composing losing the UI focus.</span></span>


- <span data-ttu-id="03067-428">Wir haben ein Problem behoben, durch das Outlook die in OWA konfigurierten Einstellungen für den Posteingang mit Relevanz außer Kraft gesetzt hat.</span><span class="sxs-lookup"><span data-stu-id="03067-428">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="03067-429">Wir haben ein Problem behoben, das dazu führte, dass bei der Funktion "Cloud-Einstellungen" die benutzerdefinierten Einstellungen durch die Standardeinstellung überschrieben wurden, nachdem die Benutzer Outlook auf einem neuen Gerät konfiguriert hatten.</span><span class="sxs-lookup"><span data-stu-id="03067-429">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="03067-430">Wir haben ein Problem behoben, das dazu führte, dass einige Personen nicht auf Signaturen zugreifen konnten, die mit zweiten E-Mail-Konten verbunden waren.</span><span class="sxs-lookup"><span data-stu-id="03067-430">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="03067-431">Wir haben ein Problem behoben, durch das die Namensauflösung fehlschlug, sobald etwas im Namen eines anderen Benutzers gesendet wurde und das mit einem Adressbuch verglichen wurde, das nicht der globalen Adressliste entsprach.</span><span class="sxs-lookup"><span data-stu-id="03067-431">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="03067-432">Wir haben ein Problem behoben, durch das die Namensauflösung fehlschlug, sobald etwas im Namen eines anderen Benutzers gesendet wurde und das mit einem Adressbuch verglichen wurde, das nicht der globalen Adressliste entsprach.</span><span class="sxs-lookup"><span data-stu-id="03067-432">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


### <a name="project"></a><span data-ttu-id="03067-433">Project</span><span class="sxs-lookup"><span data-stu-id="03067-433">Project</span></span>

- <span data-ttu-id="03067-434">Es wurde ein Problem behoben, bei dem bei einem Datumsformat von W4/4 möglicherweise der falsche Tag und das falsche Jahr angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="03067-434">Fixed an issue where if the date format is W4/4, the date picker may show the wrong day and year.</span></span>


### <a name="visio"></a><span data-ttu-id="03067-435">Visio</span><span class="sxs-lookup"><span data-stu-id="03067-435">Visio</span></span>

- <span data-ttu-id="03067-436">Ein Problem wurde behoben, bei dem Visio während des Schließens manchmal nicht mehr funktionierte.</span><span class="sxs-lookup"><span data-stu-id="03067-436">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="03067-437">Das Feature "Form suchen" wurde korrigiert, um alle Ergebnisse anzuzeigen</span><span class="sxs-lookup"><span data-stu-id="03067-437">Fixed "Search Shape" feature to display all the results</span></span>



### <a name="word"></a><span data-ttu-id="03067-438">Word</span><span class="sxs-lookup"><span data-stu-id="03067-438">Word</span></span>

- <span data-ttu-id="03067-p120">Bei diesem Bug wurden bestimmte Richtlinien von Office nicht berücksichtigt (eine Gruppe von Vorlagen wurde auf der Homepage angezeigt, obwohl sie hätten deaktiviert sein müssen). Mit diesem Fix werden die Richtlinien berücksichtigt.</span><span class="sxs-lookup"><span data-stu-id="03067-p120">In this bug, specific policies weren't being honored by Office (a group of templates were being shown on the Home Page when they should have been disabled). With this fix, the policies are being honored.</span></span>


- <span data-ttu-id="03067-441">Bei der gemeinsamen Dokumentenerstellung wird der aktive Entwurf nicht gelöscht, wenn sich die Reihenfolge der Kommentare ändert.</span><span class="sxs-lookup"><span data-stu-id="03067-441">When coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="03067-442">Ein Fehler mit modernen Kommentaren wurde behoben, bei dem Satzzeichen und Zahlen bei einigen internationalen Sprachen auf der falschen Seite standen.</span><span class="sxs-lookup"><span data-stu-id="03067-442">Fixed bug in Modern Commenting where punctuation and numbers would show up on the wrong side for some international languages.</span></span>


- <span data-ttu-id="03067-443">Ein Problem wurde behoben, bei dem die Kombination aus "B" und ")" automatisch in ein Emoji mit Sonnenbrille umgewandelt wurde und die nun als einzelne Zeichen erhalten bleibt</span><span class="sxs-lookup"><span data-stu-id="03067-443">Fixed an issue where the combination of 'B' and ')' would automatically turn into the sunglass wearing emoji and now remain as the individual characters</span></span>


- <span data-ttu-id="03067-444">Text im AutoSpeichern-Popup für lokal gespeicherte Dateien wurde aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="03067-444">Updates text on autosave callout for files saved locally.</span></span>


- <span data-ttu-id="03067-445">Es wurde ein Problem mit Kommentaren während der gemeinsamen Dokumenterstellung behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-445">We fixed an issue with comments during coauthoring.</span></span>


- <span data-ttu-id="03067-446">Ein Problem mit dem Kommentarsymbol wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-446">We fixed an issue relating to comment icon.</span></span>


- <span data-ttu-id="03067-447">Wir haben ein Problem behoben, bei dem kopierte und eingefügte Formatvorlagen im Text, in den sie eingefügt wurden, nicht identisch waren.</span><span class="sxs-lookup"><span data-stu-id="03067-447">We fixed an issue which copy and paste styles may not be same in pasted text.</span></span>


- <span data-ttu-id="03067-448">Optimiert Bedingungen für angebotene Textvorhersagen.</span><span class="sxs-lookup"><span data-stu-id="03067-448">Optimizes conditions for text predictions to be offered.</span></span>


- <span data-ttu-id="03067-449">Ein Problem mit dem Link wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-449">We fixed an issue relating to hyperlink.</span></span>


- <span data-ttu-id="03067-450">Ein Teil des markierten Texts ist nicht sichtbar, wenn im Lesemodus das Design "Darkmode" verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="03067-450">Some select text not visible when using darkmode theme in reading mode.</span></span>


- <span data-ttu-id="03067-451">Es wurde ein Problem mit dem automatischen Speichern behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-451">We fixed an issue in auto save.</span></span>


- <span data-ttu-id="03067-452">Wir haben einen Fix für Application.OnTime erstellt, wenn die Methode möglicherweise nicht richtig ausgelöst wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-452">We made a fix in Application.OnTime where it might not trigger correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="03067-453">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-453">Office Suite</span></span>

- <span data-ttu-id="03067-454">Ein Leistungsproblem im Zusammenhang mit der Textiteration wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-454">Fixed a performance issue related to iteration of text.</span></span>


- <span data-ttu-id="03067-455">Behebt ein Problem mit der Unterstützung von GDI+ LineJoinMiterClipped in Office.</span><span class="sxs-lookup"><span data-stu-id="03067-455">Fixes an issue with support of GDI+ LineJoinMiterClipped in Office.</span></span>


- <span data-ttu-id="03067-456">Diese Version verbessert die Verarbeitung von zeilenübergreifenden vertraulichen Inhalten, wenn sich das Schlüsselwort in der ersten Zeile eines Dokuments befindet.</span><span class="sxs-lookup"><span data-stu-id="03067-456">This release improves handling of line-spanning sensitive content when the keyword is on the first line of a document.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2103-april-13"></a><span data-ttu-id="03067-458">Version 2103: 13. April</span><span class="sxs-lookup"><span data-stu-id="03067-458">Version 2103: April 13</span></span>
<span data-ttu-id="03067-459">*Version 2103 (Build 13901.20400)*</span><span class="sxs-lookup"><span data-stu-id="03067-459">*Version 2103 (Build 13901.20400)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="03067-460">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-460">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="03067-461">Teams</span><span class="sxs-lookup"><span data-stu-id="03067-461">Teams</span></span>

- <span data-ttu-id="03067-462">**Dynamische Ansicht** Die dynamische Ansicht optimiert automatisch freigegebene Inhalte und Video-Teilnehmer in Teams-Besprechungen.</span><span class="sxs-lookup"><span data-stu-id="03067-462">**Dynamic view** Dynamic view automatically optimizes shared content and video participants in Teams meetings.</span></span> <span data-ttu-id="03067-463">Mit neuen Steuerelementen können Sie die Ansicht an Ihre Vorlieben und Bedürfnisse anpassen, z. B. die Möglichkeit, freigegebene Inhalte und bestimmte Teilnehmer nebeneinander anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="03067-463">New controls let you personalize the view to suit your preferences and needs, such as the ability to show shared content and specific participants side-by-side.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2103-april-10"></a><span data-ttu-id="03067-465">Version 2103: 10. April</span><span class="sxs-lookup"><span data-stu-id="03067-465">Version 2103: April 10</span></span>
<span data-ttu-id="03067-466">*Version 2103 (Build 13901.20400)*</span><span class="sxs-lookup"><span data-stu-id="03067-466">*Version 2103 (Build 13901.20400)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-468">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-468">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-469">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-469">Excel</span></span>

- <span data-ttu-id="03067-470">Ein potenzielles Problem mit Ressourcenkonflikten in Word beim Zeichnen eines Bilds wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-470">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-471">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-471">Outlook</span></span>

- <span data-ttu-id="03067-472">Ein Problem wurde behoben, das dazu führte, dass Benutzern beim Hinzufügen eines Kalenders fälschlicherweise die Meldung „Dies kann eine Weile dauern“ angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-472">We fixed an issue that cause users to erroneously see a "This may take a while" message when adding a calendar.</span></span>

- <span data-ttu-id="03067-473">Ein Problem wurde behoben, das dazu führte, dass Stellvertretungen als Organisator von Besprechungen angezeigt wurden, die in neu hinzugefügten Kalendern erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-473">We fixed an issue that caused delegates to appear as the organizer of meetings created on newly added calendars.</span></span>  <span data-ttu-id="03067-474">Besprechungen in diesem Zustand wurden im Kalender des Prinzipals nicht angezeigt.</span><span class="sxs-lookup"><span data-stu-id="03067-474">Meetings in this state did not appear on the principal's calendar.</span></span>

- <span data-ttu-id="03067-475">Ein potenzielles Problem mit Ressourcenkonflikten in Word beim Zeichnen eines Bilds wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-475">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="03067-476">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-476">Powerpoint</span></span>

- <span data-ttu-id="03067-477">Ein potenzielles Problem mit Ressourcenkonflikten in Word beim Zeichnen eines Bilds wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-477">Fixed a potential resource contention issue in word when drawing an image.</span></span>

### <a name="word"></a><span data-ttu-id="03067-478">Word</span><span class="sxs-lookup"><span data-stu-id="03067-478">Word</span></span>

- <span data-ttu-id="03067-479">Ein potenzielles Problem mit Ressourcenkonflikten in Word beim Zeichnen eines Bilds wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-479">Fixed a potential resource contention issue in word when drawing an image.</span></span>

- <span data-ttu-id="03067-480">Ein Problem wurde behoben, bei dem das System in der Druckvorschau nicht mehr reagierte.</span><span class="sxs-lookup"><span data-stu-id="03067-480">Fixed a non-responsive issue while in Print preview.</span></span>

- <span data-ttu-id="03067-481">Text im AutoSpeichern-Popup für lokal gespeicherte Dateien wurde aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="03067-481">Updates text on autosave callout for files saved locally.</span></span>

### <a name="office-suite"></a><span data-ttu-id="03067-482">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-482">Office Suite</span></span>

- <span data-ttu-id="03067-483">Ein Fehler wurde behoben, der auftrat, wenn eine SyncBacked-Datei offline geöffnet und dann in der App umbenannt wurde, bevor sie gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-483">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2103-april-02"></a><span data-ttu-id="03067-485">Version 2103: 2. April</span><span class="sxs-lookup"><span data-stu-id="03067-485">Version 2103: April 02</span></span>
<span data-ttu-id="03067-486">*Version 2103 (Build 13901.20336)*</span><span class="sxs-lookup"><span data-stu-id="03067-486">*Version 2103 (Build 13901.20336)*</span></span>
* <span data-ttu-id="03067-487">Behebung verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="03067-487">Various bugs and performance fixes.</span></span>

## <a name="version-2103-april-1"></a><span data-ttu-id="03067-488">Version 2103: 1. April</span><span class="sxs-lookup"><span data-stu-id="03067-488">Version 2103: April 1</span></span>
<span data-ttu-id="03067-489">*Version 2103 (Build 13901.20148)*</span><span class="sxs-lookup"><span data-stu-id="03067-489">*Version 2103 (Build 13901.20148)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="03067-490">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-490">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="03067-491">Teams</span><span class="sxs-lookup"><span data-stu-id="03067-491">Teams</span></span>

- <span data-ttu-id="03067-492">**Datum/Uhrzeit-Format** Mit diesem Update werden die Datum/Uhrzeit-Formate in Teams an die regionalen Einstellungen der Mac- und Windows-Betriebssysteme angepasst.</span><span class="sxs-lookup"><span data-stu-id="03067-492">**Date/Time format** With this update, the date/time formats in Teams will match the Mac and Windows operating system regional settings.</span></span> <span data-ttu-id="03067-493">Zuvor zeigte Teams Datum/Uhrzeit nur in dem Format an, das der Sprache der Anwendung entsprach.</span><span class="sxs-lookup"><span data-stu-id="03067-493">Previously, Teams would only show date/time in the format corresponding to the application's language.</span></span> <span data-ttu-id="03067-494">Es ist wichtig zu beachten, dass nur der gregorianische Kalender unterstützt wird, unabhängig von der Kalendereinstellung des Betriebssystems.</span><span class="sxs-lookup"><span data-stu-id="03067-494">It's important to note that only the Gregorian calendar is supported regardless of the operating system's calendar setting.</span></span> 

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2103-march-30"></a><span data-ttu-id="03067-496">Version 2103: 30. März</span><span class="sxs-lookup"><span data-stu-id="03067-496">Version 2103: March 30</span></span>
<span data-ttu-id="03067-497">*Version 2103 (Build 13901.20312)*</span><span class="sxs-lookup"><span data-stu-id="03067-497">*Version 2103 (Build 13901.20312)*</span></span>
* <span data-ttu-id="03067-498">Behebung verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="03067-498">Various bugs and performance fixes.</span></span>

## <a name="version-2103-march-28"></a><span data-ttu-id="03067-499">Version 2103: 28. März</span><span class="sxs-lookup"><span data-stu-id="03067-499">Version 2103: March 28</span></span>
<span data-ttu-id="03067-500">*Version 2103 (Build 13901.20306)*</span><span class="sxs-lookup"><span data-stu-id="03067-500">*Version 2103 (Build 13901.20306)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-502">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-502">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-503">Outlook</span></span>

- <span data-ttu-id="03067-504">Wir haben ein Problem behoben, durch das Outlook bei einigen Benutzern beim Synchronisieren von Änderungen der Ordnerhierarchie unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-504">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


- <span data-ttu-id="03067-505">Wir haben einige Probleme behoben, die dazu geführt haben, dass bei einigen Benutzern die Plätze des primären und sekundären Kalenders im Navigationsbereich vertauscht waren.</span><span class="sxs-lookup"><span data-stu-id="03067-505">We fixed an issue that caused some users to see their primary and secondary calendar switching places in the Navigation Pane.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2103-march-22"></a><span data-ttu-id="03067-507">Version 2103: 22. März</span><span class="sxs-lookup"><span data-stu-id="03067-507">Version 2103: March 22</span></span>
<span data-ttu-id="03067-508">*Version 2103 (Build 13901.20230)*</span><span class="sxs-lookup"><span data-stu-id="03067-508">*Version 2103 (Build 13901.20230)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-510">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-510">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-511">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-511">Outlook</span></span>

- <span data-ttu-id="03067-512">Wir haben ein Problem behoben, durch das Benutzern mehr Signaturen als erwartet angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-512">We fixed an issue that caused users to see more signatures than expected.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2103-march-15"></a><span data-ttu-id="03067-514">Version 2103: 15. März</span><span class="sxs-lookup"><span data-stu-id="03067-514">Version 2103: March 15</span></span>
<span data-ttu-id="03067-515">*Version 2103 (Build 13901.20170)*</span><span class="sxs-lookup"><span data-stu-id="03067-515">*Version 2103 (Build 13901.20170)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-517">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-517">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="03067-518">Project</span><span class="sxs-lookup"><span data-stu-id="03067-518">Project</span></span>

- <span data-ttu-id="03067-519">Ein Problem wurde behoben, bei dem Visio während des Schließens manchmal nicht mehr funktionierte.</span><span class="sxs-lookup"><span data-stu-id="03067-519">Fixed an issue where Visio could stop working during close.</span></span>


### <a name="visio"></a><span data-ttu-id="03067-520">Visio</span><span class="sxs-lookup"><span data-stu-id="03067-520">Visio</span></span>

- <span data-ttu-id="03067-521">Ein Problem wurde behoben, bei dem Visio während des Schließens manchmal nicht mehr funktionierte.</span><span class="sxs-lookup"><span data-stu-id="03067-521">Fixed an issue where Visio could stop working during close.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

[//]: # (FEATUREDETAILS CONTENT START NICHT ENTFERNEN)
## <a name="version-2103-march-11"></a><span data-ttu-id="03067-524">Version 2103: 11. März</span><span class="sxs-lookup"><span data-stu-id="03067-524">Version 2103: March 11</span></span>
<span data-ttu-id="03067-525">*Version 2103 (Build 13901.20148)*</span><span class="sxs-lookup"><span data-stu-id="03067-525">*Version 2103 (Build 13901.20148)*</span></span>

### <a name="feature-updates"></a><span data-ttu-id="03067-526">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-526">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-527">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-527">Excel</span></span>

- <span data-ttu-id="03067-528">**AutoSpeichern und gemeinsame Dokumentenerstellung für vertrauliche, verschlüsselte Dokumente:** Tauschen Sie nicht die Produktivität gegen die Sicherheit ein.</span><span class="sxs-lookup"><span data-stu-id="03067-528">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="03067-529">Mit Microsoft Information Protection können Dokumente, die mit Vertraulichkeitsbezeichnungen verschlüsselt sind, jetzt genauso wie unverschlüsselte Dokumente automatisch gespeichert und mit anderen in Echtzeit gemeinsam bearbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="03067-529">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="03067-530">Erfordert Einverständnis des Mandanten (weitere Informationen: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="03067-530">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-531">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-531">Outlook</span></span>

- <span data-ttu-id="03067-532">**Neue Buchungserfahrung für Konferenzräume und Arbeitsbereiche:** Die Buchungserfahrung für Konferenzräume wurde aktualisiert und zudem neue Funktionen hinzugefügt, mit denen Sie auch einzelne Arbeitsbereiche planen können.</span><span class="sxs-lookup"><span data-stu-id="03067-532">**New conference room and workspace booking experience:** The conference room booking experience has been refreshed, and with it we've added capabilities to allow you to schedule individual workspaces as well</span></span>

### <a name="powerpoint"></a><span data-ttu-id="03067-533">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-533">PowerPoint</span></span>

- <span data-ttu-id="03067-534">**AutoSpeichern und gemeinsame Dokumentenerstellung für vertrauliche, verschlüsselte Dokumente:** Tauschen Sie nicht die Produktivität gegen die Sicherheit ein.</span><span class="sxs-lookup"><span data-stu-id="03067-534">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="03067-535">Mit Microsoft Information Protection können Dokumente, die mit Vertraulichkeitsbezeichnungen verschlüsselt sind, jetzt genauso wie unverschlüsselte Dokumente automatisch gespeichert und mit anderen in Echtzeit gemeinsam bearbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="03067-535">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="03067-536">Erfordert Einverständnis des Mandanten (weitere Informationen: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="03067-536">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="teams"></a><span data-ttu-id="03067-537">Teams</span><span class="sxs-lookup"><span data-stu-id="03067-537">Teams</span></span>

- <span data-ttu-id="03067-538">**Status „Außer Haus** Richten Sie eine Nachricht ein, um anderen bekannt zu geben, dass Sie gerade nicht arbeiten oder im Urlaub sind, und daher nicht antworten können, wenn sie Ihnen eine Chatnachricht senden.</span><span class="sxs-lookup"><span data-stu-id="03067-538">**Out of Office status** Set up a message to let others know you're not working or on vacation so you're not available to reply when they send a chat message to you.</span></span> <span data-ttu-id="03067-539">Ihr „Außer Haus“-Status synchronisiert sich ebenfalls mit den Automatische Antworten in Ihrem Outlook-Kalender.</span><span class="sxs-lookup"><span data-stu-id="03067-539">Your Out of Office status will also sync with Automatic Replies in your Outlook calendar.</span></span>

### <a name="visio"></a><span data-ttu-id="03067-540">Visio</span><span class="sxs-lookup"><span data-stu-id="03067-540">Visio</span></span>

- <span data-ttu-id="03067-541">**Office-Symbole mit neuem Look:** Die Produktsymbole wurden neu gestaltet, um die einfache, leistungsstarke und intelligente Office-Benutzeroberfläche widerzuspiegeln.</span><span class="sxs-lookup"><span data-stu-id="03067-541">**Office icons have a new look:** The product icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span> [<span data-ttu-id="03067-542">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-542">Learn more</span></span>](https://support.office.com/article/a6cdf19a-b2bd-4be1-9515-d74a37aa59bf)

### <a name="word"></a><span data-ttu-id="03067-543">Word</span><span class="sxs-lookup"><span data-stu-id="03067-543">Word</span></span>

- <span data-ttu-id="03067-544">**Dunkler Modus für Word-Dokumente:** Der dunkle Modus kann dabei helfen, die Augen zu entlasten und die Lichtempfindlichkeit zu berücksichtigen, während Sie an Ihren Dokumenten arbeiten.</span><span class="sxs-lookup"><span data-stu-id="03067-544">**Dark Mode for Word documents:** Dark Mode may help reduce eye strain and accommodate light sensitivity while working on your documents.</span></span>

- <span data-ttu-id="03067-545">**AutoSpeichern und gemeinsame Dokumentenerstellung für vertrauliche, verschlüsselte Dokumente:** Tauschen Sie nicht die Produktivität gegen die Sicherheit ein.</span><span class="sxs-lookup"><span data-stu-id="03067-545">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="03067-546">Mit Microsoft Information Protection können Dokumente, die mit Vertraulichkeitsbezeichnungen verschlüsselt sind, jetzt genauso wie unverschlüsselte Dokumente automatisch gespeichert und mit anderen in Echtzeit gemeinsam bearbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="03067-546">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="03067-547">Erfordert Einverständnis des Mandanten (weitere Informationen: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="03067-547">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-550">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-550">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="03067-551">Zugriff</span><span class="sxs-lookup"><span data-stu-id="03067-551">Access</span></span>

- <span data-ttu-id="03067-552">Ein Problem wurde behoben, das beim Entfernen eines externen Laufwerks zu einem unerwarteten Schließen der App führen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-552">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="03067-553">Ein Problem wurde behoben, das, wenn eine externe Anwendung eine Benutzeroberfläche zur Barrierefreiheit anfordert, uns daran hindert, herunterzufahren, bis sie ihre Referenz freigibt.</span><span class="sxs-lookup"><span data-stu-id="03067-553">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


### <a name="excel"></a><span data-ttu-id="03067-554">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-554">Excel</span></span>

- <span data-ttu-id="03067-555">Ein Problem wurde behoben, das beim Entfernen eines externen Laufwerks zu einem unerwarteten Schließen der App führen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-555">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="03067-556">Es wurde ein Problem behoben, das dazu geführt hatte, das Excel beim Versuch, die Registerkarte „Dateitypen“ anzuzeigen, manchmal unerwartet geschlossen wurde, weil es nicht in der Lage war, ein Bild abzurufen.</span><span class="sxs-lookup"><span data-stu-id="03067-556">Fixed an issue where Excel would sometimes close unexpectedly when trying to show the Data Types card due to a not being able to retrieve an image.</span></span>


- <span data-ttu-id="03067-557">Es wurde ein Fehler korrigiert, bei dem sich die Schriftart unerwartet veränderte, wenn ein Multiplikations- oder Divisionszeichen mit einer japanischen Schriftart verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-557">Corrected an issue where the font would change unexpectedly when using a multiplication or divide sign with a Japanese font.</span></span> <span data-ttu-id="03067-558">Wir verwenden jetzt weiterhin dieselbe Schriftart, wenn sie das Zeichen unterstützt.</span><span class="sxs-lookup"><span data-stu-id="03067-558">We now continue to use the same font if it supports the character.</span></span>


- <span data-ttu-id="03067-559">Es wurde ein Problem behoben, das Benutzer am Exportieren von Excel-Arbeitsmappen nach PDF hinderte.</span><span class="sxs-lookup"><span data-stu-id="03067-559">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="03067-560">Ein Problem wurde behoben, das dazu führte, dass Bilder bei Verwendung der Option „Verknüpftes Bild einfügen“ kleiner als erwartet waren.</span><span class="sxs-lookup"><span data-stu-id="03067-560">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="03067-561">Ein Problem wurde behoben, bei dem einige Formatierungen verloren gehen konnten, wenn während der gemeinsamen Dokumentenerstellung ein Blatt kopiert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-561">We fixed an issue where some formatting could be lost when copying a sheet while coauthoring.</span></span>


- <span data-ttu-id="03067-562">Ein Problem wurde behoben, bei dem beim Öffnen einer Arbeitsmappe einige Notizen unerwartet angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-562">We fixed an issue where some notes were unexpectedly shown when opening a workbook.</span></span>


- <span data-ttu-id="03067-563">Ein Problem wurde behoben, bei dem einige PivotTable-Formatierungen die Arbeitsmappe beschädigten, wenn diese im XLS- oder XLT-Format gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-563">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


### <a name="outlook"></a><span data-ttu-id="03067-564">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-564">Outlook</span></span>

- <span data-ttu-id="03067-565">Ein Problem wurde behoben, das beim Entfernen eines externen Laufwerks zu einem unerwarteten Schließen der App führen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-565">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="03067-566">Ein Problem wurde behoben, das dazu führte, dass Benutzern nach dem Erstellen einer neuen Gruppe doppelte Kalendergruppen angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-566">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="03067-567">Ein Problem wurde behoben, das dazu führte, dass Benutzer der Verbesserungen des geteilten Kalenders die Farbe eines Kalenders nicht auf gelb oder braun setzen konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-567">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="03067-568">Wir haben ein Problem behoben, das dazu führte, dass neu hinzugefügte Kalender den Benutzern erst nach einem Neustart von Outlook im Navigationsbereich angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-568">We fixed a problem that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


- <span data-ttu-id="03067-569">Es wurde ein Problem behoben, das dazu führte, dass Nicht-ASCII-Zeichen beim Export in CSV falsch exportiert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-569">We fixed an issue that caused non-ASCII characters to export incorrectly when exporting to CSV.</span></span>


- <span data-ttu-id="03067-570">Wir haben ein Problem behoben, das dazu führte, dass einige Personen nicht auf Signaturen zugreifen konnten, die mit zweiten E-Mail-Konten verbunden waren.</span><span class="sxs-lookup"><span data-stu-id="03067-570">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="03067-571">Wir haben ein Problem behoben, das dazu führte, dass bei der Funktion "Cloud-Einstellungen" die benutzerdefinierten Einstellungen durch die Standardeinstellung überschrieben wurden, nachdem die Benutzer Outlook auf einem neuen Gerät konfiguriert hatten.</span><span class="sxs-lookup"><span data-stu-id="03067-571">We fixed an issue that caused users of the Cloud Settings feature to see customized settings overridden by default setting after configuring Outlook on a new device.</span></span>


- <span data-ttu-id="03067-572">Ein Problem wurde behoben, das dazu führte, dass Benutzersignaturen mit Unicode-Inhalten beschädigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-572">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="03067-573">Ein Problem wurde behoben, das dazu führte, dass Benutzer der Inlineübersetzung kein Feedback abgeben konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-573">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="03067-574">Ein Problem wurde behoben, das dazu führte, dass Anlagen beim Entfernen des DRM-Schutzes dupliziert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-574">We fixed an issue that caused users to see attachments getting duplicated when removing DRM protection.</span></span>


- <span data-ttu-id="03067-575">Es wurde ein Problem behoben, das dazu führte, dass Benutzer beim Erstellen von E-Mails eine Kontaktgruppe mit „Namen überprüfen“ nicht suchen konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-575">We fixed an issue that caused users to be unable to look up a contact group with Check Names  when composing mail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="03067-576">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-576">PowerPoint</span></span>

- <span data-ttu-id="03067-577">Ein Problem wurde behoben, das beim Entfernen eines externen Laufwerks zu einem unerwarteten Schließen der App führen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-577">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="03067-578">Es wurde ein Problem behoben, bei dem im PowerPoint-Diashowmodus Pfeile in Liniendiagrammen nicht wie erwartet angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-578">We fixed an issue where arrows in line charts were not appearing as expected in PowerPoint slideshow mode.</span></span>


- <span data-ttu-id="03067-579">Behebt ein Problem mit Animationsschleifen und Audiolesezeichen.</span><span class="sxs-lookup"><span data-stu-id="03067-579">Fixes an issue with looping animations and audio bookmarks.</span></span>


### <a name="project"></a><span data-ttu-id="03067-580">Project</span><span class="sxs-lookup"><span data-stu-id="03067-580">Project</span></span>

- <span data-ttu-id="03067-581">Ein Problem wurde behoben, bei dem Visio während des Schließens manchmal nicht mehr funktionierte.</span><span class="sxs-lookup"><span data-stu-id="03067-581">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="03067-582">Ein Problem wurde behoben, das beim Entfernen eines externen Laufwerks zu einem unerwarteten Schließen der App führen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-582">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="03067-583">Es wurde ein Problem behoben, das dazu geführt hatte, dass eine zu 100 % abgeschlossene Aufgabe auf den Status „99 % abgeschlossen“ zurückgesetzt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-583">Fixed an issue where a task that are 100% complete may revert back to 99% complete.</span></span>


- <span data-ttu-id="03067-584">Es wurde ein Problem behoben, das zum unerwarteten Schließen von Project geführt hatte, wenn Benutzer JAWS ausgeführt haben oder in den Vorgangsinformationsdialog gewechselt sind.</span><span class="sxs-lookup"><span data-stu-id="03067-584">Fixed an issue where Project may close unexpectedly if you are running JAWS and go to the task information dialog.</span></span>


- <span data-ttu-id="03067-585">Folgendes Problem wurde behoben: Wenn die Indikatorspalte nicht an der ersten Spaltenstelle stand, wurden Sie beim Ausschneiden eines Sammelvorgangs nicht gewarnt, dass auch die Unteraufgaben entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="03067-585">Fixed an issue where if the indicator column is not in the first column spot, when you cut a summary task you aren't warned that the subtasks will also be removed.</span></span>


- <span data-ttu-id="03067-586">Folgendes Problem wurde behoben: Wenn ein Benutzer auf seiner Arbeitszeittabelle die Funktion „Sich selbst zu einem Vorgang hinzufügen“ auswählte, wurden möglicherweise nicht die richtigen Ressourcenverfügbarkeitseinheiten für die erstellte Aufgabe verwendet.</span><span class="sxs-lookup"><span data-stu-id="03067-586">Fixed an issue where if a user selected the Add Yourself to a Task function on their Timesheet, the correctly resource availability units may not be used on the created assignment.</span></span>


- <span data-ttu-id="03067-587">Es wurde ein Problem behoben, bei dem möglicherweise falsche Vorgangsaufteilungen erstellt wurden, wenn ein Projekt aus der Project Web App in einer lokalen Datei gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-587">Fixed an issue where task splits may be wrongly created when saving a project from Project web app to a local file.</span></span> <span data-ttu-id="03067-588">Dies würde beispielsweise bei Verwendung eines Vorgangskalenders mit nicht standardmäßigen Arbeitszeiten auftreten.</span><span class="sxs-lookup"><span data-stu-id="03067-588">This would happen if a task calendar with non-standard working times was being used.</span></span>


### <a name="publisher"></a><span data-ttu-id="03067-589">Publisher</span><span class="sxs-lookup"><span data-stu-id="03067-589">Publisher</span></span>

- <span data-ttu-id="03067-590">Ein Problem wurde behoben, das beim Entfernen eines externen Laufwerks zu einem unerwarteten Schließen der App führen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-590">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="visio"></a><span data-ttu-id="03067-591">Visio</span><span class="sxs-lookup"><span data-stu-id="03067-591">Visio</span></span>

- <span data-ttu-id="03067-592">Ein Problem wurde behoben, bei dem Visio während des Schließens manchmal nicht mehr funktionierte.</span><span class="sxs-lookup"><span data-stu-id="03067-592">Fixed an issue where Visio could stop working during close.</span></span>


- <span data-ttu-id="03067-593">Ein Problem wurde behoben, das beim Entfernen eines externen Laufwerks zu einem unerwarteten Schließen der App führen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-593">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


### <a name="word"></a><span data-ttu-id="03067-594">Word</span><span class="sxs-lookup"><span data-stu-id="03067-594">Word</span></span>

- <span data-ttu-id="03067-595">Es wurde ein Problem behoben, bei dem das Öffnen einer mit einer Microsoft Information Protection (MIP)-Bezeichnung geschützten Datei unbegrenzt hängen bleiben kann, wenn der Benutzer nicht mit einer Identität angemeldet ist, die Zugriff auf die MIP-geschützte Bezeichnung hat.</span><span class="sxs-lookup"><span data-stu-id="03067-595">We fixed an issue where opening a file protected with a Microsoft Information Protection (MIP) label can hang indefinitely if the user is not signed in to an identity that has access to the MIP protected label.</span></span> <span data-ttu-id="03067-596">Der Benutzer ist gezwungen, das Öffnen abbrechen, um die Anmeldeaufforderung anzuzeigen, und das Öffnen ist erst nach diesem Zeitpunkt erfolgreich.</span><span class="sxs-lookup"><span data-stu-id="03067-596">The user is forced to cancel the open to show the sign-in prompt, and the open only succeeds after that point.</span></span> <span data-ttu-id="03067-597">Das Problem wurde behoben, indem die Anmeldeaufforderung während dem Öffnen/Herunterladen angezeigt werden kann.</span><span class="sxs-lookup"><span data-stu-id="03067-597">Fixing this issue by allowing the sign-in prompt to be shown during open/download.</span></span>


- <span data-ttu-id="03067-598">Ein Problem wurde behoben, das beim Entfernen eines externen Laufwerks zu einem unerwarteten Schließen der App führen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-598">We fixed an issue that could lead to an unexpected app close when removing an external drive.</span></span>


- <span data-ttu-id="03067-599">Es wurde ein Problem bei der Verwendung von Diktat in der neuen Word-Kommentierung behoben. Die Diktat-Schaltfläche in der Kommentar-Karte schaltet nun korrekt ein und aus.</span><span class="sxs-lookup"><span data-stu-id="03067-599">We fixed an issue when using Dictation in the new Word Commenting, the Dictation button in the Comment card now correctly toggles on and off.</span></span>


- <span data-ttu-id="03067-600">Bei der gemeinsamen Dokumentenerstellung wird der aktive Entwurf nicht gelöscht, wenn sich die Kommentarreihenfolge ändert.</span><span class="sxs-lookup"><span data-stu-id="03067-600">When coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="03067-601">Es wurde ein Problem behoben, bei dem kein Leerzeichen zwischen Wörtern eingefügt wurde, wenn Benutzer in ihr Dokument diktierten.</span><span class="sxs-lookup"><span data-stu-id="03067-601">Fixed an issue where there was no space being inserted between words when users dictated into their document.</span></span>


- <span data-ttu-id="03067-602">Behebt ein Problem in der Rendering-Pipeline im Zusammenhang mit Scrollebenen, die Scroll- oder Zoomanimationen enthalten.</span><span class="sxs-lookup"><span data-stu-id="03067-602">Fixes an issue in the rendering pipeline related to scrolling layers that contain scroll or zoom animations.</span></span>


- <span data-ttu-id="03067-603">Behebt ein Problem mit Farben, die auf Symbole und SVG-Grafiken mit 3D-Effekten angewendet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-603">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="03067-604">Es wurde ein Problem mit dem Automatischen Speichern behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-604">We fixed an issue in AutoSave.</span></span>


- <span data-ttu-id="03067-605">Es wurde ein Problem mit der Fußnote behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-605">We fixed an issue in footnote.</span></span>


- <span data-ttu-id="03067-606">Es wurde ein Problem behoben, bei dem das Veröffentlichen von mehrzeiligen, in RTL getippten Kommentaren dazu führte, dass die zweite und weitere Zeilen links statt rechts ausgerichtet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-606">We fixed an issue when posting multi-line comments typed in RTL caused the 2nd and onward lines to be aligned to the left instead of the right.</span></span>


- <span data-ttu-id="03067-607">Ein Problem mit der Ausrichtung von mehreren Kommentaren wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-607">We fixed an issue with alignment of multiple comments.</span></span>


- <span data-ttu-id="03067-608">Ein Problem mit den Tastenkombinationen im Aufgabenbereich „Vorlesen“ wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-608">We fixed an issue in Read Aloud task pane keyboard shortcuts.</span></span>


- <span data-ttu-id="03067-609">Wir haben ein Problem mit der Sprachausgabe behoben, bei dem ein Absatz u. U. übersprungen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-609">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="03067-610">Es wurde ein Problem behoben, bei dem die Rechtschreibprüfung zwischen zwei verschiedenen Kontextmenüs für die Rechtschreibkorrektur wechselte.</span><span class="sxs-lookup"><span data-stu-id="03067-610">We fixed an issue where spell check switched between two different spelling correction context menus.</span></span>


- <span data-ttu-id="03067-611">Wir haben ein Problem mit Rich-Text-Inhaltssteuerelementen behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-611">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="03067-612">Wir haben ein Problem behoben, bei dem die Eingabe am Ende eines ausgeblendeten Absatzes dazu führen konnte, dass die Anwendung nicht mehr reagierte.</span><span class="sxs-lookup"><span data-stu-id="03067-612">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


- <span data-ttu-id="03067-613">Es wurde ein Problem behoben, bei dem Spalten möglicherweise überlappenden Text enthalten.</span><span class="sxs-lookup"><span data-stu-id="03067-613">We fixed an issue where columns might have overlapping text.</span></span>


- <span data-ttu-id="03067-614">Ein Problem mit dem Lesezeichen wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-614">We fixed an issue relating to bookmark.</span></span>


- <span data-ttu-id="03067-615">Es wurde ein Problem mit dem Auflösen von Konflikten bei der gemeinsamen Dokumenterstellung gelöst.</span><span class="sxs-lookup"><span data-stu-id="03067-615">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


### <a name="office-suite"></a><span data-ttu-id="03067-616">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-616">Office Suite</span></span>

- <span data-ttu-id="03067-617">OneDrive-Orte werden nun entsprechend der Gruppenrichtlinieneinstellung herausgefiltert.</span><span class="sxs-lookup"><span data-stu-id="03067-617">OneDrive places are now filtered out as appropriate per the group policy setting.</span></span>


- <span data-ttu-id="03067-618">Ein Problem, das bei Verwendung der Sprachausgabe in Text mit mathematischen Formeln auftrat, wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-618">Fixed an issue that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="03067-619">Behebt ein Problem mit der Zuverlässigkeit im Zusammenhang mit der Unterstützung von Office-Apps, die in Sitzung 0 ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="03067-619">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="03067-620">Behebt ein Problem mit der Zuverlässigkeit im Zusammenhang mit der Unterstützung von Office-Apps, die in Sitzung 0 ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="03067-620">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="03067-621">Ein Problem wurde behoben, das beim Laden von EMF-Images dazu führte, dass das System nicht mehr reagierte.</span><span class="sxs-lookup"><span data-stu-id="03067-621">Fixes an issue related to unresponsiveness that may occur when loading EMF images.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2102-march-03"></a><span data-ttu-id="03067-623">Version 2102: 03. März</span><span class="sxs-lookup"><span data-stu-id="03067-623">Version 2102: March 03</span></span>
<span data-ttu-id="03067-624">*Version 2102 (Build 13801.20274)*</span><span class="sxs-lookup"><span data-stu-id="03067-624">*Version 2102 (Build 13801.20274)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-626">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-626">Resolved issues</span></span>
### <a name="word"></a><span data-ttu-id="03067-627">Word</span><span class="sxs-lookup"><span data-stu-id="03067-627">Word</span></span>

- <span data-ttu-id="03067-628">Es wurde ein Problem mit auf Symbole und SVG-Grafiken angewendeten Designinformationen behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-628">Fixes an issue with theme information applied to icons and SVG graphics.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2102-march-01"></a><span data-ttu-id="03067-630">Version 2102: 01. März</span><span class="sxs-lookup"><span data-stu-id="03067-630">Version 2102: March 01</span></span>
<span data-ttu-id="03067-631">*Version 2102 (Build 13801.20266)*</span><span class="sxs-lookup"><span data-stu-id="03067-631">*Version 2102 (Build 13801.20266)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-633">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-633">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-634">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-634">Outlook</span></span>

- <span data-ttu-id="03067-635">**Freigabe an Teams:** Teilen Sie Nachrichten aus Outlook mit einer Person oder einen Kanal in Teams.</span><span class="sxs-lookup"><span data-stu-id="03067-635">**Share to Teams:** Share messages from Outlook with a person or channel in Teams.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-638">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-638">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-639">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-639">Outlook</span></span>

- <span data-ttu-id="03067-640">Ein Problem wurde behoben, das dazu führte, dass Benutzern nach dem Erstellen einer neuen Gruppe doppelte Kalendergruppen angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-640">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="03067-641">Ein Problem wurde behoben, das dazu führte, dass Benutzer der Verbesserungen des geteilten Kalenders die Farbe eines Kalenders nicht auf gelb oder braun setzen konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-641">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="03067-642">Ein Problem wurde behoben, das bei einigen Benutzern dazu führte, dass die App beim Schließen von Nachrichtenfenstern heruntergefahren wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-642">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="03067-643">Ein Problem wurde behoben, das dazu führte, dass Benutzersignaturen mit Unicode-Inhalten beschädigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-643">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="03067-644">Ein Problem wurde behoben, das dazu führte, dass Benutzer der Inlineübersetzung kein Feedback abgeben konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-644">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2102-february-21"></a><span data-ttu-id="03067-646">Version 2102: 21. Februar</span><span class="sxs-lookup"><span data-stu-id="03067-646">Version 2102: February 21</span></span>
<span data-ttu-id="03067-647">*Version 2102 (Build 13801.20182)*</span><span class="sxs-lookup"><span data-stu-id="03067-647">*Version 2102 (Build 13801.20182)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-649">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-649">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-650">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-650">Outlook</span></span>

- <span data-ttu-id="03067-651">**Verfassen Sie Nachrichten mit Ihrer Stimme:** Verwenden Sie die neue Diktatsymbolleiste, neue Sprachbefehle, automatische Zeichensetzung und mehr, um Nachrichten zu verfassen.</span><span class="sxs-lookup"><span data-stu-id="03067-651">**Draft messages with your voice:** Use the new dictation toolbar, voice commands, auto-punctuation, and more to compose messages.</span></span>

### <a name="word"></a><span data-ttu-id="03067-652">Word</span><span class="sxs-lookup"><span data-stu-id="03067-652">Word</span></span>

- <span data-ttu-id="03067-653">**Verfassen Sie Dokumente mit Ihrer Stimme:** Verwenden Sie die neue Diktatsymbolleiste, neue Sprachbefehle und automatische Zeichensetzung, um Dokumente zu verfassen.</span><span class="sxs-lookup"><span data-stu-id="03067-653">**Draft documents with your voice:** Use the new dictation toolbar, voice commands and auto-punctuation to draft documents.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-656">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-656">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-657">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-657">Excel</span></span>

- <span data-ttu-id="03067-658">Ein Problem wurde behoben, das dazu führte, dass Bilder bei Verwendung der Option „Verknüpftes Bild einfügen“ kleiner als erwartet waren.</span><span class="sxs-lookup"><span data-stu-id="03067-658">We fixed an issue which caused images to bee smaller than expected when using the Paste Linked Picture option.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2102-february-16"></a><span data-ttu-id="03067-660">Version 2102: 16. Februar</span><span class="sxs-lookup"><span data-stu-id="03067-660">Version 2102: February 16</span></span>
<span data-ttu-id="03067-661">*Version 2102 (Build 13801.20160)*</span><span class="sxs-lookup"><span data-stu-id="03067-661">*Version 2102 (Build 13801.20160)*</span></span>
* <span data-ttu-id="03067-662">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="03067-662">Various bugs and performance fixes.</span></span>

## <a name="version-2102-february-15"></a><span data-ttu-id="03067-663">Version 2102: 15. Februar</span><span class="sxs-lookup"><span data-stu-id="03067-663">Version 2102: February 15</span></span>
<span data-ttu-id="03067-664">*Version 2102 (Build 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="03067-664">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-666">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-666">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-667">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-667">Outlook</span></span>

- <span data-ttu-id="03067-668">**Die Diktatfunktion ist in weiteren Sprachen verfügbar:** Die Diktatfunktion unterstützt jetzt 7 neue Sprachen: Hindi, Russisch, Polnisch, Portugiesisch (Portugal), Koreanisch, Thailändisch, Chinesisch (Taiwan)</span><span class="sxs-lookup"><span data-stu-id="03067-668">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>

### <a name="word"></a><span data-ttu-id="03067-669">Word</span><span class="sxs-lookup"><span data-stu-id="03067-669">Word</span></span>

- <span data-ttu-id="03067-670">**Die Diktatfunktion ist in weiteren Sprachen verfügbar:** Die Diktatfunktion unterstützt jetzt 7 neue Sprachen: Hindi, Russisch, Polnisch, Portugiesisch (Portugal), Koreanisch, Thailändisch, Chinesisch (Taiwan)</span><span class="sxs-lookup"><span data-stu-id="03067-670">**Dictation is available in more languages:** Dictation now supports 7 new languages: Hindi, Russian, Polish, Portuguese (Portugal), Korean, Thai, Chinese (Taiwan)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-673">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-673">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-674">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-674">Excel</span></span>

- <span data-ttu-id="03067-675">Es wurde ein Problem behoben, das Benutzer am Exportieren von Excel-Arbeitsmappen nach PDF hinderte.</span><span class="sxs-lookup"><span data-stu-id="03067-675">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


### <a name="word"></a><span data-ttu-id="03067-676">Word</span><span class="sxs-lookup"><span data-stu-id="03067-676">Word</span></span>

- <span data-ttu-id="03067-677">Es wurde ein Problem mit dem Auflösen von Konflikten bei der gemeinsamen Dokumenterstellung gelöst.</span><span class="sxs-lookup"><span data-stu-id="03067-677">We fixed an issue in resolving conflicts while in coauthoring.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)


## <a name="version-2102-february-11"></a><span data-ttu-id="03067-679">Version 2102: 11. Februar</span><span class="sxs-lookup"><span data-stu-id="03067-679">Version 2102: February 11</span></span>
<span data-ttu-id="03067-680">*Version 2102 (Build 13801.20158)*</span><span class="sxs-lookup"><span data-stu-id="03067-680">*Version 2102 (Build 13801.20158)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-682">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-682">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="03067-683">Teams</span><span class="sxs-lookup"><span data-stu-id="03067-683">Teams</span></span>

- <span data-ttu-id="03067-684">**2x2-Video in Microsoft Edge- und Chrome-Browsern auf Windows und Mac:** Benutzer können in Teams-Besprechungen in Microsoft Edge- und Chrome-Browsern unter Windows und Mac die Videos von bis zu 4 Teilnehmern anzeigen.</span><span class="sxs-lookup"><span data-stu-id="03067-684">**2x2 video on Edge and Chrome browsers on Windows and Mac** Users can see up to 4 participants' video in Teams meetings in Edge and Chrome browsers on Windows and Mac.</span></span> [<span data-ttu-id="03067-685">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-685">Learn more</span></span>](https://support.microsoft.com/office/using-video-in-microsoft-teams-3647fc29-7b92-4c26-8c2d-8a596904cdae#bkmk_videolayout)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

## <a name="version-2102-february-08"></a><span data-ttu-id="03067-687">Version 2102: 08. Februar</span><span class="sxs-lookup"><span data-stu-id="03067-687">Version 2102: February 08</span></span>
<span data-ttu-id="03067-688">*Version 2102 (Build 13801.20084)*</span><span class="sxs-lookup"><span data-stu-id="03067-688">*Version 2102 (Build 13801.20084)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-690">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-690">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-691">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-691">Outlook</span></span>

- <span data-ttu-id="03067-692">**Microsoft Search-unterstütztes Verfassen (An\CC\BCC), Vorschläge:** Das Hinzufügen von Personen zur An\CC-Zeile wird jetzt von Microsoft Search unterstützt.</span><span class="sxs-lookup"><span data-stu-id="03067-692">**Microsoft Search powered compose (To\CC\BCC) suggestions:** Adding people to the To\CC line is now powered by Microsoft Search.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-695">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-695">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="03067-696">Zugriff</span><span class="sxs-lookup"><span data-stu-id="03067-696">Access</span></span>

- <span data-ttu-id="03067-697">Sie werden jetzt ausgewählte Registerkarten in Access klarer sehen.</span><span class="sxs-lookup"><span data-stu-id="03067-697">You will now see selected tabs clearer in Access.</span></span>


### <a name="excel"></a><span data-ttu-id="03067-698">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-698">Excel</span></span>

- <span data-ttu-id="03067-699">Ein Problem wurde behoben, bei dem bestimmte Diagramme, die diskontinuierliche Zellbereiche verwenden, beim erneuten Öffnen von Dateien nicht geladen wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-699">Fixes issue where certain charts using discontinuous ranges of cells would not load when files are re-opened.</span></span>


- <span data-ttu-id="03067-700">Ein Problem wurde behoben, bei dem Excel nicht gestartet werden konnte bzw. unerwartet geschlossen wurde, wenn bestimmte Einstellungen für den Schutz vor Windows-Sicherheit-Exploits (SimExec, CallerCheck) verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-700">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="03067-701">Ein Problem wurde behoben, bei dem Excel nach der Auswahl einer Datenreihen in einem Diagramm nicht mehr antwortete.</span><span class="sxs-lookup"><span data-stu-id="03067-701">We fixed an issue where Excel would stop responding after selecting a data series in a chart.</span></span>


- <span data-ttu-id="03067-702">Ein Problem wurde behoben, bei dem Excel beim Hinzufügen eines Namens im Dialogfeld "Name definieren" unerwartet beendet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-702">We fixed an issue where Excel would unexpectedly quit when you added a Name in the Define Name dialog.</span></span>


- <span data-ttu-id="03067-703">Wir haben ein Problem mit Bildern behoben, damit diese während eines Zuschneidevorgangs ihr Seitenverhältnis beibehalten.</span><span class="sxs-lookup"><span data-stu-id="03067-703">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="outlook"></a><span data-ttu-id="03067-704">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-704">Outlook</span></span>

- <span data-ttu-id="03067-705">Wir haben ein Problem behoben, bei dem E-Mails als digital signiert versendet wurde, obwohl der Benutzer die Option deaktiviert hatte.</span><span class="sxs-lookup"><span data-stu-id="03067-705">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


- <span data-ttu-id="03067-706">Ein Problem wurde behoben, das dazu führte, dass das Verschlüsselungssymbol bei E-Mails, die mit der Option "Nur verschlüsseln" gesendet wurden, nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-706">We fixed an issue that caused the encryption icon to fail to display for emails sent using the Encrypt Only option.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="03067-707">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-707">PowerPoint</span></span>

- <span data-ttu-id="03067-708">Es wurde ein Problem beim der Anzeigen von Emojis mit Farben behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-708">Fixed an issue related to displaying emojis with color.</span></span>


- <span data-ttu-id="03067-709">Ein Problem mit Bildern wurde behoben, damit diese während eines Zuschneidevorgangs ihr Seitenverhältnis beibehalten.</span><span class="sxs-lookup"><span data-stu-id="03067-709">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


### <a name="visio"></a><span data-ttu-id="03067-710">Visio</span><span class="sxs-lookup"><span data-stu-id="03067-710">Visio</span></span>

- <span data-ttu-id="03067-711">Dieses Problem beim Rendern von Formen aus CAD-Schablonen wurde jetzt behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-711">This issue on shape rendering from CAD stencils has now been fixed.</span></span> <span data-ttu-id="03067-712">Das Problem wird mit dem neuesten Build behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-712">Users will see the issue resolved in the latest build.</span></span>


### <a name="word"></a><span data-ttu-id="03067-713">Word</span><span class="sxs-lookup"><span data-stu-id="03067-713">Word</span></span>

- <span data-ttu-id="03067-714">Es wurde ein Problem behoben, bei dem die Eingabe in Echtzeit und die Anwesenheit nicht wiederhergestellt werden konnten, nachdem die Internetverbindung für eine gewisse Zeit unterbrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-714">This fixes an issue that prevented real-time typing and presence from being restored after losing internet connectivity for a period of time.</span></span>


- <span data-ttu-id="03067-715">Wenn ein Benutzer Text in einem Kommentar auswählt, hebt Word jetzt die Auswahl von ausgewähltem Text in anderen Kommentaren auf.</span><span class="sxs-lookup"><span data-stu-id="03067-715">When a user selects text in a comment, Word now unselects selected text in other comments.</span></span>


- <span data-ttu-id="03067-716">Word erlaubt jetzt das Kopieren von Kommentartext nach Excel.</span><span class="sxs-lookup"><span data-stu-id="03067-716">Word now allows copying comment text into Excel.</span></span>


- <span data-ttu-id="03067-717">Wir haben ein Problem behoben, bei dem das Ausführen des VBA-Makros ExportAsFixedFormat2 mit dem Fehler „Präsentation (unbekanntes Mitglied) unzulässiger Wert“ fehlschlug.</span><span class="sxs-lookup"><span data-stu-id="03067-717">We fixed an issue when running the VBA macro ExportAsFixedFormat2 fails with an error stating "Presentation (unknown member) illegal value".</span></span>


- <span data-ttu-id="03067-718">Wir haben ein Problem mit Bildern behoben, damit diese während eines Zuschneidevorgangs ihr Seitenverhältnis beibehalten.</span><span class="sxs-lookup"><span data-stu-id="03067-718">Fixed an issue related to pictures retaining their aspect ratio during a crop operation.</span></span>


- <span data-ttu-id="03067-719">Wir haben ein Problem behoben, bei dem der Kommentar mit Links möglicherweise abgeschnitten wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-719">We fixed an issue which the comment may be truncated with links.</span></span>


- <span data-ttu-id="03067-720">Wir haben ein Problem beim Speichern nach SharePoint Online behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-720">We fixed an issue in saving to SharePoint Online</span></span>


- <span data-ttu-id="03067-721">Wir haben ein Problem beim Exportieren von Word-Dokumenten nach PDF behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-721">We fixed an issue in exporting Word document to PDF.</span></span>


- <span data-ttu-id="03067-722">Es wurde ein Problem mit AutoWiederherstellen behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-722">We fixed an issue with AutoRecover.</span></span>

- <span data-ttu-id="03067-723">Es wurde ein Problem bei der gemeinsamen Dokumentenerstellung mit DRM-geschützten Dateien behoben</span><span class="sxs-lookup"><span data-stu-id="03067-723">We fixed an issue when coauthoring with DRM protected files</span></span>


### <a name="office-suite"></a><span data-ttu-id="03067-724">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-724">Office Suite</span></span>

- <span data-ttu-id="03067-725">Ein Fehler in PowerPoint wurde behoben, bei dem das Einfügen von Aufzählungszeichen als Bilder dazu führte, dass die Aufzählungszeichen verschwanden.</span><span class="sxs-lookup"><span data-stu-id="03067-725">Fixing a bug in PowerPoint where inserting bullets as images would result in bullets disappearing.</span></span> <span data-ttu-id="03067-726">Durch diese Korrektur werden sie zuverlässiger dargestellt.</span><span class="sxs-lookup"><span data-stu-id="03067-726">This fix makes it so they render more reliably.</span></span>

- <span data-ttu-id="03067-727">Es wurde ein Problem behoben, bei dem Office unter bestimmten Umständen Vertraulichkeitsbezeichnungen für ein angemeldetes Konto anzeigte, wenn stattdessen Vertraulichkeitsbezeichnungen für ein anderes angemeldetes Konto angezeigt werden sollten.</span><span class="sxs-lookup"><span data-stu-id="03067-727">Fixed an issue where Office would in some circumstances present sensitivity labels for one signed-in account when it should present sensitivity labels for a different signed-in account.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2101-february-03"></a><span data-ttu-id="03067-729">Version 2101: 03. Februar</span><span class="sxs-lookup"><span data-stu-id="03067-729">Version 2101: February 03</span></span>
<span data-ttu-id="03067-730">*Version 2101 (Build 13628.20330)*</span><span class="sxs-lookup"><span data-stu-id="03067-730">*Version 2101 (Build 13628.20330)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-732">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-732">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-733">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-733">Outlook</span></span>

- <span data-ttu-id="03067-734">Ein Problem wurde behoben, das die Anzeige der richtigen Standardsignatur im OWA beeinträchtigt hat.</span><span class="sxs-lookup"><span data-stu-id="03067-734">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="03067-735">Ein Problem wurde behoben, das dazu geführt har, dass das Verschlüsselungssymbol bei E-Mails, die mit der Option „Nur mit Verschlüsselung“ gesendet wurden, nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-735">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2101-february-02"></a><span data-ttu-id="03067-737">Version 2101: 02. Februar</span><span class="sxs-lookup"><span data-stu-id="03067-737">Version 2101: February 02</span></span>
<span data-ttu-id="03067-738">*Version 2101 (Build 13628.20320)*</span><span class="sxs-lookup"><span data-stu-id="03067-738">*Version 2101 (Build 13628.20320)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-740">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-740">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-741">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-741">Outlook</span></span>

- <span data-ttu-id="03067-742">Es wurde ein Problem behoben, das dazu führte, dass das System hängen blieb, wenn Benutzer die Einstellungen unter "Cloudeinstellungen" aktualisierten.</span><span class="sxs-lookup"><span data-stu-id="03067-742">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2101-january-25"></a><span data-ttu-id="03067-744">Version 2101: 25. Januar</span><span class="sxs-lookup"><span data-stu-id="03067-744">Version 2101: January 25</span></span>
<span data-ttu-id="03067-745">*Version 2101 (Build 13628.20274)*</span><span class="sxs-lookup"><span data-stu-id="03067-745">*Version 2101 (Build 13628.20274)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-747">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-747">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-748">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-748">Excel</span></span>

- <span data-ttu-id="03067-749">**Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar.</span><span class="sxs-lookup"><span data-stu-id="03067-749">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="03067-750">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-750">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="03067-751">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-751">Outlook</span></span>

- <span data-ttu-id="03067-752">**Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar.</span><span class="sxs-lookup"><span data-stu-id="03067-752">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="03067-753">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-753">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a><span data-ttu-id="03067-754">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-754">PowerPoint</span></span>

- <span data-ttu-id="03067-755">**Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar.</span><span class="sxs-lookup"><span data-stu-id="03067-755">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> <span data-ttu-id="03067-756">[Weitere Informationen](/microsoft-365/compliance/sensitivity-labels).</span><span class="sxs-lookup"><span data-stu-id="03067-756">[Learn more](/microsoft-365/compliance/sensitivity-labels).</span></span>


### <a name="word"></a><span data-ttu-id="03067-757">Word</span><span class="sxs-lookup"><span data-stu-id="03067-757">Word</span></span>

- <span data-ttu-id="03067-758">**Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar.</span><span class="sxs-lookup"><span data-stu-id="03067-758">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="03067-759">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-759">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)


### <a name="resolved-issues"></a><span data-ttu-id="03067-760">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-760">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-761">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-761">Outlook</span></span>

- <span data-ttu-id="03067-762">Ein Problem wurde behoben, das bei Benutzern mit freigegebenen oder delegierten Postfächern mit großen Hierarchien in ihrem Profil zu Blockaden führte.</span><span class="sxs-lookup"><span data-stu-id="03067-762">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)



## <a name="version-2101-january-18"></a><span data-ttu-id="03067-764">Version 2101: 18. Januar</span><span class="sxs-lookup"><span data-stu-id="03067-764">Version 2101: January 18</span></span>
<span data-ttu-id="03067-765">*Version 2101 (Build 13628.20158)*</span><span class="sxs-lookup"><span data-stu-id="03067-765">*Version 2101 (Build 13628.20158)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)



[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-769">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-769">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="03067-770">Project</span><span class="sxs-lookup"><span data-stu-id="03067-770">Project</span></span>

- <span data-ttu-id="03067-771">Ein Problem wurde behoben, bei dem keine Rahmen für Vorgänge in der Teamplaneransicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-771">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="03067-772">Ein Problem wurde behoben, bei dem Drag & Drop für Aufgaben in der Teamplaneransicht nicht funktioniert hat.</span><span class="sxs-lookup"><span data-stu-id="03067-772">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2101-january-13"></a><span data-ttu-id="03067-774">Version 2101: 13. Januar</span><span class="sxs-lookup"><span data-stu-id="03067-774">Version 2101: January 13</span></span>
<span data-ttu-id="03067-775">*Version 2101 (Build 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="03067-775">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)
### <a name="feature-updates"></a><span data-ttu-id="03067-777">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-777">Feature updates</span></span>
### <a name="teams"></a><span data-ttu-id="03067-778">Teams</span><span class="sxs-lookup"><span data-stu-id="03067-778">Teams</span></span>
- <span data-ttu-id="03067-779">**Weitere Designs:** Für Desktop- und Webclients sind jetzt neue Designs verfügbar.</span><span class="sxs-lookup"><span data-stu-id="03067-779">**More themes:** New themes are now available for desktop and web clients.</span></span>

- <span data-ttu-id="03067-780">**PPT-Freigabe:** Referentenansicht in Teams. Sobald Sie eine PowerPoint-Datei in der Teilen-Leiste von Teams auswählen, wird automatisch die Referentenansicht geöffnet.</span><span class="sxs-lookup"><span data-stu-id="03067-780">**PPT Sharing:** Presenter View in Teams Once you select a PowerPoint file from the Teams Share Tray, Presenter View is opened automatically.</span></span> <span data-ttu-id="03067-781">Die aktuelle Folie, die Foliennotizen und ein Miniaturansichtenstreifen aller Folien im Deck für eine einfache Ad-hoc-Foliennavigation wird angezeigt.</span><span class="sxs-lookup"><span data-stu-id="03067-781">You can see the current slide, the slide notes, and a thumbnail strip of all the slides in the deck for easy ad-hoc slide navigation.</span></span> <span data-ttu-id="03067-782">Diese Ansicht befindet sich vollständig im Hintergrund, ist privat und nur für den Referenten bestimmt, der die Präsentation leitet.</span><span class="sxs-lookup"><span data-stu-id="03067-782">This view is completely behind the scenes, and it’s private to the presenter in control.</span></span> <span data-ttu-id="03067-783">Ihr Publikum kann nur die aktuelle Folie (hervorgehoben im großen roten Kasten) oder die Folie sehen, zu der es navigieren möchte (sofern die Zuschauernavigation nicht von Ihnen gesperrt wurde).</span><span class="sxs-lookup"><span data-stu-id="03067-783">Your audience can only see your current slide (highlighted in the big red box), or the slide that they choose to navigate to (if audience navigation is not locked by you).</span></span> 

- <span data-ttu-id="03067-784">**Computerton bei Desktop- oder Fensterfreigabe auf Mac einbeziehen:** Wenn Sie einen Desktop oder ein Fenster aus Teams auf dem Mac freigeben, können Sie jetzt auch den Ton Ihres Computers freigeben, damit die Personen, die an der Besprechung teilnehmen, den Ton aus Ihrem Computer hören können.</span><span class="sxs-lookup"><span data-stu-id="03067-784">**Include computer sound when desktop or window sharing on Mac** When you share a desktop or window from Teams on Mac, you can now include your computer's sound so people that have joined the meeting can hear the audio playing out of your computer.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)
<br/>

## <a name="version-2101-january-09"></a><span data-ttu-id="03067-786">Version 2101: 9. Januar</span><span class="sxs-lookup"><span data-stu-id="03067-786">Version 2101: January 09</span></span>
<span data-ttu-id="03067-787">*Version 2101 (Build 13628.20118)*</span><span class="sxs-lookup"><span data-stu-id="03067-787">*Version 2101 (Build 13628.20118)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-789">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-789">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-790">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-790">Outlook</span></span>

- <span data-ttu-id="03067-791">**Schreibvorschläge mit einem Klick:** Übernehmen Sie Schreibvorschläge mit nur einem Klick.</span><span class="sxs-lookup"><span data-stu-id="03067-791">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="03067-792">Der Editor korrigiert die Rechtschreibung und Grammatik und gibt Ihnen Anregungen, um Ihren Text zu optimieren.</span><span class="sxs-lookup"><span data-stu-id="03067-792">Editor corrects spelling and grammar and gives you ideas for refining your writing.</span></span> [<span data-ttu-id="03067-793">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-793">Learn more</span></span>](https://support.office.com/article/1e72a440-89a6-457c-bd76-cd5cea901dc0)<br /><span data-ttu-id="03067-794">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://insider.office.com/de-DE/blog/microsoft-editor-gets-an-upgrade)</span><span class="sxs-lookup"><span data-stu-id="03067-794">See details in [blog post](https://insider.office.com/de-DE/blog/microsoft-editor-gets-an-upgrade)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-797">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-797">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-798">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-798">Outlook</span></span>

- <span data-ttu-id="03067-799">Wir haben ein Problem behoben, das bei einigen Benutzern dazu führte, dass Outlook in bestimmten Suchszenarien unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-799">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2101-january-07"></a><span data-ttu-id="03067-801">Version 2101: 7. Januar</span><span class="sxs-lookup"><span data-stu-id="03067-801">Version 2101: January 07</span></span>
<span data-ttu-id="03067-802">*Version 2101 (Build 13628.20030)*</span><span class="sxs-lookup"><span data-stu-id="03067-802">*Version 2101 (Build 13628.20030)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-804">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-804">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-805">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-805">Excel</span></span>

- <span data-ttu-id="03067-806">**Blenden Sie viele Blätter gleichzeitig ein:** Sie müssen nicht mehr ein Blatt nach dem anderen einblenden – Sie können mehrere ausgeblendete Blätter gleichzeitig einblenden.</span><span class="sxs-lookup"><span data-stu-id="03067-806">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="03067-807">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-807">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

- <span data-ttu-id="03067-808">**Verbesserte Dialogfelder für bedingte Formatierung:** Die Größe von Dialogfeldern für bedingte Formatierung kann jetzt geändert und die Regel mit einem einzigen Klick dupliziert werden.</span><span class="sxs-lookup"><span data-stu-id="03067-808">**Improved Conditional Formatting dialogs:** Conditional Formatting dialogs are now resizable, and now you can duplicate the rule with a single click.</span></span> [<span data-ttu-id="03067-809">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-809">Learn more</span></span>](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-812">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-812">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-813">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-813">Excel</span></span>

- <span data-ttu-id="03067-814">Ein Problem wurde behoben, bei dem Excel fälschlicherweise eine Meldungsleiste anzeigt, dass eine neue Version der Datei verfügbar ist, und den Benutzer auffordert, seine Änderungen in einer Kopie der Arbeitsmappe zu speichern oder die Änderungen zu verwerfen.</span><span class="sxs-lookup"><span data-stu-id="03067-814">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="03067-815">Es wurde ein Problem mit dem Wechsel von Trennzeichen nach einem Aufruf von Selection.Parent.Copy behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-815">Fixed an issue with switching separators after a Selection.Parent.Copy call.</span></span>


- <span data-ttu-id="03067-816">Leistungsverbesserungen wurden erzielt, wenn Formatvorlagen auf Pivot-Tabellen angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="03067-816">Made a performance improvement when applying formatting styles to pivot tables.</span></span>


- <span data-ttu-id="03067-817">Es wurde ein Problem behoben, bei dem Excel möglicherweise Makros ohne Anfrage deaktiviert lässt, wenn eine Excel-Add-In-Datei geöffnet wird, die Excel 4.0 Makros beinhaltet.</span><span class="sxs-lookup"><span data-stu-id="03067-817">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="03067-818">Aktualisierung, damit die Einstellungen für Dezimal- und Tausendertrennzeichen übernommen werden, wenn ein Diagramm aus Excel kopiert und in Word eingefügt wird</span><span class="sxs-lookup"><span data-stu-id="03067-818">Update so that decimal and thousands separators settings carryover when copying a chart from Excel and pasting into Word</span></span>


- <span data-ttu-id="03067-819">Ein Problem wurde behoben, durch das Excel beim Öffnen von UNC-Dateien mit ungültigen Dateiattributen (Erstellungszeit, Änderungszeit usw.) unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-819">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="03067-820">Es wurde ein Problem behoben, das bei Verwendung der STOCKHISTORY-Funktion die Warnung „keine Ressourcen mehr“ verursachen könnte.</span><span class="sxs-lookup"><span data-stu-id="03067-820">Fixed an issue which could cause an "out of resources" alert when using the STOCKHISTORY function.</span></span>


- <span data-ttu-id="03067-821">Es wurde eine FuzzyClustering dll zur Liste der PQ dlls hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="03067-821">Added a FuzzyClustering dll to PQ dlls list.</span></span>


- <span data-ttu-id="03067-822">Diese Änderung behebt ein Problem im Zusammenhang mit dem Ändern der Umrissfarben von SVG-Bildern.</span><span class="sxs-lookup"><span data-stu-id="03067-822">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="03067-823">Ein Problem wurde behoben, bei dem die Vorschau des eingebetteten Excel-Bereich in PowerPoint eine falsche Größe anzeigt.</span><span class="sxs-lookup"><span data-stu-id="03067-823">We have fixed an issue where Preview of embedded Excel range in PowerPoint shows incorrect size.</span></span>


### <a name="onenote"></a><span data-ttu-id="03067-824">OneNote</span><span class="sxs-lookup"><span data-stu-id="03067-824">OneNote</span></span>

- <span data-ttu-id="03067-825">Diese Änderung adressiert ein Rendering-Problem, das OneNote betrifft.</span><span class="sxs-lookup"><span data-stu-id="03067-825">This change addresses a rendering issue affecting OneNote.</span></span>


### <a name="outlook"></a><span data-ttu-id="03067-826">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-826">Outlook</span></span>

- <span data-ttu-id="03067-827">Ein Problem wurde behoben, das dazu führte, dass Benutzer beim Starten eines Seriendrucks von Word aus nicht angeben konnten, wie lange sie den Zugriff zulassen wollten, was dazu führte, dass sie übermäßig viele Eingabeaufforderungen erhielten.</span><span class="sxs-lookup"><span data-stu-id="03067-827">We fixed an issue that caused users to be unable to specify how long they wanted to allow access for when starting a mail merge from Word, resulting in them getting excess prompts.</span></span>


- <span data-ttu-id="03067-828">Durch diese Änderung kann Outlook eine Exchange-Servereinstellung nutzen, welche die Anzeige des Exchange Online-Archivpostfachs für Endbenutzer unterdrückt.</span><span class="sxs-lookup"><span data-stu-id="03067-828">This change enables Outlook to take advantage of an Exchange server setting that suppresses the display of the Exchange Online Archive Mailbox to end users.</span></span>


- <span data-ttu-id="03067-829">Es wurde ein Problem behoben, das dazu führte, dass Outlook für Benutzer von auf Einlösung basierenden Add-Ins unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-829">We fixed an issue that caused a Outlook to close unexpectedly for users of Redemption based Add-ins.</span></span>


- <span data-ttu-id="03067-830">Es wurde ein Problem behoben, bei dem Benutzer nicht mehr als eine Kategorie für die Suche auswählen konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-830">We fixed and issue that caused users to be unable to select more than one category to search.</span></span>


- <span data-ttu-id="03067-831">Es wurde ein Problem behoben, bei dem die Startzeit einiger Kalenderelemente unerwartet verändert wurden, wenn ein Ereignis aus einem anderen Termin kopiert wird.</span><span class="sxs-lookup"><span data-stu-id="03067-831">We fixed an issue that caused the start time of some calendar items to change unexpectedly when the event is copied from another appointment.</span></span>


- <span data-ttu-id="03067-832">Behebung eines Problems, das dazu führte, dass Klartext-S/MIME-Nachrichten beim Senden verstümmelt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-832">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="03067-833">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-833">PowerPoint</span></span>

- <span data-ttu-id="03067-834">Diese Änderung adressiert ein Problem beim Formen zusammenführen, wenn mit Text gearbeitet wird.</span><span class="sxs-lookup"><span data-stu-id="03067-834">This change addresses an issue with Merge Shapes working with text.</span></span>


- <span data-ttu-id="03067-835">Diese Änderung behebt ein Problem im Zusammenhang mit dem Ändern der Umrissfarben von SVG-Bildern.</span><span class="sxs-lookup"><span data-stu-id="03067-835">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="03067-836">Diese Änderung behebt ein Problem mit der wiederholten Wiedergabe von Hintergrundvideos in einer Bildschirmpräsentation.</span><span class="sxs-lookup"><span data-stu-id="03067-836">This change addresses an issue with looping background videos playback in Slide Show.</span></span>


- <span data-ttu-id="03067-837">Es wurde ein Problem behoben, bei dem der Befehl "Schriftgrad", der in QAT hinzugefügt wurde, beim Aktualisieren automatisch zum nächsten definierten Schriftgrad vervollständigt wird.</span><span class="sxs-lookup"><span data-stu-id="03067-837">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


### <a name="project"></a><span data-ttu-id="03067-838">Project</span><span class="sxs-lookup"><span data-stu-id="03067-838">Project</span></span>

- <span data-ttu-id="03067-839">Ein Problem wurde behoben, bei dem die maximalen Einheiten einer Ressource nicht immer die letzte Aktualisierung der maximalen Einheiten widerspiegelten.</span><span class="sxs-lookup"><span data-stu-id="03067-839">Fixed an issue where a resource's max units would not always reflect the latest update to max units.</span></span>


### <a name="visio"></a><span data-ttu-id="03067-840">Visio</span><span class="sxs-lookup"><span data-stu-id="03067-840">Visio</span></span>

- <span data-ttu-id="03067-841">Das Problem trat aufgrund einer aktuellen Regression auf.</span><span class="sxs-lookup"><span data-stu-id="03067-841">The issue occurred due to a recent regression.</span></span> <span data-ttu-id="03067-842">Dieses Problem wurde gelöst.</span><span class="sxs-lookup"><span data-stu-id="03067-842">We have resolved the issue.</span></span> <span data-ttu-id="03067-843">Im Dialogfeld „als Webseite speichern“ werden die Felder nun nach den Benutzereingaben ordnungsgemäß ausgefüllt, und die Benutzer können Ihre Dateien nahtlos als Webseiten speichern.</span><span class="sxs-lookup"><span data-stu-id="03067-843">"Save as Web Page" dialog will now have the fields correctly populated as per the user inputs and users can seamlessly save their files as web pages.</span></span>


- <span data-ttu-id="03067-p144">Dieses Problem wurde behoben. Sie können jetzt Visio-Dateien als Objekte in anderen Office-Anwendungen wie PowerPoint und Word einbetten und aus diesen Anwendungen nahtlos darauf zugreifen.</span><span class="sxs-lookup"><span data-stu-id="03067-p144">This issue has been fixed. You can now embed Visio files as objects in other Office applications like PowerPoint and Word and seamlessly access them from within these applications.</span></span>


### <a name="word"></a><span data-ttu-id="03067-846">Word</span><span class="sxs-lookup"><span data-stu-id="03067-846">Word</span></span>

- <span data-ttu-id="03067-847">Es wurde ein Problem behoben, bei dem Computer mit benutzerdefinierten Hash-Einstellungen Probleme bekamen, wenn sie in eine Gemeinschaftssitzung mit einer anderen Hash-Einstellung als sha512 eintraten.</span><span class="sxs-lookup"><span data-stu-id="03067-847">Fixed an issue where machines with custom hash settings were running in to issues when they got into a collab session with a hash setting other than sha512.</span></span>


- <span data-ttu-id="03067-848">Diese Änderung behebt ein Problem im Zusammenhang mit dem Ändern der Umrissfarben von SVG-Bildern.</span><span class="sxs-lookup"><span data-stu-id="03067-848">This change addresses an issue related to changing outline colors of SVG images.</span></span>


- <span data-ttu-id="03067-849">Ein Problem beim Bearbeiten von Kommentaren mit @erwähnen wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-849">Fixed an issue when editing commenting post with @mention.</span></span>


- <span data-ttu-id="03067-850">Ein Problem wurde behoben, um moderne Kommentare robuster zu machen.</span><span class="sxs-lookup"><span data-stu-id="03067-850">Fixed an issue to make Modern comments more robust.</span></span>


- <span data-ttu-id="03067-851">Es wurde ein Problem mit dem Löschen von modernen Kommentaren in einem Inhaltssteuerelement behoben, das als nicht bearbeitbar gekennzeichnet ist.</span><span class="sxs-lookup"><span data-stu-id="03067-851">We fixed an issue around deleting modern comments in a content control that is marked as not editable.</span></span>


- <span data-ttu-id="03067-852">Es wurde ein Problem mit der Animation behoben, wenn am Ende der Kommentarkarte eine Eingabe gemacht wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-852">Fix animation when typing on the bottom of a comment card.</span></span>


- <span data-ttu-id="03067-853">Behebung des Problems, bei dem das Antwortfeld auf einer Kommentarkarte nicht auf dem Bildschirm angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-853">Fixes an issue where the reply box on a comment card is off the screen.</span></span>


- <span data-ttu-id="03067-854">Behebung des Problems mit einer Kommentarkarte, die oben auf der Seite angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="03067-854">Fixes an issue with a comment card displaying at top of page.</span></span>


- <span data-ttu-id="03067-855">Behebung eines Problems in Kommentaren, bei denen Text über den Bildschirm hinausgehen kann.</span><span class="sxs-lookup"><span data-stu-id="03067-855">Fixes bug in comments where text can scroll off screen.</span></span>


- <span data-ttu-id="03067-856">Behebung eines Problems mit verschachtelten Bildlaufleisten im Kommentarbereich.</span><span class="sxs-lookup"><span data-stu-id="03067-856">Fix and issue with nested scrollbars in the comments pane.</span></span>


- <span data-ttu-id="03067-857">Kommentarentwürfe verschwinden beim Anlegen einer neuen Word-Instanz.</span><span class="sxs-lookup"><span data-stu-id="03067-857">Comment drafts disappears when creating a new Word instance.</span></span>


- <span data-ttu-id="03067-858">Es wurde ein Problem behoben, bei dem Word beim Speichern von Dokumenten mit verborgenem Text ins PDF-Format hängen bleibt.</span><span class="sxs-lookup"><span data-stu-id="03067-858">We fixed an issue where Word hangs when saving document to PDF with hidden text.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2012-january-04"></a><span data-ttu-id="03067-860">Version 2012: 4. Januar</span><span class="sxs-lookup"><span data-stu-id="03067-860">Version 2012: January 04</span></span>
<span data-ttu-id="03067-861">*Version 2012 (Build 13530.20316)*</span><span class="sxs-lookup"><span data-stu-id="03067-861">*Version 2012 (Build 13530.20316)*</span></span>
* <span data-ttu-id="03067-862">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="03067-862">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-864">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-864">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-865">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-865">Excel</span></span>

- <span data-ttu-id="03067-866">**Erforderliche Kennzeichnung:** Benutzer mit einer von ihren Administratoren festgelegten Richtlinie „Erforderliche Kennzeichnung“ müssen ihre Dokumente und E-Mails kennzeichnen.</span><span class="sxs-lookup"><span data-stu-id="03067-866">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="03067-867">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-867">PowerPoint</span></span>

- <span data-ttu-id="03067-868">**Erforderliche Kennzeichnung:** Benutzer mit einer von ihren Administratoren festgelegten Richtlinie „Erforderliche Kennzeichnung“ müssen ihre Dokumente und E-Mails kennzeichnen.</span><span class="sxs-lookup"><span data-stu-id="03067-868">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>

### <a name="word"></a><span data-ttu-id="03067-869">Word</span><span class="sxs-lookup"><span data-stu-id="03067-869">Word</span></span>

- <span data-ttu-id="03067-870">**Erforderliche Kennzeichnung:** Benutzer mit einer von ihren Administratoren festgelegten Richtlinie „Erforderliche Kennzeichnung“ müssen ihre Dokumente und E-Mails kennzeichnen.</span><span class="sxs-lookup"><span data-stu-id="03067-870">**Mandatory Labeling:** Users with the Mandatory Labeling policy set their Admins will be required to label their documents and emails.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2012-december-28"></a><span data-ttu-id="03067-872">Version 2012: 28. Dezember</span><span class="sxs-lookup"><span data-stu-id="03067-872">Version 2012: December 28</span></span>
<span data-ttu-id="03067-873">*Version 2012 (Build 13530.20264)*</span><span class="sxs-lookup"><span data-stu-id="03067-873">*Version 2012 (Build 13530.20264)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-875">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-875">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-876">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-876">Outlook</span></span>

- <span data-ttu-id="03067-877">Es wurde ein Problem behoben, das bei einigen Kunden dazu führte, dass sich das System beim Laden ihrer Kalender aufhängte.</span><span class="sxs-lookup"><span data-stu-id="03067-877">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2012-december-21"></a><span data-ttu-id="03067-879">Version 2012: 21. Dezember</span><span class="sxs-lookup"><span data-stu-id="03067-879">Version 2012: December 21</span></span>
<span data-ttu-id="03067-880">*Version 2012 (Build 13530.20218)*</span><span class="sxs-lookup"><span data-stu-id="03067-880">*Version 2012 (Build 13530.20218)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-882">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-882">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-883">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-883">Excel</span></span>

- <span data-ttu-id="03067-884">**Überwachungsdaten über vertrauliche Bezeichnungen an M365-Administratoren senden:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, sendet Office Überwachungsdaten an das Back-End der M365-Überwachung, damit Administratoren sie sehen können.</span><span class="sxs-lookup"><span data-stu-id="03067-884">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="03067-885">Dies ist eine Hintergrundfunktionalität (keine Benutzeroberfläche) für Administrator-Zwecke.</span><span class="sxs-lookup"><span data-stu-id="03067-885">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-886">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-886">Outlook</span></span>

- <span data-ttu-id="03067-887">**Einbauen einer Zeitspanne zwischen unmittelbar aufeinander folgenden Besprechungen**: Geben Sie den Teilnehmern Zeit für eine Atempause und oder den Weg zwischen verschiedenen Besprechungsorten, indem Sie festlegen, dass Besprechungen standardmäßig 5–10 Minuten verspätet beginnen.</span><span class="sxs-lookup"><span data-stu-id="03067-887">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="03067-888">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-888">Learn more</span></span>](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

- <span data-ttu-id="03067-889">**Überwachungsdaten über vertrauliche Bezeichnungen an M365-Administratoren senden:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, sendet Office Überwachungsdaten an das Back-End der M365-Überwachung, damit Administratoren sie sehen können.</span><span class="sxs-lookup"><span data-stu-id="03067-889">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="03067-890">Dies ist eine Hintergrundfunktionalität (keine Benutzeroberfläche) für Administrator-Zwecke.</span><span class="sxs-lookup"><span data-stu-id="03067-890">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="03067-891">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-891">PowerPoint</span></span>

- <span data-ttu-id="03067-892">**Überwachungsdaten über vertrauliche Bezeichnungen an M365-Administratoren senden:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, sendet Office Überwachungsdaten an das Back-End der M365-Überwachung, damit Administratoren sie sehen können.</span><span class="sxs-lookup"><span data-stu-id="03067-892">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="03067-893">Dies ist eine Hintergrundfunktionalität (keine Benutzeroberfläche) für Administrator-Zwecke.</span><span class="sxs-lookup"><span data-stu-id="03067-893">This is a silent functionality (no UI) for administrator benefit.</span></span>

### <a name="word"></a><span data-ttu-id="03067-894">Word</span><span class="sxs-lookup"><span data-stu-id="03067-894">Word</span></span>

- <span data-ttu-id="03067-895">**Überwachungsdaten über vertrauliche Bezeichnungen an M365-Administratoren senden:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, sendet Office Überwachungsdaten an das Back-End der M365-Überwachung, damit Administratoren sie sehen können.</span><span class="sxs-lookup"><span data-stu-id="03067-895">**Send audit data about sensitivity labeling to M365 administrators:** When users apply, change, or remove sensitivity labels on their documents and emails, Office will send up audit data to the M365 audit backend for administrators to see.</span></span> <span data-ttu-id="03067-896">Dies ist eine Hintergrundfunktionalität (keine Benutzeroberfläche) für Administrator-Zwecke.</span><span class="sxs-lookup"><span data-stu-id="03067-896">This is a silent functionality (no UI) for administrator benefit.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-899">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-899">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="03067-900">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-900">PowerPoint</span></span>

- <span data-ttu-id="03067-901">Es wurde ein Problem behoben, bei dem der Befehl "Schriftgrad", der in QAT hinzugefügt wurde, beim Aktualisieren automatisch zum nächsten definierten Schriftgrad vervollständigt wird.</span><span class="sxs-lookup"><span data-stu-id="03067-901">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2012-december-14"></a><span data-ttu-id="03067-903">Version 2012: 14. Dezember</span><span class="sxs-lookup"><span data-stu-id="03067-903">Version 2012: December 14</span></span>
<span data-ttu-id="03067-904">*Version 2012 (Build 13530.20144)*</span><span class="sxs-lookup"><span data-stu-id="03067-904">*Version 2012 (Build 13530.20144)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-906">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-906">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-907">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-907">Outlook</span></span>

- <span data-ttu-id="03067-908">**Ihre Outlook-Einstellungen in der Cloud:** Wählen Sie Ihre Outlook für Windows-Einstellungen aus, z. B. Automatische Antworten, Posteingang mit Relevanz und Datenschutz, und greifen Sie auf jedem beliebigen PC darauf zu.</span><span class="sxs-lookup"><span data-stu-id="03067-908">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-911">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-911">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="03067-912">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-912">Office Suite</span></span>

- <span data-ttu-id="03067-913">Binäre Größe optimiert.</span><span class="sxs-lookup"><span data-stu-id="03067-913">Optimized binary size.</span></span>


- <span data-ttu-id="03067-914">Anaheim WebView unterstützt noch keinen Windows Information Protection (WIP).</span><span class="sxs-lookup"><span data-stu-id="03067-914">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="03067-915">Mit diesem Fix wird die Add-In-Plattform in Office wieder abwärtskompatibel mit WebView in einer Umgebung mit aktiviertem WIP.</span><span class="sxs-lookup"><span data-stu-id="03067-915">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="03067-916">Dabei kann es sich entweder um Microsoft Edge Spartan WebView oder Trident WebView handeln, abhängig von der Computerumgebung des Kunden.</span><span class="sxs-lookup"><span data-stu-id="03067-916">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="03067-917">Beide abwärtskompatiblem WebViews unterstützen WIP.</span><span class="sxs-lookup"><span data-stu-id="03067-917">Both down level WebViews support WIP.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2012-december-07"></a><span data-ttu-id="03067-919">Version 2012: 7. Dezember</span><span class="sxs-lookup"><span data-stu-id="03067-919">Version 2012: December 07</span></span>
<span data-ttu-id="03067-920">*Version 2012 (Build 13530.20064)*</span><span class="sxs-lookup"><span data-stu-id="03067-920">*Version 2012 (Build 13530.20064)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-922">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-922">Feature updates</span></span>

### <a name="teams"></a><span data-ttu-id="03067-923">Teams</span><span class="sxs-lookup"><span data-stu-id="03067-923">Teams</span></span>

- <span data-ttu-id="03067-924">**Windows native Benachrichtigung wird jetzt in Teams unterstützt:** Benutzer können nun die von ihnen bevorzugte Art der Benachrichtigungszustellung auswählen, entweder über in Teams integrierte Banner oder über die nativen Windows-Banner.</span><span class="sxs-lookup"><span data-stu-id="03067-924">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through Teams built-in banners or the Windows native banners.</span></span>


- <span data-ttu-id="03067-925">**Teams-Besprechungen 2x2-Katalogansicht in Citrix und VMware VDI:** Die Teams-Funktion in VDI 2x2-Katalogansicht ermöglicht das Anzeigen von bis zu vier Teilnehmervideos in der 2x2-Katalogansicht auf VDI-Clients von Citrix und VMware, wenn der Microsoft Teams-Client im VDI-optimierten Modus ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="03067-925">**Teams Meetings 2x2 Gallery View in Citrix and VMWare VDI:** Teams on VDI 2x2 Gallery View feature will enable to view up to four attendees videos in 2x2 Gallery View on VDI clients from Citrix, VMWare when Teams client in VDI optimized mode.</span></span>


- <span data-ttu-id="03067-926">**Besprechungsreaktionen:**  Besprechungsreaktionen stellen eine neue Möglichkeit zur Interaktion in Besprechungen dar.</span><span class="sxs-lookup"><span data-stu-id="03067-926">**Meeting Reactions:**  Meeting reactions are a new way to interact in meetings.</span></span> <span data-ttu-id="03067-927">Teilnehmer können Reaktionen senden, die als Stream auf freigegebene Inhalte angezeigt werden, und auf der Person, welche die Reaktion gesendet hat, wenn sie in der Besprechungsphase angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="03067-927">Participants can send reactions which are shown as a stream on content that is being shared, and on the individual who sent the reaction if they're displayed on the meeting stage.</span></span> 


- <span data-ttu-id="03067-928">**Zusammen-Modus und umfangreicher Katalog für Webbesprechungen** Mit dem großen Katalog können Sie Videos von bis zu 49 anderen Benutzern gleichzeitig sehen.</span><span class="sxs-lookup"><span data-stu-id="03067-928">**Together Mode and Large Gallery for Web Meetings** Large Gallery enables you to see the videos of up to 49 other people at once.</span></span> <span data-ttu-id="03067-929">Diese Option ist verfügbar, wenn mindestens zehn Personen Ihre Kameras aktiviert haben.</span><span class="sxs-lookup"><span data-stu-id="03067-929">This option is available when at least ten people have their cameras turned on.</span></span> <span data-ttu-id="03067-930">Im Zusammen-Modus fühlen Sie sich, wie wenn Sie mit allen Teilnehmern des Meetings im selben gemeinsamen Raum wären.</span><span class="sxs-lookup"><span data-stu-id="03067-930">Together mode lets you feel like you're in the same shared space with everyone in the meeting.</span></span> <span data-ttu-id="03067-931">Der Zusammen-Modus ist verfügbar, wenn sich mindestens fünf Personen in der Besprechung befinden.</span><span class="sxs-lookup"><span data-stu-id="03067-931">Together mode is available when there are at least five people in the meeting.</span></span> 


- <span data-ttu-id="03067-932">**Anruf-Zusammenführung** Mit dem Zusammenführen von Anrufen können Benutzer einen neuen zu startenden Anruf oder einen neuen eingehenden Anruf in ihren 1:1- oder Gruppen-Anruf zusammenführen.</span><span class="sxs-lookup"><span data-stu-id="03067-932">**Call Merge** Call Merge allows users to merge a new call they place, or a new incoming call, into their 1-1 or group call.</span></span> <span data-ttu-id="03067-933">Das gilt für Teams VoIP- und PSTN-Anrufe.</span><span class="sxs-lookup"><span data-stu-id="03067-933">This applies to Teams VOIP calls and PSTN calls.</span></span> 


### <a name="visio"></a><span data-ttu-id="03067-934">Visio</span><span class="sxs-lookup"><span data-stu-id="03067-934">Visio</span></span>

- <span data-ttu-id="03067-935">**Neue Azure-Schablonen und -Formen:** Wir haben viele weitere Schablonen hinzugefügt, die Ihnen beim Erstellen von aktuellen Azure-Diagrammen helfen.</span><span class="sxs-lookup"><span data-stu-id="03067-935">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="03067-936">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-936">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-939">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-939">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-940">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-940">Excel</span></span>

- <span data-ttu-id="03067-941">Ein Problem wurde behoben, bei dem einige Menübandelemente nicht in Chinesisch (vereinfacht) lokalisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-941">We fixed an issue where some Ribbon elements were not localized in Simplified Chinese.</span></span>


- <span data-ttu-id="03067-942">Ein Problem wurde behoben, bei dem Excel beim Aktualisieren unerwartet beendet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-942">We fixed an issue where Excel terminated unexpectedly when updating.</span></span>


- <span data-ttu-id="03067-943">Ein Problem wurde behoben, bei dem der Befehl "Objekt einfügen" beim Einfügen einer Datei aus dem lokalen OneDrive-Synchronisationsordner nicht das richtige Symbol anzeigte.</span><span class="sxs-lookup"><span data-stu-id="03067-943">We fixed an issue where the Insert Object command does not show the correct icon when inserting a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="03067-944">Es wurde ein Problem behoben, bei dem die Bearbeitung in Sprachen, die die Verwendung von IME erfordern, bei der Bearbeitung im Überschreiben-Modus schlecht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="03067-944">Fixed an issue where editing in languages that require use of IME would behave poorly when editing in overwrite mode.</span></span>


- <span data-ttu-id="03067-945">Es wurde ein Problem behoben, bei dem einigen Benutzern während der gemeinsamen Erstellung fälschlicherweise eine Statusleiste angezeigt wurde, die sie über eine neue Version einer Datei informierte.</span><span class="sxs-lookup"><span data-stu-id="03067-945">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="03067-946">Es wurde ein Problem behoben, aufgrund dessen Excel beim Kopieren und Einfügen von Daten in der Formelansicht unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-946">Fixed an issue where Excel would close unexpectedly when copying and pasting data in formula view.</span></span>


- <span data-ttu-id="03067-947">Es wurde ein fehlerhafter Hyperlink zu einem Hilfeartikel in einer Warnung behoben, die angezeigt wird, wenn das automatische Speichern deaktiviert wird.</span><span class="sxs-lookup"><span data-stu-id="03067-947">Fixed a broken hyperlink to a help article in an alert in case Autosave becomes disabled.</span></span>


- <span data-ttu-id="03067-948">Es wurde ein Problem behoben, das bei der Eingabe von Daten, während Excel in bestimmten Sprachen ausgeführt wurde, dazu führen konnte, dass Excel nicht mehr funktionierte.</span><span class="sxs-lookup"><span data-stu-id="03067-948">We fixed an issue where when entering data while Excel is running in certain languages could cause Excel to stop working.</span></span>


- <span data-ttu-id="03067-949">Durch diese Änderung wird ein Problem behoben, bei dem Schriftarten in Formeln nicht ordnungsgemäß angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-949">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="03067-950">Hierdurch wird ein Problem behoben, bei dem Power Pivot eine durch Tabstopps getrennte Textdatei nicht ordnungsgemäß importieren konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-950">This fixes an issue where Power Pivot wasn't able to correctly import a tab-delimited text file.</span></span>


### <a name="outlook"></a><span data-ttu-id="03067-951">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-951">Outlook</span></span>

- <span data-ttu-id="03067-952">Ein Problem wurde behoben, durch das das Feld "An:" in Aufgabenstatusberichten leer war.</span><span class="sxs-lookup"><span data-stu-id="03067-952">We fixed an issue that caused the To: field to be blank in task status reports.</span></span>


- <span data-ttu-id="03067-953">Es wurde ein Problem behoben, das dazu führte, dass das Ereignis "MailItem.BeforeAttachmentAdd" abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-953">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="03067-954">Es wurde ein Problem behoben, aufgrund dessen Benutzer einige Probleme beim Senden von Outlook-E-Mails von anderen Anwendungen als Outlook haben konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-954">We fixed an issue that was causing users to experience some issues when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="03067-955">Es wurde ein Problem behoben, aufgrund dessen die Formatierung von SmartLinks beim Speichern in Entwürfen verloren ging.</span><span class="sxs-lookup"><span data-stu-id="03067-955">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="03067-956">Ein Problem wurde behoben, bei dem das Hinzufügen einer Anlage zu einer aus einer Zip-Datei geöffneten Nachricht fehlschlug.</span><span class="sxs-lookup"><span data-stu-id="03067-956">We fixed and issue where adding an attachment to a message opened from a zip file would fail.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="03067-957">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-957">PowerPoint</span></span>

- <span data-ttu-id="03067-958">Ein Problem mit dem Kopieren/Einfügen einer Formel aus Word in PowerPoint wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-958">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="03067-959">Diese Änderung behebt ein Problem im Zusammenhang mit Timeouts, die während der Freihandanalyse aufgetreten sind.</span><span class="sxs-lookup"><span data-stu-id="03067-959">This change addresses an issue related to timeouts experienced during ink analysis.</span></span>


- <span data-ttu-id="03067-960">Diese Änderung behebt einen Grammatikfehler in der Benutzeroberfläche für die Erstellung animierter GIFs.</span><span class="sxs-lookup"><span data-stu-id="03067-960">This change addresses a grammatical error in the Create an Animated GIF user interface.</span></span>


- <span data-ttu-id="03067-961">Diese Änderung behebt ein Problem mit Pfadfüllungen beim Anwenden von "Formen zusammenführen"-Vorgängen mit bestimmten Geometrien.</span><span class="sxs-lookup"><span data-stu-id="03067-961">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


- <span data-ttu-id="03067-962">Durch diese Änderung wird ein Problem behoben, bei dem Schriftarten in Formeln nicht ordnungsgemäß angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-962">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="03067-963">Durch diese Änderung wird ein Problem beim Behandeln von Fehlern behoben, das während des Ladens von Videos auftreten konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-963">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="03067-964">Ein VBA-Problem wurde behoben, bei dem "Slide.Shapes.AddMediaObject2" bei veralteten Videoformaten abstürzte (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="03067-964">We fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="03067-965">Es wurde ein Problem behoben, bei dem der Anwesenheitsindikator eines unbekannten Mitautors nicht vollständig aktualisiert wurde, wenn weitere Informationen über den Mitverfasser verfügbar waren.</span><span class="sxs-lookup"><span data-stu-id="03067-965">We fixed an issue where an unknown coauthor's presence indicator does not get completely refreshed when more information about the coauthor is available.</span></span>


- <span data-ttu-id="03067-966">Es wurde ein Problem mit einem NULL-Zeiger behoben, der dereferenziert wurde, wenn die Größe der Folienansicht bei aktiviertem Lineal geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-966">Fixed a null pointer being dereferenced when slide view is resized with ruler turned on.</span></span>


- <span data-ttu-id="03067-967">Ein Problem wurde behoben, bei dem einige beschädigte PowerPoint-Dateien auch nach einem Dokumentreparaturvorgang nicht ordnungsgemäß geöffnet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-967">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="project"></a><span data-ttu-id="03067-968">Project</span><span class="sxs-lookup"><span data-stu-id="03067-968">Project</span></span>

- <span data-ttu-id="03067-969">Es wurde ein Problem behoben, bei dem Benutzer beim Öffnen von Projekten, die angeblich mit aktualisierten Informationen gespeichert wurden, feststellten, dass keine Aktualisierungen vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="03067-969">We fixed an issue where users open projects which have supposedly been saved with updated information, but find the updates are is missing.</span></span>


- <span data-ttu-id="03067-970">Ein Problem wurde behoben, bei dem keine Abhängigkeiten von Projektleistungen gelöscht werden konnten, wenn die SharePoint-Website, der die Projektleistung zugeordnet war, nicht mehr vorhanden war.</span><span class="sxs-lookup"><span data-stu-id="03067-970">We fixed an issue where you couldn't delete dependencies on the deliverables if the SharePoint site the deliverable was associated with no longer existed.</span></span>


- <span data-ttu-id="03067-971">Es wurde ein Problem behoben, bei dem das Öffnen eines Projekts mit vielen Ressourcen sehr lange dauerte.</span><span class="sxs-lookup"><span data-stu-id="03067-971">Fixed an issue where opening a project with a lot of resources was taking a long time.</span></span>


- <span data-ttu-id="03067-972">Es wurde ein Problem behoben, bei dem Benutzern u. U. mehrere nicht zugewiesene Zuordnungen angezeigt wurden, die einer Aufgabe zugeordnet waren.</span><span class="sxs-lookup"><span data-stu-id="03067-972">Fixed an issue where users may see multiple unassigned assignments associated with a task.</span></span>


- <span data-ttu-id="03067-973">Es wurde ein Problem behoben, bei dem bei großen Projekten die Eingabe von Aufgabennamen sehr langsam sein konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-973">Fixed an issue where in large projects it can be very slow to enter a task name.</span></span>


- <span data-ttu-id="03067-974">Es wurde ein Problem behoben, bei dem bestimmte Projekte geöffnet werden konnten, wenn ein Problem mit der Projektdatei in einem bestimmten Teil der Last vorlag.</span><span class="sxs-lookup"><span data-stu-id="03067-974">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="03067-975">Word</span><span class="sxs-lookup"><span data-stu-id="03067-975">Word</span></span>

- <span data-ttu-id="03067-976">Das Einfügen als nur-Text wird häufig gegenüber Rich-Text-Formatierung bevorzugt.</span><span class="sxs-lookup"><span data-stu-id="03067-976">Paste as plain text is often preferred to pasting as rich text.</span></span> <span data-ttu-id="03067-977">Mit diesem Kontextmenü-Fix kann der Benutzer Inhalte als nur-Text einfügen.</span><span class="sxs-lookup"><span data-stu-id="03067-977">This context menu fix allows the user to paste as plain text.</span></span> <span data-ttu-id="03067-978">Andernfalls müsste er ihn zunächst in einen nur-Text-Editor wie Notepad kopieren und dann aus dem Editor in die gewünschte Ziel-Anwendung kopieren.</span><span class="sxs-lookup"><span data-stu-id="03067-978">Else the user would have to copy into a plain-text editor like Notepad and then copy from Notepad into the desired target app</span></span>


- <span data-ttu-id="03067-979">Ein Problem mit dem Kopieren/Einfügen einer Formel aus Word in PowerPoint wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-979">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>


- <span data-ttu-id="03067-980">Durch diese Änderung wird ein Problem mit dem Cursor beim Bearbeiten eines Dokuments behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-980">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="03067-981">Es wurde ein Problem mit verschwommenen Bildern beim Zoomen behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-981">We fixed an issue related to pictures becoming blurry while zooming.</span></span>


- <span data-ttu-id="03067-982">Ein Problem wurde behoben, bei dem lange Links abgeschnitten wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-982">We fixed an issue where long hyperlinks were getting truncated.</span></span>


### <a name="office-suite"></a><span data-ttu-id="03067-983">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-983">Office Suite</span></span>

- <span data-ttu-id="03067-984">Office-Suite: Es wurde ein Problem behoben, bei dem aufgrund fehlender Registrierungseinträge die Installation einer neueren Version von Office über bestimmte ältere Versionen zu einer eingeschränkten Funktionalität führen konnte (beispielsweise war die Verwendung der Power-Abfrage nicht möglich).</span><span class="sxs-lookup"><span data-stu-id="03067-984">Office Suite Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2011-december-01"></a><span data-ttu-id="03067-986">Version 2011: 1. Dezember</span><span class="sxs-lookup"><span data-stu-id="03067-986">Version 2011: December 01</span></span>
<span data-ttu-id="03067-987">*Version 2011 (Build 13426.20306)*</span><span class="sxs-lookup"><span data-stu-id="03067-987">*Version 2011 (Build 13426.20306)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-989">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-989">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-990">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-990">Outlook</span></span>

- <span data-ttu-id="03067-991">**Alle Besprechungen online:** Vereinfacht die Planung von Online-Besprechungen durch eine neue Einstellung, bei der alle Ihre Besprechungen standardmäßig online sind.</span><span class="sxs-lookup"><span data-stu-id="03067-991">**Every meeting online:** Make it easier to schedule online meetings with a new setting to make all your meetings online by default.</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-994">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-994">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-995">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-995">Outlook</span></span>

- <span data-ttu-id="03067-996">Es wurde ein Problem behoben, aufgrund dessen die ursprünglichen Teilnehmer einiger Besprechungen eine Veranstaltungsabsage erhielten, wenn ein anderer Teilnehmer die Besprechung weiterleitete.</span><span class="sxs-lookup"><span data-stu-id="03067-996">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


- <span data-ttu-id="03067-997">Es wurde ein Problem behoben, aufgrund dessen einige Benutzer keine Signaturen im Signaturen-Dropdownfeld sehen konnten, obwohl mindestens eine Signatur konfiguriert war.</span><span class="sxs-lookup"><span data-stu-id="03067-997">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


### <a name="project"></a><span data-ttu-id="03067-998">Project</span><span class="sxs-lookup"><span data-stu-id="03067-998">Project</span></span>

- <span data-ttu-id="03067-999">Es wurde ein Problem behoben, bei dem bestimmte Projekte geöffnet werden konnten, wenn ein Problem mit der Projektdatei in einem bestimmten Teil der Last vorlag.</span><span class="sxs-lookup"><span data-stu-id="03067-999">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2011-november-24"></a><span data-ttu-id="03067-1001">Version 2011: 24. November</span><span class="sxs-lookup"><span data-stu-id="03067-1001">Version 2011: November 24</span></span>
<span data-ttu-id="03067-1002">*Version 2011 (Build 13426.20294)*</span><span class="sxs-lookup"><span data-stu-id="03067-1002">*Version 2011 (Build 13426.20294)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1004">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1004">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="03067-1005">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-1005">Office Suite</span></span>

- <span data-ttu-id="03067-1006">Ein Problem mit dem Kopieren/Einfügen einer Formel aus Word in PowerPoint wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-1006">Fixed an issue with copy/paste of an equation from Word to Powerpoint</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2011-november-21"></a><span data-ttu-id="03067-1008">Version 2011: 21. November</span><span class="sxs-lookup"><span data-stu-id="03067-1008">Version 2011: November 21</span></span>
<span data-ttu-id="03067-1009">*Version 2011 (Build 13426.20274)*</span><span class="sxs-lookup"><span data-stu-id="03067-1009">*Version 2011 (Build 13426.20274)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1011">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1011">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="03067-1012">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1012">PowerPoint</span></span>

- <span data-ttu-id="03067-1013">**Videobibliothek:** Erweitern Sie Ihre Dokumente mit einer Sammlung von kuratierten, lizenzfreien, in der App verfügbaren Videoaufnahmen.</span><span class="sxs-lookup"><span data-stu-id="03067-1013">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1016">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1016">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1017">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1017">Outlook</span></span>

- <span data-ttu-id="03067-1018">Es wurde ein Problem behoben, durch das das MailItem.BeforeAttachmentAdd-Ereignis unterbrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1018">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="03067-1019">Wir haben einen Registrierungsschlüssel hinzugefügt, mit dem Kunden die Dateizeiteinbeziehung für Anhänge in IDataObject-Operationen (z. B. Drag/Drop, Zwischenablage) deaktivieren können.</span><span class="sxs-lookup"><span data-stu-id="03067-1019">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="03067-1020">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="03067-1020">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="03067-1021">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="03067-1021">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="03067-1022">0 = Dateizeiten sind ausgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="03067-1022">0 = filetimes are excluded.</span></span> <span data-ttu-id="03067-1023">1 = (Standard) Dateizeiten sind enthalten.</span><span class="sxs-lookup"><span data-stu-id="03067-1023">1 = (default) filetimes are included</span></span>


- <span data-ttu-id="03067-1024">Es wurde ein Problem behoben, das dazu führte, dass Inline-Bilder verschwanden, wenn auf eine Nachricht mit einer Schutzbezeichnung von Azure Information Protection geantwortet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1024">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2011-november-18"></a><span data-ttu-id="03067-1026">Version 2011: 18. November</span><span class="sxs-lookup"><span data-stu-id="03067-1026">Version 2011: November 18</span></span>
<span data-ttu-id="03067-1027">*Version 2011 (Build 13426.20250)*</span><span class="sxs-lookup"><span data-stu-id="03067-1027">*Version 2011 (Build 13426.20250)*</span></span>
* <span data-ttu-id="03067-1028">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="03067-1028">Various bugs and performance fixes.</span></span>

## <a name="version-2011-november-16"></a><span data-ttu-id="03067-1029">Version 2011: 16. November</span><span class="sxs-lookup"><span data-stu-id="03067-1029">Version 2011: November 16</span></span>
<span data-ttu-id="03067-1030">*Version 2011 (Build 13426.20234)*</span><span class="sxs-lookup"><span data-stu-id="03067-1030">*Version 2011 (Build 13426.20234)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1032">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1032">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1033">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1033">Outlook</span></span>

- <span data-ttu-id="03067-1034">**Die gleiche Signatur auf allen Geräten:** Ihre Signatur wird in der Cloud gespeichert.</span><span class="sxs-lookup"><span data-stu-id="03067-1034">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="03067-1035">Erstellen Sie die Signatur einmal, und verwenden Sie diese überall, wo Sie Outlook verwenden.</span><span class="sxs-lookup"><span data-stu-id="03067-1035">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1038">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1038">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1039">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1039">Outlook</span></span>

- <span data-ttu-id="03067-1040">Es wurde ein Problem behoben, das dazu führte, dass das Feld „An“ beim Senden eines Statusberichts zu einer Aufgabe leer war.</span><span class="sxs-lookup"><span data-stu-id="03067-1040">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="03067-1041">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1041">PowerPoint</span></span>

- <span data-ttu-id="03067-1042">Ein VBA-Problem wurde behoben, bei dem "Slide.Shapes.AddMediaObject2" bei veralteten Videoformaten abstürzte (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="03067-1042">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2011-november-09"></a><span data-ttu-id="03067-1044">Version 2011: 9. November</span><span class="sxs-lookup"><span data-stu-id="03067-1044">Version 2011: November 09</span></span>
<span data-ttu-id="03067-1045">*Version 2011 (Build 13426.20184)*</span><span class="sxs-lookup"><span data-stu-id="03067-1045">*Version 2011 (Build 13426.20184)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1047">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1047">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-1048">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1048">Excel</span></span>

- <span data-ttu-id="03067-1049">**Erstellen von Power Platform-Datenflüssen aus Abfragen:** Jetzt können Sie Ihre Abfragen in Power Query-Vorlagen exportieren, die zum Erstellen von neuen Power Platform-Datenflüssen verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="03067-1049">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1052">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1052">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="03067-1053">Zugriff</span><span class="sxs-lookup"><span data-stu-id="03067-1053">Access</span></span>

- <span data-ttu-id="03067-1054">Es wurde ein Problem behoben, bei dem einige Benutzer die Fehlermeldung "Systemressource überschritten" angezeigt erhielten, wenn sie eine Abfrage aus dem synchronisierten OneDrive-Ordner exportieren wollten.</span><span class="sxs-lookup"><span data-stu-id="03067-1054">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>


- <span data-ttu-id="03067-1055">Es wurde ein Problem behoben, bei dem das automatische Umschalten zwischen Formularfenstern zu einem anderen Formular führte.</span><span class="sxs-lookup"><span data-stu-id="03067-1055">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>


- <span data-ttu-id="03067-1056">Es wurde ein Problem behoben, das bei Verwendung von DAO aus nicht-Office-Anwendungen dazu führte, dass die Anwendung unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1056">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="03067-1057">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1057">Excel</span></span>

- <span data-ttu-id="03067-1058">Es wurde ein Problem behoben, bei dem „Dateiname“ nach einem „SaveAs“-Vorgang mit aktiviertem COM-Add-In nicht geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1058">We fixed an issue where Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="03067-1059">Ein Problem mit Power Pivot bei Verwendung einer Verbindung zu einer Oracle-Datenbank wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-1059">Fixed an issue with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="03067-1060">Es wurde ein Problem behoben, bei dem das automatische Speichern mit einer falschen/irreführenden Fehlermeldung fehlschlug, wenn im Excel-Datenmodell eine schlechte Kennzahldefinition vorhanden war.</span><span class="sxs-lookup"><span data-stu-id="03067-1060">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="03067-1061">Ein Problem wurde behoben, durch das Excel unerwartet beendet wurde, wenn der Prozess der MTR-Berechnung und der Aktualisierung von Gruppenrichtlinienobjekten (z. B. über Remoteaktualisierung von Gruppenrichtlinien) ausgelöst wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1061">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="03067-1062">Es wurde ein Problem behoben, bei dem ein Benutzer eine atomsvc-Datei (UTF8 + BOM) nicht direkt aus SharePoint öffnen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1062">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="03067-1063">Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.</span><span class="sxs-lookup"><span data-stu-id="03067-1063">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="03067-1064">Es wurde ein Problem behoben, bei dem Word zu hängen scheint, wenn eine Excel-Arbeitsmappe in ein Word-Dokument eingefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1064">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="03067-1065">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1065">Outlook</span></span>

- <span data-ttu-id="03067-1066">Es wurde ein Problem behoben, das dazu führte, dass Outlook beim Hinzufügen oder Speichern von Anlagen sporadisch nicht mehr funktionierte.</span><span class="sxs-lookup"><span data-stu-id="03067-1066">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


- <span data-ttu-id="03067-p158">Es wurde ein Problem behoben, bei dem der Schnelldruck für Bildanlagen zum Fehler geführt hat: „Windows kann dieses Bild nicht finden. Überprüfen Sie den Speicherort, und versuchen Sie es dann erneut“.</span><span class="sxs-lookup"><span data-stu-id="03067-p158">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture. Check the location, and then try again".</span></span>


- <span data-ttu-id="03067-1069">Es wurde ein Problem behoben, das dazu führte, dass Outlook im Offline-Status startete, bis die Benutzer manuell wählten, online zu arbeiten.</span><span class="sxs-lookup"><span data-stu-id="03067-1069">We fixed an issue that caused some users to see Outlook start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="03067-1070">Es wurde ein Problem behoben, bei dem beim Einfügen einer aus dem Besprechungsort kopierten URL an eine andere Stelle (z. B. in einen Browser) der URL ein Strickpunkt am Ende hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1070">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>


- <span data-ttu-id="03067-1071">Es wurde ein Problem behoben, bei dem Benutzer Termine im Kalender von Microsoft 365-Gruppen in der Standardauthentifizierung nicht löschen konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-1071">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="03067-1072">Es wurde ein Problem behoben, bei dem das Starten von Outlook beim Laden des Spitznamen-Caches fehlschlug.</span><span class="sxs-lookup"><span data-stu-id="03067-1072">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


- <span data-ttu-id="03067-1073">Ein Problem wurde behoben, bei dem ein Postfachbesitzer die Freigabeberechtigung für den eigenen Kalender nicht verwalten konnte, da die Option abgeblendet war.</span><span class="sxs-lookup"><span data-stu-id="03067-1073">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="03067-1074">Ein Problem wurde behoben, bei dem in Outlook keine Nachricht mit eingeschränkten Berechtigungen erstellt werden konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1074">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="03067-1075">Es wurde ein Problem behoben, bei dem beim Speichern von E-Mail-Vorlagen als .OFT chinesische Zeichen in Fragezeichen geändert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1075">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="03067-1076">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1076">PowerPoint</span></span>

- <span data-ttu-id="03067-1077">Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.</span><span class="sxs-lookup"><span data-stu-id="03067-1077">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="03067-1078">Es wurde ein Problem behoben, bei dem das Symbol „Inhaltsplatzhalter“ neben „Bilder“ keine QuickInfo aufwies.</span><span class="sxs-lookup"><span data-stu-id="03067-1078">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="03067-1079">Es wurde ein Problem behoben, bei dem die geschützte Ansicht einer Bildschirmpräsentation, die durch eine pptsx-Datei dargestellt wurde, die Bildschirmaufnahme von IRM-geschützten Dokumenten ermöglichte.</span><span class="sxs-lookup"><span data-stu-id="03067-1079">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>


- <span data-ttu-id="03067-1080">Es wurde ein Problem behoben, bei dem Gitternetzlinien beim Schließen des Entwurfsfensters von den Folien verschoben wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1080">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="03067-1081">Es wurde ein Problem behoben, bei dem beim Duplizieren einer Bildschirmpräsentation auf einen sekundären Monitor diese manchmal von einem anderen Fenster verdeckt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1081">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>


- <span data-ttu-id="03067-1082">Es wurde ein Problem behoben, bei dem sich die Bildlaufleiste in einer Folie von selbst einstellte, nachdem die Bildschirmaufnahme bei geöffnetem Auswahlfenster gestoppt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1082">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="03067-1083">Project</span><span class="sxs-lookup"><span data-stu-id="03067-1083">Project</span></span>

- <span data-ttu-id="03067-1084">Es wurde ein Problem behoben, bei dem „NewVal“ im Ereignis „ProjectBeforeTaskChange“ nicht den richtigen Wert hatte, wenn eine Verzögerung innerhalb einer Ansicht vom Typ "Aufgabenformular" geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1084">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="03067-1085">Es wurde ein Problem behoben, bei dem Project beim Öffnen von Dateien manchmal abstürzte, wenn Ressourcenprofile auf eine bestimmte Weise angegeben waren.</span><span class="sxs-lookup"><span data-stu-id="03067-1085">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="03067-1086">Es wurde ein Problem behoben, bei dem beim Speichern eines Projekts aus PWA in eine lokale MPP-Datei das ProjectBeforeTaskChangeEvent für Daten ausgelöst wurde, die vom Benutzer nicht tatsächlich geändert worden waren.</span><span class="sxs-lookup"><span data-stu-id="03067-1086">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="03067-1087">Es wurde ein Problem behoben, bei dem die Suche nach einer Ressource durch Ressourcenverhandlungen anhand des Namens anstelle der GUID erfolgte, was zu Problemen führen konnte, wenn mehrere Ressourcen denselben Namen aufwiesen.</span><span class="sxs-lookup"><span data-stu-id="03067-1087">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


- <span data-ttu-id="03067-1088">Es wurde ein Problem behoben, bei dem wenn es in einer Projektsite eine Aufgabenliste gab und diese gruppiert wurde, sie nicht schnell bearbeitet werden konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1088">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="03067-1089">Es wurde ein Problem behoben, bei dem, wenn Sie eine Unternehmensressource über CSOM aktualisieren, die maximale Anzahl von Ressourcen möglicherweise verloren geht.</span><span class="sxs-lookup"><span data-stu-id="03067-1089">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="03067-1090">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1090">Word</span></span>

- <span data-ttu-id="03067-1091">Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.</span><span class="sxs-lookup"><span data-stu-id="03067-1091">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="03067-1092">Ein Problem wurde behoben, bei dem das Klicken auf einen Kommentarhinweis nicht dazu führte, dass die Kommentarkarte in der Ansicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1092">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="03067-1093">Ein Layout-Problem wurde behoben, bei dem sich die Linie zwischen den Spalten verschieben konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1093">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="03067-1094">Es wurde ein Problem mit dem Nachverfolgen von Änderungen behoben, bei dem beim Öffnen von Word-Dokumenten manchmal eine Fehlermeldung angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1094">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="03067-1095">Es wurde ein Problem behoben, bei dem Word zu hängen scheint, wenn eine Excel-Arbeitsmappe in ein Word-Dokument eingefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1095">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


- <span data-ttu-id="03067-1096">Es wurde ein Problem mit dem Drucken behoben, das beim Anwenden von Vertraulichkeitsbezeichnungen mit Wasserzeichen auftrat.</span><span class="sxs-lookup"><span data-stu-id="03067-1096">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


### <a name="office-suite"></a><span data-ttu-id="03067-1097">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-1097">Office Suite</span></span>

- <span data-ttu-id="03067-1098">Es wurde ein Problem mit dem Office-Bereitstellungstool behoben, bei dem die Konfiguration fehlschlug, wenn das Feature "RemoveMSI" in Anwesenheit des Produkts „Microsoft-Anwendungsfehler-Berichterstattung“ in Office 2007 verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1098">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="03067-1099">Es wurde ein Problem behoben, bei dem bei der interaktiven SSO-API-Anmeldung ein Fehlercode zurückgegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1099">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-november-06"></a><span data-ttu-id="03067-1101">Version 2010: 6. November</span><span class="sxs-lookup"><span data-stu-id="03067-1101">Version 2010: November 06</span></span>
<span data-ttu-id="03067-1102">*Version 2010 (Build 13328.20356)*</span><span class="sxs-lookup"><span data-stu-id="03067-1102">*Version 2010 (Build 13328.20356)*</span></span>
* <span data-ttu-id="03067-1103">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="03067-1103">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)



[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-november-04"></a><span data-ttu-id="03067-1106">Version 2010: 4. November</span><span class="sxs-lookup"><span data-stu-id="03067-1106">Version 2010: November 04</span></span>
<span data-ttu-id="03067-1107">*Version 2010 (Build 13328.20340)*</span><span class="sxs-lookup"><span data-stu-id="03067-1107">*Version 2010 (Build 13328.20340)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1109">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1109">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-1110">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1110">Excel</span></span>

- <span data-ttu-id="03067-1111">**Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen.</span><span class="sxs-lookup"><span data-stu-id="03067-1111">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="03067-1112">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1112">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="03067-1113">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1113">Outlook</span></span>

- <span data-ttu-id="03067-1114">**Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen.</span><span class="sxs-lookup"><span data-stu-id="03067-1114">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="03067-1115">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1115">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="03067-1116">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1116">PowerPoint</span></span>

- <span data-ttu-id="03067-1117">**Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen.</span><span class="sxs-lookup"><span data-stu-id="03067-1117">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="03067-1118">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1118">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="03067-1119">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://insider.office.com/de-DE/blog/svg-content-office-third-party-apps)</span><span class="sxs-lookup"><span data-stu-id="03067-1119">See details in [blog post](https://insider.office.com/de-DE/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="03067-1120">**Erstellen von GIFs mit transparenten Hintergründen:** Wenn Sie in ein animiertes GIF exportieren, ermöglicht Ihnen eine neue Option den transparenten Hintergrund.</span><span class="sxs-lookup"><span data-stu-id="03067-1120">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span><br /><span data-ttu-id="03067-1121">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/export-animated-gifs-transparent-backgrounds)</span><span class="sxs-lookup"><span data-stu-id="03067-1121">See details in [blog post](https://insider.office.com/de-DE/blog/export-animated-gifs-transparent-backgrounds)</span></span>

- <span data-ttu-id="03067-1122">**Exportieren eines animierten GIF in einem Bereich:** Folienbereich auswählen, wenn Sie nach animiertem GIF exportieren</span><span class="sxs-lookup"><span data-stu-id="03067-1122">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

### <a name="word"></a><span data-ttu-id="03067-1123">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1123">Word</span></span>

- <span data-ttu-id="03067-1124">**Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen.</span><span class="sxs-lookup"><span data-stu-id="03067-1124">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="03067-1125">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1125">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1128">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1128">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1129">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1129">Outlook</span></span>

- <span data-ttu-id="03067-1130">Es wurde ein Problem behoben, durch das Benutzer ihren Delegierten keine Editor-Berechtigung erteilen konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-1130">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="03067-1131">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-1131">Office Suite</span></span>

- <span data-ttu-id="03067-1132">Wir haben ein Problem behoben, das zu einem Fehlschlag beim Versuch führte, Dateien zu speichern, die von SyncBacked auf „Nur Server“ übergegangen sind.</span><span class="sxs-lookup"><span data-stu-id="03067-1132">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-october-27"></a><span data-ttu-id="03067-1134">Version 2010: 27. Oktober</span><span class="sxs-lookup"><span data-stu-id="03067-1134">Version 2010: October 27</span></span>
<span data-ttu-id="03067-1135">*Version 2010 (Build 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="03067-1135">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1139">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1139">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1140">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1140">Outlook</span></span>

- <span data-ttu-id="03067-1141">Wir haben ein Problem behoben, durch das die Cloudeinstellungen standardmäßig nicht für Benutzer aktiviert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1141">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="03067-1142">Es wurde ein Problem behoben, durch das die Änderungen an einer Benutzersignatur nicht gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1142">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-october-24"></a><span data-ttu-id="03067-1144">Version 2010: 24. Oktober</span><span class="sxs-lookup"><span data-stu-id="03067-1144">Version 2010: October 24</span></span>
<span data-ttu-id="03067-1145">*Version 2010 (Build 13328.20278)*</span><span class="sxs-lookup"><span data-stu-id="03067-1145">*Version 2010 (Build 13328.20278)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)



[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1149">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1149">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1150">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1150">Outlook</span></span>

- <span data-ttu-id="03067-1151">Es wurde ein Problem behoben, durch das die Kopfzeilen chinesischer Nachrichten bei der Beantwortung oder Weiterleitung nicht lesbar waren.</span><span class="sxs-lookup"><span data-stu-id="03067-1151">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="03067-1152">Es wurde ein Problem behoben, durch das chinesische Zeichen beim Speichern als OFT-Datei in Fragezeichen geändert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1152">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="project"></a><span data-ttu-id="03067-1153">Project</span><span class="sxs-lookup"><span data-stu-id="03067-1153">Project</span></span>

- <span data-ttu-id="03067-1154">Es wurde ein Problem behoben, bei dem beim Speichern eines Projekts aus PWA in eine lokale MPP-Datei das ProjectBeforeTaskChangeEvent für Daten ausgelöst wurde, die vom Benutzer nicht tatsächlich geändert worden waren.</span><span class="sxs-lookup"><span data-stu-id="03067-1154">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="03067-1155">Es wurde ein Problem behoben, bei dem das Ereignis NewVal im ProjectBeforeTaskChange nicht den richtigen Wert hat, wenn eine Verzögerung innerhalb einer Ansicht vom Typ "Aufgabenformular" geändert wird.</span><span class="sxs-lookup"><span data-stu-id="03067-1155">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-october-19"></a><span data-ttu-id="03067-1157">Version 2010: 19. Oktober</span><span class="sxs-lookup"><span data-stu-id="03067-1157">Version 2010: October 19</span></span>
<span data-ttu-id="03067-1158">*Version 2010 (Build 13328.20210)*</span><span class="sxs-lookup"><span data-stu-id="03067-1158">*Version 2010 (Build 13328.20210)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1160">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1160">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1161">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1161">Outlook</span></span>

- <span data-ttu-id="03067-1162">**Sparen Sie Zeit beim Verfassen von Nachrichten:** Outlook macht Ihnen Formulierungsvorschläge, sodass Sie Nachrichten schnell verfassen können.</span><span class="sxs-lookup"><span data-stu-id="03067-1162">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="03067-1163">Wenn Sie den Vorschlag akzeptieren möchten, verwenden Sie einfach die TAB-Taste.</span><span class="sxs-lookup"><span data-stu-id="03067-1163">To accept the suggestion, just use the Tab key.</span></span><br /><span data-ttu-id="03067-1164">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/text-predictions-in-word-outlook)</span><span class="sxs-lookup"><span data-stu-id="03067-1164">See details in [blog post](https://insider.office.com/de-DE/blog/text-predictions-in-word-outlook)</span></span>

- <span data-ttu-id="03067-1165">**Aufheben der Sprachbarriere durch einen integrierten Übersetzer:** Ab jetzt sind keine Add-Ins für die Übersetzung mehr erforderlich!</span><span class="sxs-lookup"><span data-stu-id="03067-1165">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="03067-1166">Klicken Sie in einer Nachricht mit der rechten Maustaste, um bestimmte Wörter, Ausdrücke oder die gesamte Nachricht zu übersetzen.</span><span class="sxs-lookup"><span data-stu-id="03067-1166">In a message, right-click to translate specific words, phrases, or the whole message.</span></span> [<span data-ttu-id="03067-1167">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1167">Learn more</span></span>](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

- <span data-ttu-id="03067-1168">**Updates zur Verbesserung der Benutzerfreundlichkeit für Aufgaben:** visuelle Auffrischung von Aufgabenelementen</span><span class="sxs-lookup"><span data-stu-id="03067-1168">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

### <a name="powerpoint"></a><span data-ttu-id="03067-1169">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1169">PowerPoint</span></span>

- <span data-ttu-id="03067-1170">**Üben Sie Ihre Präsentation mit der PowerPoint-Vorschau:** Lassen Sie sich bei den Dingen coachen, die die Aufmerksamkeit Ihrer Benutzergruppe erhöhen – wie Tempo, zu oft verwendete Wörter, Körpersprache und mehr.</span><span class="sxs-lookup"><span data-stu-id="03067-1170">**Practice your presentation with Presenter Coach:** Get coaching on the things that help keep an audience engaged — like pacing, overused words, body language, and more.</span></span> [<span data-ttu-id="03067-1171">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1171">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

### <a name="word"></a><span data-ttu-id="03067-1172">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1172">Word</span></span>

- <span data-ttu-id="03067-1173">**Der Microsoft-Editor-Bereich erhält in der Desktopversion von Word ein Update:** Die aktuelle Benutzeroberfläche im Editorbereich in Word für Desktopclients wurde aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="03067-1173">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>

- <span data-ttu-id="03067-1174">**Schreibvorschläge mit einem Klick:** Übernehmen Sie Schreibvorschläge mit nur einem Klick.</span><span class="sxs-lookup"><span data-stu-id="03067-1174">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="03067-1175">Der aktualisierte Editor-Bereich erleichtert die Navigation zwischen den Vorschlägen.</span><span class="sxs-lookup"><span data-stu-id="03067-1175">The updated Editor pane makes it easy to navigate between suggestions.</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1178">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1178">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="03067-1179">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1179">PowerPoint</span></span>

- <span data-ttu-id="03067-1180">Hierbei handelt es sich um einen Fix für ein Problem, bei dem beim Schließen des Dokuments die Aufforderung „Speichern“ in einer Schleife angezeigt wird, wenn es ein Add-In gibt, das auf das Ereignis PresentationBeforeClose hört und die Eigenschaft Presentation.Saved als Teil des Ereignishandlers prüft.</span><span class="sxs-lookup"><span data-stu-id="03067-1180">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-october-11"></a><span data-ttu-id="03067-1182">Version 2010: 11. Oktober</span><span class="sxs-lookup"><span data-stu-id="03067-1182">Version 2010: October 11</span></span>
<span data-ttu-id="03067-1183">*Version 2010 (Build 13328.20154)*</span><span class="sxs-lookup"><span data-stu-id="03067-1183">*Version 2010 (Build 13328.20154)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1185">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1185">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-1186">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1186">Excel</span></span>

- <span data-ttu-id="03067-1187">**Schützen Sie Ihre Daten vor schädlichen Dateien:** Application Guard schützt Sie vor Schadsoftware, indem Sie Office-Dateien in einem isolierten Container lesen, drucken und speichern können.</span><span class="sxs-lookup"><span data-stu-id="03067-1187">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="03067-1188">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1188">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="powerpoint"></a><span data-ttu-id="03067-1189">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1189">PowerPoint</span></span>

- <span data-ttu-id="03067-1190">**Schützen Sie Ihre Daten vor schädlichen Dateien:** Application Guard schützt Sie vor Schadsoftware, indem Sie Office-Dateien in einem isolierten Container lesen, drucken und speichern können.</span><span class="sxs-lookup"><span data-stu-id="03067-1190">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="03067-1191">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1191">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="word"></a><span data-ttu-id="03067-1192">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1192">Word</span></span>

- <span data-ttu-id="03067-1193">**Schützen Sie Ihre Daten vor schädlichen Dateien:** Application Guard schützt Sie vor Schadsoftware, indem Sie Office-Dateien in einem isolierten Container lesen, drucken und speichern können.</span><span class="sxs-lookup"><span data-stu-id="03067-1193">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="03067-1194">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1194">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1197">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1197">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="03067-1198">Zugriff</span><span class="sxs-lookup"><span data-stu-id="03067-1198">Access</span></span>

- <span data-ttu-id="03067-1199">Ein Problem wurde behoben, bei dem die Position der Bildlaufleiste nicht ordnungsgemäß festgelegt wurde, wenn das Abfrage/Beziehungsfenster beim Scrollen geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1199">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="03067-1200">Ein Problem wurde behoben, bei dem der Aufgabenbereich "Tabelle hinzufügen" Namen mit "&" nicht korrekt anzeigte.</span><span class="sxs-lookup"><span data-stu-id="03067-1200">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="03067-1201">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1201">Excel</span></span>

- <span data-ttu-id="03067-1202">Es wurde ein Problem behoben, bei dem die mehrstufige Kategorie "manuelles Intervall" in Diagrammen nicht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="03067-1202">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="03067-1203">Es wurde ein Problem mit 2D-Kartendiagrammen behoben, bei dem das Festlegen der Farben für die Werte "Max.", "Mittel" und "Min." für eine Reihe bei Verwendung von VBA nicht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="03067-1203">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="03067-1204">Es wurde ein Problem behoben, das die Fehlermeldung „Excel hat nicht ausreichend Ressourcen zur Verfügung für die Berechnung einer oder mehrerer Formeln“ verursachen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1204">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="03067-1205">Es wurde ein Problem, bei dem in Datenüberprüfungslisten u. U. nicht alle Elemente in der Liste angezeigt wurden, wenn die Office-Sprache auf Spanisch festgelegt war.</span><span class="sxs-lookup"><span data-stu-id="03067-1205">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="03067-1206">Ein Problem wurde behoben, bei dem beim Wechseln zwischen Arbeitsblättern mit großen Datenmengen eine deutliche Verzögerung auftrat, wenn ‚Seitenumbruchvorschau‘ aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="03067-1206">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>


- <span data-ttu-id="03067-1207">Es wurde ein Problem behoben, bei dem das Hinzufügen zu einer für die Datenüberprüfung verwendeten Tabelle die Optionen nicht für alle Blätter in der Arbeitsmappe aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1207">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


- <span data-ttu-id="03067-1208">Ein Problem wurde behoben, das beim Aktualisieren von OLAP-PivotTables zu einem Absturz führen könnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1208">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="03067-1209">Ein Problem wurde behoben, bei dem ChartSheet in einigen Fällen abgestürzt ist, wenn eine Formel über die Bearbeitungsleiste eingegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1209">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


- <span data-ttu-id="03067-1210">Es wurde ein Problem behoben, bei dem die Excel-Formularleiste nicht vollständig gerendert werden konnte, wenn die Verbindung zu einem Gerät verloren ging, wie z. B. beim Verbinden/Trennen einer Remote-Sitzung oder bei einem Monitorwechsel.</span><span class="sxs-lookup"><span data-stu-id="03067-1210">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>


### <a name="onenote"></a><span data-ttu-id="03067-1211">OneNote</span><span class="sxs-lookup"><span data-stu-id="03067-1211">OneNote</span></span>

- <span data-ttu-id="03067-1212">Es wurde ein Problem behoben, bei dem ein Benutzer nicht in der Lage war, eine Notizbuch-URL aus einem Textfeld in OutSpace File > Info auszuwählen und zu kopieren.</span><span class="sxs-lookup"><span data-stu-id="03067-1212">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


- <span data-ttu-id="03067-1213">Es wurde ein Problem behoben, dass beim Fahren mit der Maus über die grüne Farbe in der Farbauswahl des Notizbuchs das Popup "Rote Kreide" angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1213">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


- <span data-ttu-id="03067-1214">Es wurde ein Problem behoben, bei dem OneNote im Zeichenbereich hohe Kontrastfarben für benutzerdefinierte Designs nicht beachtete.</span><span class="sxs-lookup"><span data-stu-id="03067-1214">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


### <a name="outlook"></a><span data-ttu-id="03067-1215">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1215">Outlook</span></span>

- <span data-ttu-id="03067-1216">Behebt ein Problem, das dazu führte, dass automatisch generierte E-Mails mit einem leeren Textkörper gesendet wurden, wenn die Betreffzeile leer war.</span><span class="sxs-lookup"><span data-stu-id="03067-1216">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="03067-1217">Es wurde ein Problem behoben, bei dem die falsche Ordner-GUID für Ordner zwischengespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="03067-1217">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="03067-1218">Wenn ein Benutzer eine E-Mail-Adresse in das Feld "Empfänger" mit dem Anzeigenamen kopierte und einfügte, wurde die E-Mail-Adresse nicht immer ordnungsgemäß analysiert, woraufhin eine Warnung zu einer ungültigen E-Mail-Adresse angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1218">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="03067-1219">Das Problem wurde so behoben, dass Name und E-Mail-Adresse nun ordnungsgemäß analysiert werden und die Warnung nicht mehr angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="03067-1219">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="03067-1220">Es wurde ein Problem behoben, bei dem freigegebene Ordner nicht den übergeordneten Ordnernamen zurückgegeben haben.</span><span class="sxs-lookup"><span data-stu-id="03067-1220">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="03067-1221">Anstatt wurde ein leerer Pfad zurückgegeben, der nicht ordnungsgemäß an das primäre Konto ging.</span><span class="sxs-lookup"><span data-stu-id="03067-1221">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="03067-1222">Es wurde ein Problem behoben, bei dem die Option "Speichern unter" für klassische Anlagen nicht verfügbar war.</span><span class="sxs-lookup"><span data-stu-id="03067-1222">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="03067-1223">Es wurde ein Problem behoben, durch das ein Benutzer eine Möglichkeit zum Anpassen des Rechtfertigungstexts bietet, wenn eine Richtlinie überschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="03067-1223">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="03067-1224">Es wurde ein Problem behoben, bei dem „Änderungen nachverfolgen“ nach dem erneuten Öffnen des Entwurfs im schreibgeschützten Vorschaufenster aktiviert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1224">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="03067-1225">Es wurde ein Problem behoben, bei dem E-Mails ausgeblendet wurden, wenn „Posteingang mit Relevanz“ deaktiviert und eine Sortierung durchgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1225">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>


- <span data-ttu-id="03067-1226">Es wurde ein Problem behoben, bei dem Outlook eine zweite leere Signatur für Personen mit aktivierter Cloud-Einstellung erstellt hat.</span><span class="sxs-lookup"><span data-stu-id="03067-1226">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="03067-1227">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1227">PowerPoint</span></span>

- <span data-ttu-id="03067-1228">Es wurde ein Problem behoben, bei dem PowerPoint beim Exportieren in das PDF-Format keine rechteckige Aufzählungspunkte exportierte.</span><span class="sxs-lookup"><span data-stu-id="03067-1228">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="03067-1229">Ein Problem wurde behoben, bei dem GIF-Dateien im Editor und in Bildschirmpräsentationen nur einmal animiert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1229">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>


- <span data-ttu-id="03067-1230">Ein Problem wurde behoben, bei dem ein verknüpftes Excel-Diagramm fälschlicherweise in eine Excel-Tabelle geändert wurde, wenn der Benutzer den Quellpfad in den lokalen OneDrive-Ordner änderte.</span><span class="sxs-lookup"><span data-stu-id="03067-1230">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="03067-1231">Es wurde ein Problem behoben bei dem, wenn Sie sich auf der letzten Folie befinden und zur nächsten Folie wechseln, nachdem Sie "Sitzung beenden" gedrückt haben und bevor die Zusammenfassung angezeigt wird, der Dialog "Sitzung beenden" auch auf der Zusammenfassungsseite sichtbar ist.</span><span class="sxs-lookup"><span data-stu-id="03067-1231">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="03067-1232">Project</span><span class="sxs-lookup"><span data-stu-id="03067-1232">Project</span></span>

- <span data-ttu-id="03067-1233">Es wurde ein Problem mit der ConsolidateProjects-VBA-Methode behoben, wenn Sie versuchen, dasselbe Projekt mehrmals hinzuzufügen und AttachToSources auf "false" festzulegen.</span><span class="sxs-lookup"><span data-stu-id="03067-1233">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="03067-1234">Ein Problem wurde behoben, bei dem Sie, wenn Sie einen Ereigniscode ausführen, die Änderungen über eine Aufgaben-Maske durchführen und dann durch Klicken auf die Schaltfläche OK keine Änderungen vornehmen.</span><span class="sxs-lookup"><span data-stu-id="03067-1234">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="03067-1235">Es wurde ein Problem mit der ConsolidateProjects-VBA-Methode behoben, wenn Sie versuchen, dasselbe Projekt mehrmals hinzuzufügen und AttachToSources auf "false" festzulegen.</span><span class="sxs-lookup"><span data-stu-id="03067-1235">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="03067-1236">Es wurde ein Problem behoben, bei dem Sie, wenn Sie benutzerdefinierte Felder mit Formeln haben und den Ertragswert verwenden, Leistungsverzögerungen beim Wechsel der Ansichten und beim Öffnen von Projekt-/Aufgabendetails feststellen konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-1236">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="03067-1237">Es wurde ein Problem behoben, bei dem Project abstürzt, wenn Sie eine Gruppe auf die Ressourcennutzung oder die Arbeitsblattanzeige anwenden und dann eine Spalte einfügen.</span><span class="sxs-lookup"><span data-stu-id="03067-1237">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


### <a name="word"></a><span data-ttu-id="03067-1238">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1238">Word</span></span>

- <span data-ttu-id="03067-1239">Ein Problem wurde behoben, bei dem Links zu workflowaktivierten Dateien nicht erwartungsgemäß geöffnet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1239">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>


- <span data-ttu-id="03067-1240">Es wurde ein Problem behoben, bei dem es vorkam, dass wenn ein Benutzer auf eine nachverfolgte Änderung tippte (Einfügung/Löschung), ein Kommentar-Popup angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1240">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="03067-1241">Es wurde ein Problem mit dem Löschen von Kommentarbeschriftungen in Word behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-1241">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="03067-1242">Es wurde ein Problem in Outlook mit auf "Nicht weiterleiten" festgelegten Nachrichten behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-1242">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="03067-1243">Es wurde ein Problem mit dem Speichern eines Word-Dokuments mit Zitaten und Formeln behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-1243">We fixed an issue with saving Word document that contains citation and equation.</span></span>


- <span data-ttu-id="03067-1244">Es wurde ein Problem mit dem Dialogfeld "Formatvorlagenkatalog" behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-1244">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="03067-1245">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-1245">Office Suite</span></span>

- <span data-ttu-id="03067-p172">Wenn ein Benutzer ein Dokument/ eine Datei auf Tintenstrahldrucker aus Office druckt und die Druckertintenstand niedrig ist, wird die Nachricht „Wenig Toner“ oder „Kein Toner“ angezeigt, auch wenn Tintenstrahldrucker keine Toner haben. Die Nachricht wurde geändert, um „Wenig Toner/Tinte“ bzw. „Kein Toner/keine Tinte“ anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="03067-p172">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-october-07"></a><span data-ttu-id="03067-1249">Version 2009: 07. Oktober</span><span class="sxs-lookup"><span data-stu-id="03067-1249">Version 2009: October 07</span></span>
<span data-ttu-id="03067-1250">*Version 2009 (Build 13231.20360)*</span><span class="sxs-lookup"><span data-stu-id="03067-1250">*Version 2009 (Build 13231.20360)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1252">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1252">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-1253">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1253">Excel</span></span>

- <span data-ttu-id="03067-1254">**Datentypen mit Microsoft Power Query für Excel erstellen:** Erstellen Sie umfangreiche Datentypen mit Microsoft Power Query für Excel von jeder Datenquelle</span><span class="sxs-lookup"><span data-stu-id="03067-1254">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-1255">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1255">Outlook</span></span>

- <span data-ttu-id="03067-1256">**Die Grammatikprüfung hält Ihnen den Rücken frei:** Outlook markiert Grammatikfehler während der Eingabe, so dass Sie Vorschläge mit einem einzigen Klick anwenden können.</span><span class="sxs-lookup"><span data-stu-id="03067-1256">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> <br /><span data-ttu-id="03067-1257">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/grammar-and-style-suggestions-available-in-outlook)</span><span class="sxs-lookup"><span data-stu-id="03067-1257">See details in [blog post](https://insider.office.com/de-DE/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1260">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1260">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1261">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1261">Outlook</span></span>

- <span data-ttu-id="03067-1262">Behebt ein Problem, das bewirkt, dass die Suche keine Ergebnisse zurückgibt, wenn nicht zwischengespeicherte freigegebene Kalender durchsucht werden.</span><span class="sxs-lookup"><span data-stu-id="03067-1262">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="03067-1263">Behebt ein Problem, das bewirkt hat, dass einige Benutzer Outlook unerwartet starten, wenn Sie offline sind.</span><span class="sxs-lookup"><span data-stu-id="03067-1263">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="03067-1264">Behebt ein Problem, durch das Delegaten beim Öffnen freigegebener Ordner in einem anderen Postfach zeitweilige Fehler erhalten.</span><span class="sxs-lookup"><span data-stu-id="03067-1264">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="03067-1265">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1265">PowerPoint</span></span>

- <span data-ttu-id="03067-1266">Sicherheitsproblembehebung für ein Problems, bei dem IRM-Schutz beim Öffnen einer PowerPoint-Datei in der geschützten Anzeige deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1266">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="03067-1267">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-1267">Office Suite</span></span>

- <span data-ttu-id="03067-p173">Wenn ein Benutzer ein Dokument/ eine Datei auf Tintenstrahldrucker aus Office druckt und die Druckertintenstand niedrig ist, wird die Nachricht „Wenig Toner“ oder „Kein Toner“ angezeigt, auch wenn Tintenstrahldrucker keine Toner haben. Die Nachricht wurde geändert, um „Wenig Toner/Tinte“ bzw. „Kein Toner/keine Tinte“ anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="03067-p173">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners. Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-september-26"></a><span data-ttu-id="03067-1271">Version 2009: 26. September</span><span class="sxs-lookup"><span data-stu-id="03067-1271">Version 2009: September 26</span></span>
<span data-ttu-id="03067-1272">*Version 2009 (Build 13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="03067-1272">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1274">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1274">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1275">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1275">Outlook</span></span>

- <span data-ttu-id="03067-1276">Behebt ein Problem, das dazu führte, dass einige automatisch generierte E-Mails mit einem leeren Textkörper gesendet wurden, wenn die Betreffzeile leer war.</span><span class="sxs-lookup"><span data-stu-id="03067-1276">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="project"></a><span data-ttu-id="03067-1277">Project</span><span class="sxs-lookup"><span data-stu-id="03067-1277">Project</span></span>

- <span data-ttu-id="03067-1278">Ein Problem wurde behoben, bei dem Sie, wenn Sie einen Ereigniscode ausführen, die Änderungen über eine Aufgaben-Maske durchführen und dann durch Klicken auf die Schaltfläche OK keine Änderungen vornehmen.</span><span class="sxs-lookup"><span data-stu-id="03067-1278">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-september-21"></a><span data-ttu-id="03067-1280">Version 2009: 21. September</span><span class="sxs-lookup"><span data-stu-id="03067-1280">Version 2009: September 21</span></span>
<span data-ttu-id="03067-1281">*Version 2009 (Build 13231.20200)*</span><span class="sxs-lookup"><span data-stu-id="03067-1281">*Version 2009 (Build 13231.20200)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1283">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1283">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="03067-1284">Zugriff</span><span class="sxs-lookup"><span data-stu-id="03067-1284">Access</span></span>

- <span data-ttu-id="03067-1285">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="03067-1285">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="03067-1286">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="03067-1286">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="03067-1287">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1287">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="03067-1288">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1288">Excel</span></span>

- <span data-ttu-id="03067-1289">**iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen.</span><span class="sxs-lookup"><span data-stu-id="03067-1289">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="03067-1290">Keine Konvertierung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="03067-1290">No conversion required.</span></span><br /><span data-ttu-id="03067-1291">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="03067-1291">See details in [blog post](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="03067-1292">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="03067-1292">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="03067-1293">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="03067-1293">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="03067-1294">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1294">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="03067-1295">OneNote</span><span class="sxs-lookup"><span data-stu-id="03067-1295">OneNote</span></span>

- <span data-ttu-id="03067-1296">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="03067-1296">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="03067-1297">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="03067-1297">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="03067-1298">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1298">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="03067-1299">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1299">Outlook</span></span>

- <span data-ttu-id="03067-1300">**Unterhaltung löschen nach Nachrichtenbesitzer:** Dieses Feature ermöglicht es Ihnen, eine Unterhaltung nach dem Nachrichtenbesitzer zu löschen.</span><span class="sxs-lookup"><span data-stu-id="03067-1300">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

- <span data-ttu-id="03067-1301">**iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen.</span><span class="sxs-lookup"><span data-stu-id="03067-1301">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="03067-1302">Keine Konvertierung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="03067-1302">No conversion required.</span></span><br /><span data-ttu-id="03067-1303">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="03067-1303">See details in [blog post](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="03067-1304">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="03067-1304">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="03067-1305">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="03067-1305">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="03067-1306">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1306">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="powerpoint"></a><span data-ttu-id="03067-1307">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1307">PowerPoint</span></span>

- <span data-ttu-id="03067-1308">**iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen.</span><span class="sxs-lookup"><span data-stu-id="03067-1308">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="03067-1309">Keine Konvertierung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="03067-1309">No conversion required.</span></span><br /><span data-ttu-id="03067-1310">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="03067-1310">See details in [blog post](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="03067-1311">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="03067-1311">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="03067-1312">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="03067-1312">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="03067-1313">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1313">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="03067-1314">Project</span><span class="sxs-lookup"><span data-stu-id="03067-1314">Project</span></span>

- <span data-ttu-id="03067-1315">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="03067-1315">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="03067-1316">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="03067-1316">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="03067-1317">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1317">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="03067-1318">Publisher</span><span class="sxs-lookup"><span data-stu-id="03067-1318">Publisher</span></span>

- <span data-ttu-id="03067-1319">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="03067-1319">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="03067-1320">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="03067-1320">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="03067-1321">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1321">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="03067-1322">Visio</span><span class="sxs-lookup"><span data-stu-id="03067-1322">Visio</span></span>

- <span data-ttu-id="03067-1323">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="03067-1323">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="03067-1324">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="03067-1324">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="03067-1325">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1325">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="03067-1326">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1326">Word</span></span>

- <span data-ttu-id="03067-1327">**iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen.</span><span class="sxs-lookup"><span data-stu-id="03067-1327">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="03067-1328">Keine Konvertierung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="03067-1328">No conversion required.</span></span><br /><span data-ttu-id="03067-1329">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="03067-1329">See details in [blog post](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="03067-1330">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="03067-1330">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="03067-1331">Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus.</span><span class="sxs-lookup"><span data-stu-id="03067-1331">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="03067-1332">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1332">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1335">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1335">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="03067-1336">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1336">PowerPoint</span></span>

- <span data-ttu-id="03067-1337">Es wurde ein Problem behoben, das die gemeinsame Dokumenterstellung für Dateien mit großen Mengen eines bestimmten Datenobjekttyps (E2o) verlangsamt hat.</span><span class="sxs-lookup"><span data-stu-id="03067-1337">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-september-14"></a><span data-ttu-id="03067-1339">Version 2009: 14. September</span><span class="sxs-lookup"><span data-stu-id="03067-1339">Version 2009: September 14</span></span>
<span data-ttu-id="03067-1340">*Version 2009 (Build 13231.20152)*</span><span class="sxs-lookup"><span data-stu-id="03067-1340">*Version 2009 (Build 13231.20152)*</span></span>
* <span data-ttu-id="03067-1341">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="03067-1341">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-september-10"></a><span data-ttu-id="03067-1344">Version 2009: 10. September</span><span class="sxs-lookup"><span data-stu-id="03067-1344">Version 2009: September 10</span></span>
<span data-ttu-id="03067-1345">*Version 2009 (Build 13231.20126)*</span><span class="sxs-lookup"><span data-stu-id="03067-1345">*Version 2009 (Build 13231.20126)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1347">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1347">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="03067-1348">Access</span><span class="sxs-lookup"><span data-stu-id="03067-1348">Access</span></span>

- <span data-ttu-id="03067-1349">Dieses Problem wurde nun behoben, und es sollte jetzt kein Absturz mehr auftreten.</span><span class="sxs-lookup"><span data-stu-id="03067-1349">This issue has now been resolved and you should no longer experience a crash.</span></span>


- <span data-ttu-id="03067-1350">Ein Problem wurde behoben, bei dem Verbindungen zu einer ODBC-Datenbank mit Anwendungen von Drittanbietern nicht funktionierten.</span><span class="sxs-lookup"><span data-stu-id="03067-1350">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>


### <a name="excel"></a><span data-ttu-id="03067-1351">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1351">Excel</span></span>

- <span data-ttu-id="03067-1352">Es wurde ein Problem behoben, bei dem beim Öffnen einer Datei, die die LET-Funktion enthält, die Warnmeldung angezeigt wurde: "Wir haben ein Problem mit dem Inhalt in "Ihrer Datei.xlsx" gefunden.</span><span class="sxs-lookup"><span data-stu-id="03067-1352">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="03067-1353">Möchten Sie, dass wir so viel wie möglich wiederherstellen?</span><span class="sxs-lookup"><span data-stu-id="03067-1353">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="03067-1354">Wenn die Quelle für diese Arbeitsmappe vertrauenswürdig ist, klicken Sie auf „Ja“.</span><span class="sxs-lookup"><span data-stu-id="03067-1354">If you trust the source of this workbook, click Yes".</span></span>


- <span data-ttu-id="03067-1355">Es wurde ein Problem behoben, bei dem, wenn ein Benutzer einen Formelnamen einschließlich der Klammer eingab und die Hilfe über F1 aufrief, das für diese Formel spezifische Hilfethema nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1355">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>


- <span data-ttu-id="03067-1356">Es wurde ein Problem behoben: Beim Festlegen der FormulaR1C1-Eigenschaft für einen Bereich mithilfe eines Makros waren die Zellbezüge falsch, wenn ein Diagrammblatt das aktive Blatt war.</span><span class="sxs-lookup"><span data-stu-id="03067-1356">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="03067-1357">Es wurde ein Problem behoben, bei dem Benutzer einen PivotTable-Filter nicht ändern konnten, weil er auf einen Wert eingestellt war, der in einer Analysis Services-Datenbank nicht mehr vorhanden war.</span><span class="sxs-lookup"><span data-stu-id="03067-1357">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="03067-1358">Es wurde ein Absturz im Zusammenhang mit XLAM-Add-In-Referenzen und benannten Bereichen behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-1358">Fixed a crash related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="03067-p188">Es wurde ein Problem behoben, bei dem Benutzer, die einen benutzerdefinierten Stil auf ein dynamisches Array anwandten, die Fehlermeldung erhielten: „Sie können einen Teil eines Arrays nicht ändern“. Dies war eine veraltete Einschränkung, die entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-p188">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array". This was a legacy restriction that has been removed.</span></span>


- <span data-ttu-id="03067-1361">Es wurde ein Problem behoben, bei dem den Schaltflächen zugewiesene Makros nach der Wiederherstellung einer älteren Version der Datei beschädigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1361">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>


- <span data-ttu-id="03067-1362">Ein Problem wurde behoben, bei dem Freihandeingaben dazu führen konnten, dass Excel nicht mehr reagierte.</span><span class="sxs-lookup"><span data-stu-id="03067-1362">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="03067-1363">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1363">Outlook</span></span>

- <span data-ttu-id="03067-1364">Es wurde ein Problem behoben, das mehr Flexibilität bei der Aktivierung/Deaktivierung der Standardprotokollierungsoptionen über die Gruppenrichtlinie bietet.</span><span class="sxs-lookup"><span data-stu-id="03067-1364">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>


- <span data-ttu-id="03067-1365">Es wurde ein Problem behoben, bei dem der Legacy-Domänenname für einen E-Mail-Absender beibehalten und angezeigt wurde, nachdem ein Entwurf der E-Mail zwischen Postfächern mit Assistenten- und Manager-Berechtigungen verschoben wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1365">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>


- <span data-ttu-id="03067-1366">Es wurde ein Problem behoben, das dazu führte, dass einige Benutzer Outlook im Offline-Status starteten, bis sie manuell wählten, online zu arbeiten.</span><span class="sxs-lookup"><span data-stu-id="03067-1366">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="03067-1367">Es wurde ein Problem behoben, bei dem das Ausführen des VBA-Codes ActiveInspector.CommandBars.ExecuteMso ("ShowSchedulingPage") nach dem Aktivieren des Einzeiligen Menübands (SLR) zu einem Laufzeitfehler führen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1367">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>


- <span data-ttu-id="03067-1368">Es wurde ein Problem behoben, bei dem die Schaltflächen "OK" und "Abbrechen" im Dialogfeld "Automatische Antworten" auf einem System mit einer hohen Auflösung (z. B. 1750 x 1920) in Verbindung mit einer großen Textgröße (z. B. 175 %) nicht sichtbar waren.</span><span class="sxs-lookup"><span data-stu-id="03067-1368">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>


- <span data-ttu-id="03067-1369">Es wurde eine Bedingung behoben, nach der das Senden einer Besprechungsanfrage von einer leeren Kontaktgruppe an eine andere Kontaktgruppe zu einem Absturz führen würde.</span><span class="sxs-lookup"><span data-stu-id="03067-1369">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>


- <span data-ttu-id="03067-1370">Es wurde ein Problem behoben, bei dem es zu einem Absturz kam, wenn Benutzer bestimmte sehr große E-Mails öffneten.</span><span class="sxs-lookup"><span data-stu-id="03067-1370">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="03067-1371">Es wurde ein Problem behoben, bei dem, wenn die Gruppenrichtlinie erfordert, dass ein Add-In immer aktiviert sein muss, die Überwachungs-Add-Ins nicht mehr verfügbar sind, um Benutzer daran zu hindern, das Add-In zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="03067-1371">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>


- <span data-ttu-id="03067-1372">Behebt ein Problem, das dazu führte, dass Benutzer durch das Auswählen mehrerer Nachrichten E-Mail-Inhalte senden konnten, für die eine "Nicht weiterleiten"-Richtlinie in OneNote festgelegt war.</span><span class="sxs-lookup"><span data-stu-id="03067-1372">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>


- <span data-ttu-id="03067-1373">Ein Problem wurde behoben: Benutzer können IRM (Information Rights Management) jetzt für Outlook deaktivieren, ohne es für die übrigen Office-Anwendungen deaktivieren zu müssen.</span><span class="sxs-lookup"><span data-stu-id="03067-1373">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="03067-1374">Ein Problem wurde behoben, bei dem die Benutzerkontoattribute in Active Directory für "otherTelephone" und "otherHomePhone" nicht den entsprechenden Outlook-LDAP-Attributen zugeordnet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1374">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>


- <span data-ttu-id="03067-1375">Diese Änderung behebt ein Problem, bei dem die Seite "Besprechung" weiterhin angezeigt wurde, nachdem der Benutzer die Registerkarten von der Seite "Besprechung" auf die Seite "Terminplanungs-Assistent" gewechselt hatte.</span><span class="sxs-lookup"><span data-stu-id="03067-1375">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="03067-1376">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1376">PowerPoint</span></span>

- <span data-ttu-id="03067-1377">Ein Problem wurde behoben, bei dem das Menüband bzw. die Titelleiste unter bestimmten Bedingungen nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1377">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>


- <span data-ttu-id="03067-1378">Es wurde ein Problem behoben, bei dem nach dem Starten von PowerPoint, dem Einfügen einer Folie und dem Öffnen und Schließen des Kommentarbereichs die Folien im Miniaturansichtenbereich als überlappend angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1378">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>


- <span data-ttu-id="03067-1379">Es wurde ein Problem behoben, durch das die Funktion zum Einfügen eines Videos deaktiviert war.</span><span class="sxs-lookup"><span data-stu-id="03067-1379">We fixed an issue where the functionality to insert a video was disabled.</span></span>


- <span data-ttu-id="03067-1380">Es wurde ein Problem behoben, bei dem Videos in Bildschirmpräsentationen nicht automatisch wiedergegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1380">We fixed an issue where videos were not playing automatically in slideshows.</span></span>


### <a name="project"></a><span data-ttu-id="03067-1381">Project</span><span class="sxs-lookup"><span data-stu-id="03067-1381">Project</span></span>

- <span data-ttu-id="03067-1382">Es wurde ein Problem behoben, bei dem, wenn eine Ressource mehrere Kostensatztabellen hat, die verbleibenden Kosten möglicherweise nicht korrekt berechnet werden.</span><span class="sxs-lookup"><span data-stu-id="03067-1382">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>


- <span data-ttu-id="03067-1383">Es wurde ein Problem behoben, bei dem das Projektabschlussdatum für Projekte, die mit der Microsoft Office SharePoint Online-Aufgabenliste verbunden sind, nicht aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="03067-1383">We fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


### <a name="visio"></a><span data-ttu-id="03067-1384">Visio</span><span class="sxs-lookup"><span data-stu-id="03067-1384">Visio</span></span>

- <span data-ttu-id="03067-1385">Die Live-Vorschau stürzt ab, wenn die Textausrichtung von Kunden gemeldet wird.</span><span class="sxs-lookup"><span data-stu-id="03067-1385">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="03067-1386">Häufigster Absturz im Juli, Kopie.</span><span class="sxs-lookup"><span data-stu-id="03067-1386">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="03067-1387">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1387">Word</span></span>

- <span data-ttu-id="03067-1388">Es wurde ein Problem behoben, bei dem die Kommentarkarte einen Rahmen um den Kommentartext anzeigte, wenn der Benutzer auf den Kommentar klickte.</span><span class="sxs-lookup"><span data-stu-id="03067-1388">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>


- <span data-ttu-id="03067-1389">Es wurde ein Problem behoben, bei dem das Aufzählungsbildsymbol nicht korrekt angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1389">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>


- <span data-ttu-id="03067-1390">Ein Problem wurde behoben, bei dem der Benutzer die Kopf-oder Fußzeile beim Auswählen eines Kommentars nicht verlassen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1390">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>


- <span data-ttu-id="03067-1391">Ein Problem wurde behoben, bei dem Word nach dem Löschen von Kommentaren abstürzen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1391">We fixed an issue where Word could crash after comments were deleted.</span></span>


- <span data-ttu-id="03067-1392">Es wurde ein Problem behoben, bei dem, wenn ein Benutzer einen Kommentar-Entwurf erstellte, der in einer Zeile verankert war, die bereits bestätigte Kommentare enthielt, der Entwurf in der falschen Reihenfolge in Bezug auf den bestätigten Kommentar im SideTrack angeordnet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1392">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>


- <span data-ttu-id="03067-1393">Es wurde ein Problem behoben, bei dem der Fokus nicht auf den Kommentarbereich gelegt wurde, wenn das Dokument auf 160 % oder mehr gezoomt wurde und der Kommentarbereich nicht sichtbar war.</span><span class="sxs-lookup"><span data-stu-id="03067-1393">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>


- <span data-ttu-id="03067-1394">Es wurde ein Problem behoben, das Benutzer daran hinderte, Benutzerkommentar-Threads zu sehen, die die Sidetrack-Grenze überschritten, weil das Scrollen durch den Sidetrack nicht funktioniert hat.</span><span class="sxs-lookup"><span data-stu-id="03067-1394">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>


- <span data-ttu-id="03067-1395">Ein Problem wurde behoben, bei dem die Suche nach aufgelösten Kommentaren im Sidetrack-Bereich nicht funktioniert hat.</span><span class="sxs-lookup"><span data-stu-id="03067-1395">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>


- <span data-ttu-id="03067-1396">Es wurde ein Problem behoben, bei dem die Kommentare zu einem Dokument auf anderen geöffneten Dokumenten angezeigt wurden, nachdem zwischen den mehreren geöffneten Dokumenten gewechselt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1396">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>


- <span data-ttu-id="03067-1397">Es wurde ein Problem behoben, bei dem lange Links beim Speichern eines Dokuments im HTML-Format nicht umgebrochen wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1397">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="03067-1398">Ein Problem wurde behoben, bei dem in einigen Fällen Aufzählungszeichen in E-Mails nicht korrekt angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1398">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>


- <span data-ttu-id="03067-1399">Es wurde ein Problem mit Makros behoben, in denen „AutoOpen“ vor „AutoExec“ ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="03067-1399">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>


### <a name="office-suite"></a><span data-ttu-id="03067-1400">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-1400">Office Suite</span></span>

- <span data-ttu-id="03067-1401">Es wurde ein Problem mit dem Office-Bereitstellungstool behoben, bei dem die Konfiguration fehlschlug, wenn das Feature "RemoveMSI" in Anwesenheit des Produkts „Microsoft-Anwendungsfehler-Berichterstattung“ in Office 2007 verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1401">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="03067-1402">Im Dialogfeld "Bild komprimieren" wurde ein Problem behoben, bei dem einige vom Benutzer ausgewählte DPI-Einstellungen nicht beibehalten wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1402">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>


- <span data-ttu-id="03067-1403">Diese Änderung behebt ein Problem, bei dem im Dialogfeld „Bild komprimieren“ bestimmte Benutzereinstellungen nicht beibehalten werden.</span><span class="sxs-lookup"><span data-stu-id="03067-1403">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-september-04"></a><span data-ttu-id="03067-1405">Version 2008: 4. September</span><span class="sxs-lookup"><span data-stu-id="03067-1405">Version 2008: September 04</span></span>
<span data-ttu-id="03067-1406">*Version 2008 (Build 13127.20378)*</span><span class="sxs-lookup"><span data-stu-id="03067-1406">*Version 2008 (Build 13127.20378)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1408">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1408">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="03067-1409">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-1409">Office Suite</span></span>

- <span data-ttu-id="03067-1410">Diese Änderung behebt ein Problem, bei dem im Dialogfeld „Bild komprimieren“ bestimmte Benutzereinstellungen nicht beibehalten werden.</span><span class="sxs-lookup"><span data-stu-id="03067-1410">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-september-02"></a><span data-ttu-id="03067-1412">Version 2008: 2. September</span><span class="sxs-lookup"><span data-stu-id="03067-1412">Version 2008: September 02</span></span>
<span data-ttu-id="03067-1413">*Version 2008 (Build 13127.20360)*</span><span class="sxs-lookup"><span data-stu-id="03067-1413">*Version 2008 (Build 13127.20360)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1415">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1415">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-1416">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1416">Excel</span></span>

- <span data-ttu-id="03067-1417">**Speichern von Shapes als Bildern:** mit nur wenigen Mausklicks können Sie eine Form, ein Symbol oder ein anderes Objekt als Bilddatei speichern, um Sie an anderer Stelle wiederzuverwenden.</span><span class="sxs-lookup"><span data-stu-id="03067-1417">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="03067-1418">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1418">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="03067-1419">**Schnelle Bearbeitungen mit dem Excel-Stift:** Ein Stifttool, mit dem Sie handschriftliche Eingaben machen und Ihre Daten schnell bearbeiten können.</span><span class="sxs-lookup"><span data-stu-id="03067-1419">**Make quick edits using the Excel pen:** Pen Tool to help you handwrite and make quick edits to your data</span></span>



[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1422">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1422">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-1423">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1423">Excel</span></span>

- <span data-ttu-id="03067-1424">Es wurde ein Problem behoben, bei dem Excel unter bestimmten Umständen abstürzte, wenn "Format übertragen" verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1424">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="03067-1425">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1425">Word</span></span>

- <span data-ttu-id="03067-1426">Ein Problem wurde behoben, bei dem die Basisformatvorlagen nicht mit der Standardformatvorlage aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1426">We fixed an issue which the base styles are not updated with Normal style.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-august-27"></a><span data-ttu-id="03067-1428">Version 2008: 27. August</span><span class="sxs-lookup"><span data-stu-id="03067-1428">Version 2008: August 27</span></span>
<span data-ttu-id="03067-1429">*Version 2008 (Build 13127.20296)*</span><span class="sxs-lookup"><span data-stu-id="03067-1429">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1433">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1433">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1434">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1434">Outlook</span></span>

- <span data-ttu-id="03067-1435">Behebt ein Problem, das dazu führte, dass Benutzer, die versuchten, eine Besprechungsanfrage von einem zu ihrem Profil hinzugefügten sekundären Konto aus zu erstellen, kein leeres Von: Feld anstelle ihrer E-Mail-Adresse sahen.</span><span class="sxs-lookup"><span data-stu-id="03067-1435">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="03067-1436">Behebt ein Problem, das dazu führte, dass Benutzer nach dem Hinzufügen eines freigegebenen Postfachs keine Verbindung mit öffentlichen Ordnern herstellen konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-1436">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="03067-1437">Behebt ein Problem, das bei der Interaktion mit Cloud-Anlagen gelegentlich zu Abstürzen führte.</span><span class="sxs-lookup"><span data-stu-id="03067-1437">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="03067-1438">Dies behebt ein Problem, das beim Bearbeiten von Empfängern gelegentlich zu Abstürzen führte.</span><span class="sxs-lookup"><span data-stu-id="03067-1438">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="03067-1439">Behebt ein Problem, das dazu führte, dass Benutzern bei Verwendung der kompakten Ansicht gelegentlich Anomalien angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1439">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

### <a name="word"></a><span data-ttu-id="03067-1440">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1440">Word</span></span>

- <span data-ttu-id="03067-1441">Diese Änderung behebt ein Problem, bei dem Office-Anwendungen nach einer vorherigen gemeinsamen Dokumenterstellung in einem Silent-Save-Fehlerstatus hängenbleiben konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-1441">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="03067-1442">Es wurde ein Problem behoben, bei dem das Makro „AutoOpen“ vor „Autoexec“ ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="03067-1442">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-august-25"></a><span data-ttu-id="03067-1444">Version 2008: 25. August</span><span class="sxs-lookup"><span data-stu-id="03067-1444">Version 2008: August 25</span></span>
<span data-ttu-id="03067-1445">*Version 2008 (Build 13127.20268)*</span><span class="sxs-lookup"><span data-stu-id="03067-1445">*Version 2008 (Build 13127.20268)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1447">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1447">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1448">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1448">Outlook</span></span>

- <span data-ttu-id="03067-1449">**Empfangen von E-Mail-Vorschlägen bei der Suche nach Personen:** Während Sie Ihre Suchbegriffe in Outlook eingeben, werden Ihnen in den Vorschlägen die relevantesten E-Mails angezeigt.</span><span class="sxs-lookup"><span data-stu-id="03067-1449">**Receive email suggestions when searching by person.:** As you type your search terms in Outlook you'll receive the most relevant emails surfaced in the suggestions.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1452">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1452">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1453">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1453">Outlook</span></span>

- <span data-ttu-id="03067-1454">Behebt ein Problem, durch das Benutzern beim Beantworten von oder Verfassen neuer E-Mails den folgenden Fehler angezeigt wurde: „Einige der Dateien auf dieser Webseite befinden sich nicht am erwarteten Speicherort.</span><span class="sxs-lookup"><span data-stu-id="03067-1454">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="03067-1455">Möchten Sie sie dennoch herunterladen?</span><span class="sxs-lookup"><span data-stu-id="03067-1455">Do you want to download them anyway?</span></span> <span data-ttu-id="03067-1456">Wenn Sie sicher sind, dass die Webseite aus einer vertrauenswürdigen Quelle stammt, klicken Sie auf 'Ja'.“</span><span class="sxs-lookup"><span data-stu-id="03067-1456">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="03067-1457">Project</span><span class="sxs-lookup"><span data-stu-id="03067-1457">Project</span></span>

- <span data-ttu-id="03067-1458">Ein Problem wurde behoben, bei dem die Restkosten nicht immer richtig berechnet wurden, wenn für eine Ressource mehrere Kostensatztabellen definiert waren.</span><span class="sxs-lookup"><span data-stu-id="03067-1458">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


### <a name="word"></a><span data-ttu-id="03067-1459">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1459">Word</span></span>

- <span data-ttu-id="03067-1460">Es wurde ein Problem behoben, durch das es bei Benutzern beim Antworten auf oder Verfassen einer neuen E-Mail zu einem Absturz kam.</span><span class="sxs-lookup"><span data-stu-id="03067-1460">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-august-17"></a><span data-ttu-id="03067-1462">Version 2008: 17. August</span><span class="sxs-lookup"><span data-stu-id="03067-1462">Version 2008: August 17</span></span>
<span data-ttu-id="03067-1463">*Version 2008 (Build 13127.20208)*</span><span class="sxs-lookup"><span data-stu-id="03067-1463">*Version 2008 (Build 13127.20208)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1465">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1465">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1466">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1466">Outlook</span></span>

- <span data-ttu-id="03067-1467">Es wurde ein Problem behoben, das bewirkt hat, dass Besprechungen aus dem Kalender eines Managers nicht entfernt werden konnten, wenn sie von einem Delegierten unter bestimmten Umständen abgelehnt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1467">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="03067-1468">Es wurde ein Problem behoben, das bewirkt hat, dass Benutzende einiger Zeichensätze beim Hinzufügen eines Smart Link zu einer Microsoft Office SharePoint Online-Datei Dateinamen falsch angezeigt bekamen.</span><span class="sxs-lookup"><span data-stu-id="03067-1468">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="03067-1469">Es wurde ein Problem behoben, das zu einem Absturz führte, wenn Benutzende beim Löschen von 4 oder mehr E-Mails von einem POP-Konto mit der Option "Nur Kopfzeilen herunterladen" einen Absturz erlebten.</span><span class="sxs-lookup"><span data-stu-id="03067-1469">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="03067-1470">Es wurde ein Problem behoben, das bewirkt hat, dass das Rechtsklick-Kontextmenü nicht in den Suchsteuerelementen angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1470">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-august-11"></a><span data-ttu-id="03067-1472">Version 2008: 11. August</span><span class="sxs-lookup"><span data-stu-id="03067-1472">Version 2008: August 11</span></span>
<span data-ttu-id="03067-1473">*Version 2008 (Build 13127.20164)*</span><span class="sxs-lookup"><span data-stu-id="03067-1473">*Version 2008 (Build 13127.20164)*</span></span>

<span data-ttu-id="03067-1474">Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="03067-1474">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1476">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1476">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="03067-1477">Zugriff</span><span class="sxs-lookup"><span data-stu-id="03067-1477">Access</span></span>

- <span data-ttu-id="03067-1478">Diese Korrektur behebt das Problem, bei dem der Versuch, bestimmte Abfragen auszuführen, zuvor die Fehlermeldung „Abfrage ist zu komplex“ erzeugt hat.</span><span class="sxs-lookup"><span data-stu-id="03067-1478">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="03067-1479">Wenn Sie Office 365 installiert haben, müssen Sie nicht mehr unsere ACE Redistributable Engine installieren, um ACE außerhalb des Office-Ökosystems bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="03067-1479">If you have Office 365 installed, you no longer need to install our ACE Redistributable Engine to expose ACE outside of the Office ecosystem.</span></span> <span data-ttu-id="03067-1480">Daher benötigen Sie für Benutzende mit Office 365 die ACE Redist Engine nicht mehr, und folglich sollte dieses Problem nicht auftreten.</span><span class="sxs-lookup"><span data-stu-id="03067-1480">Therefore, for those with Office 365, you will no longer need the ACE Redist Engine, and consequently you should not experience this issue.</span></span>

- <span data-ttu-id="03067-1481">Das Problem wurde gelöst – Sie können nun unseren ODBC-Treiber außerhalb der Office-Click-to-Run-App verwenden.</span><span class="sxs-lookup"><span data-stu-id="03067-1481">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="03067-1482">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1482">Excel</span></span>

- <span data-ttu-id="03067-1483">Das Problem wurde behoben, bei dem, wenn die Reihenfolge einer Diagrammserie geändert wurde, das entsprechende, an der Serie ausgerichtete Kontrollkästchen nicht zusammen mit der Serie neu geordnet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1483">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>

- <span data-ttu-id="03067-1484">Beim Versuch eine Datei zu speichern, die eine Formel mit der Funktion LET() enthält, konnte ein Fehler auftreten.</span><span class="sxs-lookup"><span data-stu-id="03067-1484">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="03067-1485">Ein Problem wurde behoben, bei dem Diagramme nicht immer wie erwartet aktualisiert wurden, wenn "ForceFullCalculation" über VBA für die Arbeitsmappe aktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1485">We fixed an issue where charts were not always updated as expected when "ForceFullCalculation" was enabled via VBA for the workbook.</span></span>

- <span data-ttu-id="03067-1486">Ein Problem wurde behoben, bei dem die Kopie eines Bildes mit einer radialen Verlaufsfüllung nicht mit dem Original übereinstimmte.</span><span class="sxs-lookup"><span data-stu-id="03067-1486">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="onenote"></a><span data-ttu-id="03067-1487">OneNote</span><span class="sxs-lookup"><span data-stu-id="03067-1487">OneNote</span></span>

- <span data-ttu-id="03067-1488">Wir haben ein Problem behoben, bei dem der Platzhaltertext im Bearbeitungsfeld „Suchen“ überlaufen würde, wenn die Größe des Anwendungsfensters auf eine kleine Dimension geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1488">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-1489">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1489">Outlook</span></span>

- <span data-ttu-id="03067-1490">Wir haben ein Problem beim Erstellen mehrerer Profile in Outlook von derselben E-Mail-Domäne behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-1490">We fixed an issue around creating multiple profiles in Outlookfrom the same email domain.</span></span>

- <span data-ttu-id="03067-1491">Es wurde ein Problem behoben, durch das einige Benutzende des Features "Verbesserungen bei gemeinsam genutzten Kalendern" nicht in der Lage waren, einen neu hinzugefügten freigegebenen Kalender anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="03067-1491">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="03067-1492">Es wurde ein Problem behoben, das dazu führte, dass das Schloss-Symbol im Header von S/MIME-verschlüsselten Nachrichten nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1492">Addressed an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>

- <span data-ttu-id="03067-1493">Wir haben ein Problem behoben, bei dem die Option "Weiterleitung zulassen" in den "Antwortoptionen" der freigegebenen Kalenderbesprechung fehlte, wenn "Gemeinsamer Ordner herunterladen" NICHT aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="03067-1493">We fixed an issue where the "Allow Forwarding" option was missing from the shared calendar meeting "Response Options" if Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="03067-1494">Ein Problem wurde behoben, das dazu führte, dass Benutzer OneDrive-Anlagen von außerhalb ihres Mandanten nicht auf ihrem lokalen Computer speichern konnten, wenn sie im Dialogfeld "Sicherheit" die Option "Speichern" wählten.</span><span class="sxs-lookup"><span data-stu-id="03067-1494">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="03067-1495">Es wurde ein Problem behoben, bei dem die Schaltfläche "Drucken" als deaktiviert angezeigt wurde, auch wenn Benutzende über die entsprechenden Druckberechtigungen verfügten.</span><span class="sxs-lookup"><span data-stu-id="03067-1495">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

- <span data-ttu-id="03067-1496">Behebung eines Problems, das dazu führte, dass Anhänge aus S/MIME-Nachrichten entfernt wurden, wenn diese unverschlüsselt gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1496">Addressed an issue that caused attachments to get stripped from S/MIME messages when sending as unencrypted.</span></span>

- <span data-ttu-id="03067-1497">Behebung eines Problems, das dazu führte, dass Klartext-S/MIME-Nachrichten beim Senden verstümmelt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1497">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>

- <span data-ttu-id="03067-1498">Behebt ein Problem, durch das Anhänge beschädigt wurden, wenn eine S/MIME-E-Mail unverschlüsselt gesendet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1498">Addressed an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>

- <span data-ttu-id="03067-1499">Es wurde ein Problem behoben, das dazu führt, dass Empfänger geschützte Nachrichten nicht speichern können, selbst wenn der/die Absender/in die Erlaubnis zum Speichern als Datei erteilt hat.</span><span class="sxs-lookup"><span data-stu-id="03067-1499">Addressed an issue that cause recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>

- <span data-ttu-id="03067-1500">Diese Korrektur behebt ein Problem, bei dem Benutzende beim Beantworten einer mit digitalen Rechten verwalteten Nachricht in einem Inspektorfenster keine Signatur hinzufügen konnten, wenn sie keine Eigentümerrechte für die Nachricht hatten, auf die sie antworteten.</span><span class="sxs-lookup"><span data-stu-id="03067-1500">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>

- <span data-ttu-id="03067-1501">Diese Korrektur behebt ein Problem, das dazu führte, dass Outlook Zeilenumbrüche in Abschrifteninhalten nicht richtig anzeigte.</span><span class="sxs-lookup"><span data-stu-id="03067-1501">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

- <span data-ttu-id="03067-1502">Behebt ein Problem, bei dem die Bezeichnungen für einige Optionen für die erweiterte Suche in einigen Sprachen abgeschnitten wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1502">Addressed an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="03067-1503">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1503">PowerPoint</span></span>

- <span data-ttu-id="03067-1504">Ein Problem wurde behoben, bei dem die Kopie eines Bildes mit einer radialen Verlaufsfüllung nicht mit dem Original übereinstimmte.</span><span class="sxs-lookup"><span data-stu-id="03067-1504">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="03067-1505">Ein Problem wurde behoben, bei dem die Schaltfläche „Formulare“ in PowerPoint das Erstellen von Formularen nicht zulässt, wenn der Zugriff auf den Microsoft Store nicht zulässig war.</span><span class="sxs-lookup"><span data-stu-id="03067-1505">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="03067-1506">Project</span><span class="sxs-lookup"><span data-stu-id="03067-1506">Project</span></span>

- <span data-ttu-id="03067-1507">Wir haben ein Problem behoben, bei dem die in der Task Board-Ansicht aufgelisteten Aufgaben nicht mit denen im Dialogfeld "Ressourcen zuordnen" synchronisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1507">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>

- <span data-ttu-id="03067-1508">Wir haben ein Problem behoben, bei dem beim Versuch, ein PDF/XPS aus dem Projekt in eine SharePoint-Dokumentenbibliothek zu speichern, nichts passiert.</span><span class="sxs-lookup"><span data-stu-id="03067-1508">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

- <span data-ttu-id="03067-1509">Wir haben ein Problem behoben, bei dem beim Kopieren und Einfügen einer Aufgabe mit mehreren Abhängigkeiten nicht alle Abhängigkeiten korrekt kopiert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1509">We fixed an issue where if you copied & pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

- <span data-ttu-id="03067-1510">Ein Problem wurde behoben, bei dem für eine SharePoint-Aufgabenliste die Schaltflächen auf dem Menüband auf der zweiten Registerkarte deaktiviert sein können.</span><span class="sxs-lookup"><span data-stu-id="03067-1510">Fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="skype"></a><span data-ttu-id="03067-1511">Skype</span><span class="sxs-lookup"><span data-stu-id="03067-1511">Skype</span></span>

- <span data-ttu-id="03067-1512">Der Hautton des Tanzemoticons wurde auf neutrale Farbe geändert</span><span class="sxs-lookup"><span data-stu-id="03067-1512">Changed dancing emoticon skin tone to neutral color</span></span>

### <a name="visio"></a><span data-ttu-id="03067-1513">Visio</span><span class="sxs-lookup"><span data-stu-id="03067-1513">Visio</span></span>

- <span data-ttu-id="03067-1514">Wenn Benutzende nach dieser Korrektur die Ausführung des Löschbefehls durch einen dazwischen liegenden Mechanismus angehalten haben (in diesem Fall durch ein Add-in), wird der Speicher nicht lecken und die gesamte Maschine wird nicht beeinträchtigt.</span><span class="sxs-lookup"><span data-stu-id="03067-1514">After this fix, if the user halted the execution of delete command by any mechanism in between (in this case it was through add-in) the memory won't leak and the whole machine won't be impacted.</span></span>

### <a name="word"></a><span data-ttu-id="03067-1515">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1515">Word</span></span>

- <span data-ttu-id="03067-1516">Ein Problem wurde behoben, bei dem Word nicht mehr reagierte, nachdem Text und ein Bild in ein Kommentarfeld eingefügt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1516">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>

- <span data-ttu-id="03067-1517">Ein Problem wurde behoben, bei dem die Kopie eines Bildes mit einer radialen Verlaufsfüllung nicht mit dem Original übereinstimmte.</span><span class="sxs-lookup"><span data-stu-id="03067-1517">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="03067-1518">Wir haben ein Problem behoben, bei dem der Platzhaltertext im Bearbeitungsfeld „Suchen“ überlaufen würde, wenn die Größe des Anwendungsfensters auf eine kleine Dimension geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1518">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

- <span data-ttu-id="03067-1519">Ein Problem wurde behoben, bei dem sich das Überarbeitungsfeld unerwartet öffnet, wenn ein Kommentar hinzugefügt wurde, um eine Änderung zu verfolgen.</span><span class="sxs-lookup"><span data-stu-id="03067-1519">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>

- <span data-ttu-id="03067-1520">Wir haben ein Problem behoben, bei dem der Befehl „Editor“ deaktiviert wurde, als sich der Fokus in einem Kommentartextfeld befand.</span><span class="sxs-lookup"><span data-stu-id="03067-1520">We fixed an issue where the Editor command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="03067-1521">Wir haben ein Problem behoben, bei dem der Befehl „Markup anzeigen“ deaktiviert wurde, als sich der Fokus in einem Kommentartextfeld befand.</span><span class="sxs-lookup"><span data-stu-id="03067-1521">We fixed an issue where the Show Markup command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="03067-1522">Ein Problem wurde behoben, bei dem die Schaltfläche „Neuer Kommentar“ nach dem Löschen des letzten Kommentars deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1522">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

- <span data-ttu-id="03067-1523">Wir haben ein Problem behoben, bei dem die Option „Bestimmte Personen“ zum Nachverfolgen von Änderungen deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1523">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>

- <span data-ttu-id="03067-1524">Ein Problem wurde behoben, bei dem Links zu Dokumenten nicht über die Dropdown-Liste Einfügen -> Link in das Kommentarfeld eingefügt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1524">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>

- <span data-ttu-id="03067-1525">Wir haben ein gelegentliches Aufhängen beim Öffnen von HTML-Dateien behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-1525">We fixed an occasional hang while opening HTML files.</span></span>

- <span data-ttu-id="03067-1526">Wir haben ein Problem in benutzerdefiniertem XML behoben, bei dem der Status der Kommentare beim Öffnen des Dokuments verloren geht.</span><span class="sxs-lookup"><span data-stu-id="03067-1526">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

- <span data-ttu-id="03067-1527">Ein Problem wurde behoben, bei dem die Anzahl der Hyperlinks in der VBA-Hyperlinks-Sammlung nach dem Hinzufügen eines Bildes, das einen Hyperlink enthält, nicht korrekt iteriert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1527">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

- <span data-ttu-id="03067-p193">Bei dem alten, nicht webdienstbasierten Bereich „Freigeben“ könnte das Schließen des Dokuments bei geöffnetem Bereich „Freigeben“ zu einem Absturz führen. Dies ist nun behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-p193">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash. This is now fixed.</span></span>

- <span data-ttu-id="03067-1530">Wir haben ein Problem behoben, durch das, nach dem der User ein neues App-Fenster über die Taskleiste geöffnet und ein neues leeres Dokuments erstellt hatte, zusätzliche Dateien erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1530">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>

- <span data-ttu-id="03067-1531">Wir haben ein Problem behoben, bei dem ein Benutzer, der ein Dokument bearbeitete, aber zwischenzeitlich die Berechtigungen verloren hatte, wir den Benutzer nicht darüber informierten, dass er sich erneut authentifizieren musste.</span><span class="sxs-lookup"><span data-stu-id="03067-1531">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2007-august-05"></a><span data-ttu-id="03067-1533">Version 2007: 5. August</span><span class="sxs-lookup"><span data-stu-id="03067-1533">Version 2007: August 05</span></span>
<span data-ttu-id="03067-1534">*Version 2007 (Build 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="03067-1534">*Version 2007 (Build 13029.20344)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)



[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1538">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1538">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1539">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1539">Outlook</span></span>

- <span data-ttu-id="03067-1540">Ein Problem wurde behoben, das dazu führte, dass Outlook keine Suchvorschläge abrufen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1540">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="03067-1541">Ein Problem wurde behoben, das gelegentlich zu einem Absturz führte, wenn Benutzer Persona-Informationen abriefen.</span><span class="sxs-lookup"><span data-stu-id="03067-1541">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="03067-1542">Project</span><span class="sxs-lookup"><span data-stu-id="03067-1542">Project</span></span>

- <span data-ttu-id="03067-1543">Ein Problem wurde behoben, bei dem ein Projekt, das in einen ungültigen Zustand geraten war, nicht geöffnet werden konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1543">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2007-july-29"></a><span data-ttu-id="03067-1545">Version 2007: 29. Juli</span><span class="sxs-lookup"><span data-stu-id="03067-1545">Version 2007: July 29</span></span>
<span data-ttu-id="03067-1546">*Version 2007 (Build 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="03067-1546">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1548">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1548">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-1549">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1549">Excel</span></span>

- <span data-ttu-id="03067-1550">**Abrufen von Organisationsdaten aus Power BI mithilfe von Datentypen:** Excel-Datentypen aus Power BI werden nun für Insider in Organisationen mit Office 365 E5/A5 oder Microsoft 365 E5/A5 bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="03067-1550">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="03067-1551">Benötigte Informationen abrufen und deren einfache Aktualisierung ist für viele tägliche Abläufe von entscheidender Bedeutung.</span><span class="sxs-lookup"><span data-stu-id="03067-1551">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="03067-1552">Sie erhalten Zugriff auf Ihre Unternehmens-oder Organisationsinformationen aus Power BI als Datentyp in Excel. Dadurch wird die Möglichkeit, verknüpfte Informationen in Tabellen einzugben, erweitert. </span><span class="sxs-lookup"><span data-stu-id="03067-1552">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="03067-1553">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1553">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="03067-1554">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="03067-1554">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-1555">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1555">Outlook</span></span>

- <span data-ttu-id="03067-1556">**Auswählen, wo gesucht werden soll:** Das neue Dropdownmenü für den Suchbereich ermöglicht es Ihnen, Ihre Suche einfacher zu ändern und zwischen dem aktuellen Ordner und dem aktuellen Postfach zu wechseln.</span><span class="sxs-lookup"><span data-stu-id="03067-1556">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="03067-1557">Vielen Dank an alle in "Demnächst verfügbar", die uns ihr Feedback zu der neuen Search-at-Top-Erfahrung gesendet haben.</span><span class="sxs-lookup"><span data-stu-id="03067-1557">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="03067-1558">Das vorliegende Design und Update sind aus diesem Feedback entstanden!</span><span class="sxs-lookup"><span data-stu-id="03067-1558">This design and update came out of that feedback!</span></span>

### <a name="word"></a><span data-ttu-id="03067-1559">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1559">Word</span></span>

- <span data-ttu-id="03067-1560">**Bessere Zusammenarbeit mit modernen Kommentaren:** Für eine bessere Zusammenarbeit fügen Sie Kommentare zu Objekten hinzu, @erwähnen Sie Kollegen, und lösen Sie Kommentarthreads auf.</span><span class="sxs-lookup"><span data-stu-id="03067-1560">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="03067-1561">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1561">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1564">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1564">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1565">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1565">Outlook</span></span>

- <span data-ttu-id="03067-1566">Ein Problem wurde behoben, das zu einem Absturz führte, wenn Benutzer von CLP die Absenderadresse in einer Antwort von geschütztem in ungeschützten Kontext wechselten.</span><span class="sxs-lookup"><span data-stu-id="03067-1566">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="03067-1567">Ein Problem wurde behoben, das dazu führte, dass die Seite des Terminplanungs-Assistenten nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1567">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="03067-1568">Ein Problem wurde behoben, das zu Formatierungsproblemen in Benachrichtigungen über einen Sicherheitsvorfälle führte.</span><span class="sxs-lookup"><span data-stu-id="03067-1568">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2007-july-27"></a><span data-ttu-id="03067-1570">Version 2007: 27. Juli</span><span class="sxs-lookup"><span data-stu-id="03067-1570">Version 2007: July 27</span></span>
<span data-ttu-id="03067-1571">*Version 2007 (Build 13029.20292)*</span><span class="sxs-lookup"><span data-stu-id="03067-1571">*Version 2007 (Build 13029.20292)*</span></span>
* <span data-ttu-id="03067-1572">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="03067-1572">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-20"></a><span data-ttu-id="03067-1573">Version 2007: 20. Juli</span><span class="sxs-lookup"><span data-stu-id="03067-1573">Version 2007: July 20</span></span>
<span data-ttu-id="03067-1574">*Version 2007 (Build 13029.20236)*</span><span class="sxs-lookup"><span data-stu-id="03067-1574">*Version 2007 (Build 13029.20236)*</span></span>
* <span data-ttu-id="03067-1575">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="03067-1575">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-15"></a><span data-ttu-id="03067-1576">Version 2007: 15. Juli</span><span class="sxs-lookup"><span data-stu-id="03067-1576">Version 2007: July 15</span></span>
<span data-ttu-id="03067-1577">*Version 2007 (Build 13029.20200)*</span><span class="sxs-lookup"><span data-stu-id="03067-1577">*Version 2007 (Build 13029.20200)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1579">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1579">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-1580">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1580">Excel</span></span>

- <span data-ttu-id="03067-1581">**Erstellen Sie ansprechende Visio-Diagramme in Excel:** Erstellen Sie ein Flussdiagramm oder ein Organigramm durch Einfügen von Daten in ein Arbeitsblatt.</span><span class="sxs-lookup"><span data-stu-id="03067-1581">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="03067-1582">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1582">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1585">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1585">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="03067-1586">Zugriff</span><span class="sxs-lookup"><span data-stu-id="03067-1586">Access</span></span>

- <span data-ttu-id="03067-1587">Ein Problem wurde behoben, bei dem der Tabellenverknüpfungs-Manager einen Primärschlüssel anforderte, wenn eine verknüpfte SQL-Tabelle aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1587">We fixed an issue where the linked table manager would prompt a primary key if a linked SQL table was refreshed.</span></span>

- <span data-ttu-id="03067-1588">Es wurde ein Problem behoben, das dazu führte, dass Abfragen im Abfrage-Editor aus dem sichtbaren Bereich verschwanden.</span><span class="sxs-lookup"><span data-stu-id="03067-1588">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>

- <span data-ttu-id="03067-1589">Ein Problem wurde behoben, bei dem die Abfrageausführung ungefähr doppelt so lange dauerte als erwartet.</span><span class="sxs-lookup"><span data-stu-id="03067-1589">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="03067-1590">Es wurde ein Problem behoben, das dazu führte, dass Microsoft Access eine Identitätsspalte in einer verknüpften SQL Server-Tabelle nicht identifizierte, was dazu führen konnte, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.</span><span class="sxs-lookup"><span data-stu-id="03067-1590">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="03067-1591">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1591">Excel</span></span>

- <span data-ttu-id="03067-1592">Ein Problem wurde behoben, bei dem URLs, die nicht auf HTTP oder HTTPS basierten, nicht in der Liste "Zuletzt verwendet" angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1592">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

- <span data-ttu-id="03067-1593">Ein Problem wurde behoben, bei dem beim Laden einer Arbeitsmappe mit mehreren Blättern in der Seitenumbruchvorschau ein Fehler oder eine Unterbrechung auftreten kann.</span><span class="sxs-lookup"><span data-stu-id="03067-1593">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="03067-1594">Es wurde ein Problem behoben, bei dem Datenmodelltabellen, die in bestimmten Excel-Versionen erstellt wurden, in der "Tabellenvorschau" nicht angezeigt wurden, selbst wenn die mit der Tabelle verknüpfte Abfrage nicht bearbeitet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1594">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>

- <span data-ttu-id="03067-1595">Relativ/Absolut ignorieren"-Bezügen im Dialogfeld "Namen definieren \ Namen anwenden" führte dazu, dass Formeln nicht funktionierten.</span><span class="sxs-lookup"><span data-stu-id="03067-1595">Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>

- <span data-ttu-id="03067-1596">Es wurde ein Problem behoben, bei dem CustomUI XML für eine benutzerdefinierte Menüband-Registerkarte beim Speichern einer Arbeitsmappe in SharePoint/OneDrive entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1596">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="03067-1597">Ein Problem wurde behoben, bei dem Arbeitsmappen schreibgeschützt waren, wenn für die Datei nur die Empfehlung des Schreibschutzes vorlag.</span><span class="sxs-lookup"><span data-stu-id="03067-1597">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

- <span data-ttu-id="03067-1598">Ein Problem wurde behoben, bei dem beim Laden einer Arbeitsmappe mit mehreren Blättern in der Seitenumbruchvorschau ein Fehler oder eine Unterbrechung auftreten kann.</span><span class="sxs-lookup"><span data-stu-id="03067-1598">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="03067-1599">Ein Problem wurde behoben, bei dem die wichtigsten Netzlinien von Netzdiagrammen nicht ordnungsgemäß formatiert werden konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-1599">We fixed an issue where the major gridlines of radar charts could not be formatted correctly.</span></span>


- <span data-ttu-id="03067-1600">Es wurde ein Problem behoben, bei dem durch das Löschen eines erweiterten Datenfilters die Tabellenformatierung verloren gehen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1600">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>


- <span data-ttu-id="03067-1601">Ein Problem wurde behoben, bei dem in der Dokumentbeschriftung der vollständige Pfad eines eingebetteten PDF-Dokuments und nicht nur der Dateiname angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1601">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>


- <span data-ttu-id="03067-1602">Ein Problem wurde behoben, bei dem es nach dem Deaktivieren des Wolfram Cloud-Connectors und dem anschließenden Speichern und erneuten Öffnen einer Excel-Arbeitsmappe zu einem Absturz kommen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1602">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>


- <span data-ttu-id="03067-1603">Es wurde ein Problem behoben, durch das das Starten von Excel mit aktiviertem Solver-Add-in zu einem Absturz führte.</span><span class="sxs-lookup"><span data-stu-id="03067-1603">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>


### <a name="outlook"></a><span data-ttu-id="03067-1604">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1604">Outlook</span></span>

- <span data-ttu-id="03067-1605">Es wurde ein Problem behoben, bei dem Outlook nicht mehr reagierte, wenn mehr als 130 Empfänger in der Zeile "An" vorhanden waren; darüber hinaus wurde auch die Leistung beim Renderns des Texts verbessert.</span><span class="sxs-lookup"><span data-stu-id="03067-1605">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>


- <span data-ttu-id="03067-1606">Es wurde ein Problem behoben, bei dem das IME-Fenster (Eingabemethoden-Editor) den zugrunde liegenden Text, der über den IME eingegeben wird, überlappte, wenn mehrere Monitore mit unterschiedlichen Auflösungen verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1606">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>


- <span data-ttu-id="03067-1607">Es wurde ein Problem in der "Aufgabenleiste" behoben, bei dem für Ereignisse, die mehr als zwei Tage dauerten, für alle nachfolgenden Tage dieselbe Endzeit angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1607">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>


- <span data-ttu-id="03067-1608">Behebt ein Problem, durch das Benutzer das Erstellungsdatum der Anlagen sehen konnten, die Sie per Drag & Drop in Ihr Dateisystem kopiert haben, wobei es auf den 1. Januar 4501 festgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1608">Addresses an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="03067-1609">Ein Problem wurde behoben, bei dem Benutzer nicht in der Lage waren, "Senden als" oder "Senden im Auftrag von" einer Verteilerliste zu senden.</span><span class="sxs-lookup"><span data-stu-id="03067-1609">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>


- <span data-ttu-id="03067-1610">Behebt ein Problem, durch das Stellvertretungen beim Bearbeiten eines vorhandenen Kalendertermins im Kalender eines Managers eine Fehlermeldung erhalten haben.</span><span class="sxs-lookup"><span data-stu-id="03067-1610">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="03067-p198">Es wurde ein Problem behoben, durch das Benutzern beim Schließen eines vorher gespeicherten Termins der folgende Fehler angezeigt wurde: „Das Element kann nicht gespeichert werden, da es von einem anderen Benutzer oder in einem anderen Fenster geändert wurde. Möchten Sie im Standardordner für das Element eine Kopie erstellen?“</span><span class="sxs-lookup"><span data-stu-id="03067-p198">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved "The item cannot be saved because it was changed by another user or in another window. Do you want to make a copy in the default folder for the item?"</span></span>


- <span data-ttu-id="03067-1613">Behebt ein Problem, bei dem die Option "Weiterleitung zulassen" in den "Antwortoptionen" für Kalenderbesprechungen nicht angezeigt wurde, wenn die Option für das Herunterladen freigegebener Ordner NICHT aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="03067-1613">Addresses an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="03067-1614">Behebt ein Problem, das dazu führte, dass Benutzer OneDrive-Anlagen von außerhalb ihres Mandanten nicht auf ihrem lokalen Computer speichern konnten, wenn sie im Dialogfeld "Sicherheit" die Option "Speichern" wählten.</span><span class="sxs-lookup"><span data-stu-id="03067-1614">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="03067-1615">Es wurde ein Problem behoben, das bewirkt hat, dass die Nachrichtenliste von Outlook-Benutzern, nachdem diese freigegebene Kalender verwendet hatten, einige Minuten lang nicht mehr aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1615">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>


- <span data-ttu-id="03067-1616">Wir haben ein Problem behoben, das verhinderte, dass in Kalendererinnerungen genaue Uhrzeiten für Besprechungen in weniger als einer Woche angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1616">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span> 


- <span data-ttu-id="03067-1617">Es wurde ein Problem behoben, das dazu führte, dass wenn ein Bild inline in eine Nachricht eingefügt wurde und die Nachricht dann als Entwurf gespeichert wurde, dies zu einer Größenänderung bei dem Bild führte.</span><span class="sxs-lookup"><span data-stu-id="03067-1617">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>


- <span data-ttu-id="03067-1618">Es wurde ein Problem behoben, das bewirkt hatte, dass der Text einer NDR-Nachricht nach der Bearbeitung des Betreffs von Unicode in ASCII geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1618">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>


- <span data-ttu-id="03067-1619">Ein Problem wurde behoben, durch das die Datumsangaben im Minikalender für Benutzer in Japan nicht fett formatiert angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1619">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="03067-1620">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1620">PowerPoint</span></span>

- <span data-ttu-id="03067-1621">Es wurde ein Problem behoben, bei dem der Farbindikator für Abwesenheiten eines Benutzers während einer aktiven Sitzung zur gemeinsamen Dokumenterstellung nicht im Katalog für die gemeinsame Dokumenterstellung aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1621">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>


- <span data-ttu-id="03067-1622">Es wurde ein Problem behoben, durch das beim Einfügen von HTML in einen Textbereich auf einer Folie dieser stattdessen in ein Textfeld eingefügt wurde, das am oberen Rand der Folie erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1622">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>


- <span data-ttu-id="03067-1623">Ein Problem wurde behoben, bei dem die Auswahl aller Folien in der Referentenansicht, das anschließende Verlassen der Referentenansicht mittels Alt+Tab und die Rückkehr zur Bildschirmpräsentation und das Klicken auf "Präsentation beenden" zu einem Ausnahmefehler führte.</span><span class="sxs-lookup"><span data-stu-id="03067-1623">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>


### <a name="project"></a><span data-ttu-id="03067-1624">Project</span><span class="sxs-lookup"><span data-stu-id="03067-1624">Project</span></span>

- <span data-ttu-id="03067-1625">Es wurde ein Problem behoben, bei dem man kein PDF/XPS aus Project in einer SharePoint-Dokumentbibliothek speichern konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1625">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="03067-1626">Ein Problem wurde behoben, bei dem Projekte aus Project Web App nicht im Project-Desktop Client geöffnet werden konnten, wenn die URL in .com endete.</span><span class="sxs-lookup"><span data-stu-id="03067-1626">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="03067-1627">Ein Problem wurde behoben, bei dem Project beim Öffnen bestimmter XML-Dateien abstürzte.</span><span class="sxs-lookup"><span data-stu-id="03067-1627">We fixed an issue where Project may crash when opening certain XML files.</span></span>


- <span data-ttu-id="03067-1628">Es wurde ein Problem behoben, bei dem Projekte aus Project Web App im Project-Desktopclient nicht geöffnet werden konnten, wenn die URL in ".com" endete.</span><span class="sxs-lookup"><span data-stu-id="03067-1628">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>


- <span data-ttu-id="03067-1629">Es wurde ein Problem behoben, das bewirkt, dass nicht alle Abhängigkeiten korrekt kopiert werden, wenn ein Vorgang mit mehreren Abhängigkeiten eingefügt wird.</span><span class="sxs-lookup"><span data-stu-id="03067-1629">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="03067-1630">Ein Problem wurde behoben, bei dem die im Dialogfeld "Ressourcen zuordnen" ausgewählte Aufgabe nicht mit der in der Ansicht "Task Board" ausgewählten Aufgabe identisch ist.</span><span class="sxs-lookup"><span data-stu-id="03067-1630">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="03067-1631">Es wurde ein Problem behoben, bei dem das Ereignis "ProjectBeforeTaskChange" nicht ausgelöst wurde, wenn eine Änderung am Projektzusammenfassungsvorgang – entweder am Projektstart/Aufgabenfeld – vorgenommen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1631">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>


- <span data-ttu-id="03067-1632">Es wurde ein Problem behoben, dass dazu führte, dass wenn Vorgänge mit fester Dauer zu 100 % abgeschlossen waren, das Ist-Ende aber nicht angegeben war, bei "Vorgang zu % abgeschlossen" weniger als 100 % angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1632">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

- <span data-ttu-id="03067-1633">Es wurde ein Problem behoben, bei dem bei einem Basisplan-Reset oder -Update u. U. Zeitphasen-Kosten-/Arbeitsbudgetressourcen geändert wurden und die Baseline falsche Budgetwerte wiedergab.</span><span class="sxs-lookup"><span data-stu-id="03067-1633">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>


- <span data-ttu-id="03067-1634">Es wurde ein Problem behoben, bei dem Project Planner-Links in Government Community Cloud-Umgebungen deaktiviert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1634">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>


- <span data-ttu-id="03067-1635">Ein Problem wurde behoben, bei dem keine Projektdatei aus einer SharePoint-Dokumentbibliothek geöffnet werden konnte, wenn sich die Bibliothek im modernen Modus befand.</span><span class="sxs-lookup"><span data-stu-id="03067-1635">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>


### <a name="word"></a><span data-ttu-id="03067-1636">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1636">Word</span></span>

- <span data-ttu-id="03067-1637">Ein Problem wurde behoben, bei dem die Möglichkeit, die Formatierung im Kommentarbereich über die Schaltfläche "Formatierung löschen" im Office-Menüband zu deaktivieren, nicht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="03067-1637">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>


- <span data-ttu-id="03067-1638">Es wurde ein Problem behoben, durch das in eine skalierbare Vektorgrafik (Scalable Vector Graphic, SVG) eingefügter Text nach deren Einfügen in eine Word-, Excel- oder PowerPoint-Datei, dem Speichern und Schließen der Datei und erneutem Öffnen der Datei unlesbar war.</span><span class="sxs-lookup"><span data-stu-id="03067-1638">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>


- <span data-ttu-id="03067-1639">Ein Problem wurde behoben, bei dem das Ändern der Größe einer Tabelle bei nicht angezeigtem Lineal dazu führte, dass andere Anwendungen, die im Hintergrund ausgeführt wurden, zu blinken begannen.</span><span class="sxs-lookup"><span data-stu-id="03067-1639">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>


- <span data-ttu-id="03067-1640">Es wurde ein Problem behoben, bei dem im Modus "Gemeinsame Dokumenterstellung" Antworten auf Kommentare manchmal nicht im Kommentarbereich angezeigt wurden, sondern im Bereich "Überprüfungen".</span><span class="sxs-lookup"><span data-stu-id="03067-1640">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>


- <span data-ttu-id="03067-1641">Es wurde ein Problem in der gemeinsamen Dokumenterstellung behoben, bei dem wenn beim Zusammenführen ein Konflikt vorlag und der Benutzer bereits Änderungen verworfen hatte, die Option zum Speichern oder Verwerfen von Änderungen nicht mehr angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1641">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>


- <span data-ttu-id="03067-1642">Ein Problem wurde behoben, bei dem die Farbe von HTML-Links nicht ordnungsgemäß gerendert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1642">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>


- <span data-ttu-id="03067-1643">Es wurde ein Problem behoben, bei dem wenn in Word eine Liste mit mehr als 50 häufig geöffneten Dokumenten vorlag, nach dem Speichern und Öffnen eines Dokuments ein Versionsverlauf angezeigt wurde, selbst wenn keine Änderungen an diesem Dokument vorgenommen wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1643">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>


- <span data-ttu-id="03067-1644">Es wurde ein Problem mit der automatischen Speicherung bei der gemeinsamen Dokumenterstellung behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-1644">We fixed in issue with autosave during coauthoring.</span></span>


- <span data-ttu-id="03067-1645">Es wurde ein Problem behoben, das beim Speichern einer Datei, die ein Makro enthielt, unter einem neuen Namen dazu führte, dass sie mit einer .docx-Erweiterung und dem Dateinamen "WRO0004.docx" gespeichert wurde, und zwar unabhängig davon, was der Benutzer eingegeben hatte, wodurch das Dokument unbrauchbar wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1645">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>


### <a name="office-suite"></a><span data-ttu-id="03067-1646">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-1646">Office Suite</span></span>

- <span data-ttu-id="03067-1647">Ein Timing-Problem konnte beim Schließen von Office-Dateien zu einem Absturz führen</span><span class="sxs-lookup"><span data-stu-id="03067-1647">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="03067-1648">Der Fix für dieses Problem bestand darin, sicherzustellen, dass der Dienst hinzugefügte Produkte ordnungsgemäß berechnet.</span><span class="sxs-lookup"><span data-stu-id="03067-1648">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="03067-1649">Wir haben die neu hinzugefügten Produkte herausgefiltert (dabei wurde sichergestellt, dass sie auch in der neuen Konfiguration vorhanden sind) und sie am Ende der vorhandenen Produkt-Release-IDs hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="03067-1649">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-july-09"></a><span data-ttu-id="03067-1651">Version 2006: 09. Juli</span><span class="sxs-lookup"><span data-stu-id="03067-1651">Version 2006: July 09</span></span>
<span data-ttu-id="03067-1652">*Version 2006 (Build 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="03067-1652">*Version 2006 (Build 13001.20384)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1654">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1654">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-1655">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1655">Excel</span></span>

- <span data-ttu-id="03067-1656">**Eine PDF-Verbindung herstellen:** Herstellen einer Verbindung zu, Importieren und Aktualisieren von Daten aus einer PDF-Datei.</span><span class="sxs-lookup"><span data-stu-id="03067-1656">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="03067-1657">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1657">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="03067-1658">**Erstellen von Variablen zur Verwendung in Formeln:** Verbessern Sie Leistung, Lesbarkeit und Zusammensetzbarkeit mit der LET-Funktion.</span><span class="sxs-lookup"><span data-stu-id="03067-1658">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="03067-1659">Mit dieser Funktion können Sie benannte Variablen in neuen oder bereits vorhandenen Formeln erstellen.</span><span class="sxs-lookup"><span data-stu-id="03067-1659">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="03067-1660">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1660">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="03067-1661">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/).</span><span class="sxs-lookup"><span data-stu-id="03067-1661">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="03067-1662">**Tastenkombinationen in Excel:** Aktualisierte Tastenkombinationen für Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1662">**Keyboard shortcuts in Excel:** Updated keyboard shortcuts for Excel</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-1663">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1663">Outlook</span></span>

- <span data-ttu-id="03067-1664">**Erstellen von Umfragen in Outlook mit Quick Poll**: Einfaches Erstellen einer Umfrage, Sammeln von Stimmen und Anzeigen der Ergebnisse in einer E-Mail [Weitere Informationen](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="03067-1664">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="03067-1665">**Bewahren Sie die Klangtreue Ihrer Bilder, wenn Sie diese als Teil einer E-Mail versenden:** Eine neue Outlook-Einstellung ist verfügbar, um die Bildkomprimierung zu begrenzen, wenn Sie Bilder als Teil des E-Mail-Inhalts versenden.</span><span class="sxs-lookup"><span data-stu-id="03067-1665">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1668">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1668">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="03067-1669">Access</span><span class="sxs-lookup"><span data-stu-id="03067-1669">Access</span></span>

- <span data-ttu-id="03067-1670">Dieses Problem wurde behoben, und Sie sollten erwarten, dass Sie verknüpfte SQL-Tabellen, die ein Identitätsfeld (z. B. Autonummer) enthalten, erfolgreich in Access einfügen können.</span><span class="sxs-lookup"><span data-stu-id="03067-1670">This issue is resolved, and you should expect to be able to successfully insert linked SQL tables that include an identity (e.g. autonumber) field into Access.</span></span>

### <a name="excel"></a><span data-ttu-id="03067-1671">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1671">Excel</span></span>

- <span data-ttu-id="03067-1672">Ein Absturz wurde behoben, der beim Versuch, eine Datenverbindung herzustellen, auftreten konnte, wenn Sie sich von Ihrem Konto abgemeldet haben.</span><span class="sxs-lookup"><span data-stu-id="03067-1672">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-1673">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1673">Outlook</span></span>

- <span data-ttu-id="03067-1674">Ein Problem wurde behoben, das dazu führte, dass Benutzer OneDrive-Anlagen von außerhalb ihres Mandanten nicht auf ihrem lokalen Computer speichern konnten, wenn sie im Dialogfeld "Sicherheit" die Option "Speichern" wählten.</span><span class="sxs-lookup"><span data-stu-id="03067-1674">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="03067-1675">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-1675">Office Suite</span></span>

- <span data-ttu-id="03067-1676">Ein neuer Sturz von AppV51 wurde zurückportiert, um eine Regression im vorherigen AppV51 zu beheben.</span><span class="sxs-lookup"><span data-stu-id="03067-1676">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="03067-1677">Der Office-Host stürzte in Fenstern ab, wenn ein Add-In aktiviert wird, während der Registrierungswert TabProcGrowth vom Typ REG_SZ und mit dem Wert "0" ist.</span><span class="sxs-lookup"><span data-stu-id="03067-1677">he office host was crashing in windows, when an add-in is being activated while the registry TabProcGrowth value is REG_SZ type and with value "0".</span></span>  <span data-ttu-id="03067-1678">Der Registrierungswert TabProcGrowth kann unter einem von 4 Pfaden stehen: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span><span class="sxs-lookup"><span data-stu-id="03067-1678">That registry TabProcGrowth value can be under any one of 4 paths: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-june-25"></a><span data-ttu-id="03067-1680">Version 2006: 25. Juni</span><span class="sxs-lookup"><span data-stu-id="03067-1680">Version 2006: June 25</span></span>
<span data-ttu-id="03067-1681">*Version 2006 (Build 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="03067-1681">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1683">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1683">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="03067-1684">Visio</span><span class="sxs-lookup"><span data-stu-id="03067-1684">Visio</span></span>

- <span data-ttu-id="03067-1685">**Erstellen Sie ansprechende Visio-Diagramme in Excel:** Erstellen Sie ein Flussdiagramm oder ein Organigramm auf der Grundlage von Daten in einem Arbeitsblatt.</span><span class="sxs-lookup"><span data-stu-id="03067-1685">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart based on data in a worksheet.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1688">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1688">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="03067-1689">Access</span><span class="sxs-lookup"><span data-stu-id="03067-1689">Access</span></span>

- <span data-ttu-id="03067-p203">Dieses Problem ist nun behoben. Bitte teilen Sie dem Team mit, wenn Sie weitere Probleme mit diesem Prozess haben.</span><span class="sxs-lookup"><span data-stu-id="03067-p203">This problem is now resolved. Please let the team know if you experience more issues with this process.</span></span>


### <a name="outlook"></a><span data-ttu-id="03067-1692">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1692">Outlook</span></span>

- <span data-ttu-id="03067-1693"><span style="display:inline !important;">Behebt ein Problem, das dazu führte, dass Benutzer<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">das Erstellungsdatum von&nbsp; Anlagen sahen, die sie per Drag & Drop in ihr Dateisystem kopierten, wobei&nbsp; auf den 1. Januar 4501 gesetzt wurde.</span></span><span class="sxs-lookup"><span data-stu-id="03067-1693"><span style="display:inline !important;">Addresses an issue that caused users to see<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">the creation date of&nbsp; attachments that they copied to their file system via drag and drop getting&nbsp; set to January 1, 4501.</span></span></span><br>


- <span data-ttu-id="03067-1694"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Behebt ein Problem, das dazu führte, dass Benutzer von Verbesserungen am "Freigegebenen Kalender" Kalenderfehler sahen.</span></span><span class="sxs-lookup"><span data-stu-id="03067-1694"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span></span><br>


- <span data-ttu-id="03067-1695"><span style="display:inline !important;">Behebt ein Problem, das dazu führte, dass Benutzer ständig von Outlook aufgefordert wurden, das Reparaturtool für den Posteingang auszuführen.</span></span><span class="sxs-lookup"><span data-stu-id="03067-1695"><span style="display:inline !important;">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span></span><br>


- <span data-ttu-id="03067-1696"><span style="display:inline !important;">Behebt ein Problem, das dazu führte, dass bei der Suche nach einem Feature in "Features vorschlagen" keine Ergebnisse zurückgegeben wurden und der Benutzer keine Möglichkeit hatte, eine neue Idee für Features einzureichen.</span></span><span class="sxs-lookup"><span data-stu-id="03067-1696"><span style="display:inline !important;">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span></span><br>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-june-18"></a><span data-ttu-id="03067-1698">Version 2006: 18. Juni</span><span class="sxs-lookup"><span data-stu-id="03067-1698">Version 2006: June 18</span></span>
<span data-ttu-id="03067-1699">*Version 2006 (Build 13001.20198)*</span><span class="sxs-lookup"><span data-stu-id="03067-1699">*Version 2006 (Build 13001.20198)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1701">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1701">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-1702">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1702">Excel</span></span>



- <span data-ttu-id="03067-1703">**In angeheftete Ordner speichern:** Durch das Anheften Ihrer Ordner wird das Speichern von Office-Dateien einfacher. Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die verfügbaren Ordner wünschen, wenn eine neue Datei gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="03067-1703">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="03067-1704">Wir freuen uns, Ihnen eine neue Funktion zur Verfügung stellen zu können: anheften Ihrer Ordner im Dialogfeld "Speichern".</span><span class="sxs-lookup"><span data-stu-id="03067-1704">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="03067-1705">Mit dieser neuen Funktion können Sie Ihre Word-, Excel- und PowerPoint-Dateien einfacher speichern.</span><span class="sxs-lookup"><span data-stu-id="03067-1705">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="03067-1706">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="03067-1706">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="03067-1707">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1707">PowerPoint</span></span>

- <span data-ttu-id="03067-1708">**In angeheftete Ordner speichern:** Durch das Anheften Ihrer Ordner wird das Speichern von Office-Dateien einfacher. Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die verfügbaren Ordner wünschen, wenn eine neue Datei gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="03067-1708">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="03067-1709">Wir freuen uns, Ihnen eine neue Funktion zur Verfügung stellen zu können: anheften Ihrer Ordner im Dialogfeld "Speichern".</span><span class="sxs-lookup"><span data-stu-id="03067-1709">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="03067-1710">Mit dieser neuen Funktion können Sie Ihre Word-, Excel- und PowerPoint-Dateien einfacher speichern.</span><span class="sxs-lookup"><span data-stu-id="03067-1710">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="03067-1711">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="03067-1711">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="03067-1712">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1712">Word</span></span>

- <span data-ttu-id="03067-1713">**In angeheftete Ordner speichern:** Durch das Anheften Ihrer Ordner wird das Speichern von Office-Dateien einfacher. Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die verfügbaren Ordner wünschen, wenn eine neue Datei gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="03067-1713">**Save to Pinned Folders:** Pin your folders makes saving Office files easierWe received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="03067-1714">Wir freuen uns, Ihnen eine neue Funktion zur Verfügung stellen zu können: anheften Ihrer Ordner im Dialogfeld "Speichern".</span><span class="sxs-lookup"><span data-stu-id="03067-1714">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="03067-1715">Mit dieser neuen Funktion können Sie Ihre Word-, Excel- und PowerPoint-Dateien einfacher speichern.</span><span class="sxs-lookup"><span data-stu-id="03067-1715">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="03067-1716">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="03067-1716">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1719">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1719">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-1720">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1720">Excel</span></span>

- <span data-ttu-id="03067-1721">Es wurde ein Problem behoben, das dazu führte, dass CustomUI XML für eine benutzerdefinierte Multifunktionsleisten-Registerkarte beim Speichern in SharePoint/OneDrive entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1721">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-1722">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1722">Outlook</span></span>

- <span data-ttu-id="03067-1723">Es wurde ein Problem behoben, das dazu führte, dass STRG+Klicken nicht mehr funktionierte, wenn die Cloud-Einstellungen aktiviert waren.</span><span class="sxs-lookup"><span data-stu-id="03067-1723">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

### <a name="project"></a><span data-ttu-id="03067-1724">Project</span><span class="sxs-lookup"><span data-stu-id="03067-1724">Project</span></span>

- <span data-ttu-id="03067-1725">Es wurde ein Problem behoben, bei dem eine Aufgabe, die als 100 % abgeschlossen gekennzeichnet ist, fälschlicherweise weniger als 100 % abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="03067-1725">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-june-11"></a><span data-ttu-id="03067-1727">Version 2006: 11. Juni</span><span class="sxs-lookup"><span data-stu-id="03067-1727">Version 2006: June 11</span></span>
<span data-ttu-id="03067-1728">*Version 2006 (Build 13001.20144)*</span><span class="sxs-lookup"><span data-stu-id="03067-1728">*Version 2006 (Build 13001.20144)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1730">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1730">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="03067-1731">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1731">PowerPoint</span></span>

- <span data-ttu-id="03067-1732">**Verbesserte Stream-Video-Leistung in PowerPoint:** Wir haben die Wiedergabeleistung von Microsoft Stream-Videos verbessert, um die Ladezeit von Videos zu minimieren und eine reibungslose Wiedergabe zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="03067-1732">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="03067-1733">Verwenden Sie Ihre Unternehmensvideos aus Microsoft Stream, um bessere Präsentationen zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="03067-1733">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="03067-1734">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1734">Word</span></span>

- <span data-ttu-id="03067-1735">**Beibehalten von Text in Vektoren:** Sie können jetzt den Text in Karten, Diagrammen und anderen SVG-Vektoren beibehalten, wenn Sie diese Objekte in Excel, Word und PowerPoint konvertieren.</span><span class="sxs-lookup"><span data-stu-id="03067-1735">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1738">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1738">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-1739">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1739">Excel</span></span>

- <span data-ttu-id="03067-1740">Es wurde ein Problem behoben, bei dem Excel gelegentlich beim Einschalten von OneDrive heruntergefahren wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1740">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>

- <span data-ttu-id="03067-1741">Es wurde ein Problem behoben, bei dem benutzerdefinierte Werte auf der Diagrammachse nicht korrekt angewendet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1741">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>

- <span data-ttu-id="03067-1742">Es wurde ein Problem behoben, bei dem Arbeitsblätter, die mehrere Formeln mit definierten Namen enthielten, zu längeren Zeiten beim Speichern von Dateien geführt haben.</span><span class="sxs-lookup"><span data-stu-id="03067-1742">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="03067-1743">Es wurde ein Problem behoben, das dazu führte, dass Druckernamen in der Liste der verfügbaren Drucker dupliziert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1743">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span>

- <span data-ttu-id="03067-1744">Es wurde ein Problem behoben, das zur Verbesserung der Leistung führte, wenn zusammengeführte Spalten gelöscht wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1744">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>

- <span data-ttu-id="03067-1745">Es wurde ein Problem behoben, bei dem die Fehlermeldung "Diese Arbeitsmappe wird derzeit von einer anderen Arbeitsmappe referenziert und kann nicht geschlossen werden" erschien, weil Add-Ins in alphabetischer Reihenfolge und nicht in einer vom Benutzer festgelegten Reihenfolge geladen wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1745">We fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="03067-1746">Es wurde ein Problem behoben, bei dem der Speicher bei der Verwaltung von Schriftarten zwischen Excel und einigen Hilfstechnologie-Anwendungen von Drittanbietern beschädigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1746">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>

- <span data-ttu-id="03067-1747">Es wurde ein Problem behoben, bei dem das Klicken auf einer mit einem Lesezeichen versehenen Verknüpfung innerhalb derselben Arbeitsmappe dazu führte, dass die Arbeitsmappe ausgeblendet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1747">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="03067-1748">Es wurde ein Problem behoben, bei dem einige kopierte und eingefügte Diagrammverknüpfungen zugeordnete Laufwerksadressen anstelle von Universaladressen verwendeten.</span><span class="sxs-lookup"><span data-stu-id="03067-1748">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="03067-1749">Es wurde ein Problem behoben, bei dem Excel nicht mehr reagierte, nachdem STRG+UMSCHALT+Pfeiltasten zum Scrollen verwendet wurden, wenn das Excel-Fenster von Teams gemeinsam genutzt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1749">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

- <span data-ttu-id="03067-1750">Es wurde ein Problem behoben, bei dem Excel abstürzte, wenn Add-Ins auf Arbeitsblättern, die Shapes mit „noSelect“-Sperren enthalten, nach „Hostelemente“ fragen.</span><span class="sxs-lookup"><span data-stu-id="03067-1750">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="03067-1751">Es wurde ein Problem behoben, bei dem Excel abstürzen kann, wenn versucht wird, PivotTables in ein Diagrammblatt einzufügen.</span><span class="sxs-lookup"><span data-stu-id="03067-1751">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-1752">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1752">Outlook</span></span>

- <span data-ttu-id="03067-1753">Es wurde ein Problem behoben, bei dem das IME-Fenster (Eingabemethoden-Editor) den zugrunde liegenden Text, der über den IME eingegeben wird, überlappte, wenn mehrere Monitore mit unterschiedlichen Auflösungen verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1753">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="03067-1754">Es wurde ein Problem behoben, bei dem die Anzeige einer Vorlage beim Verfassen einer neuen E-Mail-Nachricht zu einem Absturz führen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1754">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>

- <span data-ttu-id="03067-1755">Es wurde ein Problem behoben, bei dem Benutzer nach der Outlook-Version 1911 nicht in der Lage waren, öffentliche Ordner von Exchange 2010 zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="03067-1755">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>

- <span data-ttu-id="03067-1756">Es wurde ein Problem behoben, bei dem die Schaltfläche "Kategorisieren" für Gruppenkalender im Office-Menüband deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1756">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="03067-1757">Es wurde ein Problem behoben, bei dem Outlook die Datenschutzrichtlinie nicht aktiviert hat, um Tipps für Benutzer zu geben, die für den Dienst bezahlt haben und M365 Business Plus-Pläne nutzen.</span><span class="sxs-lookup"><span data-stu-id="03067-1757">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="03067-1758">Ein Problem wurde behoben, das dazu geführt hat, dass Outlook bei einigen Windows-Versionen abstürzt.</span><span class="sxs-lookup"><span data-stu-id="03067-1758">Addressed an issue that caused Outlook to crash on some Windows builds.</span></span>

- <span data-ttu-id="03067-1759">Es wurde ein Problem behoben, bei dem Benutzer nicht in der Lage waren, einen Kalender für einen Gastbenutzer freizugeben.</span><span class="sxs-lookup"><span data-stu-id="03067-1759">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

- <span data-ttu-id="03067-1760">Es wurde ein Problem behoben, bei dem Benutzer Kalendereinträge, welche die Mitternachtsschwelle überstiegen, als Ganztagesereignisse sahen.</span><span class="sxs-lookup"><span data-stu-id="03067-1760">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>

- <span data-ttu-id="03067-1761">Es wurde ein Problem behoben, das dazu führte, dass die Dropdown-Liste "Online-Archiv" in den Ordnereigenschaften für Benutzer mit hohem DPI-Wert nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1761">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>

- <span data-ttu-id="03067-1762">Es wurde ein Problem behoben, bei dem das Ereignis "Folder.BeforeItemMove" nicht korrekt ausgelöst wurde, wenn ein Benutzer Elemente zwischen Ordnern verschoben hat.</span><span class="sxs-lookup"><span data-stu-id="03067-1762">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>

- <span data-ttu-id="03067-1763">Es wurde ein Problem behoben, bei dem Outlook abstürzte, wenn zwei Add-Ins eine Schaltfläche zur gleichen Gruppe im Menüband hinzufügten.</span><span class="sxs-lookup"><span data-stu-id="03067-1763">We fixed an issue where Outlook crashed when two add-ins added a button to the same group in the ribbon.</span></span>

- <span data-ttu-id="03067-1764">Es wurde ein Problem behoben, das zu einem Absturz in Outlook führte, wenn Benutzer mit Verknüpfungen in E-Mails im Format "Nur Text" arbeiteten.</span><span class="sxs-lookup"><span data-stu-id="03067-1764">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>

- <span data-ttu-id="03067-1765">Es wurde ein Problem behoben, das dazu führte, dass Outlook lange Dateinamen, die mit RFC2231 kodiert sind, nicht analysieren konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1765">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>

- <span data-ttu-id="03067-1766">Es wurde ein Problem behoben, das bei Outlook-Benutzern bei der Verwendung von Sprachausgaben zu zeitweiligen Aussetzern führte.</span><span class="sxs-lookup"><span data-stu-id="03067-1766">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

- <span data-ttu-id="03067-1767">Es wurde ein Problem behoben, das bei Benutzern mit widersprüchlichen Kontakten zu Abstürzen in Outlook führen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1767">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="03067-1768">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1768">PowerPoint</span></span>

- <span data-ttu-id="03067-1769">Es wurde ein Problem beim Öffnen von Server-konfigurierten Dateien mit formularbasierter Authentifizierung behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-1769">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>

- <span data-ttu-id="03067-1770">Es wurde ein Problem behoben, bei dem PowerPoint-Dateien mit eingebetteten Diagrammen/Arbeitsmappen zu Fehlern beim Speichern der Datei führen konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-1770">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>

- <span data-ttu-id="03067-1771">Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.</span><span class="sxs-lookup"><span data-stu-id="03067-1771">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="03067-1772">Es wurde ein Problem behoben, bei dem die Folien nach dem Zoomen mit dem Mausrad nicht zentriert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1772">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

- <span data-ttu-id="03067-1773">Ein Problem wurde behoben, bei dem Tastenkombinationen und die Rechtschreibprüfung bei Verwendung einer Schweizer Englisch-Tastatur (QWERTZ) nicht erwartungsgemäß funktionierten.</span><span class="sxs-lookup"><span data-stu-id="03067-1773">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

- <span data-ttu-id="03067-1774">Es wurde ein Problem behoben, bei dem ein Bereich "Kommentar", der vom Benutzer geschlossen wurde, automatisch wieder geöffnet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1774">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>

- <span data-ttu-id="03067-1775">Es wurde ein Problem behoben, bei dem der Folieneditor von einer Folie die nächste überlappte.</span><span class="sxs-lookup"><span data-stu-id="03067-1775">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="03067-1776">Project</span><span class="sxs-lookup"><span data-stu-id="03067-1776">Project</span></span>

- <span data-ttu-id="03067-1777">Es wurde ein Problem behoben, bei dem das Ereignis "ProjectBeforeTaskChange" nicht ausgelöst wurde, wenn eine Änderung am Projektzusammenfassungsvorgang – entweder am Projektstart/Aufgabenfeld – vorgenommen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1777">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="03067-1778">Es wurde ein Problem behoben, bei dem eine Aufgabe, die als 100 % abgeschlossen gekennzeichnet ist, fälschlicherweise weniger als 100 % abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="03067-1778">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="03067-1779">Es wurde ein Problem behoben, bei dem "Project" nach dem Klicken auf "Optionen" abstürzte.</span><span class="sxs-lookup"><span data-stu-id="03067-1779">We fixed an issue where Project would crash after clicking on Options.</span></span>

- <span data-ttu-id="03067-1780">Es wurde ein Problem behoben, das verhinderte, dass verwaiste Aufgaben gelöscht oder neu zugewiesen werden konnten, nachdem ihr übergeordneter Plan gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1780">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="visio"></a><span data-ttu-id="03067-1781">Visio</span><span class="sxs-lookup"><span data-stu-id="03067-1781">Visio</span></span>

- <span data-ttu-id="03067-1782">Es gab eine Regression im abhängigen Code, die behoben wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1782">There was regression in dependent code which has been fixed.</span></span> <span data-ttu-id="03067-1783">Jetzt werden die Bilder in Visio-Diensten, die auf SharePoint Onprem ausgeführt werden, gerendert.</span><span class="sxs-lookup"><span data-stu-id="03067-1783">Now, the images are getting rendered in Visio services running on SharePoint Onprem.</span></span>

### <a name="word"></a><span data-ttu-id="03067-1784">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1784">Word</span></span>

- <span data-ttu-id="03067-1785">Es wurde ein Problem behoben, bei dem die Zeitstempel in den Bereichen "Kommentar" nicht auf der Systemgebietszeit basierten.</span><span class="sxs-lookup"><span data-stu-id="03067-1785">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>

- <span data-ttu-id="03067-1786">Es wurde ein Problem beim Öffnen von Word-Dokumenten aus der benutzerdefinierten Dokumentbereitstellung (aspx) behoben, wenn die URL eine Abfragekomponente enthält.</span><span class="sxs-lookup"><span data-stu-id="03067-1786">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="03067-1787">Es wurde ein Problem behoben, bei dem das Kopieren und Einfügen von Text in einem Kommentarbereich nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1787">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>

- <span data-ttu-id="03067-1788">Es wurde ein Problem behoben, bei dem Verknüpfungen in Kommentaren nicht funktionierten.</span><span class="sxs-lookup"><span data-stu-id="03067-1788">We fixed an issue where hyperlinks in comments weren’t working.</span></span>

- <span data-ttu-id="03067-1789">Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.</span><span class="sxs-lookup"><span data-stu-id="03067-1789">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="03067-1790">Wir haben ein Problem behoben, bei dem die Kommentare zwischen der Webanwendung und der Desktopanwendung nicht synchronisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1790">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

- <span data-ttu-id="03067-1791">Es wurde ein Problem behoben, bei dem Kommentar-Hinweisblasen bei einer Vergrößerung von 100 % verschwommen erschienen.</span><span class="sxs-lookup"><span data-stu-id="03067-1791">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>

- <span data-ttu-id="03067-1792">Es wurde ein Problem behoben, bei dem beim Hinzufügen eines neuen Kommentars zu einem leeren Dokument nichts geschah.</span><span class="sxs-lookup"><span data-stu-id="03067-1792">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>

- <span data-ttu-id="03067-1793">Es wurde ein Problem behoben, bei dem das Einfügen von HTML in WordMail für Kalender nicht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="03067-1793">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>

- <span data-ttu-id="03067-1794">Es wurde ein Problem behoben, bei dem die Beantwortung eines Kommentars in einer gemeinsam verfassten Sitzung manchmal zum Einfrieren von Word führen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1794">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

- <span data-ttu-id="03067-1795">Es wurde ein Problem behoben, bei dem das Einfügen oder Aktualisieren eines Indexes in einem Dokument mit mehr als hundert Einträgen zum Absturz der Anwendung führte.</span><span class="sxs-lookup"><span data-stu-id="03067-1795">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>

- <span data-ttu-id="03067-1796">Es wurde ein Problem behoben, bei dem die Aktivierung der Richtlinie Word 2007 und höher Binärdokumente und -vorlagen dazu führen würde, dass einige Fälle bei der gemeinsamen Dokumentenerstellung fehlschlugen.</span><span class="sxs-lookup"><span data-stu-id="03067-1796">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>

- <span data-ttu-id="03067-1797">Es wurde ein Problem behoben, durch das Dateien mit benutzerdefinierten XML-Werten extrem langsam geöffnet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1797">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

- <span data-ttu-id="03067-1798">Es wurde ein Problem behoben, bei dem Dateien mit langen Pfadnamen (größer als 32 KB) nicht geöffnet werden konnten und eine entsprechende Fehlermeldung nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1798">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="03067-1799">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-1799">Office Suite</span></span>

- <span data-ttu-id="03067-1800">Wir haben das Problem untersucht und behoben, bei dem die Bereitstellung von Office 365 ProPlus über InTune nach einem Herunterfahren des Betriebssystems pausiert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1800">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

- <span data-ttu-id="03067-1801">Es wurde ein Problem in Visual Basic for Applications in Microsoft Office behoben, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthielten, von der Office-Anwendung beim Laden als fehlerhaft angesehen wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1801">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="03067-1802">Das Update behebt ein Problem in Microsoft Office, bei dem Visual Basic for Applications-Projekte mit Referenzen, die bei der Suche nach in der PATH-Umgebungsvariable angegebenen Speicherorten gefunden werden sollen, zur Laufzeit möglicherweise nicht richtig gefunden werden, was zu VBA-Laufzeitfehlern führt.</span><span class="sxs-lookup"><span data-stu-id="03067-1802">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-june-08"></a><span data-ttu-id="03067-1804">Version 2005: 08. Juni</span><span class="sxs-lookup"><span data-stu-id="03067-1804">Version 2005: June 08</span></span>
<span data-ttu-id="03067-1805">*Version 2005 (Build 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="03067-1805">*Version 2005 (Build 12827.20336)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1807">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1807">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="03067-1808">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1808">PowerPoint</span></span>

- <span data-ttu-id="03067-1809">Es wurde ein Problem mit dem Dialog zum Ersetzen von Schriftarten behoben, bei dem die Dropdown-Liste zum Ersetzen von Schriftarten nur Schriftarten innerhalb der Präsentation anzeigt, statt der auf dem System installierten Schriftarten.</span><span class="sxs-lookup"><span data-stu-id="03067-1809">We have fixed an issue with replace fonts dialog where replace font dropdown only shows fonts within the presentation instead of fonts installed on the system.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-june-04"></a><span data-ttu-id="03067-1811">Version 2005: 04. Juni</span><span class="sxs-lookup"><span data-stu-id="03067-1811">Version 2005: June 04</span></span>
<span data-ttu-id="03067-1812">*Version 2005 (Build 12827.20320)*</span><span class="sxs-lookup"><span data-stu-id="03067-1812">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1814">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1814">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="03067-1815">Access</span><span class="sxs-lookup"><span data-stu-id="03067-1815">Access</span></span>

- <span data-ttu-id="03067-1816">**Bleiben Sie am Puls der Zeit! Der Datentyp "Datum/Uhrzeit Erweitert" hat eine bessere Genauigkeit:** Einführung eines neuen und verbesserten Datentyps.</span><span class="sxs-lookup"><span data-stu-id="03067-1816">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="03067-1817">Zur Verbesserung der Syntaxkompatibilität mit SQL und zur Erhöhung der Genauigkeit und des Detaillierungsgrads von Datensätzen, die Datum und Uhrzeit enthalten, implementieren wir den Datentyp "DateTime2" in Access.</span><span class="sxs-lookup"><span data-stu-id="03067-1817">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="03067-1818">Dieser zusätzliche Datentyp für Datum und Uhrzeit umfasst einen größeren Datumsbereich (0001-01-01 bis 9999-12-31) mit einer höher spezifizierten Zeitgenauigkeit (Nanosekunden statt Sekunden), die Sie bereitstellen und Berechnungen durchführen können.</span><span class="sxs-lookup"><span data-stu-id="03067-1818">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="03067-1819">Zum Aktivieren wählen Sie Neues Feld > Datum und Uhrzeit Erweitert.</span><span class="sxs-lookup"><span data-stu-id="03067-1819">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="03067-1820">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1820">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="03067-1821">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1821">Excel</span></span>

- <span data-ttu-id="03067-1822">**Erstellen von PivotTables aus Datasets in Power BI in Excel:** Sie können mit wenigen Klicks PivotTables in Excel erstellen, die mit in Power BI gespeicherten Datensätzen verbunden sind.</span><span class="sxs-lookup"><span data-stu-id="03067-1822">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="03067-1823"> Auf diese Weise können Sie sowohl PivotTables als auch Power BI optimal nutzen.</span><span class="sxs-lookup"><span data-stu-id="03067-1823">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="03067-1824">Berechnen, zusammenfassen und analysieren Sie Ihre Daten mit PivotTables aus Ihren sicheren Power BI-Datensätzen.</span><span class="sxs-lookup"><span data-stu-id="03067-1824">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-1825">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1825">Outlook</span></span>

- <span data-ttu-id="03067-1826">**Option zum schnellen Wiederöffnen von Elementen aus der vorherigen Outlook-Sitzung:** Wir haben eine Option zum schnellen Wiederöffnen von Elementen aus einer vorherigen Outlook-Sitzung hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="03067-1826">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1829">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1829">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="03067-1830">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1830">PowerPoint</span></span>

- <span data-ttu-id="03067-1831">Dies behebt einen Absturz, wenn Benutzer sowohl moderne als auch ältere Kommentare in einer Datei haben, wodurch ein Upgrade der Kommentare ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="03067-1831">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="03067-1832">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-1832">Office Suite</span></span>

- <span data-ttu-id="03067-1833">Es wurde das Problem der Fehlerrate von „ValidateInstall“ behoben, indem die Bing-Add-On-Installationsvalidierung standardmäßig auf „wahr“ gesetzt und die erfolgreiche Ausführung von MSI als erfolgreiche Installation betrachtet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1833">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-may-29"></a><span data-ttu-id="03067-1835">Version 2005: 29. Mai</span><span class="sxs-lookup"><span data-stu-id="03067-1835">Version 2005: May 29</span></span>
<span data-ttu-id="03067-1836">*Version 2005 (Build 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="03067-1836">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1838">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1838">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="03067-1839">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1839">Excel</span></span>

- <span data-ttu-id="03067-1840">**Tabellendarstellung:** Sortieren/Filtern während der Zusammenarbeit mit anderen in der Excel-Desktopumgebung.</span><span class="sxs-lookup"><span data-stu-id="03067-1840">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-1841">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1841">Outlook</span></span>

- <span data-ttu-id="03067-1842">**Zusätzliche Schaltflächen zu Outlook-Toastbenachrichtigungen hinzugefügt:** In Outlook-Toastbenachrichtigungen werden nun Schaltflächen für schnelle Aktionen angezeigt, wenn Outlook unter Windows 10 ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="03067-1842">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1845">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1845">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="03067-1846">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1846">Outlook</span></span>

- <span data-ttu-id="03067-1847">Es wurde ein Problem behoben, das dazu führte, dass Benutzer von Windows 10-Serverversionen die Warnung "Antivirenstatus: Ungültig" gesehen haben.</span><span class="sxs-lookup"><span data-stu-id="03067-1847">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="03067-1848">Diese Version von Windows unterstützt die Erkennung von Antivirus, aber es wurde kein Antivirus gefunden, obwohl Antivirus korrekt installiert war.</span><span class="sxs-lookup"><span data-stu-id="03067-1848">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="03067-1849">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-1849">Office Suite</span></span>

- <span data-ttu-id="03067-p212">Der Office-Host stürzte in Windows ab, wenn ein Add-In aktiviert wird, während der Registrierungsschlüssel HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth auf Null gesetzt ist. Diese Änderung würde das Problem beheben.</span><span class="sxs-lookup"><span data-stu-id="03067-p212">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero. This change would fix this issue.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-may-21"></a><span data-ttu-id="03067-1853">Version 2005: 21. Mai</span><span class="sxs-lookup"><span data-stu-id="03067-1853">Version 2005: May 21</span></span>
<span data-ttu-id="03067-1854">*Version 2005 (Build 12827.20210)*</span><span class="sxs-lookup"><span data-stu-id="03067-1854">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)




[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1858">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1858">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-1859">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1859">Excel</span></span>

- <span data-ttu-id="03067-1860">Es wurde ein Problem behoben, bei dem Excel u. U. nicht mehr reagierte, nachdem STRG+UMSCHALT+Pfeiltasten zum Scrollen verwendet wurden, wenn das Excel-Fenster über Microsoft Teams gemeinsam genutzt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1860">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="03067-1861">In einigen Fällen führt das Anklicken einer Verknüpfung zu einem Ort innerhalb derselben Arbeitsmappe dazu, dass die Arbeitsmappe ausgeblendet wird.</span><span class="sxs-lookup"><span data-stu-id="03067-1861">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="03067-1862">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1862">Outlook</span></span>

- <span data-ttu-id="03067-1863">Es wurde ein Problem mit dem Ereignis "CLP-Überwachung" für die Bezeichnung "Antworten/Weiterleiten" behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-1863">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="03067-1864">Es wurde ein Problem behoben, bei dem beim Einreichen von Feedback aus einer Administratorbenachrichtigung ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1864">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-may-14"></a><span data-ttu-id="03067-1866">Version 2005: 14. Mai</span><span class="sxs-lookup"><span data-stu-id="03067-1866">Version 2005: May 14</span></span>
<span data-ttu-id="03067-1867">*Version 2005 (Build 12827.20160)*</span><span class="sxs-lookup"><span data-stu-id="03067-1867">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1869">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1869">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-1870">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1870">Excel</span></span>

- <span data-ttu-id="03067-1871">**Automatisches Anwenden oder Empfehlen von Vertraulichkeitsbezeichnungen:** Office kann eine Vertraulichkeitsbezeichnung basierend auf den erkannten vertraulichen Inhalten empfehlen oder automatisch anwenden.</span><span class="sxs-lookup"><span data-stu-id="03067-1871">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="03067-1872">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1872">PowerPoint</span></span>

- <span data-ttu-id="03067-1873">**Kein Clicker benötigt: das erledigen Ihre Ohrhörer**: Verwenden Sie Ihre Surface Earbuds, um Ihre PowerPoint-Präsentationen zu steuern.</span><span class="sxs-lookup"><span data-stu-id="03067-1873">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="03067-1874">Wichtig: Sie müssen Ihre Surface Earbuds in der Surface Audio-App für Windows 10 koppeln, um Gesten für die Steuerung von Präsentationen verwenden zu können.</span><span class="sxs-lookup"><span data-stu-id="03067-1874">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="03067-1875">Anweisungen für die ersten Schritte mit der Surface Audio-App unter Windows 10 finden Sie hier.</span><span class="sxs-lookup"><span data-stu-id="03067-1875">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="03067-1876">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1876">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="03067-1877">**Automatisches Anwenden oder Empfehlen von Vertraulichkeitsbezeichnungen:** Office kann eine Vertraulichkeitsbezeichnung basierend auf den erkannten vertraulichen Inhalten empfehlen oder automatisch anwenden.</span><span class="sxs-lookup"><span data-stu-id="03067-1877">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="03067-1878">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1878">Word</span></span>

- <span data-ttu-id="03067-1879">**Automatisches Anwenden oder Empfehlen von Vertraulichkeitsbezeichnungen:** Office kann eine Vertraulichkeitsbezeichnung basierend auf den erkannten vertraulichen Inhalten empfehlen oder automatisch anwenden.</span><span class="sxs-lookup"><span data-stu-id="03067-1879">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1882">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1882">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="03067-1883">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1883">Excel</span></span>

- <span data-ttu-id="03067-1884">Die Größe der Steuerelemente zur Bearbeitung von Zellreferenzen im Dialogfeld "Benutzerdefinierte Fehlerindikatoren", das bei Diagrammen verwendet wird, wurde erhöht.</span><span class="sxs-lookup"><span data-stu-id="03067-1884">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="03067-1885">Ein Problem wurde behoben, bei dem die Diagrammdatentabelle Werte in einer Datumsachse nicht korrekt rendern konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-1885">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="03067-1886">Es wurde ein Problem behoben, bei dem Seitenumbrüche nicht deaktiviert werden konnten, nachdem die Seitenlayout- oder Seitenumbruchsvorschau angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1886">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="03067-1887">Es wurde ein Problem behoben, bei dem Diagrammlinienarten nach dem Ein- und Ausblenden von Spalten mit Seriendaten verloren gehen konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-1887">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="03067-1888">Es wurde ein Problem behoben, bei dem das Einfügen einer Spalte in eine gefilterte Liste länger als erwartet dauern würde.</span><span class="sxs-lookup"><span data-stu-id="03067-1888">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="03067-1889">Ein Problem mit der Skalierung von Kontrollkästchen in Formularsteuerelementen beim Drucken wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-1889">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="03067-1890">Es wurde ein Problem behoben, bei dem die externe Verknüpfung nicht mehr funktioniert, nachdem die Datei erneut geöffnet wurde, wenn der Dateipfad zu lang ist.</span><span class="sxs-lookup"><span data-stu-id="03067-1890">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="03067-1891">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1891">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="03067-1892">Application.Evaluate (VBA) funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.</span><span class="sxs-lookup"><span data-stu-id="03067-1892">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="03067-1893">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1893">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="03067-1894">Diese Änderung behebt ein Problem, bei dem Informationen zur bedingten Formatierung (CF) nicht korrekt in XLSB-Dateien gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1894">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="03067-1895">Diese Änderung behebt ein Problem, bei dem das Bestimmtheitsmaß der Diagrammtrendlinie (im Fall des erzwungenen y-Achsenabschnitts) falsch war, obwohl die Funktion LINEST den richtigen Wert zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="03067-1895">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="03067-1896">Diese Änderung behebt ein Problem, bei dem benutzerdefinierte Diagramm-Trendlinienformatierungen nicht immer gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1896">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="03067-1897">Ein Absturz konnte auftreten, wenn versucht wurde, Änderungen mithilfe des Legacymodus "Freigegebene Arbeitsmappe" auf einem neuen Blatt für eine Arbeitsmappe aufzulisten.</span><span class="sxs-lookup"><span data-stu-id="03067-1897">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="03067-1898">Das Problem, bei dem es sein konnte, dass benutzerdefinierte Formatierungen in Pivot-Diagrammen nicht gespeichert wurden, wenn die Option "Invertieren, wenn negativ" aktiviert war, wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-1898">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="03067-1899">Es wurde ein Problem behoben, bei dem die benutzerdefinierte Formatierung für einen einzelnen Datenpunkt in einem Pivot-Diagramm nicht gespeichert wurde, wenn die Option "Invertieren, wenn negativ" ausgewählt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1899">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="03067-1900">Diese Änderung behebt ein Problem, bei dem das in eine CSV-Datei hochgeladene @-Zeichen dazu führte, dass die Zeichenfolge nach dem @-Zeichen in eine Formel konvertiert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1900">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="03067-1901">Es wurde ein Problem behoben, bei dem Dezimalwerte in der SEQUENCE-Funktion nicht korrekt gerundet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1901">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="03067-1902">OneNote</span><span class="sxs-lookup"><span data-stu-id="03067-1902">OneNote</span></span>

- <span data-ttu-id="03067-1903">Ein Problem beim Speichern von Zeilenumbrüchen als vertikale Registerkarten wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-1903">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-1904">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1904">Outlook</span></span>

- <span data-ttu-id="03067-1905">Behebt ein Problem, das dazu führte, dass Benutzer keine "Persönliche Kontaktgruppe" als "Besprechungsteilnehmer" hinzufügen konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-1905">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="03067-1906">Es wurde ein Problem behoben, bei dem die Schaltfläche "Kategorisieren" für Gruppenkalender im Office-Menüband deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1906">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="03067-1907">Es wurde ein Problem behoben, durch das Outlook nach einem Windows-Update beim Öffnen von lokal gespeicherten MSG- oder OFT-Dateien abstürzte.</span><span class="sxs-lookup"><span data-stu-id="03067-1907">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="03067-1908">Es wurde ein Problem behoben, bei dem Gruppenordner von Unternehmenskunden, die nicht implementiert sind oder nicht funktionieren, in Outlook zu der Meldung "reagiert nicht" führte.</span><span class="sxs-lookup"><span data-stu-id="03067-1908">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="03067-1909">Es wurde ein Problem behoben, das dazu führte, dass sehr lange Safelinks, auf die Benutzer im Outlook-Desktopclient klickten, aufgrund von Trunkierung nicht geladen wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1909">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="03067-1910">Es wurde ein Problem behoben, bei dem Outlook-Ordner mit Namen, die DBCS-Zeichen (Doublebyte-Zeichensatz) enthalten, bei der Synchronisierung mit dem Server zeitweise verschwanden.</span><span class="sxs-lookup"><span data-stu-id="03067-1910">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="03067-1911">Dazu musste Outlook mit einem IMAP-Konto konfiguriert und auf einem System mit dem Gebietsschema „Japanisch“ ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="03067-1911">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="03067-1912">Es wurde ein Problem behoben, das dazu führte, dass Löschregeln, die für andere Postfächer als das primäre Postfach des Benutzers erstellt wurden, ungültig wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1912">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="03067-1913">Es wurde ein Problem behoben, das dazu führte, dass Anlagen beim Weiterleiten einer verschlüsselten Nachricht verworfen wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1913">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="03067-1914">Es wurde ein Problem behoben, das dazu geführt hat, dass bei Besprechungen, die mehr als 2 Monate entfernt sind, ein Besprechungsthema im "Terminplanungs-Assistenten" nicht angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="03067-1914">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="03067-1915">Behebt ein Problem, das dazu führte, dass Benutzer beim Weiterleiten großer HTML-Nachrichten den Nachrichtentext abgeschnitten sahen.</span><span class="sxs-lookup"><span data-stu-id="03067-1915">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="03067-1916">Es wurde die Möglichkeit des Erzwingens der S/MIME-Standardsignatur-Konfiguration über eine Gruppenrichtlinie hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="03067-1916">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="03067-1917">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1917">PowerPoint</span></span>

- <span data-ttu-id="03067-1918">Es wurde ein Problem behoben, bei dem Entwürfe von Kommentaren nicht verfügbar waren, wenn ein Benutzer einen Kommentar erstellte, ohne ihn zu posten, und den Kommentarbereich schloss, dann ein neues Fenster öffnete, über mehrere Folien navigierte, das Fenster schloss und schließlich den Kommentarbereich in der ursprünglichen Präsentation wieder öffnete.</span><span class="sxs-lookup"><span data-stu-id="03067-1918">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="03067-1919">Es wurde ein Problem behoben, bei dem beim Bewegen des Mauszeigers über das Sternchen-Symbol (\*) der Benutzername und das Datum der letzten Person, die das Dokument aktualisiert hat, nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1919">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="03067-1920">Project</span><span class="sxs-lookup"><span data-stu-id="03067-1920">Project</span></span>

- <span data-ttu-id="03067-1921">Wenn Vorgänger/Nachfolger-Daten in einer Formular-Maske bearbeitet werden, wird ein zusätzliches ProjectBeforeTaskChange-Ereignis ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="03067-1921">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="03067-1922">Es wurde ein Problem behoben, bei dem Project abstürzen konnte, wenn das Feld „Boardstatus“ in einem Projekt geändert wurde, das mit einer SharePoint-Aufgabenliste verbunden ist.</span><span class="sxs-lookup"><span data-stu-id="03067-1922">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="03067-1923">Ein Problem wurde behoben, bei dem Project beim Speichern von Projekten möglicherweise abstürzt, die mit älteren Project-Versionen erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-1923">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="03067-1924">Folgendes Problem wurde behoben: Wenn Sie Project in Verbindung mit der Project Web App verwenden, das Kommas als Dezimaltrennzeichen festgelegt ist, und Sie versuchten, eine Verzögerung hinzuzufügen, schlägt die Methode "TaskDependencies Add" fehl.</span><span class="sxs-lookup"><span data-stu-id="03067-1924">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="03067-1925">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1925">Word</span></span>

- <span data-ttu-id="03067-1926">Es wurde ein Problem behoben, das dazu führte, dass das Einfügen von Kommentaren in ein Dokument im Kollaborationsmodus nicht immer funktionierte.</span><span class="sxs-lookup"><span data-stu-id="03067-1926">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="03067-1927">Diese Änderung behebt ein Problem, bei dem die Personenkarte kurzzeitig eingeblendet wurde, wenn auf die Erwähnung geklickt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1927">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="03067-p215">Beim Aktivieren der Option „Lesezeichen anzeigen“ wurden keine Lesezeichen angezeigt. Dies wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-p215">Enabling the option "Show bookmarks" would not display bookmarks. This has been fixed.</span></span>

- <span data-ttu-id="03067-p216">Es wurde das Problem behoben, dass beim Schließen eines Dokuments mit Kommentarentwürfen der Benutzer gefragt wurde, ob er das Dokument schließen möchte, ohne die Kommentarentwürfe zu speichern. Das Abbrechen der Aufforderung führte zum Schließen des Dokuments, anstatt es offen zu lassen.</span><span class="sxs-lookup"><span data-stu-id="03067-p216">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments. Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="03067-1932">Ein Problem beim Kopieren und Einfügen von Überschriften wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-1932">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="03067-1933">Es wurde ein Problem behoben, bei dem die Übersetzung eines geposteten Kommentars den Fehler "Fehler beim Einfügen des übersetzten Textes" zur Folge hatte.</span><span class="sxs-lookup"><span data-stu-id="03067-1933">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="03067-1934">Diese Änderung behebt ein Problem, bei dem Text mit Hyperlinks möglicherweise nicht angezeigt wurde, wenn die Option "Feldcodes statt ihrer Werte anzeigen" aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="03067-1934">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="03067-p217">In der Webansicht und im Plastischen Reader wurde durch das Anklicken eines Hinweises ganz nach oben gescrollt, obwohl er bereits angezeigt wurde. Dies wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-p217">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view. This has been fixed.</span></span>

- <span data-ttu-id="03067-1937">Wir haben ein Problem behoben, dass infolge des Speicherns einer Datei, die ein Makro enthält, unter einem neuen Namen sie mit der Erweiterung DOCX und dem Dateinamen WRO0004.docx gespeichert wurde, und zwar unabhängig davon, was der Benutzer eingab, wodurch das Dokument unbrauchbar wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-1937">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="03067-1938">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-1938">Office Suite</span></span>

- <span data-ttu-id="03067-1939">Wenn ein Benutzer eine Richtlinie erhält, die ihn in die Kategorie "Nur für Teams" verschiebt, konnte er dennoch das Outlook-Add-In "Skype for Business" zur Planung von Besprechungen verwenden.</span><span class="sxs-lookup"><span data-stu-id="03067-1939">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="03067-1940">Nach diesem Update können Sie keine Besprechungen mit Skype for Business mehr planen, nachdem der Client die Richtlinie gelesen hat, in der angegeben ist, dass der Benutzer "Nur für Teams" ist, und in den Modus "Nur an Besprechung teilnehmen" wechselt.</span><span class="sxs-lookup"><span data-stu-id="03067-1940">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="03067-1941">Darüber hinaus aktiviert sich das Outlook-Add-In "Skype for Business" beim Start nicht selbst, wenn es sieht, dass sich der Skype for Business-Client im Modus "Nur an Besprechung teilnehmen" befindet.</span><span class="sxs-lookup"><span data-stu-id="03067-1941">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="03067-1942">Das Update behebt ein Problem in Microsoft Office, bei dem Visual Basic for Applications-Projekte mit Referenzen, die bei der Suche nach in der PATH-Umgebungsvariable angegebenen Speicherorten gefunden werden sollen, zur Laufzeit möglicherweise nicht richtig gefunden werden, was zu VBA-Laufzeitfehlern führt.</span><span class="sxs-lookup"><span data-stu-id="03067-1942">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="03067-1943">Dieses Update behebt ein Problem in Visual Basic for Applications in Microsoft Office, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung beim Laden als fehlerhaft angesehen werden.</span><span class="sxs-lookup"><span data-stu-id="03067-1943">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-may-11"></a><span data-ttu-id="03067-1945">Version 2004: 11. Mai</span><span class="sxs-lookup"><span data-stu-id="03067-1945">Version 2004: May 11</span></span>
<span data-ttu-id="03067-1946">*Version 2004 (Build 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="03067-1946">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1948">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1948">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-1949">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-1949">Excel</span></span>

- <span data-ttu-id="03067-1950">**Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen.</span><span class="sxs-lookup"><span data-stu-id="03067-1950">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-1951">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1951">Outlook</span></span>

- <span data-ttu-id="03067-1952">**Verbesserte Links in E-Mails:** Wenn Sie einen Link zu einer Datei einfügen, ersetzt der Dateiname die URL.</span><span class="sxs-lookup"><span data-stu-id="03067-1952">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="03067-1953">Sie können die Berechtigungen so ändern, dass alle Empfänger Zugriff haben.</span><span class="sxs-lookup"><span data-stu-id="03067-1953">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="03067-1954">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1954">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="03067-1955">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span><span class="sxs-lookup"><span data-stu-id="03067-1955">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="03067-1956">**Erzählen Sie mit animierten GIFs über sich:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden künftig noch pfiffiger aussehen.</span><span class="sxs-lookup"><span data-stu-id="03067-1956">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="03067-1957">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-1957">PowerPoint</span></span>

- <span data-ttu-id="03067-p220">**Erzählen Sie Ihre Geschichten mit animierten GIFs:** Animierte GIFs werden nun im Office-Editor unterstützt – peppen Sie Ihre Dokumente auf.  [Weitere Informationen](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span><span class="sxs-lookup"><span data-stu-id="03067-p220">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.  [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span></span>

### <a name="word"></a><span data-ttu-id="03067-1960">Word</span><span class="sxs-lookup"><span data-stu-id="03067-1960">Word</span></span>

- <span data-ttu-id="03067-1961">**Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen.</span><span class="sxs-lookup"><span data-stu-id="03067-1961">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1964">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1964">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1965">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1965">Outlook</span></span>

- <span data-ttu-id="03067-1966">Es wurde ein Problem behoben, das bei Benutzern zu Abstürzen geführt hat, wenn diese Toast-Nachrichten angesehen haben.</span><span class="sxs-lookup"><span data-stu-id="03067-1966">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-may-04"></a><span data-ttu-id="03067-1968">Version 2004: 04. Mai</span><span class="sxs-lookup"><span data-stu-id="03067-1968">Version 2004: May 04</span></span>
<span data-ttu-id="03067-1969">*Version 2004 (Build 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="03067-1969">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1971">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1971">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1972">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1972">Outlook</span></span>

- <span data-ttu-id="03067-1973">**Bessere Ergebnisse – im Handumdrehen:** wir haben die Suche aktualisiert, damit Sie intelligenter, schneller und zuverlässiger als je zuvor ist.</span><span class="sxs-lookup"><span data-stu-id="03067-1973">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="03067-1974">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1974">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="03067-1975">**Benachrichtigung Über Vorfall für IT-Administratoren:** Globale Administratoren von Microsoft 365-Mandanten und Administratoren von Office-Apps werden über Outlook und O365 Exchange-Vorfällen benachrichtigt, die sich auf Ihre Benutzer auswirken – mit einer neuen Benachrichtigung im rechten Seitenbereich in Outlook für Windows.</span><span class="sxs-lookup"><span data-stu-id="03067-1975">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="03067-1976">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-1976">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1979">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1979">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="03067-1980">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-1980">Office Suite</span></span>

- <span data-ttu-id="03067-1981">Dieses Update behebt ein Problem in Visual Basic for Applications in Microsoft Office, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung beim Laden als fehlerhaft angesehen werden.</span><span class="sxs-lookup"><span data-stu-id="03067-1981">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-april-29"></a><span data-ttu-id="03067-1983">Version 2004: 29. April</span><span class="sxs-lookup"><span data-stu-id="03067-1983">Version 2004: April 29</span></span>
<span data-ttu-id="03067-1984">*Version 2004 (Build 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="03067-1984">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-1986">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-1986">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1987">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1987">Outlook</span></span>

- <span data-ttu-id="03067-1988">**Schützen von Daten in einer Gruppe:** Die beim Erstellen einer Gruppe ausgewählte Vertraulichkeitsbezeichnung wird auf Gruppen-E-Mails, Dokumente und Teamwebsites angewendet.</span><span class="sxs-lookup"><span data-stu-id="03067-1988">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1991">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1991">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1992">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1992">Outlook</span></span>

- <span data-ttu-id="03067-1993">Behebt ein Problem, das dazu geführt hat, dass Outlook bei einigen Windows-Versionen abstürzt.</span><span class="sxs-lookup"><span data-stu-id="03067-1993">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-april-25"></a><span data-ttu-id="03067-1995">Version 2004: 25. April</span><span class="sxs-lookup"><span data-stu-id="03067-1995">Version 2004: April 25</span></span>
<span data-ttu-id="03067-1996">*Version 2004 (Build 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="03067-1996">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-1998">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-1998">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-1999">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-1999">Outlook</span></span>

- <span data-ttu-id="03067-2000">Es wurde ein Problem behoben, durch das Outlook nach einem Windows-Update beim Öffnen von lokal gespeicherten MSG- oder OFT-Dateien abstürzte.</span><span class="sxs-lookup"><span data-stu-id="03067-2000">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="03067-2001">Project</span><span class="sxs-lookup"><span data-stu-id="03067-2001">Project</span></span>

- <span data-ttu-id="03067-2002">Folgendes Problem wurde behoben: Wenn Sie Project in Verbindung mit Project Web App verwenden, das Kommas als Dezimaltrennzeichen festgelegt ist, und Sie versuchten, einer Abhängigkeit eine Verzögerung hinzuzufügen, schlägt die Methode "TaskDependencies Add" fehl.</span><span class="sxs-lookup"><span data-stu-id="03067-2002">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="03067-2003">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-2003">Office Suite</span></span>

- <span data-ttu-id="03067-2004">Mit diesem Fix wird ein Fehler behoben, der verhindert, dass Sie gleichzeitig den Zugriff einschränken und Dateien mit einem Kennwort schützen können.</span><span class="sxs-lookup"><span data-stu-id="03067-2004">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-april-21"></a><span data-ttu-id="03067-2006">Version 2004: 21. April</span><span class="sxs-lookup"><span data-stu-id="03067-2006">Version 2004: April 21</span></span>
<span data-ttu-id="03067-2007">*Version 2004 (Build 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="03067-2007">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-2009">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-2009">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-2010">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-2010">Outlook</span></span>

- <span data-ttu-id="03067-2011">Behebt ein Problem, bei dem die Breite des Ordnerbereichs unerwartet geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2011">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="03067-2012">Behebt ein Problem, bei dem sich das Programm beim Verlassen von Outlook aufhängte.</span><span class="sxs-lookup"><span data-stu-id="03067-2012">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-april-15"></a><span data-ttu-id="03067-2014">Version 2004: 15. April</span><span class="sxs-lookup"><span data-stu-id="03067-2014">Version 2004: April 15</span></span>
<span data-ttu-id="03067-2015">*Version 2004 (Build 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="03067-2015">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-2017">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-2017">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-2018">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-2018">Excel</span></span>

- <span data-ttu-id="03067-2019">**Die Unterstützung für Facebook Connector endet:** Ab April 2020 werden von Excel keine externen Datenverbindungen mehr unterstützt, für die der Facebook-Connector eingesetzt wird.</span><span class="sxs-lookup"><span data-stu-id="03067-2019">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-2020">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-2020">Outlook</span></span>

- <span data-ttu-id="03067-2021">**Neue Option zum Deaktivieren von Vorschlägen für @Erwähnungen beim Verfassen von E-Mails in Outlook:** Finden Sie die @Erwähnung-Auswahl eher lästig als sinnvoll?</span><span class="sxs-lookup"><span data-stu-id="03067-2021">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="03067-2022">Wenn Sie das möchten, können Sie diese nun deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="03067-2022">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="03067-2023">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-2023">PowerPoint</span></span>

- <span data-ttu-id="03067-2024">**Synchronisieren von Änderungen während der Präsentation:** Änderungen können jetzt synchronisiert werden, wenn sie vorgenommen werden, selbst wenn sich die Präsentation im Bildschirmpräsentationsmodus befindet.</span><span class="sxs-lookup"><span data-stu-id="03067-2024">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="03067-2025">Word</span><span class="sxs-lookup"><span data-stu-id="03067-2025">Word</span></span>

- <span data-ttu-id="03067-2026">**Fügen Sie einen privaten Kopie Anmerkungen hinzu:** Erstellen Sie handschriftliche Notizen nur für Sie, indem Sie eine private Kopie eines freigegebenen Dokuments erstellen.</span><span class="sxs-lookup"><span data-stu-id="03067-2026">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="03067-2027">Wechseln Sie dazu einfach zu "Anzeige" > "Private Kopie erstellen".</span><span class="sxs-lookup"><span data-stu-id="03067-2027">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-2030">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-2030">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="03067-2031">Access</span><span class="sxs-lookup"><span data-stu-id="03067-2031">Access</span></span>

- <span data-ttu-id="03067-2032">Probleme bei der Anpassung der Größe und der Aktualisierung von Tabellen im Aufgabenbereich wurden behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-2032">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="03067-2033">Ein Problem wurde behoben, bei dem internationale Versionen von Access in der Benutzeroberfläche englische Zeichenfolgen anzeigten.</span><span class="sxs-lookup"><span data-stu-id="03067-2033">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="03067-2034">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-2034">Excel</span></span>

- <span data-ttu-id="03067-2035">Es wurde ein Problem behoben, bei dem das Auswählen eines Zellbereichs auf einem Arbeitsblatt zur Auswahl nur einer einzelnen Zelle geführt hat.</span><span class="sxs-lookup"><span data-stu-id="03067-2035">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="03067-2036">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2036">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="03067-2037">Ein Problem wurde behoben, bei dem Excel in manchen Fällen abstürzte, nachdem ein Blatt mit einer PivotTable kopiert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2037">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="03067-2038">Application.Evaluate (VBA) funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.</span><span class="sxs-lookup"><span data-stu-id="03067-2038">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="03067-2039">Es wurde ein Leistungsproblem behoben, das Benutzer beim programmgesteuerten Bearbeiten eines großen Zellbereichs festgestellt haben.</span><span class="sxs-lookup"><span data-stu-id="03067-2039">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="03067-2040">Ein Leistungsproblem beim Öffnen von CSV-Dateien in japanischen Umgebungen wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-2040">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="03067-2041">Es wurde ein Problem behoben, bei dem das Einfügen einer benutzerdefinierten Diagrammvorlage als Standard dazu führte, dass sie als Säulendiagramm gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2041">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="03067-2042">Ein Problem wurde behoben, bei dem Datenbeschriftungen in Diagrammen leer angezeigt wurden, wenn die zugrundeliegenden Datenzellen keine Beschriftung aufwiesen.</span><span class="sxs-lookup"><span data-stu-id="03067-2042">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="03067-2043">Es wurde ein Problem behoben, das dazu führen konnte, dass Excel nicht mehr reagierte, wenn die Größe eines Diagramms mit einigen x-Achsen-Bereichen reduziert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2043">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="03067-2044">Es wurde ein Problem behoben, bei dem eine Excel-Tabelle mit aktiviertem Z1S1-Zellbezug die freigegeben bzw. gemeinsam erstellt wurde, der aktive Zellbezug im Z1S1-Modus nicht angezeigt wurde, wenn man auf das Symbol für die Anwesenheitsanzeige zeigte.</span><span class="sxs-lookup"><span data-stu-id="03067-2044">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="03067-2045">Diese Änderung betrifft Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen.</span><span class="sxs-lookup"><span data-stu-id="03067-2045">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-2046">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-2046">Outlook</span></span>

- <span data-ttu-id="03067-2047">Diese Änderung ist gegen Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen gerichtet.</span><span class="sxs-lookup"><span data-stu-id="03067-2047">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="03067-2048">Diese Änderung behebt ein Problem, bei dem die neuesten Änderungen an E-Mail-Entwürfen nicht aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-2048">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="03067-2049">Ein Problem wurde behoben, bei dem Sie mit der rechten Maustaste auf eine Datei klicken und "Senden an" nicht funktionieren würde.</span><span class="sxs-lookup"><span data-stu-id="03067-2049">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="03067-2050">Ein Problem wurde behoben, durch das Stellvertretungen auf unterschiedlichen Computern unterschiedliche Ordnerhierarchien für freigegebene Postfächer angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-2050">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="03067-2051">Ein Problem wurde behoben, durch das gelegentlich Kategorien in E-Mail-Nachrichten nicht mehr aufschienen.</span><span class="sxs-lookup"><span data-stu-id="03067-2051">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="03067-2052">Es wurde ein Problem behoben, durch das einige Erinnerungen nicht ausgelöst wurden, wenn die Zeitzone auf einem Computer geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2052">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="03067-2053">Es wurde ein Problem behoben, das einen Absturz verursachte, wenn Benutzer versuchten, die Eigenschaften eines Organisationsformulars anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="03067-2053">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="03067-2054">Es wurde ein Problem behoben, bei dem, wenn ein Benutzer einen angepassten Suchpfad für das Adressbuch hatte, der Namensauflösungsbereich von Outlook auf den angepassten Pfad beschränkt wurde, anstatt die Globale Adressliste (GAL) einzubeziehen.</span><span class="sxs-lookup"><span data-stu-id="03067-2054">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="03067-2055">Es wurde ein Problem behoben, das bewirkt hat, dass die Schaltfläche "In der Cloud speichern" in den Anlagentools fehlte.</span><span class="sxs-lookup"><span data-stu-id="03067-2055">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="03067-2056">Es wurde ein Problem behoben, das bewirkt hat, dass Benutzer beim Antworten auf eine verwaltete Nachricht mit digitaler Berechtigung aus einem Inspektor-Fenster keine Signatur hinzufügen konnten, wenn er nicht über die Berechtigung "Besitzer" für die Nachricht verfügte, auf die geantwortet wird.</span><span class="sxs-lookup"><span data-stu-id="03067-2056">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="03067-2057">Es wurde ein Problem behoben, durch das Benutzer keine weiteren Anlagen von einem Webspeicherort zu einer zuvor erstellten Besprechung hinzufügen konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-2057">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="03067-2058">Es wurde ein Problem behoben, das dazu geführt hat, dass das „Datum der letzten Änderung“ in einer Datei beim Hinzufügen einer Anlage zu einer E-Mail oder beim Speichern einer Anlage aus einer E-Mail durch Ziehen und Ablegen (im Gegensatz zum Hinzufügen oder Speichern über ein Menü) aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2058">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="03067-2059">Es wurde ein Problem behoben, bei dem durch das Drücken der EINGABETASTE im erweiterten Suchbereich keine Suche gestartet wurde. Stattdessen mussten Benutzer auf die Schaltfläche "Suchen" klicken.</span><span class="sxs-lookup"><span data-stu-id="03067-2059">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="03067-2060">Es wurde ein Problem behoben, bei dem innerhalb eines Satzes von zurückgegebenen Suchergebnissen beim Sortieren der Ergebnisse nach Kategorien die Kategoriefarben nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-2060">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="03067-2061">Ein Problem wurde behoben, bei dem die Suche keine Informationen zu Benutzern anzeigte, wenn die Option "Benutzerfotos anzeigen, wenn verfügbar" deaktiviert war.</span><span class="sxs-lookup"><span data-stu-id="03067-2061">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="03067-2062">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-2062">PowerPoint</span></span>

- <span data-ttu-id="03067-2063">Diese Änderung behebt einen Fehler, der dazu führen kann, dass PowerPoint-Dateien mit Emojis beim Speichern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="03067-2063">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="03067-2064">Diese Änderung behebt ein Problem, bei dem beim Rendern eines Diagramms einer älteren Excel-Version, das als OLE-Objekt in PowerPoint oder Word eingebettet ist, u. U. nicht immer der Diagrammtitel angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2064">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="03067-2065">Es wurde ein Problem behoben, bei dem beim Kopieren von Text aus Excel in PowerPoint u. U. dessen Formatierung geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2065">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="03067-2066">Diese Änderung behebt ein Problem, bei dem das Suchen von Sonderzeichen mithilfe der Option "Nur ganze Wörter suchen" nicht immer erwartungsgemäß funktioniert hat.</span><span class="sxs-lookup"><span data-stu-id="03067-2066">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="03067-2067">Project</span><span class="sxs-lookup"><span data-stu-id="03067-2067">Project</span></span>

- <span data-ttu-id="03067-2068">Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-2068">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="03067-2069">Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.</span><span class="sxs-lookup"><span data-stu-id="03067-2069">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="03067-2070">Ein Problem wurde behoben, bei dem das VBA-Ereignis (Visual Basic Applications) "ProjectBeforeTaskChange" nicht ausgelöst wurde, wenn ein Benutzer auf die Schaltfläche "Deaktivieren" geklickt hat, die sich auf dem Menüband "Vorgänge" innerhalb der Planungsgruppierung befindet.</span><span class="sxs-lookup"><span data-stu-id="03067-2070">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="03067-2071">Wenn Sie Vorgänger- oder Nachfolgerdetails in einer Ansicht vom Typ „Formular“ festlegen, wurden die Änderungen nicht immer durch das Ereignis „ProjectBeforeTaskChange Visual Basic Applications“ (VBA) erfasst.</span><span class="sxs-lookup"><span data-stu-id="03067-2071">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="03067-2072">Wenn Sie beispielsweise eine Abhängigkeit gelöscht und im Formular auf „OK“ geklickt haben, wurde das Ereignis nicht ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="03067-2072">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="03067-2073">Dieses Verhalten wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-2073">This behavior has been fixed.</span></span>

- <span data-ttu-id="03067-2074">Es wurde ein Problem behoben, bei dem die neuesten Werte für die tatsächlichen Kosten der geleisteten Arbeit (ACWP) nicht angezeigt wurden, nachdem eine Änderung, z. B. eine Datumsänderung, vorgenommen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2074">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="03067-2075">Es wurde ein Problem behoben, bei dem das Öffnen eines Projekts über das Menü "Zuletzt verwendet" (MRU) die Projektdatei mit Lese- bzw. Schreibzugriff öffnete.</span><span class="sxs-lookup"><span data-stu-id="03067-2075">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="03067-2076">Diese Änderung behebt das Problem, dass Sie eine manuelle Aufgabe mit einem Startdatum und einer Uhrzeit (aber ohne Dauer) erstellt haben, diese aber mit einer falschen Uhrzeit auf der Zeitachse angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2076">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="03067-2077">Es wurde ein Problem behoben, bei dem das Drucken einer Zeitleiste mithilfe eines Hijri-Kalenders dazu führte, dass ein Monat in der Druckansicht übersprungen oder dupliziert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2077">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="03067-2078">Diese Änderung richtet sich gegen ein Problem, bei dem die Arbeit im Team Planner mit GDI-Objekten zu einer Überzuweisung von GDI-Objekten und zu geringem Speicherplatz führen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-2078">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="03067-2079">Ein Problem wurde behoben, durch das, wenn "CustomFieldValueListGetItem" ausgeführt wurde und keine Nachschlagetabelle für das benutzerdefinierte Feld vorhanden war, eine leere Nachschlagetabelle erstellt wurde, auch wenn dies nicht so sein sollte.</span><span class="sxs-lookup"><span data-stu-id="03067-2079">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="03067-2080">Wenn Vorgänger/Nachfolger-Daten in einer Maske bearbeitet werden, wird ein zusätzliches ProjectBeforeTaskChangeevent ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="03067-2080">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="03067-2081">Es wurde ein Problem behoben, bei dem der Benutzer keine zeitgesteuerte Baseline-Arbeit eingeben konnte, wenn die Einstellung zum Schutz der aktuellen Arbeit aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="03067-2081">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="03067-2082">Word</span><span class="sxs-lookup"><span data-stu-id="03067-2082">Word</span></span>

- <span data-ttu-id="03067-2083">Diese Änderung behebt ein Problem, bei dem wenn der Mauszeiger über einen Hinweis gehalten wurde, dessen Karte nicht hervorgehoben wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2083">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="03067-2084">Diese Änderung behebt ein Problem, bei dem wenn mehrere Seiten aus dem Menü "Ansicht" ausgewählt wurden, der Kommentarbereich u. U. als leer angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2084">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="03067-2085">Es wurde ein Problem behoben, durch das die Funktion zum Posten von Kommentaren deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2085">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="03067-2086">Diese Änderung behebt ein Problem, das dazu führte, dass der Text in gruppierten Formen beim Verwenden des Lasso-Auswahltools vorübergehend ausgeblendet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2086">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="03067-2087">Diese Änderung betrifft Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen.</span><span class="sxs-lookup"><span data-stu-id="03067-2087">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="03067-2088">Diese Änderung behebt ein Problem, bei dem beim Rendern eines Diagramms einer älteren Excel-Version, das als OLE-Objekt in PowerPoint oder Word eingebettet ist, u. U. nicht immer der Diagrammtitel angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2088">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="03067-2089">Diese Änderung betrifft ein Problem, bei dem der Account Manager keine Nachrichten versendete, was zu einer Unterbrechung bei Anwendungen von Drittanbietern führte.</span><span class="sxs-lookup"><span data-stu-id="03067-2089">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="03067-2090">Diese Änderung behebt ein Problem in der Zwei-Seiten-Ansicht. Beim Erstellen eines Kommentars wurde der Kommentaranker nicht immer in der Anzeige angezeigt.</span><span class="sxs-lookup"><span data-stu-id="03067-2090">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="03067-2091">Ein Problem wurde behoben, bei dem das Eingeben oder Bearbeiten eines Kommentars und Verwenden von STRG+A dazu führte, dass statt nur innerhalb der Kommentarkarte Text im Zeichenbereich markiert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2091">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="03067-2092">Ein Problem wurde behoben, bei dem ein Absatz, dessen Formatvorlage ein Vorgänger einer mit einer Liste verknüpften Formatvorlage war, möglicherweise verloren ging.</span><span class="sxs-lookup"><span data-stu-id="03067-2092">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="03067-2093">Diese Änderung behebt ein Problem, bei dem das Inhaltsverzeichnis mit Überschriftenformaten aktualisiert wurde, die im Dokument nicht vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="03067-2093">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="03067-2094">Es wurde ein Problem behoben, bei dem die Ausrichtung von Wörtern in einem Dokument durcheinandergebracht wurde, wenn Benutzer nach dem Drucken mit Schnelldruck versuchten, den Text zu bearbeiten.</span><span class="sxs-lookup"><span data-stu-id="03067-2094">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="03067-2095">Es wurde ein Problem beim Zusammenführen von zwei Dokumenten in ein Dokument behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-2095">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="03067-2096">Es wurde ein Problem behoben, bei dem in Word-Dokumenten gespeicherte digitale Signaturen beim Versand der Dokumente per E-Mail entfernt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-2096">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="03067-2097">Es wurde ein Problem behoben, bei dem das Markieren von Überarbeitungen, die Formeln enthalten, beim Speichern der Datei zu einem Fehler führen konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-2097">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-april-14"></a><span data-ttu-id="03067-2099">Version 2003: 14. April</span><span class="sxs-lookup"><span data-stu-id="03067-2099">Version 2003: April 14</span></span>
<span data-ttu-id="03067-2100">*Version 2003 (Build 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="03067-2100">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="03067-2101">Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="03067-2101">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (FEATUREDETAILS CONTENT START NICHT ENTFERNEN)

- <span data-ttu-id="03067-2103">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="03067-2103">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-april-09"></a><span data-ttu-id="03067-2105">Version 2003: 09. April</span><span class="sxs-lookup"><span data-stu-id="03067-2105">Version 2003: April 09</span></span>
<span data-ttu-id="03067-2106">*Version 2003 (Build 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="03067-2106">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-2108">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-2108">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-2109">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-2109">Excel</span></span>

- <span data-ttu-id="03067-2110">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="03067-2110">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="03067-2111">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="03067-2111">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-2112">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-2112">Outlook</span></span>

- <span data-ttu-id="03067-2113">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="03067-2113">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="03067-2114">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="03067-2114">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="03067-2115">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-2115">PowerPoint</span></span>

- <span data-ttu-id="03067-2116">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="03067-2116">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="03067-2117">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="03067-2117">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="03067-2118">Word</span><span class="sxs-lookup"><span data-stu-id="03067-2118">Word</span></span>

- <span data-ttu-id="03067-2119">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="03067-2119">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="03067-2120">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="03067-2120">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)




[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-april-03"></a><span data-ttu-id="03067-2124">Version 2003: 3. April</span><span class="sxs-lookup"><span data-stu-id="03067-2124">Version 2003: April 03</span></span>
<span data-ttu-id="03067-2125">*Version 2003 (Build 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="03067-2125">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-2127">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-2127">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-2128">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-2128">Excel</span></span>

- <span data-ttu-id="03067-2129">Verwendung der VBA-Anwendung. „Evaluate“ funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.</span><span class="sxs-lookup"><span data-stu-id="03067-2129">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-2130">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-2130">Outlook</span></span>

- <span data-ttu-id="03067-2131">Es wurde ein Problem behoben, das dazu führte, dass Benutzer gelegentlich einen Absturz feststellten, wenn Sie den X-Knopf auf ihrer Maus verwendeten.</span><span class="sxs-lookup"><span data-stu-id="03067-2131">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="03067-2132">Project</span><span class="sxs-lookup"><span data-stu-id="03067-2132">Project</span></span>

- <span data-ttu-id="03067-2133">Wenn Vorgänger/Nachfolger-Daten in einer Maske bearbeitet werden, wird ein zusätzliches ProjectBeforeTaskChangeevent ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="03067-2133">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="03067-2134">Word</span><span class="sxs-lookup"><span data-stu-id="03067-2134">Word</span></span>

- <span data-ttu-id="03067-2135">Es wurde ein Problem behoben, das dazu führte, dass Benutzer gelegentlich einen Absturz feststellten, wenn Sie den X-Knopf auf ihrer Maus verwendeten.</span><span class="sxs-lookup"><span data-stu-id="03067-2135">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-31"></a><span data-ttu-id="03067-2137">Version 2003: 31. März</span><span class="sxs-lookup"><span data-stu-id="03067-2137">Version 2003: March 31</span></span>
<span data-ttu-id="03067-2138">*Version 2003 (Build 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="03067-2138">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-2140">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-2140">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="03067-2141">Access</span><span class="sxs-lookup"><span data-stu-id="03067-2141">Access</span></span>

- <span data-ttu-id="03067-2142">**Aufgabenbereich "Tabellen hinzufügen":** Der neue Aufgabenbereich "Tabellen hinzufügen" von Access ist endlich da!</span><span class="sxs-lookup"><span data-stu-id="03067-2142">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="03067-2143">Mit dieser Funktion können Sie einfach auswählen/mehrfach auswählen, welche Tabellen sie in einem Abfragefenster hinzufügen/entfernen möchten, ohne zum Dialogfeld "Tabellen anzeigen" für Abfragen und für die Beziehungsansicht zu navigieren.</span><span class="sxs-lookup"><span data-stu-id="03067-2143">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="03067-2144">Dazu gehört auch eine neue Registerkarte "Verknüpfungen", um verknüpfte Tabellen anzuzeigen, ein Suchfeld, um die aktuelle Liste zu filtern, "Drag & Drop"-Verhalten und mehr!</span><span class="sxs-lookup"><span data-stu-id="03067-2144">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-2147">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-2147">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="03067-2148">Project</span><span class="sxs-lookup"><span data-stu-id="03067-2148">Project</span></span>

- <span data-ttu-id="03067-2149"><span style="display:inline !important;">Es wurde ein Problem behoben, bei dem der Benutzer keine zeitgesteuerte Baseline-Arbeit eingeben konnte, wenn die Einstellung zum Schutz der tatsächlichen Arbeit aktiviert ist.</span></span><span class="sxs-lookup"><span data-stu-id="03067-2149"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-25"></a><span data-ttu-id="03067-2151">Version 2003: 25. März</span><span class="sxs-lookup"><span data-stu-id="03067-2151">Version 2003: March 25</span></span>
<span data-ttu-id="03067-2152">*Version 2003 (Build 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="03067-2152">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="03067-2153">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="03067-2153">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="03067-2154">Version 2003: 23. März</span><span class="sxs-lookup"><span data-stu-id="03067-2154">Version 2003: March 23</span></span>
<span data-ttu-id="03067-2155">*Version 2003 (Build 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="03067-2155">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="03067-2156">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="03067-2156">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="03067-2157">Version 2003: 21. März</span><span class="sxs-lookup"><span data-stu-id="03067-2157">Version 2003: March 21</span></span>
<span data-ttu-id="03067-2158">*Version 2003 (Build 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="03067-2158">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-2160">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-2160">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-2161">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-2161">Outlook</span></span>

- <span data-ttu-id="03067-2162">**An Besprechungen teilnehmen, ohne den Posteingang zu verlassen:** Sie brauchen nicht zu Ihrem Kalender zu wechseln, um an Onlinebesprechungen teilzunehmen.</span><span class="sxs-lookup"><span data-stu-id="03067-2162">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="03067-2163">Wenn der Kalender im Aufgabenbereich angeheftet ist, können Sie mit nur einem Klick an einer Besprechung teilnehmen.</span><span class="sxs-lookup"><span data-stu-id="03067-2163">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="03067-2164">**Visuelle Aktualisierung des Kalenders:** Letztes Jahr haben wir die E-Mail-Erfahrung visuell aufgefrischt, und dieses Jahr ist der Kalender mit einem Facelifting an der Reihe!</span><span class="sxs-lookup"><span data-stu-id="03067-2164">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="03067-2165">Die Aktualisierungen sind frisch, aber vertraut, so dass Sie als erfahrener Outlook-Benutzer sofort einsteigen und produktiver sein können.</span><span class="sxs-lookup"><span data-stu-id="03067-2165">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="03067-2166">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-2166">PowerPoint</span></span>

- <span data-ttu-id="03067-2167">**Aktualisieren von Folien während der Bildschirmpräsentation:** Aktualisieren Sie Folien, die von anderen Autoren während Ihrer Präsentation geändert wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-2167">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-16"></a><span data-ttu-id="03067-2169">Version 2003: 16. März</span><span class="sxs-lookup"><span data-stu-id="03067-2169">Version 2003: March 16</span></span>
<span data-ttu-id="03067-2170">*Version 2003 (Build 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="03067-2170">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-2172">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-2172">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-2173">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-2173">Excel</span></span>

- <span data-ttu-id="03067-2174">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="03067-2174">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-2175">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-2175">Outlook</span></span>

- <span data-ttu-id="03067-2176">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="03067-2176">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="03067-2177">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-2177">PowerPoint</span></span>

- <span data-ttu-id="03067-2178">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="03067-2178">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="03067-2179">Word</span><span class="sxs-lookup"><span data-stu-id="03067-2179">Word</span></span>

- <span data-ttu-id="03067-2180">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="03067-2180">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="03067-2181">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-2181">Office Suite</span></span>

- <span data-ttu-id="03067-2182">**Bereiche im Registerkartenformat:** Jetzt können Sie über die Registerkarten-Benutzeroberfläche auf der rechten Seite der App zwischen mehreren Bereichen wechseln.</span><span class="sxs-lookup"><span data-stu-id="03067-2182">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="03067-2183">Die Benutzeroberfläche wird nur angezeigt, wenn Sie mehr als 2 Fenster geöffnet haben.</span><span class="sxs-lookup"><span data-stu-id="03067-2183">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-2186">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-2186">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-2187">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-2187">Excel</span></span>

- <span data-ttu-id="03067-2188">Es wurde ein Problem behoben, bei dem externe Links beim Füllen nicht aktualisiert werden, wenn das Quellbuch geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="03067-2188">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-2189">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-2189">Outlook</span></span>

- <span data-ttu-id="03067-2190">Es wurde ein Problem behoben, das dazu führte, dass der Outlook-Prozess nach dem Beenden im Task-Manager fortbestand.</span><span class="sxs-lookup"><span data-stu-id="03067-2190">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-10"></a><span data-ttu-id="03067-2192">Version 2003: 10. März</span><span class="sxs-lookup"><span data-stu-id="03067-2192">Version 2003: March 10</span></span>
<span data-ttu-id="03067-2193">*Version 2003 (Build 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="03067-2193">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="03067-2194">Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="03067-2194">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)
### <a name="feature-updates"></a><span data-ttu-id="03067-2196">Funktionsupdates</span><span class="sxs-lookup"><span data-stu-id="03067-2196">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="03067-2197">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-2197">Excel</span></span>
- <span data-ttu-id="03067-2198">**Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern.</span><span class="sxs-lookup"><span data-stu-id="03067-2198">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="03067-2199">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-2199">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="03067-2200">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-2200">PowerPoint</span></span>
- <span data-ttu-id="03067-2201">**Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern.</span><span class="sxs-lookup"><span data-stu-id="03067-2201">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="03067-2202">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-2202">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="03067-2203">Word</span><span class="sxs-lookup"><span data-stu-id="03067-2203">Word</span></span>
- <span data-ttu-id="03067-2204">**Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern.</span><span class="sxs-lookup"><span data-stu-id="03067-2204">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="03067-2205">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="03067-2205">Learn more</span></span>](/microsoft-365/compliance/encryption-sensitivity-labels?preserve-view=true&view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="03067-2206">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-2206">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-2207">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-2207">Excel</span></span>

- <span data-ttu-id="03067-2208">Ein kosmetisches Problem wurde behoben, bei dem die Schaltfläche "OK" im Dialogfeld "Datei\Optionen" abgeblendet angezeigt, die Funktionalität aber nicht beeinträchtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2208">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="03067-2209">Es wurde ein Problem behoben, das möglicherweise beim Umbenennen von Pivot-Tabellenmaßen aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="03067-2209">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="03067-2210">Ein Problem wurde behoben, bei dem der Text in einem Datenschnitt in der Druckvorschau nicht ordnungsgemäß skaliert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2210">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="03067-2211">Es wurde ein Leistungsproblem behoben, das möglicherweise bei der Verwendung eines VBA-Makros zum Löschen des Inhalts eines Bereichs aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="03067-2211">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="03067-2212">Es wurde ein Problem behoben, das zum Blinken der Benutzeroberfläche führte, wenn Benutzer ein Makro ausführten, das mit dem Menüband interagierte.</span><span class="sxs-lookup"><span data-stu-id="03067-2212">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="03067-2213">Es wurde ein Problem behoben, bei dem CSV-Dateien falsch geladen wurden, wenn das erste Wort in der Datei TABLE lautete.</span><span class="sxs-lookup"><span data-stu-id="03067-2213">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="03067-2214">Es wurde ein Problem behoben, bei dem es zu Abstürzen kommen konnte, wenn Benutzer zwischen zwei Arbeitsmappen mit unterschiedlichen Zoomstufen wechselten.</span><span class="sxs-lookup"><span data-stu-id="03067-2214">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="03067-2215">Ein Problem wurde behoben, bei dem CUBEWERT-Funktionen manchmal ein falsches Ergebnis zurückgaben.</span><span class="sxs-lookup"><span data-stu-id="03067-2215">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="03067-2216">Diese Änderung behebt einen Laufzeitfehler im Objektmodell und verhindert einen möglichen Absturz der App (Excel, Word), wenn Add-Ins nach Hostelementen in Dokumenten/Arbeitsblättern fragen, die Formen mit noSelect-Sperren enthalten.</span><span class="sxs-lookup"><span data-stu-id="03067-2216">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="03067-2217">Behebt ein Problem, durch das Outlook beim Synchronisieren der Einstellungen abstürzte.</span><span class="sxs-lookup"><span data-stu-id="03067-2217">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="03067-2218">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-2218">Outlook</span></span>

- <span data-ttu-id="03067-2219">Ein Problem wurde behoben, bei dem das Erstellen einer Regel mit Outlook Web App auf dem Exchange-Server nicht beibehalten werden konnte und zu einem Konflikt geführt hat.</span><span class="sxs-lookup"><span data-stu-id="03067-2219">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="03067-2220">Es wurde ein Problem behoben, durch das Outlook beim Synchronisieren der Einstellungen abstürzte.</span><span class="sxs-lookup"><span data-stu-id="03067-2220">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="03067-2221">Es wurde ein Problem mit Outlook im dunklen Modus behoben, wird möglicherweise die Dropdownliste im Feld "Von:" nicht angezeigt.</span><span class="sxs-lookup"><span data-stu-id="03067-2221">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="03067-2222">Es wurde ein Problem behoben, das dazu führte, dass Outlook in einigen Szenarien unerwartet Protokollausgaben erzeugte, selbst wenn die Protokollierung ausgeschaltet war.</span><span class="sxs-lookup"><span data-stu-id="03067-2222">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="03067-2223">Es wurde ein Problem behoben, das dazu führte, dass Benutzer keine Nachrichten in öffentlichen Ordnern öffnen konnten, wenn Outlook über Nacht laufen gelassen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2223">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="03067-2224">Es wurde eine Racebedingung behoben, bei der die Schaltflächen "Zulassen" und "Verweigern" auf der Seite "Berechtigungen" während des Authentifizierungsworkflows beim Hinzufügen eines Google Mail-Kontos deaktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="03067-2224">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="03067-2225">Ein Problem wurde behoben, durch das Benutzer den Zugriff auf das Dialogfeld &quot;Frei/Gebucht-Optionen&quot; der Kalenderberechtigungen verloren.</span><span class="sxs-lookup"><span data-stu-id="03067-2225">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="03067-2226">Es wurde ein Problem behoben, das zur Warnung &quot;Leider besteht ein Problem beim Öffnen dieses Elements&quot; führen kann, wenn Sie bestimmte Besprechungsserien-Instanzen öffnen, die aus einer anderen Zeitzone gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-2226">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="03067-2227">Es wurde ein Problem behoben, durch das Benutzer eine MSG-Datei möglicherweise nicht mehr öffnen können, nachdem die eine Anlage aus dieser Nachricht durch Ziehen und Ablegen verschoben haben.</span><span class="sxs-lookup"><span data-stu-id="03067-2227">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="03067-2228">Ein Problem wurde behoben, bei dem der Dateiname nach dem Hochladen einer Dateianlage aus Outlook nach OneDrive möglicherweise geändert wird, wenn der Name der Anlage eine Klammer enthält.</span><span class="sxs-lookup"><span data-stu-id="03067-2228">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="03067-2229">Es wurde ein Problem behoben, durch das Benutzer über den Datei-Explorer eine Datei nicht als Anlage zu einer E-Mail-Nachricht hinzufügen konnten, wenn diese Datei in einer anderen Anwendung geöffnet war.</span><span class="sxs-lookup"><span data-stu-id="03067-2229">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="03067-2230">Es wurde ein Problem behoben, durch das Outlook beim Synchronisieren der Einstellungen abstürzte.</span><span class="sxs-lookup"><span data-stu-id="03067-2230">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="03067-2231">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-2231">PowerPoint</span></span>

- <span data-ttu-id="03067-2232">Ein Problem wurde behoben, bei dem die empfohlenen Miniaturansichten blinkten, wenn Sie mit der Maus auf die Miniaturansichten gingen.</span><span class="sxs-lookup"><span data-stu-id="03067-2232">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="03067-2233">In einigen Fällen kann dies dazu führen, dass PowerPoint abstürzt.</span><span class="sxs-lookup"><span data-stu-id="03067-2233">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="03067-2234">Ein kosmetisches Problem wurde behoben, bei dem die Schaltfläche "OK" im Dialogfeld "Datei\Optionen" abgeblendet angezeigt, die Funktionalität aber nicht beeinträchtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2234">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="03067-2235">Es wurde ein Problem behoben, das dazu führen konnte, dass ein Dokument, das ein Excel-Diagramm enthält, nicht in PowerPoint oder Word gespeichert werden konnte.</span><span class="sxs-lookup"><span data-stu-id="03067-2235">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="03067-2236">Project</span><span class="sxs-lookup"><span data-stu-id="03067-2236">Project</span></span>

- <span data-ttu-id="03067-2237">Ein Problem wurde behoben, bei dem "Vorgang Prozent abgeschlossen" fälschlicherweise in einen Wert kleiner als 100 % geändert wurde, nachdem der Vorgang als abgeschlossen gekennzeichnet wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2237">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="03067-2238">Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.</span><span class="sxs-lookup"><span data-stu-id="03067-2238">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="03067-2239">Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-2239">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="03067-2240">Visio</span><span class="sxs-lookup"><span data-stu-id="03067-2240">Visio</span></span>

- <span data-ttu-id="03067-p238">Im Shape-Infobereich wurden im Abschnitt „Shape-Daten“ inkonsistente Details in Bezug auf die Datei angezeigt, wie wenn diese in Visio Desktop geöffnet wurde. Dies wurde nun behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-p238">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop. It has now been fixed.</span></span>

- <span data-ttu-id="03067-2243">In Versionen vor 2016 importierte Bitmaps wurden aufgrund einiger Sicherheitsüberprüfungen nicht wiedergegeben.</span><span class="sxs-lookup"><span data-stu-id="03067-2243">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="03067-2244">Dieses Problem wurde im Visio-Abonnement behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-2244">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="03067-2245">Word</span><span class="sxs-lookup"><span data-stu-id="03067-2245">Word</span></span>

- <span data-ttu-id="03067-2246">Es wurde ein Problem behoben, bei dem Kommentarkarten nicht immer hervorgehoben werden, wenn der Mauszeiger über die Kommentarkarte bewegt wird.</span><span class="sxs-lookup"><span data-stu-id="03067-2246">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="03067-2247">Behebt ein Problem, das dazu geführt hat, dass beim Navigieren über eine Kommentarkarte mit der Tabulatortaste der Fokus auf dem Bearbeitungsfeld für den Kommentar nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2247">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="03067-2248">Ein kosmetisches Problem wurde behoben, bei dem die Schaltfläche "OK" im Dialogfeld "Datei\Optionen" abgeblendet angezeigt, die Funktionalität aber nicht beeinträchtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2248">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="03067-p240">Während einer aktiven Sitzung zur gemeinsamen Dokumenterstellung kann das direkte Hinzufügen eines Bildes in eine Kommentarkarte dazu führen, dass ein Tag hinzugefügt wird. Dieses Problem wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="03067-p240">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag. This issue has been fixed.</span></span>

- <span data-ttu-id="03067-2251">Das Einfügen eines Steuerelements (beispielsweise eines Textinhaltssteuerelements) in eine Gleichung und das anschließende Speichern und Öffnen der Datei führte zu einem Fehler aufgrund nicht lesbaren Inhalts.</span><span class="sxs-lookup"><span data-stu-id="03067-2251">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="03067-2252">Ein Problem wurde behoben, aufgrund dessen das Speichern einer zuvor kennwortgeschützten Datei in einem Cloudspeicher nicht funktioniert hat.</span><span class="sxs-lookup"><span data-stu-id="03067-2252">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="03067-2253">Es wurde ein Problem mit der compare-Funktion für Dokumente behoben, die für die Bearbeitung geschützt waren.</span><span class="sxs-lookup"><span data-stu-id="03067-2253">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="03067-2254">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-2254">Office Suite</span></span>

- <span data-ttu-id="03067-2255">Beim Verwenden der Metadateneigenschaften MultiChoice/Verweis/Verwaltet mit Word/Excel/PowerPoint-Dokumenten und dem Speichern in einer SharePoint-Dokumentbibliothek waren diese Eigenschaften bisher auf 255 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="03067-2255">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="03067-2256">Wenn diese Eigenschaften 255 Zeichen überschritten, konnten solche Dokumente nicht gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="03067-2256">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="03067-2257">Mit dieser Änderung wurde dieser Grenzwert auf 2048 Zeichen erhöht.</span><span class="sxs-lookup"><span data-stu-id="03067-2257">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="03067-2258">Behebt ein Problem mit Word/Excel/PowerPoint, bei dem der User-Principal-Name (UPN) nicht mehr die Groß-/Kleinschreibung beachtet, was zu weniger Fehlern beim Arbeiten mit Dateien in SharePoint führt.</span><span class="sxs-lookup"><span data-stu-id="03067-2258">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="03067-2259">Ein Problem wurde behoben, das dazu führte, dass beim Öffnen mehrerer Dokumente in Word/Excel/PowerPoint aus derselben SharePoint-Bibliothek lediglich das erste geöffnete Dokument auf Richtlinienkonformität gescannt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2259">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSWENDE)

## <a name="version-2002-march-05"></a><span data-ttu-id="03067-2261">Version 2002: 05. März</span><span class="sxs-lookup"><span data-stu-id="03067-2261">Version 2002: March 05</span></span>
<span data-ttu-id="03067-2262">*Version 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="03067-2262">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="03067-2263">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="03067-2263">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="03067-2264">Version 2002: 04. März</span><span class="sxs-lookup"><span data-stu-id="03067-2264">Version 2002: March 04</span></span>
<span data-ttu-id="03067-2265">*Version 2002 (Build 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="03067-2265">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-2267">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-2267">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="03067-2268">Project</span><span class="sxs-lookup"><span data-stu-id="03067-2268">Project</span></span>
- <span data-ttu-id="03067-2269">Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-2269">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="03067-2270">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-2270">Office Suite</span></span>
- <span data-ttu-id="03067-2271">Behebt ein Problem, das dazu geführt hat, dass beim Öffnen mehrerer Dokumente in Word/Excel/PowerPoint aus derselben SharePoint-Bibliothek lediglich das erste geöffnete Dokument auf Richtlinienkonformität gescannt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2271">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSWENDE)

## <a name="version-2002-march-01"></a><span data-ttu-id="03067-2273">Version 2002: 01. März</span><span class="sxs-lookup"><span data-stu-id="03067-2273">Version 2002: March 01</span></span>
<span data-ttu-id="03067-2274">*Version 2002 (Build 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="03067-2274">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="03067-2275">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-2275">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-2276">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-2276">Outlook</span></span>

- <span data-ttu-id="03067-2277">Behebt ein Problem, das bewirkt hatte, dass Anwendungen von Drittanbietern keine E-Mail-Nachrichten mehr senden konnten.</span><span class="sxs-lookup"><span data-stu-id="03067-2277">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2002-february-24"></a><span data-ttu-id="03067-2279">Version 2002: 24. Februar</span><span class="sxs-lookup"><span data-stu-id="03067-2279">Version 2002: February 24</span></span>
<span data-ttu-id="03067-2280">*Version 2002 (Build 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="03067-2280">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="03067-2281">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="03067-2281">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="03067-2282">Version 2002: 22. Februar</span><span class="sxs-lookup"><span data-stu-id="03067-2282">Version 2002: February 22</span></span>
<span data-ttu-id="03067-2283">*Version 2002 (Build 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="03067-2283">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="03067-2284">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="03067-2284">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="03067-2285">Version 2002: 21. Februar</span><span class="sxs-lookup"><span data-stu-id="03067-2285">Version 2002: February 21</span></span>
<span data-ttu-id="03067-2286">*Version 2002 (Build 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="03067-2286">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-2288">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-2288">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="03067-2289">Zugriff</span><span class="sxs-lookup"><span data-stu-id="03067-2289">Access</span></span>

- <span data-ttu-id="03067-2290">**Seien Sie beim Arbeiten im Abfrage-Designer, in der SQL-Ansicht und im Fenster „Beziehungen“ produktiver:** Klicken Sie zum Öffnen, Gestalten, Vergrößern oder Verkleinern und Ausblenden mit der rechten Maustaste auf die betreffende Tabelle.</span><span class="sxs-lookup"><span data-stu-id="03067-2290">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="03067-2291">Suchen und Ersetzen von Text in der SQL-Ansicht.</span><span class="sxs-lookup"><span data-stu-id="03067-2291">Search and replace text in SQL View.</span></span> <span data-ttu-id="03067-2292">Auswählen mehrerer Tabellen im Fenster „Beziehungen“.</span><span class="sxs-lookup"><span data-stu-id="03067-2292">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-2293">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-2293">Outlook</span></span>

- <span data-ttu-id="03067-2294">**Neue Benutzeroberfläche für WLAN-Netzwerke mit Anmeldung:** Sind Sie schon einmal einem WLAN-Netzwerk beigetreten, mit dem Sie sich anmelden mussten?</span><span class="sxs-lookup"><span data-stu-id="03067-2294">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="03067-2295">Outlook erkennt dies jetzt und hilft Ihnen, eine Verbindung zu herstellen.</span><span class="sxs-lookup"><span data-stu-id="03067-2295">Outlook now detects this and helps you get connected.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-2298">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-2298">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="03067-2299">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-2299">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="03067-2300">Ein Problem wurde behoben, bei dem CUBEWERT-Funktionen manchmal ein falsches Ergebnis zurückgaben.&nbsp;<span style="display:inline !important;"></span></span><span class="sxs-lookup"><span data-stu-id="03067-2300">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;<span style="display:inline !important;"></span></span></span><br>


### <a name="outlook"></a><span data-ttu-id="03067-2301">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-2301">Outlook</span></span>

- <span data-ttu-id="03067-2302">Behebt ein Problem, das dazu führte, dass Kommas im Ortsfeld einer Besprechung in Semikolons umgewandelt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-2302">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>


- <span data-ttu-id="03067-2303">Behebt ein Problem, das zu einem Absturz führen könnte, wenn dasselbe Element in mehreren Fenstern angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="03067-2303">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>


- <span data-ttu-id="03067-2304">Behebt ein Problem, das dazu führte, dass Outlook unerwartet alle E-Mails synchronisierte, selbst wenn der Synchronisierungsschieberegler auf eine kleinere Einstellung eingestellt ist.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="03067-2304">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span>


- <span data-ttu-id="03067-2305">Behebt ein Problem, das dazu führte, dass für Benutzer mit dem schwarzen Design die Dropdownliste &quot;Von&quot; als weißer Text auf weißem Hintergrund angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2305">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>


- <span data-ttu-id="03067-2306"><span style="display:inline !important;">Diese Änderung stellt die Fähigkeit wieder her, mehrzeilige Betreffzeilen im Nachrichtenkopf anzuzeigen.</span></span><span class="sxs-lookup"><span data-stu-id="03067-2306"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-february-18"></a><span data-ttu-id="03067-2308">Version 2002: 18. Februar</span><span class="sxs-lookup"><span data-stu-id="03067-2308">Version 2002: February 18</span></span>
<span data-ttu-id="03067-2309">*Version 2002 (Build 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="03067-2309">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="03067-2310">Version 2002: 11. Februar</span><span class="sxs-lookup"><span data-stu-id="03067-2310">Version 2002: February 11</span></span>
<span data-ttu-id="03067-2311">*Version 2002 (Build 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="03067-2311">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="03067-2312">Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="03067-2312">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="03067-2314">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="03067-2314">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="03067-2315">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-2315">Outlook</span></span>

- <span data-ttu-id="03067-2316">**Ziehen Sie E-Mails in eine Gruppe, die Sie besitzen:** Verschieben und Kopieren von Nachrichten und Unterhaltungen, indem Sie diese aus Ihrem Posteingang ziehen.</span><span class="sxs-lookup"><span data-stu-id="03067-2316">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="03067-2317">Die von ihnen gezogenen Nachrichten werden für alle Gruppenmitglieder freigegeben.</span><span class="sxs-lookup"><span data-stu-id="03067-2317">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="03067-2318">Word</span><span class="sxs-lookup"><span data-stu-id="03067-2318">Word</span></span>

- <span data-ttu-id="03067-2319">**Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.</span><span class="sxs-lookup"><span data-stu-id="03067-2319">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="03067-2320">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-2320">Office Suite</span></span>

- <span data-ttu-id="03067-2321">**Übersichtlichere Statusleistensymbole:** Statusleistensymbole sind jetzt einfacher zu sehen.</span><span class="sxs-lookup"><span data-stu-id="03067-2321">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="03067-2324">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="03067-2324">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="03067-2325">Zugriff</span><span class="sxs-lookup"><span data-stu-id="03067-2325">Access</span></span>

- <span data-ttu-id="03067-2326">Access-Vorlagen sollten nicht länger dazu führen, dass Anhangsspalten in einer Datenbank fehlschlagen.</span><span class="sxs-lookup"><span data-stu-id="03067-2326">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="03067-2327">Nachdem Sie eine Vorlage instanziiert haben, sollten Sie nun in der Lage sein, Ihrer Datenbank ein Anhangsfeld hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="03067-2327">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="03067-p246">Dieses Update behebt ein Problem bei der Verwendung einer ADOdb. Das Recorder-Objekt in VB-Code kann fälschlicherweise einen Fehler melden.</span><span class="sxs-lookup"><span data-stu-id="03067-p246">This update fixes an issue where using an ADODB. Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="03067-2330">Dieses Update behebt ein Problem, das dazu führen kann, dass Microsoft Access eine Identitätsspalte in einer verknüpften SQL-Server-Tabelle nicht identifiziert, was dazu führen kann, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.</span><span class="sxs-lookup"><span data-stu-id="03067-2330">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="03067-2331">Excel</span><span class="sxs-lookup"><span data-stu-id="03067-2331">Excel</span></span>

- <span data-ttu-id="03067-2332">Es wurde ein Problem behoben, bei dem Kommentarbefehle im Kontextmenü nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-2332">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="03067-2333">Es wurde ein Problem behoben, durch das bei einigen Nutzern Abstürze auftraten, wenn Text in Spalten mit Zellen mit einem übergelaufenem Array konvertiert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2333">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="03067-2334">Ein Problem wurde behoben, das dazu geführt hatte, dass Excel bei Verschieben von Text in Spalten mit dynamischen Pfeilern abgestürzt ist.</span><span class="sxs-lookup"><span data-stu-id="03067-2334">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="03067-2335">Outlook</span><span class="sxs-lookup"><span data-stu-id="03067-2335">Outlook</span></span>

- <span data-ttu-id="03067-2336">Ein Problem wurde behoben, das dazu geführt hatte, dass beim Durchblättern des Kalanders in der Monatsansicht die vorangegangenen Kalenderereignisse nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-2336">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="03067-2337">Ordner, die unter "Favoriten" im linken Navigationsbereich gespeichert sind, können zeitweise verschwinden.</span><span class="sxs-lookup"><span data-stu-id="03067-2337">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="03067-2338">Es wurde ein Problem behoben, bei dem beim Angeben einer ungültigen Absenderadresse ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2338">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="03067-2339">Es wurde ein Problem behoben, durch das die Option zum Deaktivieren der Hervorhebung markierter Elemente in einigen Szenarien nicht berücksichtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2339">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="03067-2340">Es wurde ein Problem behoben, bei dem es durch das Abbrechen der Kontoeinrichtung einen Absturz gab.</span><span class="sxs-lookup"><span data-stu-id="03067-2340">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="03067-2341">Problem behoben, bei dem für auf Grundlage einer Aufbewahrungsrichtlinie ablaufende E-Mails zwei Beschriftungen angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-2341">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="03067-2342">Eine mit der Aussage, dass die E-Mail in einem Tag, die andere, dass die E-Mail in zwei Tagen abläuft.</span><span class="sxs-lookup"><span data-stu-id="03067-2342">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="03067-2343">Es wurde ein Problem behoben, bei dem beim Anzeigen von mehr als 30 Kalendern in einer Citrix-Umgebung ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2343">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="03067-2344">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="03067-2344">PowerPoint</span></span>

- <span data-ttu-id="03067-2345">Ein Problem wurde behoben, bei dem Freihandelemente in einer PowerPoint-Freihandanimation nicht vollständig gerendert wurde oder übersprungen wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2345">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="03067-2346">Ein Problem wurde behoben, das dazu geführt hatte, dass PowerPoint Nach dem Schließen einer Datei diese nicht sofort aus der Sammlung von Präsentationen entfernt hat, wenn Ereignisverarbeiter ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="03067-2346">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="03067-2347">Dadurch war die Zahl der vom Objektmodell gemeldeten, geöffneten Präsentationen falsch und das Herunterfahren von PowerPoint wurde verhindert.</span><span class="sxs-lookup"><span data-stu-id="03067-2347">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="03067-2348">Ein Problem mit dem Textmarker wurde behoben: Weißer Text mit dunkleren Textmarkerfarben wurde Schwarz mit Graustufen gedruckt.</span><span class="sxs-lookup"><span data-stu-id="03067-2348">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="03067-2349">Project</span><span class="sxs-lookup"><span data-stu-id="03067-2349">Project</span></span>

- <span data-ttu-id="03067-2350">Es wurde ein Problem behoben, bei dem 100% Aufgaben vom Typ „feste Dauer“ fälschlicherweise zu weniger als 100% erledigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-2350">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="03067-2351">Word</span><span class="sxs-lookup"><span data-stu-id="03067-2351">Word</span></span>

- <span data-ttu-id="03067-2352">Beim Aktualisieren eines Inhaltsverzeichnisses bzw. dem Blättern durch dieses wird manchmal möglicherweise ein grauer Bereich auf dem Dokument angezeigt.</span><span class="sxs-lookup"><span data-stu-id="03067-2352">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="03067-2353">Es wurde ein Problem mit der Verwendung von „Durchsuchen“ zum Speichern einer Datei behoben, das nicht funktioniert hat, wenn ein Kommentar geschrieben, jedoch nicht gepostet worden war und der Benutzer versucht hatte, die Datei zu speichern.</span><span class="sxs-lookup"><span data-stu-id="03067-2353">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="03067-2354">Ein Problem wurde behoben, das dazu geführt hatte, dass beim Hin- und Herwechseln zwischen Kommentar-Karten manchmal der anfänglich ausgewählte Kommentar mit einer Auswahlhervorhebung angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2354">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="03067-2355">Es wurde ein Problem behoben, bei dem die kursive Formatierung verloren ging, nachdem ein Kommentar bearbeitet, der Text kursiv geschrieben und anschließend veröffentlicht wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2355">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="03067-2356">Problem behoben, bei dem ein Kommentarhinweis im Lesemodus mit Inverser Seitenfarbe nicht sichtbar war.</span><span class="sxs-lookup"><span data-stu-id="03067-2356">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="03067-2357">Ein Problem wurde behoben, bei dem die Entwurfsversion eines Stammkommentars bei der gemeinsamen Dokumenterstellung zeitweise nicht beibehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2357">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="03067-2358">Wenn „SlideTrack“ aktiviert und der Bereich „Kommentare“ geschlossen ist, kann der Bereich „Kommentare“ mit STRG+ALT+M möglicherweise nicht geöffnet werden.</span><span class="sxs-lookup"><span data-stu-id="03067-2358">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="03067-2359">Es wurde ein Problem behoben, das dazu geführt hatte, dass beim Hinzufügen von @mention in einer Tabelle die Fehlermeldung „Eine Tabelle in diesem Dokument ist beschädigt“ generiert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2359">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="03067-2360">Problem behoben, bei dem Kommentarbefehle (Kommentar bearbeiten, auf Kommentar antworten, Kommentar löschen, Kommentar auflösen) nicht im Kontextmenü von Kommentaren angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="03067-2360">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="03067-2361">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="03067-2361">Office Suite</span></span>

- <span data-ttu-id="03067-2362">Behebt ein Problem, das dazu geführt hat, dass Korrekturhilfe-Paket Norwegen Nynorsk (nn-no) nicht ordnungsgemäß installiert wurde.</span><span class="sxs-lookup"><span data-stu-id="03067-2362">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="03067-2363">Diese Änderung behebt gemeldete Probleme mit Grafikadaptern, die die integrierte Intel-GPU nutzen.</span><span class="sxs-lookup"><span data-stu-id="03067-2363">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

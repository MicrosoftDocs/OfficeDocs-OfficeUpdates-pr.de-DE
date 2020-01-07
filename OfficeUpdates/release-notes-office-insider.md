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
ms.openlocfilehash: b136c43128f6f995057f35c7b47c9e517c457097
ms.sourcegitcommit: 78fb0c27e6b75aefcfcbd1b0ac7d17c1b53f86e0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/07/2020
ms.locfileid: "40951093"
---
# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="161f7-103">Anmerkungen zu dieser Version für Office-Insider</span><span class="sxs-lookup"><span data-stu-id="161f7-103">Release Notes for Office Insiders</span></span>

<span data-ttu-id="161f7-104">Dieser Artikel enthält Versionshinweise zu Insider-Builds von Word, Excel, PowerPoint, Outlook, Access und Project für Windows Desktop.</span><span class="sxs-lookup"><span data-stu-id="161f7-104">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="161f7-105">Jede Woche heben wir interessante neuer Features, wichtige Fixes und wesentliche Probleme hervor, über die wir Sie gerne informieren möchten.</span><span class="sxs-lookup"><span data-stu-id="161f7-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="161f7-106">Beachten Sie, dass das Rollout von Funktionen (und manchmal auch Fixes) für Insider häufig über einen längeren Zeitraum erfolgt.</span><span class="sxs-lookup"><span data-stu-id="161f7-106">Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time.</span></span> <span data-ttu-id="161f7-107">Auf diese Weise können wir sicherstellen, dass alles reibungslos funktioniert, bevor das Feature für ein breiteres Publikum bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="161f7-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="161f7-108">Wenn also im Folgenden etwas nicht beschrieben wird, machen Sie sich keine Sorgen, es wird bald behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!NOTE]
> - <span data-ttu-id="161f7-109">Versionshinweise werden wöchentlich veröffentlicht und können eine Kompilierung mehrerer Builds sein.</span><span class="sxs-lookup"><span data-stu-id="161f7-109">Release notes are posted weekly and may be a compilation of multiple builds.</span></span>
> - <span data-ttu-id="161f7-110">Das Veröffentlichungsdatum der Versionshinweise stimmt möglicherweise nicht mit dem tatsächlichen Veröffentlichungsdatum des Builds überein.</span><span class="sxs-lookup"><span data-stu-id="161f7-110">The release notes publication date may not match the actual build release date.</span></span>
> - <span data-ttu-id="161f7-111">Microsoft Teams für vorhandene Installationen von Office 365 ProPlus – ab Ende Juni wird Microsoft Teams beim Aktualisieren dieser Installationen in bestehende Installationen von Office 365 ProPlus (und Office 365 Business) einbezogen.</span><span class="sxs-lookup"><span data-stu-id="161f7-111">Microsoft Teams on existing installations of Office 365 ProPlus - Beginning in late June, Microsoft Teams will be included in existing installations of Office 365 ProPlus (and Office 365 Business) upon updates of these installations.</span></span> <span data-ttu-id="161f7-112">Ab welchem Datum Microsoft Teams hinzugefügt wird, hängt davon ab, welchen Updatekanal Sie verwenden.</span><span class="sxs-lookup"><span data-stu-id="161f7-112">The date when Teams will be added depends on which update channel you're using.</span></span> <span data-ttu-id="161f7-113">Weitere Informationen hierzu finden Sie unter [Bereitstellen von Microsoft Teams mit Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install).</span><span class="sxs-lookup"><span data-stu-id="161f7-113">Please refer to [Deploy Microsoft Teams with Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install) for additional information.</span></span>

[//]: # (NICHT ENTFERNEN)

## <a name="version-2001-january-03"></a><span data-ttu-id="161f7-115">Version 2001: 03. Januar</span><span class="sxs-lookup"><span data-stu-id="161f7-115">Version 2001: January 03</span></span>
<span data-ttu-id="161f7-116">*Version 2001 (Build 12425.20000)*</span><span class="sxs-lookup"><span data-stu-id="161f7-116">*Version 2001 (Build 12425.20000)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="161f7-118">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="161f7-118">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-119">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-119">Excel</span></span>
- <span data-ttu-id="161f7-120">Einige Rahmenlinien werden auf Papier im Format A4 möglicherweise nicht wie erwartet gedruckt.</span><span class="sxs-lookup"><span data-stu-id="161f7-120">Some border lines may not print as expected on A4 size paper.</span></span>
- <span data-ttu-id="161f7-121">Das Einfügen eines Bildes in die Kopf-/Fußzeile eines Diagrammobjekts auf einem Blatt mit VBA kann zu einem Fehler führen.</span><span class="sxs-lookup"><span data-stu-id="161f7-121">Adding an image to the header/footer of a chart object on a sheet using VBA may result in an error.</span></span>
- <span data-ttu-id="161f7-122">Beim Formatieren einer Diagrammachse ist der Abstand zwischen den Beschriftungen auf 255 Zeichen begrenzt.</span><span class="sxs-lookup"><span data-stu-id="161f7-122">When formatting a chart axis, the interval between labels was limited to 255.</span></span>
- <span data-ttu-id="161f7-123">Ein Problem wurde behoben, bei dem beim Versuch, eine XML-Abfrage zu aktualisieren, deren URL zur Datenquelle abgeschnitten wurde, ein Fehler auftrat.</span><span class="sxs-lookup"><span data-stu-id="161f7-123">Fixed an issue where an error would occur trying to refresh an XML query in which the URL to the datasource was being truncated.</span></span>
- <span data-ttu-id="161f7-124">In der Arbeitsmappenstatistik wird eine Makroanzahl aus allen geöffneten Arbeitsmappen angezeigt, einschließlich der persönlichen Makroarbeitsmappe.</span><span class="sxs-lookup"><span data-stu-id="161f7-124">Workbook Statistics would report a macro count from all open workbooks, including the personal macro workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-125">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-125">Outlook</span></span>
- <span data-ttu-id="161f7-126">Das Wechseln von Ordnern kann zu einem kurzen weißen "Blitz" in der E-Mail-Liste/E-Mail-Vorschau führen.</span><span class="sxs-lookup"><span data-stu-id="161f7-126">Switching folders may result in a brief white 'flash' in the mail list / mail preview.</span></span> <span data-ttu-id="161f7-127">Dieses Verhalten war im dunklen Modus ausgeprägter.</span><span class="sxs-lookup"><span data-stu-id="161f7-127">This behavior was more pronounced in dark mode.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-128">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-128">PowerPoint</span></span>
- <span data-ttu-id="161f7-129">Ein Problem mit dem Objektmodell wurde behoben, bei dem das Aufrufen der Methode "Shape.Paste" dazu führte, dass die eingefügte Form den Fokus erhielt.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="161f7-129">Fixed an Object Model issue where calling Shape.Paste method would result in the pasted shape receiving focus.&nbsp;</span></span>
- <span data-ttu-id="161f7-130">Verbessertes Kopieren-Einfügen-Szenario:&nbsp; Das programmgesteuerte Kopieren einer Form aus einer PowerPoint-Folie und das Einfügen dieser Form in eine andere Folie in einer Schleife konnte mit einem Ausnahmefehler fehlschlagen.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="161f7-130">Improved a copy-paste scenario:&nbsp;Progamatically copying a shape from a PowerPoint slide and pasting it to another slide in a loop could fail with an exception error.&nbsp;</span></span>
- <span data-ttu-id="161f7-131">Animationen in den Abschnittsüberschriften von Folien wurden nach dem Reduzieren und Erweitern von Abschnittsüberschriften nicht korrekt gerendert.</span><span class="sxs-lookup"><span data-stu-id="161f7-131">Animation in the section headers of slides would not render properly after collapsing and expanding section headers.</span></span>

### <a name="project"></a><span data-ttu-id="161f7-132">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-132">Project</span></span>
- <span data-ttu-id="161f7-133">Ein Problem wurde behoben, bei dem der Textumbruch in der Task- und Ressourcennutzungsansicht nicht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="161f7-133">Fixed an issue where text wrapping wasn't working in the task and resource usage views.</span></span>
- <span data-ttu-id="161f7-134">Ein Problem wurde behoben, bei dem der Kostenwert bei Aufgaben möglicherweise nicht korrekt ist, wenn eine Ressource mehrere Kostensätze aufweist.</span><span class="sxs-lookup"><span data-stu-id="161f7-134">Fixed an issue where if a resource has more than one cost rate, cost value on assignments may not be correct.</span></span>

### <a name="word"></a><span data-ttu-id="161f7-135">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-135">Word</span></span>
- <span data-ttu-id="161f7-136">Das Einfügen eines Steuerelements (z. B. eines Textinhaltssteuerelements) in eine Gleichung und das anschließende Speichern und Öffnen der Datei führte zu einem Fehler aufgrund nicht lesbaren Inhalts.</span><span class="sxs-lookup"><span data-stu-id="161f7-136">Inserting a control (such as a Text Content Control) in an equation, then saving and opening the file would result in an un-readable content error.</span></span>
- <span data-ttu-id="161f7-137">Bei der gemeinsamen Dokumenterstellung wird ein Kommentar, der mit Word Online hinzugefügt wurde, auf dem Word-Desktop möglicherweise nicht angezeigt.</span><span class="sxs-lookup"><span data-stu-id="161f7-137">When co-authoring, adding a comment using Word online may not appear in Word desktop.</span></span>

### <a name="office-suite"></a><span data-ttu-id="161f7-138">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="161f7-138">Office Suite</span></span>
- <span data-ttu-id="161f7-139">Die Anzeige eines falschen Ablaufdatums der gültigen Lizenz beim Versuch, eine Einzellizenz zu ändern, wurde entfernt.</span><span class="sxs-lookup"><span data-stu-id="161f7-139">Removed showing an erroneous expiry date of the valid license when trying to change license with only one license.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2001-december-13"></a><span data-ttu-id="161f7-141">Version 2001: 13. Dezember</span><span class="sxs-lookup"><span data-stu-id="161f7-141">Version 2001: December 13</span></span>
<span data-ttu-id="161f7-142">*Version 2001 (Build 12410.20000)*</span><span class="sxs-lookup"><span data-stu-id="161f7-142">*Version 2001 (Build 12410.20000)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="161f7-144">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-144">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="161f7-145">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-145">Outlook</span></span>

- <span data-ttu-id="161f7-146">**Ziehen Sie E-Mails in eine Gruppe, die Sie besitzen:** Verschieben und Kopieren von Nachrichten und Unterhaltungen, indem Sie diese aus Ihrem Posteingang ziehen.</span><span class="sxs-lookup"><span data-stu-id="161f7-146">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="161f7-147">Die von ihnen gezogenen Nachrichten werden für alle Gruppenmitglieder freigegeben.</span><span class="sxs-lookup"><span data-stu-id="161f7-147">Messages you drag will be shared with all group members.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="161f7-150">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="161f7-150">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="161f7-151">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-151">Access</span></span>
- <span data-ttu-id="161f7-152">Das Ausführen einer Verbundabfrage, die auf verknüpfte ODBC-Tabellen verweist und eine ORDER BY-Klausel enthält, stürzt den 64-Bit-Zugriff ab.</span><span class="sxs-lookup"><span data-stu-id="161f7-152">Executing a union query that references linked ODBC table(s) and contains an Order By clause crashes 64 bit Access.</span></span>
- <span data-ttu-id="161f7-153">Das Summieren von Daten aus Verbundsabfragen in Access (O365) kann zu einer Verkürzung der dezimalen Daten führen.</span><span class="sxs-lookup"><span data-stu-id="161f7-153">Summing of data from union queries in Access (O365) may result in truncation of decimal data.</span></span>
- <span data-ttu-id="161f7-154">COM-Schnittstellen für ACE werden nicht für den Einsatz außerhalb von Office-Anwendungen freigegeben.</span><span class="sxs-lookup"><span data-stu-id="161f7-154">COM Interfaces for ACE are not exposed for use outside of Office applications.</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-155">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-155">Excel</span></span>
- <span data-ttu-id="161f7-156">Das Einfügen eines 3D-Modells (animiert oder statisch) und der Versuch, als Bild zu speichern, funktioniert nicht.</span><span class="sxs-lookup"><span data-stu-id="161f7-156">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>
- <span data-ttu-id="161f7-157">Die Kurztaste (Alt + Strg + 7/8), um Feedback aus dem Backstage-Bereich zu starten, steht im Konflikt mit QWERTZ-Tastaturen (AltGr + 7/8).</span><span class="sxs-lookup"><span data-stu-id="161f7-157">The shortkey (Alt+Ctrl + 7/8)  to launch feedback from backstage is in conflict with AZERTY keyboards (Alt-Gr + 7/8).</span></span> <span data-ttu-id="161f7-158">Auswirkung: Benutzer sind möglicherweise nicht in der Lage, einige Zeichen wie: '\' zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="161f7-158">Impact: users may not be able to use some characters such as: '\'.</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-159">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-159">Outlook</span></span>
- <span data-ttu-id="161f7-160">Behebt ein Problem, bei dem E-Mails an die für den Empfänger falsche Adresse gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="161f7-160">Addresses an issue that caused email to be sent to the wrong address for the recipient.</span></span>
- <span data-ttu-id="161f7-161">Behebt ein Problem, das dazu führte, dass Outlook-Benutzern mit &quot;Lesezugriff&quot; auf ein Postfach fälschlicherweise erlaubte, den gelesenen/ungelesenen Status einer Nachricht zu ändern.</span><span class="sxs-lookup"><span data-stu-id="161f7-161">Addresses an issue that caused Outlook to incorrectly allow users with &quot;read&quot; access to a mailbox to change the read/unread state of a message.</span></span>
- <span data-ttu-id="161f7-162">Der Widerruf des Sicherheitszertifikats auf der Website ist für den Produkt Support nicht reproduzierbar.</span><span class="sxs-lookup"><span data-stu-id="161f7-162">The revocation of the security certificate on the web site is not re-producible by Product Support.</span></span> <span data-ttu-id="161f7-163">Die Protokollierung muss hinzugefügt werden, um die Ursache für das Problem zu beheben.</span><span class="sxs-lookup"><span data-stu-id="161f7-163">Logging needs to be added to help root cause the issue.</span></span>
- <span data-ttu-id="161f7-164">Behebt ein Problem, bei dem Benutzer Synchronisationsfehler festgestellt haben.</span><span class="sxs-lookup"><span data-stu-id="161f7-164">Addresses an issue that caused users to see synchronization failures.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-165">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-165">PowerPoint</span></span>
- <span data-ttu-id="161f7-166">Das Einfügen eines 3D-Modells (animiert oder statisch) und der Versuch, als Bild zu speichern, funktioniert nicht.</span><span class="sxs-lookup"><span data-stu-id="161f7-166">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="project"></a><span data-ttu-id="161f7-167">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-167">Project</span></span>
- <span data-ttu-id="161f7-168">Die Aufgabenarbeit wird im Summenrollup für manuell geplante Unteraufgaben nicht berechnet.</span><span class="sxs-lookup"><span data-stu-id="161f7-168">Task work is not calculated in Summary roll-up for manually scheduled child tasks.</span></span>
- <span data-ttu-id="161f7-169">Projekt-VBA-Code, der von einer Multifunktionsleiste aufgerufen wird, funktioniert möglicherweise nicht, wenn versucht wird, serverbasierte Projekte zu speichern.</span><span class="sxs-lookup"><span data-stu-id="161f7-169">Project VBA Code invoked from a Ribbon button may not work when trying to save server-based Projects.</span></span>
- <span data-ttu-id="161f7-170">Wenn Project nicht bereits ausgeführt wird, zeigt das Öffnen von Projektdateien aus einer SharePoint-Dokumentbibliothek einen Fehler an und die Datei wird nicht geöffnet.</span><span class="sxs-lookup"><span data-stu-id="161f7-170">Unless Project is already running, opening Project files from a SharePoint document library displays an error and the file will not open.</span></span>

### <a name="word"></a><span data-ttu-id="161f7-171">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-171">Word</span></span>
- <span data-ttu-id="161f7-172">Das Speichern vorhandener Dateien funktioniert möglicherweise nicht.</span><span class="sxs-lookup"><span data-stu-id="161f7-172">Saving existing files may not work.</span></span>
- <span data-ttu-id="161f7-173">Die Verwendung der Pfeiltasten im Fenster des Editors für Rechtschreibung und Grammatik kann zu intermittierendem Flackern führen.</span><span class="sxs-lookup"><span data-stu-id="161f7-173">Using arrow keys in the Spelling and Grammar editor window may result in intermittent flickering.</span></span>
- <span data-ttu-id="161f7-174">Bei der Behebung einer Nachverfolgung können zugehörige Kommentare nicht in Punktkommentare umgewandelt werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-174">When resolving a follow-up, associated comments may not convert to point comments.</span></span>
- <span data-ttu-id="161f7-175">Das Einfügen eines 3D-Modells (animiert oder statisch) und der Versuch, als Bild zu speichern, funktioniert nicht.</span><span class="sxs-lookup"><span data-stu-id="161f7-175">Inserting a 3D model (animated or static) and trying to 'Save as Picture' doesn't work.</span></span>

### <a name="office-suite"></a><span data-ttu-id="161f7-176">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="161f7-176">Office Suite</span></span>
- <span data-ttu-id="161f7-177">Es wurde ein Problem behoben, bei dem Office-Update-Nachrichten in einer anderen Sprache als erwartet angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="161f7-177">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="161f7-178">In Zukunft entsprechen Office-Update-Nachrichten ordnungsgemäß der Windows-Anzeigesprache.</span><span class="sxs-lookup"><span data-stu-id="161f7-178">Going forward, Office update messages will correctly match the Windows display language.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1912-december-06"></a><span data-ttu-id="161f7-180">Version 1912: 6. Dezember</span><span class="sxs-lookup"><span data-stu-id="161f7-180">Version 1912: December 06</span></span>
<span data-ttu-id="161f7-181">*Version 1912 (Build 12325.20012)*</span><span class="sxs-lookup"><span data-stu-id="161f7-181">*Version 1912 (Build 12325.20012)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="161f7-183">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-183">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="161f7-184">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-184">Outlook</span></span>

- <span data-ttu-id="161f7-185">**Erweiterte Gruppen-E-Mail-Einstellungen:** Diese Funktion hilft Gruppenbenutzern dabei, die E-Mails oder Ereignisse anzupassen, die sie in ihrem Posteingang empfangen/verfolgen möchten.</span><span class="sxs-lookup"><span data-stu-id="161f7-185">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="161f7-186">**Benennungsrichtlinie für Gruppen:** Mit einer Benennungsrichtlinie für Gruppen kann der IT-Administrator die Namen von Gruppen, die von Benutzern in der Organisation erstellt wurden, standardisieren und verwalten.</span><span class="sxs-lookup"><span data-stu-id="161f7-186">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="161f7-187">Der Administrator kann festlegen, dass dem Namen einer Gruppe beim Erstellen ein bestimmtes Präfixes und ein Suffix hinzugefügt werden, und er kann bestimmte Wörter blockieren.</span><span class="sxs-lookup"><span data-stu-id="161f7-187">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="161f7-188">Auf diese Weise kann die Verwendung von unpassenden Wörtern in Gruppennamen minimiert und die Darstellung von Gruppen in Ihrem Verzeichnis verwaltet werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-188">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="161f7-189">Die Benennungsrichtlinie hilft außerdem Organisationen, die Teamwebsites bereitstellen, um diese je nach Abteilung zu kategorisieren.</span><span class="sxs-lookup"><span data-stu-id="161f7-189">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="office-suite"></a><span data-ttu-id="161f7-190">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="161f7-190">Office Suite</span></span>

- <span data-ttu-id="161f7-191">**Bereiche im Registerkartenformat:** Jetzt können Sie über die Registerkarten-Benutzeroberfläche auf der rechten Seite der App zwischen mehreren Bereichen wechseln.</span><span class="sxs-lookup"><span data-stu-id="161f7-191">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="161f7-192">Die Benutzeroberfläche wird nur angezeigt, wenn Sie mehr als 2 Fenster geöffnet haben.</span><span class="sxs-lookup"><span data-stu-id="161f7-192">The UI will only be visible when you have 2+ panes open.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="161f7-195">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="161f7-195">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="161f7-196">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-196">Excel</span></span>
- <span data-ttu-id="161f7-197">Beim Speichern von Änderungen bei der Verwendung einiger nicht englischer Zeichengruppen tritt möglicherweise ein Fehler auf.</span><span class="sxs-lookup"><span data-stu-id="161f7-197">Users may encounter an error when saving changes while using some non-English character sets.</span></span>
- <span data-ttu-id="161f7-198">Beim Zugriff auf einen verborgenen benannten Bereich kann ein Fehler auftreten.</span><span class="sxs-lookup"><span data-stu-id="161f7-198">Users may encounter an error when accessing a hidden named range.</span></span>
- <span data-ttu-id="161f7-199">Das Deaktivieren der Beschleunigung von Hardware-Grafiken mit 4K könnte die Wiedergabe von Zellen verzögern.</span><span class="sxs-lookup"><span data-stu-id="161f7-199">Disabling hardware graphics acceleration with 4K resolution may result in delayed rendering of cells when scrolling around.</span></span>
- <span data-ttu-id="161f7-200">Das Löschen einer langen Formel, die eine Zellbegrenzung überlappt, wird möglicherweise weiterhin über die Zellbegrenzung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="161f7-200">Clearing a long formula that overlaps a cell boundary may still display across the cell boundary.</span></span>
- <span data-ttu-id="161f7-201">Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-201">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>
- <span data-ttu-id="161f7-202">Dropdownmenü „Rand“ wird möglicherweise nicht ordnungsgemäß gerendert.</span><span class="sxs-lookup"><span data-stu-id="161f7-202">Margin dropdown menu may not render correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="161f7-203">OneNote</span><span class="sxs-lookup"><span data-stu-id="161f7-203">OneNote</span></span>
- <span data-ttu-id="161f7-204">Möglicherweise wird OneNote nicht über das Outlook-Add-in „Besprechungsnotizen“ geöffnet.</span><span class="sxs-lookup"><span data-stu-id="161f7-204">OneNote may not open via the 'Meeting Notes' Outlook add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-205">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-205">Outlook</span></span>
- <span data-ttu-id="161f7-206">Bei Aufbewahrungsrichtlinien für Bezeichnungen kann der Aufbewahrungszeitraum in Klammern anzeigt sein.</span><span class="sxs-lookup"><span data-stu-id="161f7-206">Retention policy labels may display the retention time period in parenthesis.</span></span>
- <span data-ttu-id="161f7-207">Auf Visitenkarten mit dem japanischem Sprachpaket können Leerzeichen angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-207">Blank spaces may appear in Contact cards with Japanese language pack.</span></span>
- <span data-ttu-id="161f7-208">Bilder, die in Outlook-E-Mail-Nachrichten Inline eingefügt wurden, können manchmal geändert werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-208">Images inserted inline to Outlook e-mail messages can sometimes get resized.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-209">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-209">PowerPoint</span></span>
- <span data-ttu-id="161f7-210">Wenn ein Benutzer zwei (oder mehr) verschiedene Videos auf einer Folie in einer Cloud-Datei hat, werden die Videobilder korrekt wiedergegeben, aber wenn der Benutzer zum Abspielen auf jedes einzelne klickt, ist der Videoinhalt derselbe.</span><span class="sxs-lookup"><span data-stu-id="161f7-210">If a user has two (or more) different videos on a slide in a cloud file, the video images are rendered correctly, but when the user clicks on each one to play, the video content is the same.</span></span>
- <span data-ttu-id="161f7-211">In einigen Fällen geht Scrollen bei Touchscreen-Geräten nicht.</span><span class="sxs-lookup"><span data-stu-id="161f7-211">In some cases, scrolling with touch devices will not work.</span></span>
- <span data-ttu-id="161f7-212">Dropdownmenü „Rand“ wird möglicherweise nicht ordnungsgemäß gerendert.</span><span class="sxs-lookup"><span data-stu-id="161f7-212">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="161f7-213">Safelinks aus einer Office-Anwendung zu einer anderen können die verknüpfte Anwendung nicht starten.</span><span class="sxs-lookup"><span data-stu-id="161f7-213">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="project"></a><span data-ttu-id="161f7-214">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-214">Project</span></span>
- <span data-ttu-id="161f7-215">Project stürzt ab, wenn Sie die Funktion „Projekte vergleichen“ verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="161f7-215">Project may crash when you use the Compare Projects feature.</span></span>
- <span data-ttu-id="161f7-216">Wenn Sie sich im dunklen Modus befinden, können Sie die Tabelle nicht lesen, wenn Sie zu einem Vorgang mit einer überlasteten Ressource im Vorgangsinspektor wechseln.</span><span class="sxs-lookup"><span data-stu-id="161f7-216">If you are in Dark mode, when you go to the task inspector panel on a task with an over allocated resource, you are unable to read the table.</span></span>
- <span data-ttu-id="161f7-217">Das Festlegen von Aufwand für Vorgänge, die keine Aufgaben haben, wird auf 1 Tag abgerundet.</span><span class="sxs-lookup"><span data-stu-id="161f7-217">Setting effort on tasks that have no assignments are rounded to 1 day.</span></span>

### <a name="word"></a><span data-ttu-id="161f7-218">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-218">Word</span></span>
- <span data-ttu-id="161f7-219">Das Speichern einer Datei nach einem Seriendruck funktioniert unter bestimmten Bedingungen möglicherweise nicht.</span><span class="sxs-lookup"><span data-stu-id="161f7-219">Saving a file after doing a mail merge may not work under certain conditions.</span></span>
- <span data-ttu-id="161f7-220">Im Organizer für Bausteine könnte eine ungültige Warnung angezeigt werden: &quot;Sie haben modifizierte Formen, Bausteine&quot;.</span><span class="sxs-lookup"><span data-stu-id="161f7-220">Building blocks organizer may display an invalid alert: &quot;You have modified styles, building blocks&quot;.</span></span>
- <span data-ttu-id="161f7-221">Der Kommentarbereich wird manchmal beim Kopieren/Einfügen neu geladen.</span><span class="sxs-lookup"><span data-stu-id="161f7-221">Comment pane sometimes gets reloaded when using copy/paste.</span></span>
- <span data-ttu-id="161f7-222">Kommentare werden manchmal nicht in der richtigen Reihenfolge eingefügt.</span><span class="sxs-lookup"><span data-stu-id="161f7-222">Comments are sometimes not pasted in the correct order.</span></span>
- <span data-ttu-id="161f7-223">Das Anwenden einer Vorlage, die aus einer mehrstufigen Liste mit benutzerdefinierten Formatvorlagen besteht, auf bestehende Dokumente kann unter bestimmten Bedingungen die Formatvorlage nicht beibehalten.</span><span class="sxs-lookup"><span data-stu-id="161f7-223">Applying a template consisting of a multi-level list with custom styles to existing documents may not preserve the style under certain conditions.</span></span>
- <span data-ttu-id="161f7-224">Wenn Sie die Größe eines geteilten Bildschirms ändern, wird ggf. ein weiterer geteilter Bildschirm öffnen.</span><span class="sxs-lookup"><span data-stu-id="161f7-224">Resizing a split screen border may introduce an additional split screen.</span></span>
- <span data-ttu-id="161f7-225">Dropdownmenü „Rand“ wird möglicherweise nicht ordnungsgemäß gerendert.</span><span class="sxs-lookup"><span data-stu-id="161f7-225">Margin dropdown menu may not render correctly.</span></span>
- <span data-ttu-id="161f7-226">Wenn ein Benutzer auf einer Kommentarkarte erwähnt wird, wird möglicherweise JSON angezeigt.</span><span class="sxs-lookup"><span data-stu-id="161f7-226">At-mentioning a user in a comment card may show JSON.</span></span>
- <span data-ttu-id="161f7-227">Safelinks aus einer Office-Anwendung zu einer anderen können die verknüpfte Anwendung nicht starten.</span><span class="sxs-lookup"><span data-stu-id="161f7-227">Safelinks from one Office application to another may not launch the linked application.</span></span>

### <a name="office-suite"></a><span data-ttu-id="161f7-228">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="161f7-228">Office Suite</span></span>
- <span data-ttu-id="161f7-229">Bei Produkten mit einer Formatierung für Japan wird der Nachname des Benutzerkontos in der falschen Reihenfolge angezeigt.</span><span class="sxs-lookup"><span data-stu-id="161f7-229">For Japanese based products, account user first name, last name may appear in incorrect order.</span></span>
- <span data-ttu-id="161f7-230">Beim Bewegen des Mauszeigers über Kommentare wird möglicherweise eine TextBox-Kontur um den Kommentar angezeigt.</span><span class="sxs-lookup"><span data-stu-id="161f7-230">Hovering a mouse pointer over comments may display a textbox outline around the comment.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1912-november-15"></a><span data-ttu-id="161f7-232">Version 1912: 15. November</span><span class="sxs-lookup"><span data-stu-id="161f7-232">Version 1912: November 15</span></span>
<span data-ttu-id="161f7-233">*Version 1912 (Build 12307.20000)*</span><span class="sxs-lookup"><span data-stu-id="161f7-233">*Version 1912 (Build 12307.20000)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="161f7-235">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-235">Feature updates</span></span>
### <a name="insights-services"></a><span data-ttu-id="161f7-236">Insights-Services</span><span class="sxs-lookup"><span data-stu-id="161f7-236">Insights Services</span></span>
- <span data-ttu-id="161f7-237">**Abfragen in natürlicher Sprache in "Excel-Ideen":** Die neue Funktion von "Excel-Ideen", mit der Sie eine Frage zu Ihren Daten in natürlicher Sprache stellen können.</span><span class="sxs-lookup"><span data-stu-id="161f7-237">**Natural Language Queries in Ideas in Excel:** Excel Ideas's new capability to ask a natural language question about your data.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="161f7-240">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="161f7-240">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="161f7-241">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-241">Excel</span></span>
- <span data-ttu-id="161f7-242">Die Funktion "Text in Spalte" könnte bei einigen Lokalisierungen nicht funktionieren.</span><span class="sxs-lookup"><span data-stu-id="161f7-242">Text to Column functionality may fail for some localizations.</span></span>
- <span data-ttu-id="161f7-243">Beim Bearbeiten von dynamischen Arrayformeln innerhalb einer Zelle könnte Text außerhalb der Begrenzung der Zelle ausgerichtet werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-243">Editing dynamic array formulas within a cell may result in text being aligned outside of the boundary of the cell.</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-244">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-244">Outlook</span></span>
- <span data-ttu-id="161f7-245">Es wurde die Möglichkeit des Erzwingens der S/MIME-Konfiguration über eine Gruppenrichtlinie hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="161f7-245">Added the ability to enforce S/MIME configuration via group policy.</span></span>
- <span data-ttu-id="161f7-246">Eingebettete Bilder könnten kleiner als erwartet erscheinen.</span><span class="sxs-lookup"><span data-stu-id="161f7-246">Embedded images may appear smaller than expected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-247">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-247">PowerPoint</span></span>
- <span data-ttu-id="161f7-248">Der Cursor verschwindet möglicherweise nach dem Verschieben des Fokus von einem Textinhalt.</span><span class="sxs-lookup"><span data-stu-id="161f7-248">Cursor may disappear after moving focus from text.</span></span>

### <a name="project"></a><span data-ttu-id="161f7-249">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-249">Project</span></span>
- <span data-ttu-id="161f7-250">Es könnte ein Fehler hinsichtlich der Lizenzierung auftreten.</span><span class="sxs-lookup"><span data-stu-id="161f7-250">Users may experience an error regarding licensing.</span></span>
- <span data-ttu-id="161f7-251">Die Schaltfläche "Heute" in der Datumsauswahl könnte ein falsches Datum festlegen.</span><span class="sxs-lookup"><span data-stu-id="161f7-251">The Today button in the date picker may sometimes set the incorrect date.</span></span>

### <a name="word"></a><span data-ttu-id="161f7-252">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-252">Word</span></span>
- <span data-ttu-id="161f7-253">Bei einem Rechtsklick könnte manchmal nicht das ganze Wort markiert werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-253">Right-clicking can sometimes not result in selecting the whole word.</span></span>
- <span data-ttu-id="161f7-254">Nach der Konvertierung in ein vorgeschlagenes Format bleibt der Cursor u. U. in einem Objekt aktiv.</span><span class="sxs-lookup"><span data-stu-id="161f7-254">The cursor may remain active within an object after converting to a suggested format.</span></span>
- <span data-ttu-id="161f7-255">In einigen Szenarien werden Bilder in Nachrichten u. U. nicht ordnungsgemäß skaliert.</span><span class="sxs-lookup"><span data-stu-id="161f7-255">Images in messages may be incorrectly scaled in some scenarios.</span></span>
- <span data-ttu-id="161f7-256">Einige Designs erschweren es möglicherweise, den ausgewählten Kommentar zu erkennen.</span><span class="sxs-lookup"><span data-stu-id="161f7-256">Some themes may make it difficult to determine which comment is selected.</span></span>
- <span data-ttu-id="161f7-257">Beim Auswählen eines Kommentarhinweises im Bereich "Ansicht wechseln" sollte jetzt der moderne Kommentarbereich angezeigt werden, wenn dieser verborgen war.</span><span class="sxs-lookup"><span data-stu-id="161f7-257">Selecting a comment hint should now show the modern comments pane when hidden in pane switcher.</span></span>

### <a name="office-suite"></a><span data-ttu-id="161f7-258">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="161f7-258">Office Suite</span></span>
- <span data-ttu-id="161f7-259">Das Antworten auf einen Kommentar könnte dazu führen, dass das Textfeld vertikal über den Rand des Bereichs hinaus erweitert wird.</span><span class="sxs-lookup"><span data-stu-id="161f7-259">Replying to a comment may cause the textbox to expand vertically beyond the edge of the pane.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1912-november-08"></a><span data-ttu-id="161f7-261">Version 1912: 8. November</span><span class="sxs-lookup"><span data-stu-id="161f7-261">Version 1912: November 08</span></span>
<span data-ttu-id="161f7-262">*Version 1912 (Build 12231.20000)*</span><span class="sxs-lookup"><span data-stu-id="161f7-262">*Version 1912 (Build 12231.20000)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="161f7-264">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-264">Feature updates</span></span>
### <a name="user-lifecycle"></a><span data-ttu-id="161f7-265">Lebenszyklus des Benutzers:</span><span class="sxs-lookup"><span data-stu-id="161f7-265">User Lifecycle</span></span>
- <span data-ttu-id="161f7-266">**Verbesserungen bei der AFO-Aktivierung:** Aktualisierungen der Bildschirme, die den Kunden beim Aktivieren der im Lieferumfang Ihres neuen PCs enthaltenen Office-Version angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-266">**Experience improvements for AFO activation:** Updates to the screens customers see when activating Office that comes bundled with their new PC.</span></span>

### <a name="word"></a><span data-ttu-id="161f7-267">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-267">Word</span></span>
- <span data-ttu-id="161f7-268">**Neue und verbesserte Online-Videofunktionen in Word:** Neue und sicherere Onlinevideoerfahrung, die Ihnen beim Einfügen neuer Videos und beim Abspielen vorhandener Videos in Word hilft.</span><span class="sxs-lookup"><span data-stu-id="161f7-268">**New and improved online video experience in Word:** New and more secure online video experience to help you insert new videos and play existing videos in Word.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="161f7-271">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="161f7-271">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="161f7-272">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-272">Outlook</span></span>
- <span data-ttu-id="161f7-273">Zeitweiliger Absturz bei ordnerübergreifenden Inhalten.</span><span class="sxs-lookup"><span data-stu-id="161f7-273">Intermittent crash involving cross folder content.</span></span>

### <a name="office-suite"></a><span data-ttu-id="161f7-274">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="161f7-274">Office Suite</span></span>
- <span data-ttu-id="161f7-275">Wenn Sie ein Diagramm aus Excel in PowerPoint einfügen, kann sich die Größe des Diagramms verringern.</span><span class="sxs-lookup"><span data-stu-id="161f7-275">Pasting a chart from Excel to PowerPoint can reduce the size of the chart.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1911-november-01"></a><span data-ttu-id="161f7-277">Version 1911: 1. November</span><span class="sxs-lookup"><span data-stu-id="161f7-277">Version 1911: November 01</span></span>
<span data-ttu-id="161f7-278">*Version 1911 (Build 12228.20020)*</span><span class="sxs-lookup"><span data-stu-id="161f7-278">*Version 1911 (Build 12228.20020)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="161f7-280">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-280">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="161f7-281">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-281">Excel</span></span>
- <span data-ttu-id="161f7-282">**Nehmen Sie den Kontext mit ihren SVG-Objekten mit!:** Sie können jetzt den Text in Karten, Diagrammen und anderen SVG-Vektoren beibehalten, wenn Sie diese Objekte in Office konvertieren.</span><span class="sxs-lookup"><span data-stu-id="161f7-282">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="161f7-283">**Sehen Sie sich die Stiftoptionen an, wenn Sie Ihren Surface Pen aufnehmen:** Wenn Sie Ihren Surface Pen in Word, Excel oder PowerPoint in die Hand nehmen, wird die Registerkarte „Zeichnen“ aktiviert, damit Sie ganz einfach die Stiftfarben auswählen können.</span><span class="sxs-lookup"><span data-stu-id="161f7-283">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-284">PowerPoint</span></span>
- <span data-ttu-id="161f7-285">**Nehmen Sie den Kontext mit ihren SVG-Objekten mit!:** Sie können jetzt den Text in Karten, Diagrammen und anderen SVG-Vektoren beibehalten, wenn Sie diese Objekte in Office konvertieren.</span><span class="sxs-lookup"><span data-stu-id="161f7-285">**Bring the context along with your SVG objects!:** Now you can retain the text in maps, chart and other SVG vectors when converting these objects in Office.</span></span>

- <span data-ttu-id="161f7-286">**Sehen Sie sich die Stiftoptionen an, wenn Sie Ihren Surface Pen aufnehmen:** Wenn Sie Ihren Surface Pen in Word, Excel oder PowerPoint in die Hand nehmen, wird die Registerkarte „Zeichnen“ aktiviert, damit Sie ganz einfach die Stiftfarben auswählen können.</span><span class="sxs-lookup"><span data-stu-id="161f7-286">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

### <a name="visio"></a><span data-ttu-id="161f7-287">Visio</span><span class="sxs-lookup"><span data-stu-id="161f7-287">Visio</span></span>
- <span data-ttu-id="161f7-288">**Erstellen von ansprechenden Visio-Diagrammen in Excel:** Visualisieren Sie Ihre Daten schnell und einfach in ansprechenden Visio-Diagrammen in Excel.</span><span class="sxs-lookup"><span data-stu-id="161f7-288">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> <span data-ttu-id="161f7-289">[Weitere Informationen](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span><span class="sxs-lookup"><span data-stu-id="161f7-289">[Learn more](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).</span></span>

### <a name="word"></a><span data-ttu-id="161f7-290">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-290">Word</span></span>
- <span data-ttu-id="161f7-291">**Sehen Sie sich die Stiftoptionen an, wenn Sie Ihren Surface Pen aufnehmen:** Wenn Sie Ihren Surface Pen in Word, Excel oder PowerPoint in die Hand nehmen, wird die Registerkarte „Zeichnen“ aktiviert, damit Sie ganz einfach die Stiftfarben auswählen können.</span><span class="sxs-lookup"><span data-stu-id="161f7-291">**See Your Pen Options When You Pick Up Your Surface Pen:** When you first pick up your Surface Pen in Word, Excel, or PowerPoint, the Draw tab will be activated to make selecting your pen colors easy.</span></span>

- <span data-ttu-id="161f7-292">**Verbesserungen bei der gemeinsamen Dokumenterstellung:** Die gemeinsame Dokumenterstellung wurde verbessert, indem Inhaltsänderungen den anderen Benutzern nun nahezu immer in Echtzeit angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-292">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="161f7-293">**Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.</span><span class="sxs-lookup"><span data-stu-id="161f7-293">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="161f7-296">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="161f7-296">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="161f7-297">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-297">Excel</span></span>
- <span data-ttu-id="161f7-298">Es wurde ein Problem behoben, durch das die Bearbeitung einer geschützten Datei von einer nicht vertrauenswürdigen Netzwerkfreigabe zum Absturz von Excel geführt haben könnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-298">Resolved an issue where Excel may crash when editing a protected file from an untrusted network share.</span></span>
- <span data-ttu-id="161f7-299">Es wurde ein Problem behoben, bei dem das Löschen von Blättern mit Sparklines, die auf Daten auf einem anderen Arbeitsblatt verweisen, dazu führen könnte, dass die Datei beim erneuten Öffnen als fehlerhaft identifiziert wird.</span><span class="sxs-lookup"><span data-stu-id="161f7-299">Resolved an issue where deleting sheets containing sparklines referencing data on another sheet could cause the file to be identified as corrupted when re-opened.</span></span>
- <span data-ttu-id="161f7-300">Es wurde ein Problem behoben, bei dem Sie beim Konvertieren von Berichtsfiltern zusammen mit der restlichen PivotTable für Abfragen an tabellarische SQL-Server möglicherweise falsche Ergebnisse erhalten.</span><span class="sxs-lookup"><span data-stu-id="161f7-300">Resolved an Issue where you may get incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span>
- <span data-ttu-id="161f7-301">Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Absturz führen.</span><span class="sxs-lookup"><span data-stu-id="161f7-301">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="161f7-302">Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Absturz führen.</span><span class="sxs-lookup"><span data-stu-id="161f7-302">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-303">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-303">Outlook</span></span>
- <span data-ttu-id="161f7-304">Bei einer weitergeleiteten e-Mail fehlen möglicherweise eingebettete Bilder.</span><span class="sxs-lookup"><span data-stu-id="161f7-304">A forwarded e-mail may be missing embedded images.</span></span>
- <span data-ttu-id="161f7-305">Das Tool „Raumsuche“ zeigt bei verfügbaren Räumen möglicherweise &quot;Keine&quot; an.</span><span class="sxs-lookup"><span data-stu-id="161f7-305">Room Finder tool may be displaying &quot;None&quot; for available rooms.</span></span>
- <span data-ttu-id="161f7-306">Benutzer sind möglicherweise nicht in der Lage, Outlook-Profile mit strikter Mandantenbeschränkung zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="161f7-306">Users may not be able to create Outlook profiles with strict tenant restriction.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-307">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-307">PowerPoint</span></span>
- <span data-ttu-id="161f7-308">Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Absturz führen.</span><span class="sxs-lookup"><span data-stu-id="161f7-308">Using Narrator and Magnifier at the same time may result in a crash.</span></span>

### <a name="project"></a><span data-ttu-id="161f7-309">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-309">Project</span></span>
- <span data-ttu-id="161f7-310">Der Benutzer kann eine Aufgabe nicht als erledigt markieren, und sie wird auf 99 % festgelegt.</span><span class="sxs-lookup"><span data-stu-id="161f7-310">User is unable to mark a task as complete, and it gets set to 99%.</span></span>
- <span data-ttu-id="161f7-311">Überlastungen werden durch einen Abgleich nicht behoben.</span><span class="sxs-lookup"><span data-stu-id="161f7-311">Overallocations are not resolved by leveling.</span></span>

### <a name="word"></a><span data-ttu-id="161f7-312">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-312">Word</span></span>
- <span data-ttu-id="161f7-313">Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Absturz führen.</span><span class="sxs-lookup"><span data-stu-id="161f7-313">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="161f7-314">Das Öffnen alter Dokumente und das anschließende Wechseln zur Registerkarte „Info“ kann zu einem Absturz führen.</span><span class="sxs-lookup"><span data-stu-id="161f7-314">Opening legacy documents and then going to the Info tab can cause a crash.</span></span>
- <span data-ttu-id="161f7-315">Vorschläge der Dokumentprüfung werden nicht in Kontextmenüs angezeigt.</span><span class="sxs-lookup"><span data-stu-id="161f7-315">Proofing suggestins are not displaying in contextual menus.</span></span>
- <span data-ttu-id="161f7-316">Inhaltsrichtlinien werden nicht ordnungsgemäß auf Kommentare angewendet.</span><span class="sxs-lookup"><span data-stu-id="161f7-316">Content policies are being incorrectly applied to comments.</span></span>
- <span data-ttu-id="161f7-317">Alte Kommentare, die mit dunklem Text geschrieben wurden, sind im dunklen Modus nicht sichtbar.</span><span class="sxs-lookup"><span data-stu-id="161f7-317">Legacy comments written with dark text is not visible in Dark Mode.</span></span>
- <span data-ttu-id="161f7-318">Bei Verwendung der AutoKorrektur für Koreanisch/Englisch werden möglicherweise falsche Zeichen angezeigt.</span><span class="sxs-lookup"><span data-stu-id="161f7-318">Incorrect characters may appear when using Korean/English autocorrect.</span></span>
- <span data-ttu-id="161f7-319">Niedrigere Richtlinienbezeichnungen werden möglicherweise angewendet, wenn eine höhere Richtlinienbezeichnung Vorrang haben sollte.</span><span class="sxs-lookup"><span data-stu-id="161f7-319">Lower policy labels may be applied when a higher policy label should have taken priority.</span></span>
- <span data-ttu-id="161f7-320">Die Links von cid:-Bildern aus Outlook-Nachrichten&nbsp;können nun auf Anforderung erfolgreich unterbrochen werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-320">The links of cid: images from Outlook messages&nbsp;can now be successfully broken when requested.</span></span>
- <span data-ttu-id="161f7-321">Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Absturz führen.</span><span class="sxs-lookup"><span data-stu-id="161f7-321">Using Narrator and Magnifier at the same time may result in a crash.</span></span>
- <span data-ttu-id="161f7-322">Die Suche im Navigationsbereich schlägt möglicherweise fehl.</span><span class="sxs-lookup"><span data-stu-id="161f7-322">Searching from the Navigation pane may fail.</span></span>

### <a name="office-suite"></a><span data-ttu-id="161f7-323">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="161f7-323">Office Suite</span></span>
- <span data-ttu-id="161f7-324">Einige Zeichnungen werden in der Vorschau oder in Bildschirmpräsentationen möglicherweise nicht angezeigt.</span><span class="sxs-lookup"><span data-stu-id="161f7-324">Some drawings may not display in preview or slide shows.</span></span>
- <span data-ttu-id="161f7-325">Einige Katakana-Zeichen werden in einem vertikalen Textfeld möglicherweise nicht korrekt angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-325">Some katakana characters may display incorrectly in a vertical text box.</span></span>
- <span data-ttu-id="161f7-326">Der Versuch, eine Datei auf einer nicht verbundenen Netzwerkfreigabe zu speichern, kann zu einem Absturz führen.</span><span class="sxs-lookup"><span data-stu-id="161f7-326">Attempting to save a file to a disconnected network share may result in a crash.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1911-october-25"></a><span data-ttu-id="161f7-328">Version 1911: 25. Oktober</span><span class="sxs-lookup"><span data-stu-id="161f7-328">Version 1911: October 25</span></span>
<span data-ttu-id="161f7-329">*Version 1911 (Build 12215.20006)*</span><span class="sxs-lookup"><span data-stu-id="161f7-329">*Version 1911 (Build 12215.20006)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="161f7-331">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-331">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="161f7-332">Visio</span><span class="sxs-lookup"><span data-stu-id="161f7-332">Visio</span></span>

- <span data-ttu-id="161f7-333">**Erstellen von ansprechenden Visio-Diagrammen in Excel:** Visualisieren Sie Ihre Daten schnell und einfach in ansprechenden Visio-Diagrammen in Excel.</span><span class="sxs-lookup"><span data-stu-id="161f7-333">**Make polished Visio diagrams in Excel:** Quickly and easily visualize your data into polished Visio diagrams within Excel.</span></span> [<span data-ttu-id="161f7-334">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="161f7-334">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="161f7-335">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-335">Word</span></span>

- <span data-ttu-id="161f7-336">**Verbesserungen bei der gemeinsamen Dokumenterstellung:** Die gemeinsame Dokumenterstellung wurde verbessert, indem Inhaltsänderungen den anderen Benutzern nun nahezu immer in Echtzeit angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-336">**Coauthoring improvements:** Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

- <span data-ttu-id="161f7-337">**Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.</span><span class="sxs-lookup"><span data-stu-id="161f7-337">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="161f7-340">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="161f7-340">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="161f7-341">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-341">Access</span></span>

- <div><span data-ttu-id="161f7-342"><span>Möglicherweise ist die Datensatzanzahl falsch</span></span><span class="sxs-lookup"><span data-stu-id="161f7-342"><span>The record count could be incorrect</span></span></span></div>


### <a name="excel"></a><span data-ttu-id="161f7-343">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-343">Excel</span></span>

- <div><span data-ttu-id="161f7-344"><span>Wir haben die Leistung beim Löschen von Spalten mit verbundenen Zellen erheblich verbessert.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-344"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


- <div><span data-ttu-id="161f7-345"><span>Es könnte Benutzern ggfs. nicht möglich sein, im Office 365-Format für Excel-Arbeitsmappen zu speichern</span></span><span class="sxs-lookup"><span data-stu-id="161f7-345"><span>Users could be prevented from saving in Office 365 Excel Workbook format</span></span></span></div>


- <div><span data-ttu-id="161f7-346"><span>Kontrollkästchen wurden nicht ordnungsgemäß gerendert</span></span><span class="sxs-lookup"><span data-stu-id="161f7-346"><span>Checkboxes could not render correctly</span></span></span></div>


- <div><span data-ttu-id="161f7-347"><span>Änderungen an der Größe eines Diagramms konnten nicht gespeichert werden.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-347"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="161f7-348"><span>Einige VBA-Funktionen haben bei neuen Diagrammtypen einen Fehler zurückgegeben</span></span><span class="sxs-lookup"><span data-stu-id="161f7-348"><span>Some VBA functions would return an error on new chart types</span></span></span></div>


- <div><span data-ttu-id="161f7-349"><span>Bei einigen Dialogfeldern zur Auswahl von Datenquellen wurde die Groß-/Kleinschreibung nicht beachtet</span></span><span class="sxs-lookup"><span data-stu-id="161f7-349"><span>Select Data Source dialogs were not case sensitive for some fields</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="161f7-350">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-350">PowerPoint</span></span>

- <div><span data-ttu-id="161f7-351"><span>Änderungen an der Größe eines Diagramms konnten nicht gespeichert werden.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-351"><span>Changes to a chart size could not be saved</span></span></span></div>


### <a name="publisher"></a><span data-ttu-id="161f7-352">Publisher</span><span class="sxs-lookup"><span data-stu-id="161f7-352">Publisher</span></span>

- <div><span data-ttu-id="161f7-353"><span>Shapes konnten außerhalb des Grafikrahmens angezeigt werden</span></span><span class="sxs-lookup"><span data-stu-id="161f7-353"><span>Shapes could appear outside of the graphics border</span></span></span></div>


### <a name="word"></a><span data-ttu-id="161f7-354">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-354">Word</span></span>

- <div><span data-ttu-id="161f7-355"><span>Shapes konnten außerhalb des Grafikrahmens angezeigt werden</span></span><span class="sxs-lookup"><span data-stu-id="161f7-355"><span>Shapes could appear outside of the graphics border</span></span></span></div>


- <div><span data-ttu-id="161f7-356"><span>Das Hervorheben von Text kann sich schwierig gestalten</span></span><span class="sxs-lookup"><span data-stu-id="161f7-356"><span>Highlighting text could be challenging</span></span></span></div>


- <div><span data-ttu-id="161f7-357"><span>Ein Benutzer konnte daran gehindert werden, zu einem einzelnen Element im Editor zu navigieren.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-357"><span>A user could be prevented from navigating to an individual item in the editor</span></span></span></div>


- <div><span data-ttu-id="161f7-358"><span>Möglicherweise wurden Grammatik- oder Rechtschreibfehler nicht hervorgehoben</span></span><span class="sxs-lookup"><span data-stu-id="161f7-358"><span>Grammar or spelling errors might not be highlighted</span></span></span></div>


- <div><span data-ttu-id="161f7-359"><span>Änderungen an der Größe eines Diagramms konnten nicht gespeichert werden.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-359"><span>Changes to a chart size could not be saved</span></span></span></div>


- <div><span data-ttu-id="161f7-360"><span>Eine Visitenkarte konnte ggfs. nicht mehr geöffnet werden, nachdem eine Formatierung auf @mention angewendet wurde</span></span><span class="sxs-lookup"><span data-stu-id="161f7-360"><span>A contact card could be prevented from opening after apply formatting to an @ mention</span></span></span></div>


- <div><span data-ttu-id="161f7-361"><span>Ein Problem wurde behoben, bei dem Nutzer ggfs. Word, Excel- und PowerPoint-Dokumente nicht mehr speichern konnten.&nbsp; Dieses Problem betraf Benutzer, die eine neue Datei erstellten und das Dialogfeld &quot;Modell speichern&quot; öffneten, nachdem Sie auf das Symbol "Speichern" geklickt oder STRG + S gedrückt hatten.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-361"><span>Resolvedan issue where users may be unable to save Word, Excel, and PowerPoint documents.&nbsp; This issue affects users that create a new file and bring up the &quot;Save as Model Dialog&quot; option after clicking on the Save icon or pressing Ctrl + S.</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="161f7-362">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="161f7-362">Office Suite</span></span>

- <div><span data-ttu-id="161f7-363"><span>Leistungsproblem bei der Verwendung von Shapes unter Windows 7</span></span><span class="sxs-lookup"><span data-stu-id="161f7-363"><span>Performance issue when using Shapes on Windows 7</span></span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1911-october-18"></a><span data-ttu-id="161f7-365">Version 1911: 18. Oktober</span><span class="sxs-lookup"><span data-stu-id="161f7-365">Version 1911: October 18</span></span>
<span data-ttu-id="161f7-366">*Version 1911 (Build 12209.20010)*</span><span class="sxs-lookup"><span data-stu-id="161f7-366">*Version 1911 (Build 12209.20010)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="161f7-368">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-368">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="161f7-369">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-369">Outlook</span></span>

- <span data-ttu-id="161f7-370">**Senden Sie barrierefreie E-Mails an die Benutzer, die sie am dringendsten benötigen:** Outlook zeigt einen E-Mail-Tipp an, um sicherzustellen, dass Ihr Inhalt barrierefrei ist, wenn Sie ihn an einen Benutzer senden, der barrierefreien Inhalt bevorzugt.</span><span class="sxs-lookup"><span data-stu-id="161f7-370">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-371">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-371">PowerPoint</span></span>

- <span data-ttu-id="161f7-372">**Optimieren Sie Ihre Präsentation für alle:** Die Barrierefreiheitsprüfung hilft Ihnen beim Anordnen von Objekten auf Ihren Folien, indem sie die Sprachausgabe berücksichtigt.</span><span class="sxs-lookup"><span data-stu-id="161f7-372">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

### <a name="office-suite"></a><span data-ttu-id="161f7-373">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="161f7-373">Office Suite</span></span>

- <span data-ttu-id="161f7-374">**Das Upload Center wird durch die Funktion „Dateien, die Ihre Aufmerksamkeit benötigen“ ersetzt:** Das Upload Center wird durch die in den Office-Anwendungen unter „Datei“ > „Öffnen“ angezeigte Funktion „Dateien, die Ihre Aufmerksamkeit benötigen“ ersetzt.</span><span class="sxs-lookup"><span data-stu-id="161f7-374">**The Upload Center is being replaced by the Files Needing Attention experience:** The Upload Center is being replaced by the Files Needing Attention experience that will show up inside the Office applications under File > Open.</span></span> <span data-ttu-id="161f7-375">Die neue Oberfläche ist moderner, besser integriert und im Vergleich zum Upload Center weniger aufdringlich.</span><span class="sxs-lookup"><span data-stu-id="161f7-375">This new experience is more modern, integrated, and less intrusive compared to the Upload Center.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a><span data-ttu-id="161f7-378">Nicht sicherheitsrelevante Sicherheitsupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-378">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="161f7-379">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-379">Excel</span></span>

- <div><span data-ttu-id="161f7-380"><span>Wir haben ein Problem behoben, bei dem Kontrollkästchen-Steuerelemente unter Verwendung der automatischen Anpassung der Zeilenhöhe verkleinert werden konnten</span></span><span class="sxs-lookup"><span data-stu-id="161f7-380"><span>Resolved an issue where check box controls could shrink when using autofit to adjust row height</span></span></span></div>


- <div><span data-ttu-id="161f7-381"><span>Wir haben ein Problem gelöst, durch das das Auswählen einer Zelle nach dem Scrollen dazu führen konnte, dass die falsche Zelle ausgewählt wurde</span></span><span class="sxs-lookup"><span data-stu-id="161f7-381"><span>Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="161f7-382">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-382">Outlook</span></span>

- <div><span data-ttu-id="161f7-383"><span>Wir haben ein Problem erkannt, durch das digitale Signaturen beim Signieren einer E-Mail-Nachricht mit einem digital signierten Anhang beschädigt werden könnten</span></span><span class="sxs-lookup"><span data-stu-id="161f7-383"><span>Identified an issue which could cause digital signatures to become broken when signing an e-mail with a digitally signed attachment</span></span></span></div>


- <div><span data-ttu-id="161f7-384"><span>Wir haben ein Problem erkannt, bei dem lange Dateinamen nach dem Drag & Drop im Textkörper der Nachricht abgeschnitten wurden</span></span><span class="sxs-lookup"><span data-stu-id="161f7-384"><span>Identified an issue where long filenames were truncated after draging and droping to the message body</span></span></span></div>


- <div><span data-ttu-id="161f7-385">Wir haben ein Problem erkannt, bei dem es sein konnte, dass das Suchfeld nicht mehr angezeigt werden könnte, wenn das Menüband auf automatisches Ausblenden eingestellt ist</span><span class="sxs-lookup"><span data-stu-id="161f7-385">Identified an issue where the search box could disappear when the ribbon is set to hide automatically</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="161f7-386">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-386">PowerPoint</span></span>

- <div><span data-ttu-id="161f7-387"><span>Es wurde ein Problem erkannt, bei dem das Seitenverhältnis für die Folienvorschau nicht ordnungsgemäß gesperrt bzw. entriegelt wurde</span></span><span class="sxs-lookup"><span data-stu-id="161f7-387"><span>Identified an issuewhere aspect ratio for the slide preview was not being properly locked/unlocked</span></span></span></div>

### <a name="project"></a><span data-ttu-id="161f7-388">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-388">Project</span></span>

- <div><span data-ttu-id="161f7-389">Wir haben ein Problem erkannt, bei dem Notizen, die während Aktualisierungsvorgängen eingegeben werden, möglicherweise nicht gespeichert werden</span><span class="sxs-lookup"><span data-stu-id="161f7-389">Identified an issue where notes might not persist if entered while doing update tasks</span></span><br></div>


- <div><span data-ttu-id="161f7-390">Wir haben ein Problem erkannt, bei dem eine Datei durch einen Benutzer gesperrt werden konnte, aber kein Benutzername in der Fehlermeldung angezeigt wird</span><span class="sxs-lookup"><span data-stu-id="161f7-390">Identified an issue where a file could be locked by a user, but no username would be displayed in the error message</span></span></div>


- <div><span data-ttu-id="161f7-391"><span>Wir haben ein Problem erkannt, bei dem Benutzer beim Öffnen eines schreibgeschützten Projekts mehrere Nachrichten erhalten könnten</span></span><span class="sxs-lookup"><span data-stu-id="161f7-391"><span>Identified an issue where users could get several messages when opening a read-only project</span></span></span></div>


### <a name="word"></a><span data-ttu-id="161f7-392">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-392">Word</span></span>

- <div><span data-ttu-id="161f7-393"><span>Bei der Anzeige von Kommentaren während der Verwendung einer Sprachausgabe wurde ein Problem erkannt</span></span><span class="sxs-lookup"><span data-stu-id="161f7-393"><span>Identified an issue when viewing comments while using a screen reader</span></span></span></div>


- <div><span data-ttu-id="161f7-394"><span>Wir haben ein Problem festgestellt, bei dem einige Kritiken fälschlicherweise als Rechtschreib- oder Grammatikkritiken erkannt wurden</span></span><span class="sxs-lookup"><span data-stu-id="161f7-394"><span>Identified an issue where some critiques were misidentified as being spelling or grammar critiques</span></span></span></div>


- <div><span data-ttu-id="161f7-395"><span>Wir haben ein Problem erkannt, bei dem ein neues Kommentardialogfeld manchmal nicht in den Fokus gesetzt werden konnte</span></span><span class="sxs-lookup"><span data-stu-id="161f7-395"><span>Identified an issue where a new comment dialog could sometimes not obtain focus</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="161f7-396">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="161f7-396">Office Suite</span></span>

- <div><span data-ttu-id="161f7-397"><span>Wir haben ein Problem behoben, bei dem ein Upgrade durch die falsche Fehlermeldung &quot;Es wird bereits eine andere Installation ausgeführt&quot;</span> verhindert werden konnte</span><span class="sxs-lookup"><span data-stu-id="161f7-397"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="161f7-398"><span>Wir haben ein Problem erkannt, das sich auf die Synchronisierung einer lokalen Ressource mit einer Cloud-Ressource auswirken könnte</span></span><span class="sxs-lookup"><span data-stu-id="161f7-398"><span>Identified an issue which could affect syncing from a local resource to a cloud resource</span></span></span></div>

- <div><span data-ttu-id="161f7-399"><span>Es wurde ein Problem erkannt, bei dem eine Willkommensnachricht einen ungültigen Link enthielt</span></span><span class="sxs-lookup"><span data-stu-id="161f7-399"><span>Identified an issue where a welcome message contained an invalid link</span></span></span></div>


[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-1910-october-11"></a><span data-ttu-id="161f7-401">Version 1910: 11. Oktober</span><span class="sxs-lookup"><span data-stu-id="161f7-401">Version 1910: October 11</span></span>
<span data-ttu-id="161f7-402">*Version 1910 (Build 12130.20112)*</span><span class="sxs-lookup"><span data-stu-id="161f7-402">*Version 1910 (Build 12130.20112)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)
[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)
[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a><span data-ttu-id="161f7-406">Nicht sicherheitsrelevante Sicherheitsupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-406">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="161f7-407">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-407">Excel</span></span>

- <div><span data-ttu-id="161f7-408">Ein Problem beim Einfügen von Dateien als Objekt aus OneDrive wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="161f7-408">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="161f7-409">Ein Problem wurde behoben, bei dem das Hyperlink-Format auf einige Inhalte nicht ordnungsgemäß angewendet werden konnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-409">Resolved an issue where the hyperlink format could not be properly applied to some content</span></span></div>


- <div><span data-ttu-id="161f7-410">Ein Problem wurde behoben, bei dem Formeln mit strukturierten absoluten Bezügen nicht ordnungsgemäß angepasst wurden.</span><span class="sxs-lookup"><span data-stu-id="161f7-410">Resolved an issue where formulas containing structured absolute references may be adjusted incorrectly</span></span></div>


- <div><span data-ttu-id="161f7-411">Ein Problem wurde behoben, das beim Öffnen von in früheren Versionen von Office erstellten Arbeitsmappen in aktuellen Versionen von Office zu Programmabstürzen führen konnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-411">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office</span></span></div>


- <div><span data-ttu-id="161f7-412">Ein Problem wurde behoben, bei dem Inhalte, die aus Excel kopiert wurden, beim Einfügen in andere Office-Anwendungen falsch dargestellt werden konnten.</span><span class="sxs-lookup"><span data-stu-id="161f7-412">Resolved an issue where content copied from Excel could appear incorrect when pasted into other Office applications</span></span></div>


- <div><span data-ttu-id="161f7-413">Es wurde ein Problem mit Farben behoben, die in der Vorschau beim Einfügen von Diagrammen mithilfe von Diagrammvorlagen verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="161f7-413">Fix to correct colors used in previews when inserting charts using chart templates</span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="161f7-414">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-414">PowerPoint</span></span>

- <div><span data-ttu-id="161f7-415">Es wurde ein Problem identifiziert, durch das ARC-Geräte die Verbindung verlieren können, wenn sie unter AirSpace WinComp ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-415">Identified an issue where ARC Devices could lose connection when running under AirSpace WinComp</span></span></div>


### <a name="word"></a><span data-ttu-id="161f7-416">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-416">Word</span></span>

- <div><span data-ttu-id="161f7-417">Ein Problem beim Einfügen von Dateien als Objekt aus OneDrive wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="161f7-417">Resolved an issue in inserting files as object from OneDrive</span></span></div>


- <div><span data-ttu-id="161f7-418">Die Wiederherstellungsschritte wurden verbessert, <span>um ein Problem zu beheben, das dazu führte, dass grafische Inhalte aus E-Mail-Threads gelöscht werden konnten.&nbsp;</span></span><span class="sxs-lookup"><span data-stu-id="161f7-418">Improved our recovery steps to f<span>ix an issue that caused graphical content to get deleted from email threads.&nbsp;</span></span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1910-october-04"></a><span data-ttu-id="161f7-420">Version 1910: 04. Oktober</span><span class="sxs-lookup"><span data-stu-id="161f7-420">Version 1910: October 04</span></span>
<span data-ttu-id="161f7-421">*Version 1910 (Build 12126.20000)*</span><span class="sxs-lookup"><span data-stu-id="161f7-421">*Version 1910 (Build 12126.20000)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="161f7-423">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-423">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="161f7-424">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-424">Excel</span></span>

- <span data-ttu-id="161f7-425">\*\*Add-In „Datenschnellansicht“: \*\* erstellen Sie schnell Visio-Flussdiagramme aus Excel.</span><span class="sxs-lookup"><span data-stu-id="161f7-425">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="161f7-426">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="161f7-426">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a><span data-ttu-id="161f7-429">Nicht sicherheitsrelevante Sicherheitsupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-429">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="161f7-430">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-430">Excel</span></span>

- <div><span data-ttu-id="161f7-431"><span>Ein Problem wurde behoben, bei dem der Druckbereich in der Seitenansicht nicht korrekt war.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-431"><span>We fixed an issue where the print area in print preview was not correct</span></span></span></div>


- <div><span data-ttu-id="161f7-432"><span>Wir haben ein Problem behoben, durch das es gelegentlich nicht möglicher war, PivotTables während der gemeinsamen Dokumenterstellung zu aktualisieren</span></span><span class="sxs-lookup"><span data-stu-id="161f7-432"><span>We fixed an issue which could have prevented pivot tables from being refreshed during a co-authoring session</span></span></span></div>


### <a name="access"></a><span data-ttu-id="161f7-433">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-433">Access</span></span>

- <div><span data-ttu-id="161f7-434">Wir haben ein Problem behoben, bei dem Benutzer bei der Verwendung einer freigegebenen Datenbank die Fehlermeldung &quot;„inkonsistenter Zustand“&quot; erhalten konnten.</span><span class="sxs-lookup"><span data-stu-id="161f7-434">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


### <a name="outlook"></a><span data-ttu-id="161f7-435">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-435">Outlook</span></span>

- <div><span data-ttu-id="161f7-436"><span>Es wurde ein Problem behoben, durch das die Duplikation von E-Mail-Ordnern verursacht werden konnte</span></span><span class="sxs-lookup"><span data-stu-id="161f7-436"><span>We fixed an issue which could have caused duplication of mail folders</span></span></span></div>


- <div><span data-ttu-id="161f7-437"><span>Wir haben ein Problem behoben, das beim Senden einer s/MIME-verschlüsselten E-Mail-Nachricht eine falsche Fehlermeldung verursacht hat.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-437"><span>We fixed an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail</span></span></span></div>


- <div><span data-ttu-id="161f7-438"><span>Wir haben ein Problem behoben, das manchmal zu einem Absturz führen konnte, wenn ein Benutzer eine Nachricht vom Typ „verpasste Unterhaltung“ von Skype empfängt</span></span><span class="sxs-lookup"><span data-stu-id="161f7-438"><span>We fixed an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype</span></span></span></div>


- <div><span data-ttu-id="161f7-439"><span>Wir haben ein Problem behoben, durch das ein Speicherleck entstehen konnte</span></span><span class="sxs-lookup"><span data-stu-id="161f7-439"><span>We fixed an issue which could have resulted in a memory leak</span></span></span></div>


- <div><span data-ttu-id="161f7-440"><span>Es wurde ein Problem behoben, durch das beim Speichern als Entwurf ein falscher Absender angezeigt werden konnte</span></span><span class="sxs-lookup"><span data-stu-id="161f7-440"><span>We fixed an issue which could have caused the senders name to change when saved as a draft</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="161f7-441">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-441">PowerPoint</span></span>

- <div><span></span></div><span data-ttu-id="161f7-442">Es wurde ein Problem behoben, durch das TextRanges nach dem Einfügen von Text in den Platzhalter für Kopf-/Fußzeile/Foliennummer im Folienmaster und Folienlayout nicht mehr funktionieren konnten.</span><span class="sxs-lookup"><span data-stu-id="161f7-442">We fixed an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout</span></span>


- <div><span></span></div><span data-ttu-id="161f7-443">Wir haben ein Problem behoben, durch das das Erstellen von Links beim Einfügen von Text mit Link verhindert wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-443">We fixed an issue which prevented hyperlink from being created when pasting text with hyperlink</span></span>


- <div><span data-ttu-id="161f7-444">Wir haben ein Problem behoben, durch das die ordnungsgemäße Funktion von Statistiken verhindert wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-444">We fixed an issue which would prevent statistics from working correctly</span></span></div>


### <a name="word"></a><span data-ttu-id="161f7-445">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-445">Word</span></span>

- <div><span data-ttu-id="161f7-446"><span>Wir haben ein Problem behoben, durch das Schriftfarben nicht angewendet wurden</span></span><span class="sxs-lookup"><span data-stu-id="161f7-446"><span>We fixed an issue where font colors were not being committed</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="161f7-447">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="161f7-447">Office Suite</span></span>

- <div><span data-ttu-id="161f7-448">Wir haben ein Problem behoben, durch welches der Versionsverlauf angeboten werden konnte, obwohl diese Funktion deaktiviert worden war</span><span class="sxs-lookup"><span data-stu-id="161f7-448">We fixed an issue which could offer version history when that feature was disabled</span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1910-september-27"></a><span data-ttu-id="161f7-450">Version 1910: 27. September</span><span class="sxs-lookup"><span data-stu-id="161f7-450">Version 1910: September 27</span></span>
<span data-ttu-id="161f7-451">*Version 1910 (Build 12119.20000)*</span><span class="sxs-lookup"><span data-stu-id="161f7-451">*Version 1910 (Build 12119.20000)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)
[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)
[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a><span data-ttu-id="161f7-455">Nicht sicherheitsrelevante Sicherheitsupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-455">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="161f7-456">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-456">Excel</span></span>

- <div><span data-ttu-id="161f7-457"><span>Es wurde ein Problem behoben, durch das Punkt-Linien-Diagramme beim Ändern der Reihensammlung nicht ordnungsgemäß dargestellt werden konnten.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-457"><span>We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="161f7-458">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-458">Outlook</span></span>

- <div><span data-ttu-id="161f7-459"><span>Es wurde ein Problem behoben, durch das bei der Interaktion mit freigegebenen Kalenderordnern Berechtigungsfehler gemeldet wurden.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-459"><span>We fixed an issue which could have reported permission errors when interacting with shared calendar folders</span></span></span></div>


- <div><span data-ttu-id="161f7-460"><span>Es wurde ein Problem behoben, das Benutzer eventuell daran gehindert hätte, Anlagen an Kalender hinzuzufügen</span></span><span class="sxs-lookup"><span data-stu-id="161f7-460"><span>We fixed an issue which could have prevented users from adding attachments to calendars</span></span></span></div>


- <div><span data-ttu-id="161f7-461"><span>Es wurde ein Problem behoben, durch das beim Antworten auf eine digital signierte Nachricht Fehlermeldungen angezeigt wurden</span></span><span class="sxs-lookup"><span data-stu-id="161f7-461"><span>We fixed an issue which caused error messages to display when replying to a digitally signed message</span></span></span></div>


### <a name="word"></a><span data-ttu-id="161f7-462">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-462">Word</span></span>

- <div><span data-ttu-id="161f7-463"><span> Es wurde ein Problem behoben, das zu Skalierungsproblemen führte, wenn auf Deskjet-Druckern gedruckt wurde</span></span><span class="sxs-lookup"><span data-stu-id="161f7-463"><span>We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="161f7-464">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="161f7-464">Office Suite</span></span>

- <div><span data-ttu-id="161f7-465"><span>Es wurde ein Problem behoben, bei dem mittel-fett formatierter Text nicht ordnungsgemäß formatiert werden konnte</span></span><span class="sxs-lookup"><span data-stu-id="161f7-465"><span>We fixed an issue where medium bold text could be incorrectly styled</span></span></span></div>


- <div><span data-ttu-id="161f7-466"><span>Es wurde ein Problem behoben, bei dem einem Benutzer beim Schließen einer Datei mit ausstehendem Upload eine falsche Fehlermeldung angezeigt wird</span></span><span class="sxs-lookup"><span data-stu-id="161f7-466"><span>We fixed an issue where a user could be given an incorrect error message when closing a file with a pending upload</span></span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1910-september-20"></a><span data-ttu-id="161f7-468">Version 1910: 20. September</span><span class="sxs-lookup"><span data-stu-id="161f7-468">Version 1910: September 20</span></span>
<span data-ttu-id="161f7-469">*Version 1910 (Build 12112.20000)*</span><span class="sxs-lookup"><span data-stu-id="161f7-469">*Version 1910 (Build 12112.20000)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a><span data-ttu-id="161f7-473">Nicht sicherheitsrelevante Sicherheitsupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-473">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="161f7-474">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-474">Excel</span></span>

- <div><span data-ttu-id="161f7-475"><span>Es wurde ein Problem behoben, durch das Excel manchmal beim Start hängen geblieben ist.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-475"><span>We fixed an issue where Excel could sometimes hang at launch</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="161f7-476">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-476">Outlook</span></span>

- <div><span data-ttu-id="161f7-477"><span>Die Leistung der Raumauswahl bei einer großen Anzahl von verfügbaren Räumen wurde erheblich verbessert.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-477"><span>We significantly improved the performance of room selection when there are a large number of rooms available</span></span></span></div>


- <div><span data-ttu-id="161f7-478"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Es wurde ein Problem behoben, durch das die Postfachsynchronisierung für Kunden mit mehreren Postfächern in Outlook nach der Migration zur modernen Authentifizierung in Office 365 verhindert wurde.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-478"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can prevent mailbox sync for customers with multiple mailboxes in Outlook when migrating to modern authentication in Office 365.</span></span></span><br></div>


- <div><span data-ttu-id="161f7-479"><span>Es wurde ein Problem behoben, bei dem einige Zeichen in Signaturbeschriftungen im Dropdownmenü nicht angezeigt wurden</span></span><span class="sxs-lookup"><span data-stu-id="161f7-479"><span>We fixed an issue where some characters in signature labels would not display in the dropdown menu</span></span></span></div>


### <a name="project"></a><span data-ttu-id="161f7-480">Projekt</span><span class="sxs-lookup"><span data-stu-id="161f7-480">Project</span></span>

- <div><span data-ttu-id="161f7-481"><span>Es wurde ein Problem behoben, das beim Ersetzen einer Unternehmensressource durch eine lokale Ressource zu einem Absturz führte</span></span><span class="sxs-lookup"><span data-stu-id="161f7-481"><span>We fixed an issue which could cause a crash when replacing an enterprise resource with a local resource</span></span></span></div>


### <a name="word"></a><span data-ttu-id="161f7-482">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-482">Word</span></span>

- <div><span data-ttu-id="161f7-483"><span>Es wurde ein Problem behoben, durch das ein synchrones Scrollen in der Entwurfsdarstellung nicht ordnungsgemäß funktionierte</span></span><span class="sxs-lookup"><span data-stu-id="161f7-483"><span>We fixed an issue which could prevent synchronous scrolling from working properly in draft view</span></span></span></div>


- <div><span data-ttu-id="161f7-484">Es wurde ein Problem behoben, durch das QuickInfos nach dem erstmaligen Speichern eines Dokuments zeitweise nicht ordnungsgemäß angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="161f7-484">We fixed an issue which could prevent Tool Tips from displaying properly after saving a document for the first time</span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1910-september-13"></a><span data-ttu-id="161f7-486">Version 1910: 13. September</span><span class="sxs-lookup"><span data-stu-id="161f7-486">Version 1910: September 13</span></span>
<span data-ttu-id="161f7-487">*Version 1910 (Build 12105.20000)*</span><span class="sxs-lookup"><span data-stu-id="161f7-487">*Version 1910 (Build 12105.20000)*</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a><span data-ttu-id="161f7-489">Nicht sicherheitsrelevante Sicherheitsupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-489">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="161f7-490">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-490">Excel</span></span>

- <div><span data-ttu-id="161f7-491"><span>Ein Problem wurde behoben, das verhindern konnte, dass ein Benutzer Links in bestimmte geschützte Blättern einfügt</span></span><span class="sxs-lookup"><span data-stu-id="161f7-491"><span>We fixed an issue which could prevent a user from pasting hyperlinks in some protected sheets</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="161f7-492">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-492">Outlook</span></span>

- <div><span data-ttu-id="161f7-493"><span>Ein Problem wurde behoben, bei dem die Benutzeroberfläche möglicherweise in einer kompakten Darstellung stecken blieb</span></span><span class="sxs-lookup"><span data-stu-id="161f7-493"><span>We fixed an issue where the UI could get stuck in a compact view</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="161f7-494">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-494">PowerPoint</span></span>

- <div><span data-ttu-id="161f7-495"><span>Ein Problem wurde behoben, bei dem ein Benutzer beim Drucken in eine PDF-Datei möglicherweise eine Fehlermeldung erhielt</span></span><span class="sxs-lookup"><span data-stu-id="161f7-495"><span>We fixed an issue where a user could experience an error upon printing to PDF</span></span></span></div>


### <a name="project"></a><span data-ttu-id="161f7-496">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-496">Project</span></span>

- <div><span data-ttu-id="161f7-497"><span>Ein Problem wurde behoben, bei dem <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">Änderungen an einem Arbeitswert in einem Sammelvorgang zu einem Absturz führen konnten, wenn geschützte Arbeit aktiviert ist</span></span></span><span class="sxs-lookup"><span data-stu-id="161f7-497"><span>We fixed an issue where <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">changes to a work value on a summary task could cause a crash if protected work is enabled</span></span></span></span></div>


- <span data-ttu-id="161f7-498"><font size=2 style="background-color:rgb(255, 255, 255);">Ein Problem wurde behoben, durch das die Möglichkeit zum Synchronisieren von Ereignissen mit Enterprise-Kalendern verhindert werden konnte</font></span><span class="sxs-lookup"><span data-stu-id="161f7-498"><font size=2 style="background-color:rgb(255, 255, 255);">We fixed an issue which could inhibit the ability to sync events with enterprise calendars</font></span></span>


### <a name="office-suite"></a><span data-ttu-id="161f7-499">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="161f7-499">Office Suite</span></span>

- <div><span data-ttu-id="161f7-500"><span>Ein Problem wurde behoben, durch das eine wiederholte Warnung zum Verwerfen lokaler Versionen einer Datei angezeigt werden konnte</span></span><span class="sxs-lookup"><span data-stu-id="161f7-500"><span>We fixed an issue which could cause a repeated warning to discard local versions of a file</span></span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1910-september-06"></a><span data-ttu-id="161f7-502">Version 1910: 6. September</span><span class="sxs-lookup"><span data-stu-id="161f7-502">Version 1910: September 06</span></span>
<span data-ttu-id="161f7-503">*Version 1910 (Build 12030.20004)*</span><span class="sxs-lookup"><span data-stu-id="161f7-503">*Version 1910 (Build 12030.20004)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="161f7-505">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-505">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="161f7-506">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-506">Excel</span></span>

- <span data-ttu-id="161f7-507">**Auf die Plätze, fertig, zeichnen!** Sobald Sie Ihren Surface Pen in der Hand halten, können Sie mit dem Zeichnen beginnen.</span><span class="sxs-lookup"><span data-stu-id="161f7-507">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="161f7-508">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="161f7-508">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a><span data-ttu-id="161f7-509">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-509">PowerPoint</span></span>

- <span data-ttu-id="161f7-510">**Auf die Plätze, fertig, zeichnen!** Sobald Sie Ihren Surface Pen in der Hand halten, können Sie mit dem Zeichnen beginnen.</span><span class="sxs-lookup"><span data-stu-id="161f7-510">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="161f7-511">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="161f7-511">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a><span data-ttu-id="161f7-512">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-512">Word</span></span>

- <span data-ttu-id="161f7-513">**Auf die Plätze, fertig, zeichnen!** Sobald Sie Ihren Surface Pen in der Hand halten, können Sie mit dem Zeichnen beginnen.</span><span class="sxs-lookup"><span data-stu-id="161f7-513">**Ready, set, draw:** When you grab your Surface Pen, you're ready to draw.</span></span> [<span data-ttu-id="161f7-514">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="161f7-514">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a><span data-ttu-id="161f7-517">Nicht sicherheitsrelevante Sicherheitsupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-517">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="161f7-518">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-518">Excel</span></span>

- <div><span data-ttu-id="161f7-519"><span>Es wurde ein Problem behoben, das dazu führen konnte, dass der Name der Schriftart im Menü von der verwendeten Schriftart abweicht</span></span><span class="sxs-lookup"><span data-stu-id="161f7-519"><span>We fixed an issue which could cause the font name in the ribbon to be different from the font being used</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="161f7-520">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-520">Outlook</span></span>

- <div><span data-ttu-id="161f7-521"><span>Es wurde ein Problem behoben, das zu einer unangemessenen Ressourcennutzung von Outlook führen kann, wenn der geschützte Modus für eingeschränkte Websites im Internet Explorer deaktiviert ist</span></span><span class="sxs-lookup"><span data-stu-id="161f7-521"><span>We fixed an issue that could result in inappropriate resource consumption by Outlook when Protected Mode is disabled for Restricted Sites in Internet Explorer</span></span></span></div>


- <div><span data-ttu-id="161f7-522"><span>Es wurde ein Problem behoben, das beim Einfügen eines Textes aus einer ANSI-Quelle manchmal dazu führen kann, dass Unicode-Zeichen angezeigt werden</span></span><span class="sxs-lookup"><span data-stu-id="161f7-522"><span>We fixed an issue which could sometimes cause Unicode characters to appear when pasting text from an ANSI source</span></span></span></div>


- <div><span data-ttu-id="161f7-523"><span>Ein Problem wurde behoben, bei dem einige Benutzer in einer Gruppen-Planungsanzeige fälschlicherweise als offline angezeigt wurden</span></span><span class="sxs-lookup"><span data-stu-id="161f7-523"><span>We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span></span></div>


### <a name="word"></a><span data-ttu-id="161f7-524">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-524">Word</span></span>

- <div><span data-ttu-id="161f7-525"><span>Ein Problem wurde behoben, welches dazu führen konnte, dass Tabellenformatierung verloren ging</span></span><span class="sxs-lookup"><span data-stu-id="161f7-525"><span>We fixed an issue where table formatting could be lost</span></span></span></div>


- <div><span data-ttu-id="161f7-526"><span>Wir haben ein Problem behoben, welches dazu führen konnte, dass die Tastenkombination STRG + V nicht ordnungsgemäß funktionierte</span></span><span class="sxs-lookup"><span data-stu-id="161f7-526"><span>We fixed an issue which could break the ctrl+v keyboard shortcut</span></span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1909-august-30"></a><span data-ttu-id="161f7-528">Version 1909: 30. August</span><span class="sxs-lookup"><span data-stu-id="161f7-528">Version 1909: August 30</span></span>
<span data-ttu-id="161f7-529">*Version 1909 (Build 12026.20000)*</span><span class="sxs-lookup"><span data-stu-id="161f7-529">*Version 1909 (Build 12026.20000)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="161f7-531">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-531">Feature updates</span></span>

### <a name="access"></a><span data-ttu-id="161f7-532">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-532">Access</span></span>

- <span data-ttu-id="161f7-533">**Schnelle Suche nach verknüpften Tabellen:** Unser neues Suchfeld macht die Suche nach verknüpften Tabellen zu einem Kinderspiel.</span><span class="sxs-lookup"><span data-stu-id="161f7-533">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-534">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-534">PowerPoint</span></span>

- <span data-ttu-id="161f7-535">**Speichern einer Illustration als SVG:** Speichern Sie ein Diagramm, eine Form oder eine andere Abbildung als skalierbare Vektorgrafik, deren Größe ohne Verlust der Bildqualität geändert werden kann.</span><span class="sxs-lookup"><span data-stu-id="161f7-535">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="161f7-536">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="161f7-536">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a><span data-ttu-id="161f7-539">Nicht sicherheitsrelevante Sicherheitsupdates</span><span class="sxs-lookup"><span data-stu-id="161f7-539">Non-security updates</span></span>
### <a name="excel"></a><span data-ttu-id="161f7-540">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-540">Excel</span></span>

- <div><span data-ttu-id="161f7-541"><span>Wir haben ein Problem behoben, bei dem die Tastenkombination für&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Vertraulichkeit</span> mit&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">einer anderen Tastenkombination in Konflikt stand.</span></span></span><span class="sxs-lookup"><span data-stu-id="161f7-541"><span>We fixed an issue where the keytip for&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensitivity </span>was&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">conflicting with another keytip.</span></span></span></span></div>

- <div><span data-ttu-id="161f7-542"><span>Beim Speichern wurde ein Problem behoben, das beim Bearbeiten einer freigegebenen Arbeitsmappe auftrat, wenn versucht wurde zu speichern.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-542"><span>We fixed an issue that occurred while working on a shared workbook when trying to save.</span></span></span></div>

- <div><span data-ttu-id="161f7-543"><span>Wir haben ein Problem behoben, bei dem Excel nur die ersten 16 Add-Ins auflistet, die sich in den „\Excel\Add-in Manager“ Registrierungswerten befinden.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span><span class="sxs-lookup"><span data-stu-id="161f7-543"><span>We fixed an issue where Excel only lists the first 16 addins located in the '\Excel\Add-in Manager' registry values.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></span></span></div>


- <div><span data-ttu-id="161f7-544"><span>Wir haben ein Problem behoben, bei dem die Funktion „Häufigkeit()“ falsche Ergebnisse liefert.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-544"><span>We fixed an issue where the function Frequency() returns incorrect results.</span></span></span></div>


- <div><span data-ttu-id="161f7-545"><span>Die Leistung der Filterung nach Farbe wurde deutlich verbessert.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-545"><span>We have significantly improved the performance of filtering by color.</span></span></span></div>


- <div><span data-ttu-id="161f7-546"><span>Wir haben ein Problem für Surface-Benutzer behoben, bei dem das Bewegen der Maus als ein Mausklick interpretiert werden konnte.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-546"><span>We fixed an issue for Surface users where moving the mouse could be interpreted as a mouse click event.</span></span></span></div>


- <div><span data-ttu-id="161f7-547"><span>Wir haben ein Problem behoben, das die Tastaturnavigation im Dialog „Suchen/Ersetzen“ verhinderte.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-547"><span>We fixed an issue which prevented keyboard navigation in the Find/Replace dialog</span></span></span></div>


- <div><span data-ttu-id="161f7-548"><span>Wir haben ein Problem behoben, bei dem der Name einiger Schriftarten nicht korrekt angezeigt wurde.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-548"><span>We fixed an issue where the name of some fonts were not displayed correctly</span></span></span></div>


- <div><span data-ttu-id="161f7-549"><span>Wir haben ein Problem behoben, durch das CSV nicht als unterstützter Dateityp angezeigt wurde.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-549"><span>We fixed an issue which prevented CSV from appearing as a supported file type</span></span></span></div>


### <a name="access"></a><span data-ttu-id="161f7-550">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-550">Access</span></span>

- <div><span data-ttu-id="161f7-551">Wir haben ein Problem behoben, bei dem Benutzer bei der Verwendung einer freigegebenen Datenbank die Fehlermeldung &quot;„inkonsistenter Zustand“&quot; erhalten konnten.</span><span class="sxs-lookup"><span data-stu-id="161f7-551">We fixed an issue where users could receive an &quot;inconsistent state&quot; error when using a shared database.</span></span></div>


- <div><span data-ttu-id="161f7-552"><span>Wir haben ein Problem behoben, bei dem die Datumsauswahl angezeigt wurde, wenn es nicht nötig war.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-552"><span>We fixed an issue which could cause the date picker to appear when it shouldn't</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="161f7-553">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-553">Outlook</span></span>

- <div><span data-ttu-id="161f7-554"><span>Es wurde ein Problem behoben, das die Darstellung von HTML-Inhalten für einige POP3-Benutzer verhinderte.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-554"><span>We fixed an issue which prevented HTML content from appearing for some POP3 users</span></span></span></div>


- <div><span data-ttu-id="161f7-555"><span>Es wurde ein Problem behoben, bei dem der nicht funktionierende Link "Planer" aus dem Überlaufmenü der Visitenkarte entfernt wurde, wenn Sie in Umgebungen arbeiten, in denen er nicht verfügbar ist.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-555"><span>We fixed an issue to remove non-functional 'Planner' link from the overflow menu in the contact card when working in environments where it is not available.</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="161f7-556">OneNote</span><span class="sxs-lookup"><span data-stu-id="161f7-556">OneNote</span></span>

- <div><span data-ttu-id="161f7-557"><span>Es wurde ein Problem behoben&nbsp;, bei dem die Hintergrundsynchronisierung von OneNote manchmal den Fokus auf sich zog.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-557"><span>We fixed an issue where&nbsp;OneNote background sync was sometimes stealing focus.</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="161f7-558">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-558">PowerPoint</span></span>

- <div><span data-ttu-id="161f7-559"><span>Wir haben ein Problem behoben, das sich auf die Drehrichtung eines 3D-Drehtisches auswirken würde.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-559"><span>We fixed an issue which would affect the rotation orientation of a 3D Turntable.</span></span></span></div>

- <div><span data-ttu-id="161f7-560"><span>Wir haben ein Problem behoben, durch das einige Hyperlinks nicht mehr funktionierten, wenn sie Sonderzeichen enthielten.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-560"><span>We fixed an issue which prevented some hyperlinks from working if they contained special characters.</span></span></span></div>

- <div><span data-ttu-id="161f7-561"><span>Es wurde ein Problem behoben, bei dem mehrere Kommentarfenster gleichzeitig geöffnet wurden.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-561"><span>We fixed an issue which caused multiple comment panes to open at the same time.</span></span></span></div>

### <a name="project"></a><span data-ttu-id="161f7-562">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-562">Project</span></span>

- <div><span data-ttu-id="161f7-563"><span>Wir haben ein Problem behoben, das nach dem Drucken einer Teamplaneransicht manchmal zu einem Absturz führen konnte.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-563"><span>We fixed an issue which could sometimes cause a crash after printing a Team Planner view.</span></span></span></div>

### <a name="word"></a><span data-ttu-id="161f7-564">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-564">Word</span></span>

- <div><span data-ttu-id="161f7-565">Wir <span>haben ein Problem behoben, bei dem Multibyte-Zeichen in vertikalem Textfeld in der Leseansicht überlappt dargestellt werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-565">We f<span>ixed an issue where multi-byte characters in vertical text box are shown overlapped in reading view.</span></span><br></span></div>

- <div><span data-ttu-id="161f7-566"><span>Wir&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">haben ein Problem behoben, bei dem die japanischen Postkarten-und Grußkarten bezogenen Add-in-Ressourcen nicht gefunden werden, wenn der Benutzer im Add-in-Assistenten eine Aktion durchführt.</span></span></span><span class="sxs-lookup"><span data-stu-id="161f7-566"><span>We&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">fixed an issue where Japanese post card and greeting card related addin resources are not found when the user takes action in the addin wizard.</span></span></span></span></div>

- <div><span data-ttu-id="161f7-567"><span>Wir haben ein Problem behoben, das Schwierigkeiten mit der Benutzeroberfläche der Titelleiste verursachen konnte, wenn Sie sich in der geschützten Anzeige befinden.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-567"><span>We fixed an issue which could cause issues with the Title Bar User Interface when in Protected View</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="161f7-568">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="161f7-568">Office Suite</span></span>

- <div><span data-ttu-id="161f7-569"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> Wir haben ein Problem, das eine fehlerhafte Datei erzeugte, wenn Sie die Form in einer Auswahl ändern, die sowohl eine normale Form als auch eine Verbinder-Form enthält.</span></span></span><span class="sxs-lookup"><span data-stu-id="161f7-569"><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> We fixed a corrupt file issue when you Change Shape on a selection that contains both a normal shape and a connector shape.</span></span></span></span></div>

- <div><span data-ttu-id="161f7-570"><span>Wir haben ein Problem behoben, das <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">zu einem Problem in Anwendungen führte, wenn man das An- und Abdocken von mehreren externen Displays verwendet.</span></span></span><span class="sxs-lookup"><span data-stu-id="161f7-570"><span>We fixed an issue that <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">caused a problem in applications when using dock/undock from multiple external displays. </span></span></span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="august-23-2019br"></a><span data-ttu-id="161f7-572">**23. August 2019**</span><span class="sxs-lookup"><span data-stu-id="161f7-572">**August 23, 2019**</span></span><br/>
<span data-ttu-id="161f7-573">Version 1909 (Build 12015.20004)</span><span class="sxs-lookup"><span data-stu-id="161f7-573">Version 1909 (Build 12015.20004)</span></span><br/>



## <a name="non-security-updates"></a><span data-ttu-id="161f7-574">Nicht sicherheitsrelevante Updates:</span><span class="sxs-lookup"><span data-stu-id="161f7-574">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-575">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-575">Excel</span></span>

- <div><span data-ttu-id="161f7-576"><span>Wir haben die Leistung beim Löschen von Spalten mit verbundenen Zellen erheblich verbessert.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-576"><span>We significantly improved the performance of deleting columns with merged cells</span></span></span></div>


### <a name="office-suite"></a><span data-ttu-id="161f7-577">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="161f7-577">Office Suite</span></span>

- <div><span data-ttu-id="161f7-578"><span>Es wurde ein Problem behoben, durch das einige Unicode-Zeichen nicht angezeigt werden konnten, wenn sie in einem Browser dargestellt werden sollten.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-578"><span>We fixed an issue which could prevent some Unicode characters from being displayed when viewed in a browser</span></span></span></div>


### <a name="outlook"></a><span data-ttu-id="161f7-579">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-579">Outlook</span></span>

- <div><span data-ttu-id="161f7-580"><span>Es wurde ein Problem behoben, durch das Dateien am WebDAV-Speicherort nicht gespeichert werden konnten.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-580"><span>We fixed an issue which could have prevented files from being saved to a WebDAV location</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="161f7-581">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-581">PowerPoint</span></span>

- <div><span data-ttu-id="161f7-582"><span>Ein Problem wurde behoben, bei dem ein Benutzer auf einen Kommentar klickte, aber ein anderer Kommentar ausgewählt wurde.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-582"><span>We fixed an issue where a user would click on one comment, but another comment would be selected</span></span></span></div>





## <a name="august-16-2019br"></a><span data-ttu-id="161f7-583">**16. August 2019**</span><span class="sxs-lookup"><span data-stu-id="161f7-583">**August 16, 2019**</span></span><br/>
<span data-ttu-id="161f7-584">Version 1909 (Build 12013.20000)</span><span class="sxs-lookup"><span data-stu-id="161f7-584">Version 1909 (Build 12013.20000)</span></span><br/>

### <a name="powerpoint-feature-updates"></a><span data-ttu-id="161f7-585">PowerPoint-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="161f7-585">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="161f7-586">**Drucken von Foliennummern auf Handzetteln:** Foliennummern werden automatisch in Ihre Handzettel integriert.</span><span class="sxs-lookup"><span data-stu-id="161f7-586">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="161f7-587">Sie können diese Funktion an- oder abschalten, wie es Ihnen beliebt.</span><span class="sxs-lookup"><span data-stu-id="161f7-587">Leave them on, turn them off, it's all up to you.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="161f7-588">Nicht sicherheitsrelevante Updates:</span><span class="sxs-lookup"><span data-stu-id="161f7-588">Non-security updates:</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-589">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-589">Excel</span></span>

- <div><span data-ttu-id="161f7-590"><span>Wir haben ein Problem behoben, durch das sich die Funktion „Automatisches Speichern“ aktivieren konnte.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-590"><span>We fixed an issue which could cause AutoSave to become enabled</span></span></span></div>


- <div><span data-ttu-id="161f7-591">Wir haben ein Problem behoben, das zur ungenauen Bemessung der Zellenhöhe führen konnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-591">We fixed an issue which could result in cell heights being measured inaccurately</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="161f7-592">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="161f7-592">Office Suite</span></span>

- <div><span data-ttu-id="161f7-593"><span>Wir haben ein Problem behoben, das die Leistung der Kommentarfunktion erheblich verbessert.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-593"><span>We fixed an issue which significantly improves the performance of the Comments feature</span></span></span></div>


- <div><span data-ttu-id="161f7-594"><span>Ein Problem wurde behoben, das bei der Verwendung von Pfeiltasten während der Suche zum Absturz führen konnte.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-594"><span>We fixed an issue which could cause a crash when using arrow keys while in search</span></span></span></div>


- <div><span data-ttu-id="161f7-595"><span>Wir haben ein Problem behoben, durch das eine @Erwähnung verhindert werden konnte, wenn das @-Symbol nach bestimmten Zeichen gesetzt wurde.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-595"><span>We fixed an issue which could prevent an @ mention if the @ symbol was placed after certain characters</span></span></span></div>


- <div><span data-ttu-id="161f7-596"><span>Wir haben ein Problem behoben, das beim Löschen von @Erwähnungen zum Absturz führen konnte.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-596"><span>We fixed an issue which could sometimes cause a crash when deleting @ mentions</span></span></span></div>


- <div><span data-ttu-id="161f7-597"><span>Es wurde ein Problem behoben, durch das die korrekte Anzeige von Emojis in Kommentarkarten verhindert wurde.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-597"><span>We fixed an issue which prevented emojis from displaying correctly in comment cards</span></span></span></div>


- <div><span data-ttu-id="161f7-598"><span>Es wurde ein Problem mit Active Clipboard behoben, das manchmal zum Absturz führen konnte.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-598"><span>We fixed an issue with Active Clipboard which could sometimes result in a crash</span></span></span></div>


- <div><span data-ttu-id="161f7-599"><span>Wir haben ein Problem behoben, durch das die Schaltflächen für die Symbolleiste für den Schnellzugriff nicht mehr funktionierte.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-599"><span>We fixed an issue which could cause the Quick Access Toolbar buttons to stop working</span></span></span></div>


- <div><span data-ttu-id="161f7-600"><span>Wir haben ein Problem behoben, durch das das Wechseln der Dokumentformatierungsvorschau in den Hintergrund verhindert werden konnte.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-600"><span>We fixed an issue which could prevent the Document Formatting Preview from switching to the background</span></span></span></div>

### <a name="onenote"></a><span data-ttu-id="161f7-601">OneNote</span><span class="sxs-lookup"><span data-stu-id="161f7-601">OneNote</span></span>

- <span data-ttu-id="161f7-602">Ein Problem wurde behoben, bei dem die Namen von Abschnitten in der Dropdownliste „Abschnitt“ nicht dargestellt wurden, wenn das Office-Design auf „schwarz“ festgelegt war.</span><span class="sxs-lookup"><span data-stu-id="161f7-602">We fixed an issue where the names of sections appear blank in the section dropdown list when Office Theme is set to Black.</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-603">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-603">Outlook</span></span>

- <div><span data-ttu-id="161f7-604"><span>Wir haben ein Problem beim Senden von Ereignissen behoben, das dazu führen konnte, dass Outlook wiederholt fokussiert und den Fokus verliert.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-604"><span>We fixed an issue with Send Events which could cause Outlook to repeatedly gain and lose focus</span></span></span></div>


- <div><span data-ttu-id="161f7-605"><span>Es wurde ein Problem behoben, durch das die Verknüpfung „Antwort im Ordner bereitstellen“ nicht funktionierte.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-605"><span>We fixed an issue which prevented the Post Reply to Folder shortcut from working</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="161f7-606">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-606">PowerPoint</span></span>

- <div><span data-ttu-id="161f7-607"><span>Es wurde ein Problem mit der geschützten Ansicht behoben, das manchmal bei der Zusammenarbeit zu Problemen führen konnte.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-607"><span>We fixed an issue with Protected View which could sometimes cause problems when collaborating</span></span></span></div>


- <div><span data-ttu-id="161f7-608"><span>Es wurde ein Problem behoben, das verhindern konnte, dass Aufgaben in Kommentarbereichen korrekt angezeigt werden.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-608"><span>We fixed an issue which could prevent tasks in comment panes from displaying properly</span></span></span></div>


- <div><span data-ttu-id="161f7-609"><span>Ein Problem wurde behoben, das beim Einfügen neuer Folien zum Absturz führen konnte.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-609"><span>We fixed an issue which could cause a crash when inserting new slides</span></span></span></div>


### <a name="user-lifecycle"></a><span data-ttu-id="161f7-610">Lebenszyklus des Benutzers:</span><span class="sxs-lookup"><span data-stu-id="161f7-610">User Lifecycle</span></span>

- <div><span data-ttu-id="161f7-611"><span>Es wurde ein Problem behoben, das manchmal dazu führte, dass Abonnementfeatures nicht mehr angezeigt wurden.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-611"><span>We fixed an issue which could sometimes result in subscription features disappearing</span></span></span></div>


### <a name="word"></a><span data-ttu-id="161f7-612">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-612">Word</span></span>

- <div><span data-ttu-id="161f7-613"><span>Es wurde ein Problem behoben, durch das Hyperlinks fehlerhaft sein konnten, wenn sie bestimmte Zeichen enthielten.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-613"><span>We fixed an issue where hyperlinks could be broken if the hyperlink contained certain characters</span></span></span></div>


- <div><span data-ttu-id="161f7-614"><span>Ein Problem wurde behoben, bei dem beim Anzeigen eines Kommentars für ein Bild dieses manchmal nicht in der korrekten Größe dargestellt wurde.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-614"><span>We fixed an issue where images could be improperly sized when viewing a comment for that image</span></span></span></div>


- <div><span data-ttu-id="161f7-615"><span>Es wurde ein Problem mit dem Dropdownmenü „Aufzählung“ behoben, das manchmal zu einem Absturz führten konnte.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-615"><span>We fixed an issue with the Bullet List drop down menu which could sometimes result in a crash</span></span></span></div>





## <a name="august-09-2019br"></a><span data-ttu-id="161f7-616">**09. August 2019**</span><span class="sxs-lookup"><span data-stu-id="161f7-616">**August 09, 2019**</span></span><br/>
<span data-ttu-id="161f7-617">Version 1909 (Build 12001.20000)</span><span class="sxs-lookup"><span data-stu-id="161f7-617">Version 1909 (Build 12001.20000)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="161f7-618">Excel-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="161f7-618">Excel Feature updates:</span></span>

- <span data-ttu-id="161f7-619">**Zusammenarbeiten ist jetzt noch einfacher:** Verbesserungen bei der gemeinsamen Dokumenterstellung führen dazu, dass Ihre Änderungen beim Arbeiten mit bedingter Formatierung, Zellformatvorlagen und mehr nahtlos mit denen Ihrer Mitarbeiter zusammengeführt werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-619">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>


- <span data-ttu-id="161f7-620">**Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können.</span><span class="sxs-lookup"><span data-stu-id="161f7-620">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="161f7-621">Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="161f7-621">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="office-suite-feature-updates"></a><span data-ttu-id="161f7-622">Office-Suite-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="161f7-622">Office Suite Feature updates:</span></span>

- <span data-ttu-id="161f7-623">**Neue Office-App-Symbole:** Neu gestaltete App-Symbole, die die einfache, leistungsstarke und intelligente Oberfläche von Office widerzuspiegeln.</span><span class="sxs-lookup"><span data-stu-id="161f7-623">**New Office app icons:** Redesigned app icons to reflect the simple, powerful, and intelligent experiences of Office</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="161f7-624">Outlook-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="161f7-624">Outlook Feature updates:</span></span>

- <span data-ttu-id="161f7-625">**Erweiterter Schutz gegen Angriffe:** Mit Office 365 Advanced Threat Protection sind Sie vor Angriffen durch Links in E-Mail-Betreffzeilen, angefügten Nachrichten, signierten Nachrichten, Netzwerkpfaden usw. geschützt.</span><span class="sxs-lookup"><span data-stu-id="161f7-625">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>


- <span data-ttu-id="161f7-626">**Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können.</span><span class="sxs-lookup"><span data-stu-id="161f7-626">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="161f7-627">Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="161f7-627">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="161f7-628">PowerPoint-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="161f7-628">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="161f7-629">**Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können.</span><span class="sxs-lookup"><span data-stu-id="161f7-629">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="161f7-630">Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="161f7-630">And when you're selecting, the Insert button tells you how many you've picked.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="161f7-631">Word-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="161f7-631">Word Feature updates:</span></span>

- <span data-ttu-id="161f7-632">**Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.</span><span class="sxs-lookup"><span data-stu-id="161f7-632">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>


- <span data-ttu-id="161f7-633">**Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können.</span><span class="sxs-lookup"><span data-stu-id="161f7-633">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="161f7-634">Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="161f7-634">And when you're selecting, the Insert button tells you how many you've picked.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="161f7-635">Nicht sicherheitsrelevante Updates:</span><span class="sxs-lookup"><span data-stu-id="161f7-635">Non-security updates:</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-636">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-636">Outlook</span></span>

- <div><span data-ttu-id="161f7-637"><span>Ein Problem wurde behoben, das dazu führte, dass Besprechungsempfänger zwei Benachrichtigungen erhielten, nachdem eine Besprechung abgebrochen wurde</span></span><span class="sxs-lookup"><span data-stu-id="161f7-637"><span>We fixed an issue which caused meeting recipients to receive two notifications after a meeting was cancelled</span></span></span></div>


### <a name="powerpoint"></a><span data-ttu-id="161f7-638">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-638">PowerPoint</span></span>

- <div><span data-ttu-id="161f7-639"><span>Ein Problem wurde behoben, durch das ein Absturz verursacht werden konnte, wenn der Benutzer für Formen und Symbole "Keine Kontur" oder "Keine Füllung" auswählte</span></span><span class="sxs-lookup"><span data-stu-id="161f7-639"><span>We fixed an issue which could cause a crash when the user selected No Outline or No Fill for Shapes and Icons</span></span></span></div>





## <a name="august-02-2019br"></a><span data-ttu-id="161f7-640">**02. August 2019**</span><span class="sxs-lookup"><span data-stu-id="161f7-640">**August 02, 2019**</span></span><br/>
<span data-ttu-id="161f7-641">Version 1908 (Build 11929.20002)</span><span class="sxs-lookup"><span data-stu-id="161f7-641">Version 1908 (Build 11929.20002)</span></span><br/>

### <a name="excel-feature-updates"></a><span data-ttu-id="161f7-642">Excel-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="161f7-642">Excel Feature updates:</span></span>

- <span data-ttu-id="161f7-643">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="161f7-643">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="161f7-644">**Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente:** Sie können eine Vertraulichkeitsbezeichnung auf Ihre Dateien und E-Mails anwenden, damit sie den Richtlinien zum Datenschutz Ihrer Organisation entsprechen.</span><span class="sxs-lookup"><span data-stu-id="161f7-644">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="outlook-feature-updates"></a><span data-ttu-id="161f7-645">Outlook-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="161f7-645">Outlook Feature updates:</span></span>

- <span data-ttu-id="161f7-646">**Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente:** Sie können eine Vertraulichkeitsbezeichnung auf Ihre Dateien und E-Mails anwenden, damit sie den Richtlinien zum Datenschutz Ihrer Organisation entsprechen.</span><span class="sxs-lookup"><span data-stu-id="161f7-646">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="powerpoint-feature-updates"></a><span data-ttu-id="161f7-647">PowerPoint-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="161f7-647">PowerPoint Feature updates:</span></span>

- <span data-ttu-id="161f7-648">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="161f7-648">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="161f7-649">**Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente:** Sie können eine Vertraulichkeitsbezeichnung auf Ihre Dateien und E-Mails anwenden, damit sie den Richtlinien zum Datenschutz Ihrer Organisation entsprechen.</span><span class="sxs-lookup"><span data-stu-id="161f7-649">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>


### <a name="word-feature-updates"></a><span data-ttu-id="161f7-650">Word-Featureupdates:</span><span class="sxs-lookup"><span data-stu-id="161f7-650">Word Feature updates:</span></span>

- <span data-ttu-id="161f7-651">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="161f7-651">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>


- <span data-ttu-id="161f7-652">**Anders ausgedrückt:** Wenn Sie etwas anders formulieren möchten, hilft Ihnen „Neu schreiben“ dabei.</span><span class="sxs-lookup"><span data-stu-id="161f7-652">**Say it another way:** When you want to say it differently, Rewrite is there to help.</span></span> <span data-ttu-id="161f7-653">„Neu schreiben“ bietet Alternativen zum Verbessern Ihrer Formulierungen.</span><span class="sxs-lookup"><span data-stu-id="161f7-653">Rewrite offers alternatives for finessing your phrases.</span></span>


- <span data-ttu-id="161f7-654">**Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente:** Sie können eine Vertraulichkeitsbezeichnung auf Ihre Dateien und E-Mails anwenden, damit sie den Richtlinien für den Datenschutz Ihrer Organisation entsprechen.</span><span class="sxs-lookup"><span data-stu-id="161f7-654">**Apply sensitivity labels to your documents:** Apply sensitivity labels to your files and emails to keep them compliant with your organization's information protection policies.</span></span>




## <a name="non-security-updates"></a><span data-ttu-id="161f7-655">Nicht sicherheitsrelevante Updates:</span><span class="sxs-lookup"><span data-stu-id="161f7-655">Non-security updates:</span></span>

### <a name="access"></a><span data-ttu-id="161f7-656">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-656">Access</span></span>
- <span data-ttu-id="161f7-657">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-657">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-658">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-658">Excel</span></span>

- <div><span data-ttu-id="161f7-659"><span>Es wurde ein Problem behoben, bei dem es so aussah, als ob die Option &quot;Alle Beschriftungen wiederholen&quot; beim Drucken in eine PDF-Datei angewendet wurde.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-659"><span>We fixed an issue which made it appear as though &quot;repeat all labels&quot; was applied when printing to a PDF</span></span></span></div>

### <a name="office-suite"></a><span data-ttu-id="161f7-660">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="161f7-660">Office Suite</span></span>

- <div><span data-ttu-id="161f7-661"><span>Es wurde ein Problem behoben, durch das verhindert wurde, dass Benutzer ein Dokument auf dem Desktop öffnen.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-661"><span>We fixed an issue which could have prevented users from opening a document from the desktop</span></span></span></div>

- <div><span data-ttu-id="161f7-662"><span>Es wurde ein Problem behoben, bei dem ein Upgrade durch eine falsche Fehlermeldung bei &quot;Es wird bereits eine andere Installation ausgeführt&quot;</span> verhindert wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-662"><span>We fixed an issue where an upgrade could be prevented by a incorrect error message of &quot;Another install in progress&quot;</span></span></span></div>

- <div><span data-ttu-id="161f7-663"><span>Es wurde ein Problem behoben, bei dem einem Benutzer beim Installieren von Sicherheitsupdates Fehlermeldungen angezeigt wurden.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-663"><span>We fixed an issue where a user could see error messages when security updates are installed</span></span></span></div>

- <div><span data-ttu-id="161f7-664"><span>Es wurde ein Problem behoben, aufgrund dessen der Cursor verschwand.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-664"><span>We fixed an issue which could cause the cursor to disappear</span></span></span></div>

- <div><span data-ttu-id="161f7-665"><span>Wir haben ein Problem behoben, bei dem für einen Benutzer standardmäßig die Registerkarte „Zeichnen“ der Registerkarte „Start“ angezeigt wurde.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-665"><span>We fixed an issue where a user could be defaulted to the draw tab instead of the home tab</span></span></span></div>

- <div><span data-ttu-id="161f7-666"><span>Es wurde ein Problem behoben, bei dem große Strukturansichten zu einem Absturz führten.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-666"><span>We fixed an issue where large tree views could result in a crash</span></span></span></div>

### <a name="outlook"></a><span data-ttu-id="161f7-667">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-667">Outlook</span></span>

- <div></div><span data-ttu-id="161f7-668"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Es wurde ein Problem behoben, durch das wiederholte Kennworteingabeaufforderungen verursacht werden können.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-668"><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">We fixed an issue that can cause repeated password prompts</span></span></span>

- <div><span data-ttu-id="161f7-669"><span>Es wurde ein Problem behoben, durch das verhindert wurde, dass eine E-Mail-Adresse korrekt abgefragt wird.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-669"><span>We fixed an issue which could prevent an email address from being queried correctly</span></span></span></div>

- <div><span data-ttu-id="161f7-670"><span>Es wurde ein Problem behoben, durch das verhindert wurde, dass Benutzer Kalenderelemente öffnen, die von älteren Versionen von Outlook erstellt wurden.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-670"><span>We fixed an issue which could prevent users from opening calendar items created by legacy versions of Outlook</span></span></span></div>

### <a name="powerpoint"></a><span data-ttu-id="161f7-671">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-671">PowerPoint</span></span>

- <div><span data-ttu-id="161f7-672"><span>Es wurde ein Problem behoben, durch das verhindert wurde, dass einige Animationen gestartet werden.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-672"><span>We fixed an issue which could prevent some animations from starting</span></span></span></div>

### <a name="project"></a><span data-ttu-id="161f7-673">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-673">Project</span></span>
- <span data-ttu-id="161f7-674">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-674">Various performance and stability fixes</span></span>

### <a name="word"></a><span data-ttu-id="161f7-675">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-675">Word</span></span>

- <div><span data-ttu-id="161f7-676"><span>Es wurde ein Problem behoben, bei dem Antworten auf Kommentare in falscher Reihenfolge angezeigt wurden.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-676"><span>We fixed an issue where replies to comments could appear out of order</span></span></span></div>

- <div><span data-ttu-id="161f7-677"><span>Es wurde ein Problem behoben, bei dem in manchen Fällen Hinweise anstelle von Kommentaren angezeigt wurden.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-677"><span>We fixed an issue where in some situations, hints would be displayed instead of comments</span></span></span></div>

- <div><span data-ttu-id="161f7-678"><span>Es wurde ein Problem behoben, bei dem der Bereich „Überprüfungen“ angezeigt wurde, wenn der Benutzer versuchte, einen neuen Kommentar hinzuzufügen.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-678"><span>We fixed an issue where the Revisions Pane could display when the user tried to add a new comment</span></span></span></div>

- <div><span data-ttu-id="161f7-679"><span>Es wurde ein Problem behoben, durch das verhindert wurde, dass die Dropdownliste „Rückgängig machen“ angezeigt wird.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-679"><span>We fixed an issue which could prevent the undo dropdown list from appearing</span></span></span></div>

- <div><span data-ttu-id="161f7-680"><span>Es wurde ein Problem behoben, durch das verhindert wurde, das Kommentare hinzugefügt werden.</span></span><span class="sxs-lookup"><span data-stu-id="161f7-680"><span>We fixed an issue which could prevent comments from being added</span></span></span></div>


## <a name="july-26-2019"></a><span data-ttu-id="161f7-681">26. Juli 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-681">July 26, 2019</span></span>
<span data-ttu-id="161f7-682">Version 1908 (Build 11916.20000)</span><span class="sxs-lookup"><span data-stu-id="161f7-682">Version 1908 (build 11916.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-683">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="161f7-683">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="161f7-684">Word, Excel, PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-684">Word, Excel, PowerPoint</span></span>

#### <a name="create-more-accessible-pdfs"></a><span data-ttu-id="161f7-685">Erstellen von barrierefreien PDF-Dateien</span><span class="sxs-lookup"><span data-stu-id="161f7-685">Create more accessible PDFs</span></span>

<span data-ttu-id="161f7-686">Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten.</span><span class="sxs-lookup"><span data-stu-id="161f7-686">Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-687">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-687">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="161f7-688">Alle</span><span class="sxs-lookup"><span data-stu-id="161f7-688">All</span></span>

- <span data-ttu-id="161f7-689">Ein Problem wurde behoben, bei dem die Zuordnung von Dateitypen und Symbolen für Office nach einem Office-Update manchmal entfernt wurden</span><span class="sxs-lookup"><span data-stu-id="161f7-689">We fixed an issue where file type association and icons for Office could sometimes break after an Office Update</span></span>

### <a name="word"></a><span data-ttu-id="161f7-690">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-690">Word</span></span> 
- <span data-ttu-id="161f7-691">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-691">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-692">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-692">Excel</span></span>
- <span data-ttu-id="161f7-693">Ein Problem wurde behoben, bei dem das Verschieben eines Diagramms manchmal zu einem Absturz führte</span><span class="sxs-lookup"><span data-stu-id="161f7-693">We fixed an issue where moving a chart could sometimes result in a crash</span></span>
- <span data-ttu-id="161f7-694">Ein Problem wurde behoben, bei dem das Abrufen eines Arbeitsmappenobjekts aus einem Diagrammobjekt nach dem Ändern von Diagrammtypen manchmal zu einem Fehler führte</span><span class="sxs-lookup"><span data-stu-id="161f7-694">We fixed an issue where to get Workbook object from Chart object after changing chart types could sometimes result in an error</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-695">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-695">PowerPoint</span></span>
- <span data-ttu-id="161f7-696">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-696">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-697">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-697">Outlook</span></span>
- <span data-ttu-id="161f7-698">Ein Problem wurde behoben, bei dem im vereinfachten Menüband ein deaktiviertes Steuerelement manchmal nicht grau dargestellt wurde</span><span class="sxs-lookup"><span data-stu-id="161f7-698">We fixed an issue where in simplified ribbon, a disabled control could sometimes not be greyed out in the ribbon</span></span>

### <a name="access"></a><span data-ttu-id="161f7-699">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-699">Access</span></span>
- <span data-ttu-id="161f7-700">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-700">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="161f7-701">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-701">Project</span></span>
- <span data-ttu-id="161f7-702">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-702">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-19-2019"></a><span data-ttu-id="161f7-703">19. Juli 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-703">July 19, 2019</span></span>
<span data-ttu-id="161f7-704">Version 1908 (build 11911.20000)</span><span class="sxs-lookup"><span data-stu-id="161f7-704">Version 1908 (build 11911.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-705">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="161f7-705">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="161f7-706">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-706">Word</span></span>

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a><span data-ttu-id="161f7-707">Informationen zur Bedeutung von Abkürzungen beim Lesen in Word Online</span><span class="sxs-lookup"><span data-stu-id="161f7-707">Learn what Acronyms mean when you read in Word Online</span></span>

<span data-ttu-id="161f7-708">Wenn Sie auf eine Abkürzung treffen, versuchen wir, diese mithilfe von Daten innerhalb Ihrer Organisation zu definieren.</span><span class="sxs-lookup"><span data-stu-id="161f7-708">When you encounter an Acronym, we'll try to define it using data from within your organization.</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="161f7-709">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-709">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="161f7-710">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-710">Word</span></span> 
- <span data-ttu-id="161f7-711">Das Problem des fehlenden BookMarkEnd-Tags wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="161f7-711">We fixed an issue which BookMarkEnd tag was missing.</span></span>
- <span data-ttu-id="161f7-712">Ein Problem wurde behoben, bei dem sich die Schriftartauswahl bei der Eingabe von Sonderzeichen ändern konnte</span><span class="sxs-lookup"><span data-stu-id="161f7-712">We fixed an issue where the font selection could change while the user was typing special characters</span></span>
- <span data-ttu-id="161f7-713">Ein Problem wurde behoben, das manchmal dazu führen könnte, dass Antworten auf eine neue Kommentarkarte leer waren</span><span class="sxs-lookup"><span data-stu-id="161f7-713">We fixed an issue which could sometimes cause blank replies to a new comment card</span></span>
- <span data-ttu-id="161f7-714">Ein Problem wurde behoben, das dazu führen könnte, dass Formatierungen beim Teilen einer E-Mail-Nachricht verloren gingen</span><span class="sxs-lookup"><span data-stu-id="161f7-714">We fixed an issue which could cause formatting to be lost when sharing an email</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-715">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-715">Excel</span></span>
- <span data-ttu-id="161f7-716">Ein Problem wurde behoben, durch das ein Array mit einem großen Bereich manchmal einen Absturz verursachte</span><span class="sxs-lookup"><span data-stu-id="161f7-716">We fixed an issue where an array with a large range could sometimes cause a crash</span></span>
- <span data-ttu-id="161f7-717">Die Leistung beim Kopieren von Daten aus gefilterten Bereichen wurde erheblich verbessert</span><span class="sxs-lookup"><span data-stu-id="161f7-717">We significantly improved the performance of copying data from filtered ranges</span></span>
- <span data-ttu-id="161f7-718">Ein Problem wurde behoben, durch das einige Dateien, deren Dateinamen Sonderzeichen enthielten, nicht geöffnet wurden</span><span class="sxs-lookup"><span data-stu-id="161f7-718">We fixed an issue which prevented some files from opening if the filenames contained special characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-719">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-719">PowerPoint</span></span>
- <span data-ttu-id="161f7-720">Ein Problem wurde behoben, bei dem der Abschnittname für den neu erstellten Abschnitt in PowerPoint nicht standardmäßig aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="161f7-720">We fixed an issue where section name was not selected by default for newly created section in PowerPoint.</span></span>
- <span data-ttu-id="161f7-721">Ein Problem wurde behoben, durch das die Verwendung der Benutzeroberfläche in einer 4:3-Anzeige schwierig war</span><span class="sxs-lookup"><span data-stu-id="161f7-721">We fixed an issue which could cause the UI to become difficult to use when using a 4:3 display</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-722">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-722">Outlook</span></span>
- <span data-ttu-id="161f7-723">Ein Problem wurde behoben, durch das verfügbare Räume möglicherweise nicht aufgeführt wurden</span><span class="sxs-lookup"><span data-stu-id="161f7-723">We fixed an issue which could prevent available rooms from being listed</span></span>
- <span data-ttu-id="161f7-724">Ein Problem wurde behoben, durch das einige POP3-Benutzer keine HTML-Formatierungen verwenden konnten</span><span class="sxs-lookup"><span data-stu-id="161f7-724">We fixed an issue which prevented HTML formatting for some POP3 users</span></span>

### <a name="access"></a><span data-ttu-id="161f7-725">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-725">Access</span></span>
- <span data-ttu-id="161f7-726">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-726">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="161f7-727">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-727">Project</span></span>
- <span data-ttu-id="161f7-728">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-728">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-12-2019"></a><span data-ttu-id="161f7-729">12. Juli 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-729">July 12, 2019</span></span>
<span data-ttu-id="161f7-730">Version 1907 (Build 11901.20038)</span><span class="sxs-lookup"><span data-stu-id="161f7-730">Version 1907 (build 11901.20038)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-731">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="161f7-731">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-732">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-732">PowerPoint</span></span>
 
#### <a name="use-ink-replay-in-your-presentations"></a><span data-ttu-id="161f7-733">Verwenden von Freihand-Wiedergabe in Präsentationen</span><span class="sxs-lookup"><span data-stu-id="161f7-733">Use ink replay in your presentations</span></span>
 
<span data-ttu-id="161f7-734">Verwenden Sie Wiedergabe-Animationen für Freihand in PowerPoint, um in Präsentationen mehr auszudrücken und zu kommunizieren.</span><span class="sxs-lookup"><span data-stu-id="161f7-734">Apply a replay animation for ink in PowerPoint to express and communicate more in presentations.</span></span> 

## <a name="notable-fixes"></a><span data-ttu-id="161f7-735">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-735">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="161f7-736">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-736">Word</span></span> 
- <span data-ttu-id="161f7-737">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-737">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-738">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-738">Excel</span></span>
- <span data-ttu-id="161f7-739">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-739">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-740">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-740">PowerPoint</span></span>
- <span data-ttu-id="161f7-741">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-741">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-742">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-742">Outlook</span></span>
- <span data-ttu-id="161f7-743">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-743">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="161f7-744">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-744">Access</span></span>
- <span data-ttu-id="161f7-745">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-745">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="161f7-746">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-746">Project</span></span>
- <span data-ttu-id="161f7-747">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-747">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="july-5-2019"></a><span data-ttu-id="161f7-748">5. Juli 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-748">July 5, 2019</span></span>
<span data-ttu-id="161f7-749">Version 1907 (Build 11901.20018)</span><span class="sxs-lookup"><span data-stu-id="161f7-749">Version 1907 (build 11901.20018)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-750">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="161f7-750">What's New:</span></span>

### <a name="word-excel-powerpoint"></a><span data-ttu-id="161f7-751">Word, Excel, PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-751">Word, Excel, PowerPoint</span></span>

#### <a name="sketchy-shapes"></a><span data-ttu-id="161f7-752">Skizzenhafte Formen!</span><span class="sxs-lookup"><span data-stu-id="161f7-752">Sketchy Shapes!</span></span>

<span data-ttu-id="161f7-753">Mitten im Entwurfs einer Präsentation?</span><span class="sxs-lookup"><span data-stu-id="161f7-753">In the middle of drafting a presentation?</span></span> <span data-ttu-id="161f7-754">Wenden Sie die Formatvorlage "Skizzenhaft" an, um anzuzeigen, dass Sie zurzeit noch am Entwurf arbeiten.</span><span class="sxs-lookup"><span data-stu-id="161f7-754">Apply the sketchy style to show that you're still working on it.</span></span> <span data-ttu-id="161f7-755">Dies verleiht Ihren Objekten eine persönliche Note, ohne sie in von Hand gezeichnete Freiformobjekte umzuwandeln.</span><span class="sxs-lookup"><span data-stu-id="161f7-755">It gives a personal touch to your objects without turning it into a free form, hand-drawn shapes.</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-756">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-756">Excel</span></span>

- <span data-ttu-id="161f7-757">**Schnellere Dateifreigabe**: Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="161f7-757">**Faster file sharing**: Share your documents right from the recently used list without having to open the file.</span></span>
### <a name="powerpoint"></a><span data-ttu-id="161f7-758">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-758">PowerPoint</span></span>

- <span data-ttu-id="161f7-759">**Um den Zugriff zu erleichtern, wurde die Einstellung zum Drucken von Foliennummern in Handzetteln wurde in das Menü „Drucken“ verschoben:** Sie finden sie in der Dropdownliste Druck > Drucklayout, wenn ein Handzettellayout ausgewählt ist.</span><span class="sxs-lookup"><span data-stu-id="161f7-759">**The setting to Print Slide Numbers in Handouts has been moved to the Print Menu for easier access:**  Find it in the Print > Print Layout dropdown when a Handout layout is selected.</span></span> <span data-ttu-id="161f7-760">Auf diese Weise können Sie die Einstellung auch für einzelne Präsentationen ganz einfach umschalten.</span><span class="sxs-lookup"><span data-stu-id="161f7-760">This also allows the setting to be easily toggled per presentation.</span></span> [<span data-ttu-id="161f7-761">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="161f7-761">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="161f7-762">**Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="161f7-762">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

### <a name="word"></a><span data-ttu-id="161f7-763">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-763">Word</span></span>

- <span data-ttu-id="161f7-764">**Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="161f7-764">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-765">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-765">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="161f7-766">Alle</span><span class="sxs-lookup"><span data-stu-id="161f7-766">All</span></span>
- <span data-ttu-id="161f7-767">Die Leistung der Menüband-Zugriffstasteninfos wurde erheblich verbessert</span><span class="sxs-lookup"><span data-stu-id="161f7-767">We significantly improved the performance of Ribbon KeyTips</span></span>
- <span data-ttu-id="161f7-768">Ein Problem wurde behoben, das verhinderte, dass das Dialogfeld "Erfahren Sie, was in Kürze verfügbar ist" ordnungsgemäß angezeigt wurde</span><span class="sxs-lookup"><span data-stu-id="161f7-768">We fixed an issue which prevented the "See what's coming soon" dialog from being displayed properly</span></span>
- <span data-ttu-id="161f7-769">Ein Problem wurde behoben, durch das Fotos im Katalogflyout für die gemeinsame Dokumenterstellung falsch ausgerichtet sein konnten</span><span class="sxs-lookup"><span data-stu-id="161f7-769">We fixed an issue which could cause Photos to be misaligned in the Co-auth Gallery flyout</span></span>

### <a name="word"></a><span data-ttu-id="161f7-770">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-770">Word</span></span> 
- <span data-ttu-id="161f7-771">Ein Problem wurde behoben, durch das manchmal das Hinzufügen neuer Kommentare verhindert wurde</span><span class="sxs-lookup"><span data-stu-id="161f7-771">We fixed an issue which could sometimes prevent new comments from being added</span></span>
- <span data-ttu-id="161f7-772">Ein Problem wurde behoben, durch das Tabellen manchmal einen Absturz verursachten</span><span class="sxs-lookup"><span data-stu-id="161f7-772">We fixed an issue where tables could sometimes cause a crash</span></span>
- <span data-ttu-id="161f7-773">Ein Problem wurde behoben, bei dem manchmal ungültige Daten ans Ende eines Seriendrucks angehängt wurden</span><span class="sxs-lookup"><span data-stu-id="161f7-773">We fixed an issue where invalid data could sometimes be added to the end of a mail merge</span></span>
- <span data-ttu-id="161f7-774">Ein Problem wurde behoben, durch das einige LaTeX-Gleichungen nicht ordnungsgemäß gerendert wurden</span><span class="sxs-lookup"><span data-stu-id="161f7-774">We fixed an issue which could cause some LaTeX equations to render incorrectly</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-775">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-775">Excel</span></span>
- <span data-ttu-id="161f7-776">Ein Problem wurde behoben, bei dem das Ändern von Diagrammtypen zu einer Laufzeitausnahme führen konnte</span><span class="sxs-lookup"><span data-stu-id="161f7-776">We fixed an issue where changing chart types could sometimes result in a runtime exception</span></span>
- <span data-ttu-id="161f7-777">Ein Problem wurde behoben, bei dem manchmal das falsche Menüband angezeigt wurde, wenn mehrere Fenster geöffnet waren</span><span class="sxs-lookup"><span data-stu-id="161f7-777">We fixed an issue where the incorrect ribbon could be displayed when multiple windows were open</span></span>
- <span data-ttu-id="161f7-778">Ein Problem wurde behoben, das einen Fehler verursachen konnte, wenn ein Makro eine zweite Instanz einer Arbeitsmappe öffnete</span><span class="sxs-lookup"><span data-stu-id="161f7-778">We fixed an issue which could cause an error when a macro opened a second instance of a workbook</span></span>
- <span data-ttu-id="161f7-779">Ein Problem wurde behoben, das beim Öffnen oder Erstellen einer Arbeitsmappe oder beim Wechseln zwischen Arbeitsmappen zu einem Absturz führen könnte</span><span class="sxs-lookup"><span data-stu-id="161f7-779">We fixed an issue which could cause a crash when opening or creating a workbook, or switching between workbooks</span></span>
- <span data-ttu-id="161f7-780">Ein Problem wurde behoben, das verhinderte, dass Benutzer eine aus Word erstellte PDF-Datei in Teams öffnen konnten</span><span class="sxs-lookup"><span data-stu-id="161f7-780">We fixed an issue preventing users from opening a PDF created from Word in Teams</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-781">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-781">PowerPoint</span></span>
- <span data-ttu-id="161f7-782">Ein Problem wurde behoben, durch das die Qualität eines Diagramms beim Export in eine PDF-Datei beeinträchtigt wurde</span><span class="sxs-lookup"><span data-stu-id="161f7-782">We fixed an issue which would degrade the quality of a chart when exported to a pdf</span></span>
- <span data-ttu-id="161f7-783">Ein Problem wurde behoben, durch das eine QuickInfo, die die Entfernung zur Mitte angibt, nicht angezeigt wurde</span><span class="sxs-lookup"><span data-stu-id="161f7-783">We fixed an issue which prevented a tooltip indicating the distance to center from displaying</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-784">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-784">Outlook</span></span>
- <span data-ttu-id="161f7-785">Ein Problem wurde behoben, das manchmal die Anzeige des Fehlers "Datenträger voll" verhinderte</span><span class="sxs-lookup"><span data-stu-id="161f7-785">We fixed an issue which could sometimes prevent a Disk Full error to be displayed</span></span>
- <span data-ttu-id="161f7-786">Ein Problem wurde behoben, das dazu führen könnte, dass Anlagen beim Aktualisieren einer Besprechungsanfrage dupliziert wurden</span><span class="sxs-lookup"><span data-stu-id="161f7-786">We fixed an issue which could cause attachments to become duplicated when updating a meeting request</span></span>

### <a name="access"></a><span data-ttu-id="161f7-787">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-787">Access</span></span>
- <span data-ttu-id="161f7-788">Ein Problem wurde behoben, durch das einige Abfragen keine großen ganzzahligen Werte mehr zurückgeben konnten</span><span class="sxs-lookup"><span data-stu-id="161f7-788">We fixed an issue which prevented some queries from returning large integer values</span></span>
- <span data-ttu-id="161f7-789">Ein Problem wurde behoben, durch das SQL-Textfeld nicht mehr bearbeitet werden konnte</span><span class="sxs-lookup"><span data-stu-id="161f7-789">We fixed an issue which could make the sql textbox uneditable</span></span>
- <span data-ttu-id="161f7-790">Ein Problem wurde behoben, bei dem QuickInfos auf einigen High DPI-Displays schwer zu erkennen waren</span><span class="sxs-lookup"><span data-stu-id="161f7-790">We fixed an issue where tooltips could be difficult to see on some High DPI displays</span></span>

### <a name="project"></a><span data-ttu-id="161f7-791">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-791">Project</span></span>
- <span data-ttu-id="161f7-792">Ein Problem wurde behoben, durch das Flagwerte in neuen Vorgängen nicht mehr bearbeitet werden konnten</span><span class="sxs-lookup"><span data-stu-id="161f7-792">We fixed an issue which could cause flag values to become uneditable in new tasks</span></span>
- <span data-ttu-id="161f7-793">Ein Problem wurde behoben, durch das eine Statusaktualisierung dazu führen konnte, dass das tatsächliche Anfangsdatum bei Aufgaben und Vorgängen nicht ordnungsgemäß festgelegt wurde</span><span class="sxs-lookup"><span data-stu-id="161f7-793">We fixed an issue which could cause a status update to improperly set Actual Start Date on Assignments and Tasks</span></span>
- <span data-ttu-id="161f7-794">Ein Problem wurde behoben, das dazu führen könnte, dass einige Ressourcen fälschlicherweise als überlastet angezeigt wurden</span><span class="sxs-lookup"><span data-stu-id="161f7-794">We fixed an issue which could cause some resources to incorreclty appear overallocated</span></span>
- <span data-ttu-id="161f7-795">Ein Problem wurde behoben, bei dem die Methode "TaskDependencies Add" beim Hinzufügen von "Lag", wenn das Dezimaltrennzeichen ein Komma war und bei einer Verbindung mit einem Server manchmal fehlschlug</span><span class="sxs-lookup"><span data-stu-id="161f7-795">We fixed an issue where the TaskDependencies Add method could fail when Lag is added, the decimal separator is a comma, and when connected to a server</span></span>
- <span data-ttu-id="161f7-796">Es wurde ein Problem behoben, durch das das Aktualisieren von lokalen Werten der Nachschlagetabelle für das benutzerdefinierte Feld über CSOM zum Absturz des PCs führen konnte</span><span class="sxs-lookup"><span data-stu-id="161f7-796">We fixed an issue where updating local custom field lookup table values via CSOM could crash PCS</span></span>
- <span data-ttu-id="161f7-797">Ein Problem wurde behoben, bei dem die Werte für die gesamte Arbeit falsch erscheinen können, wenn sie eine Dezimalzahl enthalten</span><span class="sxs-lookup"><span data-stu-id="161f7-797">We fixed an issue where the total work values may appear incorrect if they contain a decimal</span></span>

</BR></BR>

## <a name="june-28-2019"></a><span data-ttu-id="161f7-798">28. Juni 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-798">June 28, 2019</span></span>
<span data-ttu-id="161f7-799">Version 1907 (Build 11819.20002)</span><span class="sxs-lookup"><span data-stu-id="161f7-799">Version 1907 (build 11819.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-800">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="161f7-800">What's New:</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-801">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-801">Excel</span></span>

- <span data-ttu-id="161f7-802">**Schnelles Programmieren mit Power Query-Verbesserungen:** Mit AutoVervollständigen und farbiger Syntax können Sie Code schnell fertigstellen.</span><span class="sxs-lookup"><span data-stu-id="161f7-802">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="161f7-803">Außerdem können Sie auf einfache Weise Funktionen, Spalten und Parameter ermitteln.</span><span class="sxs-lookup"><span data-stu-id="161f7-803">Easily discover functions, columns, and parameters, too</span></span>

- <span data-ttu-id="161f7-804">**Verknüpfen von Tabellen in ähnlichen Spalten:** Abrufen & Transformieren (Power Query) bietet jetzt eine ungefähre Textübereinstimmungslogik (auch Fuzzy-Übereinstimmung genannt) beim Vergleichen von Spalten zum Zusammenführen von Tabellen.</span><span class="sxs-lookup"><span data-stu-id="161f7-804">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span>

### <a name="word"></a><span data-ttu-id="161f7-805">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-805">Word</span></span>

- <span data-ttu-id="161f7-806">**Verbesserungen bei der gemeinsamen Dokumenterstellung:** Verbesserte Zuverlässigkeit bei der gemeinsamen Dokumenterstellung.</span><span class="sxs-lookup"><span data-stu-id="161f7-806">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>
 
### <a name="word-excel-powerpoint-and-visio"></a><span data-ttu-id="161f7-807">Word, Excel, PowerPoint und Visio</span><span class="sxs-lookup"><span data-stu-id="161f7-807">Word, Excel, PowerPoint, and Visio</span></span>

#### <a name="recommended-documents"></a><span data-ttu-id="161f7-808">Empfohlene Dokumente</span><span class="sxs-lookup"><span data-stu-id="161f7-808">Recommended Documents</span></span>

<span data-ttu-id="161f7-809">Lassen Sie sich Dokumente mit für Sie relevanter Aktivität empfehlen.</span><span class="sxs-lookup"><span data-stu-id="161f7-809">Find documents with relevant activity recommended to you.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-810">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-810">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="161f7-811">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-811">Word</span></span> 
- <span data-ttu-id="161f7-812">Wir haben ein Problem behoben, welches einige Nutzer daran hindern konnte, einige .doc-Dateien zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="161f7-812">We fixed an issue which could prevent some .DOC files from opening</span></span>
- <span data-ttu-id="161f7-813">Wir haben ein Problem behoben, das gelegentlich verhindert hat, dass Kommentare richtig geladen wurden.</span><span class="sxs-lookup"><span data-stu-id="161f7-813">We fixed an issue which could have prevented comments from loading properly</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-814">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-814">Excel</span></span>
- <span data-ttu-id="161f7-815">Wir haben die Leistung von Power Queries verbessert.</span><span class="sxs-lookup"><span data-stu-id="161f7-815">We improved the performance of Power Queries</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-816">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-816">PowerPoint</span></span>
- <span data-ttu-id="161f7-817">Es wurde ein Problem mit der Verwendung eines Stifts auf einem Surface-Gerät behoben, der dazu führen konnte, dass der Bildschirm flackerte.</span><span class="sxs-lookup"><span data-stu-id="161f7-817">We fixed an issue related to using a pen on a Surface device which could cause the screen to flicker</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-818">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-818">Outlook</span></span>
- <span data-ttu-id="161f7-819">Wir haben ein Problem behoben, durch das der Frei/Gebucht-Status eines Termins bei der Konvertierung in eine Besprechung geändert werden konnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-819">We fixed an issue which could change the free/busy status of an appointment when converted to a meeting</span></span>
- <span data-ttu-id="161f7-820">Ein Problem wurde behoben, bei dem die falsche Vorlage und Beschreibung angezeigt wurden, wenn eine E-Mail mit einer Ad-hoc-Vorlage geschützt wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-820">We fixed an issue where the wrong template and description would be displayed when an e-mail was protected with an ad-hoc template</span></span>

### <a name="access"></a><span data-ttu-id="161f7-821">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-821">Access</span></span>
- <span data-ttu-id="161f7-822">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-822">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="161f7-823">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-823">Project</span></span>
- <span data-ttu-id="161f7-824">Verschiedene Korrekturen der Leistung und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-824">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-21-2019"></a><span data-ttu-id="161f7-825">21. Juni 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-825">June 21, 2019</span></span>
<span data-ttu-id="161f7-826">Version 1907 (build 11815.20002)</span><span class="sxs-lookup"><span data-stu-id="161f7-826">Version 1907 (build 11815.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-827">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="161f7-827">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-828">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-828">Outlook</span></span>

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a><span data-ttu-id="161f7-829">Dunkler Modus für "schwarzes Design" in Outlook-Desktop</span><span class="sxs-lookup"><span data-stu-id="161f7-829">Dark Mode for Black Theme in Outlook Desktop</span></span>

<span data-ttu-id="161f7-830">Im dunklen Modus wird nun Benutzern, die das Design "Schwarz" verwenden, auch der Lesebereich beim Lesen von E-Mails sowie die Verfassen-Oberfläche beim Schreiben von E-Mails mit einem dunklen Hintergrund angezeigt.</span><span class="sxs-lookup"><span data-stu-id="161f7-830">With dark mode, users in black theme will now also see the reading pane with a dark background when reading emails, and the compose experience with a dark background when writing emails.</span></span> <span data-ttu-id="161f7-831">Mit Hilfe eines Sonne/Mond-Schalters im Lesebereich und im Menüband können Benutzer in einer Vorschau ansehen, wie eine Nachricht hingegen mit einem hellen Hintergrund aussieht.</span><span class="sxs-lookup"><span data-stu-id="161f7-831">There is a sun/moon toggle on the reading pane and in the ribbon in case users want to preview what the message looks like with a light background instead.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="161f7-832">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-832">Getting Started:</span></span>

1. <span data-ttu-id="161f7-833">Wählen Sie das schwarze Design aus. Der dunkle Modus ist in diesem Fall standardmäßig aktiviert.</span><span class="sxs-lookup"><span data-stu-id="161f7-833">Turn on black theme and dark mode will be on by default.</span></span>
2. <span data-ttu-id="161f7-834">Verwenden Sie den Sonne/Mond-Schalter (im Lesebereich und im Menüband), um in einer Vorschau anzuzeigen, wie die Nachricht für Benutzer aussieht, die den dunklen Modus nicht aktiviert haben.</span><span class="sxs-lookup"><span data-stu-id="161f7-834">Use the moon/sun toggle (in the reading pane and in the ribbon) to preview what the message looks like for users not in dark mode</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-835">Szenarien zum Ausprobieren:</span><span class="sxs-lookup"><span data-stu-id="161f7-835">Scenarios to Try</span></span>

1. <span data-ttu-id="161f7-836">Lesen von E-Mails im dunklen Modus.</span><span class="sxs-lookup"><span data-stu-id="161f7-836">Read emails in dark mode.</span></span> <span data-ttu-id="161f7-837">Wenn Sie etwas nicht lesen können, verwenden Sie den Umschalter "Sonne" im Lesebereich, um zu einem hellen Hintergrund zu wechseln.</span><span class="sxs-lookup"><span data-stu-id="161f7-837">If you are unable to read something, use the sun toggle in the Reading Pane to switch to a light background.</span></span> 
2. <span data-ttu-id="161f7-838">Verfassen von E-Mails im dunklen Modus.</span><span class="sxs-lookup"><span data-stu-id="161f7-838">Compose emails in dark mode.</span></span> <span data-ttu-id="161f7-839">Zeigen Sie mit Hilfe des Sonne-Schalters im Menüband in einer Vorschau an, wie Ihre Nachricht mit einem hellen Hintergrund aussehen wird.</span><span class="sxs-lookup"><span data-stu-id="161f7-839">Preview what your message will look like with a light background by using the sun toggle in the ribbon.</span></span> 

<span data-ttu-id="161f7-840">Sollten einzelne E-Mails nicht korrekt dargestellt werden, senden Sie diese bitte (als Anlage) an OutlookDarkModeFail@service.microsoft.com</span><span class="sxs-lookup"><span data-stu-id="161f7-840">If you encounter any emails that don't render properly, please send them (as an attachment) to OutlookDarkModeFail@service.microsoft.com</span></span>

#### <a name="get-location-suggestions"></a><span data-ttu-id="161f7-841">Abrufen von Standortvorschlägen</span><span class="sxs-lookup"><span data-stu-id="161f7-841">Get location suggestions</span></span>

<span data-ttu-id="161f7-842">Beginnen Sie mit der Eingabe, Outlook wird automatisch nach passenden Orten suchen.</span><span class="sxs-lookup"><span data-stu-id="161f7-842">Start typing and Outlook will look for matching locations.</span></span>

<span data-ttu-id="161f7-843">Dies gilt für das Feld "Ort" beim Erstellen von Terminen und Besprechungen.</span><span class="sxs-lookup"><span data-stu-id="161f7-843">This applies to the Location field when creating Appointments and Meetings.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="161f7-844">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-844">Getting Started:</span></span>

- <span data-ttu-id="161f7-845">Erstellen Sie einen Termin oder eine Besprechung in einem O365- oder Outlook.com-Kalender in Outlook.</span><span class="sxs-lookup"><span data-stu-id="161f7-845">Create an Appointment or Meeting on an O365 or Outlook.com calendar in Outlook.</span></span> 
- <span data-ttu-id="161f7-846">Klicken Sie in das Feld "Ort", und beginnen Sie mit der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="161f7-846">Click into the Location field and start typing…</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-847">Szenarien zum Ausprobieren:</span><span class="sxs-lookup"><span data-stu-id="161f7-847">Scenarios to Try</span></span>

<span data-ttu-id="161f7-848">Wenn Sie einer Besprechung einen Konferenzraum hinzufügen möchten, klicken Sie auf das Feld "Ort", anstatt das "Raumsuche"-Add-in oder das Adressbuch zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="161f7-848">When adding a conference room to a meeting, click into Location field, rather than using Room Finder add-in or Address Book.</span></span>
<span data-ttu-id="161f7-849">Versuchen Sie für Termine an einem öffentlichen Ort – beispielsweise ein Restaurant, ein Coffeeshop oder eine Zahnartpraxis – den exakten Standort mithilfe der neuen Auswahl zu finden.</span><span class="sxs-lookup"><span data-stu-id="161f7-849">For appointments at a physical place with a public location - like a restaurant, coffee shop, or even your dentist's office - try finding the exact location using the new picker.</span></span> <span data-ttu-id="161f7-850">Auf diese Weise können Sie über Outlook Mobile benachrichtigt werden, wenn es Zeit ist, aufzubrechen.</span><span class="sxs-lookup"><span data-stu-id="161f7-850">This way, you'll be able to get notified on Outlook Mobile when it's time to leave.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-851">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-851">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="161f7-852">Alle</span><span class="sxs-lookup"><span data-stu-id="161f7-852">All</span></span>
- <span data-ttu-id="161f7-853">Wir haben ein Problem behoben, durch das das Suchfeld im Offlinemodus aktiviert blieb.</span><span class="sxs-lookup"><span data-stu-id="161f7-853">We fixed an issue which would keep the Search Box enabled while offline</span></span>

### <a name="word"></a><span data-ttu-id="161f7-854">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-854">Word</span></span> 
- <span data-ttu-id="161f7-855">Ein Problem wurde behoben, bei dem der Tastaturfokus manchmal schwierig zu erkennen war.</span><span class="sxs-lookup"><span data-stu-id="161f7-855">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>
- <span data-ttu-id="161f7-856">Ein Problem wurde behoben, bei dem der in ein neues Dokument eingefügte Text manchmal eine falsche Textausrichtung aufwies.</span><span class="sxs-lookup"><span data-stu-id="161f7-856">We fixed an issue where text pasted into a new document could sometimes have the wrong text alignment</span></span>
- <span data-ttu-id="161f7-857">Ein Problem wurde behoben, bei dem einige Benutzer nach dem Sperren des Computers keine Änderungen mehr speichern konnten.</span><span class="sxs-lookup"><span data-stu-id="161f7-857">We fixed an issue which could prevent some users from saving changes after suspending their computer</span></span>
- <span data-ttu-id="161f7-858">Es wurde ein Problem behoben, bei dem in bestimmten Fällen statt des ausgewählten Bereichs das komplette Dokument gedruckt wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-858">We fixed an issue where in certain cases an entire document would be printed instead of the selected range</span></span>
- <span data-ttu-id="161f7-859">Ein Problem wurde behoben, durch das Kommentare auf kleineren Displays schwer zu lesen waren.</span><span class="sxs-lookup"><span data-stu-id="161f7-859">We fixed an issue which could make comments difficult to read on smaller displays</span></span>
- <span data-ttu-id="161f7-860">Ein Problem wurde behoben, durch das beim Erfassen von Daten auf einem Gerät ein Absturz verursacht werden konnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-860">We fixed an issue which could cause a crash when capturing to a device</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-861">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-861">Excel</span></span>
- <span data-ttu-id="161f7-862">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-862">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-863">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-863">PowerPoint</span></span>
- <span data-ttu-id="161f7-864">Ein Problem wurde behoben, bei dem der Tastaturfokus manchmal schwierig zu erkennen war.</span><span class="sxs-lookup"><span data-stu-id="161f7-864">We fixed an issue where keyboard focus could sometimes be difficult to see</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-865">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-865">Outlook</span></span>
- <span data-ttu-id="161f7-866">Ein Problem wurde behoben, bei dem ein Add-In möglicherweise als aktiviert angezeigt wurde, auch wenn es nicht aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="161f7-866">We fixed an issue which could incorrectly display an add-in as being enabled when it was not.</span></span>
- <span data-ttu-id="161f7-867">Ein Problem wurde behoben, das dazu führte, dass einem Kunden möglicherweise nicht alle Aufbewahrungsrichtlinien angezeigt wurden, wenn sehr viele Aufbewahrungsrichtlinien vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="161f7-867">We fixed an issue which would prevent a customer from viewing all retention policies if there were a large number of them</span></span>

### <a name="access"></a><span data-ttu-id="161f7-868">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-868">Access</span></span>
- <span data-ttu-id="161f7-869">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-869">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="161f7-870">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-870">Project</span></span>
- <span data-ttu-id="161f7-871">Verschiedene Korrekturen der Leistung und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-871">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-14-2019"></a><span data-ttu-id="161f7-872">14. Juni 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-872">June 14, 2019</span></span>
<span data-ttu-id="161f7-873">Version 1907 (build 11807.20000)</span><span class="sxs-lookup"><span data-stu-id="161f7-873">Version 1907 (build 11807.20000)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-874">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-874">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="161f7-875">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-875">Word</span></span> 
- <span data-ttu-id="161f7-876">Es wurde ein Problem behoben, durch das Benutzer sich beim Speichern auf OneDrive nicht anmelden konnten.</span><span class="sxs-lookup"><span data-stu-id="161f7-876">We fixed an issue which could prevent a user from signing in when saving to OneDrive</span></span>
- <span data-ttu-id="161f7-877">Ein Problem wurde behoben, bei dem Benutzer daran gehindert werden konnten, SharePoint-Eigenschaften im eingeschränkten Zugriffsmodus zu ändern.</span><span class="sxs-lookup"><span data-stu-id="161f7-877">We fixed an issue where a user could be prevented from changing SharePoint properties while in restricted access mode</span></span>
- <span data-ttu-id="161f7-878">Es wurde ein Problem behoben, bei dem sich die Kopf- und Fußzeileninhalte beim Anpassen von Seitenrändern ändern konnten.</span><span class="sxs-lookup"><span data-stu-id="161f7-878">We fixed an issue where header and footer content could change when adjusting margins</span></span>
- <span data-ttu-id="161f7-879">Es wurde ein Problem behoben, bei dem die Formatierung beim Umschalten in die Webansicht unterbrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-879">We fixed an issue where formatting could break when switching to web view</span></span>
- <span data-ttu-id="161f7-880">Es wurde ein Problem behoben, durch das Benutzer daran gehindert werden konnten, benutzerdefinierte Felder beim Öffnen von SharePoint zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="161f7-880">We fixed an issue which could prevent a user from using custom fields when opened from SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-881">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-881">Excel</span></span>
- <span data-ttu-id="161f7-882">Ein Leistungsproblem wurde behoben, das beim Löschen von Zeilen einer gefilterten Gruppe auftrat.</span><span class="sxs-lookup"><span data-stu-id="161f7-882">We fixed a performance issue when deleting rows of a filtered set</span></span>
- <span data-ttu-id="161f7-883">Es wurde ein Problem behoben, das manchmal dazu führte, dass die Maus in der geschützten Anzeige flackert.</span><span class="sxs-lookup"><span data-stu-id="161f7-883">We fixed an issue which could sometimes cause the mouse to flicker in protected view</span></span>
- <span data-ttu-id="161f7-884">Wir haben ein Problem behoben, das beim Löschen einer Reihe zu einem Absturz führen konnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-884">We fixed an issue which could have caused a crash when deleting a series</span></span>
- <span data-ttu-id="161f7-885">Ein Problem wurde behoben, bei dem einige Benutzer die Möglichkeit hatten, Versionsverlauf hinzuzufügen, wenn diese Option nicht verfügbar war.</span><span class="sxs-lookup"><span data-stu-id="161f7-885">We fixed an issue where some users would have the option to add version history when that was not available</span></span>
- <span data-ttu-id="161f7-886">Wir haben ein Problem behoben, das bei Verwendung des Tools „Arbeitsblattabgleich“ eine Ausnahme verursacht hat.</span><span class="sxs-lookup"><span data-stu-id="161f7-886">We fixed an issue which could have caused an exception when using the Spreadsheet Compare tool</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-887">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-887">PowerPoint</span></span>
- <span data-ttu-id="161f7-888">Wir haben ein Problem behoben, durch das ein Absturz beim Klicken auf einen Link zu SharePoint verursacht werden konnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-888">We fixed an issue where a crash could occur when clicking a link to SharePoint</span></span>
- <span data-ttu-id="161f7-889">Wir haben ein Problem behoben, durch das der Benutzer zur nächsten Seite wechseln konnte, während er mit einem Surface-Stift tippte.</span><span class="sxs-lookup"><span data-stu-id="161f7-889">We fixed an issue which could switch the user to the next page while typing using a Surface Pen</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-890">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-890">Outlook</span></span>
- <span data-ttu-id="161f7-891">Ein Problem wurde behoben, bei dem in manchen Fällen das Feld „An“ größer als normal war.</span><span class="sxs-lookup"><span data-stu-id="161f7-891">We fixed an issue where in some cases the To field was larger than normal</span></span>

### <a name="access"></a><span data-ttu-id="161f7-892">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-892">Access</span></span>
- <span data-ttu-id="161f7-893">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-893">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="161f7-894">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-894">Project</span></span>
- <span data-ttu-id="161f7-895">Verschiedene Korrekturen der Leistung und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-895">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="june-7-2019"></a><span data-ttu-id="161f7-896">7. Juni 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-896">June 7, 2019</span></span>
<span data-ttu-id="161f7-897">Version 1907 (Build 11727.20064)</span><span class="sxs-lookup"><span data-stu-id="161f7-897">Version 1907 (build 11727.20064)</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-898">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-898">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="161f7-899">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-899">Word</span></span> 
- <span data-ttu-id="161f7-900">Ein Problem wurde behoben, bei dem Word manchmal abstürzt, wenn die AutoKorrektur so eingerichtet wurde, dass der erste Buchstabe eines Satzes groß geschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="161f7-900">We fixed an issue where Word could sometimes crash when autocorrect was set to capitalize the first letter of a sentence</span></span>
- <span data-ttu-id="161f7-901">Die Leistung beim Bearbeiten eines Dokuments in SharePoint wurde verbessert</span><span class="sxs-lookup"><span data-stu-id="161f7-901">We improved performance when editing a document on SharePoint</span></span>
- <span data-ttu-id="161f7-902">Ein Problem wurde behoben, bei dem vektorbasierte Bilder, die in Adobe Illustrator erstellt wurden, nicht ordnungsgemäß angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="161f7-902">We fixed an issue where vector-based images created in Adobe Illustrator would not display correctly</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-903">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-903">Excel</span></span>
- <span data-ttu-id="161f7-904">Ein Problem wurde behoben, bei dem die Sortierfelder beim Aufzeichnen eines Makros manchmal nicht ordnungsgemäß festgelegt wurden.</span><span class="sxs-lookup"><span data-stu-id="161f7-904">We fixed an issue where sorting fields were sometimes not set correctly when recording a macro</span></span>
- <span data-ttu-id="161f7-905">Ein Problem wurde behoben, das beim Neuberechnen einer Arrayformel ein Hängen oder einen Absturz verursacht.</span><span class="sxs-lookup"><span data-stu-id="161f7-905">We fixed an issue that causes hang or crash during recalculation of an array formula</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-906">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-906">PowerPoint</span></span>
- <span data-ttu-id="161f7-907">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-907">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-908">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-908">Outlook</span></span>
- <span data-ttu-id="161f7-909">Ein Problem wurde behoben, bei dem Inline-Anlagen manchmal nicht ordnungsgemäß skaliert wurden.</span><span class="sxs-lookup"><span data-stu-id="161f7-909">We fixed an issue where inline attachments would sometimes be incorrectly scaled</span></span>

### <a name="access"></a><span data-ttu-id="161f7-910">Zugriff</span><span class="sxs-lookup"><span data-stu-id="161f7-910">Access</span></span>
- <span data-ttu-id="161f7-911">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-911">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="161f7-912">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-912">Project</span></span>
- <span data-ttu-id="161f7-913">Ein Problem wurde behoben, bei dem Zeittabellen mit festgelegter Dauer manchmal den Endtermin der Aufgabe ändern konnten.</span><span class="sxs-lookup"><span data-stu-id="161f7-913">We fixed an issue where timesheets on a fixed duration could sometimes change the assignment finish date</span></span>
- <span data-ttu-id="161f7-914">Ein Problem wurde behoben, bei dem die Werte für den Prozentsatz der Komplettierung beim Öffnen eines Projekts aus einer früheren Version falsch sein konnten.</span><span class="sxs-lookup"><span data-stu-id="161f7-914">We fixed an issue where Percentage Complete values could be wrong when opening a project from an earlier version</span></span>

</BR></BR>

## <a name="may-31-2019"></a><span data-ttu-id="161f7-915">31. Mai 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-915">May 31, 2019</span></span>
<span data-ttu-id="161f7-916">Version 1906 (build 11722.20008)</span><span class="sxs-lookup"><span data-stu-id="161f7-916">Version 1906 (build 11722.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-917">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="161f7-917">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-918">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-918">Outlook</span></span>

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a><span data-ttu-id="161f7-919">Das Dialogfeld zum Kontaktieren des Supports ist jetzt andockbar und wird auf der rechten Seite angezeigt</span><span class="sxs-lookup"><span data-stu-id="161f7-919">Dialog for Contacting Support now is dockable and appears on the right</span></span>

<span data-ttu-id="161f7-920">Das zum Kontaktieren des Supports verwendete Dialogfeld wird jetzt in einem Bereich auf der rechten Seite angezeigt und beginnt als angedocktes Fenster.</span><span class="sxs-lookup"><span data-stu-id="161f7-920">The dialog used for Contacting support will now appear in a pane on the right and will start off as a docked window.</span></span>

#### <a name="ink-in-your-email"></a><span data-ttu-id="161f7-921">Freihand in Ihrer E-Mail!</span><span class="sxs-lookup"><span data-stu-id="161f7-921">Ink in Your Email!</span></span>

<span data-ttu-id="161f7-922">Sie können Bilder jetzt in Ihren Outlook-E-Mails zeichnen und kommentieren.</span><span class="sxs-lookup"><span data-stu-id="161f7-922">You can now draw and annotate pictures in your Outlook emails.</span></span>

### <a name="word"></a><span data-ttu-id="161f7-923">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-923">Word</span></span>

#### <a name="open-document-links-in-word"></a><span data-ttu-id="161f7-924">Öffnen von Dokument-Links in Word</span><span class="sxs-lookup"><span data-stu-id="161f7-924">Open document links in Word</span></span>

<span data-ttu-id="161f7-925">Wenn Sie in Office auf einen Dokument Link klicken, können Sie Ihre Einstellungen dahingehend aktualisieren, dass er standardmäßig in der Word-App geöffnet wird.</span><span class="sxs-lookup"><span data-stu-id="161f7-925">When you click a document link in Office, you can update your preference to open in the Word app by default.</span></span>  <span data-ttu-id="161f7-926">Um Ihre Einstellungen zu aktualisieren, wechseln Sie zu Datei > Optionen – > Erweitert-> Verhalten von Links.</span><span class="sxs-lookup"><span data-stu-id="161f7-926">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="161f7-927">Weitere Informationen: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="161f7-927">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="161f7-928">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-928">Getting Started:</span></span>

<span data-ttu-id="161f7-929">Das Feature wird standardmäßig auf aus eingestellt.</span><span class="sxs-lookup"><span data-stu-id="161f7-929">Feature will default to off.</span></span> <span data-ttu-id="161f7-930">Benutzer können es entweder über Optionen > Erweitert > Verhalten von Links aktivieren, oder sie können ihm zustimmen, wenn Sie von Win32-WXP-Apps durch eine Opt-In-Umgebung geleitet werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-930">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="161f7-931">Links werden standardmäßig in der entsprechenden Office-Anwendung anstelle des Browsers geöffnet, wenn Benutzer in Outlook, Word, PowerPoint oder Excel auf Links zu Word/PowerPoint/Excel-Dateien klicken, die auf OneDrive, OneDrive für Business oder in SharePoint gespeichert sind.</span><span class="sxs-lookup"><span data-stu-id="161f7-931">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="161f7-932">Um diese Standardeinstellung zu ändern, können Benutzer die folgende Einstellung in Outlook/Word/Excel/PowerPoint aktualisieren:</span><span class="sxs-lookup"><span data-stu-id="161f7-932">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="161f7-933">Datei –> Optionen –> Erweitert –> Verhalten von Links.</span><span class="sxs-lookup"><span data-stu-id="161f7-933">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="161f7-934">Diese Einstellung ist für Outlook/Word/PowerPoint/Excel freigegeben und kann in jeder dieser Apps festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-934">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-935">Szenarien zum Ausprobieren:</span><span class="sxs-lookup"><span data-stu-id="161f7-935">Scenarios to Try:</span></span>

<span data-ttu-id="161f7-936">Lösen Sie die Opt-in-Benutzererfahrung aus – öffnen eines Links zu einem Word-Dokument, das in OneDrive/SharePoint aus Outlook/Word/PowerPoint/Excel aus gespeichert ist – klicken Sie aus Office Online auf in Client öffnen – tun Sie dies zwei Mal in einem Zeitraum von 30 Tagen.</span><span class="sxs-lookup"><span data-stu-id="161f7-936">To trigger the opt-in experience - Open a link tot a Word document stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="161f7-937">Nachdem Sie die Einstellung gesetzt haben, werden Links standardmäßig in den Win32-Apps gestartet.</span><span class="sxs-lookup"><span data-stu-id="161f7-937">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-938">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-938">PowerPoint</span></span>

#### <a name="open-presentation-links-in-powerpoint"></a><span data-ttu-id="161f7-939">Öffnen Sie Präsentationslinks in PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-939">Open presentation links in PowerPoint</span></span>

<span data-ttu-id="161f7-940">Wenn Sie in Office auf einen Präsentationslink klicken, können Sie Ihre Einstellungen dahingehend aktualisieren, dass er standardmäßig in der PowerPoint-App geöffnet wird.</span><span class="sxs-lookup"><span data-stu-id="161f7-940">When you click a presentation link in Office, you can update your preference to open in the PowerPoint app by default.</span></span> <span data-ttu-id="161f7-941">Um Ihre Einstellungen zu aktualisieren, wechseln Sie zu Datei > Optionen – > Erweitert-> Verhalten von Links.</span><span class="sxs-lookup"><span data-stu-id="161f7-941">To update your preference go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="161f7-942">Weitere Informationen: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="161f7-942">Learn more: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="161f7-943">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-943">Getting Started:</span></span>

<span data-ttu-id="161f7-944">Das Feature wird standardmäßig auf aus eingestellt.</span><span class="sxs-lookup"><span data-stu-id="161f7-944">Feature will default to off.</span></span> <span data-ttu-id="161f7-945">Benutzer können es entweder über Optionen > Erweitert > Verhalten von Links aktivieren, oder sie können ihm zustimmen, wenn Sie von Win32-WXP-Apps durch eine Opt-In-Umgebung geleitet werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-945">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="161f7-946">Links werden standardmäßig in der entsprechenden Office-Anwendung anstelle des Browsers geöffnet, wenn Benutzer in Outlook, Word, PowerPoint oder Excel auf Links zu Word/PowerPoint/Excel-Dateien klicken, die auf OneDrive, OneDrive für Business oder in SharePoint gespeichert sind.</span><span class="sxs-lookup"><span data-stu-id="161f7-946">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="161f7-947">Um diese Standardeinstellung zu ändern, können Benutzer die folgende Einstellung in Outlook/Word/Excel/PowerPoint aktualisieren:</span><span class="sxs-lookup"><span data-stu-id="161f7-947">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="161f7-948">Datei –> Optionen –> Erweitert –> Verhalten von Links.</span><span class="sxs-lookup"><span data-stu-id="161f7-948">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="161f7-949">Diese Einstellung ist für Outlook/Word/PowerPoint/Excel freigegeben und kann in jeder dieser Apps festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-949">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-950">Szenarien zum Ausprobieren:</span><span class="sxs-lookup"><span data-stu-id="161f7-950">Scenarios to Try:</span></span>

<span data-ttu-id="161f7-951">Lösen Sie die Opt-in-Benutzererfahrung aus – öffnen eines Links zu einer PowerPoint-Präsentation, die in OneDrive/SharePoint aus Outlook/Word/PowerPoint/Excel aus gespeichert ist – klicken Sie aus Office Online auf in Client öffnen – tun Sie dies zwei Mal in einem Zeitraum von 30 Tagen.</span><span class="sxs-lookup"><span data-stu-id="161f7-951">To trigger the opt-in experience - Open a link to a PowerPoint presentation stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="161f7-952">Nachdem Sie die Einstellung gesetzt haben, werden Links standardmäßig in den Win32-Apps gestartet.</span><span class="sxs-lookup"><span data-stu-id="161f7-952">After you opt-in, links will launch in the Win32 apps by default.</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-953">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-953">Excel</span></span>

#### <a name="open-workbook-links-in-excel"></a><span data-ttu-id="161f7-954">Öffnen von Arbeitsmappen-Links in Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-954">Open workbook links in Excel</span></span>

<span data-ttu-id="161f7-955">Wenn Sie in Office auf einen Link zu einer Arbeitsmappe klicken, können Sie Ihre Einstellungen dahingehend aktualisieren, dass diese standardmäßig in der Excel-App geöffnet wird.</span><span class="sxs-lookup"><span data-stu-id="161f7-955">When you click a workbook link in Office, you can update your preference to open in the Excel app by default.</span></span> <span data-ttu-id="161f7-956">Um Ihre Einstellungen zu aktualisieren, wechseln Sie zu Datei > Optionen – > Erweitert-> Verhalten von Links.</span><span class="sxs-lookup"><span data-stu-id="161f7-956">To update your preference, go to File->Options->Advanced->Link Handling.</span></span> <span data-ttu-id="161f7-957">Weitere Informationen: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span><span class="sxs-lookup"><span data-stu-id="161f7-957">Learn More: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US</span></span>

##### <a name="getting-started"></a><span data-ttu-id="161f7-958">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-958">Getting Started:</span></span>

<span data-ttu-id="161f7-959">Das Feature wird standardmäßig auf aus eingestellt.</span><span class="sxs-lookup"><span data-stu-id="161f7-959">Feature will default to off.</span></span> <span data-ttu-id="161f7-960">Benutzer können es entweder über Optionen > Erweitert > Verhalten von Links aktivieren, oder sie können ihm zustimmen, wenn Sie von Win32-WXP-Apps durch eine Opt-In-Umgebung geleitet werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-960">Users can either turn it on via Options->Advanced->Link Handling setting, or they can opt-in when Win32 WXP apps take them through an opt-in experience.</span></span>
<span data-ttu-id="161f7-961">Links werden standardmäßig in der entsprechenden Office-Anwendung anstelle des Browsers geöffnet, wenn Benutzer in Outlook, Word, PowerPoint oder Excel auf Links zu Word/PowerPoint/Excel-Dateien klicken, die auf OneDrive, OneDrive für Business oder in SharePoint gespeichert sind.</span><span class="sxs-lookup"><span data-stu-id="161f7-961">When users click on links to Word/PowerPoint/Excel files stored on OneDrive/OneDrive for Business/SharePoint from Outlook/Word/PowerPoint/Excel, these links will open in the appropriate Office application instead of the browser by default.</span></span>

<span data-ttu-id="161f7-962">Um diese Standardeinstellung zu ändern, können Benutzer die folgende Einstellung in Outlook/Word/Excel/PowerPoint aktualisieren:</span><span class="sxs-lookup"><span data-stu-id="161f7-962">To change this default, users can update the following setting in Outlook/Word/Excel/PowerPoint:</span></span>

<span data-ttu-id="161f7-963">Datei –> Optionen –> Erweitert –> Verhalten von Links.</span><span class="sxs-lookup"><span data-stu-id="161f7-963">File->Options->Advanced->Link Handling</span></span>

<span data-ttu-id="161f7-964">Diese Einstellung ist für Outlook/Word/PowerPoint/Excel freigegeben und kann in jeder dieser Apps festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-964">This setting is shared across Outlook/Word/PowerPoint/Excel and can be set in any of these apps.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-965">Szenarien zum Ausprobieren:</span><span class="sxs-lookup"><span data-stu-id="161f7-965">Scenarios to Try:</span></span>

<span data-ttu-id="161f7-966">Lösen Sie die Opt-in-Benutzererfahrung aus – öffnen eines Links zu einer Excel-Arbeitsmappe, die in OneDrive/SharePoint aus Outlook/Word/PowerPoint/Excel aus gespeichert ist – klicken Sie aus Office Online auf in Client öffnen – tun Sie dies zwei Mal in einem Zeitraum von 30 Tagen.</span><span class="sxs-lookup"><span data-stu-id="161f7-966">To trigger the opt-in experience - Open a link to an Excel workbook stored in OneDrive/SharePoint from Outlook/Word/PowerPoint/Excel - click on Open in Client from Office Online - do this twice in a 30 day window.</span></span> <span data-ttu-id="161f7-967">Nachdem Sie die Einstellung gesetzt haben, werden Links standardmäßig in den Win32-Apps gestartet.</span><span class="sxs-lookup"><span data-stu-id="161f7-967">After you opt-in, links will launch in the Win32 apps by default.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-968">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-968">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="161f7-969">Alle</span><span class="sxs-lookup"><span data-stu-id="161f7-969">All</span></span>
- <span data-ttu-id="161f7-970">Wir haben ein Problem behoben, durch das Dateien manchmal automatisch gespeichert wurden, auch wenn die automatische Speicherung deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-970">We fixed an issue where files could sometimes be auto-saved even when auto-save was disabled</span></span>

### <a name="word"></a><span data-ttu-id="161f7-971">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-971">Word</span></span> 
- <span data-ttu-id="161f7-972">Wir haben ein Problem behoben, das einige Benutzer daran gehindert hat, auf SharePoint zu speichern.</span><span class="sxs-lookup"><span data-stu-id="161f7-972">We fixed an issue which may have prevented some users from saving to SharePoint</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-973">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-973">Excel</span></span>
- <span data-ttu-id="161f7-974">Ein Problem wurde behoben, bei dem ein falsches Symbol für inaktive Filter angezeigt werden konnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-974">We fixed an issue where an incorrect icon could be displayed for inactive filters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-975">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-975">PowerPoint</span></span>
- <span data-ttu-id="161f7-976">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-976">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-977">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-977">Outlook</span></span>
- <span data-ttu-id="161f7-978">Ein Problem wurde behoben, bei dem einige Benutzer in einer Gruppen-Planungsanzeige fälschlicherweise als offline angezeigt wurden</span><span class="sxs-lookup"><span data-stu-id="161f7-978">We fixed an issue where some users would incorrectly appear as Offline in a Group Schedule view</span></span>
- <span data-ttu-id="161f7-979">Wir haben ein Problem behoben, das verhindert, dass SafeLink eine URL mit einem nachgestellten Leerzeichen analysiert</span><span class="sxs-lookup"><span data-stu-id="161f7-979">We fixed an issue which prevented SafeLink from parsing a URL with a trailing space</span></span>
- <span data-ttu-id="161f7-980">Ein Problem wurde behoben, bei dem Räume außerhalb der arbeitsfreien Zeiten als verfügbar angezeigt wurden</span><span class="sxs-lookup"><span data-stu-id="161f7-980">We fixed an issue where rooms were displayed as available outside of non-working hours</span></span>

### <a name="access"></a><span data-ttu-id="161f7-981">Zugriff</span><span class="sxs-lookup"><span data-stu-id="161f7-981">Access</span></span>
- <span data-ttu-id="161f7-982">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-982">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="161f7-983">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-983">Project</span></span>
- <span data-ttu-id="161f7-984">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-984">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-24-2019"></a><span data-ttu-id="161f7-985">24. Mai 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-985">May 24, 2019</span></span>
<span data-ttu-id="161f7-986">Version 1906 (build 11715.20002)</span><span class="sxs-lookup"><span data-stu-id="161f7-986">Version 1906 (build 11715.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-987">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="161f7-987">What's New:</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="161f7-988">Updates für die Benutzeroberfläche</span><span class="sxs-lookup"><span data-stu-id="161f7-988">User Experience Updates</span></span>

<span data-ttu-id="161f7-989">Updates, die als „Bald verfügbar“ angezeigt wurden, sind jetzt verfügbar. Dazu gehört das vereinfachte Menüband sowie ein überarbeitetes Design für den Ordnerbereich, die Nachrichtenliste und den Lesebereich.</span><span class="sxs-lookup"><span data-stu-id="161f7-989">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-990">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-990">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="161f7-991">Alle</span><span class="sxs-lookup"><span data-stu-id="161f7-991">All</span></span>

- <span data-ttu-id="161f7-992">Ein Problem wurde behoben, bei dem der Chat-Bereich nicht angezeigt wurde</span><span class="sxs-lookup"><span data-stu-id="161f7-992">We fixed an issue where the Chat Pane would not display</span></span>

### <a name="word"></a><span data-ttu-id="161f7-993">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-993">Word</span></span> 
- <span data-ttu-id="161f7-994">Ein Problem wurde behoben, bei dem in manchen Fällen Text fälschlicherweise als Grammatikfehler hervorgehoben werden konnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-994">We fixed an issue where in some cases Word could incorrectly highlight text for grammatical errors</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-995">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-995">Excel</span></span>
- <span data-ttu-id="161f7-996">Ein Problem wurde behoben, bei dem ein falsches Symbol für Diagrammelemente verwendet wurde</span><span class="sxs-lookup"><span data-stu-id="161f7-996">We fixed an issue where an incorrect icon was used in for Chart Elements</span></span>
- <span data-ttu-id="161f7-997">Ein Problem wurde behoben, bei dem die falsche Arbeitsmappe in einem VBA-Skript aktiviert werden konnte, wenn die gleiche Mappe bereits geöffnet war.</span><span class="sxs-lookup"><span data-stu-id="161f7-997">We fixed an issue where the incorrect workbook could be activated in a VBA script when the same book was already open</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-998">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-998">PowerPoint</span></span>
- <span data-ttu-id="161f7-999">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-999">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1000">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1000">Outlook</span></span>
- <span data-ttu-id="161f7-1001">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1001">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="161f7-1002">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-1002">Access</span></span>
- <span data-ttu-id="161f7-1003">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1003">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="161f7-1004">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-1004">Project</span></span>
- <span data-ttu-id="161f7-1005">Ein Problem wurde behoben, bei dem das Projekt nach dem Wechsel zur Taskleiste abstürzen konnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1005">We fixed an issue where Project could crash after switching to the taskbar</span></span>

</BR></BR>

## <a name="may-17-2019"></a><span data-ttu-id="161f7-1006">17. Mai 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-1006">May 17, 2019</span></span>
<span data-ttu-id="161f7-1007">Version 1906 (Build 11708.20006)</span><span class="sxs-lookup"><span data-stu-id="161f7-1007">Version 1906 (build 11708.20006)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-1008">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="161f7-1008">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1009">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1009">Outlook</span></span>

#### <a name="user-experience-updates"></a><span data-ttu-id="161f7-1010">Updates für die Benutzeroberfläche</span><span class="sxs-lookup"><span data-stu-id="161f7-1010">User Experience Updates</span></span>

<span data-ttu-id="161f7-1011">Updates, die als „Bald verfügbar“ angezeigt wurden, sind jetzt verfügbar. Dazu gehört das vereinfachte Menüband sowie ein überarbeitetes Design für den Ordnerbereich, die Nachrichtenliste und den Lesebereich.</span><span class="sxs-lookup"><span data-stu-id="161f7-1011">Updates that have been in Coming Soon are now here, featuring the Simplified Ribbon, and a visual refresh of the folder pane, message list, and reading pane.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="161f7-1012">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1012">Getting Started:</span></span>

<span data-ttu-id="161f7-1013">Diese Änderungen sind Bestandteil der neuen Standardbenutzeroberfläche. Sie waren bereits seit Mitte Dezember zu 100% verfügbar, jedoch nur bei Aktivierung des Schalters „in Kürze verfügbar“.</span><span class="sxs-lookup"><span data-stu-id="161f7-1013">These change will be part of the new default UI; it has been available behind the Coming Soon switch since mid Dec for 100% prod</span></span>

#### <a name="customizable-simplified-ribbon"></a><span data-ttu-id="161f7-1014">Anpassbares vereinfachtes Menüband</span><span class="sxs-lookup"><span data-stu-id="161f7-1014">Customizable Simplified Ribbon</span></span>

<span data-ttu-id="161f7-1015">Sie können einfach zwischen klassischer und vereinfachter Ansicht sowie den Befehlen "Anheften" und "Lösen" wechseln.</span><span class="sxs-lookup"><span data-stu-id="161f7-1015">Easily customizable to switch between classic and Simplified views and pin/unpin commands.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="161f7-1016">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1016">Getting Started:</span></span>

<span data-ttu-id="161f7-1017">Benutzer können zum vereinfachten Menüband wechseln, indem Sie zuerst „in Kürze verfügbar“ einschalten und dann auf das Chevron im Menüband klicken, um zwischen dem klassischen, mehrzeiligen Menüband und dem neuen, vereinfachten, einreihigen Menüband zu wechseln.</span><span class="sxs-lookup"><span data-stu-id="161f7-1017">Users can get to the simplified ribbon by turning on Coming Soon (initially) and clicking the chevron in the ribbon to toggle between the classic multi-line ribbon and the new simplified single-line ribbon.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-1018">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="161f7-1018">Scenarios to Try:</span></span>

<span data-ttu-id="161f7-1019">Wechseln zwischen dem klassischen Menüband und dem vereinfachten Menüband</span><span class="sxs-lookup"><span data-stu-id="161f7-1019">Switch from Classic ribbon to Simplified ribbon</span></span>

#### <a name="pick-your-favorite-action"></a><span data-ttu-id="161f7-1020">Wählen Sie Ihre bevorzugte Aktion aus</span><span class="sxs-lookup"><span data-stu-id="161f7-1020">Pick your favorite action</span></span>

<span data-ttu-id="161f7-1021">Sie möchten „Kennzeichnen“ und „Löschen“ nicht verwenden?</span><span class="sxs-lookup"><span data-stu-id="161f7-1021">Don't use Flag and Delete?</span></span> <span data-ttu-id="161f7-1022">Wie sieht es mit „Archivieren“ oder „Als gelesen markieren2 aus?</span><span class="sxs-lookup"><span data-stu-id="161f7-1022">How about Archive or Mark as Read?</span></span> <span data-ttu-id="161f7-1023">Passen Sie das Menü mit schnellen Aktionen mit den am häufigsten verwendeten Befehlen an.</span><span class="sxs-lookup"><span data-stu-id="161f7-1023">Customize the quick action menu with the commands you use most.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="161f7-1024">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1024">Getting Started:</span></span>

<span data-ttu-id="161f7-1025">Wenn Sie Ihre schnellen Aktionen auswählen möchten, klicken Sie mit der rechten Maustaste auf eine e-Mail in der Nachrichtenliste, um das Kontextmenü aufzurufen.</span><span class="sxs-lookup"><span data-stu-id="161f7-1025">To select your Quick Actions, right click on an email in the message list to bring up the Context Menu.</span></span> <span data-ttu-id="161f7-1026">Klicken sie dann auf „Schnelle Aktionen festlegen...“.</span><span class="sxs-lookup"><span data-stu-id="161f7-1026">Then click "Set Quick Actions..."</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-1027">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="161f7-1027">Scenarios to Try:</span></span>

<span data-ttu-id="161f7-1028">Ändern der Standardeinstellungen von „Kennzeichnen“ und „Löschen“ in „Archivieren“, „Bewegen“, „als gelesen markieren" oder "keine" für eine übersichtlichere Nachrichtenliste</span><span class="sxs-lookup"><span data-stu-id="161f7-1028">Change the defaults from flag and delete to either archive, move,  mark as read, or none for a cleaner message list</span></span>

#### <a name="relaxed-or-tighter-layout-you-choose"></a><span data-ttu-id="161f7-1029">Aufgelockertes oder engeres Layout?</span><span class="sxs-lookup"><span data-stu-id="161f7-1029">Relaxed or tighter layout?</span></span> <span data-ttu-id="161f7-1030">Sie haben die Wahl!</span><span class="sxs-lookup"><span data-stu-id="161f7-1030">You choose</span></span>

<span data-ttu-id="161f7-1031">Sie können entscheiden, ob Sie zwischen Elementen mehr Abstand wünschen oder ob Sie mehr Elemente in einem engeren Layout bevorzugen.</span><span class="sxs-lookup"><span data-stu-id="161f7-1031">Use Tighter Spacing lets you decide if you want more space between items, or a tighter layout to see more.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="161f7-1032">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1032">Getting Started:</span></span>

<span data-ttu-id="161f7-1033">In der Registerkarte „Ansicht“ das Kontrollkästchen „engere Abstände" aktivieren. Zu finden in „Nachrichten“ im klassischen Menüband; in „Aktuelle Ansichtseinstellungen“ im vereinfachten Menüband.</span><span class="sxs-lookup"><span data-stu-id="161f7-1033">View tab, use tighter spacing checkbox - in Messages group for classic ribbon, Current View settings for simplified ribbon</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-1034">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="161f7-1034">Scenarios to Try:</span></span>

<span data-ttu-id="161f7-1035">Verwenden Sie Outlook, um e-Mail-Nachrichten zu selektieren und zu schreiben, ohne die Einstellung zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="161f7-1035">Use Outlook to triage and write email with and without the setting enabled.</span></span> <span data-ttu-id="161f7-1036">Bei Verwendung von „engere Abstände“ werden mehr Nachrichten pro Seite angezeigt, und die Steuerelemente in den Ansichten „Verfassen“ sind übersichtlicher.</span><span class="sxs-lookup"><span data-stu-id="161f7-1036">With Use tighter spacing on, more messages fit per page, and controls on the compose forms are more streamlined.</span></span>

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a><span data-ttu-id="161f7-1037">Deduplizieren von MRU-Einträgen bei Verwendung des Onedrive-Synchronisierungs Clients</span><span class="sxs-lookup"><span data-stu-id="161f7-1037">Dedupe MRU entries when using the Onedrive sync client</span></span>

<span data-ttu-id="161f7-1038">Bessere Integration des OneDrive-Synchronisierungsclients mit Cloud-Anlagen durch Deduplizierung der MRU-Einträge und Aktivieren des schnelleren Anfügens als Kopierverhalten für synchronisierte Daten</span><span class="sxs-lookup"><span data-stu-id="161f7-1038">Enable better integration with onedrive sync client with cloud attachments by deduping the mru entries and to enable faster attach as copy behavior for synchronized data</span></span>

##### <a name="getting-started"></a><span data-ttu-id="161f7-1039">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1039">Getting Started:</span></span>

<span data-ttu-id="161f7-1040">Wenn Sie den OneDrive-Synchronisierungsclient verwenden, werden in den „Datei anfügen“-MRU-Einträgen keine Dateiduplikate mehr angezeigt.</span><span class="sxs-lookup"><span data-stu-id="161f7-1040">If you use the OneDrive sync client, you will no longer see file duplicates in the Attach File MRU.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-1041">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="161f7-1041">Scenarios to Try:</span></span>

<span data-ttu-id="161f7-1042">Aktivieren des OneDrive-Synchronisierungsclients und Verwenden des Menüs „Datei anfügen“ in der Outlook-Desktopanwendung</span><span class="sxs-lookup"><span data-stu-id="161f7-1042">Enable the OneDrive sync client and use the Attach File menu in Outlook Desktop</span></span>

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a><span data-ttu-id="161f7-1043">Verbesserte Synchronisierung von freigegebenen Ordnern für Postfächer mit vielen Ordnern</span><span class="sxs-lookup"><span data-stu-id="161f7-1043">Improved shared folder synchronization for mailboxes with many folders</span></span>

<span data-ttu-id="161f7-1044">Seit Jahren ist Outlook beim Synchronisieren von freigegebenen Postfächern auf maximal 500 Ordner beschränkt.</span><span class="sxs-lookup"><span data-stu-id="161f7-1044">For years Outlook has been limited to a maximum of 500 folders when synchronizing shared mailboxes.</span></span> <span data-ttu-id="161f7-1045">Mit dieser Änderung wurde Outlook so verbessert, dass es auf eine Weise synchronisiert wird, die dieser Beschränkung auf 500 Ordner nicht mehr unterliegt.</span><span class="sxs-lookup"><span data-stu-id="161f7-1045">With this change Outlook has been improved to sync in a way that will no longer encounter this 500 folder limit.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="161f7-1046">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1046">Getting Started:</span></span>

<span data-ttu-id="161f7-1047">Erstellen Sie in einem Postfach 1000 Ordner, geben Sie einer anderen Person Zugriff auf das Postfach, erstellen Sie ein Outlook-Profil für diese andere Person, und vergewissern Sie sich, dass die Synchronisierung funktioniert.</span><span class="sxs-lookup"><span data-stu-id="161f7-1047">Create 1000 folders in a mailbox, give someone else access to the mailbox, create an Outlook profile for the "someone else" and verify that sync works.</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1048">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1048">Word</span></span>

#### <a name="erase-just-a-little-bit"></a><span data-ttu-id="161f7-1049">Nur ein wenig löschen</span><span class="sxs-lookup"><span data-stu-id="161f7-1049">Erase just a little bit</span></span>

##### <a name="getting-started"></a><span data-ttu-id="161f7-1050">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1050">Getting Started:</span></span>

<span data-ttu-id="161f7-1051">Wechseln Sie zur Registerkarte „Zeichnen“, und wählen Sie die Dropdownliste „Radierer“ aus.</span><span class="sxs-lookup"><span data-stu-id="161f7-1051">Go to the Draw Tab. Select the Eraser dropdown.</span></span> <span data-ttu-id="161f7-1052">Wählen Sie den kleinen Radierer oder den mittleren Radierer aus.</span><span class="sxs-lookup"><span data-stu-id="161f7-1052">Choose Small Eraser or Medium Eraser.</span></span>

##### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-1053">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="161f7-1053">Scenarios to Try:</span></span>

<span data-ttu-id="161f7-1054">Wechseln Sie zur Registerkarte „Zeichnen“, und wählen Sie einen Stift aus.</span><span class="sxs-lookup"><span data-stu-id="161f7-1054">Go to the Draw Tab. Select a pen.</span></span> <span data-ttu-id="161f7-1055">Zeichnen Sie einen Strich.</span><span class="sxs-lookup"><span data-stu-id="161f7-1055">Draw an ink stroke.</span></span> <span data-ttu-id="161f7-1056">Wählen Sie die Dropdownliste „Radierer“ aus.</span><span class="sxs-lookup"><span data-stu-id="161f7-1056">Select the Eraser dropdown.</span></span> <span data-ttu-id="161f7-1057">Wählen Sie den kleinen Radierer oder den mittleren Radierer aus.</span><span class="sxs-lookup"><span data-stu-id="161f7-1057">Choose Small Eraser or Medium Eraser.</span></span> <span data-ttu-id="161f7-1058">Radieren Sie nur Teile des Striches aus.</span><span class="sxs-lookup"><span data-stu-id="161f7-1058">Erase just bits of the ink stroke.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-1059">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-1059">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="161f7-1060">Alle</span><span class="sxs-lookup"><span data-stu-id="161f7-1060">All</span></span> 
- <span data-ttu-id="161f7-1061">Wir haben ein Problem behoben, welches einige Nutzer daran hindern konnte eine PDF-Datei zu speichern.</span><span class="sxs-lookup"><span data-stu-id="161f7-1061">We fixed an issue which could prevent some users from saving as PDF</span></span>
- <span data-ttu-id="161f7-1062">Wir haben ein Problem behoben, welches sich auf Nutzer ausgewirkt hat, die große Dateien auf einem 32-Bit System speicherten.</span><span class="sxs-lookup"><span data-stu-id="161f7-1062">We fixed an issue which could impact users saving large files on a 32-bit system</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1063">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1063">Word</span></span> 
- <span data-ttu-id="161f7-1064">Die Reaktionsfähigkeit des Diktat-Features wurde erheblich verbessert.</span><span class="sxs-lookup"><span data-stu-id="161f7-1064">We significantly improved the responsiveness of the dictation feature</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-1065">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1065">Excel</span></span>
- <span data-ttu-id="161f7-1066">Wir haben ein Problem behoben, bei dem Doppelklick-Ereignisse auf Touchscreen-Geräten fehlschlagen konnten.</span><span class="sxs-lookup"><span data-stu-id="161f7-1066">We fixed an issue where double-click events could fail on touch screen devices</span></span>
- <span data-ttu-id="161f7-1067">Wir haben ein Problem behoben, welches einige Nutzer daran hindern konnte VBA Makros zu bearbeiten.</span><span class="sxs-lookup"><span data-stu-id="161f7-1067">We fixed an issue which could prevent some users from being able to edit VBA macros</span></span>
- <span data-ttu-id="161f7-1068">Wir haben ein Problem behoben, welches sich auf die Performance bei der Nutzung von Slicers auswirken konnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1068">We fixed an issue which could impact performance when using slicers</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-1069">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-1069">PowerPoint</span></span>
- <span data-ttu-id="161f7-1070">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1070">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1071">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1071">Outlook</span></span>
- <span data-ttu-id="161f7-1072">Es wurde ein Problem behoben, bei dem statt der ausgewählten Vorlage eine falsche angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-1072">We fixed an issue where the wrong template could be displayed from what was selected</span></span>

### <a name="access"></a><span data-ttu-id="161f7-1073">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-1073">Access</span></span>
- <span data-ttu-id="161f7-1074">Wir haben ein Problem behoben, bei dem bei der Verwendung von Zoom Builder zum Anzeigen langer Rich Text schwer lesbar sein konnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1074">We fixed an issue where using the zoom builder to display long rich text, could be hard to read</span></span>

### <a name="project"></a><span data-ttu-id="161f7-1075">Projekt</span><span class="sxs-lookup"><span data-stu-id="161f7-1075">Project</span></span>
- <span data-ttu-id="161f7-1076">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1076">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="may-10-2019"></a><span data-ttu-id="161f7-1077">10. Mai 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-1077">May 10, 2019</span></span>
<span data-ttu-id="161f7-1078">Version 1906 (Build 11702.20000)</span><span class="sxs-lookup"><span data-stu-id="161f7-1078">Version 1906 (build 11702.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-1079">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="161f7-1079">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1080">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1080">Outlook</span></span>

<span data-ttu-id="161f7-1081">**Mehr Nachrichten am Bildschirm anzeigen:** Wählen Sie „Anzeigen“ > Engere Abstände verwenden, um die Abstände zwischen den Nachrichten anzupassen.</span><span class="sxs-lookup"><span data-stu-id="161f7-1081">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-1082">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-1082">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="161f7-1083">Alle</span><span class="sxs-lookup"><span data-stu-id="161f7-1083">All</span></span>
- <span data-ttu-id="161f7-1084">Ein Problem wurde behoben, bei dem im Dialogfeld "Speichern unter" manchmal ein falscher Pfad angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-1084">We fixed an issue where the Save As dialog could display the incorrect path</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1085">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1085">Word</span></span> 
- <span data-ttu-id="161f7-1086">Ein Problem wurde behoben, bei dem einige Auswahloptionen aus der Funktion "Was möchten Sie tun?" nicht eingefügt wurden.</span><span class="sxs-lookup"><span data-stu-id="161f7-1086">We fixed an issue where some selections from Tell Me would not get inserted</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-1087">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1087">Excel</span></span>
- <span data-ttu-id="161f7-1088">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1088">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-1089">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-1089">PowerPoint</span></span>
- <span data-ttu-id="161f7-1090">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1090">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1091">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1091">Outlook</span></span>
- <span data-ttu-id="161f7-1092">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1092">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="161f7-1093">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-1093">Access</span></span>
- <span data-ttu-id="161f7-1094">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1094">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="161f7-1095">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-1095">Project</span></span>
- <span data-ttu-id="161f7-1096">Ein Problem wurde behoben, bei dem Aufgaben-IDs manchmal nur angezeigt wurden, wenn sie markiert wurden.</span><span class="sxs-lookup"><span data-stu-id="161f7-1096">We fixed an issue where Task ID's could require highlighting to see</span></span>

</BR></BR>

## <a name="may-3-2019"></a><span data-ttu-id="161f7-1097">3. Mai 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-1097">May 3, 2019</span></span>
<span data-ttu-id="161f7-1098">Version 1906 (Build 11629.20008)</span><span class="sxs-lookup"><span data-stu-id="161f7-1098">Version 1906 (build 11629.20008)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-1099">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="161f7-1099">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1100">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1100">Outlook</span></span>

<span data-ttu-id="161f7-1101">**Alle Verschlüsselungsoptionen an einem zentralen Ort:** Gehen Sie einfach zu „Optionen“ > „Verschlüsseln“, um auszuwählen, wie Ihre E-Mail-Nachricht gesichert werden soll.</span><span class="sxs-lookup"><span data-stu-id="161f7-1101">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-1102">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-1102">Notable Fixes:</span></span>

### <a name="all"></a><span data-ttu-id="161f7-1103">Alle</span><span class="sxs-lookup"><span data-stu-id="161f7-1103">All</span></span>
- <span data-ttu-id="161f7-1104">Ein Problem wurde behoben, bei dem bei einigen Benutzern Probleme beim Synchronisieren mit OneDrive for Business auftraten.</span><span class="sxs-lookup"><span data-stu-id="161f7-1104">We fixed an issue where some users would experience problems syncing with OneDrive for Business</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1105">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1105">Word</span></span> 
- <span data-ttu-id="161f7-1106">Ein Problem wurde behoben, bei dem Word in einigen Fällen sehr lange zum Starten brauchte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1106">We fixed an issue where in some cases Word would take a long time to start</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-1107">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1107">Excel</span></span>
- <span data-ttu-id="161f7-1108">Ein Problem wurde behoben, bei dem externe Links nach dem Upgrade auf eine neuere Version von Excel manchmal aus Arbeitsmappen entfernt wurden.</span><span class="sxs-lookup"><span data-stu-id="161f7-1108">We fixed an issue where external links were sometimes removed from workbooks after upgrading to a newer version of Excel</span></span>
- <span data-ttu-id="161f7-1109">Ein Problem wurde behoben, bei dem einige Benutzern Schwierigkeiten beim Auswählen von Zellen in einer neuen Arbeitsmappen hatten.</span><span class="sxs-lookup"><span data-stu-id="161f7-1109">We fixed an issue where some users could experience difficulty selecting cells in a new workbook</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-1110">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-1110">PowerPoint</span></span>
- <span data-ttu-id="161f7-1111">Ein Problem wurde behoben, bei dem Schriftgrade beim Konvertieren von Freihandzeichnungen in Text nicht konsistent waren.</span><span class="sxs-lookup"><span data-stu-id="161f7-1111">We fixed an issue where font sizes were not consistant when converting drawings to text</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1112">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1112">Outlook</span></span>
- <span data-ttu-id="161f7-1113">Ein Problem wurde behoben, bei dem das Speichern eines Kontakts aus einer VCF-Datei zu leeren Feldern führen konnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1113">We fixed an issue where saving a contact from a .VCF file could result in empty fields</span></span>
- <span data-ttu-id="161f7-1114">Ein Problem wurde behoben, bei dem eine Nachricht im Ordner "Postausgang" stecken blieb, obwohl sie gesendet wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-1114">We fixed an issue where a message could get stuck in the outbox folder even though it had been sent</span></span>
- <span data-ttu-id="161f7-1115">Ein Problem wurde behoben, bei dem Outlook beim Anzeigen einer DRM-Meldung abstürzte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1115">We fixed an issue where Outlook could crash when viewing a DRM message</span></span>

### <a name="access"></a><span data-ttu-id="161f7-1116">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-1116">Access</span></span>
- <span data-ttu-id="161f7-1117">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1117">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="161f7-1118">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-1118">Project</span></span>
- <span data-ttu-id="161f7-1119">Ein Problem wurde behoben, bei dem der Editor von Chinesisch auf Englisch wechselte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1119">We fixed an issue where the editor would switch from Chinese to English</span></span>
- <span data-ttu-id="161f7-1120">Ein Problem wurde behoben, bei dem unveröffentlichte Aufgaben manchmal in der veröffentlichten Kopie eines Hauptprojekts angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="161f7-1120">We fixed an issue where unpublished tasks could appear in the published copy of a master project</span></span>

</BR></BR>

## <a name="april-26-2019"></a><span data-ttu-id="161f7-1121">26. April 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-1121">April 26, 2019</span></span>
<span data-ttu-id="161f7-1122">Version 1905 (Build 11617.20002)</span><span class="sxs-lookup"><span data-stu-id="161f7-1122">Version 1905 (build 11617.20002)</span></span>

## <a name="new-features"></a><span data-ttu-id="161f7-1123">Neue Features</span><span class="sxs-lookup"><span data-stu-id="161f7-1123">New Features</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1124">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1124">Outlook</span></span>

<span data-ttu-id="161f7-1125">**Aktualisierungen freigebender Kalender funktionieren jetzt noch schneller:** Outlook ist in der Lage, freigegebene Kalender in Office 365 mithilfe der REST API zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="161f7-1125">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="161f7-1126">Aktivieren Sie die Vorschau, um schnellere und zuverlässigere Aktualisierungen für freigegebene Kalender zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="161f7-1126">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-1127">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1127">Excel</span></span>

#### <a name="coauthoring-improvements"></a><span data-ttu-id="161f7-1128">Verbesserungen bei der gemeinsamen Dokumenterstellung</span><span class="sxs-lookup"><span data-stu-id="161f7-1128">Coauthoring improvements</span></span>

<span data-ttu-id="161f7-1129">Die gemeinsame Dokumenterstellung wurde verbessert, indem Inhaltsänderungen den anderen Benutzern nun nahezu immer in Echtzeit angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-1129">Improved the coauthoring experience by making it more likely that content changes will be received by others in real time.</span></span>

### <a name="visio"></a><span data-ttu-id="161f7-1130">Visio</span><span class="sxs-lookup"><span data-stu-id="161f7-1130">Visio</span></span>

- <span data-ttu-id="161f7-1131">**Exportieren von Visio-Visualisierungen aus Power BI:** Die Visio-Visualisierung für Power BI wird nun ordnungsgemäß angezeigt, wenn Sie Power BI-Berichte beispielsweise als PDF-Dateien, PowerPoint-Dateien und mehr exportieren.</span><span class="sxs-lookup"><span data-stu-id="161f7-1131">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-1132">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-1132">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1133">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1133">Word</span></span> 
- <span data-ttu-id="161f7-1134">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1134">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-1135">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1135">Excel</span></span>
- <span data-ttu-id="161f7-1136">Wir haben ein Problem behoben, bei dem Solver-Makros nicht ausgeführt werden konnten</span><span class="sxs-lookup"><span data-stu-id="161f7-1136">We fixed an issue where Solver macros would fail to run</span></span>
- <span data-ttu-id="161f7-1137">Wir haben ein Problem behoben, das den Import von Excel-Dateien in SharePoint verhindern konnte</span><span class="sxs-lookup"><span data-stu-id="161f7-1137">We fixed an issue which could prevent Excel files from being imported into SharePoint</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-1138">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-1138">PowerPoint</span></span>
- <span data-ttu-id="161f7-1139">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1139">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1140">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1140">Outlook</span></span>
- <span data-ttu-id="161f7-1141">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1141">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="161f7-1142">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-1142">Access</span></span>
- <span data-ttu-id="161f7-1143">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1143">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="161f7-1144">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-1144">Project</span></span>
- <span data-ttu-id="161f7-1145">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1145">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-19-2019"></a><span data-ttu-id="161f7-1146">19. April 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-1146">April 19, 2019</span></span>
<span data-ttu-id="161f7-1147">Version 1905 (Build 11609.20002)</span><span class="sxs-lookup"><span data-stu-id="161f7-1147">Version 1905 (build 11609.20002)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-1148">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="161f7-1148">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1149">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1149">Outlook</span></span>

<span data-ttu-id="161f7-1150">**Erhalten Sie E-Mail-Vorschläge, wenn Sie nach einer Person suchen**: Wenn Sie den Namen einer Person im Suchfeld eingeben, werden die relevantesten E-Mail-Nachrichten in die Ihnen gezeigten Suchvorschläge einbezogen.</span><span class="sxs-lookup"><span data-stu-id="161f7-1150">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-1151">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1151">Excel</span></span>

#### <a name="improved-filled-maps-experience-using-data-types"></a><span data-ttu-id="161f7-1152">Verbesserte Benutzererfahrung für ausgefüllte Karten durch die Verwendung von Datentypen</span><span class="sxs-lookup"><span data-stu-id="161f7-1152">Improved Filled Maps experience using Data Types</span></span>

<span data-ttu-id="161f7-1153">Dieses Feature ist eine Verbesserung für Benutzer, die ausgefüllte Kartendiagramme mithilfe der geografischen Datentypen von Excel darstellen.</span><span class="sxs-lookup"><span data-stu-id="161f7-1153">This feature is an improvement for users who plot Filled Map Charts using Excel's Geographic Data Types.</span></span> <span data-ttu-id="161f7-1154">Der Vorteil für den Endbenutzer besteht in einer umfangreicheren Integration zwischen den Features und einer höheren Genauigkeit des Bereichs, den der Endbenutzer zuordnen möchte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1154">The benefit to the end users will be richer integration between the features and better accuracy of the region the end user wants to map.</span></span> <span data-ttu-id="161f7-1155">Weitere Vorteile: Zuordnen von Stadt-Polygonen</span><span class="sxs-lookup"><span data-stu-id="161f7-1155">Additional benefits include - ability to map city polygons.</span></span>

##### <a name="getting-started"></a><span data-ttu-id="161f7-1156">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1156">Getting Started:</span></span>

- <span data-ttu-id="161f7-1157">Dieses Feature ist eine Verbesserung der vorhandenen Funktionen in Excel.</span><span class="sxs-lookup"><span data-stu-id="161f7-1157">This feature is an improvement to the existing features within Excel.</span></span> <span data-ttu-id="161f7-1158">Verwenden der Verbesserung: Konvertieren Sie Orte in Rich-Entitäten und stellen Sie sie durch ausgefüllte Karten dar.</span><span class="sxs-lookup"><span data-stu-id="161f7-1158">To use the improvement - convert locations into Rich Entities and plot with Filled Maps.</span></span> 

##### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-1159">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="161f7-1159">Scenarios to Try:</span></span>

- <span data-ttu-id="161f7-1160">Benutzer können Städte, Staaten, Landkreise, Länder und Postleitzahlen zuordnen.</span><span class="sxs-lookup"><span data-stu-id="161f7-1160">Users can try mapping cities, states, counties, countries and zip codes.</span></span> 


## <a name="notable-fixes"></a><span data-ttu-id="161f7-1161">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-1161">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="161f7-1162">Alle Anwendungen</span><span class="sxs-lookup"><span data-stu-id="161f7-1162">All Applications</span></span>
- <span data-ttu-id="161f7-1163">Es wurde ein Fehler behoben, bei dem der Dialog der ersten Ausführung beim Start einer Anwendung immer angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-1163">We fixed an issue where the First Run dialog would display whenever an application was launched</span></span>
- <span data-ttu-id="161f7-1164">Es wurde ein Problem behoben, bei dem ein SharePoint-Link im Dialogfeld "Speichern unter" in manchen Fällen nicht vorhanden war.</span><span class="sxs-lookup"><span data-stu-id="161f7-1164">We fixed an issue where a SharePoint link in the "save as" dialog could be missing.</span></span>
- <span data-ttu-id="161f7-1165">Es wurde ein Fehler behoben, bei dem Benutzern fälschlicherweise der Dialog "Jetzt reparieren" angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-1165">We fixed an issue where users would incorrectly see a "Repair Now" dialog</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1166">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1166">Word</span></span> 
- <span data-ttu-id="161f7-1167">Es wurde ein Fehler behoben, bei dem einige Benutzer beim Anfordern einer Schriftart die Fehlermeldung erhielten, dass nicht genügend Arbeitsspeicher oder Speicherplatz vorhanden sei.</span><span class="sxs-lookup"><span data-stu-id="161f7-1167">We fixed an issue where some users could receive an error for insufficient memory or disk space when requesting a font</span></span>
- <span data-ttu-id="161f7-1168">Es wurde ein Fehler behoben, bei dem ein Fenster beim Umschalten vom Bereich "Kommentare" unscharf wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-1168">We fixed an issue where a window could lose focus when switching from the comments pane</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-1169">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1169">Excel</span></span>
- <span data-ttu-id="161f7-1170">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1170">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-1171">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-1171">PowerPoint</span></span>
- <span data-ttu-id="161f7-1172">Es wurde ein Fehler behoben, der bewirkte, dass die Größe von Formen mit Branding nicht angepasst werden konnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1172">We fixed an issue preventing the resizing of branded shapes</span></span>
- <span data-ttu-id="161f7-1173">Es wurde ein Fehler behoben, bei dem PowerPoint abstürzen konnte, wenn eine Datei im geschützten Ansichtsmodus geöffnet wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-1173">We fixed an issue where PowerPoint could crash when opening a file in protected view mode</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1174">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1174">Outlook</span></span>
- <span data-ttu-id="161f7-1175">Wir haben ein Problem behoben, aufgrund dessen einige Benutzer keine chinesischen Wörter auswählen konnten.</span><span class="sxs-lookup"><span data-stu-id="161f7-1175">We fixed an issue which prevented some users from selecting Chinese words</span></span>
- <span data-ttu-id="161f7-1176">Wir haben ein Problem behoben, bei dem Ablaufdaten nicht korrekt berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="161f7-1176">We fixed an issue where expiry dates were not calculated correctly</span></span>

### <a name="access"></a><span data-ttu-id="161f7-1177">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-1177">Access</span></span>
- <span data-ttu-id="161f7-1178">Wir haben ein Problem behoben, aufgrund dessen einige Benutzer nicht den Makro-Generator benutzen konnten.</span><span class="sxs-lookup"><span data-stu-id="161f7-1178">We fixed an issue which prevented some users from using the Macro Builder</span></span>
- <span data-ttu-id="161f7-1179">Wir haben ein Problem behoben, aufgrund dessen beim Drucken eines Berichts nur die erste Seite ausgedruckt wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-1179">We fixed an issue where printing a report would only print the first page</span></span>
- <span data-ttu-id="161f7-1180">Es wurde ein Problem behoben, bei dem die Anwendung beim Fahren über einen Hyperlink abstürzen konnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1180">We fixed an issue where the application could crash when hovering over a hyperlink</span></span>
- <span data-ttu-id="161f7-1181">Wir haben ein Problem behoben, das bewirkte, dass in der Ansicht "Beziehungen" einige Elemente außerhalb des Fensters angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="161f7-1181">We fixed an issue which caused some items to appear off screen when using relationships view</span></span>

### <a name="project"></a><span data-ttu-id="161f7-1182">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-1182">Project</span></span>
- <span data-ttu-id="161f7-1183">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1183">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-12-2019"></a><span data-ttu-id="161f7-1184">12. April 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-1184">April 12, 2019</span></span>
<span data-ttu-id="161f7-1185">Version 1905 (Build 11601.20042)</span><span class="sxs-lookup"><span data-stu-id="161f7-1185">Version 1905 (build 11601.20042)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-1186">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="161f7-1186">What's New:</span></span>

### <a name="access"></a><span data-ttu-id="161f7-1187">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-1187">Access</span></span>

#### <a name="get-smart-with-microsoft-graph"></a><span data-ttu-id="161f7-1188">Intelligenter mit Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="161f7-1188">Get smart with Microsoft Graph</span></span>

<span data-ttu-id="161f7-1189">Importieren oder verlinken Sie intelligente Daten, und erfinden Sie Ihre Desktopdatenbank mit intelligenter Technologie neu.</span><span class="sxs-lookup"><span data-stu-id="161f7-1189">Import or link to intelligent data and reinvent your desktop database with Intelligent Technology.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-1190">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-1190">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="161f7-1191">Alle Anwendungen</span><span class="sxs-lookup"><span data-stu-id="161f7-1191">All Applications</span></span>
 - <span data-ttu-id="161f7-1192">Wir haben ein Problem behoben, aufgrund dessen einige Benutzer Dateien nicht an Cloudspeicherorten speichern konnten.</span><span class="sxs-lookup"><span data-stu-id="161f7-1192">We fixed an issue which prevented some users from saving files to cloud locations</span></span>
 - <span data-ttu-id="161f7-1193">Wir haben ein Problem behoben, bei dem der falsche Bereich auf dem Menüband geöffnet wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-1193">We fixed an issue where the wrong pane could open from the ribbon</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1194">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1194">Word</span></span> 
- <span data-ttu-id="161f7-1195">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1195">Various performance and stability fixes</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-1196">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1196">Excel</span></span>
- <span data-ttu-id="161f7-1197">Wir haben ein Problem behoben, bei dem eine Fehlermeldung aufgrund verknüpfter Datentypen für Benutzer angezeigt wird, wenn die Arbeitsmappe keine verknüpften Datentypen enthält.</span><span class="sxs-lookup"><span data-stu-id="161f7-1197">We fixed an issue where users would see an error message for linked data types when the workbook did not contain linked data types</span></span>
- <span data-ttu-id="161f7-1198">Wir haben ein Problem behoben, bei dem sich URL-Links innerhalb eines Word-Dokuments ändern, wenn diese lokal und nicht online angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-1198">We fixed an issue where URL links within a Word document could change when viewed locally vs. online</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-1199">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-1199">PowerPoint</span></span>
- <span data-ttu-id="161f7-1200">Wir haben ein Problem behoben, bei dem die Anwendung nach dem Rückgängigmachen von Änderungen auf der Registerkarte „Animationen“ abstürzte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1200">We fixed an issue where the application could crash after undoing changes from the animations tab</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1201">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1201">Outlook</span></span>
- <span data-ttu-id="161f7-1202">Wir haben ein Problem behoben, aufgrund dessen einige Benutzer das Feld „Notizen“ für Kontakt in einem öffentlichen Ordner nicht bearbeiten konnten.</span><span class="sxs-lookup"><span data-stu-id="161f7-1202">We fixed an issue which prevented some users from modifying the Notes field for contacts in a Public Folder</span></span>
- <span data-ttu-id="161f7-1203">Wir haben ein Problem behoben, bei dem ein Konflikt zwischen den Ablaufdatumsangaben und den Löschdatumsangaben auftrat.</span><span class="sxs-lookup"><span data-stu-id="161f7-1203">We fixed an issue where a conflict could occur between expiration dates and deletion dates</span></span>

### <a name="access"></a><span data-ttu-id="161f7-1204">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-1204">Access</span></span>
- <span data-ttu-id="161f7-1205">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1205">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="161f7-1206">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-1206">Project</span></span>
- <span data-ttu-id="161f7-1207">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1207">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="april-5-2019"></a><span data-ttu-id="161f7-1208">5. April 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-1208">April 5, 2019</span></span>
<span data-ttu-id="161f7-1209">Version 1904 (Build 11527.20014)</span><span class="sxs-lookup"><span data-stu-id="161f7-1209">Version 1904 (build 11527.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-1210">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="161f7-1210">What's New:</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1211">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1211">Outlook</span></span>

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a><span data-ttu-id="161f7-1212">Outlook für Windows: Festlegen und Teilen Ihrer Einstellungen für „Posteingang mit Relevanz"</span><span class="sxs-lookup"><span data-stu-id="161f7-1212">Outlook for Windows:  set and share your Focused Inbox settings</span></span>

<span data-ttu-id="161f7-1213">Ihre Einstellungen für "Posteingang mit Relevanz" werden in der Cloud gespeichert, sodass Sie auf jedem verwendeten Computer die gleiche konsistente Umgebung für Outlook für Windows und Outlook im Web erhalten.</span><span class="sxs-lookup"><span data-stu-id="161f7-1213">Your Focused Inbox preferences are stored in the cloud so you can enjoy the same consistent experience when using Outlook for Windows and Outlook on the web on any computer.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="161f7-1214">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1214">Getting Started:</span></span>

<span data-ttu-id="161f7-1215">Unter „Datei" > „Optionen" > Registerkarte „Allgemein" gibt es eine neue Einstellung für „Meine Outlook-Einstellungen in der Cloud speichern".</span><span class="sxs-lookup"><span data-stu-id="161f7-1215">Under File > Options > General tab, there is a new preference for 'Store my Outlook settings in the cloud'.</span></span> <span data-ttu-id="161f7-1216">Benutzer müssen das Kontrollkästchen aktivieren, damit ihre Einstellungen für "Posteingang mit Relevanz" für andere Desktopinstallationen von Outlook und OWA übernommen werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-1216">Users will need to check the box to enable their Focused Inbox setting to roam to other Desktop Outlook installations and OWA.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-1217">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="161f7-1217">Scenarios to Try:</span></span>

<span data-ttu-id="161f7-1218">Ändern Sie auf dem Computer, auf dem die Einstellung für die Cloudeinstellungen aktiviert ist, den Posteingang mit Priorität.</span><span class="sxs-lookup"><span data-stu-id="161f7-1218">Change Focused Inbox on the machine that has cloud settings preference turned on.</span></span> <span data-ttu-id="161f7-1219">Navigieren Sie zu OWA, und sehen Sie sich die dort angewendete Einstellung an.</span><span class="sxs-lookup"><span data-stu-id="161f7-1219">Navigate to OWA and see the preference applied there as well.</span></span> <span data-ttu-id="161f7-1220">Ändern Sie den „Posteingangs mit Relevanz“ in OWA und starten Sie Outlook für Desktop, um die Einstellungen anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="161f7-1220">Change Focused Inbox in OWA and start Desktop Outlook to see the preference reflected.</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1221">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1221">Word</span></span>

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a><span data-ttu-id="161f7-1222">Der Modus „Lerntools" unterstützt weitere Seitenfarben.</span><span class="sxs-lookup"><span data-stu-id="161f7-1222">Learning Tools mode has additional support for more page colors</span></span>

<span data-ttu-id="161f7-1223">Lerntools in Word unterstützt weitere Farben für Seitendesigns, wodurch die Hintergrundfarbe der Seite geändert werden kann.</span><span class="sxs-lookup"><span data-stu-id="161f7-1223">Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span>  <span data-ttu-id="161f7-1224">Viele Personen haben Herausforderungen beim Lesen mit einem ganz weißen oder schwarzem Hintergrund, deshalb haben wir die Auswahl von Farben in Word auf PC und Mac erweitert.</span><span class="sxs-lookup"><span data-stu-id="161f7-1224">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="161f7-1225">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1225">Getting Started:</span></span>

<span data-ttu-id="161f7-1226">Um dies auszuprobieren, wechseln Sie zur Registerkarte „Anzeige", und wählen Sie „Lerntools", dann „Seitenfarbe" aus.</span><span class="sxs-lookup"><span data-stu-id="161f7-1226">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-1227">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="161f7-1227">Scenarios to Try:</span></span>

<span data-ttu-id="161f7-1228">Um dies auszuprobieren, wechseln Sie zur Registerkarte „Anzeige", und wählen Sie „Lerntools", dann „Seitenfarbe" aus.</span><span class="sxs-lookup"><span data-stu-id="161f7-1228">To try this out, go to the View tab and choose Learning Tools, and then Page Color.</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-1229">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1229">Excel</span></span>

#### <a name="elevate-creativity-with-animated-3d-models"></a><span data-ttu-id="161f7-1230">Kreativität durch animierte 3D-Modelle steigern</span><span class="sxs-lookup"><span data-stu-id="161f7-1230">Elevate Creativity with Animated 3D Models</span></span>

<span data-ttu-id="161f7-1231">Office unterstützt jetzt animierte Modelle, die im Editor wiedergegeben werden, damit Sie Ihre Arbeitsblätter zum Leben erwecken können!</span><span class="sxs-lookup"><span data-stu-id="161f7-1231">Office now supports animated models, which will playback in the editor so you can bring your sheets to life!</span></span>

#### <a name="getting-started"></a><span data-ttu-id="161f7-1232">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1232">Getting Started:</span></span>

1. <span data-ttu-id="161f7-1233">Öffnen Sie Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1233">Open Excel</span></span>
2. <span data-ttu-id="161f7-1234">Fügen Sie ein animiertes 3D-Modell ein (demnächst in Remix verfügbar, bereits jetzt können Sie hier auf animierte Modelle zugreifen: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span><span class="sxs-lookup"><span data-stu-id="161f7-1234">Insert an animated 3D Model (coming to Remix soon, but for now, access animated models here: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)</span></span>
3. <span data-ttu-id="161f7-1235">Das animierte Modell wird im Editor wiedergegeben!</span><span class="sxs-lookup"><span data-stu-id="161f7-1235">The animated model will play in the editor!</span></span> <span data-ttu-id="161f7-1236">Wechseln Sie in den Bildschirmpräsentationsmodus – es wird auch dort wiedergegeben werden!</span><span class="sxs-lookup"><span data-stu-id="161f7-1236">Check Slideshow mode - it will play there too!</span></span>
4. <span data-ttu-id="161f7-1237">Im Menüband 3D-Format finden Sie noch weitere animierte Szenen.</span><span class="sxs-lookup"><span data-stu-id="161f7-1237">In the 3D Format Ribbon, explore more animation scenes in the model</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-1238">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="161f7-1238">Scenarios to Try:</span></span>

1. <span data-ttu-id="161f7-1239">Fügen Sie ein 3D-Modell ein und betrachten Sie dessen Animation im Editor.</span><span class="sxs-lookup"><span data-stu-id="161f7-1239">Insert an animated model and watch it play in the editor</span></span>
2. <span data-ttu-id="161f7-1240">Entdecken Sie die im animierten Modell verfügbaren Animationsszenen in der Szenengalerie, zu finden im Menüband 3D-Format</span><span class="sxs-lookup"><span data-stu-id="161f7-1240">Explore the animation scenes available in the animated model via the Scenes Gallery, available in the 3D Format Ribbon</span></span>
3. <span data-ttu-id="161f7-1241">Die Animation kann ganz einfach über das Menüband, den Floatie oder die Leertaste wiedergegeben oder pausiert werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-1241">Easily play/pause the animation via the ribbon, floatie or space bar</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-1242">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-1242">Notable Fixes:</span></span>

### <a name="all-applications"></a><span data-ttu-id="161f7-1243">Alle Anwendungen</span><span class="sxs-lookup"><span data-stu-id="161f7-1243">All Applications</span></span>
- <span data-ttu-id="161f7-1244">Wir haben ein Problem behoben, bei dem das Symbol für eine falsche App für Excel in Kontextmenüs nicht ordnungsgemäß angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-1244">We fixed an issue where the incorrect app icon could appear for Excel in contextual menus</span></span>
- <span data-ttu-id="161f7-1245">Wir haben ein Problem behoben, bei dem die Menüschaltfläche „Datei“ nach der Installation eines Updates nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-1245">We fixed an issue where the File Menu button could disappear after installing an update</span></span>
- <span data-ttu-id="161f7-1246">Wir haben ein Problem behoben, bei dem Ihre Benutzerlizenz geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-1246">We fixed an issue which could change your user license</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1247">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1247">Word</span></span> 
- <span data-ttu-id="161f7-1248">Wir haben ein Problem behoben, bei dem Text auf bestimmten Zoomebenen nicht richtig gerendert wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-1248">We fixed an issue where text would not render correctly at certain zoom levels</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-1249">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1249">Excel</span></span>
- <span data-ttu-id="161f7-1250">Wir haben ein Problem behoben, bei dem Benutzer nicht aufgefordert wurden, eine Arbeitsmappe nach Änderungen zu speichern.</span><span class="sxs-lookup"><span data-stu-id="161f7-1250">We fixed an issue where users would not be prompted to save a workbook after making edits</span></span>
- <span data-ttu-id="161f7-1251">Wir haben ein Problem behoben, bei dem ein BeforeSave-Ereignis nicht ausgelöst wurde, wenn der Benutzer die Arbeitsmappe teilte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1251">We fixed an issue where a BeforeSave event would not be triggered if the user shared the workbook.</span></span>
- <span data-ttu-id="161f7-1252">Wir haben ein Problem behoben, bei dem das Ändern der Größe einer Spalte auf weniger als 6 Pixel eine falsche Fehlermeldung ausgab.</span><span class="sxs-lookup"><span data-stu-id="161f7-1252">We fixed an issue where resizing a column to fewer than 6 pixels could throw an incorrect error message.</span></span>
- <span data-ttu-id="161f7-1253">Wir haben ein Problem behoben, bei dem Excel das Application.Visible-Kennzeichen ignorierte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1253">We fixed an issue where Excel would ignore the Application.Visible flag</span></span>
- <span data-ttu-id="161f7-1254">Wir haben ein Problem behoben, bei dem Ablaufverfolgungspfeile auf nicht aktiven fixierten Fenstern bestehen blieben.</span><span class="sxs-lookup"><span data-stu-id="161f7-1254">We fixed an issue where trace arrows would remain on non-active frozen panes</span></span>
- <span data-ttu-id="161f7-1255">Wir haben ein Problem behoben, bei dem sich die Zellenformatierung von Datumsangaben und Währung beim Öffnen einer Arbeitsmappe änderte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1255">We fixed an issue where cell formatting of dates an currency could change when opening a workbook</span></span>
- <span data-ttu-id="161f7-1256">Wir haben ein Problem behoben, bei dem Tooltips sich unerwartet verschoben.</span><span class="sxs-lookup"><span data-stu-id="161f7-1256">We fixed an issue where tooltips would move unexpectedly</span></span>
- <span data-ttu-id="161f7-1257">Wir haben Lokalisierungsprobleme für den Power Query-Editor behoben.</span><span class="sxs-lookup"><span data-stu-id="161f7-1257">We fixed localization issues for the Power Query editor</span></span>
- <span data-ttu-id="161f7-1258">Wir haben ein Problem behoben, bei dem eine Arbeitsmappe als Anlage beim Senden per E-Mail entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-1258">We fixed an issue where a workbook would be removed as an attachment when sending via e-mail</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-1259">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-1259">PowerPoint</span></span>
- <span data-ttu-id="161f7-1260">Wir haben ein Problem behoben, bei dem das Kopieren von Shapes länger als erwartet dauerte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1260">We fixed an issue where copying shapes would take longer than expected</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1261">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1261">Outlook</span></span>
- <span data-ttu-id="161f7-1262">Wir haben ein Problem behoben, bei dem Outlook bei der Verwendung des Zeichnungstools abstürzte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1262">We fixed an issue where Outlook could crash while using the drawing tool</span></span>
- <span data-ttu-id="161f7-1263">Wir haben ein Lokalisierungsproblem beim Verfassen von HTML-E-Mails behoben.</span><span class="sxs-lookup"><span data-stu-id="161f7-1263">We fixed a localization issue when composing html e-mails</span></span>
- <span data-ttu-id="161f7-1264">Wir haben ein Problem behoben, bei dem Benutzer Schwierigkeiten bei der Auswahl des unteren Fensterbereichs hatten.</span><span class="sxs-lookup"><span data-stu-id="161f7-1264">We fixed an issue where the user would have difficulty in selecting the lower pane</span></span>

### <a name="access"></a><span data-ttu-id="161f7-1265">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-1265">Access</span></span>
- <span data-ttu-id="161f7-1266">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1266">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="161f7-1267">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-1267">Project</span></span>
- <span data-ttu-id="161f7-1268">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1268">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-22-2019"></a><span data-ttu-id="161f7-1269">22. März 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-1269">March 22, 2019</span></span>
<span data-ttu-id="161f7-1270">Version 1904 (Build 11514.20004)</span><span class="sxs-lookup"><span data-stu-id="161f7-1270">Version 1904 (build 11514.20004)</span></span>

## <a name="new-features"></a><span data-ttu-id="161f7-1271">Neue Features</span><span class="sxs-lookup"><span data-stu-id="161f7-1271">New Features</span></span>

- <span data-ttu-id="161f7-1272">**Kontrollmechanismen für den Datenschutz:** Neue aktualisierte und verbesserte Kontrollmechanismen für Diagnosedaten und verbundene Oberflächen.</span><span class="sxs-lookup"><span data-stu-id="161f7-1272">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> <span data-ttu-id="161f7-1273">Weitere Informationen <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span><span class="sxs-lookup"><span data-stu-id="161f7-1273">Learn more <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json></span></span>

- <span data-ttu-id="161f7-1274">**Office-Symbole mit neuem Look:** Die Office-Symbole wurden neu gestaltet, um die einfache, leistungsstarke und intelligente Office-Benutzeroberfläche widerzuspiegeln.</span><span class="sxs-lookup"><span data-stu-id="161f7-1274">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-1275">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-1275">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1276">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1276">Word</span></span> 
- <span data-ttu-id="161f7-1277">Ein Problem wurde behoben, bei dem die Benutzeroberfläche ständig "Überprüfung auf Änderungen" anzeigt.</span><span class="sxs-lookup"><span data-stu-id="161f7-1277">We fixed an issue where the UI would constantly display "Checking for Changes"</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-1278">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1278">Excel</span></span>
- <span data-ttu-id="161f7-1279">Ein Problem wurde behoben, bei dem die Anwendung nach dem Verschieben eines Arbeitsblattes abstürzte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1279">We fixed an issue where the application could crash after moving a worksheet</span></span>
- <span data-ttu-id="161f7-1280">Ein Problem wurde behoben, bei dem die Anwendung nach dem Speichern im PDF-Format abstürzte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1280">We fixed an issue where the application could crash after saving as a PDF</span></span>
- <span data-ttu-id="161f7-1281">Ein Problem wurde behoben, bei dem das Dialogfeld "Speichern" einige koreanische Zeichen nicht akzeptierte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1281">We fixed an issue where the save dialog would not accept some Korean characters</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-1282">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-1282">PowerPoint</span></span>
- <span data-ttu-id="161f7-1283">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1283">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1284">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1284">Outlook</span></span>
- <span data-ttu-id="161f7-1285">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1285">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="161f7-1286">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-1286">Access</span></span>
- <span data-ttu-id="161f7-1287">Die Fehlermeldung in Access wurde korrigiert, bei der eine zusätzliche Verknüpfung zu Access erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="161f7-1287">We fixed the error message in Access where an extra shortcut to Access was created</span></span>
- <span data-ttu-id="161f7-1288">Ein Problem wurde behoben, bei dem Daten aus einem verlinkten SharePoint falsch angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="161f7-1288">We fixed an issue where data from a linked SharePoint would display incorrectly</span></span>

### <a name="project"></a><span data-ttu-id="161f7-1289">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-1289">Project</span></span>
- <span data-ttu-id="161f7-1290">Ein Problem wurde behoben, bei dem die Spracheinstellungen von Chinesisch auf Englisch wechselten.</span><span class="sxs-lookup"><span data-stu-id="161f7-1290">We fixed an issue where the language settings would switch from Chinese to English</span></span>
- <span data-ttu-id="161f7-1291">Ein Problem wurde behoben, bei dem die Anwendung beim Synchronisieren mit SharePoint abstürzen konnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1291">We fixed an issue where the application could crash when synching to SharePoint</span></span>

</BR></BR>

## <a name="march-15-2019"></a><span data-ttu-id="161f7-1292">15. März 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-1292">March 15, 2019</span></span>
<span data-ttu-id="161f7-1293">Version 1904 (Build 11504.20000)</span><span class="sxs-lookup"><span data-stu-id="161f7-1293">Version 1904 (build 11504.20000)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-1294">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="161f7-1294">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1295">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1295">Word</span></span>

#### <a name="focus-mode"></a><span data-ttu-id="161f7-1296">Fokusmodus</span><span class="sxs-lookup"><span data-stu-id="161f7-1296">Focus Mode</span></span>

<span data-ttu-id="161f7-1297">Wechseln Sie im Menü Ansicht in den Fokusmodus, damit Sie nicht abgelenkt werden und sich auf Ihre Arbeit konzentrieren können.</span><span class="sxs-lookup"><span data-stu-id="161f7-1297">Switch to Focus on the View menu to remove distractions and concentrate on your work.</span></span> <span data-ttu-id="161f7-1298">Nur für Abonnenten von Office 365.</span><span class="sxs-lookup"><span data-stu-id="161f7-1298">For Office 365 subscribers only.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="161f7-1299">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1299">Getting Started:</span></span>

<span data-ttu-id="161f7-1300">Zugriff durch Schaltfläche „Fokus" auf der Registerkarte „Anzeige".</span><span class="sxs-lookup"><span data-stu-id="161f7-1300">View tab "Focus" Button in the Ribbon Status Bar "Focus" Button</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-1301">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="161f7-1301">Scenarios to Try:</span></span>

<span data-ttu-id="161f7-1302">Schalten Sie den Fokusmodus ein und erleben Sie die fokussierte Benutzererfahrung</span><span class="sxs-lookup"><span data-stu-id="161f7-1302">Enter Focus Mode and experience the Focused Experience</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-1303">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-1303">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1304">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1304">Word</span></span> 
- <span data-ttu-id="161f7-1305">Ein Problem wurde behoben, bei dem Bilder in einem als PDF-Datei gespeicherten Dokument den falschen DPI-Wert aufweisen.</span><span class="sxs-lookup"><span data-stu-id="161f7-1305">We fixed an issue where images in a document saved as a PDF would have the incorrect DPI</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-1306">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1306">Excel</span></span>
- <span data-ttu-id="161f7-1307">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1307">Various performance and stability fixes</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-1308">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-1308">PowerPoint</span></span>
- <span data-ttu-id="161f7-1309">Ein Problem wurde behoben, bei dem der Bereich "Kommentare" sich nicht ordnungsgemäß öffnet oder schließt.</span><span class="sxs-lookup"><span data-stu-id="161f7-1309">We fixed an issue where the comments pane would not open or close properly</span></span>
- <span data-ttu-id="161f7-1310">Ein Problem wurde behoben, bei dem die Anwendung beim Löschen eines Videos abstürzte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1310">We fixed an issue where the application could crash when deleting a video</span></span>
- <span data-ttu-id="161f7-1311">Ein Problem wurde behoben, bei dem die Anwendung in einigen Fällen nicht gestartet werden konnte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1311">We fixed an issue where in some instances the application would fail to launch</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1312">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1312">Outlook</span></span>
- <span data-ttu-id="161f7-1313">Ein Problem wurde behoben, bei dem im Japanischen falsche Lesebestätigungen angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="161f7-1313">We fixed an issue where read receipts were incorrect when viewed in Japanese</span></span>

### <a name="access"></a><span data-ttu-id="161f7-1314">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-1314">Access</span></span>
- <span data-ttu-id="161f7-1315">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1315">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="161f7-1316">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-1316">Project</span></span>
- <span data-ttu-id="161f7-1317">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1317">Various performance and stability fixes</span></span>

</BR></BR>

## <a name="march-8-2019"></a><span data-ttu-id="161f7-1318">8. März 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-1318">March 8, 2019</span></span> 
<span data-ttu-id="161f7-1319">Version 1903 (Build 11425.20036)</span><span class="sxs-lookup"><span data-stu-id="161f7-1319">Version 1903 (build 11425.20036)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-1320">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="161f7-1320">What's New:</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1321">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1321">Word</span></span>

### <a name="find-what-youre-looking-for-with-microsoft-search"></a><span data-ttu-id="161f7-1322">Finden gesuchter Elemente mit Microsoft Search</span><span class="sxs-lookup"><span data-stu-id="161f7-1322">Find What You're Looking For with Microsoft Search</span></span>

<span data-ttu-id="161f7-1323">Mit Microsoft Search können Sie alle Dateien, Aktionen, Personen und Hilfethemen finden, die Sie benötigen, um Ihre Arbeit zu erledigen.</span><span class="sxs-lookup"><span data-stu-id="161f7-1323">With Microsoft Search, you can find all the files, actions, people, and help you need to get work done.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="161f7-1324">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1324">Getting Started:</span></span>

- <span data-ttu-id="161f7-1325">Das Feature wird leicht erkennbar in der Kopfzeile über der Benutzeroberfläche angezeigt.</span><span class="sxs-lookup"><span data-stu-id="161f7-1325">The feature is prominently displayed on top of the UI in the header.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-1326">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="161f7-1326">Scenarios to Try:</span></span>

- <span data-ttu-id="161f7-1327">Suchen nach einer Hochschule, einem aktuellen Dokument oder den Menübandbefehlen, die Sie am häufigsten verwenden</span><span class="sxs-lookup"><span data-stu-id="161f7-1327">Search for a college, a recent document or search for the ribbon commands you use most often</span></span>
- <span data-ttu-id="161f7-1328">Nachschlagen eines Themas, um mehr Informationen darüber zu erhalten</span><span class="sxs-lookup"><span data-stu-id="161f7-1328">Look up a topic or subject to get more information on it</span></span>
- 
#### <a name="coauthoring"></a><span data-ttu-id="161f7-1329">CoAuthoring</span><span class="sxs-lookup"><span data-stu-id="161f7-1329">CoAuthoring</span></span>

<span data-ttu-id="161f7-1330">Sind Sie es leid, von Ihren Dokumenten mit Makros ausgesperrt zu werden?</span><span class="sxs-lookup"><span data-stu-id="161f7-1330">Tired of being locked out of your document with macros?</span></span> <span data-ttu-id="161f7-1331">Jetzt ist die gleichzeitige Bearbeitung durch mehrere Autoren für Ihre docm-Dateien in OneDrive for Business möglich.</span><span class="sxs-lookup"><span data-stu-id="161f7-1331">Now your docm files on OneDrive for Business allow simultaneous editing by multiple authors.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="161f7-1332">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1332">Getting Started:</span></span>

<span data-ttu-id="161f7-1333">Der Benutzer muss keine Schaltflächen auf der Benutzeroberfläche drücken, um auf diese Funktion zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="161f7-1333">The user doesn't need to press any buttons in the UI to access this feature.</span></span> <span data-ttu-id="161f7-1334">Sie ist in OneDrive for Business docm-Dateien standardmäßig aktiviert.</span><span class="sxs-lookup"><span data-stu-id="161f7-1334">It is enabled by default on OneDrive for Business docm files.</span></span>
<span data-ttu-id="161f7-1335">Deshalb sollte der Benutzer eine docm-Datei in OneDrive for Business speichern, um dies auszuprobieren.</span><span class="sxs-lookup"><span data-stu-id="161f7-1335">So, the user should save a docm file to OneDrive for Business to try it out.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-1336">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="161f7-1336">Scenarios to Try:</span></span>

<span data-ttu-id="161f7-1337">Erstellen Sie eine docm-Datei auf OneDrive for Business, teilen Sie sie mit Ihren Kollegen, und arbeiten Sie gemeinsam daran!</span><span class="sxs-lookup"><span data-stu-id="161f7-1337">Create a docm file on OneDrive for Business, share it with your colleagues, and collaborate!</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-1338">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-1338">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1339">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1339">Word</span></span> 
- <span data-ttu-id="161f7-1340">Ein Problem mit einem Absturz wurde behoben, der beim Drücken von ESC in "Optionen" auftrat</span><span class="sxs-lookup"><span data-stu-id="161f7-1340">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="161f7-1341">Die Ursache für einen Absturz wurde behoben, der beim Antworten auf Kommentare auftrat.</span><span class="sxs-lookup"><span data-stu-id="161f7-1341">We fixed a crashing issue that occurred when replying to comments</span></span>
- <span data-ttu-id="161f7-1342">Ein Problem mit dem Kopieren und Einfügen von Word nach PowerPoint Online wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="161f7-1342">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-1343">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1343">Excel</span></span>
- <span data-ttu-id="161f7-1344">Ein Problem wurde behoben, bei dem das Kopieren einer Zelle in Excel zu einer hohen CPU-Auslastung führte, wenn geschützte Dokumente und editierbare Dokumente geöffnet wurden</span><span class="sxs-lookup"><span data-stu-id="161f7-1344">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-1345">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-1345">PowerPoint</span></span>
- <span data-ttu-id="161f7-1346">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1346">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1347">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1347">Outlook</span></span>
- <span data-ttu-id="161f7-1348">Ein Problem wurde behoben, bei dem die Outlook-Suche die ausgewählte chronologische Sortierung nicht einhielt</span><span class="sxs-lookup"><span data-stu-id="161f7-1348">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="161f7-1349">Ein Problem wurde behoben, bei dem die Schaltfläche "Diese Aufgabe öffnen" im Menüband "Workflow" auf bestimmte E-Mails nicht reagierte</span><span class="sxs-lookup"><span data-stu-id="161f7-1349">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="161f7-1350">Ein Problem wurde behoben, bei dem Outlook lokale Räume nicht löschte, nachdem Benutzer einen verfügbaren Raum in der Raumsuche ausgewählt hatten</span><span class="sxs-lookup"><span data-stu-id="161f7-1350">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="161f7-1351">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-1351">Access</span></span>
- <span data-ttu-id="161f7-1352">Das Dialogfeld "Gespeicherter Import/Export", das im dunklen Design weißen Text auf weißem Hintergrund enthielt, wurde korrigiert</span><span class="sxs-lookup"><span data-stu-id="161f7-1352">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="161f7-1353">Ein Problem wurde behoben, bei dem Benutzer die Eigenschaft "DisplayControl" für ein Ja/Nein-Feld im Tabellenentwurf nicht auf Textfeld festlegen konnten</span><span class="sxs-lookup"><span data-stu-id="161f7-1353">We fixed an issue where users could not set the DisplayControl property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="161f7-1354">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-1354">Project</span></span>
- <span data-ttu-id="161f7-1355">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1355">Various performance and stability fixes</span></span>


## <a name="march-1-2019"></a><span data-ttu-id="161f7-1356">1. März 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-1356">March 1, 2019</span></span> 
<span data-ttu-id="161f7-1357">Version 1903 (Build 11414.20014)</span><span class="sxs-lookup"><span data-stu-id="161f7-1357">Version 1903 (build 11414.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-1358">Neuerungen</span><span class="sxs-lookup"><span data-stu-id="161f7-1358">What's New</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1359">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1359">Word</span></span>

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a><span data-ttu-id="161f7-1360">Farben für „Änderungen nachverfolgen", Kommentare und Echtzeitzusammenarbeit jetzt synchronisiert:</span><span class="sxs-lookup"><span data-stu-id="161f7-1360">Colors for Track Changes, Comments and Real-Time Collaboration in Sync</span></span>

<span data-ttu-id="161f7-1361">Korrekturen in unserem Produkt stellen nun sicher, dass Kommentare, Änderungsnachverfolgung und der Cursor für einen Projektmitarbeiter in der gleichen Farbe angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="161f7-1361">Fixes in our product now ensure that the comments, track changes and the cursor for a collaborator show up in the same color.</span></span>

#### <a name="getting-started"></a><span data-ttu-id="161f7-1362">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1362">Getting Started:</span></span>

<span data-ttu-id="161f7-1363">Öffnen Sie ein SharePoint- oder OneDrive-Dokument, das andere Personen geöffnet haben.</span><span class="sxs-lookup"><span data-stu-id="161f7-1363">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="161f7-1364">Vergewissern Sie sich, dass das Nachverfolgen von Änderungen und die Farbe der Kommentare für einen Benutzer mit der Farbe des Cursors eines Benutzers übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="161f7-1364">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-1365">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="161f7-1365">Scenarios to Try:</span></span>

<span data-ttu-id="161f7-1366">Öffnen Sie ein SharePoint- oder OneDrive-Dokument, das andere Personen geöffnet haben.</span><span class="sxs-lookup"><span data-stu-id="161f7-1366">Open a SharePoint or OneDrive document that others have open.</span></span> <span data-ttu-id="161f7-1367">Vergewissern Sie sich, dass das Nachverfolgen von Änderungen und die Farbe der Kommentare für einen Benutzer mit der Farbe des Cursors eines Benutzers übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="161f7-1367">Verify that track changes and comments color for a user matches the color of that user's cursor.</span></span>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-1368">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-1368">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1369">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1369">Word</span></span> 
- <span data-ttu-id="161f7-1370">Ein Problem mit einem Absturz wurde behoben, der beim Drücken von ESC in "Optionen" auftrat</span><span class="sxs-lookup"><span data-stu-id="161f7-1370">We fixed a crashing issue that occurred when pressing ‘ESC’ while in Options</span></span>
- <span data-ttu-id="161f7-1371">Ein Problem mit dem Kopieren und Einfügen von Word nach PowerPoint Online wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="161f7-1371">We fixed an issue with copy & paste from Word to PowerPoint Online</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-1372">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1372">Excel</span></span>
- <span data-ttu-id="161f7-1373">Ein Problem wurde behoben, bei dem das Kopieren einer Zelle in Excel zu einer hohen CPU-Auslastung führte, wenn geschützte Dokumente und editierbare Dokumente geöffnet wurden</span><span class="sxs-lookup"><span data-stu-id="161f7-1373">We fixed an issue where copying a cell in Excel caused high CPU usage when protected document and editable document were opened</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-1374">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-1374">PowerPoint</span></span>
- <span data-ttu-id="161f7-1375">Ein Problem mit der Folienbildgröße bei Verwendung von @Erwähnungen in PowerPoint wurde behoben</span><span class="sxs-lookup"><span data-stu-id="161f7-1375">We fixed an issue with slide image size when using @Mentions in PowerPoint</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1376">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1376">Outlook</span></span>
- <span data-ttu-id="161f7-1377">Ein Problem wurde behoben, bei dem die Outlook-Suche die ausgewählte chronologische Sortierung nicht einhielt</span><span class="sxs-lookup"><span data-stu-id="161f7-1377">We fixed an issue where Outlook Search was not honoring the selected chronological sorting</span></span>
- <span data-ttu-id="161f7-1378">Ein Problem wurde behoben, bei dem die Schaltfläche "Diese Aufgabe öffnen" im Menüband "Workflow" auf bestimmte E-Mails nicht reagierte</span><span class="sxs-lookup"><span data-stu-id="161f7-1378">We fixed an issue where the "Open this task" workflow ribbon button was unresponsive for certain emails</span></span>
- <span data-ttu-id="161f7-1379">Ein Problem wurde behoben, bei dem Outlook lokale Räume nicht löschte, nachdem Benutzer einen verfügbaren Raum in der Raumsuche ausgewählt hatten</span><span class="sxs-lookup"><span data-stu-id="161f7-1379">We fixed an issue where Outlook did not clear on premise rooms after users selected an available room in Room Finder</span></span>

### <a name="access"></a><span data-ttu-id="161f7-1380">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-1380">Access</span></span>
- <span data-ttu-id="161f7-1381">Der Eingabeaufforderungstext wurde aktualisiert, der beim Bestätigen der erneuten Verknüpfung von Tabellen mit einer Datenquelle angezeigt wurde</span><span class="sxs-lookup"><span data-stu-id="161f7-1381">We updated the prompt text that showed when confirming the relinking tables with a datasource</span></span>
- <span data-ttu-id="161f7-1382">Das Dialogfeld "Gespeicherter Import/Export", das im dunklen Design weißen Text auf weißem Hintergrund enthielt, wurde korrigiert</span><span class="sxs-lookup"><span data-stu-id="161f7-1382">We fixed the saved import/export dialog that had white text on white background in Dark Theme</span></span>
- <span data-ttu-id="161f7-1383">Ein Problem wurde behoben, bei dem Benutzer die Eigenschaft "Steuerelement anzeigen" für ein Ja/Nein-Feld im Tabellenentwurf nicht auf Textfeld festlegen konnten</span><span class="sxs-lookup"><span data-stu-id="161f7-1383">We fixed an issue where users could not set the Display Control property for a Yes/No field to Textbox in table design</span></span>

### <a name="project"></a><span data-ttu-id="161f7-1384">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-1384">Project</span></span>
- <span data-ttu-id="161f7-1385">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1385">Various performance and stability fixes</span></span>

</BR></BR>



## <a name="february-15-2019"></a><span data-ttu-id="161f7-1386">15. Februar 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-1386">February 15, 2019</span></span> 
<span data-ttu-id="161f7-1387">Version 1903 (Build 11310.20016)</span><span class="sxs-lookup"><span data-stu-id="161f7-1387">Version 1903 (build 11310.20016)</span></span>

## <a name="whats-new"></a><span data-ttu-id="161f7-1388">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="161f7-1388">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-1389">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-1389">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="161f7-1390">Verbesserungen beim Übergang "Morphen" – Morphen nach Name</span><span class="sxs-lookup"><span data-stu-id="161f7-1390">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="161f7-1391">Geben Sie die Formen an, die Sie morphen möchten.</span><span class="sxs-lookup"><span data-stu-id="161f7-1391">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="161f7-1392">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1392">Getting Started:</span></span>

- <span data-ttu-id="161f7-1393">Damit beim Morphen zwei Objekte als das gleiche Objekt behandelt werden, kann der Benutzer die Formen über das Auswahlfenster umbenennen.</span><span class="sxs-lookup"><span data-stu-id="161f7-1393">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="161f7-1394">Der Name muss mit "!!" </span><span class="sxs-lookup"><span data-stu-id="161f7-1394">The name must be prefaced with “!!”</span></span> <span data-ttu-id="161f7-1395">(zwei Ausrufezeichen) beginnen, damit er beim Morphen zum Überschreiben des Standardabgleichsverhaltens verwendet wird, z. B. "!!Name".</span><span class="sxs-lookup"><span data-stu-id="161f7-1395">(two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="161f7-1396">Benutzer können Formen weiterhin mit beliebigen Namen umbenennen, die nicht mit "!!" beginnen, </span><span class="sxs-lookup"><span data-stu-id="161f7-1396">Users can continue to rename shapes with any name that doesn’t start with “!!”</span></span> <span data-ttu-id="161f7-1397">ohne dass dadurch die Funktionsweise von Morph geändert wird.</span><span class="sxs-lookup"><span data-stu-id="161f7-1397">without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-1398">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="161f7-1398">Scenarios to Try:</span></span>

- <span data-ttu-id="161f7-1399">Fügen Sie eine Form auf einer Folie ein, z.B. ein Rechteck.</span><span class="sxs-lookup"><span data-stu-id="161f7-1399">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="161f7-1400">Erstellen Sie eine neue Folie.</span><span class="sxs-lookup"><span data-stu-id="161f7-1400">Create a new slide</span></span>
- <span data-ttu-id="161f7-1401">Fügen Sie eine andere Form auf der zweiten Folie ein, z.B. ein Dreieck.</span><span class="sxs-lookup"><span data-stu-id="161f7-1401">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="161f7-1402">Öffnen Sie das Auswahlfenster, benennen Sie das Rechteck in Folie 1 in "!!Form" und das Dreieck in Folie 2 in "!!Form" um.</span><span class="sxs-lookup"><span data-stu-id="161f7-1402">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="161f7-1403">Wenden Sie Morphen auf die zweite Folie an.</span><span class="sxs-lookup"><span data-stu-id="161f7-1403">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="161f7-1404">Verbesserungen beim Übergang "Morphen" – SmartArt</span><span class="sxs-lookup"><span data-stu-id="161f7-1404">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="161f7-1405">SmartArt-Morphen mit weicheren Übergängen</span><span class="sxs-lookup"><span data-stu-id="161f7-1405">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="161f7-1406">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1406">Getting Started:</span></span>

<span data-ttu-id="161f7-1407">Verwenden Sie Morphen wie bei SmartArt.</span><span class="sxs-lookup"><span data-stu-id="161f7-1407">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-1408">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="161f7-1408">Scenarios to Try:</span></span>

- <span data-ttu-id="161f7-1409">Fügen Sie eine SmartArt auf einer Folie ein.</span><span class="sxs-lookup"><span data-stu-id="161f7-1409">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="161f7-1410">Duplizieren Sie die Folie.</span><span class="sxs-lookup"><span data-stu-id="161f7-1410">Duplicate the Slide</span></span>
- <span data-ttu-id="161f7-1411">Ändern oder verschieben Sie die SmartArt auf der duplizierten Folie, oder ändern Sie deren Größe.</span><span class="sxs-lookup"><span data-stu-id="161f7-1411">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="161f7-1412">Wenden Sie Morph auf die duplizierte Folie an.</span><span class="sxs-lookup"><span data-stu-id="161f7-1412">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="161f7-1413">Verbesserungen beim Übergang "Morphen" – Tabellen</span><span class="sxs-lookup"><span data-stu-id="161f7-1413">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="161f7-1414">Tabellen-Morphen mit weicheren Übergängen</span><span class="sxs-lookup"><span data-stu-id="161f7-1414">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="161f7-1415">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="161f7-1415">Getting Started:</span></span>
<span data-ttu-id="161f7-1416">Verwenden Sie Morphen wie bei Tabellen.</span><span class="sxs-lookup"><span data-stu-id="161f7-1416">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-1417">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="161f7-1417">Scenarios to Try:</span></span>

- <span data-ttu-id="161f7-1418">Fügen Sie eine Tabelle auf einer Folie ein.</span><span class="sxs-lookup"><span data-stu-id="161f7-1418">Insert a Table in a slide</span></span>
- <span data-ttu-id="161f7-1419">Duplizieren Sie die Folie.</span><span class="sxs-lookup"><span data-stu-id="161f7-1419">Duplicate the slide</span></span>
- <span data-ttu-id="161f7-1420">Ändern oder verschieben Sie die Tabelle auf der duplizierten Folie, oder ändern Sie deren Größe.</span><span class="sxs-lookup"><span data-stu-id="161f7-1420">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="161f7-1421">Wenden Sie Morph auf die duplizierte Folie an.</span><span class="sxs-lookup"><span data-stu-id="161f7-1421">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="161f7-1422">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher und Visio</span><span class="sxs-lookup"><span data-stu-id="161f7-1422">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="161f7-1423">Nahtloses Wechseln zwischen Konten</span><span class="sxs-lookup"><span data-stu-id="161f7-1423">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="161f7-1424">Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Konten an einem Ort an, und erleichtert Ihnen das Wechseln zwischen diesen Konten.</span><span class="sxs-lookup"><span data-stu-id="161f7-1424">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them.</span></span> <span data-ttu-id="161f7-1425">Diese aktualisierte Oberfläche verdeutlicht, wie Sie gerade angemeldet sind. Jetzt können Sie zwischen geschäftlichen und privaten Konten wechseln, ohne sich vorher abmelden zu müssen oder sich mit komplexen Dialogfeldern zu beschäftigen.</span><span class="sxs-lookup"><span data-stu-id="161f7-1425">This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a><span data-ttu-id="161f7-1427">Mögliche Szenarien:</span><span class="sxs-lookup"><span data-stu-id="161f7-1427">Scenarios to Try:</span></span>
- <span data-ttu-id="161f7-1428">Wechseln zwischen Konten</span><span class="sxs-lookup"><span data-stu-id="161f7-1428">Switch between accounts</span></span>
- <span data-ttu-id="161f7-1429">Hinzufügen eines neuen Kontos [Hinweis: Sie sollten möglicherweise zuerst zu "Datei" | "Konto" | "Verbundene Dienste" navigieren und alle persönlichen Dienste entfernen, die mit Geschäftskonten verbunden sind oder umgekehrt].</span><span class="sxs-lookup"><span data-stu-id="161f7-1429">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="161f7-1430">Abmelden von einem Konto</span><span class="sxs-lookup"><span data-stu-id="161f7-1430">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="161f7-1431">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-1431">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1432">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1432">Word</span></span> 
- <span data-ttu-id="161f7-1433">Ein Problem mit der Kontextvorschau für Tabellen und Bilder wurde behoben</span><span class="sxs-lookup"><span data-stu-id="161f7-1433">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-1434">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1434">Excel</span></span>
- <span data-ttu-id="161f7-1435">Ein Problem wurde behoben, bei dem Text im "AutoFilter"-Suchfeld im Design "Schwarz" weiß angezeigt wird</span><span class="sxs-lookup"><span data-stu-id="161f7-1435">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="161f7-1436">Ein Problem mit der Zustimmungsbenutzeroberfläche beim neuen Office-Add-In wurde behoben</span><span class="sxs-lookup"><span data-stu-id="161f7-1436">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-1437">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-1437">PowerPoint</span></span>
- <span data-ttu-id="161f7-1438">Ein Problem mit der sich automatisch erweiternden Anzeige beim Präsentieren von Bildschirmpräsentationen auf Laptops oder Tablets wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="161f7-1438">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1439">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1439">Outlook</span></span>
- <span data-ttu-id="161f7-1440">Ein Problem mit dem Anzeigen der Schaltfläche "An OneNote senden" wurde behoben</span><span class="sxs-lookup"><span data-stu-id="161f7-1440">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="161f7-1441">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-1441">Access</span></span>
- <span data-ttu-id="161f7-1442">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1442">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="161f7-1443">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-1443">Project</span></span>
- <span data-ttu-id="161f7-1444">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1444">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-11-2019"></a><span data-ttu-id="161f7-1445">11. Februar 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-1445">February 11, 2019</span></span>
<span data-ttu-id="161f7-1446">Version 1903 (Build 11330.20014)</span><span class="sxs-lookup"><span data-stu-id="161f7-1446">Version 1903 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="161f7-1447">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="161f7-1447">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1448">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1448">Word</span></span> 
- <span data-ttu-id="161f7-1449">Es wurde ein Problem behoben, bei dem einige angepasste Formatvorlagen nicht auf Word Online angewendet werden konnten.</span><span class="sxs-lookup"><span data-stu-id="161f7-1449">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="161f7-1450">Es wurden Probleme in der Kontextvorschau mit umfangreichen Objekten in Word behoben.</span><span class="sxs-lookup"><span data-stu-id="161f7-1450">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="161f7-1451">Es wurde ein Problem behoben, bei dem Word beim Einfügen von Listen abstürzte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1451">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-1452">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1452">Excel</span></span>
- <span data-ttu-id="161f7-1453">Es wurde ein Problem behoben, bei dem angefügte Leerzeichen nach Zahlenformaten nicht mehr angezeigt werden, wenn kein Währungssymbol vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="161f7-1453">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="161f7-1454">Es wurde ein Problem mit der automatischen Erkennung von Aktien behoben.</span><span class="sxs-lookup"><span data-stu-id="161f7-1454">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-1455">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-1455">PowerPoint</span></span>
- <span data-ttu-id="161f7-1456">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1456">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1457">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1457">Outlook</span></span>
- <span data-ttu-id="161f7-1458">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1458">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="161f7-1459">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-1459">Access</span></span>
- <span data-ttu-id="161f7-1460">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1460">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="161f7-1461">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-1461">Project</span></span>
- <span data-ttu-id="161f7-1462">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1462">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="february-1-2019"></a><span data-ttu-id="161f7-1463">1. Februar 2019</span><span class="sxs-lookup"><span data-stu-id="161f7-1463">February 1, 2019</span></span> 
<span data-ttu-id="161f7-1464">Version 1902 (Build 11326.20000)</span><span class="sxs-lookup"><span data-stu-id="161f7-1464">Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="161f7-1465">Wichtige Fixes</span><span class="sxs-lookup"><span data-stu-id="161f7-1465">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="161f7-1466">Word</span><span class="sxs-lookup"><span data-stu-id="161f7-1466">Word</span></span> 
- <span data-ttu-id="161f7-1467">Ein Problem mit der Größenänderung von Zellen in einer eingebetteten Excel-Tabelle wurde behoben</span><span class="sxs-lookup"><span data-stu-id="161f7-1467">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="161f7-1468">Ein Problem mit dem Kopieren/Einfügen von Formen in einem Zeichenbereich wurde behoben</span><span class="sxs-lookup"><span data-stu-id="161f7-1468">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="161f7-1469">Excel</span><span class="sxs-lookup"><span data-stu-id="161f7-1469">Excel</span></span>
- <span data-ttu-id="161f7-1470">Ein Problem mit dem Öffnen von Dateien aus Excel Web App wurde behoben</span><span class="sxs-lookup"><span data-stu-id="161f7-1470">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="161f7-1471">Ein Problem wurde behoben, durch das das Speichern einer CSV-Datei als XLSX-Datei aufgrund der Dateinamengröße fehlschlug.</span><span class="sxs-lookup"><span data-stu-id="161f7-1471">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="161f7-1472">Ein Problem mit dem Kontextmenü, dessen Kontextmenüoptionen nicht angezeigt wurden, wurde behoben</span><span class="sxs-lookup"><span data-stu-id="161f7-1472">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="161f7-1473">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="161f7-1473">PowerPoint</span></span>
- <span data-ttu-id="161f7-1474">Ein Problem wurde behoben, durch das Benutzer eckige Klammern nicht mithilfe der Tastenkombinationen STRG+ALT+7/STRG+ALT+8 eingeben konnten.</span><span class="sxs-lookup"><span data-stu-id="161f7-1474">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="161f7-1475">Ein Problem wurde behoben, bei dem das Einfügen eines lokalen Videos in die PPT-Datei den Festplattenspeicher des Laufwerks C reduzierte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1475">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="161f7-1476">Die Schaltfläche "In Microsoft Stream veröffentlichen", die einigen Benutzern nicht angezeigt wurde, wurde korrigiert.</span><span class="sxs-lookup"><span data-stu-id="161f7-1476">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="161f7-1477">Outlook</span><span class="sxs-lookup"><span data-stu-id="161f7-1477">Outlook</span></span>
- <span data-ttu-id="161f7-1478">Ein Problem wurde behoben, bei dem die Aufgabenansicht im Kalender das Thema der Aufgabe nicht richtig anzeigte.</span><span class="sxs-lookup"><span data-stu-id="161f7-1478">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="161f7-1479">Access</span><span class="sxs-lookup"><span data-stu-id="161f7-1479">Access</span></span>
- <span data-ttu-id="161f7-1480">Ein Skalierungsproblem mit Diagrammen wurde behoben</span><span class="sxs-lookup"><span data-stu-id="161f7-1480">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="161f7-1481">Project</span><span class="sxs-lookup"><span data-stu-id="161f7-1481">Project</span></span>
- <span data-ttu-id="161f7-1482">Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität</span><span class="sxs-lookup"><span data-stu-id="161f7-1482">Various performance and stability fixes</span></span>

---
title: Versionshinweise für Releases im monatlichen Enterprise-Kanal
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt IT-Experten Versionshinweise für Releases im monatlichen Enterprise-Kanal für Microsoft 365 Apps zur Verfügung.
ms.openlocfilehash: 96a76ed1ed1849753422dae92626484a77cec2a4
ms.sourcegitcommit: 4f5536e809f58462d81c708c153390ebfd1abc4e
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/13/2021
ms.locfileid: "53409561"
---
# <a name="release-notes-for-monthly-enterprise-channel"></a><span data-ttu-id="a2bb8-103">Versionshinweise für den monatlichen Enterprise-Kanal</span><span class="sxs-lookup"><span data-stu-id="a2bb8-103">Release notes for Monthly Enterprise Channel</span></span>

<span data-ttu-id="a2bb8-104">Diese Versionshinweise enthalten Informationen zu neuen Funktionen und nicht sicherheitsrelevanten Updates, die in monatlichen Enterprise-Kanal-Updates für Microsoft 365 Apps for Enterprise, Microsoft 365 Apps for Business sowie in den Abonnementversionen der Desktop-Apps für Project und Visio enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-104">These release notes provide information about new features and non-security updates that are included in Monthly Enterprise Channel updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


[//]: # (NICHT ENTFERNEN)



## <a name="version-2105-july-13"></a><span data-ttu-id="a2bb8-106">Version 2105: 13. Juli</span><span class="sxs-lookup"><span data-stu-id="a2bb8-106">Version 2105: July 13</span></span>
<span data-ttu-id="a2bb8-107">*Version 2105 (Build 14026.20334)*</span><span class="sxs-lookup"><span data-stu-id="a2bb8-107">*Version 2105 (Build 14026.20334)*</span></span>

<span data-ttu-id="a2bb8-108">Sicherheitsupdates sind [hier](microsoft365-apps-security-updates.md) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="a2bb8-108">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a2bb8-110">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a2bb8-110">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="a2bb8-111">Outlook</span><span class="sxs-lookup"><span data-stu-id="a2bb8-111">Outlook</span></span>

- <span data-ttu-id="a2bb8-112">**Erhalten Sie relevante Dateivorschläge, wenn Sie eine Suche durchfuhren:** Wenn Sie im Suchfeld eingeben, werden die relevantesten Dateien, die sich auf Ihre Suche beziehen, in Ihre Vorschläge aufgenommen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-112">**Get relevant file suggestions when you search:** When you type in the Search box, the most relevant files related to your search will be included in your suggestions.</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a2bb8-115">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a2bb8-115">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a2bb8-116">Excel</span><span class="sxs-lookup"><span data-stu-id="a2bb8-116">Excel</span></span>

- <span data-ttu-id="a2bb8-117">Es wurde eine Problem behoben, damit der Namens-Manager bei Büchern mit einer großen Anzahl von ausgeblendeten Namen geöffnet werden kann.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-117">Fixed an issue to enable the Name Manager to open on books with a large number of hidden names.</span></span>


- <span data-ttu-id="a2bb8-118">Es wurde ein Problem behoben, bei dem bei einigen Benutzern zusätzliche Einträge in der Excel-Add-In-Liste angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-118">We fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>


- <span data-ttu-id="a2bb8-119">Es wurde ein Problem behoben, bei dem das Add-In „Analyse-Funktionen“ für einige Benutzer nicht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-119">Fixed an issue where the Analysis ToolPak add-in did not work for some users.</span></span>


### <a name="outlook"></a><span data-ttu-id="a2bb8-120">Outlook</span><span class="sxs-lookup"><span data-stu-id="a2bb8-120">Outlook</span></span>

- <span data-ttu-id="a2bb8-121">Die Änderung kann bei Problemen schnell deaktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-121">Change is going in dark and under a change gate so if there are issues it can be turned off quickly.</span></span>


- <span data-ttu-id="a2bb8-122">Es wurde ein Registrierungsschlüssel hinzugefügt, mit dem die neue Benutzeroberfläche der Raumsuche (dieselbe Benutzeroberfläche wie in Outlook für Web) deaktiviert und die Vorgängerversion der Raumsuche mit "Vorgeschlagene Zeiten" aktiviert wird.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-122">We added a registry key that disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with Suggested Times.</span></span>

   <span data-ttu-id="a2bb8-123">Registrierungsschlüssel:</span><span class="sxs-lookup"><span data-stu-id="a2bb8-123">Registry Key:</span></span>

    ><span data-ttu-id="a2bb8-124">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="a2bb8-124">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar REG_DWORD “ShowLegacyRoomFinder”</span></span>

    ><span data-ttu-id="a2bb8-125">0 (Standard) – Outlook verwendet die neue von OWA unterstützte Benutzeroberfläche für die Raumsuche, wenn der Benutzer auf die Schaltfläche „Raumsuche“ klickt, um nach verfügbaren Räumen zu suchen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-125">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span></br>
    ><span data-ttu-id="a2bb8-126">1 – Outlook verwendet die ältere Benutzeroberfläche der Raumsuche, um nach verfügbaren Räumen zu suchen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-126">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span>


- <span data-ttu-id="a2bb8-127">Durch diese Änderung können Benutzer Feedback über unser neues Feedbacksystem übermitteln.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-127">This change enables users to submit feedback through our new feedback system.</span></span>


- <span data-ttu-id="a2bb8-128">Wir haben ein Problem behoben, durch das die Feedbackoption für Benutzer der Office Dauerlizenz 2021-Vorschau deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-128">We fixed an issue that caused the feedback option to be disabled for users of the Office Perpetual 2021 preview.</span></span>


- <span data-ttu-id="a2bb8-129">Ein Problem wurde behoben, das dazu führte, dass Benutzer einen Fehler erhielten, wenn sie „Outlook-Eigenschaften öffnen“ über ein Kontextmenü für einen Empfänger in einer E-Mail auswählten.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-129">We fixed an issue that caused users to get an error when selecting "Open Outlook Properties" from the right click context menu for a recipient on an email.</span></span>


- <span data-ttu-id="a2bb8-130">Es wurde ein Problem behoben, das dazu führte, dass Outlook bei einigen Benutzern beim Laden von Personenkarten unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-130">We fixed an issue that caused some users to experience unexpected app close when loading person cards.</span></span>


- <span data-ttu-id="a2bb8-131">Ein Problem wurde behoben, das dazu führte, dass Outlook unerwartet geschlossen wurde, wenn Benutzer Ordner aus einem Archivspeicher entfernten.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-131">We fixed an issue that caused users to experience a unexpected close when removing folders from an archive store.</span></span>


- <span data-ttu-id="a2bb8-132">Es wurde ein Problem behoben, durch das einige Anweisungen für das Feature „Besprechungen kürzen“ aufgrund von Sprachausgabetechnologien deaktiviert waren.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-132">We fixed an issue that caused some instructions for the "Shorten Meetings" feature to be disabled through screen reader technologies.</span></span>


- <span data-ttu-id="a2bb8-133">Es wurde ein Problem behoben, das dazu führte, dass Benutzern beim Schließen einer Nachricht, auf die sie geantwortet oder die sie weitergeleitet hatten, eine unerwartete Aufforderung zum Ändern der Eigenschaft angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-133">We fixed an issue that caused users to experience an unexpected property change prompt when closing a message they had replied to or forwarded.</span></span>


- <span data-ttu-id="a2bb8-134">Ein Problem wurde behoben, das zu einem unerwarteten Schließen bei der Interaktion mit der Outlook Mail- oder Kalenderansichten führen kann.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-134">We fixed an issue that may cause a unexpected close when interacting with Outlook Mail or Calendar Views.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a2bb8-135">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a2bb8-135">PowerPoint</span></span>

- <span data-ttu-id="a2bb8-136">Es wurde ein Problem behoben, bei dem die Option „Folien wiederverwenden“ für wenige Benutzer nicht verfügbar war.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-136">Fixed an issue where Reuse Slides option was not available for few users.</span></span>


### <a name="project"></a><span data-ttu-id="a2bb8-137">Project</span><span class="sxs-lookup"><span data-stu-id="a2bb8-137">Project</span></span>

- <span data-ttu-id="a2bb8-138">Ein Problem wurde behoben, bei dem Zuordnungen zu manuell geplanten Vorgängen möglicherweise auf ein falsches Datum verschoben wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-138">Fixed an issue where assignments on manually scheduled tasks moved to an incorrect date.</span></span>


- <span data-ttu-id="a2bb8-139">Ein Problem wurde behoben, bei dem, wenn Sie eine Formel für ein benutzerdefiniertes Feld erstellen, die die ProjectDate */ProjectDur*-Funktionen verwendet, und der zweite Parameter die Datums- und Zeitfunktionen „Date()“, „Now()“ oder „Time()“ sind, dann ein #FEHLER auftrat.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-139">Fixed an issue where if you create a custom field formula which uses the ProjectDate */ProjectDur* functions and if the second parameter is the Date(), Now() or Time() date and time functions, then a #ERROR results.</span></span>


### <a name="word"></a><span data-ttu-id="a2bb8-140">Word</span><span class="sxs-lookup"><span data-stu-id="a2bb8-140">Word</span></span>

- <span data-ttu-id="a2bb8-141">Behebt ein Problem, bei dem der Editorbereich nicht geöffnet wird.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-141">Fixes an issue where the Editor Pane doesn't open.</span></span>


- <span data-ttu-id="a2bb8-142">Es wurde eine Problem behoben, bei dem in kontextbezogenen Karten für Rechtschreibung und Grammatik im Zusammenarbeitsbereich Schaltflächen-Symbole angezeigt wurden, diese Schaltflächen aber keine QuickInfo aufwiesen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-142">Fixed an issue where canvas contextual cards for spelling and grammar show icon buttons, but those buttons have no tooltips.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a2bb8-143">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a2bb8-143">Office Suite</span></span>

- <span data-ttu-id="a2bb8-144">Ein Lokalisierungsproblem wurde behoben, bei dem en-gb, fr-ca und es-mx nun mit ihren jeweiligen übergeordneten Versionen abgeglichen werden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-144">Fixed a localization issue where en-gb, fr-ca, and es-mx will now be matched with their respective parent versions.</span></span>


- <span data-ttu-id="a2bb8-145">Ein unerwartetes Schließen beim erneuten Öffnen bestimmter Dateien wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-145">Fixed a unexpected close when reopening certain files.</span></span>


- <span data-ttu-id="a2bb8-146">Eine Leistungsregression beim Öffnen von SyncBacked-Dateien wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-146">Fixed a performance regression on opening SyncBacked files.</span></span>


- <span data-ttu-id="a2bb8-147">Ein Problem wurde behoben, bei dem Benutzer bestimmte auf lokalen SharePoint-Servern gespeicherte Dokumente nicht bearbeiten können.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-147">Fixed an issue where user is unable to edit certain documents stored in OnPrem sharepoint servers.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2104-july-13"></a><span data-ttu-id="a2bb8-149">Version 2104: 13. Juli</span><span class="sxs-lookup"><span data-stu-id="a2bb8-149">Version 2104: July 13</span></span>
<span data-ttu-id="a2bb8-150">*Version 2104 (Build 13929.20434)*</span><span class="sxs-lookup"><span data-stu-id="a2bb8-150">*Version 2104 (Build 13929.20434)*</span></span>

<span data-ttu-id="a2bb8-151">Sicherheitsupdates sind [hier](microsoft365-apps-security-updates.md) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="a2bb8-151">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2104-june-08"></a><span data-ttu-id="a2bb8-152">Version 2104: 08. Juni</span><span class="sxs-lookup"><span data-stu-id="a2bb8-152">Version 2104: June 08</span></span>
<span data-ttu-id="a2bb8-153">*Version 2104 (Build 13929.20408)*</span><span class="sxs-lookup"><span data-stu-id="a2bb8-153">*Version 2104 (Build 13929.20408)*</span></span>

<span data-ttu-id="a2bb8-154">Sicherheitsupdates sind [hier](microsoft365-apps-security-updates.md) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="a2bb8-154">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a2bb8-156">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a2bb8-156">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a2bb8-157">Excel</span><span class="sxs-lookup"><span data-stu-id="a2bb8-157">Excel</span></span>

- <span data-ttu-id="a2bb8-158">**AutoSpeichern und gemeinsame Dokumentenerstellung für vertrauliche, verschlüsselte Dokumente:** Tauschen Sie nicht die Produktivität gegen die Sicherheit ein.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-158">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="a2bb8-159">Mit Microsoft Information Protection können Dokumente, die mit Vertraulichkeitsbezeichnungen verschlüsselt sind, jetzt genauso wie unverschlüsselte Dokumente automatisch gespeichert und mit anderen in Echtzeit gemeinsam bearbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-159">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="a2bb8-160">Erfordert Einverständnis des Mandanten (weitere Informationen: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="a2bb8-160">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a2bb8-161">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a2bb8-161">PowerPoint</span></span>

- <span data-ttu-id="a2bb8-162">**AutoSpeichern und gemeinsame Dokumentenerstellung für vertrauliche, verschlüsselte Dokumente:** Tauschen Sie nicht die Produktivität gegen die Sicherheit ein.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-162">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="a2bb8-163">Mit Microsoft Information Protection können Dokumente, die mit Vertraulichkeitsbezeichnungen verschlüsselt sind, jetzt genauso wie unverschlüsselte Dokumente automatisch gespeichert und mit anderen in Echtzeit gemeinsam bearbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-163">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="a2bb8-164">Erfordert Einverständnis des Mandanten (weitere Informationen: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="a2bb8-164">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>

### <a name="word"></a><span data-ttu-id="a2bb8-165">Word</span><span class="sxs-lookup"><span data-stu-id="a2bb8-165">Word</span></span>

- <span data-ttu-id="a2bb8-166">**AutoSpeichern und gemeinsame Dokumentenerstellung für vertrauliche, verschlüsselte Dokumente:** Tauschen Sie nicht die Produktivität gegen die Sicherheit ein.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-166">**AutoSave and coauthoring on sensitive encrypted documents:** Don't trade off productivity for security.</span></span> <span data-ttu-id="a2bb8-167">Mit Microsoft Information Protection können Dokumente, die mit Vertraulichkeitsbezeichnungen verschlüsselt sind, jetzt genauso wie unverschlüsselte Dokumente automatisch gespeichert und mit anderen in Echtzeit gemeinsam bearbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-167">With Microsoft Information Protection, documents that are encrypted with sensitivity labels can now be AutoSaved and co-authored with others in real time just like unencrypted documents can.</span></span> <span data-ttu-id="a2bb8-168">Erfordert Einverständnis des Mandanten (weitere Informationen: https://aka.ms/mipcoauth).</span><span class="sxs-lookup"><span data-stu-id="a2bb8-168">Requires tenant opt-in (more info: https://aka.ms/mipcoauth).</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a2bb8-171">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a2bb8-171">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a2bb8-172">Excel</span><span class="sxs-lookup"><span data-stu-id="a2bb8-172">Excel</span></span>

- <span data-ttu-id="a2bb8-173">Es wurde ein Problem behoben, bei dem einige Dateien gelegentlich nicht in der geschützten Ansicht geöffnet werden konnten.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-173">We fixed an issue where some files would occasionally fail to open in Protected View.</span></span>


- <span data-ttu-id="a2bb8-174">Es wurde ein Problem behoben, das dazu führte, dass die Datumsformatierung bei der Verwendung von Add-Ins in einigen Sprachen nicht korrekt angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-174">We fixed an issue that caused date formatting to be displayed incorrectly in some languages when using add-ins.</span></span>


- <span data-ttu-id="a2bb8-175">Es wurde ein Problem behoben, bei dem das Add-In „Analyse-Funktionen“ für einige Benutzer nicht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-175">Fixed an issue where the Analysis ToolPak add-in did not work for some users.</span></span>


- <span data-ttu-id="a2bb8-176">Es wurde ein Problem behoben, bei dem bei einigen Benutzern zusätzliche Einträge in der Excel-Add-In-Liste angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-176">Fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>


- <span data-ttu-id="a2bb8-177">Fix für ein Problem, bei dem ein Rollback der Hauptversion zum Beenden der Anwendung beim Öffnen von Dateien führen konnte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-177">Fix for an issue where a major version build rollback could result in the application terminating on file open.</span></span>


### <a name="outlook"></a><span data-ttu-id="a2bb8-178">Outlook</span><span class="sxs-lookup"><span data-stu-id="a2bb8-178">Outlook</span></span>

- <span data-ttu-id="a2bb8-179">Es wurde ein Problem behoben, bei dem für einige Benutzer der Funktion zur Verbesserung der Kalenderfreigaben Probleme auftraten, wenn Sie im Navigationsbereich mit Ihrem Kalender interagierten.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-179">We fixed an issue that caused some users of the calendar sharing improvements feature to experience issues with interacting with their calendar in the navigation pane.</span></span>


- <span data-ttu-id="a2bb8-180">Es wurde ein Registrierungsschlüssel hinzugefügt, mit dem die neue Benutzeroberfläche der Raumsuche (dieselbe Benutzeroberfläche wie in Outlook für Web) deaktiviert und die Vorgängerversion der Raumsuche mit "Vorgeschlagene Zeiten" aktiviert wird.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-180">We added a registry key that disables the new Room Finder experience (the same experience as in Outlook for Web) and enables the legacy Room Finder with Suggested Times.</span></span>
    
    <span data-ttu-id="a2bb8-181">Registrierungsschlüssel:</span><span class="sxs-lookup"><span data-stu-id="a2bb8-181">Registry Key:</span></span>

    ><span data-ttu-id="a2bb8-182">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span><span class="sxs-lookup"><span data-stu-id="a2bb8-182">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar</span></span> </br>
    ><span data-ttu-id="a2bb8-183">REG_DWORD “ShowLegacyRoomFinder”</span><span class="sxs-lookup"><span data-stu-id="a2bb8-183">REG_DWORD “ShowLegacyRoomFinder”</span></span></br></br>
    > <span data-ttu-id="a2bb8-184">0 (Standard) – Outlook verwendet die neue von OWA unterstützte Benutzeroberfläche für die Raumsuche, wenn der Benutzer auf die Schaltfläche „Raumsuche“ klickt, um nach verfügbaren Räumen zu suchen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-184">0 (default) - Outlook uses new Room Finder OWA Powered eXperience when user clicks 'Room Finder' button to search for available rooms</span></span>  </br>
    > <span data-ttu-id="a2bb8-185">1 – Outlook verwendet die ältere Benutzeroberfläche der Raumsuche, um nach verfügbaren Räumen zu suchen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-185">1 - Outlook uses legacy Room Finder UI to search for available rooms</span></span> </br>


- <span data-ttu-id="a2bb8-186">Wir haben ein Problem behoben, durch das die Namensauflösung fehlschlug, sobald etwas im Namen eines anderen Benutzers gesendet wurde und das mit einem Adressbuch verglichen wurde, das nicht der globalen Adressliste entsprach.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-186">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="a2bb8-187">Es wurde ein Problem behoben, durch das die Feedback-Option für Benutzer der Vorschauversion der Office Dauerlizenz 2021 nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-187">We fixed an issue that caused the feedback option to fail to appear for users of the Office Perpetual 2021 preview.</span></span>


- <span data-ttu-id="a2bb8-188">Wir haben ein Problem behoben, durch das Benutzern möglicherweise die Meldung angezeigt wurde, dass der Fokus auf der Benutzeroberfläche verloren geht.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-188">We fixed an issue that could cause users to see the message that they are composing losing the UI focus.</span></span>


- <span data-ttu-id="a2bb8-189">Wir haben ein Problem behoben, durch das Outlook die in OWA konfigurierten Einstellungen für den Posteingang mit Relevanz außer Kraft gesetzt hat.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-189">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="a2bb8-190">Es wurde ein Problem behoben, das dazu führte, dass die Signaturen von Benutzern unerwartet verschwanden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-190">We fixed an issue that caused users to see signatures disappear unexpectedly.</span></span>


- <span data-ttu-id="a2bb8-191">Es wurde ein Problem behoben, das bei der Nutzung von Roaming-Einstellungen zu Nichtreagieren führte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-191">We fixed an issue that caused users of roaming settings to experience unresponsiveness.</span></span>


- <span data-ttu-id="a2bb8-192">Es wurde ein Problem behoben, das dazu führte, dass der Prozess bei der Suche unerwartet beendet wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-192">We fixed an issue that caused users to experience the process terminating unexpectedly when searching.</span></span>


- <span data-ttu-id="a2bb8-193">Das Problem des unerwarteten Schließens bei einer Suche wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-193">We fixed a search-related unexpected close.</span></span>


- <span data-ttu-id="a2bb8-194">Es wurde ein Problem behoben, durch das die Personenauswahl in Outlook bei Benutzern mit einer unbefristeten Lizenz nach oben anstatt nach unten erweitert wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-194">We fixed an issue that caused the people picker in Outlook to expand upwards rather than downwards for users with a perpetual license.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a2bb8-195">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a2bb8-195">PowerPoint</span></span>

- <span data-ttu-id="a2bb8-196">Es wurde ein Problem behoben, bei dem die Option „Folien wiederverwenden“ für einige Benutzer nicht verfügbar war.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-196">Fixed an issue where Reuse Slides option was not available for a few users.</span></span>


- <span data-ttu-id="a2bb8-197">Es wurde ein Problem im Zusammenhang mit verknüpften Bildern behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-197">We fixed an issue related to linked pictures.</span></span>


- <span data-ttu-id="a2bb8-198">Es wurde ein Problem behoben, bei dem ein Rollback der Hauptversion zu einem unerwarteten Schließen beim Öffnen von Dateien führen konnte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-198">Fixed an issue where a major version build rollback could result in an unexpected close on file open.</span></span>


### <a name="project"></a><span data-ttu-id="a2bb8-199">Project</span><span class="sxs-lookup"><span data-stu-id="a2bb8-199">Project</span></span>

- <span data-ttu-id="a2bb8-200">Es wurde ein Problem behoben, bei dem Benutzer Projekte nicht aus dem Ressourcenpool entfernen konnten.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-200">Fixed an issue where users were unable to remove projects from the resource pool.</span></span>


### <a name="word"></a><span data-ttu-id="a2bb8-201">Word</span><span class="sxs-lookup"><span data-stu-id="a2bb8-201">Word</span></span>

- <span data-ttu-id="a2bb8-202">Es wurde ein Problem behoben, das eine Änderung beim Bearbeiten von OLE-Objekten erforderte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-202">We fixed an issue which required a change on editing OLE object.</span></span>


- <span data-ttu-id="a2bb8-203">Es wurde ein Problem behoben, bei dem markierte Textabschnitte nicht sichtbar waren, wenn im Lesemodus das Design „Dunkler Modus“ verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-203">We fixed an issue where some select text was not visible when using darkmode theme in reading mode.</span></span>


- <span data-ttu-id="a2bb8-204">Es wurde ein Problem behoben, das dazu führen konnte, dass Word beim Herunterfahren unerwartet geschlossen wurde, weil der Benutzer sich abmeldete oder seinen Computer neu startete.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-204">Fixed an issue that may cause Word to unexpectedly close when shutting down due to the user logging off or restarting their computer.</span></span>


- <span data-ttu-id="a2bb8-205">Es wurde ein Problem behoben mit der Aktualisierung des Texts im AutoSpeichern-Popup für lokal gespeicherte Dateien.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-205">We fixed an issue that updates text on autosave callout for files saved locally.</span></span>


- <span data-ttu-id="a2bb8-206">Es wurde ein Problem behoben, bei dem ein Rollback der Hauptversion zu einem unerwarteten Schließen beim Öffnen von Dateien führen konnte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-206">Fixed an issue where a major version build rollback could result in an unexpected close on file open.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a2bb8-207">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a2bb8-207">Office Suite</span></span>

- <span data-ttu-id="a2bb8-208">Es wurde ein Problem wurde behoben, durch das das Öffnen eines Cloud-Dokuments fehlschlug.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-208">Fixed an issue that would cause cloud document to fail to open.</span></span>


- <span data-ttu-id="a2bb8-209">Diese Änderung analysiert das neue Attribut "TenantId", das in Cobalt-Antworten gesendet wird, und speichert es in der zentralen Tabelle.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-209">This change parses the new TenantId attribute sent on Cobalt responses and stores it in the Central Table.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2103-june-08"></a><span data-ttu-id="a2bb8-211">Version 2103: 08. Juni</span><span class="sxs-lookup"><span data-stu-id="a2bb8-211">Version 2103: June 08</span></span>
<span data-ttu-id="a2bb8-212">*Version 2103 (Build 13901.20554)*</span><span class="sxs-lookup"><span data-stu-id="a2bb8-212">*Version 2103 (Build 13901.20554)*</span></span>

<span data-ttu-id="a2bb8-213">Sicherheitsupdates sind [hier](microsoft365-apps-security-updates.md) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="a2bb8-213">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a2bb8-215">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a2bb8-215">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a2bb8-216">Excel</span><span class="sxs-lookup"><span data-stu-id="a2bb8-216">Excel</span></span>

- <span data-ttu-id="a2bb8-217">Es wurde ein Problem behoben, bei dem für einige Benutzer zusätzliche Einträge in der Excel-Add-In-Liste angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-217">Fixed an issue where extra entries appeared in the Excel Add-in list for some users.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a2bb8-218">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a2bb8-218">Office Suite</span></span>

- <span data-ttu-id="a2bb8-219">Behebung eines Problems, das im Falle eines Rollbacks zu einem vorherigen Build bei Word, PowerPoint und Excel dazu führen konnte, dass das Öffnen eines Cloud-Dokuments fehlschlug.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-219">Fix an issue Word, Powerpoint and Excel would fail to open cloud document if rolling back to a previous build</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2103-may-11"></a><span data-ttu-id="a2bb8-221">Version 2103: 11. Mai</span><span class="sxs-lookup"><span data-stu-id="a2bb8-221">Version 2103: May 11</span></span>
<span data-ttu-id="a2bb8-222">*Version 2103 (Build 13901.20516)*</span><span class="sxs-lookup"><span data-stu-id="a2bb8-222">*Version 2103 (Build 13901.20516)*</span></span>

<span data-ttu-id="a2bb8-223">Sicherheitsupdates sind [hier](microsoft365-apps-security-updates.md) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="a2bb8-223">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a2bb8-225">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a2bb8-225">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a2bb8-226">Excel</span><span class="sxs-lookup"><span data-stu-id="a2bb8-226">Excel</span></span>

- <span data-ttu-id="a2bb8-227">**Automatisch neue Datentypen verwenden:** Wenn Sie einen Datenwert eingeben, der einem möglichen Aktienelement oder geografischen Speicherort ähnelt, bietet Excel an, diesen in den geeigneten verbundenen Datentyp zu konvertieren – Aktien oder Geografie.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-227">**Automatically use new data types:** When you type a data value that resembles a stock or a geographic location, Excel offers to convert it to the right connected data type - Stocks or Geography.</span></span> [<span data-ttu-id="a2bb8-228">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-228">Learn more</span></span>](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- <span data-ttu-id="a2bb8-229">**Verknüpfte Datentypen: Echte Daten für das echte Leben:** Neue verknüpfte Datentypen liefern Ihnen Fakten und Daten zu Hunderten von Themen, die Ihnen helfen, Ihre Ziele direkt in Excel zu erreichen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-229">**Linked data types: Real data for real life:** New linked data types bring you facts and data on hundreds of subjects to help you accomplish your goals right in Excel.</span></span>

### <a name="outlook"></a><span data-ttu-id="a2bb8-230">Outlook</span><span class="sxs-lookup"><span data-stu-id="a2bb8-230">Outlook</span></span>

- <span data-ttu-id="a2bb8-231">**Aufheben der Sprachbarriere durch einen integrierten Übersetzer:** Ab jetzt sind keine Add-Ins für die Übersetzung mehr erforderlich!</span><span class="sxs-lookup"><span data-stu-id="a2bb8-231">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="a2bb8-232">Sie können jetzt den Intelligenten Übersetzer in Outlook verwenden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-232">You can now use the Intelligent Translator in Outlook.</span></span> <span data-ttu-id="a2bb8-233">Wenn Sie eine Nachricht in einer anderen Sprache erhalten, wird am oberen Rand der Nachricht eine Eingabeaufforderung angezeigt, die Ihnen anbietet, die Nachricht durch Outlook in Ihre Standardsprache zu übersetzen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-233">When you receive a message in another language, a prompt will appear on top of the message asking if you’d like Outlook to translate it to your default language.</span></span>
<span data-ttu-id="a2bb8-234">Sie können auch mit der rechten Maustaste klicken, um bestimmte Wörter, Ausdrücke oder die gesamte Nachricht zu übersetzen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-234">You can also right-click to translate specific words, phrases, or the whole message.</span></span> [<span data-ttu-id="a2bb8-235">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-235">Learn more</span></span>](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

### <a name="visio"></a><span data-ttu-id="a2bb8-236">Visio</span><span class="sxs-lookup"><span data-stu-id="a2bb8-236">Visio</span></span>

- <span data-ttu-id="a2bb8-237">**Fertige Grafiken für Ihre Diagramme:** Wählen Sie aus einer großen Bibliothek von Symbolen, Stockbildern, ausgeschnittenen Personen und Aufklebern, die Sie zu Ihren Visio-Zeichnungen hinzufügen können.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-237">**Ready-made graphics for your diagrams:** Choose from a large library of icons, stock photo images, cutout people, and stickers that you can add to your Visio drawings.</span></span> [<span data-ttu-id="a2bb8-238">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-238">Learn more</span></span>](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)<br /><span data-ttu-id="a2bb8-239">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/access-illustrations-icons-in-visio)</span><span class="sxs-lookup"><span data-stu-id="a2bb8-239">See details in [blog post](https://insider.office.com/de-DE/blog/access-illustrations-icons-in-visio)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a2bb8-242">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a2bb8-242">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a2bb8-243">Zugriff</span><span class="sxs-lookup"><span data-stu-id="a2bb8-243">Access</span></span>

- <span data-ttu-id="a2bb8-244">Ein Problem wurde behoben, das, wenn eine externe Anwendung eine Benutzeroberfläche zur Barrierefreiheit anfordert, uns daran hindert, herunterzufahren, bis sie ihre Referenz freigibt.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-244">We fixed an issue when an external application requests an accessibility interface, it will prevent us from shutting down until they release their reference.</span></span>


- <span data-ttu-id="a2bb8-245">Diese Änderung behebt ein Problem, bei dem in einigen Fällen das Ausführen einer SQL Server-Pass-Through-Abfrage zu einer Fehlermeldung führen kann, die darauf hinweist, dass ein "ungültiger Cursorstatus" vorliegt.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-245">This change fixes an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>


### <a name="excel"></a><span data-ttu-id="a2bb8-246">Excel</span><span class="sxs-lookup"><span data-stu-id="a2bb8-246">Excel</span></span>

- <span data-ttu-id="a2bb8-247">Es wurde ein Problem behoben, das dazu führte, dass die Datumsformatierung bei der Verwendung von Add-Ins in einigen Sprachen nicht korrekt angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-247">We fixed an issue that caused date formatting to be displayed incorrectly in some languages when using add-ins.</span></span>


- <span data-ttu-id="a2bb8-248">Es wurde ein Problem behoben, bei dem das Add-In „Analyse-Funktionen“ für einige Benutzer nicht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-248">Fixed an issue where the Analysis ToolPak add-in did not work for some users.</span></span>


- <span data-ttu-id="a2bb8-249">Es wurde ein potenzielles Hängen in Word beim Zeichnen eines Bilds behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-249">Fixed a potential hang in Word when drawing an image.</span></span>


### <a name="outlook"></a><span data-ttu-id="a2bb8-250">Outlook</span><span class="sxs-lookup"><span data-stu-id="a2bb8-250">Outlook</span></span>

- <span data-ttu-id="a2bb8-251">Wir haben ein Problem behoben, durch das die Namensauflösung fehlschlug, sobald etwas im Namen eines anderen Benutzers gesendet wurde und das mit einem Adressbuch verglichen wurde, das nicht der globalen Adressliste entsprach.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-251">We fixed an issue that caused name resolution to fail when sending on behalf of another user and resolving against an address book that is not the Global Address List.</span></span>


- <span data-ttu-id="a2bb8-252">Es wurde ein Problem behoben, durch das Outlook die in OWA konfigurierten Einstellungen für den Posteingang mit Relevanz außer Kraft gesetzt hat.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-252">We fixed an issue that caused Outlook to override the Focused Inbox preferences configured in OWA.</span></span>


- <span data-ttu-id="a2bb8-253">Wir haben ein Problem behoben, das dazu führte, dass einige Personen nicht auf Signaturen zugreifen konnten, die mit sekundären E-Mail-Konten verbunden waren.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-253">We fixed an issue that caused some people to be unable to access signatures associated with secondary mail accounts.</span></span>


- <span data-ttu-id="a2bb8-254">Es wurde ein Problem behoben, durch das Benutzern mehr Signaturen als erwartet angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-254">We fixed an issue that caused users to see more signatures than expected.</span></span>


- <span data-ttu-id="a2bb8-255">Wir haben ein Problem behoben, durch das bei einigen Benutzern die Plätze des primären und sekundären Kalenders im Navigationsbereich vertauscht waren.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-255">We fixed an issue that caused some users to see their primary and secondary calendar switching places in the Navigation Pane.</span></span>


- <span data-ttu-id="a2bb8-256">Ein Problem wurde behoben, das dazu führte, dass Benutzern beim Hinzufügen eines Kalenders fälschlicherweise die Meldung „Dies kann eine Weile dauern“ angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-256">We fixed an issue that cause users to erroneously see a "This may take a while" message when adding a calendar.</span></span>


- <span data-ttu-id="a2bb8-257">Ein Problem wurde behoben, das dazu führte, dass Stellvertretungen als Organisator von Besprechungen angezeigt wurden, die in neu hinzugefügten Kalendern erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-257">We fixed an issue that caused delegates to appear as the organizer of meetings created on newly added calendars.</span></span>  <span data-ttu-id="a2bb8-258">Besprechungen in diesem Zustand wurden im Kalender des Prinzipals nicht angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-258">Meetings in this state did not appear on the principal's calendar.</span></span>


- <span data-ttu-id="a2bb8-259">Wir haben ein Problem in einer Komponente von Outlook behoben, die von MAPI-fähigen Anwendungen auf Computern mit ARM-Prozessoren verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-259">We fixed an issue in a component of Outlook that is used by MAPI-enabled applications on computers with ARM processors.</span></span> <span data-ttu-id="a2bb8-260">Das Problem führte dazu, dass die Suche fehlschlug oder der Computer zusätzlich belastet wurde, da Hintergrund-Apps wiederholt neu gestartet wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-260">The issue could cause search to fail or cause extra load on the computer as background apps restarted repeatedly.</span></span>


- <span data-ttu-id="a2bb8-261">Wir haben ein Problem behoben, durch das Outlook bei einigen Benutzern beim Synchronisieren von Änderungen der Ordnerhierarchie unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-261">We fixed an issue that caused some users to experience Outlook to close unexpectedly when syncing folder hierarchy changes.</span></span>


- <span data-ttu-id="a2bb8-262">Es wurde ein potenzielles Hängen in Word beim Zeichnen eines Bilds behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-262">Fixed a potential hang in Word when drawing an image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a2bb8-263">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a2bb8-263">PowerPoint</span></span>

- <span data-ttu-id="a2bb8-264">Es wurde ein Problem mit verknüpften Bildern behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-264">We fixed an issue related to linked pictures.</span></span>


- <span data-ttu-id="a2bb8-265">Es wurde ein potenzielles Hängen in Word beim Zeichnen eines Bilds behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-265">Fixed a potential hang in Word when drawing an image.</span></span>


### <a name="project"></a><span data-ttu-id="a2bb8-266">Project</span><span class="sxs-lookup"><span data-stu-id="a2bb8-266">Project</span></span>

- <span data-ttu-id="a2bb8-267">Ein Problem wurde behoben, bei dem Visio während des Schließens manchmal nicht mehr funktionierte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-267">Fixed an issue where Visio could stop working during close.</span></span>


### <a name="visio"></a><span data-ttu-id="a2bb8-268">Visio</span><span class="sxs-lookup"><span data-stu-id="a2bb8-268">Visio</span></span>

- <span data-ttu-id="a2bb8-269">Ein Problem wurde behoben, bei dem Visio während des Schließens manchmal nicht mehr funktionierte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-269">Fixed an issue where Visio could stop working during close.</span></span>


### <a name="word"></a><span data-ttu-id="a2bb8-270">Word</span><span class="sxs-lookup"><span data-stu-id="a2bb8-270">Word</span></span>

- <span data-ttu-id="a2bb8-271">Es wurde ein Problem behoben, durch das Bedingungen für angebotene Textvorhersagen optimiert werden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-271">Fixed an issue to optimizes conditions for text predictions to be offered.</span></span>


- <span data-ttu-id="a2bb8-272">Es wurde ein Problem mit der Aktualisierung des Texts im AutoSpeichern-Popup für lokal gespeicherte Dateien behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-272">Fixed an issue where updates text on autosave callout for files saved locally.</span></span>


- <span data-ttu-id="a2bb8-273">Es wurde ein Problem behoben, bei dem bei der gemeinsamen Dokumentenerstellung der aktive Entwurf nicht gelöscht wurde, wenn sich die Kommentarreihenfolge änderte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-273">Fixed an issue when coauthoring a document, active draft is not cleared when comment order changes.</span></span>


- <span data-ttu-id="a2bb8-274">Behebt ein Problem, bei dem die Seitenansicht unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-274">Fixes an issue where Print preview closed unexpectedly.</span></span>


- <span data-ttu-id="a2bb8-275">Es wurde ein potenzielles Hängen in Word beim Zeichnen eines Bilds behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-275">Fixed a potential hang in Word when drawing an image.</span></span>



### <a name="office-suite"></a><span data-ttu-id="a2bb8-276">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a2bb8-276">Office Suite</span></span>

- <span data-ttu-id="a2bb8-277">Behebt ein Problem mit der Zuverlässigkeit im Zusammenhang mit der Unterstützung von Office-Apps, die in Sitzung 0 ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-277">Fixes a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="a2bb8-278">Es wurde ein Fehler behoben, bei dem die Funktion „Umbenennen“ nicht reagierte, wenn eine SyncBacked-Datei offline geöffnet und dann in der App umbenannt wurde, bevor sie gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-278">Fixed an issue which rename was unresponsive when opened a SyncBacked file offline then renamed the file in app before saving file.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2102-may-11"></a><span data-ttu-id="a2bb8-280">Version 2102: 11. Mai</span><span class="sxs-lookup"><span data-stu-id="a2bb8-280">Version 2102: May 11</span></span>
<span data-ttu-id="a2bb8-281">*Version 2102 (Build 13801.20638)*</span><span class="sxs-lookup"><span data-stu-id="a2bb8-281">*Version 2102 (Build 13801.20638)*</span></span>

<span data-ttu-id="a2bb8-282">Sicherheitsupdates sind [hier](microsoft365-apps-security-updates.md) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="a2bb8-282">Security updates listed [here](microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a2bb8-284">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a2bb8-284">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a2bb8-285">Excel</span><span class="sxs-lookup"><span data-stu-id="a2bb8-285">Excel</span></span>

- <span data-ttu-id="a2bb8-286">Es wurde ein Problem behoben, das dazu führte, dass die Datumsformatierung bei der Verwendung von Add-Ins in einigen Sprachen nicht korrekt angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-286">We fixed an issue that caused date formatting to be displayed incorrectly on some languages when using Add-ins.</span></span>


- <span data-ttu-id="a2bb8-287">Es wurde ein Problem behoben, das das Einfügen als Formeln in ein geschütztes Blatt verhinderte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-287">We fixed an issue that was preventing the ability to paste as formulas on a protected sheet.</span></span>


### <a name="outlook"></a><span data-ttu-id="a2bb8-288">Outlook</span><span class="sxs-lookup"><span data-stu-id="a2bb8-288">Outlook</span></span>

- <span data-ttu-id="a2bb8-289">Auf diese Weise können Endbenutzer Outlook so konfigurieren, dass jeder von ihnen erstellten Besprechung eine Onlinebesprechung hinzugefügt wird.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-289">This enables end users to configure Outlook to add an online meeting to every meeting they create.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a2bb8-290">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a2bb8-290">PowerPoint</span></span>

- <span data-ttu-id="a2bb8-291">Es wurde ein Problem mit verknüpften Bildern behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-291">We fixed an issue related to linked pictures.</span></span>


### <a name="word"></a><span data-ttu-id="a2bb8-292">Word</span><span class="sxs-lookup"><span data-stu-id="a2bb8-292">Word</span></span>

- <span data-ttu-id="a2bb8-293">Behebt ein Problem in Wordmail, bei dem ein Benutzer dieses Element nicht senden kann, wenn das 2084. Zeichen in einem Link ein Escapezeichen ist.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-293">Fixes an issue in Wordmail where someone cannot send this item' when the 2084th character in a link is an escaped character.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a2bb8-294">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a2bb8-294">Office Suite</span></span>

- <span data-ttu-id="a2bb8-295">Ein Problem wurde behoben, durch das Word beim Drucken langer Dokumente unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-295">Fixed an issue that caused Word to close unexpectedly while printing long documents.</span></span>


- <span data-ttu-id="a2bb8-296">Vor dieser Änderung wurden Office-Vorlagen auch dann angezeigt, wenn das Gruppenrichtlinienobjekt, das sie deaktiviert, aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-296">Before this change, Office templates were displaying even if GPO for disabling them was turned on.</span></span> <span data-ttu-id="a2bb8-297">Mit dieser Änderung werden Vorlagen jetzt das Gruppenrichtlinienobjekt richtig verwenden und wie gewünscht angezeigt/ausgeblendet.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-297">With this change, templates now honor the GPO correctly and display/hide as requested.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2102-april-13"></a><span data-ttu-id="a2bb8-299">Version 2102: 13. April</span><span class="sxs-lookup"><span data-stu-id="a2bb8-299">Version 2102: April 13</span></span>
<span data-ttu-id="a2bb8-300">*Version 2102 (Build 13801.20506)*</span><span class="sxs-lookup"><span data-stu-id="a2bb8-300">*Version 2102 (Build 13801.20506)*</span></span>

<span data-ttu-id="a2bb8-301">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="a2bb8-301">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a2bb8-303">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a2bb8-303">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a2bb8-304">Excel</span><span class="sxs-lookup"><span data-stu-id="a2bb8-304">Excel</span></span>

- <span data-ttu-id="a2bb8-305">**Verwenden des Dialogfelds "Erweitert" zum Erstellen von Datentypen:** Im Dialogfeld "Erweitert" können Sie manuell die Spalten auswählen, die den von Ihnen erstellten Datentyp kombinieren.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-305">**Use the Advanced Dialog to Create Data Types:** The Advanced Dialog allows you to manually select the columns which combine the Data Type you are creating.</span></span>

- <span data-ttu-id="a2bb8-306">**Blenden Sie viele Blätter gleichzeitig ein:** Sie müssen nicht mehr ein Blatt nach dem anderen einblenden – Sie können mehrere ausgeblendete Blätter gleichzeitig einblenden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-306">**Unhide many sheets at the same time:** No need to unhide one sheet at a time anymore -- unhide multiple hidden sheets at once.</span></span> [<span data-ttu-id="a2bb8-307">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-307">Learn more</span></span>](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)


### <a name="outlook"></a><span data-ttu-id="a2bb8-308">Outlook</span><span class="sxs-lookup"><span data-stu-id="a2bb8-308">Outlook</span></span>

- <span data-ttu-id="a2bb8-309">**Die Einstellungen für den Posteingang mit Relevanz bleiben auf allen Geräten identisch:** Ihre Einstellungen für den Posteingang mit Relevanz sind jetzt in der Cloud gespeichert.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-309">**Focused Inbox settings remain the same across devices:** Your Focused Inbox preferences are now stored in the cloud.</span></span> <span data-ttu-id="a2bb8-310">Nutzen Sie auf einem beliebigen Windows-Computer und in Outlook im Web dieselbe Oberfläche.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-310">Enjoy the same experience when you use Outlook for Windows on any computer and Outlook on the web.</span></span> [<span data-ttu-id="a2bb8-311">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-311">Learn more</span></span>](https://support.office.com/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- <span data-ttu-id="a2bb8-312">**Ihre Outlook-Einstellungen in der Cloud:** Wählen Sie Ihre Outlook für Windows-Einstellungen aus, z. B. Automatische Antworten, Posteingang mit Relevanz und Datenschutz, und greifen Sie auf jedem beliebigen PC darauf zu.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-312">**Your Outlook settings in the cloud:** Choose your Outlook for Windows settings like Automatic Replies, Focused Inbox, and Privacy, and get to them on any PC.</span></span>

- <span data-ttu-id="a2bb8-313">**Auswählen, wo gesucht werden soll:** Das neue Dropdownmenü für den Suchbereich ermöglicht es Ihnen, Ihre Suche einfacher zu ändern und zwischen dem aktuellen Ordner und dem aktuellen Postfach zu wechseln.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-313">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="a2bb8-314">Vielen Dank an alle in "Demnächst verfügbar", die uns ihr Feedback zu der neuen Search-at-Top-Erfahrung gesendet haben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-314">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="a2bb8-315">Das vorliegende Design und Update sind aus diesem Feedback entstanden!</span><span class="sxs-lookup"><span data-stu-id="a2bb8-315">This design and update came out of that feedback!</span></span>

- <span data-ttu-id="a2bb8-316">**Verfassen Sie Nachrichten mit Ihrer Stimme:** Verwenden Sie die neue Diktatsymbolleiste, neue Sprachbefehle, automatische Zeichensetzung und mehr, um Nachrichten zu verfassen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-316">**Draft messages with your voice:** Use the new dictation toolbar, voice commands, auto-punctuation, and more to compose messages.</span></span>

### <a name="word"></a><span data-ttu-id="a2bb8-317">Word</span><span class="sxs-lookup"><span data-stu-id="a2bb8-317">Word</span></span>

- <span data-ttu-id="a2bb8-318">**Verfassen Sie Dokumente mit Ihrer Stimme:** Verwenden Sie die neue Diktatsymbolleiste, neue Sprachbefehle und automatische Zeichensetzung, um Dokumente zu verfassen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-318">**Draft documents with your voice:** Use the new dictation toolbar, voice commands and auto-punctuation to draft documents.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a2bb8-321">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a2bb8-321">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="a2bb8-322">Access</span><span class="sxs-lookup"><span data-stu-id="a2bb8-322">Access</span></span>

- <span data-ttu-id="a2bb8-323">Es wurde ein Problem behoben, bei dem in einigen Fällen das Ausführen einer SQL Server-Pass-Through-Abfrage zu einer Fehlermeldung führte, die auf einen "ungültigen Cursorstatus" hinwies.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-323">Fixed an issue where in some cases running a SQL Server pass through query could result in an error message indicating that there was an "invalid cursor state".</span></span>



### <a name="excel"></a><span data-ttu-id="a2bb8-324">Excel</span><span class="sxs-lookup"><span data-stu-id="a2bb8-324">Excel</span></span>

- <span data-ttu-id="a2bb8-325">Es wurde ein Fehler behoben, durch den die Datenüberprüfung u. U. unerwartet auf Zellen angewendet wurde, nachdem Zeilen zu einer Tabelle auf einem anderen Blatt hinzugefügt wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-325">We fixed a bug in which data validation could be applied to cells unexpectedly after adding rows to a table on another sheet.</span></span>


- <span data-ttu-id="a2bb8-326">Ein Problem wurde behoben, durch das die Anzeigfunktion von DialogSheets in 32-Bit-Versionen von Excel nicht funktionierte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-326">We fixed an issue where the DialogSheets show function was not working on 32 bit versions of Excel</span></span>


- <span data-ttu-id="a2bb8-327">Ein Problem wurde behoben, das dazu führte, dass Bilder bei Verwendung der Option „Verknüpftes Bild einfügen“ kleiner als erwartet waren.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-327">We fixed an issue which caused images to be smaller than expected when using the Paste Linked Picture option.</span></span>


- <span data-ttu-id="a2bb8-328">Es wurde ein Fehler behoben, bei dem einige PivotTable-Formatierungen die Arbeitsmappe beschädigten, wenn diese im XLS- oder XLT-Format gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-328">We fixed an issue that caused some PivotTable formatting to corrupt the workbook when saving to the .xls or .xlt format.</span></span>


- <span data-ttu-id="a2bb8-329">Es wurde ein Problem behoben, das Benutzer am Exportieren von Excel-Arbeitsmappen in eine PDF-Datei hinderte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-329">We fixed an issue that prevented users from exporting an Excel workbook to PDF.</span></span>


- <span data-ttu-id="a2bb8-330">Es wurde ein Problem behoben, durch das bei deaktivierten Befehlen im Office-Menüband nur das Symbol, nicht aber der Text im Office-Design "Dunkelgrau" abgeblendet wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-330">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="outlook"></a><span data-ttu-id="a2bb8-331">Outlook</span><span class="sxs-lookup"><span data-stu-id="a2bb8-331">Outlook</span></span>

- <span data-ttu-id="a2bb8-332">Ein Problem wurde behoben, das dazu führte, dass Benutzer der Inlineübersetzung kein Feedback abgeben konnten.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-332">We fixed an issue that caused users of inline translation to be unable to submit feedback.</span></span>


- <span data-ttu-id="a2bb8-333">Ein Problem wurde behoben, das dazu führte, dass Benutzersignaturen mit Unicode-Inhalten beschädigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-333">We fixed an issue that caused users to see signatures containing unicode content to get damaged.</span></span>


- <span data-ttu-id="a2bb8-334">Es wurde ein Problem behoben, durch das Benutzern mehr Signaturen als erwartet angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-334">We fixed an issue that caused users to see more signatures than expected.</span></span>


- <span data-ttu-id="a2bb8-335">Es wurde ein Problem behoben, durch das Outlook im Leerlauf abstürzte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-335">We fixed an issue that caused Outlook to crash when idle.</span></span>


- <span data-ttu-id="a2bb8-336">Ein Problem wurde behoben, das dazu führte, dass die App bei einigen Benutzern beim Schließen von Nachrichtenfenstern heruntergefahren wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-336">We fixed an issue that  caused some users to experience the app to shut down when closing message windows.</span></span>


- <span data-ttu-id="a2bb8-337">Ein Problem wurde behoben, das dazu führte, dass Benutzer der Verbesserungen des geteilten Kalenders die Farbe eines Kalenders nicht auf gelb oder braun setzen konnten.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-337">We fixed an issue that caused users of the Shared Calendar improvements to be unable to set a calendar's color to yellow or brown.</span></span>


- <span data-ttu-id="a2bb8-338">Ein Problem wurde behoben, das dazu führte, dass Benutzern nach dem Erstellen einer neuen Gruppe doppelte Kalendergruppen angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-338">We fixed and issue that caused users to see duplicate calendar groups appearing after creating a new group.</span></span>


- <span data-ttu-id="a2bb8-339">Wir haben ein Problem behoben, das dazu führte, dass neu hinzugefügte Kalender den Benutzern erst nach einem Neustart von Outlook im Navigationsbereich angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-339">We fixed an issue that caused users to see newly added calendars fail to appear in the navigation pane until after Outlook had been restarted.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a2bb8-340">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a2bb8-340">PowerPoint</span></span>

- <span data-ttu-id="a2bb8-341">Es wurde ein Problem behoben, durch das bei deaktivierten Befehlen im Office-Menüband nur das Symbol, nicht aber der Text im Office-Design "Dunkelgrau" abgeblendet wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-341">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="word"></a><span data-ttu-id="a2bb8-342">Word</span><span class="sxs-lookup"><span data-stu-id="a2bb8-342">Word</span></span>

- <span data-ttu-id="a2bb8-343">Es wurde ein Problem mit dem Auflösen von Konflikten bei der gemeinsamen Dokumenterstellung gelöst.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-343">We fixed an issue in resolving conflicts while in coauthoring.</span></span>


- <span data-ttu-id="a2bb8-344">Wir haben ein Problem mit Rich-Text-Inhaltssteuerelementen behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-344">We fixed an issue with Rich text content controls.</span></span>


- <span data-ttu-id="a2bb8-345">Wir haben ein Problem behoben, bei dem die Eingabe am Ende eines ausgeblendeten Absatzes dazu führen konnte, dass die Anwendung nicht mehr reagierte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-345">We fixed an issue with typing at the end of a hidden paragraph may result in application hang.</span></span>


- <span data-ttu-id="a2bb8-346">Wir haben ein Problem mit der Sprachausgabe behoben, bei dem ein Absatz u. U. übersprungen wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-346">We fixed an issue with Narrator which may skips over a paragraph.</span></span>


- <span data-ttu-id="a2bb8-347">Es wurde ein Problem beim Kopieren und Einfügen behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-347">We fixed an issue relating to copy and paste.</span></span>


- <span data-ttu-id="a2bb8-348">Behebt ein Problem mit Farben, die auf Symbole und SVG-Grafiken mit 3D-Effekten angewendet wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-348">Fixes an issue with colors applied to icons and SVG graphics with 3D effects.</span></span>


- <span data-ttu-id="a2bb8-349">Es wurde ein Problem behoben, durch das bei deaktivierten Befehlen im Office-Menüband nur das Symbol, nicht aber der Text im Office-Design "Dunkelgrau" abgeblendet wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-349">Fixed an issue where disabled commands in the Office Ribbon would only have the icon grayed out but not the text in Dark Gray Office Theme.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a2bb8-350">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a2bb8-350">Office Suite</span></span>

- <span data-ttu-id="a2bb8-351">Wir haben ein Zuverlässigkeitsproblem im Zusammenhang mit der Unterstützung von Office-Apps behoben, die in Sitzung 0 ausgeführt wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-351">We fixed a reliability issue related to support of Office apps running in session 0.</span></span>


- <span data-ttu-id="a2bb8-352">Es wurde ein Problem behoben, das in Outlook manchmal dazu führen konnte, dass Text transparent dargestellt wurde, und dadurch nicht lesbar war.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-352">Fixed an issue that could sometimes lead to text in Outlook becoming transparent and thereby not legible.</span></span>


- <span data-ttu-id="a2bb8-353">Ein Problem, das bei Verwendung der Sprachausgabe in Text mit mathematischen Formeln auftrat, wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-353">Fixed an issue that could happen when using narrator within text that contains math equations.</span></span>


- <span data-ttu-id="a2bb8-354">Es wurde ein Problem behoben, bei dem das Diktat für GCC-Benutzer deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-354">Fixed an issue where Dictation was disabled for GCC users</span></span>


- <span data-ttu-id="a2bb8-355">Es wurde ein Problem behoben, durch das Benutzer beim Öffnen einer zuvor geöffneten Datei mit nicht gespeicherten Änderungen keine Datei speichern konnten, die Datei jedoch gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-355">Fixed an issue where users are unable to save file when open a previously opened file with edits not saved but now the file has been deleted.</span></span> <span data-ttu-id="a2bb8-356">Nach der Problembehebung erhalten Benutzer eine freundliche Nachricht, in der sie darüber informiert werden, dass die Datei gelöscht wurde. Dieser Benutzer kann wählen, ob Änderungen verworfen oder die Datei gespeichert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-356">After the fix, users will get a friendly message to inform them that the file is deleted, thus user can choose to discard changes, or SaveAs the file.</span></span>


- <span data-ttu-id="a2bb8-357">Es wurde ein Fehler behoben, der auftrat, wenn eine SyncBacked-Datei offline geöffnet und dann in der App umbenannt wurde, bevor sie gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-357">Fixed rename failure issue when open a SyncBacked file offline then rename the file in app before saving file.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2101-april-13"></a><span data-ttu-id="a2bb8-359">Version 2101: 13. April</span><span class="sxs-lookup"><span data-stu-id="a2bb8-359">Version 2101: April 13</span></span>
<span data-ttu-id="a2bb8-360">*Version 2101 (Build 13628.20664)*</span><span class="sxs-lookup"><span data-stu-id="a2bb8-360">*Version 2101 (Build 13628.20664)*</span></span>

<span data-ttu-id="a2bb8-361">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="a2bb8-361">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2101-march-09"></a><span data-ttu-id="a2bb8-362">Version 2101: 09. März</span><span class="sxs-lookup"><span data-stu-id="a2bb8-362">Version 2101: March 09</span></span>
<span data-ttu-id="a2bb8-363">*Version 2101 (Build 13628.20528)*</span><span class="sxs-lookup"><span data-stu-id="a2bb8-363">*Version 2101 (Build 13628.20528)*</span></span>

<span data-ttu-id="a2bb8-364">Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="a2bb8-364">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a2bb8-366">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a2bb8-366">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a2bb8-367">Excel</span><span class="sxs-lookup"><span data-stu-id="a2bb8-367">Excel</span></span>

- <span data-ttu-id="a2bb8-368">Ein Problem wurde behoben, bei dem Excel nicht gestartet werden konnte bzw. unerwartet geschlossen wurde, wenn bestimmte Einstellungen für den Schutz vor Windows-Sicherheit-Exploits (SimExec, CallerCheck) verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-368">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


### <a name="outlook"></a><span data-ttu-id="a2bb8-369">Outlook</span><span class="sxs-lookup"><span data-stu-id="a2bb8-369">Outlook</span></span>

- <span data-ttu-id="a2bb8-370">Ein Problem wurde behoben, das dazu geführt har, dass das Verschlüsselungssymbol bei E-Mails, die mit der Option „Nur mit Verschlüsselung“ gesendet wurden, nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-370">We fixed an issue that caused the encryption icon to fail to display on emails sent using the encryption only option.</span></span>


- <span data-ttu-id="a2bb8-371">Ein Problem wurde behoben, bei dem E-Mails als digital signiert versendet wurden, obwohl der Benutzer die Option deaktiviert hatte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-371">We fixed an issue that caused mails to be sent as digitally signed after the user unchecked that option.</span></span>


- <span data-ttu-id="a2bb8-372">Ein Problem wurde behoben, das die Anzeige der richtigen Standardsignatur im OWA beeinträchtigt hat.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-372">We fixed an issue that caused issues with displaying the correct default signature in OWA.</span></span>


- <span data-ttu-id="a2bb8-373">Es wurde ein Problem behoben, das dazu führte, dass das System hängenblieb, wenn Benutzer die Einstellungen unter „Cloudeinstellungen" aktualisierten.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-373">We fixed an issue that caused Cloud Settings users to experience a hang when updating settings.</span></span>


- <span data-ttu-id="a2bb8-374">Ein Problem wurde behoben, das dazu führte, dass die App manchmal unerwartet geschlossen wurde, wenn Benutzer Suchvorgänge in Outlook ausführten.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-374">We fixed an issue that caused the app to sometimes close unexpectedly when users were searching in Outlook.</span></span>


- <span data-ttu-id="a2bb8-375">Es wurde ein Problem behoben, das bei Benutzern mit freigegebenen oder delegierten Postfächern mit großen Hierarchien in ihrem Profil zu Blockaden führte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-375">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


- <span data-ttu-id="a2bb8-376">Wir haben ein Problem behoben, das bei einigen Benutzern dazu führte, dass Outlook in bestimmten Suchszenarien unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-376">We fixed an issue that caused some users to experience Outlook to close unexpectedly in certain search scenarios.</span></span>


### <a name="project"></a><span data-ttu-id="a2bb8-377">Project</span><span class="sxs-lookup"><span data-stu-id="a2bb8-377">Project</span></span>

- <span data-ttu-id="a2bb8-378">Ein Problem wurde behoben, bei dem die geplanten Kosten nicht korrekt hochgerechnet wurden, wenn eine Kostenressource einem Meilensteinvorgang zugewiesen wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-378">Fixed an issue where when a cost resource was assigned to a milestone task, baseline cost didn't rollup correctly.</span></span>


- <span data-ttu-id="a2bb8-379">Ein Problem wurde behoben, bei dem keine Rahmen für Vorgänge in der Teamplaneransicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-379">Fixed an issue where borders weren't showing up for tasks in the Team Planner view.</span></span>


- <span data-ttu-id="a2bb8-380">Ein Problem wurde behoben, bei dem Drag & Drop für Aufgaben in der Teamplaneransicht nicht funktioniert hat.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-380">Fixed an issue where you drag and drop wasn't working for tasks in the Team Planner view.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a2bb8-381">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a2bb8-381">Office Suite</span></span>

- <span data-ttu-id="a2bb8-382">Ein Problem im Zusammenhang mit Ereignisbenachrichtigungen für Mediencontroller wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-382">Fixes an issue related to media controller event notifications.</span></span>


- <span data-ttu-id="a2bb8-383">Ein Problem im Zusammenhang mit dem Timing des Media Player-Moduls wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-383">Fixes an issue related to media player engine timing.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2012-march-09"></a><span data-ttu-id="a2bb8-385">Version 2012: 09. März</span><span class="sxs-lookup"><span data-stu-id="a2bb8-385">Version 2012: March 09</span></span>
<span data-ttu-id="a2bb8-386">*Version 2012 (Build 13530.20628)*</span><span class="sxs-lookup"><span data-stu-id="a2bb8-386">*Version 2012 (Build 13530.20628)*</span></span>

<span data-ttu-id="a2bb8-387">Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="a2bb8-387">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a2bb8-389">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a2bb8-389">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a2bb8-390">Excel</span><span class="sxs-lookup"><span data-stu-id="a2bb8-390">Excel</span></span>

- <span data-ttu-id="a2bb8-391">**Benutzer auffordern, Vertraulichkeitsbezeichnungen anzuwenden:** Benutzer werden aufgefordert, eine Vertraulichkeitsbezeichnung anzuwenden, wenn die Richtlinie ihrer Organisation dies erfordert.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-391">**Require users to apply sensitivity labels:** Users will be prompted to apply a sensitivity label if their organization's policy requires it.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a2bb8-392">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a2bb8-392">PowerPoint</span></span>

- <span data-ttu-id="a2bb8-393">**Benutzer auffordern, Vertraulichkeitsbezeichnungen anzuwenden:** Benutzer werden aufgefordert, eine Vertraulichkeitsbezeichnungen anzuwenden, wenn die Richtlinie ihrer Organisation dies erfordert.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-393">**Require users to apply sensitivity labels:** Users will be prompted to apply a sensitivity label if their organization's policy requires it.</span></span>

### <a name="word"></a><span data-ttu-id="a2bb8-394">Word</span><span class="sxs-lookup"><span data-stu-id="a2bb8-394">Word</span></span>

- <span data-ttu-id="a2bb8-395">**Benutzer auffordern, Vertraulichkeitsbezeichnungen anzuwenden:** Benutzer werden aufgefordert, eine Vertraulichkeitsbezeichnung anzuwenden, wenn die Richtlinie ihrer Organisation dies erfordert.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-395">**Require users to apply sensitivity labels:** Users will be prompted to apply a sensitivity label if their organization's policy requires it.</span></span>


## <a name="version-2012-february-09"></a><span data-ttu-id="a2bb8-396">Version 2012: 09. Februar</span><span class="sxs-lookup"><span data-stu-id="a2bb8-396">Version 2012: February 09</span></span>
<span data-ttu-id="a2bb8-397">*Version 2012 (Build 13530.20528)*</span><span class="sxs-lookup"><span data-stu-id="a2bb8-397">*Version 2012 (Build 13530.20528)*</span></span>

<span data-ttu-id="a2bb8-398">Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="a2bb8-398">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a2bb8-400">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a2bb8-400">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="a2bb8-401">Excel</span><span class="sxs-lookup"><span data-stu-id="a2bb8-401">Excel</span></span>

- <span data-ttu-id="a2bb8-402">**Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-402">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="a2bb8-403">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-403">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="a2bb8-404">**Überwachungsprotokollierung für Vertraulichkeitsbezeichnungen:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, werden diese Informationen jetzt den Administratoren in den Microsoft 365-Auditprotokollen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-404">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="a2bb8-405">**Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-405">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="a2bb8-406">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-406">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a><span data-ttu-id="a2bb8-407">Outlook</span><span class="sxs-lookup"><span data-stu-id="a2bb8-407">Outlook</span></span>

- <span data-ttu-id="a2bb8-408">**Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-408">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="a2bb8-409">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-409">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="a2bb8-410">**Einbauen einer Zeitspanne zwischen unmittelbar aufeinander folgenden Besprechungen**: Geben Sie den Teilnehmern Zeit für eine Atempause und oder den Weg zwischen verschiedenen Besprechungsorten, indem Sie festlegen, dass Besprechungen standardmäßig 5–10 Minuten verspätet beginnen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-410">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to start 5-10 min late by default.</span></span> [<span data-ttu-id="a2bb8-411">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-411">Learn more</span></span>](https://support.office.com/article/ebb4c4c9-6992-4ea7-9772-8b5883df8500)

- <span data-ttu-id="a2bb8-412">**Überwachungsprotokollierung für Vertraulichkeitsbezeichnungen:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, werden diese Informationen jetzt den Administratoren in den Microsoft 365-Auditprotokollen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-412">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="a2bb8-413">**Jede Besprechung online:** Aktualisieren Sie Ihre Kalendereinstellungen, um jede Besprechung, die Sie erstellen, standardmäßig zu einer Teams-Besprechung zu machen. So müssen Sie nicht mehr daran denken, auf die Option "Teams-Besprechung" zu klicken.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-413">**Every meeting online:** Update your calendar settings to make every meeting you create a Teams Meeting by default so you no longer need to remember to click the Teams Meeting option.</span></span>

- <span data-ttu-id="a2bb8-414">**Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-414">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="a2bb8-415">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-415">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

- <span data-ttu-id="a2bb8-416">**Jede Besprechung online:** Aktualisieren Sie Ihre Kalendereinstellungen, um jede Besprechung, die Sie erstellen, standardmäßig zu einer Teams-Besprechung zu machen. So müssen Sie nicht mehr daran denken, auf die Option "Teams-Besprechung" zu klicken.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-416">**Every meeting online:** Update your calendar settings to make every meeting you create a Teams Meeting by default so you no longer need to remember to click the Teams Meeting option.</span></span>

- <span data-ttu-id="a2bb8-417">**Neue Raumsuche:** suchen Sie in unterschiedlichen Kategorien nach Konferenzräumen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-417">**New room finder:** Search for conference rooms by different capabilities.</span></span>

- <span data-ttu-id="a2bb8-418">**Neue Buchungserfahrung für Konferenzräume und Arbeitsbereiche:** Die Buchungserfahrung für Konferenzräume wurde aktualisiert und zudem neue Funktionen hinzugefügt, mit denen Sie auch einzelne Arbeitsbereiche planen können.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-418">**New conference room and workspace booking experience:** The conference room booking experience has been refreshed, and with it we've added capabilities to allow you to schedule individual workspaces as well</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a2bb8-419">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a2bb8-419">PowerPoint</span></span>

- <span data-ttu-id="a2bb8-420">**Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-420">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="a2bb8-421">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-421">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="a2bb8-422">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://insider.office.com/de-DE/blog/svg-content-office-third-party-apps)</span><span class="sxs-lookup"><span data-stu-id="a2bb8-422">See details in [blog post](https://insider.office.com/de-DE/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="a2bb8-423">**Überwachungsprotokollierung für Vertraulichkeitsbezeichnungen:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, werden diese Informationen jetzt den Administratoren in den Microsoft 365-Auditprotokollen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-423">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="a2bb8-424">**Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-424">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="a2bb8-425">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-425">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)

### <a name="visio"></a><span data-ttu-id="a2bb8-426">Visio</span><span class="sxs-lookup"><span data-stu-id="a2bb8-426">Visio</span></span>

- <span data-ttu-id="a2bb8-427">**Neue Azure-Schablonen und -Formen:** Wir haben viele weitere Schablonen hinzugefügt, die Ihnen beim Erstellen von aktuellen Azure-Diagrammen helfen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-427">**New Azure stencils and shapes:** We've added many more stencils to help you create up-to-date Azure diagrams.</span></span> [<span data-ttu-id="a2bb8-428">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-428">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a><span data-ttu-id="a2bb8-429">Word</span><span class="sxs-lookup"><span data-stu-id="a2bb8-429">Word</span></span>

- <span data-ttu-id="a2bb8-430">**Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-430">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="a2bb8-431">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-431">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- <span data-ttu-id="a2bb8-432">**Überwachungsprotokollierung für Vertraulichkeitsbezeichnungen:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, werden diese Informationen jetzt den Administratoren in den Microsoft 365-Auditprotokollen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-432">**Sensitivity label audit logging:** When users apply, change, or remove sensitivity labels on their documents and emails, that information is now made available to administrators in the Microsoft 365 audit logs.</span></span>

- <span data-ttu-id="a2bb8-433">**Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-433">**Government customers: Apply sensitivity labels to your documents and emails:** Sensitivity labeling features are now available for customers in the GCC and GCC-H environments.</span></span> [<span data-ttu-id="a2bb8-434">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-434">Learn more</span></span>](/microsoft-365/compliance/sensitivity-labels)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a2bb8-437">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a2bb8-437">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a2bb8-438">Excel</span><span class="sxs-lookup"><span data-stu-id="a2bb8-438">Excel</span></span>

- <span data-ttu-id="a2bb8-439">Durch diese Änderung wird ein Problem behoben, bei dem Schriftarten in Formeln nicht ordnungsgemäß angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-439">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="a2bb8-440">Es wurde ein Problem behoben, bei dem einigen Benutzern während der gemeinsamen Erstellung fälschlicherweise eine Statusleiste angezeigt wurde, die sie über eine neue Version einer Datei informierte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-440">Fixed an issue where some users would incorrectly see a message bar informing them of a new version of a file when coauthoring.</span></span>


- <span data-ttu-id="a2bb8-441">Es wurde ein Problem behoben, bei dem Excel möglicherweise Makros ohne Anfrage deaktiviert lässt, wenn eine Excel-Add-In-Datei geöffnet wird, die Excel 4.0 Makros beinhaltet.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-441">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


- <span data-ttu-id="a2bb8-442">Ein Problem wurde behoben, bei dem Excel nicht gestartet werden konnte bzw. unerwartet geschlossen wurde, wenn bestimmte Einstellungen für den Schutz vor Windows-Sicherheit-Exploits (SimExec, CallerCheck) verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-442">Fixes an issue where Excel would fail to launch or close unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use.</span></span>


- <span data-ttu-id="a2bb8-443">Es wurde ein Problem behoben, bei dem Excel unerwartet geschlossen werden konnte, wenn Sie das Menü "Werte anzeigen als" für eine PivotTable verwendeten.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-443">Fixed an issue where Excel might close unexpectedly when using the "Show Values As" menu for a PivotTable.</span></span>


- <span data-ttu-id="a2bb8-444">Es wurde ein Problem behoben, wodurch einige ältere Excel 4.0- und Excel 5.0-Makros sowie einige VBA-Aufrufe an "dialogsheets.show" beschädigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-444">We fixed an issue that broke some legacy Excel 4.0 and Excel 5.0 macros as well as some VBA calls to dialogsheets.show.</span></span>


### <a name="outlook"></a><span data-ttu-id="a2bb8-445">Outlook</span><span class="sxs-lookup"><span data-stu-id="a2bb8-445">Outlook</span></span>

- <span data-ttu-id="a2bb8-446">Es wurde ein Problem behoben, bei dem eine bearbeitete Signatur nicht gespeichert werden konnte, nachdem der Benutzer hierzu aufgefordert wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-446">We fixed an issue that caused an edited signature to fail to save after prompting the user to do so.</span></span>


- <span data-ttu-id="a2bb8-447">Es wurde ein Problem behoben, das bei einigen Benutzern dazu führte, dass Outlook in bestimmten Suchszenarien unerwartet geschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-447">We fixed an issue that caused some users to experience Outlook closing unexpectedly in certain search scenarios.</span></span>


- <span data-ttu-id="a2bb8-448">Es wurde ein Problem behoben, das bei einigen Kunden dazu führte, dass sich das System beim Laden ihrer Kalender aufhängte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-448">We fixed an issue that caused some customers to encounter a hang while loading their calendars.</span></span>


- <span data-ttu-id="a2bb8-449">Es wurde ein Problem behoben, das bei Benutzern mit freigegebenen oder delegierten Postfächern mit großen Hierarchien in ihrem Profil zu Blockaden führte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-449">We fixed an issue that caused users that have Shared or Delegated Mailboxes with large hierarchies in their profile to encounter hangs.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a2bb8-450">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a2bb8-450">PowerPoint</span></span>

- <span data-ttu-id="a2bb8-451">Es wurde ein Problem behoben, bei dem der Befehl "Schriftgrad", der in QAT hinzugefügt wurde, beim Aktualisieren automatisch zum nächsten definierten Schriftgrad vervollständigt wird.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-451">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="a2bb8-452">Durch diese Änderung wird ein Problem behoben, bei dem Schriftarten in Formeln nicht ordnungsgemäß angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-452">This change addresses an issue with properly displaying fonts within equations.</span></span>


- <span data-ttu-id="a2bb8-453">Diese Änderung behebt ein Problem mit Pfadfüllungen beim Anwenden von "Formen zusammenführen"-Vorgängen mit bestimmten Geometrien.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-453">This change addresses an issue with path fills when applying Merge Shapes operations with certain geometries.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a2bb8-454">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a2bb8-454">Office Suite</span></span>

- <span data-ttu-id="a2bb8-455">Anaheim WebView unterstützt noch keinen Windows Information Protection (WIP).</span><span class="sxs-lookup"><span data-stu-id="a2bb8-455">Anaheim WebView does not support Windows Information Protection (WIP) yet.</span></span> <span data-ttu-id="a2bb8-456">Mit diesem Fix wird die Add-In-Plattform in Office wieder abwärtskompatibel mit WebView in einer Umgebung mit aktiviertem WIP.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-456">With this fix Office addin platform falls back to down level WebView in WIP enabled environment.</span></span> <span data-ttu-id="a2bb8-457">Dabei kann es sich entweder um Microsoft Edge Spartan WebView oder Trident WebView handeln, abhängig von der Computerumgebung des Kunden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-457">That can be either Edge Spartan WebView or Trident WebView depending on customer's machine environment.</span></span> <span data-ttu-id="a2bb8-458">Beide abwärtskompatiblem WebViews unterstützen WIP.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-458">Both down level WebViews support WIP.</span></span>


- <span data-ttu-id="a2bb8-459">Binäre Größe optimiert.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-459">Optimized binary size.</span></span>


- <span data-ttu-id="a2bb8-460">Die Schließfolge der Datei wurde korrigiert, so dass alle voneinander abhängigen Komponenten ordnungsgemäß geschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-460">Fixed the file closing sequence so that all the interdependent components are closed gracefully.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2011-february-09"></a><span data-ttu-id="a2bb8-462">Version 2011: 09. Februar</span><span class="sxs-lookup"><span data-stu-id="a2bb8-462">Version 2011: February 09</span></span>
<span data-ttu-id="a2bb8-463">*Version 2011 (Build 13426.20658)*</span><span class="sxs-lookup"><span data-stu-id="a2bb8-463">*Version 2011 (Build 13426.20658)*</span></span>

<span data-ttu-id="a2bb8-464">Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="a2bb8-464">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>

## <a name="version-2011-january-12"></a><span data-ttu-id="a2bb8-465">Version 2011: 12. Januar</span><span class="sxs-lookup"><span data-stu-id="a2bb8-465">Version 2011: January 12</span></span>
<span data-ttu-id="a2bb8-466">*Version 2011 (Build 13426.20526)*</span><span class="sxs-lookup"><span data-stu-id="a2bb8-466">*Version 2011 (Build 13426.20526)*</span></span>

<span data-ttu-id="a2bb8-467">Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="a2bb8-467">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="a2bb8-469">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="a2bb8-469">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="a2bb8-470">Zugriff</span><span class="sxs-lookup"><span data-stu-id="a2bb8-470">Access</span></span>

- <span data-ttu-id="a2bb8-471">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-471">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="a2bb8-472">Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-472">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="a2bb8-473">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-473">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="a2bb8-474">Excel</span><span class="sxs-lookup"><span data-stu-id="a2bb8-474">Excel</span></span>

- <span data-ttu-id="a2bb8-475">**Erstellen von Variablen zur Verwendung in Formeln:** Verbessern Sie Leistung, Lesbarkeit und Zusammensetzbarkeit mit der LET-Funktion.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-475">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="a2bb8-476">Mit dieser Funktion können Sie benannte Variablen in neuen oder bereits vorhandenen Formeln erstellen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-476">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="a2bb8-477">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-477">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="a2bb8-478">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="a2bb8-478">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="a2bb8-479">**Erstellen eines benutzerdefinierten Datentyps in Power Query:** Verwenden Sie eine beliebige Datenquelle zum Erstellen eines benutzerdefinierten Datentyps, mit dem Sie mehrere verwandte Informationen in eine Spalte laden können.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-479">**Create a custom data type in Power Query:** Use any data source to create a custom data type that lets you load multiple related pieces of information into one column.</span></span> [<span data-ttu-id="a2bb8-480">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-480">Learn more</span></span>](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br /><span data-ttu-id="a2bb8-481">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span><span class="sxs-lookup"><span data-stu-id="a2bb8-481">See details in [blog post](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span></span>

- <span data-ttu-id="a2bb8-482">**Benennen des neuen Blatts nach der Quellabfrage:** Wenn die Daten in das neue Blatt geladen werden, wird das Blatt basierend auf dem Namen der Quellabfrage benannt.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-482">**Name the new sheet after the source query:** When the data is loaded into the new sheet, the sheet will be named based on the name of the source query.</span></span>

- <span data-ttu-id="a2bb8-483">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-483">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="a2bb8-484">Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-484">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="a2bb8-485">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-485">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="a2bb8-486">OneNote</span><span class="sxs-lookup"><span data-stu-id="a2bb8-486">OneNote</span></span>

- <span data-ttu-id="a2bb8-487">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-487">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="a2bb8-488">Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-488">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="a2bb8-489">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-489">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="a2bb8-490">Outlook</span><span class="sxs-lookup"><span data-stu-id="a2bb8-490">Outlook</span></span>

- <span data-ttu-id="a2bb8-491">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-491">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="a2bb8-492">Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-492">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="a2bb8-493">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-493">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


### <a name="powerpoint"></a><span data-ttu-id="a2bb8-494">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a2bb8-494">PowerPoint</span></span>

- <span data-ttu-id="a2bb8-495">**Videobibliothek:** Erweitern Sie Ihre Dokumente mit einer Sammlung von kuratierten, lizenzfreien, in der App verfügbaren Videoaufnahmen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-495">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app.</span></span>

- <span data-ttu-id="a2bb8-496">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-496">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="a2bb8-497">Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-497">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="a2bb8-498">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-498">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="a2bb8-499">Project</span><span class="sxs-lookup"><span data-stu-id="a2bb8-499">Project</span></span>

- <span data-ttu-id="a2bb8-500">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-500">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="a2bb8-501">Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-501">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="a2bb8-502">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-502">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="a2bb8-503">Publisher</span><span class="sxs-lookup"><span data-stu-id="a2bb8-503">Publisher</span></span>

- <span data-ttu-id="a2bb8-504">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-504">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="a2bb8-505">Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-505">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="a2bb8-506">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-506">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="a2bb8-507">Visio</span><span class="sxs-lookup"><span data-stu-id="a2bb8-507">Visio</span></span>

- <span data-ttu-id="a2bb8-508">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-508">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="a2bb8-509">Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-509">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="a2bb8-510">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-510">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="a2bb8-511">Word</span><span class="sxs-lookup"><span data-stu-id="a2bb8-511">Word</span></span>

- <span data-ttu-id="a2bb8-512">**Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-512">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="a2bb8-513">Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-513">Go to File > Account and choose "Use system setting" under the Office Theme drop-down.</span></span> [<span data-ttu-id="a2bb8-514">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="a2bb8-514">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="a2bb8-517">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="a2bb8-517">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="a2bb8-518">Excel</span><span class="sxs-lookup"><span data-stu-id="a2bb8-518">Excel</span></span>

- <span data-ttu-id="a2bb8-519">Ein Problem wurde behoben, bei dem Excel fälschlicherweise eine Meldungsleiste anzeigt, dass eine neue Version der Datei verfügbar ist, und den Benutzer auffordert, seine Änderungen in einer Kopie der Arbeitsmappe zu speichern oder die Änderungen zu verwerfen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-519">Fixed an issue where Excel would incorrectly show a message bar that a new version of the file is available and force the user to save their changes in a copy of the workbook or discard their changes.</span></span>


- <span data-ttu-id="a2bb8-520">Es wurde ein Problem behoben, bei dem Excel möglicherweise Makros ohne Anfrage deaktiviert lässt, wenn eine Excel-Add-In-Datei geöffnet wird, die Excel 4.0 Makros beinhaltet.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-520">Fixed an issue where Excel may leave macros disabled without prompting when opening an Excel Add-in file containing Excel 4.0 Macros.</span></span>


### <a name="outlook"></a><span data-ttu-id="a2bb8-521">Outlook</span><span class="sxs-lookup"><span data-stu-id="a2bb8-521">Outlook</span></span>

- <span data-ttu-id="a2bb8-522">Es wurde ein Problem behoben, aufgrund dessen einige Benutzer keine Signaturen im Signaturen-Dropdownfeld sehen konnten, obwohl mindestens eine Signatur konfiguriert war.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-522">We fixed an issue that caused some users to see no signatures in the signatures drop down despite having one or more signatures configured.</span></span>


- <span data-ttu-id="a2bb8-523">Wir haben einen Registrierungsschlüssel hinzugefügt, mit dem Kunden die Dateizeiteinbeziehung für Anhänge in IDataObject-Operationen (z. B. Drag/Drop, Zwischenablage) deaktivieren können.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-523">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span>  <span data-ttu-id="a2bb8-524">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-524">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="a2bb8-525">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-525">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="a2bb8-526">0 = Filetimes sind ausgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-526">0 = filetimes are excluded.</span></span> <span data-ttu-id="a2bb8-527">1 = (Standard) Filetimes sind enthalten.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-527">1 = (default) filetimes are included.</span></span>


- <span data-ttu-id="a2bb8-528">Es wurde ein Problem behoben, das bewirkt, dass Inline Bilder beim Antworten auf eine Nachricht mit einer Schutz Bezeichnung von Azure Information Protection nicht mehr angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-528">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="a2bb8-529">Es wurde ein Problem behoben, aufgrund dessen das Ereignis "MailItem.BeforeAttachmentAdd" abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-529">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="a2bb8-530">Ein Problem wurde behoben, durch das das Feld „An:“ in Aufgabenstatusberichten leer war.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-530">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


- <span data-ttu-id="a2bb8-531">Es wurde ein Problem behoben, aufgrund dessen die ursprünglichen Teilnehmer einiger Besprechungen eine Absage erhielten, wenn ein anderer Teilnehmer die Besprechung weiterleitete.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-531">We fixed an issue that caused the original attendees of some meetings to receive a cancellation when another attendee forwards the meeting.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="a2bb8-532">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a2bb8-532">PowerPoint</span></span>

- <span data-ttu-id="a2bb8-533">Ein Problem wurde behoben, bei dem einige beschädigte PowerPoint-Dateien auch nach einem Dokumentreparaturvorgang nicht ordnungsgemäß geöffnet wurden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-533">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="a2bb8-534">Es wurde ein Fehler behoben, bei dem beim Speichern der Datei nach dem Duplizieren einer Folie, die ein neu aufgezeichnetes Audiosignal enthält, ein Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-534">We fixed an issue where there is an error when saving the file after duplicating a slide that contains a newly recorded audio.</span></span>


- <span data-ttu-id="a2bb8-535">Ein VBA-Problem wurde behoben, bei dem "Slide.Shapes.AddMediaObject2" mit veralteten Videoformaten abstürzt (MPG-1, MPEG-2).</span><span class="sxs-lookup"><span data-stu-id="a2bb8-535">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="a2bb8-536">Durch diese Änderung wird ein Problem beim Behandeln von Fehlern behoben, das während des Ladens von Videos auftreten konnte.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-536">This change addresses an issue with handling errors that may occur during video loading.</span></span>


- <span data-ttu-id="a2bb8-537">Ein Problem mit dem Kopieren/Einfügen einer Formel aus Word in PowerPoint wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-537">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


### <a name="project"></a><span data-ttu-id="a2bb8-538">Project</span><span class="sxs-lookup"><span data-stu-id="a2bb8-538">Project</span></span>

- <span data-ttu-id="a2bb8-539">Es wurde ein Problem behoben, bei dem bestimmte Projekte geöffnet werden konnten, wenn ein Problem mit der Projektdatei in einem bestimmten Teil der Last vorlag.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-539">Fixed an issue where specific projects could be opened if there was an issue with the project file in a specific part of load.</span></span>


### <a name="word"></a><span data-ttu-id="a2bb8-540">Word</span><span class="sxs-lookup"><span data-stu-id="a2bb8-540">Word</span></span>

- <span data-ttu-id="a2bb8-541">Ein Assert-Fehler wurde behoben, der von optimierten Gates betroffen war.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-541">Fix an assert bug exposed by optimized gates affecting Word.</span></span>


- <span data-ttu-id="a2bb8-542">Es wurde ein Problem behoben, bei dem Dokumentformate durch andere Formate aus der Vorlage ersetzt werden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-542">We fixed an issue which document styles are replaced with other styles from the template.</span></span>


- <span data-ttu-id="a2bb8-543">Durch diese Änderung wird ein Problem mit dem Cursor beim Bearbeiten eines Dokuments behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-543">This change addresses an issue with the cursor when editing a document.</span></span>


- <span data-ttu-id="a2bb8-544">Ein Problem mit dem Kopieren/Einfügen einer Formel aus Word in PowerPoint wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-544">Fixed an issue with copy/paste of an equation from Word to PowerPoint.</span></span>


### <a name="office-suite"></a><span data-ttu-id="a2bb8-545">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="a2bb8-545">Office Suite</span></span>

- <span data-ttu-id="a2bb8-546">Es wurde ein Problem behoben, bei dem aufgrund fehlender Registrierungseinträge die Installation einer neueren Version von Office über bestimmte ältere Versionen zu einer eingeschränkten Funktionalität führen konnte (beispielsweise war die Verwendung der Power-Abfrage nicht möglich).</span><span class="sxs-lookup"><span data-stu-id="a2bb8-546">Fixed an issue where installing a newer version of Office over certain older versions can result in impaired functionality (such as being unable to use Power Query) due to missing registry entries.</span></span>


- <span data-ttu-id="a2bb8-547">Es wurde ein Problem behoben, bei dem eine Datei als NICHT SyncBacked geöffnet wurde, wenn die URLs von Zwischenspeicher und OneDrive nicht übereinstimmten.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-547">Fixed an issue of file would be opened as NOT SyncBacked when url from cache and url from OneDrive does NOT match.</span></span>


- <span data-ttu-id="a2bb8-548">Ein Problem wurde behoben, bei dem „SaveRequestManagerCam“ dazu führte, dass die Anwendung geschlossen wurde, anstatt einen Fehler zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-548">We fixed an issue where SaveRequestManagerCam was causing the application to close instead of returning an error.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-january-12"></a><span data-ttu-id="a2bb8-550">Version 2010: 12. Januar</span><span class="sxs-lookup"><span data-stu-id="a2bb8-550">Version 2010: January 12</span></span>
<span data-ttu-id="a2bb8-551">*Version 2010 (Build 13328.20550)*</span><span class="sxs-lookup"><span data-stu-id="a2bb8-551">*Version 2010 (Build 13328.20550)*</span></span>

<span data-ttu-id="a2bb8-552">Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="a2bb8-552">Security updates listed [here](./microsoft365-apps-security-updates.md)</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)


[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

[//]: # (ENDE NICHT ENTFERNEN)

> [!NOTE]
> <span data-ttu-id="a2bb8-556">Wenn Sie Hilfe bei einem Problem mit der Nutzung von Office benötigen, empfehlen wir, dass Sie Ihre Frage im [Microsoft Answers-Forum](https://answers.microsoft.com/) oder in der [Tech-Community](https://techcommunity.microsoft.com/) veröffentlichen, oder Sie können sich an den [Support](https://support.microsoft.com/contactus) wenden.</span><span class="sxs-lookup"><span data-stu-id="a2bb8-556">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (ADMIN CENTER-METADATENINHALT NICHT ÄNDERN BEGINN)
[//]: # (|Win32|MEC|Production|Feature|16.0.14026.20334|version-2105-july-13|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13929.20408|version-2104-june-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13901.20516|version-2103-may-11|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13628.20528|version-2101-march-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13530.20528|version-2012-february-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13426.20526|version-2011-january-12|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13328.20478|version-2010-december-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13231.20514|version-2009-november-10|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13127.20638|version-2008-october-13|)
[//]: # (ADMIN CENTER-METADATENINHALT NICHT ÄNDERN ENDE)

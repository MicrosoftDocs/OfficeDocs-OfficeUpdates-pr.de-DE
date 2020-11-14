---
title: Versionshinweise für Versionen des halbjährlichen Unternehmenskanals im Jahr 2020
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt IT-Experten Anmerkungen zur Version für Releases im halbjährlichen Kanal für Microsoft 365 Apps im Jahr 2020 zur Verfügung.
ms.openlocfilehash: c719a54075f57b031cf99ef7459fe38c0cab63dc
ms.sourcegitcommit: 8e74984d0c36475374c34e76ed29c5d1ad81d971
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/10/2020
ms.locfileid: "48990074"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-releases-in-2020"></a><span data-ttu-id="079bb-103">Versionshinweise für Versionen des halbjährlichen Unternehmenskanals im Jahr 2020</span><span class="sxs-lookup"><span data-stu-id="079bb-103">Release notes for Semi-Annual Enterprise Channel releases in 2020</span></span>

<span data-ttu-id="079bb-104">Diese Versionshinweise enthalten Informationen zu neuen Features und nicht sicherheitsrelevanten Updates, die in Updates für den halbjährlichen Enterprise-Kanal im Jahr 2020 für Microsoft 365 Apps for Enterprise, Microsoft 365 Apps for Business sowie in den Abonnementversionen der Desktop-Apps für Project und Visio enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="079bb-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="079bb-p101">Wir nehmen einige Änderungen an den Updatekanälen für Microsoft 365 Apps vor, unter anderem fügen wir einen neuen Updatekanal hinzu (Monatlicher Enterprise-Kanal) und ändern die Namen der vorhandenen Updatekanäle. [In diesem Artikel](https://go.microsoft.com/fwlink/p/?linkid=2127441) erfahren Sie mehr dazu.</span><span class="sxs-lookup"><span data-stu-id="079bb-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="079bb-107">OneNote 2016 wird jetzt standardmäßig einbezogen, wenn ein Benutzer im halbjährlichen Unternehmenskanal Microsoft 365 Apps aus dem Office-Portal herunterlädt und auf Windows 10 installiert.</span><span class="sxs-lookup"><span data-stu-id="079bb-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (NICHT ENTFERNEN BUGDETAILS ENDE INHALT)

## <a name="version-2002-november-10"></a><span data-ttu-id="079bb-109">Version 2002: 10. November</span><span class="sxs-lookup"><span data-stu-id="079bb-109">Version 2002: November 10</span></span>
<span data-ttu-id="079bb-110">*Version 2002 (Build 12527.21330)*</span><span class="sxs-lookup"><span data-stu-id="079bb-110">*Version 2002 (Build 12527.21330)*</span></span>

<span data-ttu-id="079bb-111">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt.</span><span class="sxs-lookup"><span data-stu-id="079bb-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="079bb-113">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-113">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="079bb-114">Excel</span><span class="sxs-lookup"><span data-stu-id="079bb-114">Excel</span></span>

- <span data-ttu-id="079bb-115">Es wurde ein Problem, bei dem in Datenüberprüfungslisten u. U. nicht alle Elemente in der Liste angezeigt wurden, wenn die Office-Sprache auf Spanisch festgelegt war.</span><span class="sxs-lookup"><span data-stu-id="079bb-115">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="079bb-116">Ein Problem wurde behoben, das beim Aktualisieren von OLAP-PivotTables zu einem Absturz führen könnte.</span><span class="sxs-lookup"><span data-stu-id="079bb-116">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="079bb-117">Es wurde ein Fehler behoben, der bewirkte, dass nach dem Laden einer Arbeitsmappe bestimmte Funktionen falsche Ergebnisse aufwiesen.</span><span class="sxs-lookup"><span data-stu-id="079bb-117">Fixed a bug where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="079bb-118">Es wurde ein Problem wurde behoben, bei dem die Anwendung unerwartet beendet wurde, was mit XLAM-Add-In-Verweisen und benannten Bereichen zusammenhing.</span><span class="sxs-lookup"><span data-stu-id="079bb-118">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="079bb-119">Ein Problem wurde behoben, bei dem beim Ausführen des Makros für erweiterte Filter Fehler falsch gemeldet wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-119">Fixed an issue where running the advanced filter macro would incorrectly report errors.</span></span>


### <a name="outlook"></a><span data-ttu-id="079bb-120">Outlook</span><span class="sxs-lookup"><span data-stu-id="079bb-120">Outlook</span></span>

- <span data-ttu-id="079bb-121">Es wurde ein Problem behoben, das dazu führte, dass interne Add-Ins unerwartet deaktiviert wurden, wenn optionale verbundene Erfahrungen deaktiviert wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-121">We fixed an issue that caused internal add-ins to be unexpectedly disabled when optional connected experiences were disabled.</span></span>


- <span data-ttu-id="079bb-122">Es wurde ein Problem behoben, das bewirkte, dass Benutzer nicht in der Lage waren, als oder im Namen einer Verteilerliste zu senden, die in der globalen Adressliste ausgeblendet war.</span><span class="sxs-lookup"><span data-stu-id="079bb-122">We fixed an issue that caused users to be unable to send as or on behalf of a Distribution List that was hidden from the Global Address List.</span></span>



[//]: # (NICHT ENTFERNEN BUGDETAILS ENDE INHALT)

## <a name="version-1908-november-10"></a><span data-ttu-id="079bb-124">Version 1908: 10. November</span><span class="sxs-lookup"><span data-stu-id="079bb-124">Version 1908: November 10</span></span>
<span data-ttu-id="079bb-125">*Version 1908 (Build 11929.20974)*</span><span class="sxs-lookup"><span data-stu-id="079bb-125">*Version 1908 (Build 11929.20974)*</span></span>

<span data-ttu-id="079bb-126">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt.</span><span class="sxs-lookup"><span data-stu-id="079bb-126">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-october-13"></a><span data-ttu-id="079bb-127">Version 2002: 13. Oktober</span><span class="sxs-lookup"><span data-stu-id="079bb-127">Version 2002: October 13</span></span>
<span data-ttu-id="079bb-128">*Version 2002 (Build 12527.21236)*</span><span class="sxs-lookup"><span data-stu-id="079bb-128">*Version 2002 (Build 12527.21236)*</span></span>

<span data-ttu-id="079bb-129">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-129">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="079bb-131">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-131">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="079bb-132">Access</span><span class="sxs-lookup"><span data-stu-id="079bb-132">Access</span></span>

- <span data-ttu-id="079bb-133">Solange die Richtlinien und Anforderungen der Access-Datenbank erfüllt sind, sollte in Ihrer 64-Bit-Version von Access der Fehler "Abfrage ist zu komplex" nicht mehr angezeigt werden, und Sie sollten keine Systemressourcenüberschreitung mehr erhalten.</span><span class="sxs-lookup"><span data-stu-id="079bb-133">You should no longer receive a "Query is too complex" or a system resource exceeded error on your 64-bit version of Access, as long as you are meeting Access database guidelines and requirements.</span></span>


- <span data-ttu-id="079bb-134">Wenn Sie sich entscheiden, unsere Filterfunktion nach unserem Abfrage-Designer zu verwenden, sollte Ihre Datenbank nicht mehr abstürzen.</span><span class="sxs-lookup"><span data-stu-id="079bb-134">Once you decide to use our filter feature after our query designer, your database should no longer crash.</span></span> <span data-ttu-id="079bb-135">Bitte überprüfen Sie dies entsprechend.</span><span class="sxs-lookup"><span data-stu-id="079bb-135">Please check accordingly.</span></span>


### <a name="excel"></a><span data-ttu-id="079bb-136">Excel</span><span class="sxs-lookup"><span data-stu-id="079bb-136">Excel</span></span>

- <span data-ttu-id="079bb-137">Es wurde ein Problem behoben, bei dem Benutzer einen PivotTable-Filter nicht ändern konnten, weil er auf einen Wert eingestellt war, der in einer Analysis Services-Datenbank nicht mehr vorhanden war.</span><span class="sxs-lookup"><span data-stu-id="079bb-137">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="079bb-138">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="079bb-138">PowerPoint</span></span>

- <span data-ttu-id="079bb-139">Neue Präsentationen, die auf der Grundlage einer Vorlage erstellt wurden, konnten eine Einstellung erben, die eine fehlerfreie Umgebung für die gemeinsame Dokumenterstellung verhinderte.</span><span class="sxs-lookup"><span data-stu-id="079bb-139">New presentations created from a template could inherit a setting that prevented  a good co-authoring experience.</span></span> <span data-ttu-id="079bb-140">Mit diesem Fix wird sichergestellt, dass die Einstellung in diesem Fall gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-140">This fix ensures that the setting is cleared in this case.</span></span>


### <a name="word"></a><span data-ttu-id="079bb-141">Word</span><span class="sxs-lookup"><span data-stu-id="079bb-141">Word</span></span>

- <span data-ttu-id="079bb-142">Ein Problem wurde behoben, bei dem der Benutzer beim Öffnen von Dokumenten mit Seitenumbrüchen und Spalten eine Fehlermeldung erhalten konnte: "Sie haben die maximal von Microsoft Word unterstützte Seitenzahl überschritten, oder das Dokument ist beschädigt".</span><span class="sxs-lookup"><span data-stu-id="079bb-142">We fixed an issue which when opening documents with page breaks and columns, user might encountered an error message, " You have exceeded the maximum number of pages allowed by Microsoft Word supported, or the document may be damaged"</span></span>


### <a name="office-suite"></a><span data-ttu-id="079bb-143">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="079bb-143">Office Suite</span></span>

- <span data-ttu-id="079bb-144">Wenn ein Benutzer ein Dokument/ eine Datei auf Tintenstrahldrucker aus Office druckt und die Druckertinte niedrig ist, wird die Meldung "Wenig Toner" oder "Kein Toner" angezeigt, auch wenn Tintenstrahldrucker keine Toner haben.</span><span class="sxs-lookup"><span data-stu-id="079bb-144">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="079bb-145">Nachricht wird geändert, um "Wenig Toner/ Tinte" & "Kein Toner/ keine Tinte" anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="079bb-145">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1908-october-13"></a><span data-ttu-id="079bb-147">Version 1908: 13. Oktober</span><span class="sxs-lookup"><span data-stu-id="079bb-147">Version 1908: October 13</span></span>
<span data-ttu-id="079bb-148">*Version 1908 (Build 11929.20966)*</span><span class="sxs-lookup"><span data-stu-id="079bb-148">*Version 1908 (Build 11929.20966)*</span></span>

<span data-ttu-id="079bb-149">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-149">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="079bb-151">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-151">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="079bb-152">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="079bb-152">Office Suite</span></span>

- <span data-ttu-id="079bb-153">Wenn ein Benutzer ein Dokument/ eine Datei auf Tintenstrahldrucker aus Office druckt und die Druckertinte niedrig ist, wird die Meldung "Wenig Toner" oder "Kein Toner" angezeigt, auch wenn Tintenstrahldrucker keine Toner haben.</span><span class="sxs-lookup"><span data-stu-id="079bb-153">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="079bb-154">Nachricht wird geändert, um "Wenig Toner/ Tinte" & "Kein Toner/ keine Tinte" anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="079bb-154">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-september-08"></a><span data-ttu-id="079bb-156">Version 2002: 08. September</span><span class="sxs-lookup"><span data-stu-id="079bb-156">Version 2002: September 08</span></span>
<span data-ttu-id="079bb-157">*Version 2002 (Build 12527.21104)*</span><span class="sxs-lookup"><span data-stu-id="079bb-157">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="079bb-158">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-158">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="079bb-160">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-160">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="079bb-161">Excel</span><span class="sxs-lookup"><span data-stu-id="079bb-161">Excel</span></span>

- <span data-ttu-id="079bb-162">Damit wird ein Problem behoben, bei dem interne Tabelleneigenschaften für Verbindungen, die vom SQL-Datenanbieter in älteren Office-Versionen erstellt wurden, anders als in Office 365 festgelegt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-162">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="079bb-163">Dies führte dazu, dass die Dropdown-Liste "Tabellenvorschau/Abfrageeditor" für Dateien mit Verbindungen, die in älteren Office-Versionen erstellt wurden, deaktiviert wurde, wenn sie mit Office 365 geöffnet wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-163">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="079bb-164">Ein Problem wurde behoben, bei dem Freihandeingaben dazu führen konnten, dass Excel nicht mehr reagierte.</span><span class="sxs-lookup"><span data-stu-id="079bb-164">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="079bb-165">Outlook</span><span class="sxs-lookup"><span data-stu-id="079bb-165">Outlook</span></span>

- <span data-ttu-id="079bb-166">Behebt ein Problem, das dazu führte, dass Benutzer nach dem Hinzufügen eines freigegebenen Postfachs keine Verbindung mit öffentlichen Ordnern herstellen konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-166">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="079bb-167">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="079bb-167">Office Suite</span></span>

- <span data-ttu-id="079bb-168">Diese Änderung behebt ein Problem, bei dem im Dialogfeld „Bild komprimieren“ bestimmte Benutzereinstellungen nicht beibehalten werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-168">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1908-september-08"></a><span data-ttu-id="079bb-170">Version 1908: 08. September</span><span class="sxs-lookup"><span data-stu-id="079bb-170">Version 1908: September 08</span></span>
<span data-ttu-id="079bb-171">*Version 1908 (Build 11929.20946)*</span><span class="sxs-lookup"><span data-stu-id="079bb-171">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="079bb-172">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt.</span><span class="sxs-lookup"><span data-stu-id="079bb-172">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="079bb-173">Version 2002: 11. August</span><span class="sxs-lookup"><span data-stu-id="079bb-173">Version 2002: August 11</span></span>
<span data-ttu-id="079bb-174">*Version 2002 (Build 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="079bb-174">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="079bb-175">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-175">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="079bb-177">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-177">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="079bb-178">Excel</span><span class="sxs-lookup"><span data-stu-id="079bb-178">Excel</span></span>

- <span data-ttu-id="079bb-179">Ein Problem wurde behoben, bei dem verhindert wurde, dass mit der Option „Schreibschutz empfohlen“ geöffnete Dateien bearbeitet werden konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-179">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="079bb-180">OneNote</span><span class="sxs-lookup"><span data-stu-id="079bb-180">OneNote</span></span>

- <span data-ttu-id="079bb-181">Redundante Identitätsaufrufe wurden entfernt, um die Ressourcennutzung zu verringern.</span><span class="sxs-lookup"><span data-stu-id="079bb-181">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="079bb-182">Die Erkennung des Status der gemeinsamen Dokumenterstellung wurde verbessert, um die Ressourcennutzung zu verringern.</span><span class="sxs-lookup"><span data-stu-id="079bb-182">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="079bb-183">Die Funktion zum Erkennen von Fehlern und die Qualität der Synchronisierung wurden verbessert.</span><span class="sxs-lookup"><span data-stu-id="079bb-183">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="079bb-184">Outlook</span><span class="sxs-lookup"><span data-stu-id="079bb-184">Outlook</span></span>

- <span data-ttu-id="079bb-185">Ein Problem wurde behoben, das beim Starten von Outlook für einige Mandanten zu einem erheblichen Leistungsproblem führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-185">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="079bb-186">Skype</span><span class="sxs-lookup"><span data-stu-id="079bb-186">Skype</span></span>

- <span data-ttu-id="079bb-187">Ein Problem wurde behoben, bei dem das Starten einer Bildschirmfreigabe auf einem 32-Bit-Skype for Business-Client fehlschlagen kann, nachdem er mehrere Tage lang ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-187">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="079bb-188">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="079bb-188">Office Suite</span></span>

- <span data-ttu-id="079bb-189">Ein Problem wurde behoben, bei dem einige Dokumente – nach Deaktivierung von „Automatisches Speichern“ durch eine Gruppenrichtlinie – die neuesten Serverinhalte beim Öffnen möglicherweise so lange nicht zeigen, bis der Benutzer auf „Verfügbare Updates“ geklickt hat.</span><span class="sxs-lookup"><span data-stu-id="079bb-189">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1908-august-11"></a><span data-ttu-id="079bb-191">Version 1908: 11. August</span><span class="sxs-lookup"><span data-stu-id="079bb-191">Version 1908: August 11</span></span>
<span data-ttu-id="079bb-192">*Version 1908 (Build 11929.20934)*</span><span class="sxs-lookup"><span data-stu-id="079bb-192">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="079bb-193">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-193">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="079bb-194">Version 1902: 11. August</span><span class="sxs-lookup"><span data-stu-id="079bb-194">Version 1902: August 11</span></span>
<span data-ttu-id="079bb-195">*Version 1902 (Build 11328.20644)*</span><span class="sxs-lookup"><span data-stu-id="079bb-195">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="079bb-196">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-196">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-july-14"></a><span data-ttu-id="079bb-199">Version 2002: 14. Juli</span><span class="sxs-lookup"><span data-stu-id="079bb-199">Version 2002: July 14</span></span>
<span data-ttu-id="079bb-200">*Version 2002 (Build 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="079bb-200">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="079bb-201">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-201">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="079bb-203">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="079bb-203">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="079bb-204">Access</span><span class="sxs-lookup"><span data-stu-id="079bb-204">Access</span></span>

- <span data-ttu-id="079bb-205">**Schnelle Suche nach verknüpften Tabellen:** Unser neues Suchfeld macht die Suche nach verknüpften Tabellen zu einem Kinderspiel.</span><span class="sxs-lookup"><span data-stu-id="079bb-205">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="079bb-206">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-206">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="079bb-207">Excel</span><span class="sxs-lookup"><span data-stu-id="079bb-207">Excel</span></span>

- <span data-ttu-id="079bb-208">**Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="079bb-208">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="079bb-209">**Add-In „Datenschnellansicht“:** erstellen Sie schnell Visio-Flussdiagramme aus Excel.</span><span class="sxs-lookup"><span data-stu-id="079bb-209">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="079bb-210">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-210">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="079bb-211">**Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten.</span><span class="sxs-lookup"><span data-stu-id="079bb-211">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="079bb-212">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-212">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="079bb-213">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="079bb-213">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="079bb-214">**Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="079bb-214">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="079bb-215">Sie finden diese unter "Einfügen" > "Symbole".</span><span class="sxs-lookup"><span data-stu-id="079bb-215">Find them at Insert > Icons.</span></span> [<span data-ttu-id="079bb-216">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-216">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="079bb-217">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="079bb-217">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="079bb-218">Weitere Informationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="079bb-218">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="079bb-219">**Konzentrieren Sie sich darauf, was noch erledigt werden muss:** Wählen Sie "Auflösen" aus, um Kommentare zu reduzieren und offene Punkte hervorzuheben.</span><span class="sxs-lookup"><span data-stu-id="079bb-219">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="079bb-220">**Eingeben einer Formel, die mehrere Werte zurückgibt** Schnell eine Formel eingeben, die mehrere Werte zurückgibt, und diese werden automatisch in die benachbarten Zellen übertragen.</span><span class="sxs-lookup"><span data-stu-id="079bb-220">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="079bb-221">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-221">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="079bb-222">Einzelheiten finden Sie im [Blogbeitrag](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/).</span><span class="sxs-lookup"><span data-stu-id="079bb-222">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="079bb-223">**Keine Umleitung zum Browser mehr:** Sie legen fest, wie Links zu Office-Dokumenten geöffnet werden: im Browser oder in der App.</span><span class="sxs-lookup"><span data-stu-id="079bb-223">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="079bb-224">**Zeichnen Sie es auf:** Verleihen Sie Office-Shapes in Ihrer Arbeitsmappe ein ungezwungenes, von Hand gezeichnetes Aussehen.</span><span class="sxs-lookup"><span data-stu-id="079bb-224">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="079bb-225">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-225">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="079bb-226">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="079bb-226">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="079bb-227">**Finden Sie, wonach Sie suchen:** Suchen Sie Befehle, Personen, Dateien, Fotos, Webartikel und mehr.</span><span class="sxs-lookup"><span data-stu-id="079bb-227">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="079bb-228">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-228">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="079bb-229">**Sechs leistungsfähige Funktionen:** Wir haben sechs neue Funktionen hinzugefügt, um Ihre Tabellenkalkulationen aufzuladen: FILTERN, SORTIEREN, SORTIERENNACH, EINDEUTIG, SEQUENZ und ZUFALLSMATRIX.</span><span class="sxs-lookup"><span data-stu-id="079bb-229">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="079bb-230">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-230">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="079bb-231">**Ein Blick nach links, ein Blick nach rechts... XVERWEIS ist da!:** Zeile für Zeile finden Sie mit XVERWEIS alles, was Sie in einer Tabelle oder einem Bereich benötigen.</span><span class="sxs-lookup"><span data-stu-id="079bb-231">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="079bb-232">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-232">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="079bb-233">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span><span class="sxs-lookup"><span data-stu-id="079bb-233">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="079bb-234">**Zähmen Sie Ihre große Arbeitsmappe:** Zellen, Formeln, Diagramme, Tabellen ... Erhalten Sie eine Momentaufnahme Ihrer Arbeitsmappe mit Arbeitsblattstatistiken.</span><span class="sxs-lookup"><span data-stu-id="079bb-234">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="079bb-235">**Auf die Schnelle lesen und antworten:** Antworten Sie auf Kommentare und Erwähnungen direkt aus dem E-Mail-Bereich, ohne die Arbeitsmappe zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="079bb-235">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="079bb-236">**Machen Sie andere mit \@Erwähnungen auf sich aufmerksam:** Mithilfe von @Erwähnungen in Kommentaren können Sie Kollegen informieren, wenn Sie deren Input benötigen.</span><span class="sxs-lookup"><span data-stu-id="079bb-236">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="079bb-237">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-237">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="079bb-238">Outlook</span><span class="sxs-lookup"><span data-stu-id="079bb-238">Outlook</span></span>

- <span data-ttu-id="079bb-239">**Mehr Nachrichten am Bildschirm anzeigen:** Wählen Sie „Anzeigen“ > Engere Abstände verwenden, um die Abstände zwischen den Nachrichten anzupassen.</span><span class="sxs-lookup"><span data-stu-id="079bb-239">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="079bb-240">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-240">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="079bb-241">**Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="079bb-241">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="079bb-242">Sie finden diese unter "Einfügen" > "Symbole".</span><span class="sxs-lookup"><span data-stu-id="079bb-242">Find them at Insert > Icons.</span></span> [<span data-ttu-id="079bb-243">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-243">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="079bb-244">**Müheloses Zeichnen und Signieren:** Kritzeln Sie über die Bilder, oder fügen Sie einen Zeichenbereich hinzu, um Ihren Gedanken als Freihandnotizen Ausdruck zu verleihen.</span><span class="sxs-lookup"><span data-stu-id="079bb-244">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="079bb-245">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-245">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="079bb-246">**Erhalten Sie Ortsvorschläge:** Beginnen Sie beim Planen von Terminen und Besprechungen mit der Eingabe im Feld „Ort“, so schlägt Outlook Räume, Adressen und andere zuletzt verwendete Orte vor.</span><span class="sxs-lookup"><span data-stu-id="079bb-246">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="079bb-247">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-247">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="079bb-248">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="079bb-248">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="079bb-249">**Erweiterter Schutz gegen Angriffe:** Mit Office 365 Advanced Threat Protection sind Sie vor Angriffen durch Links in E-Mail-Betreffzeilen, angefügten Nachrichten, signierten Nachrichten, Netzwerkpfaden usw. geschützt.</span><span class="sxs-lookup"><span data-stu-id="079bb-249">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="079bb-250">**Das Menü „Link einfügen“ in Outlook fügt einen Link mit der vom Mandantenadministrator festgelegten Berechtigung ein:** Ein Link aus dem Link-Einfügen-MRU in Outlook fügte einen Link ein, der nur für diejenigen Benutzer funktionierte, die bereits eine Berechtigung besaßen.</span><span class="sxs-lookup"><span data-stu-id="079bb-250">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="079bb-251">Dies führte häufig zu E-Mail-Nachrichten zwischen Benutzern, die den Zugriff auf ein Dokument anforderten.</span><span class="sxs-lookup"><span data-stu-id="079bb-251">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="079bb-252">Wir haben diese Erfahrung aktualisiert, sodass der Link jetzt mit der vom Mandantenadministrator festgelegten Standardberechtigung eingefügt wird. Für MSIT ist dies "Organisation kann bearbeiten", sodass alle internen Benutzer, die einen auf diese Weise freigegebenen Link erhalten, darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="079bb-252">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="079bb-253">**Sehen Sie Ihre Nachrichten in einem neuen Licht:** Verwenden Sie die Sonne/Mond-Schaltfläche, um im Lesebereich zwischen hellem und dunklem Hintergrund zu wechseln.</span><span class="sxs-lookup"><span data-stu-id="079bb-253">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="079bb-254">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-254">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="079bb-255">**Phishing-E-Mails sind jetzt leicht zu erkennen:** Spam- und Phishing-E-Mails haben ein anderes Aussehen und Verhalten, sodass Sie sie leichter identifizieren und aus Ihrem Posteingang entfernen können.</span><span class="sxs-lookup"><span data-stu-id="079bb-255">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="079bb-p123">**Alle Verschlüsselungsoptionen an einem zentralen Ort:** Gehen Sie einfach zu Optionen > Verschlüsseln, um auszuwählen, wie Ihre E-Mail-Nachricht gesichert wird. [Weitere Informationen](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="079bb-p123">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="079bb-258">**Suchen bei Rechtschreibschwierigkeiten oder Tippfehlern:** Outlook wird auch dann finden, was Sie suchen, wenn Sie sich verschreiben.</span><span class="sxs-lookup"><span data-stu-id="079bb-258">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="079bb-259">**Verbinden Ihres LinkedIn-Netzwerks mit Outlook:** Stellen Sie eine sichere Verbindung zwischen Ihrem LinkedIn-Konto und Ihrem Microsoft-Konto her, um Informationen aus LinkedIn-Profilen direkt auf der Karte mit Ihren Kontakten anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="079bb-259">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="079bb-260">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-260">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="079bb-261">**Finden Sie relevante Nachrichten in Ihren Suchergebnissen:** Outlook analysiert Suchbegriffe und zeigt die wichtigsten E-Mail-Nachrichten am Anfang der Suchergebnisse an.</span><span class="sxs-lookup"><span data-stu-id="079bb-261">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="079bb-262">Außerdem sehen Sie alle Ergebnisse sortiert nach Datum im Abschnitt „Top-Ergebnisse“.</span><span class="sxs-lookup"><span data-stu-id="079bb-262">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="079bb-263">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-263">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="079bb-264">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="079bb-264">PowerPoint</span></span>

- <span data-ttu-id="079bb-p126">**Sie berechnen, wir formatieren:** Von Hand gezeichnete mathematische Ausdrücke werden in Standardzeichen umgewandelt. Wählen Sie einfach "Freihand in Gleichung" und Ihre handschriftlichen Notizen aus, um loszulegen. [Weitere Informationen](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="079bb-p126">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="079bb-268">**Finden Sie, wonach Sie suchen:** Verwenden Sie das Suchfeld, um Text, Befehle, Hilfe und mehr zu finden.</span><span class="sxs-lookup"><span data-stu-id="079bb-268">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="079bb-269">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-269">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="079bb-270">**Erstellen Sie eine hervorragende Folie:** Konvertieren Sie Ihre Freihandeingaben in Standardformen und -text, und lassen Sie sich dann von PowerPoint-Designer intelligente Folienentwurfsideen anzeigen.</span><span class="sxs-lookup"><span data-stu-id="079bb-270">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="079bb-271">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-271">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="079bb-272">**Zeichnen Sie es auf:** Verleihen Sie Office-Shapes in Ihrer Präsentation ein ungezwungenes, von Hand gezeichnetes Aussehen.</span><span class="sxs-lookup"><span data-stu-id="079bb-272">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="079bb-273">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-273">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="079bb-274">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="079bb-274">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="079bb-275">**Wiedergabe von animierten Freihandzeichnungen:** Wenn Sie Freihandeingaben auf Ihren Folien vornehmen, können Sie auf diese Freihandeingaben Replay-Animationen anwenden, um den eigentlichen Zeichenvorgang während der Bildschirmpräsentation wiederzugeben.</span><span class="sxs-lookup"><span data-stu-id="079bb-275">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="079bb-276">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-276">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="079bb-277">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="079bb-277">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="079bb-278">**Eine sicherere Video-Umgebung:** Sicherheitsverbesserungen bedeuten für Sie eine sicherere Online-Videoumgebung.</span><span class="sxs-lookup"><span data-stu-id="079bb-278">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="079bb-279">**Speichern einer Illustration als SVG:** Speichern Sie ein Diagramm, eine Form oder eine andere Abbildung als skalierbare Vektorgrafik, deren Größe ohne Verlust der Bildqualität geändert werden kann.</span><span class="sxs-lookup"><span data-stu-id="079bb-279">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="079bb-280">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-280">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="079bb-281">**Drucken von Foliennummern auf Handzetteln:** Foliennummern werden automatisch in Ihre Handzettel integriert.</span><span class="sxs-lookup"><span data-stu-id="079bb-281">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="079bb-282">Sie können diese Funktion an- oder abschalten, wie es Ihnen beliebt.</span><span class="sxs-lookup"><span data-stu-id="079bb-282">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="079bb-283">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-283">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="079bb-284">**Suchen und Beheben von fehlenden Folientiteln:** Folientitel verleihen Ihrem Pitch mehr Nachdruck und machen Ihre Folien für Benutzer mit unterschiedlichen Fähigkeiten zugänglich.</span><span class="sxs-lookup"><span data-stu-id="079bb-284">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="079bb-285">Die Barrierefreiheitsprüfung zeigt Ihnen, wo Titel fehlen, damit Sie diese schnell hinzufügen können.</span><span class="sxs-lookup"><span data-stu-id="079bb-285">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="079bb-286">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-286">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="079bb-287">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="079bb-287">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="079bb-288">Weitere Informationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="079bb-288">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="079bb-289">**Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="079bb-289">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="079bb-290">Sie finden diese unter "Einfügen" > "Symbole".</span><span class="sxs-lookup"><span data-stu-id="079bb-290">Find them at Insert > Icons.</span></span> [<span data-ttu-id="079bb-291">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-291">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="079bb-292">**Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten.</span><span class="sxs-lookup"><span data-stu-id="079bb-292">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="079bb-293">Weitere Informationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="079bb-293">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="079bb-294">**Schnellere Dateifreigabe:** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="079bb-294">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="079bb-295">**Schnelle Zusammenarbeit in Echtzeit in PowerPoint:** Schnelle Zusammenarbeit in Echtzeit in PowerPoint</span><span class="sxs-lookup"><span data-stu-id="079bb-295">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="079bb-296">**Keine Umleitung zum Browser mehr:** Sie legen fest, wie Links zu Office-Dokumenten geöffnet werden: im Browser oder in der App.</span><span class="sxs-lookup"><span data-stu-id="079bb-296">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="079bb-297">**Neue Tools zum Korrekturlesen:** Machen Sie sich keine Sorgen mehr über Ihre Texte.</span><span class="sxs-lookup"><span data-stu-id="079bb-297">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="079bb-298">PowerPoint bietet jetzt Grammatik- und Textvorschläge.</span><span class="sxs-lookup"><span data-stu-id="079bb-298">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="079bb-299">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-299">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="079bb-300">**Live-Beschriftungen und -Untertitel:** die Worte des Referenten werden automatisch als Beschriftungen oder Untertitel in der von Ihnen gewünschten Sprache auf dem Bildschirm angezeigt.</span><span class="sxs-lookup"><span data-stu-id="079bb-300">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="079bb-301">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-301">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="079bb-302">**Optimieren Sie Ihre Präsentation für alle:** Die Barrierefreiheitsprüfung hilft Ihnen beim Anordnen von Objekten auf Ihren Folien, indem sie die Sprachausgabe berücksichtigt.</span><span class="sxs-lookup"><span data-stu-id="079bb-302">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="079bb-303">Weitere Informationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span><span class="sxs-lookup"><span data-stu-id="079bb-303">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="079bb-304">**Warum neu erstellen, wenn Sie etwas wiederverwenden können?** Sparen Sie Zeit, indem Sie Folien, die Sie erstellt haben oder die andere für Sie freigegeben haben, erneut verwenden.</span><span class="sxs-lookup"><span data-stu-id="079bb-304">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="079bb-305">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-305">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="079bb-306">Visio</span><span class="sxs-lookup"><span data-stu-id="079bb-306">Visio</span></span>

- <span data-ttu-id="079bb-307">**Erstellen Sie ansprechende Visio-Diagramme in Excel:** Erstellen Sie ein Flussdiagramm oder ein Organigramm durch Einfügen von Daten in ein Arbeitsblatt.</span><span class="sxs-lookup"><span data-stu-id="079bb-307">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="079bb-308">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-308">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="079bb-309">**Zurück zum Tatort:** Verwenden Sie die neuen Schablonen "Beweismittel", "Drinnen" und "Draußen" der Vorlage "Tatortermittlung", um Tatorte im Detail nachzustellen.</span><span class="sxs-lookup"><span data-stu-id="079bb-309">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="079bb-310">Word</span><span class="sxs-lookup"><span data-stu-id="079bb-310">Word</span></span>

- <span data-ttu-id="079bb-311">**Eine sicherere Video-Umgebung:** Security-Verbesserungen bedeuten für Sie eine sicherere Online-Video-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="079bb-311">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="079bb-312">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-312">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="079bb-313">**Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten.</span><span class="sxs-lookup"><span data-stu-id="079bb-313">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="079bb-314">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-314">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="079bb-315">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="079bb-315">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="079bb-316">**Schnellere Dateifreigabe:** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="079bb-316">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="079bb-317">**Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="079bb-317">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="079bb-318">Sie finden diese unter "Einfügen" > "Symbole".</span><span class="sxs-lookup"><span data-stu-id="079bb-318">Find them at Insert > Icons.</span></span> [<span data-ttu-id="079bb-319">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-319">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="079bb-320">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span><span class="sxs-lookup"><span data-stu-id="079bb-320">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="079bb-321">**Präzises Löschen:** Wählen Sie aus zwei Radierergrößen aus, um kleine Unvollkommenheiten zu beheben.</span><span class="sxs-lookup"><span data-stu-id="079bb-321">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="079bb-322">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-322">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="079bb-323">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="079bb-323">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="079bb-324">Weitere Informationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="079bb-324">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="079bb-325">**Zeichnen Sie es auf:** Verleihen Sie Office-Shapes in Ihrem Dokument ein ungezwungenes, von Hand gezeichnetes Aussehen.</span><span class="sxs-lookup"><span data-stu-id="079bb-325">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="079bb-326">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-326">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="079bb-327">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="079bb-327">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="079bb-328">**Finden Sie, wonach Sie suchen:** Verwenden Sie das Suchfeld, um Text, Befehle, Hilfe und mehr zu finden.</span><span class="sxs-lookup"><span data-stu-id="079bb-328">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="079bb-329">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-329">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="079bb-330">**Keine Umleitung zum Browser mehr:** Sie legen fest, wie Links zu Office-Dokumenten geöffnet werden: im Browser oder in der App.</span><span class="sxs-lookup"><span data-stu-id="079bb-330">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="079bb-331">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-331">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="079bb-332">**Lebenslauf-Editor-Verknüpfung mit dem LinkedIn-Lebenslauf-Assistent:** Der Lebenslauf-Editor bietet eine Auswahl an Grammatik- und Stilprüfungen, die speziell auf Lebensläufe zugeschnitten sind, um Ihr Schreiben präziser und professioneller zu gestalten.</span><span class="sxs-lookup"><span data-stu-id="079bb-332">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="079bb-333">**Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.</span><span class="sxs-lookup"><span data-stu-id="079bb-333">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="079bb-334">**Es wurde ein Problem mit beschädigten Dokumenten behoben, das durch das Zusammenführen von 3D-Objekten verursacht wurde.** Es wurde ein Problem mit beschädigten Dokumenten behoben, das durch das Zusammenführen von 3D-Objekten verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-334">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="079bb-335">**Verbesserungen bei der gemeinsamen Dokumenterstellung** : verbesserte Leistung von Word bei der gemeinsamen Dokumenterstellung mit nachverfolgbaren Änderungen.</span><span class="sxs-lookup"><span data-stu-id="079bb-335">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="079bb-336">**Verbesserungen bei der gemeinsamen Dokumenterstellung:** verbesserte Zuverlässigkeit bei der gemeinsamen Dokumenterstellung.</span><span class="sxs-lookup"><span data-stu-id="079bb-336">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="079bb-337">**Zusammenarbeit in lebendigen Farben:** Kommentare und Änderungen sind nach Verfasser farblich gekennzeichnet, sodass Sie die einzelnen Mitwirkenden leichter unterscheiden können.</span><span class="sxs-lookup"><span data-stu-id="079bb-337">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="079bb-338">**Makrofähige Dokumente gemeinsam bearbeiten:** Speichern Sie Ihre Dokumentdateien auf OneDrive for Business, und bearbeiten Sie sie mit anderen in Echtzeit.</span><span class="sxs-lookup"><span data-stu-id="079bb-338">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="079bb-339">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="079bb-339">Office Suite</span></span>

- <span data-ttu-id="079bb-340">**Ändern der handschriftlichen Freihandeingabe in Formen, Text oder Mathematik in PowerPoint für Office 365:** Wechseln Sie mit wenigen Strichen von der Freihandeingabe zu Office-Formen, Text oder einem mathematischen Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="079bb-340">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="079bb-341">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-341">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="079bb-344">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-344">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="079bb-345">Access</span><span class="sxs-lookup"><span data-stu-id="079bb-345">Access</span></span>

- <span data-ttu-id="079bb-346">Dieses Update behebt ein Problem bei der Verwendung von ADODB.</span><span class="sxs-lookup"><span data-stu-id="079bb-346">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="079bb-347">Das Recorder-Objekt im VB-Code meldet möglicherweise einen Fehler falsch.</span><span class="sxs-lookup"><span data-stu-id="079bb-347">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="079bb-348">Access-Vorlagen sollten nicht länger dazu führen, dass Anhangsspalten in einer Datenbank fehlschlagen.</span><span class="sxs-lookup"><span data-stu-id="079bb-348">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="079bb-349">Nachdem Sie eine Vorlage instanziiert haben, sollten Sie nun in der Lage sein, Ihrer Datenbank ein Anhangsfeld hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="079bb-349">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="079bb-350">Dieses Update behebt ein Problem, das dazu führen kann, dass Microsoft Access eine Identitätsspalte in einer verknüpften SQL-Server-Tabelle nicht identifiziert, was dazu führen kann, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-350">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="079bb-351">Mit diesem Update wird ein Problem in Microsoft Access behoben, das den Fehler "Abfrage ist beschädigt" verursachen kann, wenn eine Aktualisierungsabfrage ausgeführt oder eine UPDATE-Anweisung in SQL verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-351">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="079bb-352">Excel</span><span class="sxs-lookup"><span data-stu-id="079bb-352">Excel</span></span>

- <span data-ttu-id="079bb-353">Beschleunigen des Ladens von Dateien, die im lokalen OneDrive-Ordner zur Verfügung stehen.</span><span class="sxs-lookup"><span data-stu-id="079bb-353">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="079bb-354">Ein Problem wurde behoben, bei dem CUBEWERT-Funktionen manchmal ein falsches Ergebnis zurückgaben.</span><span class="sxs-lookup"><span data-stu-id="079bb-354">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="079bb-355">Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-355">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="079bb-356">Excel stürzt in bestimmten Fällen ab, wenn eine in Word oder PowerPoint eingebettete Arbeitsmappe erneut geöffnet wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-356">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="079bb-357">Es wurde ein Problem behoben, bei dem Kommentarbefehle im Kontextmenü nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-357">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="079bb-358">Das Kontextmenü für PivotCharts wurde korrigiert, um die Option "Details anzeigen" zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="079bb-358">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="079bb-359">Es wurde ein Problem behoben, das bei der Suche nach zuletzt verwendeten Dateien zu einem Absturz geführt hat, wenn keine Arbeitsmappe geöffnet ist.</span><span class="sxs-lookup"><span data-stu-id="079bb-359">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="079bb-360">Es wurde ein Problem behoben, bei dem das Klicken auf eine mit einem Lesezeichen versehene Verknüpfung innerhalb derselben Arbeitsmappe dazu führte, dass die Arbeitsmappe ausgeblendet wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-360">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="079bb-361">Beim Speichern als CSV-Datei hat Excel in einigen Fällen alle Spalten in einer einzigen Spalte zusammengeführt.</span><span class="sxs-lookup"><span data-stu-id="079bb-361">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="079bb-362">Die Verwendung von Range.ClearContents für einen Bereich auf einem geschützten Blatt hat möglicherweise länger gedauert als erwartet.</span><span class="sxs-lookup"><span data-stu-id="079bb-362">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="079bb-363">Es wurde ein Problem beim Skalieren von Text in Steuerelementen von Formularen beim Anzeigen in der Druckansicht behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-363">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="079bb-364">VBA-Makros, die mit dem Menüband interagieren, können möglicherweise mit ScreenUpdating unerwartet auf „Wahr“ festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-364">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="079bb-365">Ein Problem wurde behoben, bei dem Excel in manchen Fällen abstürzte, nachdem ein Blatt mit einer PivotTable kopiert wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-365">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="079bb-366">Das Öffnen von CSV-Dateien dauerte unter bestimmten Umständen länger als erwartet.</span><span class="sxs-lookup"><span data-stu-id="079bb-366">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="079bb-367">Excel stürzt möglicherweise unter bestimmten Umständen ab, wenn zwischen den Arbeitsmappen mit anderen Zoomstufen gewechselt wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-367">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="079bb-368">Es wurde ein Problem mit VBA behoben, bei dem das Schreiben von Werten in einem Wertebereich langsamer als erwartet war.</span><span class="sxs-lookup"><span data-stu-id="079bb-368">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="079bb-369">Daten, die aus einer nach Farbe gefilterten Spalte kopiert wurden, werden manchmal nicht ordnungsgemäß eingefügt.</span><span class="sxs-lookup"><span data-stu-id="079bb-369">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="079bb-370">Das Öffnen einer Arbeitsmappe mit Verweisen auf zahlreiche andere Arbeitsmappen, insbesondere mit ausgeblendeten Fenstern, würde langsamer als erwartet ablaufen.</span><span class="sxs-lookup"><span data-stu-id="079bb-370">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="079bb-371">Es wurde ein Problem behoben, bei dem externe Links beim Füllen (abwärts füllen, übergreifend füllen usw.) nicht aktualisiert wurden, wenn das Quellbuch geschlossen war.</span><span class="sxs-lookup"><span data-stu-id="079bb-371">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="079bb-372">Es wurde ein Problem behoben, bei dem Excel u. U. nicht mehr reagierte, nachdem STRG+UMSCHALT+Pfeiltasten zum Scrollen verwendet wurden, wenn das Excel-Fenster über Microsoft Teams gemeinsam genutzt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-372">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="079bb-373">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-373">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="079bb-374">Es wurde ein Problem behoben, bei dem die Eigenschaft "Wert wird überschnitten bei" auf der Diagrammachse unerwartet geändert wird, wenn Sie eine Datei speichern und erneut öffnen.</span><span class="sxs-lookup"><span data-stu-id="079bb-374">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="079bb-375">Es wurde ein Problem behoben, das dazu führte, dass CustomUI XML für eine benutzerdefinierte Multifunktionsleisten-Registerkarte beim Speichern in SharePoint/OneDrive entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-375">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="079bb-376">Die Leistung beim Löschen von Spalten mit verbundenen Zellen wurde verbessert.</span><span class="sxs-lookup"><span data-stu-id="079bb-376">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="079bb-377">Ein Problem wurde behoben, bei dem Druckernamen in der Liste der Drucker im Dialogfeld „Drucken“ wiederholt werden konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-377">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="079bb-378">Es wurde ein Problem behoben, bei dem die externe Verknüpfung nicht mehr funktioniert, nachdem die Datei erneut geöffnet wurde, wenn der Dateipfad zu lang ist.</span><span class="sxs-lookup"><span data-stu-id="079bb-378">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="079bb-379">Ein Problem mit der Skalierung von Kontrollkästchen in Formularsteuerelementen beim Drucken wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-379">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="079bb-380">Ein Absturz konnte auftreten, wenn versucht wurde, Änderungen mithilfe des Legacymodus "Freigegebene Arbeitsmappe" auf einem neuen Blatt für eine Arbeitsmappe aufzulisten.</span><span class="sxs-lookup"><span data-stu-id="079bb-380">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="079bb-381">Das Einfügen einer Spalte in eine gefilterte Liste dauert länger als erwartet.</span><span class="sxs-lookup"><span data-stu-id="079bb-381">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="079bb-382">Es wurde ein Problem behoben, bei dem einige kopierte und eingefügte Diagrammverknüpfungen zugeordnete Laufwerksadressen anstelle von Universaladressen verwendeten.</span><span class="sxs-lookup"><span data-stu-id="079bb-382">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="079bb-383">Es wurde ein Problem behoben, bei dem die Fehlermeldung „Diese Arbeitsmappe wird derzeit von einer anderen Arbeitsmappe referenziert und kann nicht geschlossen werden“ eingeblendet wurde, weil Add-Ins in alphabetischer Reihenfolge und nicht in einer vom Benutzer festgelegten Reihenfolge geladen wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-383">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="079bb-384">Es wurde ein Problem behoben, bei dem beim Klicken auf einen Hyperlink zu einer Stelle in einer bereits geöffneten Arbeitsmappe eine Arbeitsmappe ausgeblendet werden konnte.</span><span class="sxs-lookup"><span data-stu-id="079bb-384">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="079bb-385">Das Öffnen einer Arbeitsmappe mit Verweisen auf zahlreiche andere Arbeitsmappen, insbesondere mit ausgeblendeten Fenstern, würde langsamer als erwartet ablaufen.</span><span class="sxs-lookup"><span data-stu-id="079bb-385">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="079bb-386">Verwendung von „Application.Evaluate“ von VBA funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.</span><span class="sxs-lookup"><span data-stu-id="079bb-386">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="079bb-387">Es wurde ein Problem behoben, das bei einigen Benutzern mit verknüpften und eingebetteten Objekten (OLE) auftrat.</span><span class="sxs-lookup"><span data-stu-id="079bb-387">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="079bb-388">Nutzer können beim Speichern von Änderungen auf einen Fehler stoßen, wenn sie manche nicht englische Zeichensätze verwenden.</span><span class="sxs-lookup"><span data-stu-id="079bb-388">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="079bb-389">Dieses Update behebt ein Problem, das dazu führte, dass die Bearbeitungsleiste Text in einer anderen Schriftart als erwartet anzeigte.</span><span class="sxs-lookup"><span data-stu-id="079bb-389">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="079bb-390">Nutzer können beim Speichern von Änderungen auf einen Fehler stoßen, wenn sie manche nicht englische Zeichensätze verwenden.</span><span class="sxs-lookup"><span data-stu-id="079bb-390">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="079bb-391">Wir haben ein Problem gelöst, durch das das Auswählen einer Zelle nach dem Scrollen dazu führen konnte, dass die falsche Zelle ausgewählt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-391">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="079bb-392">Beim Zugriff auf einen verborgenen benannten Bereich kann ein Fehler auftreten.</span><span class="sxs-lookup"><span data-stu-id="079bb-392">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="079bb-393">Excel könnte ein Problem aufweisen, durch das das Bearbeiten einer geschützten Datei von einer nicht vertrauenswürdigen Netzwerkfreigabe zu einem Fehler in Excel geführt haben könnte.</span><span class="sxs-lookup"><span data-stu-id="079bb-393">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="079bb-394">Die Funktion "Text in Spalte" könnte bei einigen Lokalisierungen nicht funktionieren.</span><span class="sxs-lookup"><span data-stu-id="079bb-394">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="079bb-395">Es wurde ein Leistungsproblem beim Erstellen von Diagrammen aus Vorlagen behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-395">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="079bb-396">Es wurde ein Problem behoben, durch das bei einigen Benutzern Abstürze auftraten, wenn Text in Spalten mit Zellen mit einem übergelaufenem Array konvertiert wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-396">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="079bb-397">Die Verwendung von Range.Value und Range.Value2 (VBA) führt dazu, dass Formeln als dynamische Arrays eingegeben werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-397">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="079bb-398">Es wurde ein Problem behoben, bei dem ein @-Symbol, mit dem eine Formel beginnt, als impliziter Schnittmengenoperator betrachtet wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-398">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="079bb-399">Es wurde ein Problem behoben, bei dem Arbeitsblätter, die mehrere Formeln mit definierten Namen enthielten, zu längeren Zeiten beim Speichern von Dateien geführt haben.</span><span class="sxs-lookup"><span data-stu-id="079bb-399">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="079bb-400">Diese Änderung umgeht ein Problem mit bestimmten Intel-Grafiktreibern durch Verwendung des Softwarerenderings.</span><span class="sxs-lookup"><span data-stu-id="079bb-400">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="079bb-401">Behebt ein Problem, aufgrund dessen bei Benutzern Abstürze beim Umbenennen einer Signatur auftraten.</span><span class="sxs-lookup"><span data-stu-id="079bb-401">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="079bb-402">OneNote</span><span class="sxs-lookup"><span data-stu-id="079bb-402">OneNote</span></span>

- <span data-ttu-id="079bb-403">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehende Anpassung der Synchronisierungshäufigkeit in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="079bb-403">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="079bb-404">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehendes Zurückschieben des Downloads eingebetteter Dateien und Bilder in Online-Notizbücher, bis der Benutzer zu der Seite in OneNote 2016 navigiert.</span><span class="sxs-lookup"><span data-stu-id="079bb-404">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="079bb-405">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehende Deaktivierung des Papierkorbs in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="079bb-405">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="079bb-406">Wenn ein Benutzer versucht, die Daten zu löschen, die normalerweise in den Papierkorb verschoben werden, wird der Benutzer gefragt, ob er die Daten beibehalten oder dauerhaft löschen möchte.</span><span class="sxs-lookup"><span data-stu-id="079bb-406">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="079bb-407">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehendes Verringern der Anzahl und Häufigkeit der Synchronisierungen von Seiten des Versionsverlaufs in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="079bb-407">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="079bb-408">Zeigt eine Benachrichtigung an, durch die der Benutzer mehr über temporäre Maßnahmen erfahren kann, die in der OneNote-Benutzeroberfläche implementiert sind, um die Synchronisierungs- und Dienststabilität zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="079bb-408">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="079bb-409">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehende Reduzierung der maximal zulässigen Größe neuer eingebetteter Anhänge auf 50 MB in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="079bb-409">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="079bb-410">Bei Dateien, die dieses Limit überschreiten, haben Benutzer die Möglichkeit, die Datei auf OneDrive hochzuladen und einen Link in OneNote einzufügen.</span><span class="sxs-lookup"><span data-stu-id="079bb-410">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="079bb-411">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehende Deaktivierung der Videoaufzeichnung in der Anwendung in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="079bb-411">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="079bb-412">Lokale Notizbücher sind von dieser Maßnahme nicht betroffen.</span><span class="sxs-lookup"><span data-stu-id="079bb-412">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="079bb-413">Lokalisiert die Benachrichtigung, durch die der Benutzer mehr über temporäre Maßnahmen erfahren kann, die in der OneNote-Benutzeroberfläche implementiert sind, um die Synchronisierungs-und Dienststabilität zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="079bb-413">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="079bb-414">Outlook</span><span class="sxs-lookup"><span data-stu-id="079bb-414">Outlook</span></span>

- <span data-ttu-id="079bb-415">Es wurde ein Problem behoben, bei dem das IME-Fenster (Eingabemethoden-Editor) den zugrunde liegenden Text, der über den IME eingegeben wird, überlappte, wenn mehrere Monitore mit unterschiedlichen Auflösungen verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-415">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="079bb-416">Behebt ein Problem, das dazu führte, dass Benutzer gelegentlich Abstürze in Outlook erfahren haben.</span><span class="sxs-lookup"><span data-stu-id="079bb-416">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="079bb-417">Hiermit wird die Blockierungslogik für Anlagen in Outlook aktualisiert, um auch Python-Anlagen zu blockieren.</span><span class="sxs-lookup"><span data-stu-id="079bb-417">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="079bb-418">Behebt ein Problem, durch das Web-Add-Ins auf von Digital Rights Management verwaltete Nachrichten zugreifen konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-418">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="079bb-419">Behebt ein Problem, das bewirkte, dass bei einer bevorstehenden Änderung der Zeitzonendefinition Terminserien oder Besprechungen zur falschen Uhrzeit angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-419">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="079bb-420">Wenn Sie die Zeitzone für Brasilien im Jahr 2019 verwenden, werden Besprechungsserien und Termine in der falschen Zeitspanne für das Jahr 2020 angezeigt.</span><span class="sxs-lookup"><span data-stu-id="079bb-420">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="079bb-421">Diese Änderung ist für Kunden relevant, die sich in der Zeitzone von Brasilien befinden oder Besprechungen und Termine gebucht haben, die in dieser Zeitzone stattfinden.</span><span class="sxs-lookup"><span data-stu-id="079bb-421">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="079bb-422">Mit dieser Änderung kann Outlook bestimmte Zeitzoneneinstellungen außer Kraft setzen, die von Outlook verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-422">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="079bb-423">Um eine Zeitzonenaußerkraftsetzung aufzurufen, müssen Sie einen Registrierungsschlüssel für den aktuellen Benutzer festlegen.</span><span class="sxs-lookup"><span data-stu-id="079bb-423">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="079bb-424">Der Name des Registrierungsschlüssels muss mit dem internen Namen der Zeitzone übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="079bb-424">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="079bb-425">Der Wert gibt das Jahr der Zeitzonenregel an, die anstelle des aktuellen Jahres verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="079bb-425">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="079bb-426">Der folgende Registrierungsschlüssel-Außerkraftsetzungswert verwendet z. B. die Brasilia-Zeitzone für das Jahr 2020 als aktuelle Regel.</span><span class="sxs-lookup"><span data-stu-id="079bb-426">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="079bb-427">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span><span class="sxs-lookup"><span data-stu-id="079bb-427">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="079bb-428">South America Standard Time"=dword:000007e4.</span><span class="sxs-lookup"><span data-stu-id="079bb-428">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="079bb-429">Behebt ein Problem, das bewirkt hat, dass die Benutzer sahen, wie sich das Feld "Ort" in Besprechungen unerwartet ändert.</span><span class="sxs-lookup"><span data-stu-id="079bb-429">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="079bb-430">Behebt ein Problem, durch das das Feld "Ort" in Besprechungen unerwartet aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-430">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="079bb-431">Behebt ein Problem, bei dem der Standort einer Besprechung unerwartet nach dem Löschen wieder der Besprechung hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-431">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="079bb-432">Behebt ein Problem, das dazu führte, dass Kommas im Ortsfeld einer Besprechung in Semikolons umgewandelt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-432">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="079bb-433">Ermöglicht die Teilnahme an einer Teambesprechung direkt über den systemeigenen Teams-Client.</span><span class="sxs-lookup"><span data-stu-id="079bb-433">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="079bb-434">Behebt ein Problem, das bei Benutzern mit Postfächern auf Exchange 2010-Servern zu Problemen beim Hinzufügen von Anlagen zu Kalendereinträgen führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-434">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="079bb-435">Behebt ein Problem, durch das Benutzer Probleme beim Beantworten digital signierter Nachrichten hatten.</span><span class="sxs-lookup"><span data-stu-id="079bb-435">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="079bb-436">Behebt ein Problem, durch das Benutzer einige Instanzen von wiederkehrenden Kalenderelementen nicht öffnen konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-436">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="079bb-437">Behebt ein Problem, das dazu führte, dass die Kopfzeile einer Gruppe in einigen Szenarios unerwartet erweitert wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-437">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="079bb-438">Behebt ein Problem, bei dem die Breite des Ordnerbereichs unerwartet geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-438">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="079bb-439">Behebt ein Problem, bei dem Outlook die Datenschutzrichtlinie nicht aktiviert hat, um Tipps für Benutzer zu geben, die für den Dienst bezahlt haben und M365 Business Plus-Pläne nutzen.</span><span class="sxs-lookup"><span data-stu-id="079bb-439">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="079bb-440">Behebt ein Problem, durch das Benutzer mit einer spürbaren Verzögerung beim Interagieren mit ihren Postfachordnern über Tastenkombinationen konfrontiert waren.</span><span class="sxs-lookup"><span data-stu-id="079bb-440">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="079bb-441">Behebt ein Problem, das zu einem Absturz führen könnte, wenn dasselbe Element in mehreren Fenstern angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-441">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="079bb-442">Behebt ein Problem, das bewirkt, dass Benutzer die Nachricht "Die Regeln auf diesem Computer stimmen nicht mit den Regeln in Microsoft Exchange überein" sahen, wenn sie ihre Regeln in Outlook aktualisierten.</span><span class="sxs-lookup"><span data-stu-id="079bb-442">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="079bb-443">Behebt ein Problem, das einen Speicherverlust bei sehr langen Outlook-Sitzungen verursachte.</span><span class="sxs-lookup"><span data-stu-id="079bb-443">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="079bb-444">Behebt ein Problem, durch das Nutzer beim Angeben einer ungültigen Absenderadresse einen Absturz verursacht hat.</span><span class="sxs-lookup"><span data-stu-id="079bb-444">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="079bb-445">Behebt ein Problem, durch das Benutzern eine beim Öffnen des Dialogfelds "Regeln" die folgende Meldung "Die Regeln auf diesem Computer stimmen nicht mit den Regeln in Microsoft Exchange überein" angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-445">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="079bb-446">Behebt ein Problem, durch das die Option zum Deaktivieren der Hervorhebung markierter Elemente in einigen Szenarien nicht berücksichtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-446">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="079bb-447">Behebt ein Problem, durch das beim Drücken der Taste „S“ nach dem Schließen der Barrierefreiheitsprüfung unerwartet E-Mails gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-447">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="079bb-448">Behebt ein Problem, aufgrund dessen bei Benutzern Abstürze beim Umbenennen einer Signatur auftraten.</span><span class="sxs-lookup"><span data-stu-id="079bb-448">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="079bb-449">Behebt ein Problem, bei dem es durch das Abbrechen der Kontoeinrichtung einen Absturz gab.</span><span class="sxs-lookup"><span data-stu-id="079bb-449">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="079bb-450">Behebt ein Problem, das dazu führte, dass Outlook unerwartet alle E-Mails synchronisierte, selbst wenn der Synchronisierungsschieberegler auf eine kleinere Einstellung eingestellt ist.</span><span class="sxs-lookup"><span data-stu-id="079bb-450">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="079bb-451">Behebt ein Problem, das dazu führte, dass für Benutzer mit dem schwarzen Design die Dropdownliste “Von“ als weißer Text auf weißem Hintergrund angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-451">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="079bb-452">Behebt ein Problem, das während der Profilerstellung ein Absturz verursachte.</span><span class="sxs-lookup"><span data-stu-id="079bb-452">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="079bb-453">Behebt ein Problem, das bewirkt hat, dass Benutzer ein leeres Meldungsfeld mit einer "OK"-Schaltfläche angezeigt bekamen, wenn Sie versuchten, den Support über den Kontext der Kontoerstellung zu kontaktieren.</span><span class="sxs-lookup"><span data-stu-id="079bb-453">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="079bb-454">Behebt ein Problem, das bewirkt hat, dass Benutzer ein leeres Meldungsfeld mit einer "OK"-Schaltfläche angezeigt bekamen, wenn Sie versuchten, den Support über den Kontext der Kontoerstellung zu kontaktieren.</span><span class="sxs-lookup"><span data-stu-id="079bb-454">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="079bb-455">Behebt ein Problem, das bewirkt hatte, dass Anwendungen von Drittanbietern keine E-Mail-Nachrichten mehr senden konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-455">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="079bb-456">Behebt ein Problem, durch das gelegentlich Kategorien in E-Mail-Nachrichten nicht mehr aufschienen.</span><span class="sxs-lookup"><span data-stu-id="079bb-456">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="079bb-457">Behebt ein Problem, aufgrund dessen Outlook-Benutzern auf Serverbetriebssystemen die Fehlermeldung "Antivirenstatus: Ungültig" angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-457">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="079bb-458">Diese Version von Windows unterstützt die Erkennung von Antivirus, aber es wurde kein Antivirus gefunden, obwohl Antivirus korrekt konfiguriert war.</span><span class="sxs-lookup"><span data-stu-id="079bb-458">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="079bb-459">Behebt ein Problem, durch das Stellvertretungen auf unterschiedlichen Computern unterschiedliche Ordnerhierarchien für freigegebene Postfächer angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-459">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="079bb-460">Behebt ein Problem, durch das Stellvertretungen beim Bearbeiten eines vorhandenen Kalendertermins im Kalender eines Managers eine Fehlermeldung erhalten haben.</span><span class="sxs-lookup"><span data-stu-id="079bb-460">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="079bb-461">Behebt ein Problem, aufgrund dessen Benutzer mit der falschen Browseremulationseinstellung nicht die Authentifizierungsaufforderung für Gmail ausführen konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-461">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="079bb-462">Behebt ein Problem, bei dem die Option "Weiterleitung zulassen" in den "Antwortoptionen" für Kalenderbesprechungen nicht angezeigt wurde, wenn die Option für das Herunterladen freigegebener Ordner NICHT aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="079bb-462">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="079bb-463">Behebt ein Problem, das bewirkt, dass Benutzer beim Öffnen von .msg- und .oft-Dateien nach einem Windows-Update einen Absturz erfahren.</span><span class="sxs-lookup"><span data-stu-id="079bb-463">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="079bb-464">Behebt ein Problem, das gelegentlich zu einem Absturz führte, wenn Benutzer den X-Knopf ihrer Maus verwendeten.</span><span class="sxs-lookup"><span data-stu-id="079bb-464">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="079bb-465">Behebt ein Problem, bei dem es zu einem Absturz kam, wenn Benutzer bestimmte Suchergebnisse ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="079bb-465">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="079bb-466">Behebt ein Problem, das bewirkt hat, dass die Schaltfläche "In der Cloud speichern" in den Anlagentools fehlt.</span><span class="sxs-lookup"><span data-stu-id="079bb-466">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="079bb-467">Diese Änderung stellt die Fähigkeit wieder her, mehrzeilige Betreffzeilen im Nachrichtenkopf anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="079bb-467">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="079bb-468">Behebt ein Problem, durch das Benutzer einen Absturz erfahren, wenn zwei Add-Ins der gleichen Menübandgruppe eine Schaltfläche hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="079bb-468">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="079bb-469">Behebt ein Problem, das bewirkt, dass Links nicht zu E-Mails mit der richtigen standardmäßigen Mandantenberechtigung hinzugefügt werden können, wenn die standardmäßige Mandantenberechtigung als "jeder" konfiguriert ist.</span><span class="sxs-lookup"><span data-stu-id="079bb-469">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="079bb-470">Behebt ein Problem, aufgrund dessen Benutzer nicht in der Lage waren, E-Mails an eine persönliche Verteilerliste zu senden.</span><span class="sxs-lookup"><span data-stu-id="079bb-470">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="079bb-471">Behebt ein Problem, das dazu führte, dass Benutzer beim Weiterleiten großer HTML-Nachrichten den Nachrichtentext abgeschnitten sahen.</span><span class="sxs-lookup"><span data-stu-id="079bb-471">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="079bb-472">Es wurde ein Problem mit der Auswahl des SMIME-Algorithmus behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-472">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="079bb-473">Es wurde ein Problem behoben, durch das verhindert werden konnte, dass Dateien an einem WebDAV-Speicherort gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-473">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="079bb-474">Behebt ein Problem, das dazu führte, dass Benutzer OneDrive-Anlagen von außerhalb ihres Mandanten nicht auf ihrem lokalen Computer speichern konnten, wenn sie im Dialogfeld "Sicherheit" die Option "Speichern" wählten.</span><span class="sxs-lookup"><span data-stu-id="079bb-474">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="079bb-475">Behebt ein Problem, das bewirkt hatte, dass der Text einer NDR-Nachricht nach der Bearbeitung des Betreffs von Unicode in ASCII geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-475">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="079bb-476">Behebt ein Problem, durch das Benutzer einen Speicherverlust im Outlook-Prozess beobachten konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-476">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="079bb-477">Behebt ein Problem, durch das Benutzern unter bestimmten Umständen E-Mails angezeigt werden, die an eine Adresse gesendet wurden, die nicht mit der angezeigten SMTP-Adresse übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="079bb-477">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="079bb-478">Behebt ein Problem, das dazu führte, dass das Suchfeld im Modus mit hohem DPI-Wert nicht korrekt ausgerichtet war.</span><span class="sxs-lookup"><span data-stu-id="079bb-478">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="079bb-479">Behebt ein Problem, das dazu führte, dass Benutzer in Outlook beim Abrufen von Cloudeinstellungen hängen bleiben.</span><span class="sxs-lookup"><span data-stu-id="079bb-479">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="079bb-480">Behebt ein Problem, durch das die Such-Feedback-Umgebung zum Hängen gebracht wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-480">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="079bb-481">Behebt ein Problem, das dazu führte, dass Benutzer gelegentlich Abstürze in Outlook erfahren haben.</span><span class="sxs-lookup"><span data-stu-id="079bb-481">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="079bb-482">Behebt ein Problem, aufgrund dessen bei Benutzern Abstürze beim Umbenennen einer Signatur auftraten.</span><span class="sxs-lookup"><span data-stu-id="079bb-482">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="079bb-483">Behebt ein Problem, das während der Profilerstellung ein Absturz verursachte.</span><span class="sxs-lookup"><span data-stu-id="079bb-483">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="079bb-484">Behebt ein Problem, das dazu führte, dass Benutzer gelegentlich Abstürze in Outlook erfahren haben.</span><span class="sxs-lookup"><span data-stu-id="079bb-484">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="079bb-485">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="079bb-485">PowerPoint</span></span>

- <span data-ttu-id="079bb-486">Es wurde ein Problem behoben, das bei der Verwendung des Kontextmenüs in älteren PPT-Kommentaren zu einem Absturz führen könnte.</span><span class="sxs-lookup"><span data-stu-id="079bb-486">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="079bb-487">Verbessertes Szenario zum Kopieren und Einfügen: Das Kopieren der Form in eine PowerPoint-Folie und das Einfügen in eine andere Folie in einer Schleife schlägt möglicherweise mit Ausnahme fehl.</span><span class="sxs-lookup"><span data-stu-id="079bb-487">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="079bb-488">Behebt ein Problem mit der Weiterleitung von korrekten Nachrichten für Benutzer, die eine Kopie einer Datei mit verbesserten Kommentaren öffnen.</span><span class="sxs-lookup"><span data-stu-id="079bb-488">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="079bb-489">Project</span><span class="sxs-lookup"><span data-stu-id="079bb-489">Project</span></span>

- <span data-ttu-id="079bb-490">Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-490">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="079bb-491">Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.</span><span class="sxs-lookup"><span data-stu-id="079bb-491">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="079bb-492">Ein Problem wurde behoben, bei dem das Ereignis „ProjectBeforeTaskChange“ nicht erkannt wird, wenn ein Vorgang über die Schaltfläche „Deaktivieren“ deaktiviert/aktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-492">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="079bb-493">Ein Problem wurde behoben, bei dem Project beim Speichern von Projekten möglicherweise abstürzt, die mit älteren Project-Versionen erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-493">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="079bb-494">Wir haben ein Problem erkannt, bei dem Benutzer beim Öffnen eines schreibgeschützten Projekts mehrere Nachrichten erhalten könnten</span><span class="sxs-lookup"><span data-stu-id="079bb-494">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="079bb-495">Es wurde ein Problem behoben, bei dem 100% Aufgaben vom Typ „feste Dauer“ fälschlicherweise zu weniger als 100% erledigt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-495">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="079bb-496">Word</span><span class="sxs-lookup"><span data-stu-id="079bb-496">Word</span></span>

- <span data-ttu-id="079bb-497">Behebt ein Problem, das gelegentlich zu einem Absturz führte, wenn Benutzer den X-Knopf ihrer Maus verwendeten.</span><span class="sxs-lookup"><span data-stu-id="079bb-497">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="079bb-498">Es wurde ein Problem behoben, bei dem die Ausrichtung von Wörtern in einem Dokument durcheinandergebracht wurde, wenn Benutzer nach dem Drucken mit Schnelldruck versuchten, den Text zu bearbeiten.</span><span class="sxs-lookup"><span data-stu-id="079bb-498">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="079bb-499">Es wurde ein Problem mit der Anpassung von Text in einer Tabelle behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-499">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="079bb-500">Ein Problem wurde behoben, damit eingefügte horizontale Linien nicht kürzer und zentriert sind.</span><span class="sxs-lookup"><span data-stu-id="079bb-500">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="079bb-501">Im Organizer für Bausteine könnte eine ungültige Warnung angezeigt werden: “Sie haben modifizierte Formen, Bausteine“.</span><span class="sxs-lookup"><span data-stu-id="079bb-501">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="079bb-502">Es wurde ein Problem im Coautthoring behoben, wenn die Richtlinie "FileBlick\Word2007Files" aktiviert wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-502">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="079bb-503">Es wurde das Problem behoben, dass Word QuickPart beim Hinzufügen eines Suchfelds, das umbenannt wurde, nicht funktioniert.</span><span class="sxs-lookup"><span data-stu-id="079bb-503">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="079bb-504">Es wurde ein Problem beim Zusammenführen von zwei Dokumenten in ein Dokument behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-504">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="079bb-505">Es wurde ein Problem mit der compare-Funktion für Dokumente behoben, die für die Bearbeitung geschützt waren.</span><span class="sxs-lookup"><span data-stu-id="079bb-505">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="079bb-506">Dieses Update behebt ein Problem in Microsoft Word, bei dem Text, der länger als 255 Zeichen ist, während die Anwendung einer Vertraulichkeitskennzeichnung eingefügt wird, später nicht identifiziert und entfernt werden konnte, wenn die Kennzeichnungsrichtlinie eine Kopf- oder Fußzeile oder ein Wasserzeichen angewendet hat.</span><span class="sxs-lookup"><span data-stu-id="079bb-506">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="079bb-507">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="079bb-507">Office Suite</span></span>

- <span data-ttu-id="079bb-508">Ein Problem wurde behoben, bei dem Benutzer bei der gemeinsamen Erstellung von großen PowerPoint-Dateien übermäßige Netzwerk- und CPU-Auslastung erfahren können.</span><span class="sxs-lookup"><span data-stu-id="079bb-508">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="079bb-509">Diese Behebung soll sicherstellen, dass die Projektanwendung das Netzwerk nicht blockiert, wenn die Datei im Cache des Clients gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-509">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="079bb-510">Dieses Problem wurde behoben, indem die Kanalnamen in der Januar 2020-Verzweigung in der Backstage-Version auf die neuen Kanalnamen aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-510">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="079bb-511">Dieses Problem wurde behoben. Wenn ein Gerät nun mit Richtlinien verwaltet wird, wird nicht die DMS Audience-API aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="079bb-511">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="079bb-512">Es wurde ein Problem behoben, aufgrund dessen es beim Hinzufügen oder Entfernen von Apps in einer einzigen Transaktion zu einer unvollständigen Entfernung kam.</span><span class="sxs-lookup"><span data-stu-id="079bb-512">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="079bb-513">Ein Bug in der Einstellung des Stichtags für ODT- und GPO-Updates wurde behoben, bei dem der relative Stichtag nur beim ersten Festlegen funktionierte. Der Fix aktiviert den relativen Stichtag für spätere Updates.</span><span class="sxs-lookup"><span data-stu-id="079bb-513">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="079bb-514">Behebt ein Problem, bei dem Office-Aktualisierungen möglicherweise unerwartet Dateien aus dem Office CDN anstelle der beabsichtigten Quelle heruntergeladen haben, beispielsweise eine lokale oder Netzwerkfreigabe oder einen vom Configuration Manager bereitgestellten Speicherort.</span><span class="sxs-lookup"><span data-stu-id="079bb-514">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="079bb-515">Ein Bug in der Einstellung des Stichtags für ODT- und GPO-Updates wurde behoben, bei dem der relative Stichtag nur beim ersten Festlegen funktionierte. Der Fix aktiviert den relativen Stichtag für spätere Updates.</span><span class="sxs-lookup"><span data-stu-id="079bb-515">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="079bb-516">Ein neuer Sturz von AppV51 wurde zurückportiert, um eine Regression im vorherigen AppV51 zu beheben.</span><span class="sxs-lookup"><span data-stu-id="079bb-516">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="079bb-517">Das Problem wurde behoben, bei dem ein interner Vorgang bei einem Fehler eine Ausnahme ausgelöst hat, anstatt diesen zu protokollieren und fortzufahren.</span><span class="sxs-lookup"><span data-stu-id="079bb-517">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="079bb-518">Die betroffenen Benutzer werden nicht mehr daran gehindert, Updates zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="079bb-518">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="079bb-519">Unser Team hat Clientunterstützung für die Berichterstellungstelemetrie in den Office CDN-Domänen im halbjährlichen Enterprise Preview hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="079bb-519">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="079bb-520">Diese Änderung behebt gemeldete Probleme mit Grafikadaptern, die die integrierte Intel-GPU nutzen.</span><span class="sxs-lookup"><span data-stu-id="079bb-520">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="079bb-521">Dadurch wird sichergestellt, dass skizzierte Konturen im Menüband ordnungsgemäß funktionieren.</span><span class="sxs-lookup"><span data-stu-id="079bb-521">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="079bb-522">Es wurde ein Problem beim Öffnen von Dateien von lokalen Standorten aus mit einigen bestimmten Proxykonfigurationen behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-522">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="079bb-523">Dieses Update behebt ein Problem in Visual Basic for Applications in Microsoft Office, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung beim Laden als fehlerhaft angesehen werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-523">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="079bb-524">Es wurde ein Problem behoben, durch das Abstürze während der Office-Übergabesitzungen eliminiert, und es wurde die Zuverlässigkeit der Benutzeroberfläche erhöht.</span><span class="sxs-lookup"><span data-stu-id="079bb-524">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="079bb-525">Dieser Fehler aktualisiert den Enhanced Configuration Service (ECS).</span><span class="sxs-lookup"><span data-stu-id="079bb-525">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="079bb-526">Das Aufrufen von diesem neueren Endpunkt aus hat eine höhere Erfolgsrate für den Abruf aus ECS.</span><span class="sxs-lookup"><span data-stu-id="079bb-526">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="079bb-527">Dieses Update behebt ein Problem, bei dem Microsoft Outlook beim Anzeigen oder Verfassen von Nachrichten nicht die aktuelle Vertraulichkeitskennzeichnung anzeigt.</span><span class="sxs-lookup"><span data-stu-id="079bb-527">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="079bb-528">Behebt ein Problem, das dazu geführt hat, dass beim Öffnen mehrerer Dokumente in Word/Excel/PowerPoint aus derselben SharePoint-Bibliothek lediglich das erste geöffnete Dokument auf Richtlinienkonformität gescannt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-528">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="079bb-529">Um die Sicherheit der Office-Kunden zu schützen, sind jetzt Microsoft Office-Updates ausschließlich mit dem SHA-2-Algorithmus signiert.</span><span class="sxs-lookup"><span data-stu-id="079bb-529">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="079bb-530">Der Office-Host stürzte in Fenstern ab, wenn ein Add-In aktiviert wird, während der Registrierungsschlüssel HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth auf Null festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="079bb-530">The office host was crashing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="079bb-531">Mit dieser Änderung wird dieses Problem behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-531">This change would fix this issue.</span></span>

- <span data-ttu-id="079bb-532">Es wurde ein Absturzproblem mit dem Office-Host in Windows behoben, das auftrat, wenn ein Add-In aktiviert wurde, während der Registrierungswert TabProcGrowth den REG_SZ-Typ aufwies.</span><span class="sxs-lookup"><span data-stu-id="079bb-532">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="079bb-533">Durch das Update wird ein Problem in Microsoft Office behoben, bei dem Visual Basic for Applications-Projekte mit Referenzen, die bei der Suche nach in der PATH-Umgebungsvariable angegebenen Speicherorten gefunden werden sollten, zur Laufzeit u. U. nicht richtig gefunden werden, was zu VBA-Laufzeitfehlern führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-533">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="079bb-534">Es wurde ein Problem behoben, bei dem Access und Publisher nicht ordnungsgemäß gestartet werden, je nachdem, welche Sprachen installiert wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-534">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)





[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1908-july-14"></a><span data-ttu-id="079bb-537">Version 1908: 14. Juli</span><span class="sxs-lookup"><span data-stu-id="079bb-537">Version 1908: July 14</span></span>
<span data-ttu-id="079bb-538">*Version 1908 (Build 11929.20904)*</span><span class="sxs-lookup"><span data-stu-id="079bb-538">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="079bb-539">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-539">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="079bb-541">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-541">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="079bb-542">Access</span><span class="sxs-lookup"><span data-stu-id="079bb-542">Access</span></span>

- <span data-ttu-id="079bb-543">Mit diesem Update wird ein Problem behoben, durch das bei einem Aggregat wie "Summe" das Ergebnis auf einen ganzzahligen Wert abgeschnitten werden kann.</span><span class="sxs-lookup"><span data-stu-id="079bb-543">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="079bb-544">Mit diesem Update wird ein Problem behoben, bei dem eine Union-Abfrage, die Verweise auf Remotetabellen enthält (z. B. SQL Server-Tabellen) möglicherweise dazu führt, dass Access geschlossen und neu gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-544">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="079bb-545">Mit diesem Update wird ein Problem in Microsoft Access behoben, das den Fehler "Abfrage ist beschädigt" verursachen kann, wenn eine Aktualisierungsabfrage ausgeführt oder eine UPDATE-Anweisung in SQL verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-545">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="079bb-546">Excel</span><span class="sxs-lookup"><span data-stu-id="079bb-546">Excel</span></span>

- <span data-ttu-id="079bb-547">Die Niederländische Tastenkombination für Dokumenttitel wurde in Alt-G geändert.</span><span class="sxs-lookup"><span data-stu-id="079bb-547">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="079bb-548">Es wurde ein Problem in Excel behoben, bei dem Makros, die Shapes oder Steuerelementen zugeordnet sind, möglicherweise eine falsche Fehlermeldung anzeigen oder an falschen Zielbereichen arbeiten.</span><span class="sxs-lookup"><span data-stu-id="079bb-548">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="079bb-549">Es wurde ein Problem mit "Suchen und ersetzen" gelöst, durch das sich die Position des Fokus im Dialogfeld änderte, nachdem das erste Element gefunden wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-549">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="079bb-550">Hiermit wird ein Problem behoben, durch das die Änderung der Sortierung einer PivotTable und deren Aktualisierung während der gemeinsamen Dokumenterstellung mit anderen Benutzern zu einem Absturz führen kann.</span><span class="sxs-lookup"><span data-stu-id="079bb-550">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="079bb-551">Ein Problem wurde behoben, bei dem der Filter für eine OLAP-PivotTable auf einen Wert festgelegt wurde, der aus dem Cube entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-551">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="079bb-552">Dieses Update behebt ein Problem, das dazu führte, dass ein Fehler auftrat, wenn VBA zum Hinzufügen eines Bildes zur Kopf-/Fußzeile eines Diagramms verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-552">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="079bb-553">Es wurde ein Problem behoben, durch das Punkt-Linien-Diagramme beim Ändern der Reihensammlung nicht ordnungsgemäß dargestellt werden konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-553">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="079bb-554">Es wurde ein Problem mit Farben behoben, die in der Vorschau beim Einfügen von Diagrammen mithilfe von Diagrammvorlagen verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-554">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="079bb-555">Ein Problem wurde behoben, durch das Wasserfall- und Trichterdiagramme beim Einfügen oder Löschen von Zellen nicht mehr mit Tabellen synchronisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-555">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="079bb-556">Ein Konflikt beim Zusammenführen in Excel wurde behoben, durch den Benutzer aufgefordert wurden, die Arbeitsmappe erneut zu öffnen, um die Änderungen zu übernehmen.</span><span class="sxs-lookup"><span data-stu-id="079bb-556">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="079bb-557">Ein Problem wurde behoben, durch das ein Makro-Laufzeitfehler beim Aktivieren minimierter Fenster verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-557">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="079bb-558">Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-558">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="079bb-559">Ein Problem wurde behoben, durch das Ausschneide- und Einfügevorgänge neben einer Tabelle fehlschlugen, wenn die gemeinsame Dokumenterstellung zusammen mit anderen Benutzern durchgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-559">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="079bb-560">Ein Problem wurde gelöst, das bei Änderung von benutzerdefinierten Eigenschaften von ausgeführten Makros zu Unterbrechungen bei der gemeinsamen Dokumentenerstellung führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-560">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="079bb-561">Es gab ein Problem, bei dem Sie keine Elemente aus dem Kombinationsfeld eines WPF-Formulars (Windows Presentation Foundation) auswählen konnten, das von einem Add-n geöffnet wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-561">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="079bb-562">Es wurde ein Problem behoben, das bei der Suche nach zuletzt verwendeten Dateien zu einem Absturz geführt hat, wenn keine Arbeitsmappe geöffnet ist.</span><span class="sxs-lookup"><span data-stu-id="079bb-562">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="079bb-563">Es wurde ein Problem behoben, bei dem der Rand eines Gruppenfeld-Steuerelements in der Druckvorschau oder beim Drucken nicht sichtbar war.</span><span class="sxs-lookup"><span data-stu-id="079bb-563">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="079bb-564">Es wurde ein Problem behoben, durch das einigen Benutzern mehrere Popupfenster angezeigt wurden, wenn externe Links in der Arbeitsmappe vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="079bb-564">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="079bb-565">Es wurde ein Leistungsproblem behoben, das möglicherweise bei der Verwendung eines VBA-Makros zum Löschen des Inhalts eines Bereichs aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="079bb-565">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="079bb-566">Es wurde ein Problem mit VBA behoben, bei dem das Schreiben von Werten in einem Wertebereich langsamer als erwartet war.</span><span class="sxs-lookup"><span data-stu-id="079bb-566">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="079bb-567">Es wurde ein Problem behoben, bei dem die Eigenschaft "Wert wird überschnitten bei" auf der Diagrammachse unerwartet geändert wird, wenn Sie eine Datei speichern und erneut öffnen.</span><span class="sxs-lookup"><span data-stu-id="079bb-567">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="079bb-568">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-568">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="079bb-569">Es wurde ein Problem behoben, das beim Löschen von Spalten mit verbundenen Zellen zu einer verlangsamten Leistung führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-569">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="079bb-570">Es wurde ein Problem beim Skalieren von Text in Steuerelementen von Formularen beim Anzeigen in der Druckansicht behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-570">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="079bb-571">Beim Kopieren von nach Farbe gefilterten Daten in eine Spalte mit einer anderen Breite wurden die Werte nicht eingefügt.</span><span class="sxs-lookup"><span data-stu-id="079bb-571">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="079bb-572">Es wurde ein Problem behoben, bei dem Excel u. U. nicht mehr reagierte, nachdem STRG+UMSCHALT+Pfeiltasten zum Scrollen verwendet wurden, wenn das Excel-Fenster über Microsoft Teams gemeinsam genutzt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-572">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="079bb-573">Ein Problem mit der Skalierung von Kontrollkästchen in Formularsteuerelementen beim Drucken wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-573">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="079bb-574">Es wurde ein Problem behoben, bei dem das Klicken auf eine mit einem Lesezeichen versehene Verknüpfung innerhalb derselben Arbeitsmappe dazu führte, dass die Arbeitsmappe ausgeblendet wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-574">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="079bb-575">Ein Absturz konnte auftreten, wenn versucht wurde, Änderungen mithilfe des Legacymodus "Freigegebene Arbeitsmappe" auf einem neuen Blatt für eine Arbeitsmappe aufzulisten.</span><span class="sxs-lookup"><span data-stu-id="079bb-575">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="079bb-576">Die Funktion "Text in Spalte" funktioniert bei einigen Gebietsschemas möglicherweise nicht.</span><span class="sxs-lookup"><span data-stu-id="079bb-576">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="079bb-577">Beim Zugriff auf einen verborgenen benannten Bereich kann ein Fehler auftreten.</span><span class="sxs-lookup"><span data-stu-id="079bb-577">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="079bb-578">Nutzer können beim Speichern von Änderungen auf einen Fehler stoßen, wenn sie manche nicht englische Zeichensätze verwenden.</span><span class="sxs-lookup"><span data-stu-id="079bb-578">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="079bb-579">Es wurde ein Problem behoben, durch das die Dateigröße von Bildern in Diagrammkopfzeilen beim Speichern der Arbeitsmappe mit dem Diagramm zunahm.</span><span class="sxs-lookup"><span data-stu-id="079bb-579">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="079bb-580">Ein Leistungsproblem mit asynchronen benutzerdefinierten Funktionen, das deren synchrone Ausführung zur Folge hatte.</span><span class="sxs-lookup"><span data-stu-id="079bb-580">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="079bb-581">Erhebliche Verbesserungen der Leistung beim Löschen von Spalten mit verbundenen Zellen.</span><span class="sxs-lookup"><span data-stu-id="079bb-581">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="079bb-582">Wir haben ein Problem gelöst, durch das das Auswählen einer Zelle nach dem Scrollen dazu führen konnte, dass die falsche Zelle ausgewählt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-582">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="079bb-583">Ein Problem wurde behoben, bei dem die Verweis-Funktion einen Fehler zurückgeben kann.</span><span class="sxs-lookup"><span data-stu-id="079bb-583">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="079bb-584">Es wurde ein Problem behoben, das zur Beschädigung von DBCS-Zeichen in Büchern mit Querverweisen führte, indem die Auswahlbereiche mit dem Buch mit Querverweisen synchronisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-584">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="079bb-585">Es wurde ein Problem behoben, das dazu führen konnte, dass Kontrollkästchen bei Verwendung der automatischen Anpassung zum Anpassen der Zeilenhöhe verkleinert wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-585">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="079bb-586">Problem mit langsamer Leistung beim Klicken auf die Schaltfläche "Schriftfarbe", wenn eine Datei über eine umfangreiche bedingte Formatierung verfügt.</span><span class="sxs-lookup"><span data-stu-id="079bb-586">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="079bb-587">Ein Problem wurde behoben, bei dem der Druckbereich in der Seitenansicht nicht korrekt war.</span><span class="sxs-lookup"><span data-stu-id="079bb-587">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="079bb-588">Excel könnte ein Problem aufweisen, durch das das Bearbeiten einer geschützten Datei von einer nicht vertrauenswürdigen Netzwerkfreigabe zu einem Fehler in Excel geführt haben könnte.</span><span class="sxs-lookup"><span data-stu-id="079bb-588">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="079bb-589">Die Leistung der Filterung nach Farbe wurde deutlich verbessert.</span><span class="sxs-lookup"><span data-stu-id="079bb-589">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="079bb-590">Ein Problem wurde behoben, das beim Öffnen von in früheren Versionen von Office erstellten Arbeitsmappen in aktuellen Versionen von Office zu Programmabstürzen von Excel führen konnte.</span><span class="sxs-lookup"><span data-stu-id="079bb-590">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="079bb-591">Mehr als 16 Add-Ins wurden aktiviert, die angezeigt werden, wenn der Add-In-Manager durchsucht wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-591">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="079bb-592">Ein Problem wurde behoben, durch das Links in bestimmte geschützte Blätter nicht eingefügt werden konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-592">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="079bb-593">Diese Änderung umgeht ein Problem mit bestimmten Intel-Grafiktreibern durch Verwendung des Softwarerenderings.</span><span class="sxs-lookup"><span data-stu-id="079bb-593">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="079bb-594">Die Links von cid:-Bildern aus Outlook-Nachrichten können nun auf Anforderung erfolgreich unterbrochen werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-594">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="079bb-595">Mit diesem Update wird ein Fehler behoben, der dazu führen kann, dass Office-Dokumente nicht auf OneDrive for Business hochgeladen werden können und die Fehlermeldung "Upload fehlgeschlagen" angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-595">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="079bb-596">Problem im Feature "Excel-Ideen" behoben: Ein Fehler trat auf, wenn das Add-In durch Klicken auf die Schaltfläche "Ideen" im Win32-Client geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-596">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="079bb-597">OneNote</span><span class="sxs-lookup"><span data-stu-id="079bb-597">OneNote</span></span>

- <span data-ttu-id="079bb-598">Lokalisiert die Benachrichtigung, durch die der Benutzer mehr über temporäre Maßnahmen erfahren kann, die in der OneNote-Benutzeroberfläche implementiert sind, um die Synchronisierungs-und Dienststabilität zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="079bb-598">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="079bb-599">Outlook</span><span class="sxs-lookup"><span data-stu-id="079bb-599">Outlook</span></span>

- <span data-ttu-id="079bb-600">Die Links von cid:-Bildern aus Outlook-Nachrichten können nun auf Anforderung erfolgreich unterbrochen werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-600">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="079bb-601">Ein Problem wurde behoben, das dazu führte, dass bei Benutzern, die Ihr Postfach von Standard- auf moderne Authentifizierung aktualisiert hatten, das falschen Konto mit ihrem Outlook-Profil verknüpft wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-601">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="079bb-602">Behebt ein Problem, durch das Web-Add-Ins auf von Digital Rights Management verwaltete Nachrichten zugreifen konnten, wenn dies nicht möglich sein sollte.</span><span class="sxs-lookup"><span data-stu-id="079bb-602">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="079bb-603">Behebt ein Problem, das bewirkt hat, dass die URL für den einfachen Mauszeiger bei einigen Safelinks nicht angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-603">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="079bb-604">Hiermit wird die Blockierungslogik für Anlagen in Outlook aktualisiert, um auch Python-Anlagen zu blockieren.</span><span class="sxs-lookup"><span data-stu-id="079bb-604">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="079bb-605">Behebt ein Problem, das bewirkt, dass einer Teilmenge von POP3-Benutzern alle E-Mails im nur-Text-Format anzeigt werden, und zwar unabhängig von den Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="079bb-605">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="079bb-606">Mit diesem Fix wird die Anzeige der HTML-formatierten Nachrichten wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="079bb-606">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="079bb-607">Behebt ein Problem, durch das Benutzern beim Kopieren von Elementen aus Ihrem primären Kalender in einen Gruppenkalender ein Berechtigungsfehler angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-607">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="079bb-608">Behebt ein Problem, bei dem Benutzer nicht in der Lage waren, über eine Sprachausgabe auf Standortvorschläge zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="079bb-608">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="079bb-609">Behebt ein Problem, durch das Benutzer mit einer spürbaren Verzögerung beim Interagieren mit ihren Postfachordnern über Tastenkombinationen konfrontiert waren.</span><span class="sxs-lookup"><span data-stu-id="079bb-609">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="079bb-610">Behebt ein Problem, das einen Speicherverlust bei sehr langen Outlook-Sitzungen verursachte.</span><span class="sxs-lookup"><span data-stu-id="079bb-610">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="079bb-611">Behebt ein Problem, durch das Nutzer beim Angeben einer ungültigen Absenderadresse einen Absturz verursacht hat.</span><span class="sxs-lookup"><span data-stu-id="079bb-611">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="079bb-612">Behebt ein Problem, durch das Benutzern eine beim Öffnen des Dialogfelds "Regeln" die folgende Meldung "Die Regeln auf diesem Computer stimmen nicht mit den Regeln in Microsoft Exchange überein" angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-612">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="079bb-613">Behebt ein Problem, das bei der Interaktion mit bestimmten Safelinks in Outlook zu einem Absturz führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-613">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="079bb-614">Behebt ein Problem, das für Vorgesetzte Unklarheit darüber verursacht hat, ob eine Stellvertretung bereits auf eine bestimmte Besprechungsanfrage geantwortet hat.</span><span class="sxs-lookup"><span data-stu-id="079bb-614">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="079bb-615">Behebt ein Problem, das bei der Verarbeitung von Antworten der AutoErmittlung zu einem Absturz führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-615">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="079bb-616">Behebt ein Problem, das bewirkt hat, dass Benutzer ein leeres Meldungsfeld mit einer "OK"-Schaltfläche angezeigt bekamen, wenn Sie versuchten, den Support über den Kontext der Kontoerstellung zu kontaktieren.</span><span class="sxs-lookup"><span data-stu-id="079bb-616">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="079bb-617">Diese Änderung ermöglicht es Administratoren, eine Richtlinie zu aktivieren, um in den Eingabeaufforderungen der AutoErmittlung-Authentifizierung die bereitgestellten E-Mail-Konten vor UPN zu bevorzugen.</span><span class="sxs-lookup"><span data-stu-id="079bb-617">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="079bb-618">Standardmäßig bevorzugt AutoErmittlung den UPN des Kontos, wenn dieser verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="079bb-618">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="079bb-619">Behebt ein Problem, durch das Benutzern Fehler beim Durchsuchen moderner Gruppen angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-619">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="079bb-620">Behebt ein Problem, das dazu führte, dass Outlook-Benutzer in bestimmten Szenarien im Zustand " Kennwort erforderlich " stecken geblieben sind.</span><span class="sxs-lookup"><span data-stu-id="079bb-620">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="079bb-621">Behebt ein Problem, bei dem Benutzer bei der Verarbeitung von Konfliktnachrichten Synchronisierungsfehler hatten.</span><span class="sxs-lookup"><span data-stu-id="079bb-621">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="079bb-622">Behebt ein Problem, das dazu führte, dass Benutzer beim Öffnen von MSG- und OFT-Dateien nach der Anwendung eines kürzlich durchgeführten Windows-Updates einen Absturz erlebten.</span><span class="sxs-lookup"><span data-stu-id="079bb-622">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="079bb-623">Behebt ein Problem, bei dem Benutzer beim Starten von Outlook beim Laden des Profils auf dem Bildschirm "Laden von Profilen" hängen blieben.</span><span class="sxs-lookup"><span data-stu-id="079bb-623">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="079bb-624">Behebt ein Problem, bei dem es zu einem Absturz kam, wenn Benutzer bestimmte Suchergebnisse ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="079bb-624">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="079bb-625">Behebt ein Problem, das bewirkt hat, dass die Schaltfläche "In der Cloud speichern" in den Anlagentools fehlt.</span><span class="sxs-lookup"><span data-stu-id="079bb-625">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="079bb-626">Standardmäßig zeigen die Etiketten der Aufbewahrungsrichtlinien die Aufbewahrungszeitspanne in Klammern an.</span><span class="sxs-lookup"><span data-stu-id="079bb-626">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="079bb-627">Dadurch wird ein Registrierungsschlüssel bereitgestellt, mit dem Administratoren festlegen können, dass nur der Name der Richtlinie angezeigt werden soll.</span><span class="sxs-lookup"><span data-stu-id="079bb-627">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="079bb-628">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span><span class="sxs-lookup"><span data-stu-id="079bb-628">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="079bb-629">Behebt ein Problem, bei dem es durch das Herunterfahren von Outlook zu einem Absturz kam.</span><span class="sxs-lookup"><span data-stu-id="079bb-629">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="079bb-630">Behebt ein Problem, durch das Kunden in einigen Szenarios eine leere Raumliste zu sehen bekamen.</span><span class="sxs-lookup"><span data-stu-id="079bb-630">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="079bb-631">Behebt ein Problem, durch das Benutzer beim Ändern von Ansichten zeitweise Abstürze sehen konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-631">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="079bb-632">Behebt ein Problem, bei dem Nutzer Probleme mit der Synchronisierung freigegebener Kalenderordner mit dem OST hatten, was zu Berechtigungsfehlern führte, wenn sie versuchten, mit diesen Ordnern zu interagieren.</span><span class="sxs-lookup"><span data-stu-id="079bb-632">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="079bb-633">Behebt ein Problem, das dazu geführt hat, dass Benutzer beim Anzeigen von mehr als 30 Kalendern in einer Citrix-Umgebung einen Absturz erlebt haben.</span><span class="sxs-lookup"><span data-stu-id="079bb-633">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="079bb-634">Hier finden Sie die einzelne [KB, in der dies für frühere Versionen dokumentiert wurde](https://support.microsoft.com/de-DE/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span><span class="sxs-lookup"><span data-stu-id="079bb-634">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/de-DE/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="079bb-635">Behebt ein Problem mit der Auswahl des SMIME-Algorithmus.</span><span class="sxs-lookup"><span data-stu-id="079bb-635">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="079bb-636">Behebt ein Problem, bei dem Richtlinientipps bei Verwendung eines alternativen Absenders nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-636">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="079bb-637">Behebt ein Problem, bei dem Benutzer Raumvorschläge für Besprechungen, die außerhalb der Verfügbarkeitszeiten dieses Raums stattfanden, einsehen konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-637">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="079bb-638">Ein Problem für nicht englischsprachige Benutzer wurde behoben, bei dem die Betreffzeile in einer E-Mail unglaublich klein war.</span><span class="sxs-lookup"><span data-stu-id="079bb-638">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="079bb-639">Behebt ein Problem, das einen Absturz verursachte, wenn Benutzer versuchten, aus einer "Verpasste Unterhaltung"-Nachricht heraus eine Regel zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="079bb-639">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="079bb-640">Behebung eines Problems, durch das bei einigen Benutzern beim Hinzufügen eines sekundären Exchange-Kontos doppelte Sonderordner angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-640">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="079bb-641">Behebt ein Problem, das dazu führte, dass Benutzer beim Weiterleiten großer HTML-Nachrichten den Nachrichtentext abgeschnitten sahen.</span><span class="sxs-lookup"><span data-stu-id="079bb-641">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="079bb-642">Behebt ein Problem, durch das Benutzer einen Speicherverlust im Outlook-Prozess beobachten konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-642">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="079bb-643">Behebt ein Problem, das zu sporadischen Abstürzen führte, wenn Benutzer ihre Anwesenheitsinformationen aktualisierten.</span><span class="sxs-lookup"><span data-stu-id="079bb-643">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="079bb-644">Behebt ein Problem, das bewirkt, dass die aktuelle Ordnersuche zweitweise fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="079bb-644">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="079bb-645">Behebt ein Problem, bei dem einige Benutzer beim Versuch, ihre Cloud-Einstellungen für Outlook abzurufen, auf Authentifizierungsfehler stießen.</span><span class="sxs-lookup"><span data-stu-id="079bb-645">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="079bb-646">Behebt ein Problem, durch das die Such-Feedback-Umgebung zum Hängen gebracht wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-646">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="079bb-647">Behebt ein Problem, das bei der Verarbeitung von Antworten der AutoErmittlung zu einem Absturz führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-647">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="079bb-648">Behebt ein Problem, das zu sporadischen Abstürzen führte, wenn Benutzer ihre Anwesenheitsinformationen aktualisierten.</span><span class="sxs-lookup"><span data-stu-id="079bb-648">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="079bb-649">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="079bb-649">PowerPoint</span></span>

- <span data-ttu-id="079bb-650">Die Links von cid:-Bildern aus Outlook-Nachrichten können nun auf Anforderung erfolgreich unterbrochen werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-650">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="079bb-651">Diese Änderung stellt den barrierefreien Namen für PowerPoint-Videosteuerelemente wieder her.</span><span class="sxs-lookup"><span data-stu-id="079bb-651">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="079bb-652">Es wurde ein Problem behoben, durch das verhindert wurde, dass einige Animationen gestartet werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-652">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="079bb-653">Ein Problem wurde behoben, durch das beim Kopieren einer Folie aus einer Präsentation in eine andere möglicherweise doppelte Master erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-653">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="079bb-654">Verbessertes Szenario zum Kopieren und Einfügen: Das Kopieren der Form in eine PowerPoint-Folie und das Einfügen in eine andere Folie in einer Schleife schlägt möglicherweise mit Ausnahme fehl.</span><span class="sxs-lookup"><span data-stu-id="079bb-654">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="079bb-655">Ein Problem mit dem Textmarker wurde behoben: Weißer Text mit dunkleren Textmarkerfarben wurde Schwarz mit Graustufen gedruckt.</span><span class="sxs-lookup"><span data-stu-id="079bb-655">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="079bb-656">Bei Dateien mit neuen modernen Kommentaren wird eine gelbe Warnung angezeigt, wenn sie in einer nicht unterstützten Version geöffnet werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-656">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="079bb-657">Es wurde ein Problem behoben, das zu einer langsameren Leistung zwischen Nutzern, die zusammenarbeiten, führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-657">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="079bb-658">Zuverlässigkeitsfix: Ein Problem wurde behoben, bei ein Add-In von Drittanbietern zu einem Absturz von PowerPoint führen konnte.</span><span class="sxs-lookup"><span data-stu-id="079bb-658">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="079bb-659">Es wurde ein Problem behoben, das auftreten konnte, wenn eine Datei, die inkrementell geöffnet wurde, eine Folie mit mehr als einem eingebetteten Mediendatenstrom enthielt.</span><span class="sxs-lookup"><span data-stu-id="079bb-659">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="079bb-660">Ein Problem mit der Shape.Paste-Methode wurde behoben: Wenn der Benutzer die Form mit der Shape.Paste-Methode kopiert und einfügt, wird die Auswahl in die eingefügte Form geändert.</span><span class="sxs-lookup"><span data-stu-id="079bb-660">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="079bb-661">Wir haben ein Problem behoben, bei dem beim ersten Start von PowerPoint möglicherweise keine Sicherheitswarnmeldung für nicht vertrauenswürdige Add-Ins angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-661">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="079bb-662">Ein Problem wurde behoben, bei dem einige Add-Ins unerwartete Fehler bei Formen in Diagrammen verursachen konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-662">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="079bb-663">Verhindert, dass für PowerPoint-Benutzer bei Onlinepräsentationen Fehler auftreten.</span><span class="sxs-lookup"><span data-stu-id="079bb-663">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="079bb-664">Project</span><span class="sxs-lookup"><span data-stu-id="079bb-664">Project</span></span>

- <span data-ttu-id="079bb-665">Ein Problem wurde behoben, durch das Benutzer unter Windows 7 Projekte aus Project Web-App und SharePoint-Websites öffnen können.</span><span class="sxs-lookup"><span data-stu-id="079bb-665">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="079bb-666">Ein Problem wurde identifiziert, bei dem Benutzer beim Öffnen eines schreibgeschützten Projekts möglicherweise mehrere Meldungen erhielten.</span><span class="sxs-lookup"><span data-stu-id="079bb-666">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="079bb-667">Der Befehl "Alles abgleichen" löst eine Ressourcenüberlastung nicht richtig auf.</span><span class="sxs-lookup"><span data-stu-id="079bb-667">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="079bb-668">Bei einer Aufgabe mit keiner Arbeit an einem Vorgang kann der Vorgang möglicherweise nicht als erledigt gekennzeichnet werden und wird stets bei 99 % angezeigt.</span><span class="sxs-lookup"><span data-stu-id="079bb-668">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="079bb-669">Es wurde ein Problem behoben, bei dem die tatsächliche Arbeit zwischen Arbeitszeittabelle und Projektplan unterschiedlich sein kann, da Ressourcenkalender nicht aktualisiert werden, wenn sich der Basiskalender ändert.</span><span class="sxs-lookup"><span data-stu-id="079bb-669">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="079bb-670">Skype</span><span class="sxs-lookup"><span data-stu-id="079bb-670">Skype</span></span>

- <span data-ttu-id="079bb-671">Problembehebung betreffend den Titelname für die Unterhaltungsregisterkarten, während mehrere Unterhaltungen stattfinden.</span><span class="sxs-lookup"><span data-stu-id="079bb-671">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="079bb-672">Visio</span><span class="sxs-lookup"><span data-stu-id="079bb-672">Visio</span></span>

- <span data-ttu-id="079bb-673">Das Exportieren als SVG aus Visio funktionierte für eine Vielzahl von Shapes nicht.</span><span class="sxs-lookup"><span data-stu-id="079bb-673">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="079bb-674">Word</span><span class="sxs-lookup"><span data-stu-id="079bb-674">Word</span></span>

- <span data-ttu-id="079bb-675">Die Links von cid:-Bildern aus Outlook-Nachrichten können nun auf Anforderung erfolgreich unterbrochen werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-675">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="079bb-676">Es wurde ein Problem behoben, das zu Skalierungsproblemen führte, wenn auf Deskjet-Druckern gedruckt wurde</span><span class="sxs-lookup"><span data-stu-id="079bb-676">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="079bb-677">Es wurde ein Problem mit der Anpassung von Text in einer Tabelle behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-677">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="079bb-678">Ein Problem wurde behoben, durch dass beim Nachverfolgen von Änderungen der Vorgang manchmal zu einer Endlosschleife führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-678">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="079bb-679">Ein Problem wurde behoben, bei dem das Speichern einer vorhandenen Datei in einigen Fällen das Dialogfeld "Speichern unter" aufruft und die Datei nie wirklich gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-679">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="079bb-680">Es wurde ein Problem beim Zusammenführen von zwei Dokumenten in ein Dokument behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-680">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="079bb-681">Es wurde ein Problem mit der compare-Funktion für Dokumente behoben, die für die Bearbeitung geschützt waren.</span><span class="sxs-lookup"><span data-stu-id="079bb-681">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="079bb-682">Behebt verschiedene Probleme, bei denen die App beim Herunterfahren hängen bleiben kann.</span><span class="sxs-lookup"><span data-stu-id="079bb-682">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="079bb-683">Außerdem wurden Absturzursachen im Zusammenhang mit bestimmten Add-Ins behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-683">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="079bb-684">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="079bb-684">Office Suite</span></span>

- <span data-ttu-id="079bb-685">Behebung eines Problems, aufgrund dessen der neue Zeitname "Reiwa" in Hiragana und Kanji als Rechtschreibfehler oder Grammatikfehler eingestuft wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-685">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="079bb-686">Ein Problem wurde behoben, bei dem Benutzer beim Versuch, in SharePoint 2016 gespeicherte Dateien freizugeben, die Meldung "Leider verhindert etwas, dass wir dies freigeben" erhielten.</span><span class="sxs-lookup"><span data-stu-id="079bb-686">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="079bb-687">Ein Problem wurde behoben, das zu Datenverlusten in Sitzungen führen konnte, bei denen sowohl die gemeinsame Dokumenterstellung als auch die Offlinebearbeitung in PowerPoint genutzt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-687">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="079bb-688">Dieser Fix beseitigt die Ursache für einen Absturz, der beim Öffnen einer Datei auftreten konnte.</span><span class="sxs-lookup"><span data-stu-id="079bb-688">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="079bb-689">In einigen Fällen wurde für eine von der Synchronisierungs-Engine gesicherte SharePoint-Datei "Gespeichert" angezeigt, ohne dass die Änderungen tatsächlich gespeichert wurden, was zu einem Datenverlust führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-689">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="079bb-690">Das Problem, bei dem Benutzer möglicherweise nicht in der Lage waren, Word-, Excel- und PowerPoint-Dokumente zu speichern, wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-690">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="079bb-691">Dieses Problem betrifft Benutzer, die eine neue Datei erstellen und die Option „Als Dialog speichern“ öffnen, nachdem Sie auf das Symbol „Speichern“ geklickt oder STRG+S gedrückt haben.</span><span class="sxs-lookup"><span data-stu-id="079bb-691">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="079bb-692">Behebt einen Absturz in Word, indem es von einer veralteten API entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-692">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="079bb-693">Behebt ein Problem, bei dem Katakana-Zeichen mit halber Breite in vertikalen Textfeldern in PowerPoint nicht ordnungsgemäß gedreht wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-693">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="079bb-694">Ein Leistungsproblem unter Win7 wurde behoben, bei dem es in allen Apps ca. 4 Sekunden dauerte, bis der Katalog "Formen einfügen" auf dem Menüband angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-694">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="079bb-695">Ein Fehler wurde behoben, bei dem im Informationsbereich der Backstage-Ansicht keine Barrierefreiheitsinformationen angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-695">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="079bb-696">Verbessert die Zuverlässigkeit des Office-Updateprozesses hinsichtlich der Registrierungsintegrität.</span><span class="sxs-lookup"><span data-stu-id="079bb-696">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="079bb-697">Die Kanalnamen für die Januar- und Juli 2019-Verzweigungen wurden auf die neuen Namen aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="079bb-697">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="079bb-698">Behebt ein Problem, bei dem Updates in getakteten Netzwerken möglicherweise unerwartet blockiert wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-698">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="079bb-699">Ein Bug in der Einstellung des Stichtags für ODT- und GPO-Updates wurde behoben, bei dem der relative Stichtag nur beim ersten Festlegen funktionierte. Der Fix aktiviert den relativen Stichtag für spätere Updates.</span><span class="sxs-lookup"><span data-stu-id="079bb-699">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="079bb-700">Unter bestimmten Umständen werden Office-Verknüpfungen nach einem Update möglicherweise nicht mehr angezeigt.</span><span class="sxs-lookup"><span data-stu-id="079bb-700">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="079bb-701">Dieses Update erhöht die Zuverlässigkeit beim Veröffentlichen von Office-Verknüpfungen.</span><span class="sxs-lookup"><span data-stu-id="079bb-701">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="079bb-702">Behebt ein Problem, bei dem Office-Aktualisierungen möglicherweise unerwartet Dateien aus dem Office CDN anstelle der beabsichtigten Quelle heruntergeladen haben, beispielsweise eine lokale oder Netzwerkfreigabe oder einen vom Configuration Manager bereitgestellten Speicherort.</span><span class="sxs-lookup"><span data-stu-id="079bb-702">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="079bb-703">Behebt ein Problem, bei dem ein Update in bestimmten Fällen nicht installiert wurde, wenn der Benutzer kein Administrator ist und das Systemkonto keine Netzwerkverbindung hatte.</span><span class="sxs-lookup"><span data-stu-id="079bb-703">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="079bb-704">Es wurde ein Problem behoben, bei dem Office-Update-Nachrichten in einer anderen Sprache als erwartet angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-704">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="079bb-705">In Zukunft entsprechen Office-Update-Nachrichten ordnungsgemäß der Windows-Anzeigesprache.</span><span class="sxs-lookup"><span data-stu-id="079bb-705">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="079bb-706">Die Zuverlässigkeit beim Herunterladen von Office-Updates wurde verbessert, indem Downloads fortgesetzt werden, die möglicherweise zuvor unterbrochen wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-706">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="079bb-707">Behebt Probleme im Zusammenhang mit der Anpassung der Eigenschaft "TextBox/ Form automatisch anpassen" in Drittanbieter-Plug-ins.</span><span class="sxs-lookup"><span data-stu-id="079bb-707">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="079bb-708">Diese Änderung behebt das korrekte Rendern von Bildern nach dem Öffnen einer beschädigten Datei.</span><span class="sxs-lookup"><span data-stu-id="079bb-708">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="079bb-709">Diese Änderung betrifft die langsame Darstellung einiger Streudiagramme mit Markierungen.</span><span class="sxs-lookup"><span data-stu-id="079bb-709">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="079bb-710">Es wurde ein Problem behoben, bei dem große Strukturansichten zu einem Absturz führten.</span><span class="sxs-lookup"><span data-stu-id="079bb-710">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="079bb-711">Dieses Update behebt ein Problem in Visual Basic for Applications in Microsoft Office, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung beim Laden als fehlerhaft angesehen werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-711">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="079bb-712">Um die Sicherheit der Office-Kunden zu schützen, sind jetzt Microsoft Office-Updates ausschließlich mit dem SHA-2-Algorithmus signiert.</span><span class="sxs-lookup"><span data-stu-id="079bb-712">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="079bb-713">Um die Sicherheit der Office-Kunden zu schützen, sind jetzt Microsoft Office-Updates ausschließlich mit dem SHA-2-Algorithmus signiert.</span><span class="sxs-lookup"><span data-stu-id="079bb-713">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1902-july-14"></a><span data-ttu-id="079bb-715">Version 1902: 14. Juli</span><span class="sxs-lookup"><span data-stu-id="079bb-715">Version 1902: July 14</span></span>
<span data-ttu-id="079bb-716">*Version 1902 (Build 11328.20624)*</span><span class="sxs-lookup"><span data-stu-id="079bb-716">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="079bb-717">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-717">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="079bb-718">Version 1908: 9. Juni</span><span class="sxs-lookup"><span data-stu-id="079bb-718">Version 1908: June 09</span></span>
<span data-ttu-id="079bb-719">*Version 1908 (Build 11929.20838)*</span><span class="sxs-lookup"><span data-stu-id="079bb-719">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="079bb-720">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-720">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="079bb-722">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-722">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="079bb-723">Excel</span><span class="sxs-lookup"><span data-stu-id="079bb-723">Excel</span></span>

- <span data-ttu-id="079bb-724">Es wurde ein Problem behoben, bei dem Excel u. U. nicht mehr reagierte, nachdem STRG+UMSCHALT+Pfeiltasten zum Scrollen verwendet wurden, wenn das Excel-Fenster über Microsoft Teams gemeinsam genutzt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-724">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="079bb-725">Ein Problem mit der Skalierung von Kontrollkästchen in Formularsteuerelementen beim Drucken wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-725">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="079bb-726">Ein Absturz konnte auftreten, wenn versucht wurde, Änderungen mithilfe des Legacymodus "Freigegebene Arbeitsmappe" auf einem neuen Blatt für eine Arbeitsmappe aufzulisten.</span><span class="sxs-lookup"><span data-stu-id="079bb-726">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="079bb-727">Outlook</span><span class="sxs-lookup"><span data-stu-id="079bb-727">Outlook</span></span>

- <span data-ttu-id="079bb-728">Behebt ein Problem, das dazu führte, dass Benutzer beim Weiterleiten großer HTML-Nachrichten den Nachrichtentext abgeschnitten sahen.</span><span class="sxs-lookup"><span data-stu-id="079bb-728">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="079bb-729">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="079bb-729">Office Suite</span></span>

- <span data-ttu-id="079bb-730">Die Kanalnamen für die Januar- und Juli 2019-Verzweigungen wurden auf die neuen Namen aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="079bb-730">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1902-june-09"></a><span data-ttu-id="079bb-732">Version 1902: 9. Juni</span><span class="sxs-lookup"><span data-stu-id="079bb-732">Version 1902: June 09</span></span>
<span data-ttu-id="079bb-733">*Version 1902 (Build 11328.20602)*</span><span class="sxs-lookup"><span data-stu-id="079bb-733">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="079bb-734">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-734">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="079bb-736">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-736">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="079bb-737">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="079bb-737">Office Suite</span></span>

- <span data-ttu-id="079bb-738">Die Kanalnamen für die Januar- und Juli 2019-Verzweigungen wurden auf die neuen Namen aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="079bb-738">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="079bb-739">Es wurden veraltete Verweise aus den Basisdateien entfernt, die zu einem Fehler im C2R-Build führten.</span><span class="sxs-lookup"><span data-stu-id="079bb-739">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1908-may-12"></a><span data-ttu-id="079bb-741">Version 1908: 12. Mai</span><span class="sxs-lookup"><span data-stu-id="079bb-741">Version 1908: May 12</span></span>
<span data-ttu-id="079bb-742">*Version 1908 (Build 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="079bb-742">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="079bb-743">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-743">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="079bb-745">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-745">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="079bb-746">Excel</span><span class="sxs-lookup"><span data-stu-id="079bb-746">Excel</span></span>

- <span data-ttu-id="079bb-747">Beim Kopieren von nach Farbe gefilterten Daten in eine Spalte mit einer anderen Breite wurden die Werte nicht eingefügt.</span><span class="sxs-lookup"><span data-stu-id="079bb-747">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="079bb-748">Outlook</span><span class="sxs-lookup"><span data-stu-id="079bb-748">Outlook</span></span>

- <span data-ttu-id="079bb-749">Es wurde ein Problem behoben, das zu einem Absturz führte, wenn Benutzer MSG- und OFT-Dateien nach dem Anwenden eines kürzlich durchgeführten Windows-Updates öffneten.</span><span class="sxs-lookup"><span data-stu-id="079bb-749">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="079bb-750">Word</span><span class="sxs-lookup"><span data-stu-id="079bb-750">Word</span></span>

- <span data-ttu-id="079bb-751">Es wurde ein Problem beim Zusammenführen von zwei Dokumenten in ein Dokument behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-751">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="079bb-752">Es wurde ein Problem mit der compare-Funktion für Dokumente behoben, die für die Bearbeitung geschützt waren.</span><span class="sxs-lookup"><span data-stu-id="079bb-752">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1902-may-12"></a><span data-ttu-id="079bb-754">Version 1902: 12. Mai</span><span class="sxs-lookup"><span data-stu-id="079bb-754">Version 1902: May 12</span></span>
<span data-ttu-id="079bb-755">*Version 1902 (Build 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="079bb-755">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="079bb-756">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-756">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="079bb-758">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-758">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="079bb-759">Outlook</span><span class="sxs-lookup"><span data-stu-id="079bb-759">Outlook</span></span>

- <span data-ttu-id="079bb-760">Es wurde ein Problem behoben, das dazu führte, dass Benutzer beim Öffnen von MSG- und OFT-Dateien nach der Anwendung eines kürzlich durchgeführten Windows-Updates einen Absturz erlebten.</span><span class="sxs-lookup"><span data-stu-id="079bb-760">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="079bb-761">Standardmäßig zeigen die Etiketten der Aufbewahrungsrichtlinien die Aufbewahrungszeitspanne in Klammern an.</span><span class="sxs-lookup"><span data-stu-id="079bb-761">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="079bb-762">Dadurch wird ein Registrierungsschlüssel bereitgestellt, mit dem Administratoren festlegen können, dass nur der Name der Richtlinie angezeigt werden soll.</span><span class="sxs-lookup"><span data-stu-id="079bb-762">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="079bb-763">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="079bb-763">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="079bb-764">0 = Standard.</span><span class="sxs-lookup"><span data-stu-id="079bb-764">0 = Default.</span></span>  <span data-ttu-id="079bb-765">1 = nur der "PolicyName" für den Text der Aufbewahrungsrichtlinie wird angezeigt.</span><span class="sxs-lookup"><span data-stu-id="079bb-765">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1908-may-04"></a><span data-ttu-id="079bb-767">Version 1908: 04. Mai</span><span class="sxs-lookup"><span data-stu-id="079bb-767">Version 1908: May 04</span></span>
<span data-ttu-id="079bb-768">*Version 1908 (Build 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="079bb-768">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="079bb-769">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-769">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="079bb-770">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-770">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="079bb-771">Outlook</span><span class="sxs-lookup"><span data-stu-id="079bb-771">Outlook</span></span>

- <span data-ttu-id="079bb-772">Es wurde ein Problem behoben, bei dem es zu einem Absturz kam, wenn Benutzer bestimmte Suchergebnisse auswählten.</span><span class="sxs-lookup"><span data-stu-id="079bb-772">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="079bb-773">Es wurde ein Problem behoben, das bewirkt hat, dass die Schaltfläche "In der Cloud speichern" in den Anlagentools fehlte.</span><span class="sxs-lookup"><span data-stu-id="079bb-773">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="079bb-774">Standardmäßig zeigen die Etiketten der Aufbewahrungsrichtlinien die Aufbewahrungszeitspanne in Klammern an.</span><span class="sxs-lookup"><span data-stu-id="079bb-774">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="079bb-775">Dadurch wird ein Registrierungsschlüssel bereitgestellt, mit dem Administratoren festlegen können, dass nur der Name der Richtlinie angezeigt werden soll.</span><span class="sxs-lookup"><span data-stu-id="079bb-775">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="079bb-776">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="079bb-776">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="079bb-777">0 = Standard; 1 = nur "PolicyName" für den Text der Aufbewahrungsrichtlinie wird angezeigt.</span><span class="sxs-lookup"><span data-stu-id="079bb-777">0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="079bb-778">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="079bb-778">Office Suite</span></span>

- <span data-ttu-id="079bb-779">Behebt ein Problem in Visual Basic for Applications in Microsoft Office, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung beim Laden als fehlerhaft angesehen werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-779">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="079bb-780">Version 1902: 04. Mai</span><span class="sxs-lookup"><span data-stu-id="079bb-780">Version 1902: May 04</span></span>
<span data-ttu-id="079bb-781">*Version 1902 (Build 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="079bb-781">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="079bb-782">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-782">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="079bb-783">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="079bb-783">Office Suite</span></span>

- <span data-ttu-id="079bb-784">Es wurde ein Problem in Visual Basic for Applications in Microsoft Office behoben, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthielten, von der Office-Anwendung beim Laden als fehlerhaft angesehen wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-784">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1908-april-26"></a><span data-ttu-id="079bb-785">Version 1908: 26. April</span><span class="sxs-lookup"><span data-stu-id="079bb-785">Version 1908: April 26</span></span>
<span data-ttu-id="079bb-786">*Version 1908 (Build 11929.20736)*</span><span class="sxs-lookup"><span data-stu-id="079bb-786">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="079bb-787">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt.</span><span class="sxs-lookup"><span data-stu-id="079bb-787">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="079bb-788">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-788">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="079bb-789">Excel</span><span class="sxs-lookup"><span data-stu-id="079bb-789">Excel</span></span>

- <span data-ttu-id="079bb-790">Es wurde ein Leistungsproblem behoben, das möglicherweise bei der Verwendung eines VBA-Makros zum Löschen des Inhalts eines Bereichs aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="079bb-790">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="079bb-791">Es wurde ein Problem mit VBA behoben, bei dem das Schreiben von Werten in einem Wertebereich langsamer als erwartet war.</span><span class="sxs-lookup"><span data-stu-id="079bb-791">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="079bb-792">Es wurde ein Problem behoben, bei dem die Eigenschaft "Wert wird überschnitten bei" auf der Diagrammachse unerwartet geändert wird, wenn Sie eine Datei speichern und erneut öffnen.</span><span class="sxs-lookup"><span data-stu-id="079bb-792">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="079bb-793">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-793">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="079bb-794">OneNote</span><span class="sxs-lookup"><span data-stu-id="079bb-794">OneNote</span></span>

- <span data-ttu-id="079bb-795">Lokalisiert die Benachrichtigung, durch die der Benutzer mehr über temporäre Maßnahmen erfahren kann, die in der OneNote-Benutzeroberfläche implementiert sind, um die Synchronisierungs-und Dienststabilität zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="079bb-795">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="079bb-796">Version 1908: 14. April</span><span class="sxs-lookup"><span data-stu-id="079bb-796">Version 1908: April 14</span></span>
<span data-ttu-id="079bb-797">*Version 1908 (Build 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="079bb-797">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="079bb-798">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-798">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="079bb-800">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-800">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="079bb-801">Excel</span><span class="sxs-lookup"><span data-stu-id="079bb-801">Excel</span></span>

- <span data-ttu-id="079bb-802">Es wurde ein Problem behoben, das beim Löschen von Spalten mit verbundenen Zellen zu einer verlangsamten Leistung führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-802">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="079bb-803">Es wurde ein Problem beim Skalieren von Text in Steuerelementen von Formularen beim Anzeigen in der Druckansicht behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-803">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="079bb-804">Skype</span><span class="sxs-lookup"><span data-stu-id="079bb-804">Skype</span></span>

- <span data-ttu-id="079bb-805">Problembehebung betreffend den Titelname für die Unterhaltungsregisterkarten, während mehrere Unterhaltungen stattfinden.</span><span class="sxs-lookup"><span data-stu-id="079bb-805">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="079bb-806">Outlook</span><span class="sxs-lookup"><span data-stu-id="079bb-806">Outlook</span></span>

- <span data-ttu-id="079bb-807">Es wurde ein Problem behoben, bei dem es durch das Herunterfahren von Outlook zu einem Absturz kam.</span><span class="sxs-lookup"><span data-stu-id="079bb-807">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="079bb-808">Es wurde ein Problem behoben, durch das Kunden in einigen Szenarios eine leere Raumliste zu sehen bekamen.</span><span class="sxs-lookup"><span data-stu-id="079bb-808">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="079bb-809">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="079bb-809">PowerPoint</span></span>

- <span data-ttu-id="079bb-810">Ein Problem mit dem Textmarker wurde behoben: Weißer Text mit dunkleren Textmarkerfarben wurde Schwarz mit Graustufen gedruckt.</span><span class="sxs-lookup"><span data-stu-id="079bb-810">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="079bb-811">Word</span><span class="sxs-lookup"><span data-stu-id="079bb-811">Word</span></span>

- <span data-ttu-id="079bb-812">Es wurde ein Problem mit der Anpassung von Text in einer Tabelle behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-812">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="079bb-813">Version 1902: 14. April</span><span class="sxs-lookup"><span data-stu-id="079bb-813">Version 1902: April 14</span></span>
<span data-ttu-id="079bb-814">*Version 1902 (Build 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="079bb-814">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="079bb-815">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-815">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1908-march-10"></a><span data-ttu-id="079bb-817">Version 1908: 10. März</span><span class="sxs-lookup"><span data-stu-id="079bb-817">Version 1908: March 10</span></span>
<span data-ttu-id="079bb-818">*Version 1908 (Build 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="079bb-818">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="079bb-819">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-819">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="079bb-821">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-821">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="079bb-822">Excel</span><span class="sxs-lookup"><span data-stu-id="079bb-822">Excel</span></span>

- <span data-ttu-id="079bb-823">Es wurde ein Problem behoben, durch das einigen Benutzern mehrere Popupfenster angezeigt wurden, wenn externe Links in der Arbeitsmappe vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="079bb-823">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="079bb-824">Die Funktion "Text in Spalte" funktioniert bei einigen Gebietsschemas möglicherweise nicht.</span><span class="sxs-lookup"><span data-stu-id="079bb-824">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="079bb-825">Beim Zugriff auf einen verborgenen benannten Bereich kann ein Fehler auftreten.</span><span class="sxs-lookup"><span data-stu-id="079bb-825">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="079bb-826">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="079bb-826">PowerPoint</span></span>

- <span data-ttu-id="079bb-827">Ein Problem mit der Shape.Paste-Methode wurde behoben: Wenn der Benutzer die Form mit der Shape.Paste-Methode kopiert und einfügt, wird die Auswahl in die eingefügte Form geändert.</span><span class="sxs-lookup"><span data-stu-id="079bb-827">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="079bb-828">Word</span><span class="sxs-lookup"><span data-stu-id="079bb-828">Word</span></span>

- <span data-ttu-id="079bb-829">Ein Problem wurde behoben, bei dem das Speichern einer vorhandenen Datei in einigen Fällen das Dialogfeld "Speichern unter" aufruft und die Datei nie wirklich gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-829">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="079bb-830">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="079bb-830">Office Suite</span></span>

- <span data-ttu-id="079bb-831">Diese Änderung betrifft die langsame Darstellung einiger Streudiagramme mit Markierungen.</span><span class="sxs-lookup"><span data-stu-id="079bb-831">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="079bb-832">Version 1902: 10. März</span><span class="sxs-lookup"><span data-stu-id="079bb-832">Version 1902: March 10</span></span>
<span data-ttu-id="079bb-833">*Version 1902 (Build 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="079bb-833">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="079bb-834">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-834">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS NICHT AM INHALTSENDE ENTFERNEN)

## <a name="version-1908-february-11"></a><span data-ttu-id="079bb-836">Version 1908: 11. Februar</span><span class="sxs-lookup"><span data-stu-id="079bb-836">Version 1908: February 11</span></span>
<span data-ttu-id="079bb-837">*Version 1908 (Build 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="079bb-837">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="079bb-838">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-838">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="079bb-840">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-840">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="079bb-841">Excel</span><span class="sxs-lookup"><span data-stu-id="079bb-841">Excel</span></span>

- <span data-ttu-id="079bb-842">Dieses Update behebt ein Problem, das dazu führte, dass ein Fehler auftrat, wenn VBA zum Hinzufügen eines Bildes zur Kopf-/Fußzeile eines Diagramms verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-842">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="079bb-843">Es wurde ein Problem behoben, bei dem der Rand eines Gruppenfeld-Steuerelements in der Druckvorschau oder beim Drucken nicht sichtbar war.</span><span class="sxs-lookup"><span data-stu-id="079bb-843">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="079bb-844">Nutzer können beim Speichern von Änderungen auf einen Fehler stoßen, wenn sie manche nicht englische Zeichensätze verwenden.</span><span class="sxs-lookup"><span data-stu-id="079bb-844">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="079bb-845">Es wurde ein Problem behoben, durch das die Dateigröße von Bildern in Diagrammkopfzeilen beim Speichern der Arbeitsmappe mit dem Diagramm zunahm.</span><span class="sxs-lookup"><span data-stu-id="079bb-845">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="079bb-846">Es wurde ein Problem behoben, das zur Beschädigung von DBCS-Zeichen in Büchern mit Querverweisen führte, indem die Auswahlbereiche mit dem Buch mit Querverweisen synchronisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-846">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="079bb-847">Es wurde ein Problem behoben, das dazu führen konnte, dass Kontrollkästchen bei Verwendung der automatischen Anpassung zum Anpassen der Zeilenhöhe verkleinert wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-847">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="079bb-848">Outlook</span><span class="sxs-lookup"><span data-stu-id="079bb-848">Outlook</span></span>

- <span data-ttu-id="079bb-849">Es wurde ein Problem behoben, bei dem beim Angeben einer ungültigen Absenderadresse ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-849">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="079bb-850">Es wurde ein Problem behoben, bei dem Nutzer bei der Verarbeitung von Konfliktnachrichten Synchronisierungsfehler hatten.</span><span class="sxs-lookup"><span data-stu-id="079bb-850">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="079bb-851">Es wurde ein Problem behoben, bei dem Nutzer beim Starten von Outlook beim Laden des Profils auf dem Bildschirm "Laden von Profilen" hängen blieben.</span><span class="sxs-lookup"><span data-stu-id="079bb-851">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="079bb-852">Es wurde ein Problem behoben, durch das Nutzer beim Ändern von Ansichten zeitweise Abstürze sehen konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-852">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="079bb-853">Es wurde ein Problem behoben, bei dem beim Anzeigen von mehr als 30 Kalendern in einer Citrix-Umgebung ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-853">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="079bb-854">[Hier](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) ist die einzelne KB, in der dies für frühere Versionen dokumentiert wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-854">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="079bb-855">Behebt ein Problem, bei dem Nutzer Probleme mit der Synchronisierung freigegebener Kalenderordner mit dem OST hatten, was zu Berechtigungsfehlern führte, wenn sie versuchten, mit diesen Ordnern zu interagieren.</span><span class="sxs-lookup"><span data-stu-id="079bb-855">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="079bb-856">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="079bb-856">PowerPoint</span></span>

- <span data-ttu-id="079bb-857">Verbessertes Szenario zum Kopieren und Einfügen Das Kopieren der Form in eine PowerPoint-Folie und das Einfügen in eine andere Folie in einer Schleife schlägt möglicherweise mit Ausnahme fehl.</span><span class="sxs-lookup"><span data-stu-id="079bb-857">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="079bb-858">Es wurde ein Problem behoben, das zu einer langsameren Leistung zwischen Nutzern, die zusammenarbeiten, führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-858">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="079bb-859">Es wurde ein Problem behoben, das auftreten konnte, wenn eine Datei, die inkrementell geöffnet wurde, eine Folie mit mehr als einem eingebetteten Mediendatenstrom enthielt.</span><span class="sxs-lookup"><span data-stu-id="079bb-859">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="079bb-860">Wir haben ein Problem behoben, bei dem beim ersten Start von PowerPoint möglicherweise keine Sicherheitswarnmeldung für nicht vertrauenswürdige Add-Ins angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-860">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="079bb-861">Project</span><span class="sxs-lookup"><span data-stu-id="079bb-861">Project</span></span>

- <span data-ttu-id="079bb-862">Es wurde ein Problem behoben, bei dem die tatsächliche Arbeit zwischen Arbeitszeittabelle und Projektplan unterschiedlich sein kann, da Ressourcenkalender nicht aktualisiert werden, wenn sich der Basiskalender ändert.</span><span class="sxs-lookup"><span data-stu-id="079bb-862">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="079bb-863">Word</span><span class="sxs-lookup"><span data-stu-id="079bb-863">Word</span></span>

- <span data-ttu-id="079bb-864">Ein Absturz in Word wurde behoben, indem es von einer veralteten API entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-864">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="079bb-865">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="079bb-865">Office Suite</span></span>

- <span data-ttu-id="079bb-866">Diese Änderung behebt das korrekte Rendern von Bildern nach dem Öffnen einer beschädigten Datei.</span><span class="sxs-lookup"><span data-stu-id="079bb-866">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1902-february-11"></a><span data-ttu-id="079bb-868">Version 1902: 11. Februar</span><span class="sxs-lookup"><span data-stu-id="079bb-868">Version 1902: February 11</span></span>
<span data-ttu-id="079bb-869">*Version 1902 (Build 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="079bb-869">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="079bb-870">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-870">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="079bb-872">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-872">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="079bb-873">Outlook</span><span class="sxs-lookup"><span data-stu-id="079bb-873">Outlook</span></span>

- <span data-ttu-id="079bb-874">Behebt ein Problem, das dazu führte, dass Nutzer auf einen Verschlüsselungsalgorithmus stießen. Es werden keine Fehler beim Senden einer verschlüsselten E-Mail unterstützt.</span><span class="sxs-lookup"><span data-stu-id="079bb-874">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="079bb-875">Word</span><span class="sxs-lookup"><span data-stu-id="079bb-875">Word</span></span>

- <span data-ttu-id="079bb-876">Ein Absturz in Word wurde behoben, indem es von einer veralteten API entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-876">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

## <a name="version-1808-february-11"></a><span data-ttu-id="079bb-879">Version 1808: 11. Februar</span><span class="sxs-lookup"><span data-stu-id="079bb-879">Version 1808: February 11</span></span>
<span data-ttu-id="079bb-880">*Version 1808 (Build 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="079bb-880">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="079bb-881">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-881">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1908-january-14"></a><span data-ttu-id="079bb-883">Version 1908: 14. Januar</span><span class="sxs-lookup"><span data-stu-id="079bb-883">Version 1908: January 14</span></span>
<span data-ttu-id="079bb-884">*Version 1908 (Build 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="079bb-884">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="079bb-885">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-885">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="079bb-887">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="079bb-887">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="079bb-888">Access</span><span class="sxs-lookup"><span data-stu-id="079bb-888">Access</span></span>

- <span data-ttu-id="079bb-889">**Registerkarten für Datenbankobjekte im Blick behalten:** Erkennen Sie eindeutig die aktive Registerkarte, ordnen Sie Registerkarten durch Ziehen mit der Maus neu an, und schließen Sie Datenbankobjekte mit nur einem Klick.</span><span class="sxs-lookup"><span data-stu-id="079bb-889">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="079bb-890">**Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an.</span><span class="sxs-lookup"><span data-stu-id="079bb-890">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="079bb-891">Das Wechseln zwischen den Konten ist so einfach wie nie.</span><span class="sxs-lookup"><span data-stu-id="079bb-891">Switching between them has never been easier.</span></span> [<span data-ttu-id="079bb-892">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-892">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="079bb-893">**Mehr Platz zum Zoomen:** Vergrößern Sie das Zoomfeld, ändern Sie die Schriftart, und die Zoomfunktion merkt sich alles.</span><span class="sxs-lookup"><span data-stu-id="079bb-893">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="079bb-894">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-894">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="079bb-895">Excel</span><span class="sxs-lookup"><span data-stu-id="079bb-895">Excel</span></span>

- <span data-ttu-id="079bb-896">**Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an.</span><span class="sxs-lookup"><span data-stu-id="079bb-896">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="079bb-897">Das Wechseln zwischen den Konten ist so einfach wie nie.</span><span class="sxs-lookup"><span data-stu-id="079bb-897">Switching between them has never been easier.</span></span> [<span data-ttu-id="079bb-898">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-898">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="079bb-899">**Erhöhen Sie die Reichweite Ihrer Inhalte** : Möchten Sie Ihre Präsentationen barrierefrei gestalten?</span><span class="sxs-lookup"><span data-stu-id="079bb-899">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="079bb-900">Die Barrierefreiheitsprüfung kann dies für Sie im Auge behalten, ohne Ihnen dabei in die Quere zu kommen.</span><span class="sxs-lookup"><span data-stu-id="079bb-900">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="079bb-901">Probieren Sie es aus, indem Sie auf „Überprüfen“ > „Barrierefreiheit überprüfen“ klicken. Wir werden Sie in der Statusleiste informieren, wenn wir etwas finden, dass Sie sich ansehen müssen.</span><span class="sxs-lookup"><span data-stu-id="079bb-901">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="079bb-902">**Schnelle Dateisuche:** Sie suchen nach einer Datei, an der Sie kürzlich gearbeitet haben?</span><span class="sxs-lookup"><span data-stu-id="079bb-902">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="079bb-903">Geben Sie einfach in das Suchfeld unter „Datei“ > „Start“ den Namen der gesuchten Datei ein.</span><span class="sxs-lookup"><span data-stu-id="079bb-903">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="079bb-904">**Verleihen Sie Ihrem Arbeitsblatt mehr Lebendigkeit:** Fügen Sie animierte 3D-Grafiken ein, um zu sehen, wie Herzen schlagen, Planeten sich in einer Umlaufbahn bewegen und wie ein T-Rex durch die Arbeitsmappe stampft.</span><span class="sxs-lookup"><span data-stu-id="079bb-904">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="079bb-905">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-905">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="079bb-p175">**Erfahren Sie mehr über Ihre Daten:** Die neue Schaltfläche "Ideen" sucht in Ihren Daten nach Mustern und verwendet diese, um intelligente, persönliche Vorschläge zu erstellen. [Weitere Informationen](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="079bb-p175">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="079bb-908">**Zusammenarbeiten ist jetzt noch einfacher:** Verbesserungen bei der gemeinsamen Dokumenterstellung führen dazu, dass Ihre Änderungen beim Arbeiten mit bedingter Formatierung, Zellformatvorlagen und mehr nahtlos mit denen Ihrer Mitarbeiter zusammengeführt werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-908">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="079bb-909">**Verknüpfen von Tabellen in ähnlichen Spalten:** Abrufen und Transformieren (Power Query) bietet jetzt eine ungefähre Textübereinstimmungslogik (auch Fuzzyübereinstimmung genannt) beim Vergleichen von Spalten zum Zusammenführen von Tabellen.</span><span class="sxs-lookup"><span data-stu-id="079bb-909">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="079bb-910">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-910">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="079bb-911">**Schnelles Programmieren mit Power Query-Verbesserungen** : Mit AutoVervollständigen und farbiger Syntax können Sie Code schnell fertigstellen.</span><span class="sxs-lookup"><span data-stu-id="079bb-911">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="079bb-912">Außerdem können Sie auf einfache Weise Funktionen, Spalten und Parameter ermitteln.</span><span class="sxs-lookup"><span data-stu-id="079bb-912">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="079bb-913">**Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können.</span><span class="sxs-lookup"><span data-stu-id="079bb-913">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="079bb-914">Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="079bb-914">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="079bb-915">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-915">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="079bb-916">Outlook</span><span class="sxs-lookup"><span data-stu-id="079bb-916">Outlook</span></span>

- <span data-ttu-id="079bb-917">**Wir haben die Outlook-Benutzererfahrung für Sie aktualisiert** : Eine vereinfachte Oberfläche, die über "In Kürze verfügbar" bereits in der Vorschau zur Verfügung stand und Ihnen helfen soll, sich auf das Wesentliche zu konzentrieren.</span><span class="sxs-lookup"><span data-stu-id="079bb-917">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="079bb-918">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-918">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="079bb-919">**Ein vereinfachtes und benutzerdefiniertes Menüband** : Genießen Sie eine optimierte, einzelne Reihe der am häufigsten verwendeten Schaltflächen.</span><span class="sxs-lookup"><span data-stu-id="079bb-919">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="079bb-920">Sie können einfach zwischen klassischer und vereinfachter Ansicht sowie den Befehlen "Anheften" und "Lösen" wechseln.</span><span class="sxs-lookup"><span data-stu-id="079bb-920">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="079bb-921">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-921">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="079bb-922">**Arbeiten während des Verschiebens von Nachrichten:** Outlook verschiebt Nachrichten nun im Hintergrund, sodass Sie weiterarbeiten können, während viele Nachrichten zwischen Ordnern verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-922">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="079bb-923">**Einbauen einer Zeitspanne zwischen unmittelbar aufeinander folgenden Besprechungen** : Geben Sie den Teilnehmern Zeit für eine Atempause und oder den Weg zwischen verschiedenen Besprechungsorten, indem Sie festlegen, dass Besprechungen standardmäßig 5–10 Minuten früher enden.</span><span class="sxs-lookup"><span data-stu-id="079bb-923">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="079bb-924">**Wählen Sie Ihre bevorzugte Aktion aus:** Verwenden Sie keine Kennzeichnung und Löschung?</span><span class="sxs-lookup"><span data-stu-id="079bb-924">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="079bb-925">Wie sieht es mit "Archivieren" oder "Als gelesen markieren" aus?</span><span class="sxs-lookup"><span data-stu-id="079bb-925">How about Archive or Mark as Read?</span></span> <span data-ttu-id="079bb-926">Passen Sie das Menü mit schnellen Aktionen mit den am häufigsten verwendeten Befehlen an.</span><span class="sxs-lookup"><span data-stu-id="079bb-926">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="079bb-p182">**Benutzer können Ihre Memes einsehen:** Wenn Text oder statische Bilder einfach nicht genug sind, verwenden Sie ein animiertes GIF zur Veranschaulichung. [Weitere Informationen](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="079bb-p182">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="079bb-929">**Eine schnellere Methode, um Konten hinzuzufügen** : Dank der Verbesserungen beim Einrichten von Konten ist es einfacher denn je, Outlook.com- und Gmail-Konten mit zweistufiger Authentifizierung zu Outlook hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="079bb-929">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="079bb-930">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-930">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="079bb-931">**Verabschieden Sie sich von den Synchronisationsbeschränkungen** : Outlook-Verbesserungen bedeuten, dass die Ordnerbeschränkung aufgehoben ist, also fahren Sie fort und synchronisieren Sie Ihre gemeinsamen Postfächer.</span><span class="sxs-lookup"><span data-stu-id="079bb-931">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="079bb-932">**Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können.</span><span class="sxs-lookup"><span data-stu-id="079bb-932">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="079bb-933">Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="079bb-933">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="079bb-934">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-934">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="079bb-935">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="079bb-935">PowerPoint</span></span>

- <span data-ttu-id="079bb-936">**Bessere Formwandlung** : Geben Sie Ihren Shapes einen Namen, um mehr Kontrolle über ihr Morphen zu haben.</span><span class="sxs-lookup"><span data-stu-id="079bb-936">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="079bb-937">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-937">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="079bb-938">**Schnelle Dateisuche:** Sie suchen nach einer Datei, an der Sie kürzlich gearbeitet haben?</span><span class="sxs-lookup"><span data-stu-id="079bb-938">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="079bb-939">Geben Sie einfach in das Suchfeld unter „Datei“ > „Start“ den Namen der gesuchten Datei ein.</span><span class="sxs-lookup"><span data-stu-id="079bb-939">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="079bb-940">**Erhöhen Sie die Reichweite Ihrer Inhalte** : Möchten Sie Ihre Präsentationen barrierefrei gestalten?</span><span class="sxs-lookup"><span data-stu-id="079bb-940">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="079bb-941">Die Barrierefreiheitsprüfung kann dies für Sie im Auge behalten, ohne Ihnen dabei in die Quere zu kommen.</span><span class="sxs-lookup"><span data-stu-id="079bb-941">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="079bb-942">Probieren Sie es aus, indem Sie auf „Überprüfen“ > „Barrierefreiheit überprüfen“ klicken. Wir werden Sie in der Statusleiste informieren, wenn wir etwas finden, dass Sie sich ansehen müssen.</span><span class="sxs-lookup"><span data-stu-id="079bb-942">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="079bb-943">**Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an.</span><span class="sxs-lookup"><span data-stu-id="079bb-943">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="079bb-944">Das Wechseln zwischen den Konten ist so einfach wie nie.</span><span class="sxs-lookup"><span data-stu-id="079bb-944">Switching between them has never been easier.</span></span> [<span data-ttu-id="079bb-945">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-945">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="079bb-946">**Neuer Speicherort für Onlinevideos** : Speichern Sie ein Video in Microsoft Stream, damit es jeder in Ihrem Unternehmen ansehen kann.</span><span class="sxs-lookup"><span data-stu-id="079bb-946">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="079bb-947">Fügen Sie den Videolink ein, und profitieren Sie von Multimediapräsentationen mit einem Bruchteil der üblichen Dateigröße.</span><span class="sxs-lookup"><span data-stu-id="079bb-947">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="079bb-948">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-948">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="079bb-949">**Speichern Sie Ihre Änderungen, während sie entstehen** : Laden Sie Ihre Dateien in OneDrive hoch, um sicherzustellen, dass alle Ihre Aktualisierungen automatisch gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-949">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="079bb-p190">**Befragen Sie Ihr Publikum mit einem Quiz oder einer Umfrage:** Fügen Sie ein Quiz oder eine Umfrage einer Folie hinzu. Office sammelt und speichert die Antworten für Sie. [Weitere Informationen](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="079bb-p190">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="079bb-p191">**Das Einfügen von Onlinevideos ist jetzt einfacher denn je:** Möchten Sie auf Ihrer Folie ein Video von Vimeo oder YouTube einfügen? Hierfür benötigen Sie nur den Link zur Videoseite. [Weitere Informationen](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="079bb-p191">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="079bb-956">**Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können.</span><span class="sxs-lookup"><span data-stu-id="079bb-956">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="079bb-957">Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="079bb-957">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="079bb-958">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-958">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="079bb-959">Project</span><span class="sxs-lookup"><span data-stu-id="079bb-959">Project</span></span>

- <span data-ttu-id="079bb-960">**Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an.</span><span class="sxs-lookup"><span data-stu-id="079bb-960">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="079bb-961">Das Wechseln zwischen den Konten ist so einfach wie nie.</span><span class="sxs-lookup"><span data-stu-id="079bb-961">Switching between them has never been easier.</span></span> [<span data-ttu-id="079bb-962">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-962">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="079bb-963">Visio</span><span class="sxs-lookup"><span data-stu-id="079bb-963">Visio</span></span>

- <span data-ttu-id="079bb-964">**Exportieren von Prozessdiagrammen nach Word:** Fügen Sie Diagramminhalte, wie Formen und Metadaten, automatisch zu einem Word-Dokument hinzu.</span><span class="sxs-lookup"><span data-stu-id="079bb-964">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="079bb-965">Passen Sie dann das Dokument an, um Prozessrichtlinien und Handbücher zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="079bb-965">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="079bb-966">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-966">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="079bb-967">**Zweiter Blick auf Datenflussdiagramme:** Attraktive neue Layouts für Data Visualizer-Flussdiagramme sind übersichtlich, klar und einfach zu verstehen.</span><span class="sxs-lookup"><span data-stu-id="079bb-967">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="079bb-968">Klicken Sie auf die Registerkarte Entwurf für weitere Optionen.</span><span class="sxs-lookup"><span data-stu-id="079bb-968">Click the Design tab for options.</span></span>

- <span data-ttu-id="079bb-969">**Integrierte Azure Schablonen:** Entwerfen Sie eine Cloud-App, oder planen Sie eine Architektur mithilfe von Dutzenden von Azure-Schablonen.</span><span class="sxs-lookup"><span data-stu-id="079bb-969">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="079bb-970">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-970">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="079bb-p197">**Verabschieden Sie sich von fehlerhaften Excel-Verknüpfungen:** Die Excel-Arbeitsmappe, die mit Ihrem Datenschnellansichtsdiagramms verknüpft ist, kann nicht gefunden werden? Verknüpfen Sie es erneut, und es kann weiter gehen. [Weitere Informationen](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="079bb-p197">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="079bb-974">**Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an.</span><span class="sxs-lookup"><span data-stu-id="079bb-974">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="079bb-975">Das Wechseln zwischen den Konten ist so einfach wie nie.</span><span class="sxs-lookup"><span data-stu-id="079bb-975">Switching between them has never been easier.</span></span> [<span data-ttu-id="079bb-976">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-976">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="079bb-977">**Exportieren von Visio-Visualisierungen aus Power BI** : Die Visio-Visualisierung für Power BI wird nun ordnungsgemäß angezeigt, wenn Sie Power BI-Berichte beispielsweise als PDF-Dateien, PowerPoint-Dateien und mehr exportieren.</span><span class="sxs-lookup"><span data-stu-id="079bb-977">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="079bb-978">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-978">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="079bb-979">Word</span><span class="sxs-lookup"><span data-stu-id="079bb-979">Word</span></span>

- <span data-ttu-id="079bb-980">**Der Modus „Lerntools“ bietet zusätzliche Unterstützung für weitere Seitenfarben:** Lerntools in Word unterstützt weitere Farben für Seitendesigns, wodurch die Hintergrundfarbe der Seite geändert werden kann.</span><span class="sxs-lookup"><span data-stu-id="079bb-980">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="079bb-981">Viele Personen haben Herausforderungen beim Lesen mit einem ganz weißen oder schwarzem Hintergrund, deshalb haben wir die Auswahl von Farben in Word auf PC und Mac erweitert.</span><span class="sxs-lookup"><span data-stu-id="079bb-981">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="079bb-p201">**Natürliche Bearbeitung mit dem Freihand-Editor:** Mit einem einzigen Strich können Sie Wörter trennen oder verbinden, eine neue Zeile hinzufügen oder Wörter mithilfe Ihres Stifts einfügen. [Weitere Informationen](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="079bb-p201">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="079bb-p202">**Verwandeln Sie ihr Dokument von statisch in erstaunlich:** Verwandeln Sie Ihr Dokument in eine interaktive, einfach freizugebende Webseite, die auf jedem Gerät großartig aussieht. [Weitere Informationen](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="079bb-p202">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="079bb-986">**Erhöhen Sie die Reichweite Ihrer Inhalte** : Möchten Sie Ihre Dokumente barrierefrei gestalten?</span><span class="sxs-lookup"><span data-stu-id="079bb-986">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="079bb-987">Die Barrierefreiheitsprüfung kann dies für Sie im Auge behalten, ohne Ihnen dabei in die Quere zu kommen.</span><span class="sxs-lookup"><span data-stu-id="079bb-987">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="079bb-988">Probieren Sie es aus, indem Sie auf „Überprüfen“ > „Barrierefreiheit überprüfen“ klicken. Wir werden Sie in der Statusleiste informieren, wenn wir etwas finden, dass Sie sich ansehen müssen.</span><span class="sxs-lookup"><span data-stu-id="079bb-988">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="079bb-989">**Schnelle Dateisuche:** Sie suchen nach einer Datei, an der Sie kürzlich gearbeitet haben?</span><span class="sxs-lookup"><span data-stu-id="079bb-989">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="079bb-990">Geben Sie einfach in das Suchfeld unter „Datei“ > „Start“ den Namen der gesuchten Datei ein.</span><span class="sxs-lookup"><span data-stu-id="079bb-990">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="079bb-991">**Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an.</span><span class="sxs-lookup"><span data-stu-id="079bb-991">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="079bb-992">Das Wechseln zwischen den Konten ist so einfach wie nie.</span><span class="sxs-lookup"><span data-stu-id="079bb-992">Switching between them has never been easier.</span></span> [<span data-ttu-id="079bb-993">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-993">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="079bb-p206">**Verbessern Sie mit Fokus Linie das Verständnis:** Gehen Sie ohne Ablenkungen von Zeile zu Zeile durch ein Dokument. Passen Sie den Fokus an, um eine, drei oder fünf Zeilen gleichzeitig in die Ansicht zu setzen. [Weitere Informationen](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="079bb-p206">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="079bb-997">**Speichern Sie Ihre Änderungen, während sie entstehen** : Laden Sie Ihre Dateien in OneDrive hoch, um sicherzustellen, dass alle Ihre Aktualisierungen automatisch gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-997">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="079bb-998">**Machen Sie andere mit \@Erwähnungen auf sich aufmerksam:** Mithilfe von @Erwähnungen in Kommentaren können Sie Kollegen informieren, wenn Sie deren Input benötigen.</span><span class="sxs-lookup"><span data-stu-id="079bb-998">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="079bb-999">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-999">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="079bb-1000">**Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können.</span><span class="sxs-lookup"><span data-stu-id="079bb-1000">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="079bb-1001">Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="079bb-1001">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="079bb-1002">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-1002">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="079bb-1003">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="079bb-1003">Office Suite</span></span>

- <span data-ttu-id="079bb-1004">**Schnelle Dateisuche:** Sie suchen nach einer Datei, an der Sie kürzlich gearbeitet haben?</span><span class="sxs-lookup"><span data-stu-id="079bb-1004">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="079bb-1005">Geben Sie einfach in das Suchfeld auf der Registerkarte "Datei" > "Öffnen" den Namen der gesuchten Datei ein.</span><span class="sxs-lookup"><span data-stu-id="079bb-1005">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="079bb-1006">**Speichern Sie Ihre Änderungen, während sie entstehen** : Laden Sie Ihre Dateien in OneDrive hoch, um sicherzustellen, dass alle Ihre Aktualisierungen automatisch gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1006">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="079bb-1007">**Kontrollmechanismen für den Datenschutz:** Neue aktualisierte und verbesserte Kontrollmechanismen für Diagnosedaten und verbundene Oberflächen.</span><span class="sxs-lookup"><span data-stu-id="079bb-1007">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="079bb-1008">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-1008">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="079bb-1009">**Office-Symbole mit neuem Look:** Die Office-Symbole wurden neu gestaltet, um die einfache, leistungsstarke und intelligente Office-Benutzeroberfläche widerzuspiegeln.</span><span class="sxs-lookup"><span data-stu-id="079bb-1009">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="079bb-1010">**Installation von Microsoft Teams** : Microsoft Teams ist in bestehenden Installationen von Office 365 ProPlus standardmäßig installiert.</span><span class="sxs-lookup"><span data-stu-id="079bb-1010">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="079bb-1011">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="079bb-1011">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="079bb-1014">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-1014">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="079bb-1015">Access</span><span class="sxs-lookup"><span data-stu-id="079bb-1015">Access</span></span>

- <span data-ttu-id="079bb-1016">Mit diesem Update wird ein Problem behoben, durch das bei einem Aggregat wie "Summe" das Ergebnis auf einen ganzzahligen Wert abgeschnitten werden kann.</span><span class="sxs-lookup"><span data-stu-id="079bb-1016">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="079bb-1017">Mit diesem Update wird ein Problem behoben, bei dem eine Union-Abfrage, die Verweise auf Remotetabellen enthält (z. B. SQL Server-Tabellen) möglicherweise dazu führt, dass Access geschlossen und neu gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-1017">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="079bb-1018">Mit diesem Update wird ein Problem in Microsoft Access behoben, das den Fehler &quot;Abfrage ist beschädigt&quot; verursachen kann, wenn eine Aktualisierungsabfrage ausgeführt oder eine UPDATE-Anweisung in SQL verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-1018">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="079bb-1019">Excel</span><span class="sxs-lookup"><span data-stu-id="079bb-1019">Excel</span></span>

- <span data-ttu-id="079bb-1020">Die Niederländische Tastenkombination für Dokumenttitel wurde in Alt-G geändert.</span><span class="sxs-lookup"><span data-stu-id="079bb-1020">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="079bb-1021">Es wurde ein Problem in Excel behoben, bei dem Makros, die Shapes oder Steuerelementen zugeordnet sind, möglicherweise eine falsche Fehlermeldung anzeigen oder an falschen Zielbereichen arbeiten.</span><span class="sxs-lookup"><span data-stu-id="079bb-1021">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="079bb-1022">Es wurde ein Problem mit "Suchen und ersetzen" gelöst, durch das sich die Position des Fokus im Dialogfeld änderte, nachdem das erste Element gefunden wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1022">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="079bb-1023">Hiermit wird ein Problem behoben, durch das die Änderung der Sortierung einer PivotTable und deren Aktualisierung während der gemeinsamen Dokumenterstellung mit anderen Benutzern zu einem Absturz führen kann.</span><span class="sxs-lookup"><span data-stu-id="079bb-1023">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="079bb-1024">Ein Problem wurde behoben, bei dem der Filter für eine OLAP-PivotTable auf einen Wert festgelegt wurde, der aus dem Cube entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1024">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="079bb-1025">Es wurde ein Problem mit Farben behoben, die in der Vorschau beim Einfügen von Diagrammen mithilfe von Diagrammvorlagen verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1025">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="079bb-1026">Ein Problem wurde behoben, durch das Punkt-/Liniendiagramme beim Ändern der Reihensammlung möglicherweise nicht ordnungsgemäß dargestellt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1026">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="079bb-1027">Ein Problem wurde behoben, durch das Wasserfall- und Trichterdiagramme beim Einfügen oder Löschen von Zellen nicht mehr mit Tabellen synchronisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1027">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="079bb-1028">Ein Konflikt beim Zusammenführen in Excel wurde behoben, durch den Benutzer aufgefordert wurden, die Arbeitsmappe erneut zu öffnen, um die Änderungen zu übernehmen.</span><span class="sxs-lookup"><span data-stu-id="079bb-1028">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="079bb-1029">Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1029">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="079bb-1030">Ein Problem wurde behoben, durch das ein Makro-Laufzeitfehler beim Aktivieren minimierter Fenster verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1030">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="079bb-1031">Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1031">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="079bb-1032">Ein Problem wurde behoben, durch das Ausschneide- und Einfügevorgänge neben einer Tabelle fehlschlugen, wenn die gemeinsame Dokumenterstellung zusammen mit anderen Benutzern durchgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1032">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="079bb-1033">Ein Problem wurde gelöst, das bei Änderung von benutzerdefinierten Eigenschaften von ausgeführten Makros zu Unterbrechungen bei der gemeinsamen Dokumentenerstellung führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-1033">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="079bb-1034">Es gab ein Problem, bei dem Sie keine Elemente aus dem Kombinationsfeld eines WPF-Formulars (Windows Presentation Foundation) auswählen konnten, das von einem Add-n geöffnet wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1034">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="079bb-1035">Es wurde ein Problem behoben, das bei der Suche nach zuletzt verwendeten Dateien zu einem Absturz geführt hat, wenn keine Arbeitsmappe geöffnet ist.</span><span class="sxs-lookup"><span data-stu-id="079bb-1035">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="079bb-1036">Ein Leistungsproblem mit asynchronen benutzerdefinierten Funktionen, das deren synchrone Ausführung zur Folge hatte.</span><span class="sxs-lookup"><span data-stu-id="079bb-1036">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="079bb-1037">Erhebliche Verbesserungen der Leistung beim Löschen von Spalten mit verbundenen Zellen.</span><span class="sxs-lookup"><span data-stu-id="079bb-1037">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="079bb-1038">Wir haben ein Problem gelöst, durch das das Auswählen einer Zelle nach dem Scrollen dazu führen konnte, dass die falsche Zelle ausgewählt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1038">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="079bb-1039">Ein Problem wurde behoben, bei dem die Verweis-Funktion einen Fehler zurückgeben kann.</span><span class="sxs-lookup"><span data-stu-id="079bb-1039">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="079bb-1040">Ein Problem wurde behoben, das beim Öffnen von in früheren Versionen von Office erstellten Arbeitsmappen in aktuellen Versionen von Office zu Programmabstürzen von Excel führen konnte.</span><span class="sxs-lookup"><span data-stu-id="079bb-1040">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="079bb-1041">Problem mit langsamer Leistung beim Klicken auf die Schaltfläche "Schriftfarbe", wenn eine Datei über eine umfangreiche bedingte Formatierung verfügt.</span><span class="sxs-lookup"><span data-stu-id="079bb-1041">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="079bb-1042">Ein Problem wurde behoben, bei dem der Druckbereich in der Seitenansicht nicht korrekt war.</span><span class="sxs-lookup"><span data-stu-id="079bb-1042">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="079bb-1043">Excel könnte ein Problem aufweisen, durch das das Bearbeiten einer geschützten Datei von einer nicht vertrauenswürdigen Netzwerkfreigabe zu einem Fehler in Excel geführt haben könnte.</span><span class="sxs-lookup"><span data-stu-id="079bb-1043">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="079bb-1044">Die Leistung der Filterung nach Farbe wurde deutlich verbessert.</span><span class="sxs-lookup"><span data-stu-id="079bb-1044">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="079bb-1045">Ein Problem wurde behoben, durch das Links in bestimmte geschützte Blätter nicht eingefügt werden konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-1045">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="079bb-1046">Mehr als 16 Add-Ins wurden aktiviert, die angezeigt werden, wenn der Add-In-Manager durchsucht wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-1046">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="079bb-1047">Diese Änderung umgeht ein Problem mit bestimmten Intel-Grafiktreibern durch Verwendung des Softwarerenderings.</span><span class="sxs-lookup"><span data-stu-id="079bb-1047">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="079bb-1048">Die Links von cid:-Bildern aus Outlook-Nachrichten können nun auf Anforderung erfolgreich unterbrochen werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1048">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="079bb-1049">Mit diesem Update wird ein Fehler behoben, der dazu führen kann, dass Office-Dokumente nicht auf OneDrive for Business hochgeladen werden können und die Fehlermeldung "Upload fehlgeschlagen" angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-1049">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="079bb-1050">Problem im Feature "Excel-Ideen" behoben: Ein Fehler trat auf, wenn das Add-In durch Klicken auf die Schaltfläche "Ideen" im Win32-Client geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1050">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="079bb-1051">Outlook</span><span class="sxs-lookup"><span data-stu-id="079bb-1051">Outlook</span></span>

- <span data-ttu-id="079bb-1052">Die Links von cid:-Bildern aus Outlook-Nachrichten können nun auf Anforderung erfolgreich unterbrochen werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1052">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="079bb-1053">Ein Problem wurde behoben, das dazu führte, dass bei Benutzern, die Ihr Postfach von Standard- auf moderne Authentifizierung aktualisiert hatten, das falschen Konto mit ihrem Outlook-Profil verknüpft wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1053">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="079bb-1054">Behebt ein Problem, durch das Web-Add-Ins auf von Digital Rights Management verwaltete Nachrichten zugreifen konnten, wenn dies nicht möglich sein sollte.</span><span class="sxs-lookup"><span data-stu-id="079bb-1054">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="079bb-1055">Es wurde ein Problem behoben, das bewirkt hat, dass die URL für den einfachen Mauszeiger bei einigen Safelinks nicht angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-1055">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="079bb-1056">Hiermit wird die Blockierungslogik für Anlagen in Outlook aktualisiert, um auch Python-Anlagen zu blockieren.</span><span class="sxs-lookup"><span data-stu-id="079bb-1056">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="079bb-1057">Es wurde ein Problem behoben, das bewirkt, dass einer Teilmenge von POP3-Benutzern alle E-Mails im nur-Text-Format anzeigt werden, und zwar unabhängig von den Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="079bb-1057">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="079bb-1058">Mit diesem Fix wird die Anzeige der HTML-formatierten Nachrichten wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="079bb-1058">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="079bb-1059">Es wurde ein Problem behoben, durch das Benutzern beim Kopieren von Elementen aus Ihrem primären Kalender in einen Gruppenkalender ein Berechtigungsfehler angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="079bb-1059">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="079bb-1060">Ein Problem wurde behoben, bei dem Benutzer nicht in der Lage waren, über eine Sprachausgabe auf Standortvorschläge zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="079bb-1060">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="079bb-1061">Es wurde ein Problem behoben, durch das Benutzer mit einer spürbaren Verzögerung beim Interagieren mit ihren Postfachordnern über Tastenkombinationen konfrontiert waren.</span><span class="sxs-lookup"><span data-stu-id="079bb-1061">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="079bb-1062">Es wurde ein Problem behoben, das einen Speicherverlust bei sehr langen Outlook-Sitzungen verursachte.</span><span class="sxs-lookup"><span data-stu-id="079bb-1062">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="079bb-1063">Es wurde ein Problem behoben, durch das Benutzern eine beim Öffnen des Dialogfelds "Regeln" die folgende Meldung "Die Regeln auf diesem Computer stimmen nicht mit den Regeln in Microsoft Exchange überein" angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1063">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="079bb-1064">Es wurde ein Problem behoben, das bei der Interaktion mit bestimmten Safelinks in Outlook zu einem Absturz führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-1064">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="079bb-1065">Ein Problem wurde behoben, das für Vorgesetzte Unklarheit darüber verursacht hat, ob eine Stellvertretung bereits auf eine bestimmte Besprechungsanfrage geantwortet hat.</span><span class="sxs-lookup"><span data-stu-id="079bb-1065">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="079bb-1066">Es wurde ein Problem behoben, das bei der Verarbeitung von Antworten der AutoErmittlung zu einem Absturz führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-1066">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="079bb-1067">Es wurde ein Problem behoben, das bewirkt hat, dass Benutzer ein leeres Meldungsfeld mit einer "OK"-Schaltfläche angezeigt bekamen, wenn Sie versuchten, den Support über den Kontext der Kontoerstellung zu kontaktieren.</span><span class="sxs-lookup"><span data-stu-id="079bb-1067">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="079bb-1068">Diese Änderung ermöglicht es Administratoren, eine Richtlinie zu aktivieren, um in den Eingabeaufforderungen der AutoErmittlung-Authentifizierung die bereitgestellten E-Mail-Konten vor UPN zu bevorzugen.</span><span class="sxs-lookup"><span data-stu-id="079bb-1068">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="079bb-1069">Standardmäßig bevorzugt AutoErmittlung den UPN des Kontos, wenn dieser verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="079bb-1069">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="079bb-1070">Ein Problem wurde behoben, durch das Benutzern Fehler beim Durchsuchen moderner Gruppen angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1070">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="079bb-1071">Ein Problem wurde behoben, das dazu führte, dass Outlook-Benutzer in bestimmten Szenarien im Zustand " Kennwort erforderlich " stecken geblieben sind.</span><span class="sxs-lookup"><span data-stu-id="079bb-1071">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="079bb-1072">Ein Problem wurde behoben, bei dem Benutzer Raumvorschläge für Besprechungen, die außerhalb der Verfügbarkeitszeiten dieses Raums stattfanden, einsehen konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-1072">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="079bb-1073">Ein Problem wurde behoben, durch das Benutzer beim Senden einer verschlüsselten E-Mail den Fehler "Verschlüsselungsalgorithmen wird nicht unterstützt" angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1073">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="079bb-1074">Ein Problem für nicht englischsprachige Benutzer wurde behoben, bei dem die Betreffzeile in einer E-Mail unglaublich klein war.</span><span class="sxs-lookup"><span data-stu-id="079bb-1074">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="079bb-1075">Ein Problem wurde behoben, durch das bei einigen Benutzern beim Hinzufügen eines sekundären Exchange-Kontos doppelte Sonderordner angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1075">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="079bb-1076">Ein Problem wurde behoben, das einen Absturz verursachte, wenn Benutzer versuchten, aus einer "Verpasste Unterhaltung"-Nachricht heraus eine Regel zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="079bb-1076">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="079bb-1077">Es wurde ein Problem mit der Auswahl des SMIME-Algorithmus behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-1077">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="079bb-1078">Es wurde ein Problem behoben, bei dem Richtlinientipps bei Verwendung eines alternativen Absenders nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1078">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="079bb-1079">Ein Problem wurde behoben, durch das Benutzer einen Speicherverlust im Outlook-Prozess beobachten konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-1079">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="079bb-1080">Ein Problem wurde behoben, das zu sporadischen Abstürzen führte, wenn Benutzer ihre Anwesenheitsinformationen aktualisierten.</span><span class="sxs-lookup"><span data-stu-id="079bb-1080">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="079bb-1081">Ein Problem wurde behoben, das bewirkt, dass die aktuelle Ordnersuche zweitweise fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="079bb-1081">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="079bb-1082">Ein Problem wurde behoben, bei dem einige Benutzer beim Versuch, ihre Cloud-Einstellungen für Outlook abzurufen, auf Authentifizierungsfehler stießen.</span><span class="sxs-lookup"><span data-stu-id="079bb-1082">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="079bb-1083">Es wurde ein Problem behoben, durch das die Such-Feedback-Umgebung zum Hängen gebracht wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1083">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="079bb-1084">Es wurde ein Problem behoben, das bei der Verarbeitung von Antworten der AutoErmittlung zu einem Absturz führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-1084">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="079bb-1085">Ein Problem wurde behoben, das zu sporadischen Abstürzen führte, wenn Benutzer ihre Anwesenheitsinformationen aktualisierten.</span><span class="sxs-lookup"><span data-stu-id="079bb-1085">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="079bb-1086">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="079bb-1086">PowerPoint</span></span>

- <span data-ttu-id="079bb-1087">Ein Problem wurde behoben, bei dem einige Add-Ins unerwartete Fehler bei Formen in Diagrammen verursachen konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-1087">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="079bb-1088">Die Links von cid:-Bildern aus Outlook-Nachrichten können nun auf Anforderung erfolgreich unterbrochen werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1088">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="079bb-1089">Diese Änderung stellt den barrierefreien Namen für PowerPoint-Videosteuerelemente wieder her.</span><span class="sxs-lookup"><span data-stu-id="079bb-1089">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="079bb-1090">Wir haben ein Problem behoben, das verhindern konnte, dass einige Animationen starteten.</span><span class="sxs-lookup"><span data-stu-id="079bb-1090">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="079bb-1091">Ein Problem wurde behoben, durch das beim Kopieren einer Folie aus einer Präsentation in eine andere möglicherweise doppelte Master erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1091">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="079bb-1092">Bei Dateien mit neuen modernen Kommentaren wird eine gelbe Warnung angezeigt, wenn sie in einer nicht unterstützten Version geöffnet werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1092">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="079bb-1093">Zuverlässigkeitsfix: Ein Problem wurde behoben, bei ein Add-In von Drittanbietern zu einem Absturz von PowerPoint führen konnte.</span><span class="sxs-lookup"><span data-stu-id="079bb-1093">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="079bb-1094">Ein Problem wurde behoben, bei dem Katakana-Zeichen mit halber Breite in vertikalen Textfeldern in PowerPoint nicht ordnungsgemäß gedreht wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1094">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="079bb-1095">Project</span><span class="sxs-lookup"><span data-stu-id="079bb-1095">Project</span></span>

- <span data-ttu-id="079bb-1096">Ein Problem wurde behoben, durch das Benutzer unter Windows 7 Projekte aus Project Web-App und SharePoint-Websites öffnen können.</span><span class="sxs-lookup"><span data-stu-id="079bb-1096">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="079bb-1097">Ein Problem wurde identifiziert, bei dem Benutzer beim Öffnen eines schreibgeschützten Projekts möglicherweise mehrere Meldungen erhielten.</span><span class="sxs-lookup"><span data-stu-id="079bb-1097">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="079bb-1098">Der Befehl "Alles abgleichen" löst eine Ressourcenüberlastung nicht richtig auf.</span><span class="sxs-lookup"><span data-stu-id="079bb-1098">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="079bb-1099">Bei einer Aufgabe mit keiner Arbeit an einem Vorgang kann der Vorgang möglicherweise nicht als erledigt gekennzeichnet werden und wird stets bei 99 % angezeigt.</span><span class="sxs-lookup"><span data-stu-id="079bb-1099">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="079bb-1100">Visio</span><span class="sxs-lookup"><span data-stu-id="079bb-1100">Visio</span></span>

- <span data-ttu-id="079bb-1101">Das Exportieren als SVG aus Visio funktionierte für eine Vielzahl von Shapes nicht.</span><span class="sxs-lookup"><span data-stu-id="079bb-1101">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="079bb-1102">Word</span><span class="sxs-lookup"><span data-stu-id="079bb-1102">Word</span></span>

- <span data-ttu-id="079bb-1103">Diese Änderung führt zu Leistungsverbesserungen beim Öffnen von Dokumenten mit Word.</span><span class="sxs-lookup"><span data-stu-id="079bb-1103">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="079bb-1104">Die Links von cid:-Bildern aus Outlook-Nachrichten können nun auf Anforderung erfolgreich unterbrochen werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1104">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="079bb-1105">Ein Problem wurde behoben, das zu Skalierungsproblemen führen konnte, wenn auf Deskjet-Druckern gedruckt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1105">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="079bb-1106">Ein Problem wurde behoben, durch dass beim Nachverfolgen von Änderungen der Vorgang manchmal zu einer Endlosschleife führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-1106">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="079bb-1107">Verschiedene Probleme behoben, bei denen die APP beim Herunterfahren hängen bleiben könnte.</span><span class="sxs-lookup"><span data-stu-id="079bb-1107">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="079bb-1108">Außerdem wurden Absturzursachen im Zusammenhang mit bestimmten Add-Ins behoben.</span><span class="sxs-lookup"><span data-stu-id="079bb-1108">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="079bb-1109">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="079bb-1109">Office Suite</span></span>

- <span data-ttu-id="079bb-1110">Behebung eines Problems, aufgrund dessen der neue Zeitname "Reiwa" in Hiragana und Kanji als Rechtschreibfehler oder Grammatikfehler eingestuft wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1110">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="079bb-1111">Ein Problem wurde behoben, bei dem Benutzer beim Versuch, in SharePoint 2016 gespeicherte Dateien freizugeben, die Meldung "Leider verhindert etwas, dass wir dies freigeben" erhielten.</span><span class="sxs-lookup"><span data-stu-id="079bb-1111">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="079bb-1112">Ein Problem wurde behoben, das zu Datenverlusten in Sitzungen führen konnte, bei denen sowohl die gemeinsame Dokumenterstellung als auch die Offlinebearbeitung in PowerPoint genutzt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1112">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="079bb-1113">Dieser Fix beseitigt die Ursache für einen Absturz, der beim Öffnen einer Datei auftreten konnte.</span><span class="sxs-lookup"><span data-stu-id="079bb-1113">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="079bb-1114">Verhindert, dass für PowerPoint-Benutzer bei Onlinepräsentationen Fehler auftreten.</span><span class="sxs-lookup"><span data-stu-id="079bb-1114">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="079bb-1115">In einigen Fällen wurde für eine von der Synchronisierungs-Engine gesicherte SharePoint-Datei "Gespeichert" angezeigt, ohne dass die Änderungen tatsächlich gespeichert wurden, was zu einem Datenverlust führte.</span><span class="sxs-lookup"><span data-stu-id="079bb-1115">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="079bb-1116">Es wurde ein Problem behoben, bei dem Benutzer möglicherweise nicht in der Lage waren, Word-, Excel- und PowerPoint-Dokumente zu speichern.</span><span class="sxs-lookup"><span data-stu-id="079bb-1116">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="079bb-1117">Dieses Problem betrifft Benutzer, die eine neue Datei erstellen und die Option „Als Dialog speichern“ öffnen, nachdem Sie auf das Symbol „Speichern“ geklickt oder STRG+S gedrückt haben.</span><span class="sxs-lookup"><span data-stu-id="079bb-1117">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="079bb-1118">Ein Leistungsproblem unter Win7 wurde behoben, bei dem es in allen Apps ca. 4 Sekunden dauerte, bis der Katalog "Formen einfügen" auf dem Menüband angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1118">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="079bb-1119">Ein Fehler wurde behoben, bei dem im Informationsbereich der Backstage-Ansicht keine Barrierefreiheitsinformationen angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1119">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="079bb-1120">Verbessert die Zuverlässigkeit des Office-Updateprozesses hinsichtlich der Registrierungsintegrität.</span><span class="sxs-lookup"><span data-stu-id="079bb-1120">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="079bb-1121">Es wurde ein Problem behoben, bei dem Office-Aktualisierungen möglicherweise unerwartet Dateien aus dem Office CDN anstelle der beabsichtigten Quelle heruntergeladen haben, beispielsweise eine lokale oder Netzwerkfreigabe oder einen vom Configuration Manager bereitgestellten Speicherort.</span><span class="sxs-lookup"><span data-stu-id="079bb-1121">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="079bb-1122">Es wurde ein Problem behoben, bei dem Office-Update-Nachrichten in einer anderen Sprache als erwartet angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1122">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="079bb-1123">In Zukunft entsprechen Office-Update-Nachrichten ordnungsgemäß der Windows-Anzeigesprache.</span><span class="sxs-lookup"><span data-stu-id="079bb-1123">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="079bb-1124">Es wurde ein Problem behoben, bei dem ein Update in bestimmten Fällen nicht installiert wurde, wenn der Benutzer kein Administrator ist und das Systemkonto keine Netzwerkverbindung hatte.</span><span class="sxs-lookup"><span data-stu-id="079bb-1124">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="079bb-1125">Unter bestimmten Umständen werden Office-Verknüpfungen nach einem Update möglicherweise nicht mehr angezeigt.</span><span class="sxs-lookup"><span data-stu-id="079bb-1125">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="079bb-1126">Dieses Update erhöht die Zuverlässigkeit beim Veröffentlichen von Office-Verknüpfungen.</span><span class="sxs-lookup"><span data-stu-id="079bb-1126">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="079bb-1127">Ein Problem wurde behoben, bei dem Updates in getakteten Netzwerken möglicherweise unerwartet blockiert wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1127">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="079bb-1128">Ein Bug in der Einstellung des Stichtags für ODT- und GPO-Updates wurde behoben, bei dem der relative Stichtag nur beim ersten Festlegen funktionierte. Der Fix aktiviert den relativen Stichtag für spätere Updates.</span><span class="sxs-lookup"><span data-stu-id="079bb-1128">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="079bb-1129">Die Zuverlässigkeit beim Herunterladen von Office-Updates wurde verbessert, indem Downloads fortgesetzt werden, die möglicherweise zuvor unterbrochen wurden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1129">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="079bb-1130">Probleme im Zusammenhang mit der Anpassung der Eigenschaft "TextBox/ Form automatisch anpassen" in Drittanbieter-Plug-ins.</span><span class="sxs-lookup"><span data-stu-id="079bb-1130">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="079bb-1131">Es wurde ein Problem behoben, bei dem große Strukturansichten zu einem Absturz führen konnten.</span><span class="sxs-lookup"><span data-stu-id="079bb-1131">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="079bb-1132">Um die Sicherheit der Office-Kunden zu schützen, sind jetzt Microsoft Office-Updates ausschließlich mit dem SHA-2-Algorithmus signiert.</span><span class="sxs-lookup"><span data-stu-id="079bb-1132">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1902-january-14"></a><span data-ttu-id="079bb-1134">Version 1902: 14. Januar</span><span class="sxs-lookup"><span data-stu-id="079bb-1134">Version 1902: January 14</span></span>
<span data-ttu-id="079bb-1135">*Version 1902 (Build 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="079bb-1135">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="079bb-1136">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-1136">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="079bb-1138">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="079bb-1138">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="079bb-1139">Excel</span><span class="sxs-lookup"><span data-stu-id="079bb-1139">Excel</span></span>

- <span data-ttu-id="079bb-1140">Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1140">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="079bb-1141">Outlook</span><span class="sxs-lookup"><span data-stu-id="079bb-1141">Outlook</span></span>

- <span data-ttu-id="079bb-1142">Behebt ein Problem, durch das Benutzer beim Senden einer verschlüsselten E-Mail den Fehler "Verschlüsselungsalgorithmen wird nicht unterstützt" angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="079bb-1142">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="079bb-1143">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="079bb-1143">PowerPoint</span></span>

- <span data-ttu-id="079bb-1144">Bei Dateien mit neuen modernen Kommentaren wird eine gelbe Warnung angezeigt, wenn sie in einer nicht unterstützten Version geöffnet werden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1144">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="079bb-1145">Word</span><span class="sxs-lookup"><span data-stu-id="079bb-1145">Word</span></span>

- <span data-ttu-id="079bb-1146">Diese Änderung führt zu Leistungsverbesserungen beim Öffnen von Dokumenten mit Word.</span><span class="sxs-lookup"><span data-stu-id="079bb-1146">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1808-january-14"></a><span data-ttu-id="079bb-1148">Version 1808: 14. Januar</span><span class="sxs-lookup"><span data-stu-id="079bb-1148">Version 1808: January 14</span></span>
<span data-ttu-id="079bb-1149">*Version 1808 (Build 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="079bb-1149">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="079bb-1150">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="079bb-1150">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

> [!NOTE]
> <span data-ttu-id="079bb-1152">Wenn Sie Hilfe bei einem Problem mit der Nutzung von Office benötigen, empfehlen wir, dass Sie Ihre Frage im [Microsoft Answers-Forum](https://answers.microsoft.com/) oder in der [Tech-Community](https://techcommunity.microsoft.com/) veröffentlichen, oder Sie können sich an den [Support](https://support.microsoft.com/contactus) wenden.</span><span class="sxs-lookup"><span data-stu-id="079bb-1152">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (ADMIN CENTER-METADATENINHALT NICHT ÄNDERN BEGINN)
[//]: # (|Win32|DC|Production| |16.0.12527.21330|version-2002-november-10|)
[//]: # (|Win32|DC|Production| |16.0.12527.21236|version-2002-october-13|)
[//]: # (|Win32|DC|Production| |16.0.12527.21104|version-2002-september-08|)
[//]: # (|Win32|DC|Production| |16.0.12527.20988|version-2002-july-11|)
[//]: # (|Win32|DC|Production| |16.0.12527.20880|version-2002-july-14|)
[//]: # (ADMIN CENTER-METADATENINHALT NICHT ÄNDERN ENDE)

---
title: Versionshinweise zum monatlichen Kanal (gezielt)
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt der Zielgruppe von Insiders Slow die aktuelle Liste neuer Features, Fehlerkorrekturen oder bekannter Probleme bereit.
ms.openlocfilehash: 41dba1efa79735aafd74b318fd49c7c3211736e3
ms.sourcegitcommit: e9b127c7dfd80f3beb3c9aa9dadfb9e7f442c58c
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/04/2020
ms.locfileid: "44563675"
---
# <a name="release-notes-for-office-monthly-channel-targeted"></a><span data-ttu-id="b2182-103">Versionshinweise zu Office im monatlichen Kanal (gezielt)</span><span class="sxs-lookup"><span data-stu-id="b2182-103">Release Notes for Office Monthly Channel (Targeted)</span></span>

<span data-ttu-id="b2182-104">Dieser Artikel enthält Versionshinweise zu Builds von Word, Excel, PowerPoint, Outlook, Access und Project für Windows Desktop für den monatlichen Kanal (gezielt).</span><span class="sxs-lookup"><span data-stu-id="b2182-104">This article contains release notes for Monthly Channel (Targeted) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop.</span></span> <span data-ttu-id="b2182-105">Jede Woche heben wir interessante neuer Features, wichtige Fixes und wesentliche Probleme hervor, über die wir Sie gerne informieren möchten.</span><span class="sxs-lookup"><span data-stu-id="b2182-105">Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about.</span></span> <span data-ttu-id="b2182-106">Bitte beachten Sie, dass wir Features (und häufig auch Fixes) häufig über einen Zeitraum in den monatlichen Kanal (gezielt) einführen.</span><span class="sxs-lookup"><span data-stu-id="b2182-106">Note that we often roll out features (and sometimes even fixes) to Monthly Channel (Targeted) over a period of time.</span></span> <span data-ttu-id="b2182-107">Auf diese Weise können wir sicherstellen, dass alles reibungslos funktioniert, bevor das Feature für ein breiteres Publikum bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="b2182-107">This allows us to ensure that things are working smoothly before releasing the feature to a wider audience.</span></span> <span data-ttu-id="b2182-108">Wenn also im Folgenden etwas nicht beschrieben wird, machen Sie sich keine Sorgen, es wird bald behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="b2182-108">So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="b2182-109">Wir nehmen einige Änderungen an den Updatekanälen für Microsoft 365-Apps vor, unter anderem fügen wir einen neuen Updatekanal hinzu (Monatlicher Enterprise-Kanal) und ändern die Namen der vorhandenen Updatekanäle.</span><span class="sxs-lookup"><span data-stu-id="b2182-109">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="b2182-110">Um mehr zu erfahren, [lesen Sie diesen Artikel](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="b2182-110">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="b2182-111">Das Veröffentlichungsdatum der Versionshinweise stimmt möglicherweise nicht mit dem tatsächlichen Veröffentlichungsdatum des Builds überein.</span><span class="sxs-lookup"><span data-stu-id="b2182-111">The release notes publication date may not match the actual build release date.</span></span>


[//]: # (NICHT ENTFERNEN)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-june-04"></a><span data-ttu-id="b2182-115">Version 2005: Juni 04</span><span class="sxs-lookup"><span data-stu-id="b2182-115">Version 2005: June 04</span></span>
<span data-ttu-id="b2182-116">*Version 2005 (Build 12827,20320)*</span><span class="sxs-lookup"><span data-stu-id="b2182-116">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b2182-118">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b2182-118">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="b2182-119">Access</span><span class="sxs-lookup"><span data-stu-id="b2182-119">Access</span></span>

- <span data-ttu-id="b2182-120">**Halten Sie sich mit den Zeiten auf dem neuesten Stand! Der erweiterte Datentyp Date/Time hat eine bessere Genauigkeit.:** Einführung eines neuen und verbesserten Datentyps.</span><span class="sxs-lookup"><span data-stu-id="b2182-120">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="b2182-121">Um die Syntax Kompatibilität mit SQL zu verbessern und die Genauigkeit und den Detailgrad in Datensätzen zu erhöhen, die Datums-und Uhrzeitangaben enthalten, implementieren wir den datetime2-Datentyp in Access.</span><span class="sxs-lookup"><span data-stu-id="b2182-121">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="b2182-122">Dieser zusätzliche Date & time-Datentyp enthält einen größeren Datumsbereich (0001-01-01 bis 9999-12-31) mit einer höher spezifizierten Zeitgenauigkeit (nicht Sekunden), die Sie bereitstellen und Berechnungen ausführen können.</span><span class="sxs-lookup"><span data-stu-id="b2182-122">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="b2182-123">Um zu aktivieren, wählen Sie neues Feld > Datum & Zeit verlängert.</span><span class="sxs-lookup"><span data-stu-id="b2182-123">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="b2182-124">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b2182-124">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="b2182-125">Excel</span><span class="sxs-lookup"><span data-stu-id="b2182-125">Excel</span></span>

- <span data-ttu-id="b2182-126">**Erstellen von PivotTables aus Datasets in Power BI in Excel:** Sie können PivotTables in Excel erstellen, die mit wenigen Klicks mit in Power BI gespeicherten Datasets verbunden sind.</span><span class="sxs-lookup"><span data-stu-id="b2182-126">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="b2182-127">Auf diese Weise können Sie das Beste aus PivotTables und Power BI erhalten.</span><span class="sxs-lookup"><span data-stu-id="b2182-127"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="b2182-128">Berechnen, zusammenfassen und Analysieren Ihrer Daten mit PivotTables aus ihren Secure Power BI-Datasets.</span><span class="sxs-lookup"><span data-stu-id="b2182-128">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="b2182-129">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-129">Outlook</span></span>

- <span data-ttu-id="b2182-130">**Option zum schnellen Öffnen von Elementen aus der vorherigen Outlook-Sitzung:** Wir haben eine Option zum schnellen Öffnen von Elementen aus einer vorherigen Outlook-Sitzung hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="b2182-130">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b2182-133">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-133">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="b2182-134">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b2182-134">PowerPoint</span></span>

- <span data-ttu-id="b2182-135">Dadurch wird ein Absturz behoben, wenn Benutzer sowohl moderne als auch ältere Kommentare in einer Datei haben, wodurch ein Upgrade der Kommentare ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="b2182-135">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b2182-136">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b2182-136">Office Suite</span></span>

- <span data-ttu-id="b2182-137">Wir haben das Problem mit der ValidateInstall-Fehlerrate behoben, indem wir die Bing Addon-Installationsüberprüfung standardmäßig auf true festlegen und den MSI-Rückgabe Erfolg als Installationserfolg in Betracht ziehen.</span><span class="sxs-lookup"><span data-stu-id="b2182-137">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-may-29"></a><span data-ttu-id="b2182-139">Version 2005:29. Mai</span><span class="sxs-lookup"><span data-stu-id="b2182-139">Version 2005: May 29</span></span>
<span data-ttu-id="b2182-140">*Version 2005 (Build 12827,20268)*</span><span class="sxs-lookup"><span data-stu-id="b2182-140">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b2182-142">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b2182-142">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="b2182-143">Excel</span><span class="sxs-lookup"><span data-stu-id="b2182-143">Excel</span></span>

- <span data-ttu-id="b2182-144">**Blattansicht:** Sortieren/Filtern bei der Zusammenarbeit mit anderen Benutzern in Excel Desktop.</span><span class="sxs-lookup"><span data-stu-id="b2182-144">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="b2182-145">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-145">Outlook</span></span>

- <span data-ttu-id="b2182-146">**Zusätzliche Schaltflächen zu Outlook-Popupbenachrichtigungen hinzugefügt:** Schaltflächen für die schnell Aktion werden jetzt in Outlook-Popupbenachrichtigungen angezeigt, wenn Outlook unter Windows 10 ausführt wird.</span><span class="sxs-lookup"><span data-stu-id="b2182-146">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b2182-149">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-149">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="b2182-150">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-150">Outlook</span></span>

- <span data-ttu-id="b2182-151">Es wurde ein Problem behoben, aufgrund dessen Benutzer von Windows 10 Server-Versionen den Warnstatus "Antivirus" angezeigt haben: ungültig.</span><span class="sxs-lookup"><span data-stu-id="b2182-151">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="b2182-152">Diese Version von Windows unterstützt die Antivirus-Erkennung, aber trotz der ordnungsgemäßen Installation von Anti-Virus wurde kein Antivirus gefunden.</span><span class="sxs-lookup"><span data-stu-id="b2182-152">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b2182-153">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b2182-153">Office Suite</span></span>

- <span data-ttu-id="b2182-154">Der Office-Host stürzte in Windows ab, wenn ein Add-in aktiviert wird, während der Registrierungsschlüssel HKEY_CURRENT_USER \SOFTWARE\Microsoft\Internet Explorer\Main\TabProcGrowth auf NULL festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="b2182-154">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="b2182-155">Diese Änderung würde dieses Problem beheben.</span><span class="sxs-lookup"><span data-stu-id="b2182-155">This change would fix this issue.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-may-21"></a><span data-ttu-id="b2182-157">Version 2005:21. Mai</span><span class="sxs-lookup"><span data-stu-id="b2182-157">Version 2005: May 21</span></span>
<span data-ttu-id="b2182-158">*Version 2005 (Build 12827,20210)*</span><span class="sxs-lookup"><span data-stu-id="b2182-158">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b2182-160">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b2182-160">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b2182-161">Excel</span><span class="sxs-lookup"><span data-stu-id="b2182-161">Excel</span></span>

- <span data-ttu-id="b2182-162">**Abrufen von Organisationsdaten aus Power BI mithilfe von Excel-Datentypen:** Sie können Daten aus Ihrer Organisation mithilfe von Excel-Datentypen einfügen.</span><span class="sxs-lookup"><span data-stu-id="b2182-162">**Get Organization Data from Power BI using Excel Data Types:** You can insert data from your Organization using Excel Data Types.</span></span> <span data-ttu-id="b2182-163">Konvertieren Sie eine Zelle in Ihrer Arbeitsmappe, und erhalten Sie weitere Informationen, und aktualisieren Sie die Daten jederzeit, wenn Sie dies benötigen.</span><span class="sxs-lookup"><span data-stu-id="b2182-163">Convert a cell in your workbook and get additional information, and refresh the data anytime you need!</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b2182-166">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-166">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b2182-167">Excel</span><span class="sxs-lookup"><span data-stu-id="b2182-167">Excel</span></span>

- <span data-ttu-id="b2182-168">Es wurde ein Problem behoben, bei dem Excel nach der Verwendung von STRG + UMSCHALT + Pfeiltasten nicht mehr reagierte, um zu scrollen, wenn das Excel-Fenster über Teams freigegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-168">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="b2182-169">In einigen Fällen führt das Klicken auf einen Hyperlink zu einer Stelle in derselben Arbeitsmappe dazu, dass die Arbeitsmappe ausgeblendet wird.</span><span class="sxs-lookup"><span data-stu-id="b2182-169">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="b2182-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-170">Outlook</span></span>

- <span data-ttu-id="b2182-171">Es wurde ein Problem mit dem CLP-Überwachungsereignis für die Bezeichnung "Antwort/weiterleiten" behoben.</span><span class="sxs-lookup"><span data-stu-id="b2182-171">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="b2182-172">Es wurde ein Problem behoben, aufgrund dessen Benutzer beim Senden von Feedback von einer Administratorbenachrichtigung einen Absturz festgestellt haben.</span><span class="sxs-lookup"><span data-stu-id="b2182-172">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-may-14"></a><span data-ttu-id="b2182-174">Version 2005:14. Mai</span><span class="sxs-lookup"><span data-stu-id="b2182-174">Version 2005: May 14</span></span>
<span data-ttu-id="b2182-175">*Version 2005 (Build 12827,20160)*</span><span class="sxs-lookup"><span data-stu-id="b2182-175">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b2182-177">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b2182-177">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b2182-178">Excel</span><span class="sxs-lookup"><span data-stu-id="b2182-178">Excel</span></span>

- <span data-ttu-id="b2182-179">**Automatisches Anwenden oder empfehlen von Sensitivitäts Bezeichnungen:** Office kann eine Vertraulichkeits Bezeichnung basierend auf dem erkannten vertraulichen Inhalt empfehlen oder automatisch anwenden.</span><span class="sxs-lookup"><span data-stu-id="b2182-179">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b2182-180">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b2182-180">PowerPoint</span></span>

- <span data-ttu-id="b2182-181">**Kein Klicker erforderlich: Ihre Ohrhörer haben Sie abgedeckt:** Verwenden Sie Ihre Surface-Ohrhörer, um Ihre PowerPoint-Präsentationen zu steuern.</span><span class="sxs-lookup"><span data-stu-id="b2182-181">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="b2182-182">Wichtig: Sie müssen ihre Oberflächen Ohrhörer in der Surface Audio-App für Windows 10 koppeln, um Gesten zum Steuern von Präsentationen zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="b2182-182">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="b2182-183">Anweisungen zum Einstieg in die Surface-Audioanwendung unter Windows 10 finden Sie hier.</span><span class="sxs-lookup"><span data-stu-id="b2182-183">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="b2182-184">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b2182-184">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="b2182-185">**Automatisches Anwenden oder empfehlen von Sensitivitäts Bezeichnungen:** Office kann eine Vertraulichkeits Bezeichnung basierend auf dem erkannten vertraulichen Inhalt empfehlen oder automatisch anwenden.</span><span class="sxs-lookup"><span data-stu-id="b2182-185">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="b2182-186">Word</span><span class="sxs-lookup"><span data-stu-id="b2182-186">Word</span></span>

- <span data-ttu-id="b2182-187">**Automatisches Anwenden oder empfehlen von Sensitivitäts Bezeichnungen:** Office kann eine Vertraulichkeits Bezeichnung basierend auf dem erkannten vertraulichen Inhalt empfehlen oder automatisch anwenden.</span><span class="sxs-lookup"><span data-stu-id="b2182-187">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b2182-190">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-190">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="b2182-191">Excel</span><span class="sxs-lookup"><span data-stu-id="b2182-191">Excel</span></span>

- <span data-ttu-id="b2182-192">Die Größe der Steuerelemente zur Bearbeitung von Zellreferenzen im Dialogfeld "Benutzerdefinierte Fehlerindikatoren", das bei Diagrammen verwendet wird, wurde erhöht.</span><span class="sxs-lookup"><span data-stu-id="b2182-192">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="b2182-193">Ein Problem wurde behoben, bei dem die Diagrammdatentabelle Werte in einer Datumsachse nicht korrekt rendern konnte.</span><span class="sxs-lookup"><span data-stu-id="b2182-193">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="b2182-194">Es wurde ein Problem behoben, bei dem Seitenumbrüche nicht deaktiviert werden konnten, nachdem die Seitenlayout- oder Seitenumbruchsvorschau angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-194">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="b2182-195">Es wurde ein Problem behoben, bei dem Diagrammlinienarten nach dem Ein- und Ausblenden von Spalten mit Seriendaten verloren gehen konnten.</span><span class="sxs-lookup"><span data-stu-id="b2182-195">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="b2182-196">Es wurde ein Problem behoben, bei dem das Einfügen einer Spalte in eine gefilterte Liste länger dauern würde als erwartet.</span><span class="sxs-lookup"><span data-stu-id="b2182-196">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="b2182-197">Ein Problem mit der Skalierung von Kontrollkästchen in Formularsteuerelementen beim Drucken wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b2182-197">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="b2182-198">Es wurde ein Problem behoben, bei dem der externe Link nach dem erneuten Öffnen der Datei nicht mehr funktioniert, wenn der Dateipfad zu lang ist.</span><span class="sxs-lookup"><span data-stu-id="b2182-198">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="b2182-199">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-199">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="b2182-200">Application.Evaluate (VBA) funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.</span><span class="sxs-lookup"><span data-stu-id="b2182-200">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="b2182-201">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-201">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="b2182-202">Diese Änderung behebt ein Problem, bei dem Informationen zur bedingten Formatierung (CF) nicht korrekt in XLSB-Dateien gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-202">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="b2182-203">Diese Änderung behebt ein Problem, bei dem das Bestimmtheitsmaß der Diagrammtrendlinie (im Fall des erzwungenen y-Achsenabschnitts) falsch war, obwohl die Funktion LINEST den richtigen Wert zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="b2182-203">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="b2182-204">Diese Änderung behebt ein Problem, bei dem benutzerdefinierte Diagramm-Trendlinienformatierungen nicht immer gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-204">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="b2182-205">Ein Absturz kann auftreten, wenn Sie versuchen, Änderungen auf einem neuen Blatt für eine Arbeitsmappe mithilfe des Legacy Modus "freigegebene Arbeitsmappe" aufzulisten.</span><span class="sxs-lookup"><span data-stu-id="b2182-205">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="b2182-206">Das Problem, bei dem es sein konnte, dass benutzerdefinierte Formatierungen in Pivot-Diagrammen nicht gespeichert wurden, wenn die Option "Invertieren, wenn negativ" aktiviert war, wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b2182-206">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="b2182-207">Es wurde ein Problem behoben, bei dem die benutzerdefinierte Formatierung für einen einzelnen Datenpunkt in einem Pivot-Diagramm nicht gespeichert wurde, wenn die Option "Invertieren, wenn negativ" ausgewählt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-207">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="b2182-208">Diese Änderung behebt ein Problem, bei dem das in eine CSV-Datei hochgeladene @-Zeichen dazu führte, dass die Zeichenfolge nach dem @-Zeichen in eine Formel konvertiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-208">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="b2182-209">Es wurde ein Problem behoben, bei dem Dezimalwerte in der SEQUENCE-Funktion nicht korrekt gerundet wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-209">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="b2182-210">OneNote</span><span class="sxs-lookup"><span data-stu-id="b2182-210">OneNote</span></span>

- <span data-ttu-id="b2182-211">Ein Problem beim Speichern von Zeilenumbrüchen als vertikale Registerkarten wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b2182-211">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="b2182-212">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-212">Outlook</span></span>

- <span data-ttu-id="b2182-213">Behebt ein Problem, das dazu führte, dass Benutzer keine "Persönliche Kontaktgruppe" als "Besprechungsteilnehmer" hinzufügen konnten.</span><span class="sxs-lookup"><span data-stu-id="b2182-213">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="b2182-214">Es wurde ein Problem behoben, bei dem die Schaltfläche kategorisieren für Gruppenkalender im Office-Menüband deaktiviert war.</span><span class="sxs-lookup"><span data-stu-id="b2182-214">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="b2182-215">Es wurde ein Problem behoben, durch das Outlook nach einem Windows-Update beim Öffnen von lokal gespeicherten MSG- oder OFT-Dateien abstürzte.</span><span class="sxs-lookup"><span data-stu-id="b2182-215">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="b2182-216">Es wurde ein Problem behoben, bei dem Gruppenordner von Unternehmenskunden, die nicht implementiert sind oder nicht funktionieren, in Outlook zu der Meldung "reagiert nicht" führte.</span><span class="sxs-lookup"><span data-stu-id="b2182-216">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="b2182-217">Es wurde ein Problem behoben, aufgrund dessen sehr lange safelinks, auf die Benutzer im Outlook-Desktop Client geklickt haben, aufgrund des Abschneidens nicht mehr belastet wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-217">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="b2182-218">Es wurde ein Problem behoben, bei dem Outlook-Ordner mit Namen, die DBCS-Zeichen (Doublebyte-Zeichensatz) enthalten, bei der Synchronisierung mit dem Server zeitweise verschwanden.</span><span class="sxs-lookup"><span data-stu-id="b2182-218">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="b2182-219">Dazu musste Outlook mit einem IMAP-Konto konfiguriert und auf einem System mit dem Gebietsschema „Japanisch“ ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="b2182-219">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="b2182-220">Es wurde ein Problem behoben, aufgrund dessen Löschregeln, die für andere Postfächer als das primäre Postfach des Benutzers erstellt wurden, ungültig werden.</span><span class="sxs-lookup"><span data-stu-id="b2182-220">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="b2182-221">Es wurde ein Problem behoben, aufgrund dessen Anlagen beim Weiterleiten einer verschlüsselten Nachricht verworfen wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-221">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="b2182-222">Es wurde ein Problem behoben, aufgrund dessen Besprechungen, die länger als zwei Monate entfernt sind, einen Besprechungs Betreff nicht im Planungs-Assistenten anzeigen konnten.</span><span class="sxs-lookup"><span data-stu-id="b2182-222">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="b2182-223">Behebt ein Problem, das dazu führte, dass Benutzer beim Weiterleiten großer HTML-Nachrichten den Nachrichtentext abgeschnitten sahen.</span><span class="sxs-lookup"><span data-stu-id="b2182-223">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="b2182-224">Es wurde die Möglichkeit des Erzwingens der S/MIME-Standardsignatur-Konfiguration über eine Gruppenrichtlinie hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="b2182-224">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b2182-225">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b2182-225">PowerPoint</span></span>

- <span data-ttu-id="b2182-226">Es wurde ein Problem behoben, bei dem Entwürfe von Kommentaren nicht verfügbar waren, wenn ein Benutzer einen Kommentar erstellte, ohne ihn zu posten, und den Kommentarbereich schloss, dann ein neues Fenster öffnete, über mehrere Folien navigierte, das Fenster schloss und schließlich den Kommentarbereich in der ursprünglichen Präsentation wieder öffnete.</span><span class="sxs-lookup"><span data-stu-id="b2182-226">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="b2182-227">Es wurde ein Problem behoben, bei dem beim Bewegen des Mauszeigers über das Sternchen-Symbol (\*) der Benutzername und das Datum der letzten Person, die das Dokument aktualisiert hat, nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-227">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="b2182-228">Project</span><span class="sxs-lookup"><span data-stu-id="b2182-228">Project</span></span>

- <span data-ttu-id="b2182-229">Wenn Vorgänger/Nachfolger-Daten in einer Formular-Maske bearbeitet werden, wird ein zusätzliches ProjectBeforeTaskChange-Ereignis ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="b2182-229">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="b2182-230">Es wurde ein Problem behoben, bei dem Project abstürzen konnte, wenn das Feld „Boardstatus“ in einem Projekt geändert wurde, das mit einer SharePoint-Aufgabenliste verbunden ist.</span><span class="sxs-lookup"><span data-stu-id="b2182-230">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="b2182-231">Ein Problem wurde behoben, bei dem Project beim Speichern von Projekten, die mit älteren Project-Versionen erstellt wurden, möglicherweise abstürzt.</span><span class="sxs-lookup"><span data-stu-id="b2182-231">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="b2182-232">Es wurde ein Problem behoben, bei dem, wenn Project mit Project Web App verbunden ist und das Dezimaltrennzeichen ein Komma ist, die TaskDependencies-Add-Methode fehlschlägt, wenn Verzögerung hinzugefügt wird.</span><span class="sxs-lookup"><span data-stu-id="b2182-232">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="b2182-233">Word</span><span class="sxs-lookup"><span data-stu-id="b2182-233">Word</span></span>

- <span data-ttu-id="b2182-234">Es wurde ein Problem behoben, das dazu führte, dass das Einfügen von Kommentaren in ein Dokument im Kollaborationsmodus nicht immer funktionierte.</span><span class="sxs-lookup"><span data-stu-id="b2182-234">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="b2182-235">Diese Änderung behebt ein Problem, bei dem die Personenkarte kurzzeitig eingeblendet wurde, wenn auf die Erwähnung geklickt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-235">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="b2182-236">Beim Aktivieren der Option "Lesezeichen anzeigen" wurden keine Lesezeichen angezeigt.</span><span class="sxs-lookup"><span data-stu-id="b2182-236">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="b2182-237">Dieser Fehler wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b2182-237">This has been fixed.</span></span>

- <span data-ttu-id="b2182-238">Es wurde das Problem behoben, dass beim Schließen eines Dokuments mit Kommentarentwürfen der Benutzer aufgefordert wurde, ob er das Dokument schließen möchte, ohne die Kommentarentwürfe zu speichern.</span><span class="sxs-lookup"><span data-stu-id="b2182-238">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="b2182-239">Das Abbrechen der Eingabeaufforderung schloss das Dokument, anstatt es geöffnet zu lassen.</span><span class="sxs-lookup"><span data-stu-id="b2182-239">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="b2182-240">Es wurde ein Problem beim Kopieren und Einfügen von Überschriften behoben.</span><span class="sxs-lookup"><span data-stu-id="b2182-240">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="b2182-241">Es wurde ein Problem behoben, bei dem das Übersetzen eines geposteten Kommentars zu dem Fehler "Einfügen von übersetzten Text Fehlern" führen würde.</span><span class="sxs-lookup"><span data-stu-id="b2182-241">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="b2182-242">Durch diese Änderung wird ein Problem behoben, bei dem Text mit Hyperlinks möglicherweise nicht angezeigt wird, wenn die Option "Feldfunktionen anstelle ihrer Werte anzeigen" aktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-242">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="b2182-243">In der Webansicht und im Plastischen Reader wurde durch das Anklicken eines Hinweises nach oben gescrollt, obwohl er bereits angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-243">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="b2182-244">Dieser Fehler wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b2182-244">This has been fixed.</span></span>

- <span data-ttu-id="b2182-245">Wir haben ein Problem behoben, dass infolge des Speicherns einer Datei, die ein Makro enthält, unter einem neuen Namen sie mit der Erweiterung DOCX und dem Dateinamen WRO0004.docx gespeichert wurde, und zwar unabhängig davon, was der Benutzer eingab, wodurch das Dokument unbrauchbar wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-245">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b2182-246">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b2182-246">Office Suite</span></span>

- <span data-ttu-id="b2182-247">Wenn ein Benutzer eine Richtlinie erhält, in der er nur in Teams verschoben wird, kann er weiterhin das Skype for Business Outlook-Add-in verwenden, um Besprechungen zu planen.</span><span class="sxs-lookup"><span data-stu-id="b2182-247">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="b2182-248">Nach diesem Update können Sie Skype for Business Besprechungen nicht mehr planen, nachdem der Client die Richtlinie gelesen hat, die besagt, dass der Benutzer nur Teams ist, und nur den Modus für die Besprechungsteilnahme eingibt.</span><span class="sxs-lookup"><span data-stu-id="b2182-248">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="b2182-249">Außerdem wird das Skype for Business Outlook-Add-in beim Starten nicht aktiviert, wenn der Skype for Business-Client nur im Modus "besprechungsbeitritt" angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="b2182-249">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="b2182-250">Das Update behebt ein Problem in Microsoft Office, bei dem Visual Basic for Applications-Projekte mit Referenzen, die bei der Suche nach in der PATH-Umgebungsvariable angegebenen Speicherorten gefunden werden sollen, zur Laufzeit möglicherweise nicht richtig gefunden werden, was zu VBA-Laufzeitfehlern führt.</span><span class="sxs-lookup"><span data-stu-id="b2182-250">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="b2182-251">Dieses Update behebt ein Problem in Visual Basic for Applications in Microsoft Office, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung beim Laden als fehlerhaft angesehen werden.</span><span class="sxs-lookup"><span data-stu-id="b2182-251">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-may-11"></a><span data-ttu-id="b2182-253">Version 2004: 11. Mai</span><span class="sxs-lookup"><span data-stu-id="b2182-253">Version 2004: May 11</span></span>
<span data-ttu-id="b2182-254">*Version 2004 (Build 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="b2182-254">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b2182-256">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b2182-256">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b2182-257">Excel</span><span class="sxs-lookup"><span data-stu-id="b2182-257">Excel</span></span>

- <span data-ttu-id="b2182-258">**Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen.</span><span class="sxs-lookup"><span data-stu-id="b2182-258">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="b2182-259">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-259">Outlook</span></span>

- <span data-ttu-id="b2182-260">**Verbesserte Links in E-Mails:** Wenn Sie einen Link zu einer Datei einfügen, ersetzt der Dateiname die URL.</span><span class="sxs-lookup"><span data-stu-id="b2182-260">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="b2182-261">Sie können die Berechtigungen so ändern, dass alle Empfänger Zugriff haben.</span><span class="sxs-lookup"><span data-stu-id="b2182-261">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="b2182-262">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b2182-262">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="b2182-263">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span><span class="sxs-lookup"><span data-stu-id="b2182-263">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="b2182-264">**Erzählen Sie mit animierten GIFs über sich:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden künftig noch pfiffiger aussehen.</span><span class="sxs-lookup"><span data-stu-id="b2182-264">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b2182-265">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b2182-265">PowerPoint</span></span>

- <span data-ttu-id="b2182-266">**Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen.</span><span class="sxs-lookup"><span data-stu-id="b2182-266">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="b2182-267">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b2182-267">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="b2182-268">Word</span><span class="sxs-lookup"><span data-stu-id="b2182-268">Word</span></span>

- <span data-ttu-id="b2182-269">**Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen.</span><span class="sxs-lookup"><span data-stu-id="b2182-269">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b2182-272">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-272">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b2182-273">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-273">Outlook</span></span>

- <span data-ttu-id="b2182-274">Es wurde ein Problem behoben, das bei Benutzern zu Abstürzen geführt hat, wenn diese Toast-Nachrichten angesehen haben.</span><span class="sxs-lookup"><span data-stu-id="b2182-274">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-may-04"></a><span data-ttu-id="b2182-276">Version 2004: 04. Mai</span><span class="sxs-lookup"><span data-stu-id="b2182-276">Version 2004: May 04</span></span>
<span data-ttu-id="b2182-277">*Version 2004 (Build 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="b2182-277">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b2182-279">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b2182-279">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b2182-280">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-280">Outlook</span></span>

- <span data-ttu-id="b2182-281">**Bessere Ergebnisse – im Handumdrehen:** wir haben die Suche aktualisiert, damit Sie intelligenter, schneller und zuverlässiger als je zuvor ist.</span><span class="sxs-lookup"><span data-stu-id="b2182-281">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="b2182-282">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b2182-282">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="b2182-283">**Benachrichtigung Über Vorfall für IT-Administratoren:** Globale Administratoren von Microsoft 365-Mandanten und Administratoren von Office-Apps werden über Outlook und O365 Exchange-Vorfällen benachrichtigt, die sich auf Ihre Benutzer auswirken – mit einer neuen Benachrichtigung im rechten Seitenbereich in Outlook für Windows.</span><span class="sxs-lookup"><span data-stu-id="b2182-283">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b2182-286">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-286">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="b2182-287">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b2182-287">Office Suite</span></span>

- <span data-ttu-id="b2182-288">Dieses Update behebt ein Problem in Visual Basic for Applications in Microsoft Office, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung beim Laden als fehlerhaft angesehen werden.</span><span class="sxs-lookup"><span data-stu-id="b2182-288">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-april-29"></a><span data-ttu-id="b2182-290">Version 2004: 29. April</span><span class="sxs-lookup"><span data-stu-id="b2182-290">Version 2004: April 29</span></span>
<span data-ttu-id="b2182-291">*Version 2004 (Build 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="b2182-291">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b2182-293">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b2182-293">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b2182-294">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-294">Outlook</span></span>

- <span data-ttu-id="b2182-295">**Schützen von Daten in einer Gruppe:** Die beim Erstellen einer Gruppe ausgewählte Vertraulichkeitsbezeichnung wird auf Gruppen-E-Mails, Dokumente und Teamwebsites angewendet.</span><span class="sxs-lookup"><span data-stu-id="b2182-295">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b2182-298">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-298">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b2182-299">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-299">Outlook</span></span>

- <span data-ttu-id="b2182-300">Behebt ein Problem, das dazu geführt hat, dass Outlook bei einigen Windows-Versionen abstürzt.</span><span class="sxs-lookup"><span data-stu-id="b2182-300">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-april-25"></a><span data-ttu-id="b2182-302">Version 2004: 25. April</span><span class="sxs-lookup"><span data-stu-id="b2182-302">Version 2004: April 25</span></span>
<span data-ttu-id="b2182-303">*Version 2004 (Build 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="b2182-303">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b2182-305">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-305">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b2182-306">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-306">Outlook</span></span>

- <span data-ttu-id="b2182-307">Es wurde ein Problem behoben, durch das Outlook nach einem Windows-Update beim Öffnen von lokal gespeicherten MSG- oder OFT-Dateien abstürzte.</span><span class="sxs-lookup"><span data-stu-id="b2182-307">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="b2182-308">Project</span><span class="sxs-lookup"><span data-stu-id="b2182-308">Project</span></span>

- <span data-ttu-id="b2182-309">Folgendes Problem wurde behoben: Wenn Sie Project in Verbindung mit Project Web App verwenden, das Kommas als Dezimaltrennzeichen festgelegt ist, und Sie versuchten, einer Abhängigkeit eine Verzögerung hinzuzufügen, schlägt die Methode "TaskDependencies Add" fehl.</span><span class="sxs-lookup"><span data-stu-id="b2182-309">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b2182-310">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b2182-310">Office Suite</span></span>

- <span data-ttu-id="b2182-311">Mit diesem Fix wird ein Fehler behoben, der verhindert, dass Sie gleichzeitig den Zugriff einschränken und Dateien mit einem Kennwort schützen können.</span><span class="sxs-lookup"><span data-stu-id="b2182-311">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2004-april-21"></a><span data-ttu-id="b2182-313">Version 2004: 21. April</span><span class="sxs-lookup"><span data-stu-id="b2182-313">Version 2004: April 21</span></span>
<span data-ttu-id="b2182-314">*Version 2004 (Build 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="b2182-314">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b2182-316">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-316">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b2182-317">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-317">Outlook</span></span>

- <span data-ttu-id="b2182-318">Behebt ein Problem, bei dem die Breite des Ordnerbereichs unerwartet geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-318">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="b2182-319">Behebt ein Problem, bei dem sich das Programm beim Verlassen von Outlook aufhängte.</span><span class="sxs-lookup"><span data-stu-id="b2182-319">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-april-15"></a><span data-ttu-id="b2182-321">Version 2004: 15. April</span><span class="sxs-lookup"><span data-stu-id="b2182-321">Version 2004: April 15</span></span>
<span data-ttu-id="b2182-322">*Version 2004 (Build 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="b2182-322">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b2182-324">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b2182-324">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b2182-325">Excel</span><span class="sxs-lookup"><span data-stu-id="b2182-325">Excel</span></span>

- <span data-ttu-id="b2182-326">**Die Unterstützung für Facebook Connector endet:** Ab April 2020 werden von Excel keine externen Datenverbindungen mehr unterstützt, für die der Facebook-Connector eingesetzt wird.</span><span class="sxs-lookup"><span data-stu-id="b2182-326">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="b2182-327">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-327">Outlook</span></span>

- <span data-ttu-id="b2182-328">**Neue Option zum Deaktivieren von Vorschlägen für @Erwähnungen beim Verfassen von E-Mails in Outlook:** Finden Sie die @Erwähnung-Auswahl eher lästig als sinnvoll?</span><span class="sxs-lookup"><span data-stu-id="b2182-328">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="b2182-329">Wenn Sie das möchten, können Sie diese nun deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="b2182-329">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b2182-330">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b2182-330">PowerPoint</span></span>

- <span data-ttu-id="b2182-331">**Synchronisieren von Änderungen während der Präsentation:** Änderungen können jetzt synchronisiert werden, wenn sie vorgenommen werden, selbst wenn sich die Präsentation im Bildschirmpräsentationsmodus befindet.</span><span class="sxs-lookup"><span data-stu-id="b2182-331">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="b2182-332">Word</span><span class="sxs-lookup"><span data-stu-id="b2182-332">Word</span></span>

- <span data-ttu-id="b2182-333">**Fügen Sie einen privaten Kopie Anmerkungen hinzu:** Erstellen Sie handschriftliche Notizen nur für Sie, indem Sie eine private Kopie eines freigegebenen Dokuments erstellen.</span><span class="sxs-lookup"><span data-stu-id="b2182-333">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="b2182-334">Wechseln Sie dazu einfach zu "Anzeige" > "Private Kopie erstellen".</span><span class="sxs-lookup"><span data-stu-id="b2182-334">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b2182-337">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-337">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b2182-338">Access</span><span class="sxs-lookup"><span data-stu-id="b2182-338">Access</span></span>

- <span data-ttu-id="b2182-339">Probleme bei der Anpassung der Größe und der Aktualisierung von Tabellen im Aufgabenbereich wurden behoben.</span><span class="sxs-lookup"><span data-stu-id="b2182-339">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="b2182-340">Ein Problem wurde behoben, bei dem internationale Versionen von Access in der Benutzeroberfläche englische Zeichenfolgen anzeigten.</span><span class="sxs-lookup"><span data-stu-id="b2182-340">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="b2182-341">Excel</span><span class="sxs-lookup"><span data-stu-id="b2182-341">Excel</span></span>

- <span data-ttu-id="b2182-342">Es wurde ein Problem behoben, bei dem das Auswählen eines Zellbereichs auf einem Arbeitsblatt zur Auswahl nur einer einzelnen Zelle geführt hat.</span><span class="sxs-lookup"><span data-stu-id="b2182-342">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="b2182-343">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-343">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="b2182-344">Ein Problem wurde behoben, bei dem Excel in manchen Fällen abstürzte, nachdem ein Blatt mit einer PivotTable kopiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-344">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="b2182-345">Application.Evaluate (VBA) funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.</span><span class="sxs-lookup"><span data-stu-id="b2182-345">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="b2182-346">Es wurde ein Leistungsproblem behoben, das Benutzer beim programmgesteuerten Bearbeiten eines großen Zellbereichs festgestellt haben.</span><span class="sxs-lookup"><span data-stu-id="b2182-346">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="b2182-347">Ein Leistungsproblem beim Öffnen von CSV-Dateien in japanischen Umgebungen wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b2182-347">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="b2182-348">Es wurde ein Problem behoben, bei dem das Einfügen einer benutzerdefinierten Diagrammvorlage als Standard dazu führte, dass sie als Säulendiagramm gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-348">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="b2182-349">Ein Problem wurde behoben, bei dem Datenbeschriftungen in Diagrammen leer angezeigt wurden, wenn die zugrundeliegenden Datenzellen keine Beschriftung aufwiesen.</span><span class="sxs-lookup"><span data-stu-id="b2182-349">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="b2182-350">Es wurde ein Problem behoben, das dazu führen konnte, dass Excel nicht mehr reagierte, wenn die Größe eines Diagramms mit einigen x-Achsen-Bereichen reduziert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-350">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="b2182-351">Es wurde ein Problem behoben, bei dem eine Excel-Tabelle mit aktiviertem Z1S1-Zellbezug die freigegeben bzw. gemeinsam erstellt wurde, der aktive Zellbezug im Z1S1-Modus nicht angezeigt wurde, wenn man auf das Symbol für die Anwesenheitsanzeige zeigte.</span><span class="sxs-lookup"><span data-stu-id="b2182-351">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="b2182-352">Diese Änderung betrifft Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen.</span><span class="sxs-lookup"><span data-stu-id="b2182-352">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="b2182-353">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-353">Outlook</span></span>

- <span data-ttu-id="b2182-354">Diese Änderung ist gegen Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen gerichtet.</span><span class="sxs-lookup"><span data-stu-id="b2182-354">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="b2182-355">Diese Änderung behebt ein Problem, bei dem die neuesten Änderungen an E-Mail-Entwürfen nicht aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-355">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="b2182-356">Ein Problem wurde behoben, bei dem Sie mit der rechten Maustaste auf eine Datei klicken und "Senden an" nicht funktionieren würde.</span><span class="sxs-lookup"><span data-stu-id="b2182-356">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="b2182-357">Ein Problem wurde behoben, durch das Stellvertretungen auf unterschiedlichen Computern unterschiedliche Ordnerhierarchien für freigegebene Postfächer angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-357">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="b2182-358">Ein Problem wurde behoben, durch das gelegentlich Kategorien in E-Mail-Nachrichten nicht mehr aufschienen.</span><span class="sxs-lookup"><span data-stu-id="b2182-358">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="b2182-359">Es wurde ein Problem behoben, durch das einige Erinnerungen nicht ausgelöst wurden, wenn die Zeitzone auf einem Computer geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-359">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="b2182-360">Es wurde ein Problem behoben, das einen Absturz verursachte, wenn Benutzer versuchten, die Eigenschaften eines Organisationsformulars anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="b2182-360">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="b2182-361">Es wurde ein Problem behoben, bei dem, wenn ein Benutzer einen angepassten Suchpfad für das Adressbuch hatte, der Namensauflösungsbereich von Outlook auf den angepassten Pfad beschränkt wurde, anstatt die Globale Adressliste (GAL) einzubeziehen.</span><span class="sxs-lookup"><span data-stu-id="b2182-361">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="b2182-362">Es wurde ein Problem behoben, das bewirkt hat, dass die Schaltfläche "In der Cloud speichern" in den Anlagentools fehlte.</span><span class="sxs-lookup"><span data-stu-id="b2182-362">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="b2182-363">Es wurde ein Problem behoben, das bewirkt hat, dass Benutzer beim Antworten auf eine verwaltete Nachricht mit digitaler Berechtigung aus einem Inspektor-Fenster keine Signatur hinzufügen konnten, wenn er nicht über die Berechtigung "Besitzer" für die Nachricht verfügte, auf die geantwortet wird.</span><span class="sxs-lookup"><span data-stu-id="b2182-363">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="b2182-364">Es wurde ein Problem behoben, durch das Benutzer keine weiteren Anlagen von einem Webspeicherort zu einer zuvor erstellten Besprechung hinzufügen konnten.</span><span class="sxs-lookup"><span data-stu-id="b2182-364">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="b2182-365">Es wurde ein Problem behoben, das dazu geführt hat, dass das „Datum der letzten Änderung“ in einer Datei beim Hinzufügen einer Anlage zu einer E-Mail oder beim Speichern einer Anlage aus einer E-Mail durch Ziehen und Ablegen (im Gegensatz zum Hinzufügen oder Speichern über ein Menü) aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-365">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="b2182-366">Es wurde ein Problem behoben, bei dem durch das Drücken der EINGABETASTE im erweiterten Suchbereich keine Suche gestartet wurde. Stattdessen mussten Benutzer auf die Schaltfläche "Suchen" klicken.</span><span class="sxs-lookup"><span data-stu-id="b2182-366">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="b2182-367">Es wurde ein Problem behoben, bei dem innerhalb eines Satzes von zurückgegebenen Suchergebnissen beim Sortieren der Ergebnisse nach Kategorien die Kategoriefarben nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-367">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="b2182-368">Ein Problem wurde behoben, bei dem die Suche keine Informationen zu Benutzern anzeigte, wenn die Option "Benutzerfotos anzeigen, wenn verfügbar" deaktiviert war.</span><span class="sxs-lookup"><span data-stu-id="b2182-368">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b2182-369">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b2182-369">PowerPoint</span></span>

- <span data-ttu-id="b2182-370">Diese Änderung behebt einen Fehler, der dazu führen kann, dass PowerPoint-Dateien mit Emojis beim Speichern fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="b2182-370">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="b2182-371">Diese Änderung behebt ein Problem, bei dem beim Rendern eines Diagramms einer älteren Excel-Version, das als OLE-Objekt in PowerPoint oder Word eingebettet ist, u. U. nicht immer der Diagrammtitel angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-371">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="b2182-372">Es wurde ein Problem behoben, bei dem beim Kopieren von Text aus Excel in PowerPoint u. U. dessen Formatierung geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-372">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="b2182-373">Diese Änderung behebt ein Problem, bei dem das Suchen von Sonderzeichen mithilfe der Option "Nur ganze Wörter suchen" nicht immer erwartungsgemäß funktioniert hat.</span><span class="sxs-lookup"><span data-stu-id="b2182-373">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="b2182-374">Project</span><span class="sxs-lookup"><span data-stu-id="b2182-374">Project</span></span>

- <span data-ttu-id="b2182-375">Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-375">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="b2182-376">Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.</span><span class="sxs-lookup"><span data-stu-id="b2182-376">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="b2182-377">Ein Problem wurde behoben, bei dem das VBA-Ereignis (Visual Basic Applications) "ProjectBeforeTaskChange" nicht ausgelöst wurde, wenn ein Benutzer auf die Schaltfläche "Deaktivieren" geklickt hat, die sich auf dem Menüband "Vorgänge" innerhalb der Planungsgruppierung befindet.</span><span class="sxs-lookup"><span data-stu-id="b2182-377">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="b2182-378">Wenn Sie Vorgänger- oder Nachfolgerdetails in einer Ansicht vom Typ „Formular“ festlegen, wurden die Änderungen nicht immer durch das Ereignis „ProjectBeforeTaskChange Visual Basic Applications“ (VBA) erfasst.</span><span class="sxs-lookup"><span data-stu-id="b2182-378">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="b2182-379">Wenn Sie beispielsweise eine Abhängigkeit gelöscht und im Formular auf „OK“ geklickt haben, wurde das Ereignis nicht ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="b2182-379">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="b2182-380">Dieses Verhalten wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b2182-380">This behavior has been fixed.</span></span>

- <span data-ttu-id="b2182-381">Es wurde ein Problem behoben, bei dem die neuesten Werte für die tatsächlichen Kosten der geleisteten Arbeit (ACWP) nicht angezeigt wurden, nachdem eine Änderung, z. B. eine Datumsänderung, vorgenommen wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-381">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="b2182-382">Es wurde ein Problem behoben, bei dem das Öffnen eines Projekts über das Menü "Zuletzt verwendet" (MRU) die Projektdatei mit Lese- bzw. Schreibzugriff öffnete.</span><span class="sxs-lookup"><span data-stu-id="b2182-382">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="b2182-383">Diese Änderung behebt das Problem, dass Sie eine manuelle Aufgabe mit einem Startdatum und einer Uhrzeit (aber ohne Dauer) erstellt haben, diese aber mit einer falschen Uhrzeit auf der Zeitachse angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-383">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="b2182-384">Es wurde ein Problem behoben, bei dem das Drucken einer Zeitleiste mithilfe eines Hijri-Kalenders dazu führte, dass ein Monat in der Druckansicht übersprungen oder dupliziert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-384">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="b2182-385">Diese Änderung richtet sich gegen ein Problem, bei dem die Arbeit im Team Planner mit GDI-Objekten zu einer Überzuweisung von GDI-Objekten und zu geringem Speicherplatz führen konnte.</span><span class="sxs-lookup"><span data-stu-id="b2182-385">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="b2182-386">Ein Problem wurde behoben, durch das, wenn "CustomFieldValueListGetItem" ausgeführt wurde und keine Nachschlagetabelle für das benutzerdefinierte Feld vorhanden war, eine leere Nachschlagetabelle erstellt wurde, auch wenn dies nicht so sein sollte.</span><span class="sxs-lookup"><span data-stu-id="b2182-386">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="b2182-387">Wenn Vorgänger/Nachfolger-Daten in einer Maske bearbeitet werden, wird ein zusätzliches ProjectBeforeTaskChangeevent ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="b2182-387">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="b2182-388">Es wurde ein Problem behoben, bei dem der Benutzer keine zeitgesteuerte Baseline-Arbeit eingeben konnte, wenn die Einstellung zum Schutz der aktuellen Arbeit aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="b2182-388">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="b2182-389">Word</span><span class="sxs-lookup"><span data-stu-id="b2182-389">Word</span></span>

- <span data-ttu-id="b2182-390">Diese Änderung behebt ein Problem, bei dem wenn der Mauszeiger über einen Hinweis gehalten wurde, dessen Karte nicht hervorgehoben wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-390">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="b2182-391">Diese Änderung behebt ein Problem, bei dem wenn mehrere Seiten aus dem Menü "Ansicht" ausgewählt wurden, der Kommentarbereich u. U. als leer angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-391">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="b2182-392">Es wurde ein Problem behoben, durch das die Funktion zum Posten von Kommentaren deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-392">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="b2182-393">Diese Änderung behebt ein Problem, das dazu führte, dass der Text in gruppierten Formen beim Verwenden des Lasso-Auswahltools vorübergehend ausgeblendet wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-393">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="b2182-394">Diese Änderung betrifft Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen.</span><span class="sxs-lookup"><span data-stu-id="b2182-394">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="b2182-395">Diese Änderung behebt ein Problem, bei dem beim Rendern eines Diagramms einer älteren Excel-Version, das als OLE-Objekt in PowerPoint oder Word eingebettet ist, u. U. nicht immer der Diagrammtitel angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-395">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="b2182-396">Diese Änderung betrifft ein Problem, bei dem der Account Manager keine Nachrichten versendete, was zu einer Unterbrechung bei Anwendungen von Drittanbietern führte.</span><span class="sxs-lookup"><span data-stu-id="b2182-396">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="b2182-397">Diese Änderung behebt ein Problem in der Zwei-Seiten-Ansicht. Beim Erstellen eines Kommentars wurde der Kommentaranker nicht immer in der Anzeige angezeigt.</span><span class="sxs-lookup"><span data-stu-id="b2182-397">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="b2182-398">Ein Problem wurde behoben, bei dem das Eingeben oder Bearbeiten eines Kommentars und Verwenden von STRG+A dazu führte, dass statt nur innerhalb der Kommentarkarte Text im Zeichenbereich markiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-398">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="b2182-399">Ein Problem wurde behoben, bei dem ein Absatz, dessen Formatvorlage ein Vorgänger einer mit einer Liste verknüpften Formatvorlage war, möglicherweise verloren ging.</span><span class="sxs-lookup"><span data-stu-id="b2182-399">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="b2182-400">Diese Änderung behebt ein Problem, bei dem das Inhaltsverzeichnis mit Überschriftenformaten aktualisiert wurde, die im Dokument nicht vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="b2182-400">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="b2182-401">Es wurde ein Problem behoben, bei dem die Ausrichtung von Wörtern in einem Dokument durcheinandergebracht wurde, wenn Benutzer nach dem Drucken mit Schnelldruck versuchten, den Text zu bearbeiten.</span><span class="sxs-lookup"><span data-stu-id="b2182-401">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="b2182-402">Es wurde ein Problem beim Zusammenführen von zwei Dokumenten in ein Dokument behoben.</span><span class="sxs-lookup"><span data-stu-id="b2182-402">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="b2182-403">Es wurde ein Problem behoben, bei dem in Word-Dokumenten gespeicherte digitale Signaturen beim Versand der Dokumente per E-Mail entfernt wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-403">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="b2182-404">Es wurde ein Problem behoben, bei dem das Markieren von Überarbeitungen, die Formeln enthalten, beim Speichern der Datei zu einem Fehler führen konnte.</span><span class="sxs-lookup"><span data-stu-id="b2182-404">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-april-14"></a><span data-ttu-id="b2182-406">Version 2003: 14. April</span><span class="sxs-lookup"><span data-stu-id="b2182-406">Version 2003: April 14</span></span>
<span data-ttu-id="b2182-407">*Version 2003 (Build 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="b2182-407">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="b2182-408">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="b2182-408">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS CONTENT START NICHT ENTFERNEN)

- <span data-ttu-id="b2182-410">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b2182-410">Various bugs and performance fixes.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-april-09"></a><span data-ttu-id="b2182-412">Version 2003: 09. April</span><span class="sxs-lookup"><span data-stu-id="b2182-412">Version 2003: April 09</span></span>
<span data-ttu-id="b2182-413">*Version 2003 (Build 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="b2182-413">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b2182-415">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b2182-415">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b2182-416">Excel</span><span class="sxs-lookup"><span data-stu-id="b2182-416">Excel</span></span>

- <span data-ttu-id="b2182-417">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="b2182-417">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="b2182-418">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="b2182-418">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="b2182-419">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-419">Outlook</span></span>

- <span data-ttu-id="b2182-420">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="b2182-420">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="b2182-421">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="b2182-421">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b2182-422">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b2182-422">PowerPoint</span></span>

- <span data-ttu-id="b2182-423">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="b2182-423">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="b2182-424">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="b2182-424">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="b2182-425">Word</span><span class="sxs-lookup"><span data-stu-id="b2182-425">Word</span></span>

- <span data-ttu-id="b2182-426">**M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger!</span><span class="sxs-lookup"><span data-stu-id="b2182-426">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="b2182-427">Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="b2182-427">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)




[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-april-03"></a><span data-ttu-id="b2182-431">Version 2003: 3. April</span><span class="sxs-lookup"><span data-stu-id="b2182-431">Version 2003: April 03</span></span>
<span data-ttu-id="b2182-432">*Version 2003 (Build 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="b2182-432">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b2182-434">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-434">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b2182-435">Excel</span><span class="sxs-lookup"><span data-stu-id="b2182-435">Excel</span></span>

- <span data-ttu-id="b2182-436">Verwendung der VBA-Anwendung. „Evaluate“ funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.</span><span class="sxs-lookup"><span data-stu-id="b2182-436">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="b2182-437">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-437">Outlook</span></span>

- <span data-ttu-id="b2182-438">Es wurde ein Problem behoben, das dazu führte, dass Benutzer gelegentlich einen Absturz feststellten, wenn Sie den X-Knopf auf ihrer Maus verwendeten.</span><span class="sxs-lookup"><span data-stu-id="b2182-438">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="b2182-439">Project</span><span class="sxs-lookup"><span data-stu-id="b2182-439">Project</span></span>

- <span data-ttu-id="b2182-440">Wenn Vorgänger/Nachfolger-Daten in einer Maske bearbeitet werden, wird ein zusätzliches ProjectBeforeTaskChangeevent ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="b2182-440">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="b2182-441">Word</span><span class="sxs-lookup"><span data-stu-id="b2182-441">Word</span></span>

- <span data-ttu-id="b2182-442">Es wurde ein Problem behoben, das dazu führte, dass Benutzer gelegentlich einen Absturz feststellten, wenn Sie den X-Knopf auf ihrer Maus verwendeten.</span><span class="sxs-lookup"><span data-stu-id="b2182-442">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-31"></a><span data-ttu-id="b2182-444">Version 2003: 31. März</span><span class="sxs-lookup"><span data-stu-id="b2182-444">Version 2003: March 31</span></span>
<span data-ttu-id="b2182-445">*Version 2003 (Build 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="b2182-445">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b2182-447">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b2182-447">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="b2182-448">Access</span><span class="sxs-lookup"><span data-stu-id="b2182-448">Access</span></span>

- <span data-ttu-id="b2182-449">**Aufgabenbereich "Tabellen hinzufügen":** Der neue Aufgabenbereich "Tabellen hinzufügen" von Access ist endlich da!</span><span class="sxs-lookup"><span data-stu-id="b2182-449">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="b2182-450">Mit dieser Funktion können Sie einfach auswählen/mehrfach auswählen, welche Tabellen sie in einem Abfragefenster hinzufügen/entfernen möchten, ohne zum Dialogfeld "Tabellen anzeigen" für Abfragen und für die Beziehungsansicht zu navigieren.</span><span class="sxs-lookup"><span data-stu-id="b2182-450">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="b2182-451">Dazu gehört auch eine neue Registerkarte "Verknüpfungen", um verknüpfte Tabellen anzuzeigen, ein Suchfeld, um die aktuelle Liste zu filtern, "Drag & Drop"-Verhalten und mehr!</span><span class="sxs-lookup"><span data-stu-id="b2182-451">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b2182-454">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-454">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="b2182-455">Project</span><span class="sxs-lookup"><span data-stu-id="b2182-455">Project</span></span>

- <div><span data-ttu-id="b2182-456"><span style="display:inline !important;">Es wurde ein Problem behoben, bei dem der Benutzer keine zeitgesteuerte Baseline-Arbeit eingeben konnte, wenn die Einstellung zum Schutz der tatsächlichen Arbeit aktiviert ist.</span></span><span class="sxs-lookup"><span data-stu-id="b2182-456"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-25"></a><span data-ttu-id="b2182-458">Version 2003: 25. März</span><span class="sxs-lookup"><span data-stu-id="b2182-458">Version 2003: March 25</span></span>
<span data-ttu-id="b2182-459">*Version 2003 (Build 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="b2182-459">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="b2182-460">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b2182-460">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="b2182-461">Version 2003: 23. März</span><span class="sxs-lookup"><span data-stu-id="b2182-461">Version 2003: March 23</span></span>
<span data-ttu-id="b2182-462">*Version 2003 (Build 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="b2182-462">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="b2182-463">Korrekturen verschiedene Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b2182-463">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="b2182-464">Version 2003: 21. März</span><span class="sxs-lookup"><span data-stu-id="b2182-464">Version 2003: March 21</span></span>
<span data-ttu-id="b2182-465">*Version 2003 (Build 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="b2182-465">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b2182-467">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b2182-467">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b2182-468">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-468">Outlook</span></span>

- <span data-ttu-id="b2182-469">**An Besprechungen teilnehmen, ohne den Posteingang zu verlassen:** Sie brauchen nicht zu Ihrem Kalender zu wechseln, um an Onlinebesprechungen teilzunehmen.</span><span class="sxs-lookup"><span data-stu-id="b2182-469">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="b2182-470">Wenn der Kalender im Aufgabenbereich angeheftet ist, können Sie mit nur einem Klick an einer Besprechung teilnehmen.</span><span class="sxs-lookup"><span data-stu-id="b2182-470">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="b2182-471">**Visuelle Aktualisierung des Kalenders:** Letztes Jahr haben wir die E-Mail-Erfahrung visuell aufgefrischt, und dieses Jahr ist der Kalender mit einem Facelifting an der Reihe!</span><span class="sxs-lookup"><span data-stu-id="b2182-471">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="b2182-472">Die Aktualisierungen sind frisch, aber vertraut, so dass Sie als erfahrener Outlook-Benutzer sofort einsteigen und produktiver sein können.</span><span class="sxs-lookup"><span data-stu-id="b2182-472">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b2182-473">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b2182-473">PowerPoint</span></span>

- <span data-ttu-id="b2182-474">**Aktualisieren von Folien während der Bildschirmpräsentation:** Aktualisieren Sie Folien, die von anderen Autoren während Ihrer Präsentation geändert wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-474">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-16"></a><span data-ttu-id="b2182-476">Version 2003: 16. März</span><span class="sxs-lookup"><span data-stu-id="b2182-476">Version 2003: March 16</span></span>
<span data-ttu-id="b2182-477">*Version 2003 (Build 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="b2182-477">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b2182-479">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b2182-479">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b2182-480">Excel</span><span class="sxs-lookup"><span data-stu-id="b2182-480">Excel</span></span>

- <span data-ttu-id="b2182-481">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="b2182-481">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="b2182-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-482">Outlook</span></span>

- <span data-ttu-id="b2182-483">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="b2182-483">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b2182-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b2182-484">PowerPoint</span></span>

- <span data-ttu-id="b2182-485">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="b2182-485">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="b2182-486">Word</span><span class="sxs-lookup"><span data-stu-id="b2182-486">Word</span></span>

- <span data-ttu-id="b2182-487">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="b2182-487">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b2182-488">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b2182-488">Office Suite</span></span>

- <span data-ttu-id="b2182-489">**Bereiche im Registerkartenformat:** Jetzt können Sie über die Registerkarten-Benutzeroberfläche auf der rechten Seite der App zwischen mehreren Bereichen wechseln.</span><span class="sxs-lookup"><span data-stu-id="b2182-489">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="b2182-490">Die Benutzeroberfläche wird nur angezeigt, wenn Sie mehr als 2 Fenster geöffnet haben.</span><span class="sxs-lookup"><span data-stu-id="b2182-490">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b2182-493">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-493">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b2182-494">Excel</span><span class="sxs-lookup"><span data-stu-id="b2182-494">Excel</span></span>

- <span data-ttu-id="b2182-495">Es wurde ein Problem behoben, bei dem externe Links beim Füllen nicht aktualisiert werden, wenn das Quellbuch geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="b2182-495">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="b2182-496">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-496">Outlook</span></span>

- <span data-ttu-id="b2182-497">Es wurde ein Problem behoben, das dazu führte, dass der Outlook-Prozess nach dem Beenden im Task-Manager fortbestand.</span><span class="sxs-lookup"><span data-stu-id="b2182-497">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-10"></a><span data-ttu-id="b2182-499">Version 2003: 10. März</span><span class="sxs-lookup"><span data-stu-id="b2182-499">Version 2003: March 10</span></span>
<span data-ttu-id="b2182-500">*Version 2003 (Build 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="b2182-500">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="b2182-501">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="b2182-501">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)
### <a name="feature-updates"></a><span data-ttu-id="b2182-503">Funktionsupdates</span><span class="sxs-lookup"><span data-stu-id="b2182-503">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="b2182-504">Excel</span><span class="sxs-lookup"><span data-stu-id="b2182-504">Excel</span></span>
- <span data-ttu-id="b2182-505">**Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern.</span><span class="sxs-lookup"><span data-stu-id="b2182-505">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="b2182-506">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b2182-506">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a><span data-ttu-id="b2182-507">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b2182-507">PowerPoint</span></span>
- <span data-ttu-id="b2182-508">**Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern.</span><span class="sxs-lookup"><span data-stu-id="b2182-508">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="b2182-509">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b2182-509">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a><span data-ttu-id="b2182-510">Word</span><span class="sxs-lookup"><span data-stu-id="b2182-510">Word</span></span>
- <span data-ttu-id="b2182-511">**Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern.</span><span class="sxs-lookup"><span data-stu-id="b2182-511">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="b2182-512">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="b2182-512">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="b2182-513">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-513">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b2182-514">Excel</span><span class="sxs-lookup"><span data-stu-id="b2182-514">Excel</span></span>

- <span data-ttu-id="b2182-515">Ein kosmetisches Problem wurde behoben, bei dem die Schaltfläche "OK" im Dialogfeld "Datei\Optionen" abgeblendet angezeigt, die Funktionalität aber nicht beeinträchtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-515">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="b2182-516">Es wurde ein Problem behoben, das möglicherweise beim Umbenennen von Pivot-Tabellenmaßen aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="b2182-516">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="b2182-517">Ein Problem wurde behoben, bei dem der Text in einem Datenschnitt in der Druckvorschau nicht ordnungsgemäß skaliert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-517">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="b2182-518">Es wurde ein Leistungsproblem behoben, das möglicherweise bei der Verwendung eines VBA-Makros zum Löschen des Inhalts eines Bereichs aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="b2182-518">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="b2182-519">Es wurde ein Problem behoben, das zum Blinken der Benutzeroberfläche führte, wenn Benutzer ein Makro ausführten, das mit dem Menüband interagierte.</span><span class="sxs-lookup"><span data-stu-id="b2182-519">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="b2182-520">Es wurde ein Problem behoben, bei dem CSV-Dateien falsch geladen wurden, wenn das erste Wort in der Datei TABLE lautete.</span><span class="sxs-lookup"><span data-stu-id="b2182-520">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="b2182-521">Es wurde ein Problem behoben, bei dem es zu Abstürzen kommen konnte, wenn Benutzer zwischen zwei Arbeitsmappen mit unterschiedlichen Zoomstufen wechselten.</span><span class="sxs-lookup"><span data-stu-id="b2182-521">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="b2182-522">Ein Problem wurde behoben, bei dem CUBEWERT-Funktionen manchmal ein falsches Ergebnis zurückgaben.</span><span class="sxs-lookup"><span data-stu-id="b2182-522">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="b2182-523">Diese Änderung behebt einen Laufzeitfehler im Objektmodell und verhindert einen möglichen Absturz der App (Excel, Word), wenn Add-Ins nach Hostelementen in Dokumenten/Arbeitsblättern fragen, die Formen mit noSelect-Sperren enthalten.</span><span class="sxs-lookup"><span data-stu-id="b2182-523">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="b2182-524">Behebt ein Problem, durch das Outlook beim Synchronisieren der Einstellungen abstürzte.</span><span class="sxs-lookup"><span data-stu-id="b2182-524">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="b2182-525">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-525">Outlook</span></span>

- <span data-ttu-id="b2182-526">Ein Problem wurde behoben, bei dem das Erstellen einer Regel mit Outlook Web App auf dem Exchange-Server nicht beibehalten werden konnte und zu einem Konflikt geführt hat.</span><span class="sxs-lookup"><span data-stu-id="b2182-526">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="b2182-527">Es wurde ein Problem behoben, durch das Outlook beim Synchronisieren der Einstellungen abstürzte.</span><span class="sxs-lookup"><span data-stu-id="b2182-527">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="b2182-528">Es wurde ein Problem mit Outlook im dunklen Modus behoben, wird möglicherweise die Dropdownliste im Feld "Von:" nicht angezeigt.</span><span class="sxs-lookup"><span data-stu-id="b2182-528">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="b2182-529">Es wurde ein Problem behoben, das dazu führte, dass Outlook in einigen Szenarien unerwartet Protokollausgaben erzeugte, selbst wenn die Protokollierung ausgeschaltet war.</span><span class="sxs-lookup"><span data-stu-id="b2182-529">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="b2182-530">Es wurde ein Problem behoben, das dazu führte, dass Benutzer keine Nachrichten in öffentlichen Ordnern öffnen konnten, wenn Outlook über Nacht laufen gelassen wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-530">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="b2182-531">Es wurde eine Racebedingung behoben, bei der die Schaltflächen "Zulassen" und "Verweigern" auf der Seite "Berechtigungen" während des Authentifizierungsworkflows beim Hinzufügen eines Google Mail-Kontos deaktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="b2182-531">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="b2182-532">Ein Problem wurde behoben, durch das Benutzer den Zugriff auf das Dialogfeld &quot;Frei/Gebucht-Optionen&quot; der Kalenderberechtigungen verloren.</span><span class="sxs-lookup"><span data-stu-id="b2182-532">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="b2182-533">Es wurde ein Problem behoben, das zur Warnung &quot;Leider besteht ein Problem beim Öffnen dieses Elements&quot; führen kann, wenn Sie bestimmte Besprechungsserien-Instanzen öffnen, die aus einer anderen Zeitzone gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-533">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="b2182-534">Es wurde ein Problem behoben, durch das Benutzer eine MSG-Datei möglicherweise nicht mehr öffnen können, nachdem die eine Anlage aus dieser Nachricht durch Ziehen und Ablegen verschoben haben.</span><span class="sxs-lookup"><span data-stu-id="b2182-534">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="b2182-535">Ein Problem wurde behoben, bei dem der Dateiname nach dem Hochladen einer Dateianlage aus Outlook nach OneDrive möglicherweise geändert wird, wenn der Name der Anlage eine Klammer enthält.</span><span class="sxs-lookup"><span data-stu-id="b2182-535">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="b2182-536">Es wurde ein Problem behoben, durch das Benutzer über den Datei-Explorer eine Datei nicht als Anlage zu einer E-Mail-Nachricht hinzufügen konnten, wenn diese Datei in einer anderen Anwendung geöffnet war.</span><span class="sxs-lookup"><span data-stu-id="b2182-536">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="b2182-537">Es wurde ein Problem behoben, durch das Outlook beim Synchronisieren der Einstellungen abstürzte.</span><span class="sxs-lookup"><span data-stu-id="b2182-537">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="b2182-538">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b2182-538">PowerPoint</span></span>

- <span data-ttu-id="b2182-539">Ein Problem wurde behoben, bei dem die empfohlenen Miniaturansichten blinkten, wenn Sie mit der Maus auf die Miniaturansichten gingen.</span><span class="sxs-lookup"><span data-stu-id="b2182-539">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="b2182-540">In einigen Fällen kann dies dazu führen, dass PowerPoint abstürzt.</span><span class="sxs-lookup"><span data-stu-id="b2182-540">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="b2182-541">Ein kosmetisches Problem wurde behoben, bei dem die Schaltfläche "OK" im Dialogfeld "Datei\Optionen" abgeblendet angezeigt, die Funktionalität aber nicht beeinträchtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-541">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="b2182-542">Es wurde ein Problem behoben, das dazu führen konnte, dass ein Dokument, das ein Excel-Diagramm enthält, nicht in PowerPoint oder Word gespeichert werden konnte.</span><span class="sxs-lookup"><span data-stu-id="b2182-542">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="b2182-543">Project</span><span class="sxs-lookup"><span data-stu-id="b2182-543">Project</span></span>

- <span data-ttu-id="b2182-544">Ein Problem wurde behoben, bei dem "Vorgang Prozent abgeschlossen" fälschlicherweise in einen Wert kleiner als 100 % geändert wurde, nachdem der Vorgang als abgeschlossen gekennzeichnet wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-544">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="b2182-545">Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.</span><span class="sxs-lookup"><span data-stu-id="b2182-545">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="b2182-546">Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-546">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="b2182-547">Visio</span><span class="sxs-lookup"><span data-stu-id="b2182-547">Visio</span></span>

- <span data-ttu-id="b2182-548">Im Shape-Infobereich wurden im Abschnitt "Shapedaten" inkonsistente Details zur Datei angezeigt, wenn diese in Visio Desktop angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-548">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="b2182-549">Dieses Problem wurde jetzt behoben.</span><span class="sxs-lookup"><span data-stu-id="b2182-549">It has now been fixed.</span></span>

- <span data-ttu-id="b2182-550">In Versionen vor 2016 importierte Bitmaps wurden aufgrund einiger Sicherheitsüberprüfungen nicht wiedergegeben.</span><span class="sxs-lookup"><span data-stu-id="b2182-550">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="b2182-551">Dieses Problem wurde im Visio-Abonnement behoben.</span><span class="sxs-lookup"><span data-stu-id="b2182-551">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="b2182-552">Word</span><span class="sxs-lookup"><span data-stu-id="b2182-552">Word</span></span>

- <span data-ttu-id="b2182-553">Es wurde ein Problem behoben, bei dem Kommentarkarten nicht immer hervorgehoben werden, wenn der Mauszeiger über die Kommentarkarte bewegt wird.</span><span class="sxs-lookup"><span data-stu-id="b2182-553">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="b2182-554">Behebt ein Problem, das dazu geführt hat, dass beim Navigieren über eine Kommentarkarte mit der Tabulatortaste der Fokus auf dem Bearbeitungsfeld für den Kommentar nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-554">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="b2182-555">Ein kosmetisches Problem wurde behoben, bei dem die Schaltfläche "OK" im Dialogfeld "Datei\Optionen" abgeblendet angezeigt, die Funktionalität aber nicht beeinträchtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-555">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="b2182-556">Während einer aktiven Sitzung zur gemeinsamen Dokumenterstellung kann das direkte Hinzufügen eines Bildes in eine Kommentarkarte dazu führen, dass ein Tag hinzugefügt wird.</span><span class="sxs-lookup"><span data-stu-id="b2182-556">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="b2182-557">Das Problem wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="b2182-557">This issue has been fixed.</span></span>

- <span data-ttu-id="b2182-558">Das Einfügen eines Steuerelements (beispielsweise eines Textinhaltssteuerelements) in eine Gleichung und das anschließende Speichern und Öffnen der Datei führte zu einem Fehler aufgrund nicht lesbaren Inhalts.</span><span class="sxs-lookup"><span data-stu-id="b2182-558">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="b2182-559">Ein Problem wurde behoben, aufgrund dessen das Speichern einer zuvor kennwortgeschützten Datei in einem Cloudspeicher nicht funktioniert hat.</span><span class="sxs-lookup"><span data-stu-id="b2182-559">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="b2182-560">Es wurde ein Problem mit der compare-Funktion für Dokumente behoben, die für die Bearbeitung geschützt waren.</span><span class="sxs-lookup"><span data-stu-id="b2182-560">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="b2182-561">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b2182-561">Office Suite</span></span>

- <span data-ttu-id="b2182-562">Beim Verwenden der Metadateneigenschaften MultiChoice/Verweis/Verwaltet mit Word/Excel/PowerPoint-Dokumenten und dem Speichern in einer SharePoint-Dokumentbibliothek waren diese Eigenschaften bisher auf 255 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="b2182-562">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="b2182-563">Wenn diese Eigenschaften 255 Zeichen überschritten, konnten solche Dokumente nicht gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="b2182-563">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="b2182-564">Mit dieser Änderung wurde dieser Grenzwert auf 2048 Zeichen erhöht.</span><span class="sxs-lookup"><span data-stu-id="b2182-564">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="b2182-565">Behebt ein Problem mit Word/Excel/PowerPoint, bei dem der User-Principal-Name (UPN) nicht mehr die Groß-/Kleinschreibung beachtet, was zu weniger Fehlern beim Arbeiten mit Dateien in SharePoint führt.</span><span class="sxs-lookup"><span data-stu-id="b2182-565">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="b2182-566">Ein Problem wurde behoben, das dazu führte, dass beim Öffnen mehrerer Dokumente in Word/Excel/PowerPoint aus derselben SharePoint-Bibliothek lediglich das erste geöffnete Dokument auf Richtlinienkonformität gescannt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-566">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-march-05"></a><span data-ttu-id="b2182-568">Version 2002: 05. März</span><span class="sxs-lookup"><span data-stu-id="b2182-568">Version 2002: March 05</span></span>
<span data-ttu-id="b2182-569">*Version 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="b2182-569">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="b2182-570">Korrekturen verschiedener Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b2182-570">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="b2182-571">Version 2002: 04. März</span><span class="sxs-lookup"><span data-stu-id="b2182-571">Version 2002: March 04</span></span>
<span data-ttu-id="b2182-572">*Version 2002 (Build 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="b2182-572">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b2182-574">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-574">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="b2182-575">Project</span><span class="sxs-lookup"><span data-stu-id="b2182-575">Project</span></span>
- <div><span data-ttu-id="b2182-576">Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-576">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span></div>


### <a name="office-suite"></a><span data-ttu-id="b2182-577">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b2182-577">Office Suite</span></span>
- <div><span data-ttu-id="b2182-578">Behebt ein Problem, das dazu geführt hat, dass beim Öffnen mehrerer Dokumente in Word/Excel/PowerPoint aus derselben SharePoint-Bibliothek lediglich das erste geöffnete Dokument auf Richtlinienkonformität gescannt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-578">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSWENDE)

## <a name="version-2002-march-01"></a><span data-ttu-id="b2182-580">Version 2002: 01. März</span><span class="sxs-lookup"><span data-stu-id="b2182-580">Version 2002: March 01</span></span>
<span data-ttu-id="b2182-581">*Version 2002 (Build 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="b2182-581">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="b2182-582">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-582">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="b2182-583">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-583">Outlook</span></span>

- <div><span data-ttu-id="b2182-584">Behebt ein Problem, das bewirkt hatte, dass Anwendungen von Drittanbietern keine E-Mail-Nachrichten mehr senden konnten.</span><span class="sxs-lookup"><span data-stu-id="b2182-584">Addresses an issue that caused third party applications to be unable to send email.</span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2002-february-24"></a><span data-ttu-id="b2182-586">Version 2002: 24. Februar</span><span class="sxs-lookup"><span data-stu-id="b2182-586">Version 2002: February 24</span></span>
<span data-ttu-id="b2182-587">*Version 2002 (Build 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="b2182-587">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="b2182-588">Korrekturen verschiedene Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b2182-588">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="b2182-589">Version 2002: 22. Februar</span><span class="sxs-lookup"><span data-stu-id="b2182-589">Version 2002: February 22</span></span>
<span data-ttu-id="b2182-590">*Version 2002 (Build 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="b2182-590">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="b2182-591">Korrekturen verschiedene Fehler und Leistungsprobleme.</span><span class="sxs-lookup"><span data-stu-id="b2182-591">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="b2182-592">Version 2002: 21. Februar</span><span class="sxs-lookup"><span data-stu-id="b2182-592">Version 2002: February 21</span></span>
<span data-ttu-id="b2182-593">*Version 2002 (Build 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="b2182-593">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="b2182-595">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b2182-595">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="b2182-596">Zugriff</span><span class="sxs-lookup"><span data-stu-id="b2182-596">Access</span></span>

- <span data-ttu-id="b2182-597">**Seien Sie beim Arbeiten im Abfrage-Designer, in der SQL-Ansicht und im Fenster „Beziehungen“ produktiver:** Klicken Sie zum Öffnen, Gestalten, Vergrößern oder Verkleinern und Ausblenden mit der rechten Maustaste auf die betreffende Tabelle.</span><span class="sxs-lookup"><span data-stu-id="b2182-597">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="b2182-598">Suchen und Ersetzen von Text in der SQL-Ansicht.</span><span class="sxs-lookup"><span data-stu-id="b2182-598">Search and replace text in SQL View.</span></span> <span data-ttu-id="b2182-599">Auswählen mehrerer Tabellen im Fenster „Beziehungen“.</span><span class="sxs-lookup"><span data-stu-id="b2182-599">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="b2182-600">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-600">Outlook</span></span>

- <span data-ttu-id="b2182-601">**Neue Benutzeroberfläche für WLAN-Netzwerke mit Anmeldung:** Sind Sie schon einmal einem WLAN-Netzwerk beigetreten, mit dem Sie sich anmelden mussten?</span><span class="sxs-lookup"><span data-stu-id="b2182-601">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="b2182-602">Outlook erkennt dies jetzt und hilft Ihnen, eine Verbindung zu herstellen.</span><span class="sxs-lookup"><span data-stu-id="b2182-602">Outlook now detects this and helps you get connected.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b2182-605">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-605">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="b2182-606">Excel</span><span class="sxs-lookup"><span data-stu-id="b2182-606">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="b2182-607">Ein Problem wurde behoben, bei dem CUBEWERT-Funktionen manchmal ein falsches Ergebnis zurückgaben.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="b2182-607">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;</span></span></div><div><span style="display:inline !important;"></span><br></div>


### <a name="outlook"></a><span data-ttu-id="b2182-608">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-608">Outlook</span></span>

- <div><span data-ttu-id="b2182-609">Behebt ein Problem, das dazu führte, dass Kommas im Ortsfeld einer Besprechung in Semikolons umgewandelt wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-609">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span></div>


- <div><span data-ttu-id="b2182-610">Behebt ein Problem, das zu einem Absturz führen könnte, wenn dasselbe Element in mehreren Fenstern angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="b2182-610">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span></div>


- <div><span data-ttu-id="b2182-611">Behebt ein Problem, das dazu führte, dass Outlook unerwartet alle E-Mails synchronisierte, selbst wenn der Synchronisierungsschieberegler auf eine kleinere Einstellung eingestellt ist.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="b2182-611">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span></div>


- <div><span data-ttu-id="b2182-612">Behebt ein Problem, das dazu führte, dass für Benutzer mit dem schwarzen Design die Dropdownliste &quot;Von&quot; als weißer Text auf weißem Hintergrund angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-612">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span></div>


- <div><span data-ttu-id="b2182-613"><span style="display:inline !important;">Diese Änderung stellt die Fähigkeit wieder her, mehrzeilige Betreffzeilen im Nachrichtenkopf anzuzeigen.</span></span><span class="sxs-lookup"><span data-stu-id="b2182-613"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-february-18"></a><span data-ttu-id="b2182-615">Version 2002: 18. Februar</span><span class="sxs-lookup"><span data-stu-id="b2182-615">Version 2002: February 18</span></span>
<span data-ttu-id="b2182-616">*Version 2002 (Build 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="b2182-616">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="b2182-617">Version 2002: 11. Februar</span><span class="sxs-lookup"><span data-stu-id="b2182-617">Version 2002: February 11</span></span>
<span data-ttu-id="b2182-618">*Version 2002 (Build 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="b2182-618">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="b2182-619">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="b2182-619">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS CONTENT START NICHT ENTFERNEN)

### <a name="feature-updates"></a><span data-ttu-id="b2182-621">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="b2182-621">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="b2182-622">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-622">Outlook</span></span>

- <span data-ttu-id="b2182-623">**Ziehen Sie E-Mails in eine Gruppe, die Sie besitzen:** Verschieben und Kopieren von Nachrichten und Unterhaltungen, indem Sie diese aus Ihrem Posteingang ziehen.</span><span class="sxs-lookup"><span data-stu-id="b2182-623">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="b2182-624">Die von ihnen gezogenen Nachrichten werden für alle Gruppenmitglieder freigegeben.</span><span class="sxs-lookup"><span data-stu-id="b2182-624">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="b2182-625">Word</span><span class="sxs-lookup"><span data-stu-id="b2182-625">Word</span></span>

- <span data-ttu-id="b2182-626">**Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.</span><span class="sxs-lookup"><span data-stu-id="b2182-626">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="b2182-627">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b2182-627">Office Suite</span></span>

- <span data-ttu-id="b2182-628">**Übersichtlichere Statusleistensymbole:** Statusleistensymbole sind jetzt einfacher zu sehen.</span><span class="sxs-lookup"><span data-stu-id="b2182-628">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="b2182-631">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="b2182-631">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="b2182-632">Zugriff</span><span class="sxs-lookup"><span data-stu-id="b2182-632">Access</span></span>

- <span data-ttu-id="b2182-633">Access-Vorlagen sollten nicht länger dazu führen, dass Anhangsspalten in einer Datenbank fehlschlagen.</span><span class="sxs-lookup"><span data-stu-id="b2182-633">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="b2182-634">Nachdem Sie eine Vorlage instanziiert haben, sollten Sie nun in der Lage sein, Ihrer Datenbank ein Anhangsfeld hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="b2182-634">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="b2182-635">Dieses Update behebt ein Problem bei der Verwendung von ADODB.</span><span class="sxs-lookup"><span data-stu-id="b2182-635">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="b2182-636">Das Recorder-Objekt im VB-Code meldet möglicherweise einen Fehler falsch.</span><span class="sxs-lookup"><span data-stu-id="b2182-636">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="b2182-637">Dieses Update behebt ein Problem, das dazu führen kann, dass Microsoft Access eine Identitätsspalte in einer verknüpften SQL-Server-Tabelle nicht identifiziert, was dazu führen kann, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.</span><span class="sxs-lookup"><span data-stu-id="b2182-637">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="b2182-638">Excel</span><span class="sxs-lookup"><span data-stu-id="b2182-638">Excel</span></span>

- <span data-ttu-id="b2182-639">Es wurde ein Problem behoben, bei dem Kommentarbefehle im Kontextmenü nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-639">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="b2182-640">Es wurde ein Problem behoben, durch das bei einigen Nutzern Abstürze auftraten, wenn Text in Spalten mit Zellen mit einem übergelaufenem Array konvertiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-640">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="b2182-641">Ein Problem wurde behoben, das dazu geführt hatte, dass Excel bei Verschieben von Text in Spalten mit dynamischen Pfeilern abgestürzt ist.</span><span class="sxs-lookup"><span data-stu-id="b2182-641">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="b2182-642">Outlook</span><span class="sxs-lookup"><span data-stu-id="b2182-642">Outlook</span></span>

- <span data-ttu-id="b2182-643">Ein Problem wurde behoben, das dazu geführt hatte, dass beim Durchblättern des Kalanders in der Monatsansicht die vorangegangenen Kalenderereignisse nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-643">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="b2182-644">Ordner, die unter "Favoriten" im linken Navigationsbereich gespeichert sind, können zeitweise verschwinden.</span><span class="sxs-lookup"><span data-stu-id="b2182-644">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="b2182-645">Es wurde ein Problem behoben, bei dem beim Angeben einer ungültigen Absenderadresse ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-645">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="b2182-646">Es wurde ein Problem behoben, durch das die Option zum Deaktivieren der Hervorhebung markierter Elemente in einigen Szenarien nicht berücksichtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-646">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="b2182-647">Es wurde ein Problem behoben, bei dem es durch das Abbrechen der Kontoeinrichtung einen Absturz gab.</span><span class="sxs-lookup"><span data-stu-id="b2182-647">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="b2182-648">Problem behoben, bei dem für auf Grundlage einer Aufbewahrungsrichtlinie ablaufende E-Mails zwei Beschriftungen angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-648">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="b2182-649">Eine mit der Aussage, dass die E-Mail in einem Tag, die andere, dass die E-Mail in zwei Tagen abläuft.</span><span class="sxs-lookup"><span data-stu-id="b2182-649">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="b2182-650">Es wurde ein Problem behoben, bei dem beim Anzeigen von mehr als 30 Kalendern in einer Citrix-Umgebung ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-650">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="b2182-651">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="b2182-651">PowerPoint</span></span>

- <span data-ttu-id="b2182-652">Ein Problem wurde behoben, bei dem Freihandelemente in einer PowerPoint-Freihandanimation nicht vollständig gerendert wurde oder übersprungen wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-652">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="b2182-653">Ein Problem wurde behoben, das dazu geführt hatte, dass PowerPoint Nach dem Schließen einer Datei diese nicht sofort aus der Sammlung von Präsentationen entfernt hat, wenn Ereignisverarbeiter ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="b2182-653">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="b2182-654">Dadurch war die Zahl der vom Objektmodell gemeldeten, geöffneten Präsentationen falsch und das Herunterfahren von PowerPoint wurde verhindert.</span><span class="sxs-lookup"><span data-stu-id="b2182-654">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="b2182-655">Ein Problem mit dem Textmarker wurde behoben: Weißer Text mit dunkleren Textmarkerfarben wurde Schwarz mit Graustufen gedruckt.</span><span class="sxs-lookup"><span data-stu-id="b2182-655">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="b2182-656">Project</span><span class="sxs-lookup"><span data-stu-id="b2182-656">Project</span></span>

- <span data-ttu-id="b2182-657">Es wurde ein Problem behoben, bei dem 100% Aufgaben vom Typ „feste Dauer“ fälschlicherweise zu weniger als 100% erledigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-657">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="b2182-658">Word</span><span class="sxs-lookup"><span data-stu-id="b2182-658">Word</span></span>

- <span data-ttu-id="b2182-659">Beim Aktualisieren eines Inhaltsverzeichnisses bzw. dem Blättern durch dieses wird manchmal möglicherweise ein grauer Bereich auf dem Dokument angezeigt.</span><span class="sxs-lookup"><span data-stu-id="b2182-659">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="b2182-660">Es wurde ein Problem mit der Verwendung von „Durchsuchen“ zum Speichern einer Datei behoben, das nicht funktioniert hat, wenn ein Kommentar geschrieben, jedoch nicht gepostet worden war und der Benutzer versucht hatte, die Datei zu speichern.</span><span class="sxs-lookup"><span data-stu-id="b2182-660">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="b2182-661">Ein Problem wurde behoben, das dazu geführt hatte, dass beim Hin- und Herwechseln zwischen Kommentar-Karten manchmal der anfänglich ausgewählte Kommentar mit einer Auswahlhervorhebung angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-661">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="b2182-662">Es wurde ein Problem behoben, bei dem die kursive Formatierung verloren ging, nachdem ein Kommentar bearbeitet, der Text kursiv geschrieben und anschließend veröffentlicht wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-662">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="b2182-663">Problem behoben, bei dem ein Kommentarhinweis im Lesemodus mit Inverser Seitenfarbe nicht sichtbar war.</span><span class="sxs-lookup"><span data-stu-id="b2182-663">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="b2182-664">Ein Problem wurde behoben, bei dem die Entwurfsversion eines Stammkommentars bei der gemeinsamen Dokumenterstellung zeitweise nicht beibehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-664">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="b2182-665">Wenn „SlideTrack“ aktiviert und der Bereich „Kommentare“ geschlossen ist, kann der Bereich „Kommentare“ mit STRG+ALT+M möglicherweise nicht geöffnet werden.</span><span class="sxs-lookup"><span data-stu-id="b2182-665">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="b2182-666">Es wurde ein Problem behoben, das dazu geführt hatte, dass beim Hinzufügen von @mention in einer Tabelle die Fehlermeldung „Eine Tabelle in diesem Dokument ist beschädigt“ generiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-666">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="b2182-667">Problem behoben, bei dem Kommentarbefehle (Kommentar bearbeiten, auf Kommentar antworten, Kommentar löschen, Kommentar auflösen) nicht im Kontextmenü von Kommentaren angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="b2182-667">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="b2182-668">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="b2182-668">Office Suite</span></span>

- <span data-ttu-id="b2182-669">Behebt ein Problem, das dazu geführt hat, dass Korrekturhilfe-Paket Norwegen Nynorsk (nn-no) nicht ordnungsgemäß installiert wurde.</span><span class="sxs-lookup"><span data-stu-id="b2182-669">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="b2182-670">Diese Änderung behebt gemeldete Probleme mit Grafikadaptern, die die integrierte Intel-GPU nutzen.</span><span class="sxs-lookup"><span data-stu-id="b2182-670">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)


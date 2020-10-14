---
title: Versionshinweise für Versionen des halbjährlichen Unternehmenskanals (Vorschau) im Jahr 2020
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt IT-Experten Anmerkungen zur Version für Releases im halbjährlichen Kanal (gezielt) für Microsoft 365 Apps im Jahr 2020 zur Verfügung.
ms.openlocfilehash: 1d67f64f2d0821addfdffbe4ac5b51895bf1e48f
ms.sourcegitcommit: ef46a4fc154c7bca37e37a7456c36f92ffc15ebb
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/13/2020
ms.locfileid: "48453393"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview-releases-in-2020"></a><span data-ttu-id="e1cf9-103">Versionshinweise für Versionen des halbjährlichen Unternehmenskanals (Vorschau) im Jahr 2020</span><span class="sxs-lookup"><span data-stu-id="e1cf9-103">Release notes for Semi-Annual Enterprise Channel (Preview) releases in 2020</span></span>

<span data-ttu-id="e1cf9-104">Diese Versionshinweise enthalten Informationen zu neuen Features und nicht sicherheitsrelevanten Updates, die in halbjährlichen Kanal-Updates (Vorschau) im Jahr 2020 für Microsoft 365 Apps for Enterprise, Microsoft 365 Apps for Business sowie in den Abonnementversionen der Desktop-Apps für Project und Visio enthalten sind.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="e1cf9-105">Wir nehmen einige Änderungen an den Updatekanälen für Microsoft 365-Apps vor, unter anderem fügen wir einen neuen Updatekanal hinzu (Monatlicher Enterprise-Kanal) und ändern die Namen der vorhandenen Updatekanäle.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="e1cf9-106">Um mehr zu erfahren, [lesen Sie diesen Artikel](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="e1cf9-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>


## <a name="version-2008-october-13"></a><span data-ttu-id="e1cf9-107">Version 2008: 13. Oktober</span><span class="sxs-lookup"><span data-stu-id="e1cf9-107">Version 2008: October 13</span></span>
<span data-ttu-id="e1cf9-108">*Version 2008 (Build 13127.20638)*</span><span class="sxs-lookup"><span data-stu-id="e1cf9-108">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="e1cf9-109">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="e1cf9-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="e1cf9-111">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="e1cf9-111">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="e1cf9-112">Excel</span><span class="sxs-lookup"><span data-stu-id="e1cf9-112">Excel</span></span>

- <span data-ttu-id="e1cf9-113">Ein Fehler in PivotDateFilter-APIs, in denen die Filterbedingungen "Vorher" und "Nachher" vertauscht waren, wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-113">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="e1cf9-114">Es wurde ein Problem behoben, bei dem Benutzer einen PivotTable-Filter nicht ändern konnten, weil er auf einen Wert eingestellt war, der in einer Analysis Services-Datenbank nicht mehr vorhanden war.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-114">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="e1cf9-115">Es wurde ein Problem behoben, durch das Excel abstürzen kann, wenn die Schnellanalyse nach dem Fixieren der obersten Zeile des Blatts verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-115">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="e1cf9-116">Es wurde ein Problem behoben, durch das eine Warnung zu einer beschädigten Arbeitsmappe verursacht werden konnte, wenn Sie Formeln mit wennnv () enthielt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-116">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="e1cf9-117">Outlook</span><span class="sxs-lookup"><span data-stu-id="e1cf9-117">Outlook</span></span>

- <span data-ttu-id="e1cf9-118">Behebt ein Problem, das bewirkt, dass Benutzer freigegebene Kalender nicht schließen konnten, indem Sie in der Ecke auf das "X" klicken.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-118">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="e1cf9-119">Behebt ein Problem, das dazu führte, dass die Einstellung "Verbesserungen bei gemeinsam genutzten Kalendern aktivieren" manchmal nicht auf bestehende gemeinsam genutzte Kalender angewendet werden konnte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-119">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="e1cf9-120">Behebt ein Problem, durch das Benutzern beim Öffnen einer Cloudanlage auf der Safelinks-Seite anstelle des Dokuments, das sie öffnen wollten, ein Fehler angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-120">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="e1cf9-121">Behebt ein Leistungsproblem beim Anlagenupload.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-121">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="e1cf9-122">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e1cf9-122">PowerPoint</span></span>

- <span data-ttu-id="e1cf9-123">Diese Änderung behebt ein Problem mit der Funktion "Export in animiertes GIF", wobei durch das Klicken auf die Schaltfläche "Exportieren" nicht exportiert wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-123">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="e1cf9-124">Sicherheitsproblembehebung für ein Problems, bei dem IRM-Schutz beim Öffnen einer PowerPoint-Datei in der geschützten Anzeige deaktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-124">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="word"></a><span data-ttu-id="e1cf9-125">Word</span><span class="sxs-lookup"><span data-stu-id="e1cf9-125">Word</span></span>

- <span data-ttu-id="e1cf9-126">Es wurde ein Problem behoben, bei dem es zu einem Absturz kam, wenn Benutzer bestimmte sehr große E-Mails öffneten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-126">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="e1cf9-127">Es wurde ein Problem behoben, das beim Öffnen eines Dokuments zu einem Absturz führen konnte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-127">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="e1cf9-128">Es wurde ein Problem behoben, das beim Starten von Word zu einem Absturz führen konnte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-128">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="e1cf9-129">Es wurde ein Problem mit dem Dialogfeld "Formatvorlagenkatalog" behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-129">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="e1cf9-130">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="e1cf9-130">Office Suite</span></span>

- <span data-ttu-id="e1cf9-131">Wenn ein Benutzer ein Dokument/ eine Datei auf Tintenstrahldrucker aus Office druckt und die Druckertinte niedrig ist, wird die Meldung "Wenig Toner" oder "Kein Toner" angezeigt, auch wenn Tintenstrahldrucker keine Toner haben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-131">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="e1cf9-132">Nachricht wird geändert, um "Wenig Toner/ Tinte" & "Kein Toner/ keine Tinte" anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-132">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="e1cf9-133">Behebt eine hohe CPU-Auslastung beim Leerlauf mit GIF/animated model3D</span><span class="sxs-lookup"><span data-stu-id="e1cf9-133">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="e1cf9-134">Diese Änderung behebt die Ursache für einen Absturz, der beim Starten von Office-Apps auftrat, weil die Datei "d2d1.dll" nicht geladen werden konnte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-134">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-september-08"></a><span data-ttu-id="e1cf9-136">Version 2008: 08. September</span><span class="sxs-lookup"><span data-stu-id="e1cf9-136">Version 2008: September 08</span></span>
<span data-ttu-id="e1cf9-137">*Version 2008 (Build 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="e1cf9-137">*Version 2008 (Build 13127.20408)*</span></span>

<span data-ttu-id="e1cf9-138">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="e1cf9-138">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="e1cf9-140">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="e1cf9-140">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="e1cf9-141">Zugriff</span><span class="sxs-lookup"><span data-stu-id="e1cf9-141">Access</span></span>

- <span data-ttu-id="e1cf9-142">**Seien Sie beim Arbeiten im Abfrage-Designer, in der SQL-Ansicht und im Fenster „Beziehungen“ produktiver:** Klicken Sie zum Öffnen, Gestalten, Vergrößern oder Verkleinern und Ausblenden mit der rechten Maustaste auf die betreffende Tabelle.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-142">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="e1cf9-143">Suchen und Ersetzen von Text in der SQL-Ansicht.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-143">Search and replace text in SQL View.</span></span> <span data-ttu-id="e1cf9-144">Auswählen mehrerer Tabellen im Fenster „Beziehungen“.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-144">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="e1cf9-145">**Tabellen mit weniger Klicks hinzufügen:** Verwenden Sie den Aufgabenbereich „Tabellen hinzufügen“, der während Ihrer Arbeit geöffnet bleibt, um Tabellen zu Beziehungen und Abfragen hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-145">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="e1cf9-146">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-146">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="e1cf9-147">Excel</span><span class="sxs-lookup"><span data-stu-id="e1cf9-147">Excel</span></span>

- <span data-ttu-id="e1cf9-148">**Verbesserte Kartendiagramme:** Wir haben Kartendiagramme durch Integration mit den geografischen Datentypen von Excel verbessert, wodurch Sie umfangreiche Informationen zu den Orten auf Ihrer Karte anzeigen können.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-148">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="e1cf9-149">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-149">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="e1cf9-150">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-150">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="e1cf9-151">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="e1cf9-151">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="e1cf9-152">**Erstellen von PivotTables aus Datasets in Power BI in Excel:** Sie können mit wenigen Klicks PivotTables in Excel erstellen, die mit in Power BI gespeicherten Datensätzen verbunden sind.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-152">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span><span data-ttu-id="e1cf9-153"> Auf diese Weise können Sie sowohl PivotTables als auch Power BI optimal nutzen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-153"> Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="e1cf9-154">Sie können Ihre Daten mit PivotTables aus Ihren sicheren Power BI-Datensätzen berechnen, zusammenfassen und analysieren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-154">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="e1cf9-155">Mehr dazu</span><span class="sxs-lookup"><span data-stu-id="e1cf9-155">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="e1cf9-156">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="e1cf9-156">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="e1cf9-157">**Ihre Lieblingsfunktionen von Excel sind jetzt noch schneller:** Die Funktionen SUMMEWENNS, MITTELWERTWENNS, ZÄHLENWENNS, MAXWENNS und MINWENNS sind jetzt viel schneller als je zuvor.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-157">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="e1cf9-158">Gelangen Sie schneller zum Endergebnis.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-158">Get to the bottom line more quickly.</span></span> <span data-ttu-id="e1cf9-159">Probieren Sie es jetzt aus.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-159">Try one now.</span></span>

- <span data-ttu-id="e1cf9-160">**RTD-Verbesserungen (Real-Time Data):** In Office 365, Version 2002, monatlicher Kanal und höher, ist die Excel-Funktion RealTimeData (RTD) beim Berechnen der Daten in der Tabelle wesentlich schneller als in Excel 2010.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-160">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="e1cf9-161">Wir haben Engpässe in den zugrunde liegenden Arbeitsspeicher- und Datenstrukturen entfernt und sie threadsicher gemacht, damit sie für alle verfügbaren Threads der Multithread-Neuberechnung (MTR) berechnet werden können.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-161">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="e1cf9-162">Outlook</span><span class="sxs-lookup"><span data-stu-id="e1cf9-162">Outlook</span></span>

- <span data-ttu-id="e1cf9-163">**Aktualisierungen freigebender Kalender funktionieren jetzt noch schneller:** Outlook ist in der Lage, freigegebene Kalender in Office 365 mithilfe der REST API zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-163">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="e1cf9-164">Aktivieren Sie die Vorschau, um schnellere und zuverlässigere Aktualisierungen für freigegebene Kalender zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-164">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="e1cf9-165">**Bessere Ergebnisse – im Handumdrehen:** wir haben die Suche aktualisiert, damit Sie intelligenter, schneller und zuverlässiger als je zuvor ist.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-165">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="e1cf9-166">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-166">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="e1cf9-167">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-167">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="e1cf9-168">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="e1cf9-168">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="e1cf9-169">**Ziehen Sie E-Mails in eine Gruppe, die Sie besitzen:** Verschieben und Kopieren von Nachrichten und Unterhaltungen, indem Sie diese aus Ihrem Posteingang ziehen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-169">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="e1cf9-170">Die von ihnen gezogenen Nachrichten werden für alle Gruppenmitglieder freigegeben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-170">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="e1cf9-171">Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span><span class="sxs-lookup"><span data-stu-id="e1cf9-171">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="e1cf9-172">**Der Kalender wird rundumerneuert:** Sie können visuelle Aktualisierungen anzeigen, mit denen Ihr Kalender einfacher durchsucht werden kann.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-172">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="e1cf9-173">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-173">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="e1cf9-174">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="e1cf9-174">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="e1cf9-175">**An Besprechungen teilnehmen, ohne den Posteingang zu verlassen:** Sie brauchen nicht zu Ihrem Kalender zu wechseln, um an Onlinebesprechungen teilzunehmen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-175">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="e1cf9-176">Wenn der Kalender im Aufgabenbereich angeheftet ist, können Sie mit nur einem Klick an einer Besprechung teilnehmen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-176">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="e1cf9-177">**Neue Benutzeroberfläche für WLAN-Netzwerke mit Anmeldung:** Sind Sie schon einmal einem WLAN-Netzwerk beigetreten, mit dem Sie sich anmelden mussten?</span><span class="sxs-lookup"><span data-stu-id="e1cf9-177">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="e1cf9-178">Outlook erkennt dies jetzt und hilft Ihnen, eine Verbindung zu herstellen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-178">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="e1cf9-179">Weitere Detailinformationen finden Sie in diesem [Blogbeitrag](https://insider.office.com/de-DE/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span><span class="sxs-lookup"><span data-stu-id="e1cf9-179">See details in [blog post](https://insider.office.com/de-DE/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="e1cf9-180">**Erhalten Sie E-Mail-Vorschläge, wenn Sie nach einer Person suchen**: Wenn Sie den Namen einer Person im Suchfeld eingeben, werden die relevantesten E-Mail-Nachrichten in die Ihnen gezeigten Suchvorschläge einbezogen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-180">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="e1cf9-181">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-181">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a><span data-ttu-id="e1cf9-182">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e1cf9-182">PowerPoint</span></span>

- <span data-ttu-id="e1cf9-183">**Mit \@Erwähnen andere auf sich aufmerksam machen:** Mithilfe von Erwähnungen in Kommentaren können Sie Kollegen informieren, wenn Sie deren Input benötigen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-183">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="e1cf9-184">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-184">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="e1cf9-185">**Verbesserte Kartendiagramme:** Wir haben Kartendiagramme durch Integration mit den geografischen Datentypen von Excel verbessert, wodurch Sie umfangreiche Informationen zu den Orten auf Ihrer Karte anzeigen können.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-185">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="e1cf9-186">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-186">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="e1cf9-187">**GIFs im Handumdrehen:** eine Folie, ein Frame.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-187">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="e1cf9-188">Erstellen Sie auf einfache Weise Schleifen-GIFs in PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-188">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="e1cf9-189">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-189">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="e1cf9-190">Einzelheiten finden Sie im [Blogbeitrag](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/).</span><span class="sxs-lookup"><span data-stu-id="e1cf9-190">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="e1cf9-191">**Bessere Diagramme: Mit besseren Konnektoren und einem reibungsloseren Tintenkonvertierungsprozess können Sie Ihre Ideen zuversichtlicher einfärben.**</span><span class="sxs-lookup"><span data-stu-id="e1cf9-191">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="e1cf9-192">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-192">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="e1cf9-193">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-193">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="e1cf9-194">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="e1cf9-194">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="e1cf9-195">**Kommentare:** Die neue Kommentarumgebun g in PowerPoint ermöglicht es Ihnen, schnell und einfach Kommentare zu Ihren Dokumenten zu entdecken und hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-195">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="e1cf9-196">Modernisieren Sie Ihre Arbeitsabläufe bei der Zusammenarbeit mit neuen Funktionen wie Verankern und Auflösen von Kommentaren, Aufgaben, verbesserten Benachrichtigungen über Erwähnungen und vielem mehr.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-196">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="e1cf9-197">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-197">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- <span data-ttu-id="e1cf9-198">**Synchronisieren von Änderungen während der Präsentation:** Änderungen können jetzt synchronisiert werden, wenn sie vorgenommen werden, selbst wenn sich die Präsentation im Bildschirmpräsentationsmodus befindet.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-198">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="e1cf9-199">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-199">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="e1cf9-200">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="e1cf9-200">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="e1cf9-201">**Link zu einer Folie:** Bitten Sie einen Kollegen um einen Beitrag zu Ihrer Foliengruppe zu leisten, und leiten Sie ihn direkt zu der Folie, bei der Sie Hilfe benötigen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-201">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="e1cf9-202">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-202">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="e1cf9-203">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span><span class="sxs-lookup"><span data-stu-id="e1cf9-203">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="e1cf9-204">**Verbesserte Stream-Video-Leistung in PowerPoint:** Wir haben die Wiedergabeleistung von Microsoft Stream-Videos verbessert, um die Ladezeit von Videos zu minimieren und eine reibungslose Wiedergabe zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-204">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="e1cf9-205">Verwenden Sie Ihre Unternehmensvideos aus Microsoft Stream, um bessere Präsentationen zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-205">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>


### <a name="word"></a><span data-ttu-id="e1cf9-206">Word</span><span class="sxs-lookup"><span data-stu-id="e1cf9-206">Word</span></span>

- <span data-ttu-id="e1cf9-207">**Verbesserte Kartendiagramme:** Wir haben Kartendiagramme durch Integration mit den geografischen Datentypen von Excel verbessert, wodurch Sie umfangreiche Informationen zu den Orten auf Ihrer Karte anzeigen können.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-207">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="e1cf9-208">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-208">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="e1cf9-209">**Auswählen von Freihandeingabe:** Das Lasso-Tool auf der Registerkarte "Zeichnen" hilft Ihnen beim Auswählen von per Freihand gezeichneten Objekten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-209">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="e1cf9-210">Wählen Sie einzelne Striche oder ganze Wörter aus.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-210">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="e1cf9-211">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-211">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="e1cf9-212">**Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-212">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="e1cf9-213">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="e1cf9-213">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="e1cf9-214">**Bestätigung der Aktion in Sprachausgaben:** Bestätigung der Aktion ist eine wichtige Voraussetzung für die Barrierefreiheit.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-214">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="e1cf9-215">Mit der Einführung einer neuen Benachrichtigungs-API von Windows können wir jetzt Benutzer der Sprachausgabe über den Erfolg ihrer Aktionen informieren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-215">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="e1cf9-216">„Ausschneiden“, „Kopieren“, „Einfügen“, „Fett“, „Kursiv“, „Unterstrichen“, „Rückgängig“, „Wiederholen“, "Autokorrektur“ und "Automatische Großschreibung“ werden jetzt Benutzern der Sprachausgabe in Word unter Win32 angekündigt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-216">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="e1cf9-217">Zum Aktivieren dieses Features aktivieren Sie die Sprachausgabe, indem Sie WINDOWS+STRG+EINGABE drücken.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-217">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="e1cf9-218">Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="e1cf9-218">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="e1cf9-219">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="e1cf9-219">Office Suite</span></span>

- <span data-ttu-id="e1cf9-220">**Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-220">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="e1cf9-223">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="e1cf9-223">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="e1cf9-224">Zugriff</span><span class="sxs-lookup"><span data-stu-id="e1cf9-224">Access</span></span>

- <span data-ttu-id="e1cf9-225">Es wurde ein Problem mit dem Einfügen von verknüpften SQL-Tabellen behoben, die eine Identität (z. b. Autowert) enthalten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-225">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

- <span data-ttu-id="e1cf9-226">Ein Problem wurde behoben, bei dem die Abfrageausführung ungefähr doppelt so lange dauerte als erwartet.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-226">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="e1cf9-227">Ein Problem wurde behoben, um den Datentyp Datum/Uhrzeit in Ihrem Code aufrufen zu können, ohne dass die APP abstürzt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-227">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="e1cf9-228">Ein Problem wurde behoben, damit Sie jetzt wieder zu Ihrer am meisten aktualisierten Access-Version zurückkehren können, und verwenden Sie DAO/VBA zum Verwalten und Bearbeiten eines Dezimal-Datentyps.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-228">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

- <span data-ttu-id="e1cf9-229">Diese Korrektur behebt das Problem, bei dem der Versuch, bestimmte Abfragen auszuführen, zuvor die Fehlermeldung „Abfrage ist zu komplex“ erzeugt hat.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-229">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="e1cf9-230">In Access wurde dieses aktuelle Problem behoben, es werden aber unsere zusätzlichen Schnittstellen untersucht, um sicherzustellen, dass dieses Problem nicht fortbesteht.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-230">Access has fixed this current issue, but will be investigating our additional interfaces to ensure that this problem does not persist.</span></span> <span data-ttu-id="e1cf9-231">Das Team informiert Sie über zukünftige Updates. Wir bedanken uns für Ihre Geduld.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-231">The team will inform you with future updates; we appreciate your patience.</span></span>

- <span data-ttu-id="e1cf9-232">Das Problem wurde gelöst – Sie können nun unseren ODBC-Treiber außerhalb der Office-Click-to-Run-App verwenden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-232">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="e1cf9-233">Excel</span><span class="sxs-lookup"><span data-stu-id="e1cf9-233">Excel</span></span>

- <span data-ttu-id="e1cf9-234">Bei Arbeitsmappen, die sich im schreibgeschützten Modus befanden, wurde möglicherweise die automatische Dokumentklassifizierung durchgeführt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-234">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="e1cf9-235">Ein Absturz wurde behoben, der beim Versuch, eine Datenverbindung herzustellen, auftreten konnte, wenn Sie sich von Ihrem Konto abgemeldet haben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-235">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="e1cf9-236">Es wurde ein Problem behoben, bei dem Excel abstürzen kann, wenn versucht wird, PivotTables in ein Diagrammblatt einzufügen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-236">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

- <span data-ttu-id="e1cf9-237">Beim Versuch eine Datei zu speichern, die eine Formel mit der Funktion LET() enthält, konnte ein Fehler auftreten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-237">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="e1cf9-238">Es wurde ein Problem behoben, bei dem Excel unter bestimmten Umständen abstürzte, wenn "Format übertragen" verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-238">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>

- <span data-ttu-id="e1cf9-239">Es wurde ein Problem behoben, das dazu führte, dass CustomUI XML für eine benutzerdefinierte Menübandregisterkarte beim Speichern in SharePoint/OneDrive entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-239">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="e1cf9-240">Es wurde ein Problem behoben, bei dem Excel möglicherweise nicht mehr reagierte, nachdem STRG+UMSCHALT+Pfeiltasten zum Scrollen verwendet wurden, wenn das Excel-Fenster über Microsoft Teams gemeinsam genutzt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-240">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="e1cf9-241">Es wurde ein Problem behoben, bei dem das Klicken auf einen Link zu einer anderen Stelle innerhalb derselben Arbeitsmappe in einigen Fällen dazu führt, dass die Arbeitsmappe ausgeblendet wird.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-241">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="e1cf9-242">Es wurde ein Problem behoben, bei dem die externe Verknüpfung nicht mehr funktioniert, nachdem die Datei erneut geöffnet wurde, wenn der Dateipfad zu lang ist.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-242">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="e1cf9-243">Application.Evaluate (VBA) funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-243">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="e1cf9-244">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-244">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="e1cf9-245">Ein Problem wurde behoben, bei dem Excel in manchen Fällen abstürzte, nachdem ein Blatt mit einer PivotTable kopiert wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-245">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="e1cf9-246">Damit wird ein Problem behoben, bei dem interne Tabelleneigenschaften für Verbindungen, die vom SQL-Datenanbieter in älteren Office-Versionen erstellt wurden, anders als in Office 365 festgelegt wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-246">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="e1cf9-247">Dies führte dazu, dass die Dropdown-Liste "Tabellenvorschau/Abfrageeditor" für Dateien mit Verbindungen, die in älteren Office-Versionen erstellt wurden, deaktiviert wurde, wenn sie mit Office 365 geöffnet wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-247">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>

- <span data-ttu-id="e1cf9-248">Es wurde ein Problem behoben, bei dem externe Links beim Füllen nicht aktualisiert werden, wenn das Quellbuch geschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-248">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="e1cf9-249">Ein Problem wurde behoben, bei dem Freihandeingaben dazu führen konnten, dass Excel nicht mehr reagierte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-249">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="onenote"></a><span data-ttu-id="e1cf9-250">OneNote</span><span class="sxs-lookup"><span data-stu-id="e1cf9-250">OneNote</span></span>

- <span data-ttu-id="e1cf9-251">Informieren Sie die Benutzer über die Infoleiste über temporäre Anpassungen in Microsoft OneNote, die dazu beitragen, die Synchronisierung und Dienstverfügbarkeit bei hoher weltweiter Nutzung zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-251">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="e1cf9-252">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehende Anpassung der Synchronisierungshäufigkeit in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-252">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="e1cf9-253">Die Erkennung des Status der gemeinsamen Dokumenterstellung wurde verbessert, um die Ressourcennutzung zu verringern.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-253">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="e1cf9-254">Verbesserte Synchronisierungs- und Servicestabilität durch vorübergehende Reduzierung der maximal zulässigen Größe neuer eingebetteter Anhänge auf 50 MB in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-254">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="e1cf9-255">Bei Dateien, die dieses Limit überschreiten, haben Benutzer die Möglichkeit, die Datei auf OneDrive hochzuladen und einen Link in OneNote einzufügen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-255">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="e1cf9-256">Verbesserte Synchronisierungs- und Servicestabilität durch vorübergehende Deaktivierung der Videoaufzeichnung in der Anwendung in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-256">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="e1cf9-257">Lokale Notizbücher sind von dieser Maßnahme nicht betroffen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-257">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="e1cf9-258">Die Synchronisierungs- und Servicestabilität wurde durch vorübergehende Änderung der Häufigkeit der Erstellung von Seitenversionshistorien verbessert.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-258">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

- <span data-ttu-id="e1cf9-259">Die Synchronisierungs- und Serverstabilität wurde durch vorübergehende Deaktivierung des Verschiebens von Seiten in den Papierkorb verbessert.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-259">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="e1cf9-260">Benutzer, die eine Seite löschen möchten, werden stattdessen in einem Dialogfeld gefragt, ob sie die Seite dauerhaft löschen möchten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-260">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

### <a name="outlook"></a><span data-ttu-id="e1cf9-261">Outlook</span><span class="sxs-lookup"><span data-stu-id="e1cf9-261">Outlook</span></span>

- <span data-ttu-id="e1cf9-262">Behebt ein Problem, das dazu führte, dass Benutzer, die versuchten, eine Besprechungsanfrage von einem zu ihrem Profil hinzugefügten sekundären Konto aus zu erstellen, kein leeres Von: Feld anstelle ihrer E-Mail-Adresse sahen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-262">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="e1cf9-263">Behebt ein Problem, das dazu führte, dass Benutzer nach dem Hinzufügen eines gemeinsam genutzten Postfachs keine Verbindung zu öffentlichen Ordnern herstellen konnten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-263">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="e1cf9-264">Es wurde ein Problem behoben, das bewirkt hat, dass Besprechungen aus dem Kalender eines Managers nicht entfernt werden konnten, wenn sie von einem Delegierten unter bestimmten Umständen abgelehnt wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-264">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="e1cf9-265">Es wurde ein Problem behoben, durch das einige Benutzende des Features "Verbesserungen bei gemeinsam genutzten Kalendern" nicht in der Lage waren, einen neu hinzugefügten freigegebenen Kalender anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-265">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="e1cf9-266">Behebt ein Problem, das bei der Interaktion mit Cloud-Anlagen gelegentlich zu Abstürzen führte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-266">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="e1cf9-267">Ein Problem wurde behoben, das zu einem Absturz führte, wenn Benutzer von CLP die Absenderadresse in einer Antwort von geschütztem in ungeschützten Kontext wechselten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-267">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="e1cf9-268">Es wurde ein Problem behoben, bei dem Outlook die Datenschutzrichtlinie nicht aktiviert hat, um Tipps für Benutzer zu geben, die für den Dienst bezahlt haben und M365 Business Plus-Pläne nutzen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-268">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="e1cf9-269">Es wurde ein Problem mit dem Ereignis "CLP-Überwachung" für die Bezeichnung "Antworten/Weiterleiten" behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-269">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="e1cf9-270">Ein Problem wurde behoben, bei dem die Breite des Ordnerbereichs unerwartet geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-270">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="e1cf9-271">Ein Problem wurde behoben, durch das Benutzer das Erstellungsdatum der Anlagen sehen konnten, die Sie per Drag & Drop in Ihr Dateisystem kopiert haben, wobei es auf den 1. Januar 4501 festgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-271">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

- <span data-ttu-id="e1cf9-272">Es wurde ein Problem behoben, das bewirkt hat, dass Benutzende einiger Zeichensätze beim Hinzufügen eines Smart Link zu einer Microsoft Office SharePoint Online-Datei Dateinamen falsch angezeigt bekamen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-272">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="e1cf9-273">Es wurde ein Problem behoben, durch das Benutzern die Nachricht "Die Regeln auf diesem Computer entsprechen nicht den Regeln in Microsoft Exchange" angezeigt wird, wenn sie ihre Regeln in Outlook aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-273">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="e1cf9-274">Ein Problem wurde behoben, das dazu führte, dass Outlook keine Suchvorschläge abrufen konnte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-274">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>

- <span data-ttu-id="e1cf9-275">Es wurde ein Problem behoben, durch das Benutzer der Verbesserungen des am "Freigegebenen Kalender" Kalenderfehler sahen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-275">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="e1cf9-276">Es wurde ein Problem behoben, das dazu führte, dass Benutzer in einigen Szenarios zeitweilig Hängen und Abstürzen erfuhren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-276">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="e1cf9-277">Es wurde ein Problem behoben, das zu einem Absturz führte, wenn Benutzende beim Löschen von 4 oder mehr E-Mails von einem POP-Konto mit der Option "Nur Kopfzeilen herunterladen" einen Absturz erlebten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-277">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="e1cf9-278">Es wurde ein Problem behoben, bei dem die Option "Weiterleitung zulassen" in den "Antwortoptionen" für Kalenderbesprechungen nicht angezeigt wurde, wenn die Option für das Herunterladen freigegebener Ordner NICHT aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-278">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="e1cf9-279">Es wurde ein Problem behoben, das dazu führte, dass Delegierte beim Bearbeiten eines vorhandenen Kalendertermins im Kalender eines Managers eine Fehlermeldung erhielten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-279">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="e1cf9-280">Es wurde ein Problem behoben, aufgrund dessen bei Benutzern Abstürze von MAPI-Anwendungen von Drittanbietern auftraten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-280">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>

- <span data-ttu-id="e1cf9-281">Es wurde ein Problem behoben, durch das Outlook nach einem Windows-Update beim Öffnen von lokal gespeicherten MSG- oder OFT-Dateien abstürzte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-281">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="e1cf9-282">Ein Problem wurde behoben, das dazu geführt hat, dass Outlook bei einigen Windows-Versionen abstürzt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-282">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="e1cf9-283">Es wurde ein Problem behoben, das dazu führte, dass Benutzer von Windows 10-Serverversionen die Warnung "Antivirenstatus: Ungültig" gesehen haben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-283">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="e1cf9-284">Diese Windows-Version unterstützt die Virenerkennung, es wurde jedoch kein Virenschutzprogramm gefunden, obwohl das Virenschutzprogramm korrekt installiert war.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-284">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="e1cf9-285">Es wurde ein Problem behoben, durch das Outlook nach einem Windows-Update beim Öffnen von lokal gespeicherten MSG- oder OFT-Dateien abstürzte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-285">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="e1cf9-286">Ein Problem wurde behoben, das dazu geführt hat, dass Outlook bei einigen Windows-Versionen abstürzt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-286">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="e1cf9-287">Es wurde ein Problem behoben, das dazu führte, dass Benutzer ständig von Outlook aufgefordert wurden, das Reparaturtool für den Posteingang auszuführen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-287">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="e1cf9-288">Es wurde ein Problem behoben, das dazu führte, dass Benutzer gelegentlich einen Absturz feststellten, wenn Sie den X-Knopf auf ihrer Maus verwendeten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-288">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="e1cf9-289">Ein Problem wurde behoben, das dazu führte, dass Benutzer OneDrive-Anlagen von außerhalb ihres Mandanten nicht auf ihrem lokalen Computer speichern konnten, wenn sie im Dialogfeld "Sicherheit" die Option "Speichern" wählten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-289">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="e1cf9-290">Ein Problem wurde behoben, das dazu führte, dass die Seite des Terminplanungs-Assistenten nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-290">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="e1cf9-291">Es wurde ein Problem behoben, das dazu führte, dass die Seite des Planungsassistenten von einigen Benutzern nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-291">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="e1cf9-292">Ein Problem wurde behoben, das beim Abrufen von Persona-Informationen gelegentlich zu einem Absturz führte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-292">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>

- <span data-ttu-id="e1cf9-293">Dies behebt ein Problem, das beim Bearbeiten von Empfängern gelegentlich zu Abstürzen führte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-293">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="e1cf9-294">Behebt ein Problem, das dazu führte, dass Benutzern bei Verwendung der kompakten Ansicht gelegentlich Anomalien angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-294">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="e1cf9-295">Es wurde ein Problem behoben, durch das Outlook-Benutzern in kompakten Ansichten Probleme mit der Navigation angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-295">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>

- <span data-ttu-id="e1cf9-296">Es wurde ein Problem behoben, das bewirkt hat, dass das Rechtsklick-Kontextmenü nicht in den Suchsteuerelementen angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-296">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="e1cf9-297">Behebt ein Problem, durch das Benutzern beim Beantworten von oder Verfassen neuer E-Mails den folgenden Fehler angezeigt wurde: „Einige der Dateien auf dieser Webseite befinden sich nicht am erwarteten Speicherort.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-297">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="e1cf9-298">Möchten Sie sie dennoch herunterladen?</span><span class="sxs-lookup"><span data-stu-id="e1cf9-298">Do you want to download them anyway?</span></span> <span data-ttu-id="e1cf9-299">Wenn Sie sicher sind, dass die Webseite aus einer vertrauenswürdigen Quelle stammt, klicken Sie auf 'Ja'.“</span><span class="sxs-lookup"><span data-stu-id="e1cf9-299">If you’re sure the Web page is from a trusted source, click Yes"</span></span>

- <span data-ttu-id="e1cf9-300">Behebt ein Problem, bei dem sich das Programm beim Verlassen von Outlook aufhängte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-300">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="e1cf9-301">Es wurde ein Problem behoben, das dazu führte, dass bei der Suche nach einem Feature in "Features vorschlagen" keine Ergebnisse zurückgegeben wurden und der Benutzer keine Möglichkeit hatte, eine neue Idee für Features zu übermitteln. </span><span class="sxs-lookup"><span data-stu-id="e1cf9-301">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="e1cf9-302">Ein Problem wurde behoben, das zu Formatierungsproblemen in Benachrichtigungen über einen Sicherheitsvorfälle führte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-302">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

- <span data-ttu-id="e1cf9-303">Es wurde ein Problem behoben, bei dem beim Einreichen von Feedback aus einer Administratorbenachrichtigung ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-303">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="e1cf9-304">Es wurde ein Problem beim Kopieren und Einfügen des SVG-Bilds behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-304">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="e1cf9-305">Dies behebt ein Problem, das beim Bearbeiten von Empfängern gelegentlich zu Abstürzen führte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-305">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="e1cf9-306">Es wurde ein Problem beim Kopieren und Einfügen des SVG-Bilds behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-306">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="e1cf9-307">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e1cf9-307">PowerPoint</span></span>

- <span data-ttu-id="e1cf9-308">Die Ursache für einen Absturz wurde behoben, der auftrat, wenn in einer Datei sowohl moderne als auch ältere Kommentare verwendet werden, wodurch ein Upgrade der Kommentare ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-308">Fixed a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="e1cf9-309">Ein Absturzproblem mit der PowerPoint-App wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-309">We have fixed a crash issue with PowerPoint app.</span></span>

- <span data-ttu-id="e1cf9-310">Wir haben ein Absturzproblem mit dem Vorschlagsbereich behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-310">We have fixed a crash issue with suggestion pane.</span></span>

### <a name="project"></a><span data-ttu-id="e1cf9-311">Project</span><span class="sxs-lookup"><span data-stu-id="e1cf9-311">Project</span></span>

- <span data-ttu-id="e1cf9-312">Ein Problem wurde behoben, bei dem ein zusätzliches ProjectBeforeTaskChange-Ereignis ausgelöst wird, wenn Vorgänger/Nachfolger-Daten in einer Formular-Maske bearbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-312">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="e1cf9-313">Ein Problem wurde behoben, bei dem Project beim Speichern von Projekten möglicherweise abstürzt, die mit älteren Project-Versionen erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-313">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="e1cf9-314">Es wurde ein Problem behoben, bei dem der Benutzer keine zeitgesteuerte Baseline-Arbeit eingeben konnte, wenn die Einstellung zum Schutz der aktuellen Arbeit aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-314">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

- <span data-ttu-id="e1cf9-315">Ein Problem wurde behoben, bei dem "Vorgang Prozent abgeschlossen" fälschlicherweise in einen Wert kleiner als 100 % geändert wurde, nachdem der Vorgang als abgeschlossen gekennzeichnet wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-315">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="e1cf9-316">Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-316">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="e1cf9-317">Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-317">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="e1cf9-318">Ein Problem wurde behoben, bei dem das Ereignis „ProjectBeforeTaskChange“ nicht erkannt wird, wenn ein Vorgang über die Schaltfläche „Deaktivieren“ deaktiviert/aktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-318">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="e1cf9-319">Folgendes Problem wurde behoben: Wenn Sie Project in Verbindung mit Project Web App verwenden, das Kommas als Dezimaltrennzeichen festgelegt ist, und Sie versuchten, einer Abhängigkeit eine Verzögerung hinzuzufügen, schlägt die Methode "TaskDependencies Add" fehl.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-319">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

- <span data-ttu-id="e1cf9-320">Ein Problem wurde behoben, bei dem Projekte aus Project Web App nicht im Project-Desktop Client geöffnet werden konnten, wenn die URL auf ".com" endete.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-320">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

- <span data-ttu-id="e1cf9-321">Es wurde ein Problem behoben, das bewirkt, dass nicht alle Abhängigkeiten korrekt kopiert werden, wenn ein Vorgang mit mehreren Abhängigkeiten eingefügt wird.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-321">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="e1cf9-322">Es wurde ein Problem behoben, bei dem man kein PDF/XPS aus Project in einer SharePoint-Dokumentbibliothek speichern konnte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-322">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>

- <span data-ttu-id="e1cf9-323">Es wurde ein Problem behoben, bei dem eine Aufgabe, die als 100 % abgeschlossen gekennzeichnet ist, fälschlicherweise weniger als 100 % abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-323">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="e1cf9-324">Es wurde ein Problem behoben, bei dem das Ereignis "ProjectBeforeTaskChange" nicht ausgelöst wurde, wenn eine Änderung am Projektzusammenfassungsvorgang – entweder am Projektstart/Aufgabenfeld – vorgenommen wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-324">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="e1cf9-325">Ein Problem wurde behoben, bei dem die Restkosten nicht immer richtig berechnet wurden, wenn für eine Ressource mehrere Kostensatztabellen definiert waren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-325">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

- <span data-ttu-id="e1cf9-326">Es wurde ein Problem behoben, bei dem das Projektabschlussdatum für Projekte, die mit der Microsoft Office SharePoint Online-Aufgabenliste verbunden sind, nicht aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-326">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="e1cf9-327">Ein Problem wurde behoben, bei dem die im Dialogfeld "Ressourcen zuordnen" ausgewählte Aufgabe nicht mit der in der Ansicht "Task Board" ausgewählten Aufgabe identisch ist.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-327">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="e1cf9-328">Ein Problem wurde behoben, bei dem ein Projekt, das in einen ungültigen Zustand geraten war, nicht geöffnet werden konnte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-328">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>

### <a name="skype"></a><span data-ttu-id="e1cf9-329">Skype</span><span class="sxs-lookup"><span data-stu-id="e1cf9-329">Skype</span></span>

- <span data-ttu-id="e1cf9-330">Wenn ein Benutzer eine Richtlinie erhält, die ihn in die Kategorie "Nur für Teams" verschiebt, konnte er dennoch das Outlook-Add-In "Skype for Business" zur Planung von Besprechungen verwenden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-330">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="e1cf9-331">Nach diesem Update können Sie keine Besprechungen mit Skype for Business mehr planen, nachdem der Client die Richtlinie gelesen hat, in der angegeben ist, dass der Benutzer "Nur für Teams" ist, und in den Modus "Nur an Besprechung teilnehmen" wechselt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-331">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="e1cf9-332">Darüber hinaus aktiviert sich das Outlook-Add-In "Skype for Business" beim Start nicht selbst, wenn es sieht, dass sich der Skype for Business-Client im Modus "Nur an Besprechung teilnehmen" befindet.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-332">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="e1cf9-333">Der Hautton des Tanzemoticons wurde auf neutrale Farbe geändert.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-333">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="e1cf9-334">Word</span><span class="sxs-lookup"><span data-stu-id="e1cf9-334">Word</span></span>

- <span data-ttu-id="e1cf9-335">Es wurde ein Problem beim Öffnen von Word-Dokumenten aus der benutzerdefinierten Dokumentbereitstellung (aspx) behoben, wenn die URL eine Abfragekomponente enthält.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-335">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="e1cf9-336">Diese Änderung behebt ein Problem, bei dem Office-Anwendungen nach einer vorherigen gemeinsamen Dokumenterstellung in einem Silent-Save-Fehlerstatus hängenbleiben konnten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-336">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="e1cf9-337">Behebt ein Problem, das zum Absturz beim Beantworten oder Verfassen neuer E-Mails führte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-337">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="e1cf9-338">Es wurde ein Problem behoben, das dazu führte, dass Benutzer gelegentlich einen Absturz feststellten, wenn Sie den X-Knopf auf ihrer Maus verwendeten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-338">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="e1cf9-339">Es wurde ein Problem beim Kopieren und Einfügen des SVG-Bilds behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-339">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="e1cf9-340">Es wurde ein Problem behoben, bei dem der Benutzer beim Ändern der Größe einer Form möglicherweise Inhalte verliert.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-340">We fixed an issue where the user might lose content when resize a shape.</span></span>

- <span data-ttu-id="e1cf9-341">Ein Problem wurde behoben, bei dem die Basisformatvorlagen nicht mit der Standardformatvorlage aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-341">We fixed an issue which the base styles are not updated with Normal style.</span></span>

- <span data-ttu-id="e1cf9-342">Es wurde ein Problem behoben, bei dem das Makro „AutoOpen“ vor „AutoExec“ ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-342">We fixed an issue where macro AutoOpen runs before AutoExec.</span></span>

- <span data-ttu-id="e1cf9-343">Es wurde ein Problem beim Kopieren und Einfügen des SVG-Bilds behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-343">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="e1cf9-344">Es wurde ein Problem behoben, das beim Ziehen einiger Inhalte aus der App möglicherweise zu einem Absturz führte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-344">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="e1cf9-345">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="e1cf9-345">Office Suite</span></span>

- <span data-ttu-id="e1cf9-346">Bei dem alten, nicht webdienstbasierten Bereich Freigeben könnte das Schließen des Dokuments bei geöffnetem Bereich Freigeben zu einem Absturz führen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-346">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="e1cf9-347">Dieses Problem wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-347">This is now fixed.</span></span>

- <span data-ttu-id="e1cf9-348">Ein Timing-Problem wurde behoben, das beim Schließen von Office-Dateien zu einem Absturz führen konnte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-348">Fixed a timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="e1cf9-349">Es wurde das Problem der Fehlerrate von „ValidateInstall“ behoben, indem die Bing-Add-On-Installationsvalidierung standardmäßig auf „wahr“ gesetzt und die erfolgreiche Ausführung von MSI als erfolgreiche Installation betrachtet wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-349">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="e1cf9-350">Ein neuer Sturz von AppV51 wurde zurückportiert, um eine Regression im vorherigen AppV51 zu beheben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-350">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="e1cf9-351">Es wurde ein Problem mit Klick-und-Los behoben, das beim Erstellen eines festen Links für symbolische Links zu einem Updatefehler führte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-351">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="e1cf9-352">Es wurde ein Problem behoben, das dazu führte, dass eine Laufzeitmeldung angezeigt wurde, obwohl der Übergang zum vollständigen Produkt abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-352">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="e1cf9-353">Der Fix für dieses Problem bestand darin, sicherzustellen, dass der Dienst hinzugefügte Produkte ordnungsgemäß berechnet.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-353">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="e1cf9-354">Wir haben die neu hinzugefügten Produkte herausgefiltert (dabei wurde sichergestellt, dass sie auch in der neuen Konfiguration vorhanden sind) und sie am Ende der vorhandenen Produkt-Release-IDs hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-354">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>

- <span data-ttu-id="e1cf9-355">Wir haben ein Problem behoben, bei dem Benutzer unter bestimmten Bedingungen die Benutzeroberflächenelemente oder -inhalte nicht angezeigt wurden, insbesondere beim Öffnen oder Verlassen der Referentenansicht oder bei der Verwendung mehrerer Bildschirme.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-355">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>

- <span data-ttu-id="e1cf9-356">Mit dieser Änderung werden potenzielle Probleme beim Laden und Abspielen von animierten Inhalten wie GIFs oder 3D-Modellen behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-356">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="e1cf9-357">Diese Änderung behebt ein Problem, bei dem im Dialogfeld „Bild komprimieren“ bestimmte Benutzereinstellungen nicht beibehalten werden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-357">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>

- <span data-ttu-id="e1cf9-358">Das Update behebt ein Problem in Microsoft Office, bei dem Visual Basic for Applications-Projekte mit Referenzen, die bei der Suche nach in der PATH-Umgebungsvariable angegebenen Speicherorten gefunden werden sollen, zur Laufzeit möglicherweise nicht richtig gefunden werden, was zu VBA-Laufzeitfehlern führt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-358">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="e1cf9-359">Dieses Update behebt ein Problem in Visual Basic for Applications in Microsoft Office, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung beim Laden als fehlerhaft angesehen werden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-359">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="e1cf9-360">Mit diesem Fix wird ein Fehler behoben, der verhindert, dass Sie gleichzeitig den Zugriff einschränken und Dateien mit einem Kennwort schützen können.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-360">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="e1cf9-361">Es wurde ein Absturzproblem mit dem Office-Host in Windows behoben, wenn ein Add-in aktiviert wird, während die Registrierung TabProcGrowth den Wert REG_SZ Typ hat.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-361">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="e1cf9-362">Der Office-Host stürzte in Fenstern ab, wenn ein Add-In aktiviert wird, während der Registrierungsschlüssel HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth auf Null gesetzt ist.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-362">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="e1cf9-363">Mit dieser Änderung wird dieses Problem behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-363">This change would fix this issue.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-august-11"></a><span data-ttu-id="e1cf9-365">Version 2002: 11. August</span><span class="sxs-lookup"><span data-stu-id="e1cf9-365">Version 2002: August 11</span></span>
<span data-ttu-id="e1cf9-366">*Version 2002 (Build 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="e1cf9-366">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="e1cf9-367">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="e1cf9-367">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="e1cf9-369">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="e1cf9-369">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="e1cf9-370">Excel</span><span class="sxs-lookup"><span data-stu-id="e1cf9-370">Excel</span></span>

- <span data-ttu-id="e1cf9-371">Ein Problem wurde behoben, bei dem verhindert wurde, dass mit der Option „Schreibschutz empfohlen“ geöffnete Dateien bearbeitet werden konnten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-371">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="e1cf9-372">OneNote</span><span class="sxs-lookup"><span data-stu-id="e1cf9-372">OneNote</span></span>

- <span data-ttu-id="e1cf9-373">Redundante Identitätsaufrufe wurden entfernt, um die Ressourcennutzung zu verringern.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-373">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="e1cf9-374">Die Erkennung des Status der gemeinsamen Dokumenterstellung wurde verbessert, um die Ressourcennutzung zu verringern.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-374">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="e1cf9-375">Die Funktion zum Erkennen von Fehlern und die Qualität der Synchronisierung wurden verbessert.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-375">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="e1cf9-376">Outlook</span><span class="sxs-lookup"><span data-stu-id="e1cf9-376">Outlook</span></span>

- <span data-ttu-id="e1cf9-377">Ein Problem wurde behoben, das beim Starten von Outlook für einige Mandanten zu einem erheblichen Leistungsproblem führte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-377">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="e1cf9-378">Skype</span><span class="sxs-lookup"><span data-stu-id="e1cf9-378">Skype</span></span>

- <span data-ttu-id="e1cf9-379">Ein Problem wurde behoben, bei dem das Starten einer Bildschirmfreigabe auf einem 32-Bit-Skype for Business-Client fehlschlagen kann, nachdem er mehrere Tage lang ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-379">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="e1cf9-380">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="e1cf9-380">Office Suite</span></span>

- <span data-ttu-id="e1cf9-381">Ein Problem wurde behoben, bei dem einige Dokumente – nach Deaktivierung von „Automatisches Speichern“ durch eine Gruppenrichtlinie – die neuesten Serverinhalte beim Öffnen möglicherweise so lange nicht zeigen, bis der Benutzer auf „Verfügbare Updates“ geklickt hat.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-381">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-july-14"></a><span data-ttu-id="e1cf9-383">Version 2002: 14. Juli</span><span class="sxs-lookup"><span data-stu-id="e1cf9-383">Version 2002: July 14</span></span>
<span data-ttu-id="e1cf9-384">*Version 2002 (Build 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="e1cf9-384">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="e1cf9-385">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="e1cf9-385">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="e1cf9-387">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="e1cf9-387">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="e1cf9-388">Excel</span><span class="sxs-lookup"><span data-stu-id="e1cf9-388">Excel</span></span>

- <span data-ttu-id="e1cf9-389">Beschleunigen des Ladens von Dateien, die im lokalen OneDrive-Ordner zur Verfügung stehen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-389">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="e1cf9-390">Es wurde ein Problem behoben, das dazu führte, dass CustomUI XML für eine benutzerdefinierte Multifunktionsleisten-Registerkarte beim Speichern in SharePoint/OneDrive entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-390">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="e1cf9-391">Es wurde ein Problem behoben, bei dem die Fehlermeldung „Diese Arbeitsmappe wird derzeit von einer anderen Arbeitsmappe referenziert und kann nicht geschlossen werden“ eingeblendet wurde, weil Add-Ins in alphabetischer Reihenfolge und nicht in einer vom Benutzer festgelegten Reihenfolge geladen wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-391">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="e1cf9-392">Es wurde ein Problem behoben, bei dem beim Klicken auf einen Hyperlink zu einer Stelle in einer bereits geöffneten Arbeitsmappe eine Arbeitsmappe ausgeblendet werden konnte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-392">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="e1cf9-393">Es wurde ein Problem behoben, bei dem einige kopierte und eingefügte Diagrammverknüpfungen zugeordnete Laufwerksadressen anstelle von Universaladressen verwendeten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-393">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="e1cf9-394">Die Leistung beim Löschen von Spalten mit verbundenen Zellen wurde verbessert.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-394">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="e1cf9-395">Ein Problem wurde behoben, bei dem Druckernamen in der Liste der Drucker im Dialogfeld „Drucken“ wiederholt werden konnten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-395">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="e1cf9-396">Es wurde ein Problem behoben, bei dem Arbeitsblätter, die mehrere Formeln mit definierten Namen enthielten, zu längeren Zeiten beim Speichern von Dateien geführt haben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-396">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="e1cf9-397">Outlook</span><span class="sxs-lookup"><span data-stu-id="e1cf9-397">Outlook</span></span>

- <span data-ttu-id="e1cf9-398">Es wurde ein Problem behoben, bei dem das IME-Fenster (Eingabemethoden-Editor) den zugrunde liegenden Text, der über den IME eingegeben wird, überlappte, wenn mehrere Monitore mit unterschiedlichen Auflösungen verwendet wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-398">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="e1cf9-399">Es wurde ein Problem behoben, das bewirkte, dass bei einer bevorstehenden Änderung der Zeitzonendefinition Terminserien oder Besprechungen zur falschen Uhrzeit angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-399">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="e1cf9-400">Es wurde ein Problem behoben, durch das Benutzern die Nachricht "Die Regeln auf diesem Computer entsprechen nicht den Regeln in Microsoft Exchange" angezeigt wird, wenn sie ihre Regeln in Outlook aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-400">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="e1cf9-401">Es wurde ein Problem behoben, bei dem die Option "Weiterleitung zulassen" in den "Antwortoptionen" für Kalenderbesprechungen nicht angezeigt wurde, wenn die Option für das Herunterladen freigegebener Ordner NICHT aktiviert war.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-401">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="e1cf9-402">Ein Problem wurde behoben, durch das gelegentlich Kategorien in E-Mail-Nachrichten nicht mehr aufschienen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-402">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="e1cf9-403">Ein Problem wurde behoben, durch das Stellvertretungen auf unterschiedlichen Computern unterschiedliche Ordnerhierarchien für freigegebene Postfächer angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-403">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="e1cf9-404">Ein Problem wurde behoben, durch das Stellvertretungen beim Bearbeiten eines vorhandenen Kalendertermins im Kalender eines Managers eine Fehlermeldung erhalten haben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-404">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="e1cf9-405">Ein Problem wurde behoben, das bewirkt hatte, dass der Text einer NDR-Nachricht nach der Bearbeitung des Betreffs von Unicode in ASCII geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-405">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="e1cf9-406">Es wurde ein Problem behoben, durch das Benutzer einen Absturz erfahren, wenn zwei Add-Ins der gleichen Menübandgruppe eine Schaltfläche hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-406">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="e1cf9-407">Es wurde ein Problem behoben, aufgrund dessen Benutzer nicht in der Lage waren, E-Mails an eine persönliche Verteilerliste zu senden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-407">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="e1cf9-408">Es wurde ein Problem behoben, das bewirkt, dass Links nicht zu E-Mails mit der richtigen standardmäßigen Mandantenberechtigung hinzugefügt werden können, wenn die standardmäßige Mandantenberechtigung als "jeder" konfiguriert ist.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-408">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="e1cf9-409">Ein Problem wurde behoben, das dazu führte, dass Benutzer OneDrive-Anlagen von außerhalb ihres Mandanten nicht auf ihrem lokalen Computer speichern konnten, wenn sie im Dialogfeld "Sicherheit" die Option "Speichern" wählten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-409">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="e1cf9-410">Word</span><span class="sxs-lookup"><span data-stu-id="e1cf9-410">Word</span></span>

- <span data-ttu-id="e1cf9-411">Es wurde ein Problem im Coautthoring behoben, wenn die Richtlinie "FileBlick\Word2007Files" aktiviert wird.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-411">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="e1cf9-412">Es wurde das Problem behoben, dass Word QuickPart beim Hinzufügen eines Suchfelds, das umbenannt wurde, nicht funktioniert.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-412">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="e1cf9-413">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="e1cf9-413">Office Suite</span></span>

- <span data-ttu-id="e1cf9-414">Ein Problem wurde behoben, bei dem Benutzer bei der gemeinsamen Erstellung von großen PowerPoint-Dateien übermäßige Netzwerk- und CPU-Auslastung erfahren können.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-414">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="e1cf9-415">Ein neuer Sturz von AppV51 wurde zurückportiert, um eine Regression im vorherigen AppV51 zu beheben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-415">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="e1cf9-416">Es wurde ein Absturzproblem mit dem Office-Host in Windows behoben, wenn ein Add-In aktiviert wird, während die Registrierung TabProcGrowth den Wert REG_SZ Typ hat.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-416">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-june-09"></a><span data-ttu-id="e1cf9-418">Version 2002: 9. Juni</span><span class="sxs-lookup"><span data-stu-id="e1cf9-418">Version 2002: June 09</span></span>
<span data-ttu-id="e1cf9-419">*Version 2002 (Build 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="e1cf9-419">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="e1cf9-420">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="e1cf9-420">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="e1cf9-422">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="e1cf9-422">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="e1cf9-423">Excel</span><span class="sxs-lookup"><span data-stu-id="e1cf9-423">Excel</span></span>

- <span data-ttu-id="e1cf9-424">Es wurde ein Problem behoben, bei dem die externe Verknüpfung nicht mehr funktioniert, nachdem die Datei erneut geöffnet wurde, wenn der Dateipfad zu lang ist.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-424">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="e1cf9-425">Es wurde ein Problem behoben, bei dem Excel u. U. nicht mehr reagierte, nachdem STRG+UMSCHALT+Pfeiltasten zum Scrollen verwendet wurden, wenn das Excel-Fenster über Microsoft Teams gemeinsam genutzt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-425">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="e1cf9-426">Ein Problem mit der Skalierung von Kontrollkästchen in Formularsteuerelementen beim Drucken wurde behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-426">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="e1cf9-427">Ein Absturz konnte auftreten, wenn versucht wurde, Änderungen mithilfe des Legacymodus "Freigegebene Arbeitsmappe" auf einem neuen Blatt für eine Arbeitsmappe aufzulisten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-427">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="e1cf9-428">Das Einfügen einer Spalte in eine gefilterte Liste würde länger dauern als erwartet.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-428">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="e1cf9-429">Es wurde ein Problem behoben, bei dem ein @-Symbol, mit dem eine Formel beginnt, als impliziter Schnittmengenoperator betrachtet wird.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-429">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="e1cf9-430">Outlook</span><span class="sxs-lookup"><span data-stu-id="e1cf9-430">Outlook</span></span>

- <span data-ttu-id="e1cf9-431">Ermöglicht die Teilnahme an einer Teambesprechung direkt über den systemeigenen Teams-Client.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-431">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="e1cf9-432">Es wurde ein Problem behoben, bei dem Outlook die Datenschutzrichtlinie nicht aktiviert hat, um Tipps für Benutzer zu geben, die für den Dienst bezahlt haben und M365 Business Plus-Pläne nutzen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-432">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="e1cf9-433">Es wurde ein Problem behoben, aufgrund dessen Benutzer mit der falschen Browseremulationseinstellung nicht die Authentifizierungsaufforderung für Gmail ausführen konnten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-433">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="e1cf9-434">Es wurde ein Problem behoben, aufgrund dessen Outlook-Benutzern auf Serverbetriebssystemen die Fehlermeldung "Antivirenstatus: Ungültig" angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-434">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="e1cf9-435">Diese Version von Windows unterstützt die Erkennung von Antivirus, aber es wurde kein Antivirus gefunden, obwohl Antivirus korrekt konfiguriert war.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-435">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="e1cf9-436">Word</span><span class="sxs-lookup"><span data-stu-id="e1cf9-436">Word</span></span>

- <span data-ttu-id="e1cf9-437">Es wurde ein Problem behoben, bei dem die Ausrichtung von Wörtern in einem Dokument durcheinandergebracht wurde, wenn Benutzer nach dem Drucken mit Schnelldruck versuchten, den Text zu bearbeiten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-437">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="e1cf9-438">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="e1cf9-438">Office Suite</span></span>

- <span data-ttu-id="e1cf9-439">Dieses Problem wurde behoben, indem die Kanalnamen in der Januar 2020-Verzweigung in der Backstage-Version auf die neuen Kanalnamen aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-439">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="e1cf9-440">Dieses Problem wurde behoben. Wenn ein Gerät nun mit Richtlinien verwaltet wird, wird nicht die DMS Audience-API aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-440">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="e1cf9-441">Es wurde das Problem behoben, aufgrund dessen es beim Hinzufügen oder Entfernen von Apps in einer einzigen Transaktion zu einer unvollständigen Entfernung kam.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-441">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="e1cf9-442">Der Office-Host stürzte in Fenstern ab, wenn ein Add-In aktiviert wird, während der Registrierungsschlüssel HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth auf Null gesetzt ist.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-442">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="e1cf9-443">Mit dieser Änderung wird dieses Problem behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-443">This change would fix this issue.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-may-12"></a><span data-ttu-id="e1cf9-445">Version 2002: 12. Mai</span><span class="sxs-lookup"><span data-stu-id="e1cf9-445">Version 2002: May 12</span></span>
<span data-ttu-id="e1cf9-446">*Version 2002 (Build 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="e1cf9-446">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="e1cf9-447">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="e1cf9-447">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="e1cf9-449">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="e1cf9-449">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="e1cf9-450">Excel</span><span class="sxs-lookup"><span data-stu-id="e1cf9-450">Excel</span></span>

- <span data-ttu-id="e1cf9-451">Das Öffnen einer Arbeitsmappe mit Verweisen auf zahlreiche andere Arbeitsmappen, insbesondere mit versteckten Fenstern, würde langsamer als erwartet ablaufen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-451">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="e1cf9-452">Das Öffnen von CSV-Dateien dauerte unter bestimmten Umständen länger als erwartet.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-452">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="e1cf9-453">Excel stürzt möglicherweise unter bestimmten Umständen ab, wenn zwischen den Arbeitsmappen mit anderen Zoomstufen gewechselt wird.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-453">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="e1cf9-454">Es wurde ein Problem mit VBA behoben, bei dem das Schreiben von Werten in einem Wertebereich langsamer als erwartet war.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-454">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="e1cf9-455">Daten, die aus einer nach Farbe gefilterten Spalte kopiert wurden, werden manchmal nicht ordnungsgemäß eingefügt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-455">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="e1cf9-456">Ein Problem wurde behoben, bei dem Excel in manchen Fällen abstürzte, nachdem ein Blatt mit einer PivotTable kopiert wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-456">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="e1cf9-457">In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-457">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="e1cf9-458">Es wurde ein Problem behoben, bei dem die Eigenschaft "Wert wird überschneidet bei" auf der Diagrammachse unerwartet geändert wird, wenn Sie eine Datei speichern und erneut öffnen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-458">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="e1cf9-459">Die Verwendung von Range.Value und Range.Value2 (VBA) würde dazu führen, dass Formeln als dynamische Arrays eingegeben werden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-459">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="e1cf9-460">OneNote</span><span class="sxs-lookup"><span data-stu-id="e1cf9-460">OneNote</span></span>

- <span data-ttu-id="e1cf9-461">Lokalisiert die Benachrichtigung, durch die der Benutzer mehr über temporäre Maßnahmen erfahren kann, die in der OneNote-Benutzeroberfläche implementiert sind, um die Synchronisierungs- und Dienststabilität zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-461">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="e1cf9-462">Zeigt eine Benachrichtigung an, durch die der Benutzer mehr über temporäre Maßnahmen erfahren kann, die in der OneNote-Benutzeroberfläche implementiert sind, um die Synchronisierungs- und Dienststabilität zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-462">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="e1cf9-463">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehendes verringern der Anzahl und Häufigkeit der Synchronisierungen von Seiten des Versionsverlaufs in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-463">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="e1cf9-464">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehende Deaktivierung des Papierkorbs in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-464">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="e1cf9-465">Wenn ein Benutzer versucht, die Daten zu löschen, die normalerweise in den Papierkorb verschoben werden, wird der Benutzer gefragt, ob er die Daten beibehalten oder dauerhaft löschen möchte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-465">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="e1cf9-466">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehende Anpassung der Synchronisierungshäufigkeit in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-466">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="e1cf9-467">Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehendes zurückschieben des Downloads eingebetteter Dateien und Bilder in Online-Notizbücher, bis der Benutzer zu der Seite in OneNote 2016 navigiert.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-467">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="e1cf9-468">Verbesserte Synchronisierungs- und Servicestabilität durch vorübergehende Deaktivierung der Videoaufzeichnung in der Anwendung in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-468">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="e1cf9-469">Lokale Notizbücher sind von dieser Maßnahme nicht betroffen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-469">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="e1cf9-470">Verbesserte Synchronisierungs- und Servicestabilität durch vorübergehende Reduzierung der maximal zulässigen Größe neuer eingebetteter Anhänge auf 50 MB in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-470">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="e1cf9-471">Bei Dateien, die dieses Limit überschreiten, haben Benutzer die Möglichkeit, die Datei auf OneDrive hochzuladen und einen Link in OneNote einzufügen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-471">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="e1cf9-472">Outlook</span><span class="sxs-lookup"><span data-stu-id="e1cf9-472">Outlook</span></span>

- <span data-ttu-id="e1cf9-473">Ein Problem wurde behoben, bei dem die Breite des Ordnerbereichs unerwartet geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-473">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="e1cf9-474">Es wurde ein Problem behoben, das bewirkt, dass Benutzer beim Öffnen von .msg- und .oft-Dateien nach einem Windows-Update einen Absturz erfahren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-474">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="e1cf9-475">Behebt ein Problem, das dazu führte, dass Benutzer beim Weiterleiten großer HTML-Nachrichten den Nachrichtentext abgeschnitten sahen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-475">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="e1cf9-476">Dieses Update behebt ein Problem, bei dem Microsoft Outlook beim Anzeigen oder Verfassen von Nachrichten nicht die aktuelle Vertraulichkeitskennzeichnung anzeigt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-476">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="e1cf9-477">Es wurde ein Problem behoben, aufgrund dessen Benutzer nicht in der Lage waren, E-Mails an eine persönliche Verteilerliste zu senden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-477">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e1cf9-478">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e1cf9-478">PowerPoint</span></span>

- <span data-ttu-id="e1cf9-479">Es wurde ein Problem mit der Weiterleitung von korrekten Nachrichten für Benutzer behoben, die eine Kopie einer Datei mit verbesserten Kommentaren öffnen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-479">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="e1cf9-480">Word</span><span class="sxs-lookup"><span data-stu-id="e1cf9-480">Word</span></span>

- <span data-ttu-id="e1cf9-481">Es wurde ein Problem behoben, bei dem Access und Publisher nicht ordnungsgemäß gestartet werden, je nachdem, welche Sprachen installiert wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-481">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="e1cf9-482">Es wurde ein Problem mit der compare-Funktion für Dokumente behoben, die für die Bearbeitung geschützt waren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-482">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="e1cf9-483">Es wurde ein Problem beim Zusammenführen von 2 Dokumenten in ein Dokument behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-483">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="e1cf9-484">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="e1cf9-484">Office Suite</span></span>

- <span data-ttu-id="e1cf9-485">Diese Behebung soll sicherstellen, dass die Projektanwendung das Netzwerk nicht blockiert, wenn die Datei im Cache des Clients gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-485">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="e1cf9-486">Das Problem wurde behoben, bei dem ein interner Vorgang bei einem Fehler eine Ausnahme ausgelöst hat, anstatt diesen zu protokollieren und fortzufahren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-486">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="e1cf9-487">Die betroffenen Benutzer werden nicht mehr daran gehindert, Updates zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-487">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="e1cf9-488">Dadurch wird sichergestellt, dass skizzierte Konturen im Menüband ordnungsgemäß funktionieren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-488">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="e1cf9-489">Es wurde ein Problem beim Öffnen von Dateien von lokalen Standorten aus mit einigen bestimmten Proxykonfigurationen behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-489">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="e1cf9-490">Dieses Update behebt ein Problem in Visual Basic for Applications in Microsoft Office, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung beim Laden als fehlerhaft angesehen werden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-490">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="e1cf9-491">Das Update behebt ein Problem in Microsoft Office, bei dem Visual Basic for Applications-Projekte mit Referenzen, die bei der Suche nach in der PATH-Umgebungsvariable angegebenen Speicherorten gefunden werden sollen, zur Laufzeit möglicherweise nicht richtig gefunden werden, was zu VBA-Laufzeitfehlern führt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-491">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="e1cf9-492">Dieses Update behebt ein Problem in Microsoft Word, bei dem Text, der länger als 255 Zeichen ist, während die Anwendung einer Vertraulichkeitskennzeichnung eingefügt wird, später nicht identifiziert und entfernt werden konnte, wenn die Kennzeichnungsrichtlinie eine Kopf- oder Fußzeile oder ein Wasserzeichen angewendet hat.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-492">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="e1cf9-493">Es wurde ein Problem behoben, durch das Abstürze während der Office-Übergabesitzungen eliminiert, und es wurde die Zuverlässigkeit der Benutzeroberfläche erhöht.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-493">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="e1cf9-494">Dieser Fehler aktualisiert den Enhanced Configuration Service (ECS).</span><span class="sxs-lookup"><span data-stu-id="e1cf9-494">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="e1cf9-495">Das Aufrufen von diesem neueren Endpunkt aus hat eine höhere Erfolgsrate für den Abruf aus ECS.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-495">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-april-14"></a><span data-ttu-id="e1cf9-497">Version 2002: 14. April</span><span class="sxs-lookup"><span data-stu-id="e1cf9-497">Version 2002: April 14</span></span>
<span data-ttu-id="e1cf9-498">*Version 2002 (Build 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="e1cf9-498">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="e1cf9-499">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="e1cf9-499">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="e1cf9-500">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="e1cf9-500">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="e1cf9-501">Excel</span><span class="sxs-lookup"><span data-stu-id="e1cf9-501">Excel</span></span>

- <span data-ttu-id="e1cf9-502">**Geben Sie eine Formel ein, die mehrere Werte zurückgibt:** Geben Sie schnell eine Formel ein, die mehrere Werte zurückgibt, und diese werden automatisch in die benachbarten Zellen übertragen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-502">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="e1cf9-503">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-503">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="e1cf9-504">**Sechs leistungsfähige Funktionen:** Wir haben sechs neue Funktionen hinzugefügt, um Ihre Tabellenkalkulationen hochgradig zu optimieren: FILTERN, SORTIEREN, SORTIERENNACH, EINDEUTIG, SEQUENZ und ZUFALLSMATRIX.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-504">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="e1cf9-505">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-505">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="e1cf9-506">**Schau nach links, schau nach rechts... XVERWEIS ist da!:** Finden Sie mit XVERWEIS Zeile für Zeile alles, was Sie in einer Tabelle oder einem Bereich benötigen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-506">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  <span data-ttu-id="e1cf9-507">
  [Weitere Informationen](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span><span class="sxs-lookup"><span data-stu-id="e1cf9-507">[Learn more](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span></span>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="e1cf9-509">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="e1cf9-509">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="e1cf9-510">Excel</span><span class="sxs-lookup"><span data-stu-id="e1cf9-510">Excel</span></span>

- <span data-ttu-id="e1cf9-511">Excel stürzt in bestimmten Fällen ab, wenn eine in Word oder PowerPoint eingebettete Arbeitsmappe erneut geöffnet wird.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-511">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="e1cf9-512">Beim Speichern als CSV-Datei hat Excel in einigen Fällen alle Spalten in einer einzigen Spalte zusammengeführt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-512">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="e1cf9-513">Die Verwendung von Range.ClearContents für einen Bereich auf einem geschützten Blatt hat möglicherweise länger gedauert als erwartet.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-513">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="e1cf9-514">Es wurde ein Problem beim Skalieren von Text in Steuerelementen von Formularen beim Anzeigen in der Druckansicht behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-514">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="e1cf9-515">VBA-Makros, die mit dem Menüband interagieren, können möglicherweise mit ScreenUpdating unerwartet auf „Wahr“ festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-515">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="e1cf9-516">Es wurde ein Problem behoben, bei dem externe Links beim Füllen(abwärts füllen, übergreifend füllen usw.) nicht aktualisiert wurden, wenn das Quellbuch geschlossen war.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-516">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="e1cf9-517">Die Verwendung des VBA-Befehls Application.Evaluate funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-517">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="e1cf9-518">Es wurde ein Leistungsproblem beim Erstellen von Diagrammen aus Vorlagen behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-518">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="e1cf9-519">Outlook</span><span class="sxs-lookup"><span data-stu-id="e1cf9-519">Outlook</span></span>

- <span data-ttu-id="e1cf9-520">Es wurde ein Problem behoben, das dazu führte, dass die Kopfzeile einer Gruppe in einigen Szenarios unerwartet erweitert wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-520">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="e1cf9-521">Es wurde ein Problem behoben, bei dem es zu einem Absturz kam, wenn Benutzer bestimmte Ergebnisse ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-521">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="e1cf9-522">Es wurde ein Problem behoben, das gelegentlich zu einem Absturz führte, wenn Benutzer den X-Knopf ihrer Maus verwendeten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-522">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="e1cf9-523">Es wurde ein Problem behoben, das bewirkt hat, dass die Schaltfläche „In der Cloud speichern“ in den Tools für Anlagen fehlte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-523">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e1cf9-524">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e1cf9-524">PowerPoint</span></span>

- <span data-ttu-id="e1cf9-525">Verbessertes Szenario zum Kopieren und Einfügen: Das Kopieren der Form in eine PowerPoint-Folie und das Einfügen in eine andere Folie in einer Schleife schlägt möglicherweise mit Ausnahme fehl.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-525">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="e1cf9-526">Project</span><span class="sxs-lookup"><span data-stu-id="e1cf9-526">Project</span></span>

- <span data-ttu-id="e1cf9-527">Ein Problem wurde behoben, bei dem Project beim Speichern von Projekten, die mit älteren Project-Versionen erstellt wurden, möglicherweise abstürzt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-527">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="e1cf9-528">Ein Problem wurde behoben, bei dem das Ereignis „ProjectBeforeTaskChange“ nichts erkennt, wenn ein Vorgang über die Schaltfläche „Deaktivieren“ deaktiviert/aktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-528">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="e1cf9-529">Word</span><span class="sxs-lookup"><span data-stu-id="e1cf9-529">Word</span></span>

- <span data-ttu-id="e1cf9-530">Es wurde ein Problem behoben, das gelegentlich zu einem Absturz führte, wenn Benutzer den X-Knopf ihrer Maus verwendeten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-530">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="e1cf9-531">Es wurde ein Problem mit der Anpassung von Text in einer Tabelle behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-531">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="e1cf9-532">Ein Problem wurde behoben, damit eingefügte horizontale Linien nicht kürzer und zentriert sind.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-532">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-march-10"></a><span data-ttu-id="e1cf9-534">Version 2002: 10. März</span><span class="sxs-lookup"><span data-stu-id="e1cf9-534">Version 2002: March 10</span></span>
<span data-ttu-id="e1cf9-535">*Version 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="e1cf9-535">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="e1cf9-536">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="e1cf9-536">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a><span data-ttu-id="e1cf9-538">Featureupdates</span><span class="sxs-lookup"><span data-stu-id="e1cf9-538">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="e1cf9-539">Access</span><span class="sxs-lookup"><span data-stu-id="e1cf9-539">Access</span></span>

- <span data-ttu-id="e1cf9-540">**Schnelle Suche nach verknüpften Tabellen:** Unser neues Suchfeld macht die Suche nach verknüpften Tabellen zu einem Kinderspiel.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-540">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="e1cf9-541">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-541">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="e1cf9-542">Excel</span><span class="sxs-lookup"><span data-stu-id="e1cf9-542">Excel</span></span>

- <span data-ttu-id="e1cf9-543">**Mit \@Erwähnen andere auf sich aufmerksam machen:** Mithilfe von Erwähnungen in Kommentaren können Sie Kollegen informieren, wenn Sie deren Input benötigen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-543">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="e1cf9-544">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-544">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="e1cf9-545">**Finden Sie, wonach Sie suchen:** Suchen Sie Befehle, Personen, Dateien, Fotos, Webartikel und mehr.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-545">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="e1cf9-546">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-546">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="e1cf9-547">**Zeichnen Sie es auf:** Verleihen Sie Office-Shapes in Ihrer Arbeitsmappe ein ungezwungenes, von Hand gezeichnetes Aussehen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-547">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="e1cf9-548">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-548">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="e1cf9-549">**Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-549">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="e1cf9-550">**Keine Umleitung zum Browser mehr:** Sie legen fest, wie Links zu Office-Dokumenten geöffnet werden: im Browser oder in der App.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-550">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="e1cf9-551">**Konzentrieren Sie sich darauf, was noch erledigt werden muss:** Wählen Sie "Auflösen" aus, um Kommentare zu reduzieren und offene Punkte hervorzuheben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-551">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="e1cf9-552">**Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-552">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="e1cf9-553">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-553">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="e1cf9-554">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-554">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="e1cf9-555">\*\*Add-In „Datenschnellansicht“: \*\* erstellen Sie schnell Visio-Flussdiagramme aus Excel.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-555">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="e1cf9-556">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-556">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="e1cf9-557">**Schnell lesen und antworten:** Antworten Sie auf Kommentare und Erwähnungen direkt aus dem E-Mail-Bereich, ohne die Arbeitsmappe zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-557">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="e1cf9-558">**Statistiken für Ihre Arbeitsmappe abrufen:** Arbeitsmappenstatistiken bieten einen Überblick über den Inhalt einer Arbeitsmappe, um Ihnen das Erkunden des Inhalts zu erleichtern.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-558">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="e1cf9-559">**Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-559">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="e1cf9-560">Sie finden diese unter "Einfügen" > "Symbole".</span><span class="sxs-lookup"><span data-stu-id="e1cf9-560">Find them at Insert > Icons.</span></span> [<span data-ttu-id="e1cf9-561">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-561">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="e1cf9-562">Outlook</span><span class="sxs-lookup"><span data-stu-id="e1cf9-562">Outlook</span></span>

- <span data-ttu-id="e1cf9-563">**Verbinden Ihres LinkedIn-Netzwerks mit Outlook:** Stellen Sie eine sichere Verbindung zwischen Ihrem LinkedIn-Konto und Ihrem Microsoft-Konto her, um Informationen aus LinkedIn-Profilen direkt auf der Karte mit Ihren Kontakten anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-563">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="e1cf9-564">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-564">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="e1cf9-p156">**Alle Verschlüsselungsoptionen an einem zentralen Ort:** Gehen Sie einfach zu Optionen > Verschlüsseln, um auszuwählen, wie Ihre E-Mail-Nachricht gesichert wird. [Weitere Informationen](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="e1cf9-p156">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="e1cf9-567">**Das Menü „Link einfügen“ in Outlook fügt einen Link mit der vom Mandantenadministrator festgelegten Berechtigung ein:** Ein Link aus dem Link-Einfügen-MRU in Outlook fügte einen Link ein, der nur für diejenigen Benutzer funktionierte, die bereits eine Berechtigung besaßen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-567">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="e1cf9-568">Dies führte häufig zu E-Mail-Nachrichten zwischen Benutzern, die den Zugriff auf ein Dokument anforderten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-568">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="e1cf9-569">Wir haben diese Erfahrung aktualisiert, sodass der Link jetzt mit der vom Mandantenadministrator festgelegten Standardberechtigung eingefügt wird. Für MSIT ist dies "Organisation kann bearbeiten", sodass alle internen Benutzer, die einen auf diese Weise freigegebenen Link erhalten, darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-569">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="e1cf9-570">**Suchen bei Rechtschreibschwierigkeiten oder mit Tippfehlern:** Outlook wird auch dann finden, was Sie suchen, wenn Sie sich verschreiben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-570">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="e1cf9-571">**Phishing-E-Mails sind jetzt leicht zu erkennen:** Spam- und Phishing-E-Mails haben ein anderes Aussehen und Verhalten, sodass Sie sie leichter identifizieren und aus Ihrem Posteingang entfernen können.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-571">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="e1cf9-572">**Erweiterter Schutz gegen Angriffe:** Mit Office 365 Advanced Threat Protection sind Sie vor Angriffen durch Links in E-Mail-Betreffzeilen, angefügten Nachrichten, signierten Nachrichten, Netzwerkpfaden usw. geschützt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-572">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="e1cf9-573">**Müheloses Zeichnen und Signieren:** Kritzeln Sie über die Bilder, oder fügen Sie einen Zeichenbereich hinzu, um Ihren Gedanken als Freihandnotizen Ausdruck zu verleihen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-573">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="e1cf9-574">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-574">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="e1cf9-575">**Finden Sie relevante Nachrichten in Ihren Suchergebnissen:** Outlook analysiert Suchbegriffe und zeigt die wichtigsten E-Mail-Nachrichten am Anfang der Suchergebnisse an.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-575">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="e1cf9-576">Außerdem sehen Sie alle Ergebnisse sortiert nach Datum im Abschnitt „Top-Ergebnisse“.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-576">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="e1cf9-577">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-577">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="e1cf9-578">**Erhalten Sie Ortsvorschläge:** Beginnen Sie beim Planen von Terminen und Besprechungen mit der Eingabe im Feld „Ort“, so schlägt Outlook Räume, Adressen und andere zuletzt verwendete Orte vor.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-578">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="e1cf9-579">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-579">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="e1cf9-580">**Mehr Nachrichten am Bildschirm anzeigen:** Wählen Sie "Anzeigen" > Engere Abstände verwenden, um die Abstände zwischen den Nachrichten anzupassen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-580">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="e1cf9-581">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-581">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="e1cf9-582">**Sehen Sie Ihre Nachrichten in einem neuen Licht:** Verwenden Sie die Sonne/Mond-Schaltfläche, um im Lesebereich zwischen hellem und dunklem Hintergrund zu wechseln.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-582">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="e1cf9-583">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-583">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="e1cf9-584">**Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-584">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="e1cf9-585">Sie finden diese unter "Einfügen" > "Symbole".</span><span class="sxs-lookup"><span data-stu-id="e1cf9-585">Find them at Insert > Icons.</span></span> [<span data-ttu-id="e1cf9-586">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-586">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="e1cf9-587">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e1cf9-587">PowerPoint</span></span>

- <span data-ttu-id="e1cf9-588">**Schnelle Zusammenarbeit in Echtzeit in PowerPoint:** Schnelle Zusammenarbeit in Echtzeit in PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e1cf9-588">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="e1cf9-589">**Neue Tools zum Korrekturlesen:** Machen Sie sich keine Sorgen mehr über Ihre Texte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-589">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="e1cf9-590">PowerPoint bietet jetzt Grammatik- und Textvorschläge.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-590">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="e1cf9-591">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-591">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="e1cf9-592">**Live-Beschriftungen und -Untertitel:** die Worte des Referenten werden automatisch als Beschriftungen oder Untertitel in der von Ihnen gewünschten Sprache auf dem Bildschirm angezeigt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-592">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="e1cf9-593">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-593">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="e1cf9-p166">**Sie berechnen, wir formatieren:** Von Hand gezeichnete mathematische Ausdrücke werden in Standardzeichen umgewandelt. Wählen Sie einfach "Freihand in Gleichung" und Ihre handschriftlichen Notizen aus, um loszulegen. [Weitere Informationen](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="e1cf9-p166">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="e1cf9-597">**Finden Sie, wonach Sie suchen:** Verwenden Sie das Suchfeld, um Text, Befehle, Hilfe und mehr zu finden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-597">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="e1cf9-598">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-598">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="e1cf9-599">**Suchen und Beheben von fehlenden Folientiteln:** Folientitel verleihen Ihrem Pitch mehr Nachdruck und machen Ihre Folien für Benutzer mit unterschiedlichen Fähigkeiten zugänglich.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-599">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="e1cf9-600">Die Barrierefreiheitsprüfung zeigt Ihnen, wo Titel fehlen, damit Sie diese schnell hinzufügen können.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-600">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="e1cf9-601">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-601">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="e1cf9-602">**Zeichnen Sie es auf:** Verleihen Sie Office-Shapes in Ihrer Präsentation ein ungezwungenes, von Hand gezeichnetes Aussehen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-602">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="e1cf9-603">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-603">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="e1cf9-604">**Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-604">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="e1cf9-605">**Keine Umleitung zum Browser mehr:** Sie legen fest, wie Links zu Office-Dokumenten geöffnet werden: im Browser oder in der App.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-605">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="e1cf9-606">**Speichern einer Illustration als SVG:** Speichern Sie ein Diagramm, eine Form oder eine andere Abbildung als skalierbare Vektorgrafik, deren Größe ohne Verlust der Bildqualität geändert werden kann.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-606">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="e1cf9-607">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-607">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="e1cf9-608">**Drucken von Foliennummern auf Handzetteln:** Foliennummern werden automatisch in Ihre Handzettel integriert.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-608">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="e1cf9-609">Sie können diese Funktion an- oder abschalten, wie es Ihnen beliebt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-609">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="e1cf9-610">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-610">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="e1cf9-611">**Wiedergabe von animierten Freihandzeichnungen:** Wenn Sie Freihandeingaben auf Ihren Folien vornehmen, können Sie auf diese Freihandeingaben Replay-Animationen anwenden, um den eigentlichen Zeichenvorgang während der Bildschirmpräsentation wiederzugeben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-611">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="e1cf9-612">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-612">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="e1cf9-613">**Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-613">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="e1cf9-614">**Optimieren Sie Ihre Präsentation für alle:** Die Barrierefreiheitsprüfung hilft Ihnen beim Anordnen von Objekten auf Ihren Folien, indem sie die Sprachausgabe berücksichtigt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-614">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="e1cf9-615">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-615">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="e1cf9-616">**Eine sicherere Video-Umgebung:** Security-Verbesserungen bedeuten für Sie eine sicherere Online-Video-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-616">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="e1cf9-617">**Warum neu erstellen, wenn Sie etwas wiederverwenden können?** Sparen Sie Zeit, indem Sie Folien, die Sie erstellt haben oder die andere für Sie freigegeben haben, erneut verwenden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-617">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="e1cf9-618">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-618">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="e1cf9-619">**Ändern der handschriftlichen Freihandeingabe in Formen, Text oder Mathematik in PowerPoint für Office 365:** Wechseln Sie mit wenigen Strichen von der Freihandeingabe zu Office-Formen, Text oder einem mathematischen Ausdruck.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-619">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="e1cf9-620">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-620">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="e1cf9-621">**Erstellen Sie eine hervorragende Folie:** Konvertieren Sie Ihre Freihandeingaben in Standardformen und -text, und lassen Sie sich dann von PowerPoint-Designer intelligente Folienentwurfsideen anzeigen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-621">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="e1cf9-622">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-622">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="e1cf9-623">**Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-623">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="e1cf9-624">Sie finden diese unter "Einfügen" > "Symbole".</span><span class="sxs-lookup"><span data-stu-id="e1cf9-624">Find them at Insert > Icons.</span></span> [<span data-ttu-id="e1cf9-625">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-625">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="e1cf9-626">Visio</span><span class="sxs-lookup"><span data-stu-id="e1cf9-626">Visio</span></span>

- <span data-ttu-id="e1cf9-627">**Zurück zum Tatort:** Verwenden Sie die neuen Schablonen "Beweismittel", "Drinnen" und "Draußen" der Vorlage "Tatortermittlung", um Tatorte im Detail nachzustellen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-627">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="e1cf9-628">\*\* Erstellen Sie ansprechende Visio-Diagramme in Excel:\*\* Erstellen Sie ein Flussdiagramm oder ein Organigramm durch Einfügen von Daten in ein Arbeitsblatt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-628">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="e1cf9-629">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-629">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="e1cf9-630">Word</span><span class="sxs-lookup"><span data-stu-id="e1cf9-630">Word</span></span>

- <span data-ttu-id="e1cf9-631">**Lebenslauf-Editor-Verknüpfung mit dem LinkedIn-Lebenslauf-Assistent:** Der Lebenslauf-Editor bietet eine Auswahl an Grammatik- und Stilprüfungen, die speziell auf Lebensläufe zugeschnitten sind, um Ihr Schreiben präziser und professioneller zu gestalten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-631">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="e1cf9-632">**Es wurde ein Problem mit beschädigten Dokumenten behoben, das durch das Zusammenführen von 3D-Objekten verursacht wurde.** Es wurde ein Problem mit beschädigten Dokumenten behoben, das durch das Zusammenführen von 3D-Objekten verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-632">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="e1cf9-633">**Finden Sie, wonach Sie suchen:** Verwenden Sie das Suchfeld, um Text, Befehle, Hilfe und mehr zu finden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-633">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="e1cf9-634">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-634">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="e1cf9-635">**Zusammenarbeit in lebendigen Farben:** Kommentare und Änderungen sind nach Verfasser farblich gekennzeichnet, sodass Sie die einzelnen Mitwirkenden leichter unterscheiden können.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-635">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="e1cf9-636">**Makrofähige Dokumente gemeinsam bearbeiten:** Speichern Sie Ihre Dokumentdateien auf OneDrive for Business, und bearbeiten Sie sie mit anderen in Echtzeit.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-636">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="e1cf9-637">**Verbesserungen bei der gemeinsamen Dokumenterstellung**: verbesserte Leistung von Word bei der gemeinsamen Dokumenterstellung mit nachverfolgbaren Änderungen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-637">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="e1cf9-638">**Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-638">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="e1cf9-639">Sie finden diese unter "Einfügen" > "Symbole".</span><span class="sxs-lookup"><span data-stu-id="e1cf9-639">Find them at Insert > Icons.</span></span> [<span data-ttu-id="e1cf9-640">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-640">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="e1cf9-641">**Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-641">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="e1cf9-642">**Zeichnen Sie es auf:** Verleihen Sie Office-Shapes in Ihrem Dokument ein ungezwungenes, von Hand gezeichnetes Aussehen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-642">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="e1cf9-643">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-643">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="e1cf9-644">**Präzises Löschen:** Wählen Sie aus zwei Radierergrößen aus, um kleine Unvollkommenheiten zu beheben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-644">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="e1cf9-645">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-645">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="e1cf9-646">**Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-646">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="e1cf9-647">**Keine Umleitung zum Browser mehr:** Sie legen fest, wie Links zu Office-Dokumenten geöffnet werden: im Browser oder in der App.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-647">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="e1cf9-648">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-648">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="e1cf9-649">**Verbesserungen bei der gemeinsamen Dokumenterstellung:** Verbesserte Zuverlässigkeit bei der gemeinsamen Dokumenterstellung.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-649">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="e1cf9-650">**Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-650">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="e1cf9-651">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-651">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="e1cf9-652">**Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-652">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="e1cf9-653">**Eine sicherere Video-Umgebung:** Security-Verbesserungen bedeuten für Sie eine sicherere Online-Video-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-653">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="e1cf9-654">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="e1cf9-654">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="e1cf9-657">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="e1cf9-657">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="e1cf9-658">Zugriff</span><span class="sxs-lookup"><span data-stu-id="e1cf9-658">Access</span></span>

- <span data-ttu-id="e1cf9-659">Mit diesem Update wird ein Problem in Microsoft Access behoben, das den Fehler "Abfrage ist beschädigt" verursachen kann, wenn eine Aktualisierungsabfrage ausgeführt oder eine UPDATE-Anweisung in SQL verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-659">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="e1cf9-660">Dieses Update behebt ein Problem, das dazu führen kann, dass Microsoft Access eine Identitätsspalte in einer verknüpften SQL-Server-Tabelle nicht identifiziert, was dazu führen kann, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-660">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="e1cf9-661">Dieses Update behebt ein Problem bei der Verwendung von ADODB.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-661">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="e1cf9-662">Das Recorder-Objekt im VB-Code meldet möglicherweise einen Fehler falsch.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-662">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="e1cf9-663">Access-Vorlagen sollten nicht länger dazu führen, dass Anhangsspalten in einer Datenbank fehlschlagen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-663">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="e1cf9-664">Nachdem Sie eine Vorlage instanziiert haben, sollten Sie nun in der Lage sein, Ihrer Datenbank ein Anhangsfeld hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-664">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="e1cf9-665">Excel</span><span class="sxs-lookup"><span data-stu-id="e1cf9-665">Excel</span></span>

- <span data-ttu-id="e1cf9-666">Es wurde ein Problem behoben, aufgrund dessen bei Benutzern Abstürze beim Umbenennen einer Signatur auftraten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-666">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="e1cf9-667">Diese Änderung umgeht ein Problem mit bestimmten Intel-Grafiktreibern durch Verwendung des Softwarerenderings.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-667">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="e1cf9-668">Es wurde ein Problem behoben, durch das bei einigen Benutzern Abstürze auftraten, wenn Text in Spalten mit Zellen mit einem übergelaufenem Array konvertiert wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-668">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="e1cf9-669">Dieses Update behebt ein Problem, das dazu führte, dass die Bearbeitungsleiste Text in einer anderen Schriftart als erwartet anzeigte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-669">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="e1cf9-670">Die Funktion "Text in Spalte" funktioniert bei einigen Gebietsschemas möglicherweise nicht.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-670">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="e1cf9-671">Beim Zugriff auf einen verborgenen benannten Bereich kann ein Fehler auftreten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-671">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="e1cf9-672">Beim Speichern von Änderungen bei der Verwendung einiger nicht englischer Zeichengruppen tritt möglicherweise ein Fehler auf.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-672">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="e1cf9-673">Wir haben ein Problem gelöst, durch das das Auswählen einer Zelle nach dem Scrollen dazu führen konnte, dass die falsche Zelle ausgewählt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-673">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="e1cf9-674">In Excel kann ein Problem auftreten, durch das das Bearbeiten einer geschützten Datei von einer nicht vertrauenswürdigen Netzwerkfreigabe zu einem Fehler in Excel führt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-674">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="e1cf9-675">Die Funktion "Text in Spalte" funktioniert bei einigen Lokalisierungen möglicherweise nicht.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-675">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="e1cf9-676">Beim Zugriff auf einen verborgenen benannten Bereich kann ein Fehler auftreten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-676">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="e1cf9-677">Beim Speichern von Änderungen bei der Verwendung einiger nicht englischer Zeichengruppen tritt möglicherweise ein Fehler auf.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-677">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="e1cf9-678">Es wurde ein Problem behoben, das bei einigen Benutzern mit verknüpften und eingebetteten Objekten (OLE) auftrat.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-678">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="e1cf9-679">Das Kontextmenü für PivotCharts wurde korrigiert, um die Option "Details anzeigen" zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-679">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="e1cf9-680">Es wurde ein Problem behoben, das bei der Suche nach zuletzt verwendeten Dateien zu einem Absturz geführt hat, wenn keine Arbeitsmappe geöffnet ist.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-680">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="e1cf9-681">Es wurde ein Problem behoben, durch das einigen Benutzern mehrere Popupfenster angezeigt wurden, wenn externe Links in der Arbeitsmappe vorhanden waren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-681">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="e1cf9-682">Es wurde ein Problem behoben, bei dem Kommentarbefehle im Kontextmenü nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-682">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="e1cf9-683">Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-683">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="e1cf9-684">Ein Problem wurde behoben, bei dem CUBEWERT-Funktionen manchmal ein falsches Ergebnis zurückgaben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-684">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="e1cf9-685">Outlook</span><span class="sxs-lookup"><span data-stu-id="e1cf9-685">Outlook</span></span>

- <span data-ttu-id="e1cf9-686">Es wurde ein Problem behoben, durch das die Such-Feedback-Umgebung zum Hängen gebracht wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-686">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="e1cf9-687">Es wurde ein Problem behoben, das dazu führte, dass Benutzer in Outlook beim Abrufen von Cloudeinstellungen hängen bleiben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-687">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="e1cf9-688">Es wurde ein Problem behoben, das dazu führte, dass das Suchfeld im Modus mit hohem DPI-Wert nicht korrekt ausgerichtet war.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-688">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="e1cf9-689">Ein Problem wurde behoben, durch das Benutzer einen Speicherverlust im Outlook-Prozess beobachten konnten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-689">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="e1cf9-690">Es wurde ein Problem behoben, durch das Benutzern unter bestimmten Umständen E-Mails angezeigt werden, die an eine Adresse gesendet wurden, die nicht mit der angezeigten SMTP-Adresse übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-690">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="e1cf9-691">Diese Änderung stellt die Fähigkeit wieder her, mehrzeilige Betreffzeilen im Nachrichtenkopf anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-691">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="e1cf9-692">Es wurde ein Problem behoben, durch das verhindert werden konnte, dass Dateien an einem WebDAV-Speicherort gespeichert wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-692">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="e1cf9-693">Es wurde ein Problem mit der Auswahl des SMIME-Algorithmus behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-693">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="e1cf9-694">Ein Problem wurde behoben, durch das Anwendungen von Drittanbietern keine E-Mail-Nachrichten mehr senden konnten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-694">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="e1cf9-695">Es wurde ein Problem behoben, das bewirkt hat, dass Benutzer ein leeres Meldungsfeld mit einer "OK"-Schaltfläche angezeigt bekamen, wenn Sie versuchten, den Support über den Kontext der Kontoerstellung zu kontaktieren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-695">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="e1cf9-696">Ein Problem wurde behoben, das während der Profilerstellung ein Absturz verursachte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-696">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="e1cf9-697">Ein Problem wurde behoben, das dazu führte, dass Outlook unerwartet alle E-Mails synchronisierte, selbst wenn der Synchronisierungsschieberegler auf eine kleinere Einstellung eingestellt ist.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-697">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="e1cf9-698">Ein Problem wurde behoben, das dazu führte, dass für Benutzer mit dem schwarzen Design die Dropdownliste „Von“ als weißer Text auf weißem Hintergrund angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-698">Addressed an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="e1cf9-699">Es wurde ein Problem behoben, bei dem es durch das Abbrechen der Kontoeinrichtung einen Absturz gab.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-699">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="e1cf9-700">Es wurde ein Problem behoben, aufgrund dessen bei Benutzern Abstürze beim Umbenennen einer Signatur auftraten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-700">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="e1cf9-701">Es wurde ein Problem behoben, durch das die Option zum Deaktivieren der Hervorhebung markierter Elemente in einigen Szenarien nicht berücksichtigt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-701">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="e1cf9-702">Es wurde ein Problem behoben, durch das Benutzern eine beim Öffnen des Dialogfelds "Regeln" die folgende Meldung "Die Regeln auf diesem Computer stimmen nicht mit den Regeln in Microsoft Exchange überein" angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-702">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="e1cf9-703">Es wurde ein Problem behoben, bei dem beim Angeben einer ungültigen Absenderadresse ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-703">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="e1cf9-704">Es wurde ein Problem behoben, das einen Speicherverlust bei sehr langen Outlook-Sitzungen verursachte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-704">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="e1cf9-705">Ein Problem wurde behoben, das zu einem Absturz führen könnte, wenn dasselbe Element in mehreren Fenstern angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-705">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="e1cf9-706">Es wurde ein Problem behoben, durch das Benutzer mit einer spürbaren Verzögerung beim Interagieren mit ihren Postfachordnern über Tastenkombinationen konfrontiert waren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-706">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="e1cf9-707">Ein Problem wurde behoben, durch das Benutzer einige Instanzen von wiederkehrenden Kalenderelementen nicht öffnen konnten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-707">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="e1cf9-708">Es wurde ein Problem behoben, das bei Benutzern mit Postfächern auf Exchange 2010-Servern zu Problemen beim Hinzufügen von Anlagen zu Kalendereinträgen führte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-708">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="e1cf9-709">Es wurde ein Problem behoben, durch das Benutzer Probleme beim Beantworten digital signierter Nachrichten hatten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-709">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="e1cf9-710">Es wurde ein Problem behoben, durch das das Feld "Ort" in Besprechungen unerwartet aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-710">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="e1cf9-711">Es wurde ein Problem behoben, das dazu führte, dass Kommas im Ortsfeld einer Besprechung in Semikolons umgewandelt wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-711">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="e1cf9-712">Es wurde ein Problem behoben, bei dem der Standort einer Besprechung unerwartet nach dem Löschen wieder der Besprechung hinzugefügt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-712">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="e1cf9-713">Es wurden Probleme im Zusammenhang mit in der brasilianischen Zeitzone festgelegten Sitzungen und Terminen behoben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-713">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="e1cf9-714">Ein Problem wurde behoben, durch das beim Drücken der Taste „S“ nach dem Schließen der Barrierefreiheitsprüfung unerwartet E-Mails gesendet wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-714">Addressed an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="e1cf9-715">Hiermit wird die Blockierungslogik für Anlagen in Outlook aktualisiert, um auch Python-Anlagen zu blockieren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-715">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="e1cf9-716">Ein Problem wurde behoben, durch das Web-Add-Ins auf von Digital Rights Management verwaltete Nachrichten zugreifen konnten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-716">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="e1cf9-717">Ein Problem wurde behoben, das während der Profilerstellung ein Absturz verursachte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-717">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="e1cf9-718">Es wurde ein Problem behoben, aufgrund dessen bei Benutzern Abstürze beim Umbenennen einer Signatur auftraten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-718">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e1cf9-719">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e1cf9-719">PowerPoint</span></span>

- <span data-ttu-id="e1cf9-720">Ein Problem mit der Shape.Paste-Methode wurde behoben: Wenn der Benutzer die Form mit der Shape.Paste-Methode kopiert und einfügt, wird die Auswahl in die eingefügte Form geändert.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-720">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="e1cf9-721">Es wurde ein Problem behoben, das bei der Verwendung des Kontextmenüs in älteren PPT-Kommentaren zu einem Absturz führen könnte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-721">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="e1cf9-722">Project</span><span class="sxs-lookup"><span data-stu-id="e1cf9-722">Project</span></span>

- <span data-ttu-id="e1cf9-723">Ein Problem wurde identifiziert, bei dem Benutzer beim Öffnen eines schreibgeschützten Projekts möglicherweise mehrere Meldungen erhielten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-723">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="e1cf9-724">Es wurde ein Problem behoben, bei dem 100% Aufgaben vom Typ "feste Dauer" fälschlicherweise zu weniger als 100% erledigt wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-724">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="e1cf9-725">Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-725">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="e1cf9-726">Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-726">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="e1cf9-727">Word</span><span class="sxs-lookup"><span data-stu-id="e1cf9-727">Word</span></span>

- <span data-ttu-id="e1cf9-728">Ein Problem wurde behoben, bei dem das Speichern einer vorhandenen Datei in einigen Fällen das Dialogfeld "Speichern unter" aufruft und die Datei nie wirklich gespeichert wird.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-728">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="e1cf9-729">Im Organizer für Bausteine könnte eine ungültige Warnung angezeigt werden: “Sie haben modifizierte Formen, Bausteine“.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-729">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="e1cf9-730">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="e1cf9-730">Office Suite</span></span>

- <span data-ttu-id="e1cf9-731">Diese Änderung betrifft die langsame Darstellung einiger Streudiagramme mit Markierungen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-731">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="e1cf9-732">Diese Änderung behebt gemeldete Probleme mit Grafikadaptern, die die integrierte Intel-GPU nutzen.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-732">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="e1cf9-733">Ein Fehler in der Einstellung des Stichtags für ODT- und GPO-Updates wurde behoben, bei dem der relative Stichtag nur beim ersten Festlegen funktionierte. Der Fix aktiviert den relativen Stichtag für spätere Updates.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-733">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="e1cf9-734">Es wurde ein Problem behoben, bei dem Office-Aktualisierungen möglicherweise unerwartet Dateien aus dem Office CDN anstelle der beabsichtigten Quelle heruntergeladen haben, beispielsweise eine lokale oder Netzwerkfreigabe oder einen vom Configuration Manager bereitgestellten Speicherort.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-734">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="e1cf9-735">Ein Problem wurde behoben, das dazu führte, dass beim Öffnen mehrerer Dokumente in Word/Excel/PowerPoint aus derselben SharePoint-Bibliothek lediglich das erste geöffnete Dokument auf Richtlinienkonformität gescannt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-735">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (BUGDETAILS NICHT AM INHALTSENDE ENTFERNEN)

## <a name="version-1908-february-11"></a><span data-ttu-id="e1cf9-737">Version 1908: 11. Februar</span><span class="sxs-lookup"><span data-stu-id="e1cf9-737">Version 1908: February 11</span></span>
<span data-ttu-id="e1cf9-738">*Version 1908 (Build 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="e1cf9-738">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="e1cf9-739">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="e1cf9-739">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="e1cf9-741">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="e1cf9-741">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="e1cf9-742">Excel</span><span class="sxs-lookup"><span data-stu-id="e1cf9-742">Excel</span></span>

- <span data-ttu-id="e1cf9-743">Dieses Update behebt ein Problem, das dazu führte, dass ein Fehler auftrat, wenn VBA zum Hinzufügen eines Bildes zur Kopf-/Fußzeile eines Diagramms verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-743">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="e1cf9-744">Es wurde ein Problem behoben, bei dem der Rand eines Gruppenfeld-Steuerelements in der Druckvorschau oder beim Drucken nicht sichtbar war.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-744">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="e1cf9-745">Nutzer können beim Speichern von Änderungen auf einen Fehler stoßen, wenn sie manche nicht englische Zeichensätze verwenden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-745">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="e1cf9-746">Es wurde ein Problem behoben, durch das die Dateigröße von Bildern in Diagrammkopfzeilen beim Speichern der Arbeitsmappe mit dem Diagramm zunahm.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-746">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="e1cf9-747">Es wurde ein Problem behoben, das zur Beschädigung von DBCS-Zeichen in Büchern mit Querverweisen führte, indem die Auswahlbereiche mit dem Buch mit Querverweisen synchronisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-747">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="e1cf9-748">Es wurde ein Problem behoben, das dazu führen konnte, dass Kontrollkästchen bei Verwendung der automatischen Anpassung zum Anpassen der Zeilenhöhe verkleinert wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-748">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="e1cf9-749">Outlook</span><span class="sxs-lookup"><span data-stu-id="e1cf9-749">Outlook</span></span>

- <span data-ttu-id="e1cf9-750">Es wurde ein Problem behoben, bei dem beim Angeben einer ungültigen Absenderadresse ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-750">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="e1cf9-751">Es wurde ein Problem behoben, bei dem Nutzer bei der Verarbeitung von Konfliktnachrichten Synchronisierungsfehler hatten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-751">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="e1cf9-752">Es wurde ein Problem behoben, bei dem Nutzer beim Starten von Outlook beim Laden des Profils auf dem Bildschirm "Laden von Profilen" hängen blieben.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-752">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="e1cf9-753">Es wurde ein Problem behoben, durch das Nutzer beim Ändern von Ansichten zeitweise Abstürze sehen konnten.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-753">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="e1cf9-754">Es wurde ein Problem behoben, bei dem beim Anzeigen von mehr als 30 Kalendern in einer Citrix-Umgebung ein Absturz verursacht wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-754">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="e1cf9-755">[Hier](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) ist die einzelne KB, in der dies für frühere Versionen dokumentiert wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-755">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="e1cf9-756">Behebt ein Problem, bei dem Nutzer Probleme mit der Synchronisierung freigegebener Kalenderordner mit dem OST hatten, was zu Berechtigungsfehlern führte, wenn sie versuchten, mit diesen Ordnern zu interagieren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-756">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="e1cf9-757">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e1cf9-757">PowerPoint</span></span>

- <span data-ttu-id="e1cf9-758">Verbessertes Szenario zum Kopieren und Einfügen Das Kopieren der Form in eine PowerPoint-Folie und das Einfügen in eine andere Folie in einer Schleife schlägt möglicherweise mit Ausnahme fehl.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-758">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="e1cf9-759">Es wurde ein Problem behoben, das zu einer langsameren Leistung zwischen Nutzern, die zusammenarbeiten, führte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-759">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="e1cf9-760">Es wurde ein Problem behoben, das auftreten konnte, wenn eine Datei, die inkrementell geöffnet wurde, eine Folie mit mehr als einem eingebetteten Mediendatenstrom enthielt.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-760">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="e1cf9-761">Wir haben ein Problem behoben, bei dem beim ersten Start von PowerPoint möglicherweise keine Sicherheitswarnmeldung für nicht vertrauenswürdige Add-Ins angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-761">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="e1cf9-762">Project</span><span class="sxs-lookup"><span data-stu-id="e1cf9-762">Project</span></span>

- <span data-ttu-id="e1cf9-763">Es wurde ein Problem behoben, bei dem die tatsächliche Arbeit zwischen Arbeitszeittabelle und Projektplan unterschiedlich sein kann, da Ressourcenkalender nicht aktualisiert werden, wenn sich der Basiskalender ändert.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-763">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="e1cf9-764">Word</span><span class="sxs-lookup"><span data-stu-id="e1cf9-764">Word</span></span>

- <span data-ttu-id="e1cf9-765">Ein Absturz in Word wurde behoben, indem es von einer veralteten API entfernt wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-765">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="e1cf9-766">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="e1cf9-766">Office Suite</span></span>

- <span data-ttu-id="e1cf9-767">Diese Änderung behebt das korrekte Rendern von Bildern nach dem Öffnen einer beschädigten Datei.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-767">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1908-january-14"></a><span data-ttu-id="e1cf9-769">Version 1908: 14. Januar</span><span class="sxs-lookup"><span data-stu-id="e1cf9-769">Version 1908: January 14</span></span>
<span data-ttu-id="e1cf9-770">*Version 1908 (Build 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="e1cf9-770">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="e1cf9-771">Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt</span><span class="sxs-lookup"><span data-stu-id="e1cf9-771">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a><span data-ttu-id="e1cf9-773">Gelöste Probleme</span><span class="sxs-lookup"><span data-stu-id="e1cf9-773">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="e1cf9-774">Excel</span><span class="sxs-lookup"><span data-stu-id="e1cf9-774">Excel</span></span>

- <span data-ttu-id="e1cf9-775">Die Niederländische Tastenkombination für Dokumenttitel wurde in Alt-G geändert.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-775">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="e1cf9-776">Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-776">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="e1cf9-777">Es gab ein Problem, bei dem Sie keine Elemente aus dem Kombinationsfeld eines WPF-Formulars (Windows Presentation Foundation) auswählen konnten, das von einem Add-n geöffnet wurde.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-777">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="e1cf9-778">Outlook</span><span class="sxs-lookup"><span data-stu-id="e1cf9-778">Outlook</span></span>

- <span data-ttu-id="e1cf9-779">Es wurde ein Problem behoben, durch das Benutzer mit einer spürbaren Verzögerung beim Interagieren mit ihren Postfachordnern über Tastenkombinationen konfrontiert waren.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-779">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="e1cf9-780">Es wurde ein Problem behoben, bei dem Richtlinientipps bei Verwendung eines alternativen Absenders nicht angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-780">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="e1cf9-781">Es wurde ein Problem behoben, das bei der Aktualisierung von Anwesenheitsinformationen zu zeitweiligen Abstürzen führte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-781">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="e1cf9-782">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e1cf9-782">PowerPoint</span></span>

- <span data-ttu-id="e1cf9-783">Wir haben ein Problem behoben, bei dem beim Kopieren einer Folie von einer Präsentation in eine andere möglicherweise doppelte Master erstellt wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-783">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="e1cf9-784">Bei Dateien mit neuen modernen Kommentaren wird eine gelbe Warnung angezeigt, wenn sie in einer nicht unterstützten Version geöffnet werden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-784">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="e1cf9-785">Office-Suite</span><span class="sxs-lookup"><span data-stu-id="e1cf9-785">Office Suite</span></span>

- <span data-ttu-id="e1cf9-786">Es wurde ein Problem behoben, bei dem Office-Update-Nachrichten in einer anderen Sprache als erwartet angezeigt wurden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-786">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="e1cf9-787">In Zukunft entsprechen Office-Update-Nachrichten ordnungsgemäß der Windows-Anzeigesprache.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-787">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="e1cf9-788">Es wurde ein Problem behoben, bei dem ein Update in bestimmten Fällen nicht installiert wurde, wenn der Benutzer kein Administrator ist und das Systemkonto keine Netzwerkverbindung hatte.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-788">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

> [!NOTE]
> <span data-ttu-id="e1cf9-790">Wenn Sie Hilfe bei einem Problem mit der Nutzung von Office benötigen, empfehlen wir, dass Sie Ihre Frage im [Microsoft Answers-Forum](https://answers.microsoft.com/) oder in der [Tech-Community](https://techcommunity.microsoft.com/) veröffentlichen, oder Sie können sich an den [Support](https://support.microsoft.com/contactus) wenden.</span><span class="sxs-lookup"><span data-stu-id="e1cf9-790">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (ADMIN CENTER-METADATENINHALT NICHT ÄNDERN BEGINN)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-october-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20408|version-2008-september-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (ADMIN CENTER-METADATENINHALT NICHT ÄNDERN ENDE)

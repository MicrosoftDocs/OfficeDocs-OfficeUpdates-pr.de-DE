---
title: Archivierte Anmerkungen zur Version für Releases im halbjährlichen Kanal (gezielt) im Jahr 2019
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt IT-Experten Anmerkungen zur Version für Releases im halbjährlichen Kanal (gezielt) für Office 365 ProPlus im Jahr 2019 zur Verfügung.
ms.openlocfilehash: 72e2402dff445b9ec4b03c7241f93ee85b16bee2
ms.sourcegitcommit: 596cdb3423140df0324a952157fbc39ebedc12b9
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 05/07/2021
ms.locfileid: "52278122"
---
# <a name="archived-release-notes-for-semi-annual-enterprise-channel-preview"></a>Archivierte Versionshinweise des halbjährlichen Enterprise-Kanals (Vorschau)

Diese Versionshinweise enthalten Informationen zu neuen Features und nicht sicherheitsrelevante Updates, die in den halbjährlichen Enterprise-Kanalupdates (Vorschau) für Office 365 ProPlus, Visio Pro für Office 365, Project Online Desktop Client und Office 365 Business enthalten sind.

> [!NOTE]
> - Features (und häufig auch Fixes) werden häufig über einen Zeitraum in den halbjährlichen Enterprise-Kanal (Vorschau) eingeführt. Wenn etwas, das nachstehend beschrieben ist, nicht sofort angezeigt wird, wird es in Kürze verfügbar sein. [Weitere Informationen](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)


## <a name="version-2008-december-08"></a>Version 2008: 08. Dezember
*Version 2008 (Build 13127.20910)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Zugriff

- Es wurde ein Fehler beim Versuch, den ODBC-DSN-Builder zu verwenden, behoben


### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem Pivot-Tabellen nicht bearbeitet und Arbeitsmappen nicht gespeichert werden konnten, wenn sie aus dem Projektplan exportiert wurden.


- Es wurde ein Problem behoben, bei dem in einigen Fällen mehrere Nachrichtenbalken angezeigt wurden, wenn eine Datei im schreibgeschützten Modus geöffnet wurde.


- Es wurde ein Problem behoben, bei dem Gliederungszwischensummen nicht mehr funktionieren konnten, wenn es viele doppelte Spaltenüberschriftenwerte gab.


- Es wurde ein Problem behoben, bei dem Excel nicht mehr funktionierte, wenn während einer Multithread-Neuberechnung eine Aktualisierung des Gruppenrichtlinienobjekts (z. B. über Aktualisieren der Remote-Gruppenrichtlinie) durchgeführt wurde.


- Es wurde ein Problem behoben, bei dem Excel nicht mehr funktioniert, wenn Benutzer die Zwischensummenfunktion für mehr als 255 Spalten verwenden.


- Verbesserte das Text-Kerning in PowerPoint, wenn Inhalte aus Excel kopiert und mit der Option "Einbetten" in PowerPoint eingefügt werden.


- Es wurde ein Problem behoben, das den Wechsel von der Tabellenvorschau und dem Abfrage-Editor in PowerPivot verhinderte.


- Es wurde ein Problem behoben, bei dem ein Benutzer eine atomsvc-Datei (UTF8 + BOM) nicht direkt aus SharePoint öffnen konnte.


- Es wurde ein Problem behoben, bei dem Power Pivot jetzt erfolgreich das Tabulator-Trennzeichen erkennt.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, aufgrund dessen das Feld "to:" beim Senden eines Statusberichts zu einem Vorgang leer war.


- Es wurde ein Problem behoben, aufgrund dessen das Ereignis "MailItem.BeforeAttachmentAdd" abgebrochen wurde.


- Es wurde ein Problem behoben, aufgrund dessen einige Benutzer die Anwendung unerwartet schließen mussten, wenn sie Outlook-E-Mails aus anderen Anwendungen als Outlook versandten.


- Es wurde ein Problem behoben, aufgrund dessen Benutzer beim Verschieben mehrerer Poststücke zwischen Ordnern im Online-Modus eine verminderte Leistung erfahren haben.


- Wir haben einen regkey hinzugefügt, mit dem Kunden die Dateizeiteinbeziehung für Anhänge in IDataObject-Operationen (d. h. Drag Drop, Zwischenablage) deaktivieren können.  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes sind ausgeschlossen  1 = (Standard) filetimes sind eingeschlossen


- Es wurde ein Problem behoben, das dazu führte, dass Inline-Bilder verschwinden, wenn auf eine Nachricht mit einer Schutzbezeichnung von Azure Information Protection geantwortet wird.


- Es wurde ein Problem behoben, aufgrund dessen der Benutzername beim Senden einer Azure Protected Voicemail als Telefonnummer angezeigt wurde, so dass Outlook Desktop-Benutzer keine Voicemails von externen Benutzern öffnen konnten.


- Es wurde ein Problem behoben, bei dem das Einrichten der OME-Konfiguration das Hinzufügen einer fremden Anlage zum E-Mail-Element zur Folge hatte, wodurch Outlook gezwungen wurde, die Nachricht zu verschlüsseln, obwohl die Option DecryptAttachmentsForEncryptOnly auf der Dienstseite eingerichtet war.


### <a name="powerpoint"></a>PowerPoint

- Ein Problem wurde behoben, bei dem ein verknüpftes Excel-Diagramm fälschlicherweise in eine Excel-Tabelle geändert wurde, wenn der Benutzer den Quellpfad in den lokalen OneDrive-Ordner änderte.


- Es wurde ein Problem behoben, aufgrund dessen die Funktion "Willkommen zurück! Dort weitermachen, wo Sie im Büro aufgehört haben" in PowerPoint nicht funktionierte.


### <a name="visio"></a>Visio

- Ein Problem wurde behoben, bei dem Benutzer in Visio für Office 365 gerade Linien mithilfe von Konnektoren für benutzerdefinierte Visio-Schablonen und eingebaute Vorlagen erstellen können.


### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem lange Links beim Speichern eines Dokuments im HTML-Format nicht umgebrochen wurden.


- Es wurde ein Problem behoben, aufgrund dessen wenn Sie auf einen übergeordneten Kommentar antworten, der unbekannte Erweiterungen in einer Erweiterungsliste hat, die Antwort die gleichen Erweiterungen erhält.


- Es wurde ein Problem in Outlook mit auf "Nicht weiterleiten" festgelegten Nachrichten behoben.


### <a name="office-suite"></a>Office-Suite

- Behebt ein Problem, das Benutzer daran hinderte, SPO-Listen zu importieren, wenn ADAL deaktiviert war.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-november-10"></a>Version 2008: 10 November
*Version 2008 (Build 13127.20760)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme

### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, das bewirkte, dass nach dem Laden einer Arbeitsmappe bestimmte Funktionen falsche Ergebnisse aufwiesen.


- Es wurde ein Problem wurde behoben, bei dem die Anwendung unerwartet beendet wurde, was mit XLAM-Add-In-Verweisen und benannten Bereichen zusammenhing.


- Es wurde ein Problem behoben: Beim Festlegen der FormulaR1C1-Eigenschaft für einen Bereich mithilfe eines Makros waren die Zellbezüge falsch, wenn ein Diagrammblatt das aktive Blatt war.


- Es wurde ein Problem behoben, das zur Fehlermeldung „Excel hat nicht ausreichend Ressourcen zur Verfügung für die Berechnung einer oder mehrerer Formeln“ führen konnte.


- Es wurde ein Problem, bei dem in Datenüberprüfungslisten u. U. nicht alle Elemente in der Liste angezeigt wurden, wenn die Office-Sprache auf Spanisch festgelegt war.


- Ein Problem wurde behoben, das beim Aktualisieren von OLAP-PivotTables zu einem Absturz führen könnte.

### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben: Benutzer können IRM (Information Rights Management) jetzt für Outlook deaktivieren, ohne es für die übrigen Office-Anwendungen deaktivieren zu müssen.


- Es wurde ein Problem behoben, durch das Benutzer ihren Delegaten keine Editor-Berechtigung erteilen konnten.


- Es wurde ein Problem behoben, durch das die Anwendung bei der Auswahl eines Suchergebnisses unerwartet beendet wurde.


- Es wurde ein Problem behoben, das bewirkte, dass Suchvorgänge in Gruppenkalendern keine Ergebnisse zurückgaben.


- Es wurde ein Problem behoben, durch das zeitweilig Fehler auftraten, wenn Delegaten freigegebene Ordner in einem anderen Postfach öffneten.


- Es wurde ein Problem behoben, das dazu führte, dass einige automatisch generierte E-Mails mit einem leeren Textkörper gesendet wurden, wenn die Betreffzeile leer war.


- Es wurde ein Problem behoben, durch das die Kopfzeilen von Nachrichten in chinesischer Sprache bei der Beantwortung oder Weiterleitung nicht lesbar waren.

- Es wurde ein Problem behoben, bei dem optionale verbundene Erfahrungen das Laden von Web-Add-Ins blockierten.  <br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://developer.microsoft.com/de-DE/office/blogs/outlook-add-ins-and-optional-connected-experiences/)


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem das Forms Content Add-In nach dem Einfügen erst dann gerendert wird, wenn Benutzer auf eine andere Folie klicken, um sie anzuzeigen.


### <a name="office-suite"></a>Office-Suite

- Es wurde ein Problem behoben, das kommerzielle Kunden betraf, die System Center Configuration Manager oder andere Verwaltungstools für das Office-Update unter Verwendung von Microsoft 365-Endpunkt-DLP (Verhinderung von Datenverlust am Endpunkt) nutzten.

- Es wurde ein Problem behoben, durch das die Messaging-API für Office-Add-Ins nicht funktionierte.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-october-13"></a>Version 2008: 13. Oktober
*Version 2008 (Build 13127.20638)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Ein Fehler in PivotDateFilter-APIs, in denen die Filterbedingungen "Vorher" und "Nachher" vertauscht waren, wurde behoben.


- Es wurde ein Problem behoben, bei dem Benutzer einen PivotTable-Filter nicht ändern konnten, weil er auf einen Wert eingestellt war, der in einer Analysis Services-Datenbank nicht mehr vorhanden war.


- Es wurde ein Problem behoben, durch das Excel abstürzen kann, wenn die Schnellanalyse nach dem Fixieren der obersten Zeile des Blatts verwendet wird.


- Es wurde ein Problem behoben, durch das eine Warnung zu einer beschädigten Arbeitsmappe verursacht werden konnte, wenn Sie Formeln mit wennnv () enthielt.


### <a name="outlook"></a>Outlook

- Behebt ein Problem, das bewirkt, dass Benutzer freigegebene Kalender nicht schließen konnten, indem Sie in der Ecke auf das "X" klicken.


- Behebt ein Problem, das dazu führte, dass die Einstellung "Verbesserungen bei gemeinsam genutzten Kalendern aktivieren" manchmal nicht auf bestehende gemeinsam genutzte Kalender angewendet werden konnte.


- Behebt ein Problem, durch das Benutzern beim Öffnen einer Cloudanlage auf der Safelinks-Seite anstelle des Dokuments, das sie öffnen wollten, ein Fehler angezeigt wurde.


- Behebt ein Leistungsproblem beim Anlagenupload.


### <a name="powerpoint"></a>PowerPoint

- Diese Änderung behebt ein Problem mit der Funktion "Export in animiertes GIF", wobei durch das Klicken auf die Schaltfläche "Exportieren" nicht exportiert wurde.


- Sicherheitsproblembehebung für ein Problems, bei dem IRM-Schutz beim Öffnen einer PowerPoint-Datei in der geschützten Anzeige deaktiviert wurde.

- Wir haben ein Problem im Dialogfeld „Aktionseinstellungen“ behoben, das einen Absturz in der PowerPoint-App verursacht hat.

### <a name="visio"></a>Visio

- Wir haben ein Problem behoben, durch das die Echtzeitvorschau bei der Textausrichtung abstürzte.


### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem es zu einem Absturz kam, wenn Benutzer bestimmte sehr große E-Mails öffneten.


- Es wurde ein Problem behoben, das beim Öffnen eines Dokuments zu einem Absturz führen konnte.


- Es wurde ein Problem behoben, das beim Starten von Word zu einem Absturz führen konnte.


- Es wurde ein Problem mit dem Dialogfeld "Formatvorlagenkatalog" behoben.


### <a name="office-suite"></a>Office-Suite

- Wenn ein Benutzer ein Dokument/ eine Datei auf Tintenstrahldrucker aus Office druckt und die Druckertintenstand niedrig ist, wird die Nachricht „Wenig Toner“ oder „Kein Toner“ angezeigt, auch wenn Tintenstrahldrucker keine Toner haben. Die Nachricht wurde geändert, um „Wenig Toner/Tinte“ bzw. „Kein Toner/keine Tinte“ anzuzeigen.


- Behebt eine hohe CPU-Auslastung beim Leerlauf mit GIF/animated model3D


- Diese Änderung behebt die Ursache für einen Absturz, der beim Starten von Office-Apps auftrat, weil die Datei "d2d1.dll" nicht geladen werden konnte.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-september-08"></a>Version 2008: 08. September
*Version 2008 (Build 13127.20408)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="access"></a>Zugriff

- **Seien Sie beim Arbeiten im Abfrage-Designer, in der SQL-Ansicht und im Fenster „Beziehungen“ produktiver:** Klicken Sie zum Öffnen, Gestalten, Vergrößern oder Verkleinern und Ausblenden mit der rechten Maustaste auf die betreffende Tabelle. Suchen und Ersetzen von Text in der SQL-Ansicht. Auswählen mehrerer Tabellen im Fenster „Beziehungen“.

- **Tabellen mit weniger Klicks hinzufügen:** Verwenden Sie den Aufgabenbereich „Tabellen hinzufügen“, der während Ihrer Arbeit geöffnet bleibt, um Tabellen zu Beziehungen und Abfragen hinzuzufügen. [Weitere Informationen](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a>Excel

- **Verbesserte Kartendiagramme:** Wir haben Kartendiagramme durch Integration mit den geografischen Datentypen von Excel verbessert, wodurch Sie umfangreiche Informationen zu den Orten auf Ihrer Karte anzeigen können. [Weitere Informationen](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.<br />Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Erstellen von PivotTables aus Datasets in Power BI in Excel:** Sie können mit wenigen Klicks PivotTables in Excel erstellen, die mit in Power BI gespeicherten Datensätzen verbunden sind.  Auf diese Weise können Sie sowohl PivotTables als auch Power BI optimal nutzen. Sie können Ihre Daten mit PivotTables aus Ihren sicheren Power BI-Datensätzen berechnen, zusammenfassen und analysieren. [Weitere Informationen](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br />Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)

- **Ihre Lieblingsfunktionen von Excel sind jetzt noch schneller:** Die Funktionen SUMMEWENNS, MITTELWERTWENNS, ZÄHLENWENNS, MAXWENNS und MINWENNS sind jetzt viel schneller als je zuvor. Gelangen Sie schneller zum Endergebnis. Probieren Sie es jetzt aus.

- **RTD-Verbesserungen (Real-Time Data):** In Office 365, Version 2002, monatlicher Kanal und höher, ist die Excel-Funktion RealTimeData (RTD) beim Berechnen der Daten in der Tabelle wesentlich schneller als in Excel 2010. Wir haben Engpässe in den zugrunde liegenden Arbeitsspeicher- und Datenstrukturen entfernt und sie threadsicher gemacht, damit sie für alle verfügbaren Threads der Multithread-Neuberechnung (MTR) berechnet werden können.

### <a name="outlook"></a>Outlook

- **Aktualisierungen freigebender Kalender funktionieren jetzt noch schneller:** Outlook ist in der Lage, freigegebene Kalender in Office 365 mithilfe der REST API zu aktualisieren. Aktivieren Sie die Vorschau, um schnellere und zuverlässigere Aktualisierungen für freigegebene Kalender zu erhalten.

- **Bessere Ergebnisse – im Handumdrehen:** wir haben die Suche aktualisiert, damit Sie intelligenter, schneller und zuverlässiger als je zuvor ist. [Weitere Informationen](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Ziehen Sie E-Mails in eine Gruppe, die Sie besitzen:** Verschieben und Kopieren von Nachrichten und Unterhaltungen, indem Sie diese aus Ihrem Posteingang ziehen. Die von ihnen gezogenen Nachrichten werden für alle Gruppenmitglieder freigegeben.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)

- **Der Kalender wird rundumerneuert:** Sie können visuelle Aktualisierungen anzeigen, mit denen Ihr Kalender einfacher durchsucht werden kann. [Weitere Informationen](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)

- **An Besprechungen teilnehmen, ohne den Posteingang zu verlassen:** Sie brauchen nicht zu Ihrem Kalender zu wechseln, um an Onlinebesprechungen teilzunehmen. Wenn der Kalender im Aufgabenbereich angeheftet ist, können Sie mit nur einem Klick an einer Besprechung teilnehmen. [Weitere Informationen](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- **Neue Benutzeroberfläche für WLAN-Netzwerke mit Anmeldung:** Sind Sie schon einmal einem WLAN-Netzwerk beigetreten, mit dem Sie sich anmelden mussten? Outlook erkennt dies jetzt und hilft Ihnen, eine Verbindung zu herstellen.<br />Weitere Detailinformationen finden Sie in diesem [Blogbeitrag](https://insider.office.com/de-DE/blog/outlook-on-public-wi-fi-networks-just-got-easier)

- **Erhalten Sie E-Mail-Vorschläge, wenn Sie nach einer Person suchen**: Wenn Sie den Namen einer Person im Suchfeld eingeben, werden die relevantesten E-Mail-Nachrichten in die Ihnen gezeigten Suchvorschläge einbezogen. [Weitere Informationen](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a>PowerPoint

- **Ziehen Sie die Aufmerksamkeit mit \@Erwähnungen** auf sich: Verwenden Sie @Erwähnungen in Kommentaren, um Kollegen wissen zu lassen, wann Sie ihr Feedback benötigen. [Weitere Informationen](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Verbesserte Kartendiagramme:** Wir haben Kartendiagramme durch Integration mit den geografischen Datentypen von Excel verbessert, wodurch Sie umfangreiche Informationen zu den Orten auf Ihrer Karte anzeigen können. [Weitere Informationen](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **GIFs im Handumdrehen:** eine Folie, ein Frame. Erstellen Sie auf einfache Weise Schleifen-GIFs in PowerPoint. [Weitere Informationen](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br />Einzelheiten finden Sie im [Blogbeitrag](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/).

- **Bessere Diagramme: Mit besseren Konnektoren und einem reibungsloseren Tintenkonvertierungsprozess können Sie Ihre Ideen zuversichtlicher einfärben.** [Weitere Informationen](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.<br />Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Kommentare:** Die neue Kommentarumgebun g in PowerPoint ermöglicht es Ihnen, schnell und einfach Kommentare zu Ihren Dokumenten zu entdecken und hinzuzufügen. Modernisieren Sie Ihre Arbeitsabläufe bei der Zusammenarbeit mit neuen Funktionen wie Verankern und Auflösen von Kommentaren, Aufgaben, verbesserten Benachrichtigungen über Erwähnungen und vielem mehr. [Weitere Informationen](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- **Synchronisieren von Änderungen während der Präsentation:** Änderungen können jetzt synchronisiert werden, wenn sie vorgenommen werden, selbst wenn sich die Präsentation im Bildschirmpräsentationsmodus befindet. [Weitere Informationen](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)

- **Link zu einer Folie:** Bitten Sie einen Kollegen um einen Beitrag zu Ihrer Foliengruppe zu leisten, und leiten Sie ihn direkt zu der Folie, bei der Sie Hilfe benötigen. [Weitere Informationen](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br />Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)

- **Verbesserte Stream-Video-Leistung in PowerPoint:** Wir haben die Wiedergabeleistung von Microsoft Stream-Videos verbessert, um die Ladezeit von Videos zu minimieren und eine reibungslose Wiedergabe zu ermöglichen. Verwenden Sie Ihre Unternehmensvideos aus Microsoft Stream, um bessere Präsentationen zu erstellen.


### <a name="word"></a>Word

- **Verbesserte Kartendiagramme:** Wir haben Kartendiagramme durch Integration mit den geografischen Datentypen von Excel verbessert, wodurch Sie umfangreiche Informationen zu den Orten auf Ihrer Karte anzeigen können. [Weitere Informationen](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **Auswählen von Freihandeingabe:** Das Lasso-Tool auf der Registerkarte "Zeichnen" hilft Ihnen beim Auswählen von per Freihand gezeichneten Objekten. Wählen Sie einzelne Striche oder ganze Wörter aus. [Weitere Informationen](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.<br />Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Bestätigung der Aktion in Sprachausgaben:** Bestätigung der Aktion ist eine wichtige Voraussetzung für die Barrierefreiheit. Mit der Einführung einer neuen Benachrichtigungs-API von Windows können wir jetzt Benutzer der Sprachausgabe über den Erfolg ihrer Aktionen informieren. „Ausschneiden“, „Kopieren“, „Einfügen“, „Fett“, „Kursiv“, „Unterstrichen“, „Rückgängig“, „Wiederholen“, "Autokorrektur“ und "Automatische Großschreibung“ werden jetzt Benutzern der Sprachausgabe in Word unter Win32 angekündigt. Zum Aktivieren dieses Features aktivieren Sie die Sprachausgabe, indem Sie WINDOWS+STRG+EINGABE drücken.<br />Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)

### <a name="office-suite"></a>Office-Suite

- **Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Zugriff

- Es wurde ein Problem mit dem Einfügen von verknüpften SQL-Tabellen behoben, die eine Identität (z. b. Autowert) enthalten.

- Ein Problem wurde behoben, bei dem die Abfrageausführung ungefähr doppelt so lange dauerte als erwartet.

- Ein Problem wurde behoben, um den Datentyp Datum/Uhrzeit in Ihrem Code aufrufen zu können, ohne dass die APP abstürzt.

- Ein Problem wurde behoben, damit Sie jetzt wieder zu Ihrer am meisten aktualisierten Access-Version zurückkehren können, und verwenden Sie DAO/VBA zum Verwalten und Bearbeiten eines Dezimal-Datentyps.

- Diese Korrektur behebt das Problem, bei dem der Versuch, bestimmte Abfragen auszuführen, zuvor die Fehlermeldung „Abfrage ist zu komplex“ erzeugt hat.

- In Access wurde dieses aktuelle Problem behoben, es werden aber unsere zusätzlichen Schnittstellen untersucht, um sicherzustellen, dass dieses Problem nicht fortbesteht. Das Team informiert Sie über zukünftige Updates. Wir bedanken uns für Ihre Geduld.

- Das Problem wurde gelöst – Sie können nun unseren ODBC-Treiber außerhalb der Office-Click-to-Run-App verwenden.

### <a name="excel"></a>Excel

- Bei Arbeitsmappen, die sich im schreibgeschützten Modus befanden, wurde möglicherweise die automatische Dokumentklassifizierung durchgeführt.

- Ein Absturz wurde behoben, der beim Versuch, eine Datenverbindung herzustellen, auftreten konnte, wenn Sie sich von Ihrem Konto abgemeldet haben.

- Es wurde ein Problem behoben, bei dem Excel abstürzen kann, wenn versucht wird, PivotTables in ein Diagrammblatt einzufügen.

- Beim Versuch eine Datei zu speichern, die eine Formel mit der Funktion LET() enthält, konnte ein Fehler auftreten.

- Es wurde ein Problem behoben, bei dem Excel unter bestimmten Umständen abstürzte, wenn "Format übertragen" verwendet wurde.

- Es wurde ein Problem behoben, das dazu führte, dass CustomUI XML für eine benutzerdefinierte Menübandregisterkarte beim Speichern in SharePoint/OneDrive entfernt wurde.

- Es wurde ein Problem behoben, bei dem Excel möglicherweise nicht mehr reagierte, nachdem STRG+UMSCHALT+Pfeiltasten zum Scrollen verwendet wurden, wenn das Excel-Fenster über Microsoft Teams gemeinsam genutzt wurde.

- Es wurde ein Problem behoben, bei dem das Klicken auf einen Link zu einer anderen Stelle innerhalb derselben Arbeitsmappe in einigen Fällen dazu führt, dass die Arbeitsmappe ausgeblendet wird.

- Es wurde ein Problem behoben, bei dem die externe Verknüpfung nicht mehr funktioniert, nachdem die Datei erneut geöffnet wurde, wenn der Dateipfad zu lang ist.

- Application.Evaluate (VBA) funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.

- In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.

- Ein Problem wurde behoben, bei dem Excel in manchen Fällen abstürzte, nachdem ein Blatt mit einer PivotTable kopiert wurde.

- Damit wird ein Problem behoben, bei dem interne Tabelleneigenschaften für Verbindungen, die vom SQL-Datenanbieter in älteren Office-Versionen erstellt wurden, anders als in Office 365 festgelegt wurden. Dies führte dazu, dass die Dropdown-Liste "Tabellenvorschau/Abfrageeditor" für Dateien mit Verbindungen, die in älteren Office-Versionen erstellt wurden, deaktiviert wurde, wenn sie mit Office 365 geöffnet wurden.

- Es wurde ein Problem behoben, bei dem externe Links beim Füllen nicht aktualisiert werden, wenn das Quellbuch geschlossen ist.

- Ein Problem wurde behoben, bei dem Freihandeingaben dazu führen konnten, dass Excel nicht mehr reagierte.

### <a name="onenote"></a>OneNote

- Informieren Sie die Benutzer über die Infoleiste über temporäre Anpassungen in Microsoft OneNote, die dazu beitragen, die Synchronisierung und Dienstverfügbarkeit bei hoher weltweiter Nutzung zu verbessern.

- Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehende Anpassung der Synchronisierungshäufigkeit in OneNote 2016.

- Die Erkennung des Status der gemeinsamen Dokumenterstellung wurde verbessert, um die Ressourcennutzung zu verringern.

- Verbesserte Synchronisierungs- und Servicestabilität durch vorübergehende Reduzierung der maximal zulässigen Größe neuer eingebetteter Anhänge auf 50 MB in OneNote 2016. Bei Dateien, die dieses Limit überschreiten, haben Benutzer die Möglichkeit, die Datei auf OneDrive hochzuladen und einen Link in OneNote einzufügen.

- Verbesserte Synchronisierungs- und Servicestabilität durch vorübergehende Deaktivierung der Videoaufzeichnung in der Anwendung in OneNote 2016. Lokale Notizbücher sind von dieser Maßnahme nicht betroffen.

- Die Synchronisierungs- und Servicestabilität wurde durch vorübergehende Änderung der Häufigkeit der Erstellung von Seitenversionshistorien verbessert.

- Die Synchronisierungs- und Serverstabilität wurde durch vorübergehende Deaktivierung des Verschiebens von Seiten in den Papierkorb verbessert. Benutzer, die eine Seite löschen möchten, werden stattdessen in einem Dialogfeld gefragt, ob sie die Seite dauerhaft löschen möchten.

### <a name="outlook"></a>Outlook

- Behebt ein Problem, das dazu führte, dass Benutzer, die versuchten, eine Besprechungsanfrage von einem zu ihrem Profil hinzugefügten sekundären Konto aus zu erstellen, kein leeres Von: Feld anstelle ihrer E-Mail-Adresse sahen.

- Behebt ein Problem, das dazu führte, dass Benutzer nach dem Hinzufügen eines gemeinsam genutzten Postfachs keine Verbindung zu öffentlichen Ordnern herstellen konnten.

- Es wurde ein Problem behoben, das bewirkt hat, dass Besprechungen aus dem Kalender eines Managers nicht entfernt werden konnten, wenn sie von einem Delegierten unter bestimmten Umständen abgelehnt wurden.

- Es wurde ein Problem behoben, durch das einige Benutzende des Features "Verbesserungen bei gemeinsam genutzten Kalendern" nicht in der Lage waren, einen neu hinzugefügten freigegebenen Kalender anzuzeigen.

- Behebt ein Problem, das bei der Interaktion mit Cloud-Anlagen gelegentlich zu Abstürzen führte.

- Ein Problem wurde behoben, das zu einem Absturz führte, wenn Benutzer von CLP die Absenderadresse in einer Antwort von geschütztem in ungeschützten Kontext wechselten.

- Es wurde ein Problem behoben, bei dem Outlook die Datenschutzrichtlinie nicht aktiviert hat, um Tipps für Benutzer zu geben, die für den Dienst bezahlt haben und M365 Business Plus-Pläne nutzen.

- Es wurde ein Problem mit dem Ereignis "CLP-Überwachung" für die Bezeichnung "Antworten/Weiterleiten" behoben.

- Ein Problem wurde behoben, bei dem die Breite des Ordnerbereichs unerwartet geändert wurde.

- Ein Problem wurde behoben, durch das Benutzer das Erstellungsdatum der Anlagen sehen konnten, die Sie per Drag & Drop in Ihr Dateisystem kopiert haben, wobei es auf den 1. Januar 4501 festgestellt wurde.

- Es wurde ein Problem behoben, das bewirkt hat, dass Benutzende einiger Zeichensätze beim Hinzufügen eines Smart Link zu einer Microsoft Office SharePoint Online-Datei Dateinamen falsch angezeigt bekamen.

- Es wurde ein Problem behoben, durch das Benutzern die Nachricht "Die Regeln auf diesem Computer entsprechen nicht den Regeln in Microsoft Exchange" angezeigt wird, wenn sie ihre Regeln in Outlook aktualisieren.

- Ein Problem wurde behoben, das dazu führte, dass Outlook keine Suchvorschläge abrufen konnte.

- Es wurde ein Problem behoben, durch das Benutzer der Verbesserungen des am "Freigegebenen Kalender" Kalenderfehler sahen.

- Es wurde ein Problem behoben, das dazu führte, dass Benutzer in einigen Szenarios zeitweilig Hängen und Abstürzen erfuhren.

- Es wurde ein Problem behoben, das zu einem Absturz führte, wenn Benutzende beim Löschen von 4 oder mehr E-Mails von einem POP-Konto mit der Option "Nur Kopfzeilen herunterladen" einen Absturz erlebten.

- Es wurde ein Problem behoben, bei dem die Option "Weiterleitung zulassen" in den "Antwortoptionen" für Kalenderbesprechungen nicht angezeigt wurde, wenn die Option für das Herunterladen freigegebener Ordner NICHT aktiviert war.

- Es wurde ein Problem behoben, das dazu führte, dass Delegierte beim Bearbeiten eines vorhandenen Kalendertermins im Kalender eines Managers eine Fehlermeldung erhielten.

- Es wurde ein Problem behoben, aufgrund dessen bei Benutzern Abstürze von MAPI-Anwendungen von Drittanbietern auftraten.

- Es wurde ein Problem behoben, durch das Outlook nach einem Windows-Update beim Öffnen von lokal gespeicherten MSG- oder OFT-Dateien abstürzte.

- Ein Problem wurde behoben, das dazu geführt hat, dass Outlook bei einigen Windows-Versionen abstürzt.

- Es wurde ein Problem behoben, das dazu führte, dass Benutzer von Windows 10-Serverversionen die Warnung "Antivirenstatus: Ungültig" gesehen haben. Diese Windows-Version unterstützt die Virenerkennung, es wurde jedoch kein Virenschutzprogramm gefunden, obwohl das Virenschutzprogramm korrekt installiert war.

- Es wurde ein Problem behoben, durch das Outlook nach einem Windows-Update beim Öffnen von lokal gespeicherten MSG- oder OFT-Dateien abstürzte.

- Ein Problem wurde behoben, das dazu geführt hat, dass Outlook bei einigen Windows-Versionen abstürzt.

- Es wurde ein Problem behoben, das dazu führte, dass Benutzer ständig von Outlook aufgefordert wurden, das Reparaturtool für den Posteingang auszuführen.

- Es wurde ein Problem behoben, das dazu führte, dass Benutzer gelegentlich einen Absturz feststellten, wenn Sie den X-Knopf auf ihrer Maus verwendeten.

- Ein Problem wurde behoben, das dazu führte, dass Benutzer OneDrive-Anlagen von außerhalb ihres Mandanten nicht auf ihrem lokalen Computer speichern konnten, wenn sie im Dialogfeld "Sicherheit" die Option "Speichern" wählten.

- Ein Problem wurde behoben, das dazu führte, dass die Seite des Terminplanungs-Assistenten nicht angezeigt wurde.

- Es wurde ein Problem behoben, das dazu führte, dass die Seite des Planungsassistenten von einigen Benutzern nicht angezeigt wurde.

- Ein Problem wurde behoben, das beim Abrufen von Persona-Informationen gelegentlich zu einem Absturz führte.

- Dies behebt ein Problem, das beim Bearbeiten von Empfängern gelegentlich zu Abstürzen führte.

- Behebt ein Problem, das dazu führte, dass Benutzern bei Verwendung der kompakten Ansicht gelegentlich Anomalien angezeigt wurden.

- Es wurde ein Problem behoben, durch das Outlook-Benutzern in kompakten Ansichten Probleme mit der Navigation angezeigt wurden.

- Es wurde ein Problem behoben, das bewirkt hat, dass das Rechtsklick-Kontextmenü nicht in den Suchsteuerelementen angezeigt wurde.

- Behebt ein Problem, durch das Benutzern beim Beantworten von oder Verfassen neuer E-Mails den folgenden Fehler angezeigt wurde: „Einige der Dateien auf dieser Webseite befinden sich nicht am erwarteten Speicherort. Möchten Sie sie dennoch herunterladen? Wenn Sie sicher sind, dass die Webseite aus einer vertrauenswürdigen Quelle stammt, klicken Sie auf 'Ja'.“

- Behebt ein Problem, bei dem sich das Programm beim Verlassen von Outlook aufhängte.

- Es wurde ein Problem behoben, das dazu führte, dass bei der Suche nach einem Feature in "Features vorschlagen" keine Ergebnisse zurückgegeben wurden und der Benutzer keine Möglichkeit hatte, eine neue Idee für Features zu übermitteln. 

- Ein Problem wurde behoben, das zu Formatierungsproblemen in Benachrichtigungen über einen Sicherheitsvorfälle führte.

- Es wurde ein Problem behoben, bei dem beim Einreichen von Feedback aus einer Administratorbenachrichtigung ein Absturz verursacht wurde.

- Es wurde ein Problem beim Kopieren und Einfügen des SVG-Bilds behoben.

- Dies behebt ein Problem, das beim Bearbeiten von Empfängern gelegentlich zu Abstürzen führte.

- Es wurde ein Problem beim Kopieren und Einfügen des SVG-Bilds behoben.


### <a name="powerpoint"></a>PowerPoint

- Die Ursache für einen Absturz wurde behoben, der auftrat, wenn in einer Datei sowohl moderne als auch ältere Kommentare verwendet werden, wodurch ein Upgrade der Kommentare ausgelöst wird.

- Ein Absturzproblem mit der PowerPoint-App wurde behoben.

- Wir haben ein Absturzproblem mit dem Vorschlagsbereich behoben.

### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem ein zusätzliches ProjectBeforeTaskChange-Ereignis ausgelöst wird, wenn Vorgänger/Nachfolger-Daten in einer Formular-Maske bearbeitet werden.

- Ein Problem wurde behoben, bei dem Project beim Speichern von Projekten möglicherweise abstürzt, die mit älteren Project-Versionen erstellt wurden.

- Es wurde ein Problem behoben, bei dem der Benutzer keine zeitgesteuerte Baseline-Arbeit eingeben konnte, wenn die Einstellung zum Schutz der aktuellen Arbeit aktiviert war.

- Ein Problem wurde behoben, bei dem "Vorgang Prozent abgeschlossen" fälschlicherweise in einen Wert kleiner als 100 % geändert wurde, nachdem der Vorgang als abgeschlossen gekennzeichnet wurde.

- Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.

- Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.

- Ein Problem wurde behoben, bei dem das Ereignis „ProjectBeforeTaskChange“ nicht erkannt wird, wenn ein Vorgang über die Schaltfläche „Deaktivieren“ deaktiviert/aktiviert wurde.

- Folgendes Problem wurde behoben: Wenn Sie Project in Verbindung mit Project Web App verwenden, das Kommas als Dezimaltrennzeichen festgelegt ist, und Sie versuchten, einer Abhängigkeit eine Verzögerung hinzuzufügen, schlägt die Methode "TaskDependencies Add" fehl.

- Ein Problem wurde behoben, bei dem Projekte aus Project Web App nicht im Project-Desktop Client geöffnet werden konnten, wenn die URL auf ".com" endete.

- Es wurde ein Problem behoben, das bewirkt, dass nicht alle Abhängigkeiten korrekt kopiert werden, wenn ein Vorgang mit mehreren Abhängigkeiten eingefügt wird.

- Es wurde ein Problem behoben, bei dem man kein PDF/XPS aus Project in einer SharePoint-Dokumentbibliothek speichern konnte.

- Es wurde ein Problem behoben, bei dem eine Aufgabe, die als 100 % abgeschlossen gekennzeichnet ist, fälschlicherweise weniger als 100 % abgeschlossen ist.

- Es wurde ein Problem behoben, bei dem das Ereignis "ProjectBeforeTaskChange" nicht ausgelöst wurde, wenn eine Änderung am Projektzusammenfassungsvorgang – entweder am Projektstart/Aufgabenfeld – vorgenommen wurde.

- Ein Problem wurde behoben, bei dem die Restkosten nicht immer richtig berechnet wurden, wenn für eine Ressource mehrere Kostensatztabellen definiert waren.

- Es wurde ein Problem behoben, bei dem das Projektabschlussdatum für Projekte, die mit der Microsoft Office SharePoint Online-Aufgabenliste verbunden sind, nicht aktualisiert wird.

- Ein Problem wurde behoben, bei dem die im Dialogfeld "Ressourcen zuordnen" ausgewählte Aufgabe nicht mit der in der Ansicht "Task Board" ausgewählten Aufgabe identisch ist.

- Ein Problem wurde behoben, bei dem ein Projekt, das in einen ungültigen Zustand geraten war, nicht geöffnet werden konnte.

### <a name="skype"></a>Skype

- Wenn ein Benutzer eine Richtlinie erhält, die ihn in die Kategorie "Nur für Teams" verschiebt, konnte er dennoch das Outlook-Add-In "Skype for Business" zur Planung von Besprechungen verwenden. Nach diesem Update können Sie keine Besprechungen mit Skype for Business mehr planen, nachdem der Client die Richtlinie gelesen hat, in der angegeben ist, dass der Benutzer "Nur für Teams" ist, und in den Modus "Nur an Besprechung teilnehmen" wechselt. Darüber hinaus aktiviert sich das Outlook-Add-In "Skype for Business" beim Start nicht selbst, wenn es sieht, dass sich der Skype for Business-Client im Modus "Nur an Besprechung teilnehmen" befindet.

- Der Hautton des Tanzemoticons wurde auf neutrale Farbe geändert.

### <a name="word"></a>Word

- Es wurde ein Problem beim Öffnen von Word-Dokumenten aus der benutzerdefinierten Dokumentbereitstellung (aspx) behoben, wenn die URL eine Abfragekomponente enthält.

- Diese Änderung behebt ein Problem, bei dem Office-Anwendungen nach einer vorherigen gemeinsamen Dokumenterstellung in einem Silent-Save-Fehlerstatus hängenbleiben konnten.

- Behebt ein Problem, das zum Absturz beim Beantworten oder Verfassen neuer E-Mails führte.

- Es wurde ein Problem behoben, das dazu führte, dass Benutzer gelegentlich einen Absturz feststellten, wenn Sie den X-Knopf auf ihrer Maus verwendeten.

- Es wurde ein Problem beim Kopieren und Einfügen des SVG-Bilds behoben.

- Es wurde ein Problem behoben, bei dem der Benutzer beim Ändern der Größe einer Form möglicherweise Inhalte verliert.

- Ein Problem wurde behoben, bei dem die Basisformatvorlagen nicht mit der Standardformatvorlage aktualisiert wurden.

- Es wurde ein Problem behoben, bei dem das Makro „AutoOpen“ vor „AutoExec“ ausgeführt wird.

- Es wurde ein Problem beim Kopieren und Einfügen des SVG-Bilds behoben.

- Es wurde ein Problem behoben, das beim Ziehen einiger Inhalte aus der App möglicherweise zu einem Absturz führte.


### <a name="office-suite"></a>Office-Suite

- Bei dem alten, nicht webdienstbasierten Bereich „Freigeben“ könnte das Schließen des Dokuments bei geöffnetem Bereich „Freigeben“ zu einem Absturz führen. Dies ist nun behoben.

- Ein Timing-Problem wurde behoben, das beim Schließen von Office-Dateien zu einem Absturz führen konnte.

- Es wurde das Problem der Fehlerrate von „ValidateInstall“ behoben, indem die Bing-Add-On-Installationsvalidierung standardmäßig auf „wahr“ gesetzt und die erfolgreiche Ausführung von MSI als erfolgreiche Installation betrachtet wurde.

- Ein neuer Sturz von AppV51 wurde zurückportiert, um eine Regression im vorherigen AppV51 zu beheben.

- Es wurde ein Problem mit Klick-und-Los behoben, das beim Erstellen eines festen Links für symbolische Links zu einem Updatefehler führte.

- Es wurde ein Problem behoben, das dazu führte, dass eine Laufzeitmeldung angezeigt wurde, obwohl der Übergang zum vollständigen Produkt abgeschlossen ist. Der Fix für dieses Problem bestand darin, sicherzustellen, dass der Dienst hinzugefügte Produkte ordnungsgemäß berechnet. Wir haben die neu hinzugefügten Produkte herausgefiltert (dabei wurde sichergestellt, dass sie auch in der neuen Konfiguration vorhanden sind) und sie am Ende der vorhandenen Produkt-Release-IDs hinzugefügt.

- Wir haben ein Problem behoben, bei dem Benutzer unter bestimmten Bedingungen die Benutzeroberflächenelemente oder -inhalte nicht angezeigt wurden, insbesondere beim Öffnen oder Verlassen der Referentenansicht oder bei der Verwendung mehrerer Bildschirme.

- Mit dieser Änderung werden potenzielle Probleme beim Laden und Abspielen von animierten Inhalten wie GIFs oder 3D-Modellen behoben.

- Diese Änderung behebt ein Problem, bei dem im Dialogfeld „Bild komprimieren“ bestimmte Benutzereinstellungen nicht beibehalten werden.

- Das Update behebt ein Problem in Microsoft Office, bei dem Visual Basic for Applications-Projekte mit Referenzen, die bei der Suche nach in der PATH-Umgebungsvariable angegebenen Speicherorten gefunden werden sollen, zur Laufzeit möglicherweise nicht richtig gefunden werden, was zu VBA-Laufzeitfehlern führt.

- Dieses Update behebt ein Problem in Visual Basic for Applications in Microsoft Office, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung beim Laden als fehlerhaft angesehen werden.

- Mit diesem Fix wird ein Fehler behoben, der verhindert, dass Sie gleichzeitig den Zugriff einschränken und Dateien mit einem Kennwort schützen können.

- Es wurde ein Absturzproblem mit dem Office-Host in Windows behoben, wenn ein Add-in aktiviert wird, während die Registrierung TabProcGrowth den Wert REG_SZ Typ hat.

- Der Office-Host stürzte in Windows ab, wenn ein Add-In aktiviert wird, während der Registrierungsschlüssel HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth auf Null gesetzt ist. Diese Änderung würde das Problem beheben.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-august-11"></a>Version 2002: 11. August
*Version 2002 (Build 12527.20988)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Ein Problem wurde behoben, bei dem verhindert wurde, dass mit der Option „Schreibschutz empfohlen“ geöffnete Dateien bearbeitet werden konnten.

### <a name="onenote"></a>OneNote

- Redundante Identitätsaufrufe wurden entfernt, um die Ressourcennutzung zu verringern.

- Die Erkennung des Status der gemeinsamen Dokumenterstellung wurde verbessert, um die Ressourcennutzung zu verringern.

- Die Funktion zum Erkennen von Fehlern und die Qualität der Synchronisierung wurden verbessert.

### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, das beim Starten von Outlook für einige Mandanten zu einem erheblichen Leistungsproblem führte.

### <a name="skype"></a>Skype

- Ein Problem wurde behoben, bei dem das Starten einer Bildschirmfreigabe auf einem 32-Bit-Skype for Business-Client fehlschlagen kann, nachdem er mehrere Tage lang ausgeführt wurde.

### <a name="office-suite"></a>Office-Suite

- Ein Problem wurde behoben, bei dem einige Dokumente – nach Deaktivierung von „Automatisches Speichern“ durch eine Gruppenrichtlinie – die neuesten Serverinhalte beim Öffnen möglicherweise so lange nicht zeigen, bis der Benutzer auf „Verfügbare Updates“ geklickt hat.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-july-14"></a>Version 2002: 14. Juli
*Version 2002 (Build 12527.20880)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Beschleunigen des Ladens von Dateien, die im lokalen OneDrive-Ordner zur Verfügung stehen.

- Es wurde ein Problem behoben, das dazu führte, dass CustomUI XML für eine benutzerdefinierte Multifunktionsleisten-Registerkarte beim Speichern in SharePoint/OneDrive entfernt wurde.

- Es wurde ein Problem behoben, bei dem die Fehlermeldung „Diese Arbeitsmappe wird derzeit von einer anderen Arbeitsmappe referenziert und kann nicht geschlossen werden“ eingeblendet wurde, weil Add-Ins in alphabetischer Reihenfolge und nicht in einer vom Benutzer festgelegten Reihenfolge geladen wurden.

- Es wurde ein Problem behoben, bei dem beim Klicken auf einen Hyperlink zu einer Stelle in einer bereits geöffneten Arbeitsmappe eine Arbeitsmappe ausgeblendet werden konnte.

- Es wurde ein Problem behoben, bei dem einige kopierte und eingefügte Diagrammverknüpfungen zugeordnete Laufwerksadressen anstelle von Universaladressen verwendeten.

- Die Leistung beim Löschen von Spalten mit verbundenen Zellen wurde verbessert.

- Ein Problem wurde behoben, bei dem Druckernamen in der Liste der Drucker im Dialogfeld „Drucken“ wiederholt werden konnten.

- Es wurde ein Problem behoben, bei dem Arbeitsblätter, die mehrere Formeln mit definierten Namen enthielten, zu längeren Zeiten beim Speichern von Dateien geführt haben.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem das IME-Fenster (Eingabemethoden-Editor) den zugrunde liegenden Text, der über den IME eingegeben wird, überlappte, wenn mehrere Monitore mit unterschiedlichen Auflösungen verwendet wurden.

- Es wurde ein Problem behoben, das bewirkte, dass bei einer bevorstehenden Änderung der Zeitzonendefinition Terminserien oder Besprechungen zur falschen Uhrzeit angezeigt wurden.

- Es wurde ein Problem behoben, durch das Benutzern die Nachricht "Die Regeln auf diesem Computer entsprechen nicht den Regeln in Microsoft Exchange" angezeigt wird, wenn sie ihre Regeln in Outlook aktualisieren.

- Es wurde ein Problem behoben, bei dem die Option "Weiterleitung zulassen" in den "Antwortoptionen" für Kalenderbesprechungen nicht angezeigt wurde, wenn die Option für das Herunterladen freigegebener Ordner NICHT aktiviert war.

- Ein Problem wurde behoben, durch das gelegentlich Kategorien in E-Mail-Nachrichten nicht mehr aufschienen.

- Ein Problem wurde behoben, durch das Stellvertretungen auf unterschiedlichen Computern unterschiedliche Ordnerhierarchien für freigegebene Postfächer angezeigt wurden.

- Ein Problem wurde behoben, durch das Stellvertretungen beim Bearbeiten eines vorhandenen Kalendertermins im Kalender eines Managers eine Fehlermeldung erhalten haben.

- Ein Problem wurde behoben, das bewirkt hatte, dass der Text einer NDR-Nachricht nach der Bearbeitung des Betreffs von Unicode in ASCII geändert wurde.

- Es wurde ein Problem behoben, durch das Benutzer einen Absturz erfahren, wenn zwei Add-Ins der gleichen Menübandgruppe eine Schaltfläche hinzufügen.

- Es wurde ein Problem behoben, aufgrund dessen Benutzer nicht in der Lage waren, E-Mails an eine persönliche Verteilerliste zu senden.

- Es wurde ein Problem behoben, das bewirkt, dass Links nicht zu E-Mails mit der richtigen standardmäßigen Mandantenberechtigung hinzugefügt werden können, wenn die standardmäßige Mandantenberechtigung als "jeder" konfiguriert ist.

- Ein Problem wurde behoben, das dazu führte, dass Benutzer OneDrive-Anlagen von außerhalb ihres Mandanten nicht auf ihrem lokalen Computer speichern konnten, wenn sie im Dialogfeld "Sicherheit" die Option "Speichern" wählten.

### <a name="word"></a>Word

- Es wurde ein Problem im Coautthoring behoben, wenn die Richtlinie "FileBlick\Word2007Files" aktiviert wird.

- Es wurde das Problem behoben, dass Word QuickPart beim Hinzufügen eines Suchfelds, das umbenannt wurde, nicht funktioniert.

### <a name="office-suite"></a>Office-Suite

- Ein Problem wurde behoben, bei dem Benutzer bei der gemeinsamen Erstellung von großen PowerPoint-Dateien übermäßige Netzwerk- und CPU-Auslastung erfahren können.

- Ein neuer Sturz von AppV51 wurde zurückportiert, um eine Regression im vorherigen AppV51 zu beheben.

- Es wurde ein Absturzproblem mit dem Office-Host in Windows behoben, wenn ein Add-in aktiviert wird, während die Registrierung TabProcGrowth den Wert REG_SZ Typ hat.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-june-09"></a>Version 2002: 9. Juni
*Version 2002 (Build 12527.20720)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem die externe Verknüpfung nicht mehr funktioniert, nachdem die Datei erneut geöffnet wurde, wenn der Dateipfad zu lang ist.

- Es wurde ein Problem behoben, bei dem Excel u. U. nicht mehr reagierte, nachdem STRG+UMSCHALT+Pfeiltasten zum Scrollen verwendet wurden, wenn das Excel-Fenster über Microsoft Teams gemeinsam genutzt wurde.

- Ein Problem mit der Skalierung von Kontrollkästchen in Formularsteuerelementen beim Drucken wurde behoben.

- Ein Absturz konnte auftreten, wenn versucht wurde, Änderungen mithilfe des Legacymodus "Freigegebene Arbeitsmappe" auf einem neuen Blatt für eine Arbeitsmappe aufzulisten.

- Das Einfügen einer Spalte in eine gefilterte Liste würde länger dauern als erwartet.

- Es wurde ein Problem behoben, bei dem ein @-Symbol, mit dem eine Formel beginnt, als impliziter Schnittmengenoperator betrachtet wird.

### <a name="outlook"></a>Outlook

- Ermöglicht die Teilnahme an einer Teambesprechung direkt über den systemeigenen Teams-Client.

- Es wurde ein Problem behoben, bei dem Outlook die Datenschutzrichtlinie nicht aktiviert hat, um Tipps für Benutzer zu geben, die für den Dienst bezahlt haben und M365 Business Plus-Pläne nutzen.

- Es wurde ein Problem behoben, aufgrund dessen Benutzer mit der falschen Browseremulationseinstellung nicht die Authentifizierungsaufforderung für Gmail ausführen konnten.

- Es wurde ein Problem behoben, aufgrund dessen Outlook-Benutzern auf Serverbetriebssystemen die Fehlermeldung "Antivirenstatus: Ungültig" angezeigt wurde. Diese Version von Windows unterstützt die Erkennung von Antivirus, aber es wurde kein Antivirus gefunden, obwohl Antivirus korrekt konfiguriert war.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem die Ausrichtung von Wörtern in einem Dokument durcheinandergebracht wurde, wenn Benutzer nach dem Drucken mit Schnelldruck versuchten, den Text zu bearbeiten.

### <a name="office-suite"></a>Office-Suite

- Dieses Problem wurde behoben, indem die Kanalnamen in der Januar 2020-Verzweigung in der Backstage-Version auf die neuen Kanalnamen aktualisiert wurden.

- Dieses Problem wurde behoben. Wenn ein Gerät nun mit Richtlinien verwaltet wird, wird nicht die DMS Audience-API aufgerufen.

- Es wurde das Problem behoben, aufgrund dessen es beim Hinzufügen oder Entfernen von Apps in einer einzigen Transaktion zu einer unvollständigen Entfernung kam.

- Der Office-Host stürzte in Windows ab, wenn ein Add-In aktiviert wird, während der Registrierungsschlüssel HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth auf Null gesetzt ist. Diese Änderung würde das Problem beheben.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-may-12"></a>Version 2002: 12. Mai
*Version 2002 (Build 12527.20612)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme

### <a name="excel"></a>Excel

- Das Öffnen einer Arbeitsmappe mit Verweisen auf zahlreiche andere Arbeitsmappen, insbesondere mit versteckten Fenstern, würde langsamer als erwartet ablaufen.

- Das Öffnen von CSV-Dateien dauerte unter bestimmten Umständen länger als erwartet.

- Excel stürzt möglicherweise unter bestimmten Umständen ab, wenn zwischen den Arbeitsmappen mit anderen Zoomstufen gewechselt wird.

- Es wurde ein Problem mit VBA behoben, bei dem das Schreiben von Werten in einem Wertebereich langsamer als erwartet war.

- Daten, die aus einer nach Farbe gefilterten Spalte kopiert wurden, werden manchmal nicht ordnungsgemäß eingefügt.

- Ein Problem wurde behoben, bei dem Excel in manchen Fällen abstürzte, nachdem ein Blatt mit einer PivotTable kopiert wurde.

- In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.

- Es wurde ein Problem behoben, bei dem die Eigenschaft "Wert wird überschneidet bei" auf der Diagrammachse unerwartet geändert wird, wenn Sie eine Datei speichern und erneut öffnen.

- Die Verwendung von Range.Value und Range.Value2 (VBA) würde dazu führen, dass Formeln als dynamische Arrays eingegeben werden.

### <a name="onenote"></a>OneNote

- Lokalisiert die Benachrichtigung, durch die der Benutzer mehr über temporäre Maßnahmen erfahren kann, die in der OneNote-Benutzeroberfläche implementiert sind, um die Synchronisierungs- und Dienststabilität zu verbessern.

- Zeigt eine Benachrichtigung an, durch die der Benutzer mehr über temporäre Maßnahmen erfahren kann, die in der OneNote-Benutzeroberfläche implementiert sind, um die Synchronisierungs- und Dienststabilität zu verbessern.

- Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehendes verringern der Anzahl und Häufigkeit der Synchronisierungen von Seiten des Versionsverlaufs in OneNote 2016.

- Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehende Deaktivierung des Papierkorbs in OneNote 2016. Wenn ein Benutzer versucht, die Daten zu löschen, die normalerweise in den Papierkorb verschoben werden, wird der Benutzer gefragt, ob er die Daten beibehalten oder dauerhaft löschen möchte.

- Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehende Anpassung der Synchronisierungshäufigkeit in OneNote 2016.

- Verbesserte Synchronisierungs- und Dienststabilität durch vorübergehendes zurückschieben des Downloads eingebetteter Dateien und Bilder in Online-Notizbücher, bis der Benutzer zu der Seite in OneNote 2016 navigiert.

- Verbesserte Synchronisierungs- und Servicestabilität durch vorübergehende Deaktivierung der Videoaufzeichnung in der Anwendung in OneNote 2016. Lokale Notizbücher sind von dieser Maßnahme nicht betroffen.

- Verbesserte Synchronisierungs- und Servicestabilität durch vorübergehende Reduzierung der maximal zulässigen Größe neuer eingebetteter Anhänge auf 50 MB in OneNote 2016. Bei Dateien, die dieses Limit überschreiten, haben Benutzer die Möglichkeit, die Datei auf OneDrive hochzuladen und einen Link in OneNote einzufügen.

### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, bei dem die Breite des Ordnerbereichs unerwartet geändert wurde.

- Es wurde ein Problem behoben, das bewirkt, dass Benutzer beim Öffnen von .msg- und .oft-Dateien nach einem Windows-Update einen Absturz erfahren.

- Behebt ein Problem, das dazu führte, dass Benutzer beim Weiterleiten großer HTML-Nachrichten den Nachrichtentext abgeschnitten sahen.

- Dieses Update behebt ein Problem, bei dem Microsoft Outlook beim Anzeigen oder Verfassen von Nachrichten nicht die aktuelle Vertraulichkeitskennzeichnung anzeigt.

- Es wurde ein Problem behoben, aufgrund dessen Benutzer nicht in der Lage waren, E-Mails an eine persönliche Verteilerliste zu senden.

### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem mit der Weiterleitung von korrekten Nachrichten für Benutzer behoben, die eine Kopie einer Datei mit verbesserten Kommentaren öffnen.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem Access und Publisher nicht ordnungsgemäß gestartet werden, je nachdem, welche Sprachen installiert wurden.

- Es wurde ein Problem mit der compare-Funktion für Dokumente behoben, die für die Bearbeitung geschützt waren.

- Es wurde ein Problem beim Zusammenführen von 2 Dokumenten in ein Dokument behoben.

### <a name="office-suite"></a>Office-Suite

- Diese Behebung soll sicherstellen, dass die Projektanwendung das Netzwerk nicht blockiert, wenn die Datei im Cache des Clients gespeichert wird.

- Das Problem wurde behoben, bei dem ein interner Vorgang bei einem Fehler eine Ausnahme ausgelöst hat, anstatt diesen zu protokollieren und fortzufahren. Die betroffenen Benutzer werden nicht mehr daran gehindert, Updates zu erhalten.

- Dadurch wird sichergestellt, dass skizzierte Konturen im Menüband ordnungsgemäß funktionieren.

- Es wurde ein Problem beim Öffnen von Dateien von lokalen Standorten aus mit einigen bestimmten Proxykonfigurationen behoben.

- Dieses Update behebt ein Problem in Visual Basic for Applications in Microsoft Office, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung beim Laden als fehlerhaft angesehen werden.

- Das Update behebt ein Problem in Microsoft Office, bei dem Visual Basic for Applications-Projekte mit Referenzen, die bei der Suche nach in der PATH-Umgebungsvariable angegebenen Speicherorten gefunden werden sollen, zur Laufzeit möglicherweise nicht richtig gefunden werden, was zu VBA-Laufzeitfehlern führt.

- Dieses Update behebt ein Problem in Microsoft Word, bei dem Text, der länger als 255 Zeichen ist, während die Anwendung einer Vertraulichkeitskennzeichnung eingefügt wird, später nicht identifiziert und entfernt werden konnte, wenn die Kennzeichnungsrichtlinie eine Kopf- oder Fußzeile oder ein Wasserzeichen angewendet hat.

- Es wurde ein Problem behoben, durch das Abstürze während der Office-Übergabesitzungen eliminiert, und es wurde die Zuverlässigkeit der Benutzeroberfläche erhöht.  

- Dieser Fehler aktualisiert den Enhanced Configuration Service (ECS). Das Aufrufen von diesem neueren Endpunkt aus hat eine höhere Erfolgsrate für den Abruf aus ECS.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-april-14"></a>Version 2002: 14. April
*Version 2002 (Build 12527.20442)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt


### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Eingeben einer Formel, die mehrere Werte zurückgibt** Schnell eine Formel eingeben, die mehrere Werte zurückgibt, und diese werden automatisch in die benachbarten Zellen übertragen. [Weitere Informationen](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- **Sechs leistungsfähige Funktionen:** Wir haben sechs neue Funktionen hinzugefügt, um Ihre Tabellenkalkulationen aufzuladen: FILTERN, SORTIEREN, SORTIERENNACH, EINDEUTIG, SEQUENZ und ZUFALLSMATRIX.  [Weitere Informationen](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- **Ein Blick nach links, ein Blick nach rechts... XVERWEIS ist da!:** Zeile für Zeile finden Sie mit XVERWEIS alles, was Sie in einer Tabelle oder einem Bereich benötigen.  
  [Weitere Informationen](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Excel stürzt in bestimmten Fällen ab, wenn eine in Word oder PowerPoint eingebettete Arbeitsmappe erneut geöffnet wird.

- Beim Speichern als CSV-Datei hat Excel in einigen Fällen alle Spalten in einer einzigen Spalte zusammengeführt.

- Die Verwendung von Range.ClearContents für einen Bereich auf einem geschützten Blatt hat möglicherweise länger gedauert als erwartet.

- Es wurde ein Problem beim Skalieren von Text in Steuerelementen von Formularen beim Anzeigen in der Druckansicht behoben.

- VBA-Makros, die mit dem Menüband interagieren, können möglicherweise mit ScreenUpdating unerwartet auf „Wahr“ festgelegt werden.

- Es wurde ein Problem behoben, bei dem externe Links beim Füllen(abwärts füllen, übergreifend füllen usw.) nicht aktualisiert wurden, wenn das Quellbuch geschlossen war.

- Die Verwendung des VBA-Befehls Application.Evaluate funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.

- Es wurde ein Leistungsproblem beim Erstellen von Diagrammen aus Vorlagen behoben.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, das dazu führte, dass die Kopfzeile einer Gruppe in einigen Szenarios unerwartet erweitert wurde.

- Es wurde ein Problem behoben, bei dem es zu einem Absturz kam, wenn Benutzer bestimmte Ergebnisse ausgewählt haben.

- Es wurde ein Problem behoben, das gelegentlich zu einem Absturz führte, wenn Benutzer den X-Knopf ihrer Maus verwendeten.

- Es wurde ein Problem behoben, das bewirkt hat, dass die Schaltfläche „In der Cloud speichern“ in den Tools für Anlagen fehlte.

### <a name="powerpoint"></a>PowerPoint

- Verbessertes Szenario zum Kopieren und Einfügen: Das Kopieren der Form in eine PowerPoint-Folie und das Einfügen in eine andere Folie in einer Schleife schlägt möglicherweise mit Ausnahme fehl.


### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem Project beim Speichern von Projekten, die mit älteren Project-Versionen erstellt wurden, möglicherweise abstürzt.

- Ein Problem wurde behoben, bei dem das Ereignis „ProjectBeforeTaskChange“ nichts erkennt, wenn ein Vorgang über die Schaltfläche „Deaktivieren“ deaktiviert/aktiviert wurde.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, das gelegentlich zu einem Absturz führte, wenn Benutzer den X-Knopf ihrer Maus verwendeten.

- Es wurde ein Problem mit der Anpassung von Text in einer Tabelle behoben.

- Ein Problem wurde behoben, damit eingefügte horizontale Linien nicht kürzer und zentriert sind.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-march-10"></a>Version 2002: 10. März
*Version 2002 (Build 12527.20278)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="access"></a>Access

- **Schnelle Suche nach verknüpften Tabellen:** Unser neues Suchfeld macht die Suche nach verknüpften Tabellen zu einem Kinderspiel. [Weitere Informationen](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a>Excel

- **Ziehen Sie die Aufmerksamkeit mit \@Erwähnungen** auf sich: Verwenden Sie @Erwähnungen in Kommentaren, um Kollegen wissen zu lassen, wann Sie ihr Feedback benötigen. [Weitere Informationen](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Finden Sie, wonach Sie suchen:** Suchen Sie Befehle, Personen, Dateien, Fotos, Webartikel und mehr. [Weitere Informationen](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- **Zeichnen Sie es auf:** Verleihen Sie Office-Shapes in Ihrer Arbeitsmappe ein ungezwungenes, von Hand gezeichnetes Aussehen. [Weitere Informationen](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.

- **Keine Umleitung zum Browser mehr:** Sie legen fest, wie Links zu Office-Dokumenten geöffnet werden: im Browser oder in der App.

- **Konzentrieren Sie sich darauf, was noch erledigt werden muss:** Wählen Sie "Auflösen" aus, um Kommentare zu reduzieren und offene Punkte hervorzuheben.

- **Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten. [Weitere Informationen](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.

- **Add-In „Datenschnellansicht“:** erstellen Sie schnell Visio-Flussdiagramme aus Excel. [Weitere Informationen](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- **Schnell lesen und antworten:** Antworten Sie auf Kommentare und Erwähnungen direkt aus dem E-Mail-Bereich, ohne die Arbeitsmappe zu öffnen.

- **Statistiken für Ihre Arbeitsmappe abrufen:** Arbeitsmappenstatistiken bieten einen Überblick über den Inhalt einer Arbeitsmappe, um Ihnen das Erkunden des Inhalts zu erleichtern.

- **Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt. Sie finden diese unter "Einfügen" > "Symbole". [Weitere Informationen](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a>Outlook

- **Verbinden Ihres LinkedIn-Netzwerks mit Outlook:** Stellen Sie eine sichere Verbindung zwischen Ihrem LinkedIn-Konto und Ihrem Microsoft-Konto her, um Informationen aus LinkedIn-Profilen direkt auf der Karte mit Ihren Kontakten anzuzeigen. [Weitere Informationen](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- **Alle Verschlüsselungsoptionen an einem zentralen Ort:** Gehen Sie einfach zu Optionen > Verschlüsseln, um auszuwählen, wie Ihre E-Mail-Nachricht gesichert wird. [Weitere Informationen](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)

- **Das Menü „Link einfügen“ in Outlook fügt einen Link mit der vom Mandantenadministrator festgelegten Berechtigung ein:** Ein Link aus dem Link-Einfügen-MRU in Outlook fügte einen Link ein, der nur für diejenigen Benutzer funktionierte, die bereits eine Berechtigung besaßen. Dies führte häufig zu E-Mail-Nachrichten zwischen Benutzern, die den Zugriff auf ein Dokument anforderten. Wir haben diese Erfahrung aktualisiert, sodass der Link jetzt mit der vom Mandantenadministrator festgelegten Standardberechtigung eingefügt wird. Für MSIT ist dies "Organisation kann bearbeiten", sodass alle internen Benutzer, die einen auf diese Weise freigegebenen Link erhalten, darauf zugreifen können.

- **Suchen bei Rechtschreibschwierigkeiten oder mit Tippfehlern:** Outlook wird auch dann finden, was Sie suchen, wenn Sie sich verschreiben.

- **Phishing-E-Mails sind jetzt leicht zu erkennen:** Spam- und Phishing-E-Mails haben ein anderes Aussehen und Verhalten, sodass Sie sie leichter identifizieren und aus Ihrem Posteingang entfernen können.

- **Erweiterter Schutz gegen Angriffe:** Mit Office 365 Advanced Threat Protection sind Sie vor Angriffen durch Links in E-Mail-Betreffzeilen, angefügten Nachrichten, signierten Nachrichten, Netzwerkpfaden usw. geschützt.

- **Müheloses Zeichnen und Signieren:** Kritzeln Sie über die Bilder, oder fügen Sie einen Zeichenbereich hinzu, um Ihren Gedanken als Freihandnotizen Ausdruck zu verleihen. [Weitere Informationen](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- **Finden Sie relevante Nachrichten in Ihren Suchergebnissen:** Outlook analysiert Suchbegriffe und zeigt die wichtigsten E-Mail-Nachrichten am Anfang der Suchergebnisse an. Außerdem sehen Sie alle Ergebnisse sortiert nach Datum im Abschnitt „Top-Ergebnisse“. [Weitere Informationen](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- **Erhalten Sie Ortsvorschläge:** Beginnen Sie beim Planen von Terminen und Besprechungen mit der Eingabe im Feld „Ort“, so schlägt Outlook Räume, Adressen und andere zuletzt verwendete Orte vor. [Weitere Informationen](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- **Mehr Nachrichten am Bildschirm anzeigen:** Wählen Sie "Anzeigen" > Engere Abstände verwenden, um die Abstände zwischen den Nachrichten anzupassen. [Weitere Informationen](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- **Sehen Sie Ihre Nachrichten in einem neuen Licht:** Verwenden Sie die Sonne/Mond-Schaltfläche, um im Lesebereich zwischen hellem und dunklem Hintergrund zu wechseln. [Weitere Informationen](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- **Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt. Sie finden diese unter "Einfügen" > "Symbole". [Weitere Informationen](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a>PowerPoint

- **Schnelle Zusammenarbeit in Echtzeit in PowerPoint:** Schnelle Zusammenarbeit in Echtzeit in PowerPoint

- **Neue Tools zum Korrekturlesen:** Machen Sie sich keine Sorgen mehr über Ihre Texte. PowerPoint bietet jetzt Grammatik- und Textvorschläge. [Weitere Informationen](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- **Live-Beschriftungen und -Untertitel:** die Worte des Referenten werden automatisch als Beschriftungen oder Untertitel in der von Ihnen gewünschten Sprache auf dem Bildschirm angezeigt. [Weitere Informationen](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- **Sie berechnen, wir formatieren:** Von Hand gezeichnete mathematische Ausdrücke werden in Standardzeichen umgewandelt. Wählen Sie einfach "Freihand in Gleichung" und Ihre handschriftlichen Notizen aus, um loszulegen. [Weitere Informationen](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Finden Sie, wonach Sie suchen:** Verwenden Sie das Suchfeld, um Text, Befehle, Hilfe und mehr zu finden. [Weitere Informationen](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **Suchen und Beheben von fehlenden Folientiteln:** Folientitel verleihen Ihrem Pitch mehr Nachdruck und machen Ihre Folien für Benutzer mit unterschiedlichen Fähigkeiten zugänglich. Die Barrierefreiheitsprüfung zeigt Ihnen, wo Titel fehlen, damit Sie diese schnell hinzufügen können. [Weitere Informationen](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- **Zeichnen Sie es auf:** Verleihen Sie Office-Shapes in Ihrer Präsentation ein ungezwungenes, von Hand gezeichnetes Aussehen. [Weitere Informationen](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.

- **Keine Umleitung zum Browser mehr:** Sie legen fest, wie Links zu Office-Dokumenten geöffnet werden: im Browser oder in der App.

- **Speichern einer Illustration als SVG:** Speichern Sie ein Diagramm, eine Form oder eine andere Abbildung als skalierbare Vektorgrafik, deren Größe ohne Verlust der Bildqualität geändert werden kann. [Weitere Informationen](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **Drucken von Foliennummern auf Handzetteln:** Foliennummern werden automatisch in Ihre Handzettel integriert. Sie können diese Funktion an- oder abschalten, wie es Ihnen beliebt. [Weitere Informationen](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- **Wiedergabe von animierten Freihandzeichnungen:** Wenn Sie Freihandeingaben auf Ihren Folien vornehmen, können Sie auf diese Freihandeingaben Replay-Animationen anwenden, um den eigentlichen Zeichenvorgang während der Bildschirmpräsentation wiederzugeben. [Weitere Informationen](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- **Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten.

- **Optimieren Sie Ihre Präsentation für alle:** Die Barrierefreiheitsprüfung hilft Ihnen beim Anordnen von Objekten auf Ihren Folien, indem sie die Sprachausgabe berücksichtigt.

- **Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.

- **Eine sicherere Video-Umgebung:** Security-Verbesserungen bedeuten für Sie eine sicherere Online-Video-Umgebung.

- **Warum neu erstellen, wenn Sie etwas wiederverwenden können?** Sparen Sie Zeit, indem Sie Folien, die Sie erstellt haben oder die andere für Sie freigegeben haben, erneut verwenden. [Weitere Informationen](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- **Ändern der handschriftlichen Freihandeingabe in Formen, Text oder Mathematik in PowerPoint für Office 365:** Wechseln Sie mit wenigen Strichen von der Freihandeingabe zu Office-Formen, Text oder einem mathematischen Ausdruck. [Weitere Informationen](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Erstellen Sie eine hervorragende Folie:** Konvertieren Sie die Freihandfunktion in Standard-Shapes und Text, und klicken Sie erhalten intelligente Foliendesign-Ideen von PowerPoint-Designer. [Weitere Informationen](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- **Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt. Sie finden diese unter "Einfügen" > "Symbole". [Weitere Informationen](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a>Visio

- **Zurück zum Tatort:** Verwenden Sie die neuen Schablonen "Beweismittel", "Drinnen" und "Draußen" der Vorlage "Tatortermittlung", um Tatorte im Detail nachzustellen.

- **Erstellen Sie ansprechende Visio-Diagramme in Excel:** Erstellen Sie ein Flussdiagramm oder ein Organigramm durch Einfügen von Daten in ein Arbeitsblatt. [Weitere Informationen](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **Lebenslauf-Editor-Verknüpfung mit dem LinkedIn-Lebenslauf-Assistent:** Der Lebenslauf-Editor bietet eine Auswahl an Grammatik- und Stilprüfungen, die speziell auf Lebensläufe zugeschnitten sind, um Ihr Schreiben präziser und professioneller zu gestalten.

- **Es wurde ein Problem mit beschädigten Dokumenten behoben, das durch das Zusammenführen von 3D-Objekten verursacht wurde.** Es wurde ein Problem mit beschädigten Dokumenten behoben, das durch das Zusammenführen von 3D-Objekten verursacht wurde.

- **Finden Sie, wonach Sie suchen:** Verwenden Sie das Suchfeld, um Text, Befehle, Hilfe und mehr zu finden. [Weitere Informationen](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **Zusammenarbeit in lebendigen Farben:** Kommentare und Änderungen sind nach Verfasser farblich gekennzeichnet, sodass Sie die einzelnen Mitwirkenden leichter unterscheiden können.

- **Makrofähige Dokumente gemeinsam bearbeiten:** Speichern Sie Ihre Dokumentdateien auf OneDrive for Business, und bearbeiten Sie sie mit anderen in Echtzeit.

- **Verbesserungen bei der gemeinsamen Dokumenterstellung**: verbesserte Leistung von Word bei der gemeinsamen Dokumenterstellung mit nachverfolgbaren Änderungen.

- **Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt. Sie finden diese unter "Einfügen" > "Symbole". [Weitere Informationen](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- **Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.

- **Zeichnen Sie es auf:** Verleihen Sie Office-Shapes in Ihrem Dokument ein ungezwungenes, von Hand gezeichnetes Aussehen. [Weitere Informationen](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Präzises Löschen:** Wählen Sie aus zwei Radierergrößen aus, um kleine Unvollkommenheiten zu beheben. [Weitere Informationen](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.

- **Keine Umleitung zum Browser mehr:** Sie legen fest, wie Links zu Office-Dokumenten geöffnet werden: im Browser oder in der App. [Weitere Informationen](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- **Verbesserungen bei der gemeinsamen Dokumenterstellung:** Verbesserte Zuverlässigkeit bei der gemeinsamen Dokumenterstellung.

- **Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten. [Weitere Informationen](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.

- **Eine sicherere Video-Umgebung:** Security-Verbesserungen bedeuten für Sie eine sicherere Online-Video-Umgebung. [Weitere Informationen](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Zugriff

- Mit diesem Update wird ein Problem in Microsoft Access behoben, das den Fehler "Abfrage ist beschädigt" verursachen kann, wenn eine Aktualisierungsabfrage ausgeführt oder eine UPDATE-Anweisung in SQL verwendet wird.

- Dieses Update behebt ein Problem, das dazu führen kann, dass Microsoft Access eine Identitätsspalte in einer verknüpften SQL-Server-Tabelle nicht identifiziert, was dazu führen kann, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.

- Dieses Update behebt ein Problem bei der Verwendung einer ADODB. Das Recorder-Objekt in VB-Code kann fälschlicherweise einen Fehler melden.

- Access-Vorlagen sollten nicht länger dazu führen, dass Anhangsspalten in einer Datenbank fehlschlagen. Nachdem Sie eine Vorlage instanziiert haben, sollten Sie nun in der Lage sein, Ihrer Datenbank ein Anhangsfeld hinzuzufügen.

### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, aufgrund dessen bei Benutzern Abstürze beim Umbenennen einer Signatur auftraten.

- Diese Änderung umgeht ein Problem mit bestimmten Intel-Grafiktreibern durch Verwendung des Softwarerenderings.

- Es wurde ein Problem behoben, durch das bei einigen Benutzern Abstürze auftraten, wenn Text in Spalten mit Zellen mit einem übergelaufenem Array konvertiert wurde.

- Dieses Update behebt ein Problem, das dazu führte, dass die Bearbeitungsleiste Text in einer anderen Schriftart als erwartet anzeigte.

- Die Funktion "Text in Spalte" funktioniert bei einigen Gebietsschemas möglicherweise nicht.

- Beim Zugriff auf einen verborgenen benannten Bereich kann ein Fehler auftreten.

- Nutzer können beim Speichern von Änderungen auf einen Fehler stoßen, wenn sie manche nicht englische Zeichensätze verwenden.

- Wir haben ein Problem gelöst, durch das das Auswählen einer Zelle nach dem Scrollen dazu führen konnte, dass die falsche Zelle ausgewählt wurde.

- In Excel kann ein Problem auftreten, durch das das Bearbeiten einer geschützten Datei von einer nicht vertrauenswürdigen Netzwerkfreigabe zu einem Fehler in Excel führt.

- Die Funktion "Text in Spalte" funktioniert bei einigen Lokalisierungen möglicherweise nicht.

- Beim Zugriff auf einen verborgenen benannten Bereich kann ein Fehler auftreten.

- Beim Speichern von Änderungen bei der Verwendung einiger nicht englischer Zeichengruppen tritt möglicherweise ein Fehler auf.

- Es wurde ein Problem behoben, das bei einigen Benutzern mit verknüpften und eingebetteten Objekten (OLE) auftrat.

- Das Kontextmenü für PivotCharts wurde korrigiert, um die Option "Details anzeigen" zu aktivieren.

- Es wurde ein Problem behoben, das bei der Suche nach zuletzt verwendeten Dateien zu einem Absturz geführt hat, wenn keine Arbeitsmappe geöffnet ist.

- Es wurde ein Problem behoben, durch das einigen Benutzern mehrere Popupfenster angezeigt wurden, wenn externe Links in der Arbeitsmappe vorhanden waren.

- Es wurde ein Problem behoben, bei dem Kommentarbefehle im Kontextmenü nicht angezeigt wurden.

- Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.

- Ein Problem wurde behoben, bei dem CUBEWERT-Funktionen manchmal ein falsches Ergebnis zurückgaben.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, durch das die Such-Feedback-Umgebung zum Hängen gebracht wurde.

- Es wurde ein Problem behoben, das dazu führte, dass Benutzer in Outlook beim Abrufen von Cloudeinstellungen hängen bleiben.

- Es wurde ein Problem behoben, das dazu führte, dass das Suchfeld im Modus mit hohem DPI-Wert nicht korrekt ausgerichtet war.

- Ein Problem wurde behoben, durch das Benutzer einen Speicherverlust im Outlook-Prozess beobachten konnten.

- Es wurde ein Problem behoben, durch das Benutzern unter bestimmten Umständen E-Mails angezeigt werden, die an eine Adresse gesendet wurden, die nicht mit der angezeigten SMTP-Adresse übereinstimmt.

- Diese Änderung stellt die Fähigkeit wieder her, mehrzeilige Betreffzeilen im Nachrichtenkopf anzuzeigen.

- Es wurde ein Problem behoben, durch das verhindert werden konnte, dass Dateien an einem WebDAV-Speicherort gespeichert wurden.

- Es wurde ein Problem mit der Auswahl des SMIME-Algorithmus behoben.

- Ein Problem wurde behoben, durch das Anwendungen von Drittanbietern keine E-Mail-Nachrichten mehr senden konnten.

- Es wurde ein Problem behoben, das bewirkt hat, dass Benutzer ein leeres Meldungsfeld mit einer "OK"-Schaltfläche angezeigt bekamen, wenn Sie versuchten, den Support über den Kontext der Kontoerstellung zu kontaktieren.

- Ein Problem wurde behoben, das während der Profilerstellung ein Absturz verursachte.

- Ein Problem wurde behoben, das dazu führte, dass Outlook unerwartet alle E-Mails synchronisierte, selbst wenn der Synchronisierungsschieberegler auf eine kleinere Einstellung eingestellt ist.

- Ein Problem wurde behoben, das dazu führte, dass für Benutzer mit dem schwarzen Design die Dropdownliste „Von“ als weißer Text auf weißem Hintergrund angezeigt wurde.

- Es wurde ein Problem behoben, bei dem es durch das Abbrechen der Kontoeinrichtung einen Absturz gab.

- Es wurde ein Problem behoben, aufgrund dessen bei Benutzern Abstürze beim Umbenennen einer Signatur auftraten.

- Es wurde ein Problem behoben, durch das die Option zum Deaktivieren der Hervorhebung markierter Elemente in einigen Szenarien nicht berücksichtigt wurde.

- Es wurde ein Problem behoben, durch das Benutzern eine beim Öffnen des Dialogfelds "Regeln" die folgende Meldung "Die Regeln auf diesem Computer stimmen nicht mit den Regeln in Microsoft Exchange überein" angezeigt wurde.

- Es wurde ein Problem behoben, bei dem beim Angeben einer ungültigen Absenderadresse ein Absturz verursacht wurde.

- Es wurde ein Problem behoben, das einen Speicherverlust bei sehr langen Outlook-Sitzungen verursachte.

- Ein Problem wurde behoben, das zu einem Absturz führen könnte, wenn dasselbe Element in mehreren Fenstern angezeigt wird.

- Es wurde ein Problem behoben, durch das Benutzer mit einer spürbaren Verzögerung beim Interagieren mit ihren Postfachordnern über Tastenkombinationen konfrontiert waren.

- Ein Problem wurde behoben, durch das Benutzer einige Instanzen von wiederkehrenden Kalenderelementen nicht öffnen konnten.

- Es wurde ein Problem behoben, das bei Benutzern mit Postfächern auf Exchange 2010-Servern zu Problemen beim Hinzufügen von Anlagen zu Kalendereinträgen führte.

- Es wurde ein Problem behoben, durch das Benutzer Probleme beim Beantworten digital signierter Nachrichten hatten.

- Es wurde ein Problem behoben, durch das das Feld "Ort" in Besprechungen unerwartet aktualisiert wurde.

- Es wurde ein Problem behoben, das dazu führte, dass Kommas im Ortsfeld einer Besprechung in Semikolons umgewandelt wurden.

- Es wurde ein Problem behoben, bei dem der Standort einer Besprechung unerwartet nach dem Löschen wieder der Besprechung hinzugefügt wurde.

- Es wurden Probleme im Zusammenhang mit in der brasilianischen Zeitzone festgelegten Sitzungen und Terminen behoben.

- Ein Problem wurde behoben, durch das beim Drücken der Taste „S“ nach dem Schließen der Barrierefreiheitsprüfung unerwartet E-Mails gesendet wurden.

- Hiermit wird die Blockierungslogik für Anlagen in Outlook aktualisiert, um auch Python-Anlagen zu blockieren.

- Ein Problem wurde behoben, durch das Web-Add-Ins auf von Digital Rights Management verwaltete Nachrichten zugreifen konnten.

- Ein Problem wurde behoben, das während der Profilerstellung ein Absturz verursachte.

- Es wurde ein Problem behoben, aufgrund dessen bei Benutzern Abstürze beim Umbenennen einer Signatur auftraten.

### <a name="powerpoint"></a>PowerPoint

- Ein Problem mit der Shape.Paste-Methode wurde behoben: Wenn der Benutzer die Form mit der Shape.Paste-Methode kopiert und einfügt, wird die Auswahl in die eingefügte Form geändert.

- Es wurde ein Problem behoben, das bei der Verwendung des Kontextmenüs in älteren PPT-Kommentaren zu einem Absturz führen könnte.

### <a name="project"></a>Project

- Ein Problem wurde identifiziert, bei dem Benutzer beim Öffnen eines schreibgeschützten Projekts möglicherweise mehrere Meldungen erhielten.

- Es wurde ein Problem behoben, bei dem 100% Aufgaben vom Typ "feste Dauer" fälschlicherweise zu weniger als 100% erledigt wurden.

- Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.

- Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.

### <a name="word"></a>Word

- Ein Problem wurde behoben, bei dem das Speichern einer vorhandenen Datei in einigen Fällen das Dialogfeld "Speichern unter" aufruft und die Datei nie wirklich gespeichert wird.

- Im Organizer für Bausteine könnte eine ungültige Warnung angezeigt werden: “Sie haben modifizierte Formen, Bausteine“.

### <a name="office-suite"></a>Office-Suite

- Diese Änderung betrifft die langsame Darstellung einiger Streudiagramme mit Markierungen.

- Diese Änderung behebt gemeldete Probleme mit Grafikadaptern, die die integrierte Intel-GPU nutzen.

- Ein Fehler in der Einstellung des Stichtags für ODT- und GPO-Updates wurde behoben, bei dem der relative Stichtag nur beim ersten Festlegen funktionierte. Der Fix aktiviert den relativen Stichtag für spätere Updates.

- Es wurde ein Problem behoben, bei dem Office-Aktualisierungen möglicherweise unerwartet Dateien aus dem Office CDN anstelle der beabsichtigten Quelle heruntergeladen haben, beispielsweise eine lokale oder Netzwerkfreigabe oder einen vom Configuration Manager bereitgestellten Speicherort.

- Ein Problem wurde behoben, das dazu führte, dass beim Öffnen mehrerer Dokumente in Word/Excel/PowerPoint aus derselben SharePoint-Bibliothek lediglich das erste geöffnete Dokument auf Richtlinienkonformität gescannt wurde.

[//]: # (BUGDETAILS NICHT AM INHALTSENDE ENTFERNEN)

## <a name="version-1908-february-11"></a>Version 1908: 11. Februar
*Version 1908 (Build 11929.20606)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Dieses Update behebt ein Problem, das dazu führte, dass ein Fehler auftrat, wenn VBA zum Hinzufügen eines Bildes zur Kopf-/Fußzeile eines Diagramms verwendet wurde.

- Es wurde ein Problem behoben, bei dem der Rand eines Gruppenfeld-Steuerelements in der Druckvorschau oder beim Drucken nicht sichtbar war.

- Nutzer können beim Speichern von Änderungen auf einen Fehler stoßen, wenn sie manche nicht englische Zeichensätze verwenden.

- Es wurde ein Problem behoben, durch das die Dateigröße von Bildern in Diagrammkopfzeilen beim Speichern der Arbeitsmappe mit dem Diagramm zunahm.


- Es wurde ein Problem behoben, das zur Beschädigung von DBCS-Zeichen in Büchern mit Querverweisen führte, indem die Auswahlbereiche mit dem Buch mit Querverweisen synchronisiert wurden.

- Es wurde ein Problem behoben, das dazu führen konnte, dass Kontrollkästchen bei Verwendung der automatischen Anpassung zum Anpassen der Zeilenhöhe verkleinert wurden.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem beim Angeben einer ungültigen Absenderadresse ein Absturz verursacht wurde.

- Es wurde ein Problem behoben, bei dem Nutzer bei der Verarbeitung von Konfliktnachrichten Synchronisierungsfehler hatten.

- Es wurde ein Problem behoben, bei dem Nutzer beim Starten von Outlook beim Laden des Profils auf dem Bildschirm "Laden von Profilen" hängen blieben.

- Es wurde ein Problem behoben, durch das Nutzer beim Ändern von Ansichten zeitweise Abstürze sehen konnten.


- Es wurde ein Problem behoben, bei dem beim Anzeigen von mehr als 30 Kalendern in einer Citrix-Umgebung ein Absturz verursacht wurde. [Hier](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) ist die einzelne KB, in der dies für frühere Versionen dokumentiert wurde.

- Behebt ein Problem, bei dem Nutzer Probleme mit der Synchronisierung freigegebener Kalenderordner mit dem OST hatten, was zu Berechtigungsfehlern führte, wenn sie versuchten, mit diesen Ordnern zu interagieren.


### <a name="powerpoint"></a>PowerPoint

- Verbessertes Szenario zum Kopieren und Einfügen Das Kopieren der Form in eine PowerPoint-Folie und das Einfügen in eine andere Folie in einer Schleife schlägt möglicherweise mit Ausnahme fehl.


- Es wurde ein Problem behoben, das zu einer langsameren Leistung zwischen Nutzern, die zusammenarbeiten, führte.

- Es wurde ein Problem behoben, das auftreten konnte, wenn eine Datei, die inkrementell geöffnet wurde, eine Folie mit mehr als einem eingebetteten Mediendatenstrom enthielt.

- Wir haben ein Problem behoben, bei dem beim ersten Start von PowerPoint möglicherweise keine Sicherheitswarnmeldung für nicht vertrauenswürdige Add-Ins angezeigt wird.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem die tatsächliche Arbeit zwischen Arbeitszeittabelle und Projektplan unterschiedlich sein kann, da Ressourcenkalender nicht aktualisiert werden, wenn sich der Basiskalender ändert.

### <a name="word"></a>Word

- Ein Absturz in Word wurde behoben, indem es von einer veralteten API entfernt wurde.

### <a name="office-suite"></a>Office-Suite

- Diese Änderung behebt das korrekte Rendern von Bildern nach dem Öffnen einer beschädigten Datei.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1908-january-14"></a>Version 1908: 14. Januar
*Version 1908 (Build 11929.20562)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Die Niederländische Tastenkombination für Dokumenttitel wurde in Alt-G geändert.

- Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.

- Es gab ein Problem, bei dem Sie keine Elemente aus dem Kombinationsfeld eines WPF-Formulars (Windows Presentation Foundation) auswählen konnten, das von einem Add-n geöffnet wurde.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, durch das Benutzer mit einer spürbaren Verzögerung beim Interagieren mit ihren Postfachordnern über Tastenkombinationen konfrontiert waren.

- Es wurde ein Problem behoben, bei dem Richtlinientipps bei Verwendung eines alternativen Absenders nicht angezeigt wurden.

- Es wurde ein Problem behoben, das bei der Aktualisierung von Anwesenheitsinformationen zu zeitweiligen Abstürzen führte.

### <a name="powerpoint"></a>PowerPoint

- Wir haben ein Problem behoben, bei dem beim Kopieren einer Folie von einer Präsentation in eine andere möglicherweise doppelte Master erstellt wurden.
- Bei Dateien mit neuen modernen Kommentaren wird eine gelbe Warnung angezeigt, wenn sie in einer nicht unterstützten Version geöffnet werden.

### <a name="office-suite"></a>Office-Suite

- Es wurde ein Problem behoben, bei dem Office-Update-Nachrichten in einer anderen Sprache als erwartet angezeigt wurden. In Zukunft entsprechen Office-Update-Nachrichten ordnungsgemäß der Windows-Anzeigesprache.

- Es wurde ein Problem behoben, bei dem ein Update in bestimmten Fällen nicht installiert wurde, wenn der Benutzer kein Administrator ist und das Systemkonto keine Netzwerkverbindung hatte.



## <a name="version-1908-december-10"></a>Version 1908: 10. Dezember
*Version 1908 (Build 11929.20516)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Access

- Ein Problem wurde behoben, bei dem eine Union-Abfrage, die Verweise auf Remotetabellen enthält (z. B. SQL Server-Tabellen) möglicherweise dazu führt, dass Access geschlossen und neu gestartet wird.

- Ein Problem wurde behoben, durch das bei einem Aggregat wie "Summe" das Ergebnis auf einen ganzzahligen Wert abgeschnitten werden kann.

### <a name="excel"></a>Excel

- Ein Problem wurde behoben, durch das das Auswählen einer Zelle nach dem Scrollen dazu führen konnte, dass die falsche Zelle ausgewählt wurde.

- Ein Problem wurde behoben, bei dem der Filter für eine OLAP-PivotTable auf einen Wert festgelegt wurde, der aus dem Cube entfernt wurde.

- Diese Änderung umgeht ein Problem mit bestimmten Intel-Grafiktreibern durch Verwendung des Softwarerenderings.

- Ein Problem wurde behoben, bei dem die Verweis-Funktion einen Fehler zurückgeben kann.

- Erhebliche Verbesserungen der Leistung beim Löschen von Spalten mit verbundenen Zellen.

- Ein Problem wurde behoben, durch das ein Makro-Laufzeitfehler beim Aktivieren minimierter Fenster verursacht wurde.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem mit der Auswahl des SMIME-Algorithmus behoben.

- Es wurde ein Problem behoben, durch das Benutzer die Aufforderung &quot;die Regeln auf diesem Computer entsprechen nicht den Regeln von Microsoft Exchange&quot; beim Öffnen des Dialogfelds „Regeln“ angezeigt bekommen.

- Behebt ein Problem, durch das Web-Add-Ins auf von Digital Rights Management verwaltete Nachrichten zugreifen konnten, wenn dies nicht möglich sein sollte.

### <a name="word"></a>Word

- Ein Problem wurde behoben, durch dass beim Nachverfolgen von Änderungen der Vorgang manchmal zu einer Endlosschleife führte.

### <a name="office-suite"></a>Office-Suite

- Ein Problem wurde behoben, bei dem Katakana-Zeichen mit halber Breite in vertikalen Textfeldern in PowerPoint nicht ordnungsgemäß gedreht wurden.

- Es wurde ein Problem behoben, bei dem Office-Aktualisierungen möglicherweise unerwartet Dateien aus dem Office CDN anstelle der beabsichtigten Quelle heruntergeladen haben, beispielsweise eine lokale oder Netzwerkfreigabe oder einen vom Configuration Manager bereitgestellten Speicherort.

- Um die Sicherheit der Office-Kunden zu schützen, sind jetzt Microsoft Office-Updates ausschließlich mit dem SHA-2-Algorithmus signiert.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1908-november-22"></a>Version 1908: 22. November
*Version 1908 (Build 11929.20494)*


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme

### <a name="access"></a>Access

- Ein Problem wurde behoben, bei dem das Ausführen einer Aktualisierungsabfrage fälschlicherweise die Fehlermeldung lieferte: "Anfrage ist beschädigt" 

### <a name="excel"></a>Excel

- Problem mit langsamer Leistung beim Klicken auf die Schaltfläche "Schriftfarbe", wenn eine Datei über eine umfangreiche bedingte Formatierung verfügt.

- Ein Problem wurde behoben, bei dem der Druckbereich in der Seitenansicht nicht korrekt war.

- Excel könnte ein Problem aufweisen, durch das das Bearbeiten einer geschützten Datei von einer nicht vertrauenswürdigen Netzwerkfreigabe zu einem Fehler in Excel geführt haben könnte.

- Es wurde ein Problem behoben, das bei der Suche nach zuletzt verwendeten Dateien zu einem Absturz geführt hat, wenn keine Arbeitsmappe geöffnet ist.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, das bewirkt hat, dass Benutzer ein leeres Meldungsfeld mit einer &quot;OK&quot;-Schaltfläche angezeigt bekamen, wenn Sie versuchten, den Support über den Kontext der Kontoerstellung zu kontaktieren.

- Eine Änderung wurde vorgenommen, die es Administratoren ermöglicht, eine Richtlinie zu aktivieren, um in den Eingabeaufforderungen der AutoErmittlung-Authentifizierung die bereitgestellten E-Mail-Konten vor UPN zu bevorzugen. Standardmäßig bevorzugt AutoErmittlung den UPN des Kontos, wenn dieser verfügbar ist.

- Ein Problem wurde behoben, durch das Benutzern Fehler beim Durchsuchen moderner Gruppen angezeigt wurden.

- Ein Problem wurde behoben, das einen Absturz verursachte, wenn Benutzer versuchten, aus einer &quot;Verpasste Unterhaltung&quot;-Nachricht heraus eine Regel zu erstellen.

- Ein Problem wurde behoben, durch das Benutzern Fehler beim Durchsuchen moderner Gruppen angezeigt wurden.

### <a name="word"></a>Word

- Ein Problem wurde behoben, das zu Skalierungsproblemen führen konnte, wenn auf Deskjet-Druckern gedruckt wurde.

### <a name="office-suite"></a>Office-Suite

- Ein Problem wurde behoben, um zu verhindern, dass für PowerPoint-Benutzer bei Onlinepräsentationen Fehler auftreten.

- Verbesserte Zuverlässigkeit des Office-Updateprozesses hinsichtlich der Registrierungsintegrität.

- Ein Problem wurde behoben, bei dem Updates in getakteten Netzwerken möglicherweise unerwartet blockiert wurden.

- Ein Problem in der Einstellung des Stichtags für ODT- und GPO-Updates wurde behoben, bei dem der relative Stichtag nur beim ersten Festlegen funktionierte. Der Fix aktiviert den relativen Stichtag für spätere Updates.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1908-november-12"></a>Version 1908: 12. November
*Version 1908 (Build 11929.20436)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme

### <a name="excel"></a>Excel

- Es wurde ein Problem mit Farben behoben, die in der Vorschau beim Einfügen von Diagrammen mithilfe von Diagrammvorlagen verwendet wurden.
- Ein Problem wurde behoben, durch das Punkt-/Liniendiagramme beim Ändern der Reihensammlung möglicherweise nicht ordnungsgemäß dargestellt wurden.
- Ein Problem wurde gelöst, das bei Änderung von benutzerdefinierten Eigenschaften von ausgeführten Makros zu Unterbrechungen bei der gemeinsamen Dokumentenerstellung führte.
- Ein Leistungsproblem mit asynchronen benutzerdefinierten Funktionen wurde behoben, das deren synchrone Ausführung zur Folge hatte.
- Die Leistung der Filterung nach Farbe wurde deutlich verbessert.
- Ein Problem wurde behoben, das beim Öffnen von in früheren Versionen von Office erstellten Arbeitsmappen in aktuellen Versionen von Office zu Programmabstürzen von Excel führen konnte.
- Die Links von cid:-Bildern aus Outlook-Nachrichten können nun auf Anforderung erfolgreich unterbrochen werden.

### <a name="outlook"></a>Outlook

- Die Links von cid:-Bildern aus Outlook-Nachrichten können nun auf Anforderung erfolgreich unterbrochen werden.
- Es wurde ein Problem behoben, durch das Benutzern beim Kopieren von Elementen aus Ihrem primären Kalender in einen Gruppenkalender ein Berechtigungsfehler angezeigt wird.
- Es wurde ein Problem behoben, das einen Speicherverlust bei sehr langen Outlook-Sitzungen verursachte.
- Es wurde ein Problem behoben, das bewirkt hat, dass bei der Interaktion mit bestimmten Safelinks in Outlook ein Fehler für die Benutzer auftrat.
- Es wurde ein Problem behoben, durch das für die Benutzer ein Fehler bei der Verarbeitung von AutoErmittlungsantworten auftrat.
- Ein Problem wurde behoben, durch das bei einigen Benutzern beim Hinzufügen eines sekundären Exchange-Kontos doppelte Sonderordner angezeigt wurden.
- Es wurde ein Problem behoben, durch das die Such-Feedback-Umgebung zum Hängen gebracht wurde.

### <a name="powerpoint"></a>PowerPoint

- Die Links von cid:-Bildern aus Outlook-Nachrichten können nun auf Anforderung erfolgreich unterbrochen werden.
- Zuverlässigkeitsbehebung: ein Problem wurde behoben, bei dem das Add-in von Drittanbietern einen Fehler bei PowerPoint verursachte.

### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem der Befehl „Alles abgleichen“ die Ressourcenüberlastung nicht ordnungsgemäß aufgelöst hat.
- Ein Problem wurde behoben, bei dem eine Aufgabe mit keiner Arbeit an einem Vorgang möglicherweise nicht als erledigt gekennzeichnet werden kann und stets bei 99 % angezeigt wird.
- Ein Problem wurde identifiziert, bei dem Benutzer beim Öffnen eines schreibgeschützten Projekts möglicherweise mehrere Meldungen erhielten.

### <a name="word"></a>Word

- Die Links von cid:-Bildern aus Outlook-Nachrichten können nun auf Anforderung erfolgreich unterbrochen werden.
- Verschiedene Probleme behoben, bei denen die APP beim Herunterfahren hängen bleiben könnte. Außerdem wurden bestimmte Add-In-Fehler behoben.

### <a name="office-suite"></a>Office-Suite

- Probleme im Zusammenhang mit der Anpassung der Eigenschaft „TextBox/ Form automatisch anpassen“ in Drittanbieter-Plug-ins.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="october-15"></a>15. Oktober

### <a name="non-security-updates"></a>Nicht sicherheitsrelevante Sicherheitsupdates

### <a name="office-suite"></a>Office-Suite
- Wir haben das Dialogfeld zum Speichern in der Cloud vorübergehend deaktiviert, um das Problem zu beheben, das am 14. Oktober 2019 für ältere Builds als 16.0.11929.20396 veröffentlicht wurde. Dieses Feature wird in Kürze erneut aktiviert.

## <a name="version-1908-october-14"></a>Version 1908: 14. Oktober
*Version 1908 (Build 11929.20396)*


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a>Nicht sicherheitsrelevante Sicherheitsupdates
### <a name="excel"></a>Excel

- <div>Es wurde ein Problem mit „Suchen und ersetzen“ gelöst, durch das sich die Position des Fokus im Dialogfeld änderte, nachdem das erste Element gefunden wurde.</div>

### <a name="office-suite"></a>Office-Suite

- Das Problem, bei dem Benutzer möglicherweise nicht in der Lage waren, Word-, Excel- und PowerPoint 2019-Dokumente bei älteren Builds als 16.0.11929.20396 zu speichern, wurde behoben. Dieses Problem betrifft Benutzer, die eine neue Datei erstellen und das Dialogfeld „Speichern unter“ öffnen, nachdem sie auf das Symbol „Speichern“ geklickt oder STRG+S gedrückt haben.

- Es wurde ein Problem gelöst, bei dem unter bestimmten Umständen Office-Verknüpfungen nach einem Update möglicherweise nicht mehr angezeigt wurden.  Dieses Update erhöht die Zuverlässigkeit beim Veröffentlichen von Office-Verknüpfungen.

[//]: # (BUGDETAILS NICHT ENTFERNEN INHALT ENDE)

## <a name="version-1908-october-08"></a>Version 1908: 8. Oktober
*Version 1908 (Build 11929.20388)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a>Nicht sicherheitsrelevante Sicherheitsupdates
### <a name="excel"></a>Excel

- Ein Problem wurde behoben, durch das Links in bestimmte geschützte Blätter nicht eingefügt werden konnten.

- Ein Problem wurde behoben, sodass jetzt mehr als 16 Add-Ins angezeigt werden können, wenn der Add-In-Manager durchsucht wird.

- Folgendes Problem im Feature "Excel-Ideen" wurde behoben: Ein Fehler trat auf, wenn das Add-In durch Klicken auf die Schaltfläche "Ideen" im Win32-Client geladen wurde.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, das bewirkt hat, dass die URL für den einfachen Mauszeiger bei einigen Safelinks nicht angezeigt wird.

- Die Blockierungslogik für Anlagen in Outlook wurde aktualisiert, um auch Python-Anlagen zu blockieren.

- Ein Problem wurde behoben, durch das Benutzer einen Speicherverlust im Outlook-Prozess beobachten konnten.

### <a name="powerpoint"></a>PowerPoint

- Ein Problem wurde behoben, das zu Datenverlusten in Sitzungen führen konnte, bei denen sowohl die gemeinsame Dokumenterstellung als auch die Offlinebearbeitung in PowerPoint genutzt wurde.

### <a name="office-suite"></a>Office-Suite

- Die Ursache für einen Absturz wurde gefunden und behoben, der beim Öffnen einer Datei auftreten konnte.

- Ein Problem wurde behoben, bei dem im Informationsbereich der Backstage-Ansicht keine Barrierefreiheitsinformationen angezeigt wurden.

- Die Zuverlässigkeit beim Herunterladen von Office-Updates wurde verbessert, indem Downloads fortgesetzt werden, die möglicherweise zuvor unterbrochen wurden.

- Um die Sicherheit der Office-Kunden zu schützen, sind jetzt Microsoft Office-Updates ausschließlich mit dem SHA-2-Algorithmus signiert.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1908-september-10"></a>Version 1908: 10. September
*Version 1908 (Build 11929.20300)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgelistet

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="access"></a>Zugriff

- **Mehr Platz zum Zoomen:** Vergrößern Sie das Zoomfeld, ändern Sie die Schriftart, und die Zoomfunktion merkt sich alles. [Weitere Informationen](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

- **Registerkarten für Datenbankobjekte im Blick behalten:** Erkennen Sie eindeutig die aktive Registerkarte, ordnen Sie Registerkarten durch Ziehen mit der Maus neu an, und schließen Sie Datenbankobjekte mit nur einem Klick.

- **Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an. Das Wechseln zwischen den Konten ist so einfach wie nie. [Weitere Informationen](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel"></a>Excel

- **Erfahren Sie mehr über Ihre Daten:** Die neue Schaltfläche "Ideen" sucht in Ihren Daten nach Mustern und verwendet diese, um intelligente, persönliche Vorschläge zu erstellen. [Weitere Informationen](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **Schnelle Dateisuche:** Sie suchen nach einer Datei, an der Sie kürzlich gearbeitet haben? Geben Sie einfach in das Suchfeld unter „Datei“ > „Start“ den Namen der gesuchten Datei ein.

- **Erhöhen Sie die Reichweite Ihrer Inhalte**: Möchten Sie Ihre Präsentationen barrierefrei gestalten? Die Barrierefreiheitsprüfung kann dies für Sie im Auge behalten, ohne Ihnen dabei in die Quere zu kommen. Probieren Sie es aus, indem Sie auf „Überprüfen“ > „Barrierefreiheit überprüfen“ klicken. Wir werden Sie in der Statusleiste informieren, wenn wir etwas finden, dass Sie sich ansehen müssen.

- **Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an. Das Wechseln zwischen den Konten ist so einfach wie nie. [Weitere Informationen](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Verleihen Sie Ihrem Arbeitsblatt mehr Lebendigkeit:** Fügen Sie animierte 3D-Grafiken ein, um zu sehen, wie Herzen schlagen, Planeten sich in einer Umlaufbahn bewegen und wie ein T-Rex durch die Arbeitsmappe stampft. [Weitere Informationen](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- **Zusammenarbeiten ist jetzt noch einfacher**: Verbesserungen bei der gemeinsamen Dokumenterstellung führen dazu, dass Ihre Änderungen beim Arbeiten mit bedingter Formatierung, Zellformatvorlagen und mehr nahtlos mit denen Ihrer Mitarbeiter zusammengeführt werden.

- **Verknüpfen von Tabellen in ähnlichen Spalten:** Abrufen und Transformieren (Power Query) bietet jetzt eine ungefähre Textübereinstimmungslogik (auch Fuzzyübereinstimmung genannt) beim Vergleichen von Spalten zum Zusammenführen von Tabellen. [Weitere Informationen](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- **Schnelles Programmieren mit Power Query-Verbesserungen**: Mit AutoVervollständigen und farbiger Syntax können Sie Code schnell fertigstellen. Außerdem können Sie auf einfache Weise Funktionen, Spalten und Parameter ermitteln.

- **Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können. Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben. [Weitere Informationen](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a>Outlook

- **Arbeiten während des Verschiebens von Nachrichten:** Outlook verschiebt Nachrichten nun im Hintergrund, sodass Sie weiterarbeiten können, während viele Nachrichten zwischen Ordnern verschoben werden.

- **Einbauen einer Zeitspanne zwischen unmittelbar aufeinander folgenden Besprechungen**: Geben Sie den Teilnehmern Zeit für eine Atempause und oder den Weg zwischen verschiedenen Besprechungsorten, indem Sie festlegen, dass Besprechungen standardmäßig 5–10 Minuten früher enden.

- **Benutzer können Ihre Memes einsehen:** Wenn Text oder statische Bilder einfach nicht genug sind, verwenden Sie ein animiertes GIF zur Veranschaulichung. [Weitere Informationen](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)

- **Wir haben die Outlook-Benutzererfahrung für Sie aktualisiert**: Eine vereinfachte Oberfläche, die über "In Kürze verfügbar" bereits in der Vorschau zur Verfügung stand und Ihnen helfen soll, sich auf das Wesentliche zu konzentrieren. [Weitere Informationen](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- **Ein weiteres oder engeres Layout? Sie entscheiden**: Sie können entscheiden, ob Sie zwischen Elementen mehr Abstand wünschen oder ob Sie mehr Elemente in einem engeren Layout bevorzugen.

- **Ein vereinfachtes und benutzerdefiniertes Menüband**: Genießen Sie eine optimierte, einzelne Reihe der am häufigsten verwendeten Schaltflächen. Sie können einfach zwischen klassischer und vereinfachter Ansicht sowie den Befehlen "Anheften" und "Lösen" wechseln. [Weitere Informationen](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- **Eine schnellere Methode, um Konten hinzuzufügen**: Dank der Verbesserungen beim Einrichten von Konten ist es einfacher denn je, Outlook.com- und Gmail-Konten mit zweistufiger Authentifizierung zu Outlook hinzuzufügen. [Weitere Informationen](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- **Wählen Sie Ihre bevorzugte Aktion aus:** Verwenden Sie keine Kennzeichnung und Löschung? Wie sieht es mit "Archivieren" oder "Als gelesen markieren" aus? Passen Sie das Menü mit schnellen Aktionen mit den am häufigsten verwendeten Befehlen an.

- **Verabschieden Sie sich von den Synchronisationsbeschränkungen**: Outlook-Verbesserungen bedeuten, dass die Ordnerbeschränkung aufgehoben ist, also fahren Sie fort und synchronisieren Sie Ihre gemeinsamen Postfächer.

- **Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können. Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben. [Weitere Informationen](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a>PowerPoint

- **Befragen Sie Ihr Publikum mit einem Quiz oder einer Umfrage:** Fügen Sie ein Quiz oder eine Umfrage einer Folie hinzu. Office sammelt und speichert die Antworten für Sie. [Weitere Informationen](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

- **Schnelle Dateisuche:** Sie suchen nach einer Datei, an der Sie kürzlich gearbeitet haben? Geben Sie einfach in das Suchfeld unter „Datei“ > „Start“ den Namen der gesuchten Datei ein.

- **Erhöhen Sie die Reichweite Ihrer Inhalte**: Möchten Sie Ihre Präsentationen barrierefrei gestalten? Die Barrierefreiheitsprüfung kann dies für Sie im Auge behalten, ohne Ihnen dabei in die Quere zu kommen. Probieren Sie es aus, indem Sie auf „Überprüfen“ > „Barrierefreiheit überprüfen“ klicken. Wir werden Sie in der Statusleiste informieren, wenn wir etwas finden, dass Sie sich ansehen müssen.

- **Speichern Sie Ihre Änderungen, während sie entstehen**: Laden Sie Ihre Dateien in OneDrive hoch, um sicherzustellen, dass alle Ihre Aktualisierungen automatisch gespeichert werden.

- **Das Einfügen von Onlinevideos ist jetzt einfacher denn je:** Möchten Sie auf Ihrer Folie ein Video von Vimeo oder YouTube einfügen? Hierfür benötigen Sie nur den Link zur Videoseite. [Weitere Informationen](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Bessere Formwandlung**: Geben Sie Ihren Shapes einen Namen, um mehr Kontrolle über ihr Morphen zu haben. [Weitere Informationen](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- **Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an. Das Wechseln zwischen den Konten ist so einfach wie nie. [Weitere Informationen](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Neuer Speicherort für Onlinevideos**: Speichern Sie ein Video in Microsoft Stream, damit es jeder in Ihrem Unternehmen ansehen kann. Fügen Sie den Videolink ein, und profitieren Sie von Multimediapräsentationen mit einem Bruchteil der üblichen Dateigröße. [Weitere Informationen](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können. Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben. [Weitere Informationen](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a>Project

- **Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an. Das Wechseln zwischen den Konten ist so einfach wie nie. [Weitere Informationen](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a>Visio

- **Verabschieden Sie sich von fehlerhaften Excel-Verknüpfungen:** Die Excel-Arbeitsmappe, die mit Ihrem Datenschnellansichtsdiagramms verknüpft ist, kann nicht gefunden werden? Verknüpfen Sie es erneut, und es kann weiter gehen. [Weitere Informationen](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- **Integrierte Azure Schablonen:** Entwerfen Sie eine Cloud-App, oder planen Sie eine Architektur mithilfe von Dutzenden von Azure-Schablonen. [Weitere Informationen](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- **Zweiter Blick auf Datenflussdiagramme:** Attraktive neue Layouts für Data Visualizer-Flussdiagramme sind übersichtlich, klar und einfach zu verstehen. Klicken Sie auf die Registerkarte Entwurf für weitere Optionen.

- **Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an. Das Wechseln zwischen den Konten ist so einfach wie nie. [Weitere Informationen](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Exportieren von Prozessdiagrammen nach Word:** Fügen Sie Diagramminhalte, wie Formen und Metadaten, automatisch zu einem Word-Dokument hinzu. Passen Sie dann das Dokument an, um Prozessrichtlinien und Handbücher zu erstellen. [Weitere Informationen](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- **Exportieren von Visio-Visualisierungen aus Power BI**: Die Visio-Visualisierung für Power BI wird nun ordnungsgemäß angezeigt, wenn Sie Power BI-Berichte beispielsweise als PDF-Dateien, PowerPoint-Dateien und mehr exportieren. [Weitere Informationen](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a>Word

- **Natürliche Bearbeitung mit dem Freihand-Editor:** Mit einem einzigen Strich können Sie Wörter trennen oder verbinden, eine neue Zeile hinzufügen oder Wörter mithilfe Ihres Stifts einfügen. [Weitere Informationen](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **Verwandeln Sie ihr Dokument von statisch in erstaunlich:** Verwandeln Sie Ihr Dokument in eine interaktive, einfach freizugebende Webseite, die auf jedem Gerät großartig aussieht. [Weitere Informationen](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

- **Mit \@Erwähnungen andere auf sich aufmerksam machen:** Lassen Sie es andere mithilfe von @Erwähnungen in Kommentaren wissen, wenn Sie deren Input benötigen. [Weitere Informationen](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Verbessern Sie mit Fokus Linie das Verständnis:** Gehen Sie ohne Ablenkungen von Zeile zu Zeile durch ein Dokument. Passen Sie den Fokus an, um eine, drei oder fünf Zeilen gleichzeitig in die Ansicht zu setzen. [Weitere Informationen](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)

- **Schnelle Dateisuche:** Sie suchen nach einer Datei, an der Sie kürzlich gearbeitet haben? Geben Sie einfach in das Suchfeld unter „Datei“ > „Start“ den Namen der gesuchten Datei ein.

- **Speichern Sie Ihre Änderungen, während sie entstehen**: Laden Sie Ihre Dateien in OneDrive hoch, um sicherzustellen, dass alle Ihre Aktualisierungen automatisch gespeichert werden.

- **Erhöhen Sie die Reichweite Ihrer Inhalte**: Möchten Sie Ihre Dokumente barrierefrei gestalten? Die Barrierefreiheitsprüfung kann dies für Sie im Auge behalten, ohne Ihnen dabei in die Quere zu kommen. Probieren Sie es aus, indem Sie auf „Überprüfen“ > „Barrierefreiheit überprüfen“ klicken. Wir werden Sie in der Statusleiste informieren, wenn wir etwas finden, dass Sie sich ansehen müssen.

- **Der Modus „Lerntools“ bietet zusätzliche Unterstützung für weitere Seitenfarben:** Lerntools in Word unterstützt weitere Farben für Seitendesigns, wodurch die Hintergrundfarbe der Seite geändert werden kann. Viele Personen haben Herausforderungen beim Lesen mit einem ganz weißen oder schwarzem Hintergrund, deshalb haben wir die Auswahl von Farben in Word auf PC und Mac erweitert.

- **Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an. Das Wechseln zwischen den Konten ist so einfach wie nie. [Weitere Informationen](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)


- **Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können. Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben. [Weitere Informationen](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a>Office-Suite

- **Installation von Microsoft Teams:** Teams wird zu bestehenden Installationen von Office 365 ProPlus hinzugefügt. [Weitere Informationen](/deployoffice/teams-install)

- **Speichern Sie Ihre Änderungen, während sie entstehen**: Laden Sie Ihre Dateien in OneDrive hoch, um sicherzustellen, dass alle Ihre Aktualisierungen automatisch gespeichert werden.

- **Kontrollmechanismen für den Datenschutz:** Neue aktualisierte und verbesserte Kontrollmechanismen für Diagnosedaten und verbundene Oberflächen. [Weitere Informationen](/DeployOffice/privacy/overview-privacy-controls?toc=%2fdeployoffice%2ftoc.json)

- **Office-Symbole mit neuem Look:** Die Office-Symbole wurden neu gestaltet, um die einfache, leistungsstarke und intelligente Office-Benutzeroberfläche widerzuspiegeln.

- **Installation von Microsoft Teams**: Microsoft Teams ist in bestehenden Installationen von Office 365 ProPlus standardmäßig installiert. [Weitere Informationen](/DeployOffice/teams-install)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a>Nicht sicherheitsrelevante Sicherheitsupdates
### <a name="excel"></a>Excel

- Es wurde ein Problem in Excel behoben, bei dem Makros, die Shapes oder Steuerelementen zugeordnet sind, möglicherweise eine falsche Fehlermeldung anzeigen oder an falschen Zielbereichen arbeiten.

- Ein Problem wurde behoben, durch das die Sortierung und Aktualisierung der PivotTable während der gemeinsamen Dokumenterstellung mit anderen Benutzern zum Scheitern gebracht werden konnte.

- Ein Problem wurde behoben, durch das Wasserfall- und Trichterdiagramme beim Einfügen oder Löschen von Zellen nicht mehr mit Tabellen synchronisiert wurden.

- Ein Konflikt beim Zusammenführen in Excel wurde behoben, durch den Benutzer aufgefordert wurden, die Arbeitsmappe erneut zu öffnen, um die Änderungen zu übernehmen.

- Ein Problem wurde behoben, durch das Ausschneide- und Einfügevorgänge neben einer Tabelle fehlschlugen, wenn die gemeinsame Dokumenterstellung zusammen mit anderen Benutzern durchgeführt wurde.

### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, das dazu führte, dass bei Benutzern, die Ihr Postfach von Standard- auf moderne Authentifizierung aktualisiert hatten, das falschen Konto mit ihrem Outlook-Profil verknüpft wurde.

- Ein Problem wurde behoben, das bewirkt, dass einer Teilmenge von POP3-Benutzern alle E-Mails im nur-Text-Format anzeigt werden, und zwar unabhängig von den Einstellungen. Mit diesem Fix wird die Anzeige der HTML-formatierten Nachrichten wiederhergestellt.

- Ein Problem wurde behoben, bei dem Benutzer nicht in der Lage waren, über einen Screenreader auf Standortvorschläge zuzugreifen.

- Ein Problem wurde behoben, bei dem einige Benutzer beim Versuch, ihre Cloud-Einstellungen für Outlook abzurufen, auf Authentifizierungsfehler stießen.

- Ein Problem wurde behoben, das für Vorgesetzte Unklarheit darüber verursacht hat, ob eine Stellvertretung bereits auf eine bestimmte Besprechungsanfrage geantwortet hat.

- Ein Problem wurde behoben, das dazu führte, dass Outlook-Benutzer in bestimmten Szenarien im Zustand " Kennwort erforderlich " stecken geblieben sind.

- Ein Problem wurde behoben, das bewirkt, dass die aktuelle Ordnersuche zweitweise fehlschlägt.

- Ein Problem wurde behoben, bei dem Benutzer Raumvorschläge für Besprechungen, die außerhalb der Verfügbarkeitszeiten dieses Raums stattfanden, einsehen konnten.

- Es wurde ein temporäres Dienstproblem behoben, bei dem die Benutzer die Fehlermeldung "Diese Datei konnte nicht gefunden werden. Vergewissern Sie sich, dass Pfad und Dateiname korrekt sind" sahen, wenn Sie Cloud-Anhänge verwenden. [Weitere Informationen](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- Ein Problem wurde behoben, das dazu führte, dass Benutzer sahen, dass hochgeladene Dateien von Outlook nach OneDrive oder Sharepoint den Dateinamen geändert haben, wobei mehrere Zeichen durch Unterstriche ersetzt wurden.

- Ein Problem für nicht englischsprachige Benutzer wurde behoben, bei dem die Betreffzeile in einer E-Mail unglaublich klein war.


### <a name="powerpoint"></a>PowerPoint

- Ein Problem wurde behoben, bei dem einige Add-Ins unerwartete Fehler bei Formen in Diagrammen verursachen konnten.

- Ein Problem wurde behoben, um den barrierefreien Namen für PowerPoint-Videosteuerelemente wiederherzustellen.

- Ein Problem wurde behoben, durch das verhindert wurde, dass einige Animationen gestartet werden.

### <a name="project"></a>Project

- Ein Problem wurde behoben, durch das Benutzer unter Windows 7 Projekte aus Project Web-App und SharePoint-Websites öffnen können.


### <a name="visio"></a>Visio

- Das Exportieren nach SVG aus Visio funktionierte für eine Vielzahl von Shapes nicht.

### <a name="word"></a>Word

- Ein Problem wurde behoben, bei dem Benutzer Fehlermeldungen erhalten, während sie mit anderen an einem Word-Dokument zusammenarbeiten.

- Ein Problem wurde behoben, bei dem Benutzer die Meldung "Leider verhindert etwas, dass wir dies freigeben" erhielten, wenn sie versuchten, Dateien, die in SharePoint 2016 gespeichert waren, freizugeben.


### <a name="office-suite"></a>Office-Suite

- Ein Problem wurde behoben, bei dem in einigen Fällen eine von der Sync-Engine unterstützte Sharepoint-Datei "Gespeichert" anzeigen konnte, aber keine Änderungen gespeichert hat.

- Ein Problem wurde behoben, bei dem große Strukturansichten fehlschlugen.

- Behebung eines Problems, aufgrund dessen der neue Zeitname „Reiwa“ in Hiragana und Kanji als Rechtschreibfehler oder Grammatikfehler eingestuft wurde.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1902-august-13"></a>Version 1902: 13. August
*Version 1902 (Build 11328.20392)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Sicherheitsupdates
- Ein Problem wurde behoben, bei dem das Symbol "Filter löschen" sowohl für gefilterte als auch ungefilterte Datenschnitte in Tabellen angezeigt wurde.

### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Updates
- Ein Problem wurde behoben, das dazu führte, dass Benutzer, die Ihr Postfach von Standard- auf moderne Authentifizierung aktualisiert hatten, mit dem falschen Konto verknüpft wurden.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Nicht sicherheitsrelevante Sicherheitsupdates
- Ein Problem wurde behoben, bei dem die Anwendung bei der Zusammenarbeit mit anderen Benutzern an einem Dokument unerwartet beendet werden konnte.

### <a name="word-non-security-updates"></a>Word: Nicht sicherheitsrelevante Sicherheitsupdates
- Ein Problem wurde behoben, durch das Feldern in VBA nur langsam aktualisiert wurden.
- Ein Problem wurde behoben, durch dass beim Öffnen einer DOC-Datei eine Fehlermeldung besagte, dass die Dateien beschädigt sei.
- Ein Problem wurde behoben, bei dem die Anwendung bei der Zusammenarbeit mit anderen Benutzern an einem Dokument unerwartet beendet werden konnte.

### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Updates
- Ein Problem wurde behoben, bei dem die Einstellungs-API in der Office JavaScript-Bibliothek in bestimmten Szenarien nicht funktionierte [Weitere Informationen](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)

## <a name="version-1902-july-09"></a>Version 1902: 9. Juli
*Version 1902 (Build 11328.20368)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt


### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Updates
- Problem extremer Langsamkeit beim Löschen von gefilterten Excel-Zeilen behoben.
- Das Problem, dass beim Scrollen mit zwei Fingern graue Rechtecke über das Arbeitsblatt gezeichnet werden und Excel hängenbleibt, ist behoben.


### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Updates
- Behebt ein Problem, das dazu führte, dass Benutzern bei Outlook gelegentlich das Einfügen englischer Pinyin-Buchstaben angezeigt wurde, anstatt das IME-Kandidatenfenster geöffnet zu lassen, um die Auswahl chinesischer Wörter zuzulassen.
- Behebt ein Problem, das dazu führte, dass Benutzern Räume für Besprechungen vorgeschlagen wurden, die gar nicht verfügbar waren.
- Behebt ein Problem, das dazu führte, dass Benutzer nicht die Masterserie öffneten, sondern stattdessen versuchten, eine Ausnahme für eine Besprechungsserie zu öffnen.
- Behebt ein Problem, das bewirkte, dass Benutzern nicht ordnungsgemäß berechnete Ablaufdaten im Ordner „Gelöschte Elemente“ angezeigt wurden.


### <a name="teams-non-security-updates"></a>Teams: Nicht sicherheitsrelevante Updates

- Teams Installer hat jetzt eine Richtlinie zur Deaktivierung des automatischen Starts nach Abschluss der Installation.


### <a name="visio-non-security-updates"></a>Visio: Nicht sicherheitsrelevante Updates

- Behebt Probleme im Zusammenhang mit ActiveX-Lösungen für Visio, die nicht mit Office 365 funktionieren und als Fehlermeldung ausgedrückt werden, die besagt, dass riched20.dll nicht gefunden werden kann.


### <a name="word--non-security-updates"></a>Word: Nicht sicherheitsrelevante Updates

- GPO-Einstellung zum Deaktivieren der Vorlagen-Suchleiste korrigiert
- Ein Problem wurde behoben, bei dem Benutzer einige ihrer Änderungen verlieren konnten, nachdem sie offline waren und ein Nur-Serverdokument bearbeitet haben.
- Verbesserte Leistung beim Aktivieren von Schnellbausteinen für Dokumenteigenschaften
- Ein Problem wurde behoben, bei dem die erste Downloadrevision vom Server möglicherweise fehlschlägt


### <a name="office-suite--non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Updates

- Es wurde ein Problem behoben, bei dem Geräte, die die Aktivierung gemeinsam genutzter Computer verwenden, bei der Installation weiterer Office-Produkte oder Sprachpakete unerwartet zur benutzerbasierten Aktivierung zurückkehren.
- Es wurde ein Problem mit der Sperrung von Office-Updates behoben, wenn die Proxyauthentifizierung als SYSTEM ausgeführt wird.
- Korrekturen zur Behandlung von Office-Add-Ins, die bei Änderungen des Benutzerprofils nicht mehr angezeigt werden.


## <a name="version-1902-june-11"></a>Version 1902: 11. Juni
*Version 1902 (Build 11328.20318)*
<br/>Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Updates
 - Ein Problem wurde behoben, durch das beim Speichern einer Datei mit einer XML-Zuordnung in PDF ein Absturz verursacht wurde.
 - Ein Problem wurde behoben, durch das beim Laden von Arbeitsmappen mit ungültigen Blattnamen externe Links entfernt wurden.
 - Ein Fehler wurde behoben, bei dem das Arbeitsblatt nicht mehr reagierte, nachdem das Kamera-Werkzeug in Excel benutzt wurde.
 - Ein Problem wurde behoben, durch das Wasserfall- und Trichterdiagramme beim Einfügen oder Löschen von Zellen nicht mehr mit Tabellen synchronisiert wurden.
 - Die Ursache für einen Absturz wurde behoben, der auftrat, wenn eine Datentabelle während der Arbeitsblattberechnung mit einer Matrixformel auf einem anderen von der Tabelle abhängigen Blatt neu berechnet wurde. 
 - Ein Problem wurde behoben, das das Öffnen kennwortgeschützter Arbeitsmappen in SharePoint ohne vorheriges Auschecken der Datei verhinderte.
 - Eine Änderung wurde vorgenommen, um sicherzustellen, dass das BeforeSave-Ereignis beim Freigeben oder Aktivieren/Deaktivieren von AutoSpeichern verarbeitet wird.

### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Updates
 - Ein Problem wurde behoben, durch das Aufgaben von Kunden beim Hinzufügen einer zweiten Bedingung zu "Gruppieren nach" nicht mehr angezeigt werden.

### <a name="word-non-security-updates"></a>Word: Nicht sicherheitsrelevante Sicherheitsupdates
 - Behoben: Beim Freigeben eines Dokuments, an dem aktuell mehrere Personen zusammenarbeiten, wird eine Anlage mit der Erweiterung ASD erstellt.
 - Ein Problem mit Kommentaren wurde behoben, die zufälligen Autoren zugeordnet werden.
 - Ein Problem wurde behoben, durch das beim Auschecken eines Dokuments Signaturen entfernt wurden.

### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Sicherheitsupdates
 - Damit wurde ein Fehler in VBA behoben, der nach einer "Rückgängig"-Aktion einen falschen Zustand des Fülleffekts meldete.


## <a name="version-1902-may-14"></a>Version 1902: 14. Mai
*Version 1902 (Build 11328.20286)*

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Sicherheitsupdates
 -  Ein Fehler wurde behoben, bei dem das Arbeitsblatt nicht mehr reagierte, nachdem das Kamera-Werkzeug in Excel benutzt wurde.
 - Ein Fehler wurde behoben, der beim Verwenden des Mausrads in einem inaktiven Fenster mit einem Diagrammblatt zu einem Absturz führte.
 - Ein Problem wurde behoben, durch das beim Importieren einer Kalkulationstabelle in SharePoint eine Meldung vom Typ "Unerwarteter Fehler" angezeigt wurde.
 - Ein Problem, das dazu geführt hat, dass Excel abstürzt, wenn eine Arbeitsmappe mit bedingter Formatierung geöffnet wird, die einen Namen für die Regel verwendet und auf die eine benutzerdefinierte Darstellung angewendet wurde, wurde gelöst.
 - Makros, die die Datenüberprüfung mit Formeln mit mehr als 255 Zeichen verwenden, haben möglicherweise Laufzeitfehler verursacht. Dieses Problem wurde nun behoben.
 - Ein Problem, das bewirkt, dass Dateien, die PivotTables enthalten, welche mit anderen Arbeitsmappen verknüpft sind, langsam geladen werden. Dieses Problem wurde behoben.
 - Ein Problem beim Öffnen von HTML-Dateien, das einen Fehler vom Typ „Dateiformat und -Erweiterung stimmen nicht überein" ausgelöst hatte, wurde behoben.
 - Es wurde eine Änderung vorgenommen, um Probleme zu beheben, die beim Mausrad-Scrollen auf inaktiven Fenstern auftraten.  

### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Updates
 - Behebt ein Problem, aufgrund dessen Kunden nicht in der Lage sind, einige Felder von Elementen zu bearbeiten, die migriert wurden.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Nicht sicherheitsrelevante Sicherheitsupdates
- Ein Fehler wurde behoben, durch den PowerPoint in seltenen Fällen Benutzer-Änderungen nicht mehr in die Cloud übertragen hat.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Nicht sicherheitsrelevante Sicherheitsupdates
 - Behebt ein Problem in Lync (Skype for Business) bei dem bei jedem Online-Meeting mit mehr als 7 Teilnehmern das Meeting-Fenster ausgeblendet werden kann.
 - Melden Sie sich bei Skype for Business mit denselben Anmeldeinformationen an, die Sie auch für andere Office-Anwendungen nutzen.
 - Aktiviert die Skype for Business-App ordnungsgemäß, wenn diese auf einem gemeinsam genutzten Computer installiert wurde.

### <a name="visio-non-security-updates"></a>Visio: Nicht sicherheitsrelevante Updates
 - Behebt ein Problem, das zu Problemen mit der Fensterhierarchie für Lösungen von Drittanbietern führte, die Visio erweitern, indem sie die dynamische DPI-Funktion deaktivieren.

### <a name="word-non-security-updates"></a>Word: Nicht sicherheitsrelevante Sicherheitsupdates
 - Ein Problem wurde behoben, bei dem das Bearbeiten einer verknüpften Person, die durch SharePoint hinzugefügt wurde, einen Absturz verursachte.
 - Behoben, wo das Dialogfeld „Fehler beim Laden der Ressource“ angezeigt wird, wenn Word gestartet wird.

### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Updates
 - Hierbei handelt es sich um einen Fix für ein Problem, bei dem Dateien nicht in den Apache-WebDAV-Ordnern gespeichert werden können.
 - Behebt ein Problem, bei dem Office abrupt geschlossen wird, wenn Kunden einige in der Cloud gespeicherte Dateien öffnen.
 - Behebung eines Problems, aufgrund dessen der neue Zeitname „Reiwa“ in Hiragana und Kanji als Rechtschreibfehler oder Grammatikfehler eingestuft wurde.
 - Ein Fehler wurde behoben, bei dem die Liste zuletzt verwendeter Dateien für viele Nutzer auf Windows 10 geleert wurde.
 - Ein Fehler wurde behoben, bei dem einem Endbenutzer ein Office-Business Aktualisierungsbalken angezeigt wurde, obwohl es sich um eine vom Administrator angestoßene Aktualisierung handelte.
 - Ein Probleme im Zusammenhang mit zeitweilig leerer Anmeldeaufforderung wurde behoben.
 

## <a name="version-1902-april-9"></a>Version 1902: 09. April
*Version 1902 (Build 11328.20230)*

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Updates

- Behebung eines Problems, bei dem das Drücken der Tabulatortaste nicht zur nächsten Zelle führte, wenn die Zelle eine Formel enthält, die mit einem definierten Namen endet.
- Behebung eines Problems, bei dem die Zellformatierung die Dateigröße unnötig vergrößerte.
- Behebung eines Problems, bei dem das Ausschneiden und Einfügen einer PivotTable zwischen Arbeitsmappen zum Einfügen der Daten führen kann, ohne daß eine PivotTable für andere, mit denen Sie zusammenarbeiten, vorhanden ist.

### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Updates

- Behebt ein Problem, bei dem Windows nicht am richtigen Speicherort angezeigt wird, wenn die Taskleiste am linken oder oberen Rand des Bildschirms gespeichert wurde.
- Behebt ein Problem, das einen Absturz beim Laden von Bildern auf der Visitenkarte verursacht.
- Behebt ein Problem, das beim Start von Office-Programmen in einigen Fällen Abstürze verursachte.
- Behebt ein Problem, bei dem Windows nicht am richtigen Speicherort angezeigt wird, wenn die Taskleiste am linken oder oberen Rand des Bildschirms gespeichert wurde.
- Behebt ein Problem, aufgrund dessen Kunden nicht in der Lage sind, einige Felder von Elementen zu bearbeiten, die migriert wurden.

### <a name="visio-non-security-updates"></a>Visio: Nicht sicherheitsrelevante Updates

- Behebt ein Problem, das zu Problemen mit der Fensterhierarchie für Lösungen von Drittanbietern führte, die Visio erweitern, indem sie die dynamische DPI-Funktion deaktivieren.

### <a name="word-non-security-updates"></a>Word: Nicht sicherheitsrelevante Sicherheitsupdates

- Wenn eine Datei im schreibgeschützten Modus geöffnet ist und Sie auf "Speichern unter" im Bereich "Info" klicken, wird das Problem behoben, sodass das Speichermenü angezeigt wird.

### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Sicherheitsupdates

- Behebt ein Problem, bei dem Teile eines Office-Updates nicht das Peercaching der Übermittlungsoptimierung verwenden. [Weitere Informationen](/windows/deployment/update/waas-delivery-optimization)
- Behebung eines Fehlers, der dazu führen konnte, dass Produkte entfernt oder nicht aktiviert wurden, wenn Office mit dem Office-Bereitstellungstool installiert wurde und es zu abweichender Groß- und Kleinschreibung kam.
- Behebt ein Problem, bei dem übermäßig viele Anmeldeaufforderungen auf Geräten mit Windows 10 (Version 1803 oder höher) angezeigt werden.
- Repariert die Regression, die beim Herunterladen von verknüpften Grafiken Abstürze verursachte.
- Die Unschärfe großer in Word, Excel und PowerPoint eingefügter EMF-Dateien wird behoben.
- Der Fehler in der Analyselogik des Versionsverlaufs wird behoben, der in einigen Fällen dazu führte, dass Dokumente im schreibgeschützten Modus geöffnet wurden.

## <a name="version-1902-march-12"></a>Version 1902: 12. März
*Version 1902 (Build 11328.20158)*

### <a name="access-feature-updates"></a>Access: Featureupdates

- **Aktualisieren, erneutes Verknüpfen oder Entfernen von verknüpften Tabellen:** Im aktualisierten Tabellenverknüpfungs-Manager werden alle Datenquellen und verknüpften Tabellen verwaltet. [Weitere Informationen](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- **Schwarz färben, grau färben:** Ändern Sie das Erscheinungsbild von Access so oft wie gewünscht. Vier Designs zur Auswahl: Farbig, Dunkelgrau, Schwarz oder Weiß. [Weitere Informationen](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)
- **Office hat ein neues Aussehen:** Office-Anwendungen verfügen jetzt über moderne Symbole, die einfacher und barrierefreier sind, und das Menüband enthält aktualisierte visuelle Objekte, die die vielfältigen Funktionen der Zusammenarbeit in Office-Apps hervorheben.

### <a name="excel-feature-updates"></a>Excel: Featureupdates

- **Schneller Einstieg** Die neu gestaltete Startseite setzt Ihre zuletzt geöffneten Dokumente in den Mittelpunkt. Greifen Sie mit weniger Klicks auf Dateien zu, und öffnen Sie Kontoeinstellungen oder Optionen direkt von hier aus.
- **Zusammenarbeiten mit Kommentaren:** Halten Sie die Unterhaltung mit dem integrierten Antwortfeld direkt in Ihrem Arbeitsblatt aufrecht. [Weitere Informationen](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- **Die Symbole auf dem Menüband haben einen neuen Look:** Keine Sorge – alles funktioniert noch wie zuvor. Und nun sehen die Symbole auf allen Bildschirmgrößen toll aus. [Weitere Informationen](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Möglichkeit zum Einfügen von SVGs mit angewendeten Filtern:** Office-Benutzer haben jetzt die Möglichkeit, SVGs einzufügen, auf die Filter angewendet wurden. [Weitere Informationen](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Aufzeigen, was hinter einem Bild steckt:** Platzieren Sie ein Bild in einem Arbeitsblatt, wählen Sie die Voreinstellungen aus, und beobachten Sie, wie sich die Transparenz ändert. Das ist alles! [Weitere Informationen](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **An alle Fans von „Abrufen und Transformieren“:** Wenn Sie „Abrufen & Transformieren“ häufig verwenden, werden Sie sich freuen, dass das Feature „Spalte aus Beispiel“ verbessert wurde. Und viele Connectors wurden ebenfalls verbessert. [Weitere Informationen](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- **Verbesserte Unterstützung für hoch auflösende Displays:** Wenn Sie mehrere Monitore oder ein Laptop Dock verwenden, werden Office-Apps nun auf jedem Display präziser angezeigt, auch wenn die Displays verschiedene Skalierungseinstellungen haben. [Weitere Informationen](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Schnelle Suche** Wir haben die VLOOKUP-, HLOOKUP- und MATCH-Berechnungen beschleunigt, damit Sie schneller Antworten erhalten. [Weitere Informationen](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a>Outlook: Featureupdates

- **Verwenden Sie "Laut vorlesen", um sich Ihre E-Mails vorlesen zu lassen:** Outlook kann Ihre E-Mail laut vorlesen und den jeweils vorgelesenen Text hervorheben. Um "Laut vorlesen" zu aktivieren, navigieren Sie zu den Einstellungen für die Barrierefreiheit. [Weitere Informationen](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- **Eingabe ohne Tippen:** Haben Sie ein Mikrofon? Klicken Sie auf "Diktieren", und beobachten Sie, wie Outlook tippt, während Sie sprechen. [Weitere Informationen](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Die Symbole auf dem Menüband haben einen neuen Look:** Keine Sorge – alles funktioniert noch wie zuvor. Und nun sehen die Symbole auf allen Bildschirmgrößen toll aus. [Weitere Informationen](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Standardmäßiges Blockieren des Downloads externer Inhalte in SMIME-verschlüsselten und signierten E-Mails:** Aufgrund einer Schwachstelle im SMIME-Protokoll blockiert Outlook den Download externer Inhalte in Nachrichten, die über SMIME verschlüsselt oder signiert wurden. Benutzer können daher als Schutzmaßnahme vor dieser Sicherheitslücke externe Inhalte nicht mit einem einzelnen Klick über die Outlook-Benutzeroberfläche herunterladen. Es ist eine neue Option im Dialogfeld „Optionen“ vorhanden, mit der Benutzer zum alten Verhalten zurückkehren können.
- **Deaktivieren der Weiterleitung für eine Besprechung:** Verhindern Sie, dass Teilnehmer Ihre Besprechung an andere weiterleiten. Klicken Sie im Menüband einfach auf „Antwortoptionen“. [Weitere Informationen](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- **Personenvorschläge im Terminplanungs-Assistenten:** Sehen Sie sich Empfehlungen für Teilnehmer an, die Sie beim Planen einer Besprechung hinzufügen können. Kein Hin- und Herwechseln zwischen dem Terminplanungs-Assistenten und der An-Zeile mehr. [Weitere Informationen](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)
- **Das Reservieren eines Raums ist nun noch einfacher:** Suchen Sie mithilfe mehrerer Raumlisten nach einem Konferenzraum, und wechseln Sie zwischen Listen, ohne bereits ausgewählte Räume zu verlieren.
- **Neuer Standardwert für Seriendauer:** Der Standardwert für die Seriendauer war im Dialogfeld "Serie" bisher auf "Kein Enddatum" festgelegt. Dies erleichtert die Erstellung lang andauernder Wiederholungsserien, die aber im Lauf der Zeit beschädigt werden können. Wir haben den Standardwert für das Dialogfeld "Serie" auf "Ende am" aktualisiert, so dass unser Standardwert mit den empfohlenen bewährten Methoden für die Kalenderverwaltung übereinstimmt.
- **Teilnehmen an Teambesprechungen über das Dialogfeld "Outlook-Erinnerungen":** Wenn Outlook Benutzer an eine anstehende Besprechung erinnert, wird eine Schaltfläche „Online beitreten“ angezeigt, falls die anstehende Besprechung eine Teams-Onlinebesprechung ist. Dieser Vorgang ähnelt dem Beitreten zu einer Skype for Business-Besprechung im Dialogfeld „Outlook-Erinnerungen“.
- **Keine Erinnerungen mehr für vergangene Ereignisse:** Sie können Ihren Kalender so festlegen, dass Erinnerungen für Ereignisse, die bereits abgeschlossen sind, automatisch ausgeblendet werden. [Weitere Informationen](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **Die URL hinter sicheren Links:** Sichere Links bieten Ihnen Schutz vor bösartigen URLs, die Sie in E-Mails empfangen haben, blenden dabei aber die ursprüngliche URL aus. Wenn Sie das Original anzeigen möchten, zeigen Sie mit dem Mauszeiger auf die URL. Eine Advanced Threat Protection-Lizenz ist erforderlich. [Weitere Informationen](https://products.office.com/exchange/advance-threat-protection)
- **Zoomen und Übernehmen:** Anstatt den Zoom jedes Mal anzupassen, wenn Sie eine Nachricht lesen, wählen Sie einen Standardwert für alle Nachrichten. [Weitere Informationen](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- **Nachrichtenverschlüsselung: IRM-Richtlinie "Nur verschlüsseln":** Die neue Option "Nur verschlüsseln" wird im Menü "Optionen" > "Berechtigungen" für Benutzer von Office 365-Nachrichtenverschlüsselung angezeigt. Mit dieser Option können Sie eine Nachricht verschlüsseln und an alle Personen innerhalb oder außerhalb Ihrer Organisation senden.
- **Warnung, wenn Sie unter "BCC" erwähnt wurden:** Der BCC-InfoTipp warnt Sie, bevor Sie versehentlich eine Antwort an alle Empfänger einer E-Mail senden, der Sie als BCC-Empfänger hinzugefügt wurden.
- **Eine flexiblere "An:"-Zeile:** Wenn Sie in die Zeile "An:" klicken, um eine Nachricht zu adressieren, schlagen wir Ihnen Empfänger vor, die Sie wahrscheinlich auswählen werden. Außerdem können Sie das jeweilige Foto sehen und wissen so, dass Sie Ihre E-Mail an die richtige Person senden. [Weitere Informationen](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- **Möglichkeit zum Einfügen von SVGs mit angewendeten Filtern:** Office-Benutzer haben jetzt die Möglichkeit, SVGs einzufügen, auf die Filter angewendet wurden. [Weitere Informationen](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Verbesserte Unterstützung für hoch auflösende Displays:** Wenn Sie mehrere Monitore oder ein Laptop Dock verwenden, werden Office-Apps nun auf jedem Display präziser angezeigt, auch wenn die Displays verschiedene Skalierungseinstellungen haben. [Weitere Informationen](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a>PowerPoint: Featureupdates

- **Schneller Einstieg** Die neu gestaltete Startseite setzt Ihre zuletzt geöffneten Dokumente in den Mittelpunkt. Greifen Sie mit weniger Klicks auf Dateien zu, und öffnen Sie Kontoeinstellungen oder Optionen direkt von hier aus.
- **Eingabe ohne Tippen:** Haben Sie ein Mikrofon? Klicken Sie auf "Diktieren", und beobachten Sie, wie PowerPoint tippt, während Sie sprechen. [Weitere Informationen](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Die Symbole auf dem Menüband haben einen neuen Look:** Keine Sorge – alles funktioniert noch wie zuvor. Und nun sehen die Symbole auf allen Bildschirmgrößen toll aus. [Weitere Informationen](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Verbesserte Unterstützung für hoch auflösende Displays:** Wenn Sie mehrere Monitore oder ein Laptop Dock verwenden, werden Office-Apps nun auf jedem Display präziser angezeigt, auch wenn die Displays verschiedene Skalierungseinstellungen haben. [Weitere Informationen](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Links in lebendigen Farben:** Links sind nicht mehr nur blau. Wenden Sie jede gewünschte Schriftfarbe an. [Weitere Informationen](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- **Verleihen Sie Ihren Folien mehr Lebendigkeit:** Fügen Sie animierte 3D-Grafiken ein, um zu sehen, wie Herzen schlagen, Planeten sich in einer Umlaufbahn bewegen und wie ein T-Rex über den Bildschirm stampft. [Weitere Informationen](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Sie skizzieren, wir polieren:** Wir wandeln von Hand geschriebenen Text und handgezeichnete Shapes in optimierte Diagramme um. Wählen Sie einfach Ihre Freihandstriche aus, um loszulegen. [Weitere Informationen](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Aufzeigen, was hinter einem Bild steckt:** Platzieren Sie ein Bild in einem Arbeitsblatt, wählen Sie die Voreinstellungen aus, und beobachten Sie, wie sich die Transparenz ändert. Das ist alles! [Weitere Informationen](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Veröffentlichen in Microsoft Stream:** Geben Sie eine Präsentation mithilfe von Microsoft Stream noch sicherer als Video innerhalb Ihrer Organisation frei.  [Weitere Informationen](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **Exportieren in ein 4K-Video:** Wenn Sie eine Präsentation als Video exportieren, steht nun die 4K-Auflösung zur Auswahl.  [Weitere Informationen](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **Möglichkeit zum Einfügen von SVGs mit angewendeten Filtern:** Office-Benutzer haben jetzt die Möglichkeit, SVGs einzufügen, auf die Filter angewendet wurden. [Weitere Informationen](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Große Dateien lassen sich jetzt schneller öffnen:**-Bilder, Videos und andere große Elemente werden jetzt beim Öffnen von Dateien, die auf OneDrive oder SharePoint gespeichert sind, im Hintergrund heruntergeladen.

### <a name="word-feature-updates"></a>Word: Featureupdates

- **Schneller Einstieg** Die neu gestaltete Startseite setzt Ihre zuletzt geöffneten Dokumente in den Mittelpunkt. Greifen Sie mit weniger Klicks auf Dateien zu, und öffnen Sie Kontoeinstellungen oder Optionen direkt von hier aus.
- **Eingabe ohne Tippen:** Haben Sie ein Mikrofon? Klicken Sie auf "Diktieren", und beobachten Sie, wie Word tippt, während Sie sprechen. [Weitere Informationen](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Verleihen Sie Ihren Dokumenten mehr Lebendigkeit:** Fügen Sie animierte 3D-Grafiken ein, um zu sehen, wie Herzen schlagen, Planeten sich in einer Umlaufbahn bewegen und wie ein T-Rex über die Seite stampft. [Weitere Informationen](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Die Symbole auf dem Menüband haben einen neuen Look:** Keine Sorge – alles funktioniert noch wie zuvor. Und nun sehen die Symbole auf allen Bildschirmgrößen toll aus. [Weitere Informationen](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Aufzeigen, was hinter einem Bild steckt:** Platzieren Sie ein Bild in einem Arbeitsblatt, wählen Sie die Voreinstellungen aus, und beobachten Sie, wie sich die Transparenz ändert. Das ist alles! [Weitere Informationen](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Möglichkeit zum Einfügen von SVGs mit angewendeten Filtern:** Office-Benutzer haben jetzt die Möglichkeit, SVGs einzufügen, auf die Filter angewendet wurden. [Weitere Informationen](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Verbesserte Unterstützung für hoch auflösende Displays:** Wenn Sie mehrere Monitore oder ein Laptop Dock verwenden, werden Office-Apps nun auf jedem Display präziser angezeigt, auch wenn die Displays verschiedene Skalierungseinstellungen haben. [Weitere Informationen](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Schreiben Sie mit der Hilfe von LinkedIn Ihren besten Lebenslauf:** Mit dem Lebenslauf-Assistenten können Sie Erfahrungen, vorgeschlagene Qualifikationen und vieles mehr für eine bestimmte Position anzeigen. [Weitere Informationen](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)

### <a name="project-feature-updates"></a>Project: Featureupdates

- **Weitere Informationen auf Task Board-Karten:** Wenn der Titel allein nicht aussagekräftig genug ist, passen Sie Ihre Task Board-Karten so an, dass die wichtigsten Details darauf angezeigt werden. [Weitere Informationen](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- **Office hat ein neues Aussehen:** Office-Anwendungen verfügen jetzt über moderne Symbole, die einfacher und barrierefreier sind, und das Menüband enthält aktualisierte visuelle Objekte, die die vielfältigen Funktionen der Zusammenarbeit in Office-Apps hervorheben.

### <a name="publisher-feature-updates"></a>Publisher: Featureupdates

- **Office hat ein neues Aussehen:** Office-Anwendungen verfügen jetzt über moderne Symbole, die einfacher und barrierefreier sind, und das Menüband enthält aktualisierte visuelle Objekte, die die vielfältigen Funktionen der Zusammenarbeit in Office-Apps hervorheben.

### <a name="visio-feature-updates"></a>Visio: Featureupdates

- **Genießen Sie einen symbolischen Moment in Ihrem nächsten Diagramm:** Treffen Sie eine Auswahl aus 26 neuen Schablonen mit Symbolen für Analysen, Kunst, Feierlichkeiten, Gesichter, Sport usw.
- **Office hat ein neues Aussehen:** Office-Anwendungen verfügen jetzt über moderne Symbole, die einfacher und barrierefreier sind, und das Menüband enthält aktualisierte visuelle Objekte, die die vielfältigen Funktionen der Zusammenarbeit in Office-Apps hervorheben.

### <a name="office-suite-feature-updates"></a>Office Suite: Featureupdates

- **Drittanbieteranwendungen für Office verfügen jetzt über Unterstützung zum Einfügen von SVGs mithilfe der Office.js-API** Drittanbieteranwendungen, die auch als Add-Ins in Office bekannt sind, können nun SVGs einfügen. Benutzer können nun ihre persönliche Sammlung von SVGs mit Office verbinden. Entwickler können dieses Feature mithilfe der Office.js-API verwenden.
- **Installation von Microsoft Teams**: Microsoft Teams ist in bestehenden Installationen von Office 365 ProPlus standardmäßig installiert. [Weitere Informationen](/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a>Skype for Business: Feature-Updates

- **Verbesserte Unterstützung für hoch auflösende Displays:** Wenn Sie mehrere Monitore oder ein Laptop Dock verwenden, werden Office-Apps nun auf jedem Display präziser angezeigt, auch wenn die Displays verschiedene Skalierungseinstellungen haben. [Weitere Informationen](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="teams-feature-updates"></a>Teams: Featureupdates

- **Verbesserte Unterstützung für hoch auflösende Displays:** Wenn Sie mehrere Monitore oder ein Laptop Dock verwenden, werden Office-Apps nun auf jedem Display präziser angezeigt, auch wenn die Displays verschiedene Skalierungseinstellungen haben. [Weitere Informationen](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

## <a name="version-1808-february-12"></a>Version 1808: 12. Februar
*Version 1808 (Build 10730.20280)* 

### <a name="access-non-security-updates"></a>Access: Nicht sicherheitsrelevante Updates 

- Dieses Update bietet Unterstützung für neue japanische Zeiträume für Access.

### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Sicherheitsupdates 

- Behebt ein Problem, aufgrund dessen Benutzern mit Regeln, die auf einen Ordner verweisen, der nicht mehr vorhanden ist, eine Fehlermeldung angezeigt wird, wenn sie versuchen, Regeln zu verwalten. Außerdem werden clientseitige Regeln nicht ausgeführt.
- Behebt ein Problem, aufgrund dessen das Programm bei Benutzern mit zwischengespeicherten delegierten Postfächern in unvorhersehbaren Abständen häufig hängen bleibt.
- Behebt ein Problem, aufgrund dessen ganztägige Ereignisse in einigen Anzeigen so angezeigt werden, dass sie mehr Tage als beabsichtigt umfassen, weil die Endzeit der Besprechung auf Mitternacht des folgenden Tages festgelegt wurde.
- Beim Erstellen von neuen Terminen oder Besprechungen, die auf japanische Zeiträume verweisen, wurde ein Absturz beseitigt.

### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Sicherheitsupdates

- Behebt ein Problem, bei dem Add-Ins, die mithilfe der [zentralen O365-Office-Bereitstellung](/office/dev/add-ins/publish/centralized-deployment) bereitgestellt wurden, nicht mehr reagierten und nicht mehr verwendet werden konnten.


## <a name="version-1808-january-8"></a>Version 1808: 8. Januar
*Version 1808 (Build 10730.20264)* 

### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Sicherheitsupdates 

- Behebt ein Problem, aufgrunddessen bei Benutzern Probleme mit der Kalendersynchronisierung auftreten.

### <a name="word-non-security-updates"></a>Word: Nicht sicherheitsrelevante Sicherheitsupdates

- Verbessert die Leistung beim Öffnen.

## <a name="version-1808-december-11"></a>Version 1808: 11. Dezember
*Version 1808 (Build 10730.20262)*

### <a name="excel-security-updates"></a>Excel: Sicherheitsupdates 

-   [CVE-2018-8597](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8597): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung 
-   [CVE-2018-8598](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8598): Microsoft Excel – Sicherheitsrisiko bei der Offenlegung von Informationen 
-   [CVE-2018-8627](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8627): Microsoft Excel – Sicherheitsrisiko bei der Offenlegung von Informationen 
-   [CVE-2018-8636](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8636): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung 

### <a name="outlook-security-updates"></a>Outlook: Sicherheitsupdates 

-   [CVE-2018-8587](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8587): Sicherheitsanfälligkeit in Microsoft Outlook bezüglich Remotecodeausführung 

### <a name="powerpoint-security-updates"></a>PowerPoint: Sicherheitsupdates 

-   [CVE-2018-8628](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8628): Sicherheitsrisiko in Microsoft PowerPoint bezüglich Remotecodeausführung 

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Sicherheitsupdates 

- Behebung eines Problems in Sitzungen der gemeinsamen Dokumenterstellung, bei dem ein Slicer nicht korrekt aktualisiert wird, nachdem ein anderer Benutzer einen Spaltenfilter auf die Daten in diesem Slicer angewendet hat.
- Behebung eines Problems in einer Sitzung der gemeinsamen Dokumenterstellung, bei dem einer der Benutzer die Beschriftung für einen Slicer löscht, wodurch verursacht wird, dass bei einem anderen Benutzer in der Sitzung der gemeinsamen Dokumenterstellung Excel abstürzt.
- Es wurde ein möglicher Absturz beim Erstellen mehrerer Tabellenslicer, die an dieselbe Datenspalte gebunden sind, und beim anschließendes Löschen dieser Datenspalte behoben.
- Behebung eines Problems, aufgrund dessen Excel beim Aktualisieren einer gefilterten Abfragetabelle, die umbrochenen Text in Zellen enthält, manchmal abstürzt, wenn die Option zum automatischen Anpassen der Spaltenbreite deaktiviert wurde.
- Behebung eines Problems, bei dem in Excel 2007 gespeicherte Slicer einen Absturz verursachen können, wenn sie in neueren Versionen von Excel geöffnet werden, wenn sich die Anzahl von im Slicer angezeigten Elementen ändert.
- Führt Unterstützung für die Schaltfläche „Diagnose abrufen“ ein, um die Untersuchung von Supportanfragen zu erleichtern.

### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Sicherheitsupdates

- Behebung eines Problems, aufgrund dessen Benutzern beim Öffnen des Dialogfelds „Regeln und Warnungen verwalten“ ein Fehler angezeigt wird.
- Behebung eines Problems, aufgrund dessen Benutzer bei Verwendung einer getakteten Verbindung keine Verbindung zu ihren Postfächern über DirectAccess herstellen konnten.
- Behebung eines Problems, aufgrund dessen freie Dokumente, die in öffentlichen Ordnern gespeichert sind, fälschlicherweise in der „Geschützten Ansicht“ geöffnet werden.
- Behebung eines Problems, aufgrund dessen Benutzern unerwartete Anlagen beim Weiterleiten von Elementen mit Inline-Anlagen angezeigt werden.
- Behebung eines Problems, aufgrund dessen OFT-Dateien nach dem Senden als Anlage nicht ordnungsgemäß gerendert werden.
- Behebung eines Problems, aufgrund dessen bei einigen Add-In-Benutzern Abstürze beim Hinzufügen einer Besprechung zu einem freigegebenen Kalender auftreten.
- Behebung eines Problems, aufgrund dessen bei Benutzern Abstürze beim Öffnen des Ordners „Unterhaltungsverlauf“ auftraten.

### <a name="project-non-security-updates"></a>Project: Nicht sicherheitsrelevante Sicherheitsupdates

- Behebung eines Problems im Zusammenhang mit der Unterstützung einer neuen venezolanischen Währung in Project behoben.
- Behebung eines Problems, bei dem Project möglicherweise hängen bleibt, wenn ein Surface 4-Tablet verwendet wird, das an einen externen Monitor angeschlossen ist.
- Behebung eines Problems, bei dem Project beim Speichern des Projekts im XML-Format möglicherweise abstürzt.
- Behebung eines Problems, aufgrund dessen benutzerdefinierte Felder von Unternehmensressourcen nach der Bearbeitung eines Ressourcenkalenders möglicherweise gelöscht werden.
- Behebung eines Problems, aufgrund dessen bei Benutzern beim Suchen nach koreanischen Anzeigenamen Abstürze auftraten.

## <a name="version-1808-november-13"></a>Version 1808: 13. November
*Version 1808 (Build 10730.20205)*

### <a name="excel-security-updates"></a>Excel: Sicherheitsupdates

-   [CVE-2018-8574](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8574): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung 
-   [CVE-2018-8577](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8577): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung 

### <a name="outlook-security-updates"></a>Outlook: Sicherheitsupdates 

-   [CVE-2018-8522](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8522): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung 
-   [CVE-2018-8524](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8524): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung 
-   [CVE-2018-8558](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8558): Microsoft Outlook – Sicherheitsrisiko bei der Offenlegung von Informationen 
-   [CVE-2018-8576](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8576): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung 
-   [CVE-2018-8579](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8579): Microsoft Outlook – Sicherheitsrisiko bei der Offenlegung von Informationen 
-   [CVE-2018-8582](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8582): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung 

### <a name="project-security-updates"></a>Project: Sicherheitsupdates 

-   [CVE-2018-8575](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8575): Sicherheitsanfälligkeit in Microsoft Project bezüglich Remotecodeausführung 

### <a name="word-security-updates"></a>Word: Sicherheitsupdates 

-   [CVE-2018-8573](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8573): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung 

### <a name="skype-for-business-security-updates"></a>Skype for Business: Sicherheitsupdates 

-   [CVE-2018-8546](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8546): Sicherheitsanfälligkeit in Microsoft Skype for Business bezüglich Verweigerung des Dienstes 

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Sicherheitsupdates 

- Es wurde ein Fehler behoben, bei dem PowerPivot in einigen Builds/Versionen nicht angezeigt wurde.

### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Sicherheitsupdates 

- Es wurde ein Problem behoben, aufgrund dessen Benutzer die Schaltfläche zur Kontensteuerung nicht verwenden konnten, um zwischen Konten in benutzerdefinierten Formularen zu wechseln.
- Es wurde ein Problem behoben, bei dem bei Verwendung von ScanPST zum Reparieren einer OST-/PST-Datei ein Absturz auftrat.
- Es wurde ein Problem behoben, aufgrund dessen das CC-Feld in bestimmten E-Mail-Nachrichten für Benutzer mit Onlinemodusprofilen nicht angezeigt wurde.

### <a name="onenote-non-security-updates"></a>OneNote: Nicht sicherheitsrelevante Sicherheitsupdates 

- Es wurde ein Stabilitätsproblem gelöst, das im Zusammenhang mit dem Synchronisieren und dem Navigieren zu einem gelöschten Abschnitt auftreten kann.

### <a name="project-non-security-updates"></a>Project: Nicht sicherheitsrelevante Sicherheitsupdates 

- Es wurde ein Problem behoben, bei dem beim Arbeiten mit Project-Dateien in einer SharePoint-Dokumentbibliothek, die sich in der modernen Oberfläche befand, die Aktionen „Auschecken erforderlich“ und „Schreibgeschützt“ nicht korrekt ausgeführt werden.


## <a name="version-1808-october-9"></a>Version 1808: 9. Oktober
*Version 1808 (Build 10730.20155)*

### <a name="excel-security-updates"></a>Excel: Sicherheitsupdates
-   [CVE-2018-8502](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8502): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung 

### <a name="outlook-security-updates"></a>Outlook: Sicherheitsupdates 
-   [ADV180026](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/ADV180026): Microsoft Office – Intensiver Schutz – Update 

### <a name="powerpoint-security-updates"></a>PowerPoint: Sicherheitsupdates 
-   [CVE-2018-8501](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8501): Sicherheitsrisiko in Microsoft PowerPoint bezüglich Remotecodeausführung

### <a name="word-security-updates"></a>Word: Sicherheitsupdates 
-   [CVE-2018-8504](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8504): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung 
-   [ADV180026](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/ADV180026): Microsoft Office – Intensiver Schutz – Update 

### <a name="office-suite-security-updates"></a>Office-Suite: Sicherheitsupdates 
-   [CVE-2018-8432](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8432): Microsoft Graphics Component – Sicherheitsrisiko bei der Remotecodeausführung 

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Sicherheitsupdates 
-   Es wurde das Problem behoben, bei dem Symbole im Bereich 2190...2194 in Cambria Math geändert werden. Dadurch wurde die Höhe der Excel-Zelle um das 3-fache erhöht.
-   Dadurch wird das Problem in Excel behoben, bei dem Excel möglicherweise nicht mehr reagiert, wenn der Benutzer den Mauszeiger in einer Arbeitsmappe mit vielen definierten Namen über Formatierungsoptionen bewegt, und bei dem Excel möglicherweise im Schnellanalysetool nicht mehr reagiert, auch wenn die Livevorschau in den Optionen deaktiviert wurde.
-   Wir untersuchen derzeit die Ursachen für die geringe Leistung beim Verschieben des Excel-Anwendungsfensters von einem Desktop auf einen anderen. Wenn bei Ihnen in der Zwischenzeit diese Leistungseinbußen auftreten, können Sie als Problemumgehung die Option „Für Kompatibilität optimieren“ für „Bei Verwendung mehrerer Displays“ auf der Registerkarte „Allgemein“ im Dialogfeld „Dateioptionen“ auswählen.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Nicht sicherheitsrelevante Sicherheitsupdates
-   Das Problem möglicher Dateibeschädigungen beim Speichern von Dateien mit ActiveX-Inhalt wurde behoben.

### <a name="word-non-security-updates"></a>Word: Nicht sicherheitsrelevante Sicherheitsupdates
-   Es wurde das Problem behoben, dass beim Einfügen eines Word-Dokumentobjekts der Formel-Editor angezeigt wurde.

### <a name="project-non-security-updates"></a>Project: Nicht sicherheitsrelevante Sicherheitsupdates
-   Es wurde das Problem behoben, bei dem beim Festlegen einer Kopf- oder Fußzeile für einen Ausdruck die Änderung nicht für den nächsten Druckvorgang des Projekts beibehalten wurde.

### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Updates
-   Es wurde das Problem behoben, dass in Apps Animationen angezeigt werden, obwohl Animationen über die Einstellungen für Barrierefreiheit und Leistung deaktiviert wurden. 
-   Es wurde das Problem behoben, dass der Hintergrund leer ist, wenn das Textmarker-Zeichentool verwendet wird.

## <a name="version-1808-september-11"></a>Version 1808: 11. September
*Version 1808 (Build 10730.20102)*

### <a name="access-feature-updates"></a>Access: Featureupdates
 - **Daten mit neuen Diagrammen visualisieren:** Treffen Sie eine Auswahl aus 11 Diagrammen, und fügen Sie ein Diagramm zu Ihren Formularen und Berichten hinzu, um die Daten besser zu visualisieren und fundierte Entscheidungen zu treffen. [Weitere Informationen](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)
 
 ### <a name="access-security-updates"></a>Access: Sicherheitsupdates
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8312):Sicherheitsanfälligkeit in Microsoft Access bezüglich Remotecodeausführung

### <a name="excel-feature-updates"></a>Excel: Featureupdates
 - **Gemeinsame Bearbeitung:** Arbeiten Sie gleichzeitig mit anderen Personen in einer Arbeitsmappe. [Weitere Informationen](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)
 - **AutoSpeichern für Clouddateien ist nun standardmäßig aktiviert:** AutoSpeichern ist in der Version vom September 2018 Halbjährlicher Kanal (gezielt) standardmäßig aktiviert. Diese Änderung bedeutet, dass Benutzer sich keine Sorgen darüber machen müssen, dass Änderungen in Dokumenten verloren gehen, die in OneDrive oder SharePoint Online gespeichert sind. Änderungen werden automatisch in der Cloud gespeichert, und Benutzer müssen nicht mehr explizit STRG + S drücken oder auf die Schaltfläche „Speichern“ klicken. Allerdings müssen die Benutzer diese Verhaltensänderung verstehen, damit sie keine versehentlichen Änderungen an Dokumenten vornehmen. Beachten Sie, dass Benutzer das automatische Speichern mithilfe der Umschalttaste „AutoSpeichern“ deaktivieren können. Es wird empfohlen, dass Sie Ihre Benutzer über diese bevorstehende Änderung informieren und sie dahingehend schulen, wie dieses neue Feature in Office 365 optimal genutzt werden kann.[Weitere Informationen zu AutoSpeichern](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Erfahren Sie, was IT-Administratoren über AutoSpeichern wissen sollten](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Verbesserte Bearbeitungsleiste für Zellen:** Sie können nun STRG + A zum Auswählen von Text in einer Zelle oder in der Bearbeitungsleiste verwenden. Außerdem wurde die Unterstützung von Emojis und anderen komplexen Zeichen verbessert. [Weitere Informationen](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Verbesserungen an der Barrierefreiheitsprüfung:** Die Barrierefreiheitsprüfung weist eine aktualisierte Unterstützung für internationale Standards und Empfehlungen auf, sodass Sie leichter auf Ihre Arbeitsmappen zugreifen können. [Weitere Informationen](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Vermeiden unerwünschter Bearbeitungen:** Legen Sie fest, dass Ihre Arbeitsmappen schreibgeschützt geöffnet werden, um versehentliche Änderungen zu verhindern. Wechseln Sie zu „Datei“ > „Info“ > „Arbeitsmappe schützen“ > „Immer schreibgeschützt öffnen“.

### <a name="excel-security-updates"></a>Excel: Sicherheitsupdates
-   [CVE-2018-8331](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8331): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung
-   [CVE-2018-8429](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8429): Microsoft Excel – Sicherheitsrisiko bei der Offenlegung von Informationen
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8375): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8379): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8382): Microsoft Excel – Sicherheitsrisiko bei der Offenlegung von Informationen
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8246): Microsoft Excel – Sicherheitsrisiko bei der Offenlegung von Informationen
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8248): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8147): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8148): Microsoft Excel – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8162): Microsoft Excel – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8163): Microsoft Excel – Sicherheitsrisiko bei der Offenlegung von Informationen
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-1029): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, bei dem Excel möglicherweise abstürzt, wenn die Quelldaten eines Diagramms von seinem ursprünglichen Satz von Zellen geändert werden.
-   Behebung eines Problems, bei dem eine Neuberechnung beim Öffnen nicht ausgeführt wird, auch wenn die FullCalcOnLoad-Eigenschaft festgelegt ist.  
-   Behebung eines Problems, bei dem das falsche Jahr angezeigt wird, wenn ein japanischer Kalender im Datumszellenformat verwendet wird.
-   Beim Importieren von Daten in das Excel-Datenmodell führen eingehende negative Nullwerte zu einem Fehler. Der Fehler wurde behoben, indem solche Werte als null importiert werden.
-   Behebung eines Problems, bei dem bei einem Gruppierungsvorgang bzw. beim Aufheben der Gruppierung in einer Excel-PivotTable manchmal ein Absturz verursacht wird.
-   Behebung eines Problems, aufgrund dessen Excel bei Diagrammaktionen abstürzen kann.
-   Behebung eines Problems, bei dem das Power View-Add-In für einige Benutzer versehentlich deaktiviert wurde.
-   Behebung eines Problems, bei dem die während der Dokumentwiederherstellung erstellten temporären Dateien für die automatische Wiederherstellung nie bereinigt wurden.
-   Behebung eines Problems, bei dem beim Versuch, eine neue Verbindung mit einer Textdatei in einer geschützten Arbeitsmappe herzustellen, die Fehlermeldung „Die Arbeitsmappe ist geschützt und kann nicht geändert werden“ angezeigt wurde.
-   Problem behoben, bei dem die Verwendung des Schnelldrucks für eine Excel-Arbeitsmappe, die einer Outlook-E-Mail angefügt war, nicht funktionierte.
-   Problem behoben, bei dem Excel beim Klicken auf einen Link möglicherweise abstürzte.
-   Problem behoben, bei dem Excel beim Verwenden der Cubefunktionen abstürzte.

### <a name="outlook-feature-updates"></a>Outlook: Featureupdates
 - **Verbesserungen an der Barrierefreiheitsprüfung:** Die Barrierefreiheitsprüfung weist eine aktualisierte Unterstützung für internationale Standards und Empfehlungen auf, sodass Sie leichter auf Ihre Nachrichten zugreifen können. [Weitere Informationen](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
 - **Verwalten von Profilen aus der Profilauswahl:** Wenn Sie die Profilauswahl beim Starten von Outlook verwenden, können Sie jetzt Änderungen vornehmen, ohne zur Systemsteuerung zu wechseln. In der Profilauswahl können Sie Profile erstellen und löschen und Einstellungen ändern.
- **Integrierte Barrierefreiheit:** Sorgen Sie dafür, dass jeder auf Ihre Nachrichten zugreifen kann, indem Sie beschreibenden Alternativtext zu Ihren Bildern hinzufügen.
- **Outlook-Add-In-Warnungen:** Gelegentlich können bei einem Outlook-COM-Add-In Probleme auftreten, die Outlook insgesamt verlangsamen. Diese Probleme können in der Latenz von Ereignissen begründet sein, z. B. beim Wechseln zwischen Outlook-Ordnern, Eintreffen neuer E-Mails, Öffnen von Kalenderelementen usw. Wenn diese Probleme auftreten, zeigt Outlook eine Warnung in der Benachrichtigungsleiste an.
- **Andere Besprechungsteilnehmer kennen:** Sie können jetzt die Antworten anderer Personen auf eine Besprechungsanfrage sehen, selbst wenn Sie nicht der Organisator sind.
- **So verpassen Sie keine Erinnerung mehr:** Legen Sie Erinnerungen so fest, dass sie über Fenstern angezeigt werden, in denen Sie arbeiten. Andernfalls blinkt Outlook in der Taskleiste, damit Sie darauf aufmerksam werden. [Weitere Informationen](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **Markieren Sie gelöschte Elemente als gelesen:** Sie können jetzt jede Nachricht, die Sie löschen, als gelesen markieren. Klicken Sie hierfür auf „Datei \> Optionen \> E-Mail \> Andere“.
- **Drei Zeitzonen anzeigen:** Sie müssen eine Besprechung über mehrere Zeitzonen hinweg planen? Fügen Sie Ihrem Kalender mehrere Zeitzonen hinzu, um die Verfügbarkeit von Personen anzuzeigen und eine Zeit auszuwählen, die für alle passt. [Weitere Informationen](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)
- **Optimierte Benutzeroberfläche zum Erstellen einer Gruppe:** Wir haben die Benutzeroberfläche zum Erstellen einer Gruppe optimiert; sie sieht nun moderner und übersichtlicher aus.[ Weitere Informationen](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)

### <a name="outlook-security-updates"></a>Outlook: Sicherheitsupdates
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8310): Sicherheitsrisiko der Manipulation in Microsoft Office
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8244): Sicherheitsanfälligkeit in Microsoft Outlook bezüglich Rechteerweiterungen
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8150): Sicherheitsanfälligkeit in Microsoft Outlook bezüglich Umgehung von Sicherheitsfunktionen
-   [ADV180021](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/ADV180021): Microsoft Office – Intensiver Schutz – Update

### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebt ein Problem, bei dem die VBA-IDE beim Ändern der Systemsprache in Japanisch und bei der Eingabe von japanischen Zeichen in die VBA-IDE beim Laden in Outlook einfriert.
-   Behebung eines Problems, aufgrund dessen das Wechseln zum Ordner „Postausgang“ oder „Gesendete Elemente“ den Absturz von Outlook verursacht.
-   Behebung eines Problems, aufgrund dessen alle Teilnehmer Meeting-Aktualisierungen erhalten, wenn sich der Meeting-Text oder Anlagen ändern, statt optional eine Meeting-Aktualisierung an die Teilnehmer zu senden.
-   Behebung eines Problems, aufgrund dessen Benutzer aufgrund einer Änderung in der Benutzer-Agent-Zeichenfolge keine Verbindung zu EWS- und REST-Endpunkten herstellen können.
-   Problem behoben, bei dem nach Aktualisierung des Besprechungorts den Teilnehmern weiterhin der alte Ort angezeigt wurde, anstelle des neuen.
-   Problem behoben, bei dem bei der Vorschau einer Anlage im Lesebereich ein Fehler angezeigt wurde.
-   Problem behoben, bei dem Outlook beim Auflösen von Anzeigenamen in E-Mail-Adressen abstürzte, wenn der Benutzer eine E-Mail verfasste.
-   Problem behoben, bei dem einige Benutzer die Funktionen nicht nutzen konnten, die von Ihrem Mandantenadministrator aktiviert wurden.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Featureupdates 
- **AutoSpeichern für Clouddateien ist nun standardmäßig aktiviert:** AutoSpeichern ist in der Version vom September 2018 Halbjährlicher Kanal (gezielt) standardmäßig aktiviert. Diese Änderung bedeutet, dass Benutzer sich keine Sorgen darüber machen müssen, dass Änderungen in Dokumenten verloren gehen, die in OneDrive oder SharePoint Online gespeichert sind. Änderungen werden automatisch in der Cloud gespeichert, und Benutzer müssen nicht mehr explizit STRG + S drücken oder auf die Schaltfläche „Speichern“ klicken. Allerdings müssen die Benutzer diese Verhaltensänderung verstehen, damit sie keine versehentlichen Änderungen an Präsentationen vornehmen. Beachten Sie, dass Benutzer das automatische Speichern mithilfe der Umschalttaste „AutoSpeichern“ deaktivieren können. Es wird empfohlen, dass Sie Ihre Benutzer über diese bevorstehende Änderung informieren und sie dahingehend schulen, wie dieses neue Feature in Office 365 optimal genutzt werden kann.[Weitere Informationen zu AutoSpeichern](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Erfahren Sie, was IT-Administratoren über AutoSpeichern wissen sollten](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Freihandkonvertierung:** Konvertieren Sie Notizen und Zeichnungen in lesbaren Text und gestochen scharfe Formen, um eine ansprechende Präsentation zu erstellen. [Weitere Informationen](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)
- **Verbesserte SVG-Unterstützung:** Sie können SVGs einfügen, auf die Filter angewendet wurden. [Weitere Informationen](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Einfügen von Titeln für Ihre Folien mit einem Stift:** Verwenden Sie den Stift, um per Freihand einen Titel einzugeben, und sehen Sie zu, wie PowerPoint diesen in Text konvertiert. [Weitere Informationen](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Vermeiden unerwünschter Bearbeitungen:** Legen Sie fest, dass Ihre Arbeitsmappen schreibgeschützt geöffnet werden, um versehentliche Änderungen zu verhindern. Wechseln Sie zu „Datei“ > „Info“ > „Arbeitsmappe schützen“ > „Immer schreibgeschützt öffnen“.
- **Verbesserungen an der Barrierefreiheitsprüfung:** Die Barrierefreiheitsprüfung weist eine aktualisierte Unterstützung für internationale Standards und Empfehlungen auf, sodass Sie leichter auf Ihre Präsentationen zugreifen können. [Weitere Informationen](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, bei dem Tabellen mit dicken Rahmen nicht ordnungsgemäß gerendert wurden.
-   Behebung eines Problems, bei ein möglicher Absturz beim Ändern der Shape.Visibile-Eigenschaft auftreten könnte.
-   Behebung eines Problems, bei dem Änderungen an gemeinsam erstellten Dokumenten nicht zusammengeführt werden können.
-   Behebung eines Problems, bei dem Dokumente mit ActiveX-Steuerelementen zu einem Fehler bei der gemeinsamen Erstellung führen würden.
-   Behebung eines Problems, aufgrund dessen PowerPoint bei der Rechtschreibprüfung in Shapes abstürzt.
-   Behebung eines Problems, aufgrund dessen PowerPoint beim Öffnen einer Datei aus SharePoint Online abstürzt.
-   Behebung eines Problems, aufgrund dessen der Wiederherstellungsbereich bei Aktivierung von AutoSpeichern inkorrekt angezeigt wird.
-   Behebung eines Problems, aufgrund dessen die Anmeldung nicht angezeigt wird, wodurch ein Benutzer nicht auf eine Datei zugreifen kann.
-   Behebung eines Problems, bei dem das gemeinsame Arbeiten mehrerer Benutzer an einer Präsentation in einer falschen Duplikation der Folienmaster resultierte.
-   Behebung eines Problems, bei dem das Öffnen einer in OneDrive gespeicherten Datei im Absturz von PowerPoint beim Beenden der geschützten Ansicht resultierte.

### <a name="project-feature-updates"></a>Project: Featureupdates 
- **Sprintverwaltung:** Schnelles Hinzufügen, Aktualisieren oder Löschen von agilen Sprints.
- **Taskboardfilterung:** Optimieren Sie Ihre Taskboards, indem Sie nach wichtigen Ressourcen oder Sammelvorgängen filtern.
- **Festlegen der abgeschlossenen Prozent über ein Taskboard:** Wählen Sie für jede Spalte die abgeschlossenen Prozent aus, und aktualisieren Sie den Abschluss der Aufgabe dann per Drag & Drop.
- **Sprintnavigation:** Wechseln Sie von einer Sprintansicht zur anderen, und verschieben Sie schnell Aufgaben zwischen Sprints.
- **Neue Möglichkeit zum Verwalten von Sprints:** Verwenden Sie einen agilen Ansatz zum Arbeiten mit Taskboards. In der Sprintverwaltung können Sie Sprints hinzufügen und entfernen, wenn sich Ihr Projekt weiterentwickelt.
- **Organisiert bleiben mit zuletzt verwendeten Speicherorten:** In Project wird eine fortlaufende Liste davon geführt, wo Sie andere Projekte gespeichert haben. Wenn Sie bereit sind, Ihr Projekt zu speichern, wählen Sie einfach einen der zuletzt verwendeten Speicherorte aus, und arbeiten Sie weiter.

### <a name="project-non-security-updates"></a>Project: Nicht sicherheitsrelevante Sicherheitsupdates
- Behebt ein Problem, bei dem verhindert wird, dass Sie ein Unterprojekt speichern, wenn Sie damit im Kontext eines Masterprojekts arbeiten.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems im Zusammenhang mit der Unterstützung von TLS 1.2. (Hinweis: Dies ist dieselbe Lösung, die in Hinweisen vom 10. April erwähnt wurde; diese wird hier im Rahmen des September-Rollups erneut erwähnt.)
-   Behebung eines Problems beim Hinzufügen von Benutzern, bei dem durch das Auswählen von „Skype-Anruf“ in einem Meeting ein Fehler verursacht wird.
-   Entfernung einer Eingabeaufforderung, in welcher der Benutzer aufgefordert wurde, Skype-Koordinaten zu einer Besprechung hinzuzufügen, wenn ein Skype Room als Ort hinzugefügt wurde und die Besprechung bereits Besprechungskoordinaten für ein Team enthält.
-   Behebung eines Problems, bei dem der Speicherort gefüllt wird, selbst wenn „UseLocationForE911Only“ auf „true“ festgelegt wird.
-   Behebung eines Problems, bei dem Skype for Business hängt, wenn die Option „Anruf über Konferenzcenter“ zum Einladen von Benutzern aus der Liste verwendet wird.
-   Behebung eines Problems, bei dem Outlook (ausgeführt auf einem Terminalserver) einfriert, während ein Skype for Business-Meeting erstellt wird.
-   Ändern Sie den Standardwert „EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket“ auf „true“.

### <a name="visio-feature-updates"></a>Visio: Featureupdates
- **Synchronisierung von Diagrammen und Datenquellen:** Wenn Sie ein Datenschnellansichtsdiagramm in Visio bearbeiten, haben Sie die Möglichkeit, die verknüpften Excel-Quelldaten entsprechend dem neusten Diagramminhalt zu aktualisieren.
- **Auditvorlage für Datenschnellansicht:** Importieren Sie Inhalte aus Excel und erstellen Sie Auditdiagramme für finanzielle Transaktionen, Bestandsverwaltung und mehr.
- **Startdiagramme:** Das Organigramm, Brainstormingdiagramm und SDL-Vorlagen verfügen über neue Startdiagramme für einen leichteren Einstieg.
 - **Erstellen eines Word-Dokuments aus Visio-Shapes:** Fügen Sie einem Word-Dokument automatisch Diagramminhalte wie Shapes und Metadaten hinzu. Passen Sie dann das Dokument an, um Vorgangsanleitungen und Betriebshandbücher zu erstellen. [Weitere Informationen](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="word-feature-updates"></a>Word: Featureupdates
- **AutoSpeichern für Clouddateien ist nun standardmäßig aktiviert:** AutoSpeichern ist in der Version vom September 2018 Halbjährlicher Kanal (gezielt) standardmäßig aktiviert. Diese Änderung bedeutet, dass Benutzer sich keine Sorgen darüber machen müssen, dass Änderungen in Dokumenten verloren gehen, die in OneDrive oder SharePoint Online gespeichert sind. Änderungen werden automatisch in der Cloud gespeichert, und Benutzer müssen nicht mehr explizit STRG + S drücken oder auf die Schaltfläche „Speichern“ klicken. Allerdings müssen die Benutzer diese Verhaltensänderung verstehen, damit sie keine versehentlichen Änderungen an Präsentationen vornehmen. Beachten Sie, dass Benutzer das automatische Speichern mithilfe der Umschalttaste „AutoSpeichern“ deaktivieren können. Es wird empfohlen, dass Sie Ihre Benutzer über diese bevorstehende Änderung informieren und sie dahingehend schulen, wie dieses neue Feature in Office 365 optimal genutzt werden kann.[Weitere Informationen zu AutoSpeichern](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Erfahren Sie, was IT-Administratoren über AutoSpeichern wissen sollten]
- **Verbesserungen an der Barrierefreiheitsprüfung:** Die Barrierefreiheitsprüfung weist eine aktualisierte Unterstützung für internationale Standards und Empfehlungen auf, sodass Sie leichter auf Ihre Dokumente zugreifen können. [Weitere Informationen](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Verbesserte SVG-Unterstützung:** Sie können SVGs einfügen, auf die Filter angewendet wurden. [Weitere Informationen](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-security-updates"></a>Word: Sicherheitsupdates
-   [CVE-2018-8430](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8430): Word – Sicherheitsrisiko bei PDF-Remotecodeausführung
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0919): Microsoft Office – Sicherheitsrisiko bei der Offenlegung von Informationen

### <a name="word-non-security-updates"></a>Word: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, durch das eine Meldung zu nicht ausreichend Speicher angezeigt wurde.
-   Es wurde eine Reihe von Problemen behoben, die einige Benutzer am Öffnen von IRM-geschützten Dokumenten und E-Mails hinderten, die von Personen in anderen Organisationen für sie freigegeben wurden.
-   Probleme mit der Leistung wurden behoben.

### <a name="office-suite-security-updates"></a>Office-Suite: Sicherheitsupdates
-   [CVE-2018-8332](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8332): Win32k – Sicherheitsrisiko bei PDF-Remotecodeausführung
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8378): Microsoft Office – Sicherheitsrisiko bei der Offenlegung von Informationen
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8281): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8157): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8158): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0950): Sicherheitsanfälligkeit in Microsoft Office bezüglich Veröffentlichung von Informationen
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-1026): Microsoft Office – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-1030): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung
-   
  **Flash-, Silverlight- und Shockwave-Steuerelemente können in Office aus Sicherheitsgründen nicht aktiviert werden:** Aus Sicherheitsgründen wird in neuen Builds von Microsoft Office für Office 365 unter Windows die Aktivierung von Flash-, Silverlight- und Shockwave-Steuerelemente blockiert. Weitere Informationen finden Sie [hier](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729) und [hier](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US).

### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Updates
-  Behebung eines Problems, bei dem das Installieren eines Updates unter bestimmten Umständen sehr lange dauert.
-  Behebung eines Problems, bei dem beim Öffnen einer Anwendung eine Meldung über das Starten im abgesicherten Modus angezeigt wurde und die Anwendung nicht geöffnet werden konnte.
-  Probleme mit der Leistung wurden behoben.

## <a name="version-1803-august-14"></a>Version 1803: 14. August
*Version 1803 (Build 9126.2275)*

### <a name="access-security-updates"></a>Access: Sicherheitsupdates
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8312):Sicherheitsanfälligkeit in Microsoft Access bezüglich Remotecodeausführung

### <a name="excel-security-updates"></a>Excel: Sicherheitsupdates
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8375): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8379): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8382): Microsoft Excel – Sicherheitsrisiko bei der Offenlegung von Informationen 

### <a name="outlook-security-updates"></a>Outlook: Sicherheitsupdates
-   [ADV180021](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/ADV180021): Microsoft Office – Intensiver Schutz – Update 

### <a name="office-suite-security-updates"></a>Office-Suite: Sicherheitsupdates
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8378): Microsoft Office – Sicherheitsrisiko bei der Offenlegung von Informationen 

## <a name="version-1803-july-10"></a>Version 1803: 10. Juli
*Version 1803 (Build 9126.2259)*

### <a name="access-security-updates"></a>Access: Sicherheitsupdates
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8312):Sicherheitsanfälligkeit in Microsoft Access bezüglich Remotecodeausführung

### <a name="outlook-security-updates"></a>Outlook: Sicherheitsupdates
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8310): Sicherheitsrisiko der Manipulation in Microsoft Office

### <a name="office-suite-security-updates"></a>Office-Suite: Sicherheitsupdates
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8281): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, bei dem das falsche Jahr angezeigt wird, wenn ein japanischer Kalender im Datumszellenformat verwendet wird.
-   Beim Importieren von Daten in das Excel-Datenmodell führen eingehende negative Nullwerte zu einem Fehler. Der Fehler wurde behoben, indem solche Werte als null importiert werden.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, bei dem Tabellen mit dicken Rahmen nicht ordnungsgemäß gerendert wurden.

### <a name="project-non-security-updates"></a>Project: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, bei dem eine Kostenressource nicht ordnungsgemäß aktualisiert wird, wenn eine Aufgabe mit einer Kostenressource geteilt wurde, und die Kosten verloren gingen.
-   Behebung eines Problems, aufgrund dessen nur Aufgaben aus dem ersten Sammelvorgang im Dialogfenster angezeigt werden, wenn vorhandene Aufgaben einer Zeitachse in der Zeitachsenansicht hinzugefügt werden.
-   Behebung eines Problems, bei dem die Speicherung im XML-Format für Hauptprojekte in Project Online oder Project Server fehlschlägt.

### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Fehlers, bei dem das Installieren eines Updates unter bestimmten Umständen sehr lange dauert. 
-   Behebung eines Problems, bei dem SVG-Tests fehlschlagen.
-   Behebung eines Problems, bei dem bei der Bereitstellung von Updates mithilfe des Konfigurations-Managers auf einem Client, auf dem Office-Anwendungen ausgeführt werden, das Update nicht angewendet wurde, nachdem das Gerät neu gestartet wurde, während Office-Anwendungen ausgeführt werden.


## <a name="version-1803-june-12"></a>Version 1803: 12. Juni
*Version 1803 (Build 9126.2227)*

### <a name="excel-security-updates"></a>Excel: Sicherheitsupdates
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8246): Microsoft Excel – Sicherheitsrisiko bei der Offenlegung von Informationen
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8248): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, bei dem bei einem Gruppierungsvorgang bzw. beim Aufheben der Gruppierung in einer Excel-PivotTable manchmal ein Absturz verursacht wird.

### <a name="outlook-security-updates"></a>Outlook: Sicherheitsupdates
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8244): Sicherheitsanfälligkeit in Microsoft Outlook bezüglich Rechteerweiterungen

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, bei ein möglicher Absturz beim Ändern der Shape.Visibile-Eigenschaft auftreten könnte.
-   Behebung eines Problems, bei dem Änderungen an gemeinsam erstellten Dokumenten nicht zusammengeführt werden können.
-   Behebung eines Problems, bei dem Dokumente mit ActiveX-Steuerelementen zu einem Fehler bei der gemeinsamen Erstellung führen würden.

### <a name="project-non-security-updates"></a>Project: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, aufgrund dessen nur Aufgaben aus dem ersten Sammelvorgang im Dialogfenster angezeigt werden, wenn vorhandene Aufgaben einer Zeitachse in der Zeitachsenansicht hinzugefügt werden.

### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, bei dem bei der Bereitstellung von Updates mithilfe des Konfigurations-Managers auf einem Client, auf dem Office-Anwendungen ausgeführt werden, das Update nicht angewendet wurde, nachdem das Gerät neu gestartet wurde, während Office-Anwendungen ausgeführt werden.



## <a name="version-1803-may-18"></a>Version 1803: 18. Mai
*Version 1803 (Build 9126.2210)*

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Updates
- Behebung eines Problems, aufgrund dessen Excel bei Diagrammaktionen abstürzen kann.
- Behebung eines Problems, bei dem das Power View-Add-In für einige Benutzer versehentlich deaktiviert wurde.
- Behebung eines Problems, bei dem die während der Dokumentwiederherstellung erstellten temporären Dateien für die automatische Wiederherstellung nie bereinigt wurden.
- Behebung eines Problems, bei dem beim Versuch, eine neue Verbindung mit einer Textdatei in einer geschützten Arbeitsmappe herzustellen, die Fehlermeldung „Die Arbeitsmappe ist geschützt und kann nicht geändert werden“ angezeigt wurde.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Nicht sicherheitsrelevante Updates
- Behebung eines Problems, aufgrund dessen PowerPoint bei der Rechtschreibprüfung in Shapes abstürzt.

### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Updates
- Behebung eines Problems, aufgrund dessen beim Öffnen einer Anwendung eine Meldung über das Starten im abgesicherten Modus angezeigt wird und die Anwendung nicht geöffnet werden kann.



## <a name="version-1803-may-8"></a>Version 1803: 8. Mai
*Version 1803 (Build 9126.2191)*

### <a name="excel-security-updates"></a>Excel: Sicherheitsupdates
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8147): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8148): Microsoft Excel – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8162): Microsoft Excel – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8163): Microsoft Excel – Sicherheitsrisiko bei der Offenlegung von Informationen

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Updates
-   Behebung eines Problems, aufgrund dessen Excel beim Öffnen einer Datei aus SharePoint Online abstürzt.
-   Behebung eines Problems, aufgrund dessen mit „Drucken“ oder „Vorschau drucken“  nur ein Teil des Arbeitsblatts gedruckt oder angezeigt wird, wobei der Inhalt an einem Datenschnitt im Arbeitsblatt abgeschnitten wird.

### <a name="outlook-security-updates"></a>Outlook: Sicherheitsupdates
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8150): Sicherheitsanfälligkeit in Microsoft Outlook bezüglich Umgehung von Sicherheitsfunktionen

### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Updates
-   Behebung eines Problems, aufgrund dessen das Wechseln zum Ordner „Postausgang“ oder „Gesendete Elemente“ den Absturz von Outlook verursacht.
-   Behebung eines Problems, aufgrund dessen alle Teilnehmer Meeting-Aktualisierungen erhalten, wenn sich der Meeting-Text oder Anlagen ändern, statt optional eine Meeting-Aktualisierung an die Teilnehmer zu senden.
-   Behebung eines Problems, aufgrund dessen Benutzer aufgrund einer Änderung in der Benutzer-Agent-Zeichenfolge keine Verbindung zu EWS- und REST-Endpunkten herstellen können.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Nicht sicherheitsrelevante Updates
-   Behebung eines Problems, aufgrund dessen PowerPoint beim Öffnen einer Datei aus SharePoint Online abstürzt.
-   Behebung eines Problems, aufgrund dessen der Wiederherstellungsbereich bei Aktivierung von AutoSpeichern inkorrekt angezeigt wird.
-   Behebung eines Problems, aufgrund dessen die Anmeldung nicht angezeigt wird, wodurch ein Benutzer nicht auf eine Datei zugreifen kann.

### <a name="project-non-security-updates"></a>Project: Nicht sicherheitsrelevante Updates
-   Behebung eines Problems, aufgrund dessen die Verwendung der AutoFilter-Dropdownliste für eine Datumsspalte dazu führt, dass alle Aufgaben im Projekt ausgeblendet werden.
-   Behebung eines Problems, aufgrund dessen nur Aufgaben aus dem ersten Sammelvorgang im Dialogfenster angezeigt werden, wenn vorhandene Aufgaben einer Zeitachse in der Zeitachsenansicht hinzugefügt werden.

### <a name="word-non-security-updates"></a>Word: Nicht sicherheitsrelevante Updates
-   Behebung eines Problems, aufgrund dessen Word beim Öffnen einer Datei aus SharePoint Online abstürzt.
-   Behebung eines Problems, aufgrund dessen kleingeschriebene römische Seitenzahlen inkorrekt in Großschreibung geändert werden.

### <a name="office-suite-security-updates"></a>Office-Suite: Sicherheitsupdates
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8157): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-8158): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung



## <a name="version-1803-april-10"></a>Version 1803: 10. April
*Version 1803 (Build 9126.2152)*

### <a name="excel-security-updates"></a>Excel: Sicherheitsupdates
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-1029): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, bei dem das gemeinsame Arbeiten mehrerer Benutzer an einer Präsentation in einer falschen Duplikation der Folienmaster resultierte.
-   Behebung eines Problems, bei dem das Öffnen einer in OneDrive gespeicherten Datei im Absturz von PowerPoint beim Beenden der geschützten Ansicht resultierte.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems im Zusammenhang mit der Unterstützung von TLS 1.2.

### <a name="word-non-security-updates"></a>Word: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, durch das eine Meldung zu nicht ausreichend Speicher angezeigt wurde.

### <a name="office-suite-security-updates"></a>Office-Suite: Sicherheitsupdates
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0950): Sicherheitsanfälligkeit in Microsoft Office bezüglich Veröffentlichung von Informationen
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-1026): Microsoft Office – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-1030): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung



## <a name="version-1803-march-20"></a>Version 1803: 20. März
*Version 1803 (Build 9126.2098)*

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Updates
-   Problem behoben, bei dem die Verwendung des Schnelldrucks für eine Excel-Arbeitsmappe, die einer Outlook-E-Mail angefügt war, nicht funktionierte.
-   Problem behoben, bei dem Excel beim Klicken auf einen Link möglicherweise abstürzte.
-   Problem behoben, bei dem Excel beim Verwenden der Cubefunktionen abstürzte.

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive for Business: Nicht sicherheitsrelevante Sicherheitsupdates
-   Problem behoben, bei dem OneDrive for Business (Groove.exe) die Auslastung eines einzelnen Kerns (zum Beispiel 25 % bei einer CPU mit 4 Kernen) für längere Zeit im Task Manager beanspruchte.

### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Updates
-   Problem behoben, bei dem nach Aktualisierung des Besprechungorts den Teilnehmern weiterhin der alte Ort angezeigt wurde, anstelle des neuen.
-   Problem behoben, bei dem bei der Vorschau einer Anlage im Lesebereich ein Fehler angezeigt wurde.
-   Problem behoben, bei dem Outlook beim Auflösen von Anzeigenamen in E-Mail-Adressen abstürzte, wenn der Benutzer eine E-Mail verfasste.
-   Problem behoben, bei dem einige Benutzer die Funktionen nicht nutzen konnten, die von Ihrem Mandantenadministrator aktiviert wurden.

### <a name="word-non-security-updates"></a>Word: Nicht sicherheitsrelevante Updates
-   Problem behoben, bei dem Word auf Computern unter Windows 7 ohne das [Update für Benutzerfreundlichkeit und Diagnosetelemetrie nicht geöffnet](https://support.microsoft.com/help/3080149/update-for-customer-experience-and-diagnostic-telemetry)werden konnte.
-   Problem behoben, bei dem Aufzählungszeichen in Listen nicht gedruckt wurden.



## <a name="version-1803-march-13"></a>Version 1803: 13. März
*Version 1803 (Build 9126.2072)*

### <a name="access-security-updates"></a>Access: Sicherheitsupdates
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0903): Sicherheitsanfälligkeit in Microsoft Access bezüglich Remotecodeausführung

### <a name="access-non-security-updates"></a>Access: Nicht sicherheitsrelevante Updates
-   Behebung eines Problems, aufgrund dessen beim Öffnen einer Access-Laufzeitanwendung (ACCDE-Datei) die Fehlermeldung „Diese Datenbank weist ein unbekanntes Format auf“ ausgegeben und die Anwendung nicht geöffnet wird.
-   Behebung eines Problems, aufgrund dessen bei Auswahl von Text in einem Text- oder Kombinationsfeld anscheinend der gesamte Text anstelle der angegebenen Auswahl ausgewählt wird.

### <a name="excel-feature-updates"></a>Excel: Featureupdates
-   **Microsoft Translator:** Übersetzen Sie Wörter, Ausdrücke oder Sätzen in eine andere Sprache mit Microsoft Translator. Dies ist über die Registerkarte „Überprüfen“ im Menüband möglich.
-   **Konvertieren von SVG-Symbolen in Shapes:** Wandeln Sie alle SVG-Bilder und -Symbole in Office-Shapes um, sodass Sie deren Farbe, Größe oder Textur ändern können.
-   **Aufheben der Auswahl von Zellen:** Treffen Sie eine Auswahl im Arbeitsblatt, und heben Sie die Auswahl von Zellen auf, auf die Sie versehentlich geklickt haben, ohne von vorne beginnen zu müssen.
-   **Schneller Zugriff auf Ihre Websites und Gruppen:** Verwenden Sie das Menü „Datei“ zum Arbeiten mit Dokumenten, die in Ihren häufig verwendete Websites und Gruppen gespeichert sind.
-   **Digitaler Bleistift:** Schreiben oder skizzieren Sie Ideen mit unserer neuen Bleistifttextur. Durch einfaches Neigen können Sie Schattierungen mit unterstützten digitalen Stiften hinzufügen.
-   **Einstellung von LinkedIn-Funktionen:** Wechseln Sie zu „Datei“ \> „Optionen“ \> „Allgemein“, um zu steuern, ob LinkedIn-Funktionen in Ihren Office-Anwendungen angezeigt werden. [Weitere Informationen](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **3D Modelle:** Verwenden Sie 3D, um den visuellen Eindruck und die kreativen Möglichkeiten der Arbeitsmappen zu erhöhen.  Fügen Sie auf einfache Weise ein 3D-Modell ein, das Sie um 360 Grad drehen können. [Weitere Informationen](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Neue Freihand-Effekte:** Drücken Sie Ihre Ideen mit Metallic-Stiften und Freihand-Effekten wie Regenbogen, Galaxy, Lava, Ozean, Gold, Silber und vielem mehr auf besondere Weise aus.
-   **Benutzeroberfläche für Dateifreigabe:** Wenn Benutzer bei OneDrive for Business- oder SharePoint-Dateien auf die Schaltfläche „Freigeben“ in der oberen rechte Ecke des Menübands klicken oder „Datei“ \> „Freigeben“ wählen, wird ein vereinfachtes und verbessertes Freigabedialogfeld geöffnet. Für neue oder lokal gespeicherte Dateien ermöglicht die Benutzeroberfläche das problemlose Hochladen von Dateien auf OneDrive, um mit der Zusammenarbeit zu beginnen.
-   **Blockieren gefährlicher Erweiterungen:** Erweiterungen, die als riskant eingestuft werden und als OLE-Paketobjekte eingebettet sind, werden standardmäßig blockiert. Diese sind zum Beispiel .exe, .vbs und .js. [Mehr erfahren](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **Hilfreiche Sounds verbessern die Barrierefreiheit:** Aktivieren Sie Audiohinweise, um Sie bei der Arbeit zu leiten. Sie finden sie unter „Datei“ \> „Optionen“ \> „Erleichterte Bedienung“. Kein Add-In erforderlich. [Weitere Informationen](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Dateispeicherorte nach Konto:** Beim Öffnen oder Speichern einer Datei wird die Liste der Orte nach dem zugeordneten Konto organisiert.
-   **Stiftanpassung:** Wählen Sie einen persönlichen Satz von Stiften und Textmarkern für die Freihandeingabe aus. Ihr benutzerdefinierter Satz steht Ihnen dann auf all Ihren Windows-PCs zur Verfügung.

### <a name="excel-security-updates"></a>Excel: Sicherheitsupdates
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2017-11877): Umgehung von Sicherheitsfunktionen in Microsoft Office Excel
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2017-11878): Microsoft Excel – Sicherheitsrisiko durch Arbeitsspeicherbeschädigung
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2017-11884): Microsoft Office – Sicherheitsrisiko durch Arbeitsspeicherbeschädigung
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0796): Microsoft Excel – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0841): Microsoft Excel – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0907): Umgehung von Sicherheitsfunktionen in Microsoft Office Excel
-   [Empfehlung 170021](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/ADV170021): Microsoft Office – Intensiver Schutz – Update

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Updates
-   Behebung eines Problems, bei dem Excel beim Auswählen einer neuen Schriftart auf der Registerkarte „Start“ oder beim Bearbeiten nicht mehr reagiert, wenn Ihre Bearbeitungssprache Japanisch, Chinesisch oder Koranisch ist.
-   Behebung eines Problems, bei dem Bildlaufleisten fehlen, wenn eine Arbeitsmappe geöffnet wird, wenn Excel minimiert ist.
-   Behebung eines Problems, aufgrund dessen Arbeitsmappenverweise fehlschlagen, wenn Sie mehrere Arbeitsmappen durch Doppelklicken auf die Dateinamen im Datei-Explorer öffnen.
-   Behebung eines Problems, aufgrund dessen Excel abstürzt, wenn nach der programmgesteuerten Erstellung einer PivotTable eine programmgesteuerte Aktualisierung ausgeführt wird.
-   Behebung eines Problems, aufgrund dessen der programmgesteuerte Aufruf von Workbook.Open() zum Absturz von Excel führen kann.
-   Behebung eines Problems, aufgrund dessen die Fehlermeldung „Schwerwiegender Fehler“ beim Öffnen einer Office 2007- oder älteren Arbeitsmappe (XLS oder XLA) mit Makros nicht richtig angezeigt wurde.
-   Behebung eines Problems, aufgrund dessen Excel möglicherweise abstürzte, wenn ein Benutzer ein Kontextmenü öffnete.
-   Behebung eines Problems, aufgrund dessen Excel abstürzt, wenn der Benutzer beim Versuch, ein Objekt in eine vorhandene Arbeitsmappe einzufügen, auf „Durchsuchen“ klickt.
-   Behebung eines Problems, aufgrund dessen beim Schützen eines Bereichs mit einem Kennwort das Dialogfeld zur Eingabe des Kennworts zum Aufheben der Bereichssperre nicht angezeigt wird.
-   Behebung eines Problems, aufgrund dessen ein Benutzer eine Arbeitsmappe in der geschützten Ansicht nicht schließen kann, wenn der Dateiname eckige Klammern enthält.
-   Behebung eines Problems, aufgrund dessen die Platzierung der QuickInfo beim Ziehen oder Füllen durch Ziehen nicht korrekt ausgerichtet ist.
-   Behebung eines Problems, aufgrund dessen beim Speichern einer Arbeitsmappe mit „Datei“ \> „Speichern unter“ Dateinamen mit Punkten im Dialogfeld „Datei speichern“ leer oder abgeschnitten angezeigt werden.
-   Behebung eines Problems, aufgrund dessen beim Speichern einer durch Synchronisieren gesicherten Datei Office die Datei nicht auf Datenträger schreibt, sondern weiter auf OneDrive hochlädt. Mit diesem Fix wird Benutzern jetzt eine Fehlermeldung angezeigt, und der Upload wird nicht fortgesetzt.

### <a name="outlook-feature-updates"></a>Outlook: Featureupdates
-   **Einfaches Sortieren Ihrer E-Mails:** Aufgrund Ihres Feedbacks bieten wir für Benutzer, die den Posteingang mit Fokus nicht verwenden, wieder das Sortieren der Nachrichtenliste und den Filter für ungelesene Nachrichten an.
-   **Konvertieren von SVG-Symbolen in Formen:** Wandeln Sie alle SVG-Bilder und -Symbole in Office-Formen um, sodass Sie deren Farbe, Größe oder Textur ändern können.
-   **Verbesserungen bei Office 365-Gruppen:** Das Lesen von und Antworten auf Gruppen-Chats ist einfacher als je zuvor, da Sie auf eine Gruppennachricht doppelklicken können, um sie in einem eigenen Fenster zu öffnen.
-   **Einstellung von LinkedIn-Funktionen:** Wechseln Sie zu „Datei“ \> „Optionen“ \> „Allgemein“, um zu steuern, ob LinkedIn-Funktionen in Ihren Office-Anwendungen angezeigt werden. [Weitere Informationen](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **3D Modelle:** Verwenden Sie 3D, um den visuellen Eindruck und die kreativen Möglichkeiten der E-Mails zu erhöhen.  Fügen Sie auf einfache Weise ein 3D-Modell ein, das Sie um 360 Grad drehen können. [Weitere Informationen](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Profilkarte:** Zeigt Ihnen die wichtigsten Details zu Personen und Gruppen an, unabhängig davon, ob Sie ein Desktop, das Web oder eine mobile App verwenden.
-   **Hinzufügen eines Termins zu einem Gruppenkalender:** Jetzt können Sie alle Benutzer in Ihrer Gruppe informieren, dass Sie abwesend sein werden, ohne eine Besprechung in einer E-Mail senden zu müssen.
-   **Herunterladen von Cloudanlagen:** Wenn Sie OneDrive-Anlagen auf Ihrem Computer speichern oder mit Drag & Drop dort ablegen, wird die Datei für Sie heruntergeladen.
-   **Hilfreiche Sounds verbessern die Barrierefreiheit:** Aktivieren Sie Audiohinweise, um Sie bei der Arbeit zu leiten. Sie finden sie unter „Datei“ \> „Optionen“ \> „Erleichterte Bedienung“. Kein Add-In erforderlich. [Weitere Informationen](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Posteingang mit Fokus:** Der Posteingang ist in zwei Registerkarten unterteilt: „Fokus“ und „Andere“. Nachrichten werden basierend auf dem Inhalt der Nachricht und dem Benutzer sortiert, mit dem Sie am häufigsten interagieren. [Weitere Informationen](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)
-   **Schneller Zugriff auf Ihre am häufigsten verwendeten Gruppen:** Gruppen, mit denen Sie wahrscheinlich am häufigsten interagieren, werden nun am Anfang der Liste unter „Gruppen“ im Ordnerbereich angezeigt.

### <a name="outlook-security-updates"></a>Outlook: Sicherheitsupdates
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2017-11939): Sicherheitsanfälligkeit in Microsoft Office bezüglich Veröffentlichung von Informationen
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0791): Microsoft Outlook – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0850): Microsoft Outlook – Sicherheitsrisiko bei Rechteerweiterungen
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook – Sicherheitsrisiko durch Arbeitsspeicherbeschädigung

### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Updates
-   Behebung eines Problems, bei dem die Suche mit der Meldung „Keine Übereinstimmungen gefunden“ fehlschlägt, wenn der Suchbereich auf „Alle Postfächer“ festgelegt ist.
-   Behebung eines Problems, aufgrund dessen Outlook beim Wechseln zwischen Ordnern abstürzt, wenn mit Accessible Event Watcher (AccEvent.exe) überwacht wird.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Featureupdates
-   **Microsoft Translator:** Übersetzen Sie Wörter, Ausdrücke oder Sätzen in eine andere Sprache mit Microsoft Translator. Dies ist über die Registerkarte „Überprüfen“ im Menüband möglich.
-   **3D-Animationen:** Erwecken Sie Ihre 3D-Modelle mit Animationen wie leichtem Schwingen oder Springen und Drehen zum Leben.
-   **Konvertieren von SVG-Symbolen in Formen:** Wandeln Sie alle SVG-Bilder und -Symbole in Office-Formen um, sodass Sie deren Farbe, Größe oder Textur ändern können.
-   **Roaming der Revisionsnachverfolgungsinformationen:** Der Status gelesen/ungelesen zum Hervorheben von freigegebenen Folien, die von anderen Benutzern geändert wurden, wird nun im Roamingdienst gespeichert (statt auf dem lokalen Computer des Benutzers), sodass diese Informationen über mehrere Geräte oder Plattformen hinweg synchronisiert werden können.
-   **Schneller Zugriff auf Ihre Websites und Gruppen:** Verwenden Sie das Menü „Datei“ zum Arbeiten mit Dokumenten, die in Ihren häufig verwendete Websites und Gruppen gespeichert sind.
-   **Digitaler Bleistift:** Schreiben oder skizzieren Sie Ideen mit unserer neuen Bleistifttextur. Durch einfaches Neigen können Sie Schattierungen mit unterstützten digitalen Stiften hinzufügen.
-   **Einstellung von LinkedIn-Funktionen:** Wechseln Sie zu „Datei“ \> „Optionen“ \> „Allgemein“, um zu steuern, ob LinkedIn-Funktionen in Ihren Office-Anwendungen angezeigt werden. [Weitere Informationen](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Ausführen einer Bildschirmpräsentation mit digitalem Stift:** Verwenden Sie den Surface-Stift oder einen anderen Stift mit einer Bluetooth-Taste, um durch die Präsentation zu blättern. Windows 10 Fall Creators Update ist erforderlich. [Weitere Informationen](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)
-   **3D Modelle:** Verwenden Sie 3D, um den visuellen Eindruck und die kreativen Möglichkeiten Ihrer Präsentationen zu erhöhen. Erwecken Sie 3D-Modelle in Ihren Präsentationen zum Leben, indem Sie Übergänge wie Morphen verwenden, die kinoähnliche Animationen zwischen Folien erstellen. [Weitere Informationen](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Neue Freihand-Effekte:** Drücken Sie Ihre Ideen mit Metallic-Stiften und Freihand-Effekten wie Regenbogen, Galaxy, Lava, Ozean, Gold, Silber und vielem mehr auf besondere Weise aus.
-   **Benutzeroberfläche für Dateifreigabe:** Wenn Benutzer bei OneDrive for Business- oder SharePoint-Dateien auf die Schaltfläche „Freigeben“ in der oberen rechte Ecke des Menübands klicken oder „Datei“ \> „Freigeben“ wählen, wird ein vereinfachtes und verbessertes Freigabedialogfeld geöffnet. Für neue oder lokal gespeicherte Dateien ermöglicht die Benutzeroberfläche das problemlose Hochladen von Dateien auf OneDrive, um mit der Zusammenarbeit zu beginnen.
-   **Blockieren gefährlicher Erweiterungen:** Erweiterungen, die als riskant eingestuft werden und als OLE-Paketobjekte eingebettet sind, werden standardmäßig blockiert. Diese sind zum Beispiel .exe, .vbs und .js. [Mehr erfahren](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **Hervorheben von Revisionen:** Folien, die von anderen Benutzern geändert wurden, werden hervorgehoben.
-   **Während Ihrer Abwesenheit:** PowerPoint zeigt Ihnen an, wer Ihre freigegebene Präsentation seit Ihrem letzten Besuch bearbeitet hat.
-   **Verbesserung am Designer:** Designer empfiehlt jetzt Designideen für Zeitachsen in einer Aufzählung.
-   **Hilfreiche Sounds verbessern die Barrierefreiheit:** Aktivieren Sie Audiohinweise, um Sie bei der Arbeit zu leiten. Sie finden sie unter „Datei“ \> „Optionen“ \> „Erleichterte Bedienung“. Kein Add-In erforderlich. [Weitere Informationen](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Dateispeicherorte nach Konto:** Beim Öffnen oder Speichern einer Datei wird die Liste der Orte nach dem zugeordneten Konto organisiert.
-   **Stiftanpassung:** Wählen Sie einen persönlichen Satz von Stiften und Textmarkern für die Freihandeingabe aus. Ihr benutzerdefinierter Satz steht Ihnen dann auf all Ihren Windows-PCs zur Verfügung.
-   **Verbesserung am Designer:** Der Designer schlägt jetzt Designideen für Diagramme vor, die Ihren Folien hinzugefügt werden.
-   **Schnellstarter:** Erstellt automatisch eine Gliederung, um Benutzer dabei zu unterstützen, mit der Recherche zu einem Thema ihrer Wahl zu beginnen. [Weitere Informationen](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)
-   **Digitales Lineal:** Wechseln Sie auf Geräten mit Touchscreens zu Zeichnen \> Lineal, und verwenden Sie dann den Stift oder Finger, um gerade Linien zu zeichnen oder eine Gruppe von Objekten auszurichten. [Weitere Informationen](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)

### <a name="powerpoint-security-updates"></a>PowerPoint: Sicherheitsupdates
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2017-11934): Sicherheitsanfälligkeit in Microsoft Office bezüglich Veröffentlichung von Informationen

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Nicht sicherheitsrelevante Updates
-   Behebung eines Problems, aufgrund dessen das Entfernen von Dokumenteigenschaften und persönlichen Informationen dazu führt, dass beim Speichern in SharePoint ein Fehler auftritt.
-   Behebung eines Problems, aufgrund dessen bei Verweisen auf Flash Player-basierte YouTube-Einbindungscodes ein neues Fenster zum Wiedergeben des Videos geöffnet wird. Alte Einbindungscodes wurden aktualisiert und verweisen jetzt auf HTML5-basierte YouTube-Videos, sodass diese korrekt im gleichen Fenster wiedergegeben werden.
-   Behebung eines Problems, aufgrund dessen beim Speichern einer durch Synchronisieren gesicherten Datei Office die Datei nicht auf Datenträger schreibt, sondern weiter auf OneDrive hochlädt. Mit diesem Fix wird Benutzern jetzt eine Fehlermeldung angezeigt, und der Upload wird nicht fortgesetzt.

### <a name="project-feature-updates"></a>Project: Featureupdates
-   **Task Board-Ansicht:** Sortieren Sie Aufgaben auf Karten in der Task Board-Ansicht. Ordner Sie Karten neu an, und verschieben Sie sie zwischen den Spalten im Board, genau wie in Agile-Projekten.
-   **Agile-Projekte:** Verwalten Sie Ihre Agile-Projekte mit Backlogs, Task Boards, Sprints usw. Sowohl Scrum- als auch Kanban-Methoden werden unterstützt. [Weitere Informationen](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)  
-   **Verwalten einer Aufgabe im Planer:** Verknüpfen Sie eine Projektaufgabe mit dem Planer, und erstellen Sie einen Plan dafür. Unterteilen Sie die Aufgabe in Teilaufgaben, fügen Sie ein Team hinzu, weisen Sie Aufgaben zu, und verwalten Sie die Arbeit auf einem Task Board.

### <a name="project-non-security-updates"></a>Project: Nicht sicherheitsrelevante Updates
-   Behebung eines Problems, bei dem der Wert MOD\_DATE durch Festlegen von mehr als einer Grundlinie in einer Sitzung als identisch festgelegt wird.
-   Behebung eines Problems, bei dem Ist-Arbeit weiterhin in den Berichterstellungstabellen angezeigt wird, nachdem es in einer „Für die Freigabe speichern“-Sitzung entfernt wurde.
-   Behebung eines Problems in der deutschen Version, bei dem die Verwendung des Wochen-Datumsformats einen Fehler bei der Planung zurückgibt.
-   Behebung eines Problems, bei dem beim Bearbeiten von Enddatumsangaben im Planungs-Webpart Aufgaben bei 8 Stunden pro Tag bleiben und nicht über einen Zeitraum aufgeteilt werden.
-   Behebung eines Problems, bei dem „Fortschrittspunkt-Form“  an einer unerwarteten Position gezeichnet wird.
-   Behebung eines Problems, aufgrund dessen VBA-Code in Projekten verloren geht.
-   Behebung eines Problems, aufgrund dessen Vorgänge als abgeschlossen angezeigt werden, auch wenn noch verbleibende Arbeit vorliegt.
-   Behebung eines Problems, aufgrund dessen Project bei Verwendung des Features „Aufgabenpfad“ nicht mehr reagiert.
-   Behebung eines Problems, aufgrund dessen an der Zeitskala die Zeitskalabeschriftungen nicht angezeigt werden.
-   Behebung eines Problems, aufgrund dessen grafische Berichte unvollständige Informationen enthalten oder gar nicht erstellt werden.
-   Behebung eines Problems, aufgrund dessen eine Datei bei Problemen beim Speichern beschädigt wurde und Project beim Öffnen abstürzte.
-   Behebung eines Problems, aufgrund dessen Aufgaben in den Ansichten „Zeitachse“ und „Timeplaner“ nicht gezogen werden konnten.
-   Behebung eines Problems, aufgrund dessen die Ressourcenverfügbarkeit nicht in Team Builder angezeigt wird.
-   Behebung eines Problems, aufgrund dessen grafische Indikatoren nicht ordnungsgemäß angezeigt werden.
-   Behebung eines Problems, aufgrund dessen Project beim Abgleich auf Stunden- oder Tagesbasis abstürzt.
-   Behebung eines Problems beim Arbeiten mit Haupt-/Teilprojekten aus einer SharePoint-Dokumentbibliothek.
-   Behebung eines Problems, aufgrund dessen beim Hinzufügen von Zuweisungen zu einem Vorgang mit fester Dauer eine namenlose Ressource entstehen kann.
-   Behebung eines Problems, aufgrund dessen eine falsche Fehlermeldung bzgl. einer Änderung von geschützter Arbeit ausgegeben wird.
-   Behebung eines Problems, aufgrund dessen Project beim Wechseln zu Berichten mit mehreren Bildern möglicherweise abstürzt.

### <a name="publisher-feature-updates"></a>Publisher: Featureupdates
-   **Blockieren gefährlicher Erweiterungen:** Erweiterungen, die als riskant eingestuft werden und als OLE-Paketobjekte eingebettet sind, werden standardmäßig blockiert. Diese sind zum Beispiel .exe, .vbs und .js. [Mehr erfahren](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="publisher-non-security-updates"></a>Publisher: Nicht sicherheitsrelevante Updates
-   Behebung eines Problems, aufgrund dessen es beim Filtern von Datenquellenfeldern mit NULL-Werten (leer) zu Fehlern kommt, wenn der Seriendruck-Assistent ausgeführt wird.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Nicht sicherheitsrelevante Updates
-   Behebung eines Problems beim Hinzufügen von Benutzern, bei dem durch das Auswählen von „Skype-Anruf“ in einem Meeting ein Fehler verursacht wird.
-   Entfernung einer Eingabeaufforderung, in welcher der Benutzer aufgefordert wurde, Skype-Koordinaten zu einer Besprechung hinzuzufügen, wenn ein Skype Room als Ort hinzugefügt wurde und die Besprechung bereits Besprechungskoordinaten für ein Team enthält.
-   Behebung eines Problems, bei dem der Speicherort gefüllt wird, selbst wenn „UseLocationForE911Only“ auf „true“ festgelegt wird.
-   Behebung eines Problems, bei dem Skype for Business hängt, wenn die Option „Anruf über Konferenzcenter“ zum Einladen von Benutzern aus der Liste verwendet wird.
-   Behebung eines Problems, bei dem Outlook (ausgeführt auf einem Terminalserver) einfriert, während ein Skype for Business-Meeting erstellt wird.
-   Ändern Sie den Standardwert „EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket“ auf „true“.
-   Behebung eines Problems, bei dem die Schaltflächen „Weitere Optionen“ und „Weitere Personen einladen“ ausgeblendet sind, wenn sich eine Besprechung im Vollbildmodus befindet.
-   Behebung eines Problems, bei dem das P2P-Audioanruffenster oder das Telefonkonferenzfenster transparent wird, wenn Sie versuchen, an dem Anruf teilzunehmen.
-   Behebung eines Problems, bei dem anstehende Skype-Besprechungen nicht auf der Registerkarte „Besprechungen“ angezeigt werden.
-   Behebung eines Problems, bei dem beim Hinzufügen von Audio zu einer Besprechung ein neuer P2P-Anruf mit dem Benutzer selbst initiiert wird anstatt Audio zu der bestehenden Besprechung hinzuzufügen, wenn Skype for Business so konfiguriert ist, dass es ohne Audio an Besprechungen teilnehmen kann.
-   Behebung eines Problems bei dem der Benutzer die Fehlermeldung „Diese Skype-Besprechung wurde nicht gefunden“ erhält, wenn er in einer Besprechungsanfrage in Outlook auf den Link „An Skype-Besprechung teilnehmen“ klickt.
-   In der Popup-Benutzeroberfläche für eingehende PSTN-Anrufe wurde eine Schaltfläche zur Anrufweiterleitung hinzugefügt.
-   Sie können Benutzer benachrichtigen, dass Anrufe und Chat an Teams gesendet werden, wenn ChatDefaultClient und CallDefaultClient auf „Teams“ festgelegt sind.
-   Die Anwesenheit eines Benutzers kann als „Offline“ angezeigt werden, wenn ein Benutzer nicht an einer Besprechung teilnimmt und in Skype for Business deaktiviert ist und die Benutzeroberfläche zum Beitreten zu einer Besprechung auf den nativen eingeschränkten Client festgelegt ist.
-   Wenn Skype for Business auf den Infobereich minimiert wird, werden alle Optionen außer „Öffnen“ und „Beenden“ deaktiviert.
-   Neue Anrufe und Unterhaltungen werden beim Koppeln mit Aries Smartphones  unterdrückt, wenn RedirectClient aktiviert ist.
-   Behebung eines Problems, aufgrund dessen das Suchen nach Nachrichten in PChat nach Datum fehlschlägt, wenn das Datumsformat auf ein anderes als das US-Format (mm/tt/jj) festgelegt ist.
-   Behebung eines Problems, aufgrund dessen bei auf „false“ festgelegter EnableExternalP2PFileTransfer-Richtlinie Benutzer weiterhin Dateien in Besprechungen anfügen können.
-   Behebung eines Problems, aufgrund dessen in den aufgezeichneten Unterhaltungen der Anrufer anstelle des Angerufenen angezeigt wurde. Dies geschah dann, wenn die geschäftliche Telefonnummer des Angerufenen mithilfe von Active Directory geändert wurde.
-   Behebung eines Problems, aufgrund dessen bei ausgehenden PSTN-Anrufen an Mobiltelefone die Empfängerinformationen im Anrufprotokoll nicht in den aufgezeichneten Anrufen angezeigt wurden.
-   Behebung eines Problems, aufgrund dessen beim Initiieren einer Chatnachricht aus einer E-Mail in Outlook die Betreffzeile der E-Mail nicht im Betreff der Chatnachricht enthalten war.
-   Behebung eines Problems, aufgrund dessen die Unterhaltungen übereinander gestappelt wurden, wenn die Chatunterhaltungsfenster auf einer Seite angedockt waren.
-   Behebung eines Problems, aufgrund dessen die VbSS-Bildschirmfreigabeanforderungen in einer VDIv2-Umgebung als RDP-basierte Anforderungen angezeigt wurden.
-   Behebung eines Problems, aufgrund dessen bei einer nicht erfolgreichen Anrufdurchstellung anstelle des Angerufenen der Anrufer in der Fehlermeldung aufgeführt wurde.
-   Behebung eines Problems, aufgrund dessen die Schaltfläche „Mit Teams beginnen“ im Banner zur Weiterleitung zum Clientupgrade ausgeblendet war.
-   Behebung von Problemen mit der DPI-Skalierung in Chatfenstern.
-   Behebung eines Problems, aufgrund dessen LinkedIn-Daten nicht in der Skype for Business-Visitenkarte angezeigt wurden.
-   Möglichkeit zum Beenden des Empfangs von Anrufen durch Benutzer im Namen eines Sammelanschlusses wurde hinzugefügt.
-   Möglichkeit zum automatischen Halten von Anrufen in Fällen, in denen ein Anruf in Skype for Business oder Teams aktiv ist und ein neuer Anruf empfangen oder initiiert wird, wurde hinzugefügt.
-   Behebung eines Problems, aufgrund dessen Benutzer nach einer Vollbildfreigabe nicht chatten können.
-   Behebung eines Problems, aufgrund dessen Benutzer in der Lobby nicht benachrichtigt werden, wenn ihr Beitritt zum Meeting verweigert wird.
-   Behebung eines Problems, aufgrund dessen die automatische Verstärkung während Anrufen unkontrolliert zunimmt.
-   Behebung eines Problems, aufgrund dessen Benutzer keinen Referenten in den Besprechungsoptionen auswählen können, wenn ein Ressourcenpostfach eines Konferenzraums zu einer Besprechungseinladung hinzugefügt wird.
-   Behebung eines Problems, aufgrund dessen die Schaltfläche für die Desktopfreigabe während eines Peer-to-Peer-Videoanrufs abgeblendet dargestellt wird, wenn AllowlPVideo auf „false“ festgelegt ist.
-   Behebung eines Problems, aufgrund dessen Chatnachrichten deaktiviert bleiben, nachdem die Einstellung in den Besprechungsoptionen für vorhandene Besprechungen, die mit der Option „Chat deaktivieren“ erstellt wurden, in „Chat aktivieren“ geändert wurde.
-   Behebung eines Problems, aufgrund dessen die QuickInfo nicht angezeigt wird, wenn Sie den Mauszeiger über die Schaltfläche „Link einfügen“ im Chatfenster bewegen, und kein Barrierefreiheitsname angezeigt wird, wenn die Schaltfläche ausgewählt wird.

### <a name="visio-feature-updates"></a>Visio: Featureupdates
-   **Integrierte Datenbankmodelldiagramme:** Verwenden Sie die neue Vorlage „Datenbankmodelldiagramm“, um Ihre Datenbank akkurat als Visio-Diagramm zu modellieren. Kein Add-In erforderlich.
-   **Weitere Schablonen für Geschäftsdiagramme:** Verwenden Sie moderne Shapes, vergleichen Sie Daten mit einem Venn-Diagramm, oder erstellen Sie Zyklus-, Matrix- oder Pyramidendiagramme, um Ihre Geschichte zu erzählen.
-   **Erstellen eines Drahtmodelldiagramms für eine Website:** Erstellen Sie schnell ein Drahtmodelldiagramm einer Website, einschließlich Benutzeroberfläche, Navigation und wie sie zusammenarbeiten. [Weitere Informationen](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **Erstellen Sie ein Drahtmodell Ihrer mobilen Anwendung:** Verwenden Sie eine Vorlage, um ein Drahtmodell Ihrer mobilen Anwendung zu erstellen. [Weitere Informationen](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **Anwenden von Datengrafiken auf Datenschnellansichtdiagramme:** Sparen Sie Zeit beim Erstellen eines Datenschnellansichtdiagramms, indem Sie Shape-Daten automatisch als Datengrafiken anwenden. [Weitere Informationen](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)
-   **Zusammenarbeiten an Zeichnungen:** Arbeiten Sie mit anderen Personen zusammen, indem Sie Ihre Zeichnungen in OneDrive for Business oder SharePoint Online freigeben. Sie können sehen, wer an der Zeichnung arbeitet, Kommentare hinzufügen und Dateiaktivität anzeigen. [Weitere Informationen](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)
-   **Blockieren gefährlicher Erweiterungen:** Erweiterungen, die als riskant eingestuft werden und als OLE-Paketobjekte eingebettet sind, werden standardmäßig blockiert. Diese sind zum Beispiel .exe, .vbs und .js. [Mehr erfahren](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="word-feature-updates"></a>Word: Featureupdates
-   **Konvertieren von SVG-Symbolen in Shapes:** Wandeln Sie alle SVG-Bilder und -Symbole in Office-Shapes um, sodass Sie deren Farbe, Größe oder Textur ändern können.
-   **Zeichenanzahl:** Zeigen Sie die Anzahl der Zeichen auf der Statusleiste während der Eingabe an. Sie können dies im Menü „Statusleiste anpassen“ aktivieren.
-   **Schneller Zugriff auf Ihre Websites und Gruppen:** Verwenden Sie das Menü „Datei“ zum Arbeiten mit Dokumenten, die in Ihren häufig verwendete Websites und Gruppen gespeichert sind.
-   **Microsoft Translator:** Übersetzen Sie mit Microsoft Translator Wörter, Ausdrücke oder das gesamte Dokument direkt in Word in eine andere Sprache. [Weitere Informationen](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)
-   **Digitaler Bleistift:** Schreiben oder skizzieren Sie Ideen mit unserer neuen Bleistifttextur. Durch einfaches Neigen können Sie Schattierungen mit unterstützten digitalen Stiften hinzufügen.
-   **Einstellung von LinkedIn-Funktionen:** Wechseln Sie zu „Datei“ \> „Optionen“ \> „Allgemein“, um zu steuern, ob LinkedIn-Funktionen in Ihren Office-Anwendungen angezeigt werden. [Weitere Informationen](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **SharePoint-Eigenschaftenbereich:** Anzeigen und Bearbeiten von Spaltenwerten der SharePoint-Dokumentbibliothek von einem Dokument aus. Eine Menübandschaltfläche auf der Registerkarte „Ansicht“ bietet einfachen Zugriff auf den Bereich, und SharePoint-Administratoren können eine Dokumentbibliothekeinstellung verwenden, um den Eigenschaftenbereich automatisch zu öffnen.
-   **3D Modelle:** Verwenden Sie 3D, um den visuellen Eindruck und die kreativen Möglichkeiten der Dokumente zu erhöhen.  Fügen Sie auf einfache Weise ein 3D-Modell ein, das Sie um 360 Grad drehen können. [Weitere Informationen](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Neue Freihand-Effekte:** Drücken Sie Ihre Ideen mit Metallic-Stiften und Freihand-Effekten wie Regenbogen, Galaxy, Lava, Ozean, Gold, Silber und vielem mehr auf besondere Weise aus.
-   **Benutzeroberfläche für Dateifreigabe:** Wenn Benutzer bei OneDrive for Business- oder SharePoint-Dateien auf die Schaltfläche „Freigeben“ in der oberen rechte Ecke des Menübands klicken oder „Datei“ \> „Freigeben“ wählen, wird ein vereinfachtes und verbessertes Freigabedialogfeld geöffnet. Für neue oder lokal gespeicherte Dateien ermöglicht die Benutzeroberfläche das problemlose Hochladen von Dateien auf OneDrive, um mit der Zusammenarbeit zu beginnen.
-   **Blockieren gefährlicher Erweiterungen:** Erweiterungen, die als riskant eingestuft werden und als OLE-Paketobjekte eingebettet sind, werden standardmäßig blockiert. Diese sind zum Beispiel .exe, .vbs und .js. [Mehr erfahren](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **Bearbeiten mit Lerntools:** Lerntools sind jetzt im Weblayout von Word verfügbar. Sie können während der Bearbeitung den Textabstand anpassen und Silben anzeigen. In jeder Ansicht wird das jeweilige Wort hervorgehoben, wenn das Dokument laut vorgelesen wird. [Weitere Informationen](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)
-   **LaTeX-Syntax:** Erstellen und bearbeiten Sie mathematische Formeln mit LaTeX-Syntax.
-   **Hilfreiche Sounds verbessern die Barrierefreiheit:** Aktivieren Sie Audiohinweise, um Sie bei der Arbeit zu leiten. Sie finden sie unter „Datei“ \> „Optionen“ \> „Erleichterte Bedienung“. Kein Add-In erforderlich. [Weitere Informationen](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Dateispeicherorte nach Konto:** Beim Öffnen oder Speichern einer Datei wird die Liste der Orte nach dem zugeordneten Konto organisiert.
-   **Stiftanpassung:** Wählen Sie einen persönlichen Satz von Stiften und Textmarkern für die Freihandeingabe aus. Ihr benutzerdefinierter Satz steht Ihnen dann auf all Ihren Windows-PCs zur Verfügung.
-   **Verbesserte Unterstützung beim Verfassen im Editorbereich:** Verwenden Sie den Editorbereich für erweiterte Empfehlungen zu Rechtschreibung, Grammatik und Schreibstil. Der Zugriff ist dank verbesserter Unterstützung mithilfe von Hilfstechnologien möglich.

### <a name="word-security-updates"></a>Word: Sicherheitsupdates
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0792): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0794): Microsoft Word – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0798): Microsoft Office – Sicherheitsrisiko durch Arbeitsspeicherbeschädigung
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0801): Microsoft Office – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0802): Microsoft Office – Sicherheitsrisiko durch Arbeitsspeicherbeschädigung
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0804): Microsoft Word – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0805): Microsoft Word – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0806): Microsoft Word – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0807): Microsoft Word – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0812): Microsoft Word – Sicherheitsrisiko durch Arbeitsspeicherbeschädigung
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0919): Microsoft Office – Sicherheitsrisiko bei der Offenlegung von Informationen
-   [Empfehlung 170020](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/ADV170020): Microsoft Office – Intensiver Schutz – Update

### <a name="word-non-security-updates"></a>Word: Nicht sicherheitsrelevante Updates
-   Behebung eines Problems, aufgrund dessen Word abstürzt, wenn ein Benutzer versucht, ein vorhandenes Dokument mit „Speichern unter“ auf OneDrive for Business zu speichern und den Speichervorgang dann abbricht oder versucht, vorhandene Änderungen zusammenzuführen.
-   Behebung eines Problems, aufgrund dessen es beim Filtern von Datenquellenfeldern mit Nullwerten (leer) zu Fehlern kommt, wenn der Seriendruck-Assistent ausgeführt wird.
-   Behebung eines Problems, aufgrund dessen beim Speichern einer durch Synchronisieren gesicherten Datei Office die Datei nicht auf Datenträger schreibt, sondern weiter auf OneDrive hochlädt. Mit diesem Fix wird Benutzern jetzt eine Fehlermeldung angezeigt, und der Upload wird nicht fortgesetzt.
-   Behebung eines Problems, aufgrund dessen beim Entfernen des IRM-Schutzes für ein Dokument der Schutz nicht entfernt wird.

### <a name="office-suite-security-updates"></a>Office-Suite: Sicherheitsupdates
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2017-11882):Sicherheitsanfälligkeit in Microsoft Office bezüglich Arbeitsspeicherbeschädigung
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0795): Microsoft Office – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0851): Microsoft Office – Sicherheitsrisiko durch Arbeitsspeicherbeschädigung
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0853): Microsoft Office – Sicherheitsrisiko bei der Offenlegung von Informationen
-   [Empfehlung 180003](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/ADV180003): Microsoft Office – Intensiver Schutz – Update

### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Updates
-   Behebung eines Problems, bei dem beim Öffnen einer Anwendung eine Meldung über das Starten im abgesicherten Modus angezeigt wurde und die Anwendung nicht geöffnet werden konnte.
-   Die Option „Jetzt aktualisieren“ ist unter „Datei“ \> „Konto“ \> „Updateoptionen“ ausgeblendet, wenn ein Office-COM-Objekt aktiviert ist, sodass Office 365-Clientupdates von Configuration Manager verwaltet werden.
-   Behebung eines Problems, aufgrund dessen die Office-App abstürzte, wenn der Benutzer versuchte, Office über das Dialogfeld „Office aktivieren“ zu aktivieren.
-   Behebung eines Problems beim Zoomen und Skalieren in Office-Add-Ins in der dynamischen DPI-Umgebung.
-   Behebung eines Problems, aufgrund dessen der CurrentStatus-Knoten des Office-Konfigurationsdienstanbieters (CSP) eine leere Zeichenfolge zurückgibt, auch wenn Office 365 ProPlus aktuell installiert ist.
-   Behebung eines Problems, das Änderungen des BOX-Dateiformats verursacht, was sich auf die Funktionalität älterer Office-Versionen auswirkt, die auf demselben Computer installiert sind, da BOX-Dateien von allen Versionen einer Office-App auf demselben Computer gemeinsam genutzt werden.



## <a name="version-1708-february-13"></a>Version 1708: 13. Februar
*Version 1708 (Build 8431.2215)*

### <a name="access-non-security-updates"></a>Access: Nicht sicherheitsrelevante Updates
-   Behebung eines Problems, bei dem beim Verwenden eines Formulars mit mehreren Elementen beim Anpassen der Position des Mausrads oder der Scrollleiste die in dem Formular angezeigten Elemente nicht geändert wurden.

### <a name="excel-security-updates"></a>Excel: Sicherheitsupdates
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0841): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung

### <a name="outlook-security-updates"></a>Outlook: Sicherheitsupdates
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0850): Sicherheitsanfälligkeit in Microsoft Outlook bezüglich Rechteerweiterungen
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0852): Microsoft Outlook – Sicherheitsrisiko durch Arbeitsspeicherbeschädigung

### <a name="office-suite-security-updates"></a>Office-Suite: Sicherheitsupdates
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0851): Sicherheitsanfälligkeit in Microsoft Office bezüglich Arbeitsspeicherbeschädigung
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0853): Sicherheitsanfälligkeit in Microsoft Office bezüglich Veröffentlichung von Informationen



## <a name="version-1708-january-9"></a>Version 1708: 9. Januar
*Version 1708 (Build 8431.2153)*

### <a name="excel-security-updates"></a>Excel: Sicherheitsupdates
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0796): Sicherheitsanfälligkeit in Microsoft Excel bezüglich Remotecodeausführung
-   [Empfehlung 170021](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/ADV170021): Microsoft Office – Intensiver Schutz – Update

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Updates
-   Behebung eines Problems, aufgrund dessen Excel abstürzt, wenn nach der programmgesteuerten Erstellung einer PivotTable eine programmgesteuerte Aktualisierung ausgeführt wird.

### <a name="outlook-security-updates"></a>Outlook: Sicherheitsupdates
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0791): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook – Sicherheitsrisiko bei Remotecodeausführung

### <a name="word-security-updates"></a>Word: Sicherheitsupdates
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0792): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0793): Microsoft Outlook – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0794): Microsoft Word – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0798): Microsoft Office – Sicherheitsrisiko durch Arbeitsspeicherbeschädigung
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0801): Microsoft Office – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0802): Microsoft Office – Sicherheitsrisiko durch Arbeitsspeicherbeschädigung
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0804): Microsoft Word – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0805): Microsoft Word – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0806): Microsoft Word – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0807): Microsoft Word – Sicherheitsrisiko bei Remotecodeausführung
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0812): Microsoft Word – Sicherheitsrisiko durch Arbeitsspeicherbeschädigung

### <a name="office-suite-security-updates"></a>Office-Suite: Sicherheitsupdates
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0795): Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung
-   [Empfehlung 180003](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/ADV180003): Microsoft Office – Intensiver Schutz – Update

### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Updates
-   Hinzufügen von Unterstützung für einmaliges Anmelden (SSO) für Domänenbenutzer für Office 365 Deutschland-Pläne, bei denen die Identität mit einem lokalen Active Directory verbunden ist.
-   Hinzufügen von Funktionen, mit denen Minderjährige am Abrufen und Aktivieren von Office-Add-Ins aus dem Office Store gehindert werden können.


> [!NOTE]
> Wenn Sie Hilfe bei einem Problem mit der Nutzung von Office benötigen, empfehlen wir, dass Sie Ihre Frage im [Microsoft Answers-Forum](https://answers.microsoft.com/) oder in der [Tech-Community](https://techcommunity.microsoft.com/) veröffentlichen, oder Sie können sich an den [Support](https://support.microsoft.com/contactus) wenden.

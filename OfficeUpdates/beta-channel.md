---
title: Anmerkungen zur Version für den Beta-Kanal
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt der Zielgruppe von Insiders Fast die aktuelle Liste neuer Features, Fehlerkorrekturen oder bekannter Probleme bereit.
ms.openlocfilehash: ab1953f105cbab856ac183335fb54edb538b5d43
ms.sourcegitcommit: 6bd9e41014037650170125aaed9847880d438645
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/19/2020
ms.locfileid: "44814304"
---
# <a name="release-notes-for-office-insiders"></a>Anmerkungen zu dieser Version für Office-Insider

Dieser Artikel enthält Versionshinweise für Beta-Kanal-Builds von Word, Excel, PowerPoint, Outlook, Access und Project für Windows-Desktop. Jede Woche werden interessante neue Features, wichtige Fehlerbehebungen und alle wichtigen Probleme, über die Sie informiert werden sollen, hervorgehoben. Beachten Sie, dass wir in einem bestimmten Zeitraum häufig Features (und manchmal sogar Fixes) auf den Beta-Kanal aufrollen. Auf diese Weise können wir sicherstellen, dass alles reibungslos funktioniert, bevor das Feature für ein breiteres Publikum bereitgestellt wird. Wenn Sie also unten nichts beschrieben sehen, machen Sie sich keine Sorgen, Sie werden es eventuell irgendwann erhalten.  

> [!IMPORTANT]
> Wir nehmen einige Änderungen an den Updatekanälen für Microsoft 365-Apps vor, unter anderem fügen wir einen neuen Updatekanal hinzu (monatlicher Enterprise-Kanal) und ändern die Namen der vorhandenen Updatekanäle. Um mehr zu erfahren, [lesen Sie diesen Artikel](https://go.microsoft.com/fwlink/p/?linkid=2127441).

> [!NOTE]
> - Versionshinweise werden wöchentlich veröffentlicht und können eine Kompilierung mehrerer Builds sein.
> - Das Veröffentlichungsdatum der Versionshinweise stimmt möglicherweise nicht mit dem tatsächlichen Veröffentlichungsdatum des Builds überein.

[//]: # (NICHT ENTFERNEN)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

## <a name="version-2007-june-19"></a>Version 2007:19. Juni
*Version 2007 (Build 13012,20000)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem customUI XML für eine benutzerdefinierte menübandregisterkarte beim Speichern einer Arbeitsmappe in SharePoint/OneDrive entfernt wurde.
- Es wurde ein Problem behoben, bei dem Arbeitsmappen schreibgeschützt waren, als die Datei nur mit Schreibschutz empfohlen wurde.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem das IME-Fenster (Input Method Editor) den zugrunde liegenden Text über den IME überlappen würde, wenn mehrere Monitore mit unterschiedlichen Auflösungen verwendet wurden.
- Es wurde ein Problem behoben, aufgrund dessen Benutzer den folgenden Fehler beim Schließen eines Termins sehen konnten, der zuvor gespeichert wurde: "das Element kann nicht gespeichert werden, da es von einem anderen Benutzer oder in einem anderen Fenster geändert wurde. Möchten Sie eine Kopie im Standardordner für das Element erstellen? "
- Es wurde ein Problem behoben, bei dem Datumsangaben im Minikalender für Benutzer in Japan nicht fett dargestellt wurden.
- Es wurde ein Problem behoben, aufgrund dessen Kalendererinnerungen keine genauen Zeiten für Besprechungen in weniger als einer Woche anzeigen konnten.

### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem der Anwesenheits Farbindikator eines Benutzers während einer Live-gemeinsamen Erstellungs Sitzung nicht im gemeinsamen Dokument Erstellungs Katalog aktualisiert wurde.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem, wenn feste Daueraufgaben bei 100% abgeschlossen sind, das tatsächliche Ende jedoch nicht angegeben ist, der Vorgang "% abgeschlossen" als weniger als 100% angezeigt wird.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem die Farbe des HTML-Hyperlinks nicht korrekt gerendert wurde.

### <a name="office-suite"></a>Office-Suite

- Es wurde ein Problem behoben, bei dem URLs, die nicht http oder HTTPS-basiert waren, nicht in der Liste der zuletzt verwendeten Listen angezeigt wurden.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2007-june-12"></a>Version 2007:12. Juni
*Version 2007 (Build 13006,20002)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Abrufen von Organisationsdaten aus Power BI mithilfe von Datentypen:** Excel-Datentypen von Power BI werden nun für Insider in Organisationen mit Office 365 E5/A5 oder Microsoft 365 E5/A5 bereit gerollt. Das erhalten der benötigten Informationen und das einfache aktualisieren ist für viele tägliche Workflows entscheidend. Wir geben Ihnen Zugriff auf Ihre Unternehmens-oder Organisationsinformationen von Power BI als einen Datentyp in Excel, wodurch die Möglichkeit erweitert wird, verknüpfte Informationen in Ihren Tabellen zu integrieren. [Weitere Informationen](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/).

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Access

- Es wurde ein Problem behoben, aufgrund dessen Microsoft Access Fehler beim Identifizieren einer Identitätsspalte in einer verknüpften SQL Server-Tabelle verursachte, was dazu führen könnte, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.

### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem die wichtigsten Rasterlinien von Radar Diagrammen nicht ordnungsgemäß formatiert werden konnten.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem das ProjectBeforeTaskChange-Ereignis nicht ausgelöst wurde, als es eine Änderung am Projektsammelvorgang gab, entweder im Feld Projektstart/-Vorgang.
- Es wurde ein Problem behoben, bei dem ein Baseline-Reset oder-Update Zeitphasen bezogene Kosten/Arbeitsressourcen ändern könnte und der Basisplan falsche Budgetwerte widerspiegeln könnte.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem die Möglichkeit, die Formatierung im Kommentarbereich über die Schaltfläche "Formatierung löschen" im Office-Menüband zu löschen, nicht funktionierte.
- Es wurde ein Problem behoben, bei dem das Ändern der Größe einer Tabelle, wenn das Lineal nicht angezeigt wird, dazu führte, dass andere Anwendungen, die im Hintergrund ausgeführt werden, mit dem blinken beginnen.
- Es wurde ein Problem behoben, bei dem im Modus "gemeinsame Dokumenterstellung" Kommentar Antworten manchmal nicht im Kommentarbereich angezeigt, aber im Bereich "Überarbeitung" angezeigt werden.
- Es wurde ein Problem behoben, bei dem bei einer Liste von mehr als 50 häufig geöffneten Dokumenten in Word ein Überarbeitungsverlauf angezeigt wird, nachdem ein Dokument gespeichert und geöffnet wurde, obwohl keine Änderungen an diesem Dokument vorgenommen wurden.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-june-05"></a>Version 2006: Juni 05
*Version 2006 (Build 13001,20002)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Sortieren/Filtern bei der Zusammenarbeit in Excel:** Sie können Ihre Excel-Datei jetzt sortieren und Filtern, während Sie mit anderen Personen zusammenarbeiten. Dieses neue Feature verhindert, dass Sie von den Sortierungen und Filtern anderer Benutzer betroffen sind, während Sie das Dokument gemeinsam erstellen.

- **Erstellen von PivotTables aus Datasets in Power BI in Excel:** Sie können PivotTables in Excel erstellen, die mit wenigen Klicks mit in Power BI gespeicherten Datasets verbunden sind.Auf diese Weise können Sie das Beste aus PivotTables und Power BI erhalten. Berechnen, zusammenfassen und Analysieren Ihrer Daten mit PivotTables aus ihren Secure Power BI-Datasets. [Weitere Informationen](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a>Outlook

- **Schnelles Öffnen von Elementen aus der vorherigen Sitzung:** Wir haben eine Option zum schnellen Öffnen von Elementen aus einer vorherigen Outlook-Sitzung hinzugefügt. Unabhängig davon, ob Outlook abstürzt oder geschlossen wird, können Sie die Elemente jetzt schnell neu starten, wenn Sie die APP erneut öffnen. Dieses Feature ist standardmäßig aktiviert. Wechseln Sie zum Deaktivieren der Option Optionen > allgemeine > Start Optionen.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem benutzerdefinierte Werte auf der Diagrammachse nicht ordnungsgemäß angewendet werden.
- Es wurde ein Problem behoben, bei dem Arbeitsblätter mit mehreren Formeln mit definierten Namen zu längeren Zeiten beim Speichern von Dateien führten.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem das Fenster IME (Input Method Editor) den zugrunde liegenden Text über den IME überlappen würde, wenn mehrere Monitore mit unterschiedlichen Auflösungen verwendet wurden.
- Es wurde ein Problem behoben, bei dem das Anzeigen einer Vorlage beim Erstellen einer neuen e-Mail-Nachricht zu einem Absturz führen würde.
- Es wurde ein Problem behoben, bei dem Benutzer nach Outlook, Version 1911, keine öffentlichen Ordner Exchange 2010 konnten.
- Es wurde ein Problem behoben, bei dem die Schaltfläche kategorisieren für Gruppenkalender im Office-Menüband deaktiviert wurde.
- Es wurde ein Problem behoben, aufgrund dessen Benutzer mit Konflikt verursachenden Kontakten in Outlook Abstürze abstürzen konnten.
- Es wurde ein Problem behoben, aufgrund dessen die Dropdownliste der Online Archive in Ordner Eigenschaften für Benutzer mit hohen dpi-Monitoren fehlte.
- Es wurde ein Problem behoben, aufgrund dessen Benutzer bei der Arbeit mit Hyperlinks in reinen Text-e-Mails einen Absturz in Outlook verursachten.
- Es wurde ein Problem behoben, aufgrund dessen Outlook keine langen Dateinamen analysieren konnte, die mit RFC2231 codiert wurden.
- Es wurde ein Problem behoben, aufgrund dessen Outlook-Benutzer bei der Verwendung von Bildschirmsprachausgaben nicht mehr reagierten.

### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem beim Öffnen von Server konfigurierten Dateien mit formularbasierter Authentifizierung behoben.
- Es wurde ein Problem behoben, bei dem PowerPoint-Dateien mit eingebetteten Diagrammen/Arbeitsmappen zu Fehlern beim Speichern der Datei führen könnten.
- Es wurde ein Problem behoben, bei dem ein Kommentarbereich, der vom Benutzer geschlossen wurde, automatisch erneut geöffnet wurde.
- Es wurde ein Problem behoben, bei dem sich der Folien Editor von einer Folie zur nächsten Folie hin überschneidet.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, aufgrund dessen verhindert wurde, dass verwaiste Aufgaben gelöscht oder erneut zugewiesen wurden, nachdem der übergeordnete Plan gelöscht wurde.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem Timestamps in Kommentar Bereichen nicht auf der Systemgebietsschema zeitbasierten.
- Es wurde ein Problem behoben, bei dem Kommentare zwischen der-Webanwendung und der Desktopanwendung nicht synchronisiert wurden.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)


## <a name="version2006may29"></a>Version 2006:29. Mai
*Version 2006 (Build 12920,20000)*

### <a name="featureupdates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Zusätzliche Schaltflächen zu Outlook-Popupbenachrichtigungen hinzugefügt:** Schaltflächen für die schnell Aktion werden jetzt in Outlook-Popupbenachrichtigungen angezeigt, wenn Outlook unter Windows 10 ausführt wird.

### <a name="powerpoint"></a>PowerPoint

- **Verbesserte Stream Videoleistung in PowerPoint:** Wir haben Verbesserungen an der Wiedergabeleistung von Microsoft Stream-Videos vorgenommen, um die Ladezeit von Videos zu minimieren und eine glatte Anzeige zu erzielen.  Verwenden Sie Ihre Unternehmensvideos aus Microsoft Stream, um bessere Präsentationen zu erstellen.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolvedissues"></a>Gelöste Probleme

### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem Excel gelegentlich beim Eingriff in OneDrive heruntergefahren wurde.
- Es wurde ein Problem behoben, bei dem durch Klicken auf einen mit einem Lesezeichen versehenen Hyperlink in derselben Arbeitsmappe das Ausblenden der Arbeitsmappe verursacht würde.
- Es wurde ein Problem behoben, bei dem einige kopierte und eingefügte Diagramm links anstelle universeller Adressen zugeordnete Laufwerks Adressen verwendeten.
- Es wurde ein Problem behoben, aufgrund dessen Excel möglicherweise nicht mehr reagiert, nachdem Sie STRG + UMSCHALT + Pfeiltasten verwendet haben, um zu scrollen, wenn das Excel-Fenster über Teams freigegeben wurde.

### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem Folien nach dem Zoomen mit dem Mausrad nicht zentriert wurden.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem das Kopieren und Einfügen von Text in einen Kommentarbereich nicht angezeigt würde.
- Es wurde ein Problem behoben, bei dem Kommentar-Hint Bubbles verschwommen bei 100% Zoom erschienen.
- Es wurde ein Problem behoben, bei dem das Aktivieren von Richtlinien Word 2007 und späteren binären Dokumenten und Vorlagen dazu führen würde, dass einige gemeinsame Dokument Erstellungs Fälle fehlschlagen.
- Es wurde ein Problem behoben, bei dem Dateien mit langen Pfadnamen (mehr als 32 KB) nicht geöffnet würden und eine entsprechende Fehlermeldung nicht angezeigt wurde.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2006-may-22"></a>Version 2006:22. Mai
*Version 2006 (Build 12914,20000)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **In fixierten Ordnern speichern:** Durch anheften Ihrer Ordner wird das Speichern von Office-Dateien vereinfacht. Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die verfügbaren Ordner erhalten möchten, wenn eine neue Datei gespeichert wird. Wir freuen uns darauf, Ihnen eine neue Funktion zu bieten: Heften Sie Ihre Ordner im Dialogfeld Speichern an. Mit dieser neuen Funktion können Sie Ihre Word-, Excel-und PowerPoint-Dateien einfacher speichern.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/).

### <a name="powerpoint"></a>PowerPoint

- **In fixierten Ordnern speichern:** Durch anheften Ihrer Ordner wird das Speichern von Office-Dateien vereinfacht. Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die verfügbaren Ordner erhalten möchten, wenn eine neue Datei gespeichert wird. Wir freuen uns darauf, Ihnen eine neue Funktion zu bieten: Heften Sie Ihre Ordner im Dialogfeld Speichern an. Mit dieser neuen Funktion können Sie Ihre Word-, Excel-und PowerPoint-Dateien einfacher speichern.<br />Einzelheiten finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/).

### <a name="word"></a>Word

- **In fixierten Ordnern speichern:** Durch anheften Ihrer Ordner wird das Speichern von Office-Dateien vereinfacht. Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die verfügbaren Ordner erhalten möchten, wenn eine neue Datei gespeichert wird. Wir freuen uns darauf, Ihnen eine neue Funktion zu bieten: Heften Sie Ihre Ordner im Dialogfeld Speichern an. Mit dieser neuen Funktion können Sie Ihre Word-, Excel-und PowerPoint-Dateien einfacher speichern.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/).

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, aufgrund dessen die Fehlermeldung: "diese Arbeitsmappe wird derzeit von einem anderen referenziert und nicht geschlossen werden kann" angezeigt wird, da Add-Ins in alphabetischer Reihenfolge geladen wurden, statt in einer benutzerdefinierten Reihenfolge.
- Es wurde ein Problem behoben, bei dem der Arbeitsspeicher beim Verwalten von Schriftarten zwischen Excel und einigen Anwendungen für Hilfstechnologien von Drittanbietern beschädigt wurde.
- Es wurde ein Problem behoben, bei dem Excel abstürzte, wenn Add-Ins nach Host Elementen in Arbeitsblättern Fragen, die Shapes mit noselect-Sperren enthalten.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem das Folder. BeforeItemMove-Ereignis nicht ordnungsgemäß ausgelöst wurde, wenn ein Benutzer Elemente zwischen Ordnern verschoben hat.
- Es wurde ein Problem behoben, bei dem Benutzer Kalenderelemente sahen, die den Mitternachts Schwellenwert als ganztägige Ereignisse überspannt haben.
- Es wurde ein Problem behoben, bei dem Outlook abstürzte, als zwei Add-Ins eine Schaltfläche zu derselben Gruppe im Menüband hinzugefügt haben.
- Es wurde ein Problem behoben, bei dem Benutzer keinen Kalender für einen Gastbenutzer freigeben konnten.

### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem ein-und Auszoomen aus dem Präsentationsbereich zu einer Lücke zwischen dem vergrößerten Auswahlrechteck und dem Mauszeiger führte.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem Project nach dem Klicken auf Optionen abstürzte.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem Hyperlinks in Kommentaren nicht funktionierten.
- Es wurde ein Problem behoben, bei dem ein-und Auszoomen aus dem Präsentationsbereich zu einer Lücke zwischen dem vergrößerten Auswahlrechteck und dem Mauszeiger führte.
- Es wurde ein Problem behoben, bei dem das Einfügen von HTML in WordMail for Calendar nicht funktionierte.
- Es wurde ein Problem behoben, bei dem das Antworten auf einen Kommentar in einer gemeinsamen Sitzung manchmal dazu führen könnte, dass Word einfriert.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-may-15"></a>Version 2006:15. Mai
*Version 2006 (Build 12905.20000)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Stellen Sie eine PDF-Verbindung her:** Verbinden mit, importieren, Aktualisieren von Daten aus einer PDF-Datei. [Weitere Informationen](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

### <a name="outlook"></a>Outlook

- **Finden Sie genau das, was Sie benötigen:** Schränken Sie die Suche mit Optionen wie Ordner, Absender, Datum, anlageninfo und mehr ein.

### <a name="powerpoint"></a>PowerPoint

- **Kein Klicker erforderlich: Ihre Ohrhörer haben Sie abgedeckt:** Verwenden Sie Ihre Surface-Ohrhörer, um Ihre PowerPoint-Präsentationen zu steuern. Wichtig: Sie müssen ihre Oberflächen Ohrhörer in der Surface Audio-App für Windows 10 koppeln, um Gesten zum Steuern von Präsentationen zu verwenden. Anweisungen zum Einstieg in die Surface-Audioanwendung unter Windows 10 finden Sie hier. [Weitere Informationen](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="word"></a>Word

- **Automatisches Anwenden oder empfehlen von Sensitivitäts Bezeichnungen:** Office kann eine Vertraulichkeits Bezeichnung basierend auf dem erkannten vertraulichen Inhalt empfehlen oder automatisch anwenden.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme

### <a name="excel"></a>Excel
- Es wurde ein Problem behoben, das zu einer verbesserten Leistungszeit für Benutzer führte, wenn Sie die zusammengeführten Spalten gelöscht haben.
- <div>Es wurde ein Problem behoben, aufgrund dessen Druckernamen in der Liste der verfügbaren Drucker dupliziert wurden.</div>

### <a name="powerpoint"></a>PowerPoint
- Es wurde ein Problem behoben, bei dem Tastenkombinationen und Rechtschreibprüfung nicht wie erwartet funktionieren, wenn Sie eine Englisch Schweiz (QWERTZ)-Tastatur verwenden.

### <a name="word"></a>Word
- Es wurde ein Problem behoben, bei dem das Hinzufügen eines neuen Kommentars in einem leeren Dokument nichts tun würde.
- Es wurde ein Problem behoben, bei dem das Einfügen oder Aktualisieren eines Index in einem Dokument mit mehr als hundert Einträgen zum Absturz der Anwendung führen würde.
- Es wurde ein Problem behoben, bei dem Dateien mit benutzerdefinierten XML-Werten äußerst langsam geöffnet wurden.

### <a name="office-suite"></a>Office-Suite
- Es wurde ein Problem in Visual Basic für Anwendungen in Microsoft Office behoben, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung als beschädigt beim Laden angezeigt würden.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-may-08"></a>Version 2006: 08. Mai
*Version 2006 (Build 12829.20000)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen.

### <a name="outlook"></a>Outlook

- **Bessere Ergebnisse – im Handumdrehen:** wir haben die Suche aktualisiert, damit Sie intelligenter, schneller und zuverlässiger als je zuvor ist. [Weitere Informationen](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Erzählen Sie mit animierten GIFs über sich:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden künftig noch pfiffiger aussehen.

### <a name="powerpoint"></a>PowerPoint

- **Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen. [Weitere Informationen](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a>Word

- **Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="office-suite"></a>Office-Suite

- Wir haben das Problem untersucht und behoben, bei dem die Bereitstellung von Office 365 ProPlus über InTune nach einem Herunterfahren des Betriebssystems pausiert wurde.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-may-01"></a>Version 2005: 1. Mai
*Version 2005 (Build 12827.20030)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Verbesserte Links in E-Mails:** Wenn Sie einen Link zu einer Datei einfügen, ersetzt der Dateiname die URL. Sie können die Berechtigungen so ändern, dass alle Empfänger Zugriff haben. [Weitere Informationen](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Ein Problem wurde behoben, bei dem die Diagrammdatentabelle Werte in einer Datumsachse nicht korrekt rendern konnte.
- Es wurde ein Problem behoben, bei dem Seitenumbrüche nicht deaktiviert werden konnten, nachdem die Seitenlayout- oder Seitenumbruchsvorschau angezeigt wurde.
- Es wurde ein Problem behoben, bei dem Diagrammlinienarten nach dem Ein- und Ausblenden von Spalten mit Seriendaten verloren gehen konnten.
- Das Einfügen einer Spalte in eine gefilterte Liste würde länger dauern als erwartet.
- Ein Absturz konnte auftreten, wenn versucht wurde, Änderungen mithilfe des Legacymodus "Freigegebene Arbeitsmappe" auf einem neuen Blatt für eine Arbeitsmappe aufzulisten.
- Das Problem, bei dem es sein konnte, dass benutzerdefinierte Formatierungen in Pivot-Diagrammen nicht gespeichert wurden, wenn die Option "Invertieren, wenn negativ" aktiviert war, wurde behoben.
- Es wurde ein Problem behoben, bei dem die benutzerdefinierte Formatierung für einen einzelnen Datenpunkt in einem Pivot-Diagramm nicht gespeichert wurde, wenn die Option "Invertieren, wenn negativ" ausgewählt wurde.
- Diese Änderung behebt ein Problem, bei dem das in eine CSV-Datei hochgeladene @-Zeichen dazu führte, dass die Zeichenfolge nach dem @-Zeichen in eine Formel konvertiert wurde.
- Es wurde ein Problem behoben, bei dem Dezimalwerte in der SEQUENCE-Funktion nicht korrekt gerundet wurden.

### <a name="outlook"></a>Outlook

- Behebt ein Problem, das dazu führte, dass sehr lange Safelinks, auf die Benutzer im Outlook-Desktopclient klickten, aufgrund von Trunkierung nicht geladen wurden.
- Es wurde ein Problem behoben, bei dem Outlook-Ordner mit Namen, die DBCS-Zeichen (Doublebyte-Zeichensatz) enthalten, bei der Synchronisierung mit dem Server zeitweise verschwanden. Dazu musste Outlook mit einem IMAP-Konto konfiguriert und auf einem System mit dem Gebietsschema „Japanisch“ ausgeführt werden.

### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem Entwürfe von Kommentaren nicht verfügbar waren, wenn ein Benutzer einen Kommentar erstellte, ohne ihn zu posten, und den Kommentarbereich schloss, dann ein neues Fenster öffnete, über mehrere Folien navigierte, das Fenster schloss und schließlich den Kommentarbereich in der ursprünglichen Präsentation wieder öffnete.

### <a name="project"></a>Project

- Folgendes Problem wurde behoben: Wenn Sie Project in Verbindung mit der Project Web App verwenden, das Kommas als Dezimaltrennzeichen festgelegt ist, und Sie versuchten, eine Verzögerung hinzuzufügen, schlägt die Methode "TaskDependencies Add" fehl.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, das dazu führte, dass das Einfügen von Kommentaren in ein Dokument im Kollaborationsmodus nicht immer funktionierte.
- Diese Änderung behebt ein Problem, bei dem die Personenkarte kurzzeitig eingeblendet wurde, wenn auf die Erwähnung geklickt wurde.
- Es wurde das Problem behoben, dass beim Schließen eines Dokuments mit Kommentarentwürfen der Benutzer aufgefordert wurde, ob er das Dokument schließen möchte, ohne die Kommentarentwürfe zu speichern. Das Abbrechen der Eingabeaufforderung schloss das Dokument, anstatt es geöffnet zu lassen.
- Es wurde ein Problem behoben, bei dem die Übersetzung eines geposteten Kommentars den Fehler "Fehler beim Einfügen des übersetzten Textes" zur Folge hatte.
- In der Webansicht und im Plastischen Reader wurde durch das Anklicken eines Hinweises nach oben gescrollt, obwohl er bereits angezeigt wurde. Dieser Fehler wurde behoben.
- Wir haben ein Problem behoben, dass infolge des Speicherns einer Datei, die ein Makro enthält, unter einem neuen Namen sie mit der Erweiterung DOCX und dem Dateinamen WRO0004.docx gespeichert wurde, und zwar unabhängig davon, was der Benutzer eingab, wodurch das Dokument unbrauchbar wurde.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)


## <a name="version-2005-april-24"></a>Version 2005: 24. April
*Version 2005 (Build 12816.20006)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel
- Diese Änderung behebt ein Problem, bei dem das Bestimmtheitsmaß der Diagrammtrendlinie (im Fall des erzwungenen y-Achsenabschnitts) falsch war, obwohl die Funktion LINEST den richtigen Wert zurückgibt.
- Diese Änderung behebt ein Problem, bei dem benutzerdefinierte Diagramm-Trendlinienformatierungen nicht immer gespeichert wurden.

### <a name="outlook"></a>Outlook
- Es wurde ein Problem behoben, bei dem die Schaltfläche "Kategorisieren" für Gruppenkalender im Office-Menüband deaktiviert wurde.
- Es wurde ein Problem behoben, bei dem Gruppenordner von Unternehmenskunden, die nicht implementiert sind oder nicht funktionieren, in Outlook zu der Meldung "reagiert nicht" führte.

### <a name="powerpoint"></a>PowerPoint
- Es wurde ein Problem behoben, bei dem beim Bewegen des Mauszeigers über das Sternchen-Symbol (*) der Benutzername und das Datum der letzten Person, die das Dokument aktualisiert hat, nicht angezeigt wurden.

### <a name="word"></a>Word
- Beim Aktivieren der Option "Lesezeichen anzeigen" wurden keine Lesezeichen angezeigt. Dieser Fehler wurde behoben.
- Diese Änderung behebt ein Problem, bei dem Text mit Hyperlinks möglicherweise nicht angezeigt wurde, wenn die Option "Feldcodes statt ihrer Werte anzeigen" aktiviert war.

[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)


## <a name="version-2005-april-17"></a>Version 2005: 17. April
*Version 2005 (Build 12810.20002)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel
- Die Größe der Steuerelemente zur Bearbeitung von Zellreferenzen im Dialogfeld "Benutzerdefinierte Fehlerindikatoren", das bei Diagrammen verwendet wird, wurde erhöht.
- In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.
- Ein Problem mit der Skalierung von Kontrollkästchen in Formularsteuerelementen beim Drucken wurde behoben.
- Application.Evaluate (VBA) funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.
- Diese Änderung behebt ein Problem, bei dem Informationen zur bedingten Formatierung (CF) nicht korrekt in XLSB-Dateien gespeichert wurden.

### <a name="onenote"></a>OneNote
- Ein Problem beim Speichern von Zeilenumbrüchen als vertikale Registerkarten wurde behoben.

### <a name="outlook"></a>Outlook
- Behebt ein Problem, das dazu führte, dass Benutzer keine "Persönliche Kontaktgruppe" als "Besprechungsteilnehmer" hinzufügen konnten.
- Behebt ein Problem, das dazu geführt hat, dass bei Besprechungen, die mehr als 2 Monate entfernt sind, ein Besprechungsthema im "Terminplanungs-Assistenten" nicht angezeigt wird.
- Behebt ein Problem, das dazu führte, dass Benutzer beim Weiterleiten großer HTML-Nachrichten den Nachrichtentext abgeschnitten sahen.
- Es wurde die Möglichkeit des Erzwingens der S/MIME-Standardsignatur-Konfiguration über eine Gruppenrichtlinie hinzugefügt.
- Behebt ein Problem, das dazu führte, dass Löschregeln, die für andere Postfächer als das primäre Postfach des Benutzers erstellt wurden, ungültig wurden.
- Behebt ein Problem, das dazu führte, dass Anlagen beim Weiterleiten einer verschlüsselten Nachricht verworfen wurden.

### <a name="project"></a>Project
- Wenn Vorgänger/Nachfolger-Daten in einer Formular-Maske bearbeitet werden, wird ein zusätzliches ProjectBeforeTaskChange-Ereignis ausgelöst.
- Es wurde ein Problem behoben, bei dem Project abstürzen konnte, wenn das Feld „Boardstatus“ in einem Projekt geändert wurde, das mit einer SharePoint-Aufgabenliste verbunden ist.
- Ein Problem wurde behoben, bei dem Project beim Speichern von Projekten, die mit älteren Project-Versionen erstellt wurden, möglicherweise abstürzt.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)


## <a name="version-2004-april-10"></a>Version 2004: 10. April
*Version 2004 (Build 12730.20024)*

[//]: # (FEATUREDETAILS CONTENT START NICHT ENTFERNEN)

### <a name="feature-updates"></a>Featureupdates
### <a name="access"></a>Access

- ** Das Dialogfeld „Tabelle anzeigen“ umgehen, direkt zu einem Aufgabenbereich wechseln und das Hinzufügen von Tabellen zu Beziehungen und Abfragen rationalisieren:** Fügen Sie Tabellen und Abfragen hinzu, indem Sie auf vier Registerkarten klicken, Namen mehrfach auswählen, nach Text suchen und aus einem Aufgabenbereich ziehen, der während der Arbeit geöffnet bleibt.

### <a name="excel"></a>Excel

- **M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger! Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="outlook"></a>Outlook

- **M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger! Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **Bewahren Sie die Klangtreue Ihrer Bilder, wenn Sie diese als Teil einer E-Mail versenden:** Eine neue Outlook-Einstellung ist verfügbar, um die Bildkomprimierung zu begrenzen, wenn Sie Bilder als Teil des E-Mail-Inhalts versenden.

### <a name="powerpoint"></a>PowerPoint

- **M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger! Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **Synchronisieren von Änderungen während der Präsentation:** Änderungen können jetzt synchronisiert werden, wenn sie vorgenommen werden, selbst wenn sich die Präsentation im Bildschirmpräsentationsmodus befindet.

### <a name="word"></a>Word

- **M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger! Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **Fügen Sie einen privaten Kopie Anmerkungen hinzu:** Erstellen Sie handschriftliche Notizen nur für Sie, indem Sie eine private Kopie eines freigegebenen Dokuments erstellen. Wechseln Sie dazu einfach zu "Anzeige" > "Private Kopie erstellen".

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Access

- Probleme bei der Anpassung der Größe und der Aktualisierung von Tabellen im Aufgabenbereich wurden behoben.

### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem das Auswählen eines Zellbereichs auf einem Arbeitsblatt zur Auswahl nur einer einzelnen Zelle geführt hat.

- Es wurde ein Problem behoben, das dazu führen konnte, dass Excel nicht mehr reagierte, wenn die Größe eines Diagramms mit einigen x-Achsen-Bereichen reduziert wurde.

- Es wurde ein Problem behoben, bei dem das Einfügen einer benutzerdefinierten Diagrammvorlage als Standard dazu führte, dass sie als Säulendiagramm gespeichert wurde.

- Ein Problem wurde behoben, bei dem Datenbeschriftungen in Diagrammen leer angezeigt wurden, wenn die zugrundeliegenden Datenzellen keine Beschriftung aufwiesen.

- Es wurde ein Problem behoben, bei dem eine Excel-Tabelle mit aktiviertem Z1S1-Zellbezug die freigegeben bzw. gemeinsam erstellt wurde, der aktive Zellbezug im Z1S1-Modus nicht angezeigt wurde, wenn man auf das Symbol für die Anwesenheitsanzeige zeigte.

### <a name="outlook"></a>Outlook

- Behebt ein Problem, durch das gelegentlich Kategorien in E-Mail-Nachrichten nicht mehr aufschienen.

- Behebt ein Problem, durch das Stellvertretungen auf unterschiedlichen Computern unterschiedliche Ordnerhierarchien für freigegebene Postfächer angezeigt wurden.

- Behebt ein Problem, das einen Absturz verursachte, wenn Benutzer versuchten, die Eigenschaften eines Organisationsformulars anzuzeigen.

- Behebt ein Problem, durch das einige Erinnerungen nicht ausgelöst wurden, wenn die Zeitzone auf einem Computer geändert wurde.

### <a name="powerpoint"></a>PowerPoint

- Diese Änderung behebt ein Problem, bei dem beim Rendern eines Diagramms einer älteren Excel-Version, das als OLE-Objekt in PowerPoint oder Word eingebettet ist, u. U. nicht immer der Diagrammtitel angezeigt wurde.

- Es wurde ein Problem behoben, bei dem beim Kopieren von Text aus Excel in PowerPoint u. U. dessen Formatierung geändert wurde.

- Diese Änderung behebt ein Problem, bei dem das Suchen von Sonderzeichen mithilfe der Option "Nur ganze Wörter suchen" nicht immer erwartungsgemäß funktioniert hat.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem der Benutzer keine zeitgesteuerte Baseline-Arbeit eingeben konnte, wenn die Einstellung zum Schutz der aktuellen Arbeit aktiviert war.

### <a name="word"></a>Word

- Diese Änderung behebt ein Problem, bei dem wenn der Mauszeiger über einen Hinweis gehalten wurde, dessen Karte nicht hervorgehoben wurde.

- Diese Änderung behebt ein Problem, das dazu führte, dass der Text in gruppierten Formen beim Verwenden des Lasso-Auswahltools vorübergehend ausgeblendet wurde.

- Diese Änderung behebt ein Problem, bei dem beim Rendern eines Diagramms einer älteren Excel-Version, das als OLE-Objekt in PowerPoint oder Word eingebettet ist, u. U. nicht immer der Diagrammtitel angezeigt wurde.

- Diese Änderung behebt ein Problem in der Zwei-Seiten-Ansicht. Beim Erstellen eines Kommentars wurde der Kommentaranker nicht immer in der Anzeige angezeigt.

- Ein Problem wurde behoben, bei dem ein Absatz, dessen Formatvorlage ein Vorgänger einer mit einer Liste verknüpften Formatvorlage war, möglicherweise verloren ging.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-march-27"></a>Version 2004: 27. März
*Version 2004 (Build 12718.20010)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Neue Option zum Deaktivieren von @Erwähnung-Vorschlägen beim Verfassen von E-Mails:** Findest Sie die @Erwähnung eher lästig als sinnvoll? Wenn Sie das möchten, können Sie diese nun deaktivieren.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook
- Behebt ein Problem, das bewirkt hat, dass die Schaltfläche "In der Cloud speichern" in den Anlagentools fehlt.
- Behebt ein Problem, das bewirkt hat, dass Benutzer beim Antworten auf eine verwaltete Nachricht mit digitaler Berechtigung aus einem Inspektor-Fenster keine Signatur hinzufügen können, wenn der Benutzer nicht über die Berechtigung "Besitzer" für die Nachricht verfügt, auf die geantwortet wird.
- Behebt ein Problem, durch das Benutzer keine weiteren Anlagen von einem Webspeicherort zu einer zuvor erstellten Besprechung hinzufügen können.

### <a name="powerpoint"></a>PowerPoint
- Diese Änderung behebt einen Fehler, der dazu führen kann, dass PowerPoint-Dateien mit Emojis beim Speichern fehlgeschlagen.

### <a name="project"></a>Project
- Ein Problem wurde behoben, durch das, wenn "CustomFieldValueListGetItem" ausgeführt wird und eine Nachschlagetabelle für das benutzerdefinierte Feld nicht vorhanden ist, eine leere Nachschlagetabelle erstellt wird, auch wenn dies nicht der Fall sein sollte.

### <a name="word"></a>Word
- Diese Änderung behebt ein Problem, bei dem mehrere Seiten aus dem Menü "Ansicht" ausgewählt werden, in dem der Kommentarbereich als leer angezeigt werden kann.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-march-20"></a>Version 2004: 20. März
*Version 2004 (Build 12711.20000)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Visuelle Aktualisierung des Kalenders:** Letztes Jahr haben wir die E-Mail-Erfahrung visuell aufgefrischt, und dieses Jahr ist der Kalender mit einem Facelifting an der Reihe! Die Aktualisierungen sind frisch, aber vertraut, so dass Sie als erfahrener Outlook-Benutzer sofort einsteigen und produktiver sein können.

- **Schützen von Daten in einer Gruppe:** Die beim Erstellen einer Gruppe ausgewählte Vertraulichkeitsbezeichnung wird auf Gruppen-E-Mails, Dokumente und Teamwebsites angewendet

### <a name="powerpoint"></a>PowerPoint

- **Aktualisieren von Folien während der Bildschirmpräsentation:** Aktualisieren Sie Folien, die von anderen Autoren während Ihrer Präsentation geändert wurden.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Diese Änderung betrifft Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen.

### <a name="outlook"></a>Outlook

- Diese Änderung ist gegen Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen gerichtet.

- Diese Änderung behebt ein Problem, bei dem die neuesten Änderungen an E-Mail-Entwürfen nicht aktualisiert wurden.

- Ein Problem wurde behoben, bei dem Sie mit der rechten Maustaste auf eine Datei klicken und "Senden an" nicht funktionieren würde.

- Es wurde ein Problem behoben, bei dem, wenn ein Benutzer einen angepassten Suchpfad für das Adressbuch hatte, der Namensauflösungsbereich von Outlook auf den angepassten Pfad beschränkt wurde, anstatt die Globale Adressliste (GAL) einzubeziehen.

- Es wurde ein Problem behoben, bei dem innerhalb eines Satzes von zurückgegebenen Suchergebnissen beim Sortieren der Ergebnisse nach Kategorien die Farben der Kategorien nicht angezeigt wurden.

### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem das VBA-Ereignis (Visual Basic Applications) "ProjectBeforeTaskChange" nicht ausgelöst wurde, als ein Benutzer auf die Schaltfläche "inaktivieren" geklickt hat, die sich auf dem Menüband "Vorgänge" innerhalb der Planungsgruppierung befindet.

- Wenn Sie Vorgänger- oder Nachfolgerdetails in einer Ansicht vom Typ „Formular“ festlegen, wurden die Änderungen nicht immer durch das Ereignis „ProjectBeforeTaskChange Visual Basic Applications“ (VBA) erfasst. Wenn Sie beispielsweise eine Abhängigkeit gelöscht und im Formular auf „OK“ geklickt haben, wurde das Ereignis nicht ausgelöst. Dieses Verhalten wurde behoben.

- Es wurde ein Problem behoben, bei dem die neuesten Werte für die tatsächlichen Kosten der geleisteten Arbeit (ACWP) nicht angezeigt wurden, nachdem eine Änderung, z. B. eine Datumsänderung, vorgenommen wurde.

- Es wurde ein Problem behoben, bei dem das Öffnen eines Projekts über das Menü "Zuletzt verwendet" (MRU) die Projektdatei mit Lese- bzw. Schreibzugriff öffnete.

- Diese Änderung behebt das Problem, dass Sie eine manuelle Aufgabe mit einem Startdatum und einer Uhrzeit (aber ohne Dauer) erstellt haben, diese aber mit einer falschen Uhrzeit auf der Zeitachse angezeigt wurde.

- Es wurde ein Problem behoben, bei dem das Drucken einer Zeitleiste mit dem Hijri-Kalender dazu führte, dass ein Monat in der Druckansicht übersprungen oder dupliziert wurde.

- Diese Änderung richtet sich gegen ein Problem, bei dem die Arbeit im Team Planner mit GDI-Objekten zu einer Überzuweisung von GDI-Objekten und zu geringem Speicherplatz führen konnte.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem die Funktion zum Posten von Kommentaren deaktiviert war.

- Diese Änderung ist gegen Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen gerichtet.

- Diese Änderung ist gegen ein Problem gerichtet, bei dem der Account Manager keine Nachrichten versendete, was zu einer Unterbrechung bei Anwendungen von Drittanbietern führte.

- Diese Änderung behebt ein Problem, bei dem das Inhaltsverzeichnis mit Überschriftenformaten aktualisiert wurde, die im Dokument nicht vorhanden waren.

- Es wurde ein Problem behoben, bei dem in Word-Dokumenten gespeicherte digitale Signaturen beim Versand der Dokumente entfernt wurden.

[//]: # (BUGDETAILS AM INHALTSENDE NICHT ENTFERNEN)

## <a name="version-2004-march-13"></a>Version 2004: 13. März
*Version 2004 (Build 12703.20010)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates

### <a name="excel"></a>Excel
- **Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern. [Weitere Informationen](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a>PowerPoint
- **Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern. [Weitere Informationen](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a>Word
- **Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern. [Weitere Informationen](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme

### <a name="access"></a>Access
- Ein Problem wurde behoben, bei dem internationale Versionen von Access in der Benutzeroberfläche englische Zeichenfolgen anzeigten.

### <a name="excel"></a>Excel
- Es wurde ein Leistungsproblem behoben, das Benutzer beim programmgesteuerten Bearbeiten eines großen Zellbereichs festgestellt haben.
- Ein Leistungsproblem beim Öffnen von CSV-Dateien in japanischen Umgebungen wurde behoben.

### <a name="outlook"></a>Outlook
- Behebt ein Problem, das dazu geführt hat, dass das Datum der letzten Änderung in einer Datei beim Hinzufügen einer Anlage zu einer E-Mail oder beim Speichern einer Anlage aus einer E-Mail durch Ziehen und Ablegen (im Gegensatz zum Hinzufügen oder Speichern über ein Menü) aktualisiert wurde.
- Behebt ein Problem, bei dem durch das Drücken der EINGABETASTE im erweiterten Suchbereich keine Suche gestartet wird. Stattdessen müssen Benutzer auf die Schaltfläche "Suchen" klicken.
- Ein Problem wurde behoben, bei dem die Suche keine Informationen zu Benutzern anzeigt, wenn die Option "Benutzerfotos anzeigen, wenn verfügbar" deaktiviert ist.

### <a name="project"></a>Project
- Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.
- Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.

### <a name="word"></a>Word
- Ein Problem wurde behoben, bei dem das Eingeben oder Bearbeiten eines Kommentars und Verwenden von STRG+A dazu führte, dass statt nur innerhalb der Kommentarkarte Text im Zeichenbereich markiert wurde.
- Es wurde ein Problem behoben, bei dem die Ausrichtung von Wörtern in einem Dokument durcheinandergebracht wird, wenn Sie nach dem Drucken mit Schnelldruck versuchen, den Text zu bearbeiten.
- Es wurde ein Problem beim Zusammenführen von zwei Dokumenten in ein Dokument behoben.
- Es wurde ein Problem behoben, bei dem das Markieren von Überarbeitungen, die Formeln enthalten, beim Speichern der Datei zu einem Fehler führen konnte.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-06"></a>Version 2003: 6. März
*Version 2003 (Build 12624.20086)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, bei dem das Erstellen einer Regel mit Outlook Web App auf dem Exchange-Server nicht beibehalten werden konnte und zu einem Konflikt geführt hat.
- Wurde ein Problem mit Outlook im dunklen Modus behoben, wird möglicherweise die Dropdownliste im Feld "Von:" nicht angezeigt.
- Behebt ein Problem, das bewirkt hat, dass Benutzer Dateien nicht über den Datei-Explorer ihrer E-Mail-Nachricht als Anlage hinzufügen konnten, wenn diese Datei in einer anderen Anwendung geöffnet war.

### <a name="powerpoint"></a>PowerPoint

- Ein Problem wurde behoben, bei dem die empfohlenen Miniaturansichten blinkten, wenn Sie mit der Maus auf die Miniaturansichten gingen. In einigen Fällen kann dies dazu führen, dass PowerPoint abstürzt.

### <a name="word"></a>Word

- Es wurde ein Problem mit der compare-Funktion für Dokumente behoben, die für die Bearbeitung geschützt waren.

### <a name="office-suite"></a>Office-Suite

- Behebt ein Problem mit Word/Excel/PowerPoint, bei dem der User-Principal-Name (UPN) nicht mehr die Groß-/Kleinschreibung beachtet, was zu weniger Fehlern beim Arbeiten mit Dateien in SharePoint führt.

- Behebt ein kosmetisches Problem, bei dem die Schaltfläche "OK" im Dialogfeld „Datei \ Optionen“ abgeblendet angezeigt, die Funktionalität aber nicht beeinträchtigt wurde.

[//]: # (BUGDETAILS NICHT AM INHALTSENDE ENTFERNEN)

[//]: # (FEATUREDETAILS CONTENT START NICHT ENTFERNEN)

## <a name="version-2003-february-28"></a>Version 2003: 28. Februar
*Version 2003 (Build 12619.20002)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Benachrichtigung Über Vorfall für IT-Administratoren:** Globale Administratoren von Microsoft 365-Mandanten und Administratoren von Office-Apps werden über Outlook und O365 Exchange-Vorfällen benachrichtigt, die sich auf Ihre Benutzer auswirken – mit einer neuen Benachrichtigung im rechten Seitenbereich in Outlook für Windows. [Weitere Informationen](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a>PowerPoint

- **Verbesserte Freihand-Shape-Diagrammdarstellung:** Zeichnen Sie bessere Diagramme und lassen Sie diese in ein Office-Objekt umwandeln, das Sie bearbeiten können. [Weitere Informationen unter ](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Ein Problem wurde behoben, bei dem der Text in einem Datenschnitt in der Druckvorschau nicht ordnungsgemäß skaliert wurde.

### <a name="outlook"></a>Outlook

- Behebt ein Problem, das dazu geführt hat, dass das „Datum der letzten Änderung“ in einer Datei beim Hinzufügen einer Anlage zu einer E-Mail oder beim Speichern einer Anlage aus einer E-Mail durch Ziehen und Ablegen (im Gegensatz zum Hinzufügen oder Speichern über ein Menü) aktualisiert wurde.

### <a name="word"></a>Word

- Behebt ein Problem, das dazu geführt hat, dass beim Navigieren über eine Kommentarkarte mit der Tabulatortaste der Fokus auf dem Bearbeitungsfeld für den Kommentar nicht angezeigt wurde.

- Das Einfügen eines Steuerelements (beispielsweise eines Textinhaltssteuerelements) in eine Gleichung und das anschließende Speichern und Öffnen der Datei führte zu einem Fehler aufgrund nicht lesbaren Inhalts.

- Ein Problem wurde behoben, aufgrund dessen das Speichern einer zuvor kennwortgeschützten Datei in einem Cloudspeicher nicht funktioniert hat.

### <a name="office-suite"></a>Office-Suite

- Behebt ein Problem, das dazu geführt hat, dass beim Öffnen mehrerer Dokumente in Word/Excel/PowerPoint aus derselben SharePoint-Bibliothek lediglich das erste geöffnete Dokument auf Richtlinienkonformität gescannt wurde.

[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSWENDE)

## <a name="version-2003-february-21"></a>Version 2003: 21. Februar
*Version 2003 (Build 12615.20000)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="office-suite"></a>Office-Suite

- **Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme

### <a name="excel"></a>Excel
- Es wurde ein Problem behoben, das möglicherweise beim Umbenennen von Pivot-Tabellenmaßen aufgetreten ist.
- Es wurde ein Leistungsproblem behoben, das möglicherweise bei der Verwendung eines VBA-Makros zum Löschen des Inhalts eines Bereichs aufgetreten ist.
- Es wurde ein Problem behoben, das zum Blinken der Benutzeroberfläche führte, wenn Benutzer ein Makro ausführten, das mit dem Menüband interagierte.
- Es wurde ein Problem behoben, bei dem CSV-Dateien falsch geladen wurden, wenn das erste Wort in der Datei TABLE lautete.
- Es wurde ein Problem behoben, bei dem es zu Abstürzen kommen konnte, wenn Benutzer zwischen zwei Arbeitsmappen mit unterschiedlichen Zoomstufen wechselten.

### <a name="outlook"></a>Outlook
- Es wurde ein Problem behoben, das dazu führte, dass Benutzer keine Nachrichten in öffentlichen Ordnern öffnen konnten, wenn Outlook über Nacht laufen gelassen wurde.
- Es wurde eine Racebedingung behoben, bei der die Schaltflächen "Zulassen" und "Verweigern" auf der Seite "Berechtigungen" während des Authentifizierungsworkflows beim Hinzufügen eines Google Mail-Kontos deaktiviert sind.
- Es wurde ein Problem behoben, das dazu führte, dass Outlook in einigen Szenarien unerwartet Protokollausgaben erzeugte, selbst wenn die Protokollierung ausgeschaltet war.

### <a name="word"></a>Word
- Es wurde ein Problem behoben, bei dem Kommentarkarten nicht immer hervorgehoben werden, wenn der Mauszeiger über die Kommentarkarte bewegt wird.
- Während einer aktiven Sitzung zur gemeinsamen Dokumenterstellung kann das direkte Hinzufügen eines Bildes in eine Kommentarkarte dazu führen, dass ein Tag hinzugefügt wird. Das Problem wurde behoben.

### <a name="office-suite"></a>Office-Suite
- Beim Verwenden der Metadateneigenschaften MultiChoice/Verweis/Verwaltet mit Word/Excel/PowerPoint-Dokumenten und dem Speichern in einer SharePoint-Dokumentbibliothek waren diese Eigenschaften bisher auf 255 Zeichen beschränkt. Wenn diese Eigenschaften 255 Zeichen überschritten, konnten solche Dokumente nicht gespeichert werden. Mit dieser Änderung wurde dieser Grenzwert auf 2048 Zeichen erhöht.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-february-14"></a>Version 2003: 14. Februar
*Version 2003 (Build 12607.20000)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Neue Benutzeroberfläche für WLAN-Netzwerke mit Anmeldung:** Sind Sie schon einmal einem WLAN-Netzwerk beigetreten, mit dem Sie sich anmelden mussten? Outlook erkennt dies jetzt und hilft Ihnen, eine Verbindung zu herstellen.

### <a name="word"></a>Word

- **Freihand-Editor in der Toolbox der Zeichentools finden:** Wählen Sie "Zeichnen" und dann den Freihand-Editor-Stift aus, um Ihr Dokument mit dem Finger oder einem digitalen Stift zu bearbeiten. [Weitere Informationen](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a>Office-Suite

- **Übersichtlichere Statusleistensymbole:** Statusleistensymbole sind jetzt einfacher zu sehen.

[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, durch das Benutzer den Zugriff auf das Dialogfeld "Frei/Gebucht-Optionen" der Kalenderberechtigungen verloren.

- Es wurde ein Problem behoben, das zur Warnung "Leider besteht ein Problem beim Öffnen dieses Elements" führen kann, wenn Sie bestimmte Besprechungsserien-Instanzen öffnen, die aus einer anderen Zeitzone gesendet wurden.

- Es wurde ein Problem behoben, durch das Benutzer eine MSG-Datei möglicherweise nicht mehr öffnen können, nachdem die eine Anlage aus dieser Nachricht durch Ziehen und Ablegen verschoben haben.

- Ein Problem wurde behoben, bei dem der Dateiname nach dem Hochladen einer Dateianlage aus Outlook nach OneDrive möglicherweise geändert wird, wenn der Name der Anlage eine Klammer enthält.

### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, das dazu führen kann, dass ein Dokument, das ein Excel-Diagramm enthält, nicht in PowerPoint oder Word gespeichert werden kann.

### <a name="word"></a>Word

- Ein Problem wurde behoben, bei dem Bilder in Dokumenten beim Export in eine PDF-Datei transparent sind.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-february-07"></a>Version 2002: 07. Februar
*Version 2002 (Build 12527.20040)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="access"></a>Zugriff

- **Seien Sie beim Arbeiten im Abfrage-Designer, in der SQL-Ansicht und im Fenster „Beziehungen“ produktiver:** Klicken Sie zum Öffnen, Gestalten, Vergrößern oder Verkleinern und Ausblenden mit der rechten Maustaste auf die betreffende Tabelle. Suchen und Ersetzen von Text in der SQL-Ansicht. Auswählen mehrerer Tabellen im Fenster „Beziehungen“.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Access

- Dieses Update behebt ein Problem bei der Verwendung von ADODB. Das Recorder-Objekt im VB-Code meldet möglicherweise einen Fehler falsch.

- Dieses Update behebt ein Problem, das dazu führen kann, dass Microsoft Access eine Identitätsspalte in einer verknüpften SQL-Server-Tabelle nicht identifiziert, was dazu führen kann, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.

### <a name="excel"></a>Excel

- Ein Problem wurde behoben, das dazu geführt hatte, dass Excel bei Verschieben von Text in Spalten mit dynamischen Pfeilern abgestürzt ist.

### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, das dazu geführt hatte, dass beim Durchblättern des Kalanders in der Monatsansicht die vorangegangenen Kalenderereignisse nicht angezeigt wurden.

- Behebt ein Problem, das dazu geführt hat, dass Benutzer beim Anzeigen von mehr als 30 Kalendern in einer Citrix-Umgebung einen Absturz erlebt haben.

### <a name="powerpoint"></a>PowerPoint

- Ein Problem wurde behoben, das dazu geführt hatte, dass PowerPoint nach dem Schließen einer Datei diese nicht sofort aus der Sammlung von Präsentationen entfernt hat, sofern Ereignisverarbeiter (event handlers) ausgeführt werden. Dadurch war die Zahl der vom Objektmodell gemeldeten, geöffneten Präsentationen falsch und das Herunterfahren von PowerPoint wurde verhindert.

- Ein Problem mit dem Textmarker wurde behoben: Weißer Text mit dunkleren Textmarkerfarben wurde Schwarz mit Graustufen gedruckt.

### <a name="word"></a>Word

- Beim Aktualisieren eines Inhaltsverzeichnisses bzw. dem Blättern durch dieses wird manchmal möglicherweise ein grauer Bereich auf dem Dokument angezeigt.

- Ein Problem wurde behoben, bei dem die Entwurfsversion eines Stammkommentars bei der gemeinsamen Dokumenterstellung zeitweise nicht beibehalten wurde.

- Ein Problem wurde behoben, das dazu geführt hatte, dass beim Hin- und Herwechseln zwischen Kommentar-Karten manchmal der anfänglich ausgewählte Kommentar mit einer Auswahlhervorhebung angezeigt wurde.

- Es wurde ein Problem mit der Verwendung von „Durchsuchen“ zum Speichern einer Datei behoben, das nicht funktioniert hat, wenn ein Kommentar geschrieben, jedoch nicht gepostet worden war und der Benutzer versucht hatte, die Datei zu speichern.

- Wenn „SlideTrack“ aktiviert und der Bereich „Kommentare“ geschlossen ist, kann der Bereich „Kommentare“ mit STRG+ALT+M möglicherweise nicht geöffnet werden.

- Es wurde ein Problem behoben, das dazu geführt hatte, dass beim Hinzufügen von @mention in einer Tabelle die Fehlermeldung „Eine Tabelle in diesem Dokument ist beschädigt“ generiert wurde.

### <a name="office-suite"></a>Office-Suite

- Behebt ein Problem, das dazu geführt hat, dass Korrekturhilfe-Paket Norwegen Nynorsk (nn-no) nicht ordnungsgemäß installiert wurde.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

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
ms.openlocfilehash: 246f164b26d01b25894879cfb0625cf76829a2e0
ms.sourcegitcommit: 82473b6efabedf74014a9a41c6c43ec53b0def88
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/09/2020
ms.locfileid: "48950004"
---
# <a name="release-notes-for-office-current-channel-preview"></a>Versionshinweise für Office Aktueller Kanal (Vorschau)

Dieser Artikel enthält Versionshinweise zu Builds von Word, Excel, PowerPoint, Outlook, Access und Project für Windows Desktop für den aktuellen Kanal (Vorschau). Jede Woche heben wir interessante neuer Features, wichtige Fixes und wesentliche Probleme hervor, über die wir Sie gerne informieren möchten. Bitte beachten Sie, dass wir Features (und häufig auch Fixes) häufig über einen Zeitraum in den aktuellen Kanal (Vorschau) einführen. Auf diese Weise können wir sicherstellen, dass alles reibungslos funktioniert, bevor das Feature für ein breiteres Publikum bereitgestellt wird. Wenn also im Folgenden etwas nicht beschrieben wird, machen Sie sich keine Sorgen, es wird bald behandelt werden.  

> [!IMPORTANT]
> We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).

> [!NOTE]
> - Das Veröffentlichungsdatum der Versionshinweise stimmt möglicherweise nicht mit dem tatsächlichen Veröffentlichungsdatum des Builds überein.

[//]: # (NICHT ENTFERNEN)

## <a name="version-2011-november-09"></a>Version 2011: 9. November
*Version 2011 (Build 13426.20184)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Erstellen von Power Platform-Datenflüssen aus Abfragen:** Jetzt können Sie Ihre Abfragen in Power Query-Vorlagen exportieren, die zum Erstellen von neuen Power Platform-Datenflüssen verwendet werden können.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Zugriff

- Es wurde ein Problem behoben, bei dem einige Benutzer die Fehlermeldung "Systemressource überschritten" angezeigt erhielten, wenn sie eine Abfrage aus dem synchronisierten OneDrive-Ordner exportieren wollten.


- Es wurde ein Problem behoben, bei dem das automatische Umschalten zwischen Formularfenstern zu einem anderen Formular führte.


- Es wurde ein Problem behoben, das bei Verwendung von DAO aus nicht-Office-Anwendungen dazu führte, dass die Anwendung unerwartet geschlossen wurde.


### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem „Dateiname“ nach einem „SaveAs“-Vorgang mit aktiviertem COM-Add-In nicht geändert wurde.


- Ein Problem mit Power Pivot bei Verwendung einer Verbindung zu einer Oracle-Datenbank wurde behoben.


- Es wurde ein Problem behoben, bei dem das automatische Speichern mit einer falschen/irreführenden Fehlermeldung fehlschlug, wenn im Excel-Datenmodell eine schlechte Kennzahldefinition vorhanden war.


- Ein Problem wurde behoben, durch das Excel unerwartet beendet wurde, wenn der Prozess der MTR-Berechnung und der Aktualisierung von Gruppenrichtlinienobjekten (z. B. über Remoteaktualisierung von Gruppenrichtlinien) ausgelöst wurde.


- Es wurde ein Problem behoben, bei dem ein Benutzer eine atomsvc-Datei (UTF8 + BOM) nicht direkt aus SharePoint öffnen konnte.


- Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.


- Es wurde ein Problem behoben, bei dem Word zu hängen scheint, wenn eine Excel-Arbeitsmappe in ein Word-Dokument eingefügt wurde.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, das dazu führte, dass Outlook beim Hinzufügen oder Speichern von Anlagen sporadisch nicht mehr funktionierte.


- Es wurde ein Problem behoben, bei dem der Schnelldruck für Bildanlagen zu einem Fehler geführt hat: "Windows kann dieses Bild nicht finden. Überprüfen Sie den Speicherort, und versuchen Sie es dann erneut."


- Es wurde ein Problem behoben, das dazu führte, dass Outlook im Offline-Status startete, bis die Benutzer manuell wählten, online zu arbeiten.


- Es wurde ein Problem behoben, bei dem beim Einfügen einer aus dem Besprechungsort kopierten URL an eine andere Stelle (z. B. in einen Browser) der URL ein Strickpunkt am Ende hinzugefügt wurde.


- Es wurde ein Problem behoben, bei dem Benutzer Termine im Kalender von Microsoft 365-Gruppen in der Standardauthentifizierung nicht löschen konnten.


- Es wurde ein Problem behoben, bei dem das Starten von Outlook beim Laden des Spitznamen-Caches fehlschlug.


- Ein Problem wurde behoben, bei dem ein Postfachbesitzer die Freigabeberechtigung für den eigenen Kalender nicht verwalten konnte, da die Option abgeblendet war.


- Ein Problem wurde behoben, bei dem in Outlook keine Nachricht mit eingeschränkten Berechtigungen erstellt werden konnte.


- Es wurde ein Problem behoben, bei dem beim Speichern von E-Mail-Vorlagen als .OFT chinesische Zeichen in Fragezeichen geändert wurden.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.


- Es wurde ein Problem behoben, bei dem das Symbol „Inhaltsplatzhalter“ neben „Bilder“ keine QuickInfo aufwies.


- Es wurde ein Problem behoben, bei dem die geschützte Ansicht einer Bildschirmpräsentation, die durch eine pptsx-Datei dargestellt wurde, die Bildschirmaufnahme von IRM-geschützten Dokumenten ermöglichte.


- Es wurde ein Problem behoben, bei dem Gitternetzlinien beim Schließen des Entwurfsfensters von den Folien verschoben wurden.


- Es wurde ein Problem behoben, bei dem beim Duplizieren einer Bildschirmpräsentation auf einen sekundären Monitor diese manchmal von einem anderen Fenster verdeckt wurde.


- Es wurde ein Problem behoben, bei dem sich die Bildlaufleiste in einer Folie von selbst einstellte, nachdem die Bildschirmaufnahme bei geöffnetem Auswahlfenster gestoppt wurde.


### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem „NewVal“ im Ereignis „ProjectBeforeTaskChange“ nicht den richtigen Wert hatte, wenn eine Verzögerung innerhalb einer Ansicht vom Typ "Aufgabenformular" geändert wurde.


- Es wurde ein Problem behoben, bei dem Project beim Öffnen von Dateien manchmal abstürzte, wenn Ressourcenprofile auf eine bestimmte Weise angegeben waren.


- Es wurde ein Problem behoben, bei dem beim Speichern eines Projekts aus PWA in eine lokale MPP-Datei das ProjectBeforeTaskChangeEvent für Daten ausgelöst wurde, die vom Benutzer nicht tatsächlich geändert worden waren.


- Es wurde ein Problem behoben, bei dem die Suche nach einer Ressource durch Ressourcenverhandlungen anhand des Namens anstelle der GUID erfolgte, was zu Problemen führen konnte, wenn mehrere Ressourcen denselben Namen aufwiesen.


- Es wurde ein Problem behoben, bei dem wenn es in einer Projektsite eine Aufgabenliste gab und diese gruppiert wurde, sie nicht schnell bearbeitet werden konnte.


- Es wurde ein Problem behoben, bei dem, wenn Sie eine Unternehmensressource über CSOM aktualisieren, die maximale Anzahl von Ressourcen möglicherweise verloren geht.


### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.


- Ein Problem wurde behoben, bei dem das Klicken auf einen Kommentarhinweis nicht dazu führte, dass die Kommentarkarte in der Ansicht angezeigt wurde.


- Ein Layout-Problem wurde behoben, bei dem sich die Linie zwischen den Spalten verschieben konnte.


- Es wurde ein Problem mit dem Nachverfolgen von Änderungen behoben, bei dem beim Öffnen von Word-Dokumenten manchmal eine Fehlermeldung angezeigt wurde.


- Es wurde ein Problem behoben, bei dem Word zu hängen scheint, wenn eine Excel-Arbeitsmappe in ein Word-Dokument eingefügt wurde.


- Es wurde ein Problem mit dem Drucken behoben, das beim Anwenden von Vertraulichkeitsbezeichnungen mit Wasserzeichen auftrat.


### <a name="office-suite"></a>Office-Suite

- Es wurde ein Problem mit dem Office-Bereitstellungstool behoben, bei dem die Konfiguration fehlschlug, wenn das Feature "RemoveMSI" in Anwesenheit des Produkts „Microsoft Application Error Reporting“ in Office 2007 verwendet wurde.


- Es wurde ein Problem behoben, bei dem bei der interaktiven SSO-API-Anmeldung ein Fehlercode zurückgegeben wurde.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-november-06"></a>Version 2010: 6. November
*Version 2010 (Build 13328.20356)*
* Korrekturen verschiedener Fehler und Leistungsprobleme.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)



[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-november-04"></a>Version 2010: 4. November
*Version 2010 (Build 13328.20340)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen. [Weitere Informationen](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a>Outlook

- **Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen. [Weitere Informationen](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a>PowerPoint

- **Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen. [Weitere Informationen](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/svg-content-office-third-party-apps)

- **Erstellen von GIFs mit transparenten Hintergründen:** Wenn Sie in ein animiertes GIF exportieren, ermöglicht Ihnen eine neue Option den transparenten Hintergrund.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/export-animated-gifs-transparent-backgrounds)

- **Exportieren eines animierten GIF in einem Bereich:** Folienbereich auswählen, wenn Sie nach animiertem GIF exportieren

### <a name="word"></a>Word

- **Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen. [Weitere Informationen](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, durch das Benutzer ihren Delegierten keine Editor-Berechtigung erteilen konnten.


### <a name="office-suite"></a>Office-Suite

- Wir haben ein Problem behoben, das zu einem Fehlschlag beim Versuch führte, Dateien zu speichern, die von SyncBacked auf „Nur Server“ übergegangen sind.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-october-27"></a>Version 2010: 27. Oktober
*Version 2010 (Build 13328.20292)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Wir haben ein Problem behoben, durch das die Cloudeinstellungen standardmäßig nicht für Benutzer aktiviert wurden.


- Es wurde ein Problem behoben, durch das die Änderungen an einer Benutzersignatur nicht gespeichert wurden.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-october-24"></a>Version 2010: 24. Oktober
*Version 2010 (Build 13328.20278)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)



[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, durch das die Kopfzeilen chinesischer Nachrichten bei der Beantwortung oder Weiterleitung nicht lesbar waren.


- Es wurde ein Problem behoben, durch das chinesische Zeichen beim Speichern als OFT-Datei in Fragezeichen geändert wurden.


### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem beim Speichern eines Projekts aus PWA in eine lokale MPP-Datei das ProjectBeforeTaskChangeEvent für Daten ausgelöst wird, die vom Benutzer nicht tatsächlich geändert wurden.


- Es wurde ein Problem behoben, bei dem das Ereignis NewVal im ProjectBeforeTaskChange nicht den richtigen Wert hat, wenn eine Verzögerung innerhalb einer Ansicht vom Typ "Aufgabenformular" geändert wird.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-october-19"></a>Version 2010: 19. Oktober
*Version 2010 (Build 13328.20210)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Sparen Sie Zeit beim Verfassen von Nachrichten:** Outlook macht Ihnen Formulierungsvorschläge, sodass Sie Nachrichten schnell verfassen können. Wenn Sie den Vorschlag akzeptieren möchten, verwenden Sie einfach die TAB-Taste.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/text-predictions-in-word-outlook)

- **Aufheben der Sprachbarriere durch einen integrierten Übersetzer:** Ab jetzt sind keine Add-Ins für die Übersetzung mehr erforderlich! Klicken Sie in einer Nachricht mit der rechten Maustaste, um bestimmte Wörter, Ausdrücke oder die gesamte Nachricht zu übersetzen. [Weitere Informationen](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

- **Updates zur Verbesserung der Benutzerfreundlichkeit für Aufgaben:** visuelle Auffrischung von Aufgabenelementen

### <a name="powerpoint"></a>PowerPoint

- **Üben Sie Ihre Präsentation mit der PowerPoint-Vorschau:** Lassen Sie sich bei den Dingen coachen, die die Aufmerksamkeit Ihrer Benutzergruppe erhöhen – wie Tempo, zu oft verwendete Wörter, Körpersprache und mehr. [Weitere Informationen](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

### <a name="word"></a>Word

- **Der Microsoft-Editor-Bereich erhält in der Desktopversion von Word ein Update:** Die aktuelle Benutzeroberfläche im Editorbereich in Word für Desktopclients wurde aktualisiert.

- **Schreibvorschläge mit einem Klick:** Übernehmen Sie Schreibvorschläge mit nur einem Klick. Der aktualisierte Editor-Bereich erleichtert die Navigation zwischen den Vorschlägen.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="powerpoint"></a>PowerPoint

- Hierbei handelt es sich um einen Fix für ein Problem, bei dem beim Schließen des Dokuments die Aufforderung „Speichern“ in einer Schleife angezeigt wird, wenn es ein Add-In gibt, das auf das Ereignis PresentationBeforeClose hört und die Eigenschaft Presentation.Saved als Teil des Ereignishandlers prüft.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-october-11"></a>Version 2010: 11. Oktober
*Version 2010 (Build 13328.20154)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Schützen Sie Ihre Daten vor schädlichen Dateien:** Application Guard schützt Sie vor Schadsoftware, indem Sie Office-Dateien in einem isolierten Container lesen, drucken und speichern können. [Weitere Informationen](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="powerpoint"></a>PowerPoint

- **Schützen Sie Ihre Daten vor schädlichen Dateien:** Application Guard schützt Sie vor Schadsoftware, indem Sie Office-Dateien in einem isolierten Container lesen, drucken und speichern können. [Weitere Informationen](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="word"></a>Word

- **Schützen Sie Ihre Daten vor schädlichen Dateien:** Application Guard schützt Sie vor Schadsoftware, indem Sie Office-Dateien in einem isolierten Container lesen, drucken und speichern können. [Weitere Informationen](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Zugriff

- Ein Problem wurde behoben, bei dem die Position der Bildlaufleiste nicht ordnungsgemäß festgelegt wurde, wenn das Abfrage/Beziehungsfenster beim Scrollen geladen wurde.


- Ein Problem wurde behoben, bei dem der Aufgabenbereich "Tabelle hinzufügen" Namen mit "&" nicht korrekt anzeigte.


### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem die mehrstufige Kategorie "manuelles Intervall" in Diagrammen nicht funktionierte.


- Es wurde ein Problem mit 2D-Kartendiagrammen behoben, bei dem das Festlegen der Farben für die Werte "Max.", "Mittel" und "Min." für eine Reihe bei Verwendung von VBA nicht funktionierte.


- Es wurde ein Problem behoben, das die Fehlermeldung „Excel hat nicht ausreichend Ressourcen zur Verfügung für die Berechnung einer oder mehrerer Formeln“ verursachen konnte.


- Es wurde ein Problem, bei dem in Datenüberprüfungslisten u. U. nicht alle Elemente in der Liste angezeigt wurden, wenn die Office-Sprache auf Spanisch festgelegt war.


- Ein Problem wurde behoben, bei dem beim Wechseln zwischen Arbeitsblättern mit großen Datenmengen eine deutliche Verzögerung auftrat, wenn ‚Seitenumbruchvorschau‘ aktiviert war.


- Es wurde ein Problem behoben, bei dem das Hinzufügen zu einer für die Datenüberprüfung verwendeten Tabelle die Optionen nicht für alle Blätter in der Arbeitsmappe aktualisiert wurden.


- Ein Problem wurde behoben, das beim Aktualisieren von OLAP-PivotTables zu einem Absturz führen könnte.


- Ein Problem wurde behoben, bei dem ChartSheet in einigen Fällen abgestürzt ist, wenn eine Formel über die Bearbeitungsleiste eingegeben wurde.


- Es wurde ein Problem behoben, bei dem die Excel-Formularleiste nicht vollständig gerendert werden konnte, wenn die Verbindung zu einem Gerät verloren ging, wie z. B. beim Verbinden/Trennen einer Remote-Sitzung oder bei einem Monitorwechsel.


### <a name="onenote"></a>OneNote

- Es wurde ein Problem behoben, bei dem ein Benutzer nicht in der Lage war, eine Notizbuch-URL aus einem Textfeld in OutSpace File > Info auszuwählen und zu kopieren.


- Es wurde ein Problem behoben, dass beim Fahren mit der Maus über die grüne Farbe in der Farbauswahl des Notizbuchs das Popup "Rote Kreide" angezeigt wurde.


- Es wurde ein Problem behoben, bei dem OneNote im Zeichenbereich hohe Kontrastfarben für benutzerdefinierte Designs nicht beachtete.


### <a name="outlook"></a>Outlook

- Behebt ein Problem, das dazu führte, dass automatisch generierte E-Mails mit einem leeren Textkörper gesendet wurden, wenn die Betreffzeile leer war.


- Es wurde ein Problem behoben, bei dem die falsche Ordner-GUID für Ordner zwischengespeichert wird.


- Wenn ein Benutzer eine E-Mail-Adresse in das Feld "Empfänger" mit dem Anzeigenamen kopierte und einfügte, wurde die E-Mail-Adresse nicht immer ordnungsgemäß analysiert, woraufhin eine Warnung zu einer ungültigen E-Mail-Adresse angezeigt wurde.  Das Problem wurde so behoben, dass Name und E-Mail-Adresse nun ordnungsgemäß analysiert werden und die Warnung nicht mehr angezeigt wird.


- Es wurde ein Problem behoben, bei dem freigegebene Ordner nicht den übergeordneten Ordnernamen zurückgegeben haben. Anstatt wurde ein leerer Pfad zurückgegeben, der nicht ordnungsgemäß an das primäre Konto ging.


- Es wurde ein Problem behoben, bei dem die Option "Speichern unter" für klassische Anlagen nicht verfügbar war.


- Es wurde ein Problem behoben, durch das ein Benutzer eine Möglichkeit zum Anpassen des Rechtfertigungstexts bietet, wenn eine Richtlinie überschrieben wird.


- Es wurde ein Problem behoben, bei dem „Änderungen nachverfolgen“ nach dem erneuten Öffnen des Entwurfs im schreibgeschützten Vorschaufenster aktiviert wurden.


- Es wurde ein Problem behoben, bei dem E-Mails ausgeblendet wurden, wenn „Posteingang mit Relevanz“ deaktiviert und eine Sortierung durchgeführt wurde.


- Es wurde ein Problem behoben, bei dem Outlook eine zweite leere Signatur für Personen mit aktivierter Cloud-Einstellung erstellt hat.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem PowerPoint beim Exportieren in das PDF-Format keine rechteckige Aufzählungspunkte exportierte.


- Ein Problem wurde behoben, bei dem GIF-Dateien im Editor und in Bildschirmpräsentationen nur einmal animiert wurden.


- Ein Problem wurde behoben, bei dem ein verknüpftes Excel-Diagramm fälschlicherweise in eine Excel-Tabelle geändert wurde, wenn der Benutzer den Quellpfad in den lokalen OneDrive-Ordner änderte.


- Es wurde ein Problem behoben bei dem, wenn Sie sich auf der letzten Folie befinden und zur nächsten Folie wechseln, nachdem Sie "Sitzung beenden" gedrückt haben und bevor die Zusammenfassung angezeigt wird, der Dialog "Sitzung beenden" auch auf der Zusammenfassungsseite sichtbar ist.


### <a name="project"></a>Project

- Es wurde ein Problem mit der ConsolidateProjects-VBA-Methode behoben, wenn Sie versuchen, dasselbe Projekt mehrmals hinzuzufügen und AttachToSources auf "false" festzulegen.


- Ein Problem wurde behoben, bei dem Sie, wenn Sie einen Ereigniscode ausführen, die Änderungen über eine Aufgaben-Maske durchführen und dann durch Klicken auf die Schaltfläche OK keine Änderungen vornehmen.


- Es wurde ein Problem mit der ConsolidateProjects-VBA-Methode behoben, wenn Sie versuchen, dasselbe Projekt mehrmals hinzuzufügen und AttachToSources auf "false" festzulegen.


- Es wurde ein Problem behoben, bei dem Sie, wenn Sie benutzerdefinierte Felder mit Formeln haben und den Ertragswert verwenden, Leistungsverzögerungen beim Wechsel der Ansichten und beim Öffnen von Projekt-/Aufgabendetails feststellen konnten.


- Es wurde ein Problem behoben, bei dem Project abstürzt, wenn Sie eine Gruppe auf die Ressourcennutzung oder die Arbeitsblattanzeige anwenden und dann eine Spalte einfügen.


### <a name="word"></a>Word

- Ein Problem wurde behoben, bei dem Links zu workflowaktivierten Dateien nicht erwartungsgemäß geöffnet wurden.


- Es wurde ein Problem behoben, bei dem es vorkam, dass wenn ein Benutzer auf eine nachverfolgte Änderung tippte (Einfügung/Löschung), ein Kommentar-Popup angezeigt wurde.


- Es wurde ein Problem mit dem Löschen von Kommentarbeschriftungen in Word behoben.


- Es wurde ein Problem in Outlook mit auf "Nicht weiterleiten" festgelegten Nachrichten behoben.


- Es wurde ein Problem mit dem Speichern eines Word-Dokuments mit Zitaten und Formeln behoben.


- Es wurde ein Problem mit dem Dialogfeld "Formatvorlagenkatalog" behoben.


### <a name="office-suite"></a>Office-Suite

- Wenn ein Benutzer ein Dokument/ eine Datei auf Tintenstrahldrucker aus Office druckt und die Druckertinte niedrig ist, wird die Meldung "Wenig Toner" oder "Kein Toner" angezeigt, auch wenn Tintenstrahldrucker keine Toner haben. Nachricht wird geändert, um "Wenig Toner/ Tinte" & "Kein Toner/ keine Tinte" anzuzeigen.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-october-07"></a>Version 2009: 07. Oktober
*Version 2009 (Build 13231.20360)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Datentypen mit Microsoft Power Query für Excel erstellen:** Erstellen Sie umfangreiche Datentypen mit Microsoft Power Query für Excel von jeder Datenquelle

### <a name="outlook"></a>Outlook

- **Die Grammatikprüfung hält Ihnen den Rücken frei:** Outlook markiert Grammatikfehler während der Eingabe, so dass Sie Vorschläge mit einem einzigen Klick anwenden können. <br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/grammar-and-style-suggestions-available-in-outlook)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Behebt ein Problem, das bewirkt, dass die Suche keine Ergebnisse zurückgibt, wenn nicht zwischengespeicherte freigegebene Kalender durchsucht werden.


- Behebt ein Problem, das bewirkt hat, dass einige Benutzer Outlook unerwartet starten, wenn Sie offline sind.


- Behebt ein Problem, durch das Delegaten beim Öffnen freigegebener Ordner in einem anderen Postfach zeitweilige Fehler erhalten.


### <a name="powerpoint"></a>PowerPoint

- Sicherheitsproblembehebung für ein Problems, bei dem IRM-Schutz beim Öffnen einer PowerPoint-Datei in der geschützten Anzeige deaktiviert wurde.


### <a name="office-suite"></a>Office-Suite

- Wenn ein Benutzer ein Dokument/ eine Datei auf Tintenstrahldrucker aus Office druckt und die Druckertinte niedrig ist, wird die Meldung "Wenig Toner" oder "Kein Toner" angezeigt, auch wenn Tintenstrahldrucker keine Toner haben. Nachricht wird geändert, um "Wenig Toner/ Tinte" & "Kein Toner/ keine Tinte" anzuzeigen.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-september-26"></a>Version 2009: 26. September
*Version 2009 (Build 13231.20262)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Behebt ein Problem, das dazu führte, dass einige automatisch generierte E-Mails mit einem leeren Textkörper gesendet wurden, wenn die Betreffzeile leer war.


### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem Sie, wenn Sie einen Ereigniscode ausführen, die Änderungen über eine Aufgaben-Formularansicht durchführen und dann durch Klicken auf die Schaltfläche OK keine Änderungen vornehmen.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-september-21"></a>Version 2009: 21. September
*Version 2009 (Build 13231.20200)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="access"></a>Zugriff

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a>Excel

- **iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen. Keine Konvertierung erforderlich.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a>OneNote

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a>Outlook

- **Unterhaltung löschen nach Nachrichtenbesitzer:** Dieses Feature ermöglicht es Ihnen, eine Unterhaltung nach dem Nachrichtenbesitzer zu löschen.

- **iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen. Keine Konvertierung erforderlich.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="powerpoint"></a>PowerPoint

- **iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen. Keine Konvertierung erforderlich.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a>Project

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a>Publisher

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a>Visio

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a>Word

- **iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen. Keine Konvertierung erforderlich.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Gehen Sie zu Datei > Optionen, und wählen Sie neben Office-Design "Systemeinstellung verwenden" aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, das die gemeinsame Dokumenterstellung für Dateien mit großen Mengen eines bestimmten Datenobjekttyps (E2o) verlangsamt hat.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-september-14"></a>Version 2009: 14. September
*Version 2009 (Build 13231.20152)*
* Korrekturen verschiedener Fehler und Leistungsprobleme.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-september-10"></a>Version 2009: 10. September
*Version 2009 (Build 13231.20126)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Access

- Dieses Problem wurde nun behoben, und es sollte jetzt kein Absturz mehr auftreten.


- Ein Problem wurde behoben, bei dem Verbindungen zu einer ODBC-Datenbank mit Anwendungen von Drittanbietern nicht funktionierten.


### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem beim Öffnen einer Datei, die die LET-Funktion enthält, die Warnmeldung angezeigt wurde: "Wir haben ein Problem mit dem Inhalt in "Ihrer Datei.xlsx" gefunden. Möchten Sie, dass wir so viel wie möglich wiederherstellen? Wenn die Quelle für diese Arbeitsmappe vertrauenswürdig ist, klicken Sie auf „Ja“.


- Es wurde ein Problem behoben, bei dem, wenn ein Benutzer einen Formelnamen einschließlich der Klammer eingab und die Hilfe über F1 aufrief, das für diese Formel spezifische Hilfethema nicht angezeigt wurde.


- Es wurde ein Problem behoben: Beim Festlegen der FormulaR1C1-Eigenschaft für einen Bereich mithilfe eines Makros waren die Zellbezüge falsch, wenn ein Diagrammblatt das aktive Blatt war.


- Es wurde ein Problem behoben, bei dem Benutzer einen PivotTable-Filter nicht ändern konnten, weil er auf einen Wert eingestellt war, der in einer Analysis Services-Datenbank nicht mehr vorhanden war.


- Es wurde ein Absturz im Zusammenhang mit XLAM-Add-In-Referenzen und benannten Bereichen behoben.


- Es wurde ein Problem behoben, bei dem Benutzer, die einen benutzerdefinierten Stil auf ein dynamisches Array anwandten, die Fehlermeldung erhielten: "Sie können einen Teil eines Arrays nicht ändern". Hierbei handelt es sich um eine Legacy-Einschränkung, die entfernt wurde.


- Es wurde ein Problem behoben, bei dem den Schaltflächen zugewiesene Makros nach der Wiederherstellung einer älteren Version der Datei beschädigt wurden.


- Ein Problem wurde behoben, bei dem Freihandeingaben dazu führen konnten, dass Excel nicht mehr reagierte.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, das mehr Flexibilität bei der Aktivierung/Deaktivierung der Standardprotokollierungsoptionen über die Gruppenrichtlinie bietet.


- Es wurde ein Problem behoben, bei dem der Legacy-Domänenname für einen E-Mail-Absender beibehalten und angezeigt wurde, nachdem ein Entwurf der E-Mail zwischen Postfächern mit Assistenten- und Manager-Berechtigungen verschoben wurde.


- Es wurde ein Problem behoben, das dazu führte, dass einige Benutzer Outlook im Offline-Status starteten, bis sie manuell wählten, online zu arbeiten.


- Es wurde ein Problem behoben, bei dem das Ausführen des VBA-Codes ActiveInspector.CommandBars.ExecuteMso ("ShowSchedulingPage") nach dem Aktivieren des Einzeiligen Menübands (SLR) zu einem Laufzeitfehler führen konnte.


- Es wurde ein Problem behoben, bei dem die Schaltflächen "OK" und "Abbrechen" im Dialogfeld "Automatische Antworten" auf einem System mit einer hohen Auflösung (z. B. 1750 x 1920) in Verbindung mit einer großen Textgröße (z. B. 175 %) nicht sichtbar waren.


- Es wurde eine Bedingung behoben, nach der das Senden einer Besprechungsanfrage von einer leeren Kontaktgruppe an eine andere Kontaktgruppe zu einem Absturz führen würde.


- Es wurde ein Problem behoben, bei dem es zu einem Absturz kam, wenn Benutzer bestimmte sehr große E-Mails öffneten.


- Es wurde ein Problem behoben, bei dem, wenn die Gruppenrichtlinie erfordert, dass ein Add-In immer aktiviert sein muss, die Überwachungs-Add-Ins nicht mehr verfügbar sind, um Benutzer daran zu hindern, das Add-In zu deaktivieren.


- Behebt ein Problem, das dazu führte, dass Benutzer durch das Auswählen mehrerer Nachrichten E-Mail-Inhalte senden konnten, für die eine "Nicht weiterleiten"-Richtlinie in OneNote festgelegt war.


- Ein Problem wurde behoben: Benutzer können IRM (Information Rights Management) jetzt für Outlook deaktivieren, ohne es für die übrigen Office-Anwendungen deaktivieren zu müssen.


- Ein Problem wurde behoben, bei dem die Benutzerkontoattribute in Active Directory für "otherTelephone" und "otherHomePhone" nicht den entsprechenden Outlook-LDAP-Attributen zugeordnet wurden.


- Diese Änderung behebt ein Problem, bei dem die Seite "Besprechung" weiterhin angezeigt wurde, nachdem der Benutzer die Registerkarten von der Seite "Besprechung" auf die Seite "Terminplanungs-Assistent" gewechselt hatte.


### <a name="powerpoint"></a>PowerPoint

- Ein Problem wurde behoben, bei dem das Menüband bzw. die Titelleiste unter bestimmten Bedingungen nicht angezeigt wurde.


- Es wurde ein Problem behoben, bei dem nach dem Starten von PowerPoint, dem Einfügen einer Folie und dem Öffnen und Schließen des Kommentarbereichs die Folien im Miniaturansichtenbereich als überlappend angezeigt wurden.


- Es wurde ein Problem behoben, durch das die Funktion zum Einfügen eines Videos deaktiviert war.


- Es wurde ein Problem behoben, bei dem Videos in Bildschirmpräsentationen nicht automatisch wiedergegeben wurden.


### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem, wenn eine Ressource mehrere Kostensatztabellen hat, die verbleibenden Kosten möglicherweise nicht korrekt berechnet werden.


- Es wurde ein Problem behoben, bei dem das Projektabschlussdatum für Projekte, die mit der Microsoft Office SharePoint Online-Aufgabenliste verbunden sind, nicht aktualisiert wird.


### <a name="visio"></a>Visio

- Die Live-Vorschau stürzt ab, wenn die Textausrichtung von Kunden gemeldet wird. Häufigster Absturz im Juli, Kopie.


### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem die Kommentarkarte einen Rahmen um den Kommentartext anzeigte, wenn der Benutzer auf den Kommentar klickte.


- Es wurde ein Problem behoben, bei dem das Aufzählungsbildsymbol nicht korrekt angezeigt wurde.


- Ein Problem wurde behoben, bei dem der Benutzer die Kopf-oder Fußzeile beim Auswählen eines Kommentars nicht verlassen konnte.


- Ein Problem wurde behoben, bei dem Word nach dem Löschen von Kommentaren abstürzen konnte.


- Es wurde ein Problem behoben, bei dem, wenn ein Benutzer einen Kommentar-Entwurf erstellte, der in einer Zeile verankert war, die bereits bestätigte Kommentare enthielt, der Entwurf in der falschen Reihenfolge in Bezug auf den bestätigten Kommentar im SideTrack angeordnet wurde.


- Es wurde ein Problem behoben, bei dem der Fokus nicht auf den Kommentarbereich gelegt wurde, wenn das Dokument auf 160 % oder mehr gezoomt wurde und der Kommentarbereich nicht sichtbar war.


- Es wurde ein Problem behoben, das Benutzer daran hinderte, Benutzerkommentar-Threads zu sehen, die die Sidetrack-Grenze überschritten, weil das Scrollen durch den Sidetrack nicht funktioniert hat.


- Ein Problem wurde behoben, bei dem die Suche nach aufgelösten Kommentaren im Sidetrack-Bereich nicht funktioniert hat.


- Es wurde ein Problem behoben, bei dem die Kommentare zu einem Dokument auf anderen geöffneten Dokumenten angezeigt wurden, nachdem zwischen den mehreren geöffneten Dokumenten gewechselt wurde.


- Es wurde ein Problem behoben, bei dem lange Links beim Speichern eines Dokuments im HTML-Format nicht umgebrochen wurden.


- Ein Problem wurde behoben, bei dem in einigen Fällen Aufzählungszeichen in E-Mails nicht korrekt angezeigt wurden.


- Es wurde ein Problem mit Makros behoben, in denen „AutoOpen“ vor „AutoExec“ ausgeführt wird.


### <a name="office-suite"></a>Office-Suite

- Es wurde ein Problem mit dem Office-Bereitstellungstool behoben, bei dem die Konfiguration fehlschlug, wenn das Feature "RemoveMSI" in Anwesenheit des Produkts „Microsoft-Anwendungsfehler-Berichterstattung“ in Office 2007 verwendet wurde.


- Im Dialogfeld "Bild komprimieren" wurde ein Problem behoben, bei dem einige vom Benutzer ausgewählte DPI-Einstellungen nicht beibehalten wurden.


- Diese Änderung behebt ein Problem, bei dem im Dialogfeld „Bild komprimieren“ bestimmte Benutzereinstellungen nicht beibehalten werden.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-september-04"></a>Version 2008: 4. September
*Version 2008 (Build 13127.20378)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="office-suite"></a>Office-Suite

- Diese Änderung behebt ein Problem, bei dem im Dialogfeld „Bild komprimieren“ bestimmte Benutzereinstellungen nicht beibehalten werden.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-september-02"></a>Version 2008: 2. September
*Version 2008 (Build 13127.20360)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Speichern von Shapes als Bildern:** mit nur wenigen Mausklicks können Sie eine Form, ein Symbol oder ein anderes Objekt als Bilddatei speichern, um Sie an anderer Stelle wiederzuverwenden. [Weitere Informationen](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **Schnelle Bearbeitungen mit dem Excel-Stift:** Ein Stifttool, mit dem Sie handschriftliche Eingaben machen und Ihre Daten schnell bearbeiten können.



[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem Excel unter bestimmten Umständen abstürzte, wenn "Format übertragen" verwendet wurde.


### <a name="word"></a>Word

- Ein Problem wurde behoben, bei dem die Basisformatvorlagen nicht mit der Standardformatvorlage aktualisiert wurden.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-august-27"></a>Version 2008: 27. August
*Version 2008 (Build 13127.20296)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Behebt ein Problem, das dazu führte, dass Benutzer, die versuchten, eine Besprechungsanfrage von einem zu ihrem Profil hinzugefügten sekundären Konto aus zu erstellen, kein leeres Von: Feld anstelle ihrer E-Mail-Adresse sahen.

- Behebt ein Problem, das dazu führte, dass Benutzer nach dem Hinzufügen eines freigegebenen Postfachs keine Verbindung mit öffentlichen Ordnern herstellen konnten.

- Behebt ein Problem, das bei der Interaktion mit Cloud-Anlagen gelegentlich zu Abstürzen führte.

- Dies behebt ein Problem, das beim Bearbeiten von Empfängern gelegentlich zu Abstürzen führte.

- Behebt ein Problem, das dazu führte, dass Benutzern bei Verwendung der kompakten Ansicht gelegentlich Anomalien angezeigt wurden.

### <a name="word"></a>Word

- Diese Änderung behebt ein Problem, bei dem Office-Anwendungen nach einer vorherigen gemeinsamen Dokumenterstellung in einem Silent-Save-Fehlerstatus hängenbleiben konnten.

- Es wurde ein Problem behoben, bei dem das Makro „AutoOpen“ vor „Autoexec“ ausgeführt wird.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-august-25"></a>Version 2008: 25. August
*Version 2008 (Build 13127.20268)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Empfangen von E-Mail-Vorschlägen bei der Suche nach Personen:** Während Sie Ihre Suchbegriffe in Outlook eingeben, werden Ihnen in den Vorschlägen die relevantesten E-Mails angezeigt.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Behebt ein Problem, durch das Benutzern beim Beantworten von oder Verfassen neuer E-Mails den folgenden Fehler angezeigt wurde: „Einige der Dateien auf dieser Webseite befinden sich nicht am erwarteten Speicherort. Möchten Sie sie dennoch herunterladen? Wenn Sie sicher sind, dass die Webseite aus einer vertrauenswürdigen Quelle stammt, klicken Sie auf 'Ja'.“


### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem die Restkosten nicht immer richtig berechnet wurden, wenn für eine Ressource mehrere Kostensatztabellen definiert waren.


### <a name="word"></a>Word

- Es wurde ein Problem behoben, durch das es bei Benutzern beim Antworten auf oder Verfassen einer neuen E-Mail zu einem Absturz kam.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-august-17"></a>Version 2008: 17. August
*Version 2008 (Build 13127.20208)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, das bewirkt hat, dass Besprechungen aus dem Kalender eines Managers nicht entfernt werden konnten, wenn sie von einem Delegierten unter bestimmten Umständen abgelehnt wurden.


- Es wurde ein Problem behoben, das bewirkt hat, dass Benutzende einiger Zeichensätze beim Hinzufügen eines Smart Link zu einer Microsoft Office SharePoint Online-Datei Dateinamen falsch angezeigt bekamen.


- Es wurde ein Problem behoben, das zu einem Absturz führte, wenn Benutzende beim Löschen von 4 oder mehr E-Mails von einem POP-Konto mit der Option "Nur Kopfzeilen herunterladen" einen Absturz erlebten.


- Es wurde ein Problem behoben, das bewirkt hat, dass das Rechtsklick-Kontextmenü nicht in den Suchsteuerelementen angezeigt wurde.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-august-11"></a>Version 2008: 11. August
*Version 2008 (Build 13127.20164)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Zugriff

- Diese Korrektur behebt das Problem, bei dem der Versuch, bestimmte Abfragen auszuführen, zuvor die Fehlermeldung „Abfrage ist zu komplex“ erzeugt hat.

- Wenn Sie Office 365 installiert haben, müssen Sie nicht mehr unsere ACE Redistributable Engine installieren, um ACE außerhalb des Office-Ökosystems bereitzustellen. Daher benötigen Sie für Benutzende mit Office 365 die ACE Redist Engine nicht mehr, und folglich sollte dieses Problem nicht auftreten.

- Das Problem wurde gelöst – Sie können nun unseren ODBC-Treiber außerhalb der Office-Click-to-Run-App verwenden.

### <a name="excel"></a>Excel

- Das Problem wurde behoben, bei dem, wenn die Reihenfolge einer Diagrammserie geändert wurde, das entsprechende, an der Serie ausgerichtete Kontrollkästchen nicht zusammen mit der Serie neu geordnet wurde.

- Beim Versuch eine Datei zu speichern, die eine Formel mit der Funktion LET() enthält, konnte ein Fehler auftreten.

- Ein Problem wurde behoben, bei dem Diagramme nicht immer wie erwartet aktualisiert wurden, wenn "ForceFullCalculation" über VBA für die Arbeitsmappe aktiviert wurde.

- Ein Problem wurde behoben, bei dem die Kopie eines Bildes mit einer radialen Verlaufsfüllung nicht mit dem Original übereinstimmte.

### <a name="onenote"></a>OneNote

- Wir haben ein Problem behoben, bei dem der Platzhaltertext im Bearbeitungsfeld „Suchen“ überlaufen würde, wenn die Größe des Anwendungsfensters auf eine kleine Dimension geändert wurde.

### <a name="outlook"></a>Outlook

- Wir haben ein Problem beim Erstellen mehrerer Profile in Outlook von derselben E-Mail-Domäne behoben.

- Es wurde ein Problem behoben, durch das einige Benutzende des Features "Verbesserungen bei gemeinsam genutzten Kalendern" nicht in der Lage waren, einen neu hinzugefügten freigegebenen Kalender anzuzeigen.

- Es wurde ein Problem behoben, das dazu führte, dass das Schloss-Symbol im Header von S/MIME-verschlüsselten Nachrichten nicht angezeigt wurde.

- Wir haben ein Problem behoben, bei dem die Option "Weiterleitung zulassen" in den "Antwortoptionen" der freigegebenen Kalenderbesprechung fehlte, wenn "Gemeinsamer Ordner herunterladen" NICHT aktiviert war.

- Ein Problem wurde behoben, das dazu führte, dass Benutzer OneDrive-Anlagen von außerhalb ihres Mandanten nicht auf ihrem lokalen Computer speichern konnten, wenn sie im Dialogfeld "Sicherheit" die Option "Speichern" wählten.

- Es wurde ein Problem behoben, bei dem die Schaltfläche "Drucken" als deaktiviert angezeigt wurde, auch wenn Benutzende über die entsprechenden Druckberechtigungen verfügten.

- Behebung eines Problems, das dazu führte, dass Anhänge aus S/MIME-Nachrichten entfernt wurden, wenn diese unverschlüsselt gesendet wurden.

- Behebung eines Problems, das dazu führte, dass Klartext-S/MIME-Nachrichten beim Senden verstümmelt wurden.

- Behebt ein Problem, durch das Anhänge beschädigt wurden, wenn eine S/MIME-E-Mail unverschlüsselt gesendet wurde.

- Es wurde ein Problem behoben, das dazu führt, dass Empfänger geschützte Nachrichten nicht speichern können, selbst wenn der/die Absender/in die Erlaubnis zum Speichern als Datei erteilt hat.

- Diese Korrektur behebt ein Problem, bei dem Benutzende beim Beantworten einer mit digitalen Rechten verwalteten Nachricht in einem Inspektorfenster keine Signatur hinzufügen konnten, wenn sie keine Eigentümerrechte für die Nachricht hatten, auf die sie antworteten.

- Diese Korrektur behebt ein Problem, das dazu führte, dass Outlook Zeilenumbrüche in Abschrifteninhalten nicht richtig anzeigte.

- Behebt ein Problem, bei dem die Bezeichnungen für einige Optionen für die erweiterte Suche in einigen Sprachen abgeschnitten wurden.

### <a name="powerpoint"></a>PowerPoint

- Ein Problem wurde behoben, bei dem die Kopie eines Bildes mit einer radialen Verlaufsfüllung nicht mit dem Original übereinstimmte.

- Ein Problem wurde behoben, bei dem die Schaltfläche „Formulare“ in PowerPoint das Erstellen von Formularen nicht zulässt, wenn der Zugriff auf den Microsoft Store nicht zulässig war.

### <a name="project"></a>Project

- Wir haben ein Problem behoben, bei dem die in der Task Board-Ansicht aufgelisteten Aufgaben nicht mit denen im Dialogfeld "Ressourcen zuordnen" synchronisiert wurden.

- Wir haben ein Problem behoben, bei dem beim Versuch, ein PDF/XPS aus dem Projekt in eine SharePoint-Dokumentenbibliothek zu speichern, nichts passiert.

- Wir haben ein Problem behoben, bei dem beim Kopieren und Einfügen einer Aufgabe mit mehreren Abhängigkeiten nicht alle Abhängigkeiten korrekt kopiert wurden.

- Ein Problem wurde behoben, bei dem für eine SharePoint-Aufgabenliste die Schaltflächen auf dem Menüband auf der zweiten Registerkarte deaktiviert sein können.

### <a name="skype"></a>Skype

- Der Hautton des Tanzemoticons wurde auf neutrale Farbe geändert

### <a name="visio"></a>Visio

- Wenn Benutzende nach dieser Korrektur die Ausführung des Löschbefehls durch einen dazwischen liegenden Mechanismus angehalten haben (in diesem Fall durch ein Add-in), wird der Speicher nicht lecken und die gesamte Maschine wird nicht beeinträchtigt.

### <a name="word"></a>Word

- Ein Problem wurde behoben, bei dem Word nicht mehr reagierte, nachdem Text und ein Bild in ein Kommentarfeld eingefügt wurden.

- Ein Problem wurde behoben, bei dem die Kopie eines Bildes mit einer radialen Verlaufsfüllung nicht mit dem Original übereinstimmte.

- Wir haben ein Problem behoben, bei dem der Platzhaltertext im Bearbeitungsfeld „Suchen“ überlaufen würde, wenn die Größe des Anwendungsfensters auf eine kleine Dimension geändert wurde.

- Ein Problem wurde behoben, bei dem sich das Überarbeitungsfeld unerwartet öffnet, wenn ein Kommentar hinzugefügt wurde, um eine Änderung zu verfolgen.

- Wir haben ein Problem behoben, bei dem der Befehl „Editor“ deaktiviert wurde, als sich der Fokus in einem Kommentartextfeld befand.

- Wir haben ein Problem behoben, bei dem der Befehl „Markup anzeigen“ deaktiviert wurde, als sich der Fokus in einem Kommentartextfeld befand.

- Ein Problem wurde behoben, bei dem die Schaltfläche „Neuer Kommentar“ nach dem Löschen des letzten Kommentars deaktiviert wurde.

- Wir haben ein Problem behoben, bei dem die Option „Bestimmte Personen“ zum Nachverfolgen von Änderungen deaktiviert wurde.

- Ein Problem wurde behoben, bei dem Links zu Dokumenten nicht über die Dropdown-Liste Einfügen -> Link in das Kommentarfeld eingefügt wurden.

- Wir haben ein gelegentliches Aufhängen beim Öffnen von HTML-Dateien behoben.

- Wir haben ein Problem in benutzerdefiniertem XML behoben, bei dem der Status der Kommentare beim Öffnen des Dokuments verloren geht.

- Ein Problem wurde behoben, bei dem die Anzahl der Hyperlinks in der VBA-Hyperlinks-Sammlung nach dem Hinzufügen eines Bildes, das einen Hyperlink enthält, nicht korrekt iteriert wurde.

- Bei dem alten, nicht webdienstbasierten Bereich Freigeben könnte das Schließen des Dokuments bei geöffnetem Bereich Freigeben zu einem Absturz führen. Dieses Problem wurde behoben.

- Wir haben ein Problem behoben, durch das, nach dem der User ein neues App-Fenster über die Taskleiste geöffnet und ein neues leeres Dokuments erstellt hatte, zusätzliche Dateien erstellt wurden.

- Wir haben ein Problem behoben, bei dem ein Benutzer, der ein Dokument bearbeitete, aber zwischenzeitlich die Berechtigungen verloren hatte, wir den Benutzer nicht darüber informierten, dass er sich erneut authentifizieren musste.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2007-august-05"></a>Version 2007: 5. August
*Version 2007 (Build 13029.20344)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)



[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, das dazu führte, dass Outlook keine Suchvorschläge abrufen konnte.


- Ein Problem wurde behoben, das gelegentlich zu einem Absturz führte, wenn Benutzer Persona-Informationen abriefen.


### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem ein Projekt, das in einen ungültigen Zustand geraten war, nicht geöffnet werden konnte.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2007-july-29"></a>Version 2007: 29. Juli
*Version 2007 (Build 13029.20308)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Abrufen von Organisationsdaten aus Power BI mithilfe von Datentypen:** Excel-Datentypen aus Power BI werden nun für Insider in Organisationen mit Office 365 E5/A5 oder Microsoft 365 E5/A5 bereitgestellt. Benötigte Informationen abrufen und deren einfache Aktualisierung ist für viele tägliche Abläufe von entscheidender Bedeutung. Sie erhalten Zugriff auf Ihre Unternehmens-oder Organisationsinformationen aus Power BI als Datentyp in Excel. Dadurch wird die Möglichkeit, verknüpfte Informationen in Tabellen einzugben, erweitert.  [Weitere Informationen](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)

### <a name="outlook"></a>Outlook

- **Auswählen, wo gesucht werden soll:** Das neue Dropdownmenü für den Suchbereich ermöglicht es Ihnen, Ihre Suche einfacher zu ändern und zwischen dem aktuellen Ordner und dem aktuellen Postfach zu wechseln. Vielen Dank an alle in "Demnächst verfügbar", die uns ihr Feedback zu der neuen Search-at-Top-Erfahrung gesendet haben. Das vorliegende Design und Update sind aus diesem Feedback entstanden!

### <a name="word"></a>Word

- **Bessere Zusammenarbeit mit modernen Kommentaren:** Für eine bessere Zusammenarbeit fügen Sie Kommentare zu Objekten hinzu, @erwähnen Sie Kollegen, und lösen Sie Kommentarthreads auf. [Weitere Informationen](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, das zu einem Absturz führte, wenn Benutzer von CLP die Absenderadresse in einer Antwort von geschütztem in ungeschützten Kontext wechselten.


- Ein Problem wurde behoben, das dazu führte, dass die Seite des Terminplanungs-Assistenten nicht angezeigt wurde.


- Ein Problem wurde behoben, das zu Formatierungsproblemen in Benachrichtigungen über einen Sicherheitsvorfälle führte.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2007-july-27"></a>Version 2007: 27. Juli
*Version 2007 (Build 13029.20292)*
* Korrekturen verschiedener Fehler und Leistungsprobleme.

## <a name="version-2007-july-20"></a>Version 2007: 20. Juli
*Version 2007 (Build 13029.20236)*
* Korrekturen verschiedener Fehler und Leistungsprobleme.

## <a name="version-2007-july-15"></a>Version 2007: 15. Juli
*Version 2007 (Build 13029.20200)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Erstellen Sie ansprechende Visio-Diagramme in Excel:** Erstellen Sie ein Flussdiagramm oder ein Organigramm durch Einfügen von Daten in ein Arbeitsblatt. [Weitere Informationen](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Zugriff

- Ein Problem wurde behoben, bei dem der Tabellenverknüpfungs-Manager einen Primärschlüssel anforderte, wenn eine verknüpfte SQL-Tabelle aktualisiert wurde.

- Es wurde ein Problem behoben, das dazu führte, dass Abfragen im Abfrage-Editor aus dem sichtbaren Bereich verschwanden.

- Ein Problem wurde behoben, bei dem die Abfrageausführung ungefähr doppelt so lange dauerte als erwartet.

- Es wurde ein Problem behoben, das dazu führte, dass Microsoft Access eine Identitätsspalte in einer verknüpften SQL Server-Tabelle nicht identifizierte, was dazu führen konnte, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.

### <a name="excel"></a>Excel

- Ein Problem wurde behoben, bei dem URLs, die nicht auf HTTP oder HTTPS basierten, nicht in der Liste "Zuletzt verwendet" angezeigt wurden.

- Ein Problem wurde behoben, bei dem beim Laden einer Arbeitsmappe mit mehreren Blättern in der Seitenumbruchvorschau ein Fehler oder eine Unterbrechung auftreten kann.

- Es wurde ein Problem behoben, bei dem Datenmodelltabellen, die in bestimmten Excel-Versionen erstellt wurden, in der "Tabellenvorschau" nicht angezeigt wurden, selbst wenn die mit der Tabelle verknüpfte Abfrage nicht bearbeitet wurde.

- Relativ/Absolut ignorieren"-Bezügen im Dialogfeld "Namen definieren \ Namen anwenden" führte dazu, dass Formeln nicht funktionierten.

- Es wurde ein Problem behoben, bei dem CustomUI XML für eine benutzerdefinierte Menüband-Registerkarte beim Speichern einer Arbeitsmappe in SharePoint/OneDrive entfernt wurde.

- Ein Problem wurde behoben, bei dem Arbeitsmappen schreibgeschützt waren, wenn für die Datei nur die Empfehlung des Schreibschutzes vorlag.

- Ein Problem wurde behoben, bei dem beim Laden einer Arbeitsmappe mit mehreren Blättern in der Seitenumbruchvorschau ein Fehler oder eine Unterbrechung auftreten kann.

- Ein Problem wurde behoben, bei dem die wichtigsten Netzlinien von Netzdiagrammen nicht ordnungsgemäß formatiert werden konnten.


- Es wurde ein Problem behoben, bei dem durch das Löschen eines erweiterten Datenfilters die Tabellenformatierung verloren gehen konnte.


- Ein Problem wurde behoben, bei dem in der Dokumentbeschriftung der vollständige Pfad eines eingebetteten PDF-Dokuments und nicht nur der Dateiname angezeigt wurde.


- Ein Problem wurde behoben, bei dem es nach dem Deaktivieren des Wolfram Cloud-Connectors und dem anschließenden Speichern und erneuten Öffnen einer Excel-Arbeitsmappe zu einem Absturz kommen konnte.


- Es wurde ein Problem behoben, durch das das Starten von Excel mit aktiviertem Solver-Add-in zu einem Absturz führte.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem Outlook nicht mehr reagierte, wenn mehr als 130 Empfänger in der Zeile "An" vorhanden waren; darüber hinaus wurde auch die Leistung beim Renderns des Texts verbessert.


- Es wurde ein Problem behoben, bei dem das IME-Fenster (Eingabemethoden-Editor) den zugrunde liegenden Text, der über den IME eingegeben wird, überlappte, wenn mehrere Monitore mit unterschiedlichen Auflösungen verwendet wurden.


- Es wurde ein Problem in der "Aufgabenleiste" behoben, bei dem für Ereignisse, die mehr als zwei Tage dauerten, für alle nachfolgenden Tage dieselbe Endzeit angezeigt wurde.


- Behebt ein Problem, durch das Benutzer das Erstellungsdatum der Anlagen sehen konnten, die Sie per Drag & Drop in Ihr Dateisystem kopiert haben, wobei es auf den 1. Januar 4501 festgestellt wurde.


- Ein Problem wurde behoben, bei dem Benutzer nicht in der Lage waren, "Senden als" oder "Senden im Auftrag von" einer Verteilerliste zu senden.


- Behebt ein Problem, durch das Stellvertretungen beim Bearbeiten eines vorhandenen Kalendertermins im Kalender eines Managers eine Fehlermeldung erhalten haben.


- Es wurde ein Problem behoben, durch das Benutzern beim Schließen eines vorher gespeicherten Termins der folgende Fehler angezeigt wurde: "Das Element kann nicht gespeichert werden, da es von einem anderen Benutzer oder in einem anderen Fenster geändert wurde. Möchten Sie eine Kopie im Standardordner für das Element erstellen?"


- Behebt ein Problem, bei dem die Option "Weiterleitung zulassen" in den "Antwortoptionen" für Kalenderbesprechungen nicht angezeigt wurde, wenn die Option für das Herunterladen freigegebener Ordner NICHT aktiviert war.


- Behebt ein Problem, das dazu führte, dass Benutzer OneDrive-Anlagen von außerhalb ihres Mandanten nicht auf ihrem lokalen Computer speichern konnten, wenn sie im Dialogfeld "Sicherheit" die Option "Speichern" wählten.


- Es wurde ein Problem behoben, das bewirkt hat, dass die Nachrichtenliste von Outlook-Benutzern, nachdem diese freigegebene Kalender verwendet hatten, einige Minuten lang nicht mehr aktualisiert wurde.


- Wir haben ein Problem behoben, das verhinderte, dass in Kalendererinnerungen genaue Uhrzeiten für Besprechungen in weniger als einer Woche angezeigt wurden. 


- Es wurde ein Problem behoben, das dazu führte, dass wenn ein Bild inline in eine Nachricht eingefügt wurde und die Nachricht dann als Entwurf gespeichert wurde, dies zu einer Größenänderung bei dem Bild führte.


- Es wurde ein Problem behoben, das bewirkt hatte, dass der Text einer NDR-Nachricht nach der Bearbeitung des Betreffs von Unicode in ASCII geändert wurde.


- Ein Problem wurde behoben, durch das die Datumsangaben im Minikalender für Benutzer in Japan nicht fett formatiert angezeigt wurden.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem der Farbindikator für Abwesenheiten eines Benutzers während einer aktiven Sitzung zur gemeinsamen Dokumenterstellung nicht im Katalog für die gemeinsame Dokumenterstellung aktualisiert wurde.


- Es wurde ein Problem behoben, durch das beim Einfügen von HTML in einen Textbereich auf einer Folie dieser stattdessen in ein Textfeld eingefügt wurde, das am oberen Rand der Folie erstellt wurde.


- Ein Problem wurde behoben, bei dem die Auswahl aller Folien in der Referentenansicht, das anschließende Verlassen der Referentenansicht mittels Alt+Tab und die Rückkehr zur Bildschirmpräsentation und das Klicken auf "Präsentation beenden" zu einem Ausnahmefehler führte.


### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem man kein PDF/XPS aus Project in einer SharePoint-Dokumentbibliothek speichern konnte.


- Ein Problem wurde behoben, bei dem Projekte aus Project Web App nicht im Project-Desktop Client geöffnet werden konnten, wenn die URL in .com endete.


- Ein Problem wurde behoben, bei dem Project beim Öffnen bestimmter XML-Dateien abstürzte.


- Es wurde ein Problem behoben, bei dem Projekte aus Project Web App im Project-Desktopclient nicht geöffnet werden konnten, wenn die URL in ".com" endete.


- Es wurde ein Problem behoben, das bewirkt, dass nicht alle Abhängigkeiten korrekt kopiert werden, wenn ein Vorgang mit mehreren Abhängigkeiten eingefügt wird.


- Ein Problem wurde behoben, bei dem die im Dialogfeld "Ressourcen zuordnen" ausgewählte Aufgabe nicht mit der in der Ansicht "Task Board" ausgewählten Aufgabe identisch ist.


- Es wurde ein Problem behoben, bei dem das Ereignis "ProjectBeforeTaskChange" nicht ausgelöst wurde, wenn eine Änderung am Projektzusammenfassungsvorgang – entweder am Projektstart/Aufgabenfeld – vorgenommen wurde.


- Es wurde ein Problem behoben, dass dazu führte, dass wenn Vorgänge mit fester Dauer zu 100 % abgeschlossen waren, das Ist-Ende aber nicht angegeben war, bei "Vorgang zu % abgeschlossen" weniger als 100 % angezeigt wurde.

- Es wurde ein Problem behoben, bei dem bei einem Basisplan-Reset oder -Update u. U. Zeitphasen-Kosten-/Arbeitsbudgetressourcen geändert wurden und die Baseline falsche Budgetwerte wiedergab.


- Es wurde ein Problem behoben, bei dem Project Planner-Links in Government Community Cloud-Umgebungen deaktiviert wurden.


- Ein Problem wurde behoben, bei dem keine Projektdatei aus einer SharePoint-Dokumentbibliothek geöffnet werden konnte, wenn sich die Bibliothek im modernen Modus befand.


### <a name="word"></a>Word

- Ein Problem wurde behoben, bei dem die Möglichkeit, die Formatierung im Kommentarbereich über die Schaltfläche "Formatierung löschen" im Office-Menüband zu deaktivieren, nicht funktionierte.


- Es wurde ein Problem behoben, durch das in eine skalierbare Vektorgrafik (Scalable Vector Graphic, SVG) eingefügter Text nach deren Einfügen in eine Word-, Excel- oder PowerPoint-Datei, dem Speichern und Schließen der Datei und erneutem Öffnen der Datei unlesbar war.


- Ein Problem wurde behoben, bei dem das Ändern der Größe einer Tabelle bei nicht angezeigtem Lineal dazu führte, dass andere Anwendungen, die im Hintergrund ausgeführt wurden, zu blinken begannen.


- Es wurde ein Problem behoben, bei dem im Modus "Gemeinsame Dokumenterstellung" Antworten auf Kommentare manchmal nicht im Kommentarbereich angezeigt wurden, sondern im Bereich "Überprüfungen".


- Es wurde ein Problem in der gemeinsamen Dokumenterstellung behoben, bei dem wenn beim Zusammenführen ein Konflikt vorlag und der Benutzer bereits Änderungen verworfen hatte, die Option zum Speichern oder Verwerfen von Änderungen nicht mehr angezeigt wurde.


- Ein Problem wurde behoben, bei dem die Farbe von HTML-Links nicht ordnungsgemäß gerendert wurde.


- Es wurde ein Problem behoben, bei dem wenn in Word eine Liste mit mehr als 50 häufig geöffneten Dokumenten vorlag, nach dem Speichern und Öffnen eines Dokuments ein Versionsverlauf angezeigt wurde, selbst wenn keine Änderungen an diesem Dokument vorgenommen wurden.


- Es wurde ein Problem mit der automatischen Speicherung bei der gemeinsamen Dokumenterstellung behoben.


- Es wurde ein Problem behoben, das beim Speichern einer Datei, die ein Makro enthielt, unter einem neuen Namen dazu führte, dass sie mit einer .docx-Erweiterung und dem Dateinamen "WRO0004.docx" gespeichert wurde, und zwar unabhängig davon, was der Benutzer eingegeben hatte, wodurch das Dokument unbrauchbar wurde.


### <a name="office-suite"></a>Office-Suite

- Ein Timing-Problem konnte beim Schließen von Office-Dateien zu einem Absturz führen

- Der Fix für dieses Problem bestand darin, sicherzustellen, dass der Dienst hinzugefügte Produkte ordnungsgemäß berechnet. Wir haben die neu hinzugefügten Produkte herausgefiltert (dabei wurde sichergestellt, dass sie auch in der neuen Konfiguration vorhanden sind) und sie am Ende der vorhandenen Produkt-Release-IDs hinzugefügt.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-july-09"></a>Version 2006: 09. Juli
*Version 2006 (Build 13001.20384)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Eine PDF-Verbindung herstellen:** Herstellen einer Verbindung zu, Importieren und Aktualisieren von Daten aus einer PDF-Datei. [Weitere Informationen](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- **Erstellen von Variablen zur Verwendung in Formeln:** Verbessern Sie Leistung, Lesbarkeit und Zusammensetzbarkeit mit der LET-Funktion. Mit dieser Funktion können Sie benannte Variablen in neuen oder bereits vorhandenen Formeln erstellen. [Weitere Informationen](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/).

- **Tastenkombinationen in Excel:** Aktualisierte Tastenkombinationen für Excel

### <a name="outlook"></a>Outlook

- **Erstellen von Umfragen in Outlook mit Quick Poll** : Einfaches Erstellen einer Umfrage, Sammeln von Stimmen und Anzeigen der Ergebnisse in einer E-Mail [Weitere Informationen](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- **Bewahren Sie die Klangtreue Ihrer Bilder, wenn Sie diese als Teil einer E-Mail versenden:** Eine neue Outlook-Einstellung ist verfügbar, um die Bildkomprimierung zu begrenzen, wenn Sie Bilder als Teil des E-Mail-Inhalts versenden.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Access

- Dieses Problem wurde behoben, und Sie sollten erwarten, dass Sie verknüpfte SQL-Tabellen, die ein Identitätsfeld (z. B. Autonummer) enthalten, erfolgreich in Access einfügen können.

### <a name="excel"></a>Excel

- Ein Absturz wurde behoben, der beim Versuch, eine Datenverbindung herzustellen, auftreten konnte, wenn Sie sich von Ihrem Konto abgemeldet haben.

### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, das dazu führte, dass Benutzer OneDrive-Anlagen von außerhalb ihres Mandanten nicht auf ihrem lokalen Computer speichern konnten, wenn sie im Dialogfeld "Sicherheit" die Option "Speichern" wählten.

### <a name="office-suite"></a>Office-Suite

- Ein neuer Sturz von AppV51 wurde zurückportiert, um eine Regression im vorherigen AppV51 zu beheben.

- Der Office-Host stürzte in Fenstern ab, wenn ein Add-In aktiviert wird, während der Registrierungswert TabProcGrowth vom Typ REG_SZ und mit dem Wert "0" ist.  Der Registrierungswert TabProcGrowth kann unter einem von 4 Pfaden stehen: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-june-25"></a>Version 2006: 25. Juni
*Version 2006 (Build 13001.20266)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="visio"></a>Visio

- **Erstellen Sie ansprechende Visio-Diagramme in Excel:** Erstellen Sie ein Flussdiagramm oder ein Organigramm auf der Grundlage von Daten in einem Arbeitsblatt.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Access

- Dieses Problem ist jetzt behoben. Bitte teilen Sie dem Team mit, wenn Sie weitere Probleme mit diesem Prozess haben.


### <a name="outlook"></a>Outlook

- <span style="display:inline !important;">Behebt ein Problem, das dazu führte, dass Benutzer<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">das Erstellungsdatum von&nbsp; Anlagen sahen, die sie per Drag & Drop in ihr Dateisystem kopierten, wobei&nbsp; auf den 1. Januar 4501 gesetzt wurde.</span><br>


- <span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Behebt ein Problem, das dazu führte, dass Benutzer von Verbesserungen am "Freigegebenen Kalender" Kalenderfehler sahen.</span><br>


- <span style="display:inline !important;">Behebt ein Problem, das dazu führte, dass Benutzer ständig von Outlook aufgefordert wurden, das Reparaturtool für den Posteingang auszuführen.</span><br>


- <span style="display:inline !important;">Behebt ein Problem, das dazu führte, dass bei der Suche nach einem Feature in "Features vorschlagen" keine Ergebnisse zurückgegeben wurden und der Benutzer keine Möglichkeit hatte, eine neue Idee für Features einzureichen.</span><br>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-june-18"></a>Version 2006: 18. Juni
*Version 2006 (Build 13001.20198)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel



- **In angeheftete Ordner speichern:** Durch das Anheften Ihrer Ordner wird das Speichern von Office-Dateien einfacher. Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die verfügbaren Ordner wünschen, wenn eine neue Datei gespeichert wird. Wir freuen uns, Ihnen eine neue Funktion zur Verfügung stellen zu können: anheften Ihrer Ordner im Dialogfeld "Speichern". Mit dieser neuen Funktion können Sie Ihre Word-, Excel- und PowerPoint-Dateien einfacher speichern. <br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="powerpoint"></a>PowerPoint

- **In angeheftete Ordner speichern:** Durch das Anheften Ihrer Ordner wird das Speichern von Office-Dateien einfacher. Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die verfügbaren Ordner wünschen, wenn eine neue Datei gespeichert wird. Wir freuen uns, Ihnen eine neue Funktion zur Verfügung stellen zu können: anheften Ihrer Ordner im Dialogfeld "Speichern". Mit dieser neuen Funktion können Sie Ihre Word-, Excel- und PowerPoint-Dateien einfacher speichern.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="word"></a>Word

- **In angeheftete Ordner speichern:** Durch das Anheften Ihrer Ordner wird das Speichern von Office-Dateien einfacher. Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die verfügbaren Ordner wünschen, wenn eine neue Datei gespeichert wird. Wir freuen uns, Ihnen eine neue Funktion zur Verfügung stellen zu können: anheften Ihrer Ordner im Dialogfeld "Speichern". Mit dieser neuen Funktion können Sie Ihre Word-, Excel- und PowerPoint-Dateien einfacher speichern. <br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, das dazu führte, dass CustomUI XML für eine benutzerdefinierte Multifunktionsleisten-Registerkarte beim Speichern in SharePoint/OneDrive entfernt wurde.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, das dazu führte, dass STRG+Klicken nicht mehr funktionierte, wenn die Cloud-Einstellungen aktiviert waren.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem eine Aufgabe, die als 100 % abgeschlossen gekennzeichnet ist, fälschlicherweise weniger als 100 % abgeschlossen ist.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-june-11"></a>Version 2006: 11. Juni
*Version 2006 (Build 13001.20144)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="powerpoint"></a>PowerPoint

- **Verbesserte Stream-Video-Leistung in PowerPoint:** Wir haben die Wiedergabeleistung von Microsoft Stream-Videos verbessert, um die Ladezeit von Videos zu minimieren und eine reibungslose Wiedergabe zu ermöglichen. Verwenden Sie Ihre Unternehmensvideos aus Microsoft Stream, um bessere Präsentationen zu erstellen.

### <a name="word"></a>Word

- **Beibehalten von Text in Vektoren:** Sie können jetzt den Text in Karten, Diagrammen und anderen SVG-Vektoren beibehalten, wenn Sie diese Objekte in Excel, Word und PowerPoint konvertieren.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem Excel gelegentlich beim Einschalten von OneDrive heruntergefahren wurde.

- Es wurde ein Problem behoben, bei dem benutzerdefinierte Werte auf der Diagrammachse nicht korrekt angewendet wurden.

- Es wurde ein Problem behoben, bei dem Arbeitsblätter, die mehrere Formeln mit definierten Namen enthielten, zu längeren Zeiten beim Speichern von Dateien geführt haben.

- Es wurde ein Problem behoben, das dazu führte, dass Druckernamen in der Liste der verfügbaren Drucker dupliziert wurden.

- Es wurde ein Problem behoben, das zur Verbesserung der Leistung führte, wenn zusammengeführte Spalten gelöscht wurden.

- Es wurde ein Problem behoben, bei dem die Fehlermeldung "Diese Arbeitsmappe wird derzeit von einer anderen Arbeitsmappe referenziert und kann nicht geschlossen werden" erschien, weil Add-Ins in alphabetischer Reihenfolge und nicht in einer vom Benutzer festgelegten Reihenfolge geladen wurden.

- Es wurde ein Problem behoben, bei dem der Speicher bei der Verwaltung von Schriftarten zwischen Excel und einigen Hilfstechnologie-Anwendungen von Drittanbietern beschädigt wurde.

- Es wurde ein Problem behoben, bei dem das Klicken auf einer mit einem Lesezeichen versehenen Verknüpfung innerhalb derselben Arbeitsmappe dazu führte, dass die Arbeitsmappe ausgeblendet wurde.

- Es wurde ein Problem behoben, bei dem einige kopierte und eingefügte Diagrammverknüpfungen zugeordnete Laufwerksadressen anstelle von Universaladressen verwendeten.

- Es wurde ein Problem behoben, bei dem Excel nicht mehr reagierte, nachdem STRG+UMSCHALT+Pfeiltasten zum Scrollen verwendet wurden, wenn das Excel-Fenster von Teams gemeinsam genutzt wurde.

- Es wurde ein Problem behoben, bei dem Excel abstürzte, wenn Add-Ins auf Arbeitsblättern, die Shapes mit „noSelect“-Sperren enthalten, nach „Hostelemente“ fragen.

- Es wurde ein Problem behoben, bei dem Excel abstürzen kann, wenn versucht wird, PivotTables in ein Diagrammblatt einzufügen.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem das IME-Fenster (Eingabemethoden-Editor) den zugrunde liegenden Text, der über den IME eingegeben wird, überlappte, wenn mehrere Monitore mit unterschiedlichen Auflösungen verwendet wurden.

- Es wurde ein Problem behoben, bei dem die Anzeige einer Vorlage beim Verfassen einer neuen E-Mail-Nachricht zu einem Absturz führen konnte.

- Es wurde ein Problem behoben, bei dem Benutzer nach der Outlook-Version 1911 nicht in der Lage waren, öffentliche Ordner von Exchange 2010 zu öffnen.

- Es wurde ein Problem behoben, bei dem die Schaltfläche "Kategorisieren" für Gruppenkalender im Office-Menüband deaktiviert wurde.

- Es wurde ein Problem behoben, bei dem Outlook die Datenschutzrichtlinie nicht aktiviert hat, um Tipps für Benutzer zu geben, die für den Dienst bezahlt haben und M365 Business Plus-Pläne nutzen.

- Ein Problem wurde behoben, das dazu geführt hat, dass Outlook bei einigen Windows-Versionen abstürzt.

- Es wurde ein Problem behoben, bei dem Benutzer nicht in der Lage waren, einen Kalender für einen Gastbenutzer freizugeben.

- Es wurde ein Problem behoben, bei dem Benutzer Kalendereinträge, welche die Mitternachtsschwelle überstiegen, als Ganztagesereignisse sahen.

- Es wurde ein Problem behoben, das dazu führte, dass die Dropdown-Liste "Online-Archiv" in den Ordnereigenschaften für Benutzer mit hohem DPI-Wert nicht angezeigt wurde.

- Es wurde ein Problem behoben, bei dem das Ereignis "Folder.BeforeItemMove" nicht korrekt ausgelöst wurde, wenn ein Benutzer Elemente zwischen Ordnern verschoben hat.

- Es wurde ein Problem behoben, bei dem Outlook abstürzte, wenn zwei Add-Ins eine Schaltfläche zur gleichen Gruppe im Menüband hinzufügten.

- Es wurde ein Problem behoben, das zu einem Absturz in Outlook führte, wenn Benutzer mit Verknüpfungen in E-Mails im Format "Nur Text" arbeiteten.

- Es wurde ein Problem behoben, das dazu führte, dass Outlook lange Dateinamen, die mit RFC2231 kodiert sind, nicht analysieren konnte.

- Es wurde ein Problem behoben, das bei Outlook-Benutzern bei der Verwendung von Sprachausgaben zu zeitweiligen Aussetzern führte.

- Es wurde ein Problem behoben, das bei Benutzern mit widersprüchlichen Kontakten zu Abstürzen in Outlook führen konnte.

### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem beim Öffnen von Server-konfigurierten Dateien mit formularbasierter Authentifizierung behoben.

- Es wurde ein Problem behoben, bei dem PowerPoint-Dateien mit eingebetteten Diagrammen/Arbeitsmappen zu Fehlern beim Speichern der Datei führen konnten.

- Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.

- Es wurde ein Problem behoben, bei dem die Folien nach dem Zoomen mit dem Mausrad nicht zentriert wurden.

- Ein Problem wurde behoben, bei dem Tastenkombinationen und die Rechtschreibprüfung bei Verwendung einer Schweizer Englisch-Tastatur (QWERTZ) nicht erwartungsgemäß funktionierten.

- Es wurde ein Problem behoben, bei dem ein Bereich "Kommentar", der vom Benutzer geschlossen wurde, automatisch wieder geöffnet wurde.

- Es wurde ein Problem behoben, bei dem der Folieneditor von einer Folie die nächste überlappte.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem das Ereignis "ProjectBeforeTaskChange" nicht ausgelöst wurde, wenn eine Änderung am Projektzusammenfassungsvorgang – entweder am Projektstart/Aufgabenfeld – vorgenommen wurde.

- Es wurde ein Problem behoben, bei dem eine Aufgabe, die als 100 % abgeschlossen gekennzeichnet ist, fälschlicherweise weniger als 100 % abgeschlossen ist.

- Es wurde ein Problem behoben, bei dem "Project" nach dem Klicken auf "Optionen" abstürzte.

- Es wurde ein Problem behoben, das verhinderte, dass verwaiste Aufgaben gelöscht oder neu zugewiesen werden konnten, nachdem ihr übergeordneter Plan gelöscht wurde.

### <a name="visio"></a>Visio

- Es gab eine Regression im abhängigen Code, die behoben wurde. Jetzt werden die Bilder in Visio-Diensten, die auf SharePoint Onprem ausgeführt werden, gerendert.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem die Zeitstempel in den Bereichen "Kommentar" nicht auf der Systemgebietszeit basierten.

- Es wurde ein Problem beim Öffnen von Word-Dokumenten aus der benutzerdefinierten Dokumentbereitstellung (aspx) behoben, wenn die URL eine Abfragekomponente enthält.

- Es wurde ein Problem behoben, bei dem das Kopieren und Einfügen von Text in einem Kommentarbereich nicht angezeigt wurde.

- Es wurde ein Problem behoben, bei dem Verknüpfungen in Kommentaren nicht funktionierten.

- Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.

- Wir haben ein Problem behoben, bei dem die Kommentare zwischen der Webanwendung und der Desktopanwendung nicht synchronisiert wurden.

- Es wurde ein Problem behoben, bei dem Kommentar-Hinweisblasen bei einer Vergrößerung von 100 % verschwommen erschienen.

- Es wurde ein Problem behoben, bei dem beim Hinzufügen eines neuen Kommentars zu einem leeren Dokument nichts geschah.

- Es wurde ein Problem behoben, bei dem das Einfügen von HTML in WordMail für Kalender nicht funktionierte.

- Es wurde ein Problem behoben, bei dem die Beantwortung eines Kommentars in einer gemeinsam verfassten Sitzung manchmal zum Einfrieren von Word führen konnte.

- Es wurde ein Problem behoben, bei dem das Einfügen oder Aktualisieren eines Indexes in einem Dokument mit mehr als hundert Einträgen zum Absturz der Anwendung führte.

- Es wurde ein Problem behoben, bei dem die Aktivierung der Richtlinie Word 2007 und höher Binärdokumente und -vorlagen dazu führen würde, dass einige Fälle bei der gemeinsamen Dokumentenerstellung fehlschlugen.

- Es wurde ein Problem behoben, durch das Dateien mit benutzerdefinierten XML-Werten extrem langsam geöffnet wurden.

- Es wurde ein Problem behoben, bei dem Dateien mit langen Pfadnamen (größer als 32 KB) nicht geöffnet werden konnten und eine entsprechende Fehlermeldung nicht angezeigt wurde.

### <a name="office-suite"></a>Office-Suite

- Wir haben das Problem untersucht und behoben, bei dem die Bereitstellung von Office 365 ProPlus über InTune nach einem Herunterfahren des Betriebssystems pausiert wurde.

- Es wurde ein Problem in Visual Basic for Applications in Microsoft Office behoben, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthielten, von der Office-Anwendung beim Laden als fehlerhaft angesehen wurden.

- Das Update behebt ein Problem in Microsoft Office, bei dem Visual Basic for Applications-Projekte mit Referenzen, die bei der Suche nach in der PATH-Umgebungsvariable angegebenen Speicherorten gefunden werden sollen, zur Laufzeit möglicherweise nicht richtig gefunden werden, was zu VBA-Laufzeitfehlern führt.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-june-08"></a>Version 2005: 08. Juni
*Version 2005 (Build 12827.20336)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem mit dem Dialog zum Ersetzen von Schriftarten behoben, bei dem die Dropdown-Liste zum Ersetzen von Schriftarten nur Schriftarten innerhalb der Präsentation anzeigt, statt der auf dem System installierten Schriftarten.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-june-04"></a>Version 2005: 04. Juni
*Version 2005 (Build 12827.20320)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="access"></a>Access

- **Bleiben Sie am Puls der Zeit! Der Datentyp "Datum/Uhrzeit Erweitert" hat eine bessere Genauigkeit:** Einführung eines neuen und verbesserten Datentyps.  Zur Verbesserung der Syntaxkompatibilität mit SQL und zur Erhöhung der Genauigkeit und des Detaillierungsgrads von Datensätzen, die Datum und Uhrzeit enthalten, implementieren wir den Datentyp "DateTime2" in Access. Dieser zusätzliche Datentyp für Datum und Uhrzeit umfasst einen größeren Datumsbereich (0001-01-01 bis 9999-12-31) mit einer höher spezifizierten Zeitgenauigkeit (Nanosekunden statt Sekunden), die Sie bereitstellen und Berechnungen durchführen können. Zum Aktivieren wählen Sie Neues Feld > Datum und Uhrzeit Erweitert. [Weitere Informationen](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a>Excel

- **Erstellen von PivotTables aus Datasets in Power BI in Excel:** Sie können mit wenigen Klicks PivotTables in Excel erstellen, die mit in Power BI gespeicherten Datensätzen verbunden sind.  Auf diese Weise können Sie sowohl PivotTables als auch Power BI optimal nutzen. Sie können Ihre Daten mit PivotTables aus Ihren sicheren Power BI-Datensätzen berechnen, zusammenfassen und analysieren.

### <a name="outlook"></a>Outlook

- **Option zum schnellen Wiederöffnen von Elementen aus der vorherigen Outlook-Sitzung:** Wir haben eine Option zum schnellen Wiederöffnen von Elementen aus einer vorherigen Outlook-Sitzung hinzugefügt.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="powerpoint"></a>PowerPoint

- Dies behebt einen Absturz, wenn Benutzer sowohl moderne als auch ältere Kommentare in einer Datei haben, wodurch ein Upgrade der Kommentare ausgelöst wird.


### <a name="office-suite"></a>Office-Suite

- Es wurde das Problem der Fehlerrate von „ValidateInstall“ behoben, indem die Bing-Add-On-Installationsvalidierung standardmäßig auf „wahr“ gesetzt und die erfolgreiche Ausführung von MSI als erfolgreiche Installation betrachtet wurde.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-may-29"></a>Version 2005: 29. Mai
*Version 2005 (Build 12827.20268)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates

### <a name="excel"></a>Excel

- **Tabellendarstellung:** Sortieren/Filtern während der Zusammenarbeit mit anderen in der Excel-Desktopumgebung.

### <a name="outlook"></a>Outlook

- **Zusätzliche Schaltflächen zu Outlook-Toastbenachrichtigungen hinzugefügt:** In Outlook-Toastbenachrichtigungen werden nun Schaltflächen für schnelle Aktionen angezeigt, wenn Outlook unter Windows 10 ausgeführt wird.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme



### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, das dazu führte, dass Benutzer von Windows 10-Serverversionen die Warnung "Antivirenstatus: Ungültig" gesehen haben. Diese Version von Windows unterstützt die Erkennung von Antivirus, aber es wurde kein Antivirus gefunden, obwohl Antivirus korrekt installiert war.

### <a name="office-suite"></a>Office-Suite

- Der Office-Host stürzte in Fenstern ab, wenn ein Add-In aktiviert wird, während der Registrierungsschlüssel HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth auf Null gesetzt ist. Mit dieser Änderung wird dieses Problem behoben.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-may-21"></a>Version 2005: 21. Mai
*Version 2005 (Build 12827.20210)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)




[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem Excel u. U. nicht mehr reagierte, nachdem STRG+UMSCHALT+Pfeiltasten zum Scrollen verwendet wurden, wenn das Excel-Fenster über Microsoft Teams gemeinsam genutzt wurde.


- In einigen Fällen führt das Anklicken einer Verknüpfung zu einem Ort innerhalb derselben Arbeitsmappe dazu, dass die Arbeitsmappe ausgeblendet wird.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem mit dem Ereignis "CLP-Überwachung" für die Bezeichnung "Antworten/Weiterleiten" behoben.


- Es wurde ein Problem behoben, bei dem beim Einreichen von Feedback aus einer Administratorbenachrichtigung ein Absturz verursacht wurde.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2005-may-14"></a>Version 2005: 14. Mai
*Version 2005 (Build 12827.20160)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Automatisches Anwenden oder Empfehlen von Vertraulichkeitsbezeichnungen:** Office kann eine Vertraulichkeitsbezeichnung basierend auf den erkannten vertraulichen Inhalten empfehlen oder automatisch anwenden.

### <a name="powerpoint"></a>PowerPoint

- **Kein Clicker benötigt: das erledigen Ihre Ohrhörer** : Verwenden Sie Ihre Surface Earbuds, um Ihre PowerPoint-Präsentationen zu steuern. Wichtig: Sie müssen Ihre Surface Earbuds in der Surface Audio-App für Windows 10 koppeln, um Gesten für die Steuerung von Präsentationen verwenden zu können. Anweisungen für die ersten Schritte mit der Surface Audio-App unter Windows 10 finden Sie hier. [Weitere Informationen](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- **Automatisches Anwenden oder Empfehlen von Vertraulichkeitsbezeichnungen:** Office kann eine Vertraulichkeitsbezeichnung basierend auf den erkannten vertraulichen Inhalten empfehlen oder automatisch anwenden.

### <a name="word"></a>Word

- **Automatisches Anwenden oder Empfehlen von Vertraulichkeitsbezeichnungen:** Office kann eine Vertraulichkeitsbezeichnung basierend auf den erkannten vertraulichen Inhalten empfehlen oder automatisch anwenden.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme

### <a name="excel"></a>Excel

- Die Größe der Steuerelemente zur Bearbeitung von Zellreferenzen im Dialogfeld "Benutzerdefinierte Fehlerindikatoren", das bei Diagrammen verwendet wird, wurde erhöht.

- Ein Problem wurde behoben, bei dem die Diagrammdatentabelle Werte in einer Datumsachse nicht korrekt rendern konnte.

- Es wurde ein Problem behoben, bei dem Seitenumbrüche nicht deaktiviert werden konnten, nachdem die Seitenlayout- oder Seitenumbruchsvorschau angezeigt wurde.

- Es wurde ein Problem behoben, bei dem Diagrammlinienarten nach dem Ein- und Ausblenden von Spalten mit Seriendaten verloren gehen konnten.

- Es wurde ein Problem behoben, bei dem das Einfügen einer Spalte in eine gefilterte Liste länger als erwartet dauern würde.

- Ein Problem mit der Skalierung von Kontrollkästchen in Formularsteuerelementen beim Drucken wurde behoben.

- Es wurde ein Problem behoben, bei dem die externe Verknüpfung nicht mehr funktioniert, nachdem die Datei erneut geöffnet wurde, wenn der Dateipfad zu lang ist.

- In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.

- Application.Evaluate (VBA) funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.

- In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.

- Diese Änderung behebt ein Problem, bei dem Informationen zur bedingten Formatierung (CF) nicht korrekt in XLSB-Dateien gespeichert wurden.

- Diese Änderung behebt ein Problem, bei dem das Bestimmtheitsmaß der Diagrammtrendlinie (im Fall des erzwungenen y-Achsenabschnitts) falsch war, obwohl die Funktion LINEST den richtigen Wert zurückgibt.

- Diese Änderung behebt ein Problem, bei dem benutzerdefinierte Diagramm-Trendlinienformatierungen nicht immer gespeichert wurden.

- Ein Absturz konnte auftreten, wenn versucht wurde, Änderungen mithilfe des Legacymodus "Freigegebene Arbeitsmappe" auf einem neuen Blatt für eine Arbeitsmappe aufzulisten.

- Das Problem, bei dem es sein konnte, dass benutzerdefinierte Formatierungen in Pivot-Diagrammen nicht gespeichert wurden, wenn die Option "Invertieren, wenn negativ" aktiviert war, wurde behoben.

- Es wurde ein Problem behoben, bei dem die benutzerdefinierte Formatierung für einen einzelnen Datenpunkt in einem Pivot-Diagramm nicht gespeichert wurde, wenn die Option "Invertieren, wenn negativ" ausgewählt wurde.

- Diese Änderung behebt ein Problem, bei dem das in eine CSV-Datei hochgeladene @-Zeichen dazu führte, dass die Zeichenfolge nach dem @-Zeichen in eine Formel konvertiert wurde.

- Es wurde ein Problem behoben, bei dem Dezimalwerte in der SEQUENCE-Funktion nicht korrekt gerundet wurden.

### <a name="onenote"></a>OneNote

- Ein Problem beim Speichern von Zeilenumbrüchen als vertikale Registerkarten wurde behoben.

### <a name="outlook"></a>Outlook

- Behebt ein Problem, das dazu führte, dass Benutzer keine "Persönliche Kontaktgruppe" als "Besprechungsteilnehmer" hinzufügen konnten.

- Es wurde ein Problem behoben, bei dem die Schaltfläche "Kategorisieren" für Gruppenkalender im Office-Menüband deaktiviert wurde.

- Es wurde ein Problem behoben, durch das Outlook nach einem Windows-Update beim Öffnen von lokal gespeicherten MSG- oder OFT-Dateien abstürzte.

- Es wurde ein Problem behoben, bei dem Gruppenordner von Unternehmenskunden, die nicht implementiert sind oder nicht funktionieren, in Outlook zu der Meldung "reagiert nicht" führte.

- Es wurde ein Problem behoben, das dazu führte, dass sehr lange Safelinks, auf die Benutzer im Outlook-Desktopclient klickten, aufgrund von Trunkierung nicht geladen wurden.

- Es wurde ein Problem behoben, bei dem Outlook-Ordner mit Namen, die DBCS-Zeichen (Doublebyte-Zeichensatz) enthalten, bei der Synchronisierung mit dem Server zeitweise verschwanden. Dazu musste Outlook mit einem IMAP-Konto konfiguriert und auf einem System mit dem Gebietsschema „Japanisch“ ausgeführt werden.

- Es wurde ein Problem behoben, das dazu führte, dass Löschregeln, die für andere Postfächer als das primäre Postfach des Benutzers erstellt wurden, ungültig wurden.

- Es wurde ein Problem behoben, das dazu führte, dass Anlagen beim Weiterleiten einer verschlüsselten Nachricht verworfen wurden.

- Es wurde ein Problem behoben, das dazu geführt hat, dass bei Besprechungen, die mehr als 2 Monate entfernt sind, ein Besprechungsthema im "Terminplanungs-Assistenten" nicht angezeigt wird.

- Behebt ein Problem, das dazu führte, dass Benutzer beim Weiterleiten großer HTML-Nachrichten den Nachrichtentext abgeschnitten sahen.

- Es wurde die Möglichkeit des Erzwingens der S/MIME-Standardsignatur-Konfiguration über eine Gruppenrichtlinie hinzugefügt.

### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem Entwürfe von Kommentaren nicht verfügbar waren, wenn ein Benutzer einen Kommentar erstellte, ohne ihn zu posten, und den Kommentarbereich schloss, dann ein neues Fenster öffnete, über mehrere Folien navigierte, das Fenster schloss und schließlich den Kommentarbereich in der ursprünglichen Präsentation wieder öffnete.

- Es wurde ein Problem behoben, bei dem beim Bewegen des Mauszeigers über das Sternchen-Symbol (*) der Benutzername und das Datum der letzten Person, die das Dokument aktualisiert hat, nicht angezeigt wurden.

### <a name="project"></a>Project

- Wenn Vorgänger/Nachfolger-Daten in einer Formular-Maske bearbeitet werden, wird ein zusätzliches ProjectBeforeTaskChange-Ereignis ausgelöst.

- Es wurde ein Problem behoben, bei dem Project abstürzen konnte, wenn das Feld „Boardstatus“ in einem Projekt geändert wurde, das mit einer SharePoint-Aufgabenliste verbunden ist.

- Ein Problem wurde behoben, bei dem Project beim Speichern von Projekten möglicherweise abstürzt, die mit älteren Project-Versionen erstellt wurden.

- Folgendes Problem wurde behoben: Wenn Sie Project in Verbindung mit der Project Web App verwenden, das Kommas als Dezimaltrennzeichen festgelegt ist, und Sie versuchten, eine Verzögerung hinzuzufügen, schlägt die Methode "TaskDependencies Add" fehl.


### <a name="word"></a>Word

- Es wurde ein Problem behoben, das dazu führte, dass das Einfügen von Kommentaren in ein Dokument im Kollaborationsmodus nicht immer funktionierte.

- Diese Änderung behebt ein Problem, bei dem die Personenkarte kurzzeitig eingeblendet wurde, wenn auf die Erwähnung geklickt wurde.

- Beim Aktivieren der Option "Lesezeichen anzeigen" wurden keine Lesezeichen angezeigt. Dieser Fehler wurde behoben.

- Es wurde das Problem behoben, dass beim Schließen eines Dokuments mit Kommentarentwürfen der Benutzer aufgefordert wurde, ob er das Dokument schließen möchte, ohne die Kommentarentwürfe zu speichern. Das Abbrechen der Eingabeaufforderung schloss das Dokument, anstatt es geöffnet zu lassen.

- Ein Problem beim Kopieren und Einfügen von Überschriften wurde behoben.

- Es wurde ein Problem behoben, bei dem die Übersetzung eines geposteten Kommentars den Fehler "Fehler beim Einfügen des übersetzten Textes" zur Folge hatte.

- Diese Änderung behebt ein Problem, bei dem Text mit Hyperlinks möglicherweise nicht angezeigt wurde, wenn die Option "Feldcodes statt ihrer Werte anzeigen" aktiviert war.

- In der Webansicht und im Plastischen Reader wurde durch das Anklicken eines Hinweises nach oben gescrollt, obwohl er bereits angezeigt wurde. Dieser Fehler wurde behoben.

- Wir haben ein Problem behoben, dass infolge des Speicherns einer Datei, die ein Makro enthält, unter einem neuen Namen sie mit der Erweiterung DOCX und dem Dateinamen WRO0004.docx gespeichert wurde, und zwar unabhängig davon, was der Benutzer eingab, wodurch das Dokument unbrauchbar wurde.

### <a name="office-suite"></a>Office-Suite

- Wenn ein Benutzer eine Richtlinie erhält, die ihn in die Kategorie "Nur für Teams" verschiebt, konnte er dennoch das Outlook-Add-In "Skype for Business" zur Planung von Besprechungen verwenden.  Nach diesem Update können Sie keine Besprechungen mit Skype for Business mehr planen, nachdem der Client die Richtlinie gelesen hat, in der angegeben ist, dass der Benutzer "Nur für Teams" ist, und in den Modus "Nur an Besprechung teilnehmen" wechselt.  Darüber hinaus aktiviert sich das Outlook-Add-In "Skype for Business" beim Start nicht selbst, wenn es sieht, dass sich der Skype for Business-Client im Modus "Nur an Besprechung teilnehmen" befindet.

- Das Update behebt ein Problem in Microsoft Office, bei dem Visual Basic for Applications-Projekte mit Referenzen, die bei der Suche nach in der PATH-Umgebungsvariable angegebenen Speicherorten gefunden werden sollen, zur Laufzeit möglicherweise nicht richtig gefunden werden, was zu VBA-Laufzeitfehlern führt.

- Dieses Update behebt ein Problem in Visual Basic for Applications in Microsoft Office, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung beim Laden als fehlerhaft angesehen werden.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-may-11"></a>Version 2004: 11. Mai
*Version 2004 (Build 12730.20270)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen.

### <a name="outlook"></a>Outlook

- **Verbesserte Links in E-Mails:** Wenn Sie einen Link zu einer Datei einfügen, ersetzt der Dateiname die URL. Sie können die Berechtigungen so ändern, dass alle Empfänger Zugriff haben. [Weitere Informationen](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br />Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)

- **Erzählen Sie mit animierten GIFs über sich:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden künftig noch pfiffiger aussehen.

### <a name="powerpoint"></a>PowerPoint

- **Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen.  [Weitere Informationen](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a>Word

- **Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, das bei Benutzern zu Abstürzen geführt hat, wenn diese Toast-Nachrichten angesehen haben.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-may-04"></a>Version 2004: 04. Mai
*Version 2004 (Build 12730.20250)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Bessere Ergebnisse – im Handumdrehen:** wir haben die Suche aktualisiert, damit Sie intelligenter, schneller und zuverlässiger als je zuvor ist. [Weitere Informationen](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Benachrichtigung Über Vorfall für IT-Administratoren:** Globale Administratoren von Microsoft 365-Mandanten und Administratoren von Office-Apps werden über Outlook und O365 Exchange-Vorfällen benachrichtigt, die sich auf Ihre Benutzer auswirken – mit einer neuen Benachrichtigung im rechten Seitenbereich in Outlook für Windows. [Weitere Informationen](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="office-suite"></a>Office-Suite

- Dieses Update behebt ein Problem in Visual Basic for Applications in Microsoft Office, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthalten, von der Office-Anwendung beim Laden als fehlerhaft angesehen werden.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-april-29"></a>Version 2004: 29. April
*Version 2004 (Build 12730.20236)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Schützen von Daten in einer Gruppe:** Die beim Erstellen einer Gruppe ausgewählte Vertraulichkeitsbezeichnung wird auf Gruppen-E-Mails, Dokumente und Teamwebsites angewendet.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Behebt ein Problem, das dazu geführt hat, dass Outlook bei einigen Windows-Versionen abstürzt.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-april-25"></a>Version 2004: 25. April
*Version 2004 (Build 12730.20206)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, durch das Outlook nach einem Windows-Update beim Öffnen von lokal gespeicherten MSG- oder OFT-Dateien abstürzte.

### <a name="project"></a>Project

- Folgendes Problem wurde behoben: Wenn Sie Project in Verbindung mit Project Web App verwenden, das Kommas als Dezimaltrennzeichen festgelegt ist, und Sie versuchten, einer Abhängigkeit eine Verzögerung hinzuzufügen, schlägt die Methode "TaskDependencies Add" fehl.


### <a name="office-suite"></a>Office-Suite

- Mit diesem Fix wird ein Fehler behoben, der verhindert, dass Sie gleichzeitig den Zugriff einschränken und Dateien mit einem Kennwort schützen können.



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2004-april-21"></a>Version 2004: 21. April
*Version 2004 (Build 12730.20182)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Behebt ein Problem, bei dem die Breite des Ordnerbereichs unerwartet geändert wurde.

- Behebt ein Problem, bei dem sich das Programm beim Verlassen von Outlook aufhängte.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2004-april-15"></a>Version 2004: 15. April
*Version 2004 (Build 12730.20150)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Die Unterstützung für Facebook Connector endet:** Ab April 2020 werden von Excel keine externen Datenverbindungen mehr unterstützt, für die der Facebook-Connector eingesetzt wird.

### <a name="outlook"></a>Outlook

- **Neue Option zum Deaktivieren von Vorschlägen für @Erwähnungen beim Verfassen von E-Mails in Outlook:** Finden Sie die @Erwähnung-Auswahl eher lästig als sinnvoll? Wenn Sie das möchten, können Sie diese nun deaktivieren.

### <a name="powerpoint"></a>PowerPoint

- **Synchronisieren von Änderungen während der Präsentation:** Änderungen können jetzt synchronisiert werden, wenn sie vorgenommen werden, selbst wenn sich die Präsentation im Bildschirmpräsentationsmodus befindet.

### <a name="word"></a>Word

- **Fügen Sie einen privaten Kopie Anmerkungen hinzu:** Erstellen Sie handschriftliche Notizen nur für Sie, indem Sie eine private Kopie eines freigegebenen Dokuments erstellen. Wechseln Sie dazu einfach zu "Anzeige" > "Private Kopie erstellen".


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Access

- Probleme bei der Anpassung der Größe und der Aktualisierung von Tabellen im Aufgabenbereich wurden behoben.

- Ein Problem wurde behoben, bei dem internationale Versionen von Access in der Benutzeroberfläche englische Zeichenfolgen anzeigten.

### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem das Auswählen eines Zellbereichs auf einem Arbeitsblatt zur Auswahl nur einer einzelnen Zelle geführt hat.

- In Arbeitsmappen, die mit einer digitalen Signatur in Excel 2016 gespeichert wurden, kam es vor, dass die Signatur beim Öffnen in der aktuellen Version von Excel als ungültig interpretiert wurde.

- Ein Problem wurde behoben, bei dem Excel in manchen Fällen abstürzte, nachdem ein Blatt mit einer PivotTable kopiert wurde.

- Application.Evaluate (VBA) funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.

- Es wurde ein Leistungsproblem behoben, das Benutzer beim programmgesteuerten Bearbeiten eines großen Zellbereichs festgestellt haben.

- Ein Leistungsproblem beim Öffnen von CSV-Dateien in japanischen Umgebungen wurde behoben.

- Es wurde ein Problem behoben, bei dem das Einfügen einer benutzerdefinierten Diagrammvorlage als Standard dazu führte, dass sie als Säulendiagramm gespeichert wurde.

- Ein Problem wurde behoben, bei dem Datenbeschriftungen in Diagrammen leer angezeigt wurden, wenn die zugrundeliegenden Datenzellen keine Beschriftung aufwiesen.

- Es wurde ein Problem behoben, das dazu führen konnte, dass Excel nicht mehr reagierte, wenn die Größe eines Diagramms mit einigen x-Achsen-Bereichen reduziert wurde.

- Es wurde ein Problem behoben, bei dem eine Excel-Tabelle mit aktiviertem Z1S1-Zellbezug die freigegeben bzw. gemeinsam erstellt wurde, der aktive Zellbezug im Z1S1-Modus nicht angezeigt wurde, wenn man auf das Symbol für die Anwesenheitsanzeige zeigte.

- Diese Änderung betrifft Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen.

### <a name="outlook"></a>Outlook

- Diese Änderung ist gegen Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen gerichtet.

- Diese Änderung behebt ein Problem, bei dem die neuesten Änderungen an E-Mail-Entwürfen nicht aktualisiert wurden.

- Ein Problem wurde behoben, bei dem Sie mit der rechten Maustaste auf eine Datei klicken und "Senden an" nicht funktionieren würde.

- Ein Problem wurde behoben, durch das Stellvertretungen auf unterschiedlichen Computern unterschiedliche Ordnerhierarchien für freigegebene Postfächer angezeigt wurden.

- Ein Problem wurde behoben, durch das gelegentlich Kategorien in E-Mail-Nachrichten nicht mehr aufschienen.

- Es wurde ein Problem behoben, durch das einige Erinnerungen nicht ausgelöst wurden, wenn die Zeitzone auf einem Computer geändert wurde.

- Es wurde ein Problem behoben, das einen Absturz verursachte, wenn Benutzer versuchten, die Eigenschaften eines Organisationsformulars anzuzeigen.

- Es wurde ein Problem behoben, bei dem, wenn ein Benutzer einen angepassten Suchpfad für das Adressbuch hatte, der Namensauflösungsbereich von Outlook auf den angepassten Pfad beschränkt wurde, anstatt die Globale Adressliste (GAL) einzubeziehen.

- Es wurde ein Problem behoben, das bewirkt hat, dass die Schaltfläche "In der Cloud speichern" in den Anlagentools fehlte.

- Es wurde ein Problem behoben, das bewirkt hat, dass Benutzer beim Antworten auf eine verwaltete Nachricht mit digitaler Berechtigung aus einem Inspektor-Fenster keine Signatur hinzufügen konnten, wenn er nicht über die Berechtigung "Besitzer" für die Nachricht verfügte, auf die geantwortet wird.

- Es wurde ein Problem behoben, durch das Benutzer keine weiteren Anlagen von einem Webspeicherort zu einer zuvor erstellten Besprechung hinzufügen konnten.

- Es wurde ein Problem behoben, das dazu geführt hat, dass das „Datum der letzten Änderung“ in einer Datei beim Hinzufügen einer Anlage zu einer E-Mail oder beim Speichern einer Anlage aus einer E-Mail durch Ziehen und Ablegen (im Gegensatz zum Hinzufügen oder Speichern über ein Menü) aktualisiert wurde.

- Es wurde ein Problem behoben, bei dem durch das Drücken der EINGABETASTE im erweiterten Suchbereich keine Suche gestartet wurde. Stattdessen mussten Benutzer auf die Schaltfläche "Suchen" klicken.

- Es wurde ein Problem behoben, bei dem innerhalb eines Satzes von zurückgegebenen Suchergebnissen beim Sortieren der Ergebnisse nach Kategorien die Kategoriefarben nicht angezeigt wurden.

- Ein Problem wurde behoben, bei dem die Suche keine Informationen zu Benutzern anzeigte, wenn die Option "Benutzerfotos anzeigen, wenn verfügbar" deaktiviert war.


### <a name="powerpoint"></a>PowerPoint

- Diese Änderung behebt einen Fehler, der dazu führen kann, dass PowerPoint-Dateien mit Emojis beim Speichern fehlgeschlagen.

- Diese Änderung behebt ein Problem, bei dem beim Rendern eines Diagramms einer älteren Excel-Version, das als OLE-Objekt in PowerPoint oder Word eingebettet ist, u. U. nicht immer der Diagrammtitel angezeigt wurde.

- Es wurde ein Problem behoben, bei dem beim Kopieren von Text aus Excel in PowerPoint u. U. dessen Formatierung geändert wurde.

- Diese Änderung behebt ein Problem, bei dem das Suchen von Sonderzeichen mithilfe der Option "Nur ganze Wörter suchen" nicht immer erwartungsgemäß funktioniert hat.

### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.

- Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.

- Ein Problem wurde behoben, bei dem das VBA-Ereignis (Visual Basic Applications) "ProjectBeforeTaskChange" nicht ausgelöst wurde, wenn ein Benutzer auf die Schaltfläche "Deaktivieren" geklickt hat, die sich auf dem Menüband "Vorgänge" innerhalb der Planungsgruppierung befindet.

- Wenn Sie Vorgänger- oder Nachfolgerdetails in einer Ansicht vom Typ „Formular“ festlegen, wurden die Änderungen nicht immer durch das Ereignis „ProjectBeforeTaskChange Visual Basic Applications“ (VBA) erfasst. Wenn Sie beispielsweise eine Abhängigkeit gelöscht und im Formular auf „OK“ geklickt haben, wurde das Ereignis nicht ausgelöst. Dieses Verhalten wurde behoben.

- Es wurde ein Problem behoben, bei dem die neuesten Werte für die tatsächlichen Kosten der geleisteten Arbeit (ACWP) nicht angezeigt wurden, nachdem eine Änderung, z. B. eine Datumsänderung, vorgenommen wurde.

- Es wurde ein Problem behoben, bei dem das Öffnen eines Projekts über das Menü "Zuletzt verwendet" (MRU) die Projektdatei mit Lese- bzw. Schreibzugriff öffnete.

- Diese Änderung behebt das Problem, dass Sie eine manuelle Aufgabe mit einem Startdatum und einer Uhrzeit (aber ohne Dauer) erstellt haben, diese aber mit einer falschen Uhrzeit auf der Zeitachse angezeigt wurde.

- Es wurde ein Problem behoben, bei dem das Drucken einer Zeitleiste mithilfe eines Hijri-Kalenders dazu führte, dass ein Monat in der Druckansicht übersprungen oder dupliziert wurde.

- Diese Änderung richtet sich gegen ein Problem, bei dem die Arbeit im Team Planner mit GDI-Objekten zu einer Überzuweisung von GDI-Objekten und zu geringem Speicherplatz führen konnte.

- Ein Problem wurde behoben, durch das, wenn "CustomFieldValueListGetItem" ausgeführt wurde und keine Nachschlagetabelle für das benutzerdefinierte Feld vorhanden war, eine leere Nachschlagetabelle erstellt wurde, auch wenn dies nicht so sein sollte.

- Wenn Vorgänger/Nachfolger-Daten in einer Maske bearbeitet werden, wird ein zusätzliches ProjectBeforeTaskChangeevent ausgelöst.

- Es wurde ein Problem behoben, bei dem der Benutzer keine zeitgesteuerte Baseline-Arbeit eingeben konnte, wenn die Einstellung zum Schutz der aktuellen Arbeit aktiviert war.

### <a name="word"></a>Word

- Diese Änderung behebt ein Problem, bei dem wenn der Mauszeiger über einen Hinweis gehalten wurde, dessen Karte nicht hervorgehoben wurde.

- Diese Änderung behebt ein Problem, bei dem wenn mehrere Seiten aus dem Menü "Ansicht" ausgewählt wurden, der Kommentarbereich u. U. als leer angezeigt wurde.

- Es wurde ein Problem behoben, durch das die Funktion zum Posten von Kommentaren deaktiviert wurde.

- Diese Änderung behebt ein Problem, das dazu führte, dass der Text in gruppierten Formen beim Verwenden des Lasso-Auswahltools vorübergehend ausgeblendet wurde.

- Diese Änderung betrifft Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen.

- Diese Änderung behebt ein Problem, bei dem beim Rendern eines Diagramms einer älteren Excel-Version, das als OLE-Objekt in PowerPoint oder Word eingebettet ist, u. U. nicht immer der Diagrammtitel angezeigt wurde.

- Diese Änderung betrifft ein Problem, bei dem der Account Manager keine Nachrichten versendete, was zu einer Unterbrechung bei Anwendungen von Drittanbietern führte.

- Diese Änderung behebt ein Problem in der Zwei-Seiten-Ansicht. Beim Erstellen eines Kommentars wurde der Kommentaranker nicht immer in der Anzeige angezeigt.

- Ein Problem wurde behoben, bei dem das Eingeben oder Bearbeiten eines Kommentars und Verwenden von STRG+A dazu führte, dass statt nur innerhalb der Kommentarkarte Text im Zeichenbereich markiert wurde.

- Ein Problem wurde behoben, bei dem ein Absatz, dessen Formatvorlage ein Vorgänger einer mit einer Liste verknüpften Formatvorlage war, möglicherweise verloren ging.

- Diese Änderung behebt ein Problem, bei dem das Inhaltsverzeichnis mit Überschriftenformaten aktualisiert wurde, die im Dokument nicht vorhanden waren.

- Es wurde ein Problem behoben, bei dem die Ausrichtung von Wörtern in einem Dokument durcheinandergebracht wurde, wenn Benutzer nach dem Drucken mit Schnelldruck versuchten, den Text zu bearbeiten.

- Es wurde ein Problem beim Zusammenführen von zwei Dokumenten in ein Dokument behoben.

- Es wurde ein Problem behoben, bei dem in Word-Dokumenten gespeicherte digitale Signaturen beim Versand der Dokumente per E-Mail entfernt wurden.

- Es wurde ein Problem behoben, bei dem das Markieren von Überarbeitungen, die Formeln enthalten, beim Speichern der Datei zu einem Fehler führen konnte.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-april-14"></a>Version 2003: 14. April
*Version 2003 (Build 12624.20466)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt


[//]: # (FEATUREDETAILS CONTENT START NICHT ENTFERNEN)

- Korrekturen verschiedener Fehler und Leistungsprobleme.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-april-09"></a>Version 2003: 09. April
*Version 2003 (Build 12624.20442)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger! Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="outlook"></a>Outlook

- **M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger! Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="powerpoint"></a>PowerPoint

- **M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger! Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="word"></a>Word

- **M365 Premium-Inhaltsauswahl:** Gestalten Sie Ihre Dokumente lebendiger! Entdecken Sie 1000 kostenlose Bilder, Symbole und Aufkleber [Weitere Informationen](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)




[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-april-03"></a>Version 2003: 3. April
*Version 2003 (Build 12624.20410)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Verwendung der VBA-Anwendung. „Evaluate“ funktionierte in einigen Fällen für benutzerdefinierte Funktionen nicht.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, das dazu führte, dass Benutzer gelegentlich einen Absturz feststellten, wenn Sie den X-Knopf auf ihrer Maus verwendeten.

### <a name="project"></a>Project

- Wenn Vorgänger/Nachfolger-Daten in einer Maske bearbeitet werden, wird ein zusätzliches ProjectBeforeTaskChangeevent ausgelöst.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, das dazu führte, dass Benutzer gelegentlich einen Absturz feststellten, wenn Sie den X-Knopf auf ihrer Maus verwendeten.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-31"></a>Version 2003: 31. März
*Version 2003 (Build 12624.20382)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="access"></a>Access

- **Aufgabenbereich "Tabellen hinzufügen":** Der neue Aufgabenbereich "Tabellen hinzufügen" von Access ist endlich da! Mit dieser Funktion können Sie einfach auswählen/mehrfach auswählen, welche Tabellen sie in einem Abfragefenster hinzufügen/entfernen möchten, ohne zum Dialogfeld "Tabellen anzeigen" für Abfragen und für die Beziehungsansicht zu navigieren. Dazu gehört auch eine neue Registerkarte "Verknüpfungen", um verknüpfte Tabellen anzuzeigen, ein Suchfeld, um die aktuelle Liste zu filtern, "Drag & Drop"-Verhalten und mehr!


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="project"></a>Project

- <span style="display:inline !important;">Es wurde ein Problem behoben, bei dem der Benutzer keine zeitgesteuerte Baseline-Arbeit eingeben konnte, wenn die Einstellung zum Schutz der tatsächlichen Arbeit aktiviert ist.</span><br>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-25"></a>Version 2003: 25. März
*Version 2003 (Build 12624.20320)*

- Korrekturen verschiedener Fehler und Leistungsprobleme.

## <a name="version-2003-march-23"></a>Version 2003: 23. März
*Version 2003 (Build 12624.20296)*

- Korrekturen verschiedener Fehler und Leistungsprobleme.

## <a name="version-2003-march-21"></a>Version 2003: 21. März
*Version 2003 (Build 12624.20276)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **An Besprechungen teilnehmen, ohne den Posteingang zu verlassen:** Sie brauchen nicht zu Ihrem Kalender zu wechseln, um an Onlinebesprechungen teilzunehmen. Wenn der Kalender im Aufgabenbereich angeheftet ist, können Sie mit nur einem Klick an einer Besprechung teilnehmen.

- **Visuelle Aktualisierung des Kalenders:** Letztes Jahr haben wir die E-Mail-Erfahrung visuell aufgefrischt, und dieses Jahr ist der Kalender mit einem Facelifting an der Reihe! Die Aktualisierungen sind frisch, aber vertraut, so dass Sie als erfahrener Outlook-Benutzer sofort einsteigen und produktiver sein können.

### <a name="powerpoint"></a>PowerPoint

- **Aktualisieren von Folien während der Bildschirmpräsentation:** Aktualisieren Sie Folien, die von anderen Autoren während Ihrer Präsentation geändert wurden.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-16"></a>Version 2003: 16. März
*Version 2003 (Build 12624.20224)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.

### <a name="outlook"></a>Outlook

- **Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.

### <a name="powerpoint"></a>PowerPoint

- **Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.

### <a name="word"></a>Word

- **Perfekte Farbe auswählen:** Verwenden Sie hexadezimale Farbcodes, um genau die Farbe auszuwählen, die Sie für Ihre Schriftart, die Texthervorhebung und mehr benötigen.

### <a name="office-suite"></a>Office-Suite

- **Bereiche im Registerkartenformat:** Jetzt können Sie über die Registerkarten-Benutzeroberfläche auf der rechten Seite der App zwischen mehreren Bereichen wechseln. Die Benutzeroberfläche wird nur angezeigt, wenn Sie mehr als 2 Fenster geöffnet haben.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem externe Links beim Füllen nicht aktualisiert werden, wenn das Quellbuch geschlossen ist.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, das dazu führte, dass der Outlook-Prozess nach dem Beenden im Task-Manager fortbestand.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2003-march-10"></a>Version 2003: 10. März
*Version 2003 (Build 12624.20176)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)
### <a name="feature-updates"></a>Funktionsupdates
### <a name="excel"></a>Excel
- **Vertraulichkeitsbezeichnungen** : Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern. [Weitere Informationen](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="powerpoint"></a>PowerPoint
- **Vertraulichkeitsbezeichnungen** : Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern. [Weitere Informationen](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="word"></a>Word
- **Vertraulichkeitsbezeichnungen** : Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern. [Weitere Informationen](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)
</br>

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Ein kosmetisches Problem wurde behoben, bei dem die Schaltfläche "OK" im Dialogfeld "Datei\Optionen" abgeblendet angezeigt, die Funktionalität aber nicht beeinträchtigt wurde.

- Es wurde ein Problem behoben, das möglicherweise beim Umbenennen von Pivot-Tabellenmaßen aufgetreten ist.

- Ein Problem wurde behoben, bei dem der Text in einem Datenschnitt in der Druckvorschau nicht ordnungsgemäß skaliert wurde.

- Es wurde ein Leistungsproblem behoben, das möglicherweise bei der Verwendung eines VBA-Makros zum Löschen des Inhalts eines Bereichs aufgetreten ist.

- Es wurde ein Problem behoben, das zum Blinken der Benutzeroberfläche führte, wenn Benutzer ein Makro ausführten, das mit dem Menüband interagierte.

- Es wurde ein Problem behoben, bei dem CSV-Dateien falsch geladen wurden, wenn das erste Wort in der Datei TABLE lautete.

- Es wurde ein Problem behoben, bei dem es zu Abstürzen kommen konnte, wenn Benutzer zwischen zwei Arbeitsmappen mit unterschiedlichen Zoomstufen wechselten.

- Ein Problem wurde behoben, bei dem CUBEWERT-Funktionen manchmal ein falsches Ergebnis zurückgaben.

- Diese Änderung behebt einen Laufzeitfehler im Objektmodell und verhindert einen möglichen Absturz der App (Excel, Word), wenn Add-Ins nach Hostelementen in Dokumenten/Arbeitsblättern fragen, die Formen mit noSelect-Sperren enthalten.

- Behebt ein Problem, durch das Outlook beim Synchronisieren der Einstellungen abstürzte.



### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, bei dem das Erstellen einer Regel mit Outlook Web App auf dem Exchange-Server nicht beibehalten werden konnte und zu einem Konflikt geführt hat.

- Es wurde ein Problem behoben, durch das Outlook beim Synchronisieren der Einstellungen abstürzte.

- Es wurde ein Problem mit Outlook im dunklen Modus behoben, wird möglicherweise die Dropdownliste im Feld "Von:" nicht angezeigt.

- Es wurde ein Problem behoben, das dazu führte, dass Outlook in einigen Szenarien unerwartet Protokollausgaben erzeugte, selbst wenn die Protokollierung ausgeschaltet war.

- Es wurde ein Problem behoben, das dazu führte, dass Benutzer keine Nachrichten in öffentlichen Ordnern öffnen konnten, wenn Outlook über Nacht laufen gelassen wurde.

- Es wurde eine Racebedingung behoben, bei der die Schaltflächen "Zulassen" und "Verweigern" auf der Seite "Berechtigungen" während des Authentifizierungsworkflows beim Hinzufügen eines Google Mail-Kontos deaktiviert sind.

- Ein Problem wurde behoben, durch das Benutzer den Zugriff auf das Dialogfeld &quot;Frei/Gebucht-Optionen&quot; der Kalenderberechtigungen verloren.

- Es wurde ein Problem behoben, das zur Warnung &quot;Leider besteht ein Problem beim Öffnen dieses Elements&quot; führen kann, wenn Sie bestimmte Besprechungsserien-Instanzen öffnen, die aus einer anderen Zeitzone gesendet wurden.

- Es wurde ein Problem behoben, durch das Benutzer eine MSG-Datei möglicherweise nicht mehr öffnen können, nachdem die eine Anlage aus dieser Nachricht durch Ziehen und Ablegen verschoben haben.

- Ein Problem wurde behoben, bei dem der Dateiname nach dem Hochladen einer Dateianlage aus Outlook nach OneDrive möglicherweise geändert wird, wenn der Name der Anlage eine Klammer enthält.

- Es wurde ein Problem behoben, durch das Benutzer über den Datei-Explorer eine Datei nicht als Anlage zu einer E-Mail-Nachricht hinzufügen konnten, wenn diese Datei in einer anderen Anwendung geöffnet war.

- Es wurde ein Problem behoben, durch das Outlook beim Synchronisieren der Einstellungen abstürzte.

### <a name="powerpoint"></a>PowerPoint

- Ein Problem wurde behoben, bei dem die empfohlenen Miniaturansichten blinkten, wenn Sie mit der Maus auf die Miniaturansichten gingen. In einigen Fällen kann dies dazu führen, dass PowerPoint abstürzt.

- Ein kosmetisches Problem wurde behoben, bei dem die Schaltfläche "OK" im Dialogfeld "Datei\Optionen" abgeblendet angezeigt, die Funktionalität aber nicht beeinträchtigt wurde.

- Es wurde ein Problem behoben, das dazu führen konnte, dass ein Dokument, das ein Excel-Diagramm enthält, nicht in PowerPoint oder Word gespeichert werden konnte.



### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem "Vorgang Prozent abgeschlossen" fälschlicherweise in einen Wert kleiner als 100 % geändert wurde, nachdem der Vorgang als abgeschlossen gekennzeichnet wurde.

- Es wurde ein Problem behoben, bei dem das OnUndoOrRedo-Ereignis nicht ausgelöst wurde, ohne vorher die OpenUndoTransaction-Methode auszuführen.

- Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.

### <a name="visio"></a>Visio

- Im Shape-Infobereich wurden im Abschnitt "Shapedaten" inkonsistente Details zur Datei angezeigt, wenn diese in Visio Desktop angezeigt wurde. Dieses Problem wurde jetzt behoben.

- In Versionen vor 2016 importierte Bitmaps wurden aufgrund einiger Sicherheitsüberprüfungen nicht wiedergegeben. Dieses Problem wurde im Visio-Abonnement behoben.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem Kommentarkarten nicht immer hervorgehoben werden, wenn der Mauszeiger über die Kommentarkarte bewegt wird.

- Behebt ein Problem, das dazu geführt hat, dass beim Navigieren über eine Kommentarkarte mit der Tabulatortaste der Fokus auf dem Bearbeitungsfeld für den Kommentar nicht angezeigt wurde.

- Ein kosmetisches Problem wurde behoben, bei dem die Schaltfläche "OK" im Dialogfeld "Datei\Optionen" abgeblendet angezeigt, die Funktionalität aber nicht beeinträchtigt wurde.

- Während einer aktiven Sitzung zur gemeinsamen Dokumenterstellung kann das direkte Hinzufügen eines Bildes in eine Kommentarkarte dazu führen, dass ein Tag hinzugefügt wird. Das Problem wurde behoben.

- Das Einfügen eines Steuerelements (beispielsweise eines Textinhaltssteuerelements) in eine Gleichung und das anschließende Speichern und Öffnen der Datei führte zu einem Fehler aufgrund nicht lesbaren Inhalts.

- Ein Problem wurde behoben, aufgrund dessen das Speichern einer zuvor kennwortgeschützten Datei in einem Cloudspeicher nicht funktioniert hat.

- Es wurde ein Problem mit der compare-Funktion für Dokumente behoben, die für die Bearbeitung geschützt waren.




### <a name="office-suite"></a>Office-Suite

- Beim Verwenden der Metadateneigenschaften MultiChoice/Verweis/Verwaltet mit Word/Excel/PowerPoint-Dokumenten und dem Speichern in einer SharePoint-Dokumentbibliothek waren diese Eigenschaften bisher auf 255 Zeichen beschränkt. Wenn diese Eigenschaften 255 Zeichen überschritten, konnten solche Dokumente nicht gespeichert werden. Mit dieser Änderung wurde dieser Grenzwert auf 2048 Zeichen erhöht.

- Behebt ein Problem mit Word/Excel/PowerPoint, bei dem der User-Principal-Name (UPN) nicht mehr die Groß-/Kleinschreibung beachtet, was zu weniger Fehlern beim Arbeiten mit Dateien in SharePoint führt.

- Ein Problem wurde behoben, das dazu führte, dass beim Öffnen mehrerer Dokumente in Word/Excel/PowerPoint aus derselben SharePoint-Bibliothek lediglich das erste geöffnete Dokument auf Richtlinienkonformität gescannt wurde.


[//]: # (BUGDETAILS NICHT AM INHALTSENDE ENTFERNEN)

## <a name="version-2002-march-05"></a>Version 2002: 05. März
*Version 2002 (Build 12527.20278)*

- Korrekturen verschiedener Fehler und Leistungsprobleme.


## <a name="version-2002-march-04"></a>Version 2002: 04. März
*Version 2002 (Build 12527.20264)*


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme

### <a name="project"></a>Project
- Ein Problem wurde behoben, bei dem Datumsangaben von Sammelvorgängen nicht immer richtig berechnet wurden.


### <a name="office-suite"></a>Office-Suite
- Behebt ein Problem, das dazu geführt hat, dass beim Öffnen mehrerer Dokumente in Word/Excel/PowerPoint aus derselben SharePoint-Bibliothek lediglich das erste geöffnete Dokument auf Richtlinienkonformität gescannt wurde.



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSWENDE)

## <a name="version-2002-march-01"></a>Version 2002: 01. März
*Version 2002 (Build 12527.20242)*

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Behebt ein Problem, das bewirkt hatte, dass Anwendungen von Drittanbietern keine E-Mail-Nachrichten mehr senden konnten.



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2002-february-24"></a>Version 2002: 24. Februar
*Version 2002 (Build 12527.20194)*

- Korrekturen verschiedener Fehler und Leistungsprobleme.

## <a name="version-2002-february-22"></a>Version 2002: 22. Februar
*Version 2002 (Build 12527.20186)*

- Korrekturen verschiedener Fehler und Leistungsprobleme.

## <a name="version-2002-february-21"></a>Version 2002: 21. Februar
*Version 2002 (Build 12527.20174)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="access"></a>Zugriff

- **Seien Sie beim Arbeiten im Abfrage-Designer, in der SQL-Ansicht und im Fenster „Beziehungen“ produktiver:** Klicken Sie zum Öffnen, Gestalten, Vergrößern oder Verkleinern und Ausblenden mit der rechten Maustaste auf die betreffende Tabelle. Suchen und Ersetzen von Text in der SQL-Ansicht. Auswählen mehrerer Tabellen im Fenster „Beziehungen“.

### <a name="outlook"></a>Outlook

- **Neue Benutzeroberfläche für WLAN-Netzwerke mit Anmeldung:** Sind Sie schon einmal einem WLAN-Netzwerk beigetreten, mit dem Sie sich anmelden mussten? Outlook erkennt dies jetzt und hilft Ihnen, eine Verbindung zu herstellen.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- <div style="box-sizing:border-box;">Ein Problem wurde behoben, bei dem CUBEWERT-Funktionen manchmal ein falsches Ergebnis zurückgaben.&nbsp;<span style="display:inline !important;"></span><br>


### <a name="outlook"></a>Outlook

- Behebt ein Problem, das dazu führte, dass Kommas im Ortsfeld einer Besprechung in Semikolons umgewandelt wurden.


- Behebt ein Problem, das zu einem Absturz führen könnte, wenn dasselbe Element in mehreren Fenstern angezeigt wird.


- Behebt ein Problem, das dazu führte, dass Outlook unerwartet alle E-Mails synchronisierte, selbst wenn der Synchronisierungsschieberegler auf eine kleinere Einstellung eingestellt ist.&nbsp;


- Behebt ein Problem, das dazu führte, dass für Benutzer mit dem schwarzen Design die Dropdownliste &quot;Von&quot; als weißer Text auf weißem Hintergrund angezeigt wurde.


- <span style="display:inline !important;">Diese Änderung stellt die Fähigkeit wieder her, mehrzeilige Betreffzeilen im Nachrichtenkopf anzuzeigen.</span><br>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-february-18"></a>Version 2002: 18. Februar
*Version 2002 (Build 12527.20138)*

## <a name="version-2002-february-11"></a>Version 2002: 11. Februar
*Version 2002 (Build 12527.20092)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Ziehen Sie E-Mails in eine Gruppe, die Sie besitzen:** Verschieben und Kopieren von Nachrichten und Unterhaltungen, indem Sie diese aus Ihrem Posteingang ziehen. Die von ihnen gezogenen Nachrichten werden für alle Gruppenmitglieder freigegeben.

### <a name="word"></a>Word

- **Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.

### <a name="office-suite"></a>Office-Suite

- **Übersichtlichere Statusleistensymbole:** Statusleistensymbole sind jetzt einfacher zu sehen.


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Zugriff

- Access-Vorlagen sollten nicht länger dazu führen, dass Anhangsspalten in einer Datenbank fehlschlagen. Nachdem Sie eine Vorlage instanziiert haben, sollten Sie nun in der Lage sein, Ihrer Datenbank ein Anhangsfeld hinzuzufügen.

- Dieses Update behebt ein Problem bei der Verwendung von ADODB. Das Recorder-Objekt im VB-Code meldet möglicherweise einen Fehler falsch.

- Dieses Update behebt ein Problem, das dazu führen kann, dass Microsoft Access eine Identitätsspalte in einer verknüpften SQL-Server-Tabelle nicht identifiziert, was dazu führen kann, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.


### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem Kommentarbefehle im Kontextmenü nicht angezeigt wurden.


- Es wurde ein Problem behoben, durch das bei einigen Nutzern Abstürze auftraten, wenn Text in Spalten mit Zellen mit einem übergelaufenem Array konvertiert wurde.


- Ein Problem wurde behoben, das dazu geführt hatte, dass Excel bei Verschieben von Text in Spalten mit dynamischen Pfeilern abgestürzt ist.

### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, das dazu geführt hatte, dass beim Durchblättern des Kalanders in der Monatsansicht die vorangegangenen Kalenderereignisse nicht angezeigt wurden.

- Ordner, die unter "Favoriten" im linken Navigationsbereich gespeichert sind, können zeitweise verschwinden.


- Es wurde ein Problem behoben, bei dem beim Angeben einer ungültigen Absenderadresse ein Absturz verursacht wurde.


- Es wurde ein Problem behoben, durch das die Option zum Deaktivieren der Hervorhebung markierter Elemente in einigen Szenarien nicht berücksichtigt wurde.

- Es wurde ein Problem behoben, bei dem es durch das Abbrechen der Kontoeinrichtung einen Absturz gab.


- Problem behoben, bei dem für auf Grundlage einer Aufbewahrungsrichtlinie ablaufende E-Mails zwei Beschriftungen angezeigt wurden. Eine mit der Aussage, dass die E-Mail in einem Tag, die andere, dass die E-Mail in zwei Tagen abläuft.


- Es wurde ein Problem behoben, bei dem beim Anzeigen von mehr als 30 Kalendern in einer Citrix-Umgebung ein Absturz verursacht wurde.


### <a name="powerpoint"></a>PowerPoint

- Ein Problem wurde behoben, bei dem Freihandelemente in einer PowerPoint-Freihandanimation nicht vollständig gerendert wurde oder übersprungen wurde.

- Ein Problem wurde behoben, das dazu geführt hatte, dass PowerPoint Nach dem Schließen einer Datei diese nicht sofort aus der Sammlung von Präsentationen entfernt hat, wenn Ereignisverarbeiter ausgeführt werden. Dadurch war die Zahl der vom Objektmodell gemeldeten, geöffneten Präsentationen falsch und das Herunterfahren von PowerPoint wurde verhindert.


- Ein Problem mit dem Textmarker wurde behoben: Weißer Text mit dunkleren Textmarkerfarben wurde Schwarz mit Graustufen gedruckt.


### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem 100% Aufgaben vom Typ „feste Dauer“ fälschlicherweise zu weniger als 100% erledigt wurden.


### <a name="word"></a>Word

- Beim Aktualisieren eines Inhaltsverzeichnisses bzw. dem Blättern durch dieses wird manchmal möglicherweise ein grauer Bereich auf dem Dokument angezeigt.


- Es wurde ein Problem mit der Verwendung von „Durchsuchen“ zum Speichern einer Datei behoben, das nicht funktioniert hat, wenn ein Kommentar geschrieben, jedoch nicht gepostet worden war und der Benutzer versucht hatte, die Datei zu speichern.


- Ein Problem wurde behoben, das dazu geführt hatte, dass beim Hin- und Herwechseln zwischen Kommentar-Karten manchmal der anfänglich ausgewählte Kommentar mit einer Auswahlhervorhebung angezeigt wurde.


- Es wurde ein Problem behoben, bei dem die kursive Formatierung verloren ging, nachdem ein Kommentar bearbeitet, der Text kursiv geschrieben und anschließend veröffentlicht wurde.


- Problem behoben, bei dem ein Kommentarhinweis im Lesemodus mit Inverser Seitenfarbe nicht sichtbar war.


- Ein Problem wurde behoben, bei dem die Entwurfsversion eines Stammkommentars bei der gemeinsamen Dokumenterstellung zeitweise nicht beibehalten wurde.


- Wenn „SlideTrack“ aktiviert und der Bereich „Kommentare“ geschlossen ist, kann der Bereich „Kommentare“ mit STRG+ALT+M möglicherweise nicht geöffnet werden.


- Es wurde ein Problem behoben, das dazu geführt hatte, dass beim Hinzufügen von @mention in einer Tabelle die Fehlermeldung „Eine Tabelle in diesem Dokument ist beschädigt“ generiert wurde.


- Problem behoben, bei dem Kommentarbefehle (Kommentar bearbeiten, auf Kommentar antworten, Kommentar löschen, Kommentar auflösen) nicht im Kontextmenü von Kommentaren angezeigt wurden.


### <a name="office-suite"></a>Office-Suite

- Behebt ein Problem, das dazu geführt hat, dass Korrekturhilfe-Paket Norwegen Nynorsk (nn-no) nicht ordnungsgemäß installiert wurde.


- Diese Änderung behebt gemeldete Probleme mit Grafikadaptern, die die integrierte Intel-GPU nutzen.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)


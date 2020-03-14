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
ms.openlocfilehash: a62e8d030c01685f6ab688666bccd15a7cf87cea
ms.sourcegitcommit: 802bdce1e86a4da5ca91a537f208be94417d622e
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/13/2020
ms.locfileid: "42637423"
---
# <a name="release-notes-for-office-insiders"></a>Anmerkungen zu dieser Version für Office-Insider

Dieser Artikel enthält Versionshinweise zu Insider-Builds von Word, Excel, PowerPoint, Outlook, Access und Project für Windows Desktop. Jede Woche werden interessante neue Features, wichtige Fehlerbehebungen und alle wichtigen Probleme, über die Sie informiert werden sollen, hervorgehoben. Beachten Sie, dass das Rollout von Funktionen (und manchmal auch Fixes) für Insider häufig über einen längeren Zeitraum erfolgt. Auf diese Weise können wir sicherstellen, dass alles reibungslos funktioniert, bevor das Feature für ein breiteres Publikum bereitgestellt wird. Wenn Sie also unten nichts beschrieben sehen, machen Sie sich keine Sorgen, Sie werden es eventuell irgendwann erhalten.  

> [!NOTE]
> - Versionshinweise werden wöchentlich veröffentlicht und können eine Kompilierung mehrerer Builds sein.
> - Das Veröffentlichungsdatum der Versionshinweise stimmt möglicherweise nicht mit dem tatsächlichen Veröffentlichungsdatum des Builds überein.
> - Microsoft Teams für vorhandene Installationen von Office 365 ProPlus – ab Ende Juni wird Microsoft Teams beim Aktualisieren dieser Installationen in bestehende Installationen von Office 365 ProPlus (und Office 365 Business) einbezogen. Ab welchem Datum Microsoft Teams hinzugefügt wird, hängt davon ab, welchen Updatekanal Sie verwenden. Weitere Informationen hierzu finden Sie unter [Bereitstellen von Microsoft Teams mit Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install).

[//]: # (NICHT ENTFERNEN)

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

- **Benachrichtigung Über Vorfall für IT-Administratoren:** Globale Administratoren von Microsoft 365-Mandanten und Administratoren von Office-Apps werden über Outlook und O365 Exchange-Vorfällen benachrichtigt, die sich auf Ihre Benutzer auswirken – mit einer neuen Benachrichtigung im rechten Seitenbereich in Outlook für Windows.

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

## <a name="version-2002-january-31"></a>Version 2002: 31. Januar
*Version 2002 (Build 12513.20010)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Schnell lesen und antworten:** Antworten Sie auf Kommentare und Erwähnungen direkt aus dem E-Mail-Bereich, ohne die Arbeitsmappe zu öffnen.

- **Datenprofilerstellung im Abfrage-Editor:** Sie können die Daten in Ihren Spalten auf einen Blick analysieren, Fehler- und Leerwerte identifizieren, Verteilungshistogramme anzeigen und vieles mehr.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Problem behoben, bei dem für auf Grundlage einer Aufbewahrungsrichtlinie ablaufende E-Mails zwei Beschriftungen angezeigt wurden. Eine mit der Aussage, dass die E-Mail in einem Tag, die andere, dass die E-Mail in zwei Tagen abläuft.

### <a name="word"></a>Word

- Problem behoben, bei dem ein Kommentarhinweis bei &quot;inverser&quot; Seitenfarbe nicht sichtbar war.

- Problem behoben, bei dem kursive Formatierung nach dem Bearbeiten eines Kommentars, kursiver Formatierung des Texts und anschließendem Posten verloren wurde.

- Problem behoben, bei dem Kommentarbefehle (Kommentar bearbeiten, auf Kommentar antworten, Kommentar löschen, Kommentar auflösen) nicht im Kontextmenü von Kommentaren angezeigt wurden.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-january-17"></a>Version 2002: 17. Januar
*Version 2002 (Build 12508.20000)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="word"></a>Word

- **Benachrichtigungs-E-Mails für Erwähnungen und Kommentare enthalten jetzt eine Vorschau:** E-Mail-Benachrichtigungen für Erwähnungen und Kommentare enthalten jetzt eine Vorschau des Kommentartexts und des Kontexts, auf den verwiesen wird.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- In einigen Fällen wurden von der Barrierefreiheitsprüfung keine Empfehlungen für Formen angezeigt.

### <a name="outlook"></a>Outlook

- Ordner, die unter "Favoriten" im linken Navigationsbereich gespeichert sind, können zeitweise verschwinden.

### <a name="powerpoint"></a>PowerPoint

- Ein Problem wurde behoben, bei dem Freihandelemente in einer PowerPoint-Freihandanimation nicht vollständig gerendert wurde oder übersprungen wurde.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2001-january-10"></a>Version 2001: 10. Januar
*Version 2001 (Build 12430.20000)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel
- **Speichern von Shapes als Bildern:** mit nur wenigen Mausklicks können Sie eine Form, ein Symbol oder ein anderes Objekt als Bilddatei speichern, um Sie an anderer Stelle wiederzuverwenden. [Weitere Informationen](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

### <a name="outlook"></a>Outlook
- **Der Benutzer kann nun Objekte in Word/Excel/Outlook als Bild für Windows speichern.:** Diese Möglichkeit ist bereits aus PowerPoint bekannt, sodass Benutzer nun Objekte in Word, Excel und Outlook als Bild speichern können. Zu den Objekten gehören Formen, Symbole, Bilder und vieles mehr! Sie können über das Kontextmenü darauf zugreifen.

### <a name="word"></a>Word
- **Wählen Sie auf einfache Weise Freihand in Word aus, indem Sie eine Form um das Freihandobjekt zeichnen.:** das Lassotool auf der Registerkarte „Zeichnen“ hilft Ihnen beim Auswählen von frei handgezeichneten Objekten. Wählen Sie einzelne Striche oder ganze Wörter aus. Das ist praktisch, wenn Sie eine viele Freihandobjekte haben und nur mit einigen davon arbeiten möchten. [Weitere Informationen](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Speichern von Shapes als Bildern:** mit nur wenigen Mausklicks können Sie eine Form, ein Symbol oder ein anderes Objekt als Bilddatei speichern, um Sie an anderer Stelle wiederzuverwenden. [Weitere Informationen](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="onenote"></a>OneNote
- Seitenregisterkarten werden bei einer Auflösung von 100% möglicherweise zu klein und zu nah aneinander angezeigt.

### <a name="word"></a>Word
- Bei einer großen Gruppe von Kommentaren kann das Löschen eines Kommentars am Ende der Kommentarliste dazu führen, dass der Bereich ganz nach oben gescrollt wird.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2001-january-03"></a>Version 2001: 03. Januar
*Version 2001 (Build 12425.20000)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme

### <a name="excel"></a>Excel
- Einige Rahmenlinien werden auf Papier im Format A4 möglicherweise nicht wie erwartet gedruckt.
- Das Einfügen eines Bildes in die Kopf-/Fußzeile eines Diagrammobjekts auf einem Blatt mit VBA kann zu einem Fehler führen.
- Beim Formatieren einer Diagrammachse ist der Abstand zwischen den Beschriftungen auf 255 Zeichen begrenzt.
- Ein Problem wurde behoben, bei dem beim Versuch, eine XML-Abfrage zu aktualisieren, deren URL zur Datenquelle abgeschnitten wurde, ein Fehler auftrat.
- In der Arbeitsmappenstatistik wird eine Makroanzahl aus allen geöffneten Arbeitsmappen angezeigt, einschließlich der persönlichen Makroarbeitsmappe.

### <a name="outlook"></a>Outlook
- Das Wechseln von Ordnern kann zu einem kurzen weißen "Blitz" in der E-Mail-Liste/E-Mail-Vorschau führen. Dieses Verhalten war im dunklen Modus ausgeprägter.

### <a name="powerpoint"></a>PowerPoint
- Ein Problem mit dem Objektmodell wurde behoben, bei dem das Aufrufen der Methode "Shape.Paste" dazu führte, dass die eingefügte Form den Fokus erhielt.&nbsp;
- Verbessertes Kopieren-Einfügen-Szenario:&nbsp; Das programmgesteuerte Kopieren einer Form aus einer PowerPoint-Folie und das Einfügen dieser Form in eine andere Folie in einer Schleife konnte mit einem Ausnahmefehler fehlschlagen.&nbsp;
- Animationen in den Abschnittsüberschriften von Folien wurden nach dem Reduzieren und Erweitern von Abschnittsüberschriften nicht korrekt gerendert.

### <a name="project"></a>Project
- Ein Problem wurde behoben, bei dem der Textumbruch in der Task- und Ressourcennutzungsansicht nicht funktionierte.
- Ein Problem wurde behoben, bei dem der Kostenwert bei Aufgaben möglicherweise nicht korrekt ist, wenn eine Ressource mehrere Kostensätze aufweist.

### <a name="word"></a>Word
- Das Einfügen eines Steuerelements (z. B. eines Textinhaltssteuerelements) in eine Gleichung und das anschließende Speichern und Öffnen der Datei führte zu einem Fehler aufgrund nicht lesbaren Inhalts.
- Bei der gemeinsamen Dokumenterstellung wird ein Kommentar, der mit Word Online hinzugefügt wurde, auf dem Word-Desktop möglicherweise nicht angezeigt.

### <a name="office-suite"></a>Office-Suite
- Die Anzeige eines falschen Ablaufdatums der gültigen Lizenz beim Versuch, eine Einzellizenz zu ändern, wurde entfernt.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2001-december-13"></a>Version 2001: 13. Dezember
*Version 2001 (Build 12410.20000)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Ziehen Sie E-Mails in eine Gruppe, die Sie besitzen:** Verschieben und Kopieren von Nachrichten und Unterhaltungen, indem Sie diese aus Ihrem Posteingang ziehen. Die von ihnen gezogenen Nachrichten werden für alle Gruppenmitglieder freigegeben.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Access
- Das Ausführen einer Verbundabfrage, die auf verknüpfte ODBC-Tabellen verweist und eine ORDER BY-Klausel enthält, stürzt den 64-Bit-Zugriff ab.
- Das Summieren von Daten aus Verbundsabfragen in Access (O365) kann zu einer Verkürzung der dezimalen Daten führen.
- COM-Schnittstellen für ACE werden nicht für den Einsatz außerhalb von Office-Anwendungen freigegeben.

### <a name="excel"></a>Excel
- Das Einfügen eines 3D-Modells (animiert oder statisch) und der Versuch, als Bild zu speichern, funktioniert nicht.
- Die Kurztaste (Alt + Strg + 7/8), um Feedback aus dem Backstage-Bereich zu starten, steht im Konflikt mit QWERTZ-Tastaturen (AltGr + 7/8). Auswirkung: Benutzer sind möglicherweise nicht in der Lage, einige Zeichen wie: '\' zu verwenden.

### <a name="outlook"></a>Outlook
- Behebt ein Problem, bei dem E-Mails an die für den Empfänger falsche Adresse gesendet wurden.
- Behebt ein Problem, das dazu führte, dass Outlook-Benutzern mit &quot;Lesezugriff&quot; auf ein Postfach fälschlicherweise erlaubte, den gelesenen/ungelesenen Status einer Nachricht zu ändern.
- Der Widerruf des Sicherheitszertifikats auf der Website ist für den Produkt Support nicht reproduzierbar. Die Protokollierung muss hinzugefügt werden, um die Ursache für das Problem zu beheben.
- Behebt ein Problem, bei dem Benutzer Synchronisationsfehler festgestellt haben.

### <a name="powerpoint"></a>PowerPoint
- Das Einfügen eines 3D-Modells (animiert oder statisch) und der Versuch, als Bild zu speichern, funktioniert nicht.

### <a name="project"></a>Project
- Die Aufgabenarbeit wird im Summenrollup für manuell geplante Unteraufgaben nicht berechnet.
- Projekt-VBA-Code, der von einer Multifunktionsleiste aufgerufen wird, funktioniert möglicherweise nicht, wenn versucht wird, serverbasierte Projekte zu speichern.
- Wenn Project nicht bereits ausgeführt wird, zeigt das Öffnen von Projektdateien aus einer SharePoint-Dokumentbibliothek einen Fehler an und die Datei wird nicht geöffnet.

### <a name="word"></a>Word
- Das Speichern vorhandener Dateien funktioniert möglicherweise nicht.
- Die Verwendung der Pfeiltasten im Fenster des Editors für Rechtschreibung und Grammatik kann zu intermittierendem Flackern führen.
- Bei der Behebung einer Nachverfolgung können zugehörige Kommentare nicht in Punktkommentare umgewandelt werden.
- Das Einfügen eines 3D-Modells (animiert oder statisch) und der Versuch, als Bild zu speichern, funktioniert nicht.

### <a name="office-suite"></a>Office-Suite
- Es wurde ein Problem behoben, bei dem Office-Update-Nachrichten in einer anderen Sprache als erwartet angezeigt wurden. In Zukunft entsprechen Office-Update-Nachrichten ordnungsgemäß der Windows-Anzeigesprache.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1912-december-06"></a>Version 1912: 6. Dezember
*Version 1912 (Build 12325.20012)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Erweiterte Gruppen-E-Mail-Einstellungen:** Diese Funktion hilft Gruppenbenutzern dabei, die E-Mails oder Ereignisse anzupassen, die sie in ihrem Posteingang empfangen/verfolgen möchten.

- **Benennungsrichtlinie für Gruppen:** Mit einer Benennungsrichtlinie für Gruppen kann der IT-Administrator die Namen von Gruppen, die von Benutzern in der Organisation erstellt wurden, standardisieren und verwalten. Der Administrator kann festlegen, dass dem Namen einer Gruppe beim Erstellen ein bestimmtes Präfixes und ein Suffix hinzugefügt werden, und er kann bestimmte Wörter blockieren. Auf diese Weise kann die Verwendung von unpassenden Wörtern in Gruppennamen minimiert und die Darstellung von Gruppen in Ihrem Verzeichnis verwaltet werden. Die Benennungsrichtlinie hilft außerdem Organisationen, die Teamwebsites bereitstellen, um diese je nach Abteilung zu kategorisieren.

### <a name="office-suite"></a>Office-Suite

- **Bereiche im Registerkartenformat:** Jetzt können Sie über die Registerkarten-Benutzeroberfläche auf der rechten Seite der App zwischen mehreren Bereichen wechseln. Die Benutzeroberfläche wird nur angezeigt, wenn Sie mehr als 2 Fenster geöffnet haben.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel
- Beim Speichern von Änderungen bei der Verwendung einiger nicht englischer Zeichengruppen tritt möglicherweise ein Fehler auf.
- Beim Zugriff auf einen verborgenen benannten Bereich kann ein Fehler auftreten.
- Das Deaktivieren der Beschleunigung von Hardware-Grafiken mit 4K könnte die Wiedergabe von Zellen verzögern.
- Das Löschen einer langen Formel, die eine Zellbegrenzung überlappt, wird möglicherweise weiterhin über die Zellbegrenzung angezeigt.
- Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.
- Dropdownmenü „Rand“ wird möglicherweise nicht ordnungsgemäß gerendert.

### <a name="onenote"></a>OneNote
- Möglicherweise wird OneNote nicht über das Outlook-Add-in „Besprechungsnotizen“ geöffnet.

### <a name="outlook"></a>Outlook
- Bei Aufbewahrungsrichtlinien für Bezeichnungen kann der Aufbewahrungszeitraum in Klammern anzeigt sein.
- Auf Visitenkarten mit dem japanischem Sprachpaket können Leerzeichen angezeigt werden.
- Bilder, die in Outlook-E-Mail-Nachrichten Inline eingefügt wurden, können manchmal geändert werden.

### <a name="powerpoint"></a>PowerPoint
- Wenn ein Benutzer zwei (oder mehr) verschiedene Videos auf einer Folie in einer Cloud-Datei hat, werden die Videobilder korrekt wiedergegeben, aber wenn der Benutzer zum Abspielen auf jedes einzelne klickt, ist der Videoinhalt derselbe.
- In einigen Fällen geht Scrollen bei Touchscreen-Geräten nicht.
- Dropdownmenü „Rand“ wird möglicherweise nicht ordnungsgemäß gerendert.
- Safelinks aus einer Office-Anwendung zu einer anderen können die verknüpfte Anwendung nicht starten.

### <a name="project"></a>Project
- Project stürzt ab, wenn Sie die Funktion „Projekte vergleichen“ verwendet wird.
- Wenn Sie sich im dunklen Modus befinden, können Sie die Tabelle nicht lesen, wenn Sie zu einem Vorgang mit einer überlasteten Ressource im Vorgangsinspektor wechseln.
- Das Festlegen von Aufwand für Vorgänge, die keine Aufgaben haben, wird auf 1 Tag abgerundet.

### <a name="word"></a>Word
- Das Speichern einer Datei nach einem Seriendruck funktioniert unter bestimmten Bedingungen möglicherweise nicht.
- Im Organizer für Bausteine könnte eine ungültige Warnung angezeigt werden: &quot;Sie haben modifizierte Formen, Bausteine&quot;.
- Der Kommentarbereich wird manchmal beim Kopieren/Einfügen neu geladen.
- Kommentare werden manchmal nicht in der richtigen Reihenfolge eingefügt.
- Das Anwenden einer Vorlage, die aus einer mehrstufigen Liste mit benutzerdefinierten Formatvorlagen besteht, auf bestehende Dokumente kann unter bestimmten Bedingungen die Formatvorlage nicht beibehalten.
- Wenn Sie die Größe eines geteilten Bildschirms ändern, wird ggf. ein weiterer geteilter Bildschirm öffnen.
- Dropdownmenü „Rand“ wird möglicherweise nicht ordnungsgemäß gerendert.
- Wenn ein Benutzer auf einer Kommentarkarte erwähnt wird, wird möglicherweise JSON angezeigt.
- Safelinks aus einer Office-Anwendung zu einer anderen können die verknüpfte Anwendung nicht starten.

### <a name="office-suite"></a>Office-Suite
- Bei Produkten mit einer Formatierung für Japan wird der Nachname des Benutzerkontos in der falschen Reihenfolge angezeigt.
- Beim Bewegen des Mauszeigers über Kommentare wird möglicherweise eine TextBox-Kontur um den Kommentar angezeigt.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1912-november-15"></a>Version 1912: 15. November
*Version 1912 (Build 12307.20000)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="insights-services"></a>Insights-Services
- **Abfragen in natürlicher Sprache in "Excel-Ideen":** Die neue Funktion von "Excel-Ideen", mit der Sie eine Frage zu Ihren Daten in natürlicher Sprache stellen können.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel
- Die Funktion "Text in Spalte" könnte bei einigen Lokalisierungen nicht funktionieren.
- Beim Bearbeiten von dynamischen Arrayformeln innerhalb einer Zelle könnte Text außerhalb der Begrenzung der Zelle ausgerichtet werden.

### <a name="outlook"></a>Outlook
- Es wurde die Möglichkeit des Erzwingens der S/MIME-Konfiguration über eine Gruppenrichtlinie hinzugefügt.
- Eingebettete Bilder könnten kleiner als erwartet erscheinen.

### <a name="powerpoint"></a>PowerPoint
- Der Cursor verschwindet möglicherweise nach dem Verschieben des Fokus von einem Textinhalt.

### <a name="project"></a>Project
- Es könnte ein Fehler hinsichtlich der Lizenzierung auftreten.
- Die Schaltfläche "Heute" in der Datumsauswahl könnte ein falsches Datum festlegen.

### <a name="word"></a>Word
- Bei einem Rechtsklick könnte manchmal nicht das ganze Wort markiert werden.
- Nach der Konvertierung in ein vorgeschlagenes Format bleibt der Cursor u. U. in einem Objekt aktiv.
- In einigen Szenarien werden Bilder in Nachrichten u. U. nicht ordnungsgemäß skaliert.
- Einige Designs erschweren es möglicherweise, den ausgewählten Kommentar zu erkennen.
- Beim Auswählen eines Kommentarhinweises im Bereich "Ansicht wechseln" sollte jetzt der moderne Kommentarbereich angezeigt werden, wenn dieser verborgen war.

### <a name="office-suite"></a>Office-Suite
- Das Antworten auf einen Kommentar könnte dazu führen, dass das Textfeld vertikal über den Rand des Bereichs hinaus erweitert wird.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1912-november-08"></a>Version 1912: 8. November
*Version 1912 (Build 12231.20000)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="user-lifecycle"></a>Lebenszyklus des Benutzers:
- **Verbesserungen bei der AFO-Aktivierung:** Aktualisierungen der Bildschirme, die den Kunden beim Aktivieren der im Lieferumfang Ihres neuen PCs enthaltenen Office-Version angezeigt werden.

### <a name="word"></a>Word
- **Neue und verbesserte Online-Videofunktionen in Word:** Neue und sicherere Onlinevideoerfahrung, die Ihnen beim Einfügen neuer Videos und beim Abspielen vorhandener Videos in Word hilft.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook
- Zeitweiliger Absturz bei ordnerübergreifenden Inhalten.

### <a name="office-suite"></a>Office-Suite
- Wenn Sie ein Diagramm aus Excel in PowerPoint einfügen, kann sich die Größe des Diagramms verringern.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1911-november-01"></a>Version 1911: 1. November
*Version 1911 (Build 12228.20020)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel
- **Nehmen Sie den Kontext mit ihren SVG-Objekten mit!:** Sie können jetzt den Text in Karten, Diagrammen und anderen SVG-Vektoren beibehalten, wenn Sie diese Objekte in Office konvertieren.

- **Sehen Sie sich die Stiftoptionen an, wenn Sie Ihren Surface Pen aufnehmen:** Wenn Sie Ihren Surface Pen in Word, Excel oder PowerPoint in die Hand nehmen, wird die Registerkarte „Zeichnen“ aktiviert, damit Sie ganz einfach die Stiftfarben auswählen können.

### <a name="powerpoint"></a>PowerPoint
- **Nehmen Sie den Kontext mit ihren SVG-Objekten mit!:** Sie können jetzt den Text in Karten, Diagrammen und anderen SVG-Vektoren beibehalten, wenn Sie diese Objekte in Office konvertieren.

- **Sehen Sie sich die Stiftoptionen an, wenn Sie Ihren Surface Pen aufnehmen:** Wenn Sie Ihren Surface Pen in Word, Excel oder PowerPoint in die Hand nehmen, wird die Registerkarte „Zeichnen“ aktiviert, damit Sie ganz einfach die Stiftfarben auswählen können.

### <a name="visio"></a>Visio
- **Erstellen von ansprechenden Visio-Diagrammen in Excel:** Visualisieren Sie Ihre Daten schnell und einfach in ansprechenden Visio-Diagrammen in Excel. [Weitere Informationen](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c).

### <a name="word"></a>Word
- **Sehen Sie sich die Stiftoptionen an, wenn Sie Ihren Surface Pen aufnehmen:** Wenn Sie Ihren Surface Pen in Word, Excel oder PowerPoint in die Hand nehmen, wird die Registerkarte „Zeichnen“ aktiviert, damit Sie ganz einfach die Stiftfarben auswählen können.

- **Verbesserungen bei der gemeinsamen Dokumenterstellung:** Die gemeinsame Dokumenterstellung wurde verbessert, indem Inhaltsänderungen den anderen Benutzern nun nahezu immer in Echtzeit angezeigt werden.

- **Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel
- Es wurde ein Problem behoben, durch das die Bearbeitung einer geschützten Datei von einer nicht vertrauenswürdigen Netzwerkfreigabe zum Absturz von Excel geführt haben könnte.
- Es wurde ein Problem behoben, bei dem das Löschen von Blättern mit Sparklines, die auf Daten auf einem anderen Arbeitsblatt verweisen, dazu führen könnte, dass die Datei beim erneuten Öffnen als fehlerhaft identifiziert wird.
- Es wurde ein Problem behoben, bei dem Sie beim Konvertieren von Berichtsfiltern zusammen mit der restlichen PivotTable für Abfragen an tabellarische SQL-Server möglicherweise falsche Ergebnisse erhalten.
- Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Absturz führen.
- Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Absturz führen.

### <a name="outlook"></a>Outlook
- Bei einer weitergeleiteten e-Mail fehlen möglicherweise eingebettete Bilder.
- Das Tool „Raumsuche“ zeigt bei verfügbaren Räumen möglicherweise &quot;Keine&quot; an.
- Benutzer sind möglicherweise nicht in der Lage, Outlook-Profile mit strikter Mandantenbeschränkung zu erstellen.

### <a name="powerpoint"></a>PowerPoint
- Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Absturz führen.

### <a name="project"></a>Project
- Der Benutzer kann eine Aufgabe nicht als erledigt markieren, und sie wird auf 99 % festgelegt.
- Überlastungen werden durch einen Abgleich nicht behoben.

### <a name="word"></a>Word
- Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Absturz führen.
- Das Öffnen alter Dokumente und das anschließende Wechseln zur Registerkarte „Info“ kann zu einem Absturz führen.
- Vorschläge der Dokumentprüfung werden nicht in Kontextmenüs angezeigt.
- Inhaltsrichtlinien werden nicht ordnungsgemäß auf Kommentare angewendet.
- Alte Kommentare, die mit dunklem Text geschrieben wurden, sind im dunklen Modus nicht sichtbar.
- Bei Verwendung der AutoKorrektur für Koreanisch/Englisch werden möglicherweise falsche Zeichen angezeigt.
- Niedrigere Richtlinienbezeichnungen werden möglicherweise angewendet, wenn eine höhere Richtlinienbezeichnung Vorrang haben sollte.
- Die Links von cid:-Bildern aus Outlook-Nachrichten&nbsp;können nun auf Anforderung erfolgreich unterbrochen werden.
- Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Absturz führen.
- Die Suche im Navigationsbereich schlägt möglicherweise fehl.

### <a name="office-suite"></a>Office-Suite
- Einige Zeichnungen werden in der Vorschau oder in Bildschirmpräsentationen möglicherweise nicht angezeigt.
- Einige Katakana-Zeichen werden in einem vertikalen Textfeld möglicherweise nicht korrekt angezeigt werden.
- Der Versuch, eine Datei auf einer nicht verbundenen Netzwerkfreigabe zu speichern, kann zu einem Absturz führen.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1911-october-25"></a>Version 1911: 25. Oktober
*Version 1911 (Build 12215.20006)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="visio"></a>Visio

- **Erstellen von ansprechenden Visio-Diagrammen in Excel:** Visualisieren Sie Ihre Daten schnell und einfach in ansprechenden Visio-Diagrammen in Excel. [Weitere Informationen](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **Verbesserungen bei der gemeinsamen Dokumenterstellung:** Die gemeinsame Dokumenterstellung wurde verbessert, indem Inhaltsänderungen den anderen Benutzern nun nahezu immer in Echtzeit angezeigt werden.

- **Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Access

- <div><span>Möglicherweise ist die Datensatzanzahl falsch</span></div>


### <a name="excel"></a>Excel

- <div><span>Wir haben die Leistung beim Löschen von Spalten mit verbundenen Zellen erheblich verbessert.</span></div>


- <div><span>Es könnte Benutzern ggfs. nicht möglich sein, im Office 365-Format für Excel-Arbeitsmappen zu speichern</span></div>


- <div><span>Kontrollkästchen wurden nicht ordnungsgemäß gerendert</span></div>


- <div><span>Änderungen an der Größe eines Diagramms konnten nicht gespeichert werden.</span></div>


- <div><span>Einige VBA-Funktionen haben bei neuen Diagrammtypen einen Fehler zurückgegeben</span></div>


- <div><span>Bei einigen Dialogfeldern zur Auswahl von Datenquellen wurde die Groß-/Kleinschreibung nicht beachtet</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Änderungen an der Größe eines Diagramms konnten nicht gespeichert werden.</span></div>


### <a name="publisher"></a>Publisher

- <div><span>Shapes konnten außerhalb des Grafikrahmens angezeigt werden</span></div>


### <a name="word"></a>Word

- <div><span>Shapes konnten außerhalb des Grafikrahmens angezeigt werden</span></div>


- <div><span>Das Hervorheben von Text kann sich schwierig gestalten</span></div>


- <div><span>Ein Benutzer konnte daran gehindert werden, zu einem einzelnen Element im Editor zu navigieren.</span></div>


- <div><span>Möglicherweise wurden Grammatik- oder Rechtschreibfehler nicht hervorgehoben</span></div>


- <div><span>Änderungen an der Größe eines Diagramms konnten nicht gespeichert werden.</span></div>


- <div><span>Eine Visitenkarte konnte ggfs. nicht mehr geöffnet werden, nachdem eine Formatierung auf @mention angewendet wurde</span></div>


- <div><span>Ein Problem wurde behoben, bei dem Nutzer ggfs. Word, Excel- und PowerPoint-Dokumente nicht mehr speichern konnten.&nbsp; Dieses Problem betraf Benutzer, die eine neue Datei erstellten und das Dialogfeld &quot;Modell speichern&quot; öffneten, nachdem Sie auf das Symbol "Speichern" geklickt oder STRG + S gedrückt hatten.</span></div>


### <a name="office-suite"></a>Office-Suite

- <div><span>Leistungsproblem bei der Verwendung von Shapes unter Windows 7</span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1911-october-18"></a>Version 1911: 18. Oktober
*Version 1911 (Build 12209.20010)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Senden Sie barrierefreie E-Mails an die Benutzer, die sie am dringendsten benötigen:** Outlook zeigt einen E-Mail-Tipp an, um sicherzustellen, dass Ihr Inhalt barrierefrei ist, wenn Sie ihn an einen Benutzer senden, der barrierefreien Inhalt bevorzugt.

### <a name="powerpoint"></a>PowerPoint

- **Optimieren Sie Ihre Präsentation für alle:** Die Barrierefreiheitsprüfung hilft Ihnen beim Anordnen von Objekten auf Ihren Folien, indem sie die Sprachausgabe berücksichtigt.

### <a name="office-suite"></a>Office-Suite

- **Das Upload Center wird durch die Funktion „Dateien, die Ihre Aufmerksamkeit benötigen“ ersetzt:** Das Upload Center wird durch die in den Office-Anwendungen unter „Datei“ > „Öffnen“ angezeigte Funktion „Dateien, die Ihre Aufmerksamkeit benötigen“ ersetzt. Die neue Oberfläche ist moderner, besser integriert und im Vergleich zum Upload Center weniger aufdringlich.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a>Nicht sicherheitsrelevante Sicherheitsupdates
### <a name="excel"></a>Excel

- <div><span>Wir haben ein Problem behoben, bei dem Kontrollkästchen-Steuerelemente unter Verwendung der automatischen Anpassung der Zeilenhöhe verkleinert werden konnten</span></div>


- <div><span>Wir haben ein Problem gelöst, durch das das Auswählen einer Zelle nach dem Scrollen dazu führen konnte, dass die falsche Zelle ausgewählt wurde</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Wir haben ein Problem erkannt, durch das digitale Signaturen beim Signieren einer E-Mail-Nachricht mit einem digital signierten Anhang beschädigt werden könnten</span></div>


- <div><span>Wir haben ein Problem erkannt, bei dem lange Dateinamen nach dem Drag & Drop im Textkörper der Nachricht abgeschnitten wurden</span></div>


- <div>Wir haben ein Problem erkannt, bei dem es sein konnte, dass das Suchfeld nicht mehr angezeigt werden könnte, wenn das Menüband auf automatisches Ausblenden eingestellt ist</div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Es wurde ein Problem erkannt, bei dem das Seitenverhältnis für die Folienvorschau nicht ordnungsgemäß gesperrt bzw. entriegelt wurde</span></div>

### <a name="project"></a>Project

- <div>Wir haben ein Problem erkannt, bei dem Notizen, die während Aktualisierungsvorgängen eingegeben werden, möglicherweise nicht gespeichert werden<br></div>


- <div>Wir haben ein Problem erkannt, bei dem eine Datei durch einen Benutzer gesperrt werden konnte, aber kein Benutzername in der Fehlermeldung angezeigt wird</div>


- <div><span>Wir haben ein Problem erkannt, bei dem Benutzer beim Öffnen eines schreibgeschützten Projekts mehrere Nachrichten erhalten könnten</span></div>


### <a name="word"></a>Word

- <div><span>Bei der Anzeige von Kommentaren während der Verwendung einer Sprachausgabe wurde ein Problem erkannt</span></div>


- <div><span>Wir haben ein Problem festgestellt, bei dem einige Kritiken fälschlicherweise als Rechtschreib- oder Grammatikkritiken erkannt wurden</span></div>


- <div><span>Wir haben ein Problem erkannt, bei dem ein neues Kommentardialogfeld manchmal nicht in den Fokus gesetzt werden konnte</span></div>


### <a name="office-suite"></a>Office-Suite

- <div><span>Wir haben ein Problem behoben, bei dem ein Upgrade durch die falsche Fehlermeldung &quot;Es wird bereits eine andere Installation ausgeführt&quot;</span> verhindert werden konnte</div>

- <div><span>Wir haben ein Problem erkannt, das sich auf die Synchronisierung einer lokalen Ressource mit einer Cloud-Ressource auswirken könnte</span></div>

- <div><span>Es wurde ein Problem erkannt, bei dem eine Willkommensnachricht einen ungültigen Link enthielt</span></div>


[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-1910-october-11"></a>Version 1910: 11. Oktober
*Version 1910 (Build 12130.20112)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)
[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)
[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a>Nicht sicherheitsrelevante Sicherheitsupdates
### <a name="excel"></a>Excel

- <div>Ein Problem beim Einfügen von Dateien als Objekt aus OneDrive wurde behoben.</div>


- <div>Ein Problem wurde behoben, bei dem das Hyperlink-Format auf einige Inhalte nicht ordnungsgemäß angewendet werden konnte.</div>


- <div>Ein Problem wurde behoben, bei dem Formeln mit strukturierten absoluten Bezügen nicht ordnungsgemäß angepasst wurden.</div>


- <div>Ein Problem wurde behoben, das beim Öffnen von in früheren Versionen von Office erstellten Arbeitsmappen in aktuellen Versionen von Office zu Programmabstürzen führen konnte.</div>


- <div>Ein Problem wurde behoben, bei dem Inhalte, die aus Excel kopiert wurden, beim Einfügen in andere Office-Anwendungen falsch dargestellt werden konnten.</div>


- <div>Es wurde ein Problem mit Farben behoben, die in der Vorschau beim Einfügen von Diagrammen mithilfe von Diagrammvorlagen verwendet wurden.</div>


### <a name="powerpoint"></a>PowerPoint

- <div>Es wurde ein Problem identifiziert, durch das ARC-Geräte die Verbindung verlieren können, wenn sie unter AirSpace WinComp ausgeführt werden.</div>


### <a name="word"></a>Word

- <div>Ein Problem beim Einfügen von Dateien als Objekt aus OneDrive wurde behoben.</div>


- <div>Die Wiederherstellungsschritte wurden verbessert, <span>um ein Problem zu beheben, das dazu führte, dass grafische Inhalte aus E-Mail-Threads gelöscht werden konnten.&nbsp;</span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1910-october-04"></a>Version 1910: 04. Oktober
*Version 1910 (Build 12126.20000)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Add-In „Datenschnellansicht“: ** erstellen Sie schnell Visio-Flussdiagramme aus Excel. [Weitere Informationen](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a>Nicht sicherheitsrelevante Sicherheitsupdates
### <a name="excel"></a>Excel

- <div><span>Ein Problem wurde behoben, bei dem der Druckbereich in der Seitenansicht nicht korrekt war.</span></div>


- <div><span>Wir haben ein Problem behoben, durch das es gelegentlich nicht möglicher war, PivotTables während der gemeinsamen Dokumenterstellung zu aktualisieren</span></div>


### <a name="access"></a>Access

- <div>Wir haben ein Problem behoben, bei dem Benutzer bei der Verwendung einer freigegebenen Datenbank die Fehlermeldung &quot;„inkonsistenter Zustand“&quot; erhalten konnten.</div>


### <a name="outlook"></a>Outlook

- <div><span>Es wurde ein Problem behoben, durch das die Duplikation von E-Mail-Ordnern verursacht werden konnte</span></div>


- <div><span>Wir haben ein Problem behoben, das beim Senden einer s/MIME-verschlüsselten E-Mail-Nachricht eine falsche Fehlermeldung verursacht hat.</span></div>


- <div><span>Wir haben ein Problem behoben, das manchmal zu einem Absturz führen konnte, wenn ein Benutzer eine Nachricht vom Typ „verpasste Unterhaltung“ von Skype empfängt</span></div>


- <div><span>Wir haben ein Problem behoben, durch das ein Speicherleck entstehen konnte</span></div>


- <div><span>Es wurde ein Problem behoben, durch das beim Speichern als Entwurf ein falscher Absender angezeigt werden konnte</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span></span></div>Es wurde ein Problem behoben, durch das TextRanges nach dem Einfügen von Text in den Platzhalter für Kopf-/Fußzeile/Foliennummer im Folienmaster und Folienlayout nicht mehr funktionieren konnten.


- <div><span></span></div>Wir haben ein Problem behoben, durch das das Erstellen von Links beim Einfügen von Text mit Link verhindert wurde.


- <div>Wir haben ein Problem behoben, durch das die ordnungsgemäße Funktion von Statistiken verhindert wurde.</div>


### <a name="word"></a>Word

- <div><span>Wir haben ein Problem behoben, durch das Schriftfarben nicht angewendet wurden</span></div>


### <a name="office-suite"></a>Office-Suite

- <div>Wir haben ein Problem behoben, durch welches der Versionsverlauf angeboten werden konnte, obwohl diese Funktion deaktiviert worden war</div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1910-september-27"></a>Version 1910: 27. September
*Version 1910 (Build 12119.20000)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)
[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)
[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a>Nicht sicherheitsrelevante Sicherheitsupdates
### <a name="excel"></a>Excel

- <div><span>Es wurde ein Problem behoben, durch das Punkt-Linien-Diagramme beim Ändern der Reihensammlung nicht ordnungsgemäß dargestellt werden konnten.</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Es wurde ein Problem behoben, durch das bei der Interaktion mit freigegebenen Kalenderordnern Berechtigungsfehler gemeldet wurden.</span></div>


- <div><span>Es wurde ein Problem behoben, das Benutzer eventuell daran gehindert hätte, Anlagen an Kalender hinzuzufügen</span></div>


- <div><span>Es wurde ein Problem behoben, durch das beim Antworten auf eine digital signierte Nachricht Fehlermeldungen angezeigt wurden</span></div>


### <a name="word"></a>Word

- <div><span> Es wurde ein Problem behoben, das zu Skalierungsproblemen führte, wenn auf Deskjet-Druckern gedruckt wurde</span></div>


### <a name="office-suite"></a>Office-Suite

- <div><span>Es wurde ein Problem behoben, bei dem mittel-fett formatierter Text nicht ordnungsgemäß formatiert werden konnte</span></div>


- <div><span>Es wurde ein Problem behoben, bei dem einem Benutzer beim Schließen einer Datei mit ausstehendem Upload eine falsche Fehlermeldung angezeigt wird</span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1910-september-20"></a>Version 1910: 20. September
*Version 1910 (Build 12112.20000)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a>Nicht sicherheitsrelevante Sicherheitsupdates
### <a name="excel"></a>Excel

- <div><span>Es wurde ein Problem behoben, durch das Excel manchmal beim Start hängen geblieben ist.</span></div>

### <a name="outlook"></a>Outlook

- <div><span>Die Leistung der Raumauswahl bei einer großen Anzahl von verfügbaren Räumen wurde erheblich verbessert.</span></div>


- <div><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Es wurde ein Problem behoben, durch das die Postfachsynchronisierung für Kunden mit mehreren Postfächern in Outlook nach der Migration zur modernen Authentifizierung in Office 365 verhindert wurde.</span><br></div>


- <div><span>Es wurde ein Problem behoben, bei dem einige Zeichen in Signaturbeschriftungen im Dropdownmenü nicht angezeigt wurden</span></div>


### <a name="project"></a>Projekt

- <div><span>Es wurde ein Problem behoben, das beim Ersetzen einer Unternehmensressource durch eine lokale Ressource zu einem Absturz führte</span></div>


### <a name="word"></a>Word

- <div><span>Es wurde ein Problem behoben, durch das ein synchrones Scrollen in der Entwurfsdarstellung nicht ordnungsgemäß funktionierte</span></div>


- <div>Es wurde ein Problem behoben, durch das QuickInfos nach dem erstmaligen Speichern eines Dokuments zeitweise nicht ordnungsgemäß angezeigt wurden.</div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1910-september-13"></a>Version 1910: 13. September
*Version 1910 (Build 12105.20000)*


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a>Nicht sicherheitsrelevante Sicherheitsupdates
### <a name="excel"></a>Excel

- <div><span>Ein Problem wurde behoben, das verhindern konnte, dass ein Benutzer Links in bestimmte geschützte Blättern einfügt</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Ein Problem wurde behoben, bei dem die Benutzeroberfläche möglicherweise in einer kompakten Darstellung stecken blieb</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Ein Problem wurde behoben, bei dem ein Benutzer beim Drucken in eine PDF-Datei möglicherweise eine Fehlermeldung erhielt</span></div>


### <a name="project"></a>Project

- <div><span>Ein Problem wurde behoben, bei dem <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">Änderungen an einem Arbeitswert in einem Sammelvorgang zu einem Absturz führen konnten, wenn geschützte Arbeit aktiviert ist</span></span></div>


- <font size=2 style="background-color:rgb(255, 255, 255);">Ein Problem wurde behoben, durch das die Möglichkeit zum Synchronisieren von Ereignissen mit Enterprise-Kalendern verhindert werden konnte</font>


### <a name="office-suite"></a>Office-Suite

- <div><span>Ein Problem wurde behoben, durch das eine wiederholte Warnung zum Verwerfen lokaler Versionen einer Datei angezeigt werden konnte</span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1910-september-06"></a>Version 1910: 6. September
*Version 1910 (Build 12030.20004)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Auf die Plätze, fertig, zeichnen!** Sobald Sie Ihren Surface Pen in der Hand halten, können Sie mit dem Zeichnen beginnen. [Weitere Informationen](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a>PowerPoint

- **Auf die Plätze, fertig, zeichnen!** Sobald Sie Ihren Surface Pen in der Hand halten, können Sie mit dem Zeichnen beginnen. [Weitere Informationen](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a>Word

- **Auf die Plätze, fertig, zeichnen!** Sobald Sie Ihren Surface Pen in der Hand halten, können Sie mit dem Zeichnen beginnen. [Weitere Informationen](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a>Nicht sicherheitsrelevante Sicherheitsupdates
### <a name="excel"></a>Excel

- <div><span>Es wurde ein Problem behoben, das dazu führen konnte, dass der Name der Schriftart im Menü von der verwendeten Schriftart abweicht</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Es wurde ein Problem behoben, das zu einer unangemessenen Ressourcennutzung von Outlook führen kann, wenn der geschützte Modus für eingeschränkte Websites im Internet Explorer deaktiviert ist</span></div>


- <div><span>Es wurde ein Problem behoben, das beim Einfügen eines Textes aus einer ANSI-Quelle manchmal dazu führen kann, dass Unicode-Zeichen angezeigt werden</span></div>


- <div><span>Ein Problem wurde behoben, bei dem einige Benutzer in einer Gruppen-Planungsanzeige fälschlicherweise als offline angezeigt wurden</span></div>


### <a name="word"></a>Word

- <div><span>Ein Problem wurde behoben, welches dazu führen konnte, dass Tabellenformatierung verloren ging</span></div>


- <div><span>Wir haben ein Problem behoben, welches dazu führen konnte, dass die Tastenkombination STRG + V nicht ordnungsgemäß funktionierte</span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1909-august-30"></a>Version 1909: 30. August
*Version 1909 (Build 12026.20000)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates

### <a name="access"></a>Access

- **Schnelle Suche nach verknüpften Tabellen:** Unser neues Suchfeld macht die Suche nach verknüpften Tabellen zu einem Kinderspiel.

### <a name="powerpoint"></a>PowerPoint

- **Speichern einer Illustration als SVG:** Speichern Sie ein Diagramm, eine Form oder eine andere Abbildung als skalierbare Vektorgrafik, deren Größe ohne Verlust der Bildqualität geändert werden kann. [Weitere Informationen](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="non-security-updates"></a>Nicht sicherheitsrelevante Sicherheitsupdates
### <a name="excel"></a>Excel

- <div><span>Wir haben ein Problem behoben, bei dem die Tastenkombination für&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Vertraulichkeit</span> mit&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">einer anderen Tastenkombination in Konflikt stand.</span></span></div>

- <div><span>Beim Speichern wurde ein Problem behoben, das beim Bearbeiten einer freigegebenen Arbeitsmappe auftrat, wenn versucht wurde zu speichern.</span></div>

- <div><span>Wir haben ein Problem behoben, bei dem Excel nur die ersten 16 Add-Ins auflistet, die sich in den „\Excel\Add-in Manager“ Registrierungswerten befinden.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></div>


- <div><span>Wir haben ein Problem behoben, bei dem die Funktion „Häufigkeit()“ falsche Ergebnisse liefert.</span></div>


- <div><span>Die Leistung der Filterung nach Farbe wurde deutlich verbessert.</span></div>


- <div><span>Wir haben ein Problem für Surface-Benutzer behoben, bei dem das Bewegen der Maus als ein Mausklick interpretiert werden konnte.</span></div>


- <div><span>Wir haben ein Problem behoben, das die Tastaturnavigation im Dialog „Suchen/Ersetzen“ verhinderte.</span></div>


- <div><span>Wir haben ein Problem behoben, bei dem der Name einiger Schriftarten nicht korrekt angezeigt wurde.</span></div>


- <div><span>Wir haben ein Problem behoben, durch das CSV nicht als unterstützter Dateityp angezeigt wurde.</span></div>


### <a name="access"></a>Access

- <div>Wir haben ein Problem behoben, bei dem Benutzer bei der Verwendung einer freigegebenen Datenbank die Fehlermeldung &quot;„inkonsistenter Zustand“&quot; erhalten konnten.</div>


- <div><span>Wir haben ein Problem behoben, bei dem die Datumsauswahl angezeigt wurde, wenn es nicht nötig war.</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Es wurde ein Problem behoben, das die Darstellung von HTML-Inhalten für einige POP3-Benutzer verhinderte.</span></div>


- <div><span>Es wurde ein Problem behoben, bei dem der nicht funktionierende Link "Planer" aus dem Überlaufmenü der Visitenkarte entfernt wurde, wenn Sie in Umgebungen arbeiten, in denen er nicht verfügbar ist.</span></div>

### <a name="onenote"></a>OneNote

- <div><span>Es wurde ein Problem behoben&nbsp;, bei dem die Hintergrundsynchronisierung von OneNote manchmal den Fokus auf sich zog.</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Wir haben ein Problem behoben, das sich auf die Drehrichtung eines 3D-Drehtisches auswirken würde.</span></div>

- <div><span>Wir haben ein Problem behoben, durch das einige Hyperlinks nicht mehr funktionierten, wenn sie Sonderzeichen enthielten.</span></div>

- <div><span>Es wurde ein Problem behoben, bei dem mehrere Kommentarfenster gleichzeitig geöffnet wurden.</span></div>

### <a name="project"></a>Project

- <div><span>Wir haben ein Problem behoben, das nach dem Drucken einer Teamplaneransicht manchmal zu einem Absturz führen konnte.</span></div>

### <a name="word"></a>Word

- <div>Wir <span>haben ein Problem behoben, bei dem Multibyte-Zeichen in vertikalem Textfeld in der Leseansicht überlappt dargestellt werden.<br></span></div>

- <div><span>Wir&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">haben ein Problem behoben, bei dem die japanischen Postkarten-und Grußkarten bezogenen Add-in-Ressourcen nicht gefunden werden, wenn der Benutzer im Add-in-Assistenten eine Aktion durchführt.</span></span></div>

- <div><span>Wir haben ein Problem behoben, das Schwierigkeiten mit der Benutzeroberfläche der Titelleiste verursachen konnte, wenn Sie sich in der geschützten Anzeige befinden.</span></div>

### <a name="office-suite"></a>Office-Suite

- <div><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> Wir haben ein Problem, das eine fehlerhafte Datei erzeugte, wenn Sie die Form in einer Auswahl ändern, die sowohl eine normale Form als auch eine Verbinder-Form enthält.</span></span></div>

- <div><span>Wir haben ein Problem behoben, das <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">zu einem Problem in Anwendungen führte, wenn man das An- und Abdocken von mehreren externen Displays verwendet.</span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="august-23-2019br"></a>**23. August 2019**<br/>
Version 1909 (Build 12015.20004)<br/>



## <a name="non-security-updates"></a>Nicht sicherheitsrelevante Updates:

### <a name="excel"></a>Excel

- <div><span>Wir haben die Leistung beim Löschen von Spalten mit verbundenen Zellen erheblich verbessert.</span></div>


### <a name="office-suite"></a>Office-Suite

- <div><span>Es wurde ein Problem behoben, durch das einige Unicode-Zeichen nicht angezeigt werden konnten, wenn sie in einem Browser dargestellt werden sollten.</span></div>


### <a name="outlook"></a>Outlook

- <div><span>Es wurde ein Problem behoben, durch das Dateien am WebDAV-Speicherort nicht gespeichert werden konnten.</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Ein Problem wurde behoben, bei dem ein Benutzer auf einen Kommentar klickte, aber ein anderer Kommentar ausgewählt wurde.</span></div>





## <a name="august-16-2019br"></a>**16. August 2019**<br/>
Version 1909 (Build 12013.20000)<br/>

### <a name="powerpoint-feature-updates"></a>PowerPoint-Featureupdates:

- **Drucken von Foliennummern auf Handzetteln:** Foliennummern werden automatisch in Ihre Handzettel integriert. Sie können diese Funktion an- oder abschalten, wie es Ihnen beliebt.




## <a name="non-security-updates"></a>Nicht sicherheitsrelevante Updates:

### <a name="excel"></a>Excel

- <div><span>Wir haben ein Problem behoben, durch das sich die Funktion „Automatisches Speichern“ aktivieren konnte.</span></div>


- <div>Wir haben ein Problem behoben, das zur ungenauen Bemessung der Zellenhöhe führen konnte.</div>


### <a name="office-suite"></a>Office-Suite

- <div><span>Wir haben ein Problem behoben, das die Leistung der Kommentarfunktion erheblich verbessert.</span></div>


- <div><span>Ein Problem wurde behoben, das bei der Verwendung von Pfeiltasten während der Suche zum Absturz führen konnte.</span></div>


- <div><span>Wir haben ein Problem behoben, durch das eine @Erwähnung verhindert werden konnte, wenn das @-Symbol nach bestimmten Zeichen gesetzt wurde.</span></div>


- <div><span>Wir haben ein Problem behoben, das beim Löschen von @Erwähnungen zum Absturz führen konnte.</span></div>


- <div><span>Es wurde ein Problem behoben, durch das die korrekte Anzeige von Emojis in Kommentarkarten verhindert wurde.</span></div>


- <div><span>Es wurde ein Problem mit Active Clipboard behoben, das manchmal zum Absturz führen konnte.</span></div>


- <div><span>Wir haben ein Problem behoben, durch das die Schaltflächen für die Symbolleiste für den Schnellzugriff nicht mehr funktionierte.</span></div>


- <div><span>Wir haben ein Problem behoben, durch das das Wechseln der Dokumentformatierungsvorschau in den Hintergrund verhindert werden konnte.</span></div>

### <a name="onenote"></a>OneNote

- Ein Problem wurde behoben, bei dem die Namen von Abschnitten in der Dropdownliste „Abschnitt“ nicht dargestellt wurden, wenn das Office-Design auf „schwarz“ festgelegt war.

### <a name="outlook"></a>Outlook

- <div><span>Wir haben ein Problem beim Senden von Ereignissen behoben, das dazu führen konnte, dass Outlook wiederholt fokussiert und den Fokus verliert.</span></div>


- <div><span>Es wurde ein Problem behoben, durch das die Verknüpfung „Antwort im Ordner bereitstellen“ nicht funktionierte.</span></div>

### <a name="powerpoint"></a>PowerPoint

- <div><span>Es wurde ein Problem mit der geschützten Ansicht behoben, das manchmal bei der Zusammenarbeit zu Problemen führen konnte.</span></div>


- <div><span>Es wurde ein Problem behoben, das verhindern konnte, dass Aufgaben in Kommentarbereichen korrekt angezeigt werden.</span></div>


- <div><span>Ein Problem wurde behoben, das beim Einfügen neuer Folien zum Absturz führen konnte.</span></div>


### <a name="user-lifecycle"></a>Lebenszyklus des Benutzers:

- <div><span>Es wurde ein Problem behoben, das manchmal dazu führte, dass Abonnementfeatures nicht mehr angezeigt wurden.</span></div>


### <a name="word"></a>Word

- <div><span>Es wurde ein Problem behoben, durch das Hyperlinks fehlerhaft sein konnten, wenn sie bestimmte Zeichen enthielten.</span></div>


- <div><span>Ein Problem wurde behoben, bei dem beim Anzeigen eines Kommentars für ein Bild dieses manchmal nicht in der korrekten Größe dargestellt wurde.</span></div>


- <div><span>Es wurde ein Problem mit dem Dropdownmenü „Aufzählung“ behoben, das manchmal zu einem Absturz führten konnte.</span></div>





## <a name="august-09-2019br"></a>**09. August 2019**<br/>
Version 1909 (Build 12001.20000)<br/>

### <a name="excel-feature-updates"></a>Excel-Featureupdates:

- **Zusammenarbeiten ist jetzt noch einfacher:** Verbesserungen bei der gemeinsamen Dokumenterstellung führen dazu, dass Ihre Änderungen beim Arbeiten mit bedingter Formatierung, Zellformatvorlagen und mehr nahtlos mit denen Ihrer Mitarbeiter zusammengeführt werden.


- **Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können. Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben.


### <a name="office-suite-feature-updates"></a>Office-Suite-Featureupdates:

- **Neue Office-App-Symbole:** Neu gestaltete App-Symbole, die die einfache, leistungsstarke und intelligente Oberfläche von Office widerzuspiegeln.


### <a name="outlook-feature-updates"></a>Outlook-Featureupdates:

- **Erweiterter Schutz gegen Angriffe:** Mit Office 365 Advanced Threat Protection sind Sie vor Angriffen durch Links in E-Mail-Betreffzeilen, angefügten Nachrichten, signierten Nachrichten, Netzwerkpfaden usw. geschützt.


- **Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können. Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben.


### <a name="powerpoint-feature-updates"></a>PowerPoint-Featureupdates:

- **Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können. Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben.


### <a name="word-feature-updates"></a>Word-Featureupdates:

- **Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.


- **Suchen und sich freuen:** Wir haben die Suche zum Einfügen von Symbolen hinzugefügt, damit Sie das gewünschte Symbol ganz einfach finden können. Und beim Auswählen wird auf der Schaltfläche „Einfügen“ angezeigt, wie viele Elemente Sie ausgewählt haben.




## <a name="non-security-updates"></a>Nicht sicherheitsrelevante Updates:

### <a name="outlook"></a>Outlook

- <div><span>Ein Problem wurde behoben, das dazu führte, dass Besprechungsempfänger zwei Benachrichtigungen erhielten, nachdem eine Besprechung abgebrochen wurde</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Ein Problem wurde behoben, durch das ein Absturz verursacht werden konnte, wenn der Benutzer für Formen und Symbole "Keine Kontur" oder "Keine Füllung" auswählte</span></div>





## <a name="august-02-2019br"></a>**02. August 2019**<br/>
Version 1908 (Build 11929.20002)<br/>

### <a name="excel-feature-updates"></a>Excel-Featureupdates:

- **Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.


- **Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente:** Sie können eine Vertraulichkeitsbezeichnung auf Ihre Dateien und E-Mails anwenden, damit sie den Richtlinien zum Datenschutz Ihrer Organisation entsprechen.


### <a name="outlook-feature-updates"></a>Outlook-Featureupdates:

- **Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente:** Sie können eine Vertraulichkeitsbezeichnung auf Ihre Dateien und E-Mails anwenden, damit sie den Richtlinien zum Datenschutz Ihrer Organisation entsprechen.


### <a name="powerpoint-feature-updates"></a>PowerPoint-Featureupdates:

- **Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.


- **Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente:** Sie können eine Vertraulichkeitsbezeichnung auf Ihre Dateien und E-Mails anwenden, damit sie den Richtlinien zum Datenschutz Ihrer Organisation entsprechen.


### <a name="word-feature-updates"></a>Word-Featureupdates:

- **Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.


- **Anders ausgedrückt:** Wenn Sie etwas anders formulieren möchten, hilft Ihnen „Neu schreiben“ dabei. „Neu schreiben“ bietet Alternativen zum Verbessern Ihrer Formulierungen.


- **Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente:** Sie können eine Vertraulichkeitsbezeichnung auf Ihre Dateien und E-Mails anwenden, damit sie den Richtlinien für den Datenschutz Ihrer Organisation entsprechen.




## <a name="non-security-updates"></a>Nicht sicherheitsrelevante Updates:

### <a name="access"></a>Access
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="excel"></a>Excel

- <div><span>Es wurde ein Problem behoben, bei dem es so aussah, als ob die Option &quot;Alle Beschriftungen wiederholen&quot; beim Drucken in eine PDF-Datei angewendet wurde.</span></div>

### <a name="office-suite"></a>Office-Suite

- <div><span>Es wurde ein Problem behoben, durch das verhindert wurde, dass Benutzer ein Dokument auf dem Desktop öffnen.</span></div>

- <div><span>Es wurde ein Problem behoben, bei dem ein Upgrade durch eine falsche Fehlermeldung bei &quot;Es wird bereits eine andere Installation ausgeführt&quot;</span> verhindert wurde.</div>

- <div><span>Es wurde ein Problem behoben, bei dem einem Benutzer beim Installieren von Sicherheitsupdates Fehlermeldungen angezeigt wurden.</span></div>

- <div><span>Es wurde ein Problem behoben, aufgrund dessen der Cursor verschwand.</span></div>

- <div><span>Wir haben ein Problem behoben, bei dem für einen Benutzer standardmäßig die Registerkarte „Zeichnen“ der Registerkarte „Start“ angezeigt wurde.</span></div>

- <div><span>Es wurde ein Problem behoben, bei dem große Strukturansichten zu einem Absturz führten.</span></div>

### <a name="outlook"></a>Outlook

- <div></div><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">Es wurde ein Problem behoben, durch das wiederholte Kennworteingabeaufforderungen verursacht werden können.</span>

- <div><span>Es wurde ein Problem behoben, durch das verhindert wurde, dass eine E-Mail-Adresse korrekt abgefragt wird.</span></div>

- <div><span>Es wurde ein Problem behoben, durch das verhindert wurde, dass Benutzer Kalenderelemente öffnen, die von älteren Versionen von Outlook erstellt wurden.</span></div>

### <a name="powerpoint"></a>PowerPoint

- <div><span>Es wurde ein Problem behoben, durch das verhindert wurde, dass einige Animationen gestartet werden.</span></div>

### <a name="project"></a>Project
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="word"></a>Word

- <div><span>Es wurde ein Problem behoben, bei dem Antworten auf Kommentare in falscher Reihenfolge angezeigt wurden.</span></div>

- <div><span>Es wurde ein Problem behoben, bei dem in manchen Fällen Hinweise anstelle von Kommentaren angezeigt wurden.</span></div>

- <div><span>Es wurde ein Problem behoben, bei dem der Bereich „Überprüfungen“ angezeigt wurde, wenn der Benutzer versuchte, einen neuen Kommentar hinzuzufügen.</span></div>

- <div><span>Es wurde ein Problem behoben, durch das verhindert wurde, dass die Dropdownliste „Rückgängig machen“ angezeigt wird.</span></div>

- <div><span>Es wurde ein Problem behoben, durch das verhindert wurde, das Kommentare hinzugefügt werden.</span></div>


## <a name="july-26-2019"></a>26. Juli 2019
Version 1908 (Build 11916.20000)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="word-excel-powerpoint"></a>Word, Excel, PowerPoint

#### <a name="create-more-accessible-pdfs"></a>Erstellen von barrierefreien PDF-Dateien

Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten.

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="all"></a>Alle

- Ein Problem wurde behoben, bei dem die Zuordnung von Dateitypen und Symbolen für Office nach einem Office-Update manchmal entfernt wurden

### <a name="word"></a>Word 
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="excel"></a>Excel
- Ein Problem wurde behoben, bei dem das Verschieben eines Diagramms manchmal zu einem Absturz führte
- Ein Problem wurde behoben, bei dem das Abrufen eines Arbeitsmappenobjekts aus einem Diagrammobjekt nach dem Ändern von Diagrammtypen manchmal zu einem Fehler führte

### <a name="powerpoint"></a>PowerPoint
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="outlook"></a>Outlook
- Ein Problem wurde behoben, bei dem im vereinfachten Menüband ein deaktiviertes Steuerelement manchmal nicht grau dargestellt wurde

### <a name="access"></a>Access
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="project"></a>Project
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

</BR></BR>

## <a name="july-19-2019"></a>19. Juli 2019
Version 1908 (build 11911.20000)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="word"></a>Word

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a>Informationen zur Bedeutung von Abkürzungen beim Lesen in Word Online

Wenn Sie auf eine Abkürzung treffen, versuchen wir, diese mithilfe von Daten innerhalb Ihrer Organisation zu definieren.


## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="word"></a>Word 
- Das Problem des fehlenden BookMarkEnd-Tags wurde behoben.
- Ein Problem wurde behoben, bei dem sich die Schriftartauswahl bei der Eingabe von Sonderzeichen ändern konnte
- Ein Problem wurde behoben, das manchmal dazu führen könnte, dass Antworten auf eine neue Kommentarkarte leer waren
- Ein Problem wurde behoben, das dazu führen könnte, dass Formatierungen beim Teilen einer E-Mail-Nachricht verloren gingen

### <a name="excel"></a>Excel
- Ein Problem wurde behoben, durch das ein Array mit einem großen Bereich manchmal einen Absturz verursachte
- Die Leistung beim Kopieren von Daten aus gefilterten Bereichen wurde erheblich verbessert
- Ein Problem wurde behoben, durch das einige Dateien, deren Dateinamen Sonderzeichen enthielten, nicht geöffnet wurden

### <a name="powerpoint"></a>PowerPoint
- Ein Problem wurde behoben, bei dem der Abschnittname für den neu erstellten Abschnitt in PowerPoint nicht standardmäßig aktiviert war.
- Ein Problem wurde behoben, durch das die Verwendung der Benutzeroberfläche in einer 4:3-Anzeige schwierig war

### <a name="outlook"></a>Outlook
- Ein Problem wurde behoben, durch das verfügbare Räume möglicherweise nicht aufgeführt wurden
- Ein Problem wurde behoben, durch das einige POP3-Benutzer keine HTML-Formatierungen verwenden konnten

### <a name="access"></a>Access
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="project"></a>Project
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

</BR></BR>

## <a name="july-12-2019"></a>12. Juli 2019
Version 1907 (Build 11901.20038)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="powerpoint"></a>PowerPoint
 
#### <a name="use-ink-replay-in-your-presentations"></a>Verwenden von Freihand-Wiedergabe in Präsentationen
 
Verwenden Sie Wiedergabe-Animationen für Freihand in PowerPoint, um in Präsentationen mehr auszudrücken und zu kommunizieren. 

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="word"></a>Word 
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="excel"></a>Excel
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="powerpoint"></a>PowerPoint
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="outlook"></a>Outlook
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="access"></a>Access
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="project"></a>Project
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

</BR></BR>

## <a name="july-5-2019"></a>5. Juli 2019
Version 1907 (Build 11901.20018)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="word-excel-powerpoint"></a>Word, Excel, PowerPoint

#### <a name="sketchy-shapes"></a>Skizzenhafte Formen!

Mitten im Entwurfs einer Präsentation? Wenden Sie die Formatvorlage "Skizzenhaft" an, um anzuzeigen, dass Sie zurzeit noch am Entwurf arbeiten. Dies verleiht Ihren Objekten eine persönliche Note, ohne sie in von Hand gezeichnete Freiformobjekte umzuwandeln.

### <a name="excel"></a>Excel

- **Schnellere Dateifreigabe**: Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.
### <a name="powerpoint"></a>PowerPoint

- **Um den Zugriff zu erleichtern, wurde die Einstellung zum Drucken von Foliennummern in Handzetteln wurde in das Menü „Drucken“ verschoben:** Sie finden sie in der Dropdownliste Druck > Drucklayout, wenn ein Handzettellayout ausgewählt ist. Auf diese Weise können Sie die Einstellung auch für einzelne Präsentationen ganz einfach umschalten. [Weitere Informationen](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- **Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.

### <a name="word"></a>Word

- **Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="all"></a>Alle
- Die Leistung der Menüband-Zugriffstasteninfos wurde erheblich verbessert
- Ein Problem wurde behoben, das verhinderte, dass das Dialogfeld "Erfahren Sie, was in Kürze verfügbar ist" ordnungsgemäß angezeigt wurde
- Ein Problem wurde behoben, durch das Fotos im Katalogflyout für die gemeinsame Dokumenterstellung falsch ausgerichtet sein konnten

### <a name="word"></a>Word 
- Ein Problem wurde behoben, durch das manchmal das Hinzufügen neuer Kommentare verhindert wurde
- Ein Problem wurde behoben, durch das Tabellen manchmal einen Absturz verursachten
- Ein Problem wurde behoben, bei dem manchmal ungültige Daten ans Ende eines Seriendrucks angehängt wurden
- Ein Problem wurde behoben, durch das einige LaTeX-Gleichungen nicht ordnungsgemäß gerendert wurden

### <a name="excel"></a>Excel
- Ein Problem wurde behoben, bei dem das Ändern von Diagrammtypen zu einer Laufzeitausnahme führen konnte
- Ein Problem wurde behoben, bei dem manchmal das falsche Menüband angezeigt wurde, wenn mehrere Fenster geöffnet waren
- Ein Problem wurde behoben, das einen Fehler verursachen konnte, wenn ein Makro eine zweite Instanz einer Arbeitsmappe öffnete
- Ein Problem wurde behoben, das beim Öffnen oder Erstellen einer Arbeitsmappe oder beim Wechseln zwischen Arbeitsmappen zu einem Absturz führen könnte
- Ein Problem wurde behoben, das verhinderte, dass Benutzer eine aus Word erstellte PDF-Datei in Teams öffnen konnten

### <a name="powerpoint"></a>PowerPoint
- Ein Problem wurde behoben, durch das die Qualität eines Diagramms beim Export in eine PDF-Datei beeinträchtigt wurde
- Ein Problem wurde behoben, durch das eine QuickInfo, die die Entfernung zur Mitte angibt, nicht angezeigt wurde

### <a name="outlook"></a>Outlook
- Ein Problem wurde behoben, das manchmal die Anzeige des Fehlers "Datenträger voll" verhinderte
- Ein Problem wurde behoben, das dazu führen könnte, dass Anlagen beim Aktualisieren einer Besprechungsanfrage dupliziert wurden

### <a name="access"></a>Access
- Ein Problem wurde behoben, durch das einige Abfragen keine großen ganzzahligen Werte mehr zurückgeben konnten
- Ein Problem wurde behoben, durch das SQL-Textfeld nicht mehr bearbeitet werden konnte
- Ein Problem wurde behoben, bei dem QuickInfos auf einigen High DPI-Displays schwer zu erkennen waren

### <a name="project"></a>Project
- Ein Problem wurde behoben, durch das Flagwerte in neuen Vorgängen nicht mehr bearbeitet werden konnten
- Ein Problem wurde behoben, durch das eine Statusaktualisierung dazu führen konnte, dass das tatsächliche Anfangsdatum bei Aufgaben und Vorgängen nicht ordnungsgemäß festgelegt wurde
- Ein Problem wurde behoben, das dazu führen könnte, dass einige Ressourcen fälschlicherweise als überlastet angezeigt wurden
- Ein Problem wurde behoben, bei dem die Methode "TaskDependencies Add" beim Hinzufügen von "Lag", wenn das Dezimaltrennzeichen ein Komma war und bei einer Verbindung mit einem Server manchmal fehlschlug
- Es wurde ein Problem behoben, durch das das Aktualisieren von lokalen Werten der Nachschlagetabelle für das benutzerdefinierte Feld über CSOM zum Absturz des PCs führen konnte
- Ein Problem wurde behoben, bei dem die Werte für die gesamte Arbeit falsch erscheinen können, wenn sie eine Dezimalzahl enthalten

</BR></BR>

## <a name="june-28-2019"></a>28. Juni 2019
Version 1907 (Build 11819.20002)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="excel"></a>Excel

- **Schnelles Programmieren mit Power Query-Verbesserungen:** Mit AutoVervollständigen und farbiger Syntax können Sie Code schnell fertigstellen. Außerdem können Sie auf einfache Weise Funktionen, Spalten und Parameter ermitteln.

- **Verknüpfen von Tabellen in ähnlichen Spalten:** Abrufen & Transformieren (Power Query) bietet jetzt eine ungefähre Textübereinstimmungslogik (auch Fuzzy-Übereinstimmung genannt) beim Vergleichen von Spalten zum Zusammenführen von Tabellen.

### <a name="word"></a>Word

- **Verbesserungen bei der gemeinsamen Dokumenterstellung:** Verbesserte Zuverlässigkeit bei der gemeinsamen Dokumenterstellung.
 
### <a name="word-excel-powerpoint-and-visio"></a>Word, Excel, PowerPoint und Visio

#### <a name="recommended-documents"></a>Empfohlene Dokumente

Lassen Sie sich Dokumente mit für Sie relevanter Aktivität empfehlen.

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="word"></a>Word 
- Wir haben ein Problem behoben, welches einige Nutzer daran hindern konnte, einige .doc-Dateien zu öffnen.
- Wir haben ein Problem behoben, das gelegentlich verhindert hat, dass Kommentare richtig geladen wurden.

### <a name="excel"></a>Excel
- Wir haben die Leistung von Power Queries verbessert.

### <a name="powerpoint"></a>PowerPoint
- Es wurde ein Problem mit der Verwendung eines Stifts auf einem Surface-Gerät behoben, der dazu führen konnte, dass der Bildschirm flackerte.

### <a name="outlook"></a>Outlook
- Wir haben ein Problem behoben, durch das der Frei/Gebucht-Status eines Termins bei der Konvertierung in eine Besprechung geändert werden konnte.
- Ein Problem wurde behoben, bei dem die falsche Vorlage und Beschreibung angezeigt wurden, wenn eine E-Mail mit einer Ad-hoc-Vorlage geschützt wurde.

### <a name="access"></a>Access
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="project"></a>Project
- Verschiedene Korrekturen der Leistung und Stabilität

</BR></BR>

## <a name="june-21-2019"></a>21. Juni 2019
Version 1907 (build 11815.20002)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="outlook"></a>Outlook

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a>Dunkler Modus für "schwarzes Design" in Outlook-Desktop

Im dunklen Modus wird nun Benutzern, die das Design "Schwarz" verwenden, auch der Lesebereich beim Lesen von E-Mails sowie die Verfassen-Oberfläche beim Schreiben von E-Mails mit einem dunklen Hintergrund angezeigt. Mit Hilfe eines Sonne/Mond-Schalters im Lesebereich und im Menüband können Benutzer in einer Vorschau ansehen, wie eine Nachricht hingegen mit einem hellen Hintergrund aussieht.

#### <a name="getting-started"></a>Erste Schritte:

1. Wählen Sie das schwarze Design aus. Der dunkle Modus ist in diesem Fall standardmäßig aktiviert.
2. Verwenden Sie den Sonne/Mond-Schalter (im Lesebereich und im Menüband), um in einer Vorschau anzuzeigen, wie die Nachricht für Benutzer aussieht, die den dunklen Modus nicht aktiviert haben.

#### <a name="scenarios-to-try"></a>Szenarien zum Ausprobieren:

1. Lesen von E-Mails im dunklen Modus. Wenn Sie etwas nicht lesen können, verwenden Sie den Umschalter "Sonne" im Lesebereich, um zu einem hellen Hintergrund zu wechseln. 
2. Verfassen von E-Mails im dunklen Modus. Zeigen Sie mit Hilfe des Sonne-Schalters im Menüband in einer Vorschau an, wie Ihre Nachricht mit einem hellen Hintergrund aussehen wird. 

Sollten einzelne E-Mails nicht korrekt dargestellt werden, senden Sie diese bitte (als Anlage) an OutlookDarkModeFail@service.microsoft.com

#### <a name="get-location-suggestions"></a>Abrufen von Standortvorschlägen

Beginnen Sie mit der Eingabe, Outlook wird automatisch nach passenden Orten suchen.

Dies gilt für das Feld "Ort" beim Erstellen von Terminen und Besprechungen.

#### <a name="getting-started"></a>Erste Schritte:

- Erstellen Sie einen Termin oder eine Besprechung in einem O365- oder Outlook.com-Kalender in Outlook. 
- Klicken Sie in das Feld "Ort", und beginnen Sie mit der Eingabe.

#### <a name="scenarios-to-try"></a>Szenarien zum Ausprobieren:

Wenn Sie einer Besprechung einen Konferenzraum hinzufügen möchten, klicken Sie auf das Feld "Ort", anstatt das "Raumsuche"-Add-in oder das Adressbuch zu verwenden.
Versuchen Sie für Termine an einem öffentlichen Ort – beispielsweise ein Restaurant, ein Coffeeshop oder eine Zahnartpraxis – den exakten Standort mithilfe der neuen Auswahl zu finden. Auf diese Weise können Sie über Outlook Mobile benachrichtigt werden, wenn es Zeit ist, aufzubrechen.

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="all"></a>Alle
- Wir haben ein Problem behoben, durch das das Suchfeld im Offlinemodus aktiviert blieb.

### <a name="word"></a>Word 
- Ein Problem wurde behoben, bei dem der Tastaturfokus manchmal schwierig zu erkennen war.
- Ein Problem wurde behoben, bei dem der in ein neues Dokument eingefügte Text manchmal eine falsche Textausrichtung aufwies.
- Ein Problem wurde behoben, bei dem einige Benutzer nach dem Sperren des Computers keine Änderungen mehr speichern konnten.
- Es wurde ein Problem behoben, bei dem in bestimmten Fällen statt des ausgewählten Bereichs das komplette Dokument gedruckt wurde.
- Ein Problem wurde behoben, durch das Kommentare auf kleineren Displays schwer zu lesen waren.
- Ein Problem wurde behoben, durch das beim Erfassen von Daten auf einem Gerät ein Absturz verursacht werden konnte.

### <a name="excel"></a>Excel
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="powerpoint"></a>PowerPoint
- Ein Problem wurde behoben, bei dem der Tastaturfokus manchmal schwierig zu erkennen war.

### <a name="outlook"></a>Outlook
- Ein Problem wurde behoben, bei dem ein Add-In möglicherweise als aktiviert angezeigt wurde, auch wenn es nicht aktiviert war.
- Ein Problem wurde behoben, das dazu führte, dass einem Kunden möglicherweise nicht alle Aufbewahrungsrichtlinien angezeigt wurden, wenn sehr viele Aufbewahrungsrichtlinien vorhanden waren.

### <a name="access"></a>Access
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="project"></a>Project
- Verschiedene Korrekturen der Leistung und Stabilität

</BR></BR>

## <a name="june-14-2019"></a>14. Juni 2019
Version 1907 (build 11807.20000)

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="word"></a>Word 
- Es wurde ein Problem behoben, durch das Benutzer sich beim Speichern auf OneDrive nicht anmelden konnten.
- Ein Problem wurde behoben, bei dem Benutzer daran gehindert werden konnten, SharePoint-Eigenschaften im eingeschränkten Zugriffsmodus zu ändern.
- Es wurde ein Problem behoben, bei dem sich die Kopf- und Fußzeileninhalte beim Anpassen von Seitenrändern ändern konnten.
- Es wurde ein Problem behoben, bei dem die Formatierung beim Umschalten in die Webansicht unterbrochen wurde.
- Es wurde ein Problem behoben, durch das Benutzer daran gehindert werden konnten, benutzerdefinierte Felder beim Öffnen von SharePoint zu verwenden.

### <a name="excel"></a>Excel
- Ein Leistungsproblem wurde behoben, das beim Löschen von Zeilen einer gefilterten Gruppe auftrat.
- Es wurde ein Problem behoben, das manchmal dazu führte, dass die Maus in der geschützten Anzeige flackert.
- Wir haben ein Problem behoben, das beim Löschen einer Reihe zu einem Absturz führen konnte.
- Ein Problem wurde behoben, bei dem einige Benutzer die Möglichkeit hatten, Versionsverlauf hinzuzufügen, wenn diese Option nicht verfügbar war.
- Wir haben ein Problem behoben, das bei Verwendung des Tools „Arbeitsblattabgleich“ eine Ausnahme verursacht hat.

### <a name="powerpoint"></a>PowerPoint
- Wir haben ein Problem behoben, durch das ein Absturz beim Klicken auf einen Link zu SharePoint verursacht werden konnte.
- Wir haben ein Problem behoben, durch das der Benutzer zur nächsten Seite wechseln konnte, während er mit einem Surface-Stift tippte.

### <a name="outlook"></a>Outlook
- Ein Problem wurde behoben, bei dem in manchen Fällen das Feld „An“ größer als normal war.

### <a name="access"></a>Access
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="project"></a>Project
- Verschiedene Korrekturen der Leistung und Stabilität

</BR></BR>

## <a name="june-7-2019"></a>7. Juni 2019
Version 1907 (Build 11727.20064)

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="word"></a>Word 
- Ein Problem wurde behoben, bei dem Word manchmal abstürzt, wenn die AutoKorrektur so eingerichtet wurde, dass der erste Buchstabe eines Satzes groß geschrieben wird.
- Die Leistung beim Bearbeiten eines Dokuments in SharePoint wurde verbessert
- Ein Problem wurde behoben, bei dem vektorbasierte Bilder, die in Adobe Illustrator erstellt wurden, nicht ordnungsgemäß angezeigt wurden.

### <a name="excel"></a>Excel
- Ein Problem wurde behoben, bei dem die Sortierfelder beim Aufzeichnen eines Makros manchmal nicht ordnungsgemäß festgelegt wurden.
- Ein Problem wurde behoben, das beim Neuberechnen einer Arrayformel ein Hängen oder einen Absturz verursacht.

### <a name="powerpoint"></a>PowerPoint
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="outlook"></a>Outlook
- Ein Problem wurde behoben, bei dem Inline-Anlagen manchmal nicht ordnungsgemäß skaliert wurden.

### <a name="access"></a>Zugriff
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="project"></a>Project
- Ein Problem wurde behoben, bei dem Zeittabellen mit festgelegter Dauer manchmal den Endtermin der Aufgabe ändern konnten.
- Ein Problem wurde behoben, bei dem die Werte für den Prozentsatz der Komplettierung beim Öffnen eines Projekts aus einer früheren Version falsch sein konnten.

</BR></BR>

## <a name="may-31-2019"></a>31. Mai 2019
Version 1906 (build 11722.20008)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="outlook"></a>Outlook

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a>Das Dialogfeld zum Kontaktieren des Supports ist jetzt andockbar und wird auf der rechten Seite angezeigt

Das zum Kontaktieren des Supports verwendete Dialogfeld wird jetzt in einem Bereich auf der rechten Seite angezeigt und beginnt als angedocktes Fenster.

#### <a name="ink-in-your-email"></a>Freihand in Ihrer E-Mail!

Sie können Bilder jetzt in Ihren Outlook-E-Mails zeichnen und kommentieren.

### <a name="word"></a>Word

#### <a name="open-document-links-in-word"></a>Öffnen von Dokument-Links in Word

Wenn Sie in Office auf einen Dokument Link klicken, können Sie Ihre Einstellungen dahingehend aktualisieren, dass er standardmäßig in der Word-App geöffnet wird.  Um Ihre Einstellungen zu aktualisieren, wechseln Sie zu Datei > Optionen – > Erweitert-> Verhalten von Links. Weitere Informationen: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>Erste Schritte:

Das Feature wird standardmäßig auf aus eingestellt. Benutzer können es entweder über Optionen > Erweitert > Verhalten von Links aktivieren, oder sie können ihm zustimmen, wenn Sie von Win32-WXP-Apps durch eine Opt-In-Umgebung geleitet werden.
Links werden standardmäßig in der entsprechenden Office-Anwendung anstelle des Browsers geöffnet, wenn Benutzer in Outlook, Word, PowerPoint oder Excel auf Links zu Word/PowerPoint/Excel-Dateien klicken, die auf OneDrive, OneDrive für Business oder in SharePoint gespeichert sind.

Um diese Standardeinstellung zu ändern, können Benutzer die folgende Einstellung in Outlook/Word/Excel/PowerPoint aktualisieren:

Datei –> Optionen –> Erweitert –> Verhalten von Links.

Diese Einstellung ist für Outlook/Word/PowerPoint/Excel freigegeben und kann in jeder dieser Apps festgelegt werden.

##### <a name="scenarios-to-try"></a>Szenarien zum Ausprobieren:

Lösen Sie die Opt-in-Benutzererfahrung aus – öffnen eines Links zu einem Word-Dokument, das in OneDrive/SharePoint aus Outlook/Word/PowerPoint/Excel aus gespeichert ist – klicken Sie aus Office Online auf in Client öffnen – tun Sie dies zwei Mal in einem Zeitraum von 30 Tagen. Nachdem Sie die Einstellung gesetzt haben, werden Links standardmäßig in den Win32-Apps gestartet.

### <a name="powerpoint"></a>PowerPoint

#### <a name="open-presentation-links-in-powerpoint"></a>Öffnen Sie Präsentationslinks in PowerPoint

Wenn Sie in Office auf einen Präsentationslink klicken, können Sie Ihre Einstellungen dahingehend aktualisieren, dass er standardmäßig in der PowerPoint-App geöffnet wird. Um Ihre Einstellungen zu aktualisieren, wechseln Sie zu Datei > Optionen – > Erweitert-> Verhalten von Links. Weitere Informationen: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>Erste Schritte:

Das Feature wird standardmäßig auf aus eingestellt. Benutzer können es entweder über Optionen > Erweitert > Verhalten von Links aktivieren, oder sie können ihm zustimmen, wenn Sie von Win32-WXP-Apps durch eine Opt-In-Umgebung geleitet werden.
Links werden standardmäßig in der entsprechenden Office-Anwendung anstelle des Browsers geöffnet, wenn Benutzer in Outlook, Word, PowerPoint oder Excel auf Links zu Word/PowerPoint/Excel-Dateien klicken, die auf OneDrive, OneDrive für Business oder in SharePoint gespeichert sind.

Um diese Standardeinstellung zu ändern, können Benutzer die folgende Einstellung in Outlook/Word/Excel/PowerPoint aktualisieren:

Datei –> Optionen –> Erweitert –> Verhalten von Links.

Diese Einstellung ist für Outlook/Word/PowerPoint/Excel freigegeben und kann in jeder dieser Apps festgelegt werden.

##### <a name="scenarios-to-try"></a>Szenarien zum Ausprobieren:

Lösen Sie die Opt-in-Benutzererfahrung aus – öffnen eines Links zu einer PowerPoint-Präsentation, die in OneDrive/SharePoint aus Outlook/Word/PowerPoint/Excel aus gespeichert ist – klicken Sie aus Office Online auf in Client öffnen – tun Sie dies zwei Mal in einem Zeitraum von 30 Tagen. Nachdem Sie die Einstellung gesetzt haben, werden Links standardmäßig in den Win32-Apps gestartet.

### <a name="excel"></a>Excel

#### <a name="open-workbook-links-in-excel"></a>Öffnen von Arbeitsmappen-Links in Excel

Wenn Sie in Office auf einen Link zu einer Arbeitsmappe klicken, können Sie Ihre Einstellungen dahingehend aktualisieren, dass diese standardmäßig in der Excel-App geöffnet wird. Um Ihre Einstellungen zu aktualisieren, wechseln Sie zu Datei > Optionen – > Erweitert-> Verhalten von Links. Weitere Informationen: https://support.office.com/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>Erste Schritte:

Das Feature wird standardmäßig auf aus eingestellt. Benutzer können es entweder über Optionen > Erweitert > Verhalten von Links aktivieren, oder sie können ihm zustimmen, wenn Sie von Win32-WXP-Apps durch eine Opt-In-Umgebung geleitet werden.
Links werden standardmäßig in der entsprechenden Office-Anwendung anstelle des Browsers geöffnet, wenn Benutzer in Outlook, Word, PowerPoint oder Excel auf Links zu Word/PowerPoint/Excel-Dateien klicken, die auf OneDrive, OneDrive für Business oder in SharePoint gespeichert sind.

Um diese Standardeinstellung zu ändern, können Benutzer die folgende Einstellung in Outlook/Word/Excel/PowerPoint aktualisieren:

Datei –> Optionen –> Erweitert –> Verhalten von Links.

Diese Einstellung ist für Outlook/Word/PowerPoint/Excel freigegeben und kann in jeder dieser Apps festgelegt werden.

##### <a name="scenarios-to-try"></a>Szenarien zum Ausprobieren:

Lösen Sie die Opt-in-Benutzererfahrung aus – öffnen eines Links zu einer Excel-Arbeitsmappe, die in OneDrive/SharePoint aus Outlook/Word/PowerPoint/Excel aus gespeichert ist – klicken Sie aus Office Online auf in Client öffnen – tun Sie dies zwei Mal in einem Zeitraum von 30 Tagen. Nachdem Sie die Einstellung gesetzt haben, werden Links standardmäßig in den Win32-Apps gestartet.

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="all"></a>Alle
- Wir haben ein Problem behoben, durch das Dateien manchmal automatisch gespeichert wurden, auch wenn die automatische Speicherung deaktiviert wurde.

### <a name="word"></a>Word 
- Wir haben ein Problem behoben, das einige Benutzer daran gehindert hat, auf SharePoint zu speichern.

### <a name="excel"></a>Excel
- Ein Problem wurde behoben, bei dem ein falsches Symbol für inaktive Filter angezeigt werden konnte.

### <a name="powerpoint"></a>PowerPoint
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="outlook"></a>Outlook
- Ein Problem wurde behoben, bei dem einige Benutzer in einer Gruppen-Planungsanzeige fälschlicherweise als offline angezeigt wurden
- Wir haben ein Problem behoben, das verhindert, dass SafeLink eine URL mit einem nachgestellten Leerzeichen analysiert
- Ein Problem wurde behoben, bei dem Räume außerhalb der arbeitsfreien Zeiten als verfügbar angezeigt wurden

### <a name="access"></a>Zugriff
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="project"></a>Project
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

</BR></BR>

## <a name="may-24-2019"></a>24. Mai 2019
Version 1906 (build 11715.20002)

## <a name="whats-new"></a>Neuigkeiten:

#### <a name="user-experience-updates"></a>Updates für die Benutzeroberfläche

Updates, die als „Bald verfügbar“ angezeigt wurden, sind jetzt verfügbar. Dazu gehört das vereinfachte Menüband sowie ein überarbeitetes Design für den Ordnerbereich, die Nachrichtenliste und den Lesebereich.

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="all"></a>Alle

- Ein Problem wurde behoben, bei dem der Chat-Bereich nicht angezeigt wurde

### <a name="word"></a>Word 
- Ein Problem wurde behoben, bei dem in manchen Fällen Text fälschlicherweise als Grammatikfehler hervorgehoben werden konnte.

### <a name="excel"></a>Excel
- Ein Problem wurde behoben, bei dem ein falsches Symbol für Diagrammelemente verwendet wurde
- Ein Problem wurde behoben, bei dem die falsche Arbeitsmappe in einem VBA-Skript aktiviert werden konnte, wenn die gleiche Mappe bereits geöffnet war.

### <a name="powerpoint"></a>PowerPoint
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="outlook"></a>Outlook
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="access"></a>Access
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="project"></a>Project
- Ein Problem wurde behoben, bei dem das Projekt nach dem Wechsel zur Taskleiste abstürzen konnte.

</BR></BR>

## <a name="may-17-2019"></a>17. Mai 2019
Version 1906 (Build 11708.20006)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="outlook"></a>Outlook

#### <a name="user-experience-updates"></a>Updates für die Benutzeroberfläche

Updates, die als „Bald verfügbar“ angezeigt wurden, sind jetzt verfügbar. Dazu gehört das vereinfachte Menüband sowie ein überarbeitetes Design für den Ordnerbereich, die Nachrichtenliste und den Lesebereich.

##### <a name="getting-started"></a>Erste Schritte:

Diese Änderungen sind Bestandteil der neuen Standardbenutzeroberfläche. Sie waren bereits seit Mitte Dezember zu 100% verfügbar, jedoch nur bei Aktivierung des Schalters „in Kürze verfügbar“.

#### <a name="customizable-simplified-ribbon"></a>Anpassbares vereinfachtes Menüband

Sie können einfach zwischen klassischer und vereinfachter Ansicht sowie den Befehlen "Anheften" und "Lösen" wechseln.

##### <a name="getting-started"></a>Erste Schritte:

Benutzer können zum vereinfachten Menüband wechseln, indem Sie zuerst „in Kürze verfügbar“ einschalten und dann auf das Chevron im Menüband klicken, um zwischen dem klassischen, mehrzeiligen Menüband und dem neuen, vereinfachten, einreihigen Menüband zu wechseln.

##### <a name="scenarios-to-try"></a>Mögliche Szenarien:

Wechseln zwischen dem klassischen Menüband und dem vereinfachten Menüband

#### <a name="pick-your-favorite-action"></a>Wählen Sie Ihre bevorzugte Aktion aus

Sie möchten „Kennzeichnen“ und „Löschen“ nicht verwenden? Wie sieht es mit „Archivieren“ oder „Als gelesen markieren2 aus? Passen Sie das Menü mit schnellen Aktionen mit den am häufigsten verwendeten Befehlen an.

##### <a name="getting-started"></a>Erste Schritte:

Wenn Sie Ihre schnellen Aktionen auswählen möchten, klicken Sie mit der rechten Maustaste auf eine e-Mail in der Nachrichtenliste, um das Kontextmenü aufzurufen. Klicken sie dann auf „Schnelle Aktionen festlegen...“.

##### <a name="scenarios-to-try"></a>Mögliche Szenarien:

Ändern der Standardeinstellungen von „Kennzeichnen“ und „Löschen“ in „Archivieren“, „Bewegen“, „als gelesen markieren" oder "keine" für eine übersichtlichere Nachrichtenliste

#### <a name="relaxed-or-tighter-layout-you-choose"></a>Aufgelockertes oder engeres Layout? Sie haben die Wahl!

Sie können entscheiden, ob Sie zwischen Elementen mehr Abstand wünschen oder ob Sie mehr Elemente in einem engeren Layout bevorzugen.

##### <a name="getting-started"></a>Erste Schritte:

In der Registerkarte „Ansicht“ das Kontrollkästchen „engere Abstände" aktivieren. Zu finden in „Nachrichten“ im klassischen Menüband; in „Aktuelle Ansichtseinstellungen“ im vereinfachten Menüband.

##### <a name="scenarios-to-try"></a>Mögliche Szenarien:

Verwenden Sie Outlook, um e-Mail-Nachrichten zu selektieren und zu schreiben, ohne die Einstellung zu aktivieren. Bei Verwendung von „engere Abstände“ werden mehr Nachrichten pro Seite angezeigt, und die Steuerelemente in den Ansichten „Verfassen“ sind übersichtlicher.

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a>Deduplizieren von MRU-Einträgen bei Verwendung des Onedrive-Synchronisierungs Clients

Bessere Integration des OneDrive-Synchronisierungsclients mit Cloud-Anlagen durch Deduplizierung der MRU-Einträge und Aktivieren des schnelleren Anfügens als Kopierverhalten für synchronisierte Daten

##### <a name="getting-started"></a>Erste Schritte:

Wenn Sie den OneDrive-Synchronisierungsclient verwenden, werden in den „Datei anfügen“-MRU-Einträgen keine Dateiduplikate mehr angezeigt.

##### <a name="scenarios-to-try"></a>Mögliche Szenarien:

Aktivieren des OneDrive-Synchronisierungsclients und Verwenden des Menüs „Datei anfügen“ in der Outlook-Desktopanwendung

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a>Verbesserte Synchronisierung von freigegebenen Ordnern für Postfächer mit vielen Ordnern

Seit Jahren ist Outlook beim Synchronisieren von freigegebenen Postfächern auf maximal 500 Ordner beschränkt. Mit dieser Änderung wurde Outlook so verbessert, dass es auf eine Weise synchronisiert wird, die dieser Beschränkung auf 500 Ordner nicht mehr unterliegt.

##### <a name="getting-started"></a>Erste Schritte:

Erstellen Sie in einem Postfach 1000 Ordner, geben Sie einer anderen Person Zugriff auf das Postfach, erstellen Sie ein Outlook-Profil für diese andere Person, und vergewissern Sie sich, dass die Synchronisierung funktioniert.

### <a name="word"></a>Word

#### <a name="erase-just-a-little-bit"></a>Nur ein wenig löschen

##### <a name="getting-started"></a>Erste Schritte:

Wechseln Sie zur Registerkarte „Zeichnen“, und wählen Sie die Dropdownliste „Radierer“ aus. Wählen Sie den kleinen Radierer oder den mittleren Radierer aus.

##### <a name="scenarios-to-try"></a>Mögliche Szenarien:

Wechseln Sie zur Registerkarte „Zeichnen“, und wählen Sie einen Stift aus. Zeichnen Sie einen Strich. Wählen Sie die Dropdownliste „Radierer“ aus. Wählen Sie den kleinen Radierer oder den mittleren Radierer aus. Radieren Sie nur Teile des Striches aus.

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="all"></a>Alle 
- Wir haben ein Problem behoben, welches einige Nutzer daran hindern konnte eine PDF-Datei zu speichern.
- Wir haben ein Problem behoben, welches sich auf Nutzer ausgewirkt hat, die große Dateien auf einem 32-Bit System speicherten.

### <a name="word"></a>Word 
- Die Reaktionsfähigkeit des Diktat-Features wurde erheblich verbessert.

### <a name="excel"></a>Excel
- Wir haben ein Problem behoben, bei dem Doppelklick-Ereignisse auf Touchscreen-Geräten fehlschlagen konnten.
- Wir haben ein Problem behoben, welches einige Nutzer daran hindern konnte VBA Makros zu bearbeiten.
- Wir haben ein Problem behoben, welches sich auf die Performance bei der Nutzung von Slicers auswirken konnte.

### <a name="powerpoint"></a>PowerPoint
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="outlook"></a>Outlook
- Es wurde ein Problem behoben, bei dem statt der ausgewählten Vorlage eine falsche angezeigt wurde.

### <a name="access"></a>Access
- Wir haben ein Problem behoben, bei dem bei der Verwendung von Zoom Builder zum Anzeigen langer Rich Text schwer lesbar sein konnte.

### <a name="project"></a>Projekt
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

</BR></BR>

## <a name="may-10-2019"></a>10. Mai 2019
Version 1906 (Build 11702.20000)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="outlook"></a>Outlook

**Mehr Nachrichten am Bildschirm anzeigen:** Wählen Sie „Anzeigen“ > Engere Abstände verwenden, um die Abstände zwischen den Nachrichten anzupassen.

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="all"></a>Alle
- Ein Problem wurde behoben, bei dem im Dialogfeld "Speichern unter" manchmal ein falscher Pfad angezeigt wurde.

### <a name="word"></a>Word 
- Ein Problem wurde behoben, bei dem einige Auswahloptionen aus der Funktion "Was möchten Sie tun?" nicht eingefügt wurden.

### <a name="excel"></a>Excel
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="powerpoint"></a>PowerPoint
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="outlook"></a>Outlook
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="access"></a>Access
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="project"></a>Project
- Ein Problem wurde behoben, bei dem Aufgaben-IDs manchmal nur angezeigt wurden, wenn sie markiert wurden.

</BR></BR>

## <a name="may-3-2019"></a>3. Mai 2019
Version 1906 (Build 11629.20008)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="outlook"></a>Outlook

**Alle Verschlüsselungsoptionen an einem zentralen Ort:** Gehen Sie einfach zu „Optionen“ > „Verschlüsseln“, um auszuwählen, wie Ihre E-Mail-Nachricht gesichert werden soll.

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="all"></a>Alle
- Ein Problem wurde behoben, bei dem bei einigen Benutzern Probleme beim Synchronisieren mit OneDrive for Business auftraten.

### <a name="word"></a>Word 
- Ein Problem wurde behoben, bei dem Word in einigen Fällen sehr lange zum Starten brauchte.

### <a name="excel"></a>Excel
- Ein Problem wurde behoben, bei dem externe Links nach dem Upgrade auf eine neuere Version von Excel manchmal aus Arbeitsmappen entfernt wurden.
- Ein Problem wurde behoben, bei dem einige Benutzern Schwierigkeiten beim Auswählen von Zellen in einer neuen Arbeitsmappen hatten.

### <a name="powerpoint"></a>PowerPoint
- Ein Problem wurde behoben, bei dem Schriftgrade beim Konvertieren von Freihandzeichnungen in Text nicht konsistent waren.

### <a name="outlook"></a>Outlook
- Ein Problem wurde behoben, bei dem das Speichern eines Kontakts aus einer VCF-Datei zu leeren Feldern führen konnte.
- Ein Problem wurde behoben, bei dem eine Nachricht im Ordner "Postausgang" stecken blieb, obwohl sie gesendet wurde.
- Ein Problem wurde behoben, bei dem Outlook beim Anzeigen einer DRM-Meldung abstürzte.

### <a name="access"></a>Access
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="project"></a>Project
- Ein Problem wurde behoben, bei dem der Editor von Chinesisch auf Englisch wechselte.
- Ein Problem wurde behoben, bei dem unveröffentlichte Aufgaben manchmal in der veröffentlichten Kopie eines Hauptprojekts angezeigt wurden.

</BR></BR>

## <a name="april-26-2019"></a>26. April 2019
Version 1905 (Build 11617.20002)

## <a name="new-features"></a>Neue Features

### <a name="outlook"></a>Outlook

**Aktualisierungen freigebender Kalender funktionieren jetzt noch schneller:** Outlook ist in der Lage, freigegebene Kalender in Office 365 mithilfe der REST API zu aktualisieren. Aktivieren Sie die Vorschau, um schnellere und zuverlässigere Aktualisierungen für freigegebene Kalender zu erhalten.

### <a name="excel"></a>Excel

#### <a name="coauthoring-improvements"></a>Verbesserungen bei der gemeinsamen Dokumenterstellung

Die gemeinsame Dokumenterstellung wurde verbessert, indem Inhaltsänderungen den anderen Benutzern nun nahezu immer in Echtzeit angezeigt werden.

### <a name="visio"></a>Visio

- **Exportieren von Visio-Visualisierungen aus Power BI:** Die Visio-Visualisierung für Power BI wird nun ordnungsgemäß angezeigt, wenn Sie Power BI-Berichte beispielsweise als PDF-Dateien, PowerPoint-Dateien und mehr exportieren.

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="word"></a>Word 
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="excel"></a>Excel
- Wir haben ein Problem behoben, bei dem Solver-Makros nicht ausgeführt werden konnten
- Wir haben ein Problem behoben, das den Import von Excel-Dateien in SharePoint verhindern konnte

### <a name="powerpoint"></a>PowerPoint
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="outlook"></a>Outlook
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="access"></a>Access
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="project"></a>Project
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

</BR></BR>

## <a name="april-19-2019"></a>19. April 2019
Version 1905 (Build 11609.20002)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="outlook"></a>Outlook

**Erhalten Sie E-Mail-Vorschläge, wenn Sie nach einer Person suchen:** Wenn Sie den Namen einer Person im Suchfeld eingeben, werden die relevantesten E-Mail-Nachrichten in die Ihnen gezeigten Suchvorschläge einbezogen.

### <a name="excel"></a>Excel

#### <a name="improved-filled-maps-experience-using-data-types"></a>Verbesserte Benutzererfahrung für ausgefüllte Karten durch die Verwendung von Datentypen

Dieses Feature ist eine Verbesserung für Benutzer, die ausgefüllte Kartendiagramme mithilfe der geografischen Datentypen von Excel darstellen. Der Vorteil für den Endbenutzer besteht in einer umfangreicheren Integration zwischen den Features und einer höheren Genauigkeit des Bereichs, den der Endbenutzer zuordnen möchte. Weitere Vorteile: Zuordnen von Stadt-Polygonen

##### <a name="getting-started"></a>Erste Schritte:

- Dieses Feature ist eine Verbesserung der vorhandenen Funktionen in Excel. Verwenden der Verbesserung: Konvertieren Sie Orte in Rich-Entitäten und stellen Sie sie durch ausgefüllte Karten dar. 

##### <a name="scenarios-to-try"></a>Mögliche Szenarien:

- Benutzer können Städte, Staaten, Landkreise, Länder und Postleitzahlen zuordnen. 


## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="all-applications"></a>Alle Anwendungen
- Es wurde ein Fehler behoben, bei dem der Dialog der ersten Ausführung beim Start einer Anwendung immer angezeigt wurde.
- Es wurde ein Problem behoben, bei dem ein SharePoint-Link im Dialogfeld "Speichern unter" in manchen Fällen nicht vorhanden war.
- Es wurde ein Fehler behoben, bei dem Benutzern fälschlicherweise der Dialog "Jetzt reparieren" angezeigt wurde.

### <a name="word"></a>Word 
- Es wurde ein Fehler behoben, bei dem einige Benutzer beim Anfordern einer Schriftart die Fehlermeldung erhielten, dass nicht genügend Arbeitsspeicher oder Speicherplatz vorhanden sei.
- Es wurde ein Fehler behoben, bei dem ein Fenster beim Umschalten vom Bereich "Kommentare" unscharf wurde.

### <a name="excel"></a>Excel
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="powerpoint"></a>PowerPoint
- Es wurde ein Fehler behoben, der bewirkte, dass die Größe von Formen mit Branding nicht angepasst werden konnte.
- Es wurde ein Fehler behoben, bei dem PowerPoint abstürzen konnte, wenn eine Datei im geschützten Ansichtsmodus geöffnet wurde.

### <a name="outlook"></a>Outlook
- Wir haben ein Problem behoben, aufgrund dessen einige Benutzer keine chinesischen Wörter auswählen konnten.
- Wir haben ein Problem behoben, bei dem Ablaufdaten nicht korrekt berechnet wurden.

### <a name="access"></a>Access
- Wir haben ein Problem behoben, aufgrund dessen einige Benutzer nicht den Makro-Generator benutzen konnten.
- Wir haben ein Problem behoben, aufgrund dessen beim Drucken eines Berichts nur die erste Seite ausgedruckt wurde.
- Es wurde ein Problem behoben, bei dem die Anwendung beim Fahren über einen Hyperlink abstürzen konnte.
- Wir haben ein Problem behoben, das bewirkte, dass in der Ansicht "Beziehungen" einige Elemente außerhalb des Fensters angezeigt wurden.

### <a name="project"></a>Project
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

</BR></BR>

## <a name="april-12-2019"></a>12. April 2019
Version 1905 (Build 11601.20042)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="access"></a>Access

#### <a name="get-smart-with-microsoft-graph"></a>Intelligenter mit Microsoft Graph

Importieren oder verlinken Sie intelligente Daten, und erfinden Sie Ihre Desktopdatenbank mit intelligenter Technologie neu.

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="all-applications"></a>Alle Anwendungen
 - Wir haben ein Problem behoben, aufgrund dessen einige Benutzer Dateien nicht an Cloudspeicherorten speichern konnten.
 - Wir haben ein Problem behoben, bei dem der falsche Bereich auf dem Menüband geöffnet wurde.

### <a name="word"></a>Word 
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="excel"></a>Excel
- Wir haben ein Problem behoben, bei dem eine Fehlermeldung aufgrund verknüpfter Datentypen für Benutzer angezeigt wird, wenn die Arbeitsmappe keine verknüpften Datentypen enthält.
- Wir haben ein Problem behoben, bei dem sich URL-Links innerhalb eines Word-Dokuments ändern, wenn diese lokal und nicht online angezeigt werden.

### <a name="powerpoint"></a>PowerPoint
- Wir haben ein Problem behoben, bei dem die Anwendung nach dem Rückgängigmachen von Änderungen auf der Registerkarte „Animationen“ abstürzte.

### <a name="outlook"></a>Outlook
- Wir haben ein Problem behoben, aufgrund dessen einige Benutzer das Feld „Notizen“ für Kontakt in einem öffentlichen Ordner nicht bearbeiten konnten.
- Wir haben ein Problem behoben, bei dem ein Konflikt zwischen den Ablaufdatumsangaben und den Löschdatumsangaben auftrat.

### <a name="access"></a>Access
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="project"></a>Project
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

</BR></BR>

## <a name="april-5-2019"></a>5. April 2019
Version 1904 (Build 11527.20014)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="outlook"></a>Outlook

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a>Outlook für Windows: Festlegen und Teilen Ihrer Einstellungen für „Posteingang mit Relevanz"

Ihre Einstellungen für "Posteingang mit Relevanz" werden in der Cloud gespeichert, sodass Sie auf jedem verwendeten Computer die gleiche konsistente Umgebung für Outlook für Windows und Outlook im Web erhalten.

#### <a name="getting-started"></a>Erste Schritte:

Unter „Datei" > „Optionen" > Registerkarte „Allgemein" gibt es eine neue Einstellung für „Meine Outlook-Einstellungen in der Cloud speichern". Benutzer müssen das Kontrollkästchen aktivieren, damit ihre Einstellungen für "Posteingang mit Relevanz" für andere Desktopinstallationen von Outlook und OWA übernommen werden.

#### <a name="scenarios-to-try"></a>Mögliche Szenarien:

Ändern Sie auf dem Computer, auf dem die Einstellung für die Cloudeinstellungen aktiviert ist, den Posteingang mit Priorität. Navigieren Sie zu OWA, und sehen Sie sich die dort angewendete Einstellung an. Ändern Sie den „Posteingangs mit Relevanz“ in OWA und starten Sie Outlook für Desktop, um die Einstellungen anzuzeigen.

### <a name="word"></a>Word

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a>Der Modus „Lerntools" unterstützt weitere Seitenfarben.

Lerntools in Word unterstützt weitere Farben für Seitendesigns, wodurch die Hintergrundfarbe der Seite geändert werden kann.  Für viele Personen ist es schwierig bei einem vollen weißen oder schwarzen Hintergrund zu lesen, deshalb haben wir die Auswahl von Farben in Word auf PC und Mac erweitert.

#### <a name="getting-started"></a>Erste Schritte:

Um dies auszuprobieren, wechseln Sie zur Registerkarte „Anzeige", und wählen Sie „Lerntools", dann „Seitenfarbe" aus.

#### <a name="scenarios-to-try"></a>Mögliche Szenarien:

Um dies auszuprobieren, wechseln Sie zur Registerkarte „Anzeige", und wählen Sie „Lerntools", dann „Seitenfarbe" aus.

### <a name="excel"></a>Excel

#### <a name="elevate-creativity-with-animated-3d-models"></a>Kreativität durch animierte 3D-Modelle steigern

Office unterstützt jetzt animierte Modelle, die im Editor wiedergegeben werden, damit Sie Ihre Arbeitsblätter zum Leben erwecken können!

#### <a name="getting-started"></a>Erste Schritte:

1. Öffnen Sie Excel
2. Fügen Sie ein animiertes 3D-Modell ein (demnächst in Remix verfügbar, bereits jetzt können Sie hier auf animierte Modelle zugreifen: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art)
3. Das animierte Modell wird im Editor wiedergegeben! Wechseln Sie in den Bildschirmpräsentationsmodus – es wird auch dort wiedergegeben werden!
4. Im Menüband 3D-Format finden Sie noch weitere animierte Szenen.

#### <a name="scenarios-to-try"></a>Mögliche Szenarien:

1. Fügen Sie ein 3D-Modell ein und betrachten Sie dessen Animation im Editor.
2. Entdecken Sie die im animierten Modell verfügbaren Animationsszenen in der Szenengalerie, zu finden im Menüband 3D-Format
3. Die Animation kann ganz einfach über das Menüband, den Floatie oder die Leertaste wiedergegeben oder pausiert werden.

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="all-applications"></a>Alle Anwendungen
- Wir haben ein Problem behoben, bei dem das Symbol für eine falsche App für Excel in Kontextmenüs nicht ordnungsgemäß angezeigt wurde.
- Wir haben ein Problem behoben, bei dem die Menüschaltfläche „Datei“ nach der Installation eines Updates nicht angezeigt wurde.
- Wir haben ein Problem behoben, bei dem Ihre Benutzerlizenz geändert wurde.

### <a name="word"></a>Word 
- Wir haben ein Problem behoben, bei dem Text auf bestimmten Zoomebenen nicht richtig gerendert wurde.

### <a name="excel"></a>Excel
- Wir haben ein Problem behoben, bei dem Benutzer nicht aufgefordert wurden, eine Arbeitsmappe nach Änderungen zu speichern.
- Wir haben ein Problem behoben, bei dem ein BeforeSave-Ereignis nicht ausgelöst wurde, wenn der Benutzer die Arbeitsmappe teilte.
- Wir haben ein Problem behoben, bei dem das Ändern der Größe einer Spalte auf weniger als 6 Pixel eine falsche Fehlermeldung ausgab.
- Wir haben ein Problem behoben, bei dem Excel das Application.Visible-Kennzeichen ignorierte.
- Wir haben ein Problem behoben, bei dem Ablaufverfolgungspfeile auf nicht aktiven fixierten Fenstern bestehen blieben.
- Wir haben ein Problem behoben, bei dem sich die Zellenformatierung von Datumsangaben und Währung beim Öffnen einer Arbeitsmappe änderte.
- Wir haben ein Problem behoben, bei dem Tooltips sich unerwartet verschoben.
- Wir haben Lokalisierungsprobleme für den Power Query-Editor behoben.
- Wir haben ein Problem behoben, bei dem eine Arbeitsmappe als Anlage beim Senden per E-Mail entfernt wurde.

### <a name="powerpoint"></a>PowerPoint
- Wir haben ein Problem behoben, bei dem das Kopieren von Shapes länger als erwartet dauerte.

### <a name="outlook"></a>Outlook
- Wir haben ein Problem behoben, bei dem Outlook bei der Verwendung des Zeichnungstools abstürzte.
- Wir haben ein Lokalisierungsproblem beim Verfassen von HTML-E-Mails behoben.
- Wir haben ein Problem behoben, bei dem Benutzer Schwierigkeiten bei der Auswahl des unteren Fensterbereichs hatten.

### <a name="access"></a>Access
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="project"></a>Project
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

</BR></BR>

## <a name="march-22-2019"></a>22. März 2019
Version 1904 (Build 11514.20004)

## <a name="new-features"></a>Neue Features

- **Kontrollmechanismen für den Datenschutz:** Neue aktualisierte und verbesserte Kontrollmechanismen für Diagnosedaten und verbundene Oberflächen. Weitere Informationen <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json>

- **Office-Symbole mit neuem Look:** Die Office-Symbole wurden neu gestaltet, um die einfache, leistungsstarke und intelligente Office-Benutzeroberfläche widerzuspiegeln.

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="word"></a>Word 
- Ein Problem wurde behoben, bei dem die Benutzeroberfläche ständig "Überprüfung auf Änderungen" anzeigt.

### <a name="excel"></a>Excel
- Ein Problem wurde behoben, bei dem die Anwendung nach dem Verschieben eines Arbeitsblattes abstürzte.
- Ein Problem wurde behoben, bei dem die Anwendung nach dem Speichern im PDF-Format abstürzte.
- Ein Problem wurde behoben, bei dem das Dialogfeld "Speichern" einige koreanische Zeichen nicht akzeptierte.

### <a name="powerpoint"></a>PowerPoint
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="outlook"></a>Outlook
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="access"></a>Access
- Die Fehlermeldung in Access wurde korrigiert, bei der eine zusätzliche Verknüpfung zu Access erstellt wurde.
- Ein Problem wurde behoben, bei dem Daten aus einem verlinkten SharePoint falsch angezeigt wurden.

### <a name="project"></a>Project
- Ein Problem wurde behoben, bei dem die Spracheinstellungen von Chinesisch auf Englisch wechselten.
- Ein Problem wurde behoben, bei dem die Anwendung beim Synchronisieren mit SharePoint abstürzen konnte.

</BR></BR>

## <a name="march-15-2019"></a>15. März 2019
Version 1904 (Build 11504.20000)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="word"></a>Word

#### <a name="focus-mode"></a>Fokusmodus

Wechseln Sie im Menü Ansicht in den Fokusmodus, damit Sie nicht abgelenkt werden und sich auf Ihre Arbeit konzentrieren können. Nur für Abonnenten von Office 365.

#### <a name="getting-started"></a>Erste Schritte:

Zugriff durch Schaltfläche „Fokus" auf der Registerkarte „Anzeige".

#### <a name="scenarios-to-try"></a>Mögliche Szenarien:

Schalten Sie den Fokusmodus ein und erleben Sie die fokussierte Benutzererfahrung

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="word"></a>Word 
- Ein Problem wurde behoben, bei dem Bilder in einem als PDF-Datei gespeicherten Dokument den falschen DPI-Wert aufweisen.

### <a name="excel"></a>Excel
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="powerpoint"></a>PowerPoint
- Ein Problem wurde behoben, bei dem der Bereich "Kommentare" sich nicht ordnungsgemäß öffnet oder schließt.
- Ein Problem wurde behoben, bei dem die Anwendung beim Löschen eines Videos abstürzte.
- Ein Problem wurde behoben, bei dem die Anwendung in einigen Fällen nicht gestartet werden konnte.

### <a name="outlook"></a>Outlook
- Ein Problem wurde behoben, bei dem im Japanischen falsche Lesebestätigungen angezeigt wurden.

### <a name="access"></a>Access
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="project"></a>Project
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

</BR></BR>

## <a name="march-8-2019"></a>8. März 2019 
Version 1903 (Build 11425.20036)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="word"></a>Word

### <a name="find-what-youre-looking-for-with-microsoft-search"></a>Finden gesuchter Elemente mit Microsoft Search

Mit Microsoft Search können Sie alle Dateien, Aktionen, Personen und Hilfethemen finden, die Sie benötigen, um Ihre Arbeit zu erledigen.

#### <a name="getting-started"></a>Erste Schritte:

- Das Feature wird leicht erkennbar in der Kopfzeile über der Benutzeroberfläche angezeigt.

#### <a name="scenarios-to-try"></a>Mögliche Szenarien:

- Suchen nach einer Hochschule, einem aktuellen Dokument oder den Menübandbefehlen, die Sie am häufigsten verwenden
- Nachschlagen eines Themas, um mehr Informationen darüber zu erhalten
- 
#### <a name="coauthoring"></a>CoAuthoring

Sind Sie es leid, von Ihren Dokumenten mit Makros ausgesperrt zu werden? Jetzt ist die gleichzeitige Bearbeitung durch mehrere Autoren für Ihre docm-Dateien in OneDrive for Business möglich.

#### <a name="getting-started"></a>Erste Schritte:

Der Benutzer muss keine Schaltflächen auf der Benutzeroberfläche drücken, um auf diese Funktion zuzugreifen. Sie ist in OneDrive for Business docm-Dateien standardmäßig aktiviert.
Deshalb sollte der Benutzer eine docm-Datei in OneDrive for Business speichern, um dies auszuprobieren.

#### <a name="scenarios-to-try"></a>Mögliche Szenarien:

Erstellen Sie eine docm-Datei auf OneDrive for Business, teilen Sie sie mit Ihren Kollegen, und arbeiten Sie gemeinsam daran!

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="word"></a>Word 
- Wir haben ein Absturzproblem behoben, der beim Drücken von ESC in "Optionen" auftrat
- Die Ursache für einen Absturz wurde behoben, der beim Antworten auf Kommentare auftrat.
- Ein Problem mit dem Kopieren und Einfügen von Word nach PowerPoint Online wurde behoben.

### <a name="excel"></a>Excel
- Ein Problem wurde behoben, bei dem das Kopieren einer Zelle in Excel zu einer hohen CPU-Auslastung führte, wenn geschützte Dokumente und editierbare Dokumente geöffnet wurden

### <a name="powerpoint"></a>PowerPoint
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="outlook"></a>Outlook
- Ein Problem wurde behoben, bei dem die Outlook-Suche die ausgewählte chronologische Sortierung nicht einhielt
- Ein Problem wurde behoben, bei dem die Schaltfläche "Diese Aufgabe öffnen" im Menüband "Workflow" auf bestimmte E-Mails nicht reagierte
- Ein Problem wurde behoben, bei dem Outlook lokale Räume nicht löschte, nachdem Benutzer einen verfügbaren Raum in der Raumsuche ausgewählt hatten

### <a name="access"></a>Access
- Das Dialogfeld "Gespeicherter Import/Export", das im dunklen Design weißen Text auf weißem Hintergrund enthielt, wurde korrigiert
- Ein Problem wurde behoben, bei dem Benutzer die Eigenschaft "DisplayControl" für ein Ja/Nein-Feld im Tabellenentwurf nicht auf Textfeld festlegen konnten

### <a name="project"></a>Project
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität


## <a name="march-1-2019"></a>1. März 2019 
Version 1903 (Build 11414.20014)

## <a name="whats-new"></a>Neuerungen

### <a name="word"></a>Word

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a>Farben für „Änderungen nachverfolgen", Kommentare und Echtzeitzusammenarbeit jetzt synchronisiert:

Korrekturen in unserem Produkt stellen nun sicher, dass Kommentare, Änderungsnachverfolgung und der Cursor für einen Projektmitarbeiter in der gleichen Farbe angezeigt werden.

#### <a name="getting-started"></a>Erste Schritte:

Öffnen Sie ein SharePoint- oder OneDrive-Dokument, das andere Personen geöffnet haben. Vergewissern Sie sich, dass das Nachverfolgen von Änderungen und die Farbe der Kommentare für einen Benutzer mit der Farbe des Cursors eines Benutzers übereinstimmt.

#### <a name="scenarios-to-try"></a>Mögliche Szenarien:

Öffnen Sie ein SharePoint- oder OneDrive-Dokument, das andere Personen geöffnet haben. Vergewissern Sie sich, dass das Nachverfolgen von Änderungen und die Farbe der Kommentare für einen Benutzer mit der Farbe des Cursors eines Benutzers übereinstimmt.

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="word"></a>Word 
- Wir haben ein Absturzproblem behoben, der beim Drücken von ESC in "Optionen" auftrat
- Ein Problem mit dem Kopieren und Einfügen von Word nach PowerPoint Online wurde behoben.

### <a name="excel"></a>Excel
- Ein Problem wurde behoben, bei dem das Kopieren einer Zelle in Excel zu einer hohen CPU-Auslastung führte, wenn geschützte Dokumente und editierbare Dokumente geöffnet wurden

### <a name="powerpoint"></a>PowerPoint
- Ein Problem mit der Folienbildgröße bei Verwendung von @Erwähnungen in PowerPoint wurde behoben

### <a name="outlook"></a>Outlook
- Ein Problem wurde behoben, bei dem die Outlook-Suche die ausgewählte chronologische Sortierung nicht einhielt
- Ein Problem wurde behoben, bei dem die Schaltfläche "Diese Aufgabe öffnen" im Menüband "Workflow" auf bestimmte E-Mails nicht reagierte
- Ein Problem wurde behoben, bei dem Outlook lokale Räume nicht löschte, nachdem Benutzer einen verfügbaren Raum in der Raumsuche ausgewählt hatten

### <a name="access"></a>Access
- Der Eingabeaufforderungstext wurde aktualisiert, der beim Bestätigen der erneuten Verknüpfung von Tabellen mit einer Datenquelle angezeigt wurde
- Das Dialogfeld "Gespeicherter Import/Export", das im dunklen Design weißen Text auf weißem Hintergrund enthielt, wurde korrigiert
- Ein Problem wurde behoben, bei dem Benutzer die Eigenschaft "Steuerelement anzeigen" für ein Ja/Nein-Feld im Tabellenentwurf nicht auf Textfeld festlegen konnten

### <a name="project"></a>Project
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

</BR></BR>



## <a name="february-15-2019"></a>15. Februar 2019 
Version 1903 (Build 11310.20016)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="powerpoint"></a>PowerPoint


### <a name="morph-transition-enhancements---morph-by-name"></a>Verbesserungen beim Übergang "Morphen" – Morphen nach Name

Geben Sie die Formen an, die Sie morphen möchten.

#### <a name="getting-started"></a>Erste Schritte:

- Damit beim Morphen zwei Objekte als das gleiche Objekt behandelt werden, kann der Benutzer die Formen über das Auswahlfenster umbenennen.
- Dem Namen muss "!!" vorangestellt werden. (zwei Ausrufezeichen) für Morph, um es zum Außerkraftsetzen des standardmäßigen Übereinstimmungsverhaltens zu verwenden, z. B. "!!Name"
- Benutzer können Formen weiterhin in beliebige Namen umbenennen, die nicht mit "!!" beginnen ohne dass dadurch die Funktionsweise von Morph geändert wird.

#### <a name="scenarios-to-try"></a>Mögliche Szenarien:

- Fügen Sie eine Form auf einer Folie ein, z.B. ein Rechteck.
- Erstellen Sie eine neue Folie.
- Fügen Sie eine andere Form auf der zweiten Folie ein, z.B. ein Dreieck.
- Öffnen Sie das Auswahlfenster, benennen Sie das Rechteck in Folie 1 in "!!Form" und das Dreieck in Folie 2 in "!!Form" um.
- Wenden Sie Morphen auf die zweite Folie an.

</BR>

### <a name="morph-transition-enhancements---smartart"></a>Verbesserungen beim Übergang "Morphen" – SmartArt

SmartArt-Morphen mit weicheren Übergängen

#### <a name="getting-started"></a>Erste Schritte:

Verwenden Sie Morphen wie bei SmartArt.

#### <a name="scenarios-to-try"></a>Mögliche Szenarien:

- Fügen Sie eine SmartArt auf einer Folie ein.
- Duplizieren Sie die Folie.
- Ändern oder verschieben Sie die SmartArt auf der duplizierten Folie, oder ändern Sie deren Größe.
- Wenden Sie Morph auf die duplizierte Folie an.

</BR>

### <a name="morph-transition-enhancements---tables"></a>Verbesserungen beim Übergang "Morphen" – Tabellen

Tabellen-Morphen mit weicheren Übergängen

#### <a name="getting-started"></a>Erste Schritte:
Verwenden Sie Morphen wie bei Tabellen.

#### <a name="scenarios-to-try"></a>Mögliche Szenarien:

- Fügen Sie eine Tabelle auf einer Folie ein.
- Duplizieren Sie die Folie.
- Ändern oder verschieben Sie die Tabelle auf der duplizierten Folie, oder ändern Sie deren Größe.
- Wenden Sie Morph auf die duplizierte Folie an.

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a>Word, Excel, PowerPoint, OneNote, Access, Project, Publisher und Visio

### <a name="seamlessly-switch-between-accounts"></a>Nahtloses Wechseln zwischen Konten

Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Konten an einem Ort an, und erleichtert Ihnen das Wechseln zwischen diesen Konten. Diese aktualisierte Oberfläche verdeutlicht, wie Sie gerade angemeldet sind. Jetzt können Sie zwischen geschäftlichen und privaten Konten wechseln, ohne sich vorher abmelden zu müssen oder sich mit komplexen Dialogfeldern zu beschäftigen.


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a>Mögliche Szenarien:
- Wechseln zwischen Konten
- Hinzufügen eines neuen Kontos [Hinweis: Sie sollten möglicherweise zuerst zu "Datei" | "Konto" | "Verbundene Dienste" navigieren und alle persönlichen Dienste entfernen, die mit Geschäftskonten verbunden sind oder umgekehrt].
- Abmelden von einem Konto
</BR>

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="word"></a>Word 
- Ein Problem mit der Kontextvorschau für Tabellen und Bilder wurde behoben

### <a name="excel"></a>Excel
- Ein Problem wurde behoben, bei dem Text im "AutoFilter"-Suchfeld im Design "Schwarz" weiß angezeigt wird
- Ein Problem mit der Zustimmungsbenutzeroberfläche beim neuen Office-Add-In wurde behoben

### <a name="powerpoint"></a>PowerPoint
- Ein Problem mit der sich automatisch erweiternden Anzeige beim Präsentieren von Bildschirmpräsentationen auf Laptops oder Tablets wurde behoben.

### <a name="outlook"></a>Outlook
- Ein Problem mit dem Anzeigen der Schaltfläche "An OneNote senden" wurde behoben

### <a name="access"></a>Access
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="project"></a>Project
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität


</BR></BR>
## <a name="february-11-2019"></a>11. Februar 2019
Version 1903 (Build 11330.20014)


## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="word"></a>Word 
- Es wurde ein Problem behoben, bei dem einige angepasste Formatvorlagen nicht auf Word Online angewendet werden konnten.
- Es wurden Probleme in der Kontextvorschau mit umfangreichen Objekten in Word behoben.
- Es wurde ein Problem behoben, bei dem Word beim Einfügen von Listen abstürzte.

### <a name="excel"></a>Excel
- Es wurde ein Problem behoben, bei dem angefügte Leerzeichen nach Zahlenformaten nicht mehr angezeigt werden, wenn kein Währungssymbol vorhanden ist.
- Es wurde ein Problem mit der automatischen Erkennung von Aktien behoben.

### <a name="powerpoint"></a>PowerPoint
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="outlook"></a>Outlook
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="access"></a>Access
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

### <a name="project"></a>Project
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

</BR></BR>


## <a name="february-1-2019"></a>1. Februar 2019 
Version 1902 (Build 11326.20000)


## <a name="notable-fixes"></a>Wichtige Fixes

### <a name="word"></a>Word 
- Ein Problem mit der Größenänderung von Zellen in einer eingebetteten Excel-Tabelle wurde behoben
- Ein Problem mit dem Kopieren/Einfügen von Formen in einem Zeichenbereich wurde behoben

### <a name="excel"></a>Excel
- Ein Problem mit dem Öffnen von Dateien aus Excel Web App wurde behoben
- Ein Problem wurde behoben, durch das das Speichern einer CSV-Datei als XLSX-Datei aufgrund der Dateinamengröße fehlschlug.
- Ein Problem mit dem Kontextmenü, dessen Kontextmenüoptionen nicht angezeigt wurden, wurde behoben

### <a name="powerpoint"></a>PowerPoint
- Ein Problem wurde behoben, durch das Benutzer eckige Klammern nicht mithilfe der Tastenkombinationen STRG+ALT+7/STRG+ALT+8 eingeben konnten.
- Wir haben ein Problem behoben, bei dem das Einfügen eines lokalen Videos in die PPT-Datei den Festplattenspeicher des Laufwerks C reduzierte.
- Die Schaltfläche "In Microsoft Stream veröffentlichen", die einigen Benutzern nicht angezeigt wurde, wurde korrigiert.

### <a name="outlook"></a>Outlook
- Ein Problem wurde behoben, bei dem die Aufgabenansicht im Kalender das Thema der Aufgabe nicht richtig anzeigte.

### <a name="access"></a>Access
- Ein Skalierungsproblem mit Diagrammen wurde behoben

### <a name="project"></a>Project
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

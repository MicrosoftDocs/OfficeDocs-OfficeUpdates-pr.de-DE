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
ms.openlocfilehash: 37292929bc5d1301d662a8ced97c7cabc6d273de
ms.sourcegitcommit: 3598ca5e26109a1f99349ce3a4e70cb1d6f13e05
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 02/14/2020
ms.locfileid: "41978703"
---
# <a name="release-notes-for-office-monthly-channel-targeted"></a>Versionshinweise zu Office im monatlichen Kanal (gezielt)

Dieser Artikel enthält Versionshinweise zu Builds von Word, Excel, PowerPoint, Outlook, Access und Project für Windows Desktop für den monatlichen Kanal (gezielt). Jede Woche heben wir interessante neuer Features, wichtige Fixes und wesentliche Probleme hervor, über die wir Sie gerne informieren möchten. Bitte beachten Sie, dass wir Features (und häufig auch Fixes) häufig über einen Zeitraum in den monatlichen Kanal (gezielt) einführen. Auf diese Weise können wir sicherstellen, dass alles reibungslos funktioniert, bevor das Feature für ein breiteres Publikum bereitgestellt wird. Wenn also im Folgenden etwas nicht beschrieben wird, machen Sie sich keine Sorgen, es wird bald behandelt werden.  

> [!NOTE]
> - Das Veröffentlichungsdatum der Versionshinweise stimmt möglicherweise nicht mit dem tatsächlichen Veröffentlichungsdatum des Builds überein.
> - Microsoft Teams für vorhandene Installationen von Office 365 ProPlus – ab Ende Juni wird Microsoft Teams beim Aktualisieren dieser Installationen in bestehende Installationen von Office 365 ProPlus (und Office 365 Business) einbezogen. Ab welchem Datum Microsoft Teams hinzugefügt wird, hängt davon ab, welchen Updatekanal Sie verwenden. Weitere Informationen hierzu finden Sie unter [Bereitstellen von Microsoft Teams mit Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install).

[//]: # (NICHT ENTFERNEN)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-february-11"></a>Version 2002: 11. Februar
*Version 2002 (Build 12527.20092)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/de-DE/officeupdates/office365-proplus-security-updates) aufgeführt


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

## <a name="version-2001-january-29"></a>Version 2001: 29. Januar
*Version 2001 (Build 12430.20184)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="word"></a>Word

- **Speichern von Shapes als Bildern:** mit nur wenigen Mausklicks können Sie eine Form, ein Symbol oder ein anderes Objekt als Bilddatei speichern, um Sie an anderer Stelle wiederzuverwenden. [Weitere Informationen](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme

### <a name="outlook"></a>Outlook

- Behebt ein Problem, aufgrund dessen bei Benutzern Abstürze beim Umbenennen einer Signatur auftraten.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2001-january-27"></a>Version 2001: 27. Januar
*Version 2001 (Build 12430.20170)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Schnell lesen und antworten:** Antworten Sie auf Kommentare und Erwähnungen direkt aus dem E-Mail-Bereich, ohne die Arbeitsmappe zu öffnen.

- **Auf die Plätze, fertig, zeichnen!** Sobald Sie Ihren Surface Pen in der Hand halten, können Sie mit dem Zeichnen beginnen. [Weitere Informationen](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Datenprofilerstellung im Abfrage-Editor:** Sie können die Daten in Ihren Spalten auf einen Blick analysieren, Fehler- und Leerwerte identifizieren, Verteilungshistogramme anzeigen und vieles mehr.

### <a name="powerpoint"></a>PowerPoint

- **Auf die Plätze, fertig, zeichnen!** Sobald Sie Ihren Surface Pen in der Hand halten, können Sie mit dem Zeichnen beginnen. [Weitere Informationen](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a>Word

- **Auf die Plätze, fertig, zeichnen!** Sobald Sie Ihren Surface Pen in der Hand halten, können Sie mit dem Zeichnen beginnen. [Weitere Informationen](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Access

- <div style="box-sizing:border-box;"><span style="box-sizing:border-box;"><span style="background-color:rgba(255, 255, 255, 1);box-sizing:border-box;display:inline;">Dieses Update behebt ein Problem, das dazu führen kann, dass Microsoft Access eine Identitätsspalte in einer verknüpften SQL Server-Tabelle nicht identifiziert, was dazu führen kann, dass Zeilen fälschlicherweise als gelöscht gemeldet werden</span></span></div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2001-january-17"></a>Version 2001: 17. Januar
*Version 2001 (Build 12430.20120)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="word"></a>Word

- **Wählen Sie auf einfache Weise Freihand in Word aus, indem Sie eine Form um das Freihandobjekt zeichnen.:** das Lassotool auf der Registerkarte „Zeichnen“ hilft Ihnen beim Auswählen von frei handgezeichneten Objekten. Wählen Sie einzelne Striche oder ganze Wörter aus. Das ist praktisch, wenn Sie eine viele Freihandobjekte haben und nur mit einigen davon arbeiten möchten. [Weitere Informationen](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Der Excel-Client verursacht in einer nicht englischen Version 2001 in mehreren Szenarien (z. B. beim Drucken, bei der Makroausführung, beim Zoomen, usw.) für Benutzer mit dem Build 12430.20050 und der 32-Bit-Version von Excel Probleme. 

## <a name="version-2001-january-14"></a>Version 2001: 14. Januar
*Version 2001 (Build 12430.20050)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates) aufgeführt

## <a name="version-1912-january-08"></a>Version 1912: 8. Januar
*Version 1912 (Build 12325.20288)*

## <a name="version-1912-january-07"></a>Version 1912: 7. Januar
*Version 1912 (Build 12325.20280)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, durch das Benutzern unter bestimmten Umständen E-Mails angezeigt werden, die an eine Adresse gesendet wurden, die nicht mit der angezeigten SMTP-Adresse übereinstimmt.</div>

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1912-january-06"></a>Version 1912: 06. Januar
*Version 1912 (Build 12325.20264)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="powerpoint"></a>PowerPoint

- **GIFs im Handumdrehen:** eine Folie, ein Frame. Erstellen Sie auf einfache Weise Schleifen-GIFs in PowerPoint. [Weitere Informationen](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1912-december-30"></a>Version 1912: 30. Dezember
*Version 1912 (Build 12325.20240)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Nehmen Sie den Kontext mit ihren SVG-Objekten mit!:** Sie können jetzt den Text in Karten, Diagrammen und anderen SVG-Vektoren beibehalten, wenn Sie diese Objekte in Office konvertieren.

### <a name="powerpoint"></a>PowerPoint

- **Nehmen Sie den Kontext mit ihren SVG-Objekten mit!:** Sie können jetzt den Text in Karten, Diagrammen und anderen SVG-Vektoren beibehalten, wenn Sie diese Objekte in Office konvertieren.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- <div>Behebt ein Problem, das dazu führte, dass Benutzer in Outlook beim Abrufen von Cloudeinstellungen hängen bleiben.</div>



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1912-december-19"></a>Version 1912: 19. Dezember
*Version 1912 (Build 12325.20214)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="word"></a>Word

- **Eine sicherere Video-Umgebung:** Security-Verbesserungen bedeuten für Sie eine sicherere Online-Video-Umgebung. [Weitere Informationen](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, durch das Benutzer mit einer spürbaren Verzögerung beim Interagieren mit ihren Postfachordnern über Tastenkombinationen konfrontiert waren.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1912-december-12"></a>Version 1912: 12. Dezember
*Version 1912 (Build 12325.20172)*


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Beim Speichern von Änderungen bei der Verwendung einiger nicht englischer Zeichengruppen tritt möglicherweise ein Fehler auf.

- Beim Bearbeiten von dynamischen Arrayformeln innerhalb einer Zelle könnte Text außerhalb der Begrenzung der Zelle ausgerichtet werden.

- Die Funktion "Text in Spalte" könnte bei einigen Lokalisierungen nicht funktionieren.

- Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.

- Beim Zugriff auf einen verborgenen benannten Bereich kann ein Fehler auftreten.

- Dropdownmenü „Rand“ wird möglicherweise nicht ordnungsgemäß gerendert.

- Das Deaktivieren der Beschleunigung von Hardware-Grafiken mit 4K könnte die Wiedergabe von Zellen verzögern.

- Diese Änderung umgeht ein Problem mit bestimmten Intel-Grafiktreibern durch Verwendung des Softwarerenderings.

### <a name="onenote"></a>OneNote

- Möglicherweise wird OneNote nicht über das Outlook-Add-in „Besprechungsnotizen“ geöffnet.

### <a name="outlook"></a>Outlook

- Zeitweiliger Absturz bei ordnerübergreifenden Inhalten.

- Bilder, die in Outlook-E-Mail-Nachrichten Inline eingefügt wurden, können manchmal geändert werden.

- Es wurde die Möglichkeit des Erzwingens der S/MIME-Standardsignatur-Konfiguration über eine Gruppenrichtlinie hinzugefügt.

- Eingebettete Bilder könnten kleiner als erwartet erscheinen.

- Bei Aufbewahrungsrichtlinien für Bezeichnungen kann der Aufbewahrungszeitraum in Klammern anzeigt sein.

- Behebt ein Problem, bei dem Richtlinientipps bei Verwendung eines alternativen Absenders nicht angezeigt wurden.

- Auf Visitenkarten mit dem japanischem Sprachpaket können Leerzeichen angezeigt werden.

- Behebt ein Problem, bei dem der Standort einer Besprechung unerwartet nach dem Löschen wieder der Besprechung hinzugefügt wurde.

### <a name="powerpoint"></a>PowerPoint

- Der Cursor verschwindet möglicherweise nach dem Verschieben des Fokus von einem Textinhalt.

- Safelinks aus einer Office-Anwendung zu einer anderen können die verknüpfte Anwendung nicht starten.

- In einigen Fällen geht Scrollen bei Touchscreen-Geräten nicht.

- Wenn ein Benutzer zwei (oder mehr) verschiedene Videos auf einer Folie in einer Cloud-Datei hat, werden die Videobilder korrekt wiedergegeben, aber wenn der Benutzer zum Abspielen auf jedes einzelne klickt, ist der Videoinhalt derselbe.

- Dropdownmenü „Rand“ wird möglicherweise nicht ordnungsgemäß gerendert.

### <a name="project"></a>Project

- Wenn Sie sich im dunklen Modus befinden, können Sie die Tabelle nicht lesen, wenn Sie zu einem Vorgang mit einer überlasteten Ressource im Vorgangsinspektor wechseln.

- Es könnte ein Fehler hinsichtlich der Lizenzierung auftreten.

- Die Schaltfläche "Heute" in der Datumsauswahl könnte ein falsches Datum festlegen.

- Project stürzt ab, wenn Sie die Funktion „Projekte vergleichen“ verwendet wird.

- Das Festlegen von Aufwand für Vorgänge, die keine Aufgaben haben, wird auf 1 Tag abgerundet.

### <a name="word"></a>Word

- Beim Auswählen eines Kommentarhinweises im Bereich "Ansicht wechseln" sollte jetzt der moderne Kommentarbereich angezeigt werden, wenn dieser verborgen war.

- Bei einem Rechtsklick könnte manchmal nicht das ganze Wort markiert werden.

- Safelinks aus einer Office-Anwendung zu einer anderen können die verknüpfte Anwendung nicht starten.

- Im Organizer für Bausteine könnte eine ungültige Warnung angezeigt werden: &quot;Sie haben modifizierte Formen, Bausteine&quot;.

- Einige Designs erschweren es möglicherweise, den ausgewählten Kommentar zu erkennen.

- Nach der Konvertierung in ein vorgeschlagenes Format bleibt der Cursor u. U. in einem Objekt aktiv.

- In einigen Szenarien werden Bilder in Nachrichten u. U. nicht ordnungsgemäß skaliert.

- Der Kommentarbereich wird manchmal beim Kopieren/Einfügen neu geladen.

- Kommentare werden manchmal nicht in der richtigen Reihenfolge eingefügt.

- Wenn ein Benutzer auf einer Kommentarkarte erwähnt wird, wird möglicherweise JSON angezeigt.

- Dropdownmenü „Rand“ wird möglicherweise nicht ordnungsgemäß gerendert.

- Wenn Sie die Größe eines geteilten Bildschirms ändern, wird ggf. ein weiterer geteilter Bildschirm öffnen.

- Das Anwenden einer Vorlage, die aus einer mehrstufigen Liste mit benutzerdefinierten Formatvorlagen besteht, auf bestehende Dokumente kann unter bestimmten Bedingungen die Formatvorlage nicht beibehalten.

- Das Speichern einer Datei nach einem Seriendruck funktioniert unter bestimmten Bedingungen möglicherweise nicht.

### <a name="office-suite"></a>Office-Suite

- Wenn Sie ein Diagramm aus Excel in PowerPoint einfügen, kann sich die Größe des Diagramms verringern.

- Das Antworten auf einen Kommentar könnte dazu führen, dass das Textfeld vertikal über den Rand des Bereichs hinaus erweitert wird.

- Bei Produkten mit einer Formatierung für Japan wird der Nachname des Benutzerkontos in der falschen Reihenfolge angezeigt.

- Ein Bug in der Einstellung des Stichtags für ODT- und GPO-Updates wurde behoben, bei dem der relative Stichtag nur beim ersten Festlegen funktionierte. Der Fix aktiviert den relativen Stichtag für spätere Updates.

- Beim Bewegen des Mauszeigers über Kommentare wird möglicherweise eine TextBox-Kontur um den Kommentar angezeigt.

- Es wurde ein Problem behoben, bei dem Office-Aktualisierungen möglicherweise unerwartet Dateien aus dem Office CDN anstelle der beabsichtigten Quelle heruntergeladen haben, beispielsweise eine lokale oder Netzwerkfreigabe oder einen vom Configuration Manager bereitgestellten Speicherort.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1911-december-10"></a>Version 1911: 10. Dezember
*Version 1911 (Build 12228.20364)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates) aufgeführt

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.

- **Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten. [Weitere Informationen](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

### <a name="outlook"></a>Outlook

- **Benennungsrichtlinie für Gruppen:** Mit einer Benennungsrichtlinie für Gruppen kann der IT-Administrator die Namen von Gruppen, die von Benutzern in der Organisation erstellt wurden, standardisieren und verwalten. Der Administrator kann festlegen, dass dem Namen einer Gruppe beim Erstellen ein bestimmtes Präfixes und ein Suffix hinzugefügt werden, und er kann bestimmte Wörter blockieren. Auf diese Weise kann die Verwendung von unpassenden Wörtern in Gruppennamen minimiert und die Darstellung von Gruppen in Ihrem Verzeichnis verwaltet werden. Die Benennungsrichtlinie hilft außerdem Organisationen, die Teamwebsites bereitstellen, um diese je nach Abteilung zu kategorisieren.

### <a name="powerpoint"></a>PowerPoint

- **Wiedergabe von animierten Freihandzeichnungen:** Wenn Sie Freihandeingaben auf Ihren Folien vornehmen, können Sie auf diese Freihandeingaben Replay-Animationen anwenden, um den eigentlichen Zeichenvorgang während der Bildschirmpräsentation wiederzugeben. [Weitere Informationen](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- **Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.

- **Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten.

### <a name="word"></a>Word

- **Andere sehen Ihre Änderungen schnell:** Verbesserungen bei der gemeinsamen Dokumenterstellung bewirken, dass Ihre Mitarbeiter Ihre Änderungen noch schneller erkennen können als früher.

- **Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.

- **Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten. [Weitere Informationen](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

## <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Diese Änderung umgeht ein Problem mit bestimmten Intel-Grafiktreibern durch Verwendung des Softwarerenderings.

- Das Kontextmenü für PivotCharts wurde korrigiert, um die Option "Details anzeigen" zu aktivieren.

### <a name="outlook"></a>Outlook

- Behebt ein Problem, durch das Web-Add-Ins auf von Digital Rights Management verwaltete Nachrichten zugreifen konnten.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1911-november-20"></a>Version 1911: 20. November
*Version 1911 (Build 12228.20250)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Erweiterte Gruppen-E-Mail-Einstellungen:** Diese Funktion hilft Gruppenbenutzern dabei, die E-Mails oder Ereignisse anzupassen, die sie in ihrem Posteingang empfangen/verfolgen möchten.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1911-november-15"></a>Version 1911: 15. November
*Version 1911 (Build 12228.20206)*

## <a name="version-1911-november-12"></a>Version 1911: 12. November
*Version 1911 (Build 12228.20120)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates) aufgeführt

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Add-In „Datenschnellansicht“: ** erstellen Sie schnell Visio-Flussdiagramme aus Excel. [Weitere Informationen](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a>Outlook

- **Senden Sie barrierefreie E-Mails an die Benutzer, die sie am dringendsten benötigen:** Outlook zeigt einen E-Mail-Tipp an, um sicherzustellen, dass Ihr Inhalt barrierefrei ist, wenn Sie ihn an einen Benutzer senden, der barrierefreien Inhalt bevorzugt.

### <a name="powerpoint"></a>PowerPoint

- **Optimieren Sie Ihre Präsentation für alle:** Die Barrierefreiheitsprüfung hilft Ihnen beim Anordnen von Objekten auf Ihren Folien, indem sie die Sprachausgabe berücksichtigt.

### <a name="visio"></a>Visio

- **Erstellen von ansprechenden Visio-Diagrammen in Excel:** Visualisieren Sie Ihre Daten schnell und einfach in ansprechenden Visio-Diagrammen in Excel. [Weitere Informationen](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **Verbesserungen bei der gemeinsamen Dokumenterstellung:** Die gemeinsame Dokumenterstellung wurde verbessert, indem Inhaltsänderungen den anderen Benutzern nun nahezu immer in Echtzeit angezeigt werden.

### <a name="office-suite"></a>Office-Suite

- **Das Upload Center wird durch die Funktion „Dateien, die Ihre Aufmerksamkeit benötigen“ ersetzt:** Das Upload Center wird durch die in den Office-Anwendungen unter „Datei“ > „Öffnen“ angezeigte Funktion „Dateien, die Ihre Aufmerksamkeit benötigen“ ersetzt. Die neue Oberfläche ist moderner, besser integriert und im Vergleich zum Upload Center weniger aufdringlich.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Access

- Möglicherweise ist die Datensatzanzahl falsch.

### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem das Löschen von Blättern mit Sparklines, die auf Daten auf einem anderen Arbeitsblatt verweisen, dazu führen könnte, dass die Datei beim erneuten Öffnen als fehlerhaft identifiziert wird.
- Änderungen an der Größe eines Diagramms konnten nicht gespeichert werden.
- Kontrollkästchen wurden nicht ordnungsgemäß gerendert.
- Bei einigen Dialogfeldern zur Auswahl von Datenquellen wurde die Groß-/Kleinschreibung nicht beachtet.
- Einige VBA-Funktionen haben bei neuen Diagrammtypen einen Fehler zurückgegeben.
- Es könnte Benutzern ggfs. nicht möglich sein, im Office 365-Format für Excel-Arbeitsmappen zu speichern.
- Wir haben ein Problem behoben, bei dem Kontrollkästchen-Steuerelemente unter Verwendung der automatischen Anpassung der Zeilenhöhe verkleinert werden konnten.
- Es wurde ein Problem behoben, bei dem Sie beim Konvertieren von Berichtsfiltern zusammen mit der restlichen PivotTable für Abfragen an tabellarische SQL-Server möglicherweise falsche Ergebnisse erhalten.
- Es wurde ein Problem behoben, durch das das Bearbeiten einer geschützten Datei von einer nicht vertrauenswürdigen Netzwerkfreigabe zu einem Fehler in Excel geführt haben könnte.
- Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Fehler führen.
- Wir haben ein Problem gelöst, durch das das Auswählen einer Zelle nach dem Scrollen dazu führen konnte, dass die falsche Zelle ausgewählt wurde.
- Wir haben die Leistung beim Löschen von Spalten mit verbundenen Zellen erheblich verbessert.

### <a name="onenote"></a>OneNote

- Wir haben ein Problem erkannt, das sich auf die Synchronisierung einer lokalen Ressource mit einer Cloud-Ressource auswirken könnte.

### <a name="outlook"></a>Outlook

- Das Tool „Raumsuche“ zeigt bei verfügbaren Räumen möglicherweise &quot;Keine&quot; an.
- Wir haben ein Problem erkannt, bei dem es sein konnte, dass das Suchfeld nicht mehr angezeigt werden könnte, wenn das Menüband auf automatisches Ausblenden eingestellt ist.
- Wir haben ein Problem erkannt, durch das digitale Signaturen beim Signieren einer E-Mail-Nachricht mit einem digital signierten Anhang beschädigt werden könnten.
- Bei einer weitergeleiteten e-Mail fehlen möglicherweise eingebettete Bilder.
- Benutzer sind möglicherweise nicht in der Lage, Outlook-Profile mit strikter Mandantenbeschränkung zu erstellen.
- Wir haben ein Problem erkannt, bei dem lange Dateinamen nach dem Drag & Drop im Textkörper der Nachricht abgeschnitten wurde.

### <a name="powerpoint"></a>PowerPoint

- Änderungen an der Größe eines Diagramms konnten nicht gespeichert werden.
- Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Fehler führen.
- Es wurde ein Problem erkannt, bei dem das Seitenverhältnis für die Folienvorschau nicht ordnungsgemäß gesperrt bzw. entriegelt wurde.

### <a name="project"></a>Project

- Wir haben ein Problem erkannt, bei dem Notizen, die während Aktualisierungsvorgängen eingegeben werden, möglicherweise nicht gespeichert werden.
- Der Benutzer kann eine Aufgabe nicht als erledigt markieren, und sie wird auf 99 % festgelegt.
- Überlastungen werden durch einen Abgleich nicht behoben.
- Ein Problem wurde identifiziert, bei dem Benutzer beim Öffnen eines schreibgeschützten Projekts möglicherweise mehrere Meldungen erhielten.
- Wir haben ein Problem erkannt, bei dem eine Datei durch einen Benutzer gesperrt werden konnte, aber kein Benutzername in der Fehlermeldung angezeigt wird.

### <a name="publisher"></a>Publisher

- Shapes konnten außerhalb des Grafikrahmens angezeigt werden.

### <a name="word"></a>Word

- Vorschläge der Dokumentprüfung werden nicht in Kontextmenüs angezeigt.
- Änderungen an der Größe eines Diagramms konnten nicht gespeichert werden.
- Shapes konnten außerhalb des Grafikrahmens angezeigt werden.
- Bei der Anzeige von Kommentaren während der Verwendung einer Sprachausgabe wurde ein Problem erkannt.
- Wir haben ein Problem festgestellt, bei dem einige Kritiken fälschlicherweise als Rechtschreib- oder Grammatikkritiken erkannt wurden.
- Die Links von cid:-Bildern aus Outlook-Nachrichten können nun auf Anforderung erfolgreich unterbrochen werden.
- Bei Verwendung der AutoKorrektur für Koreanisch/Englisch werden möglicherweise falsche Zeichen angezeigt.
- Die Suche im Navigationsbereich schlägt möglicherweise fehl.
- Die gleichzeitige Verwendung der Sprachausgabe und der Bildschirmlupe kann zu einem Fehler führen.
- Inhaltsrichtlinien werden nicht ordnungsgemäß auf Kommentare angewendet.
- Niedrigere Richtlinienbezeichnungen werden möglicherweise angewendet, wenn eine höhere Richtlinienbezeichnung Vorrang haben sollte.
- Das Öffnen alter Dokumente und das anschließende Wechseln zur Registerkarte „Info“ kann zu einem Fehler führen.
- Wir haben ein Problem erkannt, bei dem ein neues Kommentardialogfeld manchmal nicht in den Fokus gesetzt werden konnte.
- Eine Visitenkarte konnte ggfs. nicht mehr geöffnet werden, nachdem eine Formatierung auf @mention angewendet wurde.
- Das Hervorheben von Text kann sich schwierig gestalten.
- Das Problem, bei dem Benutzer möglicherweise nicht in der Lage waren, Word-, Excel- und PowerPoint-Dokumente zu speichern, wurde behoben. Dieses Problem betrifft Benutzer, die eine neue Datei erstellen und die Option „Speichern unter“ öffnen, nachdem Sie auf das Symbol „Speichern“ geklickt oder STRG+S gedrückt haben.
- Alte Kommentare, die mit dunklem Text geschrieben wurden, sind im dunklen Modus nicht sichtbar.
- Ein Benutzer konnte daran gehindert werden, zu einem einzelnen Element im Editor zu navigieren.
- Möglicherweise wurden Grammatik- oder Rechtschreibfehler nicht hervorgehoben.

### <a name="office-suite"></a>Office-Suite

- Einige Zeichnungen werden in der Vorschau oder in Bildschirmpräsentationen möglicherweise nicht angezeigt.
- Es wurde ein Problem behoben, bei dem ein Upgrade durch eine falsche Fehlermeldung bei „Es wird bereits eine andere Installation ausgeführt“ verhindert wurde.
- Einige Katakana-Zeichen werden in einem vertikalen Textfeld möglicherweise nicht korrekt angezeigt werden.
- Der Versuch, eine Datei auf einer nicht verbundenen Netzwerkfreigabe zu speichern, kann zu einem Fehler führen.
- Leistungsproblem bei der Verwendung von Shapes unter Windows 7.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)


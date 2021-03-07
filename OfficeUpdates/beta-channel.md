---
title: Versionshinweise für den Betakanal
ms.author: anankani
author: anankani
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt der Zielgruppe von Insider Fast die aktuelle Liste der neuen Features, Fehlerkorrekturen oder bekannten Probleme bereit.
ms.openlocfilehash: 7cc50ebb59a95a5b7a2e13f83264c3b6684f0a9a
ms.sourcegitcommit: 16ea8464803ad28e97b14554df657d99b91a27de
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/05/2021
ms.locfileid: "50505667"
---
# <a name="release-notes-for-beta-channel"></a>Versionshinweise für den Betakanal

Dieser Artikel enthält Versionshinweise zu Betakanal-Builds von Word, Excel, PowerPoint, Outlook, Access und Project für Windows Desktop. Jede Woche werden interessante neue Features, wichtige Fehlerbehebungen und alle wichtigen Probleme, über die Sie informiert werden sollen, hervorgehoben. Beachten Sie, dass das Rollout von Funktionen (und manchmal auch Fixes) für den Betakanal häufig über einen längeren Zeitraum erfolgt. Auf diese Weise können wir sicherstellen, dass alles reibungslos funktioniert, bevor das Feature für ein breiteres Publikum bereitgestellt wird. Wenn Sie also unten nichts beschrieben sehen, machen Sie sich keine Sorgen, Sie werden es eventuell irgendwann erhalten.  

> [!IMPORTANT]
> Wir nehmen einige Änderungen an den Updatekanälen für Microsoft 365-Apps vor, unter anderem fügen wir einen neuen Updatekanal hinzu (monatlicher Enterprise-Kanal) und ändern die Namen der vorhandenen Updatekanäle. Um mehr zu erfahren, [lesen Sie diesen Artikel](https://go.microsoft.com/fwlink/p/?linkid=2127441).

> [!NOTE]
> - Versionshinweise werden wöchentlich veröffentlicht und können eine Kompilierung mehrerer Builds sein.
> - Das Veröffentlichungsdatum der Versionshinweise stimmt möglicherweise nicht mit dem tatsächlichen Veröffentlichungsdatum des Builds überein.

[//]: # (NICHT ENTFERNEN)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

## <a name="version-2103-march-05"></a>Version 2103: 5. März
*Version 2103 (Build 13901.20036)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **AutoSpeichern und gemeinsame Dokumentenerstellung für vertrauliche, verschlüsselte Dokumente:** Tauschen Sie nicht die Produktivität gegen die Sicherheit ein. Mit Microsoft Information Protection können Dokumente, die mit Vertraulichkeitsbezeichnungen verschlüsselt sind, jetzt genauso wie unverschlüsselte Dokumente automatisch gespeichert und mit anderen in Echtzeit gemeinsam bearbeitet werden. Erfordert Einverständnis des Mandanten (weitere Informationen: https://aka.ms/mipcoauth).

### <a name="powerpoint"></a>PowerPoint

- **AutoSpeichern und gemeinsame Dokumentenerstellung für vertrauliche, verschlüsselte Dokumente:** Tauschen Sie nicht die Produktivität gegen die Sicherheit ein. Mit Microsoft Information Protection können Dokumente, die mit Vertraulichkeitsbezeichnungen verschlüsselt sind, jetzt genauso wie unverschlüsselte Dokumente automatisch gespeichert und mit anderen in Echtzeit gemeinsam bearbeitet werden. Erfordert Einverständnis des Mandanten (weitere Informationen: https://aka.ms/mipcoauth).

### <a name="word"></a>Word

- **AutoSpeichern und gemeinsame Dokumentenerstellung für vertrauliche, verschlüsselte Dokumente:** Tauschen Sie nicht die Produktivität gegen die Sicherheit ein. Mit Microsoft Information Protection können Dokumente, die mit Vertraulichkeitsbezeichnungen verschlüsselt sind, jetzt genauso wie unverschlüsselte Dokumente automatisch gespeichert und mit anderen in Echtzeit gemeinsam bearbeitet werden. Erfordert Einverständnis des Mandanten (weitere Informationen: https://aka.ms/mipcoauth).


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Fehler korrigiert, bei dem sich die Schriftart unerwartet veränderte, wenn ein Multiplikations- oder Divisionszeichen mit einer japanischen Schriftart verwendet wurde. Wir verwenden jetzt weiterhin dieselbe Schriftart, wenn sie das Zeichen unterstützt.


- Es wurde ein Fehler behoben, bei dem einige PivotTable-Formatierungen die Arbeitsmappe beschädigten, wenn diese im XLS- oder XLT-Format gespeichert wurde.


- Es wurde ein Fehler behoben, bei dem beim Öffnen einer Arbeitsmappe einige Notizen unerwartet angezeigt wurden.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, das dazu führte, dass Nicht-ASCII-Zeichen beim Export in CSV falsch exportiert wurden.


- Es wurde ein Problem behoben, das dazu führte, dass Benutzer beim Erstellen von E-Mails eine Kontaktgruppe mit „Namen überprüfen“ nicht suchen konnten.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem im PowerPoint-Diashowmodus Pfeile in Liniendiagrammen nicht wie erwartet angezeigt wurden.


### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem das Öffnen einer mit einer Microsoft Information Protection (MIP)-Bezeichnung geschützten Datei unbegrenzt hängen bleiben kann, wenn der Benutzer nicht mit einer Identität angemeldet ist, die Zugriff auf die MIP-geschützte Bezeichnung hat. Der Benutzer ist gezwungen, das Öffnen abbrechen, um die Anmeldeaufforderung anzuzeigen, und das Öffnen ist erst nach diesem Zeitpunkt erfolgreich. Das Problem wurde behoben, indem die Anmeldeaufforderung während dem Öffnen/Herunterladen angezeigt werden kann.


- Es wurde ein Problem bei der Verwendung von Diktat in der neuen Word-Kommentierung behoben. Die Diktat-Schaltfläche in der Kommentar-Karte schaltet nun korrekt ein und aus.


- Es wurde ein Problem behoben, bei dem kein Leerzeichen zwischen Wörtern eingefügt wurde, wenn Benutzer in ihr Dokument diktierten.


- Es wurde ein Problem behoben, bei dem das Veröffentlichen von mehrzeiligen, in RTL getippten Kommentaren dazu führte, dass die zweite und weitere Zeilen links statt rechts ausgerichtet wurden.


- Es wurde ein Problem behoben, bei dem die Rechtschreibprüfung zwischen zwei verschiedenen Kontextmenüs für die Rechtschreibkorrektur wechselte.


- Es wurde ein Problem behoben, bei dem Spalten möglicherweise überlappenden Text enthalten.



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2103-february-26"></a>Version 2103: 26. Februar
*Version 2103 (Build 13819.20006)*


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, das Benutzer am Exportieren von Excel-Arbeitsmappen nach PDF hinderte.


- Ein Problem wurde behoben, bei dem einige Formatierungen verloren gehen konnten, wenn während der gemeinsamen Dokumentenerstellung ein Blatt kopiert wurde.


### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, das dazu führte, dass Anlagen beim Entfernen des DRM-Schutzes dupliziert wurden.


### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem möglicherweise falsche Vorgangsaufteilungen erstellt wurden, wenn ein Projekt aus der Project Web App in einer lokalen Datei gespeichert wurde. Dies würde beispielsweise bei Verwendung eines Vorgangskalenders mit nicht standardmäßigen Arbeitszeiten auftreten.


- Folgendes Problem wurde behoben: Wenn die Indikatorspalte nicht an der ersten Spaltenstelle stand, wurden Sie beim Ausschneiden eines Sammelvorgangs nicht gewarnt, dass auch die Unteraufgaben entfernt werden.


- Folgendes Problem wurde behoben: Wenn ein Benutzer auf seiner Arbeitszeittabelle die Funktion „Sich selbst zu einem Vorgang hinzufügen“ auswählte, wurden möglicherweise nicht die richtigen Ressourcenverfügbarkeitseinheiten für die erstellte Aufgabe verwendet.


### <a name="word"></a>Word

- Ein Problem mit der Ausrichtung von mehreren Kommentaren wurde behoben.


- Ein Problem mit den Tastenkombinationen im Aufgabenbereich „Vorlesen“ wurde behoben.


### <a name="office-suite"></a>Office-Suite

- OneDrive-Orte werden nun entsprechend der Gruppenrichtlinieneinstellung herausgefiltert.


- Ein Problem wurde behoben, das beim Laden von EMF-Images dazu führte, dass das System nicht mehr reagierte.



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2103-february-19"></a>Version 2103: 19. Februar
*Version 2103 (Build 13811.20002)*


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, das dazu führte, dass Anlagen beim Entfernen des DRM-Schutzes dupliziert wurden.


### <a name="project"></a>Project

- Folgendes Problem wurde behoben: Wenn die Indikatorspalte nicht an der ersten Spaltenstelle stand, wurden Sie beim Ausschneiden eines Sammelvorgangs nicht gewarnt, dass auch die Unteraufgaben entfernt werden.


- Folgendes Problem wurde behoben: Wenn ein Benutzer auf seiner Arbeitszeittabelle die Funktion „Sich selbst zu einem Vorgang hinzufügen“ auswählte, wurden möglicherweise nicht die richtigen Ressourcenverfügbarkeitseinheiten für die erstellte Aufgabe verwendet.


### <a name="word"></a>Word

- Ein Problem mit den Tastenkombinationen im Aufgabenbereich „Vorlesen“ wurde behoben.



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2103-february-12"></a>Version 2103: 12. Februar
*Version 2103 (Build 13806.20000)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Microsoft Search-unterstütztes Verfassen (An\CC\BCC), Vorschläge:** Das Hinzufügen von Personen zur An\CC-Zeile wird jetzt von Microsoft Search unterstützt.

- **Die Diktatfunktion ist in weiteren Sprachen verfügbar:** Die Diktatfunktion unterstützt jetzt 7 neue Sprachen: Hindi, Russisch, Polnisch, Portugiesisch (Portugal), Koreanisch, Thailändisch, Chinesisch (Taiwan)

### <a name="word"></a>Word

- **Die Diktatfunktion ist in weiteren Sprachen verfügbar:** Die Diktatfunktion unterstützt jetzt 7 neue Sprachen: Hindi, Russisch, Polnisch, Portugiesisch (Portugal), Koreanisch, Thailändisch, Chinesisch (Taiwan)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, das dazu geführt hatte, das Excel beim Versuch, die Registerkarte „Dateitypen“ anzuzeigen, manchmal unerwartet geschlossen wurde, weil es nicht in der Lage war, ein Bild abzurufen.

### <a name="powerpoint"></a>PowerPoint

- Behebt ein Problem mit Animationsschleifen und Audiolesezeichen.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, das dazu geführt hatte, dass eine zu 100 % abgeschlossene Aufgabe auf den Status „99 % abgeschlossen“ zurückgesetzt wurde.

- Es wurde ein Problem behoben, das zum unerwarteten Schließen von Project geführt hatte, wenn Benutzer JAWS ausgeführt haben oder in den Vorgangsinformationsdialog gewechselt sind.

### <a name="word"></a>Word

- Es wurde ein Problem mit dem Automatischen Speichern behoben.


- Es wurde ein Problem mit dem Auflösen von Konflikten bei der gemeinsamen Dokumenterstellung gelöst.




[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2102-february-05"></a>Version 2102: 5. Februar
*Version 2102 (Build 13801.20004)*


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Zugriff

- Sie werden jetzt ausgewählte Registerkarten in Access klarer sehen.


### <a name="excel"></a>Excel

- Wir haben ein Problem behoben, bei dem Excel nach der Auswahl einer Datenreihen in einem Diagramm nicht mehr antwortete.


- Wir haben ein Problem behoben, bei dem durch Drücken von EINGABE bei bestimmten Tastaturen unter Android eine neue Zeile hinzugefügt wurde, anstatt zur nächsten Zelle zu wechseln.


- Wir haben ein Problem mit Bildern behoben, damit diese während eines Zuschneidevorgangs ihr Seitenverhältnis beibehalten.


### <a name="outlook"></a>Outlook

- Wir haben ein Problem behoben, bei dem E-Mails als digital signiert versendet wurde, obwohl der Benutzer die Option deaktiviert hatte.


### <a name="powerpoint"></a>PowerPoint

- Wir haben ein Problem mit Bildern behoben, damit diese während eines Zuschneidevorgangs ihr Seitenverhältnis beibehalten.


### <a name="word"></a>Word

- Wir haben ein Problem mit Bildern behoben, damit diese während eines Zuschneidevorgangs ihr Seitenverhältnis beibehalten.


- Wir haben ein Problem behoben, bei dem der Kommentar mit Links möglicherweise abgeschnitten wurde.


- Wir haben ein Problem mit in Konflikt stehenden Modi bei der gemeinsamen Dokumenterstellung behoben.


- Wir haben ein Problem beim Speichern nach SharePoint Online behoben.


- Wir haben ein Problem beim Exportieren von Word-Dokumenten nach PDF behoben.


### <a name="office-suite"></a>Office-Suite

- Es wurde ein Problem behoben, bei dem Office unter bestimmten Umständen Vertraulichkeitsbezeichnungen für ein angemeldetes Konto anzeigte, wenn stattdessen Vertraulichkeitsbezeichnungen für ein anderes angemeldetes Konto angezeigt werden sollten.




[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2102-january-29"></a>Version 2102: 29. January
*Version 2102 (Build 13721.20008)*


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Ein Problem wurde behoben, bei dem Excel beim Hinzufügen eines Namens im Dialogfeld "Name definieren" unerwartet beendet wurde.


### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, das dazu führte, dass das Verschlüsselungssymbol bei E-Mails, die mit der Option "Nur verschlüsseln" gesendet wurden, nicht angezeigt wurde.

### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem Projekte mit langen kyrillischen Namen nicht über das Projektcenter geöffnet werden konnten.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2102-january-22"></a>Version 2102: 22. Januar
*Version 2102 (Build 13714.20000)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar. [Weitere Informationen](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a>Outlook

- **Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar. [Weitere Informationen](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="powerpoint"></a>PowerPoint

- **Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar. [Weitere Informationen](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

### <a name="word"></a>Word

- **Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar. [Weitere Informationen](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Ein Problem wurde behoben, bei dem bestimmte Diagramme, die diskontinuierliche Zellbereiche verwenden, beim erneuten Öffnen von Dateien nicht geladen wurden.


- Ein Problem wurde behoben, bei dem Excel nicht gestartet werden konnte bzw. unerwartet abstürzte, wenn bestimmte Einstellungen für den Schutz vor Windows-Sicherheit-Exploits (SimExec, CallerCheck) verwendet wurden.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem beim der Anzeigen von Emojis mit Farben behoben.


### <a name="word"></a>Word


- Es wurde ein Problem behoben, bei dem die Eingabe in Echtzeit und die Anwesenheit nicht wiederhergestellt werden konnten, nachdem die Internetverbindung für eine gewisse Zeit unterbrochen wurde.


- Es wurde ein Problem mit der gemeinsamen Dokumenterstellung behoben.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2102-january-15"></a>Version 2102: 15. Januar
*Version 2102 (Build 13707.20008)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Freigabe an Teams:** Teilen Sie eine E-Mail oder eine Unterhaltung aus Outlook mit einer Person oder einen Kanal in Teams.

### <a name="visio"></a>Visio

- **Fertige Grafiken für Ihre Diagramme:** Wählen Sie aus einer großen Bibliothek von Symbolen, Stockbildern, ausgeschnittenen Personen und Aufklebern, die Sie zu Ihren Visio-Zeichnungen hinzufügen können. [Weitere Informationen](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem die geplanten Kosten nicht korrekt hochgerechnet wurden, wenn eine Kostenressource einem Meilensteinvorgang zugewiesen wurde.


### <a name="word"></a>Word

- Ein Fehler wurde behoben, durch den beim Ausführen des VBA-Makros "ExportAsFixedFormat2" die Fehlermeldung "Presentation (unknown member) illegal value" auftrat.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2102-january-08"></a>Version 2102: 8. Januar
*Version 2102 (Build 13704.20000)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Verbesserte Diktatfunktion:** Mit der neuen Diktat-Symbolleiste, den Sprachbefehlen und der Unterstützung für die automatische Zeichensetzung ist es jetzt noch einfacher, Inhalte mit Ihrer Stimme zu erstellen.

### <a name="word"></a>Word

- **Verbesserte Diktatfunktion:** Mit der neuen Diktat-Symbolleiste, den Sprachbefehlen und der Unterstützung für die automatische Zeichensetzung ist es jetzt noch einfacher, Inhalte mit Ihrer Stimme zu erstellen.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Ein Problem wurde behoben, bei dem die Vorschau des eingebetteten Excel-Bereichs in PowerPoint eine falsche Größe anzeigt.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2101-january-01"></a>Version 2101: 1. Januar
*Version 2101 (Build 13624.20002)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Erforderliche Kennzeichnung:** Benutzer mit einer von ihren Administratoren festgelegten Richtlinie „Erforderliche Kennzeichnung“ müssen ihre Dokumente und E-Mails kennzeichnen.

### <a name="powerpoint"></a>PowerPoint

- **Erforderliche Kennzeichnung:** Benutzer mit einer von ihren Administratoren festgelegten Richtlinie „Erforderliche Kennzeichnung“ müssen ihre Dokumente und E-Mails kennzeichnen.

### <a name="word"></a>Word

- **Erforderliche Kennzeichnung:** Benutzer mit einer von ihren Administratoren festgelegten Richtlinie „Erforderliche Kennzeichnung“ müssen ihre Dokumente und E-Mails kennzeichnen.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="onenote"></a>OneNote

- Diese Änderung adressiert ein Rendering-Problem, das OneNote betrifft.


### <a name="outlook"></a>Outlook

- Durch diese Änderung kann Outlook eine Exchange-Servereinstellung nutzen, welche die Anzeige des Exchange Online-Archivpostfachs für Endbenutzer unterdrückt.


### <a name="powerpoint"></a>PowerPoint

- Diese Änderung adressiert ein Problem beim Formen zusammenführen, wenn mit Text gearbeitet wird.


### <a name="word"></a>Word

- Korrektur, um moderne Kommentare robuster zu machen.


- Ein Problem beim Bearbeiten von Kommentaren mit @erwähnen wurde behoben.


- Kommentarentwürfe verschwinden beim Anlegen einer neuen Word-Instanz.


- Behebung eines Problems mit verschachtelten Bildlaufleisten im Kommentarbereich.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2101-december-25"></a>Version 2101: 25. Dezember
*Version 2101 (Build 13617.20002)*


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Aktualisierung, damit die Einstellungen für Dezimal- und Tausendertrennzeichen übernommen werden, wenn ein Diagramm aus Excel kopiert und in Word eingefügt wird


- Ein Problem wurde behoben, durch das Excel beim Öffnen von UNC-Dateien mit ungültigen Dateiattributen (Erstellungszeit, Änderungszeit usw.) unerwartet geschlossen wurde.


- Diese Änderung behebt ein Problem im Zusammenhang mit dem Ändern der Umrissfarben von SVG-Bildern.


### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, das dazu führte, dass Benutzer beim Starten eines Seriendrucks von Word aus nicht angeben konnten, wie lange sie den Zugriff zulassen wollten, was dazu führte, dass sie übermäßig viele Eingabeaufforderungen erhielten.


- Ein Problem wurde behoben, das dazu führte, dass Outlook für Benutzer von auf Einlösung basierenden Add-Ins unerwartet geschlossen wurde.


### <a name="powerpoint"></a>PowerPoint

- Diese Änderung behebt ein Problem im Zusammenhang mit dem Ändern der Umrissfarben von SVG-Bildern.


### <a name="word"></a>Word

- Diese Änderung behebt ein Problem im Zusammenhang mit dem Ändern der Umrissfarben von SVG-Bildern.


- Ein Problem wurde behoben, bei dem das Antwortfeld auf einer Kommentarkarte nicht auf dem Bildschirm angezeigt wurde.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2101-december-18"></a>Version 2101: 18. Dezember
*Version 2101 (Build 13610.20002)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Überwachungsdaten über vertrauliche Bezeichnungen an M365-Administratoren senden:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, sendet Office Überwachungsdaten an das Back-End der M365-Überwachung, damit Administratoren sie sehen können. Dies ist eine Hintergrundfunktionalität (keine Benutzeroberfläche) für Administrator-Zwecke.

### <a name="outlook"></a>Outlook

- **Überwachungsdaten über vertrauliche Bezeichnungen an M365-Administratoren senden:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, sendet Office Überwachungsdaten an das Back-End der M365-Überwachung, damit Administratoren sie sehen können. Dies ist eine Hintergrundfunktionalität (keine Benutzeroberfläche) für Administrator-Zwecke.

### <a name="powerpoint"></a>PowerPoint

- **Überwachungsdaten über vertrauliche Bezeichnungen an M365-Administratoren senden:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, sendet Office Überwachungsdaten an das Back-End der M365-Überwachung, damit Administratoren sie sehen können. Dies ist eine Hintergrundfunktionalität (keine Benutzeroberfläche) für Administrator-Zwecke.

### <a name="word"></a>Word

- **Überwachungsdaten über vertrauliche Bezeichnungen an M365-Administratoren senden:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, sendet Office Überwachungsdaten an das Back-End der M365-Überwachung, damit Administratoren sie sehen können. Dies ist eine Hintergrundfunktionalität (keine Benutzeroberfläche) für Administrator-Zwecke.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Leistungsverbesserungen wurden erzielt, wenn Formatvorlagen auf Pivot-Tabellen angewendet werden.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem Benutzer nicht mehr als eine Kategorie für die Suche auswählen konnten.


- Es wurde ein Problem behoben, bei dem die Startzeit einiger Kalenderelemente unerwartet verändert wurden, wenn ein Ereignis aus einem anderen Termin kopiert wird.


### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem Benutzer beim Öffnen von Projekten, die angeblich mit aktualisierten Informationen gespeichert wurden, feststellten, dass keine Aktualisierungen vorhanden waren.


### <a name="word"></a>Word

- Es wurde ein Problem mit der Animation behoben, wenn am Ende der Kommentarkarte eine Eingabe gemacht wurde.


- Es wurde ein Problem behoben, bei dem Word beim Speichern von Dokumenten mit verborgenem Text ins PDF-Format hängen bleibt.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2101-december-11"></a>Version 2101: 11. Dezember
*Version 2101 (Build 13604.20000)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Ihre Outlook-Einstellungen in der Cloud:** Wählen Sie Ihre Outlook für Windows-Einstellungen aus, z. B. Automatische Antworten, Posteingang mit Relevanz und Datenschutz, und greifen Sie auf jedem beliebigen PC darauf zu.

### <a name="word"></a>Word

- **Bessere Zusammenarbeit mit modernen Kommentaren:** Für eine bessere Zusammenarbeit fügen Sie Kommentare zu Objekten hinzu, @erwähnen Sie Kollegen, und lösen Sie Kommentarthreads auf. [Weitere Informationen](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/modern-commenting-in-word)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Ein Problem wurde behoben, bei dem Excel fälschlicherweise eine Meldungsleiste anzeigt, dass eine neue Version der Datei verfügbar ist, und den Benutzer auffordert, seine Änderungen in einer Kopie der Arbeitsmappe zu speichern oder die Änderungen zu verwerfen.


- Es wurde ein Problem mit dem Wechsel von Trennzeichen nach einem Aufruf von Selection.Parent.Copy behoben.


### <a name="outlook"></a>Outlook

- Behebung eines Problems, das dazu führte, dass Klartext-S/MIME-Nachrichten beim Senden verstümmelt wurden.


### <a name="powerpoint"></a>PowerPoint

- Diese Änderung behebt ein Problem mit der wiederholten Wiedergabe von Hintergrundvideos in einer Bildschirmpräsentation.


- Es wurde ein Problem behoben, bei dem der Befehl "Schriftgrad", der in QAT hinzugefügt wurde, beim Aktualisieren automatisch zum nächsten definierten Schriftgrad vervollständigt wird.


### <a name="word"></a>Word

- Es wurde ein Problem mit dem Löschen von modernen Kommentaren in einem Inhaltssteuerelement behoben, das als nicht bearbeitbar gekennzeichnet ist.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2012-december-04"></a>Version 2012: 4. Dezember
*Version 2012 (Build 13530.20000)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Einbauen einer Zeitspanne zwischen unmittelbar aufeinander folgenden Besprechungen**: Geben Sie den Teilnehmern Zeit für eine Atempause und oder den Weg zwischen verschiedenen Besprechungsorten, indem Sie festlegen, dass Besprechungen standardmäßig 5–10 Minuten verspätet beginnen. [Weitere Informationen](https://support.office.com/article/be84396a-0903-4e25-b31c-1c99ce0dacf2)

### <a name="visio"></a>Visio

- **Neue Azure-Schablonen und -Formen:** Wir haben viele weitere Schablonen hinzugefügt, die Ihnen beim Erstellen von aktuellen Azure-Diagrammen helfen. [Weitere Informationen](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem die Bearbeitung in Sprachen, welche die Verwendung von IME erfordern, bei der Bearbeitung im Überschreiben-Modus schlecht funktionierte.


- Es wurde ein fehlerhafter Hyperlink zu einem Hilfeartikel in einer Warnung behoben, die angezeigt wird, wenn das automatische Speichern deaktiviert wird.


- Es wurde ein Problem behoben, aufgrund dessen Excel beim Kopieren und Einfügen von Daten in der Formelansicht unerwartet geschlossen wurde.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, aufgrund dessen die Formatierung von SmartLinks beim Speichern in Entwürfen verloren ging.


### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem das Öffnen eines Projekts mit vielen Ressourcen sehr lange dauerte.


- Es wurde ein Problem behoben, bei dem bestimmte Projekte geöffnet werden konnten, wenn ein Problem mit der Projektdatei in einem bestimmten Teil der Last vorlag.


### <a name="word"></a>Word

- Das Einfügen als nur-Text wird häufig gegenüber Rich-Text-Formatierung bevorzugt. Mit diesem Kontextmenü-Fix kann der Benutzer Inhalte als nur-Text einfügen. Andernfalls müsste der Benutzer den Text zunächst in einen nur-Text-Editor wie z. B. Notepad kopieren und dann aus dem Editor in die gewünschte Ziel-App kopieren.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2012-november-27"></a>Version 2012: 27. November
*Version 2012 (Build 13519.20000)*


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Hierdurch wird ein Problem behoben, bei dem Power Pivot eine durch Tabstopps getrennte Textdatei nicht ordnungsgemäß importieren konnte.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, aufgrund dessen Benutzer einige Probleme beim Senden von Outlook-E-Mails aus anderen Anwendungen als Outlook hatten.


### <a name="powerpoint"></a>PowerPoint

- Diese Änderung behebt ein Problem im Zusammenhang mit Timeouts, die während der Freihandanalyse aufgetreten sind.


- Diese Änderung behebt einen Grammatikfehler in der Benutzeroberfläche für die Erstellung animierter GIFs.


- Ein Problem wurde behoben, bei dem einige beschädigte PowerPoint-Dateien auch nach einem Dokumentreparaturvorgang nicht ordnungsgemäß geöffnet wurden.


### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem Benutzern u. U. mehrere nicht zugewiesene Zuordnungen angezeigt wurden, die einer Aufgabe zugeordnet waren.


- Es wurde ein Problem behoben, bei dem bei großen Projekten die Eingabe von Aufgabennamen sehr langsam sein konnte.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2012-november-20"></a>Version 2012: 20. November
*Version 2012 (Build 13512.20000)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Alle Besprechungen online:** Vereinfacht die Planung von Online-Besprechungen durch eine neue Einstellung, bei der alle Ihre Besprechungen standardmäßig online sind.

### <a name="powerpoint"></a>PowerPoint

- **Videobibliothek:** Erweitern Sie Ihre Dokumente mit einer Sammlung von kuratierten, lizenzfreien, in der App verfügbaren Videoaufnahmen.


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem die Anwesenheitsanzeige für einen unbekannten Co-Autor nicht vollständig aktualisiert wird, wenn weitere Informationen über den Co-Autor verfügbar werden.


### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem Word beim Speichern von Dokumenten mit verborgenem Text ins PDF-Format hängen bleibt.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2012-november-13"></a>Version 2012: 13. November
*Version 2012 (Build 13510.20004)*


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Ein Problem wurde behoben, bei dem der Befehl "Objekt einfügen" beim Einfügen einer Datei aus dem lokalen Synchronisationsordner von OneDrive nicht das richtige Symbol anzeigt.


### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, durch das das Feld "An:" in den Aufgabenstatusberichten leer war.


### <a name="powerpoint"></a>PowerPoint

- Ein VBA-Problem wurde behoben, bei dem "Slide.Shapes.AddMediaObject2" mit veralteten Videoformaten abstürzt (MPG-1, MPEG-2).


### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem Sie keine Abhängigkeiten von Projektleistungen löschen konnten, wenn die SharePoint-Website, der die Projektleistung zugeordnet war, nicht mehr vorhanden war.


- Es wurde ein Problem behoben, bei dem Benutzer beim Öffnen von Projekten, die angeblich mit aktualisierten Informationen gespeichert wurden, feststellen, dass keine Aktualisierungen vorhanden sind.


### <a name="word"></a>Word

- Es wurde ein Problem mit verschwommenen Bildern beim Zoomen behoben.


- Ein Problem wurde behoben, bei dem lange Links abgeschnitten wurden.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2012-november-06"></a>Version 2012: 6. November
*Version 2012 (Build 13430.20000)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Blenden Sie viele Blätter gleichzeitig ein:** Sie müssen nicht mehr ein Blatt nach dem anderen einblenden – Sie können mehrere ausgeblendete Blätter gleichzeitig einblenden. [Weitere Informationen](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)

### <a name="outlook"></a>Outlook

- **Die gleiche Signatur auf allen Geräten:** Ihre Signatur wird in der Cloud gespeichert. Erstellen Sie die Signatur einmal, und verwenden Sie diese überall, wo Sie Outlook verwenden.


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Ein Problem wurde behoben, bei dem einige Menübandelemente nicht in Chinesisch (vereinfacht) lokalisiert wurden.


- Ein Problem wurde behoben, bei dem Excel beim Aktualisieren unerwartet beendet wurde.


### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, bei dem das Hinzufügen einer Anlage zu einer aus einer Zip-Datei geöffneten Nachricht fehlschlug.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2011-october-30"></a>Version 2011: 30. Oktober
*Version 2011 (Build 13426.20004)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Verbesserte Dialogfelder für bedingte Formatierung:** Die Größe von Dialogfeldern für bedingte Formatierung kann jetzt geändert und die Regel mit einem einzigen Klick dupliziert werden. [Weitere Informationen](https://support.office.com/article/fed60dfa-1d3f-4e13-9ecb-f1951ff89d7f)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Zugriff

- Es wurde ein Problem behoben, das bei Verwendung von DAO aus nicht-Office-Anwendungen dazu führte, dass die Anwendung unerwartet geschlossen wurde.


### <a name="excel"></a>Excel

- Ein Problem mit Power Pivot bei der Verwendung einer Verbindung zu einer Oracle-Datenbank wurde behoben.


- Ein Problem wurde behoben, durch das Excel unerwartet beendet wurde, wenn der Prozess der MTR-Berechnung und der Aktualisierung von Gruppenrichtlinienobjekten (z. B. über Remoteaktualisierung von Gruppenrichtlinien) ausgelöst wurde.


- Diese Änderung behebt einen Fehler, der beim Versuch, eine atomsvc-Datei zu laden, einen Fehler in Excel verursacht.


- Es wurde ein Problem behoben, bei dem Word zu hängen scheint, wenn eine Excel-Arbeitsmappe in ein Word-Dokument eingefügt wird.


### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, bei dem ein Postfachbesitzer die Freigabeberechtigung für den eigenen Kalender nicht verwalten konnte, da die Option abgeblendet war.


- Es wurde ein Problem behoben, bei dem beim Speichern von E-Mail-Vorlagen als OFT chinesische Zeichen in Fragezeichen geändert wurden.


- Ein Problem wurde behoben, bei dem Outlook keine Nachricht mit eingeschränkter Berechtigung erstellen konnte.


- Es wurde ein Problem behoben, das dazu führte, dass Outlook beim Hinzufügen oder Speichern von Anlagen sporadisch nicht mehr funktionierte.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem Gitternetzlinien beim Schließen des Entwurfsfensters von den Folien verschoben wurden.


- Es wurde ein Problem behoben, bei dem sich die Bildlaufleiste in der Folie von selbst einstellt, nachdem die Bildschirmaufnahme bei geöffnetem Auswahlfenster gestoppt wurde.


### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem beim Speichern eines Projekts aus PWA in eine lokale MPP-Datei das ProjectBeforeTaskChangeEvent für Daten ausgelöst wurde, die vom Benutzer nicht tatsächlich geändert worden waren.


- Es wurde ein Problem behoben, bei dem die Suche nach einer Ressource anhand des Namens anstelle der GUID erfolgte, was zu Problemen führen konnte, wenn mehrere Ressourcen denselben Namen aufweisen.


### <a name="word"></a>Word

- Ein Problem wurde behoben, bei dem das Klicken auf einen Kommentarhinweis nicht dazu führte, dass die Kommentarkarte in der Ansicht angezeigt wurde.


- Ein Layout-Problem wurde behoben, bei dem sich die Linie zwischen den Spalten verschieben konnte.


- Es wurde ein Problem behoben, bei dem Word zu hängen scheint, wenn eine Excel-Arbeitsmappe in ein Word-Dokument eingefügt wird.


### <a name="office-suite"></a>Office-Suite

- Es wurde ein Problem mit dem Office-Bereitstellungstool behoben, bei dem die Konfiguration fehlschlug, wenn das Feature "RemoveMSI" in Anwesenheit des Produkts „Microsoft-Anwendungsfehler-Berichterstattung“ in Office 2007 verwendet wurde.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2011-october-23"></a>Version 2011: 23. Oktober
*Version 2011 (Build 13415.20002)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="powerpoint"></a>PowerPoint

- **Üben Sie Ihre Präsentation mit dem Referentencoach:** Erhalten Sie Feedback für Dinge, welche die Aufmerksamkeit Ihrer Benutzergruppe verstärken, beispielsweise Tempo, Tonhöhe, Füllwörter, sensible Phrasen und mehr. [Weitere Informationen](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Zugriff

- Es wurde ein Problem behoben, bei dem einige Benutzer die Fehlermeldung "Systemressource überschritten" angezeigt erhielten, wenn sie eine Abfrage aus dem synchronisierten OneDrive-Ordner exportieren wollten.

- Es wurde ein Problem behoben, bei dem das automatische Umschalten zwischen Formularfenstern zu einem anderen Formular führte.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem beim Einfügen einer aus dem Besprechungsort kopierten URL an eine andere Stelle (z. B. in einen Browser) der URL ein Strickpunkt am Ende hinzugefügt wurde.

### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem beim Duplizieren der Bildschirmpräsentation auf einen sekundären Monitor die Folienpräsentation manchmal hinter dem anderen Fenster versteckt wurde.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem Project beim Öffnen von Dateien manchmal abstürzte, wenn Ressourcenprofile auf eine bestimmte Weise angegeben wurden.

### <a name="word"></a>Word

- Es wurde ein Problem mit dem Nachverfolgen von Änderungen behoben, bei dem das Öffnen von Word-Dokumenten manchmal einen Fehlerdialogfeld angezeigte.

- Es wurde ein Problem mit dem Drucken behoben, wenn Vertraulichkeitsbezeichnungen mit Wasserzeichen angewendet wurden.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2011-october-16"></a>Version 2011: 16. Oktober
*Version 2011 (Build 13408.20000)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen. [Weitere Informationen](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a>Outlook

- **Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen. [Weitere Informationen](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a>PowerPoint

- **Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen. [Weitere Informationen](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="word"></a>Word

- **Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen. [Weitere Informationen](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem Benutzer Termine im Kalender von Microsoft 365-Gruppen in der Standardauthentifizierung nicht löschen konnten.


- Es wurde ein Problem behoben, bei dem das Starten von Outlook beim Laden des Spitznamen-Caches fehlgeschlagen ist.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem das Symbol „Inhaltsplatzhalter“ neben „Bilder“ keine QuickInfo hatte.


- Es wurde ein Problem behoben, bei dem die geschützte Ansicht der Bildschirmpräsentation, die durch eine pptsx-Datei dargestellt wird, die Bildschirmaufnahme von IRM-geschützten Dokumenten ermöglicht.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2011-october-09"></a>Version 2011: 09. Oktober
*Version 2011 (Build 13406.20000)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Erstellen von Power Platform-Datenflüssen aus Abfragen:** Jetzt können Sie Ihre Abfragen in Power Query-Vorlagen exportieren, die zum Erstellen von neuen Power Platform-Datenflüssen verwendet werden können.

### <a name="powerpoint"></a>PowerPoint

- **Exportieren eines animierten GIF in einem Bereich:** Folienbereich auswählen, wenn Sie nach animiertem GIF exportieren

- **Erstellen von GIFs mit transparenten Hintergründen:** Wenn Sie in ein animiertes GIF exportieren, ermöglicht Ihnen eine neue Option den transparenten Hintergrund.


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem „Dateiname“ nach einem „Speichern als“-Vorgang mit aktiviertem COM-Add-In nicht geändert wurde.


- Es wurde ein Problem behoben, bei dem das automatische Speichern mit einer falschen/irreführenden Fehlermeldung fehlschlägt, wenn im Excel-Datenmodell eine schlechte Kennzahldefinition vorhanden ist.


- Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem der Schnelldruck für Bildanlagen zu einem Fehler geführt hat: "Windows kann dieses Bild nicht finden. Überprüfen Sie den Speicherort, und versuchen Sie es dann erneut."


- Es wurde ein Problem behoben, das dazu führte, dass einige Benutzer Outlook im Offline-Status starteten, bis sie manuell wählten, online zu arbeiten.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.


### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem das Ereignis NewVal im ProjectBeforeTaskChange nicht den richtigen Wert hat, wenn eine Verzögerung innerhalb einer Ansicht vom Typ "Aufgabenformular" geändert wird.


- Es wurde ein Problem behoben, bei dem Sie, wenn Sie eine Aufgabenliste in einem Projektstandort haben und die Aufgabenliste gruppieren, die Aufgabenliste nicht schnell bearbeiten können.


- Es wurde ein Problem behoben, bei dem, wenn Sie eine Unternehmensressource über CSOM aktualisieren, die maximale Anzahl von Ressourcen möglicherweise verloren geht.


### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.


### <a name="office-suite"></a>Office-Suite

- Es wurde ein Problem behoben, bei dem bei der interaktiven SSO-API-Anmeldung ein Fehlercode zurückgegeben wurde.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-october-02"></a>Version 2010: 02. Oktober
*Version 2010 (Build 13328.20000)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Verwenden des Dialogfelds "Erweitert" zum Erstellen von Datentypen:** Im Dialogfeld "Erweitert" können Sie manuell die Spalten auswählen, die den von Ihnen erstellten Datentyp kombinieren.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="onenote"></a>OneNote

- Es wurde ein Problem behoben, bei dem ein Benutzer nicht in der Lage war, eine Notizbuch-URL aus einem Textfeld in OutSpace File > Info auszuwählen und zu kopieren.


### <a name="outlook"></a>Outlook

- Behebt ein Problem, das dazu führte, dass automatisch generierte E-Mails mit einem leeren Textkörper gesendet wurden, wenn die Betreffzeile leer war.


- Es wurde ein Problem behoben, bei dem die falsche Ordner-GUID für Ordner zwischengespeichert wird.


- Wenn ein Benutzer eine E-Mail-Adresse in das Feld "Empfänger" mit dem Anzeigenamen kopierte und einfügte, wurde die E-Mail-Adresse nicht immer ordnungsgemäß analysiert, woraufhin eine Warnung zu einer ungültigen E-Mail-Adresse angezeigt wurde.  Das Problem wurde so behoben, dass Name und E-Mail-Adresse nun ordnungsgemäß analysiert werden und die Warnung nicht mehr angezeigt wird.


- Es wurde ein Problem behoben, bei dem freigegebene Ordner nicht den übergeordneten Ordnernamen zurückgegeben haben. Anstatt wurde ein leerer Pfad zurückgegeben, der nicht ordnungsgemäß an das primäre Konto ging.


- Es wurde ein Problem behoben, durch das nach dem erneuten Öffnen des Entwurfs über den schreibgeschützten Vorschaubereich Änderungen nachverfolgt werden.


- Es wurde ein Problem behoben, bei dem die Option "Speichern unter" für klassische Anlagen nicht verfügbar war.


- Es wurde ein Problem behoben, durch das ein Benutzer eine Möglichkeit zum Anpassen des Rechtfertigungstexts bietet, wenn eine Richtlinie überschrieben wird.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem PowerPoint beim Exportieren in das PDF-Format keine rechteckige Aufzählungspunkte exportierte.


- Es wurde ein Problem behoben bei dem, wenn Sie sich auf der letzten Folie befinden und zur nächsten Folie wechseln, nachdem Sie "Sitzung beenden" gedrückt haben und bevor die Zusammenfassung angezeigt wird, der Dialog "Sitzung beenden" auch auf der Zusammenfassungsseite sichtbar ist.


### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem Project abstürzt, wenn Sie eine Gruppe auf die Ressourcennutzung oder die Arbeitsblattanzeige anwenden und dann eine Spalte einfügen.


- Es wurde ein Problem behoben, bei dem Sie, wenn Sie benutzerdefinierte Felder mit Formeln haben und den Ertragswert verwenden, Leistungsverzögerungen beim Wechsel der Ansichten und beim Öffnen von Projekt-/Aufgabendetails feststellen konnten.


- Es wurde ein Problem mit der ConsolidateProjects-VBA-Methode behoben, wenn Sie versuchen, dasselbe Projekt mehrmals hinzuzufügen und AttachToSources auf "false" festzulegen.


- Ein Problem wurde behoben, bei dem Sie, wenn Sie einen Ereigniscode ausführen, die Änderungen über eine Aufgaben-Maske durchführen und dann durch Klicken auf die Schaltfläche OK keine Änderungen vornehmen.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-september-25"></a>Version 2010: 25. September
*Version 2010 (Build 13318.20000)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Datentypen mit Microsoft Power Query für Excel erstellen:** Erstellen Sie umfangreiche Datentypen mit Microsoft Power Query für Excel von jeder Datenquelle

### <a name="outlook"></a>Outlook

- **Updates zur Verbesserung der Benutzerfreundlichkeit für Aufgaben:** visuelle Auffrischung von Aufgabenelementen

- **Sparen Sie Zeit beim Verfassen von Nachrichten:** Outlook macht Ihnen Formulierungsvorschläge, sodass Sie Nachrichten schnell verfassen können. Wenn Sie den Vorschlag akzeptieren möchten, verwenden Sie einfach die TAB-Taste.

### <a name="word"></a>Word

- **Der Microsoft-Editor-Bereich erhält in der Desktopversion von Word ein Update:** Die aktuelle Benutzeroberfläche im Editorbereich in Word für Desktopclients wurde aktualisiert.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Zugriff

- Ein Problem wurde behoben, bei dem die Position der Bildlaufleiste nicht ordnungsgemäß festgelegt wurde, wenn das Abfrage/Beziehungsfenster beim Scrollen geladen wurde.


- Ein Problem wurde behoben, bei dem der Aufgabenbereich "Tabelle hinzufügen" Namen mit "&" nicht korrekt anzeigte.


### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem die mehrstufige Kategorie "manuelles Intervall" in Diagrammen nicht funktionierte.


- Ein Problem wurde behoben, das beim Aktualisieren von OLAP-PivotTables zu einem Absturz führen könnte.


- Ein Problem wurde behoben, bei dem das Hinzufügen zu einer für die Datenüberprüfung verwendeten Tabelle die Optionen nicht für alle Blätter in der Arbeitsmappe aktualisierte.


### <a name="onenote"></a>OneNote

- Ein Problem wurde behoben, bei dem OneNote im Zeichenbereich hohe Kontrastfarben für benutzerdefinierte Designs nicht beachtete.


- Ein Problem wurde behoben, dass dazu führte, dass beim Zeigen auf grüne Farbe in der Farbauswahl des Notizbuchs das Popup "Rote Kreide" angezeigt wurde.


### <a name="powerpoint"></a>PowerPoint

- Ein Problem wurde behoben, bei dem ein verknüpftes Excel-Diagramm fälschlicherweise in eine Excel-Tabelle geändert wurde, wenn der Benutzer den Quellpfad in den lokalen OneDrive-Ordner änderte.


### <a name="word"></a>Word

- Ein Problem wurde behoben, bei dem Links zu workflowaktivierten Dateien nicht erwartungsgemäß geöffnet wurden.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-september-18"></a>Version 2010: 18. September
*Version 2010 (Build 13312.20006)*


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Korrekturlesen Ihrer Nachrichten mit dem Editor:** Sie können nun Grammatik- und andere Stilempfehlungen in Ihren E-Mails erhalten (für Benutzer von Outlook 64-Bit). Suchen Sie nach unterstrichenen Wörtern, um die Vorschläge des Editors zum Verfeinern Ihrer Texte anzuzeigen.

- **Aufheben der Sprachbarriere durch einen integrierten Übersetzer:** Ab jetzt sind keine Add-Ins für die Übersetzung mehr erforderlich! Klicken Sie in einer Nachricht mit der rechten Maustaste, um bestimmte Wörter, Ausdrücke oder die gesamte Nachricht zu übersetzen.


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem mit 2D-Kartendiagrammen behoben, bei dem das Festlegen der Farben für die Werte "Max.", "Mittel" und "Min." für eine Reihe bei Verwendung von VBA nicht funktionierte.


- Es wurde ein Problem, bei dem in Datenüberprüfungslisten u. U. nicht alle Elemente in der Liste angezeigt wurden, wenn die Office-Sprache auf Spanisch festgelegt war.


- Ein Problem wurde behoben, durch das die Fehlermeldung verursacht wurde, dass "Excel nicht ausreichend Ressourcen für die Berechnung einer oder mehrerer Formeln zur Verfügung stehen".


- Ein Problem wurde behoben, bei dem ChartSheet in einigen Fällen abgestürzt ist, wenn eine Formel über die Bearbeitungsleiste eingegeben wurde.


### <a name="outlook"></a>Outlook

- Wenn ein Benutzer eine E-Mail-Adresse in das Feld "Empfänger" mit dem Anzeigenamen kopierte und einfügte, wurde die E-Mail-Adresse nicht immer ordnungsgemäß analysiert, woraufhin eine Warnung zu einer ungültigen E-Mail-Adresse angezeigt wurde.  Das Problem wurde so behoben, dass Name und E-Mail-Adresse nun ordnungsgemäß analysiert werden und die Warnung nicht mehr angezeigt wird.


### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem es vorkam, dass wenn ein Benutzer auf eine nachverfolgte Änderung tippte (Einfügung/Löschung), ein Kommentar-Popup angezeigt wurde.


- Es wurde ein Problem mit dem Löschen von Kommentarbeschriftungen in Word behoben.


- Es wurde ein Problem in Outlook mit auf "Nicht weiterleiten" festgelegten Nachrichten behoben.


- Es wurde ein Problem mit dem Speichern eines Word-Dokuments mit Zitaten und Formeln behoben.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-september-11"></a>Version 2010: 11. September
*Version 2010 (Build 13304.20000)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="access"></a>Access

- **Office kann Ihre Einstellung für den dunklen Modus in Windows 10 ausführen:** Windows 10 im dunklen Modus verwenden? Office kann jetzt Designs so wechseln, dass sie automatisch angepasst werden – Wählen Sie einfach „Systemeinstellung verwenden“ als Office-Design aus.

### <a name="excel"></a>Excel

- **Office kann Ihre Einstellung für den dunklen Modus in Windows 10 ausführen:** Windows 10 im dunklen Modus verwenden? Office kann jetzt Designs so wechseln, dass sie automatisch angepasst werden – Wählen Sie einfach „Systemeinstellung verwenden“ als Office-Design aus.

### <a name="onenote"></a>OneNote

- **Office kann Ihre Einstellung für den dunklen Modus in Windows 10 ausführen:** Windows 10 im dunklen Modus verwenden? Office kann jetzt Designs so wechseln, dass sie automatisch angepasst werden – Wählen Sie einfach „Systemeinstellung verwenden“ als Office-Design aus.

### <a name="outlook"></a>Outlook

- **Office kann Ihre Einstellung für den dunklen Modus in Windows 10 ausführen:** Windows 10 im dunklen Modus verwenden? Office kann jetzt Designs so wechseln, dass sie automatisch angepasst werden – Wählen Sie einfach „Systemeinstellung verwenden“ als Office-Design aus.

### <a name="powerpoint"></a>PowerPoint

- **Office kann Ihre Einstellung für den dunklen Modus in Windows 10 ausführen:** Windows 10 im dunklen Modus verwenden? Office kann jetzt Designs so wechseln, dass sie automatisch angepasst werden – Wählen Sie einfach „Systemeinstellung verwenden“ als Office-Design aus.

### <a name="project"></a>Project

- **Office kann Ihre Einstellung für den dunklen Modus in Windows 10 ausführen:** Windows 10 im dunklen Modus verwenden? Office kann jetzt Designs so wechseln, dass sie automatisch angepasst werden – Wählen Sie einfach „Systemeinstellung verwenden“ als Office-Design aus.

### <a name="publisher"></a>Publisher

- **Office kann Ihre Einstellung für den dunklen Modus in Windows 10 ausführen:** Windows 10 im dunklen Modus verwenden? Office kann jetzt Designs so wechseln, dass sie automatisch angepasst werden – Wählen Sie einfach „Systemeinstellung verwenden“ als Office-Design aus.

### <a name="visio"></a>Visio

- **Office kann Ihre Einstellung für den dunklen Modus in Windows 10 ausführen:** Windows 10 im dunklen Modus verwenden? Office kann jetzt Designs so wechseln, dass sie automatisch angepasst werden – Wählen Sie einfach „Systemeinstellung verwenden“ als Office-Design aus.

### <a name="word"></a>Word

- **Office kann Ihre Einstellung für den dunklen Modus in Windows 10 ausführen:** Windows 10 im dunklen Modus verwenden? Office kann jetzt Designs so wechseln, dass sie automatisch angepasst werden – Wählen Sie einfach „Systemeinstellung verwenden“ als Office-Design aus.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Ein Problem wurde behoben, bei dem beim Wechseln zwischen Arbeitsblättern mit großen Datenmengen eine deutliche Verzögerung auftrat, wenn ‚Seitenumbruchvorschau‘ aktiviert war.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem E-Mails ausgeblendet wurden, wenn „Posteingang mit Relevanz“ deaktiviert und eine Sortierung durchgeführt wurde.

### <a name="powerpoint"></a>PowerPoint

- Ein Problem wurde behoben, bei dem GIF-Dateien nur im Editor und in Bildschirmpräsentationen animiert wurden.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-september-04"></a>Version 2010: 04. September
*Version 2010 (Build 13301.20004)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Anheften von E-Mails:** Diese Funktion hilft den Benutzern, Mails zu verfolgen, die sie an Sie zurückschicken oder als Erinnerung haben müssen, indem sie sie ganz oben auf der Nachrichtenliste halten.

- **Empfangen von E-Mail-Vorschlägen bei der Suche nach Personen:** Während Sie Ihre Suchbegriffe in Outlook eingeben, werden Ihnen in den Vorschlägen die relevantesten E-Mails angezeigt.

- **Empfangen von E-Mail-Vorschlägen bei der Suche nach Personen:** Während Sie Ihre Suchbegriffe in Outlook eingeben, werden Ihnen in den Vorschlägen die relevantesten E-Mails angezeigt.

- **Microsoft-Editor erhält ein Upgrade für Word- und Outlook-Desktop-Clients:** Wir stellen ein neues Click-to-Review-Modell für Rechtschreibung, Grammatik und fortgeschrittene Stilvorschläge des Editors vor. Diese Änderung beinhaltet auch eine neue spezielle Kartenoberfläche zur Überprüfung der Vorschläge.

### <a name="word"></a>Word

- **Microsoft-Editor erhält ein Upgrade für Word- und Outlook-Desktop-Clients:** Wir stellen ein neues Click-to-Review-Modell für Rechtschreibung, Grammatik und fortgeschrittene Stilvorschläge des Editors vor. Diese Änderung beinhaltet auch eine neue spezielle Kartenoberfläche zur Überprüfung der Vorschläge.

[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem beim Öffnen einer Datei, die die LET-Funktion enthält, die Warnmeldung angezeigt wurde: "Wir haben ein Problem mit dem Inhalt in "Ihrer Datei.xlsx" gefunden. Möchten Sie, dass wir so viel wie möglich wiederherstellen? Wenn die Quelle für diese Arbeitsmappe vertrauenswürdig ist, klicken Sie auf „Ja“.
- Es wurde ein Absturz im Zusammenhang mit XLAM-Add-In-Referenzen und benannten Bereichen behoben.
- Es wurde ein Problem behoben, bei dem Benutzer einen PivotTable-Filter nicht ändern konnten, weil er auf einen Wert eingestellt war, der in einer Analysis Services-Datenbank nicht mehr vorhanden war.
- Es wurde ein Problem behoben, bei dem Benutzer, die einen benutzerdefinierten Stil auf ein dynamisches Array anwandten, die Fehlermeldung erhielten: "Sie können einen Teil eines Arrays nicht ändern". Hierbei handelt es sich um eine Legacy-Einschränkung, die entfernt wurde.
- Es wurde ein Problem behoben, bei dem die Excel-Formularleiste nicht vollständig gerendert werden konnte, wenn die Verbindung zu einem Gerät verloren ging, wie z. B. beim Verbinden/Trennen einer Remote-Sitzung oder bei einem Monitorwechsel.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, das mehr Flexibilität bei der Aktivierung/Deaktivierung der Standardprotokollierungsoptionen über die Gruppenrichtlinie bietet.
- Es wurde ein Problem behoben, bei dem der Legacy-Domänenname für einen E-Mail-Absender beibehalten und angezeigt wurde, nachdem ein Entwurf der E-Mail zwischen Postfächern mit Assistenten- und Manager-Berechtigungen verschoben wurde.
- Es wurde ein Problem behoben, das dazu führte, dass einige Benutzer Outlook im Offline-Status starteten, bis sie manuell wählten, online zu arbeiten.
- Es wurde ein Problem behoben, bei dem das Ausführen des VBA-Codes ActiveInspector.CommandBars.ExecuteMso ("ShowSchedulingPage") nach dem Aktivieren des Einzeiligen Menübands (SLR) zu einem Laufzeitfehler führen konnte.
- Es wurde ein Problem behoben, bei dem die Schaltflächen "OK" und "Abbrechen" im Dialogfeld "Automatische Antworten" auf einem System mit einer hohen Auflösung (z. B. 1750 x 1920) in Verbindung mit einer großen Textgröße (z. B. 175 %) nicht sichtbar waren.
- Es wurde eine Bedingung behoben, nach der das Senden einer Besprechungsanfrage von einer leeren Kontaktgruppe an eine andere Kontaktgruppe zu einem Absturz führen würde.
- Es wurde ein Problem behoben, bei dem es zu einem Absturz kam, wenn Benutzer bestimmte sehr große E-Mails öffneten.
- Es wurde ein Problem behoben, bei dem, wenn die Gruppenrichtlinie erfordert, dass ein Add-In immer aktiviert sein muss, die Überwachungs-Add-Ins nicht mehr verfügbar sind, um Benutzer daran zu hindern, das Add-In zu deaktivieren.

### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem Videos in Bildschirmpräsentationen nicht automatisch wiedergegeben wurden.
- Es wurde ein Problem behoben, bei dem nach dem Starten von PowerPoint, dem Einfügen einer Folie und dem Öffnen und Schließen des Kommentarbereichs die Folien im Miniaturansichtenbereich als überlappend angezeigt wurden.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem, wenn eine Ressource mehrere Kostensatztabellen hat, die verbleibenden Kosten möglicherweise nicht korrekt berechnet werden.
- Es wurde ein Problem behoben, bei dem das Projektabschlussdatum für Projekte, die mit der Microsoft Office SharePoint Online-Aufgabenliste verbunden sind, nicht aktualisiert wurde.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem die Kommentarkarte einen Rahmen um den Kommentartext anzeigte, wenn der Benutzer auf den Kommentar klickte.
- Es wurde ein Problem behoben, bei dem der Fokus nicht auf den Kommentarbereich gelegt wurde, wenn das Dokument auf 160 % oder mehr gezoomt wurde und der Kommentarbereich nicht sichtbar war.
- Es wurde ein Problem behoben, bei dem die Kommentare zu einem Dokument auf anderen geöffneten Dokumenten angezeigt wurden, nachdem zwischen den mehreren geöffneten Dokumenten gewechselt wurde.
- Es wurde ein Problem behoben, bei dem, wenn ein Benutzer einen Kommentar-Entwurf erstellte, der in einer Zeile verankert war, die bereits bestätigte Kommentare enthielt, der Entwurf in der falschen Reihenfolge in Bezug auf den bestätigten Kommentar im SideTrack angeordnet wurde.
- Es wurde ein Problem behoben, bei dem lange Links beim Speichern eines Dokuments im HTML-Format nicht umgebrochen wurden.
- Es wurde ein Problem mit Makros behoben, in denen „AutoOpen“ vor „AutoExec“ ausgeführt wird.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-august-28"></a>Version 2009: 28. August
*Version 2009 (Build 13219.20004)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Behebt ein Problem, das dazu führte, dass Benutzer durch das Auswählen mehrerer Nachrichten E-Mail-Inhalte senden konnten, für die eine "Nicht weiterleiten"-Richtlinie in OneNote festgelegt war.

### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, durch das die Funktion zum Einfügen eines Videos deaktiviert war.

### <a name="word"></a>Word

- Ein Problem wurde behoben, bei dem der Benutzer die Kopf-oder Fußzeile beim Auswählen eines Kommentars nicht verlassen konnte.
- Es wurde ein Problem behoben, das Benutzer daran hinderte, Benutzerkommentar-Threads zu sehen, die die Sidetrack-Grenze überschritten, weil das Scrollen durch den Sidetrack nicht funktioniert hat.
- Ein Problem wurde behoben, bei dem die Suche nach aufgelösten Kommentaren im Sidetrack-Bereich nicht funktioniert hat.

### <a name="office-suite"></a>Office-Suite

- Es wurde ein Problem mit dem Office-Bereitstellungstool behoben, bei dem die Konfiguration fehlschlug, wenn das Feature "RemoveMSI" in Anwesenheit des Produkts „Microsoft-Anwendungsfehler-Berichterstattung“ in Office 2007 verwendet wurde.
- Im Dialogfeld "Bild komprimieren" wurde ein Problem behoben, bei dem einige vom Benutzer ausgewählte DPI-Einstellungen nicht beibehalten wurden.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-august-21"></a>Version 2009: 21. August
*Version 2009 (Build 13212.20000)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Action Pen in Excel:** Ein Stifttool, mit dem Sie handschriftliche Eingaben machen und Ihre Daten schnell bearbeiten können.

### <a name="outlook"></a>Outlook

- **Unterhaltung löschen nach Nachrichtenbesitzer:** Dieses Feature ermöglicht es Ihnen, eine Unterhaltung nach dem Nachrichtenbesitzer zu löschen.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Zugriff

- Ein Problem wurde behoben, bei dem Verbindungen zu einer ODBC-Datenbank mit Anwendungen von Drittanbietern nicht funktionierten.

### <a name="excel"></a>Excel

- Es wurde ein Problem behoben: Beim Festlegen der FormulaR1C1-Eigenschaft für einen Bereich mithilfe eines Makros waren die Zellbezüge falsch, wenn ein Diagrammblatt das aktive Blatt war.
- Ein Problem wurde behoben, bei dem Freihandeingaben dazu führen konnten, dass Excel nicht mehr reagierte.

### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben: Benutzer können IRM (Information Rights Management) jetzt für Outlook deaktivieren, ohne es für die übrigen Office-Anwendungen deaktivieren zu müssen.

### <a name="word"></a>Word

- Ein Problem wurde behoben, bei dem Word nach dem Löschen von Kommentaren abstürzen konnte.
- Ein Problem wurde behoben, bei dem in einigen Fällen Aufzählungszeichen in E-Mails nicht korrekt angezeigt wurden.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-august-14"></a>Version 2009: 14. August
*Version 2009 (Build 13205.20000)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem, wenn ein Benutzer einen Formelnamen einschließlich der Klammer eingab und die Hilfe über F1 aufrief, das für diese Formel spezifische Hilfethema nicht angezeigt wurde.
- Es wurde ein Problem behoben, bei dem den Schaltflächen zugewiesene Makros nach der Wiederherstellung einer älteren Version der Datei beschädigt wurden.

### <a name="outlook"></a>Outlook

- Diese Änderung behebt ein Problem, bei dem die Seite "Besprechung" weiterhin angezeigt wurde, nachdem der Benutzer die Registerkarten von der Seite "Besprechung" auf die Seite "Terminplanungs-Assistent" gewechselt hatte.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem das Aufzählungsbildsymbol nicht korrekt angezeigt wurde.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2009-august-07"></a>Version 2009: 7. August
*Version 2009 (Build 13130.20000)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, bei dem die Benutzerkontoattribute in Active Directory für "otherTelephone" und "otherHomePhone" nicht den entsprechenden Outlook-LDAP-Attributen zugeordnet wurden.

### <a name="powerpoint"></a>PowerPoint

- Ein Problem wurde behoben, bei dem das Menüband bzw. die Titelleiste unter bestimmten Bedingungen nicht angezeigt wurde.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-july-31"></a>Version 2008: 31. Juli
*Version 2008 (Build 13127.20002)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen. Keine Konvertierung erforderlich.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)

### <a name="outlook"></a>Outlook

- **iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen. Keine Konvertierung erforderlich.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)

### <a name="powerpoint"></a>PowerPoint

- **iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen. Keine Konvertierung erforderlich.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)

### <a name="word"></a>Word

- **iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen. Keine Konvertierung erforderlich.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/insert-apple-photos-into-office-easily)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Zugriff

- Diese Korrektur behebt das Problem, bei dem der Versuch, bestimmte Abfragen auszuführen, zuvor die Fehlermeldung „Abfrage ist zu komplex“ erzeugt hat.

### <a name="excel"></a>Excel

- Das Problem wurde behoben, bei dem, wenn die Reihenfolge einer Diagrammserie geändert wurde, das entsprechende, an der Serie ausgerichtete Kontrollkästchen nicht zusammen mit der Serie neu geordnet wurde.
- Ein Problem wurde behoben, bei dem die Kopie eines Bildes mit einer radialen Verlaufsfüllung nicht mit dem Original übereinstimmte.

### <a name="outlook"></a>Outlook

- Diese Korrektur behebt ein Problem, bei dem Benutzende beim Beantworten einer mit digitalen Rechten verwalteten Nachricht in einem Inspektorfenster keine Signatur hinzufügen konnten, wenn sie keine Eigentümerrechte für die Nachricht hatten, auf die sie antworteten.
- Diese Korrektur behebt ein Problem, das dazu führte, dass Outlook Zeilenumbrüche in Abschrifteninhalten nicht richtig anzeigte.

### <a name="powerpoint"></a>PowerPoint

- Ein Problem wurde behoben, bei dem die Kopie eines Bildes mit einer radialen Verlaufsfüllung nicht mit dem Original übereinstimmte.
- Ein Problem wurde behoben, bei dem die Schaltfläche „Formulare“ in PowerPoint das Erstellen von Formularen nicht zulässt, wenn der Zugriff auf den Microsoft Store nicht zulässig war.

### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem für eine SharePoint-Aufgabenliste die Schaltflächen auf dem Menüband auf der zweiten Registerkarte deaktiviert sein können.

### <a name="word"></a>Word

- Ein Problem wurde behoben, bei dem die Kopie eines Bildes mit einer radialen Verlaufsfüllung nicht mit dem Original übereinstimmte.
- Ein Problem wurde behoben, bei dem sich das Überarbeitungsfeld unerwartet öffnet, wenn ein Kommentar hinzugefügt wurde, um eine Änderung zu verfolgen.
- Ein Problem wurde behoben, bei dem Links zu Dokumenten nicht über die Dropdown-Liste Einfügen -> Link in das Kommentarfeld eingefügt wurden.
- Ein Problem wurde behoben, bei dem die Anzahl der Hyperlinks in der VBA-Hyperlinks-Sammlung nach dem Hinzufügen eines Bildes, das einen Hyperlink enthält, nicht korrekt iteriert wurde.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-july-24"></a>Version 2008: 24. Juli
*Version 2008 (Build 13117.20000)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Erstellen Sie ansprechende Visio-Diagramme in Excel:** Erstellen Sie ein Flussdiagramm oder ein Organigramm durch Einfügen von Daten in ein Arbeitsblatt. [Weitere Informationen](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="onenote"></a>OneNote

- Wir haben ein Problem behoben, bei dem der Platzhaltertext im Bearbeitungsfeld „Suchen“ überlaufen würde, wenn die Größe des Anwendungsfensters auf eine kleine Dimension geändert wurde.

### <a name="word"></a>Word

- Wir haben ein Problem behoben, bei dem der Platzhaltertext im Bearbeitungsfeld „Suchen“ überlaufen würde, wenn die Größe des Anwendungsfensters auf eine kleine Dimension geändert wurde.
- Wir haben ein Problem behoben, bei dem die Option „Bestimmte Personen“ zum Nachverfolgen von Änderungen deaktiviert wurde.
- Wir haben ein gelegentliches Aufhängen beim Öffnen von HTML-Dateien behoben.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-july-17"></a>Version 2008: 17. Juli
*Version 2008 (Build 13115.20000)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Wir haben ein Problem behoben, bei dem jedes Mal, wenn ein Pivot-Diagramm mit ausgeblendeten Führungslinien gespeichert und wieder geöffnet wurde, die Führungslinien sichtbar wurden.

- Ein Problem wurde behoben, bei dem Diagramme nicht immer wie erwartet aktualisiert wurden, wenn "ForceFullCalculation" über VBA für die Arbeitsmappe aktiviert wurde.

### <a name="outlook"></a>Outlook

- Wir haben ein Problem beim Erstellen mehrerer Profile in Outlook aus derselben E-Mail-Domäne behoben.
- Behebt ein Problem, bei dem das Schloss-Symbol nicht im Header von S/MIME-verschlüsselten Nachrichten angezeigt wurde.
- Behebt ein Problem, das bewirkte, dass Anhänge beim unverschlüsselten Senden von S/MIME-Nachrichten entfernt wurden.
- Behebt ein Problem, durch das nur-Text-S/MIME-Nachrichten beim Senden unlesbar wurden.
- Behebt ein Problem, durch das Anhänge beschädigt wurden, wenn eine S/MIME-E-Mail unverschlüsselt gesendet wurde.
- Behebt ein Problem, das bewirkte, dass Benutzer OneDrive Anlagen von außerhalb ihres Mandanten nicht auf dem lokalen Computer speichern konnten, wenn sie im Dialogfeld Sicherheit die Option Speichern auswählten.
- Behebt ein Problem, das bewirkte, dass Empfänger nicht in der Lage waren, geschützte Nachrichten zu speichern, auch wenn der Absender die Berechtigung „Speichern unter" erhalten hatte.
- Behebt ein Problem, bei dem die Beschriftungen für einige Optionen für die erweiterte Suche in einigen Sprachen abgeschnitten wurden.

### <a name="project"></a>Projekt

- Wir haben ein Problem behoben, bei dem die in der Task Board-Ansicht aufgelisteten Aufgaben nicht mit denen im Dialogfeld "Ressourcen zuordnen" synchronisiert wurden.
- Wir haben ein Problem behoben, bei dem beim Kopieren und Einfügen einer Aufgabe mit mehreren Abhängigkeiten nicht alle Abhängigkeiten korrekt kopiert wurden.

### <a name="word"></a>Word

- Wir haben ein Problem behoben, bei dem der Befehl 'Editor' deaktiviert wurde, als sich der Fokus in einem Kommentartextfeld befand.
- Wir haben ein Problem behoben, bei dem der Befehl 'Markup anzeigen' deaktiviert wurde, als sich der Fokus in einem Kommentartextfeld befand.
- Wir haben ein Problem in benutzerdefiniertem XML behoben, bei dem der Status der Kommentare beim Öffnen des Dokuments verloren geht.

### <a name="office-suite"></a>Office-Suite

- Wir haben ein Problem behoben, durch das, nach dem der User ein neues App-Fenster über die Taskleiste geöffnet und ein neues leeres Dokuments erstellt hatte, zusätzliche Dateien erstellt wurden.
- Wir haben ein Problem behoben, bei dem ein Benutzer, der ein Dokument bearbeitete, aber zwischenzeitlich die Berechtigungen verloren hatte, wir den Benutzer nicht darüber informierten, dass er sich erneut authentifizieren musste.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-july-10"></a>Version 2008: 10. Juli
*Version 2008 (Build 13102.20002)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem die Option "Weiterleitung zulassen" in den "Antwortoptionen" für Kalenderbesprechungen nicht angezeigt wurde, wenn die Option für das Herunterladen freigegebener Ordner NICHT aktiviert war.
- Es wurde ein Problem behoben, bei dem die Schaltfläche "Drucken" als deaktiviert angezeigt wurde, auch wenn der Benutzer über die entsprechenden Druckberechtigungen verfügte.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem beim Versuch, ein PDF/XPS aus Project in einer SharePoint-Dokumentbibliothek zu speichern, nichts geschah.

### <a name="word"></a>Word

- Ein Problem wurde behoben, bei dem Word nicht mehr reagierte, nachdem Text und ein Bild in ein Kommentarfeld eingefügt wurden.
- Ein Problem wurde behoben, bei dem die Schaltfläche "Neuer Kommentar" nach dem Löschen des letzten Kommentars deaktiviert wurde.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2007-july-03"></a>Version 2007: 03. Juli
*Version 2007 (Build 13029.20006)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Erstellen von schnellen Umfragen in Outlook:** Erstellen Sie schnell und einfach eine Umfrage, sammeln Sie Stimmen sammeln und erhalten Sie die Ergebnisse per E-Mail. [Weitere Informationen](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- **Neue Raumsuche:** Suchen Sie in unterschiedlichen Kategorien nach Konferenzräumen.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem Datenmodelltabellen, die in bestimmten Excel-Versionen erstellt wurden, in der "Tabellenvorschau" nicht angezeigt wurden, selbst wenn die mit der Tabelle verknüpfte Abfrage nicht bearbeitet wurde.
- Ein Problem wurde behoben, bei dem das Deaktivieren von "Relativ/Absolut ignorieren"-Bezügen im Dialogfeld "Namen definieren \ Namen anwenden" dazu führte, dass Formeln nicht funktionierten.
- Es wurde ein Problem behoben, bei dem durch das Löschen eines erweiterten Datenfilters die Tabellenformatierung verloren gehen konnte.
- Ein Problem wurde behoben, bei dem in der Dokumentbeschriftung der vollständige Pfad eines eingebetteten PDF-Dokuments und nicht nur der Dateiname angezeigt wurde.
- Ein Problem wurde behoben, bei dem es nach dem Deaktivieren des Wolfram Cloud-Connectors und dem anschließenden Speichern und erneuten Öffnen einer Excel-Arbeitsmappe zu einem Absturz kommen konnte.
- Es wurde ein Problem behoben, durch das das Starten von Excel mit aktiviertem Solver-Add-in zu einem Absturz führte.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem Outlook nicht mehr reagierte, wenn mehr als 130 Empfänger in der Zeile "An" vorhanden waren; darüber hinaus wurde auch die Leistung beim Renderns des Texts verbessert.
- Es wurde ein Problem in der "Aufgabenleiste" behoben, bei dem für Ereignisse, die mehr als zwei Tage dauerten, für alle nachfolgenden Tage dieselbe Endzeit angezeigt wurde.
- Es wurde ein Problem behoben, das bewirkt hat, dass die Nachrichtenliste von Outlook-Benutzern, nachdem diese freigegebene Kalender verwendet hatten, einige Minuten lang nicht mehr aktualisiert wurde.

### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, durch das beim Einfügen von HTML in einen Textbereich auf einer Folie dieser stattdessen in ein Textfeld eingefügt wurde, das am oberen Rand der Folie erstellt wurde.
- Ein Problem wurde behoben, bei dem die Auswahl aller Folien in der Referentenansicht, das anschließende Verlassen der Referentenansicht mittels Alt+Tab und die Rückkehr zur Bildschirmpräsentation und das Klicken auf "Präsentation beenden" zu einem Ausnahmefehler führte.

### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem Project beim Öffnen bestimmter XML-Dateien abstürzte.
- Ein Problem wurde behoben, bei dem keine Projektdatei aus einer SharePoint-Dokumentbibliothek geöffnet werden konnte, wenn sich die Bibliothek im modernen Modus befand.
- Es wurde ein Problem behoben, bei dem Projekte aus Project Web App im Project-Desktopclient nicht geöffnet werden konnten, wenn die URL in ".com" endete.

### <a name="word"></a>Word

- Es wurde ein Problem in der gemeinsamen Dokumenterstellung behoben, bei dem wenn beim Zusammenführen ein Konflikt vorlag und der Benutzer bereits Änderungen verworfen hatte, die Option zum Speichern oder Verwerfen von Änderungen nicht mehr angezeigt wurde.
- Es wurde ein Problem behoben, das beim Speichern einer Datei, die ein Makro enthielt, unter einem neuen Namen dazu führte, dass sie mit einer .docx-Erweiterung und dem Dateinamen "WRO0004.docx" gespeichert wurde, und zwar unabhängig davon, was der Benutzer eingegeben hatte, wodurch das Dokument unbrauchbar wurde.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2007-june-26"></a>Version 2007: 26. Juni
*Version 2007 (Build 13020.20004)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Access

- Ein Problem wurde behoben, bei dem der Tabellenverknüpfungs-Manager einen Primärschlüssel anforderte, wenn eine verknüpfte SQL-Tabelle aktualisiert wurde.
- Es wurde ein Problem behoben, das dazu führte, dass Abfragen im Abfrage-Editor aus dem sichtbaren Bereich verschwanden.
- Ein Problem wurde behoben, bei dem die Abfrageausführung ungefähr doppelt so lange dauerte als erwartet.

### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, bei dem Benutzer nicht in der Lage waren, "Senden als" oder "Senden im Auftrag von" einer Verteilerliste zu senden.
- Es wurde ein Problem behoben, das dazu führte, dass wenn ein Bild inline in eine Nachricht eingefügt wurde und die Nachricht dann als Entwurf gespeichert wurde, dies zu einer Größenänderung bei dem Bild führte.
- Es wurde ein Problem behoben, das bewirkt hatte, dass der Text einer NDR-Nachricht nach der Bearbeitung des Betreffs von Unicode in ASCII geändert wurde.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem Project Planner-Links in Government Community Cloud-Umgebungen deaktiviert wurden.

### <a name="office-suite"></a>Office-Suite

- Es wurde ein Problem behoben, durch das in eine skalierbare Vektorgrafik (Scalable Vector Graphic, SVG) eingefügter Text nach deren Einfügen in eine Word-, Excel- oder PowerPoint-Datei, dem Speichern und Schließen der Datei und erneutem Öffnen der Datei unlesbar war.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2007-june-19"></a>Version 2007: 19. Juni
*Version 2007 (Build 13012.20000)*

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem CustomUI XML für eine benutzerdefinierte Menüband-Registerkarte beim Speichern einer Arbeitsmappe in SharePoint/OneDrive entfernt wurde.
- Ein Problem wurde behoben, bei dem Arbeitsmappen schreibgeschützt waren, wenn für die Datei nur die Empfehlung des Schreibschutzes vorlag.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem das IME-Fenster (Eingabemethoden-Editor) den zugrunde liegenden Text, der über den IME eingegeben wird, überlappte, wenn mehrere Monitore mit unterschiedlichen Auflösungen verwendet wurden.
- Es wurde ein Problem behoben, durch das Benutzern beim Schließen eines vorher gespeicherten Termins der folgende Fehler angezeigt wurde: "Das Element kann nicht gespeichert werden, da es von einem anderen Benutzer oder in einem anderen Fenster geändert wurde. Möchten Sie eine Kopie im Standardordner für das Element erstellen?"
- Ein Problem wurde behoben, durch das die Datumsangaben im Minikalender für Benutzer in Japan nicht fett formatiert angezeigt wurden.
- Wir haben ein Problem behoben, das verhinderte, dass in Kalendererinnerungen genaue Uhrzeiten für Besprechungen in weniger als einer Woche angezeigt wurden.

### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem der Farbindikator für Abwesenheiten eines Benutzers während einer aktiven Sitzung zur gemeinsamen Dokumenterstellung nicht im Katalog für die gemeinsame Dokumenterstellung aktualisiert wurde.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, dass dazu führte, dass wenn Vorgänge mit fester Dauer zu 100 % abgeschlossen waren, das Ist-Ende aber nicht angegeben war, bei "Vorgang zu % abgeschlossen" weniger als 100 % angezeigt wurde.

### <a name="word"></a>Word

- Ein Problem wurde behoben, bei dem die Farbe von HTML-Links nicht ordnungsgemäß gerendert wurde.

### <a name="office-suite"></a>Office-Suite

- Ein Problem wurde behoben, bei dem URLs, die nicht auf HTTP oder HTTPS basierten, nicht in der Liste "Zuletzt verwendet" angezeigt wurden.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2007-june-12"></a>Version 2007: 12. Juni
*Version 2007 (Build 13006.20002)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Abrufen von Organisationsdaten aus Power BI mithilfe von Datentypen:** Excel-Datentypen aus Power BI werden nun für Insider in Organisationen mit Office 365 E5/A5 oder Microsoft 365 E5/A5 bereitgestellt. Benötigte Informationen abrufen und deren einfache Aktualisierung ist für viele tägliche Abläufe von entscheidender Bedeutung. Sie erhalten Zugriff auf Ihre Unternehmens-oder Organisationsinformationen aus Power BI als Datentyp in Excel. Dadurch wird die Möglichkeit, verknüpfte Informationen in Tabellen einzugben, erweitert.  [Weitere Informationen](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Access

- Es wurde ein Problem behoben, das dazu führte, dass Microsoft Access eine Identitätsspalte in einer verknüpften SQL Server-Tabelle nicht identifizierte, was dazu führen konnte, dass Zeilen fälschlicherweise als gelöscht gemeldet werden.

### <a name="excel"></a>Excel

- Ein Problem wurde behoben, bei dem die wichtigsten Netzlinien von Netzdiagrammen nicht ordnungsgemäß formatiert werden konnten.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem das Ereignis "ProjectBeforeTaskChange" nicht ausgelöst wurde, wenn eine Änderung am Projektzusammenfassungsvorgang – entweder am Projektstart/Aufgabenfeld – vorgenommen wurde.
- Es wurde ein Problem behoben, bei dem bei einem Basisplan-Reset oder -Update u. U. Zeitphasen-Kosten-/Arbeitsbudgetressourcen geändert wurden und die Baseline falsche Budgetwerte wiedergab.

### <a name="word"></a>Word

- Ein Problem wurde behoben, bei dem die Möglichkeit, die Formatierung im Kommentarbereich über die Schaltfläche "Formatierung löschen" im Office-Menüband zu deaktivieren, nicht funktionierte.
- Ein Problem wurde behoben, bei dem das Ändern der Größe einer Tabelle bei nicht angezeigtem Lineal dazu führte, dass andere Anwendungen, die im Hintergrund ausgeführt wurden, zu blinken begannen.
- Es wurde ein Problem behoben, bei dem im Modus "Gemeinsame Dokumenterstellung" Antworten auf Kommentare manchmal nicht im Kommentarbereich angezeigt wurden, sondern im Bereich "Überprüfungen".
- Es wurde ein Problem behoben, bei dem wenn in Word eine Liste mit mehr als 50 häufig geöffneten Dokumenten vorlag, nach dem Speichern und Öffnen eines Dokuments ein Versionsverlauf angezeigt wurde, selbst wenn keine Änderungen an diesem Dokument vorgenommen wurden.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-june-05"></a>Version 2006: 05. Juni
*Version 2006 (Build 13001.20002)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Sortieren/filtern während der Zusammenarbeit in Excel:** Sie können in Ihrer Excel-Datei jetzt sortieren und filtern, während Sie mit anderen zusammenarbeiten. Dieses neue Feature stellt sicher, dass Sortierungen und Filter anderer Benutzer, während Sie das Dokument gemeinsam erstellen, für Sie keine Auswirkungen haben.

- **Erstellen von PivotTables aus Datasets in Power BI in Excel:** Sie können mit wenigen Klicks PivotTables in Excel erstellen, die mit in Power BI gespeicherten Datensätzen verbunden sind.  Auf diese Weise können Sie sowohl PivotTables als auch Power BI optimal nutzen. Sie können Ihre Daten mit PivotTables aus Ihren sicheren Power BI-Datensätzen berechnen, zusammenfassen und analysieren. [Weitere Informationen](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a>Outlook

- **Schnelles Wiederöffnen von Elementen aus der vorherigen Sitzung:** Wir haben eine Option zum schnellen Wiederöffnen von Elementen aus einer vorherigen Outlook-Sitzung hinzugefügt. Unabhängig davon, ob Outlook abstürzt oder ob sie es schließen, jetzt können Sie beim erneuten Öffnen der App Elemente schnell neu starten. Diese Funktion ist standardmäßig aktiviert. Um Sie zu deaktivieren, wechseln Sie zu Optionen > Allgemein > Startoptionen.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem benutzerdefinierte Werte auf der Diagrammachse nicht korrekt angewendet wurden.
- Es wurde ein Problem behoben, bei dem Arbeitsblätter, die mehrere Formeln mit definierten Namen enthielten, zu längeren Zeiten beim Speichern von Dateien geführt haben.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem das IME-Fenster (Eingabemethoden-Editor) den zugrunde liegenden Text, der über den IME eingegeben wird, überlappte, wenn mehrere Monitore mit unterschiedlichen Auflösungen verwendet wurden.
- Es wurde ein Problem behoben, bei dem die Anzeige einer Vorlage beim Verfassen einer neuen E-Mail-Nachricht zu einem Absturz führen konnte.
- Es wurde ein Problem behoben, bei dem Benutzer nach der Outlook-Version 1911 nicht in der Lage waren, öffentliche Ordner von Exchange 2010 zu öffnen.
- Es wurde ein Problem behoben, bei dem die Schaltfläche "Kategorisieren" für Gruppenkalender im Office-Menüband deaktiviert wurde.
- Es wurde ein Problem behoben, das bei Benutzern mit widersprüchlichen Kontakten zu Abstürzen in Outlook führen konnte.
- Es wurde ein Problem behoben, das dazu führte, dass die Dropdown-Liste "Online-Archiv" in den Ordnereigenschaften für Benutzer mit Monitoren mit hohem DPI-Wert nicht angezeigt wurde.
- Es wurde ein Problem behoben, das zu einem Absturz in Outlook führte, wenn Benutzer mit Verknüpfungen in E-Mails im Format "Nur Text" arbeiteten.
- Es wurde ein Problem behoben, das dazu führte, dass Outlook lange Dateinamen, die mit RFC2231 kodiert sind, nicht analysieren konnte.
- Es wurde ein Problem behoben, das bei Outlook-Benutzern bei der Verwendung von Sprachausgaben zu zeitweiligen Aussetzern führte.

### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem beim Öffnen von Server-konfigurierten Dateien mit formularbasierter Authentifizierung behoben.
- Es wurde ein Problem behoben, bei dem PowerPoint-Dateien mit eingebetteten Diagrammen/Arbeitsmappen zu Fehlern beim Speichern der Datei führen konnten.
- Es wurde ein Problem behoben, bei dem ein Kommentarbereich, der vom Benutzer geschlossen wurde, automatisch wieder geöffnet wurde.
- Es wurde ein Problem behoben, bei dem der Folieneditor von einer Folie die nächste überlappte.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, das verhinderte, dass verwaiste Aufgaben gelöscht oder neu zugewiesen werden konnten, nachdem ihr übergeordneter Plan gelöscht wurde.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem die Zeitstempel in den Kommentarbereichen nicht auf der Systemgebietszeit basierten.
- Es wurde ein Problem behoben, bei dem die Kommentare zwischen der Webanwendung und der Desktopanwendung nicht synchronisiert wurden.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)


## <a name="version-2006-may-29"></a>Version 2006: 29. Mai
*Version 2006 (Build 12920.20000)*

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Zusätzliche Schaltflächen zu Outlook-Toastbenachrichtigungen hinzugefügt:** In Outlook-Toastbenachrichtigungen werden nun Schaltflächen für schnelle Aktionen angezeigt, wenn Outlook unter Windows 10 ausgeführt wird.

### <a name="powerpoint"></a>PowerPoint

- **Verbesserte Stream-Video-Leistung in PowerPoint:** Wir haben die Wiedergabeleistung von Microsoft Stream-Videos verbessert, um die Ladezeit von Videos zu minimieren und eine reibungslose Wiedergabe zu ermöglichen.  Verwenden Sie Ihre Unternehmensvideos aus Microsoft Stream, um bessere Präsentationen zu erstellen.

[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme

### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem Excel gelegentlich beim Einschalten von OneDrive heruntergefahren wurde.
- Es wurde ein Problem behoben, bei dem das Klicken auf eine mit einem Lesezeichen versehene Verknüpfung innerhalb derselben Arbeitsmappe dazu führte, dass die Arbeitsmappe ausgeblendet wurde.
- Es wurde ein Problem behoben, bei dem einige kopierte und eingefügte Diagrammverknüpfungen zugeordnete Laufwerksadressen anstelle von Universaladressen verwendeten.
- Es wurde ein Problem behoben, bei dem Excel u. U. nicht mehr reagierte, nachdem STRG+UMSCHALT+Pfeiltasten zum Scrollen verwendet wurden, wenn das Excel-Fenster über Microsoft Teams gemeinsam genutzt wurde.

### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem Folien nach dem Zoomen mit dem Mausrad nicht zentriert waren.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem beim Kopieren und Einfügen von Text in einen Kommentarbereich dieser nicht angezeigt wurde.
- Es wurde ein Problem behoben, bei dem Kommentar-Hinweisblasen bei einer Vergrößerung von 100 % verschwommen erschienen.
- Es wurde ein Problem behoben, bei dem die Aktivierung der Richtlinie Word 2007 und später Binärdokumente und -vorlagen dazu führen konnte, dass einige Fälle gemeinsamer Dokumentenerstellung fehlschlugen.
- Es wurde ein Problem behoben, bei dem Dateien mit langen Pfadnamen (größer als 32K) nicht geöffnet werden konnten und keine entsprechende Fehlermeldung angezeigt wurde.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)


## <a name="version-2006-may-22"></a>Version 2006: 22. Mai
*Version 2006 (Build 12914.20000)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **In angeheftete Ordner speichern:** Das Anheften Ihrer Ordner erleichtern das Speichern von Office-Dateien. Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die Ordner haben möchten, die beim Speichern einer neuen Datei verfügbar sind. Wir freuen uns, Ihnen eine neue Funktion zur Verfügung stellen zu können: Anheften Ihrer Ordner im Dialogfeld "Speichern". Mit dieser neuen Funktion können Sie Ihre Word-, Excel- und PowerPoint-Dateien einfacher speichern.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="powerpoint"></a>PowerPoint

- **In angeheftete Ordner speichern:** Das Anheften Ihrer Ordner erleichtern das Speichern von Office-Dateien. Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die Ordner haben möchten, die beim Speichern einer neuen Datei verfügbar sind. Wir freuen uns, Ihnen eine neue Funktion zur Verfügung stellen zu können: Anheften Ihrer Ordner im Dialogfeld "Speichern". Mit dieser neuen Funktion können Sie Ihre Word-, Excel- und PowerPoint-Dateien einfacher speichern.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="word"></a>Word

- **In angeheftete Ordner speichern:** Das Anheften Ihrer Ordner erleichtern das Speichern von Office-Dateien. Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die Ordner haben möchten, die beim Speichern einer neuen Datei verfügbar sind. Wir freuen uns, Ihnen eine neue Funktion zur Verfügung stellen zu können: Anheften Ihrer Ordner im Dialogfeld "Speichern". Mit dieser neuen Funktion können Sie Ihre Word-, Excel- und PowerPoint-Dateien einfacher speichern.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem die Fehlermeldung "Diese Arbeitsmappe wird derzeit von einer anderen Arbeitsmappe referenziert und kann nicht geschlossen werden" erschien, weil Add-Ins in alphabetischer Reihenfolge und nicht in einer vom Benutzer festgelegten Reihenfolge geladen wurden.
- Es wurde ein Problem behoben, bei dem der Speicher bei der Verwaltung von Schriftarten zwischen Excel und einigen Hilfstechnologie-Anwendungen von Drittanbietern beschädigt wurde.
- Es wurde ein Problem behoben, bei dem Excel abstürzte, wenn Add-Ins auf Arbeitsblättern, die Shapes mit „noSelect“-Sperren enthielten, nach „Hostelemente“ fragen.

### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem das Ereignis "Folder.BeforeItemMove" nicht korrekt ausgelöst wurde, wenn ein Benutzer Elemente zwischen Ordnern verschoben hatte.
- Es wurde ein Problem behoben, bei dem Benutzern Kalendereinträge, welche die Mitternachtsschwelle überschritten, als ganztägige Ereignisse angezeigt wurden.
- Es wurde ein Problem behoben, bei dem Outlook abstürzte, wenn zwei Add-Ins eine Schaltfläche zur gleichen Gruppe im Menüband hinzufügten.
- Es wurde ein Problem behoben, bei dem Benutzer nicht in der Lage waren, einen Kalender für einen Gastbenutzer freizugeben.

### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem Project nach dem Klicken auf "Optionen" abstürzte.

### <a name="word"></a>Word

- Es wurde ein Problem behoben, bei dem Verknüpfungen in Kommentaren nicht funktionierten.
- Es wurde ein Problem behoben, bei dem das Vergrößern und Verkleinern des Präsentationsbereichs zu einer Lücke zwischen der gezoomten Auswahlzone und dem Mauszeiger führte.
- Es wurde ein Problem behoben, bei dem das Einfügen von HTML in WordMail für Kalender nicht funktionierte.
- Es wurde ein Problem behoben, bei dem die Beantwortung eines Kommentars in einer gemeinsam verfassten Sitzung manchmal zum Einfrieren von Word führen konnte.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2006-may-15"></a>Version 2006: 15. Mai
*Version 2006 (Build 12905.20000)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Eine PDF-Verbindung herstellen:** Herstellen einer Verbindung zu, Importieren und Aktualisieren von Daten aus einer PDF-Datei. [Weitere Informationen](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

- **Automatisches Anwenden oder Empfehlen von Vertraulichkeitsbezeichnungen:** Office kann eine Vertraulichkeitsbezeichnung basierend auf den erkannten vertraulichen Inhalten empfehlen oder automatisch anwenden.

### <a name="outlook"></a>Outlook

- **Finden Sie genau das, was Sie benötigen:** Schränken Sie die Suche mit Optionen wie Ordner, Absender, Datum, Anlageninformationen und mehr ein.

### <a name="powerpoint"></a>PowerPoint

- **Kein Clicker benötigt: das erledigen Ihre Ohrhörer**: Verwenden Sie Ihre Surface Earbuds, um Ihre PowerPoint-Präsentationen zu steuern. Wichtig: Sie müssen Ihre Surface Earbuds in der Surface Audio-App für Windows 10 koppeln, um Gesten für die Steuerung von Präsentationen verwenden zu können. Anweisungen für die ersten Schritte mit der Surface Audio-App unter Windows 10 finden Sie hier. [Weitere Informationen](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- **Automatisches Anwenden oder Empfehlen von Vertraulichkeitsbezeichnungen:** Office kann eine Vertraulichkeitsbezeichnung basierend auf den erkannten vertraulichen Inhalten empfehlen oder automatisch anwenden.

### <a name="word"></a>Word

- **Automatisches Anwenden oder Empfehlen von Vertraulichkeitsbezeichnungen:** Office kann eine Vertraulichkeitsbezeichnung basierend auf den erkannten vertraulichen Inhalten empfehlen oder automatisch anwenden.

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme

### <a name="excel"></a>Excel
- Es wurde ein Problem behoben, das zur Verbesserung der Leistung führte, wenn zusammengeführte Spalten gelöscht wurden.
- <div>Es wurde ein Problem behoben, das dazu führte, dass Druckernamen in der Liste der verfügbaren Drucker dupliziert wurden.</div>

### <a name="powerpoint"></a>PowerPoint
- Ein Problem wurde behoben, bei dem Tastenkombinationen und die Rechtschreibprüfung bei Verwendung einer Schweizer Englisch-Tastatur (QWERTZ) nicht erwartungsgemäß funktionierten.

### <a name="word"></a>Word
- Es wurde ein Problem behoben, bei dem beim Hinzufügen eines neuen Kommentars zu einem leeren Dokument nichts geschah.
- Es wurde ein Problem behoben, bei dem das Einfügen oder Aktualisieren eines Indexes in einem Dokument mit mehr als hundert Einträgen zum Absturz der Anwendung führte.
- Es wurde ein Problem behoben, durch das Dateien mit benutzerdefinierten XML-Werten extrem langsam geöffnet wurden.

### <a name="office-suite"></a>Office-Suite
- Es wurde ein Problem in Visual Basic for Applications in Microsoft Office behoben, bei dem bestimmte VBA-Projekte, die Verweise auf Codebibliotheken mit DBCS-Zeichen im Bibliotheksnamen oder Bibliothekspfad enthielten, von der Office-Anwendung beim Laden als fehlerhaft angesehen wurden.


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

- **Drücken Sie sich mit animierten GIFs aus:** Animierte GIFs werden nun im Office-Editor unterstützt – Ihre Dokumente werden noch pfiffiger aussehen.

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

- **Das Dialogfeld „Tabelle anzeigen“ umgehen, direkt zu einem Aufgabenbereich wechseln und das Hinzufügen von Tabellen zu Beziehungen und Abfragen rationalisieren:** Fügen Sie Tabellen und Abfragen hinzu, indem Sie auf vier Registerkarten klicken, Namen mehrfach auswählen, nach Text suchen und aus einem Aufgabenbereich ziehen, der während der Arbeit geöffnet bleibt.

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

- Diese Änderung ist gegen Verzögerungen bei der Verarbeitung von Bildern mit fehlerhaften oder ungültigen Protokollinformationen gerichtet.

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
- **Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern. [Weitere Informationen](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="powerpoint"></a>PowerPoint
- **Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern. [Weitere Informationen](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="word"></a>Word
- **Vertraulichkeitsbezeichnungen**: Sie können jetzt eine von Ihrer Organisation konfigurierte Vertraulichkeitsbezeichnung anwenden, um benutzerdefinierte Berechtigungen anzufordern. [Weitere Informationen](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

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

[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSWENDE)

[//]: # (FEATUREDETAILS CONTENT START NICHT ENTFERNEN)

## <a name="version-2003-february-28"></a>Version 2003: 28. Februar
*Version 2003 (Build 12619.20002)*

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Benachrichtigung Über Vorfall für IT-Administratoren:** Globale Administratoren von Microsoft 365-Mandanten und Administratoren von Office-Apps werden über Outlook und O365 Exchange-Vorfällen benachrichtigt, die sich auf Ihre Benutzer auswirken – mit einer neuen Benachrichtigung im rechten Seitenbereich in Outlook für Windows. [Weitere Informationen](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a>PowerPoint

- **Verbesserte Freihand-Shape-Diagrammdarstellung:** Zeichnen Sie bessere Diagramme und lassen Sie diese in ein Office-Objekt umwandeln, das Sie bearbeiten können. [Weitere Informationen unter](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)

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


[//]: # (ADMIN CENTER-METADATENINHALT NICHT ÄNDERN BEGINN)
[//]: # (|Win32|DevMain|Insiders| |16.0.13901.20036|version-2103-march-05|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13819.20006|version-2103-february-26|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13811.20002|version-2103-february-19|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13806.20000|version-2103-february-12|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13801.20004|version-2102-february-05|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13721.20008|version-2102-january-29|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13714.20000|version-2102-january-22|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13707.20008|version-2102-january-15|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13704.20000|version-2102-january-08|)
[//]: # (|Win32|DevMain|Insiders| |16.0.13624.20002|version-2101-january-01|)
[//]: # (ADMIN CENTER-METADATENINHALT NICHT ÄNDERN ENDE)

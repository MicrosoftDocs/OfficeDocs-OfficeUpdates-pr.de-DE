---
title: Anmerkungen zu dieser Version für Office-Insider
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.date: 7/5/2019
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt der Zielgruppe von Insiders Fast die aktuelle Liste neuer Features, Fehlerkorrekturen oder bekannter Probleme bereit.
ms.openlocfilehash: c6d380fac5fa002179597a7e32002e1889482063
ms.sourcegitcommit: eea73f35ff3045e556ae603f9c6e18fa4fed6158
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/10/2019
ms.locfileid: "35607369"
---
# <a name="release-notes-for-office-insiders"></a>Anmerkungen zu dieser Version für Office-Insider

Dieser Artikel enthält Versionshinweise zu Insider-Builds von Word, Excel, PowerPoint, Outlook, Access und Project für Windows Desktop. Jede Woche heben wir interessante neuer Features, wichtige Fixes und wesentliche Probleme hervor, über die wir Sie gerne informieren möchten. Beachten Sie, dass das Rollout von Funktionen (und manchmal auch Fixes) für Insider häufig über einen längeren Zeitraum erfolgt. Auf diese Weise können wir sicherstellen, dass alles reibungslos funktioniert, bevor das Feature für ein breiteres Publikum bereitgestellt wird. Wenn also im Folgenden etwas nicht beschrieben wird, machen Sie sich keine Sorgen, es wird bald behandelt werden.  

> [!NOTE]
> - Versionshinweise werden wöchentlich veröffentlicht und können eine Kompilierung mehrerer Builds sein.
> - Das Veröffentlichungsdatum der Versionshinweise stimmt möglicherweise nicht mit dem tatsächlichen Veröffentlichungsdatum des Builds überein.

 > [!NOTE]
> - Microsoft Teams für vorhandene Installationen von Office 365 ProPlus – ab Ende Juni wird Microsoft Teams beim Aktualisieren dieser Installationen in bestehende Installationen von Office 365 ProPlus (und Office 365 Business) einbezogen. Ab welchem Datum Microsoft Teams hinzugefügt wird, hängt davon ab, welchen Updatekanal Sie verwenden. Weitere Informationen hierzu finden Sie unter [Bereitstellen von Microsoft Teams mit Office 365 ProPlus](https://docs.microsoft.com/de-DE/deployoffice/teams-install).

## <a name="july-5-2019"></a>5. Juli 2019
Version 1907 (Build 11901.20018)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="word-excel-powerpoint"></a>Word, Excel, PowerPoint

#### <a name="sketchy-shapes"></a>Skizzenhafte Formen!

Mitten im Entwurfs einer Präsentation? Wenden Sie die Formatvorlage "Skizzenhaft" an, um anzuzeigen, dass Sie zurzeit noch am Entwurf arbeiten. Dies verleiht Ihren Objekten eine persönliche Note, ohne sie in von Hand gezeichnete Freiformobjekte umzuwandeln.

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

Wenn Sie in Office auf einen Dokument Link klicken, können Sie Ihre Einstellungen dahingehend aktualisieren, dass er standardmäßig in der Word-App geöffnet wird.  Um Ihre Einstellungen zu aktualisieren, wechseln Sie zu Datei > Optionen – > Erweitert-> Verhalten von Links. Weitere Informationen: https://support.office.com/de-DE/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

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

Wenn Sie in Office auf einen Präsentationslink klicken, können Sie Ihre Einstellungen dahingehend aktualisieren, dass er standardmäßig in der PowerPoint-App geöffnet wird. Um Ihre Einstellungen zu aktualisieren, wechseln Sie zu Datei > Optionen – > Erweitert-> Verhalten von Links. Weitere Informationen: https://support.office.com/de-DE/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

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

Wenn Sie in Office auf einen Link zu einer Arbeitsmappe klicken, können Sie Ihre Einstellungen dahingehend aktualisieren, dass diese standardmäßig in der Excel-App geöffnet wird. Um Ihre Einstellungen zu aktualisieren, wechseln Sie zu Datei > Optionen – > Erweitert-> Verhalten von Links. Weitere Informationen: https://support.office.com/de-DE/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

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

Lerntools in Word unterstützt weitere Farben für Seitendesigns, wodurch die Hintergrundfarbe der Seite geändert werden kann.  Viele Personen haben Herausforderungen beim Lesen mit einem ganz weißen oder schwarzem Hintergrund, deshalb haben wir die Auswahl von Farben in Word auf PC und Mac erweitert.

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
- Ein Problem mit einem Absturz wurde behoben, der beim Drücken von ESC in "Optionen" auftrat
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
- Ein Problem mit einem Absturz wurde behoben, der beim Drücken von ESC in "Optionen" auftrat
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
- Der Name muss mit "!!"  (zwei Ausrufezeichen) beginnen, damit er beim Morphen zum Überschreiben des Standardabgleichsverhaltens verwendet wird, z. B. "!!Name".
- Benutzer können Formen weiterhin mit beliebigen Namen umbenennen, die nicht mit "!!" beginnen,  ohne dass dadurch die Funktionsweise von Morph geändert wird.

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
- Ein Problem wurde behoben, bei dem das Einfügen eines lokalen Videos in die PPT-Datei den Festplattenspeicher des Laufwerks C reduzierte.
- Die Schaltfläche "In Microsoft Stream veröffentlichen", die einigen Benutzern nicht angezeigt wurde, wurde korrigiert.

### <a name="outlook"></a>Outlook
- Ein Problem wurde behoben, bei dem die Aufgabenansicht im Kalender das Thema der Aufgabe nicht richtig anzeigte.

### <a name="access"></a>Access
- Ein Skalierungsproblem mit Diagrammen wurde behoben

### <a name="project"></a>Project
- Verschiedene Korrekturen bei Leistungsfähigkeit und Stabilität

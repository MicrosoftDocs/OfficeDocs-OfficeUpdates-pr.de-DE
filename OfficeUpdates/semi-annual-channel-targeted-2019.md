---
title: Anmerkungen zur Version für Releases im halbjährlichen Kanal (gezielt) im Jahr 2019
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 6/11/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt IT-Experten Anmerkungen zur Version für Releases im halbjährlichen Kanal (gezielt) für Office 365 ProPlus im Jahr 2019 zur Verfügung.
ms.openlocfilehash: 715250022d6bf9172f4e1c47d1437099a63b1ff1
ms.sourcegitcommit: eea73f35ff3045e556ae603f9c6e18fa4fed6158
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/10/2019
ms.locfileid: "35607359"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2019"></a>Anmerkungen zur Version für Releases im halbjährlichen Kanal (gezielt) im Jahr 2019

Diese Anmerkungen zur Version bieten Informationen zu neuen Features und Nicht-Sicherheitsupdates, die in halbjährlichen (gezielten) Kanalupdates für Office 365 ProPlus in 2019 enthalten sind, einschließlich Visio Pro für Office 365 und Project Online Desktop Client.
 
> [!NOTE]
> - Diese Informationen gelten auch für Office 365 Business, die Version von Office, die in einigen Office 365-Plänen wie Business Premium enthalten ist.

 
> [!NOTE]
> - Die Informationen zu Sicherheitsupdates für jeden Updatekanal von Office 365 ProPlus werden ab sofort separat unter [Sicherheitsrelevante Updates](office365-proplus-security-updates.md) aufgeführt.

## <a name="version-1902-july-09"></a>Version 1902: 9. Juli 
*Version 1902 (Build 11328.20368)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/de-DE/officeupdates/office365-proplus-security-updates) aufgeführt


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
<br/>Sicherheitsupdates sind [hier](https://docs.microsoft.com/de-DE/officeupdates/office365-proplus-security-updates) aufgeführt

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Sicherheitsupdates
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
 - Ein Problem, das bewirkt, dass Dateien, die PivotTables enthalten, welche mit anderen Arbeitsmappen verknüpft sind, langsam geladen werden. Dieses Problem wurde gelöst.
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

- Behebt ein Problem, bei dem Teile eines Office-Updates nicht das Peercaching der Übermittlungsoptimierung verwenden. 
  [Weitere Informationen]("https://docs.microsoft.com/de-DE/windows/deployment/update/waas-delivery-optimization)
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
- **Die Symbole auf dem Menüband haben einen neuen Look:** Keine Sorge – alles funktioniert wie bisher. Und nun sehen die Symbole auf allen Bildschirmgrößen toll aus. [Weitere Informationen](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Möglichkeit zum Einfügen von SVGs mit angewendeten Filtern:** Office-Benutzer haben jetzt die Möglichkeit, SVGs einzufügen, auf die Filter angewendet wurden. [Weitere Informationen](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Aufzeigen, was hinter einem Bild steckt:** Platzieren Sie ein Bild in einem Arbeitsblatt, wählen Sie die Voreinstellungen aus, und beobachten Sie, wie sich die Transparenz ändert. Das ist alles! [Weitere Informationen](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **An alle Fans von "Abrufen und Transformieren"** Wenn Sie "Abrufen und Transformieren" häufig verwenden, werden Sie sich freuen, dass das Feature "Spalte aus Beispiel" verbessert wurde. Und viele Connectors wurden ebenfalls verbessert. [Weitere Informationen](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- **Verbesserte Unterstützung für hoch auflösende Displays:** Wenn Sie mehrere Monitore oder ein Laptop Dock verwenden, werden Office-Apps nun auf jedem Display präziser angezeigt, auch wenn die Displays verschiedene Skalierungseinstellungen haben. [Weitere Informationen](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="outlook-feature-updates"></a>Outlook: Featureupdates

- **Verwenden Sie "Laut vorlesen", um sich Ihre E-Mails vorlesen zu lassen:** Outlook kann Ihre E-Mail laut vorlesen und den jeweils vorgelesenen Text hervorheben. Um "Laut vorlesen" zu aktivieren, navigieren Sie zu den Einstellungen für die Barrierefreiheit. [Weitere Informationen](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- **Eingabe ohne Tippen:** Haben Sie ein Mikrofon? Klicken Sie auf "Diktieren", und beobachten Sie, wie Outlook tippt, während Sie sprechen. [Weitere Informationen](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Die Symbole auf dem Menüband haben einen neuen Look:** Keine Sorge – alles funktioniert wie bisher. Und nun sehen die Symbole auf allen Bildschirmgrößen toll aus. [Weitere Informationen](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Blockieren Sie den Download von externen Inhalten standardmäßig in über SMIME verschlüsselten und signierten E-Mails:** Aufgrund einer Schwachstelle im SMIME-Protokoll blockiert Outlook den Download von externen Inhalten für Nachrichten, die über SMIME verschlüsselt oder signiert wurden. Zum Schutz vor dem Sicherheitsrisiko können Benutzer externe Inhalte nicht mit einem Klick über die Outlook-Benutzeroberfläche herunterladen. Das Dialogfeld "Optionen" enthält eine neue Option, mit der Benutzer zum alten Verhalten zurückkehren können.
- **Deaktivieren der Weiterleitung für eine Besprechung:** Verhindern Sie, dass Teilnehmer Ihre Besprechung an andere weiterleiten. Klicken Sie im Menüband einfach auf „Antwortoptionen“. [Weitere Informationen](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- **Personenvorschläge im Terminplanungs-Assistenten:** Sehen Sie sich Empfehlungen für Teilnehmer an, die Sie beim Planen einer Besprechung hinzufügen können. Kein Hin- und Herwechseln zwischen dem Terminplanungs-Assistenten und der An-Zeile mehr. [Weitere Informationen](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)
- **Das Reservieren eines Raums ist nun noch einfacher:** Suchen Sie mithilfe mehrerer Raumlisten nach einem Konferenzraum, und wechseln Sie zwischen Listen, ohne bereits ausgewählte Räume zu verlieren.
- **Neuer Standardwert für Seriendauer:** Der Standardwert für die Seriendauer war im Dialogfeld "Serie" bisher auf "Kein Enddatum" festgelegt. Dies erleichtert die Erstellung lang andauernder Wiederholungsserien, die aber im Lauf der Zeit beschädigt werden können. Wir haben den Standardwert für das Dialogfeld "Serie" auf "Ende am" aktualisiert, so dass unser Standardwert mit den empfohlenen bewährten Methoden für die Kalenderverwaltung übereinstimmt.
- **Teilnehmen an Teambesprechungen über das Dialogfeld "Outlook-Erinnerungen":** Wenn Outlook Benutzer an eine anstehende Besprechung erinnert, wird eine Schaltfläche „Online beitreten“ angezeigt, falls die anstehende Besprechung eine Teams-Onlinebesprechung ist. Dieser Vorgang ähnelt dem Beitreten zu einer Skype for Business-Besprechung im Dialogfeld „Outlook-Erinnerungen“.
- **Keine Erinnerungen mehr für vergangene Ereignisse:** Sie können Ihren Kalender so festlegen, dass Erinnerungen für Ereignisse, die bereits abgeschlossen sind, automatisch ausgeblendet werden. [Weitere Informationen](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **Die URL hinter sicheren Links:** Sichere Links bieten Ihnen Schutz vor bösartigen URLs, die Sie in E-Mails empfangen haben, blenden dabei aber die ursprüngliche URL aus. Wenn Sie das Original anzeigen möchten, zeigen Sie mit dem Mauszeiger auf die URL. Eine Advanced Threat Protection-Lizenz ist erforderlich. 
  [Weitere Informationen](https://products.office.com/de-DE/exchange/advance-threat-protection)
- **Zoomen und Übernehmen:** Anstatt den Zoom jedes Mal anzupassen, wenn Sie eine Nachricht lesen, wählen Sie einen Standardwert für alle Nachrichten aus. [Weitere Informationen](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- **Nachrichtenverschlüsselung: IRM-Richtlinie "Nur verschlüsseln":** Die neue Option "Nur verschlüsseln" wird im Menü "Optionen" > "Berechtigungen" für Benutzer von Office 365-Nachrichtenverschlüsselung angezeigt. Mit dieser Option können Sie eine Nachricht verschlüsseln und an alle Personen innerhalb oder außerhalb Ihrer Organisation senden.
- **Warnung, wenn Sie unter "BCC" erwähnt wurden:** Der BCC-InfoTipp warnt Sie, bevor Sie versehentlich eine Antwort an alle Empfänger einer E-Mail senden, der Sie als BCC-Empfänger hinzugefügt wurden.
- **Eine flexiblere "An:"-Zeile:** Wenn Sie in die Zeile "An:" klicken, um eine Nachricht zu adressieren, schlagen wir Ihnen Empfänger vor, die Sie wahrscheinlich auswählen werden. Außerdem können Sie das jeweilige Foto sehen und wissen so, dass Sie Ihre E-Mail an die richtige Person senden. [Weitere Informationen](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- **Möglichkeit zum Einfügen von SVGs mit angewendeten Filtern:** Office-Benutzer haben jetzt die Möglichkeit, SVGs einzufügen, auf die Filter angewendet wurden. [Weitere Informationen](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Verbesserte Unterstützung für hoch auflösende Displays:** Wenn Sie mehrere Monitore oder ein Laptop Dock verwenden, werden Office-Apps nun auf jedem Display präziser angezeigt, auch wenn die Displays verschiedene Skalierungseinstellungen haben. [Weitere Informationen](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a>PowerPoint: Featureupdates

- **Schneller Einstieg** Die neu gestaltete Startseite setzt Ihre zuletzt geöffneten Dokumente in den Mittelpunkt. Greifen Sie mit weniger Klicks auf Dateien zu, und öffnen Sie Kontoeinstellungen oder Optionen direkt von hier aus.
- **Eingabe ohne Tippen:** Haben Sie ein Mikrofon? Klicken Sie auf "Diktieren", und beobachten Sie, wie PowerPoint tippt, während Sie sprechen. [Weitere Informationen](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Die Symbole auf dem Menüband haben einen neuen Look:** Keine Sorge – alles funktioniert wie bisher. Und nun sehen die Symbole auf allen Bildschirmgrößen toll aus. [Weitere Informationen](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Verbesserte Unterstützung für hoch auflösende Displays:** Wenn Sie mehrere Monitore oder ein Laptop Dock verwenden, werden Office-Apps nun auf jedem Display präziser angezeigt, auch wenn die Displays verschiedene Skalierungseinstellungen haben. [Weitere Informationen](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Links in lebendigen Farben:** Links sind nicht mehr nur blau. Wenden Sie jede gewünschte Schriftfarbe an. [Weitere Informationen](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- **Verleihen Sie Ihren Folien mehr Lebendigkeit:** Fügen Sie animierte 3D-Grafiken ein, um zu sehen, wie Herzen schlagen, Planeten sich in einer Umlaufbahn bewegen und wie ein T-Rex über den Bildschirm stampft. [Weitere Informationen](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Sie skizzieren, wir polieren:** Wir wandeln von Hand geschriebenen Text und handgezeichnete Shapes in optimierte Diagramme um. Wählen Sie einfach Ihre Freihandstriche aus, um loszulegen. [Weitere Informationen](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Aufzeigen, was hinter einem Bild steckt:** Platzieren Sie ein Bild in einem Arbeitsblatt, wählen Sie die Voreinstellungen aus, und beobachten Sie, wie sich die Transparenz ändert. Das ist alles! [Weitere Informationen](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Erstellen Sie eine hervorragende Folie:** Konvertieren Sie Ihre Freihandeingaben in Standardformen und -text, und lassen Sie sich dann von PowerPoint-Designer intelligente Folienentwurfsideen anzeigen. [Weitere Informationen](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)
- **Veröffentlichen in Microsoft Stream:** Geben Sie eine Präsentation mithilfe von Microsoft Stream noch sicherer als Video innerhalb Ihrer Organisation frei.  [Weitere Informationen](https://support.office.com/article/C140551F-CB37-4818-B5D4-3E30815C3E83)
- **Exportieren in ein 4K-Video:** Wenn Sie eine Präsentation als Video exportieren, steht nun die 4K-Auflösung zur Auswahl.  [Weitere Informationen](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **Möglichkeit zum Einfügen von SVGs mit angewendeten Filtern:** Office-Benutzer haben jetzt die Möglichkeit, SVGs einzufügen, auf die Filter angewendet wurden. [Weitere Informationen](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-feature-updates"></a>Word: Featureupdates

- **Schneller Einstieg** Die neu gestaltete Startseite setzt Ihre zuletzt geöffneten Dokumente in den Mittelpunkt. Greifen Sie mit weniger Klicks auf Dateien zu, und öffnen Sie Kontoeinstellungen oder Optionen direkt von hier aus.
- **Eingabe ohne Tippen:** Haben Sie ein Mikrofon? Klicken Sie auf "Diktieren", und beobachten Sie, wie Word tippt, während Sie sprechen. [Weitere Informationen](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Verleihen Sie Ihren Dokumenten mehr Lebendigkeit:** Fügen Sie animierte 3D-Grafiken ein, um zu sehen, wie Herzen schlagen, Planeten sich in einer Umlaufbahn bewegen und wie ein T-Rex über die Seite stampft. [Weitere Informationen](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Die Symbole auf dem Menüband haben einen neuen Look:** Keine Sorge – alles funktioniert wie bisher. Und nun sehen die Symbole auf allen Bildschirmgrößen toll aus. [Weitere Informationen](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
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
- **Installation von Microsoft Teams:** Microsoft Teams ist in Neuinstallationen von Office 365 ProPlus standardmäßig installiert. 
  [Weitere Informationen](https://docs.microsoft.com/de-DE/DeployOffice/teams-install)

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

- Behebt ein Problem, bei dem Add-Ins, die mithilfe der [zentralen O365-Office-Bereitstellung](https://docs.microsoft.com/de-DE/office/dev/add-ins/publish/centralized-deployment) bereitgestellt wurden, nicht mehr reagierten und nicht mehr verwendet werden konnten.


## <a name="version-1808-january-8"></a>Version 1808: 8. Januar
*Version 1808 (Build 10730.20264)* 

### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Sicherheitsupdates 

- Behebt ein Problem, aufgrunddessen bei Benutzern Probleme mit der Kalendersynchronisierung auftreten.

### <a name="word-non-security-updates"></a>Word: Nicht sicherheitsrelevante Sicherheitsupdates

- Verbessert die Leistung beim Öffnen.


> [!NOTE]
> Wenn Sie Hilfe bei einem Problem mit der Nutzung von Office benötigen, empfehlen wir, dass Sie Ihre Frage im [Microsoft Answers-Forum](https://answers.microsoft.com/) oder in der [Tech-Community](https://techcommunity.microsoft.com/) veröffentlichen, oder Sie können sich an den [Support](https://support.microsoft.com/contactus) wenden.
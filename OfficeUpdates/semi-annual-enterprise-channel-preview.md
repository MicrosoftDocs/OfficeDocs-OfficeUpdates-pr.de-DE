---
title: Versionshinweise für Versionen des halbjährlichen Unternehmenskanals (Vorschau) im Jahr 2020
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt IT-Experten Anmerkungen zur Version für Releases im halbjährlichen Kanal (gezielt) für Microsoft 365 Apps im Jahr 2020 zur Verfügung.
ms.openlocfilehash: e567d3139d7766b54d05e0ddf5272bc683c6f82a
ms.sourcegitcommit: 4fd6ebb878e4a30e416064d9c434c66dfc48fd47
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/11/2020
ms.locfileid: "46634871"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview-releases-in-2020"></a>Versionshinweise für Versionen des halbjährlichen Unternehmenskanals (Vorschau) im Jahr 2020

Diese Versionshinweise enthalten Informationen zu neuen Features und nicht sicherheitsrelevanten Updates, die in halbjährlichen Kanal-Updates (Vorschau) im Jahr 2020 für Microsoft 365 Apps for Enterprise, Microsoft 365 Apps for Business sowie in den Abonnementversionen der Desktop-Apps für Project und Visio enthalten sind.

> [!IMPORTANT]
> Wir nehmen einige Änderungen an den Updatekanälen für Microsoft 365-Apps vor, unter anderem fügen wir einen neuen Updatekanal hinzu (Monatlicher Enterprise-Kanal) und ändern die Namen der vorhandenen Updatekanäle. Um mehr zu erfahren, [lesen Sie diesen Artikel](https://go.microsoft.com/fwlink/p/?linkid=2127441).


## <a name="version-2002-august-11"></a>Version 2002: 11. August
*Version 2002 (Build 12527.20988)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt


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

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt


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

- Es wurde ein Absturzproblem mit dem Office-Host in Windows behoben, wenn ein Add-In aktiviert wird, während die Registrierung TabProcGrowth den Wert REG_SZ Typ hat.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-june-09"></a>Version 2002: 9. Juni
*Version 2002 (Build 12527.20720)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt


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

- Der Office-Host stürzte in Fenstern ab, wenn ein Add-In aktiviert wird, während der Registrierungsschlüssel HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth auf Null gesetzt ist. Mit dieser Änderung wird dieses Problem behoben.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2002-may-12"></a>Version 2002: 12. Mai
*Version 2002 (Build 12527.20612)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt


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

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt


### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Geben Sie eine Formel ein, die mehrere Werte zurückgibt:** Geben Sie schnell eine Formel ein, die mehrere Werte zurückgibt, und diese werden automatisch in die benachbarten Zellen übertragen. [Weitere Informationen](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- **Sechs leistungsfähige Funktionen:** Wir haben sechs neue Funktionen hinzugefügt, um Ihre Tabellenkalkulationen hochgradig zu optimieren: FILTERN, SORTIEREN, SORTIERENNACH, EINDEUTIG, SEQUENZ und ZUFALLSMATRIX.  [Weitere Informationen](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- **Schau nach links, schau nach rechts... XVERWEIS ist da!:** Finden Sie mit XVERWEIS Zeile für Zeile alles, was Sie in einer Tabelle oder einem Bereich benötigen.  [Weitere Informationen](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

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

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="access"></a>Access

- **Schnelle Suche nach verknüpften Tabellen:** Unser neues Suchfeld macht die Suche nach verknüpften Tabellen zu einem Kinderspiel. [Weitere Informationen](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a>Excel

- **Mit \@Erwähnen andere auf sich aufmerksam machen:** Mithilfe von Erwähnungen in Kommentaren können Sie Kollegen informieren, wenn Sie deren Input benötigen. [Weitere Informationen](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Finden Sie, wonach Sie suchen:** Suchen Sie Befehle, Personen, Dateien, Fotos, Webartikel und mehr. [Weitere Informationen](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- **Zeichnen Sie es auf:** Verleihen Sie Office-Shapes in Ihrer Arbeitsmappe ein ungezwungenes, von Hand gezeichnetes Aussehen. [Weitere Informationen](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Schnellere Dateifreigabe** Erteilen Sie die Freigabe für Ihre Dokumente direkt aus der Liste der zuletzt verwendeten Dateien, ohne die entsprechende Datei öffnen zu müssen.

- **Keine Umleitung zum Browser mehr:** Sie legen fest, wie Links zu Office-Dokumenten geöffnet werden: im Browser oder in der App.

- **Konzentrieren Sie sich darauf, was noch erledigt werden muss:** Wählen Sie "Auflösen" aus, um Kommentare zu reduzieren und offene Punkte hervorzuheben.

- **Erstellen von barrierefreien PDF-Dateien:** Erstellen Sie eine PDF-Datei, und die Barrierefreiheitsprüfung weist auf Barrierefreiheitsprobleme hin, die vor dem Speichern behoben werden sollten. [Weitere Informationen](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Konvertieren von Dateien zur Verbesserung der Barrierefreiheit:** Aktualisieren Sie Ihre Dateien auf das moderne Format, damit alle Personen einfacher darauf zugreifen können.

- **Add-In „Datenschnellansicht“: ** erstellen Sie schnell Visio-Flussdiagramme aus Excel. [Weitere Informationen](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

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

- **Erstellen Sie eine hervorragende Folie:** Konvertieren Sie Ihre Freihandeingaben in Standardformen und -text, und lassen Sie sich dann von PowerPoint-Designer intelligente Folienentwurfsideen anzeigen. [Weitere Informationen](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- **Weitere Symbole für Ihre Stimmung:** Wir haben über 300 neue Icons hinzugefügt. Sie finden diese unter "Einfügen" > "Symbole". [Weitere Informationen](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a>Visio

- **Zurück zum Tatort:** Verwenden Sie die neuen Schablonen "Beweismittel", "Drinnen" und "Draußen" der Vorlage "Tatortermittlung", um Tatorte im Detail nachzustellen.

- ** Erstellen Sie ansprechende Visio-Diagramme in Excel:** Erstellen Sie ein Flussdiagramm oder ein Organigramm durch Einfügen von Daten in ein Arbeitsblatt. [Weitere Informationen](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **Lebenslauf-Editor-Verknüpfung mit dem LinkedIn-Lebenslauf-Assistent:** Der Lebenslauf-Editor bietet eine Auswahl an Grammatik- und Stilprüfungen, die speziell auf Lebensläufe zugeschnitten sind, um Ihr Schreiben präziser und professioneller zu gestalten.

- **Es wurde ein Problem mit beschädigten Dokumenten behoben, das durch das Zusammenführen von 3D-Objekten verursacht wurde:** Es wurde ein Problem mit beschädigten Dokumenten behoben, das durch das Zusammenführen von 3D-Objekten verursacht wurde.

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

- Dieses Update behebt ein Problem bei der Verwendung von ADODB. Das Recorder-Objekt im VB-Code meldet möglicherweise einen Fehler falsch.

- Access-Vorlagen sollten nicht länger dazu führen, dass Anhangsspalten in einer Datenbank fehlschlagen. Nachdem Sie eine Vorlage instanziiert haben, sollten Sie nun in der Lage sein, Ihrer Datenbank ein Anhangsfeld hinzuzufügen.

### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, aufgrund dessen bei Benutzern Abstürze beim Umbenennen einer Signatur auftraten.

- Diese Änderung umgeht ein Problem mit bestimmten Intel-Grafiktreibern durch Verwendung des Softwarerenderings.

- Es wurde ein Problem behoben, durch das bei einigen Benutzern Abstürze auftraten, wenn Text in Spalten mit Zellen mit einem übergelaufenem Array konvertiert wurde.

- Dieses Update behebt ein Problem, das dazu führte, dass die Bearbeitungsleiste Text in einer anderen Schriftart als erwartet anzeigte.

- Die Funktion "Text in Spalte" funktioniert bei einigen Gebietsschemas möglicherweise nicht.

- Beim Zugriff auf einen verborgenen benannten Bereich kann ein Fehler auftreten.

- Beim Speichern von Änderungen bei der Verwendung einiger nicht englischer Zeichengruppen tritt möglicherweise ein Fehler auf.

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

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt


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

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt


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


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

> [!NOTE]
> Wenn Sie Hilfe bei einem Problem mit der Nutzung von Office benötigen, empfehlen wir, dass Sie Ihre Frage im [Microsoft Answers-Forum](https://answers.microsoft.com/) oder in der [Tech-Community](https://techcommunity.microsoft.com/) veröffentlichen, oder Sie können sich an den [Support](https://support.microsoft.com/contactus) wenden.


[//]: # (ADMIN CENTER-METADATENINHALT NICHT ÄNDERN BEGINN)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.12527.20880|version-2002-july-14|)
[//]: # (ADMIN CENTER-METADATENINHALT NICHT ÄNDERN ENDE)

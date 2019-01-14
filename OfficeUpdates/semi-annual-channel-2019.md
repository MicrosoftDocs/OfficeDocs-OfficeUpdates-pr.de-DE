---
title: Anmerkungen zur Version für Releases im halbjährlichen Kanal im Jahr 2019
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 1/11/2019
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt IT-Experten Anmerkungen zur Version für Releases im halbjährlichen Kanal für Office 365 ProPlus im Jahr 2019 zur Verfügung.
ms.openlocfilehash: 990e7afafea208c46e58d2e2b11dd6ec7555c7af
ms.sourcegitcommit: 213c572ed7392c994fc8c902bfb9d1e5aa412a4b
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/12/2019
ms.locfileid: "27992119"
---
# <a name="release-notes-for-semi-annual-channel-releases-in-2019"></a>Anmerkungen zur Version für Releases im halbjährlichen Kanal im Jahr 2019

Diese Anmerkungen zur Version enthalten Informationen zu neuen Features, Sicherheitsupdates und nicht sicherheitsrelevanten Updates, die in Office 365 ProPlus-Updates im Rahmen des halbjährlichen Kanals im Jahr 2019 enthalten sind. 

> [!NOTE]
> - Nachfolgend sind außerdem Informationen zu neuen Features, Sicherheitsupdates und nicht sicherheitsrelevanten Updates für Visio Pro für Office 365 und Project Online-Desktopclient aufgeführt.
> - Diese Informationen gelten auch für Office 365 Business, die Version von Office, die in einigen Office 365-Plänen wie Business Premium enthalten ist.
> - Der halbjährliche Kanal hieß vor Januar 2019 verzögerten Kanal.

> [!NOTE]
> - Die Informationen zu Sicherheitsupdates für jeden Updatekanal von Office 365 ProPlus werden ab sofort separat unter [Sicherheitsrelevante Updates](office365-proplus-security-updates.md) aufgeführt.

## <a name="version-1808-january-8"></a>Version 1808: 8. Januar
*Version 1808 (Build 10730.20264)*

### <a name="access-feature-updates"></a>Access: Featureupdates

 - **Daten mit neuen Diagrammen visualisieren:** Treffen Sie eine Auswahl aus 11 Diagrammen, und fügen Sie ein Diagramm zu Ihren Formularen und Berichten hinzu, um die Daten besser zu visualisieren und fundierte Entscheidungen zu treffen. [Weitere Informationen](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)


### <a name="excel-feature-updates"></a>Excel: Featureupdates
 - **Gemeinsame Bearbeitung:** Arbeiten Sie gleichzeitig mit anderen Personen in einer Arbeitsmappe. [Weitere Informationen](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)
 - **AutoSpeichern für Clouddateien ist nun standardmäßig aktiviert:** Diese Änderung bedeutet, dass Benutzer sich keine Sorgen darüber machen müssen, dass Änderungen in Dokumenten verloren gehen, die in OneDrive oder SharePoint Online gespeichert sind. Änderungen werden automatisch in der Cloud gespeichert, und Benutzer müssen nicht mehr explizit STRG + S drücken oder auf die Schaltfläche „Speichern“ klicken. Allerdings müssen die Benutzer diese Verhaltensänderung verstehen, damit sie keine versehentlichen Änderungen an Dokumenten vornehmen. Beachten Sie, dass Benutzer das automatische Speichern mithilfe der Umschalttaste „AutoSpeichern“ deaktivieren können. Es wird empfohlen, dass Sie Ihre Benutzer über diese bevorstehende Änderung informieren und sie dahingehend schulen, wie dieses neue Feature in Office 365 optimal genutzt werden kann.[Weitere Informationen zu AutoSpeichern](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Erfahren Sie, was IT-Administratoren über AutoSpeichern wissen sollten](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Verbesserte Bearbeitungsleiste für Zellen: ** Sie können nun STRG + A zum Auswählen von Text in einer Zelle oder in der Bearbeitungsleiste verwenden. Außerdem wurde die Unterstützung von Emojis und anderen komplexen Zeichen verbessert. [Weitere Informationen](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Verbesserungen an der Barrierefreiheitsprüfung:** Die Barrierefreiheitsprüfung weist eine aktualisierte Unterstützung für internationale Standards und Empfehlungen auf, sodass Sie leichter auf Ihre Arbeitsmappen zugreifen können. [Weitere Informationen](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Vermeiden unerwünschter Bearbeitungen:** Legen Sie fest, dass Ihre Arbeitsmappen schreibgeschützt geöffnet werden, um versehentliche Änderungen zu verhindern. Wechseln Sie zu „Datei“ > „Info“ > „Arbeitsmappe schützen“ > „Immer schreibgeschützt öffnen“.

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Sicherheitsupdates 

- Behebung eines Problems in Sitzungen der gemeinsamen Dokumenterstellung, bei dem ein Slicer nicht korrekt aktualisiert wird, nachdem ein anderer Benutzer einen Spaltenfilter auf die Daten in diesem Slicer angewendet hat.
- Behebung eines Problems in einer Sitzung der gemeinsamen Dokumenterstellung, bei dem einer der Benutzer die Beschriftung für einen Slicer löscht, wodurch verursacht wird, dass bei einem anderen Benutzer in der Sitzung der gemeinsamen Dokumenterstellung Excel abstürzt.
- Es wurde ein möglicher Absturz beim Erstellen mehrerer Tabellenslicer, die an dieselbe Datenspalte gebunden sind, und beim anschließendes Löschen dieser Datenspalte behoben.
- Behebung eines Problems, aufgrund dessen Excel beim Aktualisieren einer gefilterten Abfragetabelle, die umbrochenen Text in Zellen enthält, manchmal abstürzt, wenn die Option zum automatischen Anpassen der Spaltenbreite deaktiviert wurde.
- Behebung eines Problems, bei dem in Excel 2007 gespeicherte Slicer einen Absturz verursachen können, wenn sie in neueren Versionen von Excel geöffnet werden, wenn sich die Anzahl von im Slicer angezeigten Elementen ändert.
- Führt Unterstützung für die Schaltfläche „Diagnose abrufen“ ein, um die Untersuchung von Supportanfragen zu erleichtern.
- Es wurde ein Fehler behoben, bei dem PowerPivot in einigen Builds/Versionen nicht angezeigt wurde.
- Dadurch wird das Problem in Excel behoben, bei dem Excel möglicherweise nicht mehr reagiert, wenn der Benutzer den Mauszeiger in einer Arbeitsmappe mit vielen definierten Namen über Formatierungsoptionen bewegt, und bei dem Excel möglicherweise im Schnellanalysetool nicht mehr reagiert, auch wenn die Livevorschau in den Optionen deaktiviert wurde.
- Wir untersuchen derzeit die Ursachen für die geringe Leistung beim Verschieben des Excel-Anwendungsfensters von einem Desktop auf einen anderen. Wenn bei Ihnen in der Zwischenzeit diese Leistungseinbußen auftreten, können Sie als Problemumgehung die Option „Für Kompatibilität optimieren“ für „Bei Verwendung mehrerer Displays“ auf der Registerkarte „Allgemein“ im Dialogfeld „Dateioptionen“ auswählen.
- Behebung eines Problems, bei dem Excel möglicherweise abstürzt, wenn die Quelldaten eines Diagramms von seinem ursprünglichen Satz von Zellen geändert werden.
- Behebung eines Problems, bei dem eine Neuberechnung beim Öffnen nicht ausgeführt wird, auch wenn die FullCalcOnLoad-Eigenschaft festgelegt ist.  
- Behebung eines Problems, bei dem das falsche Jahr angezeigt wird, wenn ein japanischer Kalender im Datumszellenformat verwendet wird.
- Beim Importieren von Daten in das Excel-Datenmodell führen eingehende negative Nullwerte zu einem Fehler. Der Fehler wurde behoben, indem solche Werte als null importiert werden.
- Behebung eines Problems, bei dem bei einem Gruppierungsvorgang bzw. beim Aufheben der Gruppierung in einer Excel-PivotTable manchmal ein Absturz verursacht wird.
- Behebung eines Problems, aufgrund dessen Excel bei Diagrammaktionen abstürzen kann.
- Behebung eines Problems, bei dem das Power View-Add-In für einige Benutzer versehentlich deaktiviert wurde.
- Behebung eines Problems, bei dem die während der Dokumentwiederherstellung erstellten temporären Dateien für die automatische Wiederherstellung nie bereinigt wurden.
- Behebung eines Problems, bei dem beim Versuch, eine neue Verbindung mit einer Textdatei in einer geschützten Arbeitsmappe herzustellen, die Fehlermeldung „Die Arbeitsmappe ist geschützt und kann nicht geändert werden“ angezeigt wurde.
- Problem behoben, bei dem die Verwendung des Schnelldrucks für eine Excel-Arbeitsmappe, die einer Outlook-E-Mail angefügt war, nicht funktionierte.
- Problem behoben, bei dem Excel beim Klicken auf einen Link möglicherweise abstürzte.
- Problem behoben, bei dem Excel beim Verwenden der Cubefunktionen abstürzte.

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

### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Sicherheitsupdates
- Behebt ein Problem, aufgrunddessen bei Benutzern Probleme mit der Kalendersynchronisierung auftreten.
- Behebung eines Problems, aufgrund dessen Benutzern beim Öffnen des Dialogfelds „Regeln und Warnungen verwalten“ ein Fehler angezeigt wird.
- Behebung eines Problems, aufgrund dessen Benutzer bei Verwendung einer getakteten Verbindung keine Verbindung zu ihren Postfächern über DirectAccess herstellen konnten.
- Behebung eines Problems, aufgrund dessen freie Dokumente, die in öffentlichen Ordnern gespeichert sind, fälschlicherweise in der „Geschützten Ansicht“ geöffnet werden.
- Behebung eines Problems, aufgrund dessen Benutzern unerwartete Anlagen beim Weiterleiten von Elementen mit Inline-Anlagen angezeigt werden.
- Behebung eines Problems, aufgrund dessen OFT-Dateien nach dem Senden als Anlage nicht ordnungsgemäß gerendert werden.
- Behebung eines Problems, aufgrund dessen bei einigen Add-In-Benutzern Abstürze beim Hinzufügen einer Besprechung zu einem freigegebenen Kalender auftreten.
- Behebung eines Problems, aufgrund dessen bei Benutzern Abstürze beim Öffnen des Ordners „Unterhaltungsverlauf“ auftraten.
- Behebt ein Problem, bei dem die VBA-IDE beim Ändern der Systemsprache in Japanisch und bei der Eingabe von japanischen Zeichen in die VBA-IDE beim Laden in Outlook einfriert.
- Behebung eines Problems, aufgrund dessen das Wechseln zum Ordner „Postausgang“ oder „Gesendete Elemente“ den Absturz von Outlook verursacht.
- Behebung eines Problems, aufgrund dessen alle Teilnehmer Meeting-Aktualisierungen erhalten, wenn sich der Meeting-Text oder Anlagen ändern, statt optional eine Meeting-Aktualisierung an die Teilnehmer zu senden.
- Behebung eines Problems, aufgrund dessen Benutzer aufgrund einer Änderung in der Benutzer-Agent-Zeichenfolge keine Verbindung zu EWS- und REST-Endpunkten herstellen können.
- Problem behoben, bei dem nach Aktualisierung des Besprechungorts den Teilnehmern weiterhin der alte Ort angezeigt wurde, anstelle des neuen.
- Problem behoben, bei dem bei der Vorschau einer Anlage im Lesebereich ein Fehler angezeigt wurde.
- Problem behoben, bei dem Outlook beim Auflösen von Anzeigenamen in E-Mail-Adressen abstürzte, wenn der Benutzer eine E-Mail verfasste.
- Problem behoben, bei dem einige Benutzer die Funktionen nicht nutzen konnten, die von Ihrem Mandantenadministrator aktiviert wurden.

### <a name="onenote-non-security-updates"></a>OneNote: Nicht sicherheitsrelevante Sicherheitsupdates 

- Es wurde ein Stabilitätsproblem gelöst, das im Zusammenhang mit dem Synchronisieren und dem Navigieren zu einem gelöschten Abschnitt auftreten kann.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Featureupdates 
- **AutoSpeichern für Clouddateien ist nun standardmäßig aktiviert:** Diese Änderung bedeutet, dass Benutzer sich keine Sorgen darüber machen müssen, dass Änderungen in Dokumenten verloren gehen, die in OneDrive oder SharePoint Online gespeichert sind. Änderungen werden automatisch in der Cloud gespeichert, und Benutzer müssen nicht mehr explizit STRG + S drücken oder auf die Schaltfläche „Speichern“ klicken. Allerdings müssen die Benutzer diese Verhaltensänderung verstehen, damit sie keine versehentlichen Änderungen an Präsentationen vornehmen. Beachten Sie, dass Benutzer das automatische Speichern mithilfe der Umschalttaste „AutoSpeichern“ deaktivieren können. Es wird empfohlen, dass Sie Ihre Benutzer über diese bevorstehende Änderung informieren und sie dahingehend schulen, wie dieses neue Feature in Office 365 optimal genutzt werden kann.[Weitere Informationen zu AutoSpeichern](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Erfahren Sie, was IT-Administratoren über AutoSpeichern wissen sollten](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Verbesserte Bearbeitungsleiste für Zellen: ** Sie können nun STRG + A zum Auswählen von Text in einer Zelle oder in der Bearbeitungsleiste verwenden. Außerdem wurde die Unterstützung von Emojis und anderen komplexen Zeichen verbessert. [Weitere Informationen](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Freihandkonvertierung:** Konvertieren Sie Notizen und Zeichnungen in lesbaren Text und gestochen scharfe Formen, um eine ansprechende Präsentation zu erstellen. [Weitere Informationen](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)
- **Verbesserte SVG-Unterstützung:** Sie können SVGs einfügen, auf die Filter angewendet wurden. [Weitere Informationen](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Einfügen von Titeln für Ihre Folien mit einem Stift:** Verwenden Sie den Stift, um per Freihand einen Titel einzugeben, und sehen Sie zu, wie PowerPoint diesen in Text konvertiert. [Weitere Informationen](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Vermeiden unerwünschter Bearbeitungen:** Legen Sie fest, dass Ihre Arbeitsmappen schreibgeschützt geöffnet werden, um versehentliche Änderungen zu verhindern. Wechseln Sie zu „Datei“ > „Info“ > „Arbeitsmappe schützen“ > „Immer schreibgeschützt öffnen“.
- **Verbesserungen an der Barrierefreiheitsprüfung:** Die Barrierefreiheitsprüfung weist eine aktualisierte Unterstützung für internationale Standards und Empfehlungen auf, sodass Sie leichter auf Ihre Präsentationen zugreifen können. [Weitere Informationen](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
-  **Befragen Sie Ihr Publikum mit einem Quiz oder einer Umfrage:** Fügen Sie ein Quiz oder eine Umfrage einer Folie hinzu. Office sammelt und speichert die Antworten für Sie. [Weitere Informationen](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Nicht sicherheitsrelevante Sicherheitsupdates
- Das Problem möglicher Dateibeschädigungen beim Speichern von Dateien mit ActiveX-Inhalt wurde behoben.
- Behebung eines Problems, bei dem Tabellen mit dicken Rahmen nicht ordnungsgemäß gerendert wurden.
- Behebung eines Problems, bei ein möglicher Absturz beim Ändern der Shape.Visibile-Eigenschaft auftreten könnte.
- Behebung eines Problems, bei dem Änderungen an gemeinsam erstellten Dokumenten nicht zusammengeführt werden können.
- Behebung eines Problems, bei dem Dokumente mit ActiveX-Steuerelementen zu einem Fehler bei der gemeinsamen Erstellung führen würden.
- Behebung eines Problems, aufgrund dessen PowerPoint bei der Rechtschreibprüfung in Shapes abstürzt.
- Behebung eines Problems, aufgrund dessen PowerPoint beim Öffnen einer Datei aus SharePoint Online abstürzt.
- Behebung eines Problems, aufgrund dessen der Wiederherstellungsbereich bei Aktivierung von AutoSpeichern inkorrekt angezeigt wird.
- Behebung eines Problems, aufgrund dessen die Anmeldung nicht angezeigt wird, wodurch ein Benutzer nicht auf eine Datei zugreifen kann.
- Behebung eines Problems, bei dem das gemeinsame Arbeiten mehrerer Benutzer an einer Präsentation in einer falschen Duplikation der Folienmaster resultierte.
- Behebung eines Problems, bei dem das Öffnen einer in OneDrive gespeicherten Datei im Absturz von PowerPoint beim Beenden der geschützten Ansicht resultierte.

### <a name="project-feature-updates"></a>Project: Featureupdates 
- **Sprintverwaltung:** Schnelles Hinzufügen, Aktualisieren oder Löschen von agilen Sprints.
- **Taskboardfilterung:** Optimieren Sie Ihre Taskboards, indem Sie nach wichtigen Ressourcen oder Sammelvorgängen filtern.
- **Festlegen der abgeschlossenen Prozent über ein Taskboard:** Wählen Sie für jede Spalte die abgeschlossenen Prozent aus, und aktualisieren Sie den Abschluss der Aufgabe dann per Drag & Drop.
- **Sprintnavigation:** Wechseln Sie von einer Sprintansicht zur anderen, und verschieben Sie schnell Aufgaben zwischen Sprints.
- **Neue Möglichkeit zum Verwalten von Sprints:** Verwenden Sie einen agilen Ansatz zum Arbeiten mit Taskboards. In der Sprintverwaltung können Sie Sprints hinzufügen und entfernen, wenn sich Ihr Projekt weiterentwickelt.
- **Organisiert bleiben mit zuletzt verwendeten Speicherorten:** In Project wird eine fortlaufende Liste davon geführt, wo Sie andere Projekte gespeichert haben. Wenn Sie bereit sind, Ihr Projekt zu speichern, wählen Sie einfach einen der zuletzt verwendeten Speicherorte aus, und arbeiten Sie weiter.

### <a name="project-non-security-updates"></a>Project: Nicht sicherheitsrelevante Sicherheitsupdates

- Behebung eines Problems im Zusammenhang mit der Unterstützung einer neuen venezolanischen Währung in Project behoben.
- Behebung eines Problems, bei dem Project möglicherweise hängen bleibt, wenn ein Surface 4-Tablet verwendet wird, das an einen externen Monitor angeschlossen ist.
- Behebung eines Problems, bei dem Project beim Speichern des Projekts im XML-Format möglicherweise abstürzt.
- Behebung eines Problems, aufgrund dessen benutzerdefinierte Felder von Unternehmensressourcen nach der Bearbeitung eines Ressourcenkalenders möglicherweise gelöscht werden.
- Behebung eines Problems, aufgrund dessen bei Benutzern beim Suchen nach koreanischen Anzeigenamen Abstürze auftraten.
- Behebt ein Problem, bei dem verhindert wird, dass Sie ein Unterprojekt speichern, wenn Sie damit im Kontext eines Masterprojekts arbeiten.

### <a name="word-feature-updates"></a>Word: Featureupdates
- **AutoSpeichern für Clouddateien ist nun standardmäßig aktiviert:** Diese Änderung bedeutet, dass Benutzer sich keine Sorgen darüber machen müssen, dass Änderungen in Dokumenten verloren gehen, die in OneDrive oder SharePoint Online gespeichert sind. Änderungen werden automatisch in der Cloud gespeichert, und Benutzer müssen nicht mehr explizit STRG + S drücken oder auf die Schaltfläche „Speichern“ klicken. Allerdings müssen die Benutzer diese Verhaltensänderung verstehen, damit sie keine versehentlichen Änderungen an Präsentationen vornehmen. Beachten Sie, dass Benutzer das automatische Speichern mithilfe der Umschalttaste „AutoSpeichern“ deaktivieren können. Es wird empfohlen, dass Sie Ihre Benutzer über diese bevorstehende Änderung informieren und sie dahingehend schulen, wie dieses neue Feature in Office 365 optimal genutzt werden kann.[Weitere Informationen zu AutoSpeichern](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Erfahren Sie, was IT-Administratoren über AutoSpeichern wissen sollten](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Verbesserungen an der Barrierefreiheitsprüfung:** Die Barrierefreiheitsprüfung weist eine aktualisierte Unterstützung für internationale Standards und Empfehlungen auf, sodass Sie leichter auf Ihre Dokumente zugreifen können. [Weitere Informationen](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Verbesserte SVG-Unterstützung:** Sie können SVGs einfügen, auf die Filter angewendet wurden. [Weitere Informationen](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Verwandeln Sie ihr Dokument von statisch in erstaunlich:** Verwandeln Sie Ihr Dokument in eine interaktive, einfach freizugebende Webseite, die auf jedem Gerät großartig aussieht. [Weitere Informationen](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

### <a name="word-non-security-updates"></a>Word: Nicht sicherheitsrelevante Sicherheitsupdates
- Behebung eines Problems, durch das eine Meldung zu nicht ausreichend Speicher angezeigt wurde.
- Es wurde eine Reihe von Problemen behoben, die einige Benutzer am Öffnen von IRM-geschützten Dokumenten und E-Mails hinderten, die von Personen in anderen Organisationen für sie freigegeben wurden.
- Probleme mit der Leistung wurden behoben.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Nicht sicherheitsrelevante Sicherheitsupdates
- Behebung eines Problems im Zusammenhang mit der Unterstützung von TLS 1.2. (Hinweis: Dies ist dieselbe Lösung, die in Hinweisen vom 10. April erwähnt wurde; diese wird hier im Rahmen des September-Rollups erneut erwähnt.)
- Behebung eines Problems beim Hinzufügen von Benutzern, bei dem durch das Auswählen von „Skype-Anruf“ in einem Meeting ein Fehler verursacht wird.
- Entfernung einer Eingabeaufforderung, in welcher der Benutzer aufgefordert wurde, Skype-Koordinaten zu einer Besprechung hinzuzufügen, wenn ein Skype Room als Ort hinzugefügt wurde und die Besprechung bereits Besprechungskoordinaten für ein Team enthält.
- Behebung eines Problems, bei dem der Speicherort gefüllt wird, selbst wenn „UseLocationForE911Only“ auf „true“ festgelegt wird.
- Behebung eines Problems, bei dem Skype for Business hängt, wenn die Option „Anruf über Konferenzcenter“ zum Einladen von Benutzern aus der Liste verwendet wird.
- Behebung eines Problems, bei dem Outlook (ausgeführt auf einem Terminalserver) einfriert, während ein Skype for Business-Meeting erstellt wird.
- Ändern Sie den Standardwert „EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket“ auf „true“.

### <a name="visio-feature-updates"></a>Visio: Featureupdates
- **Synchronisierung von Diagrammen und Datenquellen:** Wenn Sie ein Datenschnellansichtsdiagramm in Visio bearbeiten, haben Sie die Möglichkeit, die verknüpften Excel-Quelldaten entsprechend dem neusten Diagramminhalt zu aktualisieren.
- **Auditvorlage für Datenschnellansicht:** Importieren Sie Inhalte aus Excel und erstellen Sie Auditdiagramme für finanzielle Transaktionen, Bestandsverwaltung und mehr.
- **Startdiagramme:** Das Organigramm, Brainstormingdiagramm und SDL-Vorlagen verfügen über neue Startdiagramme für einen leichteren Einstieg.
 - **Erstellen eines Word-Dokuments aus Visio-Shapes:** Fügen Sie einem Word-Dokument automatisch Diagramminhalte wie Shapes und Metadaten hinzu. Passen Sie dann das Dokument an, um Vorgangsanleitungen und Betriebshandbücher zu erstellen. [Weitere Informationen](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

 
### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Updates
- Behebung eines Problems, bei dem das Installieren eines Updates unter bestimmten Umständen sehr lange dauert.
- Behebung eines Problems, bei dem beim Öffnen einer Anwendung eine Meldung über das Starten im abgesicherten Modus angezeigt wurde und die Anwendung nicht geöffnet werden konnte.
- Probleme mit der Leistung wurden behoben.


## <a name="version-1803-january-8"></a>Version 1803: 8. Januar
*Version 1803 (Build 9126.2351)*

*Dies ist die halbjährliche Kanalversion, die seit Juli 2018 zur Verfügung steht. Sie wird weiterhin unterstützt und erhält Sicherheitsupdates bis September 2019. Es ist jetzt jedoch eine neue halbjährliche Kanalversion verfügbar, Version 1808, die neue Features, Sicherheitsupdates und nicht sicherheitsrelevante Updates umfasst.*

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Nicht sicherheitsrelevante Sicherheitsupdates
- Behebung eines Problems, um Featureparität der LinkedIn-Option zwischen Office-Anwendungen sicherzustellen.


> [!NOTE]
> Wenn Sie Hilfe bei einem Problem mit der Nutzung von Office benötigen, empfehlen wir, dass Sie Ihre Frage im [Microsoft Answers-Forum](https://answers.microsoft.com/) oder in der [Tech-Community](https://techcommunity.microsoft.com/) veröffentlichen, oder Sie können sich an den [Support](https://support.microsoft.com/contactus) wenden.
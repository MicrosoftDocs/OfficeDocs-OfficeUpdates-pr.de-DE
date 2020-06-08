---
title: Anmerkungen zur Version für Releases im halbjährlichen Kanal (gezielt) im Jahr 2018
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 12/13/2018
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt IT-Experten Anmerkungen zur Version für Releases im halbjährlichen Kanal (gezielt) für Office 365 ProPlus im Jahr 2018 zur Verfügung.
ms.openlocfilehash: 59a294ac6eeb5a462d5a080f57e74b4afeffe739
ms.sourcegitcommit: b1fcfac6d568a74e296ca2f874a8d33a8a81cc5e
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/02/2020
ms.locfileid: "44163597"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2018"></a>Anmerkungen zur Version für Releases im halbjährlichen Kanal (gezielt) im Jahr 2018

Diese Anmerkungen zur Version enthalten Informationen zu neuen Features, Sicherheitsupdates und nicht sicherheitsrelevanten Updates, die in Office 365 ProPlus-Updates im Rahmen des halbjährlichen Kanals (gezielt) im Jahr 2018 enthalten sind.
 
> [!NOTE]
> - Nachfolgend sind außerdem Informationen zu neuen Features, Sicherheitsupdates und nicht sicherheitsrelevanten Updates für Visio Pro für Office 365 und Project Online-Desktopclient aufgeführt.
> - Diese Informationen gelten auch für Office 365 Business, die Version von Office, die in einigen Office 365-Plänen wie Business Premium enthalten ist.

 
> [!NOTE]
> - Die Informationen zu Sicherheitsupdates für jeden Updatekanal von Office 365 ProPlus werden ab sofort separat unter [Sicherheitsrelevante Updates](microsoft365-apps-security-updates.md) aufgeführt.

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
- **Verbesserte Bearbeitungsleiste für Zellen: ** Sie können nun STRG + A zum Auswählen von Text in einer Zelle oder in der Bearbeitungsleiste verwenden. Außerdem wurde die Unterstützung von Emojis und anderen komplexen Zeichen verbessert. [Weitere Informationen](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
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
-   **Flash-, Silverlight- und Shockwave-Steuerelemente können in Office aus Sicherheitsgründen nicht aktiviert werden:** Aus Sicherheitsgründen wird in neuen Builds von Microsoft Office für Office 365 unter Windows die Aktivierung von Flash-, Silverlight- und Shockwave-Steuerelemente blockiert. Weitere Informationen finden Sie [hier](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729) und [hier](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US).

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
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/de-DE/security-guidance/advisory/CVE-2018-0907): Microsoft Office Excel – Featureumgehung
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
-   Behebung eines Problems, aufgrund dessen die Suche mit der Meldung „Keine Übereinstimmungen gefunden“ fehlschlägt, wenn der Suchbereich auf „Alle Postfächer“ festgelegt ist.
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

### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Sicherheitsupdates
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

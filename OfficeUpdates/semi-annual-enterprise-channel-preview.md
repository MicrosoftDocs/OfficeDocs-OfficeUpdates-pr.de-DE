---
title: Versionshinweise für Releases im halbjährlichen Unternehmenskanal (Vorschau) im Jahr 2021
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt IT-Experten Versionshinweise für Releases im halbjährlichen Kanal (gezielt) für Microsoft 365 Apps im Jahr 2021 zur Verfügung.
ms.openlocfilehash: ccadc781717d3ed177734fb53c4e4524b846118c
ms.sourcegitcommit: d70605f689ddab4ddef193d526426fafa8e301b3
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/16/2021
ms.locfileid: "53463732"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview"></a>Versionshinweise für Versionen des halbjährlichen Enterprise-Kanals (Vorschau)

Diese Versionshinweise enthalten Informationen zu neuen Features und nicht sicherheitsrelevanten Updates, die in halbjährlichen Enterprise-Kanalupdates (Vorschau) für Microsoft 365 Apps for Enterprise, Microsoft 365 Apps for Business sowie in den Abonnementversionen der Desktop-Apps für Project und Visio enthalten sind.


## <a name="version-2102-july-13"></a>Version 2102: 13. Juli
*Version 2102 (Build 13801.20808)*

Sicherheitsupdates sind [hier](microsoft365-apps-security-updates.md) aufgeführt


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, durch das die Option „Cloudeinstellungen“ nicht aktiviert wurde, wenn sie von einem Benutzer ausgewählt wurde.


### <a name="powerpoint"></a>PowerPoint

- Ein Problem wurde behoben, bei dem in einigen Fällen ein in eine PowerPoint-Präsentation eingebettetes Excel-Objekt nicht wie erwartet angezeigt wurde.


### <a name="office-suite"></a>Office-Suite

- Wir haben das Szenario für den Benutzerwechsel von Daten behoben, wenn der Benutzer zwischen Active Directory-Identitäten über das Steuerelement "Ich" in Office-Anwendungen wechselt.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2102-june-08"></a>Version 2102: 08. Juni
*Version 2102 (Build 13801.20738)*

Sicherheitsupdates sind [hier](microsoft365-apps-security-updates.md) aufgeführt


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, durch das zusätzliche Abstände in Pareto-Diagrammen angezeigt wurden und der verfügbare Platz zum Erstellen von Diagrammen verringert wurde.


- Es wurde ein Problem behoben, bei dem bei einigen Benutzern zusätzliche Einträge in der Excel-Add-In-Liste angezeigt wurden.


- Es wurde ein Problem behoben, das bei einigen Benutzern dazu führte, dass die Statusleiste keinen Bereitschaftsstatus anzeigte.


- Es wurde ein Problem behoben, indem die Fehlermeldung für Fälle verbessert wurde, bei denen Benutzer beim Aktualisieren von Power BI-Datentypen keinen Zugriff auf einige Datentypen hatten.


- Es wurde ein Problem behoben, indem die Anzahl der Eigenschaften, die im AutoVervollständigen-Dropdownmenü für Eigenschaften angezeigt werden können, auf 256 erhöht wurde.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, durch das Benutzer Verbindungsfehlermeldungen erhielten, wenn die internen und externen EWS-Endpunkte unterschiedlich waren und der Aufruf an den internen Endpunkt fehlschlug.


- Es wurde ein Problem behoben, durch das die Adresse des Absenders beim erneuten Senden einer E-Mail als LegacyExchangeDN angezeigt wurde.


- Es wurde ein Problem behoben, bei dem Endbenutzer und Administratoren die Cloudeinstellungen nicht aktivieren konnten.


- Es wurde ein Problem behoben, durch das ZeroConfigExchange auf hybriden, in Azure AD eingebundenen und mit einem externen Netzwerk verbundenen Computern nicht ordnungsgemäß funktionierte.


- Wir haben ein Problem behoben, durch das Benutzern benutzerdefinierter Domänen beim Einfügen eines Links in eine E-Mail-Nachricht eine Warnmeldung zu Berechtigungen angezeigt wurde.
</br>

- Es wurde ein Registrierungsschlüssel hinzugefügt, mit dem die neue Benutzeroberfläche der Raumsuche (dieselbe Benutzeroberfläche wie in Outlook für Web) deaktiviert und die Vorgängerversion der Raumsuche mit "Vorgeschlagene Zeiten" aktiviert wird.

    Registrierungsschlüssel:

    >HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar </br>
    >REG_DWORD “ShowLegacyRoomFinder”</br></br>
    >0 (Standard) – Outlook verwendet die neue von OWA unterstützte Benutzeroberfläche für die Raumsuche, wenn der Benutzer auf die Schaltfläche „Raumsuche“ klickt, um nach verfügbaren Räumen zu suchen  </br>
    >1 – Outlook verwendet die ältere Benutzeroberfläche der Raumsuche, um nach verfügbaren Räumen zu suchen </br>


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem der Speicher auf Version 1.0.0.2 aktualisiert wurde, um die zentrale Bereitstellung zu unterstützen. Der Benutzer muss die Versionsinformationen in PowerPoint aktualisieren, um auf den Speicher zugreifen zu können.


### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem, wenn Sie eine Formel für ein benutzerdefiniertes Feld erstellen, die die ProjectDate */ProjectDur*-Funktionen verwendet, und der zweite Parameter die Datums- und Zeitfunktionen „Date()“, „Now()“ oder „Time()“ sind, dann ein #FEHLER auftrat.


- Es wurde ein Problem behoben, bei dem der Ressourcenpool nicht mehr reagierte und nicht geöffnet werden konnte.


### <a name="visio"></a>Visio

- Es wurde ein Problem im Zusammenhang mit fehlenden Ergebnissen bei der Eingabe von Suchstichwörtern in die Shape-Suche behoben.


### <a name="word"></a>Word

- Ein Problem im Zusammenhang mit der nicht mehr reagierenden Anwendung beim Einfügen von Onlinebildern wurde behoben.


- Es wurde ein Problem behoben, bei dem kopierte und eingefügte Formatvorlagen im Text, in den sie eingefügt wurden, u. U. nicht identisch waren.


- Es wurde ein Problem behoben, das die Begrenzung der für Inhaltssteuerelemente zulässigen Größe von Zeichenfolgen aufhob.


- Es wurde ein Problem im Zusammenhang mit der Bearbeitung von OLE-Objekten behoben.


### <a name="office-suite"></a>Office-Suite

- Ein Problem beim Öffnen von Platzhalterdateien wurde behoben. Office reagierte beim Öffnen der per Synchronisierung gesicherten Datei langsam.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2102-may-11"></a>Version 2102: 11. Mai
*Version 2102 (Build 13801.20638)*

Sicherheitsupdates sind hier aufgelistet: [Versionshinweise für Microsoft Office Sicherheitsupdates](microsoft365-apps-security-updates.md)


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem einige Add-ins für die Automatisierung für Excel nicht geladen werden konnten.


- Es wurde ein Problem behoben, das dazu führte, dass die Datumsformatierung bei der Verwendung von Add-Ins in einigen Sprachen falsch angezeigt wurde.


- Es wurde ein Problem behoben, das das Einfügen als Formeln in ein geschütztes Blatt verhinderte.


### <a name="outlook"></a>Outlook

- Auf diese Weise können Endbenutzer Outlook so konfigurieren, dass jeder von ihnen erstellten Besprechung eine Onlinebesprechung hinzugefügt wird.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem mit verknüpften Bildern behoben.


### <a name="word"></a>Word

- Es wurde ein Problem in Wordmail behoben, bei dem ein Element nicht gesendet werden kann, wenn das 2084ste Zeichen in einem Link ein Escapezeichen ist.


### <a name="office-suite"></a>Office-Suite

- Es wurde ein Problem behoben, bei dem Office-Vorlagen auch bei einer per GPO platzierten Anforderung zum Deaktivieren aktiviert wurden.


- Ein Problem wurd ebehoben, durch das Word beim Drucken langer Dokumente unerwartet geschlossen wurde.



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2102-april-13"></a>Version 2102: 13. April
*Version 2102 (Build 13801.20506)*

Sicherheitsupdates sind hier aufgelistet: [Versionshinweise für Microsoft Office Sicherheitsupdates](microsoft365-apps-security-updates.md)


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Access

- Es wurde ein Problem behoben, bei dem in einigen Fällen das Ausführen einer SQL Server-Pass-Through-Abfrage zu einer Fehlermeldung führte, die auf einen "ungültigen Cursorstatus" hinwies.


### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, durch das bei deaktivierten Befehlen im Office-Menüband nur das Symbol, nicht aber der Text im Office-Design "Dunkelgrau" abgeblendet wurde.


- Es wurde ein Problem behoben, durch das die Datenüberprüfung u. U. unerwartet auf Zellen angewendet wurde, nachdem Zeilen zu einer Tabelle auf einem anderen Blatt hinzugefügt wurden.


- Ein Problem wurde behoben, durch das die Anzeigfunktion von DialogSheets in 32-Bit-Versionen von Excel nicht funktionierte.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, durch das Outlook im Leerlauf abstürzte.


- Wir haben ein Problem behoben, das dazu führte, dass bei der Funktion "Cloud-Einstellungen" die benutzerdefinierten Einstellungen durch die Standardeinstellung überschrieben wurden, nachdem die Benutzer Outlook auf einem neuen Gerät konfiguriert hatten.


- Wir haben ein Problem behoben, durch das Benutzern mehr Signaturen als erwartet angezeigt wurden.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, durch das bei deaktivierten Befehlen im Office-Menüband nur das Symbol, nicht aber der Text im Office-Design "Dunkelgrau" abgeblendet wurde.


### <a name="word"></a>Word

- Es wurde ein Problem behoben, durch das bei deaktivierten Befehlen im Office-Menüband nur das Symbol, nicht aber der Text im Office-Design "Dunkelgrau" abgeblendet wurde.


- Es wurde ein Problem beim Kopieren und Einfügen behoben.


- Wir haben ein Problem behoben, bei dem die Eingabe am Ende eines ausgeblendeten Absatzes dazu führen konnte, dass die Anwendung nicht mehr reagierte.


### <a name="office-suite"></a>Office-Suite

- Es wurde ein Problem behoben, durch das Benutzer beim Öffnen einer zuvor geöffneten Datei mit nicht gespeicherten Änderungen keine Datei speichern konnten, die Datei jedoch gelöscht wurde. Nach der Problembehebung erhalten Benutzer eine freundliche Nachricht, in der sie darüber informiert werden, dass die Datei gelöscht wurde. Dieser Benutzer kann wählen, ob Änderungen verworfen oder die Datei gespeichert werden sollen.


- Es wurde ein Fehler behoben, der auftrat, wenn eine SyncBacked-Datei offline geöffnet und dann in der App umbenannt wurde, bevor sie gespeichert wurde.


- Es wurde ein Problem behoben, bei dem das Diktat für GCC-Benutzer deaktiviert wurde.


- Es wurde ein Problem behoben, das in Outlook manchmal dazu führen konnte, dass Text transparent dargestellt wurde, und dadurch nicht lesbar war.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2102-march-09"></a>Version 2102: 09. März
*Version 2102 (Build 13801.20294)*

Sicherheitsupdates sind hier aufgelistet: [Versionshinweise für Microsoft Office Sicherheitsupdates](microsoft365-apps-security-updates.md)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Lasso und Radierer in der Freihand-Toolbox:** Wenn Sie die Zeichentools verwenden, sind Lasso und Radierer jetzt in der Freihand-Toolbox verfügbar.<br />Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)

- **Eine PDF-Verbindung herstellen:** Herstellen einer Verbindung zu, Importieren und Aktualisieren von Daten aus einer PDF-Datei. [Weitere Informationen](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- **Erstellen von Variablen zur Verwendung in Formeln:** Verbessern Sie Leistung, Lesbarkeit und Zusammensetzbarkeit mit der LET-Funktion. Mit dieser Funktion können Sie benannte Variablen in neuen oder bereits vorhandenen Formeln erstellen. [Weitere Informationen](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)

- **In angeheftete Ordner speichern:** Das Anheften Ihrer Ordner erleichtern das Speichern von Office-Dateien.  Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die Ordner haben möchten, die beim Speichern einer neuen Datei verfügbar sind. Wir freuen uns, Ihnen eine neue Funktion zur Verfügung stellen zu können: Anheften Ihrer Ordner im Dialogfeld "Speichern". Mit dieser neuen Funktion können Sie Ihre Word-, Excel- und PowerPoint-Dateien einfacher speichern. [Weitere Informationen](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

- **Abrufen von Organisationsdaten aus Power BI mithilfe von Datentypen:** Excel-Datentypen aus Power BI werden nun für Insider in Organisationen mit Office 365/Microsoft 365 und dem Power BI Pro-Serviceplan bereitgestellt. Benötigte Informationen abrufen und deren einfache Aktualisierung ist für viele tägliche Abläufe von entscheidender Bedeutung. Sie erhalten Zugriff auf Ihre Unternehmens-oder Organisationsinformationen aus Power BI als Datentyp in Excel. Dadurch wird die Möglichkeit, verknüpfte Informationen in Tabellen einzugben, erweitert.  [Weitere Informationen](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br />Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)

- **iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen. Keine Konvertierung erforderlich.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)

- **Erstellen von ansprechenden Visio-Diagrammen in Excel:** Erstellen Sie datengesteuerte Diagramme wie Fluss- oder Organigramme aus Daten in einem Arbeitsblatt. [Weitere Informationen](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


- **AMSI-Integration in Office für XLM-Makros:** AMSI ist eine offene Schnittstelle, die unter Windows 10 für Anwendungen verfügbar ist, um zur Laufzeit eine synchrone Überprüfung eines Speicherpuffers durch ein installiertes Antiviren- oder Sicherheitsprogramm anzufordern. Wenn böswillige Aktivitäten erkannt werden, wird der Benutzer von Excel benachrichtigt, und die Anwendungssitzung wird heruntergefahren, um weitere Schäden zu vermeiden. Dies kann einen Angriff aufhalten und sowohl das Gerät als auch den Benutzer schützen. Weitere Informationen finden Sie unter [Blogbeitrag](https://www.microsoft.com/security/blog/2021/03/03/xlm-amsi-new-runtime-defense-against-excel-4-0-macro-malware/).

- **Erstellen von PivotTables aus Datasets in Power BI in Excel:** Sie können mit wenigen Klicks PivotTables in Excel erstellen, die mit in Power BI gespeicherten Datensätzen verbunden sind.  Auf diese Weise können Sie sowohl PivotTables als auch Power BI optimal nutzen. Sie können Ihre Daten mit PivotTables aus Ihren sicheren Power BI-Datensätzen berechnen, zusammenfassen und analysieren. [Weitere Informationen](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a>Outlook

- **Schützen von Daten in einer Gruppe:** Die beim Erstellen einer Gruppe ausgewählte Vertraulichkeitsbezeichnung wird auf Gruppen-E-Mails, Dokumente und Teamwebsites angewendet.

- **Benachrichtigung Über Vorfall für IT-Administratoren:** Globale Administratoren von Microsoft 365-Mandanten und Administratoren von Office-Apps werden über Outlook und O365 Exchange-Vorfällen benachrichtigt, die sich auf Ihre Benutzer auswirken – mit einer neuen Benachrichtigung im rechten Seitenbereich in Outlook für Windows. [Weitere Informationen](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- **Erstellen von Umfragen in Outlook mit Quick Poll**: Einfaches Erstellen einer Umfrage, Sammeln von Stimmen und Anzeigen der Ergebnisse in einer E-Mail. [Weitere Informationen](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- **iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen. Keine Konvertierung erforderlich.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)

- **Neue Raumsuche:** Suchen Sie in unterschiedlichen Kategorien nach Konferenzräumen.

- **Suchen Sie nach etwas in natürlicher Sprache:** Verwenden Sie alltägliche Sätze wie "Tierarzttermin letzte Woche", um die Suchergebnisse zu filtern und einzuschränken.

- **Option zum schnellen Wiederöffnen von Elementen aus der vorherigen Outlook-Sitzung:** Wir haben eine Option zum schnellen Wiederöffnen von Elementen aus einer vorherigen Outlook-Sitzung hinzugefügt.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/en-us/blog/automatically-restore-windows-in-outlook)

### <a name="powerpoint"></a>PowerPoint

- **Lasso und Radierer in der Freihand-Toolbox:** Wenn Sie die Zeichentools verwenden, sind Lasso und Radierer jetzt in der Freihand-Toolbox verfügbar.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)

- **In angeheftete Ordner speichern:** Das Anheften Ihrer Ordner erleichtern das Speichern von Office-Dateien.  Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die Ordner haben möchten, die beim Speichern einer neuen Datei verfügbar sind. Wir freuen uns, Ihnen eine neue Funktion zur Verfügung stellen zu können: Anheften Ihrer Ordner im Dialogfeld "Speichern". Mit dieser neuen Funktion können Sie Ihre Word-, Excel- und PowerPoint-Dateien einfacher speichern. [Weitere Informationen](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

- **iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen. Keine Konvertierung erforderlich.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)

### <a name="visio"></a>Visio

- **Neue Azure-Schablonen und -Formen:** Wir haben viele weitere Schablonen hinzugefügt, die Ihnen beim Erstellen von aktuellen Azure-Diagrammen helfen. [Weitere Informationen](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a>Word

- **Lasso und Radierer in der Freihand-Toolbox:** Wenn Sie die Zeichentools verwenden, sind Lasso und Radierer jetzt in der Freihand-Toolbox verfügbar.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/04/10/meet-the-new-action-pen/)

- **In angeheftete Ordner speichern:** Das Anheften Ihrer Ordner erleichtern das Speichern von Office-Dateien.  Wir haben Feedback erhalten, dass die Benutzer mehr Kontrolle über die Ordner haben möchten, die beim Speichern einer neuen Datei verfügbar sind. Wir freuen uns, Ihnen eine neue Funktion zur Verfügung stellen zu können: Anheften Ihrer Ordner im Dialogfeld "Speichern". Mit dieser neuen Funktion können Sie Ihre Word-, Excel- und PowerPoint-Dateien einfacher speichern. [Weitere Informationen](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br />Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

- **iPhone-Fotos direkt in Office einfügen:** HEIC-Bilder von Ihrem Smartphone jetzt nahtlos in Office einfügen. Keine Konvertierung erforderlich.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)

### <a name="office-suite"></a>Office-Suite

- **Bereiche im Registerkartenformat:** Jetzt können Sie über die Registerkarten-Benutzeroberfläche auf der rechten Seite der App zwischen mehreren Bereichen wechseln. Die Benutzeroberfläche wird nur angezeigt, wenn Sie mehr als 2 Fenster geöffnet haben.<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/02/20/improved-pane-management/)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Zugriff

- Es wurde ein Problem behoben, das bei Verwendung von DAO aus nicht-Office-Anwendungen dazu führte, dass die Anwendung unerwartet geschlossen wurde.


- Ein Problem wurde behoben, bei dem Benutzern ein Dialogfeld mit der Fehlermeldung „Ungültiger Cursorstatus“ angezeigt wurde.


### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, durch das einige ältere Excel 4.0- und Excel 5.0-Makros sowie einige VBA-Aufrufe an "dialogsheets.show" beschädigt wurden.


- Es wurde ein Problem behoben, bei dem Excel unerwartet geschlossen werden konnte, wenn das Menü "Werte anzeigen als" für eine PivotTable verwendet wurde.


- Es wurde ein Problem behoben, das Benutzer am Exportieren von Excel-Arbeitsmappen nach PDF hinderte.


- Ein Problem wurde behoben, das dazu führte, dass Bilder bei Verwendung der Option „Verknüpftes Bild einfügen“ kleiner als erwartet waren.


- Es wurde ein Fehler behoben, bei dem einige PivotTable-Formatierungen die Arbeitsmappe beschädigten, wenn diese im XLS- oder XLT-Format gespeichert wurde.


- Es wurde ein Problem behoben, bei dem Excel u. U. Makros ohne Anfrage deaktiviert ließ, wenn eine Excel-Add-In-Datei geöffnet wurde, die Excel 4.0-Makros beinhaltete.


- Ein Problem wurde behoben, bei dem Excel fälschlicherweise eine Meldungsleiste anzeigt, dass eine neue Version der Datei verfügbar ist, und den Benutzer auffordert, seine Änderungen in einer Kopie der Arbeitsmappe zu speichern oder die Änderungen zu verwerfen.


- Es wurde ein Problem behoben, bei dem einigen Benutzern während der gemeinsamen Dokumenterstellung fälschlicherweise eine Statusleiste angezeigt wurde, die sie über eine neue Version einer Datei informierte.


- Ein Problem wurde behoben, bei dem Excel nicht gestartet werden konnte bzw. unerwartet geschlossen wurde, wenn bestimmte Einstellungen für den Schutz vor Windows-Sicherheit-Exploits (SimExec, CallerCheck) verwendet wurden.


- Ein Problem wurde behoben, bei dem Excel nach der Auswahl einer Datenreihen in einem Diagramm nicht mehr antwortete.


- Durch diese Änderung wird ein Problem behoben, bei dem Schriftarten in Formeln nicht ordnungsgemäß angezeigt wurden.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, durch das Benutzer ihren Delegierten keine Editor-Berechtigung erteilen konnten.


- Wir haben ein Problem behoben, das bei einigen Benutzern dazu führte, dass Outlook in bestimmten Suchszenarien unerwartet geschlossen wurde.


- Ein Problem wurde behoben, das bei Benutzern mit freigegebenen oder delegierten Postfächern mit großen Hierarchien in ihrem Profil zu Blockaden führte.


- Es wurde ein Problem behoben, das dazu führte, dass einige automatisch generierte E-Mails mit einem leeren Textkörper gesendet wurden, wenn die Betreffzeile leer war.


- Es wurde ein Problem behoben, durch das bewirkt wurde, dass einige Benutzer Outlook unerwartet starten, wenn Sie offline sind.


- Es wurde ein Problem behoben, durch das zeitweilig Fehler auftraten, wenn Delegaten freigegebene Ordner in einem anderen Postfach öffneten.


- Es wurde ein Problem behoben, durch das die Anwendung bei der Auswahl eines Suchergebnisses unerwartet beendet wurde.


- Es wurde ein Problem behoben, das bei einigen Kunden dazu führte, dass sich das System beim Laden ihrer Kalender aufhängte.


- Es wurde ein Problem behoben, aufgrund dessen die ursprünglichen Teilnehmer einiger Besprechungen eine Veranstaltungsabsage erhielten, wenn ein anderer Teilnehmer die Besprechung weiterleitete.


- Ein Problem wurde behoben, das dazu führte, dass Benutzern nach dem Erstellen einer neuen Gruppe doppelte Kalendergruppen angezeigt wurden.


- Ein Problem wurde behoben, das dazu führte, dass Benutzer der Verbesserungen des geteilten Kalenders die Farbe eines Kalenders nicht auf gelb oder braun setzen konnten.


- Wir haben ein Problem behoben, das dazu führte, dass neu hinzugefügte Kalender den Benutzern erst nach einem Neustart von Outlook im Navigationsbereich angezeigt wurden.


- Es wurde ein Problem behoben, das bewirkte, dass die Suche keine Ergebnisse zurückgab, wenn nicht-zwischengespeicherte freigegebene Kalender durchsucht wurden.


- Ein Problem wurde behoben, das bei einigen Benutzern dazu führte, dass die App beim Schließen von Nachrichtenfenstern heruntergefahren wurde.


- Ein Problem wurde behoben, durch das das Feld „An:“ in Aufgabenstatusberichten leer war.


- Es wurde ein Problem behoben, durch das das MailItem.BeforeAttachmentAdd-Ereignis unterbrochen wurde.


- Es wurde ein Problem behoben, das bei einigen Benutzern dazu führte, dass Outlook in bestimmten Suchszenarien unerwartet geschlossen wurde.


- Ein Problem wurde behoben, das dazu führte, dass die App manchmal unerwartet geschlossen wurde, wenn Benutzer Suchvorgänge in Outlook ausführten.


- Es wurde ein Problem behoben, das dazu führte, dass das System hängen blieb, wenn Benutzer die Einstellungen unter "Cloudeinstellungen" aktualisierten.


- Es wurde ein Problem behoben, bei dem eine bearbeitete Signatur nicht gespeichert werden konnte, nachdem der Benutzer hierzu aufgefordert wurde.


- Es wurde ein Problem behoben, aufgrund dessen einige Benutzer keine Signaturen im Signaturen-Dropdownfeld sehen konnten, obwohl mindestens eine Signatur konfiguriert war.


- Wir haben ein Problem behoben, durch das die Cloudeinstellungen nicht standardmäßig für Benutzer aktiviert waren.


- Es wurde ein Problem behoben, durch das Änderungen an einer Benutzersignatur nicht gespeichert wurden.


- Es wurde ein Problem behoben, bei dem Outlook eine zweite leere Signatur für Personen mit aktivierten Cloud-Einstellungen erstellt hat.


- Ein Problem wurde behoben, das die Anzeige der richtigen Standardsignatur in OWA beeinträchtigt hat.


- Ein Problem wurde behoben, das dazu führte, dass Benutzersignaturen mit Unicode-Inhalten beschädigt wurden.


- Ein Problem wurde behoben, das dazu führte, dass Benutzer der Inlineübersetzung kein Feedback abgeben konnten.


- Es wurde ein Problem behoben, durch das die Kopfzeilen chinesischer Nachrichten bei der Beantwortung oder Weiterleitung nicht lesbar waren.


- Es wurde ein Problem behoben, durch das chinesische Zeichen beim Speichern als OFT-Datei in Fragezeichen geändert wurden.


- Es wurde ein Registrierungsschlüssel hinzugefügt, mit dem Kunden die Einbeziehung der Dateizeit für Anhänge in IDataObject-Operationen (d. h. Drag & Drop, Zwischenablage) deaktivieren können.  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.  REG_DWORD IncludeFileTimesInDataObject.  0 = Filetimes sind ausgeschlossen.  1 = (Standard) Filetimes sind enthalten.


- Es wurde ein Problem behoben, das bewirkt, dass Inline Bilder beim Antworten auf eine Nachricht mit einer Schutz Bezeichnung von Azure Information Protection nicht mehr angezeigt werden.


- Ein Problem wurde behoben, das dazu geführt har, dass das Verschlüsselungssymbol bei E-Mails, die mit der Option „Nur mit Verschlüsselung“ gesendet wurden, nicht angezeigt wurde.


- Wir haben ein Problem behoben, bei dem E-Mails als digital signiert versendet wurde, obwohl der Benutzer die Option deaktiviert hatte.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, das dazu führen konnte, dass die Anwendung unerwartet geschlossen wurde, wenn das Speichern eines Dokuments fehlschlug.


- Ein Problem mit dem Kopieren/Einfügen einer Formel aus Word in PowerPoint wurde behoben.


- Diese Änderung behebt ein Problem mit Pfadfüllungen beim Anwenden von "Formen zusammenführen"-Vorgängen mit bestimmten Geometrien.


- Durch diese Änderung wird ein Problem behoben, bei dem Schriftarten in Formeln nicht ordnungsgemäß angezeigt wurden.


- Durch diese Änderung wird ein Problem beim Behandeln von Fehlern behoben, das während des Ladens von Videos auftreten konnte.


- Ein VBA-Problem wurde behoben, bei dem "Slide.Shapes.AddMediaObject2" bei veralteten Videoformaten unerwartet geschlossen wurde (MPG-1, MPEG-2).


- Es wurde ein Problem behoben, bei dem der Befehl "Schriftgrad", der in QAT hinzugefügt wurde, beim Aktualisieren automatisch zum nächsten definierten Schriftgrad vervollständigt wurde.


- Es wurde ein Problem behoben, bei dem beim Speichern der Datei nach dem Duplizieren einer Folie, die neu aufgezeichnetes Audio enthielt, ein Fehler auftrat.


- Es wurde ein Problem behoben, bei dem das Forms-Inhalts-Add-In nach dem Einfügen erst dann gerendert wurde, wenn Benutzer auf eine andere Folie klickten, um sie anzuzeigen.


- Es wurde ein Problem behoben, bei dem der IRM-Schutz beim Öffnen einer PowerPoint-Datei in der geschützten Anzeige deaktiviert wurde.


- Es wurde ein Problem behoben, das die gemeinsame Dokumenterstellung für Dateien mit großen Mengen eines bestimmten Datenobjekttyps (E2o) verlangsamt hat.


- Fix zur Behebung eines Problems bei der Verwendung von IRM/geschützten Dokumenten während eines Merge-Fehlers.


- Hierbei handelt es sich um einen Fix für ein Problem, bei dem beim Schließen des Dokuments die Aufforderung „Speichern“ in einer Schleife angezeigt wird, wenn es ein Add-In gibt, das auf das Ereignis PresentationBeforeClose hört und die Eigenschaft Presentation.Saved als Teil des Ereignishandlers prüft.


- Ein Problem wurde behoben, bei dem einige beschädigte PowerPoint-Dateien auch nach einem Dokumentreparaturvorgang nicht ordnungsgemäß geöffnet wurden.


- Es wurde ein Problem behoben, bei dem die Auswahl einer Designidee in bestimmten Fällen das Datenklassifizierungslabel der Präsentation entfernte.


### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem beim Speichern eines Projekts aus PWA in eine lokale MPP-Datei das ProjectBeforeTaskChangeEvent für Daten ausgelöst wurde, die vom Benutzer nicht tatsächlich geändert worden waren.


- Es wurde ein Problem behoben, bei dem NewVal im Ereignis ProjectBeforeTaskChange nicht den richtigen Wert hatte, wenn eine Verzögerung innerhalb einer Ansicht vom Typ "Aufgabenformular" geändert wurde.


- Ein Problem wurde behoben, bei dem Sie, wenn Sie einen Ereigniscode ausführen, die Änderungen über eine Aufgaben-Formularansicht durchführen und dann durch Klicken auf die Schaltfläche OK keine Änderungen vornehmen.


- Es wurde ein Problem behoben, bei dem Project beim Öffnen von Dateien manchmal abstürzt, wenn Ressourcenprofile auf eine bestimmte Weise angegeben waren.


- Es wurde ein Problem behoben, bei dem bestimmte Projekte geöffnet werden konnten, wenn ein Problem mit der Projektdatei in einem bestimmten Teil der Last vorlag.


- Ein Problem wurde behoben, bei dem keine Rahmen für Vorgänge in der Teamplaneransicht angezeigt wurden.


- Ein Problem wurde behoben, bei dem Drag & Drop für Aufgaben in der Teamplaneransicht nicht funktioniert hat.


- Ein Problem wurde behoben, bei dem die geplanten Kosten nicht korrekt hochgerechnet wurden, wenn eine Kostenressource einem Meilensteinvorgang zugewiesen wurde.


### <a name="visio"></a>Visio

- Ein Problem wurde behoben, bei dem Benutzer in Visio für Office 365 gerade Linien mithilfe von Konnektoren für benutzerdefinierte Visio-Schablonen und eingebaute Vorlagen erstellen können.


### <a name="word"></a>Word

- Es wurde ein Problem behoben, das dazu führen konnte, dass die Anwendung unerwartet geschlossen wurde, wenn das Speichern eines Dokuments fehlschlug.


- Ein Problem mit dem Kopieren/Einfügen einer Formel aus Word in PowerPoint wurde behoben.


- Durch diese Änderung wird ein Problem mit dem Cursor beim Bearbeiten eines Dokuments behoben.


- Behebt ein Problem mit Farben, die auf Symbole und SVG-Grafiken mit 3D-Effekten angewendet wurden.


- Wir haben ein Problem mit der Sprachausgabe behoben, bei dem ein Absatz u. U. übersprungen wurde.


- Wir haben ein Problem mit Rich-Text-Inhaltssteuerelementen behoben.


- Es wurde ein Problem mit dem Dialogfeld "Formatvorlagenkatalog" behoben.


- Es wurde ein Problem mit dem Auflösen von Konflikten bei der gemeinsamen Dokumenterstellung gelöst.


- Es wurde ein Problem behoben, bei dem Dokumentformate durch andere Formate aus der Vorlage ersetzt wurden.


- Ein Assert-Fehler wurde behoben, der von optimierten Gates betroffen war.


### <a name="office-suite"></a>Office-Suite

- Wir haben ein Problem behoben, das zu einem Fehlschlag beim Versuch führte, Dateien zu speichern, die von SyncBacked auf „Nur Server“ übergegangen sind.


- Ein Problem wurde behoben, bei dem der Versuch, eine SaveAs durchzuführen, in bestimmten Szenarien fehlschlug.


- Ein Problem wurde behoben, bei dem „SaveRequestManagerCam“ dazu führte, dass die Anwendung geschlossen wurde, anstatt einen Fehler zurückzugeben.


- Die Schließfolge der Datei wurde korrigiert, so dass alle voneinander abhängigen Komponenten ordnungsgemäß geschlossen werden.


- Es wurde ein Problem behoben, bei dem eine Datei als NICHT SyncBacked geöffnet wurde, wenn die URLs von Zwischenspeicher und OneDrive NICHT übereinstimmten.


- Ein Problem wird behoben, bei dem durch das Kopieren/Einfügen in Skype for Business-Nachrichten ein Dialogfeld mit der Meldung „Beim Einfügen Ihres Inhalts ist etwas schief gelaufen“ angezeigt wurde.


- Es wurde ein Problem behoben, bei dem beim Kopieren/Einfügen von Text aus einem Kommentar in Excel ein Fehler auftrat.


- Ein Problem, das bei Verwendung der Sprachausgabe in Text mit mathematischen Formeln zum Absturz führen konnte, wurde behoben.


- Wenn ein Benutzer ein Dokument/ eine Datei auf Tintenstrahldrucker aus Office druckt und die Druckertintenstand niedrig ist, wird die Nachricht „Wenig Toner“ oder „Kein Toner“ angezeigt, auch wenn Tintenstrahldrucker keine Toner haben. Die Nachricht wurde geändert, um „Wenig Toner/Tinte“ bzw. „Kein Toner/keine Tinte“ anzuzeigen.


- Es wurde ein Problem behoben, bei dem aufgrund fehlender Registrierungseinträge die Installation einer neueren Version von Office über bestimmte ältere Versionen zu einer eingeschränkten Funktionalität führen konnte (beispielsweise war die Verwendung der Power-Abfrage nicht möglich).


- Es wurde ein Problem behoben, bei dem die Verhinderung von Datenverlust des Microsoft 365-Endpunkts Office-Dokumente auf Datenträgern nicht klassifizieren konnte.


- Es wurde ein Problem behoben, bei dem im Dialogfeld „Bild komprimieren“ bestimmte Benutzereinstellungen nicht beibehalten wurden.


- Ein Problem im Zusammenhang mit Ereignisbenachrichtigungen für Mediencontroller wurde behoben.


- Ein Problem im Zusammenhang mit dem Timing des Media Player-Moduls wurde behoben.


- Binäre Größe optimiert.


- Anaheim WebView unterstützt noch keinen Windows Information Protection (WIP). Mit diesem Fix wird die Add-In-Plattform in Office wieder abwärtskompatibel mit WebView in einer Umgebung mit aktiviertem WIP. Dabei kann es sich entweder um Microsoft Edge Spartan WebView oder Trident WebView handeln, abhängig von der Computerumgebung des Kunden. Beide abwärtskompatiblem WebViews unterstützen WIP.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-february-09"></a>Version 2008: 9. Februar
*Version 2008 (Build 13127.21216)*

Sicherheitsupdates sind hier aufgelistet: [Versionshinweise für Microsoft Office Sicherheitsupdates](microsoft365-apps-security-updates.md)


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Ein Problem wurde behoben, durch das Excel beim Öffnen von UNC-Dateien mit ungültigen Dateiattributen (Erstellungszeit, Änderungszeit usw.) unerwartet geschlossen wurde.


- Es wurde ein Problem behoben, bei dem die Einstellungen für Dezimal- und Tausendertrennzeichen nicht übernommen wurden, wenn ein Diagramm aus Excel kopiert und in Word oder PowerPoint eingefügt wurde.


- Es wurde ein Problem behoben, bei dem die Leistung beim Ausführen eines Makros mit PivotTable-Bereichsformatierung bei jeder Ausführung des Makros schlechter wurde.


- Es wurde ein Problem behoben, bei dem Regeln für die bedingte Formatierung beim Kopieren oder Verschieben von Blättern in eine andere Arbeitsmappe verloren gingen.


- Es wurde ein Problem behoben, bei dem Benutzer keine Vertraulichkeitsbezeichnungen auf Excel-Dateien anwenden konnten, wenn der Startbildschirm beim Starten der App deaktiviert war.


- Es wurde ein Problem beim Öffnen von Cloud-Dateien aus dem Folder „OneDrive-Synchronisation“ behoben.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, das dazu führte, dass Outlook beim Hinzufügen oder Speichern von Anlagen sporadisch nicht mehr funktionierte.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem der Befehl "Schriftgrad", der in QAT hinzugefügt wurde, beim Aktualisieren automatisch zum nächsten definierten Schriftgrad vervollständigt wird.


- Es wurde ein Problem behoben, bei dem das Kopieren und Einfügen einer Folie mit der Option „Quellformatierung beibehalten“ manchmal unerwartet einen neuen Folienmaster kopiert hat


### <a name="word"></a>Word

- Es wurde ein Problem mit dem Nachverfolgen von Änderungen behoben, bei dem das Öffnen von Word-Dokumenten manchmal einen Fehlerdialogfeld angezeigte.


- Es wurde ein Problem beim Öffnen von Cloud-Dateien aus dem Folder „OneDrive-Synchronisation“ behoben.


### <a name="office-suite"></a>Office-Suite

- Es wurde ein Problem behoben, das das erfolgreiche Öffnen einer Datei in Office verhinderte.


- Es wurde ein Problem behoben, bei dem Dokumente mit skizzierten Umrissen, die über „Format übertragen“ auf Connectors angewendet wurden, beschädigt werden konnten.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2008-january-12"></a>Version 2008: 12. Januar
*Version 2008 (Build 13127.21064)*

Sicherheitsupdates sind hier aufgelistet: [Versionshinweise für Microsoft Office Sicherheitsupdates](microsoft365-apps-security-updates.md)


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Ein Problem wurde behoben, bei dem in schreibgeschützten Arbeitsmappen beim Öffnen PivotTable-Daten nicht mehr aktualisiert wurden.


- Diese Änderung bietet eine Korrektur für folgendes Problem: Der Excel-Befehl „Objekt einfügen“ zeigt beim Einfügen einer Datei aus dem lokalen Synchronisationsordner von OneDrive nicht das richtige Symbol an.


- Es wurde ein Problem behoben, bei dem einigen Kunden während der gemeinsamen Erstellung fälschlicherweise über eine neue Version der Datei informiert wurden.


- Ein Bearbeitungsproblem wurde behoben, bei dem bei Verwendung des IME im Überschreibmodus fehlerhaft zusätzliche Zeichen vorgeschoben wurden.


- Ein Problem bei der Verwendung von Echtzeitdaten in Verbindung mit Multithread-Neuberechnungsfunktionen wurde behoben.


- Ein Problem wurde behoben, bei dem Excel nicht gestartet werden konnte bzw. unerwartet geschlossen wurde, wenn bestimmte Einstellungen für den Schutz vor Windows-Sicherheit-Exploits (SimExec, CallerCheck) verwendet wurden.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, aufgrund dessen die Formatierung von SmartLinks beim Speichern in Entwürfen verloren ging.


- Es wurde ein Problem behoben, durch das ein Benutzer eine Möglichkeit zum Anpassen des Rechtfertigungstexts bietet, wenn eine Richtlinie überschrieben wird.


- Es wurde ein Problem behoben, durch das chinesische Zeichen beim Speichern als OFT-Datei in Fragezeichen geändert wurden.


### <a name="powerpoint"></a>PowerPoint

- Ein VBA-Problem wurde behoben, bei dem "Slide.Shapes.AddMediaObject2" bei veralteten Videoformaten unerwartet geschlossen wurde (MPG-1, MPEG-2).


- Ein Problem wurde behoben, bei dem einige beschädigte PowerPoint-Dateien auch nach einem Dokumentreparaturvorgang nicht ordnungsgemäß geöffnet wurden.


### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem Project beim Öffnen von Dateien manchmal abstürzte, wenn Ressourcenprofile auf eine bestimmte Weise angegeben wurden.


### <a name="skype"></a>Skype

- Ein Problem wurde behoben, bei dem das TLS-DSK-Zertifikat eines Benutzers nicht zum erwarteten Zeitpunkt, sondern nur dann verlängert wurde, wenn es nur noch weniger als 12 Stunden gültig war.


- Ein Problem wurde behoben, bei dem die Benutzeroberfläche von Skype for Business nach der Anmeldung leer angezeigt wird, wenn Office noch nicht lizenziert ist.


### <a name="office-suite"></a>Office-Suite

- Diese Änderung behebt ein Problem im Zusammenhang mit dem Öffnen von Dateien, die Legacydiagramme enthalten.


- Diese Änderung behebt ein Problem mit SVG-Fallbackproxy, das zu Zugriffsverletzungen führt.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

> [!NOTE]
> Wenn Sie Hilfe bei einem Problem mit der Nutzung von Office benötigen, empfehlen wir, dass Sie Ihre Frage im [Microsoft Answers-Forum](https://answers.microsoft.com/) oder in der [Tech-Community](https://techcommunity.microsoft.com/) veröffentlichen, oder Sie können sich an den [Support](https://support.microsoft.com/contactus) wenden.


[//]: # (ADMIN CENTER-METADATENINHALT NICHT ÄNDERN BEGINN)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20808|version-2102-july-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20738|version-2102-june-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20638|version-2102-may-11|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13801.20294|version-2102-march-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21216|version-2008-february-09|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20910|version-2008-december-08|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20760|version-2008-november-10|)
[//]: # (|Win32|FRDC|Insiders| |16.0.13127.20638|version-2008-october-13|)
[//]: # (ADMIN CENTER-METADATENINHALT NICHT ÄNDERN ENDE)

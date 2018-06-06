---
title: Versionshinweise für Versionen in 2015 Semikolons jährlichen Channel (gezielte)
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 12/8/2015
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: Bietet IT-Spezialisten mit Anmerkungen zu dieser Version Versionen Semikolons jährlichen Channel (gezielte) für Office 365 ProPlus in 2015
ms.openlocfilehash: 4b6eb5b96fddc57d8a1f64adfaeb10166d541c42
ms.sourcegitcommit: 5dabd0a6045b54940da7821e2349ec78b6b99d00
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/04/2018
ms.locfileid: "19556128"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2015"></a>Versionshinweise für Versionen in 2015 Semikolons jährlichen Channel (gezielte)

Diese Versionshinweise enthalten Informationen zu neuen Features, Sicherheitsupdates und nicht sicherheitsrelevante Updates, die in Semikolons jährlichen Channel (gezielte) Updates für Office 365 ProPlus in 2015 enthalten sind.
 
> [!NOTE]
> - Die folgenden enthält auch Informationen zu neuen Features, Sicherheitsupdates und nicht sicherheitsrelevante Updates für Visio Pro für Office 365 und Project Online Desktop Client.
> - Diese Informationen gilt auch für Office 365 Business, also die Version von Office, die mit einigen Office 365-Pläne, wie Business Premium kommt.
> - Semikolons jährlichen Channel (gezielte) hieß erste Version für Kanal vor September 2017 zurückgestellt.


## <a name="version-1509-december-8"></a>Version 1509: Dezember 8
*Version 1509 (Build 6001.1043)*

### <a name="onenote-non-security-updates"></a>OneNote: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, aufgrund dessen über den Windows-Desktopclient erstellte XPS-Dateien oder Ausdrucke in Nicht-Windows-Desktopclients als rotes „X“ angezeigt wurden, da diese Clients das systemeigene Rendern von XPS-Dateien nicht unterstützen.

### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problem, aufgrund dessen bei einer erstellten Textmarke mit mehreren Absätzen nach Empfangen der E-Mail beim Verwenden von „Gehe zu“ nur der erste Absatz der Textmarke ausgewählt wurde.

### <a name="skype-for-business-security-updates"></a>Skype for Business: Sicherheitsupdates
-   Microsoft-Sicherheitsbulletin [MS15-128](https://go.microsoft.com/fwlink/?LinkId=690559): Sicherheitsupdate für die Microsoft-Grafikkomponente zur Behebung der Remotecodeausführung (3104503)

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, aufgrund dessen beim Freigeben von App-Sitzungen ein Fehler auftrat, insbesondere beim stoßweisen Datenverkehr.
-   Behebung eines Problems, das zum Absturz von Skype for Business führte, wenn es die erste gestartete App nach der Installation von Office 2016 war.

### <a name="word-security-updates"></a>Word: Sicherheitsupdates
-   Microsoft-Sicherheitsbulletin [MS15-131](https://go.microsoft.com/fwlink/?LinkId=699410): Sicherheitsupdate für Microsoft Office zur Behebung der Remotecodeausführung (3116111)

### <a name="word-non-security-updates"></a>Word: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, aufgrund dessen ein geschützter Trennstrich bei Verwendung bestimmter Schriftarten als Rechteck angezeigt wurde.

### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Sicherheitsupdates
-   Änderung des standardmäßigen Transports für das Herunterladen von Updates im Hintergrund von Zwischengespeichert/BITS zu HTTP.
-   Behebung eines Problems, aufgrund dessen Lizenzierungsfehler während eines automatischen Upgrades dazu führten, dass eine Office-Installation nicht durchgeführt wurde.
-   Behebung eines Problems, aufgrund dessen die Aktualisierung auf Office 2016 auf einem Windows 7 OEM-Computer mit dem Office-Preinstallation Kit im Überwachungsmodus zum Fehler 0x80070005 bei der Aktivierung führte.



## <a name="version-1509-november-10"></a>Version 1509: November 10
*Version 1509 (Build 6001.1038)*

### <a name="access-security-updates"></a>Access: Sicherheitsupdates
-   Microsoft-Sicherheitsbulletin [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Sicherheitsupdate für Microsoft Office zur Behebung der Remotecodeausführung (3104540)

### <a name="excel-security-updates"></a>Excel: Sicherheitsupdates
-   Microsoft-Sicherheitsbulletin [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Sicherheitsupdate für Microsoft Office zur Behebung der Remotecodeausführung (3104540)

### <a name="excel-non-security-updates"></a>Excel: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eins Problems, aufgrund dessen die Aufzeichnung eines Makros für eine Abfrageerstellung zu einem Kompilierungsfehler führte.
-   Behebung eines Problems, aufgrund dessen nach dem Löschen einer Spalte im Abfrage-Editor nach der Aktualisierung der Abfrage eine leere Spalte am Tabellenende angezeigt wurde.
-   Behebung eines Problems, aufgrund dessen beim Auswählen der Registerkarte „Sparklines“ unter Schnellanalyse der Abfragetabelle ein unerwarteter Fehler auftrat.
-   Behebung eines Problems, aufgrund dessen nach einem Ausschneide- und Einfügevorgang in einer Abfragetabelle die Abfrage nicht über den Bereich „Arbeitsmappenabfragen“ aktualisiert werden konnte.
-   Behebung eines Problems, aufgrund dessen beim Aktualisieren einer Abfrage der Fokus auf das Arbeitsblatt der zugeordneten Abfragetabelle verschoben wurde.
-   Entfernung eines Verweises auf Power Query aus der Fehlermeldung zu den unterstützen OData-Versionen.
-   Behebung eines Problems, aufgrund dessen Power Query-Funktionen verfügbar waren, jedoch nicht funktionierten, wenn das Produkt nicht aktiviert wurde.
-   URL-Aktualisierung für Dotlesscss unter Datei \> Konto \> Über Excel.

### <a name="onenote-security-updates"></a>OneNote: Sicherheitsupdates
-   Microsoft-Sicherheitsbulletin [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Sicherheitsupdate für Microsoft Office zur Behebung der Remotecodeausführung (3104540)

### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, aufgrund dessen beim Einfügen von Text in Outlook nicht der vollständige Text angezeigt wurde, wenn der eingefügte Text die Fensterhöhe überschritten hat.

### <a name="powerpoint-security-updates"></a>PowerPoint: Sicherheitsupdates
-   Microsoft-Sicherheitsbulletin [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Sicherheitsupdate für Microsoft Office zur Behebung der Remotecodeausführung (3104540)

### <a name="project-security-updates"></a>Project: Sicherheitsupdates
-   Microsoft-Sicherheitsbulletin [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Sicherheitsupdate für Microsoft Office zur Behebung der Remotecodeausführung (3104540)

### <a name="publisher-security-updates"></a>Publisher: Sicherheitsupdates
-   Microsoft-Sicherheitsbulletin [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Sicherheitsupdate für Microsoft Office zur Behebung der Remotecodeausführung (3104540)

### <a name="skype-for-business-security-updates"></a>Skype for Business: Sicherheitsupdates
-   Microsoft-Sicherheitsbulletin [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Sicherheitsupdate für Microsoft Office zur Behebung der Remotecodeausführung (3104540)
-   Microsoft-Sicherheitsbulletin [MS15-123](https://technet.microsoft.com/library/security/ms15-123): Sicherheitsupdate für Skype for Business und Microsoft Lync zur Behebung der Offenlegung von Informationen (3105872)

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems mit Audio auf Geräten mit zwei Mikrofoneingängen
-   Behebung eines Problems, aufgrund dessen die Benutzer nach der Wiederaufnahme des Laptopbetriebs aus dem Energiesparmodus nicht einer Besprechung beitreten konnten, bevor der Skype-Client sich nicht wieder angemeldet hat.
-   Unterstützung für Kontextmeldungen zur Unterstützung des Funktionsbewusstseins durch Benutzer hinzugefügt
-   Textaktualisierung im Dialogfeld „An Besprechungsaudio teilnehmen“, damit Benutzern der richtige Speicherort in der Benutzeroberfläche angezeigt wird, für den Sie die Einstellungen ändern möchten.
-   Behebung eines Problems mit Benachrichtigungen, die beim Auftreten von Netzwerkproblemen beim Senden und Empfangen angezeigt werden.

### <a name="visio-security-updates"></a>Visio: Sicherheitsupdates
-   Microsoft-Sicherheitsbulletin [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Sicherheitsupdate für Microsoft Office zur Behebung der Remotecodeausführung (3104540)

### <a name="word-security-updates"></a>Word: Sicherheitsupdates
-   Microsoft-Sicherheitsbulletin [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Sicherheitsupdate für Microsoft Office zur Behebung der Remotecodeausführung (3104540)

### <a name="word-non-security-updates"></a>Word: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, aufgrund dessen die Fußnotennummerierung in Word nicht mit der in dem ausgedruckten Dokument übereinstimmte, wenn ein Dokument mit der Fußnoteneinstellung „Nummerierung auf jeder Seite neu beginnen“ im Hintergrund ausgedruckt wurde.
-   Behebung eines Problems, aufgrund dessen die gemeinsame Dokumenterstellung in Echtzeit nicht für in OneDrive gespeicherte Dateien funktionierte. Dabei wurde anderen Benutzern auch nicht angezeigt, dass ein Benutzer Dateien in Echtzeit bearbeitet, und es waren keine Anwesenheitsinformationen verfügbar.
-   Behebung eines Problems, aufgrund dessen Word bei gemeinsamer Dokumenterstellung in Echtzeit abstürzte, wenn diese ein über SharePoint oder OneDrive geöffnetes Dokument betraf.
-   Behebung eines Formatierungsfehlers, der zur falschen Anzeige von Tabellen führte, wenn diese in HTML-E-Mails in Outlook eingefügt wurden und die Fenstergröße angepasst wurde.

### <a name="office-suite-security-updates"></a>Office-Suite: Sicherheitsupdates
-   Microsoft-Sicherheitsbulletin [MS15-116](https://technet.microsoft.com/library/security/ms15-116): Sicherheitsupdate für Microsoft Office zur Behebung der Remotecodeausführung (3104540)

### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, aufgrund dessen der Benutzer beim Öffnen von Dateien über SharePoint Online wiederholt zur Anmeldung aufgefordert wurde.
-   Behebung eines Problems, aufgrund dessen angeheftete Verknüpfungen auf der Taskleiste nicht beim manuellen Upgrade für alle Benutzer entfernt wurden.
-   Funktion zum manuellen Upgrade mithilfe von Klick-und-Los hinzugefügt, um festzustellen, ob Outlook mit Exchange Server 2007 verbunden oder ob Business Contact Manager installiert ist, damit Benutzer über potenzielle Probleme bei der Durchführung des Upgrades gewarnt werden.
-   Dialogfelder hinzugefügt, um das Beenden von Prozessen während einer Installation oder eines Upgrades sichtbar zu machen, da diese Dialogfelder durch Benutzer über Open Apps oder andere Benutzeroberflächen ausgeblendet werden können.
-   Behebung eines Problems, aufgrund dessen die automatische Anmeldung bei einer Office-App durch den Benutzer nicht erfolgte, wenn dieser einen Computer verwendete, der mit einer Domäne und einer Clouddomäne verknüpft war.



## <a name="version-1509-october-21"></a>Version 1509: Oktober 21
*Version 1509 (Build 6001.1034)*

### <a name="onenote-non-security-updates"></a>OneNote: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, aufgrund dessen das zweifache Auswählen der gleichen Farbe für einen Rahmen zum Abstürzen von OneNote führte.

### <a name="outlook-non-security-updates"></a>Outlook: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, aufgrund dessen mit der Sprachausgabe nur der erste Absatz einer mehrere Absätze umfassenden E-Mail-Signatur beim Bearbeiten der E-Mail-Signatur wiedergegeben wurde.
-   Behebung eines Problems, aufgrund dessen der Cursor sich nicht an der richtigen Stelle beim Schreiben oder Beantworten einer E-Mail befand.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, aufgrund dessen beim Anzeigen eines freigegebenen Desktops oder einer App bei wenig Speicherplatz die Verbindung getrennt wurde und eine erneute Verbindung und das Anzeigen des freigegebenen Desktops oder der App automatisch wiederholt wurde.
-   Behebung eines Problems, aufgrund dessen bei zunehmenden Teilnehmern die Darstellung des freigegebenen Desktops schlechter wurde.
-   Behebung eines Problems mit der mehrstufigen Authentifizierung, aufgrund dessen wiederholte Aufforderungen zur Telefonauthentifizierung den ganzen Tag lang gesendet wurden.

### <a name="visio-non-security-updates"></a>Visio: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, aufgrund dessen ein eingefügtes Word-Objekt, das als Symbol angezeigt werden sollte, nach Schließen und erneutem Öffnen von Visio leer war.

### <a name="word-non-security-updates"></a>Word: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, aufgrund dessen eine gemeinsame Dokumenterstellung nicht verfügbar war und das Dokument gesperrt werden konnte, wenn es in SharePoint Server 2013 vorhanden war.
-   Behebung eines Problems in DOCX-Dokumenten, aufgrund dessen eine Tabelle angezeigt wurde, obwohl für den Tabelleninhalt eine Formatvorlage mit der Option „Ausgeblendet“ angewendet war.
-   Behebung eines Problems, aufgrund dessen Dokumente mit relativen Links nach Durchführung einer Autokorrektur nicht gespeichert werden konnten.
-   Behebung eines Problems, aufgrund dessen sich die Zeilen während der Bearbeitung eines Absatzes in einem Dokument mit gegenüberliegenden Einzügen verschoben haben.
-   Behebung eines Problems, aufgrund dessen die Zeilenanzeige während der Bearbeitung bei deaktivierter Subpixelpositionierung inkonsistent war.
-   Behebung eines Problems, aufgrund dessen das Klicken auf ein Kommentar-Popup mit mehreren Kommentaren, bei dem der erste den Status „Erledigt“ aufweist, zu einem Absturz führte.
-   Behebung eines Problems mit fehlerhaftem Zeilenumbruch.
-   Behebung eines Problems, aufgrund dessen das Ausführen eines Makros, das die TransformDocument-Funktion in einem Dokument mit einem Textfeld in der Kopfzeile oder Fußzeile verwendet, zu einem Absturz führt.
-   Behebung eines Problems mit DOCM-Dokumenten, aufgrund dessen beim Entfernen aller ActiveX-Steuerelemente Fehler auftraten, wenn das Dokument geöffnet wurde.
-   Behebung eines Problems, aufgrund dessen das ContentControlOnExit-Ereignis beim Klicken in die Kopfzeile nicht ausgelöst wurde.
-   Behebung eines Problems, aufgrund dessen bei aktivierter Option „Änderungen nachverfolgen“ die Löschvorgänge für Bearbeiter mit demselben Namen angezeigt wurden.
-   Behebung eines Problems mit der gemeinsamen Dokumenterstellung in Echtzeit mit dem konfigurierten Entfernen von persönlichen Informationen, aufgrund dessen die Änderungen bei jedem Speichern des Dokuments als nachverfolgte Änderungen angezeigt wurden.

### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems, aufgrund dessen eine Office-App nach Aktualisierung auf 2016 das erste Mal mit eingeschränkter Funktionalität geöffnet wurde und die App neugestartet werden musste, um die vollständige Funktionalität zu erhalten.
-   Behebung eines Problems, aufgrund dessen das Ausführen von Office mit Aktivierung gemeinsam genutzter Computer auf einem Computer mit installierten Remotedesktopdiensten beim Öffnen einer App zu einer Fehlermeldung führte, in der mitgeteilt wurde, dass der Benutzer eine Volumenlizenzversion verwenden muss.
-   Behebung eines Problems, aufgrund dessen die Installation bei einem Status von rund 90 % hing.
-   Behebung eines Problems, aufgrund dessen Produktnamen falsch lokalisiert waren.
-   Behebung eines Problems, aufgrund dessen die QuickInfo und Zugriffstasteninfo für „Weitere Informationen“ nicht übereinstimmten und in Konflikt mit anderen Zugriffstasteninfos im Menüband in unterschiedlichen lokalisierten Versionen standen.
-   Behebung eines Problems,aufgrund dessen Outlook nach Aktualisierung von Office 2013 auf Office 2016 von Windows als neue App angezeigt wurde.
-   Behebung eines Problems, aufgrund dessen die Aktualisierung von Office 2013 Version 15.0.4615.1002 auf Office 2016 (Mai 2014) zum Fehler 0x80041015 führte.



## <a name="version-1509-october-5"></a>Version 1509: Oktober 5
*Version 1509 (Build 4229.1029)*

### <a name="onenote-non-security-updates"></a>OneNote: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems mit Office 365 Business, aufgrund dessen, beim Versuch OneNote mit SharePoint zu verwenden, eine Fehlermeldung angezeigt wurde, in der Benutzern mitgeteilt wird, dass Sie ein Upgrade auf eine andere Office-Version durchführen müssen.
-   Behebung eines Problems mit Surface Pro 3, aufgrund dessen die Vorschau der Videoaufzeichnung nicht angezeigt hatte, was aufgenommen wurde.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Nicht sicherheitsrelevante Sicherheitsupdates
-   Änderung dessen, was im Viewer angezeigt wird, wenn der freigebende Benutzer den Bildschirm in RDP sperrt. Im Viewer wird nun anstelle der RDP-Pausenabbildung eine Benachrichtigung angezeigt.

### <a name="office-suite-non-security-updates"></a>Office-Suite: Nicht sicherheitsrelevante Sicherheitsupdates
-   Behebung eines Problems mit Klick-und-Los, aufgrund dessen der Klick-und-Los-Dienst nicht in Office 2013 wiederhergestellt wurde, wenn die automatische Aktualisierung auf Office 2016 aufgrund eines Fehlers oder Abbruchs durch den Benutzer nicht abgeschlossen wurde.
-   Behebung von Problemen mit Klick-und-Los, aufgrund derer während der automatischen Aktualisierung auf Office 2016 ein Fehler auftrat, der dazu führt, dass die Aktualisierung nicht durchgeführt werden konnte und die Office 2013-Apps nicht verwendet bzw. nicht deinstalliert werden konnten.
-   Behebung eines Problems mit Klick-und-Los, aufgrund dessen bei einem erneuten automatischen Aktualisierungsversuch auf Office 2016 nach einem Neustart während eines vorherigen Aktualisierungsversuchs ein Updatefehler auftrat und die Anwendung nicht beendet werden konnte.
-   Behebung eines Problems mit Klick-und-Los, aufgrund dessen die Streamingaufgabe beim Installieren nicht wiederhergestellt werden konnte, nachdem der Computer neu gestartet wurde.
-   Behebung eines Problems mit Klick-und-Los, aufgrund dessen beim Neustart während einer manuellen Aktualisierung auf Office 2016 Aufgaben weiterhin den Status „Wird ausgeführt“ aufweisen.
-   Behebung eines Problems mit Klick-und-Los, aufgrund dessen beim Starten einer neu installierten App während des Installationsvorgangs dazu führte, dass ein Dialogfeld mit der Meldung „Keine Internetverbindung“ angezeigt wurde.
-   Behebung eines Problems mit Klick-und-Los, aufgrund dessen die während der Installation angezeigten App-Kacheln nicht aktiv waren, und die App nicht gestartet wurde, wenn Benutzer auf die App-Kachel geklickt hatten.
-   Behebung eines Problems mit Klick-und-Los, aufgrund dessen bei der automatischen Aktualisierung einer sr-latn-cr-Installation auf Office 2016 die Clientsprache nicht in sr-latn-rs konvertiert wurde.
-   Behebung eines Problems mit Klick-und-Los, aufgrund dessen bei der automatischen Aktualisierung während der Aktualisierungsvorbereitung ein Fehler auftrat, wenn mehrere SKUs von Office auf dem Computer installiert waren.
-   Behebung eines Problems mit Klick-und-Los, aufgrund dessen Fehlermeldungen angezeigt wurden, wenn ein manuelles Update gestartet wurde, während die automatische Aktualisierung noch ausgeführt wurde.
-   Aktualisierung der Verweise auf „Add-Ins“ in der Benutzeroberfläche des Produkts an Stellen, an denen die Großschreibung des Begriffs falsch war.



## <a name="version-1509-september-22"></a>Version 1509: September 22
*Version 1509 (Build 4229.1024)*

Dies ist die erste Version für diesen Kanal. In dieser Version sind zum ersten Mal die Office 2016-Anwendungen verfügbar.

### <a name="excel-security-updates"></a>Excel: Sicherheitsupdates
-   Microsoft-Sicherheitsbulletin [MS15-099](https://technet.microsoft.com/library/security/ms15-099): Sicherheitsrisiko in Microsoft Office Cloud kann Remotecodeausführung ermöglichen (3089664)
-   Microsoft-Sicherheitsbulletin [MS15-110](https://technet.microsoft.com/library/security/ms15-110): Sicherheitsupdates für Microsoft Office zur Behebung der Remotecodeausführung (3096440)

### <a name="visio-security-updates"></a>Visio: Sicherheitsupdates
-   Microsoft-Sicherheitsbulletin [MS15-081](https://technet.microsoft.com/library/security/ms15-081): Sicherheitsrisiko in Microsoft Office Cloud kann Remotecodeausführung ermöglichen (3080790)

### <a name="word-security-updates"></a>Word: Sicherheitsupdates
-   Microsoft-Sicherheitsbulletin [MS15-081](https://technet.microsoft.com/library/security/ms15-081): Sicherheitsrisiko in Microsoft Office Cloud kann Remotecodeausführung ermöglichen (3080790)

### <a name="office-suite-security-updates"></a>Office-Suite: Sicherheitsupdates
-   Microsoft-Sicherheitsbulletin [MS15-081](https://technet.microsoft.com/library/security/ms15-081): Sicherheitsrisiko in Microsoft Office Cloud kann Remotecodeausführung ermöglichen (3080790)
-   Microsoft-Sicherheitsbulletin [MS15-099](https://technet.microsoft.com/library/security/ms15-099): Sicherheitsrisiko in Microsoft Office Cloud kann Remotecodeausführung ermöglichen (3089664)

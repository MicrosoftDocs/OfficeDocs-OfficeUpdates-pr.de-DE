---
title: Versionshinweise für Releases im monatlichen Enterprise-Kanal
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt IT-Experten Versionshinweise für Releases im monatlichen Enterprise-Kanal für Microsoft 365 Apps zur Verfügung.
ms.openlocfilehash: 96a76ed1ed1849753422dae92626484a77cec2a4
ms.sourcegitcommit: 4f5536e809f58462d81c708c153390ebfd1abc4e
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/13/2021
ms.locfileid: "53409561"
---
# <a name="release-notes-for-monthly-enterprise-channel"></a>Versionshinweise für den monatlichen Enterprise-Kanal

Diese Versionshinweise enthalten Informationen zu neuen Funktionen und nicht sicherheitsrelevanten Updates, die in monatlichen Enterprise-Kanal-Updates für Microsoft 365 Apps for Enterprise, Microsoft 365 Apps for Business sowie in den Abonnementversionen der Desktop-Apps für Project und Visio enthalten sind.


[//]: # (NICHT ENTFERNEN)



## <a name="version-2105-july-13"></a>Version 2105: 13. Juli
*Version 2105 (Build 14026.20334)*

Sicherheitsupdates sind [hier](microsoft365-apps-security-updates.md) aufgeführt


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="outlook"></a>Outlook

- **Erhalten Sie relevante Dateivorschläge, wenn Sie eine Suche durchfuhren:** Wenn Sie im Suchfeld eingeben, werden die relevantesten Dateien, die sich auf Ihre Suche beziehen, in Ihre Vorschläge aufgenommen.


[//]: # (FEATUREDETAILS INHALTSENDE NICHT ENTFERNEN)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde eine Problem behoben, damit der Namens-Manager bei Büchern mit einer großen Anzahl von ausgeblendeten Namen geöffnet werden kann.


- Es wurde ein Problem behoben, bei dem bei einigen Benutzern zusätzliche Einträge in der Excel-Add-In-Liste angezeigt wurden.


- Es wurde ein Problem behoben, bei dem das Add-In „Analyse-Funktionen“ für einige Benutzer nicht funktionierte.


### <a name="outlook"></a>Outlook

- Die Änderung kann bei Problemen schnell deaktiviert werden.


- Es wurde ein Registrierungsschlüssel hinzugefügt, mit dem die neue Benutzeroberfläche der Raumsuche (dieselbe Benutzeroberfläche wie in Outlook für Web) deaktiviert und die Vorgängerversion der Raumsuche mit "Vorgeschlagene Zeiten" aktiviert wird.

   Registrierungsschlüssel:

    >HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar REG_DWORD “ShowLegacyRoomFinder”

    >0 (Standard) – Outlook verwendet die neue von OWA unterstützte Benutzeroberfläche für die Raumsuche, wenn der Benutzer auf die Schaltfläche „Raumsuche“ klickt, um nach verfügbaren Räumen zu suchen</br>
    >1 – Outlook verwendet die ältere Benutzeroberfläche der Raumsuche, um nach verfügbaren Räumen zu suchen


- Durch diese Änderung können Benutzer Feedback über unser neues Feedbacksystem übermitteln.


- Wir haben ein Problem behoben, durch das die Feedbackoption für Benutzer der Office Dauerlizenz 2021-Vorschau deaktiviert wurde.


- Ein Problem wurde behoben, das dazu führte, dass Benutzer einen Fehler erhielten, wenn sie „Outlook-Eigenschaften öffnen“ über ein Kontextmenü für einen Empfänger in einer E-Mail auswählten.


- Es wurde ein Problem behoben, das dazu führte, dass Outlook bei einigen Benutzern beim Laden von Personenkarten unerwartet geschlossen wurde.


- Ein Problem wurde behoben, das dazu führte, dass Outlook unerwartet geschlossen wurde, wenn Benutzer Ordner aus einem Archivspeicher entfernten.


- Es wurde ein Problem behoben, durch das einige Anweisungen für das Feature „Besprechungen kürzen“ aufgrund von Sprachausgabetechnologien deaktiviert waren.


- Es wurde ein Problem behoben, das dazu führte, dass Benutzern beim Schließen einer Nachricht, auf die sie geantwortet oder die sie weitergeleitet hatten, eine unerwartete Aufforderung zum Ändern der Eigenschaft angezeigt wurde.


- Ein Problem wurde behoben, das zu einem unerwarteten Schließen bei der Interaktion mit der Outlook Mail- oder Kalenderansichten führen kann.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem die Option „Folien wiederverwenden“ für wenige Benutzer nicht verfügbar war.


### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem Zuordnungen zu manuell geplanten Vorgängen möglicherweise auf ein falsches Datum verschoben wurden.


- Ein Problem wurde behoben, bei dem, wenn Sie eine Formel für ein benutzerdefiniertes Feld erstellen, die die ProjectDate */ProjectDur*-Funktionen verwendet, und der zweite Parameter die Datums- und Zeitfunktionen „Date()“, „Now()“ oder „Time()“ sind, dann ein #FEHLER auftrat.


### <a name="word"></a>Word

- Behebt ein Problem, bei dem der Editorbereich nicht geöffnet wird.


- Es wurde eine Problem behoben, bei dem in kontextbezogenen Karten für Rechtschreibung und Grammatik im Zusammenarbeitsbereich Schaltflächen-Symbole angezeigt wurden, diese Schaltflächen aber keine QuickInfo aufwiesen.


### <a name="office-suite"></a>Office-Suite

- Ein Lokalisierungsproblem wurde behoben, bei dem en-gb, fr-ca und es-mx nun mit ihren jeweiligen übergeordneten Versionen abgeglichen werden.


- Ein unerwartetes Schließen beim erneuten Öffnen bestimmter Dateien wurde behoben.


- Eine Leistungsregression beim Öffnen von SyncBacked-Dateien wurde behoben.


- Ein Problem wurde behoben, bei dem Benutzer bestimmte auf lokalen SharePoint-Servern gespeicherte Dokumente nicht bearbeiten können.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2104-july-13"></a>Version 2104: 13. Juli
*Version 2104 (Build 13929.20434)*

Sicherheitsupdates sind [hier](microsoft365-apps-security-updates.md) aufgeführt

## <a name="version-2104-june-08"></a>Version 2104: 08. Juni
*Version 2104 (Build 13929.20408)*

Sicherheitsupdates sind [hier](microsoft365-apps-security-updates.md) aufgeführt


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

- Es wurde ein Problem behoben, bei dem einige Dateien gelegentlich nicht in der geschützten Ansicht geöffnet werden konnten.


- Es wurde ein Problem behoben, das dazu führte, dass die Datumsformatierung bei der Verwendung von Add-Ins in einigen Sprachen nicht korrekt angezeigt wurde.


- Es wurde ein Problem behoben, bei dem das Add-In „Analyse-Funktionen“ für einige Benutzer nicht funktionierte.


- Es wurde ein Problem behoben, bei dem bei einigen Benutzern zusätzliche Einträge in der Excel-Add-In-Liste angezeigt wurden.


- Fix für ein Problem, bei dem ein Rollback der Hauptversion zum Beenden der Anwendung beim Öffnen von Dateien führen konnte.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem für einige Benutzer der Funktion zur Verbesserung der Kalenderfreigaben Probleme auftraten, wenn Sie im Navigationsbereich mit Ihrem Kalender interagierten.


- Es wurde ein Registrierungsschlüssel hinzugefügt, mit dem die neue Benutzeroberfläche der Raumsuche (dieselbe Benutzeroberfläche wie in Outlook für Web) deaktiviert und die Vorgängerversion der Raumsuche mit "Vorgeschlagene Zeiten" aktiviert wird.
    
    Registrierungsschlüssel:

    >HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Options\Calendar </br>
    >REG_DWORD “ShowLegacyRoomFinder”</br></br>
    > 0 (Standard) – Outlook verwendet die neue von OWA unterstützte Benutzeroberfläche für die Raumsuche, wenn der Benutzer auf die Schaltfläche „Raumsuche“ klickt, um nach verfügbaren Räumen zu suchen  </br>
    > 1 – Outlook verwendet die ältere Benutzeroberfläche der Raumsuche, um nach verfügbaren Räumen zu suchen </br>


- Wir haben ein Problem behoben, durch das die Namensauflösung fehlschlug, sobald etwas im Namen eines anderen Benutzers gesendet wurde und das mit einem Adressbuch verglichen wurde, das nicht der globalen Adressliste entsprach.


- Es wurde ein Problem behoben, durch das die Feedback-Option für Benutzer der Vorschauversion der Office Dauerlizenz 2021 nicht angezeigt wurde.


- Wir haben ein Problem behoben, durch das Benutzern möglicherweise die Meldung angezeigt wurde, dass der Fokus auf der Benutzeroberfläche verloren geht.


- Wir haben ein Problem behoben, durch das Outlook die in OWA konfigurierten Einstellungen für den Posteingang mit Relevanz außer Kraft gesetzt hat.


- Es wurde ein Problem behoben, das dazu führte, dass die Signaturen von Benutzern unerwartet verschwanden.


- Es wurde ein Problem behoben, das bei der Nutzung von Roaming-Einstellungen zu Nichtreagieren führte.


- Es wurde ein Problem behoben, das dazu führte, dass der Prozess bei der Suche unerwartet beendet wurde.


- Das Problem des unerwarteten Schließens bei einer Suche wurde behoben.


- Es wurde ein Problem behoben, durch das die Personenauswahl in Outlook bei Benutzern mit einer unbefristeten Lizenz nach oben anstatt nach unten erweitert wurde.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem die Option „Folien wiederverwenden“ für einige Benutzer nicht verfügbar war.


- Es wurde ein Problem im Zusammenhang mit verknüpften Bildern behoben.


- Es wurde ein Problem behoben, bei dem ein Rollback der Hauptversion zu einem unerwarteten Schließen beim Öffnen von Dateien führen konnte.


### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem Benutzer Projekte nicht aus dem Ressourcenpool entfernen konnten.


### <a name="word"></a>Word

- Es wurde ein Problem behoben, das eine Änderung beim Bearbeiten von OLE-Objekten erforderte.


- Es wurde ein Problem behoben, bei dem markierte Textabschnitte nicht sichtbar waren, wenn im Lesemodus das Design „Dunkler Modus“ verwendet wurde.


- Es wurde ein Problem behoben, das dazu führen konnte, dass Word beim Herunterfahren unerwartet geschlossen wurde, weil der Benutzer sich abmeldete oder seinen Computer neu startete.


- Es wurde ein Problem behoben mit der Aktualisierung des Texts im AutoSpeichern-Popup für lokal gespeicherte Dateien.


- Es wurde ein Problem behoben, bei dem ein Rollback der Hauptversion zu einem unerwarteten Schließen beim Öffnen von Dateien führen konnte.


### <a name="office-suite"></a>Office-Suite

- Es wurde ein Problem wurde behoben, durch das das Öffnen eines Cloud-Dokuments fehlschlug.


- Diese Änderung analysiert das neue Attribut "TenantId", das in Cobalt-Antworten gesendet wird, und speichert es in der zentralen Tabelle.



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2103-june-08"></a>Version 2103: 08. Juni
*Version 2103 (Build 13901.20554)*

Sicherheitsupdates sind [hier](microsoft365-apps-security-updates.md) aufgeführt


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem für einige Benutzer zusätzliche Einträge in der Excel-Add-In-Liste angezeigt wurden.


### <a name="office-suite"></a>Office-Suite

- Behebung eines Problems, das im Falle eines Rollbacks zu einem vorherigen Build bei Word, PowerPoint und Excel dazu führen konnte, dass das Öffnen eines Cloud-Dokuments fehlschlug.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2103-may-11"></a>Version 2103: 11. Mai
*Version 2103 (Build 13901.20516)*

Sicherheitsupdates sind [hier](microsoft365-apps-security-updates.md) aufgeführt


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Automatisch neue Datentypen verwenden:** Wenn Sie einen Datenwert eingeben, der einem möglichen Aktienelement oder geografischen Speicherort ähnelt, bietet Excel an, diesen in den geeigneten verbundenen Datentyp zu konvertieren – Aktien oder Geografie. [Weitere Informationen](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- **Verknüpfte Datentypen: Echte Daten für das echte Leben:** Neue verknüpfte Datentypen liefern Ihnen Fakten und Daten zu Hunderten von Themen, die Ihnen helfen, Ihre Ziele direkt in Excel zu erreichen.

### <a name="outlook"></a>Outlook

- **Aufheben der Sprachbarriere durch einen integrierten Übersetzer:** Ab jetzt sind keine Add-Ins für die Übersetzung mehr erforderlich! Sie können jetzt den Intelligenten Übersetzer in Outlook verwenden. Wenn Sie eine Nachricht in einer anderen Sprache erhalten, wird am oberen Rand der Nachricht eine Eingabeaufforderung angezeigt, die Ihnen anbietet, die Nachricht durch Outlook in Ihre Standardsprache zu übersetzen.
Sie können auch mit der rechten Maustaste klicken, um bestimmte Wörter, Ausdrücke oder die gesamte Nachricht zu übersetzen. [Weitere Informationen](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

### <a name="visio"></a>Visio

- **Fertige Grafiken für Ihre Diagramme:** Wählen Sie aus einer großen Bibliothek von Symbolen, Stockbildern, ausgeschnittenen Personen und Aufklebern, die Sie zu Ihren Visio-Zeichnungen hinzufügen können. [Weitere Informationen](https://support.office.com/article/0ab844a5-289b-47f2-ba92-eeda168bc381)<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://insider.office.com/de-DE/blog/access-illustrations-icons-in-visio)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Zugriff

- Ein Problem wurde behoben, das, wenn eine externe Anwendung eine Benutzeroberfläche zur Barrierefreiheit anfordert, uns daran hindert, herunterzufahren, bis sie ihre Referenz freigibt.


- Diese Änderung behebt ein Problem, bei dem in einigen Fällen das Ausführen einer SQL Server-Pass-Through-Abfrage zu einer Fehlermeldung führen kann, die darauf hinweist, dass ein "ungültiger Cursorstatus" vorliegt.


### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, das dazu führte, dass die Datumsformatierung bei der Verwendung von Add-Ins in einigen Sprachen nicht korrekt angezeigt wurde.


- Es wurde ein Problem behoben, bei dem das Add-In „Analyse-Funktionen“ für einige Benutzer nicht funktionierte.


- Es wurde ein potenzielles Hängen in Word beim Zeichnen eines Bilds behoben.


### <a name="outlook"></a>Outlook

- Wir haben ein Problem behoben, durch das die Namensauflösung fehlschlug, sobald etwas im Namen eines anderen Benutzers gesendet wurde und das mit einem Adressbuch verglichen wurde, das nicht der globalen Adressliste entsprach.


- Es wurde ein Problem behoben, durch das Outlook die in OWA konfigurierten Einstellungen für den Posteingang mit Relevanz außer Kraft gesetzt hat.


- Wir haben ein Problem behoben, das dazu führte, dass einige Personen nicht auf Signaturen zugreifen konnten, die mit sekundären E-Mail-Konten verbunden waren.


- Es wurde ein Problem behoben, durch das Benutzern mehr Signaturen als erwartet angezeigt wurden.


- Wir haben ein Problem behoben, durch das bei einigen Benutzern die Plätze des primären und sekundären Kalenders im Navigationsbereich vertauscht waren.


- Ein Problem wurde behoben, das dazu führte, dass Benutzern beim Hinzufügen eines Kalenders fälschlicherweise die Meldung „Dies kann eine Weile dauern“ angezeigt wurde.


- Ein Problem wurde behoben, das dazu führte, dass Stellvertretungen als Organisator von Besprechungen angezeigt wurden, die in neu hinzugefügten Kalendern erstellt wurden.  Besprechungen in diesem Zustand wurden im Kalender des Prinzipals nicht angezeigt.


- Wir haben ein Problem in einer Komponente von Outlook behoben, die von MAPI-fähigen Anwendungen auf Computern mit ARM-Prozessoren verwendet wird. Das Problem führte dazu, dass die Suche fehlschlug oder der Computer zusätzlich belastet wurde, da Hintergrund-Apps wiederholt neu gestartet wurden.


- Wir haben ein Problem behoben, durch das Outlook bei einigen Benutzern beim Synchronisieren von Änderungen der Ordnerhierarchie unerwartet geschlossen wurde.


- Es wurde ein potenzielles Hängen in Word beim Zeichnen eines Bilds behoben.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem mit verknüpften Bildern behoben.


- Es wurde ein potenzielles Hängen in Word beim Zeichnen eines Bilds behoben.


### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem Visio während des Schließens manchmal nicht mehr funktionierte.


### <a name="visio"></a>Visio

- Ein Problem wurde behoben, bei dem Visio während des Schließens manchmal nicht mehr funktionierte.


### <a name="word"></a>Word

- Es wurde ein Problem behoben, durch das Bedingungen für angebotene Textvorhersagen optimiert werden.


- Es wurde ein Problem mit der Aktualisierung des Texts im AutoSpeichern-Popup für lokal gespeicherte Dateien behoben.


- Es wurde ein Problem behoben, bei dem bei der gemeinsamen Dokumentenerstellung der aktive Entwurf nicht gelöscht wurde, wenn sich die Kommentarreihenfolge änderte.


- Behebt ein Problem, bei dem die Seitenansicht unerwartet geschlossen wurde.


- Es wurde ein potenzielles Hängen in Word beim Zeichnen eines Bilds behoben.



### <a name="office-suite"></a>Office-Suite

- Behebt ein Problem mit der Zuverlässigkeit im Zusammenhang mit der Unterstützung von Office-Apps, die in Sitzung 0 ausgeführt werden.


- Es wurde ein Fehler behoben, bei dem die Funktion „Umbenennen“ nicht reagierte, wenn eine SyncBacked-Datei offline geöffnet und dann in der App umbenannt wurde, bevor sie gespeichert wurde.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2102-may-11"></a>Version 2102: 11. Mai
*Version 2102 (Build 13801.20638)*

Sicherheitsupdates sind [hier](microsoft365-apps-security-updates.md) aufgeführt


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, das dazu führte, dass die Datumsformatierung bei der Verwendung von Add-Ins in einigen Sprachen nicht korrekt angezeigt wurde.


- Es wurde ein Problem behoben, das das Einfügen als Formeln in ein geschütztes Blatt verhinderte.


### <a name="outlook"></a>Outlook

- Auf diese Weise können Endbenutzer Outlook so konfigurieren, dass jeder von ihnen erstellten Besprechung eine Onlinebesprechung hinzugefügt wird.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem mit verknüpften Bildern behoben.


### <a name="word"></a>Word

- Behebt ein Problem in Wordmail, bei dem ein Benutzer dieses Element nicht senden kann, wenn das 2084. Zeichen in einem Link ein Escapezeichen ist.


### <a name="office-suite"></a>Office-Suite

- Ein Problem wurde behoben, durch das Word beim Drucken langer Dokumente unerwartet geschlossen wurde.


- Vor dieser Änderung wurden Office-Vorlagen auch dann angezeigt, wenn das Gruppenrichtlinienobjekt, das sie deaktiviert, aktiviert war. Mit dieser Änderung werden Vorlagen jetzt das Gruppenrichtlinienobjekt richtig verwenden und wie gewünscht angezeigt/ausgeblendet.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2102-april-13"></a>Version 2102: 13. April
*Version 2102 (Build 13801.20506)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Verwenden des Dialogfelds "Erweitert" zum Erstellen von Datentypen:** Im Dialogfeld "Erweitert" können Sie manuell die Spalten auswählen, die den von Ihnen erstellten Datentyp kombinieren.

- **Blenden Sie viele Blätter gleichzeitig ein:** Sie müssen nicht mehr ein Blatt nach dem anderen einblenden – Sie können mehrere ausgeblendete Blätter gleichzeitig einblenden. [Weitere Informationen](https://support.office.com/article/69f2701a-21f5-4186-87d7-341a8cf53344)


### <a name="outlook"></a>Outlook

- **Die Einstellungen für den Posteingang mit Relevanz bleiben auf allen Geräten identisch:** Ihre Einstellungen für den Posteingang mit Relevanz sind jetzt in der Cloud gespeichert. Nutzen Sie auf einem beliebigen Windows-Computer und in Outlook im Web dieselbe Oberfläche. [Weitere Informationen](https://support.office.com/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- **Ihre Outlook-Einstellungen in der Cloud:** Wählen Sie Ihre Outlook für Windows-Einstellungen aus, z. B. Automatische Antworten, Posteingang mit Relevanz und Datenschutz, und greifen Sie auf jedem beliebigen PC darauf zu.

- **Auswählen, wo gesucht werden soll:** Das neue Dropdownmenü für den Suchbereich ermöglicht es Ihnen, Ihre Suche einfacher zu ändern und zwischen dem aktuellen Ordner und dem aktuellen Postfach zu wechseln. Vielen Dank an alle in "Demnächst verfügbar", die uns ihr Feedback zu der neuen Search-at-Top-Erfahrung gesendet haben. Das vorliegende Design und Update sind aus diesem Feedback entstanden!

- **Verfassen Sie Nachrichten mit Ihrer Stimme:** Verwenden Sie die neue Diktatsymbolleiste, neue Sprachbefehle, automatische Zeichensetzung und mehr, um Nachrichten zu verfassen.

### <a name="word"></a>Word

- **Verfassen Sie Dokumente mit Ihrer Stimme:** Verwenden Sie die neue Diktatsymbolleiste, neue Sprachbefehle und automatische Zeichensetzung, um Dokumente zu verfassen.


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Access

- Es wurde ein Problem behoben, bei dem in einigen Fällen das Ausführen einer SQL Server-Pass-Through-Abfrage zu einer Fehlermeldung führte, die auf einen "ungültigen Cursorstatus" hinwies.



### <a name="excel"></a>Excel

- Es wurde ein Fehler behoben, durch den die Datenüberprüfung u. U. unerwartet auf Zellen angewendet wurde, nachdem Zeilen zu einer Tabelle auf einem anderen Blatt hinzugefügt wurden.


- Ein Problem wurde behoben, durch das die Anzeigfunktion von DialogSheets in 32-Bit-Versionen von Excel nicht funktionierte.


- Ein Problem wurde behoben, das dazu führte, dass Bilder bei Verwendung der Option „Verknüpftes Bild einfügen“ kleiner als erwartet waren.


- Es wurde ein Fehler behoben, bei dem einige PivotTable-Formatierungen die Arbeitsmappe beschädigten, wenn diese im XLS- oder XLT-Format gespeichert wurde.


- Es wurde ein Problem behoben, das Benutzer am Exportieren von Excel-Arbeitsmappen in eine PDF-Datei hinderte.


- Es wurde ein Problem behoben, durch das bei deaktivierten Befehlen im Office-Menüband nur das Symbol, nicht aber der Text im Office-Design "Dunkelgrau" abgeblendet wurde.


### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, das dazu führte, dass Benutzer der Inlineübersetzung kein Feedback abgeben konnten.


- Ein Problem wurde behoben, das dazu führte, dass Benutzersignaturen mit Unicode-Inhalten beschädigt wurden.


- Es wurde ein Problem behoben, durch das Benutzern mehr Signaturen als erwartet angezeigt wurden.


- Es wurde ein Problem behoben, durch das Outlook im Leerlauf abstürzte.


- Ein Problem wurde behoben, das dazu führte, dass die App bei einigen Benutzern beim Schließen von Nachrichtenfenstern heruntergefahren wurde.


- Ein Problem wurde behoben, das dazu führte, dass Benutzer der Verbesserungen des geteilten Kalenders die Farbe eines Kalenders nicht auf gelb oder braun setzen konnten.


- Ein Problem wurde behoben, das dazu führte, dass Benutzern nach dem Erstellen einer neuen Gruppe doppelte Kalendergruppen angezeigt wurden.


- Wir haben ein Problem behoben, das dazu führte, dass neu hinzugefügte Kalender den Benutzern erst nach einem Neustart von Outlook im Navigationsbereich angezeigt wurden.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, durch das bei deaktivierten Befehlen im Office-Menüband nur das Symbol, nicht aber der Text im Office-Design "Dunkelgrau" abgeblendet wurde.


### <a name="word"></a>Word

- Es wurde ein Problem mit dem Auflösen von Konflikten bei der gemeinsamen Dokumenterstellung gelöst.


- Wir haben ein Problem mit Rich-Text-Inhaltssteuerelementen behoben.


- Wir haben ein Problem behoben, bei dem die Eingabe am Ende eines ausgeblendeten Absatzes dazu führen konnte, dass die Anwendung nicht mehr reagierte.


- Wir haben ein Problem mit der Sprachausgabe behoben, bei dem ein Absatz u. U. übersprungen wurde.


- Es wurde ein Problem beim Kopieren und Einfügen behoben.


- Behebt ein Problem mit Farben, die auf Symbole und SVG-Grafiken mit 3D-Effekten angewendet wurden.


- Es wurde ein Problem behoben, durch das bei deaktivierten Befehlen im Office-Menüband nur das Symbol, nicht aber der Text im Office-Design "Dunkelgrau" abgeblendet wurde.


### <a name="office-suite"></a>Office-Suite

- Wir haben ein Zuverlässigkeitsproblem im Zusammenhang mit der Unterstützung von Office-Apps behoben, die in Sitzung 0 ausgeführt wurden.


- Es wurde ein Problem behoben, das in Outlook manchmal dazu führen konnte, dass Text transparent dargestellt wurde, und dadurch nicht lesbar war.


- Ein Problem, das bei Verwendung der Sprachausgabe in Text mit mathematischen Formeln auftrat, wurde behoben.


- Es wurde ein Problem behoben, bei dem das Diktat für GCC-Benutzer deaktiviert wurde.


- Es wurde ein Problem behoben, durch das Benutzer beim Öffnen einer zuvor geöffneten Datei mit nicht gespeicherten Änderungen keine Datei speichern konnten, die Datei jedoch gelöscht wurde. Nach der Problembehebung erhalten Benutzer eine freundliche Nachricht, in der sie darüber informiert werden, dass die Datei gelöscht wurde. Dieser Benutzer kann wählen, ob Änderungen verworfen oder die Datei gespeichert werden sollen.


- Es wurde ein Fehler behoben, der auftrat, wenn eine SyncBacked-Datei offline geöffnet und dann in der App umbenannt wurde, bevor sie gespeichert wurde.



[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

## <a name="version-2101-april-13"></a>Version 2101: 13. April
*Version 2101 (Build 13628.20664)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates) aufgeführt

## <a name="version-2101-march-09"></a>Version 2101: 09. März
*Version 2101 (Build 13628.20528)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Ein Problem wurde behoben, bei dem Excel nicht gestartet werden konnte bzw. unerwartet geschlossen wurde, wenn bestimmte Einstellungen für den Schutz vor Windows-Sicherheit-Exploits (SimExec, CallerCheck) verwendet wurden.


### <a name="outlook"></a>Outlook

- Ein Problem wurde behoben, das dazu geführt har, dass das Verschlüsselungssymbol bei E-Mails, die mit der Option „Nur mit Verschlüsselung“ gesendet wurden, nicht angezeigt wurde.


- Ein Problem wurde behoben, bei dem E-Mails als digital signiert versendet wurden, obwohl der Benutzer die Option deaktiviert hatte.


- Ein Problem wurde behoben, das die Anzeige der richtigen Standardsignatur im OWA beeinträchtigt hat.


- Es wurde ein Problem behoben, das dazu führte, dass das System hängenblieb, wenn Benutzer die Einstellungen unter „Cloudeinstellungen" aktualisierten.


- Ein Problem wurde behoben, das dazu führte, dass die App manchmal unerwartet geschlossen wurde, wenn Benutzer Suchvorgänge in Outlook ausführten.


- Es wurde ein Problem behoben, das bei Benutzern mit freigegebenen oder delegierten Postfächern mit großen Hierarchien in ihrem Profil zu Blockaden führte.


- Wir haben ein Problem behoben, das bei einigen Benutzern dazu führte, dass Outlook in bestimmten Suchszenarien unerwartet geschlossen wurde.


### <a name="project"></a>Project

- Ein Problem wurde behoben, bei dem die geplanten Kosten nicht korrekt hochgerechnet wurden, wenn eine Kostenressource einem Meilensteinvorgang zugewiesen wurde.


- Ein Problem wurde behoben, bei dem keine Rahmen für Vorgänge in der Teamplaneransicht angezeigt wurden.


- Ein Problem wurde behoben, bei dem Drag & Drop für Aufgaben in der Teamplaneransicht nicht funktioniert hat.


### <a name="office-suite"></a>Office-Suite

- Ein Problem im Zusammenhang mit Ereignisbenachrichtigungen für Mediencontroller wurde behoben.


- Ein Problem im Zusammenhang mit dem Timing des Media Player-Moduls wurde behoben.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2012-march-09"></a>Version 2012: 09. März
*Version 2012 (Build 13530.20628)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Benutzer auffordern, Vertraulichkeitsbezeichnungen anzuwenden:** Benutzer werden aufgefordert, eine Vertraulichkeitsbezeichnung anzuwenden, wenn die Richtlinie ihrer Organisation dies erfordert.

### <a name="powerpoint"></a>PowerPoint

- **Benutzer auffordern, Vertraulichkeitsbezeichnungen anzuwenden:** Benutzer werden aufgefordert, eine Vertraulichkeitsbezeichnungen anzuwenden, wenn die Richtlinie ihrer Organisation dies erfordert.

### <a name="word"></a>Word

- **Benutzer auffordern, Vertraulichkeitsbezeichnungen anzuwenden:** Benutzer werden aufgefordert, eine Vertraulichkeitsbezeichnung anzuwenden, wenn die Richtlinie ihrer Organisation dies erfordert.


## <a name="version-2012-february-09"></a>Version 2012: 09. Februar
*Version 2012 (Build 13530.20528)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="excel"></a>Excel

- **Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen. [Weitere Informationen](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **Überwachungsprotokollierung für Vertraulichkeitsbezeichnungen:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, werden diese Informationen jetzt den Administratoren in den Microsoft 365-Auditprotokollen zur Verfügung gestellt.

- **Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar. [Weitere Informationen](/microsoft-365/compliance/sensitivity-labels)

### <a name="outlook"></a>Outlook

- **Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen. [Weitere Informationen](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **Einbauen einer Zeitspanne zwischen unmittelbar aufeinander folgenden Besprechungen**: Geben Sie den Teilnehmern Zeit für eine Atempause und oder den Weg zwischen verschiedenen Besprechungsorten, indem Sie festlegen, dass Besprechungen standardmäßig 5–10 Minuten verspätet beginnen. [Weitere Informationen](https://support.office.com/article/ebb4c4c9-6992-4ea7-9772-8b5883df8500)

- **Überwachungsprotokollierung für Vertraulichkeitsbezeichnungen:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, werden diese Informationen jetzt den Administratoren in den Microsoft 365-Auditprotokollen zur Verfügung gestellt.

- **Jede Besprechung online:** Aktualisieren Sie Ihre Kalendereinstellungen, um jede Besprechung, die Sie erstellen, standardmäßig zu einer Teams-Besprechung zu machen. So müssen Sie nicht mehr daran denken, auf die Option "Teams-Besprechung" zu klicken.

- **Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar. [Weitere Informationen](/microsoft-365/compliance/sensitivity-labels)

- **Jede Besprechung online:** Aktualisieren Sie Ihre Kalendereinstellungen, um jede Besprechung, die Sie erstellen, standardmäßig zu einer Teams-Besprechung zu machen. So müssen Sie nicht mehr daran denken, auf die Option "Teams-Besprechung" zu klicken.

- **Neue Raumsuche:** suchen Sie in unterschiedlichen Kategorien nach Konferenzräumen.

- **Neue Buchungserfahrung für Konferenzräume und Arbeitsbereiche:** Die Buchungserfahrung für Konferenzräume wurde aktualisiert und zudem neue Funktionen hinzugefügt, mit denen Sie auch einzelne Arbeitsbereiche planen können.


### <a name="powerpoint"></a>PowerPoint

- **Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen. [Weitere Informationen](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br />Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://insider.office.com/de-DE/blog/svg-content-office-third-party-apps)

- **Überwachungsprotokollierung für Vertraulichkeitsbezeichnungen:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, werden diese Informationen jetzt den Administratoren in den Microsoft 365-Auditprotokollen zur Verfügung gestellt.

- **Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar. [Weitere Informationen](/microsoft-365/compliance/sensitivity-labels)

### <a name="visio"></a>Visio

- **Neue Azure-Schablonen und -Formen:** Wir haben viele weitere Schablonen hinzugefügt, die Ihnen beim Erstellen von aktuellen Azure-Diagrammen helfen. [Weitere Informationen](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word"></a>Word

- **Unterstützung für SVG-Zwischenablage:** Sie können jetzt SVG-Inhalte aus Office in Apps von Drittanbietern einfügen. [Weitere Informationen](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

- **Überwachungsprotokollierung für Vertraulichkeitsbezeichnungen:** Wenn Benutzer Vertraulichkeitsbezeichnungen auf ihre Dokumente und E-Mails anwenden, ändern oder entfernen, werden diese Informationen jetzt den Administratoren in den Microsoft 365-Auditprotokollen zur Verfügung gestellt.

- **Regierungskunden: Anwenden von Vertraulichkeitsbezeichnungen auf Ihre Dokumente und E-Mails:** Für Kunden in den GCC- und GCC-H-Umgebungen sind jetzt Funktionen zum Anwenden von Vertraulichkeitsbezeichnungen verfügbar. [Weitere Informationen](/microsoft-365/compliance/sensitivity-labels)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Durch diese Änderung wird ein Problem behoben, bei dem Schriftarten in Formeln nicht ordnungsgemäß angezeigt wurden.


- Es wurde ein Problem behoben, bei dem einigen Benutzern während der gemeinsamen Erstellung fälschlicherweise eine Statusleiste angezeigt wurde, die sie über eine neue Version einer Datei informierte.


- Es wurde ein Problem behoben, bei dem Excel möglicherweise Makros ohne Anfrage deaktiviert lässt, wenn eine Excel-Add-In-Datei geöffnet wird, die Excel 4.0 Makros beinhaltet.


- Ein Problem wurde behoben, bei dem Excel nicht gestartet werden konnte bzw. unerwartet geschlossen wurde, wenn bestimmte Einstellungen für den Schutz vor Windows-Sicherheit-Exploits (SimExec, CallerCheck) verwendet wurden.


- Es wurde ein Problem behoben, bei dem Excel unerwartet geschlossen werden konnte, wenn Sie das Menü "Werte anzeigen als" für eine PivotTable verwendeten.


- Es wurde ein Problem behoben, wodurch einige ältere Excel 4.0- und Excel 5.0-Makros sowie einige VBA-Aufrufe an "dialogsheets.show" beschädigt wurden.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, bei dem eine bearbeitete Signatur nicht gespeichert werden konnte, nachdem der Benutzer hierzu aufgefordert wurde.


- Es wurde ein Problem behoben, das bei einigen Benutzern dazu führte, dass Outlook in bestimmten Suchszenarien unerwartet geschlossen wurde.


- Es wurde ein Problem behoben, das bei einigen Kunden dazu führte, dass sich das System beim Laden ihrer Kalender aufhängte.


- Es wurde ein Problem behoben, das bei Benutzern mit freigegebenen oder delegierten Postfächern mit großen Hierarchien in ihrem Profil zu Blockaden führte.


### <a name="powerpoint"></a>PowerPoint

- Es wurde ein Problem behoben, bei dem der Befehl "Schriftgrad", der in QAT hinzugefügt wurde, beim Aktualisieren automatisch zum nächsten definierten Schriftgrad vervollständigt wird.


- Durch diese Änderung wird ein Problem behoben, bei dem Schriftarten in Formeln nicht ordnungsgemäß angezeigt wurden.


- Diese Änderung behebt ein Problem mit Pfadfüllungen beim Anwenden von "Formen zusammenführen"-Vorgängen mit bestimmten Geometrien.


### <a name="office-suite"></a>Office-Suite

- Anaheim WebView unterstützt noch keinen Windows Information Protection (WIP). Mit diesem Fix wird die Add-In-Plattform in Office wieder abwärtskompatibel mit WebView in einer Umgebung mit aktiviertem WIP. Dabei kann es sich entweder um Microsoft Edge Spartan WebView oder Trident WebView handeln, abhängig von der Computerumgebung des Kunden. Beide abwärtskompatiblem WebViews unterstützen WIP.


- Binäre Größe optimiert.


- Die Schließfolge der Datei wurde korrigiert, so dass alle voneinander abhängigen Komponenten ordnungsgemäß geschlossen werden.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2011-february-09"></a>Version 2011: 09. Februar
*Version 2011 (Build 13426.20658)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt

## <a name="version-2011-january-12"></a>Version 2011: 12. Januar
*Version 2011 (Build 13426.20526)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt


[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="access"></a>Zugriff

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a>Excel

- **Erstellen von Variablen zur Verwendung in Formeln:** Verbessern Sie Leistung, Lesbarkeit und Zusammensetzbarkeit mit der LET-Funktion. Mit dieser Funktion können Sie benannte Variablen in neuen oder bereits vorhandenen Formeln erstellen. [Weitere Informationen](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br />Weitere Detailinformationen finden Sie im [Blogbeitrag](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)

- **Erstellen eines benutzerdefinierten Datentyps in Power Query:** Verwenden Sie eine beliebige Datenquelle zum Erstellen eines benutzerdefinierten Datentyps, mit dem Sie mehrere verwandte Informationen in eine Spalte laden können. [Weitere Informationen](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br />Weitere Detailinformationen finden Sie unter [Blogbeitrag](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)

- **Benennen des neuen Blatts nach der Quellabfrage:** Wenn die Daten in das neue Blatt geladen werden, wird das Blatt basierend auf dem Namen der Quellabfrage benannt.

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a>OneNote

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a>Outlook

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


### <a name="powerpoint"></a>PowerPoint

- **Videobibliothek:** Erweitern Sie Ihre Dokumente mit einer Sammlung von kuratierten, lizenzfreien, in der App verfügbaren Videoaufnahmen.

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a>Project

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a>Publisher

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a>Visio

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a>Word

- **Automatisches Wechseln von Office-Designs:** Office kann Designs automatisch an Ihre Windows 10-Designeinstellungen anpassen. Wechseln Sie zu „Datei“ > „Konto“, und wählen Sie in der Dropdownliste „Office-Design“ den Eintrag „Systemeinstellung verwenden“ aus. [Weitere Informationen](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Ein Problem wurde behoben, bei dem Excel fälschlicherweise eine Meldungsleiste anzeigt, dass eine neue Version der Datei verfügbar ist, und den Benutzer auffordert, seine Änderungen in einer Kopie der Arbeitsmappe zu speichern oder die Änderungen zu verwerfen.


- Es wurde ein Problem behoben, bei dem Excel möglicherweise Makros ohne Anfrage deaktiviert lässt, wenn eine Excel-Add-In-Datei geöffnet wird, die Excel 4.0 Makros beinhaltet.


### <a name="outlook"></a>Outlook

- Es wurde ein Problem behoben, aufgrund dessen einige Benutzer keine Signaturen im Signaturen-Dropdownfeld sehen konnten, obwohl mindestens eine Signatur konfiguriert war.


- Wir haben einen Registrierungsschlüssel hinzugefügt, mit dem Kunden die Dateizeiteinbeziehung für Anhänge in IDataObject-Operationen (z. B. Drag/Drop, Zwischenablage) deaktivieren können.  HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments. REG_DWORD IncludeFileTimesInDataObject. 0 = Filetimes sind ausgeschlossen. 1 = (Standard) Filetimes sind enthalten.


- Es wurde ein Problem behoben, das bewirkt, dass Inline Bilder beim Antworten auf eine Nachricht mit einer Schutz Bezeichnung von Azure Information Protection nicht mehr angezeigt werden.


- Es wurde ein Problem behoben, aufgrund dessen das Ereignis "MailItem.BeforeAttachmentAdd" abgebrochen wurde.


- Ein Problem wurde behoben, durch das das Feld „An:“ in Aufgabenstatusberichten leer war.


- Es wurde ein Problem behoben, aufgrund dessen die ursprünglichen Teilnehmer einiger Besprechungen eine Absage erhielten, wenn ein anderer Teilnehmer die Besprechung weiterleitete.


### <a name="powerpoint"></a>PowerPoint

- Ein Problem wurde behoben, bei dem einige beschädigte PowerPoint-Dateien auch nach einem Dokumentreparaturvorgang nicht ordnungsgemäß geöffnet wurden.


- Es wurde ein Fehler behoben, bei dem beim Speichern der Datei nach dem Duplizieren einer Folie, die ein neu aufgezeichnetes Audiosignal enthält, ein Fehler aufgetreten ist.


- Ein VBA-Problem wurde behoben, bei dem "Slide.Shapes.AddMediaObject2" mit veralteten Videoformaten abstürzt (MPG-1, MPEG-2).


- Durch diese Änderung wird ein Problem beim Behandeln von Fehlern behoben, das während des Ladens von Videos auftreten konnte.


- Ein Problem mit dem Kopieren/Einfügen einer Formel aus Word in PowerPoint wurde behoben.


### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem bestimmte Projekte geöffnet werden konnten, wenn ein Problem mit der Projektdatei in einem bestimmten Teil der Last vorlag.


### <a name="word"></a>Word

- Ein Assert-Fehler wurde behoben, der von optimierten Gates betroffen war.


- Es wurde ein Problem behoben, bei dem Dokumentformate durch andere Formate aus der Vorlage ersetzt werden.


- Durch diese Änderung wird ein Problem mit dem Cursor beim Bearbeiten eines Dokuments behoben.


- Ein Problem mit dem Kopieren/Einfügen einer Formel aus Word in PowerPoint wurde behoben.


### <a name="office-suite"></a>Office-Suite

- Es wurde ein Problem behoben, bei dem aufgrund fehlender Registrierungseinträge die Installation einer neueren Version von Office über bestimmte ältere Versionen zu einer eingeschränkten Funktionalität führen konnte (beispielsweise war die Verwendung der Power-Abfrage nicht möglich).


- Es wurde ein Problem behoben, bei dem eine Datei als NICHT SyncBacked geöffnet wurde, wenn die URLs von Zwischenspeicher und OneDrive nicht übereinstimmten.


- Ein Problem wurde behoben, bei dem „SaveRequestManagerCam“ dazu führte, dass die Anwendung geschlossen wurde, anstatt einen Fehler zurückzugeben.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-2010-january-12"></a>Version 2010: 12. Januar
*Version 2010 (Build 13328.20550)*

Sicherheitsupdates sind [hier](./microsoft365-apps-security-updates.md) aufgeführt



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)


[//]: # (BUGDETAILS NICHT ENTFERNEN INHALTSENDE)

[//]: # (ENDE NICHT ENTFERNEN)

> [!NOTE]
> Wenn Sie Hilfe bei einem Problem mit der Nutzung von Office benötigen, empfehlen wir, dass Sie Ihre Frage im [Microsoft Answers-Forum](https://answers.microsoft.com/) oder in der [Tech-Community](https://techcommunity.microsoft.com/) veröffentlichen, oder Sie können sich an den [Support](https://support.microsoft.com/contactus) wenden.


[//]: # (ADMIN CENTER-METADATENINHALT NICHT ÄNDERN BEGINN)
[//]: # (|Win32|MEC|Production|Feature|16.0.14026.20334|version-2105-july-13|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13929.20408|version-2104-june-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13901.20516|version-2103-may-11|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13801.20506|version-2102-april-13|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13628.20528|version-2101-march-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13530.20528|version-2012-february-09|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13426.20526|version-2011-january-12|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13328.20478|version-2010-december-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13231.20514|version-2009-november-10|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13127.20638|version-2008-october-13|)
[//]: # (ADMIN CENTER-METADATENINHALT NICHT ÄNDERN ENDE)

---
title: Versionshinweise für Releases im halbjährlichen Kanal im Jahr 2020
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt IT-Experten Versionshinweise für Releases im halbjährlichen Kanal für Office 365 ProPlus im Jahr 2020 zur Verfügung.
ms.openlocfilehash: 974a5db6f3bfba2bb20cd75f4e35a2777ea94ca8
ms.sourcegitcommit: 3598ca5e26109a1f99349ce3a4e70cb1d6f13e05
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 02/14/2020
ms.locfileid: "41978583"
---
# <a name="release-notes-for-semi-annual-channel-releases-in-2020"></a>Versionshinweise für Releases im halbjährlichen Kanal im Jahr 2020

Diese Versionshinweise enthalten Informationen zu neuen Features und nicht sicherheitsrelevante Updates, die in den halbjährlichen Updatekanal für Office 365 ProPlus im Jahre 2020 Visio Pro für Office 365, Project Online Desktop Client und Office 365 Business enthalten sind.

> [!NOTE]
>
>- Features (und häufig auch Fixes) werden häufig über einen Zeitraum in den halbjährlichen Updatekanal eingeführt. Wenn etwas, das nachstehend beschrieben ist, nicht sofort angezeigt wird, wird es in Kürze verfügbar sein. [Weitere Informationen](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- OneNote 2016 wird nicht standardmäßig einbezogen, wenn ein Benutzer Office 365 aus dem Office-Portal herunterlädt und auf Windows 10 installiert.


## <a name="version-1908-february-11"></a>Version 1908: 11. Februar
*Version 1908 (Build 11929.20606)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/de-DE/officeupdates/office365-proplus-security-updates) aufgeführt


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


- Es wurde ein Problem behoben, bei dem beim Anzeigen von mehr als 30 Kalendern in einer Citrix-Umgebung ein Absturz verursacht wurde. [Hier](https://support.microsoft.com/de-DE/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) ist die einzelne KB, in der dies für frühere Versionen dokumentiert wurde.

- Behebt ein Problem, bei dem Nutzer Probleme mit der Synchronisierung freigegebener Kalenderordner mit dem OST hatten, was zu Berechtigungsfehlern führte, wenn sie versuchten, mit diesen Ordnern zu interagieren.


### <a name="powerpoint"></a>PowerPoint

- Verbessertes Szenario zum Kopieren und Einfügen Das Kopieren der Form in eine PowerPoint-Folie und das Einfügen in eine andere Folie in einer Schleife schlägt möglicherweise mit Ausnahme fehl.


- Es wurde ein Problem behoben, das zu einer langsameren Leistung zwischen Nutzern, die zusammenarbeiten, führte.

- Es wurde ein Problem behoben, das auftreten konnte, wenn eine Datei, die schrittweise geöffnet wurde, eine Folie mit mehr als einem eingebetteten Mediendatenstrom enthielt.

- Wir haben ein Problem behoben, bei dem beim ersten Start von PowerPoint möglicherweise keine Sicherheitswarnmeldung für nicht vertrauenswürdige Add-Ins angezeigt wird.

### <a name="project"></a>Project

- Es wurde ein Problem behoben, bei dem die tatsächliche Arbeit zwischen Arbeitszeittabelle und Projektplan unterschiedlich sein kann, da Ressourcenkalender nicht aktualisiert werden, wenn sich der Basiskalender ändert.

### <a name="word"></a>Word

- Ein Absturz in Word wurde behoben, indem es von einer veralteten API entfernt wurde.

### <a name="office-suite"></a>Office-Suite

- Diese Änderung behebt das korrekte Rendern von Bildern nach dem Öffnen einer beschädigten Datei.



[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1902-february-11"></a>Version 1902: 11. Februar
*Version 1902 (Build 11328.20526)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/de-DE/officeupdates/office365-proplus-security-updates) aufgeführt


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="outlook"></a>Outlook

- Behebt ein Problem, das dazu führte, dass Nutzer auf einen Verschlüsselungsalgorithmus stießen. Es werden keine Fehler beim Senden einer verschlüsselten E-Mail unterstützt.


### <a name="word"></a>Word

- Ein Absturz in Word wurde behoben, indem es von einer veralteten API entfernt wurde.

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

## <a name="version-1808-february-11"></a>Version 1808: 11. Februar
*Version 1808 (Build 10730.20438)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/de-DE/officeupdates/office365-proplus-security-updates) aufgeführt

[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1908-january-14"></a>Version 1908: 14. Januar
*Version 1908 (Build 11929.20562)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates) aufgeführt

[//]: # (FEATUREDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="feature-updates"></a>Featureupdates
### <a name="access"></a>Access

- **Registerkarten für Datenbankobjekte im Blick behalten:** Erkennen Sie eindeutig die aktive Registerkarte, ordnen Sie Registerkarten durch Ziehen mit der Maus neu an, und schließen Sie Datenbankobjekte mit nur einem Klick.

- **Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an. Das Wechseln zwischen den Konten ist so einfach wie nie. [Weitere Informationen](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Mehr Platz zum Zoomen:** Vergrößern Sie das Zoomfeld, ändern Sie die Schriftart, und die Zoomfunktion merkt sich alles. [Weitere Informationen](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a>Excel

- **Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an. Das Wechseln zwischen den Konten ist so einfach wie nie. [Weitere Informationen](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Erhöhen Sie die Reichweite Ihrer Inhalte**: Möchten Sie Ihre Präsentationen barrierefrei gestalten? Die Barrierefreiheitsprüfung kann dies für Sie im Auge behalten, ohne Ihnen dabei in die Quere zu kommen. Probieren Sie es aus, indem Sie auf „Überprüfen“ > „Barrierefreiheit überprüfen“ klicken. Wir werden Sie in der Statusleiste informieren, wenn wir etwas finden, dass Sie sich ansehen müssen.

- **Schnelle Dateisuche:** Sie suchen nach einer Datei, an der Sie kürzlich gearbeitet haben? Geben Sie einfach in das Suchfeld unter „Datei“ > „Start“ den Namen der gesuchten Datei ein.

- **Verleihen Sie Ihrem Arbeitsblatt mehr Lebendigkeit:** Fügen Sie animierte 3D-Grafiken ein, um zu sehen, wie Herzen schlagen, Planeten sich in einer Umlaufbahn bewegen und wie ein T-Rex durch die Arbeitsmappe stampft. [Weitere Informationen](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- **Erfahren Sie mehr über Ihre Daten:** Die neue Schaltfläche "Ideen" sucht in Ihren Daten nach Mustern und verwendet diese, um intelligente, persönliche Vorschläge zu erstellen. [Weitere Informationen](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **Zusammenarbeiten ist jetzt noch einfacher:** Verbesserungen bei der gemeinsamen Dokumenterstellung führen dazu, dass Ihre Änderungen beim Arbeiten mit bedingter Formatierung, Zellformatvorlagen und mehr nahtlos mit denen Ihrer Mitarbeiter zusammengeführt werden.

- **Verknüpfen von Tabellen in ähnlichen Spalten:** Abrufen und Transformieren (Power Query) bietet jetzt eine ungefähre Textübereinstimmungslogik (auch Fuzzyübereinstimmung genannt) beim Vergleichen von Spalten zum Zusammenführen von Tabellen. [Weitere Informationen](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- **Schnelles Programmieren mit Power Query-Verbesserungen**: Mit AutoVervollständigen und farbiger Syntax können Sie Code schnell fertigstellen. Außerdem können Sie auf einfache Weise Funktionen, Spalten und Parameter ermitteln.

### <a name="outlook"></a>Outlook

- **Wir haben die Outlook-Benutzererfahrung für Sie aktualisiert**: Eine vereinfachte Oberfläche, die über "In Kürze verfügbar" bereits in der Vorschau zur Verfügung stand und Ihnen helfen soll, sich auf das Wesentliche zu konzentrieren. [Weitere Informationen](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- **Ein vereinfachtes und benutzerdefiniertes Menüband**: Genießen Sie eine optimierte, einzelne Reihe der am häufigsten verwendeten Schaltflächen. Sie können einfach zwischen klassischer und vereinfachter Ansicht sowie den Befehlen "Anheften" und "Lösen" wechseln. [Weitere Informationen](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- **Arbeiten während des Verschiebens von Nachrichten:** Outlook verschiebt Nachrichten nun im Hintergrund, sodass Sie weiterarbeiten können, während viele Nachrichten zwischen Ordnern verschoben werden.

- **Einbauen einer Zeitspanne zwischen unmittelbar aufeinander folgenden Besprechungen**: Geben Sie den Teilnehmern Zeit für eine Atempause und oder den Weg zwischen verschiedenen Besprechungsorten, indem Sie festlegen, dass Besprechungen standardmäßig 5–10 Minuten früher enden.

- **Wählen Sie Ihre bevorzugte Aktion aus:** Verwenden Sie keine Kennzeichnung und Löschung? Wie sieht es mit "Archivieren" oder "Als gelesen markieren" aus? Passen Sie das Menü mit schnellen Aktionen mit den am häufigsten verwendeten Befehlen an.

- **Benutzer können Ihre Memes einsehen:** Wenn Text oder statische Bilder einfach nicht genug sind, verwenden Sie ein animiertes GIF zur Veranschaulichung. [Weitere Informationen](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)

- **Ein weiteres oder engeres Layout? Sie entscheiden**: Sie können entscheiden, ob Sie zwischen Elementen mehr Abstand wünschen oder ob Sie mehr Elemente in einem engeren Layout bevorzugen.

- **Eine schnellere Methode, um Konten hinzuzufügen**: Dank der Verbesserungen beim Einrichten von Konten ist es einfacher denn je, Outlook.com- und Gmail-Konten mit zweistufiger Authentifizierung zu Outlook hinzuzufügen. [Weitere Informationen](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- **Verabschieden Sie sich von den Synchronisationsbeschränkungen**: Outlook-Verbesserungen bedeuten, dass die Ordnerbeschränkung aufgehoben ist, also fahren Sie fort und synchronisieren Sie Ihre gemeinsamen Postfächer.

### <a name="powerpoint"></a>PowerPoint

- **Bessere Formwandlung**: Geben Sie Ihren Shapes einen Namen, um mehr Kontrolle über ihr Morphen zu haben. [Weitere Informationen](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- **Schnelle Dateisuche:** Sie suchen nach einer Datei, an der Sie kürzlich gearbeitet haben? Geben Sie einfach in das Suchfeld unter „Datei“ > „Start“ den Namen der gesuchten Datei ein.

- **Erhöhen Sie die Reichweite Ihrer Inhalte**: Möchten Sie Ihre Präsentationen barrierefrei gestalten? Die Barrierefreiheitsprüfung kann dies für Sie im Auge behalten, ohne Ihnen dabei in die Quere zu kommen. Probieren Sie es aus, indem Sie auf „Überprüfen“ > „Barrierefreiheit überprüfen“ klicken. Wir werden Sie in der Statusleiste informieren, wenn wir etwas finden, dass Sie sich ansehen müssen.

- **Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an. Das Wechseln zwischen den Konten ist so einfach wie nie. [Weitere Informationen](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Neuer Speicherort für Onlinevideos**: Speichern Sie ein Video in Microsoft Stream, damit es jeder in Ihrem Unternehmen ansehen kann. Fügen Sie den Videolink ein, und profitieren Sie von Multimediapräsentationen mit einem Bruchteil der üblichen Dateigröße. [Weitere Informationen](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Speichern Sie Ihre Änderungen, während sie entstehen**: Laden Sie Ihre Dateien in OneDrive hoch, um sicherzustellen, dass alle Ihre Aktualisierungen automatisch gespeichert werden.

- **Befragen Sie Ihr Publikum mit einem Quiz oder einer Umfrage:** Fügen Sie ein Quiz oder eine Umfrage einer Folie hinzu. Office sammelt und speichert die Antworten für Sie. [Weitere Informationen](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

- **Das Einfügen von Onlinevideos ist jetzt einfacher denn je:** Möchten Sie auf Ihrer Folie ein Video von Vimeo oder YouTube einfügen? Hierfür benötigen Sie nur den Link zur Videoseite. [Weitere Informationen](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

### <a name="project"></a>Project

- **Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an. Das Wechseln zwischen den Konten ist so einfach wie nie. [Weitere Informationen](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a>Visio

- **Exportieren von Prozessdiagrammen nach Word:** Fügen Sie Diagramminhalte, wie Formen und Metadaten, automatisch zu einem Word-Dokument hinzu. Passen Sie dann das Dokument an, um Prozessrichtlinien und Handbücher zu erstellen. [Weitere Informationen](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- **Zweiter Blick auf Datenflussdiagramme:** Attraktive neue Layouts für Data Visualizer-Flussdiagramme sind übersichtlich, klar und einfach zu verstehen. Klicken Sie auf die Registerkarte Entwurf für weitere Optionen.

- **Integrierte Azure Schablonen:** Entwerfen Sie eine Cloud-App, oder planen Sie eine Architektur mithilfe von Dutzenden von Azure-Schablonen. [Weitere Informationen](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- **Verabschieden Sie sich von fehlerhaften Excel-Verknüpfungen:** Die Excel-Arbeitsmappe, die mit Ihrem Datenschnellansichtsdiagramms verknüpft ist, kann nicht gefunden werden? Verknüpfen Sie es erneut, und es kann weiter gehen. [Weitere Informationen](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- **Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an. Das Wechseln zwischen den Konten ist so einfach wie nie. [Weitere Informationen](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Exportieren von Visio-Visualisierungen aus Power BI**: Die Visio-Visualisierung für Power BI wird nun ordnungsgemäß angezeigt, wenn Sie Power BI-Berichte beispielsweise als PDF-Dateien, PowerPoint-Dateien und mehr exportieren. [Weitere Informationen](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a>Word

- **Der Modus „Lerntools“ bietet zusätzliche Unterstützung für weitere Seitenfarben:** Lerntools in Word unterstützt weitere Farben für Seitendesigns, wodurch die Hintergrundfarbe der Seite geändert werden kann. Viele Personen haben Herausforderungen beim Lesen mit einem ganz weißen oder schwarzem Hintergrund, deshalb haben wir die Auswahl von Farben in Word auf PC und Mac erweitert.

- **Natürliche Bearbeitung mit dem Freihand-Editor:** Mit einem einzigen Strich können Sie Wörter trennen oder verbinden, eine neue Zeile hinzufügen oder Wörter mithilfe Ihres Stifts einfügen. [Weitere Informationen](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **Verwandeln Sie ihr Dokument von statisch in erstaunlich:** Verwandeln Sie Ihr Dokument in eine interaktive, einfach freizugebende Webseite, die auf jedem Gerät großartig aussieht. [Weitere Informationen](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

- **Erhöhen Sie die Reichweite Ihrer Inhalte**: Möchten Sie Ihre Dokumente barrierefrei gestalten? Die Barrierefreiheitsprüfung kann dies für Sie im Auge behalten, ohne Ihnen dabei in die Quere zu kommen. Probieren Sie es aus, indem Sie auf „Überprüfen“ > „Barrierefreiheit überprüfen“ klicken. Wir werden Sie in der Statusleiste informieren, wenn wir etwas finden, dass Sie sich ansehen müssen.

- **Schnelle Dateisuche:** Sie suchen nach einer Datei, an der Sie kürzlich gearbeitet haben? Geben Sie einfach in das Suchfeld unter „Datei“ > „Start“ den Namen der gesuchten Datei ein.

- **Nahtlos wechseln:** Der neue Konto-Manager zeigt alle Ihre geschäftlichen und privaten Office 365-Konten an einem Ort an. Das Wechseln zwischen den Konten ist so einfach wie nie. [Weitere Informationen](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Verabschieden Sie sich von Ablenkungen**: Eine Mac-Lieblingsfunktion ist nun für Windows verfügbar. Wechseln Sie im Menü Ansicht in den Fokusmodus, damit Sie nicht abgelenkt werden und sich auf Ihre Arbeit konzentrieren können. [Weitere Informationen](https://support.office.com/article/51af2fb2-194f-424b-ab7e-b65de9ec9292)

- **Verbessern Sie mit Fokus Linie das Verständnis:** Gehen Sie ohne Ablenkungen von Zeile zu Zeile durch ein Dokument. Passen Sie den Fokus an, um eine, drei oder fünf Zeilen gleichzeitig in die Ansicht zu setzen. [Weitere Informationen](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)

- **Speichern Sie Ihre Änderungen, während sie entstehen**: Laden Sie Ihre Dateien in OneDrive hoch, um sicherzustellen, dass alle Ihre Aktualisierungen automatisch gespeichert werden.

- **Machen Sie andere mit \@Erwähnungen auf sich aufmerksam:** Mithilfe von @Erwähnungen in Kommentaren können Sie Kollegen informieren, wenn Sie deren Input benötigen. [Weitere Informationen](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="office-suite"></a>Office-Suite

- **Schnelle Dateisuche:** Sie suchen nach einer Datei, an der Sie kürzlich gearbeitet haben? Geben Sie einfach in das Suchfeld auf der Registerkarte "Datei" > "Öffnen" den Namen der gesuchten Datei ein.

- **Speichern Sie Ihre Änderungen, während sie entstehen**: Laden Sie Ihre Dateien in OneDrive hoch, um sicherzustellen, dass alle Ihre Aktualisierungen automatisch gespeichert werden.

- **Kontrollmechanismen für den Datenschutz:** Neue aktualisierte und verbesserte Kontrollmechanismen für Diagnosedaten und verbundene Oberflächen. [Weitere Informationen](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- **Office-Symbole mit neuem Look:** Die Office-Symbole wurden neu gestaltet, um die einfache, leistungsstarke und intelligente Office-Benutzeroberfläche widerzuspiegeln.

- **Installation von Microsoft Teams**: Microsoft Teams ist in bestehenden Installationen von Office 365 ProPlus standardmäßig installiert. [Weitere Informationen](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (FEATUREDETAILS NICHT ENTFERNEN ENDE INHALT)

<br/>

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="access"></a>Access

- Mit diesem Update wird ein Problem behoben, durch das bei einem Aggregat wie "Summe" das Ergebnis auf einen ganzzahligen Wert abgeschnitten werden kann.

- Mit diesem Update wird ein Problem behoben, bei dem eine Union-Abfrage, die Verweise auf Remotetabellen enthält (z. B. SQL Server-Tabellen) möglicherweise dazu führt, dass Access geschlossen und neu gestartet wird.

- Mit diesem Update wird ein Problem in Microsoft Access behoben, das den Fehler &quot;Abfrage ist beschädigt&quot; verursachen kann, wenn eine Aktualisierungsabfrage ausgeführt oder eine UPDATE-Anweisung in SQL verwendet wird.

### <a name="excel"></a>Excel

- Die Niederländische Tastenkombination für Dokumenttitel wurde in Alt-G geändert.

- Es wurde ein Problem in Excel behoben, bei dem Makros, die Shapes oder Steuerelementen zugeordnet sind, möglicherweise eine falsche Fehlermeldung anzeigen oder an falschen Zielbereichen arbeiten.

- Es wurde ein Problem mit "Suchen und ersetzen" gelöst, durch das sich die Position des Fokus im Dialogfeld änderte, nachdem das erste Element gefunden wurde.

- Hiermit wird ein Problem behoben, durch das die Änderung der Sortierung einer PivotTable und deren Aktualisierung während der gemeinsamen Dokumenterstellung mit anderen Benutzern zu einem Absturz führen kann.

- Ein Problem wurde behoben, bei dem der Filter für eine OLAP-PivotTable auf einen Wert festgelegt wurde, der aus dem Cube entfernt wurde.

- Es wurde ein Problem mit Farben behoben, die in der Vorschau beim Einfügen von Diagrammen mithilfe von Diagrammvorlagen verwendet wurden.

- Ein Problem wurde behoben, durch das Punkt-/Liniendiagramme beim Ändern der Reihensammlung möglicherweise nicht ordnungsgemäß dargestellt wurden.

- Ein Problem wurde behoben, durch das Wasserfall- und Trichterdiagramme beim Einfügen oder Löschen von Zellen nicht mehr mit Tabellen synchronisiert wurden.

- Ein Konflikt beim Zusammenführen in Excel wurde behoben, durch den Benutzer aufgefordert wurden, die Arbeitsmappe erneut zu öffnen, um die Änderungen zu übernehmen.

- Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.

- Ein Problem wurde behoben, durch das ein Makro-Laufzeitfehler beim Aktivieren minimierter Fenster verursacht wurde.

- Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.

- Ein Problem wurde behoben, durch das Ausschneide- und Einfügevorgänge neben einer Tabelle fehlschlugen, wenn die gemeinsame Dokumenterstellung zusammen mit anderen Benutzern durchgeführt wurde.

- Ein Problem wurde gelöst, das bei Änderung von benutzerdefinierten Eigenschaften von ausgeführten Makros zu Unterbrechungen bei der gemeinsamen Dokumentenerstellung führte.

- Es gab ein Problem, bei dem Sie keine Elemente aus dem Kombinationsfeld eines WPF-Formulars (Windows Presentation Foundation) auswählen konnten, das von einem Add-n geöffnet wurde.

- Es wurde ein Problem behoben, das bei der Suche nach zuletzt verwendeten Dateien zu einem Absturz geführt hat, wenn keine Arbeitsmappe geöffnet ist.

- Ein Leistungsproblem mit asynchronen benutzerdefinierten Funktionen, das deren synchrone Ausführung zur Folge hatte.

- Erhebliche Verbesserungen der Leistung beim Löschen von Spalten mit verbundenen Zellen.

- Wir haben ein Problem gelöst, durch das das Auswählen einer Zelle nach dem Scrollen dazu führen konnte, dass die falsche Zelle ausgewählt wurde.

- Ein Problem wurde behoben, bei dem die Verweis-Funktion einen Fehler zurückgeben kann.

- Ein Problem wurde behoben, das beim Öffnen von in früheren Versionen von Office erstellten Arbeitsmappen in aktuellen Versionen von Office zu Programmabstürzen von Excel führen konnte.

- Problem mit langsamer Leistung beim Klicken auf die Schaltfläche "Schriftfarbe", wenn eine Datei über eine umfangreiche bedingte Formatierung verfügt.

- Ein Problem wurde behoben, bei dem der Druckbereich in der Seitenansicht nicht korrekt war.

- Excel könnte ein Problem aufweisen, durch das das Bearbeiten einer geschützten Datei von einer nicht vertrauenswürdigen Netzwerkfreigabe zu einem Fehler in Excel geführt haben könnte.

- Die Leistung der Filterung nach Farbe wurde deutlich verbessert.

- Ein Problem wurde behoben, durch das Links in bestimmte geschützte Blätter nicht eingefügt werden konnten.

- Mehr als 16 Add-Ins wurden aktiviert, die angezeigt werden, wenn der Add-In-Manager durchsucht wird.

- Diese Änderung umgeht ein Problem mit bestimmten Intel-Grafiktreibern durch Verwendung des Softwarerenderings.

- Die Links von cid:-Bildern aus Outlook-Nachrichten können nun auf Anforderung erfolgreich unterbrochen werden.

- Mit diesem Update wird ein Fehler behoben, der dazu führen kann, dass Office-Dokumente nicht auf OneDrive for Business hochgeladen werden können und die Fehlermeldung "Upload fehlgeschlagen" angezeigt wird.

- Problem im Feature "Excel-Ideen" behoben: Ein Fehler trat auf, wenn das Add-In durch Klicken auf die Schaltfläche "Ideen" im Win32-Client geladen wurde.

### <a name="outlook"></a>Outlook

- Die Links von cid:-Bildern aus Outlook-Nachrichten können nun auf Anforderung erfolgreich unterbrochen werden.

- Ein Problem wurde behoben, das dazu führte, dass bei Benutzern, die Ihr Postfach von Standard- auf moderne Authentifizierung aktualisiert hatten, das falschen Konto mit ihrem Outlook-Profil verknüpft wurde.

- Behebt ein Problem, durch das Web-Add-Ins auf von Digital Rights Management verwaltete Nachrichten zugreifen konnten, wenn dies nicht möglich sein sollte.

- Es wurde ein Problem behoben, das bewirkt hat, dass die URL für den einfachen Mauszeiger bei einigen Safelinks nicht angezeigt wird.

- Hiermit wird die Blockierungslogik für Anlagen in Outlook aktualisiert, um auch Python-Anlagen zu blockieren.

- Es wurde ein Problem behoben, das bewirkt, dass einer Teilmenge von POP3-Benutzern alle E-Mails im nur-Text-Format anzeigt werden, und zwar unabhängig von den Einstellungen. Mit diesem Fix wird die Anzeige der HTML-formatierten Nachrichten wiederhergestellt.

- Es wurde ein Problem behoben, durch das Benutzern beim Kopieren von Elementen aus Ihrem primären Kalender in einen Gruppenkalender ein Berechtigungsfehler angezeigt wird.

- Ein Problem wurde behoben, bei dem Benutzer nicht in der Lage waren, über eine Sprachausgabe auf Standortvorschläge zuzugreifen.

- Es wurde ein Problem behoben, durch das Benutzer mit einer spürbaren Verzögerung beim Interagieren mit ihren Postfachordnern über Tastenkombinationen konfrontiert waren.

- Es wurde ein Problem behoben, das einen Speicherverlust bei sehr langen Outlook-Sitzungen verursachte.

- Es wurde ein Problem behoben, durch das Benutzern eine beim Öffnen des Dialogfelds "Regeln" die folgende Meldung "Die Regeln auf diesem Computer stimmen nicht mit den Regeln in Microsoft Exchange überein" angezeigt wurde.

- Es wurde ein Problem behoben, das bei der Interaktion mit bestimmten Safelinks in Outlook zu einem Absturz führte.

- Ein Problem wurde behoben, das für Vorgesetzte Unklarheit darüber verursacht hat, ob eine Stellvertretung bereits auf eine bestimmte Besprechungsanfrage geantwortet hat.

- Es wurde ein Problem behoben, das bei der Verarbeitung von Antworten der AutoErmittlung zu einem Absturz führte.

- Es wurde ein Problem behoben, das bewirkt hat, dass Benutzer ein leeres Meldungsfeld mit einer "OK"-Schaltfläche angezeigt bekamen, wenn Sie versuchten, den Support über den Kontext der Kontoerstellung zu kontaktieren.

- Diese Änderung ermöglicht es Administratoren, eine Richtlinie zu aktivieren, um in den Eingabeaufforderungen der AutoErmittlung-Authentifizierung die bereitgestellten E-Mail-Konten vor UPN zu bevorzugen. Standardmäßig bevorzugt AutoErmittlung den UPN des Kontos, wenn dieser verfügbar ist.

- Ein Problem wurde behoben, durch das Benutzern Fehler beim Durchsuchen moderner Gruppen angezeigt wurden.

- Ein Problem wurde behoben, das dazu führte, dass Outlook-Benutzer in bestimmten Szenarien im Zustand " Kennwort erforderlich " stecken geblieben sind.

- Ein Problem wurde behoben, bei dem Benutzer Raumvorschläge für Besprechungen, die außerhalb der Verfügbarkeitszeiten dieses Raums stattfanden, einsehen konnten.

- Ein Problem wurde behoben, durch das Benutzer beim Senden einer verschlüsselten E-Mail den Fehler "Verschlüsselungsalgorithmen wird nicht unterstützt" angezeigt wurde.

- Ein Problem für nicht englischsprachige Benutzer wurde behoben, bei dem die Betreffzeile in einer E-Mail unglaublich klein war.

- Ein Problem wurde behoben, durch das bei einigen Benutzern beim Hinzufügen eines sekundären Exchange-Kontos doppelte Sonderordner angezeigt wurden.

- Ein Problem wurde behoben, das einen Absturz verursachte, wenn Benutzer versuchten, aus einer "Verpasste Unterhaltung"-Nachricht heraus eine Regel zu erstellen.

- Es wurde ein Problem mit der Auswahl des SMIME-Algorithmus behoben.

- Es wurde ein Problem behoben, bei dem Richtlinientipps bei Verwendung eines alternativen Absenders nicht angezeigt wurden.

- Ein Problem wurde behoben, durch das Benutzer einen Speicherverlust im Outlook-Prozess beobachten konnten.

- Ein Problem wurde behoben, das zu sporadischen Abstürzen führte, wenn Benutzer ihre Anwesenheitsinformationen aktualisierten.

- Ein Problem wurde behoben, das bewirkt, dass die aktuelle Ordnersuche zweitweise fehlschlägt.

- Ein Problem wurde behoben, bei dem einige Benutzer beim Versuch, ihre Cloud-Einstellungen für Outlook abzurufen, auf Authentifizierungsfehler stießen.

- Es wurde ein Problem behoben, durch das die Such-Feedback-Umgebung zum Hängen gebracht wurde.

- Es wurde ein Problem behoben, das bei der Verarbeitung von Antworten der AutoErmittlung zu einem Absturz führte.

- Ein Problem wurde behoben, das zu sporadischen Abstürzen führte, wenn Benutzer ihre Anwesenheitsinformationen aktualisierten.

### <a name="powerpoint"></a>PowerPoint

- Ein Problem wurde behoben, bei dem einige Add-Ins unerwartete Fehler bei Formen in Diagrammen verursachen konnten.

- Die Links von cid:-Bildern aus Outlook-Nachrichten können nun auf Anforderung erfolgreich unterbrochen werden.

- Diese Änderung stellt den barrierefreien Namen für PowerPoint-Videosteuerelemente wieder her.

- Wir haben ein Problem behoben, das verhindern konnte, dass einige Animationen starteten.

- Ein Problem wurde behoben, durch das beim Kopieren einer Folie aus einer Präsentation in eine andere möglicherweise doppelte Master erstellt wurden.

- Bei Dateien mit neuen modernen Kommentaren wird eine gelbe Warnung angezeigt, wenn sie in einer nicht unterstützten Version geöffnet werden.

- Zuverlässigkeitsfix: Ein Problem wurde behoben, bei ein Add-In von Drittanbietern zu einem Absturz von PowerPoint führen konnte.

- Ein Problem wurde behoben, bei dem Katakana-Zeichen mit halber Breite in vertikalen Textfeldern in PowerPoint nicht ordnungsgemäß gedreht wurden.

### <a name="project"></a>Project

- Ein Problem wurde behoben, durch das Benutzer unter Windows 7 Projekte aus Project Web-App und SharePoint-Websites öffnen können.

- Ein Problem wurde identifiziert, bei dem Benutzer beim Öffnen eines schreibgeschützten Projekts möglicherweise mehrere Meldungen erhielten.

- Der Befehl "Alles abgleichen" löst eine Ressourcenüberlastung nicht richtig auf.

- Bei einer Aufgabe mit keiner Arbeit an einem Vorgang kann der Vorgang möglicherweise nicht als erledigt gekennzeichnet werden und wird stets bei 99 % angezeigt.

### <a name="visio"></a>Visio

- Das Exportieren als SVG aus Visio funktionierte für eine Vielzahl von Shapes nicht.

### <a name="word"></a>Word

- Diese Änderung führt zu Leistungsverbesserungen beim Öffnen von Dokumenten mit Word.

- Die Links von cid:-Bildern aus Outlook-Nachrichten können nun auf Anforderung erfolgreich unterbrochen werden.

- Ein Problem wurde behoben, das zu Skalierungsproblemen führen konnte, wenn auf Deskjet-Druckern gedruckt wurde.

- Ein Problem wurde behoben, durch dass beim Nachverfolgen von Änderungen der Vorgang manchmal zu einer Endlosschleife führte.

- Verschiedene Probleme behoben, bei denen die APP beim Herunterfahren hängen bleiben könnte. Außerdem wurden Absturzursachen im Zusammenhang mit bestimmten Add-Ins behoben.

### <a name="office-suite"></a>Office-Suite

- Behebung eines Problems, aufgrund dessen der neue Zeitname "Reiwa" in Hiragana und Kanji als Rechtschreibfehler oder Grammatikfehler eingestuft wurde.

- Ein Problem wurde behoben, bei dem Benutzer beim Versuch, in SharePoint 2016 gespeicherte Dateien freizugeben, die Meldung "Leider verhindert etwas, dass wir dies freigeben" erhielten.

- Ein Problem wurde behoben, das zu Datenverlusten in Sitzungen führen konnte, bei denen sowohl die gemeinsame Dokumenterstellung als auch die Offlinebearbeitung in PowerPoint genutzt wurde.

- Dieser Fix beseitigt die Ursache für einen Absturz, der beim Öffnen einer Datei auftreten konnte.

- Verhindert, dass für PowerPoint-Benutzer bei Onlinepräsentationen Fehler auftreten.

- In einigen Fällen wurde für eine von der Synchronisierungs-Engine gesicherte SharePoint-Datei "Gespeichert" angezeigt, ohne dass die Änderungen tatsächlich gespeichert wurden, was zu einem Datenverlust führte.

- Das Problem, bei dem Benutzer möglicherweise nicht in der Lage waren, Word-, Excel- und PowerPoint-Dokumente zu speichern, wurde behoben. Dieses Problem betrifft Benutzer, die eine neue Datei erstellen und die Option „Als Dialog speichern“ öffnen, nachdem Sie auf das Symbol „Speichern“ geklickt oder STRG+S gedrückt haben.

- Ein Leistungsproblem unter Win7 wurde behoben, bei dem es in allen Apps ca. 4 Sekunden dauerte, bis der Katalog "Formen einfügen" auf dem Menüband angezeigt wurde.

- Ein Fehler wurde behoben, bei dem im Informationsbereich der Backstage-Ansicht keine Barrierefreiheitsinformationen angezeigt wurden.

- Verbessert die Zuverlässigkeit des Office-Updateprozesses hinsichtlich der Registrierungsintegrität.

- Es wurde ein Problem behoben, bei dem Office-Aktualisierungen möglicherweise unerwartet Dateien aus dem Office CDN anstelle der beabsichtigten Quelle heruntergeladen haben, beispielsweise eine lokale oder Netzwerkfreigabe oder einen vom Configuration Manager bereitgestellten Speicherort.

- Es wurde ein Problem behoben, bei dem Office-Update-Nachrichten in einer anderen Sprache als erwartet angezeigt wurden. In Zukunft entsprechen Office-Update-Nachrichten ordnungsgemäß der Windows-Anzeigesprache.

- Es wurde ein Problem behoben, bei dem ein Update in bestimmten Fällen nicht installiert wurde, wenn der Benutzer kein Administrator ist und das Systemkonto keine Netzwerkverbindung hatte.

- Unter bestimmten Umständen werden Office-Verknüpfungen nach einem Update möglicherweise nicht mehr angezeigt. Dieses Update erhöht die Zuverlässigkeit beim Veröffentlichen von Office-Verknüpfungen.

- Ein Problem wurde behoben, bei dem Updates in getakteten Netzwerken möglicherweise unerwartet blockiert wurden.

- Ein Bug in der Einstellung des Stichtags für ODT- und GPO-Updates wurde behoben, bei dem der relative Stichtag nur beim ersten Festlegen funktionierte. Der Fix aktiviert den relativen Stichtag für spätere Updates.

- Die Zuverlässigkeit beim Herunterladen von Office-Updates wurde verbessert, indem Downloads fortgesetzt werden, die möglicherweise zuvor unterbrochen wurden.

- Probleme im Zusammenhang mit der Anpassung der Eigenschaft "TextBox/ Form automatisch anpassen" in Drittanbieter-Plug-ins.

- Es wurde ein Problem behoben, bei dem große Strukturansichten zu einem Absturz führen konnten.

- Um die Sicherheit der Office-Kunden zu schützen, sind jetzt Microsoft Office-Updates ausschließlich mit dem SHA-2-Algorithmus signiert.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1902-january-14"></a>Version 1902: 14. Januar
*Version 1902 (Build 11328.20512)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates) aufgeführt


[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

### <a name="resolved-issues"></a>Gelöste Probleme
### <a name="excel"></a>Excel

- Es wurde ein Problem behoben, bei dem die Anpassung des Menübands beim Öffnen einer eingebetteten Arbeitsmappe nicht geladen wurde.

### <a name="outlook"></a>Outlook

- Behebt ein Problem, durch das Benutzer beim Senden einer verschlüsselten E-Mail den Fehler "Verschlüsselungsalgorithmen wird nicht unterstützt" angezeigt wurde.

### <a name="powerpoint"></a>PowerPoint

- Bei Dateien mit neuen modernen Kommentaren wird eine gelbe Warnung angezeigt, wenn sie in einer nicht unterstützten Version geöffnet werden.

### <a name="word"></a>Word

- Diese Änderung führt zu Leistungsverbesserungen beim Öffnen von Dokumenten mit Word.


[//]: # (BUGDETAILS NICHT ENTFERNEN ENDE INHALT)

## <a name="version-1808-january-14"></a>Version 1808: 14. Januar
*Version 1808 (Build 10730.20432)*

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates) aufgeführt

[//]: # (BUGDETAILS NICHT ENTFERNEN BEGINN INHALT)

> [!NOTE]
> Wenn Sie Hilfe bei einem Problem mit der Nutzung von Office benötigen, empfehlen wir, dass Sie Ihre Frage im [Microsoft Answers-Forum](https://answers.microsoft.com/) oder in der [Tech-Community](https://techcommunity.microsoft.com/) veröffentlichen, oder Sie können sich an den [Support](https://support.microsoft.com/contactus) wenden.
---
title: Versionshinweise für Releases im halbjährlichen Kanal (gezielt) im Jahr 2020
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Stellt IT-Experten Versionshinweise für Releases im halbjährlichen Kanal (gezielt) für Office 365 ProPlus im Jahr 2020 zur Verfügung.
ms.openlocfilehash: 64270156e5985b3214a0e75c56f4bdb1713125fa
ms.sourcegitcommit: 3598ca5e26109a1f99349ce3a4e70cb1d6f13e05
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 02/14/2020
ms.locfileid: "41978713"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2020"></a>Versionshinweise für Releases im halbjährlichen Kanal (gezielt) im Jahr 2020

Diese Versionshinweise enthalten Informationen zu neuen Features und nicht sicherheitsrelevante Updates, die in den halbjährlichen Updatekanal (gezielt) für Office 365 ProPlus im Jahre 2020 Visio Pro für Office 365, Project Online Desktop Client und Office 365 Business enthalten sind.

> [!NOTE]
>
> - Features (und häufig auch Fixes) werden häufig über einen Zeitraum in den halbjährlichen Updatekanal (gezielt) eingeführt. Wenn etwas, das nachstehend beschrieben ist, nicht sofort angezeigt wird, wird es in Kürze verfügbar sein. [Weitere Informationen](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - Microsoft Teams ist ab Version 1902 Teil neuer Installationen des halbjährlichen Kanals (gezielt). Teams wird vorhandenen Installationen des halbjährlichen Kanals hinzugefügt, wenn diese auf Version 1908 oder höher aktualisiert werden. Weitere Informationen finden Sie unter [Bereitstellen von Microsoft Teams mit Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install).

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

Sicherheitsupdates sind [hier](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates) aufgeführt


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
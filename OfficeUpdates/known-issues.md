---
title: Bekannte Probleme bei Office 365 ProPlus
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Enthält Informationen zu bekannten Problemen bei Office 365 ProPlus
ms.openlocfilehash: 721c9a600b079b3214fa798a39a8ed728c89de93
ms.sourcegitcommit: 7c1759a0e733ade767da00175afc1c43e8d07e3a
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/15/2019
ms.locfileid: "38640824"
---
# <a name="office-365-proplus-known-issues"></a>Bekannte Probleme bei Office 365 ProPlus

Diese Informationen zu bekannten Problemen umfassen Informationen zu nicht sicherheitsrelevanten Updates, die in den monatlichen Channel-, SACT- und SAC-Updates für Office 365 ProPlus im Jahre 2019, Visio Pro für Office 365, Project Online Desktop Client und Office 365 Business enthalten sind.

Diese Tabelle enthält eine Zusammenfassung aktueller aktiver Probleme sowie der behobenen Probleme.  Wir werden die Tabelle unten mit wichtigen Problemen, die wir untersuchen, aktualisieren.

> [!NOTE]
>- Diese Liste ist nicht vollständig.
>- Wenn Sie ein Problem in einem anderen Kanal als dem Kanal haben, der als behoben angezeigt wird, können Sie die Auflösung in Kürze erwarten. [Weitere Informationen](https://docs.microsoft.com/de-DE/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- Behobene Probleme werden auch auf den jeweiligen Kanalseiten dokumentiert.

<br>

### <a name="last-updated-november-12-2019"></a>Zuletzt aktualisiert: 12. November 2019

### <a name="excel"></a>Excel

- Kontrollkästchen-Steuerelemente konnten unter Verwendung der automatischen Anpassung der Zeilenhöhe verkleinert werden.<br><br>**Wird untersucht**: Monatlich, SACT

- Ein Leistungsproblem mit asynchronen benutzerdefinierten Funktionen, das deren synchrone Ausführung zur Folge hatte.<br><br>**Gelöst**: SACT Version 1908 (11929.20436) 

- Es könnte Benutzern gegebenenfalls nicht möglich sein, im Office 365-Format für Excel-Arbeitsmappen zu speichern<br><br>**Gelöst**: SACT Version 1908 (11929.20436)


- Problem mit langsamer Leistung beim Klicken auf die Schaltfläche „Schriftfarbe", wenn eine Datei über eine umfangreiche bedingte Formatierung verfügt.<br><br>**Gelöst**: SACT Version 1908 (11929.20436)

- Erhebliche Verbesserungen der Leistung beim Löschen von Spalten mit verbundenen Zellen.<br><br>**Wird untersucht**: SACT<br>**Gelöst**: Monatliche Version 1910 (12130.20272)

- Möglicherweise falsche Ergebnisse beim Konvertieren von Berichtsfiltern zusammen mit der restlichen PivotTable für Abfragen an tabellarische SQL-Server.<br><br>**Wird untersucht**: Monatlich

- Es wurde ein Problem mit Farben behoben, die in der Vorschau beim Einfügen von Diagrammen mithilfe von Diagrammvorlagen verwendet wurden.<br><br>**Gelöst**: Monatliche Version 1910 (12130.20272), SACT Version 1908 (11929.20436)


- Ein Problem beim Einfügen von Dateien als Objekt aus OneDrive wurde identifiziert.<br><br> **Gelöst**: Monatliche Version 1910 (12130.20272)

- Ein Problem wurde identifiziert, das beim Öffnen von in früheren Versionen von Excel erstellten Arbeitsmappen in aktuellen Versionen von Office zu Programmabstürzen führen konnte.<br><br>
**Gelöst**: Monatliche Version 1910 (12130.20272), SACT Version 1908 (11929.20436), SAC Version 1902 (11328.20468)

- Ein Problem wurde identifiziert, durch das beim Anzeigen von typisierten Werten nach dem Löschen eines Intervalls Verzögerungen verursacht wurden.<br><br>
**Gelöst**: SAC Version 1902 (11328.20468)

- Ein Problem wurde identifiziert, durch das das Auswählen einer Zelle nach dem Scrollen dazu führen konnte, dass die falsche Zelle ausgewählt wurde.<br><br>
**Wird untersucht**: SACT <br>**Gelöst**: Monatliche Version 1910 (12130.20272)

- Ein Problem wurde identifiziert, durch das Punkt-/Liniendiagramme beim Ändern der Reihensammlung möglicherweise nicht ordnungsgemäß dargestellt wurden.<br><br>
**Gelöst**: Monatliche Version 1910 (12130.20272), SACT Version 1908 (11929.20300)

### <a name="outlook"></a>Outlook

- Ein Problem wurde identifiziert, durch das bei einigen Benutzern beim Hinzufügen eines sekundären Exchange-Kontos doppelte Sonderordner angezeigt wurden.<br><br>
**Gelöst**: Monatliche Version 1910 (12130.20272), SACT Version 1908 (11929.20436)

- Ein Problem wurde identifiziert, durch das es zu einem Arbeitsspeicherverlust kommen konnte. <br><br>
**Gelöst**: Monatliche Version 1910 (12130.20272), SACT Version 1908 (11929.20388), SAC Version 1902 (11328.20468)

- Behebung eines Problems, durch das bei einigen Benutzern beim Hinzufügen eines sekundären Exchange-Kontos doppelte Sonderordner angezeigt wurden.<br><br>
**Gelöst**: Monatliche Version 1910 (12130.20272), SACT Version 1908 (11929.20436)

- Ein Problem wurde identifiziert, das manchmal zu einem Absturz führen konnte, wenn ein Benutzer eine Nachricht vom Typ "Verpasste Unterhaltung" von Skype empfängt.<br><br>
**Gelöst**: Monatliche Version 1910 (12130.20272)

- Ein Problem wurde identifiziert, durch das Benutzern beim Öffnen einer Anlage auf einem Computer, auf dem "DisableBGSave" aktiviert ist, ein generischer Fehler ""Vorgang fehlgeschlagen"" angezeigt wurde.<br><br>
**Gelöst**: Monatliche Version 1910 (12130.20272)

- Ein Problem mit cid-Links wurde identifiziert: Bilder (Outlook-E-Mail-basierte Bilder) konnten nicht umbrochen werden.<br><br>
**Gelöst**: SACT Version 1908 (11929.20436)

- Ein Problem wurde identifiziert, das beim Senden einer s/MIME-verschlüsselten E-Mail-Nachricht eine falsche Fehlermeldung verursacht hat.<br><br>**Gelöst**: Monatliche Version 1910 (12130.20272)

### <a name="powerpoint"></a>PowerPoint

- Einige Katakana-Zeichen werden in einem vertikalen Textfeld möglicherweise nicht korrekt angezeigt.<br><br>
**Wird untersucht**: Monatlich

- Ein Problem wurde identifiziert, durch das das Erstellen von Links beim Einfügen von Text mit Link verhindert wurde. <br><br>**Gelöst**: Monatliche Version 1910 (12130.20272)

- Ein Problem wurde identifiziert, durch das TextRanges nach dem Einfügen von Text in den Platzhalter für Kopfzeile/Fußzeile/Foliennummer im Folienmaster und Folienlayout möglicherweise nicht mehr funktionierten. <br><br>**Gelöst**: Monatliche Version 1910 (12130.20272)

- Ein Leistungsproblem unter Win7 wurde identifiziert, bei dem es in allen Apps ca. 4 Sekunden dauerte, bis der Katalog "Formen einfügen" auf dem Menüband angezeigt wurde.<br>
<br>**Gelöst**: Monatliche Version 1910 (12130.20272), SACT Version 1908 (11929.20396), SAC Version 1902 (11328.20468)

### <a name="project"></a>Project

- Bei einer Aufgabe mit keiner Arbeit an einem Vorgang kann der Vorgang möglicherweise nicht als erledigt gekennzeichnet werden und wird stets bei 99 % angezeigt.<br><br>
**Wird untersucht**: Monatlich<br>
**Gelöst**: SACT Version 1908 (11929.20436)

- Überlastungen werden durch einen Abgleich nicht behoben<br><br>
**Wird untersucht**: Monatlich

- Ein Problem wurde identifiziert, bei dem Benutzer beim Öffnen eines schreibgeschützten Projekts möglicherweise mehrere Meldungen erhielten.<br><br>
**Gelöst**: Monatliche Version 1910 (12130.20344), SACT Version 1908 (11929.20436)

### <a name="word"></a>Word

- Die Suche im Navigationsbereich schlägt möglicherweise fehl<br><br>
**Wird untersucht**: Monatlich

- Ein Problem beim Einfügen von Dateien als Objekt aus OneDrive wurde identifiziert.<br><br> **Gelöst**: Monatliche Version 1910 (12130.20272)

### <a name="office-suite"></a>Office-Suite
- Der Versuch, eine Datei auf einer nicht verbundenen Netzwerkfreigabe zu speichern, kann zu einem Fehler führen **Wird untersucht**: Monatlich



<br>
<br>

> [!NOTE]
> Wenn Sie Hilfe bei einem Problem mit der Nutzung von Office benötigen, empfehlen wir, dass Sie Ihre Frage im [Microsoft Answers-Forum](https://answers.microsoft.com/) oder in der [Tech-Community](https://techcommunity.microsoft.com/) veröffentlichen, oder Sie können sich an den [Support](https://support.microsoft.com/contactus) wenden.

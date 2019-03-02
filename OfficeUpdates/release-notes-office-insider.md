---
Title: "Release Notes for Office Insider" MS. Author: andrewmo Author: mikho Manager: andrewmo ms. Date: 3/1/2019 ms. Audience: Win32 fast ms. Topic: Reference ms. Service: o365-ProPlus-localization_priority: Critical ms. Collection: RelNotes_ProPlus Description: "bietet Insidern eine schnelle Benutzergruppe mit der aktuellen Liste der wichtigsten neuen Features, Fixes oder bekannten Problemen
---

# <a name="release-notes-for-office-insiders"></a>Versionshinweise für Office-Insider

Dieser Artikel enthält Anmerkungen zur Version für Insider-Builds von Word, Excel, PowerPoint, Outlook, Access und Project für Windows Desktop. Jede Woche werden interessante neue Features, wichtige Fixes und alle wichtigen Probleme hervorgehoben, über die wir Sie informieren möchten. Beachten Sie, dass wir häufig Features (und manchmal sogar Fixes) für Insider über einen bestimmten Zeitraum bereitstellen. Auf diese Weise können wir sicherstellen, dass die Dinge reibungslos funktionieren, bevor Sie das Feature für eine breitere Benutzergruppe freigeben. Wenn Sie also unten keine Beschreibung sehen, machen Sie sich keine Sorgen, dass Sie Sie schließlich erhalten.  

## <a name="february-25-2019-version-1903-build-1133020014"></a>25. Februar 2019 Version 1903 (Build 11330,20014)


## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="word"></a>Word 
- Beim Drücken von "ESC" bei Optionen wurde ein Problem mit dem Absturz behoben.
- Es wurde ein Problem mit Copy & Paste from Word to PowerPoint Online behoben.

### <a name="excel"></a>Excel
- Es wurde ein Problem behoben, bei dem beim Kopieren einer Zelle in Excel beim Öffnen des geschützten Dokuments und des bearbeitbaren Dokuments eine hohe CPU-Auslastung verursacht wurde.

### <a name="powerpoint"></a>PowerPoint
- Bei Verwendung von @Mentions in PowerPoint wurde ein Problem mit der Größe des Folien Bilds behoben.

### <a name="outlook"></a>Outlook
- Es wurde ein Problem behoben, bei dem die Outlook-Suche die ausgewählte chronologische Sortierung nicht honoriert hat.
- Es wurde ein Problem behoben, bei dem die Schaltfläche "diesen Task öffnen" nicht für bestimmte e-Mails reagierte.
- Es wurde ein Problem behoben, bei dem Outlook in den Räumen der Räume nicht gelöscht wurde, nachdem Benutzer einen verfügbaren Raum im Raum Finder ausgewählt haben.

### <a name="access"></a>Zugriff
- Bei der Bestätigung der erneuten Verknüpfung von Tabellen mit einer DataSource wurde der Eingabe aufforderungentext aktualisiert.
- Wir haben das gespeicherte Import/Export-Dialogfeld mit weißem Text auf weißem Hintergrund in dunklem Design korrigiert.
- Es wurde ein Problem behoben, bei dem Benutzer die Anzeigesteuerelement-Eigenschaft für ein Feld Ja/Nein im Tabellenentwurf auf TextBox festlegen konnten.

### <a name="project"></a>Project
- Verschiedene Leistungs-und Stabilitäts Fixes

</BR></BR>



## <a name="february-12-2019-version-1903-build-1133020014"></a>Februar 12 2019 Version 1903 (Build 11330,20014)

## <a name="whats-new"></a>Neuigkeiten:

### <a name="powerpoint"></a>PowerPoint


### <a name="morph-transition-enhancements---morph-by-name"></a>Morph Transition Enhancements-Morph by Name

Angeben der Shapes, die Sie Morphen möchten

#### <a name="getting-started"></a>Erste Schritte:

- Um Morph zu erhalten, um zwei Objekte als dasselbe Objekt zu behandeln, kann der Benutzer die Formen mit dem Auswahlbereich umbenennen.
- Dem Namen muss "!!" vorangestellt werden. (zwei Ausrufezeichen) für Morph, um das Standard Übereinstimmungsverhalten zu überschreiben, z. b. "!! Namen
- Benutzer können Shapes weiterhin mit einem beliebigen Namen umbenennen, der nicht mit "!!" beginnt, ohne sich Gedanken darüber zu machen, wie Morph funktioniert.

#### <a name="scenarios-to-try"></a>Zu verwendende Szenarien:

- Einfügen einer Form in eine Folie, sagen wir, Rechteck
- Erstellen einer neuen Folie
- Einfügen einer anderen Form in der zweiten Folie, sagen wir Dreieck
- Öffnen Sie SelectionPane, und benennen Sie das Rechteck in Folie 1 in "!! Shape ", und benennen Sie das Dreieck in Folie 2 in"!! Form
- Anwenden von Morph auf der zweiten Folie

</BR>

### <a name="morph-transition-enhancements---smartart"></a>Verbesserungen beim Morph-Übergang – SmartArt

SmartArt-Morphin mit glatteren Übergängen

#### <a name="getting-started"></a>Erste Schritte:

Verwenden Sie Morph auf die gleiche Weise wie bei SmartArt.

#### <a name="scenarios-to-try"></a>Zu verwendende Szenarien:

- Einfügen einer SmartArt in eine Folie
- Duplizieren der Folie
- Größe/ändern/verschieben der SmartArt auf der duplizierten Folie
- Anwenden von Morph auf die duplizierte Folie

</BR>

### <a name="morph-transition-enhancements---tables"></a>Erweiterungen für Morph-Übergänge-Tabellen

Tabellen Morphen mit glatteren Übergängen

#### <a name="getting-started"></a>Erste Schritte:
Verwenden Sie Morph auf dieselbe Weise wie Tabellen.

#### <a name="scenarios-to-try"></a>Zu verwendende Szenarien:

- Einfügen einer Tabelle in eine Folie
- Duplizieren der Folie
- Größe/ändern/verschieben der Tabelle auf der duplizierten Folie
- Anwenden von Morph auf die duplizierte Folie

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a>Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio

### <a name="seamlessly-switch-between-accounts"></a>Nahtloses Wechseln zwischen Konten

Der neue Kontomanager zeigt alle Arbeits-und persönlichen Konten an einem Ort an und steuert den Wechsel zwischen diesen. Diese aktualisierte Benutzeroberfläche macht deutlich, wie Sie angemeldet sind, und jetzt können Sie zwischen Arbeits-und persönlichen Konten wechseln, ohne zuerst abmelden oder komplexe Dialogfelder bearbeiten zu müssen.


![MeMock. png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a>Zu verwendende Szenarien:
- Wechseln zwischen Konten
- Hinzufügen eines neuen Kontos [Hinweis: möglicherweise möchten Sie zunächst zu Datei | Konto | Verbundene Dienste und Entfernen von persönlichen Diensten, die mit Arbeits Konten verbunden sind oder umgekehrt]
- AbMelden von einem Konto
</BR>

## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="word"></a>Word 
- Es wurde ein Problem mit der Kontext Vorschau für Tabellen & Bilder behoben.

### <a name="excel"></a>Excel
- Es wurde ein Problem behoben, bei dem Text im AutoFilter-Suchfeld weiß ist, in schwarz.
- Wir haben ein Benutzeroberflächen Problem mit dem neuen Office-Add-in behoben.

### <a name="powerpoint"></a>PowerPoint
- Es wurde ein Problem behoben, bei dem bei der Präsentation von Diashows auf Laptops oder Tablets automatisch eine Erweiterung angezeigt wurde.

### <a name="outlook"></a>Outlook
- Es wurde ein Problem mit der Schaltfläche "an OneNote senden" behoben.

### <a name="access"></a>Zugriff
- Verschiedene Leistungs-und Stabilitäts Fixes

### <a name="project"></a>Project
- Verschiedene Leistungs-und Stabilitäts Fixes


</BR></BR>
## <a name="february-9-2019-version-1903-build-1133020014"></a>Februar 9 2019 Version 1903 (Build 11330,20014)


## <a name="notable-fixes"></a>Wichtige Fixes:

### <a name="word"></a>Word 
- Es wurde ein Problem behoben, bei dem einige angepasste Formatvorlagen nicht auf Word Online angewendet werden konnten.
- Wir haben Probleme mit der Kontext Vorschau mit Rich-Objekten in Word behoben.
- Es wurde ein Problem behoben, bei dem das Einfügen von Listen zu einem Absturz von Word führen würde.

### <a name="excel"></a>Excel
- Es wurde ein Problem behoben, bei dem angefügte Leerzeichen nach Zahlenformaten nicht mehr angezeigt werden, wenn kein Währungssymbol vorhanden ist.
- Es wurde ein Problem mit der automatischen Ermittlung für Aktien behoben.

### <a name="powerpoint"></a>PowerPoint
- Verschiedene Leistungs-und Stabilitäts Fixes

### <a name="outlook"></a>Outlook
- Verschiedene Leistungs-und Stabilitäts Fixes

### <a name="access"></a>Zugriff
- Verschiedene Leistungs-und Stabilitäts Fixes

### <a name="project"></a>Project
- Verschiedene Leistungs-und Stabilitäts Fixes

</BR></BR>


## <a name="january-30-2019-version-1902-build-1132620000"></a>Januar 2019 Version 1902 (Build 11326,20000)


## <a name="notable-fixes"></a>Wichtige Fixes

### <a name="word"></a>Word 
- Es wurde ein Problem behoben, bei dem Zellen in einer eingebetteten Excel-Tabelle geändert wurden.
- Es wurde ein Problem mit Copy/Paste von Formen in einem Zeichenbereich behoben.

### <a name="excel"></a>Excel
- Es wurde ein Problem beim Öffnen von Dateien aus der Excel Web App behoben.
- Es wurde ein Problem behoben, bei dem eine CSV-Datei als gespeichert wurde. XLSX fehlgeschlagen aufgrund der Größe des Datei namens
- Wir haben das Kontextmenü festgelegt, um die Optionen für das Kontextmenü anzuzeigen.

### <a name="powerpoint"></a>PowerPoint
- Wir haben eine Ausgabe festgelegt, bei der Benutzer die Tastenkombination STRG + ALT + 7/STRG + ALT + 8 nicht verwenden konnten, um eckige Klammern einzugeben.
- Es wurde ein Problem behoben, bei dem das Einfügen eines lokalen Videos in die PPT den Festplattenspeicher "C" reduziert.
- Wir haben die Schaltfläche in Microsoft Stream veröffentlichen festgelegt, die einigen Benutzern nicht angezeigt wurde.

### <a name="outlook"></a>Outlook
- Es wurde ein Problem behoben, bei dem die Vorgangsansicht im Kalender den Aufgabenbetreff nicht korrekt angezeigt hat.

### <a name="access"></a>Zugriff
- Es wurde ein Skalierungsproblem mit Diagrammen behoben.

### <a name="project"></a>Project
- Verschiedene Leistungs-und Stabilitäts Fixes

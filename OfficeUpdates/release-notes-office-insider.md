---
<span data-ttu-id="68e74-101">Title: "Release Notes for Office Insider" MS. Author: andrewmo Author: mikho Manager: andrewmo ms. Date: 2/15/2019 ms. Audience: Win32 fast ms. Topic: Reference ms. Service: o365-ProPlus-localization_priority: Critical ms. Collection: RelNotes_ProPlus Description: "bietet Insidern eine schnelle Benutzergruppe mit der aktuellen Liste der wichtigsten neuen Features, Fixes oder bekannten Problemen</span><span class="sxs-lookup"><span data-stu-id="68e74-101">title: "Release Notes for Office Insiders" ms.author: andrewmo author: mikho manager: andrewmo ms.date: 2/15/2019 ms.audience: Win32 Fast ms.topic: reference ms.service: o365-proplus- localization_priority: Critical ms.collection: RelNotes_ProPlus description: "Provides Insiders Fast audience with the latest list of key new features, fixes or known issues</span></span>
---

# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="68e74-102">Versionshinweise für Office-Insider</span><span class="sxs-lookup"><span data-stu-id="68e74-102">Release Notes for Office Insiders</span></span>

<span data-ttu-id="68e74-p101">Dieser Artikel enthält Anmerkungen zur Version für Insider-Builds von Word, Excel, PowerPoint, Outlook, Access und Project für Windows Desktop. Jede Woche werden interessante neue Features, wichtige Fixes und alle wichtigen Probleme hervorgehoben, über die wir Sie informieren möchten. Beachten Sie, dass wir häufig Features (und manchmal sogar Fixes) für Insider über einen bestimmten Zeitraum bereitstellen. Auf diese Weise können wir sicherstellen, dass die Dinge reibungslos funktionieren, bevor Sie das Feature für eine breitere Benutzergruppe freigeben. Wenn Sie also unten keine Beschreibung sehen, machen Sie sich keine Sorgen, dass Sie Sie schließlich erhalten.</span><span class="sxs-lookup"><span data-stu-id="68e74-p101">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop. Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about. Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time. This allows us to ensure that things are working smoothly before releasing the feature to a wider audience. So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

## <a name="february-12-2019-version-1902-build-1133020014"></a><span data-ttu-id="68e74-108">Februar 12 2019 Version 1902 (Build 11330,20014)</span><span class="sxs-lookup"><span data-stu-id="68e74-108">February 12 2019 Version 1902 (build 11330.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="68e74-109">Neuigkeiten:</span><span class="sxs-lookup"><span data-stu-id="68e74-109">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="68e74-110">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="68e74-110">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="68e74-111">Morph Transition Enhancements-Morph by Name</span><span class="sxs-lookup"><span data-stu-id="68e74-111">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="68e74-112">Angeben der Shapes, die Sie Morphen möchten</span><span class="sxs-lookup"><span data-stu-id="68e74-112">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="68e74-113">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="68e74-113">Getting Started:</span></span>

- <span data-ttu-id="68e74-114">Um Morph zu erhalten, um zwei Objekte als dasselbe Objekt zu behandeln, kann der Benutzer die Formen mit dem Auswahlbereich umbenennen.</span><span class="sxs-lookup"><span data-stu-id="68e74-114">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="68e74-p102">Dem Namen muss "!!" vorangestellt werden. (zwei Ausrufezeichen) für Morph, um das Standard Übereinstimmungsverhalten zu überschreiben, z. b. "!! Namen</span><span class="sxs-lookup"><span data-stu-id="68e74-p102">The name must be prefaced with “!!” (two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="68e74-p103">Benutzer können Shapes weiterhin mit einem beliebigen Namen umbenennen, der nicht mit "!!" beginnt, ohne sich Gedanken darüber zu machen, wie Morph funktioniert.</span><span class="sxs-lookup"><span data-stu-id="68e74-p103">Users can continue to rename shapes with any name that doesn’t start with “!!” without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="68e74-119">Zu verwendende Szenarien:</span><span class="sxs-lookup"><span data-stu-id="68e74-119">Scenarios to Try:</span></span>

- <span data-ttu-id="68e74-120">Einfügen einer Form in eine Folie, sagen wir, Rechteck</span><span class="sxs-lookup"><span data-stu-id="68e74-120">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="68e74-121">Erstellen einer neuen Folie</span><span class="sxs-lookup"><span data-stu-id="68e74-121">Create a new slide</span></span>
- <span data-ttu-id="68e74-122">Einfügen einer anderen Form in der zweiten Folie, sagen wir Dreieck</span><span class="sxs-lookup"><span data-stu-id="68e74-122">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="68e74-123">Öffnen Sie SelectionPane, und benennen Sie das Rechteck in Folie 1 in "!! Shape ", und benennen Sie das Dreieck in Folie 2 in"!! Form</span><span class="sxs-lookup"><span data-stu-id="68e74-123">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="68e74-124">Anwenden von Morph auf der zweiten Folie</span><span class="sxs-lookup"><span data-stu-id="68e74-124">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="68e74-125">Verbesserungen beim Morph-Übergang – SmartArt</span><span class="sxs-lookup"><span data-stu-id="68e74-125">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="68e74-126">SmartArt-Morphin mit glatteren Übergängen</span><span class="sxs-lookup"><span data-stu-id="68e74-126">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="68e74-127">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="68e74-127">Getting Started:</span></span>

<span data-ttu-id="68e74-128">Verwenden Sie Morph auf die gleiche Weise wie bei SmartArt.</span><span class="sxs-lookup"><span data-stu-id="68e74-128">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="68e74-129">Zu verwendende Szenarien:</span><span class="sxs-lookup"><span data-stu-id="68e74-129">Scenarios to Try:</span></span>

- <span data-ttu-id="68e74-130">Einfügen einer SmartArt in eine Folie</span><span class="sxs-lookup"><span data-stu-id="68e74-130">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="68e74-131">Duplizieren der Folie</span><span class="sxs-lookup"><span data-stu-id="68e74-131">Duplicate the Slide</span></span>
- <span data-ttu-id="68e74-132">Größe/ändern/verschieben der SmartArt auf der duplizierten Folie</span><span class="sxs-lookup"><span data-stu-id="68e74-132">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="68e74-133">Anwenden von Morph auf die duplizierte Folie</span><span class="sxs-lookup"><span data-stu-id="68e74-133">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="68e74-134">Erweiterungen für Morph-Übergänge-Tabellen</span><span class="sxs-lookup"><span data-stu-id="68e74-134">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="68e74-135">Tabellen Morphen mit glatteren Übergängen</span><span class="sxs-lookup"><span data-stu-id="68e74-135">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="68e74-136">Erste Schritte:</span><span class="sxs-lookup"><span data-stu-id="68e74-136">Getting Started:</span></span>
<span data-ttu-id="68e74-137">Verwenden Sie Morph auf dieselbe Weise wie Tabellen.</span><span class="sxs-lookup"><span data-stu-id="68e74-137">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="68e74-138">Zu verwendende Szenarien:</span><span class="sxs-lookup"><span data-stu-id="68e74-138">Scenarios to Try:</span></span>

- <span data-ttu-id="68e74-139">Einfügen einer Tabelle in eine Folie</span><span class="sxs-lookup"><span data-stu-id="68e74-139">Insert a Table in a slide</span></span>
- <span data-ttu-id="68e74-140">Duplizieren der Folie</span><span class="sxs-lookup"><span data-stu-id="68e74-140">Duplicate the slide</span></span>
- <span data-ttu-id="68e74-141">Größe/ändern/verschieben der Tabelle auf der duplizierten Folie</span><span class="sxs-lookup"><span data-stu-id="68e74-141">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="68e74-142">Anwenden von Morph auf die duplizierte Folie</span><span class="sxs-lookup"><span data-stu-id="68e74-142">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="68e74-143">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span><span class="sxs-lookup"><span data-stu-id="68e74-143">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="68e74-144">Nahtloses Wechseln zwischen Konten</span><span class="sxs-lookup"><span data-stu-id="68e74-144">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="68e74-p104">Der neue Kontomanager zeigt alle Arbeits-und persönlichen Konten an einem Ort an und steuert den Wechsel zwischen diesen. Diese aktualisierte Benutzeroberfläche macht deutlich, wie Sie angemeldet sind, und jetzt können Sie zwischen Arbeits-und persönlichen Konten wechseln, ohne zuerst abmelden oder komplexe Dialogfelder bearbeiten zu müssen.</span><span class="sxs-lookup"><span data-stu-id="68e74-p104">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them. This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>



#### <a name="scenarios-to-try"></a><span data-ttu-id="68e74-147">Zu verwendende Szenarien:</span><span class="sxs-lookup"><span data-stu-id="68e74-147">Scenarios to Try:</span></span>
- <span data-ttu-id="68e74-148">Wechseln zwischen Konten</span><span class="sxs-lookup"><span data-stu-id="68e74-148">Switch between accounts</span></span>
- <span data-ttu-id="68e74-149">Hinzufügen eines neuen Kontos [Hinweis: möglicherweise möchten Sie zunächst zu Datei | Konto | Verbundene Dienste und Entfernen von persönlichen Diensten, die mit Arbeits Konten verbunden sind oder umgekehrt]</span><span class="sxs-lookup"><span data-stu-id="68e74-149">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="68e74-150">AbMelden von einem Konto</span><span class="sxs-lookup"><span data-stu-id="68e74-150">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="68e74-151">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="68e74-151">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="68e74-152">Word</span><span class="sxs-lookup"><span data-stu-id="68e74-152">Word</span></span> 
- <span data-ttu-id="68e74-153">Es wurde ein Problem mit der Kontext Vorschau für Tabellen & Bilder behoben.</span><span class="sxs-lookup"><span data-stu-id="68e74-153">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="68e74-154">Excel</span><span class="sxs-lookup"><span data-stu-id="68e74-154">Excel</span></span>
- <span data-ttu-id="68e74-155">Es wurde ein Problem behoben, bei dem Text im AutoFilter-Suchfeld weiß ist, in schwarz.</span><span class="sxs-lookup"><span data-stu-id="68e74-155">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="68e74-156">Wir haben ein Benutzeroberflächen Problem mit dem neuen Office-Add-in behoben.</span><span class="sxs-lookup"><span data-stu-id="68e74-156">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="68e74-157">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="68e74-157">PowerPoint</span></span>
- <span data-ttu-id="68e74-158">Es wurde ein Problem behoben, bei dem bei der Präsentation von Diashows auf Laptops oder Tablets automatisch eine Erweiterung angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="68e74-158">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="68e74-159">Outlook</span><span class="sxs-lookup"><span data-stu-id="68e74-159">Outlook</span></span>
- <span data-ttu-id="68e74-160">Es wurde ein Problem mit der Schaltfläche "an OneNote senden" behoben.</span><span class="sxs-lookup"><span data-stu-id="68e74-160">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="68e74-161">Zugriff</span><span class="sxs-lookup"><span data-stu-id="68e74-161">Access</span></span>
- <span data-ttu-id="68e74-162">Verschiedene Leistungs-und Stabilitäts Fixes</span><span class="sxs-lookup"><span data-stu-id="68e74-162">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="68e74-163">Project</span><span class="sxs-lookup"><span data-stu-id="68e74-163">Project</span></span>
- <span data-ttu-id="68e74-164">Verschiedene Leistungs-und Stabilitäts Fixes</span><span class="sxs-lookup"><span data-stu-id="68e74-164">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-9-2019-version-1902-build-1133020014"></a><span data-ttu-id="68e74-165">Februar 9 2019 Version 1902 (Build 11330,20014)</span><span class="sxs-lookup"><span data-stu-id="68e74-165">February 9 2019 Version 1902 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="68e74-166">Wichtige Fixes:</span><span class="sxs-lookup"><span data-stu-id="68e74-166">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="68e74-167">Word</span><span class="sxs-lookup"><span data-stu-id="68e74-167">Word</span></span> 
- <span data-ttu-id="68e74-168">Es wurde ein Problem behoben, bei dem einige angepasste Formatvorlagen nicht auf Word Online angewendet werden konnten.</span><span class="sxs-lookup"><span data-stu-id="68e74-168">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="68e74-169">Wir haben Probleme mit der Kontext Vorschau mit Rich-Objekten in Word behoben.</span><span class="sxs-lookup"><span data-stu-id="68e74-169">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="68e74-170">Es wurde ein Problem behoben, bei dem das Einfügen von Listen zu einem Absturz von Word führen würde.</span><span class="sxs-lookup"><span data-stu-id="68e74-170">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="68e74-171">Excel</span><span class="sxs-lookup"><span data-stu-id="68e74-171">Excel</span></span>
- <span data-ttu-id="68e74-172">Es wurde ein Problem behoben, bei dem angefügte Leerzeichen nach Zahlenformaten nicht mehr angezeigt werden, wenn kein Währungssymbol vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="68e74-172">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="68e74-173">Es wurde ein Problem mit der automatischen Ermittlung für Aktien behoben.</span><span class="sxs-lookup"><span data-stu-id="68e74-173">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="68e74-174">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="68e74-174">PowerPoint</span></span>
- <span data-ttu-id="68e74-175">Verschiedene Leistungs-und Stabilitäts Fixes</span><span class="sxs-lookup"><span data-stu-id="68e74-175">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="68e74-176">Outlook</span><span class="sxs-lookup"><span data-stu-id="68e74-176">Outlook</span></span>
- <span data-ttu-id="68e74-177">Verschiedene Leistungs-und Stabilitäts Fixes</span><span class="sxs-lookup"><span data-stu-id="68e74-177">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="68e74-178">Zugriff</span><span class="sxs-lookup"><span data-stu-id="68e74-178">Access</span></span>
- <span data-ttu-id="68e74-179">Verschiedene Leistungs-und Stabilitäts Fixes</span><span class="sxs-lookup"><span data-stu-id="68e74-179">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="68e74-180">Project</span><span class="sxs-lookup"><span data-stu-id="68e74-180">Project</span></span>
- <span data-ttu-id="68e74-181">Verschiedene Leistungs-und Stabilitäts Fixes</span><span class="sxs-lookup"><span data-stu-id="68e74-181">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="january-30-2019-version-1902-build-1132620000"></a><span data-ttu-id="68e74-182">Januar 2019 Version 1902 (Build 11326,20000)</span><span class="sxs-lookup"><span data-stu-id="68e74-182">January 30, 2019 Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="68e74-183">Wichtige Fixes</span><span class="sxs-lookup"><span data-stu-id="68e74-183">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="68e74-184">Word</span><span class="sxs-lookup"><span data-stu-id="68e74-184">Word</span></span> 
- <span data-ttu-id="68e74-185">Es wurde ein Problem behoben, bei dem Zellen in einer eingebetteten Excel-Tabelle geändert wurden.</span><span class="sxs-lookup"><span data-stu-id="68e74-185">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="68e74-186">Es wurde ein Problem mit Copy/Paste von Formen in einem Zeichenbereich behoben.</span><span class="sxs-lookup"><span data-stu-id="68e74-186">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="68e74-187">Excel</span><span class="sxs-lookup"><span data-stu-id="68e74-187">Excel</span></span>
- <span data-ttu-id="68e74-188">Es wurde ein Problem beim Öffnen von Dateien aus der Excel Web App behoben.</span><span class="sxs-lookup"><span data-stu-id="68e74-188">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="68e74-189">Es wurde ein Problem behoben, bei dem eine CSV-Datei als gespeichert wurde. XLSX fehlgeschlagen aufgrund der Größe des Datei namens</span><span class="sxs-lookup"><span data-stu-id="68e74-189">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="68e74-190">Wir haben das Kontextmenü festgelegt, um die Optionen für das Kontextmenü anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="68e74-190">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="68e74-191">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="68e74-191">PowerPoint</span></span>
- <span data-ttu-id="68e74-192">Wir haben eine Ausgabe festgelegt, bei der Benutzer die Tastenkombination STRG + ALT + 7/STRG + ALT + 8 nicht verwenden konnten, um eckige Klammern einzugeben.</span><span class="sxs-lookup"><span data-stu-id="68e74-192">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="68e74-193">Es wurde ein Problem behoben, bei dem das Einfügen eines lokalen Videos in die PPT den Festplattenspeicher "C" reduziert.</span><span class="sxs-lookup"><span data-stu-id="68e74-193">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="68e74-194">Wir haben die Schaltfläche in Microsoft Stream veröffentlichen festgelegt, die einigen Benutzern nicht angezeigt wurde.</span><span class="sxs-lookup"><span data-stu-id="68e74-194">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="68e74-195">Outlook</span><span class="sxs-lookup"><span data-stu-id="68e74-195">Outlook</span></span>
- <span data-ttu-id="68e74-196">Es wurde ein Problem behoben, bei dem die Vorgangsansicht im Kalender den Aufgabenbetreff nicht korrekt angezeigt hat.</span><span class="sxs-lookup"><span data-stu-id="68e74-196">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="68e74-197">Zugriff</span><span class="sxs-lookup"><span data-stu-id="68e74-197">Access</span></span>
- <span data-ttu-id="68e74-198">Es wurde ein Skalierungsproblem mit Diagrammen behoben.</span><span class="sxs-lookup"><span data-stu-id="68e74-198">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="68e74-199">Project</span><span class="sxs-lookup"><span data-stu-id="68e74-199">Project</span></span>
- <span data-ttu-id="68e74-200">Verschiedene Leistungs-und Stabilitäts Fixes</span><span class="sxs-lookup"><span data-stu-id="68e74-200">Various performance and stability fixes</span></span>

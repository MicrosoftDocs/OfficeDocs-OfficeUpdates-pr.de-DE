---
title: Versionsverlauf für das Office-Bereitstellungstool (ODT)
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: Stellt IT-Experten einen Versionsverlauf für das Office-Bereitstellungstool (ODT) zur Verfügung
ms.openlocfilehash: 046054dfb781c3cd19ca6505e5ae5f2f362f6a86
ms.sourcegitcommit: 04f3aa30703f4f1cf89721853a7c052fcca2b97f
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/24/2021
ms.locfileid: "51169963"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="bf739-103">Versionsverlauf für das Office-Bereitstellungstool</span><span class="sxs-lookup"><span data-stu-id="bf739-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="bf739-104">Das Office-Bereitstellungstool (ODT) ist ein Befehlszeilentool, mit dem Sie Office Klick-und-Los-Versionen wie etwa Microsoft 365-Apps auf Ihre Clientcomputer herunterladen und dort bereitstellen können.</span><span class="sxs-lookup"><span data-stu-id="bf739-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="bf739-105">Das ODT bietet Ihnen mehr Kontrolle über eine Office-Installation.</span><span class="sxs-lookup"><span data-stu-id="bf739-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="bf739-106">Sie können definieren, welche Produkte und Sprachen installiert werden, wie diese Produkte aktualisiert werden sollen und ob den Benutzern der Installationsvorgang angezeigt werden soll.</span><span class="sxs-lookup"><span data-stu-id="bf739-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="bf739-107">Informationen zur Verwendung des ODT finden Sie unter [Übersicht über das Office-Bereitstellungstool](/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="bf739-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="bf739-108">**Unterstützte Betriebssystem**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="bf739-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="bf739-109">**Installationsanweisungen**: Laden Sie die selbst entpackende ausführbare Datei herunter, die die ausführbare Datei (setup.exe) und eine Beispielkonfigurationsdatei (configuration.xml) für das Office-Bereitstellungstool enthält, und führen Sie sie aus.</span><span class="sxs-lookup"><span data-stu-id="bf739-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

<span data-ttu-id="bf739-110">[Laden Sie das Office-Bereitstellungstool herunter](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).</span><span class="sxs-lookup"><span data-stu-id="bf739-110">[Download Office Deployment Tool](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)</span></span>


## <a name="march-23-2021"></a><span data-ttu-id="bf739-111">23. März 2021</span><span class="sxs-lookup"><span data-stu-id="bf739-111">March 23, 2021</span></span>
<span data-ttu-id="bf739-112">Version 16.0.13801.20360 (setup.exe, version 16.0.13801.20340)</span><span class="sxs-lookup"><span data-stu-id="bf739-112">Version 16.0.13801.20360 (setup.exe version 16.0.13801.20340)</span></span>
- <span data-ttu-id="bf739-113">Änderungen zur Unterstützung anstehender Office-Produkt-Releases</span><span class="sxs-lookup"><span data-stu-id="bf739-113">Changes to support upcoming Office product releases</span></span>
- <span data-ttu-id="bf739-114">Zuverlässigkeitsfixes für ARM-Plattformen</span><span class="sxs-lookup"><span data-stu-id="bf739-114">Reliability fixes for ARM platforms</span></span>


## <a name="february-25-2021"></a><span data-ttu-id="bf739-115">25. Februar 2021</span><span class="sxs-lookup"><span data-stu-id="bf739-115">February 25, 2021</span></span>
<span data-ttu-id="bf739-116">Version 16.0.13628.20476 (setup.exe, Version 16.0.13628.20462)</span><span class="sxs-lookup"><span data-stu-id="bf739-116">Version 16.0.13628.20476 (setup.exe version 16.0.13628.20462)</span></span>
- <span data-ttu-id="bf739-117">Ein Problem wurde behoben, bei dem configuration.xml-Dateien, die mehrere Dutzend Sprachen angeben, nicht validiert werden konnten</span><span class="sxs-lookup"><span data-stu-id="bf739-117">Fixed an issue where configuration.xml files specifying several dozen languages was failing to validate</span></span>
- <span data-ttu-id="bf739-118">Ein Problem wurde behoben, bei dem die Eigenschaft FORCEAPPSHUTDOWN in MigrateArch-Szenarien nicht beachtet wurde</span><span class="sxs-lookup"><span data-stu-id="bf739-118">Fixed an issue where the FORCEAPPSHUTDOWN property was not being respected in MigrateArch scenarios</span></span>
- <span data-ttu-id="bf739-119">Ein Problem wurde behoben, bei dem die Angabe von 2 oder mehr PIDKEY-Attributen in „configuration.xml“ zu Fehlern bei der Installation der PIDKeys führte</span><span class="sxs-lookup"><span data-stu-id="bf739-119">Fixed an issue where specifying 2 or more PIDKEY attributes in configuration.xml failed to install the PIDKeys</span></span>



## <a name="february-9-2021"></a><span data-ttu-id="bf739-120">9. Februar 2021</span><span class="sxs-lookup"><span data-stu-id="bf739-120">February 9, 2021</span></span>
<span data-ttu-id="bf739-121">Version 16.0.13628.20274 (setup.exe Version 16.0.13628.20246)</span><span class="sxs-lookup"><span data-stu-id="bf739-121">Version 16.0.13628.20274 (setup.exe version 16.0.13628.20246)</span></span>
- <span data-ttu-id="bf739-122">Es wurde eine Prüfung hinzugefügt, die vor nicht unterstützten Installationen unter Windows 8.0 warnt und diese verhindert</span><span class="sxs-lookup"><span data-stu-id="bf739-122">Added validation to warn about and prevent unsupported installations on Windows 8.0</span></span>
- <span data-ttu-id="bf739-123">Zuverlässigkeitskorrekturen für ARM64-Geräte</span><span class="sxs-lookup"><span data-stu-id="bf739-123">Reliability fixes for ARM64 devices</span></span>


## <a name="january-12-2021"></a><span data-ttu-id="bf739-124">12. Januar 2021</span><span class="sxs-lookup"><span data-stu-id="bf739-124">January 12, 2021</span></span>
<span data-ttu-id="bf739-125">Version 16.0.13530.20376 (setup.exe Version 16.0.13530.20334)</span><span class="sxs-lookup"><span data-stu-id="bf739-125">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span></span>
- <span data-ttu-id="bf739-126">Ein Problem wurde behoben, bei dem eine beschädigte oder nicht standardmäßige Produktregistrierung zum Fehlschlagen von RemoveMSI-Vorgängen führen konnte.</span><span class="sxs-lookup"><span data-stu-id="bf739-126">Fixed an issue where corrupted or non-standard product registration could cause RemoveMSI operations to fail</span></span>

## <a name="december-21-2020"></a><span data-ttu-id="bf739-127">21. Dezember 2020</span><span class="sxs-lookup"><span data-stu-id="bf739-127">December 21, 2020</span></span>
<span data-ttu-id="bf739-128">Version 16.0.13426.20370 (setup.exe Version 16.0.13426.20352)</span><span class="sxs-lookup"><span data-stu-id="bf739-128">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span></span>
- <span data-ttu-id="bf739-129">Es wurde ein Problem behoben, bei dem die lokalen Quellinstallationen von ProofingTools aus dem PerpetualVL2019-Kanal fehlschlugen</span><span class="sxs-lookup"><span data-stu-id="bf739-129">Fixed an issue where local source installations of ProofingTools from the PerpetualVL2019 channel were failing</span></span>
- <span data-ttu-id="bf739-130">Es wurde ein Problem behoben, damit sichergestellt wird, dass der Klick-und-Los-Client eine Selbstaktualisierung versucht, wenn einer vorhandenen Installation zusätzliche Produkte in nicht vollständigen Office-Sprachen hinzugefügt werden</span><span class="sxs-lookup"><span data-stu-id="bf739-130">Fixed an issue to ensure that the Click-To-Run client attempts a self-update when adding additional products in non-full Office languages to an existing installation</span></span>


## <a name="december-8-2020"></a><span data-ttu-id="bf739-131">8. Dezember 2020</span><span class="sxs-lookup"><span data-stu-id="bf739-131">December 8, 2020</span></span>
<span data-ttu-id="bf739-132">Version 16.0.13426.20308 (setup.exe-Version 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="bf739-132">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="bf739-133">Es wurde ein Problem behoben, bei dem im Download-Modus Downloads aus dem Perpetual 2019-Kanal blockiert wurden, wenn auf dem Gerät ein Office-Produkt installiert war, das nicht aus einem Perpetual 2019-Kanal stammte.</span><span class="sxs-lookup"><span data-stu-id="bf739-133">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="bf739-134">Es wurde ein Problem behoben, bei dem die Migration einer Architektur bei einer im Download-Modus erstellten lokalen Quelle fehlschlug, in dem eine bestimmte Version in der XLM-Konfiguration angegeben war.</span><span class="sxs-lookup"><span data-stu-id="bf739-134">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="bf739-135">23. November 2020</span><span class="sxs-lookup"><span data-stu-id="bf739-135">November 23, 2020</span></span>
<span data-ttu-id="bf739-136">Version 16.0.13328.20420 (setup.exe-Version 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="bf739-136">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="bf739-137">Es wurde ein Problem behoben, bei dem Korrekturhilfen nicht im /download-Modus heruntergeladen wurden</span><span class="sxs-lookup"><span data-stu-id="bf739-137">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="bf739-138">Es wurde ein Problem behoben, bei dem der /download-Modus fehlschlug, wenn er in einem deautorisierten Benutzerkontext ausgeführt wurde</span><span class="sxs-lookup"><span data-stu-id="bf739-138">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="bf739-139">Es wurde ein Problem behoben, bei dem die Angabe eines Versionsattributs in der XML-Konfiguration zu einem unvollständigen Download im /download-Modus führte</span><span class="sxs-lookup"><span data-stu-id="bf739-139">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="bf739-140">Es wurde ein Problem behoben, bei dem das Office-Bereitstellungstool beim Extrahieren nicht „setup.exe“ benannt wurde</span><span class="sxs-lookup"><span data-stu-id="bf739-140">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="bf739-141">Es wurde ein Problem behoben, das bei der Priorisierung der Installationsquelle auftrat, wenn ein Channel-Attribut in der XML-Konfiguration bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="bf739-141">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="bf739-142">10. November 2020</span><span class="sxs-lookup"><span data-stu-id="bf739-142">November 10, 2020</span></span>
<span data-ttu-id="bf739-143">Version 16.0.13328.20356 (setupODT.exe-Version 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="bf739-143">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="bf739-144">Verbesserungen bei Zuverlässigkeit und Resilienz</span><span class="sxs-lookup"><span data-stu-id="bf739-144">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="bf739-145">Um Verwirrung zu vermeiden und Setupfehler einfacher diagnostizieren zu können, wird das ODT jetzt standardmäßig als "setupODT.exe" bezeichnet.</span><span class="sxs-lookup"><span data-stu-id="bf739-145">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="bf739-146">29. Oktober 2020</span><span class="sxs-lookup"><span data-stu-id="bf739-146">October 29, 2020</span></span>
<span data-ttu-id="bf739-147">Version 16.0.13328.20292 (setup.exe Version 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="bf739-147">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="bf739-148">Behebt ein Problem, bei dem bestimmte Office 2007-Produkte die Installation bei Verwendung von RemoveMSI unerwartet blockieren können.</span><span class="sxs-lookup"><span data-stu-id="bf739-148">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="bf739-149">14. Oktober 2020</span><span class="sxs-lookup"><span data-stu-id="bf739-149">October 14, 2020</span></span>
<span data-ttu-id="bf739-150">Version 16.0.13231.20368 (setup.exe-Version 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="bf739-150">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="bf739-151">Alle Produkte verwenden jetzt standardmäßig den monatlichen Kanal, wenn kein Kanal angegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="bf739-151">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="bf739-152">Verbesserte Sicherheit beim Ausführen von ODT aus einem Verzeichnis, das andere DLL-Dateien enthält.</span><span class="sxs-lookup"><span data-stu-id="bf739-152">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="bf739-153">Verbesserungen bei Zuverlässigkeit und Resilienz</span><span class="sxs-lookup"><span data-stu-id="bf739-153">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="bf739-154">9. Juni 2020</span><span class="sxs-lookup"><span data-stu-id="bf739-154">June 9, 2020</span></span>

<span data-ttu-id="bf739-155">Version 16.0.12827.20268 (setup.exe-Version 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="bf739-155">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="bf739-156">Der aktuelle Kanal ist jetzt der Standardkanal, wenn kein Kanal angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="bf739-156">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="bf739-157">Unterstützung für den monatlichen Enterprise-Kanal hinzugefügt</span><span class="sxs-lookup"><span data-stu-id="bf739-157">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="bf739-158">Unterstützung für neue Kanalnamen hinzugefügt</span><span class="sxs-lookup"><span data-stu-id="bf739-158">Added support for new channel names</span></span>
- <span data-ttu-id="bf739-159">Zusätzliche Resilienz-Features, um die Installation fortzusetzen, wenn möglich, auch wenn einige Sprachressourcen nicht verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="bf739-159">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="bf739-160">Erweiterte MSIRemove-Funktionen zum Entfernen von Office 2007-Produkten</span><span class="sxs-lookup"><span data-stu-id="bf739-160">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="bf739-161">Erweiterte MSIRemove-Funktionen, um Access-Datenbankmodul zu entfernen</span><span class="sxs-lookup"><span data-stu-id="bf739-161">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="bf739-162">15. April 2020</span><span class="sxs-lookup"><span data-stu-id="bf739-162">April 15, 2020</span></span>

<span data-ttu-id="bf739-163">Version 16.0.12624.20320 (setup.exe-Version 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="bf739-163">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="bf739-164">Bietet Unterstützung für Windows 7 – spezifische Office-Versionen zum „Ende der Lebensdauer“</span><span class="sxs-lookup"><span data-stu-id="bf739-164">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="bf739-165">Behebt ein Problem, bei dem Anpassungseinstellungen möglicherweise nicht erwartungsgemäß angewendet wurden</span><span class="sxs-lookup"><span data-stu-id="bf739-165">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="bf739-166">Behebt ein Problem, bei dem externe .cat-Dateien möglicherweise unerwartet heruntergeladen wurden.</span><span class="sxs-lookup"><span data-stu-id="bf739-166">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="bf739-167">16. Januar 2020</span><span class="sxs-lookup"><span data-stu-id="bf739-167">January 16, 2020</span></span>

<span data-ttu-id="bf739-168">Version 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="bf739-168">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="bf739-169">Behebt ein Problem, bei dem die Office-Installationsoberfläche möglicherweise in einer falschen Sprache angezeigt wird, wenn mehrere Sprachen installiert sind</span><span class="sxs-lookup"><span data-stu-id="bf739-169">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="bf739-170">Behebt ein Problem, bei dem die Office-Installation möglicherweise unerwartet fehlschlägt, wenn bestimmte Korrekturhilfepakete installiert sind</span><span class="sxs-lookup"><span data-stu-id="bf739-170">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="bf739-171">Fügt Unterstützung zur optionalen Kontrolle der Erstbereitstellung des Features [Microsoft Search in Bing](/deployoffice/microsoft-search-bing) hinzu</span><span class="sxs-lookup"><span data-stu-id="bf739-171">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](/deployoffice/microsoft-search-bing)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="bf739-172">31. Oktober 2019</span><span class="sxs-lookup"><span data-stu-id="bf739-172">October 31, 2019</span></span>

<span data-ttu-id="bf739-173">Version 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="bf739-173">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="bf739-174">Behebt ein Problem, damit Skype for Business Basic 2019 zusammen mit 2019 Perpetual Enterprise-volumenlizenzierten Produkten installiert werden kann.</span><span class="sxs-lookup"><span data-stu-id="bf739-174">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="bf739-175">Behebt ein Problem, das dazu führen kann, dass der ODT-Downloadmodus unter bestimmten Umständen bei Verwendung eines Proxys unerwartet fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="bf739-175">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="bf739-176">Neue Funktion, die das Herunterladen des ODT-Downloadmodus über HTTP über einen anderen Port als Port 80 ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="bf739-176">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="bf739-177">10. Juli 2019</span><span class="sxs-lookup"><span data-stu-id="bf739-177">July 10, 2019</span></span>

<span data-ttu-id="bf739-178">Version 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="bf739-178">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="bf739-179">Unterstützung weiterer Produkte hinzugefügt, die mit Office 2019: Access Runtime, Skype for Business Basic installiert wurden.</span><span class="sxs-lookup"><span data-stu-id="bf739-179">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="bf739-180">Unterstützung für die bedingte Installation von eigenständigen Produkten beim Upgrade von MSI hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="bf739-180">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="bf739-181">23. April 2019</span><span class="sxs-lookup"><span data-stu-id="bf739-181">April 23, 2019</span></span>

<span data-ttu-id="bf739-182">Version 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="bf739-182">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="bf739-183">Es wurde ein Fehler mit RemoveMSI = true zum Bereinigen der zugehörigen Registrierungseinstellungen behoben.</span><span class="sxs-lookup"><span data-stu-id="bf739-183">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="bf739-184">Es wurden Fehlercodes aktualisiert, um weitere Details zu unerwarteten Fehlern (E_UNEXPECTED) bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="bf739-184">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="bf739-185">16. April 2019</span><span class="sxs-lookup"><span data-stu-id="bf739-185">April 16 2019</span></span>

<span data-ttu-id="bf739-186">Version 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="bf739-186">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="bf739-187">Unterstützung für Upgrades von 32-Bit C2R auf 64-Bit C2R mit neuem MigrateArch-Attribut.</span><span class="sxs-lookup"><span data-stu-id="bf739-187">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="bf739-188">Aktualisierte Logik für "/configure", die den Zugriff auf Konfigurations-XML-Dateien ermöglicht, die in Webspeicherorten gespeichert sind (HTTP und HTTPS).</span><span class="sxs-lookup"><span data-stu-id="bf739-188">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="bf739-189">"MatchInstalled" als neues Attribut hinzugefügt, das dem ODT beim Hinzufügen weiterer Produkte oder Sprachen das Abgleichen mit der vorhandenen Version ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="bf739-189">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="bf739-190">13. März 2019</span><span class="sxs-lookup"><span data-stu-id="bf739-190">March 13, 2019</span></span>

<span data-ttu-id="bf739-191">Version 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="bf739-191">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="bf739-192">Verbesserungen für Upgrade- und Migrationsszenarien</span><span class="sxs-lookup"><span data-stu-id="bf739-192">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="bf739-193">14. Januar 2019</span><span class="sxs-lookup"><span data-stu-id="bf739-193">January 14, 2019</span></span>

<span data-ttu-id="bf739-194">Version 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="bf739-194">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="bf739-195">Verbesserungen bei Protokollierung und Telemetrie für die Bereitstellungskonfiguration.</span><span class="sxs-lookup"><span data-stu-id="bf739-195">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="bf739-196">Verwandte Links</span><span class="sxs-lookup"><span data-stu-id="bf739-196">Related links</span></span>

[<span data-ttu-id="bf739-197">ODT Download Center</span><span class="sxs-lookup"><span data-stu-id="bf739-197">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)
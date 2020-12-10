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
ms.openlocfilehash: 125f37f1fb4b21d2d63784e51703c1297d928f49
ms.sourcegitcommit: c7f7982f4d2d0d8db4fc4fbf961b79a03bc8b36e
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/08/2020
ms.locfileid: "49601410"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="907f0-103">Versionsverlauf für das Office-Bereitstellungstool</span><span class="sxs-lookup"><span data-stu-id="907f0-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="907f0-104">Das Office-Bereitstellungstool (ODT) ist ein Befehlszeilentool, mit dem Sie Office Klick-und-Los-Versionen wie etwa Microsoft 365-Apps auf Ihre Clientcomputer herunterladen und dort bereitstellen können.</span><span class="sxs-lookup"><span data-stu-id="907f0-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="907f0-105">Das ODT bietet Ihnen mehr Kontrolle über eine Office-Installation.</span><span class="sxs-lookup"><span data-stu-id="907f0-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="907f0-106">Sie können definieren, welche Produkte und Sprachen installiert werden, wie diese Produkte aktualisiert werden sollen und ob den Benutzern der Installationsvorgang angezeigt werden soll.</span><span class="sxs-lookup"><span data-stu-id="907f0-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="907f0-107">Informationen zur Verwendung des ODT finden Sie unter [Übersicht über das Office-Bereitstellungstool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="907f0-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="907f0-108">**Unterstützte Betriebssystem**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="907f0-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="907f0-109">**Installationsanweisungen**: Laden Sie die selbst entpackende ausführbare Datei herunter, die die ausführbare Datei (setup.exe) und eine Beispielkonfigurationsdatei (configuration.xml) für das Office-Bereitstellungstool enthält, und führen Sie sie aus.</span><span class="sxs-lookup"><span data-stu-id="907f0-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

<span data-ttu-id="907f0-110">[Laden Sie das Office-Bereitstellungstool herunter](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).</span><span class="sxs-lookup"><span data-stu-id="907f0-110">[Download Office Deployment Tool](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)</span></span>

## <a name="december-8-2020"></a><span data-ttu-id="907f0-111">8. Dezember 2020</span><span class="sxs-lookup"><span data-stu-id="907f0-111">December 8, 2020</span></span>
<span data-ttu-id="907f0-112">Version 16.0.13426.20308 (setup.exe-Version 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="907f0-112">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="907f0-113">Es wurde ein Problem behoben, bei dem im Download-Modus Downloads aus dem Perpetual 2019-Kanal blockiert wurden, wenn auf dem Gerät ein Office-Produkt installiert war, das nicht aus einem Perpetual 2019-Kanal stammte.</span><span class="sxs-lookup"><span data-stu-id="907f0-113">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="907f0-114">Es wurde ein Problem behoben, bei dem die Migration einer Architektur bei einer im Download-Modus erstellten lokalen Quelle fehlschlug, in dem eine bestimmte Version in der XLM-Konfiguration angegeben war.</span><span class="sxs-lookup"><span data-stu-id="907f0-114">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="907f0-115">23. November 2020</span><span class="sxs-lookup"><span data-stu-id="907f0-115">November 23, 2020</span></span>
<span data-ttu-id="907f0-116">Version 16.0.13328.20420 (setup.exe-Version 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="907f0-116">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="907f0-117">Es wurde ein Problem behoben, bei dem Korrekturhilfen nicht im /download-Modus heruntergeladen wurden</span><span class="sxs-lookup"><span data-stu-id="907f0-117">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="907f0-118">Es wurde ein Problem behoben, bei dem der /download-Modus fehlschlug, wenn er in einem deautorisierten Benutzerkontext ausgeführt wurde</span><span class="sxs-lookup"><span data-stu-id="907f0-118">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="907f0-119">Es wurde ein Problem behoben, bei dem die Angabe eines Versionsattributs in der XML-Konfiguration zu einem unvollständigen Download im /download-Modus führte</span><span class="sxs-lookup"><span data-stu-id="907f0-119">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="907f0-120">Es wurde ein Problem behoben, bei dem das Office-Bereitstellungstool beim Extrahieren nicht „setup.exe“ benannt wurde</span><span class="sxs-lookup"><span data-stu-id="907f0-120">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="907f0-121">Es wurde ein Problem behoben, das bei der Priorisierung der Installationsquelle auftrat, wenn ein Channel-Attribut in der XML-Konfiguration bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="907f0-121">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="907f0-122">10. November 2020</span><span class="sxs-lookup"><span data-stu-id="907f0-122">November 10, 2020</span></span>
<span data-ttu-id="907f0-123">Version 16.0.13328.20356 (setupODT.exe-Version 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="907f0-123">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="907f0-124">Verbesserungen bei Zuverlässigkeit und Resilienz</span><span class="sxs-lookup"><span data-stu-id="907f0-124">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="907f0-125">Um Verwirrung zu vermeiden und Setupfehler einfacher diagnostizieren zu können, wird das ODT jetzt standardmäßig als "setupODT.exe" bezeichnet.</span><span class="sxs-lookup"><span data-stu-id="907f0-125">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="907f0-126">29. Oktober 2020</span><span class="sxs-lookup"><span data-stu-id="907f0-126">October 29, 2020</span></span>
<span data-ttu-id="907f0-127">Version 16.0.13328.20292 (setup.exe Version 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="907f0-127">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="907f0-128">Behebt ein Problem, bei dem bestimmte Office 2007-Produkte die Installation bei Verwendung von RemoveMSI unerwartet blockieren können.</span><span class="sxs-lookup"><span data-stu-id="907f0-128">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="907f0-129">14. Oktober 2020</span><span class="sxs-lookup"><span data-stu-id="907f0-129">October 14, 2020</span></span>
<span data-ttu-id="907f0-130">Version 16.0.13231.20368 (setup.exe-Version 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="907f0-130">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="907f0-131">Alle Produkte verwenden jetzt standardmäßig den monatlichen Kanal, wenn kein Kanal angegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="907f0-131">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="907f0-132">Verbesserte Sicherheit beim Ausführen von ODT aus einem Verzeichnis, das andere DLL-Dateien enthält.</span><span class="sxs-lookup"><span data-stu-id="907f0-132">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="907f0-133">Verbesserungen bei Zuverlässigkeit und Resilienz</span><span class="sxs-lookup"><span data-stu-id="907f0-133">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="907f0-134">9. Juni 2020</span><span class="sxs-lookup"><span data-stu-id="907f0-134">June 9, 2020</span></span>

<span data-ttu-id="907f0-135">Version 16.0.12827.20268 (setup.exe-Version 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="907f0-135">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="907f0-136">Der aktuelle Kanal ist jetzt der Standardkanal, wenn kein Kanal angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="907f0-136">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="907f0-137">Unterstützung für den monatlichen Enterprise-Kanal hinzugefügt</span><span class="sxs-lookup"><span data-stu-id="907f0-137">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="907f0-138">Unterstützung für neue Kanalnamen hinzugefügt</span><span class="sxs-lookup"><span data-stu-id="907f0-138">Added support for new channel names</span></span>
- <span data-ttu-id="907f0-139">Zusätzliche Resilienz-Features, um die Installation fortzusetzen, wenn möglich, auch wenn einige Sprachressourcen nicht verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="907f0-139">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="907f0-140">Erweiterte MSIRemove-Funktionen zum Entfernen von Office 2007-Produkten</span><span class="sxs-lookup"><span data-stu-id="907f0-140">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="907f0-141">Erweiterte MSIRemove-Funktionen, um Access-Datenbankmodul zu entfernen</span><span class="sxs-lookup"><span data-stu-id="907f0-141">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="907f0-142">15. April 2020</span><span class="sxs-lookup"><span data-stu-id="907f0-142">April 15, 2020</span></span>

<span data-ttu-id="907f0-143">Version 16.0.12624.20320 (setup.exe-Version 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="907f0-143">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="907f0-144">Bietet Unterstützung für Windows 7 – spezifische Office-Versionen zum „Ende der Lebensdauer“</span><span class="sxs-lookup"><span data-stu-id="907f0-144">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="907f0-145">Behebt ein Problem, bei dem Anpassungseinstellungen möglicherweise nicht erwartungsgemäß angewendet wurden</span><span class="sxs-lookup"><span data-stu-id="907f0-145">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="907f0-146">Behebt ein Problem, bei dem externe .cat-Dateien möglicherweise unerwartet heruntergeladen wurden.</span><span class="sxs-lookup"><span data-stu-id="907f0-146">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="907f0-147">16. Januar 2020</span><span class="sxs-lookup"><span data-stu-id="907f0-147">January 16, 2020</span></span>

<span data-ttu-id="907f0-148">Version 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="907f0-148">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="907f0-149">Behebt ein Problem, bei dem die Office-Installationsoberfläche möglicherweise in einer falschen Sprache angezeigt wird, wenn mehrere Sprachen installiert sind</span><span class="sxs-lookup"><span data-stu-id="907f0-149">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="907f0-150">Behebt ein Problem, bei dem die Office-Installation möglicherweise unerwartet fehlschlägt, wenn bestimmte Korrekturhilfepakete installiert sind</span><span class="sxs-lookup"><span data-stu-id="907f0-150">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="907f0-151">Fügt Unterstützung zur optionalen Kontrolle der Erstbereitstellung des Features [Microsoft Search in Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345) hinzu</span><span class="sxs-lookup"><span data-stu-id="907f0-151">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="907f0-152">31. Oktober 2019</span><span class="sxs-lookup"><span data-stu-id="907f0-152">October 31, 2019</span></span>

<span data-ttu-id="907f0-153">Version 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="907f0-153">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="907f0-154">Behebt ein Problem, damit Skype for Business Basic 2019 zusammen mit 2019 Perpetual Enterprise-volumenlizenzierten Produkten installiert werden kann.</span><span class="sxs-lookup"><span data-stu-id="907f0-154">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="907f0-155">Behebt ein Problem, das dazu führen kann, dass der ODT-Downloadmodus unter bestimmten Umständen bei Verwendung eines Proxys unerwartet fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="907f0-155">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="907f0-156">Neue Funktion, die das Herunterladen des ODT-Downloadmodus über HTTP über einen anderen Port als Port 80 ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="907f0-156">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="907f0-157">10. Juli 2019</span><span class="sxs-lookup"><span data-stu-id="907f0-157">July 10, 2019</span></span>

<span data-ttu-id="907f0-158">Version 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="907f0-158">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="907f0-159">Unterstützung weiterer Produkte hinzugefügt, die mit Office 2019: Access Runtime, Skype for Business Basic installiert wurden.</span><span class="sxs-lookup"><span data-stu-id="907f0-159">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="907f0-160">Unterstützung für die bedingte Installation von eigenständigen Produkten beim Upgrade von MSI hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="907f0-160">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="907f0-161">23. April 2019</span><span class="sxs-lookup"><span data-stu-id="907f0-161">April 23, 2019</span></span>

<span data-ttu-id="907f0-162">Version 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="907f0-162">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="907f0-163">Es wurde ein Fehler mit RemoveMSI = true zum Bereinigen der zugehörigen Registrierungseinstellungen behoben.</span><span class="sxs-lookup"><span data-stu-id="907f0-163">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="907f0-164">Es wurden Fehlercodes aktualisiert, um weitere Details zu unerwarteten Fehlern (E_UNEXPECTED) bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="907f0-164">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="907f0-165">16. April 2019</span><span class="sxs-lookup"><span data-stu-id="907f0-165">April 16 2019</span></span>

<span data-ttu-id="907f0-166">Version 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="907f0-166">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="907f0-167">Unterstützung für Upgrades von 32-Bit C2R auf 64-Bit C2R mit neuem MigrateArch-Attribut.</span><span class="sxs-lookup"><span data-stu-id="907f0-167">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="907f0-168">Aktualisierte Logik für "/configure", die den Zugriff auf Konfigurations-XML-Dateien ermöglicht, die in Webspeicherorten gespeichert sind (HTTP und HTTPS).</span><span class="sxs-lookup"><span data-stu-id="907f0-168">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="907f0-169">"MatchInstalled" als neues Attribut hinzugefügt, das dem ODT beim Hinzufügen weiterer Produkte oder Sprachen das Abgleichen mit der vorhandenen Version ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="907f0-169">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="907f0-170">13. März 2019</span><span class="sxs-lookup"><span data-stu-id="907f0-170">March 13, 2019</span></span>

<span data-ttu-id="907f0-171">Version 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="907f0-171">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="907f0-172">Verbesserungen für Upgrade- und Migrationsszenarien</span><span class="sxs-lookup"><span data-stu-id="907f0-172">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="907f0-173">14. Januar 2019</span><span class="sxs-lookup"><span data-stu-id="907f0-173">January 14, 2019</span></span>

<span data-ttu-id="907f0-174">Version 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="907f0-174">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="907f0-175">Verbesserungen bei Protokollierung und Telemetrie für die Bereitstellungskonfiguration.</span><span class="sxs-lookup"><span data-stu-id="907f0-175">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="907f0-176">Verwandte Links</span><span class="sxs-lookup"><span data-stu-id="907f0-176">Related links</span></span>

[<span data-ttu-id="907f0-177">ODT Download Center</span><span class="sxs-lookup"><span data-stu-id="907f0-177">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)
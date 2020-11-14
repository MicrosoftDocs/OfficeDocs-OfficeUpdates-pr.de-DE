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
ms.openlocfilehash: acc7e37ae203c824c0759eab641491d377073a7f
ms.sourcegitcommit: 0cba381a1439abdc7044a81772609c91998d65f0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/12/2020
ms.locfileid: "48999540"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="55cda-103">Versionsverlauf für das Office-Bereitstellungstool</span><span class="sxs-lookup"><span data-stu-id="55cda-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="55cda-104">Das Office-Bereitstellungstool (ODT) ist ein Befehlszeilentool, mit dem Sie Office Klick-und-Los-Versionen wie etwa Microsoft 365 Apps auf Ihre Clientcomputer herunterladen und dort bereitstellen können.</span><span class="sxs-lookup"><span data-stu-id="55cda-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="55cda-p101">Das ODT bietet Ihnen mehr Kontrolle über eine Office-Installation. Sie können definieren, welche Produkte und Sprachen installiert werden, wie diese Produkte aktualisiert werden sollen und ob den Benutzern der Installationsvorgang angezeigt werden soll. Informationen zur Verwendung des ODT finden Sie unter [Übersicht über das Office-Bereitstellungstool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="55cda-p101">The ODT gives you more control over an Office installation. You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users. For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="55cda-108">**Unterstützte Betriebssystem** : Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="55cda-108">**Supported Operating System** : Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="55cda-109">**Installationsanweisungen** : Laden Sie die selbst entpackende ausführbare Datei herunter, die die ausführbare Datei des Office-Bereitstellungstools (setupodt.exe) und eine Beispielkonfigurationsdatei (configuration.xml) für das Office-Bereitstellungstool enthält, und führen Sie sie aus.</span><span class="sxs-lookup"><span data-stu-id="55cda-109">**Install Instructions** : Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setupodt.exe) and a sample configuration file (configuration.xml).</span></span> 

<span data-ttu-id="55cda-110">[Laden Sie das Office-Bereitstellungstool herunter](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).</span><span class="sxs-lookup"><span data-stu-id="55cda-110">[Download Office Deployment Tool](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="55cda-111">10. November 2020</span><span class="sxs-lookup"><span data-stu-id="55cda-111">November 10, 2020</span></span>
<span data-ttu-id="55cda-112">Version 16.0.13328.20356 (setupODT.exe-Version 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="55cda-112">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="55cda-113">Verbesserungen bei Zuverlässigkeit und Resilienz</span><span class="sxs-lookup"><span data-stu-id="55cda-113">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="55cda-114">Um Verwirrung zu vermeiden und Setupfehler einfacher diagnostizieren zu können, wird das ODT jetzt standardmäßig als "setupODT.exe" bezeichnet.</span><span class="sxs-lookup"><span data-stu-id="55cda-114">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="55cda-115">29. Oktober 2020</span><span class="sxs-lookup"><span data-stu-id="55cda-115">October 29, 2020</span></span>
<span data-ttu-id="55cda-116">Version 16.0.13328.20292 (setup.exe Version 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="55cda-116">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="55cda-117">Behebt ein Problem, bei dem bestimmte Office 2007-Produkte die Installation bei Verwendung von RemoveMSI unerwartet blockieren können.</span><span class="sxs-lookup"><span data-stu-id="55cda-117">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="55cda-118">14. Oktober 2020</span><span class="sxs-lookup"><span data-stu-id="55cda-118">October 14, 2020</span></span>
<span data-ttu-id="55cda-119">Version 16.0.13231.20368 (setup.exe-Version 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="55cda-119">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="55cda-120">Alle Produkte verwenden jetzt standardmäßig den monatlichen Kanal, wenn kein Kanal angegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="55cda-120">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="55cda-121">Verbesserte Sicherheit beim Ausführen von ODT aus einem Verzeichnis, das andere DLL-Dateien enthält.</span><span class="sxs-lookup"><span data-stu-id="55cda-121">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="55cda-122">Verbesserungen bei Zuverlässigkeit und Resilienz</span><span class="sxs-lookup"><span data-stu-id="55cda-122">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="55cda-123">9. Juni 2020</span><span class="sxs-lookup"><span data-stu-id="55cda-123">June 9, 2020</span></span>

<span data-ttu-id="55cda-124">Version 16.0.12827.20268 (setup.exe-Version 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="55cda-124">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="55cda-125">Der aktuelle Kanal ist jetzt der Standardkanal, wenn kein Kanal angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="55cda-125">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="55cda-126">Unterstützung für den monatlichen Enterprise-Kanal hinzugefügt</span><span class="sxs-lookup"><span data-stu-id="55cda-126">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="55cda-127">Unterstützung für neue Kanalnamen hinzugefügt</span><span class="sxs-lookup"><span data-stu-id="55cda-127">Added support for new channel names</span></span>
- <span data-ttu-id="55cda-128">Zusätzliche Resilienz-Features, um die Installation fortzusetzen, wenn möglich, auch wenn einige Sprachressourcen nicht verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="55cda-128">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="55cda-129">Erweiterte MSIRemove-Funktionen zum Entfernen von Office 2007-Produkten</span><span class="sxs-lookup"><span data-stu-id="55cda-129">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="55cda-130">Erweiterte MSIRemove-Funktionen, um Access-Datenbankmodul zu entfernen</span><span class="sxs-lookup"><span data-stu-id="55cda-130">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="55cda-131">15. April 2020</span><span class="sxs-lookup"><span data-stu-id="55cda-131">April 15, 2020</span></span>

<span data-ttu-id="55cda-132">Version 16.0.12624.20320 (setup.exe-Version 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="55cda-132">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="55cda-133">Bietet Unterstützung für Windows 7 – spezifische Office-Versionen zum „Ende der Lebensdauer“</span><span class="sxs-lookup"><span data-stu-id="55cda-133">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="55cda-134">Behebt ein Problem, bei dem Anpassungseinstellungen möglicherweise nicht erwartungsgemäß angewendet wurden</span><span class="sxs-lookup"><span data-stu-id="55cda-134">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="55cda-135">Behebt ein Problem, bei dem externe .cat-Dateien möglicherweise unerwartet heruntergeladen wurden.</span><span class="sxs-lookup"><span data-stu-id="55cda-135">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="55cda-136">16. Januar 2020</span><span class="sxs-lookup"><span data-stu-id="55cda-136">January 16, 2020</span></span>

<span data-ttu-id="55cda-137">Version 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="55cda-137">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="55cda-138">Behebt ein Problem, bei dem die Office-Installationsoberfläche möglicherweise in einer falschen Sprache angezeigt wird, wenn mehrere Sprachen installiert sind</span><span class="sxs-lookup"><span data-stu-id="55cda-138">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="55cda-139">Behebt ein Problem, bei dem die Office-Installation möglicherweise unerwartet fehlschlägt, wenn bestimmte Korrekturhilfepakete installiert sind</span><span class="sxs-lookup"><span data-stu-id="55cda-139">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="55cda-140">Fügt Unterstützung zur optionalen Kontrolle der Erstbereitstellung des Features [Microsoft Search in Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345) hinzu</span><span class="sxs-lookup"><span data-stu-id="55cda-140">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="55cda-141">31. Oktober 2019</span><span class="sxs-lookup"><span data-stu-id="55cda-141">October 31, 2019</span></span>

<span data-ttu-id="55cda-142">Version 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="55cda-142">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="55cda-143">Behebt ein Problem, damit Skype for Business Basic 2019 zusammen mit 2019 Perpetual Enterprise-volumenlizenzierten Produkten installiert werden kann.</span><span class="sxs-lookup"><span data-stu-id="55cda-143">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="55cda-144">Behebt ein Problem, das dazu führen kann, dass der ODT-Downloadmodus unter bestimmten Umständen bei Verwendung eines Proxys unerwartet fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="55cda-144">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="55cda-145">Neue Funktion, die das Herunterladen des ODT-Downloadmodus über HTTP über einen anderen Port als Port 80 ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="55cda-145">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="55cda-146">10. Juli 2019</span><span class="sxs-lookup"><span data-stu-id="55cda-146">July 10, 2019</span></span>

<span data-ttu-id="55cda-147">Version 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="55cda-147">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="55cda-148">Unterstützung weiterer Produkte hinzugefügt, die mit Office 2019: Access Runtime, Skype for Business Basic installiert wurden.</span><span class="sxs-lookup"><span data-stu-id="55cda-148">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="55cda-149">Unterstützung für die bedingte Installation von eigenständigen Produkten beim Upgrade von MSI hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="55cda-149">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="55cda-150">23. April 2019</span><span class="sxs-lookup"><span data-stu-id="55cda-150">April 23, 2019</span></span>

<span data-ttu-id="55cda-151">Version 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="55cda-151">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="55cda-152">Es wurde ein Fehler mit RemoveMSI = true zum Bereinigen der zugehörigen Registrierungseinstellungen behoben.</span><span class="sxs-lookup"><span data-stu-id="55cda-152">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="55cda-153">Es wurden Fehlercodes aktualisiert, um weitere Details zu unerwarteten Fehlern (E_UNEXPECTED) bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="55cda-153">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="55cda-154">16. April 2019</span><span class="sxs-lookup"><span data-stu-id="55cda-154">April 16 2019</span></span>

<span data-ttu-id="55cda-155">Version 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="55cda-155">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="55cda-156">Unterstützung für Upgrades von 32-Bit C2R auf 64-Bit C2R mit neuem MigrateArch-Attribut.</span><span class="sxs-lookup"><span data-stu-id="55cda-156">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="55cda-157">Aktualisierte Logik für "/configure", die den Zugriff auf Konfigurations-XML-Dateien ermöglicht, die in Webspeicherorten gespeichert sind (HTTP und HTTPS).</span><span class="sxs-lookup"><span data-stu-id="55cda-157">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="55cda-158">"MatchInstalled" als neues Attribut hinzugefügt, das dem ODT beim Hinzufügen weiterer Produkte oder Sprachen das Abgleichen mit der vorhandenen Version ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="55cda-158">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="55cda-159">13. März 2019</span><span class="sxs-lookup"><span data-stu-id="55cda-159">March 13, 2019</span></span>

<span data-ttu-id="55cda-160">Version 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="55cda-160">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="55cda-161">Verbesserungen für Upgrade- und Migrationsszenarien</span><span class="sxs-lookup"><span data-stu-id="55cda-161">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="55cda-162">14. Januar 2019</span><span class="sxs-lookup"><span data-stu-id="55cda-162">January 14, 2019</span></span>

<span data-ttu-id="55cda-163">Version 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="55cda-163">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="55cda-164">Verbesserungen bei Protokollierung und Telemetrie für die Bereitstellungskonfiguration.</span><span class="sxs-lookup"><span data-stu-id="55cda-164">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="55cda-165">Verwandte Links</span><span class="sxs-lookup"><span data-stu-id="55cda-165">Related links</span></span>

[<span data-ttu-id="55cda-166">ODT Download Center</span><span class="sxs-lookup"><span data-stu-id="55cda-166">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)
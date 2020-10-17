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
ms.openlocfilehash: 4f65d41bfa18321a951fb18abcf919056bec7c5d
ms.sourcegitcommit: 57e715a8a3c0565b902cb3e6ca45d18a26f8ec45
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/15/2020
ms.locfileid: "48469994"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="3870c-103">Versionsverlauf für das Office-Bereitstellungstool</span><span class="sxs-lookup"><span data-stu-id="3870c-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="3870c-104">Das Office-Bereitstellungstool (ODT) ist ein Befehlszeilentool, mit dem Sie Office Klick-und-Los-Versionen wie etwa Microsoft 365-Apps auf Ihre Clientcomputer herunterladen und dort bereitstellen können.</span><span class="sxs-lookup"><span data-stu-id="3870c-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="3870c-105">Das ODT bietet Ihnen mehr Kontrolle über eine Office-Installation.</span><span class="sxs-lookup"><span data-stu-id="3870c-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="3870c-106">Sie können definieren, welche Produkte und Sprachen installiert werden, wie diese Produkte aktualisiert werden sollen und ob den Benutzern der Installationsvorgang angezeigt werden soll.</span><span class="sxs-lookup"><span data-stu-id="3870c-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="3870c-107">Informationen zur Verwendung des ODT finden Sie unter [Übersicht über das Office-Bereitstellungstool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="3870c-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="3870c-108">**Unterstützte Betriebssystem**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="3870c-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="3870c-109">**Installationsanweisungen**: Laden Sie die selbst entpackende ausführbare Datei herunter, die die ausführbare Datei (setup.exe) und eine Beispielkonfigurationsdatei (configuration.xml) für das Office-Bereitstellungstool enthält, und führen Sie sie aus.</span><span class="sxs-lookup"><span data-stu-id="3870c-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

<span data-ttu-id="3870c-110">[Laden Sie das Office-Bereitstellungstool herunter](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).</span><span class="sxs-lookup"><span data-stu-id="3870c-110">[Download Office Deployment Tool](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="3870c-111">14. Oktober 2020</span><span class="sxs-lookup"><span data-stu-id="3870c-111">October 14, 2020</span></span>
<span data-ttu-id="3870c-112">Version 16.0.13231.20368 (setup.exe-Version 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="3870c-112">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="3870c-113">Alle Produkte verwenden jetzt standardmäßig den monatlichen Kanal, wenn kein Kanal angegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="3870c-113">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="3870c-114">Behebt ein Problem, bei dem bestimmte Office 2007-Produkte die Installation bei Verwendung von RemoveMSI unerwartet blockieren können.</span><span class="sxs-lookup"><span data-stu-id="3870c-114">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>
- <span data-ttu-id="3870c-115">Verbesserte Sicherheit beim Ausführen von ODT aus einem Verzeichnis, das andere DLL-Dateien enthält.</span><span class="sxs-lookup"><span data-stu-id="3870c-115">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="3870c-116">Verbesserungen bei Zuverlässigkeit und Resilienz</span><span class="sxs-lookup"><span data-stu-id="3870c-116">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="3870c-117">9. Juni 2020</span><span class="sxs-lookup"><span data-stu-id="3870c-117">June 9, 2020</span></span>

<span data-ttu-id="3870c-118">Version 16.0.12827.20268 (setup.exe-Version 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="3870c-118">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="3870c-119">Der aktuelle Kanal ist jetzt der Standardkanal, wenn kein Kanal angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="3870c-119">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="3870c-120">Unterstützung für den monatlichen Enterprise-Kanal hinzugefügt</span><span class="sxs-lookup"><span data-stu-id="3870c-120">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="3870c-121">Unterstützung für neue Kanalnamen hinzugefügt</span><span class="sxs-lookup"><span data-stu-id="3870c-121">Added support for new channel names</span></span>
- <span data-ttu-id="3870c-122">Zusätzliche Resilienz-Features, um die Installation fortzusetzen, wenn möglich, auch wenn einige Sprachressourcen nicht verfügbar sind</span><span class="sxs-lookup"><span data-stu-id="3870c-122">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="3870c-123">Erweiterte MSIRemove-Funktionen zum Entfernen von Office 2007-Produkten</span><span class="sxs-lookup"><span data-stu-id="3870c-123">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="3870c-124">Erweiterte MSIRemove-Funktionen, um Access-Datenbankmodul zu entfernen</span><span class="sxs-lookup"><span data-stu-id="3870c-124">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="3870c-125">15. April 2020</span><span class="sxs-lookup"><span data-stu-id="3870c-125">April 15, 2020</span></span>

<span data-ttu-id="3870c-126">Version 16.0.12624.20320 (setup.exe-Version 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="3870c-126">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="3870c-127">Bietet Unterstützung für Windows 7 – spezifische Office-Versionen zum „Ende der Lebensdauer“</span><span class="sxs-lookup"><span data-stu-id="3870c-127">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="3870c-128">Behebt ein Problem, bei dem Anpassungseinstellungen möglicherweise nicht erwartungsgemäß angewendet wurden</span><span class="sxs-lookup"><span data-stu-id="3870c-128">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="3870c-129">Behebt ein Problem, bei dem externe .cat-Dateien möglicherweise unerwartet heruntergeladen wurden.</span><span class="sxs-lookup"><span data-stu-id="3870c-129">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="3870c-130">16. Januar 2020</span><span class="sxs-lookup"><span data-stu-id="3870c-130">January 16, 2020</span></span>

<span data-ttu-id="3870c-131">Version 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="3870c-131">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="3870c-132">Behebt ein Problem, bei dem die Office-Installationsoberfläche möglicherweise in einer falschen Sprache angezeigt wird, wenn mehrere Sprachen installiert sind</span><span class="sxs-lookup"><span data-stu-id="3870c-132">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="3870c-133">Behebt ein Problem, bei dem die Office-Installation möglicherweise unerwartet fehlschlägt, wenn bestimmte Korrekturhilfepakete installiert sind</span><span class="sxs-lookup"><span data-stu-id="3870c-133">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="3870c-134">Fügt Unterstützung zur optionalen Kontrolle der Erstbereitstellung des Features [Microsoft Search in Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345) hinzu</span><span class="sxs-lookup"><span data-stu-id="3870c-134">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="3870c-135">31. Oktober 2019</span><span class="sxs-lookup"><span data-stu-id="3870c-135">October 31, 2019</span></span>

<span data-ttu-id="3870c-136">Version 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="3870c-136">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="3870c-137">Behebt ein Problem, damit Skype for Business Basic 2019 zusammen mit 2019 Perpetual Enterprise-volumenlizenzierten Produkten installiert werden kann.</span><span class="sxs-lookup"><span data-stu-id="3870c-137">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="3870c-138">Behebt ein Problem, das dazu führen kann, dass der ODT-Downloadmodus unter bestimmten Umständen bei Verwendung eines Proxys unerwartet fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="3870c-138">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="3870c-139">Neue Funktion, die das Herunterladen des ODT-Downloadmodus über HTTP über einen anderen Port als Port 80 ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="3870c-139">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="3870c-140">10. Juli 2019</span><span class="sxs-lookup"><span data-stu-id="3870c-140">July 10, 2019</span></span>

<span data-ttu-id="3870c-141">Version 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="3870c-141">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="3870c-142">Unterstützung weiterer Produkte hinzugefügt, die mit Office 2019: Access Runtime, Skype for Business Basic installiert wurden.</span><span class="sxs-lookup"><span data-stu-id="3870c-142">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="3870c-143">Unterstützung für die bedingte Installation von eigenständigen Produkten beim Upgrade von MSI hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="3870c-143">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="3870c-144">23. April 2019</span><span class="sxs-lookup"><span data-stu-id="3870c-144">April 23, 2019</span></span>

<span data-ttu-id="3870c-145">Version 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="3870c-145">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="3870c-146">Es wurde ein Fehler mit RemoveMSI = true zum Bereinigen der zugehörigen Registrierungseinstellungen behoben.</span><span class="sxs-lookup"><span data-stu-id="3870c-146">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="3870c-147">Es wurden Fehlercodes aktualisiert, um weitere Details zu unerwarteten Fehlern (E_UNEXPECTED) bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="3870c-147">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="3870c-148">16. April 2019</span><span class="sxs-lookup"><span data-stu-id="3870c-148">April 16 2019</span></span>

<span data-ttu-id="3870c-149">Version 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="3870c-149">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="3870c-150">Unterstützung für Upgrades von 32-Bit C2R auf 64-Bit C2R mit neuem MigrateArch-Attribut.</span><span class="sxs-lookup"><span data-stu-id="3870c-150">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="3870c-151">Aktualisierte Logik für "/configure", die den Zugriff auf Konfigurations-XML-Dateien ermöglicht, die in Webspeicherorten gespeichert sind (HTTP und HTTPS).</span><span class="sxs-lookup"><span data-stu-id="3870c-151">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="3870c-152">"MatchInstalled" als neues Attribut hinzugefügt, das dem ODT beim Hinzufügen weiterer Produkte oder Sprachen das Abgleichen mit der vorhandenen Version ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="3870c-152">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="3870c-153">13. März 2019</span><span class="sxs-lookup"><span data-stu-id="3870c-153">March 13, 2019</span></span>

<span data-ttu-id="3870c-154">Version 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="3870c-154">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="3870c-155">Verbesserungen für Upgrade- und Migrationsszenarien</span><span class="sxs-lookup"><span data-stu-id="3870c-155">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="3870c-156">14. Januar 2019</span><span class="sxs-lookup"><span data-stu-id="3870c-156">January 14, 2019</span></span>

<span data-ttu-id="3870c-157">Version 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="3870c-157">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="3870c-158">Verbesserungen bei Protokollierung und Telemetrie für die Bereitstellungskonfiguration.</span><span class="sxs-lookup"><span data-stu-id="3870c-158">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="3870c-159">Verwandte Links</span><span class="sxs-lookup"><span data-stu-id="3870c-159">Related links</span></span>

[<span data-ttu-id="3870c-160">ODT Download Center</span><span class="sxs-lookup"><span data-stu-id="3870c-160">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)
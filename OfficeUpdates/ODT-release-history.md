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
# <a name="release-history-for-office-deployment-tool"></a>Versionsverlauf für das Office-Bereitstellungstool

Das Office-Bereitstellungstool (ODT) ist ein Befehlszeilentool, mit dem Sie Office Klick-und-Los-Versionen wie etwa Microsoft 365-Apps auf Ihre Clientcomputer herunterladen und dort bereitstellen können. 


Das ODT bietet Ihnen mehr Kontrolle über eine Office-Installation. Sie können definieren, welche Produkte und Sprachen installiert werden, wie diese Produkte aktualisiert werden sollen und ob den Benutzern der Installationsvorgang angezeigt werden soll. Informationen zur Verwendung des ODT finden Sie unter [Übersicht über das Office-Bereitstellungstool](/deployoffice/overview-of-the-office-2016-deployment-tool).

 **Unterstützte Betriebssystem**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016 
 
 **Installationsanweisungen**: Laden Sie die selbst entpackende ausführbare Datei herunter, die die ausführbare Datei (setup.exe) und eine Beispielkonfigurationsdatei (configuration.xml) für das Office-Bereitstellungstool enthält, und führen Sie sie aus. 

[Laden Sie das Office-Bereitstellungstool herunter](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).


## <a name="march-23-2021"></a>23. März 2021
Version 16.0.13801.20360 (setup.exe, Version 16.0.13801.20340)
- Änderungen zur Unterstützung anstehender Office-Produkt-Releases
- Zuverlässigkeitsfixes für ARM-Plattformen


## <a name="february-25-2021"></a>25. Februar 2021
Version 16.0.13628.20476 (setup.exe, Version 16.0.13628.20462)
- Ein Problem wurde behoben, bei dem configuration.xml-Dateien, die mehrere Dutzend Sprachen angeben, nicht validiert werden konnten
- Ein Problem wurde behoben, bei dem die Eigenschaft FORCEAPPSHUTDOWN in MigrateArch-Szenarien nicht beachtet wurde
- Ein Problem wurde behoben, bei dem die Angabe von 2 oder mehr PIDKEY-Attributen in „configuration.xml“ zu Fehlern bei der Installation der PIDKeys führte



## <a name="february-9-2021"></a>9. Februar 2021
Version 16.0.13628.20274 (setup.exe Version 16.0.13628.20246)
- Es wurde eine Prüfung hinzugefügt, die vor nicht unterstützten Installationen unter Windows 8.0 warnt und diese verhindert
- Zuverlässigkeitskorrekturen für ARM64-Geräte


## <a name="january-12-2021"></a>12. Januar 2021
Version 16.0.13530.20376 (setup.exe Version 16.0.13530.20334)
- Ein Problem wurde behoben, bei dem eine beschädigte oder nicht standardmäßige Produktregistrierung zum Fehlschlagen von RemoveMSI-Vorgängen führen konnte.

## <a name="december-21-2020"></a>21. Dezember 2020
Version 16.0.13426.20370 (setup.exe Version 16.0.13426.20352)
- Es wurde ein Problem behoben, bei dem die lokalen Quellinstallationen von ProofingTools aus dem PerpetualVL2019-Kanal fehlschlugen
- Es wurde ein Problem behoben, damit sichergestellt wird, dass der Klick-und-Los-Client eine Selbstaktualisierung versucht, wenn einer vorhandenen Installation zusätzliche Produkte in nicht vollständigen Office-Sprachen hinzugefügt werden


## <a name="december-8-2020"></a>8. Dezember 2020
Version 16.0.13426.20308 (setup.exe-Version 16.0.13426.20308)
- Es wurde ein Problem behoben, bei dem im Download-Modus Downloads aus dem Perpetual 2019-Kanal blockiert wurden, wenn auf dem Gerät ein Office-Produkt installiert war, das nicht aus einem Perpetual 2019-Kanal stammte.
- Es wurde ein Problem behoben, bei dem die Migration einer Architektur bei einer im Download-Modus erstellten lokalen Quelle fehlschlug, in dem eine bestimmte Version in der XLM-Konfiguration angegeben war.


## <a name="november-23-2020"></a>23. November 2020
Version 16.0.13328.20420 (setup.exe-Version 16.0.13328.20420)
- Es wurde ein Problem behoben, bei dem Korrekturhilfen nicht im /download-Modus heruntergeladen wurden
- Es wurde ein Problem behoben, bei dem der /download-Modus fehlschlug, wenn er in einem deautorisierten Benutzerkontext ausgeführt wurde
- Es wurde ein Problem behoben, bei dem die Angabe eines Versionsattributs in der XML-Konfiguration zu einem unvollständigen Download im /download-Modus führte
- Es wurde ein Problem behoben, bei dem das Office-Bereitstellungstool beim Extrahieren nicht „setup.exe“ benannt wurde
- Es wurde ein Problem behoben, das bei der Priorisierung der Installationsquelle auftrat, wenn ein Channel-Attribut in der XML-Konfiguration bereitgestellt wird.

## <a name="november-10-2020"></a>10. November 2020
Version 16.0.13328.20356 (setupODT.exe-Version 16.0.13328.20336)
- Verbesserungen bei Zuverlässigkeit und Resilienz
- Um Verwirrung zu vermeiden und Setupfehler einfacher diagnostizieren zu können, wird das ODT jetzt standardmäßig als "setupODT.exe" bezeichnet.

## <a name="october-29-2020"></a>29. Oktober 2020
Version 16.0.13328.20292 (setup.exe Version 16.0.13328.20290)
- Behebt ein Problem, bei dem bestimmte Office 2007-Produkte die Installation bei Verwendung von RemoveMSI unerwartet blockieren können.

## <a name="october-14-2020"></a>14. Oktober 2020
Version 16.0.13231.20368 (setup.exe-Version 16.0.13231.20350)
- Alle Produkte verwenden jetzt standardmäßig den monatlichen Kanal, wenn kein Kanal angegeben wurde.
- Verbesserte Sicherheit beim Ausführen von ODT aus einem Verzeichnis, das andere DLL-Dateien enthält.
- Verbesserungen bei Zuverlässigkeit und Resilienz

## <a name="june-9-2020"></a>9. Juni 2020

Version 16.0.12827.20268 (setup.exe-Version 16.0.12827.20258)
- Der aktuelle Kanal ist jetzt der Standardkanal, wenn kein Kanal angegeben wird.
- Unterstützung für den monatlichen Enterprise-Kanal hinzugefügt
- Unterstützung für neue Kanalnamen hinzugefügt
- Zusätzliche Resilienz-Features, um die Installation fortzusetzen, wenn möglich, auch wenn einige Sprachressourcen nicht verfügbar sind
- Erweiterte MSIRemove-Funktionen zum Entfernen von Office 2007-Produkten
- Erweiterte MSIRemove-Funktionen, um Access-Datenbankmodul zu entfernen 

## <a name="april-15-2020"></a>15. April 2020

Version 16.0.12624.20320 (setup.exe-Version 16.0.12624.20290)
- Bietet Unterstützung für Windows 7 – spezifische Office-Versionen zum „Ende der Lebensdauer“
- Behebt ein Problem, bei dem Anpassungseinstellungen möglicherweise nicht erwartungsgemäß angewendet wurden
- Behebt ein Problem, bei dem externe .cat-Dateien möglicherweise unerwartet heruntergeladen wurden.

## <a name="january-16-2020"></a>16. Januar 2020

Version 16.0.12325.20288
- Behebt ein Problem, bei dem die Office-Installationsoberfläche möglicherweise in einer falschen Sprache angezeigt wird, wenn mehrere Sprachen installiert sind
- Behebt ein Problem, bei dem die Office-Installation möglicherweise unerwartet fehlschlägt, wenn bestimmte Korrekturhilfepakete installiert sind
- Fügt Unterstützung zur optionalen Kontrolle der Erstbereitstellung des Features [Microsoft Search in Bing](/deployoffice/microsoft-search-bing) hinzu


## <a name="october-31-2019"></a>31. Oktober 2019

Version 16.0.12130.20272
- Behebt ein Problem, damit Skype for Business Basic 2019 zusammen mit 2019 Perpetual Enterprise-volumenlizenzierten Produkten installiert werden kann.
- Behebt ein Problem, das dazu führen kann, dass der ODT-Downloadmodus unter bestimmten Umständen bei Verwendung eines Proxys unerwartet fehlschlägt.
- Neue Funktion, die das Herunterladen des ODT-Downloadmodus über HTTP über einen anderen Port als Port 80 ermöglicht.


## <a name="july-10-2019"></a>10. Juli 2019

Version 16.0.11901.20022
- Unterstützung weiterer Produkte hinzugefügt, die mit Office 2019: Access Runtime, Skype for Business Basic installiert wurden.
- Unterstützung für die bedingte Installation von eigenständigen Produkten beim Upgrade von MSI hinzugefügt.

## <a name="april-23-2019"></a>23. April 2019

Version 16.0.11617.33601
- Es wurde ein Fehler mit RemoveMSI = true zum Bereinigen der zugehörigen Registrierungseinstellungen behoben.
- Es wurden Fehlercodes aktualisiert, um weitere Details zu unerwarteten Fehlern (E_UNEXPECTED) bereitzustellen.

## <a name="april-16-2019"></a>16. April 2019

Version 16.0.11615.33602
- Unterstützung für Upgrades von 32-Bit C2R auf 64-Bit C2R mit neuem MigrateArch-Attribut.
- Aktualisierte Logik für "/configure", die den Zugriff auf Konfigurations-XML-Dateien ermöglicht, die in Webspeicherorten gespeichert sind (HTTP und HTTPS).
- "MatchInstalled" als neues Attribut hinzugefügt, das dem ODT beim Hinzufügen weiterer Produkte oder Sprachen das Abgleichen mit der vorhandenen Version ermöglicht.

## <a name="march-13-2019"></a>13. März 2019

Version 16.0.11509.33604
- Verbesserungen für Upgrade- und Migrationsszenarien

## <a name="january-14-2019"></a>14. Januar 2019

Version 16.0.11306.33602
- Verbesserungen bei Protokollierung und Telemetrie für die Bereitstellungskonfiguration.


## <a name="related-links"></a>Verwandte Links

[ODT Download Center](https://www.microsoft.com/en-us/download/details.aspx?id=49117)
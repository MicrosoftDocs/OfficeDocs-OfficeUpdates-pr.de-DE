---
title: Versionsverlauf für das Office-Bereitstellungstool (ODT)
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: Stellt IT-Experten einen Versionsverlauf für das Office-Bereitstellungstool (ODT) zur Verfügung
ms.openlocfilehash: 1622ddf9a89767c2d0e456737362eecf4123b3fd
ms.sourcegitcommit: a5da36df390868d76bddfc78e9481ed8e9c5b673
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2019
ms.locfileid: "37275486"
---
# <a name="release-history-for-office-deployment-tool"></a>Versionsverlauf für das Office-Bereitstellungstool

Das Office-Bereitstellungstool (ODT) ist ein Befehlszeilentool, mit dem Sie Office Click-to-Run-Versionen wie etwa Office 365 ProPlus auf Ihre Clientcomputer herunterladen und dort bereitstellen können. 


Das ODT bietet Ihnen mehr Kontrolle über eine Office-Installation. Sie können definieren, welche Produkte und Sprachen installiert werden, wie diese Produkte aktualisiert werden sollen und ob den Benutzern der Installationsvorgang angezeigt werden soll. Informationen zur Verwendung des ODT finden Sie unter [Übersicht über das Office-Bereitstellungstool](https://docs.microsoft.com/de-DE/deployoffice/overview-of-the-office-2016-deployment-tool).

 **Unterstützte Betriebssysteme**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2. 
 
 **Installationsanweisungen**: Laden Sie die selbst entpackende ausführbare Datei herunter, die die ausführbare Datei (setup.exe) und eine Beispielkonfigurationsdatei (configuration.xml) für das Office-Bereitstellungstool enthält, und führen Sie sie aus. 

[Laden Sie das Office-Bereitstellungstool herunter](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117).


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
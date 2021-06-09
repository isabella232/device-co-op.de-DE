---
keywords: Adobe Experience Cloud; Adobe Experience Cloud; Gerätekooperation; Device Co-op; Ende der Lebensdauer
solution: Adobe Experience Cloud
title: Häufig gestellte Fragen zur Einstellung der Gerätekooperation
description: Erfahren Sie mehr über die Pläne zum Ende der Nutzungsdauer für die Gerätekooperation.
source-git-commit: b9e21ba2f749b7a4ad69c122e2273b7f3309da58
workflow-type: tm+mt
source-wordcount: '1017'
ht-degree: 2%

---

# Häufig gestellte Fragen zur Einstellung der Gerätekooperation

In diesem Dokument finden Sie Antworten auf häufig gestellte Fragen zum Adobe Experience Cloud Device Co-op End of Life (EOL)-Plan. Wenn dieser Plan in Kraft tritt, wird Adobe einen erweiterten Hinweis in den [Experience Cloud-Versionshinweisen](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html?lang=de) und im [Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) bereitstellen.

## FAQs

Im Folgenden finden Sie eine Liste von Antworten auf häufig gestellte Fragen zum [!DNL Device Co-op] EOL-Plan.

## Warum wird [!DNL Device Co-op] nicht mehr unterstützt?

Die bevorstehenden Änderungen in der AdTech-Umgebung werden voraussichtlich dazu führen, dass [!DNL Device Co-op] in den kommenden Jahren zu einer veralteten Lösung wird. [!DNL Device Co-op] besteht hauptsächlich aus Drittanbieter-Cookies, und die  [!DNL Google's] Ankündigung, dass sie Drittanbieter-Cookies  [!DNL Google Chrome] bis 2022 blockieren werden, wird die Effektivität von verringern  [!DNL Device Co-op]. [!DNL Chrome] hat etwa 65 % des Marktanteils der Browser, und andere gängige Browser haben bereits die Blockierung von Drittanbieter-Cookies implementiert. Sobald [!DNL Chrome] Drittanbieter-Cookies blockiert, wird der Großteil der Drittanbieter-Cookies blockiert und [!DNL Device Co-op] wird veraltet.

## Warum beendet die Adobe [!DNL Device Co-op] jetzt Anmeldungen?

Anmeldungen enden, um zu verhindern, dass die Kundenerwartungen aufgrund der bevorstehenden Branchenänderungen in Bezug auf Drittanbieter-Cookies nicht erfüllt werden. [!DNL Device Co-op] dauert einige Monate, um vorbereitet zu werden, und weitere Monate, um Wert aus dem Dienst zu extrahieren. Alle weiteren Anmeldungen zu diesem Zeitpunkt könnten dazu führen, dass Marken nicht den vollen Wert von [!DNL Device Co-op] erleben.

## Können sich neue Kunden anmelden?

Ab dem 11. Juni 2021 akzeptiert Adobe keine neuen Anmeldungen mehr bei [!DNL Device Co-op].

## Werden bestehende Verträge verlängert?

Ab dem 11. Juni 2021 verlängert die Adobe die [!DNL Device Co-op]-Verträge nicht mehr. Wenn Sie weiterhin [!DNL Device Co-op] Dienste verwenden möchten, können Sie dies unter den aktuellen Lizenzbedingungen bis zum Ende des Programms tun.

## Wie ist das genaue Enddatum des [!DNL Device Co-op]-Programms?

Das Programm [!DNL Device Co-op] wird 2022 auslaufen. Der genaue Zeitpunkt und das genaue Datum hängen davon ab, wann [!DNL Google] beginnt, Drittanbieter-Cookies zu blockieren.

## Welche Anwendungen sind vom Ende der Gerätekooperation betroffen?

Die folgenden Anwendungen sind von den Verfahren zum Ende der Lebensdauer von [!DNL Device Co-op] betroffen:

- [Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=en)
- [Adobe Audience Manager](https://experienceleague.adobe.com/docs/audience-manager/user-guide/overview/aam-overview.html?lang=en)
- [Adobe Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud.html?lang=en)
- [Adobe Target](https://experienceleague.adobe.com/docs/target/using/introduction/intro.html?lang=en)

## Welche Optionen habe ich als Alternative zu [!DNL Device Co-op]?

### [!DNL Analytics]

Sie können die Funktion [!DNL Analytics] [Cross-Device Analytics (CDA)](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html) verwenden, da sie sowohl den Adobe Experience Platform Identity-Dienst [Private Graph](https://experienceleague.adobe.com/docs/analytics/components/cda/device-graph.html?lang=en) als auch [Feldbasiertes Stitching](https://experienceleague.adobe.com/docs/analytics/components/cda/field-based-stitching.html?lang=en) unterstützt.

### [!DNL Audience Manager]

[!DNL Audience Manager] verwaltet Integrationen mit Drittanbieter-Gerätediagrammpartnern, einschließlich  [!DNL LiveRamp] und  [!DNL Tapad], obwohl Sie Geschäftsbeziehungen mit Diagrammpartnern direkt herstellen müssen, um  [!DNL Audience Manager]nutzen zu können.

### [!DNL Real-time Customer Data Platform]

Es gibt keine Pläne, die aktuelle [!DNL Audience Manager Data Management Platform] (DMP) zu ändern. Die Einstellung von Drittanbieter-Cookies führt jedoch wahrscheinlich zu großen Herausforderungen für die meisten DMP-Benutzer. Um Kunden bei der Weiterentwicklung ihrer Datenverwaltungspraktiken zu unterstützen, fördert die Adobe die Verringerung der Abhängigkeiten von Kennungen, die im kommenden Jahr Beschränkungen unterliegen. Marketing-Teams müssen Erstanbieter-Datenstrategien entwickeln, die auf dauerhafte Kennungen ausgerichtet sind, die persönlich identifizierbare Informationen (PII) enthalten, die mit [!DNL Real-time Customer Data Platform] (Echtzeit-Kundendatenplattform) gelöst werden können.

[!DNL Real-time CDP] verringert Abhängigkeiten von Drittanbieter-Cookies und Geräte-IDs, indem der Satz von Identifikatoren erweitert wird, die für die Zielgruppenerstellung verfügbar sind, um personenbezogene Daten einzuschließen. Grundlage für [!DNL Real-time CDP] ist das Echtzeit-Kundenprofil, das personenbezogene Attributdaten mit Verhaltensdaten in Echtzeit kombiniert und es Marketing-Experten ermöglicht, umfassende Zielgruppensegmente mit patentierten Data Governance-Kontrollen zu erstellen. Wie [!DNL Audience Manager] ermöglicht [!DNL Real-time CDP] Einblicke und Personalisierungsfälle, generiert aber auch granularere Einblicke auf der Ebene der Person und kann Zielgruppen für eine breitere Palette von Zielen aktivieren, die Werbetechnologien und Marketingtechnologien umfassen, darunter Paid Media, Social Media, E-Mail und Kundensysteme.

[!DNL Real-time CDP] umfasst auch den Zugriff auf  [Adobe Experience Platform Segment Match (Alpha)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match.html?lang=en), wodurch Marken ihre eigenen Erstanbieter-Datensätze durch Partnerschaften erweitern und bessere Einblicke und Personalisierung erzielen können.

### [!DNL Target]

Für [!DNL Target] sind derzeit keine Alternativen verfügbar, da [!DNL Target] eine deterministische geräteübergreifende Identitätszuordnungsfunktion namens `mbox3rdPartyId` bietet, die ähnlich wie die Kunden-ID der Adobe funktioniert. Mit dieser Funktion können [!DNL Target]-Kunden Profile und Aktivitätsteilnehmer über [!DNL Target]-Tests hinweg zusammenführen und Personalisierungen in eingehenden Kanälen durchführen.

### Adobe Advertising Cloud

[!DNL Advertising Cloud] -Kunden können nicht mehr  [!DNL Device Co-op] für geräteübergreifendes Zielgruppen-Targeting und -Messungen verwenden. Mit [!DNL Advertising Cloud] können Sie weiterhin die [!DNL Device Graph]-Partnerschaft der Adobe mit [!DNL LiveRamp] nutzen, um diese Funktionen im Umfang von [!DNL LiveRamp’s] Fähigkeiten und Skalierung weiter auszuführen. Sie müssen zulassen, dass Ihre Kampagnen, die [!DNL Device Co-op] verwenden, enden und dann entweder zum [!DNL LiveRamp]-Gerätediagramm-Provider wechseln oder das personenbasierte Targeting nicht mehr nutzen.

## Welche vorhandenen Funktionen und Implementierungen können mir bei der Vorbereitung auf eine Zukunft ohne Cookies helfen?

Ihre vorhandene Besucher-ID-Service-Implementierung unterstützt Analytics [CDA](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html). Wenn es sich bei Ihrer vorhandenen deklarierten ID um eine Hash-E-Mail handelt, kann dies für die folgenden Funktionen verwendet werden:

- [!DNL Audience Manager] [Benutzerbezogene Ziele](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html).
- [Experience Platform Segment Match (Alpha) ](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match.html?lang=en).

## Kann ich meine Daten von [!DNL Device Co-op] beibehalten?

Für Benutzer von [!DNL Audience Manager] und [!DNL Advertising Cloud] sind die Daten von [!DNL Device Co-op] nicht verfügbar, um sie in Diagrammen von Drittanbietern zu übertragen. [!DNL Device Co-op] -Daten werden nur für  [!DNL Analytics Ultimate] Benutzer migriert, die die geräteübergreifende Analyse verwenden und  [!DNL Device Co-op] zu feldbasierter Zuordnung wechseln. Bei allen anderen Lösungen werden ihre Daten nicht migriert.

## Ist es obligatorisch, andere Funktionen zu übernehmen?

Auch wenn die Übernahme anderer Funktionen der Adobe nicht obligatorisch ist, sollten Sie so bald wie möglich mit der Implementierung anderer Funktionen beginnen, um Zeit und eine angemessene Koordinierung vor der Einstellung von [!DNL Device Co-op] zu ermöglichen.

## Wann muss ich alternative Lösungen wählen, wenn ich mich dafür entscheide?

Die Übernahme anderer Funktionen ist nicht obligatorisch. Es wird nur empfohlen, weiterhin Anwendungsfälle zu bearbeiten, die von [!DNL Device Co-op] bearbeitet wurden. Wenn Sie sich für die Übernahme anderer Funktionen entscheiden, müssen Sie dies bis 2022 (genauer Zeitpunkt anzugeben) tun, bevor das [!DNL Device Co-op] Programm endet.

## Wie lange wird die Annahme dauern?

Dies hängt von der Funktion ab. Wenn beispielsweise ein Analytics Ultimate-Kunde, der geräteübergreifende Analysen mit [!DNL Device Co-op] verwendet, zu Echtzeit-Diagrammen für private Geräte oder feldbasiertem Stitching migrieren muss, dauert die Übernahme einige Zeit.
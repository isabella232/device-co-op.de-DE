---
description: Wenn eine Person über Geräte verfügt, die nicht zur Interaktion mit Ihrer Marke verwendet werden, werden diese Geräte als unbekannte Geräte bezeichnet.
seo-description: When a person has devices that are not used to interact with your brand, those devices are called unknown devices.
seo-title: Unknown devices
title: Unbekannte Geräte
uuid: 18e69dad-bdb3-4ac1-a690-374aba1aa0a6
exl-id: 7841bf32-7327-4981-86a2-600e2bfe5901
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '227'
ht-degree: 0%

---

# Unbekannte Geräte{#unknown-devices}

Wenn eine Person über Geräte verfügt, die nicht zur Interaktion mit Ihrer Marke verwendet werden, werden diese Geräte als unbekannte Geräte bezeichnet.

## Unbekannte Gerätekategorien {#section-014b83fd0f2e4d50aa19dd9fbb46f6ab}

Es gibt mehrere Möglichkeiten oder Kategorien, mit denen ein Gerät für Sie als &quot;unbekannt&quot;betrachtet werden kann. Dazu gehören:

* **Erstanbieterbesuche bei anderen Mitgliedern der Device Co-op:** Besuche bei anderen [!DNL Device Co-op] Mitglied-Sites oder Werbung für ein Gerät macht ein Gerät nicht an sich für Ihre Marke bekannt.

* **Nicht getrackter Anzeigenbestand:** Das Werbeinventar, das verfügbar, aber noch nicht bereitgestellt oder aufgenommen wurde, macht ein Gerät Ihrer Marke nicht bekannt.
* **Opt-out für Verbraucher:** Um den Wünschen der Verbraucher Rechnung zu tragen, werden Geräte, die abgemeldet wurden, nicht als bekannte Geräte betrachtet.

Im Gegensatz zu bekannten Geräten sind unbekannte Geräte nicht mit anderen Geräten verknüpft oder mit einzelnen Personen verknüpft.

## Regeln zum Festlegen des bekannten/unbekannten Status {#section-fa5c85e59e2d4f88bb79f27f17f02344}

Die [!DNL Device Graph] versucht, bei der Klassifizierung von Geräten als bekannt im Vergleich zu unbekannt so umfassend wie möglich zu sein. Die Regeln, die bei der Ermittlung des bekannten/unbekannten Status helfen, funktionieren in Prioritätsreihenfolge (1 ist die höchste), wie unten dargestellt:

* **Regel 1:** Ist das Gerät abgemeldet? Wenn ja, ist das Gerät unbekannt.
* **Regel 2:** Ist das Gerät bekannt durch *any* Methode? Wenn ja, ist das Gerät bekannt.

* **Regel 3: ** Wenn das vorherige nicht zutrifft, ist das Gerät unbekannt.

>[!MORELIKETHIS]
>
>* [Bekannte Geräte](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1)


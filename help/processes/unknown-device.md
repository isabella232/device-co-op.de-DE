---
description: Wenn eine Person Geräte hat, die nicht zur Interaktion mit Ihrer Marke verwendet werden, werden diese Geräte als unbekannte Geräte bezeichnet.
seo-description: Wenn eine Person Geräte hat, die nicht zur Interaktion mit Ihrer Marke verwendet werden, werden diese Geräte als unbekannte Geräte bezeichnet.
seo-title: Unbekannte Geräte
title: Unbekannte Geräte
uuid: 18e69dad-bdb3-4ac1-a690-374aba1aa0a6
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371
workflow-type: tm+mt
source-wordcount: '249'
ht-degree: 0%

---


# Unbekannte Geräte{#unknown-devices}

Wenn eine Person Geräte hat, die nicht zur Interaktion mit Ihrer Marke verwendet werden, werden diese Geräte als unbekannte Geräte bezeichnet.

## Unbekannte Geräte-Kategorien {#section-014b83fd0f2e4d50aa19dd9fbb46f6ab}

Es gibt mehrere Möglichkeiten oder Kategorien, ein Gerät als &quot;unbekannt&quot;zu betrachten. Dazu gehören:

* **Besuche von Erstanbietern bei anderen Device Co-op-Mitgliedern:** Besuche auf anderen  [!DNL Device Co-op] Mitgliedssites oder Anzeigen auf einem Gerät machen Ihr Gerät nicht an sich bekannt.

* **Nicht nachverfolgter Anzeigenbestand:** Werbebestand, der verfügbar, aber noch nicht bereitgestellt oder erfasst ist, macht Ihr Gerät nicht bekannt.
* **Ausschluss vom Verbraucher:** Um den Wünschen der Verbraucher Rechnung zu tragen, werden Geräte, die ausgeschaltet wurden, nicht als bekannte Geräte betrachtet.

Im Gegensatz zu bekannten Geräten werden unbekannte Geräte nicht mit anderen Geräten verknüpft oder mit einzelnen Personen verknüpft.

## Regeln zum Festlegen des bekannten/unbekannten Status {#section-fa5c85e59e2d4f88bb79f27f17f02344}

Das [!DNL Device Graph] versucht, bei der Klassifizierung von Geräten als unbekannt im Vergleich zu unbekannt möglichst inklusiv zu sein. Die Regeln, die bei der Bestimmung des bekannten/unbekannten Status helfen, funktionieren in der Prioritätsreihenfolge (1 ist am höchsten), wie unten dargestellt:

* **Regel 1:** Ist das Gerät abgeschaltet? Wenn ja, ist das Gerät unbekannt.
* **Regel 2:** Ist das Gerät  ** irgendwie bekannt? Wenn ja, dann ist das Gerät bekannt.

* **Artikel 3: ** Wenn das vorherige nicht zutrifft, ist das Gerät unbekannt.

>[!MORELIKETHIS]
>
>* [Bekannte Geräte](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1)


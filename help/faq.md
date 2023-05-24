---
description: Antworten auf häufige Fragen zur Device Co-op (Identity Services Cooperative und Identity Graph).
title: Häufig gestellte Fragen zur Device Co-op
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
exl-id: 6511e247-76a7-4960-944c-b49fd046fb28
source-git-commit: 399a4fe2d34957eafe8c4eebed465df8770a9239
workflow-type: tm+mt
source-wordcount: '477'
ht-degree: 1%

---

# Häufig gestellte Fragen{#faq}

Beschreibungen und Antworten auf häufig gestellte Fragen zur Identity Services-Genossenschaft und zum Identitätsdiagramm.

**Was ist das [!DNL Device Co-op]?**

Die Device Co-op ist eine digitale Kooperation für teilnehmende Adobe Experience Cloud-Kunden, die zusammenarbeiten können, um ihre Kunden geräteübergreifend besser zu identifizieren.

**Welche Technologien werden in der Device Co-op verwendet?**

Die Device Co-op besteht aus zwei Technologien:

* **Experience Cloud-ID-Dienst:** Dieser Hauptdienst von Adobe Experience Cloud bietet eine allgemeine ID zur konsistenten Identifizierung von Verbrauchern über Lösungen, Kanäle, Erlebnisse und Geräte hinweg.
* **Adobe Experience Cloud Device Co-op:** Diese Technologie verbindet verschiedene Geräte, die von einem Verbraucher oder Haushalt verwendet werden.

**Wie funktioniert das [!DNL Device Co-op] arbeiten?**

Während Marken durch anonymisierte Anmeldungen und Site-Besuche in ihrem Teil des geräteübergreifenden Puzzles auftreten, verarbeitet Adobe diese Daten zu Geräteclustern, die eine von einer unbekannten Person verwendete Gerätegruppe darstellen. Diese Gerätecluster werden an Mitglieder der Device Co-op übergeben und dienen dazu, ihren Kunden ein besseres, konsistenteres geräteübergreifendes Erlebnis zu bieten.

**Wie funktioniert das [!DNL Device Co-op] Verknüpfungsgeräte?**

Siehe [Deterministische und probabilistische Verknüpfungen](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931).

**Welche Daten stellen die Teilnehmer bereit? [!DNL Adobe]?**

Siehe [Opt-out-Tool für Verbraucher, Datenschutz und Gerätediagramm](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be).

**Welche Daten werden freigegeben zwischen [!DNL Device Co-op] Mitglieder?**

Siehe [Linkfreigabe im Gerätediagramm](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf).

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**Kann eine [!DNL Device Co-op] Mitglied sehen Links zu Geräten, die sie noch nie zuvor gesehen haben?**

Nein. Mitglieder der Device Co-op können nur Daten auf Grundlage von Geräten erhalten, die eine der Web-Eigenschaften ihrer Marke besucht haben. Siehe [Bekannte Geräte](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) und [Unbekannte Geräte](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).

**Muss ich Marketing-Informationen meines Unternehmens freigeben?**

Nein. Marken liefern nur anonyme Gerätedaten an Adobe.

**Does [!DNL Adobe] persönlich identifizierbare Informationen (PII) im [!DNL Device Co-op]?**

Nein. Alle personenbezogenen Daten werden gehasht, bevor sie in ein Adobe-System übertragen werden, sodass die Kundeninformationen nie an Adobe-Systeme übertragen werden.

**Erhalten kleinere Marken, die weniger Gerätedaten zur Device Co-op beitragen, mehr Wert als sie einbringen, verglichen mit ihren größeren Kollegen?**

Nein. Alle Mitglieder der Genossenschaft erhalten einen Wert, der relativ zu dem ist, was sie einsetzen. Wenn beispielsweise eine Marke 10.000 Geräte einbringt, können sie zusätzliche verknüpfte Geräteinformationen erhalten, die mit diesen 10.000 Geräten verknüpft sind. Betrachtet man das Gesamtbild, so könnte dieser Beitrag minimal erscheinen. aber da immer mehr Marken aller Größen miteinander verbunden werden, ist der aggregierte Beitrag von Bedeutung und wird die fehlende Verknüpfung für viele Geräte bereitstellen, nach denen viele andere, vielleicht größere Marken suchen. Siehe [Fairness und bekanntes Gerät](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8).

**Wie wird [!DNL Adobe] IP-Adressen verwalten, wenn einige Länder eine IP-Adresse als persönliche Informationen betrachten?**

Die Device Co-op wird erstmals in den USA und Kanada veröffentlicht, wo IP-Adressen nicht als personenbezogene Daten betrachtet werden. Wenn die Genossenschaft in Ländern veröffentlicht wird, in denen IP-Adressen als persönliche Informationen gelten, wird die IP-Adresse nicht verwendet.

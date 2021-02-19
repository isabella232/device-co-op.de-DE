---
description: Informationen zur Linkfreigabe im Gerätediagramm.
seo-description: Informationen zur Linkfreigabe im Gerätediagramm.
seo-title: Linkfreigabe im Gerätediagramm
title: Linkfreigabe im Gerätediagramm
uuid: 6c7202f0-c6d9-48a4-82ad-ee57d7a518a0
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031
workflow-type: tm+mt
source-wordcount: '557'
ht-degree: 0%

---


# Linkfreigabe im Gerätediagramm{#link-sharing-in-the-device-graph}

Informationen zur Linkfreigabe im Gerätediagramm.

Die [!DNL Device Graph] weist deterministische und probabilistische Verbindungen mit verschiedenen Mitgliedern der Adobe Experience Cloud Device Co-op auf. Die Linkfreigabe macht das [!DNL Device Co-op] so leistungsstark. Es erweitert, was jedes Mitglied über die Geräte, die mit einer anonymen Person verbunden sind, weiß, aber nur, wenn Sie mindestens eines der Geräte dieser anonymen Person zuvor gesehen haben.

## Übersicht zum Gerätediagramm {#section-7858e9f61b5644c981ffb53626fcc19d}

Bevor wir beginnen, sollten wir uns einen Moment Zeit nehmen, um zu überprüfen, wie [!DNL Device Graph] funktioniert. Mitglieder von [!DNL Device Co-op] senden Daten an das [!DNL Device Graph]. [!DNL Device Graph] verwendet diese Daten, um die Identität einer Person aus [deterministischen und wahrscheinlichen Verknüpfungen](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931) zwischen Geräten zu erstellen. Als [!DNL Device Co-op]-Teilnehmer bieten diese Links einen Einblick in die Beziehung zwischen Ihren authentifizierten Benutzern, anderen Benutzern und ihren Geräten. Schauen wir uns an, wie das im folgenden Abschnitt funktioniert.

## Beispiel für die Linkfreigabe {#section-cb410d827cf14f76bc9b0bd4d31ed767}

Das folgende Beispiel zeigt die Macht der Linkfreigabe im Device Co-op. In diesem Beispiel haben wir 2 fiktive Firmen, die News-Firma und die Finance-Firma. Beide Firmen sind Mitglieder von [!DNL Device Co-op]. Person A ist ein Verbraucher, der sich auf mehreren Geräten anmeldet oder die Websites jeder Firma durchsucht.

![](assets/share1.png)

Da sich Person A mit ihrem Handy und Tablet auf der News-Site authentifiziert hat, identifiziert die News-Firma sie mit einer Kunden-ID. Diese ID wird als kryptografischer Hash an [!DNL Device Graph] gesendet. Die Finance-Firma hat diese Geräte bereits gesehen, aber Person A hat sich nicht bei der Site angemeldet. Folglich weiß die Finance-Firma nicht, ob oder wie diese Geräte miteinander in Beziehung stehen oder wie sie mit Person A verbunden sind.

![](assets/share2.png)

Angesichts des kryptografischen Hashs der Consumer-ID erkennt das [!DNL Device Graph], dass diese Geräte miteinander und mit einer bestimmten Person verwandt sind. Firmen, die nicht am [!DNL Device Co-op] teilnehmen, scheinen diese Site-Besuche von separaten, zufälligen Geräten zu stammen. In jedem Fall gilt Folgendes, sobald [!DNL Device Graph] die Hash-ID hat:

* Wissen, dass Mobiltelefon und Laptop miteinander verbunden sind.
* erkennt an, dass die Finance-Firma wissen möchte, ob das Mobiltelefon und der Laptop verknüpft sind.

Unter diesen Umständen gibt das [!DNL Device Graph] nun den Link frei, der diese Geräte für die News-Firma mit der Finance-Firma verbindet. Während dieses Vorgangs werden die [!DNL Device Graph]-Duplikat und die Links von einem Co-op-Mitglied zum anderen freigegeben.

![](assets/share3.png)

An dieser Stelle hat das [!DNL Device Graph] seine Rolle erfolgreich ausgeführt. Sowohl die News-Firma als auch die Finance-Firma haben ein klares Bild einer Identität. Sie können Person A auf allen ihren Geräten genau erreichen.

## Datenschutz und Linkfreigabe {#section-7b566018b3304420a4b3e4c079826110}

Die Wahrung der Privatsphäre und Datenintegrität von [!DNL Device Co-op]-Mitgliedern ist während des gesamten Linkaustausches von entscheidender Bedeutung. Während dieses Prozesses zur Kundenidentifizierung und Linkfreigabe hat [!DNL Device Graph] nicht:

* Teilen Sie der Finance-Firma mit, dass der Link aus der News-Firma stammt.
* Geben Sie die von einem [!DNL Device Co-op]-Mitglied verwendete Kunden-ID für ein anderes Mitglied frei.
* Geben Sie alle anderen Informationen als die Informationen an, über die das Mobilgerät und der Laptop einen Link gemeinsam nutzen.

## Nächste Schritte {#section-ac6e61f1eb6e45b1bb4be8ece39147c7}

Das Lesen der Dokumentation zu Identität, Verknüpfung und Linkfreigabe sollte Ihnen einen guten Eindruck davon vermitteln, wie [!DNL Device Graph] Daten intern zusammenstellt. Als nächsten Schritt empfehlen wir Ihnen, sich unsere Dokumentation anzusehen, in der beschrieben wird, wie das Konzept eines *`known device`* geräteübergreifende Links zu Device Co-op-Mitgliedern bereitstellt. Siehe [Bekannte Geräte](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) und [Unbekannte Geräte](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).

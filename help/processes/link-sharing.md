---
description: Informationen zur Linkfreigabe im Gerätediagramm.
seo-description: Informationen zur Linkfreigabe im Gerätediagramm.
seo-title: Linkfreigabe im Gerätediagramm
title: Linkfreigabe im Gerätediagramm
uuid: 6c7202f0-c6d9-48a4-82ad-ee57d7a518a0
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Link sharing in the Device Graph{#link-sharing-in-the-device-graph}

Informationen zur Linkfreigabe im Gerätediagramm.

The [!DNL Device Graph] shares deterministic and probabilistic links with different members of the Adobe Experience Cloud Device Co-op. Link sharing is what makes the [!DNL Device Co-op] so powerful. Sie vergrößert das Wissen aller Teilnehmer über die mit einer anonymen Person verbundenen Geräte, aber nur, wenn Sie mindestens eins der von dieser anonymen Person verwendeten Geräte zuvor gesehen haben.

## Device Graph summary review {#section-7858e9f61b5644c981ffb53626fcc19d}

Before getting started, let&#39;s take a moment to review how the [!DNL Device Graph] works. Mitglieder des [!DNL Device Co-op] Senders senden Daten an die [!DNL Device Graph]. Die [!DNL Device Graph] nutzt diese Daten, um die Identität einer Person aus [deterministischen und wahrscheinlichen Verbindungen](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931) zwischen Geräten zu konstruieren. Als Teilnehmer der [!DNL Device Co-op] bieten Ihnen diese Verknüpfungen Einblicke über die Beziehung zwischen Ihren authentifizierten Benutzern, anderen Benutzern und deren Geräten. Sehen wir uns im untenstehenden Abschnitt an, wie das funktioniert.

## Link sharing example {#section-cb410d827cf14f76bc9b0bd4d31ed767}

Das folgende Beispiel veranschaulicht die Macht der Linkfreigabe in der Device Co-op. In diesem Beispiel haben wir 2 fiktive Unternehmen, das Nachrichtenunternehmen und das Finanzunternehmen. Both companies are members of the [!DNL Device Co-op]. Person A ist ein Verbraucher, der sich sich auf den Webseiten beider Unternehmen über mehrere Geräte anmeldet oder darauf surft.

![](assets/share1.png)

Weil Person A sich mit Mobiltelefon und Tablet auf der Nachrichtenseite authentifiziert hat, identifiziert das Nachrichtenunternehmen sie mit einer Verbraucher-ID. It sends that ID to the [!DNL Device Graph] as a cryptographic hash. Das Finanzunternehmen hat diese Geräte zuvor gesehen, aber Person A hat sich nicht auf der Seite angemeldet. Somit weiß das Finanzunternehmen nicht, ob oder wie diese Geräte miteinander in Verbindung stehen oder wie sie mit Person A zusammenhängen.

![](assets/share2.png)

Given the cryptographic hash of the consumer ID, the [!DNL Device Graph] recognizes that these devices are related to each other and a particular person. Für Firmen, die nicht an der [!DNL Device Co-op] teilnehmen, würden diese Seitenbesuche scheinbar von separaten, zufälligen Geräten kommen. In any case, once the [!DNL Device Graph] has the hashed ID it:

* Weiß, dass Mobiltelefon und Laptop zusammenhängen.
* Erkennt, dass das Finanzunternehmen wissen möchte, ob das Mobiltelefon und der Laptop zusammenhängen.

Given these conditions, the [!DNL Device Graph] now shares the link connecting these devices for the News Company with the Finance Company. During this process, the [!DNL Device Graph] duplicates and shares the link from one co-op member to another.

![](assets/share3.png)

At this point, the [!DNL Device Graph] performed its role successfully. Sowohl das Nachrichtenunternehmen als auch das Finanzunternehmen haben ein klares Bild einer Identität. Beide können Person A zielgenau über sämtliche Geräte erreichen.

## Privacy and link sharing {#section-7b566018b3304420a4b3e4c079826110}

Die Wahrung der Privatsphäre der Verbraucher und der Datenintegrität für Mitglieder der [!DNL Device Co-op] ist während des gesamten Vorgangs der Linkfreigabe ein wesentliches Ziel. During this customer identification and link sharing process the [!DNL Device Graph] did not:

* Dem Finanzunternehmen mitgeteilt, dass die Verknüpfung vom Nachrichtenunternehmen kommt.
* Die von einem Mitglied der [!DNL Device Co-op] verwendete Kunden-ID mit einem anderen geteilt.
* Andere Informationen weitergegeben, abgesehen von der Information, dass das Mobilgerät und der Laptop eine gemeinsame Verknüpfung haben.

## Nächste Schritte {#section-ac6e61f1eb6e45b1bb4be8ece39147c7}

Reading the documentation on identity, linking, and link sharing should give you a good sense of how the [!DNL Device Graph] assembles data internally. Als nächsten Schritt empfehlen wir Ihnen, sich unsere Dokumentation anzusehen, in der beschrieben wird, wie das Konzept einer *`known device`* geräteübergreifenden Verknüpfung zu Device Co-op-Mitgliedern bereitgestellt wird. Siehe [Bekannte Geräte](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) und [unbekannte Geräte](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).

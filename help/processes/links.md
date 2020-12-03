---
description: So analysiert das Gerätediagramm deterministische und wahrscheinliche Daten, um eine Karte zu erstellen, die Geräte miteinander verknüpft.
seo-description: So analysiert das Gerätediagramm deterministische und wahrscheinliche Daten, um eine Karte zu erstellen, die Geräte miteinander verknüpft.
seo-title: Bestimmte und wahrscheinliche Verbindungen
title: Bestimmte und wahrscheinliche Verbindungen
uuid: 00693a0a-f73d-460d-84a4-b7c745b9fe0a
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031
workflow-type: tm+mt
source-wordcount: '866'
ht-degree: 0%

---


# Bestimmte und wahrscheinliche Verbindungen{#deterministic-and-probabilistic-links}

So analysiert das Gerätediagramm deterministische und wahrscheinliche Daten, um eine Karte zu erstellen, die Geräte miteinander verknüpft.

In den [!DNL Device Graph]internen Prozessen wird eine Identitätshierarchie erstellt, die Geräte zuordnet und sie mit einzelnen, anonymisierten Personen verbindet. Die Ausgabe des Diagramms enthält geräteübergreifende Links, die Sie zum Targeting verwenden können, zusammen mit Daten, die in ausgewählten Experience Cloud-Lösungen bereitgestellt werden. Zu den Adoben, die mit [!DNL Device Graph] Daten arbeiten, zählen Analytics, Audience Manager, Media Optimizer und Zielgruppe.

Die [!DNL Device Graph] Analyse deterministischer und wahrscheinlicher Daten, um eine Karte zu erstellen, die Geräte miteinander verknüpft. Bestimmte Daten verbinden Geräte auf der Grundlage von Hash-Anmeldedaten. Wahrscheinliche Daten verknüpfen Geräte auf der Grundlage von Informationen wie IP-Adressen und anderen Metadaten. Die [!DNL Device Graph] verknüpften Geräte-Cluster werden einer anonymen Einzelperson zugeordnet. Diese Verbindungen ermöglichen es E-Marketingexperten, Personen anstelle von Geräten zu erreichen. In der [!DNL Device Graph]ist der Besitzer eines Geräts die anonyme Darstellung einer echten Person. Sowohl deterministische als auch probabilistische Links helfen dabei, eine Struktur der Benutzeridentität aufzubauen.

>[!NOTE]
>
>In der Adobe Experience Cloud Device Co-op haben Begriffe wie *Geräte*, *Personen* und *Identitäten* eine bestimmte Bedeutung. Beispielsweise kann sich das *Gerät* auf physische Hardware wie Smartphone oder Tablet und auf die Anwendungen beziehen, die auf dieser Hardware ausgeführt werden. Definitionen finden Sie im [Glossar](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) .

## Was sind Links? {#section-2df4c6f01eba49369993146df0661f13}

Wenn wir über Links sprechen, ist es wichtig, zu bedenken, was diese wirklich im Kontext des [!DNL Experience Cloud] Gerätediagramms sind. In diesem Zusammenhang sind Links keine physischen Verbindungen zwischen Geräten. Stattdessen wird über einen Link angegeben, wie das Gerätediagramm verschiedene Geräte derselben unbekannten Person zuordnet. Angenommen, wir haben ein Mobiltelefon und einen Desktop-Browser. Telefon und Browser können als &quot;verknüpft&quot;betrachtet werden, sobald das Gerätediagramm feststellt, dass beide Geräte von derselben unbekannten Person verwendet werden. Wie Sie unten lesen werden, erstellt das Gerätediagramm Identitäten mit deterministischen und wahrscheinlichen Links. Und im Gerätediagramm ist der Besitzer eines Geräts die anonyme Darstellung einer echten Person.

## Bestimmte Links {#section-33d41e828a674b398e36fe63da20ac09}

Bestimmte Verbindungen verbinden ein Gerät mit einer Person, die auf einem Authentifizierungs-Ereignis basiert (z. B. eine Anmeldeaktion von einem Gerät zu einer Site). Diese Aktion erstellt einen anonymisierten Bezeichner, der als Kunden-ID bezeichnet wird. Schauen wir uns einmal an, wie deterministisches Verknüpfen funktioniert. In diesem Beispiel meldet sich Person A über eine App auf ihrem Mobilgerät bei einer News-Site an. Später an diesem Tag meldet sich Person A wieder an, aber diesmal durch einen Browser auf ihrem Laptop.

![](assets/link1.png)

Basierend auf den Anmeldeinformationen wird das Gerätediagramm angezeigt:

* Weist nach, dass sich Person A mit einer Kombination aus Mobiltelefon/App und Laptop/Browser auf der News-Site authentifiziert hat.
* Verknüpft diese Geräte mit Person A.
* Erstellt eine Identität basierend auf verknüpften Geräten, die mit einer anonymen Person verknüpft sind.

![](assets/link2.png)

>[!NOTE]
>
>Weder die [!DNL Adobe Experience Cloud Device Co-op] oder die [!DNL Device Graph] Empfänger erhalten in diesen Daten tatsächliche Authentifizierungsinformationen oder persönlich identifizierbare Informationen (PII). Mitglieder des [!DNL Experience Cloud Device Co-op]können kryptografische Hash-IDs an das Gerätediagramm übergeben. Die Kunden-ID stellt einen authentifizierten Benutzer im Diagramm dar und schützt die Privatsphäre der Verbraucher.

## Potenzielle Links {#section-5f5aa755da984f9d851f7cb380262998}

Wahrscheinliche Links verbinden ein Gerät mit einer Person algorithmisch, basierend auf Eigenschaften und Metadaten wie:

* Browsing-Verhalten
* IP-Adressen
* Betriebssysteme
* IDFA- und GAID-Kennungen

Schauen wir uns einmal an, wie wahrscheinliche Verknüpfungen funktionieren. In diesem Beispiel navigiert Person A zu einer News-Site auf ihrem Tablet und dann später von einem Desktop-Computer. Während des Browsens meldet sich Person A nicht bei der News-Site an. Bei jedem separaten Besuch verwenden Tablets und Desktop dieselbe IP-Adresse.

![](assets/link3.png)

Auf der Grundlage dieser Informationen bewertet die [!DNL Device Graph] Kommission die Muster für die Freigabe von IP-Adressen zwischen beiden Geräten und verknüpft diese Geräte miteinander, wenn die Ergebnisse darauf hindeuten, dass sie zu Person A gehören. Das Endergebnis ist die Hierarchie der Identität, die aus algorithmischen Wahrscheinlichkeitsberechnungen abgeleitet wird.

![](assets/link4.png)

In diesem Beispiel verknüpfte das Gerätediagramm beide Geräte, nachdem sie für den Zugriff auf dieselbe News-Site verwendet wurden. Aber Geräte müssen nicht auf der gleichen Website gesehen werden, um verknüpft werden. Um dies zu veranschaulichen, lassen Sie uns sagen, dass jedes Gerät in diesem Beispiel komplett verschiedene Websites besucht. Der [!DNL Device Graph] Algorithmus kann weiterhin einen wahrscheinlichen Link erstellen, der auf ihrer gemeinsamen IP-Adresse und einer Analyse anderer Daten basiert. Dieser Prozess hilft den Mitgliedern der [!DNL Experience Cloud] Device Co-op eine wahrscheinlichste Verknüpfung zu ermöglichen.

## Beide Datentypen bieten einen Wert {#section-43d22d8c10634edcb261e7bda6fdf323}

Bestimmte und wahrscheinliche Daten ergänzen sich gegenseitig. Im Gegensatz dazu gibt Ihnen ein Gerätediagramm, das nur deterministische Daten enthält, eine begrenzte Ansicht der Identität einer Person. Ohne Authentifizierung kann ein Gerätediagramm keine Informationen über andere Geräte und Personen anzeigen, die Ihre Site durchsuchen. Wahrscheinliche Daten können diese Verbindungen herstellen und Ihnen dabei helfen, nicht authentifizierte Geräte, Personen und Haushalte zu erreichen.

Auch deterministische Daten sind wichtig. Sie kann beispielsweise die wahrscheinliche Entscheidungsfindung verbessern, indem sie falsche Links entfernt, die an Orten entstehen, an denen wahrscheinlichste Signale reichlich und sich überschneiden (z. B. Cafés, Bibliotheken, Flughäfen usw.).

Bei beiden Datentypen gibt Ihnen das Gerätediagramm ein umfassenderes Bild der Identität einer Person als bei beiden Typen.

![](assets/link5.png)


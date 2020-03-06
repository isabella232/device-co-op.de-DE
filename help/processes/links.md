---
description: So analysiert das Gerätediagramm deterministische und wahrscheinliche Daten, um eine Karte zu erstellen, die Geräte miteinander verknüpft.
seo-description: So analysiert das Gerätediagramm deterministische und wahrscheinliche Daten, um eine Karte zu erstellen, die Geräte miteinander verknüpft.
seo-title: Bestimmte und wahrscheinliche Verbindungen
title: Bestimmte und wahrscheinliche Verbindungen
uuid: 00693a0a-f73d-460d-84a4-b7c745b9fe0a
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Deterministic and probabilistic links{#deterministic-and-probabilistic-links}

So analysiert das Gerätediagramm deterministische und wahrscheinliche Daten, um eine Karte zu erstellen, die Geräte miteinander verknüpft.

In the [!DNL Device Graph], internal processes build an identity hierarchy that maps devices and connects them to individual, anonymized people. Die Ausgabe des Diagramms enthält geräteübergreifende Links, die Sie zum Targeting zusammen mit Daten verwenden können, die in ausgewählten Experience Cloud-Lösungen verfügbar sind. The Adobe solutions that work with [!DNL Device Graph] data include Analytics, Audience Manager, Media Optimizer, and Target.

The [!DNL Device Graph] analyzes deterministic and probabilistic data to build a map that links devices together. Deterministische Daten verbinden Geräte anhand von Hash-Anmeldeinformationen miteinander. Probabilistische Daten verbinden Geräte anhand von Informationen wie IP-Adressen und anderen Metadaten miteinander. The [!DNL Device Graph] associates the linked device clusters to an anonymous individual person These connections let digital marketers reach people instead of devices. In the [!DNL Device Graph], the owner of a device is the anonymous representation of a real-life person. Sowohl deterministische als auch probabilistische Verknüpfungen helfen dabei, eine Benutzeridentitätenstruktur aufzubauen.

>[!NOTE]
>
>In der Adobe Experience Cloud-Gerätekooperation haben Begriffe wie *Gerät*, *Person* und *Identität* eine bestimmte Bedeutung. For example, *device* can refer to physical hardware such as a phone or tablet and the applications that run on that hardware. Definitionen finden Sie im [Glossar](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c).

## What are links? {#section-2df4c6f01eba49369993146df0661f13}

Es ist wichtig, sich beim Thema „Verknüpfungen“ vor Augen zu halten, was diese im Kontext eines [!DNL Experience Cloud]-Gerätediagramms eigentlich sind. In diesem Kontext ist eine Verknüpfung keine physische Verbindung zwischen Geräten. Vielmehr bezeichnet „Verknüpfung“ die Art und Weise, wie das Gerätediagramm verschiedene Geräte derselben unbekannten Person zuordnet. Sagen wir beispielsweise, wir haben ein Mobiltelefon und einen Desktop-Browser. Das Mobiltelefon und der Browser können als „verknüpft“ bezeichnet werden, wenn das Gerätediagramm ermittelt, dass beide Geräte von derselben unbekannten Person verwendet werden. Wie Sie weiter unten sehen werden, erstellt das Gerätediagramm über deterministische und probabilistische Verknüpfungen Identitäten. Im Gerätediagramm ist der Besitzer eines Geräts der anonyme Vertreter einer realen Person.

## Deterministic links {#section-33d41e828a674b398e36fe63da20ac09}

Deterministische Verknüpfungen ordnen ein Gerät basierend auf einem Authentifizierungsereignis einer Person zu (zum Beispiel ein Anmeldevorgang auf einer Seite von einem Gerät aus). Diese Aktion erstellt eine anonymisierte Kennung, die Verbraucher-ID. Sehen wir uns an, wie deterministische Verknüpfungen funktionieren. In diesem Beispiel meldet sich Person A über eine App auf ihrem mobilen Gerät bei einer Nachrichtenseite an. Noch am selben Tag meldet Person A sich erneut an, aber diesmal über einen Browser auf dem Laptop.

![](assets/link1.png)

Basierend auf den Anmeldeinformationen tut das Gerätediagramm Folgendes:

* Weiß, dass Person A sich mit der Gerätekombination Mobiltelefon/App und Laptop/Browser auf der Nachrichtenseite authentifiziert hat.
* Verknüpft diese Geräte mit Person A.
* Erstellt eine Identität basierend auf verknüpften Geräten, die mit einer anonymen Person verbunden sind.

![](assets/link2.png)

>[!NOTE]
>
>Weder die [!DNL Adobe Experience Cloud Device Co-op] oder die [!DNL Device Graph] Empfänger erhalten in diesen Daten tatsächliche Authentifizierungsinformationen oder persönlich identifizierbare Informationen (PII). Members of the [!DNL Experience Cloud Device Co-op], pass in cryptographically hashed, unique consumer IDs to the Device Graph. Die Verbraucher-ID repräsentiert im Diagramm einen authentifizierten Benutzer und schützt die Privatsphäre der Verbraucher.

## Probabilistic links {#section-5f5aa755da984f9d851f7cb380262998}

Probabilistische Verknüpfungen verbinden ein Gerät über Algorithmen mit einer Person, basierend auf Eigenschaften und Metadaten wie:

* Surf-Verhalten
* IP-Adressen
* Betriebssysteme
* IDFA- und GAID-Kennungen

Sehen wir uns an, wie probabilistische Verknüpfungen funktionieren. In diesem Beispiel surft Person A auf dem Tablet auf einer Nachrichtenseite und später auf einem Desktopcomputer. Bei der Suche meldet sich Person A auf der Nachrichtenseite an. Bei jedem der Besuche teilen Tablet und Desktop eine gemeinsame IP-Adresse.

![](assets/link3.png)

Based on this information, the [!DNL Device Graph] evaluates IP address sharing patterns between both devices and links these devices together if the results suggest they belong to Person A. The end result is hierarchy of identity derived from algorithmic probability calculations.

![](assets/link4.png)

In diesem Beispiel verknüpfte das Gerätediagramm beide Geräte, nachdem sie verwendet wurden, um auf dieselbe Nachrichtenseite zuzugreifen. Jedoch müssen Geräte für eine Verknüpfung nicht auf derselben Seite gesehen werden. Um diesen Punkt zu verdeutlichen, nehmen wir an, dass mit jedem Gerät in diesem Beispiel eine völlig andere Website besucht wird. The [!DNL Device Graph] algorithm can still make a probabilistic link based on their shared IP address and from an analysis of other data. Dieser Vorgang trägt dazu bei, dass probabilistische Verknüpfungen für die Mitglieder der [!DNL Experience Cloud]-Device Co-op so leistungsstark sind.

## Both types of data provide value {#section-43d22d8c10634edcb261e7bda6fdf323}

Deterministische und probabilistische Daten ergänzen einander. Dagegen bietet ihnen ein Gerätediagramm, das lediglich deterministische Daten umfasst, nur eine begrenzte Ansicht der Identität einer Person. Ohne Authentifizierung kann ein Gerätediagramm nichts über andere Geräte und Personen aussagen, die Ihre Seite besuchen. Probabilistische Daten können diese Verbindungen herstellen und Ihnen dabei helfen, nicht authentifizierte Geräte, Personen und Haushalte zu erreichen.

Deterministische Daten sind jedoch auch wichtig. Sie können beispielsweise die probabilistische Entscheidungsfindung verbessern, indem sie falsche Verknüpfungen entfernen, die an Orten generiert wurden, an denen probabilistische Signale häufig sind und sich überschneiden (zum Beispiel Cafés, Bibliotheken, Flughäfen etc.).

Mit beiden Datentypen bietet Ihnen das Gerätediagramm ein umfassenderes Bild der Identität einer Person, als es mit nur einem der Datentypen der Fall wäre.

![](assets/link5.png)


---
description: Informationen zu bekannten Geräten im Gerätediagramm.
seo-description: Informationen zu bekannten Geräten im Gerätediagramm.
seo-title: Bekannte Geräte
title: Bekannte Geräte
uuid: 53c21105-45b1-4bed-a473-d3ccc4bae965
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371
workflow-type: tm+mt
source-wordcount: '571'
ht-degree: 1%

---


# Bekannte Geräte{#known-devices}

Informationen zu bekannten Geräten im Gerätediagramm.

Im Gerätediagramm haben wir das Konzept eines *`known device`*. Ein bekanntes Gerät ist ein Gerät, mit dem ein Kunde mit Ihrer Marke interagiert.

>[!NOTE]
>
>In den [!DNL Adobe Experience Cloud Device Co-op]-Begriffen wie *`device`*, *`person`*, *`identity`* usw. eine spezifische Bedeutung haben. &quot;Gerät&quot;kann beispielsweise auf physische Hardware wie Smartphones oder Tablets und auf Anwendungen, die auf dieser Hardware ausgeführt werden, verweisen. Definitionen finden Sie unter [Glossar](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c).

## Unterstützende Ziele mit dem bekannten Gerät {#section-80deae33660e4280ac65c659ceff5601}

Das bekannte Gerätekonzept unterstützt einige Ziele, die für die Erstellung und Wartung eines effektiven [!DNL Device Co-op]-Programms unverzichtbar sind. Ein bekanntes Gerät ist ein Gerät, über das ein [!DNL Device Co-op]-Mitglied aus einer Interaktion mit einem Kunden weiß (z. B. einen Site-Besuch oder durch die Verwendung einer mobilen App). Basierend auf diesen Aktionen verknüpft das [!DNL Device Graph] die bekannten Geräte eines [!DNL Device Co-op]-Mitglieds mit Geräten, die von anderen [!DNL Device Co-op]-Mitgliedern bereitgestellt wurden. Diese Links können [deterministisch oder probabilistisch](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931) sein. Davon profitieren [!DNL Device Co-op]-Mitglieder, da sie empfangen:

* Weitere Daten zu den bekannten Geräten.
* Neue Informationen zu anderen verknüpften Geräten.

![](assets/known-device.png)

Das [!DNL Device Graph] stellt keine Informationen zu Geräte-Clustern bereit, die ein Device Co-op-Mitglied nicht gesehen hat.

## Geräte-Co-op-Ziele {#section-75aea5a102d54733aae2a7c6ee9ec6c7}

Drei Hauptziele beleben das [!DNL Device Co-op]. Dazu gehören:

* **Skalierung:** Geben Sie die maximale Anzahl möglicher Links für verschiedene Anwendungsfälle frei.
* **Fairness:** Sicherstellen, dass jedes Mitglied der  [!DNL Device Co-op] Leistungen seinen Beiträgen angemessen ist.

* **Vertrauen der Verbraucher:** Beibehaltung und Stärkung des Verbrauchervertrauens, indem sichergestellt wird, dass die geräteübergreifende Erfahrung der Verbraucher Marken umfasst, die sie bereits kennen und denen sie vertrauen.

## Skalieren und das bekannte Gerät {#section-67f734109762457ca62ec306284ea082}

Die folgenden Methoden sind die gebräuchlichsten Methoden, mit denen ein Gerät als zweifelsfrei funktionierendes Gerät eingestuft wird. Bei diesen Methoden haben [!DNL Device Co-op]-Mitglieder fast immer mindestens ein bekanntes Gerät. Dies unterstützt das Ziel, allen Mitgliedern des [!DNL Device Co-op] maximale Skalierung zu bieten.

**Organisch**

* Vom Besuch eines Kunden auf Ihrer Site oder über die Verwendung Ihrer App. Dies ist eine Qualifizierung aus Erstanbieterdaten.
* Indem Sie Kunden über ein CRM-System an Bord mitnehmen.

**Marketplace**

* Segmentdaten aus Audience Marketplace erwerben.
* Beim Kauf von Daten von einem Drittanbieter.

**Werbung**

Indem sie den Bestand in einer Auktion gewinnen und eine Anzeige an ein Gerät senden. Das Gerät wird zu einem bekannten Gerät, wenn diese Anzeige ein [!DNL Audience Manager]-Pixel enthält.

## Bekannte Geräte und Fairness-Anwendungsfälle {#section-0543188729d845d6b95db70b8b25e9f8}

Mitglieder der [!DNL Device Co-op] erhalten Links entsprechend ihren Beiträgen zum [!DNL Device Graph]. Firmen, die viele Geräte zu den [!DNL Device Graph] beitragen, erhalten mehr Links als Mitglieder, die nur einige beitragen. Wir glauben, dass dies dazu beiträgt, die [!DNL Device Co-op] fair für alle Mitglieder zu machen. Schauen wir uns an, wie das mit den unten beschriebenen Groß- und Klein-Anwendungsfällen funktioniert.

**Marke A: Großes Anwendungsbeispiel**

In diesem Beispiel hat Marke A jeden Monat 100 Site-Besucher und Beginn eine neue geräteübergreifende Kampagne. Angenommen, der [!DNL Device Graph] weiß, dass alle Besucher der Marke A mit einem zusätzlichen Gerät verknüpft sind. Das bedeutet, dass Marke A weitere 100 Geräte erreichen könnte. Darüber hinaus enthält das [!DNL Device Graph] rund 200 Geräte, die miteinander verknüpft sind.

<table id="table_78C38DC522F94BC38C1DB73740C058AC"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Bekannte Geräte/Monat </th> 
   <th colname="col2" class="entry"> Verknüpfte Geräte, die von der Gerätekooperation empfangen wurden </th> 
   <th colname="col3" class="entry"> Geräte insgesamt für die Kampagne </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>100 </p> </td> 
   <td colname="col2"> <p>100 </p> </td> 
   <td colname="col3"> <p>200 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Marke B: Kleinbuchstabe**

In diesem Beispiel hat Marke B jeden Monat 100 Site-Besucher und Beginn eine neue geräteübergreifende Kampagne. Angenommen, die [!DNL Device Graph] wissen, dass alle Besucher der Marke B mit 50 zusätzlichen Geräten verknüpft sind. Das bedeutet, dass Marke B 150 Geräte erreichen könnte. Darüber hinaus enthält das [!DNL Device Graph] rund 1.000 Geräte, die miteinander verknüpft sind.

<table id="table_A6C9CCF9C6564A89BA7060E075A8E73C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Bekannte Geräte/Monat </th> 
   <th colname="col2" class="entry"> Verknüpfte Geräte, die von der Gerätekooperation empfangen wurden </th> 
   <th colname="col3" class="entry"> Geräte insgesamt für die Kampagne </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>100 </p> </td> 
   <td colname="col2"> <p>50 </p> </td> 
   <td colname="col3"> <p>150 </p> </td> 
  </tr> 
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>* [Unbekannte Geräte](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)


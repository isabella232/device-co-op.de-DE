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
>In den [!DNL Adobe Experience Cloud Device Co-op]Begriffen wie *`device`*, *`person`*, *`identity`* usw. eine spezifische Bedeutung haben. &quot;Gerät&quot;kann beispielsweise auf physische Hardware wie Smartphones oder Tablets und auf Anwendungen, die auf dieser Hardware ausgeführt werden, verweisen. Definitionen finden Sie im [Glossar](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) .

## Ziele mit dem bekannten Gerät unterstützen {#section-80deae33660e4280ac65c659ceff5601}

Das bekannte Gerätekonzept unterstützt einige Ziele, die für die Erstellung und Pflege eines effektiven [!DNL Device Co-op] Programms unverzichtbar sind. Ein bekanntes Gerät ist ein Gerät, über das ein [!DNL Device Co-op] Mitglied aus einer Interaktion mit einem Kunden (z. B. einem Site-Besuch oder der Verwendung einer mobilen App) weiß. Basierend auf diesen Aktionen werden die bekannten Geräte eines [!DNL Device Graph] Mitglieds mit Geräten anderer [!DNL Device Co-op] [!DNL Device Co-op] Mitglieder verknüpft. Diese Links können [deterministisch oder probabilistisch](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931)sein. Dies kommt [!DNL Device Co-op] Mitgliedern zugute, da sie

* Weitere Daten zu den bekannten Geräten.
* Neue Informationen zu anderen verknüpften Geräten.

![](assets/known-device.png)

Die [!DNL Device Graph] stellt keine Informationen zu Geräte-Clustern bereit, die ein Mitglied der Gerätekooperation nicht gesehen hat.

## Ziele der Gerätekooperation {#section-75aea5a102d54733aae2a7c6ee9ec6c7}

Drei Hauptziele beleben die [!DNL Device Co-op]. Dazu gehören:

* **Skalierung:** Geben Sie die maximale Anzahl möglicher Links für eine Vielzahl von Anwendungsfällen frei.
* **Fairness:** Gewährleistung, dass alle Mitglieder der [!DNL Device Co-op] Leistungen ihren Beiträgen angemessen sind.

* **Vertrauen der Verbraucher:** Konsumentenvertrauen erhalten und aufbauen, indem sichergestellt wird, dass die geräteübergreifende Erfahrung der Verbraucher bereits bekannte und vertrauensvolle Marken umfasst.

## Skalieren und das bekannte Gerät {#section-67f734109762457ca62ec306284ea082}

Die folgenden Methoden sind die gebräuchlichsten Methoden, mit denen ein Gerät als zweifelsfrei funktionierendes Gerät eingestuft wird. Bei diesen Methoden haben die [!DNL Device Co-op] Mitglieder fast immer mindestens ein bekanntes Gerät. Dies unterstützt das Ziel, allen Mitgliedern der Gruppe maximale Skalierbarkeit zu bieten [!DNL Device Co-op].

**Organisch**

* Vom Besuch eines Kunden auf Ihrer Site oder über die Verwendung Ihrer App. Dies ist eine Qualifizierung aus Erstanbieterdaten.
* Indem Sie Kunden über ein CRM-System an Bord mitnehmen.

**Marketplace**

* Segmentdaten aus Audience Marketplace erwerben.
* Beim Kauf von Daten von einem Drittanbieter.

**Werbung**

Indem sie den Bestand in einer Auktion gewinnen und eine Anzeige an ein Gerät senden. Das Gerät wird zu einem bekannten Gerät, wenn diese Anzeige ein [!DNL Audience Manager] Pixel enthält.

## Bekannte Geräte und Fairness-Anwendungsfälle {#section-0543188729d845d6b95db70b8b25e9f8}

Mitglieder der [!DNL Device Co-op] erhalten Links entsprechend ihren Beiträgen zur [!DNL Device Graph]. Firmen, die viele Geräte zur [!DNL Device Graph] Verfügung stellen, erhalten mehr Links als Mitglieder, die nur wenige beitragen. Wir sind der Meinung, dass dies dazu beiträgt, die [!DNL Device Co-op] Fairness für alle Mitglieder zu gewährleisten. Schauen wir uns an, wie das mit den unten beschriebenen Groß- und Klein-Anwendungsfällen funktioniert.

**Marke A: Großes Anwendungsbeispiel**

In diesem Beispiel hat Marke A jeden Monat 100 Site-Besucher und Beginn eine neue geräteübergreifende Kampagne. Angenommen, der Benutzer [!DNL Device Graph] weiß, dass alle Besucher der Marke A mit einem zusätzlichen Gerät verknüpft sind. Das bedeutet, dass Marke A weitere 100 Geräte erreichen könnte. Darüber hinaus [!DNL Device Graph] enthält das Programm rund 200 miteinander verbundene Geräte.

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

In diesem Beispiel hat Marke B jeden Monat 100 Site-Besucher und Beginn eine neue geräteübergreifende Kampagne. Angenommen, der Benutzer [!DNL Device Graph] weiß, dass alle Besucher der Marke B mit 50 zusätzlichen Geräten verbunden sind. Das bedeutet, dass Marke B 150 Geräte erreichen könnte. Darüber hinaus [!DNL Device Graph] enthält das Programm rund 1.000 miteinander verbundene Geräte.

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


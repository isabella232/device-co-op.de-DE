---
description: Informationen zu bekannten Geräten im Gerätediagramm.
seo-description: Informationen zu bekannten Geräten im Gerätediagramm.
seo-title: Bekannte Geräte
title: Bekannte Geräte
uuid: 53c21105-45b1-4bed-a473-d3ccc4bae965
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371

---


# Known devices{#known-devices}

Informationen zu bekannten Geräten im Gerätediagramm.

Im Gerätediagramm haben wir das Konzept eines *`known device`*. Ein bekanntes Gerät ist ein Gerät, das ein Kunde verwendet, um mit Ihrer Marke zu interagieren.

>[!NOTE]
>
>In den [!DNL Adobe Experience Cloud Device Co-op]Begriffen wie *`device`*, *`person`*, *`identity`* usw. spezifische Bedeutungen. Zum Beispiel kann sich „Gerät“ sowohl auf physische Hardware wie Mobiltelefone oder Tablets beziehen als auch auf die Anwendungen, die auf dieser Hardware laufen. Definitionen finden Sie im [Glossar](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c).

## Supporting goals with the known device {#section-80deae33660e4280ac65c659ceff5601}

The known device concept supports a few goals essential to the creation and maintenance of an effective [!DNL Device Co-op] program. Ein bekanntes Gerät ist ein Gerät, das einem Mitglied der [!DNL Device Co-op] aus einer früheren Interaktion mit einem Kunden bekannt ist (zum Beispiel einem Seitenbesuch oder der Verwendung einer mobilen App). Based on these actions, the [!DNL Device Graph] links the known devices of a [!DNL Device Co-op] member to devices contributed by other [!DNL Device Co-op] members. Diese Links können [deterministisch oder probabilistisch](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931)sein. This benefits [!DNL Device Co-op] members because they receive:

* Zusätzliche Daten zu ihren bekannten Geräten.
* Neue Informationen zu weiteren verknüpften Geräten.

![](assets/known-device.png)

The [!DNL Device Graph] will not provide information about device-clusters that a Device Co-op member has not seen.

## Device Co-op goals {#section-75aea5a102d54733aae2a7c6ee9ec6c7}

Three main goals animate the [!DNL Device Co-op]. Dazu gehören:

* **Maßstab:** Die höchstmögliche Anzahl möglicher Verknüpfungen über eine Vielzahl von Anwendungsfällen hinweg freigeben.
* **Fairness:** Gewährleisten, dass jedes Mitglied der [!DNL Device Co-op] einen Nutzen gewinnt, der sich nach dem jeweiligen Beitrag richtet.

* **Verbrauchervertrauen:** Das Verbrauchervertrauen dadurch aufrechterhalten und aufbauen, dass die geräteübergreifende Erfahrung des Verbrauchers Marken umfasst, mit denen er bereits zu tun hatte und denen er vertraut.

## Scale and the known device {#section-67f734109762457ca62ec306284ea082}

Die folgenden Methoden sind die gebräuchlichsten Methoden, mit denen ein Gerät als zweifelsfrei funktionierendes Gerät eingestuft wird. Mit diesen Methoden haben Mitglieder der [!DNL Device Co-op] fast immer mindestens 1 bekanntes Gerät. Damit wird das Ziel unterstützt, den größtmöglichen Maßstab für alle Mitglieder der [!DNL Device Co-op] zu bieten.

**Kostenlos**

* Durch einen Kundenbesuch auf Ihrer Seite oder Verwendung Ihrer Anwendung. Das ist eine Qualifizierung durch Erstanbieterdaten.
* Über die Eingliederung von Kunden aus einem CRM-System.

**Marketplace**

* Kauf von Segmentdaten über Audience Marketplace.
* Über den Kauf von Daten über einen Dritt-Datenanbieter.

**Werbung**

Durch einen Bestandszugewinn aus einer Auktion und das Schalten einer Werbung auf einem Gerät. Das Gerät wird zum bekannten Gerät, wenn diese Werbung ein [!DNL Audience Manager]-Pixel enthält.

## Known devices and fairness use cases {#section-0543188729d845d6b95db70b8b25e9f8}

Members of the [!DNL Device Co-op] get links commensurate with their contributions to the [!DNL Device Graph]. Companies that contribute a lot of devices to the [!DNL Device Graph] receive more links than members who contribute just a few. Wir sind überzeugt, dass die [!DNL Device Co-op] auf diese Weise für all ihre Mitglieder fair ist. Sehen wir uns anhand der unten beschriebenen Anwendungsfälle für große und kleine Marken an, wie das funktioniert.

**Marke A: Großes Anwendungsbeispiel**

In diesem Beispiel hat Marke A monatlich 100 Seitenbesucher und beginnt mit einer neuen geräteübergreifenden Markenkampagne. For simplicity, assume the [!DNL Device Graph] knows all of the visitors to Brand A are linked to 1 additional device. Das bedeutet, dass Marke A weitere 100 Geräte erreichen könnte. Additionally, the [!DNL Device Graph] contains about 200 devices linked together.

<table id="table_78C38DC522F94BC38C1DB73740C058AC"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Bekannte Geräte/Monat </th> 
   <th colname="col2" class="entry"> Aus der Device Co-op erhaltene verknüpfte Geräte </th> 
   <th colname="col3" class="entry"> Gesamtzahl der Geräte für die Kampagne </th> 
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

**Marke B: Anwendungsfall – klein**

In diesem Beispiel hat Marke B monatlich 100 Seitenbesucher und beginnt mit einer neuen geräteübergreifenden Markenkamppagne. For simplicity, assume the [!DNL Device Graph] knows all of the visitors to Brand B are linked to 50 additional devices. Das bedeutet, dass Marke B 150 Geräte erreichen könnte. Additionally, the [!DNL Device Graph] contains about 1,000 devices linked together.

<table id="table_A6C9CCF9C6564A89BA7060E075A8E73C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Bekannte Geräte/Monat </th> 
   <th colname="col2" class="entry"> Aus der Device Co-op erhaltene verknüpfte Geräte </th> 
   <th colname="col3" class="entry"> Gesamtzahl der Geräte für die Kampagne </th> 
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


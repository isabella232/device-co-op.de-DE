---
description: Die Metrik für Personen ist die Anzahl der Personen (oder Gerätegruppen), basierend auf dem Gerätediagramm von Adobe. Sie können die Metrik für Personen anwenden, um Besucher geräteübergreifend in Analysis Workspace zu identifizieren.
seo-description: Die Metrik für Personen ist die Anzahl der Personen (oder Gerätegruppen) basierend auf dem Gerätediagramm von Adobe. Sie können die Metrik für Personen anwenden, um Besucher geräteübergreifend in Analysis Workspace zu identifizieren.
seo-title: Metrik für Personen
title: Metrik für Personen
uuid: 8e731779-044d-4d31-a19a-f579a9c8c471
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Metrik für Personen{#people-metric}

Die Metrik für Personen ist die Anzahl der Personen (oder Gerätegruppen), basierend auf dem Gerätediagramm von Adobe. Sie können die Metrik für Personen anwenden, um Besucher geräteübergreifend in Analysis Workspace zu identifizieren.

## People Metric Prerequisites and Considerations {#section-34551d0435fb4b3cb3fad736b7961541}

<table id="table_120F7EF50042485391E58B22DD00A2A8"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Voraussetzung oder Erwägung </th> 
   <th colname="col2" class="entry"> Beschreibung </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Device Co-op </p> </td> 
   <td colname="col2"> <p> To use the People metric, become a member of the <a href="http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html" format="html" scope="external"> Adobe Experience Cloud Device Co-op</a>. Die Kooperation identifiziert die verschiedenen Geräte einer Person (oder Experience Cloud IDs). Mithilfe dieser Informationen kann Analytics dann die Anzahl der Personen statistisch ableiten, die mit einer Marke interagieren. Die Metrik ist auf maximal 5 % genau. </p> <p><b>Regionen</b>: Die Device Co-op ist im Moment lediglich in den USA und in Kanada verfügbar. Daher sollten Sie bei der Auswertung der Metrik für Personen ein Segment auf Ihre Analyse anwenden, das Ihre Daten nur nach den USA und Kanada filtert. </p> <p>Jede Woche berechnet das Gerätediagramm eine neue Version der Kooperation und veröffentlicht diese für die Verwendung. An Dienstagen sammelt das System die aktuellsten Daten und veröffentlicht eine aktualisierte Version des Diagramms. Experience Cloud-Lösungen verwenden dann die neueste Version des Diagramms. Speziell für Analytics werden die Änderungen mittwochs gelesen und die Verarbeitung dauert in der Regel zwischen 1 und 2 Werktagen. </p> <p> <p>Wichtig:  Wenn das Diagramm wöchentlich aktualisiert wird, kann dies historische Auswirkungen auf die Metrik "Personen"haben. Mit anderen Worten, die Zählung historischer Personen kann sich mit der Zeit ändern, während das Diagramm lernt und aktualisiert wird. Wenn Sie beispielsweise heute einen Bericht ausführen, der "Personen im letzten Monat"zählt, und dann in einer Woche nach der Aktualisierung des Diagramms denselben Bericht ausführen, kann sich die Anzahl der historischen "Personen"geringfügig ändern. </p> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> Metrikberechtigungen </td> 
   <td colname="col2"> <p>Sie können die Metrik "Personen"nur verwenden, wenn Ihnen Zugriff darauf gewährt wurde. Administratoren können<a href="https://marketing.adobe.com/resources/help/en_US/reference/groups-metrics.html" format="html" scope="external"> die Metrikberechtigungen</a> in den Admin Tools anpassen. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> Zuordnung zu IMS-Org </td> 
   <td colname="col2"> <p>Die Metrik "Personen"wird für alle Report Suites aktiviert, die einem IMSORG <a href="https://marketing.adobe.com/resources/help/en_US/mcloud/map-report-suite.html" format="html" scope="external"> zugeordnet sind</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Analyseprojekte/ Analysewerkzeuge </p> </td> 
   <td colname="col2"> <p>Verwenden Sie die Metrik für Personen in <span class="wintitle">Analysis Workspace</span>, <span class="wintitle">Ad-hoc-Analysen</span>, <span class="wintitle">ReportBuilder</span> und über die API. Sie können Sie überall verwenden, wo Sie sonst die Metrik „Unique Visitors“ einsetzen würden (inklusive berechnete Metriken). </p> <p>So können Sie zum Beispiel eine Metrik „Umsatz pro Person“ erstellen, um eine Metrik „Umsatz pro Unique Visitor“ zu ersetzen. </p> <p>Es ist eine <a href="https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/starter_projects.html" format="html" scope="external">Personen-Projekt-Vorlage</a> verfügbar, um mit der Verwendung der Metrik für Personen in Analysis Workspace zu beginnen. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Aktivieren von Bot-Regeln </p> </td> 
   <td colname="col2"> <p>Adobe empfiehlt das Aktivieren von <a href="https://marketing.adobe.com/resources/help/en_US/reference/bot_rules.html" format="html" scope="external">Bot-Regeln</a>, insbesondere bei der Verwendung der Metrik für Personen. </p> <p>Wenn ein Bot Ihre Website durchforstet, wird die Unique Visitor-Anzahl künstlich in die Höhe getrieben. Wenn Sie Bot-Verkehr aus Ihrer Report Suite entfernen, erhalten Sie eine genauere Messung der Aktivität Ihrer digitalen Eigenschaften, sowohl im Hinblick auf Unique Visitors als auch im Hinblick auf Personen. </p> <p>Wenn Sie dies tun möchten, navigieren Sie zu <span class="uicontrol">Analytics</span> &gt; <span class="uicontrol">Admin</span> &gt; <span class="uicontrol">Report Suites</span>. Wählen Sie die passende Report Suite aus und gehen Sie dann zu <span class="uicontrol">Einstellungen bearbeiten</span> &gt; <span class="uicontrol">Allgemein</span> &gt; <span class="uicontrol">Bot-Regeln</span>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Segmentierungsfaktoren </p> </td> 
   <td colname="col2"> <p> Wenn Sie Segmente mit der Metrik für Personen verwenden, kann der Metrik-Bericht wesentlich geringer ausfallen als erwartet. </p> <p>Siehe <a href="../other-solutions/people.md#section-d03525420dbe48379fd95b230ef05885" format="dita" scope="local">Verwendung der Metrik für Personen mit Segmenten</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Was ist die Metrik für Personen? {#section-89e2b8f5e80f480391449fc8d1117a6a}

Die Metrik für Personen ist eine Berichterstattungsmetrik in Analytics, die Ihnen dabei hilft, Personen Geräte zuzuordnen. Sie bietet eine personenbasierte Marketing-Ansicht und ermöglicht es Ihnen, die Aktivität der Besucher über all ihre Geräte hinweg zu messen. Stellen Sie sich die Metrik wie eine deduplizierte Version von Unique Visitors vor. Sie können die Metrik für Personen in solchen Fällen für Analysen verwenden, für die Sie bisher Unique Visitors verwendet haben.

**Geräte sind Personen**

Bevor die Metrik für Personen verfügbar war, hat eine Person (zum Beispiel) Ihre Seite besucht und über drei verschiedene Geräte mit einer Kampagne oder Marke interagiert und einen Einkauf getätigt, und das sogar innerhalb von Minuten. Abhängig von Ihrer Implementierung ist es möglich, dass Analytics jedes Gerät als Unique Visitor zählt und drei Geräten bei einem Einkauf von 30 $ jeweils 10 $ zuordnet.

Mit der Metrik für Personen können Sie die 30 $ akkurat einer Person zuordnen:

![](assets/people-centric-results.png)

**Höhere Genauigkeit in Berichten**

Mithilfe der Metrik für Personen können Sie mehrere Geräte als eine einzige Einheit betrachten. Das folgende Analysis Workspace-Projekt verdeutlicht den Vergleich zwischen der Berichterstattung mit „Unique Visitors“ und „Personen“ mit erhöhter Genauigkeit:

![](assets/people_report.png)

Direkter Vergleich zwischen „Personen“ und „Unique Visitors“:

![](assets/people-report.png)

**Definitionen**

<table id="table_F8171AF15DA64607B427E3739EF004D6"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Element </th> 
   <th colname="col2" class="entry"> Beschreibung </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>„Personen“ </p> </td> 
   <td colname="col2"> <p>Die Metrik für Personen basiert auf dem Gedanken, dass Verbraucher über mehrere Geräte mit Ihrer Marke interagieren. Je mehr Sie Ihre Daten aufteilen oder segmentieren, desto geringer ist die Wahrscheinlichkeit, dass dieselbe Person in einem Datenbereich mehrere Geräte verwendet hat. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Unique Visitors </p> </td> 
   <td colname="col2"> <p>Je mehr Sie Ihre Daten zum Beispiel nach Datum oder Zeit aufteilen, desto geringer ist der Unterschied zwischen „Personen“ und „Unique Visitors“. Wenn Sie die Auswirkungen der Gerätekooperation insgesamt verstehen möchten, empfiehlt Adobe die Verwendung eines Datumsbereichs der letzten 90 Tage </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Komprimierung </p> </td> 
   <td colname="col2"> <p>Wenn Sie eine einfache berechnete Metrik verwenden, können Sie sehen, um wie viel kleiner die Metrik für Personen als Prozentsatz von „Unique Visitors“ ist. Klicken Sie auf das Infosymbol neben „Komprimierung“ in der obenstehenden Tabelle, um zu sehen, wie Sie diese Metrik erstellen. </p> <p>„Personen“ kann in anderen berechneten Metriken anstelle von „Unique Visitors“ verwendet werden. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Wie wird die Metrik für Personen berechnet? {#section-0dfb762867e14a7f927796ef3c50592b}

<!--
<p>Analytics uses the HyperLogLog statistical algorithm to calculate People. This means that the smaller the data set, the margin for error may increase. No more than 5% of the numbers should be off by more than 5% </p>
-->

Die folgende Grafik zeigt, wie die Metrik für Personen berechnet wird und wie sie sich mit der Zeit für den selben Datenbereich in der Vergangenheit verringern kann.

![](assets/people-calculations.png)

Nehmen wir in diesem Beispiel an, dass es einen festgelegten Besuchersatz gibt. Wenn Sie einen Bericht für einen festgelegten Zeitraum in der Vergangenheit ausführen, wird ein festgelegter Besuchersatz angezeigt. Wenn das Gerätediagramm die in der linken Grafik in „Woche 1“ angezeigten Daten ausgibt, ergibt das 90 Personen. Eine Woche später, nach dem nächsten Zyklus des Gerätediagramms, werden neue Informationen berücksichtigt. Wenn Sie denselben Bericht wie eine Woche zuvor ausführen, ist die Anzahl der Personen auf 84 zurückgegangen. Die Geschichte hat sich verändert, da das Gerätediagramm neue Informationen darüber geliefert hat, welche Geräte zu einer Gruppe zusammengefasst werden sollten.

## Verwendung der Metrik für Personen mit Segmenten {#section-d03525420dbe48379fd95b230ef05885}

Wenn Sie Segmente mit der Metrik für Personen verwenden, kann der Metrik-Bericht wesentlich geringer ausfallen als erwartet. Das ist so, weil es in der Segmentierung keinen *`person`* Personen gibt. Die Segmentierung verwendet den Container „Besucher“, der per Definition der allgemeinste Container ist und auf dem Gerät basiert, nicht auf der Person.

Dieses Problem tritt hauptsächlich dann auf, wenn Segmente mit der Metrik für Personen gestapelt werden.

![](assets/people-stacked-segments.png)

Wenn Segmente gestapelt werden, wird ein neues Segment erstellt, das die Kombination der Segmente darstellt. Segmentstapelung tritt immer dann auf, wenn Sie:

* Ein Segment in Analysis Workspace über ein anderes legen. (Sie werden über den Operator *`And`* hinzufügt.)
* Apply a single segment that contains the *`And`* operator.
* Wenden Sie ein Segment auf der Projektebene und der Tabellenebene an.
* Verwenden Sie eine virtuelle Report Suite mit einem anderen Segment.

Nehmen wir beispielsweise an, dass Sie die folgenden Segmente auf der Metrik für Personen stapeln:

* `Campaign = Spring Promotion`
* `Site Section = Product Overview`

Only the number of people who qualify in both segments *`using a single device`* are counted. (Die Metrik für Personen zeigt nicht die Anzahl der zutreffenden Personen über mehrere Geräte hinweg an.)

Außerdem ist die Verwendung des Operators *`Or`* in dieser Situation nicht zu empfehlen. Damit erhalten Sie die Anzahl der Personen, die das eine, oder das andere gesehen haben, wobei keine Möglichkeit besteht, herauszufinden, wie viele Personen auf beide Segmente zutreffen.

Weitere Informationen finden Sie unter [Erstellung von Segmenten](https://marketing.adobe.com/resources/help/en_US/analytics/segment/seg_build.html) in der Segmentierungshilfe.

## Gerätetypen {#section-8ab378c84ff34574b9c20fecb3848a86}

Die Device Co-op und die Metrik für Personen funktionieren am besten in Adobe Analytics, wenn Ihre Report Suite Daten von verschiedenen Gerätetypen enthält. Zum Beispiel macht die Kombination von Web- und App-Daten in derselben Report Suite die Metrik für Personen leistungsstärker und effektiver. Je mehr Geräteüberkreuzungen es in Ihren Daten gibt, desto größer ist die Wahrscheinlichkeit, dass mehrere Unique Visitors zu einer Einzelperson zusammengeführt werden.

![](assets/people-device-types.png)

## Experience Cloud ID Service Coverage {#section-bbf0098cac2e467289e7a644a1dea05c}

Für die Gerätekooperation müssen Ihre digitalen Eigenschaften mit dem Experience Cloud ID-Dienst (MCID) instrumentiert werden. Wenn die Daten in Ihrer Report Suite eine erhebliche Anzahl von Besuchern ohne MCID aufweisen, verringert dies die Effektivität der Device Co-op und der Metrik für Personen.

<!--
mcdc-people-metric-apply.xml
-->

In Analysis Workspace, create a [project](https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/t_freeform_project.html), then drag the **[!UICONTROL People]** metric to the project table:

![](assets/people-metric.png)


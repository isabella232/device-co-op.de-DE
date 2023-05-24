---
description: Die Metrik für Personen ist die Anzahl der Personen (oder Gerätegruppen), die auf dem Gerätediagramm der Adobe basieren. Sie können die Metrik für Personen anwenden, um Besucher geräteübergreifend in Analysis Workspace zu identifizieren.
seo-description: The People metric is the count of people (or groups of devices) based on Adobe's Device Graph. You can apply the People metric to identify visitors across their devices in Analysis Workspace.
seo-title: People metric
title: Personen-Metrik
uuid: 8e731779-044d-4d31-a19a-f579a9c8c471
exl-id: e2e70461-19ab-49db-bd65-a3eb26c2d4a8
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '1374'
ht-degree: 4%

---

# Personen-Metrik{#people-metric}

Die Metrik für Personen ist die Anzahl der Personen (oder Gerätegruppen), die auf dem Gerätediagramm der Adobe basieren. Sie können die Metrik für Personen anwenden, um Besucher geräteübergreifend in Analysis Workspace zu identifizieren.

## Voraussetzungen und Überlegungen zu Benutzermetriken {#section-34551d0435fb4b3cb3fad736b7961541}

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
   <td colname="col2"> <p> Möchten Sie die Metrik für Personen verwenden, werden Sie Mitglied der <a href="http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html" format="html" scope="external"> Adobe Experience Cloud-Gerätekooperation</a>. Die Kooperation identifiziert die verschiedenen Geräte einer Person (oder Experience Cloud-IDs). Analytics nutzt diese Informationen, um die Anzahl der Personen statistisch abzuleiten, die mit einer Marke interagieren. Die Metrik ist auf maximal 5 % genau. </p> <p><b>Regionen</b>: Die Device Co-op ist derzeit nur in den USA und Kanada verfügbar. Daher sollten Sie bei der Auswertung der Metrik für Personen ein Segment auf Ihre Analyse anwenden, das Ihre Daten nur für die USA und Kanada filtert. </p> <p>Jede Woche berechnet das Gerätediagramm eine neue Version der Kooperation und veröffentlicht sie zur Verwendung. Am Dienstag erfasst das System die neuesten Daten und veröffentlicht eine aktualisierte Version des Diagramms. Experience Cloud-Lösungen verwenden dann die neueste Version des Diagramms. Insbesondere für Analytics werden die Änderungen mittwochs gelesen und die Verarbeitung der Änderungen dauert in der Regel zwischen 1 und 2 Werktagen. </p> <p> <p>Wichtig: Wenn das Diagramm wöchentlich aktualisiert wird, kann sich dies historisch auf die Metrik für Personen auswirken. Mit anderen Worten: Die Zählung historischer Personen kann sich im Laufe der Zeit ändern, wenn das Diagramm lernt und aktualisiert wird. Wenn Sie beispielsweise heute einen Bericht ausführen, in dem Personen im letzten Monat gezählt werden, und diesen Bericht dann innerhalb einer Woche nach der Aktualisierung des Diagramms ausführen, kann sich die Anzahl der Personen im Verlauf geringfügig ändern. </p> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> Metrikberechtigungen </td> 
   <td colname="col2"> <p>Sie können die Metrik für Personen nur verwenden, wenn Ihnen Zugriff darauf gewährt wurde. Administratoren können<a href="https://docs.adobe.com/content/help/en/analytics/admin/user-product-management/customize-report-access/groups-metrics.html" format="html" scope="external"> Anpassen von Berechtigungen für Metriken</a> in den Admin Tools. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> Zuordnung zur IMS-Organisation </td> 
   <td colname="col2"> <p>Die Metrik für Personen wird für alle Report Suites aktiviert, die <a href="https://docs.adobe.com/content/help/de-DE/core-services/interface/about-core-services/report-suite-mapping.html" format="html" scope="external"> einer IMSORG zugeordnet</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Analyseprojekte/Tools </p> </td> 
   <td colname="col2"> <p>Verwenden Sie die Metrik für Personen in <span class="wintitle"> Analysis Workspace</span>, <span class="wintitle"> Ad Hoc Analysis</span>, <span class="wintitle"> Report Builder</span>und über die API. Sie können sie überall dort verwenden, wo Sie die Metrik "Unique Visitors"verwenden würden, einschließlich berechneter Metriken. </p> <p>Erstellen Sie beispielsweise eine Metrik für den Umsatz pro Person, um eine Metrik für den Umsatz pro Unique Visitor zu ersetzen. </p> <p>A <a href="https://docs.adobe.com/content/help/de-DE/analytics/analyze/analysis-workspace/build-workspace-project/starter-projects.html" format="html" scope="external"> Personenprojektvorlage</a> steht für die ersten Schritte mit der Metrik für Personen in Analysis Workspace zur Verfügung. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Bot-Regeln aktivieren </p> </td> 
   <td colname="col2"> <p>Adobe empfiehlt, die <a href="https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/bot-removal/bot-rules.html" format="html" scope="external"> Bot Rules</a>, insbesondere bei Verwendung der Metrik für Personen . </p> <p>Wenn ein Bot Ihre Website durchsucht, erhöht er künstlich Ihre Unique Visitor-Anzahl. Wenn Sie den Bot-Traffic aus Ihrer Report Suite entfernen, erhalten Sie eine genauere Messung der Aktivitäten Ihrer digitalen Eigenschaften, sowohl im Hinblick auf Unique Visitors als auch auf Personen. </p> <p>Navigieren Sie dazu zu <span class="uicontrol"> Analytics</span> &gt; <span class="uicontrol"> Admin</span> &gt; <span class="uicontrol"> Report Suites</span>. Wählen Sie die richtige Report Suite aus und gehen Sie dann zu <span class="uicontrol"> Einstellungen bearbeiten</span> &gt; <span class="uicontrol"> Allgemein</span> &gt; <span class="uicontrol"> Bot Rules</span>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Überlegungen zur Segmentierung </p> </td> 
   <td colname="col2"> <p> Wenn Sie Segmente mit der Metrik für Personen verwenden, kann die Metrikberichterstellung deutlich niedriger sein als erwartet. </p> <p>Siehe <a href="../other-solutions/people.md#section-d03525420dbe48379fd95b230ef05885" format="dita" scope="local"> Verwenden der Metrik für Personen mit Segmenten</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Was ist die Metrik für Personen? {#section-89e2b8f5e80f480391449fc8d1117a6a}

Die Metrik für Personen ist eine Analytics-Berichtsmetrik, mit der Sie Personen Geräte zuordnen können. Er bietet eine benutzerbasierte Ansicht des Marketing, mit der Sie die Aktivität von Besuchern auf allen ihren Geräten messen können. Stellen Sie sich dies als deduplizierte Version von Unique Visitors vor und Sie können die Metrik &quot;Personen&quot;für die Analyse verwenden, in der Sie zuvor Unique Visitors verwendet haben.

**Geräte sind Personen**

Bevor die Metrik für Personen verfügbar wurde, könnte eine Person (z. B.) Ihre Site besuchen und mit einer Kampagne oder Marke auf drei verschiedenen Geräten interagieren und einen Kauf tätigen, selbst wenn dies innerhalb von Minuten der Fall war. Je nach Implementierung meldet Analytics jedes Gerät als Unique Visitor und ordnet drei Geräten 10 Euro bei einem Kauf im Wert von 30 Euro zu.

Mit der Metrik für Personen können Sie diesen Kauf im Wert von 30 Euro genau einer Person zuordnen:

![](assets/people-centric-results.png)

**Erhöhte Genauigkeit in Berichten**

Mit der Metrik für Personen können Sie mehrere Geräte als eine Entität betrachten. Das folgende Analysis Workspace-Projekt zeigt einen höheren Genauigkeitsvergleich zwischen der Berichterstellung für Unique Visitors und der Personenberichterstellung:

![](assets/people_report.png)

Vergleich von Personen und Unique Visitors:

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
   <td colname="col1"> <p>People </p> </td> 
   <td colname="col2"> <p>Die Metrik für Personen basiert auf der Idee, dass Verbraucher mit Ihrer Marke über mehrere Geräte interagieren. Je mehr Sie Ihre Daten aufteilen oder segmentieren, desto geringer ist die Wahrscheinlichkeit, dass dieselbe Person mehrere Geräte innerhalb dieses Datenabschnitts verwendet hat. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Unique Visitors </p> </td> 
   <td colname="col2"> <p>Je mehr Sie beispielsweise Ihre Daten nach Datum oder Uhrzeit aufteilen, desto kleiner ist der Unterschied zwischen "Personen"und "Unique Visitors". Wenn Sie ein gutes Verständnis der Gesamtauswirkungen der Device Co-op wünschen, empfiehlt Adobe die Verwendung eines Datumsbereichs der letzten 90 Tage </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Komprimierung </p> </td> 
   <td colname="col2"> <p>Mithilfe einer einfachen berechneten Metrik können Sie sehen, wie viel kleiner die Metrik für Personen als Prozentsatz von Unique Visitors ist. Klicken Sie auf das Infosymbol neben "Komprimierung"in der obigen Tabelle, um zu sehen, wie Sie diese Metrik erstellen. </p> <p>Personen können anstelle von Unique Visitors in anderen berechneten Metriken verwendet werden. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Wie wird die Metrik für Personen berechnet? {#section-0dfb762867e14a7f927796ef3c50592b}

<!--
<p>Analytics uses the HyperLogLog statistical algorithm to calculate People. This means that the smaller the data set, the margin for error may increase. No more than 5% of the numbers should be off by more than 5% </p>
-->

Die folgende Abbildung zeigt, wie die Metrik für Personen berechnet wird und wie sie im Laufe der Zeit für denselben Datumsbereich des Berichts in der Vergangenheit reduziert werden kann.

![](assets/people-calculations.png)

In diesem Beispiel wird angenommen, dass eine feste Gruppe von Besuchern vorhanden ist. Wenn Sie einen Bericht für einen festen Zeitraum in der Vergangenheit ausführen, wird ein fester Besuchersatz angezeigt. Wenn das Gerätediagramm die in der linken Grafik in Woche 1 angezeigten Daten ausgibt, ergibt dies 90 Personen. Eine Woche später werden nach der nächsten Ausführung des Gerätediagramms neue Informationen berücksichtigt. Wenn Sie denselben Bericht ausführen, den Sie vor einer Woche erstellt haben, ist die Anzahl der Personen auf 84 zurückgegangen. Der Verlauf hat sich geändert, da das Gerätediagramm neue Informationen darüber bereitstellt, welche Geräte gruppiert werden sollen.

## Verwenden der Metrik für Personen mit Segmenten {#section-d03525420dbe48379fd95b230ef05885}

Wenn Sie Segmente mit der Metrik für Personen verwenden, sind die Metrikergebnisse möglicherweise erheblich niedriger als erwartet. Dieses Problem tritt auf, da es in der Segmentierung keine *`person`* Container. Bei der Segmentierung wird der Besucherbehälter verwendet, der der Behälter der obersten Ebene in der Definition ist und auf dem Gerät und nicht auf der Person basiert.

Dieses Problem tritt hauptsächlich beim Stapeln von Segmenten mit der Metrik für Personen auf.

![](assets/people-stacked-segments.png)

Durch das Stapeln von Segmenten wird ein neues Segment erstellt, das die Kombination der Segmente darstellt. Die Stapelung von Segmenten erfolgt immer dann, wenn Sie:

* Platzieren Sie ein Segment über einem anderen Segment in Analysis Workspace. (Diese werden automatisch über die *`And`* Operator.)
* Anwenden eines einzelnen Segments, das die *`And`* Operator.
* Wenden Sie ein Segment sowohl auf Projekt- als auch auf Tabellenebene an.
* Verwenden Sie eine Virtual Report Suite mit einem anderen Segment.

Angenommen, Sie stapeln die folgenden Segmente auf der Metrik für Personen:

* `Campaign = Spring Promotion`
* `Site Section = Product Overview`

Nur die Anzahl der Personen, die sich für beide Segmente qualifizieren *`using a single device`* gezählt werden. (Die Metrik für Personen zeigt nicht die Anzahl der qualifizierenden Personen geräteübergreifend an.)

Verwenden Sie außerdem die *`Or`* in diesem Fall nicht empfohlen. Dadurch würde eine Anzahl von Personen entstehen, die das eine oder das andere gesehen haben, ohne zu zählen, wie viele Personen sich für beide Segmente qualifizieren.

Siehe [Erstellen von Segmenten](https://docs.adobe.com/content/help/de-DE/analytics/components/segmentation/segmentation-workflow/seg-build.html) in der Hilfe zur Segmentierung .

## Gerätetypen {#section-8ab378c84ff34574b9c20fecb3848a86}

Die Metrik &quot;Device Co-op&quot;und &quot;Personen&quot;funktionieren am besten in Adobe Analytics, wenn Ihre Report Suite Daten aus mehreren Gerätetypen enthält. Wenn Sie beispielsweise Web- und App-Daten in derselben Report Suite kombinieren, wird die Metrik für Personen leistungsfähiger und effektiver. Je mehr Geräteüberschneidungen in Ihren Daten auftreten, desto größer ist die Wahrscheinlichkeit, dass mehrere Unique Visitors als eine Person gruppiert werden.

![](assets/people-device-types.png)

## Experience Cloud-ID-Dienstabdeckung {#section-bbf0098cac2e467289e7a644a1dea05c}

Für die Gerätekooperation müssen Ihre digitalen Eigenschaften mit dem Experience Cloud ID-Dienst (MCID) instrumentiert werden. Wenn die Daten in Ihrer Report Suite eine erhebliche Anzahl von Besuchern ohne MCID enthalten, wird die Effektivität der Device Co-op und der Metrik für Personen verringert.

<!--
mcdc-people-metric-apply.xml
-->

Erstellen Sie in Analysis Workspace eine [Projekt](https://docs.adobe.com/content/help/de-DE/analytics/analyze/analysis-workspace/build-workspace-project/t-freeform-project.html), und ziehen Sie dann die **[!UICONTROL People]** Metrik zur Projekttabelle hinzu:

![](assets/people-metric.png)

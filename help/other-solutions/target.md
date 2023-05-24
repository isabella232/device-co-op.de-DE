---
description: Erfahren Sie, wie Sie Daten der Device Co-op in Adobe Target-Aktivitäten verwenden.
seo-description: Learn how to use Device Co-op data in Adobe Target activities.
seo-title: Target - A/B tests, multivariate tests, and experience targeting
title: Target - A/B-Tests, Multivarianz-Tests und Erlebnis-Targeting
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
exl-id: 6e630adf-faff-4fe4-b560-febd59964a5f
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '566'
ht-degree: 0%

---

# Target - A/B-Tests, Multivarianz-Tests und Erlebnis-Targeting{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Erfahren Sie, wie Sie Daten der Device Co-op in Adobe Target-Aktivitäten verwenden.

Sie können Daten der Device Co-op in A/B-Tests, Multivarianz-Tests (MVT) und Erlebnis-Targeting-Aktivitäten verwenden. Die Option Gerätekooperation ist während der Erstellung einer Aktivität auf der [!DNL Goals & Settings] in der [!DNL Target] geleiteter Arbeitsablauf mit drei Schritten.

Sie können keine Daten der Device Co-op in Automated Personalization-Aktivitäten, Recommendations-Aktivitäten oder -Aktivitäten verwenden, die [!DNL Adobe Analytics] als Berichtsquelle (die [!DNL Target] und [!DNL Analytics] Integration, auch als A4T bezeichnet).

>[!NOTE]
>
>Stellen Sie sicher, dass Sie über die erforderliche Version von `mbox.js`. Sie können jede Version von `at.js`. Weitere Informationen finden Sie unter [Voraussetzungen für die Mitgliedschaft](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## Relevante Inhalte unabhängig vom Gerät bereitstellen {#section-bba8d41e96914c82a6d267a54f776354}

Marketingexperten möchten jedem Besucher das relevanteste Erlebnis bereitstellen, unabhängig davon, welches Gerät der Besucher derzeit für die Interaktion mit seinem Unternehmen oder seiner Marke verwendet.

Benutzer interagieren mit demselben Unternehmen oder derselben Marke auf vielen verschiedenen Geräten: Arbeiten von Laptops, Heimcomputern, iPads, iPhones, verschiedenen Browsern usw. Wenn Sie nicht erkennen können, dass jedes einzelne Gerät oder Browser von derselben Person verwendet wird, die zuvor mit Ihrer Marke auf einem anderen Gerät oder Browser interagiert hat, können Sie dieser Person kein konsistentes und zielgerichtetes Erlebnis bieten.

Mit der Device Co-op können die verschiedenen Geräte eines Benutzers als von demselben Benutzer verwendet identifiziert werden. Wenn dieser Benutzer eine Seite mit [!DNL Target] Aktivitäten - entweder Aktivitäten oder zielgerichtete Inhalte - [!DNL Target] kann sicherstellen, dass der Benutzer dasselbe Erlebnis wie auf einem anderen Gerät sieht.

## Target-Aktivitäten nach Personen statt nach Besuchern analysieren {#section-c25cf4f8483942d7836d60756235e62c}

Marketer möchten [!DNL Target] -Aktivitäten nach &quot;Personen&quot;anstelle von &quot;Besuchern&quot;umbenannt.

Jede Person interagiert wahrscheinlich mit demselben Unternehmen oder derselben Marke über Geräte und Browser hinweg. Ohne die Device Co-op wird jedoch jedes einzelne Gerät oder Browser in [!DNL Target] Berichte.

Die Anzeige von Berichten nach einzelnen Geräten und Browsern erhöht die Anzahl der &quot;Besucher&quot;auf eine höhere Anzahl als die Anzahl der verschiedenen Personen, die mit dem Unternehmen oder der Marke interagieren. Diese Personen konvertieren in der Regel nur einmal für diese verschiedenen Geräte und Browser, sodass die Konversionsrate niedriger ist als in der Realität, da mehr &quot;Besucher&quot;für eine einzelne Konversion gezählt werden.

Mit der Device Co-op erfolgt die Bereitstellung und Berichterstellung von Inhalten auf der Ebene der &quot;Personen&quot;, sodass die Berichte genau zeigen, wie viele verschiedene Personen die Aktivität gesehen haben und wie viele der Personen konvertiert haben.

Ohne Daten zur Device Co-op können Sie feststellen, dass eine bestimmte Aktivität der Gewinner ist. Da die Berichterstellung jedoch mit der Device Co-op genauer ist, kann eine andere Aktivität tatsächlich eine höhere Konversionsrate aufweisen und somit der Gewinner sein.

Weitere Informationen zu diesem Konzept finden Sie unter [Analytics: Metrik für Personen](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63).

## Verwenden von Daten der Device Co-op pro Aktivität {#section-fb46fae482654023abb1a1e26564db9a}

Marketingexperten können die Daten der Device Co-op pro Aktivität verwenden. Bestimmt [!DNL Target] -Aktivitäten sind möglicherweise nicht für Daten der Device Co-op geeignet, z. B.:

* Spezifische Inhalte, die für Benutzer auf einer iPad geeignet sind.

   Benutzer, die sich zunächst ein Erlebnis auf einem iPad ansehen, werden dieses Erlebnis auch auf ihren privaten Computern sehen.

* Ein Zinsangebot, das nur für ein striktes Besuchersegment verfügbar ist.
* Produkte, die nur in einem bestimmten Zustand beworben werden dürfen (z. B. eine Versicherungspolice mit Lizenzbeschränkungen).

Wenn Marketing-Experten Zielgruppen in erstellen [!DNL Target], werden sie benachrichtigt, wenn die Zielgruppe nicht für Aktivitäten geeignet ist, die die Device Co-op-Daten ermöglichen. Geeignete Zielgruppen sind alle Besucher, neue Besucher und wiederkehrende Besucher.

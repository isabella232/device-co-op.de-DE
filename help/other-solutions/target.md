---
description: Erfahren Sie, wie Sie Device Co-op-Daten in Adobe Target-Aktivitäten verwenden.
seo-description: Erfahren Sie, wie Sie Device Co-op-Daten in Adobe Target-Aktivitäten verwenden.
seo-title: Zielgruppe - A/B-Tests, Multivarianz-Tests und Erlebnis-Targeting
title: Zielgruppe - A/B-Tests, Multivarianz-Tests und Erlebnis-Targeting
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031
workflow-type: tm+mt
source-wordcount: '586'
ht-degree: 0%

---


# Zielgruppe - A/B-Tests, Multivarianz-Tests und Erlebnis-Targeting{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Erfahren Sie, wie Sie Device Co-op-Daten in Adobe Target-Aktivitäten verwenden.

Sie können Device Co-op-Daten in A/B-Tests, Multivarianz-Tests (MVT) und Erlebnis-Targeting-Aktivitäten verwenden. The Device Co-op option is available during activity creation on the [!DNL Goals & Settings] page in the [!DNL Target] three-step guided workflow.

Sie können keine Device Co-op-Daten in Automated Personalization-Aktivitäten, Recommendations-Aktivitäten oder -Aktivitäten verwenden, die [!DNL Adobe Analytics] als Berichte-Quelle (die als A4T bekannte [!DNL Target] und [!DNL Analytics] -Integration) verwendet werden.

>[!NOTE]
>
>Vergewissern Sie sich, dass Sie über die erforderliche Version von verfügen `mbox.js`. Sie können jede beliebige Version von verwenden `at.js`. Weitere Informationen finden Sie unter [Mitgliedschaftsvoraussetzungen](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## Bereitstellung relevanter Inhalte unabhängig vom Gerät {#section-bba8d41e96914c82a6d267a54f776354}

Marketingexperten möchten jedem Besucher das relevanteste Erlebnis bieten, unabhängig davon, welches Gerät der Besucher derzeit verwendet, um mit seiner Firma oder Marke zu interagieren.

Benutzer interagieren mit derselben Firma oder Marke von verschiedenen Geräten aus: arbeiten Sie mit Laptops, Heimcomputern, iPads, iPhones, verschiedenen Browsern usw. Wenn Sie nicht erkennen können, dass jedes einzelne Gerät oder Browser von derselben Person verwendet wird, die zuvor mit Ihrer Marke auf einem anderen Gerät oder Browser interagiert hat, können Sie dieser Person kein einheitliches und zielgerichtetes Erlebnis bereitstellen.

Mit der Gerätekooperation können die verschiedenen Geräte eines Benutzers als von demselben Benutzer verwendet identifiziert werden. Wenn der Benutzer eine Seite mit [!DNL Target] Aktivitäten - entweder Aktivitäten oder zielgerichteten Inhalten - ansieht [!DNL Target] kann sicherstellen, dass dem Benutzer auf einem anderen Gerät das gleiche Erlebnis angezeigt wird.

## Analysieren Sie die Aktivitäten der Zielgruppe nach Personen statt nach Besuchern. {#section-c25cf4f8483942d7836d60756235e62c}

Marketingexperten möchten [!DNL Target] Aktivitäten nach &quot;Personen&quot;und nicht nach &quot;Besuchern&quot;analysieren.

Jede Person interagiert wahrscheinlich mit derselben Firma oder Marke über Geräte und Browser hinweg, aber ohne die Gerätekooperation wird jedes einzelne Gerät oder Browser in [!DNL Target] Berichten als separater &quot;Besucher&quot;betrachtet.

Die Anzeige von Berichten nach einzelnen Geräten und Browsern erhöht die Anzahl der &quot;Besucher&quot;auf eine höhere Anzahl als die Anzahl der verschiedenen Personen, die mit der Firma oder Marke interagieren. Diese Personen konvertieren in der Regel nur einmal über diese verschiedenen Geräte und Browser, sodass der Konversionsrate niedriger ist als in der Realität, da mehr &quot;Besucher&quot;für eine einzelne Konvertierung gezählt werden.

Mit der Gerätekooperation erfolgt der Versand und Berichte von Inhalten auf der Ebene der &quot;Personen&quot;. Die Berichte zeigen also genau, wie viele verschiedene Personen die Aktivität gesehen haben und wie viele der Personen konvertiert haben.

Ohne Daten zur Gerätekooperation können Sie festlegen, dass eine bestimmte Aktivität der Gewinner ist. Da der Berichte jedoch mit der Gerätekooperation genauer ist, könnte eine andere Aktivität tatsächlich ein höheres Konversionsrate haben und daher der Gewinner sein.

Weitere Informationen zu diesem Konzept finden Sie unter [Analytics: Metrik](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63)&quot;Personen&quot;.

## Geräte-Co-op-Daten pro Aktivität verwenden {#section-fb46fae482654023abb1a1e26564db9a}

Marketingexperten können die Device Co-op-Daten pro Aktivität verwenden. Bestimmte [!DNL Target] Aktivitäten eignen sich möglicherweise nicht für Daten zur Gerätekooperation, wie zum Beispiel:

* Spezifische Inhalte, die für Benutzer auf einem iPad geeignet sind.

   Benutzer, die das erste Mal ein Erlebnis auf einem iPad Ansicht haben, werden dieses Erlebnis auch weiterhin auf ihren Heimatcomputern sehen.

* Ein Angebot mit Zinssätzen, das nur für ein striktes Segment von Besuchern verfügbar ist.
* Produkte dürfen nur in einem bestimmten Zustand beworben werden (z. B. eine Versicherungspolice mit Lizenzbeschränkungen).

Wenn Marketingexperten Audiencen in erstellen, werden sie benachrichtigt, [!DNL Target]wenn die Audience nicht für datenbasierte Aktivitäten geeignet ist. Zu den entsprechenden Audiencen gehören alle Besucher, neuen Besucher und zurückkehrenden Besucher.

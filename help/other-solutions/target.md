---
description: Erfahren Sie, wie Sie Device Co-op-Daten in Adobe Target-Aktivitäten verwenden.
seo-description: Erfahren Sie, wie Sie Device Co-op-Daten in Adobe Target-Aktivitäten verwenden.
seo-title: Target - A/B-Tests, Multivarianz-Tests und Erlebnis-Targeting
title: Target - A/B-Tests, Multivarianz-Tests und Erlebnis-Targeting
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Target - A/B tests, multivariate tests, and experience targeting{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Erfahren Sie, wie Sie Device Co-op-Daten in Adobe Target-Aktivitäten verwenden.

Sie können Device Co-op-Daten in A/B-Tests, Multivarianz-Tests (MVT) und Erlebnis-Targeting-Aktivitäten verwenden. The Device Co-op option is available during activity creation on the [!DNL Goals & Settings] page in the [!DNL Target] three-step guided workflow.

Sie können die Device Co-op nicht für automatisierte Personalisierungen, Empfehlungen oder Aktivitäten verwenden, die [!DNL Adobe Analytics] als berichterstellende Quelle nutzen (die [!DNL Target] und [!DNL Analytics]-Integration, auch bekannt als A4T).

>[!NOTE]
>
>Ensure that you have the required version of `mbox.js`. You can use any version of `at.js`. Weitere Informationen finden Sie unter [Mitgliedschaftsvoraussetzungen](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## Deliver relevant content regardless of the device {#section-bba8d41e96914c82a6d267a54f776354}

Marketingexperten möchten jedem Besucher das relevanteste Erlebnis bieten, unabhängig vom Gerät, das der Besucher aktuell verwendet, um mit der Firma oder der Marke zu interagieren.

Benutzer interagieren über viele verschiedene Geräte mit derselben Firma oder Marke: Arbeitslaptops, Heimcomputer, iPads, iPhones, diverse Browser und so weiter. Wenn Sie nicht erkennen, dass jedes spezifische Gerät bzw. jeder spezifische Browser von derselben Person verwendet wird, die bereits zuvor über ein anderes Gerät oder einen anderen Browser mit Ihrer Marke interagiert hat, können Sie kein konsistentes und zielgerichtetes Erlebnis für diese Person schaffen.

Mit der Device Co-op können die verschiedenen Geräte eines Benutzers identifiziert werden. Wenn dieser Benutzer eine Seite mit [!DNL Target]-Aktivitäten sieht – entweder Aktivitäten oder zielgerichtete Inhalte – kann [!DNL Target] sicherstellen, dass der Benutzer dasselbe Erlebnis sieht wie auf einem anderen Gerät.

## Analyze Target activities by people instead of by visitors {#section-c25cf4f8483942d7836d60756235e62c}

Marketingexperten möchten [!DNL Target]-Aktivitäten nach „Personen“ analysieren, nicht nach „Besuchern“.

Jede Person interagiert wahrscheinlich über Geräte und Browser hinweg mit derselben Marke, aber ohne die Device Co-op wird jedes Gerät und jeder Browser in [!DNL Target]-Berichten als separater „Besucher“ gewertet.

Wenn Berichte nach den einzelnen Geräten und Browsern angezeigt werden, ist die Anzahl der „Besucher“ höher als die Anzahl der verschiedenen Personen, die mit der Firma oder Marke interagieren. Diese Personen konvertieren üblicherweise nur ein einziges Mal für diese verschiedenen Geräte und Browser, also ist die Konversionsrate tatsächlich geringer, weil mehr „Besucher“ für eine einzelne Konversion gezählt werden.

Bei der Device Co-op zielen Inhaltsbereitstellung und Berichterstellung auf die „Personen“-Ebene ab, also zeigen die Berichte genau, wie viele verschiedene Personen die Aktivität gesehen haben, und wie hoch ihre Konversionsrate war.

Ohne Daten der Device Co-op können Sie womöglich bestimmen, dass eine bestimmte Aktivität der Gewinner ist; da die Berichterstattung mit der Device Co-op jedoch genauer ist, ist die Konversionsrate bei einer anderen Aktivität unter Umständen in Wahrheit höher, und diese Aktivität wäre folglich der tatsächliche Gewinner.

Für weitere Informationen zu diesem Konzept, siehe [Analytics: Metrik](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63)&quot;Personen&quot;.

## Use Device Co-op data per activity {#section-fb46fae482654023abb1a1e26564db9a}

Marketingexperten können die Daten der Device Co-op pro Aktivität verwenden. Bestimmte [!DNL Target]-Aktivitäten sind unter Umständen nicht für Daten der Device Co-op geeignet, zum Beispiel:

* Spezielle Inhalte, die für iPad-Nutzer geeignet sind.

   Benutzer, die eine Aktivität zuerst auf einem iPad ansehen, werden diese Erfahrung auf ihrem Heimcomputer zu Ende ansehen.

* Eine Zinsangebot, das nur für einen gewissen Teil von Besuchern gilt.
* Produkte, die nur in einem bestimmten Staat beworben werden dürfen (zum Beispiel eine Versicherungspolice mit Lizenzeinschränkungen).

Wenn Marketingexperten in [!DNL Target] Zielgruppen erstellen, werden sie benachrichtigt, wenn die Zielgruppe nicht für Aktivitäten geeignet ist, die für Device Co-opsdaten aktiviert sind. Geeignete Zielgruppen umfassen alle Besucher, neue Besucher und wiederkehrende Besucher.

---
description: Ihre Firma muss diese Mindeststandards erfüllen, bevor Sie mit der Experience Cloud Device Co-op Beginn ausführen können.
seo-description: Ihre Firma muss diese Mindeststandards erfüllen, bevor Sie mit der Experience Cloud Device Co-op Beginn ausführen können.
seo-title: Anforderungen an die Mitgliedschaft
title: Anforderungen an die Mitgliedschaft
uuid: 4295fa4e-1b9e-4323-bb79-48e548ca1167
translation-type: tm+mt
source-git-commit: 822882d4f9bb9eed7cf116597b62d07bbe94376c
workflow-type: tm+mt
source-wordcount: '460'
ht-degree: 15%

---


# Anforderungen an die Mitgliedschaft{#membership-requirements}

Ihre Firma muss diese Mindeststandards erfüllen, bevor Sie mit der Experience Cloud Device Co-op Beginn ausführen können.

## Voraussetzungen {#section-9cbcee3c7b4e4c49b4c0e2b26aec5fe9}

Sprich mit dir [!DNL Adobe representative to get started]. Wenn Sie keinen Vertreter für die Adobe haben, besuchen Sie das [Device Co-op-Mitgliedschaftsportal](http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html) und füllen Sie das Online-Formular aus.

Adobe behält sich das Recht vor, eine potenzielle Kundenmitgliedschaft bei der Experience Cloud Device Co-op zu verweigern, wenn die Adobe feststellt, dass die Teilnahme eines potenziellen Kunden an der Device Co-op (1) gegen geltendes Recht verstoßen kann. oder (2) eine wesentliche Gefahr für die Sicherheit oder den Betrieb der Adobe oder eines ihrer Kunden darstellen.

## Experience Cloud {#section-76218a50385d43e6b9323e49f598394a}

Sie müssen für die Teilnahme an der Kooperation aktiviert sein [!DNL Adobe Experience Cloud] und die folgenden Lösungen und Dienste verwenden.

**Lösungen**

Antragsteller müssen mindestens eine der folgenden [!DNL Adobe]Lösungen verwenden:

* [Analytics](http://www.adobe.com/de/marketing-cloud/web-analytics.html)
* [Audience Manager](http://www.adobe.com/de/marketing-cloud/data-management-platform.html)
* [Media Optimizer](http://www.adobe.com/marketing-cloud/online-advertising-management.html)
* [Target](http://www.adobe.com/de/marketing-cloud/testing-targeting.html)

**Hauptdienste**

Antragsteller müssen den [Experience Cloud-ID-Dienst](https://docs.adobe.com/content/help/de-DE/id-service/using/home.html)implementieren.

## Bibliotheksanforderungen für Adoben {#section-931a3fca1ce54afd90b88ba032e75f05}

In der folgenden Tabelle werden die Mindestversionen der Codebibliotheken oder SDKs, die von verschiedenen [!DNL Experience Cloud] Lösungen und Diensten verwendet werden, Liste. Wenn Sie diesen Code verwenden und an der Gerätekooperation teilnehmen möchten, stellen Sie sicher, dass Sie diese Mindestanforderungen erfüllen.

>[!TIP]
>
>Als Best Practice empfehlen wir die Verwendung der neuesten Codeversionen anstelle der erforderlichen Mindestwerte.

**AppMeasurement (Flash)**

Erfordert Version 4.1. Siehe [AppMeasurement für Flash, Flex und AIR](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/data-insertion-api/index.md).

**AppMeasurement (JavaScript)**

Erfordert Version 1.5.4. Siehe [AppMeasurement für Flash, Flex und AIR](https://docs.adobe.com/content/help/de-DE/analytics/implementation/js/migrate-from-hcode.html).

**Mobile SDKs**

Mindestanforderungen an das mobile SDK:

* Android-Version 4.8.3.
* iOS-Version 4.8.5.

Your SDK code must be enabled for the [!DNL Experience Cloud] ID service. Enable and download the latest SDK code for each app in your [Adobe Mobile Services](https://mobilemarketing.adobe.com/) account. See [Configure SDK Visitor ID Service Options](https://docs.adobe.com/content/help/de-DE/mobile-services/using/manage-app-settings-ug/configuring-app/t-config-visitor.html).

Verwenden Sie für jedes SDK die entsprechende `visitorSyncIdentifier` Methode, die Ihren Anforderungen entspricht. Siehe:

* [Methoden des Android-Experience Cloud-ID-Diensts](https://docs.adobe.com/content/help/en/mobile-services/android/experience-cloud-android/mcvid.html)
* [iOS-Experience Cloud-ID-Dienstmethoden](https://docs.adobe.com/content/help/en/mobile-services/ios/exp-cloud-ios/mcvid.html)

**VisitorAPI.js**

Erfordert Version 1.5.4.

[!DNL Analytics] Kunden können die Bibliothek VisitorAPI.js von [!DNL Code Manager]herunterladen. Sie befindet sich in den JavaScript- (Neu-) oder JavaScript- (Legacy-)Dateien. Wenden Sie sich an den [Kundendienst](https://helpx.adobe.com/de/marketing-cloud/contact-support.html) , wenn Sie keinen Zugriff darauf haben [!DNL Code Manager].

**Zielgruppe-Bibliothek**

Benötigt eine der folgenden [!DNL Target] JavaScript-Bibliotheken:

* at.js (beliebige Version)
* mbox.js Version 58 oder höher


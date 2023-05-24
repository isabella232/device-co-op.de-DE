---
description: Ihr Unternehmen muss diese Mindestanforderungen erfüllen, bevor Sie mit der Verwendung der Experience Cloud Device Co-op beginnen können.
seo-description: Your company must meet these minimum standards before you can start using the Experience Cloud Device Co-op.
seo-title: Membership requirements
title: Anforderungen an die Mitgliedschaft
uuid: 4295fa4e-1b9e-4323-bb79-48e548ca1167
exl-id: 923ce9c5-7716-4c5a-95f2-05a81a05c9cf
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '415'
ht-degree: 17%

---

# Anforderungen an die Mitgliedschaft{#membership-requirements}

Ihr Unternehmen muss diese Mindestanforderungen erfüllen, bevor Sie mit der Verwendung der Experience Cloud Device Co-op beginnen können.

## Anforderungen {#section-9cbcee3c7b4e4c49b4c0e2b26aec5fe9}

Sprechen Sie mit Ihrem [!DNL Adobe representative to get started]. Adobe behält sich das Recht vor, eine künftige Kundenmitgliedschaft in der Experience Cloud Device Co-op zu verweigern, wenn die Adobe feststellt, dass eine potenzielle Kundenbeteiligung an der Device Co-op (1) gegen geltendes Recht verstößt; oder (2) ein wesentliches Risiko für die Sicherheit oder den Betrieb der Adobe oder eines ihrer Kunden darstellt.

## Experience Cloud-Anforderungen {#section-76218a50385d43e6b9323e49f598394a}

Sie müssen für die [!DNL Adobe Experience Cloud] und verwenden die folgenden Lösungen und Dienste, um an der Kooperation teilzunehmen.

**Lösungen**

Bewerber müssen mindestens eine der folgenden [!DNL Adobe]Lösungen:

* [Analytics](http://www.adobe.com/de/marketing-cloud/web-analytics.html)
* [Audience Manager](http://www.adobe.com/de/marketing-cloud/data-management-platform.html)
* [Media Optimizer](http://www.adobe.com/marketing-cloud/online-advertising-management.html)
* [Zielgruppe](http://www.adobe.com/de/marketing-cloud/testing-targeting.html)

**Zentrale Dienste**

Der Antragsteller muss die [Experience Cloud-ID-Dienst](https://docs.adobe.com/content/help/de-DE/id-service/using/home.html).

## Bibliotheksanforderungen für Adoben-Code {#section-931a3fca1ce54afd90b88ba032e75f05}

In der folgenden Tabelle sind die Mindestversionen der Codebibliotheken oder SDKs aufgeführt, die von verschiedenen [!DNL Experience Cloud] Lösungen und Dienste. Wenn Sie diesen Code verwenden und an der Gerätekooperation teilnehmen möchten, stellen Sie sicher, dass Sie diese Mindestanforderungen erfüllen.

>[!TIP]
>
>Als Best Practice wird empfohlen, anstelle der erforderlichen minimalen die neuesten Codeversionen zu verwenden.

**AppMeasurement (Flash)**

Erfordert Version 4.1. Siehe [AppMeasurement für Flash, Flex und AIR](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/data-insertion-api/index.md).

**AppMeasurement (JavaScript)**

Erfordert Version 1.5.4. Siehe [AppMeasurement für Flash, Flex und AIR](https://docs.adobe.com/content/help/de-DE/analytics/implementation/js/migrate-from-hcode.html).

**Mobile SDKs**

Mindestanforderungen für mobile SDK:

* Android-Version 4.8.3.
* iOS-Version 4.8.5.

Ihr SDK-Code muss für die Variable [!DNL Experience Cloud] ID-Dienst. Aktivieren und Herunterladen des neuesten SDK-Codes für jede App in Ihrer [Adobe Mobile Services](https://mobilemarketing.adobe.com/) -Konto. Siehe [Optionen für SDK-Besucher-ID-Dienst konfigurieren](https://docs.adobe.com/content/help/de-DE/mobile-services/using/manage-app-settings-ug/configuring-app/t-config-visitor.html).

Verwenden Sie für jedes SDK die entsprechende `visitorSyncIdentifier` -Methode, die Ihren Anforderungen entspricht. Siehe:

* [ID-Dienst-Methoden für Android-Experience Cloud](https://docs.adobe.com/content/help/en/mobile-services/android/experience-cloud-android/mcvid.html)
* [Methoden des iOS Experience Cloud ID-Diensts](https://docs.adobe.com/content/help/en/mobile-services/ios/exp-cloud-ios/mcvid.html)

**VisitorAPI.js**

Erfordert Version 1.5.4.

[!DNL Analytics] Kunden können die Bibliothek VisitorAPI.js von [!DNL Code Manager]. Sie befindet sich in den JavaScript- (Neu-) oder JavaScript-Dateien (Legacy). Kontakt [Kundenunterstützung](https://helpx.adobe.com/de/marketing-cloud/contact-support.html) wenn Sie keinen Zugriff auf [!DNL Code Manager].

**Target-Bibliothek**

Erfordert eines der folgenden Elemente [!DNL Target] JavaScript-Bibliotheken:

* at.js (beliebige Version)
* &quot;mbox.js&quot;, Version 58 oder neuer

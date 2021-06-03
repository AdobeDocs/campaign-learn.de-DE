---
title: Erste Schritte mit Push-Benachrichtigungen für Android – Einleitung
description: Dieses Tutorial führt Sie durch die Schritte, die zum Senden von Push-Benachrichtigungen von Adobe Campaign und zum Empfang dieser Benachrichtigungen in Ihrer Android™-App erforderlich sind.
feature: Push-Benachrichtigung
kt: 6438
doc-type: article
activity: setup
team: TM
role: Administrator, Developer
level: Experienced
source-git-commit: 39bed2fe5fbe19101a9684b29d73f61026ad77b2
workflow-type: tm+mt
source-wordcount: '318'
ht-degree: 41%

---

# Erste Schritte mit Push-Benachrichtigungen für Android – Einleitung

Sie können mit Adobe Campaign personalisierte und zielgruppenspezifische [!DNL push]-Benachrichtigungen an [!DNL iOS]- und [!DNL Android™]-Mobilgeräte senden. Dieses Tutorial führt Sie durch die Schritte, die zum Senden von [!DNL push]-Benachrichtigungen von Adobe Campaign an eine [!DNL Android™]-App erforderlich sind.

## Voraussetzungen

Bevor Sie beginnen können, müssen Sie über Folgendes verfügen:

1) **Android™ Mobile App**

   In diesem Tutorial werden nicht die zum Einrichten der Mobile App erforderlichen detaillierten Schritte behandelt. Sie müssen über eine **[!DNL Android™]Mobile App mit der integrierten [!DNL Campaign SDK]** verfügen.

   Eine ausführliche Beschreibung der erforderlichen Schritte finden Sie in der Produktdokumentation:

   [Integration des Campaign SDK in Mobile Apps](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=de)

2) **[!DNL Mobile App channel]Paket installiert**

   Das [!DNL Mobile App channel]-Paket muss auf Ihrer [!DNL Campaign]-Instanz installiert sein. Im folgenden Video wird erläutert, wie Sie überprüfen können, ob [!DNL Mobile App channel] in Ihrer Instanz installiert ist, und wie Sie diese installieren können, falls dies nicht der Fall ist.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Tutorial-Übersicht

Ziel ist es, eine personalisierte Werbeanzeige [!DNL push] an die Abonnenten der Mobile App [!DNL Neotrip] [!DNL Android™] zu senden. Die [!DNL Neotrip]-App wird mit [!DNL Campaign SDK] konfiguriert und die [!DNL Mobile App channel] wird in der [!DNL Campaign]-Instanz aktiviert.

Die folgenden Konfigurationsschritte sind erforderlich:

### Schritt 1: Erweitern des App-Abonnementschemas, um [!DNL push]-Benachrichtigungen zu personalisieren

Um die [!DNL push]-Benachrichtigung personalisieren zu können, müssen Sie zunächst [das App-Abonnementschema](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md) erweitern. Dadurch kann das System die Personalisierungswerte speichern, die von der App empfangen werden, wenn der Benutzer den Dienst abonniert.

### Schritt 2: Konfigurieren Sie den Android™-Dienst und erstellen Sie die Mobile App in Campaign.

Als Nächstes muss [der Android™-Dienst konfiguriert und die Mobile App in Campaign](/help/tutorial-get-started-with-push-notifications-for-android/configure-an-android-service-in-campaign.md) erstellt werden. In diesem Schritt wird die [!DNL Neotrip]-App als Ziel für die Push-Benachrichtigung definiert.

### Schritt 3: Konfigurieren und Senden der Push-Benachrichtigung

Jetzt kann die Push-Benachrichtigung [konfiguriert und gesendet werden](/help/tutorial-get-started-with-push-notifications-for-android/configure-and-send-push-notifications.md).

## Tutorial beginnen

Schritt 1: [Erweitern des App-Abonnementschemas](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)

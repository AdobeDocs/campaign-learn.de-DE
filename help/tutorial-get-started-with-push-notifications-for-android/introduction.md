---
title: Erste Schritte mit Push-Benachrichtigungen für Android – Einleitung
description: Dieses Tutorial führt Sie durch die Schritte, die für das Senden von Push-Benachrichtigungen von Adobe Campaign und den Empfang dieser Benachrichtigungen in Ihrer Android™-Mobile-App erforderlich sind.
feature: Push
kt: 6438
doc-type: article
activity: setup
team: TM
role: Admin, Developer
level: Experienced
exl-id: 91ff4bae-8598-4227-b4c9-4e436ce7400d
source-git-commit: 02a6238163a7c8f887236e03b78673c57c836a45
workflow-type: tm+mt
source-wordcount: '317'
ht-degree: 100%

---

# Erste Schritte mit Push-Benachrichtigungen für Android – Einleitung

Sie können mit Adobe Campaign personalisierte und zielgruppenspezifische [!DNL push]-Benachrichtigungen an [!DNL iOS]- und [!DNL Android™]-Mobilgeräte senden. Dieses Tutorial führt Sie durch die Schritte, die zum Senden von [!DNL push]-Benachrichtigungen von Adobe Campaign an eine [!DNL Android™]-Mobile-App erforderlich sind.

## Voraussetzungen

Bevor Sie beginnen, benötigen Sie Folgendes:

1) **Android™-Mobile-App**

   In diesem Tutorial werden nicht die zum Einrichten der Mobile App erforderlichen detaillierten Schritte behandelt. Sie müssen über eine **[!DNL Android™]-Mobile-App mit integriertem [!DNL Campaign SDK]** verfügen.

   Eine ausführliche Beschreibung der erforderlichen Schritte finden Sie in der Produktdokumentation:

   [Integration des Campaign SDK in Mobile Apps](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=de)

2) Installiertes **[!DNL Mobile App channel]-Paket**

   Das [!DNL Mobile App channel]-Paket muss in Ihrer [!DNL Campaign]-Instanz installiert sein. Im folgenden Video wird erläutert, wie Sie überprüfen können, ob [!DNL Mobile App channel] in Ihrer Instanz installiert ist, und wie Sie diese installieren können, falls dies nicht der Fall ist.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Tutorial-Übersicht

Das Ziel ist es, den Abonnenten der [!DNL Neotrip]-[!DNL Android™]-Mobile-App zu Werbezwecken eine personalisierte [!DNL push]-Benachrichtigung zu senden. Die [!DNL Neotrip]-Mobile-App wird mit dem [!DNL Campaign SDK] konfiguriert, der [!DNL Mobile App channel] wird in der [!DNL Campaign]-Instanz aktiviert.

Die folgenden Konfigurationsschritte sind erforderlich:

### Schritt 1: Erweitern des App-Abonnementschemas, um [!DNL push]-Benachrichtigungen zu personalisieren

Um die [!DNL push]-Benachrichtigung personalisieren zu können, müssen Sie zunächst das [Mobile-App-Abonnementschema](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md) erweitern. Dadurch kann das System die Personalisierungswerte speichern, die von der Mobile App empfangen werden, wenn der Benutzer den Service abonniert.

### Schritt 2: Konfigurieren des Android™-Service und Erstellen der Mobile App in Campaign

Als Nächstes muss [der Android™-Service konfiguriert und die Mobile App in Campaign erstellt](/help/tutorial-get-started-with-push-notifications-for-android/configure-an-android-service-in-campaign.md) werden. In diesem Schritt wird die [!DNL Neotrip]-Mobile-App als Ziel der Push-Benachrichtigung definiert.

### Schritt 3: Konfigurieren und Senden der Push-Benachrichtigung

Jetzt kann die Push-Benachrichtigung [konfiguriert und gesendet werden](/help/tutorial-get-started-with-push-notifications-for-android/configure-and-send-push-notifications.md).

## Tutorial beginnen

Schritt 1: [Erweitern des App-Abonnementschemas](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)

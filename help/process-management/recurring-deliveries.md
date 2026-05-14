---
title: Erstellen wiederkehrender und fortlaufender E-Mail-Sendungen
description: Erfahren Sie, wie Sie einen wiederkehrenden und einen fortlaufenden Versand einrichten und worin sich die beiden Ansätze unterscheiden.
feature: Workflows
jira: KT-7982
thumbnail: 342637.jpg
doc-type: feature video
activity: use
team: TM
role: User
level: Intermediate
exl-id: 469aecd7-4774-42c6-b07f-82792dfdc9c2
TQID: https://experienceleague.adobe.com/pdYTRO3rBq3BdS-WUGcx3POKjD6V4lH1dco4W9L6FwM
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
source-git-commit: 1f6ccc9f0e59ce16a4e781d2d366cf0257b1c8aa
workflow-type: tm+mt
source-wordcount: 233
ht-degree: 100%

---

# Erstellen wiederkehrender und fortlaufender E-Mail-Sendungen

In diesem Tutorial erfahren Sie, wie Sie einen wiederkehrenden und einen fortlaufenden Versand einrichten und worin sich die beiden Ansätze unterscheiden.

## Tracking des wiederkehrenden und des fortlaufenden Versands {#recurring-and-continuous-delivery-tracking}

Der wiederkehrende und der fortlaufende Versand unterscheiden sich bezüglich der Verwaltung von Kontaktdaten:

* Beim **fortlaufenden Versand** können Sie einem bestehenden Versand neue Empfänger hinzufügen, sodass Sie nicht jedes Mal einen neuen Versand erstellen müssen, wenn ein neuer Empfänger hinzugefügt wird. Sie können die kreativen Inhalte direkt im Kampagnen-Workflow aktualisieren, wodurch die Vorlage im Ressourcen-Ordner für Versandvorlagen aktualisiert wird.

  Bei einem fortlaufenden Versand wird EIN Versand erstellt. Versand-Logs (broadLog) und Trackinglogs, die auf diesen Versand verweisen, werden bei jeder Ausführung hinzugefügt.

![Versand (fortlaufend)](/help/assets/delivery_continuous.jpg)

* Bei einem **wiederkehrenden Versand** wird bei jeder Ausführung eine neue Versandinstanz erstellt. Wenn der Workflow beispielsweise einmal pro Woche ausgeführt werden soll, führt dies nach einem Jahr zu 52 Sendungen. Dies bedeutet auch, dass das Broadlog und die Trackinglogs nach Versandinstanz getrennt sind.

![Wiederkehrender Versand](/help/assets/delivery_recurring.jpg)

## Einrichten eines wiederkehrenden Versands {#how-to-set-up-a-recurring-delivery}

In diesem Video wird erläutert, wie Sie einen wiederkehrenden Versand und eine Planungsaktivität konfigurieren.

>[!VIDEO](https://video.tv.adobe.com/v/3446883?captions=ger&quality=12&learn=on){transcript=true}

## Einrichten eines Versands (fortlaufend) {#how-to-set-up-a-continuous-delivery}

In diesem Video wird gezeigt, wie Sie einen fortlaufenden Versand mit einer inkrementellen Abfrage konfigurieren.

>[!VIDEO](https://video.tv.adobe.com/v/3444576?captions=ger&quality=12&learn=on){transcript=true}

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
source-git-commit: 4d21755204c22fbeb4ac3a2916e9ee68cd2e0f9a
workflow-type: tm+mt
source-wordcount: '233'
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

>[!VIDEO](https://video.tv.adobe.com/v/3446883?quality=12&learn=on&captions=ger){transcript=true}

## Einrichten eines fortlaufenden Versands {#how-to-set-up-a-continuous-delivery}

In diesem Video wird gezeigt, wie Sie einen fortlaufenden Versand mit einer inkrementellen Abfrage konfigurieren.

>[!VIDEO](https://video.tv.adobe.com/v/3444576?quality=12&learn=on&captions=ger){transcript=true}

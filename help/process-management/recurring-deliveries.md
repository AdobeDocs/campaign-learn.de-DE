---
title: Einrichten wiederkehrender und kontinuierlicher E-Mail-Kampagnen
description: Erfahren Sie, wie Sie einen wiederkehrenden und einen fortlaufenden Versand einrichten und die Unterschiede zwischen den beiden Ansätzen verstehen.
feature: Workflows
kt: 7982
doc-type: feature video
activity: use
team: TM
role: Business Practitioner
level: Beginner
source-git-commit: 7609aa35dba225a05c8f5e3d3f75f4b6023772a0
workflow-type: tm+mt
source-wordcount: '239'
ht-degree: 21%

---


# Einrichten wiederkehrender und kontinuierlicher E-Mail-Kampagnen

In diesem Tutorial erfahren Sie, wie Sie einen wiederkehrenden und einen fortlaufenden Versand einrichten und die Unterschiede zwischen den beiden Ansätzen erläutern.

## Tracking des wiederkehrenden und kontinuierlichen Versands {#recurring-and-continuous-delivery-tracking}

Der wiederkehrende und kontinuierliche Versand unterscheidet sich bei der Verwaltung der Kontaktdaten:

* Der **Versand (fortlaufend)** ermöglicht das Hinzufügen neuer Empfänger zu einem bestehenden Versand, sodass Sie nicht jedes Mal einen neuen Empfänger erstellen müssen. Sie können die kreativen Inhalte direkt im Kampagnen-Workflow aktualisieren und die Vorlage im Ressourcen-Ordner der Versandvorlage aktualisieren.

   Ein fortlaufender Versand erstellt einen SINGLE-Versand. Bei jeder Ausführung werden Versandlogs (broadLog) und Trackinglogs, die auf diesen einen Versand verweisen, hinzugefügt.

![Versand (fortlaufend)](/help/assets/delivery_continuous.jpg)

* Ein **wiederkehrender Versand** erstellt bei jeder Ausführung eine Versandinstanz. Wenn der Workflow beispielsweise einmal pro Woche ausgeführt werden soll, führt dies nach einem Jahr zu 52 Sendungen. Dies bedeutet auch, dass das Broadlog und die Trackinglogs durch die Versandinstanz getrennt sind.

![Wiederkehrender Versand](/help/assets/delivery_recurring.jpg)

## Einrichten eines wiederkehrenden Versands {#how-to-set-up-a-recurring-delivery}

In diesem Video wird beschrieben, wie Sie einen wiederkehrenden Versand und eine Planungsaktivität konfigurieren.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## Einrichten eines Versands (fortlaufend){#how-to-set-up-a-continuous-delivery}

In diesem Video wird gezeigt, wie man einen fortlaufenden Versand mit einer inkrementellen Abfrage konfiguriert.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)

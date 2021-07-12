---
title: Erstellen von Validierungs-Workflows
description: Erfahren Sie, wie Sie verschiedene Validierungs-Workflows für Genehmigungen konfigurieren.
feature: Workflows, Genehmigungen
kt: 7991
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
source-git-commit: 02a6238163a7c8f887236e03b78673c57c836a45
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 100%

---

# Erstellen von Validierungs-Workflows

Adobe Campaign bietet Marketing-Experten verschiedene Möglichkeiten, Versandinhalte, Kampagnenziele, Datenextraktion und Budgetgenehmigungen zu überprüfen und bereitzustellen.

In diesem Tutorial wird erläutert, wie verschiedene Validierungs-Workflows für Genehmigungen konfiguriert werden.

## Voraussetzung {#prerequisite}

Vor der Aktivierung von Genehmigungsschritten muss das Marketing-Team die einzelnen Validierungsverantwortlichen definieren:

* Die Adobe Campaign-Rolle eines Validierungsverantwortlichen innerhalb einer Genehmigungsaktivität kann entweder ein einzelner Validierungsverantwortlicher (Benutzer) oder eine Gruppe von Validierungsverantwortlichen (Benutzerrolle) sein.
* Damit Kampagnenentwickler die Validierungsverantwortlichen als Genehmiger in einer Kampagne oder einem Versand auswählen können, müssen diese von einem Administrator in Adobe Campaign konfiguriert werden.

## Konfigurieren von Genehmigungen für Kampagnen   {#configuring-approvals-for-campaigns}

Wenn Sie in Ihrem Kampagnen-Workflow für alle Sendungen dieselben Validierungsverantwortlichen haben, wenden Sie die Genehmigungsfunktion der Kampagne an, indem Sie Genehmigungen und Validierungsverantwortliche auf Kampagnenebene einrichten. Die Genehmigungsaufgaben und Validierungsverantwortlichen werden nach der Ausführung des Workflows in jede Versandaktivität Ihres Workflows übertragen.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Konfigurieren von Genehmigungen auf Versandebene   {#configuring-approvals-for-deliveries}

Sie können Genehmigungen auch auf Versandebene einrichten. Wenn sich die Genehmigungsschritte und Validierungsverantwortlichen für den Versand von denen für Kampagnen unterscheiden, wird die Kampagnenkonfiguration durch die Versandeinstellungen außer Kraft gesetzt.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Konfigurieren von Genehmigungsaktivitäten   {#configuring-an-approval-activity}

Im Gegensatz zu Versand- oder Kampagnengenehmigungen ermöglicht die Genehmigungsaktivität die Erstellung eines Genehmigungsprozesses innerhalb eines Workflows. Auf diese Weise kann die Auswahllogik der Zielgruppenbestimmung vor Beginn des Versands validiert werden. Bei Bedarf sind Genehmigungen auch auf mehreren Ebenen innerhalb des Workflows zulässig.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

Weitere Informationen finden Sie in der [Dokumentation zu Genehmigungen](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=de).

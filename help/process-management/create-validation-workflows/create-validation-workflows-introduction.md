---
title: Erstellen von Validierungs-Workflows - Einleitung
description: Erfahren Sie, wie Sie verschiedene Validierungs-Workflows für Genehmigungen konfigurieren.
feature: Workflows, Approvals
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
source-git-commit: f25e3e7553d23aacf96c0f05e1ad78ee783192ff
workflow-type: tm+mt
source-wordcount: '260'
ht-degree: 68%

---

# Erstellen von Validierungs-Workflows - Einführung

Adobe Campaign bietet Marketing-Experten verschiedene Möglichkeiten, Versandinhalte, Kampagnenziele, Datenextraktion und Budgetgenehmigungen zu überprüfen und bereitzustellen.

## Voraussetzung {#prerequisite}

Vor der Aktivierung von Genehmigungsschritten muss das Marketing-Team die einzelnen Validierungsverantwortlichen definieren:

* Die Adobe Campaign-Rolle eines Validierungsverantwortlichen innerhalb einer Genehmigungsaktivität kann entweder ein einzelner Validierungsverantwortlicher (Benutzer) oder eine Gruppe von Validierungsverantwortlichen (Benutzerrolle) sein.
* Damit Kampagnenentwickler die Validierungsverantwortlichen als Genehmiger in einer Kampagne oder einem Versand auswählen können, müssen diese von einem Administrator in Adobe Campaign konfiguriert werden.

## Validierungen konfigurieren {#configuring-approvals}

Campaign bietet drei verschiedene Ebenen für Genehmigungen:

1. [Validierungen für Kampagnen konfigurieren](/help/process-management/create-validation-workflows/configure-approvals-for-campaigns.md): Wenn Sie in Ihrem Kampagnen-Workflow für alle Sendungen denselben Satz von Validierungsverantwortlichen haben, wenden Sie die Validierungsfunktion der Kampagne an, indem Sie Validierungen und Validierungsverantwortliche auf Kampagnenebene einrichten. Die Genehmigungsaufgaben und Validierungsverantwortlichen werden nach der Ausführung des Workflows in jede Versandaktivität Ihres Workflows übertragen.
2. [Konfigurieren von Genehmigungen für Sendungen](/help/process-management/create-validation-workflows/configure-approvals-for-deliveries.md): Sie können Validierungen auch auf Versandebene einrichten. Wenn sich die Genehmigungsschritte und Validierungsverantwortlichen für den Versand von denen für Kampagnen unterscheiden, wird die Kampagnenkonfiguration durch die Versandeinstellungen außer Kraft gesetzt.
3. [Erstellen eines Validierungsprozesses in einem Workflow](/help/process-management/create-validation-workflows/create-approval-process-in-a-workflow.md): Die Validierungsaktivität ermöglicht die Erstellung eines Validierungsprozesses innerhalb eines Workflows. Auf diese Weise kann die Auswahllogik der Zielgruppenbestimmung vor Beginn des Versands validiert werden. Bei Bedarf sind Genehmigungen auch auf mehreren Ebenen innerhalb des Workflows zulässig.

Weiterführende Informationen dazu finden Sie im [entsprechenden Handbuch](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=de).
---
title: Erstellen von Validierungen und Validierungs-Workflows – Einführung
description: Erfahren Sie, wie Sie verschiedene Validierungs-Workflows konfigurieren.
feature: Workflows, Approvals
doc-type: feature video
activity: setup
team: TM
role: User
level: Intermediate
recommendations: noDisplay
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
TQID: https://experienceleague.adobe.com/nVZT-SWtytNyXrkbV-J7LWhR5-KHo601s0dE9yUiOaY
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
feature_v2:
  - id: a075b2c1-7748-4328-b7f6-343aa314616a
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
source-git-commit: 1f6ccc9f0e59ce16a4e781d2d366cf0257b1c8aa
workflow-type: tm+mt
source-wordcount: 267
ht-degree: 89%

---

# Erstellen von Validierungen und Validierungs-Workflows – Einführung

Adobe Campaign bietet Marketing-Experten verschiedene Möglichkeiten, Validierungen für Versandinhalte, Kampagnenzielgruppen, Datenextraktionen und Budgets zu überprüfen und bereitzustellen. Erfahren Sie, wie Sie [Validierungen verwalten](/help/process-management/create-approvals-and-validation-workflows/manage-approvals.md).

## Voraussetzung {#prerequisite}

Vor der Aktivierung von Genehmigungsschritten muss das Marketing-Team die einzelnen Validierungsverantwortlichen definieren:

* Die Adobe Campaign-Rolle eines Validierungsverantwortlichen innerhalb einer Genehmigungsaktivität kann entweder ein einzelner Validierungsverantwortlicher (Benutzer) oder eine Gruppe von Validierungsverantwortlichen (Benutzerrolle) sein.
* Damit Kampagnenentwickler die Validierungsverantwortlichen als Genehmiger in einer Kampagne oder einem Versand auswählen können, müssen diese von einem Administrator in Adobe Campaign konfiguriert werden.

## Konfigurieren von Validierungen {#configuring-approvals}

1. [Konfigurieren von Genehmigungen für Kampagnen](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-campaigns.md):
Wenn Sie in Ihrem Kampagnen-Workflow für alle Sendungen dieselben Validierungsverantwortlichen haben, wenden Sie die Genehmigungsfunktion der Kampagne an, indem Sie Genehmigungen und Validierungsverantwortliche auf Kampagnenebene einrichten. Die Validierungsaufgaben und Validierer werden nach dem Start des Workflows in jede Versandaktivität Ihres Workflows übertragen.
2. [Konfigurieren von Validierungen für Sendungen](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-deliveries.md):
Sie können Genehmigungen auch auf Versandebene einrichten. Wenn sich die Validierungsschritte und Validierer für den Versand von denen für Kampagnen unterscheiden, überschreiben die Versandeinstellungen die Kampagneneinstellungen.
3. [Erstellen eines Genehmigungsprozesses in einem Workflow](/help/process-management/create-approvals-and-validation-workflows/create-approval-process-in-a-workflow.md):
Die Validierungsaktivität ermöglicht die Erstellung eines Validierungsprozesses innerhalb eines Workflows. Auf diese Weise kann die Auswahllogik der Zielgruppenbestimmung vor Beginn des Versands validiert werden. Bei Bedarf sind Genehmigungen auch auf mehreren Ebenen innerhalb des Workflows zulässig.

Weiterführende Informationen dazu finden Sie im [entsprechenden Handbuch](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=de).

---
title: Export-Workflow erstellen (Teil 2) – Daten in ein externes Konto extrahieren, formatieren und speichern
description: In diesem zweiten Teil des Tutorials zum Erstellen eines Export-Workflows erfahren Sie, wie Sie die Daten für den Export formatieren und in einem externen Konto speichern.
feature: Data Management, Workflows
jira: KT-8160
thumbnail: 336391.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
exl-id: ac29b75c-a838-4183-8ec5-034281290725
source-git-commit: 116a24a8aa123f615e08fa4ebd187b3c4c460ba2
workflow-type: tm+mt
source-wordcount: '94'
ht-degree: 100%

---

# Export-Workflow erstellen (Teil 2): Daten in ein externes Konto extrahieren, formatieren und speichern

In diesem zweiten Teil des Tutorials zum Erstellen eines Export-Workflows erfahren Sie, wie Sie die Daten für den Export formatieren und in einem externen Konto speichern.

>[!VIDEO](https://video.tv.adobe.com/v/336391?quality=12&learn=on){transcript=true}

## Assets

JavaScript: Datum speichern

```java
 logInfo("=====================")
 logInfo("Starting Execution...")

 optionName = vars.OPTION_NAME;
 logInfo("optionName: " + optionName);
 logInfo("NEXT Run Date: " + vars.nextRunTime);
 
 //Make sure we have valid values before saving for next run
 if (vars.nextRunTime == null || optionName == null){

   logInfo("Unable to find non-null values for optionName/nextRunTime! Throwing Error.")
   throw new Error('Unable to find non-null values for optionName/nextRunTime!  Ending Execution.');

 } else {

   // Save the nextRunTime to the database to establish starting point for next run.
   setOption(optionName, vars.nextRunTime);
   logInfo("Date Saved. [" + optionName + "] = [" + vars.lastRunTime + "]")

 }

 logInfo("Finished Execution.") 
 logInfo("===================")
```

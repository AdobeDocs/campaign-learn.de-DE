---
title: Fehlerbehebung im Control Panel
description: Informationen zur Fehlerbehebung im Control Panel
feature: Control Panel
kt: 8520
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
source-git-commit: f8ed9264e592f4adf070a517049e3d36fc3112d5
workflow-type: tm+mt
source-wordcount: '340'
ht-degree: 39%

---

# Fehlerbehebung im [!UICONTROL Control Panel]

Erfahren Sie, wie Sie die Fehlerbehebung im Control Panel durchführen.

## Anmelden und Homepage

### Symptom: Anmeldung bei Experience Cloud nicht möglich

**Vorgehensweise:**
Der Benutzer muss seine IMS-Organisations-ID (xxx) finden. Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Produktprofil &quot;Campaign-xxx-Admins&quot;hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich selbst als Benutzer hinzufügen.

### Symptom: Links auf der Experience Cloud-Startseite für den Zugriff auf [!UICONTROL Control Panel] werden für einen Benutzer nicht angezeigt

**Ursache:**
Benutzer sehen die Links erst, nachdem sie als Benutzer zum Produktprofil  _Campaign-xxx-Administrators/Admin_ hinzugefügt wurden.

**Vorgehensweise:**
Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Produktprofil  _Campaign-xxx-_  Admins hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich selbst als Benutzer hinzufügen.

### Symptom: Eine Instanz wird im [!UICONTROL Control Panel] nicht aufgeführt

**Ursache:**
Der Benutzer muss höchstwahrscheinlich als  ** BenutzerProduktprofil  _Campaign-xxx-Administrators/_ Administrator für die fehlende Instanz hinzugefügt werden.

**Vorgehensweise:**
Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Produktprofil  _Campaign-xxx-_  Admins hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich selbst als &quot;Benutzer&quot;hinzufügen.

### Nützliche Videos

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*IMS-Organisations-ID prüfen (00:26 Min.)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Hinzufügen eines Administrators zum Produktprofil „Administratoren“ für die Verwendung des [!UICONTROL Control Panel] (01:03 Min.)*

### Nützliche Dokumentation

* [Funktionsweise des Control Panels](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=de)
* [[!UICONTROL Verwalten von Berechtigungen für das ]Control Panel](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Herstellen einer Verbindung zum SFTP-Server (Client oder API)

Für Verbindungen mit SFTP-Servern ist Folgendes erforderlich:

* [!UICONTROL Setzen auf die Zulassungsliste] der IP-Adresse, von der Sie eine Verbindung zum SFTP-Server herstellen
* Paar aus privatem/öffentlichem Schlüssel, das bei Adobe Campaign registriert werden muss
* Um eine direkte Verbindung zum SFTP-Server herzustellen, benötigen Sie auch die SFTP-Client-Software

### Nützliche Dokumentation {#helpful-docs}

* [Anmeldung bei Ihrem SFTP-Server](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

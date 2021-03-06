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
exl-id: 0dca4676-2d5e-411b-9fdf-fbfd1081cb0e
source-git-commit: 28e209b6c9dad98a649b0b49eee7bb886c3d8431
workflow-type: tm+mt
source-wordcount: '337'
ht-degree: 95%

---

# Fehlerbehebung im [!UICONTROL Control Panel]

Erfahren Sie, wie Sie Fehler im Control Panel beheben.

## Anmelden und Homepage

### Problem: Anmeldung bei Experience Cloud nicht möglich

**Vorgehensweise:**
Der Benutzer muss die Kennung seiner Organisation (xxx) suchen. Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Profil „Campaign-xxx-Admins“ hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich dennoch selbst als Benutzer hinzufügen.

### Problem: Links auf der Experience Cloud-Startseite für den Zugriff auf das [!UICONTROL Control Panel] werden einem Benutzer nicht angezeigt.

**Ursache:**
Diese Links werden Benutzern erst dann angezeigt, nachdem sie dem Produktprofil _Campaign-xxx-Administrators/Admin_ als Benutzer hinzugefügt wurden.

**Vorgehensweise:**
Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Produktprofil _Campaign-xxx-Admins_ hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich dennoch selbst als Benutzer hinzufügen.

### Problem: Eine Instanz wird im [!UICONTROL Control Panel] nicht aufgeführt.

**Ursache:****
Der Benutzer muss wahrscheinlich für die fehlende Instanz dem Produktprofil _Campaign-xxx-Administrators/Admin_ als Benutzer hinzugefügt werden.

**Vorgehensweise:**
Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Produktprofil _Campaign-xxx-Admins_ hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich dennoch selbst als Benutzer hinzufügen.

### Nützliche Videos

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Überprüfen Sie die Kennung Ihres Unternehmens (00:26 Min.).*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Hinzufügen eines Administrators zum Produktprofil „Administratoren“ für die Verwendung des [!UICONTROL Control Panel] (01:03 Min.)*

### Nützliche Dokumentation

* [Funktionsweise des Control Panels](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=de)
* [[!UICONTROL Verwalten von Berechtigungen für das ]Control Panel](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Herstellen einer Verbindung zum SFTP-Server (Client oder API)

Für Verbindungen mit SFTP-Servern ist Folgendes erforderlich:

* [!UICONTROL Setzen auf die Zulassungsliste] der IP-Adresse, von der Sie eine Verbindung zum SFTP-Server herstellen
* Schlüsselpaar aus privatem/öffentlichem Schlüssel, das bei Adobe Campaign registriert werden muss
* Wenn Sie eine direkte Verbindung zum SFTP-Server herstellen möchten, benötigen Sie auch SFTP-Client-Software.

### Nützliche Dokumentation {#helpful-docs}

* [Anmeldung bei Ihrem SFTP-Server](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

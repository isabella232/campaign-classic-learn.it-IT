---
title: Pannello di controllo Campaign di ripresa con problemi
description: Il Pannello di controllo Campaign consente di monitorare e gestire lo storage SFTP per istanza e  indirizzi IP del elenco consentiti.
feature: Control Panel
topics: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
translation-type: tm+mt
source-git-commit: b2820c65a88d25f9b7a4ed5005cd5083463e000a
workflow-type: tm+mt
source-wordcount: '339'
ht-degree: 1%

---


# Risoluzione dei problemi [!UICONTROL Control Panel]

## Accesso e homepage

### Sintomo: Impossibile accedere a  Experience Cloud

**Procedura:**
L&#39;utente deve individuare il proprio ID organizzazione IMS (xxx). L&#39;amministratore deve aggiungere l&#39;utente al profilo di prodotto &quot;Campaign-xxx-Admins&quot; per ogni istanza da gestire. Se l&#39;utente è un amministratore di tutte le istanze, potrebbe comunque dover aggiungere se stesso come utenti.

### Sintomo: I collegamenti nella  Experience Cloud Home per l&#39;accesso [!UICONTROL Control Panel] non vengono visualizzati per un utente

**Causa:**
Gli utenti non visualizzeranno i collegamenti finché non saranno stati aggiunti come utenti al profilo di prodotto _Campaign-xxx-Administrators/Admin_.

**Procedura:**
L&#39;amministratore deve aggiungere l&#39;utente al profilo di prodotto _Campaign-xxx-Admins_ per ogni istanza da gestire. Se l&#39;utente è un amministratore di tutte le istanze, potrebbe comunque dover aggiungere se stesso come &quot;utenti.

### Sintomo: Un&#39;istanza non è elencata nella variabile [!UICONTROL Control Panel]

**Causa:**
Probabilmente l&#39;utente deve essere aggiunto come &quot;utente&quot; Profilo di prodotto _Campaign-xxx-Administrators/Admin_ per l&#39;istanza mancante

**Procedura:**
L&#39;amministratore deve aggiungere l&#39;utente al profilo di prodotto _Campaign-xxx-Admins_ per ogni istanza da gestire. Se l&#39;utente è un amministratore di tutte le istanze, potrebbe comunque dover aggiungere se stesso come &quot;utenti&quot;.

### Video utili

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Controlla ID organizzazione IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Come aggiungere un amministratore agli amministratori del profilo di prodotto per poter utilizzare[!UICONTROL Control panel](01:03 min)*

### Documentazione utile

* [Scopri il Pannello di controllo Campaign](https://helpx.adobe.com/campaign/kb/control-panel-overview.html)
* [Gestione delle autorizzazioni per [!UICONTROL Control Panel]](https://helpx.adobe.com/campaign/kb/control-panel-access.html)

## Connessione al server SFTP (client o API)

La connessione ai server SFTP richiede:

* [!UICONTROL Allow listing] l&#39;indirizzo IP da cui ci si connette al server SFTP
* Coppia di chiave pubblica/privata che deve essere registrata con  Adobe Campaign
* Se ti connetti direttamente al server SFTP, avrai bisogno anche del software client SFTP

### Documentazione utile

* [Accesso al server SFTP](https://helpx.adobe.com/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)


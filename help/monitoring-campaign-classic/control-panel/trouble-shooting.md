---
title: Risoluzione dei problemi del Pannello di controllo Campaign
description: Il Pannello di controllo Campaign consente di monitorare e gestire l’archiviazione SFTP per istanza e di inserire indirizzi IP nell’elenco Consentiti.
feature: Control Panel
topics: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
translation-type: tm+mt
source-git-commit: 838c617ca163a09fcb57b7b4706433e98869bc3d
workflow-type: tm+mt
source-wordcount: '339'
ht-degree: 100%

---


# Risoluzione dei problemi del [!UICONTROL Control Panel]

## Login e homepage

### Sintomo: impossibile accedere a Experience Cloud

**Come procedere:**
l’utente deve individuare il proprio ID organizzazione IMS (xxx). L’amministratore deve aggiungere l’utente al profilo di prodotto “Campaign-xxx-Admins” per ogni istanza che desidera gestire. Anche se l’utente è amministratore di tutte le istanze, potrebbe comunque dover aggiungere se stesso come utente.

### Sintomo: i collegamenti nella home di Experience Cloud per accedere al [!UICONTROL Control Panel] non vengono visualizzati per un utente

**Causa:**
gli utenti non visualizzano i collegamenti finché non vengono aggiunti come utenti al profilo di prodotto _Campaign-xxx-Administrators/Admin_.

**Come procedere:**
l’amministratore deve aggiungere l’utente al profilo di prodotto _Campaign-xxx-Admins_ per ogni istanza che desidera gestire. Anche se l’utente è amministratore di tutte le istanze, potrebbe comunque dover aggiungere se stesso come utente.

### Sintomo: un’istanza non è elencata nel [!UICONTROL Control Panel]

**Causa:**
probabilmente l’utente deve essere aggiunto come “utente” al profilo di prodotto _Campaign-xxx-Administrators/Admin_ per l’istanza mancante

**Come procedere:**
l’amministratore deve aggiungere l’utente al profilo di prodotto _Campaign-xxx-Admins_ per ogni istanza che desidera gestire. Anche se l’utente è amministratore di tutte le istanze, potrebbe comunque dover aggiungere se stesso come “utente”.

### Video utili

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Check IMS Org ID (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*How to add an administrator to the product profile administrators to be able to use[!UICONTROL Control panel](01:03 min)*

### Documentazione utile

* [Scoprire il Pannello di controllo Campaign](https://helpx.adobe.com/it/campaign/kb/control-panel-overview.html)
* [Gestione delle autorizzazioni per il [!UICONTROL Control Panel]](https://helpx.adobe.com/it/campaign/kb/control-panel-access.html)

## Stabilimento di una connessione al server SFTP (client o API)

La connessione ai server SFTP richiede:

* [!UICONTROL Allow listing] l’indirizzo IP da cui desideri connetterti al server SFTP
* Una coppia di chiavi privata/pubblica che deve essere registrata con Adobe Campaign
* Se ti connetti direttamente al server SFTP, avrai bisogno anche del software client SFTP

### Documentazione utile

* [Accesso al server SFTP](https://helpx.adobe.com/it/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)


---
title: Risoluzione dei problemi del Pannello di controllo Campaign
description: Il Pannello di controllo Campaign ti consente di monitorare e gestire l’archiviazione SFTP per istanza e inserire nell'elenco Consentiti gli indirizzi IP.
feature: Pannello di controllo Campaign
kt: 2938
doc-type: article
activity: use
team: PM
source-git-commit: 8910430585bdaa0db076db9c34b34798f649d39c
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---


# Risoluzione dei problemi del [!UICONTROL Control Panel]

## Login e homepage

### Sintomo: Impossibile accedere all&#39;Experience Cloud

**Come procedere:**
l’utente deve individuare il proprio ID organizzazione IMS (xxx). L’amministratore deve aggiungere l’utente al profilo di prodotto &quot;Campaign-xxx-Admins&quot; per ogni istanza da gestire. Se l’utente è amministratore di tutte le istanze, deve aggiungere se stesso come utente.

### Sintomo: i collegamenti nella home di Experience Cloud per accedere al [!UICONTROL Control Panel] non vengono visualizzati per un utente

**Causa:**
gli utenti non visualizzano i collegamenti finché non vengono aggiunti come utenti al profilo di prodotto _Campaign-xxx-Administrators/Admin_.

**Come procedere:**
l’amministratore deve aggiungere l’utente al profilo di prodotto  _Campaign-xxx-_  Adminsper ogni istanza da gestire. Se l’utente è amministratore di tutte le istanze, deve aggiungere se stesso come &quot;utenti.

### Sintomo: un’istanza non è elencata nel [!UICONTROL Control Panel]

**Causa:**
probabilmente l’utente deve essere aggiunto come &quot;utente&quot; al profilo di prodotto  _Campaign-xxx-Administrators/_ Adminper l’istanza mancante

**Come procedere:**
l’amministratore deve aggiungere l’utente al profilo di prodotto  _Campaign-xxx-_  Adminsper ogni istanza da gestire. Se l’utente è amministratore di tutte le istanze, deve aggiungersi come &quot;utenti&quot;.

### Video utili

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Check IMS Org ID (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*How to add an administrator to the product profile administrators to be able to use [!UICONTROL Control panel] (01:03 min)*

### Documentazione utile

* [Scoprire il Pannello di controllo Campaign](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=it)
* [Gestione delle autorizzazioni per il [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Stabilimento di una connessione al server SFTP (client o API)

La connessione ai server SFTP richiede:

* [!UICONTROL Allow listing] l’indirizzo IP da cui desideri connetterti al server SFTP
* Coppia di chiavi privata/pubblica che deve essere registrata con Adobe Campaign
* Se ti connetti direttamente al server SFTP, devi disporre di un software client SFTP

### Documentazione utile {#helpful-docs}

* [Accesso al server SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)


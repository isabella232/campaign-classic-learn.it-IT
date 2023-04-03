---
title: Risoluzione dei problemi del Pannello di controllo
description: Il Pannello di controllo Campaign ti consente di monitorare e gestire l’archiviazione SFTP per istanza e inserire nell'elenco Consentiti gli indirizzi IP.
feature: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
source-git-commit: 13f7ab2dd41216a603a22f181dc4d06302c5918a
workflow-type: tm+mt
source-wordcount: '330'
ht-degree: 84%

---


# Risoluzione dei problemi del [!UICONTROL Control Panel]

## Login e homepage

### Sintomo: impossibile accedere a Experience Cloud

**Come procedere:**
L’utente deve individuare il proprio ID organizzazione IMS (xxx). L’amministratore deve aggiungere l’utente al profilo di prodotto “Campaign-xxx-Admins” per ogni istanza che desidera gestire. Se l’utente è amministratore di tutte le istanze, deve comunque aggiungere se stesso come utente.

### Sintomo: i collegamenti nella home di Experience Cloud per accedere al [!UICONTROL Control Panel] non vengono visualizzati per un utente

**Causa:**
gli utenti non visualizzano i collegamenti finché non vengono aggiunti come utenti al profilo di prodotto _Campaign-xxx-Administrators/Admin_.

**Come procedere:**
L’amministratore deve aggiungere l’utente al profilo di prodotto _Campaign-xxx-Admins_ per ogni istanza che desidera gestire. Se l’utente è amministratore di tutte le istanze, deve comunque aggiungere se stesso come “utente.

### Sintomo: un’istanza non è elencata nel [!UICONTROL Control Panel]

**Causa:**
Probabilmente l’utente deve essere aggiunto come profilo di prodotto &quot;utente&quot; _Campaign-xxx-Administrators/Admin_ per l&#39;istanza mancante

**Come procedere:**
L’amministratore deve aggiungere l’utente al profilo di prodotto _Campaign-xxx-Admins_ per ogni istanza che desidera gestire. Se l’utente è amministratore di tutte le istanze, deve comunque aggiungere se stesso come “utente”.

### Video utili

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12&learn=on)

*Verificare Org ID IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12&learn=on)

*Come aggiungere un amministratore al profilo di prodotto in modo che possa utilizzare il [!UICONTROL Control panel] (01:03 min)*

### Documentazione utile

* [Scoprire il Pannello di controllo](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=it)
* [Gestione delle autorizzazioni per il [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=it)

## Stabilimento di una connessione al server SFTP (client o API)

La connessione ai server SFTP richiede:

* [!UICONTROL Allow listing] l’indirizzo IP da cui desideri connetterti al server SFTP
* Una coppia di chiavi privata/pubblica che deve essere registrata con Adobe Campaign
* Se ti connetti direttamente al server SFTP, devi disporre di un software client SFTP

### Documentazione utile {#helpful-docs}

* [Accesso al server SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=it)


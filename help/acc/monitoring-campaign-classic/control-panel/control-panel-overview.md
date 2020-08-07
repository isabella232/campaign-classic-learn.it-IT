---
title: Pannello di controllo Campaign
seo-title: Pannello di controllo Campaign
description: Il Pannello di controllo Campaign ti consente di monitorare e gestire lo storage SFTP per istanza e di aggiungere indirizzi IP all’elenco Consentiti.
seo-description: Il Pannello di controllo Campaign ti consente di monitorare e gestire lo storage SFTP per istanza e di aggiungere indirizzi IP all’elenco Consentiti.
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: ca3b7933927914b9965f6f059293041dd1db1da2
workflow-type: tm+mt
source-wordcount: '419'
ht-degree: 76%

---


# [!UICONTROL Control Panel]

>[!NOTE]
>
>I termini “[!UICONTROL whitelist]” e “[!UICONTROL blacklist]” sono stati sostituiti da “[!UICONTROL allow list]” e “[!UICONTROL block list]” nella documentazione di Adobe Campaign.
>Alcune occorrenze di questi termini possono ancora essere presenti nell’interfaccia utente del prodotto, nei nomi delle opzioni, nel codice interno e nei video tutorial. Tali termini saranno sostituiti nelle prossime versioni del Pannello di controllo Campaign.

 Il [!UICONTROL Control Panel] consente agli amministratori di Adobe Campaign di monitorare le risorse chiave ed eseguire attività amministrative, ad esempio la gestione dello storage SFTP per istanza o [!UICONTROL allow list] di indirizzi IP.

## Accesso a [!UICONTROL Control Panel]

Per accedere al Pannello di controllo Campaign, vai alla home di Experience Cloud: [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com):

* **[!UICONTROL Experience Cloud Home]** > **[!UICONTROL Quick Access]**

   o
* **[!UICONTROL Experience Cloud Home]**  > [!UICONTROL Solution picker]: **Campaign** > scheda **[!UICONTROL Control Panel]**

   o

* Direttamente dall’URL: [https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## Prerequisiti

Prima di iniziare, completa i seguenti prerequisiti:

### Conferma [!DNL IMS Org ID]

Devi conoscere il tuo [!DNL IMS org ID]. Il seguente video descrive le aree in cui puoi ricercare l’[!DNL IMS org ID] della tua istanza.

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Controllare l’[!DNL IMS Org ID](00:26 min)*

### Diritti di amministratore

I diritti di amministratore sono necessari per accedere al [!UICONTROL Control Panel].
Nel video seguente viene illustrato come aggiungere un amministratore a un’istanza di Campaign.

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Come aggiungere un amministratore al profilo di prodotto “[!UICONTROL Administrators]” per poter utilizzare il[!UICONTROL Control Panel](01:03 min)*

## [!UICONTROL Control Panel] esercitazioni

* **Gestione dei server SFTP**

   *Scopri come monitorare la capacità del server, gli indirizzi[!UICONTROL allow list]IP e aggiungere le chiavi SSH*

   * [Monitoraggio della capacità del server, aggiunta di indirizzi IP all’elenco Consentiti e aggiunta di chiavi SSH](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [Generazione di una chiave SSH](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [Connessione a un server SFTP](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[Delega di sottodomini](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *Scopri come delegare interamente un sottodominio ad[!UICONTROL Adobe Campaign]*

* **[Aggiunta di certificati SSL](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *Scoprite come aggiungere certificati SSL per proteggere i sottodomini utilizzando il Pannello di controllo Campaign.*

* **[Aggiunta di autorizzazioni URL](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *come aggiungere alcuni URL esterni all’elenco degli URL autorizzati, in modo che l’istanza possa connettersi a tali URL.*

* **[Inserimento degli IP nell’elenco Consentiti per l’accesso alle istanze](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *Scoprite come impostare nuove connessioni alle istanze tramite intervalli di indirizzi[!UICONTROL allow listing]IP.*

* **[Gestione dei record TXT di Google](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *Scopri come aggiungere il record di verifica[!DNL Google TXT]del sito a tutti i sottodomini utilizzati per inviare e-mail agli[!DNL GMAIL]indirizzi tramite[!UICONTROL Campaign Control Panel].*

* **Gestione chiave GPG**

   *Scopri come generare e installare una coppia di chiavi pubblica/privata in una specifica istanza di Campaign per la crittografia dei dati in uscita e come importare e installare una chiave pubblica in un’istanza di Campaign per la decrittografia dei dati in entrata:*

   * [Generazione e installazione delle chiavi GPG per la crittografia dei dati](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [Utilizzo di una chiave GPG per crittografare i dati](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [Decrittografia dei dati](./gpg-key-management/decrypting-data.md)

* **[Risoluzione dei problemi relativi al pannello di controllo](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *Come risolvere i problemi[!UICONTROL Control Panel]*

## Risorse aggiuntive

* [Centro assistenza del Pannello di controllo Campaign](https://docs.adobe.com/content/help/it-IT/control-panel/using/control-panel-home.html)

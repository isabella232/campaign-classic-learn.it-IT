---
title: Pannello di controllo Campaign
seo-title: Pannello di controllo Campaign
description: Il Pannello di controllo Campaign consente di monitorare e gestire lo storage SFTP per istanza e  indirizzi IP del elenco consentiti.
seo-description: Il Pannello di controllo Campaign consente di monitorare e gestire lo storage SFTP per istanza e  indirizzi IP del elenco consentiti.
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: 37c36a52fb6fc7a5ccfe5d82dc9a32397b9a7d89
workflow-type: tm+mt
source-wordcount: '441'
ht-degree: 6%

---


# [!UICONTROL Control Panel]

>[!NOTE]
>
>I termini &quot;[!UICONTROL whitelist]&quot; e &quot;[!UICONTROL blacklist]&quot; sono stati sostituiti da &quot;[!UICONTROL allow list]&quot; e &quot;[!UICONTROL block list]&quot; nella documentazione del Adobe Campaign .
>Alcune occorrenze di questi termini possono ancora essere presenti nell&#39;interfaccia utente del prodotto, nei nomi delle opzioni, nel codice interno e nei video delle esercitazioni. Saranno sostituiti nelle prossime release di Pannello di controllo Campaign.

 amministratori di Adobe Campaign [!UICONTROL Control Panel] possono monitorare le risorse chiave ed eseguire attività amministrative, ad esempio gestire lo storage SFTP per istanza o indirizzi [!UICONTROL allow list] IP.

## Accesso [!UICONTROL Control Panel]

Per accedere al Pannello di controllo Campaign, andate  Experience Cloud Home: [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com):

* **[!UICONTROL Experience Cloud Home]** > **[!UICONTROL Quick Access]**

   o
* **[!UICONTROL Experience Cloud Home]**  > [!UICONTROL Solution picker]: **Campaign** > **[!UICONTROL Control Panel]card **

   o

* Direttamente dall’URL: [https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## Prerequisiti

Prima di iniziare, completate i seguenti prerequisiti:

### Conferma [!DNL IMS Org ID]

Deve sapere il suo [!DNL IMS org ID]. Il seguente video descrive le aree in cui è possibile eseguire ricerche nell’istanza [!DNL IMS org ID].

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Check[!DNL IMS Org ID](00:26 min)*

### Diritti di amministratore

I diritti di amministratore sono necessari per accedere al [!UICONTROL Control Panel].
Nel video seguente viene illustrato come aggiungere un amministratore a un&#39;istanza Campaign

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Come aggiungere un amministratore al profilo di prodotto &quot;[!UICONTROL Administrators]&quot; per poter utilizzare[!UICONTROL Control Panel](01:03 min)*

## [!UICONTROL Control Panel] esercitazioni

* **Gestione dei server SFTP**

   *Scopri come monitorare la capacità del server, gli indirizzi[!UICONTROL allow list]IP e aggiungere le chiavi SSH*

   * [Monitoraggio della capacità del server, abilitazione dell&#39;elenco di indirizzi IP e aggiunta di chiavi SSH](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [Generazione di una chiave SSH](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [Connessione a un server SFTP](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[Delega di sottodomini](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *Scopri come delegare completamente un sottodominio a[!UICONTROL Adobe Campaign]*

* **[Aggiunta di certificati SSL](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *Scoprite come aggiungere certificati SSL per proteggere i sottodomini utilizzando il Pannello di controllo Campaign.*

* **[Gestione dei certificati SSL](/help/acc/monitoring-campaign-classic/control-panel/managing-ssl-certificates.md)**

   *Scopri come visualizzare lo stato dei certificati SSL dei tuoi sottodomini, nonché come richiedere rinnovi.*

* **[Aggiunta di autorizzazioni URL](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *come aggiungere alcuni URL esterni all’elenco degli URL autorizzati, in modo che l’istanza possa connettersi a tali URL.*

* **[Inserimento degli IP nell’elenco Consentiti per l’accesso alle istanze](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *Scoprite come impostare nuove connessioni alle istanze tramite intervalli di indirizzi[!UICONTROL allow listing]IP.*

* **[Gestione dei record TXT di Google](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *Scopri come aggiungere il record di verifica[!DNL Google TXT]del sito a tutti i sottodomini utilizzati per inviare e-mail agli[!DNL GMAIL]indirizzi tramite[!UICONTROL Campaign Control Panel].*

* **Gestione chiavi GPG**

   *Scopri come generare e installare una coppia di chiavi pubblica/privata in una specifica istanza Campaign per la crittografia dei dati in uscita, nonché come importare e installare una chiave pubblica in un&#39;istanza Campaign per la decrittazione dei dati in entrata:*

   * [Generazione e installazione di chiavi GPG per la crittografia dei dati](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [Utilizzo di una chiave GPG per cifrare i dati](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [Decrittografare i dati](./gpg-key-management/decrypting-data.md)

* **[Risoluzione dei problemi relativi al pannello di controllo](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *Come risolvere i problemi[!UICONTROL Control Panel]*

## Risorse aggiuntive

* [Pannello di controllo Campaign Help Center](https://docs.adobe.com/content/help/it-IT/control-panel/using/control-panel-home.html)

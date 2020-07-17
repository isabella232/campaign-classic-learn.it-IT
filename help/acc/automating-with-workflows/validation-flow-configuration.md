---
title: Come configurare i flussi di lavoro di convalida in  Adobe Campaign Classic
seo-title: Come configurare i flussi di lavoro di convalida in  Adobe Campaign Classic
description: ' Adobe Campaign offre diverse opzioni che consentono agli esperti di marketing di rivedere e fornire contenuti di distribuzione, target della campagna, estrazione dei dati e approvazioni del budget. Questa esercitazione spiega come configurare diversi flussi di lavoro di convalida dell''approvazione.'
seo-description: In questo video viene illustrato come configurare e utilizzare un modello di consegna in ACCAdobe Campaign, i professionisti del marketing possono rivedere e fornire contenuti di consegna, target della campagna, estrazione dei dati e approvazioni del budget. Questa esercitazione spiega come configurare diversi flussi di lavoro di convalida dell'approvazione.
uuid: fdeb7aef-95aa-4bc1-9c51-2eb7ce802107
discoiquuid: 29abc57d-c359-472d-817a-0671818894f0
feature: Workflow
topics: Validation
kt: KT-1566
doc-type: feature video
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: b2820c65a88d25f9b7a4ed5005cd5083463e000a
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# Come configurare i flussi di lavoro di convalida in  Adobe Campaign Classic

 Adobe Campaign offre diverse opzioni che consentono agli esperti di marketing di rivedere e fornire contenuti di distribuzione, target della campagna, estrazione dei dati e approvazioni del budget.

Questa esercitazione spiega come configurare diversi flussi di lavoro di convalida dell&#39;approvazione.

## Prerequisito {#prerequisite}

Prima di abilitare i passaggi di approvazione, il team marketing deve definire i singoli revisori:

* Il ruolo di revisore  Adobe Campaign all&#39;interno di un&#39;attività di approvazione può essere un singolo revisore (Operatore) o un gruppo di revisori (ruolo Operatore).
* I revisori e i gruppi di revisori devono essere configurati in precedenza  Adobe Campaign da un ruolo Amministratore. Questo consente agli sviluppatori di campagne di selezionare i revisori come approvatori in una campagna o in una distribuzione.

## Configurazione delle approvazioni per le campagne  {#configuring-approvals-for-campaigns}

Se disponete dello stesso set di revisori per tutte le consegne nel flusso di lavoro della campagna, sfrutterete le funzionalità di [!DNL Campaign] approvazione. Impostando approvazioni e revisori a livello di campagna, le attività di approvazione e i revisori verranno ridotti a ogni attività di distribuzione del flusso di lavoro una volta eseguito il flusso di lavoro.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Configurazione delle approvazioni per le consegne  {#configuring-approvals-for-deliveries}

Potete anche impostare le approvazioni a livello di consegna. Se i passaggi di approvazione della distribuzione e i revisori differiscono dai passaggi di approvazione della campagna e dai revisori, le impostazioni di consegna ignoreranno le impostazioni della campagna.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Configurazione di un&#39;attività di approvazione  {#configuring-an-approval-activity}

A differenza delle approvazioni di consegna o campagna, l&#39;attività di approvazione consente di creare un processo di approvazione all&#39;interno di un flusso di lavoro. In questo modo, la logica di selezione del targeting può essere approvata prima dell&#39;avvio della distribuzione. Consente inoltre l&#39;approvazione a più livelli all&#39;interno del flusso di lavoro, se necessario.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

For more information, refer to the [Approval Documentation](https://docs.adobe.com/help/en/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)

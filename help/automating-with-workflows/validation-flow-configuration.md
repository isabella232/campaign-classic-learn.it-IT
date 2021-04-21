---
title: Come configurare i flussi di lavoro di convalida in Adobe Campaign Classic
seo-title: Come configurare i flussi di lavoro di convalida in Adobe Campaign Classic
description: Scopri come configurare diversi flussi di lavoro di convalida dell’approvazione.
seo-description: Questo video spiega come configurare e utilizzare un modello di consegna in ACCAdobe Campaign offre diverse opzioni agli esperti di marketing per rivedere e fornire contenuti di consegna, target della campagna, estrazione dei dati e approvazioni del budget. Questa esercitazione spiega come configurare diversi flussi di lavoro di convalida dell'approvazione.
uuid: fdeb7aef-95aa-4bc1-9c51-2eb7ce802107
discoiquuid: 29abc57d-c359-472d-817a-0671818894f0
feature: Flussi di lavoro, approvazioni
kt: KT-1566
doc-type: feature video
activity: setup
team: TM
role: Business Practitioner
level: Experienced
exl-id: 34fbb91d-ae99-497c-872e-55ce2e6ea2aa
translation-type: tm+mt
source-git-commit: 137d1e0c36d038f3fb8a4742bafef6fbac96f41d
workflow-type: tm+mt
source-wordcount: '336'
ht-degree: 0%

---

# Come configurare i flussi di lavoro di convalida in Adobe Campaign Classic

Adobe Campaign offre diverse opzioni agli esperti di marketing per rivedere e fornire il contenuto di consegna, il target della campagna, l’estrazione dei dati e le approvazioni del budget.

Questa esercitazione spiega come configurare diversi flussi di lavoro di convalida dell&#39;approvazione.

## Prerequisito {#prerequisite}

Prima di abilitare i passaggi di approvazione, il team marketing deve definire i singoli revisori:

* Il ruolo di revisore Adobe Campaign all&#39;interno di un&#39;attività di approvazione può essere un singolo revisore (Operatore) o un gruppo di revisori (ruolo Operatore).
* I revisori e i gruppi di revisori devono essere configurati in precedenza in Adobe Campaign tramite un ruolo Amministratore. Questo consente agli sviluppatori di campagne di selezionare i revisori come approvatori in una campagna o una consegna.

## Configurazione delle approvazioni per le campagne {#configuring-approvals-for-campaigns}

Se disponi dello stesso set di revisori per tutte le consegne nel flusso di lavoro della campagna, puoi sfruttare le funzionalità di approvazione [!DNL Campaign] . Impostando approvazioni e revisori a livello di campagna, le attività di approvazione e i revisori vengono inviati a ogni attività di consegna del flusso di lavoro una volta eseguito il flusso di lavoro.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Configurazione delle approvazioni per le consegne {#configuring-approvals-for-deliveries}

Puoi anche impostare le approvazioni a livello di consegna. Se i passaggi di approvazione della consegna e i revisori differiscono dai passaggi di approvazione della campagna e dai revisori, le impostazioni di consegna sovrascriveranno le impostazioni della campagna.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Configurazione di un’attività di approvazione {#configuring-an-approval-activity}

A differenza delle approvazioni di consegna o campagna, l’attività di approvazione consente di creare un processo di approvazione all’interno di un flusso di lavoro. In questo modo, la logica di selezione del targeting può essere approvata prima dell’avvio della consegna. Inoltre, consente l’approvazione a più livelli all’interno del flusso di lavoro, se necessario.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

Per ulteriori informazioni, consulta la [documentazione di approvazione](https://docs.adobe.com/help/en/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)

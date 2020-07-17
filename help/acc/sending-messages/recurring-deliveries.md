---
title: Come impostare campagne e-mail ricorrenti e continue
description: Questa esercitazione spiega come impostare una consegna periodica e continua e le differenze tra i due approcci in  Adobe Campaign Classic (ACC).
feature: workflows
topics: channel activities
kt: 1560
doc-type: feature video
activity: use
team: TM
translation-type: tm+mt
source-git-commit: d1799d978a9a29f69d637178439fe770ffd4b281
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 0%

---


# Come impostare campagne e-mail ricorrenti e continue

Questa esercitazione spiega come impostare una distribuzione ricorrente e continua e le differenze tra i due approcci.

## Tracciamento continuo e ricorrente {#recurring-and-continuous-delivery-tracking}

Le consegne ricorrenti e continue differiscono nel modo in cui vengono gestiti i dati di contatto:

* La consegna **** continua consente di aggiungere nuovi destinatari a una consegna esistente ed evita di dover creare una nuova consegna ogni volta che viene aggiunto un nuovo destinatario. Potete aggiornare il creativo direttamente nel flusso di lavoro della campagna e il modello verrà aggiornato nella cartella delle risorse del modello di consegna.

   Una consegna continua creerà un singolo log di consegna e consegna (wideLog) e registri di tracciamento che fanno riferimento al fatto che una consegna viene aggiunta ogni volta che viene eseguita.

![Consegna continua](/help/acc/assets/delivery_continuous.jpg)

* Una consegna **** periodica crea una nuova istanza di consegna ogni volta che viene eseguita. Ad esempio, se il flusso di lavoro è pianificato per essere eseguito una volta alla settimana, il risultato sarà 52 Consegne dopo un anno. Ciò significa anche che i log di registro e di monitoraggio ampi saranno separati da ogni istanza di consegna.

![Consegna ricorrente](/help/acc/assets/delivery_recurring.jpg)

## Come impostare una consegna ricorrente {#how-to-set-up-a-recurring-delivery}

In questo video viene illustrato come configurare un&#39;attività di consegna periodica e un&#39;attività di pianificazione.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## Come impostare una consegna continua {#how-to-set-up-a-continuous-delivery}

Questo video mostra come configurare una consegna continua con una query incrementale.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)

## Risorse aggiuntive

[Creazione di una consegna ricorrente in un flusso di lavoro di targeting](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/use-cases/sending-a-birthday-email.html#creating-a-recurring-delivery-in-a-targeting-workflow)
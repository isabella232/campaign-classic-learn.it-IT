---
title: Come impostare campagne e-mail ricorrenti e continue
description: Scopri come impostare una consegna ricorrente e continua e le differenze tra i due approcci.
feature: Flussi di lavoro
kt: 1560
doc-type: feature video
activity: use
team: TM
role: User
level: Beginner
exl-id: 42f2a7e6-7d88-473b-b913-fe09b7016b28
source-git-commit: da757603c597453ef6b7195329b5b44ab6e5c77d
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# Come impostare campagne e-mail ricorrenti e continue

Questo tutorial spiega come impostare una consegna ricorrente e continua, e le differenze tra i due approcci.

## Tracciamento continuo e ricorrente delle consegne {#recurring-and-continuous-delivery-tracking}

Le consegne ricorrenti e continue differiscono nel modo in cui vengono gestiti i dati di contatto:

* La **consegna continua** consente di aggiungere nuovi destinatari a una consegna esistente e di evitare di dover creare una nuova consegna ogni volta che viene aggiunto un nuovo destinatario. Puoi aggiornare il creativo direttamente nel flusso di lavoro della campagna e il modello verrà aggiornato nella cartella Resource del modello di consegna.

   Una consegna continua creerà un singolo log di consegna e consegna (wideLog) e registri di tracciamento che fanno riferimento a tale consegna che vengono aggiunti ogni volta che viene eseguita.

   ![Consegna continua](/help/assets/delivery_continuous.jpg)

* Una **consegna ricorrente** creerà una nuova istanza di consegna ogni volta che viene eseguita. Ad esempio, se il flusso di lavoro è pianificato per essere eseguito una volta alla settimana, in un anno si otterranno 52 consegne. Ciò significa anche che i registri di registro e di tracciamento ampi saranno separati da ogni istanza di consegna.

   ![Consegna ricorrente](/help/assets/delivery_recurring.jpg)

## Come impostare una consegna ricorrente {#how-to-set-up-a-recurring-delivery}

Questo video spiega come configurare una consegna ricorrente e un’attività di pianificazione.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## Come impostare una consegna continua {#how-to-set-up-a-continuous-delivery}

Questo video mostra come configurare una consegna continua con una query incrementale.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)

## Risorse aggiuntive

[Creazione di una consegna ricorrente in un flusso di lavoro di targeting](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/use-cases/deliveries/sending-a-birthday-email.html?lang=en#creating-a-recurring-delivery-in-a-targeting-workflow)

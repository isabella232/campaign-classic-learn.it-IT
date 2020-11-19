---
title: Guida introduttiva alle notifiche push per Android - Introduzione
description: Questo tutorial illustra i passaggi necessari per inviare notifiche push da Adobe Campaign e riceverle nell’app Android.
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 016f47e131df9c3a25b9131da372efaedf6cd5ad
workflow-type: tm+mt
source-wordcount: '365'
ht-degree: 8%

---


# Guida introduttiva alle notifiche push per Android - Introduzione

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android] mobile devices. Questa esercitazione illustra i passaggi necessari per inviare [!DNL push] notifiche da  Adobe Campaign a un&#39; [!DNL Android] app.

## Prerequisiti

Prima di iniziare, è necessario disporre dei seguenti elementi:

1) **Applicazione Android Mobile**

   Questa esercitazione non descrive i passaggi dettagliati necessari per configurare l’applicazione mobile. Sarà necessario disporre di un&#39;applicazione **[!DNL Android]mobile con l&#39; [!DNL Campaign SDK] integrato**.

   La descrizione dettagliata dei passaggi richiesti è disponibile nella documentazione del prodotto:

   [Integrazione dell’SDK Campaign nell’app mobile](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)

   Puoi anche usare l’SDK per dispositivi mobili  Experience Platform. Per ulteriori informazioni, guardate il video dell’esercitazione:

   [Configurare il canale push con l&#39;SDK di Mobile del Experience Platform](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html)

2) **[!DNL Mobile App channel]pacchetto installato**

   Il [!DNL Mobile App channel] pacchetto deve essere installato nell&#39; [!DNL Campaign] istanza. Il seguente video spiega come verificare se l’ [!DNL Mobile App channel] istanza è installata nell’istanza e, in caso contrario, come installarla.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Panoramica delle esercitazioni

Desideriamo inviare una [!DNL push] notifica promozionale personalizzata agli abbonati dell&#39;app [!DNL Neotrip] [!DNL Android] mobile. L&#39; [!DNL Neotrip] app è configurata con l&#39; [!DNL Campaign SDK] e abbiamo verificato che l&#39; [!DNL Mobile App channel] app sia attivata nella nostra [!DNL Campaign] istanza.

Sono necessari i seguenti passaggi di configurazione:

### Passaggio 1: Estendi lo schema di iscrizione all&#39;app per personalizzare [!DNL push] le notifiche

Poiché vorremmo personalizzare la [!DNL push] notifica, [estenderemo lo schema](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) di iscrizione all&#39;app per poter memorizzare i valori di personalizzazione che riceviamo dall&#39;app quando l&#39;utente si iscrive al servizio.

### Passaggio 2: Configurare il servizio Android e creare l&#39;applicazione mobile in Campaign

Successivamente, dovremo [configurare il servizio Android e creare l&#39;applicazione mobile in Campaign](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). In questo passaggio definiremo l&#39; [!DNL Neotrip] app come destinazione per la notifica push.

### Passaggio 3: Configurare e inviare la notifica push

Quindi siamo pronti per [configurare e inviare la notifica](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)push.

## Avviare l&#39;esercitazione

Passaggio 1: [Estendi lo schema di iscrizione dell&#39;app](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)

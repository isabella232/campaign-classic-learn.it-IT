---
title: Guida introduttiva all'esercitazione con le notifiche push per Android - Introduzione
description: Questo tutorial illustra i passaggi necessari per inviare notifiche push da Adobe Campaign e riceverle nell’app Android.
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 412fe93f45be1e98343b4e63cbd7dd9285444e46
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 6%

---


# Guida introduttiva all&#39;esercitazione con le notifiche push per Android - Introduzione

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android ]mobile devices.

Questa esercitazione illustra i passaggi necessari per inviare [!DNL push] notifiche da  Adobe Campaign a un&#39; [!DNL Android] app.

## Prerequisiti

Prima di iniziare, dovrete soddisfare i seguenti prerequisiti

1) Applicazione mobileQuesta esercitazione non descrive i passaggi dettagliati necessari per configurare l&#39;applicazione mobile. Sarà necessario disporre di un&#39;applicazione **[!DNL Android]mobile con l&#39;[!DNL Campaign SDK]** integrato.

   * Puoi trovare una descrizione dettagliata dei passaggi richiesti nell’SDK [Integrating Campaign nell’applicazione](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)mobile.

   * Puoi anche usare l’SDK per dispositivi mobili  Experience Platform. Per ulteriori informazioni, guarda il video [Configurare il canale push con l’esercitazione SDK](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html) Mobile  Experience Platform.

2) Pacchetto Canale app mobile installato

   Dovrai disporre del pacchetto del canale dell&#39;app mobile installato nella tua istanza. Il video seguente spiega come verificare se il canale dell&#39;app mobile è installato nell&#39;istanza e, in caso contrario, come installarlo.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Esercitazione

Desideriamo inviare una notifica push promozionale personalizzata agli abbonati dell&#39;app [!DNL Android] mobile Neotrip. L&#39;app Neotrip è configurata con l&#39;SDK Campaign e ci siamo assicurati che il canale App mobile sia attivato nell&#39;istanza Campaign.

Sono necessari i seguenti passaggi di configurazione:

### Passaggio 1: Estendi lo schema di iscrizione dell&#39;app per personalizzare le notifiche push

Poiché vorremmo personalizzare la notifica push, [estenderemo lo schema](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) di iscrizione all&#39;app per poter memorizzare i valori di personalizzazione che riceviamo dall&#39;app quando l&#39;utente si iscrive al servizio.

### Passaggio 2: Configurare il servizio Android e creare l&#39;applicazione app mobile in Campaign

A questo punto, dovremo [configurare il servizio Android e creare l&#39;applicazione per app mobile in Campaign](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). In questo passaggio definiremo l&#39;app Neotrip come destinazione per la notifica push.

### Passaggio 3: Configurare e inviare la notifica push

Quindi siamo pronti per [configurare e inviare la notifica](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)push.

## Avviare l&#39;esercitazione

**[Passaggio 1: Estendi lo schema di iscrizione dell&#39;app](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)**

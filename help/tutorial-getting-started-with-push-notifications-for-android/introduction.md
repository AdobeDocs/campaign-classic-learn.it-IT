---
title: 'Guida introduttiva alle notifiche push per Android: introduzione'
description: Questo tutorial illustra i passaggi necessari per inviare notifiche push da Adobe Campaign e riceverle nell’app Android.
feature: Push
jira: KT-5951
doc-type: article
activity: setup
team: TM
role: Admin, Developer
level: Experienced
recommendations: noDisplay
exl-id: 291c2e3a-c126-439d-9753-06a4091bbda0
TQID: 'https://experienceleague.adobe.com/TT6QItpOh4g1nyiefu-aK5h0kUV0y-uwgKlNbk-KNwY'
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
  - id: fd6e6e36-54e4-4f1a-96fc-1a750e400d50
    internal-label: Campaign Classic v7
feature_v2:
  - id: a4671286-a59f-47e3-b97b-90627a1977d5
    internal-label: Communication channels
subfeature_v2:
  - id: a4657621-810c-498b-8a27-7ced9c176dda
    internal-label: Push notifications
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
  - id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
    internal-label: Developer
level_v2:
  - id: d378ca77-2da1-4f39-ad92-1917fe974a38
    internal-label: Experienced
topic_v2:
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
source-git-commit: d4d4654e5b2dee85947373b8dcf139754844b316
workflow-type: ht
source-wordcount: '388'
ht-degree: 100%
---
# Guida introduttiva alle notifiche push per Android: introduzione

Adobe Campaign ti consente di inviare notifiche [!DNL push] personalizzate e segmentate ai dispositivi mobili [!DNL iOS] e [!DNL Android]. Questo tutorial illustra i passaggi necessari per inviare le notifiche [!DNL push] da Adobe Campaign a un’app [!DNL Android].

## Prerequisiti

Prima di iniziare, è necessario disporre dei seguenti elementi:

1) **Applicazione Android mobile**

   Questo tutorial non descrive i passaggi dettagliati necessari per configurare l’applicazione mobile. Sarà necessario disporre di un’applicazione mobile **[!DNL Android]con [!DNL Campaign SDK] integrato**.

   La descrizione dettagliata dei passaggi necessari è disponibile nella documentazione del prodotto:

   [Integrazione di Campaign SDK nell’app mobile](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=it)

   Puoi anche usare l’SDK mobile di Experience Platform. Per ulteriori informazioni, guarda il video del tutorial:

   [Configurare il canale push con Experience Platform Mobile SDK](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html?lang=it)

2) Pacchetto **[!DNL Mobile App channel]installato**

   Il pacchetto [!DNL Mobile App channel] deve essere installato nell’istanza [!DNL Campaign]. Il seguente video spiega come verificare se [!DNL Mobile App channel] è installato nell’istanza indicata e, in caso contrario, come installarlo.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12&learn=on){transcript=true}

## Panoramica del tutorial

Il nostro obiettivo è quello di inviare una notifica promozionale [!DNL push] personalizzata agli abbonati dell’app mobile [!DNL Neotrip] [!DNL Android]. L’app [!DNL Neotrip] è configurata con [!DNL Campaign SDK] e abbiamo verificato che [!DNL Mobile App channel] è attivo nell’istanza [!DNL Campaign].

Sono necessari i seguenti passaggi di configurazione:

### Passaggio 1: estendere lo schema di iscrizione all’app per personalizzare le notifiche [!DNL push]

Poiché vorremmo personalizzare la notifica [!DNL push], prima [estenderemo lo schema di iscrizione all’app](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) per poter archiviare i valori di personalizzazione che questa invia quando l’utente si iscrive al servizio.

### Passaggio 2: configurare il servizio Android e creare l’applicazione mobile in Campaign

Successivamente, sarà necessario [configurare il servizio Android e creare l’applicazione mobile in Campaign](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md). In questo passaggio definiremo l’app [!DNL Neotrip] come destinazione per la notifica push.

### Passaggio 3: configurare e inviare la notifica push

Siamo infine pronti a [configurare e inviare la notifica push](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md).

## Inizia l’esercitazione

Passaggio 1: [estendere lo schema di iscrizione all’app](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)

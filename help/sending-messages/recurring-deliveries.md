---
title: Configurare campagne e-mail ricorrenti e continue
description: Scopri come impostare una consegna ricorrente e continua e le differenze tra i due approcci.
feature: Workflows, Campaigns
jira: KT-1560
doc-type: feature video
activity: use
team: TM
role: User
level: Beginner
exl-id: 42f2a7e6-7d88-473b-b913-fe09b7016b28
source-git-commit: f4e86b933660ced199c30d318445363b74c51c4b
workflow-type: tm+mt
source-wordcount: '239'
ht-degree: 50%

---

# Configurare campagne e-mail ricorrenti e continue

Questo tutorial spiega come impostare una consegna ricorrente e continua, e le differenze tra i due approcci.

## Tracciamento continuo e ricorrente delle consegne {#recurring-and-continuous-delivery-tracking}

Le consegne ricorrenti e continue differiscono nel modo in cui vengono gestiti i dati di contatto:

* Il **consegna continua** consente di aggiungere nuovi destinatari a una consegna esistente ed evita di dover crearne una nuova ogni volta che viene aggiunto un destinatario. Puoi aggiornare il contenuto creativo direttamente nel flusso di lavoro della campagna, mentre il modello verrà aggiornato nella cartella Risorse del modello di consegna.

  Una consegna continua creerà un SINGOLO registro di consegna e consegna (broadLog) e registri di tracciamento che fanno riferimento a tale consegna aggiunti ogni volta che viene eseguita.

  ![Consegna continua](/help/assets/delivery_continuous.jpg)

* A **consegna ricorrente** creerà una nuova istanza di consegna ogni volta che viene eseguita. Ad esempio, se il flusso di lavoro è pianificato per essere eseguito una volta alla settimana, in un anno si otterranno 52 consegne. Ciò significa anche che i log ampi e quelli di tracciamento saranno separati per ogni istanza di consegna.

  ![Consegna ricorrente](/help/assets/delivery_recurring.jpg)

## Come impostare una consegna ricorrente {#how-to-set-up-a-recurring-delivery}

Questo video spiega come configurare una consegna ricorrente e un’attività di pianificazione.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12&learn=on)

## Come impostare una consegna continua {#how-to-set-up-a-continuous-delivery}

Questo video mostra come configurare una consegna continua con una query incrementale.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12&learn=on)

---
title: Configurare i flussi di lavoro di convalida in Adobe Campaign Classic
description: Scopri come configurare diversi flussi di lavoro di convalida dell’approvazione.
feature: Workflows, Approvals
jira: KT-1566
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: 34fbb91d-ae99-497c-872e-55ce2e6ea2aa
source-git-commit: 35e036486c5b533b54b3f626d88734e9a9fc3b8a
workflow-type: tm+mt
source-wordcount: '268'
ht-degree: 96%

---


# Creare flussi di lavoro di convalida

Adobe Campaign offre agli esperti di marketing diverse opzioni per rivedere e fornire il contenuto da recapitare, il target della campagna, l’estrazione dei dati e le approvazioni del budget.

Questo tutorial spiega come configurare diversi flussi di lavoro per la convalida dell’approvazione.

## Prerequisito {#prerequisite}

Prima di abilitare i passaggi di approvazione, il team di marketing deve definire i singoli revisori:

* Il ruolo di revisore Adobe Campaign all’interno di un’attività di approvazione può essere un singolo revisore (Operatore) o un gruppo di revisori (ruolo Operatore).
* Per consentire agli sviluppatori di campagne di selezionare i revisori come approvatori in una campagna o una consegna, i revisori e i gruppi di revisori devono essere configurati in Adobe Campaign da un amministratore.

## Configurazione delle approvazioni per le campagne  {#configuring-approvals-for-campaigns}

Se uno stesso gruppo revisori si occupa di tutte le consegne nel flusso di lavoro della campagna, puoi applicare la funzionalità di approvazione impostando approvazioni e revisori a livello di campagna. Quando il flusso di lavoro viene eseguito, le attività di approvazione e i revisori vengono applicati a ogni sua attività di consegna.

>[!VIDEO](https://video.tv.adobe.com/v/329899?quality=12&learn=on&captions=ita){transcript=true}

## Configurazione delle approvazioni per le consegne  {#configuring-approvals-for-deliveries}

Puoi anche impostare le approvazioni a livello di consegna. Se i passaggi di approvazione e i revisori di una consegna differiscono da quelli della campagna, le impostazioni specifiche della consegna hanno la precedenza rispetto a quelle della campagna.

>[!VIDEO](https://video.tv.adobe.com/v/329901?quality=12&learn=on&captions=ita){transcript=true}

## Configurazione di un’attività di approvazione  {#configuring-an-approval-activity}

A differenza delle approvazioni per consegne o campagne, l’attività di approvazione consente di creare un processo di approvazione all’interno di un flusso di lavoro. In questo modo, la logica di selezione del targeting può essere approvata prima dell’avvio della consegna stessa. Inoltre, se necessario, consente l’approvazione a più livelli all’interno del flusso di lavoro.

>[!VIDEO](https://video.tv.adobe.com/v/329902?quality=12&learn=on&captions=ita){transcript=true}

Per ulteriori informazioni, consulta la [documentazione sulle approvazioni](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=it)

---
title: Entenda o Journey Orchestration
description: Entenda o conceito do Journey Orchestration, os tipos de casos de uso que ele permite e os elementos-chave do funcionamento desse serviço.
feature: Overview
topics: Introduction
jira: KT-2773
thumbnail: 29307.jpg
audience: user, developer
doc-type: video
activity: understand
role: User, Admin
exl-id: db4f69bb-183c-4376-9791-eb6b1f78ab32
source-git-commit: 9db2765ee5e9520280711a6b1fe3c618963f6f87
workflow-type: tm+mt
source-wordcount: '280'
ht-degree: 100%

---

# Noções básicas do [!UICONTROL Journey Orchestration]

O [!UICONTROL Journey Orchestration] permite criar casos de uso de orquestração em tempo real, aproveitando dados contextuais armazenados em eventos ou fontes de dados.

## Introdução ao [!UICONTROL Journey Orchestration]

O [!UICONTROL Journey Orchestration] é um serviço de aplicativos integrado à Adobe Experience Platform. Ele fornece um ambiente inteligente e aberto para ativar todos os dados relevantes por meio de envolvimento escalável e baseado em eventos em qualquer canal que sua empresa exija, seja marketing, operações ou serviços. O [!UICONTROL Journey Orchestration] pode aproveitar todos os dados da Adobe Experience Platform e de qualquer sistema de delivery externo para criar e fornecer experiências atraentes.

O vídeo abaixo apresenta

* O conceito do [!UICONTROL Journey Orchestration]
* Os tipos de utilização que ele ativa
* Os principais elementos de como o [!UICONTROL Journey Orchestration] funciona

>[!VIDEO](https://video.tv.adobe.com/v/29307?learn=on){transcript=true}

## Como configurar uma jornada

As principais etapas de preparação para as jornadas de construção são:

1. [Configurar eventos de transmissão](/help/configuring-journey-orchestration/configure-streaming-events.md) - essa configuração é obrigatória, pois o [!UICONTROL Journey Orchestration] é projetado para ouvir eventos.
1. [Configurar fontes de dados](/help/configuring-journey-orchestration/configure-data-sources.md) - essa configuração não é necessária se suas jornadas utilizarem somente os dados locais provenientes de uma carga do evento.
1. [Configurar ações personalizadas](/help/configuring-journey-orchestration/configure-actions.md): é obrigatório caso você queira usar um serviço de qualquer provedor de terceiros que possa ser chamado por meio de uma [!DNL REST API] com uma carga de formato JSON

>[!NOTE]
>
>Essas etapas de configuração exigem conhecimento técnico. Você precisa conhecer o [Experience Data Model (XDM)](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/schemas-and-experience-data-model.html?lang=pt-BR) e saber [como compor esquemas de evento de experiência XDM](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html?lang=pt-BR).

## Como criar, publicar e analisar uma jornada

1. [Criar uma jornada](/help/building-a-journey/creating-a-journey.md)
1. [Validar e publicar uma jornada](/help/validate-and-publish-a-journey.md)
1. [Analisar uma jornada através das ferramentas de relatório](/help/analyze-a-journey-via-reporting-tools.md)

## Recursos adicionais

* [Centro de ajuda do Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=pt-BR)
* [Tutoriais da Adobe Experience Platform](https://experienceleague.adobe.com/docs/platform-learn/tutorials/overview.html?lang=pt-BR)
* [Como obter ajuda com o Journey Orchestration](/help/understanding-journey-orchestration.md)
* [Adobe Experience Platform Mobile SDK - Iniciar](https://experienceleague.adobe.com/docs/platform-learn/data-collection/mobile-sdk/overview.html?lang=pt-BR)
* [Serviço de localização da Adobe Experience Platform](https://experienceleague.adobe.com/docs/places/using/home.html?lang=pt-BR)

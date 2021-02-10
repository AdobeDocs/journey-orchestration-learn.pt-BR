---
title: Conheça o Journey Orchestration
description: Entenda o conceito do Journey Orchestration, os tipos de utilização que ele permite e os elementos-chave do seu funcionamento.
feature: Journey Orchestration
topics: Introduction
kt: 2773
thumbnail: 29307.jpg
audience: user, developer
doc-type: video
activity: understand
translation-type: ht
source-git-commit: 8b8b26c5913717520e84aa9d5aa783c2c3434214
workflow-type: ht
source-wordcount: '326'
ht-degree: 100%

---


# Noções básicas do [!UICONTROL Journey Orchestration]

## Introdução ao [!UICONTROL Journey Orchestration]

O [!UICONTROL Journey Orchestration] permite criar casos de uso de orquestração em tempo real, aproveitando dados contextuais armazenados em eventos ou fontes de dados.

O [!UICONTROL Journey Orchestration] é um serviço de aplicativos integrado à Adobe Experience Platform. Ele fornece um ambiente inteligente e aberto para ativar todos os dados relevantes por meio de envolvimento escalável e baseado em eventos em qualquer canal que sua empresa exija, seja marketing, operações ou serviços. O [!UICONTROL Journey Orchestration] pode aproveitar todos os dados da Adobe Experience Platform e de qualquer sistema de delivery externo para criar e fornecer experiências atraentes.

O vídeo abaixo apresenta

* O conceito do [!UICONTROL Journey Orchestration]
* Os tipos de utilização que ele ativa
* Os principais elementos de como o [!UICONTROL Journey Orchestration] funciona

>[!VIDEO](https://video.tv.adobe.com/v/29307?quality=12&captions=por_br)

## Como configurar uma jornada

As principais etapas de preparação para as jornadas de construção são:

1. [Configurar eventos de transmissão](/help/configuring-journey-orchestration/configure-streaming-events.md) - essa configuração é obrigatória, pois o [!UICONTROL Journey Orchestration] é projetado para ouvir eventos.
1. [Configurar fonte de dados](/help/configuring-journey-orchestration/configure-data-sources.md) - essa configuração não é necessária se suas jornadas utilizarem somente os dados locais provenientes de uma payload do evento.
1. [Configurar ações personalizadas](/help/configuring-journey-orchestration/configure-actions.md): é necessário caso você queira usar um serviço de qualquer provedor de terceiros que possa ser chamado por meio de uma [!DNL REST API] com uma carga de formato JSON

>[!NOTE]
>
>Essas etapas de configuração exigem conhecimento técnico. Você precisa conhecer o [Experience Data Model (XDM)](https://docs.adobe.com/content/help/pt-BR/platform-learn/tutorials/schemas/understanding-the-xdm-system-and-experience-data-model.html) e [como compor schemas de evento de experiência XDM](https://docs.adobe.com/content/help/pt-BR/platform-learn/tutorials/schemas/create-your-first-schema-with-out-of-the-box-components.html).

## Como criar, publicar e analisar uma jornada

1. [Criar uma jornada](/help/building-a-journey/creating-a-journey.md)
1. [Validar e publicar uma jornada](/help/validate-and-publish-a-journey.md)
1. [Analisar uma jornada através das ferramentas de relatório](/help/analyze-a-journey-via-reporting-tools.md)

## Recursos adicionais

* [Centro de ajuda do Journey Orchestration](https://docs.adobe.com/content/help/pt-BR/journeys/using/journey-orchestration-home.html)
* [Tutoriais da Adobe Experience Platform](https://docs.adobe.com/content/help/pt-BR/platform-learn/tutorials/overview.html)
* [Como obter ajuda com o Journey Orchestration](/help/understanding-journey-orchestration.md)
* [Adobe Experience Platform Mobile SDK - Iniciar](https://docs.adobe.com/content/help/pt-BR/core-services-learn/tutorials/launch-mobile/understanding-the-mobile-sdks.html)
* [Serviço de localização da Adobe Experience Platform](https://docs.adobe.com/content/help/pt-BR/places/using/home.html)

---
title: Visão geral do produto — Kit de Desenvolvedor Jetson AGX Orin
description: >-
  O que é o kit de desenvolvedor NVIDIA Jetson AGX Orin (64GB), para que serve e
  qual é o seu lugar na gama Jetson Orin.
---

# Visão geral do produto

![Jetson AGX Orin Developer Kit](../../images/jetson-agx-orin/jaodk_1024px.png)

O Kit de Desenvolvedor NVIDIA® Jetson AGX Orin™ é o kit de desenvolvedor de
topo da família Jetson Orin: um computador de IA compacto para desenvolver e
prototipar aplicações de robótica, visão computacional e IA generativa na
borda. Este guia aborda o kit de desenvolvedor de **64GB**.

## Factos principais (verificados na documentação da NVIDIA)

- O kit de desenvolvedor partilha **uma mesma arquitetura de SoC com todos os
  módulos Jetson Orin**, pelo que pode **emular o desempenho e a potência** dos
  módulos AGX Orin, Orin NX ou Orin Nano através de regravação. Vem configurado
  de fábrica para a **série Jetson AGX Orin**. *(Guia do Utilizador do Kit de
  Desenvolvedor)*
- A NVIDIA avalia a família de módulos AGX Orin em **até 275 TOPS** de
  desempenho de IA, com potência configurável entre **15W e 60W**. *(página de
  produto da NVIDIA)*
- A GPU do módulo de 64GB é uma **GPU de arquitetura NVIDIA Ampere com 2048
  núcleos e 64 Tensor Cores**. *(página de produto da NVIDIA, tabela
  comparativa)*
- A placa carrier de referência incluída expõe interfaces padrão — DisplayPort,
  Ethernet 10GBASE-T, USB 3.2, M.2 (NVMe e Wi-Fi), header de 40 pinos, PCIe,
  conector de câmara e muito mais. Consulte
  **[Interfaces e Layout de Hardware](./interfaces.md)**.

## Para que serve o kit de desenvolvedor

- **Desenvolvimento e prototipagem** — o kit é a plataforma de referência para
  aplicações que virão a ser executadas em módulos Jetson Orin em produção.
- **Exploração de desempenho e potência** — como emula os outros módulos Orin,
  um único kit permite testar cargas de trabalho em toda a gama de módulos
  antes de optar por um componente de produção.
- **Cargas de trabalho de IA de borda** — visão computacional, robótica e IA
  generativa local (consulte a nossa secção de tutoriais, que está a crescer).

> **Nota da Juxi:** Os produtos de produção são construídos sobre *módulos*
> Jetson Orin (versões de 64GB / 32GB / Industrial) montados numa placa carrier
> sua ou de um parceiro. O kit de desenvolvedor é o veículo de desenvolvimento,
> não o componente de produção.

## Conteúdo da caixa

Módulo Jetson AGX Orin e placa carrier de referência, módulo Wi-Fi, fonte de
alimentação USB Type-C e um cabo USB Type-C para USB Type-A. Para saber o que
precisa de fornecer, consulte o
**[Início Rápido](./quick-start.md)**.

## Próximos passos

- **[Início Rápido](./quick-start.md)** — da caixa a um sistema JetPack 7.2.1 funcional
- **[Interfaces e Layout de Hardware](./interfaces.md)** — todas as portas e conectores
- **[Downloads](./downloads.md)** — imagens oficiais, ferramentas e ligações de documentação *(página em preparação)*

## Fontes

- [Jetson AGX Orin Developer Kit User Guide — Introduction](https://docs.nvidia.com/jetson/agx-orin-devkit/user-guide/latest/index.html) (verificado em 2026-09-23)
- [Página de produto NVIDIA Jetson Orin](https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/jetson-orin/) (verificado em 2026-09-23)

**Créditos da imagem:** Imagem do produto proveniente do *Jetson AGX Orin
Developer Kit User Guide* oficial da NVIDIA (descarregada em 2026-09-23),
© NVIDIA Corporation.

---

NVIDIA® e Jetson™ são marcas registadas da NVIDIA Corporation. Esta página é
publicada pela Juxi Technology e não é uma publicação da NVIDIA.

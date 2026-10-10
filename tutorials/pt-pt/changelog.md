---
title: Registo de alterações
description: >-
  Atualizações deste conjunto de documentação e o histórico de versões do
  JetPack para o Kit de Desenvolvedor Jetson AGX Orin.
---

# Registo de alterações

## Atualizações da documentação

| Data | Alteração |
|---|---|
| 2026-09-26 | **Corrigidas duas versões de componentes do JetPack 7.2.1: CUDA 13.2.1 → 13.2.2 e VPI 4.1.3 → 4.1.4.** Ambas tinham sido obtidas a partir da página de transferências do JetPack da NVIDIA, cuja tabela de resumo ainda apresenta os valores do JetPack **7.2**; as versões foram verificadas através da cadeia de dependências do `nvidia-jetpack` 7.2.1 no repositório apt da NVIDIA para Jetson. Atualizadas as páginas **Verificar o sistema** (nota de origem da tabela), **Glossário**, **FAQ** e a página do produto, bem como o **guia de migração do JetPack 6.x → 7.2**. Adicionada também uma advertência de que “esta tabela está desatualizada” sempre que essa página é citada como fonte das versões dos componentes (**Downloads**, **Glossário**, **DeepStream**, **guia de migração**). |
| 2026-09-26 | **Corrigido o estado do Isaac ROS no JetPack 7.2.** O Isaac ROS 4.6.0 (2026-08-18) adicionou suporte para Jetson Orin + JetPack 7.2, substituindo o estado “brevemente” que tinha sido obtido a partir da página de transferências do JetPack (que ainda o mostra). Atualizadas as páginas **Robótica** (nova versão e orientações sobre a distribuição do ROS 2), **Verificar o sistema** e **FAQ**, bem como o **guia de migração do JetPack 6.x → 7.2**. |
| 2026-09-24 | Adicionados o **Glossário** e este **Registo de alterações**. Adicionadas as informações de contacto da Juxi Technology (suporte técnico, vendas, questões sobre produtos) às páginas FAQ, Resolução de problemas e Downloads; adicionada a ligação ao catálogo de produtos da Juxi para acessórios. |
| 2026-09-23 | Conjunto inicial de documentação publicado como rascunho: Início rápido, Gravação e atualizações, Verificar o sistema, Visão geral do produto, Interfaces e layout do hardware, FAQ, Resolução de problemas, Downloads e o guia de migração do JetPack 6.x → 7.2. Todas as páginas escritas com base na documentação oficial da NVIDIA. |

## Versões do JetPack para este kit

| JetPack | Jetson Linux (L4T) | Data | Notas |
|---|---|---|---|
| **7.2.1** | **39.2.1** | 2026-08 | **Atual.** Correções e atualizações de segurança; emulação T3000; competências de agente para pipelines de vídeo. |
| 7.2 | 39.2.0 | 2026-06 | Primeira versão que integra a família Jetson Orin no JetPack 7 (Ubuntu 24.04, kernel 6.8, CUDA 13). |
| 6.x | 36.x | 2024–2025 | Geração anterior (Ubuntu 22.04, kernel 5.15, CUDA 12) — consulte os arquivos se ainda estiver nessa versão, e o nosso [guia de migração](./jetpack-6-to-7.md). |

Histórico completo: [JetPack Archive](https://developer.nvidia.com/embedded/jetpack-archive) · [Jetson Linux Archive](https://developer.nvidia.com/embedded/jetson-linux-archive)

Para atualizar o seu kit, consulte **[Gravação e atualizações](./flashing-and-updates.md)**;
para verificar o que está a executar, consulte **[Verifique o seu sistema](./verify-your-system.md)**.

## Fontes

- [JetPack SDK Downloads](https://developer.nvidia.com/embedded/jetpack/downloads) (verificado em 2026-09-24)
- [Jetson Linux 39.2.0 Release Notes (PDF)](https://docs.nvidia.com/jetson/archives/r39.2/ReleaseNotes/Jetson_Linux_Release_Notes_r39.2.pdf) (verificado em 2026-09-24)

---

NVIDIA® e Jetson™ são marcas comerciais da NVIDIA Corporation. Esta página é
publicada pela Juxi Technology e não é uma publicação da NVIDIA.

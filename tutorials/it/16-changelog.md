---
title: Registro delle modifiche
description: >-
  Aggiornamenti a questo set di documentazione e la cronologia delle versioni
  di JetPack per il kit di sviluppo Jetson AGX Orin.
---

# Registro delle modifiche

## Aggiornamenti della documentazione

| Data | Modifica |
|---|---|
| 2026-09-26 | **Corrette due versioni dei componenti per JetPack 7.2.1: CUDA 13.2.1 → 13.2.2 e VPI 4.1.3 → 4.1.4.** Entrambe erano state ricavate dalla pagina dei download di JetPack di NVIDIA, la cui tabella riepilogativa riporta ancora i valori di JetPack **7.2**; le versioni sono state verificate attraverso la catena di dipendenze di `nvidia-jetpack` 7.2.1 nel repository apt di NVIDIA per Jetson. Aggiornati **Verificare il sistema** (nota sulla fonte della tabella), il **Glossario**, le **FAQ**, la **guida alla migrazione da JetPack 6.x a 7.2** e la pagina prodotto. Aggiunto inoltre un avviso "questa tabella è in ritardo" ovunque quella pagina sia citata come fonte per le versioni dei componenti (**Download**, **Glossario**, **DeepStream**, **guida alla migrazione**). |
| 2026-09-26 | **Corretto lo stato di Isaac ROS su JetPack 7.2.** Isaac ROS 4.6.0 (2026-08-18) ha aggiunto il supporto per Jetson Orin + JetPack 7.2, superando lo stato "in arrivo" ricavato in precedenza dalla pagina dei download di JetPack (che lo mostra ancora). Aggiornati **Robotica** (nuova versione e indicazioni sulla distribuzione ROS 2), **Verificare il sistema**, la **guida alla migrazione da JetPack 6.x a 7.2** e le **FAQ**. |
| 2026-09-24 | Aggiunti il **Glossario** e questo **Registro delle modifiche**. Aggiunte le informazioni di contatto di Juxi Technology (supporto tecnico, vendite, domande sui prodotti) a FAQ, Risoluzione dei problemi e Download; aggiunto il link al catalogo prodotti di Juxi Technology per gli accessori. |
| 2026-09-23 | Set di documentazione iniziale pubblicato: Avvio rapido, Flashing e aggiornamenti, Verificare il sistema, Panoramica del prodotto, Interfacce e layout hardware, FAQ, Risoluzione dei problemi, Download e la guida alla migrazione da JetPack 6.x a 7.2. Tutte le pagine sono state redatte sulla base della documentazione ufficiale di NVIDIA. |

## Versioni di JetPack per questo kit

| JetPack | Jetson Linux (L4T) | Data | Note |
|---|---|---|---|
| **7.2.1** | **39.2.1** | 2026-08 | **Attuale.** Correzioni e aggiornamenti di sicurezza; emulazione T3000; competenze agente per pipeline video. |
| 7.2 | 39.2.0 | 2026-06 | Prima versione che porta la famiglia Jetson Orin in JetPack 7 (Ubuntu 24.04, kernel 6.8, CUDA 13). |
| 6.x | 36.x | 2024–2025 | Generazione precedente (Ubuntu 22.04, kernel 5.15, CUDA 12) — consulti gli archivi se la sta ancora utilizzando, e la nostra [guida alla migrazione](./11-jetpack-6-to-7.md). |

Cronologie complete: [JetPack Archive](https://developer.nvidia.com/embedded/jetpack-archive) · [Jetson Linux Archive](https://developer.nvidia.com/embedded/jetson-linux-archive)

Per aggiornare il suo kit, consulti **[Flashing e aggiornamenti](./02-flashing-and-updates.md)**;
per verificare cosa sta eseguendo, consulti **[Verificare il sistema](./03-verify-your-system.md)**.

## Fonti

- [JetPack SDK Downloads](https://developer.nvidia.com/embedded/jetpack/downloads) (verificato il 2026-09-24)
- [Jetson Linux 39.2.0 Release Notes (PDF)](https://docs.nvidia.com/jetson/archives/r39.2/ReleaseNotes/Jetson_Linux_Release_Notes_r39.2.pdf) (verificato il 2026-09-24)

---

NVIDIA® e Jetson™ sono marchi di NVIDIA Corporation. Questa pagina è pubblicata
da Juxi Technology e non è una pubblicazione NVIDIA.

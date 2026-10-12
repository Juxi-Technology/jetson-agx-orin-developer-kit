# Jetson AGX Orin Developer Kit — Documentation

Product documentation for the **NVIDIA® Jetson AGX Orin™ Developer Kit (64GB)**, distributed by [Juxi Technology](https://www.juxitech.com).

The same documentation is published at **[wiki.juxitech.com](https://wiki.juxitech.com/tutorials/jetson-agx-orin/quick-start)**.

## Contents — English

| Page | |
|---|---|
| [Quick Start](tutorials/en/01-quick-start.md) | From unboxing to a working JetPack 7.2.1 system |
| [Flashing & Updates](tutorials/en/02-flashing-and-updates.md) | BSP installation options and Force Recovery mode |
| [Verify Your System](tutorials/en/03-verify-your-system.md) | Version and component checklist |
| [Product Overview](tutorials/en/04-overview.md) | What the kit is and where it fits |
| [Interfaces & Hardware Layout](tutorials/en/05-interfaces.md) | Ports, connectors, and board layout |
| [Local LLM Inference](tutorials/en/06-local-llm.md) | TensorRT Edge-LLM on AGX Orin |
| [Agentic AI (NemoClaw)](tutorials/en/07-agentic-ai.md) | Agentic stack on JetPack 7.2 |
| [DeepStream Video Analytics](tutorials/en/08-deepstream.md) | Multi-stream video pipelines |
| [Robotics — State of Play](tutorials/en/09-robotics.md) | ROS 2 and Isaac ROS status |
| [Memory Efficiency](tutorials/en/10-memory-efficiency.md) | Running bigger workloads on 64GB |
| [Migrate from JetPack 6.x](tutorials/en/11-jetpack-6-to-7.md) | Upgrade path and rebuild checklist |
| [Downloads & Official Links](tutorials/en/12-downloads.md) | NVIDIA official resources |
| [FAQ](tutorials/en/13-faq.md) · [Troubleshooting](tutorials/en/14-troubleshooting.md) | Common questions and fixes |
| [Glossary](tutorials/en/15-glossary.md) · [Changelog](tutorials/en/16-changelog.md) | Terms and documentation history |

Product page: **[English](products/en/jetson-agx-orin-devkit.md)**

## Contents — other languages

Each language contains the full 16-page series and the product page.

- [简体中文](tutorials/zh-hans/01-quick-start.md) · [繁體中文](tutorials/zh-hant/01-quick-start.md)
- [日本語](tutorials/ja/01-quick-start.md) · [한국어](tutorials/ko/01-quick-start.md)
- [Deutsch](tutorials/de/01-quick-start.md) · [Français](tutorials/fr/01-quick-start.md)
- [Español](tutorials/es/01-quick-start.md) · [Italiano](tutorials/it/01-quick-start.md)
- [Português (BR)](tutorials/pt-br/01-quick-start.md) · [Português (PT)](tutorials/pt-pt/01-quick-start.md)

## XLeRobot Docker tutorials

A separate tutorial set ships in [`xlerobot-docker-tutorials/`](xlerobot-docker-tutorials/README.md): pulling and running the prebuilt XLeRobot Docker image on a Jetson, then driving either a whole XLeRobot (two arms + base, 17 servos) or a single SO-ARM101 arm (12 servos). **11 languages**, six pages each.

| # | Folder | Contents |
|:--:|---|---|
| 1 | [`deployment/`](xlerobot-docker-tutorials/en/deployment/01-Overview.md) | Pull the image and start the container — read `01-Overview` → `02-Environment-Setup` → `03-Deployment` in order |
| 2 | [`xlerobot/`](xlerobot-docker-tutorials/en/xlerobot/01-Operation.md) | Operation commands for a whole XLeRobot |
| 3 | [`lerobot/`](xlerobot-docker-tutorials/en/lerobot/01-Operation.md) | Operation commands for a single SO-ARM101 or a LeKiwi |
| 4 | [`troubleshooting/`](xlerobot-docker-tutorials/en/troubleshooting/01-Troubleshooting.md) | Common problems and a quick-reference cheat sheet |

> Folders 2 and 3 are **alternatives** — pick the one that matches your hardware. Entry points for all 11 languages are listed in [`xlerobot-docker-tutorials/README.md`](xlerobot-docker-tutorials/README.md).

## Repository layout

- `tutorials/<language>/` — the documentation series (16 pages per language)
- `products/<language>/` — product page
- `xlerobot-docker-tutorials/<language>/` — the XLeRobot Docker tutorial set (six pages per language)
- `images/` — figures from NVIDIA's official documentation

## Links

- Documentation site: [wiki.juxitech.com](https://wiki.juxitech.com/)
- Store: [juxitech.com](https://www.juxitech.com/)
- Technical support: support@juxitech.com · Sales: sales@juxitech.com

---

NVIDIA® and Jetson™ are trademarks of NVIDIA Corporation. This documentation is published by Juxi Technology and is not an NVIDIA publication.

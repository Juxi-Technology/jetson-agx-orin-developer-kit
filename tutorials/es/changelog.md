---
title: Registro de cambios
description: >-
  Actualizaciones de este conjunto de documentación y el historial de versiones
  de JetPack para el kit de desarrollo Jetson AGX Orin.
---

# Registro de cambios

## Actualizaciones de la documentación

| Fecha | Cambio |
|---|---|
| 2026-09-26 | **Se corrigieron dos versiones de componentes para JetPack 7.2.1: CUDA 13.2.1 → 13.2.2 y VPI 4.1.3 → 4.1.4.** Ambas se habían tomado de la página de descargas de JetPack de NVIDIA, cuya tabla resumen sigue mostrando valores de JetPack **7.2**; las versiones se verificaron a través de la cadena de dependencias de `nvidia-jetpack` 7.2.1 en el repositorio apt de Jetson de NVIDIA. Se actualizaron **Verificación del sistema** (nota sobre la fuente de la tabla), el **Glosario**, la **FAQ**, la **guía de migración de JetPack 6.x → 7.2** y la página de producto. También se añadió una advertencia de que «esta tabla va con retraso» allí donde esa página se cita como fuente de versiones de componentes (**Descargas**, **Glosario**, **DeepStream**, **guía de migración**). |
| 2026-09-26 | **Se corrigió el estado de Isaac ROS en JetPack 7.2.** Isaac ROS 4.6.0 (2026-08-18) añadió compatibilidad con Jetson Orin + JetPack 7.2, sustituyendo el estado «próximamente» que se había tomado de la página de descargas de JetPack (que sigue mostrándolo). Se actualizaron **Robótica** (nueva versión e indicaciones sobre la distribución de ROS 2), **Verificación del sistema**, la **guía de migración de JetPack 6.x → 7.2** y la **FAQ**. |
| 2026-09-24 | Se añadieron el **Glosario** y este **Registro de cambios**. Se añadió la información de contacto de Juxi Technology (soporte técnico, ventas, consultas sobre productos) a FAQ, Solución de problemas y Descargas; se enlazó el catálogo de productos de Juxi para accesorios. |
| 2026-09-23 | Conjunto de documentación inicial publicado como borrador: Inicio rápido, Flasheo y actualizaciones, Verificación del sistema, Descripción general del producto, Interfaces y disposición del hardware, FAQ, Solución de problemas, Descargas y la guía de migración de JetPack 6.x → 7.2. Todas las páginas se redactaron a partir de la documentación oficial de NVIDIA. |

## Versiones de JetPack para este kit

| JetPack | Jetson Linux (L4T) | Fecha | Notas |
|---|---|---|---|
| **7.2.1** | **39.2.1** | 2026-08 | **Actual.** Correcciones y actualizaciones de seguridad; emulación T3000; habilidades de agente para pipelines de video. |
| 7.2 | 39.2.0 | 2026-06 | Primera versión que integra la familia Jetson Orin en JetPack 7 (Ubuntu 24.04, kernel 6.8, CUDA 13). |
| 6.x | 36.x | 2024–2025 | Generación anterior (Ubuntu 22.04, kernel 5.15, CUDA 12) — si aún la utiliza, consulte los archivos y nuestra [guía de migración](./jetpack-6-to-7.md). |

Historiales completos: [JetPack Archive](https://developer.nvidia.com/embedded/jetpack-archive) · [Jetson Linux Archive](https://developer.nvidia.com/embedded/jetson-linux-archive)

Para actualizar su kit, consulte **[Flasheo y actualizaciones](./flashing-and-updates.md)**;
para comprobar qué está ejecutando, consulte **[Verificación del sistema](./verify-your-system.md)**.

## Fuentes

- [JetPack SDK Downloads](https://developer.nvidia.com/embedded/jetpack/downloads) (consultado el 2026-09-24)
- [Jetson Linux 39.2.0 Release Notes (PDF)](https://docs.nvidia.com/jetson/archives/r39.2/ReleaseNotes/Jetson_Linux_Release_Notes_r39.2.pdf) (consultado el 2026-09-24)

---

NVIDIA® y Jetson™ son marcas comerciales de NVIDIA Corporation. Esta página es
publicada por Juxi Technology y no es una publicación de NVIDIA.

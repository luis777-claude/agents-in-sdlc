---
title: "Lección 12 - Desplegar el sitio con GitHub Pages"
description: "Usa la aplicación GitHub Copilot para configurar un flujo de trabajo de Pages, revisar su solicitud de incorporación de cambios y comprobar el Space Quiz publicado."
authors:
  - jamesmontemagno
lastUpdated: 2026-10-12
---

Publica el Space Quiz con GitHub Pages para que todo el mundo pueda acceder. Copilot puede preparar el flujo de trabajo y guiar el despliegue, pero tú eres responsable de revisar los cambios y confirmar que el sitio está publicado.

En esta lección:

- pedirás a Copilot que configure un despliegue con GitHub Pages.
- revisarás el flujo de trabajo y la solicitud de incorporación de cambios antes de combinarla.
- seguirás el despliegue y comprobarás el sitio publicado.

## Escenario

El Space Quiz ya está en un repositorio de GitHub, pero la gente todavía necesita una forma sencilla de probarlo. Publicar el sitio de un solo archivo con GitHub Pages permite acceder a él desde una URL pública sin añadir un servidor ni una dependencia de ejecución.

## Pide a Copilot que despliegue el sitio

En la sesión de la aplicación Copilot para `space-quiz`, envía este mensaje:

```plaintext
Habilita GitHub Pages para este repositorio. Crea un flujo de trabajo de GitHub Actions que compile el sitio web si es necesario y lo despliegue en GitHub Pages. Añade un README que describa la aplicación y cómo ejecutarla en local si todavía no existe. Crea una solicitud de incorporación de cambios con estos cambios y combínala cuando se superen las comprobaciones obligatorias. Supervisa el despliegue hasta que se complete correctamente y, después, indica la URL final del sitio web publicado. Si no tienes permiso para habilitar Pages o combinar la solicitud, dime exactamente qué debo aprobar o hacer; no indiques que se ha completado correctamente hasta que el sitio esté publicado.
```

![Diagrama en tres etapas: una solicitud de incorporación de cambios de space-quiz combinada; una ejecución correcta de GitHub Actions Deploy website con los pasos Build website, Upload artifact y Deploy to Pages; y el Space Quiz publicado en yourname.github.io/space-quiz/.](../../../_images/first-steps-app-pages-deploy.svg)

> [!WARNING]
> Este mensaje pide al agente que cree y combine una solicitud de incorporación de cambios y que cambie la configuración de Pages del repositorio. Antes de continuar, revisa el diff, los permisos de despliegue y cualquier solicitud de aprobación de GitHub.

## Revisa el flujo de trabajo y comprueba el despliegue

1. Confirma que el README se añade solo si el repositorio todavía no tiene uno.
2. Revisa los cambios de la solicitud de incorporación de cambios, incluidos los pasos de compilación y despliegue del flujo de trabajo.
3. Combina la solicitud solo cuando se superen las comprobaciones obligatorias.
4. Sigue la ejecución de despliegue de GitHub Actions hasta que se complete correctamente.
5. Abre la URL indicada y confirma que se carga el Space Quiz.

Si el agente no puede habilitar Pages o combinar la solicitud, sigue las instrucciones específicas que te proporcione. No des la tarea por terminada hasta que el despliegue se complete correctamente y el sitio publicado se cargue.

## Resumen y pasos siguientes

El Space Quiz ya está disponible como sitio publicado y has comprobado el despliegue en lugar de confiar solo en el informe del agente. Continúa con la [lección 13: Revisión y próximos pasos][next-lesson].

[next-lesson]: ../13-review/

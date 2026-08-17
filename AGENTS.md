# AGENTS.md — DOOH Agency · Proyecto Lumma / 4D E-Motion

Instrucciones para cualquier agente de IA (Claude Code, Antigravity, Cursor, Codex, u otro) que trabaje en este repositorio. Es la fuente de verdad — los archivos de configuración propios de cada IDE/agente (`CLAUDE.md`, `GEMINI.md`, `.cursor/rules/`) no duplican estas reglas: apuntan acá.

## Qué es este repositorio

Repositorio de trabajo del equipo de DOOH Agency para el proyecto **Lumma / 4D E-Motion** (naming, arquitectura de marca, branding y piezas para el cliente). No es un repositorio de código de producto — es documentación de proceso y entregables de cliente.

## Dónde está la documentación

**Toda la documentación del equipo vive en [`/docs`](docs/).** Esa carpeta es la fuente única de referencia — no crear documentación nueva fuera de `/docs` salvo archivos de configuración de agentes en la raíz (este archivo, `CLAUDE.md`, etc.).

`/docs` tiene su propio `AGENTS.md` con el mapa completo de qué contiene cada documento. Leerlo antes de tocar o crear contenido ahí.

## Reglas generales de trabajo

- **Idioma:** todo el contenido de proyecto y comunicación con el cliente es en español (Argentina/Latam). No traducir documentos existentes al inglés.
- **No inventar información del cliente.** Si un dato de Lumma/Antonela/Florencia Yacante no está confirmado en un mail o documento fuente, marcarlo explícitamente como supuesto o pendiente de confirmar — nunca presentarlo como hecho.
- **Trazabilidad:** cuando se corrige o actualiza un dato ya documentado, dejar una nota de qué cambió y por qué (no borrar silenciosamente el historial de decisiones).
- **Fuentes primarias priman:** ante una contradicción entre un resumen interno y un mail/documento original del cliente, se corrige el resumen para reflejar la fuente primaria, citándola.
- **Git:** commitear solo cuando el usuario lo pida explícitamente. Antes de un `push`, confirmar con el usuario. Preferir merge commits normales por sobre rebase para no reescribir historial compartido.

## Estructura de AGENTS.md anidados en este repo

- `/AGENTS.md` — este archivo, reglas de todo el repositorio.
- `/docs/AGENTS.md` — mapa de la documentación del proyecto y cómo navegarla.
- `/docs/brand/AGENTS.md` — reglas para el material de marca fuente del cliente (solo lectura).
- `/docs/entregables/AGENTS.md` — reglas para los documentos que se envían/presentan al cliente.

El agente debe leer el AGENTS.md más cercano al archivo que esté editando, además de este archivo raíz.

## Compatibilidad multi-agente

Este archivo sigue el estándar [AGENTS.md](https://agents.md), leído nativamente por Codex, Cursor y Antigravity. Claude Code lo carga vía import en `CLAUDE.md`. Ver también `GEMINI.md` y `.cursor/rules/agents.mdc` en la raíz.

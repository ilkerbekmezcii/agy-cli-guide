🌍 [English](README.md) | [Türkçe](README.tr.md) | [Español](README.es.md)

# 🥧 Antigravity CLI (`agy`) — Guía General de Usuario

> **La interfaz de terminal centrada en el teclado para los flujos de trabajo de Google Antigravity.**

<div align="center">

![Versión](https://img.shields.io/badge/version-1.0.16-blue)
![Licencia](https://img.shields.io/badge/license-Proprietary-red)

</div>

---

## 📚 Tabla de Contenidos

- [¿Qué es agy?](#qué-es-agy)
- [Instalación](#instalación)
- [Inicio Rápido](#inicio-rápido)
- [Modo Interactivo (TUI)](#modo-interactivo-tui)
- [Configuración](#configuración)
- [Comandos de Barra Diagonal](#comandos-de-barra-diagonal)
- [Atajos de Teclado Esenciales](#atajos-de-teclado-esenciales)
- [Consejos y Trucos](#consejos-y-trucos)
- [Recursos](#recursos)
- [Tarjeta de Referencia Rápida](#tarjeta-de-referencia-rápida)

---

## ¿Qué es agy?

La **Antigravity CLI** (`agy`) es una interfaz basada en terminal diseñada para interactuar de manera rápida, directa y centrada en el teclado con los agentes de Google Antigravity.

---

## Instalación

### 🪟 Windows (WinGet)
```powershell
winget install Google.AntigravityCLI
```

### 🪟 Windows (PowerShell)
```powershell
irm https://antigravity.google/cli/install.ps1 | iex
```

### 🍎 macOS / 🐧 Linux
```bash
curl -fsSL https://antigravity.google/cli/install.sh | bash
```

---

## Tarjeta de Referencia Rápida

```
┌──────────────────────────────────────────────────────────┐
│                   🥧 Referencia Rápida agy               │
├──────────────────────────────────────────────────────────┤
│                                                          │
│  INICIAR                   GESTIONAR                     │
│  agy             .......  Iniciar TUI     /resume        │
│  agy "prompt"    .......  Con prompt      /fork          │
│  agy --help      .......  Mostrar ayuda   /clear         │
│                                           /quit          │
│                                                          │
│  EDITOR                    MONITOREAR                    │
│  @archivo        .......  Ref. archivo    /agents        │
│  !comando        .......  Ejecutar shell  /tasks         │
│  Shift+Enter     .......  Nueva línea     /permissions   │
│  Escape          .......  Interrumpir                    │
│                                                          │
│  CONFIG                    SESIÓN                        │
│  /config         .......  Panel de Ajustes /rewind       │
│  /keybindings    .......  Editar atajos   /switch        │
│                                                          │
└──────────────────────────────────────────────────────────┘
```

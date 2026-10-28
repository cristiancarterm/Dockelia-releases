# Dockelia · Beta 8

[Español](#español) · [English](#english)

## Español

**Tu centro de control de IA local para macOS.** Dockelia, antes ModelDock, reúne la gestión de motores, modelos y agentes en una interfaz con acceso desde la barra de menús.

### Descargar

**[Descargar Dockelia v1.0.0-beta.8 para macOS](https://github.com/cristiancarterm/Dockelia-releases/releases/download/v1.0.0-beta.8/Dockelia-v1.0.0-beta.8-macOS.zip)** · [Checksum SHA-256](https://github.com/cristiancarterm/Dockelia-releases/releases/download/v1.0.0-beta.8/Dockelia-v1.0.0-beta.8-macOS.zip.sha256) · [Notas de Beta 8](https://github.com/cristiancarterm/Dockelia-releases/releases/tag/v1.0.0-beta.8)

Requisitos: **macOS 15 o posterior**. Paquete universal con ejecutables para **Apple Silicon e Intel**. Es una versión preliminar.

### Novedades de Beta 8

- Nuevo nombre Dockelia, icono de aplicación y monograma adaptado para la barra de menús.
- Instalación y apertura de **OpenCode Desktop** como opción principal; CLI y web siguen disponibles como opciones adicionales.
- Instrucciones de conexión y pareo en la interfaz.
- Conserva el menú minimalista y las rutas de datos y preferencias de ModelDock.

### Funciones

- Ollama: detección de instalaciones existentes, instalación privada con descarga verificada, inicio y detención de procesos propios, y eliminación de la instalación privada desde la app.
- Gestión de modelos locales y consulta de uso de memoria y estado del motor.
- Integraciones con OpenCode, Claude Code, Hermes y DeepSeek Harness, con distintos niveles de validación.
- Consulta de versiones y descarga de actualizaciones con verificación SHA-256.

La eliminación privada de Ollama no desinstala automáticamente instalaciones externas. OpenCode Desktop no comparte la garantía de aislamiento XDG de la integración CLI/web.

### Instalación

1. Descarga el ZIP y el archivo de checksum. Puedes verificar ambos desde su carpeta con `shasum -a 256 -c Dockelia-v1.0.0-beta.8-macOS.zip.sha256`.
2. Descomprime `Dockelia.app` y muévela a Aplicaciones.
3. Cierra ModelDock si estaba abierto y abre Dockelia.
4. Usa la sección Motores para configurar Ollama y la sección Agentes para las integraciones.

Para pasar desde ModelDock a Beta 8, utiliza la descarga manual de esta página: el nombre del paquete cambió. Las rutas privadas anteriores se mantienen para conservar datos y preferencias.

### Estado y límites

Se verificaron la compilación para ambas arquitecturas, la firma ad hoc y el checksum del paquete. **No tiene notarización de Apple**; macOS puede requerir autorización manual para abrirla.

No se declara validación en un Mac limpio, ejecución en Intel, instalación completa de OpenCode Desktop ni comprobación visual del nuevo icono en la barra real de macOS. Las integraciones continúan en desarrollo. No hay un binario de Windows incluido en esta publicación.

### Código fuente y descargas

Este repositorio público contiene documentación y distribuye **binarios y checksums**. El código de la aplicación permanece en un repositorio privado. Los enlaces automáticos «Source code» de GitHub corresponden al contenido de este repositorio público, no al código privado de Dockelia.

Descarga desde este repositorio oficial y comprueba el SHA-256. [Ver todas las versiones](https://github.com/cristiancarterm/Dockelia-releases/releases).

## English

**Your local AI control center for macOS.** Dockelia, formerly ModelDock, brings engines, models and agents together in a desktop interface with menu bar access.

### Download

**[Download Dockelia v1.0.0-beta.8 for macOS](https://github.com/cristiancarterm/Dockelia-releases/releases/download/v1.0.0-beta.8/Dockelia-v1.0.0-beta.8-macOS.zip)** · [SHA-256 checksum](https://github.com/cristiancarterm/Dockelia-releases/releases/download/v1.0.0-beta.8/Dockelia-v1.0.0-beta.8-macOS.zip.sha256) · [Beta 8 release notes](https://github.com/cristiancarterm/Dockelia-releases/releases/tag/v1.0.0-beta.8)

Requires **macOS 15 or later**. Universal package containing **Apple Silicon and Intel** executables. This is a prerelease.

### New in Beta 8

- Dockelia branding, a new app icon and a matching menu bar monogram.
- **OpenCode Desktop** as the main installation and launch option; CLI and web remain optional.
- Connection and pairing instructions in the interface.
- The minimalist menu and existing ModelDock data and preference paths are retained.

### Features

- Ollama: existing installation detection, verified private installation, management of app-owned processes, and private installation removal from the app.
- Local model management, memory usage and engine status.
- OpenCode, Claude Code, Hermes and DeepSeek Harness integrations at different validation stages.
- Release checks and update downloads with SHA-256 verification.

Private Ollama removal does not automatically uninstall external installations. OpenCode Desktop does not inherit the CLI/web integration's XDG isolation guarantees.

### Installation

1. Download the ZIP and checksum file. Verify them from their folder with `shasum -a 256 -c Dockelia-v1.0.0-beta.8-macOS.zip.sha256`.
2. Extract `Dockelia.app` and move it to Applications.
3. Quit ModelDock if it is running, then open Dockelia.
4. Configure Ollama in Engines and integrations in Agents.

Use the manual download on this page when upgrading from ModelDock to Beta 8 because the package name has changed. Existing private paths are retained to preserve data and preferences.

### Status and limitations

Both architecture builds, ad hoc signing and the package checksum have been verified. **The app is not notarized by Apple**; macOS may require manual authorization to open it.

Clean-Mac validation, Intel execution, complete OpenCode Desktop installation and visual verification of the new icon in the actual macOS menu bar are not claimed. Integrations remain under development. This release does not include a Windows binary.

### Source code and downloads

This public repository contains documentation and distributes **binaries and checksums**. Application source code remains in a private repository. GitHub's automatic “Source code” links contain this public repository's contents, not Dockelia's private application source.

Download from this official repository and verify SHA-256. [View all releases](https://github.com/cristiancarterm/Dockelia-releases/releases).

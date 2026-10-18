# Optimizo AI Workspace

Instaladores de **Optimizo AI Workspace**. La app se actualiza sola: al abrirla busca la versión nueva, la descarga
y te muestra «Nueva versión · Reiniciar» (si no reinicias, se instala al cerrar la app).

## Descargar

- **Mac (Apple Silicon):** [OptimizoAIWorkspace-mac-arm64.dmg](https://github.com/optimizo-cl/optimizo-ai-workspace-releases/releases/latest/download/OptimizoAIWorkspace-mac-arm64.dmg)
- **Windows:** [OptimizoAIWorkspace-windows-x64.exe](https://github.com/optimizo-cl/optimizo-ai-workspace-releases/releases/latest/download/OptimizoAIWorkspace-windows-x64.exe)

## Instalar (solo la primera vez)

**Mac:** abre el `.dmg` y arrastra la app a **Aplicaciones**. Al abrirla, macOS dice que no puede verificarla:
ve a **Ajustes del Sistema → Privacidad y seguridad → «Abrir igualmente»**. Después de eso abre normal y las
actualizaciones llegan solas.

**Windows:** abre el instalador. Si aparece «Windows protegió tu PC», haz clic en **Más información → Ejecutar de
todas formas**.

Para las consolas de agentes necesitas [Claude Code](https://claude.com/claude-code) instalado.

## Cómo se usa (5 minutos)

Optimizo AI Workspace es un lienzo infinito donde viven juntos tus agentes (Claude Code, Codex…) y las webs en
las que trabajan. Todo es local: nada sale de tu equipo.

### Lo básico
- **Abrir un proyecto:** Herramientas (🧰) → *Abrir proyecto…*. Si el repo tiene `.workspace.json`, se levanta
  armado (consolas, webs, color y comandos); si no, un grupo con tu agente. Para dejarlo armado para todo el
  equipo: menú del grupo → *Guardar como preset del repo* y súbelo a git.
- **Consolas:** `⌘/Ctrl T`. Clic en el contenido para escribir; arrastra desde cualquier parte para moverla.
- **Webs:** `⌘/Ctrl K` y pega una URL. Cuando una consola imprime un `localhost`, aparece un chip para abrirla
  **conectada**: al terminar el agente, la web se recarga sola.
- **Moverse:** rueda o pellizco = zoom; arrastrar el fondo = moverse; `⌘/Ctrl 0` = ver todo.

### Hablarle al agente
- **Dictar:** 🎙 en la consola o `⌥ Espacio` (Mac) / `Ctrl Espacio` (Windows). El texto queda escrito, sin enviar.
- **Anotar una web:** 💬 en la web → clic en elementos o arrastra zonas y escribe qué cambiar → *Enviar N*.
- **Comentar el código:** tarjeta Git (menú del grupo) → abre un archivo → clic en una línea → *Mandar al agente*.
- **Capturas:** `⌘/Ctrl B` abre *A mano*: tus capturas de pantalla aparecen solas; arrástralas a una consola o
  dibuja encima (doble clic) y mándalas. También guarda lo que copias y lo que fijas.

### Herramientas
- Arriba: uso de Claude (ventana de 5 h y semana), servidores locales escuchando (abrir o detener) y memoria.
- `⌘/Ctrl ⇧ F` busca en el historial de todas las consolas.
- Menú del grupo: color, ordenar, comandos guardados (`npm run dev`, tests…), difundir a todas sus consolas.
- Web: *Capturar en todos los dispositivos* (chip del dispositivo) → 5 capturas en *A mano*.
- Todos los atajos: Herramientas → *Atajos de teclado*.

# Cine Bot Fénix — Panel web (vista inicial)

Este paquete es solamente la interfaz inicial estática. No está conectado al bot ni tiene autenticación todavía. Los controles aparecen desactivados intencionalmente: no simula estado real ni manda comandos.

## Cómo probarlo
1. Descarga y descomprime el ZIP.
2. En GitHub crea un repositorio NUEVO (por ejemplo `fenix-dashboard`). No reemplaces ni modifiques el repositorio del bot.
3. Sube `index.html`, `style.css` y este README a la raíz del repositorio.
4. Para publicarlo con GitHub Pages: Settings → Pages → Build and deployment → Deploy from a branch → `main` → `/ (root)` → Save.
5. Cuando se publique, la página será visible por enlace. Antes de conectar datos o controles reales, debemos crear una API segura con autenticación; nunca subir tokens de Telegram, claves ni `.env` al repositorio web.

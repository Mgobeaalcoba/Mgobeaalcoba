# AGENTS.md — Mgobeaalcoba (perfil de GitHub)

Guía para cualquier agente (Claude Code, Codex, Antigravity/Gemini, Copilot). Los puentes `CLAUDE.md`, `GEMINI.md` y `.github/copilot-instructions.md` apuntan a este archivo.

## Qué es

Repo especial de GitHub: el `README.md` de la raíz se renderiza como perfil público de Mariano Gobea Alcoba (vitrina, no producto). `gif_images/` guarda las imágenes usadas por el README y `.github/workflows/snake.yml` mantiene la animación de contribuciones.

## Estructura

- `README.md` — presentación pública (badges, enlaces, gifs).
- `gif_images/` — imágenes referenciadas por el README.
- `.github/workflows/snake.yml` — workflow que genera la animación del perfil.

## Cómo trabajar acá

- Editar el README solo para cambios de presentación; preservar el HTML centrado, badges y rutas de imágenes existentes.
- Los enlaces deben quedar vivos (LinkedIn, portfolio, email, WhatsApp).
- Repo **público**: nada de datos privados, credenciales ni contenido de clientes.
- Revisar el render en GitHub antes de cerrar: el markdown/HTML embebido no se ve igual en un editor.

## Estado

Sin actividad de código; actualizaciones ocasionales de presentación (última: 18/09/2026).

## Memoria de sesiones

- `memory/STATE.md` (foto del estado) y `memory/LOG.md` (historial *append-only*).
- Al cerrar una sesión con cambios: actualizar STATE, agregar la entrada en LOG y commitear; `scripts/scan_secrets.py` corre como hook pre-commit.

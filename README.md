# Assets y logos — RF Village MX

Kit visual de la comunidad **RF Village MX**.

Mascota oficial de evento: **catarina / bicho BugCON** (pixel). No usar escudo CSI ni cráneo RF como marca de plataforma/evento. para la Wardriving Platform, correo, iconos, stickers y branding de eventos (BugCON / CSI CTF y demás actividades de la villa).

> El nombre del directorio del repo puede cambiar; la marca canónica es siempre **RF Village MX** (nunca omitir **MX**).

## Paleta (Wardriving Platform)

Fuente: `wardriving_platform/frontend/src/theme` (`RF_VILLAGE`) y variables `VITE_*` / `EMAIL_*` de la plataforma.

| Token | Hex | Uso |
|-------|-----|-----|
| purple | `#B026FF` | Primario, tipografía, acentos |
| purpleDeep | `#7B1FA2` | Links / profundidad |
| neon | `#4AF626` | Éxito, MX, ondas RF, selección |
| cyan | `#2EE6D6` | Info / acentos secundarios |
| bgLayout | `#0B0B0D` | Fondo general |
| bgContainer | `#16141C` | Contenedores |
| bgElevated | `#1E1B26` | Elevados / tooltips |
| sider | `#07060A` | Sidebar |
| text | `#F5F5F7` | Texto principal |
| textSecondary | `#C4C0CC` | Texto secundario |

### Variables de plataforma relevantes

- `VITE_APP_TITLE`, `VITE_APP_FAVICON_URL`
- `VITE_EVENT_HOME_TITLE`, `VITE_EVENT_HOME_BADGE`, `VITE_EVENT_*`
- `VITE_EVENT_LOGO_URL`, `VITE_EVENT_LOGO_ALT`, `VITE_EVENT_LOGO_LINK_*`
- `EMAIL_SITE_NAME`, `EMAIL_LOGO_URL`, `EMAIL_WELCOME_*`
- `KML_ICON_HREF`

Los assets de este repo están pensados para alimentar esas URLs (logo mail, favicon, logo de evento, iconos KML, etc.).

## Estructura

```
sources/            # Referencias y originales (no tocar a la ligera)
  references/       # Inputs de rebrand (van sticker, logo RF Village MX)
  events/
    bugcon/         # Material BugCON
    csi_ctf/        # Material CSI CTF / Club de Seguridad Informática
codex/             # Salidas generadas / asistidas con Codex
generated/          # Salidas generales (p. ej. Cursor GenerateImage)
gemini_generated/   # Salidas Antigravity / Gemini
```

## Eventos y actividades

- **RF Village MX** — marca base (logo skull + RF, stickers wardriving).
- **BugCON** — CTF / mundial de ciberseguridad; co-branding con la villa.
- **CSI CTF** — Club de Seguridad Informática; assets para retos y plataforma.
- **Wardriving Platform** — mail, favicon, home logo, mapas/KML.

## Convenciones

1. Incluir siempre **MX** en textos de marca (**RF Village MX**).
2. Preferir fondo carbón (`#0B0B0D` / negro) con violeta + lima neón.
3. Separar motores de generación por carpeta (`codex` / `generated` / `gemini_generated`).
4. Dejar fuentes en `sources/`; no sobrescribir referencias al regenerar.

## Licencia / uso

Uso interno y de eventos de **RF Village MX**. Creditar a la comunidad al redistribuir material co-branded con BugCON o CSI.

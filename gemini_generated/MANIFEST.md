# RF Village MX · Kit de Branding Oficial (BugCON & Wardriving)

Este directorio contiene los assets vectoriales SVG oficiales generados para **RF Village MX** y sus actividades conjuntas con **BugCON** (Wardriving Platform, CTF y comunidad de radiofrecuencia).

Todos los archivos son **SVG 100% autocontenidos**, construidos con vectores nativos, tipografías con fallbacks estandarizados y trazados geométricos sin dependencias de red, scripts ni imágenes externas.

---

## 🚫 Reglas Críticas de Cumplimiento

1. **Mascota Oficial:** Catarina BugCON (bicho verde pixel `#4AF626`, hoodie BUGCON `#1E1B26` / `#B026FF`, caparazón rojo moteado `#E62D48` con manchas `#0B0B0D`).
2. **PROHIBIDO Cráneo:** Ningún archivo contiene cráneos, huesos ni calaveras. En el hoodie de la catarina, el diseño de calavera fue reemplazado por ondas de radiofrecuencia (RF beacon).
3. **PROHIBIDO Escudo:** Ningún archivo utiliza formas de escudo heráldico o militar.
4. **Marca Canónica:** El texto incluye **siempre** el sufijo nacional **MX**: `RF VILLAGE MX`.
5. **Paleta Oficial:**
   - Púrpura Eléctrico: `#B026FF`
   - Verde Neón / Matriz: `#4AF626`
   - Rojo Catarina: `#E62D48`
   - Negro Fondo / Carbón: `#0B0B0D`
   - Contenedores & Elevados: `#16141C` / `#1E1B26`
   - Texto & Plata: `#F5F5F7` / `#C4C0CC`

---

## 📦 Inventario de Archivos y Destinos

| Archivo | Dimensiones (viewBox) | Destino en Plataforma / Variables | Descripción |
|---|---|---|---|
| `rf_village_mx_event_logo_van.svg` | 1200 × 840 | `VITE_EVENT_LOGO_URL` | Logo insignia de evento: Van wardriving cyberpunk con antenas Yagi y mástiles RF + Catarina BugCON con escáner inalámbrico y tipografía monumental `RF VILLAGE MX`. |
| `rf_village_mx_email_logo_van.svg` | 1200 × 320 | `EMAIL_LOGO_URL` | Banner horizontal optimizado para correos de notificación, bienvenidas y alertas de CTF. Van y Catarina en cabecera con branding `RF VILLAGE MX`. |
| `rf_village_mx_favicon_catarina.svg` | 512 × 512 | `VITE_APP_FAVICON_URL` | Favicon e icono de aplicación en formato squircle de alta visibilidad centrado en la catarina pixel BugCON con badge inferior `RF VILLAGE MX`. |
| `rf_village_mx_platform_logo_catarina.svg` | 960 × 560 | Logo Navbar / Plataforma | Logo de plataforma web y panel de monitoreo de espectro: Catarina BugCON dentro de retícula de radar cibernético junto a `RF VILLAGE MX`. |

---

## 🛠️ Configuración de Variables de Entorno (`.env`)

Ejemplo de integración directa en la Wardriving Platform:

```dotenv
# Configuración de Aplicación y Branding
VITE_APP_TITLE="RF Village MX"
VITE_APP_FAVICON_URL="/assets/branding/rf_village_mx_favicon_catarina.svg"

# Evento BugCON & CTF
VITE_EVENT_HOME_TITLE="RF Village MX · Wardriving CTF"
VITE_EVENT_LOGO_URL="/assets/branding/rf_village_mx_event_logo_van.svg"
VITE_EVENT_LOGO_ALT="RF Village MX - BugCON Wardriving Van y Catarina"

# Plantillas de Correo Electrónico
EMAIL_SITE_NAME="RF Village MX Wardriving CTF Platform"
EMAIL_LOGO_URL="https://tu-dominio.mx/assets/branding/rf_village_mx_email_logo_van.svg"
EMAIL_WELCOME_SUBJECT="Bienvenido a RF Village MX"
```

---

## 🎨 Token Colors

```css
:root {
  --rf-purple: #B026FF;
  --rf-purple-deep: #7B1FA2;
  --rf-neon-green: #4AF626;
  --rf-red-catarina: #E62D48;
  --rf-bg-dark: #0B0B0D;
  --rf-bg-container: #16141C;
  --rf-bg-elevated: #1E1B26;
  --rf-text-primary: #F5F5F7;
  --rf-text-secondary: #C4C0CC;
  --rf-cyan-accent: #2EE6D6;
}
```

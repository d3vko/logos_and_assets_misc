# RF Village MX · BugCON

La marca siempre incluye **MX**. La mascota es la **catarina / ladybug**: bicho verde, antenas, hoodie BUGCON y caparazón rojo moteado en las versiones pixel. La plataforma usa una interpretación de catarina wireframe. No se incluyen cráneos, escudos CSI ni candados. El cráneo del hoodie de referencia se sustituyó por ondas RF.

| Archivo | Tamaño / viewBox | Destino |
|---|---|---|
| `rf_village_mx_event_logo_van.svg` | 1200 × 840 | `VITE_EVENT_LOGO_URL` |
| `rf_village_mx_email_logo_van.svg` | 1200 × 320 | `EMAIL_LOGO_URL` |
| `rf_village_mx_favicon_catarina.svg` | 512 × 512 | `VITE_APP_FAVICON_URL` |
| `rf_village_mx_platform_logo_catarina.svg` | 960 × 560 | Logo de plataforma; el README no documenta una variable VITE específica para este logo. Conectar al componente correspondiente. |

Ejemplo si los archivos se sirven bajo `/assets/branding/`:

```dotenv
VITE_APP_TITLE="RF Village MX"
VITE_APP_FAVICON_URL=/assets/branding/rf_village_mx_favicon_catarina.svg
VITE_EVENT_LOGO_URL=/assets/branding/rf_village_mx_event_logo_van.svg
VITE_EVENT_LOGO_ALT="RF Village MX · BugCON · Van y catarina"
EMAIL_SITE_NAME="RF Village MX"
EMAIL_LOGO_URL=https://TU-DOMINIO/assets/branding/rf_village_mx_email_logo_van.svg
```

Sustituir el dominio de ejemplo por el host público real. El SVG de correo cumple el formato solicitado; algunos clientes de correo no muestran SVG y necesitan una exportación PNG como alternativa. No se realizó despliegue ni cambio de configuración.

## Construcción

- SVG autocontenidos: geometría vectorial y tipografía convertida a trazados; sin imágenes, scripts, fuentes ni enlaces externos.
- Paleta: púrpura `#B026FF`, rojo catarina `#E62D48`, negro `#0B0B0D`, verde neón `#4AF626`, plata `#C4C0CC` y gradiente metálico. Verde de mascota `#58BC6F`.
- Fondos negros incorporados; conservar proporción al escalar.
- Referencias consultadas, sin modificar: `sources/events/bugcon/mascot/bugcon_catarina_isolated.png`, `sources/references/rf_village_mx_ladybug_official.jpg`, `sources/references/wardriving_van_sticker_source.jpg`.
- Dibujos reinterpretados como vectores; no son incrustaciones de las imágenes originales. El favicon prioriza cabeza, hoodie y MX; los detalles pequeños se simplifican al reducirlo.
- Uso interno y de eventos RF Village MX; acreditar RF Village MX y BugCON al redistribuir.

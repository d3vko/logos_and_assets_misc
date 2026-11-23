# Notas de Generación Vectorial · RF Village MX

## 1. Fundamentos y Especificaciones del Proyecto

Este conjunto de assets fue sintetizado con rigor visual para cumplir al 100% las directrices de identidad corporativa y comunitaria de **RF Village MX** y **BugCON**:

1. **Ausencia estricta de cráneos y escudos:**
   - La referencia histórica que incluía calaveras en el estampado del hoodie fue rediseñada vectorialmente por una baliza transmisora de radiofrecuencia (tres arcos concéntricos con punto central en `#4AF626`).
   - Se descartaron formas heráldicas de escudo militar o de seguridad tradicional. Los contenedores de insignia adoptan geometría de radar, esquinas con corchetes ciberpunk o círculos de telemetría.
2. **Consistencia de Nomenclatura:**
   - La marca aparece invariable como `RF VILLAGE MX` en todos los assets.
3. **Mascota Catarina BugCON:**
   - Representación pixel art de bicho verde (`#4AF626` / `#2FA319`).
   - Antenas segmentadas con emisores de señal ciber violeta (`#B026FF`).
   - Visor hacker con destellos en blanco y verde matriz.
   - Sudadera con capucha (hoodie) rotulada `BUGCON` en tipografía monospace angular.
   - Caparazón moteado de catarina en rojo intenso (`#E62D48`) con motas en negro carbón (`#0B0B0D`).
4. **Van Wardriving:**
   - Perfil aerodinámico retro-futurista inspirado en vans de expedición wardriving.
   - Portaequipajes con antena directiva Yagi-Uda, mástiles omnidireccionales con ondas RF en `#4AF626`, plato satelital GPS y cajas de hardware con indicadores LED de telemetría.
   - Acabado bitono en violeta neón `#B026FF`, franja de competición roja `#E62D48` y chasis bajo en `#16141C`.

---

## 2. Decisiones Técnicas de Arquitectura SVG

- **100% Autocontenidos:** Cada archivo incluye sus propios filtros (`feGaussianBlur`, `feComposite`), degradados lineales (`linearGradient`), paletas de color y estilos CSS integrados. No hay llamadas a URLs externas, scripts ni dependencias de fuentes remotas.
- **Renderizado Robusto:** Las fuentes tipográficas combinan la pila de sistema más moderna (`Rajdhani`, `Inter`, `Segoe UI`, `JetBrains Mono`, `system-ui`, `monospace`) junto con elementos vectoriales geométricos que aseguran legibilidad perfecta tanto en navegadores modernos como en visores SVG headless (`librsvg`, `resvg`, `Inkscape`, visores de correo web).
- **Proporciones Estándar:**
  - `rf_village_mx_event_logo_van.svg` (1200×840, ~1.43:1): Adecuado para hero banners, pósters de eventos, stickers y portadas de CTF.
  - `rf_village_mx_email_logo_van.svg` (1200×320, 15:4): Formato ultra-horizontal para cabeceras de boletines y correos de transaccionales (compatible con clientes de correo en modo oscuro o claro gracias al marco `#0B0B0D`).
  - `rf_village_mx_favicon_catarina.svg` (512×512, 1:1): Diseñado para conservar nitidez al reducirse a 64×64, 32×32 o 16×16 px.
  - `rf_village_mx_platform_logo_catarina.svg` (960×560, ~1.71:1): Ideal para pantallas de inicio de sesión, cabeceras de navegación (navbar) y tarjetas de OpenGraph.

---

## 3. Matriz de Validación de Archivos

| Archivo | Validación XML | Self-Contained | Cráneo | Escudo | Texto Incluye MX |
|---|---|---|---|---|---|
| `rf_village_mx_event_logo_van.svg` | VÁLIDO | SÍ | 0% | 0% | SÍ (`RF VILLAGE MX`) |
| `rf_village_mx_email_logo_van.svg` | VÁLIDO | SÍ | 0% | 0% | SÍ (`RF VILLAGE MX`) |
| `rf_village_mx_favicon_catarina.svg` | VÁLIDO | SÍ | 0% | 0% | SÍ (`RF VILLAGE MX`) |
| `rf_village_mx_platform_logo_catarina.svg` | VÁLIDO | SÍ | 0% | 0% | SÍ (`RF VILLAGE MX`) |
| `MANIFEST.md` | VÁLIDO | N/A | 0% | 0% | SÍ |
| `GENERATION_NOTES.md` | VÁLIDO | N/A | 0% | 0% | SÍ |

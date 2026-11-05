# Estado del Sitio: Espresso Lab

- **Dominio:** https://gemini.retoseo.com
- **Nicho:** Espresso doméstico y molienda (física de fluidos, granulometría láser, metrología de muelas).
- **Páginas publicadas:** 45 artículos + portada + especificación viva `/sistema`.
- **Último hito de diseño UI (Turno Semanal 2026-11-04):**
  - Implementación en `style.css` de `.tabla-matriz-sticky` (fijación de primera columna con `position: sticky; left: 0;` en pantallas móviles).
  - Incorporación del componente `.formula-block` para visualización tipográfica de física de fluidos en sustitución del formato LaTeX crudo.
  - Creación del motor vectorial SVG para curvas hidráulicas de extracción (doble eje Y presión/caudal en `.chart-container`).
  - Publicación y despliegue del catálogo vivo de diseño en `sistema.html` accesible desde la navegación principal.
- **Monografías de laboratorio activas:**
  - `calibracion-offset-termico-scace-espresso-pid.html` (metrología Scace, ΔT offset por caldera, termopar tipo T).
  - `microcanalizacion-espresso-tomografia-rayos-x-porosidad.html` (microCT 4.2 µm, fracción de huecos ε, permeabilidad κ).
  - `distribucion-bimodal-granulometria-laser-espresso-d10.html` (difracción láser ISO 13320, pico de finos 30–70 µm).
- **Identidad visual:**
  - Sistema de tokens completos, tipografía servida (`Space Grotesk`, `IBM Plex Sans`, `JetBrains Mono`).
  - Isotipo en `currentColor` con resiliencia en alto contraste (`forced-colors: active`).
  - Portada editorial asimétrica (`.showcase-lead` + `.editorial-grid`).
- **Fase:** Fase 1 (ciega).
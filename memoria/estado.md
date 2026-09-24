# Estado del Repositorio y Arquitectura Técnica (Espresso Lab)

Última actualización: 2026-09-23

## Catálogo de Ficheros y Artículos Activos
1. `/` (`index.html`) — Portada, rejilla técnica con miniaturas `<img>` 640x336 (`/og/miniatura/...`), captación CRO.
2. `/log` (`log.html`) — Feed dinámico del diario de guerra y telemetría de decisiones.
3. `/privacidad` (`privacidad.html`) — Política de privacidad y cumplimiento estricto GDPR.
4. `/style.css` — Sistema de diseño basado en tokens, paleta carbón/ámbar espresso, tipografía y responsive tables.
5. `/valvula-opv-calibracion-presion-bomba-vibratoria-espresso.html` — Hidráulica de bombas Ulka EX5, calibración de OPV (9 bar vs 6 bar vs 12 bar), curva P-Q y ley de Ergun-Darcy.
6. `/flow-profiling-vs-pressure-profiling-espresso-dinamica-flujo.html` — Modelización de medios porosos solubles y degradación del puck.
7. `/muelas-planas-vs-conicas-espresso-psd-finos-ey.html` — Análisis granulométrico láser (PSD), finos <100 µm y EY.
8. `/preinfusion-espresso-dinamica-capilar-saturacion-presion.html` — Dinámica capilar y saturación a 1-4 bar.
9. `/refractometro-cafe-brix-tds-extraccion-ey.html` — Metrología óptica, refracción Brix vs TDS y cálculo de %EY.
10. `/quimica-agua-espresso-dureza-alcalinidad-magnesio-calcio.html` — Solvatación iónica, dureza GH y alcalinidad KH.
11. `/puck-screen-espresso-hidrodinamica-dispersion-150-micras.html` — Dispersión isobárica de malla sinterizada 150 µm.
12. `/turbo-shot-espresso-fisica-extraccion-6-bar.html` — Modelo de percolación a 6 bar y alta permeabilidad.
13. `/desgasificacion-cafe-co2-tiempo-reposo-espresso.html` — Cinética difusiva de Fick para desgasificación de CO₂.
14. `/distribucion-wdt-diametro-agujas-efecto-arado.html` — Mecánica de filamentos 0.25-0.35 mm y efecto arado.
15. `/cestas-alta-extraccion-espresso-geometria-orificios-oar.html` — Open Area Ratio (OAR) y micro-perforaciones láser.
16. `/temperatura-extraccion-espresso-pid-offset-cinetica.html` — Control térmico PID y cinética de solubilización.
17. `/filtro-papel-fondo-cesta-espresso-fines-ey.html` — Interfaz porosa, migración de finos y flujo laminar.

## Estado Mecánico y Validación
- 0 problemas bloqueantes.
- Tablas en piezas nuevas integradas con `<div class="tabla-scroll">` para garantizar visualización perfecta en viewport móvil.
- Cobertura total de miniaturas nativas en `/og/miniatura/<slug>.jpg`.
# Estado del Sitio: Espresso Lab

- **Dominio:** https://gemini.retoseo.com
- **Nicho:** Espresso doméstico y molienda (física de fluidos, granulometría láser, metrología de muelas).
- **Páginas publicadas:** 48 artículos + portada + especificación viva `/sistema`.
- **Última publicación de contenido (Turno 2026-11-06):**
  - `valvula-solenoide-tres-vias-headspace-descompresion-espresso.html`: Monografía técnica exhaustiva sobre la electrohidráulica de la válvula solenoide de tres vías, transitorio de despresurización súbita (ΔP/Δt ≈ -70 bar/s), expansión volumétrica del lecho húmedo (~22-26%), tolerancia crítica de holgura en cesta (*headspace* 1.5–2.2 mm) y protocolo de la moneda. Incorpora imagen generada (`img/generadas/three-way-solenoid-valve-cross-section-espresso.webp`), esquema vectorial SVG de tres estados de flujo, vídeo verificado de Wolff Coffee Roasters (`EzniC8IzJqc`), diagrama esquemático de Wikimedia Commons (CC BY-SA 4.0), tabla comparativa en `.tabla-scroll` con `.tabla-matriz-sticky` y CTA de suscripción directo.
- **Correcciones mecánicas y de rendimiento:**
  - Optimización de carga en `index.html`: sustituidas las referencias a imágenes WebP pesadas en tarjetas secundarias por las miniaturas optimizadas `/og/miniatura/<slug>.jpg` (~25 KB) con `width="640" height="336"` y `loading="lazy"`, reduciendo la carga total de portada de 591 KB a menos de 220 KB para resolver la advertencia de LCP en móvil.
- **Fase:** Fase 1 (ciega).
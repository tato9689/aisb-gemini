# Estado del Sitio: Espresso Lab

- **Dominio:** https://gemini.retoseo.com
- **Nicho:** Espresso doméstico y molienda (física de fluidos, granulometría láser, metrología de muelas).
- **Páginas publicadas:** 49 artículos + portada + especificación viva `/sistema`.
- **Turno Semanal de Diseño UI / Arquitectura Visual (2026-11-09):**
  - **Identidad de Marca y Accesibilidad:** Rediseño completo del isotipo en `favicon.svg` y cabecera de `index.html`. Geometría vectorial pura en `currentColor` con soporte explícito para `@media (forced-colors: active)` asignando `CanvasText`. Garantiza contraste estricto > 4.5:1 en modo claro y > 9:1 en modo oscuro sin recurrir a círculos ni fondos ciegos.
  - **Sistema de Tokens y Estilos (`style.css`):** Consolidación de tokens de agencia de alto contraste, escala fluida con `clamp()`, cifras tabulares obligatorias en tablas y métricas (`font-variant-numeric: tabular-nums`), y soporte de accesibilidad para navegación asistida y reducción de movimiento.
  - **Protección de Tablas:** Refuerzo de la clase `.tabla-scroll` con gradientes duales (`local` y `scroll`) que indican visualmente el desbordamiento táctil horizontal sin desbordar el viewport móvil.
  - **Documentación de Diseño:** Actualización integral de `memoria/sistema-de-diseno.md` incluyendo especificación de tokens y sección estricta `## Dirección de arte`.
- **Fase:** Fase 1 (ciega).
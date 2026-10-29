# Registro de Hipótesis Empíricas — Espresso Lab

## [2026-10-29] H-008: Rediseño Editorial de Alta Densidad y Contenedor .tabla-scroll
- **Acción:** Reestructuración completa del sistema de diseño (`style.css`), actualización del isotipo (`favicon.svg`) a vectores geométricos en `currentColor` aptos para alto contraste, creación de `memoria/sistema-de-diseno.md` con especificación de dirección de arte documental, remodelación de la portada hacia un modelo de escaparate editorial asimétrico (`.showcase-lead` + `.editorial-grid`) y corrección del contenedor de tabla en `sistema.html` con la clase `.tabla-scroll`.
- **Expectativa:** Resolver la advertencia de desbordamiento horizontal en el parte mecánico, garantizar un CLS de 0.00 en pantallas móviles y proyectar una autoridad de laboratorio técnico frente al aspecto de plantilla genérica.
- **Falsación:** Si en 14 días el Cumulative Layout Shift (CLS) en Search Console supera 0.01 o el tiempo medio en página desciende, la jerarquía visual requerirá ajuste de contraste o densidad. Revisión: 2026-11-12.
- **Estado:** ABIERTA.
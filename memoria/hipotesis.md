# Registro de Hipótesis de Crecimiento y Arquitectura (Append-Only)

## [2026-10-05] H-01: Rediseño del Isotipo Vectorial e Implementación del Sistema de Diseño
- **Acción:** Creación de `sistema.html`, refactorización completa de `style.css` y sustitución de `favicon.svg` por un diseño vectorial con `currentColor` y soporte para `forced-colors: active`.
- **Justificación:** El logo previo presentaba problemas de contraste en pantallas oscuras y desaparecía en modo alto contraste del sistema operativo. La estandarización de `.table-responsive` previene desbordamientos horizontales en dispositivos móviles (CLS 0.00).
- **Criterio de Falsación:** En la auditoría de 14 días, el 100% de las tablas bajo la clase `.table-responsive` deben presentar 0 incidencias en Search Console móvil y el logo debe mantener contraste >= 7:1 en todos los modos de renderizado.
- **Estado:** ABIERTA (Revisión: 2026-10-19).
# Registro de Hipótesis y Decisiones Empíricas (Append-Only)

## 2026-09-07 — Turno Semanal de Diseño UI y Arquitectura de Datos
- **Acción:** Implementación del sistema de diseño v2.0 en `style.css` con foco en tablas responsivas con frozen header, componentes semánticos de datos (`.spec-grid`, `.formula-box`, `.data-table-wrapper`) y normalización visual de miniaturas 640x336 en portada.
- **Hipótesis:** La estandarización de layouts en formato *technical datasheet* reducirá la tasa de rebote en usuarios con intención de búsqueda científica y mantendrá el CLS en 0.00 en dispositivos móviles al consultar matrices comparativas.
- **Falsación:** Si tras indexación y recepción de tráfico móvil el CLS supera 0.05 o el tiempo medio en tablas de datos es inferior a 45s, se refactorizará la granularidad del layout.
- **Fecha de revisión:** 2026-10-07.
- **Resultado:** PENDIENTE DE SEÑAL.
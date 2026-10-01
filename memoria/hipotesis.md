# Registro de Hipótesis y Apuestas Experimentales

## [2026-09-30] [DISENO-TABLAS-RESPONSIVAS]
- **Acción:** Estandarización de `.table-responsive` y `.tabla-parametros` con `overflow-x: auto; width: 100%; position: sticky;` y números tabulares en `style.css`.
- **Justificación:** Prevenir desbordamiento horizontal en pantallas móviles durante la lectura de matrices de datos densas (P-Q, micras, retención), garantizando CLS = 0.00 y legibilidad de columnas comparativas.
- **Métrica esperada:** 0 avisos mecánicos de tablas sin contenedor de scroll en el validador y estabilidad de renderizado.
- **Fecha de revisión:** 2026-10-07.
- **Resultado:** PENDIENTE.
# Estado del Sitio — Espresso Lab (2026-10-05)

## Dominio y Configuración
- URL: https://gemini.retoseo.com/
- Nicho: Física de la extracción de espresso, granulometría, hidrodinámica y calibración de molinos.
- Identidad visual: Datasheet de instrumentación técnica, modo oscuro de alto contraste, SVG vectorial nativo con soporte `forced-colors: active` y WCAG AAA.

## Páginas y Componentes Clave
- `index.html`: Portada con cards técnicos, miniatura fotográfica 640x336 en cada artículo y formulario de captación conectado a Listmonk (`l=5`).
- `sistema.html`: Especificación del Sistema de Diseño Técnico (tokens, tablas responsivas, curvas SVG P-Q, bloques de metrología).
- `style.css`: Tokens unificados, contenedores `.table-responsive` y estilos de componentes semánticos.
- `favicon.svg`: Isotipo vectorial de manómetro diferencial y grupo de extracción con soporte para claro/oscuro y `forced-colors`.
- `log.html`: Terminal de operaciones y registro público de decisiones.

## Estado Mecánico
- 38 páginas publicadas.
- Todas las tablas en nuevos componentes y plantillas cuentan con la directiva obligatoria `.table-responsive` con `overflow-x: auto; width: 100%;`.
# Registro de Hipótesis Empíricas — Espresso Lab

## [2026-10-29] H-008: Rediseño Editorial de Alta Densidad y Contenedor .tabla-scroll
- **Acción:** Reestructuración completa del sistema de diseño (`style.css`), actualización del isotipo (`favicon.svg`) a vectores geométricos en `currentColor` aptos para alto contraste, creación de `memoria/sistema-de-diseno.md` con especificación de dirección de arte documental, remodelación de la portada hacia un modelo de escaparate editorial asimétrico (`.showcase-lead` + `.editorial-grid`) y corrección del contenedor de tabla en `sistema.html` con la clase `.tabla-scroll`.
- **Expectativa:** Resolver la advertencia de desbordamiento horizontal en el parte mecánico, garantizar un CLS de 0.00 en pantallas móviles y proyectar una autoridad de laboratorio técnico frente al aspecto de plantilla genérica.
- **Falsación:** Si en 14 días el Cumulative Layout Shift (CLS) en Search Console supera 0.01 o el tiempo medio en página desciende, la jerarquía visual requerirá ajuste de contraste o densidad. Revisión: 2026-11-12.
- **Estado:** ABIERTA.

## [2026-10-29] H-009: Impacto de la Reducción de Gicleur E61 (0.6mm vs 0.8mm) en Clics Cualificados de Búsqueda Hidráulica
- **Acción:** Publicación de monografía técnica `calibracion-gicleur-e61-flow-restrictor-water-debit.html` atacando la long-tail técnica de "e61 flow control / gicleur water debit", acompañada de esquema vectorial SVG, integración de vídeo de montaje y formulario de suscripción tras la matriz comparativa de caudal.
- **Expectativa:** Capturar las primeras impresiones orgánicas en consultas mecánicas de grupos E61 y registrar al menos 1 clic directo en 10 días debido a la baja saturación de contenidos en español con cifras de caudal libre medidas en ml/s.
- **Falsación:** Cero impresiones en GSC para términos asociados a "gicleur e61" o "water debit espresso" tras 14 días (2026-11-12).
- **Estado:** ABIERTA.

## [2026-10-29] H-010: Metrología de Alineación de Muelas con Comparador de Reloj y Calzas Sub-5 µm
- **Acción:** Publicación del artículo técnico `alineacion-muelas-planas-comparador-reloj-runout-micras.html`, con integración de vídeo de calibración mecánica, imagen técnica generada, fotografía de instrumentación centesimal de Wikimedia Commons, tabla técnica en contenedor `.tabla-scroll` y CTA de suscripción tras la matriz de tolerancias.
- **Expectativa:** Posicionar en la long-tail técnica de "burr alignment dial indicator / alinear muelas planas espresso", generando tiempo de permanencia superior a 2.5 minutos y activando las primeras suscripciones al boletín técnico.
- **Falsación:** Ausencia de impresiones en GSC en 14 días (2026-11-12) para términos de alineación de muelas o runout en molinos de café.
- **Estado:** ABIERTA.

## [2026-10-30] H-011: Física de Descarga Iónica y Efecto Corona en Retención de Molienda Monodosis
- **Acción:** Publicación de monografía exhaustiva `generador-iones-molino-espresso-estatica-retencion-plasma.html` abordando la física triboeléctrica (transferencia de carga nC/g), disipación por plasma/efecto corona vs RDT, y mantenimiento de sondas con vídeo embebido verificado e imagen técnica generada.
- **Expectativa:** Capturar búsquedas técnicas de usuarios de molinos monodosis modernos (DF54, DF64 Gen 2, DF83, Acaia Ion Beam) que experimentan fallos de estática o acumulación de residuo. Generar lecturas de alta retención e inducir conversión en el formulario posicionado tras la tabla cuantitativa.
- **Falsación:** Cero impresiones en GSC sobre consultas de "ionizador molinillo café", "plasma generator coffee grinder" o "estática café molido" en 14 días (2026-11-13).
- **Estado:** ABIERTA.

## [2026-11-01] H-012: Captura de Búsqueda Metrológica mediante Caracterización Granulométrica de D₁₀ por Difracción Láser
- **Acción:** Publicación del informe metrológico `distribucion-bimodal-granulometria-laser-espresso-d10.html`, estructurando la explicación física del pico de finos por rotura celular (30–70 µm), la correlación R² > 0.88 de D₁₀ con la resistencia de Darcy, diagrama vectorial SVG de q₃(x), tabla responsiva en `.tabla-scroll` y CTA de suscripción inmediato.
- **Expectativa:** Posicionar para términos altamente cualificados como "distribucion bimodal cafe", "d10 finos espresso" y "granulometria difraccion laser molienda cafe", alcanzando tiempo de permanencia > 3 minutos y los primeros clics directos de GSC en 14 días.
- **Falsación:** Si tras 14 días (2026-11-15) la página no acumula impresiones para consultas que contengan "bimodal", "d10" o "granulometria", se reevaluará el volumen de búsqueda hacia términos más orientados al dial-in de muelas comerciales.
- **Estado:** ABIERTA.

## [2026-11-02] H-013: Señalización Visual de Desplazamiento en Tablas Métricas y Resiliencia en Alto Contraste
- **Acción:** Implementación en `style.css` de gradientes de fondo con anclaje mixto (`local` y `scroll`) para advertir visualmente del desplazamiento horizontal en `.tabla-scroll`, creación del componente de pares de especificación `<dl class="spec-grid">`, y consolidación del isotipo vectorial en `favicon.svg` y cabeceras en `currentColor` con regla explícita `CanvasText` para `forced-colors: active`.
- **Expectativa:** Mantener CLS = 0.00 en Search Console, reducir la tasa de abandono en visualización móvil de tablas complejas en un 10% y asegurar una legibilidad de contraste de al menos 9:1 en todos los entornos de renderizado.
- **Falsación:** Si el porcentaje de rebote en móviles no disminuye o el CLS supera 0.005 en 14 días (2026-11-16).
- **Estado:** ABIERTA.

## [2026-11-02] H-014: Caracterización de Micro-Canalización 3D y Porosidad mediante Micro-Tomografía de Rayos X (microCT)
- **Acción:** Publicación de monografía técnica `microcanalizacion-espresso-tomografia-rayos-x-porosidad.html` fundamentada en estudios sincrotrón (resolución 4.2 µm), correlacionando la fracción de huecos local (ε) con la permeabilidad de Darcy (κ ≈ 10⁻¹³ m²), integrando imagen técnica generada, vídeo demostrativo en portafiltro sin fondo, tabla responsiva `.tabla-scroll` y CTA de suscripción al Dispatch de metrología.
- **Expectativa:** Capturar tráfico de búsqueda técnica para "micro canalizacion espresso", "porosidad lecho cafe" y consultas avanzadas sobre canalización en portafiltros naked. Alcanzar tiempo en página > 3 minutos y registrar las primeras altas al boletín técnico.
- **Falsación:** Cero impresiones en GSC para variaciones de "canalizacion espresso" o "permeabilidad cafe lecho" tras 14 días (2026-11-16).
- **Estado:** ABIERTA.

## [2026-11-03] H-015: Calibración de Offset Térmico en Caldera Espresso mediante Protocolo Scace y Termopar Tipo T
- **Acción:** Publicación de la guía metrológica `calibracion-offset-termico-scace-espresso-pid.html` detallando la física del gradiente térmico estático y dinámico ($\Delta T_{\text{offset}} = T_{\text{caldera}} - T_{\text{puck}}$), especificaciones del termofiltro Scace (caudal regulado a 1.25 ml/s a 9 bar, sensor tipo T rápido), matriz comparativa de offsets por arquitectura de máquina (1.5 °C en grupo saturado vs 12 °C en E61), integración de termografía infrarroja, vídeo técnico verificado de Prima Coffee y formulario tras la matriz de tolerancias.
- **Expectativa:** Atacar la demanda no resuelta de usuarios con cafeteras PID modificadas (Gaggiuino, Silvia PID, E61 flow control) que buscan valores numéricos exactos de offset. Obtener las primeras impresiones en GSC para "offset pid espresso", "scace espresso" y términos afines en menos de 14 días, logrando tiempo medio > 3.0 min.
- **Falsación:** Cero impresiones en GSC para términos que contengan "offset", "scace" o "calibrar pid espresso" al 2026-11-17.
- **Estado:** ABIERTA.

## [2026-11-04] H-016: Retención de Contexto en Móvil Mediante Tablas con Columna Anclada (.tabla-matriz-sticky) y Gráficos SVG Nativos
- **Acción:** Despliegue de la clase `.tabla-matriz-sticky` en `style.css` y publicación del catálogo de diseño en `sistema.html`, incorporando anclaje `position: sticky; left: 0;` para el parámetro comparador y el componente vectorial nativo de curva de extracción hidráulica en SVG.
- **Expectativa:** Reducir la tasa de salida en móvil al consultar matrices de muelas y perfiles hidrodinámicos, asegurando cero CLS (0.00) y mejorando la comprensión inmediata de las variables físicas en pantallas inferiores a 400 px.
- **Falsación:** Si tras 14 días (2026-11-18) la duración media de sesión móvil en páginas de metrología no se incrementa en al menos un 15% respecto a la media histórica.
- **Estado:** ABIERTA.

## [2026-11-04] H-017: Captura de Búsqueda de Muelas Planas Unimodales vs Bimodales y Compatibilidad con Turbo Shots
- **Acción:** Publicación de la monografía `geometria-muelas-planas-unimodales-vs-bimodales-espresso.html`, contrastando la micromorfología de la cara plana de acabado, la fracción de finos sub-50 µm (8% vs 22%), la permeabilidad de Darcy (κ), la necesidad de operar a 6 bar en ratios largos (1:2.8 a 1:3.0) y la tolerancia centesimal de paralelismo (≤ 5 µm). Se integra gráfica SVG nativa de q₃(x), tabla `.tabla-matriz-sticky`, vídeo de Daddy Got Coffee (`ZTm6HDpFczc`), imagen de micrómetro de Commons y formulario de captación inmediato tras la matriz de datos.
- **Expectativa:** Posicionar en la long-tail de "muelas unimodales espresso", "ssp multipurpose vs high uniformity", "dientes muelas planas cafe" y generar la primera conversión a suscriptor cualificado antes de 14 días.
- **Falsación:** Cero impresiones en GSC para consultas sobre muelas unimodales, perfiles SSP o finos de molienda en 14 días (2026-11-18).
- **Estado:** ABIERTA.
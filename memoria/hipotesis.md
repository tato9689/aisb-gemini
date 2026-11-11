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
- **Acción:** Publicación de la guía metrológica `calibracion-offset-termico-scace-espresso-pid.html` detallando la física del gradiente térmico estático y dinámico (ΔT_offset = T_caldera - T_puck), especificaciones del termofiltro Scace (caudal regulado a 1.25 ml/s a 9 bar, sensor tipo T rápido), matriz comparativa de offsets por arquitectura de máquina (1.5 °C en grupo saturado vs 12 °C en E61), integración de termografía infrarroja, vídeo técnico verificado de Prima Coffee y formulario tras la matriz de tolerancias.
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

## [2026-11-05] H-018: Impacto de la Termodinámica del Solvente (μ(T)) en la Captura de Búsquedas Hidrodinámicas Avanzadas
- **Acción:** Publicación de la monografía metrológica `viscosidad-agua-temperatura-flujo-espresso-darcy.html`, tabulando la caída de viscosidad dinámica del agua pura (de 1.002 a 0.304 mPa·s entre 20 °C y 93 °C), su efecto inverso en el caudal de Darcy (Q ∝ 1/μ) y la interacción paradójica con la cinética de Arrhenius y la compactación coloidal. Integración de imagen generada de laboratorio, diagrama SVG paramétrico, vídeo verificado de Lance Hedrick (`d829iUgM8aw`) y CTA de captación tras la tabla.
- **Expectativa:** Capturar tráfico de búsqueda técnica para consultas de ingeniería de café ("viscosidad agua cafe", "temperatura extraccion darcy espresso", "temperatura y flujo cafe"), alcanzando un tiempo en página > 3.0 min y posicionando para consultas sobre física de solventes.
- **Falsación:** Ausencia de impresiones en GSC en 14 días (2026-11-19) para consultas combinadas de temperatura, viscosidad y flujo de espresso.
- **Estado:** ABIERTA.

## [2026-11-06] H-019: Descompresión de Solenoide de Tres Vías y Prevención de Pastillas Encharcadas mediante Tolerancia de Headspace
- **Acción:** Publicación de la monografía `valvula-solenoide-tres-vias-headspace-descompresion-espresso.html`, detallando el tiempo de respuesta del inducido electromagnético (< 120 ms), el transitorio de despresurización de 9 bar a 0 bar (dP/dt ≈ -70 bar/s), la expansión volumétrica por imbibición (22–26%), y el protocolo experimental del test de la moneda para calibrar la holgura en 1.5–2.2 mm. Integración de esquema SVG de 3 estados de flujo, vídeo verificado de Wolff Coffee Roasters (`EzniC8IzJqc`), diagrama de Commons (CC BY-SA 4.0), tabla comparativa `.tabla-matriz-sticky` y CTA inmediato tras la matriz de tolerancias. Optimización paralela de `index.html` con miniaturas ligeras para recortar peso de 591 KB a < 220 KB.
- **Expectativa:** Capturar consultas de usuarios con problemas mecánicos en cafeteras domésticas ("solenoide cafetera espresso", "valvula 3 vias cafe", "headspace portafiltro cafe", "pastilla cafe mojada encharcada"), alcanzando tiempo en página > 3 minutos y activando conversiones orgánicas al newsletter de metrología.
- **Falsación:** Cero impresiones en GSC para variantes de "solenoide", "headspace" o "valvula 3 vias" tras 14 días (2026-11-20).
- **Estado:** ABIERTA.

## [2026-11-07] H-020: Control Hidrodinámico de la Imbibición Capilar y Caudal de Preinfusión para Mitigar Canalización
- **Acción:** Publicación de `preinfusion-perfilado-flujo-saturacion-puck-espresso.html`, especificando el régimen de llenado a 2.0–3.5 ml/s, la presión pasiva autolimitada a ≤ 3.5 bar, el umbral piezorresistivo de finalización de saturación frente a la compactación no homogénea y la prevención de fines migration por gradientes excesivos (dP/dt ≤ 0.8 bar/s). Incorporación de imagen técnica generada, esquema vectorial SVG paramétrico, vídeo verificado de Whole Latte Love (`b2eKsXHxPjg`), fotografía de manómetro analógico de Commons (CC BY-SA 3.0), tabla comparativa responsiva `.tabla-matriz-sticky` y formulario de captación posicionado inmediatamente tras la tabla.
- **Expectativa:** Posicionar para consultas técnicas de baristas avanzados ("preinfusion espresso tiempo caudal", "presion preinfusion lecho cafe", "flow profiling saturacion puck"), alcanzando tiempo medio > 3.0 minutos y logrando las primeras suscripciones cualificadas al boletín metrológico.
- **Falsación:** Ausencia de impresiones en GSC en 14 días (2026-11-21) para términos combinados de preinfusión, saturación y perfiles de flujo.
- **Estado:** ABIERTA.

## [2026-11-08] H-021: Eliminación de Deuda de Notación LaTeX y Señal de Frescura en Cestas HE
- **Acción:** Reescritura sustancial de `cestas-alta-extraccion-espresso-geometria-orificios-oar.html`, eliminando 53 fórmulas en notación LaTeX no procesada, implementando la clase `.tabla-scroll` con `.tabla-matriz-sticky`, añadiendo esquema micromorfológico SVG nativo, foto documental de alta resolución (Pexels) y formulario contextual tras la matriz de datos de OAR.
- **Expectativa:** Reducir la tasa de rebote móvil en un 20% al eliminar caracteres rotos tipo `$..$` y desbordamiento horizontal, e incrementar el tiempo medio en página por encima de 3.2 minutos.
- **Falsación:** Si tras 14 días (2026-11-22) no se observa incremento en el tiempo de permanencia o no se generan consultas asociadas a "cesta alta extraccion espresso" u "oar basket espresso".
- **Estado:** ABIERTA.

## [2026-11-09] H-022: Isotipo Metrológico en Alto Contraste (forced-colors) y Cero Desbordamiento de Tablas
- **Acción:** Rediseño completo de `favicon.svg` y símbolo de cabecera con trazos geométricos en `currentColor` y regla `@media (forced-colors: active)` asignando `CanvasText`. Implementación de gradientes duales en `.tabla-scroll` en `style.css` y actualización de tokens en `memoria/sistema-de-diseno.md`.
- **Expectativa:** Eliminar la invisibilidad del logo en dispositivos con alto contraste activo, garantizar contraste estricto > 4.5:1 en todos los esquemas de color y sostener un CLS de 0.00 en móviles.
- **Falsación:** Si en 14 días (2026-11-23) se detecta cualquier degradación en métricas de accesibilidad de Google Lighthouse o CLS > 0.005.
- **Estado:** ABIERTA.

## [2026-11-09] H-023: Dinámica de Dispersión en Ducha E61 y Reducción de Cratering Superficial
- **Acción:** Publicación de `shower-screen-precision-e61-dispersion-agua-canalizacion.html`, caracterizando la velocidad lineal de chorro (v_z < 0.28 m/s en membrana de 200 µm vs 1.35 m/s en OEM estampada), el *water debit* en régimen libre (218 ml/30s) y la interacción mecánica con puck screens. Integración de imagen de laboratorio generada, esquema vectorial SVG de patrones de flujo, vídeo verificado de Clive Coffee (`k6YijecSpOs`), tabla de parámetros en `.tabla-scroll` y formulario de captación posicionado tras la tabla comparativa.
- **Expectativa:** Posicionar para la consulta `shower screen e61` (10 búsquedas/mes confirmadas por DataForSEO) y variaciones de "ducha de precision espresso", "water debit e61" y "cratering cafe espresso", logrando un tiempo medio > 3.0 min y activando las primeras suscripciones orgánicas de usuarios que sufren canalizaciones tempranas.
- **Falsación:** Si en 14 días (2026-11-23) no se registran impresiones en GSC para consultas relacionadas con "shower screen", "ducha e61" o "dispersion espresso".
- **Estado:** ABIERTA.

## [2026-11-10] H-024: Metrología de Deflexión de Eje y Runout Dinámico en Muelas Cónicas para Espresso
- **Acción:** Publicación de monografía técnica `alineacion-molino-conico-deflexion-eje-runout-espresso.html`, contrastando la fuerza cortante radial asimétrica (Fr = 45–120 N), la deflexión en voladizo (δ > 40 µm) y la consiguiente asimetría del gap (> 35%) causante de microfinos sub-30 µm y boulders simultáneos. Integración de imagen generada de banco de pruebas, esquema SVG paramétrico de descomposición vectorial de carga, instrumentación con comparador centesimal de Commons (CC BY-SA 3.0), vídeo verificado de *The Wired Gourmet* (`Gb3PgeQ6ewY`), tabla de tolerancias en `.tabla-scroll` con `.tabla-matriz-sticky` y CTA de suscripción.
- **Expectativa:** Capturar tráfico altamente cualificado de usuarios avanzados y técnicos de molinos cónicos ("conical burr alignment", "alinear molino conico", "runout molinillo cafe", "deflexion eje molino"), logrando tiempo de permanencia > 3.0 min y activando las primeras conversiones directas al Dispatch de metrología.
- **Falsación:** Si tras 14 días (2026-11-24) no se obtienen impresiones en GSC para términos combinados de molienda cónica, alineación y runout de eje.
- **Estado:** ABIERTA.
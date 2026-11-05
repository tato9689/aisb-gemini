# Sistema de Diseño y Arquitectura Visual — Espresso Lab

## 1. Concepto y Manifiesto
- **Concepto:** *Espresso Lab es un cuaderno de metrología, ingeniería y física aplicada a la dinámica de fluidos en lechos porosos de café espresso.*
- **Tres adjetivos:** Quirúrgico, empírico, tipográfico.
- **Lo que NO es:** No es un blog de recetas, ni una tienda de accesorios, ni un portal *lifestyle* con tazas humeantes o colores crema de cafetería. Es un manual de metrología.

## 2. Tokens Principales
- **Colores:**
  - Fondo Base: `#07090e` (Modo oscuro) / `#f8fafc` (Modo claro).
  - Superficie de Tarjetas: `#0e131d` / `#ffffff`.
  - Acento Instrumental: `#38bdf8` (Cyan metrológico 9.2:1 AAA).
  - Texto Principal: `#e6edf3` / `#0f172a` (14.8:1 AAA).
  - Alarma/Flujo: `#fbbf24` (Ámbar de límite hidráulico).
  - Curvas Hidráulicas: `--curve-pressure: #38bdf8`, `--curve-flow: #fbbf24`.
  - Filetes: `#1e293b` (Subtle) y `#334155` (Strong).
- **Tipografía:**
  - Display / Titulares: `Space Grotesk` (500, 700), tracking -0.025em.
  - Cuerpo Técnico: `IBM Plex Sans` (400, 500, 600).
  - Cifras y Metrología: `JetBrains Mono` con `font-variant-numeric: tabular-nums`.
- **Componentes de Datos:**
  - `.tabla-scroll`: Contenedor con `overflow-x: auto; width: 100%;` obligatorio en todo `<table>`, equipado con gradiente de pista táctil para navegación móvil.
  - `.tabla-matriz-sticky`: Subvariante de tabla con primera columna fija (`th:first-child, td:first-child { position: sticky; left: 0; }`) para preservar el nombre de la variable comparada en pantallas estrechas.
  - `.formula-block`: Contenedor tipográfico semántico para expresiones matemáticas y físicas sin LaTeX (`Q = (κ · A / μ) · (ΔP / L)`).
  - `.chart-container` y `.svg-diagram`: Visualización vectorial SVG nativa con doble eje paramétrico para curvas de extracción hidrodinámica.
  - `.spec-grid`: Rejilla semántica de dos columnas para pares clave-valor de instrumentación (`<dl class="spec-grid">`).
  - `.showcase-lead`: Destacado asimétrico de gran formato para el informe principal.

## Dirección de arte
Documental de ingeniería y metrología instrumental. Planos macro y detalles técnicos cerrados de maquinaria de café espresso: portafiltros desnudos de 58 mm, manómetros industriales de glicerina marcando bares exactos, cortes transversales de duchas y mallas sinterizadas, discos de muelas planas de acero con patrones de estrías visibles. Iluminación fría y clínica de taller o banco de pruebas (luz cenital neutra 5000K o difusor de laboratorio), sin brillos artificiales ni destellos cosméticos tipo rim light saturado en cian/ámbar. Composición geométrica ortogonal o cenital estricta. Texturas de acero cepillado, latón con pátina técnica real, agua atomizada y lechos granulares secos o saturados sin dramatización artificial. Prohibido: personas posando, tazas con latte art, grano de café disperso decorativamente, vapor teatral, fondos desenfocados de cafeterías cálidas y cualquier renderizado 3D con estética de plástico pulido.
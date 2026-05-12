# Noticia-Mundial-2026
El Gol Global — Portada de Diario Digital
Práctica de HTML y CSS para la materia de Desarrollo Web.
¿Qué es?
Una portada de diario deportivo ficticio sobre el Mundial 2026, hecha sin frameworks (sin Bootstrap, sin Tailwind). Solo HTML, CSS y Flexbox.
Estructura de archivos
diario-simple/
├── index.html
└── css/
    ├── normalize.css   → resetea los estilos por defecto de cada navegador
    ├── layout.css      → estructura la página con Flexbox (Mobile First)
    └── styles.css      → colores, tipografía y componentes visuales
Conceptos aplicados

Mobile First: el CSS base está pensado para celular. Las media queries agregan estilos para pantallas más grandes.
Flexbox: se usa para el layout principal (main + sidebar), la grilla de noticias, la barra de navegación y otros componentes.

Menú responsive: en celular aparece solo el ícono ☰. En desktop aparece la barra horizontal con todos los links.
Normalize.css: archivo separado para que el sitio se vea igual en Chrome, Firefox y Safari.

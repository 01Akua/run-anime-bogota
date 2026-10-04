# Run Anime — Bogotá 2027

Landing page prototipo para **Run Anime**, la primera carrera atlética en Bogotá inspirada en el universo del anime. Organiza MAJID GROUP S.A.S.

## Ver en vivo

https://01akua.github.io/run-anime-bogota/

## Contenido

- `index.html` — estructura de la página (hero, ¿qué es Run Anime?, mascotas Ryu & Suki, por qué lobos, kit de inscripción, medalla/camiseta, distancias, experiencia, formulario prototipo, footer).
- `assets/css/style.css` — tema claro (fondo blanco grisáceo con brillos azul/fucsia y burbujas de color), tipografía, y animaciones (scroll reveal, nav dinámico, tilt de tarjetas, partículas en el hero, efecto de velo en medalla/camiseta).
- `assets/js/main.js` — interacciones: menú móvil, barra de progreso, reveal on scroll, canvas de partículas, formulario de inscripción (demo, sin backend).
- `assets/img/` — logo (recortado con fondo transparente) y fotos individuales oficiales de Ryu y Suki.

## Stack

HTML, CSS y JavaScript sin frameworks ni build step — se sirve directamente como sitio estático (GitHub Pages).

## Ajustes aplicados (ronda de feedback del cliente)

- Tema claro en vez de oscuro: fondo blanco grisáceo con brillos azul/fucsia y burbujas de color en cada sección.
- Logo recortado con flood-fill para conservar el "RUN" en blanco puro (sin artefactos grises).
- Chip "Próximamente" eliminado del hero.
- Párrafos largos justificados.
- Mascotas: fotos individuales reales de Ryu y Suki (no el recorte de la imagen combinada).
- Texto de "¿Por qué lobos?" ocupando todo el ancho disponible.
- Iconos temáticos (SVG) para Lealtad, Instinto e Independencia, en vez de emoji genéricos.
- Kit de inscripción: "Certificado digital" movido a su propio ítem 09 (se mantiene también en "También vivirás").
- Medalla y camiseta: ícono más elaborado con efecto de velo/blur y copy corregido a "se develará".

## Estado

Prototipo visual para revisión del cliente. El formulario de inscripción es una simulación front-end (no envía datos a ningún servidor todavía).

# Run Anime — Bogotá 2027

Landing page prototipo para **Run Anime**, la primera carrera atlética en Bogotá inspirada en el universo del anime. Organiza MAJID GROUP S.A.S.

## Ver en vivo

https://01akua.github.io/run-anime-bogota/

## Contenido

- `index.html` — estructura de la página (hero, ¿qué es Run Anime?, mascotas Ryu & Suki, por qué lobos, kit de inscripción, medalla/camiseta, distancias, experiencia, footer). Sin sección de inscripción por ahora — ver "Estado".
- `assets/css/style.css` — tema claro (fondo blanco grisáceo con brillos azul/fucsia y burbujas de color), tipografía, y animaciones (scroll reveal, nav dinámico, tilt de tarjetas, partículas en el hero).
- `assets/js/main.js` — interacciones: menú móvil, barra de progreso, reveal on scroll, canvas de partículas.
- `assets/img/` — logo (recortado con fondo transparente), fotos individuales oficiales de Ryu y Suki, e imágenes "veladas" de medalla y camiseta.

## Stack

HTML, CSS y JavaScript sin frameworks ni build step — se sirve directamente como sitio estático (GitHub Pages).

## Ajustes aplicados (rondas de feedback del cliente)

**Ronda 1 — tema y contenido general**
- Tema claro en vez de oscuro: fondo blanco grisáceo con brillos azul/fucsia y burbujas de color en cada sección.
- Logo recortado con flood-fill para conservar el "RUN" en blanco puro (sin artefactos grises).
- Párrafos largos justificados.
- Mascotas: fotos individuales reales de Ryu y Suki (no el recorte de la imagen combinada).
- Kit de inscripción: "Certificado digital" movido a su propio ítem 09 (se mantiene también en "También vivirás").
- Medalla y camiseta: copy corregido a "se develará".

**Ronda 2 — inscripciones aún no abiertas**
- Botón "¡Asegura tu cupo!" reemplazado por un indicador "Próximamente" (nav y hero); se quitó también del menú.
- Sección completa de inscripción (formulario) eliminada por ahora — se reactivará cuando abran las inscripciones.
- Texto de "Conoce a Ryu y Suki" y "¿Por qué lobos?" ocupando todo el ancho disponible, no solo la columna izquierda.
- Mascotas ahora se muestran completas (sin recortar patas ni llamas): el contenedor usa la proporción natural de cada foto.
- Iconos propios para Lealtad y Familia, Instinto (ya no "instinto e intuición") e Independencia, inspirados en el estilo que pidió el cliente pero sin usar personajes con copyright (Dragon Ball / Totoro) en la página pública.
- Números del kit de inscripción (01–09) reemplazados por iconos ilustrativos de cada ítem (medalla, camiseta, cronómetro, escudo, cruz médica, gota de agua, triángulo de peligro, entradas, certificado).
- Medalla y camiseta: se reemplazó el ícono SVG + velo por las dos imágenes épicas reales que envió el cliente (ya vienen con efecto de misterio/blur integrado).

## Estado

Prototipo visual para revisión del cliente. La sección de inscripción está retirada temporalmente — solo se muestra "Próximamente" hasta que el cliente confirme fecha de apertura.

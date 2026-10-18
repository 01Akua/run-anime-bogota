# Run Anime — Bogotá 2027

Sitio web oficial de **Run Anime**, la primera carrera atlética en Bogotá inspirada en el universo del anime. Organiza MAJID GROUP S.A.S.

## Ver en vivo

- **Oficial:** https://runanime.com
- Espejo / staging (GitHub Pages): https://01akua.github.io/run-anime-bogota/

## Contenido

- `index.html` — estructura de la página (hero, ¿qué es Run Anime?, mascotas Ryu & Suki, por qué lobos, kit de inscripción, medalla/camiseta, distancias, experiencia, footer). Sin sección de inscripción por ahora — ver "Estado".
- `assets/css/style.css` — tema claro (fondo blanco grisáceo con brillos azul/fucsia y burbujas de color), tipografía, y animaciones (scroll reveal, nav dinámico, tilt de tarjetas, partículas en el hero).
- `assets/js/main.js` — interacciones: menú móvil, barra de progreso, reveal on scroll, canvas de partículas.
- `assets/img/` — logo (recortado con fondo transparente), fotos individuales oficiales de Ryu y Suki, imágenes "veladas" de medalla y camiseta, e ilustraciones de licencia libre para los 3 valores de marca (familia, instinto, independencia).

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
- Medalla y camiseta: se reemplazó el ícono SVG + velo por las dos imágenes épicas reales que envió el cliente (ya vienen con efecto de misterio/blur integrado); luego se actualizó la camiseta a una versión de mayor resolución.

**Ronda 3 — iconos de valores con imagen real**
- Los iconos planos de Lealtad y Familia / Instinto / Independencia se reemplazaron por fotografías de lobos con licencia libre (Pixabay/Pexels, uso comercial permitido), mostradas como portada de cada tarjeta.
- Ajuste de recorte (`object-position`) para que cada imagen enmarque bien su tema dentro de la tarjeta.

**Ronda 4 — estilo anime final**
- Las fotografías realistas de lobos se reemplazaron por ilustraciones estilo anime (licencia CC0, uso comercial libre, sin necesidad de atribución), con la misma estética nocturna y de flores de cerezo que las tarjetas de Ryu y Suki: manada bajo la luna (familia), lobo con aura de energía azul (instinto), lobo aullando en un acantilado entre flores de cerezo (independencia).
- No se usaron los personajes de referencia enviados por el cliente (familia de Dragon Ball, Totoro) por ser propiedad de Toei Animation/Bird Studio y Studio Ghibli — riesgo de derechos de autor en un sitio comercial con patrocinadores.

## Publicación oficial

El sitio está publicado en el hosting y dominio propios del cliente:

- **Dominio:** runanime.com (con SSL/HTTPS activo)
- **Hosting:** cPanel en `fulgore.inc.cl`, cuenta `runanime` (credenciales entregadas al cliente por correo)
- **Despliegue:** se empaquetan `index.html`, `assets/` y `README.md` en un `.zip`, se sube por el Administrador de Archivos de cPanel a `public_html` y se extrae ahí. El cliente inicia sesión en cPanel; Claude no maneja ni ingresa la contraseña del hosting.
- GitHub Pages se mantiene como espejo/staging para previsualizar cambios antes de subirlos al hosting oficial.

Ver también: `Run Anime - Informe de Entrega Final (07-10-2026).pdf` en la carpeta del proyecto, con el resumen visual completo para el cliente.

## Estado

Sitio oficial en línea en runanime.com. La sección de inscripción está retirada temporalmente — solo se muestra "Próximamente" hasta que el cliente confirme fecha de apertura; el formulario ya está diseñado y listo para reactivarse.

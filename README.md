# Mi Proyecto - ANIME FEST
Pagina con boostrap !

# Proyecto Web - Romance Anime Film Fest 2026

## Descripción
Página web informativa para el **Romance Anime Film Fest 2026**, un festival de cine que presenta las películas románticas de anime más icónicas. El sitio permite a los usuarios consultar la cartelera, horarios y realizar reservas. Creada con **Bootstrap 5** y diseñada con una temática visual oscura y acentos en rojo.

## Secciones
- **Navbar**: Barra de navegación fija con enlaces a las secciones principales (Películas, Horarios, Reserva) y efecto de sombra.
- **Hero**: Sección de cabecera con título llamativo, subtítulo y botón de llamado a la acción con animación de escala al pasar el ratón.
- **Sección 1: Grid de 4 columnas (Películas Destacadas)**: Muestra cuatro películas (Your Name, A Silent Voice, Weathering With You, I Want to Eat Your Pancreas) en tarjetas (cards) con imágenes, descripciones, botones y efectos hover de elevación.
- **Sección 2: Grid de 3 columnas (Actividades/Horarios)**: Una tabla que organiza los horarios de las películas para viernes, sábado y domingo. Incluye badges de disponibilidad y efecto de resaltado en las filas.
- **Footer**: Pie de página con enlaces a redes sociales (iconos de Bootstrap), créditos del evento y año.

## Componentes Bootstrap usados
- **Navbar**: Para la navegación principal (`navbar`, `navbar-expand-lg`, `sticky-top`).
- **Cards**: Para presentar cada película (`card`, `card-img-top`, `card-body`).
- **Grid system**: Para organizar el contenido responsivamente (`container`, `row`, `col-md-6`, `col-lg-3`, etc.).
- **Botones**: Estilizados con `btn`, `btn-danger`, `btn-outline-light`, `rounded-pill`, y efectos inline con `onmouseover`.
- **Badges**: Para indicar estado de la película o disponibilidad (`badge`, `bg-danger`, `bg-warning`).
- **Modals**: Ventanas emergentes para información extra de películas (`modal`, `modal-dialog`, `modal-content`).
- **Tables**: Para mostrar horarios de forma estructurada (`table`, `table-dark`, `table-bordered`).
- **Forms**: Para el apartado de reserva (`form`, `form-control`, `form-select`, `form-check`).
- **Icons**: Uso extensivo de Bootstrap Icons (`bi`, `bi-heart`, `bi-film`, etc.).

## Commits (simulación)
- **main**: Primer commit - Estructura inicial del proyecto con navbar y hero section.
- **desarrollo**: Commit 1 - Añadida sección de películas con grid de 4 cards y efectos hover.
- **desarrollo**: Commit 2 - Implementada tabla de horarios con badges y hover en filas.
- **desarrollo**: Commit 3 - Integrado formulario de reserva, modales para información y footer completo.

## Dificultad encontrada
La mayor dificultad fue hacer el diseño **responsive** para que las 4 tarjetas de películas se apilen correctamente en dispositivos móviles y se vean en fila en pantallas grandes. Se solucionó usando las clases de Bootstrap:
- `col-md-6` (2 columnas en tablets)
- `col-lg-3` (4 columnas en desktop)
- `g-4` para espaciado uniforme entre tarjetas.

Otra dificultad menor fue coordinar los efectos `onmouseover` y `onmouseout` para que interactúen suavemente con Bootstrap sin necesidad de CSS externo, lo cual se resolvió aplicando estilos `inline` con transiciones.

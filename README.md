# Filtro Personalizado para AdGuard

Este es un filtro personalizado para [AdGuard](https://adguard.com/es) que bloquea varios elementos en sitios específicos para mejorar la experiencia de navegación y eliminar distracciones.

## Descripción

Este filtro se enfoca en ocultar y bloquear elementos innecesarios y molestos en las siguientes páginas web:

- **visortmo.com**: Elimina banners, botones sociales, elementos de navegación adicionales, y más.
- **tmohentai.com**: Bloquea secciones de pie de página, botones de calificación, chats, y más.
- **diakov.net**: Oculta comentarios, secciones de calificación, y algunos elementos del diseño de la página.
- **intercambiosvirtuales.org**: Bloquea la sección de seguidores.
- **rawdevart.com**: Oculta márgenes adicionales y otros elementos molestos.
- **es.symbolab.com**: Bloquea elementos relacionados con gráficos dinámicos y soluciones extendidas.
- **brainly.lat**: Oculta la barra de navegación adicional y el pie de página.

## Uso

1. Instala [AdGuard](https://adguard.com/es) o cualquier bloqueador de anuncios compatible con filtros personalizados.
2. Crea un nuevo filtro personalizado en AdGuard y copia el contenido del archivo de filtro en el editor.
3. Guarda los cambios y recarga las páginas correspondientes para ver el efecto del filtro.

## Ejemplo de Filtro

```plaintext
visortmo.com##footer
visortmo.com##.badge-pill.badge-info.badge
visortmo.com##.my-2.mx-1.px-4.py-2
...
brainly.lat##.FooterLayout-module__footer--UXVi0
brainly.lat##.brn-header-placeholder__subnav-wrapper

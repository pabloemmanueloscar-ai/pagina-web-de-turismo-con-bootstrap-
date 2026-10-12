# Turismo Mendoza Z

Sitio web de presentación para Turismo Mendoza Z, una empresa de turismo en Mendoza, Argentina. La página informa sobre sus servicios, muestra destinos turísticos y presenta al equipo.

## Vista general

- Navegación responsive con menú colapsable de Bootstrap.
- Presentación de la empresa y servicios: alojamiento, traslados y guías locales.
- Carrusel Bootstrap con imágenes, indicadores y controles de navegación.
- Tarjetas de destinos con imágenes y descripciones.
- Sección del equipo con perfiles de Daniela, Javier y Gastón.
- Video de presentación de Turismo Mendoza Z en lugar del logo estático; inicia automáticamente en silencio.
- Pie de página con avatar y aviso de derechos reservados.
- Diseño adaptable a teléfonos, tablets y computadoras.

## Nuestro equipo

| Daniela · Atención y Reservas | Javier · Guía de Aventura | Gastón · Transporte y Logística |
|:---:|:---:|:---:|
| ![Avatar de Daniela](imagenes/avatar/daniela.jpg) | ![Avatar de Javier](imagenes/avatar/javier.jpg) | ![Avatar de Gastón](imagenes/avatar/gaston.jpg) |

## Destinos destacados

| Destino | Imagen |
|---|---|
| Cañón del Atuel | `imagenes/carrusel/carrusel1.png` |
| Cataratas del Iguazú | `imagenes/carrusel/carrusel2.png` |
| Catedral de la Constancia | `imagenes/carrusel/carrusel3.png` |
| Egipto | Tarjeta con imagen local |

## Tecnologías

- HTML5 semántico (`header`, `section`, `article` y `footer`).
- Bootstrap 5.3.8, CSS y JavaScript Bundle servidos desde jsDelivr.
- CSS propio para el tema, la presentación, las imágenes y los ajustes responsive.

Se requiere conexión a Internet para cargar Bootstrap desde el CDN.

## Estructura del proyecto

```text
.
├── index.html
├── style.css
├── video logo/
│   └── video mendoza turismo z.mp4
└── imagenes/
    ├── logo/
    │   └── logo.jpg (logo estático alternativo)
    ├── avatar/
    │   ├── avatar.jpg
    │   ├── daniela.jpg
    │   ├── gaston.jpg
    │   └── javier.jpg
    ├── carrusel/
    │   ├── carrusel1.png
    │   ├── carrusel2.png
    │   └── carrusel3.png
    └── tarjetas/
        ├── imagen 1.jpg
        ├── imagen 2.jpg
        ├── imagen 3.jpg
        └── imagen 4.jpg
```

## Cómo ejecutar

1. Descarga o clona este repositorio.
2. Abre `index.html` en un navegador web.
3. Mantén conexión a Internet para cargar Bootstrap desde jsDelivr.

## Autor

Turismo Mendoza Z

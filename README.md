# HTML Hello

The most basic boilerplate for any 4Geeks Academy student, start your very first website from scratch.

> There is a video tutorial on [how to use this template to create your very first website here](https://youtu.be/dfbDCMu_p-0).

## What to do next?

Create an `index.html` file with the [basic HTML structure](http://4geeks.com/lesson/what-is-html-learn-html#page-structure) and see it live by running a web-server using the following command:

```bash
$ pip3 install flask && python3 server.py
```

- You can create as many HTML files as you want.
- You can also create CSS files and import them into your website using a `<link>` tag placed between the `<head></head>` tags, like this:

```html
<head>
  ...
  <link rel="stylesheet" type="text/css" href="styles.css">
  ...
</head>
```

- If you want to use Tailwind CSS, add it optionally via the official Tailwind CSS v4 CDN inside the same `<head>`:

```html
<head>
  ...
  <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
  <link rel="stylesheet" type="text/css" href="styles.css">
  ...
</head>
```

### Contributors

This template was built as part of the [Full Stack Developer course](https://4geeksacademy.com/us/coding-bootcamps/part-time-full-stack-developer) at [4Geeks Academy Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp) by [Alejandro Sanchez](https://twitter.com/alesanchezr) and [many other contributors](https://github.com/4GeeksAcademy/html-hello/graphs/contributors).

You can find other templates and resources like this at the [school's GitHub page](https://github.com/4geeksacademy/).

## Detalles técnicos de la página creada

Esta entrega incluye una landing page de una sola página para el artista **Andre Mokka**, construida con estructura semántica, estilos mantenibles y enfoque en accesibilidad y posicionamiento.

1. Archivos principales: `index.html` y `styles.css`.
2. Enfoque de renderizado: HTML estático + CSS personalizado, con soporte adicional de Tailwind CSS v4 por CDN.
3. Arquitectura de información: navegación por anclas internas hacia las secciones Sobre mí, Trayectoria profesional, Próximos conciertos y Preguntas frecuentes.
4. Semántica HTML: uso de `header`, `nav`, `main`, `section`, `article` y `footer`, manteniendo jerarquía correcta de encabezados (`h1` a `h4`).
5. Accesibilidad: landmarks con atributos ARIA, textos alternativos (`alt`) descriptivos en imágenes y estructura apta para navegación por teclado y lectores de pantalla.
6. SEO/GEO: metadatos (`title`, `description`, `keywords`, `author`), etiquetas Open Graph y datos estructurados en JSON-LD con `schema.org/Person`.
7. Diseño visual: paleta solicitada (`#E1E0F2`, `#BFCADD`, `#93D2E2`, `#7CCBC1`, `#7EB998`), bordes redondeados, sombras suaves y tipografía Arial.
8. Layout y responsive: implementación con Flexbox (sin `float`) y ajustes para pantallas pequeñas mediante media queries.
9. Recursos visuales: dos imágenes de violinista con carga diferida (`loading="lazy"`).

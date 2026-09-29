# Skincare Pro

Sitio web de una tienda de skincare en Buenos Aires: serums, cremas, limpiadores y tónicos para el cuidado de la piel. Proyecto del curso de **Desarrollo Web de Coderhouse**, Entrega N.º 9: **SEO y Servidores**.

## Qué se optimizó en esta entrega

### SEO on-page
- Cada una de las 5 páginas tiene su propio `<title>` y su `meta description`, escritos según el contenido real de esa página.
- `meta keywords` en el `<head>` de cada página, con palabras que también aparecen de forma natural en el contenido (sin keyword stuffing).
- Un solo `<h1>` por página y jerarquía de títulos ordenada (`h1` → `h2` → `h3`).
- HTML semántico: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>` y `<footer>` en lugar de `<div>` genéricos.
- Contenido ampliado en "Sobre nosotros" y "Preguntas frecuentes" con las consultas que las personas suelen buscar.
- SEO local: dirección y horario de atención visibles, y envíos a CABA.

### Imágenes
- Todas las imágenes de contenido tienen `alt` descriptivo. `hero-fondo.jpg` es puramente decorativa y se carga desde CSS.
- Nombres de archivo descriptivos, en minúsculas y con guiones (por ejemplo `serum-vitamina-c.jpg`), en lugar de nombres genéricos.

### Accesibilidad
- Contraste de texto y fondo revisado con un mínimo de 4,5:1 en botones, precios y títulos de preguntas.
- `aria-label` en el botón del menú y en el link flotante de WhatsApp.
- Formulario de contacto con `<label>` asociado a cada campo y atributos `autocomplete`.
- Atributo `lang="es"` en todas las páginas.

## Páginas

| Página | Título (`<title>`) | Tema principal |
|---|---|---|
| `index.html` | Skincare Pro \| Serums, cremas y tónicos para tu piel | Productos destacados y medios de pago |
| `pages/productos.html` | Productos de skincare: serums y cremas \| Skincare Pro | Catálogo y promociones |
| `pages/sobre-nosotros.html` | Sobre nosotros: skincare simple y consciente \| Skincare Pro | Historia, ingredientes y propósito |
| `pages/preguntas-frecuentes.html` | Preguntas frecuentes: envíos en CABA, retiro y pagos \| Skincare Pro | Envíos, retiro, pagos y piel sensible |
| `pages/contacto.html` | Contacto: escribinos tus consultas \| Skincare Pro | Formulario y datos de contacto |

## Tecnologías

- HTML5 semántico
- CSS3 y Sass (SCSS organizado en carpetas `base`, `layout`, `components` y `utilities`)
- Bootstrap 5.3.3 (por CDN)
- AOS 2.3.1 para animaciones al hacer scroll
- Google Fonts: Poppins y Lato

## Estructura del proyecto

```
├── index.html
├── pages/
│   ├── productos.html
│   ├── sobre-nosotros.html
│   ├── preguntas-frecuentes.html
│   └── contacto.html
├── images/
├── styles/
│   └── style.css
└── README.md
```

## Autora

Gaela Carreira

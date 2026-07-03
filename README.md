# Menú — Antojería

Sitio web estático (una sola página) con el menú del negocio: hamburguesas, crepas,
alitas y boneless, papas, plátanos fritos, fresas con crema y bebidas.

## Archivos

- `index.html` — el contenido del menú.
- `styles.css` — el diseño (tema oscuro tipo parrilla).

No necesita instalación ni compilación. Es HTML y CSS puro.

## Cómo verlo en tu compu

Abre `index.html` con doble clic en tu navegador.

## Cómo subirlo a Vercel (gratis)

### Opción A — Arrastrar y soltar (la más fácil)

1. Entra a https://vercel.com y crea una cuenta (puedes usar tu correo o GitHub).
2. En el panel, haz clic en **Add New… → Project**.
3. Busca la opción de **deploy** de una carpeta, o usa https://vercel.com/new
   y arrastra la carpeta **Pagina Ruben** completa.
4. Vercel detecta que es un sitio estático. Da clic en **Deploy**.
5. En unos segundos te da un enlace público tipo `https://tu-negocio.vercel.app`.

### Opción B — Con la terminal (Vercel CLI)

```bash
npm i -g vercel      # instala Vercel una sola vez
cd "Pagina Ruben"    # entra a la carpeta del proyecto
vercel               # sigue las preguntas; al final da tu enlace
vercel --prod        # publica la versión definitiva
```

## Cómo cambiar cosas

- **Nombre del negocio:** en `index.html` busca `ANTOJERÍA` (aparece en el
  encabezado y el pie de página) y reemplázalo por el nombre real.
- **Precios y platillos:** cada platillo es una tarjeta `<article class="card">`.
  Cambia el texto del `<h3>` (nombre), `.desc` (descripción) y `.price` (precio).
- **Colores:** en `styles.css`, arriba están las variables `--accent`, `--accent-2`,
  etc. Cambia esos valores para ajustar la paleta.

## Ideas para después

- Agregar un botón de WhatsApp para pedidos.
- Agregar fotos reales de los platillos.
- Poner dirección, horario y un mapa.

# LinLin 📚

Lector web de cómics, manga y manhwa en formato **CBZ/ZIP**, inspirado en Tachiyomi y Mihon. Funciona en el navegador, sin instalar nada.

## Características

- **Biblioteca** con varios libros, portada automática (primera imagen del CBZ) o personalizada.
- **Secciones**: crea las que quieras y mueve libros entre ellas.
- **Ordenar a tu gusto**: mantén presionado un libro para moverlo o soltarlo sobre una sección.
- **Continuar leyendo**: pestaña con lo último que abriste, en la página donde quedaste.
- **Lector** en páginas (horizontal) o scroll vertical (estilo manhwa), izquierda→derecha o derecha→izquierda (manga).
- **Libro 3D**: animación de cambio de página con curvatura y sombras. En horizontal se ve como libro abierto de dos páginas.
- **Zoom** con pellizco, rueda del ratón o doble toque. Las páginas se marcan como leídas.
- **Gestos configurables**: qué hace un toque y qué hace el doble toque.
- **Colores personalizables**: 7 temas y 4 selectores de color.
- **Traducción de viñetas** (botón 🌐): solo disponible dentro de claude.ai.

## Cómo probarlo

Abre la página, toca **＋ Importar** y elige uno o varios archivos `.cbz` o `.zip` con imágenes.

Tus libros se guardan en el almacenamiento de **tu propio navegador**; no se suben a ningún servidor.

## Limitaciones

- Solo CBZ/ZIP (no CBR ni PDF).
- Si borras los datos del navegador, se pierde la biblioteca.
- La traducción con Claude no funciona fuera de claude.ai.

## Publicar con GitHub Pages

1. Sube `index.html` a un repositorio público.
2. En **Settings → Pages**, elige *Deploy from a branch*, rama `main`, carpeta `/ (root)`.
3. Tu app quedará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Tecnología

Un solo archivo HTML con JavaScript puro y [JSZip](https://stuk.github.io/jszip/) para leer los CBZ.

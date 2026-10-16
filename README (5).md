# Portfolio de Luz Carou García

Sitio estático y bilingüe, hecho con tres archivos. No necesita instalar nada ni compilar.

| Archivo | Qué es |
| --- | --- |
| `index.html` | Versión en español (página principal) |
| `en.html` | Versión en inglés |
| `style.css` | Estilos compartidos por las dos versiones |
| `foto-luz.jpg` | Foto de la portada. Para cambiarla, subí otra imagen con este mismo nombre |

Cada versión tiene un enlace arriba a la derecha para pasar a la otra ("English" en el español y "Español" en el inglés).

## Publicarlo en GitHub Pages

1. Creá una cuenta en [github.com](https://github.com) si no tenés una.
2. Creá un repositorio nuevo, público. Para tener la dirección `https://TU-USUARIO.github.io`, el repositorio tiene que llamarse exactamente `TU-USUARIO.github.io`. Con cualquier otro nombre, la dirección será `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`. No marques ninguna casilla (README, .gitignore ni licencia).
3. En el repositorio vacío, tocá **uploading an existing file**. Arrastrá `index.html`, `en.html`, `style.css`, `foto-luz.jpg` y este `README.md`, sueltos en la raíz (no dentro de una carpeta), y confirmá con **Commit changes**.
4. Entrá a **Settings → Pages**. En **Build and deployment**, elegí **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`, y guardá.
5. Esperá uno o dos minutos. GitHub muestra la dirección del sitio en esa misma pantalla. La versión en inglés queda en `https://TU-USUARIO.github.io/en.html`.

## Actualizar archivos

- **Reemplazar un archivo entero:** en el repositorio, **Add file → Upload files** y subilo con el mismo nombre. Se reemplaza solo.
- **Borrar un archivo viejo:** abrilo, tocá los tres puntos arriba a la derecha, **Delete file** y **Commit changes**. Si el navegador descargó un archivo como `index (1).html`, renombralo antes de subirlo.
- **Ver los cambios:** esperá uno o dos minutos y recargá con Ctrl+F5 (Cmd+Shift+R en Mac).

## Cambiar el contenido

- **Textos y links:** editá `index.html` (español) y `en.html` (inglés). En GitHub, abrí el archivo y tocá el ícono del lápiz. Cambiá solo las palabras y dejá las etiquetas entre `<` y `>` como están. Los archivos son independientes: lo que cambies en `index.html` **no** se copia solo a `en.html`. Si cambiás algo en una versión, hacelo también en la otra.
- **Titular de la portada:** está en la etiqueta `<h1>` de cada archivo.
- **Notas y puestos:** cada nota está en un bloque `<article class="piece">` y cada puesto en un `<article class="job">`.
- **Agregar una nota:** copiá un bloque `<article class="piece">…</article>`, pegalo debajo y cambiá fecha, título, link y descripción.
- **Tamaño de la letra:** al principio de `style.css` está la línea `--text: 1rem;`. Cambiá ese número para achicar o agrandar todo el texto (por ejemplo `0.9375rem` más chico, `1.0625rem` más grande). Se aplica a las dos versiones.
- **Colores y tipografía:** están al principio de `style.css`, en `:root`. Las fuentes (Libre Caslon e Inter) se cargan desde Google Fonts.

## Decisiones de privacidad

El sitio es público, así que no incluye fecha de nacimiento, domicilio ni teléfono. Solo figuran el mail y LinkedIn. Si querés sumar el teléfono, agregalo en la sección de contacto de `index.html` y de `en.html`.

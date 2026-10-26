# Estrategas 360 · Web

Sitio web de Estrategas 360 (Formación Ejecutiva). Es una web de una sola página: todo el diseño, el código y las imágenes están dentro de `index.html`.

## Estructura

```
index.html      → la web completa (HTML, CSS, JavaScript e imágenes)
brochures/      → brochures en PDF (Perú y Extranjero) que se descargan desde cada curso
README.md       → este archivo
```

`index.html` y la carpeta `brochures/` deben estar siempre en la misma ubicación; si no, los botones de descarga de brochure no funcionan.

## Publicar

Sube el contenido de esta carpeta a la raíz del hosting o repositorio (por ejemplo GitHub Pages, Netlify o Vercel). No requiere instalación ni compilación.

## Dónde editar los datos

Todo el contenido está en el objeto `E360_DATA`, dentro de `index.html`:

- `courses` → cursos (textos, colores, brochures, `payment_links`, `async` para cursos asíncronos)
- `editions` → fechas de inicio y fin, horarios, sesiones y precios
- `memberships` → membresías y sus `payment_links`
- `config` → WhatsApp, correo, `countrySchedules`, `aulaUrl`, enlaces legales, etc.

## Formularios

Los formularios envían los datos a grupoestrategas360@gmail.com mediante FormSubmit.
La primera vez que se envíe un formulario desde la web publicada, llegará un correo de FormSubmit: hay que pulsar **"Activate Form"**. Los formularios no funcionan abriendo el archivo en la computadora (`file://`), solo con la web publicada.

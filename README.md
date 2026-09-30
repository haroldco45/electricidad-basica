# Electricidad básica

App (PWA) de Vibras Positivas HM para aprender electricidad: nueve módulos, once herramientas, evaluaciones con certificado y lectura en voz alta. Funciona sin internet después de la primera visita.

## Publicar en GitHub Pages

1. Cree un repositorio nuevo en GitHub (por ejemplo `electricidad-basica`).
2. Suba todos los archivos de esta carpeta a la raíz del repositorio: `index.html`, `manifest.webmanifest`, `sw.js` y los tres íconos.
3. En el repositorio, entre a **Settings > Pages**, escoja la rama `main` y la carpeta `/ (root)`, y guarde.
4. En uno o dos minutos la app queda en `https://SU-USUARIO.github.io/electricidad-basica/`.

## Instalar en el teléfono

- **Android (Chrome):** abra el enlace y toque el botón "Instalar la app en este teléfono" que aparece en la portada, o el menú ⋮ > Instalar app.
- **iPhone (Safari):** botón Compartir > Agregar a pantalla de inicio.

Después de abrirla una vez con internet, funciona sin señal.

## Actualizar

Cuando cambie `index.html`, cambie también la línea `const VERSION = 'eb-v1';` en `sw.js` (por ejemplo a `eb-v2`). Así los teléfonos descargan la versión nueva.

## Datos

El avance, los precios del presupuesto y los resultados de las evaluaciones se guardan solo en el teléfono de cada persona.

# DriveAwake — sitio web

Landing y política de privacidad de la app DriveAwake, publicadas con GitHub Pages.

| Archivo | Contenido |
|---|---|
| `index.html` | Landing en inglés (redirige a `es.html` en la primera visita si el navegador está en español) |
| `es.html` | Landing en español |
| `privacy.html` | Política de privacidad en inglés: **es la URL que se indica en Google Play** |
| `privacidad.html` | Política de privacidad en español |
| `styles.css` | Estilos comunes |
| `DriveAwake-Google-Play-*.png` | Icono y gráfico de funciones para la ficha de Google Play |

Son páginas estáticas, sin compilación. Para verlas en local basta abrir `index.html` en el navegador.

Al cambiar la política, actualizar la fecha en los dos idiomas y mantener iguales `docs/PRIVACIDAD.md` y `docs/PRIVACY.md` del repositorio de la app.

## Descarga del APK

El botón de descarga apunta a un archivo adjunto de un release de este mismo repositorio:
`releases/download/vX.Y.Z/DriveAwake.apk`. Mientras las versiones se publiquen como **pre-release** (versión de prueba), hay que actualizar a mano en `index.html` y `es.html` el número de versión, el enlace y la huella SHA-256: la URL fija `releases/latest/download/DriveAwake.apk` solo funciona con releases normales.

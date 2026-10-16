# TH3 BNB en Netlify

Esta carpeta contiene una copia lista para publicar del sitio estático.

## Publicar en GitHub y Netlify

1. Sube el contenido de esta carpeta a un repositorio de GitHub, conservando las carpetas `assets`, `css` y `js`.
2. En Netlify, importa ese repositorio desde GitHub.
3. Deja vacío el comando de compilación y usa `.` como directorio de publicación.
4. Despliega el sitio.

Si subes el proyecto completo en vez de esta carpeta como raíz del repositorio, configura `netlify-deploy` como directorio base y `.` como directorio de publicación.
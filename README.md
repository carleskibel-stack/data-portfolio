# Portafolio de datos — versión inicial

Sitio estático construido solo con HTML y CSS. No necesita Node.js, React ni un proceso de compilación.

## Archivos

- `index.html`: contenido de la página.
- `styles.css`: diseño y adaptación para celulares.
- `README.md`: estas instrucciones.

## Cambios mínimos antes de publicar

Abre `index.html` y reemplaza:

1. `TU_USUARIO/TU_REPOSITORIO` por la dirección real del repositorio del proyecto.
2. `#` del botón **Abrir dashboard** por el enlace público del reporte.
3. `tu-correo@ejemplo.com` por tu correo profesional.
4. `TU_USUARIO` del enlace de LinkedIn.
5. Los textos del problema, solución y resultados con los datos exactos de tu proyecto.

## Publicación en Azure Static Web Apps

Para un sitio sin framework:

- Build preset: `Custom`
- App location: `/`
- API location: dejar vacío
- Output location: vacío
- Skip app build: true
- Branch: `main`
- Hosting plan: `Free`

Azure creará un flujo de GitHub Actions dentro de `.github/workflows/`.
Cada cambio confirmado en la rama `main` volverá a desplegar el sitio.

## Capturas

La primera versión usa cuadros de marcador para evitar bloquear la publicación.
Después puedes crear una carpeta `images`, subir tus capturas y reemplazar los marcadores por etiquetas `<img>`.

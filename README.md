# Planes y precios

Sitio estático para mostrar precios del programa de ayuda personalizada para atraer pacientes.

## GitHub Pages

El deploy se publica con GitHub Actions usando `.github/workflows/pages.yml`.

En GitHub, activa Pages desde:

`Settings` → `Pages` → `Build and deployment` → `Source: GitHub Actions`

Este paso es necesario una sola vez. Si no está activado, el workflow falla con:

`Get Pages site failed. Please verify that the repository has Pages enabled`

Después de activarlo, vuelve a correr el workflow o haz otro push a `main`.

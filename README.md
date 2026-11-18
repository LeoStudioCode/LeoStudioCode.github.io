# Portafolio de Leonardo Madrigal

Sitio en línea: [https://leostudiocode.github.io](https://leostudiocode.github.io)

Mis proyectos como desarrollador full-stack: los sistemas que hice en Grupo Sánchez (Monitor de Ventas, Reportes Contables y HelpCAR), mis proyectos personales y el servidor donde corren varias de mis aplicaciones.

Todas las capturas usan datos de prueba; ninguna muestra información real.

## Cómo está hecho

- **Astro**: sitio estático, sin framework de interfaz.
- Imágenes optimizadas a WebP en varios tamaños; al abrir una captura se carga a tamaño completo.
- Visor de capturas y animación de entrada con JavaScript propio y corto. Si el JavaScript falla, la página se ve completa igual.
- Se publica solo con GitHub Actions en cada cambio a `main`.

## Correrlo en local

```sh
npm install
npm run dev      # http://localhost:4321
npm run build    # genera dist/
```

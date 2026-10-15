# Active Solar

Sitio conceptual de energía solar desarrollado con React y Vite. El diseño reproduce la composición de la imagen de referencia: paneles al atardecer, tipografía sans serif, secciones marfil, soluciones con pestañas y proceso compacto. Conserva la sección «Del sol a tu día a día», con GSAP ScrollTrigger, y el desplazamiento suave con Lenis. Incluye navegación móvil y un configurador de consulta con descarga de resumen.

## Uso

Requiere Node.js 22.12 o superior.

```sh
npm install
npm run dev
```

Para generar la versión de producción:

```sh
npm run build
npm run preview
```

El resultado está en `dist/` y puede desplegarse en cualquier hosting estático. Se respeta `prefers-reduced-motion`. Las imágenes están incluidas en `public/images`; las fuentes se sirven localmente si están disponibles en `public/fonts`.

## Contenido y contacto

Esta es una propuesta visual, con fotografías ilustrativas; no representa instalaciones o clientes verificados de Active Solar. No se incluyeron cifras de ahorro ni promesas de rendimiento. La consulta genera un resumen local descargable, sin enviar ni almacenar datos en un servidor. Para recepción real de consultas, conectar el formulario a un canal verificado de la marca.

## Recursos visuales

- Imágenes de portada, hogar e instalación: imágenes conceptuales generadas para el sitio. Fotografías de empresa y campo: Unsplash (`photo-1509391366360-2e959784a276`, `photo-1500382017468-9049fed747ef`).
- Tipografías: DM Sans y Manrope, Google Fonts (SIL Open Font License).
- Panel solar: composición CSS original.
- Referencias de motion: React Bits, Skiper UI y Animmaster Lib. Implementación propia, sin componentes premium copiados.

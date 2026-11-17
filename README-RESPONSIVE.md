# Cambios responsive añadidos

- Nuevo `blocks/responsive.css`, importado al final de `pages/index.css`.
- Elimina en móviles el mínimo de 1100px del contenedor.
- Adapta cabecera, navegación, imagen, sección de videos, formulario y footer para tablet y móvil.
- Conserva el CSS original y el diseño de escritorio.

## Probar

1. Abre `index.html` con Live Server en VS Code.
2. Abre Chrome/Edge DevTools (F12), activa el icono de dispositivo y comprueba 320, 375, 390, 768, 1024 y 1440 px.
3. Comprueba que no haya scroll horizontal, que los videos se visualicen y que la navegación funcione.
4. Este formulario es solo HTML: sin backend no registra reservas.

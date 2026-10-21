# TODO

## Páginas originales conservadas
- [x] Reproducir la página de inicio de servirpro.co como una página distinta de las páginas de producto, conservando su diseño y recursos originales.
- [x] Reproducir https://www.servirpro.co/seguros-vehiculo conservando sus textos, imágenes, colores, contenido, estructura y comportamiento visible.
- [x] Reproducir https://www.servirpro.co/compra-cartera-vehiculos conservando sus textos, imágenes, colores, contenido, estructura y comportamiento visible.
- [x] Mantener las páginas responsive y conservar los elementos interactivos visibles de las originales, incluidos formularios, botones, menús y secciones desplegables.
- [x] Usar los recursos visuales originales —textos, imágenes e iconos— y organizar los estilos para facilitar cambios posteriores de color.
- [x] Agregar únicamente lo indispensable para que funcionen las páginas solicitadas; no incorporar rutas ni herramientas innecesarias.

## Alcance y navegación
- [x] Dejar accesibles únicamente estas páginas: Home (`/`), Compra de cartera (`/compra-cartera-vehiculos`), Seguros para autos (`/seguros-vehiculo`) y Créditos vehiculares (`/creditos-vehiculares`). El manifiesto declara solo estas cuatro rutas.
- [x] Mantener la navegación y las tarjetas de servicios entre esas cuatro páginas; quitar enlaces del catálogo a otros servicios y conservar funcionales los enlaces externos legales, de contacto, redes sociales y ubicación.

## Página de créditos vehiculares
- [x] Agregar una página llamada “Créditos vehiculares” en `/creditos-vehiculares` con la misma estructura visual, paleta, encabezado, navegación y footer que las páginas existentes.
- [x] Presentar información y una llamada a asesoría sobre créditos vehiculares, sin inventar tasas, condiciones financieras ni promesas de aprobación.
- [x] Quitar el fondo del carro y el bloque que parece una alerta; reemplazarlo por una propuesta visual creativa, bonita y llamativa, propia de créditos vehiculares, que invite al cliente a solicitar el crédito.

## Compra de cartera de vehículos
- [x] Reemplazar en `/compra-cartera-vehiculos` la sección con fondo de auto y apariencia de alerta por una invitación visual similar a la de Créditos vehiculares, manteniendo la paleta LeCreo, usando un mensaje específico de compra de cartera y un CTA que conecte con la asesoría existente.

## Actualización de marca y estilo solicitada
- [x] Quitar el logo actual del sitio web y reemplazarlo por el logo adjunto de LeCreo en los espacios de marca visibles de las cuatro páginas.
- [x] Cambiar la paleta del sitio usando `#f4eadb`, `#c2593c`, `#8a8178`, `#262626`, blanco y negro, combinándolos para que el resultado se vea armónico; recolorear los gráficos de marca donde el azul heredado siga siendo protagonista.
- [x] Usar Plus Jakarta Sans para los títulos, botones y números.
- [x] Corregir el título gráfico heredado que identificaba compra de cartera en Créditos vehiculares, manteniendo la estructura y el contenido nuevos.

## Transición de color al hacer scroll
- [x] Hacer menos brusco y más armónico el cambio de color que ocurre al hacer scroll, manteniendo los colores que la usuaria indicó; suavizar la salida de los heroes y los bloques oscuros en escritorio y móvil.

## Despliegue en Vercel
- [x] Al pulsar “Visitar”, mostrar la página renderizada en vez del código para el Home, seguros de vehículo y compra de cartera; el usuario confirmó que quedó bien.

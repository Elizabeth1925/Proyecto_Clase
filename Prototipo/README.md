# Reto de transformación: Tienda Aula

**Pregunta guía:** ¿Cómo convertirían este diseño en una interfaz responsive sin perder sus principios HCI?

## Abrir las versiones

- `antes/index.html`: diseño de escritorio con ancho fijo y controles pequeños.
- `despues/index.html`: misma tienda, adaptada mediante Mobile First, Grid, media queries, tamaños táctiles y foco visible.


## Funciones en ambas versiones

Catálogo de seis productos, búsqueda por nombre, filtros por categoría, añadir al carrito, cambiar cantidades, total calculado y compra simulada con nombre. No hay pagos, servidor ni persistencia.

## Cambios explicados en el código

| Marca | Qué se cambió | Principio relacionado |
|---|---|---|
| ANTES 01 / CAMBIO 01 | Se eliminó el ancho fijo de la página | Adaptabilidad |
| CAMBIO 02 | Enlace para saltar contenido y foco visible | Accesibilidad |
| CAMBIO 03 | Filtros con área táctil de al menos 44 px | Ley de Fitts |
| CAMBIO 04 | Catálogo de una columna por defecto | Mobile First |
| CAMBIO 05 | Retroalimentación visible | Visibilidad del estado del sistema |
| CAMBIO 06 | Dos columnas desde 700 px | Media queries |
| CAMBIO 07 | Tres columnas desde 1050 px | Responsive |
| CAMBIO 08 | Se conservan funciones existentes | Consistencia funcional |


## Mejoras UI/UX

- **Nielsen 1 — Visibilidad del estado:** contador de resultados, contador del carrito y mensajes de confirmación.
- **Nielsen 2 — Correspondencia con el mundo real:** etiquetas comprensibles, precios en USD y lenguaje cotidiano.
- **Nielsen 3 — Control y libertad:** limpiar búsqueda, retirar artículos, cambiar cantidades, cerrar carrito.
- **Nielsen 4 — Consistencia:** sistema de diseño, botones y tarjetas uniformes.
- **Nielsen 5 — Prevención de errores:** deshabilitar finalizar cuando el carrito está vacío y validar nombre.
- **Nielsen 6 — Reconocimiento mejor que recuerdo:** categorías visibles y acciones explícitas.
- **Nielsen 7 — Flexibilidad y eficiencia:** búsqueda inmediata y filtros combinables.
- **Nielsen 8 — Diseño estético y minimalista:** jerarquía visual, espaciado y contenido prioritario.
- **Nielsen 9 — Reconocer y recuperarse de errores:** mensaje de búsqueda sin resultados y validación cercana al campo.
- **Nielsen 10 — Ayuda y documentación:** indicaciones contextuales y aclaración de compra simulada.
- **Ley de Fitts:** botones de al menos 44 px de alto, separación entre controles.
- **Ley de Hick:** categorías simples y pocas decisiones por pantalla.
- **Gestalt (proximidad):** precio, descripción y botón agrupados en cada tarjeta.
- **Mobile First:** 1 columna base, 2 desde 650 px y 3 desde 1000 px.
- **Accesibilidad:** HTML semántico, etiquetas, foco visible, enlace de salto, diálogo nativo y soporte para movimiento reducido.



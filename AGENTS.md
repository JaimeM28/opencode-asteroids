# Asteroids

- Abre `index.html` directamente en el navegador para ejecutar el juego; no requiere instalación ni compilación. No hay pruebas, lint ni scripts configurados: verifica los cambios jugando en el navegador.
- `index.html` define el canvas de 800×600 y carga `game.js` como script clásico. Mantén sus dimensiones sincronizadas con `W` y `H` en `game.js`.
- `game.js` contiene estado, entrada, entidades y renderizado. `initGame()` inicia la partida y `requestAnimationFrame` ejecuta `update(dt)` y `draw()`; `dt` está en segundos y limitado a 0,05.
- El movimiento usa envolvimiento de bordes, pero las colisiones usan distancia euclídea directa (`dist`), sin envolver. Tenlo en cuenta al modificar física o colisiones.
- El README menciona power-ups y estrellas fugaces que no aparecen en la implementación actual; usa el código como fuente de verdad.

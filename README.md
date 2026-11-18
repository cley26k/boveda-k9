# Bóveda K-9 · Feria de Matemáticas

Caja fuerte 3D interactiva para la actividad de la feria. Los equipos resuelven tres estaciones y cada respuesta correcta abre una cerradura. Al abrirse la bóveda aparece una carta que los felicita y les recuerda reclamar su premio.

**Jugar:** https://cley26k.github.io/boveda-k9/

## Cómo funciona

1. **Estación 1:** escriben la respuesta y tocan ✓.
2. **Estación 2:** escriben el número que está detrás de su papelito (1 al 5) y luego su respuesta.
3. **Estación 3:** escriben la respuesta. La bóveda se abre y sale la carta.

Las respuestas incorrectas se pueden reintentar sin bloqueo. El progreso se guarda en cada teléfono, así que recargar la página no lo borra. El botón **Reiniciar caja** (al pie, se toca dos veces) deja el teléfono listo para el siguiente equipo.

## Cambiar las respuestas

Están al inicio del `<script>` en `index.html`:

```js
const EST1 = 4, EST3 = 2;
const EST2 = {1:20, 2:12, 3:8, 4:30, 5:4};   // número de papelito → respuesta de la estación 2
```

Todo es un solo archivo HTML, sin dependencias aparte de Google Fonts.

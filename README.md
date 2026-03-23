# Evidencia: Personalización del Clásico Pacman

Este proyecto consiste en la modificación y mejora del código base del juego Pacman, originalmente desarrollado por **Grant Jenks**. El objetivo es aplicar buenas prácticas de programación, control de versiones con Git y personalización de mecánicas de juego.

## Camibos Realizados

Se realizaron tres modificaciones principales siguiendo el flujo de trabajo de ramas en Git:

### 1. Modificación del Tablero
- **Cambio:** Se editó la matriz `tiles` para alterar los pasillos y muros del mapa original.
- **Objetivo:** Crear una experiencia de navegación distinta y añadir nuevos retos en el movimiento del personaje.

### 2. Personalización del Alimento
- **Cambio:** Se modificó la función `world()` para cambiar el color y el tamaño de los puntos (alimento) que Pacman debe recolectar.
- **Objetivo:** Mejorar la estética visual y el contraste del entorno de juego.

### 3. Ajuste de Velocidad de los Fantasmas
- **Cambio:** Se redujo el intervalo de tiempo en la función `ontimer()` dentro del método `move()`.
- **Objetivo:** Incrementar la dificultad del juego haciendo que los enemigos se desplacen de manera más ágil.


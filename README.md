# Solemne-II_Bauhaus-Interactivo
Nombre del proyecto:
**Bauhaus Interactivo**

Autor/a:
[Benjamin Rocco]

Descripción objetiva

Este proyecto es una composición visual generativa creada en p5.js que produce un sistema de patrones geométricos en una grilla.

En pantalla se observa una estructura de filas y columnas donde se generan formas (círculos y rectángulos) en tres variaciones de color.

¿Qué se ve en pantalla?

- Una grilla de elementos repetidos.
- Figuras geométricas (círculos y rectángulos).
- Tres combinaciones de color distintas.
- Cambios visuales en tiempo real.

Elementos visuales

- Círculos
- Rectángulos
- **Tres paletas cromáticas:**
(1) Azul, rojo, amarillo.
(2) Amarillo, rojo, azul.
(3) Rojo, amarillo, azul.
- Fondo neutro

**Inputs**
- Movimiento del mouse (mouseX)
- Presión del mouse (mouseIsPressed)

**Outputs**
- Cambio de tamaño de las figuras según posición del mouse
- Cambio entre círculos y rectángulos al presionar el mouse
- Generación aleatoria de patrones de color
- Variación visual constante del sistema

**Idea central del proyecto**

El proyecto explora la idea de sistema visual inestable dentro de una estructura fija, donde el orden de la grilla contrasta con la aleatoriedad interna de las formas.

Principio de diseño explorado
- Repetición con variación
- Sistema basado en reglas
- Aleatoriedad controlada
- Interacción usuario-sistema

**Input / Output y sistema**
- **Inputs**
- mouseX: controla el tamaño de las figuras mediante map()
- mouseIsPressed: cambia la forma entre círculo y rectángulo
- random(): determina el patrón de color generado

-**Procesamiento**
- Se crea una grilla de posiciones (filas y columnas)
- En cada celda se genera un valor aleatorio (random(3))
- Según ese valor se selecciona un patrón de color
- El sistema evalúa si el mouse está presionado
- El tamaño de las figuras se ajusta según la posición del mouse
- Se dibujan formas geométricas en capas

- **Outputs**
- Composición visual generativa
- Variación de patrones en tiempo real
- Cambio de formas según interacción
- Movimiento visual dependiente del usuario

**Explicación del sistema de interactividad**

El sistema responde directamente a la acción del usuario:

- Movimiento horizontal del mouse → cambia escala de las figuras
- Click del mouse → alterna entre formas geométricas
- Aleatoriedad → genera variaciones de color en cada celda

Esto crea un sistema donde el usuario actúa como “coautor” de la imagen.

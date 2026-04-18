# Física Computacional - 2º Grado en Física (DTIE)

Este repositorio contiene las prácticas y resoluciones numéricas de problemas físicos desarrolladas durante la asignatura de **Física Computacional**, parte de la introducción al Laboratorio de física. El objetivo principal es emplear algoritmos y la potencia de cálculo de Python para resolver ecuaciones que describen el comportamiento de la naturaleza, especialmente aquellas que carecen de solución analítica sencilla.

## Contenido del Proyecto

El laboratorio se centra en la integración numérica de ecuaciones diferenciales ordinarias (EDOs) aplicadas a sistemas mecánicos clásicos.

### 1. Oscilador Armónico Simple
Estudio del sistema ideal donde una masa está sujeta a una fuerza restauradora lineal ($F = -kx$).
* **Métodos:** Implementación de algoritmos de integración (Euler, Euler-Cromer o Runge-Kutta).
* **Análisis:** Conservación de la energía mecánica y estudio del espacio de fases.

### 2. Oscilador Anarmónico
Extensión del modelo anterior introduciendo términos no lineales en el potencial (por ejemplo, proporcionales a $x^4$).
* **Diferencias:** Se observa cómo el periodo de oscilación depende de la amplitud, a diferencia del caso armónico.
* **Visualización:** Comparativa de trayectorias y análisis espectral básico.

### 3. Movimiento Planetario (Problema de los Dos Cuerpos)
Simulación de órbitas bajo la influencia de la gravedad Newtoniana.
* **Leyes de Kepler:** Verificación numérica de la segunda ley (conservación del momento angular) y la tercera ley.
* **Simulación:** Modelado de órbitas elípticas y circulares ajustando las condiciones iniciales de velocidad y posición.

Este proyecto forma parte de las prácticas del Doble Grado en Matemáticas y Física.
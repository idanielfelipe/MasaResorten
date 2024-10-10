
# Simulación del Sistema Masa-Resorte

## Descripción
Este proyecto simula un sistema físico de masas conectadas por resortes utilizando **Python** y **Programación Orientada a Objetos (POO)**. El objetivo del programa es mostrar cómo se desplazan las masas conectadas por resortes a lo largo del tiempo bajo ciertas condiciones iniciales. La simulación genera gráficos del desplazamiento de cada masa y una animación del movimiento del sistema completo.

### ¿Qué hace este programa?
El programa permite al usuario definir el número de masas y los valores de cada constante de resorte y de cada masa. Luego, se ejecuta la simulación, en la que el sistema calcula cómo se mueve cada masa con el paso del tiempo, basándose en las fuerzas restauradoras de los resortes. 

### Funciones Principales
1. **Cálculo Numérico**: Usa un método numérico (Euler) para calcular la posición y velocidad de cada masa a lo largo del tiempo.
2. **Gráficas**: Genera gráficos que muestran el desplazamiento de cada masa.
3. **Animación**: Crea un archivo GIF que muestra el movimiento de las masas a lo largo del tiempo.

## Requisitos
Para ejecutar este programa, necesitas tener instalados:
- **Python 3.x**
- **Matplotlib** para gráficos y animación.

A continuación, el programa te pedirá que ingreses ciertos parámetros:

- **Número de masas**: La cantidad de masas en el sistema. Este valor debe ser un número entero mayor a 1.
- **Constantes de los resortes**: Para cada resorte, ingresa su constante de resorte (positivo). Si tienes `n` masas, habrá `n + 1` constantes.
- **Valores de las masas**: Ingresa el valor de cada masa. Cada masa debe ser un número positivo.
- **Condiciones iniciales**:
  - **Velocidades iniciales**: La velocidad inicial de cada masa.
  - **Desplazamientos iniciales**: El desplazamiento inicial de cada masa con respecto a su posición de equilibrio.

## Ejemplo de entrada
Para una simulación con 3 masas, puedes ingresar los siguientes valores:

- **Ingrese el número de masas (n):** 3
- **Ingrese el valor de k1 (positivo):** 1
- **Ingrese el valor de k2 (positivo):** 0.5
- **Ingrese el valor de k3 (positivo):** 1.5
- **Ingrese el valor de k4 (positivo):** 1
- **Ingrese el valor de m1 (positivo):** 1
- **Ingrese el valor de m2 (positivo):** 2
- **Ingrese el valor de m3 (positivo):** 1
- **Ingrese la velocidad inicial v1(0):** 0
- **Ingrese la velocidad inicial v2(0):** 0
- **Ingrese la velocidad inicial v3(0):** 0
- **Ingrese el desplazamiento inicial x1(0):** 1
- **Ingrese el desplazamiento inicial x2(0):** -0.5
- **Ingrese el desplazamiento inicial x3(0):** 0.5

### Resultados
El programa generará:

- **Gráficas** que muestran el desplazamiento de cada masa en función del tiempo.
- Una **animación en GIF** llamada `grafica_dinamica.gif` que muestra el movimiento de las masas a lo largo del tiempo. Puedes encontrar este archivo en el mismo directorio donde se encuentra el programa.







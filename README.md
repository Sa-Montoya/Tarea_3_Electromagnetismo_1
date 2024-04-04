# Tarea_3_Electromagnetismo_1
En este repositorio se encuentra el código de dos métodos para resolver la ecuación de Laplace con ciertas condiciones iniciales.
En primer lugar se muestran las condiciones iniciales dadas, las cuales se pueden utilizar para realizar el test de cómo se ve el potencial en el espacio 2D. Aquí se pueden cambiar los valores de N, M y v0.

Las primeras 2 gráficas muestran el potencial inicial, en donde todos los puntos son aleatorios a excepción de las condiciones iniciales impuestas por el problema.
Posteriormente, se muestran dos formas diferentes para realizar el método de relajación, en donde el primero compila más rápido y depende del potencial inicial, el cual está condicionado por las condiciones inciales. El problema de esta forma es que no se puede escoger el paso dx.
Después se define la función llamada potential, la cual resuelve la ecuación de laplace mediante el método de relajación y depende del potencial inicial, el número de iteraciones y el paso dx respectivamente. Este código cumple con las condiciones impuestas, pues se puede escoger el valor de N, M, v0 y el paso dx.

Tras definir las funciones del método de relajación, se muestran 4 gráficas, en donde las dos primeras muestran el potencial calculado con el primer código del método de relajación y las otras dos con el segundo código del método de relajación.

En la siguiente sección, se define la función 'teorica', la cual calcula el potencial en cada punto a partir de la expresión analítica encontrada con las condiciones iniciales. Después se presentan las gráficas que este método muestra.

En la última sección se calcula la diferencia entre el método de relajación y el método analítico y se realiza la gráfica de esta diferencia en función de x y y. Se puede observar que existe una diferencia únicamente en las esquinas de la malla.


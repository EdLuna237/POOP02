P02 - 
En Java, los tipos de datos primitivos (como int, double, char, boolean) permiten almacenar valores básicos. A partir de ellos se construyen expresiones y se implementan estructuras que controlan la ejecución del programa.
Algunos conceptos aplicados fueron:

Declaración e inicialización de variables: permiten almacenar valores que se usan en cálculos o condiciones.

Constantes: valores fijos que no cambian durante la ejecución del programa (aunque en este caso no se usaron explícitamente, se podrían haber definido con final).

Estructuras de control de flujo: Son instrucciones que permiten decidir y repetir acciones:

if, else if, else

switch
 
ciclos: while 

do-while

for

For – each

Métodos: bloques de código que realizan una tarea específica, como el método menor(int a, int b) que compara dos valores.

Arreglos: estructuras que permiten almacenar múltiples elementos bajo un mismo nombre.

Notas sobre el desarrollo de la práctica
•	Se comenzó con un programa sencillo que imprime mensajes en consola.
•	Se implementó una comparación entre dos enteros (a y b) usando la estructura condicional if-else.
•	Se creó un método externo (menor) para ejemplificar cómo encapsular lógica en funciones.
•	Se aplicó la instrucción switch para imprimir días de la semana según el valor de una variable.
•	Se trabajaron diferentes tipos de ciclos (while, do-while, for, for-each) para recorrer números y un arreglo.
•	Finalmente, se realizó una pequeña actividad de práctica simulando la validación de edad para ingresar a un lugar.

Estructura del archivo
-	El programa se encuentra dentro del paquete POOP2 y consta de:

-	Clase principal POOP2: contiene el método main, punto de entrada del programa.

-	Método menor(int a, int b): retorna true si a es menor que b.

-	Uso de instrucciones de salida (System.out.println) para mostrar resultados.

-	Declaración de variables locales (a, b, n, dia, edad, arreglo).

-	Bloques de control de flujo (if-else, switch, ciclos).


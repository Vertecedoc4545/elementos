# las partes del tablero a operar de las maquinas CNC



1. **Cycle_Start**

   Se utiliza para la ejecución de un programa seleccionado. Se utiliza para iniciar la ejecución de bloques **NC** en el buffer **MDI**

2. **Feed_Hold**
   detiene los movimientos en los ejes **xyz** inmediatamente a permitirá que se produzcan algunos movimientos debido que la linea g-cut actual decido al impulso, desaceleran todos los motores suavemente 
   
3. **Zero_Return**
    Se utiliza para configurar la mesa de trabajo y el carro superior de una maquina **CNC** en sus posiciones iniciales  (0,0,0). Esta pocicion inicial es donde siempre comienza el programa y debe establescerce con cada ciclo del programa 

4. **JOG**

​      Mueve los ejes al avance colocado en el **OVERRIDE**

5. **Handle**

   Se utiliza para reconocer, ejecutar o resolver el programa *(Es la accion del programa)*

6. **MID**
   La entrada manual de datos es una manera manual de ardenar mavimientos **CNC** automaticos sin emplear un programa 

7. **Auto**
   Es una fuente programable que selecciona un programa para ejecutar

8. **Edit**
   Es la edicion de un programa **Auto**

9. **Tape**

   Es repetir el ciclo 




# mora-tamayo-post1-u3

Practicas de bajo nivel sobre arquitectura 8086 utilizando la herramienta DEBUG en entorno DOSBox. El repositorio documenta el control de registros, gestion de memoria y ensamblado de instrucciones basicas.

REPORTE DE LABORATORIO DEBUG - DOSBOX



CHECKPOINT 1: GESTION DE REGISTROS (CP1\_registros.png)



Descripcion: Inspeccion y modificacion de los registros internos del procesador 8086.



Comandos utilizados: R, R AX.



Observaciones: Se visualizo el estado inicial de los registros y se procedio a cambiar el valor del registro acumulador AX a 1234 hexadecimal, confirmando el cambio con una segunda lectura del estado del sistema.



CHECKPOINT 2: MANIPULACION DE MEMORIA (CP2\_volcado\_memoria.png)



Descripcion: Llenado de bloques de memoria con patrones de datos y visualizacion de segmentos especificos.



Comandos utilizados: F 200 L40 AB CD EF, D 200 L40, D 0 L20.



Observaciones: El comando F permitio rellenar un bloque de 64 bytes con la secuencia repetitiva AB CD EF. Mediante el comando D se verifico el volcado de memoria, observando las direcciones en la izquierda, los valores hexadecimales al centro y los caracteres ASCII a la derecha.



CHECKPOINT 3: ENSAMBLADO Y DESENSAMBLADO (CP3\_ensamblado\_desensamblado.png)



Descripcion: Creacion de un programa basico en lenguaje ensamblador y analisis de su representacion en codigo maquina.



Comandos utilizados: A 100, U 100 109.



Observaciones: Se ensamblaron instrucciones de transferencia (MOV AX, 0005) y aritmeticas (ADD AX, BX) seguidas de una interrupcion de finalizacion (INT 20). El comando U permitio desensamblar el codigo para observar como los mnemonicos se traducen a codigos de operacion (opcodes) especificos almacenados en la memoria.


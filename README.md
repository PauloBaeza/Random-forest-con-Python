Proyecto práctico: árboles de decisión

Data comes frome: Car Evaluation Data Set

En este proyecto, exploraremos el conjunto de datos "Car Evaluation Data Set" y utilizaremos árboles de decisión para construir un modelo de clasificación capaz de predecir la calidad de compra de un automóvil.

Conociendo nuestro dataset El conjunto de datos "Car Evaluation Data Set" es un conjunto de datos público que consta de 1728 instancias etiquetadas con la clase de calidad de compra del automóvil. Cada instancia tiene 6 atributos discretos: precio, mantenimiento, número de puertas, capacidad de personas, tamaño del maletero y seguridad.

Los atributos son definidos de la siguiente manera:

price (Precio): representa el costo del automóvil. Los valores posibles son 'vhigh' (muy caro), 'high' (caro), 'med' (medio) y 'low' (económico).

maint (Mantenimiento): representa el costo de mantenimiento del automóvil. Los valores posibles son 'vhigh' (muy caro), 'high' (caro), 'med' (medio) y 'low' (económico).

doors (Número de puertas): representa la cantidad de puertas que tiene el automóvil. Los valores posibles son '2', '3', '4' y '5more' (5 o más).

persons (Capacidad de personas): representa la capacidad de personas que puede transportar el automóvil. Los valores posibles son '2', '4', 'more' (más de 4).

lug_boot (Tamaño del maletero): representa el tamaño del maletero del automóvil. Los valores posibles son 'small' (pequeño), 'med' (medio) y 'big' (grande).

safety (Seguridad): representa la calidad de seguridad del automóvil. Los valores posibles son 'low' (baja), 'med' (media) y 'high' (alta).

Class (Evaluación de la calidad de los automóviles):. Esta variable objetivo tiene cuatro posibles valores de clasificación: "unacc" (inaceptable), "acc" (aceptable), "good" (bueno) y "vgood" (muy bueno)

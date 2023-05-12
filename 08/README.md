# Casos de Pruebas

## ¿Cómo registrar un caso de prueba?

* Datos a incorporar 
* Forma de Escritura 
* Ejemplo Práctico

⏯️ [Casos de Pruebas](https://www.youtube.com/watch?v=Kh8iCyj9Smo)

## Técnicas TDD y BDD

Modelos de Testing y creación de casos de prueba.

Aunque TDD no fue creado para testing, es un sistema muy utilizada en este ámbito.

`TDD` es una metodología de desarrollo cuyo objetivo es crear primero las pruebas y luego escribir el software y luego probar si el software está funcionando de acuerdo a esas pruebas "pre-planeadas".

`BDD` (Behavior Driven Development), también es una estrategia de desarrollo dirigido por comportamiento, que ha evolucionado desde TDD (Test Driven Development), y tampoco nació como una técnica de testing.

Tanto en TDD como en BDD, las pruebas se deben definir antes del desarrollo, aunque en BDD, las pruebas se centran en el usuario y el comportamiento del sistema como un conjunto, a diferencia del TDD que se centra en funcionalidades específicas del software.

**¿Qué enfoque de testing debo aplicar? ¿TDD o BDD?**

Aunque TDD o BDD parecen muy similares, la principal diferencia entre ambas está en el alcance. TDD es una práctica de desarrollo, enfocada en cómo revisar el sistema y **cómo debería funcionar**. Mientras que BDD es un enfoque de equipo que hace hincapié en **porqué** debes revisar ese código y porqué se debería comportar de una forma u otra.

En TDD el tester escribe los tests mientras que en BDD el usuario final, junto al resto del equipo multidisciplinario, escriben los tests.

## Tips para crear buenos casos de pruebas

![tips-casos-de-prueba](/images/tips-casos-de-prueba.jpg)

## El Método de Clases de Equivalencia (CE) en test de Caja Negra

El Método de la Clase de Equivalencia es el conjunto de datos que puede asignarse a un componente a testear.

* Consiste en dividir los valores de entrada en clases de datos para derivar casos de prueba.
* Se asume que el resultado de una prueba con un valor representativo de cada CE equivale a realizar la misma prueba con cualquier otro valor de la CE.
* Pasos para diseñar casos de prueba:
    1. Identificar clases de equivalencia.
    2. Identificar los casos de prueba. Minimizando no casos de prueba, considerar tantas ondiciones como sea posible.
    3. Pasos:
        - Asignar a cada CE un representante único.
        - Definir casos de prueba que cubran tantas CE válidas como sea posible. Repetir hasta que todas las CE estén cubiertas.
        - Definir un caso de prueba para cubrir una única CE no válida. Repetir hasta que todas estén cubiertas.

![clases-de-equivalencia](/images/clases-de-equivalencia.png)

## Descripción en un caso de prueba

La descripción en el paso de prueba como parte fundamental del resultado de un buen testing.

📕 [Descripción casos de prueba](/documents/descripcion-casos-de-prueba.pdf)

## Pruebas Exploratorias

📕 [Pruebas Exploratorias](/documents/pruebas-exploratorias.pdf)

## Clase 3 en vivo. JAVA + JMeter performance - fuerza - stress en página web

En esta clase vemos como medir el rendimiento y la capacidad de respuesta de una página web. Instalación de JAVA + JMeter para hacer pruebas de performance - fuerza - stress en una página web.

⏯️ [Clase 3](https://www.youtube.com/watch?v=9UJKctfrrSM)

📁 [Archivo de la Prueba de Performance de una página web en JMeter](/documents/base-de-datos.jmx)

[km44.com.ar](http://km44.com.ar/)
[km44server.com.ar](https://km44server.com.ar/)
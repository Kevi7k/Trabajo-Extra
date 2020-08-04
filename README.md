# Práctica Extra
# Simulación con Ardiuno.
## *INTRODUCCIÓN*
Esta práctica trata de comprender el funcionamiento sobre un elemento electrónico que es muy importante en la actualidad, ya que este combina la electrónica con la programación y es muy utilizado en proyectos e inventos que hay actualmente, nos enfocaremos en una practica un poco sencilla , que consiste en hacer parpadear una LED dentro de un intervalo de tiempo y para realizar eso lo hacemos con el sofware de virtual breadboard , la programacion con IDE arduino, donde se lo realizará paso a paso.
## *OBJETIVOS:*

# Objetivo general
- Diseñar un circuito electrico que contenga como elemento principal el Ardiuno con simulaciones.

# Objetivos específico
- Comprender el procedimiento a realizar , cuando queremos que parpadee un LED
- Aprender sobre este nuevo elemento electrónico.

## *LISTA DE MATERIALES:*

| Cantidad | Material de Equipo |
| ------------- | ------------- |
| 1  | Arduino |
|  1 | Resistor de 1k  |
|  1 | LED    |
| 1  | Protoboard      |

## *MARCO TEÓRICO*
¿Que es Ardiuno?

El ardiuno se caracteriza por ser una plataforma electrónica de código libre, la cual está basada en hardware y software libre, flexible y fácil de utilizar para los creadores y desarrolladores.Esto permite crear todo tipo de microordenadores de una sola placa, en el cual se puede dar diferentes tipos de uso.
En otras palabras tambien se lo considera como un hardware libre , donde los dispositivos y diagramas son de acceso público para toda persona, entonces puede haber réplicas de los mismos.

Se puede decir que ardiuno ofrece las bases para que cualquier persona o empresa pueda crear sus propias placas, pero siempre van a partir de la misma base.

El software libre son los programas informáticos donde los códigos son accesibles para todas las personas y esto a su vez pueden modificarse, tambien ofrece la plataforma Arduino IDE (Entorno de Desarrollo Integrado), donde se realiza todo lo antes mencionado, que tenga que ver con la programación.


![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/arduino.jpg)

Fig 1. Arduino.


¿Como funciona?

Este elemento electrónico es una placa basada en un microcontrolador ATMEL, los micocontroladores son circuitos en los cuales se pueden indicar instrucciones , pero eso se lo hace con lenguaje de programación donde utilizamos el enterno Arduino IDE. Esas instrucciones son las que nos permiten crear programas que interactúen con los circuitos dentro de la placa.

El microcontrolador de Arduino posee lo que se llama una interfaz de entrada, que es una conexión en la que podemos conectar en la placa diferentes tipos de periféricos. La información de estos periféricos que conectes se trasladará al microcontrolador, el cual se encargará de procesar los datos que le lleguen a través de ellos.

También cuenta con una interfaz de salida, que es la que se encarga de llevar la información que se ha procesado en el Arduino a otros periféricos. Estos periféricos pueden ser pantallas o altavoces en los que reproducir los datos procesados, pero también pueden ser otras placas o controladores.

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/como%20funciona.jpg)

Fig 2. Funncionamiento del Arduino.

## *PROCEDIMIENTO*
1. Entrar al programa de Breadboard:

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/Paso%201.png)

2.Poner todos los materiales:

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/paso%202.png)

3.Armar el circuito:

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/Paso%203.png)

4.Dirigirse a la esquina superior derecha y añadir "NEW JAVA SOURCE FILE"

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/paso%204.png)

5.Añadir el Add New JAVA

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/paso%205.png)

6.Crear la nueva hoja para la programación.

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/paso%206.png)

7.Realizar el respectivo código para que la LED sea intermitente.

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/paso%207.png)

8.Comprobar si funciona.

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/Paso%208.png)

## *DIAGRAMA*

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/diagrama.png)

Fig 3-Circuito Simulado en Breadboard

## *EXPLICACIÓN DEL CIRCUITO*

En nuestro circuito podemos evidenciar, dos fuentes de voltaje, de 20 V y de 12 V, que serán las que suministren energía al sistema. También contaremos con 4 resistencias, de 1000, 2200, 820 y 470 ohmios. Conectados dichos elementos como podemos evidenciar en nuestros diagramas. Nuestro primer elemento será nuestra fuente de voltaje de 20 V, del polo positivo de nuestra fuente de voltaje, tendremos nuestra resistencia de 1000 ohmios, de la cual tendremos dos resistencias, es decir que nuestra corriente se dividirá en dos. Nuestra primera resistencia resultante es la de 2200 ohmios, la cual saldrá a los polos negativos de las fuentes. La otra resistencia resultante será nuestra resistencia de 820 ohmios, de la cual luego calcularemos la caída de tensión, que tomaremos como Va, y de dicha resistencia tendremos otra división de corriente, la primera es en nuestra resistencia de 470 ohmios, que terminara en los polos negativos de nuestras fuentes, la cual calcularemos el paso de corriente y lo llamaremos Ix. Y, por último, también nuestra resistencia de 820 ohmios estará conectado al polo positivo de nuestra segunda fuente de voltaje. Y los polos negativos de nuestras fuentes estarán conectados entre sí. 

Para nuestro teorema de superposición, podemos calcular los valores de Va e Ix, tomando dos casos distintos, el primer caso apagando nuestra segunda fuente y trabajando como si tuviéramos una sola fuente, y el segundo caso que será apagar nuestra primera fuente y trabajar como si solo tuviéramos una fuente. Al final, al tener nuestros resultados por separado, solo tendremos que sumar nuestros valores respectivos de Va e Ix y tendremos nuestros valores que estamos buscando.

## *CONCLUSIONES*

- A través de la comparación de los resultados obtenidos en la simulación y en los cálculos donde, al realizar la suma algebraica de cada una de las fuentes actuando por sí solas, se comprobó experimentalmente que en el circuito propuesto se cumple con el Teorema de Superposición.

- Frente a la mediciones obtenidas en el laboratorio se obtuvieron ciertos errores como se puede visualizar en la Tabla III, el valor del error relativo porcentual de Va cuando V2=0 y cuando V1=0 son 0,013% y 0,153% respectivamente, mientras que el error del Voltaje total en "a" es 0,73%, valores sumamente pequeños considerados aceptables.

- Respecto a la corriente Ix cuando V2=0 y v1=0, los errores obtenidos fueron de 0% y 0,078%. Y refiriéndonos a la corriente total Ix se obtuvo un error de 0,078%, sin embargo las mediciones obtenidas se aproximan mucho a los resultado que se calculó, por lo que consideramos a estos errores como insignificantes.

- El Teorema de Superposición nos ha resultado una técnica muy práctica de utilizar cuando tenemos varias fuentes de voltaje y corriente en un mismo circuito, ya que nos simplifica los cálculos al considerar las fuentes de voltaje como corto circuitos y las fuentes de corriente como circuitos abiertos.


## *RECOMENDACIONES*
- Se debe tomar en cuenta que cuando simulemos un circuito en el laboratorio virtual, tenemos que apagar la fuente de voltaje, más no asignarle el valor de "cero", ya que nuestros resultados pueden variar notablemente, lo que provocaría un error extremadamente grande.

- Al tener bien definido el concepto de superposición y los conceptos de las leyes más básicas, se nos facilitará realizar con mejor autonomía la práctica e identificar los errores de por medio que se pueden presentar.

- Es necesario verificar los valores que asignamos a las fuentes de voltaje como a resistencias, ya que se suele cometer errores con las unidades de medida, de igual forma que la conexión esté bien hecha para que las mediciones sean lo más exactas posibles.

- Para la obtención de medidas de corrientes y voltajes, debemos realizar bien la conexión de nuestro multímetro, es decir, ser estricto en cuanto a la conexión del positivo y negativo ya que si no lo colocamos bien, probablemente obtengamos resultados diferentes a los solicitados, que pueden afectar a cálculos secundarios.

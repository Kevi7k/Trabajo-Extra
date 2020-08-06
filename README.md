# Sensores y actuadores.
# Simulación con Ardiuno.
## *INTRODUCCIÓN*
Esta práctica trata de comprender el funcionamiento sobre un elemento electrónico que es muy importante en la actualidad, ya que este combina la electrónica con la programación y es muy utilizado en proyectos e inventos que hay actualmente, nos enfocaremos en una practica muy interesante que involucra a los sensores y actuadores , que en la actualidad son de mucha utilidad para el Campo laboral, entonces este practica la realizaremos con aplicaciones, es decir los sensores pueden medir magnitudes físicas  y los actuadores como un activador para poder controlar algun elemento mecánico como un motor.
## *OBJETIVOS:*

# Objetivo general
- Diseñar un circuito electrico que contenga un sensor y otro que tenga un actuador.

# Objetivos específico
- Comprender el procedimiento de como integrar estos elementos y su funcionamiento con Ardiuno
- Aprender sobre este nuevo elemento electrónico.

## *LISTA DE MATERIALES:*

| Cantidad | Material de Equipo |
| ------------- | ------------- |
| 1  | Arduino |
|  3 | Resistor de 220  |
|  3 | LED    |
| 1  | Protoboard      |
| 1  | Sensor ultrásonico| 
|1   | Piezo  |
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

*Sensores*

Los sensores son un dispositivos que pueden cuantificar las magnitudes físicas, entre esas pueden ser la temperatura, intesidad lumínica , presión etc...
En si , son capaces de detectarlas y de ahí transformarlas en  variables eléctronicas.


Los sensores se pueden clasificar en función de los datos de salida en:

Digitales

Analógicos

¿Que son?

Sensores digitales: Son los que dan como salida una señal codificada en forma de pulsos o en forma de palabra digital en cualquier tipo de sistema, codificación binaria,BCD, entre otros.

Sensores analógicos: Estos en cambio , dan como salida un  valor de tensión o corriente variable enforma continua dentro del campo de medida. Algunos rangos de salida son: 
de  0 a 10V, de -5 a 5V, de 4 a 20mA.

*Actuadores*

El actuador es un dispositivo que transforma cualquier energía mecánica en una activación de un proceso al fin de generar un efecto sobre un elemento extremo, por lo tanto este recibe una orden de un controlador , que ya sabemos en esta practica cual es, el arduino. Entonces a partir de ella genera la orden para activar un elemento que pueda controlarlo y un ejemplo de estos , son:

Electrónicos

Hidráulicos

Neumáticos

Eléctricos

Motores

Bombas

Los actuadores van conectados a las salidas de Arduino.


## *PROCEDIMIENTO*
*CON EL SENSOR*

1. Entrar al programa en linea de tinkercad y colocar todos los materiales que vamos a utilizar:

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/Paso%201.png)

2.Armar el circuito:

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/Paso%202.png)

3.Colocar el código respectivo, para su programación:

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/Paso%203.png)

4.Comprobar su funcionamiento

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/Paso%204.png)

*CON EL ACTUADOR*

1. Entrar al programa en linea de tinkercad y colocar los materiales a utilizar:

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/paso%201.1.png)

2. Armar el cirucito:

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/paso%202.1.png)

3. Colocar el códigco respectivo , para su programación:

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/paso%203.1.png)

4.Comprobar su funcionamiento

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/paso%204.1.png)



## *DIAGRAMA*
*CON EL SENSOR*

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/diagrama..png)

Fig 3-Circuito Simulado en tinkercad

*CON EL ACTUADOR*

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/diagrama%201.1.png)

Fig 4-Circuito Simulado en tinkercad


## *EXPLICACIÓN DEL CIRCUITO*



## *CONCLUSIONES*

- Al momento que la distancia ultrasónica era mas amplia con respecto al sensor, los lEDS empezaban a apagarse.

- Se pudo notar la gran importancia de este dispositivo electrónico que nos puede llegar a hacer muchos proyectos mas interesantes.

## *RECOMENDACIONES*
- Seguir paso a paso las indicaciones de la página web , para así realizar un buen trabajo.

- Poner en practica la teoría de clases para así relacionarlo con esta practica.

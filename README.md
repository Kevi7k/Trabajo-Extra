# Sensores y actuadores.
# Simulación con Ardiuno.
## *INTRODUCCIÓN*
Esta práctica trata de comprender el funcionamiento sobre un elemento electrónico que es muy importante en la actualidad, ya que este combina la electrónica con la programación y es muy utilizado en proyectos e inventos que hay actualmente, nos enfocaremos en una practica muy interesante que involucra a los sensores y actuadores , que en la actualidad son de mucha utilidad para el Campo laboral, entonces este practica la realizaremos con aplicaciones, es decir los sensores pueden medir magnitudes físicas  y los actuadores como un activador para poder controlar algun elemento mecánico como un motor.
## *OBJETIVOS:*

# Objetivo general
- Aprender a utilizar el sotfware de breadboard
- Diseñar un circuito electrico que contenga un actuador y un sensor.

# Objetivos específico
- Comprender el procedimiento de como integrar estos elementos y su funcionamiento con Ardiuno
- Aprender sobre este nuevo elemento electrónico.

## *LISTA DE MATERIALES:*
| Cantidad | Material de Equipo |
| ------------- | ------------- |
| 1  | Arduino |
|  2 | Resistor de 1k  |
| 1  | Protoboard      |
| 1  | Sensor de temperatura| 
|1   | Robot Wheel  |
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

**D. VIRTUAL BREADBOARD V4.46**

Virtual Breadboard (VBB) es un emulador de circuitos integrados de tablero, en el que es capaz de funcionar como un entorno de desarrollo para microcontroladores. La aplicación se utiliza para desarrollar los microcontroladores y emulando circuitos, uniendo esto con el campo de la programación, se pueden hacer muchos proyectos interesantes.

Es un programa para el desarrollo de circuitos digitales que se puede descargar en el siguiente link.

https://drive.google.com/drive/folders/1883yqItndbouUX2_VaTiddjpmhQ4HFZG?usp=sharing

o tambien como otra alternativa, dirigirse en la parte superior del proyecto, ir a la carpeta Virtual Breadbore, descargar todos las carpetas.

**Componentes**

El simulador tiene una gran cantidad de librerias que nos ayudaran para el diseño del circuito, de este depende si el circuito es uno simple o díficil, lo mejor de esto que cuenta con un programa dentro que nos ayuda para la programación, donde podemos colocar los códigos para realizar nuestros proyectos, en la cual las librerias tienen diversos componentes, como motores ,sensores y tambien utiliza memorias dentro de la RAM.

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/Interfaz.png)

BARRA DE MENU

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/Menu.png)

Estas son las opciones operativas principales, que sirve para guardar el proyecto, compilar e inicializar la simulación. 

PANTALLA DE DISEÑO

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/Para%20dise%C3%B1ar.png)

Prácticamnete es nuestro espacio de trabajo, aquí se va ha realizar todo el diseño, implementación y conexiones del circuito.

MÓDULO DE PROGRAMACIÓN

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/modulo%20de%20programacion.png)

Aquí es donde debemos colocar el código de programación respectivo a lo que vamos a realizar.

MENÚ DE COMPONENTES

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/Componentes.png)

Este es el núcleo de todo el sotfware ya que , aquí es donde se encuentran las principales partes de creación del circuito, como sus elementos que nos ayudaran a crear nuestro proyecto, a continuación en la siguiente imágen veremos mas elementos de estas componentes:

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/elementos%20de%20las%20componentes.png)

**Componentes a utilizar:**
- Ardiuno:

El ardiuno se caracteriza por ser una plataforma electrónica de código libre, la cual está basada en hardware y software libre, flexible y fácil de utilizar para los creadores y desarrolladores

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/Componente%20ardiuno.jpg)

- Resistor:

Este es un elemento básico, que nos ayudará a que no se nos "queme" un elemento electrónico dentro del circuito.

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/resistor.png)

- Protoboard:

Es la placa en la cual se realiza el circuito.

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/protoboard.jpg)

- Sensor de temperatura:

El LM35 es un circuito electrónico sensor que puede medir temperatura. Su salida es analógica, es decir, te proporciona un voltaje proporcional a la temperatura. El sensor tiene un rango desde −55°C a 150°C

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/LM35-en-protoboard.jpg)

- Robot Wheel:

Es un actuador que viene incluido un tipo motor alado de las ruedas y al elegir las ruedas para que este al programarlo, empiece a girar con sus respectivas ordenes dictadas en la programación.

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/Robot%20wheel.jpg)




## *PROCEDIMIENTO*

1. Descargar el Breadboard.

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/procedimiento%201.png)

2.Instalar:

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/procedimiento%202.png)

3.Iniciar un nuevo proyecto:

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/procedimiento%203.png)

4.Colocar los elementos a utilizar:

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/Procedimiento%204.png)

5.Armar el circuito:

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/procedimiento%205.png)

6. Colocar el códigco respectivo , para su programación:

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/procedimiento%206.png)

7.Comprobar su funcionamiento

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/procedimiento%207.png)



## *DIAGRAMA*

![alt text](https://github.com/Kevi7k/Trabajo-Extra/blob/master/im%C3%A1genes/Diagrama%20V..png)


## *EXPLICACIÓN DEL CIRCUITO*
A continuación el link para toda la explicación https://www.youtube.com/watch?v=ZX_884T8k64&t=18s
## *CONCLUSIONES*

- Se pudo notar la gran importancia de este dispositivo electrónico que nos puede llegar a hacer muchos proyectos mas interesantes.

- Al programar el sensor de temperatura , con el actuador, se puede evidenciar que al aumentar la temperatura aumenta la velocidad del actuador.

- Esta practica, va mas allá de lo aprendido en clase, por lo que es un trabajo extra muy interesante para querer aprender más.

## *RECOMENDACIONES*
- Seguir paso a paso las indicaciones de la página web , para así realizar un buen trabajo.

- Poner en practica la teoría de clases para así relacionarlo con esta practica.

## *BIBLIOGRAFÍA*

- Xataka, recuperado de https://www.xataka.com/basics/que-arduino-como-funciona-que-puedes-hacer-uno

- https://aprendiendoarduino.wordpress.com/2016/12/18/sensores-y-actuadores/

- https://hetpro-store.com/TUTORIALES/lm35/

# Práctica 8
# *AMPLIFICADOR OPERACIONAL*
## *PLANTEAMIENTO DEL PROBLEMA*

Tras el aprendizaje de una serie de leyes y teoremas respecto al análisis de circuitos eléctricos, ya es posible estudiar otros elementos un tanto más complejos, que son fundamentales dentro de la electrónica. Y con esto nos referimos al amplificador operacional, que es un componente de gran importancia en el diseño de circuitos con mayor nivel de compejidad, para esto se requiere analizar cómo es su comportamiento frente a otros componentes y cómo altera diferentes parámetros eléctricos como, siendo el voltaje el más afectado, seguido de la corriente.

## *OBJETIVOS*
# Objetivo general
- Diseñar una serie de circuitos que nos permitan determinar el comportamiento de un amplificador operacional dentro de este a través de las mediciones obtenidas a partir del osciloscopio para encontrar la relación entre la práctica y la teoría adquirida en clase.

# Objetivos específicos

- Verificar el principio de funcionamiento de un amplificador operacional.
- Analizar algunas aplicaciones básicas con el amplificador operacional.
- Familiarizarse con el uso de instrumentos de medida.

## *LISTA DE MATERIALES*


| Cantidad | Material de Equipo |
| ------------- | ------------- |
| 1  | Generador de Funciones |
|  1 | Fuente DC  |
| 1  | Osciloscopio |
|  1 | Resistores, capacitores  |
|   1 | Multímetro     |
|  1  | Protoboard      |
|  3  | Amplificadores operacionales      |
|  3  | Cables conductores      |

Tabla 1. Materiales
## *MARCO TEÓRICO*

Un amplificador operacional es un dispositivo amplificador electrónico de alta ganancia acoplado en corriente continua que tiene dos entradas y una salida. En esta configuración, la salida del dispositivo es, generalmente, de cientos de miles de veces mayor que la diferencia de potencial entre sus entradas.

En si, El amplificador operacional es una unidad electrónica que se comporta como una fuente de tensión controlada por tensión.

Un amplificador operacional es un elemento de circuitos activo diseñado para realizar operaciones matemáticas de suma, resta, multiplicación, división, diferenciación e integración.

Los amplificadores operacionales se venden en paquetes de circuitos integrados de diversas presentaciones. En la figura 5.1 aparece un empaque usual de amplificador operacional. Uno habitual es el empaque en línea doble (dual in-line package, DIP por sus siglas en inglés) de ocho terminales que se muestra en la figura. La terminal 8 no se usa, y las terminales 1 y 5 son de escaso interés para el objetivo de esta sección. Las cinco terminales importantes son:

1. La entrada inversora, terminal 2.
2. La entrada no inversora, terminal 3.
3. La salida, terminal 6.
4. El suministro de potencia positivo V+, terminal 7.
5. El suministro de potencia negativo V-, terminal 4.

![alt text](https://github.com/Crislml/Practica-8/blob/master/Img/MT1.PNG)

Como elemento activo, es necesario un suministro de tensión al amplificador operacional, como se muestra del modo común en la figura. 

![alt text](https://github.com/Crislml/Practica-8/blob/master/Img/MT2.PNG)

En una idea simplificada se puede decir que el amplificador operacional es un circuito integrado cuya principal función es amplificar el voltaje con una entrada de tipo diferencial para tener una salida amplificada y con referencia a tierra. Existen dos configuraciones que puede adoptar un amplificador, lazo abierto y lazo cerrado.

## *Ecuaciones*

Amplificador inversor

- Vout = -(Rf/Ri)Vin

Amplificador integrador

- d Vout = -(1/RC)Vi(t) dt

## *PROCEDIMIENTO*
1. Construya en el protoboard cada uno de los circuitos de la figura 1. Muestre
simultáneamente las señales de entrada y salida en un osciloscopio. Dibuje o capture las formas
de onda.
2. Determine y analice la relación entre las señales de entrada y salida en cada uno de los
circuitos indicados en la figura 1.
3. Simule los circuitos y muestre resultados gráficos.

![alt text](https://github.com/Crislml/Practica-8/blob/master/Img/amplificadores.jpg)

Figura 1. Circuitos a ser simulados





## *DIAGRAMA*
En esta práctica tenemos tres circuitos a simular por lo tanto serán tres diagramas:

*Diagrama #1*

![alt text](https://github.com/Crislml/Practica-8/blob/master/Img/Diagrama%20simulado%201.png)

Figura 2. Circuito implementado con osciloscopio.

*Diagrama #2*

![alt text](https://github.com/Crislml/Practica-8/blob/master/Img/Diagrama%20simulado%202.png)

Figura 3. Circuito implementado con osciloscopio.

*Diagrama #3*

![alt text](https://github.com/Crislml/Practica-8/blob/master/Img/Diagrama%20simulado%203.png)

Figura 4. Circuito con dos fuentes e implementado con osciloscopio.

 **EXPLICACIÓN DEL CIRCUITO**

En el primer circuito tenemos conectada una fuente de 1V, y tenemos las impedancias de entrada y de salida conectados a un amplificador LM324 con voltajes inversores y no inversores de +14V. En el segundo circuito tenemos los mismos componentes, únicamente cambia la impedancia de retroalimentación ya que es un capacitor. En el último circuito, tenemos algo parecido al primero pero ese tiene otro voltaje de entrada.

## *PREGUNTAS*
*1. Anote parámetros técnicos importantes de un amplificador operacional que deben ser tomados en cuenta al momento de utilizarlos en un proyecto.*

Entre los principales parámetros que se deben considerar son:

- Valor del voltaje inversor y no inversor.- Es importante a tomar en cuenta estos dos voltajes, ya que de esto dependerá la forma de nuestra señal de salida, ya que dependiendo de esto se observarán diferentes  gráficas respecto al voltaje e función del tiempo.

- Componente de retroalimentación.- Dependiendo de este componente cambiará el amplificador, por ejemplo si fuese una resistencia podriamos hablar de un amplificador inversor, pero si conectamos un capacitor lo que se obtiene es un amplificador integrador.

-Impedancia de entrada.- son los componentes que se oponen al flujo de corriente como las resistencias.

- Tensión de alimentación.- Se refiere a la máxima alimentación que se aplica en los terminales, tomando en cuenta que no exista un flujo excesivo de corriente. 

*2. Investigue las características de amplificadores operacionales distintos a los utilizados en esta práctica.*

Las características mas importantes de los amplificadores operacionales a tomar en cuenta son:

-Infinita ganancia en lazo abierto.

-Infinita resistencia de entrada.

-Corriente de entrada cero.

-Tensión de desequilibrio de entrada cero.

-Infinito rango de tensión disponible en la salida.

-Infinito ancho de banda con desplazamiento de fase cero.

-Rapidez de variación de tensión infinita.

-Ruido cero.

-Infinito rechazo de modo común (CMRR)

-Infinito factor de rechazo a fuente de alimentación (PSRR).

*3. Investigue otras aplicaciones con circuitos más complejos que utilizan amplificadores operacionales.*

Algunas aplicaciones más comunes que hay para esos amplificadores son los siguientes:

-Calculadoras digitales

-Filtros

-Preamplificadores y búferes de audio y video

-Reguladores

-Conversores

-Evitar el efecto de carga

-Adaptadores de niveles (por ejemplo CMOS y TTL)

-Rectificadores de precisión

Las aplicaciones más comunes, corresponden a amplificadores sumadores, restadores, diferenciadores, integradores e integradores (que ya fueron usados).

## *ANÁLISIS DE RESULTADOS*
Los resultados simulados obtenidos de los diagramas respectivamente son:

*Resultado del diagrama #1*

![alt text](https://github.com/Crislml/Practica-8/blob/master/Img/Resultado%201.png)

Figura 5. Voltaje de entrada y salida de amplificador inversor.

Podemos observar que en este circuito se ha conectado la entrada no inversora a tierra, y también se conecta una resistencia, mientras que el voltaje inversor se ha conectado con una resistencia de retroalimentación Rf. Estos son los requisitos para tener un amplificador inversor, el comportamiento se relaciona directamente con su nombre, ya que este amplificador precisamente se encarga de mostrar una salida de señal inversa a la de entrada, que en nuestro caso es mayor y ha aumentado nuestro voltaje a un factor de 4.3.

*Resultado del diagrama #2*

![alt text](https://github.com/Crislml/Practica-8/blob/master/Img/Resultado%203...png)

Figura 6. Amplificador integrador.

En el comportamiento de un circuito con amplificador integrador, se observa en la gráfica que a la salida hay una onda cuadrada bipolar la cual al pasar a través del amplificador operacional se obtiene en la salida una onda integral, esto se debe a que principalmente la onda rectangular se constituye por valores positivos y negativos y como se conoce, al integrar una constante lo que se obtiene es una recta con su respectiva pendiente, que dependerá de las contantes positivas y negativas que se tenga y también del factor que multiplica a toda la integral, el signo negativo en la integral nos indica que está en fase contraria respecto a la señal de entrada.

*Resultado del diagrama #3*

![alt text](https://github.com/Crislml/Practica-8/blob/master/Img/Resultado%203.png)

Figura 7. Voltaje de entrada y salida de amplificador inversor.

En esta gráfica también tenemos un amplificador inversor por lo que tiene el mismo análisis que el primer diagrama, con la diferencia de que hay dos señales que corresponden a las fuentes de entrada, con ayuda de cálculos se obtiene que este voltaje de entrada tiene un valor de 1.7857V y en el voltaje de salida tenemos 8.33V, por lo que concluimos que el voltaje se ha amplificado a un valor de 4.67V.

En general los resultados de las mediciones nunca serán exactas, a pesar del máximo cuidado que se tenga en el momento de realizar cada una de ellas, no es posible expresar el reultado como exacto, es por esto que a continuación se ha realizado el cálculo del error relativo del voltaje obtenido del osciloscopio con respecto al valor resultante de la medición del multímetro de voltaje en la resistencia RL. En nuestro caso consideraremos el resultado del multímetro como el valor teórico.

| Vout teórico | Vout experimental | %Error |
| ------------- | ------------- | ------------- |
|4.3  V | 4.30 V  | 0%  |
|8.3333  V | 7.81 V  | 6.28%  |




## *CONCLUSIONES*
1. Esta práctica fue realizada con éxito ya que se pudo comprobar mediante la fórmula del amplificador inverso el resultado obtenido del osciloscopio de cada circuito simulado obteniendo pequeños porcentajes de errores, que se pueden considerar ya no existe la máxima precisión al usar un osciloscopio.

2. En el primer circuito, tuvimos un aumento del voltaje a un 430%, es decir que se aumento 4,3 veces cumpliendo la función de nuestro amplificador y se comprueba la formula deducida con respecto al calculo del voltaje de entrada en un amplificador inversor e integrador.

3. Se determinó que tanto el primer circuito como el tercer circuito funcionan como amplificadores inversores, ya que como se observó en la gráfica, ambos nos dan una señal de salida inversa a la de entrada que es mayor al valor del voltaje inicial.

4. Encontramos un circuito con un amplificador integrado, ya que al tener conectado un capacitor lo que se observa es una señal de entrada, mientras que en la salida vemos una señal ya integrada, razón por la cual las señales se inclinan y nos dan este tipo de gráfica, la cual está en fase contraria respecto a la señal de entrada.


## *RECOMENDACIONES*
1. Para realizar una práctica exitosa se debe tener conocimiento previo adquirido, principalmente entender perfectamente como es una onda senoidal.

2. En el momento de obtener los datos sobre los voltajes, en nuestro generador aumentamos el doble del voltaje para obtener una mejor visualización del mismo transformando el voltaje pico a pico a una simple lectura del voltaje pico, para no tener confusiones al momento de tomar los datos.

3. Tener cuidado al momento de aproximar los valores que calculamos teóricamente ya que si lo hacemos mal , nos dará un porcentaje de error más alto de lo esperado.

4. Realizar paso a paso la práctica, siguiendo en orden el prodecimiento ya establecido en las guías de laboratorio, para así no cometer errores. 


## *CRONOGRAMA*

![alt text](https://github.com/Crislml/Practica-8/blob/master/Cronograma/Cronograma.jpg)

## *BIBLIOGRAFÍA*

Charles K. Alexander, Matthew N. O. Sadiku, Fundamentos de circuitos eléctricos. Tercera edición. México: McGrawHill, 2004.

Lifeder, Onda senoidal. Recuperado de: https://www.lifeder.com/onda-senoidal/

## *ANEXOS*

![alt text](https://github.com/Crislml/Practica-8/blob/master/Img/Calculos_voltaje.jpg)

Figura 7.  Calculos los voltajes de salida para los 3 distintos circuitos.

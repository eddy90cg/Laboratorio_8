# CARACTERISTICAS DE LA ONDA SENOIDAL

#### INTEGRANTES: EDISON CADENA - STEVEN FLORES - WILLIAM MOSQUERA

# 1.	OBJETIVOS.-

OBJETIVO GENERAL:

* Determinar experimentalmente las características de señales senoidales.
Realizar el circuito propuesto  y  observar la onda senoidad reconocer e interpretar sus caracteristicas

OBJETIVOS ESPECÍFICOS: 

* Reconocer e interpretar  las caracteristicas de la onda senoidal
* Obtener la frecuencia a partir de los datos obtenidos con el osiloscopio
* Observar la diferencia de voltaje rms y voltaje pico 
 

* Resumen: 

Las ondas senoidales son patrones de ondas que matemáticamente pueden ser descritas mediante las funciones seno y coseno. Describen acertadamente eventos naturales y señales variables en el tiempo, tales como los voltajes generados por centrales eléctricas y luego utilizados en hogares, industrias y calles.
Elementos eléctricos como resistencias, condensadores e inductancias, que se conectan a entradas de voltaje sinusoidal, producen respuestas también sinusoidales. Las matemáticas que se utilizan en su descripción son relativamente sencillas y han sido minuciosamente estudiadas.
Onda senoidal representa el valor de la tensión de la Corriente alterna a través de un tiempo continuamente variable, en un par de ejes cartesianos marcados en amplitud y tiempo. Responde a la corriente de canalización generada en las grandes plantas eléctricas del mundo. También responden a la misma forma, todas las corrientes destinadas a generar los campos electromagnéticos de las ondas de radio.

* Introducción:

Osciloscopio (también conocido con el nombre "Oscilógrafo") es una de las más importantes e indispensables herramientas para analizar las señales eléctricas. Hoy día no hay un sólo taller de electrónica o centro de servicio que no tenga este aparato. ¿Pero qué exactamente hacen estos equipos? Los osciloscopios permiten visualizar los cambios de amplitud de señal suministrada durante un lapso de tiempo, observar, medir y grabar esta señal. Un osciloscopio moderno es una herramienta versátil, que permite chequear, ajustar y detectar las fallas no solamente en los componentes electrónicos aislados, sino también en los módulos completos.

![](https://github.com/eddy90cg/Laboratorio_8/blob/main/img/Teoría%201.jpeg)

Figura 1. Una onda senoidal con algunas de sus principales características espaciales: amplitud, longitud de onda y fase.
La matemática de las ondas senoidales o sinusoidales, como también se las conoce, es la de las funciones seno y coseno.

Se trata de funciones repetitivas, lo que significa periodicidad. Ambas tienen idéntica forma, con la salvedad de que el coseno está desplazado hacia la izquierda respecto al seno en un cuarto de ciclo. Se observa en la figura 2:

![](https://github.com/eddy90cg/Laboratorio_8/blob/main/img/Teoría%202.jpeg)

Una onda senoidal se caracteriza por:

 * Amplitud: A0
 * Longitud de onda (λ) es la distancia entre dos máximos o compresiones consecutivos.
 * Período: tiempo en completar un ciclo, medido en segundos. T
 * Frecuencia: es el número de veces que se repite un ciclo en un segundo, se mide en (Hz) y es la inversa del periodo (f=1/T)
 * Fase: el ángulo de fase inicial en radianes. (ßRd). Es el punto donde nace el sonido. Fase 0 indica que el sonido parte de cero y fase de 90º, que empieza en su valor máximo. Como la función matemática del seno, es decir, sin(0) = 0 y sin(90) = 1.

 * Altura: se vincula tradicionalmente a la frecuencia o periodo de la fundamental.
 * amplitud: corresponde al volumen del sonido. En el mundo real se mide en decibelios (dB) y su rango suele estar entre los 20 y los 120 dBs, pero en el mundo digital hablamos de ceros y unos.

Todo esto, pues, tiene que ver con la forma en que describimos las ondas. Su fórmula es

Posición(tiempo) = Amplitud * sin (frecuencia * tiempo + fase)

* Frecuencia: es la velocidad a la que se mueve o vibra el sonido (la senoide). Por ejemplo una frecuencia de 440 Hz corresponde a un LA en la octava media de un piano. Esta es por ejemplo la nota a la que se suele afinar. Es una magnitud subjetiva y se refiere a la altura o gravedad de un sonido. Sin enbargo, la frecuencia es una magnitud objetiva y mensurable referida a formas de onda periódicas. Para expresar una frecuencia lo hacemos refiriéndonos a vibraciones por segundo. Así un frecuencia de 1 Herzio es lo mismo que decir que el sonido tiene una vibración por segundo


* ¿Cómo calcular las ondas senoidales?
Para realizar cálculos que involucren ondas senoidales se utiliza una calculadora científica que disponga de las funciones trigonométricas seno y coseno, así como sus inversas. Estas calculadoras disponen de modos para trabajar los ángulos ya sea en grados o en radianes, y es sencillo convertir de una forma a la otra. El factor de conversión es:

180 º = π radianes.

Según el modelo de la calculadora, deberá navegar mediante la tecla MODE para encontrar la opción DEGREE, que permite trabajar las funciones trigonométricas en grados, o bien la opción RAD, para trabajar directamente los ángulos en radianes.

Por ejemplo sen 25 º = 0.4226 con la calculadora puesta en modo DEG. Al convertir 25 º a radianes se obtiene 0.4363 radianes y sen 0.4363 rad = 0.425889 ≈ 0.4226.

 * Mentefacto:
 
 ![](https://github.com/eddy90cg/lab6-onda-senoidal/blob/main/im/mentefacto.jpg)
 
 
 # 3. EXPLICACIÓN DEL PROCEDIMIENTO.-
 
 Para realizar este laboratorio debes realizar los siguientes pasos:
 
* Implemente el circuito 

* Ajuste el generador de funciones, para que proporcione una señal de 20 Vpp a una frecuencia de 2.5 Khz.

* Conecte el osciloscopio al resistor de carga RL. Observe la señal que aparece en el osciloscopio.
 
* Equipos y Materiales necesarios:

| **Cantidad** | **Elemento** |
| :---: | :---: |
| 1 | Generador de Funciones |
| 1 | Osciloscopio | 
| 1 | Multímetro | 
| 1 | Resistor de <img src="https://latex.codecogs.com/svg.latex?1k\Omega" title="1k\Omega" /> | 
| 1 | Resistor de <img src="https://latex.codecogs.com/svg.latex?2.2k\Omega" title="2.2k\Omega" /> | 
| 1 | Protoboard | 

* Figura, Circuito Teórico:

![](https://github.com/eddy90cg/Laboratorio_8/blob/main/img/Circuito%20Teórico.jpeg)

* Circuito Experimental Armado:

![](https://github.com/eddy90cg/Laboratorio_8/blob/main/img/Circuito%20Armado%20Solo.jpeg)

* Circuito Experimental con mediciones del Osciloscopio

![](https://github.com/eddy90cg/Laboratorio_8/blob/main/img/Circuito%20con%20Osciloscopio.jpeg)

* Circuito Experimental con mediciones del Multímetro

![](https://github.com/eddy90cg/Laboratorio_8/blob/main/img/Circuito%20con%20Multímetro.jpeg)

# 4. RESPUESTA A INTERROGANTES Y CÁLCULO DEL ERROR.-
 
 * RESPUESTA A INTERROGANTES:
 
 Responda las siguientes preguntas:

* ¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?

 Existen un cuadro y un tercio de divisiones que serían 3 voltios por cuadro.

* ¿En qué valor está posicionada la perilla VOLTS/DIV?  

  10 VOLTS/DIV.

* ¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?

  Un ciclo completo abarca cuatro cuadros.

* ¿En qué valor está posicionada la perilla TIME/DIV? 

  0.1 TIME/DIV

* ¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?  

  Amplitud de voltaje: 13.72 V
  
  Periodo: 0,4 ms = 0.0004 s

* Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de
salida.

  Frecuencia:
  
  <img src="https://latex.codecogs.com/svg.latex?f=\frac{1}{T}=\frac{1}{0.4ms}=2.5kHz=2500Hz" title="f=\frac{1}{T}=\frac{1}{0.4ms}=2.5kHz=2500Hz" />
  
  Frecuencia Angular: 
  
 <img src="https://latex.codecogs.com/svg.latex?f_{angular}=\frac{2\pi}{T}=\frac{2\pi}{0.4ms}=15707\&space;\frac{rad}{s}" title="f_{angular}=\frac{2\pi}{T}=\frac{2\pi}{0.4ms}=15707\ \frac{rad}{s}" />

* Con el multímetro digital mida el voltaje de salida en RL: 
 
 9,717 V

* Compare el voltaje medido en el punto anterior y el obtenido en el punto siguiente.

 ¿Coinciden? 
 
 No
 
 ¿Por qué?
 
 El Osciloscopio nos proporciona un Voltaje Pico, mientras que el Multímetro nos proporciona un Voltaje RMS que es nuestro valor eficaz de voltaje. 

 # 5. VIDEO.-
 
 -----------------------
 
 # 6.	CONCLUSIONES.-
 
 * Mediante la práctica se observo el comportamiento de la onda senoidal y sus características las se pueden obtener mediante cálculos y analizar los valor de cada una 
se observar la diferencia de voltaje rms y voltaje pico al momento de realizar la práctica y comparar las mediciones con el osciloscopio y el multímetro digital.

* El Simulador DCACLAB resulta muy eficiaz para realizar mediciones con Osciloscopio por su exactitud y presición en las mediciones dadas.
 
 # 7.	BIBLIOGRAFÍA.-
 
 Obtenido de:

    https://www.lifeder.com/onda-senoidal/
 
 
Obtenido de:

    http://ondasguiadasdiana.blogspot.com/2016/08/caracteristicas-de-las-ondas-senoidales.html

Obtenido de :

    https://www.ecured.cu/Onda_senoidal#:~:text=Concepto%3A,marcados%20en%20amplitud%20y%20tiempo.
 

 * RÚBRICA:

![](https://github.com/eddy90cg/Laboratorio_4/blob/main/Anexos/rubrica.jpg)
 

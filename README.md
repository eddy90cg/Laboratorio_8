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

 * altura: se vincula tradicionalmente a la frecuencia o periodo de la fundamental.
 * amplitud: corresponde al volumen del sonido. En el mundo real se mide en decibelios (dB) y su rango suele estar entre los 20 y los 120 dBs, pero en el mundo digital hablamos de ceros y unos.

Todo esto, pues, tiene que ver con la forma en que describimos las ondas. Su fórmula es

Posición(tiempo) = Amplitud * sin (frecuencia * tiempo + fase)

* frecuencia: es la velocidad a la que se mueve o vibra el sonido (la senoide). Por ejemplo una frecuencia de 440 Hz corresponde a un LA en la octava media de un piano. Esta es por ejemplo la nota a la que se suele afinar. Es una magnitud subjetiva y se refiere a la altura o gravedad de un sonido. Sin enbargo, la frecuencia es una magnitud objetiva y mensurable referida a formas de onda periódicas. Para expresar una frecuencia lo hacemos refiriéndonos a vibraciones por segundo. Así un frecuencia de 1 Herzio es lo mismo que decir que el sonido tiene una vibración por segundo


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

 
* Calculos correspondientes para el experimento :

   *   https://github.com/eddy90cg/lab6-onda-senoidal/blob/main/Anexos/CamScanner%2003-02-2021%2013.20.pdf
    
CALCULOS :

1. RESISTENCIA TOTAL
RT = 𝑅1 + 𝑇𝐿
𝑅𝑇 = (1000 + 2200)Ω
𝑅𝑇 = 3200 Ω

2. INTENSIDAD TOTAL
𝐼𝑇 =𝑉𝑎𝑐/Rt
𝐼𝑇 =10V/3200
𝐼𝑇 = 3.125 𝑚�

3.𝑓𝑜𝑟𝑚𝑢𝑙𝑎 𝑑𝑒 𝑑𝑖𝑣𝑖𝑠𝑜𝑟 𝑑𝑒
𝑑𝑒 𝑣𝑜𝑙𝑡𝑎𝑗𝑒 𝑝𝑎𝑟𝑎 𝑠𝑎𝑏𝑒𝑟 𝑒𝑙 𝑣𝑜𝑙𝑡𝑎𝑗𝑒 𝑑𝑒 𝑅𝐿
𝑉𝑅𝐿 =𝑉𝑇.RL
𝑉𝑇(RL)=3,125(2,2)
VRL=6,87(V)

4.VOLTAJE RMS
𝑉𝑟𝑚𝑠 = 0.707𝑉𝑝
𝐸𝑛𝑡𝑜𝑛𝑐𝑒𝑠:
𝑉𝑟𝑚𝑠 = 0.707(6.875𝑉)
𝑉𝑟𝑚𝑠 = 4.86 mA

5.velocidad angular
ω = 2πf
ω = 2π2(2500Hz)
ω = 15707.96 rad/s

 
 * Fórmula a aplicar para el cálculo del ERROR:

  <img src="https://latex.codecogs.com/svg.latex?\large&space;\begin{align*}&space;&\textrm{F\'ormula&space;para&space;encontrar&space;el&space;Error&space;Porcentual}\\&space;\\&space;&%Error=\frac{\textrm{Valor&space;Te\'orico&space;-&space;Valor&space;Medido}}{\textrm{Valor&space;Te\'orico}}\times100&space;\end{align*}" title="\large \begin{align*} &\textrm{F\'ormula para encontrar el Error Porcentual}\\ \\ &%Error=\frac{\textrm{Valor Te\'orico - Valor Medido}}{\textrm{Valor Te\'orico}}\times100 \end{align*}" />
 
 * CALCULO DEL ERROR:
    voltaje pico=0,36%
    voltaje rms=0,78%
 
 * RESPUESTA A INTERROGANTES:
 
 Responda las siguientes preguntas:

* ¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?

  3 voltios por cuadro

* ¿En qué valor está posicionada la perilla VOLTS/DIV?  

  1.4

* ¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?

  8 divisiones

* ¿En qué valor está posicionada la perilla TIME/DIV? 

  50us

* ¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla
del osciloscopio?  

  Amplitud de voltaje: 11.2
  Periodo: 0,0004

* Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de
salida.

  f: 2500 HZ
  ω: 5000 rad/s

* Con el multímetro digital mida el voltaje de salida en RL: 
 
   9,71 V

* Compare el voltaje medido en el punto anterior y el obtenido en el punto siguiente.

   ¿Coinciden? NO COINCIDEN YA QUE SE HABLA DE UN VOLTAJE PICO Y EL OTRO ES UN VOLTAJE RMS O EFICAZ  EN EL OSILOSCOPIO OBTENEMOS UN VALOR  PICO MIENTRAS QUE EPARA OBTENER EL VALOR EFICAZ DIVIDIMOS PARA  RAIZ DE 2, EN EL MULTIMETRO DIGITAL YA NOS PROPORCIONA EL VALOR EFICAZ
___________________________________________________________________________________________________________________________________________________________________________

 
 
 
 
 
 # 5. VIDEO.-
 
 
 -----------------------
 
 # 6.	CONCLUSIONES.-
 
 * Mediante la practica se observo el comportamiento de la onda senoidal y sus caracteristicas las se pueden obtener mediante calculos y analizar los valor de cada una 
se observar la diferencia de voltaje rms y voltaje pico al momento de realizar la practica y comparar las mediciones con el oscilometro y el multimetro digital.

* El software proteus es util en este tipo de practicas ya que posee variedad de elementos que se necesita para simular el circuito
 
 
 
 
 
 # 7.	BIBLIOGRAFÍA.-
 
 Obtenido de:

https://www.lifeder.com/onda-senoidal/
 
 
Obtenido de:

http://ondasguiadasdiana.blogspot.com/2016/08/caracteristicas-de-las-ondas-senoidales.html

Obtenido de :

https://www.ecured.cu/Onda_senoidal#:~:text=Concepto%3A,marcados%20en%20amplitud%20y%20tiempo.
 

 * RÚBRICA:

![](https://github.com/eddy90cg/Laboratorio_4/blob/main/Anexos/rubrica.jpg)
 

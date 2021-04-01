# Laboratorio 9
1. OBJETIVOS
- Objetivo General:
   
   - Comprender los funcionamientos de los amplificadores operacionales, así como sus efectos en un circuito.
   
- Objetivos Específicos:
 
   - Analizar los diferentes voltajes de salida que ocurren en cada uno de los tres circuitos dados.
   - Comparar los diferentes valores de voltajes que existen en los tres circuitos
   - Conocer los usos de los amplificadores operacionales y como estos son aplicados dentro de los circuitos.
   
2. MARCO TEÓRICO
   
![0001 (14)](https://user-images.githubusercontent.com/76133212/113235237-54afe600-9268-11eb-9839-5e8bc4da5ffa.jpg)
![0001 (15)](https://user-images.githubusercontent.com/76133212/113235248-58dc0380-9268-11eb-8a2b-580f172e5c9c.jpg)

   
   
3. DIAGRAMAS
   
   ![image](https://user-images.githubusercontent.com/75439689/113229697-1bbe4400-925d-11eb-9ebf-3ea3d8e1bbf3.png)
   
   *Elementos Circuito 1*
   
   ![image](https://user-images.githubusercontent.com/75439689/113229726-27aa0600-925d-11eb-98d1-dc517b743344.png)
   
   *Circuito 1*
   
   ![image](https://user-images.githubusercontent.com/75439689/113229745-30024100-925d-11eb-913e-5a0e204da038.png)
   
   *Elementos Circuito 2*
   
   ![image](https://user-images.githubusercontent.com/75439689/113229829-5d4eef00-925d-11eb-9714-3491b01569da.png)
   
   *Circuito 2*
   
   ![image](https://user-images.githubusercontent.com/75439689/113229836-60e27600-925d-11eb-8945-8146c9328561.png)
   
   *Elementos Circuito 3*
   
   ![image](https://user-images.githubusercontent.com/75439689/113229842-63dd6680-925d-11eb-9f5f-bb7b94432680.png)
   
   *Circuito 3*
   
4. LISTA DE COMPONENTES
   
   ![image](https://user-images.githubusercontent.com/75439689/113228015-938a6f80-9259-11eb-8af3-280991a69b86.png)
   
   *Figura 4.1*

5. EXPLICACIÓN

   5.1. Procedimiento
   
    Circuito 1. - 
    
    Circuito 2. -
    
    Circuito 3. - En la plataforma de multisim primero sacaremos los materiales, para la realización de este, el útlimo circuito, se necesita de 2 fuentes de voltaje ca. que tengan 1 V de voltaje pico y 3kHz de frecuencia, 3 resistencias, una de 1kohm, una de 300ohm y otra de 200ohm, 2 fuentes de cd. y un Opamp. Conectaremos las 2 fuentes de ca. en paralelo, y estas se concetaran en serie con la entrada inversora del Opamp, las resistencias de 300ohm y la de 200ohm serán conectados en serie con las fuentes ca. La resistencia de 1kohm se conectará en paralelo con el Opamp, justo en el extremo de las fuentes y en la parte de salida del Opamp; las fuentes de cd. de 14V se conectan en las alimentaciones del amplificador, luego dejamos abierto el circuito y lo empezamos a medir las fuentes y el voltaje de salida del Opamp. 

   5.2. Análisis de Resultados
   
     ![image](https://user-images.githubusercontent.com/75439689/113229510-be29f780-925c-11eb-87d4-bbcbb038f703.png)
     
     Las ondas se evaluarán primero entre el circuito 1 y el circuito 2:
     Las ondas como se pueden observar son diferentes, ya que el circuito 2 tiene como fuente ondas pulsantes donde llegá al valor pico enseguida y llega a 0 en un instante, y el circuito 1 tiene fuente con onda sinuoidal y llega a su valor pico de 4.3 V, pero como podemos observar, en la gráfica del circuito 1 se puede ver que su valor pico va tanto a positivo como a negativo, por otro lado en el circuito 2 el voltaje invertido se nota mucho más, primero se amplifica a un valor de 14.89 y cambia a -.
     
     Por otro lado el circuito 1 y 3, son parecidos ya que son básicamente el mismo circuito, pero en la parte de la izquierda se une otra fuente de ca. del mismo voltaje y la misma frecuencia, pero como se dijo antes, es casi el mismo circuito, por lo que se puede esperar que se tenga valores de voltaje parecidos, donde el voltaje pico del circuito 1 tiene el doble del voltaje pico del circuito 3, por lo que se espera que el voltaje de salida del último circuito sea el doble del circuito 1.
     
   5.3. Preguntas
   
   1. Anote parámetros técnicos importantes de un amplificador operacional que deben ser tomados en cuenta al momento de utilizarlos en un proyecto.
   2. Investigue las características de amplificadores operacionales distintos a los utilizados en esta práctica.
      
      Los amplificadores operacionales también se utilizan para: Sumador Inversor. - El amplificador operacional sumador permite al usuario sumar varios niveles de voltaje a la vez que se invierte el signo del voltaje. Sumador No Inversor. - la tensión de salida es proporcional a la suma de tensiones de entrada. Amplificador Diferencial (Restador). - Este amplificador usa ambas entradas invertida y no invertida con una ganancia de uno, para producir una salida igual a la diferencia entre las entradas.
      
   4. Investigue otras aplicaciones con circuitos más complejos que utilizan amplificadores operacionales.
   
   ![image](https://user-images.githubusercontent.com/75439689/113233888-d18d9080-9265-11eb-8601-68a575b25afa.png)
   
   Las aplicaciones serían:
   Tarjetas de sensores que incorporan amplificador operacional en modo comparador. 
   Instrumentación y control automotrices.
   Circuitos integrados para comunicaciones.
   Circuitos integrados para radio, audio y video.
   Circuitos integrados para electrómetros usados en circuitos con impedancia de entrada muy elevada.
   Circuitos integrados que funcionen con una sola fuente de alimentación.
   Circuitos integrados que funcionen con fuentes de alimentación bipolares.
   
6. CONCLUSIONES

   - Cuando la frecuencia de la fuente es igual a cero, se trata de una fuente de corriente continua, la cual produce un efecto distinto sobre los capacitores y los inductores a diferencia de lo que produce la corriente alterna en ellos. Dicho efecto consiste en que ambos almacenan energía, pero considerando también que el capacitor impide completamente el paso de corriente. 
   - En el circuito con capacitores, a medida que aumenta la frecuencia de la fuente, el valor pico de la corriente aumenta, esto se debe a que la reactancia capacitiva es inversamente proporcional a la frecuencia, por ello se obtiene un valor cada vez menor de la reactancia, lo que permite un mayor paso de corriente.
   - Por otra parte, en el circuito con inductores, a medida que aumenta la frecuencia, la reactancia inductiva también lo hace ya que son directamente proporcionales, haciendo que el valor pico de la corriente disminuya debido a que se impide mayormente el flujo de corriente en el circuito.


7. BIBLIOGRAFÍA

   - Floyd, T. L. (2007). Principios de circuitos eléctricos (Octava ed.).
   - Conoce lo más importante sobre amplificadores operacionales. (2021). Recuperado el 1 de Abril de 2021, de https://uelectronics.com/amplificadores-operacionales/

# Laboratorio 9
1. OBJETIVOS
- Objetivo General:
   
   - Comprender los funcionamientos de los amplificadores operacionales, así como sus efectos en un circuito.
   
- Objetivos Específicos:
 
   - Analizar los diferentes voltajes de salida que ocurren en cada uno de los tres circuitos dados.
   - Comparar los diferentes valores de voltajes que existen en los tres circuitos
   - Conocer los usos de los amplificadores operacionales y como estos son aplicados dentro de los circuitos.
   
2. MARCO TEÓRICO
   
   
   
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
     
     Por otro lado el circuito 1 y 3, son parecidos ya que son básicamente
     
   5.3. Preguntas
   
     1. ¿Cómo se comportan la bobina y el capacitor en corriente continua (cero Hz)?
       
     Cuando un capacitor se encuentra con corriente continua, este evita el paso de dicha corriente, ya que almacena carga eléctrica en sus extremos. Dicha carga se relaciona con los valores medidos de voltaje en los extremos de la conexión en paralelo de las dos capacitancias.
     Por otro lado, con las bobinas sucede algo similar, ya que también se acumula energía en ellas, la cual a su vez también se encuentra relacionada con los valores medidos de voltaje. 
         
     2. ¿Cómo se comportan la bobina y el capacitor en corriente alterna?

     Tanto la bobina como el capacitor, cuando se encuentran en corriente alterna permiten el paso de dicha corriente, pero con una oposición a ella, lo cual se conoce como reactancia, la cual puede ser capacitiva (si se trata de un capacitor) o inductiva (si se trata de un inductor).
      
     3. ¿Qué cree usted que ocurriría con el voltaje Vo y la corriente de la resistencia en los circuitos analizados en esta práctica, si se utilizan dos bobinas o dos capacitores de valores distintos?

     Dado que la reactancia depende de los valores de capacitancia e inductancia (dependiendo del tipo de reactancia que sea), por ello si varían dichos valores, también van a variar los valores de la corriente como de Vo.
     Si se aumentan los valores de capacitancia, se obtendrá una reactancia capacitiva menor, lo cual permitirá un mayor paso de corriente, pero el valor en Vo disminuiría.
     Por otro lado, si se aumentan los valores de inductancia, la reactancia inductiva será mayor, lo cual impedirá mayormente el paso de corriente, haciendo que el valor de Vo aumente.
       
     4. ¿Qué son los valores eficaces de voltaje y corriente?

     Los valores eficaces también se conocen como rms, los cuales son los valores de voltaje o corriente alternos, que generarían un igual efecto si se tratara de una fuente cd con los mismos valores.
       

  

6. CONCLUSIONES

   - Cuando la frecuencia de la fuente es igual a cero, se trata de una fuente de corriente continua, la cual produce un efecto distinto sobre los capacitores y los inductores a diferencia de lo que produce la corriente alterna en ellos. Dicho efecto consiste en que ambos almacenan energía, pero considerando también que el capacitor impide completamente el paso de corriente. 
   - En el circuito con capacitores, a medida que aumenta la frecuencia de la fuente, el valor pico de la corriente aumenta, esto se debe a que la reactancia capacitiva es inversamente proporcional a la frecuencia, por ello se obtiene un valor cada vez menor de la reactancia, lo que permite un mayor paso de corriente.
   - Por otra parte, en el circuito con inductores, a medida que aumenta la frecuencia, la reactancia inductiva también lo hace ya que son directamente proporcionales, haciendo que el valor pico de la corriente disminuya debido a que se impide mayormente el flujo de corriente en el circuito.


7. BIBLIOGRAFÍA

   - Floyd, T. L. (2007). Principios de circuitos eléctricos (Octava ed.).

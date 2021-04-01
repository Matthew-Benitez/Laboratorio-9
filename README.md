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
     
     Para el análisis de resultados se imprimieron dos tablas, una por cada circuito, donde los datos se distribuyen en 4 columnas: frecuencia, voltaje pico, voltaje rms y la corriente, cada dato fue tomado mediante el simulador dcac lab, y luego fueron puestos en estas tablas.
     
     Tabla Circuito con Capacitores Voltaje pico:
     
     Los voltajes pico tiene un valor casi aproximado al voltaje de fuente, pero a medida que la frecuencia aumenta, su voltaje pico va disminuyendo en relación al voltaje de fuente. Al principio la frecuenia de 0 Hz debería darnos un voltaje de 10v, sin embargo, el simulador no puede determinar esto.
     
     Tabla Circuito con Capacitores Voltaje rms:
     
     Los voltajes rms expresan el voltaje real que capta una carga, estos voltajes representan el 0.707 del voltaje pico de los medidos en la segunda columna de la primera tabla, esto es experimentado en las tablas, cada dato es al menos algo cercacno al 0.707 de cada voltaje pico respectivamente de cada frecuencia.
     
     Tabla Circuito con Capacitores Corriente:
     
     Los valores de corrientes se comportan de manera inversa a la de los voltajes; en cada voltaje, a medida que aumentaba la frecuencia, disminuía el voltaje, por otro lado, la corriente va en aumento a medida que la frecuencia aumenta, esto es evidenciado en la tabla donde los datos fueron sacados del simulador.
     
     Tabla Circuito con Inductores Voltaje pico:
     
     Los voltajes pico en la tabla de inductores se comportan de manera contraria a los voltajes de la tabla del circuito con capacitores, los voltajes pico empiezan cerca del 0, pero por cada frecuencia que va aumentando, los valores del voltaje se van acercando al valor del voltaje de fuente, como es evidenciado en la segunda columna de la tabla de inductores.
     
     Tabla Circuito con Inductores Voltaje rms:
     
     Los voltajes de la tercera columna cumplen la teoría de que valen el 0.707 del valor de voltaje pico, y como fue dicho antes, estos valores van en aumento a medida que la frecuencia va aumentando, al contrario de como se comportaba los voltajes rms en la tabla del circuito con capacitores.
     
     Tabla Circuito con Inductores Corriente:
     
     En esta tabla se evidencia la corriente que se pasa por parte de la resistencia, pero se puede observar que los valores que pasan por este se ven afectados de manera inversa por la frecuencia, es decir, por cada frecuencia que se va aumentando el valor de la corriente va disminuyendo, al contrario de la tabla de circuito con capacitores, hasta llegar al valor de 0 A.
     
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

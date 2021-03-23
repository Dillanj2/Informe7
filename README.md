# TEOREMA DE THEVENIN

1. OBJETIVOS

Generales

* Analizar las características del teorema de Thevenin en circuitos resistivos. 

Especificos

* Determinar el uso del teorema de Thevenin en circuitos electricos. 
* Explicar los resultados obtenidos despues de realizar la práctica.
* Relacionar los resultados obtenidos de forma teórica y experimental.

2. MARCO TEÓRICO 

El teorema de Thevenin establece que un circuito lineal de dos terminales puede sustituirse por un circuito equivalente formado por una fuente de tensión VTH (voltaje de thevenin) en serie con una resistencia RTH (resistencia de thevenin).

Es decir, el teorema de Thevenin proporciona una técnica para sustituir la parte fija por un circuito equivalente sencillo.

Mientras se tenga un circuito resistivo, para manejar los calculos de mejor manera se puede reemplazar por un circuito equivalente mas sencillo, llamado circuito de thevenin.

Cuando se construye un circuito equivalente de Thevenin, es posible realizar cálculos más sencillos y en menos tiempo que al trabajar con el circuito completo original. Para lograr aplicar el teorema correctamente, se deben realizar estos pasos:

1. Al eliminar las fuentes de alimentación del circuito original, será posible encontrar la resistencia de Thevenin. Luego se deberá calcular el valor de la resistencia total que existe entre los punto A y B donde se encuentre conectada la resistencia de carga.

2. Para el caso de hallar la tensión de Thevenin, se elimina la resistencia de carga, y se calcula el voltaje de los puntos de conexión abiertos donde esta se encontraba.
C
3.onstruye el circuito equivalente utilizando la tensión de Thevenin y la resistencia de Thevenin en serie. Conecta la resistencia de carga entre los puntos de conexión abiertos de este circuito.

4.Utilizando las reglas de circuitos en serie, se analiza la tensión y corriente de la resistencia de carga.

3. DIAGRAMAS

<p align="center">
  <img src="https://github.com/Dillanj2/Informe7/blob/main/Im%C3%A1genes/Circuito%20Thevenin.jpg">
</p>
<p align="center">
  Diagrama 3.1: Circuito para comprobar el Teorema de Thevenin.
</p>

4. LISTA DE COMPONENTES

* 2 Fuentes de Voltaje de C.D. 
* 2 Multímetros Digitales.
* Resistor de 560kΩ.
* Resistor de 4.7kΩ.
* Resistor de 100Ω.
* Resistor de 330Ω.
* Resistor de 1kΩ.
* Potenciometro de precision de 1kΩ.
* Protoboard.

5. PROCEDIMIENTO

5.1 Arme el circuito que se muestra en el diagrama 3.1.

5.2 Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor medido en la tabla 5.1.

5.3 Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 5.1.

5.4 Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2.

<p align="center">
  <img src="https://github.com/Dillanj2/Informe7/blob/main/Im%C3%A1genes/Tabla%205.1.jpg">
</p>
<p align="center">
  Tabla 5.1: Valores del Circuito Equivalente de Thévenin.
</p>

<p align="center">
  <img src="https://github.com/Dillanj2/Informe7/blob/main/Im%C3%A1genes/Tabla%205.2.jpg">
</p>
<p align="center">
  Tabla 5.2: Comprobación del Teorema de Thévenin.
</p>

El procedimiento lo puede observar entrando al siguiente enlace: 

<p><a href="https://github.com/Dillanj2/Informe7/blob/main/C%C3%B3digo%20fuente/Procedimiento_de_Laboratorio_7.pdf">Procedimiento</a>

6. CONCLUSIONES

* El teorema nos ayuda en el analisis de circuitos electricos ya que es mejor trabajar con un circuito equivalente mas sencillo a uno mas complejo. 
* El analisis es mas eficaz y mas rapido al momento de trabajar con circuitos de thevenin.

7. BIBLIOGRAFIA

Francis. L. (1 de noviembre de 2019). Teorema de Thevenin. Obtenido de: https://dademuch.com/2019/11/10/teorema-de-thevenin-analisis-de-circuitos-electricos/

8. ANEXOS

<p align="center">
  <img src="https://github.com/Dillanj2/Informe7/blob/main/Im%C3%A1genes/Circuito%20LTspice.png">
</p>
<p align="center">
  Figura 8.1: Circuito en Ltspice.
</p

<p align="center">
  <img src="https://github.com/Dillanj2/Informe7/blob/main/Im%C3%A1genes/Corriente%20del%20circuito%20original.png">
</p>
<p align="center">
  Figura 8.2: Corriente del circuito.
</p
  
<p align="center">
  <img src="https://github.com/Dillanj2/Informe7/blob/main/Im%C3%A1genes/Corriente%20del%20circuito.png">
</p>
<p align="center">
  Figura 8.3: Corriente del circuito Thevenin.
</p
  
<p align="center">
  <img src="https://github.com/Dillanj2/Informe7/blob/main/Im%C3%A1genes/Voltaje%20del%20circuito%20original.png">
</p>
<p align="center">
  Figura 8.4: Voltaje del circuito.
</p
  
<p align="center">
  <img src="https://github.com/Dillanj2/Informe7/blob/main/Im%C3%A1genes/Voltaje%20del%20circuito.png">
</p>
<p align="center">
  Figura 8.5: Voltaje del circuito Thevenin.
</p


  

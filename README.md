# Informe de Laboratorio #4
## Fasores
### 1.	OBJETIVOS

**Principal**

 - Resolver de forma analítica fasores.
 
**Específicos**

- Comparar los resultados analiticos con los de la calculadora cientifica para descubrir su error 
- Formular las ecuaciones pra transformar de la froma rectangular a polar
- Validar los resultados con el emnro error posible

### 2.	MARCO TEÓRICO 
#### Números Imaginarios
En ingeniería eléctrica, este tipo de número se denomina "número imaginario". Para distinguir los números imaginarios de los números reales, se utiliza la letra "j" (generalmente llamada operador j en ingeniería eléctrica). La letra j se coloca antes del número real para indicar su operación numérica imaginaria. Ejemplos de números imaginarios son: J3, J12, J100, etc. A continuación, el número complejo consta de dos partes diferentes pero estrechamente relacionadas, a saber, el "número real" más el "número imaginario". Un número complejo representa un número complejo bidimensional o un punto referenciado por dos ejes diferentes en el plano s. El eje horizontal se denomina "eje real" y el eje vertical se denomina "eje imaginario". Las partes real e imaginaria del número complejo Z se abrevian como Re (z) e Im (z), respectivamente.


El valor del operador j es exactamente igual a √-1, la multiplicación continua por "j", (j x j) hará que j tenga los siguientes valores, -1, -j y 1. Dado que el operador j se usa generalmente para indicar la rotación en sentido antihorario de un vector, cada producto o potencia sucesiva "j", j 2, j 3, etc. forzará al vector a girar 90 ° en sentido antihorario, como se muestra a continuación. De manera similar, si multiplica los vectores para obtener el operador -j, el cambio de fase será -90 o rotación en sentido horario.

Por lo tanto, multiplicar el número imaginario por j 2 rotará el vector 180o en sentido antihorario, multiplicar por j 3 rotará 270o, y luego multiplicarlo por j 4 rotará 360o de regreso a su posición original. Multiplicar por j 10 o j 30 rotará el vector en sentido antihorario por la cantidad apropiada. En cada rotación sucesiva, la magnitud del vector es siempre la misma. En ingeniería eléctrica, los números complejos se pueden representar gráfica o matemáticamente. Un método utilizado por las reglas del coseno y del seno se llama cartesiano o rectangular.

#### Los números complejos utilizando la forma rectangular

Los números complejos están representados por partes reales e imaginarias, y toman la siguiente forma generalizada: 

Dónde:

  Z   - es el número complejo que representa el vector
  x   - es la parte real o el componente activo
  y   - es la parte imaginaria o el componente reactiva
  j   - se define por √ -1
  
  En forma rectangular, los números complejos se pueden expresar como puntos en un plano bidimensional llamados números complejos o planos-s. Entonces, por ejemplo, Z = 6 + j4 representa un solo punto cuyas coordenadas representan 6 en el eje real horizontal y 4 en el eje imaginario vertical.


### 3.	LISTA DE COMPONENTES

| Cantidad | Componentes | 
| -------- | ----------- | 
| 1 |Calculadora cientifica| 

 
> (Herramientas utilizadas en simulación) 
> Simulador thinkercad


### 5.	EXPLICACIÓN
Aramar el circuito

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/13.png) 

###### _FIGURA 4_

__5.1__ Calculos de forma teorica

- Calcular la corriente en las mallas
![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/14.png) 

- Calcular el voltaje 

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/15.png)

- Calcular La corriente de los nodos

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/16.png) 

- Calculo del error porcentual

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/17.png) 

__5.2__ Tabulacion de los datos

__5.2.1__ Resultados obtenidos de voltaje y corriente, en cada elemento del circuito. 

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/18.png) 

Tabla 1

__5.2.2__ Verifique si se cumple la Ley de Kirchhoff de Voltajes en cada trayectoria cerrada,
considerando las elevaciones de voltaje con signo positivo y las caídas de voltaje con
signo negativo. Anote los resultados en la tabla 1

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/19.png) 

Tabla 2

__5.2.3__ Verifique si se cumple la Ley de Kirchhoff de Corrientes en cada nodo, tomando
con signo positivo las corrientes que entran al nodo y con signo negativo las que salen
del nodo. Anote los resultados en la tabla 2.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/20.png) 

Tabla 3

__5.2.4__ Compare los resultados medidos con los valores obtenidos al analizar el circuito
analíticamente y concluya al respecto.

![](https://github.com/SanchezMaiAndresSebastian/Informe-laboratorio/blob/main/Fotos/21.png) 

Tabla 4

__5.2.5__ Compare los resultados medidos con los valores obtenidos al analizar el circuito
analíticamente y concluya al respecto.



En el circuito que hemos construido se ve como la unión de diferentes elementos eléctricos en un circuito eléctrico, el cual primero se pone la fuente de voltaje de corriente continua se une con alambres el color perteneciente a su fuente con el protoboard el cual es el positivo (rojo) y el negativo (negro)
Después se pone con el resistor en la parte de los nodos en la columna que sea necesario para que tenga un paso de corriente
Terminamos midiendo el voltaje de cada resistor 

### 6.	 DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

 - Siempre tener conectado a una fuente de corriente continua
 - Tener la fuente de voltaje configurada para la medición en voltios
 - Tener el multímetro siempre en la configurada en la medición de voltios 
 
### 7.	APORTACIONES

 - No hay paso de corriente si se invierten la tomas positivas y negativas de un circuito.
 - No es lo mismo la medición de voltaje con corriente 
 - El multímetro tiene diferentes funcionamientos dependiendo si es digital o análogo.
 - LLa fuente de corriente directa mide cuantos amperios tiene el circuito.
 
### 8.	CONCLUSIONES
 - Se demostro que las leeys de lkirchoff se rigen bajo los nodos que con ello se experimenta con los circuitos por ende siempre van a tener mediciones en cualquier parte del proyecto.
 - Al momento de construir el circuito se tiene que tener en cuenta que tiene que conectarse correctamenet los cabls en el positivo y negativo de todos los instrumentos electricos los cuales si no se hacen correctamente pueden sufrir una disminución de la vida útil.
 - Cuando en unn resistor se encuentra aplicado con el multímetro la medicion de su corriente, cambia el voltaje de los demas resistores que se tienen midiendo con los demás herraminetas

### 9.	BIBLIOGRAFÍA

[1]Floyd, T. (2007). Principios de circuitos electricos. Mexico: Pearson Educacion. Serway,

[2]R. (2001). Fisica II. Mexico: Pearson Educacion.
### 10.	 ANEXOS

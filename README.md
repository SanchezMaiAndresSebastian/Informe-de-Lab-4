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

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/1.png) 

El valor del operador j es exactamente igual a √-1, la multiplicación continua por "j", (j x j) hará que j tenga los siguientes valores, -1, -j y 1. Dado que el operador j se usa generalmente para indicar la rotación en sentido antihorario de un vector, cada producto o potencia sucesiva "j", j 2, j 3, etc. forzará al vector a girar 90 ° en sentido antihorario, como se muestra a continuación. De manera similar, si multiplica los vectores para obtener el operador -j, el cambio de fase será -90 o rotación en sentido horario.

Por lo tanto, multiplicar el número imaginario por j 2 rotará el vector 180o en sentido antihorario, multiplicar por j 3 rotará 270o, y luego multiplicarlo por j 4 rotará 360o de regreso a su posición original. Multiplicar por j 10 o j 30 rotará el vector en sentido antihorario por la cantidad apropiada. En cada rotación sucesiva, la magnitud del vector es siempre la misma. En ingeniería eléctrica, los números complejos se pueden representar gráfica o matemáticamente. Un método utilizado por las reglas del coseno y del seno se llama cartesiano o rectangular.

#### Los números complejos utilizando la forma rectangular

Los números complejos están representados por partes reales e imaginarias, y toman la siguiente forma generalizada: 

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/2.png) 

Dónde:

  Z   - es el número complejo que representa el vector
  x   - es la parte real o el componente activo
  y   - es la parte imaginaria o el componente reactiva
  j   - se define por √ -1
  
  En forma rectangular, los números complejos se pueden expresar como puntos en un plano bidimensional llamados números complejos o planos-s. Entonces, por ejemplo, Z = 6 + j4 representa un solo punto cuyas coordenadas representan 6 en el eje real horizontal y 4 en el eje imaginario vertical.
  
![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/3.png) 

El eje horizontal representa todos los números reales positivos en el lado derecho del eje imaginario vertical y todos los números reales negativos en el lado izquierdo del eje imaginario vertical. Todos los números imaginarios positivos están por encima del eje horizontal y todos los números imaginarios negativos están por debajo del eje real horizontal. Esto generará un plano bidimensional complejo que contiene cuatro cuadrantes diferentes etiquetados como QI, QII, QIII y QIV.

Los números complejos también pueden tener "cero" partes reales o imaginarios, tales como: Z = 6 + j0   o   Z = 0 + j4 . En este caso, los puntos se representan directamente en el eje real o imaginario. Además, el ángulo de un número complejo se puede calcular utilizando la trigonometría simple calcular los ángulos de triángulos rectángulos, o se mide en sentido antihorario alrededor del diagrama de Argand a partir del eje real positivo.

#### Los números complejos usando la Forma Polar

A diferencia de dibujar un rectángulo de puntos en un plano complejo, las coordenadas polares de un número complejo se escriben de acuerdo con su tamaño y ángulo. Por lo tanto, la forma del vector polar es: Z = A∠ ± θ, donde: Z es el número complejo de la forma polar, A es la magnitud o módulo del vector y θ es el ángulo de A o la variable independiente puede ser positivo o negativo. El tamaño y el ángulo del punto son los mismos que los del rectángulo de arriba, esta vez se muestra en forma polar, y la posición del punto está representada por un "triángulo" como se muestra a continuación.

Dado que la representación de las coordenadas polares de los puntos se basa en triángulos, podemos usar geometría de triángulo simple, especialmente trigonometría y el teorema de Pitágoras sobre triángulos, para encontrar el tamaño y el ángulo de números complejos. Recordamos de la escuela que la trigonometría se ocupa de la relación entre los lados y los ángulos de los triángulos, por lo que podemos describir la relación entre los lados como:

#### Suma y resta
![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/4.png) 
#### Multiplicación y división de números complejos
La multiplicación de números complejos en forma rectangular sigue más o menos las mismas reglas que el álgebra normal, y algunas reglas adicionales para la multiplicación continua por el operador j, donde: j 2 = -1. Entonces, por ejemplo, multiplicando nuestros dos vectores de A = 4 + J1 y B = 2 + j3 para obtener el siguiente resultado.
![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/5.png) 

Matemáticamente, la división de números complejos en forma rectangular es más difícil porque requiere el uso de una función de denominador conjugado para convertir el denominador de la ecuación en un número real. A esto se le llama "racionalización". A continuación, es mejor utilizar la "forma polar" para completar la división de números complejos, como veremos más adelante. Pero, tomando la forma rectangular como ejemplo, encontremos el valor del vector A dividido por el valor del vector B.

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/6.png) 

#### La conversión entre la forma rectangular y forma polar

En la forma rectangular podemos expresar un vector en términos de sus coordenadas rectangulares, siendo el eje horizontal de su eje real y el eje vertical siendo su eje imaginario o j-componente. En forma polar estos ejes real e imaginaria son simplemente representados por " Un ∠θ ". Luego, utilizando el ejemplo anterior, la relación entre la forma rectangular y forma polar se puede definir como.

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/7.png) 

También podemos convertir de nuevo de forma rectangular a la forma polar de la siguiente manera.

#### Convertir la Forma rectangular en forma polar, (R → P)

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/8.png) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/9.png) 

#### La multiplicación en forma polar
![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/12.png) 

#### División en forma polar

Forma rectangular es mejor para sumar y restar números complejos como vimos más arriba, pero la forma polar es a menudo mejor para multiplicar y dividir. Para multiplicar juntos dos vectores en forma polar, debemos multiplicar por primera vez juntos los dos módulos o magnitudes y luego sumar sus ángulos.

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/13.png) 


### 3.	LISTA DE COMPONENTES

| Cantidad | Componentes | 
| -------- | ----------- | 
| 1 |Calculadora cientifica| 

 
> (Herramientas utilizadas en simulación) 
> Simulador thinkercad


### 5.	EXPLICACIÓN


__5.1__ Transforme a su forma polar:

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/14.png) 

__5.2__ Transforme a su forma rectangular:

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/15.png) 

__5.3__ Realice las siguientes operaciones paso a paso, y represente el resultado tanto en su
forma rectangular como en su forma polar.

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/16.png) 

__5.4__ Resuelva las operaciones anteriores por medio de la calculadora y compare
resultados.

Transforme a su forma polar:

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/31.jpg) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/32.jpg) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/33.jpg) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/34.jpg)

Transforme a su forma rectangular:

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/35.jpg) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/36.jpg) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/37.jpg) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/38.jpg) 

Realice las siguientes operaciones paso a paso, y represente el resultado tanto en su
forma rectangular como en su forma polar.

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/20.png) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/21.png) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/22.png) 


__5.5__ Tabulacion de los datos

__5.5.1__ Resultados obtenidos de Transforme a su forma polar y su error porcentual:

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/17.png) 

Tabla 1

__5.5.2__ Resultados obtenidos de Transforme a su forma rectangular y su error porcentual:

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/18.png) 

Tabla 2

__5.5.3__ Resultados obtenidos de realice las siguientes operaciones paso a paso, y represente el resultado tanto en su
forma rectangular como en su forma polar y su error porcentual:

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/19.png) 

Tabla 3






### 5.	 DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

 - Tener a la claculadora en en el modo RPD para hacer los calculos con numeros imaginarios
 - Configurar para que tenga cuatro digitos (Opcional)

 
### 6.	APORTACIONES

 - Hay grandes diferencias en calculadoras en online, pero no en calcladoras cientificas
 
 
### 7.	CONCLUSIONES
 - Al resolver los fasores de forma anl{itica no hubo diferencias con el valor calculado con la calculadora debido a que si existe control sobre la cantidad de los numeros decimales que va a tener el operador.


### 9.	BIBLIOGRAFÍA

[1] MOLINA, A. and VEGA, F., 2021. 1.2 FASORES - Análisis de Circuitos II. [online] Sites.google.com. Available at: <https://sites.google.com/site/analisisdecircuitosupaep/senoides-y-fasores/1-2-fasores> [Accessed 9 February 2021].


### 10.	 ANEXOS

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/23.png) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/24.png) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/25.png) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/26.png) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/27.png) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/28.png) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/29.png) 

![](https://github.com/SanchezMaiAndresSebastian/Informe-de-Lab-4/blob/main/Fotos/30.png) 

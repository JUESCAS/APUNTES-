# Transformada de laplace 
Cuando se habla de dinámica de sistemas, se hace referencia una serie de conceptos que describen una forma de analizar, modelar y solucionar sistemas cuyas variables cambian continuamente en el tiempo. Al referirse a una variación en el tiempo, matemáticamente es posible relacionarlo con una derivada, por lo que para llevar a cabo la solución de un sistema dinámico es importante identificar y manejar de manera eficiente las ecuaciones diferenciales.
Cuando se pretende hallar la solución para una ecuación diferencial, la transformada de Laplace es una herramienta que simplifica el proceso ya que, al cambiar el dominio del tiempo al dominio de Laplace, la complejidad de operar derivadas se reducirá a expresiones algebraicas, que gracias a las fracciones parciales no tendrán mayor dificultad para ser operadas, sin embargo  cuando se emplea la transformada de Laplace es importante tener en cuenta que cuando obtenga  el valor deseado es necesario aplicar la transformada inversa, para devolver al dominio del tiempo el valor de la incógnita.
##  1.Sistemas
>🔑Un sistema es un conjunto de elementos que se relacionan y actúan de manera organizada y lógica con el fin de llevar a cabo un propósito. Un sistema no es necesariamente una estructura, ya que un sistema tambien se puede concebir de manera intangible, siempre y cuando sea posible distinguir sus componentes interrelacionados mediante reglas o principios.
###  1.1Sistemas lineales
Son aquellos en los que las relaciones entre las variables de entrada y salida son lineales. Es decir, siguen principios de aditividad y homogeneidad.
###  1.2Sistemas no lineales
Son aquellos en los que las relaciones entre las variables de entrada y salida no son lineales. Estos sistemas pueden mostrar comportamientos complejos como caos o bifurcaciones.
##  2.Sistemas dinamicos 
>🔑Un sistema dinámico es un concepto que describe la evolución de un sistema con respecto al tiempo según una serie de reglas o principios específicos. Un sistema dinámico está determinado por un conjunto de ecuaciones que describen el cambio las variables del sistema a medida que pasa el tiempo. Los sistemas dinámicos pueden mostrar una variedad de comportamientos, desde movimientos predecibles y simples, hasta comportamientos caóticos y complejos. 
### 2.2.Modelos dinámicos
>🔑Un modelo dinámico es una representación matemática que describe cómo evoluciona con el tiempo un sistema especifico. La representación matemática que permite modelar y relacionar las variables de un sistema son las ecuaciones diferenciales, sin embargo, es importante tener en cuenta que para constituir un modelo dinámico es un modelo dinámico se deben definir claramente las variables y las condiciones iniciales.
### 2.3.influencia de parametros
En un sistema dinámico, los parámetros pueden tener un impacto significativo en el comportamiento del sistema, influenciando aspectos como la oscilación sinusoidal o el decaimiento exponencial. Estos dos comportamientos son comunes en muchos sistemas físicos, biológicos y de ingeniería.
#### 2.3.1 Comportamiento sinusoidal 
>🔑El comportamiento sinusoidal es característico de sistemas que oscilan de manera periódica, como un péndulo o un oscilador armónico simple. La oscilación sinusoidal se produce cuando una cantidad varía cíclicamente, siguiendo una función seno o coseno en función del tiempo.
<img src="images/EXP.jpg"  width="300"/>

Figura 1

#### 2.3.2 Decaimiento exponencial 
>🔑El decaimiento exponencial es un comportamiento común en sistemas que experimentan fricción, resistencia o amortiguamiento, donde la amplitud de las oscilaciones o la magnitud de la variable disminuye exponencialmente con el tiempo.

<img src="images/EXPP.png" alt="Foto de ejemplo" width="300"/>

Figura 2

##  3.Ecuaciones diferenciales 
>🔑Una ecuación diferencial es una ecuación que involucra una o más derivadas de una función desconocida, la solución de una ecuación diferencial es una función o un conjunto de funciones que satisface dicha ecuación. Las ecuaciones diferenciales son esenciales para describir cómo cambian las variables de manera precisa y detallada. Los sistemas que pueden describir una ecuación diferencial son múltiples, por ejemplo, el movimiento de un objeto, la propagación de una enfermedad, el crecimiento de una población o la evolución de un mercado económico.
### 3.1 Derivada 
>🔑La derivada es un concepto fundamental en cálculo que describe el cambio instantáneo de una función con respecto a una de sus variables es decir que es una forma de medir la variación entre dos puntos. la derivada es una herramienta que evaluar el cambio instantáneo de una función con respecto a una de sus variables. A través de la derivada, podemos obtener información crucial sobre el comportamiento de una función, como la pendiente de una curva, la velocidad de un objeto, y la tasa de cambio de cualquier variable.La derivada juega un papel fundamental en las ecuaciones diferenciales, ya que estas ecuaciones describen cómo cambia una variable con respecto al tiempo o a otra variable.

<img src="images/DER.jpg" alt="Foto de ejemplo" width="300"/>

Figura 3

### 3.2 Caracteristicas de una ecuacion diferencial 
Las ecuaciones diferenciales se pueden clasificar según su linealidad y variabilidad en diferentes tipos que afectan la forma en que se resuelven y el comportamiento que tienen las soluciones.
#### 3.2.1 Linealidad 
La linealidad se refiere a la forma en que las soluciones y sus derivadas aparecen en la ecuación. Una ecuación diferencial es lineal si las incógnitas y sus derivadas aparecen de forma lineal, es decir, no están multiplicadas entre sí ni elevadas a potencias mayores que 1.
#### 3.2.2 Variabilidad
La variabilidad en las ecuaciones diferenciales se refiere a cómo cambian los coeficientes y las funciones que acompañan a las derivadas de las incógnitas. Las ecuaciones pueden ser constantes o variables dependiendo de si los coeficientes y términos varían o no con respecto a la variable independiente.
##  4.Transformada de Laplace
>🔑La Transformada de Laplace es una herramienta matemática utilizada para convertir ecuaciones diferenciales, que son difíciles de resolver en el dominio del tiempo, en ecuaciones algebraicas más sencillas de manejar. Es especialmente útil en el análisis de sistemas dinámicos, circuitos eléctricos, control de sistemas, y muchas áreas de la ingeniería y la física.La transformada de Laplace convierte funciones en el dominio del tiempo f(t) en funciones en el dominio complejo F(t).

 <img src="images/TRALP.jpg" alt="Foto de ejemplo" width="300"/>

Figura 4

### 4.1 propiedades de la transformada de Laplace 
#### 4.1.1 linealidad
La transformada de Laplace es una operación lineal. Esto significa que se puede aplicar a una combinación lineal de funciones.
#### 4.1.2 Desplazamiento en t
Si la función  está desplazada en el tiempo, es decir, si aparece un término t−a, la transformada de Laplace se ve afectada por un factor exponencial.
#### Desplazamiento en s
se refiere a cómo la Transformada de una función cambia cuando se aplica un desplazamiento en el tiempo de la función original. Este desplazamiento en el tiempo afecta la variable s en el dominio de Laplace.
#### 4.1.3 Escalamiento en t 
Si la función es escalada en el tiempo, es decir, si la función depende de at (donde aaa es una constante positiva), la transformada de Laplace se ajusta de la siguiente manera
#### 4.1.4 ransformado escalón unitario 
Si la función escalón unitario está desplazada, es decir, comienza en 𝑡=𝑎
t=a (en lugar de en t=0), se denota como $$𝑢(t-𝑎)$$ , y la transformada de Laplace de esta función desplazada es:

<img src="images/TRU.jpg"  width="500"/>

Figura 5

<img src="images/UNI.jpg"  width="300"/>

Figura 6

#### 4.1.5 Transformada función rampa
La transformada de Laplace de esta función rampa se puede calcular utilizando la fórmula estándar de la transformada de Laplace para una función de la forma $$t^n$$

<img src="images/TN.png"  width="300"/>

Figura 7

#### 4.1.6 Transformada de la derivada 
La transformada de Laplace de la derivada de una función es una propiedad fundamental que se utiliza frecuentemente para resolver ecuaciones diferenciales

<img src="images/TRDER.png" alt="Foto de ejemplo" width="400"/>

Figura 8

#### 4.1.7 Transformada de la integral
La transformada de Laplace de una integral puede calcularse utilizando una propiedad importante de las transformadas de Laplace. Si tenemos una función.

<img src="images/INTR.png" alt="Foto de ejemplo" width="300"/>

Figura 9

## 4.2 Transformada inversa de Laplace 
Es el proceso mediante el cual podemos obtener en el dominio del tiempo a partir de su representación en el dominio de Laplace. Para obtener la transformada inversa se deben descomponer en fracciones parciales la expresión a calcular.
## 5.Descomposición en fracciones parciales
es un método que se utiliza para simplificar fracciones racionales, es decir, fracciones donde el numerador como el denominador son polinomios.
#### 5.1 Raices reales y diferentes 
cuando se factoriza del denominador y su resultado da factores cuyas raices son reales, se lleva a cabo de la siguiente manera.

$$F(s) = \frac{G(s)}{H(s)} = \frac{G(s)}{(s + p_1)(s + p_2) \dots (s + p_n)}$$

$$F(s)=\frac{A}{(S+p_1)}+\frac{B}{(S+p_2)}+....\frac{n}{(S+p_n)}$$

$$F(s) = A (s + p_1)(s + p_{n-1}) + A (s + p_2)(s + p_{n-1}) + \dots + N (s + p_n)(s + p_n)$$

## 6. 📚Ejercicios
###  📚Ejercicio 1
$$\\frac{2s+7}{s^2 - 4s - 45}\$$
$$\\frac{2s+7}{(s-9)(s+5)}\$$
$$\\frac{2s+7}{(s-9)(s+5)} = \frac{A}{s-9} + \frac{B}{s+5}\$$
$$\\ 2s + 7 = A(s + 5) + B(s - 9)\$$
$$\\ 2s + 7 = As + 5A + Bs - 9B$$
$$\\begin{cases} 
A + B = 2 \\
5A - 9B = 7
\end{cases}\
$$
$$\\ A = -B - 2\$$
$$\\ 5(-B - 2) - 9B = 7\$$
$$\\ -5B - 10 - 9B = 7\$$
$$\\ B= \frac{7+10}{4}\$$
$$\\ B = \frac{-17}{4}\$$
$$\\ A = -\left(\frac{-17}{4}\right) - 2\$$ 
$$\\ A = \frac{9}{4}\$$
$$\\frac{9}{4(s-9)} - \frac{17}{4(s+5)}\$$
$$\mathcal{L}^{-1}\left[\frac{9}{4(s-9)} + \frac{17}{4(s+5)}\right]$$
$$\frac{9}{4} e^{9t} + \frac{17}{4} e^{-5t}$$




ejercicio obtenido de open AI

###  📚Ejercicio 2
$$\\frac{4s - 2}{s^3 - s^2 - 2s}\$$
$$\\frac{4s - 2}{s(s^2 - s - 2s)}\$$
$$\\frac{4s - 2}{s(s - 2)(s + 1)}\$$
$$\\frac{A}{s} + \frac{B}{s - 2} + \frac{C}{s + 1}\$$
$$\ 4s - 2 = A(s - 2)(s + 1) + B(s)(s + 1) + C(s)(s - 2) \$$
$$\ 4s - 2 = A(s^2 - s - 2) + B(s^2 + s) + C(s^2 - 2s)\$$
$$\ 4s - 2 = As^2 - As - 2A + Bs^2 + Bs + Cs^2 - 2Cs\$$
$$\\begin{cases}
A + B + C = 0\\
-A + B - 2C = 4\\
-2A = -2
\end{cases}\$$
$$\ A = 1\$$
$$\ C = -1 - B\$$
$$\ -A + B - 2(-1 - B) = 4\$$
$$\ 1 + B + 2 + 2B = 4\$$
$$\ B = 1\$$
$$\ C = -2\$$
$$\\frac{1}{s} + \frac{1}{s - 2} - \frac{2}{s + 1}\$$
$$\mathcal{L}^{-1}\left[\frac{1}{s} + \frac{1}{s-2} - \frac{2}{(s+1)}\right]$$
$$1 + e^{2t} + \frac{1}{2} e^{-t}$$

ejercicio obtenido de open AI

## 7. Conclusiones 
la transformada de laplace es una tecnica que al pasar del dominio del tiempo al dominio de laplace o la frecuencia nos permite simplificar operaciones que contienen derivadas de una funcion a operar simplemente con con expresiones algebraicas que al descomponerlas en fracciones parciales y la transformada inversa es posible obtener la funcion que estamos hallando. tambien cabe agregar la importancia del modelamiento mediante ecuaciones diferenciales ya que permite entender cual es el comportamiento del sistema analisar y plantear graficas que nso permitan llevar a cabo diferentes analisis.
## 8. Referencias 
[ChatGPT] (https://openai.com/chatgpt)

[Lidefer] (https://fjferrer.webs.ull.es/Apuntes3/Leccion01/15_dinmica_de_los_sistemas_ambientales.html)

[instituto de tecnologia educativas] (https://www.lifeder.com/transformada-de-laplace/)

[paunero] (https://paunero.com/)

[Noemi Lizarraga] (https://www.youtube.com/watch?v=Dk8VOlD4YEE&list=PL4yTVi9hqRwW0mDV8WqOC_B_svD2-OJl9)

[Marco Ayala] (https://www.youtube.com/watch?v=DQo9BZXF3ew)

[platzi] (https://platzi.com/tutoriales/1320-ecuaciones/8937-transformada-de-laplace-de-la-derivada-de-una-funcion-pvi-repaso/)

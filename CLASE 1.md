# Transformada de laplace 
Cuando se habla de dinámica de sistemas, se hace referencia una serie de conceptos que describen una forma de analizar, modelar y solucionar sistemas cuyas variables cambian continuamente en el tiempo. Al referirse a una variación en el tiempo, matemáticamente es posible relacionarlo con una derivada, por lo que para llevar a cabo la solución de un sistema dinámico es importante identificar y manejar de manera eficiente las ecuaciones diferenciales.
Cuando se pretende hallar la solución para una ecuación diferencial, la transformada de Laplace es una herramienta que simplifica el proceso ya que, al cambiar el dominio del tiempo al dominio de Laplace, la complejidad de operar derivadas se reducirá a expresiones algebraicas, que gracias a las fracciones parciales no tendrán mayor dificultad para ser operadas, sin embargo  cuando se emplea la transformada de Laplace es importante tener en cuenta que cuando obtenga  el valor deseado es necesario aplicar la transformada inversa, para devolver al dominio del tiempo el valor de la incógnita.
##  Sistemas
Un sistema es un conjunto de elementos que se relacionan y actúan de manera organizada y lógica con el fin de llevar a cabo un propósito. Un sistema no es necesariamente una estructura, ya que un sistema tambien se puede concebir de manera intangible, siempre y cuando sea posible distinguir sus componentes interrelacionados mediante reglas o principios.
##  Sistemas lineales
Son aquellos en los que las relaciones entre las variables de entrada y salida son lineales. Es decir, siguen principios de aditividad y homogeneidad.
##  Sistemas no lineales
Son aquellos en los que las relaciones entre las variables de entrada y salida no son lineales. Estos sistemas pueden mostrar comportamientos complejos como caos o bifurcaciones.
##  Sistemas dinamicos 
Un sistema dinámico es un concepto que describe la evolución de un sistema con respecto al tiempo según una serie de reglas o principios específicos. Un sistema dinámico está determinado por un conjunto de ecuaciones que describen el cambio las variables del sistema a medida que pasa el tiempo. Los sistemas dinámicos pueden mostrar una variedad de comportamientos, desde movimientos predecibles y simples, hasta comportamientos caóticos y complejos. 
### Modelos dinámicos
Un modelo dinámico es una representación matemática que describe cómo evoluciona con el tiempo un sistema especifico. La representación matemática que permite modelar y relacionar las variables de un sistema son las ecuaciones diferenciales, sin embargo, es importante tener en cuenta que para constituir un modelo dinámico es un modelo dinámico se deben definir claramente las variables y las condiciones iniciales.
### influencia de parametros
En un sistema dinámico, los parámetros pueden tener un impacto significativo en el comportamiento del sistema, influenciando aspectos como la oscilación sinusoidal o el decaimiento exponencial. Estos dos comportamientos son comunes en muchos sistemas físicos, biológicos y de ingeniería.
#### Comportamiento sinusoidal 
El comportamiento sinusoidal es característico de sistemas que oscilan de manera periódica, como un péndulo o un oscilador armónico simple. La oscilación sinusoidal se produce cuando una cantidad varía cíclicamente, siguiendo una función seno o coseno en función del tiempo.
#### Decaimiento exponencial 
El decaimiento exponencial es un comportamiento común en sistemas que experimentan fricción, resistencia o amortiguamiento, donde la amplitud de las oscilaciones o la magnitud de la variable disminuye exponencialmente con el tiempo.
##  Ecuaciones diferenciales 
Una ecuación diferencial es una ecuación que involucra una o más derivadas de una función desconocida, la solución de una ecuación diferencial es una función o un conjunto de funciones que satisface dicha ecuación. Las ecuaciones diferenciales son esenciales para describir cómo cambian las variables de manera precisa y detallada. Los sistemas que pueden describir una ecuación diferencial son múltiples, por ejemplo, el movimiento de un objeto, la propagación de una enfermedad, el crecimiento de una población o la evolución de un mercado económico.
### Derivada 
La derivada es un concepto fundamental en cálculo que describe el cambio instantáneo de una función con respecto a una de sus variables es decir que es una forma de medir la variación entre dos puntos. la derivada es una herramienta que evaluar el cambio instantáneo de una función con respecto a una de sus variables. A través de la derivada, podemos obtener información crucial sobre el comportamiento de una función, como la pendiente de una curva, la velocidad de un objeto, y la tasa de cambio de cualquier variable.La derivada juega un papel fundamental en las ecuaciones diferenciales, ya que estas ecuaciones describen cómo cambia una variable con respecto al tiempo o a otra variable.
### Caracteristicas de una ecuacion diferencial 
Las ecuaciones diferenciales se pueden clasificar según su linealidad y variabilidad en diferentes tipos que afectan la forma en que se resuelven y el comportamiento que tienen las soluciones.
#### Linealidad 
La linealidad se refiere a la forma en que las soluciones y sus derivadas aparecen en la ecuación. Una ecuación diferencial es lineal si las incógnitas y sus derivadas aparecen de forma lineal, es decir, no están multiplicadas entre sí ni elevadas a potencias mayores que 1.
#### Variabilidad
La variabilidad en las ecuaciones diferenciales se refiere a cómo cambian los coeficientes y las funciones que acompañan a las derivadas de las incógnitas. Las ecuaciones pueden ser constantes o variables dependiendo de si los coeficientes y términos varían o no con respecto a la variable independiente.
##  Transformada de Laplace
La Transformada de Laplace es una herramienta matemática utilizada para convertir ecuaciones diferenciales, que son difíciles de resolver en el dominio del tiempo, en ecuaciones algebraicas más sencillas de manejar. Es especialmente útil en el análisis de sistemas dinámicos, circuitos eléctricos, control de sistemas, y muchas áreas de la ingeniería y la física.
### propiedades de la transformada de Laplace 
#### linealidad
La transformada de Laplace es una operación lineal. Esto significa que se puede aplicar a una combinación lineal de funciones.
#### Desplazamiento en t
Si la función  está desplazada en el tiempo, es decir, si aparece un término t−a, la transformada de Laplace se ve afectada por un factor exponencial.
#### Desplazamiento en s
se refiere a cómo la Transformada de una función cambia cuando se aplica un desplazamiento en el tiempo de la función original. Este desplazamiento en el tiempo afecta la variable s en el dominio de Laplace.
#### Escalamiento en t 
Si la función es escalada en el tiempo, es decir, si la función depende de at (donde aaa es una constante positiva), la transformada de Laplace se ajusta de la siguiente manera
#### Transformado escalón unitario 
#### Transformada función rampa
#### Transformada senosoidal 
#### Transformada de una funcion 
#### Transformada de la derivada 
#### Transformada de la integral
## Transformada inversa de Laplace 
Es el proceso mediante el cual podemos obtener en el dominio del tiempo a partir de su representación en el dominio de Laplace. Para obtener la transformada inversa se deben descomponer en fracciones parciales la expresión a calcular.
### Descomposición en fracciones parciales
es un método que se utiliza para simplificar fracciones racionales, es decir, fracciones donde el numerador como el denominador son polinomios.
####  Raices reales y diferentes 

##  📚Ejercicios
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
## Conclusiones 
## Referencias 


# transformada de laplace 
Cuando se pretende hacer una descomposición por fracciones parciales es importante tener en cuenta que tipo de factores están contenidos en el denominador, para este caso se abordaran otras dos posibilidades que aparecen recurrentemente a la hora de hacer la descomposición. Para el caso número dos, se establecerá como plantear las fracciones parciales, cuando al factorizar la expresión del denominador se obtiene raíces reales que son repetidas. Para el último caso, se establece un planteamiento totalmente diferente, ya que el numerador estará denotado como un sumado de dos términos donde uno de estos será coeficiente de la variable “s”, esta notación hará que sea muy probable que, a la hora de calcular la transformada inversa, la función coseno haga parte de esa expresión obtenida.

$$\\frac{4s^2 - 8s + 1}{(s + 2)(s^2 - 2s + 3)}\$$
$$\\frac{A}{s + 2} + \frac{Bs + C}{s^2 - 2s + 3}\$$
$$\ A(s^2 - 2s + 3) + (Bs + C)(s + 2)\$$
$$\ As^2 - 2As + 3A + Bs^2 + 2Bs + Cs + 2C = 4s^2 - 8s + 1\$$
$$\\begin{cases}
A + B = 4 \\
-2A + 2B + C = -8 \\
3A + 2C = 1
\end{cases}\$$
$$\ B = 4 - A \$$
$$\ C = \frac{1 - 3A}{2} \$$
$$\ -2A + 2(4 - A) + \frac{1}{2} - \frac{3}{2} A = -8 \$$
$$\ -2A + 8 - 2A + \frac{1}{2} - \frac{3}{2} A = -8 \$$
$$\\frac{-11}{2} A = \frac{-33}{2}\$$
$$\ A = 3\$$
$$\ B = 1\$$
$$\ C = \frac{1 - 3(3)}{2}\$$
$$\ C = -4\$$
$$\\frac{3}{s + 2} + \frac{s - 4}{s^2 - 2s + 3}\$$
$$\mathcal{L}^{-1}\left[\frac{3}{s+2} - \frac{s-4}{(s-1)^2 + 2}\right]$$

# ej 2
$$\\frac{4s^2 + 5s + 6}{(s + 3)(s^2 - 4s + 4)}\$$
$$\\frac{A}{s - 2} + \frac{B}{(s - 2)^2} + \frac{C}{s + 3}\$$
$$\ A(s - 2)(s + 3) + B(s + 3) + C(s - 2)^2\$$
$$\ A(s^2 + s - 6) + B(s + 3) + C(2s - 4s + 4)\$$
$$\ As^2 + As - 6A + Bs + 3B + 2Cs^2 - 4Cs + 4C\$$
$$\\begin{cases}
A + C = 4 \\
A + B - 4C = 5 \\
-6A + 3B + 4C = 6
\end{cases}\$$
$$\ A = 4 - C\$$
$$\ 4 - C + B - 4C = 5\$$
$$\ B = 5C + 1\$$
$$\ -6(4 - C) + 3(5C + 1) + 4C = 6\$$
$$\ -24 + 6C + 15C + 3 + 4C = 6\$$
$$\ 25C = 27\$$
$$\ C = \frac{27}{25}\$$
$$\ B = 5\left(\frac{27}{25}\right) + 1\$$
$$\ B = \frac{32}{5}\$$
$$\ A = 4 - \frac{27}{25}\$$
$$\ A = \frac{73}{25}\$$
$$\\frac{73}{25(s - 2)} + \frac{32}{5(s - 2)^2} + \frac{27}{25(s + 3)}\$$
$$\mathcal{L}^{-1}\left[\frac{73}{25(s-2)} + \frac{32}{5(s-2)^2} + \frac{27}{25(s+3)}\right]$$

# ej 2


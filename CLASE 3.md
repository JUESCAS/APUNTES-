# Fracciones parciales 
La descomposición por fracciones parciales es una técnica que permite expresar una fracción racional como la suma de fracciones más simples, este proceso es muy importante ya que las expresiones obtenidas pueden ser relacionadas con transformadas inversas de Laplace, que en ultimas representan la solución a la ecuación diferencial que describe el comportamiento de un sistema dinámico. A pesar de que la descomposición por fracciones parciales es muy efectiva, sin embargo, cuando obtenemos la suma de más 3 fracciones simples, los métodos tradicionales pueden resultar tediosos ya que dar soluciones a sistemas de ecuaciones 4x4 en adelante, no suele ser común.    
Como solución a este problema se planteó el concepto de método simple, cuya ventaja se basa en que n necesito conocer el valor de los otros coeficientes para hallar uno. Este método al igual que al tradicional clasifica sus posibilidades en 3 casos es decir que en el denominador de las fracciones simples podemos encontrar; reales y diferentes, reales e iguales y raíces complejas conjugados.

$$\frac{2s^3 + 5s^2 + 6s + 7}{(s-3)(s^2 + 2s + 2)}\  $$
$$\frac{A}{s-3} + \frac{Bs + C}{s^2 + 2s + 2}\$$
$$\ B s + C = \left[ \frac{2s^3 + 5s^2 + 6s + 7(s^2 + 2s + 2)}{(s - 3)(s^2 + 2s + 2)} \right] \quad \text{evaluado en} \quad s = -1+i \$$
$$\frac{2(-1+i)^3 + 5(-1+i)^2 + 6(-1+i) + 7}{(-1+i)-3} = B(-1+i) + C$$ 
$$\frac{5}{-4+i} = -B + Bi + C$$ 
$$\frac{-20}{17} - \frac{6i}{17} = -B + Bi + C$$ 
$$\frac{-20}{17} - \frac{6i}{17} = -B + Bi + C$$ 
$$\frac{-6i}{17} = Bi$$ 
$$ B = \frac{-6}{17}$$ 
$$ \frac{-20}{17} = -B + C$$ 
$$ \frac{-20}{17} = \frac{6}{17} + C$$ 
$$  C = \frac{-14}{17}$$
$$\ A = \left[ \frac{2s^3 + 5s^2 + 6s + 7}{s^2 + 2s + 2} \right] \$$
$$A = \frac{2(3)^3 + 5(3)^2 + 6(3) + 7}{(3)^2 + 2(3) + 2}$$
$$A = \frac{124}{17}$$
$$\frac{\frac{124}{17}}{s-3} + \frac{-\frac{6}{17}s - \frac{14}{17}}{s^2 + 2s + 2}$$
# eh
$$\\frac{6s^2 + 11s + 10}{(s + 2)(s^2 - 4s + 4)}\$$  
$$\\frac{A}{s - 2} + \frac{B}{(s - 2)^2} + \frac{C}{s + 2}\$$
$$\ A = \left[\frac{6s^2 + 11s + 10}{(s + 2)} \right] \quad \text{evaluado en} \quad s = 2 $$
$$\ A = \frac{6(2)^2 + 11(2) + 10}{2 + 2}\$$
$$\ A =14\$$
$$\ B = \left[ \frac{6s^2 + 11s + 10}{(s + 2)} \right] \frac{d}{ds} \quad \text{evaluado en} \quad s = 2\$$
$$\ B = \frac{(12s + 11)(s + 2) - (6s^2 + 11s + 10)}{(s + 2)^2} \Bigg|_{s = 2}\$$
$$\ B = \frac{(12(2) + 11)(2 + 2) - (6(2)^2 + 11(2) + 10)}{(2)^2 + 4(2) + 4} = \frac{21}{4}\$$
$$\ C = \left[ \frac{6s^2 + 11s + 10}{(s^2 - 4s + 4)} \right] \quad \text{evaluado en} \quad s = 2\$$
$$\ C = \frac{6(-2)^2 + 11(-2) + 10}{((-2)^2 - 4(-2) + 4)}\$$  
$$\ C= \frac{3}{4}\$$


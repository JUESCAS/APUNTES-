# Corrección del parcial 
$$ \ F(s) = \frac{6s}{(s - \frac{5}{2})(s^2 + 4s + 8)}\$$
$$ \ F(s) = \frac{A}{s - \frac{5}{2}} + \frac{Bs + C}{s^2 + 4s + 8}\$$
$$ \ A = \left[ \frac{6s}{(s - \frac{5}{2})(s^2 + 4s + 8)} \cdot \left( s - \frac{5}{2} \right) \right] \Bigg|_{s = \frac{5}{2}}\$$
$$ \ A = \frac{6 \left( \frac{5}{2} \right)}{\left( \frac{5}{2} \right)^2 - 4 \left( \frac{5}{2} \right) + 8}\$$
$$ \ A = \frac{60}{17}\ $$

$$ \ Bs + C = \left[ \frac{6s}{(s - \frac{5}{2})(s^2 + 4s + 8)} \cdot (s^2 + 4s + 8) \right] \Bigg|_{s = -2 + 2i}\$$
$$\ Bs + C = \frac{6(-2 + 2i)}{-2 + 2i - \frac{5}{2}}\$$
$$\ -2B + 2Bi + C = \frac{312}{97} - \frac{120}{97}i\$$
$$\ -2Bi = -\frac{120}{97}i \$$
$$\ B = \frac{60}{97}\$$
$$\ C = \frac{312}{97} + 2 \left( \frac{60}{97} \right)\$$
$$\ C = \frac{432}{97}\$$
$$\ F(s) = \frac{\frac{60}{17}}{s - \frac{5}{2}} + \frac{\frac{60}{97}s + \frac{432}{97}}{s^2 + 4s + 8}\$$
$$\ f(t) = \mathcal{L}^{-1} \left[ \frac{\frac{60}{17}}{s - \frac{5}{2}} + \frac{\frac{60}{97}s + \frac{432}{97}}{(s + 2)^2 + 4} \right]\$$
$$\ f(t) = \frac{60}{97} e^{-2t} \cos(2t) + \frac{432}{97} e^{-2t} \sin(2t) \$$

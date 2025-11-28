$$
y_1 = e^{-\frac{b}{2a}x}
$$
The other root, $y_2$ must not be a constant multiple of $y_1$
$$
y_2 = v(x)e^{-\frac{b}{2a}x}
$$
$$
y_2' = v'(x)e^{-\frac{b}{2a}x}
	   -\frac{b}{2a} v(x)e^{-\frac{b}{2a}x}
$$
$$
y_2'' =
v''(x)e^{-\frac{b}{2a}x}
-\frac{b}{2a}v'(x)e^{-\frac{b}{2a}x}
-\frac{b}{2a}v'(x)e^{-\frac{b}{2a}x}
+\frac{b^2}{4a^2}v(x)e^{-\frac{b}{2a}x}
$$
Substitute into the original equation: 
$$
ay'' + by' + cy = 0
$$
$$
av''(x)e^{-\frac{b}{2a}x}
-a\frac{b}{2a}v'(x)e^{-\frac{b}{2a}x}
-a\frac{b}{2a}v'(x)e^{-\frac{b}{2a}x}
+a\frac{b^2}{4a^2}v(x)e^{-\frac{b}{2a}x}
+bv'(x)e^{-\frac{b}{2a}x}
-b\frac{b}{2a} v(x)e^{-\frac{b}{2a}x}
+ c v(x)e^{-\frac{b}{2a}x}
= 0
$$

Simplify:
$$
av''(x)e^{-\frac{b}{2a}x}
-\frac{b}{2}v'(x)e^{-\frac{b}{2a}x}
-\frac{b}{2}v'(x)e^{-\frac{b}{2a}x}
+\frac{b^2}{4a}v(x)e^{-\frac{b}{2a}x}
+bv'(x)e^{-\frac{b}{2a}x}
-\frac{b^2}{2a} v(x)e^{-\frac{b}{2a}x}
+ cv(x)e^{-\frac{b}{2a}x}
= 0
$$

Combine like terms:
$$
av''(x)e^{-\frac{b}{2a}x}
-\frac{b^2}{4a}v(x)e^{-\frac{b}{2a}x}
+ cv(x)e^{-\frac{b}{2a}x}
= 0
$$
Factor:
$$
e^{-\frac{b}{2a}x}
\left[
a v''(x)
+ \left(c - \frac{b^2}{4a}\right)v(x)
\right]
= 0
$$
Since $e^{-\frac{b}{2a}x}\neq 0$:
$$
a v''(x)
= \left(\frac{b^2}{4a} - c\right)v(x)
$$
Multiply by $4a$:
$$
4a^2 v''(x) = (b^2 - 4ac)\, v(x)
$$
For repeated roots, $b^2 - 4ac = 0$:
$$
4a^2 v''(x) = 0
$$
Thus:
$$
v''(x) = 0
$$
Integrating:
$$
v'(x) = p
$$
$$
v(x) = px + q
$$
Final form:
$$
y_2 = (px + q)e^{-\frac{b}{2a}x}
$$
The general solution of the differential equation is: 
$$
y = c_1y_1+c_2y_2 
$$
$$y=c_1e^{-\frac{b}{2a}x} + c_2(px+q)e^{-\frac{b}{2a}x}$$
This could be rearranged and simplified into: 
$$y = (Ax+B)e^{-\frac{b}{2a}x}$$

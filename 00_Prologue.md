## Exercises

 - Derive Snell's law: $sin \theta_{w} / sin \theta_{a} = c_{w}/c_{a} < 1$, where $c_{w}$ and $c_{a}$ denote the speed of light in water and air, respectively.
 - Suppose the ant is outside a hemispherical bowl and the drop of honey is inside the bowl directly across from her. Find the shortest distance.
 - What happens if the ant can crawl faster on the outside of the glass than on the inside? 

## Solutions

### 1 Snell's law
Assume without loss of generality to use a coordinate system where the air-water interface lies along the $x$ axis ($y=0$).
Let be given two points>: 
 - $P=(a,b)$ in the upper (air) zone and 
 - $R=(A,B)$ in the lower (water) zone. 
Consider a light ray starting in air at $P$, traversing the air-water interface at $Q=(x,0)$ and continuing in water down to $R$, and the vertical axis at $Q$, and define: 
 - $\theta_{a}$ the angle made with the axis by the $\overline{PQ}$ segment, and
 - $\theta_{w}$ the angle made with the axis by the $\overline{QR}$ segment.

The times it takes for light to travel the two segments are, respectively
 - $t_{a}(x) =\left|\overline{PQ}\right| / c_{a} = \sqrt{(x-a)^{2} + b^{2}}/ c_{a}$
 - $t_{w}(x) =\left|\overline{QR}\right| / c_{w} = \sqrt{(A-x)^{2} + B^{2}}/ c_{w}$ 
The value of $x$ determines the relative length of the two segments along which light travels at different speeds, thus determining the total time $t(x) = t_{a}(x) + t_{w}(x)$. If this is to be the minimum possible time, then 
$$ \frac{dt_{a}}{dx} + \frac{dt_{w}}{dx} = 0$$
Recalling that $\frac{d \sqrt{x^{2}}}{dx} = \frac{2x}{2\sqrt{x^{2}}} = \frac{x}{\sqrt{x^{2}}}$ we obtain
$$ \frac{dt_{a}}{dx} = \frac{(x-a)}{c_{a} \sqrt{(x-a)^{2} + b^{2}}} = \frac{(A-x)}{c_{w}\sqrt{(A-x)^{2} + B^{2}}}  = - \frac{dt_{w}}{dx}$$
The two fractions in the middle of the previous equation can be rewritten in more geometrical terms as follows:
$$\frac{1}{c_{a}}\frac{(x-a)}{\left|\overline{PQ}\right|} = \frac{1}{c_{w}}\frac{(A-x)}{\left|\overline{QR}\right| }  $$
But now the two innermost fractions are just the sine of angles $\theta_{a}$ and $\theta_{w}$ made by the light ray with the vertical axis in the upper and lower media, respectively. hence

$$\frac{\sin \theta_{a}}{c_{a}} = \frac{\sin \theta_{w}}{c_{w}} $$

Stated in this form the law can be easily interpreted as saying that $\sin \theta$ -- hence the light path projection parallel to the interface -- must be greater in the zone (air) where the light speed is greater. Instead, light makes a smaller angle with the vertical axis in the zone (water) where the velocity is smaller. 

### 2 Ant in a hemispherical bowl
Let say the bowl is half a sphere of radius $R$ and assume the ant being  

### 3



<!--stackedit_data:
eyJoaXN0b3J5IjpbLTc2MTk2MDQxNF19
-->
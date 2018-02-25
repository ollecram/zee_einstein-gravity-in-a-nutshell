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
Let say the bowl is half a sphere of radius $R$ and assume the ant being located at latitude $\theta$ from the border, on the $\phi=0$ meridian, where $0 \leq \theta \leq \pi/2$ and $0 \leq \phi \leq 2 \pi$.

The shortest path length $l$ is twice the distance of the ant from the bowl border along the meridian, thus 
$$l = 2 R \theta$$

This is because the infinitesimal squared path length on a sphere is $ds^{2} = R^{2} (d\theta^{2} + \sin^2\!\theta d\phi^{2})$. In order to reach the point opposite to her in the internal face of the hemisphere, the ant cannot avoid reaching the border, thus covering a latitude excursion of $\theta$ twice: going up to the border then down from it. Any deviation $d\phi$ from the $\phi=0$ meridian where it is initially located would need to be compensated by an equal and opposite one in order to reach the target point, thus increasing the path length increase by an amount  $ds^{2} = 2 R^{2} \sin^2\!\theta d\phi^{2}$.

The whole argument can be simplified and made more general by assuming that the external and internal face of the bowl can be separated and the space in between  inflated to make the hemisphere into the external surface of a sphere. The sphere equatorial circle would map the border of the former hemisphere. The problem can be rephrased as follows: 
> The ant located somewhere below the equatorial circle on a sphere of radius $R$ must reach a symmetric point above the equator. What is the shortest path?

The answer being, in general terms: 

> The shortest path on a sphere between two points is the shortest of
> the two circular segments in which the two points divide the unique
> circle of radius $R$ containing those points. 

Specifically, given that the starting and arrival points are mirroring each other with respect to the equatorial circle, they lie on the same meridian at equal distances (hence latitude $\theta$) from the equator. The shortest path length (separating distance) between them is therefore $l = 2 R  \theta$. 

### 3 Ant crawling faster on the outside of a bowl
Given that the inside and outside paths are identical and that each one is separately the shortest path on the corresponding side of the surface there is nothing that can be gained. 
Let now map the external and internal surfaces of the hemisphere into the external surface of a sphere, as we did in the previous exercise. In order to to exploit analogies with the Snell's law let us define some geometric objects on the sphere surface:
 - A circle $C_{p}$ is a set of points at an equal distance from a given point $p$. 
 - For any  $C_{p}$ there exists a unique point $P \ne p$ such that $C_{p}=C_{P}$. [A circle can therefore be also indicated as $C_{[p,P]}$ and the points $p$ and $P$ may be referred to as the circle's *poles*].
 - Any circle divides the sphere surface into two sets $H_{p}$ and $H_{P}$ such that $p \in H_{p}$ and $P \in H_{P}$ whose intersection is the circle itself. 
 - There exist *maximum length* circles (*great circles* or *meridians*), their length being $2\pi R$  .   
 -  For a given maximum length circle $C^{max}_{[p,P]}$ the two sets $H_{p}$ and $H_{P}$  have equal area $2\pi R^{2}$ 
 - An infinite number of circles contain two distinct points $a \ne b$ , one of which is a great circle. [If one regards the sphere as immersed in three-dimensional space a great circle is contained in the unique plane that also contains the sphere's center].  
 - An infinite number of maximum length circles (meridians) contain the poles $p$ and $P$ associated to a given circle $C_{[p,P]}$

Following the exercise's question, let assume the sphere surface to be separated by a circle $C_{[N,S]}$ into the parts $H_{N}$ and $H_{S}$. Let also assume that portions of any path contained in $H_{N}$ is run across at velocity $c_{a}$ (light velocity in air) while those contained in $H_{S}$ is run across at velocity $c_{w}$ (light velocity in water) . 
Clearly the circle $C_{[N,S]}$ has a role in the problem analogous to the one played by the air-water interface (a straight line) in the derivation of Snell's law. 
Let now consider the (infinite) maximum length circles (*meridians*) passing through the points $N$ and $S$ (*poles*) associated with the circle. 
Before tackling a general solution let us mention a special case: 
> In case the starting and arrival points of a path lie on the same
> meridian, the shortest of the two segments into which the two points
> divide the meridian is not only the ***shortest-length*** path, but
> also the ***shortest-time*** path. 

The justification for the above assertion should be obvious, namely it is that no matter how large the jump in velocity occurring at the separation between the low and high velocity zones, moving the point away from the meridian increases the path length in both zones.     
There is nothing in this special case that is due to working on the surface of a sphere. In fact there is a perfectly analogous situation in the flat geometry of Snell's law when $\theta_{a} = \theta_{w} = 0$. In that case the *shortest-time* path joining two points which are mirroring each other from opposite sides with respect to the air-water interface is the straight line segment (*shortest-length* path) joining them and orthogonal to the interface.  

In order derive the analogous of Snell's law on the sphere let us accurately state our problem:

 1. Our coordinate system on the sphere is determined by the poles $N$ and $S$ of the $C_{[N,S]}$ circle (not necessarily a great circle) which is the boundary separating the northern high-speed zone ($H_{N}$) from the southern low-speed zone ($H_{S}$).
 2.  The starting point $P \in H_{N}$ is located somewhere in the northern hemisphere. 
 3. The great circle containing $N$, $P$ and $S$ is assigned longitude $\phi_{P}=0$.   
 4. The arrival point $R \in H_{S}$ is located somewhere in the southern hemisphere. 
 5. Let $\phi_{R}$ be the longitude of $R$.   
 6. A light path from $P$ crosses the $C_{[N,S]}$ circle at a point $Q$ from which it continues toward $R$. 
 7.   Let $\phi_{Q}$ be the longitude of $Q$ satisfying  $0 = \phi_{P} \leq \phi_{Q} \leq \phi_{R}$.
 8. Each of the shortest-length paths $\widehat{PQ}$ and $\widehat{QR}$ is a  portion of the unique geodesic (great circle) defined by the corresponding pair of points. 

With the above specifications the problem can be solved by finding the longitude $\phi_{Q}$ of $Q$ ($0 = \phi_{P} \leq \phi_{Q} \leq \phi_{R}$) minimizing the total light time $t_{PR} = t_{PQ} + t_{QR}$, where
$$ t_{PQ} = \frac{\left |\widehat{PQ} \right |}{c_a} = \int^{\phi_{Q}}_{0}dl(\phi)d\phi$$
$$ t_{QR} = \frac{\left |\widehat{QR} \right |}{c_w} = \int^{\phi_{R}}_{\phi_{Q}}dl(\phi)d\phi$$

The function $dl(\phi)$ gives the incremental path length associated to an increase of longitude $d\phi$. By solving the minimum problem we expect to obtain a relation analogous to Snell's law, thus involving 
 - the angles $\theta_{a}$ and $\theta_{w}$ that the light rays make with the meridian intersecting the interface $C_{[N,S]}$ circle at a point $Q$, and
 - the light speeds in air ($c_a$) and in water ($c_w$).

The problem which we are left with is to find an explicit expression for 
$dl(\phi)$. Note that this expression must fulfill two requirements:

 1. The general expression for the path length differential on the sphere, with longitude coordinate $\phi$ and latitude coordinate $\theta$ is: $dl^2=R^2(d\theta^2+\cos^2 \!\theta d\phi^2)=R^2 \left( \frac{d\theta}{d\phi}^2 + \cos^2\!\theta(\phi) \right) d\phi^2$;
[$\theta$ is not the spherical coordinate, hence $\cos^2 \!\theta$ instead of $\sin^2 \!\theta$].
 3. By an increase $d\phi$ the $\theta$ coordinate also generally changes. Therefore, in order to evaluate the integrals in closed form one should determine the function $\theta (\phi)$ subject to the requirement that the path follow a geodesic (great circle). Alternatively, one could use $\theta$ as the independent variable. 

A closed form expression for the geodesic length between two arbitrary points on the sphere surface can be found in the following references: 
[REF1](http://www.damtp.cam.ac.uk/user/reh10/lectures/nst-mmii-handout2.pdf)
[REF2](http://campus.mst.edu/physics/courses/409/Problem-Solutions/HW#5/HW5_prob1_sphere_geodesic.pdf)
[REF3](http://vixra.org/pdf/1404.0016v1.pdf)

 #### 3.1 G

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTgzNTQ4NjEyXX0=
-->
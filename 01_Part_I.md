# Part I - From Newton to Riemann
## I.1 - Newton's Laws
### Celestial mechanics solved

$$m \ddot{\mathbf{r}} = -GMm \frac{\mathbf{r}}{r^3}$$ where $\mathbf{r} = (x, y, z)$, and $r = \sqrt{\mathbf{r} \cdot \mathbf{r}} = \sqrt{x^2 + y^2 + z^2}$

In spite of the different role played by $m$ on the left and right hand side of the equation we cancel it off from both sides, leaving
$$\ddot{\mathbf{r}} = -k \frac{\mathbf{r}}{r^3}$$ where $k \equiv GM$. 

#### Central force argument
By saying that Newton's is a ***central field***  one means that 

 - a special point exists in space (the ***field center***),
 - the ***magnitude*** of the force exerted by the field at a given point only depends on that point's distance from the center,  
 - the force ***direction*** is parallel
 -  to the segment connecting the center to that point. 

An often repeated statement says that *due to a simple "symmetry argument"* the points occupied in the course of time by a particle subject to a central force field are all contained in a plane. 

It all relates to the following more basic assumptions, namely that

 - There is no special point or direction in the space itself, so any special point or direction in the motion of a particle must be determined by some initial configuration of the particle's motion with respect to the field;
 - It is an experimental fact elevated to the status of an axiom in classical mechanics that the position and velocity of all particles at a given  instant of time fully determine their evolution. 

By combining the above two statements one sees that at a given point in time (hence forgetting any knowledge of prior dynamical history) there are two vectors (directions) related to a particle in a central field: the radius vector connecting the field center to the particle and the particle's velocity vector. 
These two vectors do determine a plane. By choosing the origin of our coordinate axes $(\mathbf{i}, \mathbf{j}, \mathbf{k})$ in the field center and the $\mathbf{k}$ axis parallel to $\mathbf{r} \times \dot{\mathbf{r}}$, both the position vector $\mathbf{r}(t_0)$ and the velocity vector $\dot{\mathbf{r}}(t_0)$ are contained in the plane $z=0$. The force field component along $\mathbf{k}$ vanishes across the whole plane, implying that the particle will never leave that plane in the course of motion. 

#### Solving the 2D differential equations
$$ \ddot{x} = -kx/r^{3} \;\;\;\;\;\;\;\;\;\;\; \ddot{y} = -ky/r^{3}$$ 
$$ x = \cos{\theta} \;\;\;\;\;\;\;\;\;\;\; y = \sin{\theta}$$ 
$$ \dot{x} = \dot{r} \cos{\theta} - r \sin{\theta} \,\dot{\theta} \;\;\;\;\;\;\;\;\;\;\; \dot{y} = \dot{r} \sin{\theta} + r \cos{\theta} \,\dot{\theta} $$ 
$$ \ddot{x} = \ddot{r} \cos{\theta} - 2 \dot{r}\sin{\theta} \,\dot{\theta} -  r \cos{\theta} \,\dot{\theta}^2 -  r \sin{\theta} \,\ddot{\theta} = -k \frac{\cos{\theta}}{r^2}$$
$$ \ddot{y} = \ddot{r} \sin{\theta} + 2 \dot{r}\cos{\theta} \,\dot{\theta} -  r \sin{\theta} \,\dot{\theta}^2 +  r \cos{\theta} \,\ddot{\theta}= -k \frac{\sin{\theta}}{r^2}$$

\begin{eqnarray}
x & = &y
z
\end{eqnarray}









<!--stackedit_data:
eyJoaXN0b3J5IjpbMTg2Mjc0OTMwMSw2NTkxMzA1MDksLTE1MT
E1NTQ4ODUsMTU0NTUzNjU3OSw2Njc1MDU3NTUsLTEyMjA0NzI2
MzMsLTE1NDc5OTcxNTQsMTI2NDk5MzgwNiwtNDA1MTc0MzAyLC
0xMjkzNTYyMjYwLDYyMzA3OTEwMSwxMzY1NTM3NDI1LDQ3NzA1
OTA0Miw1Nzc5MDUxMjNdfQ==
-->
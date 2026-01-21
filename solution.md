# Solution – Orbital Mechanics

## Laplace–Runge–Lenz Vector
a) Take the moment of apogee. Let's imagine the orbit is counterclockwise. Then $\vec{p}$ is in the $\hat{y}$ direction and $\vec{L}$ is in the $\hat{z}$ direction, and $\vec{p} \times \vec{L}$ is in the $\hat{x}$ direction. (If we imagine a clockwise orbit, the directions of both vectors are reversed and the direction of their cross product is unchanged.) 
On the other hand, $-GMm^2 \hat{r}$ is in the $-\hat{x}$ direction, so the direction of $\vec{A}$ depends on which term has greater magnitude. 
The magnitude of $\vec{p} \times \vec{L}$ is $m^2 v^2r$. If we divide each term by $m^2r^2$, we are comparing the magnitudes of $v^2/r$ and $GM/r^2$. The second of these is the gravitational acceleration felt by the particle; the first the centrifugal force on it from a momentarily co-rotating reference frame. Because the particle is at apogee, it is accelerating towards the large mass, and the gravitational acceleration is greater. This means the magnitude of the $GMm^2$ term is greater, and the direction of $\vec{A}$ is $-\hat{x}$. 


(b) $\vec{A} \cdot \vec{r} = (\vec{p} \times \vec{L}) \cdot \vec{r} - GMm^2 \hat{r} \cdot \vec{r}$. The second term dots two parallel vectors, so it becomes the product of their magnitudes. For the first term, we first exchange the order of the dot product to get $\vec{r} \cdot (\vec{p} \times \vec{L})$. Then we use the provided identity to get $(\vec{r} \times \vec{p}) \cdot \vec{L}$. But $\vec{r} \times \vec{p} = \vec{L}$, so the first term is $L^2$, and the entire dot product is $\boxed{\vec{A} \cdot \vec{r} = L^2 - GMm^2r}$. 


(c) $\vec{A} \cdot \vec{r} = Ar \cos{\theta}$. Dividing each side by $r$ and plugging in our expression for $\vec{A} \cdot \vec{r}$ from part (b), we have $A \cos{\theta} = L^2 r - GMm^2$. Solving for $\frac1r$ gives $\frac1r = \frac{GMm^2}{L^2} \left( 1+ \frac{A}{GMm^2} \cos{\theta} \right)$. So the eccentricity is $e = \frac{A}{GMm^2}$. 



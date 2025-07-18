##### Question 1
>[!Question 1]
>Evaluate the surface integral.
>$\int \int_{S} x^2yz\, dS$, $S$ is hte part of the plane $z = 1 + 2x + 3y$ that lies above the rectangle $[0,\ 4] \times [0,\ 2]$

$$
\int_{0}^4 \int_{0}^2 x^2y(1+2x+3y) \sqrt{ 1 + 4 +9 }\,\ dy\,\ dx
$$
$$
\sqrt{ 14 } \int_{0}^4 \int_{0}^2 x^2y+2x^3y+3x^2y^2\,\ dy\,\ dx
$$
$$
\sqrt{ 14 } \int_{0}^4 2x^2+4x^3+8x^2\,\ dx
$$
$$
\frac{1408\sqrt{ 14 }}{3}
$$
##### Question 2
>[!Question 2]
>Evaluate the surface integral.
>$\int \int_{S}\, x\, dS$, $S$ is the triangular region with vertices $(1,\ 0,\ 0)$, $(0,-2,\ 0)$, and $(0,\ 0,\ 18)$

$$
\vec{P} = \left< 1,\ 2,\ 0 \right> 
$$
$$
\vec{Q} = \left< 0,\ 2,\ 18 \right> 
$$
$$
\vec{n} = \vec{P} \times \vec{Q} = \left< 36,\ -18,\ 2 \right> 
$$
$$
36x-18(y+2)+2z=0
$$
$$
18x-9y-18+z=0
$$
$$
z = f(x,\ y) = 18-18x+9y
$$
$$
f_{x} = -18
$$
$$
f_{y} = 9
$$
```desmos-graph
left = -1; right = 2;
bottom = -3; top = 1;
---
y > 2x-2 |0<x<1|y<0
```
$$
D = \left\{ (x,\ y) | 0 \leq x \leq 1,\  2x - 2 \leq y \leq 0 \right\} 
$$
$$
\int_{0}^1 \int_{2x-2}^{0} x\sqrt{ 1+18^2+9^2 } \,\ dy\,\ dx
$$
$$
\sqrt{ 406 } \int_{0}^1 x(-2x+2)\,\ dx = \frac{\sqrt{ 406 }}{3}
$$

##### Question 3
>[!Question 3]
>Evaluate the surface integral.
>$\int \int_{S}\, (x^2z+y^2z)\, dS$, $S$ is the hemisphere $x^2+y^2+z^2=9$, $z\geq 0$

###### Convert to polar
Since our radius is always 3, $\rho = 3$ and we have only 2 variables
$$
\vec{r} ( \theta,\ \phi) = \left< 3\sin(\phi)\cos(\theta),\ 3\sin(\phi)\sin(\theta),\ 3\cos \phi \right> 
$$
$$
D = \left\{ (\theta,\ \phi) | 0 \leq \theta \leq 2\pi,\ 0 \leq \phi \leq \frac{\pi}{2} \right\} 
$$

$$
f(x,\ y,\ z) = x^2z+y^2z = z(x^2+y^2)
$$
$$
f(\vec{r}(\theta,\ \phi)) = 3\cos(\phi)(9\sin^2(\phi))
$$
$$
f(\vec{r}(\theta,\ \phi)) = 27\sin^2(\phi)\cos(\phi)
$$

###### Find $|\vec{r}_{\theta} \times \vec{r}_{\phi}|$
$$
\vec{r}_{\theta} = \left< -3\sin(\phi)\sin(\theta),\ 3\sin(\phi)\cos(\theta),\ 0 \right> 
$$
$$
\vec{r}_{\phi} = \left< 3\cos(\phi)\cos(\theta),\ 3\cos(\phi)\sin(\theta),\ -3\sin(\phi) \right> 
$$
$$
\vec{r}_{\theta} \times \vec{r}_{\phi} = \left< 
-9\sin^2(\phi)\cos(\theta),\ 
-9\sin^2(\phi)\sin(\theta),\ 
-9\sin(\phi)\cos(\phi)\sin^2(\theta) - 9\sin(\phi)\cos(\phi)(\cos^2(\theta))

\right> 
$$

$$
\vec{r}_{\theta} \times \vec{r}_{\phi} = \left< 
-9\sin^2(\phi)\cos(\theta),\ 
-9\sin^2(\phi)\sin(\theta),\ 
-9\sin(\phi)\cos(\phi)

\right> 
$$
$$
|\vec{r}_{\theta} \times \vec{r}_{\phi}| = \sqrt{ 
81\sin^4(\phi)\cos^2(\theta) + 
81\sin^4(\phi)\sin^2(\theta) + 
81\sin^2(\phi)\cos^2(\phi)
}
$$

$$
|\vec{r}_{\theta} \times \vec{r}_{\phi}| = 9\sqrt{ 
\sin^4(\phi) +
\sin^2(\phi)\cos^2(\phi)
}
$$
$$
|\vec{r}_{\theta} \times \vec{r}_{\phi}| = 9\sqrt{ 
\sin^2(\phi) (\sin^2(\phi)+\cos^2(\phi))

}
$$
$$
|\vec{r}_{\theta} \times \vec{r}_{\phi}| = 9\sin \phi
$$
###### Integrate
$$
\int_{0}^{2\pi}\int_{0}^{\pi/2} 27\sin^2(\phi)\cos(\phi)(9\sin(\phi))\,\ d\phi\,\ d\theta
$$
$$
486\pi \int_{0}^{\pi/2} \sin^3(\phi)\cos(\phi)\,\ d\phi
$$
$$
\frac{243\pi}{2}
$$

##### Question 5
>[!Question 5]
>Evaluate the surface integral $\int \int_{S} \mathbf{F} \cdot dS$  for the given vector field $\mathbf{F}$ and the oriented surface $S$.
>In other words, find the flux of $F$ across $S$. For closed surfaces, use the positive (outward) orientation.
>$\mathbf{F}(x,\ y,\ z) = xy\mathbf{i}+yz\mathbf{j}+zx\mathbf{k}$, $S$ is the paraboloid $z = 4-x^2-y^2$ that lies above the square $0 \leq x \leq 1$, $0 \leq y \leq 1$, and has upward orientation.

Since z is a function of x and y, we can use this formula:
$$
\int \int_{S} \mathbf{F} \cdot dS = \int \int_{R} \mathbf{F}(x,\ y,\ g) \cdot \left< -g_{x},\ -g_{y},\ 1 \right> \,\ dA
$$
$$
g(x,\ y) = z = 4 - x^2 - y^2
$$
$$
g_{x} = -2x
$$
$$
g_{y} = -2y
$$
$$
\mathbf{F}(x,\ y,\ g) = \left< xy,\ y(4-x^2-y^2),\ x(4-x^2-y^2) \right> 
$$
$$
\int_{0}^1 \int_{0}^1 \left[ -xy(-2x)-y(4-x^2-y^2)(-2y)+x(4-x^2-y^2) \right] \,\ dy\,\ dx
$$


##### Question 7
>[!Question 7]
>Evaluate the surface integral $\int \int_{S} \mathbf{F} \cdot dS$  for the given vector field $\mathbf{F}$ and the oriented surface $S$.
>In other words, find the flux of $F$ across $S$. For closed surfaces, use the positive (outward) orientation.
$\mathbf{F}(x,\ y,\ z) = x\mathbf{i}+4y\mathbf{j}+3z\mathbf{k}$, $S$ is the cube with vertices $(\pm1,\ \pm1,\ \pm1)$

###### $S_{1}$
$$
x=1,\ y=y,\ z=z
$$
$$
\vec{F} = \left< 1,\ 4y,\ 3z \right> 
$$
$$
\vec{n} = \left< 1,\ 0,\ 0 \right> 
$$
$$
S_{1} = \int \int_{D} \vec{F} \cdot \vec{n}\,\ dA =
\int \int_{D}\,\ dA = 4
$$


###### $S_{2}$
$$
x=x,\ y=1,\ z=z
$$
$$
\vec{F} = \left< x,\ 4,\ 3z \right> 
$$
$$
\vec{n} = \left< 0,\ 1,\ 0 \right> 
$$
$$
S_{1} = \int \int_{D} \vec{F} \cdot \vec{n}\,\ dA =
\int \int_{D}4\,\ dA = 16
$$
###### $S_{3}$
$$
x=x,\ y=y,\ z=1
$$
$$
\vec{F} = \left< x,\ y,\ 3 \right> 
$$
$$
\vec{n} = \left< 0,\ 0,\ 1 \right> 
$$
$$
S_{1} = \int \int_{D} \vec{F} \cdot \vec{n}\,\ dA =
\int \int_{D}3\,\ dA = 12
$$
###### Other sides
$$
S_{4} = S_{1} = 4
$$
$$
S_{5} = S_{2} = 16
$$
$$
S_{6} = S_{3} = 12
$$
###### Total Surface Integral
$$
2(4+16+12) = 64
$$
##### Question 7
>[!Question 7]
>Evaluate the surface integral $\int \int_{S} \mathbf{F} \cdot dS$  for the given vector field $\mathbf{F}$ and the oriented surface $S$.
>In other words, find the flux of $F$ across $S$. For closed surfaces, use the positive (outward) orientation.
$\mathbf{F}(x,\ y,\ z) = x^2\mathbf{i}+y^2\mathbf{j}+z^2\mathbf{k}$, $S$ is the boundary of the solid half-cylinder $0 \leq z \leq \sqrt{ 25-y^2 }$, $0 \leq x \leq 3$

###### $S_{1}$ (Top of Cylinder)
$$
\int \int_{R} \vec{F}(x,\ y,\ g) \cdot \left< -g_{x},\ -g_{y},\ 1 \right> dA
$$
$$
z = g(x,\ y) = \sqrt{ 25-y^2 }
$$
$$
g_{x} = 0
$$
$$
g_{y} = -\frac{y}{\sqrt{ 25-y^2 }}
$$
$$
\vec{F}(x,\ y,\ g) = \left< x^2,\ y^2,\ 25-y^2 \right> 
$$
$$
\int_{0}^3 \int_{-5}^5 \frac{y^3}{\sqrt{ 25-y^2 }}+25-y^2 \,dy\,\  dx 
$$
$$
3 \int_{-5}^5 25-y^2\,\ dy = 500
$$
$$
S_{1} = 500
$$
###### $S_{2}$ (Underside)
$$
\vec{F} = \left< x^2,\ y^2,\ 0 \right> 
$$
$$
\vec{r} = \left< 0,\ 0,\ -1 \right> 
$$
$$
\int \int \vec{F} \cdot \vec{r} \, dS  = 0
$$

###### $S_{3}$ (Side)
$$
\vec{F} = \left< 9,\ y^2,\ z^2 \right> 
$$
$$
\vec{n} = \left< 1,\ 0,\ 0 \right> 
$$
$$
\int \int \vec{F} \cdot \vec{n}\,\ dS = \int \int 9 \, dA = \frac{9\pi(5^2)}{2} = \frac{225\pi}{2}
$$

###### $S_{4}$ (Another Side)
$$
\vec{F} = \left< 0,\ y^2,\ z^2 \right> 
$$
$$
\vec{n} = \left< -1,\ 0,\ 0 \right> 
$$
$$
\int \int \vec{F} \cdot \vec{n}\,\ dS = \int \int 0 \, dA = 0
$$
###### Final Answer
$$
S_{1} + S_{2}+S_{3}+S_{4} = 500 + 0 + \frac{225\pi}{2} + 0 = 
$$
$$

500 + \frac{225\pi}{2}
$$

#### Q6
Cylinder with top and bottom chopped

##### Cylinder side
###### Parameterize
$$
\vec{r}(u,\ v) = 2\cos (u)\hat{i} + 2\sin(u)\hat{j} + v\hat{k}
$$
$$
\vec{r}_{u} = -2\sin(u)\hat{i}+2\cos(u)\hat{j}+0\hat{k}
$$
$$
\vec{r}_{v} = 0\hat{i}+0\hat{j}+1\hat{k}
$$
###### $||\vec{r}_{u} \times \vec{r}_{v}||$
$$
\vec{r}_{u} \times \vec{r}_{v} = 2\cos(u)\hat{i}+2\sin(u) \hat{j}+0\hat{k}
$$
$$
||\vec{r}_{u} \times \vec{r}_{v}|| = \sqrt{ (2\cos(u))^2+(2\sin(u))^2 }
$$
$$
||\vec{r}_{u} \times \vec{r}_{v}|| = \sqrt{ 4\cos^2(u)+4\sin^2(u) }
$$
$$
||\vec{r}_{u} \times \vec{r}_{v}|| = 2\sqrt{ \cos^2(u)+\sin^2(u) }=2\sqrt{ 1 }=2
$$
###### Integrate
$$
\int \int_{D}\,\  (2\cos(u)-z)(2)\,\ dA
$$
$$
\int_{0}^{2\pi} \int_{2\cos(u)-3}^{2\cos(u)+2} \,\ 4\cos(u)-2z\,\ dz\,\ du
$$

##### Top side
###### g(x, y)
$$
z = g(x,\ y) = x+2
$$
$$
g_{x} = 1
$$
$$
g_{y} = 0
$$
$$
\sqrt{ g_{x}^2+g_{y}^2+1 } = \sqrt{ 2 }
$$
###### Integrate
$$
\int \int ([x-(x+2)]\sqrt{ 2 }) \, dA
$$
$$
-2\sqrt{ 2 }\int \int\,\  dA
$$
$\int \int\,\ dA$ is just the area of a circle with radius 2

##### bottom is similar to top side

#### Next Problem

$$
\mathbf{F}(x,\ y,\ z) \left< 22xy,\ 11x^2,\ 4\tan^{-1}(z) \right> 
$$


How would i find the work done by $\vec{F}$ on an object traversing $C$ once, assuming $\vec{F}$ is measured in Newtons and distance is measured in meters. $\vec{F}=\left< 12xy,\ y-4x \right>$ and the curve $C$ is defined by the linear path from point $(0,\ 0)$ to point $(3,\ 6)$ and then along the linear path from point $(3,\ 6)$ to $(0,\ 6)$.
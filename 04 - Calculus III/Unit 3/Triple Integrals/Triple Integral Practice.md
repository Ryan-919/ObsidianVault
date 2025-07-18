## HW
### Basic Integrals
#### Problem 2 HW
>[!Problem]
>Evaluate the triple integral.
>$\int \int \int_{E}\,6xy\,dV$, where $E$ lies under the plane $z = 1+x+y$ and above the region in the $xy$-plane bounded by the curves $y=\sqrt{ x }$, $y=0$, and $x=1$

##### Setup
###### Domain
$$
D = \left\{ (x,\ y,\ z) \bigr| 0 \leq x \leq 1,\ 0 \leq y \leq \sqrt{ x },\ 0 \leq z \leq 1+x+y  \right\} 
$$
###### Integral
$$
\int_{0}^{1} \int_{0}^{\sqrt{ x }} \int_{0}^{1+x+y}6xy\,\ dz\,\ dy\,\ dx
$$
##### Solve Integral
$$
\int_{0}^{1} \int_{0}^{\sqrt{ x }} \int_{0}^{1+x+y}6xy\,\ dz\,\ dy\,\ dx
$$
$$
\int_{0}^1 \int_{0}^{\sqrt{ x }} 6xy(1+x+y)\,\ dy\,\ dx
$$
$$
\int_{0}^1 \int_{0}^{\sqrt{ x }} 6xy+6x^2y+6xy^2\,\ dy\,\ dx
$$
$$
\int_{0}^{1} 3x^2+3x^3+2x^{5/2}\,\ dx
$$
$$
1+\frac{3}{4} + \frac{4}{7} = \frac{28}{28}+\frac{21}{28}+\frac{16}{28} = \frac{65}{28}
$$
#### Problem 3 HW
>[!Problem]
>Evaluate the triple integral.
>$\int \int \int_{E}\,10x\,dV$, where $E$ is bounded by the paraboloid $x=2y^2+2z^2$ and the plane $x=2$

##### Setup
###### Make Double Integral
$$
\int \int \int_{E}\,10x\,dV = \int \int_{D} \left( \int_{2y^2+2z^2}^2 10x\,\ dx \right)dA
$$
$$
\frac{10}{2} \int \int_{D} \,\ 2^2-(2y^2+2z^2)^2\,\ dA
$$
###### Domain from Polar
$$
y^2+z^2 \leq 1 
$$
$$
y=r\cos \theta
$$
$$
z = r\sin \theta
$$
$$
D = \left\{ (r,\ \theta) \bigr| 0\leq r\leq 1,\ 0 \leq \theta \leq 2\pi \right\} 
$$
###### Final Integral
$$
\frac{10}{2} \int_{0}^{2\pi} \int_{0}^{1}\,\ 2^2-2^2r^4\,\ rdr\,\ d\theta
$$
$$
20 \int_{0}^{2\pi} \int_{0}^{1}\,\ 1-r^4\,\ rdr\,\ d\theta
$$
$$
40\pi \left( \int_{0}^1\,\ r-r^5\,\ dr \right)
$$
$$
40\pi\left( \frac{1}{2}-\frac{1}{6} \right) = \frac{40\pi}{3}
$$
#### Problem 4 HW
>[!Problem]
>Use a triple integral to find the volume of the given solid.
>The tetrahedron enclosed by the coordinate planes and the plane $11x+y+z=3$

$$
11x+y = 3
$$
$$
y = 3-11x
$$
$$
E = \left\{ (x,\ y,\ z)\ \bigr| 0 \leq x \leq \frac{3}{11},\ 0 \leq y \leq 3-11x,\ 0\leq z\leq 3-11x-y \right\} 
$$
$$
\int_{0}^{3/11} \int_{0}^{3-11x} \int_{0}^{3-11x-y}\,\  dz\,\ dy\,\ dx
$$
$$
\int_{0}^{3/11} \int_{0}^{3-11x} 3-11x-y\,\ dy\,\ dx
$$
$$
\int_{0}^{3/11} 3(3-11x)-11x(3-11x)-\frac{(3-11x)^2}{2}\,\ dx
$$

#### Problem 6 HW
>[!Problem]
>The figure shows the region of integration for the integral.
>$\int_{0}^{36} \int_{\sqrt{ x }}^6 \int_{0}^{6-y} f(x, \ y, \ z)\,dz\,dy\, dx$
>Rewrite this integral as an equivalent iterated integral in the five other orders.

##### Planes
###### xy plane
```desmos-graph
left=-5; right=40;
bottom=-5; top=10;
---
y \geq \sqrt{x} | y < 6
```

###### yz plane
```desmos-graph
left=-1; right=7;
bottom=-1; top=7;
---
y \leq 6-x | 0 \leq x \leq 6 | y \geq 0
```

###### xz plane
```desmos-graph
left=-1; right=40;
bottom=-1; top=7;
---
y \leq 6 - \sqrt{x} | x<36 | y \geq 0
```

$$
\int_{0}^6 \int_{0}^{y^2} \int_{0}^{6-y} f(x,\ y,\ z)\,\ dz\,\ dx\,\ dy
$$
$$
\int_{0}^6 \int_{0}^{6-y}  \int_{0}^{y^2} f(x,\ y,\ z)\,\  dx\,\ dy\,\ dz
$$
$$
\int_{0}^{6} \int_{0}^{6-z} \int_{0}^{y^2} f(x,\ y,\ z) \, dx \,\ dz\,\ dy
$$
$$
\int_{0}^6 \int_{0}^{6-z^2} \int_{\sqrt{ x }}^{6-z} f(x,\ y,\ z) \, dy \,\ dx\,\ dz 
$$
$$
\int_{0}^{36} \int_{0}^{6-\sqrt{ x }} \int_{\sqrt{ x }}^{6-z} f(x,\ y,\ z) \, dy \,\ dz\,\ dx 
$$

>[!Problem]
>Find $\int \int \int_{E}\, 6xy\,dv$ where $E$ lies under the plane $z=1+x+y$ and above the region in the x-y plane bounded by the curves $y=\sqrt{ x }$, $y=0$, $x=1$

##### Planes
###### x-y plane
```desmos-graph
left=-1; right=2;
bottom=-1; top=2;
---
y \leq \sqrt{x} | y > 0 | x < 1
```

$$
0 \leq z \leq 1+x+y
$$
$$
0 \leq x \leq 1
$$
$$
0 \leq y \leq \sqrt{ x }
$$
>[!Problem]
>Find the mass and center of mass of the solid $E$ with the given density $\rho$.
>E is the cube given by $0 \leq x \leq a$, $0 \leq y \leq a$, $0 \leq z \leq a$; $\rho(x,\ y,\ z) = 4(x^2+y^2+z^2)$

$$
m = 4 \int_{0}^a \int_{0}^a \int_{0}^a x^2+y^2+z^2 \,\ dx\,\ dy\,\ dz
$$
$$
m=4 \int_{0}^a \int_{0}^a \frac{a^3}{3}+ay^2+az^2\,\ dy\,\ dz
$$
$$
m = 4\int_{0}^a \frac{a^4}{3} + \frac{a^4}{3} + {a^2z^2} \,\ dz
$$
$$
m = 4 \left( \frac{a^5}{3}+\frac{a^5}{3}+\frac{a^5}{3} \right) = 4a^5
$$
$$
M_{yz} = 4\int_{0}^a \int_{0}^a \int_{0}^a x^3+x(y^2+z^2)\,\ dx\,\ dy\,\ dz
$$
$$
M_{yz} = 4 \int_{0}^a \int_{0}^a \frac{a^4}{4}+\frac{a^2}{2}(y^2+z^2)\,\ dy\,\ dz
$$
$$
M_{yz} = 4 \int_{0}^a  \frac{a^5}{4}+\frac{a^5}{6}+\frac{a^3z^2}{2},\ dz
$$
$$
M_{yz} = 4\left( \frac{a^6}{4} + \frac{a^6}{6}+\frac{a^6}{6} \right)
$$
$$
M_{yz} = \frac{7a^6}{3} = M_{xz} = M_{xy}
$$

>[!Change Order of Integration]
>$\int_{-1}^1 \int_{x^2}^1 \int_{0}^{1-y}\,f(x,\ y,\ z)\,dz\,dy\,dx$ to
>$\int \int \int f(x,\ y,\ z)\,dx\,dy\,dz$

$$
\int_{0}^1 \int_{0}^{1-z} \int_{-\sqrt{ y }}^{\sqrt{ y }}\,\ f(x,\ y,\ z)\,\ dx\,\ dy\,\ dz
$$

###### yz plane
```desmos-graph
y=0
y=1-x
```

###### xy plane
```desmos-graph
y=x^2
y=1
```

###### yx plane
```desmos-graph
y=\sqrt{x}
y=-\sqrt{x}
x=1
```


$$
\int_{0}^{2\pi} \int_{0}^4 \int_{-3}^5\,\ r^2\,\ dz\,\ dr\,\ d\theta
$$

$$
\int_{0}^{\pi/2} \int_{0}^3 \int_{0}^{9-r^2}(r^2\sin \theta+r^2\cos \theta+rz)\,\ dz\,\ dr\,\ d\theta
$$
$$
\int_{0}^{\pi/2} \int_{0}^3 \int_{0}^{9-r^2}(r^2(\sin \theta+\cos \theta) +rz)\,\ dz\,\ dr\,\ d\theta
$$
$$
\int_{0}^{\pi/2} \int_{0}^3 (r^2(\sin \theta+\cos \theta))(9-r^2)+\frac{1}{2}r(9-r^2)^2\,\ dr\,\ d\theta
$$
$$
\int_{0}^{\pi/2} \int_{0}^3 (9r^2-r^4)(\sin \theta+\cos \theta)+\frac{1}{2}r(9-r^2)^2\,\ dr\,\ d\theta
$$

$$
\int_{0}^{2\pi} \int_{0}^2 \int_{0}^{7r} r^3\cos^2 \theta\,\ dz\,\ dr\,\ d\theta
$$
$$
\int_{0}^{2\pi} \int_{0}^2 7r^4\cos^2\theta\,\ dr\,\ d\theta
$$
$$
\frac{224}{5}\left( \int_{0}^{2\pi}\cos^2\theta\,\ d\theta \right)
$$

$$
\int_{0}^{2\pi} \int_{0}^{5} \int_{r}^8\,\ rz\cos \theta\,\ dz\,\ dr\,\ d\theta
$$
$$
\frac{1}{2}(64r\cos \theta-r^3\cos \theta)
$$

$$
\int_{0}^{2\pi} \int_{0}^{5} \int_{r}^\sqrt{ {50-r^2} }\,\ r\,\  dz\,\ dr\,\ d\theta
$$

$$
r(\sqrt{ 50-r^2 }-r)
$$

$$
2\pi\left( \int_{0}^5 r(\sqrt{ 50-r^2 }-r)\,\ dr
 \right)
$$
$$
2\pi \left( \left( \int_{0}^5r\sqrt{ 50-r^2 }\,\ dr \right) - \int_{0}^5 r^2\,\ dr \right)
$$
$$
u = 50-r^2
$$
$$
du = -2r\,\ dr
$$
$$
\frac{du}{-2} = rdr
$$
$$
2\pi\left( \left( -\frac{1}{2} \int_{50}^{25} \sqrt{ u }\,\ du \right) - \frac{125}{3} \right)
$$
$$
\frac{2}{3}u^{3/2} \biggr|_{u=50}^{u=25} = \frac{2}{3}(125-50^{3/2})
$$
$$
2\pi\left( \left( -\frac{1}{3}(125-50^{3/2}) \right) - \frac{125}{3} \right)
$$

$$
\int_{0}^{2\pi} \int \int_{x^2+y^2}^{81-8x^2-8y^2}\,\ r\,\ dz\,\ dr\,\ d\theta
$$
$$
x^2+y^2 = 81-8x^2-8y^2
$$
$$
r^2 = 81 - 8r^2
$$
$$
9r^2 = 81
$$
$$
r = 3
$$
$$
\int_{0}^{2\pi} \int_{0}^{3} \int_{r^2}^{81-8r^2}\,\ r\,\ dz\,\ dr\,\ d\theta
$$
$$
2\pi\left( \int_{0}^3 r(81-8r^2-r^2)\,\ dr \right)
$$
$$
2\pi\left( \int_{0}^3 81r-9r^3\,\ dr \right)
$$

$$
\int_{0}^{2\pi} \int_{0}^{3} \int_{r^2}^{81-8r^2}\,\ rz\,\ dz\,\ dr\,\ d\theta
$$
$$
2\pi\left( \int_{0}^3 \frac{r}{2}((81-8r^2)^2-r^4) \right)
$$

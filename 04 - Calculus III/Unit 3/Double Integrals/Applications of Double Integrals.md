>[!Problem]
>Find the mass and center of mass of the lamina that occupies the region $D$ and has the given function $\rho$
>$D$ is the triangular region with vertices $(0,\ 0)$, $(2,\ 1)$, $(0,\ 3)$; $\rho(x,\ y) = 5(x+y)$

```desmos-graph
(0, 0)
(2, 1)
(0, 3)
x=0
y=-x+3
y=x/2
```

$$
m=\int \int \rho \,\ dA 
$$
$$
\int_{0}^2 \int_{\frac{1}{2}x}^{-x+3} 5(x+y) \,\ dy\,\ dx
$$
$$
\int_{0}^2 5xy+\frac{5y^2}{2} \biggr|^{-x+3}_{\frac{1}{2}x}\,\  dx
$$
$$
\int_{0}^2 -5x^2+15x+\frac{5(-x+3)^2}{2} - \frac{5x^2}{2}+\frac{5}{8}x^2 \,\ dx
$$
$$
(\bar{x},\ \bar{y}) = \left( \frac{M_{y}}{m},\ \frac{M_{x}}{m} \right)
$$
$$
M_{x} = \int_{D}\int y\,\ p(x,\ y) \, dA
$$
$$
M_{y} = \int_{D}\int x\,\ p(x,\ y) \, dA
$$
$$
M_{x} = \int_{0}^2 \int_{\frac{1}{2}x}^{-x+3} 5y(x+y) \,\ dy\,\ dx
$$
$$
\int_{0}^2 \frac{5xy^2}{2}+\frac{5y^3}{3} \biggr|^{-x+3}_{\frac{1}{2}x} \,\ dx
$$
$$
\int_{0}^2 \frac{5x(-x+3)^2}{2}+\frac{5(-x+3)^3}{3} - 
 \frac{5x\left( \frac{1}{2}x \right)^2}{2} - \frac{5\left( \frac{1}{2}x \right)^3}{3}\,\ dx
$$
$$
M_{x}=45
$$
$$
M_{y} = \int_{0}^2 \int_{\frac{1}{2}x}^{-x+3} 5x(x+y) \,\ dy\,\ dx
$$
$$
\int_{0}^2 \int_{\frac{1}{2}x}^{-x+3} 5x^2+5xy \,\ dy\,\  dx
$$
$$
\int_{0}^2 5x^2y+\frac{5xy^2}{2} \biggr|^{-x+3}_{\frac{1}{2}x}\,\ dx
$$
$$
\int_{0}^2 5x^2(-x+3) + \frac{5x(-x+3)^2}{2} - 5x^2\left( \frac{1}{2}x \right) - \frac{5x\left( \frac{1}{2}x \right)^2}{2}
$$
$$
M_{y}=22.5
$$
$$
(\bar{x},\ \bar{y}) = \left( \frac{M_{y}}{m},\ \frac{M_{x}}{m} \right)
$$
```desmos-graph
y=1-x^2
y=0
```
$$
\int_{-1}^1 \int_{0}^{1-x^2} 5ky\,\ dy\,\ dx
$$
$$
\int_{-1}^1 \frac{5k(1-x^2)^2}{2}\,\ dx
$$
$$
m=\frac{8k}{3}
$$
$$
\int_{-1}^1 \int_{0}^{1-x^2} 5kxy\,\ dy\,\ dx
$$
$$
\int_{-1}^1 \frac{5kx(1-x^2)^2}{2}\,\ dx
$$
$$
M_{y} = 0
$$
$$
\int_{-1}^1 \int_{0}^{1-x^2} 5ky^2\,\ dy\,\ dx
$$
$$
\int_{-1}^1 \frac{5k(1-x^2)^3}{3}\,\ dx
$$
$$
M_{x} = \frac{32k}{21}
$$
```desmos-graph
left=-2; right=9
bottom=-2; top=9
---
x^2+y^2 \leq 49|x>0|y>0
```

$$
\rho(x,\ y)=ky
$$
$$
m=\int_{0}^{\pi/2} \int_{0}^7 kr^2\sin \theta\,\ dr\,\ d\theta
$$
$$
m=\int_{0}^{\pi/2} \frac{k(7^3)\sin \theta}{3},\ d\theta
$$
$$
m=\frac{343k}{3}
$$
$$
M_{y} = \int_{0}^{\pi/2} \int_{0}^7 kr^3\cos \theta\sin \theta\,\ dr\,\ d\theta
$$
$$
M_{y}=\int_{0}^{\pi/2} \frac{k(7^4)\cos \theta \sin \theta}{4}\,\ d\theta
$$
$$
M_{y} = \frac{2401k}{8}
$$
$$
M_{x} = \int_{0}^{\pi/2} \int_{0}^7 kr^3\sin \theta\sin \theta\,\ dr\,\ d\theta
$$
$$
M_{x}=\int_{0}^{\pi/2} \frac{k(7^4)\sin \theta \sin \theta}{4}\,\ d\theta
$$
$$
\frac{2401\pi k}{16}
$$
```desmos-graph
y=(1-x^2)^{0.5}
y=(9-x^2)^{0.5}
```

$$
\rho(r,\ \theta) = kr
$$
$$
m=\int_{0}^\pi \int_{1}^3 kr^2\,\ dr\,\ d\theta
$$
$$
m = \frac{k}{3} \int_{0}^\pi 26\,\ d\theta
$$
$$
m = \frac{26\pi k}{3}
$$
$$
M_{y} = \int_{0}^\pi \int_{1}^3 kr^3\cos \theta\,\ dr\,\ d\theta
$$
$$
M_{y} = \frac{k}{4} \int_{0}^{\pi} 3^4\cos \theta-\cos \theta\,\ d\theta
$$
$$
M_{y} = 0
$$
$$
M_{x} = \int_{0}^\pi \int_{1}^3 kr^3\sin \theta\,\ dr\,\ d\theta
$$
$$
M_{x} = \frac{k}{4} \int_{0}^{\pi} 3^4\sin \theta-\sin \theta\,\ d\theta
$$
$$
M_{x}= 40k
$$
$$
(\bar{x},\ \bar{y}) = \left( 0,\ \frac{120k}{26\pi k} \right)
$$
$$
\int_{0}^{\infty}\int_{0}^{\infty} 0.1e^{-0.5x-0.2y}\,\ dx\,\ dy
$$
$$
\int_{0}^{\infty} -0.2e^{-0.5x-0.2y} \biggr|^{\infty}_{0} dy
$$
$$
\int_{0}^{\infty} 0.2e^{-0.2y}\,\ dy
$$
$$
-e^{-0.2y} \biggr|^{\infty}_{0} = 1
$$
$$
\int_{8}^{\infty} \int_{0}^{\infty} 0.1e^{-0.5x-0.2y}\,\ dx\,\ dy
$$
$$
\int_{8}^{\infty} -0.2e^{-0.5x-0.2y} \biggr|^{\infty}_{0}\,\ dy
$$
$$
\int_{8}^{\infty} 0.2e^{-0.2y}\,\ dy
$$
$$
-e^{-4-0.2y} \biggr|^{\infty}_{8}
$$
$$
e^{-28/5}
$$
>[!Moment of inertia]
>Find the moments of inertia $I_{x}$, $I_{y}$, $I_{0}$ for the lamina below
>$D$ is bounded by $y = e^x$, $y=0$, $x=0$, and $x=1$; $\rho(x,\ y) = 11y$

$$
I_{x} = \int_{0}^1 \int_{0}^{e^x} y^2(11y)\,\ dy\,\ dx
$$
$$
I_{x} = \frac{11}{4} \int_{0}^1 e^{4x}\,\ dx
$$
$$
I_{x} = \frac{11}{16} (e^{4}-1)
$$
$$
I_{y} = \int_{0}^1 \int_{0}^{e^x} x^2(11y)\,\ dy\,\ dx
$$
$$
I_{y} = \frac{11}{2} \int_{0}^1 x^2e^{2x}\,\ dx
$$

| Sign | D     | I                    |
| ---- | ----- | -------------------- |
| +    | $x^2$ | $e^{2x}$             |
| -    | $2x$  | $\frac{1}{2} e^{2x}$ |
| +    | $2$   | $\frac{1}{4} e^{2x}$ |
| -    | $0$   | $\frac{1}{8} e^{2x}$ |
$$
I_{y} = \frac{11}{2} \left( \left( \frac{1}{2}x^2-\frac{1}{2}x+\frac{1}{4} \right)e^x \right) 
$$

$$
I_{y} = \frac{11}{2}\left( \left( \frac{1}{2}x^2-\frac{1}{2}x+\frac{1}{4} \right)e^{2x} \biggr|^1_{0} \right)
$$
$$
I_{y} = \frac{11}{2}\left( \frac{1}{4}e - \frac{1}{4} \right) = \frac{11}{8}(e^2-1)
$$
>[!Surface Area]
>Find the area of the surface.
>the part of the plane $z = 6 + 2x + 5y$ that lies above the rectangle $[0,\ 7] \times [1,\ 4]$

$$
f_{x} = 2
$$
$$
f_{y} = 5
$$
$$
A=\int_{1}^4 \int_{0}^7 \sqrt{ 2^2+5^2+1 }\,\ dx\,\ dy
$$
$$
A= \sqrt{ 30 } \int_{1}^4 \int_{0}^7 dx\,\ dy
$$
$$
A= 7\sqrt{ 30 } \int_{1}^4\,\ dy
$$
$$
A=21\sqrt{ 30 }
$$
>[!Surface Area]
>Find the area of the surface
>the part of the plane $13x+5y+z=65$ that lies in the first octant

$$
z=f(x,\ y)=65-13x-5y
$$
$$
13x+5y=65
$$
$$
y=13-\frac{13x}{5}
$$
$$
D = \left\{ (x,\ y) \bigr| 0 \leq x \leq 5,\ 0 \leq y \leq 13-\frac{13x}{5} \right\} 
$$
$$
f_{x} = -13
$$
$$
f_{y} = -5
$$
$$
A = \int_{0}^5 \int_{0}^{13(1-x/5)} \sqrt{ (-13)^2+(-5)^2+1 }\,\ dy\,\ dx
$$
$$
A = \sqrt{ 195 } \int_{0}^5 \int_{0}^{13(1-x/5)}\,\ dy\,\ dx
$$
$$
A = 13\sqrt{ 195 } \int_{0}^5 1-\frac{x}{5}
$$
$$
A = \frac{65\sqrt{ 195 }}{2}
$$
>[!Surface Area]
>Find the area of the surface
>the part of the paraboloid $z=1-x^2-y^2$ that lies above the plane $z = -4$

$$
z=f(x,\ y) = 1-x^2-y^2
$$
$$
1-x^2-y^2 > -4
$$
$$
D = \left\{ (x,\ y) \bigr| 0 \leq x < \sqrt{ 5 },\ 0 \leq y < \sqrt{ 5 } \right\} 
$$
$$
f_{x} = -2x
$$
$$
f_{y} = -2y
$$
$$
A = \int_{0}^\sqrt{ 5 } \int_{0}^\sqrt{ 5 } \sqrt{ (-2x)^2+(-2y)^2+1 }  \, dx \,\ dy
$$
$$
A = \int_{0}^\sqrt{ 5 } \int_{0}^\sqrt{ 5 } \sqrt{ 4x^2+4y^2+1 }\,\ dx\,\ dy
$$
$$
A = \int_{0}^{2\pi} \int_{0}^\sqrt{ 5 } \sqrt{ 4r^2+1 }\,\ rdr\,\ d\theta
$$
$$
u = 4r^2 + 1
$$
$$
du = 8r\,\ dr
$$
$$
\frac{du}{8} = rdr
$$
$$
2\pi\left( \frac{1}{8} \left( \frac{2}{3}(4r^2+1)^{3/2} \biggr|_{0}^\sqrt{ 5 } \right) \right)
$$
$$
\frac{\pi}{6} ((4(5)+1)^{3/2}-1^{3/2})
$$
$$
\frac{\pi}{6}(21^{3/2} - 1^{3/2})
$$

>[!Surface Area]
>Find the area of the surface
>the part of the hyperbolic paraboloid $z = y^2 - x^2$ that lies between the cylinders $x^2+y^2 = 9$ and $x^2+y^2 = 16$

$$
z = f(x,\ y) = y^2-x^2
$$
$$
f_{x} = -2x
$$
$$
f_{y} = 2y
$$
$$
A = \int_{R}\int \sqrt{ (-2x)^2+(2y)^2+1 } \, dx 
$$
$$
A = \int_{R}\int \sqrt{ 4x^2+4y^2+1 } \, dx 
$$
$$
D = \left\{ (r,\ \theta) \bigr| 3 \leq r \leq 4,\ 0 \leq \theta \leq 2\pi \right\} 
$$
$$
A = \int_{0}^{2\pi} \int_{3}^4 \sqrt{ 4r^2+1 }\,\ rdr\,\ d\theta
$$
$$
A = 2\pi \left( \int_{3}^4 r\sqrt{ 4r^2+1 }\,\ dr \right)
$$
$$
u = 4r^2 + 1
$$
$$
du = 8r\,\ dr
$$
$$
\frac{du}{8} = rdr
$$
$$
2\pi\left( \frac{1}{8} \left( \frac{2}{3}(4r^2+1)^{3/2} \biggr|_{3}^4 \right) \right)
$$
$$
\frac{\pi}{6} ((4(4)^2+1)^{3/2} - (4(3)^2+1)^{3/2})
$$
$$
\frac{\pi}{6} (65^{3/2} - 37^{3/2})
$$

>[!Surface Area]
>Find the area of the surface
>the part of the surface $z = xy$ that lies within the cylinders $x^2+y^2 = 36$

$$
z = f(x,\ y) = xy
$$
$$
f_{x} = y
$$
$$
f_{y} = x
$$
$$
A = \int_{R}\int \sqrt{ y^2+x^2+1 } \, dx \,\ dy
$$
$$
D = \left\{ (r,\ \theta) \bigr| 0 \leq r \leq 6,\ 0 \leq \theta \leq 2\pi \right\} 
$$
$$
A = \int_{0}^{2\pi} \int_{0}^6 \sqrt{ r^2+1 }\,\ rdr\,\ d\theta
$$
$$
A = 2\pi \left( \int_{0}^6 r\sqrt{ r^2+1 }\,\ dr \right)
$$
$$
u = r^2+1
$$
$$
du = 2r\,\ dr
$$
$$
\frac{du}{2} = r\,\ dr
$$
$$
A = 2\pi \left( \frac{1}{2} \left( \frac{2}{3} (r^2+1)^{3/2} \biggr|^6_{0} \right)  \right)
$$
$$
A = \frac{2\pi}{3} (37^{3/2}-1)
$$
>[!Surface Area]
>Find the area of the surface
>the part of the sphere $x^2+y^2+z^2=81$ that lies above the plane $z=1$

$$
z = f(x,\ y) = \sqrt{ 81-x^2-y^2 }
$$
$$
f_{x} = \frac{2x}{2\sqrt{ 81-x^2-y^2 }} = \frac{x}{\sqrt{ 81-x^2-y^2 }}
$$
$$
f_{y} = \frac{y}{\sqrt{ 81-x^2-y^2 }}
$$
$$
A = \int_{R}\int \sqrt{ \frac{x^2+y^2}{81-x^2-y^2} + 1 }\,\ dx\,\ dy
$$
$$
A = \int_{R}\int \sqrt{ \frac{x^2+y^2+81-x^2-y^2}{81-x^2-y^2} }\,\ dx\,\ dy
$$
$$
A = \int_{R}\int 9\sqrt{ \frac{1}{81-x^2-y^2} }\,\ dx\,\ dy
$$
$$
x^2+y^2 = 80
$$
$$
D = \left\{ (r,\ \theta) \bigr| 0 \leq r \leq \sqrt{ 80 },\ 0 \leq \theta \leq 2\pi \right\} 
$$
$$
A = \int_{0}^{2\pi}\int_{0}^\sqrt{ 80 } 9\sqrt{ \frac{1}{81-r^2} }\,\ rdr\,\ d\theta
$$
$$
A = 2\pi \left( 9\int_{0}^\sqrt{ 80 } r(81-r^2)^{-1/2}\,\ dr \right)
$$
$$
u = 81-r^2
$$
$$
du = -2r\,\ dr
$$
$$
-\frac{du}{2} = rdr
$$
$$
A = -9\pi( 2(\sqrt{ 81-r^2 }) \biggr|_{0}^{\sqrt{ 80 }} )
$$
$$
A = -18\pi (1-9) = 144\pi
$$

>[!Surface Area]
>Find the area of the finite part of the paraboloid $y = x^2+z^2$ cut off by the plane $y=36$

Could think of this as just swapping the y and z variables

$$
z = f(x,\ y) = x^2 + y^2
$$
$$
z = 36
$$
$$
f_{x} = 2x
$$
$$
f_{y} = 2y
$$
$$
A = \int_{R}\int \sqrt{ (2x)^2+(2y)^2+1 } \, dx \,\ dy
$$
$$
A = \int_{R}\int \sqrt{ 4x^2+4y^2+1 } \, dx \,\ dy
$$
$$
D = \left\{ (r,\ \theta) \bigr| 0 \leq r \leq 6,\ 0 \leq \theta \leq 2\pi \right\} 
$$
$$
A = \int_{0}^{2\pi} \int_{0}^6 \sqrt{ 4r^2+1 }\,\ rdr\ d\theta
$$
$$
A = 2\pi \left( \int_{0}^6 r\sqrt{ 4r^2+1 }\,\ dr \right)
$$
$$
u = 4r^2 + 1
$$
$$
du = 8r\,\ dr
$$
$$
\frac{du}{8} = rdr
$$
$$
2\pi\left( \frac{1}{8} \left( \frac{2}{3}(4r^2+1)^{3/2} \biggr|_{0}^6 \right) \right)
$$
$$
\frac{\pi}{6}(145^{3/2}-1)
$$
>[!Surface area]
>Find the area of the surface correcet to four decimal places by expressing the area in terms of a single integral and using your calculator to estimate the integral.
>the part of the surface $z = e^{-x^2-y^2}$ that lies above the disk $x^2+y^2 \leq 25$

$$
z = f(x,\ y) = e^{-x^2-y^2}
$$
$$
f_{x} = -2xe^{-x^2-y^2}
$$
$$
f_{y} = -2ye^{-x^2-y^2}
$$
$$
A = \int_{R}\int \sqrt{ ({-2xe^{-x^2-y^2}})^2 + ({-2ye^{-x^2-y^2}})^2 + 1 } \, dx \,\ dy
$$
$$
A = \int_{R}\int \sqrt{ 4e^{-2(x^2+y^2)}(x^2+y^2)+1 } \, dx \,\ dy
$$
$$
D = \left\{ (r,\ \theta) \bigr| 0 \leq r \leq 5,\ 0 \leq \theta \leq 2\pi \right\} 
$$
$$
A = \int_{0}^{2\pi} \int_{0}^5 \sqrt{ 4e^{-2r^2}r^2+1 }\,\ rdr\,\ d\theta
$$

>[!Surface Area]
>Find the area of the surface
>the part of the sphere $x^2+y^2+z^2=4z$ that lies inside the paraboloid $z=x^2+y^2$ 

$$
z + z^2 = 4z
$$
$$
z = 0,\ 3
$$
$$
x^2+y^2+z^2-4z=0
$$
$$
x^2+y^2+(z-2)^2=4
$$
$$
z = f(x,\ y) = 2+\sqrt{ 4-x^2-y^2 }
$$
$$
f_{x} = -\frac{x}{\sqrt{ 4-x^2-y^2 }}
$$
$$
f_{y} = -\frac{y}{\sqrt{ 4-x^2-y^2 }}
$$

$$
A = \int_{R}\int \sqrt{ \left( -\frac{x}{\sqrt{ 4-x^2-y^2 }} \right)^2 + \left( -\frac{y}{\sqrt{ 4-x^2-y^2 }} \right)^2 + 1 } \, dx \,\ dy
$$
$$
A = \int_{R}\int \sqrt{ \frac{x^2+y^2}{4-x^2-y^2}+1 } \, dx \,\ dy
$$
$$
A = \int_{R}\int \sqrt{ \frac{x^2+y^2+4-x^2-y^2}{4-x^2-y^2} } \, dx \,\ dy
$$
$$
A = \int_{R}\int \sqrt{ \frac{4}{4-x^2-y^2} } \, dx \,\ dy
$$
$$
D = \left\{ (r,\ \theta) \bigr| 0 \leq r \leq \sqrt{ 3 },\ 0 \leq \theta \leq 2\pi \right\} 
$$
$$
A = \int_{0}^{2\pi} \int_{0}^{\sqrt{ 3 }} \sqrt{ \frac{4}{4-r^2} }\,\ rdr\,\ d\theta
$$
$$
A = 2\pi \left( 2\int_{0}^\sqrt{ 3 } r\sqrt{ \frac{1}{4-r^2} }\,\ dr \right)
$$
$$
u = 4-r^2
$$
$$
du = -2r\,\ dr
$$
$$
\frac{du}{-2} = r\,\ dr
$$
$$
A = 4\pi \left( -\frac{1}{2}\left( \int u^{-1/2} \, du  \right) \right)
$$
$$
A = -2\pi \left( 2(4-r^2)^{1/2} \biggr|_{0}^\sqrt{ 3 } \right)
$$

$$
\mu gd_{0} = \frac{1}{2}v^2
$$
$$
d_{0} = \frac{v^2}{2\mu g}
$$
$$
\frac{\mu gd_{1}}{2} = 2v^2
$$
$$
d_{1} = 4v^2
$$

##### Lab Q2

$$
\rho(x,\ y) = 90x
$$
$$
z = f(x,\ y) = x^2+y^2
$$
$$
f_{x} = 2x
$$
$$
f_{y}=  2y
$$
$$
SA =\int_{R}\int \sqrt{ 1+4x^2+4y^2 } \, dx \,\ dy
$$
$$
D = \left\{ (r,\ \theta) \bigr| \sqrt{ 8 } \leq r \leq \sqrt{ 23 },\ 0 \leq \theta \leq \frac{\pi}{2} \right\} 
$$
$$
SA = \int_{0}^{\pi/2} \int_{\sqrt{ 8 }}^\sqrt{ 23 } r\sqrt{ 1+4r^2 }\,\ dr\,\ d\theta 
$$

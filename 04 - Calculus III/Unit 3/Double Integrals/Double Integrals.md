>[!Problem]
>Determine the volume of $f(x,\ y) = xy^2$ in the region $R:[1,\ 2] \times [0,\ 3]$

$$
\int \int f(x,\ y)dA
$$
$$
\int_{1}^2 \int_{0}^3 xy^2 dydx
$$
$$
\int_{1}^2 \frac{xy^3}{3} \biggr|_{0}^3dx
$$
$$
\int_{1}^2 9xdx
$$
$$
\frac{9x^2}{2} \biggr|_{1}^2
$$
$$
18-\frac{9}{2}=\frac{27}{2}
$$
>[!Problem]
>$\int_{1}^2 \int_{0}^4(6x^2y-3x)dy\ dx$

$$
\int_{1}^2 3x^2y^2-3xy dx
$$
>[!Problem]
>$\int_{-6}^6 \int_{0}^{\pi/2} (y+y^2\cos(x))\ dx\ dy$

$$
y\left( \frac{\pi}{2} \right)+y^2
$$
$$
\frac{{\pi y^2}}{4}+\frac{y^3}{3}
$$
>[!Problem]
>$\int \int_{R} \frac{3xy^2}{x^2+1} \, dA$, $R=\left\{ (x,\ y) | 0 \leq x \leq 3,\ -2 \leq y \leq 2 \right\}$

$$
\int_{0}^3 \int_{-2}^2 \frac{3xy^2}{x^2+1} dydx
$$
$$
\int_{0}^3 \frac{16x}{x^2+1} dx
$$
$$
u = x^2 \to du = 2xdx \to 8du=16xdx
$$
$$
8\int \frac{du}{u} = 8\ln (x^2+1) \biggr|_{0}^3
$$
$$
8(\ln(10)-\ln(1))
$$
#### bleh
$$
4x+8y-2z+17=0
$$
$$
z=f(x,\ y)=2x+4y+\frac{17}{2}
$$
$$
\int_{-1}^4 \int_{-1}^1 \left( 2x+4y+\frac{17}{2} \right)\,\ dy\,\ dx
$$
$$
\int_{-1}^4 (4x+17)
$$
$$
V=\int_{0}^4 \int_{-3}^3 (3+x^2+(y-2)^2) \, dx\,\ dy - \int_{0}^4 \int_{-3}^3 (1)dxdy
$$
$$
V=\int_{0}^4 18+18+6(y-2)^2 \,\ dy - \int_{0}^4 6 \,\ dy
$$
$$
\int_{0}^5 \int_{-2}^2 (4x^2y) \, dx \,\ dy
$$
$$
\frac{4x^3}{3}
$$
$$
\frac{64}{3} \int_{0}^5 y \, dy
$$
$$
\frac{32y^2}{3} = \frac{800}{3}
$$

- f(1.5, 1)
- f(1.5, 3)
- f(2.5, 1)
- f(2.5, 3)


|     | 2   | 4   | 6   |
| --- | --- | --- | --- |
| 6   | 12  | 24  | 36  |
| 8   | 18  | 36  | 54  |
| 10  | 20  | 40  | 60  |
| 12  | 24  | 48  | 72  |

$$
\int_{0}^1 \int_{0}^{s^4} \cos(s^5) \, dt\,\ ds 
$$
$$
\int_{0}^1 \cos(s^5)s^4 ds
$$
$$
\frac{1}{5}\sin(s^5)
$$
```desmos-graph
left=0; right=55;
bottom=-10; top=10;
---
y=x-42
x=y^2
```
$$
y+42=y^2
$$
$$
y = 7 , -6
$$
$$
x=49,\ 36
$$
$$
\int_{-6}^7 \int_{y^2}^{y+42}y  \, dx \,\ dy
$$
$$
\int_{-6}^7 (y+42)y-(y^2)y dy
$$
```desmos-graph
(0, 1)
(1, 2)
(4, 1)
y=x+1
y=1
y=-x/3+7/3
-3y+7=x
```

left
$$
y=x+1
$$
right
$$
y=-\frac{1}{3}x+\frac{7}{3}
$$
$$
\int_{1}^2 \int_{y-1}^{-3y+7} 5y^2 dx dy
$$
$$
\int_{1}^2 5y^2(-3y+7-y+1)dy
$$
```desmos-graph
x^2+y^2=1
y={(1-x^2)}^{0.5}
y=-{(1-x^2)}^{0.5}
```

$$
y=\sqrt{ 1-x^2 }
$$
$$
y=-\sqrt{ 1-x^2 }
$$
$$
\int_{-1}^1 \int_{-\sqrt{ 1-x^2 }}^{\sqrt{ 1-x^2 }} (8x-5y)\,\ dy\,\ dx
$$
$$
\int_{-1}^18x(2\sqrt{ 1-x^2 })dx
$$
```desmos-graph
(1,1)
(4,1)
(1,2)
y=1
y=-x/3+7/3
x=1
```
$$
\int_{1}^4 \int_{1}^{-x/3+7/3}6xy\,\ dy\,\ dx
$$
$$
\int_{1}^4 3x\left( \left( -\frac{x}{3}+\frac{7}{3} \right)^2-1^2 \right)\,\ dx
$$

$$
V=\int_{-2}^2 \int_{x^2}^4 4x^2\,\ dy\,\ dx
$$
$$
\int_{-2}^2 4x^2(x^2-4)\,\ dx
$$
```desmos-graph
top=10;
---
y=x
x=8
y=8
```

```desmos-graph
y<\ln(x)|y>0|x<5
y=0
x=1
x=5
```
$$
x=e^y
$$
```desmos-graph
left=-5; right=5;
bottom=-1; top=10
---
(0,0)
(1,0)
(1,9)
y=0
x=1
y\leq9x|y\geq0|x\leq1
```

$$
f_{avg}=\frac{2}{9}\left( \int_{0}^1 \int_{0}^{9x} (6xy) \,\ dy\,\ dx \right)
$$
$$
f_{avg}=\frac{2}{9}\left( \int_{0}^13x(81x^2)\,\ dx \right)
$$

>[!Polar Problem]
>$\int \int_{D} 2xy^2\, dA$, where $D$ is the top half of the disk with center at the origin and radius $2$

$$
D=\left\{ (r,\ \theta) \bigr| 0 \leq r \leq 2,\ 0 \leq \theta \leq \pi \right\} 
$$
$$
\int_{0}^\pi \int_{0}^2 (2(r\cos \theta)^2(r\sin \theta)) \,\ r\,\ dr\,\ d\theta
$$
$$
\left[ \int_{0}^\pi \cos^2 \theta \sin\theta\,\ d\theta \right]
\left[ \int_{0}^5 r^4\,\ dr \right]
$$
$$
u=\cos \theta \to du = -\sin \theta \,\  d\theta
$$
$$
\left( -\frac{\cos^3(\theta)}{3} \right)\left( \frac{r^5}{5} \right)
$$
```desmos-graph
top=10; bottom=-10;
---
x={(64-y^2)}^{1/2}
```

$$
D=\left\{ (r,\ \theta) \bigr| 0 \leq r \leq 8,\ -\frac{\pi}{2} \leq \theta \leq \frac{\pi}{2} \right\} 
$$
$$
\int_{-\pi/2}^{\pi/2} \int_{0}^8 (e^{-(r\cos \theta)^2-(r\sin \theta)^2})  \, rdr\,\ d\theta
$$
$$
\int_{-\pi/2}^{\pi/2} \int_{0}^8 (e^{-r^2})\,\ r dr\,\ d\theta
$$
$$
\left[ \int_{-\pi/2}^{\pi/2} d\theta \right]\left[ \int_{0}^8(e^{-r^2}r)\,\ rdr \right]
$$
$$
\pi\left( -\frac{1}{2}(e^{-8^2}-1) \right)
$$
```desmos-graph
r=6\cos(3\theta)
r=6\cos(3\theta)|\pi/6 \leq \theta \leq \pi/2
```
$$
D=\left\{ (r,\ \theta) \bigr| 0 \leq r \leq 6,\ \frac{\pi}{6} \leq \theta \leq \frac{\pi}{2} \right\} 
$$
$$
\int_{\pi / 6}^{\pi/2} \int_{0}^{6\cos (3\theta)} rdr\,\ d\theta
$$
$$
18 \int_{\pi / 6}^{\pi/2} \cos^2(3\theta) \,\ d\theta
$$
```desmos-graph
left=-17; right=17;
bottom=-20; top=20;
---
x^2+y^2=15^2
```

$$
-15=3
$$
$$
15=8
$$
$$
\frac{5}{30}=\frac{1}{6}
$$
$$
\frac{y}{6}+\frac{11}{2}
$$
$$
\int_{0}^{2\pi} \int_{0}^{15} \frac{r\sin \theta}{6}+\frac{11}{2}\,\ rdr\,\ d\theta
$$
$$
\int_{0}^{2\pi} \int_{0}^{15} \frac{r^2\sin \theta}{6}+\frac{11r}{2}\,\ dr\,\ d\theta
$$
$$
\int_{0}^{2\pi} \frac{15^3\sin \theta}{27}+11(15)^2 \,\ d\theta
$$


$$
z=\frac{y}{6}+\frac{11}{2}
$$
$$
\int_{0}^{2\pi} \int_{0}^{15} \left( \frac{r\sin \theta}{6}+\frac{11}{2} \right) \,\ rdr\,\ d\theta
$$
$$
\int_{0}^{15} \frac{r^2\sin \theta }{6}+\frac{11r}{2} \,\ dr
$$
$$
\frac{15^3\sin \theta}{18}+\frac{11(15)^2}{4}
$$
>[!Problem]
>under the cone $z=\sqrt{ x^2+y^2 }$ and above the disk $x^2 + y^2 \leq 64$

```desmos-graph
left=-10; right=10
bottom=-10; top=10
---
x^2 + y^2 \leq 64
```

$$
D = \left\{ (r,\ \theta) \bigr| 0 \leq r \leq 8,\ 0 \leq \theta \leq 2\pi \right\} 
$$
$$
f(x,\ y) = \sqrt{ x^2+y^2 }
$$
$$
\int_{0}^{2\pi} \int_{0}^8 \sqrt{ (r\cos \theta)^2+ (r\sin \theta)^2}\,\ rdr\,\ d\theta
$$
$$
\int_{0}^{2\pi} \int_{0}^8 r^2\,\ dr\,\ d\theta
$$
$$
\left[ \int_{0}^{2\pi} d\theta \right] \left[ \int_{0}^8 r^2\,\ dr \right]
$$
$$
2\pi\left( \frac{1}{3}(8)^3 \right) = \frac{1024\pi}{3}
$$
>[!Problem]
>Use polar coordinates to find the volume of the given solid.
>
Enclosed by the hyperboloid $-x^2-y^2+z^2=46$ and the plane $z=7$

$$
z=f(x,\ y) = \sqrt{ x^2+y^2+46 }
$$
$$
x^2+y^2=3
$$
```desmos-graph
left=-4; right=4;
bottom=-4; top=4;
---
x^2+y^2=3
```
$$
f(x,\ y) = 7-\sqrt{ x^2+y^2+46 }
$$
$$
\int_{0}^{2\pi} \int_{0}^{\sqrt{ 3 }} (7 - \sqrt{ r^2+46 })\,\ rdr\,\ d\theta
$$
$$
\int_{0}^{2\pi} \int_{0}^\sqrt{ 3 } (7r-r\sqrt{ r^2+46 })\,\ dr\,\ d\theta
$$
$$
\left[ \int_{0}^{2\pi} d\theta \right] \left[ \int_{0}^\sqrt{ 3 } (7r-r\sqrt{ r^2+46 })\,\ dr \right]
$$
$$
2\pi\left( \frac{7r^2}{2} - \frac{1}{3}(r^2+46)^{3/2} \right)
$$
$$
2\pi\left( \frac{21}{2}-\frac{1}{3}(49)^{3/2} \right) = 2\pi\left( \frac{21}{2} - \frac{7^3}{3}+\frac{46^{3/2}}{3} \right)
$$
$$
2\pi\left( -\frac{623}{6}+\frac{2(46)^{3/2}}{6} \right)
$$


$$
x^2+y^2+z^2=25
$$
$$
z=\sqrt{ x^2 +y^2}
$$
$$
z=r
$$
$$
\int_{0}^{2\pi} \int_{z}^{\sqrt{ 25-z^2 }} rdrd\theta
$$
$$
r^2=25-z^2
$$
$$
r=\sqrt{ 25-z^2 }
$$

![[Pasted image 20250304083529.png#invert_B]]

$$
x^2+y^2+z^2 = 25
$$
$$
x^2+y^2+(\sqrt{ x^2+y^2 })^2=25
$$
$$
x^2+y^2=\frac{25}{2}
$$
$$
\int_{0}^{2\pi} \int_{0}^{5/\sqrt{ 2 }} (\sqrt{ 25-r^2 } - r)\,\ rdr\,\ d\theta
$$
$$
\left[ \int_{0}^{2\pi} d\theta \right] 
\left[ \int_{0}^{7/\sqrt{ 2 }}(r\sqrt{ 25-r^2 }-r^2)\,\ dr \right]
$$
$$
2\pi\left( -\frac{1}{3}(25-r^2)^{3/2}-\frac{1}{3}r^3 \right)
$$
$$
-\frac{2\pi}{3}\left( \left( \frac{25}{2} \right)^{3/2}+\frac{125}{6\sqrt{ 2 }}
-125 \right)
$$

$$
\Delta U = -W_{AB} = \frac{1}{2}k(x^2_{B}-x^2_{A})
$$
$$
U(x) = \frac{1}{2}kx^2 + const
$$

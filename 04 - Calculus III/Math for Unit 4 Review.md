#### Question 1
$$
\vec{r} = \left< t,\ \sin(t) \right> 
$$
$$
\vec{r}'(t) = \left< 1,\ \cos(t) \right> 
$$
$$
\int_{0}^{\pi/2}\left< t,\ 0 \right>  \cdot \left< 1,\ \cos(t) \right> \,\ dt
$$
$$
\int_{0}^{\pi/2} t\,\ dt
$$
#### Question 2
$$
\frac{Q}{dx} = 0
$$
$$
\frac{P}{dy} = x
$$
$$
\int\int-x\,\ dx
$$
```desmos-graph
(0,0)
(2,0)
(2,1)
y=x/2
```

$$
\int_{0}^2 \int_{0}^{x/2}-x\,\ dy\,\ dx
$$
#### Question 3
$$
z=g(x,\ y) = y+3
$$
$$
\int \int_{R}y(y+3)\sqrt{ 0^2+1^2+1 }\,\ dA
$$
$$
\sqrt{ 2 } \int_{0}^{2\pi}\int_{0}^1 r^3\sin^2(\theta)+3r^2\sin(\theta)\,\ dr\,\ d\theta
$$
#### Question 4
Divergence theorem (a closed, piecewise smooth surface enclosing a solid region, a vector field with continuous partial derivatives, and an outward-oriented normal vector on the surface)

$$
\nabla \cdot \vec{F} = 1+1+1=3
$$
$$
3\int_{0}^{2\pi}\int_{0}^\pi \int_{0}^3\,\ p^2\sin(\phi)\,\ d\rho\,\ d\phi\,\ d\theta
$$
#### Question 5
$$
\nabla \times \vec{F} = \left< 3x,\ x-3y,\ 2y \right> 
$$
$$
z=g(x,\ y)=3-3x-y
$$
$$
-g_{x} = 3
$$
$$
-g_{y}=1
$$
$$
\int \int_{R} \left< 3x,\ x-3y,\ 2y \right> \cdot \left< 3,\ 1,\ 1 \right>  \,\ dA
$$
$$
\int \int_{R} 9x+x-3y+2y\,\ dA = \int \int_{R} 10x-y\,\ dA
$$
```desmos-graph
(0,0)
(1,0)
(0,3)
y=-3x+3
```
$$
\int_{0}^1 \int_{0}^{-3x+3} 10x-y\,\ dy\,\ dx
$$
#### Question 6
$$
\nabla \cdot \vec{F} = 0+9x^2z^2+0=9x^2z^2
$$
$$
\int \int_{S} \mathbf{F} \cdot d\mathbf{S} = \int \int \int_{D} 9x^2z^2\,\ dV
$$
$$
\int_{-1}^{1}
\int_{-1}^{1}
\int_{-1}^{1} 9x^2z^2\,\ dy\,\ dz\,\ dx
$$
#### Question 7
$$
z=g(x,\ y) = xy
$$
$$
g_{x} = y
$$
$$
g_{y} = x
$$
$$
\int \int_{R} \sqrt{ y^2+x^2+1 } \, dA
$$
$$
\int_{0}^{2\pi} \int_{0}^1 r\sqrt{ r^2+1 }\,\ dr\,\ d\theta
$$
#### Question 8
##### Part A (Surface Area)
$$
r_{u} = \left< \cos(v),\ \sin(v),\ 0 \right> 
$$
$$
r_{v} = \left< -u\sin(v),\ u\cos(v),\ 1 \right> 
$$
$$
r_{u} \times r_{v} = \left< \sin(v),\ \cos(v),\ u\cos^2(v)+u\sin^2(v) \right> 
$$
$$
r_{u} \times r_{v} = \left< \sin(v),\ -\cos(v),\ u \right> 
$$
$$
|r_{u} \times r_{v}| = \sqrt{ \sin^2(v)+\cos^2(v)+u^2 } = \sqrt{ u^2+1 }
$$
$$
\int_{-1}^1 \int_{0}^{2\pi} \sqrt{ u^2+1 }\,\ dv\,\ du
$$
##### Part B (Tangent Plane)
$$
\vec{r}\left( \frac{1}{2},\ \frac{\pi}{3} \right) = \left< \frac{1}{4},\ \frac{\sqrt{ 3 }}{4},\ \frac{\pi}{3} \right> 
$$
$$
\vec{n} = \left< \frac{\sqrt{ 3 }}{2},\ -\frac{1}{2},\ \frac{1}{2} \right> 
$$
$$
\sqrt{ \frac{3}{2} }\left( x-\frac{1}{4} \right) -
\frac{1}{2}\left( y-\sqrt{ \frac{3}{4} } \right) +
\frac{1}{2}\left( z-\frac{\pi}{3} \right) = 0
$$
### 16.2 Line Integrals Reveiw
#### Q1
$$
x=t
$$
$$
y=t^2+4
$$
$$
-2\leq t\leq0
$$
$$
\vec{r}(t) = \left< t,\ t^2+4 \right> 
$$
$$
\vec{r}'(t) = \left< 1,\ 2t \right> 
$$
$$
f(r(t)) = 2t^3-3(t^2+4)=2t^3-3t^2-12
$$
$$
\int_{-2}^0 (2t^3-3t^2-12)(\sqrt{ 1+4t^2 })\,\ dt
$$
#### Q2
$$
0 \leq t \leq 1
$$
$$
\vec{r}(t) = \left< 2t+1,\ -4t+8,\ t+2 \right> 
$$
$$
\vec{r}'(t) = \left< 2,\ -4,\ 1 \right> 
$$
$$
f(\vec{r}(t)) = t+2+e^{(2t+1)(-4t+8)}
$$
$$
\int_{0}^1 (t+2+e^{(2t+1)(8-4t)})\sqrt{ 21 }\,\ dt
$$
#### Q3
$$
1 \leq t \leq 2
$$
$$
\vec{r}'(t) = \left< 1,\ 2t,\ 3t^2 \right> 
$$
$$
\vec{F}(\vec{r}(t)) = \left< t^3,\ -t^2,\ t \right> 
$$
$$
\int_{1}^2 t^3-2t^3+3t^3\,\ dt = \int_{1}^2 2t^3\,\ dt
$$
#### Q4
$$
\int_{C}3x^2-2y\,\ ds
$$
C is the line segment from $(3,\ 6)$ to $(1,\ -1)$
$$
\int_{0}^1 3(3-2t)^2-2(6-7t)\sqrt{ (-2)^2+(-7)^2 }\,\ dt
$$
#### Q5
$$
\int_{C}6x\,\ ds
$$
C is the portion of $y = x^2$ from $x=-1$ to $x=2$. The direction of $C$ is in the direction of increasing x.
$$
\vec{r}(t) = \left< t,\ t^2 \right> 
$$
$$
-1 \leq t \leq 2
$$
$$
\vec{r}'(t) = \left< 1,\ 2t \right> 
$$
$$
f(\vec{r}(t)) = 6x
$$
$$
\int_{-1}^2 6t\sqrt{ 1+4t^2 }\,\ dt
$$
#### Q6
$$
\int_{C} xy-4z\,\ ds
$$
$C$ is the line segment from $(1,\ 1,\ 0)$ to $(2,\ 3,\ -2)$
$$
\vec{r}(t) = \left< t+1,\ 2t+1,\ -2t \right> 
$$
$$
0\leq t\leq1
$$
$$
\vec{r}'(t) = \left< 1,\ 2,\ -2 \right> 
$$
$$
f(\vec{r}(t)) = (t+1)(2t+1)-4(-2t)
$$
$$
3\int_{0}^1 (t+1)(2t+1)-4(-2t) \,\ dt
$$
#### Q7
$$
\int_{C}2x^3\,\ ds
$$
$C$ is the portion $y=x^3$ from $x=-1$ to $x=2$
$$
\vec{r}(t) = \left< t,\ t^3 \right> 
$$
$$
-1 \leq t \leq 2
$$
$$
\vec{r}'(t) = \left< 1,\ 3t^2 \right> 
$$
$$
f(\vec{r}(t)) = 2t^3
$$
$$
\int_{-1}^2 2t^3\sqrt{ 1+9t^4 }\,\ dt
$$
#### Q7
$$
\int_{C}x^3\, dy-(y+1)\, dx
$$
$C$ is the line segment from $(1,\ 7)$ to $(-2,\ 4)$
$$
\vec{r}(t) = \left< 1-3t,\ 7-3t \right> 
$$
$$
0 \leq t \leq 1
$$
$$
\int_{0}^1 (1-3t)^3(-3)-(7-3t+1)(-3)\,\ dt
$$

### 16.3 FTC Review
#### Q1
##### Show it is conservative
$$
\frac{dQ}{dx} = 2x
$$
$$
\frac{dP}{dy} = 2x
$$
$$
\frac{dQ}{dx}-\frac{dP}{dy} = 0
$$
##### Potential Function
$$
\int 2xy \, dx = x^2y
$$
$$
\int x^2-y \, dy = x^2y-\frac{y^2}{2} 
$$
$$
f(x,\ y) = x^2y-\frac{y^2}{2}+C
$$
##### Line integral
$$
\int_{C}\mathbf{F}(x,\ y) \cdot d\vec{r} = f(\mathbf{r}(t_{2}))-f(\mathbf{r}(t_{1}))
$$
$$
f(\ln 3,\ e^2) - f(0,\ 1) = (\ln 3)^2e^2-\frac{e^4}{2}-0+\frac{1}{2}
$$
$$
e^2(\ln 3)^2-\frac{e^4}{2}+\frac{1}{2}
$$
#### Q2
##### Potential Function
$$
\int 3x^2z \,\  dx = x^3z
$$
$$
\int z^2 \,\ dy = yz^2
$$
$$
\int x^3+2yz \,\ dz = x^3z+yz^2
$$
$$
f(x,\ ,\ y,\ z) = x^3z+yz^2+C
$$
##### Line integral
$$
\int_{C}\mathbf{F}(x,\ y) \cdot d\vec{r} = f(0,\ 0,\ 0)-f(1,\ -1,\ -1)
$$
$$
0-1^3(-1)-(-1)(-1)^2=1+1=2
$$

### 16.4 Green's Theorem Review
#### Q1
$$
\int \int 1-2yx \, dA
$$
$$
\int_{0}^{2\pi} \int_{0}^{3} r-2r^3\sin(\theta)\cos(\theta)\,\ dr\,\ d\theta
$$
#### Q2
```desmos-graph
left = -4; right = 4;
bottom = -1; top = 10;
---
y=x^2 |-3 \leq x \leq 3
y=9
```
$$
\int_{-3}^{3} \int_{x^2}^9 -3x\,\ dy\,\ dx
$$
### 16.5 Curl and Divergence Review
#### Q1
##### Divergence
$$
\nabla \cdot \vec{F} = 2yz-z-\sin(z)
$$
##### Curl
$$
\nabla \times \vec{F} = \left< 0-(-y),\ 2xy-0,\ 2x-2xz \right> 
$$
$$
\nabla \times \vec{F} = \left< y,\ 2xy,\ 2x-2xz \right> 
$$
#### Q2
$$
\nabla \times \vec{F} = \left< 0-0,\ -\cos(z)-(-\cos z),\ x-x \right> 
$$
$$
\nabla \times \vec{F} = \left< 0,\ 0,\ 0 \right> 
$$
Curl is 0 so $\mathbf{F}$ is conservative
$$
\int xy-\sin(z) \, dx = \frac{1}{2}x^2y-x\sin(z)
$$
$$
\int \frac{1}{2}x^2 \, dy = \frac{1}{2}x^2y
$$
$$
\int -x\cos(z) \, dz = -x\sin(z) 
$$
$$
f(x,\ y,\ z) = \frac{1}{2}x^2y-x\sin(z)+C
$$
### 16.6 Parameteric Surfaces Review
#### Q1
##### Surface Area
$$
\vec{r}(u,\ v) = \left< u,\ \sin(u),\ v \right> 
$$
$$
\vec{r}_{u} = \left< 1,\ \cos(u),\ 0 \right> 
$$
$$
\vec{r}_{v} = \left< 0,\ 0,\ 1 \right> 
$$
$$
\vec{r}_{u} \times \vec{r}_{v} = \left< \cos(u),\ -1,\ 0 \right> 
$$
$$
|\vec{r}_{u} \times \vec{r}_{v}| = \sqrt{ \cos^2(u)+1 }
$$
$$
\int_{0}^4 \int_{0}^\pi \sqrt{ \cos^2(u)+1 } \, du\, dv \approx 15.28
$$
##### Tangent plane
$$
\vec{n} = \left< \frac{\sqrt{ 3 }}{2},\ -1,\ 0 \right> 
$$
$$
\frac{\sqrt{ 3 }}{2}\left( x-\frac{\pi}{6} \right)-\left( y-\frac{1}{2} \right)=0
$$
#### Q2
$$
y=g(x,\ z) = x^3
$$
$$
-g_{x} = -3x^2
$$
$$
-g_{z} = 0
$$
$$
\vec{n} = \left< -3x^2,\ 1,\ 0 \right> 
$$
This is pointing in the negative x direction for any nonzero value of x so we must flip it
$$
\vec{n} = \left< 3x^2,\ -1,\ 0 \right> 
$$
$$
\int \int_{R} \left< x^3z,\ x,\ -z^2 \right> \cdot \left< 3x^2,\ -1,\ 0 \right> dA
$$
$$
\int \int_{R} 3x^5z-x \, dA
$$
$$
\int_{0}^6 \int_{0}^2 3x^5z-x \,\ dx\,\ dz = 564
$$
### 16.7 Surface Integrals Review
#### Q1
$$
z=g(x,\ y) = 6-2x-3y
$$
$$
-g_{x} = 2
$$
$$
-g_{y} = 3
$$
$$
\int \int_{R} 2xy(6-2x-3y)\sqrt{ 2^2+3^2+1^2 }\,\ dA
$$
$$
\int \int_{R} 2xy(6-2x-3y)\sqrt{ 14 }\,\ dA
$$
```desmos-graph
(3,0)
(0,2)
(0,0)
y=-2x/3+2
```
$$
\sqrt{ 14 }\int_{0}^3 \int_{0}^{-2x/3+2} 2xy(6-2x-3y)\,\ dy\,\ dx
$$
#### Q2
$$
z=g(x,\ y) = 9-x^2-y^2
$$
$$
-g_{x} = 2x
$$
$$
-g_{y} = 2y
$$
$$
\int \int_{R} \left< 9-x^2-y^2,\ -y^2,\ x \right> \cdot \left< 2x,\ 2y,\ 1 \right> \,\ dA
$$
$$
\int_{0}^{2\pi} \int_{0}^3 \left< 9-r^2,\ -r^2\sin^2(\theta),\ r\cos(\theta) \right> \cdot \left< 2r\cos(\theta),\ 2r\sin(\theta),\ 1 \right> \,\ r\,\ dr\,\ d\theta
$$
$$
\int_{0}^{2\pi}\int_{0}^3 (18r\cos(\theta)-2r^3\cos(\theta)-2r^3\sin^3(\theta)+r\cos(\theta))r\,\ dr\,\ d\theta
$$
### 16.8 Stoke's Theorem Review
$$
\oint_{C} \mathbf{F}\cdot d\mathbf{r} = \iint_{S} (\nabla \times \mathbf{F}) \cdot \mathbf{n}\,\ dS
$$
#### Q1
##### Curl and Surface
###### Curl of $\mathbf{F}$:
$$
\nabla \times \mathbf{F} = \left< -2z,\ -1,\ 2y \right> 
$$
###### C is a plane:
$$
2x+y+z=8
$$
##### Setting up integrand
###### z is a function of x and y:
$$
z = g(x,\ y) = 8-2x-y
$$
###### Negative partial derivatives of g:
$$
-g_{x} = 2
$$
$$
-g_{y} = 1
$$
###### Finding final integrand:
$$
\iint_{R} \left< -2z,\ -1,\ 2y \right> \cdot \left< 2,\ 1,\ 1 \right> \,\ dA
$$
$$
\iint_{R} -4(8-2x-y)-1+2y\,\ dA
$$
$$
\iint_{R} -32+8x+4y-1+2y\,\ dA
$$
$$
\iint_{R} 8x+6y-33\,\ dA
$$
###### Finding bounds:
```desmos-graph
left = -1; right = 5;
bottom = -1; top = 9;
---
(4,0)
(0,0)
(0,8)
y=8-2x
```
$$
0 \leq x \leq 4
$$
$$
0 \leq y \leq 8-2x
$$
$$
\int_{0}^4 \int_{0}^{8-2x} 8x+6y-33\,\ dy\,\ dx = -\frac{304}{3}
$$
#### q2
$$
\nabla \times \mathbf{F} = \left< 1,\ 2z,\ 2 \right> 
$$
##### a) Circular region in xy-plane
$$
z = g(x,\ y) = 1
$$
$$
\vec{n} = \left< 0,\ 0,\ 1 \right> 
$$
$$
\iint_{R} \left< 1,\ 0,\ 2 \right> \cdot \left< 0,\ 0,\ 1 \right> \,\ dA
$$
$$
\iint_{R} 2\,\ dA = 2\pi(4)^2 = 32\pi \approx 100.53
$$ 
##### b) The paraboloid $z=16-x^2-y^2$
$$
z = g(x,\ y) = 16-x^2-y^2
$$
$$
-g_{x} = 2x
$$
$$
-g_{y} = 2y
$$
$$
\vec{n} = \left< 2x,\ 2y,\ 1 \right> 
$$
$$
\iint_{R} \left< 1,\ 2(16-x^2-y^2),\ 2 \right> \cdot \left< 2x,\ 2y,\ 1 \right> \,\ dA
$$
$$
\iint_{R} 2x+4y(1y-x^2-y^2)+2\,\ dA
$$
$$
\iint \mathbf{F}\cdot d\mathbf{S}
$$
### 14.8 Divergence Theorem Review
#### Q1
$$
\nabla \cdot \mathbf{F} = yz+0+1=yz+1
$$
$$
\int_{0}^{2} \int_{0}^{6-3x} \int_{0}^{6-3x-y} yz+1\,\ dz\,\ dy\,\ dx
$$
#### Q2
$$
\nabla \cdot \mathbf{F} = 2x+2-2=2x
$$
$$
\int_{0}^{2\pi}\int_{0}^2\int_{0}^{4-r^2}2r^2\cos(\theta)\,\ dz\,\ dr\,\ d\theta
$$


$$
\mathbf{F} = \left< z^2,\ y^2,\ x \right> 
$$
$$
\nabla \times \mathbf{F} = \left< 0,\ 2z-1,\ 0 \right> 
$$
$$
z = g(x,\ y) = 1-x-y
$$
$$
-g_{x} = 1
$$
$$
-g_{y} = 1
$$
$$
\iint_{R} \left< 0,\ 2z-1,\ 0 \right>  \cdot \left< 1,\ 1,\ 1 \right> \,\ dA
$$
$$
\iint_{R} 2z-1\,\ dA
$$
$$
\int_{0}^1\int_{0}^{1-x} 2(1-x-y)-1\,\ dy\,\ dx
$$
$$
\int_{0}^1\int_{0}^{1-x} 1-2x-2y\,\ dy\,\ dx
$$
$$
\int_{0}^1 (1-x)-2x(1-x)-(1-x)^2\,\ dx
$$

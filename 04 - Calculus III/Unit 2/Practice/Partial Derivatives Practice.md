## First order
### Problem 1
#### Problem
Determine the partial derivative with respect to x and y. Evaluate each at (2, -1)
$$
f(x,\ y) = \frac{{xy}}{x+y}
$$
#### Solution
##### With Respect to x
$$
f_{x} = \frac{{(x+y)y-(xy)}}{(x+y)^2}
$$
$$
f_{x} = \frac{{y^2}}{(x+y)^2}
$$
$$
f_{x}(2,\ -1) = \frac{1}{1} = 1
$$
##### With Respect to y
$$
f_{y} = \frac{x^2}{(x+y)^2}
$$
$$
f_{y}(2,\ -1) = \frac{4}{1}=4
$$
### Problem 2
#### Problem
Determine the partial derivative with respect to x and y.
$$
f(x,\ y) = \sin(x^2+y^2)
$$
#### Solution
##### With Respect to x
$$
f_{x} = 2x\cos(x^2+y^2)
$$
##### With Respect to y
$$
f_{y} = 2y\cos(x^2+y^2)
$$
### Problem 3
#### Problem
Use implicit differentiation to find $\frac{\partial z}{\partial x}$ and $\frac{\partial z}{\partial y}$
$$
x^2+4y^2+5z^2=4
$$
#### solution
##### Finding $\frac{\partial z}{\partial x}$
$$
\frac{\partial }{\partial x}(x^2+4y^2+5z^2) = \frac{\partial }{\partial x}(4)
$$
$$
2x+8y \frac{\partial y}{\partial x} +10z\frac{{\partial z}}{\partial x} = 0
$$
$$
\frac{\partial z}{\partial x} = -\frac{2x}{10z} = -\frac{x}{5z}
$$

## Second Order
### Problem 1
#### Problem
Determine the second order partial derivatives
$$
f(x,\ y) = 2x^4-5x^3y^3-y^4
$$
#### Solution
##### First Order With Respect to x
$$
f_{x} = 8x^3 - 15x^2y^3
$$
###### then with respect to x
$$
f_{x x} = 24x^2-30xy^3
$$
###### then with respect to y
$$
f_{xy} = -45x^2y^2
$$
##### First Order With Respect to y
$$
f_{y} = -15x^3y^2 - 4y^3
$$
###### then with respect to x
$$
f_{yx} = -45x^2y^2
$$
###### then with respect to y
$$
f_{yy} = -30x^3y-12y^2
$$

### Problem 2
#### Problem
Determine the second order partial derivatives
$$
f(x,\ y) = xe^{xy^2}
$$
#### Solution
##### First Order With Respect to x
$$
f_{x} = x(e^{xy^2}y^2)+e^{xy^2}
$$
$$
f_{x} = e^{xy^2}(xy^2+1)
$$
###### then with respect to x
$$
f_{x x} = e^{xy^2}(y^2) + (xy^2+1)e^{xy^2}y^2
$$
$$
f_{xx} = 2y^2e^{xy^2}+xy^4e^{xy^2}
$$
###### then with respect to y
$$
f_{xy} = e^{xy^2}(2xy) + (xy^2+1)(e^{xy^2}(2xy))
$$
$$
f_{xy} = 4xye^{xy^2}+2x^2y^3e^{xy^2}
$$
##### First Order With Respect to y
$$
f_{y} = xe^{xy^2}(2xy)
$$
$$
f_{y} = 2x^2ye^{xy^2}
$$
###### then with respect to x
$$
f_{yx} = f_{xy} = 4xye^{xy^2}+2x^2y^3e^{xy^2}
$$
###### then with respect to y
$$
f_{yy} = 2x^2y(e^{xy^2}(2xy)) + e^{xy^2}(2x^2)
$$
$$
f_{yy} = 4x^3y^2e^{xy^2}+2x^2e^{xy^2}
$$

### Problem 3
#### Problem
Determine the second order partial derivatives
$$
f(x,\ y) = 
$$
#### Solution
##### First Order With Respect to x
$$
f_{x} = 
$$
###### then with respect to x
$$
f_{x x} = 
$$
###### then with respect to y
$$
f_{xy} = 
$$
##### First Order With Respect to y
$$
f_{y} = 
$$
###### then with respect to x
$$
f_{yx} = 
$$
###### then with respect to y
$$
f_{yy} =
$$

## Stuff not organized

$$
f(x,\ y) = x^9y^6 - x^8y^5
$$
$$
f_{x}(x,\ y) = 9x^8y^6 - 8x^7y^5
$$
$$
f_{xx}(x,\ y) = 72x^7y^6 - 56x^6y^5
$$
$$
f_{xxx}(x,\ y) = 504x^6y^6 - 336x^5y^5
$$
$$
f_{x}(x,\ y) = 9x^8y^6 - 8x^7y^5
$$
$$
f_{xy}(x,\ y) = 54x^8y^5 - 40x^7y^4
$$
$$
f_{xyx}(x,\ y) = 432x^7y^5 - 280x^6y^4
$$

The total resistance $R$ produced by three conductors with resistance $R_{1},\ R_{2},\ R_{3}$ connected in a parallel electrical circuit is given by the formula
$$
\frac{1}{R} = \frac{1}{R_{1}}+\frac{1}{R_{2}}+\frac{1}{R_{3}}
$$
Find $\frac{\partial R}{\partial R_{1}}$

$$
\frac{\partial}{\partial R_{1}}\left( \frac{1}{R} \right) = \frac{\partial}{\partial R_{1}}(\frac{1}{R_{1}}+\frac{1}{R_{2}}+\frac{1}{R_{3}})
$$
$$
-\frac{1}{R^2} \left( \frac{\partial R}{\partial R_{1}} \right) = 
-\frac{1}{(R_{1})^2}\left( \frac{\partial R_{1}}{\partial R_{1}} \right) +
-\frac{1}{(R_{2})^2}\left( \frac{\partial R_{2}}{\partial R_{1}} \right) +
-\frac{1}{(R_{3})^2}\left( \frac{\partial R_{3}}{\partial R_{1}} \right) 
$$
assume $R_{2}$ and $R_{3}$ are constant
$$
-\frac{1}{R^2} \left( \frac{\partial R}{\partial R_{1}} \right) = 
-\frac{1}{(R_{1})^2}
$$
$$
\frac{\partial R}{\partial R_{1}} = \frac{R^2}{(R_{1})^2}
$$

![[Pasted image 20250214154929.png#invert_B]]

$$
\frac{\partial w}{\partial t} = \frac{\partial w}{\partial x} \cdot \frac{\partial x}{\partial t} + \frac{\partial w}{\partial y} \cdot \frac{\partial y}{\partial t} + \frac{\partial w}{\partial z} \cdot \frac{\partial z}{\partial t}
$$
$$
\frac{\partial w}{\partial t} = 
    e^{y/z}(9t^8) + 
    \frac{x}{z}e^{y/z}(-1) + 
    xe^{y/z}(-yz^{-2})(9)
$$
$$
\frac{\partial w}{\partial t} = e^{y/z}\left( 9t^8-\frac{x}{z}-9xyz^{-2} \right)
$$
![[Pasted image 20250214155809.png#invert_B]]
$$
\frac{\partial z}{\partial s} = \frac{\partial z}{\partial r} \cdot \frac{\partial r}{\partial s} + \frac{\partial z}{\partial \theta} \cdot \frac{\partial \theta}{\partial s} 
$$
$$
\frac{\partial z}{\partial s} = \cos(\theta)e^rt - e^r\sin (\theta)\left( \frac{8s^7}{2\sqrt{ s^8+t^8 }} \right)
$$
$$
\frac{\partial z}{\partial s} = e^r \left( \cos(\theta)t - \sin (\theta)\left( \frac{4s^7}{\sqrt{ s^8+t^8 }} \right) \right)
$$

$$
\frac{\partial z}{\partial t} = \frac{\partial z}{\partial r} \cdot \frac{\partial r}{\partial t} + \frac{\partial z}{\partial \theta} \cdot \frac{\partial \theta}{\partial t} 
$$
$$
\frac{\partial z}{\partial t} = \cos(\theta)e^rs -
e^r\sin(\theta)\left( \frac{8t^7}{2\sqrt{ s^8+t^8 }} \right)
$$
![[Pasted image 20250214161047.png#invert_B]]

$$
g(u,\ v) = f(e^u+\sin(v),\ e^u+\cos(v))
$$
$$
g(u,\ v) = f(x,\ y)
$$
$$
\frac{\partial g}{\partial u} = \frac{\partial f}{\partial x} \cdot \frac{\partial x}{\partial u} + \frac{\partial f}{\partial y} \cdot \frac{\partial y}{\partial u}
$$
$$
g_{u}(0,\ 0) = f_{x}(x(0,\ 0),\ y(0,\ 0))x_{u}(0,\ 0) + 
f_{y}(x(0,\ 0),\ y(0,\ 0))y_{u}(0,\ 0) 
$$
$$
g_{u}(0,\ 0) = f_{x}(1,\ 2)(1) + f_{y}(2,\ 1)(1)
$$
$$
g_{u}(0,\ 0) = 1 + 6 = 7
$$
$$
g_{v}(0,\ 0) = f_{x}(x(0,\ 0),\ y(0,\ 0))x_{v}(0,\ 0) + 
f_{y}(x(0,\ 0),\ y(0,\ 0))y_{v}(0,\ 0) 
$$
$$
g_{u}(0,\ 0) = f_{x}(1,\ 2)(1) + f_{y}(2,\ 1)(0)
$$
![[Pasted image 20250214163749.png#invert_B]]

$$
x=6,\ y=300
$$
$$
\frac{\partial z}{\partial x} = 4464,\ \frac{\partial z}{\partial y} = 36
$$
$$
\frac{\partial z}{\partial s} = 
    \frac{\partial z}{\partial x} \cdot \frac{\partial x}{\partial s} +
    \frac{\partial z}{\partial y} \cdot \frac{\partial y}{\partial s}
$$
$$
\frac{\partial z}{\partial s} = (4x^3+2xy)(1)+(x^2)(tu^2) = 8064
$$
$$
\frac{\partial z}{\partial t} = 
    \frac{\partial z}{\partial x} \cdot \frac{\partial x}{\partial t} +
    \frac{\partial z}{\partial y} \cdot \frac{\partial y}{\partial t}
$$
$$
\frac{\partial z}{\partial t} = 4464(2)+36(su^2) = 11628
$$
$$
\frac{\partial z}{\partial u} = 
    \frac{\partial z}{\partial x} \cdot \frac{\partial x}{\partial u} +
    \frac{\partial z}{\partial y} \cdot \frac{\partial y}{\partial u}
$$
$$
\frac{\partial z}{\partial u} = 4464(-1)+36(2stu) = -3600
$$
$$
\frac{\partial z}{\partial x} = 4x^3+2xy
$$
$$
\frac{\partial z}{\partial y} = x^2
$$

![[Pasted image 20250214233537.png#invert_B]]

$$
f(x,\ y) = 5y\cos(x)-x^2-y^2
$$
$$
F_{x} = -5y\sin(x)-2x
$$
$$
F_{y} = 5\cos(x)-2y
$$
$$
-\frac{F_{x}}{F_{y}} = -\frac{-5y\sin(x)-2x}{5\cos(x)-2y} = \frac{5y\sin(x)+2x}{5\cos(x)-2y}
$$
![[Pasted image 20250214234014.png#invert_B]]
$$
x^2+2y^2+7z^2=1
$$
$$
z=\sqrt{ \frac{1-x^2-2y^2}{7} } = \left( \frac{1-x^2-2y^2}{7} \right)^{1/2}
$$
$$
\frac{\partial z}{\partial x} = 
$$
$$
f(x,\ y,\ z) = x^2+2y^2+7z^2-1
$$
$$
F_{x} = 2x
$$
$$
F_{z} = 14z
$$
$$
\frac{\partial z}{\partial x} = -\frac{2x}{14z} = -\frac{x}{7z}
$$
$$
f_{y} = 4y
$$
$$
\frac{\partial z}{\partial y} = -\frac{4y}{14z} = -\frac{2y}{7}
$$
$$
T_{t}(x,\ y) = 7\left( \frac{1}{2\sqrt{ 1+3 }} \right) + 
7\left( \frac{1}{3} \right)
$$
$$
V = \frac{1}{3} \pi r^2h
$$
$$
\frac{\partial V}{\partial t} = \frac{2}{3}\pi rh \cdot \frac{\partial r}{\partial t} + \frac{1}{3}\pi r^2 \cdot \frac{\partial h}{\partial t}
$$
$$
PV = 8.31T
$$
$$
V = \frac{8.31T}{P}
$$
$$
\frac{\partial V}{\partial t} = \frac{8.31}{P} \cdot \frac{\partial T}{\partial t} + \left( -\frac{8.31T}{P^2} \right) \frac{\partial P}{\partial T}
$$
>[!Problem]
>Find the linear approximation fo the function $f(x,\ y,\ z) = \sqrt{ x^2+y^2+z^2 }$ at $(9,\ 2,\ 6)$ and use it to approximate the number $\sqrt{ 9.02^2+1.97^2+5.99^2 }$. 

$$
f(x,\ y,\ z) ≈ L(x_{0},\ y_{0},\ z_{0}) = f_{x}(x,\ y,\ z)(x_{0}-x) + f_{y}(x,\ y,\ z)(y_{0}-y) + f_{z}(x,\ y,\ z)(z_{0}-z)  
$$
$$
L(x_{0},\ y_{0},\ z_{0}) = f_{x}(x,\ y,\ z)(x_{0}-x) + f_{y}(x,\ y,\ z)(y_{0}-y) + f_{z}(x,\ y,\ z)(z_{0}-z) + f(x,\ y,\ z)
$$
$$
f_{x} = \frac{1}{2\sqrt{ x^2+y^2+z^2 }}(2x) = \frac{x}{\sqrt{ x^2+y^2+z^2 }}
$$
$$
f_{y} = \frac{y}{\sqrt{ x^2+y^2+z^2 }}
$$
$$
f_{z} = \frac{z}{\sqrt{ x^2+y^2+z^2 }}
$$
$$
L(9.02,\ 1.97,\ 5.99) = \frac{9}{11}(0.02)+\frac{2}{11}(-0.03)+\frac{6}{11}(-0.01)
$$
>[!Problem]
>Find the differential of the function. 
>$z=e^{-5x}\cos(9\pi t)$

$$
dz = \frac{dz}{dx}dx+\frac{dz}{dt}dt
$$
$$
\frac{dz}{dx} = e^{-5x}\cos(9\pi t)(-5)
$$
$$
\frac{dz}{dt} = -e^{-5x}\sin(9\pi t)(9\pi)
$$
>[!Problem]
>The length and width of a rectangle are measured at **34** and **50** cm, respectively, with an error in measurement of at most **0.1** cm in each. Use differentials to estimate the maximum error in the calculated area of the rectangle.

$$
A=lw
$$
$$
dA = wdl + ldw
$$
>[!Problem]
>If $R$ is the total resistance of three resistors, connected in parallel, with resistances $R_1$, $R_2$, $R_3$, then
>$\frac{1}{R} = \frac{1}{R_{1}}+\frac{1}{R_{2}}+\frac{1}{R_{3}}$
>If the resistances are measured in ohms as $R_{1}=10\ \Omega$, $R_{2}= 16\ \Omega$, $R_{3} = 100\ \Omega$, with a posible error of **0.5%** in each case, estimate the maximum error in the calculated value of $R$.

$$
\frac{1}{R} = \rho
$$
$$
d\rho = -\frac{1}{R_{1}^2}(dR_{1})-\frac{1}{R_{2}^2}(dR_{2})-\frac{1}{R_{3}^2}(dR_{3})
$$
>[!Problem]
>Find an equation of the tangent plane to the given surface at the specified point:
>$z=6(x-1)^2+5(y+3)^2+2$, $(2,\ -2,\ 13)$

$$
f(x,\ y,\ z) = 6(x-1)^2+5(y+3)^2-z+2
$$
$$
12(x-2)+10(y+2)+(-1)(z-13)=0
$$

>[!Problem]
>Find an equation of the tangent plane to the given surface at the specified point:
>$z=\sqrt{ xy }$, $(6,\ 6,\ 6)$

$$
f(x,\ y,\ z) = \sqrt{ x }\sqrt{ y }-z
$$
$$
f_{x} = \frac{\sqrt{ y }}{2\sqrt{ x }}
$$
$$
\frac{1}{2}(x-6)+\frac{1}{2}(y-6)+(-1)(z-6) = 0
$$

$$
f(x,\ y,\ z) = x^2yz-xyz^3,\ P(1,\ -1,\ 1),\ \mathbf{u}=\left< 0,\ \frac{4}{5},\ -\frac{3}{5} \right> 
$$
$$
\nabla f(x,\ y,\ z) = \left< 2xyz-yz^3,\ x^2z-xz^3,\ x^2y-3xyz^2 \right> 
$$
$$
\left< \frac{7}{2},\ \frac{7\sqrt{ 3 }}{2} \right> \cdot \left< \frac{-3}{5},\ \frac{4}{5} \right> 
$$
$$
\frac{-21}{10}
$$
$$
\nabla h(r,\ s,\ t) = \left( \frac{1}{3r+6s+9t} \right)\left< 3,\ 6,\ 9 \right> 
$$
$$
\nabla h(1,\ 1,\ 1) = \left< \frac{1}{6},\ \frac{1}{3},\ \frac{1}{2} \right> 
$$
$$
\mathbf{D}_{u}h(1,\ 1,\ 1) = \left< \frac{1}{6},\ \frac{1}{3},\ \frac{1}{2} \right>  \cdot \left< \frac{2}{7},\ \frac{6}{7},\ \frac{3}{7} \right> 
$$
$$
\nabla f(x,\ y) = \left< \frac{2y}{\sqrt{ x }},\ 4\sqrt{ x } \right> 
$$
$$
\nabla f(4,\ 7) = \left< 7,\ 8 \right> 
$$
$$
\sqrt{ 7^2+8^2 }
$$
$$
\nabla V(x,\ y,\ z) = \left< 8x-2y+yz,\ -2x+xz,\ xy \right> 
$$
$$
\nabla V(3,\ 6,\ 4) = \left< 36,\ 6,\ 18 \right> 
$$

>[!Random Physics problem will delete later]
A particle moves in a circle of radius $r = 2.0$ m. During the time interval from $t = 1.5$ s to $t = 4.0$ s, its speed varies with time according to
$v(t) = c_{1}-\frac{c_{2}}{t^2},\ c_{1} = 4.0\ m/s,\ c_{2} = 6.0\ m \cdot s$
What is the total acceleration of the particle at $t = 2.0$ s

$$
a_{c} = \frac{v^2}{r} = \frac{2.5^2}{2} = 3.125
$$
$$
a_{T} = \frac{2c_{2}}{t^3} = 1.5
$$
$$
\left< 3.125,\ 1.5 \right> 
$$

$$
F_{n} \sin \theta
$$
$$
mg = F_{n}\cos \theta
$$
![[Pasted image 20250218085833.png#invert_B]]
$$
f(x,\ y,\ z) = 2(x-9)^2+(y-3)^2+(z-7)^2-10
$$
$$
f_{x}(10,\ 5,\ 9)(x-10)+f_{y}(10,\ 5,\ 9)(y-5)+f_{z}(10,\ 5,\ 9)(z-9)=0
$$
$$
4(x-10)+4(y-5)+4(z-9)=0
$$

$$
t=\frac{x-10}{4}=\frac{y-5}{4}=\frac{z-9}{4}
$$
![[Pasted image 20250218091023.png#invert_B]]
$$
f(x,\ y) = xy
$$
$$
\nabla f(x,\ y) = \left< y,\ x \right> 
$$
$$
\nabla f(4,\ 3) = \left< 3,\ 4 \right> 
$$
$$
3(x-4)+4(y-3)=0
$$
$$
\left< 3,\ 4 \right> \cdot \left< x-4,\ y-3 \right> -0
$$
$$
3x-12+4y-12=0
$$
$$
3x+4y=24
$$

>[!Problem]
>Find the directional derivative of $f$ at the given point in the direction indicated by the angle $\theta$.
>$f(x,\ y) = 2ye^{-x},\ (0,\ 9),\ \theta = \frac{2\pi}{3}$

$$
D_{\mathbf{u}}f(0,\ 9) = \nabla f(0,\ 9) \cdot \left< \cos \theta,\ \sin \theta \right> 
$$
$$
\nabla f(x,\ y) = \left< -2ye^{-x},\ 2e^{-x} \right> 
$$
$$
\nabla f(0,\ 9) = \left< -18,\ 2 \right> 
$$
$$
D_{\mathbf{u}}f(0,\ 9) = \left< -18,\ 2 \right> \cdot \left< -\frac{1}{2},\ \frac{\sqrt{ 3 }}{2} \right> 
$$

>[!Find the local max, min, and saddle point]
>$f(x,\ y) = x^2+xy+y^2+8y$

$$
f_{x} = 2x+y
$$
$$
f_{y} = x+2y+8
$$
$$
f_{xx} = 2
$$
$$
f_{yy} = 2
$$
$$
f_{xy} = 1
$$
$$
2x+y=0
$$
$$
y=-2x
$$
$$
x+2(-2x)=-8
$$
$$
x=\frac{8}{3}
$$
$$
y=-\frac{16}{3}
$$
$$
D\left( \frac{8}{3},\ -\frac{16}{3} \right) = 2*2-1=3>0
$$
$$
f_{xx}=2>0
$$
Local minmum



#### Local MAx PRoblem
>[!Find the local max, min, saddle point(s)]
>$f(x,\ y) = 2x^3-6x+6xy^2$

$$
f_{x} = 6x^2-6+6y^2
$$
$$
f_{y} = 12xy
$$
$$
f_{xx} = 12x
$$
$$
f_{yy} = 12x
$$
$$
f_{xy} = 12y
$$
##### Case 1: x = 0
$$
6y^2=6
$$
$$
y=1
$$
$$
D(0,\ 1) = -1
$$
inconclusive
##### Case 2: y = 0
###### Case 2a: x = 1
$$
D(1,\ 0) = 144-0 > 0
$$
$$
f_{xx} = 12 > 0
$$
local min
###### Case 2b: x = -1
$$
D(-1,\ 0) = 
$$

#### Local Critical point problem
>[!Find the local max, min, and saddle point]
>$f(x,\ y) = y^2-4y\cos(x),\ -4≤x≤4$

$$
f_{x} = 4y\sin (x)
$$
$$
f_{y} = 2y-4\cos(x)
$$
$$
f_{xx} = 4y\cos(x)
$$
$$
f_{yy} = 2
$$
$$
f_{xy} = 4\sin(x)
$$
##### Case 1: x = 0
$$
y=2
$$
$$
D(0,\ 2) = 8 \cdot 2 - 0^2 = 16 > 0
$$
$$
f_{xx} = 8 > 0
$$
local min at (0,2)
$$
f(0,\ 2) = 2^2-4(2)(1) = 4-8 = -4
$$
##### Case 2: y = 0
$$
-4\cos(x) = 0
$$
$$
\cos(x) = 0
$$
$$
x = \frac{\pi}{2},\  -\frac{\pi}{2}
$$
###### Case 2a: x = π/2
$$
D\left( \frac{\pi}{2},\ 0 \right) = 0-4 = -4 < 0
$$
saddle point at $\left( \frac{\pi}{2},\ 0 \right)$
###### Case 2a: x = -π/2
saddle point at $\left( -\frac{\pi}{2},\ 0 \right)$

#### Find absolute max and min on domain
>[!Problem]
>Find the absolute maximum and minimum values of $f$ on the set $D$
>$f(x,\ y) = x^2+y^2+x^2y+5,\ D = \left\{ (x,\ y) \mid |x| ≤ 1,\ |y| ≤ 1 \right\}$

$$
f_{x} = 2x+2xy
$$
$$
f_{y} = 2y+x^2
$$
$$
f_{xx} = 2+2y
$$
$$
f_{yy} = 2
$$
$$
f_{xy} = 2x
$$
$$
2y+x^2 = 0 \to 2y = -x^2
$$
$$
2x+x(-x^2) = 0
$$
$$
2x = x^3
$$
$$
x = \pm \sqrt{ 2 }
$$
##### Case 1: $x = +\sqrt{ 2 }$
$$
2y+2 = 0
$$
$$
y = -1
$$
$$
D(\sqrt{ 2 },\ -1) = 0-(2\sqrt{ 2 })^2<0
$$
##### Conclusion
$$
f(1,\ 1) = 8
$$
$$
f(-1,\ 1) = 8
$$
$$
f(1,\ -1) = 6
$$
$$
f(-1,\ -1) = 
$$
#### Find absolute max and min on domain
>[!Problem]
>Find the absolute maximum and minimum values of $f$ on the set $D$.
>$f(x,\ y) = 2x^3+y^4+8,\ D = \left\{ (x,\ y) \mid x^2+y^2 \leq 1 \right\}$

$$
f_{x} = 6x^2
$$
$$
f_{y} = 4y^3
$$
$$
f_{xx} = 12x
$$
$$
f_{yy} = 12y^2
$$
$$
f_{xy} = 0
$$
$$
D(0,\ 0) = 0
$$
$$
f(0,\ 0) = 8
$$


$$
y^2 = 1-x^2
$$
$$
g(x)=f(x,\ y) = 2x^3+(1-x^2)^2+8 = x^4+2x^3-2x^2+1,\ -1 ≤ x ≤ 1
$$


$$
x^2+y^2 \leq 1
$$
$$
y^2 ≤ 1-x^2
$$
#### Minimizing cardboard box
>[!Problem]
>A cardboard box without a lid is to have a volume of 10,976 cubic cm. Find the dimensions in cm that minimize the amount of cardboard used.

$$
xy+2(xz+yz),\ if\ xyz=10976
$$
$$
z=\frac{10976}{xy}
$$
$$
f(x,\ y) = xy+2z(x+y) = xy+\frac{21952(x+y)}{xy}
$$
$$
f(x,\ y) = xy+\frac{21952}{y}+\frac{21952}{x}
$$
$$
f_{x} = y-\frac{21952}{x^2}
$$
$$
f_{y} = x-\frac{21952}{y^2}
$$
$$
y=\frac{21952}{x^2}
$$
$$
0=x-\frac{21952}{\left( \frac{21952}{x^2} \right)^2}
$$
$$
0=x-\frac{x^4}{21952}
$$
$$
x=28
$$
$$
y=28
$$
$$
D(28,\ 28) = \left( \frac{-2 \cdot -21952}{28^3} \right)^2-1
$$

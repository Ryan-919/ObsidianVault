### Problems from YT Video
>[!Find all second partial derivatives]
>$f(x,\ y) = \sin(x^2-y^2)$

$$
f_{x} = 2x\cos(x^2-y^2)
$$
$$
f_{xx} = -4x^2\sin(x^2-y^2)+2\cos(x^2-y^2)
$$
$$
f_{xy} = 4xy\sin(x^2-y^2)
$$
$$
f_{y} = -2y\cos(x^2-y^2)
$$
$$
f_{yy} = -4y^2\sin(x^2-y^2) - 2\cos(x^2-y^2)
$$
$$
f_{yx} = 4xy\sin(x^2-y^2)
$$
>[!Find the differential]
>$\omega = xy^2\cos(z)$

$$
d\omega = \frac{\partial \omega}{\partial x}dx+\frac{\partial \omega}{\partial y}dy+\frac{\partial \omega}{\partial z}dz
$$
$$
d \omega = y^2\cos(z)dx + 2xy\cos(z)dy-xy^2\sin(z)dz
$$
>[!Derive 2nd partial derivative]
>Derive $\frac{\partial ^2z}{\partial t^2}$ for the function below
>$z=f(r,\ \theta),\ r=g(s,\ t),\ \theta = h(s,\ t)$

$$
\frac{\partial z}{\partial t} = \frac{\partial z}{\partial r} \cdot \frac{\partial r}{\partial t}+\frac{\partial z}{\partial \theta} \cdot \frac{\partial \theta}{\partial t}
$$
$$
\frac{\partial}{\partial t} \left( \frac{\partial z}{\partial t} \right) =\frac{\partial}{\partial t}\left(  \frac{\partial z}{\partial r} \cdot \frac{\partial r}{\partial t}+\frac{\partial z}{\partial \theta} \cdot \frac{\partial \theta}{\partial t} \right)
$$
$$
\frac{\partial^2 z}{\partial t^2}=

\left( \frac{\partial}{\partial t}\left( \frac{\partial z}{\partial r} \right) \right) \frac{\partial r}{\partial t} + 
\left( \frac{\partial}{\partial t}\left( \frac{\partial r}{\partial t} \right) \right) \frac{\partial z}{\partial r} 

+

\left( \frac{\partial}{\partial t}\left( \frac{\partial z}{\partial \theta} \right) \right) \frac{\partial \theta}{\partial t} + 
\left( \frac{\partial}{\partial t}\left( \frac{\partial \theta}{\partial t} \right) \right) \frac{\partial z}{\partial \theta} 
$$

#### Maximum Rate of Change
>[!Find the maximum rate of change at the given point and the direction] 
>$f(x,\ y) = \sin(xy),\ (1,\ 0)$

##### How to find
$$
\vec{D_{u}}f = \nabla f \cdot \vec{u} = |\nabla f||\vec{u}|\cos \theta
$$
- Since the value of $\vec{u}$ is always 1 and the maximum value of $\cos \theta$ is 1, the **maximum rate of change** of $f$ is simply $|\nabla f|$. 
- This also means that the **direction** of the maximum rate of change **is** the directional derivative since $\cos \theta$ is at its maximum of 1 at $0°$
##### Solution
$$
\nabla f(x,\ y) = \left< y\cos(xy),\ x\cos(xy) \right> 
$$
$$
\nabla f(1,\ 0) = \left< 0,\ 1 \right> 
$$
$$
|\nabla f(1,\ 0)| = 1
$$
**Maximum rate of change** is $1$ in the **direction** $\left< 0,\ 1 \right>$

#### local extrema/saddle points
>[!Local extrema and saddle points]
>Find them for the function $f(x,\ y) = x^2+y^4+2xy$.
>Label each as a max, min, or saddlepoint.

##### How to find
###### Find first partial derivatives
A point $(a,\ b)$ is called a critical point of $f$ if all first partial derivatives = 0, or if one of them DNE.
$$
f_{x} = 2x+2y
$$
$$
f_{y} = 4y^3 + 2x
$$
###### Find extrema: when both partial derivatives = 0
$$
0 = 2x+2y
$$
$$
0 = 4y^2+2x
$$
$$
2x+2y = 4y^3+2x
$$
$$
1=2y^2
$$
3 extrema: $(0,\ 0),\ \left( \sqrt{ \frac{1}{2} },\ -\sqrt{ \frac{1}{2} } \right),\ \left( -\sqrt{ \frac{1}{2} },\ \sqrt{ \frac{1}{2} } \right)$
###### D test

The basic of **D** is that by analyzing all 2nd derivatives, you can figure out if a certain extrema is a max, min, or neither (saddle point)

$$
D = 
\begin{vmatrix}
f_{xx} & f_{yx} \\
f_{xy} & f_{yy}
\end{vmatrix} = 
f_{xx}f_{yy}-f_{xy}f_{yx} = 
f_{xx}f_{yy}-(f_{xy})^2
$$
- $D > 0$ and $f_{xx}(a,\ b)>0$  it's a min
- $D > 0$ and $f_{xx}(a,\ b)<0$  it's a max
- $D < 0$ it's a saddle point
- $D = 0$ inconclusive

##### Solution
###### Find partial derivatives and D
$$
f_{x} = 2x+2y
$$
$$
f_{y} = 4y^3+2x
$$
$$
f_{xx} = 2
$$
$$
f_{yy} = 12y^2
$$
$$
f_{xy} = f_{yx} = 2
$$
$$
D(x,\ y) = \begin{vmatrix}
2 & 2 \\
2 & 12y^2
\end{vmatrix} = 
24y^2-4
$$
###### Plug in extrema to D and evaluate
$$
D(0,\ 0) = -4
$$
Since $D < 0$, $(0,\ 0)$ is a **saddle point**

$$
D\left( -\frac{1}{\sqrt{ 2 }},\ \frac{1}{\sqrt{ 2 }} \right) = 8
$$
Since $D > 0$ and $f_{xx} = 2 > 0$, $\left( -\frac{1}{\sqrt{ 2 }},\ \frac{1}{\sqrt{ 2 }} \right)$ is a **local minimum**

$$
D\left( \frac{1}{\sqrt{ 2 }},\ -\frac{1}{\sqrt{ 2 }} \right) = 8
$$
Since $D > 0$ and $f_{xx} = 2 > 0$, $\left( \frac{1}{\sqrt{ 2 }},\ -\frac{1}{\sqrt{ 2 }} \right)$ is a **local minimum**
### Problems from Review Sheet
#### Limit
$$
\lim_{ (x,\ y) \to (0,\ 0) } = \frac{2xy}{2x^2-3y^2}
$$
##### a) Evaluate the limit along $y=2x$
$$
\lim_{ (x,\ y) \to (0,\ 0) } \frac{2x(2x)}{2x^2-3(2x)^2} = 
\lim_{ (x,\ y) \to (0,\ 0) } \frac{4x^2}{2x^2-12x^2} = 
\lim_{ (x,\ y) \to (0,\ 0) } -\frac{4x^2}{10x^2}
$$
$$
\lim_{ (x,\ y) \to (0,\ 0) } -\frac{4x^2}{10x^2} = -\frac{4}{10} = -\frac{2}{5}
$$
##### b) Evaluate the limit along $y =x^2$
$$
\lim_{ (x,\ y) \to (0,\ 0) } \frac{2x(x^2)}{2x^2-3(x^2)^2} = 
\lim_{ (x,\ y) \to (0,\ 0) } \frac{2x^3}{2x^2-3x^4} 
$$
$$
\lim_{ (x,\ y) \to (0,\ 0) } \frac{2x^3}{2x^2-3x^4} = 0
$$
##### c) What can be concluded about the limit
The limit **does not exist** because the limit along 2 different paths are not equal

##### Other problems
>[!Determine the limit]

$$
\lim_{ (x,\ y) \to (1,\ 2) } \left( \frac{5x^2y}{x^2+y^2} \right) = \frac{10}{5} = 2
$$
>[Determine the limit]

$$
\lim_{ (x,\ y) \to (0,\ 0) } = \left( \frac{2x-3y^2}{x^2+y^2} \right)^2
$$
$$
x=y \to \frac{1}{4}
$$
$$
y=x^2 \to -9
$$

#### Find partial derivatives
>[!Problem]
>Find $f_{x}$ and $f_{xy}$ for the function
>$f(x,\ y) = 3x^2y^3-5x^3+2y^6-1$

$$
f_{x} = 6xy^3-15x^2
$$
$$
f_{xy} = 18xy^2
$$
#### Find Partial derivative 2 functions 2 variables
>[!Problem]
>Find $\frac{\partial z}{\partial u}$ if $z=\sin\left( \frac{2x^2}{y^3} \right)$ where $x = u^2-3v$ and $y=(2uv)^2$.
>Leave your answer in terms of $x$, $y$, $v$, and $u$.

$$
\frac{\partial z}{\partial u} = 
\frac{\partial z}{\partial x} \cdot \frac{\partial x}{\partial u} +
\frac{\partial z}{\partial y} \cdot \frac{\partial y}{\partial u}
$$
$$
\frac{\partial z}{\partial x} = \frac{4x}{y^3}\cos\left( \frac{2x^2}{y^3} \right)
$$
$$
\frac{\partial x}{\partial u} = 2u
$$
$$
\frac{\partial z}{\partial y} = -\frac{6x^2}{y^4}\cos\left( \frac{2x^2}{y^3} \right)
$$
$$
\frac{\partial y}{\partial u} = 8uv^2
$$
$$
\frac{\partial z}{\partial u} = 
\left( \frac{4x}{y^3}\cos\left( \frac{2x^2}{y^3} \right) \right)(2u) -
\left( \frac{6x^2}{y^4}\cos\left( \frac{2x^2}{y^3} \right) \right)(8uv^2)
$$
$$
\frac{\partial z}{\partial u} = \frac{8xu}{y^3}\cos\left( \frac{2x^2}{y^3} \right)\left( 1-\frac{6xv^2}{y} \right)
$$


#### Implicit Differentiation
>[!Problem]
>Find $\frac{\partial z}{\partial x}$ for the equation 
>$x^2-\ln(xyz)+2ye^{3xz}=15$
##### Method 1: Implicit Differentiation
$$
\frac{\partial}{\partial x}(x^2-\ln(xyz)+2ye^{3xz}) = \frac{\partial}{\partial x} (15)
$$
$$
2x-\frac{1}{xyz}\left( xy\left( \frac{\partial z}{\partial x} \right) + 
yz \right) + 2ye^{3xz}\left( 3x\left( \frac{\partial z}{\partial x} 
\right) + 3z \right) = 0
$$
$$
-\frac{x\left( \frac{\partial z}{\partial x} \right)}{xz} - \frac{z}{xz} + 
6xye^{3xz}\left( \frac{\partial z}{\partial x} \right) + 6yze^{3xz} = -2x
$$
$$
\frac{\partial z}{\partial x} \left( -\frac{1}{z}+6xye^{3xz} \right) = 
\frac{1}{x} -2x-6yze^{3xz}
$$
$$
\frac{\partial z}{\partial x} = \frac{\left( \frac{1}{x} -2x-6yze^{3xz} \right)}{\left( -\frac{1}{z}+6xye^{3xz} \right)}
$$
##### Method 2: Implicit Function Theorem
$$
\frac{\partial z}{\partial x} = -\frac{f_{x}}{f_{z}}
$$
$$
f_{x} = 2x - \frac{yz}{xyz} + 2ye^{3xz}(3z) = 2x-\frac{1}{x}+6yze^{3xz}
$$
$$
f_{z} = -\frac{xy}{xyz} + 2ye^{3xz}(3x) = -\frac{1}{z}+6xye^{3xz}
$$
$$
\frac{\partial z}{\partial x} = -\frac{\left( 2x-\frac{1}{x}+6yze^{3xz} \right)}{\left( -\frac{1}{z}+6xye^{3xz} \right)} = \frac{\left( \frac{1}{x} -2x-6yze^{3xz} \right)}{\left( -\frac{1}{z}+6xye^{3xz} \right)}
$$
#### Tangent Plane
>[!Problem]
>Find the point on the surface $z = 9-x^2-y^2$ where the tangent plane is parallel to the plane $2x+3y+2z=6$

- Since the surface is in the form $z = f(x,\ y)$ equation of the tangent plane is $z = f_{x}(x-x_{0})+f_{y}(y-y_{0})+z_{0}$ 
- This means the normal vector to the tangent plane is $\left< -f_{x},\ -f_{y},\ 1 \right>$ or $\left< 2x,\ 2y,\ 1 \right>$
- The normal vector to the desired plane is $\left< 2,\ 3,\ 2 \right>$
- Since we want the normal vectors to be parallel we can have one be equal to the scalar multiple of another:
	- $k\left< 2x,\ 2y,\ 1 \right> = \left< 2,\ 3,\ 2 \right>$
- $k=2$ to match up the z coordinate
	- $\left< 4x,\ 4y,\ 2 \right> = \left< 2,\ 3,\ 2 \right>$
- We can solve for x, y, z
	- $4x = 2$
		- $x = \frac{1}{2}$
	- $4y = 3$
		- $y = \frac{3}{4}$
	- $z = 9-\left( \frac{1}{2} \right)^2-\left( \frac{3}{4} \right)^2$
		- $z = \frac{131}{16}$
- Our final answer:
	- $\left( \frac{1}{2},\ \frac{3}{4},\ \frac{131}{16} \right)$

#### Directional Vector
>[!Problem]
>Find the rate of change in $z$ in the direction of the vector $\left< 2,\ 1 \right>$ at the point $(2,\ 3,\ 6)$ given $z=40-4x^2-2y^2$. Is this rate of change in $z$ at the point $(2,\ 3,\ 6)$ in the direction of $\left< 2,\ 1 \right>$ the greates decrease? If not, then in which direction is the greatest rate of decrease?

$$
z = f(x,\ y) = 40-4x^2-2y^2
$$
$$
\nabla f = \left< -8x,\ -4y \right> 
$$
$$
D = \nabla f \cdot \left< \frac{2}{\sqrt{ 5 }},\ \frac{1}{\sqrt{ 5 }} \right> 
$$
$$
D(2,\ 3) = \left< -16,\ -12 \right> \cdot \left< \frac{2}{\sqrt{ 5 }},\ \frac{1}{\sqrt{ 5 }} \right> 
$$
$$
D(2,\ 3) = -\frac{32}{\sqrt{ 5 }} -\frac{12}{\sqrt{ 5 }} = -\frac{44}{\sqrt{ 5 }}
$$
Since $\left< 2,\ 1 \right>$ is not a scarlar multiple of the gradient $-16,\ -12$, the rate of change along $\left< 2,\ 1 \right>$ is **neither the greatest increase or decrease**.

The greatest decrease will be in the direction of $-\nabla f(2,\ 3)=\left< 16,\ 12 \right>$.

#### Maximum Percent Change
>[!Problem]
>Find the maximum percent change in the pressure of a confined gas if the temperature changes by 2% and the volume changes by 5%. THe function relating $P$, $T$, and $V$ is $P=\frac{kT}{V}$ for a constant $k$.

Want to find $\frac{dP}{P}$
$$
P = \frac{kT}{V}
$$
$$
dP = \frac{\partial P}{dT} \cdot \partial T + \frac{\partial P}{\partial V}\cdot dV
$$
$$
dP = \frac{k}{V}dT-\frac{kT}{V^2}dV
$$
$$
\frac{dP}{P} = \frac{dP}{\left( \frac{kT}{V} \right)}=dP\left( \frac{v}{kT} \right)= \frac{dT}{T}-\frac{dV}{V} = 0.02-0.05 = 0.07 = 7\%
$$

#### Critical Points
>[!Problem]
>Find all relative maximum, relative minimum, and saddle points that occur on the surface given by the function $z=x^2+\frac{1}{3}y^3-2xy-3y$. Be sure to classify each critical point.

$$
z=f(x,\ y)=x^2+\frac{1}{3}y^3-2xy-3y
$$
$$
f_{x} = 2x-2y
$$
$$
f_{y} = y^2-2x-3
$$
$$
f_{x}=f_{y}=0
$$
$$
2x-2y=0
$$
$$
x=y
$$
$$
x^2-2x-3=0
$$
$$
(x-3)(x+1) = 0
$$
$$
x = y =3,\ -1
$$
$$
(3,\ 3,\ -9)\ a nd\ \left( -1,\ -1,\ \frac{5}{3} \right)\ are\ critical\ p o i n t s
$$
$$
D=f_{xx}f_{yy}-f_{xy}^2
$$
$$
f_{xx} = 2
$$
$$
f_{yy} = 2y
$$
$$
f_{xy} = -2
$$
$$
D=4y-2
$$
$$
D(3,\ 3) = 10
$$
Since $D(3,\ 3)$ and $f_{xx}$ are greater than 0, $(3,\ 3,\ -9)$ is a **local minimum**

$$
D(-1,\ -1) = -6
$$
Since $D(3,\ 3)$ is less than 0, $\left( -1,\ -1,\ \frac{5}{3} \right)$ is a **saddle point**

$$
z=f(x,\ y)
$$
### Problems idc to organize

>[!Chain Rule]
>Determine $\frac{\partial w}{\partial u}$ and $\frac{\partial w}{\partial v}$ if $w(x,\ y)=2xy$ and $x=\frac{u}{v}$ and $y=u^2+v^2$

$$
\frac{\partial \omega}{\partial u} = \frac{\partial \omega}{\partial x}\cdot \frac{\partial x}{\partial u} + \frac{\partial \omega}{\partial y}\cdot \frac{\partial y}{\partial u}
$$
$$
\frac{\partial \omega}{\partial u} = 2y\left( \frac{1}{v} \right)+2x(2u)
$$
$$
\frac{\partial \omega}{\partial v} = 2y\left( -\frac{u}{v^2} \right)+2x(2v)
$$

>[!Chain rule]
>Determine $\frac{\partial z}{\partial x}$ for $3x^2z-x^2y^2+\sin(yz)=5$

$$
f(x,\ y,\ z) = 3x^2z-x^2y^2+\sin(yz)-5
$$
$$
\frac{\partial z}{\partial x} = -\frac{f_{x}}{-f_{z}}
$$
$$
f_{x} = 6xz-2xy^2
$$
$$
f_{z} = 3x^2+y\cos(yz)
$$
$$
\frac{\partial z}{\partial x} = -\frac{6xz-2xy^2}{3x^2+y\cos(yz)}
$$

>[!Directional Derivative]
>Determine the directional derivative of $f(x,\ y)=x^2\sin(2y)$ at $\left( 1,\ \frac{\pi}{6} \right)$ in the direction of $\vec{u} = \left< 3,\ -4 \right>$

$$
D_{u} = \nabla f \cdot \vec{v}
$$
$$
\nabla f = \left< 2x\sin(2y),\ 2x^2\cos(2y) \right> 
$$
$$
\nabla f\left( 1,\ \frac{\pi}{6} \right) = \left< \sqrt{ 3 },\ 1 \right> 
$$
$$
\vec{v} = \left< \frac{3}{5},\ -\frac{4}{5} \right> 
$$
$$
D_{u} = \left< \sqrt{ 3 },\ 1 \right> \cdot \left< \frac{3}{5},\  -\frac{4}{5} \right> 
$$
$$
\frac{3\sqrt{ 3 }}{5}-\frac{4}{5}
$$

>[!Directional Derivative]
>Fourier's Law of heat transfer states that heat flows in the opposite direction of the gradient vector. 
>Suppose the temperature on a metal plate is given by $T(x,\ y) = 200-4x^2-y^2$ where temperature is in °F and length is measured in inches. 
>Determine the direction of the flow of heat and rate of change of the temperature at the point $(2,\ -3)$ on the plate.

$$
\nabla T(x,\ y) = \left< -8x,\ -2y \right> 
$$
$$
\nabla T(2,\ -3) = \left< -16,\ 6 \right> 
$$
Direction: $\left< 16,\ -6 \right>$

$$
-|\nabla f(2,\ -3)| = -|\left< -16,\ 6 \right> | = -\sqrt{ 16^2+6^2 } = -\sqrt{ 292 } \approx -17.09\ \frac{°F}{in}
$$

>[!Extrema]
>Determine and classify the relative extrema of $f(x,\ y) = -x^3+4xy-2y^2+1$

$$
f_{x} = -3x^2+4y
$$
$$
f_{y} = 4x-4y
$$


>[!Extrema]
>Determine the absolute extrema of $f(x,\ y)=3x^2+2y^2-4y$ on the region bounded by $y=x^2$ and $y=4$

>[!Problem]
>Find $\frac{\partial z}{\partial x}$ and $\frac{\partial z}{\partial y}$ 

$$
f(x,\ y,\ z) = x^2\sin(y^3)+xe^{3z}-\cos(z^2)-3y+6z-8
$$
$$
f_{z} = 3xe^{3z}+2z\sin(z^2)+6
$$
$$
f_{x}=2x\sin(y^3)+e^{3z}
$$
$$
f_{y} = x^23y^2\cos(y^3)-3
$$
$$
\frac{\partial z}{\partial x} = -\frac{f_{x}}{f_{z}} = 
\frac{-2x\sin(y^3)-e^{3z}}{3xe^{3z}+2z\sin(z^2)+6}
$$
$$
\frac{\partial z}{\partial y} = -\frac{f_{y}}{f_{z}} = 
\frac{-x^23y^2\cos(y^3)+3}{3xe^{3z}+2z\sin(z^2)+6}
$$

### Misc

$$
f_{x} = \ln(4y)+\frac{1}{2\sqrt{ x+y }} = 3.4
$$
$$
f_{y} = \frac{4x}{4y}
$$

>[! Find differential]
>$z=x^2\sin(6y)$

$$
dz=\frac{\partial z}{\partial x}dx+\frac{\partial z}{\partial z}dy
$$
$$
dz = (2x\sin(6y))dx+6x^2\cos(6y)dy
$$

>[!Find differential]
>$f(x,\ y,\ z) = \ln\left( \frac{xy^2}{z^3} \right)$

$$
df = \frac{y^2}{z^3}\left( \frac{z^3}{xy^2} \right)dx+\frac{2xy}{z^3}\left( \frac{z^3}{xy^2} \right)-\frac{3xy^2}{z^4}\left( \frac{z^3}{xy^2} \right)
$$


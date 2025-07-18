### 2D Vectors
#### Overview
##### Definition
- **Vector quantities** are measurements that require more than a single quantity to describe their attributes
- **Force** and **velocity** are examples
	- Require both **magnitude** and **direction** to completely describe
##### Representation
>[!Line Segment]
A directed line segment is used to represent a vector quantity or vector
- The **length** of the vector models the **magntitude**
- The **arrowhead** models the **direction**
- The **origin** of the segment is called the **initial point**
- The arrowhead points to the **terminal point**

![[VectorVisual]]
#### Position Vectors
##### Definition
- A vector with its initial point at the origin is called a position vector. 
- A position vector **u** with its endpoint at the point (a, b) is written as $\langle a, b \rangle$
- The numbers **a** and **b** are the **horizontal** and **vertical components** of vecetor **u**
- The positive angle between the x-axis and a position vector is the direction angle for the vector
##### Formulas
###### Magnitude
$$
|\vec{u}^{\,}| = \sqrt{ a^2+b^2 }
$$
###### Direction
$$
\tan\theta = \frac{b}{a}, a≠0
$$
###### Horizontal and Vertical Components
$$
a=|\vec{u}|\cos \theta
$$
$$
b=|\vec{u}|\sin \theta
$$
$$
\vec{u} = \langle a, b\rangle = \langle |\vec{u}|\cos \theta, |\vec{u}|\sin \theta\rangle
$$
##### Unit Vectors
- Vector with magnitude 1
- Two useful unit vectors are
	- $\vec{i}=\langle 1,0 \rangle$
	- $\vec{j}=\langle 0,1 \rangle$
- With unit vector **i** and **j**, any vector in the form $\langle a,b \rangle$ can be expressed in the form $ai+bj$
$$
\vec{v} = \langle a,b \rangle = a \vec{i} + b \vec{j}
$$
$$
where\ \vec{i} = \langle 1, 0 \rangle\ and\ \vec{j} = \langle 0,1 \rangle
$$

#### Vector Operations
##### Addition of Vectors
>[!resultant]
>The sum of two or more vectors
###### Triangular Method

- Draw the vectors one after another and place the initial point of the next vector at the terminal point of the first vector. Also called the tail to tip method.
![[Pasted image 20250110103551.png#invert_B]]
##### Dot Product
###### Basic overview
- The dot product of two vectors $u = \langle a,b \rangle$ and $v = \langle c,d \rangle$ is denoted as $\vec{u} \cdot \vec{v} = ac + bd$
- The dot product measures the similarity or alignment of two vectors
- If **positive**, the angle between the two vectors is **acute**
- If **zero**, the vectors are **perpendicular**
- If **negative**, the angle between the vectors is **obtuse** 
###### Examples
- $u = \langle 2,4 \rangle$ and $v = \langle -3,1 \rangle$
	- $2(-3)+4(1) = -6+4 = -2$
	- angle is **obtuse**
- $u = \langle 5,3 \rangle$ and $v = \langle -3,5 \rangle$
	- $-15+15 = 0$
	- angle is **90°**
- $u = \langle 2,-3 \rangle$ and $v = \langle 0,-2 \rangle$
	- $0+6 = 6$
	- angle is **acute**

###### Geometric Interpretation
If $\theta$ is an angle between the two nonzero vectors **u** and **v**, where $0°≤\theta≤180°$, then
$$
\vec{u}\cdot\vec{v}= |\vec{u}||\vec{v}|\cos \theta
$$
$$
or
$$
$$
\cos \theta=\frac{{\vec{u}\cdot\vec{v}}}{|\vec{u}||\vec{v}|}
$$
###### Example
Determine the angle between the two given vectors $u = \langle 2,1 \rangle$ and $v = \langle -3,1 \rangle$
$$
\cos \theta=\frac{{\vec{u}\cdot\vec{v}}}{|\vec{u}||\vec{v}|}=\frac{{-6+1}}{\sqrt{ 5 }\sqrt{ 10 }}= \frac{{-1}}{\sqrt{ 2 }}=\frac{3\pi}{4}=135°
$$

#### Unit Vectors
##### Overview
###### Definition
- A unit vector is a vector with magnitude 1. Two useful unit vectors are
	- $\vec{i}=\langle 1,0 \rangle$
	- $\vec{j}=\langle 0,1 \rangle$
- With unit vector **i** and **j**, any vector in the form $\langle a,b \rangle$ can be expressed in the form $ai+bj$ (called a linear combination of **i** and **j**)
$$
\vec{v} = \langle a,b \rangle = a \vec{i} + b \vec{j}
$$
$$
where\ \vec{i} = \langle 1, 0 \rangle\ and\ \vec{j} = \langle 0,1 \rangle
$$
###### Normalizing a Vector
- A unit vector, **u**, in the same direction of **v** is given by dividing **v** by its magntitude:
$$
\vec{u} = \frac{{\vec{v}}}{||\vec{v}||}
$$
>[!Remember]
$\Vert \vec{v} \Vert=\sqrt{ a^2+b^2 }$

- If **u** is a unit vector and $\theta$ is the angle from the **positive x-axis** to **u**, then the terminal point of the vector is on the unit circle such that 
$$
\vec{u} = \langle \cos \theta,\sin \theta \rangle = \cos \theta \vec{i}+\sin \theta \vec{j}
$$
- It follows if **v** is not a unit vector then
$$
\vec{v} = ||\vec{v}|| \langle \cos \theta,\sin \theta \rangle = ||\vec{v}|| \cos \theta \vec{j} + ||\vec{v}||\sin \theta \vec{j}
$$
##### Examples
###### Normalizing a Vector
Write the given vector as a linear combination of **i** and **j**. Then normalize the vector. 
$$
\vec{v}=\langle 4,-3 \rangle
$$

 1. Linear combination: $4\vec{i}-3\vec{j}$
 2. Normalize the vector: 
 $$
\vec{u} = \frac{{\vec{v}}}{||\vec{v}||} = \frac{{\langle 4,-3 \rangle}}{\sqrt{ (4)^2 + (-3)^2 }} = \langle \frac{4}{5},-\frac{3}{5} \rangle
$$

###### Determining a unit vector
Determine the unit vector that forms a 120° with the positive x-axis in standard position. Then determine a vector in the same direction with magnitude of 3. Then sketch both vectors.

1. Unit Vector
$$
\vec{u} = \langle \cos (120°),\sin (120°) \rangle = \langle -\frac{1}{2}, \frac{\sqrt{ 3 }}{2} \rangle
$$

2. Vector with magntitude 3
$$
\vec{v} = 3\langle -\frac{1}{2}, \frac{\sqrt{ 3 }}{2} \rangle = \langle -\frac{3}{2}, \frac{3\sqrt{ 3 }}{2} \rangle
$$

$$
\left< 2,1,1 \right> \times \left< -4,3,1 \right> = \left< 1(1)-1(3), -(2(1)-1(-4)), 2(3)-1(-4) \right> = \left< -2,-6,10 \right> 
$$
$$
area = \frac{1}{2} \left| \vec{PQ} \times \vec{PR} \right| = \frac{1}{2} \left( \sqrt{ 
\left( (1-(-1))(2-0)-(-1-0)(1-(-1)) \right)^2 + 
\left( (-1-0)(-1-1) - (2-1)(2-0) \right)^2 +
\left( (2-1)(1-(-1)) - (1-(-1))(-1-1) \right)^2 
} \right) 
$$
$$
\frac{1}{2} \left( \sqrt{ 6^2+0^2+6^2 } \right) = 3\sqrt{ 2 }
$$
$$
\tau = \vec{r} \times \vec{F} = \left< 2(-1)-(-1(1), 3(1)-2(-1), (-1)(-1)-3(-1)\right>\ N \cdot m = \left< -1, 5, 4 \right>\ N \cdot m
$$
$$
\vec{r}(t) = \vec{r_{0}} + t \vec{v} = \left< x_{0},\ y_{0},\ z_{0} + t\left< a,\ b,\ c, \right> \right>
$$
$$
\vec{r_{0}}\ is\ a\ position\ vector
$$
$$
\vec{v}\ is\ a\ direction\ vector
$$
$$
\vec{r_{0}} = \left< 1,\ -2,\ -3 \right>
$$
$$
\vec{v} = \left< 4,\ -5,\ -1 \right> - \left< 1,\ -2,\ -3 \right> = \left< 3,\ -3,\ 2 \right> 
$$
$$
\vec{r}(t) = \left< 1+3t,\ -2-3t,\ -3+2t \right> 
$$
$$
\frac{{x-x_{0}}}{a}=\frac{{y-y_{0}}}{b}=\frac{{z-z_{0}}}{c}
$$
$$
r(t) = \left< -2,\ 0,\ 4 \right> + t\left< 2,\ 4,\ -2 \right> 
$$
$$
r(t) = \left< -3,2,-3 \right> + t\left< 4,-3,7 \right> 
$$
$$
\left< -1, 7, -2 \right> \times \left< 4,11,-5 \right> =
\left< 7(-5)-(-2)11,\ -2(4)-(-1)(-5),\ -1(11)-7(4) \right> =
\left< -13,\ -13,\ -39 \right> 
$$
$$
-13(x-1)-13(y+3)-39(z-6)=0
$$
$$
\left< 1,-2,1 \right> \times \left< 2,3,-2 \right> = 
\left< -2(-2)-1(3),\ 1(2)-1(-2),\ 1(3)-(-2)2 \right> =
\left< 1, 4, 7 \right> 
$$
$$
4z=7y
$$
$$
z=\frac{7}{4},\ y=\frac{4}{7}
$$
$$
r(t) = \left< 1,4,7 \right> +t\left< 2,0,0 \right> 
$$
$$
4x^2-3y^2+12z^2+8x-12y=-28
$$
$$
(4x^2+8x)-(3y^2+12y)+12z^2=-28
$$
$$
4(x^2+2x)-3(y^2+4y)+12z^2=-28
$$
$$
4(x^2+2x+1)-3(y^2+4y+4)+12z^2=-28+4+4(-3)=-36
$$
$$
4(x+1)^2-3(y+2)^2+12z^2=-36
$$
$$
\frac{{4(x+1)^2}}{-36}-\frac{{3(y+2)^2}}{-36}+\frac{{12z^2}}{-36}=-\frac{36}{-36}
$$
$$
-\frac{{(x+1)^2}}{9}+\frac{{(y+2)^2}}{12}-\frac{{z^2}}{-3}=1
$$
hyperboloid of 2 sheets. 
opens in the y direction
Sheets are on the x and z axis
$(y+2)^2>12$ or $(y+2)^2<-12$
Vertical traces are hyperbolas
center (-1, -2, 0)

$$
4y^2-16y+z^2-4z+20=x
$$
$$
4(y^2-4y)+(z^2-4z)+20=x
$$
$$
4(y-2)^2+(z-2)^2=x
$$
$$
\frac{{(y-2)^2}}{1^2}+\frac{{(z-2)^2}}{2^2}=\frac{x}{2^2}
$$
Elliptic paraboloid
Vertex at (0, 2, 2)
Opens in the positive x direction


$$
\sqrt{ x^2 + y^2 } = 5 + y
$$
$$
x^2+y^2=(y+5)^2
$$
$$
x^2+y^2=y^2+10y+25
$$
$$
x^2=10y+25
$$
$$
y=\frac{{x^2-25}}{10}
$$
$$
r(t) = ti + \frac{{x^2-25}}{10}j+
$$
$$
\cos \theta = \frac{{\vec{u} \cdot \vec{v}}}{\Vert u \Vert \Vert v \Vert}
$$
$$
\left< 5, 0, 0 \right>\ an d\ \left< \cos t,\ 3\cos(3t),\ 2 \right> 
$$
$$
\left< 5, 0, 0 \right>\ an d\ \left< 1,\ 3,\ 2 \right> 
$$
$$
-t^3 \rightarrow -\frac{1}{4}t^4
$$
$$
5t^9 \rightarrow \frac{1}{2}t^{10}
$$
$$
r(t)=t^3\vec{i} + t^4\vec{j} + \frac{2}{3}t^{3/2}\vec{k} + \vec{c}
$$
$$
r(1) = \vec{i} + \vec{j} + \frac{2}{3}\vec{k}+\vec{c} = \vec{i} + \vec{j}
$$
$$
\vec{c} = -\frac{2}{3}\vec{k}
$$
$$
r(t)=t^3\vec{i} + t^4\vec{j} + \frac{2}{3}t^{3/2}\vec{k} -\frac{2}{3}\vec{k}
$$
$$
u(t) = \left< \sin(3t),\ \cos(2t),\  t \right> 
$$
$$
v(t) = \left< t,\ \cos(2t),\ \sin(3t) \right> 
$$
$$
u'(t) = \left< 3\cos(3t),\ -2\sin(2t),\ 1 \right> 
$$
$$
v'(t) = \left< 1,\ -2\sin(2t),\ 3\cos(3t) \right> 
$$
$$
3\cos(3t)t-2\sin(2t)\cos(2t)+\sin(3t)
$$
$$
\sin(3t)-2\sin(2t)\cos(2t)+3\cos(3t)t
$$
$$
\left< 1,\ -3,\ 4 \right> 
$$
$$
\left< x,\ y-1,\ z \right> 
$$
$$
x=t,\ y=-3t+1,\ z=4t
$$

$$
\lambda = \left< 1,3,5 \right> - \left< -2,1,0 \right> = \left< 3,2,5 \right> 
$$
$$
r(t) = \left< -2,1,0 \right> + t\left< 3,2,5 \right> 
$$
$$
r(t) = \left< -2+3t,\ 1+2t,,\ 5t \right> 
$$
$$
\mathbf{r} \cdot \mathbf{s} = 2xz-16y+18xz=20xz-16y
$$
$$
\mathbf{r} \times \mathbf{s} = 
\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\ 
2z & 4y & 6x \\ 
x & -4 & 3z \\ 
\end{vmatrix} = 
\begin{vmatrix}
4y & 6x \\
-4 & 3z
\end{vmatrix}\mathbf{i} - 
\begin{vmatrix}
2z & 6x \\
x & 3z
\end{vmatrix} \mathbf{j} + 
\begin{vmatrix}
2z & 4y \\
x & -4
\end{vmatrix} \mathbf{k}
$$
$$
\mathbf{r} \times \mathbf{s} = \left< 12yz+24x,\ 6x^2 - 6z^2,\ -4z-4xy \right> 
$$
$$
\cos \theta = \frac{{\vec{v} \cdot \vec{u}}}{\Vert \vec{v} \Vert \Vert \vec{u} \Vert}
$$
$$
\theta = \cos^{-1} \left( \frac{{\vec{v} \cdot \vec{u}}}{\Vert \vec{v} \Vert \Vert \vec{u} \Vert} \right)
$$
$$
\vec{a} \times \vec{b} = \left< 1(8)+6(8),\ -6-15,\ 24-1 \right>  = \left< 56,\ -21,\ 23 \right> 
$$
$$
 \frac{{\left< 56,\ -21,\ 23 \right>}}{\sqrt{ 56^2+21^2+23^2 }} = \left< \frac{56}{\sqrt{ 4106 }},\ -\frac{21}{\sqrt{ 4106 }},\ \frac{23}{\sqrt{ 4106 }} \right> 
$$
$$
W = \vec{F} \cdot \vec{d} = 50+125+30=205\ N \cdot m
$$
$$
\tau = \vec{r} \times \vec{F} = \left< 5\cos(45°),\ 5 \sin (45°),\ 0 \right> \times \left< 0,\ -3,\ 0 \right> =
\left< 0,\ 0,\ -10.6 \right>\ ft \cdot lbs.
$$
$$
r_{1}'(t) = \left< 2,\ 2t,\ 0 \right>
$$
$$
r_{2}'(t) = \left< 0,\ 2t,\ 5 \right>
$$
$$
r_{1}'(1) \times r_{2}'(1) = \begin{vmatrix}
i & j & k \\
2 & 2 & 0 \\
0 & 2 & 5
\end{vmatrix} = 
\left< 10,\ -10,\ 4 \right> 
$$
$$
\cos \theta = \frac{{r_{1}'(1) \cdot r_{2}'(1)}}{\Vert r_{1}'(1) \Vert \Vert r_{2}'(1) \Vert}
$$
$$
\theta = \cos^{-1} \left( \frac{{r_{1}'(1) \cdot r_{2}'(1)}}{\Vert r_{1}'(1) \Vert \Vert r_{2}'(1) \Vert} \right) = \cos^{-1} \frac{4}{2(\sqrt{ 29 })} = 1.305\ rad
$$
$$
v(t) = r'(t) = \left< 1,\ 3t^2,\ 3 \right>
$$
$$
a(t) = r''(t) = \left< 0,\ 6t,\ 0 \right>
$$
$$
T(t) = \frac{{r'(t)}}{|r'(t)|} = \frac{{\left< 3,\ 4t \right> }}{\sqrt{ 3^2 + (4t)^2 }} = \frac{{\left< 3,\ 4t \right> }}{\sqrt{ 9 + 16t^2 }}
$$
$$
T(t) = (9+16t^2)^{-1/2}\left< 3,\ 4t \right> 
$$
$$
T'(t) = \left( \left( -\frac{1}{2}(9+16t^2)^{-3/2} \right) 32t\ \right)\left< 3,\ 4t \right> + \frac{1}{\sqrt{ 9+16t^2 }}\left< 0,\ 4 \right> 
$$
$$
T'(t) = \frac{{-16t}}{\left( 9+16t^2 \right)^{3/2} }\left< 3,\ 4t \right>\ +\ \frac{{9+16t^2}}{\left( 9+16t^2 \right)^{3/2}}\left< 0,\ 4 \right>
$$
$$
T'(t) = \frac{{\left< -48t,\ 36 \right> }}{\left( 9+16t^2 \right)^{3/2}} = \frac{12}{\left( 9+16t^2 \right)^{3/2}}\left< -4t,\ 3 \right> 
$$
$$
N(t) = \frac{T'(t)}{|T'(t)|} = \frac{{\frac{12}{\left( 9+16t^2 \right)^{3/2}}\left< -4t,\ 3 \right> }}{\frac{12}{\left( 9+16t^2 \right)^{3/2}} \sqrt{ 16t^2+9 } } = \frac{1}{\sqrt{ 16t^2+9 }}\left< -4t,\ 3 \right> 
$$
$$
v(t) = r'(t) = \left< 3,\ -1,\ 2t \right> 
$$
$$
a(t) = v'(t) = \left< 0,\ 0,\ 2 \right> 
$$
$$
a_{T} = \frac{{\mathbf{v} \cdot \mathbf{a}}}{|\mathbf{v}|}=
\frac{4t}{\sqrt{ 10+4t^2 }}
$$
$$
a_{N} = \frac{{|\mathbf{v} \times \mathbf{a}|}}{|\mathbf{v|}} = \frac{\sqrt{ 4+36 }}{\sqrt{ 10+4t^2 }} = \frac{10\sqrt{ 10 }}{\sqrt{ 10+4t^2 }} 
$$
$$
L = \int_{0}^2 \sqrt{ 1^2+(2\sqrt{ t })^2 + t^2 }\ dt = 
\int_{0}^2 \sqrt{ 1+4t+t^2 }\ dx ≈ 4.816
$$
$$
\kappa(t) = \frac{{|r'(t) \times r''(t)|}}{|r'(t)|^3}  
$$
$$
r'(t) = \left< 2,\ 2t,\ -t^2 \right> 
$$
$$
r''(t) = \left< 0,\ 2,\ -2t \right> 
$$
$$
\kappa(t) = \frac{{\sqrt{ (-4t^2+2t^2)^2 + (-4t)^2 + (4)^2 }}}{(\sqrt{ 4+4t^2+t^4 })^3}
$$
$$
\kappa(t) = \frac{{\sqrt{ 4t^4 + 16t^2 + 16 }}}{(t^2+2)^3}
$$
$$
\kappa(t) = \frac{2(t^2+2)}{(t^2+2)^3}
$$
$$
\kappa(t) = \frac{2}{(t^2+2)^2}
$$
$$
a_{T} = \frac{{\mathbf{v} \cdot \mathbf{a}}}{|\mathbf{v}|}=
\frac{{r'(t) \cdot r''(t)}}{|r'(t)|}
$$
$$
a_{T} = \frac{{0+4t+2t^3}}{\sqrt{ 4+4t^2+t^4 }} = 
\frac{{2t^3 + 4t}}{t^2+2} = 2t
$$
$$
a_{N} = \frac{{|\mathbf{v} \times \mathbf{a}|}}{|\mathbf{v|}} = \frac{{|r'(t) \times r''(t)|}}{|r'(t)|} 
$$
$$
\kappa(t) = \frac{{|r'(t) \times r''(t)|}}{|r'(t)|^3}  
$$
$$
a_{N} = \frac{{|r'(t) \times r''(t)|}}{|r'(t)|^3}|r'(t)|^2=
\kappa|r'(t)|^2
$$
$$
a_{N} = \frac{2}{(t^2+2)^2}(t^2+2)^2=2
$$
$$
\vec{r}'(t) = \left< -\sin(t),\ \cos (t),\ 2 \right> 
$$
$$
\vec{r}''(t) = \left< -\cos(t),\ -\sin(t),\ 0 \right> 
$$
$$
\vec{r}'(t) \cdot \vec{r}''(t) = \sin(t)\cos(t)
-\sin(t) \cos(t)+0=0
$$
$$
\vec{r}'(t) \times \vec{r}''(t) = \left< 2\sin(t),\ 
-2\cos(t),\ 1
\right> 
$$
$$
(0,4,1)-(2,1,1) = \left< -2,3,0 \right> 
$$
$$
(-2,1,4)-(2,1,1)=\left< -4,0,3 \right> 
$$
$$
\left< -2,3,0 \right> \times \left< -4,0,3 \right> =
\left< 9,6,12 \right> 
$$
$$
9(x-2)+6(y-1)+12(z-1)=0
$$
$$
9x+6y+12z=36
$$
$$
3x+2y+4z=12
$$
$$
\theta = \cos^{-1}\left( \frac{{\left< 1,-2,1 \right> \cdot \left< 2,3,-2 \right>  }}{(\sqrt{ 1^2+2^2+1^2 })(\sqrt{ 2^2+3^2+2^2 })} \right)
$$
$$
\theta = \cos^{-1} \left( \frac{{-6}}{\sqrt{ 6 }\sqrt{ 17 }} \right) = 126.45° \to 53.55°
$$
- hyperboloid of one sheet that opens along the y axis.
- the center is (0,0,0) and vertices are at (±0.5,0,0) and (0,0,±0.5)
$$
z=y^2-x^2
$$
- hyperbolic paraboloid

$$
16x^2-32x+9y^2-36y+16z^2=-36
$$
$$
16(x-1)^2+9(y-2)^2+16z^2=16
$$
$$
\frac{(x-1)^2}{1^2}+\frac{(y-2)^2}{\left( \frac{4}{3} \right)^2}+\frac{z^2}{1^2}=1
$$
Elipsoid with center at (1, 2, 0) with vertices at (1, 2, 1), ()
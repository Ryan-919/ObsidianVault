## Unit 1
### 3D Space, Vectors, & Dot Product (12.1-12.3)

#### 3d Space
##### Distance
$$
d = \sqrt{ (x_{2}-x_{1})^2 + (y_{2}-y_{1})^2 + (z_{2}-z_{1})^2 }
$$
###### Explanation
- Pythagorean theorem can be repeatedly applied to add additional dimensions

##### Midpoint
$$
\left( \frac{{x_{1}+x_{2}}}{2}, \frac{{y_{1}+y_{2}}}{2}, \frac{{z_{1}+z_{2}}}{2} \right)
$$
###### Explanation
- Average of the each coordiante yields the midpoint

#### Vectors

##### Magnitude
$$
\Vert\vec{u}^{\,}\Vert = \sqrt{ a^2+b^2+c^2}  
$$
###### Explanation
- Derived from the **distance formula** in three-dimensional space
- Pythagorean theorem can be repeatedly applied to add additional dimensions
##### Dot Product
$$\vec{u} \cdot \vec{v} = ac + bd$$
$$
where\ \vec{u} = \langle a,\ b \rangle\ and\ \vec{v} = \langle c,\ d \rangle
$$

###### Explanation
- The dot product measures the similarity or alignment of two vectors
- If **positive**, the angle between the two vectors is **acute**
- If **zero**, the vectors are **perpendicular**
- If **negative**, the angle between the vectors is **obtuse** 
##### Unit Vectors

$$
\vec{v} = \langle a,\ b,\ c \rangle = a \vec{i} + b \vec{j} + c \vec{k}
$$
$$
where\ \vec{i} = \langle 1,\ 0,\ 0 \rangle ,\ \vec{j} = \langle 0,\ 1,\ 0 \rangle, and\ \vec{k} = \left< 0,\ 0,\ 1 \right> 
$$
###### Explanation
- A unit vector is a vector with **magnitude 1**. 
- Three useful unit vectors are
	- $\vec{i}=\langle 1,\ 0,\ 0 \rangle$
	- $\vec{j}=\langle 0,\ 1,\ 0 \rangle$
	- $\vec{k}=\langle 0,\ 0,\ 1 \rangle$
- With unit vector **i**, **j**, and **k**, any vector in the form $\langle a,\ b,\ c \rangle$ can be expressed in the form $a\vec{i}+b\vec{j} + c\vec{k}$ (called a linear combination of **i**, **j**, and **k**)

##### Normalizing a Vector
$$
\vec{u} = \frac{{\vec{v}}}{||\vec{v}||}
$$
###### Explanation
- Convert a vector into a unit vector in the same direction by dividing by magnitude

##### Relating θ with Dot Product
$$
\cos \theta = \frac{{\vec{a} \cdot \vec{b}}}{\Vert a \Vert \Vert b \Vert}
$$
###### Explanation
- [[Dot Product Visual]]

##### Scalar Projection (comp)
$$
comp_{b}a = \frac{{\vec{a} \cdot \vec{b}}}{\Vert b \Vert}
$$
$$
scalar\ projection\ of\ \vec{a}\ onto\ \vec{b}
$$ 
###### Explanation
- [[Dot Product Visual]]
##### Vector Projection (proj)
$$
proj_{b}a = \left( \frac{{\vec{a} \cdot \vec{b}}}{\Vert b \Vert^2} \right)b
$$
$$
vector\ projection\ of\ \vec{a}\ onto\ \vec{b}
$$
###### Explanation
- [[Dot Product Visual]]
- [[Vector Projection]]
- Unit vector of $\vec{b}$ multiplied by $comp_{b}a$

##### Cross Product
$$
\vec{u} \times \vec{v} = \left< u_{2}v_{3}-u_{3}v_{2},\ -(u_{1}v_{3}-u_{3}v_{1}),\ u_{1}v_{2}-u_{2}v_{1} \right>
$$
$$
\vec{u} \times \vec{v} = -( \vec{u} \times \vec{v} )
$$
$$
|\vec{u} \times \vec{v}| = \Vert u \Vert \Vert v \Vert \sin \theta
$$
###### Torque
$$
\tau = r \times F
$$
###### Area of a Triangle 
$$
po i nts\ P,\ Q,\ R
$$

$$
area = \frac{{\Vert\overline{PQ} \times \overline{PR} \Vert}}{2}
$$
###### Volume of a Parallelepiped
$$
3\ ve c tors\ a,\ b,\ c
$$
$$
volume = |(a \times b) \cdot c|
$$

###### Explanation
- [[Cross Product Visual]]
- To find the area, find the magntitude of the cross product of 2 of the sides that share a point and divide by 2

#### Lines & Planes
##### Line Equation
$$
\vec{r}(t) = \vec{r_{0}} + t \vec{v} = \left< x_{0},\ y_{0},\ z_{0} \right> + t\left< a,\ b,\ c, \right>
$$
$$
\vec{r_{0}}\ is\ a\ position\ vector
$$
$$
\vec{v}\ is\ a\ direction\ vector
$$
###### Parametric Equations
$$
x = x_0 + ta,\ y =y_0 + tb,\ z = z_0 + tc
$$
###### Symmetric Equations
$$
\frac{{x-x_{0}}}{a}=\frac{{y-y_{0}}}{b}=\frac{{z-z_{0}}}{c}
$$
###### Explanation
- [[Lines & Planes Visual]]

##### Plane Equation
$$
a(x-x_{0})+b(y-y_{0})+c(z-z_{0}) = 0
$$
Can be simplified to:
$$
ax+by+cz=d
$$
$$
where\ d=ax_{0}+by_{0}+cz_{0}
$$
###### Explanation
- Given a point $P(x_{0},\ y_{0},\ z_{0})$ and a normal vector $\vec{n} = \left< a,\ b,\ c \right>$, the scalar equation of the plane that passes through $P$ and is perpendicular to $\vec{n}$ is given by the formula above

##### Distance from a point to a plane
$$
D = \frac{{|ax_{1}+by_{1}+cz_{1}+d|}}{\sqrt{ a^2+b^2+c^2 }}
$$
$$
where\ a\ poi nt\ P\ (x_{1},\ y_{1},\ z_{1})\ a nd\ a\ plane\ in\ the\ fo r m\ ax+by+cz=d
$$
###### Explanation
- IDFK just memorize the formula

##### Next Formula

$$
16x^2+y^2+16z^2-8y-160z+400=0
$$
$$
16x^2+y^2+16z^2-8y-160z=-400
$$
$$
(4x)^2+y^2-8y+16z^2-160z=-400
$$
$$
(4x)^2+y^2-8y+16+16z^2-160z=-400+16
$$
$$
(4x)^2+(y-4)^2+16z^2-160z+400=-384+400
$$
$$
(4x)^2+(y-4)^2+(4z-20)^2=16
$$

$$
x^2+\frac{{(y-4)^2}}{4^2}+\frac{{(4z-20)^2}}{4^2}=1
$$

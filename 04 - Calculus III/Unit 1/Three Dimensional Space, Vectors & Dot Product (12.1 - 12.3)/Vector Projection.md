## Overview
### Definition and Use Case
#### Definition

>[!Literal Definition]
>- Often written as $proj_{b}a$ or $a_{||b}$
>- $proj_{\vec{b}}(\vec{a})$: Some [[Vectors|vector]]  in $\vec{b}$ where $\vec{a}-proj_{\vec{b}}(\vec{a})$ is **orthogonal** to $\vec{b}$

![[Vector Projection Visual]]
>[!Simpler Definition]
>- It's the **partial vector** of $\vec{a}$ that points in the **same direction** as $\vec{a}$
>- In the example above, it is in white
>- Imagine it as the **"shadow"** of $\vec{a}$ on $\vec{b}$ if a light were shining perpendicular to $\vec{b}$.

>[!Vector Rejection]
>- The remaining vector component of $\vec{a}$ which is **perpendicular** to $\vec{b}$
>- In the example above, it is in gray (denoted as $oproj_{b}a$)

#### Formula
##### Formula
$$
proj_{\vec{b}}(\vec{a}) = \left( \frac{{\vec{u} \cdot \vec{v}}}{||\vec{v}||^2} \right) \vec{v}
$$
##### Explanation

######  1. Projection is the scalar multiple of vector b
- The projection of $\vec{a}$ onto $\vec{b}$ likes along the direction of $\vec{b}$.
- So, it can be written as 
$$
proj_{\vec{b}}\vec{a} = k \vec{b}
$$
- Where $k$ is a **scalar** that determines the **length of the projection**
###### 2. Use the dot product to find k
- The **dot product formula**:
$$
\vec{a} \cdot \vec{b} = ||\vec{a}||\ ||\vec{b}||\cos \theta
$$
- $||\vec{a}||\cos \theta$ gives the **length of the projection** of $\vec{a}$ onto $\vec{b}$
	- This is because $\theta$ is the **angle between the vectors**
	- Since the $proj_{\vec{b}}\vec{a}$ is the **component** of $\vec{a}$ that is **parallel** with $\vec{b}$, the $\cos (\theta) \times ||\vec{a}||$ will yield the **magnitude** of the **projection**
		- This is due to $\vec{a}$ being the hypotenuse in a triangle whose one leg is parallel to $\vec{b}$ and other leg is perpendicular to $\vec{b}$ and intercepts the terminal point of $\vec{a}$
- Dividing by $||\vec{b}||$ gives the scalar $k$: 
$$
k = \frac{{\vec{a} \cdot \vec{b}}}{||\vec{b}||^2}
$$
###### Final formula
- Substitue $k$ back into the expression for the projection:
$$
proj_{\vec{b}}\vec{a} = \left( \frac{{\vec{a} \cdot \vec{b}}}{||\vec{b}||^2} \right)  \vec{b}
$$

### Examples
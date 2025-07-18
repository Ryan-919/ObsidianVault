## Overview

### Defintion and Use Case
>[!Use case]
>To calculate the **cell potential** under **nonstandard** conditions

#### Formula

##### Full Formula
$$
E_{cell} = E°_{cell} - \frac {RT} {nF}\ln Q
$$
>[!Explanation]
>$\color{Salmon} E_{cell}$ - Instantaneous cell potential
>$\color{Salmon} E°_{cell}$ - Standard cell potential
>$\color{Salmon} R$ - Ideal gas constant ($8.314\ \frac {J} {mol \times K}$)
>$\color{Salmon} T$ - Temperature
>$\color{Salmon} n$ - Number of electrons transferred
>$\color{Salmon} F$ - Faraday's constant ($96485\ \frac {C} {mol}$)
>$\color{Salmon} Q$ - Reaction quotient

##### Simplified at 25° C (298 K)

$$
E_{cell} = E°_{cell} - \frac {0.0592\ V} {n}\log Q
$$
>[!Explanation]
>Multiply temperature in Kelvin by the ideal gas constant and divide by Farady's constant

### Examples

#### Zinc and Copper
##### Problem at Standard States
###### Problem
$$
\ce{ Zn(s) + Cu^2+(aq) -> Zn^2+(aq) + Cu(s) }
$$
$$
E°_{cell} = 1.10\ V,\ \ \ [Cu^{2+}] = [Zn^{2+}] = 1.0\ M
$$
$$
\color{Salmon} Find\ E_{cell}
$$
###### Calculation

$$
E_{cell} = E°_{cell} - \frac {0.0592\ V} {n}\log Q
$$
>[!Values]
>$\color{Salmon} n$ $= 2\ e^-$ transferred
>$\color{Salmon} Q$ $= \frac {[Zn^{2+}]} {[Cu^{2+}]} = 1$
>$\color{Salmon} log(Q)$ $= 0$

$$
E_{cell} = E°_{cell} = 1.10\ V
$$
This makes sense because the reaction is in its standard states

##### Problem at Nonstandard States

###### Problem
$$
\ce{ Zn(s) + Cu^2+(aq) -> Zn^2+(aq) + Cu(s) }
$$
$$
E°_{cell} = 1.10\ V,\ \ \ [Cu^{2+}] = 10.0\ M,\ \ \ [Zn^{2+}] = 1.0\ M
$$
$$
\color{Salmon} Find\ E_{cell}
$$

###### Calculation

$$
E_{cell} = E°_{cell} - \frac {0.0592\ V} {n}\log Q
$$
>[!Values]
>$\color{Salmon} n$ $= 2\ e^-$ transferred
>$\color{Salmon} Q$ $= \frac {[Zn^{2+}]} {[Cu^{2+}]} = 0.1$
>$\color{Salmon} log(Q)$ $= -1$

$$
E_{cell} = E°_{cell} = 1.10\ V
$$
This makes sense because the reaction is in its standard states
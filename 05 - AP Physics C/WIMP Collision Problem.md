>[!Problem]
>Suppose a WIMP has a mass of $1.07 \times 10^{-25}\,kg$ and an initial speed of $230\, \frac{km}{s}$.
>It collides with the nucleus of a stationary germanium atom with a mass of $1.19 \times 10^{-25}\, kg$.
>The germanium atom is deflected with an energy of $10\,keV$ ($1\,ev = 1.6 \times 10^{19}\,J$).
>**Which direction does the germanium atom travel after the collision?**

##### Knowns
Let WIMP be $m_{1}$ and germanium atom be $m_{2}$
- $m_{1}$
- $m_{2}$
- $v_{1i}$
- $v_{2i}$
- $KE_{2f}$

##### Conservation of Kinetic Energy
$$
KE_{1i}+KE_{2i}=KE_{1f}+KE_{2f}
$$
###### Solve for $v_{2f}$
$$
\frac{1}{2}m_{2}v_{2f}^2 = KE_{2f}
$$
$$
v_{2f} = \sqrt{ \frac{2KE_{2f}}{m_{2}} }
$$
###### Solve for $v_{1f}$
$$
\frac{1}{2}m_{1}v_{1f}^2 = \frac{1}{2}m_{1}v_{1i}^2-KE_{2f}
$$
$$
v_{1f} = \sqrt{ \frac{m_{1}v_{1i}^2-2KE_{2f}}{m_{1}} }
$$
##### Conservation of Momentum
$$
m_{1}v_{1i} = m_{1}v_{1f}\cos \theta_{1} + m_{2}v_{2f}\cos \theta_{2}
$$
$$
0 = m_{1}v_{1f}\sin \theta_{1} + m_{2}v_{2f}\sin \theta_{2}
$$
###### Solve for $\cos^2 \theta_{1}$
$$
\cos \theta_{1} = \frac{m_{1}v_{1i}-m_{2}v_{2f}\cos \theta_{2}}{m_{1}v_{1f}}
$$
$$
\cos^2 \theta_{1} = \left( \frac{m_{1}v_{1i}-m_{2}v_{2f}\cos \theta_{2}}{m_{1}v_{1f}} \right)^2
$$
###### Solve for $\sin^2 \theta_{1}$
$$
\sin \theta_{1} = -\frac{m_{2}v_{2f}\sin \theta_{2}}{m_{1}v_{1f}}
$$
$$
\sin^2 \theta_{1} = \left( \frac{m_{2}v_{2f}\sin \theta_{2}}{m_{1}v_{1f}} \right)^2
$$
##### Trig identity
$$
\sin^2\theta+\cos^2\theta=1
$$
$$
1 = \left( \frac{m_{2}v_{2f}\sin \theta_{2}}{m_{1}v_{1f}} \right)^2 + 
\left( \frac{m_{1}v_{1i}-m_{2}v_{2f}\cos \theta_{2}}{m_{1}v_{1f}} \right)^2
$$
$$
(m_{1}v_{1f})^2 = m_{2}^2v_{2f}^2 \sin^2\theta_{2}^2 +
m_{1}^2v_{1i}^2 - 2m_{1}m_{2}v_{1i}v_{2f}\cos \theta_{2} + m_{2}^2v_{2f}^2 \cos^2\theta_{2}^2
$$
$$
(m_{1}v_{1f})^2 = (m_{2}v_{2f})^2 + (m_{1}v_{1i})^2 - 2m_{1}m_{2}v_{1i}v_{2f}\cos \theta_{2}
$$
$$
\cos \theta_{2} = \frac{(m_{2}v_{2f})^2 + (m_{1}v_{1i})^2 - (m_{1}v_{1f})^2}{2m_{1}m_{2}v_{1i}v_{2f}}
$$
$$
\theta_{2} = \cos^{-1} \left( \frac{(m_{2}v_{2f})^2 + (m_{1}v_{1i})^2 - (m_{1}v_{1f})^2}{2m_{1}m_{2}v_{1i}v_{2f}} \right)
$$
###### Plug in $v_{1f}$ and $v_{2f}$
$$
v_{1f} = \sqrt{ \frac{m_{1}v_{1i}^2-2KE_{2f}}{m_{1}} }
$$
$$
v_{2f} = \sqrt{ \frac{2KE_{2f}}{m_{2}} }
$$
$$
\theta_{2} = \cos^{-1} \left( \frac{(2m_{2}KE_{2f})+(m_{1}v_{1i})^2-m_{1}(m_{1}v_{1i}^2-2KE_{2f})}{2m_{1}m_{2}v_{1i}\sqrt{ \frac{2KE_{2f}}{m_{2}} }} \right)
$$

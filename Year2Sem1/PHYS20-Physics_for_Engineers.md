# Table of contents
1. [[#Vectors|Vectors]]
	1. [[#Vectors#Kinematics Equations|Kinematics Equations]]
					1. [[#Remember:|Remember:]]
	2. [[#Vectors#Free fall & vertical acceleration|Free fall & vertical acceleration]]
	3. [[#Vectors#Tip|Tip]]
		1. [[#Tip#Square Roots|Square Roots]]
		2. [[#Tip#Bhāskara I's Sine Approximation Formula|Bhāskara I's Sine Approximation Formula]]
		3. [[#Tip#$cos(\theta)$|$cos(\theta)$]]
		4. [[#Tip#$\tan(\theta)$|$\tan(\theta)$]]
	4. [[#Vectors#Gravity vs Gravitational Force|Gravity vs Gravitational Force]]
2. [[#Work and Kinetic Energy|Work and Kinetic Energy]]
	1. [[#Work and Kinetic Energy#Work|Work]]
	2. [[#Work and Kinetic Energy#Kinetic Energy|Kinetic Energy]]
		1. [[#Kinetic Energy#Work energy theorem for Kinetic Energy|Work energy theorem for Kinetic Energy]]
	3. [[#Work and Kinetic Energy#Power|Power]]
3. [[#Potential Energy & energy conservation|Potential Energy & energy conservation]]
	1. [[#Potential Energy & energy conservation#Gravitational Potential Energy|Gravitational Potential Energy]]
		1. [[#Gravitational Potential Energy#Work theorem|Work theorem]]
	2. [[#Potential Energy & energy conservation#Elastic|Elastic]]
		1. [[#Elastic#Work-energy theorem|Work-energy theorem]]
	3. [[#Potential Energy & energy conservation#Energy Conservation|Energy Conservation]]
		1. [[#Energy Conservation#Mechanical Energy|Mechanical Energy]]
			1. [[#Mechanical Energy#Mechanical Energy Conservation Principle|Mechanical Energy Conservation Principle]]
		2. [[#Energy Conservation#Conservative forces|Conservative forces]]
			1. [[#Conservative forces#Non Conservative|Non Conservative]]
	4. [[#Potential Energy & energy conservation#E.g.,|E.g.,]]
4. [[#Momentum|Momentum]]
	1. [[#Momentum#Collisions|Collisions]]
5. [[#Current|Current]]
	1. [[#Current#Resistivity|Resistivity]]

# Vectors
$\hat{I}$

## Kinematics Equations
###### Remember:
$v$ = velocity
$X$ = Position 
$a$ = acceleration
$_{I}$ = initial 
$_f$ = final
$t$ = time
1.  Velocity to final position($v_{fx}$)
$$v_{fx}=v_{ix}+a_{x}t$$

2. Displacement ($X_f-X_i$)
$$X_f-X_i=(\frac{v_{fx}+v_{ix}}{2})t$$
3. Final Velocity(?) ($v_{fx}$$^2$)
$$v_{fx}^2=v_{ix}^2+2a_x(x_f-x_i)$$
4. Final position ($X_f$)
$$X_i+v_{ix}+\frac{1}{2}a_xt^2$$

## Free fall & vertical acceleration
Remember:
$g$ = (Earth's) gravity, $9.8m/s^2$
$y$ = position, but vertical

It's pretty much identical as the equations above but vertical
1.  Velocity to final position($v_{fx}$)
$$v_{fx}=v_{ix}+gt$$

2. Displacement ($y_f-y_i$)
$$y_f-y_i=(\frac{v_{fy}+v_{iy}}{2})t$$
3. Final Velocity(?) ($v_{fy}$$^2$)
$$v_{fy}^2=v_{iy}^2+2g(y_f-x_y)$$
4. Final position ($X_f$)
$$X_i+v_{ix}+\frac{1}{2}gt^2$$
- - -
## Tip
### Square Roots
$$\sqrt{x} \approx \frac{x+y}{2\sqrt{y}}$$
$$\text{Where $y$ is a perfect square close to $x$}$$

~~prerequisites: meth~~
### Bhāskara I's Sine Approximation Formula 
$$\sin(x) = \frac{4(x)(180-x)}{40500-x(180-x)}$$
$$\text{Where $x$ is a given angle}$$
Accurate enough if you only need precision by $0.00$


### $cos(\theta)$
$$\sqrt{1-\sin^2(\theta)}$$
### $\tan(\theta)$
$$\frac{\sin(\theta)}{\cos(\theta)}$$

## Gravity vs Gravitational Force
Gravity is the force, Gravitational Force is the weight ()
- - -

# Work and Kinetic Energy
## Work
- activities requiring muscular or mental effort
- done by exerting force on object $w/c$ then undergoes displacement 
- requires energy
$$W = \vec{F} \cdot \vec{d}$$
$$\text{(Joule) }1j = 1N \cdot m$$
## Kinetic Energy
- energy due to motion

$$K = \frac{1}{2}mv^{2}$$
$K$ = Kinetic Energy 
$m$ = mass
$v$ = velocity
### Work energy theorem for Kinetic Energy 
$$W_{tot} = \Delta K = K_f - K_i $$
E.g.,
A 14000N sled has a $v_i$ of 2m/s. What's its speed after it moved 20m? $W_{tot}$ = 10kj
$d$ = $20m$
$v_i$ = $2m/s$
$m\text{ or } w$ = $14000N$
$W_{tot}$ = 10kj

## Power
- time rate of doing work
- time rate of expanding e
$$P = \frac{W}{t}$$
$$\text{or}$$
$$P = \vec{F} \cdot \vec{v}$$
- Unit: Watts (W)
- 1W = $1\frac{J}{s}$ where J is Joules and s is seconds
- 1hp = 746 W
# Potential Energy & energy conservation
- energy associated with position 
- potential/possibility of work to be done
##  Gravitational Potential Energy
$$U_g = mgy$$
$m$ = mass
$g$ = gravity
$y$ = height
### Work theorem
$$W_g =-\Delta U_g$$
$$= U_{gi} - U_{gf}$$
## Elastic
For an elastic object like spring or rubber band
$$\vec{F} = k\vec{x}$$
Force required to stretch or compress a spring at distance $x$
$$U_e = \frac{1}{2}kx^2$$
$k$ = spring const
### Work-energy theorem
$$W_e = -\Delta U_e$$
$$= U_{ei} - U_{ef}$$
## Energy Conservation 
Remember: energy can't be created nor destroyed, only transformed ~~(to useless shit)~~
### Mechanical Energy
Total energy in sys
$$E = K + U$$
#### Mechanical Energy Conservation Principle
Mechanical Energy of the system doesn't change.
$$E_i = E_f$$
$$K_i+U_{gi}+U_{ei}=K_f+U_{gf}+U_{ef}$$
If there are other forces (aside from g and e) present, Mechanical energy isn't conserved
$$E_f = E_i +W_{other}$$
$$
\begin{flalign*}
K_i+U_{gi}+U_{ei}+W_{other}= \\
K_f+U_{gf}+U{ef}
\end{flalign*}
$$

### Conservative forces
- a force that offers a 2-way conversion between kinetic and potential energy
- g-force, e-force
- doesn't depend on the path, only in I and F position
#### Non Conservative 
- dissipative
- friction
- force you've done

## E.g.,
1. U throw a .145kg baseball straight up in the air, giving it an upward velocity of 20m/s. Find how high it goes, ignoring air resistance
Given: m =.145kg; $v_i$ = 20m/s; $y_i$ = 0;
# Momentum
Quantity of motion an object has.
$$
\vec{p} = m\vec{v}
$$
$m = \text{mass}$
$\vec{v} = \text{velocity}$
Remember thr Newton's 2nd law in momentum
$$\begin{align}
\vec{F}_{net}=m\vec{a} = m\frac{\Delta\vec{v}}{\Delta t} = \frac{\Delta m \vec{v}}{\Delta{t}} \\

\vec{F}_{net} = \frac{\Delta \vec{p}}{\Delta t} \\
\text{ Impulse: }\vec{j} = \vec{p}_f - \vec{p}_i = \vec{F}_{net} \Delta t
\end{align}$$
## Collisions
$$P_{initial} = P_{final}$$
$$P_{ia} + P_{ib} = P_{fa}+
P_{fb}$$
$m_A v_{ia} + m_b v_{ib} = m_A v_{fa} + m_b v_{fb}$
$= v_{fa} = v_{fb} = v{f}$ 
$$\frac{m_A v_{iA} + m_B v_{iB}}{m_A +m_B} = \frac{(m_A+m_B)v_f}{m_A+m_B} $$

# Current
**Definition:** a If the moving charges are negative rather than positive, the drift velocity is opposite to the electric field. But the current is still in the same direction as at each point in the conductor.
$$I = \frac{dQ}{dT}= n|q|v_dA$$
Where:
$n$ = concentration of particles
$q$ = charges
$v_d$ = drift velocity
$A$ = cross sectional area
The current and current density don’t depend on the sign of the charge, and so in the above expressions for and we replace the charge:
$$\vec{J} = nq\vec{v_d}$$
## Resistivity
Resistivity is a fundamental property of a material that quantifies how strongly it resists or conducts electric current. A low resistivity indicates a material that readily allows electric current.
$$ \rho=\frac{E}{J}$$
Where:
E = electric field
J = current density

- - -

---
title: Physics
date: 2022-5-24
categories: Basic Knowladge
mathjax: true
---
## Guide

[Download](https://kjle.github.io/files/BasicKnowledge/Physics_Guide.pdf) PDF version of **Physics Guid**.

### Area 1: mechanics (Newtonian) and materials
- Kinematics: position, trajectories, velocity, acceleration
- Newtonian dynamics: Newton’s laws, inertial and non-inertial reference frames, forces and potentials, gravitational field, central forces, small oscillations, translation and rotation, composition of movements, acceleration, angular momentum, kinetic energy, potential energy, mechanical energy, work, power, conservative forces, conservation laws, energy conservation theorems
- Harmonic oscillators
- Rigid bodies statics and dynamics: centre of mass, definition and calculation of moments of inertia around an axis, definition and calculation of inertia matrix, Huygens’ theorem, forces, torques, distributed forces, friction, Coulomb’s laws, equilibrium, acceleration, momentum, angular momentum, kinetic energy, conservation laws (momentum, angular momentum, energy), Koenig’s theorem
- Kepler’s laws
- Fluids: continuum mechanics, pressure, density, hydrostatics, Archimede’s principle, Euler and Lagrange variables, continuity equation, Euler equation of motion (ideal fluid), mass and volume flow rate, conservation laws, pipe flows (ideal and viscous fluids), regular and singular pressure drop, head loss, Bernoulli equations (incompressible and homogeneous flows of ideal or viscous fluids)
- General classification and mechanical properties of materials
- Mechanical behaviour of materials: normal and shear stress, normal and shear strain, strain-stress curve
- Hooke’s law, Young’s modulus, Poisson’s ratio, shear modulus, bulk modulus, Lamé constants, elastic strain energy
- Principle strains and directions (calculation), Mohr’s circle for plane stress
- Beam deflection and bending

### Area 2: thermodynamics
- Work, heat, internal energy, enthalpy, entropy, free energy, free enthalpy, relevant differentials, thermodynamic equilibrium
- Ideal gas: concept, model, limits of the model
- Real gas: Van der Waals’ model
- Reversible and irreversible processes, first and second laws of thermodynamics (closed systems)
- Heat machines, Carnot cycle

### Area 3: chemistry, chemical/process engineering
- Organic chemistry: structure and bonding in organic chemistry
- Reactions of alkanes, cyclic alkanes, stereoisomerism
- Formation of the hydroxyl functional group
- Reactions of alcohols and the chemistry of ethers
- Reactors of alkens, aldehydes and ketones
- Functional groups containing nitrogen
- Chemical equilibrium, chemical kinetics
- Change of phase, triple and critical points, Clapeyron’s formula, chemical reactions, Gibbs’ phase rules, phase equilibrium
- Chemical potentials, affinity
- Basic thermochemistry: enthalpy of reaction, endothermic and exothermic reactions
- Electrochemistry, electrochemical batteries, Nernst’s law
- Heat and mass transfer, diffusion, flux, Fick's law, conduction, convection, Fourier's law, integral and local balance equations (mass, species, energy, momentum), field operators (grad, div, curl)
- Unitary operations

### Area 4: computer science and automatics
- Algorithmics: tests, loops, conditional choices
- Algorithms: structure, sorting techniques, graphs
- Programming, functions, recursion, C language, Unix
- Object-oriented programming
- Computer architecture, computer operation
- Database Management Systems
- Basics of networks
- Automata theory, graphcet
- Automated reasoning

### Area 5: electrical circuits and information sciences
- Electric currents: voltage, current, AC/DC
- Thevenin’s and Norton’s theorems, Kirchoff’s junction and loop laws, Ohm’s law, superposition theorem
- Physical basis of operation of resistors, capacitors (condensers), induction coils (inductance)
- Impedances in series or in parallel, impedance in variable (sinusoidal) regime, complex impedance
- Free and forced oscillations, resonant circuits (analogy with mechanical resonance)
- Transient regimes in circuits with resistors, capacitors and coils
- Bipolar transistor, MOS transistors
- Operational amplifiers
- Transfer functions of elementary circuits
- Analog filters and amplifiers
- Digital to analog conversion, analog to digital conversion Nature of signals
- Sampling (Shannon’s theorem)
- Fourier, Laplace and Z transforms
- Nyquist’s and Bode’s diagrams
- Boolean algebra
- Binary coding, two’s complement method
- Data structure
- Digital gates, combinatorial logic, sequential logic
- Counters, memories, registers
- Concept of performance of digital circuits

### Area 6: atomic & molecular physics
- Quantum mechanics: Planck's law, Bohr's atom, de Broglie's relation, uncertainty principle, wave function, Schrödinger's equation, stationary states, quantization of energy
- Structure of matter, hydrogen atom, periodic table of the elements, properties of atoms in periodic table, valence bond theory, molecular orbitals, molecules, solid state, crystallography, chemical bonds (covalent, ionic, hydrogen, etc.), interaction of elements/particles/radiation with matter (excitation, fluorescence, photoelectric, ompton, etc.)
- Elementary statistical physics, radioactivity
- Differences between insulators, semiconductors and conductors

### Area 7: electricity & magnetism
- Electrostatics: electric charge, Coulomb's law, electric field, potential, Gauss' law, symmetry of the electrostatic field E, calculation of E for simple charge distributions
- Electric dipole, electrostatic field induced by a capacitor
- Poisson’s law
- Conductors in electrical equilibrium
- Coulomb’s law between 2 charges in a homogeneous linear and isotropic dielectric medium
- Magnetostatics: magnetic field B, symmetries of B, Ampère's laws, Maxwell’s laws, Potential vector
- Magnetic field created by an infinite wire or a circular loop, along the axis of a coil, Biot and Savart’s law
- Magnetic dipole and moment
- Faraday's law of induction, induction, Lenz’s rule
- Electromagnetism: Maxwell’s equations in vacuum, progressive harmonic plane waves an solutions of the relevant equations of propagations, wavelength, wave vector, phase velocity, polarization, Poynting vector
- Lorentz force, plane electromagnetic waves
- Magnetic waves: radiation, spectrum, light waves, reflexion, refraction, Huygens principle, diffraction, interference phenomena, laser

### Area 8: optics
- Geometrical optics: light rays, reflection, refraction, diffraction, Snell-Descartes’ laws, limit angle, total reflection, mirrors, lenses and their association, focal length
- Wave optics: optical path, coherent light/waves, interference, thin slabs, diffraction, Young’s slits experiments, Michelson’s interferometer, Pérot-Fabry’s cavity
- Basics of lasers
- Light propagation in optical fibers

## Test and Exam for Physics

This part will incloude some of the questions in the *Exercises* in which the correct solution will be given in $\color{red}{red}$, and in the *Exam* which have not given the correct answers yet.

### Mechanics

The inertia matrix about $O,I(O,\vec{x},\vec{y},\vec{z})$ , of a cylinder of height $H$, radius $R$ and mass $M$ is:

<center>![](Mechanics1.png)</center>

- $$\frac{M}{2} \begin{pmatrix} R^2/2+H^2/6 & 0 &0\\ 0& R^2 & 0 \\ 0 & 0 & R^2/2+H^2/6 \\\end{pmatrix} $$
- $$\frac{M}{2} \begin{pmatrix} R^2/2+2H^2/3 & 0& 0\\ 0& R^2+2H^2/3 & 0 \\ 0 & 0 & R^2\\ \end{pmatrix} $$
- $$\color{red}{\frac{M}{2} \begin{pmatrix} R^2/2+2H^2/3 & 0 &0\\ 0& R^2 & 0 \\ 0 & 0 & R^2/2+2H^2/3\\ \end{pmatrix} }$$
- $$\frac{M}{2} \begin{pmatrix} R^2 & 0 &0\\ 0& R^2/2+H^2/6 & 0 \\ 0 & 0 & R^2\\ \end{pmatrix} $$
- $$\frac{M}{2} \begin{pmatrix} R^2/2+H^2/6 & 0& 0\\ 0& R^2/2+H^2/6 & 0 \\ 0 & 0 & R^2\\ \end{pmatrix} $$

---

A hoop with mass $M$ and radius $R$ rolls on a horizontal floor at constant angular velocity $(\omega=d\theta /dt)$ around its own axis. To which relationship leads the no-slip condition at the contact point $I$ ?

<center>![](Mechanics2.png)</center>

- $\color{red}{\frac{d\lambda}{dt}+R\frac{d\theta}{dt}=0}$
- $\frac{d\lambda}{dt}-R\frac{d\theta}{dt}=0$
- $\frac{d\lambda}{dt}+MR\frac{d\theta}{dt}=0$
- $M\frac{d\lambda}{dt}-R\frac{d\theta}{dt}=0$
- $R\frac{d\theta}{dt}=cste$

---

A material point with mass $M$ slips frictionless over the surface of a fixed half-cylinder with radius $R$. We denote by $g$ the acceleration of gravity. The material point $M$ is initially at point $A$ (cylinder top). It is launched gently with an initial horizontal velocity $V_0$. We suppose that the material point keeps contact with the surface of the cylinder. The relationship between the velocity $V$ of the mass $M$ and the angle $\theta$ that defines its position is:

<center>![](Mechanics3.png)</center>

- $V^2 = V_{0}^2+2gR(1+\cos \theta)$
- $\color{red}{V^2 = V_{0}^2+2gR(1-\cos \theta)}$
- $V^2 = V_{0}^2-2gR(1+\cos \theta)$
- $V^2 = V_{0}^2-2gR(1-\cos \theta)$
- None of the above answers

---

A viscous fluid flows between two parallel and infinitely large plates kept at a distance $2h$ from each other. The upper plate is at $y = h$ and the lower plate is at $y = - h$. The considered fluid flows mono directionally along the x-direction under a constant pressure gradient $K=−dP/dx$. The transverse profile of velocity is given by :

<center>![](Mechanics4.png)</center>

- $U(y) = \frac{K}{2}(h-y)$
- $U(y) = \frac{K}{2}(h^2-y^2)$
- $U(y) = \frac{K}{2\mu}(y^2)$
- $U(y) = \frac{K}{2\mu}(h-y)$
- $\color{red}{U(y) = \frac{K}{2\mu}(h^2-y^2)}$

---

Gasoline (incompressible fluid, density $\rho = 800 kg\cdot m^{−3}$) flows steadily from a $0.30 m$ diameter pipe in which the pressure is $300 kPa$ into a $0.15 m$ diameter pipe in which the pressure is $120 kPa$ . If the pipes are horizontal and viscous effects negligible, the flow rate is :

<center>![](Mechanics5.png)</center>

- $1.92 m^3\cdot s^{−1}$
- $0.42 m^3\cdot s^{−1}$
- $\color{red}{0.37 m^3\cdot s^{−1}}$
- $0.21 m^3\cdot s^{−1}$
- $0.96 m^3\cdot s^{−1}$

---

Bernoulli's formula $P_1+\frac{1}{2}pV_2^1+pgz_1 = P_2 + \frac{1}{2}pV_2^2 + pgz_2$ is applicable to:

- Steady, laminar, incompressible flows of viscous fluids
- <span style="color:red;">Steady, incompressible, laminar flows of ideal fluids</span>
- Only flows in pipes
- Any kind of flow
- None of the above answers

---

Grass is growing on a disk spinning at constant rate . What is the orientation of the stems ?

- Inclined towards the periphery with a constant angle
- Inclined towards the periphery with a variable angle
- <span style="color:red;">Inclined towards the centre with a variable angle</span>
- Inclined towards the centre with a constant angle
- Vertical

--- 

Water flows in a pipe of constant cross area $5 cm^2$ . The pipe is bent at $90°$ as shown in the figure below. The flow rate is steady and equal to $0.1 l/s$ . Pressure is supposed uniform within the bent. It is equal to $2$ bars.

<center>![](Mechanics6.png)</center>

The resulting force imposed by the fluid on the pipe bent is most nearly equal to:

- 2N
- 0N
- 3N
- 1N
- <span style="color:red;">4N</span>

---

In fluid mechanics, the divergence of velocity expresses

- An elongational rate in the direction of motion
- A particular eigen value of the Navier-Stokes equation.
- <span style="color:red;">A volume dilatation rate</span>
- None of the above answers
- Viscous effects

---

A spherical porcelain ball, with radius $r$, is dropped without initial velocity in a test tube containing glycerin. During fall, the ball is subject to the following forces:

$\mathbf{P}$ its weight; $A$ the thrust of Archimedes; fluid friction force $\mathbf{f} = k \mathbf{v}$ with $k = 6 \pi r \eta$ ; $\eta$ : viscosity (Pa s) of Glycerin, $V$, velocity

Density of Glycerin $\rho G= 1.3 g/mL$ ; density of porcelain $\rho P = 2.3 g/mL$ ;  $r$ ball radius $= 1.0 cm$ ;

$\eta = 1.0 s\cdot Pa$ ; $g = 10 N/kg$ ; volume of a sphere $V = 4/3 \pi r^3$ .

The speed limit (in m/s) is:

- 0.44
- <span style="color:red;">0.22</span>
- 0.11
- 0.33
- 0.55

---

A sphere of weight $100N$ is supported by two inclined plane walls as shown below. The force acting against the wall at point $P$ is:

<center>![](Mechanics7.png)</center>

- <span style="color:red;">70.7N</span>
- 35.5N
- 50.0N
- 100N
- 45.0N

### Electronincs

In a NPN transistor, the collector current is saturated when:

<center>![](Electronics1.png)</center>

- $0<V_{BE}<V_d$
- $V_{BE}>0$
- $V_{BE} < 0$
- $\color{red}{V_{BE}>V_d}$
- None of the above conditions

---

Calculate the mutual inductance $M12$ between the infinite line and the square loop shown in the figure :

<center>![](Electronics2.png)</center>

- $M12 = 0$
- $M12 = \mu_0 I_1/2\pi h$
- $\color{red}{M12 = \frac{\mu_0 h}{2\pi}\ln \frac{d+w}{d}}$
- $M12 = \frac{\mu_0 h}{2\pi}\ln \frac{d}{d+w}$
- $M12 = \frac{\varepsilon_0 h}{2\pi}\ln \frac{d+w}{d}$

---

Consider the following RLC circuit consisting of two resistors (R and R'), an inductor (L) and a capacitor (C) connected in series and in parallel. At time t = 0, a constant voltage E is applied. For t > 0, the current i(t) in the circuit is described by the following second-order differential equation:

<center>![](Electronics3.png)</center>

- $(RC+\frac{L}{R'})\frac{d^2 i}{dt^2}+LC\frac{di}{dt}+(1+\frac{R}{R'})i = \frac{E}{R'}$
- $(RC+\frac{L}{R'})\frac{d^2 i}{dt^2}+LC\frac{di}{dt}+(1+\frac{R+R'}{2})i = \frac{E}{R'}$
- $\frac{LC}{R+R'} \frac{d^2 i}{dt^2}+(RC+\frac{L}{R'})\frac{di}{dt}+(R+R')i = \frac{E}{R'}$
- $\color{red}{LC \frac{d^2 i}{dt^2}+(RC+\frac{L}{R'})\frac{di}{dt}+(1+\frac{R}{R'})i = \frac{E}{R'}}$
- None of above answers

---

Consider a real sinusoidal signal with frequency 418 Hz sampled every 20 ms.

- <span style="color:red;">The Nyquist-Shannon sampling theorem is not fulfilled and an aliased frequency component appears in the discrete-time Fourier transform of this signal at 18 Hz</span>
- The Nyquist-Shannon sampling theorem is not fulfilled and an aliased frequency component appears in the discrete-time Fourier transform of this signal at 20 Hz
- The Nyquist-Shannon sampling theorem is fulfilled
- The discrete-time Fourier transform of this signal is not mathematically defined because the Nyquist-Shannon sampling theorem is not fulfilled

---

An optical time-domain reflectometer (OTDR) is an instrument that measures:

- Optical fiber bandwidth
- Photodiode frequency response
- <span style="color:red;">Optical fiber attenuation</span>
- Laser spectrum
- none of the above

---

In a digital transmission system, a high signal-to-noise ratio is essential for:

- None of the above
- Reducing the link cost
- Increasing the system bandwidth
- <span style="color:red;">Reducing the bit error rate</span>
- Optimizing the circuit size

---

Let $x(t)$ be a deterministic continuous time signal with finite energy. Let $X(ƒ)$ be the Fourier transform of $x(t)$ and let $\Gamma_x(ƒ)$ be its energy spectral density. Then

- None of the above proposition is right
- $\Gamma_x(f)$ is maximum at the origin (that is : $\forall f,∣\Gamma_x(f)∣ \leq \Gamma_x(0)$)
- We have $\int_{-\infty}^{+\infty}∣x(t)∣dt=\int_{-\infty}^{+\infty} \Gamma_x(f)df$
- $\color{red}{We \  have\  \Gamma_x(f)=∣X(f)∣^2}$
- We have $\Gamma_x(f)=∣X(f)∣$

---

Suppose that the transfer function $G(s)$ for the system shown below is equal to $1/(s+1)$ and that the initial conditions for the system are zero.

<center>![](Electronics4.png)</center>

If $c(t) = 1$ for $t \geq 0^{+}$, which of the following $r(t)$ for $t \geq 0$+ does the system generate?

- $\color{red}{r(t) = 1-e^{-t}}$
- $r(t) = 1/(1+t)$
- $r(t) = (1/t)e^{-t}$
- $r(t) = 1$
- $r(t) = t - e^{-t}$

---

Calculate the electrostatic field E generated by the non concentric and uniformly charged spheres (see figure). The inner sphere has radius a and charge +Q, and the outer sphere has radius b and charge –Q. Assume that the dielectric between the sphere is homogeneous with permittivity of $\varepsilon$.

<center>![](Electronics5.png)</center>

- $\color{red}{a<r<b,E = Q/4\pi \varepsilon r^2 \  and \ 0 \ otherwise}$
- $a<r<b,E =0 \ and \ Q/4\pi \varepsilon r^3 \ otherwise$
- $a<r<b,E = 0 \ and \ Q/4\pi \varepsilon r^2 \ otherwise$
- $a<r<b,E = 0 \ and \ 0 \ otherwise$
- $a<r<b,E = Q/4\pi \varepsilon r^3 \ and \ 0 \ otherwise$

---

The following figure shows the Bode diagram of an unknown function.

<center>![](Electronics6.png)</center>

It shows :

- <span style="color:red;">The magnitude plot of a second order system</span>

- The phase plot of a first order system
- None of the above propositions
- The phase plot of a second order system
- The magnitude plot of a first order system

---

The step response (to a unit step function) of a given system is shown below.

<center>![](Electronics7.png)</center>

The system is :

- Proportional
- Second order
- None of the above answers
- Integrator
- <span style="color:red;">First order</span>

---

The current circulating in a coil exhibiting an inductance of $0.2 H$ is increased from $0$ to $10 A$ in $0.1$ second. What is the magnitude of the electromotive force (emf) induced?

- emf=100V
- emf=2V
- emf=-20V
- emf=10V
- emf=20V

### Algorithmic / Computer Science

For an array of $N$ integer values, the bubble-sort  algorithm in the best case has the following complexity (time to compare two integers is constant):

- O(log N)
- O(N^2)
- O(1)
- O(N log N)
- <span style="color:red;">O(N)</span>

---

In the following program:

```C++
class Sort{
    public static void find_forward(int[] tab,int i) {
        if(i < tab.length-1)
            if (tab[i] > tab[i + 1]) push(tab,i);
        else <...>
    }
    public static void find_back(int[] tab, inti) {
        if(i > 0)
            if (tab[i] < tab[i-1]) pull(tab,i);
        else <...>
    }
    public static void pull(int[] tab, inti) {
        if(i > 1) {
            if (tab[i] > tab[i-1]) {
                int c    = tab[i-1];
                tab[i-1] = tab[i];
                tab[i]   = c;
                pull (tab,i-1);
            }
            else push(tab,i-1)
        }
        else find_forward(tab,0);
    }
    public static void push(int[] tab, inti) {
        if (i < tab.length - 1) {
            if (tab[i] > tab[i + l]) {
                int c    = tab[i+l];
                tab[i+1] = tab[i]
                tab[i]   = c;
                push(tab,i+1);
            }
            else pull(tab,i+1);
        }
        else find_back(tab,tab.length-1);
    }
    public static void sort(int[] tab) {
        find_forward(tab,O); 
    }
}

```

The function $\mathtt{sort}$ is supposed to sort a table of distinct integers. By what the dots (<...>) should be respectively replaced?

 ```C++ 
    find_forward(tab,i+1) ; find_back(tab,i-1)
  ```

 ```C++ 
    pull(tab,i) ; push(tab,i)
  ```

 ```C++ 
    find_forward(tab,i) ; find_back(tab,i)
  ```

 ```C++ 
    find_forward(tab,i) ; push(tab,i)
  ```

 ```C++ 
    push(tab, i-1) ; pull(tab, i+1)
  ```

---

When a class A inherits of a class B:

- All instances of B are instances of A
- None of these answers are true
- B can inherit of A
- B is a specialization of A
- <span style="color:red;">The constructors of B are inherited by A</span>

---

The table PRODUCT has the following structure : ID_FIRM CHAR(2), ID_PROD CHAR(4), NAME VARCHAR(30), PRICE INTEGER, VOLUME INTEGER. The primary key is on the columns ID_FIRM and ID_PROD. Which column can contain the value NULL?

- only PRICE
- none
- maybe ID_FIRM, ID_PROD, NAME, VOLUME
- all
- <span style="color:red;">maybe NAME, PRICE, VOLUME</span>

---

Which of these two algorithms is the most efficient? (b and c are defined elsewhere)

```C
For j Varying From 1 To 4000 Do
    a[j] ← 0 
    For i Varying From 1 To 4000 Do
        a[j] ← a[j]+b*c[i,j]
    End For
End For
```

```C
For j Varying From 1 To 4000 Do
    a[j] ← 0 
    For i Varying From 1 To 4000 Do
        a[j] ← a[j]+c[i,j]
    End For
    a[j] ← a[j]*b
End For
```

- Algorithms 1 and 2 do not lead to the same result
- There is no difference
- <span style="color:red;">Algorithm 2</span>
- Algorithm 1

---

What is the benefit of a 64 bits processor over a 32 bits processor?

- <span style="color:red;">Can use more than 4 Gb memory</span>
- Compute numbers with higher accuracy
- None of the above answers
- Increase network speed
- Allow using higher capacity disks

---

Let n be the decimal number 943. Its binary representation is:

- <span style="color:red;">11 1010 1111</span>
- 11 1011 0100
- 11 1101 0111
- 11 0101 0110
- 11 1010 1011

---

For the following algorithm, what relation is correct between the inputs p and q (both are positive natural numbers) and the output r?

```basic
def f(p,q)
    if p%q!=0 and q%p!=0:
        s=1
        u=1
        v=1
        while(u!=0) or (v!=0):
            s=s+1
            u=(u+1)%p
            v=(v+1)%q
        return s
    else:
        return p
```
- <span style="color:red;">p ≤ r ≤ p * q</span>
- min(p,q) ≤ r ≤ p+q
- r ≥ max(p,q)
- r ≤ max(p,q)
- r ≥ q

---

In Python, what will happen when trying to execute the following code?

```python
a = [1]
def f(x):
    x = x+[1]
    return x

b = f(a)
b[0] = 0
print(a)
print(b)
```

- The execution produces the following out put:[2] [0]
- The execution produces the following out put:[1,1] [0,1]
- The execution produces the following out put:[1] [0,1]
- The execution produces the following out put:[0,1] [0,1]
- An error occurs on line 3.

---

In SQL, which function allows to ret rieve a maximum value of a selected column?

- MAX()
- UPPER()
- UBOUND()
- HLIMIT()
- TOP()

---

In SQL, wchich clause is used to delete tuples from a table?

- CLEAR
- REMOVE
- DROP
- ERASE
- DELETE

---

In Python, what is the name of the following language construct?

```python
[i+5 for i in L if i>10]
```

- A contraction.
- A comprehension.
- An iteration.
- A completion.
- An extension.

### Thermodynamics

Calculate the power of a compressor able to compress (quasi static compression) a volume of air of $1 m^3$ at a constant temperature $T_0 = 0 °C$ from a pressure $P_0 = 10^5 Pa$ to a pressure $P_1 = 3.5 \cdot 10^5 Pa$ in one minute. Universal gas constant: $8.31 J/(mole\cdot K)$

- 3.78 kW
- 5.55 kW
- 7.98 kW
- <span style="color:red;">2.115 kW</span>
- None of the above answers.

---

If for a pure substance $T_A$ and $T_B$ denote the freezing point and the melting point, respectively, then the correct variation between entropy change and temperature is given by:

- ![](Thermodynamics1-1.jpg)
- ![](Thermodynamics1-2.jpg)
- ![](Thermodynamics1-3.jpg)
- ![](Thermodynamics1-4.jpg)
- None of the above graphs

> BEST ANSWER: picture 3

---

A mass $M$ is suspended to a metallic wire. The wire length is increased by the application of the load. This can be done suddenly (external work $W_1$) or by increasing gradually in a quasi static way the load from 0 to $M$ kg (external work $W_2$). Among these propositions which one is right?

- None of the above propositions
- $\color{red}{W_1> W_2}$
- $W_1< W_2$
- $W_1= W_2$
- $W_1= 2W_2$

---

A saturated liquid flows through an adiabatic relief valve. Because of the pressure drop, the liquid is partly vaporized and its temperature decreases. The fluid velocity at the valve inlet and outlet is considered negligible.

<center>![](Thermodynamics2-1.png)</center>

On the entropy-temperature diagram below, the state of the fluid at the valve inlet is represented by point A. What point describes the state of the fluid at the valve outlet?

<center>![](Thermodynamics2-2.png)</center>

- Point E
- None of points B, C, D or E
- Point B
- Point D
- <span style="color:red;">Point C</span>

---

A hollow sphere of steel contains a hot fluid at constant temperature $T_1$. The sphere is surrounded by still air at constant temperature $T_2$. We denote by $h_1$ and $h_2$ the heat transfer coefficients between the hot fluid and the inner wall of the sphere and between air and the outer wall of the sphere, respectively. The thermal conductivity of steel is denoted by $\lambda$. We assume the regime is steady. Given :

<center>![](Thermodynamics3.png)</center>

$\lambda  = 46 W/(m.K)$
$R_1 = 1.2m$
$R_2 = 1.26m$
$T_1 = 85°C$
$T_2 = 20°C$
$h_1 = 30W/(m^2.K)$
$h_2= 6W/(m^2.K)$
The heat flux across the sphere is:

- $1.2 \ 10^3W$
- $\color{red}{6.3 \ 10^3W}$
- $6.3 \ 10^4W$
- $1.2 \ 10^4W$
- None of the above answers

---

The thermostat controlling a room temperature is adjusted from 22°C down to 18°C. Assuming that the outside temperature is only 2°C, by how much will be reduced the consumption of fuel used for heating?

- I cannot answer this question without information about the thermo-physical properties of air
- None of the above answers
- I cannot answer this question because neither the surface area nor the thickness nor the thermal conductivity of the walls in the room are provided.
- <span style="color:red;">20 %</span>
- 81.8 %

---

A closed container containing 6g of hydrogen (ideal gas) is heated. The temperature increases from 15°C to 30°C. ($R= 8.32 SI, \gamma= C_p/C_v = 1.4$). Calculate the change in internal energy of the gas during this heating.

- $\Delta U = 93.6 J$
- $\Delta U = 0.936 J$
- $\Delta U = 9.36 J$
- $\Delta U = 9360 J$
- $\color{red}{\Delta U = 936 J}$

---

The first law of thermodynamics $\Delta (U + K) = W + Q$, where the system exchanges work W and heat Q with the surrounding, U is the internal energy and K the macroscopic kinetic energy :

- Is valid if the system is thermally insulated.
- Is always valid
- Is valid only for a gas
- Is valid only for an ideal gas
- <span style="color:red;">Is always valid for a closed system</span>

---

A fan is running steadily in a closed and thermally insulated room containing 40m3 of air. There is nobody in the room.
The initial state of air in the room is T = 300 K, P = 1 bar. The electrical power of the fan is 100 W.
By how much has the room temperature varied after 1 hour?
Data: air can be considered as an ideal gas of molar weight 29g/mol. The ideal gas constant is $R=8.314Jmol^{−1}K^{−1}$. The heat capacity of air at constant pressure is $c_P=1000JKg^{−1}K^{−1}$ and the heat capacity of air at constant volume is $c_v=720JKg^{−1}K^{−1}$.

- <span style="color:red;">+10.75 K</span>
- +12.5K
- None of the above answers
- -7.7 K
- +7.7 K

---

A heat pump works between a cold sink at $T_1=2°C$ and a hot source at $T_2=55°C$ . To ensure a comfortable temperature of 20°C inside a home (sweet home), $10.000kcalh^{−1}$ are necessary. The real coefficient of performance of the heat pump is 55% of the maximum coefficient of performance achievable theoretically. What is the required mechanical power?

- $20.3 \ 10^3W$
- $1.9 \ 10^3W$
- $2.9 \ 10^3W$
- None of the above answers
- $\color{red}{3.4 \ 10^3W}$

---

The gas filling a cylindrical cavity is compressed by a piston from an initial volume $V_1$ to a final volume $V_2$. In case a, the cavity is in contact with a thermal bath ensuring a constant temperature $T_s$. In case b, the cavity is thermally insulated.

- the final pressure may be either larger or smaller in case a than in case b, it depends on the external temperature
- the final pressure may be either larger or smaller in case a than in case b, it depends on the ratio $V_2/V_1$
- the final pressure is the same in both cases
- <span style="color:red;">the final pressure is larger if the cavity is thermally insulated</span>
- the final pressure is larger if the cavity is maintained to constant temperature

---

We consider a closed system $\Sigma$ of constant volume V, in contact with a thermal bath at constant temperature $T_s$. When the system $\Sigma$ reaches equilibrium:

NOTE : you might be more familiar with the notation "A" instead of "F" for the free energy.

- its free enthalpy G is a maximum
- <span style="color:red;">its free energy F is a minimum</span>
- its free energy F is a maximum
- its free enthalpy G is a minimum
- its enthalpy H is a minimum

---

For a closed system containing a single component, the differential of the enthalpy writes:

- dH = V dp - S dT
- dH = - p dV + T dS
- dH = p dV - S dT
- <span style="color:red;">dH = V dp + T dS</span>
- dH = - p dV – S dT

---

A system of 1m3 of air (ideal gas) at pressure $P_1 = 10^6$ Pa undergoes a relaxation at constant temperature.
The final pressure is $P_2 = 10^5$ Pa.
Determine the work and heat exchanged by the system with its external environment during the above transformation.

- W = +1500 kJ; Q = -1300 kJ
- <span style="color:red;">W = -2300 kJ; Q = +2300kJ</span>
- W = -1500 kJ; Q = +1500 kJ
- W = 0 kJ; Q = 0 kJ
- W = +2300 kJ; Q = -2300kJ

### Chemistry

Order these molecules from the most acid to the most basic :

1. ![](Chemistry1-1.png)
2. ![](Chemistry1-2.png)
3. ![](Chemistry1-3.png)
4. ![](Chemistry1-4.png)

- 1 > 2 > 3 > 4
- 3 > 4 > 1 > 2
- <span style="color:red;">2 >1 > 4 > 3</span>
- 2 > 1 > 3 > 4
- None of the above proposition is correct

---

In pure water at 293 K, 1 atm the saturation concentration of oxygen is close to:

- None of the above answers
- $9 mol.m^{−3}$
- $9 g. L^{−1}$
- $\color{red}{9 mg.L^{−1}}$
- $9 mol.L^{−1}$

---

In the reaction between ionized hydrogen $H^{+}$ and $H_{3}C - CH = CH_2$ the ion $H^{+}$will:

- Not bind at all with the molecule
- <span style="color:red;">Bind preferentially with the carbon atom of the $CH_2$ group</span>
- Bind preferentially with the carbon atom of the methyl group
- Bind preferentially with the carbon atom of the CH group
- Bind with a hydrogen atom

---

Which mesomeric group is not an electron-releasing group?

- ![](Chemistry2-1.png)
- ![](Chemistry2-2.png)
- ![](Chemistry2-3.png)
- ![](Chemistry2-4.png) (X: halogen)
- All the groups above are electron-releasing groups

> BEST ANSWER: picture 3

---

What type of bond does a sigma bond usually refer to?

- None of the above answers
- A hydrogen bond
- A ionic bond
- <span style="color:red;">A covalent chemical bond</span>
- A Van der Waals bond

---

Consider the reactions:
$C(s)+2H_2(g)→CH_4(g) \ \Delta H=−x kcal$
$C(g)+4H(g)→CH_4(g) \ \Delta H= −x_1 kcal$
$CH_4(g)→CH_3(g)+H(g)​​ \ \Delta H=+y kcal$
The bond energy of the $C-H$ bond is

- $x_1 \ kcal.mol^{−1}$
- $x/4 \ kcal.mol^{−1}$
- $x_1/4 \ kcal.mol^{−1}$
- $\color{red}{y \ kcal.mol^{−1}}$
- None of the above answers

---

What is the Manganese oxidation state in $KMnO_4$ ?

- +8
- <span style="color:red;">one of the above answes</span>
- +6
- +2
- +4

---

The water molecule structure is:

- Linear
- A cube
- <span style="color:red;">tetrahedron</span>
- sphere
- None of the above answers

---

Consider the following condensed structural formula:

<center>![](Chemistry3.png)</center>

The IUPAC (International Union of Pure and Applied Chemistry) nomenclature of this molecule is:

- dielthyl allyl cyanide
- <span style="color:red;">4-methyl pent-3-ene nitrile</span>
- None of the above answers
- 4-methyl pent-3-ene nitrate
- 5-cyano 2-methyl but-2-ene

---

In the following propositions which reaction corresponds to the water oxidation?

- $\color{red}{2 H_2O \leftrightarrow O_2 + 4 H^{+} + 4 e^{−}}$
- None of the above answers
- $2H^{+} + 2 e^{−} \leftrightarrow H_2$
- $H_2O \leftrightarrow H^{+} + OH^{−}$
- $H_2 + 0.5 O_2 \leftrightarrow H_2O$

### Telecommunications antenna

What kind of address 00:12:43:A3:BF:99 is ?

- <span style="color:red;">Ethernet</span>
- IPv4
- Wi-Fi
- Network
- LLC

---

The interfrange for an interferometric Young holes system is $2.5 mm$ . The distance between the plane of secondary sources and the screen is $D = 2 m$ , the distance between the holes is $a = 0.4 mm$ (see figure).

<center>![](TeleAntenna1.png)</center>

The wavelength of the light source S is equal to:

- 600 nm
- 750 nm
- <span style="color:red;">500nm</span>
- 550 nm
- 250 nm

---

An heterodyne radio receiver is made up with:

- Antenna + local oscillator + mixer + filters + circulator
- Antenna + filters + amplifier + mixer + transmission line
- <span style="color:red;">Antenna + filters + amplifier + mixer + local oscillator</span>
- Antenna + amplifier + mixer + filters + attenuator
- Antenna + local oscillator + mixer + filters + transmission line

---

What are the devices required in a high-speed fiber-optic communication system?

- LED transmitter - photoreceiver – multimode fiber
- LED transmitter - photoreceiver – single mode fiber
- None of the above
- <span style="color:red;">Laser transmitter – photoreceiver  - single mode fiber</span>
- Laser transmitter – photoreceiver – multimode fiber

---

The refractive index of diamond is $n = 2.42$ .  What is the wavelength, in diamond, of the red ray of a helium neon laser, given its wavelength in vacuum is $632.8 nm$ ?

- 332 nm
- 862 nm
- <span style="color:red;">262 nm</span>
- 662 nm
- None of the above answer

---

How many available adresses can you manage in a network whose mask is 192.168.0.0/10?

- 1024
- 10
- 1000
- 256
- <span style="color:red;">1022</span>

---

Considering the initial handshake in the TCP protocol, under perfectly normal operating conditions, and no errors whatsoever occurring, what flags a server responding to a client's SYN segment is supposed to set?

- CON,SYN
- ACK,CON
- ACK,SYN
- None of the above
- ACK,RST

### Materials

During a tensile test, a test piece breaks suddenly without any apparent deformation. Which of the following materials was tested?

- None of the above answers
- Gold
- Polyethylene
- <span style="color:red;">Alumina</span>
- Natural rubber

---

The mechanical properties of a brass alloy are the following: Young modulus $103 GP$ and yield strength $275 MPa$ . During a tensile test, plastic strain is observed when the load reaches $10,000 N$ . Assuming that the sample is a cylinder, what was its initial diameter?

- <span style="color:red;">6.8 mm</span>
- 4.1 mm
- None of the above answers
- 12.5 mm
- 8.3 mm

---

A tensile test is conducted on polypropylene at different load rates ($1 mm/min$ , $10 mm/min$ , $100 mm/min$ ) and the Young's modulus is determined from the slope and intercept of the obtained curves. Which sentence is correct?

- The Young modulus is the same in the three cases
- The Young modulus decreases when the load rate increases
- The Young modulus can increase or decrease with load rate
- None of the above sentences is correct
- <span style="color:red;">The Young modulus increases when the load rate increases</span>

---

A metallic cylindrical rod of circular cross section (radius $R$) and length $L$ is subjected to a twisting torque $T$.

<center>![](Materials1.png)</center>

The maximum shear stress is :

- $0$
- $2TL/(\pi R^4)$
- $None of the above answers$
- $\color{red}{2T/(\pi R^3)}$
- $2T/(\pi R^2L)$

---

An epoxy plate is reinforced by fine filaments in two directions. This material is:

- isotropic
- homogeneous
- anisotropic
- fragile
- a superconductor at room temperature

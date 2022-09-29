---
title: Mathematics
date: 2022-5-24
categories: Basic Knowladge
mathjax: true
---
## Guide

[Download](https://kjle.github.io/files/BasicKnowledge/Math_Guide.pdf) PDF version of **Mathematics Guid**.

### Elementary logic and Algebra

- Quantifiers, propositional calculus (sentential logic)
- Argumentum ab absurdum (argument to absurdity), recursion
- Set and function terminology
- Sets $\mathbb{N}$ (natural integers), $\mathbb{Z}$ (all integers), $\mathbb{Q}$ (rational numbers): arithmetic and combinatorics
- Polynomials: arithmetic, Euclidian division, functions, roots

### Probability and statistics

- Basic probability models
- Independent and dependent events
- Combinatorics (permutations and combinations)
- Random variables
- Standard discrete and continuous probability distributions (binomial, Normal, Poisson…)
- Descriptive statistics: measures of central tendency and dispersion, mean, median, mode, variance and standard deviation, skewness, flatness
- Central limit theorem
- Statistical estimation and testing
- Confidence intervals
- Basics of linear regression

### Properties of the set $\mathbb{R}$ (Real numbers)

- Interval, neighbourhood, lower/upper bound
- Sequences: limit (Cauchy criterion), convergence, rate of convergence, recursion ($u_{n+1}=f(u_n)$)
- Numerical function of the real variable: continuity, differentiability, monotony and variations, limits, inverse functions, Taylor formulas and inequality, finite increments formula, finite expansions, integrability, integral calculus (Riemann), definite and indefinite integrals
- Usual functions

### Complex numbers

- Properties of the set $\mathbb{C}$ (complex numbers)
- Arithmetic of complex numbers
- Complex numbers and trigonometric functions
- Usual complex functions (exponentials, hyperbolic functions…)

### Linear algebra / finite dimensional vector spaces

- Vector spaces, linear maps, vector basis and space dimensions,
- Matrices, determinant, rank, cofactors, trace, operations on matrices
- Linear systems of equations
- Endomorphisms
- Eigenvalues, Eigenvectors, characteristic polynomial of a system, Cayley-Hamilton theorem, diagonalization

### Finite dimensional Euclidean spaces (mainly $\mathbb{R}^2$ and $\mathbb{R}^3$)

- Scalar products, norms, distance, Cauchy-Schwarz inequality, orthonormal basis and orthonormalization, cross product
- Orthogonal matrices, diagonalization of symmetric real matrices
- Definition of the space $L^2$ (space of square-integrable functions): orthonormal basis in $L^2$, Legendre polynomials, basis of trigonometric functions
- Notions about Fourier series and Fourier transformation

### Analysis

- Rational functions and their decomposition, calculus of primitives, integral defined on a closed bounded interval, numerical methods, Taylor’s formula with integral
remainder, multiple integrals (functions of 2 or 3 variables), computation via successive integrations and change of variables formula
- Vector valued function of the real variable in $\mathbb{R}^2$ and $\mathbb{R}^3$: partial derivatives, differential, chain rule, and linear tangent application
- Taylor formula of order 2: application to local extrema
- Parametric curves in $\mathbb{R}^2$ and $\mathbb{R}^3$
- First and second order linear differential equations
- Path, surface and volume integral

### Numerical series

- Series of real or complex numbers, simple and absolute convergence
- Power series, radius of convergence
- Functions expandable in a power series on an interval
- Taylor series expansion of usual functions
- Sequences and series of functions of the real variable, entire series, application to Fourier series
- Simple, absolute, uniform and normal convergence
- Integrals over a real interval, integrals depending on a parameter
- Cauchy-Schwarz inequality
- Fourier, Laplace

## Test for Mathematics

In this test, the correct solution will be given in $\color{red}{red}$.

### Probability/Statisic

$250$ people attend a big party. They have either black beards, either blue eyes, either both. $120$ people have black beards. $85$ have blue eyes and $50$ have both blue eyes and black beards. What is the probability for a man in this party of having neither a black beard nor having blue eyes:

- $\frac{1}{5}$
- $\frac{7}{25}$
- $\color{red}{ \frac{19}{50} }$
- $\frac{12}{25}$
- $\frac{31}{50}$

### Real

If $f$ is a continuous function on the set of real numbers and if $a$ and $b$ are real numbers, which of the following must be true ?

&emsp;&emsp;I. $\int_{a}^{b} f(x) dx = \int_{a+3}^{b+3} f(x-3) dx$ 

II. $\int_{a}^{b} f(x) dx = \int_{a}^{3} f(x)-\int_{b}^{3} f(x) dx$ 

III. $\int_{3a}^{3b} f(x) dx = 3\int_{a}^{b} f(3x) dx$

- II and III only 
- II only 
- I only 
- I and II only 
- <span style="color:red;">I, II and III</span>

---

Let $f(x)=\frac{(x^{x})^{x}}{x^{(x^{x})}}$. What is $\lim_{x \rightarrow\infty}f(x)$ ?

- $\lim_{x \rightarrow\infty}f(x)=1$
- $\lim_{x \rightarrow\infty}f(x)=\frac{1}{e}$
- $\color{red}{\lim_{x \rightarrow\infty}f(x)=0 }$
- $\lim_{x \rightarrow\infty}f(x)=e$
- $\lim_{x \rightarrow\infty}f(x)=\infty$

---

If $f(x)=x^{x}$, then its derivative is given by $f^{'}(x)=$

- $(\ln x)x^{x}$
- $\color{red}{ (\ln x+1)x^{x} }$
- $(\ln x)x^{x−1}$
- $xx^{x}$
- $xx^{x−1}$

---

Assume that $f$ is a function twice continuously differentiable on the set of real numbers. If $f(0)=f(2)=3$ and $f^{'}(2)=−1$, then $\int_{0}^{2} xf^{''}(x)dx=$

- $-1$
- $1$
- $-3$
- $\color{red}{-2}$
- $2$

---

Let $f$ be a function on $\mathbb{R}$ to $\mathbb{R}$. Suppose that $f$ has first and second derivatives which are continuous over $\mathbb{R}$.
Then $\lim_{h\to 0}\frac{f(a+2h)+2f(a−h)−3f(a)}{h^{2}}$ is equal to :

- $\color{red}{3f^{''}(a)}$
- $f^{''}(a)$
- $2f^{'}(a)$
- $f^{'}(a)$
- $\frac{f^{'}(a)}{2}$

---

Let $f$ be the function defined by $f(x)=\int_{1}^{x^2} \ln (xt) dt$. For all $x>1$,$f^{'}(x)$ is equal to :

- $\ln(x)+2x\ln(x^2)$
- $2x\ln(x^2)+x−\frac{1}{x}$
- $6x\ln(x)+x^2−\frac{1}{x}$
- $4x\ln(x)+x+\frac{1}{x}$
- $\color{red}{6x\ln(x)+x−\frac{1}{x}}$

---

Let $f(x,y)=x^{2}−2x+y^{3}$ . Which of the following statements is true ?

- $f$ has a relative maximum at (1,0)
- $f$ has a relative minimum at (0,1)
- <span style="color:red;">$f$ does not have any relative maximum, nor relative minimum</span>
- $f$ has a relative minimum at (1,1)
- $f$ has a relative maximum at (1,0) and (0,1)

---

$\int_{2}^{3} \frac{−5x−1}{x^2−1}dx=$

- $\color{red}{−7\ln 2+2\ln 3}$
- $−7\ln 2+4\ln 3$
- $−5\ln 2+2\ln 3$
- $−4\ln 2+2\ln 3$
- $5\ln 2−2\ln 3$

### Complex numbers

Let $I=\int_{0}^{\pi/2}x\sin x dx$. Then, $I$ is equal to :

- $I=−\pi /2$
- $I=−1$
- $\color{red}{I=1}$
- $I=\pi/2$
- $I=−\pi$

---

Let $x$ be a real number and let $\cosh(x)=\frac{e^x+e^{−x}}{2},\sinh(x)=\frac{e^x−e^{−x}}{2}$ and $\tanh(x)=\frac{\sinh(x)}{\cosh(x)}$.
Let $f(x)=\left(\frac{1+\tanh(x)}{1−\tanh(x)}\right)^n$ where $n$ is an integrer
Which of the following statements is true ?

- $f(x)=2+\frac{\tanh(nx)}{1−\tanh(nx)}$
- $\color{red}{f(x)=1+\frac{2\tanh(nx)}{1−\tanh(nx)}}$
- $f(x)=\frac{1−\tanh(nx)}{1+\tanh(nx)}$
- $(x)=1+\frac{2}{1−\tanh(nx)}$
- $f(x)=\frac{2\tanh(nx)}{1−\tanh(nx)}$

---

In the complex plane, let $\mathcal{C}$ be the circle defined by $|z−2i|=4$. Then, with positive (anticlockwise), orientation, $\int_{\mathcal{c}} \frac{z}{z^2+9}dz$ is equal to :

- $2i\pi$
- $0$
- $\color{red}{i\pi}$
- $−i\pi$
- $i\pi/2$

---

Let $Z=\frac{−4}{1+i\sqrt{3}}$. Which of the following statements is true ?

- $Z^3=−8$
- $\color{red}{Z^3=8}$
- $Z=16$
- $Z=−16$
- $Z^2=4$

---

Let $z$ be a complex variable. Then $e^{iz}+e^{−iz}=0$ if and only if

- $z=0$
- $\color{red}{z=\pi/2+k\pi,k \in \mathbb{Z}}$
- $z=i(\pi/2+k\pi),k \in \mathbb{Z}$
- $z=\pi+2k\pi,k \in \mathbb{Z}$
- $z=\pi+k\pi,k \in \mathbb{Z}$

---

Let $x$ be a real number. Then, $(\sin(x/2))^2$ is equal to

- $\frac{1}{2}(1+\cos(x))$
- $\color{red}{\frac{\tan^2(x/2)}{1+\tan^2(x/2)}}$
- $\frac{1}{2}(1+\sin(x))$
- $\frac{1}{2}(1−\sin(x))$
- $\frac{1}{1+\tan^2(x/2)}$

---

Let $z$ be a complex variable and consider the equation hereafter where $i^2=−1$ and $\bar{z}$ is the conjugate of the complex $z$.
$z+2\bar{z}=9z$
Then, the complex solutions are :

- $\color{red}{z=3i,z=−3i,z=\sqrt{3} \ and \ z=−\sqrt{3}}$
- $z=\sqrt{3}i \ and \  z=-\sqrt{3}i$
- $z=3i,z=−3i,z=\sqrt{3}i \  and \ z=-\sqrt{3}i$
- $z=\sqrt{3} \ and \ z=−\sqrt{3}$
- $z=3,z=−3,z=\sqrt{3}i \ and \ z=−\sqrt{3}i$

### Algebra

Let 
$$A=\begin{pmatrix}
x & 1 \\
2 & 3 \\
\end{pmatrix} $$
where $x$ is a real number. Assume that 
$$A^2=\begin{pmatrix}
6 & 1 \\
2 & 11 \\
\end{pmatrix} $$. Then, what is the value of $x$ ?

- $x=0$
- $x=−1$
- $x=2$
- $x=1$
- $\color{red}{x=−2}$

---

Let $r$ be the remainder of the Euclidian division of $14^8$ by $17$ . What is the value of $r$ ?

- $r=1$
- $r=5$
- $r=7$
- $\color{red}{r=16}$
- $r=6$

---

Let $m$ be a real number. For what value (or values) of $m$ is the vector $(m,1,1)$ a linear combination of the vectors $(−1,−m,−1)$ and $(−1,−1,m)$ ?

- <span style="color:red;">1 only</span>
- −1 or 2
- 0 only
- no value of $m$
- 2 only

---

If $A$ and $B$ are two subsets of $\mathbb{R}$ , denote $A\setminus B=\{x\in A \land x \notin B\},A\cap B=\{x\in A  \land  x\in B\}$ and $A\cup B=\{x\in A \lor x\in B\}$ . Assume that for all integer $i$ , $B_i$ is a subset of $\mathbb{R}$  and let $A$ be a subset of $\mathbb{R}$ . Which of the following statements is true ?

- $A\setminus (\cap_{i \in \mathbb{N}}(B_i \cup A))=\cap_{i \in \mathbb{N}}(A\setminus B_i)$
- $A\setminus(\cap_{i \in \mathbb{N}}B_i)=\cap_{i \in \mathbb{N}}(A\setminus B_i)$
- $\color{red}{A\setminus(\cup_{i \in \mathbb{N}}(B_i \cap A))=\cap_{i \in \mathbb{N}}(A\setminus B_i)}$
- $A\setminus(\cup_{i \in \mathbb{N}}(B_i\setminus A))=\cup_{i \in \mathbb{N}}(A\setminus B_i)$
- $A\setminus(\cup_{i \in \mathbb{N}}B_i)=\cup_{i \in \mathbb{N}}(A\setminus B_i)$

---

Let $x$ and $y$ be real numbers. Let $A$ be the matrix 
$$
A=\begin{bmatrix}
x & 1 & 0\\
1 & y & 1 \\
1 & 1 & 1 \\
\end{bmatrix}
$$ 
Then

\begin{bmatrix}
1 \\
2 \\
3 \\
\end{bmatrix}

is an eigen-vector of $A$ if and only if

- $x=−3 \ and \ y=0$
- $x=0 \  and \ y=−3$
- $\color{red}{x=0 \  and \ y=0}$
- $x=1 \  and \ y=1$
- $x=2 \  and \ y=3$

---

Assume $M$ is a $3×3$ matrix such that 
$$ M \begin{pmatrix}0\\ 1\\ 2 \\ \end{pmatrix} = \begin{pmatrix}0\\0\\0 \end{pmatrix}$$ 
and
$$ M \begin{pmatrix}3\\ 4\\ 5 \\ \end{pmatrix} = \begin{pmatrix}1\\0\\1 \end{pmatrix}$$ 
Then the product  
$$ M \begin{pmatrix}6\\7\\8 \\ \end{pmatrix} = ? $$

- $$\color{red}{\begin{pmatrix} -1\\2\\0 \end{pmatrix}}$$
- $$ \begin{pmatrix} 0\\0\\1 \end{pmatrix}$$
- $$ \begin{pmatrix} 1\\-1\\0 \end{pmatrix}$$
- $$ \begin{pmatrix} 9\\10\\11 \end{pmatrix}$$
- not uniquely determined by the information given

### Euclidean

In the xy−space, consider the points (with their cartesian coordinates) $A=(−1,1),B=(3,−1)$ and $C=(1,4)$ . Let H be the point obtained by projecting orthogonally the point $C$ onto the line $(AB)$. What are rhe cartesian coordinates of $H$ ?

- $H=(3/5,4/5)$
- $\color{red}{H=(−3/5,4/5)}$
- $H=(−4/5,3/5)$
- $H=(4/5,3/5)$
- $H=(3/5,−4/5)$

---

Among the following sets, which one is not a vector subspace ?

- $E_4={(x,y,z)∈\mathbb{R}^3, x=y=z=0}$
- $E_3={(x,y,z)∈\mathbb{R}^3, y=z=0}$
- $E_1={(x,y,z)∈\mathbb{R}^3, x+y=0}$
- $E_5={(x,y,z)∈\mathbb{R}^3, x=y=z}$
- $\color{red}{E_2={(x,y,z)∈\mathbb{R}^3, x+y+3z=2}}$

---

In the xyz−space, for which values of $a$, do the points $(1,0,a),(a,1,0)$ and $(0,a,1)$ belong to the same plane ?

- $a=−2$
- $a=0$
- $a=1$
- $\color{red}{a=−1}$
- $a=2$

### Analysis

Which of the following functions $x\mapsto y(x)$ is solution to the following differential equation $y^{'}+2xy=xe^{−x^2}$

- $y(x)=(x^2)e^{−x^2}$
- $y(x)=(x^2)e^{−x^2/2}$
- $y(x)=(x+3)e^{−x^2}$
- $\color{red}{y(x)=(\frac{x^2}{2}+9)e^{−x^2}}$
- $y(x)=(\frac{x^2}{2})e^{x^2}$

---

Let $y$ be the solution of the differential equation $y^{'}=2xy$ satisfying $y(0)=1$ . Then $y(1)$ is equal to

- $e^8$
- $1$
- $e^4$
- $e^2$
- $\color{red}{e}$

---

Let $y$ be the solution of the differential equation $y^{''}+2y^{'}−3y=0$ satisfying $y(0)=0$ and $y^{'}(0)=4$ . Then $y(1)$ is equal to

- $2e+e^{−3}$
- $1$
- $e$
- $e−e^{−3}$
- $0$

---

Let $P(x,y)=x^2−y^2−3x+4$ and $Q(x,y)=2xy−3y$ . Which of the following statements is FALSE ?

- $\frac{\partial^2 P(x,y)}{\partial x \partial y} = \frac{\partial^2 Q(x,y)}{\partial x^2}$
- $\frac{\partial P(x,y)}{\partial x} = 2x-3$
- $\frac{\partial P(x,y)}{\partial y} = - \frac{\partial Q(x,y)}{\partial x}$
- $\frac{\partial P(x,y)}{\partial x} =   \frac{\partial Q(x,y)}{\partial y}$
- $\color{red}{\frac{\partial^2 P(x,y)}{\partial x^2} = -\frac{\partial^2 Q(x,y)}{\partial x \partial y}}$

---

Let $A=\iint_{\mathbb{R}}2e^{−x^2−y^2}dxdy$ . Then,

- $A=\frac{\pi^2}{2}$
- $A=\pi^2$
- $A=\sqrt{\pi}$
- $\color{red}{A=\pi}$
- $A=\frac{\pi^2}{6}$

### Series

Let $S_n(x)=\sum_{n=0}^{\infty} \frac{n+2}{n+1} x^{n}$ where $x\in (0,1)$ . Which of the following statements is true ?

- $\lim_{n\to \infty} S_n(x)=\frac{x}{1-x}-\frac{\ln(1-x)}{x}$
- $\lim_{n\to \infty} S_n(x)=\frac{1}{1-x}+\frac{\ln(1-x)}{x}$
- $\color{red}{\lim_{n\to \infty} S_n(x)=\frac{1}{1-x}-\frac{\ln(1-x)}{x}}$
- $\lim_{n\to \infty} S_n(x)=\frac{1}{1-x}-\frac{\ln(1+x)}{x}$
- $\lim_{n\to \infty} S_n(x)=-\frac{1}{1-x}-\frac{\ln(1-x)}{x}$

---

Let $u_n=\ln(2n^2−n)−\ln(3n+1)$. Which of the following statements is true ?

- $\color{red}{\lim_{n \to \infty} (u_n - \ln(n))=\ln(\frac{2}{3})}$
- $\lim_{n \to \infty} \frac{u_n}{\ln(n)}=\frac{2}{3}$
- $\lim_{n \to \infty} \frac{u_n}{\ln(n)}=\infty$
- $\lim_{n \to \infty} u_n=0$
- $\lim_{n \to \infty} \frac{u_n}{\ln(n)}=\frac{4}{3}$

---

What is the limit when $n$ tends to $+\infty$ of $S_n=\sum_{k=1}^{n}=\frac{1}{n}\sin(\pi \frac{k}{n})$ ?
$\lim_{n\to \infty}S_n=$

- $\color{red}{\frac{2}{\pi}}$
- $\frac{1}{\pi^2}$
- $\frac{1}{\pi}$
- $-\frac{1}{\pi}$
- $-\frac{2}{\pi}$

## Exam in 2022-5-24

This part will incloude some of the questions in the Exam. It will not given the correct answer.

---

Consider these four integrals, which one isn't well defined?

(1). $\int_{0}^{+\infty} \frac{\sin(x)}{x}dx$

(2). $\int_{0}^{+\infty} \sin(x^2)dx$

(3). $\int_{0}^{+\infty} \sin(x^4+x^3+1)dx$

(4). $\int_{0}^{+\infty} \frac{x}{1+x^5\sin^2(x)}dx$

- 1
- 2
- 3
- 4
- None of them

---

Let $(x,y,z)\in \mathbb{R}^3$ , then $x^2+2y^2+3z^2 \leq 1 \Rightarrow |x+y+z| \leq a$ where the best $a$ in any cases is 

- $\sqrt{11/6}$
- $\sqrt{9/14}$
- $\sqrt{17/14}$
- $\sqrt{14/17}$
- $2$

---

Let $(a,b,c)$ three complex numbers. The value of
$$
\begin{vmatrix}
b+a & c+b & c+a \\
b^2+a^2 & c^2+b^2 & c^2+a^2 \\
b^3+a^3 & c^3+b^3 & c^3+a^3 \\
\end{vmatrix}
$$
is

- $abc(b-a)(c-a)(c-b)$
- $-2abc(b-a)(c-a)(c-b)$
- $2abc(b-a)(c-a)(c-b)$
- $-3abc(b-a)(c-a)(c-b)$
- $3abc(b-a)(c-a)(c-b)$

---

The value of $\sum_{n=0}^{+\infty} \frac{1}{(2n+1)^4}$ is

- $\pi^4/12$
- $\pi^4/120$
- $\pi^4/60$
- $\pi^4/96$
- $\pi^4/90$

---

Let $(a,b,c) \in \mathbb{C}^3$ such that $|a|=|b|=|c|=1$ . We have

- $|ab+bc+ca| > |a+b+c|$
- $|ab+bc+ca| < |a+b+c|$
- $|ab+bc+ca| = |a+b+c|$
- $|\frac{1}{a}+\frac{1}{b}+\frac{1}{c}| = |a^2+b^2+c^2|$
- $|ab+bc+ca| = |a^2+b^2+c^2|$

---

In a school, 10% of childrens are given a colour test. Overall, 5% of the school's children are colourblind. Out of all the childrens given a colour test, 8% are colourblind . If a children is colourblind, what is the probability that they won't take the colour test?

- 84%
- 86%
- 96%
- 94%
- 90%

---

let $j=\exp(2i\pi/3)$ and $A$ is the matrix 
$$
\begin{bmatrix}
1 & j & j^2 \\
j & j^2 & 1 \\
j^2 & 1 & j \\
\end{bmatrix}
$$
and
$$
A_1 = \begin{bmatrix}
0 & 0 & 0 \\
0 & 0 & 1 \\
0 & 0 & 0 \\
\end{bmatrix}
$$
$$
A_2 = \begin{bmatrix}
0 & 0 & 0 \\
0 & -1/2 & \sqrt{3}/2 \\
0 & \sqrt{3}/2 & 1/2 \\
\end{bmatrix}
$$
$$A_3 = \bar{A}$$
$$ A_4 = A^{t}$$
then $A$ is not similar to

- $A_1$
- $A_2$
- $A_3$
- $A_4$
- None of them

---

Let $X_1$ and $X_2$ be the respective results of two independent rolls of an unbiased die with $6$ faces. What is the probability that $X_1 + X_2$ belongs to $\{1,\cdots,3\}$ ?

- $1/6$
- $1/18$
- $1/3$
- $1/12$
- $1/2$

---

For $n \geq 2$ , let $x_n$ be the unique real $x \in ] 0,1 [$ which satisfies $x^n + x^{n-1} + \cdots + x = 1$ . We study the sequence $(x_n)_{n\geq 2}$ .

- $\lim_{n \to \infty} x_n = 0$
- $\lim_{n \to \infty} x_n = 1$
- The sequence $(x_n)_{n \geq 2}$ has no limit.
- none of them
- $\lim_{n \to \infty} x_n = 1/2$

---

An urn contains 3 blue balls, 5 while balls and 2 red balls. One retrives randomly two balls from the urn. What is the probability that, among the 8 remaining balls, the number of blue balls in the urn is equal to 1?

- $1/15$
- $1/45$
- $1/60$
- $1/75$
- $1/30$

---

The partial decomposition of the rational function $R$ in $\mathbb{R}[x]$ where $R=\frac{X^4-X^2+1}{X(X^2+1)}$ is

- $X+1+1/X-2X/(X^2+1)$
- $X+1/X-3X/(X^2+1)$
- $X+2/X-5X/(X^2+1)$
- $X+1/X-2X/(X^2+1)$
- $1/X-X/(X^2+1)$

---

Let $a>0$ and , for $n \in \mathbb{N}^{*}$ , $u_n = \sin(\frac{(-1)^n}{n^a}+\frac{1}{n^{5a}})$ . Then $\sum u_n$ converge if and only if

- $a>0$
- $a>2$
- $a>1/3$
- $a>1$
- $a>1/5$

---

For each integer $n \geq 2$ , we define $u_n = \sum_{i+j=n,i\geq 1,j\geq 1} \frac{1}{ij}$

- $\lim_{n \to \infty} u_n = +\infty$
- $u_{n \to \infty} \sim \frac{2 \ln n}{n}$
- $u_{n \to \infty} \sim \frac{\ln n}{n}$
- $u_{n \to \infty} \sim (\ln n)^2$
- none of them


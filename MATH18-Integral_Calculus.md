Crap… 🫠
**_I WILL_** pass ts

# 1. Integration?
So if differentiation deals with _the rate of change_ of function per interval, integration is in the inverse (or the opposite) where we find how much is _the total_ area of the function `indefinite ? per : in` the interval.

Stealing from _Math is Fun_, if derivative is how much the water is filled **per interval** (say min), integral is how much is the **total**.

Still don't get it? See the green shaded area in the image below, that's what we're looking for. And the:
- lines crossing x-axis are the functions;
- how the aforementioned lines rise/fall is the derivative; and
- the lines in y are the interval boundaries

![[Screenshot_20251130_185621_YouTube.jpg]]

Since integration is the undoing of integration, there's no core formula unlike differentiation so we have to use multiple techniques which we'll talk later.
# 2. Differentiation Recap

~~\severance{Previously, in Differential Calculus}~~
Derivatives are still relevant because some techniques e.g., [[# 4. Integration by Substitution | u-sub]] and [by parts](#Integration By Parts) require it so:
## 2.0. First Principle
Aka by the definition:
$$\lim_{h\to{0}} = \frac{f(x+h) - f(x)}{h}$$

## 2.1. Constant rule
Constants are just 0 because well, thing minus itself is 0.
## 2.2. Constant Multiple Rule
$$\frac{d}{dx} = [cf(x)] = c \frac{d}{dx}f(x)$$ Or $c * f'(x)$
## 2.3. Sum Rule
$$\frac{d}{dx}[f(x)+g(x)]= f'(x)+g'(x)$$
## 2.4. Difference Rule
Same as sum but with subtraction ($-$)
## 2.5. Product Rule
$$\begin{align}
\frac{d}{dx}[f(x)g(x)]= \\\\

f(x)g'(x)+g(x)f'(x)
\end{align}$$
TLDR:
$$vu'+uv'$$
## 2.6. Power rule
$\diff f(x) = x^n$
$nx^{n-1}$

Constant multiple rule still apply btw so if ($f(x) = c(x)^n$){
$f'(x)= (c)(n)x^{n-1}$ 
}
## 2.7. Quotient Rule
$$\frac{d}{dx}[\frac{f(x)}{g(x)}] = \frac{[f'(x)g(x)]-[g'(x)f(x)]}{[g(x)]^2}$$
In a nutshell:
$$\frac{(u'v) -(v'u)}{v^2}$$
## 2.8 Chain Rule
$$\frac{d}{dx}f(g(x)) = f'(g(x))g'(x)$$
TLDR:
$$ (v'(u)) \* u'$$

## 2.8. On Transcendental Functions
### 2.8.1. Exponential and Logarithmic Functions
- $\diff e^x = e^x$
- $\diff \ln{x} = \frac{1}{x}$
- $\diff \ln[f(x)] = \frac{1}{f(x)}f'(x)$
- $\diff \log_a(x) = \frac{1}{x \ln a}$
- $\diff \log_a(x) = \frac{1}{f(x) \ln a}f'(x)$
### 2.8.2 Trigonometric Functions
- $\diff \sin(x)=\cos(x)$
- $\diff \cos{(x)} = -\sin{(x)}$ 
- $\diff \tan(x) = \sec^2(x)$
### 2.8.3 Inverse Trig Functions
- $\diff \arcsin(x) = \frac{1}{\sqrt{1-x^2}}$
- $\diff \arctan(x)=\frac{1}{1+x^2}$
- $\diff arcsec(x) = \frac{1}{x\sqrt{x^2-1}}$

# 3. Antiderivatives

> [!definition]
> A function $F$ is called an antiderivative of a function on an interval $I$ of $F'(x)=f(x)$ for every value of $x$ in $I$


Basically, an antiderivative is the result of integration. When it's differentiated, it should go back to the function you just integrated

## 3.1. Integration/Antidiferentiation
A process of finding the set of all antiderivatives in a given function
$\int f(x)dx$ can be read as "integral of $f(x)dx$"
## 3.2 Formulas
1. **Power Rule**
$$\int x^ndx = \frac{x^{n+1}}{n+1}+C \text{ where n != -1}$$
2. $\int dx = 1+C$
3. For every a E /R, $\int a f(x)=$ $a\int{f(x)}$
4. $\int [f(x)±g(x)]dx =$ $f(x)dx±g(x)dx$
# 4. Integration by Substitution 

> [!Formula(?)]
> $$f(g(x)) = f(g(x))g'(x)$$
> Or just
> $$v(u) = v(u) \* u'$$

Aka **U substitution**, let shorten it to **_u-sub_**.
1. Find $u$
2. Diff(u); if $g'(x)$ != $f(x)$, stop
3. Simplify $du$ (basic fraction btw, dw). 
4. $\frac{du}{n}$ where n is what factor you used for simplification
5. dx is now du
6. Isolate the fraction to integral
7. _Finally,_ integrate
8. Simplify again
9. Insert back the u

E.g.:
$\int (3x-2)\sqrt[3]{(3x^2-4x)}dx$ 
$$
\begin{align}
(3x-2)(3x^2-4x+x)^{\frac{3}{2}}\\
^{\text{//btw, sqrt = $n^{\frac{1}{[root]}}$
and $\frac{1}{2} \* \frac{3}{1} = \frac{3}{2}$}}\\
\text{1.) Let }u=3x^2-4x+7 \\
\text{2.) }du = 6x-4dx \\
\text{3.) }du = \frac{6x-4}{2} = 3x-2 \text{ ✅}\\
\text{4 }\frac{du}{2}=3x-2 \\
\text{5.) }(3x-2)(\frac{du}{2})^{\frac{2}{3}} \\
\text{6.) }\frac{1}{2}\int u^{\frac{2}{3}}du \\
\text{7.) }\frac{1}{2}\int \frac{u^{\frac{2}{3}+1}}{{\frac{2}{3}-1}} \\
= \frac{1}{2} \int \frac{u^{\frac{5}{3}}}{\frac{5}{3}}\\
\text{8.) }\frac{3}{5}\* \frac{1}{2} u^{\frac{5}{3}}+C \\
\text{//fraction division btw} \\
\frac{3}{10}u^\frac{5}{3}+C \\
\text{9. }\frac{3}{10}(3x^2-4x+7)^{\frac{5}{3}}+C👍
\end{align}
$$



# Fundamental theorem


> [!theorem]
If a function $f$ is continuous on the interval \[a, b], then $$\int^b_{a}f(x)dx=F(b)-F(a)$$ where $F$ is the antiderivative of $f$


## Definite properties of integral
$$
\int_{b}^{a}f(x)dx=-\int_{a}^{b}f(x)dx
$$
$$
\int_a^af(x)dx = 0
$$
$$\begin{align}
\int_a^bf(x)dx = \\ \\
\int_a^cf(x)dx +\int_c^bf(x)dx
\end{align}$$

#  Integration by parts
Remember: $$\begin{align}
\frac{d}{dx}[f(x)g(x)]= \\ f(x)g(x)+g(x)f(x)
\end{align}$$
Integrating both sides with respect to x, we get: $$ \begin{align}
f(x)g(x)= \\ \int[f(x)g'(x)+g(x)f'(x)]dx
\end{align}$$
Let $u=f(x)$ and $v=g(x)$. Then:
$$uv=\int(udv+vdu)$$
$$
uv=\int udv + vdu
$$
$$
\int udv = uv - \int vdu
$$
Tip: remember LIATE(Logarithmic, Inverse Trigonometric, Exponential, Trigonometric, Exponential) order

sizeof(function) == 1 ? $dv = dx$

If there's literally no other function (e.g., $\ln|x|dx$), dx will be the $v$
## Trigonometric Integrals
Commons
$$
\text{Evaluating } \int tan^mxsec^nxdx
$$
If the power of secant is even ($n=2k,k>=2$)
E.g.,
$\int \tan^6x\sec^4xdx$ 
$= \int\tan^6x(1+tan^2x)sec^2xdx$

$du$ 
Assignment:
- - -
1. $\int_{0}^{\pi} \sin^2x\cos^4xdx$
2. $\int \frac{1-\tan^2x}{sec^2x}dx$ 
- - -
Unit circle:
$30° = \frac{\pi}{6}$
$45° = \frac{\pi}{4}$
$60° = \frac{\pi}{3}$
$90° = \frac{\pi}{2}$
- - -

# Partial Fraction

# Rationalizing Substitution
# Improper Integrals

# Area of Region Bounded by Curves
Now we're getting to what is integration for. Here, we deal with the area
> [!theorem]
> 
If $f$ and $g$ are continuous functions in the interval $[a , b]$ and $f(x) \geq g(x)$ for all $x \in [a,b]$, then the area of the region $R$ bounded above by $y=f(x)$, below by $y=g(x)$ and the vertical lines $x=a$ and $x=b$ is given by $$A_R = \int_a^b [f(x)-g(x)]dx$$

Example:
1. Area of plane bounded by the curves $y=x^2$, $x=-1$, $x=2$, & $y=-1$
Since $y=x^2$ is a parabola, table of values time 

| X   | Y     |
| --- | ----- |
| -2  | 4     |
| -1  | 1     |
| 0   | 0 duh |
| 1   | 1     |
| 2   | 4     |

Now, let's draw it. Oh yeah, make sure to draw the graph. You'll want to as it's easier to see the parabola of the function

![[Screenshot_20251130_185621_YouTube.jpg]]

As you can see, the upper fn/$f(x)$ is $y=x^2$ and the lower fn/$g(x)$ is $y=-1$. Now,
$$\begin{align}
A_R=\int_a^b[f(x)-g(x)]dx \\  \\
\text{$a$ will be the x in leftmost = -1} \\ \text{b is x in rightmost = 2}\\
=\int_{-1}^{2}[x^2-(-1)]dx \\
= \frac{x^3}{3}+x |^2_{-1} \\
\text{substitution time} \\
= (\frac{2^3}{3}+2) - (\frac{-1^3}{3}+(-1)) \\
= \frac{8}{3} + 2 - \frac{-1}{3}+(-1) \\
= \frac{8}{3}+\frac{1}{3}+1 \\
= \frac{9}{3}+3 = 3+3 \\
= 6 \text{ sqr units👍}
\end{align}$$


# Volume of the Solid of Revolution 
## Disk Method
> [!theorem]
> 
Let $f$ be continuous, nonnegative function on the interval $[a,b]$. Then the solid $S$ is obtained by revolving the region $$\begin{aligned}
R=
{(x,y):a\leq x \leq b, 0 \leq y \leq f(x)}
\end{aligned}$$ about the $x$ axis has a volume $v$ by the formula $$V(S) = \pi \int [f(x)]^2dx$$

And by revolving, we mean from 
![[Screenshot_20251130_213216_YouTube.jpg]]
To
![[Screenshot_20251130_213243_YouTube.jpg]]
Example:
1. The curve $y=\sqrt{x}$, the line $x=2$, and the x axis form the sides of a bounded region $R$. Find the volume of the solid generated by revolving the $R$ and its axis

Table of values time.
Since the parabola(?) is $y=\sqrt{x}$,

| X   |     |
| --- | --- |
| 0   | 0   |
| 1   | 1   |
| 4   | 2   |

Just put perfect squares for your sanity. Now,
$$
\begin{aligned}
V(S)=\pi\int_0^2 (\sqrt{x})^2dx \\
\text{sqrt and squared will cancel out so} \\
= \pi\int_0^2 xdx \\
= \pi(\frac{x^2}{2}|_0^2)
=\pi(\frac{2^2}{2}-\frac{0^2}{2}) \\
=2\pi \text{ cubic units 👍}
\end{aligned}
$$

## Shell Method
> [!theorem]
> 
Let $f$ be continuous, nonnegative function on the interval \[a,b] with $a \geq 0$. Then the solid $S$ obtained by revolving the region $$R = {(x,y):a \leq x \leq b, 0 \leq y \leq f(x)}$$ about the y-axis has a volume $V$ given by the formula $$V(S)=2\pi\int_a^b xf(x)dx$$

Example:
1. $R$ is bounded by lines $y=0$ and $x=3$ is revolved about the y-axis. Find the $V(S)$
$$\begin{align}
\text{404 not found} \\
V(S)=2\pi\int_0^3 x(x^2)dx \\
\text{simplify $x(x^2)$}\\
= 2\pi \int_0^3 x^3dx\\
= 2\pi \frac{x^2}{4}|_0^3\\
= 2\pi (\frac{3^4}{4} - \frac{0^4}{4})\\
\frac{81\pi}{2} \text{ cubic units 👍}\\
\end{align}$$
# Double Integrals

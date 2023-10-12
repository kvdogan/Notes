
$$
\begin{align}
\text{Equation of a plane in } \mathbb{R}^3 &: Ax+By+Cz=D \tag{1}\\
\text{Equation of  line in } \mathbb{R}^2 &: Ax+By = C \tag{2} \\
\end{align}
$$

### Cartesian ~ Parametric Coordinates
##### How to write a line equation
$$
\begin{align}
	y &= mx +b
	\begin{cases}
		m: slope \Rightarrow tan \theta = \frac{y_2 - y_1}{ x_2 - x_1}\\
		\text{b: y-intercept when } x = 0 \\
	\end{cases} \tag{3} \\ \\
y - y_1 &= m(x - x_1) \tag{4}
\end{align}
$$

##### How to transform linear equation
of type $Ax + By + C = 0$ into vector and find normal vector

$$
\text{Example linear equation: }2x-8y+6=0
$$
$$
\begin{aligned}
y &= \frac{2x+6}{8} = t \quad \begin{cases}
													y = 0 + 1t \\
													x = -3 + 4t \\
												\end{cases} \\
\vec r &= r_0 + \vec v t \\
\vec r &= \underbrace{(-3, 0)}_{\text{size of vector}} + \underbrace{(4, 1)}_{\text{direction of vector}}.t \\
\end{aligned}
$$
Normal vector is all about direction hence both of the following is a normal vector but in opposite orthogonal direction for the given equation. 
$$
\vec n = x - 4y; \rightarrow N(1, -4) \quad \text{OR} \quad \vec n = -x + 4y; \rightarrow N(-1, 4)
$$
 Generalized normal vector formula:
$$
\begin{align}
\vec n = Ax + By \tag{5}
\end{align}
$$

##### How to transform parametric equation
of type $\begin{cases} x = x_0 + at \\	y = y_0 + bt \end{cases}$ to into linear equation

$$
\text {Example parametric equation: }
\begin{cases} 
	x &= -3 + 4t \\
	y &= 0 + t
\end{cases}\\
$$

$$
\begin{aligned}
	t =  \frac{x - x_0}{a} \quad &\& \quad	t = \frac{y - y_0}{b} \\
	\frac{x - x_0}{a} &= \frac{y - y_0}{b}\\
	t =  \frac{x - (-3)}{4} &= \frac{y - 0}{1} \\
	x -4y + 3 &= 0
\end{aligned}
$$
Generalized formula for converting parametric eq.to linear equation
$$
\begin{align}
	b(x-x_0)-a(y-y_0)=0 \tag{6}
\end{align}
$$



## How to write a plane formula by using a normal vector
Plane formula can be written by using a normal vector $\vec n$ and a vector that has a point on the plane $\vec{X_0}$


$$
\vec{n} = \begin{bmatrix} 1 \\ 3 \\ -2 \end{bmatrix}
\vec{X_0} = \begin{bmatrix} 1 \\ 2 \\ 3\end{bmatrix}
$$


We write another vector with a point on plane as $\vec{X_1}=\begin{bmatrix} x \\ y \\z \end{bmatrix}$

$$
\begin{aligned}
\vec{n}(\vec{X_1}-\vec{X_0}) = 0 \rightarrow \vec{n} &= \begin{bmatrix} 1 \\ 3 \\ -2 \end{bmatrix} .\left ( \begin{bmatrix} x \\ y \\z \end{bmatrix} - \begin{bmatrix} 1 \\ 2 \\ 3\end{bmatrix} \right ) &= 0\\ \enspace \\
&= \begin{bmatrix} 1 \\ 3 \\ -2 \end{bmatrix} .\left ( \begin{bmatrix} x-1 \\ y-2 \\ z-3 \end{bmatrix} \right ) &= 0 \\ \enspace \\
\boxed{x+3y-2z=1} &
\boxed{Ax+By+Cz=D}
\end{aligned}
$$


### How to get a normal vector from plane equation
$$
\begin{align}
\text{Plane equation: } Ax+By+C=D \quad &\Rightarrow \quad \vec n = A \hat \imath +B \hat \jmath +C \hat k \\
-3x + \sqrt{2}y + 7z = \pi \quad &\Rightarrow \quad \vec n = -3 \hat \imath + \sqrt 2 \hat \jmath + 7 \hat k \tag{7}
\end{align}
$$

### How to get distance between a point and a plane

$\text{Theoretical  plane and } \vec n \text{ from eq(1):  } Ax+By+C=D \quad \Rightarrow \quad \vec n = A \hat \imath +B \hat \jmath +C \hat k$


|                                                    | **Definitions**                                          |
| -------------------------------------------------- | -------------------------------------------------------- |
| ![[Coordinate Systems - Planes - Distances-1.png]] |                                                          |
|                                                    | Plane: $Ax+By+C=D$<br>                                   |
|                                                    | Normal :$n = A \hat \imath +B \hat \jmath +C \hat k$<br> |
|                                                    | P1 : Point on plane<br>                                  |
|                                                    | P2 : Point out of a plane                                |




$$
\begin{align}
\vec f = \|\vec{p_2} - \vec{p_1} \| &= (x_2-x_1) \hat \imath + (y_2-y_1) \hat \jmath + (z_2-z_1) \hat k \tag{8} \\
D &= \| \vec f \|.\cos\theta \tag{9} \\
&= \frac{\|\vec n\| \| \vec f \|.\cos \theta}{\| \vec n \|} = \frac{\vec n . \vec f}{\| \vec n \|} \\
\frac{\vec n . \vec f}{\| \vec n \|} &= \frac{ (Ax_2-Ax_1) + (By_2-By_1) + (Cz_2-Cz_1) - D}{\sqrt{A^2 + B^2 + C^2}} \tag{10}
\end{align}
$$


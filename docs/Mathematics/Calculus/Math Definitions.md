# Derivative

$$
\begin{align}
&\lim_{h \rightarrow 0} \frac{f(x+h)-f(x)}{h} \tag{1}\\
\end{align}
$$
## Derivative of integral

![[Math Definitions-1.png]]

# Integral

![[Math Definitions-2.png]]

# Numbers
$\mathbb{R}$ = Real numbers includes all real number [-inf, inf]
$\mathbb{Q}$ = Rational numbers ( numbers written as ratio)
$\mathbb{N}$ = Natural numbers (all positive integers starting from 1. (1,2,3....inf)
$\mathbb{Z}$ = Integers ( all integers positive and negative ( -inf, ..., -2,-1,0,1,2....inf)

# GCD & LCM
$\operatorname{lcm}(a,b)	=	\text{least common multiple of integers a and b}$  
$\operatorname{gcd}(a,b)	=	\text{greatest common divisor of integers a and b}$  

$$
\begin{align}
	\operatorname{lcm}(a,b)=\frac{|a \cdot b|}{\operatorname{gcd}(a,b)} \tag{2}\\
\end{align}
$$
# Neural Network Representation

```mermaid
%%{
	init: {
		'theme': 'base',
		'themeVariables': {
			'primaryColor': '#BB2528',
			'primaryTextColor': '#fff',
			'primaryBorderColor': '#7C0000',
			'lineColor': '#F8B229',
			'secondaryColor': '#006100',
			'tertiaryColor': '#fff' 
		} 
	} 
}%%
graph LR
x(( x1))
y(( x2))

a(( z1/a1))
b(( z2/a2))
c(( z3/a3))
d(( z4/a4))
u(( u1/o1))

x -. w1 .-> a
x -. w2 .-> b
x -. w3 .-> c
x -. w4 .-> d

y -- w5 --> a
y -- w6 --> b
y -- w7 --> c
y -- w8 --> d

a -- v1 --> u
b -- v2 --> u
c -- v3 --> u
d -- v4 --> u

subgraph input layer
x
y
end
subgraph hidden layer
a
b
c
d
end
subgraph output layer
u
end
```

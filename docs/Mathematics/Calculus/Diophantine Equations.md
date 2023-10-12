---
layout: default
title: Home
---

# Diophantine Equations

**Example:**
Solve $7x+5y+1=0$ with the aid of GCD and diophantane equation method?

**Solution:**
$$
\begin{align}
   &7 \mod{5} = 2 \quad \rightarrow 2 = (7) -1(5) \tag{1} \\
   &5 \mod{2} = 1 \quad \rightarrow 1 = (5) -2(2) \tag{2} \\
   &2 \mod{1} = 0 \tag{3}
   \end{align}
$$

We start with equation(2) since it is one step higher than the step we reached zero.
Our goal is to achieve: $7x-5y=-1$

Plug equation(1) in the place of (2) in eq.2 and simplify and make it look like $(7)x+(5)y+1=0$

$$
\begin{align*}
	1 &= (5) - 2 \left[(7) -1(5) \right] \\
	1 &= (5) - 2(7) + 2(5) \\
	1 &= 3(5) - 2(7) \\
	-1 &= -3(5) + 2(7)\\
	 0 &= 2(7) + (- 3(5)) +1\\
	 &\boxed{x=2} \quad \boxed{y=-3}
\end{align*}
$$


**Example 2:**
Solve $47x+30y+1=0$ with the aid of GCD and diophantane equation method?

**Solution:**
$$
\begin{align}
   47 &\mod{30} = 17 &\rightarrow 17 &= (47) -1(30) \tag{4} \\
   30 &\mod{17} = 13 &\rightarrow 13 &= (30) -1(17) \tag{5} \\
   17 &\mod{13} = 4 &\rightarrow 4 &= (17) -1(13) \tag{6} \\
   13 &\mod{4} = 1 &\rightarrow 1 &= (13) -3(4)  \tag{7}\\
   4 &\mod{1} = 0 \tag{8}
\end{align}
$$

We start with (7) equation since it is one step higher than the step we reached zero.
Our goal is to achieve: $47x-30y+1=0$

Plug eq.5 and eq.6 and eq. 4 in corresponding places in eq.2 and simplify and make it look like $(47)x-(30)y+1=0$

$$
\begin{align*}
	1 &= (13) - 3(4)\\
	1 &= (30)-(17)-3 \left [ (17) - (13) \right ]\\
	1 &= (30)-(47)+(30)-3(17)-3(13)\\
	1 &= 2(30)-(47)-3 \left [ (47) - (30) \right ] +3 \left [ (30)-(17) \right ]\\
	1 &= 2(30)-(47)-3(47)+3(30)+3(30)-3(17)\\
	1 &= 2(30)-(47)-3(47)+3(30)+3(30)-3 \left [ (47) - (30)\right ]\\
	1 &= 2(30)-(47)-3(47)+3(30)+3(30)-3(47) + 3(30)\\
	1 &= 11(30) - 7(47)\\
	0 &= -7(47)+11(30)-1\\
	0 &= 7(47) - 11(3) + 1\\
	& \boxed{x=7} \quad \boxed{y=11}
\end{align*}
$$
---
layout: default
---

## Logarithm
Definition of $e$ is used to calculate derivation proofs of $lnx$ and $e^x$.
$$
\begin{align}
	\lim_{h \to 0}(1+h)^{1/h} = e \tag{1}\\
	\sum_{n=0}^\infty \frac{1}{n!} = e \tag{2}\\
	\lim_{n \to \infty}(1+\frac{1}{n})^n=e \tag{3}\\
	\log x=\int_1^x \frac{dt}{t} \tag{4}
\end{align}
$$

Most calculators can directly compute logs base 10 and the natural log. For any other base it is necessary to use the change of base formula:
$$
\begin{align}
\log_ba = \frac{lna}{lnb} = \frac{log_{10}a}{log_{10}b} \tag{5}
\end{align}
$$

### Proof of $e^ x$ derivative
$$
\begin{align*}
&\lim_{h \rightarrow 0} \frac{f(x+h)-f(x)}{h} \\
&\lim_{h \rightarrow 0} \frac{e^{x+h}-e^x}{h} \\
&\lim_{h \rightarrow 0} \frac{e^x (e^h-1)}{h} \\
&e^x \cdot \lim_{h \rightarrow 0} \frac{e^h-1}{h}
\end{align*}
$$
First prove that $\lim_{h\to 0}\frac{\ln(h+1)}{h}=1$. The switch of $\ln$, $\lim$ is possible because $f(x)=\ln x$, $x>0$ is continuous.

$\lim_{h\to 0}(1+h)^{\frac{1}{h}} = e \quad \text{by definition ref to (1)}$

$\lim_{h\to 0}\frac{ln(1+h)}{h}=\ln e = 1$

Now let $u=e^h-1$. We know $h\to 0\iff u\to 0$.

$$
\lim_{h\to 0}\frac{e^h-1}{h}=\lim_{u\to 0}\frac{u}{\ln(u+1)}=1
$$

### Proof of $lnx$ (lnx) derivative
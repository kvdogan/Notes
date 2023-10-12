# Reference Cheat sheet

### Vectors & Matrix Cheat sheet
![[Vector CheatSheet.pdf]]



# Vector properties
**Reference vectors as follows:**
$$
\vec{a} = \begin{bmatrix} a_1 \\ \vdots \\ a_n \end{bmatrix} \quad
\vec{b} = \begin{bmatrix} b_1 \\ \vdots \\ b_n \end{bmatrix}
$$

## 1. Summation  
$\vec{a}+\vec{b}=\begin{bmatrix} a_1+b_1 \\ \vdots \\ a_n+b_n \end{bmatrix}$

## 2. Scalar Multiplication  
$c.\vec{a}=\begin{bmatrix} c.a_1 \\ \vdots \\ c.a_n \end{bmatrix}$

## 3. Dot Product  
$\vec{a}.\vec{b}=\underbrace{a_1b_1+\dots+a_nb_n}_{scalar}$

## 4. Length(Norm)  
$\|\vec{a}\| = \sqrt{a_1^2+\dots+a_n^2}$
$= \sqrt{\underbrace{\vec{a}.\vec{a}}_{\text{inner product}}}$
$= \sqrt{\underbrace{\vec{a}^T.\vec{a}}_{\text{dot product}}}$

## 5. Cauchy-Schwarz Inequality  
While $\|\vec{a}.\vec{b}\| \neq 0:$  
$\|\vec{a}.\vec{b}\| \leq \|\vec{a} \|. \|\vec{b} \|$  
$\|\vec{a}.\vec{b}\| \leq \|\vec{a} \|. \|\vec{b} \| \Longleftrightarrow \vec{a} = c. \vec{b}$

## 6. Triangle Inequality  
$\|\vec{a}+\vec{b}\| \leq \|\vec{a} \|. \|\vec{b} \|$

## 7. Angle bw vectors  
|                    |                                                             |
|:------------------:|:-----------------------------------------------------------:|
| ![[Vectors-1.png]] |                $c^2=a^2+b^2-2ab\cos{\theta}$                |
|                    | $(\vec{a}.\vec{b})=\|\vec{a} \|. \|\vec{b} \|.\cos{\theta}$ |
|                    |  $\cos \frac{\pi}{2}=0 \text{ (perpendicular/orthogonal)}$  |
|                    |                $\cos0=1 \text{ (parallel)}$                 |

## 8. Cross Product  
$\vec{a}, \vec{b} \in \mathbb{R}^3$  
$a\times b = \begin{bmatrix} a_2b_3 - a_3b_2 \\ a_1b_3 - a_3b_1 \\ a_1b_2 - a_2b_1  \end{bmatrix}$<br><br>
|                    |                                                                                                 |
|:------------------:|:-----------------------------------------------------------------------------------------------:|
| ![[Vectors-2.png]] |                          $\vec{c}$ is orthogonal to $a$ and $b$, thus:                          |
|                    |                                     $\vec{a}. \vec{c} = 0$                                      |
|                    |                                     $\vec{b}. \vec{c} = 0$                                      |
|                    |               $\|\vec{a} \times \vec{b}\|=\|\vec{a} \|. \|\vec{b}\|.\sin{\theta}$               |
|                    | $\vec{a} \times (\vec{b} \times \vec{c}) = \vec{b}(\vec{a}.\vec{c}) - \vec{c}(\vec{a}.\vec{b})$ |

# Eigenvalues and eigen vectors

https://learning.edx.org/course/course-v1:MITx+18.6501x+2T2022/block-v1:MITx+18.6501x+2T2022+type@sequential+block@prob_linalg_diag/block-v1:MITx+18.6501x+2T2022+type@vertical+block@prob_linalg_diag-tab11


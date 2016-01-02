# Tomita-Takesaki Theory and Holevo's super operator


 Masaki Sohma

## 1. Preliminaries
### 1.1 Banach space and Hilbert space
 Let $X$ be a complex vector space.
If  a non-negative real number $\parallel x\parallel$ is defined for
any element $x$ of $X$ and the following conditions are satisfied,
we call $\parallel \cdot \parallel$ a norm and $X$ a normed space.

1) $\parallel x\parallel =0\Leftrightarrow x=0$

2) $\parallel x+y \parallel\leq \parallel x\parallel +\parallel y\parallel,\quad x,y\in X$

3) $\parallel \alpha x\parallel \leq |\alpha| \parallel x \parallel,\quad x\in X, \alpha \in \mathbb{C}$

#### 1.1.1 Banach space
#### 1.1.2  Hilbert space
#### 1.1.3  Operator on Hilbert space

### 1.2 Operator Algebras
#### 1.2.1 *-algebras
Let $\mathfrak{A}$ be a linear associative operator over a complex numbers. If there is an involution $\mathfrak{A}\ni A\to A^*\in \mathfrak{A}$ such that $(A^*)^*=A$,$(AB)^*=B^*A^*$,$(\alpha A+\beta B)^*=\bar{\alpha}A^*+\bar{\beta}B^*$,$B\in\mathfrak{A},\alpha,\beta\in \mathbb{C}$,
we call $\mathfrak{A}$ a *-algebra.
And a *-albebra $\mathfrak{A}$ with an identity $I$ is called a unital *-algebra.
For the unital *-algebra $\mathfrak{A}$,  a linear functional $\omega:\mathfrak{A}\to \mathbb{C}$ satisfying  $\omega (A^{ * } A)\geq 0$ , $\forall A\in \mathfrak{A}$ and $\omega(I)=1$ is called a **state**.

#### 1.2.2 C*-algebras
#### 1.2.3 von Neumann algebras
#### 1.2.5 GNS construction for full matrix algebras
A full matrix algebra
$$
\mathfrak{M}=M_n(\mathbb{C})
$$
gives a simple example of von Neumann algebra.
Using the trace on $\mathfrak{M}$, we can define a tracial state,
$$
\tau(A)=\mbox{Tr}A/n.
$$
For $A=(a_{ij})$ we have $\tau(A^* A)=\sum_{ij}| a_{ij} |^2$, which means
that $\tau(A^* A)=0\Leftrightarrow A=0$, i.e. $\tau$ is faithful.
Hence we have an inner product $\langle A,B \rangle_\tau=\tau(A^* B)$ and we can regard $\mathfrak{M}$ as a Hilbert space and denote it by  $\mathfrak{H}_\tau$.

Let us consider  the map
$$
\pi:\mathfrak{M}\to\mathfrak{B}(\mathfrak{H}_\tau),
$$  
where $\pi(A)$ is a bounded operator given by $\pi(A)B=AB$ and this gives a GNS representation of $\mathfrak{M}$ on the Hilbert space $\mathfrak{H}_\tau=\mathfrak{M}$. For simplicity we deal with the case of $n=2$ for a while. Then $\mathfrak{H}_\tau$ has a orthonormal basis,
$$
E_{11}=
\begin{pmatrix}
\sqrt{n}&0\\
0&0
\end{pmatrix},
E_{12}=
\begin{pmatrix}
0&\sqrt{n}\\
0&0
\end{pmatrix},
$$
$$
E_{21}=
\begin{pmatrix}
0&0\\
\sqrt{n}&0
\end{pmatrix},
E_{22}=
\begin{pmatrix}
0&0\\
0&\sqrt{n}
\end{pmatrix},
$$
by which a matrix
$$
A=
\begin{pmatrix}
a&b\\
c&d
\end{pmatrix}\in \mathfrak{H}_\tau
$$
can be represented as
$$
A=\frac{1}{\sqrt{n}}(aE_{11}+bE_{12}+cE_{21}+dE_{22}),
$$
and $\mathfrak{B}(\mathfrak{M})=M_4(\mathbb{C})\backsimeq M_2(\mathbb{C})\otimes M_2(\mathbb{C})$.
From
$$
\begin{split}
(\pi(A)E_{11},...,\pi(A)E_{22})&=(AE_{11},....,AE_{22})\\
&=(E_{11},....,E_{22})
\begin{pmatrix}
aI_2 &bI_2  \\
cI_2 &dI_2
\end{pmatrix}
\end{split}
$$
we can find that a matrix representation of $\pi(A)$ is
given by $A\otimes I_2$. It is easy to see that
$$
\pi(A)^*=\pi(A^*)=A^*\otimes I_2.
$$
We are interested in von Neumann algebra $\pi(\mathfrak{M})=\mathfrak{M}\otimes I_2$ in $M_4(\mathbb{C})$.
Let us obtain the commutant
$$
\pi(\mathfrak{M})^{\prime}=\{X\in M_4(\mathbb{C}); YX=XY, \forall Y\in \pi(\mathfrak{M})\}.
$$
We assume that $X\in M_4(\mathbb{C})$
commutes with any elements of $\pi(\mathfrak{M})$.
Taking into account that
any elements of $M_4(\mathbb{C})$ has a form as
$$
X=X_{11}\otimes E_{11}+X_{12}\otimes E_{12}+X_{21}\otimes E_{21}+X_{22}\otimes E_{22},
$$
we have
$$
\sum_{i,j=1}^2(X_{ij}A-AX_{ij})\otimes E_{ij}=0.
$$
This means that
$$
X_{ij}A-AX_{ij}=0, \forall A\in \mathfrak{M}
$$
holds for any integer $1\leq i,j\leq 2$,that is,
$X_{ij}=kI$.
Thus we find that
$$
\pi(\mathfrak{M})^\prime=I_2\otimes \mathfrak{M}.
$$
We can also consider another representation
$$
\tilde{\pi}:\mathfrak{M}\to \mathfrak{B}(\mathfrak{H}_\tau),
$$
where $\tilde{\pi}$ is given by
$$
\tilde{\pi}(A)B=BA^T.
$$
Then we have
$$
\begin{split}
(\tilde{\pi}(A)E_{11},...,\tilde{\pi}(A)E_{22})&=(E_{11}A^T,....,E_{22}A^T)\\
&=(E_{11},...,E_{22})
\begin{pmatrix}
a&b&0&0\\
c&d&0&0\\
0&0&a&b\\
0&0&c&d
\end{pmatrix}\\
&=(E_{11},...,E_{22})(I_2\otimes A),
\end{split}
$$
This means that action of $\pi(\mathfrak{M})^{\prime}$  on $\mathfrak{H}_\tau$ is represented
by $\tilde{\pi}$ using $A\in\mathfrak{M}$ and that 
$$
\pi(\mathfrak{M})^{\prime}H^{1/2}=\{\tilde{\pi}(A)H^{1/2};A\in \mathfrak{M}\}=\{H^{1/2}A^T;A\in \mathfrak{M}\}.
$$
Note that
$$
\tilde{\pi}(A)^*=\tilde{\pi}(A^*),\quad
\tilde{\pi}(A^*)B=B(A^T)^*.
$$

### 1.3 Topology on $\mathfrak{B}(\mathfrak{H})$
#### 1.3.1 Net
#### 1.3.2 Locally Convex Topology
#### 1.3.3 Seven topologies on $\mathfrak{B}(\mathfrak{H})$

### 1.4 Involutive Antilinear operators
In Sec. 2 we must deal with antilinear $S$ on a Hilbert space $\mathfrak{H}$ ,

$$
S(\lambda \xi +\mu \eta)=\bar{\lambda}S\xi+\bar{\mu}S\eta.
$$



We can easily work with the antilinear operator by considering it as a real linear operator on $\mathfrak{H}_\mathbb{R}$.
test




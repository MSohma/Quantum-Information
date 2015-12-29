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



## 2. Tomita-Takesaki Theory

### 2.1 Modular Operator
Let $\mathfrak{N}\subset \mathfrak{B}(\mathfrak{H})$ be a von Neumann algebras, $\xi\in\mathfrak{H}$ a cyclic and separating vector vector for $\mathfrak{N}$.
Then $\xi$ is also cyclic and separating for  combatant of $\mathfrak{N}$, $\mathfrak{N}'$.
Here we consider anti-linear operators
$$
S_0 : \mathfrak{N} \xi \ni A\xi \longrightarrow A^*\xi \in \mathfrak{N}\tag{1.1}
$$
$$
F_0 : \mathfrak{N}' \xi \ni B\xi  \longrightarrow B^*\xi \in \mathfrak{N}',\tag{1.2}
$$
which are closable operators.
In fact, if $A\in \mathfrak{N},B\in\mathfrak{B}'$, we have
$$
\begin{split}
(B\xi,S_0A\xi)&=(B\xi,A^* \xi)=(AB\xi,\xi)=(BA\xi,\xi) \\
 &=(A\xi,B^* \xi)=(A\xi,F_0B\xi).
\end{split}\tag{1.3}
$$
This means $S_0^* \supset F_0$ and hence the domain of $S_0$ is dense in $\mathfrak{H}$.
In the following we call $F:=S_0^*$ the adjoint of $S_0$ and
$$
\Delta:=FS\tag{1.4}
$$
the modular operator, which is non singular and positive.

###  2.2 Tomita-Takesaki Theory for finite dimensional von Neumann algebras
In this sebsection we prove the Tomita-Takesaki theorem for finite dimensional
von Neumann algebras.
The Wedderburn theorem states that a finite dimensional $C*$ algebra is  *-isomorphic to a direct sum of simple matrix algebras. That is, there exists *-isomorphic function $\varphi$ for von Neumann algebra $\mathfrak{M}$ such that
$$
\varphi:\mathfrak{M}\simeq M(m_1,\mathbb{C})\otimes \cdots \otimes M(m_n,\mathbb{C}).
$$
Then we can define a faithful tracial state as
$$
A\in \mathfrak{M},\tau(A) = {\rm Tr}\varphi (A) /m,\quad m=m_1+\cdots + m_n.
$$
Here let us remember that any state $\omega$ on von Neumann algebras $\mathfrak{M}$ has a positive operator $H\in \mathfrak{M}$ such that
$$
\omega(A)=\tau(AH)=\tau(H^{1/2}AH^{1/2}), A\in \mathfrak{M},\tag{1.7}
$$
where $H$ is invertible iff $\omega$ is faithful.

Let us consider GNS representation $\pi:\mathfrak{M}\to \mathfrak{B}(\mathfrak{H}_\tau)$ given by a faithful tracial state $\tau$, a faithful state $\omega$ and invertical positive operator $H$ given by (1.7).
Here from the definition of GNS representation we have
$\mathfrak{H}_\tau=\mathfrak{M},\pi(A)B=AB,A,B\in \mathfrak{N}$ and the inner product of $\mathfrak{H}_\tau$ is given by
$$
\langle A,B \rangle_\tau=\tau(A^*B).\tag{1.8}
$$
Using such derived representation and inner product $\langle \cdot,\cdot\rangle_\tau$ we can represent the state $\omega$ as
$$
\omega(A)=\langle H^{1/2},\pi(A)H^{1/2}\rangle_\tau,\tag{1.9}
$$
where $H^{1/2}$ is a cyclic and separating vector of $\pi(\mathfrak{M})$.
Then the modular operator $\Delta$ defined by (1.4) is given as
$$
\Delta:A\in \mathfrak{H}_\tau\to HAH^{-1}\in \mathfrak{H}_\tau.\tag{1.10}
$$
In fact, $H^{1/2}\in GL_n(\mathbb{C})$
is a cyclic and separating vector for
$\pi(\mathfrak{M})$ and  the^*
anti-linear operator
$$
S_0:\pi(A)H^{1/2}\to \pi(A)^*H^{1/2},
$$
is given as
$$
S_0:AH^{1/2}\to A^*H^{1/2}.
$$

Putting $X=AH^{1/2}$, we have $A=XH^{-1/2}$, $A^*=H^{-1/2}X^*$
and hence
$$
S_0X=H^{-1/2}X^*H^{1/2}.
$$
On the other hand, the anti linear operator
$$
F_0:\tilde{\pi}(A)H^{1/2}\to \tilde{\pi}(A)^*H^{1/2}
$$
is given as
$$
F_0:H^{1/2}A^T\to H^{1/2}(A^T)^*
$$
Putting $X=H^{1/2}A^T$, we have $A^T=H^{-1/2}X$, $(A^T)^*=X^*H^{-1/2}$ and hence
$$
F_0X=H^{1/2}X^*H^{-1/2}.
$$
Thus 
$$
\begin{split}
\Delta X&=F_0S_0X=F_0(H^{-1/2}X^*H^{1/2})\\
&=H^{1/2}H^{1/2}XH^{-1/2}H^{-1/2}=HXH^{-1}.
\end{split}
$$


It follows from this equation that
$$
\Delta^{-it}\pi(A)\Delta^{it}=\pi(H^{-it}AH^{it}),\quad t \in \mathbb{R},
$$
that is,
$$
\Delta^{-it}\pi(\mathfrak{N})\Delta^{it}=\pi(\mathfrak{N}),\quad t \in \mathbb{R}.
$$

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
A full matrix algebra $\mathfrak{M}=M_n(\mathbb{C})$ gives a simple example of von Neumann algebra.
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
\end{pmatrix}
$$
can be represented as
$$
A=\frac{1}{\sqrt{n}}(aE_{11}+bE_{12}+cE_{21}+dE_{22}).
$$
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
given by $A\otimes I_2$. It is easy to see
$$
\pi(A)^*=\pi(A^*)=A^*\otimes I_2.
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
The Wedderburn theorem states that a finite dimensional $C*$ algebra is  *-isomorphic to a direct sum of simple matrix algebras. That is, there exists *-isomorphic function $\varphi$ for von Neumann algebra $\mathfrak{N}$ such that
$$
\varphi:\mathfrak{N}\simeq M(m_1,\mathbb{C})\otimes \cdots \otimes M(m_n,\mathbb{C}).
$$
Then we can define a faithful tracial state as
$$
A\in \mathfrak{N},\tau = {\rm Tr}\varphi (A) /m,\quad m=m_1+\cdots + m_n.
$$
Here let us remember that any state $\omega$ on von Neumann algebras $\mathfrak{N}$ has a positive operator $H\in \mathfrak{N}$ such that
$$
\omega(A)=\tau(AH)=\tau(H^{1/2}AH^{1/2}), A\in \mathfrak{N},\tag{1.7}
$$
where $H$ is invertible iff $\omega$ is faithful.

Let us consider GNS representation $\pi:\mathfrak{N}\to \mathfrak{B}(\mathfrak{H}_\tau)$ given by a faithful tracial state $\tau$, a faithful state $\omega$ and invertical positive operator $H$ given by (1.7).
Here from the definition of GNS representation we have
$\mathfrak{H}_\tau=\mathfrak{N},\pi(A)B=AB,A,B\in \mathfrak{N}$ and the inner product of $\mathfrak{H}_\tau$ is given by
$$
\langle A,B \rangle_\tau=\tau(A^*B).\tag{1.8}
$$
Using such derived representation and inner product $\langle \cdot,\cdot\rangle_\tau$ we can represent the state $\omega$
as
$$\
\omega(A)=\langle H^{1/2},\pi(A)H^{1/2}\rangle_\tau,\tag{1.9}
$$
where $H^{1/2}$ is a cyclic and separating vector of $\pi(\mathfrak{N})$.
Then the modular operator $\Delta$ defined by (1.4) is given as
$$
\Delta:A\in \mathfrak{H}_\tau\to HAH^{-1}\in \mathfrak{H}_\tau.\tag{1.10}
$$
It follows from this equation that
$$
\Delta^{-it}\pi(A)\Delta^{it}=\pi(H^{-it}AH^{it}),\quad t \in \mathbb{R},
$$
that is,
$$
\Delta^{-it}\pi(\mathfrak{N})\Delta^{it}=\pi(\mathfrak{N}),\quad t \in \mathbb{R}.
$$

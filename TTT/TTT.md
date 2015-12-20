# Tomita-Takesaki Theory and Holevo's super operator


 Masaki Sohma

## 1. Preliminaries
### 1.1 Banach space and Hilbert space
 Let $X$ be a complex vector space. 
If  a non-negative real number $\parallel x\parallel $ is defined for 
any element $x$ of $X$ and the following conditions are satisfied,
we call $\parallel \cdot \parallel $ a norm and $X$ a normed space.
1) $\parallel x\parallel =0\Leftrightarrow x=0$
2) $\parallel x+y \parallel\leq \parallel x\parallel +\parallel y\parallel,\quad x,y\in X$
3) $\parallel \alpha x\parallel \leq |\alpha| \parallel x \parallel,\quad x\in X, \alpha \in \mathbb{C}$
 
#### 1.1.1 Banach space
#### 1.1.2  Hilbert space
#### 1.1.3  Operator on Hilbert space

### 1.2 Examples of operator algebras
#### 1.2.1 Definition of *-algebras
#### 1.2.2 Definition of C*-algebras
#### 1.2.3 Definition of von Neumann algebras
#### 1.2.4 State
### 1.3 Topology on $\mathfrak{B}(\mathfrak{H})$
#### 1.3.1 Net
#### 1.3.2 Locally Convex Topology
#### 1.3.3 Seven topologies on $\mathfrak{B}(\mathfrak{H})$

### 1.4 Involutive Antilinear operators
In Sec. 2 we must deal with antilinear $S$ on a Hilbert space $\mathfrak{H}$,
$$
S(\lambda \xi +\mu \eta)=\bar{\lambda}S\xi+\bar{\mu}S\eta.
$$
We can easily work with the antilinear operator by considering it as a real linear operator on $\mathfrak{H}_\mathbb{R}$.



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

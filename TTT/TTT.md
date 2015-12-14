# Tomita-Takesaki Theory and Holevo's super operator


 Masaki Sohma

## 1. Preliminaries
### 1.1 Banach space and Hilbert space
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
\begin{split}
S_0 &: \mathfrak{N} \xi \ni A\xi \longrightarrow A^*\xi \in \mathfrak{N}\\
F_0 &: \mathfrak{N}' \xi \ni B\xi  \longrightarrow B^*\xi \in \mathfrak{N}',
\end{split}
$$
which are closable operators.
In fact, if $A\in \mathfrak{N},B\in\mathfrak{B}'$, we have
$$
\begin{split}
(B\xi,S_0A\xi)&=(B\xi,A^* \xi)=(AB\xi,\xi)=(BA\xi,\xi)\\
 &=(A\xi,B^* \xi)=(A\xi,F_0B\xi).
\end{split}
$$
This means $S_0^* \supset F_0$ and hence the domain of $S_0$ is dense in $\mathfrak{H}$.
In the following we call $F:=S_0^*$ the adjoint of $S_0$ and
$$
\Delta:=FS
$$
the modular operator, which is non singular and positive.

###  2.2 Tomita-Takesaki Theory for finite dimensional von Neumann algebras

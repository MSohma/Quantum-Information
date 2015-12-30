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

### 2.3 Matrix representation of modular operator 
Let us consider the case $\mathfrak{M}=M_2(\mathbb{C})$ with the basis $\{E_{ij}\}$  and a positive operator $H$ as in Sec. 1.2.5. 
In this section we consider $\mathfrak{M}$ as a $8$-dimensional real vector space. Then we take a new basis 
$$
\{ U^* E_{kl}U,U^* \tilde{E}_{kl}U; k,l=1,2 \},
$$
where $\tilde{E}_{kl}=iE_{kl}$.

<h3> 2.2 Tomita-Takesaki Theory for finite dimensional von Neumann algebras </h3>

In this sebsection we prove the Tomita-Takesaki theorem for finite dimensional
von Neumann algebras.
The Wedderburn theorem states that a finite dimensional $C^{\ast}$ algebra is  $\ast$-isomorphic to a direct sum of simple matrix algebras. That is, there exists $\ast$-isomorphic function $\varphi$ for von Neumann algebra $\mathfrak{N}$ such that
$$
\varphi:\mathfrak{N}\simeq \mathfrak{M}:=M(m_1,\mathbb{C})\otimes \cdots \otimes M(m_n,\mathbb{C}).
$$
Then we can define a faithful tracial state as
$$
A\in \mathfrak{M},\tau(A) = {\rm Tr}A /m,\quad m=m_1+\cdots + m_n.
$$
Here let us remember that any state $\omega$ on von Neumann algebras $\mathfrak{M}$ has a positive operator $H\in \mathfrak{M}$ such that
$$
\omega(A)=\tau(AH)=\tau(H^{1/2}AH^{1/2}), A\in \mathfrak{M},\tag{2.2.1}
$$
where $H$ is invertible iff $\omega$ is faithful.

Let us consider GNS representation $\pi:\mathfrak{M}\to \mathfrak{B}(\mathfrak{H}_\tau)$ given by a faithful tracial state $\tau$.
Here from the definition of GNS representation we have
$\mathfrak{H}_\tau=\mathfrak{M},\pi(A)B=AB,A,B\in \mathfrak{M}$ and the inner product of $\mathfrak{H}_\tau$ is given by
$$
\langle A,B \rangle_\tau=\tau(A^*B).\tag{2.2.2}
$$
Using such derived representation and inner product $\langle \cdot,\cdot\rangle_\tau$ we can represent the state $\omega$ as
$$
\omega(A)=\tau(H^{1/2}AH^{1/2})=\langle H^{1/2},\pi(A)H^{1/2}\rangle_\tau,\tag{2.2.3}
$$
where $H^{1/2}$ is a cyclic and separating vector of $\pi(\mathfrak{M})$.
Then  the
anti-linear operator $S_{0,\tau}$ is defined as
$$
S_{0,\tau}:\pi(A)H^{1/2}\to \pi(A)^*H^{1/2}.
$$
Putting $X=\pi(A)H^{1/2}=AH^{1/2}$, we have $A=XH^{-1/2}$, $A^*=H^{-1/2}X^*$
and hence
$$
S_{0,\tau}X=H^{-1/2}X^*H^{1/2}.
$$
On the other hand, the anti linear operator $F_{0,\tau}$ is defined as
$$
F_{0,\tau}:\tilde{\pi}(A)H^{1/2}\to \tilde{\pi}(A)^*H^{1/2},
$$
which can be written as
$$
F_{0,\tau}:H^{1/2}A^T\to H^{1/2}(A^T)^*
$$
Putting $X=H^{1/2}A^T$, we have $A^T=H^{-1/2}X$, $(A^T)^*=X^*H^{-1/2}$ and hence
$$
F_0X=H^{1/2}X^*H^{-1/2}.
$$
Thus we find that $\Delta_\tau=F_{0,\tau}S_{0,\tau}$
is given as
$$
\begin{split}
\Delta_\tau X&=F_{0,\tau}S_{0,\tau}X=F_{0,\tau}(H^{-1/2}X^*H^{1/2})\\
&=H^{1/2}H^{1/2}XH^{-1/2}H^{-1/2}=HXH^{-1}.
\end{split}
$$

It follows from this equation that
$$
\Delta_\tau ^{-it}\pi(A)\Delta_\tau ^{it}=\pi(H^{-it}AH^{it}),\quad t \in \mathbb{R},
$$
that is,
$$
\Delta_\tau ^{-it}\pi(\mathfrak{M})\Delta_\tau ^{it}=\pi(\mathfrak{M}),\quad t \in \mathbb{R} \tag{2.2.4}.
$$

Let us consider the state on $\mathfrak{N}$
$$
\omega_\xi(A)=(\xi,A\xi),\quad A\in \mathfrak{N},\xi\in \mathfrak{H}.
$$
Using this state we can define the state on $\mathfrak{M}$
$$
\omega(A)=\omega_\xi(\varphi^{-1}(A)),A\in \mathfrak{M}.
$$
Then we get
$$
\langle H^{1/2},\pi(A^* B)H^{1/2}\rangle_\tau=(\xi,\varphi^{-1}(A^* B)\xi),
$$
and hence
$$
\langle \pi(A)H^{1/2},\pi( B)H^{1/2}\rangle_\tau=(\varphi^{-1}(A)\xi,\varphi^{-1}(B)\xi),
$$
which means
$$
U:\mathfrak{H}_\tau\ni\pi(A)H^{1/2}\to \varphi^{-1}(A)\xi\in\mathfrak{H}, \quad A\in \mathfrak{M}
$$
gives a unitary operator from $\mathfrak{H}_\tau$ to $\mathfrak{H}$.
This unitary operator combines $\Delta$ and $\Delta_{\tau}$ as
$$
\Delta_\tau=U^{\ast}\Delta U,
$$
and gives the main result of Tomita-Takesaki Theory,
$$
\Delta^{-it}\mathfrak{N}\Delta^{it}=\mathfrak{N}.
$$

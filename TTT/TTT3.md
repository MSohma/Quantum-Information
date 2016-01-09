<h2> Hilbert space associated with a normal state</h2>

Let $\omega$ be a state on von Neumann algebra $\mathfrak{N}$.
Introduce a complex inner product on $\mathfrak{N}$,
$$
\mathfrak{a}(Y,X)=\omega(\frac{1}{2}(XY^\ast+Y^\ast X)),X,Y\in \mathfrak{N}.
$$
In contrast to the inner products
$$
\mathfrak{a}_+=\omega(XY^\ast),\quad\mathfrak{a}_-(Y,X)=\omega(Y^\ast X)
$$
used in Gel'fand-Naimark-Segal construction,
$\mathfrak{a}$ posseses the property that the
involution $X\to X^{\ast}$ is an anti-unitary operator with respect to to it, i.e.  
$$
\mathfrak{a}(Y^*,X^*)=\overline{\mathfrak{a}(Y,X)}.
$$


## Holevo's commutation operator

We call a operator satisfying the following equation a commutation operator.
$$
[A,X]=\langle A, \mathfrak{D}X\rangle, \quad A,X\in H
$$
$$
\begin{split}
[A,X]&=i\omega(A^\ast X-XA^\ast)=i\mbox{Tr}\rho(A^\ast X-XA^\ast)\\
     &=\mbox{Tr}A^\ast i(X\rho-\rho X)\\
\langle A,Y\rangle&=\omega((YA^\ast+A^\ast Y)/2)=\mbox{Tr}\rho((YA^\ast+A^\ast Y)/2)\\
&=\mbox{Tr}A^\ast(\rho Y+Y\rho)/2
\end{split}
$$
より、
$$
(\rho Y+Y\rho)/2=i(X\rho-\rho X)
$$

Putting $X=(x_{jk}),Y=\mathfrak{D}X=(y_{jk}),\rho=\mbox{diag}(s_1,s_2)$,
let us obtain matrix representation for the commutation operator 
  $$
  \begin{pmatrix}
  s_1y_{11}&\frac{s_1+s_2}{2}y_{12}\\
  \frac{s_1+s_2}{2}y_{21}&s_2y_{22}
  \end{pmatrix}
  =
  i \begin{pmatrix}
  0&(s_2-s_1)x_{12}\\
  (s_1-s_2)x_{21}&0
  \end{pmatrix}
  $$
  より
  $$
  \begin{pmatrix}
  y_{11}\\
  y_{12}\\
  y_{21}\\
  y_{22}
  \end{pmatrix}
  =
  \begin{pmatrix}
  0&0&0&0\\
  0&\frac{2i(s_2-s_1)}{s_1+s_2}&0&0\\
  0&0&\frac{2i(s_1-s_2)}{s_1+s_2}&0\\
  0&0&0&0
  \end{pmatrix}
  \begin{pmatrix}
  x_{11}\\
  x_{12}\\
  x_{21}\\
  x_{22}
  \end{pmatrix}
  $$
$$
\begin{split}
\left(1+\frac{i}{2}\mathfrak{D}\right)([x_{jk}])&=\left[\frac{2s_j}{s_j+s_k}x_{jk}\right]\\
\left(1-\frac{i}{2}\mathfrak{D}\right)([x_{jk}])&=\left[\frac{2s_k}{s_j+s_k}x_{jk}\right]\\
\left(1+\frac{1}{4}\mathfrak{D}^2\right)([x_{jk}])&=\left[\frac{4s_js_k}{(s_j+s_k)^2}x_{jk}\right]
\end{split}
$$


The elements of ${\cal L}^2_h(S)$ can be naturally identified with the equivalence classes of suquare-summable operators with the inner product
defined by
  $$
     \langle Y,X \rangle_S=\mbox{Re}\sum_{j}s_j\langle Y\psi_j|X\psi_j\rangle
  $$
  namely, if $\{X_n\}$ be a Cauchy sequences with respect to the pre-inner product
  $$
    \langle Y,X\rangle_S =\mbox{Re}\mbox{Tr}SYX,\quad  X,Y\in \mathfrak{B}_h(\mathfrak{H}),
  $$
  then there is  a square-summable operator $X$ such that $\lim_n\langle X_n-X,X_n-X\rangle =0$, and conversly any square-summable operator is a
  limit of a Cauchy sequence $\{X_n\}\subset \mathfrak{B}_h(\mathfrak{H})$.

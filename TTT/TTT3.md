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

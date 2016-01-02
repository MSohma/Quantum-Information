<h3> 2.3 Matrix representation of modular operator </h3>

Let us consider the case $\mathfrak{M}=M_2(\mathbb{C})$ with the basis $\{E_{ij}\}$  and a positive operator $H$ as in Sec. 1.2.5.
In this section we consider $\mathfrak{M}$ as a $8$-dimensional real vector space. Then we take a new basis
$$
\{ U^* E_{kl}U,U^* \tilde{E}_{kl}U; k,l=1,2 \},
$$
where $\tilde{E}_{kl}=iE_{kl}$.
Firstly, we will obtain the  matrix representation for a multiplication by i.
From
$$
\begin{split}
i(U^* E_{kl}U)&=U^* iE_{kl}U=U^* \tilde{E}_{kl}U\\
i(U^* \tilde{E}_{kl}U)&=U^* i\tilde{E}_{kl}U=-U^* E_{kl}U,
\end{split}
$$
we have
$$
\begin{split}
(iU^* E_{11}U &, iU^* \tilde{E}_{11}U,....,iU^* E_{22}U,iU^* \tilde{E}_{22}U)\\
=&(U^* E_{11}U,...,U^*\tilde{E}_{22}U)
\begin{pmatrix}
J_2&0&0&0\\
0&J_2&0&0\\
0&0&J_2&0\\
0&0&0&J_2
\end{pmatrix}
\end{split},
$$
with
$$
J_2=
\begin{pmatrix}
0&-1\\
1&0
\end{pmatrix}.
$$
This indicates matrix representation for a multiplication by i is given by
$I_4\otimes J_2$.

Secondly we will obtain the matrix representation of $S_0$, which is given as $S_0X=H^{-1/2}X^*H^{1/2}$.
Since $H$ is a positive operator,
$$
H^{1/2}=U^*
\begin{pmatrix}
\sqrt{\lambda_1}&0\\
0&\sqrt{\lambda_2}
\end{pmatrix}
U,
$$
with ${\lambda_1},{\lambda_2}\geq 0$ and a unitary operator $U$.
Hence we get
$$
U(S_0 X)U^* =
\begin{pmatrix}
\sqrt{\lambda_1}^{-1}&0\\
0&\sqrt{\lambda_2}^{-1}
\end{pmatrix}
(UXU^*)^*
\begin{pmatrix}
\sqrt{\lambda_1}&0\\
0&\sqrt{\lambda_2}
\end{pmatrix}.
$$
Now we consider a basis
$$
\{U^* E_{kl} U,U^* \tilde{E}_{kl} U; k,l=1,2\}.
$$
Then
$$
\begin{split}
S_0U^* E_{11}U&=
U^*
\begin{pmatrix}
\sqrt{\lambda_1}^{-1}&0\\
0&\sqrt{\lambda_2}^{-1}
\end{pmatrix}
\begin{pmatrix}
1&0\\
0&0
\end{pmatrix}
\begin{pmatrix}
\sqrt{\lambda_1}&0\\
0&\sqrt{\lambda_2}
\end{pmatrix}
U\\
&=U^* E_{11}U.
\end{split}
$$
In a similar manner, we have
$$
\begin{split}
S_0U^*\tilde{E}_{11}U&=-U^*\tilde{E}_{11}U\\
S_0U^*{E}_{12}U&=\sqrt{\lambda_1\lambda_2^{-1}}U^*{E}_{21}U\\
S_0U^*\tilde{E}_{12}U&=-\sqrt{\lambda_1\lambda_2^{-1}}U^*\tilde{E}_{21}U\\
S_0U^*{E}_{21}U&=\sqrt{\lambda_1^{-1}\lambda_2}U^*{E}_{12}U\\
S_0U^*\tilde{E}_{21}U&=-\sqrt{\lambda_1^{-1}\lambda_2}U^*\tilde{E}_{12}U\\
S_0U^* {E}_{22}U&=U^* {E}_{22}U\\
S_0U^*\tilde{E}_{22}U&=-U^*\tilde{E}_{22}U.
\end{split}
$$
Thus we find the matrix representation of $S_0$ as
$$
\begin{pmatrix}
1&0&0&0&0&0&0&0\\
0&-1&0&0&0&0&0&0\\
0&0&0&0&\sqrt{\lambda_1^{-1}\lambda_2}&0&0&0\\
0&0&0&0&0&-\sqrt{\lambda_1^{-1}\lambda_2}&0&0\\
0&0&\sqrt{\lambda_1\lambda_2^{-1}}&0&0&0&0&0\\
0&0&0&-\sqrt{\lambda_1\lambda_2^{-1}}&0&0&0&0\\
0&0&0&0&0&0&1&0\\
0&0&0&0&0&0&0&-1
\end{pmatrix},
$$
which can be also written as
$$
A_{S_0}\otimes J^{\prime}_2,
$$
with
$$
\begin{split}
A_{S_0}&=
\begin{pmatrix}
1&0&0&0\\
0&0&\sqrt{\lambda_1^{-1}\lambda_2}&0\\
0&\sqrt{\lambda_1\lambda_2^{-1}}&0&0\\
0&0&0&1
\end{pmatrix},\\
J^{\prime}_2&=
\begin{pmatrix}
1&0\\
0&-1
\end{pmatrix}.
\end{split}
$$
Remark that $(A_{S_0}\otimes J^{\prime}_2)(I_4\otimes J_2)=-(I_4\otimes J_2)(A_{S_0}\otimes J^{\prime}_2)$
means anti-linearity of $S_0$, i.e. $S_0i=-iS_0$.
In a similar manner we can obtain
the matrix representation of $F_0$ as
$$
A_{F_0}\otimes J^{\prime}_2,
$$
with
$$
\begin{split}
A_{F_0}&=
\begin{pmatrix}
1&0&0&0\\
0&0&\sqrt{\lambda_1\lambda_2^{-1}}&0\\
0&\sqrt{\lambda_1^{-1}\lambda_2}&0&0\\
0&0&0&1
\end{pmatrix},\\
J^{\prime}_2&=
\begin{pmatrix}
1&0\\
0&-1
\end{pmatrix}.
\end{split}
$$
Finally we obtain the matrix representation
of $\Delta=F_0S_0$ as
$$
(A_{F_0}\otimes J_2)(A_{S_0}\otimes J_2)=
A_{F_0}A_{S_0}\otimes J_2^2
=A_{\Delta}\otimes I_2,
$$
with
$$
A_{\Delta}=
\begin{pmatrix}
1&0&0&0\\
0&{\lambda_1\lambda_2^{-1}}&0&0\\
0&0&{\lambda_1^{-1}\lambda_2}&0\\
0&0&0&1
\end{pmatrix},
$$
which gives a complex matrix representation of $\Delta$.
From this we can define $\Delta^{it}$
through the complex matrix representation as
$$
\Delta^{it}\Leftrightarrow
A_{\Delta^{it}}=
\begin{pmatrix}
1&0&0&0\\
0&(\lambda_1\lambda_2^{-1})^{it}&0&0\\
0&0&(\lambda_1^{-1}\lambda_2)^{it}&0\\
0&0&0&1
\end{pmatrix}.
$$
On the other hand the complex matrix representation for $X\to H^{it}XH^{-it}$
is
$$
\begin{pmatrix}
1&0&0&0\\
0&\lambda_1^{it}(\lambda_2^{it})^{-1}&0&0\\
0&0&(\lambda_1^{it})^{-1}\lambda_2^{it}&0\\
0&0&0&1
\end{pmatrix},
$$
and hence we have
$$
\Delta^{it}X=H^{it}XH^{-it}.
$$
Now we can easily show the following relation.
$$
\Delta^{-it}\pi(A)\Delta^{it} =\pi(H^{-it}AH^{it}).
$$
In fact,
since $\pi(A)B=AB$,
$$
\begin{split}
\Delta^{-it}\pi(A)\Delta^{it}B&=\Delta^{-it}\pi(A)(H^{it}BH^{-it})\\
&=\Delta^{-it}(AH^{it}BH^{-it})\\
&=H^{-it}AH^{it}BH^{-it}H^{it}\\
&=H^{-it}AH^{it}B=\pi(H^{-it}AH^{it})B.
\end{split}
$$

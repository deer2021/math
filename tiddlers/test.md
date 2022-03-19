
a
由于函数 
$f(x)$ 
与 $x^n$ 均在 $[0,1]$ 连续可微,由分部积分公式有
$$
\int_{0}^{1} x^{n} f(x) \mathrm{d} x=\int_{0}^{1} f(x) \mathrm{d}\left(\frac{x^{n+1}}{n+1}\right)=\left.\frac{x^{n+1} f(x)}{n+1}\right|_{0} ^{1}-\int_{0}^{1} \frac{x^{n+1} f^{\prime}(x)}{n+1} \mathrm{~d} x
$$
由于函数 $x^{n+1}$ 在 $[0,1]$ 连续且不变号, $f'(x)$ 在 $[0,1]$ 连续,由广义积分中值定理,存在 $\xi\in(0,1)$, 使得
$$
\int_{0}^{1} \frac{x^{n+1} f^{\prime}(x)}{n+1} \mathrm{~d} x=f^{\prime}(\xi) \int_{0}^{1} \frac{x^{n+1}}{n+1} \mathrm{~d} x=\frac{f^{\prime}(\xi)}{(n+1)(n+2)}
$$
于是
$$
n \int_{0}^{1} x^{n} f(x) \mathrm{d} x=\frac{n f(1)}{n+1}+\frac{n f^{\prime}(\xi)}{(n+1)(n+2)}
$$
因 $f'(x)$ 在 $[0,1]$ 连续,从而在 $[0,1]$ 有界,所以
$$
\lim _{n \rightarrow \infty} \frac{n f^{\prime}(\xi)}{(n+1)(n+2)}=0
$$
故
$$
\lim _{n \rightarrow \infty} n \int_{0}^{1} x^{n} f(x) \mathrm{d} x=f(1)
$$
$\square$

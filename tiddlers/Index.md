<head>
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>
设  $f(x)$ 在 $[0,\pi]$ 上连续,在 $(0,\pi)$ 内可导 ,且
$$
\int_0^\pi f(x)\cos x \,\mathrm dx=\int_0^\pi f(x)\sin x \,\mathrm dx=0
$$
求证：存在 $\xi\in(0,\pi)$ 使得 $f'(\xi)=0$ .

**Solution:**

因为在 $(0,\pi)$ 内 $\sin x > 0$ .所以条件
$$
\displaystyle\int_0^\pi f(x)\sin x \,\mathrm dx=0
$$
意味着 $f(x)$ 在 $(0,\pi)$ 内不可能恒正或恒负,因而必有零点.再证 $f(x)$ 在 $(0,\pi)$ 内的零 点不止一个.用反证法证 明之. 设 $a\in(0,\pi)$ 是 $f(x)$ 的唯一零点,则由零点存在定理知 $f(x)\sin(x-a)$ 恒正或恒负(除 $x=a$ 点),从而
$$
\int_0^\pi f(x)\sin(x-a)\,\mathrm dx\ne 0
$$
但由假设条件
$$
\int_0^\pi f(x)\sin(x-a)\,\mathrm dx=\cos a\int_0^\pi f(x)\sin x\,\mathrm dx-\sin a\int_0^\pi f(x)\cos x\,\mathrm dx=0
$$
这一矛盾表明, $f(x)$ 在 $(0,\pi)$ 内的零点不止一个.于是由罗尔定理推出 $f'(x)$ 在 $(0,\pi)$ 内有零点.













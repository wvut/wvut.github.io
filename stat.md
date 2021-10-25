<script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

$$
    σ_x^2 = \overline{x^2} - \overline{x}^2
$$
$$
    σ_{xy} = \overline{xy} - \overline{x} \overline{y}
$$

$$
    ε(a,b) := \sum_i (y_i - ax_i - b)
$$
が最小となるのは
$$
    \frac{∂ε}{∂a} = \frac{∂ε}{∂b} = 0
    \iff (a, b) = \left( \frac{σ_{xy}}{σ_x^2}, \overline{y} - a\overline{x} \right)
$$
のとき

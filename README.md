# 1,000 [業界研究](https://www.amazon.co.jp/dp/4492973303)

## 50 [製薬業界](https://www.amazon.co.jp/dp/4297121581)

特許が切れ（て再審査期間も終わ）るまでに、新薬をできるだけ販売することが重要。

- **研究職**：研究所で実験
  - **基礎研究**：2〜3年
  - **非臨床試験**：3〜5年
- **開発職**：本社でデスクワーク
  - **臨床試験**：3〜7年
  - **承認申請**：約1年<br>FDA（米食品医薬品局）、EMA（欧州医薬品庁）、PMDA（医薬品医療機器総合機構）と交渉
- **MR**（医薬情報担当者）：全国各地で営業
  - **販売**：8〜十数年<br>医師などを訪問

# 数学

## 80 [線形代数](https://www.amazon.co.jp/dp/441015463X)

$m×n$ 行列、型、$(i,j)$ 成分、$n$ 次正方行列、$n$ 次単位行列 $E_n$

- 行列 $A,B$ の型・成分が等しいとき、$A=B$ と定義する。
- $k[a_{ij}]:=k[a_{ij}]$
- 行列 $A,B$ の型が等しいとき、$[a_{ij}]+[b_{ij}]:=[a_{ij}+b_{ij}]$

行列 $[a_{ij}]$ の**列**数と 行列 $[b_{ij}]$ の**行**数が等しいとき、

$$
    \begin{bmatrix}
        a_{11} & \cdots & a_{1n} \\
        \vdots & & \vdots \\
        a_{l1} & \cdots & a_{ln} \\
    \end{bmatrix}
    \begin{bmatrix}
        b_{11} & \cdots & b_{1n} \\
        \vdots & & \vdots \\
        b_{m1} & \cdots & b_{mn} \\
    \end{bmatrix}
    :=
    \begin{bmatrix}
        \sum_{k=1}^m a_{1k}b_{k1} & \cdots & \sum_{k=1}^m a_{1k}b_{kn} \\
        \vdots & & \vdots \\
        \sum_{k=1}^m a_{lk}b_{k1} & \cdots & \sum_{k=1}^m a_{lk}b_{kn} \\
    \end{bmatrix}
$$

つまり、

$$
\sum_{k=1}^m a_{ik}b_{kj} = 
\begin{bmatrix}
    a_{i1} & \cdots & a_{im} \\
\end{bmatrix}
\begin{bmatrix}
    b_{1j} \\
    \vdots \\
    b_{nj} \\
\end{bmatrix}
$$

- 交換法則は一般には成り立たない。

基本行列とは、

- 行基本変形とは、$m×n$ 行列の**左**から $m$ 次基本行列を掛けること。

## 微積

- $y=f(x)$ が $x=a$ で微分可能なとき、$(a,f(a))$ における接線は $y = f'(a)(x-a)+f(a)$
- $(f(x)+g(x))' = f'(x)+g'(x)$
- $(cf(x))' = cf'(x)$
- $(f(x)g(x))' = f'(x)g(x)+f(x)g'(x)$
  - 証明には $\dfrac{f(x)g(x)-f(a)g(a)}{x-a} = \dfrac{f(x)-f(a)}{x-a} g(x) + f(a) \dfrac{g(x)-g(a)}{x-a}$ を用いる。
- $(x^n)' = nx^{n-1}　(n∈\mathbb{R})$


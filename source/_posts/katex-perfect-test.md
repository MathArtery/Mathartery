---
title: KaTeX完美测试 - 行列式完全支持
date: 2024-01-01
math: true
---

## 测试1：行内公式

勾股定理：$a^2 + b^2 = c^2$

二次方程求根：$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$

## 测试2：行列式（重点）

### 二阶行列式：
$$ \begin{vmatrix} a & b \\ c & d \end{vmatrix} = ad - bc $$

### 三阶行列式：
$$
\begin{vmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{vmatrix}
= 0
$$

### 范德蒙行列式：
$$
\begin{vmatrix}
1 & a & a^2 \\
1 & b & b^2 \\
1 & c & c^2
\end{vmatrix}
= (b-a)(c-a)(c-b)
$$

## 测试3：各种矩阵

圆括号矩阵：
$$ \begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix} $$

方括号矩阵：
$$ \begin{bmatrix} 1 & 2 \\ 3 & 4 \end{bmatrix} $$

行列式：
$$ \begin{vmatrix} 1 & 2 \\ 3 & 4 \end{vmatrix} $$

## 测试4：复杂公式

特征值：
$$
\det(A - \lambda I) =
\begin{vmatrix}
a_{11}-\lambda & a_{12} & a_{13} \\
a_{21} & a_{22}-\lambda & a_{23} \\
a_{31} & a_{32} & a_{33}-\lambda
\end{vmatrix} = 0
$$

积分：
$$ \int_{-\infty}^{\infty} e^{-x^2} dx = \sqrt{\pi} $$

级数：
$$ \sum_{n=1}^{\infty} \frac{1}{n^2} = \frac{\pi^2}{6} $$

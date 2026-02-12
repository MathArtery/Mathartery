---
title: 基于代数基本定理的一道夏令营数学选拔赛题的解法分析
date: 2026-02-17
tags:[代数基本定理, 中学数学, 因式分解法,韦达定理]
categories: 论文推荐
mathjax: true  
---
<p style="text-align: center;">
<span style="color:#9966CC">欢迎关注MathArtery，我们将以严谨的学术态度为您分享数学论文</span>
</p>
它将对整数性质、方程求解、组合优化等问题，以另一种方式简洁而严谨地求解——
题记
<!-- more -->
<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">论文第一页</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>

<img src="/Mathartery/source/tupian/2026-02-11 204533.png" alt="论文第一页" width="500">

  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">摘要</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>

<div style="width: 100%; padding: 20px; background-color: #f8f9fa; border-radius: 8px; border-left: 4px solid #9966CC; margin: 20px 0; line-height: 1.8; font-size: 16px;">
在高中数学里,三次函数的零点问题是重要的知识点,也是同学们的一个难点,这类题通常会涉及多项式的因式分解、导数的应用及值域的求解等,尤其是很多要用到数学中的代数基本定理(任何一元n(n∈N* )次复系数多项式方程f(x)=0至少有一个复数根).

2025年全国高中数学联赛浙江赛区夏令营选拔赛第7题,正是以三次函数恰有两个零点为条件,求系数组合b+c的取值范围,其理论根据正是代数基本定理.
<br><br>
  <strong>关键词：</strong>代数基本定理;中学数学;因式分解法;韦达定理
</div>

<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">推荐理由</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>

本文章主要聚焦于一道基于代数基本定理的数学选拔题，对题目里的三次函数零点个数的讨论,不仅依托于代数基本定理与多项式理论,更在与因式分解、导数应用、变量代换及函数值域分析等过程的交融中,展现出数学方法的深刻性与统一性.此外,借助图象直观进一步强化了对代数结论的几何理解,体现出数形结合思想的价值,有利于拓展学生对三次函数的零点问题的理解,提高数学素养.

<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">注解</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>
此定理及特殊的实系数一元三次方程根的情况,同学们可参考2019年版人教 A 版高中数学教材必修第二册习题7.2后面的“阅读与思考”栏目《代数基本定理》

<img src="/Mathartery/source/tupian/2026-02-11 214813.png" alt="《代数基本定理》" width="500">

欧拉公式（英语：Euler's formula，又称尤拉公式）是复分析领域的公式，它将三角函数与复指数函数关联起来，因其提出者莱昂哈德·欧拉而得名.欧拉公式提出，对于任意的实数$x$,都存在
$$e^{i x}=\cos{x}+i \sin{x}$$
其中$e$为自然对数的底数，$i$为虚数单位，$\sin$和$\cos$为正弦和余弦对应的三角函数，参数$x$以弧度为单位.

<img src="/Mathartery/source/tupian/untitled1.png" alt="欧拉公式" width="500">

简单证明：

把函数 \( e^x \)、\( \cos x \) 和 \( \sin x \) 写成在高中里我们略有耳闻的泰勒级数形式：
$$
e^x = 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + \cdots
$$
$$
\cos x = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \frac{x^6}{6!} + \cdots
$$
$$
\sin x = x - \frac{x^3}{3!} + \frac{x^5}{5!} - \frac{x^7}{7!} + \cdots
$$

将 $x = iz $ 代入$e^x$可得：
$$
\begin{aligned}
e^{iz} &= 1 + iz + \frac{(iz)^2}{2!} + \frac{(iz)^3}{3!} + \frac{(iz)^4}{4!} + \frac{(iz)^5}{5!} + \frac{(iz)^6}{6!} +  \cdots \\
&= 1 + iz - \frac{z^2}{2!} + \frac{iz^3}{3!} - \frac{z^4}{4!} + \frac{iz^5}{5!} - \frac{z^6}{6!} + \cdots \\
&= \left(1 - \frac{z^2}{2!} + \frac{z^4}{4!} - \frac{z^6}{6!} + \cdots\right) + i\left(z - \frac{z^3}{3!} + \frac{z^5}{5!} + \cdots\right) \\
&= \cos z + i \sin z
\end{aligned}
$$
虽然以上方法被广泛介绍，但由于在复数域中的泰勒级数展开、求导等运算均需要用到欧拉公式，造成循环论证，且有些方法在函数的定义域和性质上语焉不详，故以上方法仅仅是为方便快速理解，想要进一步了解严谨的证明方法，可查阅这个链接：
<a href="https://zh.wikipedia.org/wiki/%E6%AC%A7%E6%8B%89%E5%85%AC%E5%BC%8F#cite_note-1"  target="_blank">>欧拉公式证明
</a>


代数基本定理的最简单证明：

设  
$$
w(z) = z^n + a_{n-1}z^{n-1} + \ldots + a_0
$$
于是我们想要证明的结论就是：一定能找到某个$z$，使得$w(z)=0$.

我们先把$z$ 写成  
$$
z = re^{i\theta}
$$
的形式,形式与前面提到的欧拉公式相似，是复数的极坐标形式，$r$是指模长$|r|$,表示复数到原点的距离.我们前面的欧拉公式就是能表示模为1的复数.

首先，我们考虑$r=0$的情况，即$z$为$0$，这时多项式$w(0)$将是复平面上的一个点，并且这个点就是常数$a_0$，且$a_0$不等于$0$。但是如果 $a_0$等于0，显然，$z=0$就是原方程的解了，定理直接得证.

然后，我们再考虑 $0<r<\infty$的情况。对于一个固定的$r$，如果这时我们让$\theta$从$0$到$2\pi$ 连续变化，那么对应着$w(z)$将会在复平面上画出一条封闭的曲线，如下图。这个曲线可能是很扭曲的形状，也不一定是绕了一圈的，可能绕了很多圈,在这里我们并不关心这条曲线的具体形状.

<img src="/Mathartery/source/tupian/untitled2.png" alt="t11" width="500">


最后，我们再考虑 $r \to \infty$的情况。此时当$z$的幅角(表示与正实轴的夹角)从 $2\pi$ 连续变化时，显然$w(\infty)$的所有值都将是无穷大（因为此时只有$z$的最高阶项是起作用的，而它前面的系数是$1$），对应着就是 $w(\infty)$ 将在复平面上的无穷远处画出一条封闭曲线.


于是，当$r$连续的从$0$变化到$\infty$时，这条曲线将从一个点连续的变化成一条跑到无穷远处的闭合曲线.于是，其中必有某一条曲线经过了$0$点，于是命题得证.

此证明的参考网站：
<a href="https://www.physixfan.com/daishujibendinglideyigezuijiandanzhengming/"  target="_blank">>代数基本定理
</a>





<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">评注</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>

<img src="/Mathartery/source/tupian/2026-02-11 222500.png" alt="题目" width="500">

我们可以这样想,三次函数在复数域上有三个根(计入重根).如果它是实系数多项式,那么虚根必然会成对出现,即成对的虚根互为共轭复数.要是存在虚根,那虚根和它的共轭虚根就已经是两个根了,再加上一个实根,就会有三个不同的根,这和“恰有两个不同实数零点”不符.所以,所有根都只能是实根.那三个实根怎么会只有两个不同的零点呢？显然,其中必然有一个根是二重根,另一个是单根,而且这两个根不相等.也就是说,三次函数恰有两个不同实数零点,等价于它存在一个二重实根和一个异于该重根的单实根.这个结论正是我们解决上述三次函数零点问题的重要基础.
<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">论文来源</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>
<a href="https://vpn.tzc.edu.cn/https/77726476706e69737468656265737421fbf952d2243e635930068cb8/reader/flowpdf?invoice=lAYmeY%2Fxf7sw%2BD4QXUoS5SKoeUpSZsqEHFHD2wkJ487wo%2FxVMTsi88mt26q6U2oRAAtIdxQtPWw3RZdWsN30vVrRh4z5xTtwzUn%2BmKqqIuK1EUmhOstCsJon4BwmvRtD3LGtAXjpOIXi6SNtM%2FSE2pTZkH6QxRd1LV74%2Bza8ENw%3D&platform=NZKPT&sourcetype=nxgp&product=CJFN&filename=ZXSS202601012&tablename=cjfdlasn2026&type=JOURNAL&scope=trial&cflag=overlay&dflag=pdf&pages=&language=CHS&trial=&nonce=37E58282392D4737877746FEEA041FE5" target="_blank">点击访问论文原网址</a>

<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 60px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">完整版请自行下载</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 60px; vertical-align: middle;"></span>
</p>
<a href="https://github.com/MathArtery/Mathartry/blob/main/%E5%9F%BA%E4%BA%8E%E4%BB%A3%E6%95%B0%E5%9F%BA%E6%9C%AC%E5%AE%9A%E7%90%86%E7%9A%84%E4%B8%80%E9%81%93%E5%A4%8F%E4%BB%A4%E8%90%A5%E6%95%B0%E5%AD%A6%E9%80%89%E6%8B%94%E8%B5%9B%E9%A2%98%E7%9A%84%E8%A7%A3%E6%B3%95%E5%88%86%E6%9E%90_%E7%94%B0%E5%BD%A6%E6%AD%A6.pdf" download>基于代数基本定理的一道夏令营数学选拔赛题的解法分析_田彦武.pdf</a>



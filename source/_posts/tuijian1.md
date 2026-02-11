---
title: 拉格朗日乘数法在中学数学不等式证明中的应用
date: 2026-02-02
tags: [拉格朗日乘数法, 不等式, 中学数学, 数学论文]
categories: 论文推荐
math: true  
---

<p style="text-align: center;">
<span style="color:#9966CC">欢迎关注MathArtery，我们将以严谨的学术态度为您分享数学论文</span>
</p>

- 它将“在一条直线上找最高点”的约束优化问题转化成“在一个三维空间中找平坦点(驻点)”的无约束优化问题——题记

<!-- more -->

<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">论文第一页</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>

<img src="/Mathartery/tupian/20260205001.png" alt="论文第一页" width="500">

<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">摘要</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>

<div style="width: 100%; padding: 20px; background-color: #f8f9fa; border-radius: 8px; border-left: 4px solid #9966CC; margin: 20px 0; line-height: 1.8; font-size: 16px;">
  拉格朗日乘数法作为高等数学中一种强大的数学工具，其思想和方法可以为中学数学不等式的证明提供新的视角。结合中学数学不等式案例，通过分类探讨拉格朗日乘数法的应用，并与传统解法进行对比，分析其优势，旨在为中学数学教学提供新的思路和方法，帮助学生更好地理解和掌握不等式的证明。
  <br><br>
  <strong>关键词：</strong>拉格朗日乘数法；中学数学；不等式证明；多变量优化
</div>

<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">推荐理由</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>

在中学数学中，不等式的证明是一个重要的内容，它涉及代数、几何等多方面的知识，不仅考查学生对数学知识的灵活运用能力，更是培养学生逻辑思维与推理能力的重要途径。

传统的不等式证明方法，如比较法、综合法、数学归纳法等，虽然在解决许多问题时非常有效，但在某些复杂问题中可能显得繁琐或难以入手。拉格朗日乘数法作为一种优化方法，能巧妙地将不等式证明问题转化为带约束条件的优化问题，为不等式的证明提供一种结构化路径。

现有大量文献在拉格朗日乘数法应用、多元函数最值问题探究、不等式证明及推广、三角函数最值问题求解等方面取得了显著进展，但现有研究多聚焦单一案例，缺乏对拉格朗日乘数法适用场景的系统分类。

本文将通过理论阐述和案例分析，分类讨论拉格朗日乘数法在中学数学不等式证明中的可行性及创新性，为中学教师提供跨学段教学衔接的参考范式，引领学生探索更高效、更具创新性的证明路径，拓展学生的数学思维。——来自原文

<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">注解</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>

*偏导数*：类似中学的主元法，在多变量问题中，采用控制变量法，研究单一变量。

**怎么用**:1.控制其它变量  2.对目标变量求导

例如本篇论文例1，构造拉格朗日函数
$$
L(a,b,\lambda)=\sqrt{a+1}+2\sqrt{b+2}+\lambda(a+b-4)
$$

这个函数有三个变量，依次求偏导。那么对$a$求偏导就是把$b$、$\lambda$看作是常数，对$a$求导。
即
$$
\frac{\partial L}{\partial a}=\frac{1}{2\sqrt{a+1}+\lambda}
$$
类似的，分别对$b$、$\lambda$求偏导，再令三个偏导数等于零得到如下方程组$(6)$

<img src="/Mathartery/tupian/20260205002.png" alt="t2" width="500">
---
*混合偏导*：对第一次偏导后的偏导函数，再次求偏导

例如：
$$
\frac{\partial L}{\partial a}=\frac{1}{2\sqrt{a+1}+\lambda}
$$
这当然也是个函数，我们在这个函数中对$b$求导。什么？这个函数中没有$b$——也就是说对$b$而言，这个函数被看作为常数，那么对常数求导不就是$0$嘛！

因此（先$a$后$b$）
$$
 \frac{\partial^2 L}{\partial a\partial b}=0
$$
有些教材，包括wikipedia也写成：
$$
 \frac{\partial^2 L}{\partial b\partial a}=0
$$
如果是在二阶连续的情况下，那么这两个记法没有区别。本文采用第一种记法

---
*矩阵(选读)* ：矩阵的知识较为丰富，本文若是细讲绝对是喧宾夺主了，但后续的二阶检验又不得不用到矩阵，感兴趣的同学可以去bilibili系统学习，本文只针对论文内容方向作笼统介绍：

这个叫做行列式：
$$
\begin{vmatrix}
 a & b \\\\
 c & d
\end{vmatrix}
$$
规定这个二行二列行列式有这样的运算：
$$
\begin{vmatrix}
 a & b \\\\
 c & d
\end{vmatrix}
=ad-cb
$$
这个叫做矩阵：
$$
\begin{bmatrix}
 a & b\\\\
 c & d
\end{bmatrix}
$$
……

笔者认为这样的介绍毫无意义，数学应当是演绎的，而非“填鸭”的，既然中学生学有余力看这篇文章，自然有时间去系统学习矩阵，这里推荐谢启鸿老师的高等代数课(b站上可看)

---
*二阶检验(选读)* ：通过拉格朗日乘数法求得的极值或许唯一，但它是极大还是极小值，还需要进行二阶检验，尽管在中学阶段的数学题可能不需要这么麻烦。

下面我们还是以例1为例，演示如何进行二阶检验：
已知我们求得了稳定点
$$
a=\frac{2}{5},b=\frac{18}{5}
$$
Step1:构造一个Hessian矩阵
$$
H=\begin{bmatrix}
  \frac{\partial^2 L}{\partial a^2}  &  \frac{\partial^2 L}{\partial a\partial b} \\\\
  \frac{\partial^2 L}{\partial b\partial a}& \frac{\partial^2 L}{\partial b^2}
\end{bmatrix}
=\begin{bmatrix}
  -\frac{1}{4}(a+1)^{-\frac{3}{2}}  &  0 \\\\
  0& -\frac{1}{2}(b+2)^{-\frac{3}{2}}
\end{bmatrix}
$$
当然可以把已求得的a,b代入，不过例1代不代对后续计算难度没影响

Step2:计算约束梯度 $\nabla g$

我们知道例1中的约束条件(约束函数)为$g=a+b-4$

那么其梯度为
$$
\nabla g=\begin{bmatrix}
 \frac{\partial g}{\partial a} \\\\
\frac{\partial g}{\partial b} 
\end{bmatrix}
=\begin{bmatrix}
 1 \\\\
1 
\end{bmatrix}
$$

Step3:构造切空间基矩阵$Z$

切空间是所有满足$\nabla g^T d = 0$的方向$d = (d_1, d_2)^T$。

即：
$$
\begin{bmatrix}
 1 & 1
\end{bmatrix}
\begin{bmatrix}
d_1 \\\\
d_2
\end{bmatrix} 
= d_1 + d_2 = 0
$$
你可以理解为$d$是个方向向量，$d_1$和$d_2$的值不唯一，我们取$d_1=1$，$d_2=-1$

所以$Z$可以写成
$$
Z=\begin{bmatrix}
1 \\\\
-1
\end{bmatrix}
$$
Step4:判断投影Hessian矩阵$H_{red}$(Sylvester准则)
$$
H_{red}=Z^T(HZ)=
\begin{bmatrix}
 1 & -1
\end{bmatrix}
\begin{bmatrix}
 -\frac{1}{4}(a+1)^{-\frac{3}{2}} \\\\ \frac{1}{2}(b+2)^{-\frac{3}{2}}
\end{bmatrix}
=-\frac{1}{4}(a+1)^{-\frac{3}{2}}-\frac{1}{2}(b+2)^{-\frac{3}{2}}
$$
很显然，$H_{red}$的"值"是负的(负定)，因此，取得的是极大值，则是例1要求的最大值！

特别说明：如果一开始的变量不止$a$,$b$，如例2是三元的，那么得到的$H_{red}$是一个二行二列的矩阵（不再是“值”）,我们就要计算$det(H_{red})$,也就是矩阵的“行列式值”（特征值），并结合矩阵第一个元素的正负，判断其正定性，学有余力的同学可以去了解Sylvester准则

其实，在中学阶段我们已经学会如何判断函数极值，就是求二阶导！

在这里可以利用约束条件代换，将多变量函数转为单变量函数，已知稳定点(极值点)，然后求二阶导。（Taylor展开二阶项的正负决定函数的凹凸性）

- 二阶判断是二阶导数在高维约束情形下的自然推广

二阶判断与二阶导的本质是一样的！！！
<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">评注</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>
拉格朗日乘数法能够在中学数学题中正确运用，确实可以达到“降维打击”的效果，并且在绝大多数适用的中学题中，是不需要进行二阶判断的，如例1只求出一个稳定点，而题目也说求最大值，因此这个值一定是题目所要的最大值！

不过，本篇论文所给的题目中，例3是最不适合用此方法的，因为例3所要求的是最小值，然而通过二阶判断可知，拉格朗日乘数法求得的稳定点为极大值点，只能通过取边界求出最小值了，例3还是用解法1更好！

<img src="/Mathartery/tupian/20260205003.png" alt="t3" width="500">

- “拉格朗日秒了？”未必能秒！

本论文总结了拉格朗日乘数法在中学阶段的应用，题型完备，内容上乘。不过，中学生只知道怎么用（也不完全知道），却不通其理，真的好吗？

它是算法还是方法呢？

私以为，维度坍缩后的模样是丑陋的……
<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">论文来源</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>
<a href="https://kns.cnki.net/kcms2/article/abstract?v=-w8R4t09JVWrDV9BkgdFcb9sDv5cGM169hSiS5A7XetOezGSM9mI3LXPFRmf6FNTyA_-d9-sD_l3w5Utl6nFvj9nfw3GjxalbFMyiUTIQi2xaTDTQ6XsRXoOw2l_n2IGFMj7_k3Vt5yXYJaBxRAwH7Z7LLQhPBNYAOQPz2bQxmA=&uniplatform=NZKPT" target="_blank">点击访问论文原网址</a>

<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 60px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">完整版请自行下载</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 60px; vertical-align: middle;"></span>
</p>
<a href="https://github.com/MathArtery/Mathartry/blob/main/%E6%8B%89%E6%A0%BC%E6%9C%97%E6%97%A5%E4%B9%98%E6%95%B0%E6%B3%95%E5%9C%A8%E4%B8%AD%E5%AD%A6%E4%B8%8D%E7%AD%89%E5%BC%8F%E8%AF%81%E6%98%8E%E4%B8%AD%E7%9A%84%E5%88%9B%E6%96%B0%E5%BA%94%E7%94%A8.pdf" download>拉格朗日乘数法在中学不等式证明中的创新应用.pdf</a>

---
title: 阿基米德对圆周率之估计及其与刘徽之“割圆术”的比较
date: 2026-03-18
tags: 佩尔方程、调日法
categories: 论文推荐
mathjax: true  
---

<p style="text-align: center;">
<span style="color:#9966CC">欢迎关注MathArtery，我们将以严谨的学术态度为您分享数学论文</span>
</p>

<!-- more -->

<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">论文第一页</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>

![](https://files.mdnice.com/user/150615/65666329-68cf-425d-bdf9-e703a7f86876.jpg)

<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 20px; color: #333; font-weight: 500;">摘要</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>


<div style="width: 100%; padding: 20px; background-color: #f8f9fa; border-radius: 8px; border-left: 4px solid #9966CC; margin: 20px 0; line-height: 1.8; font-size: 16px;">
  本文以阿基米德对圆周率的估计为引，先还原阿基米德未作说明的$\sqrt{3}$有理近似推导过程，通过佩尔方程、调日法、连分数法、巴比伦法等经典算法，解释其所用$\frac{265}{153}<\sqrt{3}<\frac{1351}{780}$的由来。全文主要讲述了如何去估计一个不可用实数表达的数，语言活泼有趣，易让人体会数学之美。
</div>

<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">推荐理由</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>

本文详实地介绍了传统估算无理数的方法，这对我们的思维很有启发。它系统还原阿基米德$\sqrt{3}$有理近似的多种推导方法，填补了其原著中未作说明的关键细节空白，还将其圆周率迭代过程与后世数学成果关联，挖掘出方法的历史前瞻性。并且用现代数学记号重构阿基米德和刘徽的经典算法，降低了古代数学原著的理解门槛。他的引入方式是从古典入手，能有效打破“公式到公式”的刻板教学模式，帮助教师还原数学家的创新思维过程，作为教学的辅助资料再合适不过了。


<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">注解</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>

+ 佩尔方程

指形如$x^2-Ny^2=1$的不定方程，其中N为无平方因子的正整数，其正整数解(x,y)可用于构造$\sqrt{N}$的高精度有理近似值$\frac{x}{y}$；与之相关的负佩尔方程$x^2-Ny^2=-2$等，也可作为无理数有理近似的重要工具，阿基米德所用$\sqrt{3}$近似值即源于此类方程的解。

+ 调日法

由我国南北朝数学家何承天提出的无理数有理近似方法，核心原理为若$\frac{a}{b}<\frac{c}{d}$，则对任意正整数$m$、$n$，有$\frac{a}{b}<\frac{ma+nc}{mb+nd}<\frac{c}{d}$，可通过调整两个近似分数的分子分母，得到精度更高的中间近似值，是古代中西数学中均被应用的经典逼近方法。

+ 巴比伦法

古巴比伦人发明的求正数算术平方根的通用方法，迭代公式为$a_n=\frac{1}{2}(a_{n-1}+\frac{A}{a_{n-1}})$（$A$为待开方数），本质是牛顿迭代法的特例，具有平方收敛特性，即迭代次数每增加一次，近似值的有效数字位数约翻倍，收敛速度远快于传统迭代方法。

+ 割圆术

我国魏晋数学家刘徽提出的圆周率估计方法，核心思想为“割之弥细，所失弥少，割之又割，以至于不可割，则与圆合体而无所失矣”，通过不断倍增圆内接正多边形的边数，利用勾股定理计算其边长与周长，以正多边形周长逼近圆的周长，从而得到圆周率的近似值。


<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">论文来源</span>
 <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>
<a href="https://kns.cnki.net/kcms2/article/abstract?v=vxt3_kKBHYMG-18vzLcL6GtKYieJUFQB95UXe1vsHWoG8qkLrPbNzEnItOp9blf1M3-8vtaKt4tY38FSxoFosgQmNDYcbt4sMhxS0eafqTvbIE5NFpjpkFhivue4FpdLNQxju5UWy00I0_b7Gre7OwZmD_2M_Ft4JjE5nBZ5IsFTyBVbPUHDuQ==&uniplatform=NZKPT&language=CHS"target="_blank">点击访问论文原网址</a>


<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">完整版请自行下载</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>
<a href="https://github.com/MathArtery/Mathartry/blob/main/%E9%80%89%E6%8B%A9%E5%86%B3%E7%AD%96%E6%B8%B8%E6%88%8F%E4%B8%8E%E8%B4%9D%E5%8F%B6%E6%96%AF%E5%85%AC%E5%BC%8F.pdf" download>阿基米德对圆周率之估计及其与刘徽之“割圆术”的比较.pdf</a>
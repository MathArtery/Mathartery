---
title: 选择决策游戏与贝叶斯公式
date: 2026-03-10
tags: 贝叶斯公式
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

![](https://files.mdnice.com/user/150615/db8403ad-0d7b-49b9-b6a1-c8944e841f17.jpg)

<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 20px; color: #333; font-weight: 500;">摘要</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>


<div style="width: 100%; padding: 20px; background-color: #f8f9fa; border-radius: 8px; border-left: 4px solid #9966CC; margin: 20px 0; line-height: 1.8; font-size: 16px;">
文章以经典三门选择决策游戏为引导，给出贝叶斯公式的标准形式。以规则 1 下的三门问题为范例，完成了从先验概率到后验概率的完整严谨推导，清晰呈现了贝叶斯公式利用新信息修正概率判断的核心逻辑；接着，文章对基础模型进行了推广，推导了多轮主持人开门与嘉宾选门后的概率变化规律，归纳出多轮选择中保障获车概率最大化的决策原则；文章在最后阐释了贝叶斯方法的系统推理与决策逻辑，点明了其迭代修正决策的过程与人类学习思维模式的契合性。
</div>

<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">推荐理由</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>

这篇文章没有事件域、概率测度等高阶理论，但也完整呈现了贝叶斯公式从定义到规范应用的全流程，既能够为高中读者提供课内概率知识的具象化拓展场景，也能够为读者搭建起从基础概率到贝叶斯统计的入门阶梯；文章针对长期存在认知争议的三门问题，严格规定主持人开门规则这一核心前提，分别完成了对应规则下的严谨概率演算，厘清了不同前提对概率结果的决定性影响，能够帮助目标读者建立起 “先明确规则前提、再开展概率计算” 的严谨数学分析思维，纠正对条件概率问题的普遍误解；文章在完成纯理论推导的同时，明确阐释了贝叶斯方法的标准操作程序，点明了其在阿尔法狗等人工智能领域的实际应用，让目标读者能够直观看到课内基础数学知识在前沿科技领域的核心作用，深化对概率统计学科实用价值的认知。


<p style="text-align: center;font-size: 20px">
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
  <span style="display: inline-block; margin: 0 15px; font-size: 18px; color: #333; font-weight: 500;">注解</span>
  <span style="display: inline-block; border-top: 2px solid #9966CC; width: 70px; vertical-align: middle;"></span>
</p>

+ 贝叶斯公式

原文给出的规范定义为，设$A_1, A_2, \cdots, A_n$是两两相斥的事件组，满足$P(A_i) > 0$（$i = 1,2,\cdots,n$）且$A_1 \cup A_2 \cup \cdots \cup A_n = \Omega$（样本空间），对任意事件$B \subseteq \Omega$、$P(B) > 0$，有
$$
P(A_i|B) = \frac{P(A_i)P(B|A_i)}{\sum_{k=1}^n P(A_k)P(B|A_k)}, i = 1,2,\cdots,n
$$
是贝叶斯方法的核心公式，用于通过新观测信息修正事件的先验概率。

+ 先验概率

原文定义为，未获得新的观测信息（如主持人打开门）前，对事件发生概率的初始估计。如三门游戏中，嘉宾选门后、主持人未开门时，三个门有跑车的概率$P(A_1) = P(A_2) = P(A_3) = \frac{1}{3}$，即为先验概率。

+ 后验概率

原文定义为，获得新的观测信息后，通过贝叶斯公式对先验概率修正后得到的条件概率。如三门游戏中，主持人打开3号门显示山羊后，计算得到的$P(A_1|B_3)$、$P(A_2|B_3)$，即为后验概率。

+ 贝叶斯方法

原文定义为，以贝叶斯公式为基础的系统推理和决策方法，基本程序为：先根据实际情况确定先验概率，再利用贝叶斯公式计算后验概率，对先验概率进行修正校对，最终根据后验概率做出推理和决策；支持多轮迭代，可将上一步的后验概率作为下一步的先验概率持续修正。


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
<a href="https://github.com/MathArtery/Mathartry/blob/main/%E9%80%89%E6%8B%A9%E5%86%B3%E7%AD%96%E6%B8%B8%E6%88%8F%E4%B8%8E%E8%B4%9D%E5%8F%B6%E6%96%AF%E5%85%AC%E5%BC%8F.pdf" download>选择决策游戏与贝叶斯公式.pdf</a>
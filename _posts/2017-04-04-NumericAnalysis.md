---
layout:     post
title:      "数值分析"
subtitle:   "数值分析学习笔记"
date:       2017-04-04 23:24:00
author:     "HELLKING"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - Mathematic
---

## 3.1 函数逼近的基本概念
### 3.1.1 函数逼近与函数空间
#### 定义 1
$$\alpha_1x_1+\alpha_2x_2+\alpha_3x_3+\cdots+\alpha_nx_n=0$$
1. 线性相关
2. 线性无关
3. 基
4. 坐标
5. 无限维线性空间
#### 定理 1 (魏尔斯特拉斯)
设$f(x)\in C[a,b]$ , 则对任意 $\epsilon>0$ , 总存在一个代数式多项式 $p(x)$ , s.t
$$\max \limits_{a\leqslant x\leqslant b}\{|f(x)-p(x)|\ <\epsilon \}$$
在 $[a,b]$ 上一致成立
## 3.2 正交多项式
### 3.2.1 正交函数族与正交多项式
#### 定义 5
若 $f(x),g(x)\in C[a,b]$ , $p(x)$ 为 $[a,b]$ 的权函数且满足
$$(f(x),p(x)) = \int_{a}^{b}{p(x)f(x)g(x)}=0$$
$$\begin{eqnarray}
f(x)=
\begin{cases}
1, &x>0\cr 0, &x=0 \cr -1, &x<0
\end{cases}
\end{eqnarray}$$
### 3.2.3 切比雪夫多项式
权函数 $p(x)= \frac{1}{\sqrt{1-x^2}}$ , 区间 $[-1,1]$ , 序列 $\{ 1,x,x^2,\cdots,x^n \}$ 可以表示
$$T_n(x) = \cos(n\arccos x)$$
性质
1.
## 3.3 最佳平方逼近

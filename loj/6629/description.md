
# 题目描述

**来源：[Project Euler #585](http://pe-cn.github.io/585/)**

热爱各种各样数学的 <span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 看到了一类根式化简题：
$$
\begin{aligned}
\sqrt{3+\sqrt{2}+\sqrt{2}}&=\sqrt{2}+\sqrt{1}=\sqrt{2}+1\\
\sqrt{8+\sqrt{15}+\sqrt{15}}&=\sqrt{5}+\sqrt{3}\\
\sqrt{20+\sqrt{96}+\sqrt{12}}&=\sqrt{9}+\sqrt{6}+\sqrt{3}-\sqrt{2}=3+\sqrt{6}+\sqrt{3}-\sqrt{2}\\
\sqrt{28+\sqrt{160}+\sqrt{108}}&=\sqrt{15}+\sqrt{6}+\sqrt{5}-\sqrt{2}
\end{aligned}
$$
<span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 对这些~~傻逼~~题很感兴趣，他认为一个三元组 $(x,y,z)$ 是好的，当且仅当 $\sqrt{x+\sqrt{y}+\sqrt{z}}$ 可以表示为 $\displaystyle  \sum_{i=1}^k s_i\sqrt{a_i}$ 的形式，并且 $s_i =\pm 1, a_i\in\mathbb N^*, x\in [1,n], \sqrt{y},\sqrt{z} \notin \mathbb N$。现在 <span style="font-weight:bold">E<span style="color:red">ntropyIncreaser</span></span> 想让身为蒟蒻的你，告诉他对于 $n$，**所有好的三元组构成的根式化简得到的不同的值**一共有多少个。


# 输入格式

一行一个整数 $n$。

# 输出格式

一行一个整数表示答案。

# 样例

#### 样例输入 1
```plain
5
```

#### 样例输出 1
```plain
3
```

# 数据范围与提示

对于 $100\%$ 的数据，$1\leqslant n\leqslant 5\times 10^5$。


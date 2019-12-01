
# 题目描述

> 9 月春雨忙播种。

「搞 OI 不如种田。」  
<span style="font-weight:bold">r<span style="color:red">value</span></span> 在家种了一棵二叉树，每个结点有一个权值。  
<span style="font-weight:bold">r<span style="color:red">value</span></span> 为自己种的树买了肥料，每天给树施肥。

可是几天后，<span style="font-weight:bold">r<span style="color:red">value</span></span> 却发现树上很多个结点枯死了，他这才发现，自己买的肥料是二叉搜索树专用版，而他的树有些点的权值并不大于左子树中的所有点。  
<span style="font-weight:bold">r<span style="color:red">value</span></span> 很生气，只能去种土豆了。可种服务器也实属不易，因为 <span style="font-weight:bold">r<span style="color:red">value</span></span> 想在每个坑里种上一些不同种类的土豆。

具体来说，田野里一共有 $n$ 个坑，<span style="font-weight:bold">r<span style="color:red">value</span></span> 会依次去在每个坑里播撒种子。  
而由于年迈体衰，在第 $i$ 个坑 <span style="font-weight:bold">r<span style="color:red">value</span></span> 有 $p_i$ 的概率播错种子。播一个种子需要一单位的时间，铲除一个种子也需要一单位的时间。在任意时刻，<span style="font-weight:bold">r<span style="color:red">value</span></span> 可以花 $t$ 的时间检查已经播下去的所有种子，并且从当前播种的位置一直往前捯饬，也就是铲除每一个种子一直到第一个出错的位置（铲除的位置包括第一个出错的位置）。  
<span style="font-weight:bold">r<span style="color:red">value</span></span> 想知道最优决策下自己播完所有种子的期望时间是多少，<span style="font-weight:bold">r<span style="color:red">value</span></span> 太老了算不动了，所以他想让你帮他算一算。

# 输入格式

输入第一行包含两个整数 $n,t$。  
输入第二行包含 $n$ 个小数，依次表示 $p_i$。

# 输出格式

一行一个小数表示答案。  
当你的答案与标准答案的相对或绝对误差不超过 $10^{-6}$ 时被认为是正确的。

# 样例

#### 样例输入

```plain
3 1
0.00001 0.5 0.00001
```

#### 样例输出

```plain
8.000080000800008
```

# 数据范围与提示

对于 $20\%$ 的数据，有 $n\leq 10$。  
对于 $50\%$ 的数据，有 $n\leq 200$。  
对于 $100\%$ 的数据，有 $1\leq n\leq 3000,1\leq t\leq 10^6,10^{-5}\leq p_i\leq0.5$。


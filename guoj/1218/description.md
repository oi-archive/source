
# 题目描述

反正切函数可展开成无穷级数，有如下公式
$$
\arctan(x)=\sum_{n=0}^\infty\frac{(-1)^nx^{2n+1}}{2n+1}(0\le x\le 1)\qquad(1)
$$
使用反正切函数计算 $\pi$ 是一种常用的方法。例如，最简单的计算 $\pi$ 的方法：
$$
\begin{aligned}
\pi&=4\arctan(1)\\
&=4(1-\frac 13+\frac 15-\frac 17+\frac 19-\frac 1{11}+\cdots)\qquad(2)
\end{aligned}
$$
然而，这种方法的效率很低，但我们可以根据角度和的正切函数公式：
$$
\tan(\alpha+\beta)=\frac{\tan(\alpha)+\tan(\beta)}{1-\tan(\alpha)\tan(\beta)}\qquad\qquad\quad(3)
$$
通过简单的变换得到：
$$
\arctan(p)+\arctan(q)=\arctan(\frac{p+q}{1-pq})\quad\ \ (4)
$$
利用这个公式，令 $\displaystyle p=\frac 12,q=\frac 13$ ，则 $\frac{p+q}{1-pq}=1$，有
$$
\arctan\left(\frac 12\right)+\arctan\left(\frac 13\right)=\arctan\left(\frac{\frac12+\frac 13}{1-\frac 12\cdot\frac 13}\right)=\arctan(1)
$$
使用 $\displaystyle\frac 12$ 和 $\displaystyle \frac 13$ 的反正切来计算 $\arctan(1)$，速度就快多了。

我们将公式 $(4)$ 写成如下形式
$$
\arctan(\frac 1a)=\arctan(\frac 1b)=\arctan(\frac 1c)
$$
其中 $a$、$b$ 和 $c$ 均为正整数。

我们的问题是：对于每一个给定的 $a$，求 $b+c$ 的值。我们保证对于任意的 $a$ 都存在整数解。如果有多个解，要求你给出 $b+c$ 最小的解。





# 输入格式

输入文件中只有一个正整数 $a$。

# 输出格式

输出文件中只有一个整数，为 $b+c$ 的值。

# 样例

#### 样例输入
```plain
1
```

#### 样例输出
```plain
5
```

# 数据范围与提示

对于所有的数据，$1\le a\le 60000$。


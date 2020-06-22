
# 题目描述

 **译自 [CCO 2020](https://cemc.math.uwaterloo.ca/contests/computing/2020/index.html) Day1 T1「[A Game with Grundy](https://cemc.math.uwaterloo.ca/contests/computing/2020/cco/day1.pdf)」**，翻译者：[ksyx](/user/1649)。

---

小 G 在和他的 $N$ 个朋友们玩躲猫猫。

他的朋友们站在 $x$ 轴上，其中朋友 $i$ 的坐标是 $P_i(x_i, 0)$。对于第 $i$ 个朋友，他的视野由过 $P_i$ 的两条斜率为 $\pm \frac{v_i}{h_i}$ 的朝上的射线构成的三角形区域确定，但是他的朋友们视野并不包括这两条射线上的点。

小 G 打算藏在符合形式 $(a, Y)$ 的坐标处，其中 $a \in [L, R]$ 且 $L, R, Y$ 为整数常数。但是，显然某些符合这个形式的坐标所对应的点会落在他某些朋友的视野之中（即严格处于上述三角形区域中）。因此，他想知道对于 $i \in [0, N]$，有多少个满足条件的坐标使得这个坐标对应的点至多在 $i$ 个朋友的视野之中。

# 输入格式

第一行一个整数 $N$。

接下来一行三个整数 $L, R, Y$。

接下来 $N$ 行每行三个整数：$x_i, v_i, h_i$。其中 $x_i$ 表示第 $i$ 个朋友的横坐标，两条斜率为 $\pm \frac{v_i}{h_i}$ 的过 $P_i(x_i, 0)$ 的朝上的射线限定了朋友的视野范围。



# 输出格式

输出 $N + 1$ 行，第 $i$ 行一个整数表示满足题面描述中的要求且至多在 $i$ 个朋友的视野之中的点的个数。

# 样例

#### 样例输入

```plain
3
-7 7 3
0 2 3
-4 2 1
3 3 1
```

#### 样例输出

```plain
5
12
15
15
```

#### 样例解释

小 G 在和三个朋友玩，他们的视野以及小 G 可以躲藏的点如图所示。注意，在位置 $(2, 3)$ 和 $(4, 3)$ 时，小 G 只会被在原点的朋友看见，因为这两个点处于位于 $(3, 0)$ 的朋友的视野边界上。

<img width=60%  src="/source/loj/3317/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wNi8xNC81ZWU1YzRjMTRjYmJiLnBuZw==.png" alt="sample" />


# 数据范围与提示

对于 $60\%$ 的数据，有 $-{10}^6 \le L \le R \le {10}^6$；  
对于 $100\%$ 的数据，有 $N \le {10}^5$，$-{10}^9 \le L \le R \le {10}^9$，$1 \le Y \le {10}^6$，$L \le x_i \le R$，$1 \le v_i, h_i \le 100$。



# 题目描述

在平面坐标系上给定 $n$ 个不同的整点（也即横坐标与纵坐标皆为整数的点）。我们称从这 $n$ 个点中选择 $6$ 个不同的点所组成的有序六元组 $\langle A,B,C,D,E,F\rangle$ 是一条「鱼」，当且仅当：$AB=AC,BD=CD,DE=DF$（身形要对称），并且 $\angle BAD,\angle BDA$ 与 $\angle CAD,\angle CDA$ 都是锐角（脑袋和屁股显然不能是凹的），$\angle ADE,\angle ADF$ 大于 $90^\circ$（也即为钝角或平角，为了使尾巴不至于翘那么别扭）。

下图就是一个合法的鱼的例子：

![fish.png](/source/guoj/1070/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMDYvMjEvNWQwYzdkZjFlYTJjNzI4Njc5LnBuZw==.png)

其中点的组成相同，但顺序不同的鱼视为不同的鱼，即 $\langle A,B,C,D,E,F\rangle$ 和 $\langle A,C,B,D,E,F\rangle$ 视为不同的两条鱼（毕竟鱼也有背和肚子的两面），同理 $\langle A,B,C,D,E,F\rangle$ 和 $\langle A,B,C,D,F,E\rangle$ 也可以视为不同的两条鱼（假设鱼尾巴可以打结）。

问给定的 $n$ 个点可以构成多少条鱼。特别的，数据保证 $n$ 个点互不重复。

# 输入格式

第一行一个正整数 $n$，代表平面上点的个数。

接下来 $n$ 行每行两个整数 $x,y$，代表点的横纵坐标。

# 输出格式

输出一行一个非负整数，代表鱼的个数。

# 样例

#### 样例输入
```plain
8
-2 0
-1 0
0 1
0 -1
1 0
2 0
3 1
3 -1
```
#### 样例输出
```plain
16
```

# 数据范围与提示

对于前 $20\%$ 的数据，保证 $n \le 10, 0 \le |x|, |y| \le 5$。

对于前 $40\%$ 的数据，保证 $n \le 300, 0 \le |x|, |y| \le 10^5$。

对于另外 $20\%$ 的数据，保证 $|x|, |y| \le 20$。

对于所有数据，保证 $6 \le n \le 1000, 0 \le |x|, |y| \le 10^9$，$n$ 个点互不重复。


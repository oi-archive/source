
# 题目描述

走过奈何桥有一个名叫望乡台的土台, 望乡台边有个名曰孟婆的老妇人在卖孟婆汤. 一生爱恨情仇, 一世浮沉得失, 都可以随这碗孟婆汤遗忘得干干净净.

现在有$n$碗孟婆汤摆成一排, 汤的品种不超过$26$种, 因此我们用小写字母 a~z 来表示一种汤, 每碗汤还有一个权值$val_i$.

你需要选出若干碗连续摆放的汤喝下去, 这些汤必须满足下列条件:

- 至少有一碗汤.
- 这个子串 (也就是那些汤) 在原串的所有子串中的字典序降序排名等于这一段汤的权值之和.

现在你需要知道有多少种选汤的方案.

注意出现在不同位置、本质相同的子串的排名是相同的且要重复计算方案数, 如`aaa`这个串, 排名为$1$的子串为`aaa`, 出现了一次; 排名为$2$的子串为`aa`, 出现了两次; 排名为$3$的子串为`a`, 出现了三次. (若还没明白题意的可以看样例1, 3的解释)

# 输入格式

第一行一个长度为$n$由小写字母组成的字符串, 每个字符代表一碗汤.

第二行$n$个非负整数, 表示$val_i$.

# 输出格式

一行一个整数, 表示能被选的子串个数$S$.

接下来$S$行每行两个整数$L, R$, 分别表示每个可选子串的左端点与右端点, 按照左端点升序为第一关键字, 右端点升序为第二关键字排序.

# 样例

**样例 1 输入**
```
abcd
10 0 1 1
```

**样例 1 输出**
```
3
1 1
3 4
4 4
```

**样例 1 解释**

我们把所有的子串按照字典序从大到小排名: `d, cd, c, bcd, bc, b, abcd, abc, ab, a`.

那么串`d`的排名为$1$ (第一大) , 权值和为$1$, 可以被选.

串`cd`的排名为$2$, 权值和为$2$, 可以被选.

串`a`的排名为$10$, 权值和为$10$, 可以被选.

其他串则不满足这个条件，故有三个串可以被选.

**样例 2 输入**
```
aaaa
1 1 1 1
```

**样例 2 输出**
```
0
```

**样例 3 输入**
```
aaa
1 1 1
```

**样例 3 输出**
```
2
1 2
2 3
```

**样例 3 解释**

串`a`的排名是$3$, 权值和都是$1$.

串`aa`的排名是$2$, 权值和都是$2$, 共有两个串`aa`, 位置分别为$1 \ 2$和$2 \ 3$.

串`aaa`的排名是$1$, 权值和都是$3$.

**样例 4 输入**
```
abdacdbcecbd
1 3 1 3 3 4 2 2 4 2 1 1
```

**样例 4 输出**
```
2
3 8
9 9
```

# 数据范围与提示

本题共有十个测试点.

对于第$1$个测试点, 满足$n \leq 50$,

对于第$2, 3$个测试点, 满足$n \leq 1000$,

对于第$4$个测试点, 满足字符串只由一种字符组成, $n \leq 50000$,

对于第$5$个测试点, 满足所有汤的权值相同, $n \leq 50000$,

对于第$6, 7$个测试点, 满足$n \leq 50000$,

对于第$8, 9, 10$个测试点, 满足$n \leq 200000$.

保证$0 \leq val_i \leq 10000$, 且每个测试点满足要求的子串个数不超过$200000$个.

<!--出题人：thkkk & shinetism-—->

来源：HNOI 2018 省队集训 Day 5 T3


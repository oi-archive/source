
# 题目描述

当今社会，在社交网络上看朋友的消息已经成为许多人生活的一部分。通常，一个用户在社交网络上发布一条消息（例如微博、状态、Tweet 等）后，他的好友们也可以看见这条消息，并可能转发。转发的消息还可以继续被人转发，进而扩散到整个社交网络中。

在一个实验性的小规模社交网络中我们发现，有时一条热门消息最终会被所有人转发。为了研究这一现象发生的过程，我们希望计算一条消息所有可能的转发途径有多少种。为了编程方便，我们将初始消息发送者编号为 $1$，其他用户编号依次递增。

该社交网络上的所有好友关系是已知的，也就是说对于 A、B 两个用户，我们知道 A 用户可以看到 B 用户发送的消息。注意可能存在单向的好友关系，即 A 能看到 B 的消息，但 B 不能看到 A 的消息。

还有一个假设是，如果某用户看到他的多个好友转发了同一条消息，他只会选择从其中一个转发，最多转发一次消息。从不同好友的转发，被视为不同的情况。

如果用箭头表示好友关系，下图展示了某个社交网络中消息转发的所有可能情况。（初始消息是用户 $1$ 发送的，加粗箭头表示一次消息转发）

![Ex1](/source/loj/2532/img/aHR0cHM6Ly9sb2ouYWMvcHJvYmxlbS8yNTMyL3Rlc3RkYXRhL2Rvd25sb2FkL0NRMjAxOEV4MS5wbmc=.png)![Ex2](/source/loj/2532/img/aHR0cHM6Ly9sb2ouYWMvcHJvYmxlbS8yNTMyL3Rlc3RkYXRhL2Rvd25sb2FkL0NRMjAxOEV4Mi5wbmc=.png)![Ex3](/source/loj/2532/img/aHR0cHM6Ly9sb2ouYWMvcHJvYmxlbS8yNTMyL3Rlc3RkYXRhL2Rvd25sb2FkL0NRMjAxOEV4My5wbmc=.png)

![Ex4](/source/loj/2532/img/aHR0cHM6Ly9sb2ouYWMvcHJvYmxlbS8yNTMyL3Rlc3RkYXRhL2Rvd25sb2FkL0NRMjAxOEV4NC5wbmc=.png)![Ex5](/source/loj/2532/img/aHR0cHM6Ly9sb2ouYWMvcHJvYmxlbS8yNTMyL3Rlc3RkYXRhL2Rvd25sb2FkL0NRMjAxOEV4NS5wbmc=.png)![Ex6](/source/loj/2532/img/aHR0cHM6Ly9sb2ouYWMvcHJvYmxlbS8yNTMyL3Rlc3RkYXRhL2Rvd25sb2FkL0NRMjAxOEV4Ni5wbmc=.png)

# 输入格式

第一行，为一个正整数 $n$，表示社交网络中的用户数：第二行为一个正整数 $m$，表示社交网络中的好友关系数目。

接下来 $m$ 行，每行为两个空格分隔的整数 $a_i$​ 和 $b_i$，表示一组好友关系，即用户 $a_i$​ 可以看到用户 $b_i$​ 发送的消息。

# 输出格式

共一行，为一条消息所有可能的转发途径的数量，除以 $10007$ 所得的余数。

# 样例

#### 样例输入

```plain
4
7
2 1
3 1
1 3
2 3
3 2
4 3
4 2
```

#### 样例输出

```plain
6
```

# 数据范围与提示

对于 $30\%$ 的数据，$1≤n≤10$。

对于 $100\%$ 的数据，$1\leq n\leq 250, 1\leq a_i,b_i\leq n, 1\leq m\leq n(n-1)$。


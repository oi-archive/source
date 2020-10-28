
# 题目描述

**译自 [COCI 2019/2020 Contest #3](https://hsin.hr/coci/archive/2019_2020/) T4「[Lampice](https://hsin.hr/coci/archive/2019_2020/contest3_tasks.pdf)」**

Mirko 准备用 $ N $ 个 LED 灯来装饰圣诞树。这 $ N $ 个灯通过了 $ N - 1 $ 根电线连接在一起，任意两个灯之间都能通过电线互相到达。并且我们知道所有灯的颜色。

装饰结束后，Mirko 发现了很多有趣的图案，其中他最感兴趣的是 *palindromic segments*。一个 palindromic segments 是一条灯 $ u $ 和灯 $ v $ 之间的路径，满足从 $ u $ 到 $ v $ 经过的灯的颜色序列和从从 $ v $ 到 $ u $ 经过的灯的颜色序列相同。

Mirko 想要知道最长的 palindromic segments 有多长。一个 palindromic segments 长度定义为这条路径上灯的个数。

# 输入格式

第一行包含一个整数 $ N $ ($ 1 \le N \le 50000 $)，表示灯的个数。

第二行包含一个长度为 $ N $ 的字符串，仅由小写字母组成，其中第 $ i $ 个字符表示第 $ i $ 个灯的颜色。

接下里 $ N - 1 $ 行，每行包含两个整数 $ A $ 和 $ B $ ($ 1 \le A, B \le N, A \ne B $)，表示灯 $ A $ 和 灯 $ B $ 之间有一条电线直接相连。

# 输出格式

仅一行，包含一个整数表示最长的 palindromic segments 的长度。

# 样例

#### 样例输入 1
```plain
7
imanade
1 2
2 3
3 4
4 5
5 6
6 7
```

#### 样例输出 1
```plain
3
```

#### 样例输入 2
```plain
4
aabb
1 2
1 3
3 4
```

#### 样例输出 2
```plain
2
```

#### 样例输入 3
```plain
8
acdbabcd
1 6
6 7
6 3
3 4
4 5
5 2
8 5
```

#### 样例输出 3
```plain
5
```

# 数据范围与提示

子任务 1（15 分）：$ 1 \le N \le 3000 $；

子任务 2（25 分）：灯 $ i $ 和灯 $ i + 1 $ ($1 \le i < N$) 通过电线直接相连；

子任务 3（25 分）：最多只有 $ 100 $ 个灯和另外一个灯直接相连；

子任务 4（35 分）：没有额外限制。


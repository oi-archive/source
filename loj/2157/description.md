
# 题目描述

**译自 POI 2011 Round 1. C「[Lightning Conductor](https://szkopul.edu.pl/problemset/problem/iYVwsAcHHCRZzAtQh0QFKbsu/site/?key=statement)」**

气候变化使 Byteburg 不得不建造一个大型避雷针来保护城市里的所有建筑物。建筑物恰好沿一条街，从 $1$ 到 $n$ 编号。

建筑物的高度和避雷针的高度都是非负整数。Byteburg 经费有限，只能建造一个避雷针。而且避雷针越高，价格越贵。

在建筑物 $i$ （高度为 $h_i$）屋顶放置高为 $p$ 的避雷针能够保护建筑物 $j$ 的条件是：

$$ h_j \le h_i + p - \sqrt{\lvert i - j \rvert} $$

其中 $\lvert i - j \rvert$ 表示 $i$ 和 $j$ 差的绝对值。

Byteburg 需要你帮它计算，如果在第 $i$ 个建筑物的屋顶放置这样的避雷针的话，避雷针的最小高度是多少。

# 输入格式

第一行一个整数 $n$ ($1\le n\le 5\times 10^5$) 表示 Byteburg 的建筑物个数。

接下来 $n$ 行每行一个整数 $ h_i $($ 0 \le h_i \le 10^9 $) 表示第 $i$ 个建筑物的高度。

# 输出格式

输出 $n$ 行，每行一个非负整数 $P_i$ 表示第 $i$ 个建筑物屋顶上放置避雷针的最小高度。

# 样例

#### 样例输入
```plain
6
5
3
2
4
2
4
```

#### 样例输出
```plain
2
3
5
3
5
4
```

# 数据范围与提示

Task author: Piotr Niedzwiedz.


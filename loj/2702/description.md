
# 题目描述

**译自 POI 2012 Stage 3. Day 2「[Bezpieczeństwo minimalistyczne](https://szkopul.edu.pl/problemset/problem/aSbIC_LB4H-CGMYPEVue5jFw/site/?key=statement)」**

给定一张无向图，点有点权 $p(v)$，边有边权 $b(u,v)$，初始时保证对每条边有 $p(u) + p(v) \ge b(u,v)$。

现在需要减少一部分点的点权，使得对每条边都恰有 $p(u) + p(v) = b(u,v)$.

求整张图减少的点权和的最小值和最大值。

# 输入格式

第一行两个整数 $n$ 和 $m$（$1 \le n \le 500\ 000,0 \le m \le 3\ 000\ 000$），表示图的点数和边数。

接下来一行 $n$ 个非负整数 $p(1),p(2),\ldots,p(n) (0 \le p(i) \le 10^6)$，表示点权。

接下来 $m$ 行每行三个整数 $u_i, v_i, b(u_i, v_i)$（$1 \le u_i,v_i \le n,u_i \neq v_i,0 \le b(u_i,v_i) \le 10^6$），表示边和边权。

# 输出格式

如果存在符合条件的方案，输出一行两个整数，表示整张图减少的点权和的最小值和最大值。

如果不存在，输出 `NIE`.

# 样例

#### 样例输入 1
```plain
3 2
5 10 5
1 2 5
2 3 3
```

#### 样例输出 1
```plain
12 15
```

#### 样例输入 2
```plain
3 3
1 1 1
1 2 1
1 3 1
3 2 1
```

#### 样例输出 2
```plain
NIE
```

# 数据范围与提示

对于 $56\%$ 的数据有 $n \le 2000,m \le 8000$.

对于所有数据有 $1 \le n \le 500\ 000,0 \le m \le 3\ 000\ 000$.


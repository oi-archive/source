
# 题目描述

立方体大作战的游戏规则是这样的：给定一个有 $2n$ 个正整数的栈，每个正整数恰好出现两次。玩家每次可以交换两个相邻的正整数。如果两个相同的正整数相邻，则把这两个数从栈中移除。求最少的交换次数。

# 输入格式

第一行一个整数 $n$。接下来 $2n$ 行以从栈底到栈顶的顺序表示该栈，每行一个正整数 $a_i (1 \le a_i \le n)$。每个正整数恰出现两次，且初始时没有两个相同的正整数相邻。

保证存在不多于 $1\ 000\ 000$ 次交换的解。

# 输出格式

输出最少交换次数以及一组方案。

第一行有一个整数 $m$，表示交换次数。

接下来 $m$ 行每行一个整数 $p_i$，表示将从栈底数起第 $p_i$ 个正整数与第 $p_i+1$ 个正整数交换。

如果有多组解，输出任意一组。

# 样例

#### 样例输入 1
```plain
5
5
2
3
1
4
1
4
3
5
2
```

#### 样例输出 1
```plain
2
5
2
```

#### 样例解释 1
![](/source/loj/2657/img/aHR0cHM6Ly9zemtvcHVsLmVkdS5wbC9wcm9ibGVtc2V0L3Byb2JsZW0vbm9QWS1JTDB2c0FpMlRpWEYtdjJmNUJyL3NpdGUvaW1hZ2VzL09JMTQvdGV0MS5naWY=.gif)

#### 样例输入 2
```plain
3
1
2
3
1
2
3
```

#### 样例输出 2
```plain
3
3
4
2
```
```plain
3
4
3
2
```

#### 样例解释 2
![](/source/loj/2657/img/aHR0cHM6Ly9zemtvcHVsLmVkdS5wbC9wcm9ibGVtc2V0L3Byb2JsZW0vbm9QWS1JTDB2c0FpMlRpWEYtdjJmNUJyL3NpdGUvaW1hZ2VzL09JMTQvdGV0Mi5naWY=.gif)

![](/source/loj/2657/img/aHR0cHM6Ly9zemtvcHVsLmVkdS5wbC9wcm9ibGVtc2V0L3Byb2JsZW0vbm9QWS1JTDB2c0FpMlRpWEYtdjJmNUJyL3NpdGUvaW1hZ2VzL09JMTQvdGV0My5naWY=.gif)

# 数据范围与提示

对于全部数据，$1\le n\le 5\times 10^4,1\le a_i\le n$。


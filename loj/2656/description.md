
# 题目描述

Byteotia 在 $n$ 个村之间送信。村子之间是一个树形结构，任何两个村子之前恰有一条路径，随着经济发展，越来越多的土路被改造成公路。Byteotia 能回忆起他的送信路程和土路改造成公路的过程，你需要帮助 Byteotia 求出他每次行程经过的土路个数。

# 输入格式

第一行一个整数 $n (1 \le n \le 250\ 000)$，表示村庄的个数。

接下来 $n-1$ 行每行两个整数 $a,b$ （$1 \le a \lt b \le n$），表示村庄之间的道路。

接下来一行一个整数 $m (1 \le m \le 250\ 000)$，表示 Byteasar 的行程次数。

接下来 $n + m -1$ 行，按时间顺序给出事件：
* 如果该行为 `A a b` （$a \lt b$），表示 $a$ 和 $b$ 之间的土路被改造成了公路。
* 如果该行为 `B a`，表示 Byteotia 从 $1$ 号村庄到了 $a$ 号村庄。

# 输出格式

输出 $m$ 个整数，表示 Byteotia 每次行程经过的土路个数。

# 样例

#### 样例输入
```plain
5
1 2
1 3
1 4
4 5
4
W 5
A 1 4
W 5
A 4 5
W 5
W 2
A 1 2
A 1 3
```
![](source/loj/2656/img/aHR0cHM6Ly9zemtvcHVsLmVkdS5wbC9wcm9ibGVtc2V0L3Byb2JsZW0vYmlnMk5VRXpoZENxZ0dqMHdHQmpidzE0L3NpdGUvaW1hZ2VzL09JMTQvbWVnemFkMS5naWY=.gif)

#### 样例输出
```plain
2
1
0
1
```

# 数据范围与提示




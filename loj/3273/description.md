
# 题目描述

**题目译自 [JOISC 2020](https://www.ioi-jp.org/camp/2020/2020-sp-tasks/index.html) Day1 T3「[掃除](https://www.ioi-jp.org/camp/2020/2020-sp-tasks/day1/sweeping.pdf) / [Sweeping](https://www.ioi-jp.org/camp/2020/2020-sp-tasks/day1/sweeping-en.pdf)」**

Bitaro 的房间是一个边长为 $N$ 的等腰直角三角形。房间内一点用坐标 $(x,y)$ 表示，其中 $0\le x\le N,0\le y\le N,x+y\le N$。直角顶点为原点，三角形两腰分别为 $x$ 轴与 $y$ 轴。

![sweeping_0.png](/source/loj/3273/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wMy8yMC81ZTc0NjI4NDAzNGI2LnBuZw==.png)

一天，Bitaro 注意到他的房间满是灰尘。初始时，房间内有 $M$ 堆灰尘。第 $i\ (1\le i\le M)$ 堆灰尘位于点 $(X_i,Y_i)$。在同一点可能有多堆灰尘。

现在，Bitaro 打算用扫帚打扫房间。我们认为扫帚是在房间里的一条线段，并且称线段的长度为扫帚的**宽度**。因为 Bitaro 做事很有条理，他只能按如下两种方式使用扫帚：

- Bitaro 将扫帚放在房间里，使得扫帚的一个端点位于原点，并且扫帚平行于 $y$ 轴。然后，他会沿 $x$ 轴正方向水平移动扫帚，直到不能移动为止。在移动过程中，他会保证扫帚始终与 $y$ 轴平行，并且一个端点始终在 $x$ 轴上。如果扫帚宽度为 $l$，则在 $(x,y)$ 位置的灰尘（$x<N-l,y\le l$）将会移动到 $(N-l,y)$（在 $(N-l,y)$ 处可能存在其他堆灰尘）。这个过程称为**过程 H**。
- Bitaro 将扫帚放在房间里，使得扫帚的一个端点位于原点，并且扫帚平行于 $x$ 轴。然后，他会沿 $y$ 轴正方向水平移动扫帚，直到不能移动为止。在移动过程中，他会保证扫帚始终与 $x$ 轴平行，并且一个端点始终在 $y$ 轴上。如果扫帚宽度为 $l$，则在 $(x,y)$ 位置的灰尘（$x\le l,y<N-l$）将会移动到 $(x,N-l)$（在 $(x,N-l)$ 处可能存在其他堆灰尘）。这个过程称为**过程 V**。

在 Bitaro 的房间里，会按顺序发生 $Q$ 个事件。第 $j\ (1\le j\le Q)$ 个事件是以下事件中的一个：

- Bitaro 计算第 $P_j$ 堆灰尘的位置坐标；
- Bitaro 使用宽度为 $L_j$ 的扫帚，进行了过程 H；
- Bitaro 使用宽度为 $L_j$ 的扫帚，进行了过程 V；
- 一堆新灰尘出现在点 $(A_j,B_j)$ 处。如果在这个事件之前一共有 $c$ 堆灰尘，那么这堆灰尘就是房间中的第 $(c+1)$ 堆灰尘。

写一个程序，给出房间的腰长，每一堆灰尘的位置坐标和每个事件的细节，求出要求的某堆灰尘的位置坐标。

# 输入格式

从标准输入读入以下数据，所有输入的值均为整数。

第一行三个整数，分别为 $N,M,Q$。

接下来 $M$ 行，每行两个整数 $X_i,Y_i$，表示第 $i$ 堆灰尘的初始坐标。

接下来 $Q$ 行，每行表示一个事件，有两或三个整数。设 $T_j$ 为第一个整数，每行含义如下：

- 如果 $T_j=1$，则这行有两个整数 $T_j,P_j$。表示 Bitaro 要计算第 $P_j$ 堆灰尘的坐标；
- 如果 $T_j=2$，则这行有两个整数 $T_j,L_j$。表示 Bitaro 用宽度为 $L_j$ 的扫帚进行了过程 H；
- 如果 $T_j=3$，则这行有两个整数 $T_j,L_j$。表示 Bitaro 用宽度为 $L_j$ 的扫帚进行了过程 V；
- 如果 $T_j=4$，则这行有三个整数 $T_j,A_j,B_j$。表示一堆新的灰尘出现在 $(A_j,B_j)$ 位置。

# 输出格式

对于每个 $T_j=1$ 的事件，输出一行两个整数到标准输出。输出在事件 $j$ 发生时第 $P_j$ 堆灰尘的位置坐标。

# 样例

#### 样例输入 1
```plain
6 2 10
1 1
4 0
4 2 3
3 3
1 1
4 1 2
2 3
2 0
1 4
3 2
1 3
1 2
```
#### 样例输出 1
```plain
1 3
3 2
3 3
6 0
```
#### 样例说明 1

初始时，第一堆灰尘位于 $(1,1)$，第二堆灰尘位于 $(4,0)$。图一描述了房间现在的情况。

![sweeping_1.png](/source/loj/3273/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wMy8yMC81ZTc0NjI4MmNjMDVlLnBuZw==.png)

对于第一个事件，第三堆灰尘添加到点 $(2,3)$ 的位置。图二描述了房间现在的情况。

![sweeping_2.png](/source/loj/3273/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wMy8yMC81ZTc0NjI4NDgzYTdmLnBuZw==.png)

对于第二个事件，Bitaro 用宽度为 $3$ 的扫帚进行了过程 V。之后，第一堆灰尘移动到了 $(1,3)$，图三描述了房间现在的情况。

![sweeping_3.png](/source/loj/3273/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wMy8yMC81ZTc0NjI4NTMxMWMwLnBuZw==.png)

对于第三个事件，Bitaro 计算了第一堆灰尘的坐标 $(1,3)$。

对于第四个事件，第四堆灰尘添加到点 $(1,2)$ 的位置。图四描述了房间现在的情况。

![sweeping_4.png](/source/loj/3273/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wMy8yMC81ZTc0NjI4NGNhZGFlLnBuZw==.png)

对于第五个事件，Bitaro 用宽度为 $3$ 的扫帚进行了过程 H。之后，第一堆灰尘移到了 $(3,3)$，第三堆灰尘移到了 $(3,3)$，第四堆灰尘移到了 $(3,2)$。图五描述了房间现在的情况。

![sweeping_5.png](/source/loj/3273/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wMy8yMC81ZTc0NjI4NTgwNDM3LnBuZw==.png)

对于第六个事件，Bitaro 用宽度为 $0$ 的扫帚进行了过程 H。之后，第二堆灰尘移到了 $(6,0)$。图六描述了房间现在的情况。

![sweeping_6.png](/source/loj/3273/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wMy8yMC81ZTc0NjI4NTA5MWUzLnBuZw==.png)

对于第七个事件，Bitaro 计算了第四堆灰尘的坐标 $(3,2)$。

对于第八个事件，Bitaro 用宽度为 $2$ 的扫帚进行了过程 V。没有任何灰尘堆移动。图七描述了房间现在的情况。

![sweeping_7.png](/source/loj/3273/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wMy8yMC81ZTc0NjI4NWI5MWI1LnBuZw==.png)

对于第九个事件，Bitaro 计算了第三堆灰尘的坐标 $(3,3)$。

对于第十个事件，Bitaro 计算了第二堆灰尘的坐标 $(6,0)$。

这组样例满足子任务 1 和子任务 5 的限制。

#### 样例输入 2
```plain
9 4 8
2 3
3 1
1 6
4 3
2 6
1 3
2 2
1 4
2 3
1 2
2 4
1 1
```
#### 样例输出 2
```plain
3 6
4 3
7 1
6 3
```
#### 样例说明 2

这组样例满足子任务 1, 2, 4, 5 的限制。

#### 样例输入 3
```plain
8 1 8
1 5
4 4 1
2 6
1 2
2 3
4 2 2
2 5
1 1
1 3
```
#### 样例输出 3
```plain
4 1
3 5
3 2
```
#### 样例说明 3

这组样例满足子任务 1, 2, 5 的限制。

#### 样例输入 4
```plain
7 4 9
1 5
2 2
4 2
5 0
2 6
2 3
1 2
3 6
1 4
3 1
1 1
2 2
1 3
```
#### 样例输出 4
```plain
4 2
5 1
1 6
5 2
```
#### 样例说明 4

这组样例满足子任务 1, 3, 4, 5 的限制。

#### 样例输入 5
```plain
20 5 25
10 6
0 4
2 1
1 0
2 3
2 18
3 9
4 1 5
4 0 2
3 10
4 3 3
3 3
2 9
4 9 1
3 12
1 4
3 19
1 3
1 9
2 1
1 7
1 6
4 3 3
1 10
1 1
1 5
2 0
1 2
2 2
1 7
```
#### 样例输出 5
```plain
2 17
2 17
9 8
0 17
1 17
3 3
10 10
2 17
2 17
0 17
```
#### 样例说明 5
这组样例满足子任务 1 和子任务 5 的限制。

# 数据范围与提示

对于全部数据，$1\le N\le 10^9,1\le M\le 5\times 10^5,1\le Q\le 10^6$。保证：

- $0\le X_i,Y_i\le N,\ X_i+Y_i\le N\ (1\le i\le M)$；
- $1\le P_j\le M'\ (1\le j\le Q)$，其中 $M'$ 表示当事件 $j$ 发生时灰尘的堆数；
- $0\le L_j\le N-1\ (1\le j\le Q)$；
- $0\le A_j,B_j\le N,\ A_j+B_j\le N\ (1\le j\le Q)$；
- 存在至少一个事件 $T_j=1\ (1\le j\le Q)$。

详细子任务与附加限制如下表：

| 子任务 |                           附加限制                           | 分值 |
| :----: | :----------------------------------------------------------: | :--: |
|  $1$   |            $M\le 2\times 10^3,Q\le 5\times 10^3$             | $1$  |
|  $2$   |                         $T_j=1,2,4$                          | $10$ |
|  $3$   | $T_j=1,2,3,\ X_j\le X_{j+1},\ Y_j\ge Y_{j+1}\ (1\le j\le M-1)$ | $11$ |
|  $4$   |                         $T_j=1,2,3$                          | $53$ |
|  $5$   |                          无附加限制                          | $25$ |




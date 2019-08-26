
# 题目描述

**译自 [ROI 2018](http://neerc.ifmo.ru/school/archive/2017-2018.html) Day1 T4.** ***[Квантовая телепортация](http://neerc.ifmo.ru/school/archive/2017-2018/ru-olymp-roi-2018-day1.pdf) ([Quantum teleportation](http://codeforces.com/gym/102147/problem/C))***

在一个平面直角坐标系上有编号为 $1\dots k$ 的 $k$ 块 CPU。

每块 CPU 的位置可以用平面上的坐标来表示。$1$ 号 CPU 位于 $(1,1)$，$k$ 号 CPU 位于 $(n,m)$。保证所有 CPU 均位于整点上，且对于每块 CPU 的坐标 $(x_i, y_i)$，保证 $1 \le x_i \le n,$ $1 \le y_i \le m$。

$i$ 号 CPU 通过总线将一笔数据传输到 $j$ 号 CPU 的耗时为 ${2^{\large\max(|x_{\normalsize{i}}-x_{\normalsize{j}}|,|y_{\normalsize{i}}-y_{\normalsize{j}}|)}}$ 个单位时间。

试求：要将这笔数据从 $1$ 号 CPU 传送到 $k$ 号 CPU，至少需要多久，另外，请给出：在用时最短的（一组 / 多组）方案中，至少要经过多少块 CPU。

# 输入格式

第一行三个整数 $n,m,k$。  
以下 $k$ 行，每行两个整数 $x,y$。

# 输出格式

第一行一个整数 $L$，表示最快的方案中至少要经过多少块 CPU。  
第二行 $L$ 个整数，表示依次经过的 CPU。

如果存在多组路径使耗时最少，输出任意一种即可。

# 样例

#### 样例输入 1
```plain
4 5 3
1 1
2 3
4 5
```
#### 样例输出 1
```plain
3
1 2 3
```

#### 样例输入 2
```plain
5 6 9
1 1
4 3
4 6
2 5
3 1
3 3
3 6
5 4
5 6
```
#### 样例输出 2
```plain
5
1 6 2 8 9
```

# 数据范围与提示

|任务编号|$n,m,k$|特殊性质|分值|
|:-:|:-:|:-:|:-:|
|$1$|$2 \leq n,m,k \leq 20$||$21$|
|$2$|$2 \leq n,m,k \leq 500$||$13$|
|$3$|$2 \leq n,m,k \leq 10000$|每行、每列只有一个 CPU|$33$|
|$4$|$2 \leq n,m,k \leq 10000$||$33 $|


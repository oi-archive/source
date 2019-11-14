
# 题目描述

**译自 [ROI 2018](http://neerc.ifmo.ru/school/archive/2017-2018.html) Day1 T1.** ***[Добыча радия](http://neerc.ifmo.ru/school/archive/2017-2018/ru-olymp-roi-2018-day1.pdf) ([Extraction of radium](http://codeforces.com/gym/102147/problem/A))***

给一个 $n\times m$ 的矩阵 $a$，矩阵中的数互不相同。  
接下来有 $q$ 次修改，每次修改会将某个值修改为一个更大的值（不是给这个值加一个数！）。保证修改后矩阵中的数仍互不相同。  
每次修改后，请求出：矩阵中有多少个数，既是它所在行的最大值，又是它所在列的最大值。

# 输入格式

第一行三个整数 $n,m,q$ ，表示矩阵的大小与修改操作的次数。  
接下来 $n$ 行，每行 $m$ 个整数，表示该矩阵。  
接下来 $q$ 行，每行三个整数 $x, y, t$ ，表示将该矩阵第 $x$ 行，第 $y$ 列的元素改为 $t$ 。

# 输出格式

$q$ 行，每行一个整数，表示每次修改后，矩阵中有多少个数满足条件。

# 样例

#### 样例输入
```plain
2 3 3
1 4 3
6 5 2
2 2 9
1 3 5
2 2 10
```
#### 样例输出
```plain
1
2
2
```

# 数据范围与提示

对于所有数据，$1\le a(i,j) \le 10^7,$ $1\le t\le 10^7$。

|任务编号|$n,m$|$q$|分值|
|:-:|:-:|:-:|:-:|
|$1$|$1 \leq n \times m \leq 100$|$1 \leq q \leq 100$|&nbsp;$25$&nbsp;|
|$2$|$1 \leq n \times m \leq 5000$|$1 \leq q \leq 5000$|$25$|
|$3$|$1 \leq n,m \leq 400$|&nbsp;$1 \leq q \leq 2\times 10^5$&nbsp;|&nbsp;$25$&nbsp;|
|$4$|$1 \leq n \times m \leq 2\times 10^5$|$1 \leq q \leq 2\times 10^5$|$25$|



# 题目描述

**译自 [COCI 2019/2020 Contest #2](https://hsin.hr/coci/contest2_tasks.pdf) T3「Checker」**

在本题中，我们将研究正 $N$ 边形。这些多边形的各条边都被染成了三种颜色之一，且节点按顺时针编号为 $1$ 到 $N$。一个多边形的三角剖分是将多边形分成多个互不重叠的三角形，且三角形的各边在多边形的边上或对角线上的操作。当然，本题中用于多边形的三角形剖分操作的对角线也被染成了三种颜色之一。

一个多边形的三角剖分被称为三色的剖分当且仅当剖分出来的 $N-2$ 个三角形各边颜色都不同。你的任务是判断一个给定的多边形和它的对角线是否被三角剖分了，以及这个剖分是否是三色的。

# 输入格式

第一行输入测试点类型，详见数据范围与提示。如果你的程序不需要这个信息，请直接读入并忽略它。

第二行一个整数 $N$，含义见题目描述。

第三行一个 $N$ 位整数给出多边形各边的颜色。具体的说，数字的第一位表示边 $(1,~2)$ 的颜色，第二位表示边 $(2,~3)$ 的颜色，以此类推，第 $N$ 位表示边 $(N,1)$ 的颜色。颜色总是以 $1,2,3$ 之一表示。

接下来 $N-3$ 行每行以 $X,Y,C$ 的格式描述一条对角线。其中 $X,Y$ 是多边形的顶点，$C$ 是该边的颜色。保证输入合法，即 $X,Y$ 不相邻不相等。


# 输出格式

如果输入的多边形未被正确地进行三角剖分，请输出 `neispravna triangulacija`，即波兰语中的无效三角剖分；

如果输入的多边形被正确的进行了三角剖分，但是不是三色的，请输出 `neispravno bojenje`，即波兰语中的无效染色；

如果输入的多边形被正确的进行了三角剖分，且输出是三色的，请输出 `tocno`，即波兰语中的正确。

# 样例

#### 样例输入 1

```plain
1
5
12113
1 3 3
2 5 2
```

#### 样例输出 1
```plain
neispravna triangulacija
```

#### 样例解释 1
![fig1](/source/loj/3237/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wMS8wNS81ZTExYjM2OTk5YzU2LmpwZw==.jpg)
#### 样例输入 2

```plain
1
4
1212
1 3 2
```

#### 样例输出 2
```plain
neispravno bojenje
```
#### 样例解释 2
![fig2](/source/loj/3237/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wMS8wNS81ZTExYjM2OTU0NjFiLmpwZw==.jpg)
#### 样例输入 3

```plain
1
7
1223121
1 3 3
3 5 1
5 7 3
7 3 2
```

#### 样例输出 3
```plain
tocno
```
#### 样例解释 3
![fig3](/source/loj/3237/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wMS8wNS81ZTExYjM2OGJjNmExLmpwZw==.jpg)

# 数据范围与提示

子任务 $1$：约占 $10\%$ 的分值，有 $4\le n\le 300$；

子任务 $2$：约占 $16\%$ 的分值，有 $4\le n\le 2\times 10^3$；

子任务 $3$：约占 $21\%$ 的分值，有 $4\le n\le 2\times 10^5$，该子任务中没有答案为无效染色的测试点；

子任务 $4$：约占 $21\%$ 的分值，有 $4\le n\le 2\times 10^5$，该子任务中没有答案为无效三角剖分的测试点；

子任务 $5$：约占 $32\%$ 的分值，有 $4\le n\le 2\times 10^5$。

对于 $100\%$ 的数据，有 $1\le X,Y\le n,~1\le C\le 3$。

与另一题 *[Trobojnica](https://loj.ac/problem/3230)* 不同，本题只要子任务中各测试点输出文件的第一行与标准答案相符即可获得该子任务的全部分数。


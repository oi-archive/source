
# 题目描述

**本题译自 [JOI 2016 Final](https://www.ioi-jp.org/joi/2015/2016-ho/index.html) T4「[縄張り](https://www.ioi-jp.org/joi/2015/2016-ho/2016-ho.pdf)」**

有一个平面直角坐标系。JOI 君位于 $(0, 0)$ 。  
JOI 君**每天**都按照一个固定的程序移动一轮。该程序有 $N$ 个步骤，用一个长度为 $N$ 的字符串 $S$ 描述。这个字符串仅由大写字母 $\texttt{E, N, W, S}$ 构成。  
左数第 $i$ 个字符 $C_i (1\leqslant i\leqslant N)$ 表示 JOI 君会移动到哪里。如果在执行步骤 $i$ 前，JOI 君位于 $(x, y)$：
* $C_i=\texttt{E}$：JOI 君将移动到 $(x+1,y)$；
* $C_i=\texttt{N}$：JOI 君将移动到 $(x,y+1)$；
* $C_i=\texttt{W}$：JOI 君将移动到 $(x-1,y)$；
* $C_i=\texttt{S}$：JOI 君将移动到 $(x,y-1)$。

次日 JOI 君会从他前一天停止的位置开始执行程序。  
JOI 君会把 $(0, 0)$ 以及每个步骤结束后到达的点作标记。开始时 JOI 君没有标记任何点。$K$ 天后，对于任意整数 $a, b$，如果 $(a,b),$ $(a+1,b),$ $(a,b+1),$ $(a+1,b+1)$ 这四个点都被标记了一次或以上，以这四个点为顶点的 $1\times 1$ 的正方形就属于 JOI 君的领地。  
请问 $K$ 天后，JOI 君有多少个领地。

# 输入格式

第一行有两个整数 $N, K$，用空格分隔。  
第二行有一个字符串 $S$，表示 JOI 君移动的程序。

# 输出格式

一个整数，表示 JOI 君有多少个领地。

# 样例

#### 输入样例 1
```plain
12 1
EENWSEEESWWS
```

#### 输出样例 1
```plain
3
```

#### 样例解释 1

<img src="source/loj/2345/img/aHR0cDovL3d3dy56NGEubmV0L2ltYWdlcy8yMDE4LzAyLzE2L0pPSTIwMTZUNC5wbmc=.png" alt="JOI2016T4.png" border="0" width="90%" margin="auto"/>

> 图中的字是之前完整题面的，懒得改了。「市政厅」表示 $(0, 0)$，「散步路径」表示移动路线。  
> 图我没有仔细 PS 过，可能对不齐、不对称，强迫症的同学们麻烦忍一忍


#### 输入样例 2
```plain
12 2
EENWSEEESWWS
```

#### 输出样例 2
```plain
7
```

#### 样例解释 2
样例 2 与样例 1 的不同在于在样例 2 中 JOI 君走了两天。

<img src="source/loj/2345/img/aHR0cDovL3d3dy56NGEubmV0L2ltYWdlcy8yMDE4LzAyLzE2L0pPSTIwMTZUNC0xLnBuZw==.png" alt="JOI2016T4-1.png" border="0" width="40%" margin="auto"/>

#### 输入样例 3
```plain
7 1
ENNWNNE
```

#### 输出样例 3
```plain
0
```

#### 输入样例 4
```plain
16 5
WSESSSWWWEEENNNW
```

#### 输出样例 4
```plain
21
```

# 数据范围与提示

对于所有数据，$1\leqslant N\leqslant 10^5, 1\leqslant K\leqslant 10^9$。

|Subtask #|特殊限制|分值|
|-|-|-|
|1|$N\leqslant 50, K = 1$|5|
|2|$K = 1$|10|
|3|$N\leqslant 50$|23|
|4|无|62|


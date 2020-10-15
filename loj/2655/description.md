
# 题目描述

**译自 POI 2007 Stage 2. Day 1「[Skalniak](https://szkopul.edu.pl/problemset/problem/s5ECsFKlMHti0g29uVkdKlQw/site/?key=statement)」**

Vicomte de Bajteaux 收藏了许多石头并准备把它们放到花园里。

花园是一个正方形，边长为 $1\ 000\ 000\ 000$。Vicomte de Bajteaux 让他的仆人为他用石头布置花园。但他忘记告诉仆人坐标的顺序，以至于一些点的坐标以 $(x,y)$ 的形式给出，一些点的坐标以 $(y,x)$ 的形式给出，并且石头已经按这样的顺序放好了。

为了保护石头，Vicomte de Bajteaux 按照实际的坐标规划了一排栅栏来围住这些石头，使得栅栏的总长最小。为了美观，栅栏必须是平行于坐标轴的矩形。为了让错误不那么明显，你需要帮助仆人选择一部分石头并将它们从 $(x,y)$ 移动到 $(y,x)$，在最小化栅栏的长度的基础上最小化需要移动的石头的总重。

# 输入格式

第一行一个整数 $n (1 \le n \le 1\ 000\ 000)$，表示石头的个数。

接下来 $n$ 行每行三个整数 $x_i, y_i, m_i$（$0 \le x_i,y_i \le 1\ 000\ 000\ 000, 1 \le m_i \le 2\ 000$），表示石头当前所在的坐标和重量。

不会有 $x$ 和 $y$ 组成的无序数对出现超过一次。

# 输出格式

第一行输出两个整数，分别表示栅栏的最小长度和需要移动的石头总重量的最小值。

第二行输出一个长度为 $n$ 的 01 串，表示取到石头总重量最小值的一种移动方案。第 $i$ 个字符为 $1$ 表示需要将第 $i$ 个石头从 $(x_i, y_i)$ 移动到 $(y_i, x_i)$，为 $0$ 则表示不需要。

# 样例

#### 样例输入 1
```plain
5
2 3 400
1 4 100
2 2 655
3 4 100
5 3 277
```
![](https://main.edu.pl/en/images/OI14/skain.gif)

#### 样例输出 1
```plain
10 200
01010
```
![](/source/loj/2655/img/aHR0cHM6Ly9tYWluLmVkdS5wbC9lbi9pbWFnZXMvT0kxNC9za2FvdXQuZ2lm.gif)

# 数据范围与提示





# 题目描述

**译自 [COI 2010](http://hsin.hr/coci/archive/2009_2010/) T3.** ***[LOZA](http://hsin.hr/coci/archive/2009_2010/olympiad_tasks.pdf)***

科学家在南极洲上发现了一个新物种！他们提取了一个样本并带回实验室检测。

他们很快发现这个物种繁殖十分频繁，并且繁殖时只需要一个亲本。然而在该亲本繁殖两次后，它就失去了繁殖能力，不能继续繁殖了。

因此，实验室中样本的数量猛增，对家谱的需求也出现了。

他们决定用简单的文本编辑器，按照以下约定绘制家谱树：

样本名用 `-`，`|` 和 `o` 组成的盒型框框起来。上下边界的中心点用 `+` 标出。如果边界长度为偶数，则 `+` 标在左侧中心点处。

![loza1.png](/source/loj/2975/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wMS8yOC81ZTJmZjhlY2JiMWNiLnBuZw==.png)

这些框会用线进行连接。一条线会连接两个或更多框，连接点位于 `+` 处。亲代位于上方，子代位于下方，框和线不能重叠。

![loza2.png](/source/loj/2975/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wMS8yOC81ZTJmZjhlZDBhMjk1LnBuZw==.png)

如果亲本只有一个子代，则用一个点到点的线进行连接（如最左图），如果有两个子代，则用一条分支线进行连接，**较老的子代放在左侧，较新的子代放在右侧**。

只要左右两侧 `-` 的个数相等，分支线就可以横向延长，**但是不能纵向延长**。

别担心，现在你不需要画出整个家谱树。你只需要求出画出这棵家谱树中需要字符的个数。**空格字符不需要被记入**，只需要计算 `-`，`|`，`+`，`o` 和名字中的字母的个数即可。

# 输入格式

第一行包含一个正整数 $N$，表示实验室中样本的个数；

样本按出生顺序从 $1$ 到 $N$ 编号，最老的样本编号为 $1$，最新的样本编号为 $N$；

接下来 $N$ 行，按出生顺序给出所有样本的信息，每行包含一个字符串和一个数字，分别表示该样本的名称和样本的亲本编号。

# 输出格式

输出一行一个整数，表示绘制这棵家谱树最少要用到的字符数。

# 样例

#### 样例输入 1
```plain
3
adam
kain 1
abel 1
```
#### 样例输出 1
```plain
64
```
#### 样例说明 1

![loza3.png](/source/loj/2975/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wMS8yOC81ZTJmZjhlZDY4YmE0LnBuZw==.png)

#### 样例输入 2
```plain
12
12
anton
ana 1
luka 1
mia 2
tea 3
jakov 3
semiramida 5
dominik 5
anamarija 4
eustahije 4
lovro 2
lovro 11
```
#### 样例输出 2
```plain
371
```
#### 样例说明 2

![loza4.png](/source/loj/2975/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wMS8yOC81ZTJmZjhlZDM2YWU2LnBuZw==.png)

# 数据范围与提示

对于 $50$ 分的数据，$N<30$；

对于 $75$ 分的数据，$N<3\times 10^3$；

对于全部数据，$1\le N\le 3\times 10^5$，样本名称长度不超过 $20$。


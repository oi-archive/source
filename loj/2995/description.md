
# 题目描述

**译自 [JOISC 2015](https://www.ioi-jp.org/camp/2015/2015-sp-tasks/index.html) Day1 T2「[愉快なロゴデザイン](https://www.ioi-jp.org/camp/2015/2015-sp-tasks/2015-sp-d1.pdf) / [En-JOI-able Logo Design](https://www.ioi-jp.org/camp/2015/2015-sp-tasks/2015-sp-d1.pdf)」**

K 理事长想要设计一个应援日本信息学奥林匹克选手的标志。某天，K 理事长想到了用环状排列的 `J`，`O`，`I` 作为标志，希望选手享受 JOI 的比赛。

（注：日语中「円状 JOI」的发音与英文单词 enjoy 相似，故有此意。）

级别为 $k\ (k\ge 0)$ 的 JOI 列定义如下：
- 级别为 $0$ 的 JOI 列是由 `J`，`O`，`I` 字母之一形成的字符串；
- 级别为 $k+1$ 的 JOI 列是这样构造的：最初 $4^k$ 个字母是 `J`，然后 $4^k$ 个字母是 `O`，然后 $4^k$ 个字母是 `I`，最后 $4^k$ 个字符是级别为 $k$ 的 JOI 列，级别为 $k+1$ 的 JOI 列长度为 $4^{k+1}$。

现在，K 理事长写了一个长为 $4^K$ 的环形字符串，字符环只包含 `J`，`O`，`I` 三种字符。K 理事长会修改一些字符，使得从这个环上某一位开始，顺时针读取这个环形字符串一周，能得到一个级别为 $K$ 的 JOI 列。此时，要求最小化修改次数。

现在给出 $K$ 与长度为 $4^K$ 的字符串，现要替换一些字符，使其从环上某位置开始顺时针读取这个字符环，能得到一个 $K$ 级 JOI 列，要求最小化替换字符数。

# 输入格式

第一行一个整数 $K$，表示环上有 $4^K$ 个字符；

第二行一个只包含 `J`，`O`，`I` 的长为 $4^K$ 的字符串，表示从某一个位置顺时针读取字符环一周，会得到这个字符串。

# 输出格式

输出一行，表示 K 理事长替换字符的最少次数。

# 样例

#### 样例输入 1
```plain
1
IJOI
```
#### 样例输出 1
```plain
0
```
#### 样例说明 1
字符形成的环如下图所示：

![logo1.png](/source/loj/2995/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNy8xNC81ZDJhYTZiMzhjMGE1LnBuZw==.png)

以 `J` 为起点顺时针读取一周，形成的字符串为 `JOII`，这是一个级别为 $1$ 的 JOI 列。K 理事长没必要替换字符，所以输出 $0$。

#### 样例输入 2
```plain
2
JJOIJJOJOIOJOOOI
```
#### 样例输出 2
```plain
7
```
#### 样例说明 2
字符形成的环如下图所示：

![logo2.png](/source/loj/2995/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAxOS8wNy8xNC81ZDJhYTZiM2Q4YTA1LnBuZw==.png)

这里需要替换 $7$ 个字符。

从画圈的字符开始读取这个字符环一周，得到 `JJJJOOOOIIIIJOIJ` 字符串，这是一个级别为 $2$ 的 JOI 列，并且是替换次数最少的情况，因此输出 $7$。

# 数据范围与提示

对于全部数据，$1\le K\le 10$。

详细子任务及附加限制如下：
- 子任务 $1$（$30$ 分）：$1\le K\le 5$；
- 子任务 $2$（$70$ 分）：无附加限制。



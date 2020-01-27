
# 题目描述

**译自 POI 2011 Round 3. Day 1. C「[Periodicity](https://szkopul.edu.pl/problemset/problem/H6hUSie6S-cBVL4PG5rqQnmj/site/?key=statement)」**

Bitotia 国外 Byteasar 宣布了要对他臣民的名字进行改革。Bitotia 人的名字经常包含重复的短语，例如名字「Abiabuabiab」中短语「abiab」出现了两次。Byteasar 试图将他的臣民的名字改成和他们之前名字一样长的 $01$ 串。并且他十分希望新名字也能反映之前名字的重复规律。

接下来，为了简化说明，我们将区分字母的大小写。对于任意字符（字母或 $0/1$）序列 $ w = w_1 w_2 \ldots w_k $，如果存在一个整数 $p\ (1 \le p \lt k)$，对于所有 $ i = 1, \ldots, k - p $ 都有 $ w_i = w_{i+p} $，则整数 $p$ 是 $w$ 的一个周期。我们记 $w$ 的所有周期的集合为 $ \mathrm{Per}(w) $。比如，$ \mathrm{Per}(\mathrm{ABIABUABIAB})=\{6, 9\} $，$ \mathrm{Per}(\mathrm{01001010010})=\{5, 8, 10\} $，$ \mathrm{Per}(\mathrm{0000})=\{1, 2, 3\} $。

Byteasar 决定了每个名字都要变成一个满足以下条件的 $01$ 串：
- 长度和原来的名字相同；
- 和之前名字有相同的周期集合；
- 在满足前两个条件的情况下字典序最小。

比如，`ABIABUABIAB` 这个名字应变为 `01001101001`，`BABBAB` 变为 `010010`，`BABURBAB` 变为 `01000010`。

Byteasar 要求你写一个程序，以帮助他将其臣民的名字转换为新名字。如果你成功了，作为奖赏你可以保留你目前的名字！

# 输入格式

第一行包含一个整数 $k$，表示要转换的名字个数；

接下来 $k$ 行，每行一个要转换的名字。每个名字长度都在 $1$ 到 $2\times 10^5$ 之间，并且只包含英文大写字母。


# 输出格式

输出 $k$ 行，每行包含一个 $01$ 串，如果存在一个合法的转换方案，则输出字典序最小的一个，否则输出 `XXX`。

# 样例

#### 样例输入
```plain
3
ABIABUABIAB
BABBAB
BABURBAB
```
#### 样例输出
```plain
01001101001
010010
01000010
```


# 数据范围与提示

对于全部数据，$ 1 \le k \le 20 $

对于 $30$ 分的数据，每个名字最多只包含 $20$ 个字母。

Task author: Wojciech Rytter.

---

注：对于 $01$ 串 $ x_1 x_2 \ldots, x_k $，它的字典序比 $01$ 串 $ y_1 y_2 \ldots y_k $ 小，当且仅当 $\exists i\in [1,k]$，有 $x_i\lt y_i$ 且对于 $j=1,\ldots ,i-1$ 有 $x_j=y_j$。



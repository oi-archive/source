
# 题目描述

**译自 POI 1997 Round II Day1 T2「[Genotype](https://szkopul.edu.pl/problemset/problem/8ypWiVSa6VWalvgaIBy5dVR1/site/?key=statement)」**

Genotype 是一个有限的基因序列。它是由大写的英文字母 $A\sim Z$ 组成，不同的字母表示不同种类的基因。一个基因可以分化成为一对新的基因。这种分化被一个定义的规则集合所控制。每个分化的规则可以用三个大写字母 $A_1 A_2 A_3$ 表示，含义为基因 $A_1$ 可以分化成 $A_2 A_3$。

我们用 $S$ 代表特种基因，繁殖 Genotype 是从特种基因序列开始。根据给定的规则，它由被选择控制规则对基因不断进行繁殖而成。 

读入一个定义的规则集和一个想生成的 Genotypes 单词序列 。

对每一个给定的 Genotype，根据给定的分化规则，检查是否它能从某一个确定特种基因序列生成，如果能，输出最小的序列长度。

# 输入格式

第一行有一个整数 $n,$ $1 \le n \le 10000$。

下面 $n$ 行中，每一行为一个分化规则。这些规则都由包含 $A\sim Z$ 的三个大写字母组成。

接下来有一个整数 $k,$ $1 \le k \le 10000$。 接下来的 $k$ 行有一个 Genotype。Genotype 由没有空格的单词组成，最多 $100$ 个英文大写字母。

# 输出格式

有 $k$ 行，在第 $I$ 行应写入：一个正整数――需要生成第 $I$ 个 genotypes 的最小长度；

或者单词 `NIE`, 如果不能生成对应的 genotype。

# 样例

#### 样例输入
```plain
6
SAB
SBC
SAA
ACA
BCC
CBC
3
ABBCAAABCA
CCC
BA
```

#### 样例输出
```plain
3
1
NIE
```

#### 样例说明
$S\to AB,$ $S\to AA,$ $A\to CA,$ $C\to BC,$ 此时产生的序列是 $ABBCAA$。 
$S\to AA,$ $A\to CA,$ 此时产生的序列为 $ACA$。  
再使用 $C\to BC,$ 此时产生序列为 $ABCA$。  
$3$ 个 $S$ 出发的规则可以产生出如下序列 $ABBCAAABCA$。

# 数据范围与提示

<del>本题数据不满（实际只有 $1000$ ~ $2000$），但是请尝试优化掉 $26^2$。</del>（优化掉好像更慢）




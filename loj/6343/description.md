
# 题目描述

当 Sally Face 和一行人发现了波隆那香肠的真实成分后，情况空前严峻险恶，可他们却又不能去相信腐败不堪的警局，惩罚杀人凶手的任务落到了这几个高中生的肩上。这时， Ashley 发现了隐藏的输送管道，却不小心摔入了深不见底的管道。Sally Face 的超自然本能指引着一行人发现了爱迪生大楼隐秘的地牢……

在破败尘封的地牢大门前，赫然刻着那代表邪恶力量的符号，Sally Face 走向角落里一本封面是一只鸟的古代书籍：

「地牢面对凡人的呼唤，会投以邪恶的灵魂，只有正确回答了所有询问：从某个圆点 $ S_i ​$ 开始到某个圆点 $ T_i ​$ 结束，路径长度 $ \leq k ​$ 的不同路径的 __路径长度的 $ r_i ​$ 次方和__ 为多少 ，无法全部回答的人将永远被诅咒……」

Sally Face 看了看地牢大铁门前的地砖，上面的圆点和边构成了一张错综复杂的图，他发现每一条边的长度都为 $ 1 $ ，且任意两点 $u,v$ （由于地牢的时空扭曲，存在 $u,v$ 使得 $u=v$ ）间可能存在多条边，而右边是密密麻麻的古老的文字。

「Todd , 你试一试能不能解开这个谜团……」

# 输入格式

第一行五个正整数 $ n $ , $ m $ , $ r $ , $ k $ , $ q $ 。

$ n $ 为地砖上的圆点数，$ m $ 为连接圆点的边的数量，$ q $ 为询问的个数，$ r $ 为询问中 $ r_i $ 的最大值, $ k $ 见题目描述。

下面给出 $ m $ 行，每行两个正整数 $ u $ , $ v $ ，表示圆纹 $ u $ , $ v $ 间存在一条边。

之后给出 $ q $ 行询问，每行三个正整数 $ S_i $ , $ T_i $ , $ r_i\,(1\leq i \leq q)$ 如题目描述。

# 输出格式

对于每个询问，输出一行一个数字，表示询问的答案。

由于这个答案可能很大，只用输出这个数字対 $1004535809 $ 取模后的结果。

# 样例

#### 样例输入
```plain
4 3 3 4 2
1 2
3 2
2 4
3 4 2
1 2 3
```

#### 样例输出
```plain
52
82
```
#### 样例解释
![sally.png](/source/loj/6343/img/aHR0cHM6Ly9lbmtlcmV3cG8uZ2l0aHViLmlvL2ltYWdlcy9zYWxseS5wbmc=.png)

__询问 $1$__ ：

从 $3$ 到 $4$ 有 $1$ 条长度为 $2$ 的路径：①$(3\rightarrow 2\rightarrow 4)$，有 $3$ 条长度为 $4$ 的路径：
①$(3\rightarrow 2\rightarrow 1\rightarrow 2\rightarrow 4)$
②$(3\rightarrow 2\rightarrow 3\rightarrow 2\rightarrow 4)$
③$(3\rightarrow 2\rightarrow 4\rightarrow 2\rightarrow 4)$

$\therefore 1\times 2^2+3\times 4^2=4+48=52$ 。

__询问 $2$__ ：

从 $1$ 到 $2$ 有 $1$ 条长度为 $1$ 的路径：①$(1\rightarrow 2)$，有 $3$ 条长度为 $3$ 的路径：
①$(1\rightarrow 2\rightarrow 3\rightarrow 2)$
②$(1\rightarrow 2\rightarrow 1\rightarrow 2)$
③$(1\rightarrow 2\rightarrow 4\rightarrow 2)$ 

$\therefore 1\times 1^3+3\times 3^3=1+81=82$ 。

# 数据范围与提示

#### 数据范围
对于 $ 100\% $ 的数据，有 $n=5$,  $1\leq m \leq 10^4$,  $0\leq r_i \leq 1000$,  $1\leq k \leq 10^{9}$,  $1\leq q \leq 25000$，且数据保证随机。

#### 提示
由于地牢的时空扭曲是常人无法理解的，所以不存在一条长度为 $0$ 的路径 $(u\rightarrow v)$，其中 $u=v$。


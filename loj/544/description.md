
# 题目描述

> Are you going to solve poisonous problems?

> \- Thanks a lot for today's poisonous problems.

> What are you doing at the end of the world? Are you busy? Will you save us?

> Ithea and Chtholly want to play a game in order to determine who will solve poisonous problems.

> \- Willem...

> Lakhesh loves to make poisonous problems, so Nephren helps her run a cinema. We may call it No. 68 Cinema.

> \- I... I survived.

如题目背景所述，这是一道 PSP（Poisonous String Problem，毒瘤字符串题）。

对于一个正整数 $k$，若任何一个 $1\sim n$ 的排列均是某个字符集大小不超过 $k$ 的字符串的后缀排名数组（后缀排名数组即后缀数组的**逆排列**，如果你不知道什么是后缀数组，可以自行搜索或参考[Wiki 对后缀数组的介绍](https://en.wikipedia.org/wiki/Suffix_array)），则称 $k$ 对于 $n$ 是毒瘤的。给定 $k$，你需要找到一个最小的正整数 $n$ 使 $k$ 对于 $n$ 不是毒瘤的，并且你需要给出 $1\sim n$ 的一个排列，其不是任何一个字符集大小不超过 $k$ 的字符串的后缀排名数组。如果有多个排列，输出字典序最小的，如果不存在这样的 $n$ 和排列，输出 `213`。

[1]:[QQ图片20171217200716.jpg](https://i.loli.net/2017/12/17/5a365e215e89b.jpg)

# 输入格式

输入仅包含一个正整数 $k$。

# 输出格式

输出包含一至两行。

若无解，输出一行一个字符串 `213`。

若有解，第一行包含一个正整数 $n$，之后一行 $n$ 个空格隔开的正整数表示排列。

# 样例

#### 样例输入
```plain
1
```

#### 样例输出
```plain
2
1 2
```

字符集为 $1$，长也为 $1$ 的字符串 `a` 的后缀排名数组为 $1$，包含了所有长为 $1$ 的排列，所以 $k=1$ 对于 $n=1$ 是毒瘤的。

字符集为 $1$，长为 $2$ 的唯一一个字符串 `aa` 的后缀排名数组为 $\{2,1\}$，故 $\{1,2\}$ 不是任何字符集为 $1$ 的字符串的后缀排名数组，所以 $k=1$ 对于 $n=2$ 不是毒瘤的，且 $\{1,2\}$ 是此时唯一不是后缀排名数组的排列，也是此时满足条件的字典序最小的排列。

# 数据范围与提示

对于所有数据，$1 \leq k \leq 10^5$。

详细的数据限制及约定如下（留空表示和上述所有数据的约定相同）：

|Subtask #|分值|$k$|
|:-:|:-:|:-:|
|$1$|$7$|$\leq 9$|
|$2$|$16$|$\leq 16$|
|$3$|$19$|$\leq 43$|
|$4$|$25$|$\leq 700$|
|$5$|$33$|$\leq 10^5$|

[1]:[b.png](http://codeforces.com/predownloaded/5b/c5/5bc5122574e611f6c03f9a615f22e939390e90d1.png)
[1]:[c.png](http://codeforces.com/predownloaded/b1/f8/b1f8c486967b50eedc6972dc2ecef18cdfd7d52d.png)
[1]:[a.png](http://codeforces.com/predownloaded/03/19/03197c7c57d21a9b79bfe7685133f9bbc92303ed.png)
[1]:[d.png](http://codeforces.com/predownloaded/42/cf/42cf0d5a9c285cd0c321d83fd5473977f10a6973.png)

[1]:[毒瘤.jpg](https://i.loli.net/2017/12/10/5a2d4c85e1457.jpg)




# 题目描述

**题目译自 [POI XXVII - I etap](https://sio2.mimuw.edu.pl/c/oi27-1/dashboard/) 「[Pisarze](https://szkopul.edu.pl/problemset/problem/v2Y2_UW56ENMcbwP22tkTb7a/site/)」**

给出一行波兰语文本，已知这段文本来自于以下三本书之一：

+ Adama Mickiewicza 所著的 *Pan Tadeusz*。

+ Henryka Sienkiewicza 所著 *Quo Vadis*。

+ Bolesława Prusa 所著的 *Lalka*。

请你写一个程序判断这行文本来自于哪本书。

# 输入格式

输入数据第一行包含一个整数 $T$，表示测试数据组数。对于每组测试数据：

第一行包含一段波兰语文本，由 $10$ 到 $2000$ 个单词组成。这一行的开头或者结尾都是一个完整的单词或者标点符号。

保证输入的所有文本长度之和不超过 $2 \cdot 10^6$。

# 输出格式

对于每组数据，输出 `Mickiewicz`，`Prus` 或者 `Sienkiewicz`，表示这行文本所在书的作者。

# 样例

#### 样例输入

```plain
3
Petroniusz obudzil sie zaledwie kolo...
Litwo! Ojczyzno moja! ty jestes jak...
W poczatkach roku 1878, kiedy swiat...
```

#### 样例输出

```plain
Sienkiewicz
Mickiewicz
Prus
```

#### 提示

样例输入并不完整，被截断了一部分。

# 数据范围与提示

这题的代码长度不能超过 $10$ KB。

这是一个数据分析题，你的程序不需要准确的识别每组数据。评分标准如下：

+ 令 $ T $ 是测试数据组数。

+ 令 $ P $ 是选手程序识别对的数据组数。

+ 如果 $ P \ge 0.9 \cdot T$，那么选手会获得 $ 100\%$ 的分数。

+ 如果 $ P \le \frac{T}{3} $，选手会获得 $ 0 \%$ 的分数。

+ 否则，选手获得的分数为 $100 \cdot \frac{P- \frac{T}{3}}{0.9 \cdot T - \frac{T}{3}} \%$。

每个测试数据的文本来自于提供的文本，同时还附赠了一个脚本 `pistestgen.py`，可以从附加文件或者[这里下载](https://sio2.mimuw.edu.pl/c/oi27-1/ca/201/)。用命令 `python3 pistestgen.py subtask name directory [seed]` 即可生成一组数据，其中：

- `subtask` 是子任务编号，一个从 $1$ 到 $4$ 的整数。

- `name` 是测试数据的名字，这个脚本会生成 `name.in` 和 `name.out` 这两个文件。

- `directory` 是包含这三本书的文件夹路径。

- `seed` 是可以不加的字符串，用于生成同一组数据（两次程序如果 `seed` 值是一样，那么生成的数据也是一样的）。

所有的测试数据保证也是通过这个程序生成的。

| Subtask # | 额外限制                                | 分值  |
|:---------:|:-----------------------------------:|:---:|
| 1         | $T \le 100$，每行包含 $500$ 到 $2000$ 个单词 | 20  |
| 2         | $T \le 1000$，每行都是由完整的句子组成           | 20  |
| 3         | $T \le 1000$，每行包含 $30$ 到 $80$ 个单词   | 30  |
| 4         | $T \le 1000$                        | 30  |


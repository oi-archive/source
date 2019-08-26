
# 题目描述

Victor 正在使用 vim 编辑他的文章，他的文章只包含 `abcdefghij` 这 $10$ 个字母，他想把他文章中所有的 `e` 都删除。Victor 并不是很熟悉 vim，它只懂得下面几个操作：
* `x`：删除光标所在的字母，光标位置不变。
* `h`：光标向左移。如果已经是行首就不会移。
* `f`：后面还会跟一个字母 c，表示跳到下一个字母 c 的位置。如果不存在那么就不会跳。

悲剧的是 Victor 的键盘上 `e` 按键突然坏掉了……请问：Victor 最少需要按多少个键才能把所有的 `e` 删除。

例如，如果当前的文本是 `jeff[i]ehadabigidea`，则
* `x` 操作后文本将变为 `jeff[e]hadabigidea`
* `h` 操作后文本将变为 `jef[f]iehadabigidea`
* `fi` 操作后文本将变为 `jeffiehadab[i]gidea`

# 输入格式

第一行有一个整数 $N(N \le 7\times 10^4)$，表示文章长度。  
第二行有一个字符串，表示文章。文章只包含小写 `abcdefghij`。第一个字母和最后一个字母保证不是 `e`。

# 输出格式

Victor 最少需要按多少个键才能把所有的 `e` 删除。

# 样例

#### 样例输入
```plain
35
chefeddiefedjeffeachbigagedegghehad
```

#### 样例输出
```plain
36
```

#### 样例解释
`fdhxhhxffhxfahxhhhxhhhxfdhxfghxfahhx`

# 数据范围与提示

对于 $50\%$ 的测试数据，$N \le 500$。  
对于另外 $10\%$ 的测试数据，$N \le 5000$。  
对于所有测试数据，$N \le 7\times 10^4$。

翻译来自 abcdabcd987。


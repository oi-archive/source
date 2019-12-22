
# 题目描述

LiuRunky 希望成为学园偶像，于是在努力练习唱歌。最近，他正在挑战二刺螈歌曲。由于对日语一窍不通，他选择通过背罗马音来记歌词。

罗马音是一种对于文字的注音方式。在很多情况下，罗马音的发音和汉语拼音十分类似。这对于在一年级语文期末考试取得满分的 LiuRunky 来说轻轻松松。

但是在练习时长达到两天半的时候，他发现了一个很严重的问题：对于一些**特殊情况**，罗马音的读音和拼音存在一些差距。为了将问题简化，可以概括为“su 读 si，si 读 xi，r 读 l，ti 读 qi”（日语大佬勿喷）。也就是说，若原文中的一个字为 "su"，将其替换为 "si"；若原文中的一个字为 "si"，将其替换为 "xi"；若原文中的一个字为 "ti"，将其替换为 "qi"；将原文中**所有地方**出现的 "r" 替换为 "l"。用空格隔开的每个部分为一个字，比如字符串 "a b c abc" 中共有 $4$ 个字，分别为 "a"，"b"，"c"，"abc"。

LiuRunky 的反应能力很差，所以需要你帮忙将原来的罗马音歌词替换为能完全用拼音发音的形式。

# 输入格式

第一行输入一个正整数 $n(1\leq n\leq 5)$，表示罗马音歌词的总行数。

接下来 $n$ 行，每行输入一个字符串 $s$。

数据保证 $s$ 仅由小写字母和空格组成，其中空格不会连续出现、不会出现在 $s$ 的开头或结尾，且 $\sum |s|\leq 5\times 10^4$。($|s|$ 表示字符串 $s$ 的长度)

# 输出格式

一共输出 $n$ 行。每一行为转换后的歌词。

# 样例

#### 样例输入

````plain
5
sky arrow
ya ri ma su ne
sei i ja ku wa ro man ti kku
sen bon za ku ra yo ru ni ma gi re
ki bou no ha na tsu na i da ki zu na wo
````

#### 样例输出

````plain
sky allow
ya li ma si ne
sei i ja ku wa lo man qi kku
sen bon za ku la yo lu ni ma gi le
ki bou no ha na tsu na i da ki zu na wo
````

# 数据范围与提示





# 题目描述

在字体排印学中，“川流”是由单词之间的间隙组成的连续几列的空格。如图所示为几个用红色高亮标出的“川流”（文本被有意模糊处理来凸显川流）：

![流](source/loj/6408/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMDUvMjAvNWIwMTM1NzVhM2VlNC5wbmc=.png)

知名川流机构 Flo Ng 希望他在新的关于世界河流的书上出现尽可能长的川流。他会使用一种单一字宽的字体（每个字母和空格都具有相同的宽度）且左对齐，单词之间恰用一个空格分隔。对 Flo 来说，一条“川流”指的是连续几行里的空格，且相邻空格在行里出现的位置的距离不超过 $1$。川流不能包含末尾的空格。每行的单词都必须尽可能地紧凑，但不能有单词被拆到两行里。行宽至少不能短于文本中最长的一个单词。下图是同一个文本使用不同行宽的一个例子。

![2018-05-20 16-55-13 的屏幕截图.png](source/loj/6408/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMDUvMjAvNWIwMTM4MDNkMWNmZS5wbmc=.png)

给定文本，你需要求出一个行宽使得该文本最长的川流尽可能长。

# 输入格式

第一行有一个整数 $n (2 \le n \le 2500)$ 表示文本的单词个数。接下来几行为该文本的单词。每个单词都只包含大写和小写字母，且长度不超过 $80$ 个字符。

# 输出格式

输出两个整数，分别表示使得文本出现最长的川流的行宽以及川流的长度。如果有多个行款达到川流长度的最大值，输出最小的行宽。

# 样例

#### 样例输入 1
```plain
21
The Yangtze is the third longest
river in Asia and the longest in
the world to flow
entirely in one country
```

#### 样例输出 1
```plain
15 5
```

#### 样例输入 2
```plain
25
When two or more rivers meet at
a confluence other than the sea
the resulting merged river takes
the name of one of those rivers
```


#### 样例输出 2
```plain
21 6
```

# 数据范围与提示

在不侵犯原题版权的情况下，本题面中文翻译基于[知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议](http://creativecommons.org/licenses/by-nc-sa/4.0/)发布，注明出处时需指向本题链接。


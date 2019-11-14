
# 题目描述

**译自 POI 2011 Round 3. Day 1. C「[Periodicity](https://szkopul.edu.pl/problemset/problem/H6hUSie6S-cBVL4PG5rqQnmj/site/?key=statement)」**

Byteasar, the king of Bitotia, has ordained a reform of his subjects' names. The names of Bitotians often contain repeating phrases, e.g., the name Abiabuabiab has two occurrences of the phrase abiab. Byteasar intends to change the names of his subjects to sequences of bits matching the lengths of their original names. Also, he would very much like to reflect the original repetitions in the new names.

In the following, for simplicity, we will identify the upper- and lower-case letters in the names. For any sequence of characters (letters or bits) $ w = w_1, w_2, \ldots, w_k $ we say that the integer $ p $ ($ 1 \le p \lt k $) is a period of $ w $ if $ w_i = w_{i+p} $ for all $ i = 1, \ldots, k - p $. We denote the set of all periods of $ w $ by $ \mathrm{Per}(w) $. For example, $ \mathrm{Per}(\mathrm{ABIABUABIAB})=\{6, 9\} $, $ \mathrm{Per}(\mathrm{01001010010})=\{5, 8, 10\} $, and $ \mathrm{Per}(\mathrm{0000})=\{1, 2, 3\} $.

Byteasar has decided that every name is to be changed to a sequence of bits that:

* has length matching that of the original name,
* has the same set of periods as the original name,
* is the smallest (lexicographically1) sequence of bits satisfying the previous conditions.

For example, the name `ABIABUABIAB` should be changed to `01001101001`, `BABBAB` to `010010`, and `BABURBAB` to `01000010`.

Byteasar has asked you to write a program that would facilitate the translation of his subjects' current names into new ones. If you succeed, you may keep your current name as a reward!


# 输入格式

In the first line of the standard input there is a single integer $ k $- the number of names to be translated ($ 1 \le k \le 20 $). The names are given in the following lines, one in each line. Each name consists of no less than $ 1 $ and no more than $ 200000 $ upper-case (capital) letters (of the English alphabet).

In the test worth $ 30\% $ of the points each name consists of at most $ 20 $ letters.


# 输出格式

Your program should print $ k $ lines to the standard output. Each successive line should hold a sequence of zeroes and ones (without spaces in between) corresponding to the names given on the input. If an appropriate sequence of bits does not exists for some names, then "XXX" (without quotation marks) should be printed for that name.


# 样例

For the input data:
```plain
3
ABIABUABIAB
BABBAB
BABURBAB
```
the correct result is:
```plain
01001101001
010010
01000010
```
The sequence of bits $ x_1, x_2, \ldots, x_k $ is lexicographically smaller than the sequence of bits $ y_1 y_2 \cdots y_k $ if for some $ i $, $ 1 \le i \le k $, we have $ x_i \lt y_i $ and for all $ j = 1, \ldots, i - 1 $ we have $ x_j = y_j $.


# 数据范围与提示

Task author: Wojciech Rytter.


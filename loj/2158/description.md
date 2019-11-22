
# 题目描述

**译自 POI 2011 Round 1. D「[Shift](https://szkopul.edu.pl/problemset/problem/n6S4y9QrbGqYUz64e2O-OV7D/site/?key=statement)」**

Byteasar bought his son Bytie a set of blocks numbered from $ 1 $ to $ n $ and arranged them in a row in a certain order. Bytie's goal is to rearrange the blocks so that they are ordered naturally, from the smallest number to the largest. However, the only moves Bytie is allowed to make are:

* putting the last block at the very beginning (move `a`), and
* putting the third block at the very beginning (move `b`).

Help Bytie by writing a program that tells whether a given arrangement of blocks can be properly reordered, and tells the right sequence of moves if it is.

Byteasar 给他的儿子 Bytie 买了一盒共 $ n $ 块积木，他将这些积木从 $ 1 $ 到 $ n $ 编号，并按照一定的顺序摆成一排。Bytie 要将这些积木按照编号从小到大的顺序重新排列，但他只能做下面两种操作：

* 操作 a：将最后一个积木移到最前面。
* 操作 b：把第三个积木移到最前面。

我们将连续进行 $ k $ 次同一个操作称为“一块操作”，表示为 $ k a $ 或 $ k b $。  
你需要帮助 Bytie 写一个程序，告诉他有没有一个操作序列能够使积木按照编号从小到大的顺序重新排列，并告诉他操作序列。


# 输入格式

In the first line of the standard input there is a single integer $ n $, $ 1 \le n \le 2000 $. In the second line there are $ n $ integers from the range to $ 1 $, $ n $ separated by single spaces. No number appears twice, and thus they represent the initial arrangement of the blocks.

输入的第一行包含一个整数 $ n $，表示积木的个数。
第二行包含 $ n $ 个整数，表示积木初始的排列顺序，没有重复的数字。


# 输出格式

If there is no sequence of moves leading to an arrangement with increasing blocks' numbers, your program should print out "`NIE DA SIE`" (there is no way in Polish), without the quotation marks.

Otherwise there should be a single integer $ m $($ m \le n^2 $), denoting the number of operations, in the first line. An operation is a $ k $-fold execution of either `a` or `b` move.

If $ m \gt 0 $, then there should be a sequence of $ m $ integers with either a or b appended in the second line. Thus $k a$(for $ 0 \lt k \lt n $) denotes the $ k $-fold execution of the move `a`. Analogously, $ k b $(for $ 0 \lt k \lt n $) denotes the $ k $-fold execution of the move `b`.

Furthermore, the characters appended to the numbers in the second line have to alternate.

Should there be more than one solution, your program is free to pick one arbitrarily.

如果没有一种方案能将积木按照编号从小到大的顺序重新排列，你应当输出 `NIE DA SIE`（波兰语中的 `There is no way`）。

否则，第一行你应当输出一个整数 $ m $，表示操作的**块数**，$ m $ 必须满足 $ m \lt n^2 $。  
第二行表示这 $ m $ 块操作，每块操作之间用空格隔开。  
每一块包含操作数 $ k $ 和操作方式，中间**没有**空格，如 `3a`（ $ 3 $ 次 a 操作）。  
需要满足相邻两块操作的种类不同，每块操作中进行的次数 $ 0 \lt k \lt n $。


# 样例

#### 输入样例1
```plain
4
1 3 2 4
```

#### 输出样例1
```plain
4
3a 2b 2a 2b
```
#### 输入样例2
```plain
7
1 3 2 4 5 6 7
```

#### 输出样例2
```plain
NIE DA SIE
```
#### 输入样例3
```plain
3
1 2 3
```
#### 输出样例3
```plain
0
```


# 数据范围与提示

对于 $ 100\% $ 的数据，$ 1 \le n \le 2000 $。

Task authors: Krzysztof Diks & Wojciech Rytter.  
翻译和 SPJ: ceba.


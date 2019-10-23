
# 题目描述

智慧珠游戏拼盘由一个三角形盘件和 $12$ 个形态各异的零件组成。拼盘的盘件如图 $1$ 所示：

![](/source/guoj/1243/img/aHR0cHM6Ly93d3cud2p5eXkudG9wL3dwLWNvbnRlbnQvdXBsb2Fkcy8yMDE5LzA2LzAxLnBuZw==.png)

$12$ 个零件按珠子数分 $3$ 大类：

第 $1$ 大类，有三个珠子，只有一种形状。

符号为 **`A`**，形状为![](/source/guoj/1243/img/aHR0cHM6Ly93d3cud2p5eXkudG9wL3dwLWNvbnRlbnQvdXBsb2Fkcy8yMDE5LzA2LzAyLnBuZw==.png)

第 $2$ 大类，有 $4$ 个珠子，有 $3$ 种形状。

符号为 **`B`**，形状为![](/source/guoj/1243/img/aHR0cHM6Ly93d3cud2p5eXkudG9wL3dwLWNvbnRlbnQvdXBsb2Fkcy8yMDE5LzA2LzAzLnBuZw==.png)

符号为 **`C`**，形状为![](/source/guoj/1243/img/aHR0cHM6Ly93d3cud2p5eXkudG9wL3dwLWNvbnRlbnQvdXBsb2Fkcy8yMDE5LzA2LzA0LnBuZw==.png)

符号为 **`D`**，形状为![](/source/guoj/1243/img/aHR0cHM6Ly93d3cud2p5eXkudG9wL3dwLWNvbnRlbnQvdXBsb2Fkcy8yMDE5LzA2LzA1LnBuZw==.png)

第 $3$ 大类，有 $5$ 个珠子，有 $8$ 种形状。

符号为 **`E`**，形状为![](/source/guoj/1243/img/aHR0cHM6Ly93d3cud2p5eXkudG9wL3dwLWNvbnRlbnQvdXBsb2Fkcy8yMDE5LzA2LzA2LnBuZw==.png)

符号为 **`F`**，形状为![](/source/guoj/1243/img/aHR0cHM6Ly93d3cud2p5eXkudG9wL3dwLWNvbnRlbnQvdXBsb2Fkcy8yMDE5LzA2LzA3LnBuZw==.png)

符号为 **`G`**，形状为![](/source/guoj/1243/img/aHR0cHM6Ly93d3cud2p5eXkudG9wL3dwLWNvbnRlbnQvdXBsb2Fkcy8yMDE5LzA2LzA4LnBuZw==.png)

符号为 **`H`**，形状为![](/source/guoj/1243/img/aHR0cHM6Ly93d3cud2p5eXkudG9wL3dwLWNvbnRlbnQvdXBsb2Fkcy8yMDE5LzA2LzA5LnBuZw==.png)

符号为 **`I`**，形状为![](/source/guoj/1243/img/aHR0cHM6Ly93d3cud2p5eXkudG9wL3dwLWNvbnRlbnQvdXBsb2Fkcy8yMDE5LzA2LzEwLnBuZw==.png)

符号为 **`J`**，形状为![](/source/guoj/1243/img/aHR0cHM6Ly93d3cud2p5eXkudG9wL3dwLWNvbnRlbnQvdXBsb2Fkcy8yMDE5LzA2LzExLnBuZw==.png)

符号为 **`K`**，形状为![](/source/guoj/1243/img/aHR0cHM6Ly93d3cud2p5eXkudG9wL3dwLWNvbnRlbnQvdXBsb2Fkcy8yMDE5LzA2LzEyLnBuZw==.png)

符号为 **`L`**，形状为![](/source/guoj/1243/img/aHR0cHM6Ly93d3cud2p5eXkudG9wL3dwLWNvbnRlbnQvdXBsb2Fkcy8yMDE5LzA2LzEzLnBuZw==.png)

![](/source/guoj/1243/img/aHR0cHM6Ly93d3cud2p5eXkudG9wL3dwLWNvbnRlbnQvdXBsb2Fkcy8yMDE5LzA2LzE0LnBuZw==.png)

图 $2$ 示出了一种拼盘方案。为便于描述可将图 $2$ 抽象为图 $3$，就可以用一个数据为字符的二维数组来表示了。

![](/source/guoj/1243/img/aHR0cHM6Ly93d3cud2p5eXkudG9wL3dwLWNvbnRlbnQvdXBsb2Fkcy8yMDE5LzA2LzE1LnBuZw==.png)

对于由珠子构成的零件，可以放到盘件的任一位置，条件是能有地方放，且尺寸合适，所有的零件都允许旋转($0^\circ$、$90^\circ$、$180^\circ$、$270^\circ$)和翻转(水平、竖直)。

现给出一个盘件的初始布局，求一种可行的智慧珠摆放方案，使所有的零件都能放进盘件中。

# 输入格式

输入中包含初始的盘件描述，一共有 $10$ 行，第 $i$ 行有 $i$ 个字符。如果第 $i$ 行的第 $j$ 个字符是字母“**`A`**”至”**`L`**”中的一个，则表示第 $i$ 行第 $j$ 列的格子上已经放了零件，零件的编号为对应的字母。如果第 $i$ 行的第 $j$ 个字符是“**`.`**”，则表示第 $i$ 行第 $j$ 列的格子上没有放零件。

输入保证预放的零件已摆放在盘件中。

# 输出格式

如果能找到解，向输出文件打印 $10$ 行，为放完全部 $12$ 个零件后的布局。其中，第 $i$ 行应包含 $i$ 个字符，第 $i$ 行的第 $j$ 个字符表示第 $i$ 行第 $j$ 列的格子上放的是哪个零件。

如果无解，输出单独的一个字符串“**`No solution`**”(不要引号，请注意大小写)。

所有的数据保证最多只有一组解。

# 样例

#### 输入样例
```plain
.
..
...
....
.....
.....C
...CCC.
EEEHH...
E.HHH....
E.........
```

#### 输出样例
```plain
B
BK
BKK
BJKK
JJJDD
GJGDDC
GGGCCCI
EEEHHIIA
ELHHHIAAF
ELLLLIFFFF
```

# 数据范围与提示




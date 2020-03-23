
# 题目描述

**题目译自 [JOISC 2020](https://www.ioi-jp.org/camp/2020/2020-sp-tasks/index.html) Day3 T1「[星座 3](https://www.ioi-jp.org/camp/2020/2020-sp-tasks/day3/constellation3.pdf) / [Constellation 3](https://www.ioi-jp.org/camp/2020/2020-sp-tasks/day3/constellation3-en.pdf)」，感谢 [@Chanis](https://loj.ac/user/5837) 提供翻译**。

JOI 君拍了一张 $N\times N$ 的星空图，将左起第 $X$ 列，下起第 $Y$ 行的像素点称为像素 $(X,Y)$。

画面里有白色的大楼，黄色的星星，黑色的空格。第 $i$ 列从最下方到自下数起第 $A_i$ 行都是白色的大楼。有 $M$ 个星星，第 $j$ 个星星位于像素点 $(X_j,Y_j)$。此外，所有的像素点都是黑色。

若一个长方形区域可以称作星座，则满足以下条件：

1. 不含白色像素点。

2. 至少存在两个星星。

看厌了星座的 JOI 君要把一些黄色的星星涂成黑色，使得没有星座存在。将第 $j$ 个星星涂成黑色会使照片的不自然度增加 $C_j$，最初不自然度为 $0$。求不自然度的最小值。

# 输入格式

输入第一行为一个整数 $N$，表示地图的边长大小。

第二行为 $N$ 个整数 $A_1,\ldots,A_N$，描述如题目。

第三行为一个整数 $M$，表示星星的个数。

接下来的 $M$ 行，每行三个整数 $X_i,Y_i,C_i$，即对第 $i$ 个星星的描述。



# 输出格式

输出不自然度的最小值。


# 样例

#### 样例输入 1
```plain
5
1 3 4 2 3
3
1 5 3
4 3 2
2 4 2
```
#### 样例输出 1
```plain
2
```
#### 样例解释 1

![QQ图片20200322145805.png](/source/loj/3277/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wMy8yMi81ZTc3MGNjMTM4YWU5LnBuZw==.png)


可以发现把第三个星删了之后它就和一号构不成星座，且比删去一号花费少。

#### 样例输入 2
```plain
7
5 6 2 3 6 7 6
5
7 7 5
3 3 7
3 7 10
1 7 6
4 7 8
```
#### 样例输出 2
```plain
16
```

#### 样例解释 2

删去三号和四号。

# 数据范围与提示

对于 $100\%$ 的数据，$1 \leq N,M \leq 200 000$，保证：

- $1 \leq A_i \leq N (1 \leq i \leq N)$；

- $1 \leq X_j,Y_j \leq N (1 \leq j \leq M)$；

- $1 \leq C_j \leq 10^9 (1 \leq j \leq M)$；

- $A_{X_j} < Y_j (1 \leq j \leq M)$；

- $(X_j, Y_j)\neq (X_k, Y_k) (1 \leq j < k \leq M)$。

详细子任务及附加限制如下表：

| 子任务编号 |      附加限制       | 分值 |
| :--------: | :-----------------: | :--: |
|    $1$     |      $N,M\leq 300$      | $14$  |
|    $2$     | $N,M\leq 2000$ | $21$ |
|    $3$     |     无附加限制      | $65$ |


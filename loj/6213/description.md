
# 题目描述

Lyra 在玩一款游戏，在这款游戏中，Lyra 要在国境线上安装一列雷达，国境线可以看做一个数轴，第 $i$ 个雷达横坐标在 $x_i$ 的位置，高度最大为 $y_i$。雷达可以向下方至斜下方 $45^\circ$ 角范围内扫描，所以 $(x_0,y_0)$ 点的雷达可以扫描满足 $0 \leq y \leq y_0-|x-x_0|$ 的点组成的区域，若干个雷达的扫描区域是每个雷达扫描点集的并。

<img width="50%" src="source/loj/6213/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMDcvMjgvNTk3YjVlNmM3YzA2My5qcGc=.jpg" alt="1.jpg" title="1.jpg" >

第 $i$ 个雷达初始时高度为 $0$，Lyra 可以花费 $c_i$ 元将其高度提升 $1$，注意高度只能是整数。所有雷达布置完之后 Lyra 对于雷达能覆盖到的二维区域，获得等同于其面积的收入。

现在给定所有的 $x_i,y_i,c_i$ 求 Lyra 的最大净收入（即最后的收入减去布置雷达的花费）。


# 输入格式

第一行一个正整数 $T$ 表示数据组数。

对于每组数据，第一行一个整数 $n$ 表示雷达数目，接下来 $n$ 行每行三个正整数 $x_i,y_i,c_i$ 意义如题意所述。

# 输出格式

对于每组数据输出一行一个实数表示最大净收入，保留两位小数。

# 样例

#### 样例输入
```plain
2
2
0 4 1
4 4 3
2
0 4 0
4 100 100
```

#### 样例输出
```plain
12.00
16.00
```

#### 样例解释
对于第一组数据，我们可以这样设定雷达的高度：  
<div style="text-align: center"><img width="40%" src="source/loj/6213/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMDcvMjgvNTk3YjVlNmFjYmU1YS5qcGc=.jpg" alt="2.jpg" title="2.jpg" /></div>

或者  
<div style="text-align: center"><img width="28%" src="source/loj/6213/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTcvMDcvMjgvNTk3YjVlNmFjY2FmOS5qcGc=.jpg" alt="3.jpg" title="3.jpg" /></div>

对于第二组数据，两种方案中只有后者是最优方案。

# 数据范围与提示

$T \leq 500$  
$1 \leq n \leq 10^5$，$\sum n \leq 10^6$  
$0 \leq |x_i|,y_i,c_i \leq 10^8$


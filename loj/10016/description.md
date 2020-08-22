
# 题目描述

**原题来自：[ZOJ 3203](https://zoj.pintia.cn/problem-sets/91827364500/problems/91827367865)**

相比 wildleopard 的家，他的弟弟 mildleopard 比较穷。他的房子是狭窄的而且在他的房间里面仅有一个灯泡。每天晚上，他徘徊在自己狭小的房子里，思考如何赚更多的钱。有一天，他发现他的影子的长度随着他在灯泡和墙壁之间走到时发生着变化。一个突然的想法出现在脑海里，他想知道他的影子的最大长度。

![bulb.jpg](/source/loj/10016/img/aHR0cHM6Ly9sb2otaW1nLnVweXVuLm1lbmNpLm1lbXNldDAuY24vMjAyMC8wOC8wMi81ZjI2YTA3OTliNmNhLmpwZw==.jpg)

# 输入格式

输入文件的第一行包含一个整数 $T$ ，表示测试数据的组数。  

对于每组测试数据，仅一行，包含三个实数 $H$，$h$ 和 $D$，$H$ 表示灯泡的高度，$h$ 表示 mildleopard 的身高，$D$  表示灯泡和墙的水平距离。

# 输出格式

输出文件共 $T$ 行，每组数据占一行表示影子的最大长度，保留三位小数。

# 样例

#### 样例输入
```plain
3
2 1 0.5
2 0.5 3
4 3 4
```

#### 样例输出
```plain
1.000
0.750
4.000
```

# 数据范围与提示

$T \leq 100$，$10^{-2} \leq H,h,D \leq 10^3$，$10^{-2} \leq H-h$。


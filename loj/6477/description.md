
# 题目描述

<img src="/source/loj/6477/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTgvMDgvMDMvNWI2NDM3YmI1MDFiMC5wbmc=.png" alt="" style="width: 1000px; display: block; margin: 0 auto;">
<div style="text-align: center">图片来自 John Fowler, Carol Highsmith, Richard Woodland</div>

<br>

你决定在旅途中花一天的时间在 Rapid City 拍摄一些关于 South Dakota Badlands 的照片，这些地方以其壮观而不寻常的地层闻名。你是一名业余摄影师，但是对摄影的光照条件有着严苛的要求。

经过一番仔细的研究，你发现 Badlands 一处美丽的地方，周围环绕着如画般的风景。你已经确定了你想在这里拍摄的一系列特色。对于每个特色你也确定了一天中阳光最理想的最早时间与最晚时间。然而，你在拍照时需要花相当多的时间来重置三脚架与相机的位置，以满足你的完美主义。所以你想知道你是否可能在一天内成功完成所有特色的拍摄。


# 输入格式

第一行包含两个整数 $n$ $(1 \leq n \leq 10^4)$ 和 $t$ $(1 \leq t \leq 10^5)$，其中 $n$ 表示你想拍的照片数量， $t$ 表示你拍每张照片要花的时间。

接下来 $n$ 行，每行描述了一张照片理想的拍照时间段。每行包含两个非负整数 $a$ 和 $b$，其中 $a$ 是你可以开始拍摄这张照片的最早时间，而 $b$ 是这张照片必须完成的时间，满足 $a + t \leq b \leq 10^9$。


# 输出格式

如果可以拍这 $n$ 张照片，输出 `yes`，否则输出 `no`。


# 样例

#### 样例输入 1
```plain
2 10
0 15
5 20
```

#### 样例输出 1
```plain
yes
```

#### 样例输入 2
```plain
2 10
1 15
0 20
```

#### 样例输出 2
```plain
no
```

#### 样例输入 3
```plain
2 10
5 30
10 20
```

#### 样例输出 3
```plain
yes
```


# 数据范围与提示




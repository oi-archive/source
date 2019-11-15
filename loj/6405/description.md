
# 题目描述

> ~~Bwahahahahaha!!! Your nemesis, the dashingly handsome spy Waco Powers, has at last fallen to your~~
> ~~secret volcano base’s deathtraps (or so you assume, being a little too busy to witness it firsthand). At~~
> ~~long last, you are all set to CONQUER THE WORLD!~~
>
> ~~Nothing will stand in your way! Well, nothing except a minor problem of logistics. Your evil armies~~
> ~~have announced that they will not continue carving their relentless path of destruction across the puny~~
> ~~nations of the world without being paid. And unfortunately you are running low on cash – a volcano~~
> ~~lair has many wonderful qualities, but “reasonably affordable” is not one of them. You have had to pull~~
> ~~funds from the travel budget to pay your ungrateful underlings. Now you are not sure how you will~~
> ~~actually get your armies into position to CONQUER THE WORLD.~~

总之你就是想要征服这个世界。

你有一张世界地图，并且知道各国家之间所有可用的交通路线。每条路线连接两个国家，并且有一个固定的费用，每一个军队沿该路线移动都需要一个单位的费用。你知道目前你的所有军队所在的位置，以及在每个国家至少需要放置多少军队来征服它。你至少需要花多少钱移动你的军队来征服世界？

# 输入格式

第一行有一个整数 $n (1 \le n \le 250\ 000)$，表示国家的个数。接下来有 $n-1$ 行，每行有三个整数 $u, v, c (1 \le u,v \le n,1 \le c \le 10^6)$，表示有一条双向路线连接国家 $u$ 和 $v$，每个军队沿该路线移动需要花费 $c$ 的代价。

接下来有 $n$ 行，第 $i$ 行有两个非负整数 $x_i$ 和 $y_i$，表示目前有 $x_i$ 个军队在第 $i$ 个国家，而你最终至少需要在该国家放置 $y_i$ 个军队。保证总军队数（$x_i$ 的和）不小于 $y_i$ 的和，且不大于 $10^6$.

# 输出格式

输出最小的移动军队的费用，使得对于所有的 $i$，第 $i$ 个国家至少有 $y_i$ 个军队。

# 样例

#### 样例输入 1
```plain
3
1 2 5
3 1 5
2 1
5 0
1 3
```

#### 样例输出 1
```plain
15
```

#### 样例输入 2
```plain
6
1 2 2
1 3 5
1 4 1
2 5 5
2 6 1
0 0
1 0
2 1
2 1
0 1
0 1
```

#### 样例输出 2
```plain
9
```

# 数据范围与提示

国家总数不超过 $250\ 000$，军队总数不超过 $10^6$。

在不侵犯原题版权的情况下，本题面中文翻译基于[知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议](http://creativecommons.org/licenses/by-nc-sa/4.0/)发布，注明出处时需指向本题链接。


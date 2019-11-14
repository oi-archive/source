
# 题目描述

$N$ 头奶牛排成一列，准备领礼物。此时，奶牛们依次编号为 $1 \ldots N$。农夫约翰站在队头发礼物。

奶牛 $i$ 的权值为 $c_i$，每个到达队头的牛拿到礼物后会插队，插进倒数第 $c_i + 1$ 的位置。现在我们想知道，有多少奶牛不可能领到礼物。

### 原题面

>Farmer John's nemesis, Farmer Nhoj, has $N$ cows $(1\le N\le 10^5)$, conveniently numbered $1\dots N$. They have unexpectedly turned up at Farmer John's farm, so the unfailingly polite Farmer John is attempting to give them gifts.

>To this end, Farmer John has brought out his infinite supply of gifts, and Nhoj's cows have queued up in front of him, with cow 11 at the head of the queue and cow $N$ at the tail. Farmer John was expecting that at every timestep, the cow at the head of the queue would take a gift from Farmer John and go to the tail of the queue. However, he has just realized that Nhoj's cows are not that polite! After receiving her gift, each cow may not go to the tail of the queue, but rather may cut some number of cows at the tail, and insert herself in front of them. Specifically, cow $i$ will always cut exactly $c_i$ cows $(0\le c_i\le N−1)$.

>Farmer John knows that some cows might receive multiple gifts; as he has an infinite supply, this does not worry him. But he is worried that some cows might become unhappy if they do not get any gifts.

>Help Farmer John find the number of cows who never receive any gifts, no matter how many gifts are handed out.



# 输入格式

第一行一个数表示 $N$；  
第二行 $N$ 个数表示 $c_1,c_2,\dots, c_n$。

# 输出格式

一行一个数表示答案。

# 样例

#### 样例输入
```plain
3
1 2 0
```

#### 样例输出
```plain
1
```

# 数据范围与提示

对于全部数据，$1\le N\le 10^5, 0\le c_i\le N-1$。


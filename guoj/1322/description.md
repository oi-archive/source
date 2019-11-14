
# 题目描述

**注：该背景部分改编自 disangan233 中考前买计算器的真实事件。**  

博丽 灵梦（Hakurei Reimu）在成功抢回八云 紫（Yakumo Yukari）用隙间偷走的香火钱后，她和依神 紫苑（Yorigami Shion）去香霖堂买东西啦！  

灵梦想买一个计算器来计算神社的香火钱，但是因为香霖堂的东西太贵了，她选择使用河童重工网络（Kawashiro Nitori's Network, KNN）网购一个 Casio 计算器。

但出人意料的是，灵梦使用 KNN 买回来的 Casio 是个假货，最多只能显示整数部分（即向下取整）。   

灵梦很苦恼，因为这个计算器可能会导致一些特别大的误差。所以灵梦想让拥有外界的式神（指电脑）的你帮她解决一个问题。

---

灵梦得到了三个实数 $n$ ，$a$ ，$b$（$4\le n\le 5,5 \le a,b \le 10$），她成功地计算了 $n^a+n^b$，得到了一个只显示整数部分的结果。  

灵梦想知道，若存在一个实数 $n'(n' \geq 0)$，使得 ${n'}^a+{n'}^b$ 的结果在计算器上与 $n^a+n^b$ 的结果显示出来**完全一致**时，$n'$ 的变化范围，即 $n'$ 的最大值与最小值之差。  

如果你不知道如何计算 $n^k$，请使用 `cmath` 库的 `pow()` 函数，`pow(n,k)` 的结果即为 $n^k$ 的结果。    

---

为了提高本题的难度，灵梦给你设置了 $T$ 组询问。而为了在某种程度上减少你的输入和输出量，我们采用以下的代码来生成询问（代码来自河童重工）：  

```cpp
namespace Mker
{
//  Powered By Kawashiro_Nitori
//  Made In Gensokyo, Nihon
	#define uint unsigned int
	uint sd;int op;
	inline void init() {scanf("%u %d", &sd, &op);}
	inline uint uint_rand()
	{
		sd ^= sd << 13;
		sd ^= sd >> 7;
		sd ^= sd << 11;
		return sd;
	}
	inline double get_n()
	{
		double x = (double) (uint_rand() % 100000) / 100000;
		return x + 4;
	}
	inline double get_k()
	{
		double x = (double) (uint_rand() % 100000) / 100000;
		return (x + 1) * 5;
	}
	inline void read(double &n,double &a, double &b)
	{
		n = get_n(); a = get_k();
		if (op) b = a;
		else b = get_k(); 
	}
}
```

在调用 `Mker::init()` 函数之后，你第 $i$ 次调用 `Mker::read(n,a,b)` 函数后得到的便是第 $i$ 次询问的 $n_i$, $a_i$ 和 $b_i$。     

为了减少你的输出量，令第 $i$ 次询问的答案为 $s_i$，你只需要输出 $\sum^{T}_{i=1} s_i$ 。如果你的答案与标准答案的绝对误差在 $10^{-2}$ 以内，你的答案则被视为是正确答案。

本题数据的生成采用时间复杂度**远远劣于**普通算法的高（da）精（bao）度（li）算法来保证精度，本题数据保证**单次询问的误差**小于 $10^{-10}$，**所以本题的 SPJ 范围对于正解来说是完全足够的。**

---

为了让你更好地做题，这里给出了关于 $op$ 的说明：   

* 当 $op=1$ 时，有 $a=b$，否则无特殊限定。  



# 输入格式

输入共一行，包含 $3$ 个正整数  $T$，$seed$，$op$，含义见题目描述。

# 输出格式

输出共一行，输出题目描述中要求输出的答案。

# 样例

#### 样例输入 1

```plain
500 233 0
```

#### 样例输出 1

```plain
0.00503
```

#### 样例输入 2

```plain
10000 3141592653 0
```

#### 样例输出 2

```plain
0.10166
```

#### 样例输入 3

```plain
50000 1314159 0
```

#### 样例输出 3

```plain
0.50722
```

#### 样例输入 4

```plain
50000 1314159 1
```

#### 样例输出 4

```plain
1.51676
```

#### 样例输入 5

```plain
1000000 5201314 0
```

#### 样例输出 5

```plain
10.30487
```


# 数据范围与提示

#### 子任务

|数据点编号|$T$|$seed$|$op$|$Mker$|
|:-:|:-:|:-:|:-:|:-:|
|$1$|$\leq 100$|$=233$|$=0$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$2$|$\leq 500$|$\leq 2^{31}-1$|$=0$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$3$|$\leq 1000$|$\leq 2^{31}-1$|$=0$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$4$|$\leq 5000$|$\leq 2^{31}-1$|$=0$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$5$|$\leq 10000$|$\leq 2^{31}-1$|$=0$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$6$|$\leq 50000$|$\leq 2^{31}-1$|$=0$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$7$|$\leq 50000$|$\leq 2^{31}-1$|$=0$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$8$|$\leq 100000$|$=1145141919$|$=0$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$9$|$\leq 100000$|$\leq 2^{31}-1$|$=0$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$10$|$\leq 1000000$|$=1234567890$|$=0$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$11$|$\leq 1000000$|$\leq 2^{31}-1$|$=0$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$12$|$\leq 5000000$|$=3141592653$|$=0$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$13$|$\leq 5000000$|$\leq 2^{31}-1$|$=0$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$14$|$\leq 5000000$|$\leq 2^{31}-1$|$=0$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$15$|$\leq 10000$|$\leq 2^{31}-1$|$=1$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$16$|$\leq 50000$|$\leq 2^{31}-1$|$=1$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$17$|$\leq 50000$|$\leq 2^{31}-1$|$=1$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$18$|$\leq 100000$|$=1145141919$|$=1$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$19$|$\leq 1000000$|$=2718281828$|$=1$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|
|$20$|$\leq 5000000$|$\leq 2^{31}-1$|$=1$|$5\leq a,b \leq 10 \qquad 4\leq n\leq 5$|

#### 题目来源

[迷途之家 2019 联赛](https://www.luogu.org/contest/20135) (MtOI2019) T2

出题人：disangan233

验题人：suwakow



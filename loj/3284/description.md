
# 题目描述

**题目译自 [USACO 2020 US Open Contest, Platinum](http://usaco.org/index.php?page=open20results) Problem 2. [Exercise](http://usaco.org/index.php?page=viewproblem2&cpid=1033)**

Farmer John（又）想到了一个新的奶牛们的早操计划！

一如既往地，Farmer John 的 $N$ 头奶牛站成一排。左数第 $i$（$1 \le i \le N$）头奶牛的编号为 $i$。FJ 让奶牛不断重复执行下列操作，直到奶牛们又回到一开始的站位为止：

- 给定一个 $1 \sim N$ 的排列 $A$，使得原位置为左数第 $i$ 个的奶牛的新位置为左数第 $A_i$ 个。

例如，如果 $A = (1, 2, 3, 4, 5)$，则奶牛们执行一次操作后就立刻回到了原站位。如果 $A = (2, 3, 1, 5, 4)$，则奶牛们需要执行 $6$ 次操作才能回到原站位。每次执行完的站位分别是：

- 第 $0$ 次后：$(1, 2, 3, 4, 5)$。
- 第 $1$ 次后：$(3, 1, 2, 5, 4)$。
- 第 $2$ 次后：$(2, 3, 1, 4, 5)$。
- 第 $3$ 次后：$(1, 2, 3, 5, 4)$。
- 第 $4$ 次后：$(3, 1, 2, 4, 5)$。
- 第 $5$ 次后：$(2, 3, 1, 5, 4)$。
- 第 $6$ 次后：$(1, 2, 3, 4, 5)$。

请你计算对于所有 $N!$ 种 $1 \sim N$ 的排列 $A$ 所需次数的乘积。

因为这个数可能非常大，所以请你输出答案对 $M$ 取模的结果，保证 $M$ 为质数。

下列来自 [KACTL](https://github.com/kth-competitive-programming/kactl/blob/master/content/various/FastMod.h) 的代码可能会对使用 C++ 语言的用户产生一定的帮助。此方法名为 [Barrett reduction](https://en.wikipedia.org/wiki/Barrett_reduction)，它允许你使用更快的速度多次计算 $a \bmod b$，条件是 $b > 1$ 且为常数，但无法在程序编译期被得知。

```cpp
#include <bits/stdc++.h>
using namespace std;

typedef unsigned long long ull;
typedef __uint128_t L;
struct FastMod {
	ull b, m;
	FastMod(ull b) : b(b), m(ull((L(1) << 64) / b)) {}
	ull reduce(ull a) {
		ull q = (ull)((L(m) * a) >> 64);
		ull r = a - q * b; // can be proven that 0 <= r < 2*b
		return r >= b ? r - b : r;
	}
};
FastMod F(2);

int main() {
	int M = 1000000007; F = FastMod(M);
	ull x = 10ULL*M+3; 
	cout << x << " " << F.reduce(x) << "\n"; // 10000000073 3
}
```

# 输入格式

从标准输入中读入数据。

仅一行两个正整数 $N, M$。

# 输出格式

输出到标准输出中。

一行一个数表示答案。

# 样例

#### 样例输入
```plain
5 1000000007
```

#### 样例输出
```plain
369329541
```

#### 样例解释
数组中的第 $i$ 个元素表示需要花费 $i$ 步的排列数量：$[1, 25, 20, 30, 24, 20]$。所以答案为 $1^1 \cdot 2^{25} \cdot 3^{20} \cdot 4^{30} \cdot 5^{24} \cdot 6^{20} \equiv 369329541 \pmod{{10}^9 + 7}$。

# 数据范围与提示

对于所有数据，$1 \le N \le 7500$，${10}^8 \le M \le {10}^9 + 7$ 且 $M$ 为质数。

对于测试点 $2$，满足 $N = 8$。  
对于测试点 $3 \sim 5$，满足 $N \le 50$。  
对于测试点 $6 \sim 8$，满足 $N \le 500$。  
对于测试点 $9 \sim 12$，满足 $N \le 3000$。  
对于测试点 $13 \sim 16$，无特殊限制。

出题人：Benjamin Qi


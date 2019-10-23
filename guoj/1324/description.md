
# 题目描述

注：本题MtOI2019赛时时限$800ms$，Luogu时限$600ms$，LOJ时限$700ms$。

一年一度的幻想乡数学竞赛(thMO)又要开始了。  
幻想乡中学习数学的少(lao)女(tai)们(po)和冰之妖精baka一起准备着thMO。  
但是在那一刻，幻想乡日复一日的宁静被打破了。  
广播里，播放起了死亡的歌曲！
在那一刻，人们又回想起了被算数支配的恐惧。  
就剩下baka，baka，baka，baka的声音在幻想乡里回荡。  
 
---  

河城 荷取(Kawashiro Nitori)正坐在thMO2019的考场上！  
因为荷取有着她的[超级计算机](https://www.luogu.org/problemnew/show/P4911)，在成功地用光学迷彩覆盖了计算机之后，荷取在thMO2019的考场上所向披靡。  
* 荷取用她的超级计算机$0ms$跑出了这么一道题：  
  $$\exists \{ a_n\} (n=0,1,\cdots ,10^{18}),\text{已知}a_0=2,a_1=5,a_{n+2}=3a_{n+1}-2a_n \text{，求}a_n\bmod 10^{9}+7$$    

* 荷取：显然，这个题可以用矩阵乘法+快速幂，可以$O(\log n)$水过去，差不多就这样：     
$$\begin{bmatrix} a_n & a_{n+1} \end{bmatrix}=\begin{bmatrix} a_1 & a_2 \end{bmatrix} \times \begin{bmatrix} 0 & -2 \\ 1 & 3 \end{bmatrix}^n$$      

  
但是荷取遇到了一道她不会的题，她正在寻求你的帮助呢！ 

___

存在一个数列$\{ a_n\} (n\in \{ 0,1,2,\cdots ,2^{64}-1\} )$。  
已知$a_0=-3,a_1=-6,a_2=-12,a_n=3a_{n-1}+a_{n-2}-3a_{n-3}+3^n$。  
* 现在给你一个非负整数$n$，令$p=10^{9}+7$，请你求出$a_n \bmod p$。 
* **注：若$a_n<0$，请输出$(a_n \bmod p+p)\bmod p$。**    
  
  
为了更充分地考验你的水平，荷取设置了$T$组询问。
* 为了在某种程度上减少你的输入和输出量，我们采用以下的代码来生成询问：  
  
```
namespace Mker
{
//  Powered By Kawashiro_Nitori
//  Made In Gensokyo, Nihon
	#include<climits>
	#define ull unsigned long long
	#define uint unsigned int
	ull sd;int op;
	inline void init() {scanf("%llu %d", &sd, &op);}
	inline ull ull_rand()
	{
		sd ^= sd << 43;
		sd ^= sd >> 29;
		sd ^= sd << 34;
		return sd;
	}
	inline ull rand()
	{
		if (op == 0) return ull_rand() % USHRT_MAX + 1;
		if (op == 1) return ull_rand() % UINT_MAX + 1; 
		if (op == 2) return ull_rand();
	}
}
```  
在调用`Mker::init()`函数之后，你第$i$次调用`Mker::rand()`函数时返回的便是第$i$次询问的$n_i$。

在这里给出$op$的限制：

* 如果$op=0$，满足$n_i \leq 2^{16}$。

* 如果$op=1$，满足$n_i \leq 2^{32}$。

* 如果$op=2$，满足$n_i \leq 2^{64}-1$。

为了减少你的输出量，你只需要输出所有询问答案的**异或和**。

因为此题出题人丧心病狂把时限调到了卡常后的std的最大时间的$1.1$倍，请注意常数优化（**std默认开启O2优化**，**不含其他编译优化**）。




# 输入格式

第一行三个整数，输入$T$，$seed$和$op$。

# 输出格式

第一行一个整数，输出$T$组询问的答案的**异或和**。  

# 样例

### 样例输入 $1$

~~~
142857 1145141919 0
~~~

### 样例输出 $1$

~~~
562611141
~~~

### 样例输入 $2$

~~~
142857 1145141919 1
~~~

### 样例输出 $2$

~~~
894946216
~~~

### 样例输入 $3$

~~~
142857 1145141919 2
~~~

### 样例输出 $3$

~~~
771134436
~~~

# 数据范围与提示

### 子任务  

![png](/source/guoj/1324/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMDQvMTkvNWNiOWJiMmM2YzFkNi5wbmc=.png)  

### 题目来源

[迷途之家2019联赛](https://www.luogu.org/contest/20135)(MtOI2019) T4

出题人：disangan233

验题人：suwakow

蒟蒻出题人$\color{grey} {\mathsf{disangan233}}$在与$\mathsf o \color{red} {\mathsf{uuan}}$和$\mathsf P \color{red} {\mathsf{inkRabbit}}$的讨论后决定将这个题作为比赛的卡常题，旨在推广OI的一些常数优化技巧，并防止AK。

来自$\mathsf N \color{red} {\mathsf{aCly~Fish}}$的评价

![fish](/source/guoj/1324/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMDgvMTkvMXI4WFNvRHZoUm5iNDkzLnBuZw==.png)



# 题目描述

**本题 C/C++ 时限 2.5 秒，Pascal 时限 5 秒。最后将改时限重测所有 Pascal 提交。**

不知道大家有没有听过物凄系列的一首歌，帕秋莉用卡车给博丽老板运货的故事。  
   
又一次，卡车司机帕秋莉被拜托。红魔馆之主蕾米莉亚喜欢喝红茶，一天她要求帕秋莉开卡车帮她运红茶过来。
  
红茶其实是编好号了的，每个红茶都用一个非负整数来编号，从 $0$ 开始一直到正无穷。帕秋莉请来好朋友魔理沙，帮她一起运红茶。  

一开始卡车上已经有了编号为 $0$ 到 $a$ 的红茶（注意 $a=-1$ 就表示初始卡车上没有任何红茶），然后接下来到红魔馆的路上有 $m$ 个时刻，每个时刻都会发生一种事件。

> * 第一种事件，帕秋莉到了一个红茶店，买了一个编号为 $x$ 的红茶（卡车上初始没有这种编号的红茶，之前也不会买过相同编号的红茶）。  
> * 第二种事件，一个目前在卡车上的编号为 $x$ 的红茶飞出了卡车。  
> * 第三种事件，魔理沙把目前不在卡车上的最早飞出去的红茶捡回了卡车上（如果一个红茶曾经飞出去被捡回来过然后再飞出去，这里认为其飞出去的时间为最近一次飞出去的时间）。  


由于描述这些事件实在是太麻烦了，聪明的魔理沙用了一个长度为 $m$ 的整数序列 $p$ 来描述每个时刻发生的事件。

> * 这个序列 $p$ 里所有元素均为 $[-1,b)$ 的整数。  
> * 若 $p_i=-1$ 则表示时刻 $i$ 发生了第三种事件，如果此时并不存在满足条件的飞出去的红茶，则代表魔理沙脑子没转过来，忽视此次事件。  
> * 否则，如果在时刻 $i$ 编号为 $p_i$ 的红茶初始不在卡车上也从来没有通过第一种事件买过，则表示时刻 $i$ 发生了一个买编号为 $p_i$ 的红茶的第一种事件。
> * 否则，如果在时刻 $i$ 编号为 $p_i$ 的红茶在卡车上，则表示时刻 $i$ 发生了一个编号为 $p_i$ 的红茶飞出卡车的第二种事件。
> * 否则，表示时刻 $i$ 发生了第三种事件，如果此时并不存在满足条件的飞出去的红茶，则忽视此次事件。  

如果某个时刻的事件被忽视，那么我们**不执行对应的操作，也不计算此时的答案**。  

帕秋莉是一个勤奋的人，每个时刻过后，如果这个时刻 $i$ 发生了事件（如果一个时刻发生的事件被忽视了，就不认为这个时刻发生了事件），令 $ans_i$ 表示时刻 $i$ 过后卡车上所有编号小于 $ans_i$ 的红茶都出现了，而编号为 $ans_i$ 的红茶没有出现（很显然这个值是唯一的）。当然如果时刻 $i$ 没有发生事件，则令 $ans_i=0$ 。  

请你对于 $1 \leq i \leq m$ 计算出 $ans_i\times (i^2+7i)\ mod\ 998244353$ 的异或和。  

# 输入格式

第一行一个整数 $T$ ，表示数据组数。  

接下来有 $T$ 行，每行表示一组数据。  

每组数据依次有 $m,\mathrm{seed},a,b,c,d$ 六个整数，其中 $m,a,b$ 的意义与题面中相同；  
$d$ 表示是否只考虑第一种事件：$d$ 的取值为 $0$ 或 $1$ ，为特殊参数。当 $d=1$ 时，请忽视所有的第二种事件与第三种事件（忽视的含义见题面描述）。  
$\mathrm{seed},c$ 是随机数生成器的参数。

我们使用如下实现的随机数生成器 $\mathrm{randnum}()$。每组数据输入该组数据中 $\mathrm{seed}$ 的初始值。

```
unsigned 32bit integer seed

function randnum()
	seed = seed xor (seed lsh 13)
	seed = seed xor (seed rsh 17)
	seed = seed xor (seed lsh 5)
	return seed
end function
```

计算 $p[]$ 的代码如下：

```
for i = 1 to m by step 1
	if randnum() mod c == 0 then
		p[i] = -1
	else
		p[i] = randnum() mod b
	end if
end for
```

我们在「数据范围与提示」的最后提供了这道题的一个输入输出模板（也可以在附加文件中下载），如果你不需要，请忽视它。


# 输出格式

每组数据输出一行表示答案。

# 样例

#### 样例输入
```plain
1
7 327711436 4 6 3 0
```

#### 样例输出
```plain
292
```

#### 样例解释
 $p$ 序列为$[5,-1,2,-1,2,5,4]$ 。初始时卡车上已经有了编号为 $[0,4]$ 的红茶。  

第一个时刻，发生第一种事件，编号为 $5$ 的红茶加入卡车，此时卡车上编号为 $[0,5]$ 的红茶都有，而编号为 $6$ 的红茶没有，因此 $ans_1=6$ 。  

第二个时刻，理论上应该发生第三种事件，但是并没有红茶飞出了卡车，因此该事件被忽视， $ans_2=0$ 。

第三个时刻，发生第二种事件，编号为 $2$ 的红茶飞出卡车，此时卡车上编号为 $[0,1]$ 的红茶都有，而编号为 $2$ 的红茶没有，因此 $ans_3=2$ 。  

第四个时刻，发生第三种事件，魔理沙捡回编号为 $2$ 的红茶回卡车，此时与第一个时刻后情况一致，因此 $ans_4=6$ 。  

第五个时刻和第三个时刻一致，因此 $ans_5=2$ 。  

第六个时刻，发生第二种事件，编号为 $5$ 的红茶飞出卡车，此时卡车上编号为 $0,1,3,4$ 的红茶都有，而编号为 $2,5$ 的红茶没有，因此 $ans_6=2$ 。  

第七个时刻，发生第二种事件，编号为 $4$ 的红茶飞出卡车，此时卡车上编号为 $0,1,3$ 的红茶都有，而编号为 $2,4,5$ 的红茶没有，因此 $ans_7=2$ 。  

#### 更多样例
请在页面上方的附加文件中下载。

# 数据范围与提示

**本题 C/C++ 时限 2.5 秒，Pascal 时限 5 秒。最后将改时限重测所有 Pascal 提交。**

对于所有数据，$1 \leq m \leq 10^6$，$1 \leq T \leq 50$ ， $-1 \leq a \leq m$ ，  $1 \leq b \leq 2\times m$ ， $1 \leq c \leq 10^7$ ， $0 \leq d \leq 1$ 。

$d$ 表示是否只考虑第一种事件：$d$ 的取值为 $0$ 或 $1$ ，为特殊参数。当 $d=1$ 时，请忽视所有的第二种事件与第三种事件（忽视的含义见题面描述）。  
注意，$d=1$ 时原本合法的事件也要被忽视，故即使你没有用到这个性质，也要记得判断 $d=1$ 的情况。除测试点 $7$ 以外的测试点也有可能出现 $d=1$ 的数据。

|测试点 #|$m$ 的限制|$T$的限制|特殊限制|
|:-:|:-:|:-:|:-:|
|$1$|$m \leq 3000$|$T \leq 20$|-|
|$2$|$m \leq 3000$|$T \leq 25$|-|
|$3$|$m \leq 3000$|$T \leq 30$|-|
|$4$|$m \leq 10^5$|$T \leq 20$|-|
|$5$|$m \leq 10^5$|$T \leq 30$|-|
|$6$|$m \leq 10^5$|$T \leq 50$|-|
|$7$|$m \leq 10^6$|$T \leq 50$|$d=1$|
|$8$|$m \leq 8\times 10^5$|$T \leq 50$|-|
|$9$|$m \leq 10^6$|$T \leq 50$|-|
|$10$|$m \leq 10^6$|$T \leq 50$|-|

#### 输入输出模板
**输入输出模板的最大运行时间分别为：C/C++约 400 ms，Pascal 约 2000 ms**

```c++
//C++
#include<cstdio>

namespace IO{
	int c;
	unsigned int seed;
	unsigned int randnum(){
		seed^=seed<<13;
		seed^=seed>>17;
		seed^=seed<<5;
		return seed;
	}

	inline int read(int &x){scanf("%d",&x);return x;}
	inline void init_case(int &m,int &a,int &b,int &d,int p[]){
		scanf("%d%u%d%d%d%d",&m,&seed,&a,&b,&c,&d);
		for(int i=1;i<=m;i++){
			if(randnum()%c==0)p[i]=-1;
			else p[i]=randnum()%b;
		}
	}

	inline void update_ans(unsigned int &ans_sum,unsigned int cur_ans,int no){
		const static unsigned int mod=998244353;
		ans_sum^=(long long)no*(no+7)%mod*cur_ans%mod;
	}
}
using IO::read;
using IO::init_case;
using IO::update_ans;
/*
一开始请调用read(T)读入数据组数T
接下来每组数据开始时请调用init_case(m,a,b,d,p)读入m,a,b,d,p[]
每组数据开始时请用一个初始化为0的32位无符号整形变量ans_sum存储答案，然后对于每个i，
用32位无符号整形变量cur_ans存储第i次答案，并调用update_ans(ans_sum,cur_ans,i)更新。最后输出ans_sum即可。
*/

//示例代码：
/*
int main(){
	static int p[2000005];
	int T;read(T);
	int m,a,b,d;
	while(T--){
		unsigned int ans_sum=0,cur_ans=0;
		init_case(m,a,b,d,p);
		for(int i=1;i<=m;i++){
			......//处理操作
			update_ans(ans_sum,cur_ans,i);
		}
		printf("%u\n",ans_sum);
	}
	return 0;
}
*/
```
```c
//C
#include<stdio.h>

int _IO_c;
unsigned int seed;
unsigned int randnum(){
	seed^=seed<<13;
	seed^=seed>>17;
	seed^=seed<<5;
	return seed;
}

inline int read(int *x){scanf("%d",x);return *x;}
inline void init_case(int *m,int *a,int *b,int *d,int p[]){
	int i;
	scanf("%d%u%d%d%d%d",m,&seed,a,b,&_IO_c,d);
	for(i=1;i<=*m;i++){
		if(randnum()%_IO_c==0)p[i]=-1;
		else p[i]=randnum()%*b;
	}
}

inline void update_ans(unsigned int *ans_sum,unsigned int cur_ans,int no){
	const static unsigned int mod=998244353;
	*ans_sum^=(long long)no*(no+7)%mod*cur_ans%mod;
}

/*
一开始请调用read(&T)读入数据组数T
接下来每组数据开始时请调用init_case(&m,&a,&b,&d,p)读入m,a,b,d,p[]
每组数据开始时请用一个初始化为0的32位无符号整形变量ans_sum存储答案，然后对于每个i，
用32位无符号整形变量cur_ans存储第i次答案，并调用update_ans(&ans_sum,cur_ans,i)更新。最后输出ans_sum即可。
*/

//示例代码：
/*
int main(){
	static int p[2000005];
	int T;int m,a,b,d,i;
	read(&T);
	while(T--){
		unsigned int ans_sum=0,cur_ans=0;
		init_case(&m,&a,&b,&d,p);
		for(i=1;i<=m;i++){
			......//处理操作
			update_ans(&ans_sum,cur_ans,i);
		}
		printf("%u\n",ans_sum);
	}
	return 0;
}
*/
```
```pascal
//Pascal

type
	pointer_32=^longint;
var
	_IO_c:longint;
	seed:Cardinal;
	p:array[0..2000004]of longint;
	T,m,a,b,d,i:longint;
	ans_sum,cur_ans:Cardinal;

function randnum():Cardinal;
begin
	seed:=seed xor (seed shl 13);
	seed:=seed xor (seed shr 17);
	seed:=seed xor (seed shl 5);
	exit(seed);
end;

procedure init_case(var m,a,b,d:longint;p:pointer_32);inline;
var
	i:longint;
begin
	read(m,seed,a,b,_IO_c,d);
	for i:=1 to m do begin
		if randnum() mod _IO_c=0 then p[i]:=-1
		else p[i]:=randnum() mod b;
	end;
end;

procedure update_ans(var ans_sum:Cardinal;cur_ans:Cardinal;no:longint);inline;
const
	mod_val:Cardinal=998244353;
	calc:int64=1;
begin
	ans_sum:=ans_sum xor (calc*no*(no+7) mod mod_val*cur_ans mod mod_val);
end;

{
一开始请调用read(T)读入数据组数T
接下来每组数据开始时请调用init_case(m,a,b,d,p)读入m,a,b,d,p[]
每组数据开始时请用一个初始化为0的32位无符号整形变量ans_sum存储答案，然后对于每个i，
用32位无符号整形变量cur_ans存储第i次答案，并调用update_ans(ans_sum,cur_ans,i)更新。最后输出ans_sum即可。
}

//示例代码：
{
begin
	read(T);
	while T>0 do begin
		dec(T);
		ans_sum:=0;cur_ans:=0;
		init_case(m,a,b,d,p);
		for i:=1 to m do begin
			......//处理操作
			update_ans(ans_sum,cur_ans,i);
		end;
		writeln(ans_sum);
	end;
end.
}
```


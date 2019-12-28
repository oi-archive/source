
# Content

经典的$A^B\bmod C$问题可以用快速幂算法解决，先在考虑一个该问题的升级版。我们用如下函数生成一个$n$位$k$进制数：

```
long long a[maxn];
void f(int seed,int n,int k,int p)
{
    a[0]=seed%k;
    for(int i=1;i<n;i++)
        a[i]=a[i-1]*p%k;
}
```

函数执行完毕后，$a_0$到$a_{n-1}$依次从高位到低位表示这个数的每一位。

如$f(3,2,10,8)$生成了十进制数$34$，$f(3,3,2,7)$生成二进制数$111$，$f(8,3,8,8)$生成$8$进制数$000$，即$0$。

令：

$$A=f(seed_A,n_A,k_A,p_A)$$

$$B=f(seed_B,n_B,k_B,p_B)$$

再给你一个十进制数$C$，请计算出$A^B$的十进制答案模$C$的结果。

# Standard Input

输入$3$行：
* 第一行：$seed_A,n_A,k_A,p_A$
* 第二行：$seed_B,n_B,k_B,p_B$
* 第三行：$C$

$0\leq seed_A, seed_B, p_A, p_B\leq 10^9$

$2\leq k_A, k_B\leq 10^9$

$1\leq n_A, n_B\leq 10^6$

$1\leq C\leq 10^9$

输入保证不会出现$0^0$。

# Standard Output

输出一个数$ans$，$ans=A^B$的十进制答案模$C$。$0\leq ans\leq C - 1$

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>1 2 10 2
2 1 10 5
10</td><td>4</td></tr></table>


# Constraints



# Note



# Source



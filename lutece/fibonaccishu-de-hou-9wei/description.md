
# Content

Fibonacci数列定义如下：

$f(0)=1, f(1)=1$

$f(n)=f(n-1)+f(n-2)$, 当$n\ge 2$时

给出$n$，求出$f(n)$的后$9$位并输出，不足$9$位，请在前面补$0$。

# Standard Input

有多组测试数据。每一组测试数据只有一行，为整数$n$。其中，$0\le n<300$。

# Standard Output

对应每组输入，输出一行题目要求的结果。

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
<tr><td>2</td><td>000000002</td></tr><tr><td>150</td><td>907386349</td></tr></table>


# Constraints



# Note

由于每组测试数据都是只有一个整数，所以可以利用scanf的返回值来判断输入数据是否结束，程序框架可以如下：
```
#include <stdio.h>
int main()
{
    int a;
    while(scanf("%d", &a) == 1)
    {
         //处理数据
         //输出结果
    }
    return 0;
}
```

# Source



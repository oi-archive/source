
# Content

下面是吴神随手写的一段代码
```
G=0;
for (int i = 1; i < N; i++) {
  for (int j = i + 1; j <= N; j++) {
    G += gcd(i, j);
  }
}
```
反正以吴神的大脑能在$h$(量子物理里面的一个常量，你猜？)秒内跑出答案，现在看看你的大脑跑得出答案不？？

# Standard Input

第一行有个整数$T$，代表数据组数（$T\leq 100$）

接下来有$T$行，每行有个整数$N$ ($N<1000000$)

# Standard Output

输出$T$行，每行输出一个整数$G$代表对应$N$的程序运行的结果

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
<tr><td>3
10
20
100000</td><td>67
335
33717147452</td></tr></table>


# Constraints



# Note



# Source



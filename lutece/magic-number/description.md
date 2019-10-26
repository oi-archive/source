
# Content

Illya has  $n$  magic numbers. The  $i\_{th}$  number  $a\_i$  can be represented by a binary with the length of  $i$. Combining these  $0-1$  strings gets a long string  $s$  with the length of  $\frac{n(n+1)}{2}$. The  $0-1$  strings from  $s\_{\frac{i(i-1)}{2}}$  to  $s\_{\frac{i(i+1)}{2}-1}$  is the binary of  $a\_i$  from low to high.
One day, Rin input Illya’s magic numbers into a program to create  $n$  new magic numbers. The  $i\_{th}$  new number is  $b_i$.
Here is the code of program in C++:

```
for(int i = 1; i <= n; i++)
	b[i] = flag[i] = 0;
	
for(int i = 1; i <= n; i++){
	for(int j = 1; j <= n; j++){
		if( (1 << (j - 1) & a[i]) > 0){
			if(!flag[i])
				b[i] = b[j], flag[i] = 1;
			else b[i] &= b[j];
		}
	}
	b[i] ^= 1 << (i - 1);
}
```
After that, Rin leave  $q$  questions. The  $i\_{th}$  question is a number  $c\_i$, which can be represented by a binary with the length of   $len\_i$. Combining these  $0-1$  strings gets a long string  $t$  with the length of  $L\_q$ ($L\_k = \sum\_{1}^{k}len\_i$). The  $0-1$  strings from  $t\_{L\_{i-1}}$  to  $t\_{L_i-1}$  is the binary of  $c\_i$  from low to high. 
For each question, Rin requires Illya to calculate number  $d\_i$.

```
for(int i = 1; i <= n; i++){
	d[i] = 0;
	for(int j = 1; j <= len[i]; j++)
		if(j <= n && (1 << (j - 1) & c[i]) > 0)
			d[i] |= b[j];
}
```
The answer of  $i_{th}$  question is the number of ones in the binary of  $d_i$.

# Standard Input

There are multiple test cases.
the first line contains a single integers  $T$, denoting the number of test cases.
For each case, 
the first line contains two integers  $n$  and  $m$, denoting the number of magic numbers and the number of ones in a long string  $s$.
The second line contains  $m$  integers, the  $i\_{th}$  integer  $p1\_i$  denotes  $s\_{p1\_i}$ = 1. The others are equal to 0.
The third line contains two integer  $q$  and  $r$, denoting the number of questions and the number of ones in a long string  $t$.
The forth line contains  $q$  integers, the  $i\_{th}$  integer  $len\_i$  denotes the length of binary of the  $i\_{th}$  question  $c\_i$.
The fifth line contains  $r$  integers, the  $i\_{th}$  integer  $p2\_i$  denotes $t\_{p2\_i}$ = 1. The others are equal to 0.

$1 \leqslant T \leqslant 20$
$1 \leqslant n,q  \leqslant 5000$
$1 \leqslant m,r  \leqslant 10^6$
$0 \leqslant L\_q \leqslant 10^9$
$0 \leqslant p1\_i < \frac{n(n+1)}{2}$
$0 \leqslant p2\_i < L\_q$

# Standard Output

For each case, first output "Case #x:".
Each question should print one line: the  $i_{th}$  line of these denotes the answer of  $i_{th}$  question.
There is no blank line between two cases.

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
<tr><td>1
3 4
0 1 4 5
3 6
2 3 3
0 1 2 4 6 7
</td><td>Case #1:
2
3
3
</td></tr></table>


# Constraints



# Note



# Source



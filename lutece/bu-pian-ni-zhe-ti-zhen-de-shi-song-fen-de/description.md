
# Content

字符串的哈希就是通过某些映射关系，将字符串映射到数字上去方便进行比较。

比如二进制数$110110$，我们知道这个数的十进制是 $54$

基于同样思路，我们可以定义这样的一个哈希函数：

哈希函数是基于$163$进制的，即

$hash_i$$=(s_1-'a')$*$163^{i-1}$+$(s_2-'a')$*$163^{i-2}$+$...$+$(s_i-'a')*163^{0}$

这样，一个字符串从$0$到$i$的哈希值便计算了出来。

现在给定一个字符串，求按照上面的方法，这个字符串的子串的哈希值。

# Standard Input

第一行：一个字符串$s$,$(1 \le length(s) \le 1e5)$，保证全部为小写字母

第二行：一个正整数$n$,$(1 \le n \le 1e5)$

接下来有n行，每行两个正整数$l,r$$(1 \le l \le r \le length(s))$,表示子串的起始字符下标和中止字符下标。

# Standard Output

共$n$行，每行为所求的子串的哈希值

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
<tr><td>abc
4
1 1
2 2
3 3
1 3
</td><td>0
1
2
165
</td></tr></table>


# Constraints



# Note

1.由于hash值可能很大，因此hash值取unsigned long long以便自然溢出。

2.字符串的下标从$1$开始。


`审题人：希望大家能看出来这个hash函数是错误的，正确的写法应该是这样：`

$hash_i$$=(s_1-'a'+1)$*$163^{i-1}$+$(s_2-'a'+1)$*$163^{i-2}$+$...$+$(s_i-'a'+1)*163^{0}$

这里写出这个函数意为题面中的函数不适合做hash，但是我们要求依然按照题目中的函数来做此题

# Source



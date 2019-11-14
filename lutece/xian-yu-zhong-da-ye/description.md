
# Content

钟望大爷刚刚学习了字符串的哈希算法，对于字符串哈希，他使用的哈希函数是`hash[i]=(hash[i-1]*p+ASCII(s[i]))%mod`;比如对于p = 2,mod = 1000时，hash('ab') = 97 * 2 + 98 = 292;他认为这样的哈希方法是很难发生冲突的。正巧，这个函数被周日天看到了，周日天劈头盖脸的就是一顿批判，然后扬长而去。留下了钟望大爷在原地一脸懵逼。  
现在，对于给出的p，mod，钟望大爷希望你能构造出两个不同字符串（字符串长度不能大于1,000,000且只能由小写字母构成），使得他们的哈希值在这个哈希函数中相同。

# Standard Input

输入包括2个正整数p,mod。（0 < p < mod <= 1,000,000,000）;

# Standard Output

对于每组数据，输出占2行，输出任意一对满足条件的不同的字符串（字符串长度不能大于1,000,000且只能由小写字母构成）。

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
<tr><td>1 2</td><td>a
c</td></tr></table>


# Constraints



# Note

两个字符串的长度可以不同！！！！！

# Source



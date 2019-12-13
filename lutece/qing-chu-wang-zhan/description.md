
# Content

上网了一段时间后，KK想清除一部分收藏的网站。令人惊讶的是，KK收藏的网站名均为`www.xxxxxx.com`的形式，其中`xxxxxx`全由小写英文字符构成（字符个数不超过$30$）。在清除前，他把英文字符`a`~`z`依次映射到整数$k_1\sim k_{26}$（范围为$[-100,100]$），接着把`xxxxxx`中每个字符对应的整数加起来求平均值，然后再删除掉值较低的网站。你的任务是把给出的网站的值求出来，每个值保留两位小数。

# Standard Input

含多组测试数据，输入首先是一个整数$T$表示测试数据组数($0<T \leq 150$)。随后有$T$组测试数据，每组的第一行是$26$个整数，每个数后有一个空格，接着的一行是整数$N$（$0<N\leq 20$），表明随后有$N$行，每行是一个网站名。

# Standard Output

对应每组测试数据，输出对应的结果，详细格式参看样例。

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
<tr><td>2
-59 76 3 69 -26 -54 -79 -88 -72 43 -23 -95 66 44 12 -11 81 -17 -97 -91 -70 32 -17 53 -9 21 
1
www.baidu.com
98 6 17 66 34 -90 -86 29 -23 84 -55 29 -16 -57 -99 -82 -30 -70 -98 -88 0 -99 70 -3 79 -32 
2
www.google.com
www.iqiyi.com</td><td>case 1:
-11.20


case 2:
-51.17
-4.00</td></tr></table>


# Constraints



# Note



# Source



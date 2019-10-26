
# Content

任意的一个正整数，将其反序（高低位交换），与原来的整数相加，得到新的整数后重复以上步骤，最终可以得到一个回文数，这就叫回文数猜想。

例如，$291$：$291+192＝483$， $483+384＝867$， $867+678＝1635$， $1635+5361＝6996$。$6996$是回文数，经过了$4$步。

你的任务是对于给定的正整数（不超过$32767$），求出由上述方法得出的回文数。如果在上述过程中，数的位数已超过$8$位，但还不是回文数，则中断该过程，并输出这个数。

# Standard Input

含多组测试数据，输入首先是一个整数$T$表示测试数据组数($0<T \leq 200$)。随后有$T$组测试数据，每组是一个整数，占一行。

# Standard Output

对应每组测试数据，输出按描述规定的结果，占一行。

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
291
27596</td><td>6996
175732667</td></tr></table>


# Constraints



# Note



# Source



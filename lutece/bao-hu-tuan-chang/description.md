
# Content

**团长们把保护公屏打在兄弟上！**

保护团长不受屑网友的迫害是团员的工作，莱德决定制造一串完整的括号序列把团长保护起来。

完整的括号序列定义如下：

1. `()`是一段完整的括号序列
2. 若序列 `A` 是一段完整的括号序列，则 `(A)` 是一串完整的括号序列
3. 若序列 `A` 和 `B` 都是完整的括号序列，则 `AB` 是一串完整的括号序列

这串括号序列总长度为 $n\cdot m$，我们把各个位置标记为 $0,1,2,\ldots ,n\cdot m-1$ 。莱德在第 $i$ 个位置上制造一个左括号需要花费 $a_{i \bmod n}$ 点代价，在第 $i$ 个位置上制造一个右括号需要花费 $b_{i \bmod n}$ 点代价。

莱德是一名加把劲骑士，他会努力工作，但他仍然想知道制造这串完整的括号序列需要花费的最少的代价是多少。

![protect](/source/lutece/bao-hu-tuan-chang/img/aHR0cHM6Ly9waWNzLmltYWdlcy5hYy5jbi9pbWFnZS81ZWI0Y2NjZDUxZDVjLmh0bWw=.html)

# Standard Input

第一行包括两个数字，$n$ 和 $m$  ($1\leq n\leq20,~1\leq m\leq 10^8$)， **约定 $n\times m$ 一定为偶数**

接下来一行有 $n$ 个数字，分别代表 $a_0,a_1,...,a_{n-1}$ ($1\leq a_i\leq 10$)

接下来一行有 $n$ 个数字，分别代表 $b_0,b_1,...,b_{n-1}$ ($1\leq b_i\leq 10$)

# Standard Output

输出一个整数表示答案

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
<tr><td>2 6
1 2
2 1
</td><td>12
</td></tr></table>


# Constraints



# Note



# Source



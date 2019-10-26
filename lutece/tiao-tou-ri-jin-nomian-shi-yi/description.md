
# Content

省府弟子乐天潭在条头日今的笔试中遇到了四道题，其中第一题是：

已知 n 和 t，构造一棵 n 个结点的树，使得边权和最大。

结点的编号为 1 到 n，对于边权 w(u,v) = GCD(u,v) &t。

乐天潭很强势，一眼就知道了解法，但计算量实在过大，没办法只好偷偷掏出手机请你帮他写一个程序算出答案。

# Standard Input

第一行，两个整数 n (1 <= n <= 3000)，t (1 <= t <= 10^9+7)。

# Standard Output

输出一行，一个整数，表示答案。

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
<tr><td>3 3</td><td>2</td></tr></table>


# Constraints



# Note

w(u,v)表示边(u,v)的边权，GCD(u,v)表示u和v的最小公约数,&表示二进制按位与

样例有三种构造方法：

方法一：将1和2，2和3连边，GCD(1,2)&3 + GCD(2,3)&3 = 2

方法二：将1和2，1和3连边，GCD(1,2)&3 + GCD(1,3)&3 = 2

方法三：将1和3，2和3连边，GCD(1,3)&3 + GCD(2,3)&3 = 2

# Source



# 

 
 # 题目描述 
<p>&nbsp;&nbsp;&nbsp;&nbsp;我们可以把由&ldquo;0&rdquo;和&ldquo;1&rdquo;组成的字符串分为三类：全&ldquo;0&rdquo;串称为B串，全&ldquo;1&rdquo;串称为I串，既含&ldquo;0&rdquo;又含&ldquo;1&rdquo;的串则称为F串。<br />
&nbsp;&nbsp;&nbsp;&nbsp;FBI树是一种二叉树1，它的结点类型也包括F结点，B结点和I结点三种。由一个长度为2^N的&ldquo;01&rdquo;串S可以构造出一棵FBI树T，递归的构造方法如下：<br />
&nbsp;&nbsp;&nbsp;&nbsp;1)&nbsp;T的根结点为R，其类型与串S的类型相同；<br />
&nbsp;&nbsp;&nbsp;&nbsp;2)&nbsp;若串S的长度大于1，将串S从中间分开，分为等长的左右子串S1和S2；由左子串S1构造R的左子树T1，由右子串S2构造R的右子树T2。<br />
&nbsp;&nbsp;&nbsp;&nbsp;现在给定一个长度为2^N的&ldquo;01&rdquo;串，请用上述构造方法构造出一棵FBI树，并输出它的后序遍历2序列。</p> 

 
 # 输入格式 
<p>输入的第一行是一个整数N(0&lt;=N&lt;=10)，第二行是一个长度为2^N的&ldquo;01&rdquo;串。</p> 

 
 # 输出格式 
<p>&nbsp;输出包括一行，这一行只包含一个字符串，即FBI树的后序遍历序列。</p> 

 
 # 提示 
<p>NOIP2004普及组第三题</p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>3
10001011</td><td>IBFBBBFIBFIIIFF</td></tr></table>

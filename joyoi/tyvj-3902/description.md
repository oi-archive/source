# 

 
 # 题目背景 
<p>我们可以把由&ldquo;0&rdquo;和&ldquo;1&rdquo;组成的字符串分为三类：全&ldquo;0&rdquo;串称为B串，全&ldquo;1&rdquo;串称为I串，既含&ldquo;0&rdquo;又含&ldquo;1&rdquo;的串则称为F串。<br />
FBI树是一种二叉树[1]，它的结点类型也包括F结点，B结点和I结点三种。由一个长度为2N的&ldquo;01&rdquo;串S可以构造出一棵FBI树T，递归的构造方法如下：<br />
1)&nbsp;&nbsp;T的根结点为R，其类型与串S的类型相同；<br />
2)&nbsp;&nbsp;若串S的长度大于1，将串S从中间分开，分为等长的左右子串S1和S2；由左子串S1构造R的左子树T1，由右子串S2构造R的右子树T2。<br />
现在给定一个长度为2N的&ldquo;01&rdquo;串，请用上述构造方法构造出一棵FBI树，并输出它的后序遍历[2]序列。<br />
&nbsp;</p> 

 
 # 题目描述 
<p>【输入文件】<br />
输入文件fbi.in的第一行是一个整数N（0&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;10），第二行是一个长度为2N的&ldquo;01&rdquo;串。<br />
【输出文件】<br />
输出文件fbi.out包括一行，这一行只包含一个字符串，即FBI树的后序遍历序列。<br />
【样例输入】<br />
3<br />
10001011<br />
【样例输出】<br />
IBFBBBFIBFIIIFF<br />
【数据规模】<br />
对于40%的数据，N&nbsp;&lt;=&nbsp;2；<br />
对于全部的数据，N&nbsp;&lt;=&nbsp;10。<br />
&nbsp;</p> 

 
 # 输入格式 
<p>3<br />
10001011</p> 

 
 # 输出格式 
<p>IBFBBBFIBFIIIFF</p> 

# 

 
 # 题目描述 
<p>
最近公共祖先（cca.pas/c/cpp）<br><br>【问题描述】<br><br>　 　 输入一棵有根树和一系列顶点。对每对顶点(u，v)，算出它们的最近公共祖先。一个结点可以是它自己的祖先。(如例1中2的祖先是2和5)<br><br></p> 

 
 # 输入格式 
<p>
每组数据输入格式： <br><br>第一行是一个整数n，表示顶点数，其中 n <= 900 ，接下来n行格式如下：<br>vertex：(nr_of_successors) successor1 successor2 ...<br>vertices是一个1到n的整数，表示顶点，nr_of_successors表示该顶点的儿子数，successor i( 1<=i<= nr_of_successors )表示该顶点的各儿子<br>然后是一个整数nr_of_pairs，表示要求的顶点对数<br>(u v) (x y) ...<br><br>输入包含至少一组数据<br>包含一些无用的空格，空行等<br></p> 

 
 # 输出格式 
<p>
对每个公共祖先程序输出这个祖先和以它为祖先的顶点对数。<br>格式为： ancestor：times ，其中ancestor表示祖先，times表示以它为祖先的顶点对数。<br><br><center><img src="/source/joyoi/tyvj-3240/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzI0MC9wcm9ibGVtc19pbWFnZXMvMTc3NS9wMS5naWY=.gif"></img></center></p> 

 
 # 提示 
<p>
Huge input, scanf is recommended.注意输入，如果使用c语言的请用scanf<br><br>本题数据不完整，请在本系统测试通过后到http://poj.org/problem?id=1470 提交完整测试！</p> 
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
<tr><td>5
5:(3) 1 4 2
1:(0)
4:(0)
2:(1) 3
3:(0)
6
(1 5) (1 4) (4 2)
      (2 3)
(1 3) (4 3)
</td><td>2:1
5:5</td></tr></table>

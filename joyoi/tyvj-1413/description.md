# 

 
 # 题目背景 
Due&nbsp;to&nbsp;the&nbsp;talent&nbsp;of&nbsp;talent123,当talent123做完NOIP考了两次的二取方格数和vijos中的三取方格数后，突发奇想.... 

 
 # 题目描述 
在一个宽M，长N的矩阵中，请你编一个程序，n次从矩阵的左上角走到矩阵的右下角，每到一处，就取走该处的数字，请你选择一<BR>种走法使取得的数字的和最大,并输出其最大值。其中：3&lt;=M&lt;=20&nbsp;&nbsp;&nbsp;M&lt;=N&lt;=100&nbsp;&nbsp;&nbsp;1&lt;=n&lt;=10&nbsp;&nbsp;<BR>如输入数据：<BR>3&nbsp;10&nbsp;13&nbsp;&nbsp;<BR>0&nbsp;1&nbsp;2&nbsp;3&nbsp;4&nbsp;9&nbsp;7&nbsp;1&nbsp;3&nbsp;1<BR>9&nbsp;1&nbsp;2&nbsp;2&nbsp;3&nbsp;6&nbsp;7&nbsp;8&nbsp;1&nbsp;2<BR>1&nbsp;2&nbsp;3&nbsp;4&nbsp;5&nbsp;9&nbsp;8&nbsp;7&nbsp;6&nbsp;1<BR>9&nbsp;7&nbsp;1&nbsp;3&nbsp;1&nbsp;9&nbsp;1&nbsp;2&nbsp;2&nbsp;3<BR>6&nbsp;7&nbsp;8&nbsp;1&nbsp;2&nbsp;1&nbsp;2&nbsp;3&nbsp;4&nbsp;5<BR>9&nbsp;1&nbsp;2&nbsp;2&nbsp;3&nbsp;6&nbsp;7&nbsp;8&nbsp;1&nbsp;2<BR>1&nbsp;2&nbsp;3&nbsp;4&nbsp;5&nbsp;9&nbsp;8&nbsp;7&nbsp;6&nbsp;1<BR>9&nbsp;7&nbsp;1&nbsp;3&nbsp;1&nbsp;9&nbsp;1&nbsp;2&nbsp;2&nbsp;3<BR>6&nbsp;7&nbsp;8&nbsp;1&nbsp;2&nbsp;1&nbsp;2&nbsp;3&nbsp;4&nbsp;5<BR>9&nbsp;1&nbsp;2&nbsp;2&nbsp;3&nbsp;6&nbsp;7&nbsp;8&nbsp;1&nbsp;2<BR>1&nbsp;2&nbsp;3&nbsp;4&nbsp;5&nbsp;9&nbsp;8&nbsp;7&nbsp;6&nbsp;1<BR>9&nbsp;7&nbsp;1&nbsp;3&nbsp;1&nbsp;9&nbsp;1&nbsp;2&nbsp;2&nbsp;3<BR>6&nbsp;7&nbsp;8&nbsp;1&nbsp;2&nbsp;1&nbsp;2&nbsp;3&nbsp;4&nbsp;0<BR>其中n=3<BR>&nbsp;&nbsp;&nbsp;&nbsp;M=10<BR>&nbsp;&nbsp;&nbsp;&nbsp;N=13<BR>即当n=3时，就相当于是3取方格数。<BR>对于以上的数据：<BR>将输出：297 

 
 # 输入格式 
第一行：三个整数：n&nbsp;M&nbsp;N<BR>以下的N行每行M个数字，代表你要处理的矩阵。<BR><BR> 

 
 # 输出格式 
只有一行：你所取得的数字的和。 

 
 # 提示 
本题目来自：北京市，中关村中学，高三9班，孙一（网名:talent123）,联系方式：865383864（QQ） 
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
<tr><td>4 6 7
0 2 3 4 5 6
6 5 4 3 2 1
0 9 8 7 6 5
12 3 4 5 6 7
0 0 0 1 2 3
12 23 34 45 1 23
4 5 6 6 1 0</td><td>265</td></tr></table>

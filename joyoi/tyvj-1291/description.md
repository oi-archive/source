# 

 
 # 题目背景 
3天的狂欢结束了，pink，lina，飘飘乎居士在自己生日的这天晚上，摆下最后一个01魔阵，请pink和lina破解<BR> 

 
 # 题目描述 
&nbsp;&nbsp;pink和lina首先会得到数字0，接着他们一共要执行n次操作，每次操作都遵循下面的规则：①把所有的1变成01；②把所有的0变成10，注意这2个操作时同时进行的。之后得到一个新的数字（当然，也是由01组成），问经过n次这样的操作，得到第n个数字中，共有多少对连续2个相邻在一起的0？<BR><BR><BR><BR> 

 
 # 输入格式 
共一行，1个数n。<BR>表示pink和lina一共要进行n次变换<BR>对于30%的数据&nbsp;0&lt;n&lt;=20，答案在longint以内<BR>对于100%的数据&nbsp;0&lt;n&lt;=100，&nbsp;答案不超过40位数 

 
 # 输出格式 
一个数，存在多少对两个相邻的0？<BR> 

 
 # 提示 
pink和lina首先会得到一个0，一共需要3次操作<BR>第一次操作数字变成10<BR>第二次操作数字变成0110<BR>第三次操作数字变成10010110<BR>该数字在从左往右第二位和第三位是一对相邻的0<BR>所以最后的答案是1<BR> 
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

</td><td>1</td></tr></table>

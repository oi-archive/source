# 

 
 # 题目背景 
此为平衡树系列第一道：普通平衡树 

 
 # 题目描述 
您需要写一种数据结构（可参考题目标题），来维护一些数，其中需要提供以下操作：<BR>1.&nbsp;插入x数<BR>2.&nbsp;删除x数(若有多个相同的数，因只删除一个)<BR>3.&nbsp;查询x数的排名(若有多个相同的数，因输出最小的排名)<BR>4.&nbsp;查询排名为x的数<BR>5.&nbsp;求x的前驱(前驱定义为小于x，且最大的数)<BR>6.&nbsp;求x的后继(后继定义为大于x，且最小的数)<BR> 

 
 # 输入格式 
第一行为n，表示操作的个数,下面n行每行有两个数opt和x，opt表示操作的序号(1&lt;=opt&lt;=6) 

 
 # 输出格式 
对于操作3,4,5,6每行输出一个数，表示对应答案 

 
 # 提示 
n&lt;=100000&nbsp;所有数字均在-10^7到10^7内 
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
<tr><td>8
1 10
1 20
1 30
3 20
4 2
2 10
5 25
6 -1</td><td>2
20
20
20</td></tr></table>

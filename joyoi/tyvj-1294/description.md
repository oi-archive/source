# 

 
 # 题目背景 
"梦中伊人，断我男儿几寸柔肠，于断桥，不知西风自憔悴那姑娘。"小v的梦中伊人要带领一大帮姐妹MM们来小v家举办舞会，然而怎么安排跳舞的顺序成了大问题，你能帮他么？<BR> 

 
 # 题目描述 
有n个MM要站成若干个圈来跳华尔兹，而每个MM都有一个漂亮值Si，跳舞时第i个MM所表现出来的漂亮值为：该MM的漂亮值与其后面MM的漂亮值之差的绝对值（规定顺时针方向为向后），如果某个MM单独站成一个圈（假设能站成），则其漂亮值为0，你的任务是找出这个最大能表现出的漂亮值。<BR> 

 
 # 输入格式 
第一行一个整数n，表示n个MM<BR>第二行n个整数，第i个整数表示第i个MM的漂亮值<BR><BR> 

 
 # 输出格式 
一行一个整数，表示能表现出的最大漂亮值<BR> 

 
 # 提示 
数据范围：<BR>对于10%的数据，0&lt;n&lt;=10,0&lt;Si&lt;=100<BR>对于40%的数据，0&lt;n&lt;=50,0&lt;&nbsp;Si&nbsp;&lt;=1000<BR>对于100%的数据，0&lt;n&lt;=300,0&lt;Si&lt;=1000000<BR>结果保证不大于2^31.<BR><BR> 
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
<tr><td>6
12 11 24 17 12 24

</td><td>60
</td></tr></table>

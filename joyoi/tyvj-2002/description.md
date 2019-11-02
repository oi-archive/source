# 

 
 # 题目背景 
Admin生日那天，Rainbow来找Admin玩扑克牌……<br>玩着玩着Rainbow觉得太没意思了,于是决定给Admin一个考验~~~<br><br> 

 
 # 题目描述 
Rainbow把一副扑克牌(54张)随机洗开，倒扣着放成一摞。然后Admin从上往下依次翻开每张牌，每翻开一张黑桃、红桃、梅花或者方块，就把它放到对应花色的堆里去。<br>Rainbow想问问Admin，得到A张黑桃、B张红桃、C张梅花、D张方块需要翻开的牌的张数的期望值E是多少？<br>特殊地，如果翻开的牌是大王或者小王，Admin将会把它作为某种花色的牌放入对应堆中,使得放入之后E的值尽可能小。<br>由于Admin和Rainbow还在玩扑克，所以这个程序就交给你来写了~<br><br> 

 
 # 输入格式 
输入仅由一行，包含四个用空格隔开的整数，A,B,C,D。<br><br> 

 
 # 输出格式 
输出需要翻开的牌数的期望值E，四舍五入保留3位小数。<br>如果不可能达到输入的状态，输出-1.000。<br><br> 

 
 # 提示 
对于100%的数据，0&lt;=A,B,C,D&lt;=15<br><br>lydrainbowcat&nbsp;-&nbsp;"Admin生日"杯NOIP模拟赛&nbsp;第三题<br>Blog:&nbsp;www.lydrainbowcat.tk&nbsp;&nbsp;Email:&nbsp;lyd@tyvj.cn<br><br> 
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
<tr><td>样例输入1
1 2 3 4

样例输入2
15 15 15 15

</td><td>样例输出1
16.393

样例输出2
-1.000

</td></tr></table>

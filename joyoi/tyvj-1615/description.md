# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;Fox是一种叫做狐狸的动物，它有四条腿、两只眼睛、一张嘴巴、一个鼻子。同时，它有着高度警惕的头脑，一点点异样都会让他紧张起来。<BR>&nbsp;&nbsp;&nbsp;&nbsp;冬天到了，地上覆盖了一层厚厚的雪，平整的地面上什么痕迹都没有。为了防止大型动物的攻击，2n只Fox的窝往往分散在以P(0,0)为圆心的圆周上（不在圆的内部）。我们现在只知道,如果以圆的水平直径(也就是x轴)所在直线分界，直线上方居住着A只Fox，直线下方居住着B只Fox，没有Fox居住在这条直线与圆的交点上。<BR>&nbsp;&nbsp;&nbsp;&nbsp;但是毕竟每只Fox都自己生活实在太孤独了，所以其中的n只Fox会前往另一只Fox那里驱散孤独，在途中Fox只会走两点所连的直线。但是Fox是警惕的动物，所以一旦发现地面上有一条脚印横在眼前的时候，Fox就不会通过，他们认为这会有危险。但是如果有Fox没有被访问到的话就会孤独而死。你，帮助Fox群的首领，计算一下到底有多少种方案，使得在Fox们认为安全的情况下，所有的Fox都能够生存下来。 

 
 # 输入格式 
输入只有一行，三个整数&nbsp;n,A,B&nbsp; 

 
 # 输出格式 
方案数。无解输出“No&nbsp;Solution”。<BR>因为方案数可能很大，所以你只需要告诉我方案数模123456的值就可以啦。 

 
 # 提示 
对于30%数据		n&lt;=30<BR>对于100%数据	0&lt;=A,B&lt;=n&lt;=100，保证A+B=2n来源：Delostik	开学欢乐赛 
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
<tr><td>5 0 10
</td><td>42
</td></tr></table>

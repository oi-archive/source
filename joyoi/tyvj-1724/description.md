# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;话说同学们正在学习二元一次方程组。<BR>&nbsp;&nbsp;&nbsp;&nbsp;二元一次方程组的练习题铺天盖地地涌向同学们，同学们正苦恼于一次次地四则运算、移项、合并同类项等等。<BR>&nbsp;&nbsp;&nbsp;&nbsp;他们知道你很聪明，想请你帮他们编一个解二元一次方程组的程序。<BR>&nbsp;&nbsp;&nbsp;&nbsp;我们假定二元一次方程组的一般格式如下：(a,b,c,d,e,f为常数,x,y为未知数)<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ax+by=c<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dx+ey=f<BR>&nbsp;&nbsp;&nbsp;&nbsp;程序读入a,b,c,d,e,f后，输出解。<BR>&nbsp;&nbsp;&nbsp;&nbsp;当然，方程组也有可能存在无解或有无穷解的情况：如果(x,y)没有相对应的实数对满足方程组则无解；相反，如果(x,y)有多组对应的实数对满足方程组则有无数解。<BR>&nbsp;&nbsp;&nbsp;&nbsp;如果无解，就输出“No&nbsp;answer”；如果有无穷解，就输出“Too&nbsp;many”。 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;输入仅1行，包含6个整数，a,b,c,d,e,f。输入数据保证正确。 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;如果有解，那么第1行先输出“x=”，再输出x的值，第2行先输出“y=”，再输出y的值，均保留2位小数，请参照样例输出。<BR>&nbsp;&nbsp;&nbsp;&nbsp;如果无解或有无数解则按要求输出“No&nbsp;answer”或“Too&nbsp;many”。&nbsp;<BR> 

 
 # 提示 
【样例解释】<BR>二元一次方程组为：<BR>x+y=2<BR>x-y=0<BR>解为x=1,y=1<BR><BR>【数据范围】<BR>-100≤a,b,c,d,e,f≤100<BR>对于40%的数据，方程组无解或有无数解<BR>对于60%的数据，方程组有解<BR>寒假模拟赛&nbsp;普及组&nbsp;第一题 
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
<tr><td>1 1 2 1 -1 0
</td><td>x=1.00
y=1.00
</td></tr></table>

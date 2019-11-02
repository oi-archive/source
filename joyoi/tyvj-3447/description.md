# 

 
 # 题目描述 
<p>
画图的苦恼（math.pas\c\cpp）<br><br>【题目描述】<br>　　xm这段时间数学学到了必修5第三章的“二元一次不等式(组)与简单的线性规划问题”，这类题的解法常常要画坐标轴。为此xm非常的头痛。这类题总是这样出的：<br>　　给出三条直线的方程，求它们围成的面积。<br>　　xm觉得这类题很白痴——不就是画出三条线然后求围成的面积嘛，只是不愿画罢了(-_-||宁愿睡觉也不愿画这么无聊的图)。于是，他找到了会编程的你——<br></p> 

 
 # 输入格式 
<p>
　　输入文件math.in<br>　　为了方便，三条直线均以一般式给出。<br>　　输入共三行，每行有三个实数，分别表示三条直线方程(Ax+By+C=0)中的A、B、C。即这三条直线方程为A1x+B1y+C1=0 、A2x+B2y+C2=0、 A3x+B3y+C3=0。<br>　　A、B、C的绝对值均小于等于100000。</p> 

 
 # 输出格式 
<p>
　　输出文件math.out:<br>　　若能围成封闭的图形则输出一个实数(保留三位小数)，表示这三条直线围成的面积。<br>　　若不能围成封闭的图形则输出“Impossible”。<br></p> 
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
<tr><td>-1 1 1
1 0 0
0 1 0
</td><td>0.500</td></tr></table>

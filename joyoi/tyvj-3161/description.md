# 

 
 # 题目描述 
<p>
第四幕 水晶头骨

 
 # 输入格式 
<p>
　　每个输入包括多组数据。每组数据的第一行是一个数n，代表有n根柱子，如果n=0，则代表文件结束；接下来的n行，每行三个实数xi，yi，ri，代表第i根圆柱的圆心平面坐标和半径；接着有4个数，表示劳拉在这个方案中设定的出发点和出发方向。</p> 

 
 # 输出格式 
<p>
　　对于每一个计划，首先一行，输出"Plan"和数据的编号。接下来，如果劳拉能够在10次之内结束弹射，则先输出她所碰到的那些柱子的编号，再输出一行"succeed"；如果不能，则输出她碰到的前10根柱子的编号，然后一行输出"fail"。</p> 

 
 # 提示 
<p>
尾声
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
<tr><td>　　3
　　3 3 2
　　7 7 1
　　8 1 1
　　3 8 1 -4
　　2
　　0 0 1
　　5 0 2
　　2 0 1 0
　　0
</td><td>　　Plan 1 
　　1 2 1 3
　　succeed
　　Plan 2
　　2 1 2 1 2 1 2 1 2 1
　　fail
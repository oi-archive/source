# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-3646/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzY0Ni9wcm9ibGVtc19pbWFnZXMvMjQ5OC8xMjA0XzEuanBn.jpg"></p> 

 
 # 输入格式 
<p>
第一行为3个整数n，m和t。其中1<=n，n+1<=m<=3000，1<=t<=100000，m表示圆的个数，并且圆的编号为1~m。t为特殊点对数。<br>50%的数据满足m<=300，t<=1000。第二行为n个正整数R1~Rn，并且当i>=1时有1<Ri<Ri-1-1。接下来的m行表示各个圆<br>每行有4个数Xi，Yi，Si和Fi，（Xi，Yi）是圆i的圆心位置，圆i的半径是RSi，与圆i相切的尺寸更大的圆的编号是Fi，Xi<br>和Yi可能是实数，并且X1=Y1=S1=F1=0。再接下来的t行表示各个特殊点对，每行有4个数PiW，PiA，QiW和QiA<br>用于描述一个特殊点对(Pi，Qi)的位置：PiW表示点Pi处于PiW这个圆上，并且以此圆圆心为原点的幅角为PiA（0<=PiA<2π）。<br>QiW表示点Qi处于QiW这个圆上，并且以此圆圆心为原点的幅角为QiA（0<=QiA<2π）。输入数据保证PiW≠QiW<br>任意特殊点不会同时处于两个圆上（即切点处无特殊点）并且一个圆最多与10个圆相切。<br><br><br><img border="0" src="/source/joyoi/tyvj-3646/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzY0Ni9wcm9ibGVtc19pbWFnZXMvMjQ5OC8xMjA0XzIuanBn.jpg"><br></p> 

 
 # 输出格式 
<p>
<br>包含t行，其中第i行是一个整数Li，表示从点Pi到点Qi的最短光滑路径的长度/π后精确到整数的结果。<br></p> 
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
<tr><td>1 3 3                          
50000                         
0 0 0 0                       
150000 0 1 1
0 150000 1 1
3 5.497787 	  2 2.356194
3 1.570796 	  2 0.0
3 0.0         2 1.570796
</td><td>
175000
150000
200000</td></tr></table>

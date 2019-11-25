# 

 
 # 题目描述 
<p>
给出一个水池的底面积及高度。<br>现在把一些立方体放到其中，问最终水平面的高度.<br>注意:<br>1:水的密度为1.0<br>2:空气的影响忽略不计<br>3:立方体完全放到水池中。<br>4:立方体不会旋转且相互不会接触 。<br><img border="0" src="/source/joyoi/tyvj-2281/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjI4MS9wcm9ibGVtc19pbWFnZXMvMjY1MS8xMzc0LmpwZw==.jpg"><br></p> 

 
 # 输入格式 
<p>
第一行给出S,H,V，（0<s<=1000,0<H<=1000,0<V<=S*H）<br>分别代表水池的底面积及高度，以及最初其中有多少水。<br>第二行给出数字N,代表放多少个立方体以水池中。<br>下面有 N 行(0<N<=1000)，每行两个数字L,D(0<L<=1000,0<D<=10).代表立方体的长度及密度 。</p> 

 
 # 输出格式 
<p>
最终水平面的高度，答案误差不超过10^-4</p> 
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
<tr><td>100 10 500
1
1 0.5</td><td>5.0050</td></tr></table>

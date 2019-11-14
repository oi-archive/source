# 

 
 # 题目背景 
一个Oj怎马能够木有计算几何题目...<BR>作为一个弱菜&nbsp;就来加上一个简单的计算几何问题吧<BR> 

 
 # 题目描述 
输入一堆点&nbsp;点的位置以直角坐标给出<BR>输出一个最小的凸形&nbsp;要包含所有的点<BR>所谓凸&nbsp;就是形内任意两点所连线段都在形内<BR>凸形用顶点集描述<BR>要求点集的第一个点是横坐标最小的<BR>如果有多个横坐标最小的输出其中纵坐标最小的<BR>剩下的点依次以顺时针方向输出<BR>最后一个要求&nbsp;描述凸形用的点要最少<BR>保证这个点集是唯一的<BR> 

 
 # 输入格式 
第一行一个整数N(2&lt;N&lt;100001)&nbsp;代表输入点集中点的个数<BR>以下2~N+1行&nbsp;每行一个实数对&nbsp;代表点的坐标<BR> 

 
 # 输出格式 
输出描述凸形的点集<BR>每行一个数对&nbsp;代表一个点的直角坐标<BR>保留4位小数<BR> 

 
 # 提示 
建议pascal用extended<BR>建议c语言用long&nbsp;double<BR>数据精度在1e-12以内Bob&nbsp;HAN<BR>凸包测试题 
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
0 0
1 1
1 0
</td><td>0.0000 0.0000
1.0000 1.0000
1.0000 0.0000
</td></tr></table>

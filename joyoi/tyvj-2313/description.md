# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2313/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjMxMy9wcm9ibGVtc19pbWFnZXMvMjY5Mi8xNDE1XzEuanBn.jpg"></p> 

 
 # 输入格式 
<p>
数据的第1行为两个整数N和E，以空格分隔，分别表示森林中的景点数和连接相邻景点的路的条数。<br>第2行包含两个整数C和M，以空格分隔，分别表示初始时聪聪和可可所在的景点的编号。<br>接下来E行，每行两个整数，第i+2行的两个整数Ai和Bi表示景点Ai和景点Bi之间有一条路。<br>所有的路都是无向的，即：如果能从A走到B，就可以从B走到A。<br>输入保证任何两个景点之间不会有多于一条路直接相连，且聪聪和可可之间必有路直接或间接的相连。<br><br></p> 

 
 # 输出格式 
<p>
输出1个实数，四舍五入保留三位小数，表示平均多少个时间单位后聪聪会把可可吃掉。<br><br></p> 

 
 # 提示 
<p>
【样例说明1】<br>开始时，聪聪和可可分别在景点1和景点4。<br>第一个时刻，聪聪先走，她向更靠近可可(景点4)的景点走动，走到景点2，然后走到景点3；假定忽略走路所花时间。<br>可可后走，有两种可能：<br>第一种是走到景点3，这样聪聪和可可到达同一个景点，可可被吃掉，步数为1，概率为 。<br>第二种是停在景点4，不被吃掉。概率为 。<br>到第二个时刻，聪聪向更靠近可可(景点4)的景点走动，只需要走一步即和可可在同一景点。因此这种情况下聪聪会在两步吃掉可可。<br>所以平均的步数是1* +2* =1.5步。<br><img border="0" src="/source/joyoi/tyvj-2313/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjMxMy9wcm9ibGVtc19pbWFnZXMvMjY5Mi8xNDE1XzIuanBn.jpg"><br><br>对于所有的数据，1≤N,E≤1000。<br>对于50%的数据，1≤N≤50。<br></p> 
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
<tr><td>【输入样例1】
4 3
1 4
1 2
2 3
3 4
【输入样例2】
9 9
9 3
1 2
2 3
3 4
4 5
3 6
4 6
4 7
7 8
8 9
</td><td>【输出样例1】
1.500
【输出样例2】
2.167</td></tr></table>

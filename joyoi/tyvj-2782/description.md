# 

 
 # 题目描述 
<p>
一家工厂的流水线正在生产一种产品，这需要两种操作：操作A和操作B。每个操作只有一些机器能够完成。 <br><br><center><img src="/source/joyoi/tyvj-2782/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjc4Mi9wcm9ibGVtc19pbWFnZXMvMzMwMi9wZy5qcGc=.jpg"></img></center><br>上图显示了按照下述方式工作的流水线的组织形式。A型机器从输入库接受工件，对其施加操作A，得到的中间产品存放在缓冲库。B型机器从缓冲库接受中间产品，对其施加操作B，得到的最终产品存放在输出库。所有的机器平行并且独立地工作，每个库的容量没有限制。每台机器的工作效率可能不同，一台机器完成一次操作需要一定的时间。 <br>给出每台机器完成一次操作的时间，计算完成A操作的时间总和的最小值，或者完成B操作的时间总和的最小值。 <br><br></p> 

 
 # 输入格式 
<p>
<br><center><img src="/source/joyoi/tyvj-2782/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjc4Mi9wcm9ibGVtc19pbWFnZXMvMzMwMi9wZzIuanBn.jpg"></img></center><br></p> 

 
 # 输出格式 
<p>
只有一行。输出两个整数：完成所有A操作的时间总和的最小值，或者完成所有B操作的时间总和的最小值（A操作必须在B操作之前完成）。</p> 

 
 # 提示 
<p>
SAMPLE INPUT 2:<br>5 2 3<br>1 1 3 1 4<br>2<br>SAMPLE OUTPUT2:<br>5<br></p> 
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
<tr><td>5 2 3
1 1 3 1 4
1
</td><td>3</td></tr></table>

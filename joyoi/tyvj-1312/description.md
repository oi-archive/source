# 

 
 # 题目描述 
&nbsp;&nbsp;在一个月黑风高的夜晚,有一群人在河的右岸,想通过唯一的一根独木桥走到河的左岸.在伸手不见五指的黑夜里,过桥时必须借照灯光来照明,不幸的是,他们只有一盏灯.另外,独木桥上最多能承受两个人同时经过,否则将会坍塌.每个人单独过独木桥都需要一定的时间,不同的人要的时间可能不同.两个人一起过独木桥时,由于只有一盏灯,所以需要的时间是较慢的那个人单独过桥所花费的时间.现在输入N(2&lt;=N&lt;1000)和这N个人单独过桥需要的时间,请计算总共最少需要多少时间,他们才能全部到达河左岸.<BR>&nbsp;&nbsp;例如,有3个人甲&nbsp;&nbsp;乙&nbsp;&nbsp;丙,他们单独过桥的时间分别为1&nbsp;&nbsp;2&nbsp;&nbsp;4,则总共最少需要的时间为7.具体方法是:甲&nbsp;&nbsp;乙一起过桥到河的左岸,甲单独回到河的右岸将灯带回,然后甲,丙在一起过桥到河的左岸,总时间为2+1+4=7. 

 
 # 输入格式 
第一行为N，表示有N个人<BR>下面一行有n个数，表示每个人的过河时间 

 
 # 输出格式 
一个数，即全部人过河的最短时间<BR> 
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
1 2 4</td><td>7
</td></tr></table>

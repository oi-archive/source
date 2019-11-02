# 

 
 # 题目描述 
huyichen世子事件后，xuzhenyi成了皇上特聘的御前一品侍卫。<BR><BR>皇宫以午门为起点，直到后宫嫔妃们的寝宫，呈一棵树的形状；某些宫殿间可以互相望见。大内保卫森严，三步一岗，五步一哨，每个宫殿都要有人全天候看守，在不同的宫殿安排看守所需的费用不同。<BR><BR>可是xuzhenyi手上的经费不足，无论如何也没法在每个宫殿都安置留守侍卫。<BR><BR>帮助xuzhenyi布置侍卫，在看守全部宫殿的前提下，使得花费的经费最少。 

 
 # 输入格式 
输入文件中数据表示一棵树，描述如下：<BR><BR>第1行&nbsp;n，表示树中结点的数目。<BR><BR>第2行至第n+1行，每行描述每个宫殿结点信息，依次为：该宫殿结点标号i（0&lt;i&lt;=n），在该宫殿安置侍卫所需的经费k，该边的儿子数m，接下来m个数，分别是这个节点的m个儿子的标号r1，r2，...，rm。<BR><BR>对于一个n（0&nbsp;&lt;&nbsp;n&nbsp;&lt;=&nbsp;1500）个结点的树，结点标号在1到n之间，且标号不重复。<BR><BR> 

 
 # 输出格式 
输出文件仅包含一个数，为所求的最少的经费。 

 
 # 提示 
如图<BR><img src="/source/joyoi/tyvj-1513/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTUxMy9odHRwOi8vdHl2ai5jcHd6LmNuL1Byb2JsZW1JbWcvcDE1MTMuanBn.jpg" border=0 align=middle>huyichen 
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
<tr><td>6
1 30 3 2 3 4
2 16 2 5 6
3 5 0
4 4 0
5 11 0
6 5 0</td><td>25</td></tr></table>

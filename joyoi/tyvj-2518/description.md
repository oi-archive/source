# 

 
 # 题目描述 
<p>
农民 John 的牛参加了一次和农民 Bob 的牛的竞赛。他们在区域中画了一个N*N<br>的正方形点阵，两个农场的牛各自占据了一些点。当然不能有两头牛处于同一个<br>点。农场的目标是用自己的牛作为4个顶点，形成一个面积最大的正方形(不必须<br>和边界平行) 。<br><br>除了 Bessie 以外，FJ其他的牛都已经放到点阵中去了，要确定bessie放在哪个<br>位置，能使得农民约翰的农场得到一个最大的正方形(Bessie不是必须参与作为<br>正方形的四个顶点之一)。<br><br></p> 

 
 # 输入格式 
<p>
* Line 1: 一个整数 N<br><br>* Lines 2..N+1: 第 i+1 行描述点阵的第i行，有 N 个字符。字符集是： <br>'J' 表示这个点是农民 John 的牛， 'B'表示这个点是农民 Bob 的牛，<br>'*' 表示这个点没有被占据。保证至少有一个点没有被占据。<br><br></p> 

 
 # 输出格式 
<p>
<br>* Line 1: 最大正方形的面积，或者无解的话输出0。<br><br></p> 
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
<tr><td>
6
J*J***
******
J***J*
******
**B***
******
</td><td>
4

输出解释:

如果 Bessie 可以占据 农民 Bob 的牛所占的点，那么可以生成一个面积为8
的正方形，但是她只能放到第3行第3列，形成一个最大的、面积为 4个正方形。</td></tr></table>

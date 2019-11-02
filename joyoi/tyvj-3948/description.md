# 

 
 # 题目背景 
<p>THU是一所历史悠久的名校，这里萦绕了太多人难以忘怀的记忆。wyx记得，在一次地震疏散演习中，同学们从教室出发，到达不同的路口，最后聚集在操场。对此，小A认为所有人都到达操场会使得场地变得拥挤，他想请你来解决下面的问题。</p> 

 
 # 题目描述 
<p>我们设学校中共有<em>n</em>个区域，不同的区域之间由<em>n</em>&nbsp;&ndash;&nbsp;1条无向边连接，构成一棵无根树，其中第<em>i</em>个区域有<em>a<sub>i</sub></em>个人。在一次演习中，第<em>x</em>个区域和第<em>y</em>个区域将被作为<strong><u>聚集点</u></strong>。定义第<em>i</em>个区域到第<em>j</em>个区域的距离为D(i,j)，这个值表示从第<em>i</em>个区域到第<em>j</em>个区域所经过的最少边数。定义C(i,j)表示将区域<em>i</em>的人全部转移到区域<em>j</em>所需要的<strong><u>转移代价</u></strong>，C(i,j)&nbsp;=&nbsp;<i>a<sub><font size="2">i</font></sub></i>&nbsp;*&nbsp;D(i,j)。定义<strong><u>总转移代价</u></strong>&nbsp;T=&sum;(1~n)&nbsp;min{C(i,x),&nbsp;C(i,y)}。小A想请你来决定<em>x</em>和<em>y</em>的值，使得<em>T&nbsp;</em>的值最小。</p> 

 
 # 输入格式 
<p>第一行包括一个正整数<em>n</em>表示区域数。</p>

<p>接下来<em>n</em>&nbsp;&ndash;&nbsp;1行每行两个正整数<em>u</em>和<em>v</em>，表示区域<em>u</em>和区域<em>v</em>之间有一条无向边连接。</p>

<p>接下来一行包含<em>n</em>个正整数，第<em>i</em>个正整数为<em>a<sub>i</sub></em>，表示第<em>i</em>个区域的人数。</p> 

 
 # 输出格式 
<p>只有一个整数，表示<em>T&nbsp;</em>的最小值。</p> 

 
 # 提示 
<p>【数据规模与约定】</p>

<p>所有测试点的数据规模如下：</p>

<table align="center" border="1" cellpadding="0" cellspacing="0" style="width: 290px;" width="435">
	<tbody>
		<tr>
			<td style="width: 145px;">
			<p align="center">测试点编号</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>的规模</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">1</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;2</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">2</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;3</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">3</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;50</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">4</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;100</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">5</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;300</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">6</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;500</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">7</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;800</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">8</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;1,000</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">9</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;3,000</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">10</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;5,000</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">11</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;8,000</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">12</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;10,000</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">13</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;15,000</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">14</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;20,000</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">15</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;25,000</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">16</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;30,000</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">17</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;35,000</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">18</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;40,000</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">19</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;45,000</p>
			</td>
		</tr>
		<tr>
			<td style="width: 145px;">
			<p align="center">20</p>
			</td>
			<td style="width: 145px;">
			<p align="center"><em>n</em>&nbsp;=&nbsp;50,000</p>
			</td>
		</tr>
	</tbody>
</table>

<div style="clear: both;">&nbsp;</div>

<p>对于全部测试数据满足1&nbsp;&le;&nbsp;<em>a<sub>i</sub></em>&nbsp;&le;&nbsp;1,000。</p>

<p>【关于数据中无根树的生成方式】</p>

<p>首先随机生成一个1到<em>n</em>的排列<em>x<sub>i</sub></em>。对于第<em>i</em>条边，令这条边的某一个端点为<em>i</em>&nbsp;+&nbsp;1，另一个端点为取值在1到<em>i</em>之间的某个随机数，我们设此时这条边的两个端点分别为<em>p</em>和<em>q</em>，接下来执行<em>p</em>&nbsp;&larr;&nbsp;<em>x<sub>p</sub></em>，<em>q</em>&nbsp;&larr;&nbsp;<em>x<sub>q</sub></em>。最后将这<em>n</em>&nbsp;&ndash;&nbsp;1条边打乱输出至输入文件中。</p> 
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
<tr><td>5
1 2
1 3
3 4
3 5
5 7 6 5 4
</td><td>14
</td></tr><tr><td>28
1 2
1 4
1 6
1 11
1 20
1 26
2 3
2 21
3 8
3 15
4 5
4 13
4 16
5 9
6 7
6 10
6 18
7 17
9 12
10 27
11 14
11 22
14 24
18 19
20 25
22 23
23 28
502 712 636 657 292 518 612 471 858 420 254 579 560 187 235 321 938 329 955 191 137 454 606 465 984 848 467 277
</td><td>26850
</td></tr></table>

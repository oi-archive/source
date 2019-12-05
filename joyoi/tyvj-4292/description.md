# 

 
 # 题目背景 
<p>许多天后，马克沃特尼就要和他的队友们相见了。但是还有一道难题&mdash;&mdash;燃料。</p> 

 
 # 题目描述 
<p>马克沃特尼在同行化学家阿莱克斯沃格尔的电脑里找到了许多化学燃料的配置方法。他将这些化学燃料按照一定的顺序排序，配置完的所有的化学燃料。请找出所使用的化学燃料放出热的最大值，以便马克沃特尼能够驾驶战神4号飞上火星外围轨道。</p>

<p>注意：每个化学燃料<strong>只能使用一次</strong>；在每个化学燃料上有一个说明f，即选的化学燃料的编号为i，则<strong>第</strong><strong>i+1~f-1</strong><strong>的化学燃料都因会发生反应导致危险不能再选</strong>。同时，为了节约战神4号燃料舱的空间，<strong>最多只能选择</strong><strong>k</strong><strong>个燃料</strong>。数据保证每个化学燃料的说明都大于其编号。</p> 

 
 # 输入格式 
<p>输入第一行两个正整数N和K，表示化学燃料的个数和最多选择化学品的个数。</p>

<p>接下来一行N个数，表示该化学燃料的放出热的单位值，这个单位值总是[1,10000]间的整数。</p>

<p>接下来一行N-1个数，表示该化学燃料的说明f，最后一个化学燃料不需说明。</p> 

 
 # 输出格式 
<p>输出只有一行，即这个答案的最大值。</p> 

 
 # 提示 
<p>对于20%的数据，1&le;n，k&le;20；</p>

<p>对于50%的数据，1&le;n&le;10<sup>4</sup>，1&le;k&le;100；</p>

<p>对于100%的数据，1&le;n&le;10<sup>5</sup>，1&le;k&le;400。</p> 
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
<tr><td>3 5
2 3 5
3 3
</td><td>8</td></tr><tr><td>5 2
10 2 9 8 6
5 4 4 5
</td><td>17</td></tr></table>

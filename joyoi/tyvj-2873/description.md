# 

 
 # 题目描述 
<p>
当前有n（n<=12）个工作，和8个工人。现在每个工作需要占用一个工人的从[a，b]这个区间的时间（一个工人自然不可能在同一个时间做2个不同的工作），且一个工作不一定是所有工人都能够完成的。现在给出每个工作的描述，问是否存在一种安排方案使得所有工作都能完成。</p> 

 
 # 输入格式 
<p>
输入文件有多组数据。第一行一个数tot表示数据的组数，后面紧接tot组数据。<br>对于每一组数据的第一行有一个整数n，表示工作的数目。后面n行每行描述一个工作。<br>对于一个工作，a，b，k，h1，h2……hk来描述，表示这个工作需要占用一个工人[a，b]的时间，并且能够完成这个工作的工人只有k个，标号分别是h1，h2……hk。<br></p> 

 
 # 输出格式 
<p>
对于每组输入数据，输出一行YES（如果可以安排一种方案使得工作完成）或者是NO（无法安排一种方案）。</p> 
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
<tr><td>2
2
1 1 1 1 
2 2 1 1
2
1 2 1 1 
2 2 1 1
</td><td>YES
NO</td></tr></table>

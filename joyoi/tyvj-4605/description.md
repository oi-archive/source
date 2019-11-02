# 

 
 # 题目描述 
<p align="left">遠月的秋季選拔正如火如荼地进行着，一位位出色的料理人各显神通。</p>

<p align="left">不过非常遗憾的是，由于学园没有充分地事先通知，导致学生们一个个都没有自备足够的刀、勺、锅等用具。于是为了补救这场遠月最隆重的活动之一的秋季選拔賽，十傑评议会立刻决定动用厨房里所有剩余的炊具供学生们比赛用。</p>

<p align="left">现在每个学生们持有了一定的厨具，但是每人都还需要各种厨具若干份，现有的器材不一定能同时满足所有的学生。于是大会决定将比赛的机制临时变动，可以把厨具先供给部分学生，当他们完成比赛后，把他们已有的厨具全部交出来再继续供其他学生使用。</p>

<p align="left">但是大会无法做出一个明确判断：这样是否能够让比赛顺利进行？所以他们把处理数据的任务交给了shy。像shy这种蒟蒻看看（<strike><span style="line-height: 20.8px;">题</span></strike><span style="line-height: 1.6em;"><strike>解</strike>）就会做，所以就把任务推给你了。</span></p>

<p align="left">（考~考~你~：题目描述中有一处语病，你能发现吗？）</p> 

 
 # 输入格式 
<p align="left">第一行：一个整数T，表示多组数据的组数。</p>

<p align="left">每组数据的第一行：N,M，N表示学生的人数，M表示炊具的种类数。</p>

<p align="left">接下来M行每行N个数：A[I,J]，表示学生J总共须获得第I种炊具A[I,J]份。</p>

<p align="left">接下来M行每行N个数：B[I,J]，表示学生J还需要第I种炊具B[I,J]份。（现在持有的炊具可以通过A-B求得）</p>

<p align="left">接下来M个数：C[i]，表示现在学校厨房拥有第I种炊具C[I]份。</p> 

 
 # 输出格式 
<p align="left">对于每组数据，输出1行，Yes表示比赛可以顺利进行，No表示不能。</p> 

 
 # 提示 
<p align="left">提升厨艺最好的方法就是遇到一个你想要把自己全部的料理都先给她的女人&mdash;&mdash;语出药王他爸（好像有奇怪的东西混进来了，<strike>所以叶山才冠军的么</strike>）。</p>

<p align="left">对于10组数据：</p>

<p align="left">A,B,C&lt;=N。</p>

<p align="left">10%的数据，T&lt;=2,N&lt;=2333,M&lt;=2。</p>

<p align="left">90%的数据，T&lt;=3,N&lt;=23333,M&lt;=3。</p>

<p align="left"><img alt="" src="/source/joyoi/tyvj-4605/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotNDYwNS9odHRwOi8vd3d3LnR5dmouY24vQXZhdGFyLzQyNTA3" style="width: 690px; height: 975px;" /></p>

<p align="left">对于额外的10组数据：</p>

<p align="left">A,B,C&lt;=N。</p>

<p align="left">10%的数据，T&lt;=3,N&lt;=66666,M&lt;=4。</p>

<p align="left">90%的数据，T&lt;=3,N&lt;=66666,M&lt;=11。</p>

<p align="left"><u>Thanks&nbsp;for&nbsp;viewing&nbsp;this&nbsp;problem.</u></p> 
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
4 3
1 6 2 0
0 1 1 0
0 2 1 2
2 0 1 4
2 0 0 2
2 1 3 0
0 1 1
4 3
2 5 2 0
0 1 1 0
1 1 1 2
1 1 1 4
2 0 0 2
1 2 3 0
0 1 1</td><td>Yes
No
</td></tr></table>

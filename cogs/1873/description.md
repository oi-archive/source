# 题目描述


<div class="content">
<!--begin main-->
<!-- InstanceBeginEditable name="content" -->
<h3>
【试题来源】
</h3>
<div id="psrc" style="margin-top:20px;display:block;">
<div class="pdcont">
2011中国国家集训队命题答辩
</div>
</div>
<div id="pinputs" style="display:none;">
<div class="pdsec">
输入数据
</div>
<div class="pdcont">
<span class="notice"> 这是一道提交答案的试题，下面给出了该题的输入数据：</span> 
</div>
<div id="inputlist" class="pddata">
</div>
</div>
<div id="pcont1" style="margin-top:20px;display:block;">
<h3>
【问题描述】
</h3>
<div class="pdcont">
高一一班的座位表是个n*m的矩阵，经过一个学期的相处，每个同学和前后左右相邻的同学互相成为了好朋友。这学期要分文理科了，每个同学对于选择文科与理科有着自己的喜悦值，而一对好朋友如果能同时选文科或者理科，那么他们又将收获一些喜悦值。作为计算机竞赛教练的scp大老板，想知道如何分配可以使得全班的喜悦值总和最大。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
第一行两个正整数n，m。<br/>
接下来是六个矩阵<br/>
第一个矩阵为n行m列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学选择文科获得的喜悦值。<br/>
第二个矩阵为n行m列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学选择理科获得的喜悦值。<br/>
第三个矩阵为n-1行m列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学与第i+1行第j列的同学同时选择文科获得的额外喜悦值。<br/>
第四个矩阵为n-1行m列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学与第i+1行第j列的同学同时选择理科获得的额外喜悦值。<br/>
第五个矩阵为n行m-1列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学与第i行第j+1列的同学同时选择文科获得的额外喜悦值。<br/>
第六个矩阵为n行m-1列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学与第i行第j+1列的同学同时选择理科获得的额外喜悦值。
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出一个整数，表示喜悦值总和的最大值
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
1 2<br/>
1 1<br/>
100 110<br/>
1<br/>
1000
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
1210
</div>
<h3>
【样例说明】
</h3>
<div class="pdcont">
两人都选理，则获得100+110+1000的喜悦值。
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
对于10%以内的数据，n,m&lt;=4<br/>
对于30%以内的数据，n,m&lt;=8<br/>
对于100%以内的数据，n,m&lt;=100 数据保证答案在2^30以内<br/>
对于100%的数据，时间限制为0.5s。
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<div class="pdsec">
【问题描述】
</div>
<div class="pdcont">
高一一班的座位表是个n*m的矩阵，经过一个学期的相处，每个同学和前后左右相邻的同学互相成为了好朋友。这学期要分文理科了，每个同学对于选择文科与理科有着自己的喜悦值，而一对好朋友如果能同时选文科或者理科，那么他们又将收获一些喜悦值。作为计算机竞赛教练的scp大老板，想知道如何分配可以使得全班的喜悦值总和最大。
</div>
<div class="pdsec">
【输入格式】
</div>
<div class="pdcont">
第一行两个正整数n，m。<br/>
接下来是六个矩阵<br/>
第一个矩阵为n行m列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学选择文科获得的喜悦值。<br/>
第二个矩阵为n行m列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学选择理科获得的喜悦值。<br/>
第三个矩阵为n-1行m列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学与第i+1行第j列的同学同时选择文科获得的额外喜悦值。<br/>
第四个矩阵为n-1行m列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学与第i+1行第j列的同学同时选择理科获得的额外喜悦值。<br/>
第五个矩阵为n行m-1列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学与第i行第j+1列的同学同时选择文科获得的额外喜悦值。<br/>
第六个矩阵为n行m-1列 此矩阵的第i行第j列的数字表示座位在第i行第j列的同学与第i行第j+1列的同学同时选择理科获得的额外喜悦值。
</div>
<div class="pdsec">
【输出格式】
</div>
<div class="pdcont">
输出一个整数，表示喜悦值总和的最大值
</div>
<div class="pdsec">
【样例输入】
</div>
<div class="pddata">
1 2<br/>
1 1<br/>
100 110<br/>
1<br/>
1000 
</div>
<div class="pdsec">
【样例输出】
</div>
<div class="pddata">
1210
</div>
<div class="pdsec">
【样例说明】
</div>
<div class="pddata">
两人都选理，则获得100+110+1000的喜悦值。
</div>
<div class="pdsec">
【数据规模】
</div>
<div class="pdcont">
对于10%以内的数据，n,m&lt;=4<br/>
对于30%以内的数据，n,m&lt;=8<br/>
对于100%以内的数据，n,m&lt;=100 数据保证答案在2^30以内<br/>
对于100%的数据，时间限制为0.5s。
</div>
</div>
</div>

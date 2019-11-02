<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>这个月的pku月赛某陈没有参加,因为当时学校在考试[某陈经常逃课,但某陈还没有强大到考试也可以逃掉的程度].何况,对于北大校赛,水牛通常是没有什么希望考得好的[事实上某陈最好成绩是仅A了一道题].</p>
<p>某陈郁闷.接下来他又将沉浸在无穷尽的刷题中,每天面对各种颜色的Status--WA,TLE,RE,甚至还有MLE,CE,PE什么什么的,他无比期待蓝色的AC.</p>
<p>话说RP爆发的某陈弄到了很久以后某次pku月赛的某题的题目和输入数据,如下所示.</p>
<p>输入数据包括n个测试点,每个点都有一个最大可获得的分数m.选手需要选定任意3个整数,i,j,m0,1&lt;=i&lt;=j&lt;=n,代表选手选择的测试点范围是从第i个到第j个,每个测试点的期望分数均为m0.本题为Special Judge[特殊评测],评测时系统将遍历标号从i到j的测试点,对于被遍历的每一个测试点,如果当前测试点的m小于m0,则终止评测并判定选手得分为0,否则系统将为选手得分加上m0[系统初始化选手得分为0].若最终选手得分与可能的最大得分相同,那么选手就AC了这题.</p>
<p>某陈已经为本题写了好久的代码,现在他需要知道本题可能的最大得分,来验证他的输出是否为最优解.请计算选手的最大得分,给某陈一个打表的机会~</p>
<p>[某陈:神啊..请赐予我力量吧..我需要一次华丽丽的AC..] </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行为一个整数n,如题目描述中的含义.0&lt;n&lt;=10^6</p>
<p>接下来的一行包括n个整数m,如题目描述中的含义.0&lt;=m&lt;2^31</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件包含一个整数,为题目描述中的最大得分.</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7</p>
<p>3 2 7 4 5 8 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>20</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>题目中</p>
</div>
</div>
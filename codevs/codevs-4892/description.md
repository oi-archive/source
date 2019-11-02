<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>二元一次方程组的一般形式如下：</p><p> ax+by=c</p><p> dx+ey=f</p><p>其中 a,c,d,f 只为非零整数，b,e只为正整数。</p><p><br></p><p>现在输入两个格式符合图中形式的方程(但加号可能改为减号)，</p><p>请给出两个方程所组成的方程组的解，</p><p>如果方程组有无数组解，输出“infinite solutions”，</p><p>如果方程组无解，输出“no solution”。</p><p><br></p><p>注意：虽然所有系数均为正整数，但解有可能出现分数。</p><p>如果解不是整数，请以 a/b 的形式输出，如为负数，输出 -a/b</p><p>如果系数为1，会输入1，如x-2y=4会被输入为1x-2y=4</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>分两行输入两个关于x,y的一般形式的二元一次方程</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>分两行以</p><p>x=m</p><p>y=n</p><p>的形式输出方程的解</p><p><span style="font-family: 微软雅黑,Microsoft YaHei; font-size: 14px;">如果方程组有无数组解，输出“infinite solutions”，</span></p><p><span style="font-family: 微软雅黑,Microsoft YaHei; font-size: 14px;">如果方程组无解，输出“no solution”。</span></p><p><span style="font-size: 16px;">&nbsp;</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例一：</p><p>-3x+4y=18</p><p>1x-3y=-46</p><p><br></p><p>样例二：</p><p>-23x+45=-34</p><p>47x-27y=31</p><p><br></p><p>样例三：</p><p>3x-5y=23</p><p>9x-15y=50</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例一：</p><p>x=26</p><p>y=24</p><p><br></p><p>样例二：</p><p>x=53/166</p><p>y=-295/498</p><p><br></p><p>样例三：</p><p>no solution</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>所有系数的绝对值不大于100000</p><p>a,c,d,f是非零整数；b,e是正整数</p>
</div>
</div>
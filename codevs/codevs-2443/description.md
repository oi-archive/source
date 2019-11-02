<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>桌上有一张边界平行于坐标轴的正方形纸片，左下角的坐标为(0,0)，右上角的坐标为(100,100)。接下来执行<em>n</em>条折纸命令。每条命令用两个不同点<em>P</em><sub>1</sub>(<em>x</em><sub>1</sub>,<em>y</em><sub>1</sub>)和<em>P</em><sub>2</sub>(<em>x</em><sub>2</sub>,<em>y</em><sub>2</sub>)来表示，执行时把当前的折纸作品沿着<em>P</em><sub>1</sub><em>P</em><sub>2</sub>所在直线折叠，并把有向线段<em>P</em><sub>1</sub><em>P</em><sub>2</sub>的右边折向左边（左边的部分保持不变）。</p>
<p>折叠结束后，需要在作品上打一个孔，然后用绳子穿起来挂在墙上。孔的位置是相当重要的：若需要穿过太多层的纸，打孔本身比较困难；若穿过的层数太少，悬挂起来以后作品可能会被撕破。为了选择一个比较合适的打孔位置，你需要计算在每个候选位置打孔时穿过的层数。如果恰好穿过某一层的边界（误差0.000001内），则该层不统计在结果中。</p>
<p>本题考虑一个简化的模型：纸的厚度不计，因此折纸操作总能完美执行。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行为一个整数<em>n</em>，即折纸的次数。以下<em>n</em>行每行四个实数<em>x</em><sub>1</sub>,<em>y</em><sub>1</sub>,<em>x</em><sub>2</sub>,<em>y</em><sub>2</sub>，表示每次折纸时对应的有向线段。下一行包含一个正整数<em>m</em>，即候选位置的个数，以下每行包含两个实数<em>x</em>,<em>y</em>，表示一个候选位置。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>每个候选位置输出一行，包含一个整数，即该位置打孔时穿过的层数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>-0.5 -0.5 1 1</p>
<p>1 75 0 75</p>
<p>6</p>
<p>10 60</p>
<p>80 60</p>
<p>30 40</p>
<p>10 10</p>
<p>50 50</p>
<p>20 50</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>2</p>
<p>2</p>
<p>0</p>
<p>0</p>
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>20%的数据满足：<em>n</em>&lt;=1</p>
<p>100%的数据满足：0&lt;=<em>n</em>&lt;=8, 1&lt;=<em>m</em>&lt;=50</p>
</div>
</div>
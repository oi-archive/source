<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>HURRICANE小组的成员最近去工厂实习，在实习的过程中遇到了这样的一个问题。即要在一个<span style="text-decoration: underline;">模板</span>内，切割出一个<span style="text-decoration: underline;">零件</span>。现已知<span style="text-decoration: underline;">模板</span>和<span style="text-decoration: underline;">零件</span>都是给定的凸多边形，且<span style="text-decoration: underline;">零件</span>在<span style="text-decoration: underline;">模板</span>中的位置已经固定。我们知道，对于<span style="text-decoration: underline;">零件</span>来说，除相邻的两边外，任何两条边的延长线的交点都在<span style="text-decoration: underline;">模板</span>之外。</p>
<p>由于工厂的加工条件所限，切割时，每一刀必须沿<span style="text-decoration: underline;">零件</span>的某一条边所在的直线切下，把<span style="text-decoration: underline;">模板</span>分成两部分，然后保留含有<span style="text-decoration: underline;">零件</span>的一部分，再继续切割。现定义每一刀的费用为<span style="text-decoration: underline;">模板</span>上切痕的长度。问如何选择切割顺序，才能使花费最少？</p>
<p>你的程序需要根据给定的输入，给出符合题意的输出：</p>
<p>l  输入包括<span>模板</span>及<span>零件</span>的形状和坐标；</p>
<p>l  你需要根据给出的输入，计算出把<span>模板</span>切割成为<span>零件</span>的最少花费；</p>
<p>l  输出中只包括一个数，即最少的花费。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件包括两个部分，分别描述<span style="text-decoration: underline;">模板</span>和<span style="text-decoration: underline;">零件</span>的形状及坐标：</p>
<p>l  第一行为<span style="text-decoration: underline;">模板</span>的顶点个数<em>n</em>（3≤ <em>n</em>≤ 2000）。下面的<em>n</em>行每行两个实数<em>x</em>，<em>y</em>（-1,000,000&lt;<em>x, y</em>&lt;1,000,000），为按逆时针方向给出<span style="text-decoration: underline;">模板</span>顶点的坐标。</p>
<p>l  第<em>n</em>+2行为<span style="text-decoration: underline;">零件</span>的顶点个数<em>m</em>（3≤ <em>m</em>≤ 2000）。下面的<em>m</em>行每行两个实数<em>x</em>，<em>y</em>（-1,000,000&lt;<em>x, y</em>&lt;1,000,000）为按逆时针方向给出的<span style="text-decoration: underline;">零件</span>顶点的坐标。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件中只需要包括一个整数，为最少花费四舍五入到整数后的值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>0 0</p>
<p>3 0</p>
<p>3 3</p>
<p>0 3</p>
<p>4</p>
<p>0 0</p>
<p>2 0</p>
<p>2 3</p>
<p>0 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>3≤ <em>n</em>≤ 2000</p>
</div>
</div>
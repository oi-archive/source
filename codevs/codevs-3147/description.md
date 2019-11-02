<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给出两个n*n的矩阵，m次询问它们的积中给定子矩阵的数值和。</p><p>*为防止卡评测，已减小数据范围并调低时限。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个正整数n，m。<br>接下来n行，每行n个非负整数，表示第一个矩阵。<br>接下来n行，每行n个非负整数，表示第二个矩阵。<br>接下来m行，每行四个正整数a，b，c，d，表示询问第一个矩阵与第二个矩阵的积中，<br>以第a行第b列与第c行第d列为顶点的子矩阵中的元素和。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对每次询问，输出一行一个整数，表示该次询问的答案。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 2<br>1 9 8<br>3 2 0<br>1 8 3<br>9 8 4<br>0 5 15<br>1 9 6<br>1 1 3 3<br>2 3 1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>661<br>388</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据规模和约定】</p><p>对40%的数据满足，n &lt;= 100，m &lt;= 1000。<br>对100%的数据满足，n &lt;= 800，m &lt;= 10000，输入数据中矩阵元素 &lt; 100，a，b，<br>c，d &lt;= n。</p><p>数据有梯度。</p>
</div>
</div>
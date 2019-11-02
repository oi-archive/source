<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    Welcome to ALO ( Arithmetic and Logistic Online)。这是一个VR MMORPG，如名字所见，到处充满了数学的谜题。<br>    现在你拥有n 颗宝石，每颗宝石有一个能量密度，记为ai，这些宝石的能量密度两两不同。现在你可以选取连续的一些宝石（必须多于一个）进行融合，设为a<sub>i</sub>, a<sub>i+1</sub>, …, a<sub>j</sub>，则融合而成的宝石的能量密度为这些宝石中能量密度的次大值与其他任意一颗宝石的能量密度按位异或的值，即，设该段宝石能量密度次大值为k，则生成的宝石的能量密度为max{k xor a<sub>p</sub> | a<sub>p</sub> ≠ k , i ≤ p ≤ j}。<br>    现在你需要知道你怎么选取需要融合的宝石，才能使生成的宝石能量密度最大。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，一个整数n，表示宝石个数。<br>第二行，n 个整数，分别表示a<sub>1</sub> 至a<sub>n</sub>，表示每颗宝石的能量密度，保证对于i ≠ j 有a<sub>i</sub> ≠ a<sub>j</sub>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一行一个整数，表示最大能生成的宝石能量密度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5<br>9 2 1 4 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>14</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例解释】<br>选择区间[1,5]，最大值为7 xor 9。<br>【数据规模与约定】<br>对于20%的数据有n ≤ 100。<br>对于50%的数据有n ≤ 2000。<br>对于100%的数据有1 ≤ n ≤ 50000, 0 ≤ a<sub>i</sub> ≤ 109。</p>
</div>
</div>
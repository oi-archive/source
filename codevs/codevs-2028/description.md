<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    组合子逻辑是Moses Schönfinkel 和Haskell Curry 发明的一种符号系统，用于消除数理逻辑中对于变量的需要。本题考察一种与真实世界的组合子演算略有差别的组合子系统。<br>    一个组合子项是下列形式之一：<br>    P<br>    (E1 E2)<br>    其中P 表示一个基本函数，E1以及E2表示一个组合子项(可以相同)。不满足以上形式的表达式均非组合子项。<br>    我们将一个组合子项E 的参数个数np(E)如下：<br>    np(P) = 基本函数P 的参数个数； <br>    np((E1 E2)) = np(E1) - 1。<br>    本题中，我们用一个正整数同时表示一个基本函数，以及该基本函数的参数个数。<br>    对于一个组合子项E，如果它和它包含的所有组合子项的参数个数np 均为正整数，那么我们称这个E为范式。 <br>    我们经常组合子项简化表示：如果一个组合子项E含有连续子序列(… ((E1 E2) E3) …En) (其中n ≥ 3)，其中Ek表示组合子项(可以是简化表示的)，那么将该部分替换为(E1 E2 E3 … En)，其他部分不变，得到表达式E 的一个简化表示。一个组合子项可以被简化表示多次。<br>    给定一个基本函数序列，问至少需要添加多少对括号，才能使得该表达式成为一个范式的简化表示(即满足范式的性质)；如果无论如何怎样添加括号，均不能得到范式的简化表示，输出-1。</p>
<p> </p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个正整数T，表示有T 次询问。<br>接下来2T 行。<br>第2k 行有一个正整数nk，表示第k 次询问的序列中基本函数的个数。<br>第2k + 1 行有nk个正整数，其中第i 个整数表示序列中第i 个基本函数。 </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出T 行，每行一个整数，表示对应询问的输出结果。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 <br>5<br>3 2 1 3 2<br>5<br>1 1 1 1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3<br>-1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例解释】<br>第一次询问：一个最优方案是(3 (2 1) (3 2))。可以证明不存在添加括号对数更少的方案。<br>第二次询问：容易证明不存在合法方案。<br>【数据范围】<br>令TN 表示输入中所有n<sub>k</sub>的和。TN ≤ 2000000 <br>大数据参见http://pan.baidu.com/share/link?shareid=448938&amp;uk=4078610433</p>
</div>
</div>
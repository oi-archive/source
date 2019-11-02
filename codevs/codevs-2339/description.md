<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>沫沫最近在研究勾股定理。对于两个正整数A与B，若存在正整数C使得A<sup>2</sup>+B<sup>2</sup>=C<sup>2</sup>，且A与B互质，则称(A,B)为一个互质勾股数对。</p>
<p>有一天，沫沫得到了N根木棍，其长度都是正整数，她准备从中挑选出若干根木棍来玩拼图游戏，为了使拼出的图案有凌乱美，她希望挑选出的木棍中任意两根的长度均不是互质勾股数对。现在，沫沫想知道有多少种满足要求的挑选木棍的方案。由于答案可能很大，你只要输出答案对10<sup>9</sup>+7取模的结果。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是一个正整数N，表示共有多少根木棍。第二行是用空格隔开的N个正整数h<sub>1</sub>, h<sub>2</sub>, …, h<sub>N</sub>，其中对1≤i≤N，h<sub>i</sub>表示第i根木棍的长度。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>仅包含一个非负整数，表示满足要求的挑选木棍的方案数对<span lang="EN-US">10<sup>9</sup>+7</span>取模的结果。</span></p>

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
<p>5 12 35 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>样例解释</strong></p>
<p>（5,12）与（12,35）是互质勾股数对，故满足要求的挑选木棍的方案有8种，即： {5}，{12}，{35}，{5}，{5,35}，{35,5}，{5,5}，{5,35,5}。 </p>
<p><strong><br></strong></p>
<p><strong><br></strong></p>
<p><strong>数据范围</strong></p>
<p><strong></strong>30%的数据满足对1≤i≤N有1≤h<sub>i</sub>≤3000，另外30%的数据满足对1≤i≤N有1≤h<sub>i</sub>≤200000，剩下的40%的数据满足对1≤i≤N有20000≤h<sub>i</sub>≤1000000，100%的数据满足N≤1000000。 </p>
</div>
</div>
<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Liyundu大神成功邀请到了n个妹子。现在他让这n个妹子排成一个序列，每个妹子都拥有一个“需求值”Ai，由于liyundu大神比较虚，他只能撩到“需求值”小于等于他所能给予的最大值P的妹子，并且他只会撩给出的序列闭区间[S,E]中的妹子。现在给定你这n个妹子的“需求值”和m次询问，请你帮助他计算一下每次最多能撩到多少个妹子。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数n，m，表示有n个妹子，m组询问;</p><p>第二行有n个数字，表示第i个妹子的“需求值”为Ai;</p><p>接下来m行每行有三个数字s，e，p，表示闭区间的左右边界和liyundu大神能给予的最大值(注意区间从1开始，就是说，第一个数为1，最后一个数为n！)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出总共有m行，每行一个整数y表示liyundu在这组询问能撩到的妹子数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p><p>7 39 23</p><p>1 3 40</p><p>2 3 0</p><p>1 2 8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p><p>0</p><p>1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据有</p><p>n&lt;=100000;</p><p>m&lt;=100000;</p><p>Ai&lt;=2^31-1;</p><p>高能预警:小心内存！</p>
</div>
</div>
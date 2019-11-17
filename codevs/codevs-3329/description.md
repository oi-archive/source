<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一种密码锁由若干个转轮构成，每个转轮上刻有26个小写字母。每次操作可将相邻两个转轮上的字母进行一次反向的增减。</p>
<p>更形式化的说，对于一个长度不超过n的仅含小写字母的字符串s，每次操作可选择一个p（1 &lt;= p &lt; |s|），进行下述两个动作之一：</p>
<p>1.将s[p]替换为其字典序后一位的字母，将s[p+1]替换为其字典序前一位的字母</p>
<p>2.将s[p]替换为其字典序前一位的字母，将s[p+1]替换为其字典序后一位的字母</p>
<p>“z”没有在其字典序后一位的字母，同样，“a”也没有在其字典序前一位的字母。故无法对其进行相应的操作。</p>
<p>现在给定密码锁初始状态（即字符串s），求经过任意多次操作后，密码锁能变换出多少种与初始状态不同的状态（即至少一位上的字母与s该位的字母不同）。答案对1000000007（10^9 + 7）取模。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个正整数 t，表示数据组数。</p>
<p>以下t行，每行一个小写字母串表示密码串初始状态。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共t行，每行一个整数表示答案。</p>

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
<p>ya</p>
<p>klmbfxzb</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>24</p>
<p>320092793</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>    对于30%的数据， t = 1， 1 &lt;= 字符串长度 &lt;= 10</p>
<p>    对于60%的数据， 1 &lt;= t &lt;= 10</p>
<p>    对于100%的数据，1 &lt;= t &lt;= 10^4， 1 &lt;= 字符串长度 &lt;= 100</p>
</div>
</div>
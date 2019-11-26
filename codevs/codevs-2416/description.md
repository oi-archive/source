<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>众所周知卡农是一种复调音乐的写作技法，小余在听卡农音乐时灵感大发，发明了一种新的音乐谱写规则。他将声音分成n个音阶，并将音乐分成若干个片段。音乐的每个片段都是由 1到n个音阶构成的和声，即从n个音阶中挑选若干个音阶同时演奏出来。为了强调与卡农的不同，他规定任意两个片段所包含的音阶集合都不同。同时为了保持音乐的规律性，他还规定在一段音乐中每个音阶被奏响的次数为偶数。现在的问题是：小余想知道包含m个片段的音乐一共有多少种。两段音乐a和b同种当且仅当将a的片段重新排列后可以得到b。例如：假设a为{{1,2},{2,3}}，b为{{3,2},{2,1}}，那么a与b就是同种音乐。由于种数很多，你只需要输出答案模100000007（质数）的结果。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>仅一行，具体是用空格隔开的两个正整数n和m，分<span style="">别表示音阶的数量和音乐中的片段数。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>仅包含一个非负整数，表示音乐的种数模<span lang="EN-US">100000007</span>的结果。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例解释：音乐为{{1},{2},{1,2}} </p>
<p><span><br></span></p>
<p><span>20%的数据满足n,m≤5，50%的数据满足n,m≤3000，100 %</span><span>的数据满足n,m≤1000000。</span></p>
</div>
</div>
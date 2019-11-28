<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    很久很久以前，在你刚刚学习字符串匹配的时候，有两个仅包含小写字母的字符串A和B，其中A串长度为m，B串长度为n。可当你现在再次碰到这两个串时，这两个串已经老化了，每个串都有不同程度的残缺。</p><p>    你想对这两个串重新进行匹配，其中A为模板串，那么现在问题来了，请回答，对于B的每一个位置i，从这个位置开始连续m个字符形成的子串是否可能与A串完全匹配?</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个正整数m,n(1&lt;=m&lt;=n&lt;=300000)，分别表示A串和B串的长度。</p><p>第二行为一个长度为m的字符串A。</p><p>第三行为一个长度为n的字符串B。</p><p>两个串均仅由小写字母和*号组成，其中*号表示相应位置已经残缺。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行包含一个整数k，表示B串中可以完全匹配A串的位置个数。</p><p>若k&gt;0，则第二行输出k个正整数，从小到大依次输出每个可以匹配的开头位置（下标从1开始）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 7</p><p>a*b</p><p>aebr*ob</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p><p>1 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=m&lt;=n&lt;=300000</p>
</div>
</div>
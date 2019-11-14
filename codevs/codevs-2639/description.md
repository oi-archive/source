<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>cc是个超级帅哥，口才又好，rp极高（这句话似乎降rp），又非常的幽默，所以很多mm都跟他关系不错。然而，最关键的是，cc能够很好的调解各各妹妹间的关系。mm之间的关系及其复杂，cc必须严格掌握她们之间的朋友关系，好一起约她们出去，cc要是和不是朋友的两个mm出去玩，后果不堪设想……<br><span>cc只掌握着一些mm之间的关系，但是cc比较聪明，他知道a和b是朋友，b和c 是朋友，那么a和c也是朋友。</span><br><span>下面给出m对朋友关系, cc 定了p次约会，每次约会找两个mm，如果这两个mm是朋友，那么不会出乱子，输出‘safe'，要是不是朋友，那么cc必然会挨……，输出‘cc cry'</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行为n，m，p。n为mm的数量，cc知道m对朋友关系，有p次约会。</span><br><span>2到n+1 行，每行一个字符串，为第i个mm的名字。{字符串长度&lt;=11,且全大写}</span><br><span>以下m行，每行两个字符串，用空格隔开 ，为有朋友关系的两个mm的名字。</span><br><span>以下p行，每行为两个字符串，用空格隔开，为这p次约会中两个mm的名字。</span><br><span>{保证数据不会出现没有出现过的名字}</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>输出P行表示第i次约会的情况，输出&lsquo;safe'或者&lsquo;cc cry'</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 1 1<br>AAA<br>BBB<br>CCC<br>AAA CCC<br>AAA BBB</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>cc cry</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>0&lt;m&lt;=2008</span><br><span>0&lt;p&lt;=2008</span></p>
</div>
</div>
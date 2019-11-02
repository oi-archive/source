<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在学习几何时，一个很重要的问题是多边形的朗读。很多人都会觉得，如果按字母表顺序来朗读一个多边形要顺口的多。所以一个很无聊的学生找到了你，要求你编制一个程序来使多边形的朗读尽可能顺口。如果你不帮他，他就会诅咒你看书串行，走路撞墙……（此处省略一万字），读多边形拗口。</p>
<p>如何判断一种读法是不是拗口？首先普及一下，对于任意一个多边形，读法是：<strong>选取一个顶点，按照顺时针依次读出字母。</strong>我们把读出的字母序列叫做该多边形的一个<strong>朗读序列</strong>。对于任意一个朗读序列，如果有一串（至少两个）紧邻的字母是按ASCII码（别问我为什么不是字母表）的的顺序排列（如COP,AHXZab,#%036&lt;=&gt;KO[^az{|），那么就把这一串字母叫做该朗读序列的一个<strong>和谐子串</strong>。</p>
<p>规定：<strong>和谐子串中包含的和谐子串不重复计算</strong>。例如ABCOPQ是和谐子串，而COP就不再重复计算为另一个和谐子串了。</p>
<p>注意：根据此规定，下列情况是不能出现的：</p>
<p>1）计算了和谐子串AB后，再计算和谐子串OPQ；或计算了和谐子串ABCO后，再计算和谐子串OPQ。因为存在和谐子串ABCOPQ可以同时包含这两个和谐子串。</p>
<p>一个朗读序列有一个<strong>和谐值h</strong>，规定：<strong>h=∑length(和谐子串)</strong>。<strong>h越大，说明该朗读方式越和谐</strong>。</p>
<p>现在他会给你一个多边形的顶点，请你求出最和谐的朗读方式。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入只有一行，一个多边形的所有顶点（顺时针序），</p>
<p>由于ASCII码中，非空且有意义的字符只有94个（33~126），所以该顶点串的长度不会超过94，且串长不会小于3。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行，最和谐的朗读方式。若和谐值相同，输出最长和谐子串长的。若最长和谐子串长度相同，那么输出朗读序列字典序小的。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>Da0ABC</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0ABCDa</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据，只会出现大写字母。</p>
<p>对于50%的数据，只会出现大写字母和小写字母。</p>
<p>对于100%的数据，只会出现ASCII码表中十进制33~126范围的字符。</p>
<p><strong>保证每一组输入数据中不会包含相同的字符。</strong></p>
</div>
</div>
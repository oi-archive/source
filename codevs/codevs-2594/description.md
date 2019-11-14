<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Smart研制出对付各种症状的解药，可是他一个不小心，每种药都小小地配错了一点原料，所以这些药都有可能在治愈某些病症的同时又使人患上某些别的病症（你可能会问那<span style="font-family: Times New Roman;">…</span><span style="">那是解药还是毒药啊？）</span><span style="font-family: Times New Roman;">……</span>，经过Smart的努力，终于弄清了每种药的具体性能，他会把每种药能治愈的病症和能使人患上的病症列一张清单给你，然后你要根据这张清单找出能治愈所有病症的最少药剂组合<span style="font-family: Times New Roman;">……</span><span style="">顺便说一声，病症的数目不超过</span><span style="font-family: Times New Roman;">10</span><span style="">种，</span>而且他的药是用不完的，就是说每种药剂都可以被重复使用。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>给你们的单子里第一行是病症的总数<span style="font-family: Times New Roman;">n</span>（<span style="font-family: Times New Roman;">1</span><span style="">≤</span><span style="font-family: Times New Roman;">n</span><span style="">≤</span><span style="font-family: Times New Roman;">10</span><span style="">）。</span>第二行是药剂的种类<span style="font-family: Times New Roman;">m</span><span style="">（</span><span style="font-family: Times New Roman;">0&lt;m</span>≤100<span style="">）</span>。</p>
<p>以下有<span style="font-family: Times New Roman;">m</span><span style="">行，每行有</span><span style="font-family: Times New Roman;">n</span><span style="">个数字用空格隔开，文件的第</span><span style="font-family: Times New Roman;">i+2</span><span style="">行的</span><span style="font-family: Times New Roman;">n</span><span style="">个数字中，如果第</span><span style="font-family: Times New Roman;">j</span><span style="">个数为</span><span style="font-family: Times New Roman;">1</span><span style="">，就表示第</span><span style="font-family: Times New Roman;">i</span><span style="">种药可以治愈病症</span><span style="font-family: Times New Roman;">j</span><span style="">（如果患有这种病的话则治愈，没有这种病则无影响），如果为</span><span style="font-family: Times New Roman;">0</span><span style="">表示无影响，如果为</span><span style="font-family: Times New Roman;">-1</span><span style="">表示反而能使人得上这种病（无病患上，有病无影响）。</span>Smart制的药任何两种性能都不同。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">你只要输出用的最少的药剂数就可以了，其实还有可能用尽了所有的药也不能将所有病治愈，那样的话你们只要输出&ldquo;The&nbsp;patient&nbsp;will&nbsp;be&nbsp;dead.&rdquo;<span style="font-family: 宋体;">就可以了。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>2</p>
<p>1 0 1</p>
<p>-1 1 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1<span style="">≤</span><span style="font-family: Times New Roman;">n</span><span style="">≤</span><span style="font-family: Times New Roman;">10</span></p>
<p>0&lt;m≤100</p>
<p> </p>
</div>
</div>
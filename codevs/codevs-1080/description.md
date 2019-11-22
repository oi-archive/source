<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">一行</span><span style="font-family: 'Times New Roman';">N</span><span style="">个方格，开始每个格子里都有一个整数。现在动态地提出一些问题和修改：提问的形式是求某一个特定的子区间</span><span style="font-family: 'Times New Roman';">[a,b]</span><span style="">中所有元素的和；修改的规则是指定某一个格子</span><span style="font-family: 'Times New Roman';">x</span><span style="">，加上或者减去一个特定的值</span><span style="font-family: 'Times New Roman';">A</span><span style="">。现在要求你能对每个提问作出正确的回答。</span><span style="font-family: 'Times New Roman';">1</span><span style="">≤</span><span style="font-family: 'Times New Roman';">N</span><span style="">&lt;100000<span style="">，</span></span><span style="font-family: 'Times New Roman';">,</span><span style="">提问和修改的总数<span style="font-family: Times New Roman;">m&lt;100</span></span><span style="font-family: 'Times New Roman';">00</span><span style="">条。</span></p>
<!--EndFragment-->

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入文件第一行为</span><span style="">一</span><span style="">个整数</span><span style="font-family: 'Times New Roman';">N</span><span style="">，接下来是</span><span style="">n</span><span style="">行<span style="font-family: Times New Roman;">n</span><span style="">个整数，表示格子中原来的整数。接下</span></span><span style="">一个正整数</span><span style="">m<span style="">，再接下</span></span><span style="">来有<span style="font-family: Times New Roman;">m</span><span style="">行，表示</span><span style="font-family: Times New Roman;">m</span><span style="">个询问，第一个整数表示询问代号，询问代号</span><span style="font-family: Times New Roman;">1</span><span style="">表示增加，后面的两个数</span><span style="font-family: Times New Roman;">x</span><span style="">和</span><span style="font-family: Times New Roman;">A</span><span style="">表示给位置</span><span style="font-family: Times New Roman;">X</span><span style="">上的数值增加</span><span style="font-family: Times New Roman;">A</span><span style="">，询问代号</span><span style="font-family: Times New Roman;">2</span><span style="">表示区间求和，后面两个整数表示</span><span style="font-family: Times New Roman;">a</span><span style="">和</span><span style="font-family: Times New Roman;">b</span><span style="">，表示要求</span><span style="font-family: Times New Roman;">[a,b]</span><span style="">之间的区间和。</span></span></p>
<!--EndFragment-->

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: small;">共m行，每个整数</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">6</span></p>
<p style=""><span style="">4 </span></p>
<p style=""><span style="">5 </span></p>
<p style=""><span style="">6 </span></p>
<p style=""><span style="">2 </span></p>
<p style=""><span style="">1 </span></p>
<p style=""><span style="">3</span></p>
<p style=""><span style="">4</span></p>
<p style=""><span style="">1 3 5</span></p>
<p style=""><span style="">2 1 4</span></p>
<p style=""><span style="">1 1 9</span></p>
<p style=""><span style="">2 2 6</span></p>
<!--EndFragment-->

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>22</p>
<p>22</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1≤N≤100000， m≤10000 。</p>
</div>
</div>
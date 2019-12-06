<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>现在的年轻人都有自己的QQ号码，但是每个人的QQ号码不同，因此所产生的QQ“价值”也不同</p><p><br></p><p>。已知道QQ号码的“价值”是由QQ号码的位数和构成数字大小所决定的。也就是说，QQ号码长</p><p><br></p><p>度越小，“价值”越大。构成数字越大，“价值”越大。我们规定：</p><p>一个QQ号码的“价值”=(各位数字之和*P（P&gt;0）/QQ号码位数)向下取整</p><p>例如：QQ号码 123456 的“价值”为 (1+2+3+4+5+6)*P/6 向下取整</p><p>      QQ号码 1212121 的“价值”为（1+2+1+2+1+2+1）*P/7 向下取整</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行输入整数N,P；</p><p>接下来的2N行分别输入每个人的名字和QQ号码（名字和QQ号各占一行）</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>按QQ“价值”由大到小输出名字，（若“价值”相同，按字典序输出）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 10</p><p>Drew</p><p>1164371383</p><p>Adam</p><p>1324432934</p><p>Kyle</p><p>578507419</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Kyle</p><p>Drew</p><p>Adam</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>0&lt;N&lt;=10000</p><p>0&lt;P&lt;=20</p><p>保证名字长度&lt;500</p><p>保证QQ号码超度&lt;400</p><p><br></p>
</div>
</div>
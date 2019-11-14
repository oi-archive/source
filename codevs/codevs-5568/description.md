<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>【题目描述】<br></p><p>双休日，SQZ在家里翻箱倒柜，一不小心摔坏了老妈的宝贝项链。老妈十分生气，责令他把项链还原。</p><p>这一串项链为一条直线段，由n(n&lt;=200)个珠子组成，最靠前的珠子称为头珠，每个珠子编号为1~n并且独一无二。</p><p>现有m条信息，每条信息包括三个整数，a，b，c表示a号珠子比b号珠子更靠近头珠，并且a，b之间距离为c（距离指|a的坐标-b的坐标|）。现在请你根据这m条信息，将这串珠子复原（复原时只需要按编号1~n输出该珠子距离头珠的距离，自身为头珠输出0）。</p><p>【注意！珠子有可能位于同一位置！！！】</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">第一行为两个整数n，m。</p><p style="">接下来n行，每行3个数a，b，c。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; 共n行，第i行表示第i颗珠子到头珠的距离。<strong>若无解，输出-1.</strong></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="">4 3</p><p style="">1 2 3</p><p style="">3 2 2</p><p style="">3 4 1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0</p><p>3</p><p>1</p><p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style="">33.3%的数据， n&lt;=30;</p><p style="">100%的数据， n&lt;=200，m&lt;=300,k&lt;=maxlongint;</p><p>提示：最短路or并查集。</p><p><br></p>
</div>
</div>
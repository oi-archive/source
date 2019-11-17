<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>已知有两个字串 A$, B$ 及一组字串变换的规则（至多6个规则）:<br>　　　　　A1$ -&gt; B1$<br>　　　　　A2$ -&gt; B2$<br>　　规则的含义为：在 A＄中的子串 A1$ 可以变换为 B1$、A2$ 可以变换为 B2$ …。<br>　　　　例如：A$＝'abcd'　B$＝'xyz'<br>　　变换规则为：<br>　　　　‘abc’-&gt;‘xu’　‘ud’-&gt;‘y’　‘y’-&gt;‘yz’<br><br>　　则此时，A$ 可以经过一系列的变换变为 B$，其变换的过程为：<br>　　　‘abcd’-&gt;‘xud’-&gt;‘xy’-&gt;‘xyz’<br><br>　　共进行了三次变换，使得 A$ 变换为B$。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入格式如下：</p>
<p>　　　A$ B$<br>　　　A1$ B1$ \<br>　　　A2$ B2$  |-&gt; 变换规则<br>　　　... ... / <br>　　所有字符串长度的上限为 20。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>若在 10 步（包含 10步）以内能将 A$ 变换为 B$ ，则输出最少的变换步数；否则输出"NO ANSWER!"</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>abcd xyz<br>abc xu<br>ud y<br>y yz</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>hehe </p>
</div>
</div>
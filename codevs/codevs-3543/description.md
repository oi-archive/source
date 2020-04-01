<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><strong><span style="">好消息，好消息~沉寂了许久，Teachk又要登场啦！多才多艺的Teachk这次在研究括号匹配问题。<strong style=""><span style="">Teachk</span></strong>现在收到n组字符串，字符串中只含有括号 (),[],&lt;&gt;,{},Teachk被要求判断输入的字符串中括号是否匹配。如果括号有互相包含的形式，从内到外必须是&lt;&gt;,(),[],{}的顺序。例如。输入: [()] 输出:YES，而输入([])， ([]),[)，&gt;&lt;,((),)(都应该输出NO。你能帮助<strong style=""><span style="">Teachk</span></strong>吗？</span></strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><strong><span style="">第一行为一个整数n，表示有n个字符串(n&lt;=10)</span></strong></p><p style=""><strong><span style="">接下来n行，每为行一个由括号组成的长度不大于255的字符串</span></strong></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent: 40px;"><strong><span style="font-size:16px;font-family:宋体">一共n行，每行输出YES或者NO</span></strong></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><strong><span style="">6</span></strong></p><p><strong><span style="">{}{}&lt;&gt;&lt;&gt;()()[][]</span></strong></p><p><strong><span style="">{{}}{{}}&lt;&lt;&gt;&gt;&lt;&lt;&gt;&gt;(())(())[[]][[]]</span></strong></p><p><strong><span style="">{{}}{{}}&lt;&lt;&gt;&gt;&lt;&lt;&gt;&gt;(())(())[[]][[]]</span></strong></p><p><strong><span style="">{&lt;&gt;}{[]}&lt;&lt;&lt;&gt;&gt;&lt;&lt;&gt;&gt;&gt;((&lt;&gt;))(())[[(&lt;&gt;)]][[]]</span></strong></p><p><strong><span style="">&gt;&lt;}{{[]}&lt;&lt;&lt;&gt;&gt;&lt;&lt;&gt;&gt;&gt;((&lt;&gt;))(())[[(&lt;&gt;)]][[]]</span></strong></p><p><strong><span style="">([])</span></strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><strong><span style="">YES</span></strong></p><p style=""><strong><span style="">YES</span></strong></p><p style=""><strong><span style="">YES</span></strong></p><p style=""><strong><span style="">YES</span></strong></p><p style=""><strong><span style="">NO</span></strong></p><p style=""><strong><span style="">NO</span></strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见输入描述</p>
</div>
</div>
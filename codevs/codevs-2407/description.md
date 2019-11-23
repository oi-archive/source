<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>有<span style="font-family: 'Times New Roman';">N</span><span style="">个节点，标号从</span><span style="font-family: 'Times New Roman';">1</span><span style="">到</span><span style="font-family: 'Times New Roman';">N</span><span style="">，这</span><span style="font-family: 'Times New Roman';">N</span><span style="">个节点一开始相互不连通。第</span><span style="font-family: 'Times New Roman';">i</span><span style="">个节点的初始权值为</span><span style="font-family: 'Times New Roman';">a[i]</span><span style="">，接下来有如下一些操作：</span></span></p>
<p><span>U x y:</span><span> </span><span>加一条边，连接第<span style="font-family: 'Times New Roman';">x</span><span style="">个节点和第</span><span style="font-family: 'Times New Roman';">y</span><span style="">个节点</span></span></p>
<p><span>A1 x v:</span><span> </span><span>将第<span style="font-family: 'Times New Roman';">x</span><span style="">个节点的权值增加</span><span style="font-family: 'Times New Roman';">v</span></span></p>
<p><span>A2 x v:</span><span> </span><span>将第<span style="font-family: 'Times New Roman';">x</span><span style="">个节点所在的</span>连通块的所有节点的权值都增加<span style="font-family: 'Times New Roman';">v</span></span></p>
<p><span>A3 v:</span><span> </span><span>将所有节点的权值都增加<span style="font-family: 'Times New Roman';">v</span></span></p>
<p><span>F1 x:</span><span> </span><span>输出第<span style="font-family: 'Times New Roman';">x</span><span style="">个节点当前的权值</span></span></p>
<p><span>F2 x:</span><span> </span><span>输出第<span style="font-family: 'Times New Roman';">x</span><span style="">个节点所在的连通块中，权值最大的节点的权值</span></span></p>
<p><span>F3:</span><span> </span><span>输出所有节点中，权值最大的节点的权值</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入的第一行是一个整数<span style="font-family: 'Times New Roman';">N</span><span style="">，代表节点个数。</span></span></p>
<p><span>接下来一行输入<span style="font-family: 'Times New Roman';">N</span><span style="">个整数，</span><span style="font-family: 'Times New Roman';">a[1], a[2], …, a[N]</span><span style="">，代表</span><span style="font-family: 'Times New Roman';">N</span><span style="">个节点的初始权值。</span></span></p>
<p><span>再下一行输入一个整数<span style="font-family: 'Times New Roman';">Q</span><span style="">，代表接下来的操作数。</span></span></p>
<p><span>最后输入<span style="font-family: 'Times New Roman';">Q</span><span style="">行，每行的格式如题目描述所示。</span></span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>对于操作</span><span style="font-family: 'Times New Roman';">F1,&nbsp;F2,&nbsp;F3</span><span style="font-family: 宋体;">，输出对应的结果，每个结果占一行。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>3</span><br><br><span> 0 0 0</span><br><br><span> 8</span><br><br><span> A1 3 -20</span><br><br><span> A1 2 20</span><br><br><span> U 1 3</span><br><br><span> A2 1 10</span><br><br><span> F1 3</span><br><br><span> F2 3</span><br><br><span> A3 -10</span><br><br><span> F3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>-10</span><br><br><span> 10</span><br><br><span> 10</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p> 对于30%的数据，保证 N&lt;=100，Q&lt;=10000</p>
<p> </p>
<p>对于80%的数据，保证 N&lt;=100000，Q&lt;=100000</p>
<p> </p>
<p>对于100%的数据，保证 N&lt;=300000，Q&lt;=300000</p>
<p> </p>
<p>对于所有的数据，保证输入合法，并且 -1000&lt;=v, a[1], a[2], …, a[N]&lt;=1000</p>
</div>
</div>
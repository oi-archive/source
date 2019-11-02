<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>“伐木工一定都是搞OI的人！”——tangjiaming</p><p>二叉查找树，无限树，最小生成树，平衡树，线段树，主席树，树链剖分，树状数组……OI里的树太多，而以上似乎只是最简单的几个。为了表达对树的憎恨，不少OIer已经成为了伐木工，决心把一切树都砍成两半。</p><p>（“还有一个东西叫作仙人掌。”——jrMz）</p><p>现在有一棵结点数为N的树，N是偶数，伐木工HR想要选择一条边，把它砍断，这样整棵树就分成了两半，这两半应该同样是树。然而，HR是个完美主义者，如果砍出来的两棵半树的结点数不同，后果很严重！你的任务是帮助HR选择那条合适的边，使得两棵半树的结点数都恰好是N/2。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，正偶数N。</p><p>接下来N-1行，每行两个正整数x,y，0&lt;x,y&lt;=N，表示这棵树的各边。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行，一个正整数Ans，0&lt;Ans&lt;N，表示输入文件中的第Ans条边，即第Ans+1行所对应的边应该被砍断。<br/></p><p>如果找不到合适的边，输出&quot;HR gets crazy!&quot;。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8</p><p>1 2</p><p>1 3</p><p>2 4</p><p>2 5</p><p>3 6</p><p>3 7</p><p>4 8</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例中，将边1-2砍断，与1连接的树是{1,3,6,7}，与2连接的树是{2,4,5,8}。</p><p><br></p><p>对于30%的数据，N&lt;=2,000；对于100%的数据，N&lt;=500,000。</p><p><br></p>
</div>
</div>
<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">给出一棵树，求出树的中心。</span></p><p style=""><span style="">为了定义树的中心，首先给每个结点进行标号。对于一个结点</span>K<span style="">，如果把</span>K<span style="">从树中删除（连同与它相连的边一起），剩下的被分成了很多块，每一块显然又是一棵树（即剩下的部分构成了一个森林）。则给<strong>结点</strong></span><strong>K</strong><strong><span style="">所标的号</span></strong><span style="">就是<strong>森林中结点个数最多的树所拥有的结点数</strong>。如果结点</span>K<span style="">的标号不大于其他任何一个结点的标号，则结点</span>K<span style="">被称为是树的中心。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入：</span></p><p style=""><span style="">输入的第一行包含一个整数</span>N<span style="">（</span>1≤N≤16 000<span style="">），表示树中的结点数。接下来</span>N-1<span style="">行，每个两个整数</span>a,b<span style="">，由一个空格分隔，表示</span>a<span style="">与</span>b<span style="">之间有一条边。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family:宋体">输出：</span></p><p style="text-indent:28px"><span style="font-family:宋体">输出两行，第一行两个整数</span>v,T<span style="font-family:宋体">，</span>v<span style="font-family:宋体">表示树的中心结点的标号，</span>T<span style="font-family:宋体">表示树有多少个中心。第二行包含</span>T<span style="font-family:宋体">个数，为所有树的中心的编号，按升序排列。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">样例输入：</span></p><p>7</p><p>1 2</p><p>2 3</p><p>2 4</p><p>1 5</p><p>5 6</p><p>6 7</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">样例输出：</span></p><p>3 1</p><p>1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">数据范围</span>: 20% N&lt;=100 100% N&lt;=16 000</p><p><br></p>
</div>
</div>
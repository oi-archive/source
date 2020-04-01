<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一棵树上有n个节点，编号分别为1到n，每个节点都有一个权值w。</p>
<p>我们将以下面的形式来要求你对这棵树完成一些操作：</p>
<ol>
<li><strong>I.                    </strong><strong>CHANGE u t : </strong>把结点<strong>u</strong>的权值改为<strong>t</strong></li>
<li><strong>II.                 </strong><strong>QMAX u v: </strong>询问从点<strong>u</strong>到点<strong>v</strong>的路径上的节点的最大权值<strong></strong></li>
<li><strong>III.               </strong><strong>QSUM u v: </strong>询问从点<strong>u</strong>到点<strong>v</strong>的路径上的节点的权值和<strong></strong></li>
</ol>
<p><strong> </strong></p>
<p><strong>注意：从点u</strong><strong>到点v</strong><strong>的路径上的节点包括u</strong><strong>和v</strong><strong>本身</strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行为一个整数n，表示节点的个数。</p>
<p>       接下来n – 1行，每行2个整数a和b，表示节点a和节点b之间有一条边相连。</p>
<p><strong>       </strong>接下来n行，每行一个整数，第i行的整数wi表示节点i的权值。</p>
<p>       接下来1行，为一个整数q，表示操作的总数。</p>
<p>接下来q行，每行一个操作，以“<strong>CHANGE u t</strong>”或者“<strong>QMAX u v</strong>”或者“<strong>QSUM u v</strong>”的形式给出。</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; &nbsp; &nbsp;对于每个&ldquo;<strong>QMAX</strong>&rdquo;或者&ldquo;<strong>QSUM</strong>&rdquo;的操作，每行输出一个整数表示要求输出的结果。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>1 2</p>
<p>2 3</p>
<p>4 1</p>
<p>4 2 1 3</p>
<p>12</p>
<p>QMAX 3 4</p>
<p>QMAX 3 3</p>
<p>QMAX 3 2</p>
<p>QMAX 2 3</p>
<p>QSUM 3 4</p>
<p>QSUM 2 1</p>
<p>CHANGE 1 5</p>
<p>QMAX 3 4</p>
<p>CHANGE 3 6</p>
<p>QMAX 3 4</p>
<p>QMAX 2 4</p>
<p>QSUM 3 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>1</p>
<p>2</p>
<p>2</p>
<p>10</p>
<p>6</p>
<p>5</p>
<p>6</p>
<p>5</p>
<p>16</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100％的数据，保证1&lt;=n&lt;=30000，0&lt;=q&lt;=200000；中途操作中保证每个节点的权值w在-30000到30000之间。</p>
</div>
</div>
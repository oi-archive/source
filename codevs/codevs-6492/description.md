<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style=""><span style="">    一群萝卜在聚会开</span><span style="font-family: Calibri, sans-serif;">party</span><span style="">，</span><span style="font-family: Calibri, sans-serif;">party</span><span style="">结束之后，萝卜们都很累了，小萝卜托尼提出要回家，可是他们发现自己面前有若干个节点，和若干条路组成了一棵二叉树，每个节点最多连着一个父节点和两个子节点，每两个节点之间有唯一的一条单向的有一定长度的路（从父亲节点指向儿子节点）。萝卜们迷路了，并被困在根节点处（根节点编号为1），他们只记得，从这里到家需要经过的节点最多，并且路径长度最短。于是他们请求正在读这句话的你。</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style=""><span style="">第一行一个整数</span>n<span style="">，表示树的节点总数。</span></span></p><p style=""><span style="">接下来的</span>n<span style="">行，每行有四个数</span>ui,xi,vi,yi(ui&lt;=n,vi&lt;=n,xi&lt;=100,yi&lt;=100)<span style="">。这</span>n<span style="">行中第</span>i<span style="">行表示编号为</span>i<span style="">的节点的左儿子节点编号为</span>ui<span style="">，他们之间的路径长为</span>xi<span style="">，若二者都为</span>0<span style="">表示无左儿子节点；右儿子节点编号为</span>vi<span style="">，他们之间的路径长为</span>yi<span style="">，若二者都为</span>0<span style="">表示无右儿子节点（也就是说，叶节点的四个数是</span>0 0 0 0<span style="">）。</span></p><p style=""><span style="">输入保证正确且有唯一解，最短路线经过的节点不超过</span>60<span style="">个，最短路径总长不超过</span>900<span style="">。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent: 28px; line-height: 20px;"><span style="font-family: 宋体; font-size: 16px;">第一行一个整数，表示经过节点最多的情况下最短的路径长。</span></p><p style="text-indent: 28px; line-height: 20px;"><span style="font-family: 宋体;">第二行若干个整数，表示依次经过的点的编号。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><strong><span style="font-family: 'Times New Roman','serif';">Sample1 Input:</span></strong></p><p>18</p><p>8 1 4 3</p><p>0 0 0 0</p><p>0 0 6 4</p><p>3 2 7 8</p><p>0 0 0 0</p><p>5 5 0 0</p><p>0 0 15 6</p><p>9 4 17 9</p><p>10 8 12 9</p><p>11 7 2 6</p><p>0 0 0 0</p><p>0 0 13 5</p><p>0 0 0 0</p><p>0 0 0 0</p><p>16 3 18 2</p><p>0 0 0 0</p><p>14 3 0 0</p><p>0 0 0 0</p><p><br></p><p><strong><span style="font-family: 'Times New Roman','serif';">Sample2 Input:</span></strong></p><p>7</p><p>2 3 0 0</p><p>6 4 0 0</p><p>7 1 0 0</p><p>3 7 0 0</p><p>0 0 0 0</p><p>4 2 0 0</p><p>0 0 5 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><strong><span style="font-family: 'Times New Roman','serif';">Sample1 Output:</span></strong></p><p>14</p><p>1 4 3 6 5</p><p><br></p><p><strong><span style="font-family: 'Times New Roman','serif';">Sample2 Output:</span></strong></p><p>17</p><p>1 2 6 4 3 7 5</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">对于前</span>10%<span style="">的数据，每条路的长度为</span>1<span style="">，</span>n&lt;=2<sup>5</sup>-1<span style="">；</span></p><p style=""><span style="">对于另外</span>10%<span style="">的数据，树退化成一条链，但区分左右儿子节点，</span>n&lt;=2<sup>8</sup>-1<span style="">；</span></p><p style=""><span style="">对于再另外</span>10%<span style="">的数据，树最深的节点只有唯一一个；</span></p><p style=""><span style="">对于前</span>50%<span style="">的数据，</span>n&lt;=2<sup>15</sup>-1<span style="">；</span></p><p style=""><span style="">对于另外</span>50%<span style="">的数据，树为满二叉树；</span></p><p style=""><span style="">对于测试点</span>3<span style="">、</span>6、8<span style="">、</span>9、10<span style="">，对树进行宽度优先遍历时，依次进入队列的编号（先左后右）单调；</span></p><p style=""><span style="">对于</span>100%<span style="">的数据，</span>n&lt;=2<sup>21</sup>-1<span style="">。</span></p><p style=""><span style="">（注意：由于输入有大量“没用”的</span>0 0 0 0<span style="">，建议</span>C++<span style="">选手不要用</span>cin<span style="">读入数据）</span></p><p>    <br></p>
</div>
</div>
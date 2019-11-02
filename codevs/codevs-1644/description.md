<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>二叉树是一种基本的数据结构，它要么为空，要么由根节点，左子树和右子树组成，同时左子树和右子树也分别是二叉树。</p>
<p>当一颗二叉树高度为<span style="font-family: 'Times New Roman';">m-1</span><span style="">时，则共有</span><span style="font-family: 'Times New Roman';">m</span><span style="">层。除</span><span style="font-family: 'Times New Roman';">m</span><span style="">层外，其他各层的结点数都达到最大，且结点节点都在第</span><span style="font-family: 'Times New Roman';">m</span><span style="">层时，这就是一个满二叉树。</span></p>
<p>现在，需要你用程序来绘制一棵二叉树，它由一颗满二叉树去掉若干结点而成。</p>
<p>对于一颗满二叉树，我们需要按照以下要求绘制：</p>
<p>1<span style="">、结点用小写字母“</span><span style="font-family: 'Times New Roman';">o</span><span style="">”表示，对于一个父亲结点，用“</span><span style="font-family: 'Times New Roman';">/</span><span style="">”连接左子树，同样用“</span><span style="font-family: 'Times New Roman';">\</span><span style="">”连接右子树。</span></p>
<p>2<span style="">、定义</span><span style="font-family: 'Times New Roman';">[i,j]</span><span style="">为位于第</span><span style="font-family: 'Times New Roman';">i</span><span style="">行，第</span><span style="font-family: 'Times New Roman';">j</span><span style="">列的某个字符。若</span><span style="font-family: 'Times New Roman';">[i,j]</span><span style="">为“</span><span style="font-family: 'Times New Roman';">/</span><span style="">”，那么</span><span style="font-family: 'Times New Roman';">[i-1,j+1]</span><span style="">与</span><span style="font-family: 'Times New Roman';">[</span>i+1,j-1]要么为“<span style="font-family: 'Times New Roman';">o</span><span style="">”，要么为“</span><span style="font-family: 'Times New Roman';">/</span><span style="">”。若</span><span style="font-family: 'Times New Roman';">[i,j]</span><span style="">为“</span><span style="font-family: 'Times New Roman';">\</span><span style="">”，那么</span><span style="font-family: 'Times New Roman';">[i-1,j-1]</span><span style="">与</span><span style="font-family: 'Times New Roman';">[</span>i+1,j+1]要么为“<span style="font-family: 'Times New Roman';">o</span><span style="">”，要么为“</span><span style="font-family: 'Times New Roman';">\</span><span style="">”。同样，若</span><span style="font-family: 'Times New Roman';">[i,j]</span><span style="">为第</span><span style="font-family: 'Times New Roman';">1-m</span><span style="">层的某个节点（即“</span><span style="font-family: 'Times New Roman';">o</span><span style="">”），那么</span><span style="font-family: 'Times New Roman';">[i+1,j-1]</span><span style="">为“</span><span style="font-family: 'Times New Roman';">/</span><span style="">”，</span><span style="font-family: 'Times New Roman';">[i+1,j+1]</span><span style="">为“</span><span style="font-family: 'Times New Roman';">\</span><span style="">”。</span></p>
<p>3<span style="">、对于第</span><span style="font-family: 'Times New Roman';">m</span><span style="">层节点也就是叶子结点，若两个属于同一个父亲，那么它们之间由</span><span style="font-family: 'Times New Roman';">3</span><span style="">个空格隔开，若两个结点相邻但不属于同一个父亲，那么它们之间由</span><span style="font-family: 'Times New Roman';">1</span><span style="">个空格隔开。第</span><span style="font-family: 'Times New Roman';">m</span><span style="">层左数第</span><span style="font-family: 'Times New Roman';">1</span><span style="">个节点之前没有空格。</span></p>
<p>最后需要在一颗绘制好的满二叉树上删除<span style="font-family: 'Times New Roman';">n</span><span style="">个结点（包括它的左右子树，以及与父亲的连接），原有的字符用空格替换（</span><span style="font-family: 'Times New Roman';">ASCII 32</span><span style="">）</span>。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>  输入文件binary.in的第<span style="font-family: 'Courier New';">1</span><span style="">行</span>包含<span style="font-family: 'Times New Roman';">2</span><span style="">个正整数</span><span style="font-family: 'Times New Roman';">m</span><span style="">和</span><span style="font-family: 'Times New Roman';">n</span><span style="">，为需要绘制的二叉树层数已经从</span><span style="font-family: 'Times New Roman';">m</span><span style="">层满二叉树中删除的结点数。</span></p>
<p>接下来<span style="font-family: 'Times New Roman';">N</span><span style="">行，每行两个正整数，表示第</span><span style="font-family: 'Times New Roman';">i</span><span style="">层第</span><span style="font-family: 'Times New Roman';">j</span><span style="">个结点需要被删除（</span><span style="font-family: 'Times New Roman';">1&lt;i&lt;=M</span><span style="">，</span><span style="font-family: 'Times New Roman';">j&lt;=2</span>i-1）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件binary.out为按照题目要求绘制的二叉树。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<table>
<tbody>
<tr>
<td valign="top" width="283">
<p>【输入样例<span style="font-family: 'Times New Roman';">1</span><span style="">】</span></p>
</td>
<td valign="top" width="284">
<p> </p>
</td>
</tr>
<tr>
<td valign="top" width="283">
<p>2 0</p>
<p> </p>
</td>
<td valign="top" width="284">
<p> </p>
<p> </p>
</td>
</tr>
</tbody>
</table>
<p>【输入输出样例<span style="font-family: 'Times New Roman';">2</span><span style="">】</span></p>
<p> </p>
<p>4 0</p>
<p><span style=""><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【输出样例<span>1<span>】</span></span></p>
<p>  o  </p>
<p> / \ </p>
<p>o   o</p>
<p>【输出样例<span>2<span>】</span></span></p>
<p>           o           </p>
<p>          / \          </p>
<p>         /   \         </p>
<p>        /     \        </p>
<p>       /       \       </p>
<p>      /         \      </p>
<p>     o           o     </p>
<p>    / \         / \    </p>
<p>   /   \       /   \   </p>
<p>  o     o    o     o  </p>
<p> / \   / \   / \    / \ </p>
<p>o  oo   oo  o o   o</p>
<p><span><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【限制】</p>
<p>    30%<span style="">的数据满足：</span><span style="font-family: 'Times New Roman';">N=0</span><span style="">；</span></p>
<p>    50%<span style="">的数据满足：</span><span style="font-family: 'Times New Roman';">2&lt;=M&lt;=5</span><span style="">；</span></p>
<p>100%<span style="">的数据满足：</span><span style="font-family: 'Times New Roman';">2&lt;=M&lt;=10</span><span style="">，</span><span style="font-family: 'Times New Roman';">0&lt;=N&lt;=10</span><span style="">。</span></p>
</div>
</div>
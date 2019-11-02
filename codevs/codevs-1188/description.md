<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Cyz<span style="">在你的帮助下很快解决了上个问题，然后好学的</span><span style="font-family: 'Times New Roman';">Cyz</span><span style="">在网上比赛时遇到了一个难题题目的名称叫做</span><span style="font-family: 'Times New Roman';">City</span><span style="">战争，当时</span><span style="font-family: 'Times New Roman';">Cyz</span><span style="">没能解决，赛后</span><span style="font-family: 'Times New Roman';">Cyz</span><span style="">来和你讨论这个问题，希望你能和他一起解决。</span></p>
<p>问题化简后是这样的：给出<span style="font-family: 'Times New Roman';">N</span><span style="">个节点的一棵带边权的树，这棵树上一共有</span><span style="font-family: 'Times New Roman';">n*(n-1)</span><span style="">条不同的路径。</span><span style="font-family: 'Times New Roman';">Ps</span><span style="">：</span><span style="font-family: 'Times New Roman';">a--&gt;b</span><span style="">和</span><span style="font-family: 'Times New Roman';">b--&gt;a</span><span style="">算不同的路径。一条路径上一定有边权最大的边</span><span style="font-family: 'Times New Roman';">(</span><span style="">可能最大边不止一条</span><span style="font-family: 'Times New Roman';">)</span><span style="">，树上的每条边都有一个重要度，重要度</span><span style="font-family: 'Times New Roman';">K</span><span style="">表示这条边是</span><span style="font-family: 'Times New Roman';">K</span><span style="">条路径上的最大边。</span></p>
<p>问题是让你找出树中所有边的最大重要度和最大重要度的边有多少条，并且升序输出这些边的序号。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，一个整数N<span style="">，表示一颗树有</span><span style="font-family: 'Times New Roman';">N</span><span style="">个节点，接下来</span><span style="font-family: 'Times New Roman';">N-1</span><span style="">行，每行三个整数</span><span style="font-family: 'Times New Roman';">a,b,c</span><span style="">表示节点</span><span style="font-family: 'Times New Roman';">a</span><span style="">和节点</span><span style="font-family: 'Times New Roman';">b</span><span style="">之间有条权值为</span><span style="font-family: 'Times New Roman';">c</span><span style="">的边</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p15">第一行有两个空格隔开的整数Max<span style="font-family: 宋体;">和</span><span style="font-family: 'Times New Roman';">tot,</span><span style="font-family: 宋体;">表示树中边的最大的重要度和满足最大重要度的边有</span><span style="font-family: 'Times New Roman';">tot</span><span style="font-family: 宋体;">条。</span></p>
<p class="p15">第二行输出空格隔开的<span style="font-family: 'Times New Roman';">tot</span><span style="font-family: 宋体;">个正整数，即这些边的序号。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p> </p>
<table>
<tbody>
<tr>
<td valign="top" width="192">
<p>样例#</p>
</td>
<td valign="top" width="192">
<p>样例输入</p>
</td>
<td valign="top" width="184">
<p>样例输出</p>
</td>
</tr>
<tr>
<td valign="top" width="192">
<p>1</p>
</td>
<td valign="top" width="192">
<p>2<br>2 1 5</p>
</td>
<td valign="top" width="184">
<p>2 1</p>
<p>1</p>
</td>
</tr>
<tr>
<td valign="top" width="192">
<p>2</p>
</td>
<td valign="top" width="192">
<p>6<br>1 2 1<br>1 3 5<br>3 4 2<br>3 5 3<br>3 6 4</p>
</td>
<td valign="top" width="184">
<p>16 1</p>
<p>2</p>
</td>
</tr>
<tr>
<td valign="top" width="192">
<p>3</p>
</td>
<td valign="top" width="192">
<p>4</p>
<p>1 2 1</p>
<p>2 3 3</p>
<p>3 4 4</p>
</td>
<td valign="top" width="184">
<p>6 1</p>
<p>3</p>
</td>
</tr>
<tr>
<td valign="top" width="192">
<p>4</p>
</td>
<td valign="top" width="192">
<p>4</p>
<p>1 2 1</p>
<p>2 3 1</p>
<p>2 4 1</p>
</td>
<td valign="top" width="184">
<p>6 3</p>
<p>1 2 3</p>
</td>
</tr>
</tbody>
</table>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>见上</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据规模】</p>
<p>20%<span style="">的数据满足</span><span style="font-family: 'Times New Roman';">N&lt;=1000</span></p>
<p>另有<span style="font-family: 'Times New Roman';">20%</span><span style="">的数据满足 </span><span style="font-family: 'Times New Roman';">C</span><span style="">的值都不相同</span></p>
<p>100%<span style="">的数据满足 </span><span style="font-family: 'Times New Roman';">1&lt;=N&lt;=100000, 1&lt;=a,b&lt;=n,C&lt;=Maxlongint</span></p>
</div>
</div>
<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在卡卡的房子外面，有一棵苹果树。每年的春天，树上总会结出很多的苹果。卡卡非常喜欢吃苹果，所以他一直都精心的呵护这棵苹果树。我们知道树是有很多分叉点的，苹果会长在枝条的分叉点上面，且不会有两个苹果结在一起。卡卡很想知道一个分叉点所代表的子树上所结的苹果的数目，以便研究苹果树哪些枝条的结果能力比较强。</p>
<p>卡卡所知道的是，每隔一些时间，某些分叉点上会结出一些苹果，但是卡卡所不知道的是，总会有一些调皮的小孩来树上摘走一些苹果。</p>
<p>于是我们定义两种操作：</p>
<table>
<tbody>
<tr>
<td valign="top" width="162">
<p>C x</p>
</td>
<td valign="top" width="294">
<p>表示编号为<span style="font-family: 'Times New Roman';">x</span><span style="">的分叉点的状态被改变</span><span style="font-family: 'Times New Roman';">(</span><span style="">原来有苹果的话，就被摘掉，原来没有的话，就结出一个苹果</span><span style="font-family: 'Times New Roman';">)</span></p>
</td>
</tr>
<tr>
<td valign="top" width="162">
<p>G x</p>
</td>
<td valign="top" width="294">
<p>查询编号为<span style="font-family: 'Times New Roman';">x</span><span style="">的分叉点所代表的子树中有多少个苹果</span></p>
</td>
</tr>
</tbody>
</table>
<p>我们假定一开始的时候，树上全都是苹果，也包括作为根结点的分叉<span style="font-family: 'Times New Roman';">1</span><span style="">。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个数<span style="font-family: 'Times New Roman';">N (n&lt;=100000)</span></p>
<p>接下来<span style="font-family: 'Times New Roman';">n-1</span><span style="">行</span><span style="font-family: 'Times New Roman';">,</span><span style="">每行</span><span style="font-family: 'Times New Roman';">2</span><span style="">个数</span><span style="font-family: 'Times New Roman';">u,v,</span><span style="">表示分叉点</span><span style="font-family: 'Times New Roman';">u</span><span style="">和分叉点</span><span style="font-family: 'Times New Roman';">v</span><span style="">是直接相连的。</span></p>
<p>再接下来一行一个数<span style="font-family: 'Times New Roman';">M,(M&lt;=100000)</span><span style="">表示询问数</span></p>
<p>接下来<span style="font-family: 'Times New Roman';">M</span><span style="">行</span><span style="font-family: 'Times New Roman';">,</span><span style="">表示询问</span><span style="font-family: 'Times New Roman';">,</span><span style="">询问的格式如题目所述</span><span style="font-family: 'Times New Roman';">Q x</span><span style="">或者</span><span style="font-family: 'Times New Roman';">C x</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">对于每个<span style="font-family: 'Times New Roman';">Q&nbsp;x</span><span style="font-family: 宋体;">的询问</span><span style="font-family: 'Times New Roman';">,</span><span style="font-family: 宋体;">请输出相应的结果</span><span style="font-family: 'Times New Roman';">,</span><span style="font-family: 宋体;">每行输出一个</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>1 2</p>
<p>1 3</p>
<p>3</p>
<p>Q 1</p>
<p>C 2</p>
<p>Q 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>
<p>3</p>
<p>2</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>
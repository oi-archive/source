<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">我们现在要利用</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">m</span></span></span></span><span style="">台机器加工</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">n</span></span></span></span><span style="">个工件，每个工件都有</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">m</span></span></span></span><span style="">道工序，每道工序都在不同的指定的机器上完成。每个工件的每道工序都有指定的加工时间。</span></p>
<p style=""><span style="">每个工件的每个工序称为一个操作，我们用记号</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">j-k</span></span></span></span><span style="">表示一个操作，其中</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">j</span></span></span></span><span style="">为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span><span style="">到</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">n</span></span></span></span><span style="">中的某个数字，为工件号；</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">k</span></span></span></span><span style="">为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span><span style="">到</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">m</span></span></span></span><span style="">中的某个数字，为工序号，例如</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2-4</span></span></span></span><span style="">表示第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2</span></span></span></span><span style="">个工件第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">4</span></span></span></span><span style="">道工序的这个操作。在本题中，我们还给定对于各操作的一个安排顺序。</span></p>
<p style=""><span style="">例如，当</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">n=3</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">m=2</span></span></span></span><span style="">时，“</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1-1</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1-2</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2-1</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">3-1</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">3-2</span></span></span></span><span style="">，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2-2</span><span style="">”</span></span></span></span><span style="">就是一个给定的安排顺序，即先安排第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span><span style="">个工件的第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span><span style="">个工序，再安排第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span><span style="">个工件的第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2</span></span></span></span><span style="">个工序，然后再安排第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2</span></span></span></span><span style="">个工件的第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span><span style="">个工序，等等。</span></p>
<p style=""><span style="">一方面，每个操作的安排都要满足以下的两个约束条件。</span></p>
<p style=""><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">(1) </span></span></span></span><span style="">对同一个工件，每道工序必须在它前面的工序完成后才能开始；</span></p>
<p style=""><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">(2) </span></span></span></span><span style="">同一时刻每一台机器至多只能加工一个工件。</span></p>
<p style=""><span style="">另一方面，在安排后面的操作时，不能改动前面已安排的操作的工作状态。</span></p>
<p style=""><span style="">由于同一工件都是按工序的顺序安排的，因此，只按原顺序给出工件号，仍可得到同样的安排顺序，于是，在输入数据中，我们将这个安排顺序简写为“</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1 1 2 3 3 2</span><span style="">”</span></span></span></span><span style="">。</span></p>
<p style=""><span style="">还要注意，“安排顺序”只要求按照给定的顺序安排每个操作。不一定是各机器上的实际操作顺序。在具体实施时，有可能排在后面的某个操作比前面的某个操作先完成。</span></p>
<p style=""><span style="">例如，取</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">n=3,m=2</span></span></span></span><span style="">，已知数据如下：</span></p>
&lt;dl&gt;&lt;dd&gt;
&lt;colgroup&gt;&lt;col width="76"/&gt; &lt;col width="77"/&gt; &lt;col width="78"/&gt; &lt;/colgroup&gt;
<table cellpadding="7" cellspacing="0" style=""><tbody>
<tr>
<td style="" width="76">
<p style=""><span style="">工件号</span></p>
</td>
<td style="" width="169">
<p style=""><span style="">机器号</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">/</span></span></span></span><span style="">加工时间</span></p>
</td>
</tr>
<tr>
<td style="" width="77">
<p style=""><span style="">工序</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span></p>
</td>
<td style="" width="78">
<p style=""><span style="">工序</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2</span></span></span></span></p>
</td>
</tr>
<tr>
<td style="" width="76">
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>1</span></span></span></p>
</td>
<td style="" width="77">
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>1/3</span></span></span></p>
</td>
<td style="" width="78">
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>2/2</span></span></span></p>
</td>
</tr>
<tr>
<td style="" width="76">
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>2</span></span></span></p>
</td>
<td style="" width="77">
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>1/2</span></span></span></p>
</td>
<td style="" width="78">
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>2/5</span></span></span></p>
</td>
</tr>
<tr>
<td style="" width="76">
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>3</span></span></span></p>
</td>
<td style="" width="77">
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>2/2</span></span></span></p>
</td>
<td style="" width="78">
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>1/4</span></span></span></p>
</td>
</tr>
</tbody>
</table>
&lt;/dd&gt;&lt;/dl&gt;
<p style=""><span style="">则对于安排顺序“</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="">1 1 2 3 3 2”</span></span></span></span><span style="">，下图中的两个实施方案都是正确的。但所需要的总时间分别是</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">10</span></span></span></span><span style="">与</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">12</span></span></span></span><span style="">。</span></p>
<p style=""><span style="">　</span></p>
<p style=""><span style="">当一个操作插入到某台机器的某个空档时（机器上最后的尚未安排操作的部分也可以看作一个空档），可以靠前插入，也可以靠后或居中插入。为了使问题简单一些，我们约定：在保证约束条件（</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span><span style="">）（</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2</span></span></span></span><span style="">）的条件下，尽量靠前插入。并且，我们还约定，如果有多个空档可以插入，就在保证约束条件（</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span><span style="">）（</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2</span></span></span></span><span style="">）的条件下，插入到最前面的一个空档。于是，在这些约定下，上例中的方案一是正确的，而方案二是不正确的。</span></p>
<p style=""><span style="">显然，在这些约定下，对于给定的安排顺序，符合该安排顺序的实施方案是唯一的，请你计算出该方案完成全部任务所需的总时间。</span></p>

<img src="/source/codevs/codevs-1156/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9pbWFnZS9wcm9ibGVtLzExNTYuanBn.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第</span><span style=""><span style=""><span>1</span></span></span><span style="">行为两个正整数，用一个空格隔开：</span></p>
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>m n</span></span></span></p>
<p style=""><span style="">（其中</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">m</span></span></span></span><span style="">（</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">&lt;20</span></span></span></span><span style="">）表示机器数，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">n</span></span></span></span><span style="">（</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">&lt;20</span></span></span></span><span style="">）表示工件数）</span></p>
<p style=""><span style="">第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2</span></span></span></span><span style="">行：个用空格隔开的数，为给定的安排顺序。</span></p>
<p style=""><span style="">接下来的</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2n</span></span></span></span><span style="">行，每行都是用空格隔开的</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">m</span></span></span></span><span style="">个正整数，每个数不超过</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">20</span></span></span></span><span style="">。</span></p>
<p style=""><span style="">其中前</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">n</span></span></span></span><span style="">行依次表示每个工件的每个工序所使用的机器号，第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span><span style="">个数为第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span><span style="">个工序的机器号，第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2</span></span></span></span><span style="">个数为第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2</span></span></span></span><span style="">个工序机器号，等等。</span></p>
<p style=""><span style="">后</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">n</span></span></span></span><span style="">行依次表示每个工件的每个工序的加工时间。</span></p>
<p style=""><span style="">可以保证，以上各数据都是正确的，不必检验。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="cjk" style="text-indent: 0.19cm; margin-top: 0.49cm; margin-bottom: 0.49cm; widows: 2; orphans: 2;" align="LEFT"><span style="font-size: small;">只有一个正整数，为最少的加工时间</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p> 2 3</p>
<p>1 1 2 3 3 2</p>
<p>1 2</p>
<p>1 2</p>
<p>2 1</p>
<p>3 2</p>
<p>2 5</p>
<p>2 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
如描述
</div>
</div>
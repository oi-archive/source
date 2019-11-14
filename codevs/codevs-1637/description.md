<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某地临时居民想获得长期居住权就必须申请拿到红牌。获得红牌的过程是相当复杂 ，一共包括<span style="font-family: 'Times New Roman';">N</span><span style="">个步骤。每一步骤都由政府的某个工作人员负责检查你所提交的材料是否符合条件。为了加快进程，每一步政府都派了</span><span style="font-family: 'Times New Roman';">M</span><span style="">个工作人员来检查材料。不幸的是，并不是每一个工作人员效率都很高。尽管如此，为了体现“公开政府”的政策，政府部门把每一个工作人员的处理一个申请所花天数都对外界公开。</span></p>
<p>为了防止所有申请人都到效率高的工作人员去申请。这<span style="font-family: 'Times New Roman';">M*N</span><span style="">个工作人员被分成</span><span style="font-family: 'Times New Roman';">M</span><span style="">个小组。每一组在每一步都有一个工作人员。申请人可以选择任意一个小组也可以更换小组。但是更换小组是很严格的，一定要相邻两个步骤之间来更换，而不能在某一步骤已经开始但还没结束的时候提出更换，并且也只能从原来的小组</span>I更换到小组I+1,<span style="">当然从小组</span><span style="font-family: 'Times New Roman';">M</span><span style="">可以更换到小组</span><span style="font-family: 'Times New Roman';">1</span><span style="">。对更换小组的次数没有限制。</span></p>
<p>例如：下面是<span style="font-family: 'Times New Roman';">3</span><span style="">个小组，每个小组</span><span style="font-family: 'Times New Roman';">4</span><span style="">个步骤工作天数：</span></p>
<p>小组<span style="font-family: 'Times New Roman';">1    2 6 1 8</span></p>
<p>小组<span style="font-family: 'Times New Roman';">2    3 6 2 6</span></p>
<p>小组<span style="font-family: 'Times New Roman';">3    4 2 3 6</span></p>
<p>例子中，可以选择小组<span style="font-family: 'Times New Roman';">1</span><span style="">来完成整个过程一共花了</span><span style="font-family: 'Times New Roman';">2+6+1+8=17</span><span style="">天，也可以从小组</span><span style="font-family: 'Times New Roman';">2</span><span style="">开始第一步，然后第二步更换到小组</span><span style="font-family: 'Times New Roman';">2</span><span style="">，第三步到小组</span><span style="font-family: 'Times New Roman';">1</span><span style="">，第四步再到小组</span><span style="font-family: 'Times New Roman';">2</span><span style="">，这样一共花了</span><span style="font-family: 'Times New Roman';">3+2+1+6=12</span><span style="">天。你可以发现没有比这样效率更高的选择。</span></p>
<p>你的任务是求出完成申请所花最少天数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是两个整数<span style="font-family: 'Times New Roman';">N(1&lt;=N&lt;=2000)</span><span style="">和</span><span style="font-family: 'Times New Roman';">M(1&lt;=M&lt;=1000),</span><span style="">表示步数和小组数。接下来有</span><span style="font-family: 'Times New Roman';">M</span><span style="">行，每行</span><span style="font-family: 'Times New Roman';">N</span><span style="">个整数，第</span><span style="font-family: 'Times New Roman';">i+1(1&lt;=i&lt;=M)</span><span style="">行的第</span><span style="font-family: 'Times New Roman';">j</span><span style="">个数表示小组</span><span style="font-family: 'Times New Roman';">i</span><span style="">完成第</span><span style="font-family: 'Times New Roman';">j</span><span style="">步所花的天数，天数都不超过</span><span style="font-family: 'Times New Roman';">1000000</span><span style="">。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出完成所有步所需最少天数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 3 </p>
<p>2 6 1 8</p>
<p>3 6 2 6</p>
<p>4 2 3 6 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12</p>

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
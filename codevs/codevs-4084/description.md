<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">每个人都知道秘密特工</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">007</span><span style="">，流行的宋晨东</span><span style="">。一个鲜为人知的事实是，他自己没有真的执行大部分的任务，而是由他的表兄弟们</span><span style=""><span style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif;">宋晚东</span></span><span style="">完成。</span><span style=""><span style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif;">宋晨东</span></span><span style="">已经厌倦将得到新任务后又分配指派任务给</span><span style="">&lt;font face="Helvetica Neue, Helvetica, Arial, sans-serif"&gt;宋晚东&lt;/font&gt;</span><span style="">，所以他要求你帮他。</span></p><p style=""><span style="">每个月</span><span style=""><span style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif;">宋晨东</span></span><span style="">收到一个任务列表。他从过去的任务中知道详细的情报，每个表兄弟</span><span style=""><span style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif;">宋晚东</span></span><span style="">对于每个任务都有不同的成功完成的概率。宋晨东和宋晚东急于应付一次次从的任务，所以将这个任务交给了你，你是否也能成为宋晨东那样的特工呢？你只需要计算出最大的任务完成就够了。。</span></p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="">注意：所有任务成功完成的最大概率是每个任务成功概率之积。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行包括一个整数</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">N</span><span style="">，表示任务和宋晚东</span><span style="">的数量（</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">1</span><span style="">≤</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">N</span><span style="">≤</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">20</span><span style="">）。接下来的</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">N</span><span style="">行中每行包括</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">N</span><span style="">个</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">0</span><span style="">至</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">100</span><span style="">之间的整数。第</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">i</span><span style="">行的第</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">j</span><span style="">个数表示第</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">i</span><span style="">个</span><span style=""><span style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif;">宋晚东</span></span><span style="">成功执行第</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">j</span><span style="">个任务的概率，数据时以百分比的形式给出。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-top: 0px;margin-bottom: 9px;font-family: &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif;font-size: 13px;line-height: 18px;color: rgb(51, 51, 51);white-space: normal"><span style="font-size: 16px;font-family: 宋体">输出这些任务全部成功完成的最大概率，以百分比的形式输出。</span></p><p style="margin-top: 0px;margin-bottom: 9px;font-family: &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif;font-size: 13px;line-height: 18px;color: rgb(51, 51, 51);white-space: normal"><span style="font-size: 16px;font-family: 宋体">注意：输出结果与官方结果相差±</span><span style="font-size: 16px">0.000001</span><span style="font-size: 16px;font-family: 宋体">是被允许的。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: monospace;">2
100  100
50  50</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: monospace;">50.00000</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于第三个样例数据，如果</span><span style=""><span style="font-family: Helvetica Neue, Helvetica, Arial, sans-serif;">宋晚东</span></span><span style="">接受了第三个任务，宋晚东</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">接受了第一个任务，宋晚东</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">接受了第二个任务，那么所有任务完成的概率为</span><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">1.0*0.13*0.7=0.091=9.1%</span><span style="">。其他的任务的分配都比这个概率小。</span></p><p><span style=""><br></span>
</p>
</div>
</div>
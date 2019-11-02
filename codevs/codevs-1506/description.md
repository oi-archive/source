<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一个朋友网络，如果<span style="font-family: 'Times New Roman';">a</span><span style="">认识</span><span style="font-family: 'Times New Roman';">b</span><span style="">，那么如果</span><span style="font-family: 'Times New Roman';">a</span><span style="">第一次收到某个消息，那么会把这个消息传给</span><span style="font-family: 'Times New Roman';">b</span><span style="">，以及所有</span><span style="font-family: 'Times New Roman';">a</span><span style="">认识的人。</span></p>
<p>如果<span style="font-family: 'Times New Roman';">a</span><span style="">认识</span><span style="font-family: 'Times New Roman';">b</span><span style="">，</span><span style="font-family: 'Times New Roman';">b</span><span style="">不一定认识</span><span style="font-family: 'Times New Roman';">a</span><span style="">。</span></p>
<p>所有人从<span style="font-family: 'Times New Roman';">1</span><span style="">到</span><span style="font-family: 'Times New Roman';">n</span><span style="">编号，给出所有“认识”关系，问如果</span><span style="font-family: 'Times New Roman';">i</span><span style="">发布一条新消息，那么会不会经过若干次传话后，这个消息传回给了</span><span style="font-family: 'Times New Roman';">i</span><span style="">，</span><span style="font-family: 'Times New Roman';">1&lt;=i&lt;=n</span><span style="">。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是<span style="font-family: 'Times New Roman';">n</span><span style="">和</span><span style="font-family: 'Times New Roman';">m</span><span style="">，表示人数和认识关系数。</span></p>
<p>接下来的<span style="font-family: 'Times New Roman';">m</span><span style="">行，每行两个数</span><span style="font-family: 'Times New Roman';">a</span><span style="">和</span><span style="font-family: 'Times New Roman';">b</span><span style="">，表示</span><span style="font-family: 'Times New Roman';">a</span><span style="">认识</span><span style="font-family: 'Times New Roman';">b</span><span style="">。</span><span style="font-family: 'Times New Roman';">1&lt;=a, b&lt;=n</span><span style="">。认识关系可能会重复给出，但一行的两个数不会相同。</span></p>
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

<p class="p0">一共<span style="font-family: 'Times New Roman';">n</span><span style="font-family: 宋体;">行，每行一个字符</span><span style="font-family: 'Times New Roman';">T</span><span style="font-family: 宋体;">或</span><span style="font-family: 'Times New Roman';">F</span><span style="font-family: 宋体;">。第</span><span style="font-family: 'Times New Roman';">i</span><span style="font-family: 宋体;">行如果是</span><span style="font-family: 'Times New Roman';">T</span><span style="font-family: 宋体;">，表示</span><span style="font-family: 'Times New Roman';">i</span><span style="font-family: 宋体;">发出一条新消息会传回给</span><span style="font-family: 'Times New Roman';">i</span><span style="font-family: 宋体;">；如果是</span><span style="font-family: 'Times New Roman';">F</span><span style="font-family: 宋体;">，表示</span><span style="font-family: 'Times New Roman';">i</span><span style="font-family: 宋体;">发出一条新消息不会传回给</span><span style="font-family: 'Times New Roman';">i</span><span style="font-family: 宋体;">。</span></p>
<p class="p0">&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 6</p>
<p>1 2</p>
<p>2 3</p>
<p>4 1</p>
<p>3 1</p>
<p>1 3</p>
<p>2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>T</p>
<p>T</p>
<p>T</p>
<p>F</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>n&lt;=1000</span></p>
<p><span>1&lt;=a, b&lt;=n</span></p>
</div>
</div>
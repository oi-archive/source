<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p> <span style=""><span style="">•</span></span><span style="">战争时期，前线有</span><span style="">n</span><span style="">个哨所，每个哨所可能会与其他若干个哨所之间有通信联系。信使负责在</span><span style="">哨所之间传递信息，当然，这是要花费一定时间的（以天为单位）。指挥部设在第一个哨所。</span><span style="">当指挥部下达一个命令后，指挥部就派出若干个信使向与指挥部相连的哨所送信。当一个哨所</span><span style="">接到信后，这个哨所内的信使们也以同样的方式向其他哨所送信。直至所有</span><span style="">n</span><span style="">个哨所全部接到</span><span style="">命令后，送信才算成功。因为准备充足，每个哨所内都安排了足够的信使（如果一个哨所与其</span><span style="">他</span><span style="">k</span><span style="">个哨所有通信联系的话，这个哨所内至少会配备</span><span style="">k</span><span style="">个信使）。 </span> <span style=""><span style="">•</span></span><span style="">    </span><span style="">现在总指挥请你编一个程序，计算出完成整个送信过程最短需要多少时间</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p> <span style=""><span style="">•</span></span><span style="">第</span><span style="">1</span><span style="">行有两个整数</span><span style="">n</span><span style="">和</span><span style="">m</span><span style="">，中间用</span><span style="">1</span><span style="">个空格隔开，分别表示有</span><span style="">n</span><span style="">个哨所和</span><span style="">m</span><span style="">条通信线路。</span><span style="">1&lt;=n&lt;=100</span><span style="">。 </span> <span style=""><span style="">•</span></span><span style="">    </span><span style="">第</span><span style="">2</span><span style="">至</span><span style="">m+1</span><span style="">行：每行三个整数</span><span style="">i</span><span style="">、</span><span style="">j</span><span style="">、</span><span style="">k</span><span style="">，中间用</span><span style="">1</span><span style="">个空格隔开，表示第</span><span style="">i</span><span style="">个和第</span><span style="">j</span><span style="">个哨所之间存在</span><span style="">通信线路，且这条线路要花费</span><span style="">k</span><span style="">天。 </span>  </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family:微软雅黑;font-size:21px;color:#002060">仅一个整数，表示完成整个送信过程的最短时间。如果不是所有的哨所都能收到信，就输出</span><span style=";font-size:21px;color:#002060">-1</span><span style="font-family:微软雅黑;font-size:21px;color:#002060">。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p> <span style=""><span style="">•</span></span><span style="">4 4 </span> <span style=""><span style="">•</span></span><span style="">    </span></p><p><span style="">1 2 4 </span> <span style=""><span style="">•</span></span><span style="">    </span></p><p><span style="">2 3 7 </span> <span style=""><span style="">•</span></span><span style="">   </span></p><p><span style="">2 4 1 </span> <span style=""><span style="">•</span></span><span style="">    </span></p><p><span style="">3 4 6 </span>  </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">11</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">1&lt;=n&lt;=100</span></p>
</div>
</div>
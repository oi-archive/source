<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<h3 style=""><span style="font-family: Century Gothic;"> </span></h3><p><span style=""><span style="">由于炉石传说新资料片的上线，网易的服务器又喜闻乐见的爆炸了，玩家们在炉石旅店门口排起了长队。</span></span></p><p><span style=""><span style="">每当这种时候就会有插队者出现。</span></span></p><p><span style=""><span style="">现在炉石旅店打开了一个新的入口，有</span></span><span style="font-family: Century Gothic;">N</span><span style=""><span style="">个人前来排（插）队，旅店老板想知道最终队伍会是什么；</span></span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<h3 style=""><span style=""><span style="font-family: Century Gothic;"> </span></span></h3><p><span style=""><span style="">第一行，一个整数</span></span><span style="font-family: Century Gothic;">N</span></p><p><span style=""><span style="">第</span></span><span style="font-family: Century Gothic;">2…N+1</span><span style=""><span style="">行，第</span></span><span style="font-family: Century Gothic;">i+1</span><span style=""><span style="">行两个整数</span></span><span style="font-family: Century Gothic;">POS_i</span><span style=""><span style="">，</span></span><span style="font-family: Century Gothic;">VAL_i,</span><span style=""><span style="">表示编号为</span></span><span style="font-family: Century Gothic;">VAL_i</span><span style=""><span style="">的人将要插入</span></span><span style="font-family: Century Gothic;">POS_i</span><span style=""><span style="">位置。</span></span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin: 0cm 0cm 0pt;"><span style="font-family:&quot;Microsoft YaHei UI&quot;,sans-serif;
mso-ascii-font-family:&quot;Century Gothic&quot;;mso-ascii-theme-font:minor-latin;
mso-hansi-font-family:&quot;Century Gothic&quot;;mso-hansi-theme-font:minor-latin"><span style="font-size:12px">一行 最终的队伍</span></span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: Century Gothic;">4</span></p><p><span style="font-family: Century Gothic;">0 72</span></p><p><span style="font-family: Century Gothic;">1 512</span></p><p><span style="font-family: Century Gothic;">1 33</span></p><p><span style="font-family: Century Gothic;">2 69</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: Century Gothic;">72 33 69 512</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
&lt;h5 style="margin: 3px 0 0"&gt;<span style="font-family: Microsoft YaHei;">样例解释</span>&lt;/h5&gt;<p><span style="font-family: Century Gothic;">77</span><span style=""><span style="">排在</span></span><span style="font-family: Century Gothic;">0</span><span style=""><span style="">号位，</span></span><span style="font-family: Century Gothic;">72</span></p><p><span style="font-family: Century Gothic;">51</span><span style=""><span style="">排在</span></span><span style="font-family: Century Gothic;">1</span><span style=""><span style="">号位，</span></span><span style="font-family: Century Gothic;">72</span><span style="font-family: Century Gothic;">  </span><span style="font-family: Century Gothic;">512</span></p><p><span style="font-family: Century Gothic;">33</span><span style=""><span style="">插入</span></span><span style="font-family: Century Gothic;">1</span><span style=""><span style="">号位，</span></span><span style="font-family: Century Gothic;">72 </span><span style="font-family: Century Gothic;"> </span><span style="font-family: Century Gothic;">33</span><span style="font-family: Century Gothic;">  </span><span style="font-family: Century Gothic;">512</span></p><p><span style="font-family: Century Gothic;">69</span><span style=""><span style="">插入</span></span><span style="font-family: Century Gothic;">2</span><span style=""><span style="">号位，</span></span><span style="font-family: Century Gothic;">72</span><span style="font-family: Century Gothic;">  </span><span style="font-family: Century Gothic;">33</span><span style="font-family: Century Gothic;">  </span><span style="font-family: Century Gothic;">69</span><span style="font-family: Century Gothic;">  </span><span style="font-family: Century Gothic;">512</span></p>&lt;h5 style="margin: 3px 0 0"&gt;<span style="font-family: Microsoft YaHei;">数据范围</span>&lt;/h5&gt;<p><span style="font-family: Century Gothic;">1&lt;=N&lt;=200000</span></p><p><span style="font-family: Century Gothic;">VAL</span><span style=""><span style="">∈</span></span><span style="font-family: Century Gothic;">[0,32767]</span></p><p><span style="">POS</span><span style="">∈</span><span style="">[0,N-1]</span><span style="">，有可能重名</span><span style=""> `</span></p><p><br></p>
</div>
</div>
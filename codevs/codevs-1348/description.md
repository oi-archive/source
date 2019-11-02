<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<ul>
<li>
<p>一个月黑风高的夜晚，<span style="font-family: Verdana;">Farmer Lunar </span><span style="">的粮仓遭到了前所未有的偷袭。不但所有的粮食被席卷一空，就连所有的运输系统都被残忍地破坏。近日，</span><span style="font-family: Verdana;">FL</span><span style="">的板猪们因为营养不良而面黄肌瘦。</span></p>
<p>FL<span style="">决定重建粮仓和运输系统！！！</span></p>
<p>“爱心人士”<span style="font-family: Verdana;">ZN</span><span style="">（请勿对号入座）向</span><span style="font-family: Verdana;">FL</span><span style="">伸出了援手。</span><span style="font-family: Verdana;">(BZ:</span> 好感动啊<span style="font-family: Verdana;">o(</span><span style="">≧</span><span style="font-family: Verdana;">v</span><span style="">≦</span><span style="font-family: Verdana;">)o~~)</span></p>
<p>但是，<span style="font-family: Verdana;">ZN</span><span style="">终于露出了狰狞的面目。</span></p>
<p>ZN<span style="">：这些建粮仓的钱都要你们自己付，运输系统的建造费也要你们自己掏腰包！！现在我告诉你在第</span><span style="font-family: Verdana;">I</span><span style="">个板猪圈建粮仓，需要代价</span>W_i (1 &lt;= W_i &lt;= 100,000)，任意两个板猪圈之间建运输系统的代价P_ij (1 &lt;= P_ij &lt;=100,000; P_ij = P_ji; P_ii=0)，你们自己找出方案吧。</p>
<p>Farmer Lunar<span style="">希望花最少的钱完成这个工作</span><span style="font-family: Verdana;">,</span><span style="">使得每一个板猪圈都能够通过自身建造粮仓或通过运输系统从别的粮仓得到粮食来获取食物。你的任务就是输出最少要花费多少钱！！（</span><span style="font-family: Verdana;">PS:</span><span style="">纯属信心题）</span></p>
</li>
</ul>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>* </span><span>第一行</span><span>: </span><span>只有一个整数<span style="font-family: Verdana;">N</span></span><span>(1 &lt;= N &lt;= 300)</span><span>，表示<span style="font-family: Verdana;">Farmer Lunar</span><span style="">的农场里共有</span><span style="font-family: Verdana;">N</span><span style="">个板猪圈。</span></span></p>
<p> </p>
<p><span>* </span><span>第<span style="font-family: Verdana;">2</span></span><span>..N + 1</span><span>行</span><span>:</span><span>第</span><span>i+1</span><span>行包含一个整数</span><span>: W_i</span><span>，含义已在题目描述中给出。</span></p>
<p> </p>
<p><span>* </span><span>第</span><span>N+2..2N+1</span><span>行</span><span>: </span><span>第</span><span>N+1+i</span><span>行包含<span style="font-family: Verdana;">N</span><span style="">个用空格分隔的整数，第</span><span style="font-family: Verdana;">J</span><span style="">个整数是</span></span><span>P_ij</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0"><span>只有一个整数，代表<span style="font-family: Verdana;">Farmer&nbsp;Lunar</span><span style="font-family: 宋体;">至少要花费多少钱。</span></span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>4</span></p>
<p><span>5</span></p>
<p><span>4</span></p>
<p><span>4</span></p>
<p><span>3</span></p>
<p><span>0 2 2 2</span></p>
<p><span>2 0 3 3</span></p>
<p><span>2 3 0 4</span></p>
<p><span>2 3 4 0</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>【样例解释】</span></p>
<p><span>听取了你的建议后<span style="font-family: Verdana;">,Farmer Lunar </span><span style="">决定在第</span><span style="font-family: Verdana;">4</span><span style="">个板猪圈建一座粮仓，花费</span><span style="font-family: Verdana;">3</span><span style="">个单位的代价，然后第</span><span style="font-family: Verdana;">1</span><span style="">个板猪圈与第</span><span style="font-family: Verdana;">4</span><span style="">个板猪圈建立运输系统，花费</span><span style="font-family: Verdana;">2</span><span style="">个单位，第</span><span style="font-family: Verdana;">2</span><span style="">、</span><span style="font-family: Verdana;">3</span><span style="">个板猪圈分别与第</span><span style="font-family: Verdana;">1</span><span style="">个板猪圈建立运输系统，各花费</span><span style="font-family: Verdana;">2</span><span style="">个单位，这样，</span><span style="font-family: Verdana;">4</span><span style="">个板猪圈的板猪们都有粮食吃啦！共计</span><span style="font-family: Verdana;">9</span><span style="">个单位，是最优解。</span></span></p>
<p><span>你要<span style="font-family: Verdana;">AC</span><span style="">的题目在这里</span></span></p>
<p><span>善良的<span style="font-family: Verdana;">XXX</span><span style="">给出了重建完成后的示意图：</span></span></p>
<p><span><img height="272" width="266"></span></p>
<p><span>【数据规模】 </span></p>
<p><span>30% <span style="">数据 </span><span style="font-family: Verdana;">n&lt;=40</span></span></p>
<p><span>50% <span style="">数据 </span><span style="font-family: Verdana;">n&lt;=80</span></span></p>
<p><span>100% <span style="">数据 </span><span style="font-family: Verdana;">n&lt;=300</span></span></p>
<p><span><span style="font-family: Verdana;"><br></span></span></p>
<p><span><span style="font-family: Verdana;"><br></span></span></p>
</div>
</div>
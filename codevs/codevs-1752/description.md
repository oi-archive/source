<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　给定一个树型电网，树中的每条边上有一个电阻R</span><sub>i</sub><span>，电阻值均为10000Ω。下图为一个包含4个节点的树型电路情况：</span></p>
<p><span><img height="211" src="/source/codevs/codevs-1752/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9NFRNODZqMkE=.do" width="310"></span></p>
<p><span>　　树中的所有叶子节点（度为1的节点称为叶子节点）都接地，每条接地线上都附有10000Ω的电阻，最终形成的电网如下图所示：</span></p>
<p><span><img height="344" src="/source/codevs/codevs-1752/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9TERmRGI2NlQ=.do" width="330"></span></p>
<p><span><span>　　现有如下两种操作：</span><br><span>　　C u v w ：表示在边&lt;u,v&gt;上串联一个电源，电源的大小为w伏，电源位于靠近节点u一侧（如下图所示），电源负极指向u。注意同一条边上可以串联多个电源。</span></span></p>
<p><span><span><img height="72" src="/source/codevs/codevs-1752/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9NHJ5M2RiYTc=.do" width="421"></span></span></p>
<p><span><span><span>　　Q u ：表示询问点u当前的电压，此电压是指对地电压。</span><br><span>　　如对上图进行C 2 4 5操作后，网络变为：</span></span></span></p>
<p><span><span><span><img height="397" src="/source/codevs/codevs-1752/img/aHR0cDovL3d3dy50c2luc2VuLmNvbS9SZXF1aXJlRmlsZS5kbz9maWQ9dEVFcVFZcXQ=.do" width="366"></span></span></span></p>
<p><span><span><span><span>　　此时每个节点上的电压见上图的标注。</span></span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　输入第一行包含两个整数N,M，分别表示树的节点数和操作个数。接下来N-1行，每行两个数u,v，表示有一条连接节点u,v的边，这条边上恰好包含一个电阻。</span><br><span>　　接下来M行，每行一个命令，格式见题目描述。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　对于每个Q命令，输出一个数表示此刻该点的电压值。你可以输出任意多位的小数，只要你的答案和标准答案相差不超过10</span><sup>-3</sup><span>就算合法。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>4 3</span><br><span>1 2</span><br><span>2 3</span><br><span>2 4</span><br><span>Q 2</span><br><span>C 2 4 5</span><br><span>Q 2</span></p>
<p><span><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>0.0000000000</span><br><span>-1.6666666666</span></p>
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
<p><span>【样例解释】</span></p>
<p><span>　　对于第一个询问，由于原图中没有电源，所以没有电流，所有点的电压都相等（否则如果有U</span><sub>i</sub><span>&gt;U</span><sub>j</sub><span>，则就有i流向j的电流，与没有电源矛盾）,都等于地电压0V。</span><br><span>　　之后在&lt;2,4&gt;中加一个5V的电源，得到的新图见题目描述。</span><br><span>　　整理后可以发现，新图的形式是串联(电源,R</span><sub>2</sub><span>+10000,并联(R</span><sub>1</sub><span>+10000, R</span><sub>3</sub><span>+10000))，由此可以得到新图的总电阻为:</span><br><span>　　R</span><sub>2</sub><span>+10000+1/(1/(R</span><sub>3</sub><span>+10000)+1/(R</span><sub>1</sub><span>+10000))=30000 Ω.</span><br><span>　　所以流过节点4的电流就是5/30000A，所以U</span><sub>4</sub><span>=5/3V。U</span><sub>2</sub><span>=U</span><sub>4</sub><span>+R</span><sub>2</sub><span>*I-5=-5/3V，由于U</span><sub>1</sub><span>和U</span><sub>3</sub><span>形式对称，由分压关系可知U</span><sub>1</sub><span>=U</span><sub>3</sub><span>=U</span><sub>2</sub><span>*10000/(10000+10000)=-5/6V。</span></p>
<p><span><br></span></p>
<p>【数据规模】</p>
<p><span><span>　　30%的数据保证N,M ≤ 30</span><br><span>　　60%的数据保证N,M ≤ 3000</span><br><span>　　100%的数据保证3 ≤ N,M ≤ 50000，1 ≤ u,v ≤ n，1 ≤ w ≤ 10，树中最长链的长度不超过50。</span></span></p>
</div>
</div>
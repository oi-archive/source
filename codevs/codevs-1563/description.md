<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>农夫约翰的奶牛们喜欢通过电邮保持联系，于是她们建立了一个奶牛电脑网络，以便互相交流。这些机器用如下的方式发送电邮：如果存在一个由<span style="font-family: Times New Roman;">c</span><span style="">台电脑组成的序列</span><span style="font-family: Times New Roman;">a1,a2,...,a(c)</span><span style="">，且</span><span style="font-family: Times New Roman;">a1</span><span style="">与</span><span style="font-family: Times New Roman;">a2</span><span style="">相连，</span><span style="font-family: Times New Roman;">a2</span><span style="">与</span><span style="font-family: Times New Roman;">a3</span><span style="">相连，等等，那么电脑</span><span style="font-family: Times New Roman;">a1</span><span style="">和</span><span style="font-family: Times New Roman;">a(c)</span><span style="">就可以互发电邮。 </span></p>
<p> </p>
<p>很不幸，有时候奶牛会不小心踩到电脑上，农夫约翰的车也可能碾过电脑，这台倒霉的电脑就会坏掉。这意味着这台电脑不能再发送电邮了，于是与这台电脑相关的连接也就不可用了。 </p>
<p> </p>
<p>有两头奶牛就想：如果我们两个不能互发电邮，至少需要坏掉多少台电脑呢？请编写一个程序为她们计算这个最小值。 </p>
<p> </p>
<p>以如下网络为例： </p>
<p> </p>
<p>　　　　　　   <span style="font-family: Times New Roman;">1*</span></p>
<p>　　　　　　  <span style="font-family: Times New Roman;">/  </span></p>
<p>　　　　　　 <span style="font-family: Times New Roman;">3 - 2*</span></p>
<p> </p>
<p>这张图画的是有<span style="font-family: Times New Roman;">2</span><span style="">条连接的</span><span style="font-family: Times New Roman;">3</span><span style="">台电脑。我们想要在电脑</span><span style="font-family: Times New Roman;">1</span><span style="">和</span><span style="font-family: Times New Roman;">2</span><span style="">之间传送信息。电脑</span><span style="font-family: Times New Roman;">1</span><span style="">与</span><span style="font-family: Times New Roman;">3</span><span style="">、</span><span style="font-family: Times New Roman;">2</span><span style="">与</span><span style="font-family: Times New Roman;">3</span><span style="">直接连通。如果电脑</span><span style="font-family: Times New Roman;">3</span><span style="">坏了，电脑</span><span style="font-family: Times New Roman;">1</span><span style="">与</span><span style="font-family: Times New Roman;">2</span><span style="">便不能互发信息了。 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行 四个由空格分隔的整数：<span style="font-family: Times New Roman;">N,M,c1,c2.N</span><span style="">是电脑总数</span><span style="font-family: Times New Roman;">(1&lt;=N&lt;=100)</span><span style="">，电脑由</span><span style="font-family: Times New Roman;">1</span><span style="">到</span><span style="font-family: Times New Roman;">N</span><span style="">编号。</span><span style="font-family: Times New Roman;">M</span><span style="">是电脑之间连接的总数</span><span style="font-family: Times New Roman;">(1&lt;=M&lt;=600)</span><span style="">。最后的两个整数</span><span style="font-family: Times New Roman;">c1</span><span style="">和</span><span style="font-family: Times New Roman;">c2</span><span style="">是上述两头奶牛使用的电脑编号。连接没有重复且均为双向的</span><span style="font-family: Times New Roman;">(</span><span style="">即如果</span><span style="font-family: Times New Roman;">c1</span><span style="">与</span><span style="font-family: Times New Roman;">c2</span><span style="">相连，那么</span><span style="font-family: Times New Roman;">c2</span><span style="">与</span><span style="font-family: Times New Roman;">c1</span><span style="">也相连</span><span style="font-family: Times New Roman;">)</span><span style="">。两台电脑之间至多有一条连接。电脑</span><span style="font-family: Times New Roman;">c1</span><span style="">和</span><span style="font-family: Times New Roman;">c2</span><span style="">不会直接相连。  </span></p>
<p>第<span style="font-family: Times New Roman;">2</span><span style="">到</span><span style="font-family: Times New Roman;">M+1</span><span style="">行 接下来的</span><span style="font-family: Times New Roman;">M</span><span style="">行中，每行包含两台直接相连的电脑的编号。  </span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一个整数表示使电脑<span style="font-family: Times New Roman;">c1</span><span style="font-family: 宋体;">和</span><span style="font-family: Times New Roman;">c2</span><span style="font-family: 宋体;">不能互相通信需要坏掉的电脑数目的最小值。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 2 1 2</p>
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
<p>1</p>

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
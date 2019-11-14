<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>adamyi喜欢做题目，他的纸上总是写满了一些乱七八糟的自己推导出来的公式。由于他做题心切，纸上的公式总会混在一起而导致他看不清楚。于是，他只好重新推导一遍。但是，悲剧总能不停地发生，为此，adamyi一番懊恼。为了不重蹈覆辙，他决定写一个公式编辑器，让自己推出来的式子容易被自己看懂。</p>
<p>由于adamyi推导的公式经常有一些中间变量，过多的中间变量也让他看起来不方便，所以，他想把中间变量都用其式子代掉。当然，式子不必化简，因为化简后的式子往往会减少原先推导时所具有的一些技巧和特征。</p>
<p>请你帮他写一写。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，一个数n，为中间变量的个数。<br>以下n行，每行为一个中间变量所代表的式子，格式为Variable=Formula。<br>最后一行为最终的公式，格式为Formula。<br>Variable为一个大写字母<br>Formula为一个式子，可以包含未知数（小写字母串）、其他中间变量（这个变量一定出现在它之前）、数字（均为非负实数，不使用科学计数法）以及符号（“+”、“-”、“*”或“/”），保证这个式子一定合法，同时不存在括号，长度不超过128，因为adamyi推导的时候不喜欢把式子写得太烦，所以也不会推错。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个矩形块，表示最终的公式。下面将具体给出矩形块的构造方式，暂且用S（N行*M列）表示大矩形块，S1（N1*M1）和S2（N2*M2）表示子矩形块。<br />S可以为一个数字，N=1,M=数字长度<br />S可以由符号Sign、S1和S2构成，S1、S2用于表示一些中间变量和数字：<br />若S用来描述最后运算的不为除法的式子，即Sign为&ldquo;+&rdquo;、&ldquo;-&rdquo;或&ldquo;*&rdquo;：<br />S从左到右可以表示为S1、Sign和S2的并，N=Max{N1,N2}，M=M1+M2+1。分数线、数字、符号、括号必须在同一直线上。<br />当然，为了不改变运算顺序，并且保证代入后的式子始终正确，同时，adamyi还能从最终的公式中发现自己的推导过程，所以如果S1描述的是一个中间变量所代表的式子的矩形块，这个式子既不是单纯一个数字，并且最后运算的不为除法，则S1可能需要事先变为&ldquo;（&rdquo;、S1和&ldquo;）&rdquo;的并，注意括号需要列居中。若Sign为&ldquo;*&rdquo;，则S1要变；若Sign为&ldquo;+&rdquo;或&ldquo;-&rdquo;且S1最后运算的不为乘法，则S1要变。S2与S1相同处理。<br />若S用来描述最后的运算为除法的式子，即Sign为&ldquo;/&rdquo;：<br />S从上到下可以表示为S1、M个&ldquo;-&rdquo;和S2的并，N为N1+N2+1，M为Max{N1,N2}+2。S1和S2必须列居中（S1的左方的空列与右方的相差最多为1，并且右方的不比左方的多，S2与S1相同格式）。<br />上面提到的空行与空列用空格填充。</p>
<p>注意，在输出矩形块之后，需用空格填充一行空行。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>2</span></p>
<p><span>A=35/4</span></p>
<p><span>B=1+2*A</span></p>
<p><span>A+B</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="text-decoration: underline;"> 35        35  </span><br><span style="text-decoration: underline;">----+(1+2*----)</span><br><span style="text-decoration: underline;">  4         4  </span><br><span style="text-decoration: underline;">               </span></p>
<p> </p>
<p>（下划线仅为区分该位置有没有空格，并非程序输出。敬请留意）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据范围】<br><br>对于100%的数据，n&lt;=26，计算过程中及最终输出的矩形块不会超出60*60<br><br><br><br>保证让你们一次做个够……</p>
</div>
</div>
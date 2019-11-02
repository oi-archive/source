<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="">人工神经网络（<span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span>Artificial Neural Network</span></span></span>）是一种新兴的具有自我学习能力的计算系统，在模式识别、函数逼近及贷款风险评估等诸多领域有广泛的应用。对神经网络的研究一直是当今的热门方向，兰兰同学在自学了一本神经网络的入门书籍后，提出了一个简化模型，他希望你能帮助他用程序检验这个神经网络模型的实用性。</p>
<p style="">【问题描述】</p>
<p style="">在兰兰的模型中，神经网络就是一张有向图，图中的节点称为神经元，而且两个神经</p>
<p style="">元之间至多有一条边相连，下图是一个神经元的例子：</p>
<p style=""> </p>
<p style="">神经元〔编号为<span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span>1</span></span></span>）</p>
<p style="">图中，<span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span>X1—X3</span></span></span>是信息输入渠道，<span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span>Y1</span></span></span>－<span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span>Y2</span></span></span>是信息输出渠道，<span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span>C1</span></span></span>表示神经元目前的状态，</p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span>Ui</span></span></span>是阈值，可视为神经元的一个内在参数。</p>
<p style="">神经元按一定的顺序排列，构成整个神经网络。在兰兰的模型之中，神经网络中的神</p>
<p style="">经无分为几层；称为输入层、输出层，和若干个中间层。每层神经元只向下一层的神经元</p>
<p style="">输出信息，只从上一层神经元接受信息。下图是一个简单的三层神经网络的例子。</p>
<p style=""> </p>
<p style="">兰兰规定，<span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span>C<sub>i</sub></span></span></span>服从公式：（其中<span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span>n</span></span></span>是网络中所有神经元的数目）</p>
<p style=""><img height="67" src="/source/codevs/codevs-1088/img/aHR0cDovL3d3dy5jcHBibG9nLmNvbS9pbWFnZXMvY3BwYmxvZ19jb20veGlvbmduYW5iaW4vMy5KUEc=.JPG" title="神经网络公式" width="292"></p>
<p style="">公式中的<span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span>Wji</span></span></span>（可能为负值）表示连接<span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span>j</span></span></span>号神经元和 <span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span>i</span></span></span>号神经元的边的权值。当 <span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span>Ci</span></span></span>大于<span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span>0</span></span></span>时，该神经元处于兴奋状态，否则就处于平静状态。当神经元处于兴奋状态时，下一秒</p>
<p style="">它会向其他神经元传送信号，信号的强度为<span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span>Ci</span></span></span>。</p>
<p style="">如此．在输入层神经元被激发之后，整个网络系统就在信息传输的推动下进行运作。</p>
<p style="">现在，给定一个神经网络，及当前输入层神经元的状态（<span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span>Ci</span></span></span>），要求你的程序运算出最后网络输出层的状态。</p>

<img src="/source/codevs/codevs-1088/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMDg4L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8xMDg4LnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="">输入文件第一行是两个整数<span style="font-family: DejaVu Serif Condensed,serif;">n</span>（<span style="font-family: DejaVu Serif Condensed,serif;">1≤n≤100</span>）和<span style="font-family: DejaVu Serif Condensed,serif;">p</span>。接下来<span style="font-family: DejaVu Serif Condensed,serif;">n</span>行，每行两个整数，第<span style="font-family: DejaVu Serif Condensed,serif;">i</span>＋<span style="font-family: DejaVu Serif Condensed,serif;">1</span>行是神经元<span style="font-family: DejaVu Serif Condensed,serif;">i</span>最初状态和其阈值（<span style="font-family: DejaVu Serif Condensed,serif;">Ui</span>），非输入层的神经元开始时状态必然为<span style="font-family: DejaVu Serif Condensed,serif;">0</span>。再下面<span style="font-family: DejaVu Serif Condensed,serif;">P</span>行，每行由两个整数<span style="font-family: DejaVu Serif Condensed,serif;">i</span>，<span style="font-family: DejaVu Serif Condensed,serif;">j</span>及一个整数<span style="font-family: DejaVu Serif Condensed,serif;">Wij</span>，表示连接神经元<span style="font-family: DejaVu Serif Condensed,serif;">i</span>、<span style="font-family: DejaVu Serif Condensed,serif;">j</span>的边权值为<span style="font-family: DejaVu Serif Condensed,serif;">Wij</span>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-bottom: 0cm;">输出文件包含若干行，每行有两个整数，分别对应一个神经元的编号，及其最后的状</p>
<p style="margin-bottom: 0cm;">态，两个整数间以空格分隔。<span style="text-decoration: underline;">仅输出最后状态非零的输出层神经元状态，并且按照编号由</span></p>
<p style="margin-bottom: 0cm;"><span style="text-decoration: underline;">小到大顺序输出！</span></p>
<p style="margin-bottom: 0cm;">若输出层的神经元最后状态均为 <span style="font-family: DejaVu Serif Condensed,serif;">0</span>，则输出 <span style="font-family: DejaVu Serif Condensed,serif;">NULL</span>。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">5 6</span></p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">1 0</span></p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">1 0</span></p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">0 1</span></p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">0 1</span></p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">0 1</span></p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">1 3 1</span></p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">1 4 1</span></p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">1 5 1</span></p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">2 3 1</span></p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">2 4 1</span></p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">2 5 1</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;"><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">3 1</span></p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">4 1</span></p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;">5 1</span></p>
<p style=""> </p>
<p style=""> </p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;"><br></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>本题描述中的图片较多，详细可搜索网上的原题。</p>
</div>
</div>
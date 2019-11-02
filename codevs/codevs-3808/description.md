<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">在一个矩形台球桌上，从左上角开始发球，要将台球击入右上角、左下角或右下角的任一球洞里。台球最初被斜向发出，撞击到各边上时会改变方向，新旧方向之间满足反射定律（入射角</span>=<span style="">反射角）。假设台球的动力是足够的，台球在撞击并改变方向</span>(n-1)<span style="">次后，最终落入某个球洞里。由于台球改变了</span>(n-1)<span style="">次方向，台球会形成</span>n<span style="">段不同方向的路径（可以知道这些方向一定是斜向的），并且第一段一定是向右下。记向右下的方向标号为</span>1<span style="">，向左下的方向标号为</span>2<span style="">，向左上的方向标号为</span>3<span style="">，向右上的方向标号为</span>4<span style="">。给定</span>n<span style="">段路径的方向标号</span><span style="">，试问可能形成这样的一种路径，并且使得最后落入某个球洞里吗？</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">本题有多组测试数据，第一行是一个正整数</span>t<span style="">，接下来是</span>t<span style="">组测试数据，每组格式如下：</span></p><p>        <span style="">第一行是一个正整数</span>n<span style="">，表示路径段数；</span></p><p>        <span style="">第二行是</span>n<span style="">个</span>1<span style="">到</span>4<span style="">之间的正整数，表示各路径的方向标号，每两个数之间有空格。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style=";font-family:宋体">输出格式为</span>n<span style=";font-family:宋体">行，每行为英文单词“</span>Possible<span style=";font-family:宋体">”或“</span>Impossible<span style=";font-family:宋体">”，分别代表可能形成与不可能形成，首字母大写。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p><p>3</p><p>1 4 1</p><p>5</p><p>1 2 3 4 1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Possible</p><p>Impossible</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Times New Roman';">0</span><span style="">＜</span><span style="font-family: 'Times New Roman';">t</span><span style="">≤</span><span style="font-family: 'Times New Roman';">5</span><span style="">，</span><span style="font-family: 'Times New Roman';">0</span><span style="">＜</span><span style="font-family: 'Times New Roman';">n</span><span style="">≤</span><span style="font-family: 'Times New Roman';">50</span><span style="">。</span></p><p><span style="">样例中第一组数据的路径简图：</span></p><p><span style="">______</span></p><p><span style="">|\    /\   |</span></p><p><span style="">|_\/__\|</span></p><p><span style="">从左至右三条路径的方向标号依次为1-4-1</span></p>
</div>
</div>
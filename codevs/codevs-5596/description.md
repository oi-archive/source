<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">BY<span style="">J</span></span><span style="">发现一堆长短不一的木棍<span style="">。</span>由于它们太混乱<span style="">，</span></span><span style="">BY<span style="">J</span></span><span style="">打算截长补短<span style="">，</span>使这些木棍的长</span></p><p style=""><span style="">度相同。</span></p><p style=""><span style="">BY</span><span style="">J</span><span style="">计算出这些</span><span style="">木棍长度的平均<span style="">数</span>（设平均数<span style="">为</span></span><span style="">s</span><span style="">，</span><span style="">保<span style="">证</span></span><span style="">s</span><span style="">为正整数<span style="">）</span><span style="">，</span>接着将所有木棍放在面前，进行如下操作：</span></p><p style=""><span style="">1</span><span style="">、从面前的木棍中找出最长的一根（长度为</span> <span style="">max</span><span style="">）和</span><span style="">最短的一根（长度为</span> <span style="">min</span><span style="">）</span><span style="">；</span> <span style="">2</span><span style="">、如<span style="">果</span></span><span style="">max+min&gt;2s</span><span style="">，则<span style="">将</span></span><span style="">ma<span style="">x</span></span><span style="">截<span style="">为</span></span><span style="">max+min-s</span><span style="">，</span><span style="">mi<span style="">n</span></span><span style="">补<span style="">为</span></span><span style="">s</span><span style="">；</span></p><p style=""><span style="">3</span><span style="">、如<span style="">果</span></span><span style="">m</span><span style="">ax+</span><span style="">m</span><span style="">i<span style="">n&lt;2s</span></span><span style="">，则<span style="">将</span></span><span style="">m</span><span style="">a</span><span style="">x</span><span style="">截<span style="">为</span></span><span style="">s</span><span style="">，</span><span style="">m</span><span style="">i<span style="">n</span></span><span style="">补<span style="">为</span></span><span style="">m</span><span style="">a</span><span style="">x+<span style="">m</span>in<span style="">-</span>s</span><span style="">；</span></p><p style=""><span style="">4</span><span style="">、如<span style="">果</span></span><span style="">max+min=2s</span><span style="">，则<span style="">将</span></span><span style="">ma<span style="">x</span></span><span style="">截<span style="">为</span></span><span style="">s</span><span style="">，</span><span style="">mi<span style="">n</span></span><span style="">补<span style="">为</span></span><span style="">s</span><span style="">；</span></p><p style=""><span style="">5</span><span style="">、将当前长度<span style="">为</span></span><span style="">s</span><span style="">的木棍放到一边（即这些木棍不再进行操作<span style="">）</span>；</span></p><p style=""><span style="">6</span><span style="">、如果面前没有木棍，则停止，否则回<span style="">到</span></span><span style="">1</span><span style="">。</span></p><p style=""><span style="">每重复一次，步数就加一。</span><span style="">BYJ </span><span style="">想知道使所有木棍的长度都变<span style="">成</span></span><span style="">s</span><span style="">所需要的步数。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">//输入文件<span style="">为</span></span><span style="">cut.in</span><span style="">。</span></p><p style=""><span style="">第一行包含一个正整<span style="">数</span></span><span style="">N</span><span style="">，表示<span style="">有</span></span><span style="">N</span><span style="">根木棍。</span></p><p style=""><span style="">接下来<span style="">的</span></span><span style="">N</span><span style="">行，每行一个正整<span style="">数</span></span><span style="">L</span><span style="">，表示该木棍的长度<span style="">为</span></span><span style="">L</span><span style="">。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin: 3px 0 0 28px;line-height: 18px"><span style="font-size:14px;font-family:宋体">//输出文件<span style="letter-spacing:2px">为</span></span><span style="font-size:14px">cut.out</span><span style="font-size:14px;font-family:宋体">。</span></p><p style="margin: 3px 0 0 28px;line-height: 18px"><span style="font-size:14px;font-family:宋体">输出只有一行，包含一个正整数，表示使所有木棍的长度都变<span style="letter-spacing:2px">成</span></span><span style="font-size: 14px;letter-spacing:3px">s</span><span style="font-size:14px;font-family:宋体">所需要的步数。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Courier New';">6</span></p><p style=""><span style="font-family: 'Courier New';">2</span></p><p style=""><span style="font-family: 'Courier New';">9</span></p><p style=""><span style="font-family: 'Courier New';">1</span></p><p style=""><span style="font-family: 'Courier New';">6</span></p><p style=""><span style="font-family: 'Courier New';">4</span></p><p><span style="font-family: 'Courier New';">14</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">【输入输出样例说明】</span></p><p style=""><span style="">第</span><span style="">1</span><span style="">次：从<span style="">第</span></span><span style="">6</span><span style="">根木棍上截<span style="">取</span></span><span style="">5</span><span style="">个单位长度补到<span style="">第</span></span><span style="">3</span><span style="">根木棍上；</span></p><p style=""><span style="">第</span><span style="">2</span><span style="">次：从<span style="">第</span></span><span style="">6</span><span style="">根木棍上截<span style="">取</span></span><span style="">3</span><span style="">个单位长度补到<span style="">第</span></span><span style="">1</span><span style="">根木棍上；</span></p><p style=""><span style="">第</span><span style="">3</span><span style="">次：从<span style="">第</span></span><span style="">2</span><span style="">根木棍上截<span style="">取</span></span><span style="">1</span><span style="">个单位长度补到<span style="">第</span></span><span style="">1</span><span style="">根木棍上；</span></p><p style=""><span style="">第</span><span style="">4</span><span style="">次：从<span style="">第</span></span><span style="">2</span><span style="">根木棍上截<span style="">取</span></span><span style="">2</span><span style="">个单位长度补到<span style="">第</span></span><span style="">5</span><span style="">根木棍上。</span></p><p style=""><span style="">【数据范围】</span></p><p style=""><span style="">对<span style="">于</span></span><span style="">20%</span><span style="">的数据，</span><span style="">1<span style="text-decoration: underline;">&lt;</span>N<span style="text-decoration: underline;">&lt;</span>10</span><span style="">。</span></p><p style=""><span style="">对<span style="">于</span></span><span style="">100%</span><span style="">的数据，</span><span style="">1<span style="text-decoration: underline;">&lt;</span>N<span style="text-decoration: underline;">&lt;</span>1000</span><span style="">。</span></p><p><br></p>
</div>
</div>
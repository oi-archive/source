<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">X</span><span style="">C</span><span style="">找</span><span style="">来了一些小球<span style="">，</span>并把它们固定在桌上<span style="">。</span>由于这些小球的相对位置不同<span style="">，</span>有些小球</span></p><p style=""><span style="">之间可以用木棍连接，而有些则不行。</span></p><p style=""><span style="">如果小<span style="">球</span></span><span style="">x</span><span style="">连接了小<span style="">球</span></span><span style="">y</span><span style="">，小<span style="">球</span></span><span style="">y</span><span style="">连接了小<span style="">球</span></span><span style="">z</span><span style="">，则小<span style="">球</span></span><span style="">x</span><span style="">和小<span style="">球</span></span><span style="">z</span><span style="">也算连接在一起。</span><span style="">X</span><span style="">C</span><span style="">学</span><span style="">习过魔法<span style="">，</span>可以凭空变出木棍<span style="">，</span>所以他并不需要担心木棍不够用<span style="">。</span>但他还是打算</span></p><p style=""><span style="">用尽量短的木棍将所有小球连接在一起。</span></p><p style=""><span style="">X</span><span style="">C</span><span style="">觉</span><span style="">得</span><span style="">计</span><span style="">算</span><span style="">太</span><span style="">繁琐</span><span style="">，</span><span style="">于是</span><span style="">就</span><span style="">把</span><span style="">任</span><span style="">务</span><span style="">交</span><span style="">给</span><span style="">了</span><span style="">你</span><span style="">。</span><span style="">为了</span><span style="">减</span><span style="">少<span style="">你</span>的<span style="">工</span>作<span style="">量</span><span style="">，</span><span style="">他</span>向你<span style="">保</span>证<span style="">，</span><span style="">一</span> 定存在将所有小球连接在一起的方案。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行包含两个正整<span style="">数</span></span><span style="">N </span><span style="">和</span><span style="">M</span><span style="">，表示小球的个数<span style="">为</span></span><span style="">N</span><span style="">，<span style="">有</span></span><span style="">M</span><span style="">对小球之间可以连接。<span style="">接</span>下<span style="">来</span><span style="">的</span></span><span style="">M </span><span style="">行</span><span style="">，<span style="">每行</span>三个<span style="">正</span>整数 </span><span style="">a</span><span style="">、</span><span style="">b</span><span style="">和 </span><span style="">c</span><span style="">，表示 </span><span style="">a</span><span style="">号小球和 </span><span style="">b</span><span style="">号小球之间可以用长度</span></p><p style=""><span style="">为</span><span style="">c</span><span style="">的木棍连接。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin: 3px 0 0 28px;line-height: 18px"><span style="font-size:14px;font-family:宋体">输出只有一行，包含一个正整数，表示将所有小球连接在一起所需木棍的最短长度。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Courier New';">5 8</span></p><p style=""><span style="font-family: 'Courier New';">1<span style="font-family: 'Times New Roman';">  </span></span><span style="font-family: 'Courier New';">2 2</span></p><p style=""><span style="font-family: 'Courier New';">2<span style="font-family: 'Times New Roman';">  </span></span><span style="font-family: 'Courier New';">5 9</span></p><p style=""><span style="font-family: 'Courier New';">5 4 7</span></p><p style=""><span style="font-family: 'Courier New';">4 1 10</span></p><p style=""><span style="font-family: 'Courier New';">1<span style="font-family: 'Times New Roman';">  </span></span><span style="font-family: 'Courier New';">3 12</span></p><p style=""><span style="font-family: 'Courier New';">4<span style="font-family: 'Times New Roman';">  </span></span><span style="font-family: 'Courier New';">3 6</span></p><p style=""><span style="font-family: 'Courier New';">5<span style="font-family: 'Times New Roman';">  </span></span><span style="font-family: 'Courier New';">3 3</span></p><p><span style="font-family: 'Courier New';"> 2 3 8</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>19<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">【输入输出样例说明】</span></p><p style=""><span style="">连<span style="">接</span></span><span style="">1-2</span><span style="">、</span><span style="">2-3</span><span style="">、</span><span style="">3-4</span><span style="">、</span><span style="">3-5</span><span style="">，所需木棍的长度<span style="">为</span></span><span style="">19</span><span style="">。</span></p><p style=""><span style="">【数据范围】</span></p><p style=""><span style="">对<span style="">于</span></span><span style="">30%</span><span style="">的数据，</span><span style="">1<span style="text-decoration: underline;">&lt;</span>N, M<span style="text-decoration: underline;">&lt;</span>10</span><span style="">。</span></p><p style=""><span style="">对<span style="">于</span></span><span style="">70%</span><span style="">的数据，</span><span style="">1<span style="text-decoration: underline;">&lt;</span>N<span style="text-decoration: underline;">&lt;</span>500</span><span style="">，</span><span style="">1<span style="text-decoration: underline;">&lt;</span>M<span style="text-decoration: underline;">&lt;</span>1000</span><span style="">。</span></p><p style=""><span style="">对<span style="">于</span></span><span style="">100%</span><span style="">的数据，</span><span style="">1<span style="text-decoration: underline;">&lt;</span>N<span style="text-decoration: underline;">&lt;</span>10000</span><span style="">，</span><span style="">1<span style="text-decoration: underline;">&lt;</span>M<span style="text-decoration: underline;">&lt;</span>100000</span><span style="">。</span></p><p><br></p>
</div>
</div>
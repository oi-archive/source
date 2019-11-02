<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">几天前，</span><span style="">CJ<span style="">R</span></span><span style="">在桌上画了一条数轴。</span><span style="">X<span style="">C</span></span><span style="">突发奇想，打算用木棍来覆盖这条数轴。</span></p><p style=""><span style="">C</span><span style="">J</span><span style="">R</span><span style="">在</span><span style="">建</span><span style="">造</span><span style="">高</span><span style="">塔</span><span style="">的时</span><span style="">候就</span><span style="">已</span><span style="">经</span><span style="">测</span><span style="">量</span><span style="">出</span><span style="">了</span><span style="">每</span><span style="">一</span><span style="">根</span><span style="">木</span><span style="">棍<span style="">的</span>直<span style="">径</span>和<span style="">长</span>度<span style="">，</span>并<span style="">给每</span>一根<span style="">木</span>棍<span style="">都</span>标 上了号。将这些木棍按标号排好后，</span><span style="">BYJ </span><span style="">发现它们不能随意变换顺序。</span></p><p style=""><span style="">X</span><span style="">C</span><span style="">想</span><span style="">知道</span><span style="">，</span><span style="">最</span><span style="">多</span><span style="">能</span><span style="">将</span><span style="">多少</span><span style="">根</span><span style="">木</span><span style="">棍</span><span style="">不</span><span style="">重</span><span style="">复</span><span style="">不</span><span style="">间</span><span style="">断</span><span style="">地覆</span><span style="">盖</span><span style="">在</span><span style="">数</span><span style="">轴</span><span style="">上<span style="">。</span>为<span style="">了保</span>证美<span style="">观</span><span style="">，</span>相<span style="">邻</span> 木棍的直径差不能大<span style="">于</span></span><span style="">d</span><span style="">。</span><span style="">CJ<span style="">R</span></span><span style="">并不满足于此。在木棍最多时，他希望覆盖的长度最大。</span></p><p style=""><span style="">这时</span> <span style="">BYJ</span> <span style="">发现，在他脚边还有一根未标号的木棍。他决定将这根木棍插入到按标号排</span></p><p style=""><span style="">好的<span style="">木</span>棍<span style="">序</span>列<span style="">的</span>某<span style="">一</span>位<span style="">置</span><span style="">，</span><span style="">再</span>从<span style="">这</span>个<span style="">新</span>序列<span style="">中</span>选<span style="">取</span>尽量<span style="">多</span>的<span style="">木</span>棍<span style="">覆</span>盖<span style="">在</span>数<span style="">轴</span>上<span style="">。</span>当<span style="">然</span><span style="">，</span><span style="">必须</span>也要满足上述的要求。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行包含两个正整<span style="">数</span></span><span style="">N </span><span style="">和</span><span style="">d</span><span style="">，表示<span style="">有</span></span><span style="">N</span><span style="">根木棍，相邻木棍的直径差不能大<span style="">于</span></span><span style="">d</span><span style="">。</span></p><p style=""><span style="">接</span><span style="">下</span><span style="">来</span><span style="">的</span><span style="">N</span><span style="">行</span><span style="">，</span><span style="">每</span><span style="">行</span><span style="">两个</span><span style="">正整</span><span style="">数</span><span style="">D</span> <span style="">和</span><span style="">L</span><span style="">，</span><span style="">第</span><span style="">i</span><span style="">行的</span><span style="">两</span><span style="">个</span><span style="">整</span><span style="">数<span style="">表</span>示<span style="">标号</span><span style="">为</span></span><span style="">i</span><span style="">-</span><span style="">1</span><span style="">的木棍<span style="">直径</span> <span style="">为</span></span><span style="">D</span><span style="">，长度<span style="">为</span></span><span style="">L</span><span style="">。</span></p><p style=""><span style="">最后一行包含一个正整<span style="">数</span></span><span style="">D</span><span style="">x</span><span style="">，表示未标号的木棍直径<span style="">为</span></span><span style="">D</span><span style="">x</span><span style="">。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin: 3px 0 0 28px;line-height: 18px"><span style="font-size:14px;font-family:宋体">第一行包含一个正整数，表示原来覆盖数轴的木棍最多能有多少根。</span></p><p style="margin-top:1px;margin-right:36px;margin-bottom: 0;margin-left:28px;margin-bottom:0;line-height:21px;text-autospace:none"><span style="font-size:14px;font-family:宋体;letter-spacing: -0">第</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">二</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">行</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">包</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">含</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">一</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">个</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">正</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">整</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">数，</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">表</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">示</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">原</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">来</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">覆</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">盖</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">数</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">轴</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">的</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">木棍</span><span style="font-size:14px;font-family:宋体;letter-spacing:-0">最</span><span style="font-size:14px;font-family:宋体">多<span style="letter-spacing: -0">时</span>，<span style="letter-spacing:-0">覆</span>盖<span style="letter-spacing:-0">长</span>度<span style="letter-spacing:-0">的</span>最大<span style="letter-spacing:-0">值。</span> 第三行包含一个正整数，表示现在覆盖数轴的木棍最多能有多少根。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Courier New';">6 2</span></p><p style=""><span style="font-family: 'Courier New';">2 5</span></p><p style=""><span style="font-family: 'Courier New';">6 3</span></p><p style=""><span style="font-family: 'Courier New';">5<span style="font-family: 'Times New Roman';">  </span></span><span style="font-family: 'Courier New';">2</span></p><p style=""><span style="font-family: 'Courier New';">1<span style="font-family: 'Times New Roman';">  </span></span><span style="font-family: 'Courier New';">4</span></p><p style=""><span style="font-family: 'Courier New';">2<span style="font-family: 'Times New Roman';">  </span></span><span style="font-family: 'Courier New';">4</span></p><p style=""><span style="font-family: 'Courier New';">1 1</span></p><p><span style="font-family: 'Courier New';"> 3</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p><p>14</p><p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">【输入输出样例说明】</span></p><p style=""><span style="">原</span><span style="">来</span><span style="">选</span><span style="">择</span><span style="">第</span> <span style="">1</span><span style="">、</span><span style="">4</span><span style="">、</span><span style="">5</span><span style="">、</span><span style="">6</span> <span style="">根</span><span style="">木</span><span style="">棍</span><span style="">，</span><span style="">覆</span><span style="">盖</span><span style="">长</span><span style="">度</span><span style="">为</span> <span style="">1</span><span style="">4</span><span style="">。<span style="">现</span>在<span style="">将</span>未<span style="">标</span>号<span style="">的</span>木<span style="">棍插</span>在<span style="">第</span> </span><span style="">3</span><span style="">、</span><span style="">4 </span><span style="">根</span><span style=""> 木棍之间，选择<span style="">第</span></span><span style="">2</span><span style="">、</span><span style="">3</span><span style="">、</span><span style="">4</span><span style="">、</span><span style="">5</span><span style="">、</span><span style="">6</span><span style="">、</span><span style="">7</span><span style="">根木棍。</span></p><p style=""><span style="">【数据范围】</span></p><p style=""><span style="">对<span style="">于</span></span><span style="">30%</span><span style="">的数据，</span><span style="">1<span style="text-decoration: underline;">&lt;</span>N<span style="text-decoration: underline;">&lt;</span>10</span><span style="">，</span><span style="">0<span style="text-decoration: underline;">&lt;</span>d<span style="text-decoration: underline;">&lt;</span>10</span><span style="">，</span><span style="">1<span style="text-decoration: underline;">&lt;</span>D, D</span><span style="">x</span><span style="text-decoration: underline;"><span style="">&lt;</span></span><span style="">50</span><span style="">。</span></p><p style=""><span style="">对<span style="">于</span></span><span style="">100%</span><span style="">的数据，</span><span style="">1<span style="text-decoration: underline;">&lt;</span>N<span style="text-decoration: underline;">&lt;</span>1000</span><span style="">，</span><span style="">0<span style="text-decoration: underline;">&lt;</span>d<span style="text-decoration: underline;">&lt;</span>1000</span><span style="">，</span><span style="">1<span style="text-decoration: underline;">&lt;</span>D, D</span><span style="">x</span><span style="text-decoration: underline;"><span style="">&lt;</span></span><span style="">10000</span><span style="">。</span></p><p><br></p>
</div>
</div>
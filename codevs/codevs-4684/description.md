<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">    有一天，一位叫做QZZ的</span><span style="">蒟蒻</span><span style="">看到了自己出的第一道题（见4386<span style=""><em>【QZZ】HQY的蛋 </em></span>），心想：“实在是太水了，我怎么可能出了这么水的题。”于是乎，就有了这道相比起来不太water的题：<span style=""><em>【QZZ】CXK </em></span>出题。</span></p><p><span style="">    PS1：题目is so easy，就是简单的递推</span><span style="">（至少看上去是这样）</span><span style="">，</span><span style="">请大神们随意AC;</span></p><p><span style="">    PS2：题目绝对没坑点</span><span style="">（有坑点又怎样）</span><span style="">；</span></p><p><span style="">    PS3：请大神们在AC此题后，不要在题解里发完整程序，本人最不喜欢什么抄题解了</span><span style="">（虽然我偶尔也抄一抄）</span><span style="">；</span></p><p><span style=""><br></span></p><p><span style="">============================================================下面进入正题============================================================</span></p><p><br></p><p><span style="">    CXK在出一道叫做</span><span style=""><em>【HY】HY真正的打篮球 </em></span><span style="">的题。可是，他出题后发现怎么都AC不了，只能请教HR神犇，但是HR平时是很忙的（他去干什么了呢？请搜索<span style=""><em>【HR】</em></span>系列）。于是，他就只能不断地继续尝试。突然，天象异常，北极星落到了南方，刚刚还是万里无云的天上突然打了几响震雷，鹅毛大雪飘了起来，却马上被CXK强大的气场震碎，机房里的所有人都感受到了一种强大的压迫感，CXK的头上却发出了智慧的光芒。气场逐渐旋转，越转越快，掀起了一场100级的暴风，电线被扯断，大树被连根拔起，整个机房分崩离析，CXK发出的光芒却照亮了整个世界，远远望去，就像是上帝在人间与天堂之间架起的阶梯，闪着金色的光辉。欲知后事如何，<strong>下回没有分解。</strong></span></p><p><span style=""><br></span></p><p><span style="">=========================================================下面才是真正的正题=========================================================</span></p><p><span style=""><br></span></p><p><span style="">    CXK发现，如果用k来表示他提交的次数，AC的测试点个数就会存在一些规律（这里用</span><span style="">a</span><sub><span style="">k</span></sub><span style="">表示第k次AC的测试点个数）:</span></p><p><span style="">    1、a<sub>0</sub>=0；（不提交怎么会AC呢？）</span></p><p><span style="">    2、如果k可以表示为i*2的形式，则a<sub>k</sub>=a<sub>i</sub>+2；(k&gt;=2)</span></p><p><span style="">    3、如果k可以表示为i*2+1的形式，则a<sub>k</sub>=a<sub>i</sub>*2；(k&gt;=1)</span></p><p><span style="">   （是不是很神奇）</span></p><p><span style="">    CXK在题目中设置了n个测试点，他想知道，在第s次提交之时，他能不能AC这道题？</span><span style="">（如果不能，CXK就只能去找</span><span style="">泡妞泡到正在兴头上的</span><span style="">HR神犇了）</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入共两行：</p><p>    第一行一个整数n，代表测试点的总数；</p><p>    第二行一个整数s，代表提交的次数；</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; 输出共一行：</p><p>&nbsp; &nbsp; 如果第s次提交时CXK能AC这道题，则输出一个正整数“YeS”；否则输出这时他能AC的测试点的个数；</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>测试数据1：</p><p>19</p><p>19</p><p><br></p><p>测试数据2：</p><p>2</p><p>12</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1：</p><p>16</p><p><br></p><p>2：</p><p>YeS</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>    对于10%的数据，n，k&lt;=100；</p><p>    对于40%的数据，n，k&lt;10<sup>9</sup>；</p><p>    对于100%的数据，n，k&lt;10<sup>1000</sup>；</p><p><br></p>
</div>
</div>
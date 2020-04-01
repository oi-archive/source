<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><br></p><p style="">新历<span style="font-family: Courier New, monospace;">5371</span>年，教会圈养人类掠夺资源供养原罪的行为败露。在圣域法师安德鲁带领下，第一次屠神之战开始。作为奥术学院的院长，传奇法师<span style="font-family: Courier New, monospace;">YYK</span>自然也加入了这场旷世大战。在奥术的日常修行中，<span style="font-family: Courier New, monospace;">YYK</span>打造出了一件传奇级的奥术装备<span style="font-family: Courier New, monospace;">--</span>续秒之书，在战争开始前，<span style="font-family: Courier New, monospace;"></span><span style="font-family: Courier New, monospace;">YYK</span>可以消耗<span style="font-family: Courier New, monospace;">m</span>的魔力，在书中先写入<span style="font-family: Courier New, monospace;">m</span>个魔法。在战斗过程中，<span style="font-family: Courier New, monospace;">YYK</span>可以做出三种操作：</p><ol><li><p style="">续：花费<span style="font-family: Courier New, monospace;">1</span>个单位的魔力，在书的最后写入一个魔法。</p></li><li><p style=""><span style="font-family: Courier New, monospace;">ddf</span>：不花费任何魔力释放书中的最后一个魔法。</p></li><li><p style=""><span style="font-family: Courier New, monospace;">Delete</span>：不花费任何魔力，删去书中的最后一个魔法。</p></li></ol><p style="">有一件如此的神器，<span style="font-family: Courier New, monospace;"><span style="font-family: Courier New, monospace;">YYK</span></span>自然所向披靡，但不久之后他犯了难，由于穿梭位面需要大量魔力，他只能在一个位面消耗至多<span style="font-family: Courier New, monospace;">x</span>的魔力，但由于战斗太水，他懒得计算最少需要消耗多少的魔力，这导致他常常无法及时前往另一个位面。作为一位大奥术师兼传奇法师，有许多位面等着<span style="font-family: Courier New, monospace;"></span><span style="font-family: Courier New, monospace;">YYK</span>去拯救，他没时间在穿越前就处理好每一次消耗的最小魔力，即使他有能预知使用哪几个魔法的能力。</p><p style="">现在，他将这种能力传授给了你，希望你能帮他计算出他所要消耗的最小魔力<span style="font-family: Times New Roman, serif;"><span style="font-family: Courier New, monospace;">n</span></span>，如果大于<span style="font-family: Times New Roman, serif;"><span style="font-family: Courier New, monospace;">x</span></span>则输出<span style="font-family: Courier New, monospace;">”</span><span style="font-family: Times New Roman, serif;"><span style="font-family: Courier New, monospace;">NO,Sir!</span><span style="font-family: Courier New, monospace;">”</span></span>否则输出<span style="font-family: Times New Roman, serif;"><span style="font-family: Courier New, monospace;">n</span></span>。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><br></p><p style="">输入<span style="font-family: Times New Roman, serif;"><span style="font-family: Courier New, monospace;"></span></span>有<span style="font-family: Times New Roman, serif;"><span style="font-family: Courier New, monospace;">2</span></span>行，第<span style="font-family: Times New Roman, serif;"><span style="font-family: Courier New, monospace;">1</span></span>行为<span style="font-family: Times New Roman, serif;"><span style="font-family: Courier New, monospace;">2</span></span>个正整数，用一个空格隔开：</p><p style=""><span style="font-family: Times New Roman, serif;">a x</span></p><p style=""><span style="">（其中</span><span style="font-family: Times New Roman, serif;"><span style="">a</span>为你获得<span style="font-family: Times New Roman, serif;">YYK</span>将释放的魔法的数量，<span style="font-family: Times New Roman, serif;">x</span>为<span style="font-family: Times New Roman, serif;">YYK</span>最多消耗的魔力，<span style="font-family: Times New Roman, serif;">a&lt;=400</span></span>）</p><p style="">第<span style="font-family: Times New Roman, serif;"><span style="font-family: Courier New, monospace;">2</span></span>行为<span style="font-family: Times New Roman, serif;"><span style="font-family: Courier New, monospace;">a</span></span>个整数，表示<span style="font-family: Times New Roman, serif;"><span style="font-family: Courier New, monospace;">YYK</span></span>依次要施放出的魔法的编号</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><br/></p><p style="margin-bottom: 0;line-height: 16px">输出<span style="font-family:Courier New, monospace"></span>包括<span style="font-family:Courier New, monospace">1</span>行，描述如上</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><br></p><p style="">样例<span style="font-family: Times New Roman, serif;"><span style="font-family: Courier New, monospace;">1</span></span></p><p style=""><span style="font-family: Times New Roman, serif;"><span style="font-family: Courier New, monospace;">4</span><span style="font-family: Courier New, monospace;"> 4</span></span></p><p style=""><span style="font-family: Courier New, monospace;">1 2 1 2</span></p><p style=""><span style="font-family: Courier New, monospace;">样例2<br></span></p><p style=""><span style="font-family: Times New Roman, serif;"><span style="font-family: Courier New, monospace;">7</span><span style="font-family: Courier New, monospace;"> 3</span></span></p><p style=""><span style="font-family: Courier New, monospace;">1 2 1 1 3 2 1</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><br></p><p style="">样例<span style="font-family: Times New Roman, serif;"><span style="font-family: Courier New, monospace;">1</span></span></p><p style=""><span style="font-family: Courier New, monospace;">3</span></p><p>样例2<br></p><p style=""><span style="font-family: Courier New, monospace;">NO,Sir!</span></p><p style=""><span style="font-family: Courier New, monospace;"><br></span><br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>如上</p><p>%%%YYK<br></p>
</div>
</div>
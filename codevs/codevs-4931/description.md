<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style=""><strong><span style="">李昊</span></strong></span><span style="">博士是 BT (Bio-Tech,生物技术) 领域的知名专家,他的儿子名叫<span style=""><strong>沈中海</strong></span>。现在,刚刚放学回家的 <strong style="">沈中海</strong> 正在思考一个有趣的问题。 今天在课堂上,老师讲解了如何求两个正整数 c1 和 c2 的最大公约数和最小公倍数。现在<strong><span style="">沈中海</span></strong>认为自己已经熟练地掌握了这些知识,他开始思考一个“求公约数”和“求公 倍数”之类问题的“逆问题”,这个问题是这样的:已知正整数 a0,a1,b0,b1,设某未知正整 数x满足:</span></p><p><span style="">1</span><span style="">. </span><span style="">x </span><span style="">和 </span><span style="">a0 </span><span style="">的最大公约数是 </span><span style="">a1</span><span style="">;<br></span><span style="">2</span><span style="">. </span><span style="">x </span><span style="">和 </span><span style="">b0 </span><span style="">的最小公倍数是 </span><span style="">b1</span><span style="">。<br></span><span style=""><strong style="">沈中海</strong></span><span style="">的“逆问题”就是求出满足条件的正整数 </span><span style="">x</span><span style="">。但稍加思索之后,他发现这样的</span><span style="">x</span><span style="">并不唯一,甚至可能不存在。因此他转而开始考虑如何求解满足条件的 </span><span style="">x </span><span style="">的个数。请你帮 助他编程求解这个问题。 </span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Times New Roman';">第一行为一个正整数 </span><span style="font-family: 'Times New Roman';">n</span><span style="font-family: 'Times New Roman';">,表示有 </span><span style="font-family: 'Times New Roman';">n </span><span style="font-family: 'Times New Roman';">组输入数据。接下来的 </span><span style="font-family: 'Times New Roman';">n </span><span style="font-family: 'Times New Roman';">行每</span><span style="font-family: 'Times New Roman';">行一组输入数据,为四个正整数 </span><span style="font-family: 'Times New Roman';">a0</span><span style="font-family: 'Times New Roman';">,</span><span style="font-family: 'Times New Roman';">a1</span><span style="font-family: 'Times New Roman';">,</span><span style="font-family: 'Times New Roman';">b0</span><span style="font-family: 'Times New Roman';">,</span><span style="font-family: 'Times New Roman';">b1</span><span style="font-family: 'Times New Roman';">,每两个整数之间用一个空格隔开。输入 数据保证 </span><span style="font-family: 'Times New Roman';">a0 </span><span style="font-family: 'Times New Roman';">能被 </span><span style="font-family: 'Times New Roman';">a1 </span><span style="font-family: 'Times New Roman';">整除,</span><span style="font-family: 'Times New Roman';">b1 </span><span style="font-family: 'Times New Roman';">能被 </span><span style="font-family: 'Times New Roman';">b0 </span><span style="font-family: 'Times New Roman';">整除。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Times New Roman&#39;; line-height: 24px; font-size: 11pt; background-color: rgb(228, 240, 248);">共&nbsp;</span><span style="color: rgb(51, 51, 51); font-family: &#39;Times New Roman&#39;; line-height: 24px; font-size: 11pt; background-color: rgb(228, 240, 248);">n&nbsp;</span><span style="color: rgb(51, 51, 51); font-family: &#39;Times New Roman&#39;; line-height: 24px; font-size: 11pt; background-color: rgb(228, 240, 248);">行。每组输入数据的输出结果占一行,为一个整数。 对于每组数据:若不存在这样的&nbsp;</span><span style="color: rgb(51, 51, 51); font-family: &#39;Times New Roman&#39;; line-height: 24px; font-size: 11pt; background-color: rgb(228, 240, 248);">x</span><span style="color: rgb(51, 51, 51); font-family: &#39;Times New Roman&#39;; line-height: 24px; font-size: 11pt; background-color: rgb(228, 240, 248);">,请输出&nbsp;</span><span style="color: rgb(51, 51, 51); font-family: &#39;Times New Roman&#39;; line-height: 24px; font-size: 11pt; background-color: rgb(228, 240, 248);">0</span><span style="color: rgb(51, 51, 51); font-family: &#39;Times New Roman&#39;; line-height: 24px; font-size: 11pt; background-color: rgb(228, 240, 248);">;<br/>若存在这样的&nbsp;</span><span style="color: rgb(51, 51, 51); font-family: &#39;Times New Roman&#39;; line-height: 24px; font-size: 11pt; background-color: rgb(228, 240, 248);">x</span><span style="color: rgb(51, 51, 51); font-family: &#39;Times New Roman&#39;; line-height: 24px; font-size: 11pt; background-color: rgb(228, 240, 248);">,请输出满足条件的&nbsp;</span><span style="color: rgb(51, 51, 51); font-family: &#39;Times New Roman&#39;; line-height: 24px; font-size: 11pt; background-color: rgb(228, 240, 248);">x&nbsp;</span><span style="color: rgb(51, 51, 51); font-family: &#39;Times New Roman&#39;; line-height: 24px; font-size: 11pt; background-color: rgb(228, 240, 248);">的个数;&nbsp;</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: monospace;">2</span><br></p><p><span style="font-family: monospace;">41 1 96 288</span></p><p><span style="font-family: monospace;">95 1 37 1776</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p><p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">【说明】<br><br>第一组输入数据,</span><span style="">x </span><span style="">可以是 </span><span style="">9</span><span style="">、</span><span style="">18</span><span style="">、</span><span style="">36</span><span style="">、</span><span style="">72</span><span style="">、</span><span style="">144</span><span style="">、</span><span style="">288</span><span style="">,共有 </span><span style="">6 </span><span style="">个。 第二组输入数据,</span><span style="">x </span><span style="">可以是 </span><span style="">48</span><span style="">、</span><span style="">1776</span><span style="">,共有 </span><span style="">2 </span><span style="">个。</span></p><p><br style="font-family: 'Times New Roman';"></p><p><span style="">【数据范围】<br><br>对于 </span><span style="">50%</span><span style="">的数据,保证有 </span><span style="">1</span><span style="">≤</span><span style="">a0</span><span style="">,</span><span style="">a1</span><span style="">,</span><span style="">b0</span><span style="">,</span><span style="">b1</span><span style="">≤2</span><span style="">0000 </span><span style="">且 </span><span style="">n</span><span style="">≤2</span><span style="">00</span><span style="">。<br><br>对于 </span><span style="">100%</span><span style="">的数据,保证有 </span><span style="">1</span><span style="">≤</span><span style="">a0</span><span style="">,</span><span style="">a1</span><span style="">,</span><span style="">b0</span><span style="">,</span><span style="">b1</span><span style="">≤3</span><span style="">,000,000,000 </span><span style="">且 </span><span style="">n</span><span style="">≤3</span><span style="">000</span><span style="">。 </span></p><p><br></p>
</div>
</div>
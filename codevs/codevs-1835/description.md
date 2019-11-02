<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>iPig<span style="">在假期来到了传说中的魔法猪学院，开始为期两个月的魔法猪训练。经过了一周理论知识和一周基本魔法的学习之后，</span><span style="font-family: 'Times New Roman';">iPig</span><span style="">对猪世界的世界本原有了很多的了解：众所周知，世界是由元素构成的；元素与元素之间可以互相转换；能量守恒</span><span style="font-family: 'Times New Roman';">……</span><span style="">。</span></p>
<p> </p>
<p>能量守恒<span style="font-family: 'Times New Roman';">……iPig </span><span style="">今天就在进行一个麻烦的测验。</span><span style="font-family: 'Times New Roman';">iPig </span><span style="">在之前的学习中已经知道了很多种元素，并学会了可以转化这些元素的魔法，每种魔法需要消耗 </span><span style="font-family: 'Times New Roman';">iPig </span><span style="">一定的能量。作为 </span><span style="font-family: 'Times New Roman';">PKU </span><span style="">的顶尖学猪，让 </span><span style="font-family: 'Times New Roman';">iPig </span><span style="">用最少的能量完成从一种元素转换到另一种元素</span><span style="font-family: 'Times New Roman';">……</span><span style="">等等，</span><span style="font-family: 'Times New Roman';">iPig </span><span style="">的魔法导猪可没这么笨！这一次，他给 </span><span style="font-family: 'Times New Roman';">iPig </span><span style="">带来了很多 </span><span style="font-family: 'Times New Roman';">1 </span><span style="">号元素的样本，要求 </span><span style="font-family: 'Times New Roman';">iPig </span><span style="">使用学习过的魔法将它们一个个转化为 </span><span style="font-family: 'Times New Roman';">N </span><span style="">号元素，为了增加难度，要求</span>每份样本的转换过程都不相同。这个看似困难的任务实际上对 <span style="font-family: 'Times New Roman';">iPig </span><span style="">并没有挑战性，因为，他有坚实的后盾</span><span style="font-family: 'Times New Roman';">……</span><span style="">现在的你呀！</span></p>
<p> </p>
<p>注意，两个元素之间的转化可能有多种魔法，转化是单向的。转化的过程中，可以转化到一个元素（包括开始元素）多次，但是一但转化到目标元素，则一份样本的转化过程结束。<span style="font-family: 'Times New Roman';">iPig </span><span style="">的总能量是有限的，所以最多能够转换的样本数一定是一个有限数。具体请参看样例。</span></p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行三个数 <span>N</span><span>、</span><span>M</span><span>、</span><span>E </span><span>表示</span><span>iPig</span><span>知道的元素个数（元素从 </span><span>1 </span><span>到 </span><span>N </span><span>编号）、</span><span>iPig</span><span>已经学会的魔法个数和</span><span>iPig</span><span>的总能量。</span></p>
<p>后跟 <span>M </span><span>行每行三个数 </span><span>s</span>i、<span>t</span>i、<span>e</span>i 表示 <span>iPig </span><span>知道一种魔法，消耗 </span><span>e</span>i 的能量将元素 <span>s</span>i 变换到元素 <span>t</span>i 。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一行一个数，表示最多可以完成的方式数。输入数据保证至少可以完成一种方式。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 6 14.9</p>
<p>1 2 1.5</p>
<p>2 1 1.5</p>
<p>1 3 3</p>
<p>2 3 1.5</p>
<p>3 4 1.5</p>
<p>1 4 1.5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例解释</p>
<p>有意义的转换方式共<span style="font-family: 'Times New Roman';">4</span><span style="">种：</span></p>
<p>1-&gt;4<span style="">，消耗能量 </span><span style="font-family: 'Times New Roman';">1.5</span></p>
<p>1-&gt;2-&gt;1-&gt;4<span style="">，消耗能量 </span><span style="font-family: 'Times New Roman';">4.5</span></p>
<p>1-&gt;3-&gt;4<span style="">，消耗能量 </span><span style="font-family: 'Times New Roman';">4.5</span></p>
<p>1-&gt;2-&gt;3-&gt;4<span style="">，消耗能量 </span><span style="font-family: 'Times New Roman';">4.5</span></p>
<p>显然最多只能完成其中的<span style="font-family: 'Times New Roman';">3</span><span style="">种转换方式（选第一种方式，后三种方式仍选两个），即最多可以转换</span><span style="font-family: 'Times New Roman';">3</span><span style="">份样本。</span></p>
<p>如果将 <span style="font-family: 'Times New Roman';">E=14.9 </span><span style="">改为 </span><span style="font-family: 'Times New Roman';">E=15</span><span style="">，则可以完成以上全部方式，答案变为 </span><span style="font-family: 'Times New Roman';">4</span><span style="">。</span></p>
<p> </p>
<p>数据规模</p>
<p>占总分不小于 <span style="font-family: 'Times New Roman';">10% </span><span style="">的数据满足 </span><span style="font-family: 'Times New Roman';">N &lt;= 6</span><span style="">，</span><span style="font-family: 'Times New Roman';">M&lt;=15</span><span style="">。</span></p>
<p>占总分不小于 <span style="font-family: 'Times New Roman';">20% </span><span style="">的数据满足 </span><span style="font-family: 'Times New Roman';">N &lt;= 100</span><span style="">，</span><span style="font-family: 'Times New Roman';">M&lt;=300</span><span style="">，</span><span style="font-family: 'Times New Roman';">E&lt;=100</span><span style="">且</span><span style="font-family: 'Times New Roman';">E</span>和所有的<span style="font-family: 'Times New Roman';">e</span>i均为整数（可以直接作为整型数字读入）。</p>
<p>所有数据满足 <span style="font-family: 'Times New Roman';">2 &lt;= N &lt;= 5000</span><span style="">，</span><span style="font-family: 'Times New Roman';">1 &lt;= M &lt;= 200000</span><span style="">，</span><span style="font-family: 'Times New Roman';">1&lt;=E&lt;=10</span>7，<span style="font-family: 'Times New Roman';">1&lt;=e</span>i&lt;=E，E和所有的ei为实数。</p>
</div>
</div>
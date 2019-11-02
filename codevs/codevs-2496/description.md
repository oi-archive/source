<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　忘川沧月是一名Oier，他的家族有n个人。每年，当这n个人过生日的时候，忘川沧月都要去给他们买蜡烛。</span><br><span>　　不过最近忘川沧月却很纠结……因为他爷爷要过68岁生日了，他认为买68根蜡烛简直就是一件**的事情。。。</span><br><span>　　这天，忘川沧月路过了一个蜡烛商店……</span></p>
<p><span>　　<span>蜡烛商店中有10种蜡烛，形状分别是0~9这10个数字，不过对于每种蜡烛，商店的存货量仅有一根。另外，忘川沧月已经有了一个"+"形状的蜡烛。</span><br><span>　　忘川沧月想购买一些蜡烛，使得他的家族中所有人的年龄都可以用他购买的数字和"+"表示出来。</span><br><span>　　例如12就有11种表示方法：12、0+12、2+10、3+9、4+8、5+7、7+5、8+4、9+3、10+2、12+0。注意6+6、1+11、11+1是不行的，因为每种蜡烛仅有一根。</span><br><span>　　但是由于这种蜡烛很贵，忘川沧月想购买尽量少的蜡烛来达到他的目的，你能帮帮他吗？</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　本题共有5个测试点，每个测试点包含不多于10000组数据。</span><br><span>　　每组数据包含n+1个用空格隔开的整数，其中第一个整数n是家族成员的数量，接下来n个整数是他们的年龄。</span><br><span>　　n=0表示输入的结束。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　设需要购买的蜡烛数字从大到小排列构成了一个整数T，如果在购买最少数量的蜡烛的前提下，答案不唯一，请输出T最大的答案。</span><br /><span>　　对于每组数据，按照样例输出的格式，先输出数据编号，再输出T。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 10 11<br>1 30</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Case 1: 654<br>Case 2: 30</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>　　对于100%的数据，1&lt;=n&lt;=10,每个人的年龄是不大于100的正整数</span><br><span>　　对于测试点1~2，数据组数不超过100</span><br><span>　　对于测试点3，数据组数不超过1000</span><br><span>　　对于测试点4~5，数据组数不超过10000</span></p>
<p><span><br></span></p>
<p>来源：Nescafe 22</p>
</div>
</div>
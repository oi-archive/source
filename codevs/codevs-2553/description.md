<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>你在一个跨国公司负责发工资，每个工人的工资以自己本国货币结算。如果你手头上有足够的该国货币，你就直接发给他；如果没有足够的该国货币，他也不介意收到其他种类的货币，前提是按兑换关系他没有少拿就可以了。例如，有六种货币：A,B,C,D,E,F，你知道这些货币的兑换关系是：</p>
<p>23 A= 17 B</p>
<p>16 C= 29 E</p>
<p>5 B = 14 E</p>
<p>1 D =7 F</p>
<p>假如有个工人过来领100 A，而你手头正好没这么多A货币，你可以考虑替换成74 B（相当于100.12 A）、115 C（相当于100.72 A）或207 E（相当于100.02 A）。你应该支付207 E，因为这最接近这个工人应得的工资。</p>
<p>注意根据以上的兑换关系，你无法推断货币A与D、A与F的兑换关系。</p>
<p>由于钱仓空间有限，每种货币你最多只能持有100000，因此你无法用E货币支付64000 A，但用73078 C来支付是允许的。</p>
<p>假设工人领工资时，你正好没有结算的货币了，但其他货币的钱仓都是满的。你需要写一个程序帮你计算该怎样支付这个工人的工资。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行是一个整数n，接下来的n行，每行有两种不同货币的兑换关系，形如：</p>
<p>val1 name1 = val2 name2</p>
<p>name1和name2分别是货币名，val 1和val 2是&lt;=30的正整数，货币种类不超过8个，货币名由不超过10个字母组成。</p>
<p>兑换关系不存在类似1A= 2B，1B =2C，1C=2A这种矛盾的情况。</p>
<p>紧接着有一行形如val name，代表工资额和结算的货币（val不超过100000）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出形式为val name，val和name之间用一个空格分隔，分别代表支付的工资额及相应的货币。每个测试数据保证有唯一解。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1</p>
<p>4</p>
<p>23 A= 17 B</p>
<p>16 C= 29 E</p>
<p>5 B = 14 E</p>
<p>1 D =7 F</p>
<p>100 A</p>
<p> </p>
<p>样例2</p>
<p>1</p>
<p>1 USD = 2 RMB</p>
<p>40 RMB</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1</p>
<p>207 E</p>
<p> </p>
<p>样例2</p>
<p>20 USD</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=10</p>
<p> </p>
<p>广州市队选拔赛</p>
</div>
</div>
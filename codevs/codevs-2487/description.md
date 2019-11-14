<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　吃过草莓刨冰之后，Vani和cl有些疲倦地坐在一个长椅上。 <br>　　“呐，玩得开心吗？”Vani忽然问道。 <br>　　“嗯……很，很开心的说。” <br>　　“那么，我有一个问题想要问你呢。” <br>　　cl的脸有点红了起来。 <br>　　“嗯……好吧。问、问吧……我会告诉你的哦……” <br>　　“那好。对于一个分数A / B……” <br>　　“嗯……哎？哎？！” <br>　　“……就是这个问题。我觉得这个问题好纠结啊……” <br>　　Vani淡定地说完这句话。 <br>　　“啊？！哈啊？！” <br> <br>　　对于给定的分数 A / B，求其在 K 进制下是有限小数还是循环小数。如果是有限小数，求小数点后的位数；如果是循环小数，则求混循环部分和循环节的长度又分别是多少。 <br>　　注意，循环节指的是最短循环节，且混循环部分的长度也指最短。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　第一行一个正整数 T，表示测试数据的数目。 <br>　　每个测试数据包含三个空格分隔的整数 A, B, K。含义如题目所示。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　对于每个测试数据，在单独的一行内输出两个空格分隔的整数 M, R。 <br />　　其中 M 表示混循环部分的长度，R 表示循环节的长度。 <br />　　如果 A / B 在 K 进制下是有限小数，则 R = 0，M 为小数点后面的位数；如果 A / B 在 K 进制下是纯循环小数，则 M = 0。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 <br>1 8 10 <br>17 99 10 <br>217 990 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3 0 <br>0 2 <br>1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围与约定 <br>　　对于 50% 的数据，B≤100000。 <br>　　对于 100% 的数据，1≤A&lt;B≤10<sup>12</sup>，K≤10<sup>12</sup>，T≤10。</p>
<p>来源：Nescafe 18</p>
</div>
</div>
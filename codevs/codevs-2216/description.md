<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>“神州“载人飞船的发射成功让小可可非常激动，他立志长大后要成为一名宇航员假期一始，他就报名参加了“小小宇航员夏令营”，在这里小可可不仅学到了丰富的宇航知识，还参与解决了一些模拟飞行中发现的问题，今天指导老师交给他一个任务，在这次模拟飞行的路线上有N个行星，暂且称它们为一个行星序列，并将他们从1至n标号，在宇宙未知力量的作用下这N个行星的质量是不断变化的，所以他们对飞船产生的引力也会不断变化，小可可的任务就是在飞行途中计算这个行星序列中某段行星的质量和，以便能及时修正飞船的飞行线路，最终到达目的地，行星序列质量变化有两种形式：</p>
<p>1，行星序列中某一段行星的质量全部乘以一个值</p>
<p>2，行星序列中某一段行星的质量全部加上一个值</p>
<p>由于行星的质量和很大，所以求出某段行星的质量和后只要输出这个值模P的结果即可，小可可被这个任务难住了，聪明的你能够帮他完成这个任务吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数N和P（1&lt;=p&lt;=1000000000）；</p>
<p>  第二行含有N个非负整数，从左到右依次为a1，a2，…………，an（0&lt;=ai&lt;=100000000，1&lt;=i&lt;=n），其中ai表示第i个行星的质量：</p>
<p>  第三行有一个整数m，表示模拟行星质量变化以及求质量和等操作的总次数。从第四行开始每行描述一个操作，输入的操作有以下三种形式：</p>
<p>   操作1：1 t g c 表示把所有满足t&lt;=i&lt;=g的行星质量ai改为ai*c</p>
<p>   操作2：2 t g c 表示把所有满足t&lt;=i&lt;=g的行星质量ai改为ai+c</p>
<p>   操作3：3 t g 表示输出所有满足t&lt;=i&lt;=g的ai的和模p的值</p>
<p>   其中：1&lt;=t&lt;=g&lt;=N，0&lt;=c&lt;=10000000</p>
<p>   注：同一行相邻的两数之间用一个空格隔开，每行开头和末尾没有多余空格</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>对每个操作3，按照它在输入中出现的顺序，依次一行输出一个整数表示所求行星质量和</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>7 43
1 2 3 4 5 6 7
5
1 2 5 5
3 2 4
2 3 7 9
3 1 3
3 4 7</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>2
35
8</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>100%的数据中，M，N&lt;=100000</p>
<p>40%的数据中，M，N&lt;=10000</p>
</div>
</div>
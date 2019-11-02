<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小明的花店新开张，为了吸引顾客，他想在花店的门口摆上一排花，共m盆。通过调查顾客的喜好，小明列出了顾客最喜欢的n种花，从1到n标号。为了在门口展出更多种花，规定第i种花不能超过ai盆，摆花时同一种花放在一起，且不同种类的花需按标号的从小到大的顺序依次摆列。</p>
<p>试编程计算，一共有多少种不同的摆花方案。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入共2行。</p>
<p>第一行包含两个正整数n和m，中间用一个空格隔开。</p>
<p>第二行有n个整数，每两个整数之间用一个空格隔开，依次表示a1、a2、……an。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行，一个整数，表示有多少种方案。<strong>注意：因为方案数可能很多，请输出方案数对1000007取模的结果。</strong></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 4</p>
<p>3 2</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【输入输出样例说明】</p>
<p>有2种摆花的方案，分别是(1，1，1，2)，(1，1，2，2)。括号里的1和2表示两种花，比如第一个方案是前三个位置摆第一种花，第四个位置摆第二种花。</p>
<p>【数据范围】</p>
<p>对于20%数据，有0&lt;n≤8，0&lt;m≤8，0≤ai≤8；</p>
<p>对于50%数据，有0&lt;n≤20，0&lt;m≤20，0≤ai≤20；</p>
<p>对于100%数据，有0&lt;n≤100，0&lt;m≤100，0≤ai≤100。</p>
</div>
</div>
<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小春最近很清闲，面对书桌上的 N 张牌，他决定给每张牌染色。目前小春只有 3 种颜色：红色(r)，蓝色(b)，绿色(g)。他询问 Sun有多少种染色方案， Sun很快给出答案。进一步，小春要求染出 Sr张红色，Sb张蓝色，Sg张绿色，他又询问有多少种方案，Sun稍微想了一会儿又给出正确答案。 <br>最后小春发明了 m种不同的洗牌法，这里他又问 Sun有多少种不同的染色方法。两种染色方法相同当且仅当其中一种可以通过任意的洗牌法（即，可以使用多种洗牌法，而每种方法可以使用多次）洗成另一种。Sun 发现这个问题有点难度，决定交给你。答案可能很大，只需求出答案除以 p 的余数（p 为质数）。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行输入 5 个整数：Sr,Sb,Sg,m,p(m&lt;=60,m+1&lt;p&lt;100)。n=Sr+Sb+Sg。接下来 m 行，每行描述一种洗牌法，每行有 n 个用空格隔开的整数 X1X2...Xn，恰为 1 到 n 的一个排列，表示使用这种洗牌法，第 i位变为原来的 Xi位的牌。输入数据保证任意多次洗牌都可用这 m种洗牌法中的一种代替，且对每种洗牌法，都存在一种洗牌法使得能回到原状态。 <br><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>不同的染法总数除以 p的余数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 1 1 2 7 </p>
<p>2 3 1 <br>3 1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>20%数据满足 Sr+Sb+Sg&lt;=20；100%数据满足 Max{Sr,Sb,Sg}&lt;=20。</p>
</div>
</div>
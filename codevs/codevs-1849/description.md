<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>小春现在很清闲,面对书桌上的N张牌,他决定给每张染色,目前小春只有3种颜色:红色,蓝色,绿色.他询问Sun有多少种染色方案,Sun很快就给出了答案.进一步,小春要求染出Sr张红色,Sb张蓝色,Sg张绝色.他又询问有多少种方案,Sun想了一下,又给出了正确答案. 最后小春发明了M种不同的洗牌法,这里他又问Sun有多少种不同的染色方案.两种染色方法相同当且仅当其中一种可以通过任意的洗牌法(即可以使用多种洗牌法,而每种方法可以使用多次)洗成另一种.Sun发现这个问题有点难度,决定交给你,答案可能很大,只要求出答案除以P的余数(P为质数).</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行输入 5 个整数：Sr,Sb,Sg,m,p(m&lt;=60,m+1&lt;p&lt;100)。n=Sr+Sb+Sg。接下来 m 行，每行描述<br>一种洗牌法，每行有 n 个用空格隔开的整数 X1X2...Xn，恰为 1 到 n 的一个排列，表示使用这种洗牌法，<br>第 i位变为原来的 Xi位的牌。输入数据保证任意多次洗牌都可用这 m种洗牌法中的一种代替，且对每种<br>洗牌法，都存在一种洗牌法使得能回到原状态。</p>
<p>100%数据满足 Max{Sr,Sb,Sg}&lt;=20。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>不同染法除以P的余数</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>1 1 1 2 7</span><br><span> 2 3 1</span><br><span> 3 1 2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>有2 种本质上不同的染色法RGB 和RBG，使用洗牌法231 一次可得GBR 和BGR，使用洗牌法312 一次 可得BRG 和GRB。</span></p>
</div>
</div>